---
title: Constellation1 Commissions March 2023 Release Notes v2.1
---

# Constellation1 Commissions March 2023 Release Notes v2.1

Production Release: March 16 2023 v2.1  

## RELEASE SUMMARY

**Coming Soon:** Commissions Online for our Canadian customers.

**Report Access Permissions:** Added Reports Access permission for management users and office administrators.  
**New Report Option:** Added option to make the Bonus Override Detail report available to agents.   
**Agent Check Stub Report:** Added commission calculation breakdown.  
**Report Templates:** Added option to share report templates with agents.   
**Assistant Commission Statements:** Added Assistant Commission Statement.   
**Commission Rules Updates:** Deductions with optional discounts can be attached to a commission rule and are now automatically added to a transaction.   
**User Interface Update:** Added the side an agent represents to the name field when editing agent details and updated icons.  
**Bug Fixes**

##   
RELEASE DETAIL

Coming Soon

We are pleased to announce Commissions Online will soon be available to our Canadian customers. The release will include many exciting features not only for our Canadian customers, but our US based customers, too.   
These features include:

*   Canadian compliance for most provinces
*   Additional tax Calculations
*   Transaction Record Sheet template
    *   Customizable based on region or province
*   New Tax Reporting capability
*   Transaction contact letter templates

We're putting the finishing touches on it now and we'll let you know when we're ready!

Admin Permissions – Reports Access  
We’ve added a new permission called Reports Access. The new permission allows a Master User to manage who has access to reports.   
In the Admin View tab under System Settings > Permissions, for System & Users, there is a new Report Access permission token that can be added or removed for the Management User and the Office Administrator. Removing the permission will remove their access to reports. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-Permission.jpg)

_**Note:** By default, this permission will be added to both Management User and Office Administrator accounts._ 

Bonus Override Detail Report for Agents  
We’ve added the ability for administrators to make the Bonus Override Detail report available to agents.   
In the Agent View tab under System Settings > User Permissions, we’ve added a new Bonus Override Detail toggle in the Report Access section. This will be turned on by default and available in the Agent View. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-BonusOveride.jpg)

Agent Check Stub Report   
We’ve updated the Agent Check Stub master template to include a breakdown of the commission details and calculations, giving the agent a clearer understanding of their commission.   
We’ve added two new bookmarks to the Agent Check Stub report master template. These new bookmarks are:

*   Commission Rule  
    *   Shows the calculated rate that is applied to a transaction based on the commission rule.
*   Agent Adjusted Portion 

The master template must be downloaded and edited, then uploaded as a Customized Template.  

The Check Stub Report can also be shared with agent's. See Report Templates, below.

Report Templates  
We’ve added the ability for administrators to share custom reports with agents, allowing agents to generate two reports for their transactions: the Agent Commission Statement and the Agent Check Stub report.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-LetterTemplate2.jpg)

To have the option to make the templates available in the agent view, the master template must be downloaded, customized and uploaded as a customized template. A new toggle will show on the Edit Customized Template modal for these two templates.By default, these templates will be available in the agent view.  

To hide these reports in the Agent View, Navigate to System Settings > Advanced Settings. In the Action column, click the Edit button for the template. The below modal will appear, and the user can toggle Template Available in Agent View on or off. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-LetterTemplate.jpg)

Assistant Commission Statement   
We’ve added an Assistant Commission Statement template to the Master Templates on the Templates tab in Advanced Settings. This statement is designed to give the agent assistants a detailed understanding of their portion of the commission.

The Assistant Commission Statement template can be downloaded and customized and then uploaded back to Commissions Online.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-AssitCommStmt.jpg)

  
This statement is generated when the Assistant Bonus toggle has been turned on in the Add Bonus Override modal from the agent record. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-AssistantStatement2.jpg)

Commission Rules Updates  
We’ve added the ability to apply discounts to commission rules as a deduction that can then be applied to a transaction.   
In the Commissions section, on the Commission Rules tab, when a user adds a deduction, they can now add a discount to the deduction. 

To enable the discount option, in a commission rule, click the Edit button for the deduction, then turn the Apply Discount toggle on. Enter the corresponding percentages, and then click Save.  

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-Commission-Discount2.jpg)  
_The Deductions section for a commission rule_   
 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-AddDeductionDiscount.jpg)  
_Apply Discount_ 

Additionally, when a commission rule is added to a transaction the deductions and discounts will automatically be applied to the transaction. This improves usability and removes the need to add deductions to transactions when a commission rules is added to a transaction.  

User Interface Update   
We’ve added a label before the agent’s name when editing an agent who is associated with a transaction. The name field at the top of the page will now display the side of the transaction the agent represents.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-TransAgentLabel.jpg)

To identify Transaction Letters/Reports more easily, we have changed the associated icons within the program from standard Word icons to individual icons as below.  As usual, by hovering over icon a pop up will appear identifying the transaction statement name

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-2After.jpg)

Bug Fixes

1\. We fixed an issue with the Agent Incentive Level report not calculating correctly.    
Previously, when a user would run the Agent Incentive Level report, even if they set a customized date range, the report would run using the current day’s date to calculate the agent incentive level.     
Now, the report will use the date entered in the Up To Date field. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/2023/03%20March%202023/2023-March-ReportAgentIncentive.jpg)

2\. We fixed an issue where two download files would be created when exporting custom reports.   
Previously, when a user would export some custom reports, the system would create and download two export files.  
Now, the system will only generate one export file for the user to download.