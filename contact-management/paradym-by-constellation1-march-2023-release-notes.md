
# Paradym by Constellation1 March 2023 Release Notes

Production Release March 2023

## RELEASE SUMMARY

**User Interface:** Updated how buttons display for an intuitive and consistent user experience.    
**Bug Fixes**

## RELEASE DETAILS 

User Interface Updates    
We’ve updated the button color and order for a more intuitive and consistent user experience:  
•    Buttons with a positive action, such as Save or Continue, are colored green.  
•    Buttons with a neutral action, such as Cancel, are colored gray.  
•    Buttons with a negative action, such as Delete, are colored red. 

Bug Fixes   
1\. We fixed an issue with the main photo not being sent when a user requests property details via SMS/text message.   
Previously, when a user would send a code via SMS/text message to receive more details about a specific property, the property’s main photo was not being sent in the return message.   
Now, when a request for more property details is sent via SMS/text message, the property’s main photo will be sent in the return message. 

2\. We fixed an issue with Social Posts failing when posting to LinkedIn.   
Previously, when Social Posts were set up to be posted to some LinkedIn accounts, the posts would fail.  
Now, we have corrected this issue. Social Posts to LinkedIn are now working as expected. 

3\. We fixed an issue with brokers being charged twice when submitting a payment online.   
Previously, when a broker would pay their bill online, in some cases, the broker would be charged twice.   
Now, we have corrected the issue and credited or reversed any overpayments. 

4\. We fixed an issue with Matterport property tours not showing in My Tours.   
Previously, when a user would link a Matterport 3D tour to a property tour, the 3D tour would not show due to the default URL not being secure (HTTPS).   
Now, we have corrected the issue by securing the URL needed to download the 3D tour. When a user links a Matterport 3D tour to their property, the 3D tour will display as expected. 

5\. We fixed an issue with an agent profile showing a default cell phone number when the agent didn’t have a cell phone number listed in their profile. 

Previously, in some cases, the agent’s contact information in a property tour would show a default cell phone number if the agent hadn’t added a cell phone number to their profile. 

Now, we have fixed this issue and if an agent doesn’t have a cell phone number, no cell phone number will be displayed in the agent’s contact information for a property tour.