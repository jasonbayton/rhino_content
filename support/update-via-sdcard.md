For offline/staging purposes, it is possible to update your Rhino device via an SD card using a previously-downloaded OTA file (we provide these under [releases](/security/releases)). Updating your Rhino device via SD card is safe and fully supported by the Rhino team, however it is also reliant on having an SD card to hand. For a more technical method without this prerequisite, you may prefer to try [updating via ADB](/support/update-via-adb). Happy to continue? Here's how to do it:

## Prerequisites

- An SDCard
- A Rhino device with an SDCard slot
- A SIM pin, as the SDCard slot is typically alongside the SIM slot

## Update via ADB

<div class="numbered-instructions" markdown="1">
1. Download the appropriate OS package (zip file) from [releases](/security/releases) to your local PC. Keep note of the folder to which the update file downloads
2. Copy the zip file from the PC to the root of the SD card. You may do this either by plugging the SDCard into the PC directly, or plugging the Rhino device into the PC with data transfer enabled
3. Ensure the Rhino device has at least 50% battery
4. Reboot the device into [recovery](/support/reboot-to-recovery).
5. On the maintenance robot screen, press power and with it held, press volume up (there's a knack to this, it may take a couple of attempts)
6. Once the recovery menu appears, use the volume keys to select “update from SD card”, and power to confirm
7. Use the volume keys to select the file located on the SD card, press power to confirm
8. The update process will begin
9. The device will show update progress and completion confirmation once the update has been fully applied
  1. If the update fails to apply, record the error message, grab a photo of the screen, and [contact support](/support/escalate) if it fails more than twice.
10. Use the volume keys to select reboot, and power to confirm. The Rhino device will reboot into the updated Android build
</div>
