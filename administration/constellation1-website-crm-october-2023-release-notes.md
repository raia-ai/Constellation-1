
# Constellation1 Website & CRM October 2023 Release Notes

Production Release: October 24, 2023 

## RELEASE SUMMARY

####   
Constellation1 Websites

**Property Search Results:** Updated the number of listings that display based on device.   
**Property Detail Page:** Updates listing photo display.

**Property Detail Page:** Updated breadcrumb navigation.   
**My Listings Display:** Updated configuration of the My Listings widget on the traditional agent websites.  

#### Bug Fixes

**Websites:**  
Ability to delete office photos.   
Deletion of testimonials. 

#### Technology Updates 

## CONSTELLATION1 WEBSITES

Property Search Results (SM3) 

We’ve updated the property search results page to display the number of listings that will fit on the screen of the device being used to conduct the search.   
The typical browser and screen resolution configurations support displaying the following number of listings:

*   Desktop: 24
*   Tablet: 12
*   Smartphone: 4

This update improves page load speed, uses less data on mobile devices, and improves SEO.  
This update is specific to Search Motif 3 (SM3).

Property Detail Page Listing Photo Display  
We’ve updated how listing photos display on the Property Detail page. On the web, the page will display the first 4 listing photos, with the first photo displaying as the main photo and photos 2, 3, and 4 displaying as thumbnails below the main photo.

On mobile, the page will display the first 3 listing photos, including the main photo and photos 2 and 3 as thumbnails. 

This update is specific to Search Motif 3 (SM3).

             ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/10%20Oct%202023/2023-Oct-Website-PropDetailPagePhotos.png)             ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/10%20Oct%202023/2023-Oct-Website-PropDetailPagePhotosMobile.jpg)

Property Detail Page Breadcrumb Navigation   
We’ve updated the breadcrumb navigation that displays above the listing description on the Property Detail page to show Home as the first item.   
Previously, we showed the company name as the first item. The Home button in the breadcrumb links back to the branded agent’s homepage.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/10%20Oct%202023/2023-Oct-Website-PropDetailPage.png)

Map Search Property Pins

We’ve updated the color of the property pins that display on the map search to indicate the status of a property.

*   Green pin: Active listings
*   Yellow pin: Pending and contingent listings
*   Red pin: Sold listings  
    

Depending on the zoom level of the map and number of listings to be displayed, the user may see the listing locations marked with dots or flags.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/10%20Oct%202023/2023-Sept-MapPins.png)

  
 Traditional Agent Websites – My Listings

We’ve updated My Listings on traditional agent branded websites to display the agents’ active and sold listings.   
When the user clicks My Listings, the page will display the agent’s active or pending listings. If the agent does not have active or pending listings, the button will display as My Sold Listings and link to the agents’ sold or closed listings. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/10%20Oct%202023/2023-Sept-MyListings.png)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2023/10%20Oct%202023/2023-Sept-MySoldListings.png)

The updated widget will display all listings where the agent had a role in the transaction.   
Those roles are:

*   Listing Agent
*   Co-Listing Agent
*   Buyer’s Agent  
    

This update only applies to traditional agent websites, not CMS websites.

####   
Bug Fixes

**Website**

1\. We fixed an issue with deleting office photos on the Manage Office Photos page.  
Previously, office managers with the correct user permissions were not able to delete office photos from their offices.   
Now, this issue has been resolved. Users with the correct permissions to manage assigned offices will be able to add or delete office photos. 

2\. We fixed an issue with testimonials being deleted when an agent added a new one.   
Previously, when an agent added a new testimonial to the testimonials widget on their website, the other testimonials were being deleted.  
Now, this issue has been resolved. Agents can add or edit testimonials as expected without them being deleted. 

#### Technology Updates 

In this new release notes section, we’ll talk about code- and system-level updates and changes that might not be visible to everyday users but are no less important to making our products even better.

**Websites**  
1\. We’ve removed references to older versions of Font Awesome. This update helps reduce how much code we use on webpages and improve page load speeds. 

2\. We’ve moved third-party scripts and CSS assets to a resource bundler widget. Some of these assets have been moved to Amazon Web Services (AWS) and to the CloudFront content delivery network (CDN). This reduces the amount of code used on webpages and helps improve page load speeds. 

3\. We’ve removed the reference to JQuery.browser and, where necessary, replaced it with feature detection. 

4\. We’ve upgraded Elastic/Kibana from version 6.8 to version 7.17.10 and are planning to upgrade to version 8 in the future. This improves data handling for listing search, auto-complete, public records, and news (blog) articles.