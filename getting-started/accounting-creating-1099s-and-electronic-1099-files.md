---
title: "Accounting - Creating 1099s and Electronic 1099 Files"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/25884982"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - Creating 1099s and Electronic 1099 Files The purpose of this article is to provide instructions on how to print 1099-MISC forms, for othe"
long_description: "Accounting - Creating 1099s and Electronic 1099 Files The purpose of this article is to provide instructions on how to print 1099-MISC forms, for other income paid to vendors, and how to print 1099-NEC forms, for nonemployee compensation paid to agents and/or outside brokerages by the title company at closing. This article also includes instructions on how to create an electronic file for submission to the IRS. If you intend to submit 1099 data to the IRS electronically, we recommend that you se"
---

# Accounting - Creating 1099s and Electronic 1099 Files

The purpose of this article is to provide instructions on how to print 1099-MISC forms, for other income paid to vendors, and how to print 1099-NEC forms, for nonemployee compensation paid to agents and/or outside brokerages by the title company at closing.  This article also includes instructions on how to create an electronic file for submission to the IRS.  If you intend to submit 1099 data to the IRS electronically, we recommend that you setup a **FIRE** account with the IRS.  You will need to setup your **FIRE** account as soon as possible, so that you will have time to submit a test file to the IRS prior to your final submission.

Please note the following:  

*   The IRS currently offers two methods for e-filing: the **FIRE** site and the **IRIS** site.
*   The Constellation1 Accounting program is designed to generate e-files specifically for the **IRS FIRE** site and does not support the requirements for the **IRIS** site.
*   While the program can produce CSV files as a starting point, they are not formatted to meet the **IRS IRIS** site specifications. Adjustments must be made to the CSV file to comply with **IRIS** requirements, but unfortunately, this is not a service we provide.

Prior to generating 1099s for agents and vendors, you will need to first purchase 1099-MISC and 1099-NEC forms, then follow the instructions below:

*   Navigate to **Agents** > **Setup** > **Agents** and confirm that the correct **1099 Form** is selected for each agent.  All agents, by default, will have the **1099 Form** set to **1099-NEC.**  If the agent is not required to receive a 1099, then you may select **N/A** from the **1099** **Form** dropdown.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/79bf7edd-3afe-43c3-93cf-76d408efcf3e)

*   Navigate to **Agents** > **Processing** > **1099s**.
*   On the **1099 Data** tab, select the **Tax Year** that you wish to process for from the dropdown list.
*   Select **1099-MISC and 1099-NEC** from the **Tax Form** dropdown list.
*   Click **Create 1099 Records.**

**![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8508ae07-b6af-482a-b1da-6a6a8dd09e7e)**

*   Select **Create 1099 Records (all agents and vendors)** from the dropdown list.

When the 1099 Records have generated, you will receive the following prompt:   

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/75718bc7-439f-4f24-adaa-bb9493589d60)

*   Select **OK**. 

Ensure all 1099 recipients have a **Valid Tax ID** number, if not edit the **Recipient’s ID #** field in the 1099 data record. Alternatively, you can edit the **Tax ID/SSN** field in the agent’s profile record, and/or edit the vendor’s **Tax ID** field in the vendor’s profile record and then re-create 1099 records.

If you would like to review the printing coordinates for your 1099 forms, please review the following article: [Accounting - How to adjust 1099 printing coordinates.](https://constellation1.na3.teamsupport.com/knowledgeBase/25974723)

*   Navigate to the **Reporting** tab.

Note: The **Exclude recipients under $600?** box defaults as checked.  Review this with your accountant and uncheck if instructed to do so.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/877574d8-c896-4525-8f16-d121d97de665)

*   Print the **Pre-1099** report by ensuring **Pre-1099** is selected from the **Report** dropdown, and then click **Process** **Report.**
    *   If you would like only the last 4 digits of the tax ID number to show on the report, check the **Mask Tax ID** box.  

**![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6c86b7d6-cbd8-49a6-8a96-b0ac90509036)**

Both 1099-MISC and 1099-NEC data will appear on the report; 1099-MISC data appears first, 1099-NEC data follows.

*   Verify that all totals are correct prior to printing 1099s.
    *   If corrections are needed, make the corrections in source records then re-create 1099 records.
    *   To re-create 1099 records, navigate to the **1099 Data** tab, then click the **Create 1099 Records** button.
        *   Click **Re-create 1099 Records (all agents and vendors)** from the dropdown, if you would like to re-create 1099s for all agent and vendors.
        *   Click **Select an Agent** to re-create a 1099 for only one agent.
        *   Click **Select a Vendor** to re-create a 1099 for only one vendor.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ddded88b-62f1-47e9-98cd-3ecce91bb000)

