
# eSign - GetSessionsByTransactionIdMetadata-REST | Constellation1 Customer Hub

### GetSessionsByTransactionIdMetadata

### Use this method ONLY if:

1.  You are already integrated with eSign using the GetSessionsByTransactionId and want a quick change to gain more performance by switching to this call.
2.  You don’t have the time to integrate with the paginated call of GetSessionsLiteByTransactionId which requires client changes on your end, and which will eventually be the only one available to use down the road. So, plan eventually to integrate with GetSessionsLiteByTransactionId as your final solution.

### _This call will also get deprecated in the near future after the GetSessionsByTransactionId, and the preferred call to make is the paginated call_ GetSessionsLiteByTransactionId _which will get released in December 2019._

Retrieves an array of SigningSession object(s) by an individual transaction Id.

URI GET rest/**v2**/users/{userName}/transactions/{transactionId}

**Returns** – A SessionResponse containing an array of Session Object(s).  (See SessionResponse in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/**v2**/users/{0}/transactions/{1}”;  
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