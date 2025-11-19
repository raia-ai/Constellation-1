
# Constellation1 eSign September 2021 Release Notes

Production Release: September 21, 2021

## RELEASE SUMMARY

**LogMeIn API Improvement:** Change a user’s role through the API.

**Bug Fixes**

CHANGE USER ROLES DIRECTLY THROUGH THE API

The LogMeIn API supports eSign signing session creation. We have updated the API to allow system administrators to update a user’s role directly through the API. You will no longer need to be logged in to eSign to make these role changes.

This can be done using the following API request. Note that the email addresses of the administrator and the user who is being updated are needed to complete the request.  

Type: "PUT". Body: { "username" : "Administrators@email.com", "groupUser" : "User@beingUpdated.com", "userRole" : "admin" }

Bug Fixes

*   We fixed an issue with the date/time markup tag. The font will resize after setting a larger font size.
*   We fixed an issue with filtering signature sessions by date. Selecting “today” or “yesterday” as the filter option now returns results.  
    
*   We fixed an issue that prevented a signer from scrolling to the top of a zoomed-in document to access the “Done” button to complete a signing session.
*   We have fixed an issue that prevented a signer from scrolling left and right on a zoomed-in document when using a mobile device.
*   We fixed an issue with rDocs clients not being able to apply a template to a signing session through the API.  
    
*   We have improved security for document signers. When emailing a signing session link to someone else, the recipient will now be required to log in to the session.  
    
*   We have fixed an issue that prevented signers from using the Tab button to move through a document during a signing session.  
    

Was this article helpful to you?

Was this article helpful to you?