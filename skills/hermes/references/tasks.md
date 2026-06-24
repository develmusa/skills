# HERMES Task Catalog

Every HERMES task, grouped by module. Each entry lists the phase(s) it runs in, the responsible role, the roles involved, the outcomes it produces, and its purpose. Phase "all" means the task runs continuously across the project (Initiation, Concept, Implementation, Deployment, Closure, and the agile Execution phase). The agile Execution phase replaces Concept plus Implementation plus Deployment, so tasks shown for those traditional phases are performed inside Execution under the agile approach.

Use this catalog to know who does what, when, and which artifact each task produces. Deliverable definitions are in [deliverables.md](deliverables.md), roles in [roles.md](roles.md), milestones and states in [phases-and-milestones.md](phases-and-milestones.md).

## Project steering

- **Steer project** | Phases: all | Responsible: Project sponsor | Involved: Project management, Project committee, Quality and risk manager
  Purpose: The sponsor steers the project, ensures fast decision-making, plans and steers decision processes, regulates and monitors reporting, manages superordinate risk, and prioritizes escalated problems. Checks progress against the project management plan and status report.
  Outcomes: QA and risk report; List of steering project decisions

- **Decide on project initiation release** | Phases: Initiation | Responsible: Project sponsor | Involved: Project manager, Core organization
  Purpose: First regular decision in the project. The project is formally established and starts the initiation phase; a project manager is assigned to draw up the project initiation order and resources for initiation are released.
  Outcomes: Project initiation order; Project initiation release milestone; Project initiation release checklist; List of steering project decisions

- **Decide on execution release** | Phases: Initiation | Responsible: Project sponsor | Involved: Project manager, Core organization, Stakeholders
  Purpose: Starts solution development, puts the adapted project organization into effect, and releases resources for the next phase. Enables work in the Concept phase (traditional) or Execution phase (agile), or defers or terminates the project.
  Outcomes: Execution release milestone; Execution release checklist; Execution order; List of steering project decisions

- **Decide on phase release** | Phases: Concept, Implementation | Responsible: Project sponsor | Involved: Project manager, Core organization, Controlling and QA/risk bodies
  Purpose: In the traditional approach, creates the prerequisite for the next phase. Phase outcomes are accepted or rejected, the current phase is completed, and the next phase plus resources are released; the project is terminated if objectives cannot be met.
  Outcomes: Phase release checklist; Phase release milestone; QA and risk report; List of steering project decisions

- **Decide on release** | Phases: Execution | Responsible: Project sponsor | Involved: Project manager, Core organization or program, Controlling and QA/risk bodies
  Purpose: In the agile approach, an optional decision (mandatory only if the project management plan says so) that reviews the current release, accepts or rejects it, and releases the next release.
  Outcomes: Release milestone; Release checklist; QA and risk report; List of steering project decisions

- **Decide on closure phase release** | Phases: Deployment, Execution | Responsible: Project sponsor | Involved: Project manager, Core organization, Controlling and QA/risk bodies
  Purpose: Concludes the provision of goods or services within solution development and enables the closure phase. Outcomes are checked and accepted or rejected; under the agile approach the execution organization is dissolved.
  Outcomes: Closure phase release checklist; Closure phase release milestone; QA and risk report; List of steering project decisions

- **Decide on project closure** | Phases: Closure | Responsible: Project sponsor | Involved: Project manager, Controlling and compliance bodies, Project committee
  Purpose: Last regular and formal decision. The project organization is dissolved and the project ends; the sponsor checks that all outcomes are documented and available and approves or rejects the final project evaluation.
  Outcomes: Project closure checklist; Project closure milestone; QA and risk report; List of steering project decisions

- **Decide on project discontinuation** | Phases: Concept, Implementation, Deployment | Responsible: Project sponsor | Involved: Project manager, Controlling and QA/risk bodies, Core organization, Legal department, Project committee
  Purpose: Made before objectives are achieved. The project organization is dissolved and the project is terminated in an orderly manner. Possible only within solution development (after execution release, before closure phase release); a premature, unplanned closure.
  Outcomes: Project discontinuation checklist; Final project evaluation; Lessons learned; Project closure milestone; List of steering project decisions

