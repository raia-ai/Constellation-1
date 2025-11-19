
# Accounting - Alternate method of "voiding" and reissuing a replacement check to an agent, employee, and/or vendor.

The purpose of this article is to provide an alternative method for reissuing a check issued from the Accounts Payable, Payroll, or Sales module. 

Often times a vendor, employee, or agent will fail to cash their check in a timely manner, and so the bank may not honor the check, or they may have lost the check.  For whatever the reason, you find yourself in the position of having to reissue a check to them.  Rather than going through the process of voiding the check, in the applicable module, you may find it a little "cleaner" to account for this task in the Accounts Payable module.  To accomplish this, follow the steps outlined below:     

*   Navigate to the **Accounts Payable** module.
*   Click **Setup** in the left selection pane.
*   Select **Vendors** from the dropdown.
*   Add a vendor record for the agent, or employee, whichever is applicable.  You should already have a vendor record if the check was originally issued from the **Accounts Payable** module.  
    *   Please check to ensure you do not already have and agent and/or employee vendor record to avoid duplication.    
*   While in the **Accounts Payable** module, click on **Processing** in the left selection pane.
*   Select **Bills** from the dropdown.
*   Click on the **Manual** radio button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ae6b6685-a5c8-45e3-b714-379c1061869c)

*   *   Click **Add**.
    *   Select the **Vendor** record from the dropdown.
    *   Leave today's date in the **Date Paid** field.
    *   Enter the original **Invoice#**, if applicable.
    *   Enter a meaningful comment in the **Internal Comments** field and/or the **Check Comments** field.
    *   Uncheck the **Count for 1099** box.
        *   The 1099 activity will remain in the period of the original check.
    *   Enter negative check amount value in the **Amount** field. 
    *   Enter original check number in the **Check Number** field.
    *   In the **Check Expense Entries** section, click the green plus sign.
        *   The **Amount** field should autofill with the negative check amount.
        *   Select the **Cost of Sales** GL code from the **Account** dropdown, if reissuing an agent check.  
            *   This usually starts with a "5".
        *   Select the **Accrued Payroll** GL code from the **Account** dropdown, if reissuing an employee's payroll check.
            *   *   This usually starts with a "2". 
        *   Select the GL code from the original payment, if reissuing a vendor check that was originally generated from the **Accounts Payable** module.  
        *   Select the applicable **Office** from the dropdown.
        *   **Project** is not necessary when reissuing a check.  
        *   Enter a meaningful **Comment**.
        *   **Save** the record.

The manual bill record should look similar to the screenshot below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/028b7787-966d-42db-90fb-7c4da7fd6cc3)

*   Click on the Unpaid radio button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/98e02865-2fae-480f-91a2-89f31fcce675)

*   Click **Add.**
*   Select the **Vendor** from the dropdown.
*   Leave today's date in the **Invoice Date** and **Due Date** fields.
*   Enter the original **Invoice#**, if applicable.
*   Enter a meaningful comment in the **Internal Comments** field and/or the **Check Comments** field.
*   Check the **Print Comment on Check** box, if you opted to enter a comment. 
*   Uncheck the **Count for 1099** box.
    *   The 1099 activity will remain in the period of the original check.
*   Enter a positive check amount value in the **Amount** field. 
*   In the **Check Expense Entries** section, click the green plus sign.
    *   The **Amount** field should autofill with the positive amount.
    *   Select the same **Account** and **Office** as previously selected in the manual accounts payable record. 
    *   **Project** is not necessary when reissuing a check.  
    *   Enter a meaningful **Comment**.
    *   **Save** the record.

The **Bill** should look similar to the screenshot below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9d6ed7ac-1e1f-4617-84cf-9b07a460095e)

*   While in the **Accounts Payable** module, with **Processing** still open in the left selection pane, select **Pay Bills**.
*   Step through the payment process to print a replacement check.

Note:  When completing your bank rec, two new payment records will retrieve, one is the negative manual bill record, which will retrieve as a positive value and the other is the replacement check record, which will retrieve as a negative value.  Clear the positive and negative voided pair, that represent the check that was lost or too old to cash, they net to zero.  Only clear the replacement check when it actually clears the bank.  

Was this article helpful to you?

Was this article helpful to you?