---
title: Parse event activity JSON to get agent context
description: Use this article to understand how you can parse the activity JSON to extract agent context.
ms.date: 04/30/2025
ms.topic: reference
author: neeranelli
ms.author: nenellim
ms.reviewer: nenellim
ms.custom: bap-template
ms.collection:
---
# Parse event activity JSON to get agent context

The Omnichannel for Customer Service context messages are sent as event activity to AI agents. Context information such as customer info, live work item, or conversation ID, is sent to the agent as part of an activity JSON. The JSON can be of type **startConversation** for most channels and **ConversationUpdate** for voice conversations. 

## Fetch and use context for agents in your agent code

 To process these context messages, use activity handlers and override them in your agent code. For information on how to use activity handlers, see [Event-driven conversations using an activity handler](/azure/bot-service/bot-activity-handler-concept?view=azure-bot-service-4.0&tabs=csharp&preserve-view=true).

In the following example, when the event activity is received, the `OnEventActivityAsync` method is called to fetch and use the context. 

```CSharp
protected override async Task OnEventActivityAsync(ITurnContext<IEventActivity> turnContext, CancellationToken cancellationToken)
        {
            if (turnContext.Activity.Name == "omnichannelSetContext")
           {
                // Replace with your logic to fetch the context from Activity.Value
                IActivity replyActivity = MessageFactory.Text($"Received context :  {turnContext.Activity.Value.ToString()}");

                // Replace with your logic to consume the context
                await turnContext.SendActivityAsync(replyActivity, cancellationToken);
            }
        }
```

## Next steps

[Code samples for parsing activity JSON](bot-context-json-samples.md)  

### Related information

[setContextProvider](reference/methods/setContextProvider.md)  
[Integrate an Azure agent](../administer/configure-bot-azure.md)  

[!INCLUDE[footer-include](../../includes/footer-banner.md)]
