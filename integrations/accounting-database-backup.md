---
title: "Accounting - Database Backup"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/25367919"
tags: ["Integrations"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "Accounting - Database Backup | Constellation1 Customer Hub The purpose of this article is to provide steps for backing up the data in your Accounting"
long_description: "Accounting - Database Backup | Constellation1 Customer Hub The purpose of this article is to provide steps for backing up the data in your Accounting program.  It is very important that you establish a backup routine as soon as you start entering information into your Accounting program. It is recommended that you backup your data at least once a day.  To back up your data, you simply need to navigate to System > Processing > Database Backup, then click the Backup Database button.  Note: It is n"
---

# Accounting - Database Backup | Constellation1 Customer Hub

The purpose of this article is to provide steps for backing up the data in your Accounting program.  

It is very important that you establish a backup routine as soon as you start entering information into your Accounting program.  It is recommended that you backup your data at least once a day.    

To back up your data, you simply need to navigate to **System > Processing > Database Backup**, then click the **Backup Database** button**.** 

Note:  It is not necessary to enter a path in the **Backup Location on Database Server** field, if you do not wish to utilize the **Other Backup Location** function.  In this instance, as soon as you click the **Backup Database** button, a backup is created in the **Backup** folder located in your **Microsoft SQL Server** folder.                 

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/f64f061c-2575-4a39-af3d-1384c406247d) 

If you do wish to utilize the **Other Backup Location** function, you will need to reach out to your IT to set this up.  They will need to provide you with the path to the **Backup** folder in your **Microsoft SQL Server** folder, and you will need to enter that into the **Backup** **Location on Database Server** field.  After that is entered, you can enter the path to the second backup location into the **Other Backup Location** field.  Once both paths have been entered, click the **Backup Database** button.        

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/8b3560fe-a6c5-4085-8209-58babd4560d4)

If the backup was successful, you will receive a message similar to the one shown below.  Note: The **Database Backup** message will also point out how many backups you have in your backup folder.  If too many accumulate, you may want to point this out to your IT; they may want to remove some of them in order to save disk space.    

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/1cad0275-b8b9-4f66-941a-45567c8f9413)

\*If you would like to have Constellation1 manage your backups, contact [accounting@constellation1.com](mailto:sales@constellation1.com) to request information on our hosting service.