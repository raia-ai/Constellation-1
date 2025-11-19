# Constellation1 Commissions June 2024 Release Notes v3.3

Production Release: June 24, 2024, v3.3

## Release Summary

**Upcoming Closings:** Send email notification for upcoming closings. \
**User Permissions:** Companies now have more options to customize user account permissions.   \
**Transactions:** Added option to disable auto-populating Disbursed By and Disbursed Form when creating new transactions. \
**Seller Landlord Master Template:** Updated the master template. \
**Deposit Receipt Master Template:** Now shows deposit date and receipt date. \
**Billing Report:** Added eSign sessions to billing report.\
**Report Scheduler:** Added next run and previous run dates. \
**Agent Production Detail Report:** Added option to include inactive agents on report. \
**Custom Branding Favicon:** Updated the label shown on the browser tab.\
**Bug Fixes**

## Release Details

My Workspace – Email Notification for Upcoming Closing\
We’ve added the ability to send email notification for upcoming closings to staff members. \
In My Workspace, in the Upcoming Closings section, we’ve added a gear icon to enable and configure the option to send email notifications.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-EmailClosingsSetting.jpg)

Configuration options allow the user to set the number of days before a closing is scheduled, and who should receive email notification. Staff who are included in the list will automatically receive email notification.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-EmailClosings.jpg)

Email notifications will include all upcoming transactions for the defined number of days before closing.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-UpcomeingNotification.jpg)

_Example email notification._

Updated User Permissions&#x20;

We have enhanced the permission settings and improved the hierarchy to provide companies with greater flexibility over management users and office administrators and their respective view and access privileges.

Some improvements include,&#x20;

* Office administrators can now be associated with multiple offices.
* Office administrators can view transactions associated with their office(s) they are associated with.
* Limiting access to transaction data on the dashboard and in the transaction module.
* Improved control over office administrators' user management and editing privileges.
* Removed agent team permissions.&#x20;

Transactions – Remember Disbursed By information

We’ve added a new option to "Remember last used Disbursed By and Disbursement Form” to the Advanced Settings.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-AdSet-DisbusedBy.jpg)

When enabled, the system will automatically populate the Disbursed By field and Disbursement Form based on the previous transaction, streamlining the workflow when creating a new transaction.&#x20;

For existing customers, this feature will remain enabled by default, but can be disabled at any time.

Seller Landlord Letter Master Templates&#x20;

We have enhanced the Seller Landlord Letter to include the commission and HST, while also reorganizing the fields in a more intuitive order.

Changes include,&#x20;

* The Label for “Total Payable” has been changed to “Total Commission Less Deposit”.&#x20;
  * The calculation for \[Balance of Commission] is unchanged.

New labels and bookmarks,

* Total Commission Paid
  * \[Gross Commission] is the sum of gross commission and tax but does not subtract the deposit.
    * (total commission + hst = total commission paid) - deposit = total commission less deposit.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-MaterTempHST.jpg)

_Excerpt from Seller Landlord Letter._

Deposit Receipt Master Template&#x20;

We’ve updated the Deposit Receipt master template to include both the deposit date and the receipt date. \
The Deposit Date is the date funds were received. \
The Receipt Date is the date the receipt was generated.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-DepositDates.jpg)

_Excerpt from Deposit Receipt master template._

Reports&#x20;

**Billing Report**\
We’ve added a column to the billing report landing page, showing the number of eSign sessions sent for the billing cycle.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-ReportsBillingEsign.jpg)

The eSign sessions are also included in the report.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-eSignReport.png)

**Report Scheduler**

We’ve added the date and time of the Next Scheduled Run to scheduled reports.&#x20;

In the Edit Report Schedule, a line has been added displaying the date and time of the next scheduled run of the report, and we’ve also added the date and time when the report was previously run.&#x20;

We've also implemented validation to ensure all mandatory fields are completed and will notify the user of any missing required information.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-ReportsScheduler.jpg)

**Agent Production Detail Report**\
A new feature has been added to the production detail report that allows the user to Include or Exclude inactive agents in the report. \
This means users no longer have to activate agent accounts to ensure that their recent production is incorporated in the report.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-ReportsProductionDetail.jpg)

Custom Branding&#x20;

We have improved the information displayed on web browsers when a custom favicon is uploaded.&#x20;

When a custom favicon is uploaded in the White Labeling section, the name displayed on the browser tab will now only show "Commissions," without the mention of "Constellation1."

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/06%20June/2024-Commissions-June-FaviconTab.jpg)

Bug Fixes

1\. We fixed an issue with overriding a deduction causing another deduction to be removed.&#x20;

Previously, when a transaction deduction was overwritten, other deductions in the transaction were being removed.

Now, this issue has been resolved. Overriding a deduction will not remove other deductions within the transaction.&#x20;

2\. We fixed an issue with the system allowing a user to set an agent to inactive or terminated while associated with a pending transaction.

Previously, if an agent was associated with a pending transaction an administrator was able to set the agent account to Inactive or Terminated.&#x20;

Now, if an agent is associated with a pending transaction, they cannot be set to Inactive or terminated.
