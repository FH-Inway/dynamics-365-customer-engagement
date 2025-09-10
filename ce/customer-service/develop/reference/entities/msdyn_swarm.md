---
title: "Swarm (msdyn_swarm) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Swarm (msdyn_swarm) table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Swarm (msdyn_swarm) table/entity reference (Microsoft Dynamics 365 Customer Service)

Tracks the list of swarms created by agents to resolve the customer issues

> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Swarm (msdyn_swarm) table extends the [Microsoft Dynamics 365 Swarm (msdyn_swarm) table](/dynamics365/developer/reference/entities/msdyn_swarm).




## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_swarm_msdyn_bookingalerts](#BKMK_msdyn_swarm_msdyn_bookingalerts)
- [msdyn_swarm_msdyn_ocoutboundmessages](#BKMK_msdyn_swarm_msdyn_ocoutboundmessages)
- [msdyn_swarm_msdyn_ocvoicemails](#BKMK_msdyn_swarm_msdyn_ocvoicemails)

### <a name="BKMK_msdyn_swarm_msdyn_bookingalerts"></a> msdyn_swarm_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert msdyn_swarm_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_msdyn_swarm_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarm_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarm_msdyn_ocoutboundmessages"></a> msdyn_swarm_msdyn_ocoutboundmessages

Many-To-One Relationship: [msdyn_ocoutboundmessage msdyn_swarm_msdyn_ocoutboundmessages](msdyn_ocoutboundmessage.md#BKMK_msdyn_swarm_msdyn_ocoutboundmessages)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocoutboundmessage`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarm_msdyn_ocoutboundmessages`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarm_msdyn_ocvoicemails"></a> msdyn_swarm_msdyn_ocvoicemails

Many-To-One Relationship: [msdyn_ocvoicemail msdyn_swarm_msdyn_ocvoicemails](msdyn_ocvoicemail.md#BKMK_msdyn_swarm_msdyn_ocvoicemails)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocvoicemail`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarm_msdyn_ocvoicemails`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

