---
title: Partial Payment Transactions | Constellation1 Customer Hub
---

# Partial Payment Transactions | Constellation1 Customer Hub

A Partial Payment Transaction is used when commission is collected and paid in installments such as a new construction/builder home or if the expected commission is not received in full.

**_New Construction/Builder Transaction_**

Typically, a new construction/builder transaction involves multiple payments of commission. See example below:

1.  A commission amount of $5000.00 when the agreement is firm.
2.  50% of the remaining commission may be paid when construction begins.
3.  50% of the remaining commission may be paid when the transaction is closed and registered.

_**Late or Non-Payments of Commission with Trust/Escrow Deposits**_

Many real estate governing bodies stipulate that commission is paid to all parties within ten (10) business days of the transactions close date.

If commission is not received by the Controlling Brokerage within the timeline, the Real Estate Brokerage must disburse any trust/escrow deposits proportionately between the selling and buying sides of the transaction. When the balance of commission is received, the Real Estate Brokerage would disburse the remaining commission proportionately.

###### **Partial Payment Transaction Guidelines and Restrictions:**

1.  Once a partial payment transaction has been created, it cannot be changed back to a regular transaction.  You will need to cancel all payments and the main transaction. 
2.  Each commission amount received will be treated as an individual transaction, linked to a main transaction to ensure commission data integrity.
3.  Each payment will be disbursed to all parties involved proportionately based on the allocation of percentages/amounts per side, commission rule and commission plans associated with each payment, including Bonus Overrides, Deductions, Non Commission Income, etc.
4.  Commission plan(s) can be assigned to the Agent on the fly or amounts can be overwritten.
5.  Edits to Deductions, Bonus Overrides and Non Commission Income are supported.
6.  Reports will include all Payments and their detail individually.
7.  All Payments must be closed before closing the main transaction. 
8.  **Force Validation on Commissions** – The main transaction is automatically configured with Force Validation on Commissions toggled ON, which means that the sum of all Payments **MUST EQUAL** the main transaction. If the main transaction is edited with Force Validation on Commissions toggle OFF, then it is your responsibility to ensure that all Payments equal the total commission receivable and payable on the main transaction, including all deductions, referrals, etc. 
9.  If the main transaction is cancelled, then all the Payments statuses will change to cancelled. However, if there are any Payments that have already been closed and processed, the main transaction cannot be cancelled until the Payment(s) have been reversed. For more information, please click here; [Cancelling a Partial Payment Transaction](https://constellation1.na3.teamsupport.com/knowledgeBase/15801127)
10.  If the main transaction is closed, it must be reversed before any of its Payments can be reversed. Individual Payments can then be cancelled or reversed on their own without affecting other related Payment(s).
11.  A Partial Payment Transaction cannot be a main transaction to other Partial Payment Transaction.
12.  The Payment will inherit most values from the main transaction, including configuration in the Additional Detail section of transaction's Commission tab. The transaction's Deposit card and its interest calculations are excluded.
13.  Please note that if any changes have been made to a pending Payment, the other Payments will NOT automatically recalculate. You will need to edit the values for each Payment accordingly. 

**_Scenario 1>New Construction/Builder or Buying Side Transaction_** 

1\. The transaction is added/imported the exact same as any other Buying Side transaction with the full commission expected including all the correct amounts to be disbursed to all applicable parties, see [Creating Transactions via Transactions Wizard](https://constellation1.na3.teamsupport.com/knowledgeBase/15356015) or [Adding a Transaction Via the Transaction Wizard (Video)](https://constellation1.na3.teamsupport.com/knowledgeBase/23826668) or [Manually Adding a Transaction](https://constellation1.na3.teamsupport.com/knowledgeBase/21273607) or [Manually adding a Transaction (Video).](https://constellation1.na3.teamsupport.com/knowledgeBase/22105084)

You may want to change the transaction type for reporting purposes.

_**Please note: The State/Province will auto-populate with the same information provided in the Company. For further information, please click here: [Company Profile Maintenance](https://constellation1.na3.teamsupport.com/knowledgeBase/16981163)**_

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c591f7ee-72f5-4456-9126-622617fa1c7b)

2\. On the Details tab of transaction, select Action = $ Create Partial Payment

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e48d7adf-ee45-4a0d-9a7f-3b3e416ea5b2)

3\. You will be presented with the following window, where you will enter the amount of the expected commission including the applicable date and Save. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/865ff784-5c02-4b8a-86d0-276e1b9f72ed)

4\. A new tab will display to the right of the transactions Commission tab; Payment 1, Payment 2, etc. and the Additional Detail section on the Commission tab will display a new toggle, Force Validation on Commissions. This means that the sum of all commission received and paid (including Bonus Overrides, Deductions, Non Commission Income, etc.) for all Payments must equal the main transaction.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/051449ea-8b68-4f98-84c1-e8d7440f14fd)

5\. You will create the remaining Payments as needed following points 2. and 3. above.

_**Please note that when subsequent Payments are created, the Remaining Commission Amount will provide you with the amount allocated for Payment 1, Payment 2, etc. until full commission from the main transaction has been allocated to a Payment.**_ 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/93f9190c-1381-47de-a0a1-fff71b42e402)

