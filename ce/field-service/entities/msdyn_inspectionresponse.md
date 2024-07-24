---
title: "Inspection Response (msdyn_inspectionresponse) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Inspection Response (msdyn_inspectionresponse) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Inspection Response (msdyn_inspectionresponse) table/entity reference

Entity used to save the responses of the Inspection.

## Messages

The following table lists the messages for the Inspection Response (msdyn_inspectionresponse) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_inspectionresponses(*msdyn_inspectionresponseid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_inspectionresponses<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_inspectionresponses(*msdyn_inspectionresponseid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_inspectionresponses(*msdyn_inspectionresponseid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_inspectionresponses<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_inspectionresponses(*msdyn_inspectionresponseid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_inspectionresponses(*msdyn_inspectionresponseid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_inspectionresponses(*msdyn_inspectionresponseid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Inspection Response (msdyn_inspectionresponse) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Inspection Response (msdyn_inspectionresponse) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Inspection Response** |
| **DisplayCollectionName** | **Inspection Responses** |
| **SchemaName** | `msdyn_inspectionresponse` |
| **CollectionSchemaName** | `msdyn_inspectionresponses` |
| **EntitySetName** | `msdyn_inspectionresponses`|
| **LogicalName** | `msdyn_inspectionresponse` |
| **LogicalCollectionName** | `msdyn_inspectionresponses` |
| **PrimaryIdAttribute** | `msdyn_inspectionresponseid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_InspectionDefinition](#BKMK_msdyn_InspectionDefinition)
- [msdyn_inspectionresponseId](#BKMK_msdyn_inspectionresponseId)
- [msdyn_IsProcessed](#BKMK_msdyn_IsProcessed)
- [msdyn_isvalidresponse](#BKMK_msdyn_isvalidresponse)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_ResponseJsonContent](#BKMK_msdyn_ResponseJsonContent)
- [msdyn_status](#BKMK_msdyn_status)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
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

### <a name="BKMK_msdyn_InspectionDefinition"></a> msdyn_InspectionDefinition

|Property|Value|
|---|---|
|Description|**Unique Identifier of the Inspection Definition associated with the Inspection Response.**|
|DisplayName|**InspectionDefinition**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_inspectiondefinition`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_inspectiondefinition|

### <a name="BKMK_msdyn_inspectionresponseId"></a> msdyn_inspectionresponseId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**InspectionResponse**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_inspectionresponseid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_IsProcessed"></a> msdyn_IsProcessed

|Property|Value|
|---|---|
|Description|**Depicts whether the record is processed.**|
|DisplayName|**Is Processed**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_isprocessed`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_msdyn_inspectionresponse_msdyn_isprocessed`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_isvalidresponse"></a> msdyn_isvalidresponse

|Property|Value|
|---|---|
|Description|**Denotes whether the survey response has validation errors**|
|DisplayName|**Is Valid Response**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_isvalidresponse`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_inspectionresponse_msdyn_isvalidresponse`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**The name of the Inspection Response entity.**|
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

### <a name="BKMK_msdyn_ResponseJsonContent"></a> msdyn_ResponseJsonContent

|Property|Value|
|---|---|
|Description|**Contains the response json**|
|DisplayName|**ResponseJsonContent**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_responsejsoncontent`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

### <a name="BKMK_msdyn_status"></a> msdyn_status

|Property|Value|
|---|---|
|Description|**Status of the Inspection Response**|
|DisplayName|**Inspection Response Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_status`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_inspectionresponse_msdyn_status`|

#### msdyn_status Choices/Options

|Value|Label|
|---|---|
|192350000|**InProgress**|
|192350001|**Submitted**|

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

### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|---|---|
|Description|**Owner Id**|
|DisplayName|**Owner**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ownerid`|
|RequiredLevel|SystemRequired|
|Type|Owner|
|Targets|systemuser, team|

### <a name="BKMK_OwnerIdType"></a> OwnerIdType

|Property|Value|
|---|---|
|Description|**Owner Id Type**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridtype`|
|RequiredLevel|SystemRequired|
|Type|EntityName|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the InspectionResponse**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_inspectionresponse_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the InspectionResponse**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_inspectionresponse_statuscode`|

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
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
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

### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|---|---|
|Description|**Name of the owner**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridname`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

|Property|Value|
|---|---|
|Description|**Yomi name of the owner**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridyominame`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

|Property|Value|
|---|---|
|Description|**Unique identifier for the business unit that owns the record**|
|DisplayName|**Owning Business Unit**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`owningbusinessunit`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|businessunit|

### <a name="BKMK_OwningTeam"></a> OwningTeam

|Property|Value|
|---|---|
|Description|**Unique identifier for the team that owns the record.**|
|DisplayName|**Owning Team**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owningteam`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|team|

### <a name="BKMK_OwningUser"></a> OwningUser

|Property|Value|
|---|---|
|Description|**Unique identifier for the user that owns the record.**|
|DisplayName|**Owning User**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owninguser`|
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

- [business_unit_msdyn_inspectionresponse](#BKMK_business_unit_msdyn_inspectionresponse)
- [lk_msdyn_inspectionresponse_createdby](#BKMK_lk_msdyn_inspectionresponse_createdby)
- [lk_msdyn_inspectionresponse_createdonbehalfby](#BKMK_lk_msdyn_inspectionresponse_createdonbehalfby)
- [lk_msdyn_inspectionresponse_modifiedby](#BKMK_lk_msdyn_inspectionresponse_modifiedby)
- [lk_msdyn_inspectionresponse_modifiedonbehalfby](#BKMK_lk_msdyn_inspectionresponse_modifiedonbehalfby)
- [msdyn_msdyn_inspectiondefinition_msdyn_inspectionresponse_InspectionDefinition](#BKMK_msdyn_msdyn_inspectiondefinition_msdyn_inspectionresponse_InspectionDefinition)
- [owner_msdyn_inspectionresponse](#BKMK_owner_msdyn_inspectionresponse)
- [team_msdyn_inspectionresponse](#BKMK_team_msdyn_inspectionresponse)
- [user_msdyn_inspectionresponse](#BKMK_user_msdyn_inspectionresponse)

### <a name="BKMK_business_unit_msdyn_inspectionresponse"></a> business_unit_msdyn_inspectionresponse

One-To-Many Relationship: [businessunit business_unit_msdyn_inspectionresponse](businessunit.md#BKMK_business_unit_msdyn_inspectionresponse)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectionresponse_createdby"></a> lk_msdyn_inspectionresponse_createdby

One-To-Many Relationship: [systemuser lk_msdyn_inspectionresponse_createdby](systemuser.md#BKMK_lk_msdyn_inspectionresponse_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectionresponse_createdonbehalfby"></a> lk_msdyn_inspectionresponse_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_inspectionresponse_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_inspectionresponse_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectionresponse_modifiedby"></a> lk_msdyn_inspectionresponse_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_inspectionresponse_modifiedby](systemuser.md#BKMK_lk_msdyn_inspectionresponse_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectionresponse_modifiedonbehalfby"></a> lk_msdyn_inspectionresponse_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_inspectionresponse_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_inspectionresponse_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_inspectiondefinition_msdyn_inspectionresponse_InspectionDefinition"></a> msdyn_msdyn_inspectiondefinition_msdyn_inspectionresponse_InspectionDefinition

One-To-Many Relationship: [msdyn_inspectiondefinition msdyn_msdyn_inspectiondefinition_msdyn_inspectionresponse_InspectionDefinition](msdyn_inspectiondefinition.md#BKMK_msdyn_msdyn_inspectiondefinition_msdyn_inspectionresponse_InspectionDefinition)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_inspectiondefinition`|
|ReferencedAttribute|`msdyn_inspectiondefinitionid`|
|ReferencingAttribute|`msdyn_inspectiondefinition`|
|ReferencingEntityNavigationPropertyName|`msdyn_InspectionDefinition`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_inspectionresponse"></a> owner_msdyn_inspectionresponse

One-To-Many Relationship: [owner owner_msdyn_inspectionresponse](owner.md#BKMK_owner_msdyn_inspectionresponse)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_inspectionresponse"></a> team_msdyn_inspectionresponse

One-To-Many Relationship: [team team_msdyn_inspectionresponse](team.md#BKMK_team_msdyn_inspectionresponse)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_inspectionresponse"></a> user_msdyn_inspectionresponse

One-To-Many Relationship: [systemuser user_msdyn_inspectionresponse](systemuser.md#BKMK_user_msdyn_inspectionresponse)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`owninguser`|
|ReferencingEntityNavigationPropertyName|`owninguser`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_inspectionresponse_AsyncOperations](#BKMK_msdyn_inspectionresponse_AsyncOperations)
- [msdyn_inspectionresponse_BulkDeleteFailures](#BKMK_msdyn_inspectionresponse_BulkDeleteFailures)
- [msdyn_inspectionresponse_DuplicateBaseRecord](#BKMK_msdyn_inspectionresponse_DuplicateBaseRecord)
- [msdyn_inspectionresponse_DuplicateMatchingRecord](#BKMK_msdyn_inspectionresponse_DuplicateMatchingRecord)
- [msdyn_inspectionresponse_MailboxTrackingFolders](#BKMK_msdyn_inspectionresponse_MailboxTrackingFolders)
- [msdyn_inspectionresponse_PrincipalObjectAttributeAccesses](#BKMK_msdyn_inspectionresponse_PrincipalObjectAttributeAccesses)
- [msdyn_inspectionresponse_ProcessSession](#BKMK_msdyn_inspectionresponse_ProcessSession)
- [msdyn_inspectionresponse_SyncErrors](#BKMK_msdyn_inspectionresponse_SyncErrors)
- [msdyn_msdyn_inspectionresponse_msdyn_inspection](#BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspection)
- [msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance](#BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance)
- [msdyn_msdyn_inspectionresponse_msdyn_workorderservicetask_inspectionresponseid](#BKMK_msdyn_msdyn_inspectionresponse_msdyn_workorderservicetask_inspectionresponseid)

### <a name="BKMK_msdyn_inspectionresponse_AsyncOperations"></a> msdyn_inspectionresponse_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_inspectionresponse_AsyncOperations](asyncoperation.md#BKMK_msdyn_inspectionresponse_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectionresponse_BulkDeleteFailures"></a> msdyn_inspectionresponse_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_inspectionresponse_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_inspectionresponse_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectionresponse_DuplicateBaseRecord"></a> msdyn_inspectionresponse_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_inspectionresponse_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_inspectionresponse_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectionresponse_DuplicateMatchingRecord"></a> msdyn_inspectionresponse_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_inspectionresponse_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_inspectionresponse_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectionresponse_MailboxTrackingFolders"></a> msdyn_inspectionresponse_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_inspectionresponse_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_inspectionresponse_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectionresponse_PrincipalObjectAttributeAccesses"></a> msdyn_inspectionresponse_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_inspectionresponse_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_inspectionresponse_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectionresponse_ProcessSession"></a> msdyn_inspectionresponse_ProcessSession

Many-To-One Relationship: [processsession msdyn_inspectionresponse_ProcessSession](processsession.md#BKMK_msdyn_inspectionresponse_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectionresponse_SyncErrors"></a> msdyn_inspectionresponse_SyncErrors

Many-To-One Relationship: [syncerror msdyn_inspectionresponse_SyncErrors](syncerror.md#BKMK_msdyn_inspectionresponse_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectionresponse_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspection"></a> msdyn_msdyn_inspectionresponse_msdyn_inspection

Many-To-One Relationship: [msdyn_inspectionattachment msdyn_msdyn_inspectionresponse_msdyn_inspection](msdyn_inspectionattachment.md#BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspection)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_inspectionattachment`|
|ReferencingAttribute|`msdyn_inspectionresponseid`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_inspectionresponse_msdyn_inspection`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance"></a> msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance

Many-To-One Relationship: [msdyn_inspectioninstance msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance](msdyn_inspectioninstance.md#BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_inspectioninstance`|
|ReferencingAttribute|`msdyn_inspectionresponseid`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_inspectionresponse_msdyn_workorderservicetask_inspectionresponseid"></a> msdyn_msdyn_inspectionresponse_msdyn_workorderservicetask_inspectionresponseid

Many-To-One Relationship: [msdyn_workorderservicetask msdyn_msdyn_inspectionresponse_msdyn_workorderservicetask_inspectionresponseid](msdyn_workorderservicetask.md#BKMK_msdyn_msdyn_inspectionresponse_msdyn_workorderservicetask_inspectionresponseid)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_workorderservicetask`|
|ReferencingAttribute|`msdyn_inspectionresponseid`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_inspectionresponse_msdyn_workorderservicetask_inspectionresponseid`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

