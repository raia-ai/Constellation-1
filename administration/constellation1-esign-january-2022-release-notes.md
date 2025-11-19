---
title: "Constellation1 eSign January 2022 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/15746036"
tags: ["Administration"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign January 2022 Release Notes Production Release: January 25, 2022 RELEASE SUMMARY API: Updated our API to allow access to signer do"
long_description: "Constellation1 eSign January 2022 Release Notes Production Release: January 25, 2022 RELEASE SUMMARY API: Updated our API to allow access to signer documents.  Bulk Users Uploads: Template updated to allow administrators to assign groups and roles.  Bug Fixes Constellation1 eSign API To Return Signer Documents  We have updated our API to allow signing session creators to access documents signers have uploaded to the signing session. The API call is getsignerdocuments and the Session ID and Signe"
---

# Constellation1 eSign January 2022 Release Notes

#### Production Release: January 25, 2022

### **RELEASE SUMMARY**

**API:** Updated our API to allow access to signer documents.

**Bulk Users Uploads:** Template updated to allow administrators to assign groups and roles.  

**Bug Fixes**

## Constellation1 eSign

**API To Return Signer Documents**

We have updated our API to allow signing session creators to access documents signers have uploaded to the signing session.

The API call is getsignerdocuments and the Session ID and Signer ID are passed in the API call to identify the documents.

Session creators will be able to view the title and size of the documents, then download them if they wish.   

### **Groups and Roles for Bulk Users Uploaded**

We have added the ability to assign users to a group and assign roles when they are uploaded to eSign in bulk using our CSV upload process. This update expands on the bulk user upload process in eSign 1.0.

There are two new fields in the CSV file: Group and Role. When the file is uploaded, users will be assigned to the defined group and role, if selected.

The users who have the ability to upload users in bulk are Client Administrators and Client Support.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/BulkUserImportFile.png)

_Example of the updated import file format_

**Bug Fixes**

*   Fixed an issue with the signing session email template. The email was missing the CC’ed signers name, status and role.  
    
*   Fixed an issue with members getting an error when updating their personal preferences.
*   Fixed an issue with the Configure Signers pop-up not showing when creating a new signature session using the API.

Was this article helpful to you?

Was this article helpful to you?