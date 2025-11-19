---
title: CRM - Contact Scoring | Constellation1 Customer Hub
---

# CRM - Contact Scoring | Constellation1 Customer Hub

rDesk CRM Contact Scoring allows you to quantify website behavior by applying values to key behaviors so you can better engage, market to, and manage these leads based on their contact score. This guide covers all of the features in CRM that utilize contact scoring.

**Contact Scoring for Contacts and Leads**

Admins can view the contact scores on the Manage Leads grid for the assigned and unassigned leads.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/405ebb58-00fb-49d8-b340-569e9214a2ea.png)

The score will also display on the Contact record for Agents and Lead record for Admins.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/901b8475-f1c8-40ac-ba3b-374176e2a63b.png)

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/5fdff9d1-5fe5-42ab-ad48-8de80b0ec51f.png)

The score will change dynamically as the contact performs specific behaviors(increases) and as time passes since the behavior was captured(decreases). Scores will display in five ranges and each range has a designated color.

Click the carrot icon to sort scores in ascending or descending order in the grid.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/fe4d1081-3e03-4dc8-be99-24bb20d8b815.png)

![](https://support.realestatedigital.com/hc/en-us/article_attachments/201869005/10.jpg)

**Contact Scoring Admin**

CoBrand Admins and Broker Lead Admins can customize their contact score behaviors and values in the user interface.

1.  Login to CRM
2.  Click **Administration**
3.  Click **CoBrand Admin/Broker Lead Admin**
4.  Click on the **Contact Score** tab
5.  Click on the dropdown to select if you are revising settings for the entire company/franchise (default) or to select a specific office/broker

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/2c709b0b-9709-4678-9699-889695f92fd5.png)

![](https://support.realestatedigital.com/hc/en-us/article_attachments/201868995/5.jpg)

_Note: If you revise the settings at the Company/Franchise level, these settings will push down to all offices/brokers. If you revise the settings for a specific office/broker, these will not roll up to the company/franchise or to other offices/brokers._

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/482fb64c-07c5-43ca-9cef-fc564ee91e5d.png)

*   The default system settings will initially display (See Definitions below)
*   To change the settings, move the slider to the right to increase the value and to the left to decrease the value
    1.  For Initial and Incremental Scores, the lowest is 0 and highest is 10
        1.  If set at 0, the behavior will not be tracked
    2.  For Days to Monitor, you can set from 30 to 60 to 90
    3.  Click **Save All** to save your new settings
    4.  Click **Reset All** to reset to the system default settings

 **Contact Scoring Report**

The Contact Scoring report allows all users to run a report to be able to view and monitor their contact scores.

*   Login to CRM
*   Click **Contacts**
*   Click **Reports**
*   Select **Contact Scoring Report** from the dropdown
*   The Select Parameters, Date Selector, and Legend will display
*   Choose the Office/Broker and/or User
    1.  If logged in as a Company/Franchise Admin, you can choose Office/Broker
    2.  If logged in as an Office/Broker Admin, the office/broker will default and you can choose User
    3.  If logged in as an Agent/User, the office/broker and user will default
*   Using the Date Selector, choose the **Month** and **Year**
    1.  The date range will only show a month, if it is April 15th and you choose April, you will only receive results for two weeks
    2.  You can only run the report going back six months\*, if you choose a wider range, you will not receive results

_\*Note: This is based that we have been capturing contact score data for your company for this period of time._

*   Click **Run Report**

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/038e1aae-f566-4e55-8e10-6072e7b5f5ce.png)

*   The report will display,
    1.  Contact Name
        1.  Click in the name will take you to the contact record (Agent view) or lead record (Admin view)
    2.  Email Address
    3.  Primary Phone
    4.  Score
        1.  Contact score as of the end of the reporting period, roll up of all behavior initial and incremental scores minus deterioration
    5.  Time Period Left
        1.  Time period left based on Days to Monitor, showing longest period left
    6.  Details
        1.  When clicked will show behaviors and values that make up score
    7.  Assigned To (Admin view)
        1.  Shows agent currently assigned to contact, must be either a lead or client contact type

_![](https://support.realestatedigital.com/hc/en-us/article_attachments/201788409/8.jpg)_

![](https://support.realestatedigital.com/hc/en-us/article_attachments/201869135/9.jpg)

_Note: Contacts that are active and have a contact score as of the end of the reporting period will display._

_Example 1: If a contact performs and logs a score on the 1st, your days to monitor are set at 30 days, and the end of the reporting period is the 31st, they could be at zero and will not display on this report._

_Example 2: If a contact performs and logs a score during the reporting period but is then deleted, they will not display on this report._

1.  Use the arrows to scroll through each page
2.  Use the dropdown to adjust the viewable display size, 100% is the default
3.  Use the Find Next to search
4.  To export and print your report,
    1.  Click the **Select a format** from the dropdown
    2.  Export options will be CSV and PDF

**Definitions**

The default setting for each behavior is as follows;

*   Listing Inquiry
    *   Initial score = 8
    *   Incremental score = 4
    *   Days to monitor = 30
*   Showing Request
    *   Initial score = 9
    *   Incremental score = 4
    *   Days to monitor = 30
*   Contact Me
    *   Initial score = 5
    *   Incremental score = 3
    *   Days to monitor = 30
*   Mobile lead showing request
    *   Initial score = 10
    *   Incremental score = 5
    *   Days to monitor = 30
*   Mobile lead listing inquiry
    *   Initial score = 9
    *   Incremental score = 4
    *   Days to monitor = 30
*   What is my home worth (CMA)
    *   Initial score = 7
    *   Incremental score = 3
    *   Days to monitor = 30
*   Registration
    *   Initial score = 3
*   VOW (Virtual Office Website) Registration
    *   Initial score = 4
*   Registered user website visit
    *   Initial score = 5
    *   Incremental score = 2
    *   Days to monitor = 30
*   Saved Properties
    *   Initial score = 7
    *   Incremental score = 2
    *   Days to monitor = 30
*   Saved Searches
    *   Initial score = 5
    *   Incremental score = 2
    *   Days to monitor = 30

The scores for each behavior will be calculated as follows,

*   Initial score
    *   Score when contact initially performs behavior
*   Deterioration per day/initial score
    *   Deducted from the score each day following the initial action
    *   Calculation of initial score divided by the days to monitor
*   Incremental score
    *   Added score when contact performs the same behavior within the time period to monitor
*   Deterioration per day/incremental score
    *   Deducted from the score each day following the incremental action
    *   Calculation of incremental score divided by the days to monitor
*   Days to monitor
    *   For each individual behavior that is initiated, if it is not repeated, the contact score will decrease over this time period
    *   If the contact initiates and/or repeats a different behavior, that time period will be monitored separately but will be added to the other behaviors for a total time period left

The Contact Scores will display as follows,

*   Contacts must be active for the score to display
*   Contact scores of zero will display as blank
*   Scores will be rounded “away from zero”
    *   4999 will be 16
    *   5 will be 17
*   Scores will sort based on the actual versus displayed score.
    *   Contact scores are 16.1, 16, and 16.2. Sort order ascending will order the contacts for the actual scores of 2, 16.1 and 16 although 16 displays for all three contacts
*   Scores will display in five ranges based on a percentage from the maximum and each range will have a designated color,
    *   Top           20%: Green  
    *   Top-Middle 20%: Blue
    *   Middle         20%: Brown
    *   Bottom Middle 20%: Orange
    *   Bottom          20%: Red