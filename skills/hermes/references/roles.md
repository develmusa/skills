# HERMES Roles Reference

This reference catalogues every role described in HERMES chapter 6, grouped into the three role levels (Steering, Management, Execution), with each role's mission, responsibilities, competencies (powers), skills, and the deliverables or decisions it owns.

## How role descriptions are structured

Each HERMES role description follows the same fixed structure:

- Description: conveys the understanding of the role.
- Responsibility: what the role is responsible for (where applicable).
- Powers (also labelled Competence): the decision-making authority of the role (where applicable).
- Skills: the knowledge a person needs to perform the role. HERMES makes no distinction between knowledge and experience here, since the required level depends heavily on the project.
- Relationships: for each module, the specific tasks the role is responsible for and the other roles involved in creating the outcome. If a role has no task responsibility, no relationships are listed.

Two rules govern responsibility:

- The role responsible for a task is also responsible for achieving the outcomes and for the outcomes themselves.
- The roles involved in achieving an outcome are not exhaustive and must be defined per project.

## RACI-style responsibility model

HERMES distinguishes two responsibility positions for every task and outcome:

- Task responsibility (responsible): exactly one role is named as responsible for each task. That role owns the task, owns achieving its outcomes, and owns the outcomes themselves. This is the "responsible" / "accountable" position.
- Involved in creation of outcome (participating): one or more additional roles contribute to producing the outcome but do not carry responsibility for it. This is the "participating" / "consulted" position, and the listed set is not exhaustive (it is tailored per project).

In the role tables, the source consistently uses these two columns: "Task responsibility" (the single owning role) and "Involved in creation of outcome" (the participating roles). Steering decisions (for example release decisions and milestones) are owned at the steering level, while management owns planning, control, and procurement tasks, and execution roles own the specialist and technical delivery tasks.

## Partner groups (contractor / partner side)

HERMES organizes participants into three partner groups: user, developer, and operator. Execution roles, the test role, and the test manager can be staffed from any of these partner groups in their area of responsibility:

- Each partner group represented in the project (user, developer, operator) tests in its own area of responsibility.
- Each partner group can appoint a test manager in its own area of responsibility.

To preserve governance and avoid conflicts of interest, HERMES restricts who may staff key roles. Project management and the user representative must be located with the user; provision by partner groups, developers, or operators should be avoided for those roles. Sub-project managers should also be based with the user but may, in defined cases, be provided by partner groups (with overall responsibility staying with project management). The developer role is the partner-side delivery role (product developer and IT developer combined) and the operations manager represents the operator side.

## Steering roles

### Project sponsor

- Level: Steering.
- Mission: Responsible for the outcomes of the project and the achievement of the set objectives within the set framework conditions; initiates and steers the project.
- Responsibilities:
  - Initiation and steering of the project; overall responsibility for the project and objective achievement.
  - Reconciliation of project objectives with the overarching strategies, requirements, and objectives of the core organization.
  - Provision of resources (financial, human, infrastructure) and assurance they are used efficiently.
  - Timely decisions on requests and measures.
  - Chairing the project committee and appointing its members.
  - Appointment and steering of the project management, and definition of the project management's powers.
  - Assurance of sufficient participation by the specialist area.
- Powers (Competence):
  - Decision-making power within the framework of the allocation of powers by the core organization.
  - Allocation of financial and human resources, as well as infrastructure, to the project.
  - Escalation to the core organization.
- Skills: business understanding and knowledge of the specialist area; knowledge of core organization requirements (procurement, financing, controlling, security), project steering, and project organization; business administration knowledge for efficient use of resources; in-depth knowledge of project initiation and project management; knowledge of HERMES attested by course attendance; communication skills (represent the project internally and externally, manage stakeholders, resolve conflicts); decisiveness and assertiveness.
- Owns (decisions): decide on project initiation release, decide on execution release, decide on phase release, decide on project closure, decide on project discontinuation, decide on release, decide on closure phase release, steer project, decide on call for tenders, decide on contract award, decide on launch of operation.
- Owns / co-creates (key outcomes): project initiation order, project initiation release milestone and checklist, execution order, execution release milestone and checklist, phase release milestone and checklist, project closure milestone and checklist, project discontinuation checklist, final project evaluation, lessons learned, release milestone and checklist, closure phase release milestone and checklist, tender milestone and checklist, contract award milestone and checklist, launch of operation milestone and checklist, publication, QA and risk report, list of steering project decisions. (Source table 20.)

