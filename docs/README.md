# OctoAcme Project Management Docs

This folder is the **single source of truth** for OctoAcme's project management processes. It exists to centralize team knowledge, accelerate onboarding, and give everyone a repeatable, consistent framework for delivering software—from the first idea through to retrospective.

Use these documents as living references during project work. When a process changes, update the relevant document and open an issue (see [Contributing](#contributing) below) so the change is visible to the whole team.

---

## OctoAcme Project Management at a Glance

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle that moves from **initiation** to **planning**, **execution**, **release**, and **close/retrospective**. Work begins when a new idea is ready to be explored: the team produces a **Project One-pager** (problem, SMART goal, success metrics), identifies stakeholders, outlines a high-level timeline and risks, and completes an explicit decision gate to approve moving into planning. Once approved, the planning phase translates the initiative into an actionable backlog by breaking work into shippable increments with clear acceptance criteria, estimating scope, defining a **Definition of Done**, and mapping dependencies and milestones into a release plan.

Clear ownership and cross-functional collaboration are central. The core roles include a **Project Manager (PM)** who coordinates delivery, schedule, risks, and communication; a **Product Manager (PdM / Product Lead)** who defines outcomes, prioritises the backlog, and measures success; **Developers** who implement and test features while surfacing technical risks; **QA/Testing** partners who validate acceptance and quality; and **Stakeholders** who provide input and approvals. These roles are reinforced through shared artefacts—charter/one-pager, backlog, acceptance criteria/Definition of Done, risk register, and retrospectives—so execution is transparent and doesn't rely on tribal knowledge.

Execution is run with a consistent team rhythm and visible workflow management. Teams use a project board (**Backlog → Ready → In Progress → In Review → QA → Done**) to track progress, supported by **daily standups** for blockers and dependencies, a **weekly delivery sync** for progress and risks, and demos/reviews at sprint or milestone boundaries. Risk and dependency management is handled via a simple **risk register** (impact, likelihood, owner, mitigation, status) and an escalation path that starts with team triage and can rise through PM/Product Lead to sponsor-level escalation for business-impacting issues. Stakeholder communication is structured through regular updates (weekly or milestone-based) using templates that call out progress, next steps, risks/blockers, and decisions needed.

Quality and release practices are built into the workflow rather than treated as a final step. OctoAcme emphasises **small pull requests** (ideally ≤ 400 lines), linking PRs to issues and acceptance criteria, and requiring CI checks (tests, linting, and security scanning) before review—plus at least one approval per the team's policy. Testing expectations include unit tests for new logic, integration tests where appropriate, and end-to-end smoke tests for critical flows prior to release, with manual QA when needed for feature acceptance. Releases follow a standardised checklist: ensure criteria are met, draft release notes, prepare rollback/mitigation plans, validate in staging with smoke tests, verify post-deploy, and communicate outcomes—backed by an incident/rollback playbook and a commitment to capture learnings through retrospectives and tracked improvement actions.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's end-to-end project management philosophy, guiding principles, and lifecycle stages. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Templates and guidance for kicking off a new project: one-pager, stakeholder identification, decision gate, and initial risk mapping. |
| [Project Planning](octoacme-project-planning.md) | How to translate an approved initiative into a backlog, estimate scope, define milestones, and establish the Definition of Done. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflow management: board conventions, standup format, delivery syncs, and progress reporting. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register format, escalation paths, and stakeholder communication cadences and templates. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release checklist, staging validation, rollback/incident playbook, and post-deploy verification steps. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, how to track improvement actions, and the feedback loop back into process docs. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for PM, Product Manager/Lead, Developers, QA/Testing, and Stakeholders. |

---

## Contributing

Found a gap or want to propose an update to a process document? Please open an issue using the **[Add / Update Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template. The template prompts you for the relevant document, a summary of the proposed change, and the reason it's needed, so reviewers have the context they need to give fast, informed feedback.

Once an issue is approved, create a PR that links back to it (e.g. `Closes #<issue-number>`) and request a review from the appropriate team member.
