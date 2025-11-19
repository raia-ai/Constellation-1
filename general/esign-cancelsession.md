---
title: "eSign - CancelSession"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21150938"
tags: ["General Information"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - CancelSession | Constellation1 Customer Hub Cancels a current signing session"
long_description: "eSign - CancelSession | Constellation1 Customer Hub Cancels a current signing session. URI PUT rest/v1/sessions/{sessionId}/cancel?returnURL={returnURL} Returns – A RequestResponse containing a string (“True” or “False”) representation of a Boolean indicating whether or not the call was a success or failure in the ReturnValue. (See RequestResponse in Appendix B) Parameters Example – C# [gdlr_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″] string uri = “rest/v1/sess"
---

# eSign - CancelSession | Constellation1 Customer Hub

Cancels a current signing session.

URI PUT rest/v1/sessions/{sessionId}/cancel?returnURL={returnURL}

**Returns** – A RequestResponse containing a string (“True” or “False”) representation of a Boolean indicating whether or not the call was a success or failure in the ReturnValue.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/sessions/{0}/cancel?returnURL={1}”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
RequestResponse requestResponse;

uri = string.Format(uri, signingsessionId, returnURL);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.ContentLength = 0;  
request.Method = “PUT”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
requestResponse = jss.Deserialize<RequestResponse\>(responseString);

\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?