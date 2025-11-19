---
title: Constellation1 Commissions March 2024 Release Notes v3.0
---

# Constellation1 Commissions March 2024 Release Notes v3.0

Production Release: April 2, 2024, v3.0 

## Release Summary 

**Enterprise Insights:** Added calendar mode to dashboard charts.   
**Accounting Sync Closings:** Mark transactions as posted without syncing them to accounting.   
**New! Custom Fields:** Create and manage custom fields on agent accounts.   
**Contact Information:** Added second phone to Agent and Contact information.  
**Represented By dropdown:** Added address of contacts listed.   
**Legal Description:** Special characters can now be included in this field.   
**Agent Advance:** Added ability to track and document advance payments from a third party to agents.   
**eSignature Integration:** Added warning message when changing company email address.   
**Reflex API:** Now available to Berkshire Hathaway HomeServices brokerages.   
**Re/Max Agent Franchise ID Validation:** Inactive agents are excluded from the ID validation process.  
**Sync To Accounting:** This now defaults to off when there is no accounting system integration.   
**Bug Fixes**

## Release Details  

Enterprise Insights   
The Enterprise Insights dashboard now has a Calendar Year mode for the Annual Production chart that lets users easily compare year-over-year closings.   
When selected, the chart displays the current year's production data alongside the previous year's data for an at-a-glance view of year-over-year trends.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-InsightsCalendar.jpg)

For a more consistent and intuitive user interface, we have relocated the Date Filter for the dashboard tiles into the box that contains the tiles themselves.

Accounting Sync Closings   
We’ve added the ability to mark a transaction as Posted when sync’ing transactions to the accounting program.   
In the Accounting section, under Sync Closings, users have the option to select transactions and mark them as Posted. Transactions marked as posted will not be posted to the accounting system.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-MarkAsPosted.jpg)

New! Custom Fields   
Custom fields can now be created and included in agent records. In the Advanced Settings We’ve added a new tab titled Custom Fields. Users can add text boxes or dropdown lists with custom labels. This allows agent records to be customized with additional fields as needed.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-CustomFieldsAdmin.jpg)

  
A new section for the Custom Fields has been added to the Agent Details page to display the custom fields.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-CustomFieldsAgent.jpg)

  
   
Custom field data can be included in custom reports. They will appear in the Report Fields list labeled with "Agent", the custom name, and marked with an asterisk for easy identification.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-CustomFieldsReports.jpg)

Additional Contact Information  
We’ve updated the Agent and Contact record details by adding a second phone number field.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-AgentPhone.jpg)

The added contact information is available in custom reports and master templates that include phone numbers.   
In the custom reports, the new fields are labeled "Agent Phone 2" and "Contact Phone 2".

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-ReportsAgentPhone.jpg)

Added Address to Transaction Contacts  
We’ve updated the Represented By dropdown in a transaction contact list to include the address of the contact when the address is available.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-ContactAdress.jpg)

Special Characters in Legal Description   
We’ve updated how special characters are handled in the Legal Description field of a transaction.  
Special characters added to the Legal Description field will now display correctly on letters, without error.   
Examples of special characters are, $, @, #, %, &. 

Agent Advance Paid by Third Party  
We have implemented a new “Third Party Advance” feature that allows agents to receive an advance from a third party, on their commission and can be remitted directly. Advances will be documented in the transaction details, disbursement authorization and on the general ledger.   
“Third Party Advance” has been added to transactions, under the agents’ commission details. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-AgentAdvance1.jpg)

  
 “Third Party Advance” has been added to the master Disbursement Authorization form. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-AgentAdvance.jpg)

“Third Party Advance” has also been added to the general ledger.  
 

eSign Integration   
The eSignature integration has been updated to improve the user experience and intuitiveness.   
If a user's company email address is changed, they will receive a prompt about this change when starting a new eSign session.   
The prompt allows the user to confirm and update the email address in eSign before continuing to create the session.   
Alternatively, they can cancel and revert the company email back to the original address configured prior to eSign integration. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/04%20April/2024-Commissions-March-eSignMessagiing.jpg)

  
 We’ve also removed the ability for agents to view and download signed documents and certificate of authenticity. 

Reflex API  
Reflex, a subscription service is now available to Berkshire Hathaway HomeServices brokerages. It enables a connection between Commissions Online and the Berkshire Hathaway HomeServices reporting system.   
This integration allows brokers to seamlessly pass transaction and agent data between the two platforms using the API access, while remaining compliant with Berkshire Hathaway HomeServices brokerages data format for easy reporting.   
For more information, contact your Constellation1 representative. 

Re/Max Agent Franchise ID Validation  
We’ve updated the logic used to validate the Agent Franchise ID for Re/Max agents. Commissions Online will now only validate IDs for active agents; inactive agents will be excluded from the validation process when generating franchise reports.  

Sync to Accounting System  
By default, Sync to Accounting System is now turned off for deposits and disbursements when there is no accounting system integrated with Commissions Online.

Custom Reports   
Custom reports have been updated so that relevant contact fields are displayed based on the fields included in the report.   
For example, if agent information is added to a report, contact fields will be hidden and unavailable. Similarly, if contact information is in a report, agent fields will be hidden. 

Custom Reports – Team Leaders and Agents  
Custom reports for teams and agents have been updated to display only the contacts linked to that particular team or agent.

Bug Fixes  
1\. We fixed an issue with the Trust Report not displaying all relevant listings when the Exclude Zero Amount is selected.   
Previously, when the Exclude Zero Dollar Amount was selected, some listings with non-zero-dollar amounts were not included in the report.   
Now, qualified listings with non-zero-dollar amounts will be shown on this report. 

2\. We fixed an issue with the tax calculation on deductions  
Previously, the tax was not being calculated correctly when deductions were included in a transaction.   
Now, transactions with deductions will calculate the tax correctly.