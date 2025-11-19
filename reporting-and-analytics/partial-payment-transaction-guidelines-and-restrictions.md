
# Partial Payment Transaction Guidelines and Restrictions

The purpose of this article is to detail the guidelines and restrictions of Partial Payment Transactions.

*   Each commission amount received will be treated as an individual transaction, linked to a main transaction to ensure commission data integrity.
*   Each payment will be disbursed to all parties involved proportionately based on the percent of end, commission rules and commission plans associated with each payment, including Managers.
*   Commission plan(s) can be assigned to the Sales Associate on the fly or amounts can be overwritten.
*   Edits to Withholdings, Manager Overrides, Other Fees & MLS/Transaction Fees are supported.
*   Select reports will include all related transaction(s) and their detail collectively as a sum total and individually.
*   All partial payment transactions must be closed, processed and integrated before processing the main transactions closing.
*   Force Validation \- If the main transaction has been configured with Force Validation, this means that the sum all the partial payment transactions closed, processed and integrated **MUST EQUAL** the main transaction. Alternatively, if the main transaction is not configured with Force Validation then it is your responsibility to ensure that all partial payment transactions equal the total commission receivable and payable on the main transaction.
*   If the main transaction is voided, then all the partial payment transaction statuses will change to void. However, if there are any partial payment transactions that have already been closed, processed and integrated, the main transaction cannot be voided until the processed partial payment transaction has been reversed.
*   If the main transaction is closed, it must be reversed before any of its partial payment transactions can be reversed. Individual payments can then be voided and/or reversed on their own without affecting other related partial payment transaction(s).
*   A partial payment transaction does not support “Agent Advances”. If you try to add an “Agent Advance” is to the main transaction or partial payment transaction(s), you will receive warning that the agent advance cannot be assigned. Agent advances must be detached and/or reset to $0 and/or re-assigned, otherwise the transaction cannot be closed.
*   A partial payment transaction cannot be a main transaction to other partial payment transaction.
*   A partial payment transaction will inherit most values from the main transaction, including configuration on the Escrow panel of the Deposit tab; the escrow/trust deposits and interest calculations are excluded.
*   Please note that if any changes have been made to open partial payment transactions, other related partial payment transactions will not be automatically be recalculated, changes will be manual and configured by user.

_**For information on how to enter a Partial Payment Transaction, please review the links below depending which end of the transaction you represent.**_ 

[How to Enter a Selling End Partial Payment Transaction with an Escrow/Trust Deposit](https://constellation1.na3.teamsupport.com/knowledgeBase/13661569)

[How to Enter a Buying End Partial Payment Transaction](https://constellation1.na3.teamsupport.com/knowledgeBase/13661461)

Was this article helpful to you?

Was this article helpful to you?