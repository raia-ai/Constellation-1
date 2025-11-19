---
title: Constellation1 eSign March 2022 Release Notes
---

# Constellation1 eSign March 2022 Release Notes

Production Release: March 24, 2022 

## RELEASE SUMMARY

**Updated KBA Authentication User Interface:** Improved the KBA pop-up window design.    

**Architecture:** Upgraded various server systems. 

**Bug Fixes**

#### Updated KBA User Interface

We’ve updated the KBA authentication pop-up window design. The updated design features a cleaner layout with a simple workflow that is easier to follow.

![](https://app.na3.teamsupport.com/Wiki/WikiDocs/2472652/images/KB-ReleaseNotes/eSign/esign-2022-March-KBA.png)

####   
Architecture

  
Tall Components Upgrade

We’ve upgraded our Tall Components products to PDFKit.NET 5.0, TallPDF.NET 5.0, and PDFRasterizer.NET 4.0. The update improves system efficiency and functionality when processing PDF documents. 

.NET Upgrade  
We’ve upgraded from .NET Core 2.1 to .NET Core 3.1. We also upgraded to .NET Framework 4.8. These upgrades provide improved system performance and efficiency while keeping eSign on the latest system versions available.  

#### BUG FIXES

*   Fixed an issue with signing sessions getting stuck during a specific use case.
*   Fixed an issue that would cause a signer to get stuck and be unable to continue with their signing session during a specific use case. 
*   Fixed an issue with the Forgot Password workflow. Users with expired passwords can now update them using the Forgot Password workflow. 
*   Fixed an issue with signatures not showing on copied signing sessions. Signatures and tags in the copied session will now show in the new signing session. 
*   Fixed the timeout error when downloading large document when using the API call “getsignerdocuments”. 

Was this article helpful to you?

Was this article helpful to you?