## Project management

- **Manage and control project** | Phases: all | Responsible: Project management | Involved: User representative, Project support, Business analyst
  Purpose: Coordinates and manages participants, monitors status, updates planning, and reports to project steering. Fleshes out tasks with work orders, runs target/actual comparison, forecasts effort, cost, and deadlines, and takes corrective measures.
  Outcomes: Work order; Project status report; Project management plan; Solution requirements; Detailed specifications; Minutes

- **Draw up project management plan** | Phases: Initiation, Execution | Responsible: Project management | Involved: Project sponsor
  Purpose: Determines overall project planning and the essential rules: risk, change, and quality management, the review and procurement plans, the project and execution organization, role assignment, and (agile) whether the release decision is mandatory.
  Outcomes: Project management plan

- **Draw up project execution order** | Phases: Initiation | Responsible: Project management | Involved: Project sponsor, Stakeholders, Project participants, Controlling and compliance bodies
  Purpose: Creates the prerequisites for the execution release decision. Information from the study and other initiation outcomes is detailed in the execution order (objectives, execution specifications, risks, planning); liabilities are agreed between sponsor and project manager.
  Outcomes: Execution order

- **Prepare phase release** | Phases: Initiation, Concept, Implementation, Deployment | Responsible: Project management | Involved: User representative, Project support
  Purpose: Summarizes outcomes for decision-makers and plans the next phase in detail. The phase report shows that all required outcomes exist in the required quality and is the basis for the sponsor's phase release decision.
  Outcomes: Phase report; Project management plan; Project status report

- **Prepare release closure** | Phases: Execution | Responsible: Project management | Involved: User representative, Project support
  Purpose: For an agile release closure, summarizes outcomes for reporting. The release report describes the closing release, highlights benefits, notes known errors, and is the basis for the sponsor's decision on any next release.
  Outcomes: Release report; Project management plan; Project status report

- **Prepare project closure** | Phases: Closure | Responsible: Project management | Involved: Project support
  Purpose: Carries out and documents all final formal, organizational, and administrative activities; records open and future issues; forwards documents and outcomes to the competent bodies; transfers system documentation; compiles the final project evaluation.
  Outcomes: Final project evaluation; Lessons learned

- **Manage risks** | Phases: all | Responsible: Project management | Involved: Project support
  Purpose: Identifies risks early and defines measures for project success, covering project risks and operational risks. Risks are analyzed and evaluated, a strategy (avoid, reduce, outsource, accept) and measures defined, and assessments communicated.
  Outcomes: Project status report; Project management plan

- **Perform quality assurance** | Phases: all | Responsible: Project management | Involved: User representative, Project support
  Purpose: Ensures outcomes meet the required quality through checking (content and formal review of documents and process compliance). Testing is in the Tests module. Reviews follow the review plan and are recorded in the review report.
  Outcomes: Review report; Project management plan

- **Manage changes** | Phases: Concept, Implementation, Deployment, Execution | Responsible: Project management | Involved: User representative, Execution organization
  Purpose: In traditional development, ensures new or changed requirements are identified, assessed, and decided. For all approaches it ensures changes are documented. There is no formal change management in the initiation phase.
  Outcomes: Change status list; Change request; Solution requirements; Project management plan

- **Manage and inform stakeholders** | Phases: all | Responsible: Project management | Involved: Project sponsor, User representative, Business analyst, Project support
  Purpose: Identifies stakeholders, analyzes their interests, wins them for the project, and keeps an institutionalized information flow (including project marketing). Plans communication objectives and measures and reviews their impact.
  Outcomes: Stakeholder list; Stakeholder interests; Project management plan

