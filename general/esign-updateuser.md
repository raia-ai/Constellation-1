---
title: eSign - UpdateUser | Constellation1 Customer Hub
---

# eSign - UpdateUser | Constellation1 Customer Hub

Updates the system user information.

URI PUT rest/v1/users

**Returns** – A UserResponse containing a User Object in the Users array.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/users”;  
string salt = “Z1s6aXNQpjQ75wRX1ulI551sR1uHyg3YsOcPLeL9TaM”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
UserResponse userResponse;

//The below example show all currently available fields allowed to be updates  
User userConfig = new User();  
userConfig.SystemUserId= “systemUserId”; //Required field  
userConfig.Username = “UserName”;  
userConfig.FirstName = “FirstName”;  
userConfig.LastName = “LastName”;  
userConfig.Password = encryptedPassword;  
userConfig.Company = “Company name”;  
userConfig.Region = string.Empty;  
userConfig.SubscriptionTypes = “Annual”;  
userConfig.TimeZoneId = “Pacific Standard Time (Mexico)”;  
userConfig.EmailSignature = “EmailSignature”;  
userConfig.StatusCode = UserStatusCodes.Active;

var data = new  
{  
salt= salt,  
user= userConfig  
};  
string json = serializer.Serialize(data);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “PUT”;  
request.ContentType = “application/json”;

using (StreamWriter writer = new StreamWriter(request.GetRequestStream()))  
{  
writer.Write(json);  
}

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
userResponse = jss.Deserialize<UserResponse\>(responseString);

//The below example show EmailSignature being update using the UserName required field  
User userConfig = new User();  
userConfig.Username = “UserName”; //Required field  
userConfig.EmailSignature = “EmailSignature”;

var data = new  
{  
salt= salt,  
user= userConfig  
};  
string json = serializer.Serialize(data);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “PUT”;  
request.ContentType = “application/json”;

using (StreamWriter writer = new StreamWriter(request.GetRequestStream()))  
{  
writer.Write(json);  
}

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
userResponse = jss.Deserialize<UserResponse\>(responseString);

//The below example show StatusCode being update using the SystemUserId required field  
User userConfig = new User();  
userConfig.SystemUserId= “systemUserId”; //Required field  
userConfig.StatusCode = UserStatusCodes.Active;

var data = new  
{  
salt= salt,  
user= userConfig  
};  
string json = serializer.Serialize(data);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “PUT”;  
request.ContentType = “application/json”;

using (StreamWriter writer = new StreamWriter(request.GetRequestStream()))  
{  
writer.Write(json);  
}

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
userResponse = jss.Deserialize<UserResponse\>(responseString);

\[/gdlr\_notification\]