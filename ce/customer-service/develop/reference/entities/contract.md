---
title: "Contract table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Contract table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Contract table/entity reference (Microsoft Dynamics 365 Customer Service)

Agreement to provide customer service during a specified amount of time or number of cases.

> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Contract table extends the [Microsoft Dynamics 365 Contract table](/dynamics365/developer/reference/entities/contract).




## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [contract_msdyn_bookingalerts](#BKMK_contract_msdyn_bookingalerts)
- [contract_msdyn_ocoutboundmessages](#BKMK_contract_msdyn_ocoutboundmessages)

### <a name="BKMK_contract_msdyn_bookingalerts"></a> contract_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert contract_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_contract_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`contract_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_contract_msdyn_ocoutboundmessages"></a> contract_msdyn_ocoutboundmessages

Many-To-One Relationship: [msdyn_ocoutboundmessage contract_msdyn_ocoutboundmessages](msdyn_ocoutboundmessage.md#BKMK_contract_msdyn_ocoutboundmessages)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocoutboundmessage`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`contract_msdyn_ocoutboundmessages`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

