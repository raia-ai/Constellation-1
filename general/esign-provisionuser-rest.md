---
title: "eSign - ProvisionUser-REST"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/21150908"
tags: ["General Information"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "eSign - ProvisionUser-REST | Constellation1 Customer Hub Activates and Deactivates the user belonging to the given SystemUserId"
long_description: "eSign - ProvisionUser-REST | Constellation1 Customer Hub Activates and Deactivates the user belonging to the given SystemUserId. URI PUT rest/v1/users/provisionUser Returns – A UserResponse indicating success or failure. Parameters Example – C# string uri = “rest/v1/users/provisionUser”; string sysUserId = “The GUID for the user in hand”; string salt = “test123”; string responseString = string.Empty; JavaScriptSerializer jss = new JavaScriptSerializer(); UserResponse userResponse; var data = new"
---

# eSign - ProvisionUser-REST | Constellation1 Customer Hub

Activates and Deactivates the user belonging to the given SystemUserId.

URI PUT rest/v1/users/provisionUser

**Returns** – A UserResponse indicating success or failure.

**Parameters**

**Example** – C#

string uri = “rest/v1/users/provisionUser”;  
string sysUserId = “The GUID for the user in hand”;  
string salt = “test123”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
UserResponse userResponse;

var data = new  
{  
salt= salt,  
systemUserId= sysUserId,

userStatus = 1  
};  
string json = serializer.Serialize(data);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “PUT”;  
request.ContentType = “application/json”;

using (StreamWriter writer = new StreamWriter(request.GetRequestStream()))  
{  
writer.Write(json);  
}

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
userResponse = jss.Deserialize<UserResponse>(responseString);

Was this article helpful to you?

Was this article helpful to you?