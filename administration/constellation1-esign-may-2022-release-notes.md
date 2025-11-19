---
title: Constellation1 eSign May 2022 Release Notes
---

# Constellation1 eSign May 2022 Release Notes

Production Release: May 26, 2022

## RELEASE SUMMARY

**  
Email Notification Settings:** Changed settings from buttons to toggles. 

**Pausing Signing Sessions:** Improved functionality when pausing a signing session. 

**Hide Markups Tools:** Added option to hide Markups tools for specific groups.  

**Bug Fixes  
**

## Release Details  

Email Notification Settings

We’ve improved the user interface for enabling or disabling email notifications. Previously, on the Profile page under Email Notifications, the UI featured buttons that would turn blue when the particular notification type was enabled (clicked). 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-1.0%20email%20notifications%20button%20toggle.png)

Now this page features toggles for enabling or disabling specific notifications. This update helps make email notification settings more intuitive and user-friendly. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-2.0%20email%20notifications%20suggested%20switch%20toggle.png)

Pausing Signing Sessions

We’ve improved the flow for pausing signing sessions. Previously when pausing a session, the user was taken to the Status page and was not notified they were entering edit mode. 

Now with this enhancement, when pausing a signing session, the session creator (user) will see a modal informing them they are entering edit mode. Clicking Confirm will take the user to the session builder page, where they can edit the signing session. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-Session-Edit-Message.png)  
Notification Modal  

Hiding Markups Tools  

We’ve added the ability to hide or show Markups tools at the group level, giving you more flexibility for managing groups. Now, there is a Markups toggle on the Group Information page where an administrator can enable or disable a groups’ ability to access the Markups tools. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-HideMarkups.png)

This feature is also available to API users. Click [HERE](https://docs.constellation1.com/rest-authentication-header/rest-group-management-header/rest-creategroup "Create Group API Documentation") to view the CreateGroup API documentation and [HERE](https://docs.constellation1.com/api/api-reference-overview/group-management/updategroup "Update Groups API Documentation") to view the UpdateGroup API documentation.

Click [HERE](https://docs.constellation1.com/groupview "API Request Return Appendix B") to view the API RequestResponse in Appendix B. 

**Note:** SOAP users will need to refresh their endpoint to access this feature.  

BUG FIXES

1, Ticket no.: GPES-3070  
Fixed an issue with system templates being accessed by users. Previously, Constellation1 rDocs users who were not administrators had access to system-level templates. Now, system templates will only be accessible to rDocs users who are administrators. 

  
 ![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-System%20Templates1.png)  
Before

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-System%20Templates2.png)

After

2, Ticket nos.: GPES-3006, GPES-3007, GPES-3008, and GPES-3073   
Fixed an issue with templates created in eSign 1.0 not converting to eSign 2.0. Previously, when creating a signing session in eSign 2.0 using a template that was created in eSign 1.0, the session creator (user) would receive the message, “Failed to convert 1.0 tag to 2.0”. The resulting tags would change size and position, overlap other tags, and were not transparent. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-Tags1.png)

  
 Now, when creating a signing session in eSign 2.0 using a template created in eSign 1.0, the tags will convert successfully and will be the correct size, in the correct location, and be transparent. Bulk session templates are also included in this update. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-Tags2.png)

  
3, Ticket no.: GPES-2813  
Fixed an issue with the Form Field tag not retaining its set size. Previously, the Form Field would expand to the edge of the page as a user typed in the field.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-FormField2.png)

Now, when typing in the Form Field, it will remain the set height and width. When the text reaches the set width of the text box, it will wrap to the next line and possibly become smaller to fit in the box.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-FormField1.png)

  
4, Ticket no.: GPES- 2958  
Fixed an issue with bulk sessions that allowed the session creator to add Reviewers and CC Recipients to the session. Now when creating a bulk session, the session creator will only be allowed to add signers. 

5, Ticket no.: GPES-2874  
Fixed an issue with images of wet signatures not displaying properly on the Certificate of Authenticity. Previously, the signature may have appeared pixelated or choppy. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-Signature1.png)

Now, signature images will be an accurate representation of the wet signature. 

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/2022-esign-May-Signature2.png)