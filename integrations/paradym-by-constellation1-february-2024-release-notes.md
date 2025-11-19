
# Paradym by Constellation1 February 2024 Release Notes

Production Release February 2024

## Release Summary

**Link Social Posts to Blog:** Social posts can include links to the agent’s website blog.  
**Custom Disclaimers:** Now display on flyers.   
**Social Post URL’s:** Added secure layer to URL’s shared on social media.  
**Bug Fixes**

## Release Details 

Link Social Posts to Blog Site  
We have added the ability to share blog articles and property tours on social media and have those posts link to the agent branded website.   
In the connection settings for the blog, we have added two checkboxes that, when selected will post blog articles and property tours to social media and link to the related content on the agent website to help drive traffic to the website.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Paradym/2024/02%20February/2024-Paradym-BlogLinks.png)

Flyers Custom MLS Disclaimer   
Custom disclaimers are now displayed on flyers. When there is a custom disclaimer, it will be shown in the footer of property flyers.  

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/Paradym/2024/02%20February/202-Jan-Paradym-Disclaimer.jpg)

Secured Social Posts URL’s   
We have updated the URLs on social media posts to use the secure https protocol. This ensures that links will take users directly to the content instead of a browser warning when clicked.

  
Bug Fixes   
1\. We fixed an issue with special characters in the titles of social media posts displaying as ASCII characters.  
Previously, special characters displayed as ASCII characters instead of the characters they were meant to represent.   
Now, Special characters have been updated to display correctly. 

  
2\. We fixed an issue with users being logged out when editing leads.  
Previously, when a user edited a lead and subsequently canceled the change, the system redirected them to the login screen.  
Now, when clicking cancel, the user will be returned to the previous page as expected. 

  
Technology Updates  
1\. We’ve updated FLURL 3.0 to FLURL 4.0 to take advantage of Microsoft's System.Text.Json serializer, for improved performance.

2\. We’ve increased the frequency of pulling listing data from once daily to twice daily, on agent listings for property tours.