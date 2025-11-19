---
title: Agent Profile Zillow Display Rules
---

# Agent Profile Zillow Display Rules

There are 2 conditions that are used to determine if an agent's Zillow ratings and reviews will be displayed on their agent profile page.

**#1 - The agent has selected the setting in their Agent Portal to allow to display.**

![](https://support.realestatedigital.com/hc/en-us/article_attachments/211042007/Agent_Portal_Setting.png)

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/f7c89ca0-16a7-45ed-8964-00c613a55256.png)

RED calls this value from DataPassport, so first check to see if this is checked to allow or not.

**#2 - Verify that the agent's email address for their Zillow account is the same as their email address in RED's system.**

When RED makes the call to Zillow, we pass in the agent's primary email address. This email address has to match the email address of the agent's Zillow account. This is how we make the connection between RED and Zillow.

*   If the email's match, then results will get returned. Meaning the agent's Zillow rating and reviews will appear on their profile page.
*   If the emails don't match then their will be no results to return. Meaning the agent's profile page will not display either Zillow rating or reviews.

If both of these conditions have been met and the agent's Zillow items are not appearing on their profile page, then please open a ticket so we can investigate further.

Here is a manual way to check if an agent's email address will return results from Zillow. Replace the email address as needed in the following url, if you see results then that's their Zillow account's email address:

http://www.zillow.com/webservice/ProReviews.htm?zws-id=X1-ZWz1dzqnsh92bv\_39zrb&email=Jeremy.Rosenthal@LongandFoster.com&count=10&returncompletecontent=true&output=json

Was this article helpful to you?

Was this article helpful to you?