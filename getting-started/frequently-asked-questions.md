
# Frequently Asked Questions | Constellation1 Customer Hub

**What is the difference between StandardStatus and MlsStatus?**

In the Real Estate Standards Organization (RESO) Data Dictionary, [StandardStatus](https://ddwiki.reso.org/display/DDW17/StandardStatus+Field) is a predictable set of possible values a listing may have during the listing life cycle. [MlsStatus](https://ddwiki.reso.org/display/DDW17/MlsStatus+Field), by contrast, is a value specific to the market in question and well known by business users. Each MlsStatus must map to a single StandardStatus. Multiple MlsStatus may map to a single StandardStatus.

**Why do I see listings with StandardStatus of "Off Market" but an MlsStatus that is clearly in conflict, like "Active?"**

This is common for situations where the listing does not sell (StandardStatus "Closed") but is no longer available - and our agreement with the source MLS does not allow us to determine the actual disposition of the listing. In these instances, the MlsStatus is the last known value before the listing was removed from the source, and the StandardStatus value "Off Market" was set by us. The latter is the one to honor.

**What is DOM versus CDOM?**

DOM stands for Days on Market. CDOM is Cumulative Days on Market. What constitutes a day on market is defined by the MLS or listing source business rules. CDOM accounts for days since a property was listed. DOM is CDOM minus days where the listing was, for any reason, not being shown or marketed.

**What is the difference between Condominium and Townhouse property types? Why do I see mixed usage of these terms in the Constellation API?** 

Condominium (“Condo”) is a widely accepted property type, despite being an ownership structure as opposed to a physical structure. Because all townhouse-style residences share common elements, they fit the typical definition of Condo and therefore it is tempting to use the terms interchangeably. But even if townhouses are condominiums, not all condominiums are townhouses. Recognizing this, the RESO data dictionary separates the two in [PropertySubType](https://ddwiki.reso.org/display/DDW17/PropertySubType+Field) . As MLS (Multiple Listing Service) adoption of RESO standards increases, the quality of data on this point in the API will follow.

**Do I have to adjust the Open House Start/End times I get from the API?**

No. It is the job of the API to understand the Open House date-time values coming from the source and translate those values - if necessary - to the local time at the property.

**If null value(s) exists in the API where one would normally expect a numeric value, is that to be interpreted as zero (0)?**

No. In general, a null value means no input from the source. The actual value could be zero, but if the source system does not affirmatively state as much, the API will not assume it. 

**OnMarketDate is a critical field. Why is it empty for so many listings?**

Though it seems counterintuitive, some MLSs do not supply this date to Constellation1. For this reason, we derive a date called DerivedOnMarketTimestamp, in UTC. DerivedOnMarketTimestamp is the first time a new listing is added to the Constellation1 system. There is one uncommon exception to note, which occurs when both of these are true: 1) the MLS does not supply a listing date, and 2) the MLS feed is new to Constellation1 and was recently loaded for the first time.

**ModificationTimestamp vs RawMlsModificationTimestamp**

The RawMlsModificationTimestamp time zone is aligned with that of the native MLS. The ModificationTimestamp however is in UTC. The raw prefixed field will get updated whenever there is a change from the MLS however the ModificationTimestamp field will get updated when there is a change from the MLS and/or if we initiate a change (mapping update, download/reprocessing of data etc.)

**How to filter string values in Odata syntax?**

In OData syntax, double quotations ("") are used to represent string literals. When constructing queries or filters in OData, you may need to use string values, and enclosing them within double quotations indicates that the content between the quotes is a string. For example, in a URL query parameter for filtering records based on a string property, you might have something like: Id eq '"1307V1-8931"'

**Where are my Closed/Sold listings in Texas?**

In general, US states (Texas being our example here) with non-disclosure rules prevent Multiple Listing Organizations from providing sold listings to clients with an IDX use case.  In some cases the entire listing record is held back; other times the record is provided but without the sale price. Other feed types ("Back Office", "VOW") may allow for these records, even in non-disclosure states.  In short, the listings are probably not missing; your use case may not be permitted to see them.