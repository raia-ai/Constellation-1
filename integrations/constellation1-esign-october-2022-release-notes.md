# Constellation1 eSign October 2022 Release Notes

Production Release: October 19, 2022&#x20;

## RELEASE SUMMARY

**eSignature Branding:** Added ability to customize company branding in eSign.&#x20;

**Bug Fixes**

## RELEASE DETAILS

eSign Branding&#x20;

We’ve enhanced eSign to allow customized branding with company names and logos.&#x20;

When this is feature is enabled, we will replace the Constellation1 logo in the eSign application with your company logo and remove all references to eSign in outgoing emails.&#x20;

Please contact your Constellation1 representative for more information.&#x20;

Bug Fixes

1\. GPES-3192 \
Fixed an issue with the dashboard displaying the incorrect time for signing sessions.&#x20;

Previously, after a signing session was sent, it would display on the dashboard with the incorrect time zone. In some cases, the session would not show after searching for it by time sent because it would default to the incorrect time and not fall within the span bring searched.

Now, the dashboard will sync to the time zone set in User Settings and display sent times correctly.&#x20;

2\. GPES-3398 \
Fixed an issue with an error message showing for some signers after clicking the Review and Sign link in the email invite.&#x20;

Previously, after receiving a signing session invitation email and clicking the Review and Sign link, some signers would get an error message.&#x20;

Now, when signers click the Review and Sign link in the email, they will be taken to the first step of the signing session.&#x20;

3\. GPES-3414 \
Fixed an issue with searching for emails by address on the dashboard.&#x20;

Previously, when a user searched for emails by email address on the dashboard, they were receiving a time-out error.&#x20;

Now, when searching for emails by address, the search will complete as expected.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Oct/2022-Oct-esign-DashboardSearch.png)

4\. GPES-3069\
Fixed an issue with Completed sessions showing a Next Signer on the Sessions page.&#x20;

Previously, on the Sessions page, Completed signing sessions were erroneously showing a name in the Next Signer column.&#x20;

Now, when a session has been completed, the Next Signer column will not show a name, as expected.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Oct/2022-Oct-esign-CompletedSession.png)

5\. GPES-3235 \
Fixed an issue with the Designate Signer page apparently showing duplicate labels for signers.

Previously, on the Designate Signer page, some signer roles would appear to display twice. For example, the label Buyer 1 would appear two times. The root cause of this issue was that part of the signer role was being cut off, so the full label could not display for the second option.&#x20;

Now, the Designate Signer page will show the full label for the signer roles as expected.&#x20;

6\. GPES-3409\
Fixed an issue with a monthly subscription renewal error.&#x20;

Previously, when monthly subscriptions attempted to renew, the user would get an email stating the subscription could not be renewed due to incorrect billing information. &#x20;

Now, when a monthly subscription renews, it will renew without error, provided the billing information is still current.  &#x20;

7\. GPES-3402\
Fixed an issue with the registration page for the free 90-day Constellation1 eSign trial.

Previously, the page may have frozen up when users tried to register for the trial.&#x20;

Now, the page will process the registration as expected.
