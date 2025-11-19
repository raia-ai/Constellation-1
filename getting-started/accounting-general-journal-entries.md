---
title: Accounting - General Journal Entries
---

# Accounting - General Journal Entries

The purpose of this article is to show how to add, edit, copy, delete, and reverse an unposted general journal entry and how to copy or reverse a posted general journal entry. 

Entering journal entries is the most common task in the **General Ledger** module.  To add a journal entry, navigate to **GL>>Processing>>General Journal Entries**. 

*   Click **Add**
*   Enter a unique alphanumeric **Journal Entry Number**, up to sixteen characters
    *   Consult with your CPA for a recommended naming convention for journal entry numbers
*   Enter a **Description** for the journal entry
*   Enter **Date**, for which the entry is to be recognized for financial statement reporting, also referred to as posting date
    *   **Date** will default to **Processing Date** but can be edited
*   Enter **Amount** equal to the total of one side of the journal entry 
    *   For example, if making an entry that debits cash for $10.00, credits revenue for $6.00 and credits wage expense for $4.00, enter $10.00 in the **Amount** field
*   Click the green plus sign to add **Journal Entry Lines**
    *   *   Enter one debit or one credit on each line
        *   Select GL code from the **Account** dropdown
        *   Select **Office** from the dropdown
        *   Select **Project** from the dropdown, if applicable

*   Add additional **Journal Entry Lines** as needed
    *   Add as many journal entry lines as needed, however, the line items must balance between debits and credits, and they must balance to the **Amount** in the header
*   **Save**

Note: The **Save** button will not enable if you have an incomplete journal entry line.  If the extra line is not needed, then click the box to the left of the line.  When you click on the box, a red "x" will appear.  Select the red "x" to delete the line. 

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/17d7b1c9-3c19-4c18-8fed-2264e8d5187e.png)

Once the incomplete line is deleted, the **Save** button is activated.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/d79700d0-f6af-45de-b446-349750192fdd.png)

Note:  It is not necessary for a journal entry to be in balance prior to saving, however, all required fields must be filled before the **Save** button will enable.  If you save a journal entry, that is out of balance, eventually you will need to edit the journal entry to make it balance.  If you do not balance the journal entry, your Trial Balance and Balance Sheet will be out of balance.  A journal entry is only in balance if the **Amount**, **Debit Total**, **Credit Total** are the same, and the **Remaining** amount is $0.00. 

You can toggle between **Unposted**, **Posted**, and **All** view by clicking the radio buttons. 

From the **Unposted** view, you can **Add**, **Edit**, **Copy, Delete** or **Reverse** journal entries.  

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/eb9ecd4d-0e7b-461a-b7dc-196804f32b44.png)

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/3686ebfc-372b-4919-aa49-e60a2b336242.png)

You may not **Delete** an **Unposted** journal entry if it contains a cash account GL code that has been reconciled.  Note in the screenshot below, **Line** 1 has been reconciled and the **Delete** button is disabled:  

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/a11c4095-1d39-4ea5-abe5-ffdf4f223d6e.png)

From the **Posted** view you may only **Copy** or **Reverse** a journal entry. 

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/c1f26e81-413b-47a3-8d33-117030cc6561.png)

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/3f7f82ae-aa27-4369-8839-b2440c1e9a06.png)

Select **All** to display journal entries in the **Unposted** and **Posted** view.  From the **All** view you can **Copy** or **Reverse** a posted journal entry, or you can **Edit**, **Copy** or **Reverse** an unposted journal entry.  You can not **Add** a new journal entry from the **All** view; this can only be done from the **Unposted** view. 

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/32dbf210-c673-4859-8318-dffcc9f9b7e7.png)

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/249972fc-8e34-4c72-ad6f-acfbdfedd784.png)

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/ba5c8e3c-6238-417c-983a-de655f1aae91.png)

Note:  If you create journal entries, that are the same month after month, you may want to setup a recurring journal entries template.  To setup a recurring journal entry, navigate to **GL>>Setup>>Recurring Journal Entry Templates**.