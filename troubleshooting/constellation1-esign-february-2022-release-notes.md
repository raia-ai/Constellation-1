# Constellation1 eSign February 2022 Release Notes

Production Release: February 24, 2022&#x20;

### RELEASE SUMMARY

**Bulk Signing Sessions:** Moved the View Uploaded Documents option from bulk session Action menu.&#x20;

**API:** Updated our API to return signer uploaded documents in a paginated format.&#x20;

**Email Template:** Updated email template to version 2.0.

**Bug Fixes**

### CONSTELLATION1 ESIGN&#x20;

**BULK SIGNING SESSION – VIEW UPLOADED DOCUMENTS**

When viewing a bulk signing session, we moved the View Uploaded Documents option to the Sessions page for each signer. On the sessions page, next to the signer’s name, click the icon under the Actions column to access the View Uploaded Documents option.&#x20;

This update improves usability for managing documents that are uploaded by the signer in a bulk session. &#x20;

**API RETURNING SIGNER DOCUMENTS IN PAGINATED FORMAT**&#x20;

In our last release, we updated our API to allow signing session creators to access documents signers have uploaded to the signing session.&#x20;

In this release we updated the API call “getsignerdocuments” to return documents in a paginated format when there are more than 5 documents returned in the API call. &#x20;

Click [HERE](https://docs.constellation1.com/rest-getsignerdocuments/) to view getsignerdocuments documentation.

**EMAIL TEMPLATE UPDATE**&#x20;

We updated our email template to eSign version 2.0. Links within the email have been updated, to point to eSign 2.0.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/2022-Feb-eSign-emailtemplate.jpg)

_Example Email_

**BUG FIXES**

* Fixed an issue where your company logo might have displayed incorrectly.&#x20;
* Fixed an issue with documents failing to convert to PDF when sent thought the API, preventing the signing session from beginning. Now if a document fails to convert, the user will see an alert.&#x20;
* Updated the PDF conversion process to be more efficient and produce clearer PDF files.
