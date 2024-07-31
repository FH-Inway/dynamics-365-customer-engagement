---
title: Dynamics 365 Field Service version history
description: Release schedule and version history for Dynamics 365 Field Service.
ms.date: 07/16/2024
ms.topic: overview
author: jshotts
ms.author: jasonshotts
---

# Dynamics 365 Field Service version history

## Release schedule

When a new version of Dynamics 365 Field Service releases, it becomes available in different geographic regions at different times. Use the table below to see when the next release will become available in the region of your environment.

For information about other updates to Field Service, visit the [Dynamics 365 and Microsoft Power Platform release plans](https://releaseplans.microsoft.com/?app=Field+Service).
For information about older versions, see [Version history archive](version-history-archive.md#field-service).

| Station | Region | Current version | Next version | Scheduled date |
| ------- | ------ | --------------  | -----------  | -------------  |
|**Station 1** |  *First Release*| [8.8.121.18](/dynamics365/field-service/version-history#8812118)  | TBD |08/02/2024 |
|**Station 2** |  *South America, Canada, India, France, South Africa, Germany, Switzerland, Norway, Korea*| [8.8.121.18](/dynamics365/field-service/version-history#8812118)  | TBD |08/16/2024 |
|**Station 3** | *United Arab Emirates, Japan, Asia Pacific, United Kingdom, Oceania* |[8.8.120.18](/dynamics365/field-service/version-history#8812018)  |  [8.8.121.18](/dynamics365/field-service/version-history#8812118)   |08/02/2024 |
| | *USG* | [8.8.121.18](/dynamics365/field-service/version-history#8812118)  | TBD |08/16/2024 |
|**Station 4** |*Europe* |[8.8.120.18](/dynamics365/field-service/version-history#8812018) |  [8.8.121.18](/dynamics365/field-service/version-history#8812118)   | 08/16/2024 |
|**Station 5** | *North America*|  [8.8.119.15](/dynamics365/field-service/version-history#8811915) |  [8.8.120.18](/dynamics365/field-service/version-history#8812018)   | 08/02/2024 |
|**Station 6** |*Government Community Cloud, DoD, China*  |  [8.8.119.15](/dynamics365/field-service/version-history#8811915) |  [8.8.120.18](/dynamics365/field-service/version-history#8812018)   | 08/02/2024 |
| | *Dedicated Scale Groups* |   [8.8.119.15](/dynamics365/field-service/version-history#8811915)  |   [8.8.120.18](/dynamics365/field-service/version-history#8812018) | 08/16/2024 |
>[!NOTE]
>
> - Dates in all regions except Government Community Cloud (GCC), USG, and China indicate the timing of the next automatic update. Dates in GCC, USG, and China indicate version availability; at this time, there is no automatic update for the GCC, USG, and China regions.
> - For all other regions, while most updates should be complete on the scheduled night, updates requiring more time may be completed during dark hours over the weekend indicated in the **Scheduled date** column.

## 8.8.121.18
(Includes Universal Resource Scheduling version [3.12.136.53](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213653) and Resource Scheduling controls version 1.2.75.241931)

- Fixed an issue where the agreement booking service task name was set by the incident type service task type instead of the incident type service task name.
- Fixed an issue when submitting feedback via global command bar in the Field Service app module.
- Field Service mobile app: Updated client-side logic to consider whitespace as empty in fields related to primary incident zype when performing validation. 

## 8.8.120.18
(Includes Universal Resource Scheduling version [3.12.135.34](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213534) and Resource Scheduling controls version 1.2.74.241731).

- Improved the duplicate validation logic on postal code form.
- Fixed an error on postal code form about an unterminated string literal when using the ‘#’ character.

## 8.8.119.15

This release is a hotfix on Field Service version [8.8.119.14](/dynamics365/field-service/version-history#8811914)

- Prevented copilot installation for CHN, DOC, USG, GCC, and SGP regions
  
## 8.8.119.14
(Includes Universal Resource Scheduling version [3.12.134.25](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213425) and Resource Scheduling controls version 1.2.73.241652).

- Booking Card view on Work Order form can now be customized to show or hide fields.
- Booking Card “Duration” changed to “Task duration” to make it more clear the duration is calculated based on service 
  tasks, not booking durations.
- Work order task width now dynamically displays based on length of task name.

## 8.8.118.21

This release is a hotfix on Field Service version [8.8.118.19](/dynamics365/field-service/version-history#8811819)

- Prevented copilot installation for CHN, DOC, USG, GCC, and SGP regions

## 8.8.118.19

This release is a hotfix on Field Service version [8.8.118.17](/dynamics365/field-service/version-history#8811817)

- Field Service mobile app: Fixed a bug which caused inspections question text to overlay on itself when exporting to PDF.
  
## 8.8.118.17
(Includes Universal Resource Scheduling version [3.12.132.9](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121329) and Resource Scheduling controls version 1.2.71.241432).

- You can now edit and delete child records of inactive primary work order incidents.

## 8.8.117.35

This release is a hotfix on Field Service version [8.8.117.34](/dynamics365/field-service/version-history#8811734)

- Prevented copilot installation for CHN, DOC, USG, GCC, and SGP regions

## 8.8.117.34

This release is a hotfix on Field Service version [8.8.117.32](/dynamics365/field-service/version-history#8811732)

- Field Service mobile app: Fixed a bug which caused inspections question text to overlay on itself when exporting to PDF.

## 8.8.117.32
(Includes Universal Resource Scheduling version [3.12.132.9](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121329) and Resource Scheduling controls version 1.2.71.241432).

This release is a hotfix on Field Service version [8.8.117.30](/dynamics365/field-service/version-history#8811730)

## 8.8.117.30
(Includes Universal Resource Scheduling version [3.12.131.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121311) and Resource Scheduling controls version 1.2.70.241042).

- Released optional country field on postal codes to support global postal codes with the same postal code number.
- Fixed a bug that prevented users from completing bookings when a second booking existed on the work order they don't have access to.
- New work order grid now properly filters on related entities.
- Fixed translation issues with finance and operations apps installation button in Field Service settings.

## 8.8.114.30

This release is a hotfix on Field Service version [8.8.114.29](/dynamics365/field-service/version-history#8811429)

## 8.8.114.29

This release is a hotfix on Field Service version [8.8.114.26](/dynamics365/field-service/version-history#8811426)

- Fixed an issue that caused issues with the booking control on the new work order form when changing time zones.

## 8.8.114.26
(Includes Universal Resource Scheduling version [3.12.131.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121311) and Resource Scheduling controls version 1.2.70.241042).

- The Use of Products Out of Stock setting in Field Service Settings keeps its value when enabling or disabling the Finance and Operations Integration setting.
- Tax Exempt and Sales Tax Code fields on Account will be hidden when disabling the Calculate Tax setting.
- Fixed a bug that caused some images to be corrupted when exporting inspection responses to PDF.

## 8.8.113.29

This release is a hotfix on Field Service version [8.8.113.28](/dynamics365/field-service/version-history#8811328)

## 8.8.113.28

This release is a hotfix on Field Service version [8.8.113.25](/dynamics365/field-service/version-history#8811325)

- Copilot summary control will no longer hide the system status drop down.
- The new work order grid control will now only evaluate ribbon rules for the selected row instead of for every row rendered all at once.


## 8.8.113.25
(Includes Universal Resource Scheduling version [3.12.130.10](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213010) and Resource Scheduling controls version 1.2.69.240991).

-  No updates were made to Dynamics 365 Field Service in this release.

## 8.8.112.28

This release is a hotfix on Field Service version [8.8.112.24](/dynamics365/field-service/version-history#8811224)

- Copilot summary control will no longer hide the system status drop down.
- The new work order grid control will now only evaluate ribbon rules for the selected row instead of for every row rendered all at once.

## 8.8.112.24
 This release is a hotfix on Field Service version [8.8.112.23](/dynamics365/field-service/version-history#8811223)

- Fixed a problem that prevented sub-status from appearing as a column in the work order grid view in the absence of a status column.
- Fixed a problem preventing 'Exports to Excel' command from the focused view when any column is filtered.

## 8.8.112.23
(Includes Universal Resource Scheduling version [3.12.129.28](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212928) and Resource Scheduling controls version 1.2.68.240862).

- Copilot in Field Service branding updates.
- Custom booking statuses no longer extend past their dropdown container.
- The quantity to bill updates for work order products when editing the quantity via grid control on the work order form.
- Customer phone number now populates in bookings created via work order form.
- The functional location list is now scrollable when viewing large hierarchies on work order form.
- Work order summary card no longer shows a completion bar when the work order has an estimated duration of 0.
- Work order status column now extends to the end of the details card on work order form.
- Work order priority no longer allows drop-down selection when set to read-only.
- Long functional location names will now wrap around when selecting a location on the work order from.
- Long work order statuses now truncate.
- Long work order service tasks names now truncate in the list view on the work order form.

## 8.8.110.18
(Includes Universal Resource Scheduling version [3.12.125.30](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212530) and Resource Scheduling controls version 1.2.64.240721).

- Updated translation of warnings when cancelling work orders.
- Double clicking now opens work orders from the work order list.

## 8.8.111.25 (2024 wave 1 early access, update 1)
(Includes Universal Resource Scheduling version [3.12.127.12](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212712---2024-wave-1-early-access-update1) and Resource Scheduling controls version 1.2.66.240663).

- The new work order list view no longer shows inactive records.
- The booked resources column has several improvements and now shows by default. This column is intended to only be used with the new work order grid control.
- New work order forms and views are no longer called ‘new’. Older forms are labeled ‘legacy’.

## 8.8.109.12
This release is a hotfix on Field Service version [8.8.109.10](/dynamics365/field-service/version-history#8810910)
(Includes Universal Resource Scheduling version [3.12.124.11](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212411) and Resource Scheduling controls version 1.2.63.240662).

## 8.8.109.10
(Includes Universal Resource Scheduling version [3.12.124.11](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212411) and Resource Scheduling controls version 1.2.63.240602).

## 8.8.108.12
This release is a hotfix on Field Service version [8.8.108.10](/dynamics365/field-service/version-history#8810810)
(Includes Universal Resource Scheduling version [3.12.123.34](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212334) and Resource Scheduling controls version 1.2.62.240661).

- Fixed a problem with Field Service updates when mixed reality security roles are applied.

## 8.8.108.10
(Includes Universal Resource Scheduling version [3.12.123.34](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212334) and Resource Scheduling controls version 1.2.62.240451).

Fixed several issues on the Get Started page:
- Buttons in cards now show in high contrast mode and lose focus while in side panes.
- Card height no longer changes when panning.

## 8.8.111.14 (2024 wave 1 early access)
(Includes Universal Resource Scheduling version [3.12.126.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121261---2024-wave-1-early-access-release) and Resource Scheduling controls version 1.2.65.240241).

-	Actuals generated through agreements populate the same fields as actuals generated from invoices that are linked directly to a work order.
-	The new work order experience is now the default for all new organizations.
-	Fixed a bug causing script error while adding service task type to a work order.
-	Added option in the Power Apps portal to make work order preview grid lookups editable.
-	Functional location hierarchy can now be visualized inline on the new work order location section.


