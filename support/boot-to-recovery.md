Android's recovery mode is a device-level tool built into most Android devices today. All Rhino devices can access recovery mode using the key combination `Power` + `Volume up` when the unit is powered off. Recovery can be used to reset a device back to factory settings, test hardware functions, and more.  

## Hardware key combination

<div class="numbered-instructions" markdown="1">
1. Turn off the Rhino device
2. Hold `Power` + `volume up` together until the device vibrates.
3. The device will boot to a bootloader menu, use `volume up` to move between the options until **Recovery** is selected, then press `volume down` to confirm the selection.
4. The device will boot into recovery mode, and first shows a picture of the Android robot showing <i class="fas fa-exclamation-triangle text-warning"></i>. Press `power`, then while holding, press `volume up` in quick succession. This may take a few attempts as it can be tricky to get the timing just right.
5. The recovery menu will appear.
</div>

## ADB

<div class="numbered-instructions" markdown="1">
1. Connect a powered-on Rhino device to your PC
2. Open the commandline utility
3. Run `adb devices` to confirm the Rhino device is present and authorised
4. Run `adb reboot recovery`
5. Follow steps 4 and 5 above

NB: The Rhino device must have [debugging](/support/enable-debugging) enabled, and the PC must already have [ADB set up](/support/set-up-adb) for this to work.
