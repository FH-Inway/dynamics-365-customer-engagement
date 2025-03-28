---
title: Copy an environment that includes omnichannel environment
description: Follow these steps to create a copy of a Dynamics 365 environment that includes omnichannel capabilities.
author: neeranelli
ms.author: nenellim
ms.reviewer: nenellim
ms.topic: how-to
ms.collection: 
ms.date: 03/03/2025
ms.custom: bap-template
ai.usage: ai-assisted
---

# Copy an environment that includes omnichannel environment

[!INCLUDE[cc-rebrand-bot-agent](../../includes/cc-rebrand-bot-agent.md)]


Omnichannel capabilities in Dynamics 365 Contact Center and Dynamics 365 Customer Service let you integrate external services and channels such as WhatsApp, Twilio, and Azure Communication Services. The integration parameters are stored in Dataverse tables. To create a copy of an environment that contains omnichannel capabilities, you can use the standard copy feature of model-driven apps. The integration parameters are copied to the new environment. However, you need to perform some additional steps to make sure that the copied environment works correctly. For example, if you have digital messaging channels, you need to delete and configure them again.

## Prerequisites

- [Omnichannel for Customer Service is configured in both the source and the target environment](/dynamics365/contact-center/implement/provision-channels#set-up-channels).
- Both the source and the target environment have the same set of channels enabled.
- [If you use unified routing, it's turned on in both the source and the target environment](../administer/provision-unified-routing.md).

## Copy the environment from the source

[Copy an environment](/power-platform/admin/copy-environment) and choose one of the following copy options:

- **Minimal copy**. Schemas and customizations only are copied. The source data isn't copied. [Turn off the channels](/dynamics365/contact-center/implement/provision-channels#turn-off-channels) and turn them back on. You can then create the channels and workstreams in the target environment, and no corrections are needed.
- **Full copy**. Everything in the source is copied. You need to [make a few corrections in the target environment](#configure-the-target-environment-after-copying-from-the-source) before you can start using it.

## Configure the target environment after copying from the source

If you chose the full copy option, it can take up to an hour for the data to appear in the target environment.

1. [Review and update the users, role mappings, and capacity profiles](../administer/users-user-profiles.md) in the target environment.

1. Review the queues and update the customer service representative memberships for representative assignments. Learn more in the following articles:

    - [Create and manage queues for cases](../administer/set-up-queues-manage-activities-cases.md)
    - [Create and manage queues for unified routing](../administer/queues-omnichannel.md)

1. If you have live chat configured in your source environment, update the live chat widget snippets in your website or portal to point to the target environment.

    The live chat widget snippets in the source are regenerated in the target environment. Make sure that you copy the new scripts from the target environment and update your website code to use them.

1. Make sure that the user features and chat settings are updated for the chat channel configuration in the target environment.

1. Recreate the channel configurations for each channel in the target environment. [Delete the existing channel or page](../administer/delete-channel.md) and dissociate the channel from the corresponding channel-specific workstream. Configure the channel again, and then update the channel-specific workstream with the newly configured channel.

   > [!IMPORTANT]
   > When you copy an environment with a configured voice channel, the Azure Communication Services resource is also copied. You can use one resource in one environment only. Therefore, disconnect the Azure Communication Services resource in the target environment. Otherwise, it can cause issues with the voice channel setup in both the source and target environments.


    - Voice:
      - [Configure a new voice channel](../administer/voice-channel-inbound-calling.md)
      - [Disconnect from Azure Communication Services resources](../administer/voice-channel-disconnect-from-acs.md)
      - [Connect to a different Azure Communication Services resource](../administer/voice-channel-acs-resource.md)
    - [Configure a new WhatsApp channel](../administer/configure-whatsapp-channel.md)
    - [Configure a new Facebook channel](../administer/configure-facebook-channel.md)
    - [Configure a LINE channel](../administer/configure-line-channel.md)
    - [Configure an Apple Messages for Business channel](../administer/configure-apple-messages-for-business-channel.md)
    - [Configure a Microsoft Teams channel](../administer/configure-microsoft-teams.md)
    - [Configure a custom channel](../develop/bring-your-own-channel.md)
    - [Configure an SMS channel using Azure Communication Services](../administer/configure-sms-channel-acs.md)
    - [Configure an SMS channel for Twilio](../administer/configure-sms-channel-twilio.md)

## Configure Copilot agents in the target environment

1. Delete any AI agents (agents) in Copilot Studio in all workstreams and the environment.

1. [Create an AI agent](../administer/manage-your-bots.md#add-an-agent) or connect a previously configured agent that's specific to the target environment and configure with channel workstreams.

1. Update the workstreams to use the new agent.

> [!NOTE]
> To use the same agent in Copilot Studio in the target environment, reconnect it to the new environment, and then follow [the configuration steps](/microsoft-copilot-studio/configuration-hand-off-omnichannel?tabs=webApp#manage-your-copilots-omnichannel-capabilities) to disconnect and reconnect the application. If you reconnect the agent to another environment, it will break the source environment.

> [!NOTE]
> When performing a copy of an organization, please note that survey bots from the source environment will not be functional in the target environment. To ensure proper functionality, create new survey bots in the target environment. For more information, visit Configure feedback surveys using Copilot Studio (preview) | Microsoft Learn [image](https://github.com/user-attachments/assets/7b91d12d-bce3-49c5-8d99-f7cae21fa217)


## Configure AI agents in Azure in the target environment

1. Delete any agents in Azure in all workstreams and the environment.

1. Reconnect the agent following the steps in [Configure the agent user](../administer/configure-bot-azure.md#integrate-azure-agents-with-omnichannel-for-customer-service).

## Configure real-time and historical analytics

1. To make sure that [real-time analytics reports](../administer/enable-realtime-analytics-dashboard-administrator.md) reflect information in the target environment, on the real-time analytics page in the Customer Service admin center, turn off **Enable Omnichannel real-time analytics**, and then turn it back on.

1. To make sure that [historical analytics reports](../administer/oc-historical-analytics-reports.md) reflect information in the target environment, on the historical analytics page in the Customer Service admin center, turn off **Enable Omnichannel historical analytics report**, and then turn it back on.

### Related information

- [Export and import app configuration data](export-import-omnichannel-data.md)
