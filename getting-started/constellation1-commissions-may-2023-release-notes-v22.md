---
title: Constellation1 Commissions May 2023 Release Notes v2.2
---

# Constellation1 Commissions May 2023 Release Notes v2.2

Production Release: May 9, 2023 v2.2

## RELEASE SUMMARY

  
**Dashboard Widgets:** Improved filtering options for dashboard widgets.   
**Adding New Deductions:** Create new deduction rules for a commission plan on the fly.   
**Transfer Trust Deposits:** Transfer trust deposits to another transaction.   
**Partial Payment Transaction Letters:** Added option to generate letters for partial payments.   
**Closing Errors:** Updated Closing Wizard to show all closing errors first.   
**Add New Contacts:** Users can add new contacts to transactions and commission rules.   
**Sync Trust Option:** Updated Sync to Accounting System toggle label.  
**Inactive Commission Plans:** Added ability to set plans to inactive.   
**Inactive Deductions:** Added ability to set deductions to inactive.   
**Inactive Offices and Contacts:** Added ability to set offices and contacts to inactive.   
**Importing Transactions:** Added ability to run commission calculations automatically when importing transactions.   
**New TMS Integrations:** Add interactions to Dotloop and SkySlope.  
**Custom Report Formatting:** Add formatting tools to custom reports and removed the Run button.   
**New Custom Report Filter:** Added Agent Split to custom reports.   
**Custom Reports for Agents:** Custom reports can be made available individually to agents.   
**Bug Fixes**

## RELEASE DETAILS

  
Dashboard Widgets  
We’ve improved the functionality of our dashboard widgets by adding the ability to display Pending and Closed Transactions according to the user’s filters.   
On the dashboard widget, select Pending or Closed, then set the time frame. Click the number in the center of the widget to view the filtered list. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-Dashboard.jpg)  
 

Create New Deductions  
We’ve added the ability for a user to create new deductions on the fly from the Deductions dropdown on the Commission Plans and Commission Rules pages in the Commissions module.   
A user now has the option to create and add new deductions without leaving the workflow on the Commission Rules page.   
In the Deductions section, the user can select + Create New Deduction from the dropdown if the kind of rule the user wants to apply doesn’t exist.  

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-AddDedcution.png)

After clicking + Add New Deduction, the user will see a modal where they can enter the Deduction Name, Payee, Receivable Account, Expense Account, and choose whether to toggle the Exclude from Company Dollar, Taxable, and Withholding options on (the default is off).

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-AddDedcution2.png)  
 Selecting Save will add the new deduction to the current commission plan and apply it to any transactions currently associated with that commission plan. 

Transfer Trust Deposit to Another Transaction  
We’ve added the ability to transfer trust deposits from one transaction to another.   
Within a transaction, on the Details page under Deposits, we’ve added an option to the Action menu to Transfer Deposits. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-TransferDeposit.png)

When selected, the user will be presented with a wizard where they can select the transaction to which the deposit should be applied.  

Partial Payment Transaction Letters  
We’ve added the option to generate letters for transactions with partial payments.   
Within a transaction, on the Contacts page, we’ve added a new dropdown to the Transaction Resource Letter modal titled Payment Level.   
The user can generate letters for every payment level, including either partial or full payments toward a transaction. Multiple partial payments are added to the dropdown dynamically as Payment 1, Payment 2, etc.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-PartialPaymentLetter.png)

_Select the letter template and payment level._  

Closing Transaction Wizard  
We’ve added a new Notification step to the Closing Wizard where we display all the errors or warnings associated with the closing, making it easy to see them all at once before taking action. These will appear in the Errors section.  
The current transaction closing workflow remains unchanged. If there are any errors associated with a transaction, the user will need to correct them before the transaction can be closed.   
Warning and error messages may include:  
•    SSN/SIN missing   
•    Agent missing  
•    Buyer or Seller missing  
•    Partial transactions with Pending statuses 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-ClosingTrans.png)

Add New Contacts to Transactions and Commission Rules  
We’ve improved the workflow for adding new contacts directly to a transaction, a commission rule, or a deduction.   
Administrators can now add new contacts on the fly to the system without leaving their current workflow. 

Contacts can be added in the following places:  
•    Transaction Details > Deposits > Add Deposit > Disbursement  
•    Transaction > Commission > Deductions   
•    Commission Rules > Deductions 

**Transaction Details > Deposits > Add Deposits > Disbursement**  
On a Transaction Details page, in the Deposits section, click the Action button and select Add Deposit / Disbursement.   
In the Add Deposit / Disbursement modal, select + Add Transaction Contact from the Payee dropdown. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-AddContactDip-Disbursment.png)  
 

**Transaction > Commission > Deductions**  
On a transaction’s Commission page, add a deduction or edit an existing one.    
In the Select Calculation Basis and Payee modal, select Add New Contact from the Payee dropdown. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-AddDedcutionPayee.png)

  
 **Commission Rules > Deductions**  
In the Commissions module, on the Commission Rules tab, in the Deductions section.  
To add the new contact, Edit the deduction and select Add New Contact from the Payee dropdown.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-AddCommissionRuleContactAdminFee.png)

Trust Deposits   
We’ve updated the label for the Sync Trust toggle under Transaction Details > Add Deposit / Disbursement for a more intuitive user experience.   
The new label is Sync to Accounting System. We’ve also added an informative tooltip to explain to users what the toggle is for. When the user hovers their mouse over the ⓘ icon, they will see the following message:  
If sync is deselected, the entry will never be posted to the accounting system.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-DontDeposit.png)

  
The functionality remains the same: when toggled off, the deposit or disbursement will not be posted to the accounting system. When toggled on, it will post as expected.  
The label in the Integration Status column in the Deposits section has also been updated to Do Not Post when this is togged off for a particular deposit.   
•    Do Not Post means the item will not be posted to the accounting system.   
•    Not Yet Posted means the item has not been posted yet, the posting is pending. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-DoNotPost.png)

