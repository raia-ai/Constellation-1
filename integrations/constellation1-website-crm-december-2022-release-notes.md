# Constellation1 Website & CRM December 2022 Release Notes

Production Release: December 6, 2022&#x20;

## RELEASE SUMMARY

#### Constellation1 CRM&#x20;

**New! Automatic Lead Status:** Lead status now updates automatically based on specific criteria and customizable rules. \
**Simplified Admin Dashboard:** Updated UI on the Widgets and Announcements admin dashboard. \
**Contact Details:** Updated contact filter options and improved design of the Action Plan section. \
**Action Plan Manager:** Contacts assigned to one Action Plan can now be easily copied to another.&#x20;

#### Constellation1 Websites

**National Association of Realtors:** Updated how VOW and IDX listings display listing broker information to comply with NAR rule changes. \
**User Permissions:** Added a new permission to allow admins to delete agents from their assigned office. \
**Social Media Login:** Added Apple ID as login option.&#x20;

#### Bug Fixes

**CRM:**\
Issue with downloading action plans as a PDF.

**Website:**\
Issue with the number of listings displayed being limited to 12.&#x20;

## CONSTELLATION1 CRM&#x20;

New! Automatic Lead Status \
Lead status now updates automatically based on certain criteria and customizable Routing Rule. Previously, the lead status field was set manually. \
Now, when a lead is added to the CRM, the status may set itself automatically to Accepted, Not Accepted, Cool, Warm, or Hot based on category and the associated Routing Rule. On the Categories page, we’ve added four new fields for defining the category.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-Website-StatusCatergories.png)

The new fields are:\
•    Assignment Status – Is the lead assigned or not assigned? \
•    Accepted by the Agent – Has the agent accepted or not accepted the lead?\
•    Contact Status Event – What is the event needed for this category? \
•    Lead Status – What is the current status of the lead? \
Then on the Routing Rules page, we’ve added Lead Status Manager to the Routing Rules For… dropdown, where a rule can be created to set the status of the lead based on the category. The rule will automatically set the lead’s status, e.g., Cool, Warm, Hot, etc.  &#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-Website-StatusRules.png)

The lead status can be set for company, office, and agent leads.

Updated Widgets and Announcements Admin Dashboard&#x20;

We’ve updated how the administration dashboard for Widgets and Announcements displays. \
We’ve simplified the interface to remove unnecessary columns from the menu and added mouseover text to the action icons to tell users what they do more easily. \
The mouseover text indicates the following for each of the four icons, respectively:\
•    Published / Not Published \
•    Edit\
•    Preview\
•    Delete

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-CRM-Widgets.png)

Contact Details&#x20;

**Contact Summary Page**

We’ve updated the filter options on the Contact Summary page to be more intuitive and user-friendly. \
We replaced the term Filter By… with Advanced Filters and we changed the term All to No Filter. \
The functionality for both options remains the same. Advanced Filters is the new dropdown label for accessing the different filtering options and selecting No Filter will return all contacts, leads, and clients.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-CRM-ContactFiltersBefore.png) ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-CRM-ContactFiltersAfter.png)

Before                                            After

**Contact Detail Page**

We’ve updated the user interface on the Contact Detail page to provide a more intuitive user experience. In the Action Plan section, we’ve aligned the text for easy readability and added mouseover text to the Preview and Delete icons.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-CRM-APMMouseover.png)

Action Plans – Copy Recipients \
Users can now easily copy the recipients assigned to one Action Plan and add them to another Action Plan.&#x20;

On the Add Recipients page of an Action Plan, the user can select individual recipients or groups of recipients to assign to the Action Plan by clicking the corresponding tab. When opening the Add Recipients page, the default setting is to show all contacts.&#x20;

In this enhancement, we’ve added a dropdown to the Add Recipients page where the user can select an Action Plan to display the contacts who are assigned to that plan. The user can then easily tick the box next to the contacts’ names or select all and click Save to add them to the current Action Plan.&#x20;

For example, a user might be creating a new 2023 Action Plan and want to copy the contacts for a particular 2022 Action Plan to the new Action Plan.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-CRM-APMrecipents.png)

## CONSTELLATION1 WEBSITES

Updated NAR Policies&#x20;

The National Association of Realtors (NAR) has amended its policies regarding how the listing broker is displayed on VOW and IDX listings.

The new policies state that IDX displays must and VOW should identify the name of the listing firm and display the email or phone number provided by the listing participant in a prominent location in a readily visible color and typeface. Previously, displaying the email address or phone number was not required.&#x20;

To remain compliant with the IDX rules, we’ve updated the default property detail page layout to include the listing brokerage name and either their phone number or email address provided in the listing data from the MLS. \
MLSs must notify their members of the change and require them to include listing broker’s or listing agent’s phone number or email when creating a new listing.&#x20;

We also ask that you inform us when your MLS(s) implement(s) this new rule. Depending on how an MLS passes new data in their feed, there may be some data mapping needed on our side to ensure your feeds display correctly.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-Website-IDX.png)

**Note:** This update has been applied to the default Property Detail Page layout. If your company is using a custom layout, please contact your Constellation1 representative for more details.&#x20;

User Permissions&#x20;

We’ve added a new user permission to allow office administrators to delete users from their assigned office(s).&#x20;

The new permission is “Can Delete Users in Assigned Office(s).”

When this permission is enabled for an office administrator, they will be able to delete users from all offices they are assigned to.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/12%20Dec%202022/2022-Oct-Website-Permissions.png)

**Note:** Deleted user accounts are difficult to recover. Account recovery could incur a charge if we need to restore it from a backup. Check twice before deleting users and limit the number of admins with permission to delete users.

Consumer Social Media Login

In our last release, we improved how consumers can create an account by adding the ability to click a social media icon and use those same credentials to create their account. In this release, we’ve added the ability to use Apple ID to create an account. \
Accounts can now be created using Facebook, Google, Twitter, LinkedIn, and Apple ID. &#x20;

## BUG FIXES

**CRM** \
Fixed an issue with previewing and downloading Action Plan messages to PDF. \
Previously, when previewing an Action Plan email activity, then downloading the email as a PDF, the system would download the first email message in the Action Plan, not necessarily the email message being previewed when the Action Plan has multiple emails. \
Now, when previewing an email activity, then downloading the email as a PDF, the system will download the email activity that is being previewed.&#x20;

**Website**\
For agent channel websites, we fixed an issue with agents who don’t have a website only being able to display a maximum of 12 of their listings. \
Previously, on a company website, agents who didn’t have an active website could only display a maximum of 12 listings. \
Now, when an agent who does not have a website and has more than 12 listings, all their listings will show on the property search results page.
