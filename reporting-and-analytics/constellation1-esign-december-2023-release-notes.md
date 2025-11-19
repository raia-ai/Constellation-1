# Constellation1 eSign December 2023 Release Notes

Production Release: December 18, 2023&#x20;

## Release Summary

**Underline and Strikethru:** Improved usability.\
**User Interface:** Removed “Signer” from status bar label. \
**Bug Fixes**

## Release Details

Underline and Strikethru Markup Improvements\
We’ve updated the Underline and Strikethru markups for improved usability. \
We’ve added additional padding to the edges of the markups to create a larger area to grab and move them. We’ve also added a visible border to make it easier to see where the user can grab the markups.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/12%20Dec/2023-Dec-eSign-Markups.jpg)

User Interface Update\
We’ve updated the Status column on the Dashboard and the Sessions page. \
We’ve removed the word “Signer” from the progress bar label, making the signing session status easier to read.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/12%20Dec/2023-Dec-eSign-Status.jpg)

Bug Fixes

1\. GPES-4555\
We’ve fixed an issue with text being cut off when using the Text markup. \
Previously, when a Text markup contained multiple lines of text with a font larger than 20pt, some of the text may have been cut off and not visible to the signer during the signing session.  \
Now, this issue has been resolved.&#x20;

2\. GPES-4445\
We’ve fixed an issue with adding templates to a signing session on a mobile device. \
Previously, when adding a template to a new signing session on a mobile device, the Add Packages modal was not displaying responsively, making it difficult to add the template to the signing session.  \
Now, this issue has been resolved.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/12%20Dec/2023-Dec-eSign-Template1.jpg) ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2023/12%20Dec/2023-Dec-eSign-Template2.jpg)

&#x20;                                                                                    _Before                                                                After_

&#x20;3\. GPES-4593\
We fixed an issue with the Group Support account having access to more groups than they are assigned.\
Previously, the Group Support user account was able to view and manage more groups than were assigned to them.  \
Now, this issue has been resolved.
