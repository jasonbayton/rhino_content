---
title: Boot a RHINO device into recovery
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-10-02'
updated: ''
url: "/support/boot-to-recovery"
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

Android's recovery mode is a device-level tool built into most Android devices on the market. All RHINO devices can access recovery mode using the key combination `Power` + `Volume up` when the unit is powered off. Recovery can be used to reset a device back to factory settings, test hardware functions, and more.  

## Hardware key combination

<div class="numbered-instructions" markdown="1">
1. Turn off the RHINO device
2. Hold `Power` + `volume up` together until the device vibrates.
3. The device will boot to a bootloader menu, use `volume up` to move between the options until **Recovery** is selected, then press `volume down` to confirm the selection.
4. The device will boot into recovery mode, and first shows a picture of the Android robot showing <i class="fas fa-exclamation-triangle text-warning"></i>. Press `power`, then while holding, press `volume up` in quick succession. This may take a few attempts as it can be tricky to get the timing just right.
5. The recovery menu will appear.
</div>

NB: For step 4, holding the buttons down for too long will cause the device to reboot. The button combination need only be pressed for a moment.

## ADB

<div class="numbered-instructions" markdown="1">
1. Connect a powered-on RHINO device to your PC
2. Open the commandline utility
3. Run `adb devices` to confirm the RHINO device is present and authorised
4. Run `adb reboot recovery`
5. Follow steps 4 and 5 above
</div>

Notes:

1. The RHINO device must have [debugging](/support/enable-debugging) enabled, and the PC must already have [ADB set up](/support/set-up-adb) for this to work.
2. The K27p and DS have no physical volume keys for hardware key combination recovery mode.
3. The M10p requires the use of two SIM pins to depress the hidden power and volume buttons.
