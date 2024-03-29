---
title: Device admin & Android Enterprise
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-09-28'
updated: '2021-09-30'
url: "/support/device-admin"
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

Device administrator has been deprecated since Android 10, and EMM vendors are gradually moving away from device admin-based management.

See [this blog](https://www.blog.google/products/android-enterprise/da-migration/) and [this blog](https://www.blog.google/products/android-enterprise/why-its-time-enterprises-adopt-androids-modern-device-management-apis/) from Google for details.

## Does RHINO support device administrator?

The RHINO team fully endorse the use of Android Enterprise and actively _discourage_ device administrator for device management. We have invested heavily in solutions, services and have extensively validated our hardware for Android Enterprise-based deployments to ensure the best possible experience; something that can't be guaranteed with device admin-based management.

Officially, RHINO devices running Android 10 and above do not fully support device administrator, and support requests pertaining to device administrator enrolment will be handled on a best-effort basis. Since EMM vendors today still support device administrator enrolment, nothing prevents customers from leveraging it, however limitations will become apparent, and the RHINO team will direct customers to their EMM vendors for support.

From 11 onwards, RHINO devices do _not at all_ support device administrator, and we encourage migration to Android Enterprise.

## Why should customers leverage Android Enterprise?

Android Enterprise is a mature, well-developed replacement for device administrator, offering:

- Increased security
- Improved support
- Consistent management across devices
- Better app and account management
- Greater functionality

For details on how to get started with Android Enterprise, speak to your EMM vendor for guidance on management on their platform, read through help topics on the [Android Enterprise help community](https://support.google.com/work/android), or read our CPO's [introduction to Android Enterprise](https://bayton.org/docs/enterprise-mobility/android/what-is-android-enterprise-and-why-is-it-used/).
