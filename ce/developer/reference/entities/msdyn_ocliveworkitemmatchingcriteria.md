---
title: "Conversation Matching Criteria (msdyn_ocliveworkitemmatchingcriteria) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Conversation Matching Criteria (msdyn_ocliveworkitemmatchingcriteria) table/entity with Microsoft Dynamics 365."
ms.topic: generated-reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Conversation Matching Criteria (msdyn_ocliveworkitemmatchingcriteria) table/entity reference (Microsoft Dynamics 365)

Contains matching criterias for conversations

## Messages

The following table lists the messages for the Conversation Matching Criteria (msdyn_ocliveworkitemmatchingcriteria) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_ocliveworkitemmatchingcriterias(*msdyn_ocliveworkitemmatchingcriteriaid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Associate`<br />Event: True |[Associate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Associate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-associate-method-or-associaterequest)|
| `BulkRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Create`<br />Event: True |`POST` /msdyn_ocliveworkitemmatchingcriterias<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_ocliveworkitemmatchingcriterias(*msdyn_ocliveworkitemmatchingcriteriaid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Disassociate`<br />Event: True |[Disassociate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Disassociate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-disassociate-method-or-disassociaterequest)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `PurgeRetainedContent`<br />Event: True |<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_ocliveworkitemmatchingcriterias(*msdyn_ocliveworkitemmatchingcriteriaid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_ocliveworkitemmatchingcriterias<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `RollbackRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `SetState`<br />Event: True |`PATCH` /msdyn_ocliveworkitemmatchingcriterias(*msdyn_ocliveworkitemmatchingcriteriaid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_ocliveworkitemmatchingcriterias(*msdyn_ocliveworkitemmatchingcriteriaid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_ocliveworkitemmatchingcriterias(*msdyn_ocliveworkitemmatchingcriteriaid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|
| `ValidateRetentionConfig`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Conversation Matching Criteria (msdyn_ocliveworkitemmatchingcriteria) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Conversation Matching Criteria** |
| **DisplayCollectionName** | **Conversation Matching Criterias** |
| **SchemaName** | `msdyn_ocliveworkitemmatchingcriteria` |
| **CollectionSchemaName** | `msdyn_ocliveworkitemmatchingcriterias` |
| **EntitySetName** | `msdyn_ocliveworkitemmatchingcriterias`|
| **LogicalName** | `msdyn_ocliveworkitemmatchingcriteria` |
| **LogicalCollectionName** | `msdyn_ocliveworkitemmatchingcriterias` |
| **PrimaryIdAttribute** | `msdyn_ocliveworkitemmatchingcriteriaid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_matchingcriteriaid](#BKMK_msdyn_matchingcriteriaid)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_ocliveworkitemid](#BKMK_msdyn_ocliveworkitemid)
- [msdyn_ocliveworkitemmatchingcriteriaId](#BKMK_msdyn_ocliveworkitemmatchingcriteriaId)
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

### <a name="BKMK_msdyn_matchingcriteriaid"></a> msdyn_matchingcriteriaid

|Property|Value|
|---|---|
|Description|**Lookup on the Matching Criteria**|
|DisplayName|**Matching Criteria**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_matchingcriteriaid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_matchingcriteria|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description||
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
|MaxLength|850|

### <a name="BKMK_msdyn_ocliveworkitemid"></a> msdyn_ocliveworkitemid

|Property|Value|
|---|---|
|Description|**Liveworkitem ID**|
|DisplayName|**Conversation**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_ocliveworkitemid`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_ocliveworkitem|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteriaId"></a> msdyn_ocliveworkitemmatchingcriteriaId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Conversation Matching Criteria**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_ocliveworkitemmatchingcriteriaid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

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
|Description|**Status of the Conversation Matching Criteria**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_ocliveworkitemmatchingcriteria_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Conversation Matching Criteria**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_ocliveworkitemmatchingcriteria_statuscode`|

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
|RequiredLevel|SystemRequired|
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

- [business_unit_msdyn_ocliveworkitemmatchingcriteria](#BKMK_business_unit_msdyn_ocliveworkitemmatchingcriteria)
- [lk_msdyn_ocliveworkitemmatchingcriteria_createdby](#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_createdby)
- [lk_msdyn_ocliveworkitemmatchingcriteria_createdonbehalfby](#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_createdonbehalfby)
- [lk_msdyn_ocliveworkitemmatchingcriteria_modifiedby](#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_modifiedby)
- [lk_msdyn_ocliveworkitemmatchingcriteria_modifiedonbehalfby](#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_modifiedonbehalfby)
- [msdyn_ocliveworkitemmatchingcriteria_matchingcriteriaid_msdyn_matchingcriteria](#BKMK_msdyn_ocliveworkitemmatchingcriteria_matchingcriteriaid_msdyn_matchingcriteria)
- [msdyn_ocliveworkitemmatchingcriteria_ocliveworkitemid_msdyn_ocliveworkitem](#BKMK_msdyn_ocliveworkitemmatchingcriteria_ocliveworkitemid_msdyn_ocliveworkitem)
- [owner_msdyn_ocliveworkitemmatchingcriteria](#BKMK_owner_msdyn_ocliveworkitemmatchingcriteria)
- [team_msdyn_ocliveworkitemmatchingcriteria](#BKMK_team_msdyn_ocliveworkitemmatchingcriteria)
- [user_msdyn_ocliveworkitemmatchingcriteria](#BKMK_user_msdyn_ocliveworkitemmatchingcriteria)

### <a name="BKMK_business_unit_msdyn_ocliveworkitemmatchingcriteria"></a> business_unit_msdyn_ocliveworkitemmatchingcriteria

One-To-Many Relationship: [businessunit business_unit_msdyn_ocliveworkitemmatchingcriteria](businessunit.md#BKMK_business_unit_msdyn_ocliveworkitemmatchingcriteria)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_createdby"></a> lk_msdyn_ocliveworkitemmatchingcriteria_createdby

One-To-Many Relationship: [systemuser lk_msdyn_ocliveworkitemmatchingcriteria_createdby](systemuser.md#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_createdonbehalfby"></a> lk_msdyn_ocliveworkitemmatchingcriteria_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_ocliveworkitemmatchingcriteria_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_modifiedby"></a> lk_msdyn_ocliveworkitemmatchingcriteria_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_ocliveworkitemmatchingcriteria_modifiedby](systemuser.md#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_modifiedonbehalfby"></a> lk_msdyn_ocliveworkitemmatchingcriteria_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_ocliveworkitemmatchingcriteria_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_ocliveworkitemmatchingcriteria_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_matchingcriteriaid_msdyn_matchingcriteria"></a> msdyn_ocliveworkitemmatchingcriteria_matchingcriteriaid_msdyn_matchingcriteria

One-To-Many Relationship: [msdyn_matchingcriteria msdyn_ocliveworkitemmatchingcriteria_matchingcriteriaid_msdyn_matchingcriteria](msdyn_matchingcriteria.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_matchingcriteriaid_msdyn_matchingcriteria)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_matchingcriteria`|
|ReferencedAttribute|`msdyn_matchingcriteriaid`|
|ReferencingAttribute|`msdyn_matchingcriteriaid`|
|ReferencingEntityNavigationPropertyName|`msdyn_matchingcriteriaid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `RemoveLink`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_ocliveworkitemid_msdyn_ocliveworkitem"></a> msdyn_ocliveworkitemmatchingcriteria_ocliveworkitemid_msdyn_ocliveworkitem

One-To-Many Relationship: [msdyn_ocliveworkitem msdyn_ocliveworkitemmatchingcriteria_ocliveworkitemid_msdyn_ocliveworkitem](msdyn_ocliveworkitem.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_ocliveworkitemid_msdyn_ocliveworkitem)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_ocliveworkitem`|
|ReferencedAttribute|`activityid`|
|ReferencingAttribute|`msdyn_ocliveworkitemid`|
|ReferencingEntityNavigationPropertyName|`msdyn_ocliveworkitemid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `RemoveLink`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_ocliveworkitemmatchingcriteria"></a> owner_msdyn_ocliveworkitemmatchingcriteria

One-To-Many Relationship: [owner owner_msdyn_ocliveworkitemmatchingcriteria](owner.md#BKMK_owner_msdyn_ocliveworkitemmatchingcriteria)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_ocliveworkitemmatchingcriteria"></a> team_msdyn_ocliveworkitemmatchingcriteria

One-To-Many Relationship: [team team_msdyn_ocliveworkitemmatchingcriteria](team.md#BKMK_team_msdyn_ocliveworkitemmatchingcriteria)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_ocliveworkitemmatchingcriteria"></a> user_msdyn_ocliveworkitemmatchingcriteria

One-To-Many Relationship: [systemuser user_msdyn_ocliveworkitemmatchingcriteria](systemuser.md#BKMK_user_msdyn_ocliveworkitemmatchingcriteria)

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

- [msdyn_ocliveworkitemmatchingcriteria_AsyncOperations](#BKMK_msdyn_ocliveworkitemmatchingcriteria_AsyncOperations)
- [msdyn_ocliveworkitemmatchingcriteria_BulkDeleteFailures](#BKMK_msdyn_ocliveworkitemmatchingcriteria_BulkDeleteFailures)
- [msdyn_ocliveworkitemmatchingcriteria_DuplicateBaseRecord](#BKMK_msdyn_ocliveworkitemmatchingcriteria_DuplicateBaseRecord)
- [msdyn_ocliveworkitemmatchingcriteria_DuplicateMatchingRecord](#BKMK_msdyn_ocliveworkitemmatchingcriteria_DuplicateMatchingRecord)
- [msdyn_ocliveworkitemmatchingcriteria_MailboxTrackingFolders](#BKMK_msdyn_ocliveworkitemmatchingcriteria_MailboxTrackingFolders)
- [msdyn_ocliveworkitemmatchingcriteria_PrincipalObjectAttributeAccesses](#BKMK_msdyn_ocliveworkitemmatchingcriteria_PrincipalObjectAttributeAccesses)
- [msdyn_ocliveworkitemmatchingcriteria_ProcessSession](#BKMK_msdyn_ocliveworkitemmatchingcriteria_ProcessSession)
- [msdyn_ocliveworkitemmatchingcriteria_SyncErrors](#BKMK_msdyn_ocliveworkitemmatchingcriteria_SyncErrors)

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_AsyncOperations"></a> msdyn_ocliveworkitemmatchingcriteria_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_ocliveworkitemmatchingcriteria_AsyncOperations](asyncoperation.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_BulkDeleteFailures"></a> msdyn_ocliveworkitemmatchingcriteria_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_ocliveworkitemmatchingcriteria_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_DuplicateBaseRecord"></a> msdyn_ocliveworkitemmatchingcriteria_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_ocliveworkitemmatchingcriteria_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_DuplicateMatchingRecord"></a> msdyn_ocliveworkitemmatchingcriteria_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_ocliveworkitemmatchingcriteria_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_MailboxTrackingFolders"></a> msdyn_ocliveworkitemmatchingcriteria_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_ocliveworkitemmatchingcriteria_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_PrincipalObjectAttributeAccesses"></a> msdyn_ocliveworkitemmatchingcriteria_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_ocliveworkitemmatchingcriteria_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_ProcessSession"></a> msdyn_ocliveworkitemmatchingcriteria_ProcessSession

Many-To-One Relationship: [processsession msdyn_ocliveworkitemmatchingcriteria_ProcessSession](processsession.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ocliveworkitemmatchingcriteria_SyncErrors"></a> msdyn_ocliveworkitemmatchingcriteria_SyncErrors

Many-To-One Relationship: [syncerror msdyn_ocliveworkitemmatchingcriteria_SyncErrors](syncerror.md#BKMK_msdyn_ocliveworkitemmatchingcriteria_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_ocliveworkitemmatchingcriteria_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

