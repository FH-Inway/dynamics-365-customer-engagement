---
title: "Sample: Query the working hours of multiple users| MicrosoftDocs"
description: "Sample demonstrates how to retrieve the working hours of multiple users by using the QueryMultipleSchedulesRequest message."
ms.custom: 
ms.reviewer: pehecke

ms.suite: 
ms.tgt_pltfrm: 
ms.topic: sample
applies_to: 
  - Dynamics 365 Customer Engagement (on-premises)
helpviewer_keywords: 
  - sample for querying the schedules of multiple users
  - schedule and appointment entities
  - querying the schedules of multiple users sample, schedule and appointment entities samples
ms.assetid: 68c9d5d9-ab69-4b6f-9f84-a1d5919d549e
caps.latest.revision: 26
author: JimDaly
ms.author: nabuthuk
search.audienceType: 
  - developer
---
# Sample: Query the working hours of multiple users

This sample shows how to retrieve the working hours of multiple users by using the [QueryMultipleSchedulesRequest](/dotnet/api/microsoft.crm.sdk.messages.querymultipleschedulesrequest?view=dynamics-general-ce-9&preserve-view=true) message. You can download the sample from [here](https://github.com/Microsoft/PowerApps-Samples/tree/master/dataverse/orgsvc/CSharp).

This sample requires additional users that are not present in your system. Create the required user manually **as is** shown below in **Office 365** before you run the sample. Replace `yourorg` with the `OrgName` of your organization.

**First Name**: Kevin<br/>
**Last Name**: Cook<br/>
**Security Role**: Sales Manager<br/>
**UserName**: kcook@yourorg.onmicrosoft.com<br/>

[!include[cc-sample-note](includes/cc-sample-note.md)]

## How to run this sample

[!include[cc-how-to-run-samples](includes/cc-how-to-run-PA-samples.md)]

## What this sample does

The `QueryMultipleScheduleRequest` message is intended to be used in a scenario where it contains data that is needed to search multiple resources for available time block that match the specified parameters.

## How this sample works

In order to simulate the scenario described in [What this sample does](#what-this-sample-does), the sample will do the following:

### Setup

1. Checks for the current version of the org.
2. Retrieves the current user's information and also the user, that you have created manually in **Office 365**.

### Demonstrate

The `QueryMultipleScheduleRequest` message retrieves the working hours of the current user and the user that you have created manually.

### Clean up

Display an option to delete the records created in [Setup](#setup). The deletion is optional in case you want to examine the entities and data created by the sample. You can manually delete the records to achieve the same result.
 


[!INCLUDE[footer-include](../../../includes/footer-banner.md)]
