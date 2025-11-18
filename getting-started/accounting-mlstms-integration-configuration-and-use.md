---
title: "Accounting - MLS/TMS Integration Configuration and Use"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21308007"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - MLS/TMS Integration Configuration and Use This article's goal is to guide users through the setup and use of the MLS/TMS Integration tool"
long_description: "Accounting - MLS/TMS Integration Configuration and Use This article's goal is to guide users through the setup and use of the MLS/TMS Integration tool to import MLS and TMS transactions into Constellation1 Accounting, allowing them to be processed accordingly within the platform. WARNING: The following steps will only work if you have the System Setting LH_BROKER_ID set up by our Support team: If you do not have this setting configured, please submit a request to accounting@constellation1.com to"
---

# Accounting - MLS/TMS Integration Configuration and Use

This article's goal is to guide users through the setup and use of the **MLS/TMS Integration** tool to import MLS and TMS transactions into Constellation1 Accounting, allowing them to be processed accordingly within the platform.

**WARNING**: The following steps will only work if you have the System Setting LH\_BROKER\_ID set up by our Support team:

![A screenshot of a computer programAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/55acade8-f7b5-4c2b-af4a-f6ead6710749)

If you do not have this setting configured, please submit a request to [accounting@constellation1.com](mailto:accounting@constellation1.com) to request for this feature to be activated. Please note that activation of this feature will be considered a Professional Service and will include an invoice quote to be completed.

**Configuration Steps**

The following tabs in MLS/TMS Integration need to be configured prior to retrieving any MLS transactions.

**Office Mappings**

Within **Sales > Processing > MLS/TMS Integration**, navigate to the **Office Mappings** tab:

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/256483ff-4b3e-402c-9efb-1431f183daa6)

This tab will have all offices noted in your MLS setup as available options. the **Map To** field allows you to create a 1:1 correlation between the MLS office and the offices that you have set up on the platform. These fields must be filled to retrieve any listings to import. Additionally, once these offices have been mapped you can decide which offices to import into Constellation1 Accounting:

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f315d810-8eb0-47c7-bc8b-e1103b2f0aa7)

Once this has been set up, transactions associated with specific agents will be capable of transferring onto the platform as long as the agent’s email on the MLS transactions **matches the email set up on the Agent in Constellation1 Accounting**.

**Import Statuses**

Within the Import Statuses tab, you will be able to choose which MLS/TMS statuses will be allowed to be imported into the Accounting program. Please note that transactions can only be imported into the program if they are not closed.

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/eac8cb81-00c7-4ddc-8ac1-8c5c6dcdfe1c)

**Referral Settings**

The Referral Settings tab will allow you to configure how the Third-party tab will populate on sales transactions for specific fields:

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9defd23d-c9cc-4fcf-9a9d-eda8b3c9872a)

Please note that populating these fields is optional and only needs to be filled out if the MLS transactions that you are importing will always have specific values in these fields.

**Value Mappings (TMS Transactions Only)**

In the Value Mappings tab, you will be able to map specific values found on TMS transactions to transactions found in the Accounting platform. By clicking on each item under Field, you will be able to map specific values to match fields in Accounting as needed:

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/930d1a52-f65c-4dbf-ae65-b064fbea3bf1)

**Retrieving Transactions**

Once the above steps are completed, you will be able to begin pulling transactions into Constellation1 Accounting. Enter the date that you would like to pull all transactions from in the **Get Changes Since** field, then click **Retrieve**:

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/89470955-87f0-4a72-b5db-1565751f561a)

Doing this will populate transactions on the **Transactions** tab:

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/77440cf0-354d-4236-83a4-500232c5dbce)

Please note that Agent E-mail values will appear red if there is not any Agents in the Accounting platform with an exact matching email. These transactions will not be correlated to any existing agent.

From here, you can select which transactions you would like to import by selecting the checkbox beside each one. Once you have determined that you have selected everything that you wish to import, click **Import Selected**:

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/2d871606-3b27-4f88-9277-cd67da246adc)

From here, you can then navigate to Sales > Processing > Sales Transactions to process transactions in Constellation1 Accounting as required.