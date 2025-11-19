# eSign - DeleteSession | Constellation1 Customer Hub

### DeleteSession

Deletes a current signing session.

URI DELETE rest/v1/sessions/{sessionId}

**Returns** – A RequestResponse containing a string (“True” or “False”) representation of a Boolean indicating whether or not the call was a success or failure in the ReturnValue.  (See RequestResponse in Appendix B)

**Parameters continue**

**Example** – C#\
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″]\
string uri = “rest/v1/sessions/{0}”;\
string responseString = string.Empty;\
JavaScriptSerializer jss = new JavaScriptSerializer();\
RequestResponse requestResponse;

uri = string.Format(uri,signingsessionId);\
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);\
request.Headers.Add(“Authorization” , encryptedToken);

request.Method = “DELETE”;\
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();\
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();\
requestResponse = jss.Deserialize\<RequestResponse>(responseString);\
\[/gdlr\_notification]

Was this article helpful to you?

Was this article helpful to you?
