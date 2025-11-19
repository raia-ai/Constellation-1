---
title: Constellation1 Website & CRM March 2024 Release Notes
---

# Constellation1 Website & CRM March 2024 Release Notes

Production Release: March 13, 2024 

## Release Summary  

####   
**Constellation1 Websites**

**Location Search By Zip Code:** Added city name to auto suggest when searching by zip code.

**Listings Sold Price:** Added ability to hide the sold price of a property.   
**Blog Posts Preview:** Added preview option.

**Share Blog Posts:** Added share option to blog posts. 

**Canonical Tag Reference:** Added canonical tag reference to office and agent websites.  

#### **Bug Fixes**

**Website:**  
Blog post title image showing twice.  
Agent blog linking back to company website. 

#### **Technology Updates**

**Website:**   
Consolidated email servers.   
Updated Light Gallery 

Updated address parser to Smarty.

## Constellation1 Website Release Details

Location Search By Zip Code

We have updated the property search to now include the city name when users search by zip code.  
When users are searching for properties by zip code, the city name now appears alongside the zip code in the auto-suggest drop-down on the homepage property search and on the property search page. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/03%20March/2024-March-Website-ZipCodeSearch.jpg)

This update applies to property search motif 3 (SM3). 

Hide Sold Price 

We’ve added the option to hide the price on sold listings. The price field will display "$--" where the price would normally appear.   
To enable hiding sold prices, please contact your Constellation1 representative.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/03%20March/2024-March-Website-SoldPrice.jpg)

Preview Blog Posts

We’ve added a Preview button to the News article edit page allowing users to preview their blog posts before publishing them. 

  
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/03%20March/2024-March-Website-PreviewBlog.jpg)

Share Blog Posts  
We added a Share link to blog articles allowing viewers to share a blog post on their social media or send a link in email.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/03%20March/2024-March-Website-ShareBlog.jpg)

Canonical Tag Reference on Office and Agent Websites

To enhance search engine optimization, we have added canonical tag references to office and agent websites to clearly identify ownership of the pages.

## Bug Fixes  

**Website**  
1\. Fixed an issue with blog posts showing the header image twice.   
Previously, published blog posts displayed the header image twice, causing a malformed design.  
Now, this issue has been fixed so that now only one header image will be shown on each post.

2\. Fixed an issue with clicking Home on an agent branded blog post navigating the user to the company blog landing page.   
Previously, when viewing an agent-branded blog post, then clicking the Home link would redirect the users to the company blog landing page instead of the agent site.   
Now, clicking Home on an agent post navigates users back to the agent blog landing page.

##   
Technology Updates  

**Websites**  
1\. We’ve consolidated multiple email servers to a new and up to date SMTP server. 

2\. We’ve updated Light Gallery from version 1.0 to the latest 2.7.2 version. Light Gallery displays listing photos and thumbnail images on the listing detail page as well as in the full photo viewer.

 3. To improve accuracy and efficiency, we have updated the address parser for property search auto-suggestions to now use Smarty for parsing property addresses.