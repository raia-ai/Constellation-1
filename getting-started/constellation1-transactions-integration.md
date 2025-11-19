# Constellation1 Transactions Integration | Constellation1 Customer Hub

This article outlines the setup process between Commissions and Constellation1 Transactions accounts.&#x20;

Navigate to **Setup > Company Profile >** **Integration**&#x20;

* In the MLS/TMS Status To Import section select the statuses for import or Add/Delete ones as needed.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17950408)

* Once the preferred statuses selected close and relaunch the Commissions application for new configuration to take effect. &#x20;

_**Please note: Active = Listings and there is no logic to filter out "Expired" transactions, the Commissions application will import whatever transaction statuses are provided by Constellation1 Transactions.**_&#x20;

**Importing from Constellation1 Transactions**&#x20;

* Select **MLS/TMS Sync** on left sidebar&#x20;
* Modified Since date will display the date that you last performed the sync and reflects transactions modified as of that date.&#x20;
* Select **Sync**&#x20;
* A list of transactions will be presented for import; select as needed or Select All&#x20;
* Select **Import**&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17950409)

**A confirmation notification will appear confirming the import was successful. Note: Commissions will import Agents attached to a transaction as long as email addresses match in both applications.**&#x20;

* The sync occurs approximately every 30 minutes.

Below are the data to data fields synced based on Constellation1 Transactions API:&#x20;

* Address 1 \
  Address 2 \
  City \
  State \
  Zip Code \
  Property Type - all transactions will import as Transaction Type=S regardless of how "S" is described \
  MLS Number \
  List Price (Listing Price) \
  Sale Price (Sold Price) \
  Escrow/Closing No. = Escrow Number on the Escrow panel of Deposit tab of Transaction \
  Tx Type/Agent Represents = Transaction Side \
  Transaction Status = Status (open, closed or void) \
  Contract Acceptance Date = Effective Date \
  Estimated Closing Date = Closing Date (if Scheduled Date is not available, we will use Estimated Closing Date and if Estimated Closing Date is not available, we will use today's date) \
  Listing Date&#x20;
* **Transaction Resources** \
  Description (Resource Type) \
  First Name \
  Last Name \
  Company \
  Home Phone \
  Work Phone = Business Phone \
  Email&#x20;

Was this article helpful to you?

Was this article helpful to you?
