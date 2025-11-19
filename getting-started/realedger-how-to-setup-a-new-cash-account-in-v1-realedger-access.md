# REALedger - How to Setup a New Cash Account in v1 REALedger (Access)

The purpose of this article is to provide the steps to setup a new Cash Account in REALedger.

* Add a new GL code for the new cash account by navigating to GL>>Maintenance>>Chart of Accounts and click Add.
* Enter a unique five-digit GL Code that begins with “1".
* Enter unique Description.
* Select “1” from the Type dropdown.
* Select Current Assets from the SubType dropdown.
* Select “0” from the Profit Group dropdown.
* Select “C” from the Category dropdown.&#x20;
* Navigate to System>>Maintenance>>System G/L Posting Accounts, choose the new account from the GL code dropdown list for SetCode **CASHDFLT**. &#x20;
* In System>>Maintenance>>Last Used Transaction Numbers, edit the GL Code in Field Name column for xxxxx\_ACH and xxxxx\_Check with the new five-digit GL code account number.
* Enter the number prior to the first check number of your new check stock in the Last Number Used for ACH advice and check number.  WARNING:  When ordering check stock, be certain to order checks that start with a check number that is higher than the last check number used for you old account, to avoid duplication of check numbers within the program.
* Enter a new class for each module that will have a new cash account.  WARNING:  Do not alter an existing class, enter new classes that reference the new cash account.
  * To add a new sales class, navigate to Sales>>Maintenance>>Sale Class.&#x20;
  * To add a new accounts payable class, navigate to AP>>Maintenance>>Vendor Class.
  * To add a new payroll class, navigate to Payroll>>Maintenance>>Payroll Class.

If the new classes above will be the defaults for new transactions, navigate to System>>Maintenance>>Offices and select the new classes on the Class Defaults tab. &#x20;

* Edit all pending sales, unpaid A/P and unpaid payroll transactions to use the new classes, if you do not want to pay them from the old cash account.
* In Payroll>>Maintenance>>Employee Master File, edit the Default Payroll Class in each employee’s master file.
* In AP>>Maintenance>>Vendor Master File, edit the vendor records to use the new class.
* In GL>>Processing>>General Journal Entries, enter a journal entry to recognize the opening deposit to the new account.
* In Bank>>Maintenance>>Edit Monthly Bank Balances, select the new Cash Acct from the dropdown. Enter a Reconciliation Date of the last day of the month, prior to opening the account.
* Leave Reconciled Balance as zero and save. &#x20;

Was this article helpful to you?

Was this article helpful to you?
