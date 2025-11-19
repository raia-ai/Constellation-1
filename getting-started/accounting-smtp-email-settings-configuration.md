---
title: Accounting - SMTP Email Settings Configuration
---

# Accounting - SMTP Email Settings Configuration

This article will guide you to set up Constellation1 Accounting's email settings to allow for commission statements to be emailed directly from the program instead of printing physical copies or saving statements to PDF to be emailed manually. Please follow the steps below:

1\. Navigate to **System > Setup > SMTP E-Mail Settings**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/83667129-9ccc-4bf2-8d66-f78ae1992544)

2\. Select the **Add** button

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/674bdc7e-c149-4be7-9d18-aedd45cb762f)

3\. Enter the applicable **E-mail From** address that will be used 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/98d53b6e-e67a-41e5-bd54-5e62f30fa4eb)

4\. Enter the matching password for the email address being used. **PLEASE NOTE**: If you are using multi-factor authentication with your email address, you may need to create an app password for this function to work correctly for you. For more instructions on how to create an app password, please review the following articles:

**Microsoft**: [How to get and use app passwords - Microsoft Support](https://support.microsoft.com/en-us/account-billing/how-to-get-and-use-app-passwords-5896ed9b-4263-e681-128a-a6f2979a7944) 

**Google**: [Sign in with app passwords - Google Account Help](https://support.google.com/accounts/answer/185833?hl=en) 

5\. Under **SMTP Server URL** and **SMTP Server Port #**, enter the following details depending on the email service you are using:

**Microsoft**:

SMTP Server URL: smtp.office365.com

SMTP Server Port #: 587

**Google**:

SMTP Server URL: smtp.gmail.com

SMTP Server Port #: 587 (TLS) or 465 (SSL)

6\. Ensure the **Use SSL/TLS?** box is checked, as current authentication requirements for most SMTP setups require this.

7\. Click **Save**.

Once these steps are complete, you can test to ensure that you have configured everything correctly by entering a different email address in the **Recipient E-mail** field, then clicking **Send Test E-mail**. A message should appear in that address' inbox if your configuration is correct.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a3f534b9-e11b-45c3-8713-1ef962a78cde)