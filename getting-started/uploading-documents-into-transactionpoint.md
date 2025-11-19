
# Uploading Documents into TransactionPoint | Constellation1 Customer Hub

## Uploading Documents into TransactionPoint®

## Overview

Documents can be uploaded into the TransactionPoint® system using a pre-generated coversheet or without a coversheet. Coversheets can be generated from the TransactionPoint® application for uploading documents into a user’s general inbox, or to a specific transaction, order or activity. There are a variety of ways to upload documents into TransactionPoint®. This document is a quick guide to uploading documents into TransactionPoint®.

## Scope and Limitations

*   TransactionPoint supports the following file types, supported file types will be uploaded directly to a transaction or a user’s inbox. Unsupported file types will only be stored in the Message Center.

*   .txt
*   .doc
*   .pdf
*   .tif
*   .dot
*   .xls
*   .ppt
*   .mpp
*   .rtf
*   .tiff
*   .jpeg
*   .jpg
*   .gif
*   .pub
*   .png
*   .vsd
*   .bmp
*   .docx
*   .xlsx
*   .pptx
*   .vcf

*   TransactionPoint rejects the following file types, blacklisted file types will not be processed by any of the TP servers, this includes web services servers,

*   .ade
*   .adp
*   .app
*   .asp
*   .bas
*   .bat
*   .cer
*   .chm
*   .cmd
*   .com
*   .cpl
*   .crt
*   .csh
*   .exe
*   .fxp
*   .hlp
*   .hta
*   .inf
*   .ins
*   .isp
*   .its
*   .js
*   .jse
*   .ksh
*   .lnk
*   .mad
*   .maf
*   .mag
*   .mam
*   .maq
*   .mar
*   .mas
*   .mat
*   .mau
*   .mav
*   .maw
*   .mda
*   .mdb
*   .mde
*   .mdt
*   .mdw
*   .mdz
*   .msc
*   .msi
*   .msp
*   .mst
*   .ops
*   .pcd
*   .pif
*   .prf
*   .prg
*   .pst
*   .reg
*   .scf
*   .scr
*   .sct
*   .shb
*   .shs
*   .tmp
*   .url
*   .vb
*   .vbe
*   .vbs
*   .vsm
*   .cros
*   .vss
*   .vst
*   .vsw
*   .ws
*   .wsc
*   .wsf
*   .wsh
    
    File size limitations
    

|     |     |
| --- | --- |
| **Upload Type** | **Max size** |
| Email | 20 MB (Total Message Size including attachments) |
| Browser Upload | 20 MB |
| Web Service | 50 MB |
| Fax In | 999 pgs / transmission |
| Fax Out | 50 pgs / transmission |
| FTP | 50 MB |

*   Digital documents - Specification Recommendations:
    *   300 dpi recommended, 200 dpi minimum resolution
    *   Black and White only, no gray scale (documents with coversheet only)
    *   File size preferably smaller than 5mb and not to exceed 10mb
    *   Auto-detect page size or page resize disabled
    *   6 Kbps and up modem transmission rate fax machines
    *   TIFF Compressed – G3 scanned images with .TIF extension
    *   Internet connectivity required except for faxing documents with coversheets

## Client Setup:

### FTP  Setup:

