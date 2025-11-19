# Setup for Century 21 (Canada) Franchise report

This article highlights critical information regarding account configuration for generating any report to Century 21 Canada.

* Each agent must have the correct Franchise ID setup within their profile where the last four digits of the Franchise ID field must correspond to the last four digit ID as assigned by Century 21 Canada.
* Navigate to **Agents** in the left panel menu; Franchise ID is located under **Additional Details**:

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-SetupC21FranchiseReport/SetupC21FranchiseReport1.png)

* Enter the correct Branch Office ID; note that multi-branch offices require an ID per branch office
* Navigate to Setup > **Branch Offices**

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-SetupC21FranchiseReport/SetupC21FranchiseReport2.png)

**Generating Report**

* Navigate to Reports > Franchise Reports > **Century 21 (Canada) Report**
* Select the starting and ending dates as needed
* The generated reports cannot be modified and will be saved in an Excel format to the system's default directory. The folder and the report files should not be renamed or deleted. This is extremely important as you will be unable to generate the same report again once transactions have been reported. If you want to re-generate one report, you will need to choose exactly the same date range. Please note that transactions reported in previous reports will not be re-generated again.

**Open and Collapsed Deals Report (Uses the Effective Date of the Transaction)**

A = Branch ID\
B = Start Date of Report\
C = End Date of Report\
D = Number of Open Transactions\
E = Number of Open Ends\
F = Total Sale Price of Open Transactions\
G = Total Gross Commission Amount of Open Transactions\
H = Number of Collapsed Transactions - this value is based on the following criteria regarding the transaction; i. Firm in date range specified, ii. Voided in date range specified and iii. Scheduled to close in date range specified\
I = Number of Ends for Collapsed Transactions\
J = Total Sale Price of Collapsed Transactions\
K = Total Gross Commission from Collapsed Transactions

_Please note that since this report displays in a summary format, it will only display the branch number, it will not display the new branch-project fields. Back Office uses the Process Date to retrieve data to generate report, however this is not required by Century 21._

**The Closed Transaction Report (Uses Closing Date of the Transaction)**

_Please note: the report heading displays Closing Date however transactions will populate using the Processed date_

A = Branch ID\
B = Start Date of Report\
C = End Date of Report\
D = Transaction Number\
E = Closing Date\
F = Sale Price\
G = Selling Portion of Commission\
H = Buying Portion of Commission

I =  F= Sales, T = Lease\
J, K = Selling Agent ID, Percentage of Selling End\
L, M = Selling Agent ID, Percentage of Selling End\
N, O = Selling Agent ID, Percentage of Selling End\
P, Q = Selling Agent ID, Percentage of Selling End\
R, S = Buying Agent ID, Percentage of Buying End\
T, U = Buying Agent ID, Percentage of Buying End\
V, W = Buying Agent ID, Percentage of Buying End\
X, Y = Buying Agent ID, Percentage of Buying End
