---
title: eSign - CreateUser | Constellation1 Customer Hub
---

# eSign - CreateUser | Constellation1 Customer Hub

Creates a new user.

URI POST rest/v1/users

**Returns** – A UserResponse containing a User Object in the Users array.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/users”;  
string salt = “Z1s6aXNQpjQ75wRX1ulI551sR1uHyg3YsOcPLeL9TaM”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
UserResponse userResponse;

User createUser = new User();  
createUser.FirstName = “FirstName”; //Required field  
createUser.LastName = “LastName”; //Required field  
createUser.Username = “UserName”; //Required field  
createUser.Password = encryptedPassword; //Required field  
createUser.Company = “Company name”;  
createUser.Region = string.Empty;  
createUser.SubscriptionTypes = “Annual”;  
createUser.TimeZoneId = “Pacific Standard Time”;  
createUser.StatusCode = UserStatusCodes.Active;

var data = new  
{  
salt= salt,  
user= createUser  
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
userResponse = jss.Deserialize<UserResponse\>(responseString);

\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?