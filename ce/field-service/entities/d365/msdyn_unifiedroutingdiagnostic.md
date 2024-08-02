---
title: "Routing diagnostic item (msdyn_unifiedroutingdiagnostic) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Routing diagnostic item (msdyn_unifiedroutingdiagnostic) table/entity with Microsoft Dynamics 365."
ms.date: 08.01.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Routing diagnostic item (msdyn_unifiedroutingdiagnostic) table/entity reference

The entity used to store unified routing diagnostic data.

## Messages

The following table lists the messages for the Routing diagnostic item (msdyn_unifiedroutingdiagnostic) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_unifiedroutingdiagnostics(*msdyn_unifiedroutingdiagnosticid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_unifiedroutingdiagnostics<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_unifiedroutingdiagnostics(*msdyn_unifiedroutingdiagnosticid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_unifiedroutingdiagnostics(*msdyn_unifiedroutingdiagnosticid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_unifiedroutingdiagnostics<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_unifiedroutingdiagnostics(*msdyn_unifiedroutingdiagnosticid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_unifiedroutingdiagnostics(*msdyn_unifiedroutingdiagnosticid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_unifiedroutingdiagnostics(*msdyn_unifiedroutingdiagnosticid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Routing diagnostic item (msdyn_unifiedroutingdiagnostic) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Routing diagnostic item (msdyn_unifiedroutingdiagnostic) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Routing diagnostic item** |
| **DisplayCollectionName** | **Routing diagnostic items** |
| **SchemaName** | `msdyn_unifiedroutingdiagnostic` |
| **CollectionSchemaName** | `msdyn_unifiedroutingdiagnostics` |
| **EntitySetName** | `msdyn_unifiedroutingdiagnostics`|
| **LogicalName** | `msdyn_unifiedroutingdiagnostic` |
| **LogicalCollectionName** | `msdyn_unifiedroutingdiagnostics` |
| **PrimaryIdAttribute** | `msdyn_unifiedroutingdiagnosticid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_completedon](#BKMK_msdyn_completedon)
- [msdyn_decisionrulesetid](#BKMK_msdyn_decisionrulesetid)
- [msdyn_diagnosticdata](#BKMK_msdyn_diagnosticdata)
- [msdyn_diagnosticdatatype](#BKMK_msdyn_diagnosticdatatype)
- [msdyn_evaluation](#BKMK_msdyn_evaluation)
- [msdyn_inputdata](#BKMK_msdyn_inputdata)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_ocliveworkitemid](#BKMK_msdyn_ocliveworkitemid)
- [msdyn_outputdata](#BKMK_msdyn_outputdata)
- [msdyn_ruletype](#BKMK_msdyn_ruletype)
- [msdyn_sequencenumber](#BKMK_msdyn_sequencenumber)
- [msdyn_startedon](#BKMK_msdyn_startedon)
- [msdyn_targetobject](#BKMK_msdyn_targetobject)
- [msdyn_targetobjectIdType](#BKMK_msdyn_targetobjectIdType)
- [msdyn_unifiedroutingdiagnosticId](#BKMK_msdyn_unifiedroutingdiagnosticId)
- [msdyn_unifiedroutingrunid](#BKMK_msdyn_unifiedroutingrunid)
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

### <a name="BKMK_msdyn_completedon"></a> msdyn_completedon

|Property|Value|
|---|---|
|Description|**Date and time when the rule execution was completed.**|
|DisplayName|**Completed On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_completedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_decisionrulesetid"></a> msdyn_decisionrulesetid

|Property|Value|
|---|---|
|Description|**Unique identifier for Decision rule set associated with unifiedroutingdiagnostic.**|
|DisplayName|**Decision Rule Set Id**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_decisionrulesetid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_decisionruleset|

### <a name="BKMK_msdyn_diagnosticdata"></a> msdyn_diagnosticdata

|Property|Value|
|---|---|
|Description|**Diagnostics data**|
|DisplayName|**Diagnostics Data**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_diagnosticdata`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

### <a name="BKMK_msdyn_diagnosticdatatype"></a> msdyn_diagnosticdatatype

|Property|Value|
|---|---|
|Description|**Diagnostic Data type**|
|DisplayName|**Diagnostic Data Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_diagnosticdatatype`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_unifiedroutingdiagnostic_msdyn_diagnosticdatatype`|

#### msdyn_diagnosticdatatype Choices/Options

|Value|Label|
|---|---|
|0|**Unknown**|
|1|**Demand ML Diagnostic**|
|2|**Demand Classification Diagnostic**|
|3|**Demand RTQ Diagnostic**|
|4|**Assignment Diagnostic**|

### <a name="BKMK_msdyn_evaluation"></a> msdyn_evaluation

|Property|Value|
|---|---|
|Description|**Evaluation**|
|DisplayName|**Evaluation**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_evaluation`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

### <a name="BKMK_msdyn_inputdata"></a> msdyn_inputdata

|Property|Value|
|---|---|
|Description|**Input data**|
|DisplayName|**Input Data**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_inputdata`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**Name of the unifiedroutingdiagnostic record**|
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
|MaxLength|200|

### <a name="BKMK_msdyn_ocliveworkitemid"></a> msdyn_ocliveworkitemid

|Property|Value|
|---|---|
|Description|**Unique identifier for Conversation associated with unifiedroutingdiagnostic.**|
|DisplayName|**Work item**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_ocliveworkitemid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_ocliveworkitem|

### <a name="BKMK_msdyn_outputdata"></a> msdyn_outputdata

|Property|Value|
|---|---|
|Description|**Output data**|
|DisplayName|**Output Data**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_outputdata`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

### <a name="BKMK_msdyn_ruletype"></a> msdyn_ruletype

|Property|Value|
|---|---|
|Description|**Rule type**|
|DisplayName|**Rule Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_ruletype`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_unifiedroutingdiagnostic_msdyn_ruletype`|

#### msdyn_ruletype Choices/Options

|Value|Label|
|---|---|
|1|**Demand Classification**|
|2|**Route To Queue**|
|3|**Skill Identification**|
|4|**ML**|
|5|**Prioritization**|
|6|**Assignment**|
|9|**Assignment Selection Criteria**|
|11|**Intake**|
|12|**Custom API Classification**|
|13|**Custom API Route to Queue**|
|20|**ICD Route To Queue**|

### <a name="BKMK_msdyn_sequencenumber"></a> msdyn_sequencenumber

|Property|Value|
|---|---|
|Description|**Sequence number**|
|DisplayName|**Sequence Number**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_sequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_startedon"></a> msdyn_startedon

|Property|Value|
|---|---|
|Description|**Date and time when the rule execution was started.**|
|DisplayName|**Started On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_startedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_targetobject"></a> msdyn_targetobject

|Property|Value|
|---|---|
|Description|**Unique identifier for the target object associated with unifiedroutingdiagnostic.**|
|DisplayName|**Target Object**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_targetobject`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_ocliveworkitem, queueitem|

### <a name="BKMK_msdyn_targetobjectIdType"></a> msdyn_targetobjectIdType

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_targetobjectidtype`|
|RequiredLevel|None|
|Type|EntityName|

### <a name="BKMK_msdyn_unifiedroutingdiagnosticId"></a> msdyn_unifiedroutingdiagnosticId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Unified Routing Diagnostic**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_unifiedroutingdiagnosticid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_unifiedroutingrunid"></a> msdyn_unifiedroutingrunid

|Property|Value|
|---|---|
|Description|**Unique identifier for Unified routing run associated with Unified routing diagnostic.**|
|DisplayName|**unified routing run wrapper**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unifiedroutingrunid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_unifiedroutingrun|

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
|Description|**Status of the unifiedroutingdiagnostic**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_unifiedroutingdiagnostic_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the unifiedroutingdiagnostic**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_unifiedroutingdiagnostic_statuscode`|

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

- [business_unit_msdyn_unifiedroutingdiagnostic](#BKMK_business_unit_msdyn_unifiedroutingdiagnostic)
- [lk_msdyn_unifiedroutingdiagnostic_createdby](#BKMK_lk_msdyn_unifiedroutingdiagnostic_createdby)
- [lk_msdyn_unifiedroutingdiagnostic_createdonbehalfby](#BKMK_lk_msdyn_unifiedroutingdiagnostic_createdonbehalfby)
- [lk_msdyn_unifiedroutingdiagnostic_modifiedby](#BKMK_lk_msdyn_unifiedroutingdiagnostic_modifiedby)
- [lk_msdyn_unifiedroutingdiagnostic_modifiedonbehalfby](#BKMK_lk_msdyn_unifiedroutingdiagnostic_modifiedonbehalfby)
- [msdyn_msdyn_decisionruleset_msdyn_unifiedroutingdiagnostic_decisionrulesetid](#BKMK_msdyn_msdyn_decisionruleset_msdyn_unifiedroutingdiagnostic_decisionrulesetid)
- [msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_ocliveworkitemid](#BKMK_msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_ocliveworkitemid)
- [msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_targetobject](#BKMK_msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_targetobject)
- [msdyn_queueitem_msdyn_unifiedroutingdiagnostic_targetobject](#BKMK_msdyn_queueitem_msdyn_unifiedroutingdiagnostic_targetobject)
- [msdyn_unifiedroutingrun_msdyn_unifiedroutingdiagnostic](#BKMK_msdyn_unifiedroutingrun_msdyn_unifiedroutingdiagnostic)
- [owner_msdyn_unifiedroutingdiagnostic](#BKMK_owner_msdyn_unifiedroutingdiagnostic)
- [team_msdyn_unifiedroutingdiagnostic](#BKMK_team_msdyn_unifiedroutingdiagnostic)
- [user_msdyn_unifiedroutingdiagnostic](#BKMK_user_msdyn_unifiedroutingdiagnostic)

### <a name="BKMK_business_unit_msdyn_unifiedroutingdiagnostic"></a> business_unit_msdyn_unifiedroutingdiagnostic

One-To-Many Relationship: [businessunit business_unit_msdyn_unifiedroutingdiagnostic](businessunit.md#BKMK_business_unit_msdyn_unifiedroutingdiagnostic)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_unifiedroutingdiagnostic_createdby"></a> lk_msdyn_unifiedroutingdiagnostic_createdby

One-To-Many Relationship: [systemuser lk_msdyn_unifiedroutingdiagnostic_createdby](systemuser.md#BKMK_lk_msdyn_unifiedroutingdiagnostic_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_unifiedroutingdiagnostic_createdonbehalfby"></a> lk_msdyn_unifiedroutingdiagnostic_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_unifiedroutingdiagnostic_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_unifiedroutingdiagnostic_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_unifiedroutingdiagnostic_modifiedby"></a> lk_msdyn_unifiedroutingdiagnostic_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_unifiedroutingdiagnostic_modifiedby](systemuser.md#BKMK_lk_msdyn_unifiedroutingdiagnostic_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_unifiedroutingdiagnostic_modifiedonbehalfby"></a> lk_msdyn_unifiedroutingdiagnostic_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_unifiedroutingdiagnostic_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_unifiedroutingdiagnostic_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_decisionruleset_msdyn_unifiedroutingdiagnostic_decisionrulesetid"></a> msdyn_msdyn_decisionruleset_msdyn_unifiedroutingdiagnostic_decisionrulesetid

One-To-Many Relationship: [msdyn_decisionruleset msdyn_msdyn_decisionruleset_msdyn_unifiedroutingdiagnostic_decisionrulesetid](msdyn_decisionruleset.md#BKMK_msdyn_msdyn_decisionruleset_msdyn_unifiedroutingdiagnostic_decisionrulesetid)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_decisionruleset`|
|ReferencedAttribute|`msdyn_decisionrulesetid`|
|ReferencingAttribute|`msdyn_decisionrulesetid`|
|ReferencingEntityNavigationPropertyName|`msdyn_decisionrulesetid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_ocliveworkitemid"></a> msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_ocliveworkitemid

One-To-Many Relationship: [msdyn_ocliveworkitem msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_ocliveworkitemid](msdyn_ocliveworkitem.md#BKMK_msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_ocliveworkitemid)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_ocliveworkitem`|
|ReferencedAttribute|`activityid`|
|ReferencingAttribute|`msdyn_ocliveworkitemid`|
|ReferencingEntityNavigationPropertyName|`msdyn_ocliveworkitemid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_targetobject"></a> msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_targetobject

One-To-Many Relationship: [msdyn_ocliveworkitem msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_targetobject](msdyn_ocliveworkitem.md#BKMK_msdyn_msdyn_ocliveworkitem_msdyn_unifiedroutingdiagnostic_targetobject)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_ocliveworkitem`|
|ReferencedAttribute|`activityid`|
|ReferencingAttribute|`msdyn_targetobject`|
|ReferencingEntityNavigationPropertyName|`msdyn_targetobject_msdyn_ocliveworkitem`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_queueitem_msdyn_unifiedroutingdiagnostic_targetobject"></a> msdyn_queueitem_msdyn_unifiedroutingdiagnostic_targetobject

One-To-Many Relationship: [queueitem msdyn_queueitem_msdyn_unifiedroutingdiagnostic_targetobject](queueitem.md#BKMK_msdyn_queueitem_msdyn_unifiedroutingdiagnostic_targetobject)

|Property|Value|
|---|---|
|ReferencedEntity|`queueitem`|
|ReferencedAttribute|`queueitemid`|
|ReferencingAttribute|`msdyn_targetobject`|
|ReferencingEntityNavigationPropertyName|`msdyn_targetobject_queueitem`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_unifiedroutingrun_msdyn_unifiedroutingdiagnostic"></a> msdyn_unifiedroutingrun_msdyn_unifiedroutingdiagnostic

One-To-Many Relationship: [msdyn_unifiedroutingrun msdyn_unifiedroutingrun_msdyn_unifiedroutingdiagnostic](msdyn_unifiedroutingrun.md#BKMK_msdyn_unifiedroutingrun_msdyn_unifiedroutingdiagnostic)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_unifiedroutingrun`|
|ReferencedAttribute|`msdyn_unifiedroutingrunid`|
|ReferencingAttribute|`msdyn_unifiedroutingrunid`|
|ReferencingEntityNavigationPropertyName|`msdyn_unifiedroutingrunid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_unifiedroutingdiagnostic"></a> owner_msdyn_unifiedroutingdiagnostic

One-To-Many Relationship: [owner owner_msdyn_unifiedroutingdiagnostic](owner.md#BKMK_owner_msdyn_unifiedroutingdiagnostic)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_unifiedroutingdiagnostic"></a> team_msdyn_unifiedroutingdiagnostic

One-To-Many Relationship: [team team_msdyn_unifiedroutingdiagnostic](team.md#BKMK_team_msdyn_unifiedroutingdiagnostic)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_unifiedroutingdiagnostic"></a> user_msdyn_unifiedroutingdiagnostic

One-To-Many Relationship: [systemuser user_msdyn_unifiedroutingdiagnostic](systemuser.md#BKMK_user_msdyn_unifiedroutingdiagnostic)

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

- [msdyn_unifiedroutingdiagnostic_AsyncOperations](#BKMK_msdyn_unifiedroutingdiagnostic_AsyncOperations)
- [msdyn_unifiedroutingdiagnostic_BulkDeleteFailures](#BKMK_msdyn_unifiedroutingdiagnostic_BulkDeleteFailures)
- [msdyn_unifiedroutingdiagnostic_DuplicateBaseRecord](#BKMK_msdyn_unifiedroutingdiagnostic_DuplicateBaseRecord)
- [msdyn_unifiedroutingdiagnostic_DuplicateMatchingRecord](#BKMK_msdyn_unifiedroutingdiagnostic_DuplicateMatchingRecord)
- [msdyn_unifiedroutingdiagnostic_MailboxTrackingFolders](#BKMK_msdyn_unifiedroutingdiagnostic_MailboxTrackingFolders)
- [msdyn_unifiedroutingdiagnostic_PrincipalObjectAttributeAccesses](#BKMK_msdyn_unifiedroutingdiagnostic_PrincipalObjectAttributeAccesses)
- [msdyn_unifiedroutingdiagnostic_ProcessSession](#BKMK_msdyn_unifiedroutingdiagnostic_ProcessSession)
- [msdyn_unifiedroutingdiagnostic_SyncErrors](#BKMK_msdyn_unifiedroutingdiagnostic_SyncErrors)

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_AsyncOperations"></a> msdyn_unifiedroutingdiagnostic_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_unifiedroutingdiagnostic_AsyncOperations](asyncoperation.md#BKMK_msdyn_unifiedroutingdiagnostic_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_BulkDeleteFailures"></a> msdyn_unifiedroutingdiagnostic_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_unifiedroutingdiagnostic_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_unifiedroutingdiagnostic_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_DuplicateBaseRecord"></a> msdyn_unifiedroutingdiagnostic_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_unifiedroutingdiagnostic_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_unifiedroutingdiagnostic_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_DuplicateMatchingRecord"></a> msdyn_unifiedroutingdiagnostic_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_unifiedroutingdiagnostic_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_unifiedroutingdiagnostic_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_MailboxTrackingFolders"></a> msdyn_unifiedroutingdiagnostic_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_unifiedroutingdiagnostic_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_unifiedroutingdiagnostic_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_PrincipalObjectAttributeAccesses"></a> msdyn_unifiedroutingdiagnostic_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_unifiedroutingdiagnostic_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_unifiedroutingdiagnostic_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_ProcessSession"></a> msdyn_unifiedroutingdiagnostic_ProcessSession

Many-To-One Relationship: [processsession msdyn_unifiedroutingdiagnostic_ProcessSession](processsession.md#BKMK_msdyn_unifiedroutingdiagnostic_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_unifiedroutingdiagnostic_SyncErrors"></a> msdyn_unifiedroutingdiagnostic_SyncErrors

Many-To-One Relationship: [syncerror msdyn_unifiedroutingdiagnostic_SyncErrors](syncerror.md#BKMK_msdyn_unifiedroutingdiagnostic_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_unifiedroutingdiagnostic_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

