---
# required metadata

title: How to wipe only corporate data from appstitleSuffix: "Intune Azure preview"
description: "Intune Azure preview: Learn how to selectively wipe apps with Microsoft Intune."
keywords:
author: andredm7
ms.author: andredm
manager: angrobe
ms.date: 02/07/2016
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 42605e6e-5b84-44ff-b86e-346ea123b53e

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: mghadial
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure
---

# How to wipe only corporate data from Intune-managed apps

[!INCLUDE[azure_preview](./includes/azure_preview.md)]

When a device is lost or stolen, or if the employee leaves your company, you want to make sure company app data is removed from the device. But you might not want to remove personal data on the device, especially if this is an employee-owned device.

To selectively remove company app data, create a wipe request by using the steps in this topic. After the request is finished, the next time the app runs on the device, company data is removed from the app.

>[!IMPORTANT]
> Contacts synced directly from the app to the native address book are removed. Any contacts synced from the native address book to another external source cannot be wiped. Currently, this only applies to the Microsoft Outlook app.

## Create a wipe request

1.  Sign in to the [Azure portal](https://portal.azure.com).

2.  Choose **More Services**, type **Intune** in the filter textbox, and select **Intune**. The Intune preview blade opens, choose the **Manage apps** blade.

	![Screenshot of the New wipe request blade](./media/intune-azure-preview-blade.png)

3.  On the **Mobile Apps blade**, choose **New wipe request**. The **New wipe request** blade opens.

4.  Choose  **New wipe request**. The **New wipe request** blade opens.

    ![Screenshot of the New wipe request blade](./media/AzurePortal_MAM_NewWipeRequest.png)

5.  Choose **User** to open the **User** blade, and select the user whose app data you want to wipe.

6.  Choose **Device**. This opens the **Device** blade that lists all the devices associated with the selected user, and also provides two columns, the device name, which is a friendly name defined by the user, and the device type, its device platform. Select the device you want to wipe.

7.  You are now back on the **New wipe request** blade. Choose **Ok** to make a wipe request. 

The service creates and tracks a separate wipe request for each protected app on the device, and the user associated with the wipe request.

## Monitor your wipe requests

You can have a summarized report that shows the overall status of the wipe request, and includes the number of pending requests and failures. To get more details, follow these steps:

1.  On the **Mobile Apps - App Selective Wipe blade** blade, you can see the list of your requests grouped by users. Because the system creates a wipe request for each protected app running on the device, you might see multiple requests for a user. The status indicates whether a wipe request is **pending**, **failed**, or **successful**.

	![Screenshot of the New wipe request blade](./media/wipe-request-status-1.png)

Additionally, you'll be able to see the device name, and its device type, which can be helpful when reading the reports.

>[!IMPORTANT]
> The user must open the app for the wipe to occur, and the wipe may take up to 30 minutes after the request was made.

## Delete a wipe request

Wipes with pending status are displayed until you manually delete them.  To manually delete a wipe request:

1.  On the **Wipe request** blade, choose the **Wipe request** tile to open the **Wipe request** blade.

2.  Right-click on the wipe request you want to delete, then choose **Delete wipe request**.

	![Screenshot of the New wipe request blade](./media/delete-wipe-request.png)

3.  You're prompted to confirm the deletion, choose **Yes** or **No**, then click **OK**.

### See also
[What's app protection policy](app-protection-policy.md)

[What's app management](app-management.md)