- **Deal with problems and benefit from lessons learned** | Phases: all | Responsible: Project management | Involved: Project sponsor, User representative
  Purpose: Level-appropriate handling of problems and continual learning from experience. Problems are identified, evaluated, and solved early or escalated; lessons learned are continuously documented and passed to the sponsor for the core organization.
  Outcomes: Lessons learned

- **Agree on and steer goods/services** | Phases: Concept, Implementation, Deployment, Execution | Responsible: Project management | Involved: Service providers, Controlling and compliance bodies, User representative, Project partners
  Purpose: The service level agreement regulates the relationship with internal or external service providers; deviations in delivery are identified and handled. HERMES refers to project agreements, SLAs, and contracts collectively as an agreement.
  Outcomes: Agreement; Evaluation report; Quote request; Offer

## Project foundations

- **Prepare study** | Phases: Initiation | Responsible: Project management | Involved: User representative, Business analyst, IT architect, Project support
  Purpose: Sets objectives, defines rough requirements, and establishes and evaluates solution options so the decision on next steps can be made. Selects and adapts a suitable scenario, fixes the traditional or agile approach, and roughly plans the project and milestones.
  Outcomes: Study; Stakeholder list

- **Decide on next steps** | Phases: Initiation | Responsible: Project management | Involved: Project sponsor, Stakeholders, Those involved in the study
  Purpose: Fixes the choice of solution option, scenario, approach (traditional or agile), and project value, enabling the project management plan and execution order. Made only if continuing makes sense.
  Outcomes: Next steps milestone; Next steps checklist; Study; List of management project decisions

- **Analyze legal basis** | Phases: Initiation | Responsible: Project management | Involved: Project support
  Purpose: Ensures legal requirements are met or that measures to create them are defined. Documents the existing legal basis for the future system, analyzes gaps and imminent changes, and assesses impact on the study and execution.
  Outcomes: Legal basis analysis

- **Analyze protection needs** | Phases: Initiation | Responsible: ISDP manager | Involved: Project management
  Purpose: Determines the information security and data protection requirements; mandatory for every IT project so ISDP is considered from the start. If enhanced protection is needed, an ISDP concept with in-depth risk analysis must follow.
  Outcomes: Protection needs analysis

- **Prepare procurement analysis** | Phases: Initiation | Responsible: Project management | Involved: Controlling and compliance bodies for procurement, Procurement/purchasing unit
  Purpose: Compiles procurement-relevant information and requirements and establishes the basis for selecting the procurement procedure. Clarifies what is procured by whom, the market situation, legal requirements, and the procurement plan.
  Outcomes: Procurement analysis

- **Carry out prototyping** | Phases: Initiation, Concept, Implementation, Execution | Modules: Project foundations, Product, IT system | Responsible: Developer | Involved: User representative, IT architect
  Purpose: A risk-minimizing measure: simplified but largely functional solution approaches are built and tested to check feasibility, usability, acceptance, appearance, or dimensions. Findings feed into further planning; the prototype may be reusable or disposable.
  Outcomes: Prototype realized; Prototype documentation

## Organization

- **Establish organizational requirements** | Phases: Concept, Execution | Responsible: Business analyst | Involved: User representative
  Purpose: Develops all organizational requirements for the solution. A deeper situation analysis shows the need for action; the requirements build on the study and execution order and stay solution-neutral, forming the basis for the organization concept.
  Outcomes: Organizational requirements; Situation analysis

- **Draw up organization concept** | Phases: Concept, Execution | Responsible: Business analyst | Involved: User representative
  Purpose: Describes the new organization and the procedure for realizing it: business model, organizational and process structure (core, management, support processes), and the changes to the existing organization. Options may be described and evaluated.
  Outcomes: Organization concept; Business model description; Process description; Organization description

- **Advocate stakeholder interests** | Phases: Initiation, Concept, Implementation, Deployment, Execution | Modules: Organization, Product, IT system | Responsible: User representative | Involved: User representative
  Purpose: Brings stakeholder requirements and the user perspective into solution development to promote acceptance. The user representative gathers suggestions, feeds them in (via change management or agile development), and keeps stakeholder interests current.
  Outcomes: Stakeholder interests

