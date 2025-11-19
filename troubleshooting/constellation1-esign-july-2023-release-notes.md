# Constellation1 eSign July 2023 Release Notes

Production Release: July 19, 2023&#x20;

## RELEASE SUMMARY

**Bug Fixes**&#x20;

## RELEASE DETAILS

#### Bug Fixes

1\. GPES-3825\
We’ve fixed an issue with the Read Tags function not completing when uploading files containing invalid tags or images as PDFs.&#x20;

Previously, when adding files with invalid signer tags or images in PDF format to a signing session, the system was not able to read the tags, preventing the Read Tags function from completing.&#x20;

Now, when these kinds of files are added to a signing session, the system will show a warning message alerting the user that the system could not read these tags.&#x20;

2\. GPES-3812\
We’ve fixed an issue with the signature pad not displaying the Select and Close buttons when a signer was reviewing a document in landscape view on the mobile version of eSign.&#x20;

Previously, when a signer attempted to create a signature on the Signature page while viewing a document in landscape view on their mobile device, the Select and Close buttons would not display.&#x20;

Now, this issue has been resolved. The Select and Close buttons will display on the signature pad when viewing a document in landscape mode on a mobile device.

3\. GPES-3803 \
We’ve fixed an issue with text clearing from a document when removing anchor tags.&#x20;

Previously, when a user would remove anchor tags from a document, all the text would also be removed. &#x20;

Now when removing anchor tags, the system will not remove text from the document.&#x20;

4\. GPES-3227\
We’ve fixed an issue with a signer’s name not updating in the Signers dropdown in step 2 if the name was edited while creating the signing session.&#x20;

Previously, if a signer’s name was edited while the signing session was being created, the edited name did not update in the Signers dropdown in step 2 to add them to the session.&#x20;

Now, if a signer’s name is edited when creating the signing session, the updated name will show in step 2.&#x20;

5\. GPES-3790\
We’ve fixed an issue with the Initials tag not updating when the corresponding signer’s name is edited while creating a signing session. &#x20;

Previously, if a signer’s name was edited while creating a signing session, the Initials tag didn’t update to show the signer’s correct initials.

For example, if the signer’s name was Bob Smith and an Initials tag was added to a document, and then the signer’s name was updated to Robert Smith, the Initials tag would continue to show as BS instead of RS.&#x20;

Now, if a signer’s name is edited while creating a signing session, the Initials tag will update and display the correct initials.&#x20;

6\. GPES-3729\
We’ve fixed an issue with the line spacing in the Text Box Markup tag.&#x20;

Previously, when the Text Box Markup tag was added to a document, then stretched to span multiple lines, the space between lines would be reduced.&#x20;

Now, the line spacing in the Text Box Markup tag has been corrected. When a document is finalized, the line spacing will not be reduced.&#x20;

7\. GPES-3833 \
We fixed an issue with users getting an error when returning to the Sessions page in eSign after completing a signing session.&#x20;

Previously, if a user created and sent a signing session, then opened it and completed their signing ceremony, they would receive an error message when they returned to the Sessions page.&#x20;

Now, this issue has been resolved. Session creators who are also signers will be able to return to their Sessions page after completing their signing ceremony without seeing an error message.
