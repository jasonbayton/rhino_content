---
title: What is a Full OTA?
subtitle: 'How is a Full OTA different from a "normal" OTA?'
featuredImage: ''
featured: 'false'
date: '2021-10-15'
updated: ''
url: "/support/what-is-a-full-ota"
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

Every release cycle the Rhino team upload an OTA package for customers to download and manually apply to their Rhino devices.

These releases require a specific previously released build of Android to be present on the device. For example you cannot update a Rhino device running a build date of 2020-07-14 to 2021-04-26 if build 2021-04-26 targets the prior release dated 2021-03-18. Your Rhino device will state explicitly it is looking for a build which is not present on the device.

As many of our customers stage their devices before deployment, and wish to run with what is often a much newer Android version than the device shipped with (particularly when said devices are purchased, then stored), this can result in the need to manually update (via [ADB](/support/update-via-adb) or [SDCard](/support/update-via-sdcard)) multiple small update files. A tedious process.

To ease this requirement, the Rhino team occasionally release a Full OTA package in tandem with the normal OTA package. This OTA package requires only the build running on the Rhino device being updated is older than the build being manually updated. With a Full OTA package, a device running a build from early 2020 on Android 9.0 could be updated to an Android 10 build in late 2021 through one manual update.

Full OTAs are available on the release pages of each device (eg, [T8](/security/releases/t8)). You may check the release pages sporadically for new full OTA packages.

Should you wish to request a Full OTA is generated for a particular software build to aid in your staging project, please [reach out to the Rhino team](/support/escalate).
