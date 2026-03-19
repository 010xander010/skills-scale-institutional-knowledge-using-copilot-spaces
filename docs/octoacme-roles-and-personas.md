# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## UX Designer

### Role Summary
UX Designers ensure user needs are at the core of solution design. They advocate for usability and accessibility from inception through delivery, translating user insights into clear design artifacts that guide development.

### Responsibilities
- Lead user research and feedback sessions to surface needs and pain points
- Define wireframes, mockups, prototypes, and UX acceptance criteria
- Collaborate with the Product Manager on user journeys and personas
- Consult Developers and QA on implementation feasibility and testability
- Establish and maintain design standards and accessibility guidelines

### Goals
- Ensure every feature delivers an intuitive and accessible user experience
- Reduce usability defects discovered late in the cycle
- Align design decisions with user research and business objectives

### Typical Communication
- Design reviews and usability walkthroughs with the Product Manager and Developers
- Shared design assets and annotated mockups in a design repository
- Accessibility and UX acceptance criteria added to backlog items

### Interaction with Existing Roles
- **Developers**: Provides design assets, prototypes, and interaction specifications; consults on technical constraints; reviews implemented UI against design specs.
- **Product Managers**: Partners closely to align user needs with business goals and co-defines acceptance criteria for user-facing features.
- **Project Managers**: Flags design dependencies and timeline needs; attends planning sessions to ensure design work is accounted for in schedules.
- **Stakeholders**: Presents research findings and design concepts; gathers feedback to validate direction before development begins.
- **QA**: Provides UX acceptance criteria and participates in usability reviews; supports QA in identifying visual and interaction regressions.

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and coach the team on continuous process improvements. They create an environment where the team can deliver effectively and sustainably.

### Responsibilities
- Organize and run sprints, daily standups, sprint planning, retrospectives, and reviews
- Identify and remove blockers that impede team progress
- Shield the team from external interruptions and scope creep during sprints
- Track sprint progress and surface risks early
- Foster a culture of continuous improvement and psychological safety

### Goals
- Enable the team to achieve consistent, predictable delivery velocity
- Eliminate recurring impediments through root-cause resolution
- Ensure agile practices are understood and applied effectively

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment log updates shared with the Project Manager
- Retrospective action items tracked and followed up each sprint

### Interaction with Existing Roles
- **Developers**: Acts as a servant-leader and coach; removes day-to-day blockers; ensures the team has clarity on sprint goals.
- **Product Managers**: Coordinates backlog refinement and ensures the product backlog is ready for planning; escalates priority conflicts.
- **Project Managers**: Partners on delivery cadence, milestone alignment, and escalation paths for cross-team dependencies.
- **Stakeholders**: Manages expectations around sprint scope and change requests; communicates progress at sprint reviews.
- **QA**: Ensures QA activities are planned within the sprint; surfaces testing bottlenecks as impediments when they threaten sprint goals.

---

## Solution Architect

### Role Summary
Solution Architects own the high-level technical vision of the project. They make architecture decisions that ensure the solution is scalable, reliable, maintainable, and aligned with organizational standards.

### Responsibilities
- Develop and maintain system architecture documentation and decision records (ADRs)
- Evaluate technology trade-offs and select appropriate stacks and patterns
- Guide Developers in adhering to architectural standards and best practices
- Identify technical risks and propose mitigation strategies
- Assist the Product Manager in scoping and validating technical feasibility

### Goals
- Deliver a coherent, sustainable technical architecture that supports long-term product growth
- Minimize technical debt introduced through poor design decisions
- Ensure architecture decisions are documented and understood across the team

### Typical Communication
- Architecture review sessions with Developers and Project/Product Managers
- Architecture Decision Records (ADRs) maintained in the project repository
- Technical feasibility input during planning and refinement sessions

### Interaction with Existing Roles
- **Developers**: Provides architectural guidance, reviews designs for alignment with standards, and serves as an escalation point for complex technical decisions.
- **Product Managers**: Advises on technical feasibility, estimates complexity of proposed features, and flags architectural implications of product decisions.
- **Project Managers**: Surfaces technical risks and dependencies that affect project timelines; contributes to the risk register.
- **Stakeholders**: Communicates technical direction and constraints in business-accessible terms during milestone reviews.
- **QA**: Identifies non-functional requirements (performance, security, scalability) that QA should validate; ensures test environments mirror production architecture.

---

## Technical Writer

### Role Summary
Technical Writers ensure that documentation is clear, up-to-date, and tailored for both end users and developers. They maintain the accuracy and accessibility of all project documentation throughout the delivery lifecycle.

### Responsibilities
- Create and update technical and user-facing documentation (guides, API docs, release notes)
- Maintain process documents, changelogs, and runbooks
- Work with QA and Developers to accurately document feature behaviors and edge cases
- Assist Project and Product Managers with communication artifacts such as release announcements
- Review and improve documentation quality, consistency, and accessibility

### Goals
- Ensure every release is accompanied by complete, accurate documentation
- Reduce support burden by proactively documenting common questions and workflows
- Maintain a single source of truth for product and process documentation

### Typical Communication
- Collaborative editing and review cycles with Developers and QA before each release
- Documentation status updates included in sprint reviews
- Feedback loops with Product Manager and Stakeholders to validate documentation accuracy

### Interaction with Existing Roles
- **Developers**: Gathers technical details for API docs and feature documentation; reviews developer-written content for clarity and completeness.
- **Product Managers**: Aligns on user-facing messaging, feature descriptions, and release notes content.
- **Project Managers**: Incorporates documentation tasks into project schedules; ensures documentation is part of the Definition of Done.
- **Stakeholders**: Validates that user-facing documentation meets audience needs; incorporates feedback into revisions.
- **QA**: Collaborates on documenting test procedures, known issues, and feature behavior to support testing and end-user understanding.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

