---
title: "Configure Email Notifications (Master Data Services) | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "master-data-services"
ms.tgt_pltfrm: ""
ms.topic: conceptual
helpviewer_keywords: 
  - "e-mail [Master Data Services], configuring"
  - "notifications [Master Data Services], configuring notifications"
ms.assetid: 4241a6ab-7465-471b-9890-57c6b572037e
caps.latest.revision: 6
author: "douglaslMS"
ms.author: "douglasl"
manager: craigg
---
# Configure Email Notifications (Master Data Services)
  Configure notification emails when you want [!INCLUDE[ssMDSshort](../includes/ssmdsshort-md.md)] to send email messages automatically.  
  
### To configure notifications  
  
1.  In [!INCLUDE[ssMDScfgmgr](../includes/ssmdscfgmgr-md.md)], on the **Database** page, select your [!INCLUDE[ssMDSshort](../includes/ssmdsshort-md.md)] database.  
  
2.  In the **System Settings** section, click **Create Profile**.  
  
3.  Complete all required fields. For more information, see [Create Database Mail Profile and Account Dialog Box &#40;Master Data Services Configuration Manager&#41;](../../2014/master-data-services/create-database-mail-profile-and-account-dialog-box.md).  
  
4.  Click **OK**.  
  
    > [!NOTE]  
    >  After you configure notifications, you cannot use [!INCLUDE[ssMDScfgmgr](../includes/ssmdscfgmgr-md.md)] to make changes. You must make changes directly in the [!INCLUDE[ssMDSshort](../includes/ssmdsshort-md.md)] database. For more information, see [Database Mail Configuration Objects](../relational-databases/database-mail/database-mail-configuration-objects.md).  
  
## Next Steps  
  
-   There are settings in [!INCLUDE[ssMDScfgmgr](../includes/ssmdscfgmgr-md.md)] that affect notifications. You can adjust these settings in [!INCLUDE[ssMDScfgmgr](../includes/ssmdscfgmgr-md.md)] or directly in the System Settings table in the [!INCLUDE[ssMDSshort](../includes/ssmdsshort-md.md)] database. For more information, see [System Settings &#40;Master Data Services&#41;](system-settings-master-data-services.md).  
  
## See Also  
 [Notifications &#40;Master Data Services&#41;](../../2014/master-data-services/notifications-master-data-services.md)   
 [Troubleshooting Email Notifications (Master Data Services)](http://social.technet.microsoft.com/wiki/contents/articles/troubleshooting-email-notifications-master-data-services.aspx)   
 [Configure Business Rules to Send Notifications &#40;Master Data Services&#41;](../../2014/master-data-services/configure-business-rules-to-send-notifications-master-data-services.md)  
  
  