
# eSign - GetUserById | Constellation1 Customer Hub

URI GET rest/v1/users/{id}

**Returns** – A UserResponse containing a User Object in the Users array. (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/users/{0}”;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
string responseString = string.Empty;  
UserResponse userResponse;

uri = string.Format(uri, id);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
userResponse = jss.Deserialize<UserResponse\>(responseString);

\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?