
# Constellation1 Commissions June 2023 Release Notes v2.3

Production Release: June 14, 2023 v2.3

## RELEASE SUMMARY

  
**Dashboard Widgets:** Filter selections will remain.   
**Dropdown Options:** Administrators can customize the display order of dropdown list items.   
**Transaction Sorting:** Sort transactions by transaction number.   
**Transaction Detail Saving:** Added notification of unsaved data when navigating away from page.   
**Canceled Transactions:** Added date filter option for canceled transactions.   
**Agent Transaction Statements:** Send multiple statements in one email.   
**Transaction Held By:** Added option to select your company from dropdown more easily.  
**Agent View:** Give agents read-only access to their listings and transactions.    
**Agent View:** Removed Company Net from Agent Profile page.   
**Commission Plans:** Filter selections will remain.   
**Commission Tax Amount:** Added option to override tax amount.   
**Contact Sync:** Added option to save and sync contacts to QuickBooks® with one click.   
**Vendor Tax Forms:** Added option to issue tax documents to vendors.  
**Payee-Specific Tax Numbers:** Tax Number field are now specific to payee type.  
**Company Contact Card:** Updated contacts so your company sorts to the top of the list.   
**Accounting Integration:** Removed references to account features and functionality when there is no accounting integration.   
**Office Accounting ID:** Added ability to reset office integration with QuickBooks.  
**General Ledger:** Added option to pay referrals and cooperating brokerages from trust account.   
**General Ledger:** Added ability to edit names in the general ledger.   
**Disbursement Authorization:** Updated to include a property’s list price.   
**Pre-Built Reports:** Hidden unnecessary filters on pre-built reports.   
**Custom Reports:** Added filters to include tax on custom reports.   
**User Interface:** Active field is highlighted.   
**Bug Fixes** 

## RELEASE DETAILS

  
Dashboard Widgets   
In a recent release, we updated the dashboard widgets to allow a user to select and display Pending and Closed transactions. When a user changes the dashboard widget settings, the settings will remain as selected until the user changes them again, even if the user navigates away and then returns to the dashboard.  

Customizable Dropdown Options   
We’ve updated our field settings to give administrators the ability to customize the options and sort order of certain dropdown lists.   
In System Settings > Advanced Settings > Field Settings, we’ve added clickable icons next to each item to allow the administrator to edit the existing options and change their sort order.   
By default, the items sort in alphabetical order. Now, an administrator can favorite their desired items, which will then sort to the top of the list in alphabetical order.  
These new icons will show when the user hovers their mouse over on an item in the list.   
The new icons are:

*   Star: Sets the item as a favorite.
*   Trash: Deletes the item.
*   Edit: Allows the user to edit the item’s name.

These new settings are available for the following dropdowns:

*   Transaction Type
*   Property Type
*   Lead Source
*   Conditions

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-favorite.png)

Sorting by Transaction Number  
We’ve added the option to sort transactions by transaction number. On the Transactions page, a user can click the Transactions Number column to sort the listed transactions in either ascending or descending order. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-TransactionSort.png)

Transaction Detail Saving  
We’ve added validation to the Transaction Detail page to notify the user if there is unsaved data on the page if they try to navigate away.   
If there is unsaved data, the user will see a modal presenting them with the option to save their changes. Clicking Yes will save the user’s work before they continue their navigation. Clicking No will let the user navigate away without saving.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-SaveChanges.png)  
 

Filtering Canceled Transactions by Date  
We’ve updated the filtering functionality on the Transactions page to allow the user to filter canceled transactions by date range in addition to pending transactions. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-TransactionSearch.png)

Agent Transaction Statements Delivery Options    
We’ve updated the statement delivery options in the workflow of the closing process to allow a user to send a single combined Agent Check Stub and Agent Commission Statement when one agent represented both sides of a transaction. This feature is also available in the Statement Delivery under the Action menu.  
This update improves the workflow when closing a transaction and will include both the sell side and buy side statements into one emailed document. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-Statements.png)

Transactions – Company Name Available in Held By Field   
We’ve added the option to easily select your company in the Held By field in the Deposits section of a transaction.   
After clicking the Held By dropdown, the user will be presented with a “+My Company” option. The user can click it to add the company name to the Held By field, saving the user from having to search for their company name in the list. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-HeldBy.png)

Agent View – Read-Only View of Transactions and Listings   
We’ve added a new permission to the Agent View to allow agents to add or edit their listings and transactions.   
In System Settings, in the Permissions section on the Agent View page, we’ve added a Listing & Transaction Access option with a toggle that allows the administrator to set whether an agent can add and edit their listings and transactions. When this option is toggled off, agents will have read-only access to their listings and transactions.   
This setting is enabled by default. To allow an agent read only access, an administrator will need to disable this setting.  

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-EditListingTrans.png)

Agent View – Removed Company Net from Agent Profile  
We’ve updated the Agent View and removed Company Net from the Commission Summary section on the agent profile page. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-ComanyNet.png)  
_Old view of the agent profile where the Company Net column was located._

Commission Plans  
We’ve changed the functionality of the filters on the Commission Plans page. Once the filter options are set, the settings will be retained and will remain that way when the user navigates within the Commissions module.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-CommissionsFilters.png)

Override Tax Amount for a Commission   
In some cases, depending on the commission and tax calculation, the tax amount for a commission could be incorrect by up to ± 3 cents. We’ve added the ability for a user to override the tax amount for a commission and adjust it by up to 3 cents in the Commission tab for a transaction. This feature is available when the Enable Tax toggle in Advanced Settings is on. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-Tax.png)  
 

