---
title: "Queue Item (QueueItem) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Queue Item (QueueItem) table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Queue Item (QueueItem) table/entity reference (Microsoft Dynamics 365 Customer Service)

A specific item in a queue, such as a case record or an activity record.

> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Queue Item (QueueItem) table extends the [Microsoft Dynamics 365 Queue Item (QueueItem) table](/dynamics365/developer/reference/entities/queueitem).



## Customized columns/attributes

Microsoft Dynamics 365 Customer Service modifies the definition of columns/attributes defined in other solutions. Listed by **SchemaName**.

- [ObjectId](#BKMK_ObjectId)
- [ObjectTypeCode](#BKMK_ObjectTypeCode)

### <a name="BKMK_ObjectId"></a> ObjectId

Changes from [ObjectId (Microsoft Dataverse)](/power-apps/developer/data-platform/reference/entities/queueitem#BKMK_ObjectId)

|Property|Value|
|---|---|
|Targets|msdyn_bookingalert, msdyn_ocoutboundmessage, msdyn_timegroup, msdyn_timegroupdetail|


### <a name="BKMK_ObjectTypeCode"></a> ObjectTypeCode

Changes from [ObjectTypeCode (Microsoft Dataverse)](/power-apps/developer/data-platform/reference/entities/queueitem#BKMK_ObjectTypeCode)

#### ObjectTypeCode Choices/Options

|Value|Label|
|---|---|
|10224|**Teams chat**|
|10240|**Knowledge Article Template**|
|10359|**Invite Redemption**|
|10360|**Portal Comment**|
|10456|**IoT Alert**|
|10667|**Customer Voice alert**|
|10677|**Customer Voice survey invite**|
|10679|**Customer Voice survey response**|
|10736|**Overflow Action Config**|
|10760|**Ongoing conversation (Deprecated)**|
|10772|**Conversation**|
|10789|**Session**|
|10993|**Copilot Transcript**|
|11089|**Booking Alert**|
|11106|**Fulfillment Preference**|
|11107|**Time Group Detail**|
|11168|**Outbound message**|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [msdyn_bookingalert_QueueItems](#BKMK_msdyn_bookingalert_QueueItems)
- [msdyn_ocoutboundmessage_QueueItems](#BKMK_msdyn_ocoutboundmessage_QueueItems)
- [msdyn_timegroup_QueueItems](#BKMK_msdyn_timegroup_QueueItems)
- [msdyn_timegroupdetail_QueueItems](#BKMK_msdyn_timegroupdetail_QueueItems)

### <a name="BKMK_msdyn_bookingalert_QueueItems"></a> msdyn_bookingalert_QueueItems

One-To-Many Relationship: [msdyn_bookingalert msdyn_bookingalert_QueueItems](msdyn_bookingalert.md#BKMK_msdyn_bookingalert_QueueItems)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_bookingalert`|
|ReferencedAttribute|`activityid`|
|ReferencingAttribute|`objectid`|
|ReferencingEntityNavigationPropertyName|`objectid_msdyn_bookingalert`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_ocoutboundmessage_QueueItems"></a> msdyn_ocoutboundmessage_QueueItems

One-To-Many Relationship: [msdyn_ocoutboundmessage msdyn_ocoutboundmessage_QueueItems](msdyn_ocoutboundmessage.md#BKMK_msdyn_ocoutboundmessage_QueueItems)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_ocoutboundmessage`|
|ReferencedAttribute|`activityid`|
|ReferencingAttribute|`objectid`|
|ReferencingEntityNavigationPropertyName|`objectid_msdyn_ocoutboundmessage`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_timegroup_QueueItems"></a> msdyn_timegroup_QueueItems

One-To-Many Relationship: [msdyn_timegroup msdyn_timegroup_QueueItems](msdyn_timegroup.md#BKMK_msdyn_timegroup_QueueItems)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_timegroup`|
|ReferencedAttribute|`msdyn_timegroupid`|
|ReferencingAttribute|`objectid`|
|ReferencingEntityNavigationPropertyName|`objectid_msdyn_timegroup`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_timegroupdetail_QueueItems"></a> msdyn_timegroupdetail_QueueItems

One-To-Many Relationship: [msdyn_timegroupdetail msdyn_timegroupdetail_QueueItems](msdyn_timegroupdetail.md#BKMK_msdyn_timegroupdetail_QueueItems)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_timegroupdetail`|
|ReferencedAttribute|`msdyn_timegroupdetailid`|
|ReferencingAttribute|`objectid`|
|ReferencingEntityNavigationPropertyName|`objectid_msdyn_timegroupdetail`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.queueitem?displayProperty=fullName>
