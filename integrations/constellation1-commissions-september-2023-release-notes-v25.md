---
title: Constellation1 Commissions September 2023 Release Notes v2.5
---

# Constellation1 Commissions September 2023 Release Notes v2.5

Production Release: September 6, 2023, v 2.5

## RELEASE SUMMARY

  
**Enterprise Insights Dashboard:** Added more filter options.   
**Enterprise Insights Transactions:** Enabled sorting by column header and added cancelled transactions.   
**Annual Production Chart:** Updated the Annual Production chart to include ends.   
**Custom Templates:** Removed option to share some custom templates with agents.   
**Commission Plan Recalculation:** Added option to recalculate commission totals after the agent's default plan is changed.   
**Deactivate Commission Rules:** Added ability to set rules to inactive.   
**Referral Contact Address:** Added contact address to search results when adding contact as a referral.   
**Default State or Province:** Set company’s state or province as default.   
**Commissions from Multiple Contacts:** Added option to receive commissions from multiple contacts.   
**Accounts Receivable Sync:** Added ability to automatically sync accounts receivable at closing.   
**Cost of Improvements:** Added field to account for tax deductible improvements in tax calculations.   
**Flat Amounts:** Added ability to enter a negative number in the Flat Amount field.   
**Sync Batch Errors:** Added new error messages when batch deposits and batch checks fail to sync.   
**Billing Report:** Added new billing report.   
**Transaction Commission Detail Report:** Added as an option to the Report Scheduler.   
**Canadian T4A forms:** Added support for T4A Canadian tax form.   
**British Virgin Islands:** Added support for the British Virgin Islands.   
**User Interface:** Updates for a better user experience.   
**Anywhere:** Updated the MLS Boards field.  
**Bug Fixes**

## RELEASE DETAILS

Enterprise Insights  
We introduced our new Enterprise Insights feature in the July 2023 release. As we continue to improve this feature, we’ll include all updates in the Commissions Online release notes.   
For more information, please refer to our July release notes.   
[July Release Notes](https://constellation1.na3.teamsupport.com/knowledgeBase/21025925)

Enterprise Insights Dashboard  
We’ve added Year to Date and Custom Date Range options to the date filter dropdown on the Enterprise Insights Dashboard.   
When Year to Date is selected, the Dashboard widgets will show data for the calendar year to date.   
Custom Date Range allows the user to enter the exact date range for which they want data to display. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-DashboardTiles.png)

Enterprise Insights Transactions  
We’ve added the ability to sort transactions by column header. On the Transactions page, the column header is now clickable, allowing the user to sort transactions by:

*   MLS ID
*   Street
*   City
*   State
*   Represents
*   Close Date 
*   Sales Volume
*   Agent Net
*   Brokerage Net  
     

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-EntInsigSortTrans.png)

Additionally, we’ve added the ability to filter cancelled transactions. On the Transaction page, Cancelled has been added as a filter option to the status list.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-EntInsigCanceledTrans.png)

Annual Production Chart   
We’ve updated the Annual Production chart on the Commissions Online Dashboard to include the number of ends as a filter option.    
We’ve added the option to select $ Values or # Ends on the chart, allowing the user to switch between these two options. The user can download the chart in various formats, including different image formats and as a PDF, CSV, or XLS. Click the hamburger menu to the right of the toggle to access the download options.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-DashboardProdChart.jpg)

Custom Templates  
We recently added the option to share custom templates with agents. In this release, we’ve removed the option to share templates that do not apply to agents.   
The custom templates that can be shared with agents are:

*   Agent Check Stub Report
*   Agent Commission Statement
*   Assistant Commission Statement 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-AgentTemplateToggle.png) 

The toggle shown above will no longer appear as an option for other reports.

Commission Plan Recalculation We’ve added the option to recalculate agents’ commissions if their default commission plan is changed.   
After the user changes an agent’s default commission plan, they will be prompted to recalculate the commissions for all the agent’s open transactions.    
This eliminates the need to delete the agent, then re-add them to their transactions for the new commission calculation to be applied.   
After changing the default commission plan, the user now has the option to:

*   Cancel
    *   Reverts to the previous default plan without saving
*   Save Only
    *   Saves the new default and only applies the new commission rule to newly added transactions
*   Save & Recalculate
    *   Saves the new default and recalculates the commission amount for all open transactions

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-ReCalculateComm.jpg)

  
 Set Commission Rules to Inactive  
We’ve added the ability to set commission rules that are no longer used to inactive. We’ve added an Active toggle to each commission rule that allows the user to set a commission rule to active or inactive. Commission rules are active by default.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-CommissionRuleInactive.png)

  
 Inactive rules will not show in the list of commission rules when creating a transaction. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-CommissionRuleInactive2.jpg)

  
Rules that are associated with a pending transaction cannot be set to inactive. If the user tries to set such a rule to inactive, they will see a message alerting them to the number of transactions associated with the rule.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-CommissionRuleInactive1.png)

Referral Contacts Address  
We’ve added contact addresses to the predictive options when adding a referral to a transaction.   
If there are multiple contacts with the same name, displaying the contact address will make it easier to identify the correct contact to add to the transaction. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-RefurralContact2.jpg)

Note that if the contact record does not include an address, no address information will display.

