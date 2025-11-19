
# Constellation1 Website & CRM August 2023 Release Notes

Production Release: August 15, 2023 

## RELEASE SUMMARY

####   
Constellation1 Websites + CRM

**Google Analytics:** Updated tracking code for Google Analytics 4 (GA4). 

#### Constellation1 Websites

**Agent Search Results Page:** Updated logic for View My Listings link.   
**Agent Branded Listing Results:** Updated button wording.  
**Custom Forms:** Added a GA4 Action Name field.

**Listing Detail Page:** Removed Coming Soon price from price history.   
**Architecture:** Optimized scripts for faster page loads and improved SEO.

#### Bug Fixes

**CRM Desktop:**   
Issue with saving action plans with a new task. 

**CRM Mobile App:**   
Issue with push notifications on Android phones.   
Issue with downloading the CRM Mobile App on Android phones.   
Issue with time zones displayed in reminder notifications. 

## CONSTELLATION1 WEBSITES + CRM

Google Analytics   
We’re pleased to announce that we’ve finished upgrading all client instances of Constellation1 Websites and CRM to Google Analytics 4 (GA4), the next-generation website analytics platform.   
To learn more about the new GA4 tracking code and the switch to Google Analytics 4, visit Google’s dedicated page here.

[Google Analytics 4](https://support.google.com/analytics/answer/11583528?hl=en#:~:text=Until%20July%201%2C%202023%2C%20you,for%20at%20least%20six%20months "Google Analytics 4") 

If you still have any questions or would like more information about the new Google tracking code, please contact your Constellation1 representative.  

##   
CONSTELLATION1 WEBSITES

  
View My Listings Link   
We’ve updated the logic for the View My Listings link on the agent search results page and the Agent Detail landing page.   
This new logic considers whether the agent has active listings or not. If the agent does not have active listings, rather than linking to an empty page, the View My Listings link will redirect to the My Sold Listings page, showing sold properties where the agent represented either the buyer or seller.   
This improves the user experience and is better for search engine optimization (SEO). 

  
![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/08%20August/2023-Aug-AgentSearch.png)

Agent Listings Page  
We’ve updated the button names for two buttons at the top of the agent branded listings page to reduce confusion and provide a better user experience.  
On the agent’s My Listings page, the two buttons now read My Active Listings and My Sold Listings, with the number of corresponding listings provided in parentheses. Clicking either button will filter the listings accordingly.

 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/08%20August/2023-Aug-AgentPropSearchResults.png)

Custom Form Label for GA4   
We’ve added a GA4 Action Name field to custom forms.   
The name entered in this field will show on the Google traffic reports, providing more insight into how customers are using your website and forms. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/08%20August/2023-Aug-Website-CustomForm.png)  
Listing Detail Page  
We’ve removed the Coming Soon price from the price history section on the listing detail page. Consumers will now see the assessed price in the history and not the projected price.  

Architecture Improvements   
We’ve updated various website scripts that are responsible for various functions, like loading images efficiently, for a better user experience and improved SEO.  
For example, on the Property Detail page, we’ve removed the photo gallery carousel that showed below the main listing photo.

We made these improvements to: 

*   Company Home page
*   Property Search Results page
*   Property Detail page
*   Listing carousels 

We’ve also added new schema.org meta data fields and improved existing meta data with language relevant to real estate giving search engines more details related to each property and a better understanding of the content.

Now, all webpages load faster and handle images more efficiently on both desktop and mobile, coupled with improved meta data for a better user experience and improved SEO.

[Click here](https://schema.org/docs/faq.html) to learn more about schema.org.

## BUG FIXES

CRM Desktop  
1\. We fixed an issue with the Action Plan Manager displaying an error when trying to save an action plan after adding a new task.   
Previously, a user might have received an error message when trying to save an action plan after modifying it by adding a new task.   
Now, this issue has been resolved and users can add new tasks to action plans as expected. 

CRM Mobile App  
1\. We fixed an issue with CRM Mobile App push notifications not working on some versions of Android phones.  
Previously, push notifications were not being received on newer versions of Android phones.  
Now, this issue has been resolved and all Android phones will receive push notifications as expected.  

2\. We fixed an issue with users getting an error message when downloading the CRM Mobile App on newer versions of Android phones.  
Previously, when a user with a newer version of an Android phone would try to download the CRM Mobile App, they would get a message saying, “This app isn't available for your device because it is made for an older version of Android.”  
Now, this issue has been resolved. All Android users can now download the CRM Mobile App.  

3\. We fixed an issue with reminder notifications displaying Pacific time, regardless of the user’s set time zone.   
Previously, To-Do and Task reminder notifications displayed deadlines in Pacific time, causing confusion among those who weren’t in the Pacific Time Zone.   
Now, this issue has been resolved and notifications will display the correct time for the time zone the user selected in CRM desktop.