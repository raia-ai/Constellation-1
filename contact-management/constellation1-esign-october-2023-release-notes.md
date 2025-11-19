# Constellation1 eSign October 2023 Release Notes

Production Release: October 25, 2023&#x20;

## RELEASE SUMMARY

**Expired Signing Sessions:** Added ability to copy and resend expired signing sessions. \
**Default Font Size:** Added option to set the default tag font size in Account Settings. \
**Markups:** Improved usability. \
**Reply Email Address:** Added sender name back to emails sent from eSign.\
**Bug Fixes**

## RELEASE DETAILS

Expired Signing Sessions\
eSign Online now allows users to copy expired signing sessions in order to send them again. \
On the Sessions page, in the Action menu, we’ve added Copy as an option.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/10%20Oct/2023-Oct-eSign-CopyExpired.png)

&#x20;When the user selects Copy, they will see a Copy Session popup where they can modify their session settings and create a new signing session. Signers and documents can be identical to the copied session and transferred to the new signing session by checking the corresponding boxes. \
The user can also select whether to copy the original document(s) or the version(s) that were signed by at least one party before the session expired.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/10%20Oct/2023-Oct-eSign-CopyExpiredSigned.png)

After the user clicks Continue, the new signing session will open in an edit view where the sender can further review and modify it if needed before sending.&#x20;

Set Default Font Size\
We’ve added the ability for users to set the default font size for signer tags and markups.

We’ve added a new section to Account Settings where the user can set the desired font size and save their setting as the default for their signing sessions.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/10%20Oct/2023-Oct-eSign-DefaultFontSize.png)

Improved Markup Usability\
We’ve updated markups for improved usability.\
We’ve added additional padding to the edges of the markups, creating a larger touch target around the markup where the user can grab the edge, making it easier to adjust their size and orientation when placing them on a document.&#x20;

Reply Email Address\
Last month, we announced we had removed sender names from the From field on emails sent from eSign. Our customers responded with their feedback, and we are adding sender names back to the From field. \
We’ve made this a configurable setting for companies that would still like to remove the sender name from the From field. If you would like to make this change, please contact your eSign representative. \
Emails sent from eSign will have noreply@esignonline.net as the From address.

Bug Fixes

1\. GPES-4459\
We fixed an issue with placing signer tags and markups on the right half of a document when using eSign Mobile. \
Previously, when using eSign Mobile, tags placed on the right side of a document may have become locked in place and uneditable.\
Now, this issue has been resolved.&#x20;

2\. GPES-4429\
We fixed an issue with markups and signer tags not dropping in the correct place when dragged onto the document using eSign Mobile.\
Previously, when creating a signing session using eSign Mobile, the user could drag a markup or tag to a particular place on the document, but it would sometimes change position.\
Now, this issue has been resolved. Markups and tags will remain where the user drops them.
