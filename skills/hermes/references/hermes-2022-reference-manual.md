# HERMES

## REFERENCE MANUAL-Project management

Outcome-oriented project management method for various types of projects 2022 edition

* * *

Foreword

The evolution of HERMES

The HERMES project management method is a successful product that successively adapts to
the spirit of the times and reflects each evolutionary stage of the understanding of the project.
This is one of the reasons why HERMES has been able to hold its own for over 50 years.

As of version 2022, HERMES can be used to manage both traditional and agile or scaled agile
projects.

This is made possible by decoupling project and development management, which allows the
security of a structured project approach to be combined with the many advantages of selforganized agile or scaled agile development management.

The program management appendix to this reference manual allows agile and traditional
projects to be managed together as part of a program.

In an effort to be able to adapt the project management method very quickly to changing market conditions and user requirements, we have optimized the development of the method and
migrated it to a digital platform.

This makes HERMES online ( [www.hermes.admin.ch](http://www.hermes.admin.ch/)) the central information platform for the
method. In HERMES online, you can also register for the newsletter, make change requests,
or give feedback in general.

We would like to thank everyone who has helped and is still helping us to keep this method
up-to-date, simple, and clear, and we wish you much success in using it.

HERMES Officer

Federal Chancellery FCh

Digital Transformation and ICT Steering
[www.bk.admin.ch](http://www.bk.admin.ch/)

[www.bk.admin.ch](http://www.bk.admin.ch/)

* * *

# Impressum

## Overall responsibility and published by

Federal Chancellery FCh, Digital Transformation and ICT Steering DTI

## "Digital First" principle

The HERMES publication process follows the "Digital First" principle. Consequently, [www.her-](http://www.her-/) mes.admin.ch is the leading source; only the content published there is binding and decisive for certification.

## Copyright and reservation

HERMES is an open standard of the Swiss Federal Administration. The Swiss Confederation, represented by DTI, is the copyright holder. Personal use is governed by Article 19 of the Federal Act on Copyright and Related Rights (Federal Copyright Act, CopA, SR 231.1). This edition may contain shortcomings or inconsistencies. Liability for damage and warranty for defects on the part of the Swiss Confederation is excluded, unless otherwise provided for by mandatory statutory provisions of the applicable law. Errors, problems, or suggested changes can be communicated to the publisher online via HERMES at [www.hermes.admin.ch](http://www.hermes.admin.ch/).

## Note on gender equality in language

To make it more readable and comprehensible, this manual refers to roles and people in forms which are independent of a person's gender and positions in an organization. These formula- tions explicitly include all other genders in their respective function.

## Support

Email: [hermes@bk.admin.ch](mailto:hermes@bk.admin.ch)

## eGovernment standards

eCH Standard 0054

## Available via

HERMES online ( [www.hermes.admin.ch](http://www.hermes.admin.ch/)). In the interest of sustainability, printed products are no longer offered.

3/244

* * *

# Edition

2022 edition / 3rd printing (revised) 09.03.2026

4/244

* * *

# Preface

"Small deeds done are better than great deeds planned." (Peter Marshall) Agile methods have proven superior to traditional approaches in many areas of our fast-moving times. It therefore makes sense that they are also being used more frequently by the public authorities and are reflected in HERMES. However, the experience of the Swiss Federal Audit Office (SFAO) shows that consistent application of a method is not a sufficient guarantee for successful project implementation. Other aspects are also important. We therefore encourage you to keep the following in mind: Any transformation depends on cultural change. From the outset, raise the awareness of everyone involved that innovation is not driven by technology alone, but rather starts with the individual employee. Encourage a willingness to engage in dialogue, learn to live with uncertainty, question taboos, and allow for errors. A zero- error culture is fatal - not only, but especially for the agile world. Focus on the business and the end user. As the project sponsor, steer the project by focusing on the expected business benefits and by ensuring that reporting is consistently aligned with those benefits. For example, use milestones to define when you want to realize which benefit and leave project execution primarily to the project team. With regard to the Administration's transformation plans, do not hesitate to question existing organizations and processes. Motivate those involved to develop the solution together with the users. In the case of the Administration, users include citizens, companies, subsidy recipients, but also cantons and communes. Dare to ask everyone involved to work together so that the end result is a continuous end-to-end process. Assemble the puzzle pieces in your plan without any gaps. Orchestrate your projects in such a way that they jointly make a valuable contribution to achiev- ing your strategic objectives. Involve architecture, ICS1 and security officers at an early stage sothattheirrequirementsareactuallytakenintoaccount. Finally,makesureyouhavesufficient explicit test cases for the internal controls and security elements and that they are automated to the extent possible. Provide your organization with the necessary powers. Securekeyresourcesinatimelyandsustainablemannerandunambiguouslyconfirmtheirrole- specific responsibilities. Make sure that the user representative (product owner) has both the expertise and the necessary decision-making powers, and never start without a mature quality and risk management system. We will examine these aspects during our audits in the Federal Administration, and we look forward to exploring this new world together with all users. If you have any questions, please contact us at [info@efk.admin.ch](mailto:info@efk.admin.ch). Swiss Federal Audit Office SFAO [www.efk.admin.ch](http://www.efk.admin.ch/)

1. The internal control system (ICS) of the Federal Administration, phased in between 2007 and 2008
   5/244

* * *

# A Method overview

## A.1 HERMES project management-The big picture

The outcome diagram (see the figure below) provides a rough big picture for the outcomes of HERMES project management.

Project steering Project mgmt Project foundations Project initiation order Stakeholder list **Initiation** Legal basis analysis Study Protection needs analysis Procurement analysis Project mgmt plan Execution order Project steering Project mgmt Organization Product IT system Procurement Tests Deploymentorganization IT migration IT operation ISDP Phase-independent Situation analysis Situation analysis Situation analysis Project managementOrganizational requirements Solution requirementsSolution requirements plan **Concept** Stakeholder concept ProductconceptSystem concept Tender Operating conceptISDP concept list Organization documentation Project status report Business model description Iteration Iteration Evaluation reportTest concept Service level agreement Process description Organization description Solution architectureIntegration conceptAgreement Deployment concept Migration concept Phase report Detailed specificationsDetailed specificationsDetailed specifications infrastructure Test Deployment measures Detailed specifications Operating infrastructure Operating manual ISDP measures **Execution** Release report Process Organization realized realized realized realized QA and risk report description description Product developed/ System developed/ Interfaces realized Test report Migrationprocedure System integrated Operating organization ISDP concept adapted parameterized realized realized **Implementation** Change request Organizationimplemented User manual User manual installationinstructionsTest concept Integration and Change status list Acceptance report

Agreement Organization activated Productactivated Systemactivated Deployment measures Migrationcarried out Operation activated ISDP concept transferred carried out **Deployment** Project decisions Acceptance report ISDP concept Lessons learned Legacysystem Test concept Final project evaluation infrastructure transferred removed **Closure** HERMES phase model for traditional and agile projects

Figure 1: Overview of the HERMES modules and the essential outcomes along the phases

HERMES is an outcome-oriented process method; the focus is on the outcomes. The overview shows the essential outcomes of the individual modules throughout each phase as well as the rough dependencies and interrelationships. The oval iteration arrows in red symbolize the core of the iteration, the driving character of the product and IT system modules during agile devel- opment. The outcomes of the other modules are developed in sync with that iteration, likewise iteratively and incrementally.

## A.2 What is HERMES project management?

HERMES project management is the holistic management method for carrying out projects and programs of various types in many fields of activity, such as organization adjustment, IT, and service and product development.

HERMES project management supports the steering, management, and execution of projects and accompanies the further development of organizational structures, products and services, IT and logistics systems, infrastructures, etc. with various levels of complexity and different features. A project can be divided into subprojects that deal with different aspects of the same project (e.g. subprojects for users, creators, operators for organization, IT, legal bases). Long- term or complex projects do not necessarily have to be structured as programs. They can be carried out as projects with implementation units.

As a method, HERMES project management has a clear, easy-to-understand structure with

6/244 common terminology for all participants, has a modular design, and can be expanded. It is continuously updated and further developed.

# A.3 Project sizes supported by HERMES

To ensure the completeness of both the information and the method itself, the full scope of HERMES project management is designed for large projects with a high level of complexity. This is not an appropriate fit for every project, however. Using the user-defined scenarios func- tionality provided in HERMES online, the standard scenarios are first adjusted via the sizing function according to the actual project value determined. The project value is determined from several parameters that can be entered by the user. Based on the determined value of the project, the sizing function provides the project manager with a scenario tailored to the size of the project. In a second step, the scenario - once adapted to the appropriate scope - can optionally be further customized. This is done using the tailoring function. At the end, the customized scenario can be downloaded, including the adapted structure plans and templates.

# A.4 Use of HERMES project management in practice

The HERMES project management method supports two approaches: The traditional phased approach as described in systems engineering1, hereinafter referred to as "traditional", and the iterative and incremental approach2, hereinafter referred to as "agile". The method provides a frameworkthatmakesitpossibletoembeddifferentapproachesandthecorrespondingproject- specific methods in a uniform way. The figure below shows the functional use of the HERMES project management method, illus- trates the prerequisites for the project roles involved in carrying out the project, and shows how the application of the method requires other relevant methodological training or at least sound project practice: The project management method channels knowledge acquired in different areas, enhances it with HERMES-specific elements and terminology, and provides a homoge- neous framework for all projects.

1. The traditional approach set out in Systems Engineering, ETHZ, Walter F. Daenzer
2. Based on e.g. Extreme Programming or SCRUM: Development methods used mainly for agile software devel- opment. The focus is on the development process; specific project management aspects are not defined.
   7/244

* * *

Projects Experience & practice Practice

Experience Project management method HERMES Sustainability Manuals / Online Document templates Training / Certification Governance Agile expertise

Project management expertise

## HERMES project management in action

Daily business

Figure 2: How HERMES project management works in practice

HERMES courses and certifications consolidate the required competence and expertise. This ensuresthesamemannerofreportingandcommunicationbothwithintheprojectandinrelation to the core organization, while at the same time meeting the accompanying framework require- ments of HERMES project management (see Section "User Information", e.g. Governance). In this way, projects of all types can be anchored uniformly within the core organization, exhibiting thesamelevelofintegrationintotheoperationalprocessesregardlessoftheselectedapproach. The project teams are supported in applying the approach selected for the project and in deliv- ering the outcomes required by the project management method in a lean manner. This does not curtail the traditional and agile methods, but additional, binding method components are required and defined with regard to roles, tasks, or outcomes. The HERMES framework lays a structure over the selected approach that provides a uniform picture of all projects externally and communicates the same language internally to all project participants. This makes the se- lected project approach completely autonomous as such, so that it can be integrated into any organization. Independently of the project type or approach, both planning and controlling are largely done in the same way.

# A.5 The interfaces of HERMES project management

HERMES project management covers the entire project life cycle and is outcome-oriented. It guarantees the compatibility of its standardized interfaces within the project and with the core organization,suchasreporting,regardlessofwhetherdevelopmentiscarriedoutinatraditional or agile manner. HERMES terminology guarantees a common language and understanding between the core and project organizations, between the project and the program, and between project, applica- tion, and portfolio management. Within the project organization, the project sponsor, project management, and user represen- tative are the indispensable roles for the functioning of the interfaces, but also for the project as a whole:

8/244

* * *

- Theprojectsponsorsteerstheprojectandhastheoverallresponsibilityfortheprojectand for achievement of the project objectives;
- Theprojectmanagementmanagesandcoordinatestheprojectanddeterminesitscourse; - The user representative is responsible for solution development.

## A.6 Agile development management with HERMES

The HERMES project management method is a project approach framework into which a spe- cific agile development method can be inserted like a black box. HERMES does not go into any furtherdetail on the development approachencapsulated in thisway, but it does define relevant interfaces for the purpose of steering, management, communication, and reporting. These are the corresponding outcomes and specific roles. When we talk about agile implementation in this manual, we are referring to the development of solutions in time-limited projects using both simple agile methods (Scrum, Kanban, etc.) and scaled agile methods (SAFe up to the "Essential" or "ART Flow" level). The traditional and agile development processes have a fundamentally different understanding ofthemanagementoftherolesofthehierarchylevelofexecution. Whilethetraditionalapproach assumes that the project manager issues work orders, in the agile approach the work of the execution organization is steered by the user representative via the solution requirements, and the teams organize their work independently. The project manager manages the project, but the project manager is not allowed to interfere with the self-organization of the agile execution organization. As the representative of the agile execution organization, the user representative is the contact person for the project manager. The terminology within agile development is not prescribed; it depends on the development method used in each case. Only the outcome interfaces and the terminology within the frame- work of project management are defined. HERMES project management gives the project its uniform structure and a uniform framework. The focus is on the project life cycle; agile development management forms a black box as an encapsulated method. Agile development management determines the organization and steering of the execution organization and autonomously steers solution development within a predefined framework. The method-specific role models, processes, and rituals can be put into practice without interference - provided there is consensus within the core and project organization. FurtherinformationonHERMESandagilitycanbefoundinthedocument"AgileGuide-Project management", which is an extension to this reference manual.

## A.7 Positioning of program management

In organizations with far-reaching and comprehensive changes, a holistic management system isrequiredtoachieveobjectiveswithinagroupofinterrelatedprojectsinaleanandcoordinated manner. Thismanagementsystemiscalledprogrammanagementandisanextensionofproject management. Inprogrammanagement,theprojectsaregroupedtogetheraspartofaprogram. Projects and programs can be managed side by side in a core organization. The figure below shows an example of a portfolio with traditionally and agilely managed projects and a program that includes other projects. The figure shows that a project can be stand-alone or part of a program. A program contains several projects. Projects and programs can be combined within a portfolio.

9/244

* * *

Figure 3: Simultaneous management of projects and programs in a core organization

HERMES project management creates a common understanding of project and program management. Aprerequisite,however,isthattheprojectpartnersinvolvedinprogrammanagement
have the necessary skills to perform their role successfully. The extension of project management by program management is discussed in the appendix to this reference manual.

A.8 User information

The user information describes specific aspects of HERMES project management. User information forms the basis for a deeper understanding of the method, for example in relation to
governanceandsustainability. UserinformationalsoshowshowHERMESshouldbeappliedin
specificsituationsandhelpstoreduceroomforinterpretation, forexampleinagiledevelopment
or when using implementation units.

* * *

B HERMES project management method
components

B.1 Phases

The HERMES phase model for projects forms the backbone of every project. It creates the
conditions for the common understanding of all project participants. This is an important prerequisite for the successful cross-organizational handling of projects.

The phase model builds on the life cycle of a project. The figure below shows the HERMES
project life cycle and the phase model for the traditional and agile approach; the initiation phase
at the start and the closure phase at the end of the project are common to both approaches and
include the solution development phases.

Figure 4: HERMES project life cycle with phase model for traditional and agile approach

Accordingly,projectsarecarriedoutineitherfiveorthreephases. Theprojectstartswiththeinitiation phase and ends with the closure phase. The initiation phase corresponds to a structured
orientation for a focused project. It formulates which possible solutions exist and which path
to take. The closure phase ends the project and defines the organizational and administrative
transition from the project organization to the application organization1.

The phases included between initiation and closure are, in the traditional approach, the three
phasesof concept, implementation, and deployment, andin the agile approach, onlyexecution.

A scenario is geared towards the implementation of projects of a specific nature. The scenario
contains precisely those HERMES method components that are important for the development
of the solution. Consequently, HERMES project management is quick and easy to use. By way
of example, the figure below shows several plans of a core organization with the corresponding
projects and scenarios.

B.2 Scenarios

If the core organization wants to explore a possible vision for a solution, it starts the project with
the initiation phase, the outcomes of which also decide whether a traditional or agile approach
should be taken for the development procedure. Within a single program, some of the projects
maybecarriedoutaccordingtothetraditionalapproach,othersaccordingtotheagileapproach.

1. Like the project organization, the application organization is a temporary organization that is closely related to
   the core organization. It is system- or product-specific and ends at the end of the life cycle of a product or a
   system (the application).

* * *

Figure 5: Projects of a core organization with scenarios

In the initiation phase, the project manager selects the suitable solution option, along with the
scenario suitable for the development procedure. Based on this, the project manager plans
the specific procedure and the development of the solution. HERMES offers a selection of
possible standard scenarios, such as for an organizational adjustment or for the development
of a service/product.

HERMESuserscanadaptstandardscenariostotheneedsoftheirorganizationandcreatetheir
own user-defined scenarios.

B.3 Modules

Modules are reusable building blocks assigned to phases for creating projects and scenarios.
Thematicallyrelatedoutcomesandthetasksassociatedwiththemformamodule(seethefigure
below).

Tasks
Figure 6: A module is composed of outcomes and tasks

The project manager can create additional modules and integrate them into user-defined scenarios.

* * *

B.4 Outcomes

As shown in the figure below with a selection of outcomes for each phase, outcomes are at the
heart of HERMES project management.

There is an outcome description for each outcome. For all documents, there are document
templatesthatdescribethecontentintheoutcomesinmoredetail. Tasksandrolesareassigned
to each outcome. The roles give an indication of the responsibilities for outcomes and of the
involvement in the production of outcomes.

HERMES defines minimum required documents (outcomes) to meet project governance requirements.

Figure 7: Outcomes are at the heart of HERMES

The figure below shows that the phases start and end with milestones. These milestones correspond to quality gates when the outcomes and the procedure are decided. This also involves
coordination with the strategic objectives and requirements of the core organization. Analogous to phase releases, optional interim releases may be approved under the agile approach,
creating additional milestones.

Figure 8: Phases and releases with milestones as quality gates

All milestones are outcomes that mark decision points over the course of the project. Each
decision task accordingly ends with a milestone. Depending on the module, there are different
decisions and consequently also different further milestones.

* * *

### B.5 Tasks

Tasks are used to develop outcomes. Thematically related outcomes together with their asso- ciated tasks form modules. There is a task description for each task. It defines the general approach and the activities that are undertaken to produce the outcomes. The roles give an indication of the role to which the responsibility for a task is assigned.

### B.6 Roles

HERMES project management distinguishes between the roles of the core organization and roles of the project organization, but it describes only the HERMES roles of the project organi- zation. For each role, there is a role description with the responsibilities, powers, and required skills for the roles as well as their relationships. Each role is assigned to one of the hierarchy levels of steering, management, or execution. Different roles are defined which can be used as needed. Partners in the project organization are users, creators, and operators. Each role is assigned to one or more partner groups. The figure below shows a project organization with the minimum roles to be filled, highlighted in gray: project sponsor, project management, and user representative.

# Core organization

# Project organization

## Steering Project sponsor

## Management Project management

## Execution User representative

Figure 9: Minimum roles to be filled: project sponsor, project management, and user

representative

14/244

* * *

1 Phases

1.1 Introduction

1.1.1 Project life cycle

With its phase model, the HERMES project management method supports both the traditional
and the agile approach. The phase model for projects is based on the life cycle of the project.
Forallprojectparticipants, itcreatestheprerequisiteforacommonunderstandingoftheproject
process. The phases determine the project structure.

The figure below shows the HERMES project life cycle.

Figure 10: HERMES project life cycle

- The project start is where the envisaged project is aligned with visions, needs, and objectives. Not infrequently, the focus is on both an urgent need for action as well as external
influences (legislators, policymaking and politics, international agreements, association
rules, etc.) or superordinate entities (core organization, program, or portfolio).
- The solution development according to the traditional or agile approach is carried out on

- The solution development according to the traditional or agile approach is carried out on
the basis of the execution release.
- The project end concludes the current project in organizational and formal terms and pre-

- The project end concludes the current project in organizational and formal terms and prepares the transition to the application organization.

1.1.2 Project start

The initiation phase is always situated at the project start. The figure below shows the initiation
process with the most important outcomes.

* * *

Figure 11: Outcome diagram of the initiation phase

During initiation, the requisite project-specific foundations and the possible solution options are
elaborated, compared, and evaluated. The choice of solution option includes the decision as
to whether the development approach should be agile or traditional. This decision must be
justified in terms of the subject matter and process and should not merely follow current trends.
The proposed approach is derived from the premises available to the project and is shaped by
the selected solution option.

1.1.3 Solution development

The solution development process differs depending on whether a traditional or agile approach
is adopted. Most of the method components are almost identical under both approaches; what
differs is the project organization and the structure of the project, and consequently the development process and ultimately also the specialist and formal content of the outcomes.

In agile development management, changes are a fundamental part of the development process. Theexecutionorganizationfollowsthegivenanddesiredimpactandproactivelyresponds
to changing requirements instead of following a fixed plan. Development and deployment are
iterative and incremental. A phase structure does not make sense under this approach. For
that reason, the execution phase cannot be further subdivided.

Depending on which approach is selected, the solution development of the project after execution release is either
- traditional

and then concluded with the closure phase, irrespective of the approach taken.

solely with an execution phase

The interfaces to the core organization remain largely the same, as do the documents required
at project closure.

with the phases of concept, implementation, and deployment, or
agile

- agile
solely with an execution phase

* * *

1.1.4 Project end

The closure phase is always situated at the project end. It is the last phase of each project,
during which the project is conclusively brought to completion. The closest attention during this
phase is paid to the project documentation, which is checked accordingly and supplemented
and structured as necessary, especially from a formal point of view. The organizational and
administrative transition from the project organization to the application organization is also set
out during this phase; legacy systems are deactivated or removed, all project data is archived
in accordance with the provisions of the core organization and, if necessary, responsibility for
the solution is transferred.

The purpose of the closure phase is, in particular, to ensure that the organizational and administrative handover and transition interfaces of the project (vis-à-vis the core organization,
the program, the portfolio, the application organization, if necessary the operating organization,
etc.) remain identical regardless of the approach selected.

1.2 Phase overview

Figure 12: HERMES phase model for traditional and agile approaches

The phase model
-

- covers the common controlling and reporting requirements of management,
- fully integrates into a traditional or agile core organization, regardless of the approach

- fully integrates into a traditional or agile core organization, regardless of the approach
chosen,
-

| HERMES phases Traditional development | Project life cycle | HERMES phases agile development |
| --- | --- | --- |
| Initiation | Project start | Initiation |
| Concept | Solution development | Execution |
| Implementation |  |  |
| Deployment |  |  |
| Closure | Project end | Closure |

- makes use of synergies and avoids any redundancies, and
-

- is easy to apply.

The table shows the phase model using traditional and agile development processes:

* * *

1.2.2 Uniform project structure

The first and last phases of the project are always common to all projects. A project begins with
the initiation phase and ends with the closure phase. This ensures the uniformity of the project
structure and the project life cycle. The project interfaces to the core organization, controlling,
program, portfolio, etc. are kept the same regardless of the approach. The transitions to the
application organization and operating organization are channeled in a uniform way.

The project structure is supported additionally by the milestones described in Section "Outcomes". Overthecourseoftheproject, theymarkimportantdecisionoutcomesofprojectsteering and management. As shown in the figure below, milestones are at the beginning and end of
each phase. With each phase release, the (financial, personnel, infrastructure) resources are
released for the next phase by the sponsor. Under the agile approach, interim releases can be
defined and approved on an optional basis as milestones during the execution phase.
Execution Phase Closure phase Phase

Figure 13: Milestones at the beginning and end of each phase and approval of interim releases

These milestones defined in terms of the project structure correspond to quality gates, before
which the outcomes and the procedure are decided. Compliance with the requirements and the
conformity of the project with the strategic objectives of the core organization are checked.

1.2.3 Phase progression

Theinitiationphaseprovidesabasisforplanningandsteeringtheproject. Theinitiationphaseis
followedbysolutiondevelopment, eitherwiththetraditionalphasesofconcept, implementation,
and deployment or with the agile phase of execution. The execution phase covers the agile
development process and serves to embed any agile development method within the HERMES
framework.

The closure phase provides space for all necessary measures in connection with the removal
of the replaced legacy product or system environment, including the infrastructure that is no
longer required, and for the systematic shutting down of the project, including all administrative
and organizational measures.
Alongthephases,furtherdecisionsaremadewithcorrespondingspecificmilestonesthatdeter-

Alongthephases,furtherdecisionsaremadewithcorrespondingspecificmilestonesthatdetermine the successful progression of the project. These milestones vary depending on the nature
oftheproject. Asanexample,thefigurebelowshowsthesteeringandmanagementmilestones
for traditional and agile IT development projects.

* * *

Figure 14: Milestones for traditional and agile IT development projects

For the next steps milestone, but also for other milestones, achievement of the sustainability
goals (see Section "User Information") is also taken into account as an assessment criterion.

Overthecourseoftheentireproject,reportingiscarriedoutinaccordancewiththerequirements
of the core organization in terms of the content and, to the extent feasible, the frequency of the
reports (see Section "User Information").

1.3 Explanation regarding the phase description

For each phase, a phase description is provided that is always structured in the same way:
-

- Description of the phase as a whole, highlighted
-

- Description of the phase as a whole, highlighted
- Enumeration of important points and rough description of what needs to be done over the
course of the phase
-

1.4 Explanation of the phases
1.4.1 Project start

- Based on the project initiation order, the project sponsor releases the resources for the
initiation phase. The project sponsor commissions the project manager to carry out the

- Description of the phase closure, highlighted

1.4.1 Project start initiation phase.

- From the perspective of project management, the initiation phase is always handled using the traditional approach. Agile tools can nevertheless also be used.
- The study is compiled. - The work starts with an initial status report, objectives, and rough requirements.
- The solution options are drawn up. The solution options are described in such detail that they can be evaluated in a comprehensible and transparent manner.
- The project and operational risks are determined.
- In parallel with the study, the legal basis analysis and the protection needs analysis are drawn up and included in the decision.
- It is further defined and documented in a comprehensible manner how to proceed within the framework of each solution option: either traditional or agile.
- The decision on next steps is made.
- A procurement analysis is carried out in parallel to the study for any procurement of a product or a system.
- Thescenariosuitableforthesolutiondevelopmentisselectedandcustomizedasneeded. - Based on the chosen option and the approach, the project management plan and execu- tion order are drawn up and compared with the strategies, specifications, and overriding objectives of the core organization. Stakeholder interests are analyzed and conflicts of interest are resolved.
- If an agile approach is taken, it is set out whether the optional decision on release is required in the project.
- Thedecisiononexecutionreleaseismadeandtheexecutionorderissigned. Therelease is carried out by the core organization and the sponsor.
  At the end of the initiation phase, a check is carried out to see whether it is wise to release the project; if so, the decision on execution release is made. Possible reasons for termination include lack of economic efficiency, excessive risks, infeasibility, legal or political concerns, and lack of alignment with the objectives, strategies, and priorities of the organization.

## 1.4.2 Traditional solution development

## 1.4.2.1 Concept

Concept Implementation Deployment Initiation Closure Execution

The option chosen in the initiation phase is fleshed out. The outcomes are drawn up in such detail that those involved in the project can plan, offer, and implement the solution based on reliable foundations.

- Basedontheselectedoptionandtheinitialstatusreportfromthestudy,situationanalyses are carried out.

- Based on the findings from the situation analyses, the requirements from the study are fleshed out, completed, and newly defined as solution requirements.

- In organizational and IT projects or if business processes or structures are affected by the solution, the organizational requirements and subsequently the organization concept must be drawn up in every case.

- Thesolutionisdevelopedconceptually. Thefeasibility, whereapplicableonlyofindividual solution components, is tested, e.g. with prototypes.

- The deployment concept is designed in preparation for deployment.

- Depending on the scenario, a test concept and migration concept are designed.

- In IT projects, the solution architecture and the operating concept are also designed. The
  20/244 decision on solution architecture is made.

- Ifasolutionistobeprocured, thecallfortendersisissued, thetendersareevaluated, and the selected product or system is procured.

- For systems, the integration concept is designed. - The implementation release decision is made (decide on phase release).

- The project and operational risks must be identified, analyzed, and evaluated.

- Feasibility of the solution development must still be proven or confirmed. - Theresourcesforthenextphasearereleasedbasedonthefleshedoutprojectman- agement plan and the offers available.
  At the end of the concept phase, a check is carried out to see whether it is wise to implement the project. Possible reasons for termination include economic inefficiency, excessive risks, infeasibility, and lack of alignment with the objectives and strategies of the organization.


## 1.4.2.2 Implementation

Concept Implementation Deployment Initiation Closure Execution

The product or system is implemented and tested. The necessary preparatory work is done to minimize the deployment risks. The product or system is developed or, if procured, parameterized or adapted.

- The organization is implemented. - In IT projects, the IT system is integrated into the operating infrastructure.
- Preliminary acceptance is carried out. - The operating organization is implemented and the documentation is prepared.
- Deployment is prepared on the basis of the deployment concept.
- Depending on the scenario, tests are carried out and migration is prepared.
- The deployment release decision is made (decide on phase release). It is based on the preliminary acceptance decision. The resources for the next phase are released based on the fleshed out project management plan.
  Attheendoftheimplementationphase, thedeploymentrisksmustbeassessedandbeaccept- able. Otherwise, deployment cannot take place.

## 1.4.2.3 Deployment

Concept Implementation Deployment Initiation Closure Execution

The deployment phase ensures a safe transition to the new state. Operation is launched.

- The deployment measures such as user training, etc., are carried out.
- Depending on the scenario, a migration is performed. - The product or system and the organization are activated.
- Operation is activated. - The ISDP concept is transferred.
- During the initial period of operation between the launch of operation and the acceptance of the complete system or product, the project supports problem analysis and resolution (after which the warranty begins, and with it regular operation).
- The decision on closure phase release is made. The resources for the closure phase are released based on the updated project management plan.
  21/244

* * *

At the end of the deployment phase, the decision on acceptance is made and the phase is closed once the operation has been successfully launched.

## 1.4.3 Agile solution development

## 1.4.3.1 Execution

Concept Implementation Deployment Initiation Closure Execution

The option selected in the initiation phase is executed iteratively and incrementally. The project organization, including the execution organization, is established. The solution requirements are further divided, refined, and fleshed out. The requirements are updated, prioritized, and processed(developed, realized, andputintooperation)indescendingorderofpriority; priorities are updated continuously and adjusted according to project findings.

- Basedontheselectedoptionandtheinitialstatusreportfromthestudy,situationanalyses are carried out.
- With the findings from the situation analyses, the requirements from the study are fleshed out, completed, and defined as prioritized initial solution requirements.
- If the envisaged solution affects business processes or structures, the organizational re- quirements must be drawn up in every case.
- If a solution is to be procured, the call for tenders is issued, the offers are evaluated, and the selected product or system is procured.
- With each iteration, a further part of the solution-the increment-is created, which can be seamlessly connected to the already created scope of execution results. Iterative and incremental execution:
- Each individual solution requirement is continuously fleshed out, refined, completed, and divided and prioritized to such an extent that they can be processed in descending order of priority.
- The organization concept is drawn up and the successively emerging organization is realized and documented.
- The project, operational, and deployment risks are identified, analyzed, evaluated, and assessed. Feasibility is checked.
- The product is developed or adapted or the system is developed or parameterized.
- In parallel, the operating organization and all other outcomes of the remaining mod- ules are successively developed, realized, and documented.
- For systems, the integration concept is designed and the decision on solution archi- tecture is made.
- For systems, tests are designed and conducted, migration is prepared and carried out, and the system is integrated into the operating infrastructure.
- The deployment concept is designed and the preliminary acceptance, deployment measures such as user training etc., and the launch of operation are carried out.
- The organization, the relevant part of the solution (one or more increments), and the operation are activated.
- During the initial period of operation until the acceptance of the part of the solution, the project supports problem analysis and resolution (after which the warranty begins, and with it regular operation).
- If so defined in the project management plan, the decision on approval of the next release is made (decide on release).
- The decision on closure phase release is made. The resources for the closure phase are released based on the updated project management plan.
  22/244

* * *

After the completed launch of operation including the acceptance of the last release, the agile part of the project and the execution phase are completed; the execution organization is
dissolved into the project organization.

1.4.4 Project end

1.4.4.1 Closure

The closure phase provides a structure for the systematic shutting down of a project. Project
documentation is checked and amended as needed. The project closure is prepared.
-

- From the perspective of project management, the closure phase is always handled using
the traditional approach. Agile tools can nevertheless also be used.
- The outcomes are checked for completeness and amended, in particular from a formal

- The outcomes are checked for completeness and amended, in particular from a formal
perspective.
- The final project evaluation is checked and approved as appropriate.

- The final project evaluation is checked and approved as appropriate.
- The project organization is dissolved. Before the dissolution, it can be checked whether

- The project organization is dissolved. Before the dissolution, it can be checked whether
parts of the project organization can be transferred analogously to the application organization.
- The outcomes, documentation, etc., are transferred to the core organization, specifically

- The outcomes, documentation, etc., are transferred to the core organization, specifically
the application, operating, and maintenance organization. In IT projects, this also applies
to the test infrastructure, including the test concept and the tools.
- The documentation of the project execution, including the outcomes of the approach, is

- The documentation of the project execution, including the outcomes of the approach, is
archived according to the filing rules of the core organization.
- Depending on the scenario and taking the specifications into account, the legacy system

- Depending on the scenario and taking the specifications into account, the legacy system
is decommissioned and removed, including the old, no longer required infrastructure, and
the legacy data is archived or destroyed.

At the end of the closure phase, the project closure is carried out. The final project evaluation is
prepared. Openpointsaretransferredtothecoreorganizationandtheapplicationorganization.
The project is closed and the project organization is dissolved.

* * *

2 Scenarios

2.1 Introduction

Different kinds of projects are carried out within a core organization. Projects can vary significantly in terms of content and complexity.

HERMES provides various scenarios to satisfy the diversity of projects. A scenario is oriented
towardssolutiondevelopmentinprojectswithaspecificcharacteristic,suchasthedevelopment
or adaptation of an IT solution.

As the figure below shows, a scenario maps the complete solution development of a project
and supports the project manager in execution planning. The findings of the study are decisive
for the selection of the appropriate standard scenario. The initiation and closure phases are not
part of a scenario.

Figure 15: Selection and application of the scenario suitable for the project

A standard scenario contains those method components that are usually of importance for
projects with the respective characteristics. This makes HERMES quick and easy to use.
The project manager can adapt standard scenarios to the needs of the core organization and
the project at hand, and create further user-defined scenarios.

Figure 16: Multiple modules with tasks and outcomes as the basis for a scenario

2.2 Overview of scenarios

2.2.1 Structure of scenarios

Scenariosarebasedonmoduleswiththematicallyrelatedtasksandoutcomes. Thefigurebelow
shows how a scenario can be formed with the help of modules B and N and part of module A.

* * *

module can be used in several scenarios or - because a module can be more comprehensive
than a scenario - used only partially in a scenario. Because the modules are composed of the
corresponding tasks and outcomes, there is a coordinated solution development template for
each scenario, including the necessary document templates.

A scenario describes only the solution development; the initiation and closure phases are outside the scenario.

2.2.2 Standard scenarios

HERMES offers five standard scenarios for projects with different characteristics:
-

- Service/product development
- Service/product adaptation

- Service/product adaptation
- IT development

- IT development
- IT adaptation

- IT adaptation
- Organizational adjustment

- Organizational adjustment

The following table shows the modules used for each scenario according to context.

| Scenarios/Modules | Project steering | Project management | Procurement | Organization | Product | IT system | Tests | Deployment organization | IT migration | IT operation | ISDP |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Service/product development | X | X |  | X | X |  |  | X |  |  |  |
| Service/product adaptation | X | X | X | X | X |  |  | X |  |  |  |
| IT development | X | X |  | X |  | X | X | X | X | X | X |
| IT adaptation | X | X | X | X |  | X | X | X | X | X | X |
| Organizational adjustment | X | X |  | X |  |  |  | X |  |  |  |

Table 2: Standard scenarios for projects with various characteristics including modules

The range of standard scenarios is not exhaustive. The demand for new scenarios is reviewed
periodically, and additional standard scenarios are made available as needed.

2.2.3.1 Adjustment of scenarios

- Sizing
- Tailoring

- Tailoring

* * *

## 2.2.3.2 Sizing

Toensurethe completenessofthe informationandthe methoditself, the fullscope ofHERMES project management is designed for large projects with a high level of complexity. Since many core organizations predominantly manage medium and small projects, the appli- cation of the method should be adapted to the size of the project using the sizing function. The use of the sizing function reduces the complexity of the procedure and the scope of the documentation to an absolute minimum while complying with HERMES governance. Thesizingfunctiondeterminestheactualrequiredprojectsizefromseveralparametersthatcan be entered by the user. Based on this, the sizing function provides the project manager with a scenario tailored to the size of the project with an execution structure plan and the necessary templates. Thisadaptationsupportedbytheonlinetoolguaranteesmethodcontinuityandcoherence(HER- MES governance) and allows all projects to be processed in a lean manner. The resulting user-defined scenario can then be optionally adjusted to the respective project requirements using the tailoring function.

## 2.2.3.3 Tailoring

Usingtailoring,standardscenariosoruser-definedscenariosalreadycreatedthroughsizingare adapted to the needs of the project and further customized. This can also be done with the help of HERMES online. There are four basic options that can be used in combination:

1. Remove modules from an existing scenario: Unnecessary modules are removed. Example: In a project without migration, remove the IT migration module from the IT development scenario.
2. Remove tasks and outcomes: The content of a module can be reduced by outcomes and associated tasks, with the exception of the minimum required documents.
3. Integrate an additional subject-specific module into the existing scenario: A separate module with subject-specific content-with existing or with new customized tasks and outcomes-is created and integrated into a scenario.
4. Add tasks and outcomes: The content of a module can be extended. New customized tasks and outcomes can be created.
   Withthehelpoftheseoptions, additional, user-defined, project-ororganization-specificscenar- ios can be easily modeled. The figure below shows how several projects of a core organization with different scenarios can be handled simultaneously side by side.

26/244

* * *

Figure 17: Application of standard and user-defined scenarios

User-definedscenarioscanbesharedwithotherHERMESusersormadeavailabletoallusers.
Further information can be found on HERMES online.

2.3 Explanation regarding the scenario description

For each scenario, a scenario description is provided that is always structured in the same way:
-

- Applicability
describes concrete project criteria for which the scenario is suitable.

describes concrete project criteria for which the scenario is suitable.
- Modules

- Modules

enumerate and graphically represent all modules of the scenario along the solution development; the project foundations module and parts of other modules that are used outside
solution development and accordingly do not appear in any scenario are shown shaded
white.

2.4 Scenario directory

2.4.1 Service/product scenarios

2.4.1.1 Service/product development

The service/product scenario supports the execution of those projects where a service or product is developed and provided.

The product/service scenario is based on the following modules shown in the figure below:
-

Examples:
-

- Development of training materials and courses on a specific topic
- Development of an internal standard

- Development of an internal standard
- Establishment of a delivery service

- Product
- Deployment organization

- Establishment of a delivery service

- Deployment organization

* * *

Figure 18: Modules in the context of the service/product development scenario

2.4.1.2 Service/product adaptation

Applicability

Theservice/productadaptationscenariosupportstheexecutionofthoseprojectswhereaproductorserviceavailableonthemarketis procured,adapted,and integrated intotheorganization.

Modules

The service/product adaptation scenario is based on the following modules shown in the figure
below:
-

- Project steering
- Project management

- Project management
- Procurement

- Procurement
- Organization

- Organization
- Product

- Product
- Deployment organization

Figure 19: Modules in the context of the service/product adaptation scenario

As needed, the tests module can also be embedded in the scenario. This makes it possible to
organize and conduct tests of solutions.

* * *

2.4.2 Information technology scenarios

2.4.2.1 IT development

Applicability

The IT development scenario supports the execution of those projects where a new IT application is developed for the specific needs of one or more specialist areas (user needs) or an
existing IT solution is further developed and is integrated both technically and organizationally.

Modules

The IT development scenario is based on the following modules shown in the figure below:
-

- Project steering
- Project management

- Project management
- Organization

- Organization
- IT system

- IT system
- Tests

- Tests
-

- Deployment organization
- IT migration

- IT migration
- IT operation

- IT operation
- ISDP

- ISDP

Figure 20: Modules in the context of the IT development scenario

The IT adaptation scenario is based on the following modules shown in the figure below:
-

The IT adaptation scenario supports the execution of those projects where an IT solution available on the market (e.g. standard software or IT infrastructure) is procured, adapted, and integrated both technically and organizationally.

- Project steering
- Project management

- Project management
- Procurement

- Procurement
-

2.4.2.2 IT adaptation

- Organization
- IT system

* * *

- Tests
-

- Deployment organization
- IT migration

- IT migration
- IT operation

- IT operation
-

- ISDP

Figure 21: Modules in the context of the IT adaptation scenario

2.4.3 Organization scenarios

2.4.3.1 Organizational adjustment
Applicability

Applicability

The organizational adjustment scenario supports the execution of those projects where new
organizations are established or existing organizations are adjusted through restructuring and
innovation, new business areas, in- and outsourcing, acquisitions, mergers and separations,
liquidations, (international) expansions, etc.
Examples:

Relocation, adjustment, or creation of an organization

- Project management
- Organization

Merger of organizations

- Organization
- Deployment organization

Outsourcing of services to a service center

- Deployment organization

* * *

Figure 22: Modules in the context of the organizational adjustment scenario

* * *

3 Module

3.1 Introduction

Modules contain thematically related tasks and outcomes. They are building blocks for creating
projects and scenarios.

The figure below shows an overall context of all modules that can be used and in some cases
even must be used. In addition, own modules can be created.

Figure 23: Overall context of available standard modules in HERMES

3.2.1 Standard modules

The table lists all available standard modules according to their context and shows in which
project phases they can occur.

| Project Phases/Modules | Initiation | Concept | Implementation | Deployment | Execution | Closure |
| --- | --- | --- | --- | --- | --- | --- |
| Project steering | X | X | X | X | X | X |
| Project management | X | X | X | X | X | X |
| Project foundations | X |  |  |  |  |  |
| Procurement |  | X |  |  | X |  |
| Organization |  | X | X | X | X |  |
| Product |  | X | X | X | X |  |
| IT system |  | X | X | X | X |  |
| Tests |  | X | X | X | X | X |
| Deployment organization |  | X | X | X | X |  |
| IT migration |  | X | X | X | X | X |
| IT operation |  | X | X | X | X |  |
| ISDP |  | X | X | X | X |  |

Table 3: Standard modules assigned to project phases

To comply with the project governance, the following modules must always be included in each
project:
-

- Project steering;
- Project management;

- Project management;
- Project foundations;

- Deployment organization.

- Project foundations;
- Deployment organization.

3.2.2 Customized modules

Supplementing the standard modules available, it is also possible to develop own subject-,
organization-, or project-specific modules with existing or new customized tasks and outcomes
andtointegratethemintoownprojectsorscenarios. ThisisalsosupportedbyHERMESonline.

3.3 Explanation regarding the module description

For each module, a module description is provided that is always structured in the same way:
-

- Purpose
defines the purpose of the module.

defines the purpose of the module.
What has to be done

- What has to be done

describes the module tasks in the overall context of the module.
Tasks and outcomes

- theoutcomesderivedfromoradaptedbythetasksandassignedtothecorresponding
project phases.

provide a tabular breakdown of
- the module tasks in their overall context, with the decision-making tasks highlighted

* * *

3.4 Description of the modules

3.4.1 Steering and management modules

3.4.1.1 Project steering

Purpose

Theprojectsteeringmoduleensurestheoverallandcross-organizationalsteeringoftheproject
and ensures that the set objectives are achieved.

What to do
-

- Initiate the project, steer it continuously, and ensure that it is kept in line with the core
organization's overarching objectives and requirements.
- Consider and integrate stakeholder concerns, make decisions on risks.

- Consider and integrate stakeholder concerns, make decisions on risks.
-

- Make decisions on steering.
- Close the project, discontinue early where necessary.

- Close the project, discontinue early where necessary.

Tasks and outcomes

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Decide on project initiation release | List of steering project decisions | X |  |  |  |  |  |
|  | Project initiation order | X |  |  |  |  |  |
|  | Project initiation release milestone | X |  |  |  |  |  |
|  | Project initiation release checklist | X |  |  |  |  |  |
| Decide on execution release | Execution release milestone | X |  |  |  |  |  |
|  | Execution release checklist | X |  |  |  |  |  |
|  | List of steering project decisions | X |  |  |  |  |  |
|  | Execution order | X |  |  |  |  |  |
| Decide on project closure | Project closure checklist |  |  |  |  |  | X |
|  | Project closure milestone |  |  |  |  |  | X |
|  | QA and risk report |  |  |  |  |  | X |
|  | List of steering project decisions |  |  |  |  |  | X |
| Decide on phase release | Phase release checklist |  | X | X |  |  |  |
|  | Phase release milestone |  | X | X |  |  |  |
|  | List of steering project decisions |  | X | X |  |  |  |
|  | QA and risk report |  | X | X |  |  |  |
| Decide on project discontinuation | Project discontinuation checklist |  | X | X | X |  |  |
|  | Final project evaluation |  | X | X | X |  |  |
|  | List of steering project decisions |  | X | X | X |  |  |
|  | Lessons learned |  | X | X | X | X |  |
|  | Project closure milestone |  | X | X | X | X |  |
| Decide on release | QA and risk report |  |  |  |  | X |  |
|  | Release milestone |  |  |  |  |  | X |
|  |  | I | C | I | D | E | C |
|  | Release checklist |  |  |  |  | X |  |
|  | List of steering project decisions |  |  |  |  | X |  |
| Decide on closure phase release | Closure phase release checklist |  |  |  | X | X |  |
|  | Closure phase release milestone |  |  |  | X | X |  |
|  | List of steering project decisions |  |  |  | X | X |  |
|  | QA and risk report |  |  |  | X | X |  |
| Steer project | QA and risk report |  | X | X | X | X |  |
|  | List of steering project decisions | X | X | X | X | X | X |

Table 4: Project steering module tasks and outcomes

3.4.1.2 Project management

Purpose

The project management module encompasses the planning, management, and coordination
of the project in order to achieve the project outcomes and procedure objectives, as well as the
execution of all necessary accompanying measures.

What to do

- Plan and manage the project and complete it with the required outcome according to the
defined framework (deadlines and costs).
- Gain stakeholders for the project and inform them.

- Gain stakeholders for the project and inform them.
- Manage risks, overcome problems, and take lessons learned into account.

- Manage risks, overcome problems, and take lessons learned into account.
- Agreeonandsteergoods/services, managechangemanagementandqualityassurance.

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Draw up project execution order | Execution order | X |  |  |  |  |  |
| Manage risks | Project status report |  | X | X | X | X |  |
| Project management plan |  | X | X | X | X |  |  |
| Deal with problems and benefit from lessons learned | Lessons learned |  | X | X | X | X | X |
| Manage and control project | Work order | X | X | X | X | X | X |
| Solution requirements |  |  |  |  | X |  |  |
| Detailed specifications |  |  |  |  | X |  |  |
| Project status report | X | X | X | X | X | X |  |
|  | Project management plan | X | X | X | X | X | X |
| Minutes | X | X | X | X | X | X |  |
| Release report |  |  |  |  | X |  |  |
|  | Project management plan |  |  |  |  | X |  |
| Project status report |  |  |  |  | X |  |  |
|  |  |  |  |  | X |  |  |

Tasks and outcomes

- Agreeonandsteergoods/services, managechangemanagementandqualityassurance.

* * *

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Draw up project management plan | Project management plan | X |  |  |  |  |  |
| Prepare phase release | Project management plan |  | X | X | X | X |  |
| Project status report |  | X | X | X | X |  |  |
| Phase report |  | X | X | X | X |  |  |
| Manage changes | Change status list |  | X | X | X | X |  |
| Change request |  | X | X | X | X |  |  |
| Solution requirements |  | X | X | X |  |  |  |
| Project management plan |  | X | X | X | X |  |  |
| Agree on and steer goods/services | Evaluation report |  | X | X | X | X |  |
| Agreement |  | X | X | X | X |  |  |
| Quote request |  | X | X | X | X |  |  |
| Manage and inform stakeholders | Stakeholder list | X | X | X | X | X | X |
| Stakeholder interests | X | X | X | X | X | X |  |
| Project management plan | X | X | X | X | X | X |  |
| Perform quality assurance | Project management plan |  | X | X | X | X | X |
| Review report |  | X | X | X | X | X |  |
| Prepare project closure | Final project evaluation |  |  |  |  |  | X |
|  | Lessons learned |  |  |  |  |  | X |

Table 5: Project management module tasks and outcomes

3.4.2 Execution modules

- Prepare study to decide on next steps.
- Clarify the legal basis and analyze protection needs.

3.4.2.1 Project foundations
Purpose

- Carry out a procurement analysis if procurement with subsequent adaptation is planned.
- Createtheprerequisitesfordrawinguptheprojectmanagementplanandexecutionorder.

- Clarify the legal basis and analyze protection needs.
- Carry out a procurement analysis if procurement with subsequent adaptation is planned.

The project foundations module creates a concrete, well-founded starting point for possible
solution development and subsequent project closure.

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Analyze legal basis | Legal basis analysis | X |  |  |  |  |  |
|  |  | I | C | I | D | E | C |
| Decide on next steps | List of management project decisions | X |  |  |  |  |  |
| Next steps checklist | X |  |  |  |  |  |  |
| Study | X |  |  |  |  |  |  |
| Next steps milestone | X |  |  |  |  |  |  |
| Prepare procurement analysis | Procurement analysis | X |  |  |  |  |  |
| Analyze protection needs | Protection needs analysis | X |  |  |  |  |  |
| Carry out prototyping | Prototype documentation | X |  |  |  |  |  |
| Prototype realized | X |  |  |  |  |  |  |
| Prepare study | Stakeholder list | X |  |  |  |  |  |
| Study | X |  |  |  |  |  |  |

Table 6: Project foundations module tasks and outcomes

3.4.2.2 Procurement

Purpose

The procurement module is used for the targeted procurement of a system, product, or service
available on the market by means of an open or selective procedure.

What to do
-

- Procurement by means of an open or selective procedure and public tender; all other
procurement is handled with the project management module.
- Boundaries:

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Draw up agreement | Agreement |  | X |  |  | X |  |
| Decide on call for tenders | Tender checklist |  | X |  |  | X |  |
|  | List of steering project decisions |  | X |  |  | X |  |
|  | Tender milestone |  | X |  |  | X |  |
| Decide on contract award | Contract award checklist |  | X |  |  | X |  |
|  | Contract award milestone |  | X |  |  | X |  |
|  | List of steering project decisions |  | X |  |  | X |  |
|  | Publication |  | X |  |  | X |  |
| Prepare call for tenders | Tender documentation |  | X |  |  | X |  |
| Evaluate tenders | Evaluation report |  | X |  |  | X |  |
|  | Tender report |  | X |  |  | X |  |

The development of the procurement foundations such as needs and market analysis,
determination of the proper procedure with the procurement/purchasing unit, ensuring the
legal aspects, and procedure selection take place during the development of the procurement analysis in the project foundations module.

- Boundaries:

* * *

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Issue call for tenders | Tender documentation |  | X |  |  | X |  |
|  | Offer |  | X |  |  | X |  |

Table 7: Procurement module tasks and outcomes

3.4.2.3 Organization

Purpose

The organization module supports the solution-specific structure or adaptation of the organization and its implementation or provides the organizational and specialist basis for the structure
of the solution.

What to do

- Adapt or redesign, implement, and activate organization with business model, organizational and process structure.
- Continuously identify and analyze the interests of the stakeholders.

- Continuously identify and analyze the interests of the stakeholders.
- Involve stakeholders in the solution development.

- Involve stakeholders in the solution development.

Tasks and outcomes

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Draw up organization concept | Process description |  | X |  |  | X |  |
|  | Organization concept |  | X |  |  | X |  |
|  | Business model description |  | X |  |  | X |  |
|  | Organization description |  | X |  |  | X |  |
| Activate organization | Organization activated |  |  |  | X | X |  |
| Establish organizational requirements | Situation analysis |  | X |  |  | X |  |
|  | Organizational requirements |  | X |  |  | X |  |
| Advocate stakeholder interests | Stakeholder interests |  | X | X | X | X |  |
| Implement organization | Organization description |  |  | X |  | X |  |
|  | Process description |  |  | X |  | X |  |
|  | Organization implemented |  |  | X |  | X |  |

- Design the product concept and develop or adapt the product.
- Refine the solution requirements.

3.4.2.4 Product

Purpose

Table 8: Organization module tasks and outcomes

- Refine the solution requirements.
- Create detailed specifications.

- Create detailed specifications.
- Know the interests of the stakeholders and, where appropriate, involve them in solution development.

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Activate product | Product activated |  |  |  | X | X |  |
| Design product concept | Product concept |  | X |  |  | X |  |
| Decide on product concept | List of management project decisions |  | X |  |  | X |  |
|  | Product concept checklist |  | X |  |  | X |  |
|  | Product concept milestone |  | X |  |  | X |  |
| Carry out prototyping | Prototype realized |  | X | X |  | X |  |
|  | Prototype documentation |  | X | X |  | X |  |
| Advocate stakeholder interests | Stakeholder interests |  | X | X | X | X |  |
| Realize product | Product developed or adapted |  |  | X |  | X |  |
|  | Detailed specifications |  |  | X |  | X |  |
|  | Product documentation |  |  | X |  | X |  |
|  | User manual |  |  | X |  | X |  |
| Prepare solution requirements | Situation analysis |  | X |  |  | X |  |
|  | Solution requirements |  | X |  |  | X |  |

Table 9: Product module tasks and outcomes

3.4.2.5 IT system

The IT system module is used to develop a system.

| Task |
| --- |
|  |
| Advocate stakeholder interests |
| Design integration concept |
| Carry out prototyping |
|  |
| Realize system |
|  |

| Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- |
|  | I | C | I | D | E | C |
| Stakeholder interests |  | X | X | X | X |  |
| Integration concept |  | X |  |  | X |  |
| Prototype realized |  | X | X |  | X |  |
| Prototype documentation |  | X | X |  | X |  |
| User manual |  |  | X |  | X |  |
| System concept |  |  | X |  | X |  |
| Detailed specifications |  |  | X |  | X |  |

- Refine the solution requirements, prepare the solution architecture, and check feasibility
(using prototypes if necessary).
- Realize and/or integrate and document the system.

- Create detailed specifications and realize the system and integration.
- Know the interests of the stakeholders and involve them in solution development.

- Know the interests of the stakeholders and involve them in solution development.

39/244

* * *

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
|  | Solution architecture |  |  | X |  | X |  |
|  | System developed or parameterized |  |  | X |  | X |  |
| Prepare solution architecture | System concept |  | X |  |  | X |  |
|  | Solution architecture |  | X |  |  | X |  |
| Prepare solution requirements | Solution requirements |  | X |  |  | X |  |
|  | Situation analysis |  | X |  |  | X |  |
| Decide on solution architecture | Solution architecture milestone |  | X |  |  | X |  |
|  | Solution architecture checklist |  | X |  |  | X |  |
|  | List of management project decisions |  | X |  |  | X |  |
| Prepare system integration | Detailed specifications |  |  | X |  | X |  |
|  | Integration and installation instructions |  |  | X |  | X |  |
|  | Solution architecture |  |  | X |  | X |  |
|  | Interfaces realized |  |  | X |  | X |  |
| Activate system | System activated |  |  |  | X | X |  |

Table 10: IT system module tasks and outcomes

3.4.2.6 Tests

The tests module is used for systematically and efficiently organizing and conducting solution
tests.

- Realize and transfer test infrastructure.
- Prepare and conduct the tests and record them in the minutes.

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Transfer test infrastructure | Test concept |  |  |  |  |  | X |
|  | Minutes |  |  |  |  |  | X |
|  | Test infrastructure transferred |  |  |  |  |  | X |
| Realize test infrastructure | Test infrastructure realized |  |  | X |  | X |  |
| Design test concept | Test concept |  | X |  |  | X |  |
| Conduct test | Test concept |  |  | X | X | X |  |
|  | Test report |  |  | X | X | X |  |

- Prepare and conduct the tests and record them in the minutes.

* * *

3.4.2.7 Deployment organization

Purpose

The deployment organization module supports training and deployment of the new solution or
transition to the new state.

What to do

- Design deployment concept.
- Realize and execute deployment measures and deployment organization.

- Realize and execute deployment measures and deployment organization.
- Carry out preliminary acceptance and acceptance.

- Carry out preliminary acceptance and acceptance.
- Perform organizational change management.

- Perform organizational change management.

Tasks and outcomes

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Execute deployment measures | Deployment measures carried out |  |  |  | X | X |  |
| Design deployment concept | Project management plan |  | X |  |  | X |  |
| Deployment concept |  | X |  |  | X |  |  |
| Decide on acceptance | Acceptance report |  |  |  | X | X |  |
| Acceptance checklist |  |  |  | X | X |  |  |
| List of management project decisions |  |  |  | X | X |  |  |
| Acceptance milestone |  |  |  | X | X |  |  |
| Realize deployment measures | Deployment measures realized |  |  |  | X | X |  |
| Decide on preliminary acceptance | Preliminary acceptance milestone |  |  |  | X | X |  |
|  | List of management project decisions |  |  |  | X | X |  |
| Preliminary acceptance checklist |  |  |  | X | X |  |  |
| Acceptance report |  |  |  | X | X |  |  |
| Decide on launch of operation | Launch of operation checklist |  |  |  | X | X |  |
| Launch of operation milestone |  |  |  | X | X |  |  |
| List of steering project decisions |  |  |  | X | X |  |  |

3.4.2.8 IT migration

Table 12: Deployment organization module tasks and outcomes

Purpose

The IT migration module is used to transfer the data to the new system and to decommission
and remove the legacy system.

* * *

What to do

- Design, plan, prepare, and conduct migration.
- Conduct acceptance of migration.

- Conduct acceptance of migration.
- Decommission the legacy system.

- Decommission the legacy system.

Tasks and outcomes

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Design migration concept | Migration concept |  | X |  |  | X |  |
| Conduct migration | Migration carried out |  |  |  | X | X |  |
| Decommission the legacy system | Legacy system removed |  |  |  |  |  | X |
| Decide on acceptance of migration | Acceptance report |  |  |  | X | X |  |
|  | Migration acceptance milestone |  |  |  | X | X |  |
|  | List of management project decisions |  |  |  | X | X |  |
|  | Migration acceptance checklist |  |  |  | X | X |  |
| Realize migration procedure | Migration procedure realized |  |  |  | X | X |  |
|  | Detailed specifications |  |  |  | X | X |  |

Table 13: IT migration module tasks and outcomes

3.4.2.9 IT operation

TheIToperationmoduleisusedtodesignandrealizetheoperatingorganizationattheoperator
and to activate the operation.

What to do
-

- Design and realize operation with infrastructure and operating organization.
- Integrate the system into operation.

| Task | Outcome |
| --- | --- |
|  |  |
| Realize operation | Operating |
|  | Operating |
|  | Operating |
| Activate operation | Operating |
|  | Operation |
| Integrate the system into operation | System in |
|  | Operating |
| Design operating concept | Operating |

|  | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- |
|  | I | C | I | D | E | C |
| organization realized |  |  | X |  | X |  |
| manual |  |  | X |  | X |  |
| infrastructure realized |  |  | X |  | X |  |
| manual |  |  |  | X | X |  |
| activated |  |  |  | X | X |  |
| egrated |  |  | X |  | X |  |
| manual |  |  | X |  | X |  |
| concept |  | X |  |  | X |  |

- Integrate the system into operation.
- Activate operation.

- Activate operation.

* * *

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
|  | Service level agreement |  | X |  |  | X |  |

Table 14: IT operation module tasks and outcomes

3.4.2.10 ISDP

Purpose

In the ISDP module (information security and data protection), the necessary protection measures concerning information security and data protection are defined for the use and operation
of the IT solution.

What to do

- Identify ISDP requirements, assess risks, and design and implement measures to meet
the requirements.
- Design the ISDP concept and document the outcomes on an ongoing basis.

- Design the ISDP concept and document the outcomes on an ongoing basis.

Tasks and outcomes

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Design ISDP concept | ISDP concept |  | X |  |  | X |  |
| Transfer ISDP concept | ISDP concept |  |  |  | X | X |  |
|  | ISDP concept transferred |  |  |  | X | X |  |
| Implement ISDP concept | ISDP concept |  |  | X |  | X |  |
|  | ISDP measures realized |  |  | X |  | X |  |
| Decide on ISDP concept | List of management project decisions |  | X |  |  | X |  |
|  | ISDP concept checklist |  | X |  |  | X |  |
|  | ISDP concept milestone |  | X |  |  | X |  |

Table 15: ISDP module tasks and outcomes

* * *

4 Outcomes

4.1 Introduction

The HERMES project management method is outcome-oriented; outcomes as the most important method components are at the heart of HERMES.

Two types of outcomes are distinguished. An outcome may be:

1. a document that is drafted where possible on the basis of an existing document template
   such as an execution order, a study, a checklist, or a process description;

2. a state thatisnewlyachieved,suchasoperatinginfrastructurerealizedoralsoamilestone

3. a state thatisnewlyachieved,suchasoperatinginfrastructurerealizedoralsoamilestone
   that is the direct consequence of a decision.


Boundaries

The outcome of an entire project (the actual finished solution) or a part thereof (the increment)
are not HERMES method components. This solution may include products, services, IT applications, infrastructures, changed or new operating organizations, new or merged core organizations, or individual organizational units. The project outcome may also consist of trained
users and the activated organization with its processes. At the end of a successful project, the
outcome is a solution, an overall system, consisting of one or more activated elements.

4.2 Overview of outcomes

4.2.1 Standard outcomes

4.2.1.1 Standard documents

| Documents |
| --- |
| Acceptance report |
| Agreement |
| Business model description |
| Change request |
| Change status list |
| Checklists |
| Deployment concept |
| Detailed specifications |
| Evaluation report |
| Execution order |
| Final project evaluation |
| Integration and installation instructions |
| Integration concept |

|  | minimum required documents |
| --- | --- |
|  | X |
|  |  |
|  | X |
|  | X |
|  | X |
|  | X |
|  | X |
|  | X |
|  | X |
|  | X |

* * *

Documents
ISDP concept
Legal basis analysis
Lessons learned
List of management project decisions
List of steering project decisions
Migration concept
Minutes
Offer
Operating concept
Operating manual
Organization concept
Organization description
Organizational requirements
Phase report
Process description
Procurement analysis
Product concept
Product documentation
Project initiation order
Project management plan
Project status report
Protection needs analysis
Prototype documentation
Publication
QA and risk report
Quote request
Release report
Review report
Service level agreement
Situation analysis
Solution architecture
Solution requirements
Stakeholder interests
Stakeholder list
Study
System concept

minimum
required
documents
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X
X

* * *

**minimum** **required** **Documents** **docu-** **ments** Tender documentation X Tender report Test concept X Test report X User manual Work order

Table 16: Overview of outcomes-documents

The minimum required documents marked with an X are required to meet governance require- ments. These include not only those outcomes that must be checked by the auditors, but also all those that must be produced in a module as a "must have". The minimum required documents are the safeguards for ensuring the project's success and reflect a general project situation without addressing the specifics of individual projects. The preparation of the minimum required documents is mandatory. If a module is not relevant for the project, the minimum required documents defined in it are also dropped. They are likewise dropped if, under certain circumstances, their use is not foreseen in the module (e.g. in the case of traditional/agile). The minimum required documents can also be adapted to the specific needs of the core organization in accordance with its governance provisions.

## 4.2.1.2 Standard states

The following table lists all the standard states. **States** Deployment measures carried out Deployment measures realized Interfaces realized ISDP concept transferred ISDP measures realized Legacy system removed Migration carried out Migration procedure realized Milestones Operating infrastructure realized Operating organization realized Operation activated Organization activated Organization implemented Product activated Product developed or adapted Prototype realized

46/244

* * *

| States |  |
| --- | --- |
| System activated |  |
| System developed or parameterized |  |
| System integrated |  |
| Test infrastructure realized |  |
| Test infrastructure transferred |  |
| Table 17: Overview of outcomes - states |  |

4.2.2 Customized outcomes

Table 17: Overview of outcomes - states

Supplementing the standard documents and states, it is possible to integrate further specialist,
organization-specific, or project-specific outcomes in one's own modules. This is supported by
HERMES online and is especially relevant when new modules with new tasks are developed.
Examples of customized outcomes can be core organization-specific reports or a completed
consultation.

4.3 Explanation regarding outcome description

Foreachoutcome,adescriptionoftheoutcomeisprovidedthatisalwaysstructuredinthesame
way:
-

- Description
creates a fundamental understanding of the outcome.

creates a fundamental understanding of the outcome.
Content (for documents only)

- Content (for documents only)
describes the proposed content of a document (see document templates below).

describes the proposed content of a document (see document templates below).
Where applicable, each content note is marked with "A" for agile or "T" for traditional.

Where applicable, each content note is marked with "A" for agile or "T" for traditional.
- Relationships (online only)

- Relationships (online only)
show how the outcome relates to modules, roles, and tasks.

show how the outcome relates to modules, roles, and tasks.
- Templates (online only)

A document template is available for all documents. The template is a concrete aid for
deeper understanding of the application of HERMES documents. The document templatescan, however, beadaptedtotheneedsoftheorganizationorreplacedbyadequate
tool-supported solutions (see Section "User Information").

- Item being accepted
- Those involved in acceptance

- Templates (online only)
A document template is available for all documents. The template is a concrete aid for

- Those involved in acceptance
- Basis

- Basis
- Acceptance procedure

4.4 Description of the outcomes

- Acceptance procedure
- Acceptance criteria with defect categories

The acceptance report is created for decisions on preliminary acceptance, acceptance, and
acceptance migration. It documents compliance with the agreement on solution characteristics
(product/service/system) and existing defects. It is a legally binding document.

4.4.1.1 Acceptance report
Description

4.4.1 Documents

- Acceptance criteria with defect categories
-

- Delivery outcomes and defects, incl.

* * *

- Measures - Responsibilities - Deadlines
- Acceptance outcome - Signatures

## 4.4.1.2 Change request

**Description** Thechangerequestfor traditionally managedsolutiondevelopmentformsthebasisforachange in content. It includes the description of the change to be made, as well as the request, the procedure for making the change, and the proposed solution for implementing the change. The change request acts as a requirement to be met and specifies the change to be made in detail. In the case of agile solution development, the change request comes into play when changes are identified by the execution organization that affect the project objectives, the budget, or the time frame of the overall project.

**Content**

- Change request number - Requester - Date of request
- Reason for change - Description of the change - Information on execution
- Proposed solution - Impact assessment - Effort
- Costs - Deadline - Risks

## 4.4.1.3 Change status list

**Description** Thechangestatuslistisusedtoenumerateandmonitorchangesaswellasdocumentalladded, deleted, or changed functions or other modifications. It supports the comprehensibility of the project progress (governance) and provides an overview of the processing status and-if the changes are made-the status of the changes. A change request resulting from agile solution development which affects the objectives, costs, ordeadlinesoftheoverallprojectisprocessedinthetraditionalwayandrecordedinthechange status list table as a traditional change, i.e. all information according to column K must be entered.

**Content** For each change: (T=traditional, A=agile)

- Change request number (T) - Requester (T) - Date of request (T/A)
- Change/brief description (A) - Decision maker (T) - Status (T/A)
  48/244

* * *

- Change date (T/A) - Person responsible for the change (T) - Effort (T)
- Cost (T) - Impact (T)

## 4.4.1.4 Offer

**Description** The offer specifies the service or product proposed by the developer/operator. The offer also includes all commercial elements such as effort, costs, warranties, guarantees, rights to outcomes, etc. The offer describes the processes and procedures for the provision of the goods/services and/or for the installation and integration of products/systems. **Content** The structure of the offer is based on the purchaser's specifications.

## 4.4.1.5 Tender report

**Description** In the case of public procurement, a report on the opening of tenders is prepared after the submission deadline. On a case-by-case basis, all points relevant to procurement law and procurement evaluation are also recorded in the report. **Content**

- Procurement item - Date - Tenderer/offer
- Subject matter - Opening report

## 4.4.1.6 User manual

**Description** The user manual contains all the information that the user of a product/system needs to use it properly and to be able to react correctly in the event of problems. **Content**

- Overview - Functions - Detailed descriptions of use
- Defect handling

## 4.4.1.7 Work order

**Description** The work order contains all relevant information for completing a set task. The project manager uses it to give orders to the project staff within the framework of project planning, management, information, and monitoring. Work orders can be issued internally or externally. Any solution- specific orders must be coordinated with the user representative in advance.

49/244

* * *

**Content**

- Work objectives - Outcomes - Boundaries
- Prerequisites and dependencies - List of activities with - Reference to the outcomes
- Activity - Those responsible/involved - Plan hours
- Deadlines - Status - Resource requirements
- Presentation of outcomes - Quality assurance

## 4.4.1.8 Tender documentation

**Description** The tender documentation includes all information published in the context of a call for tender. This includes first and foremost the specifications, together with the catalogue of criteria, which is an indispensable part of the tender documentation. The purchaser often has organization- specific tender documentation that should be prioritized. The tender documentation additionally includes a draft contract, general terms and conditions of the core organization, the tender notice, and further specification enclosures. If questions are answered in a public tender, the questions and answers are likewise part of the tender documentation and are given to all tenderers. **Content**

- Specifications with - Background with - Introduction, purpose of the document
- Reason for the tender, need for action - Procurement item - Description of the situation with
- Organization - Strengths and weaknesses - Quantities and frequencies
- Scope and price - Target situation with - Objectives and requirements
- Mandatory and discretionary criteria - Scope - Price (range)
- Deadlines - Structure of the offer - Administrative details
- List of criteria with - Eligibility and award criteria - Weighting
- Points
  50/244

* * *

- Appendices such as - General terms and conditions - Draft contract
- Tender notice - Additional tender documentation

## 4.4.1.9 Procurement analysis

**Description** The procurement analysis describes the concrete need for action, what is to be procured by whom and when, how the market presents itself, which other framework conditions must be observed, and which procurement procedure applies. The analysis is coordinated with the con- trolling and compliance bodies. Asasupplementtothestudy,theprocurementanalysisformsthebasisforthedecisionwhether or not to release continuation of the project. It is also a prerequisite for drawing up the project management plan and the execution order. **Content**

- Reason for procurement, need for action - Procurement contents with - Procurement needs
- Procurement item with type, condition, and quality - Availability on the market - Tenderers and suppliers with
- Possible tenderers and suppliers - Existing suppliers - Existing contracts and their duration
- Requirements for tenderers - Selection of potential tenderers - Desired distribution type
- Roles and their responsibilities with - Tasks and responsibilities of project manager - Tasksandresponsibilitiesofprojectteamincludingcontact/coordinationpointforten- derers and suppliers
- Tasks and responsibilities of procurement unit/purchasing - Scheduling aspects - Financial aspects
- Approximate preliminary costing/efficiency preview - Procurement law aspects - Standards of procurement:
- What documents are used in procurement? - How are the process steps in procurement designed? - Forms of contract:
- What forms of contract are used? - Coordination of processes:
- How are the interdependencies between the procurement process and other up- stream or downstream processes managed?
- Does procurement differ depending on the solution option from the study? - Procurement plan - Tender procedure
- Procedure for questions about the tender, the documents
  51/244

* * *

## 4.4.1.10 Operating manual

**Description** The operating manual provides all the information the operator needs to operate the system properly and to be able to react correctly in the event of problems. All operating information of relevance for the operator is documented in the operating manual. During agile solution development, the operating manual is updated several times, per itera- tion/release, according to the activation of a complete part of the solution. **Content**

- System overview - Launch of operation - Prerequisites for the launch of operation
- Launch of operation process - Quality assurance after the launch of operation - System acceptance specifications
- Implementation and monitoring of operation - Interruption or termination of operation - Support organization with
- Support processes - Organization with roles - Change management with
- Change management process - Change management organization with - Roles
- Contact details - Security provisions - Appendices
- Operating concept - Integration concept

## 4.4.1.11 Operating concept

**Description** The operating concept describes the operating organization with the organizational structure and operating processes of the operator. The operating concept forms the basis for creating the operating manual and the organization of the operator. **Content**

- Operation requirements - System technology - IT infrastructure concept
- Systems, components used, versions - Networks - Data security
- Archiving - Organization - Organizational structure
- Operating process - System operation with
  52/244

* * *

- Normal operation - System monitoring - Work preparation
- Troubleshooting - Description of security aspects - Requirement coverage

## 4.4.1.12 Detailed specifications

**Description**

In traditional solution development, the detailed specifications describe the functional and qual- itative solution characteristics. They are based on the solution requirements and the product concept or, in the case of IT projects, the system concept and the solution architecture. They are designed in sufficient detail in terms of content and planning to form a reliable basis for the realization (development and adaptation or development and parameterization) of the solution. The detailed specifications form the basis for the creation of detailed test case descriptions. In agile solution development, the detailed specifications largely correspond to a sprint backlog, but from a project management perspective serve only to document the current planning of those requirements that the execution organization has selected and that are to be completed within the respective iteration. The detailed specifications are continued in an iterative and incremental manner as part of the manage and control project task, so that the requirements of previous iterations that have already been completed in the document are each supplemented by a new chapter. Alternatively, it is possible to make only a reference to the documentation in the development framework.

**Content**

In traditional solution development, the content of the detailed specifications depends on the item being implemented and the specification method used. The following specification is pos- sible on a supplementary basis:

- Detailed requirements with - Organizational requirements - Functional requirements
- Quality requirement, framework condition
  In agile solution development, on the other hand, the content is characterized by the agile de- velopment methods used.

## 4.4.1.13 Execution order

**Description**

The execution order forms the framework and the binding basis for solution development and subsequent project closure and authorizes continuation of the project. It contains all essential solution-specific information as well as indications of the procedure in the next phases. It is a binding agreement between the project sponsor and the project manager.

**Content**

- Background and need for action - Objectives - Solution objectives
- Project procedure objectives with
  53/244

* * *

- Traditional/agile approach - Scenario - Further project procedure objectives
- Framework conditions, strategy reference and boundaries - Summary description of the solution - Strategy reference and implementation of requirements
- Legal basis - Investment requirements - Resource and aid requirements
- Cost/benefit/economic efficiency (preview) - Planning and organization - Approach (development management)
- Risks - Consequences - Liabilities

## 4.4.1.14 Deployment concept

**Description** The deployment concept describes the measures for deployment of the solution and the de- ployment organization. This includes the measures of organizational change management to support the transition to the new state, the training concept, the planning of acceptances includ- ing acceptance criteria, and the release criteria for the launch of operation. **Content**

- Background - Impact analysis - Deployment procedure
- Deployment measures with - Organizational transition/change management - Emergency measures and emergency organization
- Training concept with - Requirements - Training procedure
- Training materials - Training infrastructure - Deployment organization
- Deployment planning - Planning of preliminary acceptance and acceptance with - Acceptance criteria
- Release criteria for the launch of operation

## 4.4.1.15 Evaluation report

**Description** The evaluation report summarizes the results of the tender evaluation. It forms the basis for the award decision.

54/244

* * *

**Content**

- Background - Procedure for the evaluation - Members of the evaluation team
- Evaluation process - Call for tender, questions, and tender opening - Results of the evaluation with
- Eligibility criteria - Technical specifications - Award criteria
- Evaluation procedure - Evaluation of tenders (performance value/economic efficiency) - Comparison of tenders
- Selection and justification - Recommendation with - Most suitable tender (performance value)
- Most economically efficient tender (cost/benefit) - Best tender (performance value/economic efficiency) - Requests
- Signatures - Appendices with - Completed list of criteria
- Evaluation - Other appendices

## 4.4.1.16 Business model description

**Description** The business model description includes all organizational aspects that are relevant for the solutionandthatcanbeinfluencedbythesolution,anditprovidestheframeworkfortheprocess structure and organizational structure. It is based on the elements of the business model of an organization, reinforces the holistic view of the organization, and encompasses a selection of components such as customer segmentation and customer relationships. **Content** The content is strongly influenced by the project and the approach as well as the core organi- zation.

- Business model overview - Customer segments - Value propositions
- Channels - Communication channels - Distribution channels
- Sales channels - Customer relationships - Key activities on
- Value propositions - Markets - Customer relationships
- Key resources
  55/244

* * *

- Physical - Financial - Intellectual
- Personnel - Key partnerships - Revenue sources
- Cost structure - Cost-oriented business model - Value-oriented business model

## 4.4.1.17 Integration and installation instructions

**Description** The integration and installation instructions describe how the system is integrated and installed in the operating infrastructure. **Content**

- Current situation - Prerequisites - Integration and installation activities
- Error and defect handling - Support - Integration organization
- Acceptance

## 4.4.1.18 Integration concept

**Description** The integration concept describes how the system is integrated into the environment. It also describeshowtransportfromonesystemenvironmenttoanothertakesplaceandhowtoensure configuration management and quality. In the case of deployment with implementation units (traditional) or step-by-step integration with releases (agile), the planning of implementation units or release planning according to the project management plan is part of the integration concept. **Content**

- System overview and integration items - Integration objects and interfaces - Integration environments
- Integration steps - Transport and deployment overview - Framework conditions and interdependencies
- Integration organization - Risks - Quality assurance
  56/244

* * *

4.4.1.19 ISDP concept

Description

The ISDP concept forms the basis for defining the information security and data protection
(ISDP) measures. It shows the residual risks associated with the operation of the system and
the organization.

Content

The content is based on the requirements of the core organization.

4.4.1.20 List of management project decisions

Description

Thelistofmanagementprojectdecisionsdocumentstheoutcomesofthedecision-makingtasks
of the management hierarchy level. The list is used for the entire duration of a project.

Content

- Decision
-

- Underlying documents
- Decision-makers at the management and/or execution hierarchy level

- Milestone achieved yes/no
-

- Decision-makers at the management and/or execution hierarchy level
- Date

- Date

4.4.1.21 List of steering project decisions

The list of steering project decisions documents the outcomes of the decision-making tasks of
the steering hierarchy level. The list is used for the entire duration of a project.

- Decision
-

In traditional solutiondevelopment,thesolutionrequirementsarepreparedintheconceptphase
onthebasisofthestudyandthesituationanalysisinthefinallevelofdetailandaresuccessively
updated during solution development via change management as needed.

- Underlying documents
- Decision-makers at the steering hierarchy level

The solution requirements include all the requirements that the future system or product must
fulfill. Thisincludesthespecialistandtechnicalrequirements, butalsoexpectedcharacteristics,
functions, legal and solution-relevant and regulatory requirements, operational, support and
security requirements, as well as requirements for optimization and defect correction of any
existing products or systems.

- Decision-makers at the steering hierarchy level
-

- Date

4.4.1.22 Solution requirements task). **Content**

- Rough requirements - Requirements catalogue - Detailed solution requirements

## 4.4.1.23 Solution architecture

**Description** The solution architecture is based on the system concept and divides the system into subsys- tems and their components. It describes the system structure and the interfaces. The solution architecture allows for a comprehensive view of the system. Depending on the project outcome and scope, it contains several architecture elements and models, e.g. the business process model, the function model (e.g., with use cases/user stories), the data architecture/data model, and the security architecture. It also contains the IT documentation or refers to the developer's documentation. The outcomes of the system concept are summarized in an appendix to the solution architecture. The solution architecture takes into account the specifications of the controlling and compliance bodies. **Content**

- System structure - Overview of the system - Subsystems and components
- Solution architectures/models - Interfaces and scope - Interfaces with peripheral systems
- Reference to integration concept - Boundaries - Feasibility assessment
- Compliance with specifications - Requirement assignment and coverage - Outcomes of the system concept

## 4.4.1.24 Migration concept

**Description** The migration concept describes the technical and organizational requirements for migration and contains the migration procedure concept. The migration concept proves feasibility and shows migration planning. Aside from technical and organizational requirements, the auditing, information security and ISDP requirements are also taken into account. **Content**

- Migration objectives - Migration requirements - Migration items
- Data analysis - Migration procedure - Migration plan
- Feasibility
  58/244

* * *

- Archiving and decommissioning of the legacy system - Requirement coverage

## 4.4.1.25 Quote request

**Description** Offers for various services internal and external to the organization are obtained with the quote request. The offers form the basis for the service level agreement as described in the agree on and steer goods/services task. The quote specifications allow the offers to be compared and evaluated.

**Content**

- Sponsor - Background - Subject of the order
- Deadlines - Conditions - Quote specifications
- Administrative process for procurement

## 4.4.1.26 Organizational requirements

**Description** The organizational requirements define whether a new or updated business model is needed and/orwhethertheorganizationalandprocessstructureischanging. Theyincludethosecontex- tual, business, and organizational requirements that strengthen the internal organization within the framework of the future solution and enable the solution itself to be more effective. In addition to the traditional aspects specific to the organizational and process structure, they also include the requirements on economic efficiency, effectiveness, and efficiency as well as the objectives of the core organization and the organizational strategy derived from the ob- jectives, often manifested in a business model that defines the framework into which the new organization must be fitted.

**Content** The content is strongly influenced by the project and the approach.

- Background - Direction of the planned/changed business model - Direction of the planned/changed organizational structure
- Direction of the planned/changed process structure - List of requirements

## 4.4.1.27 Organization description

**Description** The organization description describes the organizational structure with a detailed organiza- tion chart, function descriptions, and personnel requirements. It forms the basis for assigning positions.

59/244

* * *

**Content**

- Organization chart - Organizational interfaces - Function descriptions
- Personnel requirements

## 4.4.1.28 Organization concept

**Description** Theorganizationconceptgoesintomoredepthaboutthesolutionoptiondescribedandselected in the study from an organizational perspective. It is based on the organizational requirements, supplementedwhereneededbythefindingsfromthesolutionrequirements,anditdescribesthe relevant business model aspects as well as the organizational and process structure (business processes) for business processing and support. It shows which new organization is created and which changes are made to what already exists. **Content**

- Background - Organizational requirements - Business model
- Organizational structure - Process structure - Overview of changes
- Requirement coverage

## 4.4.1.29 Phase report

**Description** The phase report forms the basis for deciding on the release of the next phase and for updating the project status report. It summarizes the outcomes and decisions of the current phase and shows the organization of the next phase. **Content**

- Background - Strategy reference and implementation of requirements - Benefits and economic efficiency
- Legal basis - Planning and organization - Forecast regarding objective achievement and solutions
- Problems and measures - Risks - Requests
- Conclusion
  60/244

* * *

## 4.4.1.30 Product documentation

**Description** Product documentation refers to the technical documentation of the product. All of the docu- mentation defined in the development process together forms the product documentation. It is a prerequisite for the maintenance and further development of the product. **Content** Thecontentoftheproductdocumentationdependsontheoutcomesdefinedinthedevelopment process.

## 4.4.1.31 Product concept

**Description** The product concept goes into more depth about the solution option described and selected in thestudy. Itisbasedonthesolutionrequirements, supplementedwhereneededbythefindings from the organizational requirements, and it describes the product to be created. Depending on the product and the complexity of the solution requirements, its structure and level of detail vary. **Content**

- Background - Requirements - Boundaries
- Intended use - Product classifications - Product description
- Variants

## 4.4.1.32 Lessons learned

**Description** The lessons learned are systematically collected and continuously documented as a project review. They support the continual improvement process in the project and in the core orga- nization. They provide valuable information for the further course of the project and possible indicators for subsequent projects by identifying and adopting positive aspects and preventing negative aspects as far as possible. **Content**

- Contact - Subject area - Date
- Lessons learned: positive/negative - Relevance: possible significance for own project or other projects - Possible causes
- Recommendation: information for the core organization
  61/244

* * *

## 4.4.1.33 Project initiation order

**Description** The project initiation order forms the binding basis for the release of the initiation phase. It is the agreement between the project sponsor and project manager for the initiation phase.

**Content**

- Background - Objectives - Objectives of the initiation phase
- Parameters - Resource requirements with - personnel costs
- materials - costs - Deadlines
- Project organization and personnel - Communication - Risks

## 4.4.1.34 Project management plan

**Description** The initial development of the project management plan is influenced by the decision on next steps in the initiation phase. The decision on the approach in particular -traditional or agile - influences the execution of the tasks and the structure and content of the outcomes. The project management plan contains the overall planning of the project and the essential regulations on methods, techniques, roles, and tools determined for the specific project. The project management plan serves as a uniform basis for action for everyone involved in the project. As part of project organization, the project management plan ensures that the respon- sibilities and the division of tasks between service recipients, internal service providers, and external suppliers where applicable are sufficiently clearly regulated and documented. As the projectprogresses,itiscontinuouslyfleshedoutandupdatedaccordingtotheprincipleofrolling planning and steering. In agile solutiondevelopment, the schedule for the executionphase is combined with the (agile) release plan. This release plan specifies when operation is activated for each release. It also specifies whether the (optional) release decision is mandatory in the project or not. At the end of the phase, the project management plan is adapted to the changed conditions for the next phase. Before the closure phase is released, the project management plan for project closure is also prepared and adapted accordingly.

**Content**

- Project description - Summary - Phases and milestones ( traditional ) or releases ( agile )
- Release yes/no ( agile ) - Scenario with execution structure plan - Execution organization with
- Project organization chart - Roles in core and project organization - Assignment of roles (including the execution organization (agile))
  62/244

* * *

- Project outcome structure
- Quality objectives and specifications (for execution)

- Quality objectives and specifications (for execution)
- Review plan (QA)

- Review plan (QA)
- Execution planning with

- Execution planning with
- Schedule

- Schedule
- Release plan ( agile ) with

- Release plan ( agile ) with
- Releases

- Releases
- Dependencies and requirements

- Dependencies and requirements
- Organization

- Organization
- Deadlines

- Deadlines

- Cost plan/approved budget
- Resource plan

- Resource plan
- Procurement plan

- Procurement plan
- Communication plan

- Communication plan
- Stakeholder management (project-specific)

- Stakeholder management (project-specific)
- Reporting

- Reporting
- Specifications, methods, work instruments, and tools

- Specifications, methods, work instruments, and tools
- Quality assurance

- Change management
- Risk management

- Quality assurance
- Change management

- Risk management
- Escalation procedure

- Escalation procedure
- Document management

- Document management

4.4.1.35 Final project evaluation
Description

Description

The final project evaluation forms the basis for the project closure decision. It gives the project
sponsor information on the target/actual comparison with regard to the project and procedure
objectivesintermsofdeliverables,scheduling,andfinances. Thecontentofthelessonslearned
outcome is documented in a summary. The content and deadlines for project success monitoring are set.

- Background
- Evaluation of the achievement of objectives
- Economic efficiency

- Economic efficiency
- Target/actual comparison

- Directly from the project with
- Pending item

- Target/actual comparison
- Costs/benefits

- Implementation deadline
Further measures after project closure with

- Implementation deadline
- Further measures after project closure with
- Measure

- Deadlines
- Outcomes

- Those responsible
-

- Implementation deadline

* * *

- Request

## 4.4.1.36 Project status report

**Description** The project status report is used for periodic reporting on the project status, project progress, andforecastsastohowtheprojectwillproceed. Theformandmethodofreportingaresetoutin theprojectmanagementplan. Theprojecttakesaccountofthecoreorganization'srequirements with regard to reporting content and frequency. **Content**

- Overview of project status - Forecast regarding objective achievement (agile: burndown chart) - Target/actual comparison and forecasts
- Costs/benefits - Effort - Deadlines
- Outcomes - Problems and measures - Risks
- Outlook

## 4.4.1.37 Minutes

**Description** The minutes document, firstly, the decisions and orders that are made or placed in a meeting and, secondly, important management and execution processes that must be traceable later as needed. Important discussion and action points are recorded. Orders recorded in the minutes are transferred to a to-do list. In general: The full set of minutes ensures the traceability and comprehensibility of decisions and pro- cesses. **Content**

- Header section - Meeting type / Topic - Date / Time / Place
- Chair / Minutes - Participants / Absentees - Minutes section with
- Welcome / Approval of last minutes, if applicable - Individual agenda items discussed - Decision list
- Information on the next meeting, if applicable - To-do list (appendix)
  64/244

* * *

## 4.4.1.38 Prototype documentation

**Description** The prototype documentation forms the basis for the creation and evaluation of the prototype. It records the prototyping objectives, requirements, outcomes, and conclusions. **Content**

- Background - Parameters - Requirements
- Concept - Prototype concept - Required infrastructure
- Summary of test results - Reference to test concept - List of test cases
- Summary of test protocols, test report - Conclusions - Recommendations

## 4.4.1.39 Process description

**Description** The process description is a detailed process structure down to the individual process level, describing the processes with the tools used. **Content**

- Overview of the processes - For each process: - Process description (according to eCH-0140)
- Tabular process flow - Graphical process flow

## 4.4.1.40 Review report

**Description** The review report records review findings and documents the implementation decisions con- cerning the findings, as well as the decision on the status of the outcome. **Content**

- Outcome to be checked - Review date - Reviewer
- Findings - Decisions on findings - Outcome decision
  65/244

* * *

## 4.4.1.41 Publication

**Description** The publication provides information about the award for the tender concerned. The form and content of the publication are specified by the controlling and compliance bodies or the procure- ment office. In Switzerland, public tenders are generally published via [www.simap.ch](http://www.simap.ch/). **Content**

- Tender concerned - Procurement office - Successful tenderer
- Legal means

## 4.4.1.42 QA and risk report

**Description** The QA (quality assurance) and risk report is prepared by the quality and risk manager (QRM) after being commissioned by the project sponsor. It provides independent information on the quality and risk situation of the project. The content of the QA and risk report depends on the mandate and scope, as well as on the methods used. **Content**

- Mandate and scope - Procedure - Overall assessment with project status
- Quality assessment - Risk assessment - Recommendations

## 4.4.1.43 Release report

**Description** Under the agile approach, the release report provides an overview of the project's success so far, forming the basis for the preparation of the project status report and, depending on the provision in the project management plan, also for the decision on approval of any next release. It summarizes the outcomes and decisions of the current release and provides an overview of the remaining outlay for the project. **Content**

- Background - Strategy reference and implementation of requirements - Benefits and economic efficiency
- Content of the release - Known errors - Burndown chart
- Risks - Conclusion
  66/244

* * *

## 4.4.1.44 Legal basis analysis

**Description** Thelegalbasisanalysisdescribestheexistingandapplicablelegalbasisfortheprojectoutcome andthepossibleneedforittobeamended. Specialattentionispaidtothecommunal, cantonal, national, and-where applicable-international legal as well as product-relevant and regulatory requirements that the envisaged solution, including its effects on the peripheral systems, must comply with (product compliance).

**Content**

- Existing legal basis - Imminent changes - Gaps identified
- Proposals to close gaps - Notes concerning product compliance - Evaluation of the consequences
- Recommendations

## 4.4.1.45 Protection needs analysis

**Description** The protection needs analysis, or ISDP analysis, documents the information security and data protection requirements. These are to be taken into account within the framework of the re- quirements of the core organization when developing the solution.

**Content** The content is based on the requirements of the core organization.

## 4.4.1.46 Service level agreement

**Description** A service level agreement (SLA) is a contractual agreement between the operator and the user, represented by the sponsor and the user representative. The SLA specifies the services to be provided by the operator, defines their service level (quality of service), and formulates any measures and penalties for non-compliance. As a rule, the agreed services and their service levels are subject to a charge. If operations are outsourced, SLAs can be an important factor in evaluating the potential oper- ator.

**Content** The content of an SLA is specified by the core organization. An external provider may already have a predefined SLA. The SLA may cover points including the following:

- Preamble with - Subject matter - Objectives
- Partners - Scope - Entry into effect, duration, cancellation
- Services - Remuneration with
  67/244

* * *

- Transfer prices - Invoicing - Payment modalities
- Reporting with - Service level reports (standard reports) - Other reports (as needed)
- Consequences of deviation from agreed service levels - Rules for monitoring the SLAs (SLA audits)
- Rules for changing the SLAs - Rules for resolving conflicts - Data protection
- Liability and warranty - Damages - Applicable law
- Legal venue - Arbitration - Confidentiality, secrecy, and publication
- Partial invalidity of provisions - Signatures - Enclosures

## 4.4.1.47 Situation analysis

**Description** The situation analysis describes and analyzes the current situation and future developments by supplementing the rough status report in the study and going into more depth. The overall solution and influence area of the option selected in the initiation phase is used to determine the area of investigation. In addition to compiling the essential quantities and frequencies, the situation analysis in particular addresses the deficiencies and weaknesses that must be eliminated as far as possible with the future solution, and it defines the existing strengths that are to be preserved. The situation analysis examines whether the organization module is relevant. The situation analysis forms the specialist basis for the definition of the solution and organiza- tional requirements to be met by the project outcome. It is neutral in terms of objectives and solutions. **Content**

- Current situation - Current organization (if relevant) with - Business model/business perspective
- Organizational structure - Process structure - Description, if available, of the current solution (current system/current product)
- Objective and intended use, function - Documentation on the existing solution such as - Original solution description/solution concept
- Parameters and specifications - User documentation - Operating manual
- ISDP - Interfaces and peripheral systems (organizational/technical)
  68/244

* * *

- Operating costs - Quantities and frequencies - Analysis of strengths, weaknesses, and causes
- Description of the current overall context - Strengths and weaknesses analysis - Conclusion and need for action

## 4.4.1.48 Stakeholder interests

**Description** The stakeholder interests form the basis for informing the stakeholders and for direct cooper- ation with them. The analysis of stakeholder interests is conducted separately from the stake- holder list. This analysis is a subjective, internal project assessment and not a public outcome. The stakeholder interests are needed for communication and for cooperation with stakeholders and are regularly updated.

**Content**

- Stakeholder positioning - Stakeholder description - Identified conflicts of interest and objectives

## 4.4.1.49 Stakeholder list

**Description** The stakeholder list is developed for the first time in the initiation phase and forms the basis for managing the stakeholders, for direct cooperation with them, and for communication planning. It is continuously updated over the course of the project.

**Content**

- Stakeholders

## 4.4.1.50 Study

**Description** The study describes the desired solution by defining the objectives - based on the status report - in terms of the benefits sought. It lists possible solution variants and the proposed procedure, then evaluates them. It corresponds to the business case and shows the business benefits as wellasthereferencetothestrategyandtheobjectivesofthecoreorganization. Allaspectsthat haveaninfluenceontheplannedsolutionorthatcanbeinfluencedbythesolutionarementioned in the study. In addition, the appropriate scenario (see Section "Scenarios") is selected, a user- defined scenario is created where appropriate, and the future value of the project is estimated. The study is detailed only to the extent that the direction of the envisaged project is clear and the decision on next steps can be made. The lean approach applies in particular to the status report so as not to prolong the initiation phase unnecessarily. The decision on next steps documented in the study forms the basis for preparing a decision on whether or not to continue a project. The study is the prerequisite for drawing up the project management plan and the execution order.

69/244

* * *

**Content**

- Background - Status report from a business perspective with - Business organization
- Product or IT system - Quantities and frequencies - Information security and data protection
- Description of the current overall context - Strengths and weaknesses analysis - Analysis and evaluation
- Objectives - Framework conditions, strategy reference and boundaries - Parameters
- Rough requirements - Solution options with - Option overview
- Description per option, incl. proposed approach - Analysis and evaluation with - Degree of objective achievement
- Requirement coverage - Cost/benefit/economic efficiency considerations - Risk assessment (project and operational risks)
- Further criteria such as sustainability, etc. - Proposal and decision on next steps - Solution option
- Scenario - Procedure - Project value
- Planning and deadlines - Scenario and modules - Project deadlines, milestones
- Planned period of use

## 4.4.1.51 System concept

**Description** The system concept goes into more depth about the solution option described and selected in the study. It is based on the solution requirements and shows how the solution meets those requirements. The system concept can describe and evaluate several system options. There can be several system concepts on different topics. **Content**

- Background - Requirements - Solution concept with system options For each system variant:
- Description - Requirement coverage - Feasibility assessment
- Comparison of options - Recommendation
  70/244

* * *

## 4.4.1.52 Test concept

**Description** The test concept describes the test objectives, test objects, test types, test infrastructure, and test organization. It also includes test planning and test case descriptions. A detailed test case description is created for each test case. This constitutes the test specifications. Test planning determinesthelogicalandchronologicalstructureofthetests. Thetestconceptformsthebasis on which the test organization and test infrastructure are provided and the tests are carried out. The test concept is updated if new findings arise. **Content**

- Test objectives - Test strategy and test levels - Test objects
- Test types - Test coverage - Overview of test cases
- Assessment of test objectives and test coverage - Test framework with - Test prerequisites
- Defect classification - Starting and abandonment conditions - Test environment
- Test case descriptions - Test plan - Test organization and responsibilities
- Test infrastructure with - Test system - Test data
- Test tools

## 4.4.1.53 Test report

**Description** The test report records the test results. The test results are evaluated according to the defect classes defined in the test concept. **Content**

- Test cases from the test concept - ID - Designation
- Test date - Tester - Description of defect / Comments
  71/244

* * *

## 4.4.1.54 Agreement

**Description** The agreement governs the cooperation between different project participants, mainly between theuser(projectsponsor)andthedeveloper. Theagreementcanbeconcludedforoneormore phases. Agreements are differentiated according to project agreement and contract.

**Content** The content of agreements is stipulated by the core organization. The agreement may include, but is not limited to, the following points:

- Deployment - Elements of the contract - Scope
- Scope of goods/services and outcomes - Persons deployed - Cooperation duties
- Quality assurance and acceptance - Warranty - Data protection and data security
- Change management - Reporting - Effort and costs
- Signatures - Supplementary technical standards - Regulations
- Directives

## 4.4.2 Checklists

Description Checklists are part of the documents. They are used to support decision-making. They repre- sentlistsofmonitoringandreviewstepswhichmustbeexecutedsystematicallyandcompletely within the scope of a decision preparation. This reduces the probability of wrong decisions, given that all essential aspects are taken into account. Each checklist is tailored to a specific decision and specifies the necessary review points with outcomes, release criteria, evaluation, those responsible, and review date. The checklist can be supplemented with additional criteria as part of the decision-making process. All checklists are divided into three sections accordingly:

- General review points - Organization-specific review points - Project-specific review points

## 4.4.2.1 Acceptance checklist

**Description** The acceptance checklist describes review points and criteria that are relevant for the accep- tance decision.

72/244

* * *

## 4.4.2.2 Migration acceptance checklist

**Description** The migration acceptance checklist describes review points and criteria that are relevant for the migration acceptance decision.

## 4.4.2.3 Tender checklist

**Description** Thetenderchecklistdescribesreviewpointsandcriteriathatarerelevantforthetenderdecision.

## 4.4.2.4 Launch of operation checklist

**Description** The launch of operation checklist describes review points and criteria that are relevant for the decision on launch of operation.

## 4.4.2.5 Execution release checklist

**Description** The execution release checklist describes review points and criteria that are relevant for the execution release decision.

## 4.4.2.6 ISDP concept checklist

**Description** The ISDP concept checklist describes review points and criteria relevant for the ISDP concept decision.

## 4.4.2.7 Solution architecture checklist

**Description** The solution architecture checklist describes review points and criteria that are relevant for the solution architecture decision.

## 4.4.2.8 Phase release checklist

**Description** The phase release checklist describes review points and criteria that are relevant for the phase release decision.

## 4.4.2.9 Closure phase release checklist

**Description** The closure phase release checklist describes review points and criteria that are relevant for the closure phase release decision.

73/244

* * *

4.4.2.10 Product concept checklist

Description

Theproductconceptchecklistdescribesreviewpointsandcriteriathatarerelevantfortheproduct concept decision.

4.4.2.11 Project discontinuation checklist

Description

The project discontinuation checklist describes review points and criteria that are relevant for
the project discontinuation decision.

4.4.2.12 Project closure checklist

Description

The project closure checklist describes review points and criteria relevant to the project closure
decision.

4.4.2.13 Project initiation release checklist

Description

The project initiation release checklist describes review points and criteria that are relevant for
the project initiation release decision.

4.4.2.14 Release checklist

Description

The release checklist describes review points and criteria that are relevant for the release decision.

4.4.2.15 Preliminary acceptance checklist

Description

The preliminary acceptance checklist describes all review points and criteria that are relevant
for the preliminary acceptance decision.

4.4.2.17 Contract award checklist

Description

The contract award checklist describes review points and criteria that are relevant for the contract award decision.

The next steps checklist describes review points and criteria that are relevant for the decision
on next steps.

* * *

## 4.4.3 States

## 4.4.3.1 Legacy system removed

**Description** The old system version and the legacy system are decommissioned or removed in accordance with the specifications. The decommissioning also includes the destruction or archiving of data.

## 4.4.3.2 Operation activated

**Description** Operation of the activated system is launched and conducted with the operating organization defined in the operating concept. The activities set out in the operating manual are carried out. The operating staff carry out the operating tasks. The prerequisites for measuring and complying with the SLA are given.

## 4.4.3.3 Operating infrastructure realized

**Description** The operating infrastructure comprises all infrastructures required for the creation and opera- tion of a system with the various system environments (development, testing, production, etc.) and all its components. The operating infrastructure also includes the components needed to supervise operation, such as monitoring and alarm systems, statistical tools, etc.

## 4.4.3.4 Operating organization realized

**Description** The operating organization defined in the operating concept, including the operating organiza- tional structure and operating processes of the operator, is realized. The operating staff are trained and can perform the operating tasks.

## 4.4.3.5 Deployment measures carried out

**Description** The measures described and realized in the deployment concept are executed. The implemen- tation of the measures is reviewed and their quality assurance carried out. For example, user training has been carried out and the participants' course assessments are available for quality assurance.

## 4.4.3.6 Deployment measures realized

**Description** The measures described in the deployment concept and the organization needed for deploy- ment are realized. For example, the superusers are recruited and trained to support the users in deployment, or the training materials are produced so that training can then be carried out.

## 4.4.3.7 ISDP measures realized

**Description** The ISDP measures are realized on the basis of the ISDP concept. They ensure that the re- quirements in terms of protection needs are met in accordance with the ISDP concept.

75/244

* * *

## 4.4.3.8 ISDP concept transferred

**Description** The ISDP concept is updated, checked by the controlling and compliance bodies, and trans- ferred from the project organization to the core organization.

## 4.4.3.9 Migration carried out

**Description** The migration from the old system to the new or further developed system is carried out and documented in accordance with the specifications of the controlling and compliance bodies. The comprehensibility of the migration is ensured. Successful migration is the prerequisite for its acceptance and the decision on launch of operation.

## 4.4.3.10 Migration procedure realized

**Description** The migration procedure realized has been tested by the developer or the developer's tester. Thedeveloperortesterprovidesevidenceofthetestsperformed. Thetestsaretheprerequisite for preliminary acceptance.

## 4.4.3.11 Organization activated

**Description** The new organization is activated. It carries out its processes according to the process descrip- tions. Iftheneworganizationisactivatedunder traditional solutiondevelopment,thisistheprerequisite for activating the product or system. In agile solution development, only the relevant part of the organization is activated.

## 4.4.3.12 Organization implemented

**Description** The organization defined in the organization concept is implemented. Based on the process description and organization description, the measures were realized in order to establish the organization (position assignments, recruitment, etc.).

## 4.4.3.13 Product activated

**Description** The activated product is made available to users for utilization.

## 4.4.3.14 Product developed or adapted

**Description** The developed and/or adapted product has been tested by the developer or the tester of the developer. It is handed over to the user for the tests and preliminary acceptance.

76/244

* * *

## 4.4.3.15 Prototype realized

**Description** The prototype is used to check the feasibility or behavior of a system or product in a specific situation. Prototypes are used to assess and reduce risks. Over the course of the project, several different prototypes can be realized in order to test the feasibilityoftheproject. Adistinctioncanbemadebetweendisposableprototypesandreusable prototypes.

## 4.4.3.16 Interfaces realized

**Description** The interfaces realized ensure the exchange of data between the system and the peripheral systems. The interface has been tested by the developer or the integrator and the developer's tester. It is handed over to the operator for integration into the operating infrastructure.

## 4.4.3.17 System activated

**Description** The activated system is made available to users for utilization.

## 4.4.3.18 System developed or parameterized

**Description** Thedevelopedand/orparameterizedsystemhasbeentestedbythedeveloperortheintegrator and the developer's tester. It is handed over to the operator for integration into the operating infrastructure. Development and integration can take place in several steps or releases.

## 4.4.3.19 System integrated

**Description** The integrated system is available to the user's testers for testing and preliminary acceptance. The system is activated after the decisions on preliminary acceptance and launch of operation.

## 4.4.3.20 Test infrastructure realized

**Description** A test infrastructure consisting of a test system (including all systems for performing tests), test data, and test tools is used to perform the tests. The test infrastructure is provided according to the test concept. The test infrastructure must meet different requirements depending on the test method. Different test systems may then also be required. The test infrastructure is based on the infrastructure of the production system, i.e. on the oper- ating infrastructure realized. The test system must correspond to the production system to the extent that the test case descriptions can be carried out under realistic conditions. Ifnon-anonymizedcopiesofproductivedataareusedastestdataforthetests,therequirements for ISDP must be met.

77/244

* * *

## 4.4.3.21 Test infrastructure transferred

**Description** The entire test infrastructure including the test concept has been transferred to the core orga- nization.

## 4.4.4 Milestones

Description Milestones are states and are always the consequence of a decision. They mark and define a specific point in time reached in the course of the project. Milestones serve as envisaged and achieved decision outcomes for project steering and man- agement, give the project a structure, and mark important points in the course of the project at which decisions are made on next project steps.

## 4.4.4.1 Acceptance milestone

**Description** The milestone is reached when the decision on acceptance is made. The solution is defini- tively transferred to the application organization and, where applicable, also to the operating organization. After that, the warranty begins and with it regular operation.

## 4.4.4.2 Migration acceptance milestone

**Description** The milestone is reached when the decision on acceptance of migration is made. The use of the new system can be released for the users (decide on launch of operation).

## 4.4.4.3 Tender milestone

**Description** The milestone is reached when the decision on call for tenders is made. The tender can be published.

## 4.4.4.4 Launch of operation milestone

**Description** The milestone is reached when the decision on launch of operation is made. The solution can be put into operation.

## 4.4.4.5 Execution release milestone

**Description** The milestone is reached when the decision on execution release is made. Work starts accord- ing to the execution order.

78/244

* * *

## 4.4.4.6 ISDP concept milestone

**Description** The milestone is reached when the decision on ISDP concept is made. Implementation of the ISDP measures can begin.

## 4.4.4.7 Solution architecture milestone

**Description** The milestone is reached when the decision on solution architecture is made. This forms the prerequisite for the development or adaptation of systems.

## 4.4.4.8 Phase release milestone

**Description** The milestone is reached when the decision on phase release is made. The work in the next phase can begin.

## 4.4.4.9 Closure phase release milestone

**Description** The milestone is reached when the decision on closure phase release is made. The provision of goods or services within the scope of solution development is completed. The work in the closure phase can begin.

## 4.4.4.10 Product concept milestone

**Description** The milestone is reached when the decision on product concept is made. The concept is the prerequisite for the development or adaptation of products or services.

## 4.4.4.11 Project closure milestone

**Description** The milestone is reached when the decision on project closure is made. The project is con- cluded.

## 4.4.4.12 Project initiation release milestone

**Description** The milestone is reached when the decision on project initiation release is made. The project has been formally launched. Work starts according to the project initiation order.

## 4.4.4.13 Release milestone

**Description** The milestone is reached when the decision on release is made. Work on the next release can begin under the agile approach.

79/244

* * *

## 4.4.4.14 Preliminary acceptance milestone

**Description** The milestone is reached when the decision on preliminary acceptance is made. This forms the basis for the execution of deployment measures and launch of operation.

## 4.4.4.15 Next steps milestone

**Description** The milestone is reached when the decision on next steps is made. This forms the basis for drawing up the project management plan and the execution order.

## 4.4.4.16 Contract award milestone

**Description** The milestone is reached when the decision on contract award is made. The decision can be published and the contract work with the successful tenderer can begin.

80/244

* * *

# 5 Tasks

### 5.1 Introduction

#### 5.1.1 Positioning of tasks

Outcomes are at the heart of HERMES. They are developed together with the tasks. A task consists of several activities. Activities are used to develop one or more outcomes and to ensure the quality requirements are met. Two types of tasks are distinguished:

- Decision-making tasks, which lead to a decision and end with the milestone outcome. They are further divided into
- Decision-making tasks of steering and - Decision-making tasks of management.
- Other tasks that accompany the course of the project, serve to develop outcomes and solutions, and ensure or increase quality.
  Task descriptions do not replace knowledge of the methods and practices to be applied or corresponding training.

#### 5.1.2 Decision-making tasks

#### 5.1.2.1 General

Decisions have to be made over the course of the project. Tasks that lead to a decision are defined as decision-making tasks. They end with a milestone. HERMES distinguishes between decisions made by project steering and decisions made by project management. For example, the decision on launch of operation is made by the project sponsor (steering), while the decision on solution architecture is made by the project manager (management). At the end of a phase (traditional) or a release (agile, if the decision on release approval is required in the project), steering checks whether the necessary specialist decisions have been made. If this is not the case, the next phase or the next release is not approved. In this way, steering can make decisions without having the necessary expertise itself. Decision-making tasks are supported by checklists.

#### 5.1.2.2 Steering decisions

At the steering hierarchy level, decisions are made by the project sponsor. The project sponsor decidesonprojectinitiationrelease,executionrelease,phaserelease,interimreleaseapprovals where applicable, project closure, project discontinuation where applicable, as well as other important decisions such as initiating a call for tenders, deciding on an award of contract, or approving launch of operation. As needed, the project sponsor is advised and supported by other roles, such as the project committee, the project manager, or the user representative.

81/244

* * *

5.1.2.3Management decisions

Management decisions are decisions of the project manager on project outcomes.

Review and acceptance of technical outcomes is carried out on behalf of management by the
execution level, i.e. by the specialists for the topic in question. Depending on the process
model, the project manager or user representative plans the decision-making tasks, taking into
account the specifications of the controlling and compliance bodies of the core organization.

5.2Overview of tasks

5.2.1Standard tasks

The table shows the assignment of all provided tasks to project phases, including the corresponding outcomes.

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Decommission the legacy system | Legacy system removed |  |  |  |  |  | X |
| Manage changes | Change status list |  | X | X | X | X |  |
| Change request |  | X | X | X | X |  |  |
| Solution requirements |  | X | X | X |  |  |  |
| Project management plan |  | X | X | X | X |  |  |
| Evaluate tenders | Evaluation report |  | X |  |  | X |  |
| Tender report |  | X |  |  | X |  |  |
| Issue call for tenders | Tender documentation |  | X |  |  | X |  |
| Offer |  | X |  |  | X |  |  |
| Prepare call for tenders | Tender documentation |  | X |  |  | X |  |
| Prepare procurement analysis | Procurement analysis | X |  |  |  |  |  |
| Activate operation | Operating manual |  |  |  | X | X |  |
| Operation activated |  |  |  | X | X |  |  |
| Realize operation | Operating organization realized |  |  |  | X | X |  |
| Operating manual |  |  |  | X | X |  |  |
| Operating infrastructure realized |  |  |  | X | X |  |  |
| Design operating concept | Operating concept |  |  | X |  | X |  |
| Service level agreement |  |  | X |  | X |  |  |
| Design deployment concept | Project management plan |  |  | X |  | X |  |
| Deployment concept |  |  | X |  | X |  |  |
| Execute deployment measures | Deployment measures carried out |  |  |  | X | X |  |
| Realize deployment measures | Deployment measures realized |  |  |  | X | X |  |
| Decide on acceptance | Acceptance report |  |  |  | X | X |  |
| Acceptance checklist |  |  |  | X | X |  |  |
| List of management project decisions |  |  |  | X | X |  |  |
| Acceptance milestone |  |  |  | X | X |  |  |
|  |  | I | C | I | D | E | C |
| Decide on call for tenders | Tender checklist |  | X |  |  | X |  |
| List of steering project decisions |  | X |  |  | X |  |  |
| Tender milestone |  | X |  |  | X |  |  |
| Decide on launch of operation | Launch of operation checklist |  |  |  | X | X |  |
| Launch of operation milestone |  |  |  | X | X |  |  |
| List of steering project decisions |  |  |  | X | X |  |  |
| Decide on execution release | Execution release milestone | X |  |  |  |  |  |
| Execution release checklist | X |  |  |  |  |  |  |
| List of steering project decisions | X |  |  |  |  |  |  |
| Execution order | X |  |  |  |  |  |  |
| Decide on ISDP concept | List of management project decisions |  | X |  |  | X |  |
| ISDP concept checklist |  | X |  |  | X |  |  |
| ISDP concept milestone |  | X |  |  | X |  |  |
| Decide on solution architecture | Solution architecture milestone |  | X |  |  | X |  |
| Solution architecture checklist |  | X |  |  | X |  |  |
| List of management project decisions |  | X |  |  | X |  |  |
| Decide on closure phase release | Closure phase release checklist |  |  |  | X | X |  |
| Closure phase release milestone |  |  |  | X | X |  |  |
| List of steering project decisions |  |  |  | X | X |  |  |
| QA and risk report |  |  |  | X | X |  |  |
| Decide on phase release | Phase release checklist |  | X | X |  |  |  |
| Phase release milestone |  | X | X |  |  |  |  |
| List of steering project decisions |  | X | X |  |  |  |  |
| QA and risk report |  | X | X |  |  |  |  |
| Decide on product concept | List of management project decisions |  | X |  |  | X |  |
| Product concept checklist |  | X |  |  | X |  |  |
| Product concept milestone |  | X |  |  | X |  |  |
| Decide on project discontinuation | Project discontinuation checklist |  | X | X | X |  |  |
| Final project evaluation |  | X | X | X |  |  |  |
| List of steering project decisions |  | X | X | X |  |  |  |
| Lessons learned |  | X | X | X |  |  |  |
| Project closure milestone |  | X | X | X |  |  |  |
| Decide on project closure | Project closure checklist |  |  |  |  |  | X |
| Project closure milestone |  |  |  |  |  | X |  |
| QA and risk report |  |  |  |  |  | X |  |

* * *

| Task | Outcome | Phases |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | D | E | C |
|  | List of steering project decisions |  |  |  |  | X |
| Decide on project initiation release | List of steering project decisions | X |  |  |  |  |
|  | Project initiation order | X |  |  |  |  |
|  | Project initiation release milestone | X |  |  |  |  |
|  | Project initiation release checklist | X |  |  |  |  |
| Decide on release | QA and risk report |  |  |  | X |  |
|  | Release milestone |  |  |  | X |  |
|  | Release checklist |  |  |  | X |  |
|  | List of steering project decisions |  |  |  | X |  |
| Decide on preliminary acceptance | Preliminary acceptance milestone |  | X |  | X |  |
|  | List of management project decisions |  | X |  | X |  |
|  | Preliminary acceptance checklist |  | X |  | X |  |
|  | Acceptance report |  | X |  | X |  |
| Decide on next steps | List of management project decisions | X |  |  |  |  |
|  | Next steps checklist | X |  |  |  |  |
|  | Study | X |  |  |  |  |
|  | Next steps milestone | X |  |  |  |  |
| Decide on contract award | Contract award checklist |  | X |  | X |  |
|  | Contract award milestone |  | X |  | X |  |
|  | List of steering project decisions |  | X |  | X |  |
|  | Publication |  | X |  | X |  |
| Design integration concept | Integration concept |  | X |  | X |  |
| Design ISDP concept | ISDP concept |  | X |  | X |  |
| Implement ISDP concept | ISDP concept |  | X |  | X |  |
|  | ISDP measures realized |  | X |  | X |  |
| Transfer ISDP concept | ISDP concept |  |  | X | X |  |
|  | ISDP concept transferred |  |  | X | X |  |
| Agree on and steer goods/services | Evaluation report |  | X | X | X |  |
|  | Agreement |  | X | X | X |  |
|  | Quote request |  | X | X | X |  |
|  | Offer |  | X | X | X |  |
| Prepare solution requirements | Situation analysis |  | X |  | X |  |
|  | Solution requirements |  | X |  | X |  |

* * *

| Task | Outcome | Phases |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | I | C | I | D | E | C |
| Prepare solution architecture | System concept |  | X |  |  | X |  |
| Solution architecture |  | X |  |  | X |  |  |
| Conduct migration | Migration carried out |  |  |  | X | X |  |
| Design migration concept | Migration concept |  | X |  |  | X |  |
| Realize migration procedure | Migration procedure realized |  |  | X |  | X |  |
| Detailed specifications |  |  | X |  | X |  |  |
| Activate organization | Organization activated |  |  |  | X | X |  |
| Implement organization | Organization description |  |  | X |  | X |  |
| Process description |  |  | X |  | X |  |  |
| Organization implemented |  |  | X |  | X |  |  |
| Establish organizational requirements | Situation analysis |  | X |  |  | X |  |
| Organizational requirements |  | X |  |  | X |  |  |
| Draw up organization concept | Process description |  | X |  |  | X |  |
| Organization concept |  | X |  |  | X |  |  |
| Business model description |  | X |  |  | X |  |  |
| Organization description |  | X |  |  | X |  |  |
| Prepare phase release | Project management plan |  | X | X | X |  |  |
| Project status report |  | X | X | X |  |  |  |
| Phase report |  | X | X | X |  |  |  |
| Deal with problems and benefit from lessons learned | Lessons learned |  | X | X | X | X | X |
| Activate product | Product activated |  |  | X | X |  |  |
| Realize product | Product developed or adapted |  |  | X |  | X |  |
| Detailed specifications |  |  | X |  | X |  |  |
| Product documentation |  |  | X |  | X |  |  |
| User manual |  |  | X |  | X |  |  |
| Design product concept | Product concept |  | X |  |  | X |  |
| Manage and control project | Work order | X | X | X | X | X | X |
| Solution requirements |  |  |  |  | X |  |  |
| Detailed specifications |  |  |  |  | X |  |  |
| Project status report | X | X | X | X | X | X |  |
|  | Project management plan | X | X | X | X | X | X |
| Minutes | X | X | X | X | X | X |  |
| QA and risk report |  | X | X | X |  |  |  |
|  | List of steering project decisions | X | X | X | X | X | X |
| Final project evaluation |  |  |  |  |  | X |  |
|  | Lessons learned |  |  |  |  |  | X |
|  |  | I | C | I | D | E | C |
| Draw up project management plan | Project management plan | X |  |  |  |  |  |
| Carry out prototyping | Prototype documentation | X | X | X |  | X |  |
| Prototype realized | X | X | X |  | X |  |  |
| Perform quality assurance | Project management plan |  | X | X | X | X | X |
| Review report |  | X | X | X | X | X |  |
| Analyze legal basis | Legal basis analysis | X |  |  |  |  |  |
| Prepare release closure | Release report |  |  |  |  | X |  |
| Project management plan |  |  |  |  | X |  |  |
| Project status report |  |  |  |  | X |  |  |
| Manage risks | Project status report |  | X | X | X | X |  |
| Project management plan |  | X | X | X | X |  |  |
| Analyze protection needs | Protection needs analysis | X |  |  |  |  |  |
| Manage and inform stakeholders | Stakeholder list | X | X | X | X | X | X |
| Stakeholder interests | X | X | X | X | X | X |  |
| Project management plan | X | X | X | X | X | X |  |
| Advocate stakeholder interests | Stakeholder interests |  | X | X | X | X |  |
| Prepare study | Stakeholder list | X |  |  |  |  |  |
| Study | X |  |  |  |  |  |  |
| Activate system | System activated |  |  |  | X | X |  |
| Integrate the system into operation | System integrated |  | X |  |  | X |  |
| Operating manual |  | X |  | X |  |  |  |
| Realize system | User manual |  | X |  | X |  |  |
| System concept |  | X |  | X |  |  |  |
| Detailed specifications |  | X |  | X |  |  |  |
| Solution architecture |  | X |  | X |  |  |  |
| System developed or parameterized |  | X |  | X |  |  |  |
| Detailed specifications |  | X |  | X |  |  |  |
| Prepare system integration | Integration and installation instructions |  | X |  | X |  |  |
| Solution architecture |  | X |  | X |  |  |  |
| Interfaces realized |  | X |  | X |  |  |  |
| Test concept |  | X | X | X |  |  |  |
| Conduct test | Test report |  | X | X | X |  |  |
| Test infrastructure |  | X |  | X |  |  |  |
| Realize test infrastructure | Test infrastructure realized |  | X |  | X |  |  |
| Transfer test infrastructure | Test infrastructure |  |  |  |  | X |  |
|  |  | I | C | I | D | E | C |
|  | Minutes |  |  |  |  |  | X |
|  | Test infrastructure transferred |  |  |  |  |  | X |
| Design test concept | Test concept |  | X |  |  | X |  |
| Draw up agreement | Agreement |  | X |  |  | X |  |

Table 18: Assignment of all tasks to project phases, including corresponding outcomes

5.2.2 Customized tasks

Supplementing the standard tasks available, it is also possible to integrate new subject-,
organization-, or project-specific tasks into own modules and then to expand them with outcomes.

This is supported by HERMES online and is especially relevant when new modules are developed. Examples of customized tasks can be extended, core organization-specific reporting or
project-specific risk management.

5.3 Explanation regarding task description

For each task, a task description is provided that is always structured in the same way:
-

- Purpose
describes the intent and purpose of the task.

describes the intent and purpose of the task.

- Basic idea
creates a fundamental understanding of the task.

creates a fundamental understanding of the task.
HERMES-specific

- HERMES-specific

describes how HERMES supports the task in concrete terms.
- Basis/prerequisites

- Basis/prerequisites

describe how the task is executed. If possible, the activities are listed in chronological
order. Where applicable, the outcomes are marked with "A" for agile or "T" for traditional.
- Relationships (online only)

show how the tasks relate to other module elements.
- Outcomes

order. Where applicable, the outcomes are marked with "A" for agile or "T" for traditional.
Relationships (online only)

- Outcomes
show which outcomes are generated by the task. Where applicable, the outcomes are

- Outcomes
show which outcomes are generated by the task. Where applicable, the outcomes are
marked with "A" for agile or "T" for traditional.

* * *

## 5.4 Descriptions of the tasks

### 5.4.1 Decision-making tasks of steering

### 5.4.1.1 Decide on call for tenders

Concept Implementation Deployment Initiation Closure Execution **Purpose** The decision on call for tenders creates the prerequisite for publication. **Basic idea** After the decision on call for tenders, the tender documentation is published or, in the case of an invitation procedure, sent out. **HERMES specific** The decision on call for tenders is made by the project sponsor, where applicable with the involvement of the body in charge of tenders in the core organization. The project sponsor ensures coordination with the core organization. **Basics**

- Tender documentation - Project management plan
  **Activities**

- Add further criteria to the tender checklist. - Check the tender documentation with the tender checklist.

- Check whether overarching strategies, standards, and specifications have been adhered to and whether confirmations from the competent bodies are available.

- Coordinate the decision with the core organization. - Make formal decision on call for tenders.
  **Outcomes**

- Tender checklist - List of steering project decisions - Tender milestone


### 5.4.1.2 Decide on launch of operation

Concept Implementation Deployment Initiation Closure Execution **Purpose** The decision on launch of operation is the prerequisite for the activation of the product or the system (with subsequent activation of operation) and for the productive use of the solution.

88/244

* * *

Basic idea

The project sponsor decides on the launch of operation at the request of the project manager
or the user representative.

HERMES specific

The sponsor's decision on launch of operation is based on the decisions on preliminary acceptance and acceptance of migration, on the execution of deployment measures, and on further,
partly project-specific release criteria according to the deployment concept.

Basics

- Preliminary acceptance milestone
- Migration acceptance milestone

- Migration acceptance milestone
- Deployment concept

- Deployment concept
- Deployment measures carried out

- Deployment measures carried out
- ISDP concept transferred

- ISDP concept transferred

Activities

- Add further release criteria to the launch of operation checklist.
- Evaluate release criteria and assess and present deployment risks.

- Evaluate release criteria and assess and present deployment risks.
- Make formal decision on launch of operation.

- Make formal decision on launch of operation.
-

- Release utilization for users after successful launch of operation.

Outcomes

- Launch of operation checklist
- Launch of operation milestone

- Launch of operation milestone
-

- List of steering project decisions

5.4.1.3 Decide on execution release

HERMES specific

With the execution release, solution development begins and the adapted project organization
is put into effect. The resources required for the next phase are released.

The decision on execution release continues the project with the next phase and starts the
solution development. It creates the prerequisite for the work in the concept phase under a
traditional approach and in the execution phase under an agile approach.

* * *

effect. In the agile approach, the execution organization is formally established in the project organization. The solution development is initiated with the execution release; this starts with the concept phase in the traditional approach and with the execution phase in the agile approach. A decision is made whether

- the initiation phase is concluded or whether further outcomes are to be developed and, provided that the initiation phase can be concluded, whether the project continuation

- is released, - is not currently released and is to be requested again at a later date, or

- is not released and the project is terminated (does not constitute an actual project discon- tinuation, see Decide on project discontinuation).
  **Basics**

- Project management plan - Execution order
  **Activities**

- Add further criteria to execution release checklist. - Project sponsor checks the execution order against the execution release checklist.

- Ensure resources (human, financial, infrastructure) for the entire project duration. - Release resources for the next phase.

- Deliver the execution order to the decision makers. - Project organization is communicated to core organization and stakeholders.

- Coordinate the decision in the core organization. - Make formal decision on execution release.

- If the decision is positive: - Sign execution order; - Release resources for solution development (concept or execution phase);

- Inform stakeholders about the decision.
  **Outcomes**

- Execution release milestone - Execution release checklist - List of steering project decisions

- Execution order


## 5.4.1.4 Decide on closure phase release

Concept Implementation Deployment Initiation Closure Execution **Purpose** The decision on closure phase release concludes the provision of goods or services within the scopeofthesolutiondevelopmentandcreatestheprerequisitefortheworkintheclosurephase.

90/244

* * *

## Basic idea

The outcomes of the entire solution development are checked and accepted or rejected. The phase is completed, and the closure phase as well as the resources required for it are released. **HERMES specific** At the end of the deployment or execution phase, the phase report and, under the agile ap- proach, the final release report are also accepted. The project sponsor decides on the end of solution development and on release of the closure phase. If the solution development is agile, the execution organization is dissolved. A decision is made

- whetherthephaseisconcludedorwhetherthereareadditionaloutcomestobedeveloped prior to conclusion of the phase, or

- whether the closure phase is released.
  **Basics**

- Acceptance milestone - Phase report - Release report

- Project management plan - Project status report
  **Activities**

- Add further release criteria to closure phase release checklist. - Coordinate the decision in the core organization.

- Make formal decision on closure phase release or reject outcomes. - If the decision is positive:

- Release resources for the next project phase. - Inform those affected about the decision.
  **Outcomes**

- Closure phase release checklist - Closure phase release milestone - List of steering project decisions

- QA and risk report


## 5.4.1.5 Decide on phase release

Concept Implementation Deployment Initiation Closure Execution **Purpose** In the traditional approach, the phase release decision creates the prerequisite for the work in the next phase.

91/244

* * *

## Basic idea

The phase outcomes are checked and accepted or rejected. The current phase is completed and the next project phase is released, as are any resources needed. If the defined project objectivescannotbeachieved,theprojectisterminated(seeDecideonprojectdiscontinuation).

## HERMES specific

At the end of the current project phase, the phase report is approved and a decision is made on the conclusion of the phase. The sponsor then decides on the release of the next phase. Before phase release, the phase report and the project management plan are compared with the overarching strategies and objectives of the core organization. New findings are taken into account. Adjustments to the project management plan and project organization are decided and put into effect. If the project has specific controlling and QA/risk management bodies, they prepare a report for the project sponsor.

**Basics**

- Project management plan - Project status report - Phase report
  **Activities**

- Add further release criteria to the phase release checklist.

- Critically review objectives, feasibility, and benefits of the envisaged solution based on new findings and align with the core organization's objectives.

- Check whether overarching strategies, standards, and requirements have been adhered to and whether confirmations from the competent bodies are available.

- Ensure that the necessary resources (human, financial, infrastructure, knowledge and experience)areavailableinatimelyandsufficientmannerfortheremainderoftheproject.

- Coordinate the decision in the core organization. - Reviewandapproveorrejectphasereport, projectmanagementplan, andphase-specific outcomes.

- Make formal decision on phase release or reject outcomes. - If the decision is positive:

- Release resources for the next project phase. - Inform those affected about the decision.

- If the set objectives cannot be achieved: - Either determine corrective measures, or

- Decide on project discontinuation and request termination of the project.
  **Outcomes**

- Phase release checklist - Phase release milestone - List of steering project decisions

- QA and risk report
  92/244


* * *

## 5.4.1.6 Decide on project discontinuation

Concept Implementation Deployment Initiation Closure Execution

**Purpose**

The decision on project discontinuation is made before the set objectives have been achieved. The project organization is dissolved and the project is terminated in an orderly manner.

## Basic idea

Project discontinuation is an unplanned step that can at most be foreseen as a possible action when, for example, a pilot project, a research project, or a project under aggravated critical circumstances is undertaken. The generally unpopular step of a project discontinuation lies entirely within the competence and responsibility of the project sponsor. The termination should be as smooth as possible and without "collateral damage". The dissolution of the project organization is performed anal- ogously to a project closure. The project participants are officially released from their project responsibilities. Document storage is purged and the existing project documentation is transferred to the core organization. Thereasonsforprojectdiscontinuationarecompiledanddocumented. Anyopen, relevant pending items and unresolved points are transferred to the responsible persons in the coreorganization. Anylegalaspectsarisingfromunfulfilledcontractsaretransferredtothelegal department of the core organization.

## HERMES specific

A project discontinuation is possible only within the scope of solution development, i.e. after the decision on execution release and before the decision on closure phase release. It constitutes a premature, unplanned, possibly also abrupt project closure with the project closure milestone. The decision is made by the sponsor. Termination of the project during the initiation phase does not constitute actual project discon- tinuation, because initiation serves as a structured orientation for a focused project, and any decision not to release execution followed by subsequent termination of the project is one of the possible steps anticipated in advance. This also applies to termination of the project in the earlierinitiationphase. Formalterminationoftheprojectisnotprovidedfor; nevertheless, some activities of this task can support the termination if needed. It should be ensured that the value already added can be preserved, thus limiting the damage due to project discontinuation. Since the prepare project closure task cannot be performed in the event of project discontinu- ation, the lessons learned and the final project evaluation including the discontinuation notice must also be prepared before the decision is made. The project manager's final project evaluation is reviewed and approved or rejected by project steering. The sponsor forwards important lessons learned from the project to the relevant bod- ies. The project sponsor ensures that the orderly project discontinuation requirements of the con- trolling and compliance body as well as governance are met. A decision is made

93/244

* * *

- that the project is discontinued.
  If the project has specific controlling and QA/risk management bodies, they prepare a final report. All members of the project team, all affected stakeholders, as well as all internal bodies and external service providers involved in the project are informed.

**Basics**

- Project management plan - Lessons learned
  **Activities**

- Add further criteria to the project discontinuation checklist. - Purge document storage. - Secure value already created, if possible.

- Check work in progress to determine whether it should be discontinued immediately or better continued to the finished outcomes.

- Ensurethattheclosureworkhasbeencompleted; carryoutorcommissioncorresponding tests.

- Return unrequired resources (infrastructure, etc.) to the core organization. - Revoke access rights granted specifically for the project.

- Finalize expense recording systems, project accounts, reporting, etc.

- Transfer pending items arising from the project to those responsible in the core organiza- tion.

- Communicate the decision to the controlling and compliance bodies as well as to the project team.

- Have projects deleted from any portfolio. - Hold final project committee meeting. - Make formal decision on project discontinuation.

- Dissolve project organization. - Inform those affected and interested about the decision.

- Add experience from the project discontinuation to lessons learned and pass them on the relevant bodies.

- Legal aspects such as disputes regarding agreements, rescission, shared liability, fees, claims for damages, etc. must be forwarded to the legal department of the core organi- zation in a separate order, together with the relevant documentation, or the lawyers are involved directly.
  **Outcomes**

- Project discontinuation checklist - Final project evaluation - List of steering project decisions

- Lessons learned - Project closure milestone
  94/244


* * *

## 5.4.1.7 Decide on project closure

Concept Implementation Deployment Initiation Closure Execution

**Purpose** With the decision on project closure, the project organization is dissolved and the project is ended.

## Basic idea

The last step of project closure is the formal dissolution of the project organization. This comes under the authority and responsibility of the project sponsor. The project participants are offi- cially relieved of their project responsibilities.

## HERMES specific

The decision on project closure is the last regular and formal decision in the project. The project sponsor checks that all outcomes are formally documented correctly and made available for further use and for the application organization in an orderly manner. The project sponsor ensures that the project closure requirements of the controlling and compliance body as well as governance are met. The project sponsor reviews and either approves or rejects the project management's final project evaluation. The project sponsor passes on important lessons learned from the project to the relevant parties. The project sponsor also checks to what extent the project organization to be dissolved could be used as an application organization during the service life of the solution system and, if so, whether this is possible or feasible within the framework of the core organization. The project sponsor decides

- whether the project will be closed or whether further documentation of the outcomes will need to be developed prior to project closure; and
- whether or not the dissolved project organization will be partially or fully transferred to the successor organization under a different name.
  If the project has specific controlling and QA/risk management bodies, they prepare a final report.

**Basics**

- Project management plan - Test infrastructure transferred - Legacy system removed

- Lessons learned - Final project evaluation
  **Activities**

- Add further criteria to the project closure checklist. - Ensurethattheclosureworkhasbeencompleted. Carryoutorcommissioncorresponding tests.

- Provide decision-makers with the final project evaluation and further information for decision-making.

- Coordinate decision with the controlling and compliance bodies. - Hold final project committee meeting.

- Approve (or reject) the final project evaluation.
  95/244


* * *

- Make formal decision on project closure. - If the decision is positive: - Dissolve project organization.

- Inform those affected and interested about the decision. - Pass on lessons learned from the project to relevant bodies.
  **Outcomes**

- Project closure checklist - Project closure milestone - QA and risk report

- List of steering project decisions


## 5.4.1.8 Decide on project initiation release

Concept Implementation Deployment Initiation Closure Execution

**Purpose** With the decision on project initiation release, the project is established and it starts with the initiation phase.

## Basic idea

Withtheprojectinitiationrelease,theprojectformallybegins. Aninitialclarificationisundertaken whether the envisaged solution will be pursued. Intheorderplacement, thepointsareclarifiedthatareimportantforsuccessfulprojectinitiation.

## HERMES specific

The decision on project initiation release is the first regular decision in the project, with which the project is formally established. The decision is made solely by the project sponsor on behalf of the core organization, possibly within the framework of an existing portfolio. The decision is madethattheenvisagedprojectshouldbecheckedforprojectsuitabilityandworthinessaspart of the initiation phase. The project sponsor assigns a project manager to draw up the project initiation order, which is still outside the possible future project structure. The project manager does not necessarily have to take over project management for the following phases. As long as the decision on project initiation release has not been made, the project is still non-existent. The project organization for the initiation phase, consisting at least of the project sponsor and the project manager/user representative (in the same person) is put into effect. The resources required for initiation are released.

**Basics**

- Project initiation release checklist - Project initiation order
  96/244

* * *

**Activities**

- Outside the possible future project structure: - Add further criteria to the project initiation release checklist.

- The project sponsor checks the project initiation order with the project initiation re- lease checklist.

- Ensure resources for the initiation phase. - As part of the project:

- Make formal decision on project initiation release. - Sign project initiation order. - Release resources for the initiation phase.

- Inform the core organization and enter projects in any existing portfolio.
  **Outcomes**

- List of steering project decisions - Project initiation order - Project initiation release milestone

- Project initiation release checklist


## 5.4.1.9 Decide on release

Concept Implementation Deployment Initiation Closure Execution **Purpose** In the agile approach, the decision on release creates the prerequisite for the work in the next release. **Basic idea** The outcomes of the release are reviewed and accepted or rejected. The current release is completed and the next one is released. If the set goals cannot be achieved, the project is terminated (see Decide on project discontinuation). **HERMES specific** Whether or not the optional decision on release is mandatory for a given project depends on a note to that effect in the project management plan. At the end of the current release, the release report is accepted and a decision is made on closure of the release. The sponsor then decides on the next release. Prior to release, the release report and project management plan are coordinated with the over- arching strategies and objectives of the core organization or any overarching program. New findings are taken into account. If specific controlling and QA/risk management bodies have been commissioned, they prepare a report for the sponsor. **Basics**

- Project management plan - Project status report - Release report
  97/244

* * *

**Activities**

- Add further release criteria to release checklist.

- Critically review objectives, feasibility, and benefits of the envisaged solution based on new findings and align with the core organization's objectives.

- Check whether overarching strategies, standards, and requirements have been adhered to and whether confirmations from the competent bodies are available.

- Supply decision-makers with the release report, project management plan, and other decision-making documents.

- Ensure that the necessary resources (human, financial, infrastructure, knowledge and experience)areavailableinatimelyandsufficientmannerfortheremainderoftheproject.

- Coordinate the decision in the core organization.

- Review and approve or reject release report, project management plan, and release- specific outcomes.

- Make formal decision on release or reject outcomes. - If the decision is positive:

- Inform those affected about the decision. - If the set objectives cannot be achieved:

- Either determine corrective measures, or - Decide on project discontinuation and request termination of the project.
  **Outcomes**

- QA and risk report - Release milestone - Release checklist

- List of steering project decisions


## 5.4.1.10 Decide on contract award

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The decision on contract award creates the prerequisite for publication of the award and prepa- ration of the contract with the successful tenderer.

## Basic idea

After the decision on contract award, the tenderers are informed about the outcome of the eval- uation. The award is published.

## HERMES specific

The decision on contract award is made by the sponsor. The activities are based on the procurement plan chapter in the project management plan. Any requirements of the core organization must be taken into account.

**Basics**

- Contract award checklist - Publication - Contract award milestone
- List of steering project decisions
  98/244

* * *

**Activities**

- Supplement contract award checklist. - Critically review objectives, feasibility, and benefits of the envisaged solution based on new findings and align with the core organization's objectives.

- Provide decision-makers with the evaluation report. - Coordinate the decision with the core organization and the controlling and compliance bodies responsible for procurement.

- Approve or reject the evaluation report. - If the evaluation report is approved:

- Make formal decision on contract award; - Publish award, e.g. at [www.simap.ch](http://www.simap.ch/); - Send rejection notice to unsuccessful tenderers;

- If necessary, conduct debriefings; - Possiblyfurtheractivitiesaccordingtospecificrequirementsofthecoreorganization. - Outcomes
  **Outcomes**

- Contract award checklist - Contract award milestone - List of steering project decisions

- Publication


## 5.4.2 Decision-making tasks of management

## 5.4.2.1 Decide on acceptance of migration

Concept Implementation Deployment Initiation Closure Execution **Purpose** The decision on acceptance of migration shows that the migration was successful; it is one of the prerequisites for the launch of operation. **Basic idea** If the quality criteria for the migration are met, utilization of the new system is released to the users (decision on launch of operation). **HERMES specific** The decision on acceptance of migration requires the decision on preliminary acceptance and is made before the decision on launch of operation. **Basics**

- Preliminary acceptance milestone - Migration carried out
  99/244

* * *

**Activities**

- Add further criteria to the migration acceptance checklist. - Check the achievement of the quality criteria.

- Accept or reject migration. - If the decision is positive: - Make formal decision on acceptance of migration;

- Formally complete migration and document it in a comprehensible manner; - Release system.
  **Outcomes**

- Acceptance report - Migration acceptance milestone - List of management project decisions

- Migration acceptance checklist


## 5.4.2.2 Decide on acceptance

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The decision on acceptance concludes the provision of goods or services within the scope of the solution development and creates the basis for the decision on closure phase release. The solution, including the required documentation, is definitively transferred to the application organization and, where applicable, to the operating organization.

## Basic idea

Acceptancetakesplacebetweentheprojectsponsorandthedeveloperorsupplierandoperator ofthesolution; inthecaseofaproduct,theoperatorisgenerallytheuser. Acceptanceregulates how outstanding obligations are to be handled and how the provision of goods or services is to be completed.

## HERMES specific

Acceptance takes place after operational activation and after the solution or part of the solution has been operational for an initial period during which utilization can take place-e.g. according to the product concept-and any defects are identified. Acceptance is planned by all those involved in a timely manner. With the acceptance of the solution, the development/parameterization of the system, the de- velopment/adaptation of the service/product, or the implementation of the organization is defini- tivelycompletedandtheprovisionofgoodsorserviceswithinthescopeofsolutiondevelopment is concluded. If necessary, separate acceptance processes (between developer and operator, between de- veloper and user, etc.) are carried out.

100/244

* * *

Basics

- Organization activated
-

- Operation activated
- Product documentation

- Product documentation
-

- User manual

Activities

- Determine the organization and general conditions for acceptance.
- Add further criteria to the acceptance checklist.

- Add further criteria to the acceptance checklist.
- Prepare acceptance in technical and organizational terms.

- Prepare acceptance in technical and organizational terms.
- Perform acceptance process and record findings.

- Perform acceptance process and record findings.
- Make formal decision on acceptance and next steps.

- Make formal decision on acceptance and next steps.
- Analyze and classify findings (e.g. by defect category, new requirements).

- Analyze and classify findings (e.g. by defect category, new requirements).

Outcomes

- Acceptance report
- Acceptance checklist

- Acceptance milestone

- List of management project decisions
- Acceptance milestone

- Acceptance checklist
- List of management project decisions

5.4.2.3 Decide on ISDP concept

Purpose

The decision on ISDP concept confirms compliance with the requirements of the core organization.

HERMES specific

Before the decision is made, the ISDP concept is checked by the responsible controlling and
compliance bodies.
In the case of procurement (i.e. not customized development) of a system, the ISDP concept

In the case of procurement (i.e. not customized development) of a system, the ISDP concept
is reviewed after evaluation. This is because the tender chosen has a significant impact on the
ISDP concept.

- Project management plan

* * *

**Activities**

- Add further criteria to the ISDP concept checklist.

- Have the ISDP concept checked by the competent controlling and compliance body and get feedback.

- Have the project sponsor acknowledge protection measures and residual risks. - Make formal decision on ISDP concept.
  **Outcomes**

- List of management project decisions - ISDP concept checklist - ISDP concept milestone


## 5.4.2.4 Decide on solution architecture

Concept Implementation Deployment Initiation Closure Execution **Purpose** The decision on solution architecture forms the prerequisite for the development or parameter- ization of systems. **Basic idea** The decision on solution architecture confirms conformity with the IT architecture of the core organization. **HERMES specific** Before the decision is made, the solution architecture is checked by the responsible controlling and compliance bodies. In the case of procurement (i.e., adaptation) of a system, the solution architecture is reviewed before and after evaluation. This is because the tender chosen may result in an adaptation of the solution architecture. **Basics**

- Solution architecture
  **Activities**

- Add further criteria to the solution architecture checklist. - Havethesolutionarchitecturecheckedbythecompetentcontrollingandcompliancebody and get feedback.

- Make formal decision on solution architecture.
  **Outcomes**

- Solution architecture milestone - Solution architecture checklist - List of management project decisions
  102/244


* * *

## 5.4.2.5 Decide on product concept

Concept Implementation Deployment Initiation Closure Execution **Purpose** The decision on product concept forms the prerequisite for the development or adaptation of products or services. **Basic idea** The decision on product concept confirms conformity of the envisaged solution with the require- ments and needs of the core organization. **HERMES specific** Before the decision is made, the product concept is checked by the responsible controlling and compliance bodies. In the case of procurement (i.e., adaptation) of a product or service, the product concept is reviewed before and after evaluation. This is because the tender chosen may result in an adap- tation of the product. **Basics**

- Product concept
  **Activities**

- Add further criteria to the product concept checklist. - Havetheproductconceptcheckedbythecompetentcontrollingandcompliancebodyand get feedback.

- Make formal decision on product concept.
  **Outcomes**

- List of management project decisions - Product concept checklist - Product concept milestone


## 5.4.2.6 Decide on preliminary acceptance

Concept Implementation Deployment Initiation Closure Execution **Purpose** Preliminary acceptance creates the basis for the execution of deployment measures as well as the subsequent launch of operation with acceptable risks. **Basic idea** Quality assurance measures such as tests and inspections are carried out in advance for pre- liminary acceptance. Preliminary acceptance gives users, developers, and operators the as- surance that the transfer of the solution to the new state will most likely be successful.

103/244

* * *

## HERMES specific

Preliminary acceptance is planned early by all those involved. The acceptance criteria are checked jointly in accordance with the deployment concept. **Basics**

- Deployment measures realized - Deployment concept - Business model description

- Process description - Organization description - Organization implemented

- ISDP concept - ISDP measures realized - System integrated

- Test report
  **Activities**

- Determine the organization and general conditions for preliminary acceptance. - Check realized deployment measures and emergency organization.

- Add further criteria to the preliminary acceptance checklist. - Prepare preliminary acceptance in technical and organizational terms.

- Perform preliminary acceptance and record findings. - Analyze and classify findings (e.g. by defect category, new requirements).

- Make formal decision on preliminary acceptance.
  **Outcomes**

- Preliminary acceptance milestone - List of management project decisions - Preliminary acceptance checklist

- Acceptance report


## 5.4.2.7 Decide on next steps

Concept Implementation Deployment Initiation Closure Execution **Purpose** The decision on next steps clarifies the choice of solution option, scenario, approach (whether traditional or agile), and project value. It forms the prerequisite for drawing up the project man- agement plan and subsequently the execution order. **Basic idea** The decision on next steps sets the direction for how the solution development is executed, for future operation, and for the long-term benefit that can be achieved. If it becomes apparent that the expected benefit cannot be achieved, work is stopped at that time and the findings are recorded for those interested.

104/244

* * *

## HERMES specific

The decision on next steps is made only if it makes sense to continue the project. If so, care is taken when choosing the next steps to ensure that a sustainable solution option is chosen. Accordingly, the proposed option is reviewed again from that perspective. To this end, the various stakeholders are integrated into the decision-making process. The project manager decides on a solution option after consulting the project sponsor and other stakeholders. The decision is based on the option descriptions and evaluations developed in the study as well as the recommendations of those involved in the study and other stakeholders Secondly, it is decided how the solution is to be developed. Here, a choice is made between a traditional or agile approach to solution development. This choice must be made for each project, since each project has different characteristics. The approach cannot be specified in the program or portfolio, and the choice must accordingly be comprehensible. Thirdly, a suitable scenario is selected (see Section "Scenarios"), and the project value is de- termined as needed. The study is supplemented according to the decisions taken. If, when deciding on next steps, the conclusion is reached that continuing the project makes little sense, the project is concluded.

**Basics**

- Study - Procurement analysis
  **Activities**

- Add further criteria to the next steps checklist. - Check whether sustainability aspects are taken into account.

- Check whether the directions of the study and of the procurement analysis are congruent.

- Obtain recommendations based on the option description and evaluation in the study.

- Examine and decide on the appropriate approach for the preferred solution option.

- Coordinate the decision with the project sponsor and stakeholders. - Make formal decision on next steps.
  **Outcomes**

- List of management project decisions - Next steps checklist - Study

- Next steps milestone


## 5.4.3 Other tasks

## 5.4.3.1 Decommission the legacy system

Concept Implementation Deployment Initiation Closure Execution

105/244

* * *

**Purpose** After the productive deployment of the new or the further developed system, the legacy system or the old system version is decommissioned.

## Basic idea

Thelegacysystemortheoldversionofthefurtherdevelopedsystemisdecommissionedinsuch a way that the data security and data protection requirements are met and the specifications of controlling and compliance bodies are complied with.

## HERMES specific

The decommissioning of the legacy system or the old version of the further developed system is based on the procedure defined in the migration concept. Thedataarchivingrequirementsthatmayhavebeentakenintoaccountinthemigrationconcept and those relating to data security and data protection (according to the solution requirements) are implemented.

**Basics**

- Migration concept - Organizational requirements - Solution requirements

- Acceptance milestone
  **Activities**

- Decommission the legacy system or old system version. - Treat legacy data according to migration concept.

- Dismantle and dispose of the legacy system or remove the old system version (software).

- Remove infrastructure that is no longer needed, reverse structural, technical, or other measures as determined by the core organization, suspend or rescind ISDP measures and provisions.
  **Outcomes**

- Legacy system removed


## 5.4.3.2 Manage changes

Concept Implementation Deployment Initiation Closure Execution

**Purpose** In traditional solution development, change management ensures that newly identified or changed requirements are identified, assessed, and decided upon. It further ensures that changes to all projects, regardless of approach, are documented.

## Basic idea

Change management makes it possible to maintain control over development of the solution in the event of changes to objectives, scope, requirements, framework conditions, etc., and to recognize the impact on subsequent use and operation. The project manager ensures that the change process is followed and documented consistently. In traditional solution development, execution planning and outcomes are adjusted based on 106/244 approved changes.

In agile solution development, normally only the changes are documented in the change status
list. A change request in the traditional sense is absolutely necessary if changes are identified
by the execution organization that affect the project objectives, the budget, or the time frame of
the overall project.

Thereisnoformalchangemanagementintheinitiationphasebecausetheorganizationandsolution requirements and the solution objectives have not yet been defined. If there are changes
in relation to the project initiation order, for example, the project sponsor decides on these
changes.

HERMES specific

The changes are managed within the scope of solution development according to the project
management plan.

Under the traditional approach, approved changes are updated in the solution requirements.

Under the agile approach, documentation of the most significant changes is drawn up based on
the updated solution requirements.

The change status list keeps track of all the changes dealt with and provides an overview of
their status.

Basics

- Solution requirements
- Change request

- Change request

Activities

- Enter and update change requests in traditional solution development and the most significant changes in agile solution development in the change status list. (T/A)
- Analyze and approve/reject change requests. (T)

- Analyze and approve/reject change requests. (T)
- Plan, implement and review approved changes. (T)

- Plan, implement and review approved changes. (T)
- Adjust project management plan based on the changes, as needed. (T/A)

- Adjust project management plan based on the changes, as needed. (T/A)
T=traditional, A=agile

T=traditional, A=agile

- Change status list
-

The available tenders are recorded in the report and evaluated according to the evaluation
criteria.

- Solution requirements
- Project management plan

- Change request
- Solution requirements

* * *

## Basic idea

Afterthedeadlinehasexpired,thetendersareopenedandtenderreportiscreated. Thetenders are then evaluated. The evaluation is based on the list of criteria completed by the tenderer and the information provided in the tender.

## HERMES specific

The activities are based on the procurement plan chapter in the project management plan. The receipt and opening of tenders are recorded in the tender report. If tenderer presentations are made, all procurement law and evaluation-related points are recorded in the tender report and, if necessary, subsequent tenders are obtained. If tenderer presentations are made, all procurement law and evaluation-related points are recorded in the tender report. Theevaluationreportcontainstheconsolidatedresultsoftheevaluationandtheproposalissued by those in charge of the evaluation.

**Basics**

- Offer - Project management plan - Tender documentation

- Procurement analysis
  **Activities**

- Open tenders, check them formally (on time, complete), and create report. - Evaluate tenders in terms of content.

- Carry out procurement planning activities (e.g. organizing and recording tenderer presen- tations, conducting and recording negotiations, etc.).

- Draw up an evaluation report and prepare a proposal.

- Coordinate the evaluation report with the controlling and compliance bodies responsible for procurement.
  **Outcomes**

- Evaluation report - Tender report


## 5.4.3.4 Issue call for tenders

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The tender is conducted according to a specific, transparent procedure.

## Basic idea

With the publication of the call for tenders, an unrestricted group of tenderers is informed and invited to apply. As needed, any further tender documents are made available, questions are answered, and incoming tenders are collected.

108/244

* * *

HERMES specific

The activities are based on the procurement plan chapter in the project management plan.

The call for tenders is published on the simap platform ( [www.simap.ch](http://www.simap.ch/)). Replies to questions
from tenderers are recorded. They are made available to all interested parties in a neutralized
form and are part of the tender procedure.

Basics

- Tender milestone
-

- Project management plan
- Tender documentation

- Tender documentation

Activities
-

- Publish tender documentation or invite interested parties.
- Carry out procurement planning activities (e.g. answer tenderers' questions).

- Carry out procurement planning activities (e.g. answer tenderers' questions).

- Tender documentation
-

- Offer

5.4.3.5 Prepare call for tenders

The preparation of the tender documentation makes it possible to issue a formally correct call
for tenders, to obtain comparable offers, and to perform a comprehensible and comparable
evaluation of the offers.

HERMES specific

The tender documentation is prepared in such detail that the offers can be evaluated in a comprehensible manner. For this purpose, the evaluation criteria questions are set out in the list of
criteria.

The draft contract forms the basis for concluding the contract and is part of the tender documentation.

Specificationsaredrawnupinordertocomparetheoffersreceived. Thespecificationsdescribe
the requirements for the items to be procured (goods, services, etc.) and the procurement
procedure. By drawing up the specifications, the customer becomes aware of what is really
needed, and the tenderer in turn recognizes what the customer wants. The specifications also
force tenderers to comment on issues they may prefer to avoid and to submit the offer in the
required structure. This creates a clear, uniform reference basis.

* * *

law requirements (according to the procurement analysis). The outcomes produced in other modules, such as solution and organizational requirements, concepts, etc., are an integral part of the specifications, where relevant and available.

**Basics**

- Procurement analysis - Project management plan - Protection needs analysis

- Study - Organizational requirements - Solution requirements
  **Activities**

- Produce tender documentation with specifications, list of criteria, draft contract, tender notice, and other documents.

- Coordinate the tender documentation with the controlling and compliance bodies and/or have the latter check them.
  **Outcomes**

- Tender documentation


## 5.4.3.6 Prepare procurement analysis

Concept Implementation Deployment Initiation Closure Execution

**Purpose** Preparationoftheprocurementanalysisisusedtocompileallprocurement-relevantinformation and requirements, prepare the tendering process, and establish the basis for selecting the type of procedure. It is ensured that the procurement is coordinated with the execution planning.

## Basic idea

The procurement analysis ensures timely and comprehensive information on what is to be pro- cured by whom, how the market presents itself, which other parameters must be considered, whether any requirements under procurement law must be fulfilled, and which procurement procedure is to be used. The procurement analysis is coordinated with the controlling and com- pliance bodies for procurement. Tendering, evaluation, and procurement are prepared from a technical and legal perspective, and the rough financial framework is defined. In the procurement analysis, fundamental procedural issues are clarified, such as:

- Is a call for tenders justified, what is the specific need for action?
- What exactly is to be procured, and what requirements are there in terms of quantity and quality?
- What is the current market situation, what is the general offer? - What type of market is it?
- How many tenderers are expected? - Which tenderers and suppliers may be considered?
- Do contracts already exist and for how long will they remain valid?
- What are the requirements for the tenderers?
  110/244

* * *

- Who is responsible for what in the project?
- Who prepares the tender documentation, who evaluates and assesses, who pre- pares the evaluation report, etc.?
- How does the decision-making process work? - What is the estimated cost of what is to be procured?
- When should procurement take place? - What is the planned timeframe/duration of use?
- How is timing coordinated with the project? - What does the specific procurement plan look like?
- Has funding been secured for the entire project, including consequential costs?
- How is the entire procurement process structured in terms of standards and contract forms?
- What tender procedure is to be used? - How will questions about the tender documentation be answered?
- Are vendor presentations envisaged?
  Theprocurementanalysistakesaccountofinternalandstatutoryrequirements, processes, and deadlines.

## HERMES specific

The preparation of the tendering procedure should begin as early as possible, i.e. already in the initiation phase. Under no circumstances should the project be delayed by the clarifications and coordination necessary for a call for tenders. If, in the course of preparing the study, it is recognized that procurement of the solution is envisaged in one or more of the options, a procurement analysis must be prepared. Where a procurement analysis is prepared, it must be coordinated with the study. This applies in particular to the procurement plan. The call for tenders itself takes place only after the execution release.

**Basics**

- Project initiation release milestone - Study
  **Activities**

- Conduct needs and market analysis and gather information on possible solutions (prod- ucts, services, etc.).

- Initiate kick-off meeting. - Define the type of procedure based on the characteristics of the procurement, the core organization's requirements, and the statutory basis.

- Flesh out tasks, activities, and outcomes and take account of the core organization's re- quirements and the statutory basis.

- Create the procurement plan from a scheduling and financial point of view and, to the extent already possible, coordinate it with the planning from the study.

- Formulate requirements for the project organization. - Plan human and financial resources for procurement.

- Coordinate procurement analysis with the controlling and compliance bodies responsible for procurement.
  111/244


* * *

Outcomes

- Procurement analysis

5.4.3.7 Activate operation

Purpose

Activation of the new operating organization releases the system for initial utilization and later
acceptance.

Basic idea

The activated system, tools needed for operation, and operating processes are put into effect
so that the user can use the system productively.

HERMES specific

Operation is activated based on the decision to launch operation. Activation and subsequent
utilizationofthesystembytheusersmaybeaone-offoccurrence;in agile solutiondevelopment,
however, this may also occur several times. In such cases, further parts of the solution always
build on each other and come into play. The operator ensures operation according to the SLA.

Users and operators are actively supported by the project in the initial period up to the acceptance of the system.

Basics

- Organization activated
- System activated

- System activated
- Operating manual

- Operating manual

Activities

- Support the project organization during the initial utilization period.
- Monitor how systems and processes are functioning and check compliance with agree-

- Monitor how systems and processes are functioning and check compliance with agreements.
-

- Analyze problems that arise and take or propose measures.
- If necessary, analyze and implement stabilization measures.

- If necessary, analyze and implement stabilization measures.
- Update the operating manual with the lessons learned.

Outcomes
-

- Update the operating manual with the lessons learned.

* * *

## 5.4.3.8 Realize operation

Concept Implementation Deployment Initiation Closure Execution **Purpose** Based on the operating concept, the operating infrastructure and organization are realized to a degree that enables the system to be integrated. **Basic idea** Based on the operating concept, the operating infrastructure, the operating organization, and the tools required for operation are realized. **HERMES specific** All components and measures defined in the operating concept are implemented and checked with suitable quality assurance measures. The operator tests the operating infrastructure to such an extent that integration can take place. The operator creates an initial version of the operating manual. **Basics**

- Operating concept - Service level agreement
  **Activities**

- Realize operating infrastructure and have tests carried out by the operator. - Create operating manual.

- Realize tools in accordance with the operating concept. - Realize specific security measures. - Realize operating organization.

- Prepare handover from the project organization to the operating organization. - Testing and acceptance by the operator's competent bodies.
  **Outcomes**

- Operating organization realized - Operating manual - Operating infrastructure realized


## 5.4.3.9 Design operating concept

Concept Implementation Deployment Initiation Closure Execution **Purpose** Thefutureoperatinginfrastructureandoperatingorganizationaredescribed,andtheprocedure for their realization is defined.

113/244

* * *

## Basic idea

The operating concept shows how the requirements affecting operation are met at the organi- zational and technical level. **HERMES specific** Based on the solution requirements and the solution architecture, the operating organization with the organizational structure and operating processes, the operating infrastructure, and the tools for operating the system are defined and set out in the operating concept. The operator's specifications are incorporated into the operating concept. The drawing up of the service level agreement is related to the agree on and steer goods/ser- vices task. It concludes the SLA and steers the goods/services. However, the steering of goods/services extends beyond the duration of the project and must be continued by the sub- sequent application organization. **Basics**

- Solution requirements - Organizational requirements - Solution architecture milestone
  **Activities**

- Analyze the operating requirements defined in the solution requirements.

- Determine the need for operating infrastructure (rooms, hardware, software, means of communication, etc.) and tools for operating the system.

- Analyze the security requirements. - Design an operating concept. - Align with the operator's specifications.

- Determine the operating costs. - If operations are outsourced, obtain offers from external operators in advance.

- Draft the SLAs. - Coordinate SLAs with the controlling and compliance bodies or have the latter check and finalize them.

- Coordinate the operating concept with the stakeholders.
  **Outcomes**

- Operating concept - Service level agreement


## 5.4.3.10 Draw up project execution order

Concept Implementation Deployment Initiation Closure Execution **Purpose** Drawing up the execution order creates the prerequisites for deciding on execution release and thus for continuing the project with solution development.

114/244

* * *

Basic idea

Drawing up the execution order is based on the study, comprehensible execution planning in
theprojectmanagementplan, thelegalbasisanalysis, theprotectionneedsanalysis, whereapplicable also the procurement analysis and, depending on the solution-specific characteristics,
the stakeholder list.

HERMES specific

The outcomes developed in the initiation phase form the basis for drawing up the execution order. The relevant information from the study and the other outcomes is further fleshed out and
set out in the execution order. The focus is particularly on the objectives, the execution specifications, the risks, and the planning. Liabilities are drawn up and agreed between the project
sponsor and the project manager. The execution order is coordinated with the requirements of
the core organization.

In addition to the project management plan, the execution order is the prerequisite for steering
and control of the project by the project sponsor.

Basics

- Study
- Project management plan

- Project management plan
- Legal basis analysis

- Legal basis analysis
- Protection needs analysis

- Protection needs analysis
- Procurement analysis

- Procurement analysis
- Stakeholder list

- Stakeholder list
- Next steps milestone

- Next steps milestone

Activities

- Incorporate relevant outcomes from the study, the procurement analysis, and the project
management plan into the execution order.
- Verifytheexecutionorderwiththeprojectsponsor, stakeholders, projectparticipants, and

- Verifytheexecutionorderwiththeprojectsponsor, stakeholders, projectparticipants, and
controlling and compliance bodies.

With the design of the deployment concept, all relevant aspects with regard to subsequent
deployment are compiled and conceptualized to such an extent that they can subsequently
be realized and executed.

Outcomes
-

The deployment concept determines how deployment is to take place:
-

5.4.3.11 Design deployment concept

- Execution order

Decide between deployment on a specific date or phased deployment, and plan accordingly;

* * *

- Deployment organization:
Define deployment support roles;

Define deployment support roles;
Deployment measures:

- Deployment measures:
Develop training, prepare documents.

Develop training, prepare documents.

HERMES specific

The deployment concept is designed based on the solution and organizational requirements as
well as the concepts of various modules.

Designingtheconceptalsoincludestheanalysisandplanningofthemeasuresoforganizational
change management to support the transition to the new state, the development of the training
concept, the rules governing the procedure for acceptance including the acceptance criteria,
and the definition of the release criteria for the decision on launch of operation.

Ifasolutionisprocured,thedeveloperdrawsonexperiencefromsimilarprojectswhendesigning
the deployment concept. In this case, the deployment concept is designed after procurement,
and the acceptance criteria are defined between the organizations involved in the project at the
time the contract is signed.

When replacing an existing system, the content of the deployment concept is related to the
migration concept. They can influence each other.

Basics

- Solution requirements
- Organizational requirements

- Organizational requirements
- Solution architecture

- Solution architecture
- Product concept

- Product concept
- Organization concept

- Organization concept
- ISDP concept

- ISDP concept
- Project management plan

- Project management plan
- Solution architecture milestone

Activities

- Solution architecture milestone

- Design a deployment concept taking account of the deployment risks.
- Integrate deployment planning into the project management plan.

- Integrate deployment planning into the project management plan.
- Identify user and operator training needs and record training measures in the deployment

- Identify user and operator training needs and record training measures in the deployment
concept.
- Coordinate the deployment concept with the stakeholders.

- Coordinate the deployment concept with the stakeholders.
- Plan acceptances and regulate them together with the acceptance criteria.

- Plan acceptances and regulate them together with the acceptance criteria.
- Determine release criteria for the launch of operation.

- Determine release criteria for the launch of operation.

- Project management plan
- Deployment concept

* * *

## 5.4.3.12 Execute deployment measures

Concept Implementation Deployment Initiation Closure Execution **Purpose** Carrying out the realized and prepared deployment measures creates one of the bases for the launch of operation and subsequent use of the system. **Basic idea** The realized deployment measures are carried out. This includes user training, for example. The execution of the deployment measures can extend over the entire duration of the deploy- ment until the closure phase release. **HERMES specific** The realized deployment measures, which have been verified as part of the decision on prelim- inary acceptance, are carried out based on the deployment planning developed in the deploy- ment concept. In agile solution development, this may occur several times. **Basics**

- Deployment measures realized - Deployment concept - Preliminary acceptance milestone
  **Activities**

- Carry out the realized deployment measures. - Check the effectiveness of the deployment measures.
  **Outcomes**

- Deployment measures carried out


## 5.4.3.13 Realize deployment measures

Concept Implementation Deployment Initiation Closure Execution **Purpose** The deployment measures are realized based on the deployment concept. **Basic idea** The deployment measures and the deployment organization are realized.

- The development of training is an example of the realization of a deployment measure; the execution of the training takes place during the execute deployment measures task.
- The training of superusers who support deployment is an example of the realization of the deployment organization; they do not become active until deployment, however.
  117/244

* * *

## HERMES specific

The emergency measures and the emergency organization defined in the deployment concept are realized. In agile solution development, realization may occur several times. The realized deployment measures and emergency organization are checked in the decide on preliminary acceptance task. **Basics**

- Deployment concept
  **Activities**

- Realize deployment measures and deployment organization (including emergency mea- sures and emergency organization).
  **Outcomes**

- Deployment measures realized


## 5.4.3.14 Design integration concept

Concept Implementation Deployment Initiation Closure Execution **Purpose** With the design of the integration concept, all relevant aspects with regard to subsequent inte- gration of the system into the operating infrastructure are compiled and conceptualized to such an extent that the system integration can be prepared. **Basic idea** Integration must be designed so that the system can be integrated into the target environment. **HERMES specific** The integration defined in the system architecture is further specified. The interfaces with pe- ripheral systems and the transfer from one operating environment (e.g. development, test, integration, training) to another are specified. System integration is planned and recorded in the integration concept. If a system is procured, the final integration concept design takes place after the award of the contract. **Basics**

- Solution requirements - Solution architecture
  **Activities**

- Define system integration into the peripheral systems, create specifications for the inter- faces and record them in the integration concept.

- Determine integration into the operating platforms. - Design the transfer of software, data, etc. between operating platforms.

- Create an integration plan and record it in the integration concept.

- Verify the integration concept with prototypes (test installations) if necessary.
  118/244


* * *

- Coordinate the integration concept with stakeholders.

Outcomes

- Integration concept

5.4.3.15 Design ISDP concept

The ISDP concept creates the prerequisites for realizing and transferring the requirements for
information security and data protection.

Basic idea

The ISDP concept completes the information security and data protection requirements. It includes a detailed and in-depth risk analysis. The protection measures are defined.

HERMES specific

The ISDP concept is based, firstly, on the study and protection needs analysis outcomes developed in the initiation phase and, secondly, on the organizational and solution requirements
outcomes. It must be handled in accordance with the requirements of the core organization
concerning information protection.

Basics

- Protection needs analysis
- Study

- Study
- Solution requirements

- Solution requirements
- Organizational requirements

- Organizational requirements

Activities

- Create a system description with the security-related components.
- Create a risk analysis, show how risks are addressed with overarching concepts, and

- Create a risk analysis, show how risks are addressed with overarching concepts, and
identify residual risks.
- Create the emergency concept and processing regulations, and record them in the ISDP

- Coordinate the ISDP concept with the controlling and compliance bodies.

- Create the emergency concept and processing regulations, and record them in the ISDP
concept.
- Coordinate the ISDP concept with the controlling and compliance bodies.

* * *

Purpose

The protection measures defined in the ISDP concept are implemented. The implemented
protection measures are a prerequisite for preliminary acceptance.

Basic idea

TheimplementationoftheISDPconceptcreatestheprerequisitesforthetestingoftheITsystem
and for its operation.

HERMES specific

The protection measures defined in the ISDP concept are implemented in the corresponding
modules, for example in the organization module and the IT system module. In agile solution
development, implementation may occur several times.

In the deployment organization module, the outcomes of the implemented technical protection
measures are checked before preliminary acceptance with the decide on preliminary acceptance task.

Basics

- ISDP concept
- ISDP concept milestone

Activities

- ISDP concept milestone

- Accompany the implementation of the protection measures.
- Document the implementation status in the ISDP concept.

- Document the implementation status in the ISDP concept.
- Update the residual risk assessment in the ISDP concept.

- Update the residual risk assessment in the ISDP concept.
-

- Get approval for the ISDP concept with the residual risks from the project sponsor.

Outcomes

- ISDP concept
- ISDP measures realized

5.4.3.17 Transfer ISDP concept

- ISDP measures realized

The ISDP concept is updated, checked, and transferred from the project organization to the
core organization. This is one of the prerequisites for the decision on launch of operation.

Withthesubsequentdecisiononlaunchofoperation,theprojectsponsorthusassumesresponsibility for the risks of operation.

120/244

* * *

**Basics**

- ISDP measures realized - ISDP concept
  **Activities**

- Update the implementation status in the ISDP concept. - Update the residual risk assessment in the ISDP concept.

- Have the ISDP concept checked by the competent controlling and compliance body and get feedback.

- Get approval for the ISDP concept with the residual risks from the project sponsor and the core organization's executive board.
  **Outcomes**

- ISDP concept - ISDP concept transferred


## 5.4.3.18 Agree on and steer goods/services

Concept Implementation Deployment Initiation Closure Execution

**Purpose**

Theservicelevelagreementcreatesaclearlyregulatedrelationshipbetweentheprojectandthe (internal or external) service providers on the one hand, and between the project organization and the core organization on the other. Deviations during the provision of goods/services are identified and dealt with. Boundaries:

- If it is determined during the initiation phase that the entire project merely constitutes pro- curement and that no other project activities are involved, procurement is transferred di- rectly to the purchasing unit of the core organization and the project is terminated. HER- MES does not support procurement alone.
- Comprehensive procurement by means of open or selective procedures and public publi- cation (e.g. a public call for tenders) is carried out through the procurement module in the case of product or system adaptation, otherwise outside the project organization directly by the purchasing unit of the core organization.
- An agreement on the acquisition of operation- and maintenance-specific services during the utilization phase of the system between the user and the future operator of the system
- the service level agreement (SLA) - is drawn up in the IT operation module.

## Basic idea

The project acquires various goods/services internal and external to the organization which must be agreed on and steered. Goods/services acquired by the project include, for example, employee services (human resources), premises, IT resources, training, etc. The need for goods/services is identified and analyzed and, if necessary, a market survey is carried out. Questions such as the following are clarified:

- Is a call for tenders justified, what is the specific need for action? - Whatresourcesaretobeprocured,inwhatnumbersand,inthecaseofhumanresources,
  e.g. with what specialist focus?
- What is the current market situation, what is the general offer?
  121/244

* * *

- What type of market is it? - How many tenderers are expected?
- Which tenderers and suppliers may be considered?
- Do contracts already exist and for how long will they remain valid?
- What are the requirements for the tenderers?
- When should the procurement take place and for what duration of use? - Has funding been secured (project budget)?
  Based on this, quotes are obtained and agreements concluded. If,however,theneedsandmarketanalysisshowsthatacomprehensiveprocurementbymeans of open or selective procedures and public publication is necessary, resource procurement is carried out using the procurement module. The goods/services are periodically checked for compliance with the planning and agreements.

## HERMES specific

This task deals with the following four cases:

1. Procurement of internal goods/services without cost allocation
2. Procurement of internal goods/services with cost allocation
3. Procurement of external goods/services: negotiated procedure (with one or several of- fers).
4. Procurement of external goods/services: invitation procedure (with several offers and evaluation report).
   The first four cases are dealt with as follows:

- Case 1 and case 2 The procurement of internal goods/services of the core organization (i.e. without jurisdic- tion in the event of a dispute) is regulated with project agreements and project SLAs for operation during the project phases.
  The project agreement regulates the goods/services for project execution. The project SLA regulates the operation of the system (e.g. the test system) for operation during the project phases.

- Case 3 The procurement of external goods/services with a negotiated procedure is regulated by means of quote requests, contracts, and SLAs specific to the service provider.

- Case 4 The procurement of external goods/services with an invitation procedure is regulated by means of quote requests, contracts, and SLAs specific to the service provider. With the invitation procedure, an evaluation report is prepared for evaluating the offers.
  Project agreements, project SLAs, SLAs specific to the service provider, and contracts are drawn up according to the requirements of the core organization. HERMES refers to these outcomes as an agreement. During and upon completion of the provision of goods/services, a performance assessment is carriedoutanddiscussedwiththeprojectpartners. Itformsthebasisforanysteeringmeasures. Deviations from the agreed goods/services or from the required needs are analyzed and dealt with in the manage changes task. Changes are initiated in good time to ensure compliance with the requirements (e.g. the legal basis). Significant problems are solved via the deal with problems and benefit from lessons learned task.


122/244

* * *

**Basics**

- Project initiation order - Project management plan - Execution order
  **Activities**

- Establish the required role profiles (skills requirements) and the capacity requirement for humanresourcesbasedontheplannedtasksandoutcomes, andrecordthemasaneeds requirement.

- Determine the need for infrastructure (rooms, hardware, software, means of communica- tion, etc.).

- Draft internal project agreements and SLAs. - Create quote requests for external goods/services, obtain and evaluate quotes. In the case of an invitation procedure, produce an evaluation report.

- Coordinate agreements with the controlling and compliance bodies and/or have the latter check them before concluding the agreements.

- Assess goods/services during and upon completion of the provision of goods/services.
  **Outcomes**

- Evaluation report - Agreement - Quote request

- Offer


## 5.4.3.19 Prepare solution requirements

Concept Implementation Deployment Initiation Closure Execution

**Purpose** All relevant requirements for the solution and its deployment, operation, utilization, etc., are prepared. In traditional solution development, the requirements form the basis for the development of the solution architecture or product concept. In agile solution development, the fleshed out and prioritized requirements are the cornerstone for their successive continuation and completion.

## Basic idea

The following outcomes are produced:

- The situation analysis is more in-depth than the status report from the study and shows the need for action.
- The solution requirements build on the objectives from the study and from the execution order, flesh out the rough requirements from the study, and expand on them based on the need for action identified in the situation analysis.
  The formulated solution requirements are neutral with regard to the solution.

123/244

* * *

## HERMES specific

The solution requirements are designed and prioritized in sufficient detail in terms of content and planning to form a reliable basis for the development or procurement of the system. If the system is procured, the solution requirements are incorporated into the specifications. In traditional solution development, the accepted solution requirements are updated, where needed, only by way of change management. In agile solution development, the level of detail of the initially defined solution requirements varies depending on the criticality of a system element. The solution requirements are then continuously updated as part of the manage and control project task.

**Basics**

- Study - Legal basis analysis - Procurement analysis

- Protection needs analysis - Execution order - Stakeholder list
  **Activities**

- Critically question the framework conditions from the execution order and analyze the influences on the project's success.

- Comprehensively supplement the status report from the study and go into more depth.

- Flesh out requirements, document them as solution requirements, and prioritize them clearly.

- Coordinate the solution requirements with the stakeholders.
  **Outcomes**

- Solution requirements - Situation analysis


## 5.4.3.20 Prepare solution architecture

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The solution architecture creates the basis for the implementation of the system.

## Basic idea

The following outcomes are produced:

- The system concept creates the basis for and supplements the solution architecture. It describes solution con- cepts for specific issues (e.g. user administration and access rights, archiving).
- The solution architecture describes the system with its components and its structure, as well as the interfaces with peripheral systems. The solution architecture also describes the relationship between the IT architecture and the business processes.
  In the system concept, several solution approaches are established and evaluated. The se- lected approaches are combined in the solution architecture to form a comprehensive solution. 124/244

* * *

HERMES specific

The system concept is based directly on the solution requirements, on any organizational requirements, and on the study. It goes into more depth about the solution option described and
selected in the study. Several subject-specific system concepts can be developed, each with
different solution approaches.

The solution architecture is based on the system concept and forms the basis for the decision
on solution architecture. It is fleshed out further in the course of solution development.

Basics

- Study
- Solution requirements

- Solution requirements
-

- Organizational requirements
- Prototype realized

- Prototype realized

Activities

- Integratesolutionconceptsintothesolutionarchitectureorreferencethemasappendices.
- Check the solution architecture with prototypes as needed.

- Prepare solution architecture.
-

- Check the solution architecture with prototypes as needed.
- Coordinate the outcomes with the stakeholders.

- Coordinate the outcomes with the stakeholders.

Outcomes

- System concept
- Solution architecture

- Solution architecture

5.4.3.21 Conduct migration

Themigrationiscarriedoutusingtheselectedmigrationprocedures. Aftermigration,thequality
of the migration is checked. Any necessary adjustments are made.

- Detailed specifications
- Migration procedure realized

- Migration procedure realized

* * *

**Activities**

- Conduct migration with the migration procedures according to the migration concept. - Implement quality assurance measures.

- Make necessary adjustments.
  **Outcomes**

- Migration carried out


## 5.4.3.22 Design migration concept

Concept Implementation Deployment Initiation Closure Execution **Purpose** The migration concept creates the basis for the transfer of the old system to the new system and the decommissioning of the legacy system. **Basic idea** The focus of the system migration is on the migration of application data, i.e. data migration. Migrations can be technical (automatic) or organizational (manual). The migration concept takes into account the quantities, frequencies, and quality of the data in the legacy system and its integration into the target system. Possible migration scenarios are analyzed and evaluated so that the appropriate migration procedures can be determined. Migration considerations include aspects of the feasibility, economic efficiency, quality, and tim- ing of a migration. Withdatamigration,theissuesoflegacydataarchivingandsystemdecommissioningmustalso be addressed. Data security and data protection aspects are taken into account. **HERMES specific** The deployment strategy in the deployment concept determines the migration strategy (e.g. step-by-step deployment requires step-by-step migration). **Basics**

- Solution requirements - Deployment concept - ISDP concept
  **Activities**

- Analyze the system and data. - Design a migration concept based on the deployment concept.

- Check the impact on the deployment concept.

- Design the decommissioning of the legacy system and clarify data archiving if necessary. - Review feasibility.

- Coordinate the migration concept with the stakeholders.
  126/244


* * *

**Outcomes**

- Migration concept

## 5.4.3.23 Realize migration procedure

Concept Implementation Deployment Initiation Closure Execution **Purpose** The migration procedures are realized to such an extent that migration to the productive system can be carried out. **Basic idea** Different realization steps are carried out depending on the process. **HERMES specific** The detailed specifications are developed on the basis of the migration concept. Migration quality has a major influence on the operational launch of the new system. Accordingly, quality assurance measures are of key importance. The migration procedures are tested according to the test concept. This is done with the tests module. **Basics**

- Migration concept
  **Activities**

- Create detailed specifications for migration and decommissioning of the legacy system. - Realize test infrastructure.

- Consider specifications regarding archiving, data security, and data protection. - Realize migration procedure.

- Document migration procedure (e.g. with checklist). - Review the migration procedure with the tests module.
  **Outcomes**

- Migration procedure realized - Detailed specifications


## 5.4.3.24 Activate organization

Concept Implementation Deployment Initiation Closure Execution **Purpose** With the activation, the new organization is put into effect. Employees work in their new roles according to the new business model and the new processes.

127/244

* * *

Basic idea

The business analyst activates the new organization so that users can work in their new roles
according to the new business model and the new processes.

HERMES specific

After the decision on launch of operation, the business analyst activates the new organization.
The new organization comes into effect, and work is performed in accordance with the new
organization.

The project organization accompanies and supports the organization during the initial utilization
period.

The decision on acceptance is made once utilization is smooth and in accordance with the new
business model, the new process description, and the new organization description.

Basics

- Launch of operation milestone

Activities

- Inform stakeholders at an early stage.
- Activate organization.

- Activate organization.
-

- Support the project organization during the initial utilization period.
- Analyze problems that arise and take or propose measures.

- Analyze problems that arise and take or propose measures.
- If necessary, analyze and implement stabilization measures.

- If necessary, analyze and implement stabilization measures.

Outcomes

- Organization activated

5.4.3.25 Implement organization

The organization is fully realized. The organizational and personnel/position-specific prerequisites are created to such an extent that the new organization can be activated.

The business model description includes the business perspective and defines the framework
fortheprocessandorganizationdescription. Theprocessdescriptionformulatestheprocesses
with the tools used. The organization description defines the organizational structure with a
detailed organization chart, function descriptions, and personnel requirements. Based on the
businessmodeldescription, theprocessdescription, andtheorganizationdescription, themeasures are realized in order to establish the organization (communication channels, distribution channels, role assignments, recruitment, etc.). In the deployment organization module, the outcomes of the realized organization are checked before preliminary acceptance with the decision on preliminary acceptance task.

**Basics**

- Organization concept - Business model description - Process description

- Organization description
  **Activities**

- Realize/complete business model description. - Realize/complete process description. - Realize/complete organization description.

- Define measures to establish and implement the organization.

- Incorporate any newly arising requirements for the solution (product, system) or its oper- ation via change management.
  **Outcomes**

- Organization description - Process description - Organization implemented


## 5.4.3.26 Establish organizational requirements

Concept Implementation Deployment Initiation Closure Execution

**Purpose** All relevant requirements for the solution are developed.

## Basic idea

The following outcomes are produced:

- The situation analysis is more in-depth than the status report from the study and shows the need for action.
- The organizational requirements build on the objectives from the study and from the exe- cution order, flesh out the rough requirements from the study from an organizational and business perspective, and expand on them based on the need for action identified in the situation analysis.
  The formulated organizational requirements are neutral with regard to the solution.

## HERMES specific

The organizational requirements are designed and prioritized in sufficient detail in terms of con- tent and planning to form a reliable basis for the necessary adjustments to the existing organi- zation and, if necessary, for the development or procurement of the solution. If the solution is procured, the organizational requirements are incorporated into the specifications. The organizational requirements are the basis for the development of the organization concept and-where relevant-also for all other concepts in the project.

129/244

* * *

**Basics**

- Study - Legal basis analysis - Protection needs analysis

- Stakeholder list - Procurement analysis
  **Activities**

- Critically question the framework conditions from the execution order and analyze the influences on the project's success.

- Comprehensivelysupplementthestatusreportfromthestudyfromabusinessperspective and go into more depth.

- Flesh out requirements, document them as organizational requirements, and prioritize them clearly.

- Coordinate the organizational requirements with the stakeholders.
  **Outcomes**

- Situation analysis - Organizational requirements


## 5.4.3.27 Draw up organization concept

Concept Implementation Deployment Initiation Closure Execution

**Purpose**

In the organization concept, the new organization is described and the procedure for its realiza- tion is defined.

## Basic idea

The organization concept describes the business model and the organizational and process structure (processes) for business processing. It shows how the new organization is designed and which changes are made to what already exists. The process description comprises the core processes, management processes, and support processes. As needed, different organi- zation options can be described and evaluated.

## HERMES specific

The organization concept is based directly on the organizational requirements, on any solu- tion requirements (pure organization projects do not have solution requirements), and on the study. All organizational aspects are conceptually developed from a business perspective, first in the business model description and then in the organizational and process structure. The business model description defines the framework for the organizational and process structure. The organizational structure provides information about the new or adapted structures in the core organization; the process structure is where the process model is developed and the cor- responding processes are identified and documented. Basedontheorganizationconceptandtheroughpartialoutcomes,thedetailedbusinessmodel description, processdescription, andorganizationdescriptioncanthenbeundertaken, depend- ing on the type of project and the available possibilities, in particular in connection with any parallel activities of the product and IT system modules.

130/244

* * *

Basics

- Study
-

- Organizational requirements
- Solution requirements

- Solution requirements

Activities

- Draw up organization concept with
- Rough business model,

- Rough business model,
- Rough organizational structure,

- Rough organizational structure,
- Rough process structure with process landscape and rough process description.

- Rough process structure with process landscape and rough process description.
Analyze impact on the organization and check for feasibility.

- Analyze impact on the organization and check for feasibility.
- Coordinate organization concept with the stakeholders.

- Coordinate organization concept with the stakeholders.

Outcomes

- Process description
- Organization concept

- Organization concept
- Business model description

- Organization description

- Business model description
- Organization description

5.4.3.28 Prepare phase release

Purpose

Toenablethephasereleasetobegiven,theoutcomesaresummarizedforthedecision-makers
and the next phase is planned.

Basic idea

At the end of a project phase, a decision is made on how the project is to proceed. For this
purpose, the information required for decision-making is prepared for the decision-makers. The
phase report in particular must show that all the necessary outcomes are available in the required quality.

- Project management plan
- Project status report

- Project status report
- Change status list

- Change status list
- Lessons learned

Planning accuracy increases continuously over the course of the project thanks to in-depth
knowledge of the project and the expected outcomes.

The phase report with the requests is compiled. It forms the basis for the project sponsor's
decision on release of the next phase.

- Release report

- Lessons learned
- Release report

* * *

Activities

- Plan the next phase in detail.
-

- Verify the overall plan.
- Summarize outcomes of the course of the project, including changes, in the phase report

- Summarize outcomes of the course of the project, including changes, in the phase report
and evaluate them in terms of quality.
- Update the project management plan and coordinate it with everyone involved as well as

- Update the project management plan and coordinate it with everyone involved as well as
with the controlling and compliance bodies.
-

- Update the project status report as an appendix to the phase report.
- Createfurtherprerequisitesforphaserelease(e.g. ensuringadaptedprojectorganization

- Createfurtherprerequisitesforphaserelease(e.g. ensuringadaptedprojectorganization
and availability of resources).
- Submit requests for the acceptance of outcomes, next steps, the funds and resources to

- Submit requests for the acceptance of outcomes, next steps, the funds and resources to
be released, etc.
-

- Initiate project steering decisions.

Outcomes

- Project management plan
- Project status report

- Project status report
- Phase report

- Phase report

5.4.3.29 Deal with problems and benefit from lessons learned

Purpose

Level-appropriate processing of problems helps to achieve the set objectives. Learning from
experience supports continual improvement within the project and the core organization.

Identifying and solving problems at an early stage is an important prerequisite for achieving
milestones and objectives. If the person working on the problem cannot solve it or cannot solve
it in time, the problem is escalated immediately within the project organization.

HERMES specific

The lessons learned from solving problems are useful as a pool of experience as the project
progresses and also for other projects. The pool of experience and its use is part of a continual
improvement process in the project and in the core organization. This does not take place only
at the end of the project.

* * *

Basics

- Project management plan
- Lessons learned

- Lessons learned

Activities

- Identify and evaluate problems.
- Define measures and monitor course of project.

- Define measures and monitor course of project.
- Initiate and manage escalations and implement de-escalation measures.

- Initiate and manage escalations and implement de-escalation measures.
- Inform those involved about the solution.

- Inform those involved about the solution.
- Regularly analyze the lessons learned from the course of the project and problem situa-

- Regularly analyze the lessons learned from the course of the project and problem situations, and identify improvement measures for further project execution.
- Continually document the lessons learned in the lessons learned outcome and pass them

- Continually document the lessons learned in the lessons learned outcome and pass them
on to the project sponsor (for the attention of the core organization).

Outcomes

5.4.3.30 Activate product

- Lessons learned

The developer activates the product so that the user can use it productively. It includes all
components necessary for operation.

HERMES specific

After the decision on launch of operation, the product is activated by the developer and then
used by users.

- Inform stakeholders at an early stage.
- Activate product.

- Support the project organization during the initial utilization period.
- Analyze problems that arise and take or propose measures.

Basics
-

Users and, where applicable, operators are actively supported by the project during the initial
utilization period until acceptance of the product.

- Launch of operation milestone
- Product developed or adapted

- Product developed or adapted

- If necessary, analyze and implement stabilization measures.

* * *

**Outcomes**

- Product activated

## 5.4.3.31 Realize product

Concept Implementation Deployment Initiation Closure Execution **Purpose** The product is developed or adapted so that it meets the solution requirements and is ready for preliminary acceptance. **Basic idea** Thedetailedspecificationsarepreparedonthebasisofthesolutionrequirementsandtheprod- uct concept. The product is realized:

- All elements relevant for the utilization are realized or made available.

- If a product is procured, the procured product is adapted and product enhancements are developed.

- If customized development is envisaged for the product, the product is developed.

- The product documentation and the user manual are produced.
  Before the launch of operation, the product and the documentation are quality checked. **HERMES specific** HERMES does not describe how the product is realized. This is highly dependent on the prod- uct. Following the development or adaptation of the product, the product documentation and user manual are produced. Theperformqualityassurancetaskintheprojectmanagementand/ortestsmodulecanbeused to perform quality assurance measures. **Basics**

- Solution requirements - Organizational requirements - Product concept

- Product concept milestone
  **Activities**

- Develop detailed specifications. - Develop or customize product. - Produce product documentation.

- Produce user manual. - Prepare and implement quality assurance measures.
  **Outcomes**

- Product developed or adapted - Detailed specifications - Product documentation

- User manual
  134/244


* * *

## 5.4.3.32 Design product concept

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The design of the product concept forms the basis for realization of the product.

## Basic idea

Intheproductconcept,theproductisdescribedwithitscomponentsandstructure,possiblyalso with its relation to business processes. As needed, different product options can be described and evaluated.

## HERMES specific

The product concept is based directly on the solution requirements, any organizational require- ments, and the study. In the product concept, the requirements and the description of the solution option selected in the study are fleshed out in the form of a specification. The product concept is designed in such detail in terms of content and planning that it forms a reliable basis for the realization (development or adaptation) of the product. The product concept forms the basis for acceptance of the product over the further course of the project.

**Basics**

- Study - Solution requirements - Organizational requirements

- Prototype realized
  **Activities**

- Fine-tune requirements based on the option chosen.

- Flesh out the description of the selected option in the product concept.

- Verify the product concept with prototypes if necessary. - Coordinate the product concept with the stakeholders.
  **Outcomes**

- Product concept


## 5.4.3.33 Manage and control project

Concept Implementation Deployment Initiation Closure Execution

**Purpose** Throughout the project, the project participants are coordinated and managed. The project status is continuously monitored, planning is updated, and information to that effect is commu- nicated to project steering.

135/244

* * *

## Basic idea

Management and control of the project are based on the planning. The planning describes how the set objectives will be achieved (target). The project manager fleshes out the tasks and outcomes defined in the planning with work or- ders. This makes the work processes transparent and reduces the risk of misunderstandings. Under the traditional approach, the project manager handles and coordinates solution-specific concernswiththeuserrepresentative;underthe agile approach,thisdoesnotapply. Theproject manager provides for a functioning project organization appropriate to the circumstances, man- ages and supports the project participants, and coordinates the dependencies between the works. The project's progress is periodically checked on the basis of the planning and the degree of outcome completion. The current project status (actual) is surveyed and compared with the planning(target/actualcomparison). Theeffort,costs,anddeadlinesforthefurthercourseofthe project are estimated and portrayed as a forecast. In the event of actual or predicted deviations from the planning, the project manager takes measures, supported by the user representative, to ensure that the set objectives are achieved. The impact of the measures is continuously assessed. Information on the project status and forecasts is collected and compiled by the project man- agement and communicated to project steering by means of reporting.

## HERMES specific

The project initiation order forms the basis for management and control of the project during the initiation phase. In the subsequent phases, the information on project management and control and on the rules governing reporting is recorded in the project management plan. Reporting consists of reports andprojectmeetings. Reportsincludetheprojectstatusreportaswellasthephaseandrelease reports created in other tasks. Further reports may be needed depending on the requirements of the core organization. The work orders are assigned in advance to the responsible project team members based on the roles. The solution requirements, the detailed specifications, and the release plan (in the project man- agement plan) are continuously updated during agile solution development. If significant project changes are required, they are handled in the manage changes task.

**Basics**

- Project initiation order - Project management plan - Execution order

- Lessons learned - Solution requirements - Detailed specifications
  **Activities**

- Have changes identified during the initiation phase relating to the project initiation order approved by the project sponsor.

- After execution release, continuously update the project management plan.

- Hold kick-off meeting with everyone involved and create a project culture. - Provide infrastructure.
  136/244


* * *

- Plan and commission the tasks, outcomes, and resources.
-

- Determine framework conditions and specifications for reporting; define reporting with reports and project meetings in the project management plan and agree on them with the
project sponsor.
- Draw up project status reports according to the requirements and prepare, conduct, and

- Draw up project status reports according to the requirements and prepare, conduct, and
post-process meetings, and take minutes; record decisions.
- Continually coordinate project progress and important findings with the project sponsor.

- Continually coordinate project progress and important findings with the project sponsor.
- Manage project staff and ensure goal orientation and common understanding of proce-

- Manage project staff and ensure goal orientation and common understanding of procedures and outcomes.
- Issue work orders and coordinate with the user representative where necessary; coordi-

- Issue work orders and coordinate with the user representative where necessary; coordinate the interdependencies between orders.
- Check progress (incl. QA measures and risks) by comparing actual values with planned

- Check progress (incl. QA measures and risks) by comparing actual values with planned
valuesandmakingforecasts; analyzedeviationsfromwhatwasplannedandinitiatemeasures.
-

- In agile solution development, update solution requirements, detailed specifications, and
release plan (in the project management plan).

Outcomes

- Work order
-

- Solution requirements
- Detailed specifications

- Detailed specifications
- Project status report

- Project status report
- Project management plan

- Project management plan
- Minutes

- Minutes

Basic idea

In the interest of efficient project execution, the project sponsor ensures rapid decision-making.
The project sponsor plans and steers the decision-making processes in cooperation with the
projectmanagerand,ifnecessary,withotherparties. Theprojectsponsorincludesthedecisionmakers in the project.

* * *

The project sponsor regulates and monitors reporting, which ensures formal standardized infor- mation between project management, project steering, and other bodies. Problems that cannot be solved by the project management are escalated to project steering. Project steering treats these problems with the necessary priority and urgency. **HERMES specific** The project sponsor defines the reporting requirements and checks progress based on the project management plan and the project status report of the project manager. The project sponsor decides on significant measures and related adjustments to the project management plan, change requests, and risk-minimizing measures. **Basics**

- Project initiation order - Project management plan - Execution order

- Phase report - Release report - Project status report
  **Activities**

- Check progress. - Request project management plan and project status report. - Carryouttarget/actualcomparisons, assessforecasts, analyzedeviations, andiden- tify the need for action.

- Take measures. - Risk management

- Add further risks identified to the project and business risks in the project status re- port.

- Analyze risks. - Decide on measures. - Check the implementation of measures and their impact.

- Arrangeforindependentcontrolling,QA/riskmanagementand/orprojectreviewsand project audits to be carried out.

- Decisions - Plan and steer decision-making processes. - Make, communicate, and enforce project decisions.

- Integrate stakeholders. - Make change request decisions. - Handle escalation.
  **Outcomes**

- QA and risk report - List of steering project decisions
  138/244


* * *

## 5.4.3.35 Prepare project closure

Concept Implementation Deployment Initiation Closure Execution

**Purpose** As part of the preparation for project closure, all final activities and measures are carried out and documented from a formal, organizational, and administrative perspective, open and future pending issues are recorded, and all necessary documents and outcomes are forwarded to the competent bodies so that the decision to dissolve the project organization and terminate the project can be made.

## Basic idea

Document storage is purged and the project documentation is transferred to the core organiza- tion. Project execution and the outcomes are evaluated. All pending items arising from the project are transferred to those responsible in the core orga- nization.

Note:

- To review the success of the project, it is necessary (e.g. for the user organization) to check sometime after project closure whether the expected impact has been achieved in the project sponsor's view. This includes an in-depth review of the achievement of objectives or a post calculation, for example.

## HERMES specific

Thedocumentationofthelessonslearnediscompleted. Thefinalprojectevaluationiscompiled.

**Basics**

- Project management plan - Lessons learned - Closure phase release milestone
  **Activities**

- Purge document storage. - Transfer the system documentation relevant for operation, maintenance, and further de- velopment to the core organization and archive the project execution documentation (project plans, minutes, contracts, phase reports, etc.) in accordance with the storage regulations of the core organization.

- Return unrequired resources (infrastructure, etc.) to the core organization. - Revoke access rights granted specifically for the project.

- Finalize expense recording systems, project accounts, reporting, etc. - Compile final project evaluation. - Finalize the lessons learned.

- As a pending item, determine what is to be investigated in the context of project success monitoring, what measures are to be envisaged for this purpose, and who is to carry them out.

- Transfer all pending items from the project, including necessary measures, to the core organization (e.g. for the attention of the application organization).
  139/244


* * *

**Outcomes**

- Final project evaluation - Lessons learned

## 5.4.3.36 Draw up project management plan

Concept Implementation Deployment Initiation Closure Execution

**Purpose**

The drawing up of the project management plan determines the overall planning of the project and the essential provisions and regulations on the basis of the planning and deadlines from the study, and it creates the prerequisites for drawing up the execution order.

## Basic idea

Thedrawingupoftheprojectmanagementplandeterminestheinitialoverallplanningofsolution development and the essential regulations for the further course of the project, even before execution release. Theplanningandprocessingofthevariousprojectsmustbeguidedbytheorganization-specific requirements of the core organization.

## HERMES specific

The stakeholder list, the procurement analysis (where applicable), and the study with the de- cision on next steps form the basis for drawing up the project management plan. The project management plan is the prerequisite for project steering and control by the project sponsor and the coordination of the project with the requirements of the core organization. The project management plan forms the basis for the management and control of the project by the project management. It is guided by the decision on next steps and determines how risk managementorchangemanagementwillbeexecuted, howqualityassuranceofoutcomesand processes/tasks will be ensured, and so on. If an agile approach is planned, the project management plan determines whether optional releases are mandatory in the project or not. This decision is made by the project sponsor. Before execution release, a master plan is created according to the principle of rolling planning, and the subsequent phase-concept or execution-is planned in detail. At the end of each phase or release, the next phase/release is planned in detail and the master plan is reviewed. This is done with the prepare phase release or prepare release closure task. If the project is embedded in a program, the program management plan takes precedence. Project provisions of the project management plan must not run counter to the meaning and spirit of the corresponding program provisions. The exception to this rule is the choice between the traditional or agile approach to solution development. This must always be examined for each individual project and documented in the study.

**Basics**

- Stakeholder list - Study - Procurement analysis
- Next steps milestone
  140/244

* * *

**Activities**

- Obtain information about the project and its environment. - Draw up project management plan and in particular:

- Define the risk management process and risk assessment metrics; - Determine and communicate the change process;

- Set quality objectives for execution;

- Define a review procedure for the outcomes and processes/tasks and record it in the review plan chapter;

- Determine quality assurance review methods; - Adopt the procurement plan from the procurement analysis, check it, coordinate it with the study, adjust it if necessary, and record it;

- Under an agile approach, explicitly state whether the decision on release is manda- tory;

- Determine execution organization - Project organization including execution organization (agile) - Role assignment for core and project organization
  **Outcomes**

- Project management plan


## 5.4.3.37 Carry out prototyping

Concept Implementation Deployment Initiation Closure Execution

**Purpose** With prototyping, simplified but largely functional solution approaches can be created and tested. This permits checking of the feasibility or usability of the focused solution, and where applicable its helpfulness and acceptance. In addition to the technical and functional criteria, the appearance or the dimensions and proportions of the product and the visualized idea for services can also be assessed.

## Basic idea

Thecreationofaprototype-orperhapsonlyamodelinthecaseofproducts-isarisk-minimizing measure. Prototyping can be carried out once or several times in different phases depending on the project situation. A prototype can be reusable or disposable. Depending on the findings, the next steps are determined.

## HERMES specific

As needed, prototyping is carried out once or several times over the course of the project. The required basis/prerequisites depend on the needs and the project status. The objectives and the concept as well as the outcomes of the prototype are recorded in the prototype documentation. The prototype is developed and the outcomes from the prototyping are evaluated.

141/244

* * *

**Activities**

- Develop objectives, concept, and methodology for the prototype. - Create prototype. - Evaluate prototype.

- Document outcomes and conclusions and incorporate them into further planning. - Destroy prototype or ensure reusability.
  **Outcomes**

- Prototype realized - Prototype documentation


## 5.4.3.38 Perform quality assurance

Concept Implementation Deployment Initiation Closure Execution

**Purpose** Quality assurance ensures that the outcomes developed throughout the project are of the re- quired quality.

## Basic idea

In principle, quality assurance makes a distinction between "checking" and "testing":

- With respect to a system or product, checking includes the content-related and formal review of documents and compliance with agreed processes/tasks;
- Testing includes verifying the fulfillment of solution requirements and the applicability of the processes to the current system.
  The quality of an outcome becomes evident during development. Several QA measures are often carried out during development in order to ensure the required quality. Checkingortestingattheendofthedevelopmentprocessisusedfortheacceptanceorapproval of an outcome and confirms that the quality requirements for the outcome have been met.

## HERMES specific

The perform quality assurance task includes checking. Testing, on the other hand, is the subject of the tests module. Checking outcomes such as consultations, reviews, audits, etc., is performed in accordance with the project management plan. The project management plan also contains the review plan with the outcomes and their review procedure, as well as information on which role has to perform which review tasks under the traditional or agile approach. The reviews are listed as activities in the work order for the creation of the corresponding out- come. The outcomes of a review are recorded in the review report. The project sponsor can ask the project management to carry out quality assurance. To this end, theprojectsponsorappointsanindependentbodythatreportsdirectlytothesponsor. This measure is performed in the project steering module with the steer project task.

142/244

* * *

**Basics**

- Project management plan - Work order
  **Activities**

- Set quality objectives for the project phase or release-derived from the objectives to be achieved-in the project management plan.

- Record the review procedure and procedures in the work order in accordance with the projectmanagementplanandensurethatthereisuniformunderstandingamongallproject participants.

- (Delegate and) carry out/have carried out reviews and record the outcomes in the review report.

- Evaluate the fitness for purpose of quality assurance and make adjustments if necessary.
  **Outcomes**

- Project management plan - Review report


## 5.4.3.39 Analyze legal basis

Concept Implementation Deployment Initiation Closure Execution

**Purpose** Analysis of the legal basis ensures that the legal requirements for the project are met or that the measures are defined in such a way that they can be created.

## Basic idea

The legal basis must be complied with in every project. It constitutes an immovable restriction for a project.

## HERMES specific

Project management ensures that the existence of a sufficient legal basis is clarified. To this end, contact is made with the competent body (usually legal services or another unit responsible for legislative matters). In the absence of a sufficient legal basis, it is necessary

- again in cooperation with the competent bodies-to clarify whether and how the necessary adjustments to the legal basis can be made. **Basics**

- Project initiation release milestone - Project initiation order - Stakeholder list
  **Activities**

- Document the existing legal basis with regard to the future system.

- Analyze imminent changes to the existing legal basis.

- Identify possible gaps in the legal basis and work out proposals to fill the gaps with the competent bodies.

- Assess the impact on the study and project execution.
  143/244


* * *

- Coordinate the legal basis analysis with the stakeholders.

Outcomes

- Legal basis analysis

5.4.3.40 Prepare release closure

Purpose

For the closure of a release, the outcomes are summarized and made available for reporting as
part of the agile approach.

Basic idea

At the end of a release, information on the project status and forecast is delivered to project
steering via reporting. If a decision on release has to be made in accordance with the project
management plan, the information is required by the decision-makers for decision-making.

The release report is prepared. The overall success of the project is reviewed, the release that
iscomingtoanendisdescribed, thebenefitsarehighlighted, andknownerrorsarepointedout.

The release report forms the basis for reporting and for the project sponsor's decision on any
next release.

The project management plan is updated.

Basics

- Project management plan
- Project status report

- Project status report
- Change status list

- Change status list
- Lessons learned

- Lessons learned

Activities
-

- Identify next release according to release plan (project management plan).
- Verify execution plan.

- Verify execution plan.
-

- Update the project management plan and coordinate it with everyone involved as well as
with the controlling and compliance bodies.
- Summarize the outcomes of the release, including changes, in the release report.

- Project management plan
- Project status report

- Arrange for project steering decisions to be made.

- Summarize the outcomes of the release, including changes, in the release report.
- Update project status report as an appendix to the release report.

* * *

5.4.3.41 Manage risks

Purpose

Risk management identifies risks at an early stage and defines measures to ensure project
success.

Basic idea

Risks are possible future events that pose a problem if they occur. Project risks concern the
course of the project. Operational risks affect the utilization of the project outcomes.

Risks are identified, analyzed, and evaluated. Depending on the significance of a risk, the
strategy (e.g. avoidance, reduction, outsourcing, acceptance) and measures for dealing with
the risk are defined.

HERMES specific

Risks are managed within the framework of solution development according to the project management plan.

In the traditional approach, this is continuously and at the end of each phase. In the agile
approach, an in-depth risk review takes place at the end of each release so that the decision to
release the next phase or the next release can be made. The effective risks are recorded in the
phase or release report and in the project status report, depending on the project. The effective
risks are recorded in the phase or release report and in the project status report, depending on
the project.

The risk assessment is recorded in the QA and risk report.

As part of the steer project task, the project sponsor can commission superordinate risk management of the project.

Basics

- Phase report
- Release report

- Project management plan
- Phase report

- Identify risks and group them into risk areas; analyze risks and assess their probability of
occurrence and the extent of damage, and document this in the project status report.
- Define the strategy (e.g. avoidance, reduction, outsourcing, acceptance of the risk) for

- Define the strategy (e.g. avoidance, reduction, outsourcing, acceptance of the risk) for
each risk in the project status report and define, commission, and monitor the measures.
- Periodically communicate the assessment of the risk situation to the relevant bodies and

- Project status report
- Project management plan

- Periodically communicate the assessment of the risk situation to the relevant bodies and
persons using the project status report.

- Release report
-

- Project management plan

* * *

## 5.4.3.42 Analyze protection needs

Concept Implementation Deployment Initiation Closure Execution **Purpose** The protection needs analysis determines the information security and data protection require- ments.

## Basic idea

A protection needs analysis must be conducted for each IT project. This ensures that the ISDP aspects are taken into account from the start.

## HERMES specific

If the protection needs analysis shows that enhanced protection is necessary, an ISDP concept with an in-depth risk analysis must be designed during solution development.

**Basics**

- Project initiation release milestone - Project initiation order - Stakeholder list
  **Activities**

- Analyze information security and protection needs. - Perform risk analysis.

- Review information security and data protection requirements and assess the impact on the study, project execution, and the envisaged solution.

- Coordinate protection needs analysis with the controlling and compliance bodies.
  **Outcomes**

- Protection needs analysis


## 5.4.3.43 Manage and inform stakeholders

Concept Implementation Deployment Initiation Closure Execution

**Purpose** Stakeholdersareidentified,contacted,gainedfortheproject,theirbasicinterestsanalyzed,and measures defined to ensure the project's success. Informing stakeholders ensures the institu- tionalized flow of information between the project and its environment. Informing stakeholders also includes project marketing.

## Basic idea

The project manager and the project sponsor identify and analyze all persons or groups who have a legitimate interest in the course of the project or for whom it is important, due to their interests, how the future solution will work. The interests, expectations, and objectives of these affected stakeholders are compiled, analyzed, and examined for possible discrepancies and conflicts. To increase the chances of success, identified discrepancies or conflicts must be resolvedasfaraspossible. Ifnecessary,decision-makingprocessesareplannedanddecisions 146/244 are prepared. The communication objectives and communication measures are planned and/or carried out, and their impact is regularly reviewed. Communication takes target groups and stakeholder interests into account.

## HERMES specific

The task is in principle the responsibility of the project manager. It is defined for each project in the project management plan. The project manager compiles the stakeholder list together with the project sponsor and the stakeholder interests together with the user representative. The identification of stakeholders including the stakeholder list and stakeholder interests are created for the first time in the initiation phase and are continually pursued over the course of the project. The institutionalized information flow is defined in the communication plan as part of the project management plan.

**Basics**

- Project management plan - Stakeholder list - Stakeholder interests
  **Activities**

- Determine framework conditions and specifications for communication. - Identify and analyze stakeholders, compile and update stakeholder list and stakeholder interests.

- Identify suitable stakeholders as potential project committee members and propose them to the project sponsor.

- Continuously manage stakeholders. - Continuouslyinformprojectsponsor,userrepresentative,andotherauthorizedstakehold- ers.

- Define communication objectives, plan communication measures, and coordinate them with the project sponsor. Implement measures and measure impact. Continually update the communication plan in the project management plan.

- Create decision planning, coordinate it with the project sponsor, and integrate it into com- munication planning.
  **Outcomes**

- Stakeholder list - Stakeholder interests - Project management plan
  147/244


* * *

## 5.4.3.44 Advocate stakeholder interests

Concept Implementation Deployment Initiation Closure Execution

**Purpose** Stakeholders play a key role in solution development, given that they contribute requirements and the user's perspective to development and in that way directly influence the development process. The representation of stakeholders and their interests during solution development promotes the acceptance and success of the new solution.

## Basic idea

The identified and informed stakeholders are involved in the project to the extent that solution development can benefit directly from their knowledge, allowing the stakeholders to recognize the project results as their own solution. Stakeholders can be involved either through their representation in the project or through their direct participation in the solution as specialists.

## HERMES specific

The task is the responsibility of the user representative. The impulses and functional requirements of the stakeholders are contributed via change man- agement under the traditional approach, and as part of agile development under the agile ap- proach. The stakeholder interests compiled for the first time in the initiation phase are continuously pursued and analyzed over the course of the project.

**Basics**

- Stakeholder list - Stakeholder interests
  **Activities**

- Approach stakeholders, interview them, address specialized and solution-specific issues and problems together with them, obtain opinions from business practice.

- Receive suggestions and wishes from stakeholders and incorporate them into the project.

- Represent stakeholder interests in the project or allow stakeholders to participate directly in solution development.

- Update stakeholder interests.
  **Outcomes**

- Stakeholder interests


## 5.4.3.45 Prepare study

Concept Implementation Deployment Initiation Closure Execution

148/244

* * *

**Purpose**

The purposes of the study include setting objectives, defining rough requirements, and estab- lishing and evaluating solution options so that the decision on next steps can be made and documented in the study.

## Basic idea

Aprojectmustbeinlinewiththespecifications(strategyandobjectives)ofthecoreorganization. It must take account of the framework conditions, and its economic efficiency must be ensured. Thestudyisfleshedouttosuchanextentthatplanningaccuracyfordeadlines, costs, andeffort is achieved that is appropriate for the time of the project. It must be possible to assess the risks and economic efficiency comprehensively.

## HERMES specific

In a first step, the status report and the development of possible objectives based on the status report are used to check whether a (new) solution is needed at all and accordingly whether a continuation of the project appears necessary. As the study is fleshed out further, including all accompanyingoutcomes, itischeckedonanongoingbasiswhetheritmakessensetocontinue the project. If this is not the case, the initiation phase and the project are concluded. The findings from the legal basis analysis and the protection needs analysis are adopted. The set objectives and requirements form the basis for developing different options. The ob- jectives are finalized. The requirements are described in such a way that the project content and project scope are clear and the evaluation criteria can be defined. The requirements are fleshed out as the project progresses further. The options are described in the study on the basis of the objectives and requirements. Typical options include customized development on the one hand and the procurement of a solution available on the market on the other. Any findings (e.g. from the market environment) arising from the procurement analysis, which must be prepared in parallel with the study, are used to develop options involving procurement. The options are described in sufficient detail for them to be evaluated. The evaluation criteria are defined for evaluating the options. These include the degree of objective achievement, cov- erage of requirements, and other evaluation criteria such as compliance with the requirements, feasibility, risks, and benefits. Depending on the option, the approach-traditional or agile-is defined. The evaluation is comprehensibly documented and shows the current state of knowledge when the decision is made. Beforeplanningandscheduling,thesuitablescenarioforthesolutiondevelopment(seeSection "Scenarios") is selected and adapted as required.

**Basics**

- Project initiation release milestone - Project initiation order - Stakeholder list
  149/244

* * *

**Activities** Prepare the status report and record it in the study. Develop solution objectives and requirements, coordinate them with stakeholders, adjust the stakeholder list, and include them in the study. Identify conflicts of interest and resolve them with the project sponsor. Integrate market surveys and information from the procurement analysis into the study. Integrate the findings from the legal basis analysis and the protection needs analysis into the study. Describe solution options individually. Determine evaluation criteria and their weighting. Evaluate solution options based on the evaluation criteria. Select a suitable scenario, customize it further as needed, determine the project value, and define the approach (traditional/agile). Assess the impact of the decision on next steps on the project. Roughly plan project and deadlines, define rough cornerstones (milestones) Complete the study. Coordinate the study with the project sponsor and stakeholders, including the controlling and compliance bodies.

**Outcomes**

- Stakeholder list - Study

## 5.4.3.46 Activate system

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The system activation is the prerequisite for the activation of the operation.

## Basic idea

The system is activated so that operation can subsequently be activated.

## HERMES specific

After the decision on launch of operation, the developer activates the system.

**Basics**

- Launch of operation milestone
  **Activities**

- Activate system. - Provide support during the initial utilization period.

- Analyze problems that arise; define and decide on measures (bug fixing). - If necessary, take stabilization measures.
  150/244


* * *

**Outcomes**

- System activated

## 5.4.3.47 Integrate the system into operation

Concept Implementation Deployment Initiation Closure Execution **Purpose** The integration of the system into the operating infrastructure creates the prerequisites for car- rying out the tests and for preliminary acceptance. **Basic idea** The system realized (developed or parameterized) is:

- integrated into the operating infrastructure technically and organizationally; and - tested.

## HERMES specific

Basedontheintegrationconcept, onlythesystemisintegratedintotheoperatinginfrastructure. Testing is performed in the tests module. The links to peripheral systems are activated. According to the integration plan in the integration and installation instructions outcome, the integration of the system can be done in several steps. **Basics**

- Operating infrastructure realized - Operating organization realized - Operating manual

- Integration concept - Integration and installation instructions - System developed or parameterized

- Interfaces realized
  **Activities**

- Carry out and document integration steps according to the integration and installation instructions.

- Implement and ensure transition from one operating platform (e.g. development, testing, training, production) to another.

- Document lessons learned from the integration process in the operating manual for later maintenance and further development.

- Include operating concept and integration concept outcomes as attachments to the oper- ating manual.
  **Outcomes**

- System integrated - Operating manual
  151/244


* * *

## 5.4.3.48 Realize system

Concept Implementation Deployment Initiation Closure Execution **Purpose** Thesystemisdevelopedorparameterizedtothepointwhereitmeetsthesolutionrequirements and is ready for integration. **Basic idea** Based on the solution requirements of the system concept and the solution architecture, the detailed specifications are created. The system is realized:

- when a system is procured, the procured system is parameterized and system enhance- ments are developed;
- if customized development is envisaged for the system, the system is developed; - the user manual is produced.

## HERMES specific

The developer tests the system during realization before the first delivery to the user and oper- ator. Tests after the first delivery are supported by the tests module. The documentation compiled so far, in particular the system concept and the solution architecture, is updated as necessary and the user manual is produced. **Basics**

- Solution requirements - System concept - Solution architecture

- Solution architecture milestone - ISDP concept milestone
  **Activities**

- Create detailed specifications. - Develop or parameterize system.

- Arrange for quality assurance and testing to be conducted by developer. - Update documentation. - Produce user manual.

- Update system architecture.
  **Outcomes**

- User manual - System concept - Detailed specifications

- Solution architecture - System developed or parameterized
  152/244


* * *

## 5.4.3.49 Prepare system integration

Concept Implementation Deployment Initiation Closure Execution **Purpose** System integration is prepared by the developer to enable the operator to integrate the system into operation. **Basic idea** The detailed specifications needed for integration are prepared. **HERMES specific** Based on the integration concept, interfaces with peripheral systems and necessary adjust- ments to peripheral systems are realized. Integration into operation is prepared on the basis of the operating concept and the operator's specifications. The integration and installation instructions are drawn up. **Basics**

- Integration concept - Solution architecture - Operating concept
  **Activities**

- Create detailed specifications. - Develop interfaces. - Coordinate adjustments to peripheral systems.

- Prepare integration into operation. - Produce integration and installation instructions. - Update system architecture.
  **Outcomes**

- Detailed specifications - Integration and installation instructions - Solution architecture

- Interfaces realized


## 5.4.3.50 Conduct test

Concept Implementation Deployment Initiation Closure Execution **Purpose** Tests are conducted to ensure that the system meets the stipulated requirements. The tests are carried out and the test results are evaluated and recorded.

153/244

* * *

## Basic idea

Provided that the preconditions for doing so are met, the first tests are carried out on the test system. Accordingly, the test infrastructure must have been realized beforehand.

## HERMES specific

The conduct test task comprises:

1. proper testing on the test system of the realized test infrastructure;
2. testing of the integrated system as part of the integrate the system into operation task;
3. testing the realized product as part of the realize product task;
4. testing the realized migration procedure as part of the realize migration procedure task; and
5. quality testing as part of the perform quality assurance task.
   The tests are carried out according to the test case descriptions in the test concept. They are furtherspecifiedasneeded. Thetestresultsenteredinthetestreportareevaluatedaccordingto criteriadefinedinthetestconcept. Thetestreportischeckedbeforethedecisiononpreliminary acceptance. As needed, the tests are repeated several times until the quality criteria are met. Open issues from the tests and the next steps in this regard are established by binding agreement. The test plan in the test concept is continually updated.

**Basics**

- Test concept - Test infrastructure realized - ISDP measures realized

- ISDP concept
  **Activities**

- Check whether the preliminary conditions for testing are met to start the tests.

- Perform tests according to the test concept.

- Log the test results and evaluate them according to criteria in the test concept.

- If necessary, correct defects and repeat tests. - Agree on how to deal with unresolved issues.
  **Outcomes**

- Test concept - Test report


## 5.4.3.51 Realize test infrastructure

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The test infrastructure is provided before testing starts. It includes all elements necessary for test execution and the collection and evaluation of the test results.

154/244

* * *

## Basic idea

Provide test infrastructure with test system, test data, and test tools (e.g., test management system for collecting and evaluating the results). **HERMES specific** The test infrastructure is prepared in accordance with the responsibilities defined in the test concept. Quality assurance measures are used to check that the test infrastructure is ready and complete. **Basics**

- Test concept - Operating infrastructure realized
  **Activities**

- Provide test infrastructure according to the test concept. - Ensure the quality of the test infrastructure.

- Release the test infrastructure for testing.
  **Outcomes**

- Test infrastructure realized


## 5.4.3.52 Transfer test infrastructure

Concept Implementation Deployment Initiation Closure Execution **Purpose** After project closure, tests are conducted during the utilization and maintenance phase for cor- rections and for further developments. For that reason, the test infrastructure including the test concept must be transferred to the core organization. **Basic idea** Toenablemaintenanceandfurtherdevelopmentofthesystemduringtheutilizationphaseafter the end of the project, the test infrastructure including the test concept must be transferred to the core organization before project closure. **HERMES specific** The test concept and test infrastructure are transferred after acceptance, but before project closure. They are transferred by the project organization to those responsible for operation and further development at the user, developer, and operator. **Basics**

- Acceptance milestone - Test concept
  155/244

* * *

**Activities**

- Adjust the test concept with test case descriptions and test data or update it with findings from the tests.

- Inform and train those responsible. - Carry out formal transfer. - Record transfer in the minutes.
  **Outcomes**

- Test concept - Minutes - Test infrastructure transferred


## 5.4.3.53 Design test concept

Concept Implementation Deployment Initiation Closure Execution

**Purpose** The test concept creates the prerequisites for the systematic and efficient organization and execution of the tests.

## Basic idea

Testing solutions requires specific test management. This is described by the test concept. The test concept with the test plan and test case descriptions is the basis on which the test organization and test infrastructure are provided and the tests are carried out.

## HERMES specific

Thebasisforthetestconceptisprovidedbythesolutionrequirementsandbythecorresponding concepts. The development of the test concept requires close cooperation between the user, developer, and operator, given that they have to make further essential contributions to the testing pro- cess in addition to the information from the basic documents. The test concept must be jointly accepted and then implemented.

**Basics**

- Solution requirements - Organizational requirements - Product concept

- System concept - Operating concept - Migration concept
  **Activities**

- Establishqualityfeaturesandrequirementsor, ifalreadyavailable, verifyandrecordthem in the test concept.

- Define test objectives and test types, and record them in the test concept.

- Describe test infrastructure with test system, test data, and test tools.

- Prepare test objects, test organization, test case descriptions, and test plan as part of the test concept.
  156/244


* * *

- Coordinate the test concept with the stakeholders.

Outcomes

- Test concept

5.4.3.54 Draw up agreement

Purpose

Theagreementisdrawnuponthebasisofthetenderdocumentationincludingappendicessuch
as the draft contract, the general terms and conditions, and the offer.

Basic idea

A project agreement, a contract, or service level agreements (SLAs) govern cooperation between different project participants such as the user (project sponsor), developer, and operator
and can be concluded for one or more phases.

This task is related to the agree on and steer goods/services task, with which the contract is
concluded and the goods/services are steered.

Once the agreement is concluded, the goods/services are periodically checked for compliance
with the planning and agreements. This is dealt with in the agree on and steer goods/services
task.

Basics

- Tender documentation
-

- Project management plan
- Offer

- Offer
-

- Contract award milestone

- Draw up agreement.
-

- Have the core organization or controlling and compliance bodies review the agreement.
- Ensure contract execution.

- Agreement

* * *

6 Roles

6.1 Introduction

6.1.1 Role model

HERMESdefinesarolemodelanddescribesstandardizedrolesinordertocreateauniformunderstanding across the whole organization. A distinction is made between stand-alone projects
and projects embedded in a program. All described roles are exclusively HERMES roles.

The role model distinguishes between the role groups of the core organization and the roles
and role groups of the project organization. The figure below shows the role model of a core
organization with the role groups of executive board, project management competence center,
and controlling and compliance bodies, along with a project organization (traditional/agile) with
the minimum required roles of project sponsor, project management, and user representative
(shaded in gray). Other roles may be used as needed.

Figure 24: Core organization and project organization with minimum required roles (gray)

The term "core organization" is defined broadly in HERMES. A core organization can be, for
example, an administration, a school, an institute, an association, or a company. In the case
of state or large communal administrations, corporate groups, complex companies, etc., the
role of core organization can be played by individual organizational units or even individual
departments.

In agile project organization, the role of user representative functions as an interface to the
execution organization. The role holder assumes specialist responsibility by additionally taking
on a corresponding role in the execution organization (dashed line).

Asthefigureaboveshows,threepermanentrolegroupsarerelevantforallstand-aloneprojects
in the core organization:

* * *

- Executive board Steers the portfolio from a strategic perspective, prioritizes projects, and assigns infras- tructure as well as human and financial resources to the specific project.
- Project management competence center Often also referred to as the project management office (PMO) of the core organization. Provides and further develops methods, tools, coaching, and other goods and services for project and program management and often also manages the portfolio operationally.
- Controlling and compliance bodies Define requirements and check compliance from the perspective of the overall organiza- tion. Suchbodiesincludefinancialcontrol, auditing, ITcontrolling, andtherelevantbodies for solution architecture and ISDP, for example.
  The roles of the role groups listed vary depending on the core organization.

## 6.1.3 Project organization

## 6.1.3.1 Overview

The project organization is a one-off, temporary, and often interdisciplinary organization that is closely linked to the core organization. It is put into effect with the project initiation order and dissolved with the decision on project closure at the latest. The project organization is continuously adapted to the needs of the project over the course of project execution, especially with the execution order. Depending on how the project unfolds, additional project participants may join the project organization. For example, an external ten- dererofaproductisnotdetermineduntilafterprocurementandthenbecomespartoftheproject organization. The agile execution organization is only part of the project organization during the execution phase. In the initiation and closure phases, the project organization remains traditional, which does not prevent the project team from using agile techniques for appropriate tasks. The project organization consists of various roles. They regulate the tasks, powers, and re- sponsibilities of those involved in the project. Each role is specified with a role description.

## 6.1.3.2 Partner groups

Each role is assigned to one or more partner groups. The HERMES project organization com- prises the partner groups of user, developer, and operator:

- User The user is the owner of the project and uses the solution to handle business processes. Users are responsible for defining their requirements for the solution, and they test and accept the product/system or solution.
- Developer The developer as a service provider either develops or supplies and integrates the solu- tion. The developer is responsible for development or delivery and integration according to the specifications in terms of quality, time, and costs.
- Operator The operator as a service provider integrates the technical solution into the operating environment, ensures the operating organization, and operates the system. The operator is responsible for the provision of the operating infrastructure, operational integration, the operating organization, and operation in accordance with the agreements.
  Inpractice, projectsareoftensupportedbysuppliersorexternalserviceproviders. Inparticular, the roles of the developer partner group are often filled by external service providers. If various services of the core organization are outsourced, the operators, for example, and increasingly eventheusers(e.g. bymeansofprojectmanagerpools),canalsobeexternalserviceproviders.

159/244

* * *

Notwithstandingthis, theroleholdersmustalwaysandexclusivelyrepresenttheroleviewofthe
partner group for which they are providing services in order to rule out any conflicts of interest.

Each partner group of users, developers, or operators has its own power and responsibility to
decide on representation in the project by service providers from outside the partner group.

6.1.3.3 Hierarchy levels

Each role is assigned to one of the hierarchy levels of steering, management, or execution:
-

- Steering roles
steer theproject as a whole across the organization andensure that the set objectives are

steer theproject as a whole across the organization andensure that the set objectives are
achieved.
-

- Management roles

draw up project foundations, manage project and employees.
- Execution roles

- Execution roles
develop the solution and implement quality assurance measures.

develop the solution and implement quality assurance measures.

The figure below shows the assignment of roles to the hierarchy levels shown in yellow in a
typical traditional and agile project organization.

Figure 25: Role assignment to hierarchy levels of a traditional or agile project organization

6.1.3.4 Project roles in programs

Program management is described in the appendix to this reference manual. The following
explanations look at program management from the project perspective.

* * *

Figure 26: Projects combined into programs

The program sponsor steers the program. Depending on the form of the program organization
(see the figure below), the program management manages the program and coordinates the
cross-project aspects and the dependencies between the projects. Each project is managed by
its own project management. The user representative defines the solution.

The steering of the project can be supported by a project committee (under the direction of the
project sponsor) and/or at a superordinate level by a program committee (under the direction
of the program sponsor). From the perspective of the controlling and compliance bodies, each
individual project is an independent controlling object with specifications in terms of costs, time,
and outcomes.

The program closure program phase can be released only once all projects are completed.

Forms of organization

If a project becomes part of a program, the project organization must be integrated into the
program organization and various project organization roles have to be adjusted or replaced.
These primarily concern the roles of the project sponsor and the project management. The
adjustments can vary depending on the organization form chosen for the program. The effects
are mainly in the areas of steering, management, and control.

The adjusted role descriptions for the program are recorded in the project management plan.

The diagram in the figure below schematically shows three conceivable forms of organization:
one as a stand-alone project, and two as parts of a program.

The minimum roles to be filled in the project are shown in gray. Program-specific roles are
outlined in blue and are not discussed further here.

The following description discusses the three organizational forms shown in the figure above
from the project perspective. The discussion is rudimentary and for a general understanding
only.

* * *

## Project organization

A certain core organization is responsible for the success of the project:

- The project sponsor is responsible for the success of the project and steers the project;
- The project management manages the project on behalf of the project sponsor;
- The user representative is responsible for the solution.

## Program organization 1

Several core organizations are responsible for the success of the projects assigned to them:

- The program management runs and coordinates the project and the project management from the perspective of the overarching program and continuously coordinates with the project sponsor.
- The project sponsor is responsible for the success of the respective project, upholds the interests of its core organization, steers the project on behalf of the program sponsor and works with the program sponsor to address and resolve any conflicts of interest that may arise between the objectives of the program and those of the core organization;
- The project management manages the project on behalf of the project sponsor, executes theprogram-specificinstructionsoftheprogrammanagementandcoordinatestheproject management plan with the program management;
- The user representative is responsible for the solution.
  This type of program organization changes the roles of the project sponsor and the project management. Each project sponsor reports to both their own core organization and to the programsponsorandmusttakebothinstancesintoaccountwhenmakingdecisions. Theproject management is coordinated by the program management.

## Program organization 2

Acertaincoreorganizationisresponsibleforthesuccessoftheprogramandallprojectsinvolved in it:

- Theprogrammanagement(fromaprojectperspectiveatthesteeringhierarchylevel,from a program perspective at the management hierarchy level), steers the project and man- ages (see role description of project sponsor) the project management, but the responsi- bility for the project success lies with the program sponsor;
- Theprojectmanagementmanagestheprojectonbehalfoftheprogrammanagementand coordinates the project management plan with them;
- The user representative is responsible for the solution.
  Thistypeofprogramorganizationhasnosponsorattheprojectlevel,replacingtheprojectspon- sor with the program management. The program management assumes all tasks and duties of the project sponsor within a project. The project management is thus subordinate to a program management, which is assigned to the steering hierarchy level in the project organization, and to the management level in the program organization.

162/244

* * *

6.2 Overview of roles

6.2.1 Standard roles

Thefollowingtablelistsallstandardrolesandshowstheirassignmenttothehierarchyleveland
the partner group.

| Hierarchy level | Role |
| --- | --- |
| Steering | Steering roles |
|  | Project sponsor\* |
|  | Project committee |
|  | Quality and risk manager |
| Management | Management roles |
|  | Technical committee |
|  | Project management\* |
|  | Project support |
|  | Sub-project manager |
| Execution | Execution roles |
|  | User representative\* |
|  | Operations manager |
|  | Business analyst |
|  | Developer |
|  | Execution organization |
|  | ISDP manager |
|  | IT architect |
|  | Tester |
|  | Test manager |

|  | User | Creator | Operator |
| --- | --- | --- | --- |
| X | X | X | X |
| X |  |  |  |
| X | X | X | X |
| X |  |  |  |
| X | X | X |  |
| X | X | X | X |
| X | X | X | X |
| X |  |  | X |
| X | X |  |  |
|  | X |  |  |
| X | X | X |  |
| X |  |  |  |
| X | X | X |  |
| X | X | X |  |
| X | X | X |  |

The user representative is responsible for development of the product/specialist solution.

The minimum roles to be filled, marked with an asterisk (\*), are required in order to meet the
governancerequirements. Thesethreerolesareindispensablefortheproject,regardlessofthe
selected approach (traditional or agile), and must be located in the user partner group. They
must be filled in every project:
-

- The project sponsor has overall responsibility for the project and the achievement of the
objectives.
- The project manager has sole management responsibility and is responsible for the

Other mandatory roles are assigned depending on project requirements.

The execution roles, also referred to in organization charts as specialists (with the exception of
theuserrepresentative),arenumerousandnotexhaustive. Dependingonthecoreorganization
or the type of project, further project-specific execution roles may be added.

Under the agile approach, all execution roles involved in the project are combined in the execution organization during the execution phase. The execution organization role is a role group.

* * *

## 6.2.2 Customized roles

Supplementing the standard roles available, it is also possible to integrate own specialist, organization-specific, or project-specific roles into own projects. This is supported by HER- MES online and is especially relevant when new modules are developed and provided with new tasks and outcomes. Examples of customized roles are integration manager, logistician, real estate manager, purchaser, and facility manager.

## 6.2.3 Role assignment

## 6.2.3.1 General explanations

The role assignment is defined for each role required in the project. Role assignment is in accordance with the project requirements. It takes into account the ex- perience required in the project, the capacity needed, and the availability of the role holders. Theconcreteprojectorganizationandroleassignmentarerecordedintheprojectmanagement plan. In order to comply with project governance, the following principles must be observed when assigning the roles:

- One person can take on several roles, provided that no conflicts of interest arise as a result.
- Onerolecanbeheldbyseveralpeople, providedthattheroleallowsmultipleholders. For example, there are usually several testers in a project, but only one project sponsor.
  Information on role assignment for selected roles at the hierarchy levels of steering, manage- ment, and execution is provided below.

## 6.2.3.2 Steering

## Project sponsor

- The project sponsor must be located with the user.
- The project sponsor must be a single natural person from the core organization.
- The project sponsor initializes, finances, and steers the entire project.
- The project sponsor is the project's representative with regard to the executive board of the core organization and the controlling and compliance bodies and must be located at a correspondingly high hierarchy level in the core organization.
- The project sponsor ensures that the stakeholders identified by the project management who are important to the success of the project are represented in the project.
- Therolesofprojectsponsorandprojectmanagementmaynotbeheldbythesameperson.

## Project committee

- The project sponsor appoints the members of the project committee.
- Organizations relevant to the success of the project are represented in the project com- mittee.
- The project sponsor determines the voting rights of the project committee members.

## Quality and risk manager

- Depending on the size of the project and the risks, the project sponsor appoints a quality and risk management body, which reports directly to the project sponsor.
- The independent organization providing the quality and risk manager does not assume any further roles in the project and must ensure the independence of the mandate.
  164/244

* * *

## 6.2.3.3 Management

## Project management

- The project sponsor appoints the project management.
- The project management must be located with the user and solely represent the user's interests in the project. This also applies if the role holder is organizationally subordinated orlocatedelsewhere(e.g. externalrecruitmentorpoolorganization). Provisionbypartner groups, developers, or operators should be avoided due to potential conflicts of interest and to ensure governance.
- The project management manages the project and is responsible for the smooth progress of the project including all sub-projects.
- The project management can also be a sub-project manager.
- If the project management additionally takes on an execution role, the project sponsor must ensure that sufficient capacity is available for project management.

## Sub-project manager

- The project management appoints the sub-project manager.
- The sub-project manager should be based with the user, but in any case exclusively rep- resenttheuser'sinterestsintheproject. Thisappliesinparticulariftheroleholderisorga- nizationally subordinated or located elsewhere. Provision by partner groups, developers, or operators may be considered (the project management has overall responsibility).
- Thesub-projectmanagermanagesthesub-projectandisresponsibleforsmoothprogress of the project vis-à-vis the project management.
- If the sub-project manager additionally takes on an execution role, the project manage- ment must ensure that sufficient capacity is available for sub-project management.

## 6.2.3.4 Execution

**General**

The responsibilities, powers, and skills of all execution roles remain the same regardless of whether the roles are part of a project team or a sub-project team.

## User representative

- The project sponsor appoints the user representative.
- The user representative must be located with the user. Provision by developers or opera- tors should be avoided due to a lack of knowledge of the user environment and potential conflicts of interest.
- The user representative is responsible for the specialist design of the solution. - Iftheuserrepresentativeadditionallytakesonafurtherexecutionrole,theprojectsponsor must ensure that sufficient capacity is available for user representation.
- The user representative is constrained by the assigned resources when developing the solution.

## Business analyst

- The business analyst can, based on their expertise, also take on the role of user repre- sentative. However, this requires in-depth knowledge of the specialist area in question for which the solution is being developed.
  165/244

* * *

**Tester**

- Each partner group represented in the project (user, developer, operator) tests in its area of responsibility.

### Test manager

Each partner group represented in the project (user, developer, operator) can appoint a test manager in its area of responsibility.

## 6.3 Explanation regarding role description

Therolesdescribetheresponsibility,powers,andrequiredskillsofthoseinvolvedintheproject. They form the basis for a common understanding. The roles are assigned to specific tasks and outcomes. For each role, a role description is provided that is always structured in the same way:

- Description conveys an understanding of the role.
- Responsibility describes, where applicable, the responsibility of the role.
- Powers describe, where applicable, the powers of the role.
- Skills describe what knowledge a person needs in order to perform the role. When describing skills, no distinction is made between knowledge and experience, given that the level of skills required is highly dependent on the project.
- Relationships (where relevant) show for each module the specific tasks for which the role is responsible and which other roles are involved in the creation of the outcome. If the role has no task responsibility, relationships are not listed.
- The role responsible for the task is also responsible for achieving the outcomes and for the outcomes themselves.
- The roles involved in achieving the outcomes are not exhaustive and have to be defined according to the specific project.

## 6.4 Description of the roles

### 6.4.1 Steering roles

### 6.4.1.1 Project sponsor

**Description**

The project sponsor is responsible for the outcomes of the project and the achievement of the set objectives within the set framework conditions.

**Responsibility**

- Initiation and steering of the project - Overall responsibility for the project and objective achievement
- Reconciliation of the project objectives with the overarching strategies, requirements, and objectives of the core organization
- Provisionofresources(financial, human, infrastructure)andassurancethattheyareused efficiently
- Timely decisions on requests and measures - Chairing of the project committee and appointment of its members
  166/244

* * *

- Appointment and steering of the project management, definition of the project management's powers
- Assurance of sufficient participation by the specialist area

- Assurance of sufficient participation by the specialist area

Competence

- Decision-making power within the framework of the allocation of powers by the core organization
-

- Allocation of financial and human resources, as well as infrastructure, to the project
- Escalation to the core organization

- Escalation to the core organization

Skills

- Business understanding and knowledge of the specialist area
- Knowledge of the core organization requirements for the project (e.g. for procurement,

- Knowledge of the core organization requirements for the project (e.g. for procurement,
financing, controlling, security), for project steering, and for the project organization
- Business administration knowledge to ensure the efficient and effective use of financial

- Business administration knowledge to ensure the efficient and effective use of financial
and human resources
- In-depth knowledge of project initiation and project management

- In-depth knowledge of project initiation and project management
- Knowledge of HERMES, attested to by course attendance

- Knowledge of HERMES, attested to by course attendance
- Communicationskillstorepresenttheprojectinternallyandexternally,managestakehold-

- Decisiveness and assertiveness

Relationships

- Communicationskillstorepresenttheprojectinternallyandexternally,managestakeholders, and resolve conflicts
- Decisiveness and assertiveness

| Module | Task | Task responsibility |
| --- | --- | --- |
| Project steering | Decide on project initiation release | Project sponsor |
|  |  |  |
|  |  |  |
|  | Decide on execution release | Project sponsor |
|  |  |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
| Sensor | List of steering project decisions | Project sponsor, Project management |
|  | Project initiation order | Project sponsor, Project management |
|  | Project initiation release milestone | Project sponsor, Project management |
|  | Project initiation release checklist | Project sponsor, Project management |
| Sensor | Execution release milestone | Project sponsor, Project management, Project committee |
|  | Execution release checklist | Project sponsor, Project management, Quality and risk manager |
|  |  |  |
|  |  |  |
|  | Decide on project closure | Project sponsor |
|  |  |  |
|  |  |  |
|  | Decide on phase release | Project sponsor |
|  |  |  |
|  |  |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | List of steering project decisions | Project sponsor, Project management |
|  | Execution order | Project sponsor, Project management, User representative |
| Sor | Project closure checklist | Project sponsor, Project management, Quality and risk manager |
|  | Project closure milestone | Project sponsor, Project management, Project committee |
|  | QA and risk report | Project sponsor, Quality and risk manager |
|  | List of steering project decisions | Project sponsor, Project management |
| Sor | Phase release checklist | Project sponsor, Project management, Quality and risk manager |
|  | Phase release milestone | Project sponsor, Project management, Project committee, User representative |
|  | List of steering project decisions | Project sponsor, Project management |
|  | QA and risk report | Project sponsor, Quality and risk manager |
|  | Decide on project discontinuation | Project sponsor |
|  |  |  |
|  |  |  |
|  |  |  |
| Decide on release | Project sponsor |  |
|  |  |  |
|  |  |  |
| Decide on closure phase release | Project sponsor |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
| or | Project discontinuation checklist | Project sponsor, Project management, User representative, Quality and risk manager |
|  | Final project evaluation | Project sponsor, Project management |
|  | List of steering project decisions | Project sponsor, Project management |
|  | Lessons learned | Project sponsor, Project management, User representative |
|  | Project closure milestone | Project sponsor, Project management |
| or | QA and risk report | Project sponsor, Quality and risk manager |
|  | Release milestone | Project sponsor, Project management, Project committee, User representative |
|  | Release checklist | Project sponsor, Project management, User representative, Quality and risk manager |
|  | List of steering project decisions | Project sponsor, Project management |
| or | Closure phase release checklist | Project sponsor, Project management, Quality and risk manager |
|  |  |  |
|  |  |  |
|  |  |  |
| Steer project | Project sponsorship |  |
|  |  |  |
| Procurement | Decide on call for tenders | Project sponsorship |
|  |  |  |
| Decide on contract award | Project sponsorship |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Closure phase release milestone | Project sponsor, Project management, Project committee, User representative |
|  | List of steering project decisions | Project sponsor, Project management |
|  | QA and risk report | Project sponsor, Quality and risk manager |
| or | QA and risk report | Project sponsor, Quality and risk manager |
|  | List of steering project decisions | Project sponsor, Project management, Project committee |
| or | Tender checklist | Project sponsor, Project management, User representative, Quality and risk manager |
|  | List of steering project decisions | Project sponsor, Project management |
|  | Tender milestone | Project sponsor, Project management, Project committee, User representative |
| or | Contract award checklist | Project sponsor, Project management, User representative, Quality and risk manager |
|  |  |  |
|  |  |  |
| Deployment organization | Decide on launch of operation | Project sponsorship |
|  |  |  |
|  |  |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Contract award milestone | Project sponsor, Project management, Project committee, User representative |
|  | List of steering project decisions | Project sponsor, Project management |
|  | Publication | Project sponsor, Project management |
| or | Launch of operation checklist | Project sponsor, Project management, Quality and risk manager |
|  | Launch of operation milestone | Project sponsor, Project management, Project committee |
|  | List of steering project decisions | Project sponsor, Project management |

Table 20: Tasks for which the project sponsor is responsible and other roles involved in
creating the outcomes

Description

- Support for the project and its anchoring in the organization represented by the project
committee member
- Early raising of concerns of the organization represented

- Early raising of concerns of the organization represented
- Participation in the development of solutions to problems

- Participation in the development of solutions to problems

* * *

**Competence**

- Can request a project review or project audit - Power to issue recommendations:

- Recommendations on closure and release of phases to the project sponsor

- Recommendations on risk-minimizing measures to the project sponsor (e.g. on ap- pointment of project controlling or the quality and risk manager)

- Can gather all the information needed to steer and assess the project

- If eligible to vote, may participate in voting
  **Skills**

- Overarching knowledge of the specialist area - In-depth knowledge of the special field represented

- Business administration knowledge to ensure the efficient and effective use of financial and human resources

- In-depth knowledge of project steering - Knowledge of HERMES, ideally by means of course attendance

- Ability to work in a team, to communicate, and to resolve conflicts


## 6.4.1.3 Quality and risk manager

**Description** The quality and risk manager supports the project sponsor with an independent assessment of the project and recommends measures to achieve the project objectives. **Responsibility**

- Assessment of compliance with the requirements of the core organization

- Assessment of the procedure and the outcomes of project management, project organi- zation, and cooperation in the project

- Comprehensive assessment of the processes of project steering, project management, and project execution in regard to all project participants

- Evaluation of the project outcomes from a qualitative perspective - Assessment of the project status and forecasts

- Assessment of risks - Recommendation of measures to deal with risks and achieve the project objectives

- Transparent reporting to the project sponsor
  **Competence**

- Recommendations on closure and release of phases to the project sponsor - Recommendations on measures to the project sponsor

- Cangatheralltheinformationneededtoassesstheproject(withdirectaccesstoallproject participants, including execution organization)
  **Skills**

- In-depth knowledge of project management, particularly concerning the aspects of con- trolling, quality assurance, and risk management

- Business administration knowledge - In-depth knowledge of HERMES, attested to by a certificate

- In the case of agile implementation, in-depth knowledge of the agile method used

- Ability to work in a team, to communicate, and to resolve conflicts

- Good writing skills, e.g. to create reports
  172/244


* * *

## 6.4.2 Management roles

## 6.4.2.1 Technical committee

**Description** Thetechnicalcommitteeisrolegroup,whichunderthe traditional approachsupportstheproject management with the evaluation of outcomes. The members of the technical committee raise the concerns of the organizational unit they rep- resent. Theprojectmanagementorganizesandchairsthemeetingsofthetechnicalcommittee.

**Responsibility** Advice and support for the project management in the evaluation of specialist issues and out- comes Support for the project and its anchoring in the organization represented by the technical com- mittee member Early raising of concerns of the organization represented

**Competence**

- Gives recommendations on outcomes to the project management - Gives recommendations on quality assurance measures to the project management

- Can access all required information
  **Skills**

- In-depth knowledge of the specialist area and special field represented

- Business administration knowledge for evaluating and prioritizing requirements and as- sessing options and economic efficiency

- Ability to work in a team, to communicate, and to resolve conflicts


## 6.4.2.2 Project management

**Description** The project management manages the project on behalf of the project sponsor. The project management manages and coordinates the project regardless of the specialist focus of the solution and the chosen development approach.

**Responsibility**

- Management of the project to achieve the set objectives (especially time, cost, quality) and procedure objectives
- Economical and sustainable use of resources - Management of reporting and provision of comprehensive, regular, and situational infor- mation to project steering so that the relevant steering and decision-making tasks can be performed
- Identification and recruitment of stakeholders for the project, analysis of their basic inter- ests
- Management of risks and of quality assurance - Compliance with organizational requirements (governance)
- Ensuring timely involvement of the responsible controlling and compliance bodies so that their legitimate requirements are met
- Arrangement of the methods, practices, and tools to be used in the project in addition to HERMES and assurance of their use, provided they do not fall within the sovereignty of the agile execution organization.
  173/244

* * *

- Implementation of steering and management decisions
- Performance of procurement in accordance with the requirements

- Performance of procurement in accordance with the requirements
- Verification of compliance by the contracting parties in the project with the SLA (service

- Verification of compliance by the contracting parties in the project with the SLA (service
level agreement)

Competence

- Can access all project information
- Authority to use the resources released

- Authority to use the resources released
- Sole project management responsibility and authority to give instructions, without interfer-

- Sole project management responsibility and authority to give instructions, without interfering with the sovereignty of the execution organization under the agile approach, as long
as it remains within the scope of the execution order
- Decision-making power within the framework defined with the project sponsor

- Decision-making power within the framework defined with the project sponsor
- In consultation with the project sponsor:

- Division of the project into sub-projects,
- Appointment of sub-project managers, and

- In consultation with the project sponsor:
- Division of the project into sub-projects,

- Appointment of sub-project managers, and
- Delegation of management tasks.

- Delegation of management tasks.

Skills

- Knowledge of the core organization's requirements in terms of the project, operation, and
application of the solution (e.g. for procurements, financing, controlling, security)
- In-depth project management knowledge (main criterion)

- In-depth knowledge of HERMES, attested to by a certificate
- Good knowledge of the methods and practices used in the project

- In-depth project management knowledge (main criterion)
- In-depth knowledge of HERMES, attested to by a certificate

- Good knowledge of the methods and practices used in the project
-

- Business administration knowledge to assess options and economic efficiency and to ensure the efficient and effective use of financial and human resources
- Decisiveness and assertiveness

- Decisiveness and assertiveness
- Managerial skills

- Managerial skills
- Communication skills

- Communication skills
- to represent the project internally and externally;

- to represent the project internally and externally;
- to manage stakeholders and resolve conflicts;

| Module | Task | Task responsibility | Outcome | Involved in creation of outcome |
| --- | --- | --- | --- | --- |
| Project management | Draw up project execution order | Project management | Execution order | Project management, User representative, Project support |
| Manage risks | Project management | Project status report | Project management, Project support |  |
|  |  | Project management plan | Project management |  |

Relationships

- to be able to communicate in a manner appropriate to the level (e.g., during presentations in the project committee, before committees of the core organization, etc.)
Good writing skills, e.g. to create project reports

- to manage stakeholders and resolve conflicts;
-

- Good writing skills, e.g. to create project reports

* * *

| Module | Task | Task responsibility |
| --- | --- | --- |
|  | Deal with problems and benefit from lessons learned | Project management |
| Manage and control project | Project management |  |
|  |  |  |
|  |  |  |
|  |  |  |
| Prepare release closure | Project management |  |
|  |  |  |
|  |  |  |
| Draw up project management plan | Project management |  |
| Prepare phase release | Project management |  |

| y | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Lessons learned | Project management, Project sponsor, User representative |
|  | Work order | Project management, User representative, Project support |
|  | Solution requirements | Project management, User representative |
|  | Detailed specifications | Project management, User representative |
|  | Project status report | Project management, Project support |
|  | Project management plan | Project management |
|  | Minutes | Project management, User representative, Project support |
|  | Release report | Project management, User representative, Project support |
|  | Project management plan | Project management |
|  | Project status report | Project management, Project support |
|  | Project management plan | Project management, Project sponsor |
|  | Project management plan | Project management |
|  |  |  |
|  |  |  |
| Manage changes | Project management |  |
|  |  |  |
|  |  |  |
| Agree on and steer goods/services | Project management |  |
|  |  |  |
|  |  |  |
| Manage and inform stakeholders | Project management |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Project status report | Project management, Project support |
|  | Phase report | Project management, User representative, Project support |
|  | Change status list | Project management, User representative, Project support |
|  | Change request | Project management, User representative, Business analyst, Project support |
|  | Solution requirements | Project management, User representative |
|  | Project management plan | Project management |
|  | Evaluation report | Project management, User representative, Project support |
|  | Agreement | Project management, Project sponsor, Project support |
|  | Quote request | Project management, Project support |
|  | Offer | Project management, Project support |
|  | Stakeholder list | Project management, Project sponsor, Business analyst, Project support |
|  |  |  |
| Perform quality assurance | Project management |  |
|  |  |  |
| Prepare project closure | Project management |  |
| Project foundations | Analyze legal basis | Project management |
| Decide on next steps | Project management |  |
|  |  |  |
|  |  |  |
|  |  |  |

| City | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Stakeholder interests | Project management, User representative |
|  | Project management plan | Project management, Project sponsor |
|  | Project management plan | Project management |
|  | Review report | Project management, User representative, Project support |
|  | Final project evaluation | Project management, Project support |
|  | Lessons learned | Project management, Project sponsor, User representative |
|  | Legal basis analysis | Project management, Project support |
|  | List of management project decisions | Project management, User representative, Project support |
|  | Next steps checklist | Project management, User representative, Quality and risk manager, Project support |
|  | Study | Project management, User representative |
|  | Next steps milestone | Project management, User representative |
|  | Prepare study | Project management |
|  |  |  |
| Procurement | Draw up agreement | Project management |
| Issue call for tenders | Project management |  |
|  |  |  |
| Product | Decide on product concept | Project management |
|  |  |  |
|  |  |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Stakeholder list | Project management, Project sponsor,User representative,Business analyst,Project support |
|  | Study | Project management,User representative,Business analyst,IT architect,Project support |
|  | Agreement | Project management,Project sponsor,User representative |
|  | Tender documentation | Project management,User representative,Project support |
|  | Offer | Project management,User representative,Operations manager,Developer |
|  | List of management project decisions | Project management,Project support |
|  | Product concept checklist | Project management,Quality and risk manager,Project support |
|  | Product concept milestone | Project management,User representative |
| IT system | Decide on solution architecture | Project management |
|  |  |  |
| Deployment organization | Decide on acceptance | Project management |
|  |  |  |
|  |  |  |
|  | Decide on preliminary acceptance | Project management |
|  |  |  |

| V | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Solution architecture milestone | Project management, User representative |
|  | Solution architecture checklist | Project management, Quality and risk manager, Project support |
|  | List of management project decisions | Project management, Project support |
|  | Acceptance report | Project management, User representative, Operations manager, Developer, Quality and risk manager, Project support |
|  | Acceptance checklist | Project management, Quality and risk manager, Project support |
|  | List of management project decisions | Project management, User representative, Project support |
|  | Acceptance milestone | Project management, User representative |
|  | Preliminary acceptance milestone | Project management, User representative |
|  | List of management project decisions | Project management, User representative, Project support |
|  |  |  |
|  |  |  |
| IT migration | Decide on acceptance of migration | Project management |
|  |  |  |
|  |  |  |
| ISDP | Decide on ISDP concept | Project management |

| Category | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Preliminary acceptance checklist | Project management, Quality and risk manager, Project support |
|  | Acceptance report | Project management, User representative, Operations manager, Developer, Quality and risk manager, Project support |
|  | Acceptance report | Project management, User representative, Operations manager, Developer, Quality and risk manager, Project support |
|  | Migration acceptance milestone | Project management, User representative |
|  | List of management project decisions | Project management, User representative, Project support |
|  | Migration acceptance checklist | Project management, Quality and risk manager, Project support |
|  | List of management project decisions | Project management, Project support |
|  |  |  |
|  |  |  |

| y | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | ISDP concept checklist | Project management, Quality and risk manager, Project support |
|  | ISDP concept milestone | Project management, User representative |

Table 21: Tasks for which the project management is responsible and other roles involved in
creating the outcomes

6.4.2.3 Project support

Description

Projectsupportassiststheprojectmanagementindealingwithorganizationalandadministrative
matters. The role is also referred to as project office (PO).

Responsibility
-

- Responsibility for activities delegated to the role

Competence
-

- Within the scope of the activities delegated to the role, can:
- Request, provide, and prepare information

- Request, provide, and prepare information
- Make arrangements

- Make arrangements

Skills

- Knowledge of the project environment
- In-depth project management knowledge

- In-depth project management knowledge
- Knowledge of the methods and practices to be applied in project support's tasks

- Knowledge of the methods and practices to be applied in project support's tasks
- In-depth knowledge of HERMES, attested to by a certificate

- Adherence to the guidelines agreed with the project management in own sub-project
- Economical and sustainable use of resources in own area

- In-depth knowledge of HERMES, attested to by a certificate
- Business administration knowledge

Description

- Business administration knowledge
- Ability to work in a team, to communicate, and to resolve conflicts

- Good writing skills and ability to create documentation

- Economical and sustainable use of resources in own area
- Management of reporting in own sub-project and comprehensive, regular, and situational

- Ability to work in a team, to communicate, and to resolve conflicts
- Good writing skills and ability to create documentation information to the project management, so that the project management can fulfill the relevant management and communication tasks

- Implementation of steering and management decisions
  **Competence**

- Can access all information relating to own sub-project - Authority to use the resources released for the sub-project

- Sole management responsibility and authority to give instructions in the sub-project, with- out interfering in the sovereignty of the execution organization under the agile approach

- Decision-making power within the scope defined with the project management (within the framework of the project management's powers)
  **Skills**

- Knowledge of the project environment - Knowledge of the core organization's requirements in terms of the project and operation of the application or in terms of application of the project

- In-depth project management knowledge - In-depth knowledge of HERMES, attested to by a certificate

- Knowledge of the methods and practices used in the project

- Knowledge of methods and techniques to assess options and economic efficiency - Decisiveness and assertiveness - Managerial skills

- Communication skills - Adequate writing skills


## 6.4.3 Execution roles

## 6.4.3.1 User representative

**Description**

The user representative represents the users and their interests in the project. The user repre- sentative is responsible for the clear specialist solution requirements agreed with the specialist departments as a stable basis for the implementation and technical success of the solution de- velopment. The user representative is the contact person for both the execution organization andthestakeholders,constitutingabindingcommunicationchannelwithintheprojectorganiza- tion. Theuserrepresentativeisappointedbytheprojectsponsorandismanagedbytheproject management, butisautonomousduringsolutiondevelopmentinspecialistandsolution-specific questions and decisions covered by the execution order. Under the agile approach, the user representative serves as an interface to the execution orga- nization. In such cases, the role holder assumes specialist responsibility by additionally assum- ing the role of product owner, which is well known in agile environments. All detailed tasks and responsibilities within the agile execution organization are defined by the agile method used.

**Responsibility**

- Responsibility for the scope of goods/services and the specialist success of the delivery outcomes
- Establishment of all solution-specific requirements - Responsibility for the solution requirements - Maintainingtransparencyandmakingsolutionrequirementsavailabletoallthoseinvolved in the project
- Contributing the complete specialist requirements and functionality coordinated with the
  182/244 specialist areas and customers; representing stakeholder interests
  - Maximizing the added value of the development work (maximizing the value of the solu-

- Maximizing the added value of the development work (maximizing the value of the solution)
-

- Ensuring the scope of goods/services and the specialist success of the solution
- Involvement of stakeholders in solution development according to the stakeholder list

- Involvement of stakeholders in solution development according to the stakeholder list
- Compliance with ISDP requirements

- Compliance with ISDP requirements
- In the case of agile execution, interface to the execution organization

- In the case of agile execution, interface to the execution organization

Competence

- Can access all required information
- Decision on the characteristics of the solution including the quality requirements covered

- Decision on the characteristics of the solution including the quality requirements covered
by the execution order
-

- Definition of the acceptance criteria
- Collaboration with stakeholders and execution organization

- Collaboration with stakeholders and execution organization
- Participation in defining requirements and concluding SLAs

- Participation in defining requirements and concluding SLAs

Skills

- In-depth knowledge of the specialist area
- Knowledge of project management and of HERMES

- Knowledge of project management and of HERMES
-

- In-depth knowledge of traditional and agile development management
- Knowledgeofthedevelopmentmanagement,design,andspecificationmethodsandprac-

- Knowledgeofthedevelopmentmanagement,design,andspecificationmethodsandpractices
-

- Basic knowledge of business administration
- Knowledge of the project environment

- Knowledge of the project environment
- Knowledgeofthecoreorganization'srequirementsintermsofoperationoftheapplication

- Knowledgeofthecoreorganization'srequirementsintermsofoperationoftheapplication
(e.g. for procurements, financing, controlling, security) or in terms of application of the
delivery outcomes
-

- Ability to establish, formulate, evaluate, and prioritize requirements and prepare change
requests
- Good writing skills

- Good writing skills
- Abstraction and simplification ability

- Abstraction and simplification ability
- Ability to work in a team, to communicate, and to resolve conflicts

- Assertiveness
- Natural authority

| Module | Task | Task responsibility | Outcome | Involved in creation of outcome |
| --- | --- | --- | --- | --- |
| Project foundations | Prepare procurement analysis | User representative | Procurement analysis | User representative, Project management |
| Procurement | Prepare call for tenders | User representative | Tender documentation | User representative, Project management |

- Ability to work in a team, to communicate, and to resolve conflicts
- Visionary thinking

- Visionary thinking
- Assertiveness

Relationships

- Natural authority

* * *

| Module | Task | Task responsibility |
| --- | --- | --- |
|  | Evaluate tenders | User representative |
|  |  |  |
| Organization | Advocate stakeholder interests | User representative |
| Product | Design product concept | User representative |
| Advocate stakeholder interests | User representative |  |
| Prepare solution requirements | User representative |  |
| IT system | Advocate stakeholder interests | User representative |
| Prepare solution requirements | User representative |  |
| Deployment organization | Execute deployment measures | User representative |
| Design deployment concept | User representative |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Evaluation report | User representative, Project management |
|  | Tender report | User representative, Project management |
|  | Stakeholder interests | User representative |
|  | Product concept | User representative,Business analyst |
|  | Stakeholder interests | User representative |
|  | Situation analysis | User representative,Business analyst |
|  | Solution requirements | User representative,Business analyst |
|  | Stakeholder interests | User representative |
|  | Solution requirements | User representative,IT architect,Business analyst |
|  | Situation analysis | User representative,IT architect,Business analyst |
|  | Deployment measures carried out | User representative,Project management,Business analyst |
|  | Project management plan | User representative,Project management |
|  | Realize deployment measures | User representative |
| ISDP | Implement ISDP concept | User representative |
|  |  |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
| Deployment concept | User representative, Project management,Business analyst |  |
| Deployment measures realized | User representative,Project management,Business analyst |  |
| ISDP concept | User representative,Project management,Operations manager,ISDP manager,Developer |  |
| ISDP measures realized | User representative,Project management,Operations manager,ISDP manager,IT architect |  |

Table 22: Tasks for which the user representative is responsible and other roles involved in
creating the outcomes

- Provision of the goods and services agreed with the operator while adhering to the set
deadlines and budgets
- Contribution of the operator's requirements

6.4.3.2 Operations manager

Description

- Contribution of the operator's requirements
- Compliance with the operator's ISDP requirements

- Compliance with the operator's ISDP requirements

* * *

Competence

- Can access all required information
-

- Authority to give instructions to the operator with regard to own specialist areas

Skills

- In-depth knowledge of operation
-

- Knowledgeofthecoreorganization'srequirementsfortheprojectandtheoperationofthe
application (e.g. technical and organizational requirements)
- Ability to develop requirements, specifications, concepts, and operating documentation

- Ability to develop requirements, specifications, concepts, and operating documentation
- Business administration knowledge for assessing options and economic efficiency

- Business administration knowledge for assessing options and economic efficiency
- In-depth knowledge of HERMES, attested to by a certificate

- In-depth knowledge of HERMES, attested to by a certificate
- Good writing skills, e.g. to create operating documentation

- Good writing skills, e.g. to create operating documentation
- Ability to work in a team, to communicate, and to resolve conflicts

- Ability to work in a team, to communicate, and to resolve conflicts
- Management of specialists in own area of responsibility

- Management of specialists in own area of responsibility

Relationships

| Module | Task | Task responsibility |
| --- | --- | --- |
| Tests | Realize test infrastructure | Operations manager |
| IT operation | Realize operation | Operations manager |
|  |  |  |
| Activate operation | Operations manager |  |
| Integrate the system into operation | Operations manager |  |
| Design operating concept | Operations manager |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Test infrastructure realized | Operations manager, User representative, Business analyst, Test manager |
|  | Operating organization realized | Operations manager |
|  | Operating manual | Operations manager |
|  | Operating infrastructure realized | Operations manager |
|  | Operating manual | Operations manager |
|  | Operation activated | Operations manager, Developer |
|  | System integrated | Operations manager, Developer |
|  | Operating manual | Operations manager |
|  | Operating concept | Operations manager, IT architect |

* * *

| Module | Task | Task responsibility | Outcome | Involved in creation of outcome |
| --- | --- | --- | --- | --- |
|  |  |  | Service level agreement | Operations manager, Project sponsor, Project management, User representative |

Table 23: Tasks for which the operations manager is responsible and other roles involved in
creating the outcomes

6.4.3.3 Business analyst

Description

The business analyst, often also referred to as the business organizer, forms the interface betweentheuseranddeveloper/operatorpartnergroups. Thebusinessanalystestablishes,questions, analyzes, and prioritizes user needs and requirements based on business processes and
structures and transforms them into organizational requirements. These are used by the developerandoperatorasabasisforthedesignandoperationoftheproductorsystem. Conversely,
the business analyst takes solution-specific aspects into account in the design of the envisaged
organization.

Responsibility
-

- Establishment of all organizational requirements
- Responsibility for the organizational requirements

- Responsibility for the organizational requirements
- Definition of the business processes and organizational structure

- Definition of the business processes and organizational structure
- Ensuring the involvement of various specialists

- Ensuring the involvement of various specialists

- Can access all required information
- Collaboration with all partner groups

- Collaboration with all partner groups
- Design, implementation, and activation of the organization

- Businessadministrationknowledgeinorganizationaltheoryandforevaluatingoptionsand
economic efficiency
- Ability to establish, formulate, evaluate, and prioritize requirements

- Ability to establish, formulate, evaluate, and prioritize requirements
- Project management knowledge

Skills

- Design, implementation, and activation of the organization

- Project management knowledge
- In-depth knowledge of HERMES, attested to by a certificate

- In-depth knowledge of HERMES, attested to by a certificate
- Ability to work in a team, to communicate, and to resolve conflicts

- Ability to work in a team, to communicate, and to resolve conflicts
- Good writing skills

- Management of specialists in own area of responsibility

- Good writing skills
- Management of specialists in own area of responsibility

* * *

Relationships

| Module | Task | Task responsibility |
| --- | --- | --- |
| Organization | Draw up organization concept | Business analysis |
|  |  |  |
|  |  |  |
|  | Activate organization | Business analysis |
|  | Establish organizational requirements | Business analysis |
|  |  |  |
|  | Implement organization | Business analysis |
|  |  |  |
|  |  |  |

| y | Outcome | Involved in creation of outcome |
| --- | --- | --- |
| yst | Process description | Business analyst, User representative |
|  | Organization concept | Business analyst, User representative |
|  | Business model description | Business analyst, User representative |
|  | Organization description | Business analyst, User representative |
| yst | Organization activated | Business analyst, User representative |
| yst | Situation analysis | Business analyst, User representative |
|  | Organizational requirements | Business analyst, User representative |
| yst | Organization description | Business analyst, User representative |
|  | Process description | Business analyst, User representative |
|  | Organization implemented | Business analyst |

Table 24: Tasks for which the business analyst is responsible and other roles involved in
creating the outcomes

Description

TheroleofdeveloperiscomprehensiveandreferstotheproductdeveloperandtheITdeveloper
in one. The developer realizes the product or system according to the solution requirements
and the preceding concepts. The developer activates the product or system.

* * *

Responsibility
-

- Responsibility for realization of the product or system

Competence

- Can access all required information

Skills

- In-depth knowledge of the special field of product or software development
- In-depth knowledge of the methods and practices used to create solutions

- In-depth knowledge of the methods and practices used to create solutions
- Knowledge of HERMES

- Knowledge of HERMES
-

- Ability to work in a team, to communicate, and to resolve conflicts

Relationships

| Module | Task | Task responsibili |
| --- | --- | --- |
| Project foundations | Carry out prototyping | Developer |
| Product | Activate product | Developer |
| Carry out prototyping | Developer |  |
| Realize product | Developer |  |
|  |  |  |
|  |  |  |
|  |  |  |
| IT system | Carry out prototyping | Developer |
|  |  |  |
| Realize system | Developer |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Prototype documentation | Developer, IT architect |
|  | Prototype realized | Developer, User representative, IT architect |
|  | Product activated | Developer, User representative, Business analyst |
|  | Prototype realized | Developer, User representative |
|  | Prototype documentation | Developer |
|  | Product developed or adapted | Developer, User representative, Business analyst |
|  | Detailed specifications | Developer, User representative, Business analyst |
|  | Product documentation | Developer |
|  | User manual | Developer, User representative |
|  | Prototype realized | Developer, User representative, IT architect |
|  | Prototype documentation | Developer |
|  | User manual | Developer, User representative |

* * *

| Module | Task | Task responsibility |
| --- | --- | --- |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
| Prepare system integration | Developer |  |
|  |  |  |
|  |  |  |
| Activate system | Developer |  |
| IT migration | Conduct migration | Developer |
| Realize migration procedure | Developer |  |
|  |  |  |

| Category | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | System concept | Developer, Operations manager, IT architect, User representative |
|  | Detailed specifications | Developer, User representative, Business analyst, IT architect |
|  | Solution architecture | Developer, Operations manager, IT architect |
|  | System developed or parameterized | Developer, User representative, Business analyst, IT architect |
|  | Detailed specifications | Developer, Business analyst, IT architect |
|  | Integration and installation instructions | Developer, Operations manager |
|  | Solution architecture | Developer, Operations manager, IT architect |
|  | Interfaces realized | Developer, Operations manager |
|  | System activated | Developer, Operations manager, User representative, Business analyst |
|  | Migration carried out | Developer, Operations manager, Business analyst |
|  | Migration procedure realized | Developer, Operations manager |
|  | Detailed specifications | Developer, Business analyst, IT architect |

Table 25: Tasks for which the developer is responsible and other roles involved in creating the
190/244
outcomes

* * *

## 6.4.3.5 Execution organization

**Description** The execution organization is an interdisciplinary role group that applies exclusively during the agile approach in the execution phase. The composition of the role group depends on the type of project, the outcomes to be created, and the development method used. When establish- ing the project organization under the agile approach, the specialist responsibility of the user representative must be taken into account through incorporation of the role in the execution organization. Project management responsibility lies with the project management, which may not, however, interfere with the sovereignty of the execution organization. The execution organization orga- nizes itself. No responsibilities, powers, skills, or relationships are therefore defined for the execution orga- nization.

**Responsibility**

- is defined by the agile execution method used
  **Competence**

- is defined by the agile execution method used
  **Skills**

- is defined by the agile execution method used


## 6.4.3.6 ISDP manager

**Description** The ISDP manager is responsible for the aspects of information security and data protection in the project.

**Responsibility**

- Assurance that the information security requirements and data protection measures are taken into account and implemented in the project

- Promotion of understanding/awareness of ISDP in the project
  **Competence**

- Can access all required project information - Issuing of security-related specifications for dealing with data and information during


## project execution

**Skills**

- In-depth knowledge of the special field of ISDP
- Knowledge of the legal basis and the requirements of the core organization
- Knowledge of IT standards, architectures, methods, and practices
- In-depth knowledge of the methods and practices to be applied in own field of activities
- Business administration knowledge for evaluating options and economic efficiency - Process management knowledge
- In-depth knowledge of HERMES, preferably attested to by a certificate
- Ability to work in a team, to communicate, and to resolve conflicts
- Good writing skills, e.g. to create reports
  191/244

* * *

Relationships

| Module | Task | Task responsibility |
| --- | --- | --- |
| Project foundations | Analyze protection needs | ISDP manage |
| ISDP | Design ISDP concept | ISDP manage |
|  | Transfer ISDP concept | ISDP manage |
|  |  |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
| User | Protection needs analysis | ISDP manager, Project management |
| User | ISDP concept | ISDP manager, Operations manager, IT architect |
| User | ISDP concept | ISDP manager, Project sponsor, Project management, User representative, Operations manager, IT architect |
|  | ISDP concept transferred | ISDP manager, Project management, User representative, Operations manager |

Table 26: Tasks for which the ISDP manager is responsible and other roles involved in
creating the outcomes

6.4.3.7 IT architect

Description

The IT architect designs the solution architecture of the system to be created. The IT architect
defines the solution components of the system and their interfaces with the peripheral systems.

- Assurance of compliance with the existing standards and architecture requirements and
performance of audits

Responsibility
-

- Authority to give instructions in the in the architecture context
- Decision-making power regarding the solution architecture

- Decision-making power regarding the solution architecture

* * *

Skills

- Knowledge of the specialist area
-

- In-depth knowledge of the special field of IT architecture
- In-depth knowledge of IT standards, architectures, methods, and practices

- In-depth knowledge of IT standards, architectures, methods, and practices
- Business administration knowledge for evaluating options and economic efficiency

- Business administration knowledge for evaluating options and economic efficiency
- Project management knowledge

- Project management knowledge
- Knowledge of HERMES

- Knowledge of HERMES
-

- Ability to work in a team, to communicate, and to resolve conflicts
- Very good writing skills, e.g. to create solution architecture documentation

- Very good writing skills, e.g. to create solution architecture documentation

| Module | Task | Task responsibility |
| --- | --- | --- |
| IT system | Design integration concept | IT architect |
|  | Prepare solution architecture | IT architect |
|  |  |  |
| IT migration | Design migration concept | IT architect |
|  | Decommission the legacy system | IT architect |

| Category | Outcome | Involved in creation of outcome |
| --- | --- | --- |
|  | Integration concept | IT architect, Operations manager, Business analyst, Developer |
|  | System concept | IT architect, Business analyst, User representative, Developer |
|  | Solution architecture | IT architect, Operations manager, Developer |
|  | Migration concept | IT architect, Business analyst, Developer |
|  | Legacy system removed | IT architect, Project management, Operations manager, Business analyst |

6.4.3.8 Tester

Description

Table 27: Tasks for which the IT architect is responsible and other roles involved in creating
the outcomes

The tester participates in the creation of test case descriptions, carries out tests, and assesses
and logs the outcomes.

* * *

**Responsibility**

- Support for the test manager in the creation of test case descriptions

- Performance of tests for one or more test objects

- Evaluation and recording of the test results in the form of test reports
  **Competence**

- Can access all required information - Decision-making power to classify the test results according to the defect categories de- fined in the test plan
  **Skills**

- In-depth knowledge of the specialist area (specialist processes, organizational require- ments, solution requirements, etc., in own test area)

- Knowledge of testing and test methods - Quick comprehension and thorough working methods - Assertiveness

- Ability to work in a team, to communicate, and to resolve conflicts


## 6.4.3.9 Test manager

**Description** The test manager designs, plans, and coordinates testing. The test manager ensures that the test fundamentals are developed in the form of the test concept and transfers testing to the subsequent operation. **Responsibility**

- Assurancethatthevariousrequirementssuchasorganizationalrequirementsandsolution requirements regarding the quality of the system are met
  **Competence**

- Defines the test methods and test organization - Determinesemployeeandsystemdeploymentfortestingandordersteststobeconducted
  **Skills**

- Knowledge of the specialist area - In-depth knowledge of the test objects (specialist processes, technology, etc.)

- In-depth knowledge of the special field of quality assurance and testing with the corre- sponding methods and practices

- Knowledge of the design and implementation of IT solutions - Knowledge of project management

- In-depth knowledge of change management - Knowledge of HERMES, ideally attested to by a certificate - Decisiveness and assertiveness

- Ability to work in a team, to communicate, and to resolve conflicts

- Good writing skills, e.g. to create test concepts and test reports
  194/244


* * *

Relationships

| Module | Task | Task responsibility |
| --- | --- | --- |
| Tests | Transfer test infrastructure | Test manage |
|  |  |  |
|  | Design test concept | Test manage |
|  | Conduct test | Test manage |
|  |  |  |

| Activity | Outcome | Involved in creation of outcome |
| --- | --- | --- |
| - | Test concept | Test manager, Project management |
| - | Minutes | Test manager, Project management |
| - | Test infrastructure transferred | Test manager, Project management |
| - | Test concept | Test manager, Tester, User representative, Operations manager, Business analyst, Developer |
| - | Test concept | Test manager, Tester, User representative, Operations manager, Business analyst, Developer |
| - | Test report | Test manager, Tester |

Table 28: Tasks for which the test manager is responsible and other roles involved in creating
the outcome

* * *

7 User information

7.1 Introduction

This section assists in the proper use of HERMES project management. To support users,
this section contains information that allows for a deeper understanding of HERMES, explains
application cases, provides guidelines of sorts for specific cases, and so on.

7.2 Information overview

The user information for HERMES is divided into two categories:

1. Explanations
   The explanations on HERMES show how specific topics are integrated into HERMES.

The explanations on HERMES show how specific topics are integrated into HERMES.
They illustrate interrelationships and enable a deeper understanding of methods.
2\. Notes on application cases

2. Notes on application cases
   The notes on application cases show how HERMES should be implemented in specific

The notes on application cases show how HERMES should be implemented in specific
situations. They ensure safe application and help to reduce the scope for interpretation.

The table shows the information per category.

| Category | Information |
| --- | --- |
| Explanations | Governance |
| Sustainability |  |
| Project management and development management |  |
| Financial steering and management |  |
| Notes on application cases | Planning |
| Implementation units under traditional approach |  |
| Application with other methods and practices |  |
| Integration of HERMES into the core organization |  |

Table 29: User information per category

7.3 Explanation regarding the information description

The description of information does not follow a fixed or uniform structure. Each note is structured according to needs and forms an independent topic unit.

* * *

## 7.4 Description of information

### 7.4.1 Governance

### 7.4.1.1 Project governance

Governanceisgenerallyunderstoodtomean"responsiblecorporatemanagementandcontrol". It must be implemented in particular by the management of the core organization. Project governance is part of corporate governance. The following characteristics of good project governance represent requirements for project steering and project management:

- Effective and functional project planning, project steering, and project management - Constructive cooperation between project organization and core organization
- Consideration of stakeholder interests - Alignment of the set objectives with requirements of the core organization
- Solid basis for correct, efficient, and transparent decisions - Institutionalized and timely flow of information, transparency in project communication
- Comprehensibility of project implementation and any changes of objectives - Appropriate approach to risks
- Functional and adequate project organization and infrastructure - Efficient and sustainable use of resources
  HERMES project management is designed to ensure good project governance.

### Implementation of significant changes

### Creation of the solution

In the implementation of corporate planning supported by HERMES project management, sig- nificant changes are realized by means of projects. During the initiation phase, more depth is provided for the business planning outlines. At the end of the phase, an execution order is drawn up so that the project sponsor, in coordination with the core organization, can decide whether to approve continuation of the project and how to approach solution development. The core organization appoints and fills the decisive roles of the project from its own ranks or from the user partner group: first the project sponsor and then, through the project sponsor, the project management, and the user representative. The executive board and the controlling and compliance bodies are involved in the project through decision-making tasks and reporting. The project sponsor is responsible for continuous communication between the core and project organization; the project management is responsible for identifying and possibly for gaining stakeholders for the project and informing them; and the user representative is responsible for involving them in project execution. Within the project, the project sponsor is the highest decision-making authority. _**Utilization of the solution**_ Utilization

- ofthecreated product or service beginswithactivationoftheproductandtheorganization, - of the created system with the activation of the operation, and
- of the created organization with the activation of the organization.
  Theprerequisitesforsustainableutilizationarecreatedintheproject. Theprojectisclosedonce the operation is stable, the solution has been accepted, and all necessary final tasks have been performed. During the transition from project to application organization, it is ensured that the roles required for utilization are assigned. These often include the roles of user representative andoperationsmanager. Theprojectistransformedintotheapplication. Ifthecoreorganization maintains the same portfolio for both projects and applications, as indeed is envisaged in the 197/244

* * *

HERMES portfolio management, only the status changes from project to application. However, it should be taken into account that the project and the application overlap in the portfolio. This is particularly the case in the development of agile solutions. The executive board of the user and that of the developer or operator remain in contact also during the utilization period. The check to see whether the originally set objectives have been achieved is carried out during the utilization stage.

## Comprehensibility of the selected approach

Responsible project execution also involves choosing the appropriate approach. The decision as to whether the project approach is traditional or agile must be made at the project level, given that each project has its own characteristics. This also applies to projects within a pro- gram. Even several IT projects that are being handled in parallel may have different framework conditions that require different approaches. Different methods and techniques can be used for the choice of approach. The requirements of controlling and compliance bodies must be met. The choice of approach must be comprehen- sible.

## Self-determination of users over the project

In some cases, it has become customary for the service providers or the partner groups of developers or operators to have a significant influence on the project, even to the extent of dominating them. Firstly, this contradicts the understanding of roles and partners in HERMES. Secondly, the users cannot fully assume their responsibility in the project and are accordingly unable to protect their interests. The core organization/user partner group-as the owner of the project and user of the solution

- provides the financial resources for the project. This gives it the right to decide freely and without limitation by the other partner groups on the project structure, the management method applied, as well as the approach, and to fill the minimum number of roles with its own staff or staff employed by them. However, it must also make use of these rights and consistently assert them/itself. This in turn is part of its obligation. With respect to the self-determination of users over the project, the following project roles are especially relevant:
- Project sponsor - Defines the framework for project initiation and for solution development.
- Determines the assignment of roles, especially the user partner group. - Decides on the type of development approach.
- Asserts the interests of the project sponsor's core organization. - Project management - Prepares the steering decisions.
- Safeguards the interests of the core organization. - Manages the roles of all partner groups.
- Enforces the selected approach. - Ensures reporting. - User representative
- Prepares the steering and management decisions. - Evaluates options in the interest of the core organization.
- Supports the project management in safeguarding the interests of the core organiza- tion and in reporting.
  In the core organization, the following role groups in particular deal with self-determination:

198/244

* * *

- Controlling and compliance bodies - Evaluate compliance with the requirements with respect to the approach set out in the execution order.
- Executive board - Checks whether the core organization's requirements and objectives with respect to

## the project are being met.

## Integration into the portfolio

The figure below shows a possible subordination of the portfolio within the core organization. The project portfolio is often located

- in the project management competence center or - in the controlling and compliance bodies.
  As a rule, however, responsibility lies with the executive board. The governance requirement concerning efficient and sustainable use of resources means that an assessment is carried out to ascertain whether a project should be initiated and its execution shouldlaterbereleased. Onetaskofthecoreorganizationistosteerandcontrolalloftheorga- nization's projects on an overarching basis. This is done with project portfolio management. It includestheoverarchingprioritizationandcoordinationofprojects,theallocationofresourcesto projects, and decisions on which projects are initiated, executed, halted, and terminated. From the company's perspective, it is advantageous to merge the project portfolio and the application portfolio into a superordinate product portfolio. **Core organization** Project management Controlling and Executive board competence center compliance bodies

a) or b)

## Project portfolio

Project portfolio Project 1 Initiation Concept Implementation Deployment Closure Project 2Initiation Execution Closure Project 3 Initiation Execution Closure Project 4 Initiation Concept Implementation Deployment Closure Project 5 Initiation Execution Closure Project nInitiation Concept Implementation Deployment Closure

Figure 28: Two common ways to assign the portfolio in organizational terms

One of the ways in which HERMES supports the integration of projects-and of applications-into portfolio management is with the phase model (consistent project structure), phases and releases, milestones, and reporting.

199/244

* * *

7.4.1.2 Reporting

The project governance requirement concerning transparent communication necessitates reporting. Reporting also supports the project governance requirement concerning traceability
and comprehensibility of the project. Reporting is carried out periodically along the phases
according to the requirements of the core organization.

Reporting formally regulates the flow of information within the project organization and vis-à-vis
the core organization. Timely reporting is a prerequisite to enable the competent bodies in the
project organization and core organization to carry out their tasks responsibly.

The transparency achieved with reporting is of benefit not only for the core organization and the
project sponsor, but also for the project manager, given that it documents the quality of project
execution:
-

- Project status report
Project status reports are prepared periodically from the beginning of a project until its

Project status reports are prepared periodically from the beginning of a project until its
closure. In time frames defined by the core organization, the project manager uses the
project status report to inform the project sponsor and the core organization about the
project status (plan/actual comparison) and the expected next steps (forecast).
- Phase report

- Phase report
At the end of the concept, implementation, deployment, and execution phases, the phase

At the end of the concept, implementation, deployment, and execution phases, the phase
outcomes and the planning of the further course of the project are prepared for the project
sponsor in such a way that the project sponsor can decide on how to proceed (usually on
phase release).
- Release report (agile)

- Release report (agile)
During the execution phase, the outcomes of the release are prepared for the project

During the execution phase, the outcomes of the release are prepared for the project
sponsor at the end of each release in such a way that the sponsor is informed about the
success of the release as well as progress and overall development. If it was determined
in the initiation phase that decisions on release must be made, the release report serves
as a decision-making tool.
- Final project evaluation

- Final project evaluation

At the end of the closure phase, the final project evaluation is created. It provides the
basis for continual improvement in the core organization based on the lessons learned.

Asthefigurebelowshows,reportingstaysuniformwithintheprojectorganizationandinrelation
to the core organization, regardless of which development approach is selected. This ensures
that governance is maintained in reporting for both the traditional and the agile development
approach.

* * *

Figure 29: Encapsulated reporting structure that is uniform in relation to the core organization

Supplementingreporting,definedspecialistoutcomesareforwardedtothecontrollingandcompliance bodies for review (e.g. solution architecture).

Meeting the project governance requirements

Review subject matter

When assessing a project, one of the checks is whether the project meets the requirements for
good project governance.

The following list describes for each requirement how the individual HERMES method components support the meeting of the requirements.

Effective project steering and management
-

- Roles
Roles are a key method component for meeting the requirements for effective project

Roles are a key method component for meeting the requirements for effective project
steering and management:
- Responsibility for tasks and outcomes is assigned to the defined roles in the project.

- In the traditional approach, a role group of technical committee is defined to support
the role of the project management. This enables the stakeholders to be included in
the project organization both in the management area and at the technical level.
- Theprojectorganizationsectiondescribeswhichaspectsaretobetakenintoaccount

- Responsibility for tasks and outcomes is assigned to the defined roles in the project.
- The roles are assigned to the hierarchy levels of steering, management, and execu-

- Theprojectorganizationsectiondescribeswhichaspectsaretobetakenintoaccount
when assigning roles in order to ensure effective project steering and management.

* * *

- Modules and tasks The steering and management tasks are described in detail. They are grouped in the project steering and project management modules and are therefore clearly visible for the project sponsor, project management, and other project participants.
  This ensures a high degree of transparency with regard to tasks and outcomes for which the project sponsor and project management are responsible.

- Outcomes Every project has certain outcomes-the minimum required documents-that have to be achieved to enable it to be steered and managed. These include the execution order and the project management plan, for example. The minimum required documents from a governance perspective are defined in the outcomes section.

- Reporting Project steering requires reliable information on planning, project status, and forecasts. These are provided via reporting.


## Consideration of stakeholder interests

- Roles The roles of project steering (project sponsor), project management, and specialist solu- tion development (user representative) are responsible for their respective tasks.
- Tasks - The manage and inform stakeholders task ensures that stakeholders are identified and their interests are analyzed.
- The advocate stakeholder interests task ensures that stakeholders can contribute their ideas and demands to the project and are involved in the solution development as needed.
- Outcomes The stakeholder list and stakeholder interests are first established in the initiation phase and are continuously pursued over the course of the project.

## Cooperation between the project organization and core organization

- HERMES and portfolio management HERMES supports the integration of projects into portfolio management.
- Phases and milestones The phases and milestones (with quality gates) support cooperation (e.g. with regard to clear interfaces).
- Roles The role model establishes a clear link between the project organization and the core organization with its controlling and compliance bodies.
- Tasks Severaltaskssupportcooperationbetweentheprojectorganizationandcoreorganization. For example:
- the decision-making tasks for project initiation release, execution release, phase re- lease, release, and project closure;
- the agree on and steer goods/services task; - the decide on solution architecture task;
- the decide on ISDP concept task.
  202/244

* * *

## Alignment of the set objectives with requirements of the core organization

- Phases/releases Before the execution release at the end of the initiation phase and the respective release or phase release, the objectives are aligned with the strategies and objectives of the core organization within the framework of the relevant decision-making tasks.

## Transparency in project communication

- Tasks Communication planning is created with the manage and inform stakeholders task. Com- munication is target-group-oriented.
- Reporting Reporting ensures project-internal communication between the project management and the project sponsor, and also provides a realistic and timely overview and holistic evalua- tion for the core organization.

## Comprehensibility of the course of the project

- Outcomes The outcomes achieved as the project progresses document the course of the project.
- Periodic reporting, which includes the project status report and the phase report, documents the progress of the project.
- Project decisions are recorded and minutes are taken of meetings. - The lessons learned are continuously recorded.
- the final project evaluation, planned and actual comparisons are carried out (tar- get/actual comparison), and key findings are recorded.
- Theprojectmanagementplaniscontinuouslyupdatedanddocumentstherespective planning status.
- Procurements are documented with an evaluation report. - Changes are managed and recorded in the change status list.

## Appropriate approach to risks

- Outcomes The project status report contains the current risk assessment and informs the recipients about the project management's assessment.
- Tasks Risk management is continuously managed with the manage risks task.
- Roles At the project steering hierarchy level, the role of quality and risk manager supports the project sponsor with an independent assessment of the project.
- Phases/releases If, attheendofaphaseorrelease, therisksaredeemedunacceptable, adecisiononnext steps must be made, and the project may have to be terminated.
- Modules and scenarios Modules and scenarios support all project participants and the core organization with a common understanding of how a project with a specific characteristic is handled. In this way, misunderstandings can be prevented and project risks can be reduced overall.
  203/244

* * *

## Efficient and sustainable use of resources

- Modules and scenarios Modules and scenarios enable efficient project planning.
- Initiation phase Attheendoftheinitiationphase,acheckiscarriedouttoseewhetheritiswisetocontinue the project by means of an execution order. Possible reasons for not doing so are lack of economicefficiency,excessiverisks,infeasibility,andlackofalignmentwiththeobjectives and strategies of the organization.
- Phases, releases, and milestones At the end of the phases or at the end of the release, a check is carried out within the framework of solution development to see whether it is wise to continue the project. Pos- siblereasonsfordiscontinuationincludeexcessiverisks,lackofbenefits,escalatingcosts, etc.
- User information The sustainability section describes how projects are implemented sustainably, how sus- tainable outcomes are achieved and which criteria are used to assess sustainability.

## 7.4.2 Sustainability

## 7.4.2.1 Understanding of sustainability

The foundation of sustainability is the sustainability concept of the World Commission on En- vironment and Development (Brundtland Commission). This defines that sustainable devel- opment should satisfy the needs of the present, but must not endanger the needs of future generations. To accomplish this, economic, social, and ecological processes must be brought into harmony with each other. Sustainable development strives to achieve a balanced and sus- tainable relationship between nature and its capacity to renew itself and the demands placed on it by the population. The implications of today's actions for the future must accordingly be taken into account. For example, the consumption of the environment and resources must be reduced to a sustainable level for the long term while maintaining economic capacity and social cohesion. All these sustainabilityrequirementsalsoaffecttheprojects. Whendefiningtheobjectivestobeachieved, the project must not be limited to economic efficiency alone, but must also include society and the environment. In this respect, successful project management also has a positive impact on sustainable development. From a sustainability and life-cycle perspective in the area of information and communication technologies, the focus is primarily on energy and resource efficiency as well as working condi- tions in producing countries. Special attention is paid to procurement by defining ecological and socialawardcriteria. Forinformationtechnologies,animportantroleisalsoplayedbylong-term data security, data protection, data integrity, and access to knowledge.

## 7.4.2.2 Sustainability with HERMES

## HERMES as a complete project

HERMES supports the sustainability of the solution. The method components are described with regard to sustainability aspects below.

204/244

* * *

**Phases** It is important to enshrine sustainability objectives when defining strategic objectives. These are included in the project as a requirement during the initiation phase.

- For the project sponsor, one of the decision-making criteria for the execution release is whether and how the project meets the sustainability requirements and objectives. As a result, unsustainable projects are not even released for continuation.

- Inadditiontocompliancewiththerequirementsandalignmentwiththestrategicobjectives, theachievementofthesustainabilityobjectivesisalsotakenintoaccountasanevaluation criterion for each decision on release or phase release.
  **Outcomes** All outcomes required for sustainable operation are developed in the project. These include the organization with its processes, as well as the outcomes for maintenance and further develop- ment, including the user manual, operating manual, product concept, solution architecture, and detailed specifications. The test infrastructure and test tools are transferred from the project to the core organization for further development after project closure. The following outcomes support sustainability in decision-making:

- Study Evaluation criteria for the decision on next steps (choice of solution option)

- Tender documentation (specifications) List of criteria for evaluating the solution and tenderers

- Checklists Review points and criteria in the decision-making process
  **Tasks** Several tasks specifically support sustainability in the project, for example:

- Decision-making tasks such as: - Decisions on execution release, phase release, release, and project closure;

- Decision on next steps; - Decision on solution architecture; - Agree on and steer goods/services task;

- Manage and inform stakeholders task; - Prepare procurement analysis task; - Procurement module tasks.
  **Modules** In the procurement module, the sustainability objectives and requirements are included in the list of criteria for the procurement of services and products and are included in the evaluation.


**Roles** Withtheirpowersandresponsibility,rolescanpromoteaconsciousapproachtoresources. The understanding needed for this is created already when defining the objectives. Accordingly, all roles and their tasks are decisive for the project's sustainability. The following three roles are particularly relevant with regard to sustainability objectives:

- Project sponsor - Defines the objectives in line with the strategy and sustainability requirements.
- Prioritizes the solution objectives, resolves conflicts between objectives, and incor- porates them into solution requirements and organizational requirements.
  205/244

* * *

- Regularly checks the implementation of requirements and the achievement of objec- tives.

- Ensures the involvement of stakeholders and their requirements. - Ensures the long-term resources needed for operation. - Project management

- Enshrines sustainability awareness in the project. - Considers sustainability criteria when making decisions.

- Ensures the careful use of resources.

- When assigning roles, ensures that specialists have the skills needed to fill the roles and closes any skills gaps (in the agile approach, this falls within the powers of the execution organiszation).

- User representative - Integrates the sustainability objectives into the solution requirements and prioritizes them.

- Anchors sustainability awareness in solution development. - Understands the value creation of development work to include sustainability.

- Considers the interests of stakeholders. - Supports the project sponsor in defining sustainability objectives.

- Incorporates sustainability into the procurement process. - Ensures that sustainability aspects are factored in when defining requirements.

- Sees to a value-oriented prioritization of requirements. - The sustainability objectives are included in the evaluation of the requirements.

- Evaluates options also from a sustainability perspective.
  In the project organization, the following execution roles in particular are concerned with sus- tainability:

- Business analyst - Determines the sustainability requirements of the core organization.

- Integrates the sustainability objectives into the organizational requirements. - Considers the sustainability aspects when drawing up the organization concept.

- Accompanies the user representative in the formulation of the sustainability objec- tives.

- Operations manager - Considers sustainability aspects when defining the operation-related requirements.

- Considers sustainability aspects when designing the operating concept. - Ensures sustainable operation.
  In the core organization, the following role groups in particular deal with sustainability:

- Controlling and compliance bodies - Assess compliance with the requirements and the achievement of the sustainability objectives.

- Check the product concept. - Check the solution architecture. - Homogeneousarchitectures shouldmakeitpossibleto ensurethelong-termop- eration and further development of systems.

- Executive board - Prioritizes the projects in the portfolio also using criteria that take sustainability into account.

- Checks whether the sustainability requirements and objectives can be realistically achieved with the project.
  206/244


* * *

7.4.3 Project management and development management

7.4.3.1 Project management

As the figure below shows, HERMES distinguishes between traditional project management
and project management with agile execution.

Figure 30: HERMES offers traditional and hybrid project management

The solution development can be traditional or agile:
-

- Traditional product management supports traditional development management;
- Project management with agile execution supports agile development management.

- Project management with agile execution supports agile development management.

7.4.3.2 Agile development management

Agile developmentmethodsarenotprojectmanagementmethods,butratherdevelopmentmanagement methods. Projects under HERMES must fulfill certain framework conditions, such as
compliance with governance, the smooth embedding of the project in the existing planning and
controllingprocessesofthecoreorganization(fundamentalmissionofHERMES),andcommon
language/uniform terminology. Agile developments without a corresponding project management framework do not fulfill these requirements. Agile methods and frameworks are therefore
embedded in HERMES project management.

The figure below shows the HERMES phase model with agile development management.

Figure 31: Phase model with agile development

The understanding of roles in project management with agile development is based on both
traditionalprojectmanagementandagiledevelopmentmethods. Theprojectorganizationworks
accordingtotraditionalprojectmanagement,theexecutionorganizationaccordingtothechosen
agile method. The user representative acts as an interface between the project and execution
organization.

Further information on HERMES and agility can be found in the document "Agiler Leitfaden -
Projektmanagement" (in German), which is an extension to this reference manual.

The solution development in the project can be either traditional or agile. In practice, however,
there are cases in which a project is undertaken with a combination of both approaches.

This requires appropriate tailoring in the initiation phase, as the selected scenario and the execution structure plan must be adapted. The figure below shows two examples of such combinations.

Figure 32: Traditional/agile development management - example options

7.4.3.3 Traditional/agile development management

* * *

## 7.4.4 Financial steering and management

## 7.4.4.1 General

The project's financial steering and management starts with the decision on project initiation releaseandendswiththedecisiononprojectclosure,insomecaseswiththedecisiononproject discontinuation.

## 7.4.4.2 Funding

Astheowneroftheproject,thecoreorganizationprovidesthefinancialresourcesfortheproject. The initiation phase constitutes preliminary goods/services for the entire project, financed using the project budget or line budget. The outlay for the initiation phase is included as preliminary goods/services in the project's economic efficiency considerations. The planning of resource requirements and financing is carried out for the entire project. A master plan is created in the initiation phase, and this is continuously checked and adjusted. In the traditional approach, the binding investment and operating costs must be known at the end of the concept phase. These also factor in the costs of covering project risks. In the agile approach, key figures for operating costs are fleshed out successively from release to release and reported on a release-by-release basis. The expected investment costs or the total budget for the solution development, plus the costs for the closure phase, are in principle defined as fixed in the execution order. The operating costs are financed using the project budget during project execution and then using the line budget.

## 7.4.4.3 Steering

With the decision on execution release, the investment budget required for execution is ap- proved by the core organization. The project sponsor assumes responsibility for this and, in the traditional approach, releases the financial resources in phases. This release is steered by means of the phase release decision-making tasks. In the agile approach, there is no need for a successive release of finances. These are fixed for the solution development or defined as a cost ceiling and are released once with the execution order. Within the framework of agile development, the estimated remaining outlay is compared with the actual remaining outlay by means of a burndown chart and communicated by means of a release report. The project sponsor is responsible for financial steering and ensures the economic efficiency of the project. The project sponsor accordingly steers the project costs and the future operating costs. Reporting provides all the information the project sponsor needs to assess the project status and cost developments. Given that the budget is fixed in the agile environment, financial control and project success are measured and ensured by other instruments. If necessary, the project sponsor appoints an independent quality and risk manager for steering support. Theprojectmanagementisresponsibleforthefinancialmanagementoftheproject. Theproject management takes care of project accounting and prepares the information for steering. Through the manage changes task, the project management ensures that changes in require- ments and scope, as well as their impact on costs, personnel requirements, and deadlines, are identified, analyzed, requested, and decided in a timely manner. Planning is adjusted accord- ingly.

208/244

* * *

## 7.4.5 Planning

## 7.4.5.1 Planning basis and procedure

Planning forms the basis for the efficient and effective use of resources required in the project. It is the prerequisite for managing and steering the project. It supports communication and the reconciliation of activities among the project participants. After conducting the study with the objectives and the decision on next steps in the initiation phase, the first step in execution planning is execution structuring. The project management selects the appropriate scenario in HERMES online in accordance with the decision on next steps. The scenario with its method components provides a basic structure that is adopted for solution development and adapted to the specific circumstances of the project. The planning outcomes are recorded in the project management plan. It is the key instrument for managing the project and includes all the plans for the project. It is created in the initiation phase and continually updated in subsequent phases. After the decision on execution release, the paths of the traditional and agile approach diverge. In traditional solution development, planning is done by the project management according to the principle of rolling planning; in agile solution development, further planning is done au- tonomously by the execution organization.

## 7.4.5.2 Initial planning of solution development

In the initiation phase, the continuation of the project is planned. The execution structuring is created and the outcomes of the further course of the project are defined on the basis of the study. The human and financial resources are planned only in enough detail to ensure their availability for the entire project. First, the execution structure plan is developed according to the following procedure:

1. Create a study, define scope and boundaries for solution development.
2. In HERMES online:

- Select scenario and adjust if necessary (within the scope of the study). - Create and export execution structure plan.
- Integrate execution structure plan into the project management plan.

3. Supplement solution-specific outcomes and tasks.
4. Adapt roles in the project management plan to the scenario.
   Theprojectmanagementplanisthendrawnupwiththefollowingsteps-theydonotnecessarily have to be carried out in this order and can be taken more than once:

- Define risk management; - Create QA plan and review plan; - Estimate outlay for outcomes;
- Determine interdependencies; - Create a schedule (where applicable, also provide release plan (agile));
- Ensure resources for the duration of the entire project with the agree on and steer goods/services task;
- Factor in qualification and availability of resources when estimating outlay and dura- tion;
- Estimate the duration of the tasks; - Plan the use of resources; - Create a communication plan;
- Create a cost plan; - Check project management plan with QA measure;
- Coordinate the project management plan with stakeholders and verify it as a basis for the execution order.
  209/244

* * *

## 7.4.5.3 Planning in traditional solution development

## From rough to detailed

The distinction according to phases and the fleshing out and extension of the procedure com- ponent "from rough to detailed" comes from systems engineering and is one of the foundations of the traditional phased approach of HERMES. In traditional solution development, planning, steering, and management are based on the principle of rolling planning. Towards the end of the concept and implementation phases, the next phase is planned in detail before the decision on phase release is made, and the rough planning is reviewed.

## Detailed planning for the next phase

The following activities are carried out:

- Review the execution structure plan and complete tasks and outcomes; - Flesh out tasks and outcomes;
- Define work packages for the next phase and specify persons responsible for each work package;
- Flesh out the work package activities and outcomes; - Verify outlay estimates based on work packages;
- Flesh out resource planning; - Flesh out the phase schedule; - Create decision plan;
- Flesh out review plan; - Flesh out communication plan; - Update the risk list and measures;
- Verify the overall plan; - Check project management plan with QA measure;
- Coordinate the project management plan with stakeholders.

## Planning and steering with work packages

The detailed planning of a traditional phase is based on work packages. They are the prereq- uisite for controlling and steering the project. The following notes apply for work packages:

- Several work packages can be created from one task.
- One or more outcomes result from a work package. These are achieved in activities. When creating a work package order, the described activities are further refined.
- Upon completion of the work package, the outcomes have been subjected to the QA measures defined in the review plan or test concept and have been accepted.
- A person is assigned responsibility for a work package. Several people can collaborate within a work package.
- A work package typically lasts between two and six weeks.

## Planning accuracy over the course of the project

At the beginning of the project, the knowledge about a potential solution is by no means zero. Already at the beginning of the initiation phase, planning is possible with only a low degree of accuracy. By proceeding in phases, i.e. from rough to detailed, the outcomes are continuously fleshed out. As a result, knowledge increases, uncertainty is reduced, and planning accuracy increases over the further course of the project. The increasing knowledge (with the level of detail of the outcomes) and planning accuracy are directly related. The planning accuracy to be achieved at a specific point in time determines the level of detail at which the outcomes are to be prepared. The figure below shows how knowledge about the solution increases and how planning inaccu-

210/244 racy decreases over the course of the project.

high

Knowledge about the solution

Planning inaccuracy

low Time Initiation Concept Implementation Deployment Closure

Figure 33: Increasing knowledge/decreasing planning inaccuracy

HERMES cannot specify how detailed planning should be at a specific point in time, given that thisishighlydependentonthesituationandonthecharacteristicsandcomplexityoftheproject. This should instead be specified by the project sponsor and the controlling and compliance bodies of the core organization. Estimatesshouldgenerallyindicateplanningaccuracydetails, andreservesshouldbeincluded intheexecutionorderandprojectmanagementplanonthatbasis. Forthispurpose,theestimate assumptions must be documented in order to meet the governance requirement concerning transparent communication.

## 7.4.5.4 Planning in agile solution development

In agile solution development, other mechanisms come into play; the aspect from rough to detailedtakesplacewithintheframeworkofiterativeprocessingandiscarriedoutautonomously by the execution organization at the hierarchy level of execution. Agile release planning is linked to the schedule in the project management plan. On the project side, planning at the management level is limited to coordinating aspects and is activated again only in the closure phase.

## 7.4.6 Implementation units under traditional approach

If the traditional solution development of an IT project becomes so complex that the implemen- tation of the whole scope seems questionable, or if initial outcomes for use are to be delivered as quickly as possible, the implementation and deployment phases can be broken down into several implementation units. ThetraditionalapproachofHERMESprojectmanagementenablesbothsequentialandoverlap- ping in time or parallel development in implementation units. The release of the first implemen- tation unit is the implementation phase release, which requires regular closure of the concept phase. Each implementation unit covers the two phases of implementation and deployment. An implementation unit comprises all technical and organizational outcomes of the project that are required for deployment of the system or a part of it. At the end of an implementation unit, the product or system is used productively. The figure below schematically shows the overlap in time between implementation units as

211/244 independent control units, each with an implementation and deployment phase. Closure phase Implementation unit 1 release Initiation Concept Implementation Deployment

Implementation unit 2 Implementation Deployment

Implementation unit 3 Implementation Deployment implementation units Release of start of Implementation unit n Implementation Deployment Closure

Implementation units Project start Solution development Project end Project duration

Figure 34: Implementation units overlapping in time using traditional approach

The following points need to be observed with respect to implementation units:

- The initiation and concept phases are completed. Implementation units can be started after the concept phase. After that point, the project takes place in the phases and mile- stones of the respective implementation unit. There is no superordinate phase model.
- Although the number of implementation units is not limited by HERMES, the duration of the project should not be unlimited. For this reason, the implementation units are planned as a whole in the concept phase.
- Each implementation unit covers the implementation and deployment phases. Each im- plementation unit goes through the decision-making tasks of steering and management.
- The start of an implementation unit must be released by project steering. This requires an updated project management plan.
- From a controlling perspective, implementation units are planned and controlled sepa- rately in terms of costs, deadlines, and outcomes. They form independent control units. Accordingly, reporting should be geared to the implementation units.
- Itmakessenseforafinalevaluationoftheimplementationunittobecarriedoutattheend of every implementation unit and the lessons learnt to be documented and used.
  Provided that each implementation unit could be finished with a formal phase closure, at the end of the last implementation unit a decision is made on effective release of the next closure phase. Intheclosurephase,thecorrespondingtasksarecarriedoutandoutcomesarecreated. This includes the final project evaluation of all implementation units.

## 7.4.7 Application with other methods and practices

HERMES defines the outcomes and the general course of the project. However, it does not prescribe which methods and practices must be used to produce the outcomes. HERMES is thus supplemented by subject-specific methods and practices over the course of theproject(seethefigurebelow). Users,developers,andoperatorsdefinetheseandcoordinate them with the tasks, outcomes, and roles according to HERMES.

212/244

* * *

Concept Implementation Deployment Initiation Closure Execution

User methods/practices (e.g. BPMN or INTERLIS)

Developer methods/practices (e.g. SCRUM)

Operator methods/practices (e.g. ITIL)

Figure 35: Use of supplementary methods and practices

For the participants, especially in the context of solution development, this gives rise to new dimensions that universalize the applicability and usability of HERMES and still fully accom- modate the individual method protagonists. For example, the user can specify that they will use an open source tool for conceptual data modeling, or the developer can employ the agile developmentmethodfavoredinthedeveloper'scoreorganizationforthedevelopmentprocess. The following points must be observed when supplementary methods and practices are used:

- The tasks, outcomes, and roles of project steering and project management are always based on HERMES and cannot be replaced by other methods.
- The HERMES phase model remains in place. - The milestones are set and cannot be changed.
- Specifications on the use of methods and practices are recorded in the project manage- ment plan.

## 7.4.8 Integration of HERMES into the core organization

## 7.4.8.1 General

Since each core organization has its own specific characteristics, it is often essential and ad- vantageous to adapt the method to its needs to ensure efficient project management. ThefollowingobjectivesarepursuedwiththeintegrationofHERMESintothecoreorganization:

- Specific core organization processes and requirements that HERMES is not aware of are taken into account.
- The project manager, the user representative, and other project participants receive even better support. They have a framework defined specifically for the organization.
- Project management efficiency is increased, given that processes and requirements do not have to be reinvented for every project.
- Quality is increased with the more extensive integration of practices into the method, of othermethods, and of tools. In particular, the widelyused agiledevelopmentmethods are deprived of their project management deficits. Thanks to HERMES, they fully adapt to the organization.
- HERMES training can incorporate organization-specific adaptations and accordingly be more effective. With regard to certification, it is recommended in particular not to change the HERMES terminology excessively.
  213/244

* * *

7.4.8.2 Procedure

HERMES is best integrated into the core organization by way of a project.

The project can be carried out on the basis of the service/product adaptation scenario. In doing
so, the aspects of the deployment organization are also taken into account in training, and the
organization with the processes for operation and further development of project management
are created and activated.

The adaptation is made by the project management competence center.

7.4.8.3 Adapting the method

Integration of important elements into the method

The core organization's requirements are integrated into the method, e.g.
-

- Requirements arising from organization-specific processes
- Decision-making process traditional/agile, necessary information for decision-making

- Requirements of other decision-making processes
- Reporting requirements (project status report, phase report, release report)

- Decision-making process traditional/agile, necessary information for decision-making
- Requirements of other decision-making processes

- Reporting requirements (project status report, phase report, release report)
- Requirements for SLAs, contracts, and agreements

- Requirements for SLAs, contracts, and agreements
- Security and data protection aspects

- Aspects of the solution architecture

- Security and data protection aspects
- Aspects of the solution architecture

Thespecificmethodsandpracticesforproducingoutcomesareintegratedintothemethod, e.g.
-

- Presentation of requirements engineering outcomes
- Presentation of data modeling outcomes (e.g. using INTERLIS, UML

1
- Presentation of data modeling outcomes (e.g. using INTERLIS, UML)
- Presentation of business process modeling outcomes (e.g. using BPMN

2
- Presentation of business process modeling outcomes (e.g. using BPMN)
- Embedding of agile development method (e.g. using SCRUM)

- Embedding of agile development method (e.g. using SCRUM)
- Practices for integration into operation (e.g. with the help of ITIL

3
- Practices for integration into operation (e.g. with the help of ITIL)

Phases and milestones
-

- The defined phases must not be omitted, but they may be subdivided.
- The milestones must not be omitted, but they are guided by the procedure and any sub-

- The milestones must not be omitted, but they are guided by the procedure and any subdivision of the phases.
- The names of the method components must not be changed.

- The names of the method components must not be changed.

- Multiple document templates can be created for a single outcome.
- Document templates must include the contents defined in the method outcome descrip-

- Document templates must include the contents defined in the method outcome descrip-

- Minimum required documents (outcomes) must not be omitted.
-

- Several individual outcomes can be integrated into a single document.
- Outcomes can be split.

1. Unified Modeling Language (UML), designed by the Object Management Group for object-oriented modeling,
   is a graphical description language for the presentation of software systems such as database applications,
   real-time systems, and workflow applications.
2. Business Process Model and Notation (BPMN), designed by the Object Management Group, is a graphical

- Outcomes can be split.
- Additional outcomes can be defined.

2. Business Process Model and Notation (BPMN), designed by the Object Management Group, is a graphical
   description language for creating business process models, flowcharts, and workflows.

3. Information Technology Infrastructure Library (ITIL) is an IT service management framework consisting of best

4. Information Technology Infrastructure Library (ITIL) is an IT service management framework consisting of best
   practice processes for the provision of IT services.

5. Abbreviation of the German "Geschäftsverwaltung", used in administration for workflow systems with electronic


practice processes for the provision of IT services.
4\. Abbreviation of the German "Geschäftsverwaltung", used in administration for workflow systems with electronic
records and process management.

* * *

tion, but they can be extended and fleshed out.

- The new tasks needed to create the outcomes must be described.
  Modules, scenarios

- New modules and scenarios can be created.

- The defined HERMES scenarios and modules can be extended with outcomes and the associated tasks, but not reduced. If outcomes or tasks are removed from a scenario or module, this results in a customized scenario.
  Roles

- Roles can be described in greater detail as long as the essential task area is identical.

- Further roles can be defined. A role description is mandatory for each new role.

- New roles must be assigned to one of the hierarchy levels and a partner group.

- Minimum roles to be filled as well as their assignment to the user partner group must not be changed.
  Checklists

- The contents of all checklists can be freely adapted and expanded.

- Checklist components described in decision-making tasks cannot be omitted. - Separate individual checklists can also be defined in addition.
  Once the organization-specific adaptations have been made, scenarios are created for projects with the same characteristics.


215/244

* * *

Vocabulary

Phases

|  | German | French |
| --- | --- | --- |
| 1.4.4.1 | Abschluss | Clôture |
| 1.4.2.1 | Konzept | Conception |
| 1.4.2.3 | Einführung | Déploiement |
| 1.4.3.1 | Umsetzung | Mise en œuvre |
| 1.4.2.2 | Realisierung | Réalisation |
| 1.4.1.1 | Initialisierung | Initialisation |

| Italian | English |  |
| --- | --- | --- |
| Conclusione | Closure | 23 |
| Progettazione | Concept | 20 |
| Introduzione | Deployment | 21 |
| Attuazione | Execution | 22 |
| Realizzazione | Implementation | 21 |
| Avvio | Initiation | 19 |

Table 30: HERMES phases vocabulary, 4 languages

Scenarios

|  | German | French |
| --- | --- | --- |
| 2.4.2.2 | IT-Adaption | Adaptation IT |
| 2.4.2.1 | IT-Entwicklung | Développement IT |
| 2.4.3.1 | Organisation-sanpassung | Adaptation de l'organisation |
| 2.4.1.2 | Dienstleistung/Produkt Adaption | Adaptation de la prestation/du produit |
| 2.4.1.1 | Dienstleistung/Produkt Entwicklung | Développement de la prestation/du produit |

| Italian | English |  |
| --- | --- | --- |
| Adeguamento IT | IT adaptation | 29 |
| Sviluppo IT | IT development | 29 |
| Adeguamento dell'organizzazione | Organizational adjustment | 30 |
| Adeguamento del servizio/prodotto | Service/product adaptation | 28 |
| Sviluppo del servizio/prodotto | Service/product development | 27 |

Modules

Table 31: HERMES scenarios vocabulary, 4 languages

216/244

* * *

|  | German | French |
| --- | --- | --- |
| 3.4.2.5 | IT-System | Système informatique |
| 3.4.2.3 | Organisation | Organisation |
| 3.4.2.2 | Beschaffung | Achat |
| 3.4.2.4 | Produkt | Produit |
| 3.4.2.1 | Projektgrundlagen | Bases du projet |
| 3.4.1.2 | Projektführung | Conduite du projet |
| 3.4.1.1 | Projekts-teuerung | Pilotage du projet |
| 3.4.2.6 | Tests | Tests |

| Italian | English |  |
| --- | --- | --- |
| Sistema IT | IT system | 39 |
| Organizzazione | Organization | 38 |
| Acquisto | Procurement | 37 |
| Prodotto | Product | 38 |
| Basi del progetto | Project foundations | 36 |
| Gestione del progetto | Project management | 35 |
| Conduzione del progetto | Project steering | 34 |
| Test | Tests | 40 |

Table 32: HERMES modules vocabulary, 4 languages

Outcomes

|  | German | French |
| --- | --- | --- |
| 4.4.2.1 | Checkliste Abnahme | Liste de contrôle Réception |
| 4.4.4.1 | Meilenstein Abnahme | Jalon Réception |
| 4.4.1.1 | Abnahmeprotokoll | Procès-verbal de réception |
| 4.4.1.54 | Vereinbarung | Accord |
| 4.4.1.16 | Geschäftsmodellbeschreibung | Description du modèle d'affaires |
| 4.4.1.2 | Änderungsantrag | Demande de modification |
| 4.4.1.3 | Änderungsstatusliste | Liste de l'état des modifications |
| 4.4.2.9 | Checkliste Phasenfreigabe Abschluss | Liste de contrôle Libération de la phase de clôture |
| 4.4.4.9 | Meilenstein Phasenfreigabe Abschluss | Jalon Libération de la phase de clôture |

| Italian | English |  |
| --- | --- | --- |
| Lista di controllo Accettazione | Acceptance checklist | 72 |
| Pietra miliare Accettazione | Acceptance milestone | 78 |
| Verbale di accettazione | Acceptance report | 47 |
| Accordo | Agreement | 72 |
| Descrizione del modello operativo | Business model description | 55 |
| Domanda di modifica | Change request | 48 |
| Lista Stato delle modifiche | Change status list | 48 |
| Lista di controllo Avvio della fase Conclusione | Closure phase release checklist | 73 |
| Pietra miliare Avvio della fase Conclusione | Closure phase release milestone | 79 |
| 4.4.2.17 | Checkliste Zuschlag | Liste de contrôle Adjudication |
| 4.4.4.16 | Meilenstein Zuschlag | Jalon Adjudication |
| 4.4.1.14 | Einführungskonzept | Concept de déploiement |
| 4.4.3.5 | Einführungs-massnahmen durchgeführt | Mesures de déploiement effectuées |
| 4.4.3.6 | Einführungs-massnahmen realisiert | Mesures de déploiement réalisées |
| 4.4.1.12 | Detailspezifikation | Spécification détaillée |
| 4.4.1.15 | Evaluationsbericht | Rapport d'évaluation |
| 4.4.1.13 | Durchführungauf-trag | Mandat d'exécution |
| 4.4.2.5 | Checkliste Durchführungfreigabe | Liste de contrôle Libération de l'exécution |
| 4.4.4.5 | Meilenstein Durchführungfreigabe | Jalon Libération de l'exécution |
| 4.4.1.35 | Projektschluss-beurteilung | Evaluation finale du projet |
| 4.4.1.17 | Integrations-und Installationsanleitung | Guide d'intégration et d'installation |
| 4.4.1.18 | Integrationkonzept | Concept d'intégration |
| 4.4.3.16 | Schnittstellen realisiert | Interfaces réalisées |
| 4.4.1.19 | ISDS-Konzept | Concept SIPD |
| 4.4.2.6 | Checkliste ISDS-Konzept | Liste de contrôle Concept SIPD |
| 4.4.4.6 | Meilenstein ISDS-Konzept | Jalon Concept SIPD |

| Italian | English |  |
| --- | --- | --- |
| Lista di controllo Aggiudicazione | Contract award checklist | 74 |
| Pietra miliare Aggiudicazione | Contract award milestone | 80 |
| Progettazione dell'introduzione | Deployment concept | 54 |
| Misure d'introduzione attuate | Deployment measures carried out | 75 |
| Misure d'introduzione realizzate | Deployment measures realized | 75 |
| Specifica dettagliata | Detailed specifications | 53 |
| Rapporto di valutazione | Evaluation report | 54 |
| Mandato di esecuzione | Execution order | 53 |
| Lista di controllo Avvio dell'esecuzione | Execution release checklist | 73 |
| Pietra miliare Avvio dell'esecuzione | Execution release milestone | 78 |
| Valutazione finale del progetto | Final project evaluation | 63 |
| Guida per l'integrazione e l'installazione | Integration and installation instructions | 56 |
| Progettazione dell'integrazione | Integration concept | 56 |
| Interfacce realizzate | Interfaces realized | 77 |
| Piano SIPD | ISDP concept | 57 |
| Lista di controllo Piano SIPD | ISDP concept checklist | 73 |
| Pietra miliare Piano SIPD | ISDP concept milestone | 79 |
| 4.4.3.8 | ISDS-Konzept überführt | Concept SIPD transféré |
| 4.4.3.7 | ISDS-Massnahmen realisiert | Mesures SIPD réalisées |
| 4.4.2.4 | Checkliste Betriebsaufnahme | Liste de contrôle Mise en service |
| 4.4.4.4 | Meilenstein Betriebsaufnahme | Jalon Mise en service |
| 4.4.3.1 | Altsystem entfernt | Ancien système mis hors service |
| 4.4.1.44 | Rechtsgrundlagenanalyse | Analyse des bases légales |
| 4.4.1.32 | Projekterfahrungen | Expériences acquises |
| 4.4.1.20 | Liste Projekte tentscheide Führung | Liste Décisions de conduite |
| 4.4.1.21 | Liste Projekte tentscheide Steuerung | Liste Décisions de pilotage |
| 4.4.2.2 | Checkliste Abnahme Migration | Liste de contrôle Réception de la migration |
| 4.4.4.2 | Meilenstein Abnahme Migration | Jalon Réception de la migration |
| 4.4.3.9 | Migration durchgeführt | Migration effectuée |
| 4.4.1.24 | Migrationskonzept | Concept de migration |
| 4.4.3.10 | Migrationsverfahren realisiert | Procédure de migration réalisée |
| 4.4.1.37 | Protokoll | Procès-verbal |

| Italian | English |  |
| --- | --- | --- |
| Piano SIPD trasferito | ISDP concept transferred | 76 |
| Misure SIPD realizzate | ISDP measures realized | 75 |
| Lista di controllo Messa in esercizio | Launch of operation checklist | 73 |
| Pietra miliare Messa in esercizio | Launch of operation milestone | 78 |
| Vecchio sistema disinstallato | Legacy system removed | 75 |
| Analisi delle basi legali | Legal basis analysis | 67 |
| Esperienze del progetto | Lessons learned | 61 |
| Lista Decisioni della gestione | List of management project decisions | 57 |
| Lista Decisioni della conduzione | List of steering project decisions | 57 |
| Lista di controllo Accettazione della migrazione | Migration acceptance checklist | 73 |
| Pietra miliare Accettazione della migrazione | Migration acceptance milestone | 78 |
| Migrazione effettuata | Migration carried out | 76 |
| Progettazione della migrazione | Migration concept | 58 |
| Procedura di migrazione realizzata | Migration procedure realized | 76 |
| Verbale | Minutes | 64 |
| 4.4.2.16 | Checkliste Weiteres Vorgehen | Liste de contrôle Suite du projet |
| 4.4.4.15 | Meilenstein Weiteres Vorgehen | Jalon Suite du projet |
| 4.4.1.4 | Angebot | Offre |
| 4.4.1.11 | Betriebskonzept | Concept d'exploitation |
| 4.4.3.3 | Betriebsinfras-truktur realisiert | Infrastructure d'exploitation réalisée |
| 4.4.1.10 | Betriebshandbuch | Manuel d'exploitation |
| 4.4.3.4 | Betriebsorganisation realisiert | Organisation de l'exploitation réalisée |
| 4.4.3.2 | Betrieb aktiviert | Exploitation activée |
| 4.4.3.11 | Organisation aktiviert | Organisation activée |
| 4.4.1.28 | Organisation-skonzept | Concept d'organisation |
| 4.4.1.27 | Organisations-beschreibung | Description de l'organisation |
| 4.4.3.12 | Organisation umgesetzt | Organisation mise en œuvre |
| 4.4.1.26 | Organisations sanforderungen | Exigences organisation-nelles |
| 4.4.2.8 | Checkliste Phasenfreigabe | Liste de contrôle Libération de la phase |
| 4.4.4.8 | Meilenstein Phasenfreigabe | Jalon Libération de la phase |
| 4.4.1.29 | Phasenbericht | Rapport de phase |

| Italian | English |  |
| --- | --- | --- |
| Lista di controllo Continuazione | Next steps checklist | 74 |
| Pietra miliare Continuazione | Next steps milestone | 80 |
| Offerta | Offer | 49 |
| Piano di esercizio | Operating concept | 52 |
| Infrastruttura di esercizio realizzata | Operating infrastructure realized | 75 |
| Manuale di esercizio | Operating manual | 52 |
| Organizzazione di esercizio realizzata | Operating organization realized | 75 |
| Esercizio attivato | Operation activated | 75 |
| Organizzazione attivata | Organization activated | 76 |
| Progettazione dell'organizzazione | Organization concept | 60 |
| Descrizione dell'organizzazione | Organization description | 59 |
| Organizzazione attuata | Organization implemented | 76 |
| Requisiti dell'organizzazione | Organizational requirements | 59 |
| Lista di controllo Avvio della fase | Phase release checklist | 73 |
| Pietra miliare Avvio della fase | Phase release milestone | 79 |
| Rapporto di fase | Phase report | 60 |
| 4.4.2.15 | Checkliste Vorabnahme | Liste de contrôle Préréception |
| 4.4.4.14 | Meilenstein Vorabnahme | Jalon Préréception |
| 4.4.1.39 | Prozess-beschreibung | Description de processus |
| 4.4.1.9 | Beschaffungsanalyse | Analyse de l'appel d'offres |
| 4.4.3.13 | Produkt aktiviert | Produit activé |
| 4.4.1.31 | Produktkonzept | Concept du produit |
| 4.4.2.10 | Checkliste Produktkonzept | Liste de contrôle Concept du produit |
| 4.4.4.10 | Meilenstein Produktkonzept | Jalon Concept du produit |
| 4.4.3.14 | Produkt entwickelt oder angepasst | Produit développé ou adapté |
| 4.4.1.30 | Produktdokumentation | Documentation du produit |
| 4.4.2.12 | Checkliste Projektabschluss | Liste de contrôle Clôture du projet |
| 4.4.4.11 | Meilenstein Projektabschluss | Jalon Clôture du projet |
| 4.4.2.11 | Checkliste Projektabbruch | Liste de contrôle Interruption du projet |
| 4.4.1.33 | Projektinitialisierungsauf-trag | Mandat d'initialisation du projet |

| Italian | English |  |
| --- | --- | --- |
| Lista di controlloAccettazione preliminare | Preliminary acceptance checklist | 74 |
| Pietra miliareAccettazione preliminare | Preliminary acceptance milestone | 80 |
| Descrizione del processo | Process description | 65 |
| Analisi dell'acquisto | Procurement analysis | 51 |
| Prodotto attività | Product activated | 76 |
| Progettazione del prodotto | Product concept | 61 |
| Lista di controlloProgettazione del prodotto | Product concept checklist | 74 |
| Pietra miliareProgettazione del prodotto | Product concept milestone | 79 |
| Prodotto sviluppato o adeguato | Product developed or adapted | 76 |
| Documentazione del prodotto | Product documentation | 61 |
| Lista di controlloConclusione del progetto | Project closure checklist | 74 |
| Pietra miliareConclusione del progetto | Project closure milestone | 79 |
| Lista di controlloInterruzione del progetto | Project discontinuation checklist | 74 |
| Mandato di avvio del progetto | Project initiation order | 62 |
| 4.4.2.13 | Checkliste Projektinitialisierungsfreigabe | Liste de contrôle Libération de l'initialisation du projet |
| 4.4.4.12 | Meilenstein Projektinitialisierungsfreigabe | Jalon Libération de l'initialisation du projet |
| 4.4.1.34 | Projektmanagementplan | Plan de gestion du projet |
| 4.4.1.36 | Projektstatusbericht | Rapport sur l'état du projet |
| 4.4.1.45 | Schutzbedarfsanalyse | Analyse des besoins de protection |
| 4.4.1.38 | Prototypdokumentation | Documentation du prototype |
| 4.4.3.15 | Prototyp realisiert | Prototype réalisé |
| 4.4.1.41 | Publikation | Publication |
| 4.4.1.42 | QS- und Risikobericht | Rapport sur la qualité et les risques |
| 4.4.1.25 | Offertanfrage | Demande d'offres |
| 4.4.2.14 | Checkliste Releasefreigabe | Liste de contrôle Libération du release |
| 4.4.4.13 | Meilenstein Releasefreigabe | Jalon Libération du release |
| 4.4.1.43 | Releasebericht | Rapport de release |
| 4.4.1.40 | Prüfprotokoll | Procès-verbal de vérification |
| 4.4.1.46 | Service Level Agreement | Accord sur le niveau de service |
| 4.4.1.47 | Situationsanalyse | Analyse de la situation |

| Italian | English |  |
| --- | --- | --- |
| Lista di controllo Avvio del progetto | Project initiation release checklist | 74 |
| Pietra miliare Avvio del progetto | Project initiation release milestone | 79 |
| Piano di gestione progettuale | Project management plan | 62 |
| Rapporto sullo stato del progetto | Project status report | 64 |
| Analisi delle esigenze di protezione | Protection needs analysis | 67 |
| Documentazione del prototipo | Prototype documentation | 65 |
| Prototipo realizzato | Prototype realized | 77 |
| Pubblicazione | Publication | 66 |
| Rapporto Controllo qualità e rischi | QA and risk report | 66 |
| Domanda di offerta | Quote request | 59 |
| Lista di controllo Avvio del rilascio | Release checklist | 74 |
| Pietra miliare Avvio del rilascio | Release milestone | 79 |
| Rapporto di rilascio | Release report | 66 |
| Rapporto di verifica | Review report | 65 |
| Accordo sui livelli di servizio | Service level agreement | 67 |
| Analisi della situazione | Situation analysis | 68 |
| 4.4.1.23 | Lösungsarchitektur | Architecture de la solution |
| 4.4.2.7 | Checkliste Lösungsarchitektur | Liste de contrôle Architecture de la solution |
| 4.4.4.7 | Meilenstein Lösungsarchitektur | Jalon Architecture de la solution |
| 4.4.1.22 | Lösungsanforderungen | Exigences envers la solution |
| 4.4.1.48 | Stakeholderinteressen | Intérêts des parties prenantes |
| 4.4.1.49 | Stakeholdererliste | Liste des parties prenantes |
| 4.4.1.50 | Studie | Étude |
| 4.4.3.17 | System aktiviert | Système activé |
| 4.4.1.51 | Systemkonzept | Concept du système |
| 4.4.3.18 | System entwickelt oder parametrisiert | Système développé ou paramétré |
| 4.4.3.19 | System integriert | Système intégré |
| 4.4.2.3 | Checkliste Ausschreibung | Liste de contrôle Appel d'offres |
| 4.4.1.8 | Ausschreibungsunterlagen | Dossier d'appel d'offres |
| 4.4.4.3 | Meilenstein Ausschreibung | Jalon Appel d'offres |
| 4.4.1.5 | Angebotsprotokoll | Procès-verbal des offres |
| 4.4.1.52 | Testkonzept | Concept de test |
| 4.4.3.20 | Testinfrastruk | Infrastructure |

| Italian | English |  |
| --- | --- | --- |
| Architettura della soluzione | Solution architecture | 58 |
| Lista di controllo Architettura della soluzione | Solution architecture checklist | 73 |
| Pietra miliare Architettura della soluzione | Solution architecture milestone | 79 |
| Requisiti della soluzione | Solution requirements | 57 |
| Interessi degli stakeholder | Stakeholder interests | 69 |
| Lista Stakeholder | Stakeholder list | 69 |
| Studio | Study | 69 |
| Sistema attivato | System activated | 77 |
| Piano del sistema | System concept | 70 |
| Sistema sviluppato o parametrizzato | System developed or parameterized | 77 |
| Sistema integrato | System integrated | 77 |
| Lista di controllo Bando di concorso | Tender checklist | 73 |
| Documentazione del bando di concorso | Tender documentation | 50 |
| Pietra miliare Bando di concorso | Tender milestone | 78 |
| Verbale dell'offerta | Tender report | 49 |
| Progettazione dei test | Test concept | 71 |
| Infrastruttura di | Test infrastructure | 77 |
| 4.4.3.21 | Testinfrastruktur überführt | Infrastructure de test transférée |
| 4.4.1.53 | Testprotokoll | Procès-verbal de test |
| 4.4.1.6 | Anwendung-shandbuch | Manuel d'utilisation |
| 4.4.1.7 | Arbeitsauftrag | Mandat de travail |

| Italian | English |  |
| --- | --- | --- |
| Infrastruttura di test trasferita | Test infrastructure transferred | 78 |
| Verbale dei test | Test report | 71 |
| Manuale d'uso | User manual | 49 |
| Mandato di lavoro | Work order | 49 |

Table 33: HERMES outcomes vocabulary, 4 languages

Tasks

|  | German | French |
| --- | --- | --- |
| 5.4.3.7 | Betrieb aktivieren | Activer l'exploitation |
| 5.4.3.24 | Organisation aktivieren | Activer l'organisation |
| 5.4.3.30 | Produkt aktivieren | Activer le produit |
| 5.4.3.46 | System aktivieren | Activer le système |
| 5.4.3.44 | Stakeholderinteressen vertreten | Représenter les intérêts des parties prénantes |
| 5.4.3.18 | Leistungen vereinbaren und steuern | Définir et piloter les prestations |
| 5.4.3.39 | Rechtsgrundlagenanalyse erarbeiten | Élaborer l'analyse des bases légales |
| 5.4.3.42 | Schutzbedarfs-analyse erarbeiten | Élaborer l'analyse des besoins de protection |
| 5.4.3.37 | Prototyping durchführen | Effectuer le prototypage |
| 5.4.3.21 | Migration durchführen | Effectuer la migration |
| 5.4.3.50 | Test durchführen | Effectuer les tests |

| Italian | English |  |
| --- | --- | --- |
| Attivare l'esercizio | Activate operation | 112 |
| Attivare l'organizzazione | Activate organization | 127 |
| Attivare il prodotto | Activate product | 133 |
| Attivare il sistema | Activate system | 150 |
| Rappresentare gli interessi degli stakeholder | Advocate stakeholder interests | 148 |
| Concordare e gestire le prestazioni | Agree on and steer goods/services | 121 |
| Elaborare l'analisi delle basi legali | Analyze legal basis | 143 |
| Elaborare l'analisi delle esigenze di protezione | Analyze protection needs | 146 |
| Eseguire la prototipazione | Carry out prototyping | 141 |
| Eseguire la migrazione | Conduct migration | 125 |
| Eseguire i test | Conduct test | 153 |
| 5.4.3.29 | Probleme behandeln und Erfahrungen nutzen | Traiter les problèmes et mettre à profit les expériences |
| 5.4.2.2 | Entscheid Abnahme treffen | Décider de la réception |
| 5.4.2.1 | Entscheid Abnahme Migration treffen | Décider de la réception de la migration |
| 5.4.1.1 | Entscheid Ausschreibung treffen | Décider de l'appel d'offres |
| 5.4.1.4 | Entscheid Phasenfreigabe Abschluss treffen | Décider de la libération de la phase de clôture |
| 5.4.1.10 | Entscheid Zuschlag treffen | Décider de l'adjudication |
| 5.4.1.3 | Entscheid Durchführungsfreigabe treffen | Décider de la libération de l'exécution |
| 5.4.2.3 | Entscheid ISDS-Konzept treffen | Décider du concept SIPD |
| 5.4.1.2 | Entscheid Betriebsaufnahme treffen | Décider de la mise en service |
| 5.4.2.7 | Entscheid Weiteres Vorgehen treffen | Décider de la suite du projet |
| 5.4.1.5 | Entscheid Phasenfreigabe treffen | Décider de la libération de la phase |
| 5.4.2.6 | Entscheid Vorabnahme treffen | Décider de la préréception |
| 5.4.2.5 | Entscheid Produktkonzept | Décider du concept du |

| Italian | English |  |
| --- | --- | --- |
| Trattare i problemi e valorizzare le esperienze | Deal with problems and benefit from lessons learned | 132 |
| Decisione Accettazione | Decide on acceptance | 100 |
| Decisione Accettazione della migrazione | Decide on acceptance of migration | 99 |
| Decisione Bando di concorso | Decide on call for tenders | 88 |
| Decisione Avvio della fase Conclusione | Decide on closure phase release | 90 |
| Decisione Aggiudicazione | Decide on contract award | 98 |
| Decisione Avvio dell'eseucuzione | Decide on execution release | 89 |
| Decisione Piano SIPD | Decide on ISDP concept | 101 |
| Decisione Messa in esercizio | Decide on launch of operation | 88 |
| Decisione Continuazione | Decide on next steps | 104 |
| Decisione Avvio della fase | Decide on phase release | 91 |
| Decisione Accettazione preliminare | Decide on preliminary acceptance | 103 |
| Decisione Progettazione | Decide on product | 103 |
| 5.4.1.7 | Entscheid Projektabschluss treffen | Décider de la clôture du projet |
| 5.4.1.6 | Entscheid Projektabbruch treffen | Décider l'interruption du projet |
| 5.4.1.8 | Entscheid Projektinitial-isierungsfreigabe treffen | Décider de la libération de l'initialisation du projet |
| 5.4.1.9 | Entscheid Releasefreigabe treffen | Décider de la libération du release |
| 5.4.2.4 | Entscheid Lösungsarchitektur treffen | Décider de l'architecture de la solution |
| 5.4.3.1 | Altsystem ausser Betrieb setzen | Mettre l'ancien système hors service |
| 5.4.3.11 | Einführungskonzept erarbeiten | Élaborer le concept de déploiement |
| 5.4.3.14 | Integra-tionskonzept erarbeiten | Élaborer le concept d'intégration |
| 5.4.3.15 | ISDS-Konzept erarbeiten | Élaborer le concept SIPD |
| 5.4.3.22 | Migra-tionskonzept erarbeiten | Élaborer le concept de migration |
| 5.4.3.9 | Betriebskonzept erarbeiten | Élaborer le concept d'exploitation |
| 5.4.3.32 | Produk-tkonzept erarbeiten | Élaborer le concept du produit |
| 5.4.3.53 | Testkonzept erarbeiten | Élaborer le concept de test |
| 5.4.3.54 | Vereinbarung erarbeiten | Élaborer l'accord |

| Italian | English |  |
| --- | --- | --- |
| Decisione Conclusione del progetto | Decide on project closure | 95 |
| Decisione Interruzione del progetto | Decide on project discontinuation | 93 |
| Decisione Avvio del progetto | Decide on project initiation release | 96 |
| Decisione Avvio del rilascio | Decide on release | 97 |
| Decisione Architettura della soluzione | Decide on solution architecture | 102 |
| Disattivare il vecchio sistema | Decommission the legacy system | 105 |
| Elaborare la progettazione dell'introduzione | Design deployment concept | 115 |
| Elaborare la progettazione dell'integrazione | Design integration concept | 118 |
| Elaborare il piano SIPD | Design ISDP concept | 119 |
| Elaborare la progettazione della migrazione | Design migration concept | 126 |
| Elaborare il piano di esercizio | Design operating concept | 113 |
| Elaborare la progettazione del prodotto | Design product concept | 135 |
| Elaborare la progettazione dei test | Design test concept | 156 |
| Elaborare l'accordo | Draw up agreement | 157 |
| 5.4.3.27 | Organisation-skonzept erarbeiten | Élaborer le concept d'organisation |
| 5.4.3.10 | Durch-führungsauf-trag erarbeiten | Élaborer le mandat d'exécution |
| 5.4.3.36 | Projektmanagementplan erarbeiten | Élaborer le plan de gestion du projet |
| 5.4.3.26 | Organisation-sanforderungen erarbeiten | Élaborer les exigences organisation-nelles |
| 5.4.3.3 | Angebote bewerten | Évaluer les offres |
| 5.4.3.12 | Einführungs-massnahmen durchführen | Effectuer les mesures de déploiement |
| 5.4.3.16 | ISDS-Konzept realisieren | Réaliser le concept SIPD |
| 5.4.3.25 | Organisation umsetzen | Réaliser l'organisation |
| 5.4.3.47 | System in Betrieb integrieren | Intégrer le système en fonctionnement |
| 5.4.3.4 | Ausschreibung durchführen | Effectuer l'appel d'offres |
| 5.4.3.33 | Projekt führen und kontrollieren | Conduire et contrôler le projet |
| 5.4.3.43 | Stakeholder managen und informieren | Gérer et informer les parties prenantes |
| 5.4.3.2 | Änderungen managen | Gérer les modifications |
| 5.4.3.41 | Risiken managen | Gérer les risques |
| 5.4.3.38 | Qualitätssicherung führen | Conduire l'assurance de la qualité |

| Italian | English |  |
| --- | --- | --- |
| Elaborare la progettazione dell'organizzazione | Draw up organization concept | 130 |
| Elaborare il mandato di esecuzione del progetto | Draw up project execution order | 114 |
| Elaborare il piano di gestione progettuale | Draw up project management plan | 140 |
| Elaborare i requisiti dell'organizzazione | Establish organizational requirements | 129 |
| Valutare le offerte | Evaluate tenders | 107 |
| Eseguire le misure d'introduzione | Execute deployment measures | 117 |
| Realizzare il piano SIPD | Implement ISDP concept | 119 |
| Attuare l'organizzazione | Implement organization | 128 |
| Integrare il sistema nell'esercizio | Integrate the system into operation | 151 |
| Pubblicare il bando di concorso | Issue call for tenders | 108 |
| Gestire e controllare il progetto | Manage and control project | 135 |
| Gestire e informare gli stakeholder | Manage and inform stakeholders | 146 |
| Gestire le modifiche | Manage changes | 106 |
| Gestire i rischi | Manage risks | 145 |
| Gestire la garanzia della qualità | Perform quality assurance | 142 |
| 5.4.3.5 | Ausschreibung erarbeiten | Élaborer l'appel d'offres |
| 5.4.3.28 | Phasenfreigabe vorbereiten | Préparer la libération de la phase |
| 5.4.3.6 | Beschaffungsanalyse erarbeiten | Élaborer l'analyse de l'appel d'offres |
| 5.4.3.35 | Projektabschluss vorbereiten | Préparer la clôture du projet |
| 5.4.3.40 | Releaseabschluss vorbereiten | Préparer la clôture du release |
| 5.4.3.20 | Lösungsarchitektur erarbeiten | Élaborer l'architecture de la solution |
| 5.4.3.19 | Lösungsanforderungen erarbeiten | Élaborer les exigences envers la solution |
| 5.4.3.45 | Studie erarbeiten | Élaborer l'étude |
| 5.4.3.49 | Systemintegraction vorbereiten | Préparer l'intégration du système |
| 5.4.3.13 | Einführungsmassnahmen realisieren | Réaliser les mesures de déploiement |
| 5.4.3.23 | Migrationsverfahren realisieren | Réaliser la procédure de migration |
| 5.4.3.8 | Betrieb realisieren | Réaliser l'environnement d'exploitation |
| 5.4.3.31 | Produkt realisieren | Réaliser le produit |
| 5.4.3.48 | System realisieren | Réaliser le système |
| 5.4.3.51 | Testinfrastruktur realisieren | Réaliser l'infrastructure de test |
| 5.4.3.34 | Projekt steuern | Piloter le projet |

| Italian | English |  |
| --- | --- | --- |
| Elaborare il bando di concorso | Prepare call for tenders | 109 |
| Preparare l'avvio della fase | Prepare phase release | 131 |
| Elaborare l'analisi dell'acquisto | Prepare procurement analysis | 110 |
| Preparare la conclusione del progetto | Prepare project closure | 139 |
| Preparare la conclusione del rilascio | Prepare release closure | 144 |
| Elaborare l'architettura della soluzione | Prepare solution architecture | 124 |
| Elaborare i requisiti della soluzione | Prepare solution requirements | 123 |
| Elaborare lo studio | Prepare study | 148 |
| Preparare l'integrazione del sistema | Prepare system integration | 153 |
| Realizzare le misure d'introduzione | Realize deployment measures | 117 |
| Realizzare la procedura di migrazione | Realize migration procedure | 127 |
| Realizzare l'esercizio | Realize operation | 113 |
| Realizzare il prodotto | Realize product | 134 |
| Realizzare il sistema | Realize system | 152 |
| Realizzare l'infrastruttura per i test | Realize test infrastructure | 154 |
| Condurre il progetto | Steer project | 137 |
| 5.4.3.17 | ISDS-Konzept überführen | Transférer le concept SIPD |
| 5.4.3.52 | Testinfrastruktur überführen | Transférer l'infrastructure de test |

| Italian | English |  |
| --- | --- | --- |
| Trasferire il piano SIPD | Transfer ISDP concept | 120 |
| Trasferire l'infrastruttura per i test | Transfer test infrastructure | 155 |

Table 34: HERMES tasks vocabulary, 4 languages

Roles

|  | German | French |
| --- | --- | --- |
| 6.4.3.3 | Business Analyst | Business analyst |
| 6.4.3.4 | Entwickler | Développeur |
| 6.4.3.5 | Umsetzungsorganisation | Organisation de mise en oeuvre |
| 6.4.3.6 | ISDS-Verantwortlicher | Responsable SIPD |
| 6.4.3.7 | IT-Architekt | Architecte informatique |
| 6.4.3.2 | Betriebsverantwortlicher | Responsable de l'exploitation |
| 6.4.1.2 | Projektausschuss | Comité de pilotage |
| 6.4.2.2 | Projektleiter | Chef de projet |
| 6.4.1.1 | Auftraggeber | Mandant |
| 6.4.2.3 | Projektunter-stützung | Assistance de projet |
| 6.4.1.3 | Qualitäts- und Risikomanager | Gestionnaire de la qualité et des risques |
| 6.4.2.4 | Teilprojektleiter | Chef de sous-projet |
| 6.4.2.1 | Fachausschuss | Comité spécialisé |
| 6.4.3.9 | Testverantwortlicher | Responsable des tests |
| 6.4.3.8 | Tester | Testeur |
| 6.4.3.1 | Anwen-dervertreter | Représentant des utilisateurs |

| Italian | English |  |
| --- | --- | --- |
| Business Analyst | Business analyst | 187 |
| Sviluppatore | Developer | 188 |
| Organizzazione di attuazione | Execution organization | 191 |
| Responsabile SIPD | ISDP manager | 191 |
| Architetto IT | IT architect | 192 |
| Responsabile dell'esercizio | Operations manager | 185 |
| Comitato di progetto | Project committee | 171 |
| Capoprogetto | Project management | 173 |
| Committente | Project sponsor | 166 |
| Supporto di progetto | Project support | 181 |
| Gestore della qualità e dei rischi | Quality and risk manager | 172 |
| Responsabile di sottoprogetto | Sub-project manager | 181 |
| Comitato esperti | Technical committee | 173 |
| Responsabile dei test | Test manager | 194 |
| Collaudatore | Tester | 193 |
| Rappresentante degli utenti | User representative | 182 |

Table 35: HERMES roles vocabulary, 4 languages

* * *

Contents

Foreword 2

Impressum 3

Preface 5

A Method overview 6
A.1 HERMES project management - The big picture 6
A.2 What is HERMES project management? 6
A.3 Project sizes supported by HERMES 7
A.4 Use of HERMES project management in practice 7
A.5 The interfaces of HERMES project management 8
A.6 Agile development management with HERMES 9
A.7 Positioning of program management 9
A.8 User information 10

B HERMES project management method components 11
B.1 Phases 11
B.2 Scenarios 11
B.3 Modules 12
B.4 Outcomes 13
B.5 Tasks 14
B.6 Roles 14

1 Phases 15
1.1 Introduction 15
1.1.1 Project life cycle 15
1.1.2 Project start 15
1.1.3 Solution development 16

* * *

2.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

* * *

4.4.1.2 Change request 48
4.4.1.3 Change status list 48
4.4.1.4 Offer 49
4.4.1.5 Tender report 49
4.4.1.6 User manual 49
4.4.1.7 Work order 49
4.4.1.8 Tender documentation 50
4.4.1.9 Procurement analysis 51
4.4.1.10 Operating manual 52
4.4.1.11 Operating concept . . . . . . . . . . . . . . . . . . . . . . . . . . 52
4.4.1.12 Detailed specifications 53
4.4.1.13 Execution order 53
4.4.1.14 Deployment concept . . . . . . . . . . . . . . . . . . . . . . . . . 54
4.4.1.15 Evaluation report . . . . . . . . . . . . . . . . . . . . . . . . . . . 54
4.4.1.16 Business model description . . . . . . . . . . . . . . . . . . . . . 55
4.4.1.17 Integration and installation instructions 56
4.4.1.18 Integration concept 56
4.4.1.19 ISDP concept 57
4.4.1.20 List of management project decisions 57
4.4.1.21 List of steering project decisions 57
4.4.1.22 Solution requirements . . . . . . . . . . . . . . . . . . . . . . . . 57
4.4.1.23 Solution architecture . . . . . . . . . . . . . . . . . . . . . . . . . 58
4.4.1.24 Migration concept 58
4.4.1.25 Quote request 59
4.4.1.26 Organizational requirements 59
4.4.1.27 Organization description 59
4.4.1.28 Organization concept 60
4.4.1.29 Phase report 60
4.4.1.30 Product documentation 61
4.4.1.31 Product concept 61
4.4.1.32 Lessons learned . . . . . . . . . . . . . . . . . . . . . . . . . . . 61
4.4.1.33 Project initiation order . . . . . . . . . . . . . . . . . . . . . . . . 62
4.4.1.34 Project management plan . . . . . . . . . . . . . . . . . . . . . . 62
4.4.1.35 Final project evaluation 63
4.4.1.36 Project status report . . . . . . . . . . . . . . . . . . . . . . . . . 64
4.4.1.37 Minutes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 64
4.4.1.38 Prototype documentation 65
4.4.1.39 Process description 65
4.4.1.40 Review report 65
4.4.1.41 Publication 66
4.4.1.42 QA and risk report . . . . . . . . . . . . . . . . . . . . . . . . . . 66
4.4.1.43 Release report . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66
4.4.1.44 Legal basis analysis . . . . . . . . . . . . . . . . . . . . . . . . . 67
4.4.1.45 Protection needs analysis . . . . . . . . . . . . . . . . . . . . . . 67
4.4.1.46 Service level agreement 67
4.4.1.47 Situation analysis 68
4.4.1.48 Stakeholder interests 69
4.4.1.49 Stakeholder list 69
4.4.1.50 Study 69
4.4.1.51 System concept 70
4.4.1.52 Test concept 71

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

. . . . . . . . . . . . . .

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

. . . . . . . . . . . . . . . . . . . .

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

232/244

* * *

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

4.4.1.53 Test report 71
4.4.1.54 Agreement 72
Checklists . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 72
4.4.2.1 Acceptance checklist 72
4.4.2.2 Migration acceptance checklist . . . . . . . . . . . . . . . . . . . 73
4.4.2.3 Tender checklist 73
4.4.2.4 Launch of operation checklist . . . . . . . . . . . . . . . . . . . . 73
4.4.2.5 Execution release checklist . . . . . . . . . . . . . . . . . . . . . 73
4.4.2.6 ISDP concept checklist 73
4.4.2.7 Solution architecture checklist 73
4.4.2.8 Phase release checklist . . . . . . . . . . . . . . . . . . . . . . . 73
4.4.2.9 Closure phase release checklist 73
4.4.2.10 Product concept checklist . . . . . . . . . . . . . . . . . . . . . . 74
4.4.2.11 Project discontinuation checklist 74
4.4.2.12 Project closure checklist 74
4.4.2.13 Project initiation release checklist 74
4.4.2.14 Release checklist 74
4.4.2.15 Preliminary acceptance checklist . . . . . . . . . . . . . . . . . . 74
4.4.2.16 Next steps checklist 74
4.4.2.17 Contract award checklist 74
States 75
4.4.3.1 Legacy system removed 75
4.4.3.2 Operation activated 75
4.4.3.3 Operating infrastructure realized 75
4.4.3.4 Operating organization realized 75
4.4.3.5 Deployment measures carried out 75
4.4.3.6 Deployment measures realized . . . . . . . . . . . . . . . . . . . 75
4.4.3.7 ISDP measures realized 75
4.4.3.8 ISDP concept transferred . . . . . . . . . . . . . . . . . . . . . . 76
4.4.3.9 Migration carried out . . . . . . . . . . . . . . . . . . . . . . . . . 76
4.4.3.10 Migration procedure realized 76
4.4.3.11 Organization activated 76
4.4.3.12 Organization implemented 76
4.4.3.13 Product activated 76
4.4.3.14 Product developed or adapted 76
4.4.3.15 Prototype realized 77
4.4.3.16 Interfaces realized . . . . . . . . . . . . . . . . . . . . . . . . . . 77
4.4.3.17 System activated 77
4.4.3.18 System developed or parameterized . . . . . . . . . . . . . . . . 77
4.4.3.19 System integrated 77
4.4.3.20 Test infrastructure realized 77
4.4.3.21 Test infrastructure transferred 78
Milestones 78
4.4.4.1 Acceptance milestone . . . . . . . . . . . . . . . . . . . . . . . . 78
4.4.4.2 Migration acceptance milestone 78
4.4.4.3 Tender milestone 78
4.4.4.4 Launch of operation milestone 78
4.4.4.5 Execution release milestone 78
4.4.4.6 ISDP concept milestone . . . . . . . . . . . . . . . . . . . . . . . 79
4.4.4.7 Solution architecture milestone . . . . . . . . . . . . . . . . . . . 79
4.4.4.8 Phase release milestone 79

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

4.4.2
4.4.3
4.4.4
233/244

* * *

4.4.4.9 Closure phase release milestone . . . . . . . . . . . . . . . . . . 79
4.4.4.10 Product concept milestone. . . . . . . . . . . . . . . . . . . . . 79
4.4.4.11 Project closure milestone. . . . . . . . . . . . . . . . . . . . . . 79
4.4.4.12 Project initiation release milestone . . . . . . . . . . . . . . . . . 79
4.4.4.13 Release milestone . . . . . . . . . . . . . . . . . . . . . . . . . . 79
4.4.4.14 Preliminary acceptance milestone. . . . . . . . . . . . . . . . . 80
4.4.4.15 Next steps milestone. . . . . . . . . . . . . . . . . . . . . . . . 80
4.4.4.16 Contract award milestone . . . . . . . . . . . . . . . . . . . . . . 80
5 Tasks 81
5.1 Introduction. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 81
5.1.1 Positioning of tasks. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 81
5.1.2 Decision-making tasks . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 81
5.1.2.1 General . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 81
5.1.2.2 Steering decisions . . . . . . . . . . . . . . . . . . . . . . . . . . 81
5.1.2.3 Management decisions. . . . . . . . . . . . . . . . . . . . . . . 82
5.2 Overview of tasks. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 82
5.2.1 Standard tasks. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 82
5.2.2 Customized tasks. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 87
5.3 Explanation regarding task description. . . . . . . . . . . . . . . . . . . . . . . . 87
5.4 Descriptions of the tasks . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 88
5.4.1 Decision-making tasks of steering. . . . . . . . . . . . . . . . . . . . . . 88
5.4.1.1 Decide on call for tenders . . . . . . . . . . . . . . . . . . . . . . 88
5.4.1.2 Decide on launch of operation. . . . . . . . . . . . . . . . . . . 88
5.4.1.3 Decide on execution release. . . . . . . . . . . . . . . . . . . . 89
5.4.1.4 Decide on closure phase release . . . . . . . . . . . . . . . . . . 90
5.4.1.5 Decide on phase release. . . . . . . . . . . . . . . . . . . . . . 91
5.4.1.6 Decide on project discontinuation. . . . . . . . . . . . . . . . . 93
5.4.1.7 Decide on project closure . . . . . . . . . . . . . . . . . . . . . . 95
5.4.1.8 Decide on project initiation release . . . . . . . . . . . . . . . . . 96
5.4.1.9 Decide on release. . . . . . . . . . . . . . . . . . . . . . . . . . 97
5.4.1.10 Decide on contract award . . . . . . . . . . . . . . . . . . . . . . 98
5.4.2 Decision-making tasks of management. . . . . . . . . . . . . . . . . . . 99
5.4.2.1 Decide on acceptance of migration. . . . . . . . . . . . . . . . 99
5.4.2.2 Decide on acceptance . . . . . . . . . . . . . . . . . . . . . . . . 100
5.4.2.3 Decide on ISDP concept. . . . . . . . . . . . . . . . . . . . . . 101
5.4.2.4 Decide on solution architecture . . . . . . . . . . . . . . . . . . . 102
5.4.2.5 Decide on product concept. . . . . . . . . . . . . . . . . . . . . 103
5.4.2.6 Decide on preliminary acceptance. . . . . . . . . . . . . . . . . 103
5.4.2.7 Decide on next steps. . . . . . . . . . . . . . . . . . . . . . . . 104
5.4.3 Other tasks. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 105
5.4.3.1 Decommission the legacy system. . . . . . . . . . . . . . . . . 105
5.4.3.2 Manage changes. . . . . . . . . . . . . . . . . . . . . . . . . . 106
5.4.3.3 Evaluate tenders . . . . . . . . . . . . . . . . . . . . . . . . . . . 107
5.4.3.4 Issue call for tenders. . . . . . . . . . . . . . . . . . . . . . . . 108
5.4.3.5 Prepare call for tenders. . . . . . . . . . . . . . . . . . . . . . . 109
5.4.3.6 Prepare procurement analysis. . . . . . . . . . . . . . . . . . . 110
5.4.3.7 Activate operation. . . . . . . . . . . . . . . . . . . . . . . . . . 112
5.4.3.8 Realize operation. . . . . . . . . . . . . . . . . . . . . . . . . . 113
5.4.3.9 Design operating concept . . . . . . . . . . . . . . . . . . . . . . 113
5.4.3.10 Draw up project execution order. . . . . . . . . . . . . . . . . . 114
5.4.3.11 Design deployment concept. . . . . . . . . . . . . . . . . . . . 115
234/244

* * *

5.4.3.12 Execute deployment measures . . . . . . . . . . . . . . . . . . . 117
5.4.3.13 Realize deployment measures. . . . . . . . . . . . . . . . . . . 117
5.4.3.14 Design integration concept. . . . . . . . . . . . . . . . . . . . . 118
5.4.3.15 Design ISDP concept. . . . . . . . . . . . . . . . . . . . . . . . 119
5.4.3.16 Implement ISDP concept. . . . . . . . . . . . . . . . . . . . . . 119
5.4.3.17 Transfer ISDP concept. . . . . . . . . . . . . . . . . . . . . . . 120
5.4.3.18 Agree on and steer goods/services. . . . . . . . . . . . . . . . 121
5.4.3.19 Prepare solution requirements. . . . . . . . . . . . . . . . . . . 123
5.4.3.20 Prepare solution architecture . . . . . . . . . . . . . . . . . . . . 124
5.4.3.21 Conduct migration . . . . . . . . . . . . . . . . . . . . . . . . . . 125
5.4.3.22 Design migration concept . . . . . . . . . . . . . . . . . . . . . . 126
5.4.3.23 Realize migration procedure. . . . . . . . . . . . . . . . . . . . 127
5.4.3.24 Activate organization. . . . . . . . . . . . . . . . . . . . . . . . 127
5.4.3.25 Implement organization. . . . . . . . . . . . . . . . . . . . . . . 128
5.4.3.26 Establish organizational requirements . . . . . . . . . . . . . . . 129
5.4.3.27 Draw up organization concept. . . . . . . . . . . . . . . . . . . 130
5.4.3.28 Prepare phase release. . . . . . . . . . . . . . . . . . . . . . . 131
5.4.3.29 Deal with problems and benefit from lessons learned. . . . . . 132
5.4.3.30 Activate product. . . . . . . . . . . . . . . . . . . . . . . . . . . 133
5.4.3.31 Realize product. . . . . . . . . . . . . . . . . . . . . . . . . . . 134
5.4.3.32 Design product concept . . . . . . . . . . . . . . . . . . . . . . . 135
5.4.3.33 Manage and control project . . . . . . . . . . . . . . . . . . . . . 135
5.4.3.34 Steer project. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 137
5.4.3.35 Prepare project closure. . . . . . . . . . . . . . . . . . . . . . . 139
5.4.3.36 Draw up project management plan . . . . . . . . . . . . . . . . . 140
5.4.3.37 Carry out prototyping. . . . . . . . . . . . . . . . . . . . . . . . 141
5.4.3.38 Perform quality assurance. . . . . . . . . . . . . . . . . . . . . 142
5.4.3.39 Analyze legal basis. . . . . . . . . . . . . . . . . . . . . . . . . 143
5.4.3.40 Prepare release closure . . . . . . . . . . . . . . . . . . . . . . . 144
5.4.3.41 Manage risks . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 145
5.4.3.42 Analyze protection needs . . . . . . . . . . . . . . . . . . . . . . 146
5.4.3.43 Manage and inform stakeholders . . . . . . . . . . . . . . . . . . 146
5.4.3.44 Advocate stakeholder interests . . . . . . . . . . . . . . . . . . . 148
5.4.3.45 Prepare study. . . . . . . . . . . . . . . . . . . . . . . . . . . . 148
5.4.3.46 Activate system. . . . . . . . . . . . . . . . . . . . . . . . . . . 150
5.4.3.47 Integrate the system into operation. . . . . . . . . . . . . . . . 151
5.4.3.48 Realize system . . . . . . . . . . . . . . . . . . . . . . . . . . . . 152
5.4.3.49 Prepare system integration. . . . . . . . . . . . . . . . . . . . . 153
5.4.3.50 Conduct test. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 153
5.4.3.51 Realize test infrastructure . . . . . . . . . . . . . . . . . . . . . . 154
5.4.3.52 Transfer test infrastructure. . . . . . . . . . . . . . . . . . . . . 155
5.4.3.53 Design test concept. . . . . . . . . . . . . . . . . . . . . . . . . 156
5.4.3.54 Draw up agreement. . . . . . . . . . . . . . . . . . . . . . . . . 157
158
6.1 Introduction. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 158
6.1.1 Role model. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 158
6.1.2 Core organization. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 158
6.1.3 Project organization. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 159
6.1.3.1 Overview. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 159
6.1.3.2 Partner groups . . . . . . . . . . . . . . . . . . . . . . . . . . . . 159
6.1.3.3 Hierarchy levels. . . . . . . . . . . . . . . . . . . . . . . . . . . 160
235/244

* * *

6.1.3.4 Project roles in programs 160

6.2 Overview of roles 163
6.2.1 Standard roles 163
6.2.2 Customized roles 164
6.2.3 Role assignment 164
6.2.3.1 General explanations 164
6.2.3.2 Steering 164
6.2.3.3 Management 165
6.2.3.4 Execution 165

6.3 Explanation regarding role description 166

6.4 Description of the roles 166
6.4.1 Steering roles 166
6.4.1.1 Project sponsor 166
6.4.1.2 Project committee 171
6.4.1.3 Quality and risk manager 172

6.4.2 Management roles 173
6.4.2.1 Technical committee 173
6

* * *

7.4.5.2 Initial planning of solution development. . . . . . . . . . . . . . 209
7.4.5.3 Planning in traditional solution development. . . . . . . . . . . 210
7.4.5.4 Planning in agile solution development. . . . . . . . . . . . . . 211
7.4.6 Implementation units under traditional approach. . . . . . . . . . . . . . 211
7.4.7 Application with other methods and practices. . . . . . . . . . . . . . . . 212
7.4.8 Integration of HERMES into the core organization. . . . . . . . . . . . . 213
7.4.8.1 General . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 213
7.4.8.2 Procedure. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 214
7.4.8.3 Adapting the method. . . . . . . . . . . . . . . . . . . . . . . . 214
Vocabulary **216**

Contents **230**

List of Tables **238**

List of Figures **240**

Index **241**

237/244

* * *

List of Tables

1 HERMES phases for projects with traditional and agile solution development . . . . 17
2 Standard scenarios for projects with various characteristics including modules. . . 25
3 Standard modules assigned to project phases. . . . . . . . . . . . . . . . . . . . . 33
4 Project steering module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . 35
5 Project management module tasks and outcomes . . . . . . . . . . . . . . . . . . . 36
6 Project foundations module tasks and outcomes . . . . . . . . . . . . . . . . . . . . 37
7 Procurement module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . . . 38
8 Organization module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . . . 38
9 Product module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . 39
10 IT system module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . 40
11 Tests module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40
12 Deployment organization module tasks and outcomes . . . . . . . . . . . . . . . . . 41
13 IT migration module tasks and outcomes. . . . . . . . . . . . . . . . . . . . . . . . 42
14 IT operation module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . . . 43
15 ISDP module tasks and outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43
16 Overview of outcomes - documents. . . . . . . . . . . . . . . . . . . . . . . . . . . 46
17 Overview of outcomes - states . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 47
18 Assignment of all tasks to project phases, including corresponding outcomes . . . . 87
19 Roles and their assignment to the hierarchy level and the partner group . . . . . . . 163
20 Tasksforwhichtheprojectsponsorisresponsibleandotherrolesinvolvedincreating
the outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 171
21 Tasks for which the project management is responsible and other roles involved in
creating the outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 181
22 Tasks for which the user representative is responsible and other roles involved in
creating the outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 185
23 Tasks for which the operations manager is responsible and other roles involved in
creating the outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 187
24 Tasks for which the business analyst is responsible and other roles involved in creating the outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 188
25 Tasks for which the developer is responsible and other roles involved in creating the
outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 190
26 TasksforwhichtheISDPmanagerisresponsibleandotherrolesinvolvedincreating
the outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 192
27 Tasks for which the IT architect is responsible and other roles involved in creating
the outcomes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 193
28 Tasks for which the test manager is responsible and other roles involved in creating
the outcome. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 195
29 User information per category . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 196
30 HERMES phases vocabulary, 4 languages . . . . . . . . . . . . . . . . . . . . . . . 216
31 HERMES scenarios vocabulary, 4 languages . . . . . . . . . . . . . . . . . . . . . . 216
32 HERMES modules vocabulary, 4 languages . . . . . . . . . . . . . . . . . . . . . . . 217
238/244

* * *

HERMES outcomes vocabulary, 4 languages . . . . . . . . . . . . . . . . . . . . . . 224 HERMES tasks vocabulary, 4 languages. . . . . . . . . . . . . . . . . . . . . . . . 229 HERMES roles vocabulary, 4 languages . . . . . . . . . . . . . . . . . . . . . . . . . 229

239/244

* * *

List of Figures

1 Overview of the HERMES modules and the essential outcomes along the phases . 6
2 How HERMES project management works in practice . . . . . . . . . . . . . . . . . 8
3 Simultaneous management of projects and programs in a core organization . . . . . 10
4 HERMES project life cycle with phase model for traditional and agile approach . . . 11
5 Projects of a core organization with scenarios . . . . . . . . . . . . . . . . . . . . . . 12
6 A module is composed of outcomes and tasks . . . . . . . . . . . . . . . . . . . . . 12
7 Outcomes are at the heart of HERMES . . . . . . . . . . . . . . . . . . . . . . . . . 13
8 Phases and releases with milestones as quality gates . . . . . . . . . . . . . . . . . 13
9 Minimum roles to be filled: project sponsor, project management, and user representative. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
10 HERMES project life cycle. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
11 Outcome diagram of the initiation phase . . . . . . . . . . . . . . . . . . . . . . . . . 16
12 HERMES phase model for traditional and agile approaches . . . . . . . . . . . . . . 17
13 Milestones at the beginning and end of each phase and approval of interim releases 18
14 Milestones for traditional and agile IT development projects . . . . . . . . . . . . . . 19
15 Selection and application of the scenario suitable for the project. . . . . . . . . . . 24
16 Multiple modules with tasks and outcomes as the basis for a scenario . . . . . . . . 24
17 Application of standard and user-defined scenarios . . . . . . . . . . . . . . . . . . . 27
18 Modules in the context of the service/product development scenario . . . . . . . . . 28
19 Modules in the context of the service/product adaptation scenario. . . . . . . . . . 28
20 Modules in the context of the IT development scenario . . . . . . . . . . . . . . . . . 29
21 Modules in the context of the IT adaptation scenario . . . . . . . . . . . . . . . . . . 30
22 Modules in the context of the organizational adjustment scenario . . . . . . . . . . . 31
23 Overall context of available standard modules in HERMES . . . . . . . . . . . . . . 32
24 Core organization and project organization with minimum required roles (gray) . . . 158
25 Role assignment to hierarchy levels of a traditional or agile project organization . . . 160
26 Projects combined into programs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 161
27 Three possible basic variants of project organization . . . . . . . . . . . . . . . . . . 161
28 Two common ways to assign the portfolio in organizational terms . . . . . . . . . . . 199
29 Encapsulated reporting structure that is uniform in relation to the core organization . 201
30 HERMES offers traditional and hybrid project management . . . . . . . . . . . . . . 207
31 Phase model with agile development . . . . . . . . . . . . . . . . . . . . . . . . . . . 207
32 Traditional/agile development management - example options . . . . . . . . . . . . 207
33 Increasing knowledge/decreasing planning inaccuracy . . . . . . . . . . . . . . . . . 211
34 Implementation units overlapping in time using traditional approach. . . . . . . . . 212
35 Use of supplementary methods and practices . . . . . . . . . . . . . . . . . . . . . . 213

* * *

Index

Modules
Deployment organization, 41
ISDP, 43
IT migration, 41
IT operation, 42
IT system, 39
Organization, 38
Procurement, 37
Product, 38
Project foundations, 36
Project management, 35
Project steering, 34
Tests, 40
Outcomes
Acceptance checklist, 72
Acceptance milestone, 78
Acceptance report, 47
Agreement, 72
Business model description, 55
Change request, 48
Change status list, 48
Closure phase release checklist, 73
Closure phase release milestone, 79
Contract award checklist, 74
Contract award milestone, 80
Deployment concept, 54
Deployment measures carried out, 75
Deployment measures realized, 75
Detailed specifications, 53
Evaluation report, 54
Execution order, 53
Execution release checklist, 73
Execution release milestone, 78
Final project evaluation, 63
Integration and installation instructions,
56
Integration concept, 56
Interfaces realized, 77
ISDP concept, 57
ISDP concept checklist, 73
ISDP concept milestone, 79
ISDP concept transferred, 76
ISDP measures realized, 75
Launch of operation checklist, 73
Launch of operation milestone, 78
241/244

Legacy system removed, 75
Legal basis analysis, 67
Lessons learned, 61
List of management project decisions,
57
List of steering project decisions, 57
Migration acceptance checklist, 73
Migration acceptance milestone, 78
Migration carried out, 76
Migration concept, 58
Migration procedure realized, 76
Minutes, 64
Next steps checklist, 74
Next steps milestone, 80
Offer, 49
Operating concept, 52
Operating infrastructure realized, 75
Operating manual, 52
Operating organization realized, 75
Operation activated, 75
Organization activated, 76
Organization concept, 60
Organization description, 59
Organization implemented, 76
Organizational requirements, 59
Phase release checklist, 73
Phase release milestone, 79
Phase report, 60
Preliminary acceptance checklist, 74
Preliminary acceptance milestone, 80
Process description, 65
Procurement analysis, 51
Product activated, 76
Product concept, 61
Product concept checklist, 74
Product concept milestone, 79
Product developed or adapted, 76
Product documentation, 61
Project closure checklist, 74
Project closure milestone, 79
Project discontinuation checklist, 74
Project initiation order, 62
Project initiation release checklist, 74
Project initiation release milestone, 79
Project management plan, 62
Project status report, 64

* * *

Protection needs analysis, 67
Prototype documentation, 65
Prototype realized, 77
Publication, 66
QA and risk report, 66
Quote request, 59
Release checklist, 74
Release milestone, 79
Release report, 66
Review report, 65
Service level agreement, 67
Situation analysis, 68
Solution architecture, 58
Solution architecture checklist, 73
Solution architecture milestone, 79
Solution requirements, 57
Stakeholder interests, 69
Stakeholder list, 69
Study, 69
System activated, 77
System concept, 70
Systemdevelopedorparameterized,77
System integrated, 77
Tender checklist, 73
Tender documentation, 50
Tender milestone, 78
Tender report, 49
Test concept, 71
Test infrastructure realized, 77
Test infrastructure transferred, 78
Test report, 71
User manual, 49
Work order, 49

Phases

Business analyst, 187
Developer, 188
Execution organization, 191
ISDP manager, 191
IT architect, 192
Operations manager, 185
Project committee, 171
Project management, 173
Project sponsor, 166

Project support, 181
Quality and risk manager, 172
Sub-project manager, 181
Technical committee, 173
Test manager, 194
Tester, 193
User representative, 182

Scenarios

IT adaptation, 29
IT development, 29
Organizational adjustment, 30
Service/product adaptation, 28
Service/product development, 27

Tasks
Activate operation, 112
Activate organization, 127
Activate product, 133
Activate system, 150
Advocate stakeholder interests, 148
Agreeonandsteergoods/services,121
Analyze legal basis, 143
Analyze protection needs, 146
Carry out prototyping, 141
Conduct migration, 125
Conduct test, 153
Deal with problems and benefit from
lessons learned, 132
Decide on acceptance, 100
Decide on acceptance of migration, 99
Decide on call for tenders, 88
Decide on closure phase release, 90
Decide on contract award, 98
Decide on execution release, 89
Decide on ISDP concept, 101
Decide on launch of operation, 88
Decide on next steps, 104
Decide on phase release, 91
Decide on preliminary acceptance, 103
Decide on product concept, 103
Decide on project closure, 95
Decide on project discontinuation, 93
Decide on project initiation release, 96
Decide on release, 97
Decide on solution architecture, 102
Decommission the legacy system, 105
Design deployment concept, 115
Design integration concept, 118
Design ISDP concept, 119
Design migration concept, 126
Design operating concept, 113

* * *

Design product concept, 135 Design test concept, 156 Draw up agreement, 157 Draw up organization concept, 130 Draw up project execution order, 114 Draw up project management plan, 140 Establish organizational requirements, 129 Evaluate tenders, 107 Execute deployment measures, 117 Implement ISDP concept, 119 Implement organization, 128 Integratethesystemintooperation, 151 Issue call for tenders, 108 Manage and control project, 135 Manage and inform stakeholders, 146 Manage changes, 106 Manage risks, 145 Perform quality assurance, 142 Prepare call for tenders, 109 Prepare phase release, 131 Prepare procurement analysis, 110 Prepare project closure, 139 Prepare release closure, 144 Prepare solution architecture, 124 Prepare solution requirements, 123 Prepare study, 148 Prepare system integration, 153 Realize deployment measures, 117 Realize migration procedure, 127 Realize operation, 113 Realize product, 134 Realize system, 152 Realize test infrastructure, 154 Steer project, 137 Transfer ISDP concept, 120 Transfer test infrastructure, 155

243/244

* * *

# The project management method for products, services, digitalization, and organization.

HERMES can be applied immediately and offers:

- Modular structure for concrete project processes;
- Online tool for method support;
- Document templates, including checklists, for efficient project management;
- Scenarios for easier execution planning. HERMES is simple and understandable and provides:
- Clear task descriptions with activities;
- Concrete role descriptions for cross-organizational cooperation;
- Document templates for quick and clearly presented outcomes.

## HERMES as a management tool supports:

- The project sponsor with regard to governance and sustainability;
- The project and program manager with planning, checking, and management;
- The user representative and specialists with project execution;
- Management with the higher-level strategic steering of projects and programs. This reference manual is the standard for projects of the Federal Administration and many cantons, communes, and companies. HERMES is also the eCH standard for e-government projects and programs (eCH-0054). Program management as part of project management is dealt with in a separate appendix. HERMES is recommended for all types of programs and projects. HERMES covers all dimensions of modern program and project management, such as procurement management, stakeholder management, communication and reporting, risk and quality management, traditional and agile development, governance and sustainability. Moreover, program- and project-specific procedures are described.

# HERMES Online: [https://www.hermes.admin.ch](https://www.hermes.admin.ch/)