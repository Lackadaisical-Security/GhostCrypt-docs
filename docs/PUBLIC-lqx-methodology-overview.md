# GhostCrypt LQX Methodology — Public Layer Overview

> **Public Documentation Notice**  
> This document is a public, non-normative documentation artifact. It does not disclose source code,
> object code, binaries, cryptographic keys, private transformation pipelines, operational deployment
> procedures, protected container internals, licensing infrastructure, or any information sufficient to
> reproduce, bypass, reverse engineer, or independently implement GhostCrypt technology.
>
> All proprietary implementation details are intentionally omitted. Access to this document does not
> grant any license, authorization, export permission, or technical-data transfer.


## Purpose

The LQX methodology is a proprietary multi-layer cryptographic design intended for defensive file
protection, research-grade cryptographic experimentation, and controlled commercial evaluation.
The public version of this document describes the architecture at a conceptual level only.

## Public Architecture Summary

LQX uses a layered protection model with independently isolated stages. Each stage is designed to
contribute a distinct defensive property, such as:

- authenticated encryption behavior
- key separation
- post-quantum migration readiness
- integrity validation
- metadata compartmentalization
- hardware-bound licensing compatibility
- tamper-resistance checks
- failure-containment boundaries

## Redacted Layer Model

The following public table intentionally avoids algorithm ordering, key sizes, KDF parameters,
entropy sources, exact operation counts, and implementation details.

| Layer Group | Public Role | Public Description |
|---|---|---|
| Foundation Group | Baseline confidentiality | Establishes the first proprietary protection boundary. |
| Hybrid Group | Classical/PQ transition | Combines conventional and post-quantum design goals without disclosing implementation. |
| Integrity Group | Validation and tamper checks | Provides proprietary authenticity and corruption-detection behavior. |
| Diversity Group | Algorithmic separation | Uses independent internal stages to reduce single-point failure assumptions. |
| Outer Protection Group | Container-facing protection | Finalizes protected output and prepares metadata for the private container system. |

## Placeholder Layer Specification

```text
Layer 00: [PROPRIETARY REDACTED] — private transformation family
Layer 01: [PROPRIETARY REDACTED] — private transformation family
Layer 02: [PROPRIETARY REDACTED] — private transformation family
Layer 03: [PROPRIETARY REDACTED] — private transformation family
Layer 04: [PROPRIETARY REDACTED] — private transformation family
Layer 05: [PROPRIETARY REDACTED] — private transformation family
Layer 06: [PROPRIETARY REDACTED] — private transformation family
Layer 07: [PROPRIETARY REDACTED] — private transformation family
Layer 08: [PROPRIETARY REDACTED] — private transformation family
Layer 09: [PROPRIETARY REDACTED] — private transformation family
```

## Non-Disclosure Boundary

The public documentation does not disclose:

- exact algorithms, ordering, or chaining
- key sizes, salts, KDF schedules, or derivation flow
- entropy sources or collection logic
- processing order for encryption or decryption
- memory layout, internal buffers, or container offsets
- anti-analysis, anti-tamper, or licensing enforcement logic
- test vectors or implementation-compatible examples

## Validation Model

Public claims should be interpreted as product-level claims only. Implementation validation,
security review, formal analysis, and reproducibility materials are available only through
authorized review channels under written agreement.

## Export-Control / Restricted Access Notice

GhostCrypt technology may include cryptographic functionality and may be subject to U.S. and
international export-control, sanctions, restricted-party, end-use, and end-user regulations,
including the EAR, ITAR, and OFAC-administered sanctions programs. No export, reexport, transfer,
release, disclosure, download, technical assistance, defense service, or foreign-person access is
authorized except through written approval by Lackadaisical Security and any required legal review,
classification, screening, and government authorization.

No representation is made in this public document that any item has been finally classified under a
specific ECCN, USML category, license exception, or export-control designation. Classification and
authorization requirements must be determined before any transfer, disclosure, commercial delivery,
or foreign-person access.


## Copyright

Copyright © 2025 Lackadaisical Security. All rights reserved.