Default State or Province  
We’ve updated Commissions Online to default to the state or province shown in the company profile when creating a new transaction. 

Commissions From Multiple Contacts  
We’ve added the ability for a transaction to record commissions from multiple contacts.   
In a transaction, on the Commissions page under Commission Details > Additional Detail, a user can add multiple contacts in the Commission Receivable From box. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-MultiCommissions.png)

Adding an additional contacts will require the following information:  
•    Commission Receivable From  
•    Check Amount  
•    Check Number  
•    Check Date

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-MultiCommissions2.png)

The total commission amount from all contacts must match the total commission amount. An amount mismatch will cause an error when closing the transaction.

  
Accounts Receivable Sync  
We’ve added the ability to sync accounts receivable in the Closing Wizard.   
We’ve added a Sync Accounts Receivable Now toggle to the Payment Information page of the Closing Wizard. When enabled, accounts receivable will sync as they currently do in the Expense tab of an agent profile.   
This updated workflow removes the need to navigate to the Expense tab for each agent and sync accounts receivable manually before generating the Agent Check Stub Report. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-CloseSyncTrans.png)

Transaction – Cost of Improvements   
We’ve added a Cost of Improvements field to Transactions in the Additional Details section of the Details page.   
Cost of Improvements is a new field where the user can enter the dollar amount of total improvements made to a property. The dollar amount is factored into the tax calculation for the adjusted gross commission. This feature can be used as a tax override to account for tax deductions permitted by law.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-CostOfImp.png)

Flat Amount Commission Rule   
We’ve added the ability to enter a negative dollar amount in the Flat Amount field for a commission rule.   
In Commissions, in the Commission Rules tab, a user can now enter a negative dollar amount in the Flat Amount field. This is another way to include a deduction in the commission rule. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-CommRuleNegNum.png)

  
Sync Batch Errors  
We’ve updated the on-screen text for batch sync errors for batch deposits and batch checks in the Accounting module.  
The new errors inform the user if the batch sync failed and provide more details about why it failed. 

Billing Report    
We’ve added a new Billing Report to the Reports module. The Billing Report is configured to show the number of billable transactions in a given month.   
A transaction is counted in the billing report when it’s closed within the billing month (UTC time-zone). Reopened and closed transactions will not be counted additional times. There is an information icon with more details about the billing report.  
We’ve added a new permission called View Billings to the Permissions section that can be enabled for Management User and Office Administrator accounts, allowing them to access the report. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-Billing3.jpg)

  
The Billing report includes:

*   Transaction #
*   Address
*   City
*   State/Province
*   System Close Date
*   Process Date

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-BillingReport.png)

Transaction Commission Detail Report   
We’ve added the Transaction Commission Detail Report as an option to the Report Scheduler. Users can now schedule this report to run automatically.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-ReportSchduler.png)

Canadian T4A forms   
We’ve added support for Canadian T4A tax form in the Agents module for Canadian tax reporting. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-T4A.png)

  
A user can select an agent using the check box next to their name, then click the Action menu to:

*   Review
    *   Review and modify the information.
*   Generate T4A
    *   Create a PDF.
*   Generate eFile
    *   Create an electronic form in XML format.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-T4Areview.png)   
_Review page_

British Virgin Islands  
We’ve added the British Virgin Islands as an option to the country dropdown on the Company page. Commissions Online will now dynamically update the related geographical features, such as city and state, for the British Virgin Islands. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-BVI.png)

User Interface Update  
We’ve updated the Accounting module to display accounting integration errors in red to draw users’ attention to them, so they can be corrected.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-ErrorsInRed.png)

Anywhere (Formerly Realogy) – Updated MLS Boards  
We’ve changed the MLS Board field on the Agent Details page under Additional Details to a dropdown. When the user types in the field, a filtered list of MLS boards will display for easier selection.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/09%20Sept/2023-Commissions-Sept-AgentMLSBoard.png)

Bug Fixes

1\. We fixed an issue with Shared Non-Commission Income not showing the customized name on reports.   
Previously, when the label for Shared Non-Commission Income was changed, the updated name didn’t display on the relevant reports.   
Now, when there is a customized name for Shared Non-Commission Income, the report will display the customized name. 

2\. We fixed an issue with the buyer’s name showing on the Closing Review when it should have displayed the buyer’s or seller’s attorney’s name.   
Previously, on the Closing Review, the buyers name, or the sellers name, was shown when it should have been the buyer’s attorney’s name or the sellers attorney’s name.   
Now, this issue has been corrected and the buyer’s attorney’s name or seller’s attorney’s name will show on the Closing Review page.

3\. We fixed an issue with the transaction screen freezing when an agent tried to view their transactions.   
Previously, when Conditions Tracking and the agent permission to add/edit their transactions were both disabled, the transaction page would freeze when the agent tried to view their transactions.   
Now, we’ve updated the logic for these settings and this issue has been resolved. 

4\. We fixed an issue with a trust account disbursing more funds than were in the account.   
Previously, when closing a transaction where the company represented the seller, if the company had enabled the Pay Referrals & Coop Brokers from Trust Account option for the general ledger, the system would disburse funds to both, causing the trust account to be overdrawn.   
Now, this issue has been corrected and the system will only disburse funds to the required entity.