
# Accounting - Positive Pay | Constellation1 Customer Hub

The purpose of this article is to define the purpose of Positive Pay and how to set it up.

Positive Pay is a system used by banks to detect fraud. Positive Pay works by matching the dollar amount of each check, the check number and the account number that is presented for payment against checks that have been previously authorized and issued by your company. 

To enable positive pay functionality, navigate to **GL > Setup > Chart of Accounts**

*   Locate the GL code associated with the cash account needed to export check information to the bank
*   Enter **PositivePay Check Code**
    *   Provided by bank
*   Enter **PositivePay Void Check Code**
    *   Provided by bank
*   Enter **PositivePay Export Type**, **Exclude** codes and voids or **Include** codes and voids
    *   Determined by bank

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/7bee136d-0e44-49a0-b8a8-ff9d1955076c) 

When you are ready to create the csv file to import to your bank, navigate to **Bank > Reports > PositivePay Export**.

*   Enter Starting Date and Ending Date
*   Click **Choose Folder** button
*   Navigate to folder setup for positive pay export files
*   Select **Cash Account** from dropdown
*   Check **Set as default** box, if applicable
*   Click **Export** button

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f3ec8264-a5b7-47eb-b7d6-31df23f30510) 

The following pop-up will appear, referencing the path to the csv file:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0582703a-4546-4a56-bff8-e3e7e3a61337) 

*   Click **OK**
*   Log into your bank to transmit/upload the file

The criterion for agent checks to be included in a positive pay export are as follows:

*   They must be from the selected cash account.
*   They must be paid in the date range selected.
*   They cannot be ACH payments.
*   They cannot be marked as deleted.
*   They cannot have a check number of zero.  

Was this article helpful to you?

Was this article helpful to you?