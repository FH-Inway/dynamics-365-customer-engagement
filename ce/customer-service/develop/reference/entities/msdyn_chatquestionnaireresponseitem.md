---
title: "Survey Response Value (msdyn_chatquestionnaireresponseitem) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Survey Response Value (msdyn_chatquestionnaireresponseitem) table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Survey Response Value (msdyn_chatquestionnaireresponseitem) table/entity reference (Microsoft Dynamics 365 Customer Service)

Stores survey response values

## Messages

The following table lists the messages for the Survey Response Value (msdyn_chatquestionnaireresponseitem) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_chatquestionnaireresponseitems(*msdyn_chatquestionnaireresponseitemid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Associate`<br />Event: True |[Associate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Associate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-associate-method-or-associaterequest)|
| `BulkRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Create`<br />Event: True |`POST` /msdyn_chatquestionnaireresponseitems<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_chatquestionnaireresponseitems(*msdyn_chatquestionnaireresponseitemid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Disassociate`<br />Event: True |[Disassociate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Disassociate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-disassociate-method-or-disassociaterequest)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `PurgeRetainedContent`<br />Event: True |<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_chatquestionnaireresponseitems(*msdyn_chatquestionnaireresponseitemid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_chatquestionnaireresponseitems<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `RollbackRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `SetState`<br />Event: True |`PATCH` /msdyn_chatquestionnaireresponseitems(*msdyn_chatquestionnaireresponseitemid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_chatquestionnaireresponseitems(*msdyn_chatquestionnaireresponseitemid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_chatquestionnaireresponseitems(*msdyn_chatquestionnaireresponseitemid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|
| `ValidateRetentionConfig`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Survey Response Value (msdyn_chatquestionnaireresponseitem) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Survey Response Value** |
| **DisplayCollectionName** | **Survey Response Values** |
| **SchemaName** | `msdyn_chatquestionnaireresponseitem` |
| **CollectionSchemaName** | `msdyn_chatquestionnaireresponseitems` |
| **EntitySetName** | `msdyn_chatquestionnaireresponseitems`|
| **LogicalName** | `msdyn_chatquestionnaireresponseitem` |
| **LogicalCollectionName** | `msdyn_chatquestionnaireresponseitems` |
| **PrimaryIdAttribute** | `msdyn_chatquestionnaireresponseitemid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_chatansweroptionid](#BKMK_msdyn_chatansweroptionid)
- [msdyn_ChatAnswerText](#BKMK_msdyn_ChatAnswerText)
- [msdyn_ChatQuestionnaireResponseId](#BKMK_msdyn_ChatQuestionnaireResponseId)
- [msdyn_chatquestionnaireresponseitemId](#BKMK_msdyn_chatquestionnaireresponseitemId)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_surveyquestionid](#BKMK_msdyn_surveyquestionid)
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

### <a name="BKMK_msdyn_chatansweroptionid"></a> msdyn_chatansweroptionid

|Property|Value|
|---|---|
|Description|**Survey answer option**|
|DisplayName|**Survey answer option**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_chatansweroptionid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_chatansweroption|

### <a name="BKMK_msdyn_ChatAnswerText"></a> msdyn_ChatAnswerText

|Property|Value|
|---|---|
|Description|**Survey answer text**|
|DisplayName|**Survey answer text**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_chatanswertext`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|500|

### <a name="BKMK_msdyn_ChatQuestionnaireResponseId"></a> msdyn_ChatQuestionnaireResponseId

|Property|Value|
|---|---|
|Description|**Survey response**|
|DisplayName|**Survey response**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_chatquestionnaireresponseid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_chatquestionnaireresponse|

### <a name="BKMK_msdyn_chatquestionnaireresponseitemId"></a> msdyn_chatquestionnaireresponseitemId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Survey Response Values**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_chatquestionnaireresponseitemid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_name`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|512|

### <a name="BKMK_msdyn_surveyquestionid"></a> msdyn_surveyquestionid

|Property|Value|
|---|---|
|Description|**Survey Question Id**|
|DisplayName|**Survey Question Id**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_surveyquestionid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_surveyquestion|

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
|Description|**Status of the Survey Response value**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_chatquestionnaireresponseitem_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Survey response value**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_chatquestionnaireresponseitem_statuscode`|

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

- [business_unit_msdyn_chatquestionnaireresponseitem](#BKMK_business_unit_msdyn_chatquestionnaireresponseitem)
- [lk_msdyn_chatquestionnaireresponseitem_createdby](#BKMK_lk_msdyn_chatquestionnaireresponseitem_createdby)
- [lk_msdyn_chatquestionnaireresponseitem_createdonbehalfby](#BKMK_lk_msdyn_chatquestionnaireresponseitem_createdonbehalfby)
- [lk_msdyn_chatquestionnaireresponseitem_modifiedby](#BKMK_lk_msdyn_chatquestionnaireresponseitem_modifiedby)
- [lk_msdyn_chatquestionnaireresponseitem_modifiedonbehalfby](#BKMK_lk_msdyn_chatquestionnaireresponseitem_modifiedonbehalfby)
- [msdyn_msdyn_chatansweroption_msdyn_chatquestionnaireresponseitem](#BKMK_msdyn_msdyn_chatansweroption_msdyn_chatquestionnaireresponseitem)
- [msdyn_msdyn_chatquestionnaireresponse_msdyn_chatquestionnaireresponseitem_nested](#BKMK_msdyn_msdyn_chatquestionnaireresponse_msdyn_chatquestionnaireresponseitem_nested)
- [msdyn_msdyn_surveyquestion_msdyn_chatquestionnaireresponseitem](#BKMK_msdyn_msdyn_surveyquestion_msdyn_chatquestionnaireresponseitem)
- [owner_msdyn_chatquestionnaireresponseitem](#BKMK_owner_msdyn_chatquestionnaireresponseitem)
- [team_msdyn_chatquestionnaireresponseitem](#BKMK_team_msdyn_chatquestionnaireresponseitem)
- [user_msdyn_chatquestionnaireresponseitem](#BKMK_user_msdyn_chatquestionnaireresponseitem)

### <a name="BKMK_business_unit_msdyn_chatquestionnaireresponseitem"></a> business_unit_msdyn_chatquestionnaireresponseitem

One-To-Many Relationship: [businessunit business_unit_msdyn_chatquestionnaireresponseitem](businessunit.md#BKMK_business_unit_msdyn_chatquestionnaireresponseitem)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_chatquestionnaireresponseitem_createdby"></a> lk_msdyn_chatquestionnaireresponseitem_createdby

One-To-Many Relationship: [systemuser lk_msdyn_chatquestionnaireresponseitem_createdby](systemuser.md#BKMK_lk_msdyn_chatquestionnaireresponseitem_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_chatquestionnaireresponseitem_createdonbehalfby"></a> lk_msdyn_chatquestionnaireresponseitem_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_chatquestionnaireresponseitem_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_chatquestionnaireresponseitem_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_chatquestionnaireresponseitem_modifiedby"></a> lk_msdyn_chatquestionnaireresponseitem_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_chatquestionnaireresponseitem_modifiedby](systemuser.md#BKMK_lk_msdyn_chatquestionnaireresponseitem_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_chatquestionnaireresponseitem_modifiedonbehalfby"></a> lk_msdyn_chatquestionnaireresponseitem_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_chatquestionnaireresponseitem_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_chatquestionnaireresponseitem_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_chatansweroption_msdyn_chatquestionnaireresponseitem"></a> msdyn_msdyn_chatansweroption_msdyn_chatquestionnaireresponseitem

One-To-Many Relationship: [msdyn_chatansweroption msdyn_msdyn_chatansweroption_msdyn_chatquestionnaireresponseitem](msdyn_chatansweroption.md#BKMK_msdyn_msdyn_chatansweroption_msdyn_chatquestionnaireresponseitem)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_chatansweroption`|
|ReferencedAttribute|`msdyn_chatansweroptionid`|
|ReferencingAttribute|`msdyn_chatansweroptionid`|
|ReferencingEntityNavigationPropertyName|`msdyn_chatansweroptionid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_chatquestionnaireresponse_msdyn_chatquestionnaireresponseitem_nested"></a> msdyn_msdyn_chatquestionnaireresponse_msdyn_chatquestionnaireresponseitem_nested

One-To-Many Relationship: [msdyn_chatquestionnaireresponse msdyn_msdyn_chatquestionnaireresponse_msdyn_chatquestionnaireresponseitem_nested](msdyn_chatquestionnaireresponse.md#BKMK_msdyn_msdyn_chatquestionnaireresponse_msdyn_chatquestionnaireresponseitem_nested)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_chatquestionnaireresponse`|
|ReferencedAttribute|`msdyn_chatquestionnaireresponseid`|
|ReferencingAttribute|`msdyn_chatquestionnaireresponseid`|
|ReferencingEntityNavigationPropertyName|`msdyn_ChatQuestionnaireResponseId`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_surveyquestion_msdyn_chatquestionnaireresponseitem"></a> msdyn_msdyn_surveyquestion_msdyn_chatquestionnaireresponseitem

One-To-Many Relationship: [msdyn_surveyquestion msdyn_msdyn_surveyquestion_msdyn_chatquestionnaireresponseitem](msdyn_surveyquestion.md#BKMK_msdyn_msdyn_surveyquestion_msdyn_chatquestionnaireresponseitem)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_surveyquestion`|
|ReferencedAttribute|`msdyn_surveyquestionid`|
|ReferencingAttribute|`msdyn_surveyquestionid`|
|ReferencingEntityNavigationPropertyName|`msdyn_surveyquestionid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_chatquestionnaireresponseitem"></a> owner_msdyn_chatquestionnaireresponseitem

One-To-Many Relationship: [owner owner_msdyn_chatquestionnaireresponseitem](owner.md#BKMK_owner_msdyn_chatquestionnaireresponseitem)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_chatquestionnaireresponseitem"></a> team_msdyn_chatquestionnaireresponseitem

One-To-Many Relationship: [team team_msdyn_chatquestionnaireresponseitem](team.md#BKMK_team_msdyn_chatquestionnaireresponseitem)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_chatquestionnaireresponseitem"></a> user_msdyn_chatquestionnaireresponseitem

One-To-Many Relationship: [systemuser user_msdyn_chatquestionnaireresponseitem](systemuser.md#BKMK_user_msdyn_chatquestionnaireresponseitem)

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

- [msdyn_chatquestionnaireresponseitem_AsyncOperations](#BKMK_msdyn_chatquestionnaireresponseitem_AsyncOperations)
- [msdyn_chatquestionnaireresponseitem_BulkDeleteFailures](#BKMK_msdyn_chatquestionnaireresponseitem_BulkDeleteFailures)
- [msdyn_chatquestionnaireresponseitem_MailboxTrackingFolders](#BKMK_msdyn_chatquestionnaireresponseitem_MailboxTrackingFolders)
- [msdyn_chatquestionnaireresponseitem_PrincipalObjectAttributeAccesses](#BKMK_msdyn_chatquestionnaireresponseitem_PrincipalObjectAttributeAccesses)
- [msdyn_chatquestionnaireresponseitem_ProcessSession](#BKMK_msdyn_chatquestionnaireresponseitem_ProcessSession)
- [msdyn_chatquestionnaireresponseitem_SyncErrors](#BKMK_msdyn_chatquestionnaireresponseitem_SyncErrors)

### <a name="BKMK_msdyn_chatquestionnaireresponseitem_AsyncOperations"></a> msdyn_chatquestionnaireresponseitem_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_chatquestionnaireresponseitem_AsyncOperations](asyncoperation.md#BKMK_msdyn_chatquestionnaireresponseitem_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_chatquestionnaireresponseitem_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_chatquestionnaireresponseitem_BulkDeleteFailures"></a> msdyn_chatquestionnaireresponseitem_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_chatquestionnaireresponseitem_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_chatquestionnaireresponseitem_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_chatquestionnaireresponseitem_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_chatquestionnaireresponseitem_MailboxTrackingFolders"></a> msdyn_chatquestionnaireresponseitem_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_chatquestionnaireresponseitem_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_chatquestionnaireresponseitem_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_chatquestionnaireresponseitem_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_chatquestionnaireresponseitem_PrincipalObjectAttributeAccesses"></a> msdyn_chatquestionnaireresponseitem_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_chatquestionnaireresponseitem_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_chatquestionnaireresponseitem_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_chatquestionnaireresponseitem_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_chatquestionnaireresponseitem_ProcessSession"></a> msdyn_chatquestionnaireresponseitem_ProcessSession

Many-To-One Relationship: [processsession msdyn_chatquestionnaireresponseitem_ProcessSession](processsession.md#BKMK_msdyn_chatquestionnaireresponseitem_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_chatquestionnaireresponseitem_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_chatquestionnaireresponseitem_SyncErrors"></a> msdyn_chatquestionnaireresponseitem_SyncErrors

Many-To-One Relationship: [syncerror msdyn_chatquestionnaireresponseitem_SyncErrors](syncerror.md#BKMK_msdyn_chatquestionnaireresponseitem_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_chatquestionnaireresponseitem_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

