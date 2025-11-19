# Constellation1 Commissions September 2022 Release Notes v1.15

Production Release: September 7, 2022 v1.15

## Release Summary&#x20;

**New! Commission Statements and Check Stubs:** Share commission statements and check stubs with your agents.&#x20;

**Transaction Control:** Enable the buying side to control a transaction. &#x20;

**Imported Listings:** Convert listings to transactions automatically.  &#x20;

**New Commission Calculation Type:** Added type that includes pending transactions.

**Commission Income:** View shared and unshared income included in a transaction.&#x20;

**Imported Transactions:** Removed ability to reverse closed transactions.&#x20;

**Commissions Disbursed by Third Party:** New Disbursed by Third Party toggle workflow.&#x20;

**Commissions Disbursed by Third Party:** Added new warning messages.&#x20;

**Transaction Numbers:** Removed ability to edit auto-generated transaction numbers.&#x20;

**Agent Check Stub:** Added amount needed to level up to next tier.&#x20;

**Monthly Activity Summary Report:** Updated name and description.&#x20;

**Shared Documents:** Shared documents will be sent as PDF files.&#x20;

**Custom Reports:** Added new agent-centric data points to reports.&#x20;

**New! Realogy Franchise Detail Reporting:** Added Realogy-specific reporting feature.&#x20;

**Commission Statement:** Added Landlord and Tenant fields.&#x20;

**QuickBooks® Integration:** Transaction number and property address added to the Reference Number and Memo fields.&#x20;

**Commission Plans:** Added Withholding as a new deduction type.&#x20;

**Agent Accounts:** Uploaded documents are now auto saved.&#x20;

**Transaction Groups:** The setting will default to the setting of the previous transaction.&#x20;

**Advanced Settings:** Updated user interface.&#x20;

**Calendars:** Calendars have been updated throughout the system.&#x20;

**Company Name:** Character limit increased.&#x20;

**Bug Fixes**

## Release Details&#x20;

Commission Statement and Check Stub Delivery

We’ve added the ability to email commission statements and check stubs to agents for their pending and closed transactions. When selected, a modal will open where the user can select the agent(s) associated with the transaction, which document(s) they want to send, and the template they want to use.\
Statements and/or check stubs can be sent from any of these three locations: \
•    A pending transaction\
•    The closing transaction wizard\
•    A closed transaction

Agent commission statements are available for pending and closed transactions.\
Check stubs are available only for closed transactions. \
&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-StatementDelivery1.png)

Pending Transaction&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-StatementDelivery2Closed.png)\
Closed Transaction&#x20;

Transaction Control - Disburse Trust Funds from Buying Side\
We’ve enhanced the user’s ability to control and disburse trust funds from the buying side.\
This option is based on functionality available in previous desktop version of Commissions and is available in the Controlling Side dropdown on the Transaction Details page.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-controllingSide.png)

Convert Listings to Transactions&#x20;

We’ve enhanced the listing import process. \
Users can now import listings and automatically convert them into Constellation1 Commissions transactions from the following transaction management systems: \
•    SkySlope\
•    Dotloop\
•    DocuSign\
•    Constellation1 Transactions &#x20;

When the listing is converted into a transaction in the transaction management system, it will also be converted into a pending transaction, moved to the Transaction Module, and displayed in the transaction list.

Commission Calculation Type – Anniversary Period Written

We’ve added a new Commission Calculation type: Anniversary Period Written.\
The Anniversary Period commission calculation type only includes closed transactions. The new type, Anniversary Period Written, includes pending and closed transactions.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-AnniversaryPeriod.png)

Commission Income&#x20;

We’ve added new fields to the Transaction Commission page. The new fields display shared and unshared income included in the total commission amount for a transaction. \
To display the Additional Income fields, click the down arrow next to the Commission Amount from the Transaction Commission tab. &#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-AdditionalIncome.png)

Imported Transactions&#x20;

We’ve removed the ability to reverse a closed transaction imported from previous desktop versions of Commissions.&#x20;

Commissions Disbursed by Third Party – Workflow

We’ve improved the workflow when the Disbursed by Third Party option is added to a transaction.&#x20;

Within a transaction, when the Commission Disbursed by Third Party toggle located under Additional Details is On, two fields will appear on the page displaying the default settings that were configured in Advanced Settings. The user also has the option to override the default settings and manually enter the disbursement information.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-DisbursedBy.png)

Commissions Disbursed by Third Party – Warning Messages

We’ve updated the warning messages users receive when there is an issue with a commission disbursed by a third party.\
The new warning messages are related to specific cases where a required configuration may be missing.&#x20;

