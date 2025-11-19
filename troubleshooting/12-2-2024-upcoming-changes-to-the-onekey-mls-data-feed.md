---
title: 12-2-2024 - Upcoming Changes to the OneKey MLS Data Feed
---

# 12-2-2024 - Upcoming Changes to the OneKey MLS Data Feed

On Monday December 2nd, 2024, a vendor system conversion will be implemented for this feed. To ensure a smooth transition, we’ve made the updated data available for early access. You can preview the changes by including the **$reconvert=true** flag in your queries. Please note that your current OSN remains unchanged.

Here’s what to expect with this new instance of the data feed:

1.  **Listings with ListAOR as LIBOR:** The ListingId will now include a prefix "L".
    
2.  **Listings with ListAOR as HGAR:** For entries where the OriginalEntryTimestamp is after 2024-11-12, the ListingId will no longer include the "H" prefix.
    
3.  **New Listings Post-Migration:** Listing IDs will be numeric and will not carry any prefixes. This will be true of both HGAR and LIBOR.
    
4.  **MemberMlsId Changes:** Some MemberMlsIds will be updated. Legacy IDs can be found under AltMemberMlsId.
    

If you have any questions or need assistance, our team is here to help.

Was this article helpful to you?

Was this article helpful to you?