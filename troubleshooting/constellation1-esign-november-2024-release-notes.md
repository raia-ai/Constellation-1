---
title: Constellation1 eSign November 2024 Release Notes
---

# Constellation1 eSign November 2024 Release Notes

Production Release: November 25, 2024

## Release Summary

**Signer Names:** Updated handling of special characters in signer names.   
**Bulk Send:** Added country option to signer upload CSV file.   
**User Login:** Improved efficiency of user login process.   
**Bug Fixes**

## Release Details 

Signer Names   
The system now properly handles names containing accents (\`) and/or tildes (~). It will no longer append a random letter from the middle of a name to the signer's initials tag. 

Instead, the signer's initials will be derived directly from their first, middle, and last name.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/11%20November/2024-Nov-eSign-Initials.png)

Bulk Send

We’ve added the option to include a signers Country in the bulk send recipient CSV file. 

If your signers are all located in the United States, you can continue using your existing CSV file without the country column. If the country is not specified in the CSV, we will automatically set the default to the United States.

The system will accept the following country name variations:  
•    UK and United Kingdom  
•    USA and United States   
•    CA and Canada

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/11%20November/2024-Nov-eSign-BulkUpload.png)

  
Bug Fixes

1\. GPES-5073  
We fixed an issue with the sequence of "CC Recipients" not showing in the correct order.

Previously, when signers were added to a signing session and their role was changed to CC-Recipient, the recipient sometimes remained in the same position instead of being moved below the signers.

Now, this issue has been resolved. CC-Recipients will be placed in the correct order in a signing session. 

  
2\. GPES-5017  
We fixed an issue with changing the sort order of documents uploaded to step 1 of a signing session.

Previously, the documents would not re-sort when users changed the order using the number dropdown options next to each document name.

Now, this issue has been resolved. Changing the order number next to a document will update their sort order.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/11%20November/2024-Oct-eSign-DocumentOrdering.png)

_Example of the sorting issue._