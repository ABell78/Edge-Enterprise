---
title: "Frequently asked questions (FAQ) about Microsoft Edge in the enterprise"
ms.author: collw
author: dan-wesley
manager: seanlynd
ms.date: 08/30/2022
audience: ITPro
ms.topic: conceptual
ms.prod: microsoft-edge
ms.localizationpriority: medium
ms.collection: M365-modern-desktop
description: "Frequently asked questions (FAQ) about Microsoft Edge in the enterprise"
--- 


# Microsoft Edge frequently asked questions

This article contains frequently asked questions (FAQ) about Microsoft Edge in the enterprise.

> [!NOTE]
> This article applies to Microsoft Edge version 77 or later.

## How do I know which version of Microsoft Edge I have?

Select the ellipses icon (**...**) in the upper-right corner of Microsoft Edge, and then select **Settings**. Select **About Microsoft Edge** to see your version of Microsoft Edge.

## What about Internet Explorer 11?

>[!Note]
> The Internet Explorer 11 desktop application has [retired and is out of support as of June 15, 2022](https://aka.ms/IEJune15Blog) for certain versions of Windows 10.  
>
> - You can still access older, legacy sites that require Internet Explorer with Internet Explorer mode in Microsoft Edge. [Learn how >](https://aka.ms/IEmodewebsite)
> - The Internet Explorer 11 desktop application will progressively redirect to the faster, more secure Microsoft Edge browser, and will ultimately be disabled via Windows Update. [Disable IE today>](/deployedge/edge-ie-disable-ie11)  

## Does Microsoft Edge support ActiveX controls or Browser Helper Objects like Silverlight or Java?

No. Microsoft Edge doesn't support ActiveX controls or Browser Help Objects (BHOs) like Silverlight or Java. However, if you're running web apps that use ActiveX controls, BHOs, or legacy document modes on Internet Explorer 11, you can configure them to run in IE mode on  Microsoft Edge. For more information, see [Configure IE mode on Microsoft Edge](./edge-ie-mode.md).

## Will favorites be ported over from the current version of Microsoft Edge or will I have to re-add them?

Microsoft Edge supports import from existing installs of Microsoft Edge, Chrome, Internet Explorer, and Firefox (on Win10). The following settings are supported for importing: Bookmarks, History, Passwords, and Autofill (payments, addresses, and generic forms). You can choose to import either from the First-run Experience or from browser settings.

## What's the difference between the Stable, Beta, Dev, and Canary channels/builds?

The Stable channel of Microsoft Edge is the most stable channel we offer with enterprise-focused features ready for you to [pilot and evaluate](https://aka.ms/EdgeEnterprise) across your organization. The Beta channel allows you to validate the next Stable release with a representative set of users. The Stable and Beta channels are updated approximately every four weeks. The Dev and Canary channels continue to update weekly and daily, respectively. Offline installers (MSIs and PKG files) are available only for Stable, Beta, and Dev channels. For more information, see [Overview of Microsoft Edge channels](./microsoft-edge-channels.md).

## What kind of extension support do I have with Microsoft Edge?

Microsoft Edge supports extensions from [Microsoft Edge Insider Addons](https://go.microsoft.com/fwlink/?linkid=2081222) and the [Chrome Web Store](https://go.microsoft.com/fwlink/?linkid=2072338).

## Do you support Mobile Device Management (MDM) and Microsoft Intune?

Yes. Configuring Microsoft Edge on Windows 10 using Microsoft Intune and Mobile Device Management (MDM) is now supported. For more information, see [Configure Microsoft Edge using Microsoft Intune](./configure-edge-with-intune.md) and [Configure Microsoft Edge using Mobile Device Management](./configure-edge-with-mdm.md).

## Does Windows Server Update Services (WSUS) support the initial deployment of Microsoft Edge?

Yes. There are packages in the [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Search.aspx?q=the%20new%20microsoft%20edge%20for%20windows) that can be used for the initial deployment of Microsoft Edge via WSUS. After initial deployment, automatic updates are configured by default. For more information, see [Update in WSUS for the new Microsoft Edge for Windows 10, version 1809, 1903, 1909, and 2004: October 29, 2020](https://support.microsoft.com/help/4584642/update-in-wsus-for-the-new-microsoft-edge).

 Manual updates can be done through a configuration management tool, like [ConfigMgr](/configmgr/apps/deploy-use/deploy-edge?bc=%2fDeployEdge%2fbreadcrumb%2ftoc.json&toc=%2fDeployEdge%2ftoc.json).

## Are Initial Preferences supported?

Yes. For more information, see [Configure Microsoft Edge using Initial Preferences settings for the first run](./initial-preferences-support-on-microsoft-edge-browser.md)

## See also

- [Microsoft Edge documentation landing page](./index.yml)
- [Microsoft Edge Enterprise landing page](https://aka.ms/EdgeEnterprise)
  
