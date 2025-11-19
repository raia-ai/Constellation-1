# Constellation1 Accounting - April 2024 Release Notes

Production Release: April 22, 2024&#x20;

## Release Summary

**Agent Commission Statement:** Added Previous Payment/Credit and Balances to statement. \
**Bank Reconciliation:** Updated notes field to wrap longer notes. \
**Incentive Level Report:** Add Gross Commission to report. \
**Bug Fixes**

## Release Details

Agent Commission Statement\
We’ve added two new columns to the Agent Commission Statement. The new columns, labeled “Previous Payment/Credit” and “Balance,” have been added to the “Charges Paid By This Check” section, making it easy for agents to clearly see if previous payments and credits have been applied to charges paid from the current payment.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/04%20April/2024-Accounting-2118.png)

&#x20;The "Agent Commission Statement" is not to be confused with the “Commission Statement”.

Bank Reconciliation Notes\
We’ve updated the Bank Reconciliation "Notes" section, to wrap lengthy text to the next line preventing it from being cut off. \
Text will wrap to three lines. If it exceeds that, a vertical scroll bar will be added to the "Notes" box.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/04%20April/2024-Accounting-BankNotes.jpg)

Incentive Level Report\
We’ve added a Gross Commission column to the Incentive Level report that shows each agent’s gross commission for the reported period.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/04%20April/2024-Accounting-2161-GrossComm.png)

Bug Fixes

1\. We fixed an issue with voiding commission checks that have a negative Agent Charge Payments/Chargebacks (ACHG) post-split balance not being credited to the agent.&#x20;

Previously, when a commission check with a negative ACHG balance is voided, the agent was not being credited.&#x20;

Now, when a commission check that has a negative ACHG post-split is voided, or when a transaction with one or more commissions with a negative ACHG post-split is voided, an accounts receivable credit will be created. This credit will be applied to the agent charge that was generated when the original commission was closed.

2\. We fixed an issue with the PostZero setting not working as expected.&#x20;

Previously, when PostZero was enabled, any transactions with a $0.00 (zero-dollar) amount were not being posted to the general ledger.&#x20;

Now, this problem has been resolved so that zero-dollar transactions post properly to the general ledger when PostZero is enabled.

3\. We fixed an issue with check stubs showing the full amount as paid when making a partial payment on a vendor’s bill.&#x20;

Previously, when making a partial payment to a vendor, the check stub showed the full amount of the bill as paid and not the partial payment amount.

Now, the check stub will show the amount paid on the check. The amount of the check has also been moved to the left, so it doesn’t align with the "Amount" column, to clearly distinguish the total check amount from the summed amounts in the column.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/04%20April/2024-Accounting-Check%20Total.png)

4\. We fixed an issue with multiple credits being created when voiding a sale with Third-party referrals.&#x20;

Previously, when voiding a sale with multiple agents and a third-party referral, multiple AP credits were being created.&#x20;

Now, when a sale with multiple agents and a third-party referral is voided only one AP credit will be created.&#x20;

5\. We fixed an issue with the vendor account number not being printed on checks.&#x20;

Previously, when the “Print Acct# on Checks” was selected, the account number was not being printed on the checks.&#x20;

Now, when “Print Acct# on Checks” is selected, the account number will be printed on the check.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/04%20April/2024-Accounting-VendorAccountNumber.jpg)

6\. We fixed an issue with recalculating the Agent $ / Office $ split when Third-party Pass-through money is added or removed from a transaction.&#x20;

Previously, when changes were made to Third-party Pass-through money, the commission would be recalculated.&#x20;

Now, commission will not be recalculated for Third-party Pass-through money under the following conditions:&#x20;

* If the Third-party line is Pass-through money and changes are made to the Third-party amount either directly with a dollar value or indirectly with percentage change.
* If a Third-party pass-through line is deleted or added.&#x20;

The agent commission will still be recalculated as expected for non-pass-through, third-party lines when the agent commission is greater than 0%.
