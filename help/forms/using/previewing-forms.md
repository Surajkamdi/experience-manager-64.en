---
title: Previewing a form
seo-title: Previewing a form
description: You can preview your forms before publishing or activating to ensure it meets the expectations. Preview options may vary across the supported form types.
seo-description: You can preview your forms before publishing or activating to ensure it meets the expectations. Preview options may vary across the supported form types.
uuid: fd7551e1-93c9-44f5-9475-c51245e8f6e9
products: SG_EXPERIENCEMANAGER/6.4/FORMS
topic-tags: author
discoiquuid: fcc77092-da05-4d11-b1e9-5fe3e15eaecf
---

# Previewing a form{#previewing-a-form}

## Overview {#overview}

In AEM Forms, you can preview the forms and documents present in the repository. Preview helps to know exactly how the forms look and behave when they are released to the end users.

When previewing forms, they are rendered in interactive interface and the user can fill the forms with data. When previewing documents, they are rendered in non-interactive mode and the user can only view the document. For forms, an additional option of Custom Preview is available. Using this option, you can preview the form using data from an XML file. The data fills up some or all of the fields of the form being previewed.

The following table lists the preview options available for different types of supported forms:

<table border="1" cellpadding="1" cellspacing="1" width="100%"> 
 <tbody>
  <tr>
   <td style="text-align: center;"><strong>Asset type</strong><br /> </td> 
   <td style="text-align: center;"><strong>Available preview options</strong><br /> </td> 
  </tr>
  <tr>
   <td>Document</td> 
   <td>PDF preview</td> 
  </tr>
  <tr>
   <td>PDF Form</td> 
   <td>PDF preview and Preview with Data<br /> </td> 
  </tr>
  <tr>
   <td>adaptive form</td> 
   <td>HTML preview and HTML preview with Data</td> 
  </tr>
  <tr>
   <td>Form Template</td> 
   <td>PDF preview, PDF preview with Data, HTML preview, HTML preview with Data<br /> </td> 
  </tr>
 </tbody>
</table>

## Previewing a form {#previewing-a-form}

1. Select an asset you want to preview, and click Preview ![](assets/aem6forms_preview.png) in the actions toolbar.

   >[!NOTE]
   >
   >To select an asset, switch to List view from the default Card view. Click ![](assets/aem6forms_viewlist.png) or ![](assets/aem6forms_viewcard.png) to switch views.

1. Clicking Preview lists the possible preview options applicable for the selected Asset Type. Click the desired option to render the selected asset in a new tab.

   Your options are:

    * Preview as HTML
    * Preview with Data
    * Preview as PDF (available for form templates)

## Preview with Data {#preview-with-data}

When you select **Preview with Data**, you can see how the form looks with real data entered in it. Preview with Data option lets you upload an XML that contains sample user data. The sample user data is used to populate the preview form in the format you choose.

1. Select an asset, click Preview ![](assets/aem6forms_preview.png), and select **Preview with Data**.
1. In the Preview Form dialog, provide FormData as an XML file. Click Preview to render the form with the merged data from XML.
