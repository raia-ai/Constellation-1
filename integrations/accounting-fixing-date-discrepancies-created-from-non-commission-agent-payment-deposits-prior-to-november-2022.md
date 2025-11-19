---
title: Accounting - Fixing date discrepancies created from non-commission agent payment deposits (prior to November 2022)
---

# Accounting - Fixing date discrepancies created from non-commission agent payment deposits (prior to November 2022)

The purpose of this article is to provide the steps, that need to be taken, to correct differences in the date of a non-commission agent deposit, in the Bank module, and the agent payment record in the Agents module.

Prior to Constellation1 Accounting program build 2022.11.21, it was possible, in some instances to cause theses dates to be out of sync. This problem becomes apparent when reconciling your Agent Charge Aging (30, 60, 90, 120) report with either the Balance Sheet or Trial Balance reports. If the Agent Charge Aging (30, 60, 90, 120) report balance is not the same as the Agent Accounts Receivable GL balance, then this could be what is causing the discrepancy.

To fix the date discrepancy, follow the steps below:

*   Navigate to Bank > Processing > Non-commission Deposits
*   Highlight the relevant non-commission deposit
*   Click Edit
*   Change the date to any other date
*   Save
*   Edit
*   Change Date back to correct date
*   Save

The agent payment record in the Agents module will now match the date in the non-commission agent deposit.

Was this article helpful to you?

Was this article helpful to you?