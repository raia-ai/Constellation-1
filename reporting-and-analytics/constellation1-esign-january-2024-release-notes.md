---
title: Constellation1 eSign January 2024 Release Notes
---

# Constellation1 eSign January 2024 Release Notes

Production Release: January 24, 2024 

## RELEASE SUMMARY

**Administration Reports:** Added user and group usage reports.

**Bug Fixes**

## RELEASE DETAILS

Administration Usage Reports  

To provide greater insight into user and group activity, we've added a usage report for Client and Group administrators that shows the number of eSignature sessions created by each user or group user for the year to date.

The report displays the number of signing sessions created, drafts, sent, paused, completed, cancelled, and expired.

The report will be exportable to a CSV file in the near future. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/01%20Jan/2024-Jan-eSign-UsageReport.jpg)

Bug Fixes

1\. GPES-3747  
We fixed an issue with billing customers who upgraded from a monthly subscription to an annual subscription.

Previously, when customers upgraded from monthly to annual subscriptions mid-month, the system would immediately activate the annual subscription, sometimes overcharging customers. 

Now, we’ve corrected this issue and identified all affected customers and corrected their accounts. 

2\. GPES-4605  
We’ve fixed an issue with RTF documents adding extra spaces between letters and words when it was uploaded to a signing session.

Previously, when an RTF document was uploaded to a signing session, extra spaces were inserted between words and letters. This resulted in unreadable embedded tags, as well as stretched-out words and sentences.

Now, this issue has been resolved. 

3\. GPES-4622  
We fixed an issue with some bulk signing sessions not showing in the signing sessions archive. 

Previously, some signing sessions created using the bulk send function were not showing in the list of archived signing sessions.

Now, this issue has been resolved. 

4\. GPES-4648  
We fixed an issue with attachments not being sent to signers when a signing session is created through the API.

Previously, when a signing session was created through the eSignature API and the setting to include attachments is enabled, signed documents were not being sent to the signers.

Now, this issue has been resolved.  

5\. GPES-4558  
We fixed an issue with the signature block created in the users’ profile displaying incorrectly on emails sent to signers.

Previously, the signature created in the users’ profile was malformed and failed to display properly in the email sent to signers. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/01%20Jan/2024-Jan-eSign-Signature.jpg)

 Now, this issue has been resolved.