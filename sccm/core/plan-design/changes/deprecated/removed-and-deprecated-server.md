---
title: Deprecated for site servers
titleSuffix: Configuration Manager
description: Learn about the products and operating systems that Configuration Manager no longer supports for site servers.
ms.date: 02/19/2020
ms.prod: configuration-manager
ms.technology: configmgr-other
ms.topic: conceptual
ms.assetid: d53ac075-438b-41da-ab85-42f33982da0c
author: mestew
ms.author: mstewart
manager: dougeby
---

# Removed and deprecated for Configuration Manager site servers

*Applies to: Configuration Manager (current branch)*

This article describes products and operating systems that are removed from support for Configuration Manager site servers, or will be removed in a future update (deprecated). It provides early notice about future changes that might affect your use of Configuration Manager.  

This information may change in the future. It might not include each deprecated feature, product, or operating system.  

## Server OS  

|Operating systems|Deprecation first announced|Support removed|
|-|-|-|
|Windows Server 2008 R2 with SP1|July 10, 2015| Version 1702|
|Windows Server 2008 with SP2|July 10, 2015|Version 1511|

## SQL Server

|SQL Server versions|Deprecation first announced|Support removed|
|-|-|-|
|SQL Server 2008 R2|July 10, 2015|Version 1702|
|SQL Server 2008|July 10, 2015|Version 1511|

If you need to upgrade your version of SQL Server, we recommend the following methods, from easy to more complex:

1. [Upgrade SQL Server in-place](/sccm/core/servers/manage/upgrade-on-premises-infrastructure#BKMK_SupConfigUpgradeDBSrv) (recommended).  

2. Install a new version of SQL Server on a new computer. Then to point your site server at the new SQL Server, [use the database move option](/sccm/core/servers/manage/modify-your-infrastructure#bkmk_dbconfig) of Configuration Manager setup.  

3. Use [backup and recovery](/sccm/protect/understand/backup-and-recovery).  

## Next steps

For more information, see the following articles:

- [Removed and deprecated](/sccm/core/plan-design/changes/deprecated/removed-and-deprecated)  

- [Microsoft Support Lifecycle](https://support.microsoft.com/lifecycle)  

- [Support for current branch versions of Configuration Manager](/sccm/core/servers/manage/current-branch-versions-supported)  
