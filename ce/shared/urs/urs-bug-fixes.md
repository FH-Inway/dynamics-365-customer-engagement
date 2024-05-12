
## Release schedule

When a new version of Universal Resource Scheduling releases, it becomes available in different geographic regions at different times. The table shows estimates for when the next release will become available in the region of your environment.

For information about other updates to Universal Resource Scheduling, visit the Field Service section of the [Dynamics 365 release plans](/dynamics365/release-plans/).
For information about older versions, see [Version history archive](../../field-service/version-history-archive.md#universal-resource-scheduling).

| Station | Region | Current version | Next version | Scheduled date |
| ------- | ------ | --------------  | -----------  | -------------  |
|**Station 1** |  *First Release*| [3.12.131.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121311)  | TBD | 05/17/2024 |
|**Station 2** |  *South America, Canada, India, France, South Africa, Germany, Switzerland, Norway, Korea* |  [3.12.131.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121311)  | TBD | 05/24/2024 |
|**Station 3** | *United Arab Emirates, Japan, Asia Pacific, United Kingdom, Oceania* | [3.12.130.10](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213010)  | [3.12.131.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121311) | 05/10/2024 |
| | *USG* |   [3.12.131.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121311)  | TBD | 05/24/2024 |
|**Station 4** |*Europe* |   [3.12.130.10](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213010)  | [3.12.131.1](/dynamics365/field-service/field-service-version-history-resource-scheduling#3121311) | 05/17/2024 |
|**Station 5** |  *North America*|  [3.12.129.28](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212928)  | [3.12.130.10](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213010)  | 05/10/2024 |
|**Station 6** | *Government Community Cloud, DoD, China*  |[3.12.129.28](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212928)  | [3.12.130.10](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213010)  | 05/10/2024 |
| | *Dedicated Scale Groups* |[3.12.129.28](/dynamics365/field-service/field-service-version-history-resource-scheduling#31212928)  | [3.12.130.10](/dynamics365/field-service/field-service-version-history-resource-scheduling#31213010)  | 05/17/2024 |

>[!NOTE]
>
> - Dates in all regions except Government Community Cloud (GCC), USG, and China are estimates of the next automatic update. Dates in GCC, USG, and China indicate version availability; at this time, there is no automatic update for the GCC, USG, and China regions.
> - For all other regions, while most updates should be complete on the scheduled night, updates requiring more time may be completed during dark hours over the weekend indicated in the **Scheduled date** column.

## 3.12.131.1

**Resource Scheduling Controls:** 1.2.70.241042

**Dataverse:** 4.0.121.1

- Horizontal scroll location is now maintained when switching views on the schedule board.
- List view on the schedule assistant now sorts all results instead of just the current page.
- Various tooltips have been improved.
- Fixed a bug that was cancelling all related bookings when a Project Operations user canceled a project requirement in an interday view. 
- Fixed a bug that was causing the requirement panel to crash when reordering tabs with active filters applied. 
- Fixed a bug that was mislabeling or and duplicating certain entities in the Related tab of a bookable resource form. 


## 3.12.130.10

**Resource Scheduling Controls:** 1.2.69.240991

**Dataverse:** 4.0.120.10

- Inactive organizational units are no longer displayed on the map
- Custom color setting for working/non-working hours are now used in aggregated views and the hourly view.
- Fixed a bug that prevented the selection of new some new tabs on the requirement pane. 
- Fixed a bug with syncing changes to a booking in the schedule assistant grid.
- Fixed a bug that was causing schedule board to crash when maximizing it from a very small window.
- Fixed a bug that was causing the details panel to not respect customized requirements detail view for resource type.


## 3.12.129.28

**Resource Scheduling Controls:** 1.2.68.240862

**Dataverse:** 4.0.119.28

- Fixed a bug that was preventing some users from rearranging schedule board tabs.
- Unchecked working days are no longer shown in the schedule board's list view.
- Various bug fixes to working days selection.
- Fixed a bug that was casing discrepancies between values on bookings made using the Create panel and how they were displayed in Map view.
- Requirement details are now shown properly in the Edit Booking panel. 
- Users can now change booking status in the Create Booking panel.

## 3.12.125.30

**Resource Scheduling Controls:** 1.2.64.240721

**Dataverse:** 4.0.115.30

- Fixed a bug that was disabling saved filters after a hard refresh for some users.
- Fixed a bug that was disabling the Delete button in a booking context menu in multiday views.
- Travel times of existing bookings are now updated when previous bookings are deleted.
- Booking statuses can now be updated while in multiday views in both List and Gantt modes.

## 3.12.127.12 - 2024 Wave 1 Early Access update 1

**Resource Scheduling Controls:** 1.2.66.240663

**Dataverse:** 4.0.117.12

- Users can now select which days of the week are visible on the schedule board.
- Added a vertical line to indicate current day while in aggregated views.
- Fixed bug where Move Bookings was not functioning properly in some time zones.
- Removed entry point to Schedule Board Settings from Booking Setup Metadata ribbon button.

## 3.12.124.11

**Resource Scheduling Controls:** 1.2.63.240662

**Dataverse:**  4.0.114.11

- Fixed a bug where edited search ranges were defaulting back to requirement start/end dates in Schedule Assistant.
- Improved Service Territory search box in the Select Resources panel.
- Requirement proposed and fulfilled durations now update automatically when bookings are made in Schedule Assistant.
- Fixed a bug that was impacting the Move Bookings feature for some users.
- Various security enhancements.
- Fixed a bug where double clicking on a booking was not opening the record while in the schedule board's hourly view.

**Resource Scheduling Controls:** 1.2.63.240662

## 3.12.123.34

**Resource Scheduling Controls:** 1.2.62.240661

**Dataverse:**  4.0.113.34

- Travel time calculates correctly for facility resources.
- All relevant fields now link to their respective entities in the requirements pane on the schedule board.
- The time zone setting in the schedule board settings is now reflected when moving a booking.
- Performance improvements when switching between schedule board tabs.
- Various security enhancements.
- Fixed a bug where double clicking on a booking was not opening the record while in the schedule board's hourly view.

**Resource Scheduling Controls:** 1.2.62.240661

## 3.12.126.1 - 2024 Wave 1 Early Access

**Resource Scheduling Controls:** 1.2.65.240241

**Dataverse:** 4.0.116.1

- Booking templates now feature updated colors and color picking tools.
- Fixed a bug that was impacting requirement grid column filters for some users.


## 3.12.122.50

**Resource Scheduling Controls:** 1.2.61.240223

**Dataverse:** 4.0.112.50

- Minor user experience bug fixes for requirement groups, map pins, and service territories.

## 3.12.121.18

**Resource Scheduling Controls:** 1.2.60.240112

**Dataverse:** 4.0.111.21

- Released new **Specify Pattern** version to break down long-duration or complex requirements.
- Bookings made in the Booking pane can now be set to any time granularity. 
- Fixed a bug where resources marked to not show on the schedule board were listed in the *Move to* dropdown.
- The number of child resources for pools and crews now show on the schedule board.
- Extra capacity of a resource now shows on the schedule board when available. 
- Booking rules now support HTML tags.
- The *Service territory* field on the *Select resource* filter now supports free text.

## 3.12.120.16

**Resource Scheduling Controls:** 1.2.59.233402

**Dataverse:** 4.0.110.19

- Introduced new version of the **Specify Pattern** control to break down multi-day requirements.
- Fixed a bug where users without delete permissions were shown a delete button on bookings.  
- Enabled free text in the service territory filter field.  
- Booking rules now support HTML tags on the new schedule board.
- When closing schedule assistant on the schedule board, users see their last open requirement tab.  
- The schedule board supports Internet Explorer mode of the Microsoft Edge browser. 
- Fixed a bug that caused an incorrect number of child resources to show on the schedule board for Crew and Pool resources.  
- The move option on the schedule board now respects the resource selection of the schedule board.
- Users can set specific times in the booking panel beyond the existing 15-minute granularity.

## 3.12.119.27

**Resource Scheduling Controls:** 1.2.58.232961

**Dataverse:** 4.0.109.27

- Performance improvements for API calls.
- Performance improvements when using the schedule assistant with lots of bookable resources.  
- Fixed a bug where bookings made with the schedule assistant are longer than resource's availability when search availability is manually set.  
- Fixed a bug that was causing an error message when opening the specify pattern control.
- Fixed bugs with apostrophes in requirement names and booking templates.
- PowerApps improvements with the specify pattern control.

## 3.12.118.19

**Resource Scheduling Controls:** 1.2.57.232831

**Dataverse:** 4.0.108.19

- In the map view on the schedule board, there are now visual indicators to show which record is selected. 
- Fixed a bug that was preventing some tooltips to not properly function while in list view. 
- Improved the schedule board resolution slider to honor the configured working time. 
- Fixed a bug that was displaying an error when booking certain full capacity requirements with a “Full Requirement” booking method. 
- Fixed bugs that were causing errors to be displayed when editing booking lengths in multi-day views.  

**Resource Scheduling Controls:** 1.2.57.232963

- Fixed a bug where apostrophes were shown as undefined when part of a book template name
- Fixed a bug where the Schedule Board requirements grid wasn't showing data. 

## 3.12.117.31

**Resource Scheduling Controls:** 1.2.56.232691

**Dataverse:** 4.0.107.30

- **Proportional booking visualization on aggregated schedule board views:** On daily, weekly, and monthly schedule board views, bookings are displayed as a proportion of their duration to the time block instead of filling the whole period.  
- When schedule assistant fails to create a booking, an error message now shows more information. 
- Fixed an issue that was causing the schedule board to load the wrong date when operating in specific time zones. 
- Fixed an issue that was causing selected resources to be displayed as undefined when using client extensions.  

**Resource Scheduling Controls:** 1.2.56.232963

- Fixed a bug where apostrophes were shown as undefined when part of a book template name
- Fixed a bug where the Schedule Board requirements grid wasn't showing data.  

## 3.12.112.5

**Resource Scheduling Controls:** 1.2.52.232511

**Dataverse:** 4.0.102.5

- **Capacity for resource search**: Resource search is now supported for organizations with more than 5,000 resources. 
- **Accessibility**: Implemented various accessibility improvements including increased support for screen readers, new visual labels, and more ARIA attributes. 
- Fixed an issue in the API where calling *msdyn_SearchResourceAvailability* consistently returned empty *AvailabilityIntervals* and *Characteristics*.
- Fixed an issue that led to the schedule assistant returning no available slots when a user entered information in the *Time from promised* field.  
- Fixed an issue where service territory filters were being reset when navigating through pages of a resource selection search.  

**Resource Scheduling Controls:** 1.2.52.232844
 - Various security enhancements  

## 3.12.116.5 - 2023 Wave 2 Early Access update2

**Resource Scheduling Controls:** 1.2.55.232482

**Dataverse:** 4.0.106.5

- **Retirement of the legacy schedule board:** The new schedule board is faster, more user-friendly, and accessible. It lays the foundation for new capabilities such as multiday scheduling and intelligent interactions.
- **Proportional bookings on multiday views:** Quickly determine a resource’s availability and utilization.
- **Multiple recurrences in work hours calendar:** Greater flexibility in resource scheduling, helping you meet business demands while adjusting to your workforce’s needs.
- Fixed an issue where rebooking and substituting on a requirement that got deleted was failing.
- Fixed an issue where the schedule board color wasn't being applied when saving the board setting with a new color.
- Fixed an issue where "Find Availability" in the new schedule board wasn't considering custom fields.

## 3.12.111.36

**Resource Scheduling Controls:** 1.2.51.232411

**Dataverse:** 4.0.101.36

- Fixed an issue where filtering resources by name didn't handle accented characters correctly.
- Fixed an issue where the “Time From/To Promised” fields weren't displayed during drag and drop operations on the schedule board if custom booking templates were enabled.
- Fixed an issue where the resource search bar on the schedule board was limited to the client-side records and couldn't search for all records when there were more than 5,000 resources.
- Fixed an issue where the schedule board didn't load completely after creating a new tab and switching back to the “Initial public view” tab. 
- Fixed an issue where the calendar icons on the “From” and “To” fields in the requirement group form didn't open the calendar picker. 
- Fixed several accessibility issues in the “Edit Booking Alerts Template” dialog, button labels, ARIA attributes, and screen reader compatibility.

## 3.12.110.18

**Resource Scheduling Controls:** 1.2.50.232152

**Dataverse:** 4.0.100.18

- Fixed a bug where the schedule board color wasn't applied when saving the board setting with a new color.
- Fixed a bug where the “Find Availability” feature in the new schedule board didn't consider custom fields.
- Improved accessibility for the “New Filter Layout” dialog, the “New Schedule Board Tab” button in portrait mode, and the “New Schedule Board” navigation panel.
- Fixed a bug where the schedule assistant requirement view wasn't picked up when the schedule assistant was launched from the book button.
- Fixed a bug where an incorrect “End Time” was populated on the booking custom entity when the “Default Booking Duration” had a Null value.
- Fixed a bug where an incorrect “End Time” was populated in the “Create Booking Panel” in Schedule Assistant when creating a booking for a requirement for the second time.
- Fixed a bug where the schedule board crashed when cold loading or creating a new tab in a small width window.
- Fixed a bug where the “Book & Exit” button reappeared after booking a requirement group, and it canceled the bookings.

## 3.12.114.1 - 2023 Wave 2 Early Access update1

**Resource Scheduling Controls:** 1.2.54.232001

**Dataverse:** 4.0.101.1

**Work hours calendar supports multiple recurrences**: Previously, you could only have one work hour recurrence per resource. With the added capability of multiple recurrences, you can now unlock greater flexibility in your resource scheduling to meet business demands further while adjusting to the needs of your workforce for employee retention and job satisfaction.


## 3.12.114.11 - 2023 Wave 2 Early Access (EA) Release

**Resource Scheduling Controls:** 1.2.54.232001

**Dataverse:** 4.0.104.11

**Legacy Schedule Board Retirement**: Fixed an issue where the legacy schedule board retirement message appears even if the new schedule board is already in use.

**Booking Status Icon Alignment**: Fixed an issue where the booking status icon doesn't align properly on short-duration bookings in the schedule board multiday views.

**Schedule Assistant Launch Issues Resolved**: Fixed an issue where the old schedule assistant launches when selecting **Book** on the requirement page.

## 3.12.109.2

**Resource Scheduling Controls:** 1.2.49.231861

**Dataverse:** 4.0.99.2

- Resource Utilization now shows for schedule board tabs beyond the 10th tab.
- If GPS tracking is enabled for a resource with a "location agnostic" location, a pin is displayed on the schedule board map for the last known location.

## 3.12.108.5

**Resource Scheduling Controls:** 1.2.48.231771

**Dataverse:** 4.0.98.5

- The "Ignore Duration" filter option in the schedule assistant now works correctly on the daily, weekly, and monthly views.
- The zoom control on the schedule board persists when switching between tabs.
- When switching between tabs on the schedule board, resource filters reset correctly.
- Search results in schedule assistant are paged correctly when performing repeated searches.


## 3.12.107.2

**Resource Scheduling Controls:** 1.2.47.231641

**Dataverse:** 4.0.97.2

- The duration field in the Create Booking pane now populates correctly when launched from the schedule assistant.
- Characters no longer dropped when typing quickly in the filter field on the open requirements subgrid on the schedule board.


## 3.12.106.7

**Resource Scheduling Controls:** 1.2.46.231371

**Dataverse:** 4.0.96.7

- Opening the map from Schedule Assistant now centers the viewing area correctly.
- Using the "Select Resources" option on the filter panel on the schedule board applies the resource filter correctly. Additionally, corrected a performance regression with this control.
- Selecting a resource in Schedule Assistant populates the correct start date, end date, and duration in the Create Booking panel based on the resource availability and the requirement.


## 3.12.105.25

**Resource Scheduling Controls:** 1.2.45.231281

**Dataverse:** 4.0.95.25

- More performance improvements for loading daily/weekly/monthly views on the schedule board.
- Bug fixes

    - Custom schedulable entities where the relationship to the requirement entity was created manually are no longer be blocked from scheduling on the legacy schedule board.
    - Colors across the resource card, summary row, and booking now align correctly based on utilization.
    - When scheduling entities that contain autonumbered content in the name field, the name of the related booking created is now be generated correctly.

## 3.12.104.14

**Resource Scheduling Controls:** 1.2.44.231111

**Dataverse:** 4.0.94.14

- Using ctrl/cmd+scroll on the schedule board adjusts the date range granularity.
- The error message when encoding an address for a resource now tells you when an error occurs because the address is too long.
- When manually creating bookings on the schedule board using the "Fixed" booking method, you can now partially fulfill a requirement by reducing the duration.
- Bug fixes:
   - The legacy schedule board no longer shows system tabs.
   - On the legacy schedule board, changes to tab settings are saved correctly.


## 3.12.103.21

**Resource Scheduling Controls:** 1.2.43.230971

**Dataverse:** 4.0.93.21

This release is a hotfix on Unified resource scheduling [3.12.103.12](/dynamics365/field-service/field-service-version-history-resource-scheduling#31210312).

- Creating a booking on directly on the legacy schedule board now opens the lookup pane to select a parent requirement.
- Custom business process errors messages now show on the legacy schedule board correctly.

## 3.12.103.12

**Resource Scheduling Controls:** 1.2.43.230971

**Dataverse:** 4.0.93.12

- A board refresh on the schedule board refreshes all fields that were added to the bookable resource cell template.
- The map on the schedule board now supports routes containing more than 25 stops.
- More performance improvements when loading the schedule board, primarily focused on optimizing the number of API calls.
- Bug fixes:
     - Removing the organizational unit field from the default *Bookable Resource Booking* form no longer causes an error on the form.
     - Tooltips now work across all views when a *Bookable Resource Booking* doesn't have a parent *Resource Requirement*.


## 3.12.102.24

**Resource Scheduling Controls:** 1.2.42.230871

**Dataverse:** 4.0.92.24

This release is a hotfix on Unified resource scheduling [3.12.102.17](/dynamics365/field-service/field-service-version-history-resource-scheduling#31210217).

- Creating a booking on directly on the legacy schedule board now opens the lookup pane to select a parent requirement.
- Custom business process errors messages now show on the legacy schedule board correctly.

## 3.12.102.17 - 2023 wave 1 release

**Resource Scheduling Controls:** 1.2.42.230871

**Dataverse:** 4.0.92.17

- Multiple performance improvements to reduce schedule board load times. Visible performance improvements vary depending on the amount of data loaded on the schedule board.
- Replaced deprecated OData API calls across all Universal Resource Scheduling controls.
- On the schedule board, the default unit for the duration field on the create and edit booking panels is now hours. Entering a number in that field without a unit 	will be interpreted as hours, instead of minutes.
- Bug fixes:
  - Day names on the calendar control in the requirements subgrid of the schedule board are now localized correctly.
  - Booking rules no longer block Schedule Assistant from closing.
  - Deselecting a resource on the schedule board is now reflected on the map, resetting the view.
  - (Project Operations) Maintain bookings mode no longer constantly refreshes on daily/weekly/monthly views.
  - In the requirements subgrid on the schedule board, filtering requirement groups by territory now behaves as expected.
  - The end date on the create booking panel from the daily/weekly/monthly views on the schedule board now reacts consistently and no longer adds an extra day in some cases.
  - Drag and select to create a new booking on the schedule board now works after creating a booking by drag-and-drop.

## 3.12.101.3 - 2023 wave 1 early access update 1

**Resource Scheduling Controls:** 1.2.41.230631

**Dataverse:** 4.0.91.3

- Bug fixes
  - Fixed labels on the schedule board.

## 3.12.98.7

**Resource Scheduling Controls:** 1.2.38.230543

**Dataverse:** 4.0.88.7

- Color saturation on booking templates on the schedule board has been increased to improve visibility, particularly for customized colors.
- Booking tooltips now have a link to open the parent record in a modal, and an icon to open in a new window.
- Locked icons are now shown on booking templates.
- Bug fixes
	- Users without bulk edit privileges are blocked from editing multiple bookings simultaneously on the schedule board.
 	- Maintain Bookings mode will no longer cause repeated refreshes on daily/weekly/monthly views on the schedule board.
 	- The zoom settings will now be maintained and applied correctly when switching between tabs and views on the schedule board.

## 3.12.100.2 - 2023 Wave 1 Early Access (EA) Release

**Resource Scheduling controls:** 1.2.40.230251

- The new schedule board is now the default for all organizations, and the legacy schedule board is [officially deprecated](../../common-scheduler/deprecations.md).

## 3.12.97.18

**Resource Scheduling Controls:** 1.2.37.230406

**Dataverse:** 4.0.87.17

-  Bug fixes
   - The schedule board will now load correctly when using lock options on bookings.


## 3.12.97.9

**Resource Scheduling Controls:** 1.2.37.230406

**Dataverse:** 4.0.87.9

- Removed error logging for extraneous "Failed to resolve sorting" issue that was bloating error logs.
- Bug Fixes
  -  When a user moves a booking in the weekly view, the date in the prompt message now correctly displays the date the booking is moving to instead of the first day of that week. The date selected is consistent with the original date. For example, move it from Monday to Monday the following week.
  -  Icon for locked bookings now shows on the schedule board.
  -  Resource Scheduling Optimization Add-in options on the schedule board for single resource optimization behave similarly to the legacy schedule board.
  -  The schedule board now always respects the start/end times in the working time settings.
  -  Selecting a resource on hourly/weekly/daily view on the schedule board now opens the Create Booking pane as expected.
  -  Switching from daily to hourly view on the schedule board no longer occasionally crashes the schedule board.

## 3.12.96.38

**Resource Scheduling controls:** 1.2.36.230171

- This release fixes the create/update booking failures with organizations running custom plugins to create/update bookings seen with URS version 3.12.96.25.

## 3.12.96.25

**Resource Scheduling controls:** 1.2.36.230171

- Improved data caching on schedule board, reducing the load time on the schedule board or when switching between tabs.
- Decreased the number of times the schedule board refreshes on load, particularly for Schedule Assistant, reducing screen flicker and page loading times.
- Bug fixes
  - Creating a booking with one-minute duration now behaves as expected.
  - Typing quickly in the search or filter boxes on the schedule board no longer closes the input box.
  - Changing the nonworking hours color on the schedule board no longer requires a page refresh to see the selected color.
  - The time on the schedule board now always respects personalization settings at across zoom levels.
  - When a user selects the "Rebook" option, the suggested start time is the start time on the existing booking.
  - The schedule board no longer crashes when switching between tabs with different timezones.

## 3.12.92.14

(Includes Resource Scheduling controls version 1.2.35.223541).

- Race condition resulting in incorrect resources to be used in loadBookingAggregates.
- New schedule board update for customizations to resource templates.
- Booking alert panel crash when alerts have been deleted.
- Fixed a bug that prevented creating a new entity in the Field Service setup wizard.
- Improved error handling for geocode action.
- Improved resource search from Schedule Assistant.
- Fixed a bug that prevented viewing bookings for crew members with schedule board refresh.
- Improved booking tooltip for lookup fields from related entities.
- Requirements can be scheduled multiple times while first one is still booking.
- Fixed a bug where drag and drop booking in new schedule board before booking is complete results in duplicate booking.
- Improved formatting function to display duration in day view and negative duration.

## 3.12.91.2

(Includes Resource Scheduling controls version 1.2.31.222853).

Bug fixes for the new schedule board include:

- Added booking tooltip error showing work order information on custom views.
- Added booking tooltip error when start time and end time are missing.
- Fixed a bug in the details panel when selecting lookup fields for a requirement.
- Improved details panel that was missing some field values for resources.
- Resource search now searches as text is entered.
- Fixed a bug where drag and drop wasn’t showing estimated travel time for custom booking templates.
- Fixed a bug where the Show Travel Duration setting was always active. 
- Added schedule assistant errors when editing text in the search box.

## 3.12.90.2

(Includes Resource Scheduling controls version 1.2.30.222701).

- Corrected "Get Started" banners and messaging for Bing Maps integration for European customers.
- The Remaining Duration field will now update correctly when bookings are manually adjusted on the schedule board.
- Filter is now correctly applied from the Maintain Bookings option for team members associated to a project record.
- Soft bookings will now interact with the expand/collapse options as expected on the schedule board.
- Autorefresh on the schedule board will now update the color of bookings based on priority.
- Fullscreen icon will now show on customized booking tooltip views on the schedule board.
- Adding a custom web resource to a schedule board tab will no longer cause other tabs to show an HTTP 404 error.
- Selecting a resource (with no requirement selected) on the schedule board should now open the details panel as expected.

(Includes Resource Scheduling controls version 1.2.30.222771)

(This release is a hotfix on Resource Scheduling controls version  1.2.30.222701)
 - Fixed a bug in which the NSAT survey and introductory video weren't displaying for some environments after being upgraded.
 
## 3.12.88.3 - 2022 wave 2 early access update 2

(Includes Resource Scheduling controls version 1.2.29.222551).

## 3.12.85.11

(Includes Resource Scheduling controls version 1.2.26.222492).

Scheduling bug fixes to the new schedule board:

- Bookings created from cases weren't re-rendered the right priority when Schedule Board is refreshed. 
- Booking tile text visibility on selection for light status color.
- Schedule Type settings  application.
- "move to" Dialog on bookings rejects selected resource and blocks move.
- Two bookings are merged into one booking in Daily view.
- Details panel not rendering some field values.
- Estimated Arrival time sets the End time of the booking with incorrect value.


## 3.12.84.3

(Includes Resource Scheduling controls version 1.2.25.222292).

Scheduling bug fixes to the new schedule board:
 - Custom filter control doesn't work.
 - Can't Drag and Drop onsite Work order to Organization Crew Resource with Auto Update Booking Travel Enabled.
 - The Booking records aren't focused on the Map.
 - Ability to show more results on left panel filter dropdowns.
 - Appointments aren't respected as "busy" when searching for availability for requirements.
 - Requirements details present on Schedule Assist are showing the fields with no value.
 - Details pane isn't showing the right view.  


## 3.12.87.3 - 2022 wave 2 early access update 1

(Includes Resource Scheduling controls version 1.2.28.222201).


