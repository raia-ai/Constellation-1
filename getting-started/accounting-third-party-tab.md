
# Accounting - Third-Party Tab | Constellation1 Customer Hub

The purpose of this article is to explain the purpose of the **Third-Party** tab of a sale transaction and how to fill out the third-party record.

The **Third-party** tab serves three purposes. 

1.  Payments made to a third-party, paid out of the proceeds of the sale transaction
2.  Money that will not be paid out to a third-party, but instead will be held by your company
3.  Money received that is more than or less than the gross revenue, referred to as pass-through

By default, non-pass-through third-party records will not be recognized as revenue for the sale and will be deducted from the gross commission when determining the amount to be distributed among the agents. If you would like the third-party payments to be included in the total gross revenue amount, posted to the general ledger, you will need to enable system setting **TPGCPOST** by navigating to **System**\>>**Setup**\>>**System Settings**.

*   Highlight system setting **TPGCPOST**
*   Click **Edit**
*   Check the **Enabled?** box
*   Click **Save**

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/ff1c96af-2323-4353-a813-8f3ace77ae16.png) 

To demonstrate the effect the **TPGCPOST** system setting has on the GL, the following third-party referral was entered:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/61be0f8d-cb26-4f5a-ad87-417ef169c8e4.png) 

With system setting **TPGCPOST** disabled, a sale with gross revenue of $5000 and a third-party referral for $1250 will affect the GL as follows:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/4ebefff3-930e-450a-8716-4e4bc70aa746.png) 

With system setting **TPGCPOST** enabled, a sale with gross revenue of $5000 and a third-party referral for $1250 will affect the GL as follows:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/a25b0352-a48d-463e-852a-b4ffa4149f6c.png) 

Note:  Changing system setting **TPGCPOST**, from enabled to disabled or from disabled to enabled, will not affect the GL activity for posted data.  In addition, if you have unposted closed sales, you will need to click **Edit** and then **Save** on each record for the change to be recognized in the GL.

To add a third-party record, to a sale transaction, click on the **Third-party** tab and click the green plus sign.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/39f23bb4-66cb-4472-b946-4b9aea0ce367.png) 

The following record will open:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/4e55e7e9-5e33-48ef-9c31-59095b2a7546.png) 

At a minimum, all fields outlined in ‘red’ will need to be filled before you will be able to save the sale transaction.

To fill out the third-party record:

*   Check the **Pass-through?** box, if applicable.
    *   For information pertaining to pass-through functionality, refer to the [Third-Party Pass-Through](https://constellation1.na3.teamsupport.com/knowledgeBase/14506632 "Third-Party Pass-Through Money") article. 
*   Select the **Payee** by clicking on the “**…**” box

If the recipient of the payment is already setup as a vendor, select the vendor from the left pane of the **Select Vendor** pop-up and click **OK**.

If the recipient of the payment does not exist, you can click **Add** to create a new vendor record.

Once the appropriate vendor has been selected or added, click **Save** then **OK,** to return to the third-party record.  You will then see the vendor in the **Payee** field:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/fd08accf-8bd4-44d6-922d-7bf1e03d7327.png)

*   Select the appropriate GL code from the **Account** dropdown
*   Select the appropriate **Office** from the dropdown
*   Select the appropriate **Project** from the dropdown, if applicable
*   Select **Referral Network** from the dropdown, if applicable
    *   Note: This is only applicable for some franchises

The **Amount** of the referral can be recorded in one of three ways:

1\. You can enter a **% of Sale Price**:

 **![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/2c7bfb05-4bfe-4581-8153-75599e2555b3.png)**

2. You can enter a **% of Gross Revenue**:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/c5558ab4-f2f2-4be8-b7fb-2effce2f9c17.png) 

Enter **Less Adjustment** amount, if applicable. This field is used to add or subtract from the payment amount when the **% of** option is used. For example; if gross revenue, on the sale, is $5000 and the referral is based on 10% of the gross revenue, less a $125 adjustment, select **% of Gross Revenue**, enter 10% in the **Percent** field, $125 in the **Less** **Adjustment** field, and the **Amount** will calculate 10% of $5000 to be $500 and subtract the $125 adjustment, leaving an **Amount** of $375.  Adjustments can reduce the amount of the third-party payment by entering a positive adjustment amount, or increase the amount of the payment by entering a negative adjustment amount.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/a24c3558-8d28-427d-bb8a-2ee4e2568012.png)

3. You can enter a flat **Amount** manually:

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/8dcbd07a-efde-40ca-8cd7-4665734fdbe1.png) 

By default, the **Pay by AP?** box will be checked. With this box checked, an AP bill will be created for you, upon closing the sale transaction.  If you de-select this option, you will have to manually create the AP bill, if applicable.

*   Select the appropriate **Class** from the dropdown list.
*   Select the appropriate **Check Resp** from the dropdown.  

The **Side That Paid** field is only applicable for select franchises. However, you may choose to use it for information purposes only.

The **Exclude from Franchise Fees?** field is only applicable for select franchises. However, you may choose to use it for information purposes only.

**Tip:**  Add defaults to the vendor’s setup record to prevent having to enter the **Office**, **Account**, **Project** and **Class**.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/4e22c91e-91a8-4088-8e54-8742fe668321.png)