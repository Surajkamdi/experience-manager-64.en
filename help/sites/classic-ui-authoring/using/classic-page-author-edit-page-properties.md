---
title: Editing Page Properties
seo-title: Editing Page Properties
description: Properties of a page can vary depending on the nature of the page. For example some pages might be connected to a live copy while others are not and the live copy information will be available as appropriate.
seo-description: Properties of a page can vary depending on the nature of the page. For example some pages might be connected to a live copy while others are not and the live copy information will be available as appropriate.
uuid: 7bb4c472-2aa4-4f23-b0b7-8d4d308f4ae2
contentOwner: Chris Bohnert
products: SG_EXPERIENCEMANAGER/6.4/SITES
topic-tags: page-authoring
content-type: reference
discoiquuid: 6dedc49b-46a2-489c-8c69-f237272f3c26
---

# Editing Page Properties{#editing-page-properties}

You can define the required properties for a page. These can vary depending on the nature of the page. For example some pages might be connected to a live copy while others are not and the live copy information will be available as appropriate.

## Page Properties {#page-properties}

The properties are distributed across several tabs:

### Basic {#basic}

* The title of the page is shown in various locations. For example, the **Websites** tab list and the **Sites** card/list views.

  This is a mandatory field.

* Here you can add, or remove tags from the page by updating the list in the selection box:

    * After selecting a tag is it listed below the selection box. You can remove a tag from this list using the x.
    * A completely new tag can be entered by typing the name in an empty selection box.  
      The new tag will actually be created when you hit enter. The new tag will then be shown in a box, with a small star on the right indicating that it is a new tag.
    * With the drop-down functionality you can select from existing tags.
    * An x appears when you mouse-over a tag entry in the selection box; this can be used to remove that tag for this page.

* A toggle switch to indicate whether the page is shown or hidden in the page navigation.
* A title to be used on the page.
* You can specify a separate title for use in the navigation (for example, if you want something more concise). If empty, the **Title** will be used.
* A subtitle for use on the page.
* Your description of the page, its purpose or any other details you want to add.
* The date and time at which the published page will be activated. When published this page will be kept dormant until the specified time.

  Leave these fields empty for pages you want to publish immediately (the normal scenario).

* The time at which the published page will be deactivated.

  Again leave these fields empty for pages you want to publish immediately.

* Allows you to enter a vanity URL for this page. That allows you to have a shorter and more expressive URL.

  For example, if the Vanity URL is set to w `elcome`to the page identified by the path / `v1.0/startpage`for the website h `ttp://example.com,` then h `ttp://example.com/welcome`would be the vanity URL of h `ttp://example.com/content/v1.0/startpage`

  >[!CAUTION]
  >
  >Vanity URLs:
  >
  >    
  >    
  >    * must be unique so you should take care that the value is not already used by another page.
  >    * do not support regex patterns.
  >    
  >

* Indicates whether you want the page to use the vanity URL.

### Advanced {#advanced}

* The page language.
* Indicate the page to which this page should automatically redirect.
* Indicate the [design](../../../sites/developing/using/designer.md) to be used for this page.
* Specify an alias to be used with this page.
* [Define the list of templates that will be available](../../../sites/classic-ui-authoring/using/classic-feature-templates.md#allowingatemplate) within this sub-branch.
* Enables (or disables) use of [closed user groups](../../../sites/administering/using/cug.md) (CUGs).
* The page to be used for login.
* Groups eligible for login to the CUG.
* Realm name for the CUG.
* Specify an export configuration.

### Thumbnail {#thumbnail}

* Shows the page thumbnail image. You can:

    * **Generate Preview** 
      Generate a preview of the page to use as thumbnail.  
    
    * **Upload Image** 
      Upload an image to use as thumbnail.

### Cloud Services {#cloud-services}

* Define properties for [cloud services](../../../sites/developing/using/extending-cloud-config.md).

### Personalization {#personalization}

* Select a [Brand to specify a scope for Targeting](../../../sites/classic-ui-authoring/using/classic-personalization-campaigns.md).

### Permissions {#permissions}

* **Permissions** (touch-optimized UI)

  View the [effective permissions and add new permissions](../../../sites/administering/using/user-group-ac-admin.md).

### Blueprint {#blueprint}

* Define properties for a Blueprint page within [multi-site management](../../../sites/administering/using/msm.md). Controls the circumstances under which modifications will be propagated to the Live Copy.

### Live Copy {#live-copy}

* Define properties for a Live Copy page within [multi-site management](../../../sites/administering/using/msm.md). Controls the circumstances under which modifications will be propagated from the Blueprint.

### Site Structure {#site-structure}

* Provide links to pages that provide site-wide functionality, such as **Signup Page**, **Offline Page**, amongst others.

## Editing Page Properties {#editing-page-properties}

### Editing Page Properties for a Specific Page {#editing-page-properties-for-a-specific-page}

Page Properties define the various properties of the page, such as titles, when they appear on the website and others.

1. Open the page you want to edit.  

1. In the sidekick open the **Page** tab then select **Page Properties...**

   This opens a dialog with multiple tabs.

1. Make the changes you require, then click **OK** to save.
