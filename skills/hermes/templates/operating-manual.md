# Operating manual

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

The operating manual provides all the information the operator needs to operate the system properly and to be able to react correctly in the event of problems. All operating information of relevance for the operator is documented in the operating manual.

During agile solution development, the operating manual is updated several times, per iteration/release, as each complete part of the solution is activated.

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

## System overview

System components

...

Content is based on the chapter on system technology in the operating concept.
> _Overview of the system components important for operation and their interrelationships (technical, organizational) ..., illustration, if applicable._
> _Customizable with Microsoft PowerPoint (right mouse button - Presentation Object - Open)_

...
> _If necessary, description of the system in text form._

Interfaces

...
> _Copy the integration objects and interfaces from the integration concept and adapt them if necessary._

## Launch of operation

[ ... ]

### Prerequisites for the launch of operation

...
> _Copy the chapter on parameters and dependencies from the integration concept and adapt it if necessary._

### Launch of operation process

...
> _Copy the chapter on integration and installation activities from the integration and installation guide and adapt it if necessary._

### Quality assurance after the launch of operation

...
> _Copy the chapter on quality assurance from the integration concept and adapt it if necessary._

### System acceptance specifications

...
> _Copy the chapter on operational requirements from the operating concept and adapt it if necessary._

## Execution and monitoring of operation
> _Describes measures for maintaining and monitoring operations, based on the system operation chapter in the operating concept._

| No. | Area | Measure |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Server monitoring | The client writes all data relevant for monitoring into the log file. Configuration of log files is described in the installation manual. It is recommended to keep the log files for at least 6 months ... |
| 02 | Verification of correct processing | In order to check the correct processing (receipt and dispatch), there are the following possibilities ... |
| 03 | Backup protection | In the event that a backup is created by the client, the corresponding directory in which the client is written must be protected accordingly at the directory level. |
|   | Backup and recovery | The following data can be secured with the backup mechanism ... |
| ... |   |   |

## Interruption or termination of operation
> _Stopping system operation, procedure for relaunch of operation, quality assurance after relaunch of operation, dismantling the system, archiving, transfer, ..._

Planned interruption of operation (shutdown and restart)

...

For example: If the ABC app was installed as a service, it can be stopped as a service ... if the ABC app was installed as a start script, a corresponding stop script is available in the directory ...

Unplanned service interruption (crash)

...
> _After a crash, it must be ensured that application server and database processes are no longer running; if necessary, these must be terminated using appropriate tools ..._

Post-treatment and finishing work

...
> _If any final work is required after the end of the operation, it should be mentioned here, this may concern e.g. the treatment of data carriers ..._

## Support organization

[ ... ]

### Support processes

...
> _Copy the Support chapter from the integration and installation instructions and adapt it if necessary._

### Organization with roles

...
> _Copy the table from the Integration Organization chapter of the Integration and Installation Instructions and adjust it if necessary._

## Change management

[ ... ]

### Change management process
> _Reference to operating processes, description of the procedure in the event of changes (incl. organizational aspects such as communication with users, etc.) ..._

| No. | Step | Description |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Clarify needs |   |
| 02 | Create concept |   |
| 03 | Plan measures |   |
| ... |   |   |

### Change management organization

| No. | Organization | Position | Name | Contact address |
| --- | --- | --- | --- | --- |
| 01 | ... |   |   |   |
| 01 | IT operation | Operations manager | Hans Müller | hans.mueller@abc.com |
| 02 | Department XY | Product owner | Bea Keller | +41 99 999 999 |
| ... |   |   |   |   |

## Security provisions

...
> _Description of the provisions and measures to ensure the necessary security, including the areas of infrastructure, organization and personnel as well as disaster preparedness and insurance ..._

| No. | Area | Security provision |
| --- | --- | --- |
| 01 | ... |   |
| 01 | Data storage | The client does not store messages for an extended period of time. The database only stores data about the messages, but not the messages themselves. For this reason, no special security names are necessary for long-term storage of sensitive data |
| 02 | Database protection | Direct access to the database must be restricted to administrators so that unintentional or deliberate changes in the database do not corrupt the state of the client and thus make it inconsistent |
| 03 | Backup protection | In the event that a backup is created by the client, the corresponding directory in which the client is written must be protected accordingly at the directory level. |
| ... |   |   |

## Annexes
- Operating concept
- Integration concept

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
