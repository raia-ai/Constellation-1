---
title: "Constellation1 Accounting - September 2022 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/17952892"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Accounting - September 2022 Release Notes Release Build: 2022.07.27 Sales Pending Sales:  When the value of any of the following fields"
long_description: "Constellation1 Accounting - September 2022 Release Notes Release Build: 2022.07.27 Sales Pending Sales:  When the value of any of the following fields on the Details tab of a sale transaction are changed, Third-Party lines and the agent's Gross Commission are recalculated  Sale Price Gross Revenue Comm %  When the value of any of the following fields on the Third-Party tab of a sale transaction are changed, the Amount of the third-party record and the agent's Gross Commission are recalculated  %"
---

# Constellation1 Accounting - September 2022 Release Notes

**Release Build: 2022.07.27**

**Sales**

*   Pending Sales:
    *   When the value of any of the following fields on the **Details** tab of a sale transaction are changed, **Third-Party** lines and the agent's **Gross Commission** are recalculated
        *   **Sale Price**
        *   **Gross Revenue**
        *   **Comm %** 
    *   When the value of any of the following fields on the **Third-Party** tab of a sale transaction are changed, the **Amount** of the third-party record and the agent's **Gross Commission** are recalculated
        *   **% of**
        *   **Percent**
        *   **Less Adjustment**
        *   **Amount**
*   Commission tab of Sale Transactions:
    *   **Second Payee** field has been removed from the **Agent Payment Details**
    *   Negative pre-split and post-split amounts can now be entered in commissions, even if the agent is currently over the $ Ceiling or Count Ceiling for the deduction 
*   Commission Calculations:
    *   Commission can now be calculated based on the **Closed** date in sales
    *   **Incentive Level** now determined by the **Basis Date** selected in the **Commission Plans** setup
    *   If system setting **COMMPLANALL** is enabled, commissions paid under all plans are considered, however, the date field to qualify by, is determined by **Commission Plan** selected in agent's commission record on sale transaction
        *   This new functionality should only be used if all of the agent's commission plans use the same **Basis Date**
        *   The values in the agent's **Earnings Summaries** on the **Commission** tab, in the agent's profile record, are determined by the **Basis Date** selected in the agent's default **Commission Plan**.  If the agent has no default **Commission Plan** selected, the **Date Paid** referenced in **Agent Payment Details** section of the **Commission** tab in **Sale Transactions** is used
            *   Note:  The agent's 1099 value, is always based on the **Date Paid**, not the **Closed** date of a sales transaction 
            *   Note: Changing the **Basis Date** in **Commission Plans** setup will not automatically recalculate **Pending** sales, **Re-Calc** **Projected Agent/Office Splits** can be used to do that
*   Agent's Commission Statement:
    *   The full property address, **Address1, Address2, City, State & Zip** code, now prints on the agent's commission statement, for both the default and legacy versions of the agent's commission statement
        *   The address prints on a single line
        *   For longer addresses, text is truncated and will not wrap
    *   When commission statements are e-mailed, the property address is now included on the subject line of the e-mail
    *   On the **Legacy** version of the agent's commission statement, the agent's name and address has been added to the upper-left-hand side of the report heading 
*   Voiding Commission Payments: 
    *   When a commission payment, in a posted sale is voided, the negating sale and the original sale are no longer marked as voided
    *   In a posted sale, with two or more commission payments, each commission payment can be voided at different times  
    *   Voiding an agent check, in a posted sale, will result in the creation of a negating sale record  
        *   If more than one agent check is voided in a posted sale, each void will create a new negating sale record  
            *   The second voided check record will have **V2** listed after the original transaction number 
*   **Agents Moving up Incentive Levels** report is displayed when an agent is paid for multiple commissions, in the same check run, where one of the commissions alone is not enough to move to the next incentive level, but all commission combined is enough to move to a higher incentive level
*   The **Check#** column in **Transaction Summary** report now wraps to allow display of any number of digits
*   MLS/TMS Integration: 
    *   When uploading agent charge payments to **Agent Portal**, only agent payments, that have not been previously uploaded, will be submitted
    *   When **Refresh Transaction List** is selected, all transactions on the **Transaction List** tab are selected by default  

**Trust**

*   Bank reconciliation **Description** field changed to show **Trust record #** followed by **Payee** referenced in trust records

*   Changes show in **selection grid**, **Bank Reconciliation Worksheet** report, and **Bank Reconciliation History** report
*   Change is not retroactive

*   Activity already retrieved into bank reconciliation, with old format, can be removed from bank reconciliation and re-retrieved to display new format

*   Closing **Issue Trust Checks** tab, before selecting additional trust checks for printing, no longer required  

*   When **Finish Processing** button is selected, buttons are now disabled, and selection of new unpaid payments are immediately available for selection 

*   When retrieving trust deposits from sale transactions, if trust record has been previously linked to the sale transaction, then the trust pop-up will have the pertinent trust record selected and displayed
*   Issue Trust Checks:

*   Added **Address** column to the selection grid  
*   If related sale transaction has been selected from the trust record, property address from related transaction is displayed
*   Address is taken from the linked sale transaction's **Address1 & City** field, and will print in the **Memo** line on trust checks, when system setting **TRMEMOSRC** is set to **ADDRESS**

