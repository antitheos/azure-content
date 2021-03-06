<properties
   pageTitle="What's New in Azure Data Catalog"
   description="Overview of new capabilities in the Azure Data Catalog preview."
   services="data-catalog"
   documentationCenter=""
   authors="steelanddata"
   manager="NA"
   editor=""
   tags=""/>
<tags
   ms.service="data-catalog"
   ms.devlang="NA"
   ms.topic="article"
   ms.tgt_pltfrm="NA"
   ms.workload="data-catalog"
   ms.date="09/04/2015"
   ms.author="maroche"/>

# What's new in Azure Data Catalog

Updates to **Azure Data Catalog** are released on a regular basis. Not every release will include new user-facing features, as some releases are focused on back-end service capabilities. This page will highlight new user-facing capabilities added to the **Azure Data Catalog** service.

## What's new for the week of September 4, 2015 release

As of the week of September 4, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for manually registering unknown data source types. Users can manually enter data source information using the **Azure Data Catalog** portal, so that data sources not explicitly supported by the data source registration tool can be annotated and discovered.
- Support for registering and discovering SQL Server databases as containers. When registering SQL Server tables and views, **Azure Data Catalog** will create an entry for the database as well as for the tables and views. The database can be discovered and annotated using the **Azure Data Catalog** portal. Users can also search and filter the contents of a database in addition to searching and filtering the contents of the catalog.


> [AZURE.NOTE] SQL Server tables and views that have been registered prior to the 2015-09-04 release must be re-registered using the data source registration tool before the database entry will be added to the catalog. Re-registering a data source does not affect any annotations that have been added by users in the **Azure Data Catalog** portal.

## What's new for the week of August 28, 2015 release

As of the week of August 28, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for data profiling of SQL Server and Oracle data sources. When registering SQL Server and Oracle tables and views, users can choose to include data profile information for the objects being registered. The data profile includes object-level and column-level statistics.
- Support for Hadoop HDFS data sources. Users can now register and discover HDFS files and directories.

## What's new for the week of August 21, 2015 release

As of the week of August 21, 2015, the following capabilities have been added to **Azure Data Catalog**:

- Support for providing access request information for registered data sources. For any registered data asset, users can now provide instructions for requesting access, including email links or URLs, to easily integrate with existing tools and processes.
- Tool tips for tags and experts, to make it easier to discover what users have provided what metadata for registered data assets.
- We’ve added a new “User” button and menu to our top navigation bar. This menu lets the user see the account used to log on to **Azure Data Catalog**, and to sign out if desired. This menu also displays the catalog name, which is valuable to developers using the **Azure Data Catalog** REST API.
- Standard Edition Only: When adding owners to data assets, **Azure Data Catalog** now supports both user accounts and security groups as owners. To add a security group as an owner for selected data assets, you can enter either the group’s display name or the group’s UPN email address, if it has one.
- Support for Azure Blob Storage data sources. Users can now register and discover Azure Storage blobs and directories.
