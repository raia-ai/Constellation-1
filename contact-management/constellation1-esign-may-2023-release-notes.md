# Constellation1 eSign May 2023 Release Notes

Production Release: May 23, 2023&#x20;

## RELEASE SUMMARY

**DevExpress:** Updated support for converting HTML documents to PDF. \
**Custom Domains:** Added support to redirect to a custom website domain. \
**Certificate of Authenticity:** Added an easier way for users to download certificates. \
**Date Tag Format:** Added option to configure Date tag format to include date, time, or both.\
**Signer Tags and Markups:** Various updates and improvements. \
\*\*Bug Fixes\
\*\*

## RELEASE DETAILS

DevExpress\
We’ve replaced Tall Components with DevExpress for increased stability and reliability when eSign converts documents from HTML to PDF. This update reflects our continued effort to replace Tall Components.&#x20;

Custom Domains\
We’ve improved the signing session creation workflow through the API for companies that have a custom website domain. \
When a user creates and sends a signing session through the eSign API, eSign now supports the option to redirect the user back to their company website, where they can continue working. \
This feature is specific to the API and is optional. Please contact your Constellation1 representative for more details.&#x20;

Certificate of Authenticity \
We’ve updated the Download Documents page to allow the session sender to download the certificate of authenticity more easily once the signing session is complete. This update simplifies the path the session sender needs to take to access and download the COA.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-COADownload.png)

On the Download Documents page, there are now two columns: Single Documents and All Documents Zip File. The certificate of authenticity for the session will be listed here. The user can select the documents they want to download by checking the box for the desired documents, then clicking Download.

New Date Tag Format Setting\
We’ve updated User Groups to allow an administrator to configure the default format for the Date tag. \
On the signing Group Information page, we’ve added a dropdown to set the default Date tag format for the signing group. The administrator can select the default Date tag format to include just the date, just the time, or both. This setting will be applied to all users in the User Group.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-DateTime1.jpg)

Updated Signer Tags and Markups  \
**Add Text**\
We’ve updated the Add Text markup tag so the background is transparent. \
The transparent background allows the markup to be placed on a document while showing the content behind the markup. This is helpful when placing the tag in a relatively small area and allows for exact placement.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-MarkupsTransparent.png)

**Form Field** \
We’ve updated the Form Field signer tag to be optional by default. Previously, the Form Field was required by default for the signer.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-SessionFormFieldSettings.png)

We’ve also updated the Form Field to automatically populate the signer’s name, making it easier for the signer. When the Form Field is placed on a document, the user can select the option to populate the signer’s name using the Auto Populate Signer Name checkbox in the Form Field settings. \
When the signer receives the documents, their name will be populated in the form field.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-SessionFormFieldSettings2.png)

&#x20;\
**Radio Buttons** \
We’ve updated the setting for placing radio buttons on a document. The default number of radio buttons that are placed on a document is two. Now, if the user opts to add more than two buttons, that updated number will be the new default for the remainder of that session when placing the next set of radio buttons.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-RadioButtons.png)

Once a user logs out, the system will revert to the default of placing two radio buttons.&#x20;

Bug Fixes

1\. GPES-3723, GPES-3722\
We fixed an issue with tags not properly displaying on a document. \
Previously, when a signing session was created using a template, the signing tags were not showing on the document. \
Now, this issue has been resolved. Additional validation has been added to prevent this issue in the future.&#x20;

2\. GPES-3620\
We’ve fixed an issue with the Include Attachments toggle being enabled for a signer but the signer not receiving the attachments when a signing session was created using the eSign API. \
Previously, when a signing session was created through the API and the Include Attachments toggle was enabled, the signer was not receiving the attachments as expected. \
Now, when a signing session is created through the API and the Include Attachments toggle is enabled for a signer, the signer will receive the attachments as expected.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-Attachments.png)

3\. GPES-3616 \
We fixed an issue with users receiving an error message when trying to upload certain types of files to eSign. \
Previously, when a certain type of file was uploaded to eSign, it would cause an error. The error was caused by DevExpress and usually occurred with MS Word files that had been converted to PDF.\
Now, this issue has been resolved with our DevExpress update.&#x20;

4\. GPES-3565\
We fixed an issue with the Contact modal showing behind the left navigation when the browser was zoomed in over 100%. \
Previously, when a browser was set to a zoom level higher than 100% when viewing a user’s Contact information, part of the modal was hidden behind the left navigation.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/05%20May%202023/2023-May-ContactCard.png)

Now, this issue has been resolved. If there is an overlap with the left navigation, the Contact modal will display in front of the left navigation, not behind it.
