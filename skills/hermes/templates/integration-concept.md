# Integration concept

> Official HERMES template, converted to markdown. Lines in quote blocks are the original fill-in guidance. Replace every [ ... ] placeholder; delete guidance and unused rows before use.

Project name / Project number

| Field | Entry |
| --- | --- |
| Edit date | dd.mm.yyyy |
| Version | 0.1 |
| Document status | in progress |
| Classification | unclassified |
| Author | ... |
| Project management | Project manager |
| Project sponsor | Project sponsor |
| Administrative unit | Administrative unit |
| Business area | Business area |
| Internal order no. | Internal order number |
| Project number | Project number |
| Federal PFCT | Link |
> _Adapt table as necessary before use._

## Introduction

[ ... ]

### Aim and purpose of the document

The integration concept describes how the system is integrated into the environment. It also describes how transport from one system environment to another takes place and how to ensure configuration management and quality. In the case of deployment with implementation unit (traditional) or step-by-step integration with releases (agile), the planning of implementation units or release planning according to the project management plan is part of the integration concept.
> _Text in color and italics is for guidance/examples only and should be deleted before release. [Text] indicates field names._

### Referenced documents

| No. | Name | Number / Link |
| --- | --- | --- |
| [1] | ... | # |

### Applicable documents

| Name | Number / Link |
| --- | --- |
| ... | # |

### Definitions and abbreviations

| Abbreviation | Meaning |
| --- | --- |
| CHF | Swiss francs |
| PD | Person days |
| PS | Project sponsor |
| PM | Project management |

### Specifications, methods and tools

| Title | Specification / method / tool | Version |
| --- | --- | --- |
| Project management method | HERMES | Current version |
| Documentation | MS Office suite, as per template |   |
| Processes / Procedures | MS PowerPoint, Visio |   |
| Procurement | As per core organization's specifications |   |
| Document storage | As per core organization's specifications |   |
| Reporting | As per core organization's specifications |   |

## Current situation

...
> _Why does this document exist, what is it used for (integration into operating environments, distinction from installation instructions), e.g.: This document describes the planning and parameters for integrating the XYZ specialized application into the existing operating environment of the Federal Statistical Office and is distinct from the integration and installation instructions, which describe the specific execution._

## System overview

...
> _Overview of the system components that are important for operation and their interrelationships (technical, organizational), clear distinction between what is part of the system and what is part of the environment._
> _Take the content from the chapter on the system structure of the solution architecture and make it more specific if needed._

## Integration objects and interfaces

...
> _List of relevant integration objects (e.g. LDAP, DB, external systems)._
> _Interface description (type of communication, protocols, data formats)._
> _Copy content from the chapter Interfaces to surrounding systems of the solution architecture, adapt it and transfer it to the following graphic._
> _Customizable with Microsoft PowerPoint (right mouse button - Presentation Object - Open)_

## Integration environments

...
> _Description of the surroundings: Development, testing, integration, acceptance, production environment._
> _Purpose, responsibilities, differences. e.g.: The integration environment is used to test new versions of the XYZ specialist application against connected peripheral systems before they are transferred to the acceptance and then production environment; the integration team is responsible for this. Differences mainly relate to data volume, stability and user group._

## Integration steps
> _High-level roadmap of integration steps (no detailed installation steps), handling of transitional solutions, parallel operation._

| No. | Integration step | Description |
| --- | --- | --- |
| 01 | ... | ... |
| 01 | Setup and configuration of the integration environment | Integration management takes over the coordination, steering and control of the integration measures across all phases |
| 02 | Connection to central peripheral systems | (LDAP, DB, Message Broker |
| 03 | Gradual roll-out | Gradual rollout of individual modules in parallel operation with the legacy system |
| 04 | Validation through integration and interface testing |   |
| 05 | Complete replacement of the old system | Transitional solutions such as data replication ensure coexistence until productive operation |
| ... |   |   |

## Transport and deployment overview

...
> _High-level description of transport concepts (e.g. CI/CD pipeline, release packages), move detailed steps to the installation instructions, e.g.: The XYZ specialized application is transported via an automated CI/CD pipeline: Release packages are created in the build environment, transported via the integration and acceptance environment, and rolled out in the production environment after successful approval; detailed deployment steps are described in the installation instructions._

## Parameters and interdependencies

Technical prerequisites

| No. | Prerequisite | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | HW/SW |   |
| 02 | Network |   |
| 03 | User rights |   |
| ... |   |   |

Organizational prerequisites

| No. | Prerequisite | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Acceptance of other projects |   |
| ... |   |   |

## Integration organization
> _Responsibilities for integration (project management, architect, company representative), communication and escalation channels._

| No. | Organization | Position | Name | Contact address |
| --- | --- | --- | --- | --- |
| 01 | ... |   |   |   |
| 01 | IT operation | Operations manager | Hans Müller | hans.mueller@abc.com |
| 02 | IT operation | System administrator | Bea Keller | bea.keller@abc.com |
| ... |   |   |   |   |

## Risks
> _Measures to minimize integration risks_

| No. | Risk description | Measures | Responsible | Deadline |
| --- | --- | --- | --- | --- |
| R1 |   |   |   |   |
| R1 | Data inconsistencies | Clean data migration with validations | PM | dd.mm.yyyy |
| R2 | Performance bottlenecks | Load and failover testing, monitoring with clear escalation and rollback processes | PM |   |
| R3 | Unstable interfaces | Contractually defined interfaces (versioning, timeouts, retries/circuit breakers) |   |   |
| R2 | ... |   |   |   |

## Quality assurance

...
> _Measures to ensure quality in integration._

| No. | Quality assurance | Description |
| --- | --- | --- |
| 01 |   |   |
| 01 | Monitoring | The system is continuously monitored in order to immediately detect possible misconduct. |
| 02 | Backup | Backups of the system are created periodically |
| ... |   |   |

## Document log

Change control

| Version | Name | Date | Remarks |
| --- | --- | --- | --- |
| 0.1 |   | dd.mm.yyyy |   |

Review

| Version | Name | Date | Remarks |
| --- | --- | --- | --- |
| 0. |   | dd.mm.yyyy |   |

Release

| Version | Name | Date | Remarks |
| --- | --- | --- | --- |
| 1.0 |   | dd.mm.yyyy |   |
