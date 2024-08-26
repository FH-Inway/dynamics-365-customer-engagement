---
title: "Quote table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Quote table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Quote table/entity reference (Microsoft Dynamics 365 Field Service)

Formal offer for products and/or services, proposed at specific prices and related payment terms, which is sent to a prospective customer.

> [!NOTE]
> The Microsoft Dynamics 365 Field Service Quote table extends the [Microsoft Dynamics 365 Quote table](/dynamics365/developer/entities/quote).



## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [msdyn_Account](#BKMK_msdyn_Account)
- [msdyn_EstimatedCost](#BKMK_msdyn_EstimatedCost)
- [msdyn_InvoiceSetupTotals](#BKMK_msdyn_InvoiceSetupTotals)
- [msdyn_OrderType](#BKMK_msdyn_OrderType)
- [msdyn_QuoteLineEndDate](#BKMK_msdyn_QuoteLineEndDate)
- [msdyn_QuoteLineStartDate](#BKMK_msdyn_QuoteLineStartDate)

### <a name="BKMK_msdyn_Account"></a> msdyn_Account

|Property|Value|
|---|---|
|Description|**Customer Account associated with this Quote**|
|DisplayName|**Potential Customer**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_account`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|account|

### <a name="BKMK_msdyn_EstimatedCost"></a> msdyn_EstimatedCost

|Property|Value|
|---|---|
|Description|**The estimated cost of this quote**|
|DisplayName|**Estimated Cost**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_estimatedcost`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_InvoiceSetupTotals"></a> msdyn_InvoiceSetupTotals

|Property|Value|
|---|---|
|Description|**The totals of all assigned Invoice Setups**|
|DisplayName|**Invoice Setup Totals**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_invoicesetuptotals`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|0|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_OrderType"></a> msdyn_OrderType

|Property|Value|
|---|---|
|Description|**Internal use only.**|
|DisplayName|**Order Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_ordertype`|
|RequiredLevel|Recommended|
|Type|Picklist|
|DefaultFormValue|192350000|
|GlobalChoiceName|`msdyn_quote_msdyn_ordertype`|

#### msdyn_OrderType Choices/Options

|Value|Label|
|---|---|
|192350000|**Item based**|
|690970002|**Service-Maintenance Based**|

### <a name="BKMK_msdyn_QuoteLineEndDate"></a> msdyn_QuoteLineEndDate

|Property|Value|
|---|---|
|Description|**The latest end date of all associated quote lines**|
|DisplayName|**Latest Quote Line End Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_quotelineenddate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_QuoteLineStartDate"></a> msdyn_QuoteLineStartDate

|Property|Value|
|---|---|
|Description|**The earliest Start Date of all Quote Lines that are associated to this quote**|
|DisplayName|**Earliest Quote Line Start Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_quotelinestartdate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|


## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** and **IsValidForUpdate**. Listed by **SchemaName**.

- [msdyn_estimatedcost_Base](#BKMK_msdyn_estimatedcost_Base)
- [msdyn_EstimatedQuoteMargin](#BKMK_msdyn_EstimatedQuoteMargin)
- [msdyn_invoicesetuptotals_Base](#BKMK_msdyn_invoicesetuptotals_Base)
- [msdyn_TotalAmount](#BKMK_msdyn_TotalAmount)
- [msdyn_totalamount_Base](#BKMK_msdyn_totalamount_Base)

### <a name="BKMK_msdyn_estimatedcost_Base"></a> msdyn_estimatedcost_Base

|Property|Value|
|---|---|
|Description|**Value of the Estimated Cost in base currency.**|
|DisplayName|**Estimated Cost (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_estimatedcost_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_EstimatedQuoteMargin"></a> msdyn_EstimatedQuoteMargin

|Property|Value|
|---|---|
|Description|**Estimated Margin of this quote**|
|DisplayName|**Estimated Margin**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_estimatedquotemargin`|
|RequiredLevel|None|
|Type|Decimal|
|ImeMode|Auto|
|MaxValue|100000000000|
|MinValue|-100000000000|
|Precision|2|
|SourceTypeMask|8|

### <a name="BKMK_msdyn_invoicesetuptotals_Base"></a> msdyn_invoicesetuptotals_Base

|Property|Value|
|---|---|
|Description|**Value of the Invoice Setup Totals in base currency.**|
|DisplayName|**Invoice Setup Totals (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_invoicesetuptotals_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_TotalAmount"></a> msdyn_TotalAmount

|Property|Value|
|---|---|
|Description||
|DisplayName|**TotalAmount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_totalamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Auto|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_msdyn_totalamount_Base"></a> msdyn_totalamount_Base

|Property|Value|
|---|---|
|Description|**Value of the TotalAmount in base currency.**|
|DisplayName|**TotalAmount (Base)**|
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
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [msdyn_account_quote_Account](#BKMK_msdyn_account_quote_Account)
- [transactioncurrency_quote](#BKMK_transactioncurrency_quote)

### <a name="BKMK_msdyn_account_quote_Account"></a> msdyn_account_quote_Account

One-To-Many Relationship: [account msdyn_account_quote_Account](account.md#BKMK_msdyn_account_quote_Account)

|Property|Value|
|---|---|
|ReferencedEntity|`account`|
|ReferencedAttribute|`accountid`|
|ReferencingAttribute|`msdyn_account`|
|ReferencingEntityNavigationPropertyName|`msdyn_account`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `Cascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_transactioncurrency_quote"></a> transactioncurrency_quote

One-To-Many Relationship: [transactioncurrency transactioncurrency_quote](transactioncurrency.md#BKMK_transactioncurrency_quote)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_quote_msdyn_quotebookingincident_Quote](#BKMK_msdyn_quote_msdyn_quotebookingincident_Quote)
- [msdyn_quote_msdyn_quotebookingproduct_Quote](#BKMK_msdyn_quote_msdyn_quotebookingproduct_Quote)
- [msdyn_quote_msdyn_quotebookingservice_Quote](#BKMK_msdyn_quote_msdyn_quotebookingservice_Quote)
- [msdyn_quote_msdyn_quotebookingservicetask_Quote](#BKMK_msdyn_quote_msdyn_quotebookingservicetask_Quote)
- [msdyn_quote_msdyn_quotebookingsetup_Quote](#BKMK_msdyn_quote_msdyn_quotebookingsetup_Quote)
- [msdyn_quote_msdyn_quoteinvoicingsetup_Quote](#BKMK_msdyn_quote_msdyn_quoteinvoicingsetup_Quote)
- [quote_msdyn_bookingalerts](#BKMK_quote_msdyn_bookingalerts)

### <a name="BKMK_msdyn_quote_msdyn_quotebookingincident_Quote"></a> msdyn_quote_msdyn_quotebookingincident_Quote

Many-To-One Relationship: [msdyn_quotebookingincident msdyn_quote_msdyn_quotebookingincident_Quote](msdyn_quotebookingincident.md#BKMK_msdyn_quote_msdyn_quotebookingincident_Quote)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_quotebookingincident`|
|ReferencingAttribute|`msdyn_quote`|
|ReferencedEntityNavigationPropertyName|`msdyn_quote_msdyn_quotebookingincident_Quote`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_quote_msdyn_quotebookingproduct_Quote"></a> msdyn_quote_msdyn_quotebookingproduct_Quote

Many-To-One Relationship: [msdyn_quotebookingproduct msdyn_quote_msdyn_quotebookingproduct_Quote](msdyn_quotebookingproduct.md#BKMK_msdyn_quote_msdyn_quotebookingproduct_Quote)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_quotebookingproduct`|
|ReferencingAttribute|`msdyn_quote`|
|ReferencedEntityNavigationPropertyName|`msdyn_quote_msdyn_quotebookingproduct_Quote`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_quote_msdyn_quotebookingservice_Quote"></a> msdyn_quote_msdyn_quotebookingservice_Quote

Many-To-One Relationship: [msdyn_quotebookingservice msdyn_quote_msdyn_quotebookingservice_Quote](msdyn_quotebookingservice.md#BKMK_msdyn_quote_msdyn_quotebookingservice_Quote)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_quotebookingservice`|
|ReferencingAttribute|`msdyn_quote`|
|ReferencedEntityNavigationPropertyName|`msdyn_quote_msdyn_quotebookingservice_Quote`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_quote_msdyn_quotebookingservicetask_Quote"></a> msdyn_quote_msdyn_quotebookingservicetask_Quote

Many-To-One Relationship: [msdyn_quotebookingservicetask msdyn_quote_msdyn_quotebookingservicetask_Quote](msdyn_quotebookingservicetask.md#BKMK_msdyn_quote_msdyn_quotebookingservicetask_Quote)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_quotebookingservicetask`|
|ReferencingAttribute|`msdyn_quote`|
|ReferencedEntityNavigationPropertyName|`msdyn_quote_msdyn_quotebookingservicetask_Quote`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_quote_msdyn_quotebookingsetup_Quote"></a> msdyn_quote_msdyn_quotebookingsetup_Quote

Many-To-One Relationship: [msdyn_quotebookingsetup msdyn_quote_msdyn_quotebookingsetup_Quote](msdyn_quotebookingsetup.md#BKMK_msdyn_quote_msdyn_quotebookingsetup_Quote)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_quotebookingsetup`|
|ReferencingAttribute|`msdyn_quote`|
|ReferencedEntityNavigationPropertyName|`msdyn_quote_msdyn_quotebookingsetup_Quote`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_quote_msdyn_quoteinvoicingsetup_Quote"></a> msdyn_quote_msdyn_quoteinvoicingsetup_Quote

Many-To-One Relationship: [msdyn_quoteinvoicingsetup msdyn_quote_msdyn_quoteinvoicingsetup_Quote](msdyn_quoteinvoicingsetup.md#BKMK_msdyn_quote_msdyn_quoteinvoicingsetup_Quote)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_quoteinvoicingsetup`|
|ReferencingAttribute|`msdyn_quote`|
|ReferencedEntityNavigationPropertyName|`msdyn_quote_msdyn_quoteinvoicingsetup_Quote`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_quote_msdyn_bookingalerts"></a> quote_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert quote_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_quote_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`quote_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

