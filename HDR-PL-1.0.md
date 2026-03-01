# HDR Public Software License 1.0 (HDR-PL-1.0)

> **Preamble.** Digital technology must preserve human dignity, ownership, privacy, and agency. This license grants broad freedom to use, study, modify, and share software while requiring distributors and operators to respect the Human and Digital Rights principles summarized in the HDR. The license seeks to combine strong copyleft protections with explicit obligations around data use, transparency, and device ownership.

---

## Table of Contents

1. Preamble
2. Definitions
3. Grant of Copyright License
4. Source Form and Conveying
5. Copyleft and Downstream Obligations
6. Anti‑Tivoization and No Secret Kill‑Switch
7. Services, Telemetry, and AI Training
8. Advertising and Monetization Constraints
9. Patent and Contributor Grants
10. Preservation of Notices and HDR Attribution
11. No Additional Restrictions
12. Disclaimer of Warranty; Limitation of Liability
13. Compatibility, Versions & Governance
14. How to Apply This License (headers, SPDX, HDR_NOTICE)

---

## 1. Preamble

Digital life is real life. Ownership, consent, privacy, and fairness must apply online as they do offline. To preserve those rights, licensors publishing software under this license grant expansive rights to recipients while requiring that downstream conveyances and operators respect the Human and Digital Rights principles summarized in the HDR.

## 2. Definitions

* **Licensed Work.** The work (in source or object form) distributed under this license.
* **You.** Any natural person or legal entity exercising rights under this license.
* **Program.** Any work that results from combining the Licensed Work with other code or content.
* **Convey.** Any act of transferring, distributing, publishing, or otherwise making the Licensed Work available to another party, including providing functionality via a hosted service (see Service Conveyance).
* **Service Conveyance.** Making the Licensed Work available to end users as part of a hosted or remotely executed service, including SaaS, hosted APIs, device firmware services, or other remote-execution models.
* **HDR Principles.** The principles described in the Human and Digital Rights Declaration, including meaningful opt-in for data use, protection against arbitrary bricking or disabling of devices without disclosure/consent, algorithmic transparency and appeal, and enhanced protections for vulnerable persons.

## 3. Grant of Copyright License

Subject to the terms and conditions of this license, the copyright holder grants you a worldwide, royalty-free, non-exclusive, perpetual license to:

* copy, modify, and distribute the Licensed Work (in source or object form);
* make and run Programs that include or are derived from the Licensed Work;
* combine the Licensed Work with other works and convey the resulting Program under the terms of this license.

## 4. Source Form and Conveying

1. When you convey the Licensed Work in object form (including binaries, firmware images, or compiled artifacts), you must accompany it with the complete corresponding source code in a reasonable and standard form, or provide a written offer with a durable, verifiable method to obtain the corresponding source for at least three (3) years from the date of conveyance.
2. When conveying a modified version you must include a clear, human‑readable changelog describing modifications and a pointer to the location of the canonical repository or contact information for the contributor.

## 5. Copyleft and Downstream Obligations

1. Any conveyance of a Program that contains the Licensed Work, or where the Licensed Work is a substantial part of the combined Program, must be licensed to recipients under the terms of this license (HDR-PL-1.0) or a later approved version of this license.
2. You may not apply license terms, technical measures, or contractual obligations to recipients that negate or materially conflict with the HDR Principles.

## 6. Anti‑Tivoization and No Secret Kill‑Switch

1. If the Licensed Work is conveyed in device firmware, device images, or packages intended to run on consumer hardware, you must not impose technical restrictions that intentionally prevent recipients from running modified versions of the Licensed Work on that hardware.
2. An exception is permitted only when a remote-control, kill-switch, or device‑disabling capability is clearly and conspicuously disclosed at the point of sale and explicit, informed opt-in consent for that capability was obtained from the purchaser. The disclosure and consent must be recorded in documentation accompanying the product and in the license notice.
3. Any such remote-control capability must be limited to stated purposes (repair, security response, court order compliance, or explicitly disclosed safety features) and must not be used to silently revoke ownership or essential user capabilities.

## 7. Services, Telemetry, and AI Training

When you operate or convey the Licensed Work as part of a Service Conveyance, you must comply with the following obligations:

