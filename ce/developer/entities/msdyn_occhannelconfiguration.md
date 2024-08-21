---
title: "Channel Configuration (msdyn_occhannelconfiguration) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Channel Configuration (msdyn_occhannelconfiguration) table/entity with Microsoft Dynamics 365."
ms.date: 08/21/2024
ms.service: powerapps
ms.topic: reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Channel Configuration (msdyn_occhannelconfiguration) table/entity reference

Channel Configuration

## Messages

The following table lists the messages for the Channel Configuration (msdyn_occhannelconfiguration) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: True |`POST` /msdyn_occhannelconfigurations<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_occhannelconfigurations(*msdyn_occhannelconfigurationid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_occhannelconfigurations(*msdyn_occhannelconfigurationid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_occhannelconfigurations<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `SetState`<br />Event: True |`PATCH` /msdyn_occhannelconfigurations(*msdyn_occhannelconfigurationid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_occhannelconfigurations(*msdyn_occhannelconfigurationid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_occhannelconfigurations(*msdyn_occhannelconfigurationid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Channel Configuration (msdyn_occhannelconfiguration) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Channel Configuration (msdyn_occhannelconfiguration) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Channel Configuration** |
| **DisplayCollectionName** | **Channel Configurations** |
| **SchemaName** | `msdyn_occhannelconfiguration` |
| **CollectionSchemaName** | `msdyn_occhannelconfigurations` |
| **EntitySetName** | `msdyn_occhannelconfigurations`|
| **LogicalName** | `msdyn_occhannelconfiguration` |
| **LogicalCollectionName** | `msdyn_occhannelconfigurations` |
| **PrimaryIdAttribute** | `msdyn_occhannelconfigurationid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsCustomizable](#BKMK_IsCustomizable)
- [msdyn_closeconversationifoooh](#BKMK_msdyn_closeconversationifoooh)
- [msdyn_enabletransfertoooohqueue](#BKMK_msdyn_enabletransfertoooohqueue)
- [msdyn_engagementcontext](#BKMK_msdyn_engagementcontext)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_occhannelconfigurationId](#BKMK_msdyn_occhannelconfigurationId)
- [msdyn_privacytermsaccepted](#BKMK_msdyn_privacytermsaccepted)
- [msdyn_privacytermsversion](#BKMK_msdyn_privacytermsversion)
- [msdyn_streamsource](#BKMK_msdyn_streamsource)
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

### <a name="BKMK_msdyn_closeconversationifoooh"></a> msdyn_closeconversationifoooh

|Property|Value|
|---|---|
|Description|**Specifies whether the conversation should be closed when it is created out of operating hours**|
|DisplayName|**Close Conversation If Outside Of OperatingHours**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_closeconversationifoooh`|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|
|GlobalChoiceName|`msdyn_occhannelconfiguration_msdyn_closeconversationifoooh`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_enabletransfertoooohqueue"></a> msdyn_enabletransfertoooohqueue

|Property|Value|
|---|---|
|Description|**Specifies whether the conversation can be transferred to an out of operating hour queue**|
|DisplayName|**Enable Transfer to Outside Of OperatingHours Queue**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_enabletransfertoooohqueue`|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|
|GlobalChoiceName|`msdyn_occhannelconfiguration_msdyn_enabletransfertoooohqueue`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_engagementcontext"></a> msdyn_engagementcontext

|Property|Value|
|---|---|
|Description|**Entity carrying the engagement context details of the channel.**|
|DisplayName|**Engagement Context**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_engagementcontext`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|128|

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
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_occhannelconfigurationId"></a> msdyn_occhannelconfigurationId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Channel Configuration**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_occhannelconfigurationid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_privacytermsaccepted"></a> msdyn_privacytermsaccepted

|Property|Value|
|---|---|
|Description|**Indicates whether the Privacy Terms has been accepted by the user or not.**|
|DisplayName|**Privacy terms accepted**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_privacytermsaccepted`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_occhannelconfiguration_msdyn_privacytermsaccepted`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_privacytermsversion"></a> msdyn_privacytermsversion

|Property|Value|
|---|---|
|Description|**The version of the privacy terms.**|
|DisplayName|**Privacy terms version**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_privacytermsversion`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|20|

### <a name="BKMK_msdyn_streamsource"></a> msdyn_streamsource

|Property|Value|
|---|---|
|Description|**Stream source of the channel e.g. LiveChat, SMS, Facebook etc**|
|DisplayName|**Stream Source**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_streamsource`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_streamsource`|

#### msdyn_streamsource Choices/Options

|Value|Label|
|---|---|
|192350000|**Entity Records**|

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
|Description|**Status of the Channel Configuration**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_occhannelconfiguration_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Channel Configuration**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_occhannelconfiguration_statuscode`|

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

- [lk_msdyn_occhannelconfiguration_createdby](#BKMK_lk_msdyn_occhannelconfiguration_createdby)
- [lk_msdyn_occhannelconfiguration_createdonbehalfby](#BKMK_lk_msdyn_occhannelconfiguration_createdonbehalfby)
- [lk_msdyn_occhannelconfiguration_modifiedby](#BKMK_lk_msdyn_occhannelconfiguration_modifiedby)
- [lk_msdyn_occhannelconfiguration_modifiedonbehalfby](#BKMK_lk_msdyn_occhannelconfiguration_modifiedonbehalfby)
- [organization_msdyn_occhannelconfiguration](#BKMK_organization_msdyn_occhannelconfiguration)

### <a name="BKMK_lk_msdyn_occhannelconfiguration_createdby"></a> lk_msdyn_occhannelconfiguration_createdby

One-To-Many Relationship: [systemuser lk_msdyn_occhannelconfiguration_createdby](systemuser.md#BKMK_lk_msdyn_occhannelconfiguration_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_occhannelconfiguration_createdonbehalfby"></a> lk_msdyn_occhannelconfiguration_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_occhannelconfiguration_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_occhannelconfiguration_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_occhannelconfiguration_modifiedby"></a> lk_msdyn_occhannelconfiguration_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_occhannelconfiguration_modifiedby](systemuser.md#BKMK_lk_msdyn_occhannelconfiguration_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_occhannelconfiguration_modifiedonbehalfby"></a> lk_msdyn_occhannelconfiguration_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_occhannelconfiguration_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_occhannelconfiguration_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_organization_msdyn_occhannelconfiguration"></a> organization_msdyn_occhannelconfiguration

One-To-Many Relationship: [organization organization_msdyn_occhannelconfiguration](organization.md#BKMK_organization_msdyn_occhannelconfiguration)

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

- [msdyn_msdyn_occhannelconfiguration_msdyn_agentresourceforecasting_channel](#BKMK_msdyn_msdyn_occhannelconfiguration_msdyn_agentresourceforecasting_channel)
- [msdyn_msdyn_occhannelconfiguration_msdyn_occhannelstateconfiguration_occhannelconfigurationid](#BKMK_msdyn_msdyn_occhannelconfiguration_msdyn_occhannelstateconfiguration_occhannelconfigurationid)
- [msdyn_occhannelconfiguration_AsyncOperations](#BKMK_msdyn_occhannelconfiguration_AsyncOperations)
- [msdyn_occhannelconfiguration_BulkDeleteFailures](#BKMK_msdyn_occhannelconfiguration_BulkDeleteFailures)
- [msdyn_occhannelconfiguration_DuplicateBaseRecord](#BKMK_msdyn_occhannelconfiguration_DuplicateBaseRecord)
- [msdyn_occhannelconfiguration_DuplicateMatchingRecord](#BKMK_msdyn_occhannelconfiguration_DuplicateMatchingRecord)
- [msdyn_occhannelconfiguration_MailboxTrackingFolders](#BKMK_msdyn_occhannelconfiguration_MailboxTrackingFolders)
- [msdyn_occhannelconfiguration_PrincipalObjectAttributeAccesses](#BKMK_msdyn_occhannelconfiguration_PrincipalObjectAttributeAccesses)
- [msdyn_occhannelconfiguration_ProcessSession](#BKMK_msdyn_occhannelconfiguration_ProcessSession)
- [msdyn_occhannelconfiguration_SyncErrors](#BKMK_msdyn_occhannelconfiguration_SyncErrors)

### <a name="BKMK_msdyn_msdyn_occhannelconfiguration_msdyn_agentresourceforecasting_channel"></a> msdyn_msdyn_occhannelconfiguration_msdyn_agentresourceforecasting_channel

Many-To-One Relationship: [msdyn_agentresourceforecasting msdyn_msdyn_occhannelconfiguration_msdyn_agentresourceforecasting_channel](msdyn_agentresourceforecasting.md#BKMK_msdyn_msdyn_occhannelconfiguration_msdyn_agentresourceforecasting_channel)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_agentresourceforecasting`|
|ReferencingAttribute|`msdyn_channel`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_occhannelconfiguration_msdyn_agentresourceforecasting_channel`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_occhannelconfiguration_msdyn_occhannelstateconfiguration_occhannelconfigurationid"></a> msdyn_msdyn_occhannelconfiguration_msdyn_occhannelstateconfiguration_occhannelconfigurationid

Many-To-One Relationship: [msdyn_occhannelstateconfiguration msdyn_msdyn_occhannelconfiguration_msdyn_occhannelstateconfiguration_occhannelconfigurationid](msdyn_occhannelstateconfiguration.md#BKMK_msdyn_msdyn_occhannelconfiguration_msdyn_occhannelstateconfiguration_occhannelconfigurationid)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_occhannelstateconfiguration`|
|ReferencingAttribute|`msdyn_occhannelconfigurationid`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_occhannelconfiguration_msdyn_occhannelstateconfiguration_occhannelconfigurationid`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_AsyncOperations"></a> msdyn_occhannelconfiguration_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_occhannelconfiguration_AsyncOperations](asyncoperation.md#BKMK_msdyn_occhannelconfiguration_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_BulkDeleteFailures"></a> msdyn_occhannelconfiguration_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_occhannelconfiguration_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_occhannelconfiguration_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_DuplicateBaseRecord"></a> msdyn_occhannelconfiguration_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_occhannelconfiguration_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_occhannelconfiguration_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_DuplicateMatchingRecord"></a> msdyn_occhannelconfiguration_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_occhannelconfiguration_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_occhannelconfiguration_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_MailboxTrackingFolders"></a> msdyn_occhannelconfiguration_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_occhannelconfiguration_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_occhannelconfiguration_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_PrincipalObjectAttributeAccesses"></a> msdyn_occhannelconfiguration_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_occhannelconfiguration_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_occhannelconfiguration_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_ProcessSession"></a> msdyn_occhannelconfiguration_ProcessSession

Many-To-One Relationship: [processsession msdyn_occhannelconfiguration_ProcessSession](processsession.md#BKMK_msdyn_occhannelconfiguration_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_occhannelconfiguration_SyncErrors"></a> msdyn_occhannelconfiguration_SyncErrors

Many-To-One Relationship: [syncerror msdyn_occhannelconfiguration_SyncErrors](syncerror.md#BKMK_msdyn_occhannelconfiguration_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_occhannelconfiguration_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

