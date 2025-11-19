# REALedger 6.9 - How to close the calendar year, close the fiscal year, print unofficial 1099s, and c

This article outlines the processes for the following:

* Closing the calendar year
* Printing unofficial 1099-MISC forms
* Printing unofficial 1099-NEC forms
* Creating a magnetic media file, for submission of 1099 data to the IRS
* Closing the fiscal year

These processes should not be undertaken without a thorough understanding of the results. We recommend reviewing this article thoroughly, before executing any of the year-end processes.  If you prefer, you can click on the links below, to review a short video tutorial, demonstrating the process for closing the calendar year, and a short video demonstrating the process for creating unofficial 1099s and a magnetic media file for electronic submission to the IRS.&#x20;

Note:  The videos that are accessible from the links below, were recorded using closing Calendar Year 2022 as an example.  Also, the screenshots referenced in this article were created using Calendar Year 2022 as an example.  Be sure to adjust the dates you input, to reflect the relevant calendar and/or fiscal year, prior to closing the calendar and/or fiscal year.&#x20;

[**REALedger - How to Close the Calendar Year (constellation1.com)**](https://share.constellation1.com/watch/N1G5VF12Mj9eQUm6dhzfpW?vyetoken=ad1750fb-4b6c-4c52-bd95-410bdfed4305\&autoplay=1)

[**REALedger - How to print pre-1099 report, unofficial 1099s, and create a magnetic media file for IRS (constellation1.com)**](https://share.constellation1.com/watch/2QGeqcacVLxngeCnYsotyi?vyetoken=5ac1fd8b-8d39-437e-8657-89f38f9d3180\&autoplay=1)

REALedger has two recommended annual processes, closing the calendar year and closing the fiscal year.  The calendar year _must be_ closed before 1099 and W-2 data can be compiled for the calendar year.  Calendar year refers to the twelve-month period that runs from January 1st through December 31st.  Fiscal year refers to any twelve-month accounting period, the beginning and end of which are defined by the company.  An example would be July 1st through June 30th. &#x20;

**Note: You must log in as “master” prior to closing the calendar year, failing to do so will result in inaccurate 1099 & W-2 data for the year.  If you do not log in as “master” you will need to begin the closing process again.**

The **Close at End of Calendar Year** process will need to be performed after all payments from the accounts payable, payroll, and sales modules have been made.  The closing process _does not_ need to be completed on 12/31.  However, if you do wait to close the calendar year in January, of the following year, you will need to **Re-Create Agent Year to Dates**, **Re-Create Employee Year** **to Dates** and **Re-Create Vendor Year to Dates**, through the current date in January.  The instructions for doing this will be outlined below, after the instructions for closing the calendar year.  &#x20;

The calendar year end process compiles all agent income, employee income, and vendor payments, for the calendar year.  Prior to processing the **Close at End of Calendar Year**, proceed with the following:

* Pay all vendors, agents, and employees.
* Have all users log out of the REALedger program.&#x20;
  * To check if everyone is logged out, navigate to **System > Maintenance > System Information > Show Current Connections**.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795133)

* Enter password for **master** then click **OK**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795134)

You should only see user **master** logged in at this time.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795135)

* Click **OK** to the above pop-up.
* Log out of the program.
  * Instruct all users to stay out of the program until after the calendar year is closed.
* Create a new folder in the REALedger directory called **CYREND\_20##**.
* Make a backup of the following files:&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795136)

**Note:  If you access the REALedger program from our Constellation1 server, you can skip the backup process, as this is done for you on a daily basis.** &#x20;

Follow the instructions below to find the location of the REAL\_prg.mde file:

* Right click on the REALedger program icon.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795137)

* Select **Properties**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795138)

The location is displayed in the **Target** field.  The path to the program file is before **\real\_prg.mde**.  By default, the file will be named **real\_prg.mde**, but may have been changed to \_prg.mde.  In the example below, the program file is located in the C:\REALedger69 folder.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795139)

If you do not know the location of your **REAL\_dat.mdb, REAL\_arc.mdb** and **REAL.mdw** files, follow the instructions below:

* Launch REALedger.
* Navigate to **System > Maintenance > System Information**.&#x20;

The location of the **REAL\_dat.mdb** file is displayed in the **Current Data** field.  By default, the file will be named **Real\_dat.mdb**, but may have been changed to \_dat.mdb. In the screenshot below, the data is located in the C:\REALedger69 folder.  Note:  You will find the **REAL\_arc.mdb** and the **REAL.mdw** files in the same folder as **REAL\_dat.mdb** file, however, you will not see these files referenced in the **Current Data** field, shown below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795140)

