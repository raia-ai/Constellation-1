---
title: "Contact Sync"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/28990168"
tags: ["Top Producer X CRM"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Contact Sync | Constellation1 Customer Hub Contact Sync allows you to sync your contacts with Google Contacts and Microsoft Contacts (Outlook, Office"
long_description: "Contact Sync | Constellation1 Customer Hub Contact Sync allows you to sync your contacts with Google Contacts and Microsoft Contacts (Outlook, Office 365). Contacts in the other system will be automatically brought to Top Producer® X CRM and future contact changes will be updated in both locations."
---

# Contact Sync | Constellation1 Customer Hub

Contact Sync allows you to sync your contacts with Google Contacts and Microsoft Contacts (Outlook, Office 365). Contacts in the other system will be automatically brought to Top Producer® X CRM and future contact changes will be updated in both locations.

  
**Disabling Top Producer® 8i CRM Contact Sync**  
If you previously set up Contact Sync or Calendar Sync in Top Producer® 8i CRM, you’ll need to disable that integration before setting up Contact Sync in Top Producer® X CRM. To disable the integration, follow these steps:

1.  Log in to Top Producer® 8i CRM.
2.  Go to Settings > Integrations > Edit Settings.
3.  Click Remove (Google/Outlook) Account.
4.  See Setting up Contact Sync below for how to set up Contact Sync in Top Producer® X CRM.

If you are a new user, or otherwise have not set up sync in Top Producer® 8i CRM, you may skip the above steps.

**Note:** After the integration is disabled, log out of Top Producer® X CRM and log in again to see the Contact Sync tab.

**Setting up Contact Sync**  
To set up Contact Sync, follow these steps:

1.  Log in to Top Producer® X CRM.
2.  Click Settings in the main menu, then the Contact Sync tab.
    
    ![](https://na3.files.teamsupport.com/TSData/WikiDocs/2472652/images/TopProducer%20-%20Wiki%20KB%20images/ContactSync/ContactSync1.png)
    
    If you don’t see the Contact Sync tab here, please find the answer in the FAQ below.
    
3.  Enter your email address and click Authorize.
    
    ![](https://na3.files.teamsupport.com/TSData/WikiDocs/2472652/images/TopProducer%20-%20Wiki%20KB%20images/ContactSync/ContactSync2.png)
    
4.  Sign in to your account if directed, and follow the prompts to grant Top Producer® X CRM any required permissions.
5.  When finished, you’ll be returned to the Contact Sync screen and the status will show as Initializing.
    
    ![](https://na3.files.teamsupport.com/TSData/WikiDocs/2472652/images/TopProducer%20-%20Wiki%20KB%20images/ContactSync/ContactSync3.png)
    

  
Feel free to navigate away from this screen and continue using Top Producer® X CRM while the sync processes. When the status on this page shows Running, the initial sync has finished and contacts will continue to sync automatically.

**Using Contact Sync**  
For contacts that were synced to Top Producer® X CRM, there is nothing further to do. Any changes made in either system will be automatically reflected in the other.

For contacts in Top Producer® X CRM that were added manually, imported from a file, or came from a lead provider you will need to click Add to Sync in the contact record to add the contact to the sync.

![](https://na3.files.teamsupport.com/TSData/WikiDocs/2472652/images/TopProducer%20-%20Wiki%20KB%20images/ContactSync/ContactSync4.png)

Or mass add contacts to the sync by selecting up to 50 contacts at a time on the Contacts page and clicking the Add to contact sync icon.

![](https://na3.files.teamsupport.com/TSData/WikiDocs/2472652/images/TopProducer%20-%20Wiki%20KB%20images/ContactSync/ContactSync5.png)

Contact information that syncs includes:

*   Name
*   Company
*   Title
*   Email
*   Address
*   Phone
*   Website

**Frequently Asked Questions**

**Q:** Why don't I see the Contact Sync tab?  
**A:** The Contact Sync tab will not be available if you previously set up Contact Sync or Calendar Sync in Top Producer® 8i CRM. Disable that integration by following these steps:

1.  Log in to Top Producer® 8i CRM.
2.  Go to Settings > Integrations > Edit Settings.
3.  Click Remove (Google/Outlook) Account.

Note: After the integration is disabled, log out of Top Producer® X CRM and log in again to see the Contact Sync tab

**Q:** Do I have to worry about duplicates?  
**A:** We do have duplicate contact checking BUT your contacts MUST have the following in their record in order to avoid duplicates:

*   First name
*   Last name
*   Email or phone number

If they don’t, you’ll get duplicates for the contacts that don’t have this info.

**Q:** What is the maximum amount of contacts I can sync?  
**A:** Contact Sync supports a maximum of 20,000 contacts.

**Q:** Can I set up contact sync with two contact sources (e.g. Outlook and Google)?  
**A:** To minimize the risk of duplicates you can only sync one source.

**Q:** What fields are synced?

**A:**

*   First name
*   Last name
*   Company
*   Job title
*   Birthday
*   Home address (no others)
*   Phone numbers
*   Fax numbers
*   Website

**Q:** What contact type and status will synced contacts have?  
**A:**

*   Type: Google, Microsoft etc.
*   Status: Future

  
**Q:** If I add a contact in Top Producer® X CRM, will it be added to my synced contact source?  
**A:** Not automatically. You must click the Add to Sync button as described above.

**Q:** What happens if I delete a synced contact in Top Producer® X CRM?  
**A:** The contact will be removed from Top Producer® X CRM and from the sync, but will not be deleted in the other system. If the contact is updated in the other system, it will be re-added to Top Producer® X CRM and the sync.

**Q:** What happens if I delete a contact in the other system?  
**A:** The contact will be removed from the sync but will not be automatically removed from Top Producer® X CRM.