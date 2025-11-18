---
title: "Accounting - How to Defer Agent Payments"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/19089349"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - How to Defer Agent Payments The purpose of this article is to provide steps on how to account for deferring an agent's commission from a"
long_description: "Accounting - How to Defer Agent Payments The purpose of this article is to provide steps on how to account for deferring an agent's commission from a sale.  To defer an agent's commission, you will need a GL code for Commissions Payable, a unique post-split deduction with the Deduct for 1099? box check, and a vendor profile record for the agent, with the Print 1099? box checked.  To setup a GL code for Commission Payable, navigate to the General Ledger module and following the steps below. You c"
---

# Accounting - How to Defer Agent Payments

The purpose of this article is to provide steps on how to account for deferring an agent's commission from a sale. 

To defer an agent's commission, you will need a GL code for **Commissions Payable**, a unique post-split deduction with the **Deduct for 1099?** box check, and a vendor profile record for the agent, with the **Print 1099?** box checked.  

To setup a GL code for **Commission Payable**, navigate to the **General Ledger** module and following the steps below.  You can skip this step if you already have a liability setup for **Commissions Payable**.

*   Click **Setup**.
*   Select **Chart of Accounts** from the dropdown.
*   Click **Add**.
*   Select **Current Liabilities** from the **Account Subtype** dropdown.
*   Select **Liabilities** from the **Account Lookup Category** dropdown.
*   Enter **Commissions Payable** in the **Account Description** field.
*   Enter a unique **GL Code** for the liability.
*   Click **Save**. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/dc087af2-209c-432a-a720-6d8f7bff4d7e)

To setup a post-split for the agent, navigate to the **Agents** module and follow the steps below.

*   Click **Setup**.
*   Select **Post-Split Deductions** from the dropdown.
*   Click **Add**.
*   Enter unique **Deduction Code** up to 8 characters.
    *   Recommended format of code:  "DEF\_ABC", where "DEF" stands for deferred, and "ABC" is the agent's initials.
*   Check the **Show Description on Stub Report?** box.
*   Enter unique **Description**.
    *   Recommendation:  Include the agent's full name in the description.
*   Check the **Show Description YTD on Stub Report?** box.
*   Select GL code for **Commissions Payable** from the **Credit Account** dropdown.  
*   Edit **Default Percent / Amount** values, if applicable.
*   **Percent of What** selection is required.  We recommend you select **Agent $ After Split With Office** from the dropdown, in case at some point the agent would like a percentage deferred instead of the full amount of their commission.  
*   Enter **$ Ceiling / Count Ceiling**, if applicable.  
*   Click the **green plus sign**, to the right of the **Vendor to pay** field, to select the agent from the list of vendors, or you can add the vendor on the fly. 
    *   For assistance with adding a new vendor, click on the following link to access a Knowledge Base article that will guide you through the process.  **[How to add a vendor profile record.](https://constellation1.na3.teamsupport.com/knowledgeBase/24924349)** 
*   Select **Seller/Buyer/Address** from the **Bill Comment Option** dropdown. 
*   Check the **Deduct for 1099?** box. 
    *   This will ensure that the agent's commission will not be 1099'd from the sale.  The agent's 1099 earnings will be determined by the date that the agent is paid from the **Accounts Payable** module.    
*   Click on the **Manage Subscriptions** button and check the **Subscribe** box for the agent.  
*   Click **Save**. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/55717e78-e67d-4fd0-81fe-d7cb80509a2c)

When closing a sale for the agent, in the **Post-Split Deductions** section of the agent's commission record, enter the amount of the deferral in the **Amount** field or if the agent would like a percentage of the **Agent $ After Split With Office**, enter the percentage in the **Percent** field, then step through the payment process.  Upon finalizing the payment process, an AP bill will be created for the agent and the agent will be 1099'd based on the date the AP bill is paid.   

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/dbc7ed58-cd6c-439d-8e68-7cd73904b0fb)

Was this article helpful to you?

Was this article helpful to you?