---
title: eSign - EncryptString | Constellation1 Customer Hub
---

# eSign - EncryptString | Constellation1 Customer Hub

Used to encrypt plain text into Rijndael 256-bit using a given salt.

URI GET rest/v1/encrypt/{plainText}/{salt}

**Returns** – A RequestResponse containing the encrypted string in the ReturnValue property.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#

string uri = “rest/v1/encrypt/{0}/{1}”;  
string salt = “Z1s6aXNQpjQ75wRX1ulI551sR1uHyg3YsOcPLeL9TaM”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
RequestResponse requestResponse;

uri = string.Format(uri, plainText, salt);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
requestResponse = jss.Deserialize<RequestResponse\>(responseString);

Was this article helpful to you?

Was this article helpful to you?