---
title: "EnvironmentSettings (msdyn_scienvironmentsettings) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the EnvironmentSettings (msdyn_scienvironmentsettings) table/entity with Microsoft Dynamics 365."
ms.topic: generated-reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# EnvironmentSettings (msdyn_scienvironmentsettings) table/entity reference (Microsoft Dynamics 365)

SCI environment level settings

## Messages

The following table lists the messages for the EnvironmentSettings (msdyn_scienvironmentsettings) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Associate`<br />Event: True |[Associate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Associate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-associate-method-or-associaterequest)|
| `BulkRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Create`<br />Event: True |`POST` /msdyn_scienvironmentsettings<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_scienvironmentsettings(*msdyn_scienvironmentsettingsid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Disassociate`<br />Event: True |[Disassociate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Disassociate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-disassociate-method-or-disassociaterequest)|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `PurgeRetainedContent`<br />Event: True |<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_scienvironmentsettings(*msdyn_scienvironmentsettingsid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_scienvironmentsettings<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RollbackRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `SetState`<br />Event: True |`PATCH` /msdyn_scienvironmentsettings(*msdyn_scienvironmentsettingsid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_scienvironmentsettings(*msdyn_scienvironmentsettingsid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_scienvironmentsettings(*msdyn_scienvironmentsettingsid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|
| `ValidateRetentionConfig`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the EnvironmentSettings (msdyn_scienvironmentsettings) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **EnvironmentSettings** |
| **DisplayCollectionName** | **EnvironmentSettings** |
| **SchemaName** | `msdyn_scienvironmentsettings` |
| **CollectionSchemaName** | `msdyn_scienvironmentsettingses` |
| **EntitySetName** | `msdyn_scienvironmentsettings`|
| **LogicalName** | `msdyn_scienvironmentsettings` |
| **LogicalCollectionName** | `msdyn_scienvironmentsettingses` |
| **PrimaryIdAttribute** | `msdyn_scienvironmentsettingsid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_AzureSubscriptionId](#BKMK_msdyn_AzureSubscriptionId)
- [msdyn_ContainerName](#BKMK_msdyn_ContainerName)
- [msdyn_Name](#BKMK_msdyn_Name)
- [msdyn_RepAudioChannel](#BKMK_msdyn_RepAudioChannel)
- [msdyn_scienvironmentsettingsId](#BKMK_msdyn_scienvironmentsettingsId)
- [msdyn_StorageAccountName](#BKMK_msdyn_StorageAccountName)
- [msdyn_TrackedCompetitors](#BKMK_msdyn_TrackedCompetitors)
- [msdyn_TrackedKeywords](#BKMK_msdyn_TrackedKeywords)
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

### <a name="BKMK_msdyn_AzureSubscriptionId"></a> msdyn_AzureSubscriptionId

|Property|Value|
|---|---|
|Description|**The subscription of the external storage that is used for uploading audio files for processing and storing the adio files for playback**|
|DisplayName|**Azure Subscription Id**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_azuresubscriptionid`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|36|

### <a name="BKMK_msdyn_ContainerName"></a> msdyn_ContainerName

|Property|Value|
|---|---|
|Description|**The name of the storage account container that is used for uploading audio files for processing**|
|DisplayName|**Container Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_containername`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|200|

### <a name="BKMK_msdyn_Name"></a> msdyn_Name

|Property|Value|
|---|---|
|Description|**The name of the environment settings record**|
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

### <a name="BKMK_msdyn_RepAudioChannel"></a> msdyn_RepAudioChannel

|Property|Value|
|---|---|
|Description|**Default channel configured for the representatives**|
|DisplayName|**Rep Audio Channel**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_repaudiochannel`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|1|
|MinValue|0|

### <a name="BKMK_msdyn_scienvironmentsettingsId"></a> msdyn_scienvironmentsettingsId

|Property|Value|
|---|---|
|Description|**Unique identifier for the environment settings**|
|DisplayName|**Environment Settings**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_scienvironmentsettingsid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_StorageAccountName"></a> msdyn_StorageAccountName

|Property|Value|
|---|---|
|Description|**The external storage that is used for uploading audio files for processing**|
|DisplayName|**Storage Account Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_storageaccountname`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

### <a name="BKMK_msdyn_TrackedCompetitors"></a> msdyn_TrackedCompetitors

|Property|Value|
|---|---|
|Description|**A comma separated list of specific competitors to track for analysis and get relevant insights around them**|
|DisplayName|**Tracked Competitors**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_trackedcompetitors`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

### <a name="BKMK_msdyn_TrackedKeywords"></a> msdyn_TrackedKeywords

|Property|Value|
|---|---|
|Description|**A comma separated list of specific words to track for analysis and get relevant insights around them**|
|DisplayName|**Tracked Keywords**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_trackedkeywords`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

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
|Description|**Status of the environment settings**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_scienvironmentsettings_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the environment settings**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_scienvironmentsettings_statuscode`|

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

- [lk_msdyn_scienvironmentsettings_createdby](#BKMK_lk_msdyn_scienvironmentsettings_createdby)
- [lk_msdyn_scienvironmentsettings_createdonbehalfby](#BKMK_lk_msdyn_scienvironmentsettings_createdonbehalfby)
- [lk_msdyn_scienvironmentsettings_modifiedby](#BKMK_lk_msdyn_scienvironmentsettings_modifiedby)
- [lk_msdyn_scienvironmentsettings_modifiedonbehalfby](#BKMK_lk_msdyn_scienvironmentsettings_modifiedonbehalfby)
- [organization_msdyn_scienvironmentsettings](#BKMK_organization_msdyn_scienvironmentsettings)

### <a name="BKMK_lk_msdyn_scienvironmentsettings_createdby"></a> lk_msdyn_scienvironmentsettings_createdby

One-To-Many Relationship: [systemuser lk_msdyn_scienvironmentsettings_createdby](systemuser.md#BKMK_lk_msdyn_scienvironmentsettings_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_scienvironmentsettings_createdonbehalfby"></a> lk_msdyn_scienvironmentsettings_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_scienvironmentsettings_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_scienvironmentsettings_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_scienvironmentsettings_modifiedby"></a> lk_msdyn_scienvironmentsettings_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_scienvironmentsettings_modifiedby](systemuser.md#BKMK_lk_msdyn_scienvironmentsettings_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_scienvironmentsettings_modifiedonbehalfby"></a> lk_msdyn_scienvironmentsettings_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_scienvironmentsettings_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_scienvironmentsettings_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_organization_msdyn_scienvironmentsettings"></a> organization_msdyn_scienvironmentsettings

One-To-Many Relationship: [organization organization_msdyn_scienvironmentsettings](organization.md#BKMK_organization_msdyn_scienvironmentsettings)

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

- [msdyn_scienvironmentsettings_AsyncOperations](#BKMK_msdyn_scienvironmentsettings_AsyncOperations)
- [msdyn_scienvironmentsettings_BulkDeleteFailures](#BKMK_msdyn_scienvironmentsettings_BulkDeleteFailures)
- [msdyn_scienvironmentsettings_DuplicateBaseRecord](#BKMK_msdyn_scienvironmentsettings_DuplicateBaseRecord)
- [msdyn_scienvironmentsettings_DuplicateMatchingRecord](#BKMK_msdyn_scienvironmentsettings_DuplicateMatchingRecord)
- [msdyn_scienvironmentsettings_MailboxTrackingFolders](#BKMK_msdyn_scienvironmentsettings_MailboxTrackingFolders)
- [msdyn_scienvironmentsettings_PrincipalObjectAttributeAccesses](#BKMK_msdyn_scienvironmentsettings_PrincipalObjectAttributeAccesses)
- [msdyn_scienvironmentsettings_ProcessSession](#BKMK_msdyn_scienvironmentsettings_ProcessSession)
- [msdyn_scienvironmentsettings_SyncErrors](#BKMK_msdyn_scienvironmentsettings_SyncErrors)

### <a name="BKMK_msdyn_scienvironmentsettings_AsyncOperations"></a> msdyn_scienvironmentsettings_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_scienvironmentsettings_AsyncOperations](asyncoperation.md#BKMK_msdyn_scienvironmentsettings_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_scienvironmentsettings_BulkDeleteFailures"></a> msdyn_scienvironmentsettings_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_scienvironmentsettings_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_scienvironmentsettings_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_scienvironmentsettings_DuplicateBaseRecord"></a> msdyn_scienvironmentsettings_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_scienvironmentsettings_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_scienvironmentsettings_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_scienvironmentsettings_DuplicateMatchingRecord"></a> msdyn_scienvironmentsettings_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_scienvironmentsettings_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_scienvironmentsettings_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_scienvironmentsettings_MailboxTrackingFolders"></a> msdyn_scienvironmentsettings_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_scienvironmentsettings_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_scienvironmentsettings_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_scienvironmentsettings_PrincipalObjectAttributeAccesses"></a> msdyn_scienvironmentsettings_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_scienvironmentsettings_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_scienvironmentsettings_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_scienvironmentsettings_ProcessSession"></a> msdyn_scienvironmentsettings_ProcessSession

Many-To-One Relationship: [processsession msdyn_scienvironmentsettings_ProcessSession](processsession.md#BKMK_msdyn_scienvironmentsettings_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_scienvironmentsettings_SyncErrors"></a> msdyn_scienvironmentsettings_SyncErrors

Many-To-One Relationship: [syncerror msdyn_scienvironmentsettings_SyncErrors](syncerror.md#BKMK_msdyn_scienvironmentsettings_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_scienvironmentsettings_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

