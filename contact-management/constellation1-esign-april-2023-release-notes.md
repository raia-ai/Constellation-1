---
title: Constellation1 eSign April 2023 Release Notes
---

# Constellation1 eSign April 2023 Release Notes

Production Release: April 19, 2023 

## RELEASE SUMMARY

**DevExpress:** Added support for long file names.   
**Signer Roles on Templates:** Improved signer role assignment workflow.   
**Signing Session Status Label:** Improved display of signing session status.   
**HTML Support in Email Signatures:** Updated fields to support HTML.   
**Email Preview:** Improved display when previewing email messages.   
**Single Sign-On Workflow:** Improved workflow when creating signing sessions via single sign-on.   
**Signing Session Name Locked:** Updated signing session name to be uneditable after a session has been created.   
**eSign API:** Improved workflow for when signing session creators are also signers.   
**Bug Fixes**

## RELEASE DETAILS

DevExpress Update  
As part of our ongoing DevExpress update, eSign 2.0 now supports long file names. Documents with long file names will no longer cause issues with a signing session. This update also applies to files that are uploaded to a signing session with a short name, then renamed with a long name.

Also included in this update, documents that are scanned as an image file can now be uploaded to eSign 2.0 and converted to PDF without issue. See bug fix GPES-3672 below.  

Signer Roles on Templates  
We’ve improved templates to make it easier for users to add more than one signer for a specific signer role.   
Under Signer Roles, when a user adds a role to the template, the modal now features a number picker, so the user can define the number of signers for that role. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-AddRole.jpg)

  
Signing Session Status Label   
We’ve updated the Session Status label for pending signing sessions for a more intuitive and user-friendly experience.   
We’ve updated the label color to blue to be more visible and the text form “Pending” to “Sent to # Signers” where the number updates dynamically based on the total number of signers. 

The updated label shows on the Sessions page and the Session Status page. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-StatusLabel1.jpg)  
_Sessions Page_

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-StatusLabel2.jpg)  
_Session Status Page_

HTML Support in Email Signatures   
We’ve improved the Email and Email Signature fields to support HTML. Users can now create email messages and email signatures using HTML, then add them to the Email Message field in step 1 and to the Email Signature field in the Signatures modal on the User Profile page. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-EmailSigStep1.jpg)  
_Step 1_

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-EmailSig1.jpg)  
_Signatures modal_  

To add HTML to the Email Message or Email Signature fields, click the </> icon on the Menu Bar to open the HTML editor. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-EmailSig2.jpg)

Paste the HTML into the box, then click the </> icon again to see the signature as it will display at the bottom of an email. Email signatures are included at the bottom of all outgoing signing session emails.

Email Preview   
We’ve updated how email previews display across eSign for a more consistent user experience.   
When creating a signing session, the user can draft an email message and preview it before sending the signing session.   
Previously, the email preview would open in a modal.   
We’ve updated how email previews display before sessions are sent so that they now appear in an expanded section of the Signing Session Information box. This is consistent with how email previews display after a session is sent. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-EmailDisplay.jpg)

  
Single Sign-On Workflow  
We’ve updated the single sign-on workflow for an improved user experience when editing a signing session.   
After a signing session has been created, if the user wants to edit the session via a single sign-on URL, they will now be taken to step 1 of the signing session where they can edit it.   
Previously, when the user accessed the signing session using the single sign-on URL, they were taken to the Session Status page, where there wasn’t an option to edit the session.  

Signing Session Name Locked    
We’ve improved security for signing sessions created via the single sign-on URL to lock the session name.   
Previously, after a signing session was created, a user could modify the session name. This created confusion and an inconsistent user experience.   
Now, after a signing session has been created, the signing session name field will be grayed out and uneditable. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-SessionTitle.png)

eSign API  
We’ve improved the workflow for signing sessions created via the eSign API when the creator is also a signer.  
When the creator of a signing session created through the API is also a signer, we’ve enabled an Include Me as a Signer toggle. This allows the creator of the session to launch their signing ceremony immediately after sending the session. 

  
Bug Fixes

1\. GPES-3683, GPES-3501  
We fixed an issue with markup tags disappearing from a document that was previously included in a template when adding another, newer document.   
Previously, if a user added a new document to a template, any markup tags in a previously uploaded document would disappear.   
Now, when adding a new document to a template, the markup tags will remain on the document as expected. 

2\. GPES-3672  
We fixed an issue with field placement changing after certain types of documents had been signed.   
Previously, in some rare cases when a scanned document was uploaded to a signing session as a JPG file, after the document was signed and returned, some of the fields may have moved from their original location.  
Now, when a field is placed on a such a scanned document, it will remain in that location after the document has been signed and the session completed. 

3\. GPES-3610, GPES-3682, GPES-3652   
We fixed an issue where some users were no longer able to draw their signature or initials when accessing signing sessions on an Android smartphone or tablet.    
Previously, Android users found they could not draw their signature or initials in mobile mode. If a user tried to draw their signature, the background would scroll. They could still complete their signing sessions without issue by selecting one of the stylized signatures generated by the system.  
Now, we’ve corrected this issue and those users who want to draw their own signatures on mobile can now do so again. 

4\. GPES-3552   
We fixed an issue with group logos not displaying in signing session emails.   
Previously, if a signing group had uploaded a group logo, the logo wouldn’t show in signing session emails.   
Now, we’ve corrected this issue and group logos will show on signing session emails as expected.  

5\. GPES-2152   
We fixed an issue with the signing session sender’s email address not being automatically added to the email message generated after clicking the Contact Sender button.   
Previously, if a user clicked the Contact Sender button in the signing ceremony navigation bar, the email message that popped up wouldn’t include the session sender’s email address in the To field.   
Now, when a user clicks the Contact Sender button, the sender’s email address will appear in the To field as expected. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/04%20April%202023/2023-April-ContactSender.jpg)