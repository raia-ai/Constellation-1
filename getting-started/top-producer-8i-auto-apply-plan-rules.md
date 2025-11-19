---
title: "Top Producer 8i: Auto Apply Plan Rules"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/28977240"
tags: ["Getting Started"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Top Producer 8i: Auto Apply Plan Rules Top Producer CRM understands the importance of following up with your leads"
long_description: "Top Producer 8i: Auto Apply Plan Rules Top Producer CRM understands the importance of following up with your leads. If you’re receiving too many leads to manually apply action plans to them all, Auto Apply Plan Rules enable you to automatically apply plans to new leads. You can define a unique rule for every unique combination of Lead Type, Source, Sub Source, and Other Source. For example, you can define a rule that will be applied to buyers who found you through your lawn sign, and a different"
---

# Top Producer 8i: Auto Apply Plan Rules

Top Producer CRM understands the importance of following up with your leads. If you’re receiving too many leads to manually apply action plans to them all, **Auto Apply Plan Rules** enable you to automatically apply plans to new leads.

You can define a unique rule for every unique combination of **Lead Type**, **Source**, **Sub Source**, and **Other Source**. For example, you can define a rule that will be applied to buyers who found you through your lawn sign, and a different rule for buyers who found you through your website.

Once a rule has been automatically applied to a plan, the activities contained within the plan will appear in the **My Business** section of the Dashboard as they come due.

  
**Creating an Auto Apply Plan Rule**

**Important:** Before setting up a rule, make sure you know ahead of time which plan you want to use, and what the Lead Type and Sources are for the incoming leads. If you create a rule with incorrect selections, the plan will not be applied as expected and could even be applied to the wrong leads.

Go to the **Calendar** main menu icon and click **Auto Apply Plan Rules**.

From the **Auto Apply Plan Rules** for Leads page, click the **Add Rule** link to open the **Add Rule** form.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/216a425d-1f05-49eb-90e1-3ae70d084a84)

From the **Lead Details** segment, select a **Lead Type** and the appropriate **Sources**. From the **Action Plans to Apply** segment, place a check mark next to the action plan(s) to assign the leads.

Rule Name

The **Rule Name** is only seen by you when setting up the rules, but is required and should be as descriptive as possible. Typically the name should describe where the lead came from. This field is only editable in the Add Rule form. Once a rule has been added, its name cannot be edited from the Edit Rule form.

Lead Type

The Lead Type you select will affect the types of Plans available for assigning.

Source

The Source is the primary method of identifying incoming leads. Lead providers that you define in the Lead Provider Setup tab (located in the **Preferences** menu) will automatically be available from this field.

Sub Source

The Sub Source field can be used to add an extra dimension to leads generated from your Web Lead Forms. The Sub Source field gives you the freedom to group all of your Web Leads under a single Source and create a single rule to handle them, while reserving the ability to specify special rules for leads with particular sub sources. If all Sub Sources are selected, the rule is applied based on the Source/Other Source values (i.e. it does not matter if an incoming lead contains a Sub Source value). If only “No Sub Source” is selected in this drop-down list, the rule is only applied if the incoming lead does not contain a Sub Source value.

Other Source

The Other Source field provides an additional level for identifying incoming leads. You can add values for this drop-down list on the **Lead Info** tab of a contact record.

If all Other Sources are selected, the rule is applied based on the Source/Sub Source values (i.e. it does not matter if an incoming lead contains an Other Source value). If only “No Other Source” is selected in this drop-down list, the rule is only applied if the incoming lead does not contain an Other Source value.

Action Plans to Apply

A listing of available action plans that are appropriate for the Lead Type you specified earlier.

Click the **Add Auto Apply Rule** button to save your rule. It then displays from the **Auto Apply Plan Rules** page with the new rule added.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/b63efca6-8163-4ab8-9f9c-e2dd9769159b)

**Note:** You can have only one rule per criteria, so if the rule you just created overlaps with another pre-existing rule, you will be offered the opportunity to either automatically modify the pre-existing rule so that it does not overlap the new one (no action required on your part), or modify the new rule that you just created.

Once the rule is set up, the next time a lead comes in from the specified Web page that meets the lead type and source criteria, the rule will automatically apply the action plan(s) you chose.

When comparing incoming leads to your criteria, Top Producer CRM joins the **Type**, **Source**, **Sub Source** and **Other Source** fields with AND operators, and joins any multiple picks that you made within those fields with OR operators. For example: **Type\[Buyer OR Seller\] AND Source\[Ad OR Lawn sign\]** would match buyers who responded to an ad, sellers who responded to an ad, buyers who responded to a lawn sign, and sellers who responded to a lawn sign.

Action plan activities can be viewed from **My Business** on the Dashboard, or by opening the contact record and going to the **Activities** tab.