*   Read the confirmation pop-up message, prior to clicking **Yes** or **No**.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f88b7f8d-8093-413a-b1d1-7f52ee70e65a)

Note:  You can add additional 1099 records, if you have paid vendors or agents outside of the program. 

*   If adding a new **1099-MISC** record, select **1099-MISC** from the **Tax Form** dropdown, prior to clicking the **Add** button.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/be8e6e64-a643-433f-8fd0-c98402acfa8b)

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/1afa2ef1-3bdc-46e9-93a9-9a9e705852d4)

*   If adding a new **1099-NEC** record, select **1099-NEC** from the **Tax Form** dropdown, prior to clicking the **Add** button.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f606a2e0-4e21-41a6-a2d4-9924f747d466)

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0c0212f2-556e-4123-b24b-b5373c65d60e)

When you are ready to print the 1099s, follow the steps below:

*   Navigate to the **Reporting** tab and select **Official 1099s** from the **Report** dropdown.
*   Select **1099-NEC** from the dropdown to the left of the **Process Report** button.
    *   If you would like only the last 4 digits of the tax ID number to show on the report, check the **Mask Tax ID** box.  
*   Ensure all fields are completed in the **Payer Info** section.  If anything is missing, click **Edit,** complete the required fields, then click **Save**. 

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/29c0249b-2de8-4d46-82f1-2e4fcda7befc)

*   Click **Process Report**.
*   Insert **Copy A** of the 1099-NEC forms into your printer.  You may want to print only one page to check alignment.
*   Repeat this process for **Copy 1**, **Copy 2**, **Copy B**, and **Copy C**. 

Once the 1099-NEC forms are printed, repeat the above steps for printing 1099-MISC forms by selecting **1099-MISC** from the dropdown to the left of the **Process Report** button.

Note:  The program _does not_ include functionality to print **Form 1096**. 

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c18d3403-2da8-46fb-9a23-2ef510ff0198)

Note:  All vendor records default to 1099-MISC, you may edit this by selecting the correct form from the **1099 Form** dropdown in the vendor’s **Setup** record. The options in this dropdown are **N/A, 1099-MISC,** and **1099-NEC.**  

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/32f33341-a208-4a2e-a463-68dfd8874229)

If you are required to, or choose to, submit 1099 data to the IRS electronically, you can opt to send both 1099-MISC and 1099-NEC data together in the same file, by selecting **All Forms** from the **Export** dropdown.  If you would like to report the 1099-MISC and 1099-NEC data in separate files, you can select **1099-MISC Only** or **1099-NEC Only**, prior to generating the export file.  In either case, select the **IRS Format –** **(excludes corrections)** from the dropdown, prior to generating the export file.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c8d831b5-a193-4e20-92df-0437d7b8aedb)

*   Click on the ellipsis **“…”** to open the file browser window, select a destination location, then click **Generate Export**.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/cf280099-85d9-44a1-974a-382affdf2922)

It is highly recommended that you submit a test file to the IRS.  To create a test file, select **IRS Format – Test File** from the dropdown prior to generating the export file.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e99342ff-2cba-4957-9704-85027255a2d1)

In the future, if you find corrections are needed, to the 1099 data previously submitted to the IRS, first navigate to the **1099 Data** tab.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/430721d2-ea7a-4bf0-ba52-82dce02c74e5)

*   Check the **Correction (electronic)** box on the **1099-NEC Data** and/or **1099-MISC** **Data** record. 

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/4c0a4f7b-80fd-461b-abf7-7bb205740882)

*   Navigate to the **Reporting** tab and select **IRS Format – Electronic corrections** prior to generating the export. 

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f030a0ca-fad5-429d-b166-b46c2dfc3d35)

If you do not plan to print 1099s from the program, you may choose to generate a CSV Format file to use with third-party software. The CSV file contains filing and earnings information that can be imported into your chosen 1099 software.  Note:  When you click the **Generate Export** button, the file is created in the folder designated in the **Output File** field. However, the file does not automatically include the .csv extension, but the contents of the file are structured as if it were a .csv file, even though the extension might be missing.

You can name the file with any extension you prefer, depending on how file associations are configured on your computer. For instance, using the .txt extension might make sense because the file can be opened in text editors like Notepad. This flexibility allows you to handle the exported file in a way that best suits your needs.

 ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e142e726-5bb4-4490-8ef0-949972eb0897)