---
title: CCA Hosted Application (Hosted Control) 
description: Learn about the Customer Care Accelerator (CCA) Hosted Application hosted control type and how you can create the hosted control in Unified Service Desk.
ms.date: 05/15/2025
ms.topic: reference
author: gandhamm
ms.author: mgandham
ms.reviewer: mgandham
search.audienceType: 
  - customizer
  - developer
ms.custom: evergreen
---
# CCA Hosted Application (Hosted Control)
A Customer Care Accelerator (CCA) hosted application hosted control enables you to host an external application or web application in [!INCLUDE[pn_unified_service_desk](../includes/pn-unified-service-desk.md)] and interact with it by using the [UII adapters](../unified-service-desk/uii-adapters.md). It's also used for hosting the control that connects [!INCLUDE[pn_unified_service_desk](../includes/pn-unified-service-desk.md)] with a [!INCLUDE[pn_computer_telephony_integration_cti](../includes/pn-computer-telephony-integration-cti.md)] system.

 This type of hosted control also provides the link to traditional CCA hosted applications. For more information about building a CCA hosted application, see the **CCA Deployment Guide** in the [!INCLUDE[pn_user_inteface_integration_uii](../includes/pn-user-interface-integration-uii.md)] SDK [download package](https://go.microsoft.com/fwlink/p/?LinkId=519179).

<a name="Create"></a>
## Create a CCA Hosted Application hosted control
 You create a hosted control type of **CCA Hosted Application** to host a [!INCLUDE[pn_uii_acronym](../includes/pn-uii-acronym.md)] hosted application. A [!INCLUDE[pn_uii_acronym](../includes/pn-uii-acronym.md)] hosted application is a user control that can be used to host external, web, remote, and custom applications within [!INCLUDE[pn_unified_service_desk](../includes/pn-unified-service-desk.md)]. For information about using [!INCLUDE[pn_uii_acronym](../includes/pn-uii-acronym.md)] hosted applications, see [Integrate with external applications and web applications](../unified-service-desk/integrate-external-applications-web-applications.md).

 While creating a new hosted control, the fields in the **New Hosted Control** screen vary based on the type of hosted control you want to create. For detailed information about the information that you need to specify for each field for creating a **CCA Hosted Application** type of hosted control, see [Create and manage UII hosted applications](../unified-service-desk/create-manage-uii-hosted-applications.md).

> [!NOTE]
>  The **CCA Hosted Application** hosted control type has many limitations as it relates to the [!INCLUDE[pn_unified_service_desk](../includes/pn-unified-service-desk.md)] functionality. In particular, these hosted controls don’t fire events. While it’s possible for these controls to fire events into [!INCLUDE[pn_unified_service_desk](../includes/pn-unified-service-desk.md)], it isn’t automatic like it would be for other [!INCLUDE[pn_unified_service_desk](../includes/pn-unified-service-desk.md)] hosted controls.

<a name="actions"></a>
## Predefined UII actions
 The developer of the [!INCLUDE[pn_uii_acronym](../includes/pn-uii-acronym.md)] hosted application decides which actions should be added to the control.

### See also
 [Create and manage UII hosted applications](../unified-service-desk/create-manage-uii-hosted-applications.md)
 [Use UII adapters to interact with external and web applications](../unified-service-desk/use-uii-adapters-interact-external-web-applications.md)
 [Use UII automation adapters to interact with external and web applications](../unified-service-desk/use-uii-automation-adapter-interact-external-web-applications.md)
 [Use UII hosted controls with Unified Service Desk](../unified-service-desk/use-uii-hosted-controls-unified-service-desk.md)
 [Integrate with CTI systems using CTI adapters](../unified-service-desk/integrate-cti-systems-cti-adapters.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]
