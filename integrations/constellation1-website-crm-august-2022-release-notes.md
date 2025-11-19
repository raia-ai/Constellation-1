# Constellation1 Website & CRM August 2022 Release Notes

Production Release: August 2, 2022&#x20;

## RELEASE SUMMARY

####

**Constellation1 CRM**&#x20;

**To-Do Notes:** To-Do notes now display in the Notes section.

**Groups:** New bulk email sends to contact groups.&#x20;

#### **Constellation1 Websites**

**Automated Blog Posts:** New Constellation1 Digital Marketing Suite integration allowing Websites users to automate blog posting.

#### **Bug Fixes**

#### CRM:&#x20;

Deleting tasks on the calendar\
Listing Activity widget\
Listing placeholder photos

#### Website:

Removed placeholder text\
Walk Score error\
For Sale, For Lease setting in Listing Editor\
Incorrect price on Listings Carousel\
Links from CRM to the website&#x20;

##

CONSTELLATION1 CRM&#x20;

To-Do Notes

We’ve improved the availability of notes created as part of a To-Do action item. When a To-Do is created, the user can add notes to it. Previously, these notes only displayed in the To-Do itself.&#x20;

Now, when a To-Do is completed, the notes will be added to the Notes section and the contact record history. This update is available in both the desktop and mobile versions of CRM.&#x20;

Send Bulk Emails from Groups

We’ve improved the Groups module so users can send emails to multiple contacts in one action.&#x20;

&#x20;On the Groups page, we’ve added a Send Email button.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/08%20August%202022/2022-July-CRM-GroupEmail1.png)

When clicked, a modal will open with the options to Email All Contacts in the Group or Email Selected Contacts.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/08%20August%202022/2022-July-CRM-GroupEmail2.png)

Once the contacts have been selected, the user clicks Email. A second modal will open to the Quick Email drafting page, where the user can write their message and then click Send to send it.\
&#x20;

## CONSTELLATION1 WEBSITES

Automated Blog Posting

We’re excited to announce the release of a new feature that seamlessly and automatically updates your agent websites with blog posts.

We’ve integrated Websites and our Digital Marketing Suite to provide fresh, relevant content for your audience to help drive traffic to your website and improve your site’s search engine optimization and ranking.

This new automated blog posting integration is a subscription service that can be made available to agents who have an active Constellation1 CMS website. Once enabled, we will automatically publish industry news, blog posts, and listing content that is branded to the agent’s website.

* We publish two categories of blog post content according to different schedules:\
  Real estate-related news, information, and advice –posted once a week.&#x20;
* Listing-related posts – these posts specifically promote the agent’s listings. Whenever a new listing hits the market or has recently been sold, a blog post announcing it will be posted with pictures and information pulled directly from the MLS.

More details related to implementation are forthcoming. \
&#x20;

## BUG FIXES

#### **CRM**&#x20;

1\. Fixed an issue with completing or deleting tasks on the calendar.&#x20;

Previously, on the Task page of the calendar, if the user clicked Complete Selected or Delete Selected and no selections were made, a gray screen would open with no option to close it.&#x20;

Now, if no selection has been made when clicking Complete Selected or Delete Selected, the system will alert the user.&#x20;

2\. Fixed an issue with Lead Activity dashboard widget text showing up incomplete and distorted.

Previously, if the name of the lead activity exceeded the number of characters for the widget, the text would be distorted and cut off. \
Now, we’ve added formatting to the text and added an ellipsis ( … ) to the end to indicate there is more text to the label.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/08%20August%202022/2022-July-CRM-LeadActBefore.png) \
Before \
&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/08%20August%202022/2022-July-CRM-LeadActAfter.png)\
After

3\. Fixed an issue where the listing placeholder photo was missing from the Properties tab. \
Previously, if a listing didn’t have a photo, the listing photo space on the Properties tab would show a blank space.\
&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/08%20August%202022/2022-July-CRM-NoPhoto.png)\
Before

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/08%20August%202022/2022-July-CRM-NoPhotoAfter.png)

After

Now, if a listing does not have any listing photos, the system will display a No Photo image as a placeholder. \
&#x20;

#### **Website**

1\. Fixed an issue with the placeholder text that was displayed in various URL fields on the CMS Pro website admin.&#x20;

Previously, some of the URL fields in content widgets would show a URL as a placeholder. This information was not intuitive or helpful.

Now, to simplify the display and avoid confusion, we have removed the placeholder text.

2\. Fixed an issue with setting a listing to For Sale or For Lease in the Listing Editor.&#x20;

Previously, when setting a listing to either For Sale or For Lease in the Listing Editor, the setting was not being saved.&#x20;

Now, the toggle to set a listing to For Sale or For Lease is reliable and will save the correct setting.&#x20;

3\. Fixed an issue with Walk Score not showing on the property detail page for some customers.&#x20;

Previously, in some use cases, the Walk Score would not show on the Property Detail page. This issue affected customers who opted to use JQuery v3.6 on their website. &#x20;

Now, the issue with JQuery v3.6 has been corrected and the Walk Score will show on the Property Detail page.&#x20;

4\. Fixed an issue with the incorrect price showing on the Sold Listings carousel.&#x20;

Previously, properties on the Sold Listings carousel displayed the listing price and not the sale price.&#x20;

Now, the Sold Listings carousel will show the listing’s sale price.&#x20;

5\. Fixed an issue with links in the CRM only going to the CMS Dashboard.&#x20;

Previously, when clicking the Saved Property or Saved Search link in the CRM, the user was taken to their CMS dashboard.&#x20;

Now, when the user clicks a link to access a consumer’s saved search or saved property, they will be taken to the correct location.
