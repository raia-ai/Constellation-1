# Accounting - How to Account for Employee Bonus

The purpose of this article is to provide options on how to pay an employee bonus.  You should consult with your accountant for guidance on the tax effects of paying bonuses to employees.&#x20;

If you would like to track bonus expenses separately from regular wages, you may want to enter a unique GL code for bonuses.&#x20;

To setup a new GL code, go to **GL** > **Setup** > **Chart of Accounts**.

* Click **Add**.
* Select **Account Subtype** from the dropdown.
* Select **Account Lookup Category** from the dropdown.
* Enter a unique five digit **GL Code** and **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8dbf0561-907d-4e24-af64-33f13080240d)

If you decide to track bonus expenses with a unique GL code, setup a new earnings code, by going to **Payroll** > **Setup** > **Employee Earning Codes**.

* Click **Add**.
* Enter a unique **Code** up to eight characters long.&#x20;
* Enter **Description**.
* Leave **Type** as **Others**.
* Select GL **Account** from the dropdown.
* Click **Salaried** radio button and **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/54ca49b5-5a94-4d64-b0a0-3afebeadd824)

Add the new earnings code to each employee's setup record.

* Go to **Payroll** > **Setup** > **Employees**.&#x20;
* Find the employee **Name** and click **Edit**.
* Select the **Earnings** tab.
* Click the green plus sign to add an additional **Earning** code.&#x20;
* Select the new code from the dropdown and **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8b267b21-bc7a-476d-93e9-b348658dfb32)

There are two ways to pay the bonus.

1. Include the bonus earnings in the same check as the employee’s regular wages.
2. Create a separate check for bonus earnings only.

If you plan to include the bonus earnings in the same check as the employee’s regular wages, go to **Payroll** > **Processing** > **Generate Payroll**.

* Select **Pay Frequency** from the dropdown.
* Select **Payroll Class** from the dropdown.
* Enter **Period End** date and click **Process**.
* Go to **Payroll** > **Processing** > **Payroll**.
* Highlight the **Employee Name** and click **Edit**.
* Enter full amount of bonus in the **Rate**
  * Do not enter hours, the bonus was setup as **Salaried** and does not require hours to calculate the bonus.
* If employee is paid hourly, enter hours worked on separate earnings line item and **Save**.   &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/efd02253-350f-4cbc-b6bd-524cbda440a6)

Go to **Payroll** > **Processing** > **Issue Payroll Payments** and process payroll checks with bonus pay included.&#x20;

If you decide to pay the employee bonus in a separate check, go to **Payroll >** **Processing > Generate Payroll**.&#x20;

* Select **Pay Frequency** from the dropdown.
* Select **Payroll Class** from the dropdown.
* Enter **Period End** date and click **Process**.
* Go to **Payroll** > **Processing** > **Payroll**.
* Highlight the **Employee Name** and click **Edit**.
* Enter full amount of bonus in the **Rate**
  * Do not enter hours, the bonus was setup as **Salaried** and does not require hours to calculate the bonus.
* Enter 0.00 for **Hours** and **Rate** for earning code used for regular wages and **Save**.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c9f63bb5-3bd0-4e2d-b9cd-9fafbacfcf6f)

Go to **Payroll** > **Processing** > **Issue Payroll Payments** and process bonus payroll checks.

Was this article helpful to you?

Was this article helpful to you?
