---
title: "eSign - GetExpiredSessions-REST"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21151201"
tags: ["General Information"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - GetExpiredSessions-REST | Constellation1 Customer Hub GetExpiredSessions Retrieves a paginated list of expired session IDs for the given token"
long_description: "eSign - GetExpiredSessions-REST | Constellation1 Customer Hub GetExpiredSessions Retrieves a paginated list of expired session IDs for the given token, page size and page number. URI GET rest/v1/sessions/expired/{pageSize}/{pageNum} Returns – A SessionLiteBucketView containing the archived signing session IDs, along with the total count. (See SessionLiteBucketView in Appendix B) Parameters Example – C# [gdlr_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″] string ur"
---

# eSign - GetExpiredSessions-REST | Constellation1 Customer Hub

### GetExpiredSessions

Retrieves a paginated list of expired session IDs for the given token, page size and page number.

URI GET rest/v1/sessions/expired/{pageSize}/{pageNum}

**Returns** – A SessionLiteBucketView containing the archived signing session IDs, along with the total count. (See SessionLiteBucketView in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/sessions/expired/{0}/{1}”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
SessionLiteBucketView sessionLiteBucket;

uri = string.Format(uri,pageSize, pageNum);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
sessionLiteBucket = jss.Deserialize<SessionLiteBucketView>(responseString);  
\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?