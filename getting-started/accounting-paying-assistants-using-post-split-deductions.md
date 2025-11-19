# Accounting - Paying Assistants Using Post Split Deductions

The purpose of this article is to show how to pay an assistant from an agent's commission, in stances when the assistant _is not_ a licensed agent, and when the assistant _is_ a licensed agent. &#x20;

The first step to take, when an agent would like part of their agent split to be deducted to pay their assistant, is to setup a unique post-split.  To setup a post-split deduction, navigate to **Agents > Setup > Post-Split Deductions**.

* Click **Add**
* Enter unique **Deduction Code** up to eight characters
* Check **Show Description** **on Stub Report?** box, if you would like this to be reflected on each agent’s Commission Statement
* Enter **Description**
* Check **Show Description YTD on Stub Report?** box, if you would like this to be reflected on each agent’s Commission Statement
  * **The Description YTD** field will auto-fill but can be edited
* Select GL **Credit Account** from dropdown
* Enter **Default Percent** or **Default Amount**, if applicable
* Select **Percent of What** from the dropdown
  * Note, this field is required; however, it is only applicable when used with **Default Percent**
* Enter **$ Ceiling** or **Count Ceiling**, if applicable
* Select **Vendor to pay**, if applicable, by clicking the green plus sign (**+)** and selecting from the current vendor list or add a new vendor record.
  * Once vendor is selected, click **OK**
* Select **Bill Comment Option** from the dropdown
  * The choices are **Seller/Buyer/Address** and **Agent Name**
    * When paying an assistant, it is recommended that **Seller/Buyer/Address** is selected, so the assistant can keep track of which property they are being paid for, from the AP module
  * Note, **Bill Comment Option** is only required if you have selected a **Vendor to pay**
* Do not check the **Show Agent Tax ID in Bill?** box
  * &#x20; Note, this is only required for **Retirement Deductions**
* The **Rank Order of Deduction** field will auto-fill but can be edited
* Check the **Deduct for 1099?** box, if you would like this deduction to affect the agent’s 1099 value&#x20;
* Leave all other boxes unchecked
* Click **Manage Subscriptions** and check the box in the **Subscribe** column next to applicable agents
* Click **OK**
* Click **Save**

In the example below, an agent would like to pay his assistant, Jeff Daniels, 10% of their **Agent $ After Split with Office**. Jeff Daniels is not a licensed agent and so the agent would like for an AP bill to be created for Jeff Daniels after each closing. In this scenario, you may want to setup the new post-split deductions as follows:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d66d5134-9bb8-4f2e-a3e0-9170b57905bb)

After the new post-split deduction has been setup, navigate to **Sales > Processing > Sales Transactions**. &#x20;

* Select an existing **Pending** sale or click **Add** to create a new sale
  * Note if selecting an existing **Pending** sale, you will need to click the **Re-initialize** button on the agent's commission record to bring in the new post-split deduction.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0f5e10fd-a9c7-4f87-a961-fa600e17d983)

Once the Re-initialize button is selected, the new post-split populates and deducts 10% of Agent $ to be paid to the assistant. &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a2fd05fa-77df-46eb-be73-cb4fe93ffc0f)

In the example below, an agent would like to pay his assistant, who is a licensed agent with the office, 10% of their **Agent $ After Split with Office**. In this scenario, you may want to setup the new post-split deductions as follows:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/dbbc7ea7-acf8-4c9a-8fd3-b7692f9afc66)

After the new post-split deduction has been setup, navigate to **Sales > Processing > Sales Transactions**. &#x20;

* Select an existing **Pending** sale or click **Add** to create a new sale
  * Note if selecting an existing **Pending** sale, you will need to click the **Re-initialize** button on the agent's commission record to bring in the new post-split deduction.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0f5e10fd-a9c7-4f87-a961-fa600e17d983)

Once the Re-initialize button is selected, the new post-split populates and deducts 10% of Agent $ to be paid to the assistant. &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d5469f39-4ab9-45f8-bab6-d9749a5f0ba7)

To pay the assistant, click on the green plus sign (+) to select the assistant from your list of agents.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/59501421-ecf1-46dd-afc9-53ae76379b80)

On the assistant's agent commission record, enter a negative amount in the ASST post-split equal to the amount that was deducted from the lead agents Agent $. This will result in a positive Agent Payment for the assistant. &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/60f27324-f714-4393-81d5-a17d47789710)
