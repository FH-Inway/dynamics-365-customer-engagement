---
title: Use autonomous case management agents to create and update cases (preview)
description: Learn how to use autonomous case management agents to efficiently handle case management tasks.
author: gandhamm
ms.author: mgandham
ms.reviewer: mgandham
ms.topic: how-to 
ms.collection: 
ms.date: 03/04/2025
ms.custom: bap-template 
---

# Use autonomous case management agents to create and update cases (preview)

[!INCLUDE [preview-banner](~/../shared-content/shared/preview-includes/preview-banner.md)]

The autonomous case management agent  uses live chat conversations and incoming emails  to create cases and fill in relevant case fields. It can also update case fields during ongoing conversations, eliminating the need for manual case creation and reducing errors.

[!INCLUDE [preview-banner](../../../shared-content/shared/preview-includes/preview-note-d365.md)]


## Autonomous case creation

The agent creates cases automatically from chat conversations and incoming emails.

### Live chat

When you accept a conversation that is routed directly or is escalated by a self-assist agent (bot) with enough context, the autonomous case management agent performs the following actions:

- Maps the context from the conversation to the fields configured by the administrator and predicts the values for those fields.
- Creates a new case that opens in a new tab in the Active Conversation form. A case is created only if the agent has enough context to populate all the configured fields. 
- Populates the values of the fields in the case.
- Automatically saves the case.

If there isn't enough context in the conversation to populate the mandatory fields, the agent doesn't create a case when you accept the conversation. However, when you end the conversation, if there's enough information, the agent creates a case, if it isn't manually created.

### Email

For an incoming email, a case is created automatically based on the configured ARC rules. The agent then predicts and populates the configured default fields with the context from the email. 

## Update a case

The agent updates the fields configured by the administrator as follows:

- **For a case created from a conversation**: The **Update from conversation** button appears on the case form. When you select the button, the agent populates the fields with context from the ongoing conversation. Updated fields are highlighted, and a banner indicates they were modified using AI. 
- If there isn't enough context to populate the fields, the agent doesn't update them and displays a message indicating no changes.
- If the conversation is in wrap-up state, the agent checks if a case is created. If the case isn't created, the agent creates a new case and populates the case fields. If a case is created, the agent updates the specified fields.
- When you end the conversation and if the administrator has enabled the **Automatically create a note at the end of the a live chat using conversation summary** option, the agent creates a note with the conversation summary at the end of the chat.

- **For a case created from an email**: The agent populates the fields with context from incoming emails linked to the case. 

 You can review the updated fields from in **Audit history** if your administrator has enabled Dataverse auditing.

> [!NOTE]
> If Case fields that configured for AI agent updates are updated manually, the AI agent doesn't overwrite the manual updates.

## Next steps

 [Use autonomous follow-up and closure of cases](use-follow-up-closure.md)