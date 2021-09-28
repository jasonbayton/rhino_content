Device administrator has been deprecated since Android 10, and EMM vendors are gradually moving away from device admin-based management.

See [this blog post from Google](https://www.blog.google/products/android-enterprise/da-migration/) for details.

## Does Rhino support device administrator?

Officially, Rhino devices running Android 10 and above no longer fully support device administrator, and support requests pertaining to device administrator enrolment will be handled on a best-effort basis. Since EMM vendors today still support device administrator enrolment, nothing prevents customers from leveraging it, however limitations will become apparent.

From 11 onwards, Rhino devices do _not_ support device administrator, and we encourage migration to Android Enterprise.

## What should customers leverage instead?

Android Enterprise is a mature, well-developed replacement for device administrator, offering:

- Increased security
- Improved support
- Consistent management across devices
- Better app and account management
- Greater functionality

For details on how to get started with Android Enterprise, speak to your EMM vendor for guidance on management on their platform, read through help topics on the [Android Enterprise help community](https://support.google.com/work/android), or read our CPO's [introduction to Android Enterprise](https://bayton.org/docs/enterprise-mobility/android/what-is-android-enterprise-and-why-is-it-used/).
