
# eSign - GetSessionsByTransactionId | Constellation1 Customer Hub

### GetSessionsByTransactionId

### _This call will get deprecated in the near future, the preferred call to make is the paginated call_ GetSessionsLiteByTransactionId _which will get released in December 2019._

Retrieves an array of SigningSession object(s) by an individual transaction Id.

URI GET rest/v1/users/{userName}/transactions/{transactionId}

**Returns** – A SessionResponse containing an array of Session Object(s).  (See SessionResponse in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/users/{0}/transactions/{1}”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
SessionResponse sessionResponse;

uri = string.Format(uri, username, “Transaction Id”);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
sessionResponse = jss.Deserialize<SessionResponse\>(responseString);

\[/gdlr\_notification\]

Was this article helpful to you?

Was this article helpful to you?