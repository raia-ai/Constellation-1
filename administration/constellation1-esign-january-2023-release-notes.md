
# Constellation1 eSign January 2023 Release Notes

Production Release: February 1 2023 

## RELEASE SUMMARY

**eSign Mobile Responsiveness:** Documents now automatically fit device width on the Preview page.   
**Document Review:** Signers can now review a document before starting a signing ceremony.   
**Bug Fixes**

## RELEASE DETAILS 

eSign Mobile Responsiveness   
We’ve improved usability when previewing signing sessions on eSign Mobile.   
Now after creating a signing session and viewing the document on the Preview page, the document will be dynamically sized to fit the width of the user’s mobile device. This allows the user to easily view where the markups and tags are placed on the document without having to scroll up/down or left/right to see the document in full. 

Document Review   
We’ve added Document Review to signing sessions. Now when a signer receives an invitation to sign a document, they can review the documents before starting the signing session.   
Document Review is enabled for each signer as needed when creating a signing session. When adding recipients to a session, click the dots in the Action column next to the signer and select Edit. In the Add Recipient modal, toggle Document Review to YES. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/01%20Jan%202023/2023-Jan-esign-DocReview1.png)

When the signer clicks the Review & Sign button in their invitation email, they will be presented with a welcome page with the document displayed in the preview window. After the signer scrolls to the bottom of the document, the Continue button will be enabled. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/01%20Jan%202023/2023-Jan-esign-DocReview2a.png)

The signer can then concent and click Continue to begin the signing session. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/01%20Jan%202023/2023-Jan-esign-DocReview2b.png)

Bug Fixes

1\. GPES-3530

We fixed an issue where the word “Null” would show briefly underneath the template name when uploading documents to a transaction.

Previously, when uploading documents to a transaction, the word “Null” would momentarily display under the template name.

Now, this message will no longer display when uploading documents.

2\. GPES-3524

We fixed an issue with time zone and date format settings not saving for newly created user accounts.

Previously, when a new user account was created either manually or through the API, the time zone and date format settings were not saved. The user would then have to manually set their time zone and date format preferences before creating a signing session. Now, when a new user account is created, the system will save their time zone and date format settings. 

3\. GPES-3523

We fixed an issue with Form Simplicity not saving a user’s time zone when it is set correctly in eSign 2.0

Previously, when a user updated their time zone in eSign, the change was not saved in Form Simplicity, and Form Simplicity would overwrite the time zone with the default setting

Now, when the time zone is updated, either in eSign or Form Simplicity, the change will be saved and Form Simplicity will not overwrite the time zone with the default setting.

4\. GPES-3396

We fixed an issue with document names and recipient information running off the edge of the screen when previewing a signing session on a mobile device

Previously, when previewing a signing session, the document and recipient names would run off the edge of the screen on the Preview page.

Now, when previewing a signing session, document names and recipient information will be correctly displayed within the viewing area.

5\. GPES-2966

We fixed an issue with conditional tag values showing after a tag was deleted from a document.

Previously, when tags were added to a document and then deleted, other tags that had conditions based on the previously placed tags would show the deleted tags as conditional options.

For example, if radio buttons were added to a document, then deleted, the deleted radio buttons would still show as an option for adding conditions for another tag, such as the signature. This allowed a user to assign the radio button as a condition for the signature, even though the radio button was no longer present in the document, potentially making it impossible to complete the session.

Now, when tags are deleted from a document, the deleted tags will no longer be included as options when selecting conditions for other tags.

6\. GPES-3548

We fixed an issue with some forms not converting when after uploading them to a signing session.

Previously, when uploading forms from the FS Library to a signing session, the forms failed to convert to PDF.

Now, when these forms are uploaded to a signing session, they will convert to PDF as expected.

Note: Documents in XFA format are not supported and will not convert to PDF.