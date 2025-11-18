---
title: "Accounting - When Agent Changes Tax ID Numbers"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/15512709"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - When Agent Changes Tax ID Numbers The purpose of this article is to show how to account for instances when an agent changes their tax ID"
long_description: "Accounting - When Agent Changes Tax ID Numbers The purpose of this article is to show how to account for instances when an agent changes their tax ID number.  The most common way that agent earnings are reported to the IRS is by an agent's Social Security Number (SSN). But for many, there can be tax advantages to forming a corporation and having earnings reported to the IRS using an Employer Identification Number (EIN). If you intend to issue 1099s to your agents from your accounting program at"
---

# Accounting - When Agent Changes Tax ID Numbers

The purpose of this article is to show how to account for instances when an agent changes their tax ID number. 

The most common way that agent earnings are reported to the IRS is by an agent's Social Security Number (SSN).  But for many, there can be tax advantages to forming a corporation and having earnings reported to the IRS using an Employer Identification Number (EIN).  If you intend to issue 1099s to your agents from your accounting program at calendar year end, and your agent has had two or more tax ID numbers, it is important to maintain a separate agent profile record for each unique tax ID number they've had if you do not want to make manual edits to their 1099s at year end.  To add a second agent profile record, navigate to **Agents > Setup > Agents**.

A few other things to consider, when an agent changes their tax ID number, is whether or not to transfer their current agent charge balance, and whether or not you would like to honor their previous earnings to date for commission calculation purposes.   

If you want to transfer the agent's open agent charge balance, enter a lump sum agent credit, by navigating to **Agents > Processing > AR Credits/Payments**.  You can then click **Apply Payment** and **Auto-Apply** the credit to all open agent charges.  Then navigate to **Agents > Processing > Agent Charges** and enter a lump sum agent charge for the new agent entity.  

If you need to honor their earnings to date for commission calculation purposes, one way to accomplish this is to setup a **team** for the two agent entities, along with a **team commission plan**, and then enable system setting **COMMPLANALL**. 

To setup a new team, navigate to **Agents > Setup > Teams**.

After adding both agents as **Team Members**, enter a **De-active Date** for the old agent's profile record.  

To setup a new team commission plan, navigate to **Agents > Setup > Commission Plans**.

To enable system setting **COMMPLANALL**, navigate to **System > Setup > System Settings**.

After the new team and new team commission plan have been set up, and system setting **COMMPLANALL** has been enabled, assign each agent to the new commission plan and new team by navigating to **Agents > Setup > Agents > Commission** tab.  At this time, you may also like to terminate the old agent record by entering a **Termed/End Date** in the **Dates** section on the **Personal** tab of their profile record.  

If the terminated agent has existing **Pending** sales, you will need to remove the agent from the **Pending** sales and then add the new agent to the sale.  

Note:  If you have closed sales for the new agent entity and accidentally closed the transaction using the old agent entity, you have a few options.  You can void the agent check and reissue to the correct agent entity, you can edit each agent's 1099 manually at the end of the calendar year, or you can create a **Historical** sale to transfer commission from one agent entity to the other.