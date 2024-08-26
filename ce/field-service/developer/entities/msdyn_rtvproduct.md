---
title: "RTV Product (msdyn_rtvproduct) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the RTV Product (msdyn_rtvproduct) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# RTV Product (msdyn_rtvproduct) table/entity reference

Records products to be returned on an RTV

## Messages

The following table lists the messages for the RTV Product (msdyn_rtvproduct) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_rtvproducts(*msdyn_rtvproductid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_rtvproducts<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_rtvproducts(*msdyn_rtvproductid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_rtvproducts(*msdyn_rtvproductid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_rtvproducts<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_rtvproducts(*msdyn_rtvproductid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_rtvproducts(*msdyn_rtvproductid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_rtvproducts(*msdyn_rtvproductid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the RTV Product (msdyn_rtvproduct) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the RTV Product (msdyn_rtvproduct) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **RTV Product** |
| **DisplayCollectionName** | **RTV Products** |
| **SchemaName** | `msdyn_rtvproduct` |
| **CollectionSchemaName** | `msdyn_rtvproducts` |
| **EntitySetName** | `msdyn_rtvproducts`|
| **LogicalName** | `msdyn_rtvproduct` |
| **LogicalCollectionName** | `msdyn_rtvproducts` |
| **PrimaryIdAttribute** | `msdyn_rtvproductid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_Description](#BKMK_msdyn_Description)
- [msdyn_LineOrder](#BKMK_msdyn_LineOrder)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_Product](#BKMK_msdyn_Product)
- [msdyn_Quantity](#BKMK_msdyn_Quantity)
- [msdyn_RMA](#BKMK_msdyn_RMA)
- [msdyn_RMAProduct](#BKMK_msdyn_RMAProduct)
- [msdyn_RTV](#BKMK_msdyn_RTV)
- [msdyn_rtvproductId](#BKMK_msdyn_rtvproductId)
- [msdyn_TotalCreditAmount](#BKMK_msdyn_TotalCreditAmount)
- [msdyn_Unit](#BKMK_msdyn_Unit)
- [msdyn_UnitCreditAmount](#BKMK_msdyn_UnitCreditAmount)
- [msdyn_Warehouse](#BKMK_msdyn_Warehouse)
- [msdyn_WorkOrder](#BKMK_msdyn_WorkOrder)
- [msdyn_WorkOrderProduct](#BKMK_msdyn_WorkOrderProduct)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [TransactionCurrencyId](#BKMK_TransactionCurrencyId)
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

### <a name="BKMK_msdyn_Description"></a> msdyn_Description

|Property|Value|
|---|---|
|Description|**Type a description of the product.**|
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
|MaxLength|2000|

### <a name="BKMK_msdyn_LineOrder"></a> msdyn_LineOrder

|Property|Value|
|---|---|
|Description|**Shows the order of this product within the RTV.**|
|DisplayName|**Line Order**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_lineorder`|
|RequiredLevel|ApplicationRequired|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**Enter the name of the custom entity.**|
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

### <a name="BKMK_msdyn_Product"></a> msdyn_Product

|Property|Value|
|---|---|
|Description|**Product to return**|
|DisplayName|**Product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_product`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|product|

### <a name="BKMK_msdyn_Quantity"></a> msdyn_Quantity

|Property|Value|
|---|---|
|Description|**Enter the quantity returned.**|
|DisplayName|**Quantity**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_quantity`|
|RequiredLevel|ApplicationRequired|
|Type|Double|
|ImeMode|Auto|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|

### <a name="BKMK_msdyn_RMA"></a> msdyn_RMA

|Property|Value|
|---|---|
|Description|**Originating RMA if item was returned from customer**|
|DisplayName|**RMA**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_rma`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_rma|

### <a name="BKMK_msdyn_RMAProduct"></a> msdyn_RMAProduct

|Property|Value|
|---|---|
|Description|**Originating RMA Product if item was returned from customer**|
|DisplayName|**RMA Product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_rmaproduct`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_rmaproduct|

### <a name="BKMK_msdyn_RTV"></a> msdyn_RTV

|Property|Value|
|---|---|
|Description|**RTV this line item relates to**|
|DisplayName|**RTV**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_rtv`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_rtv|

### <a name="BKMK_msdyn_rtvproductId"></a> msdyn_rtvproductId

|Property|Value|
|---|---|
|Description|**Shows the entity instances.**|
|DisplayName|**RTV Product**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_rtvproductid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_TotalCreditAmount"></a> msdyn_TotalCreditAmount

|Property|Value|
|---|---|
|Description|**Shows the total Amount to be credited on this item.**|
|DisplayName|**Total Credit Amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_totalcreditamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|0 (Precision property)|

### <a name="BKMK_msdyn_Unit"></a> msdyn_Unit

|Property|Value|
|---|---|
|Description|**Unit for this product**|
|DisplayName|**Unit**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unit`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|uom|

### <a name="BKMK_msdyn_UnitCreditAmount"></a> msdyn_UnitCreditAmount

|Property|Value|
|---|---|
|Description|**Enter the unit amount to be credited.**|
|DisplayName|**Unit Credit Amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unitcreditamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|0 (Precision property)|

### <a name="BKMK_msdyn_Warehouse"></a> msdyn_Warehouse

|Property|Value|
|---|---|
|Description|**Warehouse from where this product is returned**|
|DisplayName|**Warehouse**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_warehouse`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_warehouse|

### <a name="BKMK_msdyn_WorkOrder"></a> msdyn_WorkOrder

|Property|Value|
|---|---|
|Description|**Originating Work Order if item was returned from customer**|
|DisplayName|**Work Order**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_workorder`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_workorder|

### <a name="BKMK_msdyn_WorkOrderProduct"></a> msdyn_WorkOrderProduct

|Property|Value|
|---|---|
|Description|**Originating Work Order Product if item was returned from customer**|
|DisplayName|**Work Order Product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_workorderproduct`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_workorderproduct|

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
|Description|**Status of the RTV Product**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_rtvproduct_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the RTV Product**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_rtvproduct_statuscode`|

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

### <a name="BKMK_TransactionCurrencyId"></a> TransactionCurrencyId

|Property|Value|
|---|---|
|Description|**Unique identifier of the currency associated with the entity.**|
|DisplayName|**Currency**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`transactioncurrencyid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|transactioncurrency|

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
- [ExchangeRate](#BKMK_ExchangeRate)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [msdyn_totalcreditamount_Base](#BKMK_msdyn_totalcreditamount_Base)
- [msdyn_unitcreditamount_Base](#BKMK_msdyn_unitcreditamount_Base)
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

### <a name="BKMK_ExchangeRate"></a> ExchangeRate

|Property|Value|
|---|---|
|Description|**Shows the exchange rate for the currency associated with the entity with respect to the base currency.**|
|DisplayName|**Exchange Rate**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`exchangerate`|
|RequiredLevel|None|
|Type|Decimal|
|ImeMode|Disabled|
|MaxValue|100000000000|
|MinValue|1E-10|
|Precision|10|
|SourceTypeMask|0|

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

### <a name="BKMK_msdyn_totalcreditamount_Base"></a> msdyn_totalcreditamount_Base

|Property|Value|
|---|---|
|Description|**Shows the value of the total credit amount in the base currency.**|
|DisplayName|**Total Credit Amount (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_totalcreditamount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|0 (Precision property)|

### <a name="BKMK_msdyn_unitcreditamount_Base"></a> msdyn_unitcreditamount_Base

|Property|Value|
|---|---|
|Description|**Shows the value of the unit credit amount in the base currency.**|
|DisplayName|**Unit Credit Amount (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unitcreditamount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|0 (Precision property)|

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

- [business_unit_msdyn_rtvproduct](#BKMK_business_unit_msdyn_rtvproduct)
- [lk_msdyn_rtvproduct_createdby](#BKMK_lk_msdyn_rtvproduct_createdby)
- [lk_msdyn_rtvproduct_createdonbehalfby](#BKMK_lk_msdyn_rtvproduct_createdonbehalfby)
- [lk_msdyn_rtvproduct_modifiedby](#BKMK_lk_msdyn_rtvproduct_modifiedby)
- [lk_msdyn_rtvproduct_modifiedonbehalfby](#BKMK_lk_msdyn_rtvproduct_modifiedonbehalfby)
- [msdyn_msdyn_rma_msdyn_rtvproduct_RMA](#BKMK_msdyn_msdyn_rma_msdyn_rtvproduct_RMA)
- [msdyn_msdyn_rmaproduct_msdyn_rtvproduct_RMAProduct](#BKMK_msdyn_msdyn_rmaproduct_msdyn_rtvproduct_RMAProduct)
- [msdyn_msdyn_rtv_msdyn_rtvproduct_RTV](#BKMK_msdyn_msdyn_rtv_msdyn_rtvproduct_RTV)
- [msdyn_msdyn_warehouse_msdyn_rtvproduct_Warehouse](#BKMK_msdyn_msdyn_warehouse_msdyn_rtvproduct_Warehouse)
- [msdyn_msdyn_workorder_msdyn_rtvproduct_WorkOrder](#BKMK_msdyn_msdyn_workorder_msdyn_rtvproduct_WorkOrder)
- [msdyn_msdyn_workorderproduct_msdyn_rtvproduct_WorkOrderProduct](#BKMK_msdyn_msdyn_workorderproduct_msdyn_rtvproduct_WorkOrderProduct)
- [msdyn_product_msdyn_rtvproduct_Product](#BKMK_msdyn_product_msdyn_rtvproduct_Product)
- [msdyn_uom_msdyn_rtvproduct_Unit](#BKMK_msdyn_uom_msdyn_rtvproduct_Unit)
- [owner_msdyn_rtvproduct](#BKMK_owner_msdyn_rtvproduct)
- [team_msdyn_rtvproduct](#BKMK_team_msdyn_rtvproduct)
- [TransactionCurrency_msdyn_rtvproduct](#BKMK_TransactionCurrency_msdyn_rtvproduct)
- [user_msdyn_rtvproduct](#BKMK_user_msdyn_rtvproduct)

### <a name="BKMK_business_unit_msdyn_rtvproduct"></a> business_unit_msdyn_rtvproduct

One-To-Many Relationship: [businessunit business_unit_msdyn_rtvproduct](businessunit.md#BKMK_business_unit_msdyn_rtvproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_rtvproduct_createdby"></a> lk_msdyn_rtvproduct_createdby

One-To-Many Relationship: [systemuser lk_msdyn_rtvproduct_createdby](systemuser.md#BKMK_lk_msdyn_rtvproduct_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_rtvproduct_createdonbehalfby"></a> lk_msdyn_rtvproduct_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_rtvproduct_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_rtvproduct_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_rtvproduct_modifiedby"></a> lk_msdyn_rtvproduct_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_rtvproduct_modifiedby](systemuser.md#BKMK_lk_msdyn_rtvproduct_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_rtvproduct_modifiedonbehalfby"></a> lk_msdyn_rtvproduct_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_rtvproduct_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_rtvproduct_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_rma_msdyn_rtvproduct_RMA"></a> msdyn_msdyn_rma_msdyn_rtvproduct_RMA

One-To-Many Relationship: [msdyn_rma msdyn_msdyn_rma_msdyn_rtvproduct_RMA](msdyn_rma.md#BKMK_msdyn_msdyn_rma_msdyn_rtvproduct_RMA)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_rma`|
|ReferencedAttribute|`msdyn_rmaid`|
|ReferencingAttribute|`msdyn_rma`|
|ReferencingEntityNavigationPropertyName|`msdyn_rma`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_rmaproduct_msdyn_rtvproduct_RMAProduct"></a> msdyn_msdyn_rmaproduct_msdyn_rtvproduct_RMAProduct

One-To-Many Relationship: [msdyn_rmaproduct msdyn_msdyn_rmaproduct_msdyn_rtvproduct_RMAProduct](msdyn_rmaproduct.md#BKMK_msdyn_msdyn_rmaproduct_msdyn_rtvproduct_RMAProduct)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_rmaproduct`|
|ReferencedAttribute|`msdyn_rmaproductid`|
|ReferencingAttribute|`msdyn_rmaproduct`|
|ReferencingEntityNavigationPropertyName|`msdyn_rmaproduct`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_rtv_msdyn_rtvproduct_RTV"></a> msdyn_msdyn_rtv_msdyn_rtvproduct_RTV

One-To-Many Relationship: [msdyn_rtv msdyn_msdyn_rtv_msdyn_rtvproduct_RTV](msdyn_rtv.md#BKMK_msdyn_msdyn_rtv_msdyn_rtvproduct_RTV)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_rtv`|
|ReferencedAttribute|`msdyn_rtvid`|
|ReferencingAttribute|`msdyn_rtv`|
|ReferencingEntityNavigationPropertyName|`msdyn_rtv`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_msdyn_warehouse_msdyn_rtvproduct_Warehouse"></a> msdyn_msdyn_warehouse_msdyn_rtvproduct_Warehouse

One-To-Many Relationship: [msdyn_warehouse msdyn_msdyn_warehouse_msdyn_rtvproduct_Warehouse](msdyn_warehouse.md#BKMK_msdyn_msdyn_warehouse_msdyn_rtvproduct_Warehouse)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_warehouse`|
|ReferencedAttribute|`msdyn_warehouseid`|
|ReferencingAttribute|`msdyn_warehouse`|
|ReferencingEntityNavigationPropertyName|`msdyn_warehouse`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_workorder_msdyn_rtvproduct_WorkOrder"></a> msdyn_msdyn_workorder_msdyn_rtvproduct_WorkOrder

One-To-Many Relationship: [msdyn_workorder msdyn_msdyn_workorder_msdyn_rtvproduct_WorkOrder](msdyn_workorder.md#BKMK_msdyn_msdyn_workorder_msdyn_rtvproduct_WorkOrder)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_workorder`|
|ReferencedAttribute|`msdyn_workorderid`|
|ReferencingAttribute|`msdyn_workorder`|
|ReferencingEntityNavigationPropertyName|`msdyn_workorder`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_workorderproduct_msdyn_rtvproduct_WorkOrderProduct"></a> msdyn_msdyn_workorderproduct_msdyn_rtvproduct_WorkOrderProduct

One-To-Many Relationship: [msdyn_workorderproduct msdyn_msdyn_workorderproduct_msdyn_rtvproduct_WorkOrderProduct](msdyn_workorderproduct.md#BKMK_msdyn_msdyn_workorderproduct_msdyn_rtvproduct_WorkOrderProduct)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_workorderproduct`|
|ReferencedAttribute|`msdyn_workorderproductid`|
|ReferencingAttribute|`msdyn_workorderproduct`|
|ReferencingEntityNavigationPropertyName|`msdyn_workorderproduct`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_product_msdyn_rtvproduct_Product"></a> msdyn_product_msdyn_rtvproduct_Product

One-To-Many Relationship: [product msdyn_product_msdyn_rtvproduct_Product](product.md#BKMK_msdyn_product_msdyn_rtvproduct_Product)

|Property|Value|
|---|---|
|ReferencedEntity|`product`|
|ReferencedAttribute|`productid`|
|ReferencingAttribute|`msdyn_product`|
|ReferencingEntityNavigationPropertyName|`msdyn_product`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_uom_msdyn_rtvproduct_Unit"></a> msdyn_uom_msdyn_rtvproduct_Unit

One-To-Many Relationship: [uom msdyn_uom_msdyn_rtvproduct_Unit](uom.md#BKMK_msdyn_uom_msdyn_rtvproduct_Unit)

|Property|Value|
|---|---|
|ReferencedEntity|`uom`|
|ReferencedAttribute|`uomid`|
|ReferencingAttribute|`msdyn_unit`|
|ReferencingEntityNavigationPropertyName|`msdyn_unit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_rtvproduct"></a> owner_msdyn_rtvproduct

One-To-Many Relationship: [owner owner_msdyn_rtvproduct](owner.md#BKMK_owner_msdyn_rtvproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_rtvproduct"></a> team_msdyn_rtvproduct

One-To-Many Relationship: [team team_msdyn_rtvproduct](team.md#BKMK_team_msdyn_rtvproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_TransactionCurrency_msdyn_rtvproduct"></a> TransactionCurrency_msdyn_rtvproduct

One-To-Many Relationship: [transactioncurrency TransactionCurrency_msdyn_rtvproduct](transactioncurrency.md#BKMK_TransactionCurrency_msdyn_rtvproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_rtvproduct"></a> user_msdyn_rtvproduct

One-To-Many Relationship: [systemuser user_msdyn_rtvproduct](systemuser.md#BKMK_user_msdyn_rtvproduct)

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

- [msdyn_msdyn_rtvproduct_msdyn_rmareceiptproduct_RTVProduct](#BKMK_msdyn_msdyn_rtvproduct_msdyn_rmareceiptproduct_RTVProduct)
- [msdyn_rtvproduct_ActivityPointers](#BKMK_msdyn_rtvproduct_ActivityPointers)
- [msdyn_rtvproduct_adx_inviteredemptions](#BKMK_msdyn_rtvproduct_adx_inviteredemptions)
- [msdyn_rtvproduct_adx_portalcomments](#BKMK_msdyn_rtvproduct_adx_portalcomments)
- [msdyn_rtvproduct_Annotations](#BKMK_msdyn_rtvproduct_Annotations)
- [msdyn_rtvproduct_Appointments](#BKMK_msdyn_rtvproduct_Appointments)
- [msdyn_rtvproduct_AsyncOperations](#BKMK_msdyn_rtvproduct_AsyncOperations)
- [msdyn_rtvproduct_BulkDeleteFailures](#BKMK_msdyn_rtvproduct_BulkDeleteFailures)
- [msdyn_rtvproduct_chats](#BKMK_msdyn_rtvproduct_chats)
- [msdyn_rtvproduct_connections1](#BKMK_msdyn_rtvproduct_connections1)
- [msdyn_rtvproduct_connections2](#BKMK_msdyn_rtvproduct_connections2)
- [msdyn_rtvproduct_DuplicateBaseRecord](#BKMK_msdyn_rtvproduct_DuplicateBaseRecord)
- [msdyn_rtvproduct_DuplicateMatchingRecord](#BKMK_msdyn_rtvproduct_DuplicateMatchingRecord)
- [msdyn_rtvproduct_Emails](#BKMK_msdyn_rtvproduct_Emails)
- [msdyn_rtvproduct_Faxes](#BKMK_msdyn_rtvproduct_Faxes)
- [msdyn_rtvproduct_Letters](#BKMK_msdyn_rtvproduct_Letters)
- [msdyn_rtvproduct_MailboxTrackingFolders](#BKMK_msdyn_rtvproduct_MailboxTrackingFolders)
- [msdyn_rtvproduct_msdyn_bookingalerts](#BKMK_msdyn_rtvproduct_msdyn_bookingalerts)
- [msdyn_rtvproduct_msdyn_copilottranscripts](#BKMK_msdyn_rtvproduct_msdyn_copilottranscripts)
- [msdyn_rtvproduct_msdyn_ocliveworkitems](#BKMK_msdyn_rtvproduct_msdyn_ocliveworkitems)
- [msdyn_rtvproduct_msdyn_ocsessions](#BKMK_msdyn_rtvproduct_msdyn_ocsessions)
- [msdyn_rtvproduct_msfp_alerts](#BKMK_msdyn_rtvproduct_msfp_alerts)
- [msdyn_rtvproduct_msfp_surveyinvites](#BKMK_msdyn_rtvproduct_msfp_surveyinvites)
- [msdyn_rtvproduct_msfp_surveyresponses](#BKMK_msdyn_rtvproduct_msfp_surveyresponses)
- [msdyn_rtvproduct_PhoneCalls](#BKMK_msdyn_rtvproduct_PhoneCalls)
- [msdyn_rtvproduct_PrincipalObjectAttributeAccesses](#BKMK_msdyn_rtvproduct_PrincipalObjectAttributeAccesses)
- [msdyn_rtvproduct_ProcessSession](#BKMK_msdyn_rtvproduct_ProcessSession)
- [msdyn_rtvproduct_RecurringAppointmentMasters](#BKMK_msdyn_rtvproduct_RecurringAppointmentMasters)
- [msdyn_rtvproduct_ServiceAppointments](#BKMK_msdyn_rtvproduct_ServiceAppointments)
- [msdyn_rtvproduct_SocialActivities](#BKMK_msdyn_rtvproduct_SocialActivities)
- [msdyn_rtvproduct_SyncErrors](#BKMK_msdyn_rtvproduct_SyncErrors)
- [msdyn_rtvproduct_Tasks](#BKMK_msdyn_rtvproduct_Tasks)

### <a name="BKMK_msdyn_msdyn_rtvproduct_msdyn_rmareceiptproduct_RTVProduct"></a> msdyn_msdyn_rtvproduct_msdyn_rmareceiptproduct_RTVProduct

Many-To-One Relationship: [msdyn_rmareceiptproduct msdyn_msdyn_rtvproduct_msdyn_rmareceiptproduct_RTVProduct](msdyn_rmareceiptproduct.md#BKMK_msdyn_msdyn_rtvproduct_msdyn_rmareceiptproduct_RTVProduct)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_rmareceiptproduct`|
|ReferencingAttribute|`msdyn_rtvproduct`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_rtvproduct_msdyn_rmareceiptproduct_RTVProduct`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_ActivityPointers"></a> msdyn_rtvproduct_ActivityPointers

Many-To-One Relationship: [activitypointer msdyn_rtvproduct_ActivityPointers](activitypointer.md#BKMK_msdyn_rtvproduct_ActivityPointers)

|Property|Value|
|---|---|
|ReferencingEntity|`activitypointer`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_ActivityPointers`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_adx_inviteredemptions"></a> msdyn_rtvproduct_adx_inviteredemptions

Many-To-One Relationship: [adx_inviteredemption msdyn_rtvproduct_adx_inviteredemptions](adx_inviteredemption.md#BKMK_msdyn_rtvproduct_adx_inviteredemptions)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_inviteredemption`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_adx_inviteredemptions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_adx_portalcomments"></a> msdyn_rtvproduct_adx_portalcomments

Many-To-One Relationship: [adx_portalcomment msdyn_rtvproduct_adx_portalcomments](adx_portalcomment.md#BKMK_msdyn_rtvproduct_adx_portalcomments)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_portalcomment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_adx_portalcomments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_Annotations"></a> msdyn_rtvproduct_Annotations

Many-To-One Relationship: [annotation msdyn_rtvproduct_Annotations](annotation.md#BKMK_msdyn_rtvproduct_Annotations)

|Property|Value|
|---|---|
|ReferencingEntity|`annotation`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_Annotations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_Appointments"></a> msdyn_rtvproduct_Appointments

Many-To-One Relationship: [appointment msdyn_rtvproduct_Appointments](appointment.md#BKMK_msdyn_rtvproduct_Appointments)

|Property|Value|
|---|---|
|ReferencingEntity|`appointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_Appointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_AsyncOperations"></a> msdyn_rtvproduct_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_rtvproduct_AsyncOperations](asyncoperation.md#BKMK_msdyn_rtvproduct_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_BulkDeleteFailures"></a> msdyn_rtvproduct_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_rtvproduct_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_rtvproduct_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_chats"></a> msdyn_rtvproduct_chats

Many-To-One Relationship: [chat msdyn_rtvproduct_chats](chat.md#BKMK_msdyn_rtvproduct_chats)

|Property|Value|
|---|---|
|ReferencingEntity|`chat`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_chats`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_connections1"></a> msdyn_rtvproduct_connections1

Many-To-One Relationship: [connection msdyn_rtvproduct_connections1](connection.md#BKMK_msdyn_rtvproduct_connections1)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record1id`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_connections1`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 100<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_connections2"></a> msdyn_rtvproduct_connections2

Many-To-One Relationship: [connection msdyn_rtvproduct_connections2](connection.md#BKMK_msdyn_rtvproduct_connections2)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record2id`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_connections2`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_DuplicateBaseRecord"></a> msdyn_rtvproduct_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_rtvproduct_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_rtvproduct_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_DuplicateMatchingRecord"></a> msdyn_rtvproduct_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_rtvproduct_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_rtvproduct_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_Emails"></a> msdyn_rtvproduct_Emails

Many-To-One Relationship: [email msdyn_rtvproduct_Emails](email.md#BKMK_msdyn_rtvproduct_Emails)

|Property|Value|
|---|---|
|ReferencingEntity|`email`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_Emails`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_Faxes"></a> msdyn_rtvproduct_Faxes

Many-To-One Relationship: [fax msdyn_rtvproduct_Faxes](fax.md#BKMK_msdyn_rtvproduct_Faxes)

|Property|Value|
|---|---|
|ReferencingEntity|`fax`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_Faxes`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_Letters"></a> msdyn_rtvproduct_Letters

Many-To-One Relationship: [letter msdyn_rtvproduct_Letters](letter.md#BKMK_msdyn_rtvproduct_Letters)

|Property|Value|
|---|---|
|ReferencingEntity|`letter`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_Letters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_MailboxTrackingFolders"></a> msdyn_rtvproduct_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_rtvproduct_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_rtvproduct_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_msdyn_bookingalerts"></a> msdyn_rtvproduct_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert msdyn_rtvproduct_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_msdyn_rtvproduct_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_msdyn_copilottranscripts"></a> msdyn_rtvproduct_msdyn_copilottranscripts

Many-To-One Relationship: [msdyn_copilottranscript msdyn_rtvproduct_msdyn_copilottranscripts](msdyn_copilottranscript.md#BKMK_msdyn_rtvproduct_msdyn_copilottranscripts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_copilottranscript`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_msdyn_copilottranscripts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_msdyn_ocliveworkitems"></a> msdyn_rtvproduct_msdyn_ocliveworkitems

Many-To-One Relationship: [msdyn_ocliveworkitem msdyn_rtvproduct_msdyn_ocliveworkitems](msdyn_ocliveworkitem.md#BKMK_msdyn_rtvproduct_msdyn_ocliveworkitems)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocliveworkitem`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_msdyn_ocliveworkitems`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_msdyn_ocsessions"></a> msdyn_rtvproduct_msdyn_ocsessions

Many-To-One Relationship: [msdyn_ocsession msdyn_rtvproduct_msdyn_ocsessions](msdyn_ocsession.md#BKMK_msdyn_rtvproduct_msdyn_ocsessions)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_msdyn_ocsessions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_msfp_alerts"></a> msdyn_rtvproduct_msfp_alerts

Many-To-One Relationship: [msfp_alert msdyn_rtvproduct_msfp_alerts](msfp_alert.md#BKMK_msdyn_rtvproduct_msfp_alerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_alert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_msfp_alerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_msfp_surveyinvites"></a> msdyn_rtvproduct_msfp_surveyinvites

Many-To-One Relationship: [msfp_surveyinvite msdyn_rtvproduct_msfp_surveyinvites](msfp_surveyinvite.md#BKMK_msdyn_rtvproduct_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyinvite`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_msfp_surveyinvites`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_msfp_surveyresponses"></a> msdyn_rtvproduct_msfp_surveyresponses

Many-To-One Relationship: [msfp_surveyresponse msdyn_rtvproduct_msfp_surveyresponses](msfp_surveyresponse.md#BKMK_msdyn_rtvproduct_msfp_surveyresponses)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyresponse`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_msfp_surveyresponses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_PhoneCalls"></a> msdyn_rtvproduct_PhoneCalls

Many-To-One Relationship: [phonecall msdyn_rtvproduct_PhoneCalls](phonecall.md#BKMK_msdyn_rtvproduct_PhoneCalls)

|Property|Value|
|---|---|
|ReferencingEntity|`phonecall`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_PhoneCalls`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_PrincipalObjectAttributeAccesses"></a> msdyn_rtvproduct_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_rtvproduct_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_rtvproduct_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_ProcessSession"></a> msdyn_rtvproduct_ProcessSession

Many-To-One Relationship: [processsession msdyn_rtvproduct_ProcessSession](processsession.md#BKMK_msdyn_rtvproduct_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_RecurringAppointmentMasters"></a> msdyn_rtvproduct_RecurringAppointmentMasters

Many-To-One Relationship: [recurringappointmentmaster msdyn_rtvproduct_RecurringAppointmentMasters](recurringappointmentmaster.md#BKMK_msdyn_rtvproduct_RecurringAppointmentMasters)

|Property|Value|
|---|---|
|ReferencingEntity|`recurringappointmentmaster`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_RecurringAppointmentMasters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_ServiceAppointments"></a> msdyn_rtvproduct_ServiceAppointments

Many-To-One Relationship: [serviceappointment msdyn_rtvproduct_ServiceAppointments](serviceappointment.md#BKMK_msdyn_rtvproduct_ServiceAppointments)

|Property|Value|
|---|---|
|ReferencingEntity|`serviceappointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_ServiceAppointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_SocialActivities"></a> msdyn_rtvproduct_SocialActivities

Many-To-One Relationship: [socialactivity msdyn_rtvproduct_SocialActivities](socialactivity.md#BKMK_msdyn_rtvproduct_SocialActivities)

|Property|Value|
|---|---|
|ReferencingEntity|`socialactivity`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_SocialActivities`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_SyncErrors"></a> msdyn_rtvproduct_SyncErrors

Many-To-One Relationship: [syncerror msdyn_rtvproduct_SyncErrors](syncerror.md#BKMK_msdyn_rtvproduct_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rtvproduct_Tasks"></a> msdyn_rtvproduct_Tasks

Many-To-One Relationship: [task msdyn_rtvproduct_Tasks](task.md#BKMK_msdyn_rtvproduct_Tasks)

|Property|Value|
|---|---|
|ReferencingEntity|`task`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_rtvproduct_Tasks`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

