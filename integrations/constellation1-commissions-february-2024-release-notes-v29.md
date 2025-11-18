---
title: "Constellation1 Commissions February 2024 Release Notes v2.9"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/23025242"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Commissions February 2024 Release Notes v2.9 Production Release: February 26, 2024, v2.9  RELEASE SUMMARY Enterprise Insights: Added ne"
long_description: "Constellation1 Commissions February 2024 Release Notes v2.9 Production Release: February 26, 2024, v2.9  RELEASE SUMMARY Enterprise Insights: Added new Limited Access user permission. Single Sign On Account Creation: Create user accounts from third party applications. Exclude Capped Deductions: Updated the label in the settings. Transaction Number Auto Generation: Added option to include a custom prefix to transaction numbers.  Transactions Sort Order: Changed default sort order of transaction."
---

# Constellation1 Commissions February 2024 Release Notes v2.9

Production Release: February 26, 2024, v2.9 

## RELEASE SUMMARY

**Enterprise Insights:** Added new Limited Access user permission.  
**Single Sign On Account Creation:** Create user accounts from third party applications.  
**Exclude Capped Deductions:** Updated the label in the settings.  
**Transaction Number Auto Generation:** Added option to include a custom prefix to transaction numbers.   
**Transactions Sort Order:** Changed default sort order of transaction.  
**Closing Transactions:** Added Close Date to closing wizard.   
**Transaction Contact Search:** Search for contacts associated with a transaction.  
**Master Templates:** Added new letters for Sellers and Buyers.   
**Disbursement Authorization Master Template:** Added new bookmarks to the master template.   
**Reports:** Updated Date Time Stamp on pre-built and custom reports.   
**Trust Reports:** Compliance has been added as a report option.   
**Bug Fixes**

## RELEASE DETAILS

Enterprise Insights   
A new Limited Access user permission has been added for Master Users to restrict access for certain enterprise Insights users. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-EntInt-LimitedAccess2.jpg)

This permission limits user accounts to accessing only the brokerages associated with their account.   
It also restricts access to Users, Administration in the left navigation, and on the dashboard, the Group filter will not be available.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-EntInt-LimitedAccess5.jpg)

Single Sign On Account Creation    
In January, we added Single Sign-On (SSO) integration, allowing companies to connect Commissions Online with third-party applications.   
Now, we have added the ability for Commissions Online to automatically create temporary accounts for users coming from those integrated third-party applications. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-SSO-TempUsers.jpg)

  
When a new third-party user accesses Commissions Online, the administrator will receive an email notification alerting them of the new account. In the Users module, the administrator can then upgrade the temporary account to a full Agent or Administrator account or delete it.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-SSO-Upgrade.png)

  
Exclude Capped Deductions  
Recently we added the option "Exclude Capped Deductions" to the Advanced Settings to determine how deductions are applied in a transaction. Now, we have updated the label for this setting.  
In the Transaction Setting of the Advanced Settings the toggle has been updated to “Exclude Deductions from Capped Amount Calculation”   
The functionality remains the same, when "Exclude Deductions from Capped Amount Calculation" is enabled, deductions will be applied to the capped deduction amount regardless of the "Exclude from Commission Tier" setting. The "Exclude Deductions from Capped Amount Calculation" will override the “Exclude from Commission Tier” setting in a transaction. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-ExcludeCapped.jpg)

Added Prefix Option to Transaction Numbering  
When the automatic generation of transaction numbers is enabled, there's now an option to add a Transaction Number Prefix.   
The prefix is a static number that can include numbers, letters, and special characters (123ABC-), but it does not increment - only the transaction number will increase with each new transaction.

The Prefix and Transaction number fields are limited to eight characters.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-TransNumber.jpg)

Transactions Sort Order  
The Transactions landing page now sorts transactions in ascending order by Transaction Number.   
The most recent transactions will appear at the top of the list. Users can change the sort order, which will be remembered when returning to the transactions page.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-TransactionSort.jpg)

