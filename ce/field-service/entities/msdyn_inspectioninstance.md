---
title: "Inspection (msdyn_inspectioninstance) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Inspection (msdyn_inspectioninstance) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Inspection (msdyn_inspectioninstance) table/entity reference



## Messages

The following table lists the messages for the Inspection (msdyn_inspectioninstance) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_inspectioninstances(*msdyn_inspectioninstanceid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_inspectioninstances<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_inspectioninstances(*msdyn_inspectioninstanceid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_inspectioninstances(*msdyn_inspectioninstanceid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_inspectioninstances<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_inspectioninstances(*msdyn_inspectioninstanceid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_inspectioninstances(*msdyn_inspectioninstanceid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_inspectioninstances(*msdyn_inspectioninstanceid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Inspection (msdyn_inspectioninstance) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Inspection (msdyn_inspectioninstance) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Inspection** |
| **DisplayCollectionName** | **Inspections** |
| **SchemaName** | `msdyn_inspectioninstance` |
| **CollectionSchemaName** | `msdyn_inspectioninstances` |
| **EntitySetName** | `msdyn_inspectioninstances`|
| **LogicalName** | `msdyn_inspectioninstance` |
| **LogicalCollectionName** | `msdyn_inspectioninstances` |
| **PrimaryIdAttribute** | `msdyn_inspectioninstanceid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_caseid](#BKMK_msdyn_caseid)
- [msdyn_Completed](#BKMK_msdyn_Completed)
- [msdyn_CustomerAssetId](#BKMK_msdyn_CustomerAssetId)
- [msdyn_inspectioninstanceId](#BKMK_msdyn_inspectioninstanceId)
- [msdyn_inspectionresponseid](#BKMK_msdyn_inspectionresponseid)
- [msdyn_InspectionTemplateId](#BKMK_msdyn_InspectionTemplateId)
- [msdyn_InspectionTemplateVersionId](#BKMK_msdyn_InspectionTemplateVersionId)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_surveybounded](#BKMK_msdyn_surveybounded)
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

### <a name="BKMK_msdyn_caseid"></a> msdyn_caseid

|Property|Value|
|---|---|
|Description|**Unique identifier for Case associated with Inspection.**|
|DisplayName|**Case**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_caseid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|incident|

### <a name="BKMK_msdyn_Completed"></a> msdyn_Completed

|Property|Value|
|---|---|
|Description||
|DisplayName|**Completed**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_completed`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_CustomerAssetId"></a> msdyn_CustomerAssetId

|Property|Value|
|---|---|
|Description|**Unique identifier for Customer Asset associated with Inspection.**|
|DisplayName|**Customer Asset**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_customerassetid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_customerasset|

### <a name="BKMK_msdyn_inspectioninstanceId"></a> msdyn_inspectioninstanceId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Inspection**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_inspectioninstanceid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_inspectionresponseid"></a> msdyn_inspectionresponseid

|Property|Value|
|---|---|
|Description|**Unique identifier for Inspection Response associated with Inspection.**|
|DisplayName|**InspectionResponse**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_inspectionresponseid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_inspectionresponse|

### <a name="BKMK_msdyn_InspectionTemplateId"></a> msdyn_InspectionTemplateId

|Property|Value|
|---|---|
|Description|**Unique identifier for Inspection Template associated with Inspection.**|
|DisplayName|**Inspection Template**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_inspectiontemplateid`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_inspection|

### <a name="BKMK_msdyn_InspectionTemplateVersionId"></a> msdyn_InspectionTemplateVersionId

|Property|Value|
|---|---|
|Description|**Unique identifier for Inspection Template Version associated with Inspection.**|
|DisplayName|**InspectionTemplateVersion**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_inspectiontemplateversionid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_inspectiondefinition|

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

### <a name="BKMK_msdyn_surveybounded"></a> msdyn_surveybounded

|Property|Value|
|---|---|
|Description||
|DisplayName|**Survey Bounded**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_surveybounded`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

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
|Description|**Status of the Inspection**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_inspectioninstance_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Inspection**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_inspectioninstance_statuscode`|

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

- [business_unit_msdyn_inspectioninstance](#BKMK_business_unit_msdyn_inspectioninstance)
- [lk_msdyn_inspectioninstance_createdby](#BKMK_lk_msdyn_inspectioninstance_createdby)
- [lk_msdyn_inspectioninstance_createdonbehalfby](#BKMK_lk_msdyn_inspectioninstance_createdonbehalfby)
- [lk_msdyn_inspectioninstance_modifiedby](#BKMK_lk_msdyn_inspectioninstance_modifiedby)
- [lk_msdyn_inspectioninstance_modifiedonbehalfby](#BKMK_lk_msdyn_inspectioninstance_modifiedonbehalfby)
- [msdyn_incident_msdyn_inspectioninstance_CaseId](#BKMK_msdyn_incident_msdyn_inspectioninstance_CaseId)
- [msdyn_msdyn_customerasset_msdyn_inspectioninstance_customerassetid](#BKMK_msdyn_msdyn_customerasset_msdyn_inspectioninstance_customerassetid)
- [msdyn_msdyn_inspection_msdyn_inspectioninstance](#BKMK_msdyn_msdyn_inspection_msdyn_inspectioninstance)
- [msdyn_msdyn_inspectiondefinition_msdyn_inspectioninstance](#BKMK_msdyn_msdyn_inspectiondefinition_msdyn_inspectioninstance)
- [msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance](#BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance)
- [owner_msdyn_inspectioninstance](#BKMK_owner_msdyn_inspectioninstance)
- [team_msdyn_inspectioninstance](#BKMK_team_msdyn_inspectioninstance)
- [user_msdyn_inspectioninstance](#BKMK_user_msdyn_inspectioninstance)

### <a name="BKMK_business_unit_msdyn_inspectioninstance"></a> business_unit_msdyn_inspectioninstance

One-To-Many Relationship: [businessunit business_unit_msdyn_inspectioninstance](businessunit.md#BKMK_business_unit_msdyn_inspectioninstance)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectioninstance_createdby"></a> lk_msdyn_inspectioninstance_createdby

One-To-Many Relationship: [systemuser lk_msdyn_inspectioninstance_createdby](systemuser.md#BKMK_lk_msdyn_inspectioninstance_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectioninstance_createdonbehalfby"></a> lk_msdyn_inspectioninstance_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_inspectioninstance_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_inspectioninstance_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectioninstance_modifiedby"></a> lk_msdyn_inspectioninstance_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_inspectioninstance_modifiedby](systemuser.md#BKMK_lk_msdyn_inspectioninstance_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_inspectioninstance_modifiedonbehalfby"></a> lk_msdyn_inspectioninstance_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_inspectioninstance_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_inspectioninstance_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_incident_msdyn_inspectioninstance_CaseId"></a> msdyn_incident_msdyn_inspectioninstance_CaseId

One-To-Many Relationship: [incident msdyn_incident_msdyn_inspectioninstance_CaseId](incident.md#BKMK_msdyn_incident_msdyn_inspectioninstance_CaseId)

|Property|Value|
|---|---|
|ReferencedEntity|`incident`|
|ReferencedAttribute|`incidentid`|
|ReferencingAttribute|`msdyn_caseid`|
|ReferencingEntityNavigationPropertyName|`msdyn_CaseId`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_customerasset_msdyn_inspectioninstance_customerassetid"></a> msdyn_msdyn_customerasset_msdyn_inspectioninstance_customerassetid

One-To-Many Relationship: [msdyn_customerasset msdyn_msdyn_customerasset_msdyn_inspectioninstance_customerassetid](msdyn_customerasset.md#BKMK_msdyn_msdyn_customerasset_msdyn_inspectioninstance_customerassetid)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_customerasset`|
|ReferencedAttribute|`msdyn_customerassetid`|
|ReferencingAttribute|`msdyn_customerassetid`|
|ReferencingEntityNavigationPropertyName|`msdyn_CustomerAssetId`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_inspection_msdyn_inspectioninstance"></a> msdyn_msdyn_inspection_msdyn_inspectioninstance

One-To-Many Relationship: [msdyn_inspection msdyn_msdyn_inspection_msdyn_inspectioninstance](msdyn_inspection.md#BKMK_msdyn_msdyn_inspection_msdyn_inspectioninstance)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_inspection`|
|ReferencedAttribute|`msdyn_inspectionid`|
|ReferencingAttribute|`msdyn_inspectiontemplateid`|
|ReferencingEntityNavigationPropertyName|`msdyn_InspectionTemplateId`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_inspectiondefinition_msdyn_inspectioninstance"></a> msdyn_msdyn_inspectiondefinition_msdyn_inspectioninstance

One-To-Many Relationship: [msdyn_inspectiondefinition msdyn_msdyn_inspectiondefinition_msdyn_inspectioninstance](msdyn_inspectiondefinition.md#BKMK_msdyn_msdyn_inspectiondefinition_msdyn_inspectioninstance)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_inspectiondefinition`|
|ReferencedAttribute|`msdyn_inspectiondefinitionid`|
|ReferencingAttribute|`msdyn_inspectiontemplateversionid`|
|ReferencingEntityNavigationPropertyName|`msdyn_InspectionTemplateVersionId`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance"></a> msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance

One-To-Many Relationship: [msdyn_inspectionresponse msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance](msdyn_inspectionresponse.md#BKMK_msdyn_msdyn_inspectionresponse_msdyn_inspectioninstance)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_inspectionresponse`|
|ReferencedAttribute|`msdyn_inspectionresponseid`|
|ReferencingAttribute|`msdyn_inspectionresponseid`|
|ReferencingEntityNavigationPropertyName|`msdyn_inspectionresponseid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_inspectioninstance"></a> owner_msdyn_inspectioninstance

One-To-Many Relationship: [owner owner_msdyn_inspectioninstance](owner.md#BKMK_owner_msdyn_inspectioninstance)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_inspectioninstance"></a> team_msdyn_inspectioninstance

One-To-Many Relationship: [team team_msdyn_inspectioninstance](team.md#BKMK_team_msdyn_inspectioninstance)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_inspectioninstance"></a> user_msdyn_inspectioninstance

One-To-Many Relationship: [systemuser user_msdyn_inspectioninstance](systemuser.md#BKMK_user_msdyn_inspectioninstance)

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

- [msdyn_inspectioninstance_AsyncOperations](#BKMK_msdyn_inspectioninstance_AsyncOperations)
- [msdyn_inspectioninstance_BulkDeleteFailures](#BKMK_msdyn_inspectioninstance_BulkDeleteFailures)
- [msdyn_inspectioninstance_DuplicateBaseRecord](#BKMK_msdyn_inspectioninstance_DuplicateBaseRecord)
- [msdyn_inspectioninstance_DuplicateMatchingRecord](#BKMK_msdyn_inspectioninstance_DuplicateMatchingRecord)
- [msdyn_inspectioninstance_MailboxTrackingFolders](#BKMK_msdyn_inspectioninstance_MailboxTrackingFolders)
- [msdyn_inspectioninstance_PrincipalObjectAttributeAccesses](#BKMK_msdyn_inspectioninstance_PrincipalObjectAttributeAccesses)
- [msdyn_inspectioninstance_ProcessSession](#BKMK_msdyn_inspectioninstance_ProcessSession)
- [msdyn_inspectioninstance_SyncErrors](#BKMK_msdyn_inspectioninstance_SyncErrors)

### <a name="BKMK_msdyn_inspectioninstance_AsyncOperations"></a> msdyn_inspectioninstance_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_inspectioninstance_AsyncOperations](asyncoperation.md#BKMK_msdyn_inspectioninstance_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectioninstance_BulkDeleteFailures"></a> msdyn_inspectioninstance_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_inspectioninstance_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_inspectioninstance_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectioninstance_DuplicateBaseRecord"></a> msdyn_inspectioninstance_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_inspectioninstance_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_inspectioninstance_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectioninstance_DuplicateMatchingRecord"></a> msdyn_inspectioninstance_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_inspectioninstance_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_inspectioninstance_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectioninstance_MailboxTrackingFolders"></a> msdyn_inspectioninstance_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_inspectioninstance_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_inspectioninstance_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectioninstance_PrincipalObjectAttributeAccesses"></a> msdyn_inspectioninstance_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_inspectioninstance_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_inspectioninstance_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectioninstance_ProcessSession"></a> msdyn_inspectioninstance_ProcessSession

Many-To-One Relationship: [processsession msdyn_inspectioninstance_ProcessSession](processsession.md#BKMK_msdyn_inspectioninstance_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_inspectioninstance_SyncErrors"></a> msdyn_inspectioninstance_SyncErrors

Many-To-One Relationship: [syncerror msdyn_inspectioninstance_SyncErrors](syncerror.md#BKMK_msdyn_inspectioninstance_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_inspectioninstance_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

