---
title: "Constellation1 Website & CRM May 2022 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/16892663"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Website & CRM May 2022 Release Notes Production Release: May 9, 2022  RELEASE SUMMARY Constellation1 CRM  Reports: Improved Action Plan"
long_description: "Constellation1 Website & CRM May 2022 Release Notes Production Release: May 9, 2022  RELEASE SUMMARY Constellation1 CRM  Reports: Improved Action Plan Manager report to track email open rates in real time.  Updated Login Permissions: Added ability for broker administrators to log in as an agent with full access to the agent account. Contact Details: Removed the Time Zone field. Architecture: Upgraded email servers and services and improved MLS data access.  CRM Mobile App Contact Sync: Removed v"
---

# Constellation1 Website & CRM May 2022 Release Notes

Production Release: May 9, 2022 

## RELEASE SUMMARY

#### Constellation1 CRM 

**Reports:** Improved Action Plan Manager report to track email open rates in real time. 

**Updated Login Permissions:** Added ability for broker administrators to log in as an agent with full access to the agent account.

**Contact Details:** Removed the Time Zone field.

**Architecture:** Upgraded email servers and services and improved MLS data access. 

#### CRM Mobile App

**Contact Sync:** Removed validation for country code on phone numbers when using Contact Sync. 

#### Constellation1 Websites 

**Public Records Listing Pages:** Enabled sitemaps for public records pages.

**News Articles/Blog:** Updated field names to be more intuitive.  

#### Bug fixes

## CONSTELLATION1 CRM 

Action Plan Manager Report – Real-Time Open Rate

Brokers and Agents can understand a lot about their leads and the effectiveness of their messaging when they track email open rates. 

We’ve improved the Action Plan Manager report to show the real-time email open rate. Now the CRM will update the report mere seconds after a recipient opens an action plan email. 

To view the report, go to Contacts, then Reports, and select the Action Plan Manager report. The real-time open rate will appear in the right-most column.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-May-APM%20Report.png)

Previously, the system would process this information overnight, so the most accurate open rate would only be available the next day.  

  
Broker Admin – Login as an Agent 

Broker administrators can now log in to the CRM as an agent for more flexibility when managing these accounts. 

This feature was previously available just for the Website admin and has now been added to the CRM. It allows the administrator to log in as a particular agent and have full access to that agent’s CRM account. Only users with Cobrand Admin permission will have access to this feature.

To log in as an agent, go to Administration, Cobrand Admin, then click on the Accounts tab. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-May-Admin-Login.png)

Contact Details – Time Zone

We’ve removed the Time Zone field from the Contact Detail page, simplifying how contact details display. This field served no functional purpose and caused some confusion. 

The Time Zone previously displayed in the contact record on the Contact Details tile (see below). 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-May-Contact%20Time%20zone.png)

Architecture Improvements

**Email Servers**  
We’ve added new email servers to our network. These new servers expand our capacity, improve stability, and allow us to send outgoing emails more efficiently.

We’ve also updated our Feedback Loop email service. This service helps manage outgoing emails, opt-outs, and unsubscribe requests. Feedback Loop is designed to maintain a good sender reputation with recipient email hosts to ensure the highest delivery rate possible. 

**MLS Data**   
We’ve improved access to MLS listing data, making it more effective and reliable in CRM. 

Previously, the CRM would connect to a RETS server to access listing data. Now, it connects directly to our internal listing database. This is particularly useful for providing the most up-to-date listing information when creating flyers or CMAs. 

## CRM MOBILE APP

Sync Contacts

We’ve removed country code validation for new contact phone numbers when using the Sync Contact feature in the CRM mobile app. This update will reduce the possibility of creating duplicate contact in CRM. 

For example, a cell phone might store a contact’s phone number with the country code: +1 808-555-1212.

Previously, if the contact was already in the CRM without the country code in their phone number (808-555-1212), the CRM might not have matched it to the existing contact, causing the system to create a duplicate contact without the country code in the phone number. Now the system will recognize that the phone numbers are functionally identical and not create a duplicate contact.

## CONSTELLATION1 WEBSITES

Public Records Listing Pages 

We’ve added the ability to have sitemaps created for public records listing pages. This can improve the SEO value of the public records pages on our customers’ websites because sitemaps help search engines find real estate-related information, and can help improve search engine rankings. 

Sitemaps for public records pages are not enabled by default. To have this feature enabled, please contact your Constellation1 representative for requirements and details. 

News Articles/Blog

We’ve recently updated the workflows for creating and managing blogs. Now we have updated field names in the Blog Admin section. The updated field names are more intuitive and will give the user a clearer understanding of the purpose of those fields. 

## BUG FIXES

#### CRM 

*   Fixed an issue with the token field in the content editor not opening and showing the available tokens. Previously, the dropdown did not open when clicked. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-May-APM-Tokens-bugfix.png)

*   Fixed an issue with Action Plan emails not being published. Previously, when clicking the Publish button on an email, the email would not be published. 

#### Website  

*   Fixed an issue with school data not showing on Public Records Listing Detail page. Previously, the public records listing page was not showing school information.