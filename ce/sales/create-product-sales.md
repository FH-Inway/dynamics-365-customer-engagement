---
title: Manage products
description: Use products in Dynamics 365 Sales to define the products or services that your organization offers.
ms.date: 02/27/2025
ms.topic: how-to
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
ms.custom:
  - dyn365-sales
searchScope:
  - D365-App-msdynce_saleshub
  - D365-App-msdynce_salespro
  - D365-Entity-product
  - D365-UI-*
  - Dynamics 365
  - Sales
  - Customer Engagement
---

# Manage products

Use products in Dynamics 365 Sales to define the products or services that your organization offers.

## Create a product

Products are the backbone of your business. They can be physical products or services—whatever your organization sells. Your sales reps use the products you create in [!INCLUDE[pn-sales-enterprise-doc-name-shortest](../includes/pn-sales-enterprise-doc-name-shortest.md)] to generate sales quotes, marketing campaigns, orders, and invoices. Your customer service reps might also use them when they create customer service cases.

Products that you create are visible to all users in your organization.

1. Depending on the sales app that you're using, do one of the following:

    - If you're using the Sales Hub app,
      1. Select **Change area** ![Icon to change the work area.](media/change-area-icon.png "Icon to change the work area") at the lower-left corner of the site map, and then select **App Settings**.
      1. In the **Product Catalog** area, select **Families and products**.
    - If you're using the Sales Professional app,
      - Select **Price Lists** from the site map.

1. (Applicable for Sales Premium and Sales Enterprise) To create a child product to an existing product family, select the family in the list, and then on the command bar, select **Add Product**. The selected family becomes the parent family of the new product you're creating. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Create a product family](create-product-family.md)

1. To create an independent product, select **Add Product**.

    :::image type="content" source="media/products-grid.png" alt-text="Screenshot showing all products, families, and bundles.":::

1. Fill in your information:

    - **Name**: Enter the name of the product.
    - **Product ID**: Enter the product ID.
    - **Parent**: Select a new parent for this product. More information: [Change the parent of a product (reparenting)](change-product-parent.md)
    - **Valid From**/**Valid To**: Define the period the product is valid for by selecting a **Valid From** and **Valid To** date.
    - **Unit Group**: Select a unit group. A unit group is a collection of various units a product is sold in and defines how individual items are grouped into larger quantities. For example, if you're adding seeds as a product, you may have created a unit group called "Seeds" and defined its primary unit as "packet."
    - **Default Unit**: Select the most common unit in which the product will be sold. Units are the quantities or measurements that you sell your products in. For example, if you're adding seeds as a product, you can sell it in packets, boxes, or pallets. Each of these becomes a unit of the product. If seeds are mostly sold in packets, select that as the unit. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Create a unit group and add units to that group](create-unit-group-add-units-that-group.md)
    - **Default Price List**: If this is a new product, this field is read-only. Before you can select a default price list, you must complete all the required fields and then save the record. Although the default price list is not required, after you save the product record, it is a good idea to set a default price list for each product. If a customer record does not contain a price list, [!INCLUDE[pn-sales-enterprise-doc-name-shortest](../includes/pn-sales-enterprise-doc-name-shortest.md)] can use the default price list for generating quotes, orders, and invoices.
    - **Decimals Supported**: Enter a whole number between 0 and 5. If the product can't be divided into fractional quantities, enter 0. The precision of the **Quantity** field in the quote, order, or invoice product record is validated against the value in this field if the product does not have an associated price list.
    - **Subject**: Associate this product with a subject. You can use subjects to categorize your products and to filter reports.

1. Select **Save**.

1. If you're creating this product under a family, the product will inherit the properties from its parent family. To change a product's property, in the **Product Properties** section, open the property by selecting the name, and selecting **Override**. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Use properties to describe a product](use-properties-describe-product.md)

1. To add product relationships, select the **Related** tab, and then select **Product Relationships**. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Define related products to increase chances of sales](define-related-products-increase-chances-sales.md)

1. To see all the products that are associated with this product in a bundle, select the **Related** tab, and select **Product Bundles**.

1. Select **Save**.

> [!NOTE]
> Previewing the properties of a product is currently not supported.

## List sales records associated with a product

You can list the sales records associated with a product for various reasons. For example, before you can delete a product, you must remove the product from all the associated sales records. The following steps show you how to list the opportunities associated with a product. Use the same steps to list other sales records such as quotes, orders, and invoices.

1. Select **Opportunities** from the site map.
1. Select **Edit filters** at the top of the page.
1. Delete all the existing filters from the view.
1. Select **Add** > **Add related entity** with the following filters:
    - **Related entity**: Opportunity Products (Opportunity) or Opportunity Lines (Opportunity)

        > [!NOTE]
        > The related entity name differs for each table but it's similar to the example provided. For example, the related entity name for quote table is Quote Products (Quote) or Quote Lines (Quote).

    - **Operator**: Contains data
    - **Field**: Existing product
    - **Operator**: Equals
    - **Value**: Select the product you want to list the opportunities for.

    :::image type="content" source="media/linked-products-filter.png" alt-text="Screenshot of the filter to list opportunities associated with a product.":::

1. Select **Apply** to view the opportunities that contain the product.
1. Select the view drop-down at the top of the page, and then select **Save as new view** to save the view.

## Typical next steps

- [Define product pricing with price lists and price list items](create-price-lists-price-list-items-define-pricing-products.md)
- [Classify products and bundles into product families](create-product-bundles-sell-multiple-items-together.md)

[!INCLUDE [cant-find-option](../includes/cant-find-option.md)]

## Related information

[Set up a product catalog](set-up-product-catalog-walkthrough.md)  
[Manage sales literature](create-sales-literature.md)  
[Change the parent of a product (reparenting)](change-product-parent.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
