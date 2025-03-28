---
title: "Opportunity Product (OpportunityProduct) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Opportunity Product (OpportunityProduct) table/entity with Microsoft Dynamics 365."
ms.topic: generated-reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Opportunity Product (OpportunityProduct) table/entity reference (Microsoft Dynamics 365)

Association between an opportunity and a product.

## Messages

The following table lists the messages for the Opportunity Product (OpportunityProduct) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Associate`<br />Event: True |[Associate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Associate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-associate-method-or-associaterequest)|
| `Create`<br />Event: True |`POST` /opportunityproducts<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /opportunityproducts(*opportunityproductid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Disassociate`<br />Event: True |[Disassociate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Disassociate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-disassociate-method-or-disassociaterequest)|
| `Retrieve`<br />Event: True |`GET` /opportunityproducts(*opportunityproductid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /opportunityproducts<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `Update`<br />Event: True |`PATCH` /opportunityproducts(*opportunityproductid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /opportunityproducts(*opportunityproductid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Opportunity Product (OpportunityProduct) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `CalculatePrice`|<xref:Microsoft.Dynamics.CRM.CalculatePrice?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.CalculatePriceRequest>|

## Properties

The following table lists selected properties for the Opportunity Product (OpportunityProduct) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Opportunity Product** |
| **DisplayCollectionName** | **Opportunity Products** |
| **SchemaName** | `OpportunityProduct` |
| **CollectionSchemaName** | `OpportunityProducts` |
| **EntitySetName** | `opportunityproducts`|
| **LogicalName** | `opportunityproduct` |
| **LogicalCollectionName** | `opportunityproducts` |
| **PrimaryIdAttribute** | `opportunityproductid` |
| **PrimaryNameAttribute** |`opportunityproductname` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [BaseAmount](#BKMK_BaseAmount)
- [Description](#BKMK_Description)
- [EntityImage](#BKMK_EntityImage)
- [ExtendedAmount](#BKMK_ExtendedAmount)
- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsPriceOverridden](#BKMK_IsPriceOverridden)
- [IsProductOverridden](#BKMK_IsProductOverridden)
- [LineItemNumber](#BKMK_LineItemNumber)
- [ManualDiscountAmount](#BKMK_ManualDiscountAmount)
- [OpportunityId](#BKMK_OpportunityId)
- [OpportunityProductId](#BKMK_OpportunityProductId)
- [OpportunityProductName](#BKMK_OpportunityProductName)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [ParentBundleId](#BKMK_ParentBundleId)
- [ParentBundleIdRef](#BKMK_ParentBundleIdRef)
- [PricePerUnit](#BKMK_PricePerUnit)
- [PricingErrorCode](#BKMK_PricingErrorCode)
- [ProductAssociationId](#BKMK_ProductAssociationId)
- [ProductDescription](#BKMK_ProductDescription)
- [ProductId](#BKMK_ProductId)
- [ProductName](#BKMK_ProductName)
- [ProductTypeCode](#BKMK_ProductTypeCode)
- [PropertyConfigurationStatus](#BKMK_PropertyConfigurationStatus)
- [Quantity](#BKMK_Quantity)
- [SequenceNumber](#BKMK_SequenceNumber)
- [SkipPriceCalculation](#BKMK_SkipPriceCalculation)
- [Tax](#BKMK_Tax)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [TransactionCurrencyId](#BKMK_TransactionCurrencyId)
- [UoMId](#BKMK_UoMId)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)

### <a name="BKMK_BaseAmount"></a> BaseAmount

|Property|Value|
|---|---|
|Description|**Shows the total price of the opportunity product, based on the price per unit, volume discount, and quantity.**|
|DisplayName|**Amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`baseamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_Description"></a> Description

|Property|Value|
|---|---|
|Description|**Type additional information to describe the opportunity product, such as manufacturing details.**|
|DisplayName|**Description**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`description`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

### <a name="BKMK_EntityImage"></a> EntityImage

|Property|Value|
|---|---|
|Description|**The default image for the entity.**|
|DisplayName|**Entity Image**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`entityimage`|
|RequiredLevel|None|
|Type|Image|
|CanStoreFullImage|False|
|IsPrimaryImage|True|
|MaxHeight|144|
|MaxSizeInKB|10240|
|MaxWidth|144|

### <a name="BKMK_ExtendedAmount"></a> ExtendedAmount

|Property|Value|
|---|---|
|Description|**Shows the total amount due for the opportunity product, calculated on the Amount value minus the Manual Discount amount.**|
|DisplayName|**Extended amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`extendedamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

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

### <a name="BKMK_IsPriceOverridden"></a> IsPriceOverridden

|Property|Value|
|---|---|
|Description|**Select whether the pricing on the opportunity product reflects an override of the product catalog pricing.**|
|DisplayName|**Price Overridden**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ispriceoverridden`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`opportunityproduct_ispriceoverridden`|
|DefaultValue|False|
|True Label|Override Price|
|False Label|Use Default|

### <a name="BKMK_IsProductOverridden"></a> IsProductOverridden

|Property|Value|
|---|---|
|Description|**For system use only.**|
|DisplayName|**Select Product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`isproductoverridden`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`opportunityproduct_isproductoverridden`|
|DefaultValue|False|
|True Label|Write-In|
|False Label|Existing|

### <a name="BKMK_LineItemNumber"></a> LineItemNumber

|Property|Value|
|---|---|
|Description|**Type the line item number for the opportunity product to easily identify the product in the opportunity documents and make sure it's listed in the correct order.**|
|DisplayName|**Line Item Number**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`lineitemnumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|1000000000|
|MinValue|0|

### <a name="BKMK_ManualDiscountAmount"></a> ManualDiscountAmount

|Property|Value|
|---|---|
|Description|**Type the manual discount amount for the opportunity product to deduct any negotiated or other savings from the product total.**|
|DisplayName|**Manual Discount Amount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`manualdiscountamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|False|
|MaxValue|100000000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_OpportunityId"></a> OpportunityId

|Property|Value|
|---|---|
|Description|**Unique identifier of the opportunity with which the opportunity product is associated.**|
|DisplayName|**Opportunity**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`opportunityid`|
|RequiredLevel|SystemRequired|
|Type|Lookup|
|Targets|opportunity|

### <a name="BKMK_OpportunityProductId"></a> OpportunityProductId

|Property|Value|
|---|---|
|Description|**Unique identifier of the opportunity product.**|
|DisplayName|**Opportunity Product**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`opportunityproductid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_OpportunityProductName"></a> OpportunityProductName

|Property|Value|
|---|---|
|Description|**Opportunity Product Name. Added for 1:n referential relationship (internal purposes only)**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`opportunityproductname`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|500|

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

### <a name="BKMK_ParentBundleId"></a> ParentBundleId

|Property|Value|
|---|---|
|Description|**Choose the parent bundle associated with this product**|
|DisplayName|**Parent Bundle**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`parentbundleid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

### <a name="BKMK_ParentBundleIdRef"></a> ParentBundleIdRef

|Property|Value|
|---|---|
|Description|**Choose the parent bundle associated with this product**|
|DisplayName|**Parent bundle product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`parentbundleidref`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|opportunityproduct|

### <a name="BKMK_PricePerUnit"></a> PricePerUnit

|Property|Value|
|---|---|
|Description|**Shows the price per unit of the opportunity product, based on the price list specified on the parent opportunity.**|
|DisplayName|**Price per unit**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`priceperunit`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|2|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

### <a name="BKMK_PricingErrorCode"></a> PricingErrorCode

|Property|Value|
|---|---|
|Description|**Select the pricing error for the opportunity product.**|
|DisplayName|**Pricing Error**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`pricingerrorcode`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`qooi_pricingerrorcode`|

#### PricingErrorCode Choices/Options

|Value|Label|
|---|---|
|0|**None**|
|1|**Detail Error**|
|2|**Missing Price Level**|
|3|**Inactive Price Level**|
|4|**Missing Quantity**|
|5|**Missing Unit Price**|
|6|**Missing Product**|
|7|**Invalid Product**|
|8|**Missing Pricing Code**|
|9|**Invalid Pricing Code**|
|10|**Missing UOM**|
|11|**Product Not In Price Level**|
|12|**Missing Price Level Amount**|
|13|**Missing Price Level Percentage**|
|14|**Missing Price**|
|15|**Missing Current Cost**|
|16|**Missing Standard Cost**|
|17|**Invalid Price Level Amount**|
|18|**Invalid Price Level Percentage**|
|19|**Invalid Price**|
|20|**Invalid Current Cost**|
|21|**Invalid Standard Cost**|
|22|**Invalid Rounding Policy**|
|23|**Invalid Rounding Option**|
|24|**Invalid Rounding Amount**|
|25|**Price Calculation Error**|
|26|**Invalid Discount Type**|
|27|**Discount Type Invalid State**|
|28|**Invalid Discount**|
|29|**Invalid Quantity**|
|30|**Invalid Pricing Precision**|
|31|**Missing Product Default UOM**|
|32|**Missing Product UOM Schedule**|
|33|**Inactive Discount Type**|
|34|**Invalid Price Level Currency**|
|35|**Price Attribute Out Of Range**|
|36|**Base Currency Attribute Overflow**|
|37|**Base Currency Attribute Underflow**|
|38|**Transaction currency is not set for the product price list item**|

### <a name="BKMK_ProductAssociationId"></a> ProductAssociationId

|Property|Value|
|---|---|
|Description|**Unique identifier of the product line item association with bundle in the opportunity**|
|DisplayName|**Bundle Item Association**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`productassociationid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

### <a name="BKMK_ProductDescription"></a> ProductDescription

|Property|Value|
|---|---|
|Description|**Type a detailed product description or additional notes about the opportunity product, such as talking points or product updates, that will assist the sales team when they discuss the product with the customer.**|
|DisplayName|**Write-In Product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`productdescription`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|500|

### <a name="BKMK_ProductId"></a> ProductId

|Property|Value|
|---|---|
|Description|**Choose the product to include on the opportunity to link the product's pricing and other information to the opportunity.**|
|DisplayName|**Existing Product**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`productid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|product|

### <a name="BKMK_ProductName"></a> ProductName

|Property|Value|
|---|---|
|Description|**Calculated field that will be populated by name and description of the product.**|
|DisplayName|**Product name**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`productname`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|500|

### <a name="BKMK_ProductTypeCode"></a> ProductTypeCode

|Property|Value|
|---|---|
|Description|**Product Type**|
|DisplayName|**Product type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`producttypecode`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|1|
|GlobalChoiceName|`qooiproduct_producttype`|

#### ProductTypeCode Choices/Options

|Value|Label|
|---|---|
|1|**Product**|
|2|**Bundle**|
|3|**Required Bundle Product**|
|4|**Optional Bundle Product**|
|5|**Project-based Service**|

### <a name="BKMK_PropertyConfigurationStatus"></a> PropertyConfigurationStatus

|Property|Value|
|---|---|
|Description|**Status of the property configuration.**|
|DisplayName|**Property Configuration**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`propertyconfigurationstatus`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|2|
|GlobalChoiceName|`qooiproduct_propertiesconfigurationstatus`|

#### PropertyConfigurationStatus Choices/Options

|Value|Label|
|---|---|
|0|**Edit**|
|1|**Rectify**|
|2|**Not Configured**|

### <a name="BKMK_Quantity"></a> Quantity

|Property|Value|
|---|---|
|Description|**Type the amount or quantity of the product the customer would like to purchase.**|
|DisplayName|**Quantity**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`quantity`|
|RequiredLevel|ApplicationRequired|
|Type|Decimal|
|ImeMode|Disabled|
|MaxValue|100000000000|
|MinValue|-100000000000|
|Precision|5|
|SourceTypeMask|0|

### <a name="BKMK_SequenceNumber"></a> SequenceNumber

|Property|Value|
|---|---|
|Description|**Shows the ID of the data that maintains the sequence.**|
|DisplayName|**Sequence Number**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`sequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_SkipPriceCalculation"></a> SkipPriceCalculation

|Property|Value|
|---|---|
|Description|**Skip price calculation**|
|DisplayName|**Skip Price Calculation**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`skippricecalculation`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`qooidetail_skippricecalculation`|

#### SkipPriceCalculation Choices/Options

|Value|Label|
|---|---|
|0|**DoPriceCalcAlways**|
|1|**SkipPriceCalcOnCreate**|
|2|**SkipPriceCalcOnUpdate**|
|3|**SkipPriceCalcOnUpSert**|

### <a name="BKMK_Tax"></a> Tax

|Property|Value|
|---|---|
|Description|**Type the tax amount to be applied on the opportunity product.**|
|DisplayName|**Tax**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`tax`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|False|
|MaxValue|100000000000000|
|MinValue|-100000000000000|
|Precision|2|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

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
|Description|**Choose the local currency for the record to make sure budgets are reported in the correct currency.**|
|DisplayName|**Currency**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`transactioncurrencyid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|transactioncurrency|

### <a name="BKMK_UoMId"></a> UoMId

|Property|Value|
|---|---|
|Description|**Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.**|
|DisplayName|**Unit**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`uomid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|uom|

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

- [BaseAmount_Base](#BKMK_BaseAmount_Base)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [EntityImage_Timestamp](#BKMK_EntityImage_Timestamp)
- [EntityImage_URL](#BKMK_EntityImage_URL)
- [EntityImageId](#BKMK_EntityImageId)
- [ExchangeRate](#BKMK_ExchangeRate)
- [ExtendedAmount_Base](#BKMK_ExtendedAmount_Base)
- [ManualDiscountAmount_Base](#BKMK_ManualDiscountAmount_Base)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OpportunityStateCode](#BKMK_OpportunityStateCode)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdType](#BKMK_OwnerIdType)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [PricePerUnit_Base](#BKMK_PricePerUnit_Base)
- [Tax_Base](#BKMK_Tax_Base)
- [VersionNumber](#BKMK_VersionNumber)
- [VolumeDiscountAmount](#BKMK_VolumeDiscountAmount)
- [VolumeDiscountAmount_Base](#BKMK_VolumeDiscountAmount_Base)

### <a name="BKMK_BaseAmount_Base"></a> BaseAmount_Base

|Property|Value|
|---|---|
|Description|**Value of the Amount in base currency.**|
|DisplayName|**Amount (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`baseamount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|---|---|
|Description|**Shows who created the record.**|
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
|Description|**Shows who created the record on behalf of another user.**|
|DisplayName|**Created By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_EntityImage_Timestamp"></a> EntityImage_Timestamp

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`entityimage_timestamp`|
|RequiredLevel|None|
|Type|BigInt|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|

### <a name="BKMK_EntityImage_URL"></a> EntityImage_URL

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`entityimage_url`|
|RequiredLevel|None|
|Type|String|
|Format|Url|
|FormatName|Url|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|200|

### <a name="BKMK_EntityImageId"></a> EntityImageId

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`entityimageid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

### <a name="BKMK_ExchangeRate"></a> ExchangeRate

|Property|Value|
|---|---|
|Description|**Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.**|
|DisplayName|**Exchange Rate**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`exchangerate`|
|RequiredLevel|None|
|Type|Decimal|
|ImeMode|Disabled|
|MaxValue|100000000000|
|MinValue|1E-12|
|Precision|12|
|SourceTypeMask|0|

### <a name="BKMK_ExtendedAmount_Base"></a> ExtendedAmount_Base

|Property|Value|
|---|---|
|Description|**Value of the Extended Amount in base currency.**|
|DisplayName|**Extended Amount (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`extendedamount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_ManualDiscountAmount_Base"></a> ManualDiscountAmount_Base

|Property|Value|
|---|---|
|Description|**Value of the Manual Discount Amount in base currency.**|
|DisplayName|**Manual Discount Amount (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`manualdiscountamount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|---|---|
|Description|**Shows who last updated the record.**|
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
|Description|**Unique identifier of the delegate user who last modified the opportunityproduct.**|
|DisplayName|**Modified By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_OpportunityStateCode"></a> OpportunityStateCode

|Property|Value|
|---|---|
|Description|**Select the status of the opportunity product.**|
|DisplayName|**Opportunity Status**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`opportunitystatecode`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`opportunityproduct_opportunitystatecode`|

#### OpportunityStateCode Choices/Options

|Value|Label|
|---|---|

### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|---|---|
|Description|**Owner Id**|
|DisplayName|**Owner**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`ownerid`|
|RequiredLevel|ApplicationRequired|
|Type|Owner|
|Targets|systemuser, team|

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
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owningbusinessunit`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets||

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
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets||

### <a name="BKMK_PricePerUnit_Base"></a> PricePerUnit_Base

|Property|Value|
|---|---|
|Description|**Value of the Price Per Unit in base currency.**|
|DisplayName|**Price Per Unit (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`priceperunit_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|1 (Organization.PricingDecimalPrecision)|

### <a name="BKMK_Tax_Base"></a> Tax_Base

|Property|Value|
|---|---|
|Description|**Value of the Tax in base currency.**|
|DisplayName|**Tax (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`tax_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

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

### <a name="BKMK_VolumeDiscountAmount"></a> VolumeDiscountAmount

|Property|Value|
|---|---|
|Description|**Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.**|
|DisplayName|**Volume Discount**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`volumediscountamount`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|False|
|MaxValue|922337203685477|
|MinValue|0|
|Precision|2|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

### <a name="BKMK_VolumeDiscountAmount_Base"></a> VolumeDiscountAmount_Base

|Property|Value|
|---|---|
|Description|**Value of the Volume Discount in base currency.**|
|DisplayName|**Volume Discount (Base)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`volumediscountamount_base`|
|RequiredLevel|None|
|Type|Money|
|ImeMode|Disabled|
|IsBaseCurrency|True|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|2 (TransactionCurrency.CurrencyPrecision)|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [lk_opportunityproduct_createdonbehalfby](#BKMK_lk_opportunityproduct_createdonbehalfby)
- [lk_opportunityproduct_modifiedonbehalfby](#BKMK_lk_opportunityproduct_modifiedonbehalfby)
- [lk_opportunityproductbase_createdby](#BKMK_lk_opportunityproductbase_createdby)
- [lk_opportunityproductbase_modifiedby](#BKMK_lk_opportunityproductbase_modifiedby)
- [opportunity_products](#BKMK_opportunity_products)
- [opportunityproduct_parent_opportunityproduct](#BKMK_opportunityproduct_parent_opportunityproduct-many-to-one)
- [opportunityproduct_parentref_opportunityproduct](#BKMK_opportunityproduct_parentref_opportunityproduct-many-to-one)
- [product_opportunities](#BKMK_product_opportunities)
- [productAssociation_opportunity_product](#BKMK_productAssociation_opportunity_product)
- [team_opportunityproduct](#BKMK_team_opportunityproduct)
- [transactioncurrency_opportunityproduct](#BKMK_transactioncurrency_opportunityproduct)
- [unit_of_measurement_opportunity_products](#BKMK_unit_of_measurement_opportunity_products)
- [user_opportunityproduct](#BKMK_user_opportunityproduct)

### <a name="BKMK_lk_opportunityproduct_createdonbehalfby"></a> lk_opportunityproduct_createdonbehalfby

One-To-Many Relationship: [systemuser lk_opportunityproduct_createdonbehalfby](systemuser.md#BKMK_lk_opportunityproduct_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_opportunityproduct_modifiedonbehalfby"></a> lk_opportunityproduct_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_opportunityproduct_modifiedonbehalfby](systemuser.md#BKMK_lk_opportunityproduct_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_opportunityproductbase_createdby"></a> lk_opportunityproductbase_createdby

One-To-Many Relationship: [systemuser lk_opportunityproductbase_createdby](systemuser.md#BKMK_lk_opportunityproductbase_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_opportunityproductbase_modifiedby"></a> lk_opportunityproductbase_modifiedby

One-To-Many Relationship: [systemuser lk_opportunityproductbase_modifiedby](systemuser.md#BKMK_lk_opportunityproductbase_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_opportunity_products"></a> opportunity_products

One-To-Many Relationship: [product opportunity_products](product.md#BKMK_opportunity_products)

|Property|Value|
|---|---|
|ReferencedEntity|`product`|
|ReferencedAttribute|`productid`|
|ReferencingAttribute|`productid`|
|ReferencingEntityNavigationPropertyName|`productid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_opportunityproduct_parent_opportunityproduct-many-to-one"></a> opportunityproduct_parent_opportunityproduct

One-To-Many Relationship: [opportunityproduct opportunityproduct_parent_opportunityproduct](#BKMK_opportunityproduct_parent_opportunityproduct-one-to-many)

|Property|Value|
|---|---|
|ReferencedEntity|`opportunityproduct`|
|ReferencedAttribute|`opportunityproductid`|
|ReferencingAttribute|`parentbundleid`|
|ReferencingEntityNavigationPropertyName|`parentbundleid_opportunityproduct`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_opportunityproduct_parentref_opportunityproduct-many-to-one"></a> opportunityproduct_parentref_opportunityproduct

One-To-Many Relationship: [opportunityproduct opportunityproduct_parentref_opportunityproduct](#BKMK_opportunityproduct_parentref_opportunityproduct-one-to-many)

|Property|Value|
|---|---|
|ReferencedEntity|`opportunityproduct`|
|ReferencedAttribute|`opportunityproductid`|
|ReferencingAttribute|`parentbundleidref`|
|ReferencingEntityNavigationPropertyName|`parentbundleidref_opportunityproduct`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_product_opportunities"></a> product_opportunities

One-To-Many Relationship: [opportunity product_opportunities](opportunity.md#BKMK_product_opportunities)

|Property|Value|
|---|---|
|ReferencedEntity|`opportunity`|
|ReferencedAttribute|`opportunityid`|
|ReferencingAttribute|`opportunityid`|
|ReferencingEntityNavigationPropertyName|`opportunityid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_productAssociation_opportunity_product"></a> productAssociation_opportunity_product

One-To-Many Relationship: [productassociation productAssociation_opportunity_product](productassociation.md#BKMK_productAssociation_opportunity_product)

|Property|Value|
|---|---|
|ReferencedEntity|`productassociation`|
|ReferencedAttribute|`productassociationid`|
|ReferencingAttribute|`productassociationid`|
|ReferencingEntityNavigationPropertyName|`productassociationid_productassociation`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_opportunityproduct"></a> team_opportunityproduct

One-To-Many Relationship: [team team_opportunityproduct](team.md#BKMK_team_opportunityproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_transactioncurrency_opportunityproduct"></a> transactioncurrency_opportunityproduct

One-To-Many Relationship: [transactioncurrency transactioncurrency_opportunityproduct](transactioncurrency.md#BKMK_transactioncurrency_opportunityproduct)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_unit_of_measurement_opportunity_products"></a> unit_of_measurement_opportunity_products

One-To-Many Relationship: [uom unit_of_measurement_opportunity_products](uom.md#BKMK_unit_of_measurement_opportunity_products)

|Property|Value|
|---|---|
|ReferencedEntity|`uom`|
|ReferencedAttribute|`uomid`|
|ReferencingAttribute|`uomid`|
|ReferencingEntityNavigationPropertyName|`uomid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_opportunityproduct"></a> user_opportunityproduct

One-To-Many Relationship: [systemuser user_opportunityproduct](systemuser.md#BKMK_user_opportunityproduct)

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

- [OpportunityProduct_AsyncOperations](#BKMK_OpportunityProduct_AsyncOperations)
- [OpportunityProduct_BulkDeleteFailures](#BKMK_OpportunityProduct_BulkDeleteFailures)
- [OpportunityProduct_Dynamicpropertyinstance](#BKMK_OpportunityProduct_Dynamicpropertyinstance)
- [opportunityproduct_MailboxTrackingFolders](#BKMK_opportunityproduct_MailboxTrackingFolders)
- [opportunityproduct_parent_opportunityproduct](#BKMK_opportunityproduct_parent_opportunityproduct-one-to-many)
- [opportunityproduct_parentref_opportunityproduct](#BKMK_opportunityproduct_parentref_opportunityproduct-one-to-many)
- [opportunityproduct_principalobjectattributeaccess](#BKMK_opportunityproduct_principalobjectattributeaccess)
- [OpportunityProduct_ProcessSessions](#BKMK_OpportunityProduct_ProcessSessions)
- [OpportunityProduct_SyncErrors](#BKMK_OpportunityProduct_SyncErrors)

### <a name="BKMK_OpportunityProduct_AsyncOperations"></a> OpportunityProduct_AsyncOperations

Many-To-One Relationship: [asyncoperation OpportunityProduct_AsyncOperations](asyncoperation.md#BKMK_OpportunityProduct_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`OpportunityProduct_AsyncOperations`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_OpportunityProduct_BulkDeleteFailures"></a> OpportunityProduct_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure OpportunityProduct_BulkDeleteFailures](bulkdeletefailure.md#BKMK_OpportunityProduct_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`OpportunityProduct_BulkDeleteFailures`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_OpportunityProduct_Dynamicpropertyinstance"></a> OpportunityProduct_Dynamicpropertyinstance

Many-To-One Relationship: [dynamicpropertyinstance OpportunityProduct_Dynamicpropertyinstance](dynamicpropertyinstance.md#BKMK_OpportunityProduct_Dynamicpropertyinstance)

|Property|Value|
|---|---|
|ReferencingEntity|`dynamicpropertyinstance`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`OpportunityProduct_Dynamicpropertyinstance`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_opportunityproduct_MailboxTrackingFolders"></a> opportunityproduct_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder opportunityproduct_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_opportunityproduct_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`opportunityproduct_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_opportunityproduct_parent_opportunityproduct-one-to-many"></a> opportunityproduct_parent_opportunityproduct

Many-To-One Relationship: [opportunityproduct opportunityproduct_parent_opportunityproduct](#BKMK_opportunityproduct_parent_opportunityproduct-many-to-one)

|Property|Value|
|---|---|
|ReferencingEntity|`opportunityproduct`|
|ReferencingAttribute|`parentbundleid`|
|ReferencedEntityNavigationPropertyName|`opportunityproduct_parent_opportunityproduct`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_opportunityproduct_parentref_opportunityproduct-one-to-many"></a> opportunityproduct_parentref_opportunityproduct

Many-To-One Relationship: [opportunityproduct opportunityproduct_parentref_opportunityproduct](#BKMK_opportunityproduct_parentref_opportunityproduct-many-to-one)

|Property|Value|
|---|---|
|ReferencingEntity|`opportunityproduct`|
|ReferencingAttribute|`parentbundleidref`|
|ReferencedEntityNavigationPropertyName|`opportunityproduct_parentref_opportunityproduct`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_opportunityproduct_principalobjectattributeaccess"></a> opportunityproduct_principalobjectattributeaccess

Many-To-One Relationship: [principalobjectattributeaccess opportunityproduct_principalobjectattributeaccess](principalobjectattributeaccess.md#BKMK_opportunityproduct_principalobjectattributeaccess)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`opportunityproduct_principalobjectattributeaccess`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_OpportunityProduct_ProcessSessions"></a> OpportunityProduct_ProcessSessions

Many-To-One Relationship: [processsession OpportunityProduct_ProcessSessions](processsession.md#BKMK_OpportunityProduct_ProcessSessions)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`OpportunityProduct_ProcessSessions`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 110<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_OpportunityProduct_SyncErrors"></a> OpportunityProduct_SyncErrors

Many-To-One Relationship: [syncerror OpportunityProduct_SyncErrors](syncerror.md#BKMK_OpportunityProduct_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`OpportunityProduct_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

