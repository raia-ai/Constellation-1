# eSign- WebHook | Constellation1 Customer Hub

A **WebHook** is an HTTP POST callback that occurs when something happens. eSign implements WebHook to notify consumers of a signing session status update.

For a consuming application to receive a WebHook call from eSign, it needs to implement a REST service endpoint that accepts eSign’s JSON as explained here.

This code example is in .NET C#, but you can do the same thing in the language of your choice.

1.
   1. Create a WebApi Controller (call it anything you want) where you handle the WebHook call and process the message, like this.

public class WebhooksController : ApiController\
{

&#x20;   \[HttpPost]\
\[Route(“api/Webhooks/Process”)]\
public IHttpActionResult Process(\[FromBody]EsignView data)\
{\
var jsonData = JsonConvert.SerializeObject(data);

&#x20;       // Use data to handle your application’s workflow status.

&#x20;       return Ok($”Got your data of: {jsonData}”);\
}

}

1. Define your view model as follows. The Type can be either “SessionStatus” or “SignerStatus”, with the corresponding statuses defined below.

public class EsignView.\
{\
public EsignData Data { get; set; }\
}

public class EsignData\
{\
public Guid SigningSessionId { get; set; }

public Guid NewSigningSessionId { get; set; }

public Guid SignerId { get; set; }

public string Type { get; set; }

public int Status { get; set; }

public string Title { get; set; }

public string DeclinedReason { get; set; }

}

* You can also include the needed enumerations as follows.

public enum SessionStatusType\
{\
InDraft = 1,\
InSent = 2,\
Completed = 3,\
Cancelled = 4,\
Deleted = 5,\
InPaused = 6,\
Expired = 7\
}

* Also, define these signer statuses.

PendingInvite = 1;\
Invited = 2;\
InProgress = 3;\
Completed = 4;\
Cancelled = 5;\
Declined = 6;\
Delegated = 7;\
AuthenticationFailed = 8;

* Once you’ve set up your service and tested it, then provide your published URL to the eSignature team so they would set it up on their end to receive a WebHook call.
* A new property DeclinedReason has been added to the message body part of the signer decline webhook, this holds the reason selected by the signer as to why he/she declined to sign.