## Product

- **Design product concept** | Phases: Concept, Execution | Responsible: User representative | Involved: Business analyst
  Purpose: Forms the basis for realizing the product. Describes the product with its components and structure, fleshing out the requirements and the selected solution option as a specification; product options may be described and evaluated.
  Outcomes: Product concept

- **Decide on product concept** | Phases: Concept, Execution | Responsible: Project manager | Involved: Controlling and compliance bodies, Developer
  Purpose: Prerequisite for developing or adapting products or services; confirms conformity with the core organization's requirements and needs. The product concept is checked by the responsible bodies (and, for procurement, reviewed before and after evaluation).
  Outcomes: Product concept milestone; Product concept checklist; List of management project decisions

- **Realize product** | Phases: Implementation, Execution | Responsible: Developer | Involved: User representative, Business analyst
  Purpose: Develops or adapts the product so it meets the solution requirements and is ready for preliminary acceptance. Detailed specifications are derived, the product is procured and adapted or custom-built, documentation and user manual produced, and QA performed.
  Outcomes: Product developed or adapted; Detailed specifications; Product documentation; User manual

- **Activate product** | Phases: Deployment, Execution | Responsible: Developer | Involved: User representative, Business analyst
  Purpose: After the launch of operation decision, the developer activates the product for productive use including all components needed for operation, and supports users during the initial utilization period until acceptance.
  Outcomes: Product activated

## IT system

- **Prepare solution requirements** | Phases: Concept, Execution | Modules: IT system, Product | Responsible: Business analyst | Involved: User representative, Stakeholders, Project manager
  Purpose: Prepares all relevant requirements for the solution and its deployment, operation, and use. In traditional development they feed the solution architecture or product concept; in agile they are the prioritized cornerstone for successive work.
  Outcomes: Solution requirements; Situation analysis

- **Prepare solution architecture** | Phases: Concept, Implementation, Execution | Responsible: IT architect | Involved: Operations manager, Developer, Business analyst, User representative
  Purpose: Creates the basis for implementing the system. The system concept establishes and evaluates several approaches, then the selected ones are combined into a solution architecture describing the system, its components, structure, and interfaces.
  Outcomes: Solution architecture; System concept

- **Decide on solution architecture** | Phases: Concept, Execution | Responsible: Project manager | Involved: Controlling and compliance bodies, IT architect
  Purpose: Prerequisite for developing or parameterizing systems; confirms conformity with the core organization's IT architecture. Checked by the responsible bodies (and, for procurement, reviewed before and after evaluation).
  Outcomes: Solution architecture milestone; Solution architecture checklist; List of management project decisions

- **Design integration concept** | Phases: Concept, Execution | Responsible: IT architect | Involved: Developer, Operator, Stakeholders
  Purpose: Compiles and conceptualizes integration of the system into the operating infrastructure, specifying interfaces with peripheral systems and transfer between operating environments. If procured, final design follows contract award.
  Outcomes: Integration concept

- **Realize system** | Phases: Implementation, Execution | Responsible: Developer | Involved: User representative, Business analyst, IT architect
  Purpose: Develops or parameterizes the system so it meets the solution requirements and is ready for integration. Detailed specifications are created, the system procured and built or parameterized, QA and developer testing arranged, and documentation and user manual produced.
  Outcomes: System developed or parameterized; Detailed specifications; System concept; Solution architecture; User manual

- **Prepare system integration** | Phases: Implementation, Execution | Responsible: Developer | Involved: Operations manager, IT architect, Business analyst
  Purpose: Prepares integration so the operator can integrate the system into operation. Interfaces with peripheral systems and necessary adjustments are realized, and the integration and installation instructions are drawn up.
  Outcomes: Interfaces realized; Integration and installation instructions; Detailed specifications; Solution architecture

