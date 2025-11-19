# Constellation1 Website & CRM March 2022 Release Notes

Production Release: March 29, 2022&#x20;

## RELEASE SUMMARY

#### **Constellation1 CRM**&#x20;

**Action Plan Manager:** Improved workflow for publishing action plans.&#x20;

**Action Plan Manager:** Added ability to track the open rate of sent email messages in real time.&#x20;

**Documents:** Updated use of special characters in file names. &#x20;

**Calendar Events:** Activity Category is now a required field.&#x20;

**Architecture:** System upgraded to .NET Framework Version 4.8.

#### **Constellation1 Websites**&#x20;

**Website Admin:** Forgot Password link added to login page.&#x20;

**Blog Posts:** Improved workflow for managing blog posts.\
&#x20;

#### **Bug fixes**

## CONSTELLATION1 CRM&#x20;

Action Plan Manager Workflow Improvements

We’ve improved the workflow for publishing action plans. Previously when publishing an action plan, the user would need to navigate away from the action plan, or would be redirected back to the Action Plan Manager dashboard.&#x20;

Now, when a user publishes an action plan, either from the action plan details page or on the APM dashboard, the page will refresh to show the current publish status of the action plan. The user will no longer need to navigate away from the action plan details page and will no longer be redirected back to the first page of the APM dashboard.&#x20;

Real-Time Email Open Rate

It’s important to know if your leads and clients are opening your emails. With this release, we’ve improved the tracking code in emails sent from the CRM. This code tracks and reports the open rate of those emails and can now report open rates in real time.&#x20;

Detailed open rates are available in the APM Report, located in the Reports section.&#x20;

Tracked emails sent from the CRM include:

* Action plan emails
* Quick emails
* Flyers sent from the flyers module&#x20;

**Coming soon:** In phase two of this enhancement, we’ll release an open rate widget for the CRM dashboard.&#x20;

Documents&#x20;

We noticed some users were uploading documents and files with special characters in the file name. This caused an error when the user tried to open the file again.&#x20;

With this release, we’ve added a validation to file names when they are being uploaded to the documents module.&#x20;

If a user attempts to upload a file with special characters in the name, they will receive an error message and the file will not be uploaded.&#x20;

Special characters that are not allowed include: &, <, >, ", ', #, +, and %.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-March-DocsError.png)

Calendar Events&#x20;

Activity Category is now a required field when scheduling a calendar event, activity or To Do. \
By requiring the Activity Category, users will have better and more complete information regarding the event, appointment, or To Do.

This update includes events, appointments, and To Dos on the CRM mobile app and any other third-party sources where this information is shared.&#x20;

When adding a calendar activity, the following fields are now required:

* Activity Type
* Activity Category
* Subject&#x20;

Required fields are indicated with an asterisk.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-March-Calendar-Activity3.png)

Architecture&#x20;

We have upgraded the CRM platform from .NET Framework Version 4.5.2 to the latest version 4.8. \
This upgrade provides improved system performance and efficiency while keeping CRM on the latest available system version.

## CONSTELLATION1 WEBSITES

Website Administration – Forgot Password

On the website administration login page, we’ve added a Forgot Password link.&#x20;

When a user clicks the Forgot Password link, they will be prompted to enter the email address associated with their account. The system will then email a link allowing the user to reset their password. Links emailed to a user expire after 72 hours.&#x20;

Websites passwords must:

* Be between 4 and 16 characters
* Not contain any spaces\
  Not contain &, <, or >&#x20;

The Forgot Password link will be added to all website administration login pages.&#x20;

Note: In the case where user login info is managed in an external system, the link can be removed by request. Please contact your Constellation1 representative with any questions.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-March-ForgotPassword.png)

Blog Posts

We’ve made improvements to the workflow for working with agent blog posts.&#x20;

On the agent CMS and CMS Pro website administration dashboard, we’ve added a Create/Edit Blog link that allows agents to easily access their blog posts.&#x20;

The link is in the dropdown list under the agent’s name.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-March-Blog1.png)

When clicked, this will take the agent to the blog dashboard, where they can create new posts or edit existing ones.&#x20;

Additionally, when creating or editing a blog post, we’ve added a button allowing the user to upload a title image to the article. The user will no longer need to post the photo and add the URL of the photo in the post edit page.&#x20;

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Website%20CRM/CRM-2022-March-BlogPhotoUpload.png)

#### **BUG FIXES**

CRM Mobile&#x20;

* We have fixed an issue with selecting contacts. Tapping the check box next to a contact will now select or deselect the contact. &#x20;
* We have made some UI updates to error messages in the mobile CRM. The messages will now be formatted correctly.
