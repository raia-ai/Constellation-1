---
title: Constellation1 eSign June 2023 Release Notes
---

# Constellation1 eSign June 2023 Release Notes

Production Release: June 21, 2023 

## RELEASE SUMMARY

**Signature Tags:** Updated Signature tags to display long signatures correctly.    
**Bug Fixes**

## RELEASE DETAILS

Updated Signatures Tags   
We’ve improved the way long signatures display in eSign. Previously, when a signer had a particularly long name, their signature would wrap to the next line and fall outside of the borders of the Signature tag. The wrapped overset text wouldn’t display on the final document, effectively cutting off the end of the signature.  
We’ve adjusted the behavior of the Signature tag so it displays signatures in full. The First Name and Last Name fields in eSign each have a limit of 100 characters, so signatures may be up to 200 characters long, including the spaces. The signature will stay the width of the Signature tag and wrap to as many lines as needed. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/06%20June%202023/2023-June-eSign-Signature01.png)  
New Signature tag behavior – During a signing session

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/06%20June%202023/2023-June-eSign-Signature02.png)  
Final document with complete signatures displayed

  
Bug Fixes

1\. GPES-3814  
We’ve fixed an issue with eSign not recognizing Signer tags when multiple documents are uploaded to a signing session.

Previously, if a signing session was created with multiple documents with embedded Signer tags, and the session creator clicked Read Tags, eSign would only recognize the tags in the first document uploaded to the system. 

Now, this issue has been resolved and signing sessions with multiple documents with embedded Signer tags will identify those tags in all documents and associate them with a signer role when the Read Tags button is clicked. 

2\. GPES-3786  
We’ve fixed an issue with the look of signatures and initials drawn on mobile devices. 

Previously, signatures or initials drawn using a finger on a mobile phone looked messy and blocky.

Now, we’ve resolved the issue. Signatures and initials will now look like those drawn by the signer.  

3\. GPES-3724   
We’ve fixed an issue with the text form field allowing text to run off the page, even when set to fixed width.

Previously, after adding a text form field to a document and setting it to fixed width, when the signer entered too much text into the field, it would not enforce the fixed width and would let text run off the edge of the page.

Now, this issue has been resolved and text form fields with fixed widths will enforce that width and wrap text accordingly.  

4\. GPES-3713  
We’ve fixed an issue with the dashboard timing out when setting a custom date range.

Previously, when a user would set a custom date range on the dashboard, it may have returned a time out error.  

Now, when setting a custom date range, the dashboard will not time out. 

5\. GPES-3712

We’ve fixed an issue with the Initials tag changing when the corresponding signer’s name is edited during a signing session. 

Previously, if a signer’s name was edited while a signing session was in progress, the Initials tag didn’t accurately validate the signer’s initials, causing the initials to change. 

This issue was most visible for signers with a first, middle, and last name. The middle initial may have been dropped when they signed the document.

Now, when editing a signer’s name while a signing session is in progress, the initials tag will accurately validate the signer’s initials when they sign the document.

6\. GPES-3704 

We’ve fixed an issue with conditional settings not being applied to form fields in signing sessions. 

Previously, when creating an individual signing session or a signing session from a template, the conditional settings for the form fields might not have been saved in the signing session.  

Now, when creating an individual signing session or a session from a template, any conditional settings set on form fields will be saved and applied to the field during the signing session. 

7\. GPES-3687

We’ve fixed an issue with the Include Attachments toggle moving back to No after setting it to Yes. 

Previously, on the Profile page, if a user set the Include Attachments toggle to Yes, it would immediately appear to move back to No. However, the Yes setting was saved and would be reflected on the page after refreshing it, causing confusion.

Now, when adjusting the Include Attachments toggle, the chosen setting will display accurately on the page as expected.