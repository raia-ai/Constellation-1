---
title: "Constellation1 Commissions December 2024 Relese Notes v3.9"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/25554888"
tags: ["Contact Management"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Commissions December 2024 Relese Notes v3.9 Production Release: December 9, 2024, v3.9 Release Summary  NEW"
long_description: "Constellation1 Commissions December 2024 Relese Notes v3.9 Production Release: December 9, 2024, v3.9 Release Summary  NEW! Dashboard, Forecast Charts: Added closing forecast chart.  Transaction Checklists: Added option to email multiple contacts when tasks are reviewed.  Canadian Electronic Tax Filing: Updated T619 electronic transmittal to comply with a new format.  Reports: Updated the Agent Incentive Level report and the Transaction Detail report.  Bug Fixes Release Details  New! Dashboard,"
---

# Constellation1 Commissions December 2024 Relese Notes v3.9

Production Release: December 9, 2024, v3.9

## Release Summary  

**NEW! Dashboard, Forecast Charts:** Added closing forecast chart.   
**Transaction Checklists:** Added option to email multiple contacts when tasks are reviewed.   
**Canadian Electronic Tax Filing:** Updated T619 electronic transmittal to comply with a new format.   
**Reports:** Updated the Agent Incentive Level report and the Transaction Detail report.   
**Bug Fixes**

## Release Details

New! Dashboard, Forecast Charts

We’ve added a new chart to the dashboard to show a forecast of pending closings in the next 12 months and beyond. 

A dropdown option has been added to the Production chart where a user can select Forecast. Closings Forecast charts can be based on $Values or #Ends. The charts show a bar chart of pending closings for Past Months, the next 12 months and Future Months.

The chart lists Pending Closings only, sorted by their expected closing month. The "Past Months" column are closings in months before the current month and the "Future Months" column are expected closings beyond the next 12 months.

The Forecast chart is available on the Broker and Enterprise Insights dashboards. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/12%20December/2024-Commissions-Dec-Forecast.png)

  
Transaction Checklists  
Administrators can now include other team members when reviewing tasks. 

We've added an option to email other users during the task review process. In the Task Approval popup, the administrator can select one or more admin users from the Recipients dropdown to receive an email about the task review. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/12%20December/2024-Commissions-Dec-ReviewTasks.png)

Canadian Tax Filing   
We have reviewed the relevant Canadian tax documentation to ensure that the electronic filing of T619 electronic transmittal complies with the Canadian rules and formatting requirements.

The T619 electronic transmittal XML file has been updated to include:

*   The transmitter's CRA Account Number
*   Updated tags for "TransmitterName" and "TransmitterCountryCode" to comply with the standard format
*   No changes to the T4A form

[Click Here](https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2024/get-ready-by-january-2025-there-will-be-changes-to-the-electronic-filing-of-information-returns.html) for more details about these changes.  

Reports   
**Agent Incentive Level Report**   
We've updated the Agent Incentive Level report to hide the Basis Date and Report Range fields. This provides a more intuitive user experience when creating or editing the report.

The Basis Date is directly tied to the Commission Plan configuration, specifically the "Period Starting" to "Period Ending" Commission Basis date. Since this date has no relevance for the report, we've removed it from both the Out of the Box report and Report Scheduler.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/12%20December/2024-Commissions-Dec-AgentIncentiveReport.png)

**Transaction Commission Detail Report**

On the Transaction Commission Detail report, we’ve added two new options to the Report Range dropdown list. They are "Month to Date" and "Year to Date."

When either of these is selected, the Custom Date range fields will be hidden, as a custom date range would not apply in those cases.

This update has been applied to the Out Of the Box report and to the Report Scheduler. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/12%20December/2024-Commissions-Dec-TransCommDetailRPT.png)

Bug Fixes

1\. We fixed an issue with the advanced filters not being saved in the Transaction Commission Detail report.

Previously, when creating or editing the Transaction Commission Detail report, the advanced filter criteria was not being saved. This was happening in the Out Of the Box report and Report Scheduler.

Now, this issue has been resolved. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/12%20December/2024-Commissions-Dec-TransCommDetailRPTBug.png)

2\. We fixed an issue with the incorrect status displaying on the agent landing page.

Previously, when an agent status was set to Inactive, the agent record on the agent landing page, displayed Active. 

Now, this issue has been corrected to display the correct status on the agent landing page. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2024/12%20December/2024-Commissions-Dec-AgentStatus.png)

  
3\. We fixed an issue with an error when activating an agent with pending transactions. 

Previously, when an agent is set to Active from Inactive and the agent has one or more pending transactions, the agent was not being set to Active.

Now, this issue has been resolved. Setting an inactive agent to active will make the agent active as expected.