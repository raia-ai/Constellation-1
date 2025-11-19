
# Paradym by Constellation1 August 2022 Release Notes

Production Release #81: August 23, 2022

## RELEASE SUMMARY

**Auto Tours:** Added support for PNG images. 

**Lead Capture Codes:** Added ability to sort tours by lead capture code. 

**Bug Fixes**

## RELEASE DETAILS 

Auto Tours

We’ve added PNG image support for Auto Tours. This enhancement will make it easier to create and manage images for Auto Tours by expanding the number of acceptable file formats. 

Lead Capture Code  

We’ve added the ability to sort tours by lead capture code. These codes can be printed on signs or flyers to direct leads to a particular tour. In the tour list view, a user can now sort by lead capture code to identify the tour using that code then reassign it to a new tour or remove it from a sold or off-market property. 

Bug Fixes 

•    We fixed an issue with ListHub blocking agents who didn’t have a city or state associated with their account.    
Previously, when Paradym would connect to ListHub to retrieve an agent’s Auto Tours, ListHub would block access if certain information was missing from the agent’s account.   
Now, we’ve improved the code that connects with ListHub to allow us to pull the agent’s Auto Tours even if city or state isn’t provided. 

•    We fixed an issue that prevented CMAP and CMAF brokers from accessing their weekly summary report.   
Previously, when a broker would try to access their weekly summary report, they would get an error message.   
Now, when a broker accesses their weekly summary report, the report will open. 

  
•    We fixed an issue with Quick Chat freezing during the Awaiting Agent… step.   
Previously, when a consumer would try to chat with an agent using Quick Chat, the Quick Chat would freeze during the Awaiting Agent… step.   
Now, this issue has been resolved and the consumer will be able to connect with the agent and initiate the chat.