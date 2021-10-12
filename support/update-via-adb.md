For offline/staging purposes, it is possible to update your Rhino device via the Android Debug Bridge (ADB) using a previously-downloaded OTA file (we provide these under [releases](/security/software-releases)). Updating your Rhino device via ADB is safe and fully supported by the Rhino team, however it is also somewhat technical. For a simpler method, you may prefer to try [updating via SDCard](/support/update-via-sdcard). Happy to continue? Here's how to do it:

## Prerequisites-  

- A PC with [ADB configured](/support/set-up-adb)
- A Rhino device with [USB debugging mode enabled](/support/enable-debugging)

## Update via ADB

<div class="numbered-instructions" markdown="1">
1. Download the appropriate OS package (zip file) from [releases](/security/software-releases) to your local PC. Keep note of the folder to which the update file downloads.
2. Ensure ADB debugging is enabled on your Rhino device and connect it to a PC
3. Reboot the device into recovery by opening the commandline utility on your PC and entering adb command `adb reboot recovery`
4. On the maintenance robot screen, press power and with it held, press volume up (there's a knack to this, it may take a couple of attempts)
5. Once the recovery menu appears, use the volume keys to select “update from ADB”, and power to confirm
6. The device will show it is ready to receive an update over ADB
7. On the PC, type `adb devices`, you should see the device listed
  1. If the device is not listed, check the device is properly connected
  2. If the device shows unauthorised, kill the ADB server on your PC and type `adb devices` to restart it
8. Send the update with `adb sideload update.zip`
  1. Tip: `CD` to the directory in which you downloaded the OTA file. It will not be named "update.zip" by default, so replace the text above with the actual file name, or rename the file to update.zip to use the command above unmodified
9. The device will show update progress and completion confirmation once the update has been fully applied
  1. If the update fails to apply, record the error message, grab a photo of the screen, and [contact support](/support/escalate) if it fails more than twice
10. Use the volume keys to select reboot, and power to confirm. The Rhino device will reboot into the updated Android build
</div>

Be aware when attempting to sideload multiple OTA files, a reboot between will be necessary to allow the system time to apply the update in an online state and update core identifiers such as build fingerprint.
