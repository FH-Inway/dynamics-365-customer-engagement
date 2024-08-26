---
title: "Recurring Sales Action V2 (msdyn_recurringsalesactionv2) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Recurring Sales Action V2 (msdyn_recurringsalesactionv2) table/entity with Microsoft Dynamics 365."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Recurring Sales Action V2 (msdyn_recurringsalesactionv2) table/entity reference



## Messages

The following table lists the messages for the Recurring Sales Action V2 (msdyn_recurringsalesactionv2) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: True |`POST` /msdyn_recurringsalesactionsv2<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_recurringsalesactionsv2(*msdyn_recurringsalesactionv2id*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_recurringsalesactionsv2(*msdyn_recurringsalesactionv2id*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_recurringsalesactionsv2<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `SetState`<br />Event: True |`PATCH` /msdyn_recurringsalesactionsv2(*msdyn_recurringsalesactionv2id*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_recurringsalesactionsv2(*msdyn_recurringsalesactionv2id*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_recurringsalesactionsv2(*msdyn_recurringsalesactionv2id*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Recurring Sales Action V2 (msdyn_recurringsalesactionv2) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Recurring Sales Action V2 (msdyn_recurringsalesactionv2) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Recurring Sales Action V2** |
| **DisplayCollectionName** | **Recurring Sales Actions V2** |
| **SchemaName** | `msdyn_recurringsalesactionv2` |
| **CollectionSchemaName** | `msdyn_recurringsalesactionv2s` |
| **EntitySetName** | `msdyn_recurringsalesactionsv2`|
| **LogicalName** | `msdyn_recurringsalesactionv2` |
| **LogicalCollectionName** | `msdyn_recurringsalesactionv2s` |
| **PrimaryIdAttribute** | `msdyn_recurringsalesactionv2id` |
| **PrimaryNameAttribute** |`msdyn_triggername` |
| **TableType** | `Standard` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_CustomActionName](#BKMK_msdyn_CustomActionName)
- [msdyn_FailureCount](#BKMK_msdyn_FailureCount)
- [msdyn_FeatureName](#BKMK_msdyn_FeatureName)
- [msdyn_IsRecurrencePatternSchedule](#BKMK_msdyn_IsRecurrencePatternSchedule)
- [msdyn_LastExecutionInfo](#BKMK_msdyn_LastExecutionInfo)
- [msdyn_Payload](#BKMK_msdyn_Payload)
- [msdyn_RecordState](#BKMK_msdyn_RecordState)
- [msdyn_recurringsalesactionv2Id](#BKMK_msdyn_recurringsalesactionv2Id)
- [msdyn_RetryCount](#BKMK_msdyn_RetryCount)
- [msdyn_Schedule](#BKMK_msdyn_Schedule)
- [msdyn_StartDate](#BKMK_msdyn_StartDate)
- [msdyn_TriggerName](#BKMK_msdyn_TriggerName)
- [msdyn_WorkloadName](#BKMK_msdyn_WorkloadName)
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

### <a name="BKMK_msdyn_CustomActionName"></a> msdyn_CustomActionName

|Property|Value|
|---|---|
|Description||
|DisplayName|**Custom Action Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_customactionname`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|200|

### <a name="BKMK_msdyn_FailureCount"></a> msdyn_FailureCount

|Property|Value|
|---|---|
|Description|**Failure Count is used while recreating the missing jobs.**|
|DisplayName|**Failure Count**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_failurecount`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_FeatureName"></a> msdyn_FeatureName

|Property|Value|
|---|---|
|Description||
|DisplayName|**Feature Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_featurename`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_recurringsalesactionv2_msdyn_featurename`|

#### msdyn_FeatureName Choices/Options

|Value|Label|
|---|---|
|0|**Scheduled Scoring**|
|1|**Scheduled Assignment**|
|2|**Scheduled Maintenance**|
|3|**Recurrent Assignment**|
|4|**Recurrent Duplicate Detection**|
|5|**Sales Accelerator Mail Notification to Admin**|
|6|**Scheduled DataHygiene Validation Trigger**|
|7|**Scheduled DataHygiene Validation**|
|8|**Restore Missing RSA Triggers**|
|9|**Sync CRUD Data to CDS Validation**|
|10|**Sync CRUD Data to CDS**|
|11|**Sales Cxp provisioning trigger**|
|12|**Sales analytics provisioning trigger**|
|13|**Digital selling task maintenance job**|
|14|**OOB Suggestions Athena Sync Status**|
|15|**Relationship Analytics**|
|16|**Predictive Forecasting**|
|17|**Work assignment user membership trigger**|
|18|**Manual Forecasting**|

### <a name="BKMK_msdyn_IsRecurrencePatternSchedule"></a> msdyn_IsRecurrencePatternSchedule

|Property|Value|
|---|---|
|Description|**Indicates whether the schedule is of Recurrence Pattern type.**|
|DisplayName|**Is Recurrence Pattern Schedule**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_isrecurrencepatternschedule`|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|
|GlobalChoiceName|`msdyn_recurringsalesactionv2_msdyn_isrecurrencepatternschedule`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_LastExecutionInfo"></a> msdyn_LastExecutionInfo

|Property|Value|
|---|---|
|Description||
|DisplayName|**Last Execution Info**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_lastexecutioninfo`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|4000|

### <a name="BKMK_msdyn_Payload"></a> msdyn_Payload

|Property|Value|
|---|---|
|Description|**Input Data for the Custom Action**|
|DisplayName|**Payload**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_payload`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|4000|

### <a name="BKMK_msdyn_RecordState"></a> msdyn_RecordState

|Property|Value|
|---|---|
|Description|**State of the record with respect to Jobs Service**|
|DisplayName|**Record State**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_recordstate`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_recurringsalesactionv2_msdyn_recordstate`|

#### msdyn_RecordState Choices/Options

|Value|Label|
|---|---|
|0|**Created**|
|1|**Missing**|

### <a name="BKMK_msdyn_recurringsalesactionv2Id"></a> msdyn_recurringsalesactionv2Id

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Recurring Sales Action V2**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_recurringsalesactionv2id`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_RetryCount"></a> msdyn_RetryCount

|Property|Value|
|---|---|
|Description|**Retry Count is used to track the retry of job.**|
|DisplayName|**Retry Count**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_retrycount`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_Schedule"></a> msdyn_Schedule

|Property|Value|
|---|---|
|Description||
|DisplayName|**Schedule**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_schedule`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|4000|

### <a name="BKMK_msdyn_StartDate"></a> msdyn_StartDate

|Property|Value|
|---|---|
|Description||
|DisplayName|**StartDate**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_startdate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_TriggerName"></a> msdyn_TriggerName

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_triggername`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|200|

### <a name="BKMK_msdyn_WorkloadName"></a> msdyn_WorkloadName

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_workloadname`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|200|

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
|Description|**Status of the Recurring Sales Action V2**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_recurringsalesactionv2_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Recurring Sales Action V2**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_recurringsalesactionv2_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|1|Label: **Active**<br />State:0<br />TransitionData: None|
|2|Label: **Inactive**<br />State:1<br />TransitionData: None|
|3|Label: **Missing**<br />State:0<br />TransitionData: None|

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

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OrganizationId](#BKMK_OrganizationId)
- [VersionNumber](#BKMK_VersionNumber)

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

- [lk_msdyn_recurringsalesactionv2_createdby](#BKMK_lk_msdyn_recurringsalesactionv2_createdby)
- [lk_msdyn_recurringsalesactionv2_createdonbehalfby](#BKMK_lk_msdyn_recurringsalesactionv2_createdonbehalfby)
- [lk_msdyn_recurringsalesactionv2_modifiedby](#BKMK_lk_msdyn_recurringsalesactionv2_modifiedby)
- [lk_msdyn_recurringsalesactionv2_modifiedonbehalfby](#BKMK_lk_msdyn_recurringsalesactionv2_modifiedonbehalfby)
- [organization_msdyn_recurringsalesactionv2](#BKMK_organization_msdyn_recurringsalesactionv2)

### <a name="BKMK_lk_msdyn_recurringsalesactionv2_createdby"></a> lk_msdyn_recurringsalesactionv2_createdby

One-To-Many Relationship: [systemuser lk_msdyn_recurringsalesactionv2_createdby](systemuser.md#BKMK_lk_msdyn_recurringsalesactionv2_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_recurringsalesactionv2_createdonbehalfby"></a> lk_msdyn_recurringsalesactionv2_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_recurringsalesactionv2_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_recurringsalesactionv2_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_recurringsalesactionv2_modifiedby"></a> lk_msdyn_recurringsalesactionv2_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_recurringsalesactionv2_modifiedby](systemuser.md#BKMK_lk_msdyn_recurringsalesactionv2_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_recurringsalesactionv2_modifiedonbehalfby"></a> lk_msdyn_recurringsalesactionv2_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_recurringsalesactionv2_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_recurringsalesactionv2_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_organization_msdyn_recurringsalesactionv2"></a> organization_msdyn_recurringsalesactionv2

One-To-Many Relationship: [organization organization_msdyn_recurringsalesactionv2](organization.md#BKMK_organization_msdyn_recurringsalesactionv2)

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

- [msdyn_recurringsalesactionv2_AsyncOperations](#BKMK_msdyn_recurringsalesactionv2_AsyncOperations)
- [msdyn_recurringsalesactionv2_BulkDeleteFailures](#BKMK_msdyn_recurringsalesactionv2_BulkDeleteFailures)
- [msdyn_recurringsalesactionv2_MailboxTrackingFolders](#BKMK_msdyn_recurringsalesactionv2_MailboxTrackingFolders)
- [msdyn_recurringsalesactionv2_PrincipalObjectAttributeAccesses](#BKMK_msdyn_recurringsalesactionv2_PrincipalObjectAttributeAccesses)
- [msdyn_recurringsalesactionv2_ProcessSession](#BKMK_msdyn_recurringsalesactionv2_ProcessSession)
- [msdyn_recurringsalesactionv2_SyncErrors](#BKMK_msdyn_recurringsalesactionv2_SyncErrors)

### <a name="BKMK_msdyn_recurringsalesactionv2_AsyncOperations"></a> msdyn_recurringsalesactionv2_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_recurringsalesactionv2_AsyncOperations](asyncoperation.md#BKMK_msdyn_recurringsalesactionv2_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_recurringsalesactionv2_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_recurringsalesactionv2_BulkDeleteFailures"></a> msdyn_recurringsalesactionv2_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_recurringsalesactionv2_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_recurringsalesactionv2_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_recurringsalesactionv2_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_recurringsalesactionv2_MailboxTrackingFolders"></a> msdyn_recurringsalesactionv2_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_recurringsalesactionv2_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_recurringsalesactionv2_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_recurringsalesactionv2_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_recurringsalesactionv2_PrincipalObjectAttributeAccesses"></a> msdyn_recurringsalesactionv2_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_recurringsalesactionv2_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_recurringsalesactionv2_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_recurringsalesactionv2_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_recurringsalesactionv2_ProcessSession"></a> msdyn_recurringsalesactionv2_ProcessSession

Many-To-One Relationship: [processsession msdyn_recurringsalesactionv2_ProcessSession](processsession.md#BKMK_msdyn_recurringsalesactionv2_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_recurringsalesactionv2_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_recurringsalesactionv2_SyncErrors"></a> msdyn_recurringsalesactionv2_SyncErrors

Many-To-One Relationship: [syncerror msdyn_recurringsalesactionv2_SyncErrors](syncerror.md#BKMK_msdyn_recurringsalesactionv2_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_recurringsalesactionv2_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

