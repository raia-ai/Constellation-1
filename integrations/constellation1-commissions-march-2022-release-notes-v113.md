---
title: "Constellation1 Commissions March 2022 Release Notes v1.13"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/16305127"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Commissions March 2022 Release Notes v1.13 Production Release: March 17 2022 v1.13 RELEASE SUMMARY Trust Deposits: Improved workflow an"
long_description: "Constellation1 Commissions March 2022 Release Notes v1.13 Production Release: March 17 2022 v1.13 RELEASE SUMMARY Trust Deposits: Improved workflow and behavior, including a character limit for the Check Number field, Sync Trust defaulted to ON, and check details made available."
---

# Constellation1 Commissions March 2022 Release Notes v1.13

Production Release: March 17 2022 v1.13  

## RELEASE SUMMARY

**Trust Deposits:** Improved workflow and behavior, including a character limit for the Check Number field, Sync Trust defaulted to ON, and check details made available.

  
**Commission Disbursement Authorization Letter:** Separated buying and selling commissions on both sides transactions and added referrer’s mailing address.

  
**Disbursed By:** Added the ability to search for a title company’s contact person by first or last name. 

  
**Commission Plans Company/Agent Split:** Added ability to calculate company and agent commission splits based on agent side gross commission. 

  
**Character Limit Added to Company Name on Contact Form:** Added a character limit to the Company Name field on the contact details form.

  
**Role of Title Company in a Transaction:** Added the option to select the role of a title company in a transaction. 

**Agent History:** Allow negative integer.

**Closing transactions:** Added option to bypass A/R sync.    

**Bug Fixes**

## CONSTELLATION1 COMMISSIONS

#### Trust Deposits 

  
Based on customer feedback, we’ve made improvements to Trust Deposits. 

  
It’s important for users who hold trust on transactions to have access to financial details. Trust holders are now able to view the details of trust checks that have been deposited and disbursed.

The added details include:

*   Check number
*   Posted status (Posted/Unposted)
*   Check comments

Additionally, the default setting to Sync Trust deposits is now set to ON. Going forward, trust deposit syncs will happen automatically unless this option is disabled. 

  
We’ve also added a character limit to the Check Number field for trust deposits to align with the 11-character limit in QuickBooks®. In the past, check numbers over 11 characters would cause the trust deposit to fail and prevent future trust deposits from automatically syncing. 

Now when entering a check number, you will not be able to type more than 11 characters. 

  
   
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions-2022-March-CheckNumber.png)

####    
Commissions Disbursement Authorization Letters

**Separate Buying and Selling Commissions**

We’ve updated the Commission Disbursement Authorization letter to separate the buying and selling commission amounts into their own line items on “both sides” transactions. 

  
This enhancement makes it easier to see the commission amounts for the buying and selling sides when both are being paid to the same broker.

An added benefit is that the title company can easily find and include the separate amounts in their closing documents.  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions-2022-March-CDA-BuySell.png)

_Excerpt from CDA Letter_

   
**Added Referral Contact Address**

Additionally, the contact address of anyone who made a referral (if applicable) is now included on the Disbursement Authorization letter. 

This will reduce the time and communication needed by the title and escrow companies to collect contact information to mail a check when a referral fee is due.

#### Disbursed By – Search for Company Contact Person

We’ve added the ability to search for a title company’s contact person by first or last name on a transaction’s Commission Disbursed page. 

  
If your company has multiple contacts at a single title company, it’s important to select the correct contact to associate with a transaction. This enhancement allows a user to easily search for and select the correct contact for a transaction.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions-2022-March-NameSearch.png)

####   
Commission Plans – Company/Agent Split Calculation 

Company/agent commission splits can now be calculated based on the agent side gross commission or the defined commission. 

On the Commission Plan Details page, there is a toggle under Advanced Options to set the company/agent split.

The Calculate Adjusted Company Portion on Agent Side Gross option defaults to OFF, meaning the split will be based on the adjusted agent commission.

  
Enabling this option by turning the toggle ON will calculate the company/agent split based on the agent side gross commission.

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions-2022-March-Gross-Comm-Split.png)

#### Contacts – Company Name Character Limit

We’ve added a 35-character limit to the Company Name field when entering a contact to align with the QuickBooks® character limit.

  
When syncing with QuickBooks®, we append a 5-digit company ID to the company name. Since the QuickBooks® character limit is 41, 35 is the maximum our field can allow, since we also add a space between the company name and ID number. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions-2022-March-Company-Name.png)  
 

####   
Select Role of Title Company in a Transaction 

We’ve added the ability to select a role for the title company attached to a transaction.  

  
In specific cases, where escrow or title companies will disburse commissions, a user can select the appropriate title company and role. For example, a user can now select Escrow Company for a transaction, whereas previously, the role defaulted to Title Company with no option to change it.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions-2022-March-TitleCompanyRole.png)

####   
Negative Integer in Agent History 

Users can now use negative integers for closed transaction in the agent history.

This enhancement allows the user to adjust total amounts for past transactions that may have an incorrect values. 

For example: Sales volume.

This change will not affect 1099s generated by QuickBooks® for US-based clients. 

_**Note:** In a future release, Canadian clients will need to check and ensure the accuracy of the T4A reports from QuickBooks®._

This change will also save hours for users who reconcile their bank accounts. 

####   
Closing Transactions

We’ve added a new toggle to enable or disable the A/R sync when closing a transaction. 

The new toggle is located in Advanced Settings under Transaction Settings. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions-2022-March-ByPassARSync.png)

The Bypass A/R Sync on Transaction Closing toggle will be disabled by default. This means the automatic A/R sync on closings will happen automatically. By enabling this option, you will stop the automatic sync process. 

With this enhancement, we have added a Refresh button to the Close Transaction Wizard. When clicked, the Refresh button allows the user to manually sync agent data with QuickBooks® and populate the Pending Expense Amount column for the selected agent. 

BUG FIXES

*   Fixed an issue with displaying the agent's name on checks for agents who are paid as a company. The company name will now show on the check, not the agent’s name.
*   Fixed an issue with Accounts Receivable funds being added to an agent check stub report. They will now be deducted from the total on the agent check stub report.