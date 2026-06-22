# Security Policy

## Scope

This security policy applies to the public documentation repository for **GhostCrypt LQX-20 Cosmic** and related Lackadaisical Security public materials.

This repository is documentation-only. It does **not** contain source code, object code, binaries, installers, private APIs, activation services, cryptographic keys, decryption matrices, proprietary transformation pipelines, production licensing logic, or operational deployment infrastructure.

Security reports concerning private builds, licensed binaries, commercial deployments, customer environments, or non-public Lackadaisical Security systems are in scope only when submitted by an authorized party under an applicable written agreement.

## Supported Materials

| Material | Status | Notes |
| --- | --- | --- |
| Public README / documentation | Supported | Documentation errors, security-sensitive disclosure, and unsafe implementation guidance may be reported. |
| Public license / notice / export-control files | Supported | Report contradictions, missing restrictions, or unclear compliance language. |
| Public examples or placeholders | Supported | Report examples that accidentally expose implementation details or unsafe instructions. |
| Source code, binaries, installers, activation services, production APIs | Not included in this repository | Access requires written authorization and applicable compliance review. |
| Legacy private drafts or internal documents | Not public scope | Do not redistribute, mirror, or publish internal materials. |

## Reporting a Vulnerability

Do **not** report security vulnerabilities through public GitHub issues, public discussions, social media, or pull requests containing sensitive details.

Send reports to:

**security@lackadaisical-security.com**

Recommended subject line:

```text
[SECURITY] GhostCrypt LQX-20 Cosmic Report
```

For export-control, licensing, sanctions, or restricted-access concerns, use:

**export@lackadaisical-security.com**

For legal or compliance concerns, use:

**legal@lackadaisical-security.com**

## What to Include

Please include as much of the following as possible:

- Affected repository, file, document, section, or version.
- Clear description of the issue.
- Security impact and realistic exploitation scenario.
- Steps to reproduce, if applicable.
- Whether the report concerns public documentation, licensed software, private materials, or a deployed environment.
- Any screenshots, logs, snippets, or references needed to verify the issue.
- Your preferred contact method for follow-up.

Do not include third-party secrets, private keys, customer data, unlawfully obtained data, or exploit material that is not necessary to demonstrate the issue.

## Security Research Guidelines

Good-faith security research is welcome when it stays within the authorized scope.

### Permitted

- Reviewing public documentation for accidental disclosure of implementation details.
- Reporting unsafe examples, exposed internal paths, leaked identifiers, or contradictory security claims.
- Testing only systems, files, containers, accounts, or deployments that you own or are expressly authorized to assess.
- Reporting suspected licensing, export-control, sanctions, or access-control weaknesses through private channels.

### Not Permitted

- Accessing, testing, or attacking systems you do not own or lack authorization to assess.
- Attempting to decrypt, bypass, extract, or recover data that does not belong to you.
- Circumventing licensing, HWID binding, activation controls, access controls, or commercial restrictions.
- Reverse engineering proprietary binaries, protocols, activation systems, or private APIs except where expressly authorized in writing.
- Exfiltrating, modifying, deleting, or publicly disclosing data.
- Social engineering, phishing, physical attacks, denial-of-service testing, or harassment.
- Publishing exploit details before Lackadaisical Security has had a reasonable opportunity to investigate and remediate.

## Disclosure Process

Lackadaisical Security aims to follow coordinated vulnerability disclosure.

General target timelines:

| Stage | Target |
| --- | --- |
| Acknowledgment | Within 3 business days |
| Initial triage | Within 10 business days |
| Status update | As appropriate based on severity and complexity |
| Coordinated disclosure | By mutual agreement |

Critical issues may be handled faster. Complex issues, export-control concerns, licensing-abuse cases, or reports requiring legal review may require extended timelines.

## Severity Classification

Severity is evaluated based on realistic impact, exploitability, affected scope, and whether the issue concerns public documentation or licensed private systems.

| Severity | Examples |
| --- | --- |
| Critical | Public release of private keys, production signing material, source code, activation secrets, decryption matrices, or exploitable deployment credentials. |
| High | Accidental publication of implementation-sensitive cryptographic internals, license-bypass logic, container-parsing internals, or operational deployment procedures. |
| Medium | Documentation that materially weakens security posture, encourages unsafe deployment, exposes non-secret internal structure, or creates compliance ambiguity. |
| Low | Typos, stale contact information, unclear wording, minor documentation inconsistencies, or non-sensitive metadata exposure. |

## Bug Bounty Status

There is no public bug bounty program unless a separate written agreement states otherwise.

Any bounty, reward, consulting fee, recognition, testing authorization, or disclosure timeline must be agreed in writing before testing begins. Submitting a report does not create an obligation to pay a reward.

## Export Control and Restricted Access

GhostCrypt LQX-20 Cosmic and related Lackadaisical Security technologies may include cryptographic functionality and may be subject to United States and international export-control, sanctions, and restricted-party regulations, including but not limited to the Export Administration Regulations (EAR), the International Traffic in Arms Regulations (ITAR), and regulations administered by the U.S. Office of Foreign Assets Control (OFAC).

Do not export, reexport, transfer, disclose, download, provide access to, or provide technical assistance involving controlled technology except as expressly authorized in writing by Lackadaisical Security and only after applicable classification, licensing, sanctions, end-user, end-use, destination, and restricted-party review.

This public repository does not represent a final ECCN, USML category, license exception, export authorization, defense-service authorization, or legal classification.

## No Warranty and No Implied Permission

This security policy does not grant any license, source-code access, binary access, commercial right, reverse-engineering right, export authorization, or permission to access non-public systems.

All rights are reserved by Lackadaisical Security. This policy should be read together with the repository `LICENSE`, `NOTICE.md`, and `EXPORT_CONTROL.md`.

## Contact

Security: **security@lackadaisical-security.com**  
Export Control: **export@lackadaisical-security.com**  
Legal: **legal@lackadaisical-security.com**  
Website: **https://lackadaisical-security.com**

---

Copyright © 2025 Lackadaisical Security. All rights reserved.
