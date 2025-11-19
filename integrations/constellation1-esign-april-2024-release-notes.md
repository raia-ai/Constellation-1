# Constellation1 eSign April 2024 Release Notes

Production Release: May 6, 2024

## Release Summary

**Require Signer to Upload Document:** Added feature to require signers to upload a document before completing a signing session.\
**Group Managers:** Search for Groups and Group Users by creation date.&#x20;

**Signing Sessions:** Improved sessions containing many signer tags. \
**Bug Fixes**

**Technology Update**

## Release Details

Require Signer to Upload Document\
We have added the ability to require signers to upload a document before completing their signing session. \
A new "Document Upload Required" toggle has been added to the contact record to enable this requirement when creating a signing session.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/04%20April/2024-April-eSign-UploadDoc.jpg)

When this option is enabled, the signer will be required to upload a document before they can complete the signing session.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/04%20April/2024-April-eSign-UploadDocMessage.jpg)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/04%20April/2024-April-eSign-UploadDocNav.png)

Customers who use the API can also set this requirement as part of the Properties Parameter.\
signer.MandateDocUpload = true;&#x20;

[CLICK HERE](https://docs.constellation1.com/rest-integration-strategies-workflows/rest-signing-sessions-header/rest-createsession/) for more information about the API.

Date Filter Added to Groups \
We have added date range filters to the Groups and Group Users pages. \
At the top right of these pages, users can now search for groups based on when they were created.\
The available filter options include Current Day, Last Month, and Custom Date Range.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/04%20April/2024-April-eSign-GroupDate.jpg)

Improved Signing Sessions\
We’ve improved the usability for signing sessions with a large number of signer tags, by removing the processing spinner, allowing signers to sign each tag quickly and efficiently.&#x20;

**Bug Fixes**

1\. GPES-4763\
We fixed an API issue with the sign now button redirecting users to the eSign login screen.

Previously, when some API users clicked the "sign now" button, they were incorrectly directed to the eSign login screen instead of the document that needed signing.

Now, we’ve updated the API to direct signers to the signing session for that document as expected.&#x20;

2\. GPES-4759\
We’ve fixed an issue with the Text markup not displaying the full text entered into the markup tag when using the mobile view.

Previously, when users entered text into the Text markup tag using the mobile view, some text was not visible because the markup was being saved with a default width instead of expanding to show the full text.

Now, we’ve fixed this issue so the text markup displays the full width of the text entered in the mobile view.

3\. GPES-4757 \
We fixed an issue with the bottom half of signatures being cut off.

Previously, in some cases the bottom half of a signature was cut off and didn’t show on the signed document.

Now, this issue has been resolved. &#x20;

**Technology Updates**\
1\. We’ve updated the .net framework from .Net 6 to .Net8.
