---
title: Set up ADB for debugging
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-10-19'
updated: ''
url: "/support/set-up-adb"
type: doc
published: 'true'
parent: Support
topic: Advanced
order: '0'
appliesTo:
- T5se
- T8
- C10
- M10p
- K27p
---

ADB, or Android Debug Bridge, is a command-line utility included with Google's Android SDK. ADB can control and interact with your Rhino device over USB or network from a computer, and allows below operations:

- Install, copy, and delete files.
- Install a program on a device.
- Record a video or take a screenshot of the phone.
- Debug a device in case of its malfunction.
- Examine logs on the phone.
- Upgrade the firmware of the programs and system elements.
- Get full access to information about OS and a device

Steps to configure ADB on a host **Windows** computer:

<div class="numbered-instructions" markdown="1">
1. Go to Google's SDK platform tools download [page](https://developer.android.com/studio/releases/platform-tools)
2. Download the platform tools zip file for the Windows OS
3. Extract the zip file to a preferred folder
4. Head to **Control Panel** > **System and Security** > **System** > **Advanced system settings**
5. Open **Environment variables**
6. In **System variables**, select *Path* and click Edit
7. Input the filesystem path to the unzipped platform-tools folder
8. Once input, close out of settings (make sure these are saved first) and connect an android device with [USB debugging enabled](/support/enable-debugging)
9. Open command prompt and type "adb devices"
10. Command terminal will display the list of devices connected along with the serial number of the device(s) connected
</div>
