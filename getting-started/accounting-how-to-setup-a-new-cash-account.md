---
title: Accounting - How to Setup a New Cash Account
---

# Accounting - How to Setup a New Cash Account

The purpose of this article is to provide the necessary steps to setup a new cash account that will be used to pay agents, vendors, and/or employees.

1.  Setup a new GL code.
    1.  Navigate to **GL** \> **Setup** \> **Chart of Accounts** and click **Add**.
    2.  Select **Current Assets** from **Account Subtype** dropdown.
    3.  Select **Cash** from **Account Lookup Category** dropdown.
    4.  Enter **Account Description.**
    5.  Enter a unique five digit **GL Code.**
    6.  Enter **Bank Account Information**.
        1.  **Bank Account Information** is optional; however, it is required for **NACHA Batches** functionality.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d9b6d18c-15dd-4d25-b5f3-dca3b78cf2b2) 

2.  Update **Posting Accounts**.
    1.  Navigate to **GL** \> **Setup** \> **Posting Accounts.**
    2.  Highlight **Posting Code CASHDFLT.** 
    3.  Click **Edit** to select the new cash **Account** for non-commission deposits, if applicable.
    4.  Click **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/7ec60c9e-2236-45e8-af04-cdfbba7828d3)  

3.  Setup new classes for Sales, AP and Payroll, if applicable.
    1.  Navigate to **System** \> **Setup** \> **Classes**
    2.  Click **Add,** complete required fields, and then **Save.**  
4.  Edit the default classes in Office Setup.
    1.  Navigate to **System** \> **Setup** \> **Offices.**
    2.  Highlight the **Office** and click **Edit.** 
    3.  Select new **Class Defaults** from the dropdowns for **AP**, **Payroll**, and **Sales** then **Save**.
    4.  If you have more than one office, repeat the steps above.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d97d3506-c459-4901-9be1-a2fc2f9db32a) 

5.  Edit all pending sales, third-party records in those sales, unpaid AP bills and unpaid payroll transactions, if applicable.
6.  If you use the Payroll module, navigate to **Payroll** \> **Setup** \> **Employees.**
    1.  Highlight the first employee **Name** and click **Edit**.
    2.  Select the new **Class** from the dropdown and **Save**.
    3.  If you have more than one employee, repeat the steps above.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/fa4511b6-46ec-4511-af8c-00b4f2739507) 

7.  Edit the **Default Class** in vendor records.
    1.  Navigate to **AP** \> **Setup** \> **Vendors.**
    2.  Click **Edit**.
    3.  Select the new **Default Class** from the dropdown and **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8756490a-4ddf-4a5f-a02e-65227d4bd6a3) 

8.  Create a journal entry to recognize the opening deposit into the new cash account.
    1.  Navigate to **GL** \> **Processing** \> **General Journal Entries.**
    2.  Click **Add,** fill out required fields and **Save**.
        1.  Note: **Debit** the new cash account and **Credit** the cash account the funds were transferred from.
9.  For bank reconciliation purposes, enter a beginning balance of zero, for the new account.
    1.  Navigate to **Bank** \> **Setup** \> **Monthly Bank Balances**.
    2.  Select the new **Cash Acct** from the dropdown.
    3.  Click **Add**.
    4.  Enter a **Reconciliation Date** equal to the last day of the month, prior to opening the account and hit **Save**.
        1.  Do not edit any other fields; they must remain as $0.00.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9ac8f825-eb71-4327-bef2-e13d51eab816) 

Was this article helpful to you?

Was this article helpful to you?