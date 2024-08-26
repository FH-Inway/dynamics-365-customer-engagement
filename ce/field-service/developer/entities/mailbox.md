---
title: "Mailbox table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Mailbox table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Mailbox table/entity reference



> [!NOTE]
> The Microsoft Dynamics 365 Field Service Mailbox table extends the [Microsoft Dynamics 365 Mailbox table](/dynamics365/developer/entities/mailbox).




## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

### <a name="BKMK_msdyn_bookingalert_mailbox_sendermailboxid"></a> msdyn_bookingalert_mailbox_sendermailboxid

Many-To-One Relationship: [msdyn_bookingalert msdyn_bookingalert_mailbox_sendermailboxid](msdyn_bookingalert.md#BKMK_msdyn_bookingalert_mailbox_sendermailboxid)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`sendermailboxid`|
|ReferencedEntityNavigationPropertyName|`msdyn_bookingalert_mailbox_sendermailboxid`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.mailbox?displayProperty=fullName>