*   When no related sale **Transaction Number** set in the trust record, **Address** in header of trust record will print on **Memo** line of trust check

*   Trust Transactions:

*   When sale is selected from trust transaction, **Office**, **Seller**, and **Buyer** fields now auto-fill from sale transaction
*   **Buyer** and **Seller** will auto-fill from the sale, only if they are entered on the **Entities** tab of the sale
*   Unpaid check lines, determined by no value in **Date Paid** field, no longer appear on **Trust Audit** report
*   Added **Check Address2** field, to trust check details

*   **Check** **Address2**, will print on trust check

*   When system setting **TRMEMOSRC** is set to **COMMENT**, value entered in **Comment** field of trust check line prints on **Memo** line of trust check
*   Error will no longer appear upon **Save** in instances where trust lines for deposits and/or checks are entered and then deleted within the same **Edit** period 

**Agents**

*   Agent Credit Card Processing:

*   Removed the word **Select** before checkboxes in header row of selection grid
*   Added wait cursor, when header checkbox is checked in **Agents** selection grid

*   Commission Plans Setup:

*   **Basis Date** dropdown added

*   Choices are **CL: Close Date** and **PD: Date Paid**

*   Existing commission plans will be set to **PD: Date Paid** at time of upgrade

*   When new **Pre-Split Deductions** are added to agent's profile record, fields **Anniv Reset?**, **$ Ceiling**, and **Count Ceiling** now default to values set in **Pre-Split Deductions** setup records

*   When new **Post-Split Deductions** are added to an agent's profile record, fields **Anniv Reset?**, **$ Ceiling**, and **Count Ceiling** now default to values set in **Post-Split Deductions** setup records
*   Reports:
    *   Agent Sales Ranking report:  Added **Offer Date**, **Projected to Close Date**, **Failed Date**, and **Entered Date** to **Date Filter Option**
    *   Filter by **[Payee Type](https://constellation1.na3.teamsupport.com/knowledgeBase/16890300 "Accounting - Agent Income Ledger Report - Payee Type Options Filter")** added to the **Agent Income Ledger** report
    *   **Agent Income Ledger** report now has option to filter by **Commission Plans**

**Accounts Payable**

*   Purchases Journal:  Unapplied payments and unapplied credits are now listed

**Bank**

*   The **Save** button is now enabled for **Non-Commission Deposits**, entered for agent payments, when the agent has a zero and/or credit balance; eliminating the need to click on the **Create Payment** button. 
*   Bank reconciliation **Description** field changed to show **Trust record #** followed by **Payee** referenced in trust records
    *   Changes show in the **selection grid**, **Bank Reconciliation Worksheet** report, and **Bank Reconciliation History** report
    *   Change is not retroactive
        *   Activity already retrieved into bank reconciliation, with old format, can be removed from bank reconciliation and re-retrieved to display new format

**General Ledger**

*   New system setting [**GLSORTNAME**](https://constellation1.na3.teamsupport.com/knowledgeBase/17138084 "Accounting - System Setting GLSORTNAME")

  **Payroll**

*   **Pay Period** date range added to employee pay stubs

*   **Pay Period** date range is listed above the **Earnings** summaries  

*   Issue Payroll Payments:  Selection grid column heading **Pay Period** has been changed to **Period End**
*   Generate Payroll:

*   **Pay Frequency** dropdown now only lists frequencies that have been selected in profiles of active employees
*   Added **Period Beginning** and **Period Ending** date fields
*   Removed **Period End** label and replaced with **Period Ending** label

*   Employee Address Report:  Removed **Pager** column label and replaced with **Fax** column label 
*   Payroll Records:

*   Added **Period Beginning** field above **Period Ending** field
*   When adding payroll records manually, when **Employee** is selected from dropdown, and **Period Ending** is entered, the **Period Beginning** date will autofill based on the **Pay Frequency** entered in employee's profile record, if the **Period Beginning** date has not already been entered
*   **Edit** button has been enabled in **Paid** view of payroll records

*   Only **Period Beginning**, **Period Ending**, **Date Paid** and **Paycheck Comment** fields can be edited

*   **Date Paid** field can only be edited if payroll record has not been posted or reconciled and is not included in a NACHA batch  

**System**

*   System Setting **TRMEMOSRC**: 

*   Changed description to **Source for memo text on Trust checks**
*   Changed **Text Value** selection to a dropdown
*   Added **COMMENT** selection list 

*   Enter key now behaves like Tab key with [some exceptions](https://constellation1.na3.teamsupport.com/knowledgeBase/16561769 "Accounting - Enter Key Functionality")
*   New system setting [**COMMPLANEDIT**](https://constellation1.na3.teamsupport.com/knowledgeBase/16891581 "Accounting - System Setting COMMPLANEDIT")
*   New system setting **[SHOW100PCTDATE](https://constellation1.na3.teamsupport.com/knowledgeBase/16891899 "Accounting - System Setting SHOW100PCTDATE")**
*   When emailing agent statements, if timeout error is encountered, attempt will be made to send next email.  If two consecutive timeout errors are encountered, the email process will halt. 

Was this article helpful to you?

Was this article helpful to you?