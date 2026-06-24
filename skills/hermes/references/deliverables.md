# HERMES Deliverables Reference

Catalog of the HERMES documents and checklists, naming each artifact, its purpose, and (where the source states it) its typical contents and owning role, so an agent can decide which artifact to produce and what goes in it.

## Documents

Listed alphabetically by name, matching the order of section 4.4.1 in the source. The source rarely names an explicit owning role per document, so role notes appear only where the manual states them. Where content lists are very long, only the main headings are kept.

### Acceptance report
Created for decisions on preliminary acceptance, acceptance, and acceptance migration. Documents compliance with the agreement on solution characteristics (product, service, or system) and any existing defects. Legally binding.
- Item being accepted; those involved in acceptance; basis
- Acceptance procedure; acceptance criteria with defect categories
- Delivery outcomes and defects, including measures, responsibilities, deadlines
- Acceptance outcome; signatures

### Change request
For traditional solution development, forms the basis for a change in content: describes the change to be made, the request, the procedure, and the proposed solution. In agile development it applies when changes identified by the execution organization affect project objectives, budget, or time frame of the overall project.
- Change request number; requester; date of request
- Reason for change; description of the change; information on execution
- Proposed solution; impact assessment; effort
- Costs; deadline; risks

### Change status list
Used to enumerate and monitor changes and to document all added, deleted, or changed functions or other modifications. Supports the comprehensibility of project progress (governance) and shows processing and change status. Agile change requests that affect overall project objectives, costs, or deadlines are recorded here as traditional changes (full column K).
- Per change (marked T traditional, A agile): change request number (T); requester (T); date of request (T/A)
- Change/brief description (A); decision maker (T); status (T/A)
- Change date (T/A); person responsible for the change (T); effort (T); cost (T); impact (T)

### Offer
Specifies the service or product proposed by the developer/operator, including all commercial elements (effort, costs, warranties, guarantees, rights to outcomes). Describes the processes and procedures for provision and for installation/integration.
- Structure follows the purchaser's specifications.

### Tender report
In public procurement, a report on the opening of tenders prepared after the submission deadline. Records points relevant to procurement law and procurement evaluation as applicable.
- Procurement item; date; tenderer/offer
- Subject matter; opening report

### User manual
Contains all the information a user of a product/system needs to use it properly and to react correctly to problems.
- Overview; functions; detailed descriptions of use
- Defect handling

### Work order
Contains all relevant information for completing a set task. The project manager uses it to give orders to project staff within project planning, management, information, and monitoring. Issued internally or externally; solution-specific orders are coordinated with the user representative in advance.
- Work objectives; outcomes; boundaries
- Prerequisites and dependencies; list of activities with reference to outcomes
- Activity; those responsible/involved; plan hours
- Deadlines; status; resource requirements
- Presentation of outcomes; quality assurance

### Tender documentation
All information published in a call for tender. Centers on the specifications plus the catalogue of criteria. Organization-specific tender documentation is prioritized where it exists. Also includes a draft contract, general terms and conditions, the tender notice, and specification enclosures; in public tenders, questions and answers given to all tenderers form part of it.
- Specifications (background, purpose, reason/need, procurement item, situation description)
- Organization; strengths and weaknesses; quantities and frequencies; scope and price
- Target situation (objectives and requirements; mandatory and discretionary criteria; scope; price range)
- Deadlines; structure of the offer; administrative details
- List of criteria (eligibility and award criteria; weighting; points)
- Appendices (general terms and conditions; draft contract; tender notice; additional documentation)

### Procurement analysis
Describes the concrete need for action: what is to be procured by whom and when, how the market presents itself, other framework conditions, and the applicable procurement procedure. Coordinated with controlling and compliance bodies. As a supplement to the study, forms the basis for the decision on whether to release continuation of the project, and is a prerequisite for the project management plan and the execution order.
- Reason for procurement, need for action; procurement contents and needs
- Procurement item (type, condition, quality); availability on the market; tenderers and suppliers
- Existing suppliers and contracts; requirements for and selection of tenderers; desired distribution type
- Roles and responsibilities (project manager, project team, procurement unit)
- Scheduling, financial, and procurement-law aspects; preliminary costing/efficiency preview
- Standards, documents, process steps, forms of contract; coordination of processes; procurement plan; tender procedure; procedure for questions

