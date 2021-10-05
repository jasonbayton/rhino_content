Enabling developer option allows user to perform various debugging tasks like viewing logcat, taking bug reports, etc. It can be very useful in various scenarios and aids tremendously in troubleshooting issues.

<div class="callout callout-warning">
<div class="callout-heading">Enterprise management heads-up</div>
USB debugging may be prevented by policy for managed devices. Please consult your administrator/IT team for guidance on enabling developer options described below.
</div>

## Enabling developer settings  

Prerequisites – [PC with ADB configured](/support/set-up-adb)

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
