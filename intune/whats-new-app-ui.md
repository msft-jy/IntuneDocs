---
# required metadata

title: UI updates for Intune end-user apps
titlesuffix: Microsoft Intune
description: Find out what has changed in UI for apps that work on end-user devices with Microsoft Intune.
keywords:
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 03/29/2018
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: b782e382-8deb-48a7-a437-d7c5a17163f1

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: priyar
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure

---
# UI updates for Intune end-user apps
Learn what updates have been made to the UI for apps that your end users will see in this release of Microsoft Intune. Understanding these updates can help you with user communications and any updating custom documentation that you've created to support your deployment. It can also help you understand how to better troubleshoot any issues they're facing should they call helpdesk for support using the Company Portal.

<!---End-user messaging for accounts 1573558, 1712; changes to be made for other platforms for 1801 Users of the Company Portal website, will be blocked from taking actions that require write access to your tenant. They will see appropriate error messaging explaining that their account is under maintenance. Similar changes are coming to the Company Portal apps for Android, iOS, macOS, and Windows soon. ![Error message that occurs during account move](./media/account-move-rom-iwp-user-1712.png)--->

## Week of April 23, 2018
#### Updated navigation view in the Company Portal app for Windows 10 <!-- 1195010 -->
The Intune Company Portal app for Windows 10 has been updated with the [Fluent Design System's navigation view](https://docs.microsoft.com/en-us/windows/uwp/design/basics/navigation-basics). Along the side of the app, you'll notice a static, vertical list of all top-level pages. Click any link to quickly view and switch between pages. This is the first of several updates you'll see as part of our ongoing effort to create a more adaptive, empathetic, and familiar experience in Intune. 

![Screenshot of the Company Portal app dashboard showing the Fluent Design navigation view](./media/1804_WindowsCP_Fluent_01.png)


## Week of April 2, 2018

#### User experience update for the Company Portal app for iOS <!-- 1412866 -->
We've released a major user experience update to the Company Portal app for iOS. The update features a complete visual redesign that includes a modernized look and feel. We've maintained the functionality of the app, but increased its usability and accessibility.  

You'll also see:
- Support for iPhone X.
- Faster app launch and loading responses, to save users time.
- Additional progress bars to provide users with the most up-to-date status information.
- Improvements to the way users upload logs, so if something goes wrong, it's easier to report.  

|Before|After|
|---|---|
|![01](/intune/media/cp_iosRedesign_before_1803_01.png)|![01](/intune/media/cp_iosRedesign_after_1803_01.png)|
|*Combined with previous step*|![02](/intune/media/cp_iosRedesign_after_1803_02.png)|
|![03](/intune/media/cp_iosRedesign_before_1803_02.png)|![03](/intune/media/cp_iosRedesign_after_1803_03.png)|

#### Improvements to the language in the Company Portal app for Windows <!---1683758--->
We've improved the language in the Company Portal for Windows 10 to be more user-friendly and specific to your company.

|Before|After|
|---|---|
|![01](./media/windows_enroll_before_1803.png)|![01](./media/windows_enroll_after_1803.png)|
|![02](./media/windows_view_policy_issues_before_1803.png)|![02](./media/windows_view_policy_issues_after_1803.png)

## Week of March 12, 2018

#### Company Portal for Android visual updates <!--976944 -->

We've updated the Company Portal app for Android to follow Android's [Material Design](https://material.io/) guidelines.

|Before|After|
|---|---|
|![01](./media/android_about_before_1803.png)|![01](./media/androidCP_about_after_1803.png)|
|![02](./media/android_contact_it_before_1803.png)|![02](./media/android_contact_it_after_1803.png)|
|![03](./media/android_devices_before_1803.png)|![03](./media/androidCP_devicelist_after_1803.png)|
|![04](./media/android_device_details_before_1803.png)|![05](./media/androidCP_devicedetails_1_after1803.png)|
|![05](./media/android_device_details_update_settings_before_1803.png)|![05](./media/androidCP_devicedetails_red_box_2_after1803.png)|
|![06](./media/android_profile_before_1803.png)|![06](./media/android_profile_after_1803.png)|
|![07](./media/androidCP_Setup01_before_1803.png)|![07](./media/androidCP_Setup01_after_1803.png)|


## Week of November 27, 2017

### New "Device Categories" step in guided setup for the Company Portal app for Windows 10 <!---1335292--->

If you've enabled [device group mapping](device-group-mapping.md), the Company Portal app for Windows 10 now walks your users through selecting a device category after enrolling their device.

![Device group mapping category](./media/w10_cp_category_device_setup_after_1711.png)

## Week of November 13, 2017

### Improvements to device setup workflow in the Company Portal for iOS in version 2.9.0 <!---1417174--->

We've improved the device setup workflow in the Company Portal app for iOS. The language is more user-friendly and we've combined screens where possible. We have also made the language more specific to your company by using your company name throughout the setup text.

> [!NOTE]
> We use the company name you have set in the Azure Portal in **Microsoft Intune** > **Mobile Apps** > **Company Portal branding** > **Company name**. If you have not set this value, we will use the tenant name set in **Azure Active Directory** > **Properties** > **Name**. If you have not set a company name in Company Portal branding and don’t want your tenant name to be displayed, we recommend that you set the company name in the Company Portal branding tab. If you don’t want this string to show in the header in Company Portal, you can deselect the checkbox to “Show company name next to logo.”

|Before|After|
|---|---|
|![01](./media/ios_cp_enroll_01_before_1711.png)|![01](./media/ios_cp_enroll_01_after_1711.png)|
|![02](./media/ios_cp_enroll_02_before_1711.png)|*Combined with previous step*|
|![03](./media/ios_cp_enroll_03_before_1711.png)|![03](./media/ios_cp_enroll_03_after_1711.png)|
|![04](./media/ios_cp_enroll_04_before_1711.png)|![04](./media/ios_cp_enroll_04_after_1711.png)|
|![05](./media/ios_cp_enroll_05_before_1711.png)|![05](./media/ios_cp_enroll_05_after_1711.png)|
|![06](./media/ios_cp_enroll_06_before_1711.png)|![06](./media/ios_cp_enroll_06_after_1711.png)|
|![07](./media/ios_cp_enroll_07_before_1711.png)|![07](./media/ios_cp_enroll_07_after_1711.png)|


## Week of November 6, 2017

### Updates to the Company Portal app for Windows 10 <!--1299474-->
The Settings page in the Company Portal app for Windows 10 has been updated to make the settings and intended user actions to be more consistent across all settings. It has also been updated to match the layout of other Windows apps.

|Before|After|
|---|---|
|![01](./media/w10-share-logs.png)|![02](./media/w10-share-logs-after-1711.png)|


### Search improvements to the Company Portal apps and website <!--1418189-->
The Company Portal apps now use searches across app categories, names, and descriptions. The results are sorted in decreasing order of relevance. These updates are also available on the [Company Portal website](https://portal.manage.microsoft.com).

We're still fine-tuning the way relevance is tracked, so please let us know how it's working using the "Feedback" link at the bottom of the Company Portal website.

## Week of October 16, 2017

### Search improvements to the Company Portal website <!--1331697-->
We're improving our app search capabilities, starting with the [Company Portal website](https://portal.manage.microsoft.com). Searches will now be performed on app categories in addition to the Name and Description fields. The results will be sorted, by default, in decreasing order of relevance. 

iOS users will also receive this change, as the Company Portal website is also used as part of the Company Portal app for iOS. The Company Portal apps for Android and Windows will receive similar updates in the coming months.

We're still fine-tuning the way relevance is tracked, so please let us know how it's working using the "Feedback" link at the bottom of the Company Portal website.


### iOS Company Portal displays large icons <!-- 1454593 -->
This release fixes a known issue with how the iOS Company Portal displays icons in the app tile. If you upload app icons of 120x120 pixels or larger, they now display in the [Company Portal website](https://portal.manage.microsoft.com) and the iOS Company Portal's apps pages at the full size of the app tile.


## Week of October 2, 2017

#### Improvements to device setup workflow in Company Portal <!--1490692-->
We've improved the device setup workflow in the Company Portal app for Android. The language is more user-friendly and specific to your company, and we've combined screens where possible. 

|Before|After|
|---|---|
|![01](./media/android_cp_enroll_01_post_1709.png)|![01](./media/android_cp_enroll_01_1709_new.png)|
|![01a](./media/android_cp_enroll_01_before_1710.png)| *Combined with previous step* |
|![02](./media/android_cp_enroll_02_before_1710.png)|![02](./media/android_cp_enroll_02_after_1710.png)|
|![03](./media/android_cp_enroll_03_before_1710.png)|![03](./media/android_cp_enroll_03_after_1710.png)|

Additional steps have been improved on Android for Work devices.

|Before|After|
|---|---|
|![04](./media/android_work_cp_enroll_01_before_1710.png)|![04](./media/android_work_cp_enroll_01_after_1710.png)|
|![05](./media/android_work_cp_enroll_02_before_1710.png)| *Combined with previous step* |
|![06](./media/android_work_cp_enroll_03_before_1710.png)|![06](./media/android_work_cp_enroll_03_after_1710.png)|
|![07](./media/android_work_cp_enroll_04_before_1710.png)|![07](./media/android_work_cp_enroll_04_after_1710.png)|
|![08](./media/android_work_cp_enroll_05_before_1710.png)| *Combined with previous step* |


We've also updated the conditional access email activation screen.

|Before|After|
|---|---|
|![06](./media/android_conditional_access_email_before_1710.png)|![06](./media/android_conditional_access_email_after_1710.png)

## Week of September 11, 2017

### Easier-to-understand phrasing for the Company Portal app for Android <!---1396349--->  

The enrollment process for the Company Portal app for Android has been simplified with new text to make it easier for end-users to enroll. If you have custom enrollment documentation, you will want to update it to reflect the new screens. You can find sample images below:

|Before|After|
|---|---|
|![01](./media/android_cp_enroll_01_before_1709.png)|![01](./media/android_cp_enroll_01_post_1709.png)|
|![02](./media/android_cp_enroll_02_before_1709.png)|![02](./media/android_cp_enroll_02_post_1709.png)|
|![03](./media/android_cp_enroll_03_before_1709.png)|![03](./media/android_cp_enroll_03_post_1709.png)|
|![04](./media/android_cp_enroll_04_before_1709.png)|![04](./media/android_cp_enroll_04_post_1709.png)|
|![05](./media/android_cp_enroll_05_before_1709.png)|![05](./media/android_cp_enroll_05_post_1709.png)|


## August 2017

### iOS 11 Mail app will support OAuth <!---1196951--->

Conditional access with Intune supports more secure authentication on iOS devices with OAuth. To support this, there will now be a different flow on the Company Portal app for iOS to allow for more secure authentication. When end users try to sign in to a new Exchange account in the Mail app, they will see a web view prompt. Upon enrollment in Intune, users will see a prompt to allow the native Mail app to access a certificate. Most end users will not see any more quarantined emails. Existing mail accounts will continue to use basic authentication protocol, so these users will still have quarantine emails delivered to them. This sign in experience for end users is similar to the one on Office mobile apps.

![Selecting account type in native mail app.](./media/ios-11-ca-email-after-1708-01.png)

![After selecting Exchange, iOS device prompt asks for email address and account name.](./media/ios-11-ca-email-after-1708-02.png)

![Provide email address and name for account.](./media/ios-11-ca-email-after-1708-03.png)

![Sent to external Microsoft login page.](./media/ios-11-ca-email-after-1708-04.png)

![Providing password on Microsoft page.](./media/ios-11-ca-email-after-1708-05.png)

![Microsoft prompts user to enroll device into management.](./media/ios-11-ca-email-after-1708-06.png)

![User is prompted to enroll from Company Portal website.](./media/ios-11-ca-email-after-1708-07.png)



### Intune Mobile Application Management (MAM) dialog boxes will have a modern interface <!-- 1199015 -->

Intune Mobile Application Management (MAM) dialog boxes will be updated to a modern look and feel. The dialog boxes will function in the same way as the previous style.

**Previous experience**

![old interface](./media/NewUI_Old_AttachFileHandler.jpg)

**Modern experience**

![modern interface](./media/NewUI_Modern_AttachFileHandler.jpg)


### Updates to the "Device Details" page on the Company Portal app for Windows 10 <!---1287448--->

The Company Portal app for Windows 10 is moving the __Category__ tag from below the title to a property on the __Device Details__ page.

![The Company Portal app for Windows' "Device Details" screen, which now shows the "Categories" field as a property rather than directly below the title of that screen.](./media/cp_win10_category_tag_move_after_1708.png)

## July 2017

### Apps details pages will display new information for Android devices <!--1287476-->

The apps details page of the Company Portal app for Android will now display the app categories that the IT admin has defined for that app.

![The new app details page](./media/cp_android_appdetails_after_1708.png)

### Improved sign in experience across Company Portal apps for all platforms <!--User Story 1132123-->

We are announcing a change that is coming in the next few months that will improve the sign-in experience for the Intune Company Portal apps for Android, iOS, and Windows. The new user experience will automatically appear across all platforms for the Company Portal app when Azure AD makes this change. In addition, users can now sign in to the Company Portal from another device with a generated, single-use code. This is especially useful in cases when users need to sign in without credentials.  

Below you can see the previous sign-in experience, the new sign-in experience with credentials, and the new sign-in experience from another device.

__Previous sign in experience__

![The Company Portal sign-in page, with an icon of a person in front of a graphical representation of a website. The "Sign in" button is Underneath. A link at the bottom leads to Microsoft Privacy and Cookies information.](./media/cp_ios_aad_signin_before_1704_001.png)

![After tapping Sign in, the user enters their credentials on this page, which asks for a user's email and password, along with offering ways to resolve password failures.](./media/cp_ios_aad_signin_before_1704_002.png)

![After providing their password, the Company Portal app signs in, noting this with a loading bar.](./media/cp_ios_aad_signin_before_1704_003.png)

__New sign in experience__

![The Company Portal sign in page, with an icon of a person in front of a graphical representation of a website. Underneath is the "Sign in" button. A link at the bottom leads to Microsoft Privacy and Cookies information.](./media/cp_ios_aad_signin_after_1704_001.png)

![The user is prompted to provide just their email address rather than their email and password on the same screen.](./media/cp_ios_aad_signin_after_1704_002.png)

![The user is prompted for their password after their email address has been accepted.](./media/cp_ios_aad_signin_after_1704_003.png)

![After going through the authentication process, the Company Portal app signs in, noting this with a loading bar.](./media/cp_ios_aad_signin_from_another_device_after_1704_007.png)

__New sign in experience when signing in from another device__

![The Company Portal sign-in page, with an icon of a person in front of a graphical representation of a website. Underneath is the "Sign in" button. A link at the bottom leads to Microsoft Privacy and Cookies information.](./media/cp_ios_aad_signin_from_another_device_after_1704_001.png)

Tap the __Sign-in from another device__ link.

![Instructions are provided to go to the aka.ms/devicelogin page with a unique passcode from your work computer, then to use the code to sign in.](./media/cp_ios_aad_signin_from_another_device_after_1704_003.png)

Launch a browser and go to [https://aka.ms/devicelogin](https://aka.ms/devicelogin).

![An image of the user's browser on their work computer rather than their Company Portal app. The "Device login" page displayed prompts the user for the code they received in the Company Portal app.](./media/cp_ios_aad_signin_from_another_device_after_1704_004.png)

Enter the code you saw in the Company Portal app. When you select __Continue__, you will be able to authenticate in the using any method that is supported by your company, such as a smartcard.

![The user has input their unique code into the field, and the "Device login" site has asked for confirmation that the Intune Company Portal was the correct app to receive authorization to sign in.](./media/cp_ios_aad_signin_from_another_device_after_1704_005.png)

![A confirmation page that states that the user has now signed into the Company Portal app on their device, and that this page can be closed.](./media/cp_ios_aad_signin_from_another_device_after_1704_006.png)

The Company Portal app will begin signing in.

![After going through the authentication process, the Company Portal app signs in, noting this with a loading bar.](./media/cp_ios_aad_signin_from_another_device_after_1704_007.png)

## June 2017

### Company Portal app for Android now has a new end-user experience for App Protection Policies
Based on customer feedback, we've modified the Company Portal app for Android to show an **Access Company Content** button. The intent is to prevent end users from unnecessarily going through the enrollment process when they only need to access apps that support App Protection Policies, a feature of Intune mobile application management.

The user will tap on the **Access Company Content** button instead of beginning to enroll the device.

![An image of the Android Company Portal app, which shows in large text "Access Company Content" in the middle rather than offering immediate enrollment options as is the standard case](./media/and_access_company_content_after_1706.png)

The user then is taken to the Company Portal website to authorize the app for use on their device, where the Company Portal website verifies their credentials.

![An image of the Company Portal website, confirming the sign-in.](./media/and_iwp_sign_in_auth_page_after_1706.png)

The device can still be enrolled into full management by tapping on the **action** menu.

![An image of the Company Portal app for Android, showing the menu from the top right corner of the screen with an option to still enroll the device.](./media/and_sign_in_menu_after_app_protection_policy_enrolled_after_1706.png)

### Improvements to app syncing with Windows 10 Creators Update <!--676505-->

The Company Portal app for Windows 10 will now automatically initiate a sync for app install requests for devices with Windows 10 Creators Update (version 1703). This will reduce the issue of app installs stalling during the "Pending Sync" state. In addition, users will be able to manually initiate a sync from within the app.

![An image of the Windows 10 Company Portal app, where the download of Microsoft Word is in a pending state from the Company Portal's app store.](./media/w10_download_pending_after_1706.png)

![An image of the Windows 10 Company Portal app, with the new automatic syncing state showing with a status message indicating that the device is syncing and attempting to download the app.](./media/w10_download_pending_syncing_after_1706.png)

### New guided experience for Windows 10 Company Portal <!---1058938--->
The Company Portal app for Windows 10 will include a guided Intune walkthrough experience for devices that have not been identified or enrolled. The new experience provides step-by-step instructions that guide the user through registering into Azure Active Directory (required for Conditional Access features) and MDM enrollment (required for device management features). The guided experience will be accessible from the Company Portal home page. Users can continue to use the app if they do not complete registration and enrollment, but will experience limited functionality.

This update is only visible on devices running Windows 10 Anniversary Update (build 1607) or higher.

![An image of the Windows 10 Company Portal app landing page, with a status message in the middle in the "devices" list which is telling a user that the device they're on hasn't been set up for corporate use yet, and that the user should select the message to begin setup.](./media/win10_guided_enroll_select_setup_after_1706.png)

![An image of the Windows 10 Company Portal app setup page, which is warning the user that they need to add a corporate account to this device, then they can enroll it into management.](./media/win10_guided_enroll_we_help_setup_after_1706.png)

![An image of the Windows 10 Company Portal app adds corporate account to this device page, which is telling the user that they will need to go to the Settings app and select "Connect" to complete enrollment. After they do this, the screen tells them that they will need to return to the Company Portal app to complete enrolling.](./media/win10_guided_enroll_leaving_for_iwp_after_1706.png)

![An image of the Windows 10 Company Portal app enroll into management screen, which shows a completed status message saying that the user's device is now enrolled and that they should tap the 'next' button to continue.](./media/win10_guided_enroll_youre_now_enrolled_after_1706.png)

![An image of the Windows 10 Company Portal app completion screen, letting the user know that they're all set, and that the device is enrolled with a corporate account properly added to it.](./media/win10_guided_enroll_youre_all_set_after_1706.png)

### New menu action to easily remove Company Portal <!--1164569-->
Based on user feedback, the Company Portal app for Android has added a new menu action to initiate the removal of Company Portal from your device. This action removes the device from Intune management so that the app can be removed from the device by the user.

![An image of the Android Company Portal app, with the action menu opened in the top right corner. The new "remove company portal" option is available as the third option, underneath "my profile" and "settings", and above "terms and conditions", "help and feedback", and "about".](./media/android_remove_cp_menu_action_after_1705.png)

![An image of the confirmation dialog, that is available after selecting the new "remove company portal" option from the action menu. The dialog informs the user that "by removing company portal, your device will no longer be managed by your IT admin and may remove access to company data, company apps, and company email." It then asks the user to confirm that they want to remove the Company Portal app by selecting "Yes".](./media/android_remove_cp_menu_confirmation_after_1705.png)

### Improvements to the app tiles in the Company Portal app for iOS <!--1230777-->
We updated the design of the app tiles on the homepage to reflect the branding color you set for the Company Portal.

**Before**

![An image of the Company Portal app for iOS from before the update, which showed preset filler images for "All apps", "Featured apps," and "categories."](./media/cp_ios_homepage_before_1705.png)

**After**

![An image of the Company Portal app for iOS after the update, which now reflects the ability to select whatever colors are relevant for your organization.](./media/cp_ios_homepage_after_1705.png)

### Account picker now available for the Company Portal app for iOS
If users have used their work or school account to sign in to other Microsoft apps on their iOS device, then they may see our new account picker when signing into the Company Portal for the first time.

![An image of the account selector, which shows a test user "Robin Swanson" choosing between one of their two email addresses. There is a button underneath the two addresses that allows the user to sign in with a different account.](./media/cp_ios_multi-account-selector-after-1705.png)

## April 2017

### New icons for the Managed Browser and the Company Portal <!--918433, 918431-->

The Managed Browser is receiving updated icons for both the Android and iOS versions of the app. The new icon will contain the updated Intune badge to make it more consistent with other apps in Enterprise Mobility + Security (EM+S).

<html>
<body>
   <table id="wrapper">
      <tr>
         <td>
            <img src="/intune/media/cp_manbro_before_042017.png" alt="The previous version of the Managed Browser app icon." width="200" height="366" align="center">
          </td>
          <td>
             <img src="/intune/media/cp_manbro_after_042017.png" alt="The updated version of the Managed Browser app icon." width="200" height="366" align="center">
           </td>
      </tr>
   </table>
</body>
</html>

The Company Portal is also receiving updated icons for the Android, iOS, and Windows versions of the app to improve consistency with other apps in EM+S. These icons will be gradually released across platforms from April to late May.

### Sign in progress indicator in Android Company Portal <!--953374-->

An update to the Android Company Portal app shows a sign-in progress indicator when the user launches or resumes the app. The indicator progresses through new statuses, beginning with "Connecting...", then "Signing in...", then "Checking for security requirements..." before allowing the user to access the app.

<html>
<body>
   <table id="wrapper">
      <tr>
         <td>
            <img src="/intune/media/cp_android_connecting_042017.png" alt="The Company Portal app for Android sign-in screen that shows a partially filled loading bar with the phrase 'Connecting' underneath it." width="200" height="366" align="center">
          </td>
          <td>
             <img src="/intune/media/cp_android_signing_in_042017.png" alt="The Company Portal app for Android sign-in screen that shows a partially filled loading bar with the phrase 'Signing in' underneath it." width="200" height="366" align="center">
           </td>
           <td>
              <img src="/intune/media/cp_android_checking_security_reqs_042017.png" alt="The Company Portal app for Android sign-in screen that shows a partially filled loading bar with the phrase 'Checking for security requirements' underneath it." width="200" height="366" align="center">
           </td>
      </tr>
   </table>
</body>
</html>

### Improved app install status for the Windows 10 Company Portal app <!--676495-->
The Windows 10 Company Portal app now provides an install progress bar on the app details page. This is supported for modern apps on devices running the Windows 10 Anniversary Update and up.

__Before__
  ![An image of the previous version of the loading screen, where the status simply said 'installing.'](./media/cp_win10_install_status_before_1704.png)

__After__
  ![An image of the updated version of the loading screen, which now shows an install progress bar.](./media/cp_win10_install_status_after_1704.png)

## February 2017

### New user experience for the Company Portal app for Android <!--621622, announced 1702-->
Beginning in March, the Company Portal app for Android will follow [material design guidelines](https://material.io/guidelines/material-design/introduction.html) to create a more modern look and feel. This improved user experience includes:

* __Colors__: tab headers can be colored according to your custom color palette.

![On the left, an image of the Company Portal app for Android before the update. On the right, an image of the Company Portal app for Android after the update. Both images show the Devices tab as the selected tab from the three available tabs of Apps, Devices, and Contact IT.](./media/CP_Android_DevicesTab_BeforeAfter.png)

* __Interface__: __Featured Apps__ and __All Apps__ buttons have been updated in the __Apps__ tab. The __Search__ button is now a floating action button.

![On the left, an image of the Company Portal app for Android before the update. On the right, an image of the Company Portal app for Android after the update. Both images show the Apps tab as the selected tab from the three available tabs of Apps, Devices, and Contact IT.](./media/CP_Android_AppsTab_BeforeAfter.png)

* __Navigation__: All Apps shows a tabbed view of __Featured__, __All__ and __Categories__ for easier navigation. __Contact IT__ has been streamlined for improved readability.

<html>
<body>
   <table id="wrapper">
      <tr>
         <td>
            <img src="/intune/media/cp_android_contactit_after.png" alt="The Company Portal app for Android displaying an updated version of the Contact IT tab. The tab shows available contact information for IT, including phone number, email address, IT website, and IT contact information." width="200" height="366" align="center">
          </td>
      </tr>
   </table>
</body>
</html>

## January 2017

### Modernizing the Company Portal website <!--753980, announced 1701-->
Beginning in February, the Company Portal website will support apps that are targeted to users who do not have managed devices. The website will align with other Microsoft products and services by using a new contrasting color scheme, dynamic illustrations, and a "hamburger menu," ![Small image of the hamburger menu that is now added at the top left corner of the Company Portal website](./media/CP_hamburger_menu.png) which will contain helpdesk contact details and information on existing managed devices. The landing page will be rearranged to emphasize apps that are available to users, with carousels for Featured and Recently Updated apps.

![On the left, an image of the current version of the Company Portal website with its previous version of Apps, My Devices, and Featured and Categories views. On the right, an image of the updated version of the Company Portal website with a refreshed app carousel, list of Recently Published apps, and updated Categories view.](./media/CP_Website_BeforeAfter_Feb2016.png)

## Coming soon in the UI
These are the plans for ways we will be improving the user experience by updating our user interface.

> [!Note]
> Please note that the images below may be previews, and the announced product may differ from the presented versions.

### <a name="ui-iwp"></a>New user experience update for the Company Portal website <!--2000968-->

We’re introducing a new Company Portal website experience, with UI updates, streamlined workflows and accessibility improvements. This will include customer-driven enhancements like app sharing and improved overall performance to bring you a more user-friendly experience.

We’ve added some new features, based on feedback from customers like you, that will significantly improve existing functionality and usability:

-	UI improvements throughout the website
-	Ability to share direct links to apps
- Improved performance for large app catalogs

You don't need to take any action to prepare for this change. We’ll let you know when the updated Company Portal website becomes available for you. However, you may eventually need to update end-user docs with updated screenshots. Note that you may also need to update documentation for the Company Portal app on iOS, as the website powers the **Apps** section of the iOS app.

|Updated|Previous|
|---|---|
|![The updated device page shows the device cleanly aligned above device information, no longer popping up above the full list.](./media/iwp-device-after-1803.png)|![The previous version of the device page.](./media/iwp-device-before-1803.png)|
|![The updated app install page shows the app cleanly above a description and various install information, including publish date, version, and type of app.](./media/iwp-app-install-after-1803.png)|![The previous version of the app install page.](./media/iwp-app-install-before-1803.png)|

### UI updates to the Company Portal website <!--1313244 part 2-->

__Updates to Featured Apps__
We've added a dedicated page to the site where users can browse apps that you've chosen to feature, and made some UI tweaks to the Featured section on the homepage.

![The colorful tiles that show the apps. They are large squares of color underneath each app, where the color is pulled from the primary color within the app logo. The "Featured Apps" section appears across the top of the Company Portal app.](./media/cp_win10_colorful_tiles_after_1708.png)



### See also
* [Microsoft Intune Blog](http://go.microsoft.com/fwlink/?LinkID=273882)
* [Cloud Platform roadmap](https://www.microsoft.com/cloud-platform/roadmap)
* [What's new in Intune](https://docs.microsoft.com/intune/whats-new)
