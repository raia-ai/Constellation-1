---
title: "Constellation1 eSign October 2024 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/25124711"
tags: ["Reporting & Analytics"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign October 2024 Release Notes Production Release: October 28, 2024 Release Summary Signing Session Mobile Usability: Updated the doc"
long_description: "Constellation1 eSign October 2024 Release Notes Production Release: October 28, 2024 Release Summary Signing Session Mobile Usability: Updated the document viewer to zoom in or out on documents. Mobile Signing Session: Improved the signer’s workflow when signing documents.  Templates: Updated messaging when adding templates.  Bug Fixes Release Details Mobile View Document Zoom The mobile application's document viewing experience now allows users to zoom in and out on individual documents during"
---

# Constellation1 eSign October 2024 Release Notes

Production Release: October 28, 2024

## Release Summary

**Signing Session Mobile Usability:** Updated the document viewer to zoom in or out on documents.  
**Mobile Signing Session:** Improved the signer’s workflow when signing documents.   
**Templates:** Updated messaging when adding templates.   
**Bug Fixes**

## Release Details

Mobile View Document Zoom  
The mobile application's document viewing experience now allows users to zoom in and out on individual documents during a signing session, rather than zooming the entire page.   
This targeted zoom functionality improves usability by enabling users to focus on specific content within a document, unlike the previous zoom feature that affected the whole page. 

  
Mobile Signing Session  
We’ve improved the signers user experience when signer tags are placed close to the left margin of a document.   
When there isn't enough space to the left of the signer tag, the "Next" button will now appear to the right, ensuring the signer can easily see and touch the “Next” button. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/10%20October/2024-Oct-eSign-Next.jpg)

  
Updated Template Messaging  
We've added a new message to alert users when a template added to a signing session does not match the session document.   
This mismatch can cause problems, so the new message informs users of the discrepancy.  
When there is a mismatch, we’ve added the following message to alert the user. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/10%20October/2024-Oct-eSign-TemplateMessage.png)

  
Bug Fixes

1\. GPES-4804  
We fixed an issue with the second CC recipient on a signing session not being invited to the signing session.   
Previously, when a signing session had multiple CC recipients, the second recipient would not receive an email invitation. This would cause the session to stall with a status of "Pending Notification" or "Pending Invite".  
Now, this issue has been resolved, all those invited to a signing session will be notified at the appropriate time. 

2\. GPES-4922  
We fixed an issue with adding recipients to a bulk signing session not showing the signers name or action menu.  
Previously, when adding recipients to a bulk signing session, the signers name and action menu were not showing.  
Now, this issue has now been resolved. When signers are added to a bulk signing session, their names and the action menu will be shown.

4\. GPES-5014  
We fixed an issue that prevented group administrators from accessing usage reports. 

Previously, group administrator were not able to access the usage reports in the Group Tools section.   

Now, this issue has been resolved. Group users with the Admin role can run the group usage reports. 

5\. GPES-4564   
We fixed an issue with the display of the time zone when logged in as an administrator.

Previously, when an administrator viewed a user account that didn’t have a time zone set, the time zone displayed was the administrator’s own time zone.

Now, when an administrator views a user account that does not have a time zone set, the administrator’s view will not show any preselected time zone for the user.