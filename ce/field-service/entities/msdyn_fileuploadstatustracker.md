---
title: "File Upload Status Tracker (msdyn_fileuploadstatustracker) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the File Upload Status Tracker (msdyn_fileuploadstatustracker) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# File Upload Status Tracker (msdyn_fileuploadstatustracker) table/entity reference

File Upload Status Tracker

## Messages

The following table lists the messages for the File Upload Status Tracker (msdyn_fileuploadstatustracker) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: True |`POST` /msdyn_fileuploadstatustrackers<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_fileuploadstatustrackers(*msdyn_fileuploadstatustrackerid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Retrieve`<br />Event: True |`GET` /msdyn_fileuploadstatustrackers(*msdyn_fileuploadstatustrackerid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveEntityChanges`<br />Event: True | |<xref:Microsoft.Xrm.Sdk.Messages.RetrieveEntityChangesRequest>|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_fileuploadstatustrackers<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `Update`<br />Event: True |`PATCH` /msdyn_fileuploadstatustrackers(*msdyn_fileuploadstatustrackerid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: True |`PATCH` /msdyn_fileuploadstatustrackers(*msdyn_fileuploadstatustrackerid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the File Upload Status Tracker (msdyn_fileuploadstatustracker) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the File Upload Status Tracker (msdyn_fileuploadstatustracker) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **File Upload Status Tracker** |
| **DisplayCollectionName** | **File Upload Status Tracker** |
| **SchemaName** | `msdyn_fileuploadstatustracker` |
| **CollectionSchemaName** | `msdyn_fileuploadstatustrackers` |
| **EntitySetName** | `msdyn_fileuploadstatustrackers`|
| **LogicalName** | `msdyn_fileuploadstatustracker` |
| **LogicalCollectionName** | `msdyn_fileuploadstatustrackers` |
| **PrimaryIdAttribute** | `msdyn_fileuploadstatustrackerid` |
| **PrimaryNameAttribute** |`msdyn_uploadfilename` |
| **TableType** | `Elastic` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_attempt](#BKMK_msdyn_attempt)
- [msdyn_errorcode](#BKMK_msdyn_errorcode)
- [msdyn_errormessage](#BKMK_msdyn_errormessage)
- [msdyn_fileuploadstatus](#BKMK_msdyn_fileuploadstatus)
- [msdyn_fileuploadstatustrackerId](#BKMK_msdyn_fileuploadstatustrackerId)
- [msdyn_forecastconfigurationid](#BKMK_msdyn_forecastconfigurationid)
- [msdyn_forecastrecurrenceupdatedetailslist](#BKMK_msdyn_forecastrecurrenceupdatedetailslist)
- [msdyn_uploadedon](#BKMK_msdyn_uploadedon)
- [msdyn_uploadfilename](#BKMK_msdyn_uploadfilename)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [PartitionId](#BKMK_PartitionId)
- [TTLInSeconds](#BKMK_TTLInSeconds)

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

### <a name="BKMK_msdyn_attempt"></a> msdyn_attempt

|Property|Value|
|---|---|
|Description|**Attempt Number of uploading quota.**|
|DisplayName|**Attempt Number of uploading quota**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_attempt`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_errorcode"></a> msdyn_errorcode

|Property|Value|
|---|---|
|Description|**Error Code**|
|DisplayName|**Error Code**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_errorcode`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_errormessage"></a> msdyn_errormessage

|Property|Value|
|---|---|
|Description|**Error Message**|
|DisplayName|**Error Message**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_errormessage`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|4000|

### <a name="BKMK_msdyn_fileuploadstatus"></a> msdyn_fileuploadstatus

|Property|Value|
|---|---|
|Description|**File Upload Status**|
|DisplayName|**File Upload Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_fileuploadstatus`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_fileuploadstatustracker_fileuploadstatus`|

#### msdyn_fileuploadstatus Choices/Options

|Value|Label|
|---|---|
|1|**FileUploaded**|
|2|**ParsingInProgress**|
|3|**UpdateSuccess**|
|4|**UpdateFailed**|

### <a name="BKMK_msdyn_fileuploadstatustrackerId"></a> msdyn_fileuploadstatustrackerId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**File Upload Status Tracker**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_fileuploadstatustrackerid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_forecastconfigurationid"></a> msdyn_forecastconfigurationid

|Property|Value|
|---|---|
|Description||
|DisplayName|**msdyn_forecastconfigurationid**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_forecastconfigurationid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_forecastconfiguration|

### <a name="BKMK_msdyn_forecastrecurrenceupdatedetailslist"></a> msdyn_forecastrecurrenceupdatedetailslist

|Property|Value|
|---|---|
|Description||
|DisplayName|**msdyn_forecastrecurrenceupdatedetailslist**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_forecastrecurrenceupdatedetailslist`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Json|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|10000|

### <a name="BKMK_msdyn_uploadedon"></a> msdyn_uploadedon

|Property|Value|
|---|---|
|Description|**Date and time when the file was uploaded**|
|DisplayName|**Uploaded on**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_uploadedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_uploadfilename"></a> msdyn_uploadfilename

|Property|Value|
|---|---|
|Description|**Upload File Name**|
|DisplayName|**Upload File Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_uploadfilename`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
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

### <a name="BKMK_PartitionId"></a> PartitionId

|Property|Value|
|---|---|
|Description|**Logical partition id. A logical partition consists of a set of records with same partition id.**|
|DisplayName|**Partition Id**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`partitionid`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_TTLInSeconds"></a> TTLInSeconds

|Property|Value|
|---|---|
|Description|**Time to live in seconds.**|
|DisplayName|**Time to live**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ttlinseconds`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|1|


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

- [lk_msdyn_fileuploadstatustracker_createdby](#BKMK_lk_msdyn_fileuploadstatustracker_createdby)
- [lk_msdyn_fileuploadstatustracker_createdonbehalfby](#BKMK_lk_msdyn_fileuploadstatustracker_createdonbehalfby)
- [lk_msdyn_fileuploadstatustracker_modifiedby](#BKMK_lk_msdyn_fileuploadstatustracker_modifiedby)
- [lk_msdyn_fileuploadstatustracker_modifiedonbehalfby](#BKMK_lk_msdyn_fileuploadstatustracker_modifiedonbehalfby)
- [msdyn_msdyn_forecastconfiguration_msdyn_fileuploadstatustracker_forecastconfigurationid](#BKMK_msdyn_msdyn_forecastconfiguration_msdyn_fileuploadstatustracker_forecastconfigurationid)

### <a name="BKMK_lk_msdyn_fileuploadstatustracker_createdby"></a> lk_msdyn_fileuploadstatustracker_createdby

One-To-Many Relationship: [systemuser lk_msdyn_fileuploadstatustracker_createdby](systemuser.md#BKMK_lk_msdyn_fileuploadstatustracker_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_fileuploadstatustracker_createdonbehalfby"></a> lk_msdyn_fileuploadstatustracker_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_fileuploadstatustracker_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_fileuploadstatustracker_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_fileuploadstatustracker_modifiedby"></a> lk_msdyn_fileuploadstatustracker_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_fileuploadstatustracker_modifiedby](systemuser.md#BKMK_lk_msdyn_fileuploadstatustracker_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_fileuploadstatustracker_modifiedonbehalfby"></a> lk_msdyn_fileuploadstatustracker_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_fileuploadstatustracker_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_fileuploadstatustracker_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_forecastconfiguration_msdyn_fileuploadstatustracker_forecastconfigurationid"></a> msdyn_msdyn_forecastconfiguration_msdyn_fileuploadstatustracker_forecastconfigurationid

One-To-Many Relationship: [msdyn_forecastconfiguration msdyn_msdyn_forecastconfiguration_msdyn_fileuploadstatustracker_forecastconfigurationid](msdyn_forecastconfiguration.md#BKMK_msdyn_msdyn_forecastconfiguration_msdyn_fileuploadstatustracker_forecastconfigurationid)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_forecastconfiguration`|
|ReferencedAttribute|`msdyn_forecastconfigurationid`|
|ReferencingAttribute|`msdyn_forecastconfigurationid`|
|ReferencingEntityNavigationPropertyName|`msdyn_forecastconfigurationid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

