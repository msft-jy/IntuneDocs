---
# required metadata

title: Your Android device seems to be encrypted
description:
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/25/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: ba593c08-1a78-4013-8525-b45a948772ec
searchScope:
 - User help

# optional metadata

ROBOTS:  
#audience:
#ms.devlang:
ms.reviewer: arnab
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-enduser

---


# Your Android device seems to be encrypted, but Company Portal says otherwise

When you encrypt a device, you are encoding the information on it using a secret key that is known only to you, which prevents unauthorized people from accessing it. As a step towards making sure your information is secured, your organization is requiring you to encrypt your Android device before you can access company files, email, or data.

## Common issues

Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted. Different device manufacturers have varying descriptions and locations for the startup passcode. Most of the time, this is referred to as "Secure Startup." 

## Solutions

### Add a startup PIN

Certain Android devices will require you to create a startup PIN to make sure that your device is secure. There are many versions of Android from many different manufacturers. You can try to fix this issue by finding a location in your settings app to enable this option. For example, on the Samsung Galaxy S7, you enable Secure Startup by going to **Settings** > **Lock Screen and Security** > **Secure Startup**.  

### Downgrade your version of Android
If your device offers you the option to downgrade to Android 6.0+, then do so. There is a risk of data loss if you should try to downgrade your device. Otherwise, we recommend that you contact your IT admin to resolve this issue. You can get contact information for your IT admin at the [Company Portal website](http://portal.manage.microsoft.com) for contact information.

## Specific manufacturer issues

Some Android devices on version 7.0+ encrypt data in ways that is inconsistent with certain Android platform standards. These devices may seem to be encrypted out of the box, but Intune recognizes the methods used as putting the device's information at risk from malicious users who have physical access to the device.

> [!Note]
> Microsoft works with manufacturers to address any issues we find while testing, or that users report to us. We'll update this article whenever new information is available. 

## Known devices

### Known devices that can be updated to fix this issue

If you have one of the following devices, you may experience this issue if you have not updated your device to the most recent version of Android. You can install the updates for these devices by going to **Settings** > **Update**. 

- [Huawei Honor 8](http://consumer.huawei.com/en/support/mobile-phones/honor8_en-sup.htm)
- [Huawei P9](http://consumer.huawei.com/mobile-phones/p9/index.html)

### Known devices that currently cannot be updated to fix this issue

- [Huawei Mate 8](http://consumer.huawei.com/en/mobile-phones/mate8/index.htm)
- [Xiaomi Mi smartphones](https://xiaomi-mi.com/mi-smartphones/)
