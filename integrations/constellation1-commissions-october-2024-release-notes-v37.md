
# Constellation1 Commissions October 2024 Release Notes v3.7

Production Release: October 15, 2024, v3.7

## Release Summary

**Transaction Checklists:** Enhanced functionality including automatically adding checklists to a transaction, review checklists email notification.   
**Review Transaction Checklists and Documents:** Improved workflow to review checklists, tasks and submitted documents.  
**Agent View of Checklists:** Limited ability for agents and team leaders to add required tasks to a transaction.   
**Import Transactions:** Reduced the time to sync listings with DotLoop and Skyslope.   
**Listing Import:** Updated fields used to validate listings when imported.   
**Agent Import:** Added real-time import sync and updated the user interface.    
**Reports:** Updated the Cash Flow Projection report.   
**Usability:** Improved page loads when applying filters to landing pages.   
**Agent View:** Removed agents and team leaders’ ability to edit the details card and franchise card.

## Release Details

Transaction Checklists

Last month, we introduced customizable checklists that can be applied to transactions. 

Now, we're enhancing this feature by allowing checklists to be automatically applied to a transaction based on predetermined criteria.  
In the System Settings, on the Checklist page, when creating a new checklist, we've added a new toggle to the Checklist Details card, titled "Auto-Attach to Transaction Based on Criteria." 

When enabled, administrators can create criteria for checklists. When the criteria is met, the checklist will automatically be added to any transaction that is added or imported into Commissions Online.

Criteria can be created using any combination of the following:

*   Transaction Type
*   Property Type
*   Side 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-AddTask.jpg)

Review Transaction Checklists, Tasks and Documents

We’ve enhanced the checklist, tasks and document review workflow for transaction tasks to provide an easy and intuitive user experience.  
When an agent submits a document for review, the administrator receives an email notification with a direct link. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-ReviewEmail1.jpg)  
_Example of email notification_

The link takes the administrator to the transaction's Checklist tab, where they can view tasks and review their documents and approve, reject or mark the document as not applicable. The agent will receive an email with the results of the review. 

Additionally, administrators can now easily monitor transactions for tasks and related documents that have been submitted for approval. 

A new "Submitted Approvals" section has been added to the My Workspace page, displaying transactions and the number of task that have been submitted and are awaiting review. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-Workspace-TaskReview.jpg)  
_My Workspace Page_

Clicking the address will open the Checklist page within the transaction where the administrator can review the tasks and the related documents that have been submitted.   
 **Note:** Transactions cannot be closed if there are any outstanding required tasks, and tasks cannot be added to closed or cancelled transactions.

Agent View of Tasks

We’ve removed the ability for agents and team leaders to add required tasks to a transaction. However they can still add Optional Tasks to their transactions.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-AgentViewTask.jpg)

  
Import Transactions 

We’ve improved the process of importing listings and transactions from DotLoop and Skyslope, now both will sync on an hourly basis instead of every three hours.

Clicking the Retrieve button will trigger a real-time sync with DotLoop or Skyslope, and update the transaction data.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-Workspace-TransImport.jpg)

Additionally, the import interface has been updated with several new features:

*   **Date Range:** Users can select the date range of transactions to be imported. The start date will default to the last import date. The end date will default to the current date, but both the start and end dates can be manually defined by the user.
*   **Office Filter:** An office filter option has been added, allowing users to select which office(s) the transactions should be imported from.
*   **Pagination:** Users can customize the number of transactions displayed per page, up to a maximum of 250. The system will remember this preferred setting.  
    
*   **Multi-Select:** Users can now select multiple transactions across multiple pages.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-Workspace-transImport2.jpg)

  
Listing Import 

We've updated the fields used to validate listings during the import process.   
Previously, we used a listing's MLS ID, primary street address, and postal code to identify a property in Commissions Online.   
Moving forward, we will now only use the BrokerID and SourceID to identify listings and either import new ones or update existing ones in the system.

Agent Import

The agent import interface has been updated for a more intuitive workflow. Field and button labels have been revised to provide a more accurate representation.  
Clicking the Import button will trigger an import of agent data even if the sync automation is enabled. 

  
Reports 

The Cash Flow Projection report has been updated and now includes a new Total Cash Column Calculation formatting field. This update has also been applied to the scheduled Cash Flow Projection Report as well.

The dropdown options are:

*   Company Income + Non-Company Deductions
*   Running Tally of Total Cash

The Total Cash column can be set to show either the sum of Company Income and Non-Company Deductions per row, or the cumulative running tally of that Total Cash value progressively over rows. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-CashFlowReport.png)

Usability

We’ve improved how pages load, providing a smoother, more responsive experience when users apply filters to landing pages.   
This update eliminates the previous bouncing effect and applies to the Transactions, Listings, Agents, Users, Contacts, and Offices pages.

  
Agent and Team Leader Views

We’ve removed access for agents and team leaders to edit the details on the Deposit card and the Franchise card, on the details tab of a transaction. These fields will be visible but grayed out in the Agent View. 

   
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/10%20October/2024-Commissions-Oct-AgentView.jpg)

_Agent View_