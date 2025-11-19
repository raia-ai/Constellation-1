# Constellation1 Website & CRM April 2024 Release Notes

Production Release: April 10, 2024&#x20;

## Release Summary

#### **Constellation1 Websites**

**Listing Traffic Report:** Added user permissions to manage access to the report. \
**Sold Listings:** Manage the number of photos to display on sold listings.\
**SEO Improvements:** Added H1 tags to various content pages.&#x20;

#### **Bug Fixes**

**CRM:** \
Issue with the Activities widget.&#x20;

**Website:**\
Issue with lead submissions being marked as spam.\
Issue with intermittent errors on the property detail page.&#x20;

#### **Technology Updates**

**Website:**\
Updated address parser.&#x20;

## Website Release Details

Listing Traffic Report \
We’ve updated the user permissions to restrict access to the Listing Traffic and Single Listing reports. \
Now, logged-in users running these reports will only see and access data for MLS boards they are associated with. \
This adds a layer of security and privacy to the report data.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/04%20April/2024-April-Website-ListingReport.jpg)

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/04%20April/2024-April-Website-ListingReport2.jpg)

Sold Listings Photo Display\
We have added a new setting that allows brokers and MLS websites to control how many photos are displayed on sold listings. \
Brokers and MLS websites can now choose to display the first 1 to 5 photos on sold listings. \
By default the first photos on sold listings are shown. \
Contact your Constellation1 representative if you would like to increase the number of photos shown on sold listings.

SEO Improvements\
We have added H1 tags to the Property Search Results page, State level Homes For Sale pages, and to the agent’s name on their CMS homepages. \
The H1 tag is the most important heading on a webpage, indicating to search engines like Google the main topic of that page. \
Adding H1 tags helps search engines understand and prioritize page content. \
Click the links below then open the source code of the page to see examples of the pages with new H1 tags,&#x20;

[Search results page](https://showcase.rdeskbw-stage.com/brittany-dancy/listing/listingsearchresultsonly.aspx?Search=d842f409-b1c0-44f4-88fc-a8fdd81e2258\&SearchType=AgentHome\&InternalAgentCd=\&OfficeCds=\&AgentHomePageSearchType=AllMyListings\&ListingType=\&ListingDistrictTypeID=\&PriorSales=\&Sort=6).\
[Homes For Sale](https://showcase.rdeskbw-stage.com/homes-for-sale).\
[Agent Homepage](https://showcase.rdeskbw-stage.com/sean-claude).

This update is only applied to the default page layouts.

## Bug Fixes

**CRM** \
1\. We fixed a issue that prevented the Save & Next button from working properly when users were creating activities. \
Previously, clicking Save & Next after adding an activity did not clear the form to allow entering additional activities. \
Now, this issue is fixed. Clicking Save & Next will now present a fresh form for users to add more activities.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/2024/04%20April/2024-April-CRM-ActivitySnapshot.jpg)

**Website**\
1\. Fixed an issue with the property detail page intermittently erroring.\
Previously, in some cases a property detail page would error and not display. \
Now, this issue has been resolved.

## Technology Updates&#x20;

**Website**\
1\. Updated the polygon search to now use Geo Shape.  Geo Polygon has been deprecated.
