---
title: Constellation1 Commissions December 2022 Release Notes v1.17
---

# Constellation1 Commissions December 2022 Release Notes v1.17

CONSTELLATION1 COMMISSIONS V 1.17 December 15, 2022

## Release Summary 

**New! Import Integration:** Added support to integrate with Constellation1 Transactions.   

**New! Reports Scheduler:** Added option to schedule and send reports automatically. 

**New! Notes:** Notes can now be added to transactions and agents. 

**Franchise Reports:** Added new franchise reports for Windermere and Berkshire Hathaway HomeServices (BHHS).

**Transaction Recalculation:** Added option to recalculate transactions when a commission plan is updated. 

**SkySlope Imports:** Improved warning messaging for SkySlope imports. 

**Bug Fixes**

## Release Details 

New! Integration with Constellation1 Transactions   
We’re pleased to announce our integration with Constellation1 Transactions, our transaction management solution.

Transactions created in Constellation1 Transactions can now be imported into Commissions Online in a similar way as SkySlope, Dotloop, or DocuSign transactions.

To configure your Constellation1 Transactions integration, contact your Commissions representative or email commissions@constellation1.com. 

New! Report Scheduler  
We’re also happy to introduce our new Report Scheduler, which allows users to automate report generation and distribution. 

A user can now schedule when a report should run and have it emailed automatically to whatever recipients they choose.  
Reports can run daily, weekly or monthly and are generated as a PDF or in XLSX format based on specific parameters such as the day of the week, month, and time.

The available reports are:  
•    Agent Incentive Level  
•    Agent Production Ranking  
•    Cash Flow Projection 

The reports generally use default filter settings, however the user can set advanced filters to refine the reports. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/12%20Dec%202022/2022-Dec-Commission-ReportsScheduler.png)

  
New! Notes  
We’ve added the ability for a user to add notes to transactions and agents.   
Notes are listed in the Transaction and Agent Details tabs. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/12%20Dec%202022/2022-Dec-Commission-Notes2.png)

  
To manually add a note, select Add Notes. Select a Reminder Date if needed, select the High Importance toggle if needed, enter your note text, then select Save. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/12%20Dec%202022/2022-Dec-Commission-Notes.png)  

New Franchise Reports    
We’ve added new franchise-level reports for our franchisees at Windermere and Berkshire Hathaway HomeServices (BHHS). The reports are available in the Reports section, under the Franchise Reporting tab.

Our Windermere franchisees can now access their own franchise reports in this tab, and we’ve added a Batch Transmission Report for our BHHS franchisees. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/12%20Dec%202022/2022-Dec-Commission-FranchiseReports.png)  

Transaction Recalculation  
When changing commission plans, the user will now be given the option to recalculate any affected transactions. 

When changing any of the following, the user will be alerted that the change will affect the current transaction:  
•    Commission basis  
•    Commission calculation type  
•    Ceiling amount on a tier  
•    An advanced option

The user will have the option to recalculate the commission(s) before saving or save the changes without recalculating the commission(s).

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/12%20Dec%202022/2022-Dec-Commission-Recalculate.jpg)

  
SkySlope Imports  
We’ve improved the warning messages when importing transactions from SkySlope. When a transaction is imported and the city name exceeds 30 characters, the user will receive a message letting them know the city name is too long and it should be shortened in SkySlope before importing trying to import it again.

  
Bug Fixes   
1\. Fixed an issue with the data migration tool not migrating the bonus override information correctly for non-agent contacts.   
Previously, when data was migrated from Back Office Commander to Commissions Online, the bonus override information was not accurately migrated for non-agent contacts  
Now, when migrating data for non-agent contacts, the data will be migrated accurately. 

2\. Fixed an issue with partial payments not syncing with their main transaction when the controlling side was changed.   
Previously, if a partial payment was associated with a transaction and the controlling side was changed, the partial payment would not sync with the transaction.   
Now, partial payments will sync automatically with their main transaction. 

3\. Fixed an issue with the Agent Check Stub Report not calculating the amount needed to reach the next commission tier.   
Previously, on the Agent Check Stub Report, the difference between the commission needed before this deal and the commission needed after this deal was not being accurately calculated.   
Now, the Agent Check Stub Report will accurately calculate the amount needed to reach the next tier BEFORE and AFTER the deal in question. 

4\. Fixed an issue with the Agent Check Stub Report not including shared and unshared income.  
Previously, shared and unshared income was not being included in the Check Stub Report.    
Now, shared and unshared income is being included on the Agent Check Stub Report. 

5\. Fixed an issue with the Agent Check Stub Report showing inaccurate outstanding accounts receivable balances.   
Previously, with some older transactions, the Agent Check Stub Report would show outstanding accounts receivable balances for the agent that had been previously paid.  
Now, the accounts receivable data will show the correct amounts on the Agent Check Stub Report.

6\. Fixed an issue with an incorrect referral amount displaying on a both sides transaction on the Transaction Commission Detail Report.   
Previously, when a referral was added on the buy side of a both sides transaction, the referral amount showed as being split between both sides.  
Now, when a referral is added on the buy side of a both sides transaction, the referral amount will show on the buy side and not as being split between both sides. 

7\. Fixed an issue with creating a commission plan and the Prorate Across Tiers setting not being saved.   
Previously, when a commission plan was created and Prorate Across Tiers was toggled on, the setting was not being saved .   
Now, when a commission plan is saved with the Prorate Across Tiers toggle on, the setting will be saved.