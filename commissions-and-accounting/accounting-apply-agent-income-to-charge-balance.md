---
title: Accounting - Apply Agent Income to Charge Balance
---

# Accounting - Apply Agent Income to Charge Balance

The purpose of this article is to provide a workaround for instances when an agent would rather not receive an AP check for income related activity, and instead would like the amount to be applied to their agent charge balance.  

In most instances, if an agent needs to be paid out of the AP module for referrals or other types of income, the payment that is issued to them is 1099able and the **Count for 1099** box is checked on the AP bill.  A check is then issued to them, that they take to the bank and cash and the payment is added to their 1099 balance for the year.  There are, however, instances when an agent would rather not receive the check and would like instead to have the amount applied to their agent charge balance.  In this instance, you may think that issuing the agent a credit against their agent charge balance will account for this, however, issuing an agent credit has no affect on their 1099.  So, rather than trying to remember to edit their 1099 value at year end, there is a better way to track this, so manual edits to their 1099s are not necessary at yearend.   

In the above scenario, there are three things that need to happen:

1.  Agent needs to be 1099'd on the income generated, even though they are not receiving a check

2.  The amount needs to be applied to their agent charge balance

3.  The cash account should not be affected in any way

To accomplish this, navigate to **AP > Processing > Bills** and click on the **Manual** radio button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0808d8dc-34b2-48cc-82e2-06154730f609)

*   Click **Add**
*   Select the agent from the **Vendor** dropdown or click on the green plus sign to add the agent as a new vendor
    *   Be certain to check the **Print 1099?** box and select the correct **1099 Form**, as advised by your CPA. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6d3b4616-12df-4d99-88f6-487535feb01d)

*   Complete the manual bill record as follows and **Save**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/3c249d7f-e283-437f-a980-c5f4022bd591)

Next, enter an agent payment by navigating to **Bank > Processing > Non-Commission Deposits**.

*   Click **Add**
*   Select the same, cash account as referenced in the manual bill, from the **Cash Acct** dropdown
*   **Deposit Date** will default to the **Processing Date,** but can be edited
*   Enter **Amount** of the manual bill, previously created
*   Check the **Agent Deposit?** box and select the **Agent** from the dropdown list
*   Enter the **Amount** in the **Credit Distribution Entries** section
*   Click **Apply Payment**

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/391752ae-05fe-487c-bc7e-3466943bc3c5)

*   Click **Auto-Apply** or manually select which **Charge #s** to apply the payment to, and enter those values in the **Payment** column 
*   Click **OK**

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f70ae92a-04d1-4efe-973d-0f6167f6ff3c)

*   Click **Save**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/821ad726-8549-4097-942b-01fe4cea773b)

What happens in the GL:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/7efdc6de-e9b1-4c83-a35b-b3d509531349)

Cash activity above nets to zero and an agent payment record, as seen below, has been created for the agent, reducing their agent charge balance.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6cfb373c-50d2-48ba-8055-6c80c5d4e9f9)

Also, 1099 activity is reflected on the Agent 1099 Earnings for the calendar year:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/01d676dd-fa5e-4793-af66-670d769e52cd)