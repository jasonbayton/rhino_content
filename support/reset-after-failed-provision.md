---
title: Reset your RHINO device following a failed zero-touch enrolment event
subtitle: 'This applies to all Android Management API based EMM vendors, such as Intune, Mambo, Wizy, and others.'
featuredImage: ''
featured: 'false'
date: '2022-02-18'
updated: ''
url: "/support/reset-after-failed-provision"
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

Occasionally the zero-touch provisioning flow may fail. This can be a number of things:
1. Connectivity
2. DPC errors
3. Invalid/expired enrolment tokens
4. The device is not zero-touch registered
5. The device doesn't have a zero-touch configuration assigned

For 4, the zero-touch provisioning process will not initiate, instead progressing through the standard setup wizard. The solution to this is to reach out to the [RHINO support team](/support/escalate) for assistance. Please have a PO or other proof of purchase available as this may requested, in addition to your zero-touch customer ID.

For 5, locate the IMEI of the RHINO device, log on to the [zero-touch customer portal](https://partner.android.com/zerotouch), search for the device based on the IMEI field and assign a configuration.

For 1-3, this will often leave the device in a state that cannot be progressed, but equally doesn't automatically prompt to reset the unit in some situations. Normally the DPC (MobileIron, VMWare, agents) will have an option to reset the device through a menu item manually, and details for this can be found within the documentation provided by your EMM vendor.

Customers leveraging Mambo, Intune, Wizy, or another Android Management API based EMM can, at almost any point through the enrolment process, tap the menu icon in the top right of the screen and choose to reset the unit to factory settings.

Where the enrolment token has expired, the zero-touch process will stall, and the Android Device Policy agent will offer to scan a QR code. More often than not leveraging this will result in additional "invalid token" errors, irrespective of the validity of the QR code scanned. The simplest solution is to reset the device, and start the zero-touch provisioning process again **once the zero-touch configuration has been updated with a new enrolment token**.

For more assistance on zero-touch, please reach out to the [RHINO support team](/support/escalate).
