---
title: "eSign - REST – SendSignerEmailInvites"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21150537"
tags: ["Troubleshooting"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - REST – SendSignerEmailInvites SendSignerEmailInvites URI PUT rest/v1/signers/invite Returns – A RequestResponse containing any errors in the D"
long_description: "eSign - REST – SendSignerEmailInvites SendSignerEmailInvites URI PUT rest/v1/signers/invite Returns – A RequestResponse containing any errors in the Details property. (See RequestResponse in Appendix B) Parameters Example – C# [gdlr_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″] string uri = “rest/v1/signers/invite”; JavaScriptSerializer jss = new JavaScriptSerializer(); RequestResponse requestResponse; Signer signer = new Signer(); List<Signer> signerList = new L"
---

# eSign - REST – SendSignerEmailInvites

### SendSignerEmailInvites

URI PUT rest/v1/signers/invite

**Returns** – A RequestResponse containing any errors in the Details  property. (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]

string uri = “rest/v1/signers/invite”;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
RequestResponse requestResponse;

Signer signer = new Signer();  
List<Signer\> signerList = new List<Signer\>();

signer.SignerId = “signerId”;  
signer.Sequence = 0;  
signer.FirstName = “firstname”;  
signer.LastName = “lastname”;  
signer.EmailAddress = “email address”;  
signer.StateCode = 0;  
signer.StatusCode = 1;  
signerList.Add(signer);

var data = new  
{  
signerList = signerList,  
signingSessionId = signingsessionId,  
returnURL = returnURL  
};  
string json = serializer.Serialize(data);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “PUT”;  
request.ContentType = “application/json”;

using (StreamWriter writer = new StreamWriter(request.GetRequestStream()))  
{  
writer.Write(json);  
}

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
requestResponse = jss.Deserialize<RequestResponse\>(responseString);

\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?