Set Commission Plans to Inactive  
We’ve added the ability to set commissions plans that are no longer used to Inactive.   
In a commission plan, under Advanced Options, we’ve added a toggle to set the commission plan to Inactive. Commission plans that are set to Inactive will not be available to add to a transaction. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-InactiveCommission.png)  

In addition, we’ve added a dropdown to allow the user to filter by active or inactive status on the Commissions Plans page. 

Set Deductions to Inactive   
We’ve added the ability to set deductions that are no longer used to inactive.   
In a commission plan, in the Deductions tab, we’ve added a toggle to set the deduction to inactive. Deductions that are set to inactive will not be available to add to a transaction. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-Deduction.png)

  
 In addition, we’ve added a dropdown to allow the user to filter by active or inactive status in the Deductions tab.   
 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-DeductionFilter.png)

Set Offices and Contacts to Inactive  
We’ve added the ability to set offices and contacts to Inactive. Offices and contacts that are set to inactive will no longer be able to be added to a transaction or commission plan.   
**Contacts**  
On the Edit Contact page, we’ve added an Active toggle to set the contact status. To set a contact to inactive, turn the toggle off, then click Save.

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-ContactActive.png)  
_Edit Contact Page_

**Offices**  
On the Edit Office page, we’ve added an Active toggle to set the office status. To set an office to inactive, turn the toggle off, then click Save.

   
_![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-Office.png)_

_Edit Office Page_

Contacts and offices may not be set to inactive if the following conditions apply:  
•    Contact/office is attached to any pending transaction  
•    Contact/office is attached to any active deductions as a payee  
•    Contact/office is attached to any active agent bonus override recipient

In these cases, the user will receive a warning message and the action will not be completed.  
We’ve also added the ability to filter contacts and offices by active or inactive status. At the top of the Contacts and Office pages, there is a new dropdown next to the search bar.

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-ContactSearch.png)  
Contacts

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-OfficeSearch.png)  
Office 

Updated Transaction Import Process  
We’ve updated the transaction import process by adding a Run Commission Calculations on Import toggle.  
When toggled on, the commission calculations for the transaction will be calculated automatically upon import.   
The addition of this feature is designed to remove the necessary step of forcing the user to first import a transaction, then navigate to the Commissions to initiate the commission calculation. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-Import.png)

  
 **Note:** When toggled on, it may slow the import process as more needs to happen in the background to complete the import.

Improved Integrations   
We’ve improved transaction management software integrations to allow users to integrate with Dotloop and SkySlope.   
In the Integrations > Transaction Management section, click on the name of the TMS to be integrated with Commissions Online. A setup wizard will open, simply follow the instructions to complete the integration. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-Integrations.png)

   
Be prepared to provide the following information to complete the connection:  
•    **Dotloop:** You’ll need your TMS login information then have to approve Commissions Online access from Dotloop.   
•    **SkySlope:** You’ll need your Access Key and Secret.

Custom Report Formatting  
We’ve updated custom reports to include more formatting options.   
For custom reports, under Filters > Formatting, we added the following options:

*   Group By
    *   Agent or Office
*   Sub-Totals
    *   Totals or Averages
*   Totals
    *   Totals or Averages
*   Export Page Break Formatting
    *   Agent or Office
    *   Added to Pre-Built Reports
*   Sort By
    *   Multi-select option 

With this update, we’ve removed the Summary Type and replaced it with Group By and Sub-Totals.  
The Group By option will export to PDF and CSV format, the other options will only export to PDF.   
These options are available on pre-built reports that are copied. The user can then apply these options to the saved copy of the pre-built report. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-ReporsGroupBy.png)

We’ve also removed the Run button from custom reports. The run functionality has been incorporated into the Export button. 

  
New Custom Report Filter   
We’ve added a new report field to custom reports titled Agent Split. The Agent Split shows the current agent split percentage collected from the current transaction.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-AgentSplit.png)

Custom Reports for Agents  
We’ve enhanced agent access to custom reports, and administrators can now make specific reports available to agents.   
Reports can be enabled for agents in System Settings > User Permissions > Manage Permissions > Agent View.   
We’ve added a new section titled Custom Report Access. The administrator can enable reports individually so they are available to agents.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/05%20May%202023/2023-Commissions-May-ReportsAgentview.png)

  
 When a report is toggled on, it will be available to agents in the left navigation of the Reports section. Agents will then be able to run, view, and download the reports.

Bug Fixes  
1\. We fixed an issue with the Balance Due for a buy side transaction when the selling brokerage is holding the deposit.  
Previously, when the selling brokerage was holding the deposit, the buy side of the transaction was showing an incorrect balance due.   
Now, this issue has been corrected and the balance due will be correctly calculated. 

2\. We fixed an issue with the company dollar being deducted from an agent commission tier when the Exclude from Commission Tier was toggled on, causing the agent tier to be incorrectly calculated on the agent check stub report.    
Previously, when the Exclude from Commission Tier was togged on, the company dollar was being deducted from the agent commission tier before this transaction.   
Now, when the Exclude from Commission Tier is toggled on, the company dollar will not be deducted from the agent commission tier and the agent check stub will be calculated correctly.