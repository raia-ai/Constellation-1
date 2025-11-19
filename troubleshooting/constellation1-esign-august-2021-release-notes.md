
# Constellation1 eSign August 2021 Release Notes

Production Release: August 24, 2021

## RELEASE SUMMARY

**LogMeIn API Improvments:** Manage whether to display the “Add” signing session button in eSign and support for creating new groups has been added.

**Bug Fixes.  
**

Manage the display of the Add button through the API

The LogMeIn API supports creating a signing session in eSign. You can now use the API to display or hide the “Add” signing session button in eSign. This new feature helps to avoid confusion and provide a single source for created new signing sessions. The API has been updated to include a parameter that will allow you to display or hide the “Add” button in eSign. API parameter: {allowAddSession}: true/false to control the ability to allow adding sessions. The default is set to false, meaning the button will be hidden by default and you will need to choose to display it.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign-2021-August-AddButton.png)  

For more details regarding the LogMeIn API [Click Here](https://docs.constellation1.com/api/intergration-strategies-and-workflows/logmein-esign-2-0 "eSign LogMeIn 2.0")

Create Groups Through the API

You have already been able to edit and manage groups in eSign through the API. Now you can also create new groups. We have updated the API to include a parameter that will pass in the new group information and create the group in eSign. This parameter allows you to have one source of information and to automate the group creation process.

API request body:

{ "username" : "john.smith@constellation1.com", "group": { "LeftMenuColorHex" : "", "EmailThemeColorHex" : "", "Name" : "add group name here", "CustomerName" : "add customer name here", "CustomerAddress1" : "add customer address here", "CustomerAddress2" : "add customer address 2 here", "CustomerCity" : "add city name here", "CustomerState" : "CT", "CustomerCountry" : "US", "CustomerZipCode" : "54000", "CustomerEmail" : "jsmith@abc.com", "CustomerPhone" : "(111)111-1111", "WebhookUrl" : "https://www.abc.com", "IsActive" : "1" } }

#### Bug Fixes

*   We have fixed an issue where editing a bulk session would cause an error.
*   We have fixed an issue so the font in the initials field to matches the font used in the signature field.
*   We have updated check boxes and radio buttons to be mobile responsive.
*   We have fixed an issue with copied templates so the size and formatting of signing tags is maintained.