Examples of situations where a warning message may show include:\
•    Disbursed by Third Party toggle is off\
•    Disbursed by contact is not selected \
•    Disbursement form is blank or missing&#x20;

The new messages are more intuitive to help the user understand the exact issue and resolve it.&#x20;

Transaction Numbers Not Editable

We’ve removed the ability to edit auto-generated transaction numbers. If a transaction number has been auto-generated, the Transaction Number field will be grayed out and the user will not be able to edit it.&#x20;

Agent Check Stub Report&#x20;

We’ve updated the Agent Check Stub Report to include the amount needed to reach the next tier based on the agent’s commission plan before and after closing this transaction.

This eliminates the need for the user to generate a second report showing their commission level and next tier level.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-CheckStub2.png)

Pre-Built Reports

We’ve updated the name and description of the Monthly Activity Summary Report.

The Monthly Activity Summary Report has been renamed the Monthly Activity Summary and the description has been changed to accurately describe the report: Displays summary of office production based on selected criteria.

Shared Documents in PDF Format&#x20;

Documents shared from the Documents tab within a transaction will now be sent as PDFs. This allows the recipient to easily view an uneditable document.&#x20;

Administrators are still able to download the document in Word format.

Custom Reports

We’ve added new data point fields to reports to allow users to create custom reports that include agent details. The new fields are:\
•    Birth Date\
•    Hire Date\
•    License Expiration Date\
•    License Number\
•    Agent SSN or EIN\
•    Agent Address1\
•    Agent Address2\
•    Agent City\
•    Agent State\
•    Agent Zip\
•    Agent Email\
•    Agent Phone\
•    Commission Plan (Label)&#x20;

New! Realogy Franchise Detail Reporting

We’ve added new Franchise Detail reporting for Realogy brokers. Realogy companies can use this feature to export their data in the right Realogy format.

To initiate this reporting, navigate to Main Menu > System Settings > Company. In the Franchise Designation dropdown, select the correct Realogy company and enter the Integration Key in the appropriate field.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-RealogyCompany.png)

After selecting your Realogy company, additional tabs will appear for mapping the Property Type, Lead Source, Additional Users, Transactions, and Results fields in order to generate the necessary reporting information.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-RealogyReport.png)\
Once the fields are configured and saved, the user can run the report and the data will automatically be uploaded to our data hub. Dash integration will then sync the data with Realogy.&#x20;

Commission Statements

We’ve improved the Commission Statement template to include Landlord and Tenant. The updated fields on the Commission Statement template now show as Seller/Landlord and Buyer/Tenant.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-CommissionStatement2.png)

QuickBooks® Bill Number Includes Transaction Number and Address

We’ve improved our QuickBooks® integration.&#x20;

When the agent payment setting is set to Bill, the transaction number and property address will be populated in the Reference Number field and the Memo field in QuickBooks®.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-BillNumber.png)

Added Withholding to Transaction Commission Plans

We’ve added Withholding as a new type of commission plan deduction.&#x20;

The purpose of this field is to allow additional funds to be withheld from an agent’s commission for personal reasons, such as charitable donations, or as a garnishment.&#x20;

Additional withholdings can be added to an agent’s commission plan on the Deductions tab. When the additional withholdings have been added, the Payee dropdown will change, allowing the user to select an agent or search for another contact to designate where the withheld funds should go.&#x20;

When withholdings are added, there is a separate line item on the general ledger to allow the user to manage how the withholdings are handled in the accounting system.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-Withholding.png)

Agent Accounts - Adding Documents

We’ve improved the workflow when adding documents to an agent profile. \
When adding documents, they will be saved automatically. Users will no longer be prompted to save them.

Transaction Groups

We’ve improved the setting for Transaction Group options.&#x20;

Previously, when creating a new transaction, the Transaction Group field would default to Residential. We’ve enhanced this field to now remember the previous setting.&#x20;

When the user creates the next transaction, this field will default to the same setting as the previously created transaction.

Advanced Settings&#x20;

We’ve made improvements to the user interface on the Advanced Settings page, making it more intuitive and user-friendly.

Calendar Years extended

We’ve updated all calendars, most notably the Agent’s Date of Birth, to include the years from 1930 to the present. \
Previously the calendar only included years starting from 1950. \
We’ve also updated the Anniversary Reset Period to now include No Limit as an option when adding an agent.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Commissions/09%20Sept%202022/2022-Aug-Commission-AnniversaryPeriod2.png)

&#x20;\
Company Name – Character Limit Increased&#x20;

