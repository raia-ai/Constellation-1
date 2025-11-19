
# Constellation1 eSign August 2022 Release Notes

Production Release: August 25, 2022 

##   
RELEASE SUMMARY

**Signer Roles:** Simplified CC Recipient roles to make adding them to a signing session easier.

**Dashboard:** Added the ability to search and sort failed emails using the Reason column.

**Email Attachments:** Documents will no longer be sent as attachments. 

**API:** Added the option for API users to include an email signature for group users.

**Architecture:** Updated Tall Components for increased functionality. 

**Profile Pictures:** Added the ability to delete profile photos.

**New User Guide:** Added a full user guide. 

**Bug Fixes**

## Release Details 

Signer Rolls 

We’ve improved signer roles and removed Actions options that did not apply to CC Recipients. Because CC Recipients are not signers, we removed Allow Delegation, Signing In-Person, and other signer actions that do not apply to this role.

  
  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20August/2022-Aug-eSign-SignerActons.png)  
Add Recipient - Signer

  
  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20August/2022-Aug-eSign-CCRecipient.png)  
Add Recipient - CC Recipient 

  
Dashboard

We’ve added the ability to filter failed emails by the Reason column. This improvement will make it easier to quickly group emails together by the reason they failed, allowing for easy administration. 

Additionally, we added a search box to allow users to search for specific email addresses. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20August/2022-Aug-eSign-SearchEmail.png)

Email Attachments 

To improve efficiency and document security, we’re no longer sending documents as email attachments. Users can view and download documents using the secure Download Documents link in the email message. 

In addition to better security, this will prevent emails from failing to send or being rejected due to oversized attachments. 

eSignature API Update 

We’ve improved our API to include the option to make an email signature for a group of users when creating a group through the API.

When a group user account is created, the email signature can be passed in through the API. The signature will show on the group user’s profile page. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20August/2022-Aug-eSign-UserSignature.png)

Tall Components Updates

We’ve updated the Tall Components library for increased efficiency and functionality. This update allows users to select multiple documents and merge them into one file using the Print feature. It also improves how images are managed. When an image file is uploaded to the system, it will be converted to a PDF. 

**Note:** Uploaded images will fill an 8.5 x 11 page based on the length dimension, without cropping any part of the image. 

User Profile Pictures 

We’ve improved how users manage their profile pictures. Previously, there wasn’t an option to delete their profile picture. Now, we’ve added a button to change the profile picture, with additional options to upload a new picture or delete the current picture. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20August/2022-Aug-eSign-ProfilePic.png)

User Guide

We’ve added a full User Guide to the Profile menu to complement the Quick Start Guide. Both guides are available to all users.

Bug Fixes

1\. GPES-3199  
We fixed an issue with the Signing Session Viewed email being sent multiple times.   

Previously, if a signer clicked the Start Signing button multiple times, the Signing Session Viewed email would be sent multiple times. 

Now, when the Start Signing button is clicked multiple times, the Signing Session Viewed email will only be sent once. 

2\. GPES-3136   
We fixed an issue with a user status not being updated in both eSignature 1.0 and 2.0.

Previously, if a user account status was updated to either Active or Inactive in eSignature 1.0, the change was not being updated in eSignature 2.0.

Now, if an update is made in either eSignature 1.0 or 2.0, the change will sync across both versions.