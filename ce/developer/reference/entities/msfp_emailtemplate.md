---
title: "Customer Voice survey email template (msfp_emailtemplate) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Customer Voice survey email template (msfp_emailtemplate) table/entity with Microsoft Dynamics 365."
ms.topic: generated-reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Customer Voice survey email template (msfp_emailtemplate) table/entity reference (Microsoft Dynamics 365)

Template for an email message that contains the survey invitation link.

## Messages

The following table lists the messages for the Customer Voice survey email template (msfp_emailtemplate) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msfp_emailtemplates(*msfp_emailtemplateid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Associate`<br />Event: True |[Associate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Associate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-associate-method-or-associaterequest)|
| `BulkRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Create`<br />Event: True |`POST` /msfp_emailtemplates<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msfp_emailtemplates(*msfp_emailtemplateid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Disassociate`<br />Event: True |[Disassociate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Disassociate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-disassociate-method-or-disassociaterequest)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `PurgeRetainedContent`<br />Event: True |<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msfp_emailtemplates(*msfp_emailtemplateid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msfp_emailtemplates<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `RollbackRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `SetState`<br />Event: True |`PATCH` /msfp_emailtemplates(*msfp_emailtemplateid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msfp_emailtemplates(*msfp_emailtemplateid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msfp_emailtemplates(*msfp_emailtemplateid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|
| `ValidateRetentionConfig`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Customer Voice survey email template (msfp_emailtemplate) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Customer Voice survey email template** |
| **DisplayCollectionName** | **Customer Voice survey email templates** |
| **SchemaName** | `msfp_emailtemplate` |
| **CollectionSchemaName** | `msfp_emailtemplates` |
| **EntitySetName** | `msfp_emailtemplates`|
| **LogicalName** | `msfp_emailtemplate` |
| **LogicalCollectionName** | `msfp_emailtemplates` |
| **PrimaryIdAttribute** | `msfp_emailtemplateid` |
| **PrimaryNameAttribute** |`msfp_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msfp_Candelete](#BKMK_msfp_Candelete)
- [msfp_Canedit](#BKMK_msfp_Canedit)
- [msfp_Canrename](#BKMK_msfp_Canrename)
- [msfp_emailtemplatebody](#BKMK_msfp_emailtemplatebody)
- [msfp_emailtemplateId](#BKMK_msfp_emailtemplateId)
- [msfp_emailtemplatesubject](#BKMK_msfp_emailtemplatesubject)
- [msfp_language](#BKMK_msfp_language)
- [msfp_name](#BKMK_msfp_name)
- [msfp_sourcesurveyidentifier](#BKMK_msfp_sourcesurveyidentifier)
- [msfp_survey](#BKMK_msfp_survey)
- [msfp_tags](#BKMK_msfp_tags)
- [msfp_templatetype](#BKMK_msfp_templatetype)
- [msfp_version](#BKMK_msfp_version)
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

### <a name="BKMK_msfp_Candelete"></a> msfp_Candelete

|Property|Value|
|---|---|
|Description|**Specifies if the email template can be deleted.**|
|DisplayName|**Is deletable**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_candelete`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msfp_emailtemplate_msfp_candelete`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msfp_Canedit"></a> msfp_Canedit

|Property|Value|
|---|---|
|Description|**Specifies if the email template can be edited.**|
|DisplayName|**Is editable**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_canedit`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msfp_emailtemplate_msfp_canedit`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msfp_Canrename"></a> msfp_Canrename

|Property|Value|
|---|---|
|Description|**Specifies if the email template can be renamed.**|
|DisplayName|**Is renamable**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_canrename`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msfp_emailtemplate_msfp_canrename`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msfp_emailtemplatebody"></a> msfp_emailtemplatebody

|Property|Value|
|---|---|
|Description|**Stores body of the email template.**|
|DisplayName|**Email template body**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_emailtemplatebody`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1000000|

### <a name="BKMK_msfp_emailtemplateId"></a> msfp_emailtemplateId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Survey email template**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msfp_emailtemplateid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msfp_emailtemplatesubject"></a> msfp_emailtemplatesubject

|Property|Value|
|---|---|
|Description|**Stores subject of the email template.**|
|DisplayName|**Email template subject**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_emailtemplatesubject`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1000|

### <a name="BKMK_msfp_language"></a> msfp_language

|Property|Value|
|---|---|
|Description|**Language of the email message template**|
|DisplayName|**Language**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_language`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|400|

### <a name="BKMK_msfp_name"></a> msfp_name

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_name`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|250|

### <a name="BKMK_msfp_sourcesurveyidentifier"></a> msfp_sourcesurveyidentifier

|Property|Value|
|---|---|
|Description|**Unique identifier for the survey in the source application.**|
|DisplayName|**Source survey identifier**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_sourcesurveyidentifier`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msfp_survey"></a> msfp_survey

|Property|Value|
|---|---|
|Description|**Unique identifier for Customer Voice survey associated with Customer Voice survey email template.**|
|DisplayName|**survey email template**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_survey`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msfp_survey|

### <a name="BKMK_msfp_tags"></a> msfp_tags

|Property|Value|
|---|---|
|Description|**Stores tags added to the email template.**|
|DisplayName|**Tags**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_tags`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1000|

### <a name="BKMK_msfp_templatetype"></a> msfp_templatetype

|Property|Value|
|---|---|
|Description|**Determines the type of template.**|
|DisplayName|**Template type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_templatetype`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|647390000|
|GlobalChoiceName|`msfp_emailtemplate_msfp_templatetype`|

#### msfp_templatetype Choices/Options

|Value|Label|
|---|---|
|647390000|**User**|
|647390001|**Survey**|

### <a name="BKMK_msfp_version"></a> msfp_version

|Property|Value|
|---|---|
|Description|**Version of the email message template**|
|DisplayName|**Version**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msfp_version`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|400|

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
|Description|**Status of the Survey email template**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msfp_emailtemplate_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Survey email template**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msfp_emailtemplate_statuscode`|

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

- [business_unit_msfp_emailtemplate](#BKMK_business_unit_msfp_emailtemplate)
- [lk_msfp_emailtemplate_createdby](#BKMK_lk_msfp_emailtemplate_createdby)
- [lk_msfp_emailtemplate_createdonbehalfby](#BKMK_lk_msfp_emailtemplate_createdonbehalfby)
- [lk_msfp_emailtemplate_modifiedby](#BKMK_lk_msfp_emailtemplate_modifiedby)
- [lk_msfp_emailtemplate_modifiedonbehalfby](#BKMK_lk_msfp_emailtemplate_modifiedonbehalfby)
- [msfp_msfp_survey_msfp_emailtemplate_surveyid](#BKMK_msfp_msfp_survey_msfp_emailtemplate_surveyid)
- [owner_msfp_emailtemplate](#BKMK_owner_msfp_emailtemplate)
- [team_msfp_emailtemplate](#BKMK_team_msfp_emailtemplate)
- [user_msfp_emailtemplate](#BKMK_user_msfp_emailtemplate)

### <a name="BKMK_business_unit_msfp_emailtemplate"></a> business_unit_msfp_emailtemplate

One-To-Many Relationship: [businessunit business_unit_msfp_emailtemplate](businessunit.md#BKMK_business_unit_msfp_emailtemplate)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msfp_emailtemplate_createdby"></a> lk_msfp_emailtemplate_createdby

One-To-Many Relationship: [systemuser lk_msfp_emailtemplate_createdby](systemuser.md#BKMK_lk_msfp_emailtemplate_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msfp_emailtemplate_createdonbehalfby"></a> lk_msfp_emailtemplate_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msfp_emailtemplate_createdonbehalfby](systemuser.md#BKMK_lk_msfp_emailtemplate_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msfp_emailtemplate_modifiedby"></a> lk_msfp_emailtemplate_modifiedby

One-To-Many Relationship: [systemuser lk_msfp_emailtemplate_modifiedby](systemuser.md#BKMK_lk_msfp_emailtemplate_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msfp_emailtemplate_modifiedonbehalfby"></a> lk_msfp_emailtemplate_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msfp_emailtemplate_modifiedonbehalfby](systemuser.md#BKMK_lk_msfp_emailtemplate_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msfp_msfp_survey_msfp_emailtemplate_surveyid"></a> msfp_msfp_survey_msfp_emailtemplate_surveyid

One-To-Many Relationship: [msfp_survey msfp_msfp_survey_msfp_emailtemplate_surveyid](msfp_survey.md#BKMK_msfp_msfp_survey_msfp_emailtemplate_surveyid)

|Property|Value|
|---|---|
|ReferencedEntity|`msfp_survey`|
|ReferencedAttribute|`msfp_surveyid`|
|ReferencingAttribute|`msfp_survey`|
|ReferencingEntityNavigationPropertyName|`msfp_survey`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_owner_msfp_emailtemplate"></a> owner_msfp_emailtemplate

One-To-Many Relationship: [owner owner_msfp_emailtemplate](owner.md#BKMK_owner_msfp_emailtemplate)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msfp_emailtemplate"></a> team_msfp_emailtemplate

One-To-Many Relationship: [team team_msfp_emailtemplate](team.md#BKMK_team_msfp_emailtemplate)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msfp_emailtemplate"></a> user_msfp_emailtemplate

One-To-Many Relationship: [systemuser user_msfp_emailtemplate](systemuser.md#BKMK_user_msfp_emailtemplate)

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

- [msfp_emailtemplate_AsyncOperations](#BKMK_msfp_emailtemplate_AsyncOperations)
- [msfp_emailtemplate_BulkDeleteFailures](#BKMK_msfp_emailtemplate_BulkDeleteFailures)
- [msfp_emailtemplate_MailboxTrackingFolders](#BKMK_msfp_emailtemplate_MailboxTrackingFolders)
- [msfp_emailtemplate_PrincipalObjectAttributeAccesses](#BKMK_msfp_emailtemplate_PrincipalObjectAttributeAccesses)
- [msfp_emailtemplate_ProcessSession](#BKMK_msfp_emailtemplate_ProcessSession)
- [msfp_emailtemplate_SyncErrors](#BKMK_msfp_emailtemplate_SyncErrors)
- [msfp_msfp_emailtemplate_msfp_localizedemailtem](#BKMK_msfp_msfp_emailtemplate_msfp_localizedemailtem)
- [msfp_msfp_emailtemplate_msfp_surveyreminder_emailtemplate](#BKMK_msfp_msfp_emailtemplate_msfp_surveyreminder_emailtemplate)

### <a name="BKMK_msfp_emailtemplate_AsyncOperations"></a> msfp_emailtemplate_AsyncOperations

Many-To-One Relationship: [asyncoperation msfp_emailtemplate_AsyncOperations](asyncoperation.md#BKMK_msfp_emailtemplate_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msfp_emailtemplate_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msfp_emailtemplate_BulkDeleteFailures"></a> msfp_emailtemplate_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msfp_emailtemplate_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msfp_emailtemplate_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msfp_emailtemplate_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msfp_emailtemplate_MailboxTrackingFolders"></a> msfp_emailtemplate_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msfp_emailtemplate_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msfp_emailtemplate_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msfp_emailtemplate_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msfp_emailtemplate_PrincipalObjectAttributeAccesses"></a> msfp_emailtemplate_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msfp_emailtemplate_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msfp_emailtemplate_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msfp_emailtemplate_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msfp_emailtemplate_ProcessSession"></a> msfp_emailtemplate_ProcessSession

Many-To-One Relationship: [processsession msfp_emailtemplate_ProcessSession](processsession.md#BKMK_msfp_emailtemplate_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msfp_emailtemplate_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msfp_emailtemplate_SyncErrors"></a> msfp_emailtemplate_SyncErrors

Many-To-One Relationship: [syncerror msfp_emailtemplate_SyncErrors](syncerror.md#BKMK_msfp_emailtemplate_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msfp_emailtemplate_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msfp_msfp_emailtemplate_msfp_localizedemailtem"></a> msfp_msfp_emailtemplate_msfp_localizedemailtem

Many-To-One Relationship: [msfp_localizedemailtemplate msfp_msfp_emailtemplate_msfp_localizedemailtem](msfp_localizedemailtemplate.md#BKMK_msfp_msfp_emailtemplate_msfp_localizedemailtem)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_localizedemailtemplate`|
|ReferencingAttribute|`msfp_emailtemplateid`|
|ReferencedEntityNavigationPropertyName|`msfp_msfp_emailtemplate_msfp_localizedemailtem`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msfp_msfp_emailtemplate_msfp_surveyreminder_emailtemplate"></a> msfp_msfp_emailtemplate_msfp_surveyreminder_emailtemplate

Many-To-One Relationship: [msfp_surveyreminder msfp_msfp_emailtemplate_msfp_surveyreminder_emailtemplate](msfp_surveyreminder.md#BKMK_msfp_msfp_emailtemplate_msfp_surveyreminder_emailtemplate)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyreminder`|
|ReferencingAttribute|`msfp_emailtemplate`|
|ReferencedEntityNavigationPropertyName|`msfp_msfp_emailtemplate_msfp_surveyreminder_emailtemplate`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

