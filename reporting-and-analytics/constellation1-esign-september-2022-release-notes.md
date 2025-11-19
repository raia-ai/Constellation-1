# Constellation1 eSign September 2022 Release Notes

Production Release: September 27, 2022&#x20;

## RELEASE SUMMARY

**Dashboard:** Added the ability to filter failed emails by error type.

**Bug Fixes**

## Release Details

Dashboard&#x20;

In a previous release, we added the ability to filter failed emails by the reason that they failed. In this release, we’ve added a dropdown to further filter failed emails by error type.&#x20;

This improvement will make it easier to not only group emails by reason but also to group these emails by error type, allowing the user to quickly and easily identify emails that have been marked as spam or as a permanent failure.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Sept/2022-Sept-esign-FailedEmails.png)

Bug Fixes

1\. GPES-3271\
We fixed an issue with the Certificate of Authenticity not accurately recording SMS authentication.&#x20;

Previously, the Certificate of Authentication would show Email as the authentication method when a signer authenticated using SMS.&#x20;

Now, when a signer authenticates their signing session using SMS, the Certificate of Authenticity will show SMS and not Email.&#x20;

2\. GPES-3311\
We fixed an issue with some pages not loading and showing a No Data Available message.&#x20;

Previously, some pages did not load the content that was expected. For example, templates didn’t show on the Templates page. The issue was caused by an errant database process.&#x20;

Now, we’ve corrected the errant process so pages will load as expected.

3\. GPES-3288\
We fixed an issue with signers receiving a second invite to a signing session they had already completed.&#x20;

Previously, if the sender edited a session during a short window after all the signers had completed it, the signers would then receive another email inviting them to a signature session they had already completed.&#x20;

Now, when the last signer signs, we have reduced the window of time where this issue existed. The sender will not be able to edit a session after the last signer has signed.&#x20;

4\. GPES-3357 and GPES-2819\
We’ve fixed an issue with the signer being prompted to designate a delegate signer for a non-required field.&#x20;

Previously, in a specific use case where a reviewer or CC recipient was associated with a signing session along with other signing roles that may also have had a co-signer, the signer was asked to designate a signer as the co-signer.&#x20;

Now, the signing session will recognize when a signer completes their session and the co-signer role will not be required.&#x20;

5\. GPES-3346\
We fixed an issue with the dashboard loading slowly.&#x20;

Previously, the dashboard was taking a long time to load.&#x20;

Now, we have optimized the code for this page, and the dashboard will load much faster.&#x20;

6\. GPES-3293\
We fixed an issue with generating reports.

Previously, when running a report that needed to sort through a lot of data, it might have taken longer to generate the report.

Now, we have optimized the database and code used to call a report. Reports will run more efficiently and return results faster.&#x20;

7\. GPES-3318\
We fixed an issue in eSign 1.0 with the screen resolution causing some browsers to block buttons on the document review.

Previously, when a user had their computer monitor resolution set to 125%, the Continue button on the Document Review page would not work.&#x20;

Now, the buttons on the Document Review page will work regardless of the screen resolution.
