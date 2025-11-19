
# Paradym by Constellation1 August 2023 Release Notes

Production Release August 2023

## Release Summary

**Large Images:** Added process to resize large images before they are posted to social media.   
**New User Listings:** New listings will be posted to the agent blog only after their connection date.   
**Bug Fixes**

## Release Details 

Social Posts with Large Images   
We’ve improved how images are handled when an agent manually creates social posts. For square posts, photos should generally be no larger than 1024px by 1024px. In some cases, agents may try uploading larger photos, which could cause the post to fail.   
We’ve implemented a process to resize larger images to the proper size and ensure they post as expected. 

Bug Fixes 

1\. We fixed an issue with posts failing on X (formally known as Twitter).   
Previously, when Paradym tried posting to X, the posts would fail due to changes X had made to their API.  
Now, this issue has been resolved. We’ve upgraded the API and posts will publish as expected.

2\. We fixed an issue with assigning MLS IDs to agents when a new broker account was created and agents were added to it.   
Previously, when adding agent accounts to a newly created broker account, the system failed to correctly associate the agents’ MLS IDs with their accounts.   
Now, this issue has been resolved. We’ve updated the service that handles this process. 

3\. We fixed an issue with brokers getting the “Oops” error message when creating broker-level posts.   
Previously, when brokers tried to access their My Content page to create or edit a post, they were getting an error message.   
Now, this issue has been resolved. 

4\. We fixed an issue with brokers getting the “Oops” error message when trying to manually opt in a group of agents.   
Previously, when a broker tried to opt a group of agents in to company-level auto tours, they were getting an error message.   
Now, this issue has been resolved. 

5\. We fixed an issue with not showing the correct reason why photos were failing to post to Instagram.  
Previously, when attempting to post a PNG to Instagram, the post would fail due to the file type not being supported. The system would show a message indicating that the post had failed, but not the reason, so the user was unable to correct the problem by uploading a supported image type.  
Now, we have updated the error messaging to indicate that PNGs are not supported so that users can upload a supported image type to their post.