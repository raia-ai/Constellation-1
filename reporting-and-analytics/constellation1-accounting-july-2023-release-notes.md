---
title: "Constellation1 Accounting - July 2023 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/20896000"
tags: ["Reporting & Analytics"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Accounting - July 2023 Release Notes Production Release: July 2023  RELEASE SUMMARY   Bank – Non-Commission Deposits: Added hyperlink t"
long_description: "Constellation1 Accounting - July 2023 Release Notes Production Release: July 2023  RELEASE SUMMARY"
---

# Constellation1 Accounting - July 2023 Release Notes

Production Release: July 2023 

## RELEASE SUMMARY

  
**Bank – Non-Commission Deposits:** Added hyperlink to all deposits in the relevant batch. 

**Bank – All Checks Combined Check Register Report:** Added option to only show voided checks and omitted checks with a $0.00 (zero dollar) amount and a check number of 0.

**Cash Activity Report:** Added option to exclude entries with a $0.00 (zero dollar) amount.  

**Bank Reconciliation:** Added ability to select and clear multiple line items, added safeguard to the As Of date field to prevent reconciliation errors, and removed uncleared items when finalizing a reconciliation. 

**New! Accounts Payable:** Added option to upload QFX file.

**New! Accounts Payable:** Added a new dropdown to sort accounts payable by different primary/secondary combinations and updated column headers.

**Historical Payroll Records:** Updated deduction calculations and system will now save deductions with a zero or negative dollar amount. 

**Agents – All Charges Entered/Paid:** Agent Accounts Receivable option is now unchecked by default. 

**Agents – Processing Late Fees:** Made “Include Payments Through” field required. 

**Agents – Agent Credits/Payments Labels:** Updated AR Credit/Payments label and button location. 

**New! Sales Transaction:** Added Class as a filter option for transactions.  

**General Ledger:** Changed format of inactive GL codes on the GL Explorer. 

**New! General Ledger – Reports:** Added activity filter to “Balance Sheet – 12-month” report. 

**User Interface:** Various report updates. 

**Sales – Trust Transactions:** Removed Promissory Note and Redemption from the Type selections and the Trust Audit Report. 

**General Ledger – General Journal Entries:** Can now save with a $0.00 (zero dollar) amount.

**Bug Fixes** 

## RELEASE DETAILS 

Bank – Non-Commission Deposits  
We’ve improved the workflow for non-commission deposits to be more intuitive. We’ve removed the “Included in Batch” check box and replaced it with a clickable hyperlink that is labeled with the batch number. When clicked, it will open the Batch Deposits view and display all the deposits included in that batch. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Bank-BatchDeposit.png)  

Bank – All Checks Combined Check Register Report  
We’ve added an option to create a report that only shows voided checks. 

In the All Checks Combined Check Register tab, we’ve added a Voids Only check box. When selected, the report generated for the selected date range will only include voided checks (excluding voided trust checks). 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Bank-VoidsOnly.jpg)

We’ve also updated the report to omit checks with a check number of 0 (zero) and checks with a $0.00 (zero dollar) amount. 

Bank – Cash Activity Report  
We’ve updated the Cash Activity Report by adding an Include Zero Amounts check box to the report options. When unchecked, the report will exclude entries that have a $0.00 (zero dollar) amount. 

This check box is selected by default. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Bank-CashActivityZeroAmounts.png)

  
We’ve also improved the layout of many reports, including the Cash Activity Report. These improvements include:

*   Sorting the report sections in a more logical order
*   Sorting checks in numerical order
*   Showing the check # for commission and non-commission deposits
*   Eliminating extra white space

These improvements make the report more intuitive, easier to read, and easier to print. 

Bank – Bank Reconciliation   
**Added Multi-Select Option**  
We’ve added the option to select multiple line items for clearing on the Bank Reconciliation page. 

A user can now select a line item, scroll to the last item they would like to select, then press and hold the Shift key when clicking the last item to select all the items in between the first and last items. If the user then selects the Cleared check box for any one of the selected items, it will select the Cleared box for all the selected line items. 

Click [here](https://constellation1.na3.teamsupport.com/knowledgeBase/20795307) for more details regarding this functionality. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Bank-MultiSelectCleared.jpg)

**New “As Of” Date Field Verification**  
We’ve also updated the “as of” date field on the Bank Reconciliation page to prevent a user from entering a date that is earlier than the prior reconciliation date. If they do, the user will receive the following message: The new bank balance date cannot be earlier than any dates in the retrieved activity. 

This safeguard prevents the user from creating overlapping (and therefore incorrect) reconciliations.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Bank-AsOfDate.jpg)

**Removal of Uncleared Records**  
When finalizing a bank reconciliation, all remaining uncleared records will now be removed. Don’t be alarmed. All remaining uncleared records will be retrieved and displayed during the next reconciliation.   

   
Accounts Payable – Import Credit and Debit Card Transactions  
We’ve added a new Import Credit and Debit Card Transactions option to the Processing menu in the Accounts Payable module. This new option supports QFX files generated by Intuit’s suite of software products and most banks.

A user can download a QFX file from their Bank and then upload it to the Constellation1 Accounting system using this new option. Uploaded records will generate Unpaid or Manual bill records that will show on the Bills page. 

Click [here](https://constellation1.na3.teamsupport.com/knowledgeBase/20463509) for more details about this new feature. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-AP-UploadCCqfxFile.png)

  
 Accounts Payable –Bill Sorting  
We’ve added a new sort option to the Pay Bills page. This new dropdown allows the user to sort the vendor list by a primary and secondary sort option.

A user can select from the following primary/secondary sort option combinations:

*   Date to Pay then Vendor – Sort first by Date to Pay, then Vendor
*   Vendor then Date to Pay – Sort by Vendor, then Date to Pay
*   Vendor then Invoice – Sort by Vendor, then Invoice number

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-APDateToPay.jpg)