- **Activate system** | Phases: Deployment, Execution | Responsible: Developer | Involved: Operations manager, User representative, Business analyst
  Purpose: Prerequisite for activating operation. After the launch of operation decision the developer activates the system, supports the initial utilization period, fixes bugs, and takes stabilization measures if needed.
  Outcomes: System activated

## Procurement

- **Prepare call for tenders** | Phases: Concept, Execution | Responsible: Project management | Involved: Controlling and compliance bodies, Procurement/purchasing unit
  Purpose: Prepares the tender documentation in enough detail to issue a formally correct call, obtain comparable offers, and run a comparable evaluation. Produces specifications, list of criteria, and draft contract.
  Outcomes: Tender documentation

- **Decide on call for tenders** | Phases: Concept, Execution | Responsible: Project sponsor | Involved: Body in charge of tenders, Controlling and compliance bodies, Project manager
  Purpose: Creates the prerequisite for publishing the call for tenders. After the decision the tender documentation is published, or sent out in an invitation procedure.
  Outcomes: Tender milestone; Tender checklist; List of steering project decisions

- **Issue call for tenders** | Phases: Concept, Execution | Responsible: Project management | Involved: Tenderers, Procurement/purchasing unit
  Purpose: Conducts the tender by a specific, transparent procedure. Publication (on simap) informs and invites an unrestricted group of tenderers; questions are answered and incoming tenders collected.
  Outcomes: Tender documentation; Offer

- **Evaluate tenders** | Phases: Concept, Execution | Responsible: Project management | Involved: Those in charge of evaluation, Controlling and compliance bodies for procurement
  Purpose: After the deadline, tenders are opened, a tender report created, and offers evaluated against the criteria. The evaluation report consolidates the results and the proposal of those in charge.
  Outcomes: Evaluation report; Tender report

- **Decide on contract award** | Phases: Concept, Execution | Responsible: Project sponsor | Involved: Core organization, Controlling and compliance bodies for procurement
  Purpose: Creates the prerequisite for publishing the award and preparing the contract with the successful tenderer. Tenderers are informed of the result and the award is published.
  Outcomes: Contract award milestone; Contract award checklist; Publication; List of steering project decisions

- **Draw up agreement** | Phases: Concept, Implementation, Execution | Responsible: Project management | Involved: Project sponsor, User representative, Project support
  Purpose: Drawn up from the tender documentation, draft contract, terms, and offer. A project agreement, contract, or SLA governs cooperation between participants and can span one or more phases.
  Outcomes: Agreement

## Tests

- **Design test concept** | Phases: Concept, Execution | Responsible: Test manager | Involved: Tester, User representative, Operations manager, Business analyst, Developer
  Purpose: Creates the prerequisites for systematic, efficient testing. Establishes quality features, test objectives and types, infrastructure, test objects, organization, test case descriptions, and the test plan; jointly accepted by user, developer, and operator.
  Outcomes: Test concept

- **Realize test infrastructure** | Phases: Implementation, Execution | Responsible: Operations manager | Involved: User representative, Business analyst, Test manager
  Purpose: Provides everything needed to run tests and collect and evaluate results (test system, test data, test tools). Prepared per the test concept, checked for readiness via QA, and released for testing.
  Outcomes: Test infrastructure realized

- **Conduct test** | Phases: Implementation, Deployment, Execution | Responsible: Test manager | Involved: Tester, User representative, Operations manager, Business analyst, Developer
  Purpose: Ensures the system meets the stipulated requirements. Covers the test system, integrated system, realized product, and realized migration procedure; results are entered and evaluated in the test report and tests repeated until quality criteria are met.
  Outcomes: Test report; Test concept

- **Transfer test infrastructure** | Phases: Closure | Responsible: Test manager | Involved: Project management
  Purpose: Transfers the test infrastructure and test concept to the core organization so tests can be run for corrections and further development during use and maintenance. Done after acceptance, before project closure.
  Outcomes: Test infrastructure transferred; Test concept; Minutes

