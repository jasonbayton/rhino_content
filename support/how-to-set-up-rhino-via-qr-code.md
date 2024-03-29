---
title: How to set up a RHINO device via QR code
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-09-29'
updated: ''
url: "/support/how-to-set-up-rhino-via-qr-code"
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

QR code enrolment allows customers to initiate Android Enterprise managed provisioning with just a simple scan of a QR code from the welcome screen. QR code provisioning is simple, and allows for several advanced options to be embedded within, such as Wi-Fi network, system app availability, EMM enrolment credentials, and more. After scanning the QR, the device will download the corresponding Device Policy controller application from the Google Play Store. Managed provisioning will then initiate and EMM enrolment will take over shortly after using the enrolment credentials provided by the respective EMM vendor.

## Steps to enrol the device via QR code

<div class="numbered-instructions" markdown="1">
1. Turn on the device from a boxed state, or factory reset the unit if not fresh from the box. You'll must be greeted by the welcome screen
2. Tap 6 times on the set-up screen to launch the QR code scanner
3. The device will launch the QR code scanner
4. Scan the QR code supplied by the EMM administrator/IT department
5. The device will identify the DPC app required and start downloading
  1. If Wi-Fi details are embedded, the device will connect automatically to Wi-Fi, similarly should cellular be forced, the device will connect over a mobile network and continue provisioning. If nothing is declared, the end user will be prompted to connect to Wi-Fi
6. Once downloaded, the DPC will install and setup will complete, moving automatically over to the EMM vendor enrolment flow
7. Enter the enrolment credentials supplied by the EMM vendor
8. Proceed with the instructions on screen and complete the enrolment
9. Your device is now enrolled and setup is complete
</div>

<div class="callout callout-warning">
The RHINO team do not supply QR codes for device management. Speak to your organisation for this.
</div>
