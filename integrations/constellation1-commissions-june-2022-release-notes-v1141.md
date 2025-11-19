# Constellation1 Commissions June 2022 Release Notes v1.14.1

Production Release: June 2022 v1.14.1

### Release Summary&#x20;

**Transaction Imports from Dotloop:** Offer Acceptance Date will be auto-populated from the Contract Agreement Date.

**Transaction Numbering:** Transaction numbers can be auto-assigned to transactions that are converted from listings.&#x20;

**Transaction Number Validation:** Added validation to prevent duplicates. &#x20;

**Sort Listings and Transactions:** Added sorting by column header.

**Transaction Landing Page:** Added ability to customize which columns display.&#x20;

**Commission Plan, Company Portion:** Added the ability to include deductions from the company portion of a commission.&#x20;

**Agent Bonus Override:** Added the ability to calculate a bonus override based on sale price.

**Partial Payment Transactions:** Added ability to edit the sale price.&#x20;

**General Ledger:** Improved user interface.&#x20;

**Improved Transaction Closing:** Added the ability to close transactions on the Contacts and Commission tabs.&#x20;

**Reports:** Added two new pre-built reports.&#x20;

**Enhanced Report:** Updated the Transactions Commission Detail report.&#x20;

**Review Closing Document:** Added auto-generated closing information document to the transaction’s Documents tab.&#x20;

**Bug Fixes**

## Release Details

Transaction Import – Dotloop\
We’ve improved transaction imports from Dotloop. \
Previously, Constellation1 Commissions would populate the Offer Acceptance Date with the date of the import. \
Now, the Contract Agreement Date in Dotloop will auto-populate the Offer Acceptance Date field with the correct date.

Transaction Numbering\
We’ve improved the numbering of transactions when they are converted from listings.&#x20;

Previously, a transaction number had to be manually assigned when converting a listing to Pending. The auto-assign only provided a transaction number to new or imported transactions.

Now, when Transaction Number Auto Generation is enabled, Constellation1 Commissions will assign the next sequential number to the transaction.

This setting is located in the Transaction Settings section of Advanced Settings in System Settings. When enabled, the user can also set the starting number in the field provided.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-TransactionNumbers.png)

Transaction Number Validation\
We’ve added logic to validate transaction numbers, whether imported or added manually.

Previously, users could manage transaction numbers, allowing for the possibility of duplicates. Now, when importing or manually creating transactions in Constellation1 Commissions, the system will check the transaction number to confirm it is unique. If the system finds an existing transaction number, the user will receive an error message alerting them of the transaction number conflict.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-DupTransError.png)

Import Page – Sort Listings and Transactions\
We’ve added the ability to sort listings and transactions by the column header on their respective import pages.

The sort columns for imported listings are:&#x20;

* Address
* MLS Number
* Listing Date
* Listing Price

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/91cb6c64-5527-4e60-9154-6fc120da4c87.png)

The sort columns for imported transactions are:&#x20;

* Address&#x20;
* Status
* MLS Number
* Close Date
* Sale Price

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-ImportTransactionsxxx.png)

&#x20;\
Transaction Landing Page\
We’ve added the option to customize which columns display on the Transaction Landing page. A user can select up to 6 columns, including Transaction Number, they would like to see on the Transactions landing page.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-TransactionHome.png)

Commission Plan – Deductions from Company Portion \
We’ve added Adjusted Company Portion as an option to the Deduct From dropdown on the Commission Plan Details page to include deductions from the company portion of a commission.\
Selecting this option will calculate the commission amount by deducting it from the company portion, thereby reducing the company net.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-CompanyDeduction.png)

Bonus Override \
We’ve added the option to calculate a bonus override based on a percent of the sale price.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-Bonus2.png)

Partial Payment Transaction \
We’ve added the ability to edit the sale price on transactions with partial payments. Previously, the sale prices for transactions with a partial payment were not editable.&#x20;

General Ledger UI Enhancement\
We’ve enhanced your ability to see account details on the General Ledger with general user interface improvements. We’ve removed the eye icon and added a dropdown to the fields. When clicking the dropdown arrow, the field will show the Account Number and Account Type.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-AccountsReceivable.png)

Improved Transaction Closing\
It’s now easier to close a transaction. We’ve added an Action menu with the option to close the transaction to the Contacts and Commission tabs. Previously, this menu was only available in the Details tab.&#x20;

&#x20;![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/06%20June%202022/2022-June-Commissions-CloseTrans.png)\
&#x20;&#x20;

New Pre-Built Reports\
We’ve created two new pre-built reports. Both reports are located in the Management Reports section.&#x20;

The new reports are:

**Monthly Activity Summary** – this report displays a year-over-year comparison of agent production.&#x20;

The report criteria are:

* Date Type: Close
* Date Range: (Current Month)
* Transaction Status: All (O-Pending, C-Closed, V-Canceled)
* Transaction Type: All   &#x20;
* Agents:  All   &#x20;
* Offices:  All   &#x20;

**Title/Escrow Details** – this report displays the title and escrow details for selected transactions.\
The report criteria are:

* Date Type: Close or Process
* Date Range: Month to Date, Year to Date or Custom
* Transaction Status: All (O-Pending, C-Closed, V-Canceled)
* Transaction Type: All  &#x20;
* Agents:  All  &#x20;
* Offices:  All &#x20;

Enhanced Transaction Commission Detail Report \
We’ve enhanced the Transaction Commission Detail report. \
In the Advanced Filters, a user can now group commission details by agent or office.&#x20;

Updates to the report include:

* Added a Referral Fee column
* Removed Status column
* Removed Grand Total line on the last page&#x20;

Review Closing Documentation \
When a transaction is closed, the system will generate a Review Closing Document and will now automatically upload it to the transaction’s Documents tab. \
If a transaction is re-opened and then closed again, the previous Review Closing Document will be overridden with an updated one in the Documents tab.

**Bug Fixes**&#x20;

Zero-dollar transaction commissions \
Fixed an issue with zero-dollar transaction commissions not being calculated accurately.

Previously, if an agent had a commission allocation of $0.00 (zero dollars) and the Gross Commission was updated with a flat amount, the commission calculations were inaccurate. This caused the company dollar amount to be incorrect.&#x20;

Now, when the agent commissions allocation is $0.00 (zero dollars) and the Gross Commission is updated, the calculations will be accurate.&#x20;

Improved QuickBooks® Integration\
Fixed an issue with Process Date being incorrect in QuickBooks®.

Previously, when integrating a transaction with QuickBooks®, the system would auto-populate the Process Date with the integration date, not the correct Process Date.&#x20;

Now, when integrating a transaction with QuickBooks®, the correct date will display.
