
# CRM - Amazon SNS Integration Guide

**What is Amazon Simple Notification Service?**

Amazon Simple Notification Service (Amazon SNS) is a web service that makes it easy to set up, operate, and send notifications from the cloud.  It provides developers with a highly scalable, flexible, and cost-effective capability to publish messages from an application and immediately deliver them to subscribers or other applications. It is designed to make web-scale computing easier for developers. Amazon SNS follows the “publish-subscribe” (pub-sub) messaging paradigm, with notifications being delivered to clients using a “push” mechanism that eliminates the need to periodically check or “poll” for new information and updates.

FAQs:  [http://aws.amazon.com/sns/faqs](http://aws.amazon.com/sns/faqs)

**How does it work?**

RED creates a “topic” for your leads, which is an “access point” – identifying a specific subject or event type – for publishing messages and allowing clients to subscribe for notifications. Subscribers are clients interested in receiving notifications from topics of interest; they can subscribe to a topic or be subscribed by the topic owner, which is RED. Subscribers specify the protocol and end-point (URL, email address, etc.) for notifications to be delivered. When the publisher (RED) has information or updates to notify their subscribers about, RED will publish a message to the topic – which immediately triggers Amazon SNS to deliver the message to all applicable subscribers.

**What are the benefits?**

Amazon SNS offers several benefits making it a versatile option for building and integrating loosely coupled, distributed applications:

*   Instantaneous, push-based delivery (no polling)
*   Simple APIs and easy integration with applications
*   Flexible message delivery over multiple transport protocols

RED recognizes clients have various implementations with other vendors, which require fast integration with the RED platform.  Amazon SNS will push lead activity to subscribers rather than requiring subscribers to constantly query RED’s APIs for the same lead activity.

**What data is available?**

RED will send lead activity received from rW lead capture forms, profile updates and saving or editing a saved property or search.

See below for detailed field information.

**Configuration options**

By default, all lead activity will be sent to the client’s topic. However, RED has implemented a workflow where Lead Source / Sub-Source combinations can be used to limit the types of lead activity messages sent to the topic. This can be configured through the use of Lead Categories and Routing Rules in rDesk CRM.

For example, a client may want to distribute Saved Property activities but not Saved Searches from the Company website to the topic.

**How to subscribe to a topic**                           

A subscriber needs to be invited to subscribe to a topic. RED will help facilitate this process but requires the endpoint URL where all messages will be pushed.

Please see Step 3 in the following link to ensure you are setup to receive messages: [http://docs.aws.amazon.com/sns/latest/dg/SendMessageToHttp.html#SendMessageToHttp.confirm](http://docs.aws.amazon.com/sns/latest/dg/SendMessageToHttp.html#SendMessageToHttp.confirm)

**Message fields**

RED will send the following data as a JSON object within the Message field.

### Contact Model

| **Field Name** | **Type** | **Description** |
| --- | --- | --- |
| contactKey | GUID | RED’s internal contact ID |
| acceptedByMember | Boolean |     |
| company | String |     |
| firstName | String |     |
| fullName | String | Prefix + F + M + L + Suffix |
| jobTitle | String |     |
| lastName | String |     |
| middleName | String |     |
| namePrefix | String |     |
| nameSuffix | String |     |
| nickname | String |     |
| originatingSystemContactKey | String | Contact’s RED ID |
| originatingSystemName | String | “Real Estate Digital” |
| preferredContactMethod | String | Missing field indicates “No Preference” |
| preferredPhoneType | String | Missing field indicates “No Preference” |
| preferredTime | String | Missing field indicates “No Preference” |
| timestampEntered | DateTime | Creation date (UTC) |
| timestampModified | DateTime | Last modified date (UTC) |

### Address Model

| **Field Name** | **Type** | **Description** |
| --- | --- | --- |
| addressKey | GUID | Passed in URL |
| address1 | String |     |
| address2 | String |     |
| addressType | String |     |
| city | String |     |
| country | String |     |
| postalCode | String |     |
| stateOrProvince | String |     |
| timestampEntered | DateTime | Creation date (UTC) |
| timestampModified | DateTime | Last modified date (UTC) |

### Assignment Model

Assignment history of the contact.

| **Field Name** | **Type** | **Description** |
| --- | --- | --- |
| assignmentKey | GUID | Passed in URL |
| ownerKey | String |     |
| ownerType | String | Member or Office |
| timestampEntered | DateTime | Creation date (UTC) |

### Email Address Model

| **Field Name** | **Type** | **Description** |
| --- | --- | --- |
| emailAddressKey | GUID | Passed in URL |
| emailAddress | String |     |
| emailType | String | Primary, Secondary, Alternate |
| timestampEntered | DateTime | Creation date (UTC) |
| timestampModified | DateTime | Last modified date (UTC) |
| usedForAPM | Boolean |     |

### Lead Source Model

Captured activities that include a Lead Source / Sub-source. For example, a Saved Property or Saved Search event.

| **Field Name** | **Type** | **Description** |
| --- | --- | --- |
| leadSourceKey | GUID | Passed in URL |
| leadSource | String | Can be used to trigger Updated Leads routing options |
| subLeadSource | String | Can be used to trigger Updated Leads routing options |
| isLead | Boolean | If ever isLead = True, the lead will always be visible to assigned Owner and lead admins.   Once set to True, it cannot be changed.<br><br>If isLead is always False, the lead will only be visible to the assigned Member. |
| referrerURL | String | Referring URL from previous domain |
| originalReferrerURL | String | <ReferralSource/> |
| timestampEntered | DateTime | Creation date (UTC) |

### Note Model

| **Field Name** | **Type** | **Description** |
| --- | --- | --- |
| noteKey | GUID | RED ID |
| note | String |     |
| addedByMember | String |     |
| timestampEntered | DateTime | Creation date (UTC) |

### Phone Number Model

| **Field Name** | **Type** | **Description** |
| --- | --- | --- |
| phoneNumberKey | GUID | RED ID |
| phoneNumber | String |     |
| phoneNumberType | String | Home, Work, Mobile or Fax |
| timestampEntered | DateTime | Creation date (UTC) |
| timestampModified | DateTime | Last modified date (UTC) |

### Property Model

| **Field Name** | **Type** | **Description** | **Examples** |
| --- | --- | --- | --- |
| listingId | String (255) | MLS ID | 21417705 |
| listAor | String (50) | MLS Org ID | OABR |
| mlsStatus | String (50) |     | Status="Active" |
| listingContractDate | DateTime |     | 9/15/2014 12:00:00 AM |
| daysOnMarket | Integer |     | 396 |
| listPrice | Decimal |     | 3900000 |
| streetNumber | String (25) |     | 19414 |
| streetNumberNumeric | Integer |     | 19414 |
| streetDirPrefix | String (15) |     |     |
| streetName | String (50) |     | Mynster Springs |
| streetSuffix | String (25) |     | Road |
| city | String (50) |     | Council Bluffs |
| stateOrProvince | String (2) |     | IA  |
| country | String (2) |     | USA |
| postalCode | String (10) |     | 51503 |
| countyOrParish | String (50) |     | Pottawattamie |
| subdivisionName | String (50) |     | Lands |
| directions | String (1024) |     |     |
| listAgentFirstName | String (50) |     |     |
| listAgentLastName | String (50) |     |     |
| listAgentFullName | String (150) |     |     |
| listAgentMlsId | String (25) |     | 1772 |
| listOfficeMlsId | String (25) |     | 100887 |
| propertyType | String (50) |     | Single Family |
| propertySubType | String (50) |     | Ranch |
| lotSizeArea | Decimal |     | 9999 |
| lotSizeDimensions | String (150) |     | 101 Acres |
| poolFeatures | String (1024) |     |     |
| bedroomsTotal | Integer |     | 5   |
| bathroomsTotal | String (25) |     | 4   |
| garageSpaces | Decimal |     | 14  |
| stories | Integer |     | 1.00 |
| yearBuilt | Integer |     | 1983 |
| heating | String (1024) |     | Electric Heating, Propane |
| cooling | String (1024) |     | Central Air |
| interiorFeatures | String (1024) |     | InteriorFeatures |
| exteriorFeatures | String (1024) |     | Stone, Log |
| roof | String (1024) |     | Metal |
| listAgentEmail | String (80) |     | [Judy.Cleveland@cbshome.com](mailto:Judy.Cleveland@cbshome.com) |
| _listBrokerName_ | String (50) |     | CBSHOME Real Estate 159 Dodge |
| listBrokerPhone | String (16) |     | 402-934-1590 |
| _unitNumber_ | String (25) |     | F   |
| _contactNote_ | String (4000) |     | This is the ‘Note’ captured on the Lead Capture form |
| _propertyUrl_ | String(128) |     | [www.domain.com/12345](http://www.domain.com/12345) |