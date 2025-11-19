# Constellation1 Accounting - March 2023 Release Notes

Production Release: March 8, 2023&#x20;

## RELEASE SUMMARY

**System Settings:** Added option to pay commissions with single or multiple checks. \
**Check Expense:** Added line numbers to Check Expense Entries. \
**Agent Filters:** Added Office filter to Agents > Setup to filter and sort agents by office.  \
**Bank Reconciliation:** Improved workflow when checks are voided and reissued. \
**Bank Reports:** Increased the width of the Check# column on the Cash Activity report. \
**Sales Transactions:** Added numbers to indicate how many agents are associated with a transaction.\
**Agent Reports:** Added Grand Total line to the Open Items Charge Statement report. \
**Bug Fixes**

## RELEASE DETAILS

System Settings \
We’ve added the option to set the system to pay agents with single or multiple checks for their transactions. \
In System Settings, under the COMMPYMTGROUP setting code, we've added the option to pay each commission with a separate payment.&#x20;

The dropdown now includes the following options:

* Pay all commissions with a single payment.
  * An agent with one or more commission records, in one or more transactions, will be paid with a single ACH payment or check.&#x20;
* Pay all commissions in same transaction with a single payment.
  * An agent with one or more commission records, in the same transaction, will be paid with a single ACH payment or check.
* Pay each commission with a separate payment.
  * An agent with one or more commission records, in one or more transactions, will be paid with a separate ACH payment or check, one for each commission record.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Agents-SysSettings.jpg)

Accounts Payable – Bills – Check Expense  \
We’ve improved the display of Check Expense Entries under Bills. \
We’ve added a Line Number column to the Check Expense Entries section of Bills and Recurring Bills to ensure the sort order does not change from when the bill was first entered. A user can now organize and sort Check Expense Entries by line number.\
&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Accounting-BillsLine.jpg)

Sort Agents by Office\
We’ve added an Office filter in the Agents section under Setup, allowing the user to filter the list of agents by office, then sort each column in ascending or descending order.   \
When sorting by the Agent column, the agent name shown is based on the Name on Report field.&#x20;

&#x20;![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Agents-SortAgents1.png)\
&#xNAN;_&#x4F;ffice Filter_

&#x20;![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Agents-SortAgents.jpg)\
&#xNAN;_&#x41;gent list_

Bank Reconciliation \
We’ve improved the workflow for Bank Reconciliations when a check is voided and reissued. \
When a check was issued, voided, and then re- issued as a new check with the same number, the system would record the two credits as one line item and the debit as a separate line item. This caused confusion and made it difficult to find the correct check amount. Now, the system will record the three payment records as one line item and not three.

Bank Reports\
We’ve widened the Check# column on the Cash Activity report. \
Previously, if there was a long check number, the number would wrap to the next line, making the report difficult to read. \
To improve readability, the Check# column has been widened to accommodate check numbers up to 12 digits long. \
&#xNAN;_**Note:** A 13th digit would wrap to the next line._&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Agents-AgentReportGrandTotal.png)

Sales Transactions \
We’ve added text to indicate how many agents are associated with a transaction. \
In the Sales module, on the Sales Transactions > Commission tab, the user will now see “(1 of #)”  next to the Agents field where # is the total number of agents associated with the transaction.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Agents-NumberOfAgents.jpg)

Agent Reports\
We’ve updated the Open Items Charge Statements report to now include a Grand Totals line at the bottom of the report.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Agents-AgentReportGrandTotal.jpg)

Bug Fixes

1\. We fixed an issue with the Credit Card Payment check box not being active for Batch Deposits and Non-Commission Deposits in the Bank module.\
Previously, the Credit Card Payment check box was disabled, and the user couldn’t select this option when creating a credit card batch deposit. \
Now, the box is active and can be selected where appropriate to create a credit card batch deposit.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/03%20March/2023-Feb-Accounting-Bug-CCPayment.jpg)

2\. We fixed an issue with adding pending sales for companies with only one office to the Sales section.  \
Previously, in some instances, when adding a pending sale, when user clicked Add, they would be presented with an erroneous message asking if they would like to adjust the deposit to zero dollars.  \
Now, when adding a pending transaction, the user can immediately enter the sales details without receiving the erroneous message.

3\. We fixed an issue with FICA and FMED calculations for the first pay period of a new calendar year. This only affected calculations for employees who had met the FICA and FMED threshold in the previous calendar year.    \
Previously, when a check was issued, the system would calculate the tax based on the Period Ending date.\
Now, the taxes are calculated based on the Date Paid.
