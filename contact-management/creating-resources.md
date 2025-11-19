
# Creating Resources | Constellation1 Customer Hub

Resources are the data tables of all the types of contacts entered in transactions. This article will outline how to add resources to your database, and a brief description of the fields.

*   To add a new Resource, select Resources from the Set up menu
*   Select a related category then select New and complete the required fields
*   When creating or modifying transactions, check the applicable resource list first (Buyer, Seller, etc.) to see if that contact already exists in the database.  If it does, you can add it to the transaction by double clicking on the highlighted name.  If that particular resource does not exist, you will need to add it as instructed above.
*   Below is a brief description of the fields:

**The Fields of the Resource Set Up Menu** **-** This value will auto-generate when a new resource is created.  The values can be translated as follows so that if you need to cross reference the name in Commander Back Office to the Other Names list in QuickBooks®, it will be more identifiable.

**Payee** – This field is used by the system if any checks/cheques are to be issued for the particular resource.  This field indicates if the system should make the checks/cheque payable to the resource ‘N: Name' or ‘C: Company'.  You can use the drop down menu to select the appropriate option.  If Payee = Name, then the First Name & Last Name are mandatory fields, if Payee = C, then the Company Name is the mandatory field.

**Address -** Enter the street number and name

**Unit No -** Enter the suite number, if applicable

**SIN/SSN** – Enter the Social Insurance Number or Social Security Number, if applicable, for the resource.  Please note that if there is no value entered in this field when generating an interest check/cheque for the Buyer, you will be prompted when closing if you still wish to issue the interest check/cheque or not.

 **Tax** – Enter the tax number, if applicable, for the resource.  For example, if the resource is a Brokerage in Canada, you would enter their HST number in this field.  If HST is applicable for the particular resource, you must enter the HST number for that resource.  If no HST number is entered, the system will not calculate HST on transactions for that resource.  (Tax amounts can be manually overridden on any particular transaction).

**Payee** – This field is used by the system if any checks/cheques are to be issued for the particular resource.  This field indicates if the system should make the checks/cheque payable to the resource ‘N: Name' or ‘C: Company'.  You can use the drop down menu to select the appropriate option.  If Payee = Name, then the First Name & Last Name are mandatory fields, if Payee = C, then the Company Name is the mandatory field.

**Reset Accounting ID -** This button should only be clicked if you receive a conflicting ID error when integrating to QuickBooks®.  The error indicates that there is a problem with the ID assigned to any resource used in the transaction and appropriate entries to QuickBooks® will NOT post as expected.  The easiest way to fix this problem is to reverse the transaction and re-close it once you have Reset Accounting ID for the specified resource.

**Integrate as Vendor for 1099**  is only available for Brokers and Seller/Buyers resources.  By initiating this functionality, through the closing process, it will post applicable resources to the Vendors list in QuickBooks® rather that its existing Other Names list.

**Editing Resources**

To edit the information stored for a resource you need to access the Resource File.  This can be done two different ways.

First, you can get to the Resource file through Set up Menu.  Follow the steps below:

1.  Select option Resources from the Set Up  menu.  A second drop-down menu will appear listing the different resource types
2.  Select the resource type
3.  Select the Lookup field and start to type the last name or company name of the contact to edit
4.  When the resource is highlighted, select the Edit icon
5.  Select Save

**Deleting Resources**

To delete a resource in the database, please follow the steps noted below, please note that if this particular resource has already been attached to a closed or voided transaction, it cannot be deleted

1.  Select option Resources from the File Maintenance drop-down menu.  A second drop-down menu will appear listing the different resource types
2.  Select the type of resource (External Agent, Broker, Buyer/Seller, Attorney, Advance Company or Miscellaneous) you wish to delete
3.  Begin typing the last name or company name of the contact to delete and once highlighted, select Delete
4.  Select OK