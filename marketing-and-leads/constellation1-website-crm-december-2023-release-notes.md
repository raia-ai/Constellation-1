
# Constellation1 Website & CRM December 2023 Release Notes

Production Release: December 5, 2023 

## Release Summary

#### Constellation1 CRM 

**Company Name in Action Plans:** Added company name to signature line of individual (agent) Action Plans.  
**Action Plan Updates:** Updated Action Plans for 2024. 

#### Constellation1 Websites

**RSS Feeds:** Added support for RSS feeds to website widgets with images and links.  
**Property Details Page:** Updated how listing photo thumbnails display.  
**Company Blog Posts:** Added option to not display company-level blog posts on agent websites.

#### Bug Fixes

**Websites:**  
Issue with social login.   
Auto-suggest not showing all options.   
Thumbnails not showing on Single Property Details pages. 

#### Technology Updates 

**Websites:**

Updated Elastic Search.   
Implemented DNS-prefetch.   
Removed Bootstrap 4.0.0-alpha.6. 

**CRM:**

Updated Telerik.dll for the RAD editor.  

## Constellation1 CRM 

Company Names in Action Plan Emails  
We’ve updated the emails sent as part of all agent-level Action Plans to include the agent’s company name in the agents' signature.   
The {{MY\_COMPANY\_NAME}} token also shows in the dropdown of available tokens when editing Action Plan emails.  
Including the name of the company the agent belongs to in drip marketing emails increases brand awareness for both the company and the agent. 

2024 Action Plan Updates

We’ve updated the following Action Plans for 2024:  
•    Homeowners Newsletter Series   
•    Annual Occasions  
These updated Action Plans are available now and ready to use. 

## Constellation1 Websites

Widgets Now Support RSS Feeds

We’ve added support for RSS feeds to website widgets. Company, office, and agent websites can now display the images and links shown in the RSS feed directly on the website wherever the user places the widget.

Listing Photo Display

We’ve updated how listing photos display on the Property Details page. The Property Details page will display the first four listing photos, with the first photo displaying as the main photo and photos 2, 3, and 4 displaying as thumbnails below the main photo. On mobile, the page will display the first three listing photos, including the main photo and photos 2 and 3 as thumbnails. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/12%20Dec%202023/2023-Oct-Website-PropDetailPagePhotos.png)

Company Blog Posts

We’ve updated Websites to allow companies to determine whether company-level blog posts will be posted on agent websites that have blogging enabled.  
Currently, when a company-level blog post is published, it will also be posted to agent blogs under Older Posts if the agent website has blogging enabled.  
With this update, companies can now keep company-level blogs from showing on agent blogs. This new functionality can be enabled at no extra cost. For more details, please contact your Constellation1 representative. 

#### Bug Fixes

**Website**  
1\. Fixed an issue with social login not working.   
Previously, some users experienced an error when using the social login feature to use their social media credentials to create or log in to their user accounts on the website.   
Now, this has been resolved. Website users will be able to create and log in to their accounts using their social media credentials. 

2\. Fixed an issue with autosuggest in the property search only showing three options.  
Previously, when using the Location field to search for properties, autosuggest would only display three options even when more options were available.  
Now, this issue has been resolved. Property search autosuggest will show all available options that match the search criteria.  

3\. Fixed an issue with the Single Property Details page (also known as Property Showcase) not showing thumbnails of the listing photos.   
Previously, on the Single Property Details page, thumbnails of the listing photos were not showing.   
Now, this issue has been resolved and listing photos will show on the Single Property Details page as expected. 

#### Technology Updates  

**Websites**  
1\. We’ve completed a significant performance optimization project for our Elastic Search cluster that powers Websites and CRM. 

2\. We’ve implemented DNS-prefetch to optimize cross-domain referenced resources, improving SEO and page load speed.

3\. We’ve removed Bootstrap 4.0.0-alpha.6 from Websites. 

**CRM**

1\. We've updated the Telerik.dll for the RAD editor to version 2023.3.1010.45.