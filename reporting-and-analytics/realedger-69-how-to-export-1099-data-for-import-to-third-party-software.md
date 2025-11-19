---
title: REALedger 6.9 - How to export 1099 data for import to third-party software
---

# REALedger 6.9 - How to export 1099 data for import to third-party software

The purpose of this article is to provide instructions for exporting 1099 data for import to third-party software.  

When ready, close the calendar year by navigating to System>>Processing>>Close at End of Calendar Year.  This is typically done in early January after all commission payments from the previous year have been made.  This process creates 1099 records.

Make any necessary manual edits to 1099 records by navigating to Agents>>Maintenance>>1099 Data and AP>>Maintenance>>1099 Data.

Generate Pre-1099 report by navigating to Agents>>Reports>>Agent Earnings and Income>>1099s.  Enter the last day of the tax year and click the Print Pre-1099 Report button.  This populates a table that is used in the 1099 processing that will be exported in the next step.

Navigate to System>>Maintenance>>Data Export Utility and browse to the folder where you want to export the 1099 data and enter a filename in the Select table to Export dropdown, select tblAG\_Pre1099, select Output Type, then click Export Data.

The exported file can be viewed in Excel. The information in each column is mostly obvious from the column name. There is a column named TaxFormType that identifies whether the record is for 1099-MISC or 1099-NEC.  The column named Box1Rents holds the value for Box1 for either 1099-MISC or 1099-NEC.  The “Rents” in the column name predates the 1099-NEC form but this column contains the values for 1099-NEC Box 1, Nonemployee Compensation.

Was this article helpful to you?

Was this article helpful to you?