---
title: Constellation1 Commissions January 2025 Release Notes v4.0
---

# Constellation1 Commissions January 2025 Release Notes v4.0

Production Release: January 13, 2025, v4.0

## Release Summary 

**Checklists, Tasks and Forms:** Forms can now be uploaded and attached to tasks.   
**Task Dependencies:** Organize tasks to be completed in a specific order.  
**Optional Tasks:** Removed optional tasks from the system.   
**Transaction Module:** Added more options to sort transactions.   
**Transaction Closing Wizard:** Updated the Process Date on the report preview.   
**General Ledger:** Removed reference to accounting systems when accounting is not integrated with Commissions Online.   
**Single Sign-On:** Added OpenID Connect as Single Sign-On option.   
**Reports:** Removed report parameters from the report URL.  
**Bug Fixes  
**

## Release Details

Checklists, Tasks and Forms  
We're pleased to announce several updates to the Checklist and Tasks features. Companies now have the options to attach pre-uploaded forms directly to tasks. 

Upon request and dependent on your company providing the forms, Constellation1 will upload the forms and map the form fields to data within Commissions Online.

When enabled, a new Forms tab will be added to the Checklists module, displaying the uploaded forms. Administrators can then create or edit tasks and attach a form as needed.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-Forms.png)

On the Tasks page, enable the “Attach Form” option and then select the desired form from the dropdown menu.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-Forms-Tasks.png)

eSignature integration with forms is coming soon. 

  
Task Dependency  
Administrators now have the option to organize tasks into a specific order (or stages) and establish dependencies between them. 

When creating or editing a checklist, they can “Enable Stage Dependencies". When enabled an order number will display next to each task, the administrator can then set the sequence of tasks within the checklist.  

Tasks must then be completed in the designated order before the agent or team leader can access the next one, helping agents to stay on task while working through a transaction. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-TaskDependancy.png)

Optional Tasks  
Optional tasks have been removed from the system as they added confusion and were unnecessary.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-OptionalTasks.png)

  
Transactions Module  
We’ve updated the Transaction module to allow users the ability to sort transactions by Transaction Type and Property Type. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-TransSort.png)

Close Transaction   
The Process Date has been added to the Review Closing Report presented in the Closing Wizard and on the finalized Closing Report.

Also, the verbiage on the report has been updated from “Processed Date” to “Process Date”.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-ProcessDate.png)

  
Single Sign-On; Added OpenID Connect   
We now offer OpenID Connect (OIDC) as a Single Sign-On (SSO) option. 

This SSO feature is available upon request. For optimal OIDC configuration and implementation, we recommend working closely with our team.  

Please contact your Commissions Online representative for more details. 

  
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-OpenID.png)

  
Once this feature is configured, an SSO link will appear on the login page, allowing users to click a button, be validated, and then logged into Commissions Online.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-OpenIDSSOLoginPage.png)  
 

  
General Ledger   
When mapping accounts in the General Ledger, we've removed references to 'creating a matching account' in an accounting system, when an accounting program is not integrated with Commissions Online. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-GL.png)  
_General Ledger_

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-Accounting.png)  
_Add Constellation1 Account popup modal_ 

  
Reports  
The reports URL has been updated to remove the parameters of the report that were previously displayed, including the CompanyID, AgentIDs, TransactionIDs, EnterpriseInfoID, and other related details. 

This update improves the overall security of the system.

Bug Fixes 

1\. We fixed an issue with adding new deductions to a commission plan when using the Commissions Wizard. 

Previously, when the Commissions Wizard was enabled and the user created a new deduction, then tried to add that deduction to a commission plan, the deduction was not available in the dropdown menu. 

Now, this issue has been resolved. 

2\. We fixed an issue with the Active/Inactive filter not working in the Commissions module.

Previously, in the Commissions module, the Active/Inactive filter was returning both active and inactive commission plans and deductions.

Now, this issue has been resolved. Setting the filter to either active or inactive will return results that match the setting.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-InactiveBug.png)

3\. We fixed an issue with the option to “Apply Bonus Cap” being enabled when adding a bonus override to an agent.

Previously, when a bonus override was added to an agent the “Apply Bonus Cap” was unintentionally being enabled.

Now, this issue has been resolved. When adding a bonus override and leaving the “Apply Bonus Cap” disabled, it will remain disabled when saving the bonus override. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2025/01%20January/2025-Commissions-Jan-BonusOverride.png)

4\. We fixed an issue with the agent Listings module erroring.

Previously, when logged into Commissions Online as an agent then navigating to the Listings module, the system would show an error.

Now, this issue has been resolved. Agents are able to access their listings as expected.  

5\. We fixed an issue with a search bar showing when adding a commission rule. 

Previously, in the Commissions module, under Commission Rules, there was a search bar showing on the page to add a rule.

Now, this issue has been resolved. The unnecessary search bar has been removed. 

6\. We fixed an issue with the Agent Production Detail report generating an error. 

Previously, when a user would run the Agent Production Detail report and select any transaction type, it would cause the report to error.

Now, this issue has been resolved. The Agent Production Detail report with transaction types selected, will return the report as expected. 

 7. We fixed an issue with the Transaction Record Sheet not showing the transaction's condition name. 

Previously, when a condition was added to a transaction, the name of the condition did not appear on the Transaction Record Sheet. 

Now, this issue has been resolved. Condition names now show on the Transaction Record Sheet regardless if they have been met or not. 

8\. We fixed an issue where users received an incorrect warning message related to the close date when completing a transaction. 

Previously, when closing a transaction, users would receive a warning message stating the close date was greater than the process date, even when the dates were accurate. 

Now, this issue has been resolved, and users will no longer encounter this warning message when the close date and process date are valid.