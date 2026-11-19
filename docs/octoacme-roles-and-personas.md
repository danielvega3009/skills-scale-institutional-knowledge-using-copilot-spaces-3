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

## QA/Testing Lead

### Role Summary
The QA/Testing Lead establishes the test strategy and provides independent quality and acceptance validation across the project.

### Responsibilities
- Define test scope, coverage, tools, and entry/exit criteria
- Coordinate unit, integration, end-to-end, accessibility, and other applicable testing
- Identify quality risks and communicate their impact to delivery teams
- Validate that completed work meets acceptance criteria and the Definition of Done
- Maintain traceability between requirements, tests, defects, and release readiness

### Goals
- Prevent defects and detect regressions early
- Create consistent, repeatable release validation
- Provide clear evidence that acceptance criteria are met

### Interactions with existing roles
- Works with **Product Managers** to clarify acceptance criteria and quality expectations
- Partners with **Developers** on testability, automated coverage, debugging, and defect resolution
- Coordinates with **Project Managers** on testing schedules, risks, dependencies, and release decisions
- Shares quality status and escalates unresolved risks to stakeholders

---

## UX/Design Lead

### Role Summary
The UX/Design Lead represents users and ensures the solution is understandable, usable, accessible, and consistent with the product experience.

### Responsibilities
- Lead discovery of user needs and translate findings into flows, prototypes, and specifications
- Define interaction, visual, content, and accessibility requirements
- Facilitate design reviews and resolve usability trade-offs
- Validate that implemented experiences match agreed designs and acceptance criteria

### Goals
- Improve usability and customer outcomes
- Maintain a coherent experience across features and touchpoints
- Reduce design rework and accessibility gaps

### Interactions with existing roles
- Works with **Product Managers** to convert customer and business needs into design direction
- Partners with **Developers** to define feasible implementation details and review builds
- Collaborates with the **QA/Testing Lead** on usability and accessibility acceptance checks
- Informs **Project Managers** of design dependencies, decisions, and review milestones

---

## Security and Privacy Lead

### Role Summary
The Security and Privacy Lead establishes security and privacy expectations and provides specialist guidance for identifying, assessing, and mitigating risk.

### Responsibilities
- Define applicable security and privacy requirements
- Review designs and changes for threat, compliance, and data-handling risks
- Coordinate security testing, remediation, incident preparation, and required approvals
- Maintain relevant standards and raise unresolved risks to accountable decision-makers

### Goals
- Reduce security and privacy exposure
- Build compliance and protection into delivery rather than adding it at release
- Provide clear, actionable risk guidance

### Interactions with existing roles
- Advises **Developers** on secure design, implementation, dependency management, and remediation
- Works with **Product Managers** to evaluate risk, scope, and customer or regulatory trade-offs
- Partners with the **QA/Testing Lead** on security testing and validation
- Supports the **Project Manager** and release team with risk tracking and escalation

---

## Data and Analytics Lead

### Role Summary
The Data and Analytics Lead defines how project outcomes will be measured and ensures that teams make decisions from reliable evidence.

### Responsibilities
- Define success metrics and measurement plans
- Confirm instrumentation, data availability, and reporting requirements
- Analyze experiments, adoption, quality, and customer outcomes
- Recommend adjustments based on evidence and communicate limitations

### Goals
- Make outcomes measurable and comparable
- Improve prioritization through reliable insights
- Enable faster, evidence-based iteration

### Interactions with existing roles
- Partners with **Product Managers** to define outcome metrics and evaluation methods
- Works with **Developers** to instrument features and validate event or data quality
- Provides evidence to **Project Managers** for reporting, decisions, and risk reviews
- Presents findings to stakeholders and connects results to roadmap decisions

---

## Support and Operations Lead

### Role Summary
The Support and Operations Lead represents operational readiness, ongoing customer impact, and the ability to run and support the delivered solution.

### Responsibilities
- Identify support, monitoring, capacity, documentation, and on-call needs
- Prepare support knowledge, runbooks, escalation paths, and known limitations
- Feed production issues and customer feedback into prioritization
- Coordinate incident communication and operational follow-up

