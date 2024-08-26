---
title: "Opportunity table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Opportunity table/entity with Microsoft Dynamics 365 Customer Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Opportunity table/entity reference (Microsoft Dynamics 365 Customer Service)

Potential revenue-generating event, or sale to an account, which needs to be tracked through a sales process to completion.

> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Opportunity table extends the [Microsoft Dynamics 365 Opportunity table](/dynamics365/developer/entities/opportunity).




## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

### <a name="BKMK_transactioncurrency_opportunity"></a> transactioncurrency_opportunity

One-To-Many Relationship: [transactioncurrency transactioncurrency_opportunity](transactioncurrency.md#BKMK_transactioncurrency_opportunity)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

### <a name="BKMK_opportunity_msdyn_bookingalerts"></a> opportunity_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert opportunity_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_opportunity_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`opportunity_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: `CRMActivity.RollupByParty`<br />ViewId: `00000000-0000-0000-00aa-000010001903`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