### Project committee member

- Level: Steering.
- Mission: Supports the project and anchors it in the organization the member represents; the committee is chaired by the project sponsor.
- Responsibilities:
  - Support for the project and its anchoring in the organization represented.
  - Early raising of the concerns of the organization represented.
  - Participation in the development of solutions to problems.
- Powers (Competence):
  - Can request a project review or project audit.
  - Power to issue recommendations: on closure and release of phases to the project sponsor, and on risk-minimizing measures to the project sponsor (for example appointment of project controlling or the quality and risk manager).
  - Can gather all information needed to steer and assess the project.
  - If eligible to vote, may participate in voting.
- Skills: overarching knowledge of the specialist area; in-depth knowledge of the special field represented; business administration knowledge for efficient use of resources; in-depth knowledge of project steering; knowledge of HERMES (ideally by course attendance); ability to work in a team, communicate, and resolve conflicts.
- Owns: no task responsibility (advisory and recommending role). Note: the explicit H4 header for this role was lost in the PDF-to-markdown conversion, but the role content (section 6.4.1.2) is present.

### Quality and risk manager

- Level: Steering.
- Mission: Supports the project sponsor with an independent assessment of the project and recommends measures to achieve the project objectives.
- Responsibilities:
  - Assessment of compliance with the requirements of the core organization.
  - Assessment of the procedure and outcomes of project management, project organization, and cooperation in the project.
  - Comprehensive assessment of the processes of project steering, project management, and project execution for all participants.
  - Evaluation of project outcomes from a qualitative perspective.
  - Assessment of project status and forecasts.
  - Assessment of risks and recommendation of measures to deal with risks and achieve objectives.
  - Transparent reporting to the project sponsor.
- Powers (Competence):
  - Recommendations on closure and release of phases to the project sponsor.
  - Recommendations on measures to the project sponsor.
  - Can gather all information needed to assess the project, with direct access to all project participants including the execution organization.
- Skills: in-depth knowledge of project management (especially controlling, quality assurance, risk management); business administration knowledge; in-depth knowledge of HERMES attested by a certificate; for agile implementation, in-depth knowledge of the agile method used; ability to work in a team, communicate, and resolve conflicts; good writing skills (for example to create reports).
- Owns / co-creates: the QA and risk report (co-created with project sponsor), and participates in many steering checklists (execution release, project closure, phase release, project discontinuation, release, closure phase release, tender, contract award, launch of operation) as a participating role. Independence: provided by an organization that takes no other role in the project and reports directly to the project sponsor.

## Management roles

### Technical committee

- Level: Management.
- Mission: A role group that, under the traditional approach, supports the project management with the evaluation of outcomes. Members raise the concerns of the organizational unit they represent; the project management organizes and chairs the committee meetings.
- Responsibilities:
  - Advice and support for the project management in evaluating specialist issues and outcomes.
  - Support for the project and its anchoring in the organization represented by the member.
  - Early raising of the concerns of the organization represented.
- Powers (Competence):
  - Gives recommendations on outcomes to the project management.
  - Gives recommendations on quality assurance measures to the project management.
  - Can access all required information.
- Skills: in-depth knowledge of the specialist area and special field represented; business administration knowledge for evaluating and prioritizing requirements and assessing options and economic efficiency; ability to work in a team, communicate, and resolve conflicts.
- Owns: no task responsibility (advisory role group, traditional approach only).

### Project management

