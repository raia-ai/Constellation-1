---
title: "Berkshire Hathaway HomeServices Configurations"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/13434611"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Berkshire Hathaway HomeServices Configurations | Constellation1 Customer Hub Constellation1 Commissions supports the data bridge batch reporting for a"
long_description: "Berkshire Hathaway HomeServices Configurations | Constellation1 Customer Hub Constellation1 Commissions supports the data bridge batch reporting for all Berkshire Hathaway HomeServices Affiliates. This article highlights the initial configuration instructions which are covered during implementation.  Navigate to Setup > Company Profile > Integration  Enter “BHHS” for Franchise Code Ensure the Enable Franchise Integration checkbox is selected If MLS/Transaction Fee should be exempt from Franchise"
---

# Berkshire Hathaway HomeServices Configurations | Constellation1 Customer Hub

Constellation1 Commissions supports the data bridge batch reporting for all Berkshire Hathaway HomeServices Affiliates. This article highlights the initial configuration instructions which are covered during implementation. 

**Navigate to Setup > Company Profile > Integration** 

*   Enter “BHHS” for Franchise Code
*   Ensure the Enable Franchise Integration checkbox is selected
*   If MLS/Transaction Fee should be exempt from Franchise Fees, select the Exempt MLS/Transaction Fee checkbox
*   If Referral fee(s) should be exempt from Franchise Fees, select the Exempt Referral Fee checkbox

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17772046)

Navigate to Setup > **Branch Offices**

*   Enter the Berkshire Hathaway HomeServices office number for this Branch Office (these numbers are assigned by Berkshire Hathaway HomeServices) in the Franchise Number field.
*   All Branch Offices within a brokerage must have the same first 5 characters (refers to Berkshire Hathaway HomeServices Affiliate ID).
*   Within the Commissions system, multiple Branch Offices will share the same Franchise number. Note that even if only one location, a Franchise number is required.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17772047)

**Agents & Branches**

*   Each Agent must have an associated Berkshire Hathaway HomeServices Agent ID entered in the Franchise ID field, which is located on Main tab of Agent; Additional Details panel.
*   If the Agent’s Franchise ID is omitted, those transactions will be listed with validation errors in the Batch Manager and omitted from batch submission until the Franchise ID has been updated.
*   Also note each Agent must be assigned a Branch Office.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17772048)

**Transaction Level**

*   Each Transaction must have a Transaction Group selected on the Main Tab
*   Each transaction must be assigned a Branch (Selling Side, Buying Side or Both)

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17772049)

**Franchise Tab of Transaction once you EXPAND Tabs by click on +**

*   All fields in the Franchise tab are specific to Berkshire Hathaway HomeServices.
*   There are separate Add / Edit / Del / Save / Cancel buttons to allow these fields to be edited even after transactions are closed. First save the transaction then click Edit in the Franchise box to enable editing of the fields.
*   Franchise Transaction Type is required for Berkshire Hathaway HomeServices batches.
*   The Transaction Number field will automatically populate and should not be changed; this is the transaction number that will be reported to Berkshire Hathaway HomeServices.
*   The Adjust Sequence Number is essentially how many times this transaction has been previously transmitted successfully to Berkshire Hathaway HomeServices.
*   It must be 0 the first time a closed transaction is submitted then incremented by 1.
*   Commissions handles this automatically but there are times when users may need to manually set the value because a previous submission was rejected.
*   The Exclude from Franchise Reporting box is for situations where a transaction should not be sent to Berkshire Hathaway HomeServices.  For example, transactions that existed before the Data Bridge was enabled or special transactions exempt from all Franchise Fees (examples vary depending on Franchise Agreements with Berkshire Hathaway HomeServices but could include Agents selling their own properties).
*   If,  “Is In Network Referral “ is checked (i.e. there was a referral from another brokerage under a HSF or Berkshire Hathaway HomeServices subsidiary) then “Is Referral” must also be checked and Referring Brokerage Affiliate ID must have a valid Berkshire Hathaway HomeServices Affiliate ID (i.e. 2 character state/province abbreviation + 3 digit affiliate number).

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17772050)

**Referral Fees**

*   Referral Fees can be excluded from Berkshire Hathaway Franchise Fees.  Any transaction(s) with the Referral Fees checkbox selected will result in the brokerage paying less in Franchise Fees for that transaction.
*   Probably the most common situation that leads to adjustments needing to be sent to Berkshire Hathaway is when a referral was not marked as exempt from Franchise Fees but should have been.
*   The transaction will need to be reversed, initiate the check box on the Referral Fee, re-close,  adjust the sequence number if already submitted so that it will be included in next batch.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17772051)

Was this article helpful to you?

Was this article helpful to you?