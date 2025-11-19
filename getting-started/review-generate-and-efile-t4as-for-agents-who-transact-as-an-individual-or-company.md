---
title: Review, Generate and Efile T4A's for Agents who Transact as an Individual or Company
---

# Review, Generate and Efile T4A's for Agents who Transact as an Individual or Company

The purpose of this article is to provide users with the steps to review, generate and Efile T4A's for your Agents who transact as an individual or company. 

_**Note: This functionality is only available if you integrate with QuickBooks®.**_

On the left navigation bar select **Contacts** and the very first contact displayed will be your Brokerage.  Edit the contact and ensure the company's Business Number is entered.  Typically, this is the same number as the brokerages tax number except with RP instead of RT for example 123456789**RP**0001.

**![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/dfa5dc2f-581a-49e2-9338-5ac7b96570df)**

Prior to reviewing T4A’s we strongly recommend all mandatory information for the Agent is entered correctly: 

1\. Name (individual or company)

2\. Social Insurance Number or Business Number (individual or company)

3\. Address

4\. Address 2 (if applicable)

5\. City

6\. Province Code (ON, AB, BC, etc.)

7\. Postal Code

In addition, we recommend confirming values displayed via T4A review window by using the Transaction Commission Detail via Reports / Transaction Reports section. 

Please configure the report with the information as described below:

Using for T4A validations, toggled ON. (This will grey out Transaction Status and Basis Date saving time, however if user wants to manually generate a report with Transaction Status and Basis Date enabled, simply toggle off this option).

Tax Year, select from drop down

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/810460cc-7b3a-44a2-a14f-413934f941fc)

In the Advanced Filters section, select as needed;

**Source of Commission Data** will include both Actual and Historical amounts whether they are both selected or not. If user does not want to include any values entered via the Agents profile / Commission Details tab / Agent History, select Actual.

**Transactions excluded from Commission Tiers** = Include

**Award Allocations** = Exclude

**Inactive Agents** = Include if there are Agents whom left at anytime in the previous calendar year

**Transaction Details** can be included or excluded, this is users preference

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/677f0bd9-deb2-4acb-973c-3549663ede49)

In the Formatting section, select Export Page Break Formatting = Agent so a copy of the report can be provided along with the T4A slip. 

Select **RUN**, to generate the report. 

**Note: If history has been entered for Agents that have changed their registration to transact as a Personal Real Estate Corporation, please select Actual. This will eliminate any history that may have been entered to capture commission earned as an individual vs a Personal Real Estate Corporation towards their existing commission plan. The reported amount may require adjustments (+/-) to the T4A amount once reviewed.** 

**Note: Effective Tax Year 2023, Box 015 is only mandatory if there is an amount in Box 016. Here is the link from Canada Revenue Agency site; [https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll/completing-filing-information-returns/t4a-information-payers/t4a-slip.html](https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll/completing-filing-information-returns/t4a-information-payers/t4a-slip.html)**

**Review T4A's (It is not mandatory to complete the Review, however we strongly recommend that users do)**

From the left navigation bar select **Agents / T4A tab**

Select the applicable Tax Year from the drop down

Show Agents with No T4A Values should be toggled ON if user wishes to manually enter values for an Agent who has not processed any transactions within the application

Agent Names with a black information icon to the far right, indicate that mandatory information described above is missing (SIN/Business Number, City, Postal Code, etc.) and should be corrected before proceeding.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/be70d43b-98ca-41c9-84a2-1c388ab385bb)

Place check in box to left of Agent names and select Action = Review

You will be presented with the following screen; where Box 20, Box 28 and Box 22 will auto-populate based on the transactions with a process date in the calendar year. 

**Box 20** represents the Agent Net total on the Transaction Commission Detail report, including any Agent History with a date in the applicable calendar year

**Box 28** represents the Bonus Override total the Agent received during the calendar year.  This value can be confirmed by generating the Bonus Override Detail report with the same filters detailed  above. 

**Box 22** represents the value of a withholding type deduction such as a garnishment for non-payment of personal income tax. This value can be confirmed by generating the Company Profit Deductions report with the same filters detailed above.

**Box 48** will not auto-populate and should only be used if the Agent has provided your Brokerage with non-commission related services such as sign installations, lawn cutting, general office cleaning, etc. It is your responsibility to ensure compliancy with Canada Revenue Agency requirements.  

The Adjustment boxes support both a positive and negative value should user need to increase or decrease the Final amounts.

The blue arrows to the left and right, will go to the next or previous Agent record. 

When finished reviewing, select **Save**, then **Exit**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/62e38449-ff2e-4cf4-b48d-3a22c3edeb75)

**Generate T4A's**

Select Action = Generate T4A

User will be presented with the following screen; 

Download T4A Slips will save a zipped folder to the PC's Downloads folder, ex. 2023 T4A Slips 202309201501.zip

Save T4A Slips to Documents will save the zipped folder to the T4A Documents section, once expanded. 

Select **Generate**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/43f755e4-a901-451d-81b5-bef44ea70dd0)

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9932bcc9-f005-4a9d-944a-2dca68c5beb0)

Navigate to the PC's downloads folder and unzip the folder to see a separate .pdf for each Agent (individual or company), a Multi-Agent.pdf that will contain slips for all Agents and a Summary.pdf if the brokerage is not required to submit electronically. 

These .pdf's can be printed, added to the Documents tab of the Agent profile, emailed as an attachment, etc. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a807a086-21c3-4bec-9ba0-09f58853d8e1)

**Generate Efile**

Select Action = Generate EFile

User will be presented with the following screen; enter your name, phone, extension and email as required by Canada Revenue Agency. 

Download T4A Efile will save a zipped folder to your PC's Downloads folder, ex. 2023 T4A EFile 202309201529.zip

Save T4A Efile to Documents will save the zipped folder to the T4A Documents section, once expanded. 

Select **Generate**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5cd0602b-0a68-4b4b-b976-8ececc0b6803)

User will be presented with the following window;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5dfbe543-cba0-424a-b744-09534b5545a6)

**Cancel** will return to the T4A window

**OK** will redirect to the Internet File Transfer site 

Once user selects ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/67230a28-a7e0-4263-a90b-ef26806c7c50) at the bottom of the page, user will be presented with the following screen, select **Next** and follow the prompts provided by Canada Revenue Agency. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8c07c4cc-c662-4dc3-a46a-9a117e98e44d)

The .xml will be found in the PC's downloads folder. Unzip the Efile folder to find the .xml required to upload to Canada Revenue Agency site.   

The folder will also contain a .pdf of the Summary form for your records.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a533b31a-253a-4dd3-8f5b-5bdb18aa2bab)

User is now finished with T4A's. 

_**Note: If the .xml is rejected by Canada Revenue Agency, you will fix the issue (for example, invalid postal code or wrong amounts) then review, generate and Efile again. A new zipped folder will be generated that is saved to your PC's downloads folder.**_