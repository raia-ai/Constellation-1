---
title: "Constellation1 eSign September 2023 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21582272"
tags: ["Administration"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign September 2023 Release Notes Production Release: September 26, 2023  RELEASE SUMMARY  Email Reply Label: Updated the sender’s nam"
long_description: "Constellation1 eSign September 2023 Release Notes Production Release: September 26, 2023  RELEASE SUMMARY  Email Reply Label: Updated the sender’s name on emails sent from eSign.  Bug Fixes RELEASE DETAILS  No-Reply Email Address We’ve removed the sender’s name from the From address on emails sent from eSign.  Previously, emails sent from eSign included the name of the signing session creator in the From field.  Now, emails sent from eSign will come from “No Reply noreply@esignonline.net.” Bug F"
---

# Constellation1 eSign September 2023 Release Notes

Production Release: September 26, 2023  

## RELEASE SUMMARY

**Email Reply Label:** Updated the sender’s name on emails sent from eSign.     
**Bug Fixes**

## RELEASE DETAILS  

No-Reply Email Address  
We’ve removed the sender’s name from the From address on emails sent from eSign.   
Previously, emails sent from eSign included the name of the signing session creator in the From field.   
Now, emails sent from eSign will come from “No Reply [noreply@esignonline.net.”](mailto:noreply@esignonline.net.%E2%80%9D)

Bug Fixes  
1\. GPES-3806  
We fixed an issue with certain PDF documents failing to upload to a signing session.   
Previously, when a user would upload a specific kind of PDF document to a signing session, the document would not fully upload.  
Now, this issue has been resolved. When uploading PDF documents, they will be added to the signing session as expected. 

2\. GPES-3828   
We’ve fixed an issue with the Action and Order menus not displaying when using eSign on a mobile device.  
Previously, when a user created a signing session using a mobile device, the Action and Order menu options didn’t display.   
Now, this issue has been resolved. eSign Mobile will work as expected and is consistent with eSign Desktop. 

3\. GPES-3879, GPES-4412  
We fixed an issue with placing, moving, and editing various form fields on a document in eSign Mobile.  
Previously, when various form fields were placed on a document, they were not movable or editable when creating a signing session in eSign Mobile.   
Now, this issue has been resolved and form fields are both movable and editable in eSign Mobile. 

4\. GPES-3898   
We fixed an issue with signer roles applied to custom templates not carrying over to new signing sessions.   
Previously, when a user created a signing session using a custom template that had been shared, the custom roles were not being applied to the signing session.    
Now, this issue has been resolved and roles that are part of custom templates will also be applied to new signing sessions as expected.  

5\. GPES-4435   
We fixed an issue with not being able to drag form fields onto a document when creating a signing session from a custom template.   
Previously, when creating a signing session using a custom template on eSign Mobile, the user was not able to drag form fields onto the document.   
Now, this issue has been resolved. Users will be able to add form fields to documents in custom templates when creating signing sessions on mobile devices. 

6\. GPES-4430  
We fixed an issue with re-adding users to a group after they were deleted.  
Previously, an administrator was not able to add a user back into a group after that user had been removed from the group. The reason was that even after the user was removed from the group, a record of them being part of the group remained in the database.   
Now, this issue has been resolved and administrators will be able to add/remove users from groups as expected.  

7\. GPES-4444  
We fixed an issue with creating packages with incomplete information.   
Previously, when a user tried to save a package that was missing required information, the package would not save, and the page would freeze in a permanent state of loading.    
Now, when a user tries to save a package that is missing required information, they will be presented with a message alerting them to provide it so they can save. 

8\. GPES-4434  
We fixed an issue with a signer’s signature and initials occasionally displaying in an oversized font.   
Previously, when a signer added their signature, initials, or other markup to a document, the font might have displayed in an oversized format, causing the document to be unusable. This was due to a combination of Windows 11 and a new Chrome browser.  
Now, this issue has been resolved and signatures and initials will display as expected on signed documents.