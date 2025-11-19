---
title: "Constellation1 Commissions May 2022 Release Notes v1.14"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/16941590"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Commissions May 2022 Release Notes v1.14 Production Release: May 2022 v1.14 Release Summary  General Ledger Updates: Improved access an"
long_description: "Constellation1 Commissions May 2022 Release Notes v1.14 Production Release: May 2022 v1.14 Release Summary  General Ledger Updates: Improved access and visibility to account details. Added new Payment method.  Disbursements: Added Reverse and removed NSF from disbursements."
---

# Constellation1 Commissions May 2022 Release Notes v1.14

Production Release: May 2022  v1.14  

## Release Summary

**General Ledger Updates:** Improved access and visibility to account details. Added new Payment method.

**Disbursements:** Added Reverse and removed NSF from disbursements.

**Zero-Dollar Transactions:** Create any transaction type with a zero-dollar sale price.

**Commission Plan Deductions:** Added toggle to Split Deduction Across Agents.

**Agent Anniversary Reset Period:** Added option to not reset an agent commission plan.

**Creating Transactions:** Agent list now displays in alphabetical order.

**Importing Transactions:** Improved TMS import options. 

**Document Management:** Added document upload, storage and Sharing feature.

**Reports:** Improvements made to pre-built and custom reports.

**Contacts List:** Added ability to delete contacts.

**User Interface updates:** General updates made to the user interface.

**Bug Fixes**

## Release Details

General Ledger Profile  
We’ve improved the visibility of account information in the General Ledger by adding an “eye” icon next to each field under Constellation1 Accounts that will display the account name, number, and type when clicked. 

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-GL-Account-Info1.png)  
_New General Ledger button_

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-GL-Account-Info2.png)  
_Account Details_

Agent Payment Setting  
We’ve added the option to set Agent Payment options as a Bill or Check.  
On the General Ledger page under Additional Details, we’ve added a new dropdown labeled Agent Payment Setting. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-GL-Payment-Options.png)  
In the dropdown, you can select Bill or Check as the payment type. Check is the default setting. 

This is integrated into QuickBooks® as a “bill" to be paid through Accounts Payable and will update in real time.  
When this option is set to Bill, a new line will be added to the bottom of the General Ledger page and will need to be mapped into QuickBooks®.  

  
  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-AgentPaymentSetting.png)

Deposits and Disbursements – Reversal and NSF  
For Disbursements, NSF has been removed from the Actions menu for Disbursements. This update makes the disbursement workflow more efficient and intuitive.   
From the Actions menu, you have the option to View disbursement details or Reverse a disbursement. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Reversal2.png)  
_Disbursement Actions Menu_

For Deposits, the ability to Reverse a Deposit or set a deposit as NSF will remain. From the Actions menu, you can View deposit details, Reverse a deposit that was entered in error, or set a deposit as NSF where a deposit doesn't clear.   
Note: Reversing a deposit will void the deposit, and setting it to NSF will create a journal entry.  

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Reversal1.png)  
_Deposit Actions Menu_

  
Zero-Dollar Transactions  
We’ve improved transaction management by allowing you to create a transaction of any type with a Sale Price of $0.00.  
Previously, only referral-type transactions could be created with an amount of $0.00. 

Commission Plan Deductions   
Commission plans now have a new deduction option. This new feature allows deductions to be split between agents or applied to all agents individually.   
In Commission Plans, we added a new Split Deduction Across Agents toggle.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Deduction-Split.png)

   
Examples:

*   **Enabled/On:** The deduction will be split between the agents based on their commission allocation.
    *   If the deduction is $1,000 and the commission allocation is 50/50, a deduction of $500 will be applied to each agent.
    *   This is the default setting.  
        
*   **Disabled/Off:** The deduction will be applied to each agent
    *   If the deduction is $1,000, this amount will be deducted from both agents

Agent Anniversary Reset Period

The Agent Anniversary Reset Period now supports No Limit. Previously, the agent anniversary period would limit agents to a 3, 6, 9 or 12 month period before their commission plan would be reset back to tier 1.   
Now, administrators have the option to select No Limit. Selecting this option will not reset the agent commission plan. This ensures the agents’ commissions will accumulate over the lifetime the agent has transactions with the company or brokerage.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-AgentAnniversary.png)

Display of Agent Lists  
When adding agents to a transaction, we will now display their names in alphabetical order by First and Last Name. 

Importing Transactions  
You now have more control over data imported from Dotloop, SkySlope, or other supported transaction management systems (TMS). This new feature lets you define what data is imported.    
On the Advanced Settings page, under Transaction Settings, you will see a newly added Transaction Import Override dropdown. 

