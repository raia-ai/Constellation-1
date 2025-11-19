# Constellation1 Commissions July 2024 Release Notes v3.4

Production Release: July 2024 v3.4

## Release Summary

**Transaction Record Sheet:** Added option to send Transaction Record Sheet for an agent’s signature through eSign. \
**General Ledger:** Reorganized accounting types. \
**Master Templates:** Updated Disbursement Authorization and Agent Check Stub.\
**White Labeling:** Improved the company logo cropping tool. \
**Bug Fixes**

## Release Details

Added eSign Functionality to Transaction Record Sheet \
Administrators can now send the Transaction Record Sheet to agents for electronic signature through our eSign integration. \
To access the eSign feature, navigate to the commission tab within a transaction, go to the agent details section, and click the Transaction Record Sheet icon.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/07%20July/2024-Commissions-July-esignTRS1.jpg)

&#x20;A new toggle option has been added to the pop-up modal, enabling administrators to initiate an eSign session for the transaction record sheet.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/07%20July/2024-Commissions-July-esignTRS3.jpg)

&#x20;Once the eSign session is initiated, the transaction record sheet will appear on the Documents tab with a status of "Awaiting Signature". The status will then update to "Signed" after all parties have electronically signed the document.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/07%20July/2024-Commissions-July-esignTRS2a.jpg)

eSign sessions will be added to the billing report and include the name of the document(s) that was sent for signature. &#x20;

General Ledger\
The General Ledger has been reorganized to better align with the structure of accounting types, creating a more intuitive user experience.\
Related accounting types have been grouped together.&#x20;

Additionally, the accounting types of Long-Term Liability, Other Expense, and Other Income have been removed as part of this reorganization.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/07%20July/2024-Commissions-July-GL.jpg)

Master Templates\
**Disbursement Authorization** \
We’ve added new bookmarks for Commission Amount, Shared and Unshared income to the Disbursement Authorization master template. \
Commission Amount is the commission amount only.&#x20;

Total Commission is the sum of Commission Amount, Shared and Unshared Income.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/07%20July/2024-Commissions-July-CDAShared.jpg)

&#x20;**Note:** If the Side and Controlling Side are the same, the shared and unshared amounts for both the selling and buying sides will be included in the bookmarks.\
However, if the Controlling Side is different from the Transaction Side, we will only display the amount for the Transaction Side.

**Agent Check Stub**\
The agent check stub report now includes a detailed breakdown of the net commission, total tax, and the overall check total.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/07%20July/2024-Commissions-July-CheckStub.jpg)

White Labeling\
The cropping tool for uploading the company logo to the White Labeling section has been enhanced to improve usability. \
Users can now adjust and resize the crop, as well as drag and zoom the image in or out to modify the fit.

Bug Fixes

1\. We fixed an issue with the Transaction Import Sync Automation modal becoming unresponsive.&#x20;

Previously, when opening the Transaction Import Sync Automation modal the system would display a "Processing, Please Wait" message and then become unresponsive.&#x20;

Now, this issue has been resolved.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/07%20July/2024-Commissions-July-AutoSyncTransjpg.jpg)

2\. We fixed an issue with a transaction type not displaying correctly on the transaction landing page.&#x20;

Previously, when a new transaction type was added to the system then selected as the transaction type, the transaction would display the incorrect transaction type on the transaction landing page.&#x20;

Now, this issue has been resolved.
