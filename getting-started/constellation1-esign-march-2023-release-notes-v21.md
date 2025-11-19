---
title: "Constellation1 eSign March 2023 Release Notes v2.1"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/19975076"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign March 2023 Release Notes v2.1 Production Release: March 22, 2023  RELEASE SUMMARY DevExpress Switch: Updated the PDF creation pro"
long_description: "Constellation1 eSign March 2023 Release Notes v2.1 Production Release: March 22, 2023  RELEASE SUMMARY DevExpress Switch: Updated the PDF creation process to DevExpress for increased functionality.  Architecture: Improved error checking when sending emails.  Bug Fixes  RELEASE DETAILS DevExpress Switch We’ve replaced Tall Components with DevExpress for increased stability and functionality when eSign creates the signed PDFs after a signing session has been completed. This is the culmination of a"
---

# Constellation1 eSign March 2023 Release Notes v2.1

Production Release: March 22, 2023 

## RELEASE SUMMARY

**DevExpress Switch:** Updated the PDF creation process to DevExpress for increased functionality. 

**Architecture:** Improved error checking when sending emails. 

**Bug Fixes**

## RELEASE DETAILS

DevExpress Switch  
We’ve replaced Tall Components with DevExpress for increased stability and functionality when eSign creates the signed PDFs after a signing session has been completed. This is the culmination of an overall plan to replace Tall Components. 

Architecture  
We’ve improved the process for sending signing session invitation emails to automatically resend them if they fail to send the first time.   
We have various monitors in place to track email activity and are immediately alerted when there is an issue with our email host. We are now leveraging these monitors and alerts to automatically queue up and resend any emails that failed to send.

This improvement stems from the fix for an issue reported in ticket GPES-3636 regarding signing session invitation emails not being sent. 

At the time this was reported, emails were not being sent to some signers. We resolved the issue with our email host, and as a course of action, we identified the signers whose email invitations were not sent and resent them.

  
Bug Fixes

1\. GPES-3430 and GPES-3626   
We’ve fixed several markup tag placement issues when in mobile mode.   
Previously, when a user added tags to a document in mobile mode, they may have received error messages, or the tags may have disappeared.   
Now, we’ve corrected these issues with placing tags in mobile mode. 

2\. GPES-3542  
We’ve fixed an issue with missing text wrapping in signing session invitation emails.   
Previously, in some signing session invitation emails, the text would run over and not wrap to the next line as expected.   
Now, we’ve corrected this formatting issue and the message in the signing session invitation email will display properly.

3\. GPES-3414  
We’ve fixed an issue with an error message appearing on the dashboard when searching for a specific email address in the Total Emails Delivered tile.   
Previously, when a user searched Total Emails Delivered, they may have received a JavaScript error message.   
Now, this issue has been resolved. Users will be able to search for specific emails from the dashboard tiles. 

4\. GPES-3539   
We’ve fixed an issue with an error message appearing when uploading PDF documents to a signing session.  
Previously, when a user would upload a specific kind of PDF document to a signing session, they would receive an error message saying the file was not recognized as a valid PDF format.  
Now, this issue has been resolved. When uploading PDF documents, they will be added to the signing session as expected.