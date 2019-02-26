---
title: Configuring Remoting endpoints
seo-title: Configuring Remoting endpoints
description: Learn how to configure remoting endpoints.
seo-description: Learn how to configure remoting endpoints.
uuid: 271e1d83-4ae9-426d-828b-0ad7eca6f5e5
contentOwner: admin
content-type: reference
geptopics: SG_AEMFORMS/categories/managing_endpoints
products: SG_EXPERIENCEMANAGER/6.4/FORMS
discoiquuid: fee34bd4-9168-4880-a5de-8895d3f39d48
---

# Configuring Remoting endpoints{#configuring-remoting-endpoints}

A remoting endpoint enables an application built with Flex to invoke the service using (Deprecated for AEM forms) AEM forms Remoting. A remoting endpoint is automatically created for each activated service. A Flex destination that has the same name as the endpoint is created, and Flex clients can create remote objects that point to this destination to invoke operations on the relevant service.

## Remoting endpoint settings {#remoting-endpoint-settings}

**Flex Client Authentication Method:** Determines the type of response that the server sends back to the client when the invoked service is security enabled, the operation invoked does not support anonymous invocations, and the client passes in either no or invalid credentials.