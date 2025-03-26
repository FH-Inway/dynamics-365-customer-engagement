---
title: Enable and configure sales qualification agent
description: Enable and configure the sales qualification agent in Dynamics 365 Sales to help sellers leverage AI for effective lead qualification.
ms.date: 03/19/2025
ms.topic: how-to
ms.service: dynamics-365-sales
ms.custom:
  - ai-gen-docs-bap
  - ai-gen-desc
  - ai-seo-date:10/04/2023
  - bap-template
  - ai-gen-description
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
search.app: salescopilot-docs
ms.collection: bap-ai-copilot
ai-usage: ai-assisted
---

# Enable and configure sales qualification agent

To help sellers leverage AI for lead research and qualification, enable and configure the sales qualification agent. Configure the details about your company and products you sell, your ideal customer profile, and other settings. These configurations help align the agent with your company's sales strategy and goals.

## Prerequisites

The sales qualification agent relies on existing Dynamics 365 Sales features to provide comprehensive research insights. While these features aren't mandatory for the functioning of the agent, they enhance the agent's capabilities and provide a more holistic view of the lead and account.

- [Copilot in Dynamics 365 Sales](enable-setup-copilot.md): Turn on Copilot to include the [lead summary](copilot-get-information.md#summarize-a-lead) and [account summary](copilot-get-information.md#summarize-an-account) on the **Lead insights** page.
- [Bing search](/power-platform/admin/geographical-availability-copilot): Provide consent for Bing search so that the agent can fetch relevant information from external websites and include it in its research synthesis.
- [New look](/power-apps/user/modern-fluent-design#enabling-the-modern-look-for-my-app-and-removing-the-toggle): Ensure that you enabled the new look for the Sales Hub app.

## Grant permissions to custom roles
<a name="grant-permissions"></a>

Question: Do we need this permission for public preview?

If you want to allow custom roles to access the agent, ensure that they have the necessary permissions.

Grant **User** level permissions for read, write, create, append, append to, and assign to the following entities:

- Sales Copilot Email Insight
- Sales Copilot Insight
- Sales Copilot Insight Card State

:::image type="content" source="media/sqa-custom-role-permissions.png" alt-text="Screenshot of the permissions to be granted for a custom security role.":::


## How to set up and activate the agent

Setting up the sales qualification agent requires collaboration between the tenant admin and the Dynamics 365 Sales admin. The tenant admin must first provide the necessary consents and configure capacity. Once these prerequisites are met, the Dynamics 365 Sales admin can proceed with configuring the agent to align with the company's sales strategy and goals.

The following steps describe how the tenant admin and the Dynamics 365 Sales admin can set up the agent.

<a name="open-the-sales-qualification-agent-settings-page"></a>
1. In the Sales Hub app, go to **Change area** in the lower left corner of the page and select **App Settings**.
1. Go to **General Settings** > **Copilot** > **Agents (Preview)**.
   The Welcome to Copilot agents (Preview) page appears.

   :::image type="content" source="media/sqa-configuration-page.png" alt-text="Screenshot of the sales qualification agent configuration page.":::
1. In the **Before you get started** section, complete the following prerequisites as a tenant admin:
   - Grant the required consents for the agent to use Bing search and Copilot Studio.
   - Manage capacity for the agent to run in your environment. The agent uses the same capacity as other Copilot features in Copilot Studio. [Learn more about messages and capacity](/power-platform/admin/manage-copilot-studio-messages-capacity?tabs=new).
   
   If the required consents are already granted and capacity is configured, you'll directly see **Get started** when you open the **Agents** page.
   
1. Select **Get started** to configure the agent.

1. In the **General** section, fill in details about your company, products you sell, and who should have access to the agent:

   | Field | Input | Example input |
   |-------------------------|-------------------------|----------------------------|
   | Team access | Select the security roles that need access to the agent, including the system administrator role. Typically, this field should include sales roles responsible for lead qualification. If you're selecting a custom role, ensure that [necessary permissions](#grant-permissions) are provided before adding it to the **Team access** list. | Salesperson, Sales Manager, System Administrator |
   | Company knowledge | Enter your company's name and website URL. The agent uses this information to tailor its research. | Company name: "Contoso Ltd." Website URL: "https://www.contoso.com" |
   | Value proposition of your offering | Describe the products or services you sell in natural language. This information helps the agent understand your offerings and generate lead qualification suggestions.| Cloud-based CRM solution that helps businesses streamline sales processes, improve customer relationships, and drive revenue growth. Our platform includes features such as lead management, opportunity tracking, email integration, and analytics.|

1. Adjust the [data refresh frequency](#adjust-the-frequency-of-research-data-refresh) in the **Data** section. By default, the data refresh frequency is set to **Medium**, which is ideal for most businesses.

1. In the **Research** section, review the resources that the agent uses to gather information about leads. The following sources are predefined and can't be edited:

   | Source | Description |
   |-------------------------|-------------------------|
   | Default basic research | Includes insights gathered from Copilot summaries, who knows whom, related opportunities, and so on. |
   | Default web research | Includes insights from predefined web resources to gather authentic information about the company's business, finances, and news. |

1. (Optional) [Add resources for custom web research](#add-web-custom-research).

1. In the **Qualification** section, define your **Ideal customer profile** (ICP) to help the agent identify leads that are a good fit for further engagement.

   | Field | Input |
   |-------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
   | Describe your ideal customer criteria | Specify the criteria for your ideal customer, such as industries you're targeting, company size, customer location, and job titles. |
   | Where to find this information | Verify the prepopulated fields from out-of-the-box Dataverse tables that'll be used for validating the criteria. If you want to use custom fields or table, [add a custom criteria for ideal customer profile](#add-custom-criteria-for-ideal-customer-profile).|

   :::image type="content" source="media/sqa-ideal-customer-profile.png" alt-text="Screenshot of the ideal customer profile configuration.":::

1. Review all the settings to ensure that they align with your company's sales strategy and goals. 
1. Select **Activate** to activate the agent.
   If you don't have enough capacity to activate the agent, a banner appears at the top of the page, indicating the same. You can select the Power Platform admin center link in the banner to add more capacity or save the agent settings and come back later to activate the agent.

After the agent gets activated, it starts working on the last 100 leads, with the newly created leads processed first.

## Add web custom research

You can add custom research sources to the agent's research synthesis. This addition allows the agent to pull information from specific websites that are relevant to your business and industry.

You can add up to five custom web research sources.

1. In the [sales qualification agent settings page](#open-the-sales-qualification-agent-settings-page), scroll down to **Research** > **Lead research** > **Custom web research**.
1. Select **Add custom research**.
1. Specify the insights you want the agent to get from the website. For example, you could say, evaluate if the company is "safe" to engage with based on its inspections, crashes, and safety ratings from the past 24 months.
1.  Add the URL of the website that provides the information. Ensure that the website is publicly accessible and doesn't require any authentication. Select **Next**.
1. In the **Provide instructions** dialog, specify the following details:
    1. Add specific instructions on what information you want the agent to extract from the website. For example, you could say, "Inspections, crashes, and safety ratings."
    1. Select the field that's most relevant to the information you want to extract. For example, if you're extracting information about the safety rating of the lead's company, select **Lead** > **Company Name**.

## Add custom criteria for ideal customer profile

Use custom criteria to define specific characteristics that are important for your ideal customer profile. You can select custom fields from Dataverse or add public URLs that provide relevant information about the lead's company. For example, you could add a custom criterion for "Company revenue" and map it to a custom field in Dataverse or provide a URL that lists the company revenue.
 
1. In the sales qualification agent settings page, scroll down to **Qualification** > **Ideal customer profile**.
1. Select **Add custom criterion**.
1. Enter the name of the custom criterion. For example, "Company revenue"
1. Take one of the following actions:
    - Select **Select Dataverse field(s)** and then select the field that you want to map to the custom criterion. 
    - Select **Or add public URL** and enter the URL of the website that provides the information. Ensure that the website is publicly accessible and doesn't require any authentication. In the **Provide instructions** dialog, specify the following details:
        1. Add specific instructions on what information you want the agent to extract from the website. For example, you could say, "Look at the last earnings report and find the company revenue for the last quarter"
        1. Select the field that's most relevant to the information you want to extract. For example, if you're extracting information about the revenue of the lead's company, select **Lead** > **Company Name**.
1. Select **Add**.
   The criterion is added to the list of ideal customer profile criteria.
1. Enter the value for the custom criterion. For example, if the company revenue should be greater than $1 million, enter **>1000000**.

## Adjust the frequency of research data refresh

By default, the research data is refreshed every three days. You can adjust the frequency of data refresh based on your business needs and available capacity. Question: What about new leads? Do they also follow this cadence?

1. In the sales qualification agent settings page, scroll down to **Data** > **Refresh options**.
1. Select the refresh option that's suitable for your business needs:
   - **High:** Data is refreshed every day. This option is ideal for businesses that need the latest information always. This option consumes more capacity.
   - **Medium:** Data is refreshed every three days. This option is suitable for businesses that need regular updates but don't require daily insights. This option balances performance and data accuracy.
   - **Low:** Data is refreshed every seven days. This option is suitable for businesses that don't need frequent updates and want to save capacity. This option consumes the least capacity.

## View usage consumption by the agent

You can start monitoring the usage consumption of the sales qualification agent after the agent is published. This information helps you keep track of the capacity consumed by the agent and the remaining capacity.

1. Open the [sales qualification agent settings page](#open-the-sales-qualification-agent-settings-page).
1. Select **View usage consumption** to view the usage consumption of the agent.
   This option is only available after the agent is published.
   Questions: Does this display the consumption by SQA or all the agents in D365 sales, including custom agents created by the customer?
   You're redirected to the Power Platform admin center, where you can view the usage consumption by product, agent, and environment.


## Deactivate the agent

If you no longer want the sales qualification agent to run in your environment or need to save capacity, you can deactivate it. When deactivated, new leads aren't processed, and existing lead insights aren't updated. However, insights already generated for existing leads will remain available.

1. [Open the sales qualification agent settings page](#open-the-sales-qualification-agent-settings-page).
2. Scroll down to the bottom of the page.
3. Select **Deactivate**.

The agent's status changes to **Deactivating** until the process is complete. Once deactivated, the status changes to **Inactive**.