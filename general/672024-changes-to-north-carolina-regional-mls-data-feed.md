
# 6/7/2024 - Changes to North Carolina Regional MLS data feed

We would like to inform you about an upcoming change that will impact your usage of the North Carolina Regional MLS data feed (OSN NorthCarolinaRegional).

On Friday June 7th, 2024, a vendor system conversion will take place for this feed. As a result, you will see additional 10 years of sold data and key values will change (ListingKey, ListAgentKey, ListOfficeKey, etc.). The OSN will remain the same during this conversion.

To ensure a seamless transition, you can now view the data using $reconvert=true parameter in your queries.  This parameter should not be used in production yet. Once the feed conversion goes live on Friday June 7th, 2024, the parameter will no longer have any effect.

Example:   
[https://listings.constellation1apis.com/OData/Property?$select=BuyerAgentKey,BuyerOfficeKey,ListAgentKey,ListingKey,ListOfficeKey&$filter=OriginatingSystemName](https://listings.constellation1apis.com/OData/Property?$select=BuyerAgentKey,BuyerOfficeKey,ListAgentKey,ListingKey,ListOfficeKey&$filter=OriginatingSystemName) eq 'NorthCarolinaRegional' and ListingId eq '100428026'

[https://listings.constellation1apis.com/OData/Property?$select=BuyerAgentKey,BuyerOfficeKey,ListAgentKey,ListingKey,ListOfficeKey&$filter=OriginatingSystemName](https://listings.constellation1apis.com/OData/Property?$select=BuyerAgentKey,BuyerOfficeKey,ListAgentKey,ListingKey,ListOfficeKey&$filter=OriginatingSystemName) eq 'NorthCarolinaRegional' and ListingId eq '100428026'&$reconvert=true

Was this article helpful to you?

Was this article helpful to you?