### Operating manual
Provides all information the operator needs to operate the system properly and react correctly to problems. In agile development it is updated per iteration/release as complete parts of the solution are activated.
- System overview; launch of operation (prerequisites, process, QA, acceptance specifications)
- Implementation and monitoring of operation; interruption or termination of operation
- Support organization (processes, roles); change management (process, organization, roles)
- Contact details; security provisions
- Appendices (operating concept; integration concept)

### Operating concept
Describes the operating organization with the organizational structure and operating processes of the operator. Forms the basis for the operating manual and the operator's organization.
- Operation requirements; system technology; IT infrastructure concept
- Systems/components/versions; networks; data security; archiving
- Organization; organizational structure; operating process
- System operation (normal operation, system monitoring, work preparation, troubleshooting)
- Security aspects; requirement coverage

### Detailed specifications
In traditional development, describes functional and qualitative solution characteristics, based on solution requirements and the product concept (or, for IT, the system concept and solution architecture). Detailed enough to be a reliable basis for realization and for detailed test case descriptions. In agile development it largely corresponds to a sprint backlog and documents current planning of selected requirements per iteration, continued iteratively (or replaced by a reference to development-framework documentation).
- Traditional: detailed requirements (organizational, functional); quality requirement/framework condition
- Agile: content characterized by the agile development methods used

### Execution order
Forms the framework and binding basis for solution development and subsequent project closure, and authorizes continuation of the project. Contains all essential solution-specific information and the procedure for the next phases. A binding agreement between the project sponsor and the project manager.
- Background and need for action; objectives; solution objectives
- Project procedure objectives (traditional/agile approach; scenario; further objectives)
- Framework conditions, strategy reference, and boundaries; summary description of the solution
- Legal basis; investment requirements; resource and aid requirements
- Cost/benefit/economic efficiency preview; planning and organization; approach (development management)
- Risks; consequences; liabilities

### Deployment concept
Describes the measures for deployment of the solution and the deployment organization, including organizational change management for the transition, the training concept, planning of acceptances (with acceptance criteria), and release criteria for the launch of operation.
- Background; impact analysis; deployment procedure
- Deployment measures (organizational transition/change management; emergency measures and organization)
- Training concept (requirements; procedure; materials; infrastructure)
- Deployment organization; deployment planning
- Planning of preliminary acceptance and acceptance (acceptance criteria); release criteria for launch of operation

### Evaluation report
Summarizes the results of the tender evaluation and forms the basis for the award decision.
- Background; procedure for the evaluation; members of the evaluation team
- Evaluation process; call for tender, questions, and tender opening
- Results (eligibility criteria; technical specifications; award criteria; evaluation procedure; evaluation and comparison of tenders)
- Selection and justification; recommendation (most suitable, most economically efficient, best tender); requests
- Signatures; appendices (completed list of criteria; evaluation; other)

### Business model description
Covers all organizational aspects relevant to the solution and influenceable by it, providing the framework for process and organizational structure. Based on the elements of the organization's business model; reinforces a holistic view.
- Business model overview; customer segments; value propositions
- Channels (communication, distribution, sales); customer relationships; key activities; markets
- Key resources (physical, financial, intellectual, personnel); key partnerships
- Revenue sources; cost structure; cost-oriented and value-oriented business model

### Integration and installation instructions
Describe how the system is integrated and installed in the operating infrastructure.
- Current situation; prerequisites; integration and installation activities
- Error and defect handling; support; integration organization; acceptance

### Integration concept
Describes how the system is integrated into the environment, how transport between system environments takes place, and how configuration management and quality are ensured. For deployment with implementation units (traditional) or step-by-step integration with releases (agile), it includes the planning of implementation units or release planning per the project management plan.
- System overview and integration items; integration objects and interfaces; integration environments
- Integration steps; transport and deployment overview; framework conditions and interdependencies
- Integration organization; risks; quality assurance