## Deployment organization

- **Design deployment concept** | Phases: Concept, Execution | Responsible: Project management | Involved: Developer, Stakeholders, User representative
  Purpose: Compiles and conceptualizes all relevant deployment aspects: how deployment happens (fixed date or phased), the deployment organization and support roles, deployment measures, organizational change management, training, acceptance rules, and release criteria for launch of operation.
  Outcomes: Deployment concept; Project management plan

- **Realize deployment measures** | Phases: Deployment, Execution | Responsible: Project management | Involved: Deployment organization (superusers), Developer
  Purpose: Realizes the deployment measures and deployment organization per the deployment concept, including emergency measures and emergency organization (for example developing training and training superusers).
  Outcomes: Deployment measures realized

- **Execute deployment measures** | Phases: Deployment, Execution | Responsible: Project management | Involved: Deployment organization (superusers), Users
  Purpose: Carries out the realized, prepared deployment measures (for example user training) per the deployment planning, creating one of the bases for launch of operation. May happen several times in agile development.
  Outcomes: Deployment measures carried out

- **Decide on preliminary acceptance** | Phases: Deployment, Execution | Responsible: Project manager | Involved: User representative, Developer, Operator, Tester
  Purpose: Creates the basis for executing deployment measures and the subsequent launch of operation with acceptable risks. QA measures (tests and inspections) give users, developers, and operators assurance the transfer will likely succeed.
  Outcomes: Preliminary acceptance milestone; Preliminary acceptance checklist; Acceptance report; List of management project decisions

- **Implement organization** | Phases: Deployment, Execution | Responsible: Business analyst | Involved: User representative
  Purpose: Fully realizes the organization so the organizational and personnel prerequisites exist for activation. The business model, process, and organization descriptions are completed and measures (channels, role assignments, recruitment) realized.
  Outcomes: Organization implemented; Organization description; Process description

- **Activate organization** | Phases: Deployment, Execution | Responsible: Business analyst | Involved: User representative
  Purpose: Puts the new organization into effect; employees work in new roles under the new business model and processes. After the launch of operation decision, the project organization accompanies and supports it until acceptance.
  Outcomes: Organization activated

- **Decide on launch of operation** | Phases: Deployment, Execution | Responsible: Project sponsor | Involved: Project manager, User representative
  Purpose: Prerequisite for activating the product or system and for productive use. The sponsor decides based on preliminary acceptance, migration acceptance, executed deployment measures, and the release criteria in the deployment concept.
  Outcomes: Launch of operation milestone; Launch of operation checklist; List of steering project decisions

- **Decide on acceptance** | Phases: Deployment, Execution | Responsible: Project manager | Involved: Project sponsor, Developer or supplier, Operator, User
  Purpose: Concludes the provision of goods or services and is the basis for closure phase release. The solution and documentation are definitively transferred to the application (and operating) organization, after activation and an initial operating period.
  Outcomes: Acceptance milestone; Acceptance report; Acceptance checklist; List of management project decisions

## IT migration

- **Design migration concept** | Phases: Concept, Execution | Responsible: IT architect | Involved: Business analyst, Developer
  Purpose: Creates the basis for transferring the old system to the new one and decommissioning the legacy system. Focuses on data migration (quantities, frequencies, quality), feasibility, economy, timing, archiving, and data security and protection.
  Outcomes: Migration concept

- **Realize migration procedure** | Phases: Implementation, Execution | Responsible: Developer | Involved: Operations manager, Business analyst, IT architect
  Purpose: Realizes the migration procedures to the point where migration to the productive system can be carried out. Detailed specifications are derived, the test infrastructure realized, archiving and data protection considered, and the procedure documented and reviewed.
  Outcomes: Migration procedure realized; Detailed specifications

- **Conduct migration** | Phases: Deployment, Execution | Responsible: Developer | Involved: Operations manager, Business analyst
  Purpose: Carries out the migration using the selected procedures per the migration concept. After migration, its quality is checked and necessary adjustments made.
  Outcomes: Migration carried out

