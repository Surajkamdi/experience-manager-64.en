---
title: Set up the Android studio project and build the Android app
seo-title: Set up the Android studio project and build the Android app
description: Steps to set up the Android Studio project and build the installer for the AEM Forms app
seo-description: Steps to set up the Android Studio project and build the installer for the AEM Forms app
uuid: ff9d44a5-a112-405d-849b-ff7113b26cb3
content-type: reference
products: SG_EXPERIENCEMANAGER/6.3/FORMS
topic-tags: forms-app
discoiquuid: 5aadf09c-7700-4cfc-a5ac-016d19de3add
---

# Set up the Android studio project and build the Android app{#set-up-the-android-studio-project-and-build-the-android-app}

| This article is for building the AEM Forms App 6.3.1.1 and later versions. For building an app from source code of source code of the AEM Forms App 6.3, see [Set up the Eclipse project and build the Android™ app](../../forms/using/setup-eclipse-project-build-installer.md). |
|---|

AEM Forms provides the complete source code of the AEM Forms app. The source contains all components to build a custom AEM Forms app. The source code archive, `adobe-lc-mobileworkspace-src-<version>.zip` is a part of the `adobe-aemfd-forms-app-src-pkg-<version>.zip` package on package share.

To get the AEM Forms app source, perform the following steps:

1. Navigate to package share  
   URL: `http://<server>:<port>/crx/packageshare`.

1. Download the source package. When you download the package, it is added in your AEM Forms package manager.
1. After it is downloaded, navigate to: `http://<server>:<port>/crx/packmgr/index.jsp`, and install `adobe-aemfd-forms-app-src-pkg-<version>.zip`.

1. To download the source-code archive, open `http://<server>:<port>/crx/de/content/forms/mobileapps/src/adobe-lc-mobileworkspace-src-<version>.zip` in your browser.   
   The source package is downloaded on your device.

The following image displays the extracted contents of the `adobe-lc-mobileworkspace-src-<version>.zip`.

![Extracted contents of the zipped Android™ source](assets/mws-content-1.png)

The following image displays the directory structure of the `android`folder in the `src`folder.

![Directory structure of the android folder in src](assets/android-folder.png) 

## Build standard AEM Forms app <br> {#set-up-the-xcode-project}

1. Perform the following steps to set up a project in Android™ Studio and provide a signing identity:

   Log in to a machine that has Android™ Studio installed and configured.

1. Copy the downloaded `adobe-lc-mobileworkspace-src-<version>.zip` archive to:

   **For MAC users**: `[User_Home]/Projects`

   **For Windows® users**: `%HOMEPATH%\Projects`

   >[!NOTE]
   >
   >For Windows®, it is recommended that you keep the android project in the system drive.

1. Extract the archive in the following directory:

   **For MAC users**: `[User_Home]/Projects/[your-project]`

   **For Windows® users**: `%HOMEPATH%\Projects\[your-project]`

   >[!NOTE]
   >
   >It is recommended, that you keep the extracted android project in the system drive before importing the project into Android Studio.

1. Launch Android™ Studio.

   **For MAC users**: Update the `local.properties` file present in the `[User_Home]/Projects/[your-project]/android` folder and point the `sdk.dir` variable to `SDK` location on your desktop.

   **For Windows® users**: Update the `local.properties` file present in the `%HOMEPATH%\Projects\[your-project]\android` folder and point the `sdk.dir` variable to `SDK` location on your desktop.

1. Click **[!UICONTROL Finish]**to build the project.

   The project is available in the ADT Project Explorer.

   ![eclipse project after building the app](assets/eclipsebuildmws.png)

1. In Android™ Studio, select **[!UICONTROL Import Project (Eclipse ADT, Gradle, Etc.)]**.
1. In the project explorer, select the root directory of the project that you want to build in the **Root Directory** text box:

   **For Mac users:** [User_Home]/Projects/MobileWorkspace/src/android

   **For Windows® users:** %HOMEPATH%\Projects\MobileWorkspace\src\android

1. After the project is imported, a pop-up appears with option to update the Android™ plugin Gradle. Click the appropriate button depending on your requirement.

   ![](assets/dontremindmeagainforthisproject.png)

1. After successful gradle build, the following screen appears. Connect the appropriate device or emulator with the system and click **[!UICONTROL Run Android™]**.  
   ****

   ![](assets/gradleconsole.png)

1. Android™ Studio displays the connected devices and available emulators. Select the device on which you want to run the application and then click **OK**.  
   ****

   ![](assets/connecteddevice.png)

After you have built the project, you can choose to install the app using Android™ Debug Bridge or Android™ Studio.

### Using Android™ Debug Bridge {#andriod-debug-bridge}

You can install the application on an Android™ device via the [Android™ Debug Bridge](http://developer.android.com/tools/help/adb.html) with the following command:

**For MAC users**: `adb install [User_Home]/Projects/[your-project]/adobe-lc-mobileworkspace-src-[version]/android/build/outputs/apk/android-debug.apk`

**For Windows® users**: `adb install %HOMEPATH%\Projects\[your-project]\adobe-lc-mobileworkspace-src-[version]\android\build\outputs\apk\android-debug.apk`

[**Contact Support**](https://www.adobe.com/account/sign-in.supportportal.html)