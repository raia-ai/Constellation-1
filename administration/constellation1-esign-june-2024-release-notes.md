# Constellation1 eSign June 2024 Release Notes

Production Release: June 25, 2024

## Release Summary

**Signing Sessions:** Uploading documents is more intuitive. \
**Bug Fixes**

## Release Details

Uploading Documents to a Signing Session\
We’ve improved the process for signers uploading documents during their signing session.\
When a signer uploads a document, they will now be directed back to the Next button in the document where they left off, allowing them to seamlessly continue the signing session.\
Previously, the Next button would not appear when a document was uploaded during a signing session.

Bug Fixes

1\. GPES-4706\
We fixed an issue with markups and tags not showing on documents when creating a group signing session with a template.&#x20;

Previously, when creating a group signing session, some signer markups placed on the document in the template were not showing on the document.

Now, when a group signing session is created using a template, all signer fields will show on the document as expected. This issue has been resolved. &#x20;

2\. GPES-4745\
We fixed an issue with the default form field setting not being saved on templates.&#x20;

Previously, when creating a template and adding a Form Field to a document, the setting on the form field was not being displayed on the document during the creation of a signing session.

Now, when form fields are updated and saved, they will show the setting value on the document.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2024/06%20June/2024-June-eSign-FormField.jpg)

3\. GPES-4807&#x20;

We fixed an issue with placing markups and tags on the right edge of a document.&#x20;

Previously, when creating a signing session and placing a markup or tag close near the right edge of a document, the markup or tag would not stay where it was placed.

Now, this issue has been fixed, ensuring that markups and tags remain in their designated positions on a document.