- **Decide on acceptance of migration** | Phases: Deployment, Execution | Responsible: Project manager | Involved: User representative, Operator, Developer
  Purpose: Shows the migration succeeded and is a prerequisite for launch of operation. If migration quality criteria are met, use of the new system is released. Requires preliminary acceptance and precedes launch of operation.
  Outcomes: Migration acceptance milestone; Migration acceptance checklist; Acceptance report; List of management project decisions

- **Decommission the legacy system** | Phases: Closure | Responsible: Operator | Involved: Developer, Core organization, Controlling and compliance bodies
  Purpose: After productive deployment of the new system, the legacy system or old version is decommissioned so data security, data protection, and the specifications of controlling and compliance bodies are met, per the migration concept.
  Outcomes: Legacy system removed

## IT operation

- **Design operating concept** | Phases: Concept, Execution | Responsible: Operator | Involved: Project manager, Controlling and compliance bodies, Stakeholders, External operators
  Purpose: Describes the future operating infrastructure and organization and the procedure to realize them. Based on solution requirements and architecture, defines the operating organization, processes, infrastructure, and tools; incorporates the SLA.
  Outcomes: Operating concept; Service level agreement

- **Realize operation** | Phases: Implementation, Execution | Responsible: Operator | Involved: Project manager, Operator's competent bodies
  Purpose: Realizes the operating infrastructure, organization, and tools needed to integrate the system, per the operating concept. Components and measures are checked via QA and the operator creates an initial operating manual.
  Outcomes: Operating infrastructure realized; Operating organization realized; Operating manual

- **Integrate the system into operation** | Phases: Implementation, Execution | Responsible: Operations manager | Involved: Developer
  Purpose: Creates the prerequisites for testing and preliminary acceptance. The realized system is integrated technically and organizationally into the operating infrastructure (possibly in several steps) and links to peripheral systems are activated.
  Outcomes: System integrated; Operating manual

- **Activate operation** | Phases: Implementation, Execution | Responsible: Operator | Involved: User representative, Project manager, Users
  Purpose: Releases the system for initial use and later acceptance. The activated system, operating tools, and processes are put into productive use; the operator ensures operation per the SLA. May happen once or, in agile, several times.
  Outcomes: Operating manual

## ISDP (information security and data protection)

- **Design ISDP concept** | Phases: Concept, Execution | Responsible: ISDP officer | Involved: Controlling and compliance bodies, Project manager
  Purpose: Creates the prerequisites for realizing and transferring the ISDP requirements. Completes the ISDP requirements with a detailed risk analysis and defines protection measures, based on the study, protection needs analysis, and requirements.
  Outcomes: ISDP concept

- **Decide on ISDP concept** | Phases: Concept, Execution | Responsible: Project manager | Involved: Controlling and compliance bodies, Project sponsor
  Purpose: Confirms compliance with the core organization's information security and data protection requirements. The ISDP concept is checked by the responsible bodies (and, for procurement, reviewed after evaluation).
  Outcomes: ISDP concept milestone; ISDP concept checklist; List of management project decisions

- **Implement ISDP concept** | Phases: Implementation, Execution | Responsible: ISDP officer | Involved: Developer, Project manager, Project sponsor
  Purpose: Implements the protection measures defined in the ISDP concept (in modules such as organization and IT system). Implemented measures are a prerequisite for preliminary acceptance; status and residual risks are documented and approved by the sponsor.
  Outcomes: ISDP measures realized; ISDP concept

- **Transfer ISDP concept** | Phases: Deployment, Execution | Responsible: ISDP officer | Involved: Controlling and compliance bodies, Project sponsor, Core organization's executive board
  Purpose: Updates, checks, and transfers the ISDP concept from the project to the core organization; a prerequisite for the launch of operation decision, with which the sponsor assumes responsibility for the operation risks.
  Outcomes: ISDP concept transferred; ISDP concept