We’ve also updated the column headers on the Pay Bills Report to match the corresponding information that displays on the Bill page.   
**Column, Bill** has been changed to **Record #**, **Invoice** has been changed to **Invoice #**, and **Bill Amt** has been changed to **Amount**. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Sales-PayBills.jpg)

Historical Payroll Records   
We’ve updated how historical payroll records are calculated. Historical payroll can now calculate the deduction totals and net pay when there is a negative deduction. Historical payroll records with a $0.00 (zero dollar) amount or negative amount will show on the Payroll Journal Report.

Previously, when the gross pay was $0.00 or negative, it was excluded from the report. 

Agents – All Charges Entered/Paid Settings    
We’ve changed the default setting for Agent Accounts Receivable in the All Charges Entered/Paid tab.   
On the All Changes Entered/Paid tab, in the Agents module that shows on the GL Codes page, the Agent Accounts Receivable check box is now unchecked by default. We’ve added a tooltip with more details next to the check box. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Agents-GLCodes.jpg)

Agents – Processing Late Fees   
We’ve updated the Include Payments Through date field on the Process Late Fees tab to make this field required.   
Making this field required helps to prevent erroneous late fees from being charged to accounts that are current. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Agents-LateFee.jpg)

Agents – Agent Credits/Payments Label  
We’ve updated the AR Credits/Payments label in the Processing menu in the left navigation of the Agents module. We’ve changed the name from **AR Credits/Payments** to **Agent Credits/Payments**.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-AgentCreditPmt1.jpg)

  
We’ve also changed the button text on the Agent Credits/Payments page to **Apply Credit/Payment…** and moved it to the bottom left, next to Charges Paid. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-AgentCreditPmt2.jpg)

Sales – Added Class as Filter Option to Transactions   
We’ve added a new dropdown to the Sales Transaction page titled Class. The Class dropdown allows the user to select a Class to filter sales transactions. 

The selected Class shows in the transaction’s Commission tab. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-SalesTransClass.jpg)

General Ledger – GL Explorer Improvements

We’ve improved how inactive general ledger codes are displayed on the GL Explorer page in the Accounts between dropdown. 

We’ve moved the word “Inactive” for when a GL code has been set to inactive to the end of the code description. Previously, it was placed in front of the code number. This update keeps the GL codes in numerical order, allowing the user to easily search for and find inactive GL codes.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-GL-DeactivateAccount.jpg)

General Ledger – Balance Sheet – 12 Month Report   
We’ve added a new Only Include Accounts With Activity check box to the Balance Sheet – 12 Month Report. When selected, the report will only display accounts with activity in the past 12 months, including any accounts with a zero balance that have had activity during the reporting period.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-GL-12MoBalaceSheet.jpg)

  
   
User Interface Updates – Reports  
**Sales Rank Report**   
The Rank – Performance by Month Report now has an option to rank by sale price. This option has been added to the Rank By section in the General tab of the Rank – Performance By Month page. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-SalesRankSalesPrice.jpg)

We’ve also updated a column name in the report: we changed the **Associate Commission** column to **Agent Commission**.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Sales-RankBefore.jpg)  
_Before_  
 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Sales-RankAfter.jpg)  
_After_

We’ve also updated Sales Detail Report by moving some of the report criteria from the last page of the report to the header.   
For example, the date range, property type, and status now show in the header. Some report details will still show at the bottom of the report. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-ReportHeader.jpg)  
_Top of the Sales Detail Report_ 

**Accounts Payable – Aging Report**  
We’ve updated column names in the Accounts Payable, AP Aging report.   
We’ve changed **Date Accrued** to **Invoice Date** and **Date to Pay** to **Due Date**. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-APAging.jpg)

Sales Trust Transactions  
We’ve removed Promissory Note and Redemption from the Type dropdown. Now, the only available types are Check and Deposit. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-PromisaryNote.png)

_Before_

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-PromisaryNoteAfter.png)  
_After_

We’ve also removed these labels from the Trust Audit Report. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Sales-TrustType.png)

General Ledger – Journal Entries    
We’ve updated the Recurring Journal Entry Templates to save totals when the amount field is $0.00 (zero dollars).   
Previously, the Save button was disabled when the total was $0.00.

Bug Fixes

1\. We fixed an issue with certain trust records not showing on the Cash Activity Report.  

Previously, in the Sales module, when the Group By module was selected, the trust records that didn’t include the buyer or seller would not show on the report. 

Now, trust records that don’t include the buyer or seller will show on the Cash Activity Report. 

2\. We fixed an issue with importing agents who represent both sides of a transaction from SkySlope. 

Previously, when an internal agent who represented both sides of a transaction was imported, the Buying Count and Selling Count would remain at 0. External agents imports would also fail. 

Now, when an internal agent is imported, the Buying Count and Selling Count will import as 1, and external agents will import to the Entities tab with sides set to Both. 

3\. We fixed a sorting issue in the Bank Reconciliation when selecting a range of checks to mark as Cleared on the Bank Reconciliation page. 

Previously, on the Bank Reconciliation page, when a user selected the options for Cleared By Date, Mark Cleared By #, and Remove Cleared Mark, the sort order of the checks would change.

Now, the current sort order will remain unchanged when Mark Cleared By Date, Mark Cleared By #, or Remove Cleared Mark is used. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2023/07%20July/2023-Accounting-Bank-ClearCheck.jpg)

4\. We fixed an issue with reports failing to export.

Previously, when a report was exported and set to overwrite an existing report, the export would fail. 

Now, this issue has been corrected. When overwriting an existing report with a newly exported report, the new report will export and overwrite the existing one as expected.