- Level: Management.
- Mission: Manages the project on behalf of the project sponsor, regardless of the specialist focus of the solution or the chosen development approach.
- Responsibilities:
  - Management of the project to achieve the set objectives (especially time, cost, quality) and procedure objectives.
  - Economical and sustainable use of resources.
  - Management of reporting and provision of comprehensive, regular, and situational information to project steering.
  - Identification and recruitment of stakeholders and analysis of their basic interests.
  - Management of risks and of quality assurance.
  - Compliance with organizational requirements (governance).
  - Timely involvement of responsible controlling and compliance bodies.
  - Arrangement of methods, practices, and tools used in addition to HERMES (except those within the sovereignty of the agile execution organization).
  - Implementation of steering and management decisions.
  - Performance of procurement in accordance with requirements.
  - Verification of compliance by contracting parties with the SLA (service level agreement).
- Powers (Competence):
  - Can access all project information.
  - Authority to use the resources released.
  - Sole project management responsibility and authority to give instructions, without interfering with the sovereignty of the execution organization under the agile approach (within the scope of the execution order).
  - Decision-making power within the framework defined with the project sponsor.
  - In consultation with the project sponsor: division of the project into sub-projects, appointment of sub-project managers, and delegation of management tasks.
- Skills: knowledge of the core organization's requirements (procurement, financing, controlling, security); in-depth project management knowledge (main criterion); in-depth knowledge of HERMES attested by a certificate; good knowledge of the methods and practices used; business administration knowledge to assess options and economic efficiency; decisiveness and assertiveness; managerial skills; communication skills (represent the project, manage stakeholders, resolve conflicts, communicate at the appropriate level); good writing skills (for example project reports).
- Owns (tasks): draw up project execution order; manage risks; deal with problems and benefit from lessons learned; manage and control project; prepare release closure; draw up project management plan; prepare phase release; manage changes; agree on and steer goods/services; manage and inform stakeholders; perform quality assurance; prepare project closure; analyze legal basis; decide on next steps; prepare study; draw up agreement; issue call for tenders; decide on product concept; decide on solution architecture; decide on acceptance; decide on preliminary acceptance; decide on acceptance of migration; decide on ISDP concept.
- Owns / co-creates (key outcomes): execution order, project management plan, project status report, phase report, change status list and change request, solution requirements, detailed specifications, evaluation report, agreement, quote request / offer, stakeholder list and stakeholder interests, review report, final project evaluation, lessons learned, legal basis analysis, list of management project decisions, next steps milestone and checklist, study, tender documentation, product concept milestone and checklist, solution architecture milestone and checklist, acceptance report, acceptance milestone and checklist, preliminary acceptance milestone and checklist, migration acceptance milestone and checklist, ISDP concept milestone and checklist, minutes, release report. (Source table 21.) Staffing rule: must be located with the user and represent the user's interests; provision by partner groups, developers, or operators should be avoided.

### Project support

- Level: Management.
- Mission: Assists the project management in dealing with organizational and administrative matters. Also referred to as the project office (PO).
- Responsibilities:
  - Responsibility for the activities delegated to the role.
- Powers (Competence):
  - Within the scope of the delegated activities, can request, provide, and prepare information, and make arrangements.
- Skills: knowledge of the project environment; in-depth project management knowledge; knowledge of the methods and practices applied in project support's tasks; in-depth knowledge of HERMES attested by a certificate; business administration knowledge; ability to work in a team, communicate, and resolve conflicts; good writing skills and ability to create documentation.
- Owns: no independent task responsibility; participates in the creation of many management outcomes (for example project status report, stakeholder list, checklists, reports) as a participating role.

### Sub-project manager

- Level: Management.
- Mission: Manages a sub-project on behalf of the project management and is responsible for its smooth progress vis-a-vis the project management.
- Responsibilities:
  - Adherence to the guidelines agreed with the project management in the own sub-project.
  - Economical and sustainable use of resources in the own area.
  - Management of reporting in the own sub-project and provision of comprehensive, regular, and situational information to the project management.
  - Implementation of steering and management decisions.
