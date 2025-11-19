---
title: "Dotloop Integration"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/19166627"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Dotloop Integration | Constellation1 Customer Hub This article details the steps to configure and integrate Commissions Online with Dotloop, including"
long_description: "Dotloop Integration | Constellation1 Customer Hub This article details the steps to configure and integrate Commissions Online with Dotloop, including the fields that will be integrated.  On the left navigation bar select Transactions, and at the top right of the window select the Import button.  In the Transaction Office Mapping section, ensure you correctly map each office as needed and select Save Mapping.  Note: This only needs to be completed once unless you add more offices to your account"
---

# Dotloop Integration | Constellation1 Customer Hub

This article details the steps to configure and integrate Commissions Online with Dotloop, including the fields that will be integrated.

On the left navigation bar select **Transactions**, and at the top right of the window select the Import button. ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/34c4d2af-edda-427e-bd97-6300d94cf274) 

In the **Transaction Office Mapping** section, ensure you correctly map each office as needed and select Save Mapping.

**_Note: This only needs to be completed once unless you add more offices to your account._**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/18025030)

On the Import card, the **Last Import Date** will display at the top right and users must select at least one Transaction Status before selecting Retrieve button.

The **Back** button will return users to the Transactions landing page and the other buttons will be reviewed later in this article.  

If you want to import a specific transaction, you must enter the Transaction Address (or combination of letters in the address) before selecting Retrieve button.

Users can opt to import for a single Office, multiple Offices or all Offices. The default is all Offices. 

**Please note: Active = Listings and there is no logic to filter out "Expired" listings. The Commissions Online application will import whatever transaction statuses are provided by Dotloop except Archived and Done. Cancelled statuses will automatically change the status of the transaction in Commissions Online from Pending to Cancelled.**   

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f004d7d9-86c0-4570-b5f4-bf400a9eb3f6)

**Run Commission Calculation on Import**, mouse over the Information icon to see more detail on its use before making your selection.  Once toggled on/off, the setting will remain unchanged the next time you import. 

  ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9276df21-62e7-4983-96c1-a20b37e9fc85)

**Transaction Import Override**

All Data Fields includes all fields listed below.

Do Not Override will not override any transaction if selected.

Transaction Data Only - Excluding Commission includes fields that are not directly tied to the commission calculation as indicated when you hover over the information icon.

**Once the drop down is selected and user imports a transaction, the option will remain unchanged until user changes it and imports again.**  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d26c8538-20f9-4af5-836a-afc3450cb72e)

The **Added / Edited From** and **To** will display the previously selected Added / Edited From date and To with today's date, that you last retrieved transactions to import.

**Note:** The check boxes are color-coded and translate as follows:   
•    Blue – Not previously imported  
•    Orange – Previously imported   
•    Gray – Transaction with Cancelled status

You can sort the transactions available for import by Address, MLS Number, Close Date and Sale Price by clicking on the appropriate column header.

The **Import Group Selection** drop down options:  

**Select New Only** \- will place check marks beside ONLY your new transactions ready for import

**Select All** \- will select ALL transactions in list

**Deselect All** \- will deselect any selections made

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

_**Agents will only be included if their email in Dotloop is the same as the email in Constellation1 Commissions Online.**_ 

_**Dotloop syncs to the data hub every hour.**_ 

Transactions (all transactions will import as Sale type, unless the field in dotloop contains "Lease" or "Rental" and then the transaction type will be Lease or Rental)

MLS Number 

Address  
Address 2 City State Zip Code Contract Agreement Date (Offer Acceptance Date), if no date is entered in dotloop - the integration will auto-populate today's date  
Transaction Side (Buying, Selling or Both) Referral Name (first and last) Referral Flat Amount OR Percentage Sale Price Closing Date (Close Date)Commission Amount Co-Brokerage Seller and Buyer Contacts Lease Transactions; 1 Landlord, 2 Tenants and Leased Price 

Note: If there are two transactions with the same MLS number (one representing the Selling side and the other representing the Buying side), Commissions first maps to the MLS number for a previously imported transaction. If there are two new transactions with same MLS number, only one transaction will be imported as new transaction. The second new transaction will update the first one because of same MLS number.