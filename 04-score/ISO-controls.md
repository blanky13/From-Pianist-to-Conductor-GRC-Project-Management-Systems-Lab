# ISO-Aligned Control Set

## Purpose

This is a deliberately small learning subset for OrchestraX. It is **not** a complete ISO/IEC 27001 Annex A implementation.

ISO/IEC 27001:2022 contains an Annex A reference set of 93 information-security controls. ISO/IEC 27001 uses risk treatment to determine the controls an organization needs; Annex A is then used as a comparison/reference set to help verify that necessary controls have not been omitted.

## Selected Controls

| ID | ISO/IEC 27001:2022 Annex A | OrchestraX Learning Use |
|---|---|---|
| A.5.15 | Access control | Define and enforce access rules |
| A.5.16 | Identity management | Manage identities across the lifecycle |
| A.5.18 | Access rights | Provision, review and remove rights |
| A.5.24 | Information security incident management planning and preparation | Establish incident-management readiness |
| A.8.8 | Management of technical vulnerabilities | Identify and treat technical vulnerabilities |
| A.8.15 | Logging | Generate and manage relevant logs |
| A.8.32 | Change management | Control security-relevant changes |

## Why These Controls

The set deliberately creates cross-functional dependencies:

- **Access control** connects GRC, IT and Security.
- **Identity management** connects HR and IT.
- **Access rights** creates JML and review workflows.
- **Incident management** connects Security, IT, Operations and management.
- **Vulnerability management** creates prioritization and remediation dependencies.
- **Logging** connects implementation, monitoring and evidence.
- **Change management** connects technical execution with governance.

## Control Ownership Principle

The Annex A identifier is not the owner.

Ownership belongs to an OrchestraX role that has authority and responsibility for the actual control outcome.

## Evidence Principle

For every selected control, the project will eventually identify:

- control owner;
- implementation mechanism;
- operating frequency or trigger;
- evidence source;
- reviewer;
- exception path;
- testing method;
- failure condition.

## Version Control

This file intentionally uses the 2022 control structure. If the standard or applicable guidance changes, the project should update the reference version rather than silently mixing editions.
