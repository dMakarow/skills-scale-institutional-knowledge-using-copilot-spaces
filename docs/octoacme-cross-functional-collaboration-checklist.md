# OctoAcme — Cross-Functional Collaboration Checklist

## Purpose
Provide a phase-by-phase reference for cross-functional collaboration, ensuring all roles are engaged at the right moment and critical handoffs are not missed. Use this checklist alongside the [Roles & Personas](octoacme-roles-and-personas.md) document.

---

## Phase 1 — Initiation

| # | Action | Primary Owner | Supporting Roles |
|---|--------|--------------|-----------------|
| 1.1 | Draft Project One-pager (problem, goal, success metrics) | Project Manager | Product Manager |
| 1.2 | Identify stakeholders and communication plan | Project Manager | Product Manager, Business Analyst |
| 1.3 | Gather initial business requirements and constraints | Business Analyst | Product Manager |
| 1.4 | Confirm team roles and assign named owners for each role | Project Manager | All roles |
| 1.5 | Conduct decision gate review (go/no-go to planning) | Project Manager | Product Manager, Stakeholders |

**Checklist (Initiation)**
- [ ] One-pager drafted and reviewed by Product Manager
- [ ] Stakeholder list completed; communication plan agreed
- [ ] Initial requirements captured by Business Analyst
- [ ] All key roles identified and named owners confirmed
- [ ] Go/no-go decision documented

---

## Phase 2 — Planning

| # | Action | Primary Owner | Supporting Roles |
|---|--------|--------------|-----------------|
| 2.1 | Run backlog refinement; create stories with acceptance criteria | Product Manager | Business Analyst, Scrum Master |
| 2.2 | Produce UX wireframes / prototypes for key flows | UX Designer | Product Manager, Developers |
| 2.3 | Validate acceptance criteria and use cases | Business Analyst | QA/Testing, Developers |
| 2.4 | Estimate scope and define Definition of Done | Scrum Master | Developers, Product Manager |
| 2.5 | Build release plan and milestone map | Project Manager | Release Manager, Product Manager |
| 2.6 | Populate risk register; identify cross-team dependencies | Project Manager | Business Analyst, Release Manager |
| 2.7 | Align support team on upcoming scope and timeline | Project Manager | Support/Customer Success Lead |

**Checklist (Planning)**
- [ ] Backlog prioritized; all stories have clear acceptance criteria
- [ ] UX designs reviewed and accepted by Product Manager and Developers
- [ ] Acceptance criteria sign-off from Business Analyst and QA/Testing
- [ ] Definition of Done documented and agreed by team
- [ ] Release plan and milestones confirmed with Release Manager
- [ ] Risk register populated with owners and mitigations
- [ ] Support/Customer Success Lead briefed on planned scope

---

## Phase 3 — Execution

| # | Action | Primary Owner | Supporting Roles |
|---|--------|--------------|-----------------|
| 3.1 | Facilitate daily standups and track blockers | Scrum Master | Developers, Project Manager |
| 3.2 | Implement features per design specs and acceptance criteria | Developers | UX Designer, Business Analyst |
| 3.3 | Review implemented features for design fidelity | UX Designer | Developers |
| 3.4 | Validate features against acceptance criteria (QA) | QA/Testing | Business Analyst, Developers |
| 3.5 | Escalate impediments or scope changes to Project Manager | Scrum Master / Business Analyst | Project Manager |
| 3.6 | Update risk register and stakeholder status reports | Project Manager | Scrum Master, Release Manager |
| 3.7 | Conduct sprint reviews and demos | Scrum Master | All roles |

**Checklist (Execution)**
- [ ] Daily standups running; blockers captured and resolved promptly
- [ ] Features reviewed for design fidelity by UX Designer before QA
- [ ] All acceptance criteria validated by QA/Testing and Business Analyst
- [ ] Impediments escalated and resolved in a timely manner
- [ ] Risk register reviewed at weekly sync; status reports sent to stakeholders
- [ ] Sprint demos completed with stakeholder feedback captured

---

## Phase 4 — Release

| # | Action | Primary Owner | Supporting Roles |
|---|--------|--------------|-----------------|
| 4.1 | Conduct release readiness review (go/no-go) | Release Manager | Project Manager, QA/Testing |
| 4.2 | Draft and distribute release notes | Release Manager | Product Manager, Support/Customer Success Lead |
| 4.3 | Deploy to staging and run smoke tests | Release Manager | Developers, QA/Testing |
| 4.4 | Confirm support team readiness for post-release | Release Manager | Support/Customer Success Lead |
| 4.5 | Deploy to production and run post-deploy verifications | Release Manager | Developers |
| 4.6 | Announce release to stakeholders | Project Manager | Release Manager, Product Manager |
| 4.7 | Monitor for post-deploy incidents | Support/Customer Success Lead | Release Manager, Developers |

**Checklist (Release)**
- [ ] Release readiness review completed; go/no-go decision documented
- [ ] Release notes drafted and reviewed by Product Manager
- [ ] Staging deployment validated with smoke tests
- [ ] Support/Customer Success Lead confirmed ready for post-release
- [ ] Production deployment completed and post-deploy verification passed
- [ ] Release communicated to stakeholders
- [ ] Post-deploy monitoring in place; escalation path confirmed

---

## Phase 5 — Close & Retrospective

| # | Action | Primary Owner | Supporting Roles |
|---|--------|--------------|-----------------|
| 5.1 | Facilitate retrospective (what went well, what to improve) | Scrum Master | All roles |
| 5.2 | Collect and synthesize customer feedback post-launch | Support/Customer Success Lead | Product Manager |
| 5.3 | Document improvement actions and assign owners | Project Manager | Scrum Master |
| 5.4 | Feed customer insights back into product roadmap | Product Manager | Support/Customer Success Lead, Business Analyst |
| 5.5 | Update process docs based on lessons learned | Project Manager | All roles |

**Checklist (Close & Retrospective)**
- [ ] Retrospective completed; notes documented with action items
- [ ] Customer feedback summary shared with Product Manager
- [ ] Improvement actions tracked with named owners and target dates
- [ ] Product roadmap updated to reflect customer insights
- [ ] Relevant process documents updated

---

## RACI Summary

The table below provides a high-level RACI (Responsible, Accountable, Consulted, Informed) view across the five project phases. For full role definitions and interaction details, see [Roles & Personas](octoacme-roles-and-personas.md).

| Phase | Project Manager | Product Manager | Scrum Master | Developers | UX Designer | Business Analyst | Release Manager | Support Lead |
|-------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Initiation | **A/R** | C | — | I | — | C | I | I |
| Planning | **A/R** | R | R | C | R | R | C | I |
| Execution | **A** | C | R | R | R | C | I | I |
| Release | **A** | C | I | R | — | I | **R** | C |
| Close/Retro | **A/R** | R | R | C | C | C | I | R |

*Key: R = Responsible, A = Accountable, C = Consulted, I = Informed*

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
