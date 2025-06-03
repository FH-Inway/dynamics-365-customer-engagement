---
title: "Actual (msdyn_actual) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Actual (msdyn_actual) table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Actual (msdyn_actual) table/entity reference (Microsoft Dynamics 365 Customer Service)



## Messages

The following table lists the messages for the Actual (msdyn_actual) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_actuals(*msdyn_actualid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Associate`<br />Event: True |[Associate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Associate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-associate-method-or-associaterequest)|
| `BulkRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Create`<br />Event: True |`POST` /msdyn_actuals<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_actuals(*msdyn_actualid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Disassociate`<br />Event: True |[Disassociate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Disassociate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-disassociate-method-or-disassociaterequest)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `PurgeRetainedContent`<br />Event: True |<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_actuals(*msdyn_actualid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_actuals<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `RollbackRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `SetState`<br />Event: True |`PATCH` /msdyn_actuals(*msdyn_actualid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_actuals(*msdyn_actualid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_actuals(*msdyn_actualid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|
| `ValidateRetentionConfig`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Actual (msdyn_actual) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Actual** |
| **DisplayCollectionName** | **Actuals** |
| **SchemaName** | `msdyn_actual` |
| **CollectionSchemaName** | `msdyn_actuals` |
| **EntitySetName** | `msdyn_actuals`|
| **LogicalName** | `msdyn_actual` |
| **LogicalCollectionName** | `msdyn_actuals` |
| **PrimaryIdAttribute** | `msdyn_actualid` |
| **PrimaryNameAttribute** |`msdyn_description` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_AccountCustomer](#BKMK_msdyn_AccountCustomer)
- [msdyn_AccountingDate](#BKMK_msdyn_AccountingDate)
- [msdyn_AccountVendor](#BKMK_msdyn_AccountVendor)
- [msdyn_actualId](#BKMK_msdyn_actualId)
- [msdyn_AdjustmentStatus](#BKMK_msdyn_AdjustmentStatus)
- [msdyn_Amount](#BKMK_msdyn_Amount)
- [msdyn_AmountMethod](#BKMK_msdyn_AmountMethod)
- [msdyn_BasisAmount](#BKMK_msdyn_BasisAmount)
- [msdyn_BasisPrice](#BKMK_msdyn_BasisPrice)
- [msdyn_BasisQuantity](#BKMK_msdyn_BasisQuantity)
- [msdyn_BillingStatus](#BKMK_msdyn_BillingStatus)
- [msdyn_BillingType](#BKMK_msdyn_BillingType)
- [msdyn_bookableresource](#BKMK_msdyn_bookableresource)
- [msdyn_ContactCustomer](#BKMK_msdyn_ContactCustomer)
- [msdyn_ContactVendor](#BKMK_msdyn_ContactVendor)
- [msdyn_CustomerType](#BKMK_msdyn_CustomerType)
- [msdyn_description](#BKMK_msdyn_description)
- [msdyn_DocumentDate](#BKMK_msdyn_DocumentDate)
- [msdyn_EndDateTime](#BKMK_msdyn_EndDateTime)
- [msdyn_ExchangeRateDate](#BKMK_msdyn_ExchangeRateDate)
- [msdyn_externaldescription](#BKMK_msdyn_externaldescription)
- [msdyn_ExternalReferenceDate](#BKMK_msdyn_ExternalReferenceDate)
- [msdyn_ExternalReferenceID](#BKMK_msdyn_ExternalReferenceID)
- [msdyn_Invoice](#BKMK_msdyn_Invoice)
- [msdyn_IsJournalized](#BKMK_msdyn_IsJournalized)
- [msdyn_Percent](#BKMK_msdyn_Percent)
- [msdyn_Price](#BKMK_msdyn_Price)
- [msdyn_PriceList](#BKMK_msdyn_PriceList)
- [msdyn_Product](#BKMK_msdyn_Product)
- [msdyn_Quantity](#BKMK_msdyn_Quantity)
- [msdyn_SalesContract](#BKMK_msdyn_SalesContract)
- [msdyn_SalesContractLine](#BKMK_msdyn_SalesContractLine)
- [msdyn_StartDateTime](#BKMK_msdyn_StartDateTime)
- [msdyn_TransactionClassification](#BKMK_msdyn_TransactionClassification)
- [msdyn_TransactionTypeCode](#BKMK_msdyn_TransactionTypeCode)
- [msdyn_Unit](#BKMK_msdyn_Unit)
- [msdyn_UnitSchedule](#BKMK_msdyn_UnitSchedule)
- [msdyn_VendorType](#BKMK_msdyn_VendorType)
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
|Description|**Sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_AccountCustomer"></a> msdyn_AccountCustomer

|Property|Value|
|---|---|
|Description|**Select the customer.**|
|DisplayName|**Customer ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_accountcustomer`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|account|

### <a name="BKMK_msdyn_AccountingDate"></a> msdyn_AccountingDate

|Property|Value|
|---|---|
|Description||
|DisplayName|**Accounting Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_accountingdate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_AccountVendor"></a> msdyn_AccountVendor

|Property|Value|
|---|---|
|Description||
|DisplayName|**Vendor**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_accountvendor`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|account|

### <a name="BKMK_msdyn_actualId"></a> msdyn_actualId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Actual**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_actualid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_AdjustmentStatus"></a> msdyn_AdjustmentStatus

|Property|Value|
|---|---|
|Description|**Shows the adjustment status ID of the transaction.**|
|DisplayName|**Adjustment Status ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_adjustmentstatus`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_adjustmentstatus`|

#### msdyn_AdjustmentStatus Choices/Options

|Value|Label|
|---|---|
|192350000|**In Process**|
|192350001|**Adjusted**|
|192350002|**Unadjustable**|

### <a name="BKMK_msdyn_Amount"></a> msdyn_Amount

|Property|Value|
|---|---|
|Description|**Enter the amount in transaction currency.**|
|DisplayName|**Amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_amount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|1000000000|
|MinValue|-1000000000|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_AmountMethod"></a> msdyn_AmountMethod

|Property|Value|
|---|---|
|Description|**Select the method by which the amount was computed.**|
|DisplayName|**Amount Method ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_amountmethod`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|192350000|
|GlobalChoiceName|`msdyn_amountmethod`|

#### msdyn_AmountMethod Choices/Options

|Value|Label|
|---|---|
|192350000|**Multiply Quantity By Price**|
|192350001|**Fixed Price**|
|192350002|**Multiply Basis Quantity By Price**|
|192350003|**Multiply Basis Amount By Percent**|

### <a name="BKMK_msdyn_BasisAmount"></a> msdyn_BasisAmount

|Property|Value|
|---|---|
|Description|**Enter the cost amount of the sales transaction in the transaction currency.**|
|DisplayName|**Basis Amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_basisamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|1000000000|
|MinValue|-1000000000|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_BasisPrice"></a> msdyn_BasisPrice

|Property|Value|
|---|---|
|Description|**Enter the cost price of the sales transaction in transaction currency.**|
|DisplayName|**Basis Price**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_basisprice`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|1000000000|
|MinValue|-1000000000|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_BasisQuantity"></a> msdyn_BasisQuantity

|Property|Value|
|---|---|
|Description|**Enter the cost quantity of the sales transaction in the base (organization) currency.**|
|DisplayName|**Basis Quantity**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_basisquantity`|
|RequiredLevel|None|
|Type|Decimal|
|ImeMode|Auto|
|MaxValue|1000000000|
|MinValue|-1000000000|
|Precision|2|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_BillingStatus"></a> msdyn_BillingStatus

|Property|Value|
|---|---|
|Description|**Select the billing status ID.**|
|DisplayName|**Billing status ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_billingstatus`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_billingstatus`|

#### msdyn_BillingStatus Choices/Options

|Value|Label|
|---|---|
|192350000|**Unbilled Sales Created**|
|192350001|**Customer Invoice Created**|
|192350002|**Customer Invoice Posted**|
|192350003|**Canceled**|

### <a name="BKMK_msdyn_BillingType"></a> msdyn_BillingType

|Property|Value|
|---|---|
|Description|**Select the billing type ID.**|
|DisplayName|**Billing type ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_billingtype`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_billingtype`|

#### msdyn_BillingType Choices/Options

|Value|Label|
|---|---|
|192350000|**Non Chargeable**|
|192350001|**Chargeable**|
|192350002|**Complimentary**|
|192350003|**Not Available**|

### <a name="BKMK_msdyn_bookableresource"></a> msdyn_bookableresource

|Property|Value|
|---|---|
|Description|**Shows the bookable resource for which the actual is recorded.**|
|DisplayName|**Bookable Resource**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_bookableresource`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|bookableresource|

### <a name="BKMK_msdyn_ContactCustomer"></a> msdyn_ContactCustomer

|Property|Value|
|---|---|
|Description|**Select the customer contact.**|
|DisplayName|**Customer contact ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_contactcustomer`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|contact|

### <a name="BKMK_msdyn_ContactVendor"></a> msdyn_ContactVendor

|Property|Value|
|---|---|
|Description||
|DisplayName|**Vendor**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_contactvendor`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|contact|

### <a name="BKMK_msdyn_CustomerType"></a> msdyn_CustomerType

|Property|Value|
|---|---|
|Description|**Select the customer type ID.**|
|DisplayName|**Customer type ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_customertype`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|192350001|
|GlobalChoiceName|`msdyn_partytype`|

#### msdyn_CustomerType Choices/Options

|Value|Label|
|---|---|
|192350001|**Account**|
|192350002|**Contact**|

### <a name="BKMK_msdyn_description"></a> msdyn_description

|Property|Value|
|---|---|
|Description|**Type the record description.**|
|DisplayName|**Description**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_description`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|200|

### <a name="BKMK_msdyn_DocumentDate"></a> msdyn_DocumentDate

|Property|Value|
|---|---|
|Description|**Enter the transaction date of the business event.**|
|DisplayName|**Document Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_documentdate`|
|RequiredLevel|ApplicationRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_EndDateTime"></a> msdyn_EndDateTime

|Property|Value|
|---|---|
|Description|**Enter the end date and time for this transaction.**|
|DisplayName|**End Date/Time**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_enddatetime`|
|RequiredLevel|ApplicationRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_ExchangeRateDate"></a> msdyn_ExchangeRateDate

|Property|Value|
|---|---|
|Description|**Enter the date of the exchange rate used for this transaction.**|
|DisplayName|**Exchange Rate Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_exchangeratedate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_externaldescription"></a> msdyn_externaldescription

|Property|Value|
|---|---|
|Description|**The external description of the business transaction.**|
|DisplayName|**External Description**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_externaldescription`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|200|

### <a name="BKMK_msdyn_ExternalReferenceDate"></a> msdyn_ExternalReferenceDate

|Property|Value|
|---|---|
|Description|**Stores a date from an external system, such as a journal entry voucher date from an ERP system**|
|DisplayName|**External Reference Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_externalreferencedate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_ExternalReferenceID"></a> msdyn_ExternalReferenceID

|Property|Value|
|---|---|
|Description|**Stores an ID from an external system, such as the journal entry voucher number from an ERP system.**|
|DisplayName|**External Reference ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_externalreferenceid`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_Invoice"></a> msdyn_Invoice

|Property|Value|
|---|---|
|Description|**The unique identifier of an invoice.**|
|DisplayName|**Invoice**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_invoice`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|invoice|

### <a name="BKMK_msdyn_IsJournalized"></a> msdyn_IsJournalized

|Property|Value|
|---|---|
|Description||
|DisplayName|**Is Journalized**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_isjournalized`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_actual_msdyn_isjournalized`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_Percent"></a> msdyn_Percent

|Property|Value|
|---|---|
|Description|**Enter the percent.**|
|DisplayName|**Percent**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_percent`|
|RequiredLevel|None|
|Type|Decimal|
|ImeMode|Auto|
|MaxValue|1000000000|
|MinValue|-1000000000|
|Precision|2|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_Price"></a> msdyn_Price

|Property|Value|
|---|---|
|Description|**Enter the price in the transaction currency.**|
|DisplayName|**Price**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_price`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|1000000000|
|MinValue|-1000000000|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_PriceList"></a> msdyn_PriceList

|Property|Value|
|---|---|
|Description|**Select the price list.**|
|DisplayName|**Price list ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_pricelist`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|pricelevel|

### <a name="BKMK_msdyn_Product"></a> msdyn_Product

|Property|Value|
|---|---|
|Description|**Select the product ID.**|
|DisplayName|**Product ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_product`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|product|

### <a name="BKMK_msdyn_Quantity"></a> msdyn_Quantity

|Property|Value|
|---|---|
|Description|**Enter the quantity.**|
|DisplayName|**Quantity**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_quantity`|
|RequiredLevel|None|
|Type|Decimal|
|ImeMode|Auto|
|MaxValue|1000000000|
|MinValue|-1000000000|
|Precision|2|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_SalesContract"></a> msdyn_SalesContract

|Property|Value|
|---|---|
|Description|**Select the project contract.**|
|DisplayName|**Project Contract ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_salescontract`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|salesorder|

### <a name="BKMK_msdyn_SalesContractLine"></a> msdyn_SalesContractLine

|Property|Value|
|---|---|
|Description|**Type the project contract line.**|
|DisplayName|**Project Contract Line**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_salescontractline`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_StartDateTime"></a> msdyn_StartDateTime

|Property|Value|
|---|---|
|Description|**Enter the start date and time.**|
|DisplayName|**Start Date/Time**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_startdatetime`|
|RequiredLevel|ApplicationRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_TransactionClassification"></a> msdyn_TransactionClassification

|Property|Value|
|---|---|
|Description|**Shows the transaction classification of this transaction.**|
|DisplayName|**Transaction Class**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_transactionclassification`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_transactionclassification`|

#### msdyn_TransactionClassification Choices/Options

|Value|Label|
|---|---|
|192350000|**Time**|
|192350001|**Expense**|
|192350002|**Material**|
|192350003|**Milestone**|
|192350004|**Fee**|

### <a name="BKMK_msdyn_TransactionTypeCode"></a> msdyn_TransactionTypeCode

|Property|Value|
|---|---|
|Description|**Shows the transaction type of this transaction.**|
|DisplayName|**Transaction Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_transactiontypecode`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`msdyn_transactiontypecode`|

#### msdyn_TransactionTypeCode Choices/Options

|Value|Label|
|---|---|
|192350000|**Cost**|
|192350004|**Project Contract**|
|192350005|**Unbilled Sales**|
|192350006|**Billed Sales**|
|192350007|**Resourcing Unit Cost**|
|192350008|**Inter-Organizational Sales**|

### <a name="BKMK_msdyn_Unit"></a> msdyn_Unit

|Property|Value|
|---|---|
|Description|**Select the unit of measure.**|
|DisplayName|**Unit of measure**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unit`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|uom|

### <a name="BKMK_msdyn_UnitSchedule"></a> msdyn_UnitSchedule

|Property|Value|
|---|---|
|Description|**Select the unit schedule.**|
|DisplayName|**Unit Schedule**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_unitschedule`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|uomschedule|

### <a name="BKMK_msdyn_VendorType"></a> msdyn_VendorType

|Property|Value|
|---|---|
|Description||
|DisplayName|**Vendor Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_vendortype`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|192350001|
|GlobalChoiceName|`msdyn_partytype`|

#### msdyn_VendorType Choices/Options

|Value|Label|
|---|---|
|192350001|**Account**|
|192350002|**Contact**|

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
|Description|**Status of the Actual**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_actual_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Actual**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_actual_statuscode`|

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
|Description|**Shows the currency associated with the entity.**|
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
- [ExchangeRate](#BKMK_ExchangeRate)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [msdyn_amount_Base](#BKMK_msdyn_amount_Base)
- [msdyn_basisamount_Base](#BKMK_msdyn_basisamount_Base)
- [msdyn_basisprice_Base](#BKMK_msdyn_basisprice_Base)
- [msdyn_price_Base](#BKMK_msdyn_price_Base)
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

### <a name="BKMK_ExchangeRate"></a> ExchangeRate

|Property|Value|
|---|---|
|Description|**Exchange rate for the currency associated with the entity with respect to the base currency.**|
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

### <a name="BKMK_msdyn_amount_Base"></a> msdyn_amount_Base

|Property|Value|
|---|---|
|Description|**Enter the value of the amount in the base (organization) currency.**|
|DisplayName|**Amount (Base currency)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_amount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_basisamount_Base"></a> msdyn_basisamount_Base

|Property|Value|
|---|---|
|Description|**Enter the cost amount of the sales transaction in the base (organization) currency.**|
|DisplayName|**Basis Amount (Base currency)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_basisamount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_basisprice_Base"></a> msdyn_basisprice_Base

|Property|Value|
|---|---|
|Description|**Enter the cost price of the sales transaction in base (organization) currency.**|
|DisplayName|**Basis Price (Base currency)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_basisprice_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_price_Base"></a> msdyn_price_Base

|Property|Value|
|---|---|
|Description|**Enter the price in the base (organization) currency.**|
|DisplayName|**Price (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_price_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

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

- [business_unit_msdyn_actual](#BKMK_business_unit_msdyn_actual)
- [lk_msdyn_actual_createdby](#BKMK_lk_msdyn_actual_createdby)
- [lk_msdyn_actual_createdonbehalfby](#BKMK_lk_msdyn_actual_createdonbehalfby)
- [lk_msdyn_actual_modifiedby](#BKMK_lk_msdyn_actual_modifiedby)
- [lk_msdyn_actual_modifiedonbehalfby](#BKMK_lk_msdyn_actual_modifiedonbehalfby)
- [msdyn_account_msdyn_actual_AccountCustomer](#BKMK_msdyn_account_msdyn_actual_AccountCustomer)
- [msdyn_account_msdyn_actual_AccountVendor](#BKMK_msdyn_account_msdyn_actual_AccountVendor)
- [msdyn_bookableresource_msdyn_actual_bookableresource](#BKMK_msdyn_bookableresource_msdyn_actual_bookableresource)
- [msdyn_contact_msdyn_actual_ContactCustomer](#BKMK_msdyn_contact_msdyn_actual_ContactCustomer)
- [msdyn_contact_msdyn_actual_ContactVendor](#BKMK_msdyn_contact_msdyn_actual_ContactVendor)
- [msdyn_invoice_msdyn_actual_Invoice](#BKMK_msdyn_invoice_msdyn_actual_Invoice)
- [msdyn_pricelevel_msdyn_actual_PriceList](#BKMK_msdyn_pricelevel_msdyn_actual_PriceList)
- [msdyn_product_msdyn_actual_Product](#BKMK_msdyn_product_msdyn_actual_Product)
- [msdyn_salesorder_msdyn_actual_SalesContract](#BKMK_msdyn_salesorder_msdyn_actual_SalesContract)
- [msdyn_uom_msdyn_actual_Unit](#BKMK_msdyn_uom_msdyn_actual_Unit)
- [msdyn_uomschedule_msdyn_actual_UnitSchedule](#BKMK_msdyn_uomschedule_msdyn_actual_UnitSchedule)
- [owner_msdyn_actual](#BKMK_owner_msdyn_actual)
- [team_msdyn_actual](#BKMK_team_msdyn_actual)
- [TransactionCurrency_msdyn_actual](#BKMK_TransactionCurrency_msdyn_actual)
- [user_msdyn_actual](#BKMK_user_msdyn_actual)

### <a name="BKMK_business_unit_msdyn_actual"></a> business_unit_msdyn_actual

One-To-Many Relationship: [businessunit business_unit_msdyn_actual](businessunit.md#BKMK_business_unit_msdyn_actual)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_actual_createdby"></a> lk_msdyn_actual_createdby

One-To-Many Relationship: [systemuser lk_msdyn_actual_createdby](systemuser.md#BKMK_lk_msdyn_actual_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_actual_createdonbehalfby"></a> lk_msdyn_actual_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_actual_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_actual_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_actual_modifiedby"></a> lk_msdyn_actual_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_actual_modifiedby](systemuser.md#BKMK_lk_msdyn_actual_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_actual_modifiedonbehalfby"></a> lk_msdyn_actual_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_actual_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_actual_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_account_msdyn_actual_AccountCustomer"></a> msdyn_account_msdyn_actual_AccountCustomer

One-To-Many Relationship: [account msdyn_account_msdyn_actual_AccountCustomer](account.md#BKMK_msdyn_account_msdyn_actual_AccountCustomer)

|Property|Value|
|---|---|
|ReferencedEntity|`account`|
|ReferencedAttribute|`accountid`|
|ReferencingAttribute|`msdyn_accountcustomer`|
|ReferencingEntityNavigationPropertyName|`msdyn_AccountCustomer`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `Cascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_account_msdyn_actual_AccountVendor"></a> msdyn_account_msdyn_actual_AccountVendor

One-To-Many Relationship: [account msdyn_account_msdyn_actual_AccountVendor](account.md#BKMK_msdyn_account_msdyn_actual_AccountVendor)

|Property|Value|
|---|---|
|ReferencedEntity|`account`|
|ReferencedAttribute|`accountid`|
|ReferencingAttribute|`msdyn_accountvendor`|
|ReferencingEntityNavigationPropertyName|`msdyn_AccountVendor`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `Cascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_bookableresource_msdyn_actual_bookableresource"></a> msdyn_bookableresource_msdyn_actual_bookableresource

One-To-Many Relationship: [bookableresource msdyn_bookableresource_msdyn_actual_bookableresource](bookableresource.md#BKMK_msdyn_bookableresource_msdyn_actual_bookableresource)

|Property|Value|
|---|---|
|ReferencedEntity|`bookableresource`|
|ReferencedAttribute|`bookableresourceid`|
|ReferencingAttribute|`msdyn_bookableresource`|
|ReferencingEntityNavigationPropertyName|`msdyn_bookableresource`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_contact_msdyn_actual_ContactCustomer"></a> msdyn_contact_msdyn_actual_ContactCustomer

One-To-Many Relationship: [contact msdyn_contact_msdyn_actual_ContactCustomer](contact.md#BKMK_msdyn_contact_msdyn_actual_ContactCustomer)

|Property|Value|
|---|---|
|ReferencedEntity|`contact`|
|ReferencedAttribute|`contactid`|
|ReferencingAttribute|`msdyn_contactcustomer`|
|ReferencingEntityNavigationPropertyName|`msdyn_ContactCustomer`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `Cascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_contact_msdyn_actual_ContactVendor"></a> msdyn_contact_msdyn_actual_ContactVendor

One-To-Many Relationship: [contact msdyn_contact_msdyn_actual_ContactVendor](contact.md#BKMK_msdyn_contact_msdyn_actual_ContactVendor)

|Property|Value|
|---|---|
|ReferencedEntity|`contact`|
|ReferencedAttribute|`contactid`|
|ReferencingAttribute|`msdyn_contactvendor`|
|ReferencingEntityNavigationPropertyName|`msdyn_ContactVendor`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `Cascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_invoice_msdyn_actual_Invoice"></a> msdyn_invoice_msdyn_actual_Invoice

One-To-Many Relationship: [invoice msdyn_invoice_msdyn_actual_Invoice](invoice.md#BKMK_msdyn_invoice_msdyn_actual_Invoice)

|Property|Value|
|---|---|
|ReferencedEntity|`invoice`|
|ReferencedAttribute|`invoiceid`|
|ReferencingAttribute|`msdyn_invoice`|
|ReferencingEntityNavigationPropertyName|`msdyn_Invoice`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_pricelevel_msdyn_actual_PriceList"></a> msdyn_pricelevel_msdyn_actual_PriceList

One-To-Many Relationship: [pricelevel msdyn_pricelevel_msdyn_actual_PriceList](pricelevel.md#BKMK_msdyn_pricelevel_msdyn_actual_PriceList)

|Property|Value|
|---|---|
|ReferencedEntity|`pricelevel`|
|ReferencedAttribute|`pricelevelid`|
|ReferencingAttribute|`msdyn_pricelist`|
|ReferencingEntityNavigationPropertyName|`msdyn_PriceList`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_product_msdyn_actual_Product"></a> msdyn_product_msdyn_actual_Product

One-To-Many Relationship: [product msdyn_product_msdyn_actual_Product](product.md#BKMK_msdyn_product_msdyn_actual_Product)

|Property|Value|
|---|---|
|ReferencedEntity|`product`|
|ReferencedAttribute|`productid`|
|ReferencingAttribute|`msdyn_product`|
|ReferencingEntityNavigationPropertyName|`msdyn_Product`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_salesorder_msdyn_actual_SalesContract"></a> msdyn_salesorder_msdyn_actual_SalesContract

One-To-Many Relationship: [salesorder msdyn_salesorder_msdyn_actual_SalesContract](salesorder.md#BKMK_msdyn_salesorder_msdyn_actual_SalesContract)

|Property|Value|
|---|---|
|ReferencedEntity|`salesorder`|
|ReferencedAttribute|`salesorderid`|
|ReferencingAttribute|`msdyn_salescontract`|
|ReferencingEntityNavigationPropertyName|`msdyn_SalesContract`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_uom_msdyn_actual_Unit"></a> msdyn_uom_msdyn_actual_Unit

One-To-Many Relationship: [uom msdyn_uom_msdyn_actual_Unit](uom.md#BKMK_msdyn_uom_msdyn_actual_Unit)

|Property|Value|
|---|---|
|ReferencedEntity|`uom`|
|ReferencedAttribute|`uomid`|
|ReferencingAttribute|`msdyn_unit`|
|ReferencingEntityNavigationPropertyName|`msdyn_Unit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_uomschedule_msdyn_actual_UnitSchedule"></a> msdyn_uomschedule_msdyn_actual_UnitSchedule

One-To-Many Relationship: [uomschedule msdyn_uomschedule_msdyn_actual_UnitSchedule](uomschedule.md#BKMK_msdyn_uomschedule_msdyn_actual_UnitSchedule)

|Property|Value|
|---|---|
|ReferencedEntity|`uomschedule`|
|ReferencedAttribute|`uomscheduleid`|
|ReferencingAttribute|`msdyn_unitschedule`|
|ReferencingEntityNavigationPropertyName|`msdyn_UnitSchedule`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_actual"></a> owner_msdyn_actual

One-To-Many Relationship: [owner owner_msdyn_actual](owner.md#BKMK_owner_msdyn_actual)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_actual"></a> team_msdyn_actual

One-To-Many Relationship: [team team_msdyn_actual](team.md#BKMK_team_msdyn_actual)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_TransactionCurrency_msdyn_actual"></a> TransactionCurrency_msdyn_actual

One-To-Many Relationship: [transactioncurrency TransactionCurrency_msdyn_actual](transactioncurrency.md#BKMK_TransactionCurrency_msdyn_actual)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_actual"></a> user_msdyn_actual

One-To-Many Relationship: [systemuser user_msdyn_actual](systemuser.md#BKMK_user_msdyn_actual)

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

- [msdyn_actual_Annotations](#BKMK_msdyn_actual_Annotations)
- [msdyn_actual_AsyncOperations](#BKMK_msdyn_actual_AsyncOperations)
- [msdyn_actual_BulkDeleteFailures](#BKMK_msdyn_actual_BulkDeleteFailures)
- [msdyn_actual_DuplicateBaseRecord](#BKMK_msdyn_actual_DuplicateBaseRecord)
- [msdyn_actual_DuplicateMatchingRecord](#BKMK_msdyn_actual_DuplicateMatchingRecord)
- [msdyn_actual_MailboxTrackingFolders](#BKMK_msdyn_actual_MailboxTrackingFolders)
- [msdyn_actual_PrincipalObjectAttributeAccesses](#BKMK_msdyn_actual_PrincipalObjectAttributeAccesses)
- [msdyn_actual_ProcessSession](#BKMK_msdyn_actual_ProcessSession)
- [msdyn_actual_SyncErrors](#BKMK_msdyn_actual_SyncErrors)

### <a name="BKMK_msdyn_actual_Annotations"></a> msdyn_actual_Annotations

Many-To-One Relationship: [annotation msdyn_actual_Annotations](annotation.md#BKMK_msdyn_actual_Annotations)

|Property|Value|
|---|---|
|ReferencingEntity|`annotation`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_Annotations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_AsyncOperations"></a> msdyn_actual_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_actual_AsyncOperations](asyncoperation.md#BKMK_msdyn_actual_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_BulkDeleteFailures"></a> msdyn_actual_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_actual_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_actual_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_DuplicateBaseRecord"></a> msdyn_actual_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_actual_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_actual_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_DuplicateMatchingRecord"></a> msdyn_actual_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_actual_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_actual_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_MailboxTrackingFolders"></a> msdyn_actual_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_actual_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_actual_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_PrincipalObjectAttributeAccesses"></a> msdyn_actual_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_actual_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_actual_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_ProcessSession"></a> msdyn_actual_ProcessSession

Many-To-One Relationship: [processsession msdyn_actual_ProcessSession](processsession.md#BKMK_msdyn_actual_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_actual_SyncErrors"></a> msdyn_actual_SyncErrors

Many-To-One Relationship: [syncerror msdyn_actual_SyncErrors](syncerror.md#BKMK_msdyn_actual_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_actual_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

