
# Accounting – System Setting REPORTTIMEOUT

The purpose of this article is to provide information regarding system setting **REPORTTIMEOUT**.

Because some reports take longer to process than others, you may occasionally face a timeout error when processing a report.  The default time, for system setting **REPORTTIMEOUT**, is 60 seconds but can be changed as needed. If a report times out, close the report parameters tab for that report, navigate to **System** \> **Setup** \> **System Settings** and increase the **Numeric Value** of system setting **REPORTTIMEOUT** by 60 seconds, then re-open the report parameters for the report again.

**REPORTTIMEOUT** should only be made as large as necessary.  You may be tempted to make it exceedingly large (e.g. 3600 seconds = 1 hour) but that just means that the process will run for an hour before timing out.  Because of this, we recommend increasing the **Numeric Value** by 60 seconds. Repeat this process until you are able to process the report without timeouts.

In practice, if REPORTTIMEOUT is 300 (= 5 minutes) and a report still times out, you should contact [Accounting@constellation1.com](mailto:Accounting@constellation1.com) to report the issue. 

Was this article helpful to you?

Was this article helpful to you?