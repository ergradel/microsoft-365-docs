---
title: Onboarding tools and methods for Windows 10 devices
description: Onboard Windows 10 devices so that they can send sensor data to the Microsoft Defender ATP sensor
keywords: Onboard Windows 10 devices, group policy, endpoint configuration manager, mobile device management, local script, gp, sccm, mdm, intune
search.product: eADQiWindows 10XVcnh
search.appverid: met150
ms.prod: m365-security
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
localization_priority: Normal
manager: dansimp
audience: ITPro
ms.collection: M365-security-compliance
ms.topic: conceptual
ms.technology: mde
---

# Onboarding tools and methods for Windows 10 devices

[!INCLUDE [Microsoft 365 Defender rebranding](../../includes/microsoft-defender.md)]

**Applies to:**
- [Microsoft Defender for Endpoint](https://go.microsoft.com/fwlink/p/?linkid=2154037)
- [Microsoft 365 Defender](https://go.microsoft.com/fwlink/?linkid=2118804)
- [Microsoft 365 Endpoint data loss prevention (DLP)](/microsoft-365/compliance/endpoint-dlp-learn-about)
- [Microsoft 365 Insider risk management](/microsoft-365/compliance/insider-risk-management)

>Want to experience Defender for Endpoint? [Sign up for a free trial.](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?ocid=docs-wdatp-assignaccess-abovefoldlink)

Devices in your organization must be configured so that the Defender for Endpoint service can get sensor data from them. There are various methods and deployment tools that you can use to configure the devices in your organization.

The following deployment tools and methods are supported:

- Group Policy
- Microsoft Endpoint Configuration Manager
- Mobile Device Management (including Microsoft Intune)
- Local script

## In this section
Topic | Description
:---|:---
[Onboard Windows 10 devices using Group Policy](configure-endpoints-gp.md) | Use Group Policy to deploy the configuration package on devices.
[Onboard Windows devices using Microsoft Endpoint Configuration Manager](configure-endpoints-sccm.md) | You can use either use Microsoft Endpoint Manager (current branch) version 1606 or Microsoft Endpoint Manager (current branch) version 1602 or earlier to deploy the configuration package on devices.
[Onboard Windows 10 devices using Mobile Device Management tools](configure-endpoints-mdm.md) | Use Mobile Device Management tools or Microsoft Intune to deploy the configuration package on device.
[Onboard Windows 10 devices using a local script](configure-endpoints-script.md) | Learn how to use the local script to deploy the configuration package on endpoints.
[Onboard non-persistent virtual desktop infrastructure (VDI) devices](configure-endpoints-vdi.md) | Learn how to use the configuration package to configure VDI devices.


>Want to experience Defender for Endpoint? [Sign up for a free trial.](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?ocid=docs-wdatp-configureendpoints-belowfoldlink)
