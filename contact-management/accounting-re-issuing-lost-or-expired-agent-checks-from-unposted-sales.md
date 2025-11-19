# Accounting - Re-issuing Lost or Expired Agent Checks from Unposted Sales

The purpose of this article is to explain the process for reissuing an agent check.&#x20;

There may come a time when an agent contacts you, to let you know they have lost their check, or they have held onto it for so long that the bank will no longer honor the check.  It is important, when issuing the new check, that you use the current date to void and reissue the check.  This will prevent you from altering financial data from a prior period.

In the following scenario, the agent lost check number 51, dated 7/1/2021:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/6dd161ce-6d73-4b19-a2de-0709def9b9e3)

To void a commission check, go to **Sales** > **Processing** > **Void Commission Payments**, then click the **Void** button once you have selected the check that you want to void:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/5ad46953-2fef-46a6-aff3-72799f301514)

Once this is done, close the **Void Commission Payments** tab.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/3531808c-3faa-42e7-91bf-66f2be963056)

To reissue the check, open the original sales transaction that the check was issued from. You will now find two agent commission records. The first record is the original check record and the second is the voided check record.

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/dd595f7d-9508-44ad-8900-3404bdc2ac13)

Click the green plus sign to add another agent record to the sale:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8e94d636-0ddc-4044-a28b-a47caebe33f5)

Make certain that all values are exactly as they were in the original check record, resulting in the same **Agent Payment** value, as the original check.

Uncheck the **Recalc at closing** box to ensure the record does not revert to default values, when stepping through the **Issue Commission Payments** process.&#x20;

Uncheck the **Pay by ACH?** box, if you plan to reissue a paper check to the agent, otherwise leave the Pay by ACH? box checked if you would like to include the payment in your next NACHA batch, if applicable.&#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/bfdd4475-2a85-4a9c-8f34-cc06b0bc5a8f)

**Save** the record and step through the **Issue Commission Payments** process to reissue a check to the agent. &#x20;

What happens in the GL:

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/93dbea87-fa3c-44e9-bc76-8bc4467dfaa0)

Note:  If the sale was posted, reference the [**Voiding an Agent Check on a Posted Sale**](https://constellation1.na3.teamsupport.com/knowledgeBase/14528373) article to review this unique process.
