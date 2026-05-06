# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers both core delivery roles and cross-functional roles that support modern software projects.

> For a summary of how these roles interact across the project lifecycle, see the [Interaction Map](#interaction-map) and [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md).

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master

### Role Summary
The Scrum Master serves the delivery team by facilitating agile ceremonies, removing impediments, and ensuring Scrum best practices are consistently followed. They act as a coach—not a manager—helping the team continuously improve its process.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers and impediments that slow the team
- Shield the team from external interruptions during a sprint
- Coach team members on agile principles and Scrum practices
- Track and report team velocity, cycle time, and sprint health metrics
- Escalate systemic blockers to the Project Manager when they cannot be resolved at the team level

### Goals
- Maintain a healthy agile cadence and high team morale
- Reduce impediments and unplanned disruptions
- Foster a culture of continuous improvement

### Typical Communication
- Daily standup facilitation and blocker summaries
- Sprint retrospective notes and action item tracking
- Agile health metrics shared with the Project Manager

### Interaction with Existing Roles
- **Project Manager**: Aligns on delivery timelines and escalates team-level blockers that require cross-team coordination or resource decisions.
- **Product Manager**: Collaborates on backlog health, backlog refinement sessions, and ensuring stories are sprint-ready with clear acceptance criteria.
- **Developers**: Coaches on agile practices, removes impediments surfaced during standups, and facilitates estimation and planning sessions.

---

## UX Designer

### Role Summary
UX Designers are responsible for the end-to-end user experience—researching user needs, designing flows and interfaces, and validating usability before and after implementation. They bridge the gap between business requirements and a delightful, functional product.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity UI assets
- Define and maintain design systems, style guides, and component libraries
- Review implemented features for design fidelity and accessibility
- Document user flows and interaction specifications for developers
- Advocate for user needs during backlog prioritization and feature trade-offs

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce rework caused by late-stage usability issues
- Ensure design decisions are grounded in real user data

### Typical Communication
- Design reviews and prototype walkthroughs with Product Manager and Developers
- Annotated design files and user flow documents in the project repo
- Usability test reports shared with the Product Manager and stakeholders

### Interaction with Existing Roles
- **Product Manager**: Collaborates on feature priorities, problem framing, and validating that proposed solutions meet user needs before development begins.
- **Developers**: Provides detailed design specifications, answers implementation questions, and reviews completed features for design fidelity.
- **Project Manager**: Flags design-related scope changes or dependencies that may affect timeline or capacity.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They gather, document, and validate requirements, ensuring that what is built aligns with business objectives and can be verified through clear acceptance criteria.

### Responsibilities
- Elicit requirements from stakeholders through interviews, workshops, and document analysis
- Translate business needs into clear user stories, use cases, and acceptance criteria
- Maintain a requirements traceability matrix to track coverage
- Identify gaps, conflicts, or ambiguities in requirements early
- Support QA/Testing teams by clarifying acceptance criteria during test planning
- Facilitate requirement sign-off with stakeholders before development begins

### Goals
- Eliminate ambiguity in requirements before development starts
- Ensure complete and testable acceptance criteria for every backlog item
- Improve alignment between business expectations and delivered outcomes

### Typical Communication
- Requirements workshops and stakeholder interviews
- User stories, use case documents, and acceptance criteria shared in the project backlog
- Weekly alignment with the Product Manager and QA/Testing on open requirements questions

### Interaction with Existing Roles
- **Product Manager**: Works closely to refine and validate product requirements, ensuring business intent is accurately captured in the backlog.
- **Project Manager**: Flags requirements that introduce scope changes or new dependencies that may affect the project plan.
- **Developers**: Clarifies acceptance criteria, answers technical-business translation questions, and supports estimation sessions.

---

## Release Manager

### Role Summary
Release Managers own the end-to-end release process, coordinating across development, QA, and operations to ensure features are deployed safely, reliably, and on schedule. They act as the single point of accountability from release planning through post-deploy verification.

### Responsibilities
- Define and maintain the release calendar and deployment schedules
- Coordinate release readiness reviews with developers, QA, and operations teams
- Manage go/no-go decisions based on quality gates and risk assessments
- Oversee staging validation, production deployment, and post-deploy verification steps
- Draft and distribute release notes and stakeholder communications
- Maintain rollback and incident playbooks; trigger rollback when needed
- Capture lessons learned from each release and drive process improvements

### Goals
- Deliver releases safely, on schedule, and with minimal customer impact
- Reduce release failures and post-deploy incidents through rigorous process
- Increase release frequency and confidence over time

### Typical Communication
- Release readiness reviews and go/no-go meeting notes
- Release notes and stakeholder deployment announcements
- Incident reports and rollback notifications (when applicable)

### Interaction with Existing Roles
- **Project Manager**: Aligns release windows with the project plan, communicates schedule changes, and co-manages stakeholder expectations around delivery dates.
- **Developers**: Coordinates final code freeze, reviews CI/CD pipeline status, and confirms deployment readiness checklists are complete.
- **Support/Customer Success Lead**: Provides advance notice of upcoming releases, shares release notes, and coordinates post-release support readiness.

---

## Support / Customer Success Lead

### Role Summary
The Support / Customer Success Lead is the voice of the customer post-release. They manage customer-facing issues, collect and synthesize user feedback, and feed actionable insights back into the product roadmap and project planning process.

### Responsibilities
- Serve as the primary contact for customer-reported issues and inquiries post-launch
- Triage, prioritize, and escalate production incidents based on customer impact
- Collect, synthesize, and communicate user feedback and satisfaction trends
- Maintain and update customer-facing documentation, FAQs, and release notes
- Coordinate with the Release Manager on support readiness ahead of each release
- Provide the Product Manager and Project Manager with regular summaries of incident trends and improvement opportunities

### Goals
- Maximize customer satisfaction and retention post-launch
- Reduce incident resolution time through clear escalation and coordination
- Create a feedback loop that continuously improves the product and process

### Typical Communication
- Incident escalation reports and triage notes shared with the Project Manager and Release Manager
- Monthly customer satisfaction and feedback summaries shared with the Product Manager
- Support readiness confirmations prior to each release

### Interaction with Existing Roles
- **Product Manager**: Provides qualitative and quantitative customer feedback that informs backlog prioritization and product direction.
- **Project Manager**: Escalates high-impact production incidents and communicates ongoing support load that may affect resourcing or planning.
- **Release Manager**: Confirms support team readiness before releases and coordinates post-deploy monitoring and customer communication.

---

## Interaction Map

The table below summarizes the primary handoff and collaboration points between roles across the project lifecycle.

| From \ To              | Project Manager | Product Manager | Scrum Master | Developers | UX Designer | Business Analyst | Release Manager | Support Lead |
|------------------------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **Project Manager**    | — | Schedule & scope | Delivery status | Priorities & constraints | Timeline impacts | Scope changes | Release windows | Incident escalation |
| **Product Manager**    | Trade-offs & priorities | — | Backlog health | Feature specs | Problem framing | Requirements review | Release content | Feedback loops |
| **Scrum Master**       | Blocker escalation | Sprint health | — | Agile coaching | Sprint cadence | Refinement sessions | — | — |
| **Developers**         | Risks & status | Scope questions | Standup updates | — | Design clarification | AC questions | Deployment readiness | — |
| **UX Designer**        | Scope flags | Usability findings | — | Design specs | — | Requirement gaps | — | UX-related issues |
| **Business Analyst**   | Scope impacts | Requirements | Sprint-ready stories | AC clarification | Flow validation | — | Release scope | — |
| **Release Manager**    | Schedule updates | Release content | — | Code freeze coordination | — | — | — | Support readiness |
| **Support Lead**       | Incident reports | Feedback summaries | — | — | UX issues | — | Pre-release readiness | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) for a practical reference on how these roles collaborate at each project phase.

