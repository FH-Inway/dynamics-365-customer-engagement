---
title: Best practices for configuring AI agents
description: This article lists the best practices that you can follow when you configure Azure and Copilot agents in your contact center.
ms.date: 04/14/2025
author: neeranelli
ms.author: nenellim
ms.reviewer: nenellim
ms.topic: best-practice
ms.custom: bap-template
ms.collection:
---

# Best practices for configuring AI agents

[!INCLUDE[cc-feature-availability-embedded-yes](../../includes/cc-feature-availability-embedded-yes.md)]

[!INCLUDE[cc-rebrand-bot-agent](../../includes/cc-rebrand-bot-agent.md)]

[!INCLUDE[cc-context-variable-considerations](../../includes/cc-context-variable-considerations.md)]

When you configure Azure and Copilot agents in Omnichannel for Customer Service, use the following best practices:

 - If you're using a Copilot AI agent to create a low latency greeting, make sure you configure the AI agent for the workstream. The AI agent is triggered before your custom routing logic is run. Learn more about best practices for Copilot agents in [Optimize agents to minimize latency](/microsoft-copilot-studio/guidance/optimize-minimize-latency).

- In a queue, if both AI agents (agents) and customer service representatives (service representatives or representatives) are available, set the agent’s capacity higher than all representatives. An agent’s capacity isn't reduced even after a work item is assigned to it. This ensures that any conversation routed to the queue is first picked up by the agent.

- When an agent escalates a conversation to a representative, make sure that the context variables are updated by the agent and the corresponding routing rules match correctly.

- When a conversation escalated by an agent comes back to the agent queue due to incorrect routing or context variables not being updated at runtime, the conversation isn't assigned to the same agent again. So, to prevent conversations from ending up in an infinite loop, you must configure a representative for the agent queue.

- Unlike representatives, agents aren't added to a "default" queue at the outset; you must add them from the Copilot Service admin center app.

- The message size must be less than or equal to 28 KB in all messaging channels. The size limit includes metadata like timestamps and tags. If you're a bot author or developer and want to pass complex cards or message types across channels, ensure that your message size doesn't exceed the limit. If you're integrating a custom channel via Direct Line, then make sure that the activity payload doesn't exceed the message size limit.


### Related information

[Integrate an Azure bot](configure-bot-azure.md)  
[Integrate a Copilot Studio bot](configure-bot-virtual-agent.md)  
[Configure bots to escalate and end conversations](../develop/bot-escalate-end-conversation.md)  
[Manage context variables](manage-context-variables.md)  
[Context variables for a bot](context-variables-for-bot.md)  

[!INCLUDE[footer-include](../../includes/footer-banner.md)]
