# Paradym by Constellation1 June 2022 Release Notes

Production Release #80: June 21, 2022

## RELEASE SUMMARY

**Twilio Chat:** Updated API.&#x20;

**Bug Fixes**

## RELEASE DETAILS&#x20;

Twilio Chat

We’ve updated and improved the Twilio Chat API to allow access to updated chat and conversation features in a secure and stable environment.&#x20;

Bug Fixes&#x20;

* We fixed an issue with Visual Tours not being created. Previously, when a listing was imported from an MLS board and the listing date was missing, a Visual Tour was not being created. Now, when listings are imported and the listing date is missing, a Visual Tour will still be created.
* We fixed an issue with the Content Manager. Previously, when editing a blog post in the Content Manager, the link and meta fields would disappear. Now, when editing a blog post, the link and meta fields will continue to display on the edit page, as expected.&#x20;
* We fixed an issue with Auto Tours changing their status to Unknown and the property price being set to $0. Previously, the status for some Auto Tours would change from Active to Unknown and the price would be set to $0.\
  Now, we’ve added additional validation to Auto Tours to monitor and prevent unwanted changes from happening.&#x20;
* We fixed an issue with Auto Tours not being created for new listings from Realogy. Previously, we were not able to pull listing photos from Realogy using the URL they provided for new listings. Now, after working with Realogy, we’re able to access listing photos for new listings on the Realogy system.

Was this article helpful to you?

Was this article helpful to you?
