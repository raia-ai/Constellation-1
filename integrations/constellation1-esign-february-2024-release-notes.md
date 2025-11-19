---
title: "Constellation1 eSign February 2024 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/22957861"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign February 2024 Release Notes Production Release: February 21, 2024 Release Summary Processing Anchor Tags: Improved usability for"
long_description: "Constellation1 eSign February 2024 Release Notes Production Release: February 21, 2024 Release Summary Processing Anchor Tags: Improved usability for uploaded documents with anchor tags.  Bug Fixes Technology Updates Release Details Processing Anchor Tags We have improved eSignature to be more efficient and user-friendly for documents with many anchor tags.  When uploading such documents, eSignature now processes them faster. However, users will not be able to proceed to step 2 while the documen"
---

# Constellation1 eSign February 2024 Release Notes

Production Release: February 21, 2024

## Release Summary

**Processing Anchor Tags:** Improved usability for uploaded documents with anchor tags. 

**Bug Fixes**

**Technology Updates**

## Release Details  

Processing Anchor Tags  
We have improved eSignature to be more efficient and user-friendly for documents with many anchor tags.   
When uploading such documents, eSignature now processes them faster. However, users will not be able to proceed to step 2 while the documents are processing, and may be notified that documents are being processed. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/02%20Feb/2024-Feb-eSign-ProcessingDoc.png)

Bug Fixes

1\. GPES-4671 and GPES-4668  
We fixed an issue with exporting contacts erroring. 

Previously, when exporting 100 or more contacts, users would receive a “Bad Request” error message.

Now, users can export contacts as expected. 

2\. GPES-4613  
We’ve fixed an issue that caused certain markup tags to be omitted when sending a document for signature.

Previously, when using Windows 11 and Google Chrome to send a signing session, some markup tags placed on the document would disappear after the recipient completed their signing session.

Now, all markup tags and fields will be included on a document when signed and returned as expected. 

Technology Updates

1\. The recently released Administration Usage reports have been optimized with improvements made to the database.