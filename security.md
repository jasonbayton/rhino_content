---
title: RHINO security
subtitle: ''
featuredImage: ''
featured: 'false'
date: '2021-01-01'
updated: ''
url: "/security"
type: doc_parent
published: 'true'
parent: ''
is_parent: 'true'
parentID: Security
childTopics:
- Releases
topic: ''
order: '0'
---

## Overview

As part of our commitment to the security and longevity of our portfolio, RHINO devices benefit from software updates throughout the lifetime of each model. Updates are provided in two ways:

### Android version upgrades

All RHINO devices are guaranteed a minimum of one Android version upgrade from the date of launch. For Global SKU devices, upgrades are rolled out in stages across all devices from our central OTA servers. For Private SKU customers, upgrades are made available on an agreed-upon basis, or shortly following Global SKU rollout if no agreements are in place.

As RHINO is made for extended support and availability, new Android version upgrades may be undertaken during the period of hardware availability. This may be due to demand, customer agreement, or otherwise. If your organisation leverages RHINO and desires a version upgrade, reach out to [sales](mailto:sales@socialmobile.com).

### Android security updates & maintenance releases

**All RHINO devices benefit from security updates within 90 days of release from Google, normally sooner, for 3-5 years, model-depending.**

Security updates include all CVEs addressed by Google for the referenced SPL (security patch level), and may also address CVEs published by SOC vendors (eg, MediaTek) and partners (eg, Honeywell) if available. We recommend security updates are applied as soon after release from our central OTA servers as possible. For customers with EMMs supporting it, we also make the OTA files available for local/closed network installation via Android Enterprise (Android 10) and OEMconfig (Android 9.0+).

As the RHINO range of devices supports A/B seamless updates, downtime for system updates is minimal, requiring only a reboot once the update is applied in the background. Should this update fail to apply, it will reboot back into the previous OS build. This minimises risk for deployed endpoints.

Occasionally, maintenance releases will be required. These include changes outside of security patches and may resolve performance issues, bugs, configuration issues or update system applications. These updates will typically include an updated SPL but not always. A maintenance release can be identified by _Build type: **MR**_ compared to a security update's _Build type: **SMR**_.

## Android security update support

The following table outlines each available RHINO device and pertinent information relating to support.
<div id="support_table" markdown="1">
| **Model**                          | **SKU** | **Launch** | **OS** | **Upgrade**                                    | **EOA**   | **SMR EOS** |
|------------------------------------|---------|------------|--------|------------------------------------------------|-----------|-------------|
| [RHINO C6](/security/releases/t80)       | Global  | 2023       | 12     | 13                                             | 2025      | 2026        |
| [RHINO T80](/security/releases/t80)      | Global  | 2023       | 12     | 13                                             | 2025      | 2026        |
| [RHINO T5se](/security/releases/t5se)    | Global  | Sep 2022   | 11     | 12                                             | Dec 2024  | Sep 2025    |
| [RHINO PACE A1](/security/releases/pace-a1)    | US  | Sep 2022 | 11     | 12                                             | Dec 2024  | Sep 2025    |
| [RHINO T8](/security/releases/t8)        | Global  | Aug 2020   | 9      | [10](/security/releases/t8/t8-001_20210605)    | Aug 2023  | Aug 2023    |
| [RHINO C10](/security/releases/c10)      | Global  | Aug 2020   | 9      | [10](/security/releases/c10/c10-001_20210617)  | Aug 2023  | Aug 2025    |
| [RHINO M10p](/security/releases/m10p)    | Global  | Sept 2020  | 10     | 11                                             | Sept 2023 | Sept 2025   |

EOA - End of availability (manufacture)  
SMR EOS - End of security update releases  

**NB**: EOA/EOS referenced is _expected_ and may be extended subject to availability of components, vendor support, or customer engagement. Ongoing discussions of extended support may not be reflected in this list, so refer to your TAM or Partner organisations for updated details.  
</div>

## Disclosing vulnerabilities

For details on disclosing vulnerabilities to the RHINO team, [click here](/security/vulnerability-disclosure).
