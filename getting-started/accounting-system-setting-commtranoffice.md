# Accounting – System Setting COMMTRANOFFICE

The purpose of this article is to provide information regarding system setting **COMMTRANOFFICE**.

System setting **COMMTRANOFFICE**, when enabled, is used to update the agent’s office, on their commission record, to the same office as designated in the sale transaction, regardless of the agent’s default office. This becomes important if you want the GL activity for pre-splits, post-splits, revenue, and cost of sales to be accounted for with the office designated in the sale transaction, and not necessarily the agent’s default office.&#x20;

The **COMMTRANOFFICE** system setting is disabled by default.  If you would like to enable this setting, go to **System** > **Setup** > **System Settings**.

* Filter for setting **COMMTRANOFFICE**
* Click **Edit**
* Check the **Enabled?** box and **Save**

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ab3414ad-0d4d-45c1-af5c-4da41691d4d1)

Here’s how it works:

Agent’s default office is H:Hudson:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/35d347da-7380-4506-b403-256739d168fa)

Office selected in the sale transaction is T: Tigard:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/fefdedf0-fa39-4416-831a-76ac62b110c3)

With system setting **COMMTRANOFFICE** enabled, the agent’s office in the sale will default to T: Tigard, and not H: Hudson, the agent’s default office.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5fd7af91-0a7d-4952-abc3-b63225dcd6bd)

When **COMMTRANOFFICE** is enabled and the transaction office is changed in a sale transaction, if there are any agent commission offices that differ from the transaction office, you will receive the following pop-up:&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/daf6d7e5-5023-4294-8fbe-1d0ad6c1f7c9)

Click **Yes**, if you would like all agent commission records to update to the transaction office.

Note: Regardless of the value of **COMMTRANOFFICE**, users are free to change the office in the agent’s commission record as long as the transaction is not posted.
