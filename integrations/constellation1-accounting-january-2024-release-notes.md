
# Constellation1 Accounting - January 2024 Release Notes

Production Release: January 2024 

## Release Summary 

**Credit Card Processing:** Enhanced credit card processing.  
**Quarterly Estimated Tax Reports:** Changed the default setting for the date fields and removed the Date Warning message.   
**AP Check Stub:** Removed Record# column.   
**Invalid Tax ID’s:** Added Source column to the 1099 Data page.   
**Agents Module User Interface:** Updated the 1099 page when adding or editing an agent 1099 data.   
**One Line Sales Report:** Updated report. 

## Release Details  

  
Enhanced Credit Card Processing  
We’ve upgraded our credit card processing system for improved security, stability, and efficiency. 

Benefits of this upgrade include:  
•    An even more secure and stable environment for processing credit card transactions.  
•    No longer need to retrieve Charge Batch files.   
•    Added ability to stop processing a batch of charges.  
•    Real-time credit card processing status.

  
Two Accounting configurations need to be updated. A Constellation1 representative will reach out to assist with these changes.   
The first is a Third-party integration. In System Settings, a new third-party integration has been added with Setting name, CSIPaySystem. In the Text Value dropdown, select PYXiS and click Save.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-Settings-CSIPAYMENT.jpg)

   
The second is to add a terminal ID to Credit Card Settings. A Constellation1 representative will provide you with this information. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-CreditCardSettings-TerminalID.jpg)

   
Additionally, there are two new features for processing agent and vendor credit cards. 

  
**Stop Processing**  
We’ve added the ability to stop processing charges. To stop processing a batch of charges, click the Stop Processing button. Transactions that have already been processed cannot be stopped.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-Agent-CCProcessing.jpg)

  
 **Real-Time Processing**   
Credit cards will be processed in real time. In the Agent Credit Card Processing section, on the Charge Batches tab, users can now see the credit card processing status and results right away.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-Agent-BatchSummary.jpg)

Quarterly Estimated Taxes Reports   
We’ve updated the date fields for the Quarterly Estimated Taxes Report to provide a more intuitive and more accurate report.   
The Starting Date field is now blank by default, and the Ending Date field is set to the last day of the previous month, based on the user’s system date. Users will need to confirm with the IRS their starting date for the current tax cycle.   
We’ve also removed the Date Warning message.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-Agent-EstTaxes.jpg)

  
 AP Check Stub Update  
We’ve removed the Record# column from the AP Check Stub, making it easier to read. This information was not useful or necessary for vendors. 

Tax ID Sources  
In the Agent module, on the 1099 Data page, we’ve added a Source column allowing the user to easily identify the module where the tax ID was entered so it can be updated as needed.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-1099Source.jpg)

  
User Interface Update  
In the Agents module on the 1099 tab, the center panel with the list of Tax Names and 1099’s will collapse when adding or editing the record.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-Settings-1AgentBefore.jpg)

Before editing or adding  
   
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Accounting/2024/01Jan/2023-Accounting-Settings-2AgentAfter.jpg)  
While adding or editing

Updated One Line Sales Report  
We’ve updated the One Line Sales Report to prevent the MLS column from overlapping with the Volume column.   
When processing the MLS version of the report, we automatically hide the Agent Commission and Office Earnings columns, allowing for more room on the report. We’ve moved the MLS column to the left to prevent it from overlapping with the Volume column.