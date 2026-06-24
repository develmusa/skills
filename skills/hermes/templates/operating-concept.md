# Operating concept

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

The operating concept describes the operating organization with the organizational structure and operating processes of the operator. The operating concept forms the basis for creating the operating manual and the organization of the operator.
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

## Operational requirements
> _The operational requirements are described in the solution requirements document. Reference to the solution requirements. If adjustments are necessary, these must be recorded in the solution requirements document._

| No. | Requirement ID* | Requirement | Description |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | LA-02 | SaaS solution | The operation of the web solution is ensured on a suitable operating platform as SaaS with high availability and optimal scalability of the computer performance. |
| 02 | LA-04 | Open Source Cloud Computing | The web solution is operated as open source cloud computing; the software used for the web solution can be open source or more proprietary in nature but must be platform independent and system neutral. |
| 03 | LA-08 | Preventive maintenance | Within the scope of basic readiness, preventive maintenance of the web solution is ensured by means of updates and upgrades and ensures continuous, trouble-free operation. |
| ... |   |   |   |

* ID according to the requirements catalog in the solution requirements

## System technology

[ ... ]

### IT infrastructure concept

...
> _For example: The Elastic Load Balancer distributes the load between both availability zones (EU West 1 and EU West 2). In the public subnet, there is a NAT gateway in each availability zone that provides the routing for the editorial system. The editorial system is installed in a Docker container, which is scaled by auto scaling._
> _The MySQL database is obtained as a managed database service from Amazon and is maintained in both availability zones. However, only one instance is active at a time - the passive one takes over in the event of an error. An automatic scaling of the service ..._
> _Customizable with Microsoft PowerPoint (right mouse button - Presentation Object - Open)_

### Systems, components used, versions

| No. | System | Component and version | Description |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | Amazon | Amazon Elastic Load Balancer (ELB) - Version 2.45 | To distribute the requests to several web server instances |
| 02 | Amazon | Amazon EKS | To operate the Docker Containers |
| 03 | Docker Images | Apache web server 2.4.37 |   |
| ... |   |   |   |

### Networks

| No. | System | Component and version | Description |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | Amazon | Amazon NAT Gateway | To connect to the Internet |
| ... |   |   |   |

### Data security

| No. | System | Component and version | Description |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | Amazon | Amazon S3 Bucket | To save the encrypted user-specific data |
| ... |   |   |   |

### Archiving

...
> _For example: Since the client is an interface or middleware, it does not offer any function for archiving or deleting data; no data should accumulate in the interface directories during normal operation as these are each fetched and processed by a system; this must be checked periodically; larger data accumulations can indicate a problem with the overall system ..._

## Organization

[ ... ]

### Organizational structure

...
> _Organization needed to operate the IT system (organizational chart, jobs, functions), for example: The operation of the solution is ensured by ABC. Solution maintenance is the responsibility of:_

| No. | Organization | Position | Name | Contact address |
| --- | --- | --- | --- | --- |
| 01 | ... |   |   |   |
| 01 | IT operation | System administrator | Hans Müller | hans.mueller@abc.com |
| 02 | IT operation | System administrator | Bea Keller | +41 99 999 999 |
| ... |   |   |   |   |
> _Furthermore, description of the effects of the IT system in terms of organization, analysis of the need to adapt the rough quantities._

| No. | Aspect | Amount |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Number of subsites | 1,000 |
| 02 | Number of monthly page impressions | 1,000,000 |
| 03 | Storage space | 500 GB |
| ... |   |   |

### Operating processes
> _Operating processes needed to operate the IT system, description of user support tasks with process description, regulations, instructions_

| No. | Process | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Operation monitoring | To prevent unnecessary interruptions to operations, the system is monitored using CloudWatch. Here, utilization and log data are aggregated and evaluated in order to ... |
| 02 | Importing updates | Updates classified as 'Critical' are installed within 24 hours in the time window between 2am and 3am. |
| 03 | Software changes | Any changes to the software are immediately reported to the customer, as well as unplanned maintenance windows that become necessary to update software |
| ... |   |   |

...
> _Furthermore, description of the effects of the IT system on the processes, analysis of the need for adaptation, ..._

## System operation

[ ... ]

### Normal operation

| No. | Operation instance | Metrics | Description |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | Docker Container | CPU utilization | The utilization of the virtual CPU |
|   |   | DiskReadOps | The number of read operations |
|   |   | DiskWriteOps | The number of write operations |
| ... |   |   |   |

### System monitoring

...
> _Description of operational monitoring with supervision, alerting, etc., data backup, data protection controls, reference to operational processes, for example: The system is monitored at all times with Amazon CloudWatch and scaled if necessary. CloudWatch collects monitoring and operational data in the form of logs, metrics and events, and natively connects to all Amazon Cloud services in use. System errors are detected at an early stage and the ..._

### Work preparation

...
> _Project-specific concepts_

## Troubleshooting

Error levels

| No. | Error levels | Description | Max. duration for troubleshooting |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | Immaterial error | Errors that impair use of the application but allow the function to be executed by means of alternatives | By arrangement |
| 02 | Minor error | Errors that impair use of the application in certain sub-areas due to lack of alternatives | 5 PD |
| 03 | Serious error | Errors that make the execution of entire functions impossible | 2 PD |
| 04 | Critical error | Errors that give incorrect outcomes and trigger critical situations | 1 PD |
| ... |   |   |   |

Process

...
> _Reference to operating processes, description of the procedure in the event of an error (incl. organizational aspects such as communication with users, etc.), such as: The project sponsor notifies the contractor of the error by means of an incident ticket, describes it (e.g. by means of error code, error number, error text and situation in which the error occurs) and classifies the error according to the table above. Operating and service hours apply. The contractor analyzes the error and reports back the predicted time required for troubleshooting. If the contractor has a different assessment, they must give reasons for their assessment. The project sponsor decides on execution._

## Description of security aspects

...
> _Project-specific concepts, for example: The application is implemented in compliance with the Open Web Application Security Project (OWASP) so that security problems from the outset..._
> _Should security problems nevertheless arise, we have isolated the user roles from each other as much as possible ..._
> _The user-specific data is stored encrypted in the S3 bucket. The key is either chosen by the visitor or generated automatically by the system. However, the key will not ..._
> _Regular updates ensure that the system is in as secure a state as possible...._

## Requirement coverage

...
> _Assessment of the degree of coverage in accordance with the requirements in the chapter on operational requirements_

| No. | Requirement | Requirement coverage | Reason (if not fully covered) |
| --- | --- | --- | --- |
| 01 | ... |   |   |
| 01 | SaaS solution | 100% |   |
| 02 | Open Source Cloud Computing | 50% | Platform independence not fully possible |
| 03 | Preventive maintenance | 100% |   |
| ... |   |   |   |

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
