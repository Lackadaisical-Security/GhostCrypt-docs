# GhostCrypt Container Format — Public Non-Normative Overview

> **Public Documentation Notice**  
> This document is a public, non-normative documentation artifact. It does not disclose source code,
> object code, binaries, cryptographic keys, private transformation pipelines, operational deployment
> procedures, protected container internals, licensing infrastructure, or any information sufficient to
> reproduce, bypass, reverse engineer, or independently implement GhostCrypt technology.
>
> All proprietary implementation details are intentionally omitted. Access to this document does not
> grant any license, authorization, export permission, or technical-data transfer.


## Overview

GhostCrypt containers use a proprietary protected-file format. The public documentation does not
disclose the binary format, header layout, magic values, offsets, metadata structures, key derivation
flow, validation logic, hidden/internal fields, or decryption behavior.

## Public Container Model

```text
[ Public Conceptual Header ]
[ Protected Metadata Region ]
[ Protected Payload Region ]
[ Integrity / Validation Region ]
[ Optional Proprietary Extensions ]
```

This diagram is conceptual only and is not compatible with any real GhostCrypt container.

## Public Design Goals

- protected data encapsulation
- metadata isolation
- integrity validation
- format-version flexibility
- hardware-bound licensing compatibility
- private extension support
- controlled migration between product versions

## Redacted Format Details

The following categories are intentionally omitted from public documentation:

- binary header size and layout
- magic signatures
- version fields
- salts, IVs, nonces, KDF fields, and validation material
- internal metadata blocks
- key-checking logic
- passphrase validation flow
- hardware-binding fields
- hidden/internal volume behavior
- anti-analysis, decoy, padding, or forensic-resistance mechanisms
- C structs, typedefs, macros, and constants
- parser logic or test vectors

## Compatibility

Container compatibility is guaranteed only for authorized builds distributed by Lackadaisical Security
or approved commercial channels. Public documentation must not be used to build parsers, converters,
extractors, validators, emulators, or compatibility layers.

## Security Review

Container-format review may be made available to qualified reviewers under NDA, written agreement,
and export-control review. Public disclosure of implementation-compatible container details is not
authorized.

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
