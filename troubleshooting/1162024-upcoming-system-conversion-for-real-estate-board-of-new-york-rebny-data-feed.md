# 1/16/2024 - Upcoming System Conversion for Real Estate Board of New York (REBNY) Data Feed

We would like to notify you of an upcoming change that may impact your use of the **Real Estate Board of New York (REBNY)** data feed.

**Key values in all resources will be changing (ListingKey, MemberKey, OfficeKey, etc.)** as a result of this conversion.

**Additionally, all IDs will be changing as well (ListingId, MemberMlsId, OfficeMlsId, etc.)**

You will be able to view the former **ListingId** in the newly converted data feed using the field **SourceSystemKey**.&#x20;

For example,

&#x20;       {

&#x20;           "ListAgentFullName": "John Smith",

&#x20;           "ListAgentMlsId": "12345",

&#x20;           "**ListingId**": "RLS5678910", _**(New ListingId)**_

&#x20;           "ListOfficeMlsId": "9876",

&#x20;           "ListOfficeName": "ABC Real Estate",

&#x20;           "**SourceSystemKey**": "ABC-918273645", _**(Former ListingId)**_

&#x20;           "UnparsedAddress": "123 Front Street"

&#x20;       }

For agent and office IDs, **prefixed values will be removed**.&#x20;

**Before:**

&#x20;           "ListAgentMlsId": "RBNY-**12345**",

&#x20;           "ListOfficeMlsId": "RBNY-**9876**",

**After:**

&#x20;           "ListAgentMlsId": "**12345**",

&#x20;           "ListOfficeMlsId": "**9876**",
