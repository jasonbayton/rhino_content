---
title: Factory reset your RHINO device
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-01-01'
updated: ''
url: "/support/factory-reset"
type: doc
published: 'true'
parent: Support
topic: General
order: '0'
appliesTo:
- C10
- T8
- M10p
- T5se
- K27p
- PACE A1
---

Factory resetting your RHINO device is recommended before parting ways with it to ensure any and all personal or private information has been removed. Likewise, resetting a device may resolve issues where other attempted solutions have not prevailed. Depending on the state of the device, resetting it to a factory-like state can be achieved in one of two ways.

## **With** access to the Android OS

<div class="numbered-instructions" markdown="1">
1. Open **Settings**
  1. Either swipe up from the home screen to display the app drawer, and select settings, or
  2. Swipe down from the notification area and tap the settings icon present in the notification panel.
2. Tap **System**
3. Tap **Reset options**
4. Tap **Erase all data (factory reset)**
5. Tap **Erase all data** again
6. The RHINO device will begin the irreversible process of resetting the device back to factory settings, and will become available to be set back up again within several minutes.
</div>

Note - the device must have at least 20% charge to reset in this way.

## With **no** access to the Android OS

Assuming the device will not boot, or the end-user is locked out of the device because of a passcode or enterprise management issue, it may be possible to reset through RHINO recovery mode.

<div class="callout callout-danger" markdown="1">
<div class="callout-heading">Factory Reset Protection (FRP)</div>
Resetting a RHINO device in this way may initiate FRP if this hasn't been disabled through enterprise management. If the device has both a Google account & passcode added, FRP may be present and will require the device passcode and/or Google account credentials on first boot. **Without these details the device must be sent to the [RHINO team](/support/escalate) for repair**.
</div>

<div class="numbered-instructions" markdown="1">
1. Follow steps outlined [here](/support/boot-to-recovery) to boot the RHINO device into recovery mode. Once the recovery menu is shown, use the volume keys to move up and down through the menu, pressing power to confirm.
2. Select **Wipe data/factory reset**
3. Select and confirm **Factory reset data**
4. The RHINO device will begin the irreversible process of resetting the device back to factory settings, and will become available to be set back up again within several minutes.
</div>

_Tip_: While the device is resetting, please don't press buttons or attempt to interrupt the process. It may take some time to complete the reset process, but interrupting it may cause corruption or boot errors.

_Zero-touch_: If the device is zero-touch registered with an organisation, performing a factory reset of the device will not remove the zero-touch configuration, and the device will re-enrol into enterprise management automatically on attempting to set the device up again. If the device should not remain zero-touch registered, please remove it via the [zero-touch portal](https://partner.android.com/zerotouch).  

_Enterprise management_: EMM policies may prevent resetting of the device, both via Android Settings, and recovery. Should a device fail to boot/allow access with policies set, the device may need to be sent in to the [RHINO team](/support/escalate) for repair.