- Powers (Competence):
  - Can access all information relating to the own sub-project.
  - Authority to use the resources released for the sub-project.
  - Sole management responsibility and authority to give instructions in the sub-project, without interfering with the sovereignty of the execution organization under the agile approach.
  - Decision-making power within the scope defined with the project management (within the framework of the project management's powers).
- Skills: knowledge of the project environment; knowledge of the core organization's requirements for the project and operation/application; in-depth project management knowledge; in-depth knowledge of HERMES attested by a certificate; knowledge of the methods and practices used; knowledge of methods and techniques to assess options and economic efficiency; decisiveness and assertiveness; managerial skills; communication skills; adequate writing skills.
- Owns: mirrors the project management's responsibilities within the bounds of its own sub-project; appointed by the project management. Note: in the PDF-to-markdown conversion the project support and sub-project manager descriptions (sections 6.4.2.3 and 6.4.2.4) are interleaved; the content above is reconstructed from lines 6736-6773.

## Execution roles

General rule: the responsibilities, powers, and skills of all execution roles remain the same whether the role sits in a project team or a sub-project team.

### User representative

- Level: Execution.
- Mission: Represents the users and their interests; responsible for clear specialist solution requirements agreed with the specialist departments as a stable basis for implementation and technical success. Acts as the binding communication channel between the execution organization and stakeholders. Appointed by the project sponsor, managed by the project management, but autonomous in specialist and solution-specific decisions covered by the execution order. Under the agile approach, additionally assumes the role of product owner and serves as the interface to the execution organization.
- Responsibilities:
  - Responsibility for the scope of goods/services and the specialist success of the delivery outcomes.
  - Establishment of all solution-specific requirements and responsibility for the solution requirements.
  - Maintaining transparency and making solution requirements available to all involved.
  - Contributing complete specialist requirements and functionality coordinated with the specialist areas and customers; representing stakeholder interests.
  - Maximizing the added value of the development work (maximizing the value of the solution).
  - Ensuring the scope of goods/services and the specialist success of the solution.
  - Involvement of stakeholders per the stakeholder list.
  - Compliance with ISDP requirements.
  - In agile execution, acting as interface to the execution organization.
- Powers (Competence):
  - Can access all required information.
  - Decision on the characteristics of the solution including the quality requirements covered by the execution order.
  - Definition of the acceptance criteria.
  - Collaboration with stakeholders and the execution organization.
  - Participation in defining requirements and concluding SLAs.
- Skills: in-depth knowledge of the specialist area; knowledge of project management and HERMES; in-depth knowledge of traditional and agile development management; knowledge of development management, design, and specification methods and practices; basic business administration knowledge; knowledge of the project environment and core organization requirements; ability to establish, formulate, evaluate, and prioritize requirements and prepare change requests; good writing skills; abstraction and simplification ability; teamwork, communication, conflict resolution; visionary thinking; assertiveness; natural authority.
- Owns (tasks): prepare procurement analysis; prepare call for tenders; evaluate tenders; advocate stakeholder interests; design product concept; prepare solution requirements; execute deployment measures; design deployment concept; realize deployment measures; implement ISDP concept.
- Owns / co-creates (key outcomes): procurement analysis, tender documentation, evaluation report, tender report, stakeholder interests, product concept, situation analysis, solution requirements, deployment concept, deployment measures carried out / realized, project management plan, ISDP concept and ISDP measures realized. (Source table 22.) Staffing rule: must be located with the user; provision by developers or operators should be avoided.

### Operations manager

- Level: Execution.
- Mission: Provides the goods and services agreed with the operator while adhering to deadlines and budgets, and represents the operator side. Manages specialists in the own area.
- Responsibilities:
  - Provision of the goods and services agreed with the operator, on time and on budget.
  - Contribution of the operator's requirements.
  - Compliance with the operator's ISDP requirements.
- Powers (Competence):
  - Can access all required information.
  - Authority to give instructions to the operator with regard to the own specialist areas.
- Skills: in-depth knowledge of operation; knowledge of the core organization's requirements for the project and the operation of the application (technical and organizational); ability to develop requirements, specifications, concepts, and operating documentation; business administration knowledge for assessing options and economic efficiency; in-depth knowledge of HERMES attested by a certificate; good writing skills (operating documentation); teamwork, communication, conflict resolution; management of specialists in the own area.
- Owns (tasks): realize test infrastructure; realize operation; activate operation; integrate the system into operation; design operating concept.
- Owns / co-creates (key outcomes): test infrastructure realized, operating organization realized, operating manual, operating infrastructure realized, operation activated, system integrated, operating concept, service level agreement. (Source table 23.)

### Business analyst

- Level: Execution.
- Mission: Often called the business organizer; forms the interface between the user and the developer/operator partner groups. Establishes, questions, analyzes, and prioritizes user needs and requirements based on business processes and structures, and transforms them into organizational requirements; conversely, takes solution-specific aspects into account in the design of the envisaged organization.
- Responsibilities:
  - Establishment of all organizational requirements and responsibility for them.
  - Definition of the business processes and organizational structure.
  - Ensuring the involvement of various specialists.
- Powers (Competence):
  - Can access all required information.
  - Collaboration with all partner groups.
  - Design, implementation, and activation of the organization.
- Skills: business administration knowledge in organizational theory and for evaluating options and economic efficiency; ability to establish, formulate, evaluate, and prioritize requirements; project management knowledge; in-depth knowledge of HERMES attested by a certificate; teamwork, communication, conflict resolution; good writing skills; management of specialists in the own area.
- Owns (tasks): draw up organization concept; activate organization; establish organizational requirements; implement organization.
- Owns / co-creates (key outcomes): process description, organization concept, business model description, organization description, organization activated, situation analysis, organizational requirements, organization implemented. (Source table 24.) Note: a business analyst with sufficient specialist-area knowledge may also take on the user representative role.

### Developer

- Level: Execution.
- Mission: A comprehensive role covering the product developer and the IT developer in one. Realizes the product or system according to the solution requirements and the preceding concepts, and activates the product or system.
- Responsibilities:
  - Responsibility for realization of the product or system.
- Powers (Competence):
  - Can access all required information.
- Skills: in-depth knowledge of the special field of product or software development; in-depth knowledge of the methods and practices used to create solutions; knowledge of HERMES; teamwork, communication, conflict resolution.
- Owns (tasks): carry out prototyping; activate product; realize product; realize system; prepare system integration; activate system; conduct migration; realize migration procedure.
- Owns / co-creates (key outcomes): prototype documentation and prototype realized, product activated, product developed or adapted, detailed specifications, product documentation, user manual, system concept, solution architecture, system developed or parameterized, integration and installation instructions, interfaces realized, system activated, migration carried out, migration procedure realized. (Source table 25.)

### Execution organization

- Level: Execution.
- Mission: An interdisciplinary role group that applies exclusively under the agile approach in the execution phase. Its composition depends on the project type, the outcomes to be created, and the development method used. The execution organization organizes itself.
- Responsibility, Powers, Skills: all defined by the agile execution method used; HERMES defines none of its own.
- Notes: when setting up the agile project organization, the specialist responsibility of the user representative must be incorporated into the execution organization. Project management responsibility lies with the project management, which may not interfere with the sovereignty of the execution organization. No responsibilities, powers, skills, or relationships are defined by HERMES for this role group.

### ISDP manager

- Level: Execution.
- Mission: Responsible for information security and data protection (ISDP) in the project.
- Responsibilities:
  - Assurance that information security requirements and data protection measures are taken into account and implemented in the project.
  - Promotion of understanding and awareness of ISDP in the project.
- Powers (Competence):
  - Can access all required project information.
  - Issuing of security-related specifications for dealing with data and information during project execution.
- Skills: in-depth knowledge of the special field of ISDP; knowledge of the legal basis and core organization requirements; knowledge of IT standards, architectures, methods, and practices; in-depth knowledge of methods and practices in the own field; business administration knowledge for evaluating options and economic efficiency; process management knowledge; in-depth knowledge of HERMES (preferably attested by a certificate); teamwork, communication, conflict resolution; good writing skills (for example reports).
- Owns (tasks): analyze protection needs; design ISDP concept; transfer ISDP concept.
- Owns / co-creates (key outcomes): protection needs analysis, ISDP concept, ISDP concept transferred. (Source table 26.)

### IT architect

- Level: Execution.
- Mission: Designs the solution architecture of the system to be created; defines the solution components of the system and their interfaces with peripheral systems.
- Responsibilities:
  - Assurance of compliance with existing standards and architecture requirements, and performance of audits.
- Powers (Competence):
  - Authority to give instructions in the architecture context.
  - Decision-making power regarding the solution architecture.
- Skills: knowledge of the specialist area; in-depth knowledge of the special field of IT architecture; in-depth knowledge of IT standards, architectures, methods, and practices; business administration knowledge for evaluating options and economic efficiency; project management knowledge; knowledge of HERMES; teamwork, communication, conflict resolution; very good writing skills (for example solution architecture documentation).
- Owns (tasks): design integration concept; prepare solution architecture; design migration concept; decommission the legacy system.
- Owns / co-creates (key outcomes): integration concept, system concept, solution architecture, migration concept, legacy system removed. (Source table 27.)

### Tester

- Level: Execution.
- Mission: Participates in the creation of test case descriptions, carries out tests, and assesses and logs the outcomes.
- Responsibilities:
  - Support for the test manager in creating test case descriptions.
  - Performance of tests for one or more test objects.
  - Evaluation and recording of test results in the form of test reports.
- Powers (Competence):
  - Can access all required information.
  - Decision-making power to classify test results according to the defect categories defined in the test plan.
- Skills: in-depth knowledge of the specialist area (specialist processes, organizational requirements, solution requirements in the own test area); knowledge of testing and test methods; quick comprehension and thorough working methods; assertiveness; teamwork, communication, conflict resolution.
- Owns: no standalone task responsibility table in the source; contributes to test reports and supports the test manager. Each partner group (user, developer, operator) provides testers in its own area of responsibility.

### Test manager

- Level: Execution.
- Mission: Designs, plans, and coordinates testing; ensures the test fundamentals are developed in the form of the test concept and transfers testing to subsequent operation.
- Responsibilities:
  - Assurance that the various requirements (organizational requirements, solution requirements) regarding system quality are met.
- Powers (Competence):
  - Defines the test methods and test organization.
  - Determines employee and system deployment for testing and orders tests to be conducted.
- Skills: knowledge of the specialist area; in-depth knowledge of the test objects (specialist processes, technology); in-depth knowledge of the special field of quality assurance and testing with the corresponding methods and practices; knowledge of the design and implementation of IT solutions; knowledge of project management; in-depth knowledge of change management; knowledge of HERMES (ideally attested by a certificate); decisiveness and assertiveness; teamwork, communication, conflict resolution; good writing skills (test concepts and test reports).
- Owns (tasks): transfer test infrastructure; design test concept; conduct test.
- Owns / co-creates (key outcomes): test concept, minutes, test infrastructure transferred, test report. (Source table 28.) Each partner group (user, developer, operator) can appoint a test manager in its own area of responsibility.

## Gaps

- Header conversion artifacts: the H4 headers for project committee member (6.4.1.2), and the cleanly separated bodies for project support (6.4.2.3) and sub-project manager (6.4.2.4), were damaged or interleaved in the PDF-to-markdown conversion. The role content was reconstructed from the surrounding text and from the staffing rules in section 6.2.3, but the exact section header text for the committee member role is not present in the source range.
- The developer description states the role covers product developer and IT developer "in one"; HERMES does not list these as separate named roles in this range.
- The tester (6.4.3.8) has no Relationships table in the source range, so its owned outcomes are inferred from the test manager's table and from general statements; no standalone tester task-responsibility list is given.
- The IT architect's Responsibility, Powers, and Skills headers appear out of order in the source (PDF artifact), but the content was matched to the correct sub-fields.
- Some module/task table cells in the source are blank or show only fragments of labels (for example "or", "Sor", "yst", "manage"); these are OCR truncations of the role names (project sponsor, business analyst, ISDP manager) and have been normalized to the correct role names.
