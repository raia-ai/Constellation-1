---
title: "Accounting - Buyers/Sellers Export"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/25175680"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - Buyers/Sellers Export | Constellation1 Customer Hub The purpose of this article is to provide steps for creating a csv export file, to be"
long_description: "Accounting - Buyers/Sellers Export | Constellation1 Customer Hub The purpose of this article is to provide steps for creating a csv export file, to be used by the brokerage and/or individual agents. This export can be used by the brokerage and/or agent for many purposes, such as holiday cards, mail merge, or label printing.  To create the csv export file, navigate to Sales > Reports > Buyers/Sellers Export, then follow the steps below.  Enter a Starting Date and Ending Date for the date range th"
---

# Accounting - Buyers/Sellers Export | Constellation1 Customer Hub

The purpose of this article is to provide steps for creating a csv export file, to be used by the brokerage and/or individual agents.  This export can be used by the brokerage and/or agent for many purposes, such as holiday cards, mail merge, or label printing. 

To create the csv export file, navigate to **Sales > Reports > Buyers/Sellers Export**, then follow the steps below. 

*   Enter a **Starting Date** and **Ending Date** for the date range that you wish to export.
*   The **Preview Report?** and **Print Summary Only?** check boxes do not apply to the export and can be ignored.  
*   Check the **File per Agent** box if you want to have a separate export per agent.    
    *   The file name will format as the agent's **Name on Reports\_BuyersSellers.csv** if this box is checked off.
        *   For example:  If the **Name on Reports** field in the agent's profile record is **Franks, Mary**, the file will be named **FranksMary\_BuyersSellers.csv**.
    *   If a file with the name already exists, it is overwritten without prompting.
    *   If the **File per Agent** box is left unchecked, one csv file will be created and named **BuyersSellers.csv**.  If a file with the name already exists, it is overwritten without prompting.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/14973796-44c0-4736-aa77-3e8442c89bb6)

Additional information pertaining to the file:

*   The output format is csv (comma-separated values) with column headings.
    *   Excel can open csv files or the files can be viewed in a text editor (e.g. Notepad) or used with any application that can use csv files.
*   Only the side represented by the brokerage’s agents is included in the output.
*   Side is based on non-zero value in **Listing Count** or **Buying Count** fields, of the agent's commission record within sale transactions.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0f0a9e8f-89bd-4834-8ede-e275e75c0560)

*   When the **File per Agent** box is unchecked, if the brokerage’s agents represented both seller and buyer, then two lines will appear in the file, one for buyer and one for seller.
*   When the **File per Agent** box is checked, if the brokerage's agents represented both seller and buyer, two or more lines will be spread across the file.
*   If two agents represented the same side, and both have side count greater than zero, then the buyer or seller for the agents' side will appear in the files for both of the agents when the **File per Agent** box is checked.
*   The contact info comes from the related contact record if the contact is entered on the **Entities** tab of the sale transaction with **Type** equal to **Buyer** or **Seller**.
*   If the contact is not entered through the **Entities** tab, then the name comes from the name fields above the tabs in the sale transaction and the export file will be missing additional fields included in the contact records.  For example, address, phone number and/or Email address.  

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/3e4efc23-d3ed-44d2-b4dd-b1fa10ee59d6)

*   If the contact is entered through the **Entities** tab, then the additional information included in the contact record will be included in the export. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f6930b13-dc04-491c-bc38-f8690ec89db2)

*   The contact record can be found by navigating to **System > Setup > Contacts**.   
    *   Make certain that the address referenced in the contact record, is the address you intend to use for your export. If you would like record of a different address, add that as a second line item on the **Entities** tab. 
        *   Only the primary **Seller** and **Buyer** entered on the **Entities** tab will be included in the export.

Was this article helpful to you?

Was this article helpful to you?