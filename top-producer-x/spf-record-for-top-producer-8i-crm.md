# SPF record for Top Producer 8i CRM

**SPF record for Top Producer 8i CRM**

When using a personal domain name for your email address to send emails from within Top Producer® 8i, there is sometimes a need to create an SPF record.

**Standard Top Producer SPF record**

The current SPF record for Top Producer products is:

v=spf1 include:\_spf.topproducer.com -all

This Standard Top Producer SPF record will only allow for the sending of email for the domain through the Top Producer servers. If the domain is used for sending email through other mail servers, those mail servers plus Top Producer will need to be all added into the same SPF record (see below).

**SPF record for multiple mail servers including Top Producer**

This SPF record will allow for the sending of email for the domain through the Top Producer mail servers and other email servers used for sending email. Below are some popular mail servers that we were able to obtain, to the best of our knowledge, their respective current SPF record information plus the Top Producer mail servers.

For GoDaddy:\
v=spf1 MX include:secureserver.net include:\_spf.topproducer.com -all\
&#x20;

For Google:\
v=spf1 MX include:\_spf.google.com include:\_spf.topproducer.com -all\
&#x20;

For Microsoft / Office365 / Outlook:\
v=spf1 include:spf.protection.outlook.com include:\_spf.topproducer.com -all\
&#x20;

**Note:** This is only for Top Producer 8i. You should not do this if your only sending through a connected email in Top Producer X.

If you have any questions, please contact support by clicking the 'Chat Now' bubble located at the bottom right corner of your Top Producer 8i CRM, or email [support@topproducer.com](mailto:support@topproducer.com)
