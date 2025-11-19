# Paradym by Constellation1 October 2022 Release Notes

Production Release #82: October 18, 2022

## RELEASE SUMMARY

**Password Security:** Improved password security.&#x20;

**Bug Fixes**

## RELEASE DETAILS&#x20;

Password Security&#x20;

We’ve improved password security through several updates.

First, we’ve added new minimum password requirements so users create stronger passwords to provide better account protection and prevent unauthorized logins.

If a current user’s password does not meet these new minimum requirements, the next time they log in, they will be redirected to a page to update their password.&#x20;

The new requirements are:\
•    Minimum of 6 characters (existing users)\
•    Minimum of 8 characters (new users)\
•    At least 1 capital letter\
•    At least 1 lower case letter\
•    At least 1 number \
•    At least 1 special character (e.g., @, $, !, %, \*, ?, &, ., -, #, >, <, +, =)

Second, we’ve made changes to how we send passwords via email. The only time we will send a password in an email is to new users. The password will be a temporary password, and the user will be required to change it right away. The Paradym system will not send password information via email under any other circumstances. If you receive an email purporting to be from Paradym requesting or providing password information, please notify your account representative.&#x20;

Third, we’ve updated the Forgot Password and Reset Password workflows. To verify the identity of a user who wants to change their password, we will send a verification code to the email address associated with their account. To change their password, the user will need to enter the verification code and their new password on the Reset Password page.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Paradym/10%20Oct%202022/2022-Oct-Paradym-Pasword.png)

Finally, the Change Password option has been removed from Broker Owner accounts. Broker owners will no longer be able to view or change agent passwords. However, broker owners can still log in as a particular agent if needed (this feature remains unchanged).

Bug Fixes&#x20;

•    We fixed an issue with a single photo showing multiple times in a listing tour. \
Previously, if a listing was imported with just a single photo, AutoTours would create a property tour using the one photo multiple times. \
Now, when AutoTours creates a tour from a listing with just one image, it will not duplicate the image in the tour.

•    We fixed an issue with AutoTours not creating a tour for some listings. \
Previously, if a listing was imported from ListHub or SimplyRETS without a listing date, AutoTours would not create a tour for the listing. \
Now, AutoTours will create tours for listings even when the Listing Date field is blank. \
&#x20;\
•    We fixed an issue with the weather on the Viewer Detail page showing an error. \
Previously, if a user navigated to the Viewer Detail page and selected Local Weather, it would display an error message. \
Now, when the weather option is selected, it will open the local weather page as expected.
