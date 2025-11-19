# Constellation1 Website & CRM Febrary 2023 Release Notes

Production Release: February 14, 2023&#x20;

## RELEASE SUMMARY

### Constellation1 CRM&#x20;

**Adding Contacts:** Manually added contacts will now be set to register by default. \
**Managing Action Plan Recipients:** Improved functionality when changing the number of recipients displayed. \
**Action Plans:** Updated to 2023 Homeowners and Annual Occasions Action Plans. \
**Lead Assignment Flow:** Improved usability of the lead Assignment Status workflow. \
**CoBrand Admin:** Improved function of the Delete button on the Dashboard Administration page. \
**New! User Permission:** Added Marketing Admin user permission. \
**UI Update:** Updated Add Task modal.&#x20;

### CRM Mobile App

**Updated Quick Email Flow:** Emailing a contact now opens Quick Email in the app. \
**Contact Record:** Recent Activity added to the Contact Detail page.&#x20;

**Constellation1 Websites**\
**Agent CMS Website Design:** Updated the team website design to display the agents’ cellphone number. \
**Security Updates:** Added reCAPTCHA to the consumer login page and improved system security. \
**Contact Forms:** Improved form accessibility.&#x20;

### Bug Fixes

**CRM:** \
Issue with the Performance Dashboard.

Quick Email Preview.

**Website:**\
Issue with the Home button showing twice. &#x20;

## CONSTELLATION1 CRM&#x20;

Registering Added Contacts\
We’ve updated the default setting when manually adding contacts to CRM. In the Add New Contact form, the option to register the contact will now default to Yes.\
The contact will automatically be registered unless the user selects No.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/02%20Feb%202023/2023-Feb-CRM-AddContact.png)

Managing Action Plan Recipients \
We’ve made it easier to manage Action Plan recipients. \
On the Manage Recipients page, if a user selects a number of recipients by checking the box next to their name, then changes how many recipients show on the page, the recipients that have been selected will still remain selected. Previously, the user would need to re-select these recipients.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/02%20Feb%202023/2023-Feb-CRM-APM-Recips.jpg)

Action Plan Manager \
In January, we updated the 2023 emails for the Homeowners Newsletter and the Annual Occasions Action Plans with fresh, mobile-responsive content.

Lead Categories \
In our December release, we added Assignment Status to the Lead Categories page, allowing the user to customize lead rules. In this release, we’ve improved the usability of the Assignment Status fields to make them more intuitive.&#x20;

When setting the Assignment Status, the user will no longer be able to pick from the Accepted by the Agent dropdown until the Assignment Status is set to Assigned or Unassigned. This update helps the user avoid setting an Accepted by the Agent option before picking from the required Assignment Status dropdown first.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/02%20Feb%202023/2023-Feb-CRM-AssignmentStatus.jpg)

CoBrand Admin – Dashboard Administration\
We’ve improved the usability of the Dashboard administration page in the CoBrand Admin by disabling the Delete button when no records are selected. \
In the Announcements and Widgets sections, the Delete button is now grayed out (disabled) to indicate there is no action available if no items are selected. \
When the user selects an announcement or widget, the Delete button will be enabled and turn blue, allowing the user to delete the selected items.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/02%20Feb%202023/2023-Feb-CRM-CobrandAdmin.jpg)

New! Marketing Admin User Permission\
We’ve added a new Marketing Admin permission to CRM. This permission allows users to manage company- and office-level Action Plans and the company-level Calendar.&#x20;

UI Update\
We’ve updated the user interface for adding an activity by removing duplicate titles:

&#x20;        ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/02%20Feb%202023/2023-Feb-CRM-AddActivity1Before.jpg)    ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/02%20Feb%202023/2023-Feb-CRM-AddActivityAfter.jpg)\
&#x20;_Before                                                                          After_

## CONSTELLATION1 CRM MOBILE APP   &#x20;

Quick Emails\
We’ve improved agents’ ability to email their leads and clients from the CRM mobile app. When the user taps the email icon, a Quick Email will open in the mobile app. The agent can select the recipients, compose their message, and send the email. \
Messages sent from Quick Email will be logged in the contact history. Previously, composing a message would open the native email application on the user’s mobile device.&#x20;

Contact Record \
We’ve updated contact records by adding Recent Activity to the Contact Detail page. This provides more information regarding recent activities related to the contact and provides the same functionality as the Recent Activity in the desktop version of the Contact Detail page.&#x20;

## CONSTELLATION1 WEBSITES

Agent Websites \
We’ve improved the agent team website design to display the agent’s cellphone number on their website instead of the office phone number when both are provided. Now, when the Mobile phone number field is populated, the agent website will display the cellphone number instead of the office number.\
This functionality is consistent with all agent CMS website designs. When the Mobile phone number is available, we will display that number on the agent’s website.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/02%20Feb%202023/2023-Feb-Website-TeamDesign.jpg)

Security Updates\
**Website Login Page for Consumers**\
We’ve updated the security on the consumer login page by adding Google reCAPTCHA. When a consumer attempts to log in to their account, Google reCAPTCHA works in the background to validate the login attempt. If Google reCAPTCHA suspects the login attempt is a bot or other automated process, it will present a reCAPTCHA challenge question. \
&#xNAN;_**Note:** A cookie will be placed on the consumer’s computer that will keep them logged in to their account when they return to the website._&#x20;

**System Security**\
We’ve made several updates to our website servers to guard against unauthorized system activity.\
We contract with White Hat and adhere to their website and system security standards. Whenever potential vulnerabilities are found, we address them immediately. \
Some of the vulnerabilities found and addressed in this release are:\
•    Content spoofing \
•    SQL injections\
•    Contact form hijacking \
We’re committed to keeping your websites safe and secure.&#x20;

Contact Forms\
We’ve enhanced contact forms at all levels and added screen-readable labels to all fields, bringing the forms into compliance with ADA guidelines. \
Note: We work with a third-party to scan our websites and alert us when there is a potential to improve usability and maintain ADA compliance.&#x20;

## BUG FIXES

**CRM** \
1\. We fixed an issue with the Performance Dashboard not filtering leads by the selected category on the Manage Leads page. \
Previously, when a user clicked a lead category on the Performance Dashboard, the user was taken to the Manage Leads page but the leads were not being filtered by the selected category. \
Now, when a user clicks a lead category on the Performance Dashboard, only the leads for the selected category will display on the Manage Leads page.&#x20;

2\. We fixed an issue with the Quick Email preview window showing only a portion of the email message.

Previously, when composing a Quick Email then clicking the Preview button, the preview window displayed only a portion of the email.

Now, when previewing a Quick Email message, the preview window will utilize the full preview window to display the email message.

**Website**\
1\. We fixed an issue with agent websites showing two Home buttons in the top navigation.\
Previously, when an agent website was activated without an MLS ID, the new website would show the Home button in the top navigation twice. \
Now, when a new agent website is activated without adding the agent’s MLS ID, the website will not add a second Home button to the top navigation.
