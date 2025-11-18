---
title: "eSign - REST – GetSignerInviteToken"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21150517"
tags: ["General Information"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - REST – GetSignerInviteToken GetSignerInviteToken URI GET rest/v1/signers/{signerId}/token Returns – A RequestResponse containing the encrypted"
long_description: "eSign - REST – GetSignerInviteToken GetSignerInviteToken URI GET rest/v1/signers/{signerId}/token Returns – A RequestResponse containing the encryptedToken string in the ReturnValue property. (See RequestResponse in Appendix B) Parameters Example – C# [gdlr_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″] string uri =“/v1/signers/{0}/token”; uri = string.Format(uri, id); RequestResponse requestResponse; HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host"
---

# eSign - REST – GetSignerInviteToken

### GetSignerInviteToken

URI GET rest/v1/signers/{signerId}/token

**Returns** – A RequestResponse containing the encryptedToken string in the ReturnValue property. (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]

string uri =“/v1/signers/{0}/token”;

uri = string.Format(uri, id);

RequestResponse requestResponse;

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
string responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
requestResponse = jss.Deserialize<RequestResponse\>(responseString);

\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?