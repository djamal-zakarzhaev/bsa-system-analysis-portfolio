# Business & Systems Analysis Learning Portfolio

A portfolio of 14 School 21 business and systems analysis assignments, developed around two recurring case studies: an online barbershop booking service and an order-delivery service.

The repository shows a progression from problem decomposition and stakeholder analysis through requirements, domain and process modeling, interaction design, non-functional requirements, and requirements management. Deliverables are primarily in Russian; every module retains the original English and Russian assignment brief.

> **Portfolio scope:** this is an educational case study, not a production system. The repository contains analysis artifacts and interface wireframes—not application source code, a deployed product, or automated acceptance tests.

## What this portfolio demonstrates

- stakeholder identification, needs analysis, and glossary management;
- As-Is / To-Be analysis, context diagrams, and data-flow modeling;
- requirements elicitation through role play, workshops, and brainstorming;
- domain modeling, CRUD analysis, data dictionaries, and logical data models;
- DFD, swimlane, state, and BPMN modeling;
- user stories, use cases, alternate flows, and role-based access rules;
- interface inventories, key scenarios, wireframes, field rules, and controls;
- measurable non-functional requirements for performance, availability, scalability, localization, and security;
- requirements registration and positive/negative test-case design.

## Selected artifacts

### Logical data model

![Logical data model for the barbershop booking case](BSA04_Domains.ID_1361447-1-develop/src/ex03_BRS_model.png)

Editable source: [`ex03_BRS_model.drawio`](BSA04_Domains.ID_1361447-1-develop/src/ex03_BRS_model.drawio)

### Level-0 data-flow diagram

![Level-0 DFD for the barbershop booking case](BSA05_Diagrams.ID_1361446-1-develop/src/BRS/ex00_BRS_dfd.png)

### Manager interface wireframe

![Manager main-menu wireframe](BSA11_UserInterfaces.ID_1361457-Team_TL_joelleet.6f9d1128_4541_4165-1-develop/src/Ex05/assets/fig_03_scr_mg_01.png)

The UI module includes 22 linked wireframes for manager, specialist, and client flows.

## Learning path

| Module | Topic | Evidence in `src/` |
|---|---|---|
| BSA00 | Decomposition and analyst foundations | information-source registers, glossaries, decomposition exercises |
| BSA01 | Stakeholders | stakeholder register, onion diagram, needs/problems matrix, glossary |
| BSA02 | Requirements foundations | As-Is actions, context diagram, To-Be changes, data flows |
| BSA03 | Requirements elicitation | role-play, brainstorming, workshop, and vision artifacts |
| BSA04 | Domain modeling | entity catalogs, CRUD matrix, data dictionaries, editable logical models |
| BSA05 | Analysis diagrams | DFD, swimlane, extended swimlane, state diagrams, state tables |
| BSA06 | Business processes and BPMN | process inventory, discussions, process descriptions, BPMN diagrams, review matrix |
| BSA07 | User stories | role-oriented stories and a coordination record |
| BSA08 | Use cases | six documents covering descriptions, main flows, and alternate flows |
| BSA09 | Objects, references, and roles | entity specifications and evolving class diagrams |
| BSA10 | Functional requirements | lifecycle/status models, CRUD behavior, operation detail, access matrix |
| BSA11 | User interaction design | interface catalog, scenarios, 22 wireframes, validation and control rules |
| BSA12 | Non-functional requirements | performance, reliability, scalability, localization, and security attributes |
| BSA13 | Requirements management | requirement records, traceable IDs, test cases, and task-tool screenshots |

For direct links to every module, its brief, and its main deliverables, see the [artifact catalog](docs/artifact-catalog.md).

## How to review

1. Start with BSA01–BSA02 to see the business context, stakeholders, problems, and target-state framing.
2. Continue with BSA04–BSA06 for data, behavior, and business-process models.
3. Review BSA07–BSA10 for user and system requirements with lifecycle and access detail.
4. Finish with BSA11–BSA13 for interaction design, quality attributes, traceability, and test cases.

The original assignment structure is intentionally preserved. In each module:

- `README.md` and `README_RUS.md` contain the assignment brief;
- `src/` contains the submitted work;
- `materials/` and `misc/` contain course references and illustrations.

## Tools and formats

The portfolio uses Markdown, Microsoft Word, Excel, PDF, PNG, and editable Draw.io sources. The artifacts apply BPMN, DFD, swimlane, state, context, onion, CRUD, logical data-model, user-story, use-case, and wireframing techniques.

No build is required. Open Markdown and PNG files directly on GitHub; use Microsoft Office or a compatible suite for `.docx` / `.xlsx`, and Draw.io for `.drawio` files.

## Status and limitations

- All 14 module folders contain submission artifacts matching the exercise groups in their assignment briefs.
- The repository has been checked for readable Office containers, PDF readability, image rendering, duplicate content, local Markdown links, and obvious secret-file patterns.
- Some modules were team assignments, as indicated by `Team` in their preserved folder names. This portfolio does not present those artifacts as sole-authored work.
- Assessment grades and formal stakeholder approval are not included, so the repository does not claim either.
- There is no executable application or automated test suite; validation here checks artifact integrity and repository presentation.

## Repository notes

The course folders contain a minimal `School 21 License` marker supplied with the assignments. No broader root-level license is asserted. Review the license marker in the relevant module before reusing an artifact.

