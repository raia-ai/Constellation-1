---
title: "Accounting - How to Account for Agent Advance"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/19054671"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - How to Account for Agent Advance The purpose of this article is to provide steps for accounting for an agent advance"
long_description: "Accounting - How to Account for Agent Advance The purpose of this article is to provide steps for accounting for an agent advance. If you provide an agent with an advance, and they would like to repay the advance from their future commission payments, we recommend that you account for the advance by following the steps below.  First of all, if you would like to charge the agent a flat fee for interest on the advance, follow the steps below: Navigate to General Ledger > Setup > Chart of Accounts."
---

# Accounting - How to Account for Agent Advance

The purpose of this article is to provide steps for accounting for an agent advance.

If you provide an agent with an advance, and they would like to repay the advance from their future commission payments, we recommend that you account for the advance by following the steps below. 

First of all, if you would like to charge the agent a flat fee for interest on the advance, follow the steps below:

*   Navigate to **General Ledger > Setup > Chart of Accounts**.
    *   Add a new GL code, to account for interest on the advance.  
        *   Account Subtype = Other Income
        *   Account Lookup Category = Revenue 
        *   Account Description = Interest Income from Agent Advances.

See example below:  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f48e122b-f369-445e-9dfd-35f1e2b83a63)

*   Navigate to **Agents > Processing > Agent Charges**.
    *   Add an agent charge to account for interest on the advance.
    *   Code the charge to Interest Income from Agent Advances, GL code 41350 in the example above  

In the example below, the agent is being charged a flat fee of $100 for interest on their advance. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0cbcddc0-1abc-406f-b15e-00de8d5600c3)

To account for the advance given to the agent, follow the steps below:

*   Navigate to **General Ledger > Setup > Chart of Accounts**.
    *   Add a new GL code, to account for the agent's advance.  
        *   Account Subtype = Current Assets
        *   Account Lookup Category = Assets 
        *   Account Description = Agent Advance - \[Agent's Name\].

See example below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6c0b3518-60e1-4bbd-a8a5-2d9f1c29345f)

*   Navigate to **Accounts Payable > Processing > Bills**.
    *   Add a new bill.
        *   Code the bill to "Agent Advance - \[Agent's Name\]", GL Code 11226, as shown in the example above.

See example below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/41dd55e0-c6ae-4b9f-be10-4df95937741b)

*   Navigate to **Agents > Setup > Post-Split Deductions**.
    *   Add a new post-split deduction exclusively for the agent receiving the advance.
        *   Deduction Code = "##\_ADV", where ## is the agent's initials.
        *   Check the "Show Description on Stub Report?" box.
        *   Description = Agent Advance: \[Agent's Name\].
        *   Check the "Show Description YTD on Stub Report?" box.
        *   Credit Account = "Agent Advance - \[Agent's Name\]", GL code 11226 as shown in example above.
        *   Default Percent/Amount values are optional.
        *   Percent of What = Agent $ After Split with Office.
        *   $ Ceiling / Count Ceiling are optional.
            *   If the agent will repay the advance, by the end of the year, then you can enter the amount of the advance in the $ Ceiling field.
            *   If you do not anticipate repayment of the advance by year end, then you will need to track the balance the agent still owes, prior to closing their sales, to avoid over-collection. 

See example below: 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/91be0ddf-7c0d-44f0-95b4-57248aa77765)

The agent's current advance balance can be found on the Balance Sheet and/or the Trial Balance. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e6ce0064-66c2-47f4-b24a-58a8d89f06d2)

When closing a sale for the agent, you can collect payment against the advance, by entering their payment amount in the post-split deduction that you added for the advance. 

See screenshot below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/69943c67-f3db-4c36-8b41-a805d08341b0)

The agent will also be able to see the amount that was deducted from their commission payment, to repay a portion and/or all of their advance. 

See screenshot below: 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/411705ce-d56a-4e51-a290-7c3b929588a2)

As the agent repays the advance, you can check for the remaining amount owed by reviewing the Balance Sheet and/or Trial Balance.

See screenshot below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/33e7c2d1-47cf-4ebf-9d8e-b87ab666858e)

If you would like to provide the agent with a report, to show them how much has been collected towards repaying their advance, you can provide them with the Post-Split Deductions report.  To print the Post-Split Deductions report, follow the steps below:

*   Navigate to **Agents > Reports > Post-Split Deductions**.
    *   Remove Starting Date.
    *   Ending Date = Current Date
    *   Remove checkmarks from all deductions except the Agent Advance deduction.

See Screenshot below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/288e4389-fdf1-4c22-a45e-0eb696484894)

*   Navigate to the Agents tab.
*   Remove the checkmarks from all agents except the agent who has been given the advance. 
*   Click "Process Report".

See screenshot below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d569d594-adfa-4331-9337-2cf5773f1b9f)

In the screenshot below, you can see that the report shows that the agent has paid $1,000 towards their advance. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5a0c4c73-9e8c-4d82-9d2b-c718dbbd02eb)