---
title: "eSign - CopySigningSession"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21150966"
tags: ["General Information"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - CopySigningSession | Constellation1 Customer Hub Copies a current signing session"
long_description: "eSign - CopySigningSession | Constellation1 Customer Hub Copies a current signing session. URI POST rest/v1/sessions/copy Returns – A SessionResponse containing a Signing Session Id and a Session Object. (See SessionResponse in Appendix B) Parameters Example – C# [gdlr_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″] string uri = “rest/v1/sessions/copy”; JavaScriptSerializer jss = new JavaScriptSerializer(); SessionResponse sessionResponse; Session copySession = new"
---

# eSign - CopySigningSession | Constellation1 Customer Hub

Copies a current signing session.

URI POST rest/v1/sessions/copy

**Returns** – A SessionResponse containing a Signing Session Id and a Session Object.  (See SessionResponse in Appendix B)

 **Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/sessions/copy”;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
SessionResponse sessionResponse;  
Session copySession = new Session();

copySession.SessionInfo = new SessionInfo();

copySession.SigningSessionId = signingSessionId;  
copySessionConfig.SessionInfo.TransactionId = “Copy Sign Session”;  
copySessionConfig.SessionInfo.TransactionTitle = “Copy Sign Session”;

CopyOptions copyOptions = new CopyOptions();  
copyOptions.Version = 0;  
copyOptions.RetainFields = true;

Signer signer;  
List<Signer\> signers = new List<Signer\>();

signer = new Signer();  
signer.SignerId = “signerId”;  
signer.EmailAddress = “emailAddress@docs.constellation1.com”;  
signers.Add(signer);

signer = new Signer();  
signer.SignerId = “signerId”;  
signers.Add(signer);

signer = new Signer();  
signer.EmailAddress = “emailAddress2@docs.constellation1.com”;  
signers.Add(signer);

copySession.Signers = signers.ToArray();

var data = new  
{  
copyOptions = copyOptions,  
session = copySession  
};  
string json = serializer.Serialize(data);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “POST”;  
request.ContentType = “application/json”;

using (StreamWriter writer = new StreamWriter(request.GetRequestStream()))  
{  
writer.Write(json);  
}

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
sessionResponse = jss.Deserialize<RequestResponse\>(responseString);

\[/gdlr\_notification\]