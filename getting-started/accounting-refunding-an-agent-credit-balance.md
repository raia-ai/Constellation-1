
# Accounting - Refunding an Agent Credit Balance

The purpose of this article is to show how to refund an agent's accounts receivable credit balance, in instances where an agent has overpaid their agent charges.  

To refund an agent's accounts receivable credit balance, follow the steps below:

*   Navigate to **Accounts Payable > Setup > Vendors** and add a vendor record for the agent.
    *   Note:  The refund will not be 1099able, so select **N/A** as the **1099 Form**, in the vendor profile record, or select **N/A** as the **1099 Form** in the **Bill**.
    *   If the agent already has a vendor record, skip this step.
*   Navigate to **General Ledger > Setup > Account Lookup Categories**.
*   Highlight **Assets Control** in the **Account Lookup Category** column, then click **Edit**.
*   Check the box to the right of **AP Module**. 
*   Click **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/3d8bd637-ff65-493d-9c4a-345b683aaf13)

*   Navigate to **Accounts Payable > Processing > Bills**.
*   Click **Add**.
*   Select the agent's vendor name from the dropdown.
    *   Note, you may also free-type the agent's name as entered in the vendor profile record, into the **Vendor** field, or you can click the green plus sign to select the agent's vendor name, from the **Vendor** pop-up.   
*   **Invoice#**, **Internal Comments**, and **Check Comments** fields are optional.
    *   Note, if entering a comment in the **Check Comments** field, you must check the **Print Comment on Check** box, if it is not already selected. 
*   Select **N/A** from the **1099 Form** dropdown. 
*   Enter amount of refund in the **Amount** field. 
*   In the **Agent Charge Entries** section of the bill, click the green plus to select the agent from the **Agent** dropdown. 
    *   Note the **Check Expense Entries** section of the bill is **_not_** used when refunding agents.  
*   Select the **Agents Accounts Receivable** GL code from the **Account** dropdown. 
    *   Note, if you are unsure which GL code is the **Agents Accounts Receivable** GL code, navigate to **General Ledger > Setup > Posting Accounts** to check which GL code is selected in the **Account** field of **Posting Code "AGENTAR"**.   

In the screenshot below, GL code 11150 is the **Agent Accounts Receivable** code.  Note, you may find that a different GL code and/or description of this GL code is shown; make certain to use the GL code, that you have selected in the **Account** field when entering the AP bill.         

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ec2a014a-3e75-40f8-b83b-2df4c0303e0c) 

*   Selecting a **Project** is _**not**_ recommended.
*   The **Date** field is not editable, if you would like to select a different date, you will need to do this from the **Invoice Date** field.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5a7e1b3f-db04-41dc-a3df-da2c7ff6aa98)

*   Uncheck the **Late Fee?** and **Taxable?** boxes, if applicable. 
    *   Note, if you have not enabled the **Late Fee?** and **Taxable?** boxes in your system setup, you will not see these. 
*   Enter **Description**.
*   Click **Save**.

Below is an example of how to enter a bill, to refund an agent all or a portion of their agent accounts receivable balance:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/b6e2a19e-544a-4c10-aea9-964472c0b991)

*   Navigate to **General Ledger > Setup > Account Lookup Categories**.
*   Highlight **Assets Control** in the **Account Lookup Category** column, then click **Edit**.
*   Uncheck the box to the right of **AP Module**. 
*   Click **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/cdd81768-664d-48e1-9cf5-359332bea85c)

*   Navigate to **Accounts Payable > Processing > Pay Bills** to generate a refund check for the agent.

NOTE:  Refunding an agent's credit balance creates an agent charge that is **_not_** considered to be a business expense for the agent.  To finish the refund process, you should navigate to **Agents > Processing > Agent Credits/Payments** to apply any unapplied amounts to the newly created agent charge.  

Was this article helpful to you?

Was this article helpful to you?