---
title: "Saved Search Emails"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/14381961"
tags: ["Reporting & Analytics"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Saved Search Emails | Constellation1 Customer Hub If you are receiving reports of saved search emails being received at a time different from when the"
long_description: "Saved Search Emails | Constellation1 Customer Hub If you are receiving reports of saved search emails being received at a time different from when the search was created, then there is a good chance that everything is working as intended. Below is a scenario that details the logic on how these emails get sent out. Update Time is set to “Daily”: If there is at least 1 “match” within the 24 hour time period from when a saved search is created, then the notification email will be sent out at the ti"
---

# Saved Search Emails | Constellation1 Customer Hub

If you are receiving reports of saved search emails being received at a time different from when the search was created, then there is a good chance that everything is working as intended.

Below is a scenario that details the logic on how these emails get sent out.

Update Time is set to “Daily”:

If there is at least 1 “match” within the 24 hour time period from when a saved search is **created**, then the notification email will be sent out at the time the search was **created**.

Example #1:  Saved search was created at 4pm, and two matches happened sometime in the middle of the night when new listings were imported, then this means that a notification email will be sent at 4pm.  If matches are made every night, then this means the emails will continue to go out at 4pm every day. 

If there are **NO** matches within the 24 hour time frame, then the emails will be sent out at the time when a match occurs.

Example #2:  A user created a saved search at 4pm but the search criteria was very narrow, thus no matches were made in the first 24 hours.  Two days later, a match was made at 11AM.  Within a few minutes of a match being made, the system will send out a notification email.  This will then **restart** the “24 hour clock” meaning that if additional matches are made within the next 24 hours, then the next email will be **sent out again** at 11AM. 

To summarize: if you have a search that uses few search criteria and it is likely that matches will occur daily, then an email will be sent out every 24 hours from the time the search was created. Otherwise if there are no matches in that time frame, the emails will become decoupled from when the saved search was created and will begin to send out at the time a new match was found.

"Weekly" and "Monthly" updates work the same as the "Daily" update scenario except instead of a 24 hour period it is the corresponding time frame; ie "Weekly" updates mean a week long time frame and "Monthly" updates mean a month long time frame. 

**_\*\*\*\*\*IMPORTANT NOTE\*\*\*\*\*_**

Please DO NOT confuse Saved Search Emails with Saved Property Emails. These are two different things and work differently.

Saved Property Emails do not have a frequency that is set, instead they send on demand as an update is found.