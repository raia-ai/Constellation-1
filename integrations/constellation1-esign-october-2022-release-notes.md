---
title: Constellation1 eSign October 2022 Release Notes
---

# Constellation1 eSign October 2022 Release Notes

Production Release: October 19, 2022 

## RELEASE SUMMARY

**eSignature Branding:** Added ability to customize company branding in eSign. 

**Bug Fixes**

## RELEASE DETAILS  

eSign Branding 

We’ve enhanced eSign to allow customized branding with company names and logos. 

When this is feature is enabled, we will replace the Constellation1 logo in the eSign application with your company logo and remove all references to eSign in outgoing emails. 

Please contact your Constellation1 representative for more information. 

  
Bug Fixes

1\. GPES-3192   
Fixed an issue with the dashboard displaying the incorrect time for signing sessions. 

Previously, after a signing session was sent, it would display on the dashboard with the incorrect time zone. In some cases, the session would not show after searching for it by time sent because it would default to the incorrect time and not fall within the span bring searched.

Now, the dashboard will sync to the time zone set in User Settings and display sent times correctly. 

  
2\. GPES-3398   
Fixed an issue with an error message showing for some signers after clicking the Review and Sign link in the email invite. 

Previously, after receiving a signing session invitation email and clicking the Review and Sign link, some signers would get an error message. 

Now, when signers click the Review and Sign link in the email, they will be taken to the first step of the signing session. 

  
3\. GPES-3414   
Fixed an issue with searching for emails by address on the dashboard. 

Previously, when a user searched for emails by email address on the dashboard, they were receiving a time-out error. 

Now, when searching for emails by address, the search will complete as expected. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Oct/2022-Oct-esign-DashboardSearch.png)

  
4\. GPES-3069  
Fixed an issue with Completed sessions showing a Next Signer on the Sessions page. 

Previously, on the Sessions page, Completed signing sessions were erroneously showing a name in the Next Signer column. 

Now, when a session has been completed, the Next Signer column will not show a name, as expected. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Oct/2022-Oct-esign-CompletedSession.png)

5\. GPES-3235   
Fixed an issue with the Designate Signer page apparently showing duplicate labels for signers.

Previously, on the Designate Signer page, some signer roles would appear to display twice. For example, the label Buyer 1 would appear two times. The root cause of this issue was that part of the signer role was being cut off, so the full label could not display for the second option. 

Now, the Designate Signer page will show the full label for the signer roles as expected. 

6\. GPES-3409  
Fixed an issue with a monthly subscription renewal error. 

Previously, when monthly subscriptions attempted to renew, the user would get an email stating the subscription could not be renewed due to incorrect billing information.  

Now, when a monthly subscription renews, it will renew without error, provided the billing information is still current.   

7\. GPES-3402  
Fixed an issue with the registration page for the free 90-day Constellation1 eSign trial.

Previously, the page may have frozen up when users tried to register for the trial. 

Now, the page will process the registration as expected.