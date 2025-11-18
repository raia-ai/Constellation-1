---
title: "Constellation1 eSign July 2023 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/20963705"
tags: ["Troubleshooting"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign July 2023 Release Notes Production Release: July 19, 2023  RELEASE SUMMARY  Bug Fixes  RELEASE DETAILS Bug Fixes 1"
long_description: "Constellation1 eSign July 2023 Release Notes Production Release: July 19, 2023  RELEASE SUMMARY"
---

# Constellation1 eSign July 2023 Release Notes

Production Release: July 19, 2023 

## RELEASE SUMMARY

  
**Bug Fixes** 

## RELEASE DETAILS

#### Bug Fixes

1\. GPES-3825  
We’ve fixed an issue with the Read Tags function not completing when uploading files containing invalid tags or images as PDFs. 

Previously, when adding files with invalid signer tags or images in PDF format to a signing session, the system was not able to read the tags, preventing the Read Tags function from completing. 

Now, when these kinds of files are added to a signing session, the system will show a warning message alerting the user that the system could not read these tags. 

2\. GPES-3812  
We’ve fixed an issue with the signature pad not displaying the Select and Close buttons when a signer was reviewing a document in landscape view on the mobile version of eSign. 

Previously, when a signer attempted to create a signature on the Signature page while viewing a document in landscape view on their mobile device, the Select and Close buttons would not display. 

Now, this issue has been resolved. The Select and Close buttons will display on the signature pad when viewing a document in landscape mode on a mobile device.

3\. GPES-3803   
We’ve fixed an issue with text clearing from a document when removing anchor tags. 

Previously, when a user would remove anchor tags from a document, all the text would also be removed.  

Now when removing anchor tags, the system will not remove text from the document. 

4\. GPES-3227  
We’ve fixed an issue with a signer’s name not updating in the Signers dropdown in step 2 if the name was edited while creating the signing session. 

Previously, if a signer’s name was edited while the signing session was being created, the edited name did not update in the Signers dropdown in step 2 to add them to the session. 

Now, if a signer’s name is edited when creating the signing session, the updated name will show in step 2. 

5\. GPES-3790  
We’ve fixed an issue with the Initials tag not updating when the corresponding signer’s name is edited while creating a signing session.  

Previously, if a signer’s name was edited while creating a signing session, the Initials tag didn’t update to show the signer’s correct initials.

For example, if the signer’s name was Bob Smith and an Initials tag was added to a document, and then the signer’s name was updated to Robert Smith, the Initials tag would continue to show as BS instead of RS. 

Now, if a signer’s name is edited while creating a signing session, the Initials tag will update and display the correct initials. 

6\. GPES-3729  
We’ve fixed an issue with the line spacing in the Text Box Markup tag. 

Previously, when the Text Box Markup tag was added to a document, then stretched to span multiple lines, the space between lines would be reduced. 

Now, the line spacing in the Text Box Markup tag has been corrected. When a document is finalized, the line spacing will not be reduced. 

7\. GPES-3833   
We fixed an issue with users getting an error when returning to the Sessions page in eSign after completing a signing session. 

Previously, if a user created and sent a signing session, then opened it and completed their signing ceremony, they would receive an error message when they returned to the Sessions page. 

Now, this issue has been resolved. Session creators who are also signers will be able to return to their Sessions page after completing their signing ceremony without seeing an error message.