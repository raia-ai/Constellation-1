---
title: "Constellation1 eSign May 2025 Release Notes"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/27144086"
tags: ["Administration"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Constellation1 eSign May 2025 Release Notes Production Release: Tuesday May 27, 2025 Release Summary Small UI improvements"
long_description: "Constellation1 eSign May 2025 Release Notes Production Release: Tuesday May 27, 2025 Release Summary Small UI improvements. Architectural change to retry sending emails when we fail to communicate with our email vendor. Eliminated the Power User role. Other various fixes. Release Details In the past we’ve had an email delivery downtime issue due to our vendor, Mailgun, having issues, which kept our users stranded. Now we’ve introduced a built-in retry mechanism if this issue ever occurs again, s"
---

# Constellation1 eSign May 2025 Release Notes

Production Release: Tuesday May 27, 2025

**Release Summary**

*   Small UI improvements.
*   Architectural change to retry sending emails when we fail to communicate with our email vendor.
*   Eliminated the Power User role.
*   Other various fixes.

**Release Details**

In the past we’ve had an email delivery downtime issue due to our vendor, Mailgun, having issues, which kept our users stranded. Now we’ve introduced a built-in retry mechanism if this issue ever occurs again, so users don’t get affected, and their emails will eventually be delivered.

Bug Fixes

1.  GPES-5460

We fixed a phone format issue related to SMS authentication when the session was created through the API. This prevented the signers from authenticating their phone number when launching the signing ceremony.

2.  GPES-5456

Updating a user or a group user with a new password from the API calls didn’t reflect the newly given password.

3.  GPES-5448

After editing a session and changing a recipient role, prevented that recipient from getting a new invite.

4.  GPES-5446

We cought an issue within a narrow time slot window where the signer after launching the signing ceremony was able to still complete signing if the sender had just edited the session.

5.  GPES-5430

We corrected the action menu’s display on some grids when having only one row where didn’t show all the options.

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/aa7f83e9-99cb-44aa-8cb3-4db3ea1f9265)

6.  GPES-5400

When eSignature was launched from Constellation1 Documents TMS the Include Attachment option was not being turned on.

7.  GPES-5320

Under certain session settings, the Include Attachments option was being disabled for users.

8.  GPES-5147

We have removed completely the group role Power User as it was an extra unnecessary role.

9.  GPES-5031

Now we’ve added the Group column to the Users grid to make it easy on users to see which users are group users without the need to go into the Group Users page.