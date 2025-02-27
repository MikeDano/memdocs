---
title: Available third-party software update catalogs
titleSuffix: Configuration Manager
description: List of third-party update catalogs available for import into Configuration Manager
ms.date: 08/02/2021
ms.prod: configuration-manager
ms.technology: configmgr-sum 
ms.topic: reference
ms.assetid: 2a118f4d-1757-49d5-9bfd-e0fbd4fc032d
author: mestew
ms.author: mstewart
manager: dougeby
---

# Available third-party software update catalogs

*Applies to: Configuration Manager (current branch)*

The **Third-Party Software Update Catalogs** node in the Configuration Manager console allows you to subscribe to third-party catalogs, publish their updates to your software update point (SUP), and then deploy them to clients. You can [add custom catalogs](third-party-software-updates.md#add-a-custom-catalog) from third-party vendors. 

## Third-party update catalogs available for import
<!--9989251-->
To make it easier to find custom catalogs, we're providing a list of links as a convenience. Some catalogs are freely available and some catalogs have an additional cost associated with them. This list includes catalogs that may only work with [System Center Updates Publisher](../tools/updates-publisher.md) and not the **Third-Party Software Update Catalogs** node in the Configuration Manager console. Check with the catalog provider for details including pricing, support, and if the catalog supports in-console third-party updates.

|</br></br>Custom catalog provider|</br></br> URL|
|--|--|
|Adobe | Multiple catalogs are available from Adobe. </br>  https://www.adobe.com/devnet-docs/acrobatetk/tools/DesktopDeployment/sccm.html |
|Centero Software Manager| https://software-manager.com/csm-for-sccm-patch-management-solution |
|Dell| *Partner catalog* available in the **Third-Party Software Update Catalogs** node </br> https://www.dell.com/support/article/sln311138/ </br></br> https://downloads.dell.com/Catalog/DellSDPCatalogPC.cab </br></br>ftp://ftp.dell.com/catalog/DellSDPCatalog.cab |
|Fujitsu| https://support.ts.fujitsu.com/GFSMS/globalflash/FJSVUMCatalogForSCCM.cab |
|HP| *Partner catalog* available in the **Third-Party Software Update Catalogs** node <br> https://hpia.hpcloud.hp.com/downloads/sccmcatalog/HpCatalogForSms.latest.cab</br></br> `http://ftp.hp.com/pub/softlib/software/sms_catalog/HpCatalogForSms.latest.cab` |
|Ivanti Patch for MEM | https://www.ivanti.com.au/products/patch-management-for-mem |
|Lenovo | *Partner catalog* available in the **Third-Party Software Update Catalogs** node </br> https://download.lenovo.com/luc/v2/LenovoUpdatesCatalog2v2.cab </br></br> Lenovo updates catalog V3 information </br> https://thinkdeploy.blogspot.com/2020/06/lenovo-updates-catalog-v3-for-sccm.html </br></br> Lenovo Patch </br> https://www.lenovo.com/us/en/software/lenovo-patch-sccm |
|ManageEngine Patch Connect Plus| https://www.manageengine.com/sccm-third-party-patch-management |
|Patch My PC| Full catalog </br> https://patchmypc.com/third-party-patch-management-for-sccm-and-intune </br></br> Limited catalog </br> https://patchmypc.com/frequently-asked-questions#trial-catalog |
|SolarWinds Patch Manager| https://www.solarwinds.com/patch-manager/use-cases/third-party-patch-management-sccm |

## Open this article from the Configuration Manager console
<!--9989251-->
Starting in Configuration Manager 2107, you can  choose **More Catalogs** from the ribbon in the **Third-party software update catalogs** node to get to this article. Right-clicking on **Third-Party Software Update Catalogs** node displays a **More Catalogs** menu item.  Selecting **More Catalogs** opens a link to to this page.  

:::image type="content" source="./media/9989251-more-catalogs.png" alt-text="Screenshot of the Third-Party Software Update Catalogs node with the More Catalogs icon in the ribbon":::

## Next steps

- [Add custom catalogs for third party software updates](third-party-software-updates.md#add-a-custom-catalog)
- [Configure the SUP to synchronize the product](../get-started/configure-classifications-and-products.md#to-configure-classifications-and-products-to-synchronize) into Configuration Manager
