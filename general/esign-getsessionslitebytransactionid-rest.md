
# eSign - GetSessionsLiteByTransactionId-REST | Constellation1 Customer Hub

### GetSessionsLiteByTransactionId

### _Use this call instead of GetSessionsByTransactionId and GetSessionsByTransactionIdMetadata. This call will eventually replace both of those calls._

Retrieves an array of SigningSession object(s) by an individual transaction Id, holding only some session header info in a paginated manner where the caller provides the page size, page number etc… The caller can control when to stop making the paginated call when it reaches the TotalCount value.

URI GET rest/v1/sessions/lite/{username}/{transactionId}/{pageSize}/{pageNum}/sortBy?colName={sortCol}&sortOrder={sortOrder}

**Returns** – A ResponseSessionInfoLiteView containing an array of Session Object(s).  (See ResponseSessionInfoLiteView in Appendix B)

**Parameters**

**Example** – C#  
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″\]  
string uri = “rest/v1/sessions/lite/{0}/{1}/{2}/{3}/sortBy?colName={3}&sortOrder={5}”;  
string responseString = string.Empty;  
JavaScriptSerializer jss = new JavaScriptSerializer();  
ResponseSessionInfoLiteView sessionResponse;

var pageSize = 50; // Max value  
var pageNum = 0; // 0-based from 0 to (totalCount – 1)  
var sortCol = “Title”;

uri = string.Format(uri, username, “Transaction Id”, pageSize, pageNum, sortCol, “asc”);  
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);  
request.Headers.Add(“Authorization” , encryptedToken);  
request.Method = “GET”;  
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();  
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();  
sessionResponse = jss.Deserialize<ResponseSessionInfoLiteView\>(responseString);

\[/gdlr\_notification\]