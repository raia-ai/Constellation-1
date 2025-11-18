---
title: "Constellation1 eSign June 2021 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/16146335"
tags: ["Administration"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign June 2021 Release Notes Production Release: June 29, 2021  RELEASE SUMMARY  Constellaton1 eSign Email notifications: Define when"
long_description: "Constellation1 eSign June 2021 Release Notes Production Release: June 29, 2021"
---

# Constellation1 eSign June 2021 Release Notes

Production Release: June 29, 2021

##   
RELEASE SUMMARY

####   
**Constellaton1 eSign**

**Email notifications:** Define when users are cc’ed on signed documents.  
**Signing groups:** Group name is available in step 2, for easier signer management.   

**Managing fonts in markup tags:** Senders can manage the font size and style used in markup tags. 

**API updates:** Improved API functionality to allow more control over signing sessions.  

**Administrator functionality:** Administrators can now view users’ session info page. 

## Constellaton1 eSign

Email Notifications

Notifying key people associated to a signing session is important. You can now define who receives an email notification when a specific signer completes their signature session.

Example: when a buyer completes their signature session, the buyer’s agent can receive an email notification, letting them know the buyer signature session has been completed. 

When creating a signature session, 

*   Add the signers and those who should be notified.
*   Set the signing order.
*   Place those who should be notified after the signer who they should be notified when that signer complete their signing session.
*   In the “Type” column, select “CC-Recipient” as their role. An email notification will be sent to this person after the signer above them has completed their signing session.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/esign-2021-June-recip.png)

Signing Groups

We have added the ability to create signing groups for a signing session. Signing groups will allow any one person who is part of a group to sign on behalf of the group. 

When adding signers to a signature session:

*   Select “Show signing groups”.
*   Enter the group name in the “Signing Group” box. 
    *   The group name must be an exact match for the system to identify the signers as members of the group. 
    *   **Pro Tip:** Copy/paste the group name to ensure they match. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/esign-2021-June-Group.png)

When you add a signature box or other markup tag to a form, the group name will show as an option. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/esign-2021-June-Group2.png)

Manage Font Size and Type in Markup Tags

When creating a signing session, the session creator can now adjust the font size and font type that displays in the markup tags. This gives the session creator more control over the document. 

The font control shows in the options menu for the markup tag. Click the gear icon next to the markup to open the options menu.  

_**Note:** The signature markup only allows the font size to be adjusted. Font size and styles are available for all other markups._

|     |     |
| --- | --- |
| ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/esign-2021-June-fontcontrol.png)<br><br>_Signature Markup_ | ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/esign-2021-June-textesignfontcontrol.png)<br><br>Text Field Markup |

API Users Ability to Pause and Edit Signing Sessions

Customers who use our API are now able to pause and edit signing sessions that are in progress.  
This functionality is similar to the “in-app” functionality. 

Improved Administration Functionality

System Administrators and Group Administrators now have real time access to view specific users accounts, signing sessions and the status’ on the users session info page. 

This feature is permission based and allows: 

*   System administrators can view accounts of users who are part of their company.
*   Group administrators can view users’ account who are part of their group.