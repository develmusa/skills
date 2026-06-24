# Test concept

> Official HERMES template, converted to markdown. Lines in quote blocks are the original fill-in guidance. Replace every [ ... ] placeholder; delete guidance and unused rows before use.

Project name / Project number

| Field | Entry |
| --- | --- |
| Edit date | 4/2/2026 |
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

The test concept describes the test objectives, test objects, test types, test infrastructure, and test organization. It also includes test planning and test case descriptions. A detailed test case description is created for each test case. This constitutes the test specifications. Test planning determines the logical and chronological structure of the tests. The test concept forms the basis on which the test organization and test infrastructure are provided and the tests conducted. The test concept is updated if new findings arise.
> _Italic text in the document: Information on use or examples - to be adapted or deleted accordingly._

### Referenced documents

| No. | Name | Number / Link |
| --- | --- | --- |
| [1] |   | # |

### Applicable documents

| Name | Number / Link |
| --- | --- |
|   | # |

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

## Test objectives

Overall measurable test objectives across all test cases:

| No. | Description | Measurement variable | Priority |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | Interface test successful | Exchange of data correct | 1 |
| 02 | System architecture meets the requirements of xy |   | 2 |
| 03 | - | Program abc functional | 1 |
| ... |   |   |   |

* Priority: 1 = high, 2 = medium, 3 = low

## Test strategy and test levels
> _Efficient testing requires a well thought-out (and possibly agile) test strategy:_
> _With which test strategy can the development be accompanied and supplemented in order to achieve the specified quality? How intensively should testing be at which level? This depends on different factors, such as the available budget for testing, the risk, the complexity of the system to be developed, the amount of teams, etc._
> _Which test levels (developer test (module test), integration test, system test and acceptance test) are there / from which test level should testing start?_
> _How can overlaps of different test levels be avoided (prevention of redundancies)?_
> _How can deficits in the available test environment be circumvented/overcome?_
> _etc._

| No. | Test strategies | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Test strategy | .... developer testing at unit level is carried out on both a white box and black box basis and... |
| 02 | Test levels | Developer test, integration test, system test |
| 03 | Prevention of redundancies |   |
| 04 | Deficits of the test environment can be circumvented |   |
| ... |   |   |

## Test objects

| No. | Object | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Master data | Which master data (articles, customers, suppliers, etc.) |
| 02 | Transaction data | Which transaction data (invoices, credit notes, item stocks, orders etc.) |
| ... |   |   |

## Test types

| No. | Test type | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Functionality test | Checking the functions |
| 02 | User test | Checking the operation |
| ... |   |   |

## Test coverage

[ ... ]

### Overview of test cases
> _Overview of the test cases, which are described in detail in the following test case descriptions._

| No. | Test Object | Test cases |
| --- | --- | --- |
| T-01 | ... |   |
| T-01 | Master data | Entering new master data |
| T-02 | Master data | Delete master data |
| T-03 | Master data |   |
| T-04 | Transaction data | Entering new master data |
| ... |   |   |

### Assessment of test objectives and test coverage

...
> _Basic assessment of testing objectives and coverage_

## Test framework

[ ... ]

### Test prerequisites
> _Testers, previous knowledge, infrastructure, etc._

| No. | Prerequisite | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Tester | B. Meier, A. Klein, K. Lang |
| 02 | Previous knowledge | MS Office, SAP |
| 03 | Infrastructure | Laptop with intranet connection |
| ... |   |   |

### Defect classification

The defects found, or the requirements (expectations) not fulfilled, are classified from 1 to 4. Category 0 is used only if a flawless outcome is to be shown separately:

| No. | Defect category | Description |
| --- | --- | --- |
| 0 | Flawless | Flawless and in line with requirements |
| 1 | Insignificant defect | Use possible, proven usability, no defect should occur |
| 2 | Minor defect | Use possible, usability is only slightly impaired |
| 3 | Major defect | Use still possible, usability is greatly reduced |
| 4 | Critical defect | Unusable; essential functionality is not provided; operation is not acceptable (e.g. safety-related). |

The classification reflects the severity of the consequences and the time and outlay required to remedy the defects that can be identified. The allocation of the defects found to a defect category also roughly determines the order of priority for remedying the defects.

In the case of defect category 1 to 3, the system/product can be accepted with reservations. However, measures to remedy the defects must be defined. A supplementary review is mandatory.

If, instead, category 4 defects are found, the system/product cannot be accepted and the provider must take immediate measures to remedy these defects. The provider must also arrange for another acceptance procedure.

### Starting and abandonment conditions

...
> _Prerequisites for start of test, data, infrastructure, discontinuation conditions: Incorrect, incomplete data, infrastructure not fully functional, unexpectedly poor test results, etc._

## Test environment

...
> _Description and organization of the required (practical) test environment(s)_

## Test case descriptions
> _Describe all test cases individually in the following format, as outlined in the test case overview._

| ID / Designation | T-01 | Reference to requirement & Acceptance criterion | OA-nn or LA-nn e.g. number of the requirement in the catalog of solution requirements or organizational requirements |
| --- | --- | --- | --- |
| Description | ... |   |   |
| Test prerequisite | ... |   |   |
| Test steps | ... ... ... |   |   |
| Expected outcome | ... |   |   |

## Test schedule

| No. | Activity | Responsible | Participants | Deadline |
| --- | --- | --- | --- | --- |
| 01 | ... |   |   |   |
| 01 | Entering new master data | Hans Meier | Urs Klein | 12.02.2022 |
| 02 | Delete master data | Bea Keller | Erich Gross | 12.03.2022 |
| ... |   |   |   |   |

## Test organization and responsibilities

...

## Test infrastructure

[ ... ]

### Test system

...

### Test data

...

### Test tools

...
> _Test management software, list of reports_

## Document log

Change control

| Version | Name | Date | Remarks |
| --- | --- | --- | --- |
| 0.1 |   |   |   |

Review

| Version | Name | Date | Remarks |
| --- | --- | --- | --- |
| 0. |   |   |   |

Release

| Version | Name | Date | Remarks |
| --- | --- | --- | --- |
| 1.0 |   |   |   |
