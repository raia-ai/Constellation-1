---
title: Using Your Domain Name With Top Producer Websites
---

# Using Your Domain Name With Top Producer Websites

Here are the steps to setup a domain name to point to a Top Producer Website and also to have the domain appear as a secure site without having to purchase or install an SSL certificate.  These steps will use a Godaddy account as an example.

1.  Log into Godaddy at [https://www.godaddy.com/](https://www.godaddy.com/) and click Sign in (top right) or to go [https://sso.godaddy.com/](https://sso.godaddy.com/)
2.  Click My Account in the upper left area, then click Domains.  
    ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/75fcef38-8168-475d-8559-a4dc3bb28b27)
3.  From the Domain Portfolio, click on the domain name used for TWS  
    ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/825e48e0-33de-48cc-8c16-f476929f6859)
4.  Click the DNS tab to access the DNS settings.
    
    ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/00336fba-6e9b-4160-9913-eefcb4db9152)
    
5.  From the DNS/Advanced DNS section, we will need to add a new A records, CNAMEs and TXT files. Click Add New Record button, we’ll start by adding the A Records which includes 3 sets of IP addresses:  
    Under Type, click the drop list and select the A record.  
    Under Name, type in the @ symbol.  
    Enter the IP addresses in the Value field. You can click the +Add another value link to enter multiple IP addresses for the A record type.  
    104.18.229.191  
    104.18.203.85  
    104.16.161.39  
    Leave the TTL value to ½ hour.  
    ![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/46a7dcaa-fcd8-4d3d-a5c0-1a12b0cdd22c)
6.  Click Save.
7.  Click Add New Record again, this time we are adding the CNAME type record.  
    For the first CNAME, enter \_dmarc into the Name field.  
    In the Value field, enter \_dmarc.topproducer.net. \*\*include the dot at the end of this value  
    Click +Add another value to include the 2nd CNAME.  
    For the second CNAME, enter tpo-tws-int.\_domainkey in the Name field.  
    In the Value field, enter tpo-tws-int.\_domainkey.topproducer.com. \*\*include the dot at the end of this value.
8.  Click Save All Records.
9.  Look for a CNAME with the name www.  It will likely exist already and have the Value using the domain name.  
    Edit the www CNAME to the following: tws-r.topproducer.net.  \*\*include the dot at the end of this value.  Leave the TTL to 1 Hour.
10.  Click Save.
11.  Look for a TXT record type that has a Value that begins with v=spf1 include  
    \-If you do not see one, click Add New Record.  Click the drop list under Type and select TXT.  Set the Name field to @.  Under the Value field, add v=spf1 include:\_spf.topproducer.com -all.  
    \-If you do find an existing TXT record, edit the value to add include:\_spf.topproducer.com before the -all section. Example: v=spf1 include:secureserver.net include:\_spf.topproducer.com -all
12.  Click Save.
13.  This concludes the DNS changes needed for the domain in Godaddy or domain registrar control panel.  You can now log out of the domain registrar control panel.
14.  Once these steps have been completed, please contact Top Producer Support and advise them your domain name is now pointing to the Top Producer Website servers, as there is an additional step that needs to be done to complete the domain setup.  Your domain name will then start to display your Top Producer Website within 24-48 hours.

Was this article helpful to you?

Was this article helpful to you?