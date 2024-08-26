---
title: "Purchase Order (msdyn_purchaseorder) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Purchase Order (msdyn_purchaseorder) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Purchase Order (msdyn_purchaseorder) table/entity reference

Record Purchase Orders pertaining to Work Orders or otherwise

## Messages

The following table lists the messages for the Purchase Order (msdyn_purchaseorder) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_purchaseorders(*msdyn_purchaseorderid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_purchaseorders<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_purchaseorders(*msdyn_purchaseorderid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_purchaseorders(*msdyn_purchaseorderid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_purchaseorders<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_purchaseorders(*msdyn_purchaseorderid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_purchaseorders(*msdyn_purchaseorderid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_purchaseorders(*msdyn_purchaseorderid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Purchase Order (msdyn_purchaseorder) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Purchase Order (msdyn_purchaseorder) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Purchase Order** |
| **DisplayCollectionName** | **Purchase Orders** |
| **SchemaName** | `msdyn_purchaseorder` |
| **CollectionSchemaName** | `msdyn_purchaseorders` |
| **EntitySetName** | `msdyn_purchaseorders`|
| **LogicalName** | `msdyn_purchaseorder` |
| **LogicalCollectionName** | `msdyn_purchaseorders` |
| **PrimaryIdAttribute** | `msdyn_purchaseorderid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_Address1](#BKMK_msdyn_Address1)
- [msdyn_Address2](#BKMK_msdyn_Address2)
- [msdyn_Address3](#BKMK_msdyn_Address3)
- [msdyn_AddressName](#BKMK_msdyn_AddressName)
- [msdyn_AmountBilled](#BKMK_msdyn_AmountBilled)
- [msdyn_ApprovalStatus](#BKMK_msdyn_ApprovalStatus)
- [msdyn_ApprovedRejectedBy](#BKMK_msdyn_ApprovedRejectedBy)
- [msdyn_AutoNumbering](#BKMK_msdyn_AutoNumbering)
- [msdyn_Booking](#BKMK_msdyn_Booking)
- [msdyn_City](#BKMK_msdyn_City)
- [msdyn_Country](#BKMK_msdyn_Country)
- [msdyn_DateExpected](#BKMK_msdyn_DateExpected)
- [msdyn_InternalFlags](#BKMK_msdyn_InternalFlags)
- [msdyn_Latitude](#BKMK_msdyn_Latitude)
- [msdyn_Longitude](#BKMK_msdyn_Longitude)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_OrderedBy](#BKMK_msdyn_OrderedBy)
- [msdyn_PaymentTerm](#BKMK_msdyn_PaymentTerm)
- [msdyn_PODate](#BKMK_msdyn_PODate)
- [msdyn_PostalCode](#BKMK_msdyn_PostalCode)
- [msdyn_purchaseorderId](#BKMK_msdyn_purchaseorderId)
- [msdyn_ReceivetoWarehouse](#BKMK_msdyn_ReceivetoWarehouse)
- [msdyn_RequestedByResource](#BKMK_msdyn_RequestedByResource)
- [msdyn_ShipTo](#BKMK_msdyn_ShipTo)
- [msdyn_ShipVia](#BKMK_msdyn_ShipVia)
- [msdyn_StateOrProvince](#BKMK_msdyn_StateOrProvince)
- [msdyn_SubStatus](#BKMK_msdyn_SubStatus)
- [msdyn_SystemStatus](#BKMK_msdyn_SystemStatus)
- [msdyn_TotalAmount](#BKMK_msdyn_TotalAmount)
- [msdyn_Vendor](#BKMK_msdyn_Vendor)
- [msdyn_VendorNote](#BKMK_msdyn_VendorNote)
- [msdyn_WorkOrder](#BKMK_msdyn_WorkOrder)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [processid](#BKMK_processid)
- [stageid](#BKMK_stageid)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [TransactionCurrencyId](#BKMK_TransactionCurrencyId)
- [traversedpath](#BKMK_traversedpath)
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

### <a name="BKMK_msdyn_Address1"></a> msdyn_Address1

|Property|Value|
|---|---|
|Description||
|DisplayName|**Street 1**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_address1`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|250|

### <a name="BKMK_msdyn_Address2"></a> msdyn_Address2

|Property|Value|
|---|---|
|Description||
|DisplayName|**Street 2**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_address2`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|250|

### <a name="BKMK_msdyn_Address3"></a> msdyn_Address3

|Property|Value|
|---|---|
|Description||
|DisplayName|**Street 3**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_address3`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|250|

### <a name="BKMK_msdyn_AddressName"></a> msdyn_AddressName

|Property|Value|
|---|---|
|Description|**Enter the location to ship the products of this PO to.**|
|DisplayName|**Address Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_addressname`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|250|

### <a name="BKMK_msdyn_AmountBilled"></a> msdyn_AmountBilled

|Property|Value|
|---|---|
|Description||
|DisplayName|**Amount Billed**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_amountbilled`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|900000000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

### <a name="BKMK_msdyn_ApprovalStatus"></a> msdyn_ApprovalStatus

|Property|Value|
|---|---|
|Description|**Enter the current status of the approval.**|
|DisplayName|**Approval Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_approvalstatus`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_poapprovalstatus`|

#### msdyn_ApprovalStatus Choices/Options

|Value|Label|
|---|---|
|690970000|**Approved**|
|690970001|**Rejected**|

### <a name="BKMK_msdyn_ApprovedRejectedBy"></a> msdyn_ApprovedRejectedBy

|Property|Value|
|---|---|
|Description|**The user who approved or rejected this PO**|
|DisplayName|**Approved/Rejected By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_approvedrejectedby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_msdyn_AutoNumbering"></a> msdyn_AutoNumbering

|Property|Value|
|---|---|
|Description|**Internal field used to generate the next name upon entity creation. It is optionally copied to the msdyn_name field.**|
|DisplayName|**Auto-Numbering**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_autonumbering`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_Booking"></a> msdyn_Booking

|Property|Value|
|---|---|
|Description|**If purchase order is being ordered directly to a booking specify here. Note, when specified, by default all products will receive directly to booking.**|
|DisplayName|**Booking**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_booking`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|bookableresourcebooking|

### <a name="BKMK_msdyn_City"></a> msdyn_City

|Property|Value|
|---|---|
|Description||
|DisplayName|**City**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_city`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|80|

### <a name="BKMK_msdyn_Country"></a> msdyn_Country

|Property|Value|
|---|---|
|Description||
|DisplayName|**Country/Region**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_country`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|80|

### <a name="BKMK_msdyn_DateExpected"></a> msdyn_DateExpected

|Property|Value|
|---|---|
|Description|**Enter the date you expect to receive your order. Note that products added once the date is specified here will automatically be set to this date.**|
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

### <a name="BKMK_msdyn_InternalFlags"></a> msdyn_InternalFlags

|Property|Value|
|---|---|
|Description|**For internal use only.**|
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

### <a name="BKMK_msdyn_Latitude"></a> msdyn_Latitude

|Property|Value|
|---|---|
|Description||
|DisplayName|**Latitude**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_latitude`|
|RequiredLevel|None|
|Type|Double|
|ImeMode|Auto|
|MaxValue|90|
|MinValue|-90|
|Precision|5|

### <a name="BKMK_msdyn_Longitude"></a> msdyn_Longitude

|Property|Value|
|---|---|
|Description||
|DisplayName|**Longitude**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_longitude`|
|RequiredLevel|None|
|Type|Double|
|ImeMode|Auto|
|MaxValue|180|
|MinValue|-180|
|Precision|5|

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

### <a name="BKMK_msdyn_OrderedBy"></a> msdyn_OrderedBy

|Property|Value|
|---|---|
|Description|**Unique identifier for User associated with Purchase Order.**|
|DisplayName|**Ordered By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_orderedby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_msdyn_PaymentTerm"></a> msdyn_PaymentTerm

|Property|Value|
|---|---|
|Description|**The payment terms for this PO**|
|DisplayName|**Payment Term**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_paymentterm`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_paymentterm|

### <a name="BKMK_msdyn_PODate"></a> msdyn_PODate

|Property|Value|
|---|---|
|Description|**Shows the date you submitted your order to the vendor. Note this field is for information only.**|
|DisplayName|**Purchase Order Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_purchaseorderdate`|
|RequiredLevel|ApplicationRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_PostalCode"></a> msdyn_PostalCode

|Property|Value|
|---|---|
|Description||
|DisplayName|**Postal Code**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_postalcode`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|20|

### <a name="BKMK_msdyn_purchaseorderId"></a> msdyn_purchaseorderId

|Property|Value|
|---|---|
|Description|**Shows the entity instances.**|
|DisplayName|**Purchase Order**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_purchaseorderid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_ReceivetoWarehouse"></a> msdyn_ReceivetoWarehouse

|Property|Value|
|---|---|
|Description|**Warehouse where products of this PO will be received to**|
|DisplayName|**Receive to Warehouse**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_receivetowarehouse`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_warehouse|

### <a name="BKMK_msdyn_RequestedByResource"></a> msdyn_RequestedByResource

|Property|Value|
|---|---|
|Description|**Resource that requested the purchase**|
|DisplayName|**Requested By Resource**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_requestedbyresource`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|bookableresource|

### <a name="BKMK_msdyn_ShipTo"></a> msdyn_ShipTo

|Property|Value|
|---|---|
|Description|**Enter the location to ship to. If the PO has been associated to a work order or a schedule, you can ship directly to the service account address.**|
|DisplayName|**Ship To**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_shipto`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_poshiptotype`|

#### msdyn_ShipTo Choices/Options

|Value|Label|
|---|---|
|690970000|**Site**|
|690970001|**Business Unit**|
|690970002|**Service Account**|
|690970003|**Other**|

### <a name="BKMK_msdyn_ShipVia"></a> msdyn_ShipVia

|Property|Value|
|---|---|
|Description|**Method of shipment by vendor**|
|DisplayName|**Ship Via**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_shipvia`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_shipvia|

### <a name="BKMK_msdyn_StateOrProvince"></a> msdyn_StateOrProvince

|Property|Value|
|---|---|
|Description||
|DisplayName|**State Or Province**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_stateorprovince`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|50|

### <a name="BKMK_msdyn_SubStatus"></a> msdyn_SubStatus

|Property|Value|
|---|---|
|Description|**Purchase Order Substatus**|
|DisplayName|**Substatus**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_substatus`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_purchaseordersubstatus|

### <a name="BKMK_msdyn_SystemStatus"></a> msdyn_SystemStatus

|Property|Value|
|---|---|
|Description|**Enter the current status of the purchase order.**|
|DisplayName|**System Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_systemstatus`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|690970000|
|GlobalChoiceName|`msdyn_posystemstatus`|

#### msdyn_SystemStatus Choices/Options

|Value|Label|
|---|---|
|690970000|**Draft**|
|690970001|**Submitted**|
|690970002|**Canceled**|
|690970003|**Products Received**|
|690970004|**Billed**|

### <a name="BKMK_msdyn_TotalAmount"></a> msdyn_TotalAmount

|Property|Value|
|---|---|
|Description|**Total Amount (used by Field Service only)**|
|DisplayName|**Total Amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_totalamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|0|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

### <a name="BKMK_msdyn_Vendor"></a> msdyn_Vendor

|Property|Value|
|---|---|
|Description|**Vendor you wish to purchase from**|
|DisplayName|**Vendor**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_vendor`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|account|

### <a name="BKMK_msdyn_VendorNote"></a> msdyn_VendorNote

|Property|Value|
|---|---|
|Description|**If you wish to display a note for the vendor on this PO specify it here**|
|DisplayName|**Vendor Note**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_vendornote`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

### <a name="BKMK_msdyn_WorkOrder"></a> msdyn_WorkOrder

|Property|Value|
|---|---|
|Description|**If purchase order is being ordered directly to a work order specify here. Note, when specified, by default all products will receive directly to work order.**|
|DisplayName|**Work Order**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_workorder`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_workorder|

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

### <a name="BKMK_processid"></a> processid

|Property|Value|
|---|---|
|Description|**Contains the ID of the process associated with the entity.**|
|DisplayName|**Process Id**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`processid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

### <a name="BKMK_stageid"></a> stageid

|Property|Value|
|---|---|
|Description|**Contains the ID of the stage where the entity is located.**|
|DisplayName|**Stage Id**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`stageid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the Purchase Order**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_purchaseorder_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Purchase Order**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_purchaseorder_statuscode`|

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

### <a name="BKMK_traversedpath"></a> traversedpath

|Property|Value|
|---|---|
|Description|**Shows a comma-separated list of string values that represent the unique identifiers of stages in a business process flow instance in the order that they occur.**|
|DisplayName|**Traversed Path**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`traversedpath`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1250|

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
- [msdyn_amountbilled_Base](#BKMK_msdyn_amountbilled_Base)
- [msdyn_totalamount_Base](#BKMK_msdyn_totalamount_Base)
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

### <a name="BKMK_msdyn_amountbilled_Base"></a> msdyn_amountbilled_Base

|Property|Value|
|---|---|
|Description|**Shows the value of the amount billed in the base currency.**|
|DisplayName|**Amount Billed (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_amountbilled_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

### <a name="BKMK_msdyn_totalamount_Base"></a> msdyn_totalamount_Base

|Property|Value|
|---|---|
|Description|**Shows the value of the total amount in the base currency.**|
|DisplayName|**Total Amount (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_totalamount_base`|
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

- [business_unit_msdyn_purchaseorder](#BKMK_business_unit_msdyn_purchaseorder)
- [lk_msdyn_purchaseorder_createdby](#BKMK_lk_msdyn_purchaseorder_createdby)
- [lk_msdyn_purchaseorder_createdonbehalfby](#BKMK_lk_msdyn_purchaseorder_createdonbehalfby)
- [lk_msdyn_purchaseorder_modifiedby](#BKMK_lk_msdyn_purchaseorder_modifiedby)
- [lk_msdyn_purchaseorder_modifiedonbehalfby](#BKMK_lk_msdyn_purchaseorder_modifiedonbehalfby)
- [msdyn_account_msdyn_purchaseorder_Vendor](#BKMK_msdyn_account_msdyn_purchaseorder_Vendor)
- [msdyn_bookableresource_msdyn_purchaseorder_RequestedByResource](#BKMK_msdyn_bookableresource_msdyn_purchaseorder_RequestedByResource)
- [msdyn_bookableresourcebooking_msdyn_purchaseorder_Booking](#BKMK_msdyn_bookableresourcebooking_msdyn_purchaseorder_Booking)
- [msdyn_msdyn_paymentterm_msdyn_purchaseorder_PaymentTerm](#BKMK_msdyn_msdyn_paymentterm_msdyn_purchaseorder_PaymentTerm)
- [msdyn_msdyn_purchaseordersubstatus_msdyn_purchaseorder_SubStatus](#BKMK_msdyn_msdyn_purchaseordersubstatus_msdyn_purchaseorder_SubStatus)
- [msdyn_msdyn_shipvia_msdyn_purchaseorder_ShipVia](#BKMK_msdyn_msdyn_shipvia_msdyn_purchaseorder_ShipVia)
- [msdyn_msdyn_warehouse_msdyn_purchaseorder_ReceivetoWarehouse](#BKMK_msdyn_msdyn_warehouse_msdyn_purchaseorder_ReceivetoWarehouse)
- [msdyn_msdyn_workorder_msdyn_purchaseorder_WorkOrder](#BKMK_msdyn_msdyn_workorder_msdyn_purchaseorder_WorkOrder)
- [msdyn_systemuser_msdyn_purchaseorder_ApprovedRejectedBy](#BKMK_msdyn_systemuser_msdyn_purchaseorder_ApprovedRejectedBy)
- [msdyn_systemuser_msdyn_purchaseorder_OrderedBy](#BKMK_msdyn_systemuser_msdyn_purchaseorder_OrderedBy)
- [owner_msdyn_purchaseorder](#BKMK_owner_msdyn_purchaseorder)
- [processstage_msdyn_purchaseorder](#BKMK_processstage_msdyn_purchaseorder)
- [team_msdyn_purchaseorder](#BKMK_team_msdyn_purchaseorder)
- [TransactionCurrency_msdyn_purchaseorder](#BKMK_TransactionCurrency_msdyn_purchaseorder)
- [user_msdyn_purchaseorder](#BKMK_user_msdyn_purchaseorder)

### <a name="BKMK_business_unit_msdyn_purchaseorder"></a> business_unit_msdyn_purchaseorder

One-To-Many Relationship: [businessunit business_unit_msdyn_purchaseorder](businessunit.md#BKMK_business_unit_msdyn_purchaseorder)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorder_createdby"></a> lk_msdyn_purchaseorder_createdby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorder_createdby](systemuser.md#BKMK_lk_msdyn_purchaseorder_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorder_createdonbehalfby"></a> lk_msdyn_purchaseorder_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorder_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_purchaseorder_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorder_modifiedby"></a> lk_msdyn_purchaseorder_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorder_modifiedby](systemuser.md#BKMK_lk_msdyn_purchaseorder_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_purchaseorder_modifiedonbehalfby"></a> lk_msdyn_purchaseorder_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_purchaseorder_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_purchaseorder_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_account_msdyn_purchaseorder_Vendor"></a> msdyn_account_msdyn_purchaseorder_Vendor

One-To-Many Relationship: [account msdyn_account_msdyn_purchaseorder_Vendor](account.md#BKMK_msdyn_account_msdyn_purchaseorder_Vendor)

|Property|Value|
|---|---|
|ReferencedEntity|`account`|
|ReferencedAttribute|`accountid`|
|ReferencingAttribute|`msdyn_vendor`|
|ReferencingEntityNavigationPropertyName|`msdyn_vendor`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `Cascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_bookableresource_msdyn_purchaseorder_RequestedByResource"></a> msdyn_bookableresource_msdyn_purchaseorder_RequestedByResource

One-To-Many Relationship: [bookableresource msdyn_bookableresource_msdyn_purchaseorder_RequestedByResource](bookableresource.md#BKMK_msdyn_bookableresource_msdyn_purchaseorder_RequestedByResource)

|Property|Value|
|---|---|
|ReferencedEntity|`bookableresource`|
|ReferencedAttribute|`bookableresourceid`|
|ReferencingAttribute|`msdyn_requestedbyresource`|
|ReferencingEntityNavigationPropertyName|`msdyn_requestedbyresource`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_bookableresourcebooking_msdyn_purchaseorder_Booking"></a> msdyn_bookableresourcebooking_msdyn_purchaseorder_Booking

One-To-Many Relationship: [bookableresourcebooking msdyn_bookableresourcebooking_msdyn_purchaseorder_Booking](bookableresourcebooking.md#BKMK_msdyn_bookableresourcebooking_msdyn_purchaseorder_Booking)

|Property|Value|
|---|---|
|ReferencedEntity|`bookableresourcebooking`|
|ReferencedAttribute|`bookableresourcebookingid`|
|ReferencingAttribute|`msdyn_booking`|
|ReferencingEntityNavigationPropertyName|`msdyn_booking`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_paymentterm_msdyn_purchaseorder_PaymentTerm"></a> msdyn_msdyn_paymentterm_msdyn_purchaseorder_PaymentTerm

One-To-Many Relationship: [msdyn_paymentterm msdyn_msdyn_paymentterm_msdyn_purchaseorder_PaymentTerm](msdyn_paymentterm.md#BKMK_msdyn_msdyn_paymentterm_msdyn_purchaseorder_PaymentTerm)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_paymentterm`|
|ReferencedAttribute|`msdyn_paymenttermid`|
|ReferencingAttribute|`msdyn_paymentterm`|
|ReferencingEntityNavigationPropertyName|`msdyn_paymentterm`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_purchaseordersubstatus_msdyn_purchaseorder_SubStatus"></a> msdyn_msdyn_purchaseordersubstatus_msdyn_purchaseorder_SubStatus

One-To-Many Relationship: [msdyn_purchaseordersubstatus msdyn_msdyn_purchaseordersubstatus_msdyn_purchaseorder_SubStatus](msdyn_purchaseordersubstatus.md#BKMK_msdyn_msdyn_purchaseordersubstatus_msdyn_purchaseorder_SubStatus)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_purchaseordersubstatus`|
|ReferencedAttribute|`msdyn_purchaseordersubstatusid`|
|ReferencingAttribute|`msdyn_substatus`|
|ReferencingEntityNavigationPropertyName|`msdyn_substatus`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_shipvia_msdyn_purchaseorder_ShipVia"></a> msdyn_msdyn_shipvia_msdyn_purchaseorder_ShipVia

One-To-Many Relationship: [msdyn_shipvia msdyn_msdyn_shipvia_msdyn_purchaseorder_ShipVia](msdyn_shipvia.md#BKMK_msdyn_msdyn_shipvia_msdyn_purchaseorder_ShipVia)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_shipvia`|
|ReferencedAttribute|`msdyn_shipviaid`|
|ReferencingAttribute|`msdyn_shipvia`|
|ReferencingEntityNavigationPropertyName|`msdyn_shipvia`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_warehouse_msdyn_purchaseorder_ReceivetoWarehouse"></a> msdyn_msdyn_warehouse_msdyn_purchaseorder_ReceivetoWarehouse

One-To-Many Relationship: [msdyn_warehouse msdyn_msdyn_warehouse_msdyn_purchaseorder_ReceivetoWarehouse](msdyn_warehouse.md#BKMK_msdyn_msdyn_warehouse_msdyn_purchaseorder_ReceivetoWarehouse)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_warehouse`|
|ReferencedAttribute|`msdyn_warehouseid`|
|ReferencingAttribute|`msdyn_receivetowarehouse`|
|ReferencingEntityNavigationPropertyName|`msdyn_receivetowarehouse`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_workorder_msdyn_purchaseorder_WorkOrder"></a> msdyn_msdyn_workorder_msdyn_purchaseorder_WorkOrder

One-To-Many Relationship: [msdyn_workorder msdyn_msdyn_workorder_msdyn_purchaseorder_WorkOrder](msdyn_workorder.md#BKMK_msdyn_msdyn_workorder_msdyn_purchaseorder_WorkOrder)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_workorder`|
|ReferencedAttribute|`msdyn_workorderid`|
|ReferencingAttribute|`msdyn_workorder`|
|ReferencingEntityNavigationPropertyName|`msdyn_workorder`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_systemuser_msdyn_purchaseorder_ApprovedRejectedBy"></a> msdyn_systemuser_msdyn_purchaseorder_ApprovedRejectedBy

One-To-Many Relationship: [systemuser msdyn_systemuser_msdyn_purchaseorder_ApprovedRejectedBy](systemuser.md#BKMK_msdyn_systemuser_msdyn_purchaseorder_ApprovedRejectedBy)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`msdyn_approvedrejectedby`|
|ReferencingEntityNavigationPropertyName|`msdyn_approvedrejectedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_systemuser_msdyn_purchaseorder_OrderedBy"></a> msdyn_systemuser_msdyn_purchaseorder_OrderedBy

One-To-Many Relationship: [systemuser msdyn_systemuser_msdyn_purchaseorder_OrderedBy](systemuser.md#BKMK_msdyn_systemuser_msdyn_purchaseorder_OrderedBy)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`msdyn_orderedby`|
|ReferencingEntityNavigationPropertyName|`msdyn_orderedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_purchaseorder"></a> owner_msdyn_purchaseorder

One-To-Many Relationship: [owner owner_msdyn_purchaseorder](owner.md#BKMK_owner_msdyn_purchaseorder)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_processstage_msdyn_purchaseorder"></a> processstage_msdyn_purchaseorder

One-To-Many Relationship: [processstage processstage_msdyn_purchaseorder](processstage.md#BKMK_processstage_msdyn_purchaseorder)

|Property|Value|
|---|---|
|ReferencedEntity|`processstage`|
|ReferencedAttribute|`processstageid`|
|ReferencingAttribute|`stageid`|
|ReferencingEntityNavigationPropertyName|`stageid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_purchaseorder"></a> team_msdyn_purchaseorder

One-To-Many Relationship: [team team_msdyn_purchaseorder](team.md#BKMK_team_msdyn_purchaseorder)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_TransactionCurrency_msdyn_purchaseorder"></a> TransactionCurrency_msdyn_purchaseorder

One-To-Many Relationship: [transactioncurrency TransactionCurrency_msdyn_purchaseorder](transactioncurrency.md#BKMK_TransactionCurrency_msdyn_purchaseorder)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_purchaseorder"></a> user_msdyn_purchaseorder

One-To-Many Relationship: [systemuser user_msdyn_purchaseorder](systemuser.md#BKMK_user_msdyn_purchaseorder)

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

- [bpf_msdyn_purchaseorder_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799](#BKMK_bpf_msdyn_purchaseorder_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799)
- [msdyn_msdyn_purchaseorder_msdyn_purchaseorderbill_PurchaseOrder](#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderbill_PurchaseOrder)
- [msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder](#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder)
- [msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceipt_PurchaseOrder](#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceipt_PurchaseOrder)
- [msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceiptproduct_PurchaseOrder](#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceiptproduct_PurchaseOrder)
- [msdyn_msdyn_purchaseorder_msdyn_rtv_OriginalPO](#BKMK_msdyn_msdyn_purchaseorder_msdyn_rtv_OriginalPO)
- [msdyn_purchaseorder_ActivityPointers](#BKMK_msdyn_purchaseorder_ActivityPointers)
- [msdyn_purchaseorder_adx_inviteredemptions](#BKMK_msdyn_purchaseorder_adx_inviteredemptions)
- [msdyn_purchaseorder_adx_portalcomments](#BKMK_msdyn_purchaseorder_adx_portalcomments)
- [msdyn_purchaseorder_Annotations](#BKMK_msdyn_purchaseorder_Annotations)
- [msdyn_purchaseorder_Appointments](#BKMK_msdyn_purchaseorder_Appointments)
- [msdyn_purchaseorder_AsyncOperations](#BKMK_msdyn_purchaseorder_AsyncOperations)
- [msdyn_purchaseorder_BulkDeleteFailures](#BKMK_msdyn_purchaseorder_BulkDeleteFailures)
- [msdyn_purchaseorder_chats](#BKMK_msdyn_purchaseorder_chats)
- [msdyn_purchaseorder_connections1](#BKMK_msdyn_purchaseorder_connections1)
- [msdyn_purchaseorder_connections2](#BKMK_msdyn_purchaseorder_connections2)
- [msdyn_purchaseorder_DuplicateBaseRecord](#BKMK_msdyn_purchaseorder_DuplicateBaseRecord)
- [msdyn_purchaseorder_DuplicateMatchingRecord](#BKMK_msdyn_purchaseorder_DuplicateMatchingRecord)
- [msdyn_purchaseorder_Emails](#BKMK_msdyn_purchaseorder_Emails)
- [msdyn_purchaseorder_Faxes](#BKMK_msdyn_purchaseorder_Faxes)
- [msdyn_purchaseorder_Letters](#BKMK_msdyn_purchaseorder_Letters)
- [msdyn_purchaseorder_MailboxTrackingFolders](#BKMK_msdyn_purchaseorder_MailboxTrackingFolders)
- [msdyn_purchaseorder_msdyn_bookingalerts](#BKMK_msdyn_purchaseorder_msdyn_bookingalerts)
- [msdyn_purchaseorder_msdyn_copilottranscripts](#BKMK_msdyn_purchaseorder_msdyn_copilottranscripts)
- [msdyn_purchaseorder_msdyn_ocliveworkitems](#BKMK_msdyn_purchaseorder_msdyn_ocliveworkitems)
- [msdyn_purchaseorder_msdyn_ocsessions](#BKMK_msdyn_purchaseorder_msdyn_ocsessions)
- [msdyn_purchaseorder_msfp_alerts](#BKMK_msdyn_purchaseorder_msfp_alerts)
- [msdyn_purchaseorder_msfp_surveyinvites](#BKMK_msdyn_purchaseorder_msfp_surveyinvites)
- [msdyn_purchaseorder_msfp_surveyresponses](#BKMK_msdyn_purchaseorder_msfp_surveyresponses)
- [msdyn_purchaseorder_PhoneCalls](#BKMK_msdyn_purchaseorder_PhoneCalls)
- [msdyn_purchaseorder_PrincipalObjectAttributeAccesses](#BKMK_msdyn_purchaseorder_PrincipalObjectAttributeAccesses)
- [msdyn_purchaseorder_ProcessSession](#BKMK_msdyn_purchaseorder_ProcessSession)
- [msdyn_purchaseorder_RecurringAppointmentMasters](#BKMK_msdyn_purchaseorder_RecurringAppointmentMasters)
- [msdyn_purchaseorder_ServiceAppointments](#BKMK_msdyn_purchaseorder_ServiceAppointments)
- [msdyn_purchaseorder_SharePointDocumentLocations](#BKMK_msdyn_purchaseorder_SharePointDocumentLocations)
- [msdyn_purchaseorder_SocialActivities](#BKMK_msdyn_purchaseorder_SocialActivities)
- [msdyn_purchaseorder_SyncErrors](#BKMK_msdyn_purchaseorder_SyncErrors)
- [msdyn_purchaseorder_Tasks](#BKMK_msdyn_purchaseorder_Tasks)

### <a name="BKMK_bpf_msdyn_purchaseorder_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799"></a> bpf_msdyn_purchaseorder_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799

Many-To-One Relationship: [msdyn_bpf_2c5fe86acc8b414b8322ae571000c799 bpf_msdyn_purchaseorder_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799](msdyn_bpf_2c5fe86acc8b414b8322ae571000c799.md#BKMK_bpf_msdyn_purchaseorder_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bpf_2c5fe86acc8b414b8322ae571000c799`|
|ReferencingAttribute|`bpf_msdyn_purchaseorderid`|
|ReferencedEntityNavigationPropertyName|`bpf_msdyn_purchaseorder_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: msdyn_purchaseorder<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderbill_PurchaseOrder"></a> msdyn_msdyn_purchaseorder_msdyn_purchaseorderbill_PurchaseOrder

Many-To-One Relationship: [msdyn_purchaseorderbill msdyn_msdyn_purchaseorder_msdyn_purchaseorderbill_PurchaseOrder](msdyn_purchaseorderbill.md#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderbill_PurchaseOrder)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_purchaseorderbill`|
|ReferencingAttribute|`msdyn_purchaseorder`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_purchaseorder_msdyn_purchaseorderbill_PurchaseOrder`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder"></a> msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder

Many-To-One Relationship: [msdyn_purchaseorderproduct msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder](msdyn_purchaseorderproduct.md#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_purchaseorderproduct`|
|ReferencingAttribute|`msdyn_purchaseorder`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_purchaseorder_msdyn_purchaseorderproduct_PurchaseOrder`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: Purchase Order<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceipt_PurchaseOrder"></a> msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceipt_PurchaseOrder

Many-To-One Relationship: [msdyn_purchaseorderreceipt msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceipt_PurchaseOrder](msdyn_purchaseorderreceipt.md#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceipt_PurchaseOrder)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_purchaseorderreceipt`|
|ReferencingAttribute|`msdyn_purchaseorder`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceipt_PurchaseOrder`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceiptproduct_PurchaseOrder"></a> msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceiptproduct_PurchaseOrder

Many-To-One Relationship: [msdyn_purchaseorderreceiptproduct msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceiptproduct_PurchaseOrder](msdyn_purchaseorderreceiptproduct.md#BKMK_msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceiptproduct_PurchaseOrder)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_purchaseorderreceiptproduct`|
|ReferencingAttribute|`msdyn_purchaseorder`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_purchaseorder_msdyn_purchaseorderreceiptproduct_PurchaseOrder`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_purchaseorder_msdyn_rtv_OriginalPO"></a> msdyn_msdyn_purchaseorder_msdyn_rtv_OriginalPO

Many-To-One Relationship: [msdyn_rtv msdyn_msdyn_purchaseorder_msdyn_rtv_OriginalPO](msdyn_rtv.md#BKMK_msdyn_msdyn_purchaseorder_msdyn_rtv_OriginalPO)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_rtv`|
|ReferencingAttribute|`msdyn_originalpurchaseorder`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_purchaseorder_msdyn_rtv_OriginalPO`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: Original Purchase Order<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_ActivityPointers"></a> msdyn_purchaseorder_ActivityPointers

Many-To-One Relationship: [activitypointer msdyn_purchaseorder_ActivityPointers](activitypointer.md#BKMK_msdyn_purchaseorder_ActivityPointers)

|Property|Value|
|---|---|
|ReferencingEntity|`activitypointer`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_ActivityPointers`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_adx_inviteredemptions"></a> msdyn_purchaseorder_adx_inviteredemptions

Many-To-One Relationship: [adx_inviteredemption msdyn_purchaseorder_adx_inviteredemptions](adx_inviteredemption.md#BKMK_msdyn_purchaseorder_adx_inviteredemptions)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_inviteredemption`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_adx_inviteredemptions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_adx_portalcomments"></a> msdyn_purchaseorder_adx_portalcomments

Many-To-One Relationship: [adx_portalcomment msdyn_purchaseorder_adx_portalcomments](adx_portalcomment.md#BKMK_msdyn_purchaseorder_adx_portalcomments)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_portalcomment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_adx_portalcomments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_Annotations"></a> msdyn_purchaseorder_Annotations

Many-To-One Relationship: [annotation msdyn_purchaseorder_Annotations](annotation.md#BKMK_msdyn_purchaseorder_Annotations)

|Property|Value|
|---|---|
|ReferencingEntity|`annotation`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_Annotations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_Appointments"></a> msdyn_purchaseorder_Appointments

Many-To-One Relationship: [appointment msdyn_purchaseorder_Appointments](appointment.md#BKMK_msdyn_purchaseorder_Appointments)

|Property|Value|
|---|---|
|ReferencingEntity|`appointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_Appointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_AsyncOperations"></a> msdyn_purchaseorder_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_purchaseorder_AsyncOperations](asyncoperation.md#BKMK_msdyn_purchaseorder_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_BulkDeleteFailures"></a> msdyn_purchaseorder_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_purchaseorder_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_purchaseorder_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_chats"></a> msdyn_purchaseorder_chats

Many-To-One Relationship: [chat msdyn_purchaseorder_chats](chat.md#BKMK_msdyn_purchaseorder_chats)

|Property|Value|
|---|---|
|ReferencingEntity|`chat`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_chats`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_connections1"></a> msdyn_purchaseorder_connections1

Many-To-One Relationship: [connection msdyn_purchaseorder_connections1](connection.md#BKMK_msdyn_purchaseorder_connections1)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record1id`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_connections1`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 100<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_connections2"></a> msdyn_purchaseorder_connections2

Many-To-One Relationship: [connection msdyn_purchaseorder_connections2](connection.md#BKMK_msdyn_purchaseorder_connections2)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record2id`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_connections2`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_DuplicateBaseRecord"></a> msdyn_purchaseorder_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_purchaseorder_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_purchaseorder_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_DuplicateMatchingRecord"></a> msdyn_purchaseorder_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_purchaseorder_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_purchaseorder_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_Emails"></a> msdyn_purchaseorder_Emails

Many-To-One Relationship: [email msdyn_purchaseorder_Emails](email.md#BKMK_msdyn_purchaseorder_Emails)

|Property|Value|
|---|---|
|ReferencingEntity|`email`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_Emails`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_Faxes"></a> msdyn_purchaseorder_Faxes

Many-To-One Relationship: [fax msdyn_purchaseorder_Faxes](fax.md#BKMK_msdyn_purchaseorder_Faxes)

|Property|Value|
|---|---|
|ReferencingEntity|`fax`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_Faxes`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_Letters"></a> msdyn_purchaseorder_Letters

Many-To-One Relationship: [letter msdyn_purchaseorder_Letters](letter.md#BKMK_msdyn_purchaseorder_Letters)

|Property|Value|
|---|---|
|ReferencingEntity|`letter`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_Letters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_MailboxTrackingFolders"></a> msdyn_purchaseorder_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_purchaseorder_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_purchaseorder_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_msdyn_bookingalerts"></a> msdyn_purchaseorder_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert msdyn_purchaseorder_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_msdyn_purchaseorder_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_msdyn_copilottranscripts"></a> msdyn_purchaseorder_msdyn_copilottranscripts

Many-To-One Relationship: [msdyn_copilottranscript msdyn_purchaseorder_msdyn_copilottranscripts](msdyn_copilottranscript.md#BKMK_msdyn_purchaseorder_msdyn_copilottranscripts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_copilottranscript`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_msdyn_copilottranscripts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_msdyn_ocliveworkitems"></a> msdyn_purchaseorder_msdyn_ocliveworkitems

Many-To-One Relationship: [msdyn_ocliveworkitem msdyn_purchaseorder_msdyn_ocliveworkitems](msdyn_ocliveworkitem.md#BKMK_msdyn_purchaseorder_msdyn_ocliveworkitems)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocliveworkitem`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_msdyn_ocliveworkitems`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_msdyn_ocsessions"></a> msdyn_purchaseorder_msdyn_ocsessions

Many-To-One Relationship: [msdyn_ocsession msdyn_purchaseorder_msdyn_ocsessions](msdyn_ocsession.md#BKMK_msdyn_purchaseorder_msdyn_ocsessions)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_msdyn_ocsessions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_msfp_alerts"></a> msdyn_purchaseorder_msfp_alerts

Many-To-One Relationship: [msfp_alert msdyn_purchaseorder_msfp_alerts](msfp_alert.md#BKMK_msdyn_purchaseorder_msfp_alerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_alert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_msfp_alerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_msfp_surveyinvites"></a> msdyn_purchaseorder_msfp_surveyinvites

Many-To-One Relationship: [msfp_surveyinvite msdyn_purchaseorder_msfp_surveyinvites](msfp_surveyinvite.md#BKMK_msdyn_purchaseorder_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyinvite`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_msfp_surveyinvites`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_msfp_surveyresponses"></a> msdyn_purchaseorder_msfp_surveyresponses

Many-To-One Relationship: [msfp_surveyresponse msdyn_purchaseorder_msfp_surveyresponses](msfp_surveyresponse.md#BKMK_msdyn_purchaseorder_msfp_surveyresponses)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyresponse`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_msfp_surveyresponses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_PhoneCalls"></a> msdyn_purchaseorder_PhoneCalls

Many-To-One Relationship: [phonecall msdyn_purchaseorder_PhoneCalls](phonecall.md#BKMK_msdyn_purchaseorder_PhoneCalls)

|Property|Value|
|---|---|
|ReferencingEntity|`phonecall`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_PhoneCalls`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_PrincipalObjectAttributeAccesses"></a> msdyn_purchaseorder_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_purchaseorder_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_purchaseorder_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_ProcessSession"></a> msdyn_purchaseorder_ProcessSession

Many-To-One Relationship: [processsession msdyn_purchaseorder_ProcessSession](processsession.md#BKMK_msdyn_purchaseorder_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_RecurringAppointmentMasters"></a> msdyn_purchaseorder_RecurringAppointmentMasters

Many-To-One Relationship: [recurringappointmentmaster msdyn_purchaseorder_RecurringAppointmentMasters](recurringappointmentmaster.md#BKMK_msdyn_purchaseorder_RecurringAppointmentMasters)

|Property|Value|
|---|---|
|ReferencingEntity|`recurringappointmentmaster`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_RecurringAppointmentMasters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_ServiceAppointments"></a> msdyn_purchaseorder_ServiceAppointments

Many-To-One Relationship: [serviceappointment msdyn_purchaseorder_ServiceAppointments](serviceappointment.md#BKMK_msdyn_purchaseorder_ServiceAppointments)

|Property|Value|
|---|---|
|ReferencingEntity|`serviceappointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_ServiceAppointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_SharePointDocumentLocations"></a> msdyn_purchaseorder_SharePointDocumentLocations

Many-To-One Relationship: [sharepointdocumentlocation msdyn_purchaseorder_SharePointDocumentLocations](sharepointdocumentlocation.md#BKMK_msdyn_purchaseorder_SharePointDocumentLocations)

|Property|Value|
|---|---|
|ReferencingEntity|`sharepointdocumentlocation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_SharePointDocumentLocations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_SocialActivities"></a> msdyn_purchaseorder_SocialActivities

Many-To-One Relationship: [socialactivity msdyn_purchaseorder_SocialActivities](socialactivity.md#BKMK_msdyn_purchaseorder_SocialActivities)

|Property|Value|
|---|---|
|ReferencingEntity|`socialactivity`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_SocialActivities`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_SyncErrors"></a> msdyn_purchaseorder_SyncErrors

Many-To-One Relationship: [syncerror msdyn_purchaseorder_SyncErrors](syncerror.md#BKMK_msdyn_purchaseorder_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_purchaseorder_Tasks"></a> msdyn_purchaseorder_Tasks

Many-To-One Relationship: [task msdyn_purchaseorder_Tasks](task.md#BKMK_msdyn_purchaseorder_Tasks)

|Property|Value|
|---|---|
|ReferencingEntity|`task`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_purchaseorder_Tasks`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

