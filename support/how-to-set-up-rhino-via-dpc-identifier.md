---
title: How to set up a Rhino device via DPC identifier
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-09-29'
updated: ''
url: "/support/how-to-set-up-rhino-via-dpc-identifier"
type: doc
published: 'true'
parent: Support
topic: Enterprise
order: '0'
appliesTo:
- C10
- T8
- K27p
- M10p
- T5se
---

DPC Identifier enrolment allows customers to initiate Android Enterprise managed provisioning with no additional external requirements, such as a QR code, NFC tag, or pre-setup with zero-touch. DPC identifier provisioning is simple; at the point where an end user would usually enter their Google account details, a DPC identifier will be entered instead, in the format of `afw#identifername`. After entering the identifier, the device will download the corresponding Device Policy controller application from the Google Play Store. Managed provisioning will then initiate and EMM enrolment will take over shortly after using the enrolment credentials provided by the respective EMM vendor.

## Steps to enrol the device via DPC identifier  

<div class="numbered-instructions" markdown="1">
1. Turn on the device from a boxed state, or factory reset the unit if not fresh from the box. You'll must be greeted by the welcome screen.  
2. Tap to start the Setup Wizard and connect to a network (Wi-Fi or cellular)
3. Proceed through the Wizard to Google Sign in screen
4. Enter the DPC identifier of your respective EMM vendor in place of a Google account
5. The device will identify the DPC app required and start downloading, you may be prompted to approve this
6. Once downloaded, the DPC will install and setup will complete, moving automatically over to the EMM vendor enrolment flow
7. Enter the enrolment credentials supplied by the EMM vendor
8. Proceed with the instructions on screen and complete the enrolment
9. Your device is now enrolled and setup is complete
</div>

<div class="callout callout-info">
Contact your EMM vendor for the respective DPC identifier.  
</div>
