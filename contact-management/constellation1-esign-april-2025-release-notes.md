
# Constellation1 eSign April 2025 Release Notes

Production Release: Tuesday April 29, 2025

**Release Summary**

*   Small UI improvements.
*   The signing session title is now part of all webhook types.
*   The signing session expiration date is no longer copied when copying sessions.

**Release Details**

Signing session title sent in the Webhook types

Now, all Webhook types contain the session’s Title. This property only existed in one of the Webhook types but upon request now it’s added to all types.

Signing session expiration date no longer copied when copying sessions

The session’s expiration date used to get copied before, which caused confusion if it was a past date and the user didn’t pay attention to it, and it expired the session sooner than expected after sending the session. So, now the expiration date is left blank to let the user specify one if needed.

Bug Fixes

1.  GPES-2919

Under some certain cases, the previously selected authentication methods would not get displayed upon multiple edits to a recipient, yet the value is still saved in the data record. Now, the selected auth method is always selected regardless of the times the recipient is edited.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a95547a0-830d-4cc4-a694-3d78428c0648)

2.  GPES-4771

When creating a new contact and adding a comma in the last name as “Zee, Lee”, searching for this contact replaced the email column value with a portion of the last name.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/9b32136b-ed87-447c-b59f-e4937f274955)

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/2a2f55f4-c862-4792-98cf-454c27de81a0)

3.  GPES-4944

The user failed to upload image files to template creation. Now, that’s allowed just like in session creation.

4.  GPES-5066

When adding a signer from the designate signers’ window and going to second page to assign signer tags, the signers’ drop down showed NULL for these signers. Now, we correctly show the signer’s name.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/11cabd83-be1c-4386-89ae-7eab945f23c1)

5.  GPES-5156

Email attachments were being attached with a GUID filename format rather than the original filename.

6.  GPES-5226

The signing session’s expiration date was being copied along copying sessions, which under some cases caused the session to expire when the user didn’t modify the past date. Now, we don’t copy the expiration date and allow the user to enter the desired date.

7.  GPES-5370

Now, all webhook types contain the signing session’s title in them as requested by customers.

8.  GPES-5388

Under certain desktop screen resolutions like 1530 x 730, some grid action menus were not visible to the user.

9.  GPES-5413

Now, the API call to create sessions limits the value of _ReminderFrequenceDays_ to 30 days. Any other value greater than 30 will be reset to 30.