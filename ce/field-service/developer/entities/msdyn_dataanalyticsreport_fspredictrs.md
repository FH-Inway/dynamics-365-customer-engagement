---
title: "Resource duration (preview) (msdyn_dataanalyticsreport_fspredictrs) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Resource duration (preview) (msdyn_dataanalyticsreport_fspredictrs) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Resource duration (preview) (msdyn_dataanalyticsreport_fspredictrs) table/entity reference (Microsoft Dynamics 365 Field Service)

Resource duration (preview)

## Messages

The following table lists the messages for the Resource duration (preview) (msdyn_dataanalyticsreport_fspredictrs) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: True |`POST` /msdyn_dataanalyticsreport_fspredictrses<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_dataanalyticsreport_fspredictrses(*msdyn_dataanalyticsreport_fspredictrsid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_dataanalyticsreport_fspredictrses(*msdyn_dataanalyticsreport_fspredictrsid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_dataanalyticsreport_fspredictrses<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `SetState`<br />Event: True |`PATCH` /msdyn_dataanalyticsreport_fspredictrses(*msdyn_dataanalyticsreport_fspredictrsid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_dataanalyticsreport_fspredictrses(*msdyn_dataanalyticsreport_fspredictrsid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_dataanalyticsreport_fspredictrses(*msdyn_dataanalyticsreport_fspredictrsid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Resource duration (preview) (msdyn_dataanalyticsreport_fspredictrs) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Resource duration (preview) (msdyn_dataanalyticsreport_fspredictrs) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Resource duration (preview)** |
| **DisplayCollectionName** | **Resource duration (preview)** |
| **SchemaName** | `msdyn_dataanalyticsreport_fspredictrs` |
| **CollectionSchemaName** | `msdyn_dataanalyticsreport_fspredictrses` |
| **EntitySetName** | `msdyn_dataanalyticsreport_fspredictrses`|
| **LogicalName** | `msdyn_dataanalyticsreport_fspredictrs` |
| **LogicalCollectionName** | `msdyn_dataanalyticsreport_fspredictrses` |
| **PrimaryIdAttribute** | `msdyn_dataanalyticsreport_fspredictrsid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsCustomizable](#BKMK_IsCustomizable)
- [msdyn_dataanalyticsreport_fspredictrsId](#BKMK_msdyn_dataanalyticsreport_fspredictrsId)
- [msdyn_dataanalyticsreportid](#BKMK_msdyn_dataanalyticsreportid)
- [msdyn_datainsightsandanalyticsfeatureid](#BKMK_msdyn_datainsightsandanalyticsfeatureid)
- [msdyn_DisplayOrder](#BKMK_msdyn_DisplayOrder)
- [msdyn_IsVisible](#BKMK_msdyn_IsVisible)
- [msdyn_name](#BKMK_msdyn_name)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)

### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|---|---|
|Description|**Sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_IsCustomizable"></a> IsCustomizable

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Is Customizable**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`iscustomizable`|
|RequiredLevel|SystemRequired|
|Type|ManagedProperty|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrsId"></a> msdyn_dataanalyticsreport_fspredictrsId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**DataAnalyticsReport_FSPredictRS**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_dataanalyticsreport_fspredictrsid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_dataanalyticsreportid"></a> msdyn_dataanalyticsreportid

|Property|Value|
|---|---|
|Description|**Data Analytics Report Id**|
|DisplayName|**dataanalyticsreportid**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_dataanalyticsreportid`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|36|

### <a name="BKMK_msdyn_datainsightsandanalyticsfeatureid"></a> msdyn_datainsightsandanalyticsfeatureid

|Property|Value|
|---|---|
|Description|**Lookup to feature entity**|
|DisplayName|**datainsightsandanalyticsfeatureid**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_datainsightsandanalyticsfeatureid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_datainsightsandanalyticsfeature|

### <a name="BKMK_msdyn_DisplayOrder"></a> msdyn_DisplayOrder

|Property|Value|
|---|---|
|Description|**Display Order**|
|DisplayName|**Display Order**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_displayorder`|
|RequiredLevel|ApplicationRequired|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_IsVisible"></a> msdyn_IsVisible

|Property|Value|
|---|---|
|Description|**Is Report Visible**|
|DisplayName|**Is Visible**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_isvisible`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_dataanalyticsreport_fspredictrs_msdyn_isvisible`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_name`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|True|
|MaxLength|100|

### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|---|---|
|Description|**Date and time that the record was migrated.**|
|DisplayName|**Record Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overriddencreatedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the DataAnalyticsReport_FSPredictRS**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_dataanalyticsreport_fspredictrs_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the DataAnalyticsReport_FSPredictRS**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_dataanalyticsreport_fspredictrs_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|1|Label: **Active**<br />State:0<br />TransitionData: None|
|2|Label: **Inactive**<br />State:1<br />TransitionData: None|

### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Time Zone Rule Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`timezoneruleversionnumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|

### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|---|---|
|Description|**Time zone code that was in use when the record was created.**|
|DisplayName|**UTC Conversion Time Zone Code**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`utcconversiontimezonecode`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|


## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** and **IsValidForUpdate**. Listed by **SchemaName**.

- [ComponentIdUnique](#BKMK_ComponentIdUnique)
- [ComponentState](#BKMK_ComponentState)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [IsManaged](#BKMK_IsManaged)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OrganizationId](#BKMK_OrganizationId)
- [OverwriteTime](#BKMK_OverwriteTime)
- [SolutionId](#BKMK_SolutionId)
- [SupportingSolutionId](#BKMK_SupportingSolutionId)
- [VersionNumber](#BKMK_VersionNumber)

### <a name="BKMK_ComponentIdUnique"></a> ComponentIdUnique

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Row id unique**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`componentidunique`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_ComponentState"></a> ComponentState

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Component State**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`componentstate`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue||
|GlobalChoiceName|`componentstate`|

#### ComponentState Choices/Options

|Value|Label|
|---|---|
|0|**Published**|
|1|**Unpublished**|
|2|**Deleted**|
|3|**Deleted Unpublished**|

### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who created the record.**|
|DisplayName|**Created By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was created.**|
|DisplayName|**Created On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who created the record.**|
|DisplayName|**Created By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_IsManaged"></a> IsManaged

|Property|Value|
|---|---|
|Description|**Indicates whether the solution component is part of a managed solution.**|
|DisplayName|**Is Managed**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`ismanaged`|
|RequiredLevel|SystemRequired|
|Type|Boolean|
|GlobalChoiceName|`ismanaged`|
|DefaultValue|False|
|True Label|Managed|
|False Label|Unmanaged|

### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who modified the record.**|
|DisplayName|**Modified By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was modified.**|
|DisplayName|**Modified On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who modified the record.**|
|DisplayName|**Modified By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_OrganizationId"></a> OrganizationId

|Property|Value|
|---|---|
|Description|**Unique identifier for the organization**|
|DisplayName|**Organization Id**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`organizationid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|organization|

### <a name="BKMK_OverwriteTime"></a> OverwriteTime

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Record Overwrite Time**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overwritetime`|
|RequiredLevel|SystemRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_SolutionId"></a> SolutionId

|Property|Value|
|---|---|
|Description|**Unique identifier of the associated solution.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`solutionid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_SupportingSolutionId"></a> SupportingSolutionId

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|`supportingsolutionid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|---|---|
|Description|**Version Number**|
|DisplayName|**Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`versionnumber`|
|RequiredLevel|None|
|Type|BigInt|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [lk_msdyn_dataanalyticsreport_fspredictrs_createdby](#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_createdby)
- [lk_msdyn_dataanalyticsreport_fspredictrs_createdonbehalfby](#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_createdonbehalfby)
- [lk_msdyn_dataanalyticsreport_fspredictrs_modifiedby](#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_modifiedby)
- [lk_msdyn_dataanalyticsreport_fspredictrs_modifiedonbehalfby](#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_modifiedonbehalfby)
- [msdyn_dasfeature_dasfspredictrs_datainsightsandanalyticsfeatureid](#BKMK_msdyn_dasfeature_dasfspredictrs_datainsightsandanalyticsfeatureid)
- [organization_msdyn_dataanalyticsreport_fspredictrs](#BKMK_organization_msdyn_dataanalyticsreport_fspredictrs)

### <a name="BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_createdby"></a> lk_msdyn_dataanalyticsreport_fspredictrs_createdby

One-To-Many Relationship: [systemuser lk_msdyn_dataanalyticsreport_fspredictrs_createdby](systemuser.md#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_createdonbehalfby"></a> lk_msdyn_dataanalyticsreport_fspredictrs_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_dataanalyticsreport_fspredictrs_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_modifiedby"></a> lk_msdyn_dataanalyticsreport_fspredictrs_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_dataanalyticsreport_fspredictrs_modifiedby](systemuser.md#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_modifiedonbehalfby"></a> lk_msdyn_dataanalyticsreport_fspredictrs_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_dataanalyticsreport_fspredictrs_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_dataanalyticsreport_fspredictrs_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_dasfeature_dasfspredictrs_datainsightsandanalyticsfeatureid"></a> msdyn_dasfeature_dasfspredictrs_datainsightsandanalyticsfeatureid

One-To-Many Relationship: [msdyn_datainsightsandanalyticsfeature msdyn_dasfeature_dasfspredictrs_datainsightsandanalyticsfeatureid](msdyn_datainsightsandanalyticsfeature.md#BKMK_msdyn_dasfeature_dasfspredictrs_datainsightsandanalyticsfeatureid)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_datainsightsandanalyticsfeature`|
|ReferencedAttribute|`msdyn_datainsightsandanalyticsfeatureid`|
|ReferencingAttribute|`msdyn_datainsightsandanalyticsfeatureid`|
|ReferencingEntityNavigationPropertyName|`msdyn_datainsightsandanalyticsfeatureid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_organization_msdyn_dataanalyticsreport_fspredictrs"></a> organization_msdyn_dataanalyticsreport_fspredictrs

One-To-Many Relationship: [organization organization_msdyn_dataanalyticsreport_fspredictrs](organization.md#BKMK_organization_msdyn_dataanalyticsreport_fspredictrs)

|Property|Value|
|---|---|
|ReferencedEntity|`organization`|
|ReferencedAttribute|`organizationid`|
|ReferencingAttribute|`organizationid`|
|ReferencingEntityNavigationPropertyName|`organizationid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_dataanalyticsreport_fspredictrs_AsyncOperations](#BKMK_msdyn_dataanalyticsreport_fspredictrs_AsyncOperations)
- [msdyn_dataanalyticsreport_fspredictrs_BulkDeleteFailures](#BKMK_msdyn_dataanalyticsreport_fspredictrs_BulkDeleteFailures)
- [msdyn_dataanalyticsreport_fspredictrs_DuplicateBaseRecord](#BKMK_msdyn_dataanalyticsreport_fspredictrs_DuplicateBaseRecord)
- [msdyn_dataanalyticsreport_fspredictrs_DuplicateMatchingRecord](#BKMK_msdyn_dataanalyticsreport_fspredictrs_DuplicateMatchingRecord)
- [msdyn_dataanalyticsreport_fspredictrs_MailboxTrackingFolders](#BKMK_msdyn_dataanalyticsreport_fspredictrs_MailboxTrackingFolders)
- [msdyn_dataanalyticsreport_fspredictrs_PrincipalObjectAttributeAccesses](#BKMK_msdyn_dataanalyticsreport_fspredictrs_PrincipalObjectAttributeAccesses)
- [msdyn_dataanalyticsreport_fspredictrs_ProcessSession](#BKMK_msdyn_dataanalyticsreport_fspredictrs_ProcessSession)
- [msdyn_dataanalyticsreport_fspredictrs_SyncErrors](#BKMK_msdyn_dataanalyticsreport_fspredictrs_SyncErrors)

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_AsyncOperations"></a> msdyn_dataanalyticsreport_fspredictrs_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_dataanalyticsreport_fspredictrs_AsyncOperations](asyncoperation.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_BulkDeleteFailures"></a> msdyn_dataanalyticsreport_fspredictrs_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_dataanalyticsreport_fspredictrs_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_DuplicateBaseRecord"></a> msdyn_dataanalyticsreport_fspredictrs_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_dataanalyticsreport_fspredictrs_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_DuplicateMatchingRecord"></a> msdyn_dataanalyticsreport_fspredictrs_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_dataanalyticsreport_fspredictrs_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_MailboxTrackingFolders"></a> msdyn_dataanalyticsreport_fspredictrs_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_dataanalyticsreport_fspredictrs_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_PrincipalObjectAttributeAccesses"></a> msdyn_dataanalyticsreport_fspredictrs_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_dataanalyticsreport_fspredictrs_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_ProcessSession"></a> msdyn_dataanalyticsreport_fspredictrs_ProcessSession

Many-To-One Relationship: [processsession msdyn_dataanalyticsreport_fspredictrs_ProcessSession](processsession.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dataanalyticsreport_fspredictrs_SyncErrors"></a> msdyn_dataanalyticsreport_fspredictrs_SyncErrors

Many-To-One Relationship: [syncerror msdyn_dataanalyticsreport_fspredictrs_SyncErrors](syncerror.md#BKMK_msdyn_dataanalyticsreport_fspredictrs_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dataanalyticsreport_fspredictrs_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

