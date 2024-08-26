---
title: "Agreement Booking Incident (msdyn_agreementbookingincident) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Agreement Booking Incident (msdyn_agreementbookingincident) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Agreement Booking Incident (msdyn_agreementbookingincident) table/entity reference

Specify the booking incident for the agreement.

## Messages

The following table lists the messages for the Agreement Booking Incident (msdyn_agreementbookingincident) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_agreementbookingincidents(*msdyn_agreementbookingincidentid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_agreementbookingincidents<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_agreementbookingincidents(*msdyn_agreementbookingincidentid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `msdyn_FieldServiceAgreementBookingIncidentCopyAction`<br />Event: False |**msdyn_FieldServiceAgreementBookingIncidentCopyAction action** |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `msdyn_FieldServiceAgreementBookingIncidentStatusAction`<br />Event: False |**msdyn_FieldServiceAgreementBookingIncidentStatusAction action** |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_agreementbookingincidents(*msdyn_agreementbookingincidentid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_agreementbookingincidents<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_agreementbookingincidents(*msdyn_agreementbookingincidentid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_agreementbookingincidents(*msdyn_agreementbookingincidentid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_agreementbookingincidents(*msdyn_agreementbookingincidentid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Agreement Booking Incident (msdyn_agreementbookingincident) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Agreement Booking Incident (msdyn_agreementbookingincident) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Agreement Booking Incident** |
| **DisplayCollectionName** | **Agreement Booking Incidents** |
| **SchemaName** | `msdyn_agreementbookingincident` |
| **CollectionSchemaName** | `msdyn_agreementbookingincidents` |
| **EntitySetName** | `msdyn_agreementbookingincidents`|
| **LogicalName** | `msdyn_agreementbookingincident` |
| **LogicalCollectionName** | `msdyn_agreementbookingincidents` |
| **PrimaryIdAttribute** | `msdyn_agreementbookingincidentid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_Agreement](#BKMK_msdyn_Agreement)
- [msdyn_agreementbookingincidentId](#BKMK_msdyn_agreementbookingincidentId)
- [msdyn_AgreementBookingSetup](#BKMK_msdyn_AgreementBookingSetup)
- [msdyn_CustomerAsset](#BKMK_msdyn_CustomerAsset)
- [msdyn_Description](#BKMK_msdyn_Description)
- [msdyn_EstimatedDuration](#BKMK_msdyn_EstimatedDuration)
- [msdyn_FunctionalLocation](#BKMK_msdyn_FunctionalLocation)
- [msdyn_IncidentItemsCopied](#BKMK_msdyn_IncidentItemsCopied)
- [msdyn_IncidentType](#BKMK_msdyn_IncidentType)
- [msdyn_InternalFlags](#BKMK_msdyn_InternalFlags)
- [msdyn_name](#BKMK_msdyn_name)
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
|Description|**Shows the sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_Agreement"></a> msdyn_Agreement

|Property|Value|
|---|---|
|Description|**Shows the agreement associated with the agreement booking incident.**|
|DisplayName|**Agreement**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_agreement`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_agreement|

### <a name="BKMK_msdyn_agreementbookingincidentId"></a> msdyn_agreementbookingincidentId

|Property|Value|
|---|---|
|Description|**Shows the entity instances.**|
|DisplayName|**Agreement Booking Incident**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_agreementbookingincidentid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_AgreementBookingSetup"></a> msdyn_AgreementBookingSetup

|Property|Value|
|---|---|
|Description|**Shows the agreement booking setup associated with the agreement booking incident.**|
|DisplayName|**Agreement Booking Setup**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_agreementbookingsetup`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_agreementbookingsetup|

### <a name="BKMK_msdyn_CustomerAsset"></a> msdyn_CustomerAsset

|Property|Value|
|---|---|
|Description|**Customer Asset related to this incident reported**|
|DisplayName|**Customer Asset**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_customerasset`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_customerasset|

### <a name="BKMK_msdyn_Description"></a> msdyn_Description

|Property|Value|
|---|---|
|Description|**Incident description**|
|DisplayName|**Description**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_description`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|8000|

### <a name="BKMK_msdyn_EstimatedDuration"></a> msdyn_EstimatedDuration

|Property|Value|
|---|---|
|Description|**Shows the time estimated to resolve this incident.**|
|DisplayName|**Estimated Duration**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_estimatedduration`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_FunctionalLocation"></a> msdyn_FunctionalLocation

|Property|Value|
|---|---|
|Description|**Agreement Booking Incident's functional location.**|
|DisplayName|**Functional Location**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_functionallocation`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_functionallocation|

### <a name="BKMK_msdyn_IncidentItemsCopied"></a> msdyn_IncidentItemsCopied

|Property|Value|
|---|---|
|Description||
|DisplayName|**Incident Items Copied**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_incidentitemscopied`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_agreementbookingincident_msdyn_incidentitemscopied`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_IncidentType"></a> msdyn_IncidentType

|Property|Value|
|---|---|
|Description|**Shows the incident type associated with the agreement booking incident.**|
|DisplayName|**Incident Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_incidenttype`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_incidenttype|

### <a name="BKMK_msdyn_InternalFlags"></a> msdyn_InternalFlags

|Property|Value|
|---|---|
|Description||
|DisplayName|**Internal Flags**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_internalflags`|
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
|Description||
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

### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|---|---|
|Description|**Shows the date and time that the record was migrated.**|
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
|Description|**Shows the status of the agreement booking incident.**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_agreementbookingincident_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Select the Agreement Booking Incident's status.**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_agreementbookingincident_statuscode`|

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
|Description|**Shows the time zone code that was in use when the record was created.**|
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
|Description|**Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.**|
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
|Description|**Shows who created the record on behalf of another user.**|
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
|Description|**Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.**|
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
|Description|**Shows who last updated the record on behalf of another user.**|
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

- [business_unit_msdyn_agreementbookingincident](#BKMK_business_unit_msdyn_agreementbookingincident)
- [lk_msdyn_agreementbookingincident_createdby](#BKMK_lk_msdyn_agreementbookingincident_createdby)
- [lk_msdyn_agreementbookingincident_createdonbehalfby](#BKMK_lk_msdyn_agreementbookingincident_createdonbehalfby)
- [lk_msdyn_agreementbookingincident_modifiedby](#BKMK_lk_msdyn_agreementbookingincident_modifiedby)
- [lk_msdyn_agreementbookingincident_modifiedonbehalfby](#BKMK_lk_msdyn_agreementbookingincident_modifiedonbehalfby)
- [msdyn_msdyn_agreement_msdyn_agreementbookingincident_Agreement](#BKMK_msdyn_msdyn_agreement_msdyn_agreementbookingincident_Agreement)
- [msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingincident_AgreementBookingSetup](#BKMK_msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingincident_AgreementBookingSetup)
- [msdyn_msdyn_customerasset_msdyn_agreementbookingincident_CustomerAsset](#BKMK_msdyn_msdyn_customerasset_msdyn_agreementbookingincident_CustomerAsset)
- [msdyn_msdyn_functionallocation_msdyn_agreementbookingincident_FunctionalLocation](#BKMK_msdyn_msdyn_functionallocation_msdyn_agreementbookingincident_FunctionalLocation)
- [msdyn_msdyn_incidenttype_msdyn_agreementbookingincident_IncidentType](#BKMK_msdyn_msdyn_incidenttype_msdyn_agreementbookingincident_IncidentType)
- [owner_msdyn_agreementbookingincident](#BKMK_owner_msdyn_agreementbookingincident)
- [team_msdyn_agreementbookingincident](#BKMK_team_msdyn_agreementbookingincident)
- [user_msdyn_agreementbookingincident](#BKMK_user_msdyn_agreementbookingincident)

### <a name="BKMK_business_unit_msdyn_agreementbookingincident"></a> business_unit_msdyn_agreementbookingincident

One-To-Many Relationship: [businessunit business_unit_msdyn_agreementbookingincident](businessunit.md#BKMK_business_unit_msdyn_agreementbookingincident)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingincident_createdby"></a> lk_msdyn_agreementbookingincident_createdby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingincident_createdby](systemuser.md#BKMK_lk_msdyn_agreementbookingincident_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingincident_createdonbehalfby"></a> lk_msdyn_agreementbookingincident_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingincident_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_agreementbookingincident_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingincident_modifiedby"></a> lk_msdyn_agreementbookingincident_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingincident_modifiedby](systemuser.md#BKMK_lk_msdyn_agreementbookingincident_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingincident_modifiedonbehalfby"></a> lk_msdyn_agreementbookingincident_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingincident_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_agreementbookingincident_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_agreement_msdyn_agreementbookingincident_Agreement"></a> msdyn_msdyn_agreement_msdyn_agreementbookingincident_Agreement

One-To-Many Relationship: [msdyn_agreement msdyn_msdyn_agreement_msdyn_agreementbookingincident_Agreement](msdyn_agreement.md#BKMK_msdyn_msdyn_agreement_msdyn_agreementbookingincident_Agreement)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_agreement`|
|ReferencedAttribute|`msdyn_agreementid`|
|ReferencingAttribute|`msdyn_agreement`|
|ReferencingEntityNavigationPropertyName|`msdyn_agreement`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingincident_AgreementBookingSetup"></a> msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingincident_AgreementBookingSetup

One-To-Many Relationship: [msdyn_agreementbookingsetup msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingincident_AgreementBookingSetup](msdyn_agreementbookingsetup.md#BKMK_msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingincident_AgreementBookingSetup)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_agreementbookingsetup`|
|ReferencedAttribute|`msdyn_agreementbookingsetupid`|
|ReferencingAttribute|`msdyn_agreementbookingsetup`|
|ReferencingEntityNavigationPropertyName|`msdyn_agreementbookingsetup`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_msdyn_customerasset_msdyn_agreementbookingincident_CustomerAsset"></a> msdyn_msdyn_customerasset_msdyn_agreementbookingincident_CustomerAsset

One-To-Many Relationship: [msdyn_customerasset msdyn_msdyn_customerasset_msdyn_agreementbookingincident_CustomerAsset](msdyn_customerasset.md#BKMK_msdyn_msdyn_customerasset_msdyn_agreementbookingincident_CustomerAsset)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_customerasset`|
|ReferencedAttribute|`msdyn_customerassetid`|
|ReferencingAttribute|`msdyn_customerasset`|
|ReferencingEntityNavigationPropertyName|`msdyn_customerasset`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_functionallocation_msdyn_agreementbookingincident_FunctionalLocation"></a> msdyn_msdyn_functionallocation_msdyn_agreementbookingincident_FunctionalLocation

One-To-Many Relationship: [msdyn_functionallocation msdyn_msdyn_functionallocation_msdyn_agreementbookingincident_FunctionalLocation](msdyn_functionallocation.md#BKMK_msdyn_msdyn_functionallocation_msdyn_agreementbookingincident_FunctionalLocation)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_functionallocation`|
|ReferencedAttribute|`msdyn_functionallocationid`|
|ReferencingAttribute|`msdyn_functionallocation`|
|ReferencingEntityNavigationPropertyName|`msdyn_FunctionalLocation`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_incidenttype_msdyn_agreementbookingincident_IncidentType"></a> msdyn_msdyn_incidenttype_msdyn_agreementbookingincident_IncidentType

One-To-Many Relationship: [msdyn_incidenttype msdyn_msdyn_incidenttype_msdyn_agreementbookingincident_IncidentType](msdyn_incidenttype.md#BKMK_msdyn_msdyn_incidenttype_msdyn_agreementbookingincident_IncidentType)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_incidenttype`|
|ReferencedAttribute|`msdyn_incidenttypeid`|
|ReferencingAttribute|`msdyn_incidenttype`|
|ReferencingEntityNavigationPropertyName|`msdyn_incidenttype`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_agreementbookingincident"></a> owner_msdyn_agreementbookingincident

One-To-Many Relationship: [owner owner_msdyn_agreementbookingincident](owner.md#BKMK_owner_msdyn_agreementbookingincident)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_agreementbookingincident"></a> team_msdyn_agreementbookingincident

One-To-Many Relationship: [team team_msdyn_agreementbookingincident](team.md#BKMK_team_msdyn_agreementbookingincident)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_agreementbookingincident"></a> user_msdyn_agreementbookingincident

One-To-Many Relationship: [systemuser user_msdyn_agreementbookingincident](systemuser.md#BKMK_user_msdyn_agreementbookingincident)

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

- [msdyn_agreementbookingincident_ActivityPointers](#BKMK_msdyn_agreementbookingincident_ActivityPointers)
- [msdyn_agreementbookingincident_adx_inviteredemptions](#BKMK_msdyn_agreementbookingincident_adx_inviteredemptions)
- [msdyn_agreementbookingincident_adx_portalcomments](#BKMK_msdyn_agreementbookingincident_adx_portalcomments)
- [msdyn_agreementbookingincident_Annotations](#BKMK_msdyn_agreementbookingincident_Annotations)
- [msdyn_agreementbookingincident_Appointments](#BKMK_msdyn_agreementbookingincident_Appointments)
- [msdyn_agreementbookingincident_AsyncOperations](#BKMK_msdyn_agreementbookingincident_AsyncOperations)
- [msdyn_agreementbookingincident_BulkDeleteFailures](#BKMK_msdyn_agreementbookingincident_BulkDeleteFailures)
- [msdyn_agreementbookingincident_chats](#BKMK_msdyn_agreementbookingincident_chats)
- [msdyn_agreementbookingincident_connections1](#BKMK_msdyn_agreementbookingincident_connections1)
- [msdyn_agreementbookingincident_connections2](#BKMK_msdyn_agreementbookingincident_connections2)
- [msdyn_agreementbookingincident_DuplicateBaseRecord](#BKMK_msdyn_agreementbookingincident_DuplicateBaseRecord)
- [msdyn_agreementbookingincident_DuplicateMatchingRecord](#BKMK_msdyn_agreementbookingincident_DuplicateMatchingRecord)
- [msdyn_agreementbookingincident_Emails](#BKMK_msdyn_agreementbookingincident_Emails)
- [msdyn_agreementbookingincident_Faxes](#BKMK_msdyn_agreementbookingincident_Faxes)
- [msdyn_agreementbookingincident_Letters](#BKMK_msdyn_agreementbookingincident_Letters)
- [msdyn_agreementbookingincident_MailboxTrackingFolders](#BKMK_msdyn_agreementbookingincident_MailboxTrackingFolders)
- [msdyn_agreementbookingincident_msdyn_bookingalerts](#BKMK_msdyn_agreementbookingincident_msdyn_bookingalerts)
- [msdyn_agreementbookingincident_msdyn_copilottranscripts](#BKMK_msdyn_agreementbookingincident_msdyn_copilottranscripts)
- [msdyn_agreementbookingincident_msdyn_ocliveworkitems](#BKMK_msdyn_agreementbookingincident_msdyn_ocliveworkitems)
- [msdyn_agreementbookingincident_msdyn_ocsessions](#BKMK_msdyn_agreementbookingincident_msdyn_ocsessions)
- [msdyn_agreementbookingincident_msfp_alerts](#BKMK_msdyn_agreementbookingincident_msfp_alerts)
- [msdyn_agreementbookingincident_msfp_surveyinvites](#BKMK_msdyn_agreementbookingincident_msfp_surveyinvites)
- [msdyn_agreementbookingincident_msfp_surveyresponses](#BKMK_msdyn_agreementbookingincident_msfp_surveyresponses)
- [msdyn_agreementbookingincident_PhoneCalls](#BKMK_msdyn_agreementbookingincident_PhoneCalls)
- [msdyn_agreementbookingincident_PrincipalObjectAttributeAccesses](#BKMK_msdyn_agreementbookingincident_PrincipalObjectAttributeAccesses)
- [msdyn_agreementbookingincident_ProcessSession](#BKMK_msdyn_agreementbookingincident_ProcessSession)
- [msdyn_agreementbookingincident_RecurringAppointmentMasters](#BKMK_msdyn_agreementbookingincident_RecurringAppointmentMasters)
- [msdyn_agreementbookingincident_ServiceAppointments](#BKMK_msdyn_agreementbookingincident_ServiceAppointments)
- [msdyn_agreementbookingincident_SocialActivities](#BKMK_msdyn_agreementbookingincident_SocialActivities)
- [msdyn_agreementbookingincident_SyncErrors](#BKMK_msdyn_agreementbookingincident_SyncErrors)
- [msdyn_agreementbookingincident_Tasks](#BKMK_msdyn_agreementbookingincident_Tasks)
- [msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingproduct_AgreementBookingIncident](#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingproduct_AgreementBookingIncident)
- [msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservice_AgreementBookingIncident](#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservice_AgreementBookingIncident)
- [msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident](#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident)
- [msdyn_msdyn_agreementbookingincident_msdyn_workorderincident_AgreementBookingIncident](#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_workorderincident_AgreementBookingIncident)

### <a name="BKMK_msdyn_agreementbookingincident_ActivityPointers"></a> msdyn_agreementbookingincident_ActivityPointers

Many-To-One Relationship: [activitypointer msdyn_agreementbookingincident_ActivityPointers](activitypointer.md#BKMK_msdyn_agreementbookingincident_ActivityPointers)

|Property|Value|
|---|---|
|ReferencingEntity|`activitypointer`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_ActivityPointers`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_adx_inviteredemptions"></a> msdyn_agreementbookingincident_adx_inviteredemptions

Many-To-One Relationship: [adx_inviteredemption msdyn_agreementbookingincident_adx_inviteredemptions](adx_inviteredemption.md#BKMK_msdyn_agreementbookingincident_adx_inviteredemptions)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_inviteredemption`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_adx_inviteredemptions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_adx_portalcomments"></a> msdyn_agreementbookingincident_adx_portalcomments

Many-To-One Relationship: [adx_portalcomment msdyn_agreementbookingincident_adx_portalcomments](adx_portalcomment.md#BKMK_msdyn_agreementbookingincident_adx_portalcomments)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_portalcomment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_adx_portalcomments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_Annotations"></a> msdyn_agreementbookingincident_Annotations

Many-To-One Relationship: [annotation msdyn_agreementbookingincident_Annotations](annotation.md#BKMK_msdyn_agreementbookingincident_Annotations)

|Property|Value|
|---|---|
|ReferencingEntity|`annotation`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_Annotations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_Appointments"></a> msdyn_agreementbookingincident_Appointments

Many-To-One Relationship: [appointment msdyn_agreementbookingincident_Appointments](appointment.md#BKMK_msdyn_agreementbookingincident_Appointments)

|Property|Value|
|---|---|
|ReferencingEntity|`appointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_Appointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_AsyncOperations"></a> msdyn_agreementbookingincident_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_agreementbookingincident_AsyncOperations](asyncoperation.md#BKMK_msdyn_agreementbookingincident_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_BulkDeleteFailures"></a> msdyn_agreementbookingincident_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_agreementbookingincident_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_agreementbookingincident_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_chats"></a> msdyn_agreementbookingincident_chats

Many-To-One Relationship: [chat msdyn_agreementbookingincident_chats](chat.md#BKMK_msdyn_agreementbookingincident_chats)

|Property|Value|
|---|---|
|ReferencingEntity|`chat`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_chats`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_connections1"></a> msdyn_agreementbookingincident_connections1

Many-To-One Relationship: [connection msdyn_agreementbookingincident_connections1](connection.md#BKMK_msdyn_agreementbookingincident_connections1)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record1id`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_connections1`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 100<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_connections2"></a> msdyn_agreementbookingincident_connections2

Many-To-One Relationship: [connection msdyn_agreementbookingincident_connections2](connection.md#BKMK_msdyn_agreementbookingincident_connections2)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record2id`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_connections2`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_DuplicateBaseRecord"></a> msdyn_agreementbookingincident_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_agreementbookingincident_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_agreementbookingincident_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_DuplicateMatchingRecord"></a> msdyn_agreementbookingincident_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_agreementbookingincident_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_agreementbookingincident_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_Emails"></a> msdyn_agreementbookingincident_Emails

Many-To-One Relationship: [email msdyn_agreementbookingincident_Emails](email.md#BKMK_msdyn_agreementbookingincident_Emails)

|Property|Value|
|---|---|
|ReferencingEntity|`email`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_Emails`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_Faxes"></a> msdyn_agreementbookingincident_Faxes

Many-To-One Relationship: [fax msdyn_agreementbookingincident_Faxes](fax.md#BKMK_msdyn_agreementbookingincident_Faxes)

|Property|Value|
|---|---|
|ReferencingEntity|`fax`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_Faxes`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_Letters"></a> msdyn_agreementbookingincident_Letters

Many-To-One Relationship: [letter msdyn_agreementbookingincident_Letters](letter.md#BKMK_msdyn_agreementbookingincident_Letters)

|Property|Value|
|---|---|
|ReferencingEntity|`letter`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_Letters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_MailboxTrackingFolders"></a> msdyn_agreementbookingincident_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_agreementbookingincident_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_agreementbookingincident_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_msdyn_bookingalerts"></a> msdyn_agreementbookingincident_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert msdyn_agreementbookingincident_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_msdyn_agreementbookingincident_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_msdyn_copilottranscripts"></a> msdyn_agreementbookingincident_msdyn_copilottranscripts

Many-To-One Relationship: [msdyn_copilottranscript msdyn_agreementbookingincident_msdyn_copilottranscripts](msdyn_copilottranscript.md#BKMK_msdyn_agreementbookingincident_msdyn_copilottranscripts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_copilottranscript`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_msdyn_copilottranscripts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_msdyn_ocliveworkitems"></a> msdyn_agreementbookingincident_msdyn_ocliveworkitems

Many-To-One Relationship: [msdyn_ocliveworkitem msdyn_agreementbookingincident_msdyn_ocliveworkitems](msdyn_ocliveworkitem.md#BKMK_msdyn_agreementbookingincident_msdyn_ocliveworkitems)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocliveworkitem`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_msdyn_ocliveworkitems`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_msdyn_ocsessions"></a> msdyn_agreementbookingincident_msdyn_ocsessions

Many-To-One Relationship: [msdyn_ocsession msdyn_agreementbookingincident_msdyn_ocsessions](msdyn_ocsession.md#BKMK_msdyn_agreementbookingincident_msdyn_ocsessions)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_msdyn_ocsessions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_msfp_alerts"></a> msdyn_agreementbookingincident_msfp_alerts

Many-To-One Relationship: [msfp_alert msdyn_agreementbookingincident_msfp_alerts](msfp_alert.md#BKMK_msdyn_agreementbookingincident_msfp_alerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_alert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_msfp_alerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_msfp_surveyinvites"></a> msdyn_agreementbookingincident_msfp_surveyinvites

Many-To-One Relationship: [msfp_surveyinvite msdyn_agreementbookingincident_msfp_surveyinvites](msfp_surveyinvite.md#BKMK_msdyn_agreementbookingincident_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyinvite`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_msfp_surveyinvites`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_msfp_surveyresponses"></a> msdyn_agreementbookingincident_msfp_surveyresponses

Many-To-One Relationship: [msfp_surveyresponse msdyn_agreementbookingincident_msfp_surveyresponses](msfp_surveyresponse.md#BKMK_msdyn_agreementbookingincident_msfp_surveyresponses)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyresponse`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_msfp_surveyresponses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_PhoneCalls"></a> msdyn_agreementbookingincident_PhoneCalls

Many-To-One Relationship: [phonecall msdyn_agreementbookingincident_PhoneCalls](phonecall.md#BKMK_msdyn_agreementbookingincident_PhoneCalls)

|Property|Value|
|---|---|
|ReferencingEntity|`phonecall`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_PhoneCalls`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_PrincipalObjectAttributeAccesses"></a> msdyn_agreementbookingincident_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_agreementbookingincident_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_agreementbookingincident_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_ProcessSession"></a> msdyn_agreementbookingincident_ProcessSession

Many-To-One Relationship: [processsession msdyn_agreementbookingincident_ProcessSession](processsession.md#BKMK_msdyn_agreementbookingincident_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_RecurringAppointmentMasters"></a> msdyn_agreementbookingincident_RecurringAppointmentMasters

Many-To-One Relationship: [recurringappointmentmaster msdyn_agreementbookingincident_RecurringAppointmentMasters](recurringappointmentmaster.md#BKMK_msdyn_agreementbookingincident_RecurringAppointmentMasters)

|Property|Value|
|---|---|
|ReferencingEntity|`recurringappointmentmaster`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_RecurringAppointmentMasters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_ServiceAppointments"></a> msdyn_agreementbookingincident_ServiceAppointments

Many-To-One Relationship: [serviceappointment msdyn_agreementbookingincident_ServiceAppointments](serviceappointment.md#BKMK_msdyn_agreementbookingincident_ServiceAppointments)

|Property|Value|
|---|---|
|ReferencingEntity|`serviceappointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_ServiceAppointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_SocialActivities"></a> msdyn_agreementbookingincident_SocialActivities

Many-To-One Relationship: [socialactivity msdyn_agreementbookingincident_SocialActivities](socialactivity.md#BKMK_msdyn_agreementbookingincident_SocialActivities)

|Property|Value|
|---|---|
|ReferencingEntity|`socialactivity`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_SocialActivities`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_SyncErrors"></a> msdyn_agreementbookingincident_SyncErrors

Many-To-One Relationship: [syncerror msdyn_agreementbookingincident_SyncErrors](syncerror.md#BKMK_msdyn_agreementbookingincident_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingincident_Tasks"></a> msdyn_agreementbookingincident_Tasks

Many-To-One Relationship: [task msdyn_agreementbookingincident_Tasks](task.md#BKMK_msdyn_agreementbookingincident_Tasks)

|Property|Value|
|---|---|
|ReferencingEntity|`task`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingincident_Tasks`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingproduct_AgreementBookingIncident"></a> msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingproduct_AgreementBookingIncident

Many-To-One Relationship: [msdyn_agreementbookingproduct msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingproduct_AgreementBookingIncident](msdyn_agreementbookingproduct.md#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingproduct_AgreementBookingIncident)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_agreementbookingproduct`|
|ReferencingAttribute|`msdyn_agreementbookingincident`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingproduct_AgreementBookingIncident`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: Agreement Booking Incident<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservice_AgreementBookingIncident"></a> msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservice_AgreementBookingIncident

Many-To-One Relationship: [msdyn_agreementbookingservice msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservice_AgreementBookingIncident](msdyn_agreementbookingservice.md#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservice_AgreementBookingIncident)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_agreementbookingservice`|
|ReferencingAttribute|`msdyn_agreementbookingincident`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservice_AgreementBookingIncident`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: Agreement Booking Incident<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident"></a> msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident

Many-To-One Relationship: [msdyn_agreementbookingservicetask msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident](msdyn_agreementbookingservicetask.md#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_agreementbookingservicetask`|
|ReferencingAttribute|`msdyn_agreementbookingincident`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_agreementbookingincident_msdyn_agreementbookingservicetask_AgreementBookingIncident`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: Agreement Booking Incident<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_agreementbookingincident_msdyn_workorderincident_AgreementBookingIncident"></a> msdyn_msdyn_agreementbookingincident_msdyn_workorderincident_AgreementBookingIncident

Many-To-One Relationship: [msdyn_workorderincident msdyn_msdyn_agreementbookingincident_msdyn_workorderincident_AgreementBookingIncident](msdyn_workorderincident.md#BKMK_msdyn_msdyn_agreementbookingincident_msdyn_workorderincident_AgreementBookingIncident)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_workorderincident`|
|ReferencingAttribute|`msdyn_agreementbookingincident`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_agreementbookingincident_msdyn_workorderincident_AgreementBookingIncident`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