To adjust the tax amount, the user can click the tax amount field shown below, enter the correct amount, then click Save.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-Tax2.png)

Contact Sync  
We’ve added the ability for users to save and sync contacts with QuickBooks® with a single click.   
When saving a contact that has already been synced with QuickBooks®, the save button will have a dropdown that will display the options to Save or Save & Sync. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-Contacts_SaveSync2.png)

  
Tax Reporting for Vendors   
We’ve added a toggle to enable tax documentation generation for vendors on the Contacts page.   
Tax documentation includes 1099 forms in the US and T4A forms in Canada. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-ContactTax.png)

  
Not all vendors require these forms. If you are unsure, check what your settings should be with your accountant. When enabled, the system will automatically generate the applicable form for the vendor at tax time.

Customized Tax Field Based on Payee Type   
We’ve updated how relevant tax number fields display on the Contacts page so that the appropriate field displays only for the payee type it applies to. 

When the Payee Type in the contact record is set to Company, the system will now only display the Tax Number field relevant to companies (EIN in the United States, Business Number in Canada). This will help users avoid confusion about which fields they need to fill in for the contact.

The relevant individual fields will continue to display when the Payee Type is an individual. These options are available when tax is enabled for the company.  

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-Tax-EIN.png)  
_Contact type is Individual.  
_

  _![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-SansTax-EIN.png)_  
_Contact type is Company._

Company Contact Card  
We’ve updated the Contacts page to display your company contact record at the top of the page. This update makes it easier to find your company in the list of contacts. 

Accounting Integration  
We’ve updated the system to be more intuitive and user friendly when Commissions Online does not have any accounting integrations. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-Accounting.png)

  
Some of the changes include:

*   Removing Accounting from the left navigation
*   Removing the Expenses tab from the Agent Details page
*   Removing the options to sync with the accounting system in the general ledger
*   Removing the options to sync or reverse closed transactions in Transactions

We’ve also updated the closing process. When closing a transaction, on the Payment Information page, we’ve removed the Pending Expense Amount, Payment Amount, and Agent Commission Check Amount After Expense columns. We’ve also removed the Process button. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-Transaction-Close.png)

Resetting Office Accounting ID   
We’ve added the option for an administrator to reset the Accounting ID for an office.   
In System Settings, under Office, in the Edit Office section, we’ve added a Reset Accounting ID button to reset the existing integration with QuickBooks Online for the selected office. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-AccountingID.png)

  
New General Ledger Toggle  
We’ve added a new toggle to the General Ledger settings called Pay Referrals & Coop Brokerages from Trust Account.   
When this toggle is on, referral and cooperating brokerage payments will be disbursed from the trust account.   
This setting is off by default.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-GL-PayFromTrust.png)

Edit Names in the General Ledger  
We’ve added the ability to edit names in the Commissions Online general ledger.   
We’ve added an Edit icon next to each item in the dropdown that allows the user to edit the label. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-GLEdit.png) The updated name will not sync with QuickBooks® Online, it will only show in the Commissions Online General Ledger. 

Disbursement Authorization Template Update  
We’ve added List Price to the Disbursement Authorization Master Template. The template can be downloaded, modified, and uploaded as a custom template.

When a Disbursement Authorization Letter is generated, the list price of a property can now be included along with the sale price.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-DisbursmentTemplate.png)

_Disbursement Authorization Master Template_

Report Filter Updates   
We’ve updated how the filters available for pre-built reports display.   
Some reports display filter options that don’t apply to that specific report. In the past, these options were grayed out. Now, we’ve removed these filters from the filters section for a cleaner interface.   
This update has been applied to all pre-built reports that had filter fields that were grayed out. For example, for the Agent Incentive Level Report, we’ve removed the Transaction Status, Transaction Type, and Basis Date fields (shown below), so they will no longer appear.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-OOBFilters.png)  
 

Changes to Custom Reports   
We’ve updated custom reports to include tax-related data points.   
There are tax data fields in several reports, including the pre-built Agent Income Summary Report. However, if a user copied and saved this report as a custom report, these data fields were not included in the custom report.  
Now, when the Agent Income Summary Report is copied, these data fields will be included.  
The data fields that will be included are:  
•    Total Deductions Tax   
•    Bonus Override Tax   
•    Agent Net Tax   
•    Total Tax   
These data fields are also available in other custom reports.  

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-CustomReportTax.png)

User Interface Update  
We’ve updated the user interface to highlight the active field on the page. The active field will now display with a blue line around the text box. This update helps the user to quickly see what field they are working in. 

  
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/06%20June%202023/2023-Commissions-June-highlight.png)

Bug Fixes

1\. We fixed an issue with the system locking up when calculating a commission that exceeds 100%.

Previously, when a commission exceeded the sale price of the transaction, the system would lock up. 

Now, when calculating a commission that exceeds 100%, the system will calculate the correct amount and percentage without locking. For example, for a commission rule where % = 100% plus a flat amount of $55, a sale price of $1,000 will calculate a commission amount of $1,055, which, expressed as a percent, is 105.5%. 

2\. We fixed an issue with Commission Deduction fields showing twice on custom reports where the agent represents both sides of the transaction. 

Previously, when an agent represented both sides of a transaction and the custom report included agent deductions, the deductions would show twice.

Now, when agent deductions are calculated on custom reports where the agent represents both sides of a transaction, the deductions will show once and be calculated correctly as expected. 

3\. We fixed an issue with the Award Allocation not showing on custom reports. 

Previously, when the Transaction Commission Detail report was copied, the Award Allocation was not included in the custom report. 

Now, when the Transaction Commission Detail report is copied, the Award Allocation will be included in the custom report.