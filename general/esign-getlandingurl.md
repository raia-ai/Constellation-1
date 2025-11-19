# eSign - GetLandingURL | Constellation1 Customer Hub

Used to retrieve a landing URL for the user’s client eSign application based on a using an encrypted token. This is mainly used by the eSign Printer. &#x20;

URI GET rest/v1/landingurl

**Returns** – A RequestResponse containing the user’s landing URL string in the ReturnValue property.  (See RequestResponse in Appendix B)

**Parameters**

**Example** – C#

\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″]\
string uri = “rest/v1/landingurl”;\
string responseString = string.Empty;\
JavaScriptSerializer jss = new JavaScriptSerializer();\
RequestResponse requestResponse;

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);\
request.Headers.Add(“Authorization” , encryptedToken);\
request.Method = “GET”;\
request.ContentType = “application/json”;

HttpWebResponse response = (HttpWebResponse)request.GetResponse();\
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();\
requestResponse = jss.Deserialize\<RequestResponse>(responseString);

System.Diagnostics.Process.Start(autologinUrl);

\[/gdlr\_notification]

Was this article helpful to you?

Was this article helpful to you?
