---
title: Constellation1 Commissions February 2025 Release Notes v4.1
---

# Constellation1 Commissions February 2025 Release Notes v4.1

Production Release: February 10, 2025, v4.1

## Release Summary  

**Checklists:** Added version numbers to forms selection menu.   
**Forms:** Added integration with eSign.   
**QuickBooks® Desktop Integration:** Updated messaging when maximum number of connections are reached.   
**API Webhooks:** Receive notifications in your applications for updates to transactions in Commissions Online.   
**API Create Transactions:** Added ability to create and manage transactions via our API.  
**Agent Imports:** Disabled auto-populating Anniversary Date in agent record.   
**Enterprise Insights:** Improve performance.  
**Reports:** Added Month to Date to Billing report.   
**User Interface Updates:** The label “Clone” has been changed to “Copy”.  
**Canadian Customers:** Updated link to T4A eFile tax information.   
**Bug Fixes**

## Release Detail

Checklists

We’ve enhanced the checklist forms to now show version numbers when adding forms to a checklist task.  

When adding a form to a checklist, the version number will be shown alongside the form name in the dropdown menu, enabling users to easily identify and select the correct version.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/02%20February/2025-Commissions-Feb-FormsVersion.png)

  
eSign Integration with Forms  
Commissions Online now offers eSignature integration for checklist forms, allowing agents and team leaders to seamlessly send forms to their buyers, sellers, and other contacts involved in a transaction for electronic signature.

When forms are provided to Constellation1, we can add signer tags to the document(s) making them eSignature-ready.

Within a transaction, on the Checklist page, next to the form, agents and team leaders can access and select the “eSignature” option from the action menu. This will prompt the agent to specify who the form should be sent to for signing via the eSign system.

  
This new eSign integration streamlines the signing process, providing a more efficient and convenient experience for everyone involved in a real estate transaction.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/02%20February/2025-Commissions-Feb-eSign.png)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/02%20February/2025-Commissions-Feb-eSignForms1.png)  
_Select Signers._

When a signing session begins the document will show on the Documents page along with the status.  
 

QuickBooks® Desktop  
We’ve updated the messaging when non-integrated users attempt to access QuickBooks® desktop in the Integrations module.  
The messaging informs the user of the limited number of connections to QuickBooks® desktop for their company.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/02%20February/2025-Commissions-Feb-QB-Inegrations1.png)

API Webhooks  
The Commissions Online API now features Webhooks functionality, which enables customers using the API to receive notifications within their own application when a transaction is closed in Commissions Online.

  
API – Create and Manage Transaction  
We’ve updated our API to now allow user to create and manage transactions in Commissions Online from an external application.  
API documentation is available upon request. 

  
Agent Imports

To improve data accuracy, we have disabled the automatic population of an agent's Anniversary Date when importing their record into Commissions Online. 

Previously, the Anniversary Date field was being filled with the date of the import, which could result in inaccurate information being added to the system. 

We’ve also enhanced the process of validating the agent anniversary date when applying various commission plans.

These changes help prevent incorrect anniversary data on commission plans in Commissions Online.

Enterprise Insights Performance  

The performance of Enterprise Insights has been optimized, resulting in a significantly faster loading of the dashboard page that improves overall efficiency and usability.

  
Reports

**Billing Report**

The billing report now includes a “Month to Date” section, which displays transactions processed up to the current date when the report is run mid-month. Additionally, the report will feature eSign sessions for the current month-to-date period.

User Interface Update

The label “Clone” label has been updated and changed to “Copy”, enhancing the system's intuitiveness and improving the overall user experience.

Canadian Customers T4A eFile  

We’ve updated the T4A eFile link to direct users to the correct page at: [https://apps.cra-arc.gc.ca/ebci/njfs/ext/disclaimer](https://apps.cra-arc.gc.ca/ebci/njfs/ext/disclaimer).

  
Bug Fixes

1\. We have resolved an issue that caused a "Resend" prompt to appear when users were editing or saving listings in the Firefox browser. 

Previously, Firefox users would receive this prompt when editing, saving, activating, or withdrawing a listing, suggesting their changes had not been saved. 

Now, this issue has now been resolved. Going forward, Firefox users will have a consistent experience with other browsers, without the unnecessary "Resend" prompt.

  
2\. We fixed an issue with not being able to scroll the Enterprise Insights page when filters are enabled.

Previously, when a user applied filters on the Enterprise Insights page, they were not able to scroll down the page. 

Now, this issue has been resolved. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/02%20February/2025-Commissions-Feb-EntPriseDashboard.png)

3\. We fixed an issue with the Sellers Attorney Letter displaying the incorrect dollar amount in the Less Deposit field. 

Previously, the Sellers Attorney Letter was showing $0.00 in the Less Deposit field when there was a GIC/Term Deposit issued. 

Now, this issue has been resolved. The Sellers Attorney Letter will show the correct dollar amount in the Less Deposit field even when there is a GIC/Term Deposit issued as reflected in the transaction. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/02%20February/2025-Commissions-Feb-SellerLetterLessDeposit.png)  
_Excerpt of the Sellers Attorney Letter showing the issue._