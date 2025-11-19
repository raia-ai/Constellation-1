
# Constellation1 eSign February 2023 Release Notes

Production Release: February 23, 2023 

## RELEASE SUMMARY

**Administrator Access:** Added ability for admins to search the signing sessions of other users.   
**Document Review:** Document review is now an option when creating a session through our API.   
**eSign API:** Increased total size of documents that can be put through the API.   
**Name Editing:** Added ability to prevent signers from editing their name.   
**Recipient Validation:** Improved how recipients with the same email address are validated.   
**Signer Authentication Reset:** Added ability for senders to reset a signer’s authentication attempts.   
**Purged Documents:** Updated workflow for documents purged from the system.   
**Document Review:** Simplified Document Review workflow.   
**Bug Fixes**

## RELEASE DETAILS  

Administrator Access   
We’ve improved administrators’ ability to search the signing sessions of other users.   
When an administrator selects View Sessions for another user, they will now be able to search and filter these sessions, making it easier to find a specific session. 

Document Review  
We’ve improved signers’ ability to review documents before starting a signing session created through our API.  
When a signing session is created through our API, Document Review will now be available to signers so they can review the documents before signing.   
This update also allows sender to authenticate a session using Document Review. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/02%20Feb%202023/2023-Feb-esign-DocReview1.jpg)

eSign API   
We’ve increased the maximum total size of documents that can be added to a signing session through the API.  
When a user creates a signing session through the API, they can now add document files totaling up to 100 MB. 

Name Editing  
We’ve added the ability for signing session creators to prevent signers from editing their name.   
When adding a signer to a session, the session creator can toggle Disable Edit Name on and off in the Add Recipient modal. When the toggle is on and shows the word YES, the signer will not be able to edit their name appearing as their signature, but will still be able to select the font style.   
 

Recipient Email Address Validation  
We’ve improved how the system validates separate recipients with the same email address, for example, spouses or business partners who share an inbox.  
When adding multiple signers with the same email address to a signing session, the session creator will no longer be presented with the option to update the existing contact or add a new contact. Now the new person with the same email address will be automatically added as a new contact. The updated workflow makes it easier to add multiple people who share the same email address. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/02%20Feb%202023/2023-Feb-esign-SameEmail.jpg)

Signer Authentication Reset  
We’ve improved the process for signing session senders to reset the number of attempts a signer has to authenticate their session.   
If a signer fails to authenticate their signing session five times, they are locked out for security purposes. Previously, the sender didn’t have an easy way to reset the signer’s authentication attempts to allow them to try to log in again.   
Now, the sender can simply resend the signing session to the signer. Resending the session resets the authentication attempts, allowing the signer five more attempts to authenticate their session. If the signer can’t authenticate their session after 10 attempts, it may be a sign that the sender should provide additional authentication assistance.  
This was initially reported as a bug in ticket GPES-3592. 

Purged Documents   
We’ve improved the workflow for downloading documents that have been purged from the system.   
Previously, after documents were purged and deleted from the system, the link to download them remained on the Download Documents page and on the Session Info page, but clicking the link would result in an error.   
Once a signing session has been completed, the documents can be downloaded.   
Now, after the documents have been purged from the system, there will no longer be links to download them on the Download Documents or Session Info pages, but the system will display the names of the documents associated with the signing session.  
We’ve also updated the email notification to download the documents. If documents are purged immediately, an email will not be sent. If documents are purged later, the download link in the previously sent email will redirect to a page with the following message:  
You are attempting to access a session that has been purged.  
This session's documents are no longer available. Please contact the sender of your signing session.

Simplified Document Review Workflow   
We've removed the option to enable Document Review for CC Recipients and Reviewer roles when adding recipients to a signing session.   

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/02%20Feb%202023/2023-Feb-esign-DocReview.jpg)

Document reviewers will be notified of a signing session by email. The only action available to them is to review the documents. It is redundant to show the Document Review toggle for this role, so we’ve removed it. 

CC recipients are not signers and therefore should not be able to review documents in a signing session. They will now just receive the completed documents when the session is successfully completed.  

These changes simplify communications and the workflows for these roles.

  
Bug Fixes

