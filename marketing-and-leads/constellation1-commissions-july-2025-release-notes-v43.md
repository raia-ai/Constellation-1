# Constellation1 Commissions July 2025 Release Notes v4.3

Production Release: July 16, 2025, v4.3

## Release Summary

## **Transaction Number via Import:** Field length reduced to 10 characters

## **Transaction:** “Commission Disbursed by Third Party” flag is now controlled by the advanced setting flag “Remember last used Disbursed By and Disbursement Form”

## **T4A E-File Process Transmitter Name:**  Added validation when transmitter name length exceeds 35 characters

## **Auto Filter Agents by Selected Office:** Automatically filters agents when the office is selected

## **Ability to Apply Minimum/Maximum Cap for Post-Split Deduction:** Applying excess deduction to agent is now ignored when the deduction cap is configured

## **Commercial Commission Rules:** Added ability to create a commercial commission rule

## **Enabled Custom Fields for Transaction:** Users can now add custom fields

## **Reports:** Agent Income Summary provides new filter include/exclude pre-split deductions

## **Agent Check Stub:** Withholding type deductions are now separated from post-split deductions&#x20;

## **Enterprise Insights:** Added ability to assign permissions "By Groups"

## **General Ledger:** Bonus Override and Referrals payments can be configured to integrate to Accounts Payable&#x20;

## **Bug Fixes**

## Release Detail

## **Transaction Number Length Reduced to 10**

The length of the transaction number that is auto-generated during transaction import has been reduced to 10 characters&#x20;

## **Transaction**

## The “Commission Disbursed by Third Party” toggle is now controlled by the advanced setting flag “Remember last used Disbursed By and Disbursement Form”

## **T4A E-File Process Transmitter Name**

Commissions Online now validates transmitter name maximum length will not exceed 35 characters, this will prevent errors when submitting the file to Canada Revenue Agency

**Auto Filter Agents by Selected Office**

Commissions Online now automatically filters out the agent list when an office is selected

**Ability to Apply Minimum/Maximum Cap for Post Split Deduction**

Enabled the ability to configure a minimum and maximum threshold for a Post Split deduction at the agent level. **“Apply Excess Deduction Value to”** setting will be ignored by system when deduction cap is applied for a Post Split deduction.

**Commercial Commission Rule**

Added ability to support a **“Commercial”** type commission calculation

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f9f1d88f-f261-4438-87a3-c8f416747438)

Added **“Square Footage”** in Transaction / Details tab / Additional Details card

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/62a95a5b-9c5c-4c36-8633-db0f9cbdf323)

**Enabled Custom Fields for Transaction**

Users can now add/define custom fields for transaction in Advanced Settings

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/d1a7e2c9-c32c-4b3a-8bbe-ae0c3e4d0b58)

Custom fields are displayed via Transaction / Details tab / Custom Fields card and can be selected when creating Custom Reports&#x20;

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/28577a08-eef4-4a6c-86d8-622e76cae6e8)

**Reports**

In **“Agent Income Summary Report”**, user can now choose to include **“Total Deduction Amount – Include Pre-Split”** which represents the sum of all deductions or **“Total Deduction Amount – Exclude Pre-Split”** which represents the sum of Post Split deductions only.

![A screenshot of a login formAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/3fe99b33-bf5b-4bca-a3f7-1f06093501d9)

**“Agent Deduction Total – Post Split”** field has also been added to Custom Reports

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/39111e9c-01d4-4606-9cc9-a8915111a4f2)

**Agent Check Stub**

Garnishment type deductions are now separated from **“Post-Split Deductions'',** and shown right above **“Check Total”**

![A screenshot of a documentAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0f4c3676-7bbc-4d69-b48f-eba15c45e76f)

**Enterprise Insights**

A permission can now be assigned "**By Groups”** when creating/editing a user.

![A screenshot of a computerAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/85249877-bcc7-4053-bfeb-fd931ff7d8a7)

**General Ledger**

**“Bonus Override”** and **“Referral”** payments can now be posted as a “Bill” when integrating with accounting system.

![A screenshot of a computer screenAI-generated content may be incorrect.](https://constellation1.na3.teamsupport.com/api/attachments/action/1/fc814c11-f23b-4c62-9479-14810534e602)

**Bug Fixes**

1\. Tax rounding resulted in negative amount caused Transaction Commission page to freeze.

System now rounds negative tax amount to agent or broker’s portion depending on where the negative tax happened. This prevents any negative tax amount to be calculated.

2\. Added Report Generate Date to all Reports in Enterprise, Team Lead, and Agent View

All reports generated from Enterprise, Team Lead, and Agent View were missing the Date/Time stamp. This has been fixed.

3\. Users can now edit the Commission Rule name without receiving an error.
