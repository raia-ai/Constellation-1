---
title: "Constellation1 eSign July 2022 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/17539697"
tags: ["Contact Management"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign July 2022 Release Notes Production Release: August 2, 2022  RELEASE SUMMARY Dashboard: Added ability to sort data by column heade"
long_description: "Constellation1 eSign July 2022 Release Notes Production Release: August 2, 2022  RELEASE SUMMARY Dashboard: Added ability to sort data by column header. User’s Name Displays in Header: Added logged-in user’s name to the header banner and improved how the profile menu displays.  Bug Fixes Release Details  Dashboard Improvements We’ve improved the new dashboard to allow users to sort the following data by column header: • Total Emails Delivered • Failed Emails • Opened Emails • Opened Invites On e"
---

# Constellation1 eSign July 2022 Release Notes

Production Release: August 2, 2022 

## RELEASE SUMMARY

**Dashboard:** Added ability to sort data by column header.

**User’s Name Displays in Header:** Added logged-in user’s name to the header banner and improved how the profile menu displays. 

**Bug Fixes**

## Release Details  

Dashboard Improvements

We’ve improved the new dashboard to allow users to sort the following data by column header:  
•    Total Emails Delivered  
•    Failed Emails  
•    Opened Emails  
•    Opened Invites  
On each of these pages, the column header is clickable to sort the information in either ascending or descending order. This will make it easier for users to find the signing session or document they are looking for.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20July/2022-July-eSign-DashboardSort3.png)

User’s Name Displays in Header

We’ve added the logged-in user’s name to the header section of the interface. This mimics the functionality available in eSign 1.0. 

We’ve also improved the display of the User Profile dropdown menu and added the ability for users to upload a profile picture. To update profile information and upload a photo, click on the Profile icon in the top right corner and navigate to Account.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20July/2022-July-eSign-NameInBanner.png)

BUG FIXES

1\. GPES-3199  
We fixed an issue with signing sessions not showing on the Sessions page when logged in as a manager or administrator. 

Previously, when logged in as a manager or administrator, signing sessions didn’t show even when navigating to the user’s Sessions page or applying filters to search for them. 

Now, signing sessions will show for managers and administrators and they will be able to use the filters to find specific signing sessions. 

2\. GPES-3190   
We fixed an issue with administrators sending signing session emails for sessions whose status should not have allowed emails to be sent. 

Previously, an administrator was able to send signing session emails even if the sender has paused the session or the session had a status where emails shouldn’t be sent.

Now, validation has been added to confirm the signing session is valid before email invites are sent. If the session is not valid, the administrator will receive a message that says the session is paused or otherwise blocked and an email can’t be sent.

  
3\. GPES-3191   
We fixed an issue with signers not being saved to a signing session. 

Previously, if a signer was listed multiple times in the sender’s address book with the same first name, last name, and email address, the system was not able to save the signer to the singing session.

Now, if there are multiple entries for a signer contact in the address book, the system will resolve this issue by using the most recently updated contact record.

  
4\. GPES-2989   
We fixed an issue with Session Viewed emails being sent multiple times to the sender and the signer of a session whenever the signer opened the signing session. 

Previously, when a signing session was opened, the session sender and signer would receive multiple confirmation messages. 

Now, when a signing session is opened, only one confirmation email will be sent to the sender and the signer. 

5\. GPES-2108   
We fixed an issue with a delay in launching Step 1 when creating a new signing session. 

Previously, when a new signing session was created, it could take up to 20 seconds to launch Step 1 and the indicator showing that the system was working did not display. 

Now, we have improved the code to launch Step 1 faster, and the user will receive a visual indicator that the system is working on backend processes.