6\. Once all Payments have been created, you will see all the Payments for the transaction. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/78fc101e-17a5-4271-94de-4a690504e0af)

7\. The Transaction Landing page will display an arrow on the left and if selected, you will see all Payments, Commission Amounts and Close Dates. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f0b0fbb6-067a-49ad-b61d-4869902c157b)

8\. To close Payment 1, review the commission amounts as usual. Select Action = Close on the Payment 1, 2, 3, etc. tab only.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0f75bac0-0319-4f00-8eb6-8ca9d42bbe98)

9\. If integrating with QuickBooks®, all checks/cheques, deposits and journal entries will integrate as usual except that we will append A, B, C, etc. to the transaction number's memo so that you can differentiate Payment 1, 2, etc. Ex. Tran# 2023020A where A represents Payment 1. 

10\. Once the commission has been paid out in full, you can close the main transaction.  The Review Closing form will be blank. 

**Reminder: you cannot take the Agents Expense Amount when closing the main transaction as there is no commission left to pay. This step will change the status of the transaction from Pending to Closed ONLY.**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/77033407-79ae-4ecc-8d56-00371757cf98)

**_**Scenario 2>Late or Non-Payments of Commission with a Deposit Attached**_**

1\. The transaction is added/imported the exact same as any other Selling Side transaction with the full commission expected including all the correct amounts to be disbursed to all applicable parties, including a Deposit with any interest amounts, processing fees, etc. as usual; see [Creating Transactions via Transactions Wizard](https://constellation1.na3.teamsupport.com/knowledgeBase/15356015) or [Adding a Transaction Via the Transaction Wizard (Video)](https://constellation1.na3.teamsupport.com/knowledgeBase/23826668) or [Manually Adding a Transaction](https://constellation1.na3.teamsupport.com/knowledgeBase/21273607) or [Manually adding a Transaction (Video).](https://constellation1.na3.teamsupport.com/knowledgeBase/22105084)

2\. On the Details tab of transaction, select Action = $ Create Partial Payment

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/926b346c-ebb6-4fcb-8b09-dbab1b34d4d3)

3\. You will be presented with the following window, to enter the amount of commission you wish pay for the first installment of commission. The amount entered does not include tax, if applicable. Ensure you select a Close Date and Save.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/68075101-6e42-4fac-80d1-1b13a44b70ce)

4\. A new tab will display to the right of the transactions Commission tab; Payment 1, Payment 2, etc. and the Additional Detail section on the Commission tab will display a new toggle, Force Validation on Commissions. This means that the sum of all commission received and paid (including Bonus Overrides, Deductions, Non Commission Income, etc.) for all Payments must equal the initial transaction. **If any amounts/values for Payment 1 need to be adjusted, please ensure those are completed before creating more Payments.** 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/849d8fa5-b3de-42f1-9282-175d06d6e1cf)

5\. You will create the remaining Payments as needed following points 2., 3. and 4. above.

_**Please note that when additional Payments are created, the Remaining Commission Amount will display the remaining amount to allocate until the full commission from the main transaction has been allocated to a Payment.**_ 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6ee5de1c-67dd-4011-9d07-5c521563b919)

6\. Once all payments have been created, you will see all the Payments for the transaction. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/82c10d00-28fd-40fb-97e1-2fc5b6cd9207)

7\. The Transaction Landing page will display an arrow on the left and if selected, you will see all Payments, Commission Amounts and Close Dates.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e02ce6ba-5457-47d4-81c3-8684c800fb7a)

8\. Before closing Payment 1, you must disburse the amount of the deposit that will be used, payable to your own Company. This could be the full deposit or a portion of the deposit and should include tax if applicable.  For the step by step directions, please click here; [Disbursing Trust/Escrow Deposits](https://constellation1.na3.teamsupport.com/knowledgeBase/16238244)

The Payee will be your Company, select Payment 1 from the drop down and add a Comment if required. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ba6c080c-86f6-49d2-b188-89c63b13ba29)

Once saved, the Deposit screen will look comparable to below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6747722f-d3ee-40a9-aabe-6a0843c029c2)

9\. To close Payment 1, review the commission amounts as usual. Select Action = Close on the Payment tab only.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/b0b92264-3bd1-48d2-8b52-2af9b4c61624)

The deposit will display on the Review Closing form exactly as it would if this was not a Partial Payment Transaction.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8226699b-c7b7-47ee-b423-405b964ada3c)

10\. If integrating with QuickBooks®, all checks/cheques, deposits and journal entries will integrate as usual except that we will append A, B, C, etc. to the transaction number's memo so that you can differentiate Payment 1, 2, etc. Ex. Tran# 2023045A where A represents Payment 1. 

11.If you did not disburse the full amount of deposit, you must disburse as needed for each Payment. 

12\. Once all payments have been paid, you can close the main transaction.  The Review Closing form will only display interest amounts for integration if configured.  **Reminder: you cannot take the Agents Expense Amount when closing the main transaction as there is no commission left to pay. This step will change the status of the transaction from Pending to Closed ONLY.**