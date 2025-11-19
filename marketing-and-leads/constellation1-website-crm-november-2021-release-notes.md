# Constellation1 Website & CRM November 2021 Release Notes

Production Release: November 23, 2021

## RELEASE SUMMARY

#### **Constellation1 CRM**

**Uploading Photos and Logos:** Improved process for uploading agent photos and logos.

**Updated Action Plans:** Brand-new content and exciting Action Plans improvements for 2022 and beyond.

#### **Constellation1 Websites**

**Emails Sent from Custom Email Domains:** Support for sending emails from branded email addresses.

**Franchise Website Leads:** Updated handling of leads generated on franchise websites.

#### **Bug Fixes**

**CRM** – Web Docs

**Website** – Agent Search Results

## Constellation1 CRM

IMPROVED UPLOADING OF AGENT PHOTOS AND LOGOS

To help you and your agents manage your company’s brand image, we’ve improved the process for and information related to uploading agent photos and logos.

The CRM now accepts photos:

* Up to 5 MB
* In JPG, PNG, and GIF formats

Recommended aspect ratios/dimensions:

* Agent photos: 3:4 (e.g., 150 x 100)
* Agent logos: 3:2 (e.g., 150 x 200)

2022 ACTION PLANS

As we get closer to ringing in a new year, we’re updating our annual and seasonal action plans.

A new-and-improved monthly newsletter series is in the works and slated for our December release. The newsletters will feature new content designed to drive more traffic to your website with updated images for a friendlier, more attractive look and feel. The new newsletter features a “year over year” schedule, meaning you don’t have to add the newsletter to your clients at the beginning of each new year. The newsletter series will automatically continue into the new year.

The seasonal postcard series is being updated to reflect 2022 dates. Postcards are also being updated with new content and images. The updated action plans will also be fully responsive.

Example:

|                                                                                                                                                                      |                                                                                                                                                                  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><img src="https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/CRM-2021-Nov-PostcardOld.jpg" alt=""><br><br><em>Previous Version</em></p> | <p><img src="https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/CRM-2021-Nov-Postcard-New.jpg" alt=""><br><br><em>New Version</em></p> |

## Constellation1 Websites

SENDING EMAILS FROM CUSTOM EMAIL DOMAINS

As announced in our September release notes, we’re pleased to confirm we’ve added the ability to send emails using your company’s custom email domain.

This new feature will determine if we are allowed to send emails from the primary email address associated with a custom agent, office, or company website domain email address.

Before an email is sent, this email service will validate our authority to send emails using the From address of the sender’s email domain:

* If we have authority, the email will be sent from the sender’s email address.
* If we do not have authority, we will attempt to send from your company’s default email address. If the company default email address is not defined in the website admin, the email will be sent from our system address.

The following email services are not supported with this new feature:

* Gmail
* Yahoo! mail
* Hotmail
* Most free or community-based email services

To allow our system to send emails on your behalf, an update is needed with your domain registrar. You need to add a text file to your domain that includes the following SPF record:

&#x20;           v=spf1 ip4:208.93.240.0/24 \~all

Your registrar (such as GoDaddy or other company with which you registered your domain) will be able to help you make this update.

Benefits of email authority include:

* Agent and company branding
* Ensuring the highest delivery success rate
* Email services recognizing the sender as an authorized and legitimate sender
* Recipient email servers validating email sender authenticity (less likely to be sent to Spam)

Example of a domain zone file:

![](https://docsstaging1.wpengine.com/wp-content/uploads/2021/11/Website-2021-Nov-ZoneFile-300x162.png)

![](https://docsstaging1.wpengine.com/wp-content/uploads/2021/11/Website-2021-Nov-SPF-TextFile-300x78.png)

A guide and FAQ are available upon request. Please reach out to your Constellation1 representative.

Franchise Website Leads

We’re improving lead routing and lead management on franchise websites. When a consumer registers on the franchise website, then subsequently searches for a property, we will now route that lead to the first broker where the property search was conducted, as if the lead had registered on that broker’s website. This means more accurate and timelier lead routing to the team with the right expertise.

## Bug fixes

#### **CRM**

**Web Documents:** Fixed an issue that was causing an error when uploading files to Web Documents.

#### **Website**

**Agent Search:** Fixed an issue with the Contact Me link on the agent search results page.
