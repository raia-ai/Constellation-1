
# eSign - GetSession | Constellation1 Customer Hub

### GetSession

Retrieves a current signing session object from its session Id.

URI GET rest/v1/sessions/{sessionId}

**Returns** – A SessionResponse containing a Signing Session Id and an array of Session Object(s).  (See SessionResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/sessions/{0}”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
SessionResponse sessionResponse;

uri = string.Format(uri,signingsessionId);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
sessionResponse = jss.Deserialize<RequestResponse\>(responseString);  
\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?