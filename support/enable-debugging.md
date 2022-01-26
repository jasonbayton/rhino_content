---
title: Enable USB debugging & collect a bug report
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-09-29'
updated: ''
url: "/support/enable-debugging"
type: doc
published: 'true'
parent: Support
topic: Advanced
order: '0'
appliesTo:
- C10
- T8
- K27p
- M10p
- T5se
---

Enabling developer options allow users to perform various debugging tasks, including viewing Logs, taking bug reports, etc. It can be very useful in various scenarios and aids tremendously in troubleshooting issues.

<div class="callout callout-warning">
<div class="callout-heading">Enterprise management heads-up</div>
USB debugging may be prevented by policy for managed devices. Please consult your administrator/IT team for guidance on enabling developer options described below.
</div>

## Enabling developer settings  

<div class="numbered-instructions" markdown="1">
1. Open Settings
  1. Either swipe up from the home screen to display the app drawer, and select settings, or
  2. Swipe down from the notification area and tap the settings icon present in the notification panel.
2. Tap About device
3. Swipe down to Build number
4. Tap 7 times on Build number
5. Developer mode will be enabled
</div>

## Enabling USB debugging

Prerequisites – [PC with ADB configured](/support/set-up-adb)

After enabling developer mode,

<div class="numbered-instructions" markdown="1">
1. Tap back into Settings
2. Tap System
3. Tap Advanced
4. Tap developer options
5. Swipe to USB debugging, and toggle it on
</div>

It'll now be possible to plug your Rhino device into a computer and undertake various debugging tasks. When first plugging in, the device will prompt for authorisation. Allow this.

## Take a bug report

With developer options enabled:

<div class="numbered-instructions" markdown="1">
1. Open Settings
  1. Either swipe up from the home screen to display the app drawer, and select settings, or
  2. Swipe down from the notification area and tap the settings icon present in the notification panel.
2. Tap System
3. Tap Advanced
4. Tap Developer options
5. Swipe until bug report appears in view, and tap **Take a bug report**
</div>

The bug report will become available via a notification within a few moments. From there, share it to a preferred application or download it to a connected computer.

Alternatively, from ADB run `adb bugreport E:\Reports\MyBugReports` (choose an appropriate location) to save a bug report directly to your computer without interacting with the device directly.

More details, via [Google](https://developer.android.com/studio/debug/bug-report).

## Capture live logcat

With developer options enabled, if requested by the Rhino team:

<div class="numbered-instructions" markdown="1">
1. Connect the device to PC via USB
2. Run the command `adb logcat \> path/filename.txt`
  1. NB: Change `path/filename.txt` to a legitimate path on your computer
3. Replicate the issue(s), one per logcat command issuance and note down the timestamp to the second
  1. If the timestamp isn't provided _to the second_ (ie 12:13:34) with the logcat, the Rhino team will request a new logcat with timestamp.
4. Hit Ctrl + C to stop logging to file
  1. That'll be CMD + C on Mac
5. Fetch the log file from the saved location, and send it to the Rhino team
</div>