### ISDP concept
Forms the basis for defining information security and data protection (ISDP) measures. Shows the residual risks associated with operating the system and the organization.
- Content based on the requirements of the core organization.

### List of management project decisions
Documents the outcomes of the decision-making tasks of the management hierarchy level. Used for the entire duration of a project.
- Decision; underlying documents
- Decision-makers at the management and/or execution hierarchy level
- Milestone achieved yes/no; date

### List of steering project decisions
Documents the outcomes of the decision-making tasks of the steering hierarchy level. Used for the entire duration of a project.
- Decision; underlying documents
- Decision-makers at the steering hierarchy level
- Date

### Solution requirements
Includes all requirements the future system or product must fulfill: specialist and technical requirements, expected characteristics and functions, legal/regulatory requirements, operational/support/security requirements, and requirements for optimization and defect correction of existing products or systems. In traditional development, prepared in the concept phase from the study and situation analysis and updated via change management as needed.
- Rough requirements; requirements catalogue; detailed solution requirements

### Solution architecture
Based on the system concept; divides the system into subsystems and components and describes structure and interfaces, allowing a comprehensive view. Contains architecture elements/models (e.g., business process model, function model with use cases/user stories, data architecture/data model, security architecture) and the IT documentation (or a reference to the developer's documentation). System concept outcomes are summarized in an appendix. Takes account of controlling and compliance specifications.
- System structure (overview; subsystems and components)
- Solution architectures/models; interfaces and scope (interfaces with peripheral systems); reference to integration concept
- Boundaries; feasibility assessment; compliance with specifications
- Requirement assignment and coverage; outcomes of the system concept

### Migration concept
Describes the technical and organizational requirements for migration and contains the migration procedure concept. Proves feasibility and shows migration planning. Also takes account of auditing, information security, and ISDP requirements.
- Migration objectives; migration requirements; migration items
- Data analysis; migration procedure; migration plan; feasibility
- Archiving and decommissioning of the legacy system; requirement coverage

### Quote request
Used to obtain offers for services internal and external to the organization. The offers form the basis for the service level agreement (in the agree on and steer goods/services task). The quote specifications allow offers to be compared and evaluated.
- Sponsor; background; subject of the order
- Deadlines; conditions; quote specifications
- Administrative process for procurement

### Organizational requirements
Define whether a new or updated business model is needed and/or whether the organizational and process structure is changing. Include contextual, business, and organizational requirements that strengthen the internal organization and make the solution more effective, plus requirements on economic efficiency, effectiveness, and efficiency and the objectives/strategy of the core organization.
- Background; direction of the planned/changed business model
- Direction of the planned/changed organizational structure; direction of the planned/changed process structure
- List of requirements

### Organization description
Describes the organizational structure with a detailed organization chart, function descriptions, and personnel requirements. Forms the basis for assigning positions.
- Organization chart; organizational interfaces
- Function descriptions; personnel requirements

### Organization concept
Goes deeper into the solution option selected in the study from an organizational perspective. Based on the organizational requirements (supplemented by solution requirements findings); describes the relevant business model aspects and the organizational and process structure for business processing and support. Shows the new organization created and the changes to existing organization.
- Background; organizational requirements; business model
- Organizational structure; process structure; overview of changes; requirement coverage

### Phase report
Forms the basis for deciding on release of the next phase and for updating the project status report. Summarizes the outcomes and decisions of the current phase and shows the organization of the next phase.
- Background; strategy reference and implementation of requirements; benefits and economic efficiency
- Legal basis; planning and organization; forecast regarding objective achievement and solutions
- Problems and measures; risks; requests; conclusion

### Product documentation
The technical documentation of the product; all documentation defined in the development process together forms it. Prerequisite for maintenance and further development.
- Content depends on the outcomes defined in the development process.

### Product concept
Goes deeper into the solution option selected in the study. Based on the solution requirements (supplemented by organizational requirements findings); describes the product to be created. Structure and level of detail vary with the product and complexity.
- Background; requirements; boundaries
- Intended use; product classifications; product description; variants

### Lessons learned
Systematically collected and continuously documented as a project review. Support the continual improvement process in the project and the core organization, and provide indicators for subsequent projects.
- Contact; subject area; date
- Lessons learned (positive/negative); relevance (significance for own or other projects); possible causes
- Recommendation (information for the core organization)

### Project initiation order
Forms the binding basis for release of the initiation phase. The agreement between the project sponsor and project manager for the initiation phase.
- Background; objectives; objectives of the initiation phase
- Parameters; resource requirements (personnel costs, materials, costs); deadlines
- Project organization and personnel; communication; risks

### Project management plan
Contains the overall planning of the project and the essential regulations on methods, techniques, roles, and tools for the specific project. Serves as a uniform basis for action for everyone involved and clearly regulates responsibilities and division of tasks across service recipients, internal providers, and external suppliers. Continuously updated by rolling planning and steering; adapted at phase ends and before the closure phase. In agile development the execution-phase schedule is combined with the (agile) release plan.
- Project description; summary; phases and milestones (traditional) or releases (agile); release yes/no (agile)
- Scenario with execution structure plan; execution organization; project organization chart; roles and their assignment
- Project outcome structure; quality objectives and specifications; review plan (QA)
- Execution planning (schedule; release plan with releases, dependencies, requirements, organization, deadlines)
- Cost plan/approved budget; resource plan; procurement plan; communication plan
- Stakeholder management (project-specific); reporting; specifications, methods, work instruments, and tools
- Quality assurance; change management; risk management; escalation procedure; document management

### Final project evaluation
Forms the basis for the project closure decision. Gives the project sponsor a target/actual comparison on project and procedure objectives (deliverables, scheduling, finances), a summary of lessons learned, and the content and deadlines for project success monitoring.
- Background; evaluation of the achievement of objectives; economic efficiency
- Target/actual comparison (costs/benefits)
- Pending items directly from the project (with implementation deadline)
- Further measures after project closure (measure; deadlines; outcomes; those responsible; implementation deadline); request

### Project status report
Used for periodic reporting on project status, progress, and forecasts. Form and method of reporting are set in the project management plan; the project follows the core organization's requirements on content and frequency.
- Overview of project status; forecast regarding objective achievement (agile: burndown chart); target/actual comparison and forecasts
- Costs/benefits; effort; deadlines
- Outcomes; problems and measures; risks; outlook

### Minutes
Document decisions and orders made in a meeting, and important management and execution processes that must be traceable later. Important discussion and action points are recorded; recorded orders are transferred to a to-do list. Ensure traceability and comprehensibility of decisions and processes.
- Header section (meeting type/topic; date/time/place; chair/minutes; participants/absentees)
- Minutes section (welcome; approval of last minutes; agenda items discussed; decision list)
- Information on the next meeting; to-do list (appendix)

### Prototype documentation
Forms the basis for the creation and evaluation of the prototype. Records prototyping objectives, requirements, outcomes, and conclusions.
- Background; parameters; requirements
- Concept (prototype concept; required infrastructure)
- Summary of test results; reference to test concept; list of test cases
- Summary of test protocols and test report; conclusions; recommendations

### Process description
A detailed process structure down to the individual process level, describing the processes with the tools used.
- Overview of the processes
- Per process: process description (per eCH-0140); tabular process flow; graphical process flow

### Review report
Records review findings and documents the implementation decisions on the findings, as well as the decision on the status of the outcome.
- Outcome to be checked; review date; reviewer
- Findings; decisions on findings; outcome decision

### Publication
Provides information about the award for the tender concerned. Form and content are specified by the controlling and compliance bodies or the procurement office. In Switzerland, public tenders are generally published via www.simap.ch.
- Tender concerned; procurement office; successful tenderer; legal means

### QA and risk report
Prepared by the quality and risk manager (QRM) after being commissioned by the project sponsor. Provides independent information on the quality and risk situation of the project. Content depends on the mandate, scope, and methods used.
- Owner/preparer: quality and risk manager (QRM)
- Mandate and scope; procedure; overall assessment with project status
- Quality assessment; risk assessment; recommendations

### Release report
Under the agile approach, provides an overview of the project's success so far. Basis for preparing the project status report and, depending on the project management plan, for the decision on approval of any next release. Summarizes outcomes and decisions of the current release and the remaining outlay.
- Background; strategy reference and implementation of requirements; benefits and economic efficiency
- Content of the release; known errors; burndown chart
- Risks; conclusion

### Legal basis analysis
Describes the existing and applicable legal basis for the project outcome and the possible need for amendment. Pays special attention to communal, cantonal, national, and (where applicable) international legal, product-relevant, and regulatory requirements the solution and its effects on peripheral systems must comply with (product compliance).
- Existing legal basis; imminent changes; gaps identified
- Proposals to close gaps; notes concerning product compliance; evaluation of the consequences; recommendations

### Protection needs analysis
Also called the ISDP analysis. Documents the information security and data protection requirements, to be taken into account within the core organization's requirements when developing the solution.
- Content based on the requirements of the core organization.

### Service level agreement
A contractual agreement (SLA) between the operator and the user, represented by the sponsor and the user representative. Specifies the services the operator provides, defines their service level (quality of service), and sets any measures and penalties for non-compliance. Agreed services and levels are normally charged. For outsourced operations, SLAs can be an important factor in evaluating a potential operator.
- Content specified by the core organization (external providers may supply a predefined SLA). May cover:
- Preamble (subject matter; objectives; partners; scope; entry into effect, duration, cancellation)
- Services; remuneration (transfer prices; invoicing; payment modalities)
- Reporting (service level reports; other reports); consequences of deviation; rules for monitoring (SLA audits) and changing SLAs
- Conflict resolution; data protection; liability and warranty; damages; applicable law; legal venue; arbitration
- Confidentiality, secrecy, and publication; partial invalidity of provisions; signatures; enclosures

### Situation analysis
Describes and analyzes the current situation and future developments, deepening the rough status report from the study. Uses the overall solution and influence area of the selected option to determine the area of investigation. Addresses deficiencies and weaknesses to eliminate and strengths to preserve, examines whether the organization module is relevant, and forms the specialist basis for defining solution and organizational requirements. Neutral in terms of objectives and solutions.
- Current situation; current organization if relevant (business model/perspective; organizational structure; process structure)
- Description of the current solution (current system/product): objective and intended use, function; documentation (solution description/concept; parameters and specifications; user documentation; operating manual; ISDP)
- Interfaces and peripheral systems (organizational/technical); operating costs; quantities and frequencies
- Analysis of strengths, weaknesses, and causes; description of the current overall context; strengths and weaknesses analysis; conclusion and need for action

### Stakeholder interests
Form the basis for informing stakeholders and cooperating directly with them. The analysis is conducted separately from the stakeholder list, is a subjective internal project assessment (not a public outcome), and is regularly updated.
- Stakeholder positioning; stakeholder description; identified conflicts of interest and objectives

### Stakeholder list
Developed first in the initiation phase; forms the basis for managing stakeholders, cooperating directly with them, and communication planning. Continuously updated over the project.
- Stakeholders

### Study
Describes the desired solution by defining objectives (from the status report) in terms of benefits sought, lists and evaluates possible solution variants and the proposed procedure. Corresponds to the business case and shows business benefits and the reference to strategy and core-organization objectives. Selects the appropriate scenario (or creates a user-defined one) and estimates the future value of the project. Detailed only enough to make the decision on next steps clear; that decision forms the basis for the decision on whether to continue the project. Prerequisite for the project management plan and the execution order.
- Background; status report from a business perspective (business organization; product or IT system; quantities and frequencies; information security and data protection; current overall context; strengths and weaknesses analysis; analysis and evaluation)
- Objectives; framework conditions, strategy reference, and boundaries; parameters; rough requirements
- Solution options (option overview; description per option including proposed approach; analysis and evaluation: degree of objective achievement, requirement coverage, cost/benefit/economic efficiency, risk assessment, further criteria such as sustainability)
- Proposal and decision on next steps (solution option; scenario; procedure; project value)
- Planning and deadlines (scenario and modules; project deadlines, milestones; planned period of use)

### System concept
Goes deeper into the solution option selected in the study. Based on the solution requirements; shows how the solution meets them. Can describe and evaluate several system options, and there can be several system concepts on different topics.
- Background; requirements; solution concept with system options
- Per system variant: description; requirement coverage; feasibility assessment
- Comparison of options; recommendation

### Test concept
Describes test objectives, test objects, test types, test infrastructure, and test organization. Includes test planning and test case descriptions; a detailed description per test case constitutes the test specifications. Test planning sets the logical and chronological structure of the tests. Basis for providing the test organization and infrastructure and carrying out the tests; updated as new findings arise.
- Test objectives; test strategy and test levels; test objects; test types; test coverage; overview of test cases
- Assessment of test objectives and coverage; test framework (test prerequisites; defect classification; starting and abandonment conditions; test environment)
- Test case descriptions; test plan; test organization and responsibilities
- Test infrastructure (test system; test data; test tools)

### Test report
Records the test results, evaluated according to the defect classes defined in the test concept.
- Test cases from the test concept (ID; designation)
- Test date; tester; description of defect/comments

### Agreement
Governs cooperation between project participants, mainly between the user (project sponsor) and the developer. Can be concluded for one or more phases. Differentiated into project agreement and contract.
- Content stipulated by the core organization. May include:
- Deployment; elements of the contract; scope; scope of goods/services and outcomes
- Persons deployed; cooperation duties; quality assurance and acceptance; warranty
- Data protection and data security; change management; reporting; effort and costs
- Signatures; supplementary technical standards; regulations; directives

## Checklists

Checklists are part of the documents and support decision-making. Each is a list of monitoring and review steps to be executed systematically and completely within a decision preparation, reducing the probability of wrong decisions. Each is tailored to a specific decision and specifies review points with outcomes, release criteria, evaluation, those responsible, and review date. All checklists are divided into three sections: general review points, organization-specific review points, and project-specific review points.

- Acceptance checklist: review points and criteria relevant for the acceptance decision.
- Migration acceptance checklist: review points and criteria relevant for the migration acceptance decision.
- Tender checklist: review points and criteria relevant for the tender decision.
- Launch of operation checklist: review points and criteria relevant for the decision on launch of operation.
- Execution release checklist: review points and criteria relevant for the execution release decision.
- ISDP concept checklist: review points and criteria relevant for the ISDP concept decision.
- Solution architecture checklist: review points and criteria relevant for the solution architecture decision.
- Phase release checklist: review points and criteria relevant for the phase release decision.
- Closure phase release checklist: review points and criteria relevant for the closure phase release decision.
- Product concept checklist: review points and criteria relevant for the product concept decision.
- Project discontinuation checklist: review points and criteria relevant for the project discontinuation decision.
- Project closure checklist: review points and criteria relevant to the project closure decision.
- Project initiation release checklist: review points and criteria relevant for the project initiation release decision.
- Release checklist: review points and criteria relevant for the release decision.
- Preliminary acceptance checklist: all review points and criteria relevant for the preliminary acceptance decision.
- Contract award checklist: review points and criteria relevant for the contract award decision.
- Next steps checklist: review points and criteria relevant for the decision on next steps.

## Gaps

- The documents catalog in this source range almost never names an explicit owning role per document. Only the QA and risk report states an owner (quality and risk manager, QRM). Owning roles for other documents are not given here and would need to be derived from the roles or modules sections elsewhere in the manual.
- Checklist numbering in the source skips 4.4.2.16; section 4.4.2.15 (preliminary acceptance) is followed directly by 4.4.2.17 (contract award). The "next steps checklist" appears at the end of 4.4.2 without its own subsection number. Both are included above; no checklist content beyond the one-line purpose is provided in the source.
