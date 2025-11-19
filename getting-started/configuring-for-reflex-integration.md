
# Configuring for REflex Integration | Constellation1 Customer Hub

This article will provide you with the relevant information to configure Commissions Online for REflex Integration.

**Company**

To begin, from the left navigation bar select **System Settings** / **Company.** Ensure your Franchise Designation is selected, make any other changes you may require and select **Save** button at top right. The Affiliate ID is provided by Berkshire Hathaway HomeServices head office and will display in the Affiliate ID field. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5e0f62e0-b127-49a1-b6f1-49f1913b2159)

**Offices**

From the left navigation bar, select **Offices.** To add/edit an Office, please follow the steps detailed in our Knowledge Base by clicking here; [Office Maintenance.](https://constellation1.na3.teamsupport.com/knowledgeBase/16981872)

The Office Franchise ID is mandatory, and includes any Offices that may be inactive.  Once the Office Franchise ID is entered for each Office, select **Save** button at top right.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f8b6d46a-4e40-4806-bec8-fb3bcac67abb)

**Agents**

From left the navigation bar, select **Main Menu / Agents** 

*   At the top right, select **Action / Import REflex** to sync all of your Agents from REflex to Commissions Online. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d40aa895-170f-475d-aecc-9169a7f1a837)

*   Select **Import** button to Import all Agents from REflex

Once all Agents have been imported, you can configure the REflex Agent Import Sync Automation. The Sync is not bi-directional meaning all updates flow from REflex to Commissions Online.

To do this, toggle ON Sync Automation, select the Frequency (Daily or Weekly), Time of Sync and the Day of Sync which is only enabled if you select Frequency of Weekly. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ecc63843-b7fe-47b4-8a1e-ea91e3a8defa)

**Teams**

From the left navigation bar, select **Agents / Teams** tab**.** To add/edit a Team, please follow the steps detailed in our Knowledge Base by clicking here**;** [Teams.](https://constellation1.na3.teamsupport.com/knowledgeBase/17481761)

**Transactions**

*   Each transaction must have a Transaction Group selected on the Details tab / Additional Details card, select either Residential or Commercial.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17765379)

**Franchise Details card**

*   This card can be edited on closed transactions. 
*   The adjustment sequence number indicates how many times this transaction has been submitted to Berkshire Hathaway HomeServices.
*   It must be 0 (zero) the first time a closed transaction is submitted and then incremented by 1 for each subsequent submission thereafter.
*   Commissions Online handles this automatically but there are times when you may need to manually change the value because a previous submission was rejected.
*   **Please note that Commissions Online does not allow for a negative adjustment number. If directed to use -1 please adjust to 1 in Commissions Online.**
*   Exclude from Reporting will be used as required by your franchise. Perhaps vacant land type transactions or agents who sell their own properties are exempt from submissions.
*   If, “Is Referral" is toggled ON and the referral you received was from another Berkshire Hathaway HomeServices brokerage, then “Is In Network Referral” will be toggled ON and you must enter the Referring Brokerages Affiliate Id.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17765380)

**Transaction / Referrals**

*   Referral amounts paid to other brokerages can be exempt from Franchise fees as needed
*   To do this, navigate to the Commission tab of the transaction and select the ellipsis to the far right of the referral amount, then Advanced Options

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c7ed858c-6d2c-48ab-a2e6-ee4c0c3c0ef3)

Select the applicable Referring Franchise from the drop down and toggle ON, Exempt from Franchise Fee and Save.

*   **PLEASE NOTE**: in the event a transaction is closed and you have forgotten to mark a referral as exempt from Franchise Fee, it is NOT necessary to reverse the transaction to correct it.  The toggle for "Exempt from Franchise Fee" can be toggled ON for closed transactions.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/dce4b2f1-214b-4c0c-88cb-3c842bcd57bf)

**Franchise Reporting**

From the left navigation bar, select Reports / Franchise Reports tab and expand the Mappings card. 

Each Transaction Type displayed MUST be mapped to the appropriate Berkshire Hathaway HomeServices equivalent. This step only needs to be completed once unless you add new Transaction Types in Commissions Online. 

If you are not clear or have questions regarding mapping the transaction types, please consult with your Franchise.

Once all the selections are made, select **Save.** 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/55e46572-8032-4fbb-bc85-fefdb06165d2)

**Transactions / Export to REflex**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/be4bea0e-44d0-4a94-b6cf-859231b994b5)

*   Batch Type; New Batch is the default, however if you wish to see transactions included in a previous batch, select Previous Batch from the drop down and then you will be able to select the Previous Batch ID as needed. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6b255eb8-5c54-4401-a084-f1e0bfece3bb)

*   New Batch will display the list of all closed transactions since the last batch
*   All transactions will be selected (checked) to include, however if you can deselect transactions as needed
*   Select the Export to REflex button and when the submission is completed, a confirmation window will display to advise
*   There are no reports specific to Berkshire Hathaway HomeServices' REflex Integration, however the Transaction Commission Detail report should capture most of the information that was submitted in the batch

**NOTE: If a previous batch (transaction) was declined, and a resubmission of the batch (transaction) is required once corrections have been made. Select the Previous Batch that the transaction was originally submitted (after changing Adjustment Sequence Number on the corrected transaction) as detailed above.**