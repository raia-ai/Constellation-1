
# eSign - AutoLogMeIn.aspx | Constellation1 Customer Hub

### Auto Log Me In

Authorizes the passed in token and user to do different eSign UI related operations as specified in the URI parameters.  
Use this if you want to give your application a single sign-on (SSO) capability to access eSign UI. Currently, eSign doesn’t support either OAuth1/2 or SAML, so this is a workaround.

Here is a usage example.

https://{client name}.{environment}.esignonline.net/auth/AutoLogMeIn.aspx?user={eSign username}&token={eSign token}&ssid={ssid}&page={page name}

{client name}: Is your provided client name.  
{environment}: Is the environment you’re pointing to.  
{eSign username}: Is the email of your eSign account.  
{eSign token}: Is the generated eSign token.  
{ssid}: Is the Signing Session ID you pass if the provided page requires it as listed below.  
{page name}: Is one of the following.

*   “1”: Puts you on eSign step-1, requires SSID
*   “2”: Puts you on eSign step-2, requires SSID
*   “3”: Puts you on eSign step-3, requires SSID
*   “4”: Puts you on eSign step-4, requires SSID
*   “5”: Puts you on eSign step-5, requires SSID
*   “6”: Puts you on eSign step-6, requires SSID
*   “Cancel”: Puts you on the cancel session page, requires SSID
*   “Continue”: Puts you back on where you left off from steps 1-6 or the session status page, requires SSID
*   “Copy”: Puts you on the copy session page, requires SSID
*   “Support”: Puts you on administrator’s support page, if the specified user has administrator privileges
*   “Users”: Puts you on administrator’s users’ page, if the specified user has administrator privileges
*   “Archive”: Puts you on the archive page
*   “Contacts”: Puts you on the contact page
*   “History”: Puts you on the history (default) page
*   “Template”: Puts you on the template page
*   “emailpref”: Puts you on the email preference page

Was this article helpful to you?

Was this article helpful to you?