After you have backed up the four files referenced above, follow the steps below to close the calendar year: &#x20;

* Launch REALedger and log in as the **master** user.
  * This is extremely important, if you close the calendar year while logged in as any other user, your 1099 and W2 data will not be correct, and you will need to repeat the steps listed below to close the calendar year using the **master login**.  &#x20;
* Navigate to **System > Maintenance > Re-Create Agent Year to Dates**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795141)

* Navigate to the Agents tab.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795142)

* Click **Select All** to ensure all agents with 1099 data will be included, when compiling 1099 data.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795143)

* Navigate back to the **Re-Create** tab.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795144)

* Enter **Ending Date** of 12/31/yyyy, where yyyy is the calendar year you are closing.
* Select the **Update all month to date and year to date totals** radio button.
* Click **Update Agent Totals**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795145)

If you are not closing your calendar year exactly on 12/31, then you will receive the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795146)

* Click **Yes** to the pop-up above, if you would like to continue.
* Click **Yes** to the pop-up below, if you would like to continue.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795147)

* Click **OK** on the pop-up below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795148)

* Select the **Update Pre-and Post-split deduction totals** radio button.
* Click **Update Agent Totals** button again.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795149)

If you are not closing your calendar year exactly on 12/31, then you will receive the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795146)

* Click **Yes** to the pop-up above, if you would like to continue.
* Click **Yes** to the pop-up below, if you would like to continue.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795151)

* Click **OK** on the pop-up below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795148)

* Click **Update Agent Plateau Dates** button.
  * It does not matter which radio button you have selected in the **Type of accumulated total process** section.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795153)

If you are not closing your calendar year exactly on 12/31, then you will receive the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795146)

* Click **Yes** to the pop-up above, if you would like to continue.
* Click **Yes** to the pop-up below, if you would like to continue.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795155)

* Click **OK** on the pop-up below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795156)

If you use the **Payroll** module and you wish to print **W-2s** from the program, follow the steps below:

* Navigate to **System > Maintenance > Re-Create Employee Year to Dates**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795157)

* Enter **Ending Date** of 12/31/yyyy, where yyyy is the calendar year you are closing.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795158)

* If vacation hours DO NOT carry over from year to year, check the **Update available vacation hours** radio button.
* If sick hours DO NOT carry over from year to year, check the **Update available sick hours** radio button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795159)

* Click the **Update Employee Accumulated Totals** button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795160)

* Click **Yes** on the pop-up below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795161)

* Click **OK** on the pop-up below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795148)

If you would like to print unofficial **1099-MISC** forms for your vendors, and/or combine agent 1099 earnings paid from the AP module with 1099 earnings paid from the Agents module, follow the instructions below:

* Navigate to **System > Maintenance > Re-Create Vendor Year to Dates**.  &#x20;
* Enter **Starting Date** of 01/01/yyyy, where yyyy is the calendar year you are closing.&#x20;
* Enter **Ending Date** of 12/31/yyyy, where yyyy is the calendar year you are closing.
* Leave **Calendar Date for 1099 file re-creation** field _blank_.
  * If you do not leave this field blank, you will need to restart the **Close at End of Calendar Year** process.
* Click **Update Vendor Totals** button.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795163)

* Click **Yes** to the pop-up below, if you would like to continue.
  * Click **No** if you do not want to continue at this time.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795164)

* Click **OK** to the pop-up below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795148)

Once you have recreated year to date totals for agents, employees, and vendors, follow the instructions below to complete the calendar year closing:

* Navigate to **System > Processing > Close at End of Calendar Year**.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795166)

* Enter **Calendar year end date** of 12/31/yyyy, where yyyy is the current calendar year you are closing.
* Click **Close Calendar Year** button.
* Click **Yes** to the following pop-up, if you would like to continue:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795167)

* Click **OK** to the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795168)

At this point, your 1099 and W2 data records have been created.

**Note:  If you did not close the calendar year on 12/31 and instead closed it on a day in January, after you close the calendar year, you will need to recreate year to date totals for agents, employees, and vendors again, only this time the dates used will be dates from January.  For example:  If you are closing your calendar year on January 15th, then you will need to recreate agent, employee and vendor year to dates, but setup the dates as shown in the screenshots below:** &#x20;

**Recreate Agents YTDs for 2023:**

* Navigate to **System > Maintenance > Re-Create Agent Year to Dates**.
* Follow instructions given previously, for re-creating agent year to dates, but use the current January date as the **Ending Date**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795169)

