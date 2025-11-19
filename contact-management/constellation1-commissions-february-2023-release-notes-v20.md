---
title: Constellation1 Commissions February 2023 Release Notes v2.0
---

# Constellation1 Commissions February 2023 Release Notes v2.0

Production Release: February 8 2023 v2.0

## Release Summary

**Agent View:** More transaction details and reports are now available to agents.    
**Pending Transactions:** Pending transactions can now be included in commission calculations.   
**Administration Permissions:** Added a validation step to prevent users from being able to grant permissions higher than their own permission level.   
**Deductions:** Withholding settings are no longer editable when a plan is associated with a transaction.   
**Commission Calculations:** Added a warning message when a change may affect commission calculations.   
**SkySlope Imports:** Cooperating Broker can now be included when importing transactions.   
**Commissions Online URL:** Added a new URL for accessing Commissions Online.    
**Agent Commission Statement:** Updated master template to include more transaction details.   
**General Ledger:** Added agent check stub information when payment is set to Bill.  
**Reports:** Updated various report filters and options.  
**Bug Fixes**

## Release Details

  
Agent View  
We’ve enhanced agent access to transaction details and reports.   
In the Agent view of a transaction, we’ve added three sections to the Details page:  
•    Deposits (read only)  
•    Franchise Details (Franchise customers only)  
•    Notes

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-AgentView.jpg)

These new sections put important transaction information at agents' fingertips.

Additionally, certain transaction reports have been made available to agents. A company administrator can disable the reports to remove them from the agents' view.   
To disable these reports, the administrator will need to navigate to System Settings > Permissions, then to the Agent View tab. The administrator can toggle off any of the available reports listed under Report Access. 

  
  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-AgentViewAdmin.jpg)

Reports that can be enabled include:  
•    Agent Incentive Level  
•    Transaction Commission Detail  
•    Pending Transactions  
When a report is toggled on, it will be available to agents in the Reports section in the left navigation. Agents will then be able to run, view, and download the reports. 

Commission Plans – Include Pending Transactions 

We’ve added the ability to include pending transactions in commission calculations. To do this, go to Commission Plan > Edit Plan > Commission Plan Details and turn the Include Pending Transactions? toggle on.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-IncludePending.png)

Updated Permissions Settings 

We’ve updated user permissions by adding a validation to check the permission level of the user making the change to prevent them from granting permissions with higher authority than their account.   
For example, now an office administrator will no longer be able to grant Master User permissions to themselves or to other accounts (only a Master User can grant Master User permissions). 

Deductions – Withholdings Changes Restricted

We’ve updated our system to prevent users from changing the withholding settings for a deduction when a commission plan is associated with a transaction.   
Users can toggle Withholding for a particular deduction on and off in the Edit Deduction section of the Deductions tab for the plan. Once the commission plan is associated with a transaction, the user will no longer be able to change the Withholding setting.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-Withholding.jpg)

  
Transaction Recalculation Warning Message

We’ve added a warning message to display when any change is made to the deductions attached to a commission plan that affects the commission calculation.   
The message says how many pending transactions are affected, and the user has the option to Cancel, Save Only, or Save & Recalculate the affected transactions.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-DeductionChangeCalc.png)

If the user selects Save Only, the change will only be applied to future transactions that are associated with the updated commission plan. Existing transactions will not be recalculated until the user navigates to the Commission tab of the transaction.  

SkySlope Imports   
We’ve improved transaction imports from SkySlope to include the Cooperating Broker separately from the Cooperating Agent.   
For the Cooperating Broker to be imported, the contact information needs to be entered in the correct fields in SkySlope. Add the Cooperating Broker’s name to the CO Broker Company field and their email address to the E-Mail field to import them into Commissions.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-SkySlope.png)

Commissions Online – New URL 

We’ve updated the primary URL for Commissions Online:  
The previous URL was [https://cwa-prod.azurewebsites.net](https://cwa-prod.azurewebsites.net/).  
The new URL is [https://commissions.constellation1.com](https://commissions.constellation1.com/).  
Both URLs will take the user to the Commissions Online login page.  

The next time you log in to Commissions Online, take a moment to add or update your Bookmarks. 

Agent Commission Statement Master Template Update  
We’ve updated the Agent Commission Statement Master Template to now include more transaction details. 

The newly added information includes:   
•    Transaction Offer Acceptance Date  
•    MLS#  
•    Cooperating Agent Name  
•    Cooperating Agent Phone   
•    Cooperating Agent Email

This update is intended to ensure agents have all the transaction information they need. 

General Ledger Update  
We’ve updated the Agent Payment Setting in the General Ledger to now include agent check stub details when the Agent Payment Setting is set to Bill.   
Previously, when the agent payment was set to Bill, the agent check stub report was not displaying the accounts receivable (agents expense deductions) amounts deducted from their commission checks.   
Now, when the agent payment is set as Bill, the agent check stub report will include accounts receivable amounts similar to how it is created when the agent payment is set as Check. 

  
  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-GL-Bill.jpg)

Reports   
**Agent Transaction Detail Report**   
We’ve enhanced the Agent Type filter to allow the user to select either Internal, External or both when creating the Transaction Detail report.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-AgemtType.jpg)

**Report Scheduler**   
Recently, we introduced a new feature to automatically generate and distribute various reports. With this release, we’ve added Hawaii Standard Time (HST), Alaska Standard Time (AST) and Hawaii-Aleutian Standard Time, allowing companies in these time zones to configure reports to run and have the time stamp consistent with the time zone where their office is located. 

**Franchise – RE/MAX**  
We’ve added the option to include or exclude award allocations in RE/MAX franchisee reports. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023%2002%20Feb/2023-Feb-Commission-AwardAllocation.jpg)

Bug Fixes  

1\. We fixed an issue with the award allocation not showing the correct information on the Transaction Commission Details report. 

Previously, when award allocation was included in a report, the calculation was not showing the correct information. 

Now, when the Award Allocation filter is set to Include, the award allocation will show the correct information on the Transaction Commission Detail report. 

2\. We fixed an issue with a transaction coordinator being added to a transaction as contact type Other when importing transactions from Constellation1 Transactions, formally called Transaction Point.

Previously, when a transaction was imported from Constellation1 Transactions, the transaction coordinator was being added to the transaction with the Contact Type, Other. 

Now, when importing transaction from Constellation1 Transaction, the transaction coordinator will not be included in the transaction. 

3.We fixed an issue with a Co-Operating brokerage being attached to a transaction when the other side of the transaction does not have an agent attached to the transaction, when importing from Constellation1 Transactions.

Previously, when a transaction was imported from Constellation1 Transactions, and there isn't an agent attached to the other side of the transaction, a Co-Operating Brokerage was being attached.

Now, when a transaction is imported from Constellation1 Transactions, and there is no agent on the other side of the transaction, a Co-Operating broker will not be attached to the transaction.

4\. We fixed an issue with statistics and data not displaying on the dashboard for some users.

Previously, when some users logged into Commission Online, their dashboard didn’t display the expected data. 

Now, when these users log in, the expected data related to their account will display on their dashboard.