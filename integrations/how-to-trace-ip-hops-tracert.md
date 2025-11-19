# How To Trace IP Hops - Tracert

Follow the below instructions on your computer to see how your ISP is routing you to the website. This can be useful in determining how areas on the website are determining your location.

**Note:** Depending on router/ISP configurations you may not get all results returned when running this command. You may see several lines of  '\* \* \* Request Timed out'. Again this is no error on your part.

For Windows -

Click on start.\
Click in the search box.\
Then type cmd (or command prompt)\
Once you have your Terminal box open, type in the following but be sure to replace example.com with your domain name:\
tracert example.com

You should see a response similar to the following:\
Tracing route to example.com \[64.13.192.208]\
over a maximum of 30 hops:

1 <1 ms <1 ms <1 ms 72.10.62.1\
2 <1 ms <1 ms <1 ms 10.101.248.1\
3 1 ms <1 ms 1 ms 10.104.65.161\
4 1 ms 5 ms 1 ms 10.104.0.1\
5 2 ms 2 ms 3 ms 10.0.10.33\
6 5 ms 3 ms 2 ms example.com \[64.13.192.208]

Trace complete.

(it will look something like this)

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/af797561-a72e-4690-ac3f-d2304a9f9cb3.png)

From here, you can take the IP addresses displayed and plug them into an IP lookup website/tool to see where they physically are located.

Example of such a site - http://www.ip-tracker.org/locator/ip-lookup.php

Note: Depending on ISP configurations, and what tool/site is used for tracking, they may not give location details to the IP address.&#x20;

To find out your public IP address - google "What Is My IP Address" and it should display on the screen.

Was this article helpful to you?

Was this article helpful to you?
