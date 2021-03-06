---
title: "What is Analysis Services? | Microsoft Docs"
ms.date: 02/04/2020
ms.prod: sql
ms.technology: analysis-services
ms.topic: overview
ms.author: owend
ms.reviewer: owend
author: minewiskan
monikerRange: "asallproducts-allversions || azure-analysis-services-current || power-bi-premium-current || >= sql-analysis-services-2016"
---
# What is Analysis Services?

[!INCLUDE[ssas-appliesto-sqlas-all-aas-pbip](../includes/ssas-appliesto-sqlas-all-aas-pbip.md)]

Analysis Services is an analytical data engine (Vertipaq) used in decision support and business analytics. It provides enterprise-grade semantic data models for business reports and client applications such as Power BI, Excel, Reporting Services reports, and other data visualization tools. Analysis Services is available in different platforms:

**SQL Server Analysis Services** - Installed as an on-premises server instance, SQL Server Analysis Services supports tabular models at all compatibility levels (depending on version), multidimensional models, data mining, and Power Pivot for SharePoint.

**Azure Analysis Services** - Created as an Azure resource, Azure Analysis Services server resources support tabular models at the 1200 and higher compatibility levels. DirectQuery, partitions, row-level security, bi-directional relationships, and translations are all supported. To learn more, see [What is Azure Analysis Services](/azure/analysis-services/analysis-services-overview).

**Power BI Premium (Preview)** - The Analysis Services Vertipaq engine provides programmability, client application, and tool support for Power BI Premium datasets through client libraries and APIs that support the open-standard XMLA protocol. Power BI Premium datasets support connections through XMLA endpoints for *read-only* and *read-write* operations from Microsoft and third-party client applications and tools. To learn more, see [Power BI Premium dataset connectivity with the XMLA Endpoint](https://docs.microsoft.com/power-bi/service-premium-connect-tools).

## Documentation

Analysis Services documentation is located at different places in docs.microsoft.com depending on the platform or version you're using. In general, [Azure Analysis Services documentation](https://docs.microsoft.com/azure/analysis-services/) is included with Azure documentation. If you're interested in having your tabular models in the cloud, it's best to start there. 

Documentation you see in the Table of Contents to the left is known as the core Analysis Services documentation. Core documentation can apply to just one platform, like SQL Server Analysis Services, or to all Analysis Services platforms including Azure Analysis Services. This is because how you create and deploy a tabular model, or manage certain server properties or databases is much the same, regardless of platform.

In the core documentation, at the top of each article an **Applies To** banner indicates the platforms the article applies to. Keep in mind, feature and functionality changes are happening to each platform all the time. When they do, we make every effort to update the documentation.

Looking for **SQL Server 2014 Analysis Services** documentation? - SQL Server 2014 Analysis Services documentation is kept separate from later version documentation. This is due to changing documentation models used on docs.microsoft.com compared to MSDN, where SQL Server 2014 and earlier Books Online documentation was originally published. Go to [SQL Server 2014 Analysis Services documentation](https://docs.microsoft.com/sql/analysis-services/analysis-services?view=sql-server-2014). Need to go back even further? See [SQL Server previous versions documentation](https://docs.microsoft.com/previous-versions/sql/).

## See also

[Azure Analysis Services documentation](https://docs.microsoft.com/azure/analysis-services/)   
[What is Power BI Premium?](https://docs.microsoft.com/power-bi/service-premium-what-is)   