**Recreate Employee YTDs for 2023:**

* Navigate to **System > Maintenance > Re-Create Employee Year to Dates**.
* Follow instructions given previously, for re-creating employee year to dates, but use the current January date as the **Ending Date**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795170)

**Recreate Vendor YTDs for 2023:**

* Navigate to **System > Maintenance > Re-Create Vendor Year to Dates**.
* Follow instructions given previously, for re-creating vendor year to dates, but use 01/01/2023 as the **Starting Date** and the current January date as the **Ending Date**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795171)

**Modify 1099 data**

Once you have closed the calendar year, 1099 and W-2 data can be viewed and modified, if applicable.

To modify agent 1099 data, navigate to **Agents > Maintenance > 1099 Data**.

To modify vendor 1099 data, navigate to **Accounts Payable > Maintenance > 1099 Data**.

To modify employee W-2 data, navigate to **Payroll > Maintenance > W-2 Data**.

Note:  You can modify the information in the 1099 data records at will, without affecting the current agent, vendor, or employee master files. When modifying the 1099 and W-2 data, be very careful that you are on the record for the correct calendar year, as there is a record for each year an agent, vendor or employee has been associated with your company, and the year that appears first, in the **1099 Data**, is not the current year, it is the first year, that you started using the program.  &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795172)

**1099s**

When you are ready to review the accuracy of compiled 1099 data, navigate to **Agents>>Reports>>Agent Earnings and Income>>1099s**.

* Navigate to the **Offices** tab to ensure all offices are selected.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795173)

* Navigate back to the **General** tab.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795174)

* In the **Enter Year End Date** field, enter 12/31/yyyy, where yyyy is the current 1099 calendar year.&#x20;
* Check the **Combine Agent and Vendor 1099s for Same Tax ID** box, to combine 1099 data for agents and vendors with the same tax ID number.&#x20;
* Select **Agents and Vendors** from the **Type of Recipient to Include** dropdown.
* Select **All** from the **Type of Data to Include** dropdown.
* Select the **Print Pre-1099 Report** button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795175)

1099-MISC data will print first, followed by 1099-NEC data.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795176)

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795177)

* Review the report to verify all totals are correct, prior to printing _unofficial_ 1099-MISC forms to plain paper for your vendors, and prior to printing _unofficial_ 1099-NEC forms to plain paper for your agents.
  *
    * If editing of any 1099 data is needed, be certain to print the Pre-1099 report again to verify totals are then correct.&#x20;

After reviewing the report and confirming that values are correct, follow the instructions below to print unofficial 1099-MISC forms and unofficial 1099-NEC forms to plain paper:

* Leave the **Beginning Count** and **Ending Count** boxes blank.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795178)

* Select **MISC** from the **Form** dropdown.
* Select **Plain paper 1 per page or Plain Paper 2 per page** from the **Format** dropdown.
* Click **Print 1099’s** button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795179)

A preview of the 1099-MISC data will come to the screen.

* Print to plain paper.

Note:  If you selected format **Plain paper 2 per page**, the data for two different agents will print on each page.&#x20;

To print 1099-NEC data to plain paper:

* Select **NEC** from the **Form** dropdown.
* Leave the **Beginning Count** and **Ending Count** boxes blank.
* Select either the **Plain paper 1** **per page** or **Plain paper 2 per page**, from the **Format** dropdown.
* Click **Print 1099’s** button.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795180)

A preview of the 1099-NEC data will come to the screen.&#x20;

* Print to plain paper.

Note:  If you selected format **Plain paper 2 per page**, the data for two different agents will print on each page.&#x20;

**Electronic Filing**

**Since, you will not be able to print official 1099-NEC forms for your agents, or official 1099-MISC forms for your vendors, you will be required to submit both agent & vendor 1099 data electronically to the IRS.**

**Note: You will need to setup a FIRE account with the IRS before you will be able to submit 1099 data electronically.  Do this as soon as possible, so that you will have time to submit a test file to the IRS prior to final submission.**

When you are ready to generate your electronic test file:

* Navigate to **Agents>>Reports>>Agent Earnings and Income>>1099s**.
* Click on **Print Pre-1099 Report**.
  * The report will print to screen.
  * Close report.
* Click on **Is this a Test file only?**
* Click on the **Generate Magnetic Media** button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795181)

* Click **Yes** to the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795182)

* Make note of the path to the file.
* Click **OK**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795183)

* Follow instructions provided by the IRS to submit the electronic file test file.

