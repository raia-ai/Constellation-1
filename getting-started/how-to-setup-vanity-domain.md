
# How To Setup Vanity Domain

An Agent purchases domain for example from GoDaddy or similar and is redirecting to this vanity site by framing their website in iframe. This may cause issues with content not displaying as expected and other similar issues. 

Since this is an external website and not supported by RED platform we suggest to use the following way to setup your vanity domain.

**Steps for Client to follow for the configuration**

**BHHS**

1.  Within the DNS manager (ex: Godaddy)
    208.  Point the root A record to 208.93.240.77 (root domain)
    209.  Point the “m.” A record to 208.93.240.77 (mobile)
    210.  Point the “www.” A record to 208.93.240.77 (www.)
2.  Update the primary URL to reflect this domain

Since Real Living uses their own IP address, its going to be the following

**Real Living**

1.  Within the DNS manager (ex: Godaddy)
    208.  Point the root A record to 208.93.240.38 (root domain)
    209.  Point the “m.” A record to 208.93.240.38 (mobile)
    210.  Point the “www.” A record to 208.93.240.38 (www.)
2.  Update the primary URL to reflect this domain (RED can do this part)

**For Web01 Clients**

1.  Within the DNS manager (ex: Godaddy)
    208.  Point the root A record to 208.93.240.72 (root domain)
    209.  Point the “m.” A record to 208.93.240.72 (mobile)
    210.  Point the “www.” A record to 208.93.240.72 (www.)
2.  Update the primary URL to reflect this domain

 **\* If the client needs to support subdomains, then they need to create a star record that points to the IP’s above.**

Was this article helpful to you?

Was this article helpful to you?