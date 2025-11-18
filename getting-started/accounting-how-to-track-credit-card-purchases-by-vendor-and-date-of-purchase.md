---
title: "Accounting - How to track credit card purchases by vendor and date of purchase"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/17617904"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - How to track credit card purchases by vendor and date of purchase The purpose of this article is to provide workaround instructions for h"
long_description: "Accounting - How to track credit card purchases by vendor and date of purchase The purpose of this article is to provide workaround instructions for how to track credit card purchases by vendor and date of purchase.  Before you will be able to track credit card purchases by vendor and date of purchase, you will first need to setup a new GL liability code for the credit card you wish to track, make certain the GL Code starts with a '2', so it will group with other liability GL Codes on your Balan"
---

# Accounting - How to track credit card purchases by vendor and date of purchase

The purpose of this article is to provide workaround instructions for how to track credit card purchases by vendor and date of purchase.  

Before you will be able to track credit card purchases by vendor and date of purchase, you will first need to setup a new GL liability code for the credit card you wish to track, make certain the GL Code starts with a "2", so it will group with other liability GL Codes on your Balance Sheet.  Initially you will setup the account with an **Account Subtype = Current Assets**, **Account Lookup Category = Cash**, **and Bank Account Type = Checking**.  You will edit this GL code after you have setup a new AP class. 

To set up a new GL code, navigate to **General Ledger > Setup > Chart of Accounts** and setup a new GL code using the following screenshot as a guide:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/126bd321-cd35-4d89-b4cf-fc2da654ffad)

Next, setup a new AP class.  To do this, navigate to **System > Setup > Classes** and setup a new **Class** using the following screenshot as a guide:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/4360c2c5-e3e9-41a3-941a-8bb540861730)

After you setup the new AP class, navigate back to **General Ledger > Setup > Chart of Accounts** and edit the GL code using the following screenshot as a guide:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c8e51fec-0cac-4c01-8c40-8aab6aeb6a48)

You are now all set to start tracking credit card purchases by vendor and date of purchase.  

When entering credit card charges, navigate to **AP > Processing > Bills > Manual** view. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e75d559e-e9a4-4b06-bfde-9d5d9aa7ac8a)

*   Click **Add**
*   Select the **Vendor** from the dropdown. 
*   Enter the date the charge was made in the **Date Paid** field.
*   Select the new AP class, for your credit card, from the **Class** dropdown.
*   Select **Resp. Code** from the dropdown or accept default.
*   Entering **Invoice#** and **Internal Comments** is optional.  
*   The **Check Comments** field can be left blank, it is not applicable when entering **Manual** AP bills.
*   The **Count for 1099** box and the **1099 Form** will default to settings in the vendor's profile record but may be overridden if applicable. 
*   Enter **Amount**.
*   Check the **Debit Transaction** box to generate a unique **Check Number** or enter one manually.
*   Enter **Check Expense** **Entries**.
*   Enter **Agent Charge Entries** if applicable.
*   **Save**

Upon **Save**, the liability for the credit card will be _credited_, which increases the balance of the credit card liability, and the expense will be _debited_.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/15ef3e68-50b0-4c02-adb5-a0bc96de13d3)

When it is time to make a credit card payment, assuming you will be making payments online, navigate to **AP > Processing > Bills > Manual** view.

*   Click **Add**
*   Select the _credit card company_ from the **Vendor** dropdown. 
*   Enter the date the payment was made in the **Date Paid** field.
*   Select **Class** from the dropdown.
    *   Note:  The **Class** selection will _not_ be the credit card class, it will be the class used for AP payments, usually your operating account.
*   Select **Resp. Code** from the dropdown or accept default.
*   Entering **Invoice#** and **Internal Comments** is optional.  
*   The **Check Comments** field can be left blank, it is not applicable when entering **Manual** AP bills.
*   The **Count for 1099** box and the **1099 Form** will default to settings in the vendor's profile record. 
*   Enter **Amount**.
*   Check the **Debit Transaction** box to generate a unique **Check Number** or enter one manually.
*   Enter the GL Code for the credit card liability in the **Check Expense** **Entries**.
*   Do not enter anything in the **Agent Charge Entries** section.
*   **Save**

Upon **Save**, the liability for the credit card will be _debited_, which decreases the balance of the credit card liability, and the cash account will be _credited_.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/1a773fd4-1a90-4dca-932b-e9f588b5a1dd)

Note:  One benefit of using the above method to account for credit card purchases, is that it allows you to choose a unique vendor for each purchase and select the actual date the charge was made.  Another benefit is that you can make payments on your credit card, instead of paying the balance in full.