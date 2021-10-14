---
title: 'SafetyNet compliance issue when enrolling into SOTI MobiControl'
subtitle:
featuredImage:
featured: 'false'
date: '2021-10-14'
updated:
url: '/support/soti-safetynet-compliant'
type: 'doc'
published: 'true'
parent: 'Support'
topic: 'Enterprise'
order: '0'
appliesTo:
  - 'T5se'
  - 'T8'
  - 'C10'
  - 'M10p'
  - 'K27p'
---

When enrolling a Rhino device into SOTI MobiControl, you may encounter the following error:

> Enrollment failed. This device is not SafetyNet compliant. Please contact your system administrator

This is _not_ a Rhino issue, as all Rhino models are GMS certified and SafetyNet compliant from factory. This is a known, random issue which occurs when enrolling into SOTI MobiControl. The SOTI team are aware of it.

Should this error show during enrolment, please wipe and retry.

If it continues to happen, you may either:

<div class="numbered-instructions" markdown="1">
1. Opt to disable SafetyNet verification:
  1. Head to System Settings
  2. Open Global Settings
  3. Select Android Plus Tab
  4. Edit your "Add Devices" rule
  5. Scroll to and open Advanced
  6. Check "Enroll on SafetyNet Attestation Failure
2. Contact SOTI support for further assistance
</div>

Unless your device is modified in any way from factory state (rooting, system modification, etc), the Rhino team cannot help with this directly and encourage reaching out to SOTI support.
