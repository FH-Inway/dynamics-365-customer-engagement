---
title: "Customer Voice survey invite (msfp_surveyinvite) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Customer Voice survey invite (msfp_surveyinvite) table/entity with Microsoft Dynamics 365 Customer Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Customer Voice survey invite (msfp_surveyinvite) table/entity reference (Microsoft Dynamics 365 Customer Service)

Activity that tracks a survey invitation sent to a person.

> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Customer Voice survey invite (msfp_surveyinvite) table extends the [Microsoft Dynamics 365 Customer Voice survey invite (msfp_surveyinvite) table](/dynamics365/developer/entities/msfp_surveyinvite).



## Customized columns/attributes

Microsoft Dynamics 365 Customer Service modifies the definition of columns/attributes defined in other solutions. Listed by **SchemaName**.

### <a name="BKMK_RegardingObjectId"></a> RegardingObjectId

Changes from [RegardingObjectId (Microsoft Dynamics 365)](/dynamics365/developer/entities/msfp_surveyinvite#BKMK_RegardingObjectId)

|Property|Value|
|---|---|
|Targets|msdyn_bookingalertstatus|


## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [msdyn_bookingalertstatus_msfp_surveyinvites](#BKMK_msdyn_bookingalertstatus_msfp_surveyinvites)
- [msdyn_bookingrule_msfp_surveyinvites](#BKMK_msdyn_bookingrule_msfp_surveyinvites)
- [msdyn_resourceterritory_msfp_surveyinvites](#BKMK_msdyn_resourceterritory_msfp_surveyinvites)
- [msdyn_systemuserschedulersetting_msfp_surveyinvites](#BKMK_msdyn_systemuserschedulersetting_msfp_surveyinvites)
- [msdyn_timegroup_msfp_surveyinvites](#BKMK_msdyn_timegroup_msfp_surveyinvites)
- [msdyn_timegroupdetail_msfp_surveyinvites](#BKMK_msdyn_timegroupdetail_msfp_surveyinvites)
- [msfp_surveyinvite_transactioncurrency_transactioncurrencyid](#BKMK_msfp_surveyinvite_transactioncurrency_transactioncurrencyid)

### <a name="BKMK_msdyn_bookingalertstatus_msfp_surveyinvites"></a> msdyn_bookingalertstatus_msfp_surveyinvites

One-To-Many Relationship: [msdyn_bookingalertstatus msdyn_bookingalertstatus_msfp_surveyinvites](msdyn_bookingalertstatus.md#BKMK_msdyn_bookingalertstatus_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_bookingalertstatus`|
|ReferencedAttribute|`msdyn_bookingalertstatusid`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencingEntityNavigationPropertyName|`regardingobjectid_msdyn_bookingalertstatus_msfp_surveyinvite`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_bookingrule_msfp_surveyinvites"></a> msdyn_bookingrule_msfp_surveyinvites

One-To-Many Relationship: [msdyn_bookingrule msdyn_bookingrule_msfp_surveyinvites](msdyn_bookingrule.md#BKMK_msdyn_bookingrule_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_bookingrule`|
|ReferencedAttribute|`msdyn_bookingruleid`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencingEntityNavigationPropertyName|`regardingobjectid_msdyn_bookingrule_msfp_surveyinvite`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_resourceterritory_msfp_surveyinvites"></a> msdyn_resourceterritory_msfp_surveyinvites

One-To-Many Relationship: [msdyn_resourceterritory msdyn_resourceterritory_msfp_surveyinvites](msdyn_resourceterritory.md#BKMK_msdyn_resourceterritory_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_resourceterritory`|
|ReferencedAttribute|`msdyn_resourceterritoryid`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencingEntityNavigationPropertyName|`regardingobjectid_msdyn_resourceterritory_msfp_surveyinvite`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_systemuserschedulersetting_msfp_surveyinvites"></a> msdyn_systemuserschedulersetting_msfp_surveyinvites

One-To-Many Relationship: [msdyn_systemuserschedulersetting msdyn_systemuserschedulersetting_msfp_surveyinvites](msdyn_systemuserschedulersetting.md#BKMK_msdyn_systemuserschedulersetting_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_systemuserschedulersetting`|
|ReferencedAttribute|`msdyn_systemuserschedulersettingid`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencingEntityNavigationPropertyName|`regardingobjectid_msdyn_systemuserschedulersetting_msfp_surveyinvite`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_timegroup_msfp_surveyinvites"></a> msdyn_timegroup_msfp_surveyinvites

One-To-Many Relationship: [msdyn_timegroup msdyn_timegroup_msfp_surveyinvites](msdyn_timegroup.md#BKMK_msdyn_timegroup_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_timegroup`|
|ReferencedAttribute|`msdyn_timegroupid`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencingEntityNavigationPropertyName|`regardingobjectid_msdyn_timegroup_msfp_surveyinvite`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_timegroupdetail_msfp_surveyinvites"></a> msdyn_timegroupdetail_msfp_surveyinvites

One-To-Many Relationship: [msdyn_timegroupdetail msdyn_timegroupdetail_msfp_surveyinvites](msdyn_timegroupdetail.md#BKMK_msdyn_timegroupdetail_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_timegroupdetail`|
|ReferencedAttribute|`msdyn_timegroupdetailid`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencingEntityNavigationPropertyName|`regardingobjectid_msdyn_timegroupdetail_msfp_surveyinvite`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msfp_surveyinvite_transactioncurrency_transactioncurrencyid"></a> msfp_surveyinvite_transactioncurrency_transactioncurrencyid

One-To-Many Relationship: [transactioncurrency msfp_surveyinvite_transactioncurrency_transactioncurrencyid](transactioncurrency.md#BKMK_msfp_surveyinvite_transactioncurrency_transactioncurrencyid)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid_msfp_surveyinvite`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

