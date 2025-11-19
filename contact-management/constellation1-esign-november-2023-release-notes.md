
# Constellation1 eSign November 2023 Release Notes

Production Release: November 20 2023 

## RELEASE SUMMARY

**Signer Tags and Markups:** Enhanced ability to manually adjust the position of tags and markups.   
**Time Zone:** Time Zone is now a required field when adding new users.   
**Text Markup Tag:** Updated to expand vertically.   
**Bug Fixes**

## RELEASE DETAILS

Manually Adjust Signer Tag and Markup Position with Arrow Keys  
We’ve enhanced users' the ability to manually adjust the position of signer tags and markups on a document with the arrow keys after dragging and dropping them while creating a signing session.

To move a tag or markup with the arrow keys, first click it to select it, then press the arrow keys to move it up, down, left, or right by 1 pixel per press. Press Ctrl + \[arrow key\] (on a PC) or Command + \[arrow key\] (on a Mac) to move the tag or markup by 10 pixels per press.  
Users can also open the tag or markup settings and manually enter values corresponding to the X and Y axis on the document.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/11%20Nov/2023-Nov-eSign-XYAxis.png)

This can be helpful for ensuring extra precision while placing tags and markups are placed where they do not obscure any important information on the document.

Set Time Zone for New Users   
Time Zone is now a required field when adding new users to eSign.   
When adding new users, the administrator will have to set the time zone of the user they are adding. The selected time zone will default to the administrator’s time zone, but if the user’s time zone is different, the administrator can select the correct one from the dropdown. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/11%20Nov/2023-Nov-eSign-AddUsersTimeZone.png)

  
Users who create signing sessions through our API will no longer need to login to eSign and set their time zone. 

Text Markups Expand Vertically   
We’ve updated the functionality of text markups to allow them to expand vertically when the user hits Enter to insert a hard (carriage) return.   
If the text in the box reaches the right page margin, the text will automatically wrap to the next line. 

  ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/11%20Nov/2023-Nov-eSign-TextMarkup.png)

Bug Fixes

1\. GPES-3883  
We fixed an issue with sorting contacts.   
Previously, on the Contacts page, when a user tried to sort contacts by name, phone number, or email by clicking the corresponding column header, the list wouldn’t sort as expected.    
Now, this issue has been resolved and users can sort contacts by either ascending or descending order by clicking the column header. 

2\. GPES-4483  
We fixed an issue with some PDF documents missing text after they were uploaded to eSign.   
Previously, when certain PDF documents were uploaded to eSign, some of the text would be missing. It was determined that there was an issue with DevExpress.  
Now, DevExpress has provided an update, and this issue has been resolved. 

3\. GPES-4507  
We fixed an issue with anchor tags not showing on a document after being uploaded to eSign.   
Previously, when a document containing anchor tags was uploaded to eSign, the anchor tag service failed to recognize the tags, causing them not to show on the document.   
Now, the anchor tag service has been updated and this issue has been resolved. 

4\. GPES-4481   
We fixed an issue with check marks and radio button selections not showing on some signed documents.   
Previously, in some instances, radio button and check box selections made by a signer may not have displayed on the completed document.  
DevExpress has provided an update, and this issue has been resolved. The radio button and check box selections will now be included in the document.

5\. GPES-4484  
We fixed an issue with Recipient Ordering setting all signers as the first signer when creating a signing session from rDocs.  
Previously, when a signing session was created from rDocs and Recipient Ordering was enabled, all signers added to a session would be set as the first signer.   
Now, this issue has been resolved and signer order will match the session creator’s selection when creating a signing session.

6\. GPES-4489   
We fixed an issue with the keyboard showing when dragging a markup onto a document while using eSign on a mobile device.   
Previously, when a user would drag a markup onto a document using eSign mobile on a touchscreen device, the keyboard would open, covering a large portion of the document. eSign recognized the tap, but not the hold or drag actions.  
Now, this issue has been resolved and the keyboard will no longer obscure the view of the document when dragging markups.