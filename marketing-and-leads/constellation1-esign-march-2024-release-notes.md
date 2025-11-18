---
title: "Constellation1 eSign March 2024 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/23246175"
tags: ["Marketing & Leads"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign March 2024 Release Notes Production Release: March 20, 2024 Release Summary eSignature Mobile: Usability improvements"
long_description: "Constellation1 eSign March 2024 Release Notes Production Release: March 20, 2024 Release Summary eSignature Mobile: Usability improvements.  Bug Fixes Release Details  Improvements to eSignature Mobile We've made significant updates to the user experience for eSign mobile, including improvements to the display of documents, creating bulk signing sessions and placing markups and signer tags on documents."
---

# Constellation1 eSign March 2024 Release Notes

Production Release: March 20, 2024

## Release Summary  

**eSignature Mobile:** Usability improvements.   
**Bug Fixes**

## Release Details  

Improvements to eSignature Mobile  
We've made significant updates to the user experience for eSign mobile, including improvements to the display of documents, creating bulk signing sessions and placing markups and signer tags on documents.

  
Documents now fit the width of the device displaying them, eliminating the need for horizontal scrolling.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/03%20March/2024-March-eSign-MobileDoc.jpg)

  
When creating a bulk signing session, the workflow for step 2 has been updated to match the workflow in step 2 for creating a regular signing session. This change provides a consistent user experience across both regular and bulk signing sessions.

Placing markups and signer tags on a document is now more intuitive to enhance the user experience with greater ease and fluidity. 

Bug Fixes  
1\. GPES-4735  
We fixed an issue with some templates failing to load when a signing session is created via the API.

Previously, some templates failed to load when creating signing sessions via the API due to leading or trailing spaces in the template name. We fixed this issue so templates now load as expected when creating signing sessions through the API.

Now, we’ve fixed this issue so templates now load as expected when creating signing sessions through the API. 

2\. GPES-2778  
We’ve fixed an issue with dragging markups and signer tags off the right edge of a document.

Previously, users were able to drag markups and signer tags past the right edge of a document, causing a portion of the markups and tags to be incorrectly displayed off-screen. 

Now, we’ve fixed this issue so markups and tags will remain on the document.