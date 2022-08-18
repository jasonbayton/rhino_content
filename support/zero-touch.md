---
title: Provision your RHINO device with zero-touch
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2022-03-16'
updated: ''
url: "/support/zero-touch"
type: doc
published: 'true'
parent: Support
topic: Enterprise
order: '0'
appliesTo:
- C10
- T8
- M10p
- T5se
- K27p
---

<div class="callout callout-warning">
<div class="callout-heading">Enterprise management heads-up</div>
Note: You will need a zero-touch Customer Account which can be acquired from your device reseller. If you are using a RHINO Device purchased direct from Social Mobile or RHINO online, please <a href="/support/escalate">contact the RHINO team</a>
</div>

## What is zero-touch?

Zero-touch is an Android Enterprise enrolment method, which can offer an efficient way to provision your RHINO devices for enterprise management. Used by many organisations, it allows a device to be preconfigured, or assigned, to an EMM platform prior to the device being switched on for the first time (the out of box experience).

Once you have zero-touch configured, you can turn on an assigned device, connect it to a network & the zero-touch configuration will pull down the EMM config to enrol it onto your EMM Console.


## Benefits of zero-touch

As the name suggests, there is minimal interaction required from the IT/mobile admin teams, reducing staging and preparatory steps considerably and allowing direct-to-customer/employee shipment, which can assist with large scale corporately owned device rollouts.

## Zero Touch Minimum Requirements

You will need a compatible device running Android Oreo [8.0], and all Android 9.0 devices on the market are supported by default. All RHINO devices as of 2022 run Android 10 or newer.

## How to configure Zero Touch

<div class="numbered-instructions" markdown="1">
1. [Click here to access your Zero Touch Portal](https://partner.android.com/zerotouch)
2. Navigate to the Configurations tab, then create a new configuration
3. Choose your desired EMM from the list, or Android Device Policy for AMAPI EMMs such as Mambo, Microsoft Endpoint Manager, Wizy, etc.
4. Fill out the additional support information, and optionally pre-fill the DPC extras field with enrolment details, these can be obtained through your EMM.
5. Save.
</div>

Note: If your EMM token expires, or enrolment details change, you can update the configuration with the new details as often as you wish by clicking edit next to the saved, existing configuration.

## Adding Configuration to Devices

<div class="numbered-instructions" markdown="1">
1. Once your devices have been added by your reseller, they should appear in the Devices tab of your Zero Touch Portal.
2. Select the Devices tab and assign the configuration to your devices.
</div>

<div class="callout callout-warning">
<div class="callout-heading">Enterprise management heads-up</div>
Note: If you assign a configuration to a device which has already been turned on and connected to a network. That device will need to be factory reset to pick up the configuration.
</div>
