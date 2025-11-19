---
title: Constellation1 Commissions May 2024 Release Notes v3.2
---

# Constellation1 Commissions May 2024 Release Notes v3.2

Production Release: May 28, 2024, v3.2

## Release Summary

**Commission Plans:** Updated user interface.   
**Commission Plans Deductions Cap:** Added option to change deduction amount after cap amount is reached.   
**Custom Branding:** Added more branding options for franchise companies.  
**Broker Custom Branding:** Added custom branding options for brokerages.   
**My Workspace:** Alert icon added for upcoming closings.   
**Dashboard:** Improved user experience when viewed in responsive mode.   
**Agent View:** Removed edit access to some agent profile fields.   
**General Ledger:** New warning message when mapping third party advance payable.   
**API:** Create and manage agent accounts through the API.  
**eSignature:** CC contacts when sending documents through eSignature.  
**Bug Fixes**

## Release Details

Updated Commission Plans   
We’ve made updates to the user interface of the Commission Plans module to enhance the user experience, making it more intuitive and user-friendly when creating and managing commission plans.   
Users can now easily select the commission plan type when creating or editing a commission plan, after which they will see the available commission options specific to that type.   
Additionally, updates have been made to dropdown menus and advanced options for better usability.  
These updates have also been applied to the Commission Wizard when creating Flat Rate and Sliding Scale plans. Partial Payment plans can be created and managed in the non-wizard interface. 

 _![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-CommisionPlanSliding2.jpg)_  
_Sliding Scale_ 

 _![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-CommisionPartial.jpg)_  
_Partial Payment_

  _![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-CommisionPlanFlat.jpg)_  
_Flat Rate_

These changes are specific to the user interface and workflow, they do not affect commission plan calculations for existing plans. 

  
Commission Deductions Cap Amount  
We've introduced a new feature to the Commission Plans that allows for changes to the deduction amount after the cap amount is reached.

When adding deductions to a commission plan, a cap amount can be specified. Now, it is now possible to include deductions or make changes to deductions on commissions after the cap amount has been reached.

Deductions can be a dollar amount, percentage, or the sum of both.

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-DeductionsCap.jpg)

  
Custom Branding – Enterprise Insights  
In a recent release, we introduced the option for companies and franchises to apply custom branding to Commissions Online.   
As part of this release, we are pleased to introduce the following new branding features,

*   Upload a favicon.
*   Customize the system email address.
*   Set up a custom URL.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-CompanyCustBranding.jpg)

**Favicon**  
In the Enterprise Insights platform, within the White Labeling module, under Custom Branding, administrators can upload a favicon that will appear in the browser tab. Favicons should be in a .png or .ico format and not to exceed 100kb. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-BrowserTab.jpg)

  
**Custom URL and system email address**  
DNS configurations are necessary to connect your company's custom URL to Commissions Online and to customize the system email address domain.

Please contact your Constellation1 representative for more information. 

Custom Branding - Brokerages  
As part of this release, we have also extended access to some of these branding features, allowing brokerages the ability to customize their Commissions Online account, when access is granted.

In Enterprise Insights within the While Labeling module, under Brokerage Override, administrators can grant access to brokerages, allowing them to customize their brokerage Commissions Online account. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-BrokerOverrides.jpg)

  
When access is granted, brokers will have access to these features in the System Settings, on the Company settings page.  

*   Logo.
*   Email Templates.
*   Left navigation menu color.
*   System email address (when enabled at the franchise level).

[CLICK HERE](https://constellation1.na3.teamsupport.com/knowledgeBase/23611286) for more information on custom branding, or contact your Constellation1 representative.  

  
My Workspace Alert for Upcoming Closings

We’ve enhanced the My Workspace icon to display an alert icon when there are upcoming closings.   
Whenever there are closings scheduled within the next 7 days, an alert icon will appear alongside the My Workspace icon.

Click on the My Workspace icon to clear the notification and to see the upcoming closings.  
 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-Dashboard.jpg)

  
Dashboard User Interface Update  
We have made updates to the dashboard to enhance the user experience, ensuring that when viewed in responsive mode, labels, buttons, and dropdowns will no longer overlap.  

Agent View  
We’ve removed the ability for agents to edit some information in their profile to prevent unexpected changes to reporting, commission rates and tiers, financial reports and information when integrated with QuickBooks®.   
Agents are no longer able to edit the following fields in their profile, 

*   Office
*   Business/EIN/SSN/SIN Number
*   Date of Hire
*   Date of Contract End
*   MLS ID 
*   MLS Board

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-AgentView.jpg)

General Ledger Mapping of Third-Party Advance Payable  
We’ve updated the General Ledger to notify users when the Third-Party Advance Payable is configured but the Record Transaction Clearing Activity is not mapped to the corresponding general ledger account.   
This improvement aims to prevent transaction imbalances when transactions are integrated with QuickBooks® 

API   
We’ve enhanced the Commissions Online API to allow administrators the ability to easily add, edit and manage agent accounts in Commissions Online. 

CC Contacts When Sending Documents Through eSignature  
We’ve added the option to copy (CC) contacts when sending documents through eSignature.   
Now, when sending the Disbursement Authorization from a transaction, users have the option to select contacts associated with the transaction to receive the email sent to the signer.   
The CC recipients will receive email notifications when a signing session is sent and completed. Additionally, they will also be able to download the signed documents.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/05%20May/2024-Commissions-May-CCContact.jpg)  
 

Bug Fixes

1\. We fixed an issue with the date being set back to year 1930 when the Apply Cap to Commission Plan Deductions is enabled. 

Previously, when the Apply Cap is enabled on a Commission Plan Deductions and a custom date is set, clicking the back arrow would cause the custom date to be set to the year 1930.

Now, this issue has been resolved and custom dates will not be reset. 

2\. We fixed an issue with the QuickBooks® Profit and Loss report was not balancing.

Previously, when Third Party Advance is enabled and agent is paid by the title company the QuickBooks® profit and loss report was not balanced. 

Now, this issue has been resolved.