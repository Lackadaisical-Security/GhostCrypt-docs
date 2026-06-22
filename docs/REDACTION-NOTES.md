# Redaction Notes

Generated: 2026-06-22

## Summary

The uploaded documents were converted into public placeholder documentation. The sanitized versions
preserve product positioning and compliance posture while removing implementation-compatible details.

## File-by-File Treatment

### lqx10-layers.md

Original risk categories:
- exact layer algorithm names and ordering
- key sizes
- KDF pseudocode and parameters
- entropy-source descriptions
- encryption/decryption processing order
- quantum-resistance analysis tied to specific layers

Public treatment:
- replaced with conceptual layer groups
- removed algorithms, ordering, KDFs, entropy sources, code, and operation flow
- added explicit non-disclosure boundary

### ULTIMATE-PENTA-GUIDE.md

Original risk categories:
- transformation counts and primitive breakdowns
- build commands
- source-tree layout
- implementation diagrams
- configuration examples
- deployment/source availability language
- unverifiable awards/certification-style claims

Public treatment:
- converted to product overview
- removed build, source tree, implementation, and configuration details
- reframed master tooling as private administrative infrastructure
- removed third-party recognition claims unless separately verifiable

### API-REFERENCE-ULTIMATE-PENTA.md

Original risk categories:
- real-looking header names
- function signatures
- file-processing API
- primitive-specific APIs
- HWID/license-generation APIs
- error codes
- integration examples
- CMake/Visual Studio integration material

Public treatment:
- replaced with API availability placeholder
- removed implementation-compatible signatures and examples
- restricted developer access to written agreement and compliance review

### container-format.md

Original risk categories:
- exact container structure
- header sizes
- C structs
- magic values
- KDF and validation flows
- hidden volume / decoy behavior
- anti-forensics mechanisms
- HWID validation logic

Public treatment:
- replaced with non-normative conceptual container overview
- removed all binary layout and parsing details
- removed hidden/decoy/anti-forensics implementation descriptions

### DEPLOYMENT-GUIDE.md

Original risk categories:
- installation commands
- GPO/SCCM/DSC/Azure deployment scripts
- license-generation commands
- hardening and Defender exclusion commands
- monitoring scripts
- update URLs
- emergency unlock workflows
- defense/government deployment examples

Public treatment:
- replaced with availability and compliance overview
- removed operational commands, scripts, and deployment automation
- restricted operational deployment support to authorized channels

## General Rule

For the public repo, anything that helps a third party build, deploy, parse, bypass, emulate,
reverse engineer, or operate the product should be private or replaced with placeholders.
