
# Constellation1 eSign November 2022 Release Notes

Production Release: November 17, 2022 

## RELEASE SUMMARY

**Signing Session:** Updated the signing order to allow for multiple signers to have the same spot in the signing sequence.

**Dashboard:** Updated labels for completed signing sessions. 

**Date/Time Tag:** Updated default setting option to include the time. 

**Webhooks:** Declined signature sessions now include the reason it was declined. 

**DevExpress:** Updated to the latest version and deprecated XFA file type. 

**Bug Fixes**

## RELEASE DETAILS  

Signing Session – Updated Signing Order 

We’ve improved signing sessions to allow multiple signers to have the same sequence number in the signing order.   
Previously, all signers had a unique place in the signing order and the session had to follow that sequence. Now, multiple signers can share the same number in the signing order.   
For example, in a signing session with multiple signers, it may be important for a particular signer to complete their session first. The other signers may sign in any order and at any time. In such casees, after signer 1 has completed their signing session, an invite will now be sent to all other signers at the same time, allowing them to complete their signing sessions sooner rather than having to wait for their turn in the signing order. 

Updated Dashboard Label

We’ve updated the label for completed signing sessions on the dashboard. When a signing session is complete, the Status column will now display Competed.    
Previously the status would show the number of signers who had signed and how many had yet to sign (e.g., “1 of 1 Completed”. The new label provides clarity and a useful visual cue.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Nov/2022-Nov-esign-Dashboard-CompletedSession.png)

Default Date and Time Tag Setting

We’ve updated the Date/Time tag to allow a company to change the default setting for this tag.   
Currently, the default setting is to display the date only. A company can request that the default setting be changed to include the date and time. The default setting also applies to signing sessions created through the API.   
To have the default setting changed, please contact your Constellation1 representative.  

Updated Messaging via Webhooks

We’ve improved the use of webhooks to now also provide the reason a signing session was declined.   
When a signer declines a signing session, we are now also communicating the reason they declined the session via webhooks. 

DevExpress 

We’ve upgraded eSign 2.0 to the latest version of DevEpress. This update removes support for XFA files, as this file type has been deprecated as a standard.   
When XFA files are uploaded to a signing session, the user will receive a message saying the file failed to upload due to being an unsupported file type. They will be prompted to upload a supported file type before going to step 2.    
eSign supports the following file types, .bmp, .gif, .jpg, .png, .tiff, .xls, .xlsx, .doc, .docx, .rtf, .pdf, and .txt. 

Bug Fixes

1\. GPES-3369   
We fixed an issue with authentication method missing from the Session Info page.   
Previously, when creating a signing session and adding an authentication method, the authentication method was not showing on the Session Info page.   
Now, when the authentication is added to a signing session, it will be documented on the Session Info page as expected. 

2\. GPES-3419  
We fixed an issue with PDF documents failing to upload when some fillable form fields are left blank.   
Previously, when a PDF document was uploaded to a signing session and some of the fillable form fields were left blank, the document would fail to upload and display an error message.   
Now, PDF documents with blank fillable form fields will upload successfully. 

3\. GPES-3439   
We fixed an issue with some PDF documents with fillable form fields not converting the data in the form fields.   
Previously, in some cases, when a PDF document with fillable form fields was uploaded to a signing session, the data added to the fillable form fields did not convert. This left the fields blank.  
Now, when a PDF document with fillable form fields is uploaded to a signing session, the data in the form fields will convert as expected. 

4\. GPES-3403  
We fixed an issue with the documents ZIP file not downloading documents.   
Previously, when the signer opted to view the documents during a signing session, they were presented with the option to download the documents in a ZIP file. The ZIP file is only created after a signing session has been completed.   
Now, the document ZIP file will only show as an option after the signing session has been completed.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Nov/2022-Nov-esign-Docs-zipfile.png)