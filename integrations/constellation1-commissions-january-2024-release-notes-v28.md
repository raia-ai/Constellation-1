
# Constellation1 Commissions January 2024 Release Notes v2.8

Production Release: January 22, 2024 v2.8 

## Release Summary

**New! eSignature Integration:** Easily connect to eSignature to send documents for signatures.   
**New! Single Sign On:** Option to add SSO ability.   
**Canadian T4A Form:** Updated T4A tax form for 2023.  
**Exclude Capped Deductions:** Added new option to transactions.   
**Dashboard Office Filter:** Filter data on dashboard by office.   
**Dashboard Widgets:** Added Tooltip to show unrounded dollar values.  
**Statement Delivery:** Added option to send Transaction Record Sheet.   
**Transaction Deposits Table:** Updated sort order of date.   
**Transaction Import:** Added filter for address as import option.   
**Contact Types:** Updated workflow when changing contact types.   
**Master Template:** Updated letter template for Internal Agent and Cooperating Agent.   
**Reports:** Added new filter options.   
**Bug Fixes**

## Release Details

New! eSignature Integration

We are excited to announce the integration of eSignature capabilities. Users can now utilize eSignature to send Disbursement Authorizations for signatures directly from transactions.

Within a transaction, on the Commission page, click the Disbursement Authorization icon. A new toggle has been added to enable sending the document to eSign for authorization.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2024-Commissions-Jan-esign-form.jpg)

   
When enabled, the user can select contacts who are involved in the transaction to sign the Disbursement Authorization electronically.

The selected recipients will receive an email granting access to review and sign the document. Once signed, the document will return to the transaction and appear on the Documents page with a Signed status.

eSignature is not enabled by default. Please contact your Constellation1 representative for details. 

New! Added SSO Option

We’ve added the capability to configure Single Sign-On (SSO) in the Advanced Settings, enabling companies to integrate single sign-on with third-party applications.

When SSO is enabled, a section for configuring third-party integration will appear in Advanced Settings.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2024-Commissions-Jan-QnetSSO.jpg)

  
When enabled, users can enter the Identity Provider Metadata URL that links to the third-party service, that uses the SAML 2.0 protocol.   
Then generate the Default Relay State key that will be added to the third-party service.

SSO is a licensed service, please contact your constellation1 representative for details. 

Canadian T4A Tax Form

We’ve updated the Canadian tax form T4A to comply with the 2023 tax regulations. 

Option to Exclude Capped Deductions

We’ve added the option "Exclude Capped Deductions" to the Advanced Settings to determine how deductions are applied in a transaction.  
When "Exclude Capped Deductions" is enabled, deductions will be applied to the capped deduction amount regardless of the "Exclude from Commission Tier" setting. The "Exclude Capped Deductions" will override the Exclude from Commission Tier setting.

Deductions will not be included in the commission history. 

The Exclude Capped Deductions option is disabled by default and can be enabled in the Transaction Settings of the Advanced Settings. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-Capped%20DeductionsSetting2.jpg)

Dashboard Office Filter

A new Office filter dropdown has been added to the dashboard's Advanced Filters, allowing users to view data for a specific office.   
Selecting an office from this list will filter the dashboard to only show data for that office.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-DashboardOffices.jpg)

Dashboard Widget Dollar Values 

We’ve updated the behavior of the available chart data on the dashboard.   
Now, when the user hovers their cursor over a data point on a dashboard chart, a tooltip will display the actual, unrounded dollar value. Now, this includes all dollar amounts displayed on the dashboard. 

  
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-DashboardMouseover.jpg)

Transaction Record Sheet Statement Delivery

The Transaction Record Sheet can now be sent directly from a transaction. This document has been added to the Documents dropdown menu on the Statement Delivery page for Pending transactions.

This new functionality is similar to the existing capabilities in Commissions Desktop, also known as BOC.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-StatementDelivery.jpg)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2024-Commissions-Jan-TransRecordSheet.jpg)

 Updated Transaction Deposit Table

The Deposits table within a transaction now sorts in ascending order by date, rather than by the date the deposit was entered.   
This change makes the sorting of the Deposits table consistent with the Trust Reports.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-DepositTable.jpg)

Transaction Import Filters

The Transaction Import page has been updated to now include a Transaction Address filter option, that allows users to quickly find and import transactions. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2024-Commissions-Jan-TransImport.jpg)

Contact Type Landlord and Tenant

We recently added Landlord and Tenant as contact types. Previously, users had to delete and re-add the contact to the transaction to change their type.   
Now, users can change the contact type in a transaction without having to delete and re-add them. This applies to contacts originally added using the Transaction Wizard.

Updated Master Templates

**Selling Broker and Buying Broker**   
The master templates for Selling Broker and Buying Broker now include two new bookmarks for adding the Internal Agent and Cooperating Agent information.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-Template.jpg)

_Excerpt from the Buying Broker letter_

**Sellers Attorney Letter**

The Sellers Attorney letter master template, has been revised to subtract the amount being held in trust for the seller by the cooperating brokerage.

Specifically, the \[Deposit in Trust\] calculation now subtracts the Sale Price, Commission, and G.S.T. to determine the amount in trust.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-DepInTrust.jpg)

Reports

**Transaction Commission Rule**   
A New report field titled Commission Rule has been added to Custom Reports.   
When added, this report field will include the name of the commission rule applied to each transaction, on the report. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-CommissionRule.jpg)

**Partial Payment Information**  
Custom reports now have a Partial Payments filter field in the Advanced Filters options.   
Users can filter reports to show Main Transactions, Partial Payment transactions, or both.   
An information icon explains how the Partial Payment filter works.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-PartialPaymentFilter.jpg)

**Include Withholding Type**  
The Company Profit Deductions report now includes a dropdown box under Advanced Filters that allows users to either include or exclude the withholding type on the report.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2023-Commissions-Jan-WitholdingType.jpg)

Bug Fixes  
1\. We fixed an issue that prevented flat amount commission plans from calculating and displaying the correct amounts on the Agent Commission Summary Table.

Previously, flat amount commission plans were not calculating and displaying the correct amount on the Agents Commission Summary table.

Now, this issue has been resolved. 

2\. We fixed an error when selecting Close date on the commissions page of a transaction and not allowing the commission to split between the agent and the company.

Previously, when a user selected Close on a transaction and the commission rules cross multiple tiers, the system was not calculating the commission split.

Now, this issue has been resolved. 

3\. We fixed an issue with manually assigning a transaction number when converting listings into a transaction. 

Previously, when converting a listing into a transaction while the transaction wizard was turned off, the system would not save the manually entered transaction number.

Now, this issue has been resolved. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/01%20January/2024-Commissions-Jan-CustomTransNumber.png)

4\. We fixed an issue that caused the Agent Check Stub report for agents working in a team, to display the incorrect amount needed for the agent to reach the next tier. 

Previously, when agents are working in a team the Agent Check Stub report did not show the correct amount needed to reach the next tier.

Now, we’ve updated the report logic to include the commission amounts of all agents in the team for the transaction.