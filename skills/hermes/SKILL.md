---
name: hermes
version: 2022.3.0
description: Apply the HERMES 2022 project management method (the Swiss Confederation standard) to plan and run a project end to end. Use when the user mentions HERMES, runs a Swiss public-sector or IT/organizational project, or asks about a HERMES scenario, phase, milestone, role, deliverable, or template.
metadata:
  hermes_edition: "2022 edition / 3rd printing (revised), 09.03.2026"
  source: "Federal Chancellery FCh, Digital Transformation and ICT Steering DTI"
  source_url: "https://www.hermes.admin.ch"
  ech_standard: "eCH-0054"
---

# HERMES Project Management

HERMES is the outcome-oriented project and program management method of the Swiss Confederation (HERMES 2022). It gives every project the same backbone: phases bounded by milestone quality gates, built from reusable modules, packaged into scenarios, scaled by sizing and tailoring, staffed by three role levels, and driven toward defined deliverables (called outcomes).

This skill lets you set up a HERMES project, decide the approach, plan the phases and roles, and generate the required documents. It carries the full method as reference files plus a markdown template for every deliverable and checklist.

For anything beyond the summaries below, open the matching reference file. Do not guess HERMES specifics: the catalogs are exhaustive, so look them up.

## The model in one minute

- **Two approaches.** Traditional (five phases) or agile (three phases). The choice is made in Initiation and must be justified. See [references/method-foundations.md](references/method-foundations.md).
- **Phases.** Traditional: Initiation, Concept, Implementation, Deployment, Closure. Agile: Initiation, Execution, Closure. Initiation and Closure are always present and identical across approaches. See [references/phases-and-milestones.md](references/phases-and-milestones.md).
- **Milestones.** Every phase boundary and every decision task ends in a milestone, a quality gate where outcomes are accepted and the sponsor releases resources for the next step.
- **Modules.** Reusable building blocks of related outcomes and tasks (Project steering, Project management, Project foundations, Procurement, Organization, Product, IT system, Tests, Deployment organization, IT migration, IT operation, ISDP).
- **Scenarios.** A template for a project type that bundles the right modules. Five standard scenarios: Service/product development, Service/product adaptation, IT development, IT adaptation, Organizational adjustment. See [references/scenarios-sizing-tailoring.md](references/scenarios-sizing-tailoring.md).
- **Sizing then tailoring.** Sizing scales the scenario to the project value (project size); tailoring adds or removes modules, tasks, and outcomes. The minimum required documents and the four mandatory modules (Project steering, Project management, Project foundations, Deployment organization) can never be removed.
- **Roles.** Three levels: Steering, Management, Execution. The three indispensable roles are project sponsor (steering), project management (management), and user representative (execution, who is the product owner under agile). See [references/roles.md](references/roles.md).
- **Deliverables (outcomes).** About 54 documents plus checklists, states, and milestones. Each task produces specific outcomes. See [references/deliverables.md](references/deliverables.md) and [references/tasks.md](references/tasks.md).

## Running a HERMES project

1. **Initiation.** Run the study: set objectives, rough requirements, and solution options. Analyze legal basis, protection needs, and procurement as needed. Make the decision on next steps (solution option, approach traditional or agile, scenario, project value). Draw up the project management plan and execution order. The phase ends at the execution release, where the sponsor releases solution development.
2. **Size and tailor.** From the study, select the scenario, run sizing to scale it to the project value, then tailor it. Record the result in the project management plan and the execution structure plan. Full procedure in [references/scenarios-sizing-tailoring.md](references/scenarios-sizing-tailoring.md).
3. **Concept** (traditional). Establish organizational and solution requirements and the concepts and solution architecture (product concept, system concept, ISDP concept, operating concept, deployment concept, migration concept, test concept). Pass the decision gates (solution architecture, product concept, ISDP concept) and the phase release.
4. **Implementation** (traditional). Develop or parameterize the system, realize the product, the organization, interfaces, migration procedure, operating organization, and ISDP measures; run tests; reach preliminary acceptance, then the phase release.
5. **Deployment** (traditional). Execute deployment measures, carry out migration, activate the organization, product, and system, activate operation, accept migration and the solution, decide on launch of operation, then the closure phase release.
6. **Closure.** Complete and hand over documentation, transfer the test infrastructure, decommission the legacy system, transfer the ISDP concept, compile the final project evaluation and lessons learned, then the project closure decision.

Agile projects replace steps 3 to 5 with a single **Execution** phase that delivers the solution in iterative releases, each optionally gated by a release decision. Steering, governance, and the Initiation and Closure phases stay the same.

At every gate, use the matching checklist in [templates/](templates/README.md). Throughout, the project management module runs continuously: manage and control the project, manage risks, changes, stakeholders, quality, problems, and lessons learned.

## Reference files

Open these on demand; each is an exhaustive catalog.

- [references/method-foundations.md](references/method-foundations.md): philosophy, the two approaches, the phase model, the module catalog, role levels, and how the pieces fit.
- [references/scenarios-sizing-tailoring.md](references/scenarios-sizing-tailoring.md): the five standard scenarios with their modules, plus the full sizing and tailoring procedure and checklist.
- [references/phases-and-milestones.md](references/phases-and-milestones.md): each phase in detail, plus the complete milestone and state catalogs.
- [references/roles.md](references/roles.md): every role by level, with mission, responsibilities, powers, skills, owned tasks, and deliverables, and the responsibility model.
- [references/tasks.md](references/tasks.md): every task by module, with phase, responsible role, involved roles, outcomes, and purpose.
- [references/deliverables.md](references/deliverables.md): every document and checklist with its purpose and contents.
- [references/governance-and-agile.md](references/governance-and-agile.md): project governance, change control, rolling-wave planning, implementation units, agile development management, reporting, and program management.
- [references/hermes-2022-reference-manual.md](references/hermes-2022-reference-manual.md): the full official reference manual (HERMES 2022 edition, 3rd printing revised, 09.03.2026). The only source for sustainability, financial steering and funding, integrating HERMES into the core organization, and combining HERMES with other methods; also the fallback for anything not covered by the distilled files above.

## Templates

[templates/](templates/README.md) holds a markdown template for every HERMES deliverable and checklist (69 in total), converted from the official HERMES 2022 templates. Each keeps the official section structure and fill-in guidance (shown in quote blocks). To produce a document: open its template, replace every `[ ... ]` placeholder, follow the embedded guidance, and delete the guidance and unused rows before delivery. Cross-check the document purpose in [references/deliverables.md](references/deliverables.md) and the producing task in [references/tasks.md](references/tasks.md).

## Working principles

- HERMES is outcome-oriented: plan and steer by the outcomes (deliverables), not by activity.
- Keep the four mandatory modules and the minimum required documents in every project, however small.
- Decisions belong to the steering level (sponsor); management plans and controls; execution delivers. Keep the three indispensable roles filled.
- Adapt the method to the project with sizing and tailoring; never inflate a small project to the full scope.
- The authoritative source is the official method at https://www.hermes.admin.ch.
