---
title: "Swarm participant (msdyn_swarmparticipant) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Swarm participant (msdyn_swarmparticipant) table/entity with Microsoft Dynamics 365."
ms.date: 08.01.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Swarm participant (msdyn_swarmparticipant) table/entity reference

Stores the participants information of swarm

## Messages

The following table lists the messages for the Swarm participant (msdyn_swarmparticipant) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_swarmparticipants(*msdyn_swarmparticipantid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_swarmparticipants<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_swarmparticipants(*msdyn_swarmparticipantid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_swarmparticipants(*msdyn_swarmparticipantid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_swarmparticipants<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_swarmparticipants(*msdyn_swarmparticipantid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_swarmparticipants(*msdyn_swarmparticipantid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_swarmparticipants(*msdyn_swarmparticipantid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Swarm participant (msdyn_swarmparticipant) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Swarm participant (msdyn_swarmparticipant) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Swarm participant** |
| **DisplayCollectionName** | **Swarm participants** |
| **SchemaName** | `msdyn_swarmparticipant` |
| **CollectionSchemaName** | `msdyn_swarmparticipants` |
| **EntitySetName** | `msdyn_swarmparticipants`|
| **LogicalName** | `msdyn_swarmparticipant` |
| **LogicalCollectionName** | `msdyn_swarmparticipants` |
| **PrimaryIdAttribute** | `msdyn_swarmparticipantid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_acceptedon](#BKMK_msdyn_acceptedon)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_rejectedon](#BKMK_msdyn_rejectedon)
- [msdyn_rejectedreason](#BKMK_msdyn_rejectedreason)
- [msdyn_swarmid](#BKMK_msdyn_swarmid)
- [msdyn_swarmparticipantId](#BKMK_msdyn_swarmparticipantId)
- [msdyn_swarmroleid](#BKMK_msdyn_swarmroleid)
- [msdyn_userid](#BKMK_msdyn_userid)
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

### <a name="BKMK_msdyn_acceptedon"></a> msdyn_acceptedon

|Property|Value|
|---|---|
|Description|**Time when participant accepts the chat invitation**|
|DisplayName|**Accepted on**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_acceptedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

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
|MaxLength|100|

### <a name="BKMK_msdyn_rejectedon"></a> msdyn_rejectedon

|Property|Value|
|---|---|
|Description|**Time when participant rejected the chat invitation**|
|DisplayName|**Rejected on**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_rejectedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_rejectedreason"></a> msdyn_rejectedreason

|Property|Value|
|---|---|
|Description|**Reason for the rejection of swarm request**|
|DisplayName|**Rejected reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_rejectedreason`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

### <a name="BKMK_msdyn_swarmid"></a> msdyn_swarmid

|Property|Value|
|---|---|
|Description|**Lookup to the swarm record**|
|DisplayName|**Swarm**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_swarmid`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_swarm|

### <a name="BKMK_msdyn_swarmparticipantId"></a> msdyn_swarmparticipantId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Swarm participant**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_swarmparticipantid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_swarmroleid"></a> msdyn_swarmroleid

|Property|Value|
|---|---|
|Description|**Lookup to the swarm role record**|
|DisplayName|**Participant role**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_swarmroleid`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_swarmrole|

### <a name="BKMK_msdyn_userid"></a> msdyn_userid

|Property|Value|
|---|---|
|Description|**Lookup to the user record**|
|DisplayName|**User**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_userid`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|systemuser|

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
|Description|**Status of the swarm participant**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_swarmparticipant_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Invited**<br />DefaultStatus: 0<br />InvariantName: `Invited`|
|1|Label: **Accepted**<br />DefaultStatus: 0<br />InvariantName: `Accepted`|
|2|Label: **Rejected**<br />DefaultStatus: 0<br />InvariantName: `Rejected`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the swarm participant**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_swarmparticipant_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|192350001|Label: **Accepted**<br />State:1<br />TransitionData: None|
|192350002|Label: **Autoaccepted**<br />State:1<br />TransitionData: None|
|192350003|Label: **Invited**<br />State:0<br />TransitionData: None|
|192350004|Label: **Rejected**<br />State:2<br />TransitionData: None|

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

- [business_unit_msdyn_swarmparticipant](#BKMK_business_unit_msdyn_swarmparticipant)
- [lk_msdyn_swarmparticipant_createdby](#BKMK_lk_msdyn_swarmparticipant_createdby)
- [lk_msdyn_swarmparticipant_createdonbehalfby](#BKMK_lk_msdyn_swarmparticipant_createdonbehalfby)
- [lk_msdyn_swarmparticipant_modifiedby](#BKMK_lk_msdyn_swarmparticipant_modifiedby)
- [lk_msdyn_swarmparticipant_modifiedonbehalfby](#BKMK_lk_msdyn_swarmparticipant_modifiedonbehalfby)
- [msdyn_msdyn_swarm_msdyn_swarmparticipant_swarmid](#BKMK_msdyn_msdyn_swarm_msdyn_swarmparticipant_swarmid)
- [msdyn_msdyn_swarmrole_msdyn_swarmparticipant_swarmroleid](#BKMK_msdyn_msdyn_swarmrole_msdyn_swarmparticipant_swarmroleid)
- [msdyn_systemuser_msdyn_swarmparticipant_userid](#BKMK_msdyn_systemuser_msdyn_swarmparticipant_userid)
- [owner_msdyn_swarmparticipant](#BKMK_owner_msdyn_swarmparticipant)
- [team_msdyn_swarmparticipant](#BKMK_team_msdyn_swarmparticipant)
- [user_msdyn_swarmparticipant](#BKMK_user_msdyn_swarmparticipant)

### <a name="BKMK_business_unit_msdyn_swarmparticipant"></a> business_unit_msdyn_swarmparticipant

One-To-Many Relationship: [businessunit business_unit_msdyn_swarmparticipant](businessunit.md#BKMK_business_unit_msdyn_swarmparticipant)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_swarmparticipant_createdby"></a> lk_msdyn_swarmparticipant_createdby

One-To-Many Relationship: [systemuser lk_msdyn_swarmparticipant_createdby](systemuser.md#BKMK_lk_msdyn_swarmparticipant_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_swarmparticipant_createdonbehalfby"></a> lk_msdyn_swarmparticipant_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_swarmparticipant_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_swarmparticipant_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_swarmparticipant_modifiedby"></a> lk_msdyn_swarmparticipant_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_swarmparticipant_modifiedby](systemuser.md#BKMK_lk_msdyn_swarmparticipant_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_swarmparticipant_modifiedonbehalfby"></a> lk_msdyn_swarmparticipant_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_swarmparticipant_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_swarmparticipant_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_swarm_msdyn_swarmparticipant_swarmid"></a> msdyn_msdyn_swarm_msdyn_swarmparticipant_swarmid

One-To-Many Relationship: [msdyn_swarm msdyn_msdyn_swarm_msdyn_swarmparticipant_swarmid](msdyn_swarm.md#BKMK_msdyn_msdyn_swarm_msdyn_swarmparticipant_swarmid)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_swarm`|
|ReferencedAttribute|`msdyn_swarmid`|
|ReferencingAttribute|`msdyn_swarmid`|
|ReferencingEntityNavigationPropertyName|`msdyn_swarmid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_msdyn_swarmrole_msdyn_swarmparticipant_swarmroleid"></a> msdyn_msdyn_swarmrole_msdyn_swarmparticipant_swarmroleid

One-To-Many Relationship: [msdyn_swarmrole msdyn_msdyn_swarmrole_msdyn_swarmparticipant_swarmroleid](msdyn_swarmrole.md#BKMK_msdyn_msdyn_swarmrole_msdyn_swarmparticipant_swarmroleid)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_swarmrole`|
|ReferencedAttribute|`msdyn_swarmroleid`|
|ReferencingAttribute|`msdyn_swarmroleid`|
|ReferencingEntityNavigationPropertyName|`msdyn_swarmroleid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_systemuser_msdyn_swarmparticipant_userid"></a> msdyn_systemuser_msdyn_swarmparticipant_userid

One-To-Many Relationship: [systemuser msdyn_systemuser_msdyn_swarmparticipant_userid](systemuser.md#BKMK_msdyn_systemuser_msdyn_swarmparticipant_userid)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`msdyn_userid`|
|ReferencingEntityNavigationPropertyName|`msdyn_userid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_swarmparticipant"></a> owner_msdyn_swarmparticipant

One-To-Many Relationship: [owner owner_msdyn_swarmparticipant](owner.md#BKMK_owner_msdyn_swarmparticipant)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_swarmparticipant"></a> team_msdyn_swarmparticipant

One-To-Many Relationship: [team team_msdyn_swarmparticipant](team.md#BKMK_team_msdyn_swarmparticipant)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_swarmparticipant"></a> user_msdyn_swarmparticipant

One-To-Many Relationship: [systemuser user_msdyn_swarmparticipant](systemuser.md#BKMK_user_msdyn_swarmparticipant)

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

- [msdyn_swarmparticipant_AsyncOperations](#BKMK_msdyn_swarmparticipant_AsyncOperations)
- [msdyn_swarmparticipant_BulkDeleteFailures](#BKMK_msdyn_swarmparticipant_BulkDeleteFailures)
- [msdyn_swarmparticipant_DuplicateBaseRecord](#BKMK_msdyn_swarmparticipant_DuplicateBaseRecord)
- [msdyn_swarmparticipant_DuplicateMatchingRecord](#BKMK_msdyn_swarmparticipant_DuplicateMatchingRecord)
- [msdyn_swarmparticipant_MailboxTrackingFolders](#BKMK_msdyn_swarmparticipant_MailboxTrackingFolders)
- [msdyn_swarmparticipant_PrincipalObjectAttributeAccesses](#BKMK_msdyn_swarmparticipant_PrincipalObjectAttributeAccesses)
- [msdyn_swarmparticipant_ProcessSession](#BKMK_msdyn_swarmparticipant_ProcessSession)
- [msdyn_swarmparticipant_SyncErrors](#BKMK_msdyn_swarmparticipant_SyncErrors)

### <a name="BKMK_msdyn_swarmparticipant_AsyncOperations"></a> msdyn_swarmparticipant_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_swarmparticipant_AsyncOperations](asyncoperation.md#BKMK_msdyn_swarmparticipant_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarmparticipant_BulkDeleteFailures"></a> msdyn_swarmparticipant_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_swarmparticipant_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_swarmparticipant_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarmparticipant_DuplicateBaseRecord"></a> msdyn_swarmparticipant_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_swarmparticipant_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_swarmparticipant_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarmparticipant_DuplicateMatchingRecord"></a> msdyn_swarmparticipant_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_swarmparticipant_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_swarmparticipant_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarmparticipant_MailboxTrackingFolders"></a> msdyn_swarmparticipant_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_swarmparticipant_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_swarmparticipant_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarmparticipant_PrincipalObjectAttributeAccesses"></a> msdyn_swarmparticipant_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_swarmparticipant_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_swarmparticipant_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarmparticipant_ProcessSession"></a> msdyn_swarmparticipant_ProcessSession

Many-To-One Relationship: [processsession msdyn_swarmparticipant_ProcessSession](processsession.md#BKMK_msdyn_swarmparticipant_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_swarmparticipant_SyncErrors"></a> msdyn_swarmparticipant_SyncErrors

Many-To-One Relationship: [syncerror msdyn_swarmparticipant_SyncErrors](syncerror.md#BKMK_msdyn_swarmparticipant_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_swarmparticipant_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

