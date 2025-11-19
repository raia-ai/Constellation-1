---
title: Accounting - Adjusting Under-collected Pre-split Deductions From the Current Calendar Year
---

# Accounting - Adjusting Under-collected Pre-split Deductions From the Current Calendar Year

The purpose of this article is to show how to account for an agent being overpaid, in the _current_ calendar year, when pre-split amounts were under collected.

**Note:** Do not add new commission records in sales that closed in a previous calendar year. This will alter the agent's 1099 value and will need to send the agent and the IRS a corrected 1099 for that year.  

If an agent was overpaid because pre-split amounts were under collected, navigate to **Sales > Processing > Sales Transactions** and follow the steps below:

*   Navigate to the **Closed** view.
    *   Please note that a limited number of sales can be found in the **Closed** view: the current month's closed sales and the closed sales for the last 2 full months.  After that timeframe, the older sales can be found in the **All** view.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0253afdd-08a2-42b2-96ad-8b8cb0b06a7a)

*   Highlight the original sale transaction in the left pane.
*   Click **Edit**. 
*   Navigate to the **Commission** tab.
*   Click the green plus sign, to add a new commission record for the agent.
*   Select the agent from the pop-up.
*   Click **OK**.
*   Select **Category** "Z", signifying that this is a commission adjustment.
*   Enter the amount that was under-collected in the relevant pre-split deduction **Amount** field.
*   Ensure that the **Office $** and **Agent $** fields reflect the correct values.
    *   Note, pre-split deductions are shared expenses between the office and the agent if the agent's incentive level is less than 100%.  Which means that if the agent was overpaid, then the office was overpaid as well.
*   In the Pre-split Deductions and Post-Split Deductions sections, zero out any default deductions; the override box will be selected automatically when you zero out the values.

At this point, the amount the agent was overpaid will populate the ACHG post-split as a negative value.  When you step through the payment process, an agent charge will be created for the agent, to repay with a future closing.  Alternatively, you can request a check from the agent, then enter an agent non-commission deposit in the bank module and apply it to the newly created agent charge. 

*   Uncheck the "Recalc at closing" box to ensure that none of the values change during the payment process.
*   Review the commission record for accuracy.
*   Click **Save**.
*   Set the **Processing Date** back to the date of the original payment. 
*   Click the **Actions** button.
*   Select **Issue Payments**.  
    *   Alternatively, navigate to **Sales > Processing > Issue Commission Payments**.
*   Step through the payment process.

In the screenshot below, the pre-split FRAN was under-collected $110 and the agent was at a 50% split with the office, when the sale closed.  This resulted in the agent being paid $50 too much.  When you step through the payment process, a $50 agent charge will be created, to charge back the agent the $50 they were overpaid.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d41bc4a9-0387-48a7-a853-529fcaa5b50c)

Was this article helpful to you?

Was this article helpful to you?