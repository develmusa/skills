# Migration concept

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

The migration concept describes the technical and organizational requirements for migration and contains the migration procedure concept. The migration concept proves feasibility and shows migration planning. Aside from technical and organizational requirements, the auditing, information security and ISDP requirements are also taken into account.
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

## Migration objectives

| No. | Objective | Priority |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Correction of errors in master data | 1 |
| 02 | Extension of the range of functions | 1 |
| 03 | Improved use of available resources | 2 |
| ... |   |   |

* Priority: 1 = high, 2 = medium, 3 = low

## Migration requirements
> _The migration requirements are described in the solution requirements document. Reference to the solution requirements. If adjustments are necessary, these must be recorded in the solution requirements document._

| No. | Requirement ID* | Requirement | Description |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | LA-01 | Data cleansing | "Disposal and reprocessing" of legacy data |
| 02 | LA-05 | Automatic transfer | All migration objects must be transferred automatically |
| ... |   |   |   |

* ID according to the requirements catalog in the solution requirements

## Migration items

| No. | Migration item | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Master data | Which master data (articles, customers, suppliers, etc.) are to be transferred? |
| 02 | Transaction data | Which transaction data (invoices, credit notes, item stocks, orders, etc.) are to be transferred? |
| ... |   |   |

## Data analysis

...
> _Analysis of the data to be migrated (e.g. what dependencies exist between the data to be migrated? Does certain data have to be transferred manually?), quantities, frequencies, data quality (e.g. which data is difficult or impossible to transfer as standard)?_

## Migration procedure

Overview

| Migration item | Requirement with ID* | Migration procedure | Assessment of requirement coverage |
| --- | --- | --- | --- |
| ... |   |   |   |
| Transaction data | LA-01: Data cleansing | Import via MS Excel | met |
| Master data |   |   |   |
| ... |   |   |   |

* ID according to the requirements catalog in the solution requirements

Concept (per procedure)
> _Conceptual description of the procedures, required infrastructure, etc._

| No. | Migration procedure | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Import via MS Excel | Export existing data from the existing system to Excel, macro for format adjustments, import Excel into the new system. No specific infrastructure required. |
| ... |   |   |

## Migration plan
> _Procedure for migration, timing, dependencies, quality checks_

| Date | Migration step | Description |
| --- | --- | --- |
| dd.mm.yyyy | ... |   |
| dd.mm.yyyy | Determination of articles to be migrated | A specific PLSQL procedure determines all articles to be migrated via a database link. |
|   | ID mapping | IDs are mapped via functions: Standard buyer in the legacy system -> standard buyer in the new system. Errors are written to an error table and ... |
| ... |   |   |

## Feasibility

Risks

Assessment of feasibility or migration risks:

| No. | Migration risks | Possible solution | Residual risk |
| --- | --- | --- | --- |
| 01 |   |   |   |
| 01 | Errors exist in the existing system: Supposedly mandatory fields are not set for some of the data. Negative stock levels exist for some items. And much more ... | Error elimination through automatic or manual clean-up in the existing system. | low |
| 02 | Inactive customers are not to be migrated: however, there are open items for some of these customers | Activation of customers with open items | medium |
| ... |   |   |   |

## Fallback scenario

...
> _"Plan B" in the event of migration problems_

## Archiving and decommissioning of the legacy system

...
> _Archiving concept: How should the data of the legacy systems be stored in order to fulfill all requirements in a legally secure manner? How long must the legacy data be kept? Should it still be possible to evaluate the legacy data? Who should be able to access the legacy data and how often?_
> _Decommissioning plan: If any final work is required after the end of the operation, it should be mentioned here, this may concern e.g. the treatment of data carriers ..._
> _Disposal_

## Requirement coverage

| No.* | Requirement | Coverage |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Data cleansing | not met |
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
