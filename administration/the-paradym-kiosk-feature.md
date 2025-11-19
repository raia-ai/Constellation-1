---
title: The Paradym Kiosk Feature | Constellation1 Customer Hub
---

# The Paradym Kiosk Feature | Constellation1 Customer Hub

The Paradym Kiosk Feature

A Handy Tool to Display a Series of Tours One After the Other

Would you like to display a series of tours for your newest listings in your office lobby or window display?  Perhaps instead, you want to highlight some older listings that need a little attention?  Pricier listings?  Use Paradym's Inventory Kiosk Feature!

The Inventory Kiosk feature allows you to display a series of tours one after the other, each displaying for a set amount of time (that you choose) on a large monitor in your office's lobby, office storefront display, or a mall kiosk. 

To see a quick demo of how this feature displays multiple tours, visit this link:  
[https://view.paradym.com/kiosk/123456](https://view.paradym.com/kiosk/123456)/  
(but change 123456 to your own account number)

Not sure what your account number is?  Just log into your Paradym account, and choose Settings from the drop down menu with your name in the upper right of the screen.  Next, you can click Profile on the left to see your account number near the top of the screen.

Of course, you can adjust a few settings to allow you to control which tours are shown and for how long each appears on the screen.  Here is a quick summary of the options you can add to the link.  We’ll describe them in greater depth below the summary.

Basic Link: https://view.paradym.com/kiosk/\[your account number\]/

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| Options You Can Add |     | Purpose |     | Example |
| ?top=\[number\] |     | This option controls HOW MANY recent tours will be displayed before repeating. |     | [https://view.paradym.com/kiosk/247474/?top=2](https://view.paradym.com/kiosk/247474/?top=2)  <br>In this example, top is equal to 2, so it will only show 2 tours before repeating.  Admittedly, showing only 2 tours is not very useful, but it is very effective to demonstrate how this feature works. |
| ?delay=\[number\] |     | This option controls HOW LONG to play each tour before moving to the next. |     | [https://view.paradym.com/kiosk/247474/?delay=3](https://view.paradym.com/kiosk/247474/?delay=3)  <br>In this example, delay is set to 3, so each tour will display for only 3 seconds before the next tour is loaded.  It is doubtful that anyone would set the duration to such a short period, but for the purpose of demonstrating the option, a lower setting will show you how it works without making you wait. |
| ?f=\[filter number\] |     | This option controls WHICH tours will be displayed.  It uses predefined filters, which are described in more detail later in this document. |     | [https://view.paradym.com/kiosk/247474/?f=195277](https://view.paradym.com/kiosk/247474/?f=195277)  <br>In this example, we are specifying to use the tours defined by filter 195277, so we will see a different list than if we do not specify which tours to use. |
| ?o=\[office number\] |     | This option will allow multi-office broker accounts to specify that they only want to display tours from a particular office. |     | [https://view.paradym.com/kiosk/247474/?o=12](https://view.paradym.com/kiosk/247474/?o=12)  <br>In this example, we are specifying to display tours only from office 12 |
| ?sk=400 |     | If you want full screen photos, you can use this option, but it will remove agent branding from the top AND limit you to seeing only three scenes of each tour.  A better option for larger images is to use CTRL-mouse wheel or your browser’s Zoom setting to zoom in a little |     | [https://view.paradym.com/kiosk/247474/?sk=400](https://view.paradym.com/kiosk/247474/?sk=400) |

**Can I use more than 1 option at a time?**

Yes, of course you can.  Just add an ampersand character between multiple desired options, and do not repeat the question mark.  For example, if you want each tour to play for 20 seconds AND you want to play the most recent 50 tours, then you can combine the **?delay=20** and **?top=50** like this:

[https://view.paradym.com/kiosk/247474/?delay=20&top=50](https://view.paradym.com/kiosk/247474/?delay=20&top=50)

You can place the extra parameters/options in any order you want.

Additional Information

Let’s look at each option in more detail.

**Controlling HOW MANY Tours are Displayed:**

As noted above, you can change how many tours are displayed by adding **?top=\[number\]** to your link.  Of course, if you only have 20 tours and you specify **?top=25**, we won’t display 5 extra tours.  Oh, if only it were that easy to get new listings! 

If you do not use this parameter in the link, then 10 recent tours will be displayed.  If you want to use an unlimited number of tours, set this to 0.

**Controlling HOW LONG Each Tour is Played Before the Next Tour Loads:**

The **?delay=\[number\]** option controls how many seconds each tour will be displayed before the next tour loads.  If you do not choose how long to display each tour, then expect to see them play for approximately 10 seconds each.

**Using Filters to Control WHICH Tours are Displayed:**

Unless you specify a filter to use, the kiosk link will use your default Showcase filter to decide which tours to include, and then it will display the most recent 10 (or a different number if you used the “top=” option previously discussed to change the quantity). 

If you are not familiar with the filters, you can find them by logging into your account and clicking Settings from the drop down menu with your name then clicking Showcase on the left.  The filter list appears at the bottom of the screen. 

These filters allow you to create separate lists of your property tours to meet certain criteria.  Instead of your list showing all of your tours, perhaps you only want people seeing your active properties.  Perhaps there are times when you want to show all of your successfully sold listings, so you want to filter your tour list to only display sold properties.  Maybe you want to show only properties in a certain price range or single family homes vs. condos and townhomes. These filters are used by your Showcase Inventory page (an entirely different topic, but feel free to call us for more info) as well as this Kiosk feature.

By default, the kiosk feature will use the default filter (indicated by a filled in selection circle), which in the case below is Active Listings.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/fee83e52-769b-4308-a4b6-acde8c562f3f.png) 

You can click EDIT to see how the filter is defined.  In the case of this screen, the Property section shows us that it will display tours that are marked as Active, are either single family homes, condos, or townhouses, and are priced higher than $10,000 (a common trick people use to avoid letting rentals slip into a list since they are generally lower priced).  Change any criteria desired for any filter, or on the previous screen, click the option to create a new filter (visible until you reach the maximum total of 5 filters). 

 **![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/6309a77f-3d6d-482c-a83c-3026a6bf771f.png)**

**So how do I add the filter to the kiosk link?**

As we noted in the chart above, you want to add the f=\[filter number\] parameter (preceded by a question mark or ampersand) to the link, so you will need to know that filter number.  Once you have created a filter (or chosen an existing one), bring up the EDIT screen as though you are going to make changes.  Now look in your browser’s address bar to see what page you are viewing.  That link will show the filter number.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/f6cdc4bd-f441-413c-89cd-72ff7d93d2a1.png) 

In this case, the filter number is 190276, so the link will be:  
https://view.paradym.com/kiosk/\[your account number\]/?f=190276

or combined with other options:  
https://view.paradym.com/kiosk/\[your account number\]/?delay=30&f=190276

\* Note that if two people set up identical filters, those filters will NOT have the same filter number.  Always check the filter number in your own account.

**Using the Office Number to Limit the Tours Seen to Only One Office**

If you have a company level account but only want to display the tours for one office, you can specify the office by adding the o=\[the office number\] parameter to the kiosk link.  You will just need to determine the office number, which you can do by viewing it in your browser’s address bar.  The office number will appear in the address bar when a multi-office company account clicks the name of any office on the Account Management screen. 

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/7bff2b1e-3eae-46e3-8b81-92beea61be85.png)

In this case, it is 8205, so the kiosk link would be  
https://view.paradym.com/kiosk/\[your account number\]/?o=8205

or combined with other options:  
https://view.paradym.com/kiosk/\[your account number\]/?delay=30&o=8205

FAQ

**Can I specify to combine the tours for a couple of agents who work as a team but have their own individual accounts?**

If you wish, you can include more than one agent’s account number in the URL and separate them by a comma.

To combine the tours for accounts 12345 and 112233, for example, you would use this link:  
[https://view.paradym.com/kiosk/12345,112233](https://view.paradym.com/kiosk/12345,112233)

Since the kiosk includes some agent branding at the top, be aware that the branding shown will be for the first account number listed.

**One of my tours is not included when I use the kiosk feature.**

More than likely, you have a filter problem.  Check the criteria for your default filter or the filter you specified.   Also, check the filter number in your link since every account has its own filter number list, even if two people have their filters set up identically.

If you have any questions about the kiosk, just email us (support@paradym.com) or give us a call at 800-873-0700.  Live support is available Monday through Friday from 9AM to 6PM Eastern time.