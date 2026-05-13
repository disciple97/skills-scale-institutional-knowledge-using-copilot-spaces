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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed additions)

Expanding the set of documented personas helps clarify ownership, reduce handoff friction, and ensure accountability across cross-functional work. The following roles are commonly involved in delivery but are not always explicitly documented in our process docs. Adding them will improve clarity for project teams and stakeholders.

### Engineering Manager

#### Role Summary
Engineering Managers (EMs) provide technical leadership for teams, support career development, and align engineering resourcing with project needs.

#### Responsibilities
- Coordinate staffing and capacity planning across teams
- Remove organizational blockers and escalate resource conflicts
- Mentor technical leads and developers
- Champion engineering best practices and technical debt management

#### Interaction with existing roles
- Works with Project Managers to align team capacity and schedules
- Collaborates with Product Managers on prioritization trade-offs influenced by capacity or technical constraints
- Supports Developers and Tech Leads with hiring, skill growth, and escalation

---

### Technical Lead (Tech Lead)

#### Role Summary
Tech Leads provide day-to-day technical direction for a project or feature area, making architecture and design decisions and guiding implementation.

#### Responsibilities
- Define technical approach and design patterns for features
- Review and approve significant design decisions and complex PRs
- Coordinate cross-team technical dependencies
- Ensure code quality and mentor developers on technical matters

#### Interaction with existing roles
- Collaborates with Developers on design and code reviews
- Aligns with Project Managers on technical risks and schedules
- Works with EMs on resourcing and technical debt priorities

---

### UX / Product Designer

#### Role Summary
Designers translate product goals into user-centered experiences, create wireframes and prototypes, and validate solutions with users.

#### Responsibilities
- Create UX artifacts (wireframes, prototypes, design specs)
- Conduct user research and usability testing
- Define accessibility and usability acceptance criteria
- Work with engineers to ensure designs are feasible and implemented correctly

#### Interaction with existing roles
- Partners with Product Managers to refine requirements and acceptance criteria
- Works closely with Developers during implementation and QA to resolve design questions
- Informs Project Managers of design-related schedule impacts or dependencies

---

### Data Analyst / Data Engineer

#### Role Summary
Data roles ensure product decisions are informed by data, build measurement plans, and provide analytics to validate success metrics.

#### Responsibilities
- Define metrics and instrumentation requirements
- Build dashboards and provide ongoing analysis
- Validate experiment results and success criteria
- Ensure data quality and correct event tracking

#### Interaction with existing roles
- Works with Product Managers to define success metrics and measurement plans
- Collaborates with Developers/Platform Engineers to implement instrumentation
- Provides PMs and stakeholders with dashboards used in reporting

---

### Security Engineer / Security Reviewer

#### Role Summary
Security-focused engineers review designs and code for security and ensure compliance with security policies and scans.

#### Responsibilities
- Conduct threat modeling for sensitive features
- Review dependencies and third-party risks
- Triage and validate security scan findings
- Advise on mitigations and required controls

#### Interaction with existing roles
- Works with Developers and Tech Leads during design and PR review cycles
- Notifies Project Managers and Product Managers of security risks that affect timelines or scope
- Coordinates with Legal/Compliance when necessary

---

### Release / Platform Engineer

#### Role Summary
Release or Platform Engineers maintain CI/CD pipelines, deployment automation, and environment stability to enable repeatable releases.

#### Responsibilities
- Maintain and improve CI/CD pipelines and deployment tooling
- Create rollback/mitigation automation and runbooks
- Support staging and production deployments and post-deploy verification

#### Interaction with existing roles
- Collaborates with Project Managers and Developers to schedule and execute releases
- Works with QA and Observability owners to ensure pre/post-deploy checks are in place

---

### QA Lead / Test Engineer

#### Role Summary
QA Leads coordinate testing strategy, maintain test suites, and work with engineering to ensure acceptance criteria are met.

#### Responsibilities
- Define test plans for features and releases
- Maintain automated test coverage and manual QA processes
- Triage test failures and work with Developers to resolve issues

#### Interaction with existing roles
- Partners with Developers and Tech Leads to define DoD and acceptance criteria
- Reports test status to Project Managers and Product Managers

---

### Customer Support / Customer Success Representative

#### Role Summary
Support roles surface real-world issues, provide product feedback, and communicate known issues to customers and teams.

#### Responsibilities
- Triage incoming customer issues and provide timely responses
- Provide contextual feedback to Product and Project teams about customer pain points
- Assist with release communications and post-release monitoring

#### Interaction with existing roles
- Works with PMs for prioritization of customer-reported issues
- Coordinates with Developers and QA for reproducing and resolving bugs
- Supports PM/Project Manager in communicating known issues to stakeholders

---

### Business Analyst

#### Role Summary
Business Analysts translate business needs into clear requirements and help scope work while aligning stakeholders.

#### Responsibilities
- Elicit and document detailed requirements
- Map business processes and identify impacts
- Support acceptance criteria and edge-case definition

#### Interaction with existing roles
- Works closely with PMs and Product Managers during planning
- Collaborates with Developers and QA to clarify requirements during implementation

---

### Scrum Master / Delivery Lead

#### Role Summary
Scrum Masters (or Delivery Leads) facilitate agile ceremonies, remove team impediments, and help the team improve delivery practices.

#### Responsibilities
- Facilitate standups, retrospectives, and sprint planning
- Track and remove impediments to delivery
- Coach the team on agile practices and continuous improvement

#### Interaction with existing roles
- Works with Project Managers to surface and escalate blockers
- Supports Developers and QA in maintaining a sustainable delivery cadence

---

### Legal / Compliance Liaison

#### Role Summary
Legal or compliance contacts ensure regulatory and contractual obligations are considered in scope and design.

#### Responsibilities
- Review features for compliance risk (privacy, data handling, contracts)
- Provide guidance on legal constraints and required approvals
- Document compliance-related requirements and controls

#### Interaction with existing roles
- Alerts Product Managers and Project Managers to compliance requirements that affect timelines or scope
- Works with Security Engineers for controls and risk mitigation

---

### How adding these personas improves outcomes
- Clearer ownership reduces handoff ambiguity and missed responsibilities.
- Faster decision-making when the right role and escalation are documented.
- Improved quality and risk management through earlier involvement of security, QA, and compliance.
- Better measurement and data-driven decisions when data roles and analysts are included.
- Smoother releases and lower operational risk with platform/release engineers explicitly involved.

---

## Suggested next steps
1. Review the proposed personas with the PM/PdM/Engineering leads and adjust responsibilities to match team structure.
2. Incorporate the finalized personas into docs/octoacme-roles-and-personas.md (this change).
3. Update related process docs to reference role-specific responsibilities where applicable (e.g., release guide, security runbook, QA section).
4. Create a lightweight RACI or responsibility matrix for high-risk activities (releases, security approvals, production incidents).

