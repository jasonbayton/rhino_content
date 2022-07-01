---
title: Remove an application from Battery Optimisation
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2022-07-01'
updated: ''
url: "/support/battery-optimisation"
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

Battery Optimisation is part of Android's suite of power management tools. It allows Android to control the activities of optimised applications, including background usage and network communications. It does this to allow for longer battery life, as having many apps running in the background and consuming data unfettered would lead to considerable battery drain when the device is not in use.

By removing an application from the Battery Optimisation list, Android will less aggressively manage the application, allowing applications to maintain the device in a non-idle state. This is useful for applications that rely heavily on a consistent network connection or rely on background activities in order to function, but this comes at the cost of greater battery usage.

## Remove an application from Battery Optimisation  

<div class="numbered-instructions" markdown="1">
1. Open Settings
  1. Either swipe up from the home screen to display the app drawer, and select settings, or
  2. Swipe down from the notification area and tap the settings icon present in the notification panel.
2. Tap Apps & notifications
3. Tap Advanced
4. Tap Special app access
5. Tap Battery optimisation
6. Tap Not optimised and select All apps
6. Scroll through the list of applications, or use the search icon to search for the app by keyword, then tap the app
7. Tap Don't optimise
</div>

NB: An API is under development to enable this functionality remotely. For the time being, removing an app from Battery Optimisation requires access to the device.

NB: When raising battery life concerns with the [RHINO team](/support/escalate), log data will show applications in or out of the whitelist state, as well as their overall battery usage, and this may be determined as a cause for poor battery life, and recommendations for application optimisations may be made.
