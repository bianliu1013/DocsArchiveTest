---
# required metadata

title: Enroll your macOS device in Intune | Microsoft Docs
description: Describes how to enroll a macOS device in Intune
keywords: Mac OS X, macOS, OS X
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 02/23/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 58eb0e7a-1321-4c66-a281-88fb01e72c1csearchScope: - User help

# optional metadata

ROBOTS:  
#audience:
#ms.devlang:
ms.reviewer: jieyang
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-enduser

---

# Enroll your macOS device in Intune

Getting access to your organization’s apps, data, and resources makes it possible for you to do your job. If you're using a macOS device at work, this means installing a __Management Profile__. This is simply a file set up by your IT admin that loads settings and access information onto your Mac. Want to know more? Find out [what happens when you install the Company Portal app and enroll your device in Intune](what-happens-if-you-install-the-company-portal-app-and-enroll-your-device-in-intune-ios.md)

  > [!NOTE]
  > If you're actually trying to enroll an iOS device, such as an iPhone or iPad, [try these instructions instead](enroll-your-device-in-intune-ios.md).

1. On your __Dock__, find __Safari__ and open a new window, then open the [Company Portal website](http://portal.manage.microsoft.com).
2. Log into the Company Portal website with your work or school account.

  [!INCLUDE[wit_nextref](includes/end-user-password-guidance.md)]

3. When you log in, you will see any available __Home__, __Apps__, and __Categories__ tabs. This page will show whatever apps are available for you to install. If you do not have any devices enrolled yet, you'll see a notice that says **We can't show you any apps.** You can proceed by selecting __My Devices__.

 ![A screenshot of the landing page for the web portal with the web portal showing that no apps can be installed yet, with a My Devices button underneath.](./media/macOS_enroll_001_landing_page.png)

4. On the __My Devices__ page, you will either see a list of enrolled devices or simply a banner. This depends on if you already have a device enrolled, macOS or otherwise. To enroll a device that is not listed, select the banner that says __If your device is listed, tap here to identify it. You can also tap here to enroll your device if it is not listed__.

  ![A screenshot of the My Device page, with a couple of unidentified devices above the banner prompt to enroll unlisted devices or identify unidentified ones.](./media/macOS_enroll_002_tap_here_banner.png)

5. A popup window will appear with a brief explanation of why you are going to __Identify or enroll this device__. Review this, then click __Enroll__ to proceed.

 ![Identify or Enroll this Device macOS](./media/macOS_enroll_003_IDenroll_popup.png)

6. A second popup window will appear with a brief explanation of what will happen when you __Enroll this device__. Review this, then click __Install__ to proceed.

 ![Enroll this device macOS](./media/macOS_enroll_004_enroll_popup.png)

  > [!NOTE]
  > Intune needs access to your computer to make sure that your device is secure enough to access your organization's resources. Find out [what happens when you enroll your device in Intune](what-happens-if-you-install-the-Company-Portal-app-and-enroll-your-device-in-intune-ios.md).

7. __System Preferences__ will open, and ask you if you want to __Install "Management Profile"?__ Click __Install__ to proceed, or get more details by clicking __Show Profile__.

 ![Install Management Profile](./media/macOS_enroll_005_sysprefs_mgmt_profile.png)

8. A macOS popup window will appear. Confirm that you want to make changes by providing your computer's __User Name__ and __Password__, then clicking __OK__. This will install the management profile onto your Mac.

 ![macOS Profile Install Popup](./media/macOS_enroll_006_sysprefs_admin_login.png)

9. You may see some additional messages from your Mac with more details about the profile, or whether you're sure that you want to __Install__. Click __Continue__ and __Install__ through these to proceed. Once the installation finishes, you will be able to view your newly-installed __Management Profile__ in the list of __Device Profiles__.

 ![macOS Profile Installed](./media/macOS_enroll_007_sysprefs_installed_profile.png)

Still need help? Check in with your IT administrator. You can find their contact information on the [Company Portal website](http://portal.manage.microsoft.com).
