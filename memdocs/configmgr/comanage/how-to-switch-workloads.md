---
title: Switch co-management workloads
titleSuffix: Configuration Manager
description: Learn how to switch workloads currently managed by Configuration Manager to Microsoft Intune.
ms.prod: configuration-manager
ms.technology: configmgr-comanage
author: mestew
ms.author: mstewart
manager: dougeby
ms.date: 07/16/2020
ms.topic: how-to
ms.assetid: 60e2022f-a4f9-40dd-af01-9ecb37b43878
---

# How to switch Configuration Manager workloads to Intune

One of the benefits of co-management is switching workloads from Configuration Manager to Microsoft Intune. When a Windows 10 device has the Configuration Manager client and is enrolled to Intune, you get the benefits of both services. You control which workloads, if any, you switch the authority from Configuration Manager to Intune. Configuration Manager continues to manage all other workloads, including those workloads that you don't switch to Intune, and all other features of Configuration Manager that co-management doesn't support.

If you switch a workload to Intune, but later change your mind, you can switch it back to Configuration Manager.

For more information on the supported workloads, see [Workloads](workloads.md).

## Switch workloads 
<!--3555750 FKA 1357954 -->
You can configure different pilot collections for each of the co-management workloads. Being able to use different pilot collections allows you to take a more granular approach when shifting workloads. You can switch workloads when you enable co-management, or later when you're ready. If you haven't already enabled co-management, do that first. For more information, see [How to enable co-management](how-to-enable.md). After you enable co-management, modify the settings in the co-management properties.

1. In the Configuration Manager console, go to the **Administration** workspace, expand **Cloud Services**, and select the **Cloud Attach** node. For version 2103 and earlier, select the **Co-management** node.
1. Select the co-management object, and then choose **Properties** in the ribbon.  
1. Switch to the **Workloads** tab. By default, all workloads are set to the **Configuration Manager** setting. To switch a workload, move the slider control for that workload to the desired setting.  

    ![Screenshot of Workloads tab on co-management properties page](media/3555750-co-management-workloads-tab.png)

    - **Configuration Manager**: Configuration Manager continues to manage this workload.  

    - **Pilot Intune**: Switch this workload only for the devices in the pilot collection. You can change the **Pilot collections** on the **Staging** tab of the co-management properties page.  

    - **Intune**: Switch this workload for all Windows 10 devices enrolled in co-management.  

4. Go to the **Staging** tab and change the **Pilot collection** for any of the workloads if needed.
  
   ![Screenshot of Staging tab on co-management properties page](media/3555750-co-management-staging-tab.png)

> [!Important]  
> Before you switch any workloads, make sure you properly configure and deploy the corresponding workload in Intune. Make sure that workloads are always managed by one of the management tools for your devices. When you switch a co-management workload, the co-managed devices automatically synchronize MDM policy from Microsoft Intune. <!--7087526-->


## Next steps

[Monitor co-management](how-to-monitor.md)
