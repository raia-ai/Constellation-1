---
title: "QuickBooks® Online Security Enhancement for Commissions Desktop"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/23115022"
tags: ["Commissions & Accounting"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "QuickBooks® Online Security Enhancement for Commissions Desktop This article provides the instructions to update Commissions Desktop to support the ne"
long_description: "QuickBooks® Online Security Enhancement for Commissions Desktop This article provides the instructions to update Commissions Desktop to support the new security enhancements implemented in QuickBooks® Online and effective March 1, 2024.  Please note, you must be running the most up to date version of Commissions Desktop (v5.4.0.11111). Update Commissions Desktop To check your version, please navigate to Help / License Information To update the application, please click here for the step-by-step"
---

# QuickBooks® Online Security Enhancement for Commissions Desktop

This article provides the instructions to update Commissions Desktop to support the new security enhancements implemented in QuickBooks® Online and effective **March 1, 2024**. 

**Please note, you must be running the most up to date version of Commissions Desktop (v5.4.0.11111).**

_**Update Commissions Desktop**_

To check your version, please navigate to Help / License Information

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a1ceaab4-91fd-4724-bdc7-71086fd14284)

To update the application, please click here for the step-by-step instructions; [System Update and Backup](https://constellation1.na3.teamsupport.com/knowledgeBase/13670491)

_**Replacing the DLL's**_

Once updated to v5.4.0.1111, please click on this link; [https://cwastoragedev.blob.core.windows.net/misc/bocpatchfeb2024/boc\_qbo\_dlls.zip](https://cwastoragedev.blob.core.windows.net/misc/bocpatchfeb2024/boc_qbo_dlls.zip "https://cwastoragedev.blob.core.windows.net/misc/bocpatchfeb2024/boc_qbo_dlls.zip") which will save to your local PC's "Downloads" folder.

**Please note, Commissions Desktop cannot be launched when replacing the files noted below and the files MUST be replaced on your internal server and all applicable workstations.**

Navigate to your local PC's Downloads folder and unzip the folder. Copy the folder and its contents to a temporary folder on your C:\\Drive. Inside the unzipped "BOC QBO DLLS" folder you copy all the files and paste to “C:\\Program Files (x86)\\Emphasys\\quickTRS” folder (the folder may be different if the application was not installed to the default folder initially)

When prompted to replace the DLL's, select YES for all DLL's.

Once completed, you can launch Commissions Desktop and when possible please try to process a transactions closing, integrate a trust deposit, email a document or Import Transactions from your Transaction Management application (Skyslope, Dotloop, etc.) as there are some components related to these modules that are affected.