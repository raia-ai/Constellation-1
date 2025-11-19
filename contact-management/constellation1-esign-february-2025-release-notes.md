
# Constellation1 eSign February 2025 Release Notes

Production Release: March 4, 2025

## **Release Summary**

*   Introduced a new import contact option.
*   Added font size support to the following anchor tags (Signature, Initial, Date/Time, Text)

**Release Details**

Upload contacts

The user now has the ability to import/upload a CSV file of contacts, and can download a sample file format by clicking the “View Sample” button.

**![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/2dccd42b-b678-47c4-bf77-1892067bdf45.png)**

Anchor tags font size

Refer to the documentation at: [https://docs.constellation1.com/anchor-tags/](https://docs.constellation1.com/anchor-tags/)

Bug Fixes

1.  GPES-5304  
    We fixe an issue due to updated Gmail client showing hidden HTML elements, so now the visible placeholders are replaced with empty strings to prevent this Gmail issue from happening.

2.  GPES-5299  
    Email format validation was broken under some cases, where invalid email formats were allowed to be saved.

3.  GPES-5271  
    We corrected the from email address and the date sent on under the Dashboard page when viewing the details of a delivered email.

4.  GPES-5269

We decided to update the IP address on some of the action logs to be that of the sender’s rather than the final signers to give more accurate information as to who that action log should be long to. The following action logs will now show the sender’s IP address that gets recorded when the session is created.

*   *   Session completed and closed by…
    *   eSignature Session edit completed by…
    *   eSignature Session Created by…

5.  GPES-5252  
    A minor iOS UI fix to the tags’ setting icon spacing.

6.  GPES-5238

Now the API call, Get Session Files, and when downloading/viewing the final signed documents will show with the renamed file name, if any.

7.  GPES-5224  
    When the recipient ordering is on, and the user has multiple recipients with similar indexes e.g. (1, 1, 2, 2, 3, 4, 4, 5), when dragging tags to some of them and deciding to drop the untagged recipients, the order indexes after the dropped recipients will now roll back to continuous sequence. E.g. if having (1, 1, 2, 2, 3, 4, 4, 5) and the user drops 3, then the new sequence will be (1, 1, 2, 2, 3, 4, 5).

8.  GPES-5120  
    We fixed an issue with when hitting the Back button from the Preview page, a page of a multi-page document was not being displayed correctly. Now, all pages show up correctly.

9.  GPES-5108  
    We fixed an issue where the page numbers were not showing correctly sometimes on the Preview Session page.

10.  GPES-5039  
    We fixed an issue where when the user selects GMT as the local time zone, it showed as a GDT. The problem wasn’t just GMT but also some other related time zones.

11.  GPES-5028  
    We’re now showing the signers count on the Apply Template modal window. It used to not show the value.

12.  GPES-4756  
    We fixed an issue with the Preview, and the Template creation pages where under some cases the Page # of # wasn’t being displayed correctly.

Was this article helpful to you?

Was this article helpful to you?