---
title: "1/16/2024 - Upcoming System Conversion for Real Estate Board of New York (REBNY) Data Feed"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/26000945"
tags: ["Troubleshooting"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "1/16/2024 - Upcoming System Conversion for Real Estate Board of New York (REBNY) Data Feed We would like to notify you of an upcoming change that may"
long_description: "1/16/2024 - Upcoming System Conversion for Real Estate Board of New York (REBNY) Data Feed We would like to notify you of an upcoming change that may impact your use of the Real Estate Board of New York (REBNY) data feed. Key values in all resources will be changing (ListingKey, MemberKey, OfficeKey, etc.) as a result of this conversion. Additionally, all IDs will be changing as well (ListingId, MemberMlsId, OfficeMlsId, etc.) You will be able to view the former ListingId in the newly converted"
---

# 1/16/2024 - Upcoming System Conversion for Real Estate Board of New York (REBNY) Data Feed

We would like to notify you of an upcoming change that may impact your use of the **Real Estate Board of New York (REBNY)** data feed.

**Key values in all resources will be changing (ListingKey, MemberKey, OfficeKey, etc.)** as a result of this conversion.

**Additionally, all IDs will be changing as well (ListingId, MemberMlsId, OfficeMlsId, etc.)**

You will be able to view the former **ListingId** in the newly converted data feed using the field **SourceSystemKey**. 

For example,

        {

            "ListAgentFullName": "John Smith",

            "ListAgentMlsId": "12345",

            "**ListingId**": "RLS5678910", **_(New ListingId)_**

            "ListOfficeMlsId": "9876",

            "ListOfficeName": "ABC Real Estate",

            "**SourceSystemKey**": "ABC-918273645", **_(Former ListingId)_**

            "UnparsedAddress": "123 Front Street"

        }

For agent and office IDs, **prefixed values will be removed**. 

**Before:**

            "ListAgentMlsId": "RBNY-**12345**",

            "ListOfficeMlsId": "RBNY-**9876**",

**After:**

            "ListAgentMlsId": "**12345**",

            "ListOfficeMlsId": "**9876**",