*   Internet connectivity to [trpoint.com](ftp://ftp.trpoint.com/) using TCP Port 21
*   FTP Username/Password credentials
*   Documents with coversheet only
*   Black and White only, no gray scale
*   TIFF Compressed – G3 scanned images with .TIF extension, or PDF – check with your account representative to confirm which file type has been set up for your site.
*   Transfer file in Passive Mode (PASV)

### Scanner  Setup:

*   Internet connectivity to FTP or Email
*   300 dpi recommended, 200 dpi minimum resolution
*   Auto-detect page size or page resize disabled
*   TIFF Compressed – G3 scanned images with .TIF extension
*   Documents with coversheet - black and white only, no gray scale
*   Documents without coversheet – colored allowed if emailed

### Fax  Setup:

*   6 Kbps and up modem transmission rate fax machines
*   Black and White only, no gray scale
*   Documents with coversheet only

## Uploading documents with fax coversheet 

### Faxing documents with coversheet

*   Insert coversheet in front of document and fax document to the toll free number indicated in coversheet
*   Multiple documents can be batched together in a single fax transmission, separated by coversheets

### Emailing documents with coversheet

*   Insert coversheet in front of document (batching allowed)
*   Email documents to [docs@fax.trpoint.com](mailto:docs@fax.trpoint.com)

### Using Document Communication Module client application

*   Install Document Communication Module
*   Enter access code provided by TP team
*   Configure module’s outbox, sent box and log folders
*   Schedule recurring processing time, i.e. every 5 mins, 30 mins
*   Copy or move documents to outbox
*   Wait for scheduled process or click on “Run” button to transfer file via web service or FTP
*   TIFF or PDF, TIFF recommended

### Using FTP to upload documents with coversheet

*   FTP to [trpoint.com](ftp://ftp.trpoint.com/) via ftp client, browser or windows explorer
*   Upload documents with coversheets
*   TIFF documents only

### Digital Scanning documents with coversheet

*   Scan documents with coversheet in front of document.
*   Scan destination to email to upload using [docs@fax.trpoint](mailto:docs@fax.trpoint)
*   Scan destination to ftp to upload using [trpoint.com](ftp://ftp.trpoint.com/).
*   Scan destination to folder and upload using document communication module

## Uploading documents without coversheet

### Direct Upload

*   Login to TransactionPoint®
*   Go to Document Center or Transaction Document Box
*   Click on “Upload” button
*   Click on Browse button and select file to upload

### Emailing without coversheet

*   Email transaction documents to: [transactionID@trpoint.com](mailto:transactionID@doc.trpoint.com)        
*   Email order documents to: [orderID$0@trpoint.com](mailto:orderID$0@doc.trpoint.com)
*   Email User Inbox to: [username@trpoint.com](mailto:username@doc.trpoint.com),

(\*Email attachments can be zipped on email and will be automatically extracted and processed.)

### Using Document Management Live (DML)

*   Download install files from TransactionPoint®
*   Install Document Management Live
*   Start Document Management Live
*   Login with TransactionPoint® username and password
*   Select transaction or activities to upload document to
*   Browse for files to upload
*   Submit documents into TransactionPoint®

### Using Print to TP – Printer Driver

*   DML installation provide TransactionPoint® print driver
*   In any application that can print, choose “Print to TP” Printer
*   Select transaction or activities to upload to
*   Submit documents into TransactionPoint®

### Digital Scanning without coversheet

*   Scan destination to email to upload using email address
*   Scan destination to file folder system to upload using DML or upload via browser
    
    ### Direct Upload from Documents Tab
    
    *   Select the ‘Documents’ tab at the top of each screen.
    *   Search for the desired transaction, and make sure it appears selected in the dropdown list
    *   The ‘Transaction Documents’ box for the selected transaction will display, showing documents currently in that file.
    *   Click the ‘Upload’ button to upload documents from the user’s hard drive into the General Documents and Orders activity.
        
        ![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/0fb8bf78-c543-463f-b4d7-c9545815e5e6.png)
        
        The user’s personal Inbox also displays on this screen, below the Transaction Documents box.  The user can move or copy documents from his personal inbox into the desired activity for the transaction on the screen.
        
         

## E-Mailing Documents and Messages to TransactionPoint

When an e-mail with an attachment is sent to [txnid@trpoint.com](mailto:txnid@doc.trpoint.com), , the e-mail content will be added to the Communication Log for that transaction.  And e-mails sent to a TransactionPoint user with or without document attachments will be saved.

Supported document types that can be e-mailed are: .doc, .docx, .xls, .xlsx, .ppt, .pptx, .pdf, .tiff, .tif, .pub, .vcf, .txt, .rtf, .png, .bmp, .jpg, .gif, .zip.    (Zipped files will be extracted automatically during the process. The documents will individually post to the transaction or inbox.)

## E-mails without **attachments** sent to a transaction

E-mails sent to a transaction without an attachment(s) will be placed in the transaction’s Message Center.  From there, they can be moved to the communication log or deleted.  Messages remaining in the Messages tab will be deleted after 90 days.

###  ![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/7fbe7038-abac-422f-91b7-95541bb6eef7.png) 

## E-mails with **attachments** sent to a transaction

E-mails sent to a transaction with attachment(s) will be placed in the specified transaction.  The e-mail message becomes part of the Communication Log and all the attached documents are added to transaction documents, attached to the ‘General Documents and Orders’ activity. 

  **![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/5702096c-9364-49e2-b7c5-d60bc187c34d.png)**

The document name is the name of the attachment.  For Example: if you emailed ‘Order Document.docx’ to [1234-5678@trpoint.com](mailto:1234-5678@doc.trpoint.com), the name will appear in the Transaction Documents box as ‘Order Document.

![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/54b60007-7976-43de-9d3b-e892eca426aa.png) 

The message body of the email appears in the communication log along with a list of the documents that were added to the transaction.  There is a single log entry under the type ‘DOC’ that contains both the names of the documents and the e-mail message.  To make viewing long messages easy, the first 500 characters of the e-mail show in the log, and a ‘more’ button allows you to view the full message.  (The ‘more’ button displays on all messages, since additional options are available)

  
 ![](https://constellation1.na3.teamsupport.com/api/attachments/image/2472652/5c8a98f6-5e1b-4f92-b600-4b94940c7400.png)