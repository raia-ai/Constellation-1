# Accounting - NACHA Batches | Constellation1 Customer Hub

The purpose of this article is to provide instruction on how to setup and use NACHA ACH payment processing.  A NACHA file is an electronic set of instructions that creates a batch of ACH payments when uploaded to the bank.

Before you will be able to submit NACHA batches to your bank, you will first need to contact your bank to find out their process for importing NACHA batches.  When you reach out to your bank, you will need to ask them what the first character to use for your company identifier and ask whether you need to include both sides, debit and credit, in each transaction.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/b638881d-94e2-4c42-a69b-c7ee48159c8f)

After meeting with your bank, follow the instructions below prior to submitting your first NACHA batch.&#x20;

First, navigate to **General Ledger > Setup > Chart of Accounts**

Select the cash account that will be used to generate the NACHA payment file.

* NOTE: The General Ledger account setup process is the same, whether issuing ACH Sales Commission or ACH Vendor payments
* Enter the Bank information as required
  * Name, Routing Number, Account Number, Account Type
* **Save** when completed

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f7927218-fb49-43f7-bf85-8b6157ae5a0f)

To pay agents via ACH, navigate to **Agents > Setup > Agents**

Select agent and click **EDIT**.

* Click on the **Credit Card/ACH** tab, and check the **Pay Commission by ACH?** box
* Click the ‘+’ sign below **ACH Information List** to add the agent’s bank account information
* Select **Account Type**, enter **Routing Number**, **Account number**, and **Holder Name**, as it appears on check
* Note:  “**%**” defaults to 100.00%.  You may choose to have the ACH drafted out of more than one account.  If the agent chooses to do this, ask them what % they would like drafted from each account.
* **Save** when completed

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9cc60ae8-9e9a-4329-a61e-adc6ad4c83d1)

To pay vendors via ACH, go to **Accounts Payable > Setup > Vendors**

* Select vendor and click **Edit**
* Click on the **ACH Info** tab and check the **Pay By ACH?** box
* Click the ‘**+**’ sign under **ACH Information List** to add the vendor’s bank account information
* Select **Account Type**, enter **Routing Number**, **Account number**, and **Holder Name**, as it appears on check
* Note:  “**%**” defaults to 100.00%.  You may choose to have the ACH drafted out of more than one account.  If the vendor chooses to do this, ask them what % they would like drafted from each account.
* **Save** when completed

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/afef6565-f6f6-4a48-b2c3-a0e95810990c)

After issuing agent and/or vendor payments, navigate to **Bank > Processing > NACHA Batches**

* Select **Cash Acct** from the dropdown

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0bc2bc92-0b48-4af6-88a7-e0b2791f2798)

* Navigate to the **Account Settings** tab
* Select **First Character of Company Identifier**
  * NOTE: Contact your bank to obtain the value for this field
* Check the box to **Include both sides (debit and credit) in each transaction**, only if instructed to do so by your bank
* Click **Choose Folder** and browse to where you want to save the NACHA export file

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a29258be-7c9f-4380-8b94-113481974269)

* Navigate to **Batches** tab and click **Add**
* Select date range for transactions to retrieve
* Select **Effective Date**
  * NOTE:  This is usually the bank’s next business day.  &#x20;
* Click **Retrieve Payments**
  * NOTE: Click the box to the left of any record you do not want to include in your NACHA batch and click **Remove Selected**
* Click **Save**
* Click **Generate NACHA File**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/689cd704-187c-4df8-8993-24aa0be6e439)

* Click **OK** to the message confirming the file was created

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8687ebca-b536-4322-ae8e-90316368b0c0)

* Upload NACHA file using the steps provided by your bank

Was this article helpful to you?

50% of voters found this helpful

Was this article helpful to you?