When the IRS has notified you that the test file was received and processed successfully, you can create your **Original** file.&#x20;

When you are ready to generate your **Original** electronic file:

* Navigate to **Agents>>Reports>>Agent Earnings and Income>>1099s**.
* Click on **Print Pre-1099 Report**.
  * The report will print to screen.
  * Close report.
* Select **Original** from the **Original, Replacement, or Correction File?** dropdown.&#x20;
* Click on the **Generate Magnetic Media** button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795184)

* Click **Yes** to the following pop-up:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795182)

* Make note of the path to the file.
* Click **OK**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795186)

* Follow instructions provided by the IRS to submit your **Original** file.

**Payroll**

If you use the payroll module and will be printing W-2s from the program, navigate to **Payroll > Reports > Other > W-2s**.&#x20;

* Enter 12/31/yyyy, into the **Enter Yearend Date field**, where yyyy is the current W-2 calendar year.&#x20;
* Click **Print Pre-W2 Report**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795187)

* Review the **Pre-W2 Report** for accuracy.
* Click **Close**.

Once you have confirmed that all values are correct:

* Click **Print W2’s button** and W-2s will print to screen.
* Insert official W-2 forms into your printer prior to selecting the printer icon.
* Click **Return**.

**Close at End of Fiscal Year**

The fiscal year should only be closed after posting through the end of the fiscal year.  Closing the fiscal year, zero’s out Income Statement accounts, creates the balance forward records for the Balance Sheet accounts, then rolls up the YTD profit/loss to retained earnings. &#x20;

Note: You _can_ enter journal entries after closing your fiscal year. If you do enter journal entries after you have closed the fiscal year, you will need to post the general ledger again, then re-summarize the GL for the fiscal year.&#x20;

Prior to running the **Close at End of Fiscal Year** utility, you should:

* Post the General Ledger through your Fiscal Year End date.
  * Fiscal year refers to any twelve-month accounting period, the beginning and end of which are defined by the company.  So, your fiscal year could end on 12/31/yyyy or it could be something else.  An example would be July 1st through June 30th. &#x20;
* Create a new folder in the REALedger directory called **FYREND\_2022**
* Log out of the program.
  * Instruct all users to stay out of the program until after the Fiscal year is closed.
* Make a backup of the following files:&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795136)

Follow the instructions below to find the location of the REAL\_prg.mde file:

* Right click on the REALedger program icon.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795137)

* Select **Properties**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795138)

The location is displayed in the **Target** field.  The path to the program file is before **\real\_prg.mde**.  By default, the file will be named **real\_prg.mde**, but may have been changed to \_prg.mde.  In the example below, the program file is located in the C:\REALedger69 folder.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795139)

If you do not know the location of your **REAL\_dat.mdb, REAL\_arc.mdb** and **REAL.mdw** files, follow the instructions below:

* Launch REALedger.
* Navigate to **System > Maintenance > System** Information.&#x20;

The location of the **REAL\_dat.mdb** file is displayed in the **Current Data** field.  By default, the file will be named **Real\_dat.mdb**, but may have been changed to \_dat.mdb. In the screenshot below, the data is located in the C:\REALedger69 folder.  Note:  You will find the **REAL\_arc.mdb** and the **REAL.mdw** files in the same folder as **REAL\_dat.mdb** file, however, you will not see these files referenced in the **Current Data** field, shown below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795140)

After you have backed up the four files referenced above, follow the steps below to close the fiscal year: &#x20;

* Relaunch REALedger and navigate to **System>>Processing>>Close at End of Fiscal Year**.
* Enter the **Fiscal year end date**.
* Select **Close Fiscal Year** button.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795193)

* Click **Yes** to the pop-up shown below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795194)

* Click **OK** to the pop-up shown below:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/17795195)

* Notify users that they can log back into the program.

Note:  If you enter journal entries after closing the Fiscal year, you will need to post the general ledger again and **Re-Summarize G/L for Financial Statements**.

I you would like assistance closing the calendar year and/or fiscal year, contact [account@constellation1.com](mailto:account@constellation1.com) to obtain a quote for this billable service.  &#x20;

_Note:  Closing the calendar year and fiscal year is no longer required in version 2 of REALedger, which makes the year-end process much more simplified.  If you are interested in upgrading to version 2 of REALedger, reach out to_ [_sales@constellation1.com_](mailto:sales@constellation1.com) _to obtain a quote for upgrading to version 2 of REALedger, which is now referred to as Constellation1 Accounting._
