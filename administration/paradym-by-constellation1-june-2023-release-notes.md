---
title: Paradym by Constellation1 June 2023 Release Notes
---

# Paradym by Constellation1 June 2023 Release Notes

Production Release June 2023

## RELEASE SUMMARY

  
**My Tours:** Increased cover photo size to a maximum of 1080x810.   
**Social Posting:** Exclude comments field when there are no comments in the post.   
**Architecture:** Improved website security.   
**Bug Fixes**

## RELEASE DETAILS 

My Tours    
We have increased the maximum allowable size for the cover photo for property tours posted to Instagram.   
The photo size has been increased from 640x480 to 1080x810. 

Social Posting on Instagram   
We’ve updated the social posting on Instagram to exclude the comment fields when there are no comments. This avoids posting blank space to Instagram. 

Architecture  
We’ve improved the security of the website. The changes include removing security.asp and replacing it with a newer version of Bootstrap security.  
The changes are invisible to the user however the new security feature is used on the login screen, Forgot Password, Administrator and Broker security when accessing broker features on the Paradym website. 

Bug Fixes 

1\. We fixed an issue with connecting to an Instagram Business account on the Social Media Connections page.   
Previously, when a user selected to connect to an Instagram Business account and they didn’t have an Instagram Business account, they would receive an error message.   
Now, when a user selects to connect to an Instagram Business account and they don’t have an account, the user is redirected back to the Social Media Connections page with a message indicating that an account was not found. 

2\. We fixed an issue with connecting to Instagram if the user has multiple accounts.   
Previously, users who have multiple Instagram accounts, tried to connect to Instagram, the system was not able to connect to their selected account and the user would receive an error message.   
Now, this issue has been corrected and the user with multiple Instagram accounts will be able to select the account that should be connected to their Paradym account. 

3\. We fixed an issue with social media posts being stuck in pending status.    
Previously, when posting to social media, the post would remain in Pending status and not be posted to their respective social media account.    
Now, this issue has been resolved. 

4\. We fixed an issue with posts to Instagram showing an Authorization error message.   
Previously, when posting to Instagram the user may have received an Authorization Error message. This error message was not accurate about the cause of the issue. The issue was an image was too large for Instagram.  
Now, this issue has been corrected. When an image is too large to post to Instagram, the user will receive the correct messaging to resolve the issue.  

5\. We fixed an issue with posts to Instagram for a user being terminated.   
Previously, if a post to Instagram failed, the system would terminate the users connection, preventing future postings to be posted.   
Now, this issue has been corrected. If a single post fails, the system will not terminate the users connection to Instagram. 

  
6\. We fixed an issue with broker tours being posted to YouTube twice.   
Previously, when a video was posted to YouTube from a Broker account, the system would duplicate the post, causing the video to show twice on the brokers YouTube account.   
Now, this issue has been resolved.