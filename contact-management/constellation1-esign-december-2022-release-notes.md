# Constellation1 eSign December 2022 Release Notes

Production Release: December 15, 2022&#x20;

## RELEASE SUMMARY

**Input Field Formatting:** Added formatting to fields for a better user experience.   \
**Signing Session Management:** Signing sessions created in eSign 1.0 can be managed in eSign 2.0. \
**Administrator Access:** Upgraded signing session access for administrators. \
**Knowledge-Based Authentication:** Improved UI for an intuitive user experience. \
**Email Attachments:** Documents that are smaller than 20 MB will be attached to emails. \
**eSign Mobile:** Improved usability.\
**UI Updates:** Various user interface updates.  \
**Bug Fixes**

## RELEASE DETAILS

Input Field Formatting\
We’ve improved the usability of input fields for a more intuitive user experience. The user can now type into a field and the text will intuitively be formatted as expected for that field. &#x20;

For example, a user will no longer need to type the slashes ( / ) in a date field. The field will automatically format the date with the slashes, e.g., 01/01/2023.

We’ve also improved the State field. Start typing the name of a state and the dropdown will jump to the section of available options.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Dec/2022-Dec-esign-KBA-Welcome.png)

Signing Session Management\
We’ve improved compatibility between eSign 1.0 and 2.0. This issue was originally reported as a bug in ticket GPES-3460. If a signing session that had been created in eSign 1.0 was then canceled using eSign 2.0, the signing session would continue to send reminders to the signers.&#x20;

Recognizing some customers will encounter this use case, we’ve improved the compatibility between the two versions. When a signing session is created in 1.0, the user will now be able to update the signing session in 2.0.&#x20;

However, this does not provide the best user experience. Signing sessions should be managed in the version they are created in. For the best user experience and access to the latest features, we encourage our customers to upgrade to eSign 2.0. For questions about how to do this, contact your Constellation1 representative.

Administrator Access  \
We’ve expanded eSign administrator access to be able to manage user sessions. In addition to viewing signing sessions, administrators can now edit, resend, or cancel signing sessions. \
Any edits or updates to a signing session made by an administrator will also be tracked in the Certificate of Authenticity.&#x20;

Knowledge-Based Authentication \
We’ve updated the user interface for signers who are using KBA to authenticate their identity for a signing session. The update provides an easier and more intuitive user experience.&#x20;

Improvements include:

* Added validation for required fields before the signer can go to the next step
* Relocated the Retake modal to a prominent position in the middle of the screen
* Changed text to be specific about the information needed to authenticate
* Updated the State field to compel the signer to select their state
* Required fields are now highlighted with a blue outline.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Dec/2022-Dec-esign-KBA-Nes.png)

In the screenshot above, notice the Start KBA button is deactivated. To avoid confusion, it will only become clickable once the required fields are completed.&#x20;

Email Attachments\
We recently updated how email attachments are handled by adding a link to the email so the user can download the documents.

In this release, we’ve added validation to calculate the total size of the documents being attached to an email. If the documents are less than 20 MB, they will be attached to the email and sent. For convenience, the link to download the documents will be included in the email message, too.&#x20;

If the attachments are 20 MB or larger, the documents will not be attached to the email to ensure deliverability. The recipient will need to click the link in the email to download the documents. &#x20;

eSign Mobile\
We’ve improved the usability of the eSign Mobile, originally reported as a bug in ticket GPES-2978.&#x20;

Improvements to eSign Mobile include:

* Easy log-in workflow
* Improved flow for creating a signing session
* Smooth drag-and-drop functionality when placing markups on a document

**Note:** eSign Mobile is only compatible with eSign 2.0.

User Interface Updates\
We’ve made various user interface updates:

* Updated the favicon in the browser bar for consistent branding
* Added space between the Delete and Setting icons on the markup tag
  * ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022%20Dec/2022-Dec-esign-Markup.png)
* Removed duplicate headers in the signing ceremony header
* Corrected typos in the Terms & Conditions and KBA interface

Bug Fixes

1\. GPES-3491\
We fixed an issue with Knowledge-Based Authentication not being responsive to touch on mobile devices. \
Previously, when a signer would try to authenticate their identity with KBA, some fields, such as State and Country, were not responding to touch. \
Now, the touch response for these fields has been restored when using a mobile device.&#x20;

2\. GPES-3490 \
We fixed an issue with a signer getting an error message after declining a signing session. \
Previously, when a signer would decline a signing session, they would see an error message. \
Now, when a signer declines a signing session, they will see a modal prompting them to provide a reason for declining the signing session, as expected.&#x20;

3\. GPES-3459\
We fixed an issue with form fields on a PDF document being removed in step 2 when creating a signing session.\
Previously, when a PDF document with fillable form fields was uploaded to a signing session, if the user selected Read Tags from the Actions menu, the contents of the form fields would be cleared. \
Now, when a fillable PDF form is uploaded and Read Tags is selected, the content in the form fields will remain as expected.

4\. GPES-3418\
We fixed an issue with a completed signing session showing Next Signer instead of Completed on the Signing History and Session pages. \
Previously, when a signing session was completed, the History and Session pages would show Next Signer instead of Completed. \
Now, when a session has been completed, the History and Session pages will show the correct status of Completed.

5\. GPES-3365\
We fixed an issue with radio button markups not showing all conditions that can be applied to the radio button.\
Previously, when a radio button was added to a document, the user could set the conditions for the radio button but not all the conditions were showing in the settings. \
Now, when a condition is applied to a radio button, all conditional options will show in the radio button settings.
