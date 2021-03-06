---
title: "What USB drivers do I need to debug Android on Windows?"
ms.topic: troubleshooting
ms.prod: xamarin
ms.assetid: 36EC7341-A2A4-409C-BD4F-330BAC505123
ms.technology: xamarin-android
author: mgmclemore
ms.author: mamcle
ms.date: 05/30/2018
---

# What USB drivers do I need to debug Android on Windows?

## Finding USB Drivers

To debug on an Android device when developing in Windows; you need to
install a compatible USB driver. The Android SDK Manager includes the
"Google USB Driver" by default, which adds support for Nexus devices as
described here:
[http://developer.android.com/sdk/win-usb.html](http://developer.android.com/sdk/win-usb.html)

Other devices require USB drivers specifically published by the device
manufacturer. Some links for the most common manufacturers are included
in this guide:
[http://developer.android.com/tools/extras/oem-usb.html](http://developer.android.com/tools/extras/oem-usb.html)

## Alternatives

Depending on the manfacturer, it can be difficult to track down the
exact USB driver needed. Some alternatives for testing Android apps
developed in Windows including using an Android emulator or using
external testing services. Some of these include:

- [App Center Test](https://docs.microsoft.com/appcenter/test-cloud/) - Cloud Testing services run on hundreds of real Android devices.

- [Visual Studio Emulator for Android](https://www.visualstudio.com/en-us/features/msft-android-emulator-vs.aspx)

- [Debugging with the Google Android Emulator](~/android/deploy-test/debugging/android-sdk-emulator/index.md)

