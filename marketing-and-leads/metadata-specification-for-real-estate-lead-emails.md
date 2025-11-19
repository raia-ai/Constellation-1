
# Metadata Specification for Real Estate Lead Emails

<!DOCTYPE html ... >

<html xmlns= ... >

...

...

...

**Valid fields**

|     |     |     |     |
| --- | --- | --- | --- |
| **Field Name** | **Notes** | **Required** | **Example Content** |
| lead\_information\_version | Version number of the specification. | ✓   | “1.0” |
| lead\_source | Primary source of the lead. This can be any value. We recommend using a clear and consistent value for easy identification. If not provided, Top Producer will choose a sensible default value. |     | “Realtor.com” “AgentWebsite.com” |
| lead\_type | The type of lead. Valid values are “Buyer”, “Seller”, and “Renter”. If not provided, Top Producer will assume “Buyer”. |     | “Buyer” “Seller” “Renter” |
| lead\_name | The name of the lead. |     | “John Smith” |
| lead\_email | The email address of the lead. |     | “jsmith123@gmail.com“ |
| lead\_phone | The phone number of the lead. |     | “555-555-5555” |
| lead\_property\_address | The property address about which the lead is inquiring. |     | “123 Main Street, Los Angeles, CA 90210” |
| lead\_mls | The MLS number of the property address. |     | “A5712345” |
| lead\_message | A message from the lead to the agent. |     | “Hello, I am interested in… I have the following question…” |
| lead\_property\_city | The city of the property on the original lead inquiry. |     | “Los Angeles” |
| lead\_property\_state | The state of the property on the original lead inquiry. |     | “CA” |
| lead\_property\_zip | The zip code of the property on the original lead inquiry. |     | “90210” |
| lead\_max\_price | The max budget as identified by the client. |     | “500000” |
| lead\_primary\_zip | The primary zip code of the lead’s home search. May be different from the zip code of the property identified in the original inquiry. |     | “90211” |
| lead\_time\_frame | The buying/selling time frame as identified by the lead. |     | “3-6 months” “<90 days” “As Soon As Possible” |
| lead\_financing | How the lead plans to finance their purchase. |     | “financing-pre-approval” “already-pre-qualified” |
| lead\_assigned\_agent | The name of the agent the lead has been assigned to. |     | “Jenny Agent” |
| lead\_assigned\_agent\_email | The email of the agent that the lead has been assigned to. |     | “jennyagent@email.com” |
| lead\_assigned\_agent\_phone | The phone number of the agent that the lead has been assigned to. |     | “555-555-1234” |
| lead\_loan\_officer | The name of the loan officer that the lead has been assigned to. |     | “Bob Lender” |
| lead\_loan\_officer\_company | The company of the loan officer that the lead has been assigned to. |     | “Lender Financial” |
| lead\_loan\_officer\_email | The email of the loan officer that the lead has been assigned to. |     | “bob.lender@lenderfinancial.com” |
| lead\_loan\_officer\_phone | The phone of the loan officer that the lead has been assigned to. |     | “555-555-6789” |
| lead\_title\_officer | The name of the title officer that the lead has been assigned to. |     | “Sam Titles” |
| lead\_title\_officer\_company | The company of the title officer that the lead has been assigned to. |     | “beachside title” “fnf” |
| lead\_title\_officer\_email | The email of the title officer that the lead has been assigned to. |     | “sam.titles@email.com “ |
| lead\_title\_officer\_phone | The phone of the title officer that the lead has been assigned to. |     | “555-555-4567” |
| **_The specification also allows for up to 100 custom fields as follows:_** |     |     |     |
| lead\_$FIELDNAME$ | A custom field, such as lead\_min\_bedrooms or lead\_max\_price. Contact Top Producer at [support@topproducer.com](mailto:support@topproducer.com) if you would like FiveStreet or Top Producer CRM to parse any custom fields. |     | Any content. |