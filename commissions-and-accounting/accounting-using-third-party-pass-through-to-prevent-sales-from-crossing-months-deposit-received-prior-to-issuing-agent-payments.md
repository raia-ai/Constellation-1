
# Accounting - Using Third-Party Pass-through to prevent sales from crossing months. (Deposit received prior to issuing agent payments.)

The purpose of this article is to show how to use negative pass-through, on the **Third-party** tab of a sale, for commission deposits that are deposited into the bank prior to stepping through the payment process.  

Generally, to make a sale balance, you need to receive a commission deposit equal to the gross revenue of the sale, and you record the commission deposit in the **Deposits Details** section on the **Commission** tab of the sale. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/1add2f30-3f37-45ef-9143-688a50f90c87)

However, in instances when you receive a commission check and would like to deposit it into the bank, prior to closing a sale, it is best to account for the commission deposit as negative **Pass-through**, on the **Third-party** tab, of the sale, along with entering a non-commission deposit in the bank module. 

For example, if you receive a commission deposit of $50,000 and would like to deposit it in the bank on 12/31/2024, but do not plan to close the sale and issue payments to agents until January of 2025, you can follow the steps below to account for the commission check getting deposited into the bank prior to closing the sale.

*   Navigate to Bank > Processing > Non-Commission Deposits.
*   Click **Add**.
*   Select the **Cash Acct** from the dropdown.
*   Enter **Deposit Date** 12/31/2024.
*   Enter **Check#**, if applicable. 
*   Enter **Amount** of $50,000.
*   In the **Description** field, enter the property address of the sale and/or the transaction number of the sale.
*   Click the green plus sign to the right of **Credit Distribution Entries**.
*   Enter $50,000 in the **Amount** field.
*   Select the GL code for the commission revenue account from the **Account** dropdown.  This usually starts with a "4".
*   Select the **Office** from the dropdown.  
*   Select the **Project** from the dropdown, if applicable.
*   The **Comment** field will auto-fill with the **Description** entered above but can be overwritten.  
*   Click **Save**. 

The **Non-Commission Deposits** record should look similar to the screenshot below.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/629eb037-f400-4ced-9fd2-2c4b2d51e5dc)

*   Navigate to **Sales>>Processing>>Sale Transactions**.
*   Find the **Pending** sale and highlight it.
*   Click **Edit**.
*   Navigate to the **Third-party** tab.
*   Click the green plus sign in the **Deductions Total** section.
*   Check the **Pass-through** box.

When you check the **Pass-through** box, you will receive the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/94eb5c61-8820-41c5-8a94-7ecc4eabf0ba)

*   Read the pop-up, then click **OK**.
*   Enter meaningful comment in the **Payee** field.  
*   Select the same **Account** GL code, selected in the **Non-Commission Deposit** record, from the dropdown. 
*   Select the same **Office**, selected in the **Non-Commission Deposit** record, from the dropdown.  
*   Select the **Project** from the dropdown, if applicable.
*   Enter ($50,000.00) in the **Amount** field.

The **Third-party** record should look similar to the screenshot below.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/452e8c24-4cfe-4a0a-9b12-45de588c7179)

*   Navigate to the **Commission** tab.
*   In the **Deposit Details** section, enter a line item with a deposit **Amount** of 0.00
*   Enter a unique **Description**. You may want to reference the non-commission deposit Rec#.
*   **Save** the record.

You can now close the sale and issue payments to agents on whatever day, month, or year that you like.