---
title: eSign - GetTokenUserNamePassword | Constellation1 Customer Hub
---

# eSign - GetTokenUserNamePassword | Constellation1 Customer Hub

### GetTokenUserNamePassword – To be Deprecated, use GetToken instead

Used to retrieve an encryptedToken based on user credentials as opposed to an encrypted API key.

URI GET rest/v1/tokenusernamepassword/{userName}/{salt}

**Returns** – A RequestResponse containing the encryptedToken string in the ReturnValue property.  The encryptedToken will be an encrypted value of your token. This will be sent with almost every call to the web service regarding user handling and session creation. (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/tokenusernamepassword/{0}/{1}”;  
string salt = “Z1s6aXNQpjQ75wRX1ulI551sR1uHyg3YsOcPLeL9TaM”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
RequestResponse requestResponse;

uri = string.Format(uri, userName, salt);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedPassword);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
requestResponse = jss.Deserialize<RequestResponse\>(responseString);  
\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?