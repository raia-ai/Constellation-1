
# Constellation1 Website & CRM June 2023 Release Notes

Production Release: June 20, 2023 

## RELEASE SUMMARY

#### Constellation1 CRM 

**Office Dropdown:** Updated dropdown to search for and select offices.   
**Groups:** Updated how contacts are selected when sending emails.    
**Assigning Leads:** Improved Lead Assignment modal when manually assigning leads.   
**User Interface Updates:** Updated how pages respond when processing a user action.  

#### Constellation1 Websites

**Security:** Updated password standards for more secure passwords. 

**Forms Security:** Updated Captcha to v3.  
**SEO:** Updated listing landing pages for cities without listings.   
**Market Trend Report:** Updated subscription form to auto-populate the user’s name and email address. 

#### Bug Fixes

**CRM Mobile App:**   
Issue with the downloading app to certain Android phones. 

**Website:**  
Issue with scheduling blog posts.   
Listing Activity Summary Report layout.   
Contact Me button not showing on some agent websites. 

## CONSTELLATION1 CRM 

Searching and Selecting Offices  
We’ve created an option to add auto-suggest functionality to the office dropdown on various CRM pages, including the Lead Admin pages, for a more user-friendly experience.   
When the user clicks the office field, a dropdown displays showing the first 5 offices at the top of the list. If applicable, the user can then scroll down to show the first 50 offices.  
With this feature enabled, the user can now search within the dropdown. As the user types the name of an office in the field, the system will auto-suggest offices that match what the user typed.  
For companies with many offices, this improves system performance and allows users to find and select the desired office more quickly and easily.   
The feature is optional and is not enabled for all customers. We’ve identified customers who will benefit the most from this functionality and will enable it for them automatically. If you would like this feature enabled or would like to review and test the functionality, please contact your Constellation1 representative for more details. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/06%20June%202023/2023-June-CRM-Office.png)

Groups – Selecting Contacts

We’ve updated the Contact Groups module to allow a user to select all the contacts in a group when there are multiple pages of contacts. Previously, if the user selected all contacts, the system only selected the contacts displaying on the current page.

In the group email workflow, when an agent selects one or more contacts in a group, then clicks Send Email, the button expands to give the user the option to send the email to all contacts or just the selected contacts.

  
With this improvement, selecting All Contacts will send the email to everyone in the group, not just the contacts on the current page. In the example below, clicking All Contacts will send the email to all 151 contacts, not just the 5 displayed. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/06%20June%202023/2023-June-CRM-SelectAll.png)

Lead Assignment  
We’ve updated the Lead Assignment overlay to be more intuitive. The Search and Clear buttons are now disabled if there is no action for the user to take. When a user enters a name in the search box, the Search and Clear buttons will become active. 

  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/06%20June%202023/2023-June-CRM-LeadAssignl.png)

User Interface Updates  
We’ve updated our user interface for a more intuitive experience. Previously, while CRM was completing a background process after a user clicked a button, they could still scroll through and click other items on the page. These clicks interrupted the previous process, created confusion, and could overload the system, reducing performance and causing errors.

  
Now, we’ve improved how the system shows when it is processing. The user will see an overlay that says Processing… and they will no longer be able to scroll or click other items. Once the page has completely loaded, the user will be able to continue working.

  
  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/06%20June%202023/2023-June-CRM-Processing.png)

## CONSTELLATION1 WEBSITES

Stronger Password Standards  

We’ve improved security when logging in to Websites and CRM by creating new standards that will result in stronger passwords . These standards will apply to both agent passwords and the passwords consumers create on company, office and agent websites.  
The new password standards require passwords to have the following criteria:

*   A minimum of 8 characters
*   At least one uppercase letter
*   At least one lowercase letter
*   At least one number
*   At least one special character

This new standard is compatible with single sign-on and back office imports. This feature is optional and available to all customers at no cost on request. Please contact your Constellation1 representative for details.  

Forms Security   
We’ve improved security on customer-facing website forms by updating Captcha to version 3. Captcha detects possible malicious activity on a form and blocks it, so Website customers receive fewer potentially malicious submissions or spam responses. This updated version of Captcha ensures Website forms have the latest in form security. 

Improved SEO for Listing Landing Pages

We’ve improved search engine optimization value for listing landing pages in cities where there are currently no listings available. In some cases, search engines may assign these pages a low value if they do not return any results and don’t explain why.   
Now, when there are no listings in a city, we’ve updated the verbiage on the page to say, “We were unable to find listings in \[city, state\]”. Below this message, we will also display up to 25 listings that are closest to the searched city.   
For an example of how this looks, please [click here](http://showcase.rdeskbw-stage.com/homes-for-sale/TX/Dripping-Springs). 

Market Trend Report Subscription

We’ve updated the form for subscribing to the Market Trend Report. Now, it will automatically populate the user’s name and email address, making it easier for the user to subscribe to and receive regular email updates.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/06%20June%202023/2023-June-WebsiteMarketTrent.png)

## BUG FIXES

#### CRM Mobile App

1\. We fixed an issue with users being unable to download the CRM mobile app on older Android phones. 

Previously, when an agent would try to download the CRM mobile app using certain older Android phones, the agent may have received a message saying the app wasn’t available to download. The root cause was an issue with the certificate required by Google Play.

Now, we’ve resolved this issue for all versions of the CRM mobile app. Android users will be able to download it, even on older phones. 

#### Website

1\. We fixed an issue with scheduling blog posts.

Previously, after creating a blog post and scheduling it to be publish on a future date, the post would publish right away.

Now, when scheduling a blog post, the post will remain unpublished until the selected date, at which time it will be published on the public-facing website as expected. 

2\. We fixed an issue with the layout of the Listing Activity Summary Report. 

Previously, some items on the Listing Activity Summary Report page did not line up with the related content, and the calendar was not displaying correctly.

Now, we have updated the layout for the Listing Activity Summary Report so the page layout is clean, the text lines up with the relevant fields, and the calendar displays correctly. 

3\. We fixed an issue with the Contact Me button not showing in the agent website footer when a particular color scheme was selected.

Previously, when an agent selected a particular color scheme for their website, the Contact Me button didn’t display properly because the button color and the website design’s color scheme were the same. 

Now, the Contact Me button will display as expected in the footer for all color schemes.