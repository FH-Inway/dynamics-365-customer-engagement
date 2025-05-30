---
title: Join an existing connected chat in Sales Hub
description: Learn how to join an existing connected chat in Sales Hub.
ms.date: 08/16/2024
ms.topic: how-to
ms.service: dynamics-365-sales
author: sbmjais
ms.author: shjais
ms.reviewer: shjais 
---

# Join an existing connected chat

View and easily join chats that are connected to a record you have write access to.

## Join a connected chat

As a seller, you can view and easily join chats that are connected to a record you have write access to, even if you weren't originally a participant in the chat. For example, if you've onboarded to a lead previously managed by another seller, you can join the chat to understand the context and then collaborate with your colleagues.

> [!NOTE]
> You can only join connected chats. To do so, you must have write access to the record and your admin must turn on the Join Chat capability for the record type in which you want to join any existing connected chat.

1. Open the record for which you want to join the chat.

2. In the **Teams chats** pane, go to any of the connected chats you want to join. A lock icon is displayed with text that says, "Hover over to join this chat". When you hover over the lock icon, if you have write access to the associated record, a **Join** button is displayed.

    > [!NOTE]
    > Let's assume you have only Read access to the set of Accounts which your team is working on. Your administrator has enabled the Join chat functionality for the Accounts record type.
    >
    > If you don't see the text that allows you to hover and join a chat, there are three possible causes:<br> - Your administrator hasn't enabled the Join chat capability for the record type.<br> - You have read-only access to the record.<br> - Both previous scenarios apply.
    >     
    > In these cases, you will still see a list of conversations with the message "The chat is locked". In this case, you can ask a member of the chat to manually add you, or you can ask your administrator to turn on the Join chat capabilities for that record type. 

3. Select **Join**.

    :::image type="content" source="media/hover-join-chat.png" alt-text="Screenshot of the instruction to hover over a chat to join it.":::

    The Teams pop-up chat shows you're added, giving you access to the entire chat history. Other chat members also receive a system message that you've joined.

## Related information

[Configure the ability for users to join chats](enable-join-chat.md)

