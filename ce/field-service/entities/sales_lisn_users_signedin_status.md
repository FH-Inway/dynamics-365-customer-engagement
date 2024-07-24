---
title: "sales_lisn_users_signedin_status table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the sales_lisn_users_signedin_status table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# sales_lisn_users_signedin_status table/entity reference

Contains the signed in status of the users to LinkedIn Display Widgets

## Messages

The following table lists the messages for the sales_lisn_users_signedin_status table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: True |`POST` /sales_lisn_users_signedin_statuses<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `Delete`<br />Event: True |`DELETE` /sales_lisn_users_signedin_statuses(*sales_lisn_users_signedin_statusid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /sales_lisn_users_signedin_statuses(*sales_lisn_users_signedin_statusid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /sales_lisn_users_signedin_statuses<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `Update`<br />Event: True |`PATCH` /sales_lisn_users_signedin_statuses(*sales_lisn_users_signedin_statusid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `Upsert`<br />Event: False |`PATCH` /sales_lisn_users_signedin_statuses(*sales_lisn_users_signedin_statusid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|


## Events

The following table lists the events for the sales_lisn_users_signedin_status table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the sales_lisn_users_signedin_status table.

|Property|Value|
| --- | --- |
| **DisplayName** | **sales_lisn_users_signedin_status** |
| **DisplayCollectionName** | **sales_lisn_users_signedin_statuses** |
| **SchemaName** | `sales_lisn_users_signedin_status` |
| **CollectionSchemaName** | `sales_lisn_users_signedin_statuses` |
| **EntitySetName** | `sales_lisn_users_signedin_statuses`|
| **LogicalName** | `sales_lisn_users_signedin_status` |
| **LogicalCollectionName** | `sales_lisn_users_signedin_statuses` |
| **PrimaryIdAttribute** | `sales_lisn_users_signedin_statusid` |
| **PrimaryNameAttribute** |`system_user_id` |
| **TableType** | `Standard` |
| **OwnershipType** | `None` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [is_lisn_user_signed_in](#BKMK_is_lisn_user_signed_in)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [sales_lisn_users_signedin_statusId](#BKMK_sales_lisn_users_signedin_statusId)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [system_user_id](#BKMK_system_user_id)
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

### <a name="BKMK_is_lisn_user_signed_in"></a> is_lisn_user_signed_in

|Property|Value|
|---|---|
|Description||
|DisplayName|**is_lisn_user_signed_in**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`is_lisn_user_signed_in`|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|
|GlobalChoiceName|`sales_lisn_users_signedin_status_is_user_signed_in`|
|DefaultValue|False|
|True Label|true|
|False Label|false|

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

### <a name="BKMK_sales_lisn_users_signedin_statusId"></a> sales_lisn_users_signedin_statusId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**sales_lisn_users_signedin_status**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`sales_lisn_users_signedin_statusid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the sales_lisn_users_signedin_status**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`sales_lisn_users_signedin_status_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the sales_linkedin_users_signedin_status**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`sales_lisn_users_signedin_status_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|1|Label: **Active**<br />State:0<br />TransitionData: None|
|2|Label: **Inactive**<br />State:1<br />TransitionData: None|

### <a name="BKMK_system_user_id"></a> system_user_id

|Property|Value|
|---|---|
|Description|**System User Id**|
|DisplayName|**system_user_id**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`system_user_id`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

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

- [lk_sales_lisn_users_signedin_status_createdby](#BKMK_lk_sales_lisn_users_signedin_status_createdby)
- [lk_sales_lisn_users_signedin_status_createdonbehalfby](#BKMK_lk_sales_lisn_users_signedin_status_createdonbehalfby)
- [lk_sales_lisn_users_signedin_status_modifiedby](#BKMK_lk_sales_lisn_users_signedin_status_modifiedby)
- [lk_sales_lisn_users_signedin_status_modifiedonbehalfby](#BKMK_lk_sales_lisn_users_signedin_status_modifiedonbehalfby)

### <a name="BKMK_lk_sales_lisn_users_signedin_status_createdby"></a> lk_sales_lisn_users_signedin_status_createdby

One-To-Many Relationship: [systemuser lk_sales_lisn_users_signedin_status_createdby](systemuser.md#BKMK_lk_sales_lisn_users_signedin_status_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_sales_lisn_users_signedin_status_createdonbehalfby"></a> lk_sales_lisn_users_signedin_status_createdonbehalfby

One-To-Many Relationship: [systemuser lk_sales_lisn_users_signedin_status_createdonbehalfby](systemuser.md#BKMK_lk_sales_lisn_users_signedin_status_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_sales_lisn_users_signedin_status_modifiedby"></a> lk_sales_lisn_users_signedin_status_modifiedby

One-To-Many Relationship: [systemuser lk_sales_lisn_users_signedin_status_modifiedby](systemuser.md#BKMK_lk_sales_lisn_users_signedin_status_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_sales_lisn_users_signedin_status_modifiedonbehalfby"></a> lk_sales_lisn_users_signedin_status_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_sales_lisn_users_signedin_status_modifiedonbehalfby](systemuser.md#BKMK_lk_sales_lisn_users_signedin_status_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [sales_lisn_users_signedin_status_AsyncOperations](#BKMK_sales_lisn_users_signedin_status_AsyncOperations)
- [sales_lisn_users_signedin_status_BulkDeleteFailures](#BKMK_sales_lisn_users_signedin_status_BulkDeleteFailures)
- [sales_lisn_users_signedin_status_DuplicateBaseRecord](#BKMK_sales_lisn_users_signedin_status_DuplicateBaseRecord)
- [sales_lisn_users_signedin_status_DuplicateMatchingRecord](#BKMK_sales_lisn_users_signedin_status_DuplicateMatchingRecord)
- [sales_lisn_users_signedin_status_MailboxTrackingFolders](#BKMK_sales_lisn_users_signedin_status_MailboxTrackingFolders)
- [sales_lisn_users_signedin_status_PrincipalObjectAttributeAccesses](#BKMK_sales_lisn_users_signedin_status_PrincipalObjectAttributeAccesses)
- [sales_lisn_users_signedin_status_ProcessSession](#BKMK_sales_lisn_users_signedin_status_ProcessSession)
- [sales_lisn_users_signedin_status_SyncErrors](#BKMK_sales_lisn_users_signedin_status_SyncErrors)

### <a name="BKMK_sales_lisn_users_signedin_status_AsyncOperations"></a> sales_lisn_users_signedin_status_AsyncOperations

Many-To-One Relationship: [asyncoperation sales_lisn_users_signedin_status_AsyncOperations](asyncoperation.md#BKMK_sales_lisn_users_signedin_status_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sales_lisn_users_signedin_status_BulkDeleteFailures"></a> sales_lisn_users_signedin_status_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure sales_lisn_users_signedin_status_BulkDeleteFailures](bulkdeletefailure.md#BKMK_sales_lisn_users_signedin_status_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sales_lisn_users_signedin_status_DuplicateBaseRecord"></a> sales_lisn_users_signedin_status_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord sales_lisn_users_signedin_status_DuplicateBaseRecord](duplicaterecord.md#BKMK_sales_lisn_users_signedin_status_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sales_lisn_users_signedin_status_DuplicateMatchingRecord"></a> sales_lisn_users_signedin_status_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord sales_lisn_users_signedin_status_DuplicateMatchingRecord](duplicaterecord.md#BKMK_sales_lisn_users_signedin_status_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sales_lisn_users_signedin_status_MailboxTrackingFolders"></a> sales_lisn_users_signedin_status_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder sales_lisn_users_signedin_status_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_sales_lisn_users_signedin_status_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sales_lisn_users_signedin_status_PrincipalObjectAttributeAccesses"></a> sales_lisn_users_signedin_status_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess sales_lisn_users_signedin_status_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_sales_lisn_users_signedin_status_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sales_lisn_users_signedin_status_ProcessSession"></a> sales_lisn_users_signedin_status_ProcessSession

Many-To-One Relationship: [processsession sales_lisn_users_signedin_status_ProcessSession](processsession.md#BKMK_sales_lisn_users_signedin_status_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sales_lisn_users_signedin_status_SyncErrors"></a> sales_lisn_users_signedin_status_SyncErrors

Many-To-One Relationship: [syncerror sales_lisn_users_signedin_status_SyncErrors](syncerror.md#BKMK_sales_lisn_users_signedin_status_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sales_lisn_users_signedin_status_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