### Goals
- Improve operational readiness and customer experience
- Reduce time to detect and resolve production issues
- Turn operational learning into product and process improvements

### Interactions with existing roles
- Informs **Product Managers** and **Developers** about recurring issues, customer impact, and improvement opportunities
- Works with **Project Managers** on readiness dependencies, status, and incident escalation
- Coordinates with the **QA/Testing Lead** on smoke tests and support scenarios
- Collaborates with the release and security leads on deployment and incident response

---

## Release Coordinator

### Role Summary
The Release Coordinator owns the release-readiness process and coordinates a controlled, observable transition of approved changes into production.

### Responsibilities
- Confirm that acceptance criteria, testing, security checks, and approvals are complete
- Schedule deployment windows and coordinate participants and communications
- Maintain rollback and contingency plans
- Verify post-deployment health and communicate release outcomes

### Goals
- Reduce release risk and avoidable production disruption
- Create consistent, repeatable release execution
- Ensure stakeholders receive timely and accurate release information

### Interactions with existing roles
- Coordinates **Developers** and the **QA/Testing Lead** around code freeze, smoke tests, deployment, and validation
- Works with **Project Managers** on timing, risks, stakeholders, and communication
- Partners with Security and Privacy and Support and Operations leads on approvals, monitoring, and incident readiness
- Confirms **Product Manager** expectations for release scope and communication

---

## Executive Sponsor or Key Stakeholder

### Role Summary
The Executive Sponsor or designated key stakeholder provides organizational authority, resolves cross-functional constraints, and confirms that a project remains aligned with strategic and customer priorities.

### Responsibilities
- Approve major scope, investment, or priority changes
- Resolve escalations that exceed the team's authority
- Secure resources and remove organization-level blockers
- Sponsor transparency, adoption, and accountability

### Goals
- Maintain alignment with business outcomes and strategic priorities
- Enable timely decisions for high-impact issues
- Ensure teams can deliver and sustain the intended value

### Interactions with existing roles
- Provides decision context and approval to **Product Managers** and **Project Managers**
- Reviews major risks, trade-offs, and outcome evidence with delivery and analytics leads
- Supports escalation resolution when issues affect milestones, resources, or customer commitments
- Receives concise status and decision requests rather than routine delivery detail

---

## Selecting personas for a project

Not every project requires every persona. Teams should apply the smallest set of roles needed for clear accountability and add specialist personas when the work introduces relevant scope, risk, or dependencies. Assignments may be combined when a person has sufficient capacity and does not create a conflict of interest.

Projects should document:
- Named role owners or accountable delegates
- Which existing role and new persona work together for each key handoff
- Where decisions or approvals are required
- How the role is represented in planning, execution, release, and retrospectives

A responsibility matrix can clarify these arrangements. Record ownership as **Accountable**, **Responsible**, **Consulted**, or **Informed** only for activities that apply to the project.

| Activity | Accountable role | Responsible roles | Consulted roles | Informed roles |
|---|---|---|---|---|
| Outcome and priority | Product Manager | Design, Analytics | Stakeholders | Delivery team |
| Implementation plan | Project Manager | Developers | QA, Design, Operations | Product Manager |
| Quality and acceptance | QA/Testing Lead | QA/Testing, Developers | Product Manager, Design | Project Manager |
| Security and privacy | Security and Privacy Lead | Security/Privacy, Developers | Release, Project Manager | Product Manager |
| Release readiness | Release Coordinator | Release, Developers, QA | Operations, Security, Project Manager | Product Manager, stakeholders |
| Operational readiness | Support and Operations Lead | Support/Operations | Developers, Release, QA | Product Manager, Project Manager |
| Outcome measurement | Data and Analytics Lead | Data/Analytics, Developers | Product Manager | Project Manager, stakeholders |
| Executive trade-offs | Executive Sponsor | Project Manager, Product Manager | Delivery and specialist leads | Team |

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
