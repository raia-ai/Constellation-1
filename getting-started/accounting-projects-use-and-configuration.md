
# Accounting - Projects (Use and Configuration)

The purpose of this article is to explain the purpose of projects and how to setup them up.

A project can serve as an additional filter on many reports from the Sales, Agents, Accounts Payable, and General Ledger modules. However, what sets the projects filter apart from other report filters is that it allows you to process various Income Statement reports by specific projects.  For example, if your brokerage has exclusive rights to sell vacant lots in a new housing development, you can setup a project to track sales made in that development, to see what income was generated from that very specific source.  

To setup a project, navigate to **General Ledger>>Setup>>Projects**. 

*   Click **Add**.
*   Enter a unique **Project Code**, up to 8 characters.
*   Enter **Project Description.**
*   Enter **Warning Text**, if applicable.
*   Enter **Project Address**, if applicable.

In the example below a project was setup to track a rental property, including a **Warning** **Text** to remind users that the agent will receive 50% in commission for the Foxglove rental property sale transactions.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9f78f516-2f6e-4d37-8c06-9c31cfd63dd4)

When an agent commission record is added to a sale, and **FOXGLOVE** is selected from the **Project** dropdown, the following **Project Warning** will pop-up as a reminder that the agent should receive 50% commission for this rental property. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ae19fcc2-24b8-4a5e-8280-8c2c98402a32)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/737.png)

If you would like to see the profitability of this rental property, navigate to **General Ledger**\>>**Reports** and select your preferred I**ncome** **Statement** report.  In the example below, the **Income Statement - Date Range** report was selected. 

*   Enter **Starting Date**.
*   Enter **Ending Date**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0aeedddb-48a6-418d-b16b-60ac910010b6)

*   Navigate to the **Projects** tab.
*   Remove all checkmarks from the Selected column, except **FOXGLOVE**.
*   Uncheck the **Exclude Project Filter** check box.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ce32cad5-8b17-49a7-a3ee-a238c9bdadfa)

Note:  Make sure to select the FOXGLOVE project when entering Bills for purchases made on behalf of the project.  And example would be payments made for yard maintenance. 

In the example below, the **Income Statement - Date Range** report was selected and processed for the **FOXGLOVE** project.  By processing the report for the **FOXGLOVE** project, you can clearly see that the **Net Profit** for this rental property was $5,700 for the period of 1/1/2023 - 06/30/2023.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d457646e-b65b-43f8-860b-741544863cd8)