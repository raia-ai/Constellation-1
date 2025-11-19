---
title: eSign - PurgeSessionDocs – REST
---

# eSign - PurgeSessionDocs – REST

### PurgeSessionDocs

Purges a completed/expired/canceled session’s document files, then notifies the client of a webhook status change when completed.  
If the session is completed/approved, it will email all party members to give them a chance to download the documents beforehand, as after purging they will not have access to them anymore.

URI PUT rest/v1/sessions/{sessionId}/purge?returnURL={returnURL}&purgeNow={true/false}

**Returns** – A RequestResponse containing a string (“True” or “False”) representation of a Boolean indicating whether or not the call was a success or failure in the ReturnValue.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/sessions/{0}/purge?returnURL={1}&purgeNow={2}”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
RequestResponse requestResponse;

uri = string.Format(uri, signingsessionId, returnURL, purgeNow);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.ContentLength = 0;  
request.Method = “PUT”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
requestResponse = jss.Deserialize<RequestResponse>(responseString);

\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?