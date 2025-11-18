---
title: "eSign - GetSessionActionLogs"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21151214"
tags: ["General Information"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - GetSessionActionLogs | Constellation1 Customer Hub GetSessionActionLogs Retrieves an array of ActionLog object(s) by session Id"
long_description: "eSign - GetSessionActionLogs | Constellation1 Customer Hub GetSessionActionLogs Retrieves an array of ActionLog object(s) by session Id. An action log object contains a date, IP address, and a description for the action. URI GET rest/v1/sessions/{sessionId}/actionlogs Returns – An ActionLogResponse containing ActionLog Object(s) in the Actionlog array. (See RequestResponse in Appendix B) Parameters Example – C# [gdlr_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″]"
---

# eSign - GetSessionActionLogs | Constellation1 Customer Hub

### GetSessionActionLogs

Retrieves an array of ActionLog object(s) by session Id. An action log object contains a date, IP address, and a description for the action.

URI GET rest/v1/sessions/{sessionId}/actionlogs

**Returns** – An ActionLogResponse containing ActionLog Object(s) in the Actionlog array.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/sessions/{0}/actionlogs”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
ActionLogResponse actionLogResponse;

uri = string.Format(uri,signingsessionId);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
actionLogResponse = jss.Deserialize<ActionLogResponse\>(responseString);  
\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?