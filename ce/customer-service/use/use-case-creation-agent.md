---
title: Use Case Management Agent to create and update cases (preview)
description: Learn how to use autonomous case management agents to efficiently handle case management tasks.
author: gandhamm
ms.author: mgandham
ms.reviewer: mgandham
ms.topic: how-to 
ms.collection: 
ms.date: 05/26/2025
ms.custom: bap-template 
---

# Use Case Management Agent to create and update cases (preview)

[!INCLUDE [preview-banner](~/../shared-content/shared/preview-includes/preview-banner.md)]

The Case Management Agent uses chat conversations and incoming emails  to create cases and fill in relevant case fields. It can also update case fields during ongoing conversations, eliminating the need for manual case creation and reducing errors.

[!INCLUDE [preview-banner](../../../shared-content/shared/preview-includes/production-ready-preview-dynamics365.md)]


## Autonomous case creation

The agent creates cases automatically from chat conversations and incoming emails.

### Chat

When you accept a conversation routed directly or escalated by a self-assist agent with enough context, the Case Management Agent performs the following actions:

- Maps the context from the conversation to the fields configured by the administrator and predicts the values for those fields.
- Creates a new case that opens in a new tab in the **Active Conversation** form. A case is created only if the agent has enough context to populate all the configured fields. 
- Populates the values of the fields in the case.
- Automatically saves the case.

If there isn't enough context in the conversation to populate the mandatory fields, the agent doesn't create a case when you accept the conversation. However, when you end the conversation, if there's enough information, the agent creates a case, if it isn't manually created.

### Email

For an incoming email, a case is created automatically based on the configured ARC rules. The agent then predicts and populates the configured default fields with the context from the email. 

## Update a case

The agent updates the fields configured by the administrator as follows:

- **For a case created from a conversation**: Select **Update from conversation** on the case form. The agent populates the fields with context from the ongoing conversation. Updated fields are highlighted, and a banner indicates that they were modified using AI.
- If there isn't enough context to populate the fields, the agent doesn't update them and displays a message indicating no changes.
- If the conversation is in wrap-up state, the agent checks if a case is created. If the case isn't created, the agent creates a new case and populates the case fields. If a case is created, the agent updates the specified fields.

- **For a case created from an email**: The agent populates the fields with context from incoming emails linked to the case. 

You can review the updated fields in **Audit history** if your administrator enables auditing for the entity. You need to have access to audit history to be able to view the AI updates.

> [!NOTE]
> If case fields configured for AI agent updates are updated manually, the AI agent doesn’t overwrite the manual updates.

## Next steps

 [Use autonomous follow-up and closure of cases](use-follow-up-closure.md)