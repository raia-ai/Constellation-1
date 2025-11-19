# Constellation1 Commissions November 2024 Release Notes v3.8

Production Release: November 12, 2024, v3.8

## Release Summary&#x20;

**Transactions Deposit / Disbursement form:** Auto populates the deposited amount on the disbursement form and displays a warning message when the requested disbursements exceed the available deposits.\
**Transaction Imports:** Import Override saves its setting and other user Interface updates.\
**Transactions Module:** Add or remove columns and sort options have been updated. \
**Transaction Details:** Editing transaction number produces a warning message.\
**Transaction Checklists:** Agents and team leaders can now submit multiple tasks for approval. \
**My Workspace:** Improved the review process of multiple tasks for approval.\
**Reports:** User interface updates. \
**Transaction Commission Detail Report:** Added option to Filter by transaction number. \
**User Interface:** Updates\
**Bug Fixes**

## Release Details

Transactions Deposit / Disbursement Form\
We’ve updated the transactions Deposit / Disbursement form to automatically populate the “Amount” field when the selected Type is set to “Disbursement”, allowing users to easily view the total deposit amount without having to return to the transaction details page.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-DisbursementAmount.jpg)

Additionally, the system now displays a warning message when a user attempts to disburse more funds than have been deposited.&#x20;

In a transaction, under the Deposit card, the Add Deposit / Disbursement form will display a warning message alerting the user they are attempting to disburse more funds than deposited.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-DisbursementError.jpg)

Transaction Import\
The transaction import page has been updated to provide a more intuitive and user-friendly experience. Key changes include:

* The Transaction Import Override option now saves the user's preferred setting, ensuring it is remembered across sessions. Listing imports are not affected by this update.&#x20;
* A back button has been added for easier navigation.
* The label "Automated Sync" has been changed to "Sync Automation".
* The date range labels have been updated to "Added/Edited From – To".

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-ImportOverride.jpg)

Transactions Module\
The column selection option now remains open as users make changes, allowing for easier updates to the column headers. The selection box will automatically close when the user clicks outside of the selection box.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-TransColumnEdit.jpg)

Additionally, users can sort columns by Transaction Number, Address and Close Date. However, sorting by Property Type and Transaction Type has been disabled.&#x20;

Transaction Details – Edit Transaction Number \
The system now displays a warning message when an administrator attempts to edit the transaction number for any transaction that has been integrated with the accounting system.&#x20;

Additionally, the user will receive a warning when the Auto-Save feature is enabled.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-TransNumber.PNG)

Transaction Checklists – Multi-Select Tasks for Approval \
Agents and team leaders can now select one or more tasks individually and submit them for approval simultaneously.&#x20;

The updated Checklist page now includes checkboxes that allow users to select and submit for approval, one or more tasks at once, improving efficiency and convenience.

Tasks that are pending approval or have been completed are not available to be submitted again.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-SubmitTasks.jpg)

_Agent or Team Leader view._

My Workspace \
We’ve improved the transaction checklist review and approval process for administrators.&#x20;

When one or more agents submit checklist items from one or more transactions for approval, the approving administrator can view each transaction as a separate line item with one or more tasks awaiting approval on their My Workspace page, making the workflow more intuitive and easier to navigate.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-MyWorkspace.png)

Clicking the property address will take the administrator to the transaction's Checklist page where they can update the task(s).&#x20;

As each checklist task is completed, it will be automatically removed from the My Workspace page.

Reports \
We’ve updated the label of some buttons on the out of the box reports to be more intuitive. \
“Save” has been updated to “Save Filters”.\
“Run” has been updated to “Generate”.\
Custom reports are not affected by this update.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-ReportButtons.jpg)

Transaction Commission Detail Report\
Users can now filter the Transaction Commission Detail Report by Transaction Number.

In the Advanced filters of the out of the box report and the Report Scheduler, we’ve added a Transaction Number field where a user can enter a transaction number to create a report for that transaction.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-TransColumnDetailReport.jpg)

User Interface Updates\
The updated user interface now includes an "X" icon in all search boxes. When a user enters text into a search field, the "X" icon appears, allowing them to quickly and easily clear the search criteria with a single click.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-Search1.jpg)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-Search2.jpg)

We’ve also updated label "Run" on various transaction-related letters and reports to now display "Save" on the buttons.&#x20;

This updated includes the following but is not limited to, the Agent Commission Statement, Transaction Record Sheet, Conveyancer's Report, Disbursement Authorization, and Agent Check Stub and any other report generated from the word document templates.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/11%20November/2024-Commissions-Nov-Save.png)

Bug Fixes

1\. We fixed an issue with the display of the commission wizard when creating a commission plan.

Previously, when creating a commission plan, some of the steps were not highlighted to indicate the current step in the process.&#x20;

Now, the display issue with the wizard and has been resolved.&#x20;

2\. We fixed an issue with scheduled PDF reports not displaying the date/time in the top left corner.&#x20;

Previously, when a scheduled report was created in a PDF format, the date/time was missing from the top left corner.

Now, this issue has been resolved.&#x20;

3\. We fixed an issue with agents getting an error when logging into Commissions Online.

Previously, when an agent or user is invited more that once, they were getting an error when attempting to log in.&#x20;

Now, this issue has been resolved.&#x20;

4\. We fixed an issue with some users getting an error when syncing with QuickBooks®.

Previously, in some cases a user would get an access token error message when trying to sync with QuickBooks®.

Now, this issue has been resolved.
