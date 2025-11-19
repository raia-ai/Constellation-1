---
title: How to Record Agent 1099 Activity When Commission Paid Directly by Title/Escrow Company
---

# How to Record Agent 1099 Activity When Commission Paid Directly by Title/Escrow Company

This article details the steps required to configure the application to allow users to record an agents 1099 activity when they receive a commission check directly from the Title/Escrow company without affecting the Brokerages financial records. 

To configure the application to record agents 1099 activity when paid by a third party; on the left navigation bar select **System Settings / General Ledger** 

On the Additional Details card of the Main tab, ensure Agent Commission Paid by Third Party toggle is ON. This will apply to all general ledger profiles users may have configured. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/df56e24c-885d-42fe-951b-8b2bac9b0686)

Scroll down the page and in the Constellation1 Processes column, Bank Accounts section, find and select "Record Agent Activity(1099s)". In the Constellation1 Accounts column (middle column), add Constellation1 Account OR select from the list of bank accounts available. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/b85d0ba0-72ca-42b3-9775-374a05c7cf7f)

If user selected to add a new bank account, and toggled ON Create Matching Account in QuickBooks®, then a new bank account will be created in QuickBooks® and automatically display in the QuickBooks® Accounts column. Select Save. 

If user is integrating with Xero®, bank accounts must be created in Xero® before they can be selected via the drop down. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/82c67619-683b-440e-86db-f8df29aa3e5e)

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6cbbed44-8e8d-4836-9bb4-934478374a1c)

If user selected an existing bank account in the Constellation1 Accounts column, select the refresh QuickBooks® icon. Scroll down the page and select the corresponding QuickBooks® bank account from the list and Save.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17637940)

To confirm you have set this up correctly, navigate to the Commission tab of any transaction.  Expand Additional Detail to ensure Commission Disbursed by Third Party toggle is ON, so that you can select/add the Disbursed By contact who is paying the commission and the corresponding Disbursement Form. Save the transaction. 

Please note, if Commission Disbursed by Third Party is toggled ON, any new transaction added manually, via the Transaction Wizard or imported will automatically inherit all the configuration noted above. For further information on turning off this automation, please click here; [Advanced Settings](https://constellation1.na3.teamsupport.com/knowledgeBase/20368643) or [Advanced Settings ( Video).](https://constellation1.na3.teamsupport.com/knowledgeBase/22297060)

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f57677a7-fd6f-4c8a-a25b-6b455467945c)

Users can now process the transaction's closing and will see the applicable bank account on the Review Closing Report before selecting the Process button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17637942)