1\. GPES-2942  
We’ve fixed an issue with the incorrect color displaying for the left navigation.   
Previously, in specific cases, when logging in to eSign, the left navigation didn’t display the default blue color, causing the text in the left navigation bar to be unreadable.   
Now, we’ve corrected this issue, and the default blue color will display when logging in to eSign 2.0. 

2\. GPES-3430   
We fixed an issue with markups and tags disappearing when placed too close to the edge of a document when using eSign on a mobile device.   
Previously, when a markup or signer tag was placed in the margins or too close to the edge of a document, the markup or tag would disappear and be removed from the document.   
We’ve corrected this behavior to allow markups and tags to be placed close to the edge and even a little over the edge of a document.   
Note: It is still best practice to keep markups and tags within the document margins. 

3\. GPES-3466  
We’ve fixed an issue with the action menu presenting invalid options to the session sender and reviewer after the reviewer has completed their session.   
Previously, when a reviewer completed their session, the action menu on the Session Info page displayed invalid options, including the ability to resend the session.   
Now, after a reviewer has completed their session, the menu on the Session Info page will only display valid options, preventing the sender and reviewer from accidentally initiating an invalid action while a signing session is active. 

4\. GPES-3515  
We’ve fixed an issue with users getting an error message saying, “Object reference not set to an instance of an object” when there were many documents attached to a signing session.  
Previously, if a signing session included a large number of documents, and the user tried to edit or change the order of the documents, they would receive this error.  
Now, we’ve improved the document handling process to accommodate a large number attached to a signing session.

5\. GPES-3568  
We’ve fixed an issue with allowing signers to access a signature session after they declined or delegated their signer role.  
Previously, even after a signer declined or delegated a signing session, they were still able to access the signing session without accepting the disclosure agreements.   
Now, if a signer declines or delegates their signer role for a session and does not accept the disclosure agreements, they will not be able to access the signing session. 

6\. GPES-3580   
We’ve fixed an issue with the system not sending a webhook after a signing session has been canceled.   
Previously, when a signing session was canceled, the system did not generate a webhook to notify other applications of the change.   
Now, when a signing session is canceled, a webhook will be generated and sent out as expected.  

7\. GPES-3600   
We’ve fixed an issue with being unable to cancel a signing session if it included a file with a long name.   
Previously, when there was a file with a long name attached to a signing session, canceling the session would cause an error.   
Now, when canceling a signing session with an attached file with a long name, the session will cancel as expected without an error. 

8\. GPES-3592   
We’ve fixed an issue with the Certificate of Authenticity not showing a green check mark to indicate the signing session has been successfully completed.   
Previously, due to a change in the DevExpress settings, the green check mark didn’t display on the Certificate of Authenticity.   
Now, the settings in DevExpress have been updated to display the green check mark on the COA. 

9\. GPES-3591   
We’ve fixed an issue with the Review Documents button incorrectly displaying the words Start KBA after KBA authentication had been completed by a document reviewer.   
Previously, after a document reviewer has completed their KBA authentication, the button to review the documents would still be labeled Start KBA, causing confusion.   
Now, after a document reviewer has completed KBA authentication, the button to review documents will be labeled correctly. 

10\. GPES-3590   
We’ve fixed an issue with signing sessions completing after a reviewer completed their session.    
Previously, when a document reviewer completed their review of the document, the signing session would be marked as compete, even if there were still incomplete signing sessions.   
Now, the signing session will not be marked as complete until all signing sessions have been completed, even after a document reviewer has completed their review. 

11\. GPES-3582   
We’ve fixed an issue with second signing session invitation links not working.   
Previously, the link in the second signing session invitation to open the session was not working and resulted in an error message.  
Now, when a signing session invitation is re-sent, the link will work and take the signer to the signing session. 

12\. GPES-3600   
We’ve fixed an issue with a document ZIP file causing an error after a signing session has been canceled.   
Previously, when cancelling a signing session that included a document with a long file name, the system would create a ZIP file of the documents and cause an error when the sender tried to view the canceled session.    
Now, when cancelling this type of session, the system will no longer try to zip the documents and the sender will be able to view the canceled session.