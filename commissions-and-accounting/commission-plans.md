---
title: Commission Plans | Constellation1 Customer Hub
---

# Commission Plans | Constellation1 Customer Hub

This article will provide a better understanding of the logic of creating Commission plans, and helpful if you are looking into how to get the best use of our logic in our plans. 

*   A commission plan is the Agreement between the Brokerage and Agent. Every Brokerage knows exactly what they need to make from each Agent to stay in business, however commission plans differ from Brokerage to Brokerage.
*   Select **Commissions** on the left sidebar; then select NEW icon at top right of window.
*   Assign the plan a name (limited to 6 characters) and more details can be entered in Plan Description field.
*   The **Commission Calculation Type** allows you to specify how commissions are calculated between the Agent and Brokerage.

Select the option from the drop down:

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-CommissionPlans/commissionplans1.png)

*   **_Anniversary Period_** - calculation is the same as 'Year Written' below, except the system will use the transaction's close date instead of effective date.**_Closed_** - calculates commission **from the Agents** **Anniversary start date to the transaction’s closing date**.
*   **_Firm_** – calculates commission using the **firm date** of the transaction; from the Agents Anniversary start date to the transaction’s firm date. If you have more than one transaction with the same firm date, the program will use the transaction number as the secondary field to sequentially calculate the Agents earned commissions for plans that are based on different levels.
*   **_Partial Payment_** **-** provides ability for a Brokerage to collect a flat fee for each installment received. Full details can be found via Creating a Partial Payment Commission Plan
*   **_Rolling 12 Month (Closed)_** – calculates the commission according to the Agent’s commission level based on the **closed date**; within a plan period that starts and counts all **closed deals** **12 months prior** to the closing date of the transaction.
*   **_Rolling 12 Month (Closed - Previous 12)_** – calculate commission at the same level in an existing month, using only the history of the previous 12 months without crossing levels based on commission, sales volume, etc. If the agent represents both sides of a transaction, then the commission amount on the Buying Side will include the Selling Side commission. 
*   **_Rolling 12 Month (Written)_** – calculates the commission according to the Agent’s commission level based on the **effective date**; within a plan period that starts and counts all **written deals** **12 months prior** to the written date of the transaction.
*   _**Rolling 12 Month (Less a Day)**_ _\- calculates the commission according to the Agent’s commission level based on the **closed date**; within a plan period that starts and counts all **closed deals** **12 months prior** to the closing date of the transaction. Less one day._
*   **_Rolling 13 Month (Exclude Existing Month) -_** calculates the commission according to the Agent’s commission level based on the closed date; within a plan period that starts and counts all **closed deals in the 12 months prior to the closing date of the transaction and will exclude any and all transactions closed in existing month**
*   **_Today (Closed)_** – calculates the Agent's commission from the Anniversary start date to today (the day you are processing the closing).  The commission logic for ‘Today’ is exactly same as type ‘Closed’, except the history date range for ‘Today’ is Anniversary starting date to Today’s day,  the history for type ‘Closed’ is from Anniversary starting date to current transaction’s closed date. The plan will go to which level is always based how much history calculated from above commission history formula. 
*   **_Transaction_** – calculates the commission according to the Agent’s commission level based on the **effective date** of the transaction (the date the transaction was entered); from the Anniversary start date to the transaction’s effective date.  If you have more than one transaction with the same effective date, the program will use the transaction number as the secondary field to sequentially calculate the Agents earned commissions for plans that are based on different levels.
*   _**Year Written** –_ calculates the commission according to the Agent’s commission level based on the **effective date**; from the Anniversary start date to the anniversary end date.  Logically, you only have one option; "N", then the calculation will include "Closed" transactions only.  We cannot think of an instance in which you would want the commission calculation to include both open and closed transactions.  If you have more than one transaction with the same effective date, the program will use the transaction number as the secondary field to sequentially calculate the Agents earned commissions for plans that are based on different levels. 
*   **_Note\-_** _Commissions recalculate at the time the transaction status has changed from open to closed.  If the commission plan is configured to "Include Open Transactions" via the Additional Configuration panel, then the transaction will calculate commission based on the Agents' Anniversary start and end dates as they relate to the closing date of the transaction.  If you have more than one transaction with the same closing, the system will use the transaction number as the secondary field to sequentially calculate the Agents earned commissions for plans that are based on different levels._

 _**Commission Basis**_ 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-CommissionPlans/commissionplans2.png)

The **Commission Basis** determines how the commissions will be calculated based on the following calculation logic.

To initiate this functionality, go to Company Profile / System Defaults tab in the Additional System Settings section, ensure there is a checkmark in the appropriate box labelled "Enable Commission Basis".  You will need to exit and relaunch  Back Office for the new settings to initiate.

**Agent Portion**

*   This is our current Agent Potion logic which calculates the agent's Commission Basis  after Transaction Fee/MLS Fee, Other Fee(s) (before referral),  Referral, Other Fee(s) (after referral); Other Fee(s) (after split), before Manager Override – Deduction Type – Agent Portion, Withholding(s) 1,2,3 if applicable
*   Agent Portion Commission will equal Commission Basis (above), less Other Fee(s) after split, less Broker Portion Flat
*   Other Fees after split will calculate on the Commission Basis Calculation amount (above)
*   Broker Portion Commission will equal Broker Split Calculation less 100% of some off the top deductions; Not Applicable
*   Broker Commission will equal Broker Portion Commission + Broker Flat Commission

**Brokerage Portion**

