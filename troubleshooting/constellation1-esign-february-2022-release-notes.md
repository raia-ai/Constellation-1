---
title: Constellation1 eSign February 2022 Release Notes
---

# Constellation1 eSign February 2022 Release Notes

Production Release: February 24, 2022 

### RELEASE SUMMARY

**Bulk Signing Sessions:** Moved the View Uploaded Documents option from bulk session Action menu. 

**API:** Updated our API to return signer uploaded documents in a paginated format. 

**Email Template:** Updated email template to version 2.0.

**Bug Fixes**

### CONSTELLATION1 ESIGN 

**BULK SIGNING SESSION – VIEW UPLOADED DOCUMENTS**

When viewing a bulk signing session, we moved the View Uploaded Documents option to the Sessions page for each signer. On the sessions page, next to the signer’s name, click the icon under the Actions column to access the View Uploaded Documents option. 

This update improves usability for managing documents that are uploaded by the signer in a bulk session.    

**API RETURNING SIGNER DOCUMENTS IN PAGINATED FORMAT** 

In our last release, we updated our API to allow signing session creators to access documents signers have uploaded to the signing session. 

In this release we updated the API call “getsignerdocuments” to return documents in a paginated format when there are more than 5 documents returned in the API call.  

Click [HERE](https://docs.constellation1.com/rest-getsignerdocuments/ "Get Signer Documents API Information") to view getsignerdocuments documentation.

**EMAIL TEMPLATE UPDATE** 

We updated our email template to eSign version 2.0. Links within the email have been updated, to point to eSign 2.0.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/2022-Feb-eSign-emailtemplate.jpg)

_Example Email_

**BUG FIXES**

*   Fixed an issue where your company logo might have displayed incorrectly. 
*   Fixed an issue with documents failing to convert to PDF when sent thought the API, preventing the signing session from beginning. Now if a document fails to convert, the user will see an alert. 
*   Updated the PDF conversion process to be more efficient and produce clearer PDF files.