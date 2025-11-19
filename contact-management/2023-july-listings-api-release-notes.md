
# 2023 July - Listings API Release Notes

**Public Records Data:**

We are please to announce the upcoming availability of public records data to launch in the upcoming quarter. Please contact us to review the public record data dictionary.

Constellation1 Ventures into International Markets  

In our pursuit of expansion, Constellation1 is making significant strides on the international front. We are excited to introduce several new data feeds from various regions across North America. These include internationally recognized MLS platforms such as OMNI MLS (Mexico, Peru, Colombia, etc.), Cayman Islands, Turks & Caicos, and Centris (French-speaking regions). Please contact our team if you are interested in adding these markets.  

Enhanced Office Resource Expansion from Member  

Constellation1’s Listings API now offers enhanced support for expanding the Office entity directly from the Member entity. This feature eliminates requiring separate queries and enables the retrieval of additional data through a single API call.  

  "value": \[ 

        { 

            "Id": "1307CV47277", 

            "AltMemberMlsId": "21759616", 

            "MemberFirstName": "Jane", 

            "MemberKey": "13078954276739", 

            "MemberLastName": "Doe", 

            "MemberMlsId": "CV9999", 

            "MemberMlsSecurityClass": "Agent Level", 

            "MemberStateLicense": "012341234", 

            "MemberStatus": "Active", 

            "MemberType": "REALTOR Salesperson", 

            "ModificationTimestamp": "2022-12-06T18:28:25+00:00", 

            "EntityEventSequenceNumeric": 638059481020000000, 

            "OfficeKey": "1307829041646", 

            "OfficeMlsId": "9999", 

            "OriginalEntryTimestamp": "2022-11-14T14:07:52", 

            "OriginatingSystemName": "CRMLS", 

            "RawMlsModificationTimestamp": "2022-11-23T17:16:41", 

            "Office": \[ 

                { 

                    "Id": "1357913579", 

                    "AltOfficeMlsId": "399999", 

                    "DataSourceId": 0, 

                    "MainOfficeKey": "12345678912345", 

                    "MainOfficeMlsId": "OC9999", 

                    "ModificationTimestamp": "2023-04-13T09:00:10+00:00", 

                    "EntityEventSequenceNumeric": 638169732090000000, 

                    "OfficeAddress1": "123 Main Street Ste. 200", 

                    "OfficeBrokerKey": "1357913579", 

                    "OfficeBrokerMlsId": "OFFNAME!", 

                    "OfficeCity": "San Ramon", 

                    "OfficeCorporateLicense": "01878277", 

                    "OfficeKey": "134567890123", 

                    "OfficeMlsId": "9999", 

                    "OfficeName": "ABC REALTY OF CALIFORNIA INC", 

                    "OfficePhone": "8885555555", 

                    "OfficePostalCode": "94583", 

                    "OfficeStateOrProvince": "CA", 

                    "OfficeStatus": "Active", 

                    "OriginalEntryTimestamp": "2017-02-16T09:26:16", 

                    "OriginatingSystemName": "CRMLS", 

                    "RawMlsModificationTimestamp": "2023-04-12T22:21:20", 

                    "MainOfficeName": "ABC Realty of California Inc" 

Geo-Spatial Searches 

Listings API now supports Geo-Spatial searches to support creating custom boundaries. Listings in the API, which also contain geospatial information are represented with the RESO data dictionary fields and presented in the OData response.  

1.  [Longitude](https://ddwiki.reso.org/display/DDW17/Longitude+Field) 
    

2.  [Latitude](https://ddwiki.reso.org/display/DDW17/Latitude+Field)  
    

 For search purposes, a field named “Location” represents both Latitude and Longitude. 

Constellation1’s API supports two styles of Geospatial search:

1\. POLYGON

 A Polygon is a series of coordinates (longitude/latitude pairs) which can represent basic shapes, typically a Polygon’s first and last coordinates match to form a closed shape. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/2d373aea-3864-4d9e-835d-0055b3bb6989) 

Breaking down the OData $filter expression: 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c977fad1-51d7-40d8-be12-aa18314d8fa6) 

The API supports the “geo.intersects” canonical function which accepts two parameters, firstly the field (“Location”) representing the latitude/longitude of each listing and second the Polygon shape where listings are located within.

2\. RADIUS

 A radius search is a listing which is located within distance from a fixed point on a map. 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/1e961195-d280-46d7-bd6c-0e32bd8fb881) 

The function used for radius search “geo.distance” accepts two parameters representing the field (“Location”) and a fixed point (latitude/longitude), followed by a less than operator with a distance value represented by meters.  

More information on OData [Geospatial search](https://www.odata.org/blog/geospatial-properties/) 

New Frequently Asked Questions (FAQ) 

Based on valuable feedback from our customers, we have created a comprehensive list of Frequently Asked Questions. We are pleased to announce this launch designed to provide the easiest and most efficient way to find answers to common queries.