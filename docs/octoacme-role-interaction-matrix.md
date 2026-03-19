# OctoAcme Role Interaction Matrix

## Purpose
This matrix provides a quick-reference guide to cross-functional interactions between roles on OctoAcme projects. Use it to understand key interaction points, dependencies, handoff expectations, communication frequency, and decision ownership.

---

## Interaction Summary Table

| | Project Manager | Product Manager | Developers | QA | UX Designer | Scrum Master | Solution Architect | Technical Writer |
|---|---|---|---|---|---|---|---|---|
| **Project Manager** | — | Weekly sync | Sprint planning & status | QA sign-off coordination | Design timeline alignment | Delivery cadence partnership | Risk & dependency escalation | Documentation schedule |
| **Product Manager** | Weekly sync | — | Backlog refinement & AC | Acceptance validation | User journey alignment | Sprint goal clarity | Feasibility input | Release notes review |
| **Developers** | Status updates & blockers | Backlog clarification | — | PR handoff & defect triage | Design implementation | Standup & impediment removal | Architecture guidance | Feature documentation input |
| **QA** | Milestone sign-off | Acceptance criteria | Defect reporting & retesting | — | UX acceptance review | Sprint blockers escalation | Non-functional requirements | Test procedure documentation |
| **UX Designer** | Timeline & capacity | Product alignment | Design handoff | Usability review | — | Sprint design tasks | Design feasibility | UX documentation |
| **Scrum Master** | Delivery cadence | Backlog readiness | Daily standup facilitation | Testing in sprint | Design in sprint | — | Technical impediments | Documentation in DoD |
| **Solution Architect** | Risk register input | Feasibility advising | Architecture guidance | Non-functional req. validation | Design constraints | Technical blockers | — | Architecture documentation |
| **Technical Writer** | Documentation in schedule | Release notes | Feature documentation | Test & issue documentation | UX copy & help text | Documentation in DoD | Architecture docs | — |

---

## Key Interaction Points & Dependencies

### Project Manager ↔ Product Manager
- **Interaction**: Weekly alignment on roadmap, scope changes, and stakeholder communications.
- **Dependency**: Product Manager provides prioritized backlog; Project Manager confirms capacity and timelines.
- **Decision Owner**: Product Manager owns *what* to build; Project Manager owns *when* and *how* to deliver.

### Product Manager ↔ UX Designer
- **Interaction**: Ongoing collaboration during discovery and feature definition phases.
- **Dependency**: UX Designer produces wireframes and prototypes; Product Manager validates against business goals.
- **Decision Owner**: Product Manager owns feature scope; UX Designer owns user experience quality.

### Product Manager ↔ Solution Architect
- **Interaction**: Feasibility reviews during planning; trade-off discussions for complex features.
- **Dependency**: Solution Architect advises on technical constraints before commitments are made.
- **Decision Owner**: Product Manager owns product direction; Solution Architect owns architectural decisions.

### Solution Architect ↔ Developers
- **Interaction**: Architecture reviews, design sessions, and ongoing technical guidance throughout implementation.
- **Dependency**: Developers implement against architectural standards; escalate design questions to Solution Architect.
- **Decision Owner**: Solution Architect owns architecture decisions; Developers own implementation details within those constraints.

### Scrum Master ↔ Project Manager
- **Interaction**: Regular coordination on sprint delivery, milestone alignment, and cross-team dependencies.
- **Dependency**: Scrum Master provides sprint progress data; Project Manager translates to stakeholder reporting.
- **Decision Owner**: Scrum Master owns agile process; Project Manager owns overall project governance.

### Developers ↔ QA
- **Interaction**: PR handoffs, defect triage, retesting cycles.
- **Dependency**: QA validates developer output against acceptance criteria before features are marked Done.
- **Decision Owner**: QA owns pass/fail decisions; Developers own defect remediation.

### UX Designer ↔ Developers
- **Interaction**: Design handoffs, implementation reviews, and accessibility validation.
- **Dependency**: Developers require finalized design specs before building UI; UX Designer reviews implementation against specs.
- **Decision Owner**: UX Designer owns design intent; Developers own technical implementation approach.

### Technical Writer ↔ All Roles
- **Interaction**: Information-gathering interviews, documentation reviews, and changelog updates throughout each sprint.
- **Dependency**: Technical Writer depends on all roles for accurate, timely input.
- **Decision Owner**: Technical Writer owns documentation quality and structure; subject-matter experts own content accuracy.

---

## Communication Frequency Recommendations

| Role Pair | Recommended Frequency | Primary Channel |
|---|---|---|
| Project Manager + Product Manager | Weekly | Sync meeting + shared project board |
| Project Manager + Scrum Master | Weekly or per-sprint | Sync meeting |
| Product Manager + UX Designer | Weekly during active design | Design reviews + async comments |
| Product Manager + Solution Architect | At planning milestones + as needed | Architecture review sessions |
| Solution Architect + Developers | Per sprint / ongoing | Design sessions + async (ADRs, PRs) |
| Scrum Master + Developers | Daily | Standup |
| Developers + QA | Per PR / daily during QA phase | PR comments + standup |
| UX Designer + Developers | Per sprint / per feature | Design handoff + async feedback |
| Technical Writer + Developers | Per feature / per release | Async (docs PRs, review comments) |
| Technical Writer + Product Manager | Per release | Review meetings + async |

---

## Decision Ownership Quick Reference

| Decision Area | Owner | Consulted | Informed |
|---|---|---|---|
| Product roadmap & priorities | Product Manager | Stakeholders, Solution Architect | All roles |
| Project timelines & milestones | Project Manager | Product Manager, Scrum Master | All roles |
| Architecture & technology choices | Solution Architect | Developers, Product Manager | Project Manager, QA |
| User experience & design | UX Designer | Product Manager, Developers | QA, Technical Writer |
| Agile process & ceremonies | Scrum Master | Project Manager | Developers, Product Manager |
| Feature acceptance (pass/fail) | QA | Developers, Product Manager | Project Manager |
| Documentation quality & structure | Technical Writer | All roles (content accuracy) | All roles |
| Sprint scope & sprint goal | Product Manager + Scrum Master | Developers | Project Manager, Stakeholders |
| Risk escalation | Project Manager | All roles | Stakeholders |

---

## Handoff Checklist Between Key Roles

### UX Designer → Developers
- [ ] Finalized wireframes/mockups shared in design repository
- [ ] Interaction specifications and edge cases documented
- [ ] Accessibility requirements listed
- [ ] UX acceptance criteria added to backlog items
- [ ] Design review session held with Developers before implementation begins

### Solution Architect → Developers
- [ ] Architecture Decision Record (ADR) created for significant decisions
- [ ] System architecture diagram updated
- [ ] Non-functional requirements (performance, security, scalability) documented
- [ ] Technology and library decisions documented with rationale

### Developers → QA
- [ ] PR includes issue link and acceptance criteria
- [ ] Automated tests written and passing in CI
- [ ] Feature behavior documented in PR description or linked doc
- [ ] Known limitations or edge cases called out

### QA → Release
- [ ] All acceptance criteria verified
- [ ] Regression suite passed
- [ ] Non-functional requirements validated (if applicable)
- [ ] Sign-off documented and communicated to Project Manager

### All Roles → Technical Writer
- [ ] Feature behavior and changes communicated before release
- [ ] API or interface changes documented or flagged
- [ ] Known issues and workarounds shared
- [ ] Documentation reviewed and approved before publishing
