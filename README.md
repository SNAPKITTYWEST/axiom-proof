# Bel Esprit D’Accord — Copyright, Licensing & Legal Warning

**Copyright © 2026 Ahmad Ali Parr, Bel Esprit D’Accord Irrevocable Trust, and SnapKitty Collective Limited (FLP). All rights reserved except as expressly granted below.**

**Contact:** [ahmedparr93@gmail.com](mailto:ahmedparr93@gmail.com)
**Project Organization:** [SNAPKITTYWEST](https://github.com/SNAPKITTYWEST?utm_source=chatgpt.com)

## ⚠️ IMPORTANT LICENSING WARNING

This repository is **not offered under a single unrestricted open-source license**.

It uses a **tri-license structure** consisting of:

1. **Business Source License 1.1 (BSL-1.1)**
2. **GNU Affero General Public License v3.0 (AGPL-3.0)**
3. **Mozilla Public License 2.0 (MPL-2.0) with a separate commercial licensing option**

You must determine which license grants the rights you intend to exercise **before copying, modifying, distributing, deploying, sublicensing, or commercially operating the software**.

**Do not assume that the presence of source code means unrestricted commercial use is permitted.**

The applicable license files in this repository control the legal terms of use. This README is an informational guide and does not replace the actual license texts or a separately executed commercial agreement.

---

## 1. BUSINESS SOURCE LICENSE 1.1

The BSL-1.1 layer provides source availability while imposing specified restrictions on certain commercial uses.

Under the project's BSL configuration:

* Commercial use is subject to the BSL-1.1 terms.
* Certain managed-service and enterprise-scale offerings are restricted during the BSL period.
* The applicable **Change Date is August 8, 2028**.
* On the Change Date, the BSL-covered code is intended to become available under AGPL-3.0, subject to the precise terms of the BSL-1.1 license.

**See:** `LICENSE.BSL`

The actual BSL text governs if this summary conflicts with it.

---

## 2. GNU AFFERO GENERAL PUBLIC LICENSE v3.0

The AGPL-3.0 option provides strong network copyleft.

Where AGPL-3.0 applies:

* Modifications are subject to AGPL-3.0 requirements.
* Network interaction provisions apply as specified by the AGPL.
* Corresponding-source and license-notice obligations must be satisfied where applicable.
* Redistribution must preserve the applicable AGPL terms.

**See:** `LICENSE.AGPL`

The actual AGPL-3.0 text governs.

---

## 3. MOZILLA PUBLIC LICENSE 2.0

The MPL-2.0 option provides file-level copyleft.

Under MPL-2.0:

* Covered modified files remain subject to MPL-2.0.
* MPL-covered code can generally be combined with proprietary code subject to the MPL's conditions.
* Copyright, license, and notice requirements must be preserved.
* The MPL does **not** automatically impose its terms on unrelated proprietary files merely because they are combined with MPL-covered code.

**See:** `LICENSE.MPL`

The actual MPL-2.0 text governs.

---

# COMMERCIAL DUAL LICENSING

Organizations that require rights outside the applicable copyleft/source-available terms may request a separate **commercial license**.

A commercial agreement may provide rights such as:

* Proprietary distribution
* Closed-source modifications
* Copyleft bypass where legally permissible
* Commercial embedding
* Enterprise deployment
* Alternative redistribution terms
* Other rights negotiated directly with the copyright holder

Commercial licensing inquiries:

**[ahmedparr93@gmail.com](mailto:ahmedparr93@gmail.com)**

A commercial license is **not granted merely by contacting the copyright holder**. Commercial rights outside the applicable public licenses require an executed agreement or other written authorization from the rights holder.

---

# LICENSE SELECTION GUIDE

| Intended use                                                  | Relevant licensing path |
| ------------------------------------------------------------- | ----------------------- |
| Use under the source-available commercial restrictions        | **BSL-1.1**             |
| Network/SaaS deployment where AGPL terms are applicable       | **AGPL-3.0**            |
| Modification of MPL-covered files                             | **MPL-2.0**             |
| Proprietary commercial deployment requiring different rights  | **Commercial License**  |
| Open-source redistribution under the applicable copyleft path | **AGPL-3.0**            |

**Important:** This table is only a high-level guide. It does not determine the legal license for a particular implementation. Review the actual license text and the files' applicable licensing notices.

---

# COPYRIGHT AND OWNERSHIP

Copyright © 2026:

**Ahmad Ali Parr**
**Bel Esprit D’Accord Irrevocable Trust**
**SnapKitty Collective Limited (FLP)**

All rights not expressly granted by an applicable license are reserved.

No contributor, user, distributor, customer, or downstream operator receives ownership of the underlying intellectual property merely by obtaining a copy of the repository.

Third-party components remain subject to their respective licenses.

---

# CONTRIBUTIONS

Contributions to this repository may be incorporated into the project under the project's applicable licensing framework.

Before submitting substantial third-party code, contributors should ensure that they have the necessary rights to contribute that material.

Do not submit proprietary, confidential, or third-party code for which you do not possess the necessary authorization.

---

# LICENSE COMPATIBILITY ENGINE

This project includes a Prolog-based license compatibility reasoner:

```text
backends/license_policy.pl
```

Example:

```bash
swipl -q -t halt -f backends/license_policy.pl -- matrix
```

Check dependencies:

```bash
swipl -q -t halt -f backends/license_policy.pl -- check agpl3 deps.json
```

Select a license for a use case:

```bash
swipl -q -t halt -f backends/license_policy.pl -- select saas_wrapper
```

The compatibility engine is an engineering aid. **Its output is not legal advice and does not override the actual license texts.**

---

# WHY TRI-LICENSE?

The structure separates three different objectives.

### BSL-1.1 — Commercial protection

The BSL layer provides source availability while temporarily restricting specified commercial uses, particularly the types of commercial service deployment defined by the project's BSL configuration.

### AGPL-3.0 — Network copyleft

The AGPL path is intended to ensure that software distributed or operated under AGPL-3.0 remains subject to the freedoms and source-disclosure obligations specified by that license.

### MPL-2.0 — File-level flexibility

The MPL path provides a weaker, file-level copyleft model that can facilitate integration with proprietary systems while preserving the MPL requirements for covered files.

### Commercial License — Proprietary use

Organizations requiring rights beyond those available through the public licensing options may negotiate a separate commercial agreement.

---

# TRANSITION TIMELINE

**August 8, 2026**

BSL-1.1 + AGPL-3.0 + MPL-2.0 licensing structure becomes effective.

**August 8, 2028**

The stated BSL Change Date.

BSL-covered material is intended to transition to AGPL-3.0 according to the terms of the BSL-1.1 license.

**After the Change Date**

The applicable BSL-covered code is intended to remain available under the public licensing paths specified by the project, including AGPL-3.0 and MPL-2.0 where applicable, or under a separately negotiated commercial license.

---

# ⚠️ NO IMPLIED RIGHTS

Unless expressly granted by an applicable license or written agreement, this repository does **not** grant:

* Trademark rights
* Patent rights beyond those expressly provided by the applicable license
* Rights to use project branding
* Rights to represent yourself as an authorized distributor
* Rights to remove copyright notices
* Rights to relicence another person's contributions
* Rights to commercially exploit restricted BSL-covered functionality outside the BSL terms

---

# NO WARRANTY

THE SOFTWARE IS PROVIDED SUBJECT TO THE TERMS OF THE APPLICABLE LICENSE.

TO THE MAXIMUM EXTENT PERMITTED BY LAW, THE COPYRIGHT HOLDERS AND CONTRIBUTORS DISCLAIM WARRANTIES AND LIABILITY AS PROVIDED BY THE APPLICABLE LICENSE.

**THE ACTUAL LICENSE TEXTS CONTROL.**

If there is any conflict between this README and `LICENSE.BSL`, `LICENSE.AGPL`, `LICENSE.MPL`, or a separately executed commercial agreement, the applicable legal instrument controls.

---

## Repository License Files

```text
LICENSE.BSL
LICENSE.AGPL
LICENSE.MPL
```

For commercial licensing:

**[ahmedparr93@gmail.com](mailto:ahmedparr93@gmail.com)**

**Copyright © 2026 Ahmad Ali Parr / Bel Esprit D’Accord Irrevocable Trust / SnapKitty Collective Limited (FLP).**