Transaction Close Date  
We’ve added the Close Date to the Close Transaction wizard. On the Payment Information page, the user will be able to view the close date of the transaction. Additionally, warning messages have been added to alert the user about any mismatch between the Close Date, the Process Date and the Offer Acceptance Date.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-CloseDate.jpg)

  
If the Close Date occurs before the Process Date, the system will display a warning message to the user.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-CloseDateWarning.jpg)

If the Close Date occurs before the Offer Acceptance Date, the system will display a warning message to the user.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-CloseDateWarning2.jpg)

In both cases, the user can proceed with closing the transaction without changing the dates or navigate to the Details tab of the transaction and update the dates before closing the transaction. 

Transaction Contact Search  
Users can now search for transactions by contact name.   
In the Advanced Filters under Transactions, we’ve added a new filed titled Transaction Contacts, this new search option allows users to find all transactions associated with a specific contact.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-TransactionContacts.jpg)

Master Templates   
We’ve added two new letters to the master templates, Buyers Letter and Sellers Letter.  
Buyers Letter and Sellers Letter is addressed to the respective buyer or seller and includes details related to their transaction.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-BuyerSeller-Template.jpg)

Disbursement Authorization Master Template  
The Disbursement Authorization master template has been updated to include more information about the parties involved with a transaction. 

In the “Title/3rd Party Company” section, we added the contact person from the third-party company.  
•    \[Third Party Company Contact\]   
The third-party company contact, is the named person with the Title Company that is associated with a transaction.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-Template-3rdParty.jpg)

The following have been added to the master template:  
•    Side: \[Transaction Side\]   
•    Transaction Number: \[Transaction Number\] 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-Template-Sides.jpg)

And 

In the Broker 3rd Party Point of Contact section, we’ve added:  
•    \[Miscellaneous Contact\]   
The Miscellaneous Contact is listed as the “Transaction Coordinator”.    
“Transaction Coordinator” has also been added as a contact type.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-Template-ThrdParyContact.jpg)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-Template-MiscContact-TC.jpg)

These updates have been made to the master template and do not affect any customized templates.  

  
Updated Report Date Time Stamp  
We’ve updated pre-built and custom reports to show a consistent date and time format using the user's local time zone. The updated time stamp shows on the report preview and on reports exported to PDF. The format is: Year-Month-Day Time.   
For example, 2024-02-14 02:25:40 PM

Previously, reports inconsistently displayed UTC time, which was confusing for users unsure of when the report was generated.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-ReportDateTimeStamp.jpg)

This update does not apply to Franchise reports. 

Canadian Compliance Trust Reports   
Canadian customers can now access a new Compliance report.   
In the Trust Report filters, Compliance has been added to the Report Type filters. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-TrustReport.jpg)

  
The Compliance report includes several key features:  
•    Transaction status in the Status column.  
•    Each summarizes Deposits/Trusts for each transaction.  
•    Bank is a sum of deposits less terms and disbursements.   
•    Term shows the sum of deposits in a term.   
•    Total is a sum of deposits and term deposits less issued disbursements.   
 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/02%20February/2024-Commissions-Feb-Report-CanadianTrust.jpg)

_Example of Trust Compliance Report_

Bug Fixes

1\. We fixed an issue with the Trust report excluding some transactions when Zero Amounts is set to Exclude.

Previously, when Zero Amounts was set to Exclude the report would exclude some transactions that didn’t have zero amounts. 

Now, when running a Trust report and setting Zero Amounts to Exclude, transactions with non-zero amounts will show on the report.   

2\. We fixed an issue with agent information being removed when saving an agent user account.

Previously, when an agent user account was edited, some information was being deleted from the agent record when viewing it in Users module.

Now, when editing an agent account, all information associated with the account will be retained. 

3\. We fixed an issue with the Review Closing Report showing the Seller in the Commissions Receivable From field.

Previously, the Review Closing Report incorrectly displayed the seller's name in the Commissions Receivable From field instead of showing the selling attorney's name as it should.

Now, the Review Closing Report will show the correct contact person in the Commissions Receivable From field.