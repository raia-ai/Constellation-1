# eSign - CreateSession | Constellation1 Customer Hub

Starts a new signing session by sending a list of documents and signers to be used in the creation of a signing session. You can assign a template using the document.FormId, assign signer roles for each signer and specify signer authentication such as Knowledge Base Authentication (KBA).  **See Appendix B for a list of predefined signer roles available.**

URI POST rest/v1/sessions

**Returns** – A SessionResponse containing a Signing Session Id and an array of Session Object(s).  (See SessionResponse in Appendix B)

**Parameters**

**Example** – C#\
\[gdlr\_notification icon=”none” type=”color-border” border=”#31BEF9″ color=”#000000″]\
string uri = “rest/v1/sessions”;\
string signsessionId = string.Empty;\
string url = string.Empty;\
string autologinUrl = landingURL + “token={0}\&user={1}\&ssid={2}\&page={3}”;\
JavaScriptSerializer jss = new JavaScriptSerializer();\
List\<Document> documents = new List\<Document>();\
SessionResponse sessionResponse;

Session sessionConfig = new Session();\
sessionConfig.SessionInfo = new SessionInfo();

sessionConfig.SessionInfo.TransactionId = “New Session”;\
sessionConfig.SessionInfo.Title = “New Session”;\
sessionConfig.SessionInfo.UseSequence = 0;  //0 is non-sequential, 1 is sequential, 2 disables invites.\
sessionConfig.SessionInfo.AllowDelegation = true;\
sessionConfig.SessionInfo.CopyTo = “user1@docs.constellation1.com,user2@docs.constellation1.com”;\
sessionConfig.SessionInfo.Password = “password”;\
sessionConfig.SessionInfo.FirstSigner = true;\
sessionConfig.SessionInfo.EmailOptions = 3;

sessionConfig.SessionInfo.SendSignerInvites = false; // Set this parameter if you want invites to be sent or not when the session is started.

// Use this if you want your users to be redirected in eSign 2.0 when they hit the Send button on Step2\
sessionConfig.SessionInfo.SendSessionRedirectUrl = “[www.mysite.com](https://app.na3.teamsupport.com/www.mysite.com)”;

sessionConfig.SessionInfo.ExpiresOn = DateTime.Now.AddDays(20); //New property to specify session’s expiration date. 90 days in the future max.\
sessionConfig.SessionInfo.ReminderFrequencyDays = 2;  //New property to specify session reminder frequency.

Document documentConfig = new Document();\
documentConfig.FileName = “Test.docx”;\
documentConfig.FormId = “”; // This is the value given in the Templates configuration.

documentConfig.HasAnchorTags= true;  // New property telling eSign to process this document for Anchor Tags. Refer to Anchor Tags section.

documentConfig.AnchorTagsAdjustmentCategory= “predefined client specific category”;  // New property telling eSign to adjust the anchor tags of this document according to predefined adjustment values mapped to this category.

documentConfig.FileBytes = File.ReadAllBytes(@”D:\doc\Test.docx”);

documents.Add(documentConfig);\
sessionConfig.Documents = documents.ToArray();

Signer signer;\
List\<Signer> signers = new List\<Signer>();

signer = new Signer();\
signer.EmailAddress = “email1@docs.constellation1.com”;\
signer.FirstName = “FirstName”;\
signer.LastName = “LastName”;\
signer.SignerRole = “Seller 1”; //(see signer roles Appendix B)\
signer.AuthMethod = Authentication.KBA;\
signer.AuthenticationSettings = new eSignAPI.AuthenticationSettings();\
signer.AuthenticationSettings.Password = “password”;

// New flag to mandate a signer to upload a document before completing the session.

// You can also set this flag as part of the Properties parameter.

signer.MandateDocUpload = true;&#x20;

signer.AuthMethods = new List(); // Required to instantiate

signer.Properties = new Dictionary\<object, object>();  // Required to instantiate

// Here we’re assuming the template used has two merge fields one called “CompanyName” and the other “Job Title”. So, you supply their values this way.

signer.MergeFieldMapping = new Dictionary\<string, string>() { { “CompanyName”, “RED” }, { “Job Title”, “Manager” } };

signer.SignerEmailMessage = “email message”;

signer.SignerEmailSubject = “subject line”;

signers.Add(signer);

signer = new Signer();\
signer.EmailAddress = “email2@docs.constellation1.com”;\
signer.FirstName = “FirstName”;\
signer.LastName = “LastName”;\
signer.SignerRole = “Buyer 1”; //(see signer roles Appendix B)\
signer.AuthMethod = Authentication.KBA;

signer.AuthMethods = new List(); // Required to instantiate

signer.Properties = new Dictionary\<object, object>();  // Required to instantiate

signer.SignerEmailMessage = “email message”;

signer.SignerEmailSubject = “subject line”;

signers.Add(signer);

sessionConfig.Signers = signers.ToArray();

var data = new\
{\
userName = userName,\
session = sessionConfig\
};\
string json = serializer.Serialize(data);

HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host + uri);\
request.Headers.Add(“Authorization” , encryptedToken);\
request.Method = “POST”;\
request.ContentType = “application/json”;

using (StreamWriter writer = new StreamWriter(request.GetRequestStream()))\
{\
writer.Write(json);\
}

HttpWebResponse response = (HttpWebResponse)request.GetResponse();\
responseString = new StreamReader(response.GetResponseStream()).ReadToEnd();\
sessionResponse = jss.Deserialize\<RequestResponse>(responseString);signsessionId = sessionResponse.SigningSessionId.ToString();

url = string.Format(autologinUrl, encryptedToken, user, signsessionId, “continue”);

System.Diagnostics.Process.Start(url);

\[/gdlr\_notification]
