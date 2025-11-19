# Constellation1 eSign June 2022 Release Notes

Production Release: 30, 2022&#x20;

## RELEASE SUMMARY

**All-New Dashboard:** Added a new dashboard to provide signing session statistics and email delivery reports.

**Knowledge Base Authentication:** Added new billing options.

**Sign Now or Later:** Improved the workflow when the session creator is also a signer.&#x20;

**Form Fields:** Made form fields required by default.&#x20;

**Form Field Settings:** Updated the user interface.&#x20;

**Document Downloads:** Improved the workflow when downloading documents from a completed signing session.&#x20;

**History Log:** Delegated sessions will now be logged in the session history.&#x20;

**Bug Fixes**

## RELEASE DETAILS

All-New Dashboard&#x20;

We’re pleased to present the all-new eSignature 2.0 dashboard! This new dashboard is designed to help administrators support their end users with real-time signing session statistics and email delivery reports. We’ve designed the dashboard and the reports to be intuitive, easy to use, and easy to understand.

Users can select one of the eight tiles at the top of the page to display a high-level view of the report in the lower section of the page. They can also filter the information that displays by date by selecting a date range at the top of the dashboard. These include Current Day, Last Month, and the ability to select a custom date range.

The available options are:&#x20;

* Total Sessions&#x20;
* Declined Signers
* Pending Sessions&#x20;
* Completed Sessions&#x20;
* Total Emails Delivered&#x20;
* Failed Emails&#x20;
* Open Emails
* Open Invites&#x20;

Each report features a line-item display showing high-level statistics related to the report. Clicking the three dots in the Actions column opens a sub-menu of actions related to the specific item and report.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/June%202022/Dashboard.JPG)

Knowledge Based Authentication (KBA) Billing Options

We’ve improved the billing options for signing sessions that use Knowledge Based Authentication (KBA).&#x20;

Previously, when a user created a signing session and added KBA authentication, they would be prompted to enter a credit card number that would be billed for the KBA service.&#x20;

Now, the company has the option to have all KBA charges billed to their company account. When the signing session creator adds KBA authentication, they will not be prompted to enter a credit card number, the system will simply move on to the next step and Constellation1 will bill the company for such charges.&#x20;

This KBA billing method change is optional and can be enabled by request. Please contact your Constellation1 representative for more details.&#x20;

Session Creator – Sign Now or Later

We’ve improved the workflow for signing sessions where the session creator is also a signer. Previously, a signing session creator who is also a signer had the option to sign now, sign later or close the popup window.

Now, the signing session creator will no longer be able to close the popup window, they must opt to either sign now or sign later by clicking the corresponding button.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/June%202022/2022-esign-June-SignNowAfter.png)

Form Fields Default Set to Required

We’ve updated the form field settings to now default to required whenever a field is placed on a document.&#x20;

Form fields are often used for important information, such as Name or Title. Previously, when a form field was added to a document, it was optional, and the session creator would need to manually set the field to required.&#x20;

Now, when a form field is added to a document, it will be required by default for the signer. The updated setting improves the workflow and efficiency for the user when creating a session by removing the manual step of changing the field setting to required, ensuring important information is added to the document at the time of signing.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/June%202022/2022-esign-June-Form-Required.png)

Form Field Settings User Interface&#x20;

We’ve updated the user interface on the form field settings menu. This update makes the user interface cleaner and easier to read.&#x20;

Document Downloads

We’ve improved the workflow for downloading documents from a completed signing session. Previously, when a user clicked the Download icon in the File Preview, the document would open in a browser window, adding an additional step to download the document. The document name would also autopopulate as a long string of alphanumeric text.&#x20;

Now, when a user clicks the Download icon in the File Preview, the document will download immediately and will have the correct file name.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/June%202022/2022-esign-June-DownloadDoc.png)

History Log

We’ve improved the details shown in the Action History Log when a signer delegates the signing session to another person to sign. &#x20;

When a signer opens their signing session, then delegates the session to another signer, this action will be logged in the session’s Action History Log.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/June%202022/2022-esign-June-History.png)

BUG FIXES

1\. Ticket no: GPES-3130 \
We fixed an issue with copying signing sessions.&#x20;

Previously, when copying a signing session, the new session would be incomplete and the tags placed in the documents would be missing. Now, when copying a signing session, the session will be complete and include all the existing tags in the documents.

2\. Ticket no: GPES-3094\
Fixed an error when sending a signing session with a signer group.&#x20;

Previously, when a group was added to a signing session, the session creator was not able to send the signing session and would receive the message, “You have some recipients that don’t have tags given to them?” The system was not recognizing the signers as a group. Now, when a group is assigned to a signing session, the system will recognize the signers as a group and not generate an error, thereby allowing one person from the group to sign on behalf of the group.

3\. Ticket no: GPES-3105 \
Fixed an issue with anchor tags discarding signer roles that have a space.&#x20;

Previously, if a signer role associated with an anchor tag had a space, the signer role would be ignored. For example, the signer role Sales Representative might have been converted to SalesRepresentative or ignored and not converted.&#x20;

Now, signer roles in an anchor tag will not be ignored and will convert accurately with the space in the name.&#x20;

4\. Ticket no: GPES-3014\
Fixed an issue with some Rich Text Files (RTF) not converting to PDF.

Previously, certain RTF documents would fail to convert. The problematic RTF files were complex and may have included layers or other formatting. Now, these RTF files will convert to PDF correctly.

5\. Ticket no: GPES-3000\
Fixed an issue with the Next button jumping to the bottom of the document when starting a signing session on a Mac.&#x20;

Previously, when a signer opened a session using a Mac, the Next button would appear to the very bottom of the document, not where the next signable field in the document appears. \
Now, when a signer opens a session, the document will scroll properly, and the Next button will appear next to the next tag needing the signer’s attention.
