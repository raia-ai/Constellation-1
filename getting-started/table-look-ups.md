
# Table Look Ups | Constellation1 Customer Hub

The Table Lookup feature can be used to add additional information to certain fields.  For example, conditions on transactions can be set up to include more detail, such as the type of condition. Please note that the system will only validate a particular field if at least one entry has been defined per field.

The following is a list of some of the Table Look Up’s and a description of how they are used:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/9bef7e76-5734-42e1-950f-fb1f0cdd8f39.png)

**Demographics**

The information configured here will help track and print reports based on the demographic data of buyers and sellers. For example, Age Bracket will create a report illustrating the age breakdown; Experience will track the first time home buyers and Business source will show lead sources such as referrals, advertising or other.

**Managers**

**Tier -** allows users to define various levels of Manager Overrides allowing a team of managers to be configured and applicable manager team reporting.  These labels will appear on the D1 format of the Transaction Record Sheet.

**Assistant**\- Allows users to define the assistant and provide Assistant Commission Statement, which can either be printed during the closing process or also can be found on a closed transaction under the Documents Ta

**Notes**

**Action Notes**: These can be used to record and track any specific notes regarding the transaction when you print your Start of Day reports.  For example, a reminder that this Agent has a garnishment from the government or that they have an advance processed. Action Notes can be attached to Agents, Resources and Transactions.

**Referrals-** Allows the user to set up various referral sources for tracking.

**Trade Codes**

**Transaction Type**: Examples of a transaction type are referrals, appraisals, leases, commercial leases, relocations, new home, sales and commercial calculation.  The program comes with these values and ONLY the descriptions can be modified if required.

**Trade User Codes 1 – 5**: These are used for validating the five User Defined Fields on the Custom Tab of the transaction, and User Defined node. Trade User Codes can be used to track other reportable values that may be necessary in your business. You may set up descriptions for these fields in the Change Company Profile function, but it is through Table Look Ups that you can define the values for these fields.

**Conditions**:

*    Conditions must be created here first - they cannot be added "on the fly" like many of our other data entry fields.  The Condition field on the Transaction file is used to record and track the type of condition. The system only allows you to use 1 character alphanumeric code in the Value field, for example, ‘F’ for conditional on financing, ‘I’ for conditional on inspection, 'S' for conditional sale of buyer's property, etc.  The description field can be used to enter the full name of the condition, "Inspection", "Sale of Buyer's Property". This field can then be used to run reports for all transactions with a particular condition.  Please note that when you set up a new company, the system automatically sets up conditions ‘N: Not Firm’ (if the transaction is conditional) and ‘Y: Firm' (if the transaction is firm). The FIRM option MUST not be changed.
*   Values with more than a single character will result in the follow error: "Value is to big for property 'condition ID", therefore user must enter a single character only.
*   For new entries to appear in the drop down menu on the transaction screen, relaunch the application. Any previously entered Condition Values exceeding one character will not show on the Condition Value drop down menu. Any changes attempted to be made to this Condition value (other than reducing it to a single character) will not save.