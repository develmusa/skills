# Solution architecture

> Official HERMES template, converted to markdown. Lines in quote blocks are the original fill-in guidance. Replace every [ ... ] placeholder; delete guidance and unused rows before use.

Project name / Project number

| Field | Entry |
| --- | --- |
| Edit date | 4/5/2026 |
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

The solution architecture is based on the system concept and divides the system into subsystems and their components. It describes the system structure and the interfaces. The solution architecture allows for a comprehensive view of the system. Depending on the project outcome and scope, it contains several architecture elements and models, e.g. the business process model, the function model (e.g. with use cases/user stories), the data architecture/data model, and the security architecture. It also contains the IT documentation or refers to the developer's documentation. The outcomes of the system concept are summarized in an appendix to the solution architecture.

The solution architecture takes into account the specifications of the controlling and compliance bodies.
> _Text in color and italics is for guidance/examples only and should be deleted before release._

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

## System structure

[ ... ]

### Overview of the system

...
> _Customizable with Microsoft PowerPoint (right mouse button - Presentation Object - Open)_

### Subsystems and components

| No. | Subsystem and component | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Database system | Oracle Database Cloud |
| 02 | Web server | Apache HTTP Server |
| 03 | Operating system | Linux software |
| ... |   |   |

### Architectures / Models

...
> _The following example is deliberately kept simple. The solution architecture must be documented in accordance with organizational specifications: network zones, firewalls, etc. must be taken into account._
> _Customizable with Microsoft PowerPoint (right mouse button - Presentation Object - Open)_

## Interfaces and scope

[ ... ]

### Interfaces with peripheral systems

| No. | Interface | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Document management system | Office Manager is addressed via the standard interface |
| 02 | SAP |   |
| ... |   |   |

### Reference to integration concept

...
> _The solution architecture described here is specified in detail in the integration concept._

### Boundaries
> _Copy the table with the system-relevant distinctions from the Parameters chapter in the study and, if necessary, adapt it or add further distinctions._

| No. | Boundaries | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | IT firewall | It is an internal solution that runs on the intranet and is therefore completely within the firewall system. |
| ... |   |   |

## Feasibility assessment

...
> _Assessment regarding the feasibility of the planned solution, from a technical and, if applicable, organizational point of view._

## Compliance with specifications
> _Coverage of solution requirements with prescriptive character_

| No. | Requirements | Conformity | Description, justification of deviations |
| --- | --- | --- | --- |
| 01 |   |   |   |
| 01 | ISO9001 | partially | Process changes initiated by the project are ISO9001 compliant. |
| 02 | New EU data protection regulation | Yes | New EU data protection regulation must be observed or complied with ... |
| ... |   |   |   |

## Requirement assignment and coverage
> _Coverage of solution requirements: Copy the requirement title and brief description from the requirements catalog in the solution requirements into the table below and add the respective requirement coverage._

| No.* | Requirement title according to solution requirements | Brief description of requirements / component | Description of the cover |
| --- | --- | --- | --- |
| LA-01 |   |   |   |
| LA-01 | Receive data | RFID | By means of RFID technology |
| LA-02 | Save data | Flash drive | Saving on the flash memory of the device |
| ... |   |   |   |

* Number of the requirement in the catalog of solution requirements.

## Outcomes of the system concept

...
> _Summary of findings from the system concept_

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
