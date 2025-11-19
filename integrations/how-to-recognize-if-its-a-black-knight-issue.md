# How To Recognize If Its A Black Knight Issue

The Black Knight pulls their data from public records for recently sold, so it is irrelevant of a MLS has sold information.

We are most likely able to provide information in the aggregate regarding sale information (MLS) but cannot provide property level information due to MLS restrictions. They make an XML call to us so we do not support printing.

**We use Black Knight data throughout the rW website.  Here are some examples:**

1\. Nearby Sales & Sales History on the property detail page.  This tab is called the “Sales History.”

![](https://support.realestatedigital.com/hc/en-us/article_attachments/201884925/BlackKnight.jpg)2. Market Trends data (marketvalue.aspx, marketvalue5.aspx)

![](https://support.realestatedigital.com/hc/en-us/article_attachments/201810119/BlackKnight3.jpg)3.  When you use the developer tools within Chrome, Firefox or IE, you can trace to see what API call is being made to fetch the data.  In ALL cases where we use Black Knight data, we make a call to their API that looks like this (for example).  When you see “xml.sitexdata.com”, this is an indication that we’re using Black Knight.

[http://xml.sitexdata.com/restapi/Service/ADDRESSSEARCH/55E68A07-FEFC-4C78-A16A-C10B937174CE\_1/875%20Rusk%20St%20%20New%20Braunfels%20%20TX/128\_1/\_/Data?callback=rw.ui.PropertyHistory.callBackPropertyHistory\&noCacheIE=1](http://xml.sitexdata.com/restapi/Service/ADDRESSSEARCH/55E68A07-FEFC-4C78-A16A-C10B937174CE_1/875%20Rusk%20St%20%20New%20Braunfels%20%20TX/128_1/_/Data?callback=rw.ui.PropertyHistory.callBackPropertyHistory\&noCacheIE=1)

**Who do you contact if you find a Black Knight issue?**

An email detailing the issue along with proper steps to recreate should be sent to the following distribution list:   [ClientIntegrations@bkfs.com](mailto:BlackKnightDNA.ClientIntegrations@bkfs.com)

Was this article helpful to you?

Was this article helpful to you?