The available options are:

*   All Data Fields
    *   On import, all transaction data will be added or updated, including commission data  
        
*   Do Not Override
    *   Existing transactions will not be updated by the import
*   Transaction Data Only
    *   All transaction data will be updated, including property details, contacts, and sale price, excluding commission data

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Txn-Import-Controls.png)

**Please note:**  
•    Agent data is not included in Transaction Data   
•    Transaction Data includes all fields that are not directly tied to commission calculations

Document Upload and Sharing   
Managing documents has never been easier. We’ve added a Documents tab to the Transactions and Agents sections. In this tab, you can upload and manage documents. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Documents1.png)

From the Action menu, you can share documents or mark them as private. Documents can be shared with others associated with the transaction or set to Private so only the person who uploaded them can view them. 

Supported file types that can be uploaded are:

|     |     |
| --- | --- |
| xls<br><br>     xlsx<br><br>     csv<br><br>     pdf<br><br>     doc<br><br>     docx | jpeg<br><br>     jpg<br><br>     png<br><br>     zip<br><br>     txt<br><br>     rtf |

Constellation1 provides 5 gigabytes of safe and secure storage for your company. If you require more storage, please reach out to your Constellation1 representative.

Custom Reports   
You can now export custom reports as a CSV or to PDF. Click the Export button to see and select the export options.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Report-Export.png)

  
    
Pre-Built Reports  
Save Reports  
You can now save your filters options with pre-built reports. Giving you quick and easy access to your information.   
Select the options for each filter, then click Save. The next time the report is opened, the filters will populate with the previously selected options, saving you from creating the report each time you access it.  

  
Copy Reports  
We’ve added the ability to copy certain pre-built reports, allowing you to use the report as a template for a new custom report. 

  
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Report-Copy1.png)

When viewing the report, click Copy to open the report in edit mode.  
Add or remove fields to customize it, then click Save.

Your new report will be saved to your custom reports. If you didn't give your report a new name, we will append -Copy to the report name for easy identification.  

The reports that can be copied are:  
•    Agent Income Summary  

•    Agent Transaction Details

•    Pending Transactions

•    Transaction Commission Detail  

Export Reports  
Exporting pre-built reports is now easier than ever. We’ve added the ability to export pre-built reports.

To export a report, click Run. On the report details click the hamburger menu in the top left corner. Select Export. Select the file format of the export.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Report-Export2.png)

Export file types are, 

*   RTF
*   xls 2003
*   xlsx
*   PDF
*   Tagged Image
*   Plain Text
*   Web archive

Depending on the export format you may be presented with other options that are specific to the selected format.

Click the Export button at the bottom of the left column.  

Preview Reports  
A report preview has been added to some pre-built reports. The preview will show the first 15 rows of the report and will show below the filters section. The preview is in a tabular format and does not show any formatting.  

  
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Report-Preview.png)

Reports with the preview option include:  
•    Agent Income Summary  
•    Pending Transactions  
•    Transaction Commission Detail  
•    Agent Transaction Detail 

Contacts List  
You can now delete contacts from the list. If you have duplicate contacts or people who don’t need to be in your address book anymore, you can remove them.   
In Contacts, in the Action menu next to each contact, click the three dots, then click Delete to delete a contact. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/Commission-2022-April-Contact-Delete.png)

**Note:** Contacts who are attached to a transaction cannot be deleted. 

User Interface Improvements   
You will notice we’ve made changes to some of the layouts, designs, and verbiage throughout the Commissions application. These changes all work together to improve workflow, efficiency, and intuitiveness. 

BUG FIXES

*   Fixed an issue with the Dotloop integration to ensure transaction data imports correctly. 
*   Fixed an issue with the Agent Commission Statement not showing commission and deduction details accurately.
    *   Examples: End Side Gross Commission or Referral Amount.
*   Fixed an issue with Address 2 showing multiple times on the Closing Review Report.
*   Fixed an issue with Integrated Deposits showing the payment method as “Cash” in QuickBooks®.
*   Fixed an issue with offices assigned to a transaction not populating accurately in reports, and QuickBooks®.
*   Fixed an issue with the Transaction Number and Transaction Address not showing in the memo field in QuickBooks®  
    
*   Fixed an issue with the calculations used to determine the Agent Anniversary amount on the Agent Check Stub Report. 
*   Fixed an issue with information not showing for the “Agent Anniversary to Date Before This Closing” and “Commissions Needed to Reach Next Tier” fields on the Agent Check Stub Report.