---
title: Constellation1 eSign January 2025 Release Notes
---

# Constellation1 eSign January 2025 Release Notes

Production Release: January 28, 2025

## Release Summary

**Archived Signing Sessions:** Added ability to copy archived sessions.   
**Signing Session Expiration:** Updated expiration time to UTC time.  
**Managing Templates:** Added delete confirmation popup.  
**Mobile View Usability:** Updated the zoom function on documents when creating a signing session.  
**Signing Session User Interface:** Updated label from Done to Submit.  
**Bug Fixes**

## Release Details 

Copy Archived Signing Sessions

Users can now copy archived signing sessions, enhancing the overall usability. 

This feature enables signing session creators to efficiently recreate past signing sessions, with their associated documents and tags for an efficient process to create a signing session. Under the Action menu, Copy has been add to the menu options. 

API users can also take advantage of this feature. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2025/01%20January/2025-Jant-eSign-CopyArcived.png)

Signing Session Expiration  
To provide a consistent user experience, we have updated the expiration time for signing sessions. 

When a session has an expiration date set, it will expire at 12:00 AM UTC (Coordinated Universal Time) on the selected date. 

Please note that UTC time is 5 hours ahead of Eastern Standard Time and 8 hours ahead of Pacific Standard Time. 

The Session Status will display the expiration date and time converted to your local time zone.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2025/01%20January/2025-Jant-eSign-ExprationTime.png)

  
Managing Templates  
We've added a secondary confirmation prompt when deleting documents from a template.

Previously, when creating or editing a template, selecting "Delete" from the action menu next to a document would delete the document without requiring confirmation, leading to unintended document loss. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2025/01%20January/2025-Jant-eSign-TemplateDeleteDoc.png)

Session Creation iOS Mobile View Document Zoom  

The eSign mobile view user experience now allows signing session creators using Apple iOS to zoom in and out on individual documents when creating a signing session.  

This targeted zoom functionality improves usability by enabling the session creators to focus on specific content and precise placement of tags and markups within a document.  

Zoom functionality for Android was updated in last months release. 

  
Signing Session User Interface

To enhance the signer's user experience, in the signing session, we have relabeled the "Done" button to "Submit" for a more intuitive interface. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2025/01%20January/2025-Jant-eSign-SubmitButton.png)

Bug Fixes

1\. GPES-5163

We fixed an issue with the billing section displaying unrelated invoices to some user accounts. 

Previously, in a specific use case, the billing section displayed invoices that were unrelated to their account. 

Now, this issue has been resolved. User accounts will only be able to see invoices related to their account and permissions. 

2\. GPES-5162 

We have fixed an issue that prevented certain signer actions from being enabled. 

Previously, when enabling the "Allow Delegation," "Include Attachments," and "Document Review" options for a signer, in the signing session the "Allow Delegation" and "Include Attachments" settings were not enabled or available as options to the signer in the signing session.

Now, this issue has been resolved. 

  
3\. GPES-5157

We have fixed an issue where the “Document Upload Required” setting was being toggled off after a signing session was sent. 

Previously, if a signer had the “Document Upload Required” option enabled, and the session creator then edited the signer's details, the “Document Upload Required” option would be toggled off. 

This issue has been resolved. When the Document Upload Required setting is enabled, it will remain enabled.

  
 4\. GPES-5123

We fixed an issue with signer tags being removed from a signing session in some cases when applying a template.

Previously, in a specific use case, applying a template to a signing session and adding other signer tags, then removing the template could inadvertently remove all signer tags from the document. 

Now, this issue has been resolved. 

5\. GPES-5020

We fixed an issue with duplicate contact records being created in a signing session.

Previously, when a user edited or updated a contact's information after adding them to a signing session, the system would save the contact as a new, duplicate record instead of updating the existing record. 

Now, this issue has been resolved. Updating a contact's information in a signing session will update the existing record without creating a new contact. 

6\. GPES-5159

We have fixed an issue with replacing a document during a signing session when creating a signing session using an android device.  

Previously, when creating a signing session, uploading a document, navigating to step 2, then returning to step 1 to replace the document, the old document was not being replaced with the new document. 

Now, this issue has now been resolved. Users can replace a document in a signing session when using an Android device as expected.