In a recent release, we announced that we’d added a 35-character limit to the Company Name field when entering a contact to align with the QuickBooks® character limit.&#x20;

In this release, we’ve updated the character limit for company names to 50 characters.&#x20;

**Bug Fixes**

1\. Fixed an issue with a commission plan not being saved when a new agent is added. \
Previously, when adding a new agent, then adding a commission plan to the agent, the commission plan was not being saved.\
Now, when saving the agent after adding the commission plan, the commission plan will be saved to the agent.&#x20;

2\. Fixed an issue with a commission deduction name showing multiple times on the deductions report.\
Previously, the commission deduction name and amount would show multiple times on a custom report when exported. \
Now, the commission deduction will show once per transaction.&#x20;

3\. Fixed an issue with the Transaction Detail Report. \
Previously, the Include Internal Agents filter would include details from agents that should have been filtered out of the report. \
Now, this filter will only allow the selected agents to be included in the report.&#x20;

4\. Fixed an issue with the agent name showing as the payee on a Commission Disbursement Authorization Report when they are set up as a company.\
Previously, when an agent was set up as a company, the agent’s name would show as the payee. \
Now, when an agent is set up as a company, their company name will show as the payee on the Commission Disbursement Authorization.

5\. Fixed an issue with the Payee Name field being left blank on Trust Disbursements. \
Previously, the system allowed the user to enter a disbursement without adding the Payee Name.\
Now, we’ve added validation to the Payee Name field making it required when adding a deposit or disbursement.&#x20;

6\. Fixed an issue with a third-party escrow or title company name not showing on the Commission Disbursement Authorization.\
Previously, a third-party company didn’t show on the Commission Disbursement Authorization Letter.\
Now, the third-party company will show on the Commission Disbursement Authorization Letter.

7\. Fixed an issue with batch deposits not updating when a transaction in the batch was reversed.\
Previously, when a transaction was included in a batch and was reversed, the batch deposit didn’t update with a corrected amount. \
Now, when a transaction is reversed, the batch deposit amount will be amended and show the correct amount. When the transaction is updated and closed again, it will not be included in the original batch. Instead, it can be processed by itself or included in a new batch.&#x20;

8\. Fixed an issue with batch deposit dates changing when a transaction in the batch was reversed. \
Previously, when a transaction in a batch was reversed, the batch deposit date also changed to the date the transaction was reversed. \
Now, when a transaction in a batch is reversed, the batch deposit date will not change from the original date. &#x20;

9\. Fixed an issue with transactions not inheriting the Commission Distributed by Third Party setting. \
Previously, when a new transaction was created, the Commission Distributed by Third Party toggled was not inherited. \
Now, when a transaction is created, and the Commission Disbursed by Third Party is toggled on, the transaction will inherit this setting.

10\. Fixed an issue with historical figures not being included in the Transaction Commission Detail report. \
Previously, when the Source of Commission Data field was left blank, the report only included actual figures from Pending, Closed, or Canceled transactions. Historical figures were not included.  \
Now, when running the Transaction Commission Detail report, if no option is selected in the Source of Commission Data field, the report will include all actual and historical figures. &#x20;

11\. Fixed an issue with the cap amount applied to a deduction. \
Previously, when there was a cap on the deduction and the agent was on both sides of a transaction, the deduction was applied twice.\
Now, when the cap amount it met on the selling side, it will only be applied once if the agent is on both sides of a transaction.

12\. Fixed an issue with selecting a payee in an agent record.\
Previously, when selecting Company as the payee, the related fields didn’t update. For example, after selecting a Company as the payee, the SSN field didn’t change to EIN.\
Now, when selecting a company as the payee, the related fields will update to the correct labels based on the payee selected, i.e., Company, Employee, or Individual.&#x20;

13\. Fixed an issue with the incorrect sales volume showing on the Transaction Commission Detail Report. \
Previously, the Transaction Commission Detail Report didn’t include transactions with partial payments.\
Now, the sales volume will include transactions with partial payments and return the correct and accurate sales volume.

14\. Fixed an issue with errors not showing when adding an agent to QuickBooks®. \
Previously, if there was an error when adding an agent to QuickBooks®, the system would display error codes in the message that were not helpful. \
Now, if there is an error when an agent is added from Constellation1 Commissions to QuickBooks®, the system will display a more user-friendly error message.

15\. Fixed an issue with the seller not being saved when a pending listing was converted to a transaction. \
Previously, when a pending listing was converted to a transaction, the seller information was not saved as part of the transaction.\
Now, when a pending listing is converted to a transaction, the seller information will be saved to the transaction.
