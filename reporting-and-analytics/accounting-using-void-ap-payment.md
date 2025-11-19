---
title: Accounting - Using Void AP Payment
---

# Accounting - Using Void AP Payment

The purpose of this article is to review the process for voiding AP payments and the effect this has on financial data. 

**Before voiding an AP payment, it is important to have the processing date set to the day you would like the voided payment record to accrue for financial reporting** (as seen in our article here: [Accounting - How to Change the Processing Date | Constellation1 Customer Hub)](https://constellation1.na3.teamsupport.com/knowledgeBase/16221922) . Do you want the void to accrue in the current financial period or a historical financial period?  More times than not, you will want to accrue the void in the current financial period, so you do not change the financial reporting from previous periods. This becomes very important when the payment you wish to void is from the previous calendar year.  If you date the void in the previous calendar year, this will affect the vendor’s 1099, from the previous calendar year, and alter financial data for the year.  Note: You may only void a check that has not cleared the bank.  

To demonstrate how the GL is affected when entering an AP bill, paying the bill, and voiding the payment, see below:

An AP bill was entered with an **Invoice Date** of 9/22/2023.  The **“Invoice Date”** is equivalent to the accrual date.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/afe295f8-7f16-45cb-bb13-92eabc8c656e)  

Effect on GL:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/b9539d9d-e7f9-45c2-8221-78eeb28ae502)  

On 9/26/2023 the bill was paid:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/67d202ab-9729-4060-9b8f-0aed2db8351e)  

Effect on GL:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/7f326a53-2658-4aad-98d5-9b85d1304cff)  

On 10/31/2023, a decision was made to void the payment.

To void the payment, go to **AP>>Processing>>Void AP Payment**.

*   Select the **Check/ACH#** from the left pane.
*   Click the **Void** button.   

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/94913a59-10c7-4a32-b7c5-60e82e3c4275)  

When you click the **Void** button, and click **Yes**, you will receive the following message:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e81793e6-4799-4c2d-a087-0e8f617e67ac)  

After voiding, a negative payment record is created:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/2fd8fd2e-cce0-43a4-bbbc-6ba26aafb781)  

Effect on GL:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5b536573-185c-40be-ac4a-ef8706417e27)  

After the payment is voided, the original bill returns to the **Unpaid** view in **AP>>Processing>>Bills**:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/2a1918f9-0443-407b-824e-0ebed3d3e703)  

At this point, you can do one of the following:

*   Repay the bill.
*   Click the **Reverse Bill...** button, which will create a credit and apply it to the bill automatically.   
    *   Note the **Delete** button is not enabled because the **Invoice Date**, in this example, is from a previous calendar month.  If you would like to delete the bill, and you have never paid the bill previously, then you can **Edit** the bill and change the **Invoice Date** to a date in the current month, if the bill has not already been posted.  Keep in mind, if you do this, then the historical GL activity will be altered from the date of the original bill forward. 
*   Create a manual credit and apply it to the unpaid bill manually. 
    *   Note, by creating a manual credit, you can date the credit for any period you wish.  Keep in mind, if you back date the credit you will alter historical GL activity.   

 When selecting the **Reverse Bill** option, you will receive the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/27e8e5da-e74d-4991-9b1f-30824cc8ff04)  

The following is the credit record that was created and applied to the unpaid bill:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/522adc22-a157-4e32-9cd3-608c345234c3)