1. **Data & Model Use Notice.** Publish a concise, machine‑readable notice describing any automatic collection of user data, behavioral profiling, or use of user‑contributed content for model training. The notice must be linked from user interfaces where data is collected and from the top-level documentation.
2. **Explicit Opt‑In.** Obtain explicit, auditable opt‑in consent before using any personal data, sensitive signals, or user-contributed content for model training, behavioral profiling for personalized advertising, or persistent identifiers beyond the minimum necessary for service operation.
3. **Revocation & Deletion.** Provide practical mechanisms for users to export, delete, and revoke consent for their data and to request removal from training datasets where feasible. Disclose limitations when removal is technically infeasible and obtain consent accordingly.
4. **Appeals & Human Review.** For consequential automated decisions (account suspension, content removal, denial of essential features), provide a clear appeals path and human review process. Automated systems must disclose accuracy limitations and allow users to obtain explanations of major factors influencing the decision.

## 8. Advertising and Monetization Constraints

1. Behavioral profiling used to target ads requires user opt‑in. Contextual ads (based on immediate content) are permitted without opt‑in.
2. Advertisements that use exploitative attention techniques (e.g., sexualized thumbnails aimed at inferred vulnerabilities) are disallowed by default for minors and must be subject to stricter limits for all users.
3. Every ad delivered as part of a Program or Service Conveyance must offer a concise “Why this ad?” explanation and a one‑click opt‑out for ad personalization.

## 9. Patent and Contributor Grants

1. Each contributor to the Licensed Work grants downstream recipients a non‑exclusive, worldwide, royalty‑free patent license for patents necessarily infringed by the contributor's contribution as distributed by the contributor.
2. If you initiate patent litigation alleging that a contributor's code infringes your patent(s), your license under this agreement terminates automatically.

## 10. Preservation of Notices and HDR Attribution

1. All copies and substantial portions of the Licensed Work must retain the original copyright notice, this license text, and a short `HDR_NOTICE` that summarizes the HDR Principles and points recipients to where they may exercise opt-in/opt-out and appeals.
2. Distributors must not remove, obfuscate, or hide notices that inform users of their rights and how to exercise them.

## 11. No Additional Restrictions

You may not impose legal or technical restrictions on recipients that contradict the HDR Principles or otherwise prevent recipients from exercising rights granted by this license (for example, requiring irrevocable assignment of ownership rights, forcing permanent data transfer without consent, or using hidden subscriptions to revoke user ownership).

## 12. Disclaimer of Warranty; Limitation of Liability

The Licensed Work is provided "AS IS," without warranty of any kind, express or implied, including but not limited to warranties of merchantability, fitness for a particular purpose, or non‑infringement. To the extent permitted by law, the authors and licensors shall not be liable for any damages arising from the use of the Licensed Work.

## 13. Compatibility, Versions & Governance

1. The licensor may publish new versions of this license. Works may be re‑released under a later version only if they preserve the HDR Principles.
2. Optionally, licensors may choose to include a permissive compatibility clause allowing downstream relicensing under the GNU General Public License version 3 (GPL‑3.0) provided that all HDR obligations remain honored in practice. This option is **not** automatic; the original copyright holder must choose it explicitly.

## 14. How to Apply This License

### Recommended short header (source file):

```
Copyright (c) 2026 <Your Name or Organization>
Licensed under the HDR Public Software License 1.0 (HDR-PL-1.0).
See the LICENSE file for details and the included HDR_NOTICE for human‑readable rights information.
```

### LICENSE file and HDR_NOTICE

Include the full text of this license in a `LICENSE` file at the project root. Also include an `HDR_NOTICE.md` or `HDR_NOTICE.txt` that summarizes the HDR Principles in plain language and explains how users may:

* opt in/out of data uses and training,
* request export or deletion of data,
* appeal consequential automated decisions,
* find disclosure of any device remote-control capabilities that were consented to by purchasers.

### SPDX and Metadata

Suggested SPDX tag: `HDR-PL-1.0` (adopt and reserve this identifier if you plan to publish the license broadly). Provide metadata in project manifest files (e.g., `package.json`, `pyproject.toml`) referencing `HDR-PL-1.0`.

---

## Example `HDR_NOTICE.md` (short)

```
This project is licensed under the HDR Public Software License 1.0 (HDR-PL-1.0).
It adheres to the Human & Digital Rights principles:
- Data collection and model training use require explicit opt-in.
- You have rights to export and delete your data where feasible.
- Devices distributed with remote-control capabilities disclose them at sale and require purchaser consent.
- Appeals and human review processes are available for consequential automated decisions.
See the full LICENSE for exact terms and contact <maintainer contact> for support.
```

---

## Final notes

This license is intended as a practical, copyleft-forward instrument that encodes human- and digital-rights obligations into software distribution and service operation. It is a draft and should be reviewed by legal counsel before use in production.
