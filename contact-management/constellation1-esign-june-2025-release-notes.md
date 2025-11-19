# Constellation1 eSign June 2025 Release Notes

Production Release: Tuesday June 24, 2025&#x20;

**Release Summary**

* New email notification control flag
* Expanding on the email validation regular expression.
* Auto retries of jobs caused redundant emails due to bad emails in the session

**Release Details**

With the previous release’s introduction of a built-in retry mechanism of email failures, we discovered a small number of sessions have had invalid emails added to them, which caused users to receive duplicate email notifications.

Bug Fixes

1. GPES-5516, GPES-5507

These two tickets addressed the issue of duplicate emails being sent when starting or canceling a session that had invalid email addresses added to it. We’re also monitoring the system to resolve such issues before the release is out to production.

2. GPES-2433

This prevents the app from allowing adding invalid emails to the sessions, or contacts, or selecting an existing invalid email from the contact to be added to a session.

3. GPES-3740

With a slow network connection, sometimes clicking the Download Document button on completed sessions caused an Unauthorized error to be displayed.

4. GPES-4700

We previously noted that a user had an invalid PDF that had no pages, but it was uploaded correctly, but then resulted in no pages displayed when attempting to add tags to the document. Now, we’re deleting such files and not allow the user to go to the step to add tags, and indicating a zero page on the uploaded file with a spinner next to it.

5. GPES-5113

As requested we’ve added a new email notification toggle “Intermediate Signed Document Downloads” under the user’s account page to prevent sending intermediately signed documents when a session has multiple signers, and only send the final email to all recipients with the option to download the final documents.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/e9ebabe0-a26d-437d-8a38-839c241c4764)

6. GPES-5491

When the client-level option to parse QR codes from the first page in a document was enabled and the uploaded files didn’t have QR codes or had barcodes instead, this option caused an error that prevented the document from getting uploaded. It was turned OFF for those customers in production, but we also added a guard to prevent the failure of the document upload process in such a case.
