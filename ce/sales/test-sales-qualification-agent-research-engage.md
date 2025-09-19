---
title: Test the Sales Qualification Agent
description: Learn how to test the Sales Qualification Agent in Dynamics 365 Sales and evaluate its accuracy and performance.
ms.date: 09/05/2025
ms.topic: how-to
ms.service: dynamics-365-sales
ms.custom: bap-template
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
search.app: salescopilot-docs
ms.collection: bap-ai-copilot
---

# Test the Sales Qualification Agent

After you've [configured the agent](configure-sales-qualification-agent.md), you can test its functionality, evaluate the quality and relevance of its research insights, validate the outreach emails and follow-up email responses (applicable only for **Research and engage** mode), test the handoff criteria.

## Prerequisites

Before testing the Sales Qualification Agent, ensure that you have the following requirements in place:  

### Create users for each role

Ensure that your test environment includes:

| User Role     | Details                                                                 |
|---------------|-------------------------------------------------------------------------|
| **Sellers**   | 3–4 users to whom the agent will hand off leads. Ensure that they have the seller role and valid email addresses.                    |
| **Supervisors** | At least 1 user to monitor the agent and intervene when necessary.    |

### Create test leads

When you're creating test leads, ensure that you have a diverse set of leads that meet the following criteria:

- **Company names**: Use real company and competitor names for leads to ensure meaningful research insights. As the agent relies on public data, using fictitious names doesn't yield relevant insights as there's no public data available for those names. If you need to use a fictitious name for demonstration purposes, consider using the fictitious organization **Proseware** (https://proseware.azurewebsites.net/).

- Leads must contain a valid email ID. As the agent will send outreach and follow-up emails to this ID, use your email ID or create a test email ID in your organization's domain to avoid sending emails to real customers.

- **Selection criteria**: When you configure the agent, you define the kind of leads the agent should process. For example, you can have agent process only **Hot** leads from a **Trade Show**. 
    - At least 10 leads that meet the selection criteria.
    - At least 5 leads that don't match the criteria and hence should be excluded from agent processing.
- **Target customer profile**: When you configure the agent, you define the characteristics of your target customer. For the purpose of testing, use a simple set of criteria. For example:
  - Industry: Technology
  - Annual revenue: Over $1 million
  - Job title: C-Level Executive
  - Location: North America
-  Out of the 10 leads that meet the selection criteria, ensure you have:

    - **High fit leads**: At least 3-4 leads that match at least 70% of the target customer profile criteria. In our example, the lead should meet at least 3 of the 4 criteria.
    - **Medium fit leads**: At least 3-4 leads that match between 50% and 70% of the target customer profile criteria.
    - **Low fit leads**: At least 3-4 leads that match less than 50% of the target customer profile criteria.
   > [!NOTE]
   > In the Research and engage mode, the agent also considers BANT (Budget, Authority, Need, Timeline) criteria and purchase intent signals to prioritize leads. For testing purposes, you can try to include these signals in your lead data or provide them as part of follow-up email to the agent.

  - **Note down your assessment(Optional):** In a spreadsheet, create a list of leads with the following columns and your assessment of their target customer profile fit, selection criteria match, and handoff status. This will help you validate the agent's behavior against expected outcomes:
    - Lead name
    - Company name
    - Lead source
    - Lead rating (Hot, Warm, Cold)
    - Email address
    - Industry
    - Annual revenue
    - Job title
    - Location
    - Selection criteria match (Yes/No)
    - Target customer profile fit (High/Medium/Low)
    - BANT criteria (Research and engage mode only)
    - Purchase intent signals (Research and engage mode only)


## Step 1: Review leads being processed by the agent

**Objective**: View the leads that are being processed by the agent.

After you start the agent, you can check if the agent picked the correct leads for processing.

1. In the Sales Hub app, go to **Leads**.

1. From the views drop-down, select **Leads Engaged by AI Agent**.  
   This list displays all leads that are being processed by the agent. This view is a point-in-time view. Leads stay in this view only while the agent is processing them. Once the agent hands off the lead to a seller or disqualifies it, the lead moves out of this view.

## Step 2: Validate research insights

**Objective**: Validate the quality and relevance of research insights generated by the agent.

1. In the Sales Hub app, go to **Leads**.  
1. From the views drop-down, select **Leads handed over by AI Agent**.  
   > [!NOTE]
   > In **Research and engage** mode, if you'd like to see the research insights even before the lead hand over, you can check the **Leads being processed by AI Agent** view and select a lead for which you've received an outreach email.
1. Open a lead and review the research insights. The summary appears at the top of the lead form and select **View full summary**. Evaluate for the following insights on the summary page:  

   - Accuracy of company background information, and connected accounts and contacts.
   - Relevance of the suggested action.
   - Accuracy of financial data and strategic priorities.
   - Completeness of insights based on available knowledge sources.
   - Accuracy and completeness of competitor analysis.
   - Presence of references from the configured knowledge sources for competitor insights.

## Step 3: Test outreach email

**Objective**: Confirm that the agent generates appropriate outreach email for leads.

1. In the Sales Hub app, go to **Leads**.  
1. From the views drop-down, select **Leads handed over by AI Agent**.  
1. Open the lead used in [the validating research insights section](#step-2-validate-research-insights).  
1. Complete one of the following steps depending on the mode of the Sales Qualification Agent you've configured:  

   - If the agent is in **Research-only** mode, select **Draft email** to view the outreach email generated by the agent.  
   - If the agent is in **Research and engage** mode, validate the outreach email you received from the agent in your test inbox.  
1. Evaluate the following information:
    - Relevance of the email content to the lead's context.  
    - Clarity and professionalism of the email tone.  
    - Inclusion of personalized elements such as lead's name and company.  
    - Overall effectiveness of the email in engaging the lead.  
    - Presence of unsubscribe option in the email footer.  
    - References from the configured knowledge sources.  
    - Accuracy of the recipient's email address.  

## Step 4: Test follow-up email responses and lead handoff

This section is applicable only for **Research and engage** mode. 

> [!NOTE]
> In **Research-only** mode, the agent hands off the lead to a seller after the research is complete and outreach email is drafted.

**Objective**: Confirm that the agent responds correctly to customers’ queries based on available knowledge sources and is able to hand off leads to sellers or disqualify leads as per the defined criteria.

1. When the agent is running, you'll receive an outreach email from the agent.
1. Reply to the email with different types of responses to simulate various customer interactions. You can use the following scenarios:
1. Simulate positive engagement from mock customers. For example, you can say you're interested in a product demo. Validate the following information:  

    - Handoff occurs to the correct seller/team.  
    - Lead appears in the **Leads handed over by AI Agent** view for sellers.  
    - The Lead research page includes handover summary (including insights and context).  

1. Simulate undetected intent by asking a question that is not covered by the knowledge base. Validate the following information:  
  
    - Agent doesn't respond and instead hands off to a seller.  
    - Lead appears in the **Leads handed over by AI Agent** view for sellers.  
    - Seller receives lead with handover summary and open questions.  

1. Simulate negative engagement. For example, you can say you don't want to be contacted anymore or say you aren't interested. Validate the following information:  

    - Lead appears in **Leads disqualified by AI agent** view in the lead grid for supervisors.  
    - Check notes or reasons for disqualification.  
    - Verify whether you're able to reassign the lead to a seller.  
