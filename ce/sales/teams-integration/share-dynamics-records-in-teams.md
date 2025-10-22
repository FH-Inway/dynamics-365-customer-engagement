---
title: Share Dynamics 365 records within Microsoft Teams conversations
description: Learn how to share Dynamics 365 records within Microsoft Teams conversations
ms.date: 09/17/2025
ms.topic: how-to
ms.service: dynamics-365-sales
author: sbmjais
ms.author: shjais
ms.reviewer: shjais 
---

# Share Dynamics 365 records within Microsoft Teams conversations (production-ready preview)

[!INCLUDE [cc-beta-prerelease-disclaimer](../../includes/cc-beta-prerelease-disclaimer.md)]

Discussing a particular opportunity on Teams? Share the record of the chat conversation and let participants view it without navigating away from Teams. You can share any Dynamics 365 record on Teams channels and chat conversations.

## Share a Dynamics 365 record through search

As a sender, you can share records using search in the app. The search displays the record name and the table type in the search results. However, if you want to search records as per a table type and preview a record in the search results, you must use the advanced search functionality.

> [!NOTE]
> You can also share a record by typing `@Dynamics 365` followed by a message to the Dynamics 365 app during a Teams conversation. The app allows you to search for the record and then it shares the record on your behalf in the Teams conversation. For example, if you type `@Dynamics 365, help me find the Alpine deal`, the app responds with a message to search for the record. You can then search for the record and share it.

**To share a record using search:**

1.  Go to the new or an existing conversation in which you want to share a record, and then [open the Dynamics 365 app](access-d365-app.md#access-the-dynamics-365-app).

2.  In the **Dynamics 365** window, search for the record to share, and then select it to share as a card on the chat.

    > [!NOTE]
    > -   By default, the recently accessed records are displayed, without performing any search. You can either search for the record or use the record type tabs available above the search field to search for a particular record type.
    > -   The **All** tab allows you to search for all table type (out-of-the-box and custom) records. Other tabs are specific to a table type and allow you to search for that record type.    
    
    :::image type="content" source="media/me-search-record.png" alt-text="Screenshot of searching for a record.":::
    
    The selected record is shared on the Teams chat.
    
    :::image type="content" source="media/me-info-card.png" alt-text="Screenshot of an interactive card.":::

**To share a record using advanced search:**

1.  Go to the new or existing conversation in which you want to share a record, and then [open the Dynamics 365 app](access-d365-app.md#access-the-dynamics-365-app).

2.  Select **Action Commands** (**…**) in the upper-right corner, and then select **Advanced search**.

    :::image type="content" source="media/me-advanced-search-menu.png" alt-text="Screenshot of accessing advanced search.":::

3.  In the **Advanced search** window, enter or select the following values:

    - **Search for a record to share**: Name of the record to share.

    - **Filter by**: Record type to search for.

    :::image type="content" source="media/me-adv-search-record.png" alt-text="Screenshot of searching for a record using advanced search.":::

4.  From the results, preview a record by selecting the down arrow next to the record name. Select a record to share it as a card on the chat.

    :::image type="content" source="media/me-adv-search-results.png" alt-text="Screenshot of advanced search results.":::

If you see a disclaimer while sharing a record over Teams, it means that the app isn't yet added for that conversation or team. You can still share the record over Teams. The recipients must add the Dynamics 365 app to their Teams.

## Share a record through URL

You can also share a record by pasting the URL of a Dynamics 365 record. You can get the URL of a record from the web browser. The record is displayed as an information card with actions.

## Related information

[Share and update Dynamics 365 records within Microsoft Teams conversations](share-d365-record-overview.md)   
[Access the Dynamics 365 app through messaging extensions](access-d365-app.md)   
[Edit settings of the Dynamics 365 app](edit-d365-app.md)    
[Share feedback](share-feedback-d365-app.md)    
[View and update record details](view-update-dynamics-records.md)   
[Add chat messages to Dynamics 365 as notes or tasks](add-chat-d365.md)   
