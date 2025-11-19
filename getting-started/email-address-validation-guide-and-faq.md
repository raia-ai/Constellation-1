# Email Address Validation Guide and FAQ

## Constellation1 Website and CRM&#x20;

### Overview

Branding is an important part of any business, and you work hard to promote your unique brand and get your name known. We take great care when sending emails to your leads and clients and want to put you first. When we send emails on your behalf, we want those emails to come from you.

Constellation1 has implemented a new service that will determine if we are allowed to send emails using the From address associated with your custom agent, office or company email domain.

Emails sent from the CRM will do the following check,&#x20;

* If we have authority, the email will be sent from the sender’s email address.&#x20;
* If we do not have authority, the email will be sent from our system address.&#x20;
  * Our CRM system address is rdeskcrm@rdesk.com&#x20;

Emails sent from the website system will do the following check,&#x20;

* If we have authority, the email will be sent from the sender’s email address.&#x20;
* If we do not have authority, the system will check the “Custom From Email Address”.&#x20;
* If we are unable to send from this address the email will be sent from our system address.
* Our website system address is notifications@rdesk.com&#x20;

This feature also helps the recipient email servers to determine the validity of the email message they receive.&#x20;

To allow our system to send emails on your behalf, a simple update is needed to your custom domain. With your domain registrar, you need to add an SPF record to the DNS record of your domain.

This is not as scary as it sounds. Your registrar (such as GoDaddy or other company with which you registered your domain) will be able to help you make this update.&#x20;

Benefits include:&#x20;

* Agent and company branding
* Highest delivery success rate
* Email services recognize the sender as an authorized, legitimate sender
* Emails are more likely to land in the recipient’s inbox

### Updating Your Domain

Updating your domain is easy, however we recommend contacting your registrar’s support desk to help ensure the SPF file is setup without any issues. &#x20;

This section is designed to give you a high-level understanding of the steps to add the SPF record to your domain. Different registrar sites will have a different workflow, so the steps here may not be exact for your situation.&#x20;

Steps:\
Login to your registrar site. \
Contact their support team. (Optional) \
Navigate to the domain you use to send emails from.\
Navigate to the DNS Record for that domain. \
&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/Charlie/Email%20SPF%20FAQs/DNS-Record.png)

Within the DNS record you may need to add a “TXT” record. The TXT record may include Type, Host, TXT Value and TTL fields.\
In the TXT Value field, add the following,\
v=spf1 ip4:208.93.240.0/24 \~all

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/Charlie/Email%20SPF%20FAQs/Txt-Record.png)

If you need to define the Host, simply enter the @ symbol, or check with your registrar for the correct host. \
Then Save the record. It should now show as part of your DNS record.&#x20;

### FAQ&#x20;

**Q:** What is an SPF record? \
**A:** Sender Policy Framework (SPF) is used to authenticate the sender of an email. An SPF record is a text file with a list of IP addresses that are allowed to send email on your behalf and is part of your domain DNS record. &#x20;

**Q:** Why should I add an SPF record to my domain? \
**A:** The SPF record allows you to give Constellation1 email servers permission to send email using your email address as the sender and place your address in the From field.&#x20;

**Q:** Does this affect the recipient of the email?\
**A:** No, the person or group receiving the email message will not see any difference. However, the email server that receives the email will be able to check the email and determine if the email message is from an authorized sender. Because they are able to check and validate the sender, your emails are more likely to land in the recipient’s inbox and not in the spam folder.&#x20;

**Q:** What are the emails being sent from my email address?\
**A:** Some of the most common emails sent on your behalf can include the following

* Saved search
* Saved property
* Drip marketing messages

**Q:** What do I need to do to have emails sent from my email address?\
**A:** Your registrar will be able to assist you with adding the SPF record to your domain. Add the following as a text record to your domain DNS record. \
v=spf1 ip4:208.93.240.0/24 \~all \
&#x20;\
**Q:** Why am I not able to have emails sent from my Gmail or Yahoo email account?\
**A:** Free and community-based emails are not supported due to you not being the registered owner of the domain. In this example the domain is @gmail.com and @yahoo.com.

**Q:** What happens if someone replies to my emails?\
**A:** Reply emails will go to the sender. When emails are sent, we include the “reply to” value to be the senders primary email address. Regardless of Constellation1 having authority to send on your behalf or not. This ensures the reply emails will go to the sender. &#x20;

**Q:** Are there any other benefits?\
**A:** Yes, this will allow recipient email servers to recognize Constellation1 as a legitimate sender resulting in a higher delivery rate. &#x20;

**Q:** Are there other resources where I can get more information?\
**A:** Yes, this site has some good information about SPF files. \
[https://dmarcian.com/what-is-spf/](https://dmarcian.com/what-is-spf/)
