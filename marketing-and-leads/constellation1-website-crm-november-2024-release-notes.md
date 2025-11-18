---
title: "Constellation1 Website & CRM November 2024 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/25393289"
tags: ["Marketing & Leads"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 Website & CRM November 2024 Release Notes Production Release: November 20, 2024 Release Summary Constellation1 Websites Customer Profil"
long_description: "Constellation1 Website & CRM November 2024 Release Notes Production Release: November 20, 2024 Release Summary Constellation1 Websites Customer Profile: Improved usability of the customer profile page. Properties REST API: Added RESO Seller, Concessions Amount to the API. Bug Fixes  Website: Issue with saving agent profile without a username.  Issue with state field not populating when creating a new listing in Listing Editor.  Website Release Details Customer Profile We've enhanced the customer"
---

# Constellation1 Website & CRM November 2024 Release Notes

Production Release: November 20, 2024

## Release Summary

#### **Constellation1 Websites**

**Customer Profile:** Improved usability of the customer profile page.  

**Properties REST API:** Added RESO Seller, Concessions Amount to the API.

#### **Bug Fixes** 

**Website:**  
Issue with saving agent profile without a username.   
Issue with state field not populating when creating a new listing in Listing Editor. 

## Website Release Details

Customer Profile  
We've enhanced the customer profile page to improve the overall experience.   
Now, when customers make updates, they will remain on the profile page and receive an on-screen confirmation that their changes were successfully saved. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/11%20November/2024-Nov-Website-ProfileSucess.png)

Customers can unsubscribe from saved search and property email notifications by unchecking the relevant options under the Notification Preferences, on their dashboard settings. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/11%20November/2024-Nov-Website-ProfileUnsubscribe.png)

When a customer opts out, they will also be unsubscribed from all emails, including marketing messages and action plans. The user will be added to the Opt-Out list in the CRM.

Administrators can later opt them back in through the Opt-Out page in the CRM.

  
Additionally, the "Update Password" button will only become active once the customer has populated all the required password fields when updating their password.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/11%20November/2024-Nov-Website-ChangePW.png)

Properties REST API

We’ve updated the properties REST API to now includes the RESO seller concessions amount, allowing users to retrieve the concession amount as a numerical value wherever that data is available.

The following has been added to the API:  
•    concessionsYn  
•    concessionsAmount  
•    concessionsPriceType  
•    concessionsClosingCost  
•    concessionsPropertyImprovementCosts  
•    concessionsFinancingCosts  
•    concessionsBuyersBrokerFee  
•    concessionsOtherCosts  
•    concessionsComments

## Bug Fixes  

**Website**

1\. We fixed an issue with saving an agent profile without a username. 

Previously, the website's admin was saving agent and user accounts without a required username

Now, field validation has been updated and this issue has been resolved.   
 

2\. Fixed an issue with the state field not being populated automatically in the Property Editor when creating a new pocket listing.

Previously, In the property editor, the state field did not automatically populate with the available state or province options when creating a new pocket listing.

Now, this issue has been resolved. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/11%20November/2024-Nov-Website-ListingEditor.png)

3\. Fixed an issue with the Listing Rollup Report not returning data. 

Previously, the Listing Rollup Report failed to return any data, the user was presented with the message “No Data Available”. 

Now, this issue has been resolved. 

4\. Fixed an issue that was limiting meta descriptions to 160 characters.

Previously, there is system setting that when enabled, limits a meta description to 160 characters. This limit was being enforced regardless of the setting. 

Now, this issue has been resolved. When this setting is not enabled, the meta description will not be enforced.