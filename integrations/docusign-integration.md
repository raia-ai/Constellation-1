---
title: "DocuSign Integration"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/19338960"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "DocuSign Integration | Constellation1 Customer Hub This article details the steps to configure and integrate Commissions Online with DocuSign, includi"
long_description: "DocuSign Integration | Constellation1 Customer Hub This article details the steps to configure and integrate Commissions Online with DocuSign, including the fields that will be integrated.  On the left navigation bar select Transactions, and at the top right of the window select the Import button. In the Transaction Office Mapping section, ensure you correctly map each office as needed and select Save Mapping.  Note: This only needs to be completed once unless you add more offices to your accoun"
---

# DocuSign Integration | Constellation1 Customer Hub

This article details the steps to configure and integrate Commissions Online with DocuSign, including the fields that will be integrated.

On the left navigation bar select **Transactions**, and at the top right of the window select the Import button.![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/34c4d2af-edda-427e-bd97-6300d94cf274)

In the **Transaction Office Mapping** section, ensure you correctly map each office as needed and select Save Mapping.

**_Note: This only needs to be completed once unless you add more offices to your account._**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/18025030)On the Import card, the **Last Import Date** will display at the top right and users must select at least one Transaction Status before selecting Retrieve button.

The **Back** button will return users to the Transactions landing page and the other buttons will be reviewed later in this article.  

If you want to import a specific transaction, you must enter the Transaction Address (or combination of letters in the address) before selecting Retrieve button.

Users can opt to import for a single Office, multiple Offices or all Offices. The default is all Offices. 

DocuSign supports the following statuses:

1\. Active

2\. Sold

3\. Leased

4\. Closed

5\. Under Contract

6\. Pending

7\. Canceled

Active statuses will be imported via Listings. 

All other statuses will be imported as Pending Transactions regardless of the DocuSign statuses noted above.

If the "Status" field is empty, it will be mapped to "ACTIVE" by default and imported via Listings.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f9de4d38-0faa-4cdc-b68f-3469bd980ae0)

**Run Commission Calculation on Import**, mouse over the Information icon to see more detail on its use before making your selection.  Once toggled on/off, the setting will remain unchanged the next time you import. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a780a7f1-9a5e-47a6-9a05-56f374868df7)

**Transaction Import Override**

All Data Fields includes all fields listed below.

Do Not Override will not override any transaction if selected.

Transaction Data Only - Excluding Commission includes fields that are not directly tied to the commission calculation as indicated when you hover over the Information icon.

**Once the drop down is selected and user imports a transaction, the option will remain unchanged until user changes it and imports again.** 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d26c8538-20f9-4af5-836a-afc3450cb72e)

The **Added / Edited From** and **To** will display the previously selected Added / Edited From date and To with today's date, that you last retrieved transactions to import.

**Note:** The check boxes are color-coded and translate as follows:   
•    Blue – Not previously imported  
•    Orange – Previously imported   
•    Gray – Transaction with Cancelled status

You can sort the transactions available for import by Address, MLS Number, Close Date and Sale Price by clicking on the appropriate column header.

The **Import Group Selection** drop down options:  

**Select New Only** \- will place check marks beside ONLY your new transactions ready for import

**Select All** \- will select ALL transactions in list

**Deselect All** \- will deselect any selections made

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5302508c-5598-4eca-a8a5-5b3172eb97af)

Once you have selected the transaction(s) you wish to Import, select the Import button.

Commissions Online will import the selected transaction(s) and a pop-up screen will appear confirming the transaction(s) has/have been imported and the transaction(s) will display in your transaction list.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17640274)

**Sync Automation button**

Users have the option to schedule the transactions import. 

Imports can be scheduled based on:  
•    Frequency (Manual, Daily, Weekly)  
•    Time of Sync   
•    Day of Sync   
•    Transaction Status 

Daily includes listings and transactions within the previous 24 hour period.  
Weekly includes listings and transactions within the previous 7 days.  
Manual includes listings and transactions since the last sync date. 

_**Agents will only be included if their email in DocuSign is the same as the email in Constellation1 Commissions Online.**_

_**DocuSign syncs to the data hub approximately every 3 hours.**_ 

Below are the data to date fields synched based on DocuSign's API:  

MLS Number  
Listing Type  
Status  
Address  
City  
State/Province  
Zip/Postal Code  
Price  
Listing Date  
Sold Date (Contract Date)  
Transaction Side (side represented; Buying, Selling or Dual Ended)  
Referral Name (first and last)  
Referral Flat Amount OR Percentage  
Sale Price  
Sold Date (Contract Date)  
Property Type  
Closing Date  
Sale Commission  
Co-Brokerage  
Seller and Buyer Contact  
Lease Transactions: 1 Landlord, 2 Tenants and Leased Price

The transaction import mapping logic for New / Existing transaction is:

**1\. If MLS Number exists for the MLS transaction**

*   It will try to match the MLS number with the existing transactions in the database. If same MLS number is found. Then check box will be marked as Orange (Already Imported).
*   If no transaction is found with the MLS number, then it will try to match the External Source Id with the existing transaction in the database. If same External Source Id is found, then check box will be marked as Orange (Already Imported)
*   If no transaction is found with the External Source Id, then this MLS transaction will be marked as Blue (New Transaction).

**2\. If MLS Number DOES NOT exist for the MLS transaction**

*   It will try to match the External Source Id with the existing transaction in the database. If same External Source Id is found, then check box will be marked as Orange (Already Imported)
*   If no transaction is found with the External Source Id, then this MLS transaction will be marked as Blue (New Transaction).

_**This logic will be applied whenever user try to retrieve the transaction from Listing Hub, regardless if they have imported previously or not.**_

_**External Source ID = a unique ID that is assigned by the TMS Integration for a transaction.**_