---
title: Microsoft Defender ATP for Android - Privacy information
description: Privacy controls, how to configure policy settings that impact privacy and information about the diagnostic data collected in Microsoft Defender ATP for Android.
keywords: microsoft, defender, atp, android, privacy, diagnostic
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

#  Microsoft Defender for Endpoint on Android - Privacy information

**Applies to:**
- [Microsoft Defender for Endpoint](https://go.microsoft.com/fwlink/p/?linkid=2154037)
- [Microsoft 365 Defender](https://go.microsoft.com/fwlink/?linkid=2118804)

> Want to experience Microsoft Defender for Endpoint? [Sign up for a free trial.](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?ocid=docs-wdatp-exposedapis-abovefoldlink) 


Defender for Endpoint for Android collects information from your configured
Android devices and stores it in the same tenant where you have Defender for Endpoint.

Information is collected to help keep Defender for Endpoint for Android secure,
up-to-date, performing as expected and to support the service.

## Required Data 

Required data consists of data that is necessary to make Defender for Endpoint
for Android work as expected. This data is essential to the operation of the
service and can include data related to the end user, organization, device, and
apps. Here's a list of the types of data being collected:

### App information

Information about Android application packages (APKs) on the device including

-  Install source
-  Storage location (file path) of the APK
-  Time of install, size of APK and permissions

### Web page / Network information

- Full URL (on supported browsers), when clicked
- Connection information
- Protocol type (such as HTTP, HTTPS, etc.)


### Device and account information

- Device information such as date & time, Android version, OEM model, CPU
        info, and Device identifier
- Device identifier is one of the below:
    - Wi-Fi adapter MAC address
    - [Android
            ID](https://developer.android.com/reference/android/provider/Settings.Secure#ANDROID_ID)
            (as generated by Android at the time of first boot of the device)
    - Randomly generated globally unique identifier (GUID)

- Tenant, Device and User information
    -   Azure Active Directory (AD) Device ID and Azure User ID: Uniquely
            identifies the device, User respectively at Azure Active directory.

    -   Azure tenant ID - GUID that identifies your organization within
            Azure Active Directory

    -   Microsoft Defender ATP org ID - Unique identifier associated with
            the enterprise that the device belongs to. Allows Microsoft to
            identify whether issues are impacting a select set of enterprises
            and how many enterprises are impacted 

    -   User Principal Name – Email ID of the user

### Product and service usage data
-   App package info, including name, version, and app upgrade status

-   Actions performed in the app

-   Threat detection information, such as threat name, category, etc.

-   Crash report logs generated by Android

## Optional Data

Optional data includes diagnostic data and feedback data. Optional diagnostic
data is additional data that helps us make product improvements and provides
enhanced information to help us detect, diagnose, and fix issues. Optional
diagnostic data includes:

-   App, CPU, and network usage

-   State of the device from the app perspective, including scan status, scan
    timings, app permissions granted, and upgrade status

-   Features configured by the admin

-   Basic information about the browsers on the device

**Feedback Data** is collected through in-app feedback provided by the user

-   The user’s email address, if they choose to provide it

-   Feedback type (smile, frown, idea) and any feedback comments submitted by
    the user
