---
title: "Action Card (ActionCard) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Action Card (ActionCard) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Action Card (ActionCard) table/entity reference (Microsoft Dynamics 365 Field Service)

Action card entity to show action cards.

> [!NOTE]
> The Microsoft Dynamics 365 Field Service Action Card (ActionCard) table extends the [Microsoft Dynamics 365 Action Card (ActionCard) table](/dynamics365/developer/entities/actioncard).



## Customized columns/attributes

Microsoft Dynamics 365 Field Service modifies the definition of columns/attributes defined in other solutions. Listed by **SchemaName**.

### <a name="BKMK_RegardingObjectId"></a> RegardingObjectId

Changes from [RegardingObjectId (Microsoft Dataverse)](/power-apps/developer/data-platform/reference/entities/actioncard#BKMK_RegardingObjectId)

|Property|Value|
|---|---|
|Targets|msdyn_bookingalert|


## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

### <a name="BKMK_msdyn_bookingalert_ActionCards"></a> msdyn_bookingalert_ActionCards

One-To-Many Relationship: [msdyn_bookingalert msdyn_bookingalert_ActionCards](msdyn_bookingalert.md#BKMK_msdyn_bookingalert_ActionCards)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_bookingalert`|
|ReferencedAttribute|`activityid`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencingEntityNavigationPropertyName|`regardingobjectid_msdyn_bookingalert`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.actioncard?displayProperty=fullName>
