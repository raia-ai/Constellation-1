# eSign - CancelPurgingSession – REST

### CancelPurgingSession

Cancels a scheduled purge operation of a signing session that’s in “To Be Purged” state and puts it back to its prior state. You can call this as long as the session is still within the waiting period to be purged i.e. default 72 hours.

**Returns** – A RequestResponse containing a string (“True” or “False”) representation of a Boolean indicating whether or not the call was a success or failure in the ReturnValue.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″]\
string uri = “rest/v1/sessions/cancelPurging/{0}”;\
string responseString = string.Empty;\
JavaScriptSerializer jss = new JavaScriptSerializer();\
RequestResponse requestResponse;

uri = string.Format(uri, signingsessionId);\
HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);\
request.Headers.Add(“Authorization” , encryptedToken);\
request.ContentLength = 0;\
request.Method = “PUT”;\
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();\
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();\
requestResponse = jss.Deserialize(responseString);

\[/gdlr\_notification]

Was this article helpful to you?

Was this article helpful to you?
