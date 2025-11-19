---
title: "eSign - AuthenticateUser"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21150291"
tags: ["General Information"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - AuthenticateUser | Constellation1 Customer Hub Used to retrieve a User Object using an encryptedToken, username, encrypted password, and a sal"
long_description: "eSign - AuthenticateUser | Constellation1 Customer Hub Used to retrieve a User Object using an encryptedToken, username, encrypted password, and a salt. URI GET rest/v1/authenticateuser/{userName}/{salt} Returns – A UserResponse containing a User Object in the User Array property. (See UserResponse in Appendix B) Parameters Example – C# [gdlr_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″] string uri = “rest/v1/authenticateuser/{0}/{1}”; string salt = “Z1s6aXNQpjQ7"
---

# eSign - AuthenticateUser | Constellation1 Customer Hub

Used to retrieve a User Object using an encryptedToken, username, encrypted password, and a salt.

URI GET rest/v1/authenticateuser/{userName}/{salt}

**Returns** – A UserResponse containing a User Object in the User Array property. (See UserResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/authenticateuser/{0}/{1}”;  
string salt = “Z1s6aXNQpjQ75wRX1ulI551sR1uHyg3YsOcPLeL9TaM”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
UserResponse userResponse;

uri = string.Format(uri, userName, salt);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken + “:” + encryptedPassword);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
userResponse = jss.Deserialize<RequestResponse\>(responseString);  
\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?