---
title: "Purchase Order Product (msdyn_purchaseorderproduct) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Purchase Order Product (msdyn_purchaseorderproduct) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Purchase Order Product (msdyn_purchaseorderproduct) table/entity reference

Record products to be ordered on purchase order

## Messages

The following table lists the messages for the Purchase Order Product (msdyn_purchaseorderproduct) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_purchaseorderproducts(*msdyn_purchaseorderproductid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_purchaseorderproducts<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_purchaseorderproducts(*msdyn_purchaseorderproductid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_purchaseorderproducts(*msdyn_purchaseorderproductid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_purchaseorderproducts<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_purchaseorderproducts(*msdyn_purchaseorderproductid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_purchaseorderproducts(*msdyn_purchaseorderproductid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_purchaseorderproducts(*msdyn_purchaseorderproductid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Purchase Order Product (msdyn_purchaseorderproduct) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Purchase Order Product (msdyn_purchaseorderproduct) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Purchase Order Product** |
| **DisplayCollectionName** | **Purchase Order Products** |
| **SchemaName** | `msdyn_purchaseorderproduct` |
| **CollectionSchemaName** | `msdyn_purchaseorderproducts` |
| **EntitySetName** | `msdyn_purchaseorderproducts`|
| **LogicalName** | `msdyn_purchaseorderproduct` |
| **LogicalCollectionName** | `msdyn_purchaseorderproducts` |
| **PrimaryIdAttribute** | `msdyn_purchaseorderproductid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_AssociateToBooking](#BKMK_msdyn_AssociateToBooking)
- [msdyn_AssociateToWarehouse](#BKMK_msdyn_AssociateToWarehouse)
- [msdyn_AssociateToWorkOrder](#BKMK_msdyn_AssociateToWorkOrder)
- [msdyn_DateExpected](#BKMK_msdyn_DateExpected)
- [msdyn_Description](#BKMK_msdyn_Description)
- [msdyn_InternalFlags](#BKMK_msdyn_InternalFlags)
- [msdyn_IsOrdered](#BKMK_msdyn_IsOrdered)
- [msdyn_ItemStatus](#BKMK_msdyn_ItemStatus)
- [msdyn_LineOrder](#BKMK_msdyn_LineOrder)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_Product](#BKMK_msdyn_Product)
- [msdyn_PurchaseOrder](#BKMK_msdyn_PurchaseOrder)
- [msdyn_purchaseorderproductId](#BKMK_msdyn_purchaseorderproductId)
- [msdyn_QtyBilled](#BKMK_msdyn_QtyBilled)
- [msdyn_QtyReceived](#BKMK_msdyn_QtyReceived)
- [msdyn_Quantity](#BKMK_msdyn_Quantity)
- [msdyn_TotalCost](#BKMK_msdyn_TotalCost)
- [msdyn_Unit](#BKMK_msdyn_Unit)
- [msdyn_UnitCost](#BKMK_msdyn_UnitCost)
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

### <a name="BKMK_msdyn_AssociateToBooking"></a> msdyn_AssociateToBooking

|Property|Value|
|---|---|
|Description|**Link this product to Booking. If specified and warehouse is not set then product will be added to Resource Booking**|
|DisplayName|**Associate To Booking**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_associatetobooking`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|bookableresourcebooking|

### <a name="BKMK_msdyn_AssociateToWarehouse"></a> msdyn_AssociateToWarehouse

|Property|Value|
|---|---|
|Description|**Warehouse to which this product should be received to**|
|DisplayName|**Associate To Warehouse**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_associatetowarehouse`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_warehouse|

### <a name="BKMK_msdyn_AssociateToWorkOrder"></a> msdyn_AssociateToWorkOrder

|Property|Value|
|---|---|
|Description|**Link this product to Work Order. If specified and warehouse is not set then product will be added to work order**|
|DisplayName|**Associate To Work Order**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_associatetoworkorder`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_workorder|

### <a name="BKMK_msdyn_DateExpected"></a> msdyn_DateExpected

|Property|Value|
|---|---|
|Description|**Enter the date you expect this product to arrive to the shipping address. This value defaults to the date set on the PO.**|
|DisplayName|**Date Expected**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_dateexpected`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_Description"></a> msdyn_Description

|Property|Value|
|---|---|
|Description|**Enter the product description to display for the vendor.**|
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

### <a name="BKMK_msdyn_IsOrdered"></a> msdyn_IsOrdered

|Property|Value|
|---|---|
|Description||
|DisplayName|**Is Ordered**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_isordered`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_purchaseorderproduct_msdyn_isordered`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_ItemStatus"></a> msdyn_ItemStatus

|Property|Value|
|---|---|
|Description|**Enter the current status of this product.**|
|DisplayName|**Item Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_itemstatus`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|690970000|
|GlobalChoiceName|`msdyn_purchaseorderproductstatus`|

#### msdyn_ItemStatus Choices/Options

|Value|Label|
|---|---|
|690970000|**Pending**|
|690970001|**Received**|
|690970002|**Canceled**|

### <a name="BKMK_msdyn_LineOrder"></a> msdyn_LineOrder

|Property|Value|
|---|---|
|Description|**Shows the order of this product within the purchase order.**|
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
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_Product"></a> msdyn_Product

|Property|Value|
|---|---|
|Description|**Product to order**|
|DisplayName|**Product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_product`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|product|

### <a name="BKMK_msdyn_PurchaseOrder"></a> msdyn_PurchaseOrder

|Property|Value|
|---|---|
|Description|**Purchase order this line item relates to**|
|DisplayName|**Purchase Order**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_purchaseorder`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_purchaseorder|

### <a name="BKMK_msdyn_purchaseorderproductId"></a> msdyn_purchaseorderproductId

|Property|Value|
|---|---|
|Description|**Shows the entity instances.**|
|DisplayName|**Purchase Order Product**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_purchaseorderproductid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_QtyBilled"></a> msdyn_QtyBilled

|Property|Value|
|---|---|
|Description|**Enter the quantity currently billed.**|
|DisplayName|**Quantity Billed**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_qtybilled`|
|RequiredLevel|None|
|Type|Double|
|ImeMode|Auto|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|

### <a name="BKMK_msdyn_QtyReceived"></a> msdyn_QtyReceived

|Property|Value|
|---|---|
|Description|**Enter the quantity currently received.**|
|DisplayName|**Quantity Received**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_qtyreceived`|
|RequiredLevel|None|
|Type|Double|
|ImeMode|Auto|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|

### <a name="BKMK_msdyn_Quantity"></a> msdyn_Quantity

|Property|Value|
|---|---|
|Description|**Enter the quantity ordered.**|
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

### <a name="BKMK_msdyn_TotalCost"></a> msdyn_TotalCost

|Property|Value|
|---|---|
|Description|**Shows the total cost of this product. This is calculated by (Unit Cost * Units) + Additional Cost + Commission Costs**|
|DisplayName|**Total Cost**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_totalcost`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|0|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

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

### <a name="BKMK_msdyn_UnitCost"></a> msdyn_UnitCost

|Property|Value|
|---|---|
|Description|**Enter the cost of this product per unit.**|
|DisplayName|**Unit Cost**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unitcost`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

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
|Description|**Status of the Purchase Order Product**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_purchaseorderproduct_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Purchase Order Product**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_purchaseorderproduct_statuscode`|

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
|RequiredLevel|ApplicationRequired|
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
- [msdyn_totalcost_Base](#BKMK_msdyn_totalcost_Base)
- [msdyn_unitcost_Base](#BKMK_msdyn_unitcost_Base)
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

### <a name="BKMK_msdyn_totalcost_Base"></a> msdyn_totalcost_Base

|Property|Value|
|---|---|
|Description|**Shows the value of the total cost in the base currency.**|
|DisplayName|**Total Cost (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_totalcost_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

### <a name="BKMK_msdyn_unitcost_Base"></a> msdyn_unitcost_Base

|Property|Value|
|---|---|
|Description|**Shows the value of the unit cost in the base currency.**|
|DisplayName|**Unit Cost (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unitcost_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

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

- [business_unit_msdyn_purchaseorderproduct](#BKMK_business_unit_msdyn_purchaseorderproduct)
- [lk_msdyn_purchaseorderproduct_createdby](#BKMK_lk_msdyn_purchaseorderproduct_createdby)
- [lk_msdyn_purchaseorderproduct_createdonbehalfby](#BKMK_lk_msdyn_purchaseorderproduct_createdonbehalfby)
- [lk_msdyn_purchaseorderproduct_modifiedby](#BKMK_lk_msdyn_purchaseorderproduct_modifiedby)
- [lk_msdyn_purchaseorderproduct_modifiedonbehalfby](#BKMK_lk_msdyn_purchaseorderproduct_modifiedonbehalfby)
- [msdyn_bookableresourcebooking_msdyn_purchaseorderproduct_AssociateToBooking](#BKMK_msdyn_bookableresourcebooking_msdyn_purchaseorderproduct_AssociateToBooking)
- [msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder](#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder)
- [msdyn_msdyn_warehouse_msdyn_purchaseorderproduct_AssociateToWarehouse](#BKMK_msdyn_msdyn_warehouse_msdyn_purchaseorderproduct_AssociateToWarehouse)
- [msdyn_msdyn_workorder_msdyn_purchaseorderproduct_AssociateToWorkOrder](#BKMK_msdyn_msdyn_workorder_msdyn_purchaseorderproduct_AssociateToWorkOrder)
- [msdyn_product_msdyn_purchaseorderproduct_Product](#BKMK_msdyn_product_msdyn_purchaseorderproduct_Product)
- [msdyn_uom_msdyn_purchaseorderproduct_Unit](#BKMK_msdyn_uom_msdyn_purchaseorderproduct_Unit)
- [owner_msdyn_purchaseorderproduct](#BKMK_owner_msdyn_purchaseorderproduct)
- [team_msdyn_purchaseorderproduct](#BKMK_team_msdyn_purchaseorderproduct)
- [TransactionCurrency_msdyn_purchaseorderproduct](#BKMK_TransactionCurrency_msdyn_purchaseorderproduct)
- [user_msdyn_purchaseorderproduct](#BKMK_user_msdyn_purchaseorderproduct)

### <a name="BKMK_business_unit_msdyn_purchaseorderproduct"></a> business_unit_msdyn_purchaseorderproduct

One-To-Many Relationship: [businessunit business_unit_msdyn_purchaseorderproduct](businessunit.md#BKMK_business_unit_msdyn_purchaseorderproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorderproduct_createdby"></a> lk_msdyn_purchaseorderproduct_createdby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorderproduct_createdby](systemuser.md#BKMK_lk_msdyn_purchaseorderproduct_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorderproduct_createdonbehalfby"></a> lk_msdyn_purchaseorderproduct_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorderproduct_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_purchaseorderproduct_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorderproduct_modifiedby"></a> lk_msdyn_purchaseorderproduct_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorderproduct_modifiedby](systemuser.md#BKMK_lk_msdyn_purchaseorderproduct_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorderproduct_modifiedonbehalfby"></a> lk_msdyn_purchaseorderproduct_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorderproduct_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_purchaseorderproduct_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_bookableresourcebooking_msdyn_purchaseorderproduct_AssociateToBooking"></a> msdyn_bookableresourcebooking_msdyn_purchaseorderproduct_AssociateToBooking

One-To-Many Relationship: [bookableresourcebooking msdyn_bookableresourcebooking_msdyn_purchaseorderproduct_AssociateToBooking](bookableresourcebooking.md#BKMK_msdyn_bookableresourcebooking_msdyn_purchaseorderproduct_AssociateToBooking)

|Property|Value|
|---|---|
|ReferencedEntity|`bookableresourcebooking`|
|ReferencedAttribute|`bookableresourcebookingid`|
|ReferencingAttribute|`msdyn_associatetobooking`|
|ReferencingEntityNavigationPropertyName|`msdyn_associatetobooking`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder"></a> msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder

One-To-Many Relationship: [msdyn_purchaseorder msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder](msdyn_purchaseorder.md#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_purchaseorder`|
|ReferencedAttribute|`msdyn_purchaseorderid`|
|ReferencingAttribute|`msdyn_purchaseorder`|
|ReferencingEntityNavigationPropertyName|`msdyn_purchaseorder`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_warehouse_msdyn_purchaseorderproduct_AssociateToWarehouse"></a> msdyn_msdyn_warehouse_msdyn_purchaseorderproduct_AssociateToWarehouse

One-To-Many Relationship: [msdyn_warehouse msdyn_msdyn_warehouse_msdyn_purchaseorderproduct_AssociateToWarehouse](msdyn_warehouse.md#BKMK_msdyn_msdyn_warehouse_msdyn_purchaseorderproduct_AssociateToWarehouse)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_warehouse`|
|ReferencedAttribute|`msdyn_warehouseid`|
|ReferencingAttribute|`msdyn_associatetowarehouse`|
|ReferencingEntityNavigationPropertyName|`msdyn_associatetowarehouse`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_workorder_msdyn_purchaseorderproduct_AssociateToWorkOrder"></a> msdyn_msdyn_workorder_msdyn_purchaseorderproduct_AssociateToWorkOrder

One-To-Many Relationship: [msdyn_workorder msdyn_msdyn_workorder_msdyn_purchaseorderproduct_AssociateToWorkOrder](msdyn_workorder.md#BKMK_msdyn_msdyn_workorder_msdyn_purchaseorderproduct_AssociateToWorkOrder)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_workorder`|
|ReferencedAttribute|`msdyn_workorderid`|
|ReferencingAttribute|`msdyn_associatetoworkorder`|
|ReferencingEntityNavigationPropertyName|`msdyn_associatetoworkorder`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_product_msdyn_purchaseorderproduct_Product"></a> msdyn_product_msdyn_purchaseorderproduct_Product

One-To-Many Relationship: [product msdyn_product_msdyn_purchaseorderproduct_Product](product.md#BKMK_msdyn_product_msdyn_purchaseorderproduct_Product)

|Property|Value|
|---|---|
|ReferencedEntity|`product`|
|ReferencedAttribute|`productid`|
|ReferencingAttribute|`msdyn_product`|
|ReferencingEntityNavigationPropertyName|`msdyn_product`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_uom_msdyn_purchaseorderproduct_Unit"></a> msdyn_uom_msdyn_purchaseorderproduct_Unit

One-To-Many Relationship: [uom msdyn_uom_msdyn_purchaseorderproduct_Unit](uom.md#BKMK_msdyn_uom_msdyn_purchaseorderproduct_Unit)

|Property|Value|
|---|---|
|ReferencedEntity|`uom`|
|ReferencedAttribute|`uomid`|
|ReferencingAttribute|`msdyn_unit`|
|ReferencingEntityNavigationPropertyName|`msdyn_unit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_purchaseorderproduct"></a> owner_msdyn_purchaseorderproduct

One-To-Many Relationship: [owner owner_msdyn_purchaseorderproduct](owner.md#BKMK_owner_msdyn_purchaseorderproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_purchaseorderproduct"></a> team_msdyn_purchaseorderproduct

One-To-Many Relationship: [team team_msdyn_purchaseorderproduct](team.md#BKMK_team_msdyn_purchaseorderproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_TransactionCurrency_msdyn_purchaseorderproduct"></a> TransactionCurrency_msdyn_purchaseorderproduct

One-To-Many Relationship: [transactioncurrency TransactionCurrency_msdyn_purchaseorderproduct](transactioncurrency.md#BKMK_TransactionCurrency_msdyn_purchaseorderproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_purchaseorderproduct"></a> user_msdyn_purchaseorderproduct

One-To-Many Relationship: [systemuser user_msdyn_purchaseorderproduct](systemuser.md#BKMK_user_msdyn_purchaseorderproduct)

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

- [msdyn_msdyn_purchaseorderproduct_msdyn_inventoryjournal_POProduct](#BKMK_msdyn_msdyn_purchaseorderproduct_msdyn_inventoryjournal_POProduct)
- [msdyn_msdyn_purchaseorderproduct_msdyn_purchaseorderreceiptproduct_POProduct](#BKMK_msdyn_msdyn_purchaseorderproduct_msdyn_purchaseorderreceiptproduct_POProduct)
- [msdyn_purchaseorderproduct_ActivityPointers](#BKMK_msdyn_purchaseorderproduct_ActivityPointers)
- [msdyn_purchaseorderproduct_adx_inviteredemptions](#BKMK_msdyn_purchaseorderproduct_adx_inviteredemptions)
- [msdyn_purchaseorderproduct_adx_portalcomments](#BKMK_msdyn_purchaseorderproduct_adx_portalcomments)
- [msdyn_purchaseorderproduct_Annotations](#BKMK_msdyn_purchaseorderproduct_Annotations)
- [msdyn_purchaseorderproduct_Appointments](#BKMK_msdyn_purchaseorderproduct_Appointments)
- [msdyn_purchaseorderproduct_AsyncOperations](#BKMK_msdyn_purchaseorderproduct_AsyncOperations)
- [msdyn_purchaseorderproduct_BulkDeleteFailures](#BKMK_msdyn_purchaseorderproduct_BulkDeleteFailures)
- [msdyn_purchaseorderproduct_chats](#BKMK_msdyn_purchaseorderproduct_chats)
- [msdyn_purchaseorderproduct_connections1](#BKMK_msdyn_purchaseorderproduct_connections1)
- [msdyn_purchaseorderproduct_connections2](#BKMK_msdyn_purchaseorderproduct_connections2)
- [msdyn_purchaseorderproduct_Emails](#BKMK_msdyn_purchaseorderproduct_Emails)
- [msdyn_purchaseorderproduct_Faxes](#BKMK_msdyn_purchaseorderproduct_Faxes)
- [msdyn_purchaseorderproduct_Letters](#BKMK_msdyn_purchaseorderproduct_Letters)
- [msdyn_purchaseorderproduct_MailboxTrackingFolders](#BKMK_msdyn_purchaseorderproduct_MailboxTrackingFolders)
- [msdyn_purchaseorderproduct_msdyn_bookingalerts](#BKMK_msdyn_purchaseorderproduct_msdyn_bookingalerts)
- [msdyn_purchaseorderproduct_msdyn_copilottranscripts](#BKMK_msdyn_purchaseorderproduct_msdyn_copilottranscripts)
- [msdyn_purchaseorderproduct_msdyn_ocliveworkitems](#BKMK_msdyn_purchaseorderproduct_msdyn_ocliveworkitems)
- [msdyn_purchaseorderproduct_msdyn_ocsessions](#BKMK_msdyn_purchaseorderproduct_msdyn_ocsessions)
- [msdyn_purchaseorderproduct_msfp_alerts](#BKMK_msdyn_purchaseorderproduct_msfp_alerts)
- [msdyn_purchaseorderproduct_msfp_surveyinvites](#BKMK_msdyn_purchaseorderproduct_msfp_surveyinvites)
- [msdyn_purchaseorderproduct_msfp_surveyresponses](#BKMK_msdyn_purchaseorderproduct_msfp_surveyresponses)
- [msdyn_purchaseorderproduct_PhoneCalls](#BKMK_msdyn_purchaseorderproduct_PhoneCalls)
- [msdyn_purchaseorderproduct_PrincipalObjectAttributeAccesses](#BKMK_msdyn_purchaseorderproduct_PrincipalObjectAttributeAccesses)
- [msdyn_purchaseorderproduct_ProcessSession](#BKMK_msdyn_purchaseorderproduct_ProcessSession)
- [msdyn_purchaseorderproduct_RecurringAppointmentMasters](#BKMK_msdyn_purchaseorderproduct_RecurringAppointmentMasters)
- [msdyn_purchaseorderproduct_ServiceAppointments](#BKMK_msdyn_purchaseorderproduct_ServiceAppointments)
- [msdyn_purchaseorderproduct_SharePointDocumentLocations](#BKMK_msdyn_purchaseorderproduct_SharePointDocumentLocations)
- [msdyn_purchaseorderproduct_SocialActivities](#BKMK_msdyn_purchaseorderproduct_SocialActivities)
- [msdyn_purchaseorderproduct_SyncErrors](#BKMK_msdyn_purchaseorderproduct_SyncErrors)
- [msdyn_purchaseorderproduct_Tasks](#BKMK_msdyn_purchaseorderproduct_Tasks)

### <a name="BKMK_msdyn_msdyn_purchaseorderproduct_msdyn_inventoryjournal_POProduct"></a> msdyn_msdyn_purchaseorderproduct_msdyn_inventoryjournal_POProduct

Many-To-One Relationship: [msdyn_inventoryjournal msdyn_msdyn_purchaseorderproduct_msdyn_inventoryjournal_POProduct](msdyn_inventoryjournal.md#BKMK_msdyn_msdyn_purchaseorderproduct_msdyn_inventoryjournal_POProduct)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_inventoryjournal`|
|ReferencingAttribute|`msdyn_purchaseorderproduct`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_purchaseorderproduct_msdyn_inventoryjournal_POProduct`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_purchaseorderproduct_msdyn_purchaseorderreceiptproduct_POProduct"></a> msdyn_msdyn_purchaseorderproduct_msdyn_purchaseorderreceiptproduct_POProduct

Many-To-One Relationship: [msdyn_purchaseorderreceiptproduct msdyn_msdyn_purchaseorderproduct_msdyn_purchaseorderreceiptproduct_POProduct](msdyn_purchaseorderreceiptproduct.md#BKMK_msdyn_msdyn_purchaseorderproduct_msdyn_purchaseorderreceiptproduct_POProduct)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_purchaseorderreceiptproduct`|
|ReferencingAttribute|`msdyn_purchaseorderproduct`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_purchaseorderproduct_msdyn_purchaseorderreceiptproduct_POProduct`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_ActivityPointers"></a> msdyn_purchaseorderproduct_ActivityPointers

Many-To-One Relationship: [activitypointer msdyn_purchaseorderproduct_ActivityPointers](activitypointer.md#BKMK_msdyn_purchaseorderproduct_ActivityPointers)

|Property|Value|
|---|---|
|ReferencingEntity|`activitypointer`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_ActivityPointers`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_adx_inviteredemptions"></a> msdyn_purchaseorderproduct_adx_inviteredemptions

Many-To-One Relationship: [adx_inviteredemption msdyn_purchaseorderproduct_adx_inviteredemptions](adx_inviteredemption.md#BKMK_msdyn_purchaseorderproduct_adx_inviteredemptions)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_inviteredemption`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_adx_inviteredemptions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_adx_portalcomments"></a> msdyn_purchaseorderproduct_adx_portalcomments

Many-To-One Relationship: [adx_portalcomment msdyn_purchaseorderproduct_adx_portalcomments](adx_portalcomment.md#BKMK_msdyn_purchaseorderproduct_adx_portalcomments)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_portalcomment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_adx_portalcomments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_Annotations"></a> msdyn_purchaseorderproduct_Annotations

Many-To-One Relationship: [annotation msdyn_purchaseorderproduct_Annotations](annotation.md#BKMK_msdyn_purchaseorderproduct_Annotations)

|Property|Value|
|---|---|
|ReferencingEntity|`annotation`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_Annotations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_Appointments"></a> msdyn_purchaseorderproduct_Appointments

Many-To-One Relationship: [appointment msdyn_purchaseorderproduct_Appointments](appointment.md#BKMK_msdyn_purchaseorderproduct_Appointments)

|Property|Value|
|---|---|
|ReferencingEntity|`appointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_Appointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_AsyncOperations"></a> msdyn_purchaseorderproduct_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_purchaseorderproduct_AsyncOperations](asyncoperation.md#BKMK_msdyn_purchaseorderproduct_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_BulkDeleteFailures"></a> msdyn_purchaseorderproduct_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_purchaseorderproduct_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_purchaseorderproduct_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_chats"></a> msdyn_purchaseorderproduct_chats

Many-To-One Relationship: [chat msdyn_purchaseorderproduct_chats](chat.md#BKMK_msdyn_purchaseorderproduct_chats)

|Property|Value|
|---|---|
|ReferencingEntity|`chat`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_chats`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_connections1"></a> msdyn_purchaseorderproduct_connections1

Many-To-One Relationship: [connection msdyn_purchaseorderproduct_connections1](connection.md#BKMK_msdyn_purchaseorderproduct_connections1)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record1id`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_connections1`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 100<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_connections2"></a> msdyn_purchaseorderproduct_connections2

Many-To-One Relationship: [connection msdyn_purchaseorderproduct_connections2](connection.md#BKMK_msdyn_purchaseorderproduct_connections2)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record2id`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_connections2`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_Emails"></a> msdyn_purchaseorderproduct_Emails

Many-To-One Relationship: [email msdyn_purchaseorderproduct_Emails](email.md#BKMK_msdyn_purchaseorderproduct_Emails)

|Property|Value|
|---|---|
|ReferencingEntity|`email`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_Emails`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_Faxes"></a> msdyn_purchaseorderproduct_Faxes

Many-To-One Relationship: [fax msdyn_purchaseorderproduct_Faxes](fax.md#BKMK_msdyn_purchaseorderproduct_Faxes)

|Property|Value|
|---|---|
|ReferencingEntity|`fax`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_Faxes`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_Letters"></a> msdyn_purchaseorderproduct_Letters

Many-To-One Relationship: [letter msdyn_purchaseorderproduct_Letters](letter.md#BKMK_msdyn_purchaseorderproduct_Letters)

|Property|Value|
|---|---|
|ReferencingEntity|`letter`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_Letters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_MailboxTrackingFolders"></a> msdyn_purchaseorderproduct_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_purchaseorderproduct_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_purchaseorderproduct_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_msdyn_bookingalerts"></a> msdyn_purchaseorderproduct_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert msdyn_purchaseorderproduct_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_msdyn_purchaseorderproduct_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_msdyn_copilottranscripts"></a> msdyn_purchaseorderproduct_msdyn_copilottranscripts

Many-To-One Relationship: [msdyn_copilottranscript msdyn_purchaseorderproduct_msdyn_copilottranscripts](msdyn_copilottranscript.md#BKMK_msdyn_purchaseorderproduct_msdyn_copilottranscripts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_copilottranscript`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_msdyn_copilottranscripts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_msdyn_ocliveworkitems"></a> msdyn_purchaseorderproduct_msdyn_ocliveworkitems

Many-To-One Relationship: [msdyn_ocliveworkitem msdyn_purchaseorderproduct_msdyn_ocliveworkitems](msdyn_ocliveworkitem.md#BKMK_msdyn_purchaseorderproduct_msdyn_ocliveworkitems)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocliveworkitem`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_msdyn_ocliveworkitems`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_msdyn_ocsessions"></a> msdyn_purchaseorderproduct_msdyn_ocsessions

Many-To-One Relationship: [msdyn_ocsession msdyn_purchaseorderproduct_msdyn_ocsessions](msdyn_ocsession.md#BKMK_msdyn_purchaseorderproduct_msdyn_ocsessions)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_msdyn_ocsessions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_msfp_alerts"></a> msdyn_purchaseorderproduct_msfp_alerts

Many-To-One Relationship: [msfp_alert msdyn_purchaseorderproduct_msfp_alerts](msfp_alert.md#BKMK_msdyn_purchaseorderproduct_msfp_alerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_alert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_msfp_alerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_msfp_surveyinvites"></a> msdyn_purchaseorderproduct_msfp_surveyinvites

Many-To-One Relationship: [msfp_surveyinvite msdyn_purchaseorderproduct_msfp_surveyinvites](msfp_surveyinvite.md#BKMK_msdyn_purchaseorderproduct_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyinvite`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_msfp_surveyinvites`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_msfp_surveyresponses"></a> msdyn_purchaseorderproduct_msfp_surveyresponses

Many-To-One Relationship: [msfp_surveyresponse msdyn_purchaseorderproduct_msfp_surveyresponses](msfp_surveyresponse.md#BKMK_msdyn_purchaseorderproduct_msfp_surveyresponses)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyresponse`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_msfp_surveyresponses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_PhoneCalls"></a> msdyn_purchaseorderproduct_PhoneCalls

Many-To-One Relationship: [phonecall msdyn_purchaseorderproduct_PhoneCalls](phonecall.md#BKMK_msdyn_purchaseorderproduct_PhoneCalls)

|Property|Value|
|---|---|
|ReferencingEntity|`phonecall`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_PhoneCalls`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_PrincipalObjectAttributeAccesses"></a> msdyn_purchaseorderproduct_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_purchaseorderproduct_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_purchaseorderproduct_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_ProcessSession"></a> msdyn_purchaseorderproduct_ProcessSession

Many-To-One Relationship: [processsession msdyn_purchaseorderproduct_ProcessSession](processsession.md#BKMK_msdyn_purchaseorderproduct_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_RecurringAppointmentMasters"></a> msdyn_purchaseorderproduct_RecurringAppointmentMasters

Many-To-One Relationship: [recurringappointmentmaster msdyn_purchaseorderproduct_RecurringAppointmentMasters](recurringappointmentmaster.md#BKMK_msdyn_purchaseorderproduct_RecurringAppointmentMasters)

|Property|Value|
|---|---|
|ReferencingEntity|`recurringappointmentmaster`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_RecurringAppointmentMasters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_ServiceAppointments"></a> msdyn_purchaseorderproduct_ServiceAppointments

Many-To-One Relationship: [serviceappointment msdyn_purchaseorderproduct_ServiceAppointments](serviceappointment.md#BKMK_msdyn_purchaseorderproduct_ServiceAppointments)

|Property|Value|
|---|---|
|ReferencingEntity|`serviceappointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_ServiceAppointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_SharePointDocumentLocations"></a> msdyn_purchaseorderproduct_SharePointDocumentLocations

Many-To-One Relationship: [sharepointdocumentlocation msdyn_purchaseorderproduct_SharePointDocumentLocations](sharepointdocumentlocation.md#BKMK_msdyn_purchaseorderproduct_SharePointDocumentLocations)

|Property|Value|
|---|---|
|ReferencingEntity|`sharepointdocumentlocation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_SharePointDocumentLocations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_SocialActivities"></a> msdyn_purchaseorderproduct_SocialActivities

Many-To-One Relationship: [socialactivity msdyn_purchaseorderproduct_SocialActivities](socialactivity.md#BKMK_msdyn_purchaseorderproduct_SocialActivities)

|Property|Value|
|---|---|
|ReferencingEntity|`socialactivity`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_SocialActivities`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_SyncErrors"></a> msdyn_purchaseorderproduct_SyncErrors

Many-To-One Relationship: [syncerror msdyn_purchaseorderproduct_SyncErrors](syncerror.md#BKMK_msdyn_purchaseorderproduct_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorderproduct_Tasks"></a> msdyn_purchaseorderproduct_Tasks

Many-To-One Relationship: [task msdyn_purchaseorderproduct_Tasks](task.md#BKMK_msdyn_purchaseorderproduct_Tasks)

|Property|Value|
|---|---|
|ReferencingEntity|`task`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorderproduct_Tasks`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