*   On Brokerage Portion Gross less Transaction Fee/MLS Fee, less Other Fee(s) (before referral), less Referral, less Other Fee(s) (after referral)
*   Broker Commission Basis calculation will occur after MLS /Transaction Fee Fee, Other Fee(s) (before referral), Referral, Other Fee(s) (after referral); before Manager Override – Deduction Type – Broker Portion
*   Agent Portion Commission will equal Commission Basis (above), less Other Fee(s) after split, less Broker Portion Flat
*   Other Fees after split will calculate on the Commission Basis Calculation amount (above)
*   Broker Portion Commission will equal Broker Split Calculation less 100% of some off the top deductions; Not Applicable
*   Broker Commission will equal Broker Portion Commission + Broker Flat Commission

**Gross**

*   This logic will calculate the agent’s Portion and split calculation (i.e. 60% to agent 40 % to broker) before any off the top deductions
*   Agent Portion will equal Agent’s the % of the Gross commission less any fees deducted after split, and less  any Broker Flat fee if applicable.
*   Other Fees after split will calculate on the  % of the Gross Commission
*   Broker Portion will equal Broker Split Calculation less 100% of all off the top deductions of Transaction Fee, Other Fee(s) (before and after referral) and Referral Fee

**Gross Less MLS/Trans. Fee**

*   This logic will calculate the agent's Portion after MLS/ Transaction fee deduction, and before  any off the top deductions
*   Agent Portion will equal Commission Basis, less Other Fee(s) after split, less Broker Portion Flat if applicable
*   Other Fees after split will calculate on the Commission Basis Calculation amount (above)
*   Broker Portion Commission will equal Broker Split Calculation less 100% of some off the top deductions; Other Fee(s) (before and after referral) and Referral Fee

**Gross Less MLS/Trans. Fee and Deductions (Other Fees)**

*   This logic will calculate the agent's Commission Basis after all off the top deductions and before referral.
*   Agent Portion will equal Commission Basis (above), less Other Fee(s) after split, less Broker Portion Flat
*   Other Fees after split will calculate on the Commission Basis Calculation amount (above)
*   Broker Portion Commission will equal Broker Split Calculation less 100% of some off the top deductions;  Referral Fee, Other Fee(s) (after referral)

**Gross Less MLS/Trans. Fee, Deductions and Referral**

*   This logic will calculate the agent's Commission Basis after MLS /Transaction Fee, Other Fee(s) (before referral),  Referral and before Other Fee(s) (after referral)
*   Agent Portion Commission will equal Commission Basis (above), less Other Fee(s) after split, less Broker Portion Flat
*   Other Fees after split will calculate on the Commission Basis Calculation amount (above)
*   Broker Portion Commission will equal Broker Split Calculation less 100% of some off the top deductions;  Other Fee(s) (after referral)

 **Adjust Gross (Less all off the top Deductions)**

*   This is our current "Adjusted Gross" logic which calculates the agent's Commission Basis after MLS/ Transaction fee, Other Fee(s) (before referral),  Referral, Other Fee(s) (after referral)
*   Agent Portion Commission will equal Commission Basis (above), less Other Fee(s) after split, less Broker Portion Flat
*   Other Fees after split will calculate on the Commission Basis Calculation amount (above)
*   Broker Portion Commission will equal Broker Split Calculation less 100% of some off the top deductions; Not Applicable
*   Broker Commission will equal Broker Portion Commission + Broker Flat commission

**Sales Volume = Sales Price**

*   A few notes regarding this commission basis: the percentage or Broker Flat will calculate out on the adjusted gross and the volume aggregates on the sales price entered, if this is a dual agent transaction the agent gets credit for both sides or twice the sales price. **Please note, this Commission Basis will calculate the commission split using the sum of historical (previously closed transactions and/or Agent History entered) Sales Volume starting level/tier; it will not cross levels (prorate) mid-sales volume.**

**Sales Price**

*   Is a plan designed to allow the brokerage to have a flat fee deduction to the agent based on the sales price entered on a transaction. EX. Sales Price is 250,000 the agent commission is 100% with a flat fee deduction of 250.00 to the brokerage or per agreement between agent and brokerage. Sales Price is not cumulative, its a per transaction calculation.

**Gross Volume**

*   This plan is based on both the sales price and the agent GCI is then divided by ( this can be at user specific requirements) by the default of 2.5% bringing down the actual sales volume with the premise that the actual GCI of what the sales volume would have been if the full commission collected had been the industry standard of 3%  GCI.

**Additional Parameters** 

*   **AND/OR -** By selecting “AND”, the program will base commission calculations on the criteria entered.  For example, if the commission plan was 70/30 to 80,000 and 6 ends, once the Agent received 80,000 in gross commissioned sales and closed 6 ends, the system would automatically start calculations based on the next level of the commission plan.  By selecting “O”, the commission plan would use either the history or the number of ends.  For example, if you had a commission plan of 70/30 to 80,000 and 6 ends, the Agent would have to receive 80,000 in commissioned sales or have done 6 ends to move to the next level of the commission plan.
*   **End -** Commission plans can be based on ends as well as gross dollars.  This field is used the same way as the ‘Up to $’ field.  You can enter the number of ends the Agent must close before moving to the next level of the plan. In the End field, if applicable, enter the maximum number of ends that the Agent must sell before moving to the next level of the commission plan, otherwise, leave this field as ‘999.00’ If the plan is based on a 11.5 end calculation, you may enter it now.

Was this article helpful to you?

Was this article helpful to you?