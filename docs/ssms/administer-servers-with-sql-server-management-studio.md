---
description: "Administer Servers with SQL Server Management Studio"
title: "Administer Servers with SQL Server Management Studio"
ms.custom: seo-lt-2019
ms.date: "01/19/2017"
ms.prod: sql
ms.prod_service: "sql-tools"
ms.reviewer: ""
ms.technology: ssms
ms.topic: conceptual
helpviewer_keywords: 
  - "SQL Server Management Studio [SQL Server], servers"
  - "servers [SQL Server], administering"
ms.assetid: 938bb035-e07a-4082-9f93-229d9feb6b06
author: "markingmyname"
ms.author: "maghan"
---
# Administer Servers with SQL Server Management Studio

[!INCLUDE[SQL Server Azure SQL Database Synapse Analytics PDW ](../includes/applies-to-version/sql-asdb-asdbmi-asa-pdw.md)]

Microsoft SQL Server Management Studio is a rich, integrated administrative client designed to meet the SQL Server and Azure SQL Database administrator's server management requirements. In [!INCLUDE[ssManStudio](../includes/ssmanstudio-md.md)], administrative tasks are accomplished using Object Explorer, which allows you to connect to any server in the SQL Server family and graphically browse its contents. A server can be an instance of the [!INCLUDE[ssDE](../includes/ssde_md.md)], [!INCLUDE[ssASnoversion](../includes/ssasnoversion_md.md)], [!INCLUDE[ssRSnoversion](../includes/ssrsnoversion-md.md)], [!INCLUDE[ssISnoversion](../includes/ssisnoversion-md.md)] or Azure SQL Database.  
  
The tool components of [!INCLUDE[ssManStudio](../includes/ssmanstudio-md.md)] include Registered Servers, Object Explorer, Solution Explorer, Template Explorer, the Object Explorer Details page, and the document window. To display a tool, on the **View** menu, click the tool name. To display the Query Editor tool, click the **New Query** button on the toolbar.  
  
> [!IMPORTANT]  
> Network traffic between [!INCLUDE[ssManStudio](../includes/ssmanstudio-md.md)] and SQL Server is unencrypted by default. Do not work with sensitive data (including passwords) in [!INCLUDE[ssManStudio](../includes/ssmanstudio-md.md)] unless you have established an encrypted connection. For more information, see [How to: Enable Encrypted Connections to the Database Engine (SQL Server Configuration Manager)](../database-engine/configure-windows/enable-encrypted-connections-to-the-database-engine.md).  
  
Use [!INCLUDE[ssManStudio](../includes/ssmanstudio-md.md)] to:  
  
- Register servers.  
  
- Connect to an instance of the Database Engine, SSAS, SSRS, SSIS or Azure SQL Database.  
  
- Configure server properties.  
  
- Manage database and SSAS objects such as cubes, dimensions, and assemblies.  
  
- Create objects, such as databases, tables, cubes, database users, and logins.  
  
- Manage files and filegroups.  
  
- Attach or detach databases.  
  
- Launch scripting tools.  
  
- Manage security.  
  
- View system logs.  
  
- Monitor current activity.  
  
- Configure replication.  
  
- Manage full-text indexes.  
  
To start and stop SQL Server or SQL Server Agent, use SQL Server Configuration Manager.  
  
## See Also

- [Use SQL Server Management Studio](./sql-server-management-studio-ssms.md)  
- [How to: View server properties (SQL Server Management Studio)](../database-engine/configure-windows/view-or-change-server-properties-sql-server.md)  
