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

## New / Additional Personas

The following personas can help close gaps in ownership and delivery clarity. Add these as subsections where appropriate.

### Engineering Lead

#### Role Summary
Technical owner for the codebase and architecture decisions for a project or sub-system.

#### Responsibilities
- Drive technical design and architecture decisions
- Resolve implementation trade-offs and approve major changes
- Mentor engineers and promote engineering best practices
- Ensure code quality, performance, and non-functional requirements are addressed
- Identify and communicate technical risks and mitigation plans

#### Goals
- Maintain a sustainable, scalable architecture
- Reduce technical debt and avoid rework
- Enable predictable delivery through clear technical direction

#### Typical Communication
- Design reviews and architecture syncs
- Technical decision records and RFCs
- Pairing sessions with developers

#### Interaction Guidance
Works with PM/PdM to translate requirements into technical scope; coordinates with Developers, QA, and Delivery Lead on implementation and release readiness; escalates technical blockers to the Product Lead.

---

### Delivery Lead

#### Role Summary
Coordinates cross-team delivery details, timelines, and release execution for larger initiatives.

#### Responsibilities
- Maintain an integrated delivery plan across teams and components
- Track dependencies, milestones, and risks
- Run release readiness checks and coordinate cutover/rollout steps
- Facilitate cross-team communication and escalation

#### Goals
- Reduce delivery friction and missed dependencies
- Ensure releases are executed smoothly and on schedule

#### Typical Communication
- Cross-team planning meetings and dependency boards
- Release readiness checklists and runbooks

#### Interaction Guidance
Works closely with PMs, Engineering Leads, Release Manager, and Support Owner; escalates schedule or dependency issues to Product Lead when necessary.

---

### UX Researcher / Designer

#### Role Summary
Owns user research, usability, and design decisions for features.

#### Responsibilities
- Plan and conduct user research and interviews
- Produce wireframes, prototypes, and design specs
- Define UX acceptance criteria and testable scenarios
- Validate designs during demos and usability tests

#### Goals
- Deliver usable, accessible, and delightful user experiences
- Reduce rework by validating assumptions early

#### Typical Communication
- Design reviews, user-testing sessions, and demos
- Handoff artifacts and acceptance criteria to Developers

#### Interaction Guidance
Partners with PdM to define user needs; hands off design and assets to Developers; collaborates with QA to validate UX acceptance criteria.

---

### Data Analyst / Data Owner

#### Role Summary
Ensures feature instrumentation, metrics, and data model correctness.

#### Responsibilities
- Define success metrics and measurement plans
- Validate telemetry and data quality
- Create dashboards and ad-hoc analyses to inform decisions
- Support experiments and post-release analysis

#### Goals
- Ensure decisions are data-informed and measurable
- Provide timely insights to product and engineering

#### Typical Communication
- Analytics reviews, dashboard walkthroughs, and metrics reports

#### Interaction Guidance
Works with PdM to define success metrics; coordinates with Developers for instrumentation; reports outcomes to PM and stakeholders.

---

### Security Liaison

#### Role Summary
Point of contact for security requirements, threat modeling, and vulnerability triage.

#### Responsibilities
- Review threat models and security implications of proposals
- Ensure security checks are integrated into CI and release pipelines
- Triage and prioritize security findings and advisories
- Advise on mitigation strategies and timelines

#### Goals
- Reduce security risk and time-to-fix for vulnerabilities
- Maintain secure defaults and compliance where applicable

#### Typical Communication
- Security reviews, incident triage calls, and advisories

#### Interaction Guidance
Engages with Engineering Leads, Developers, and Security on-call; informs PM and Product Lead of any blocking security issues and recommended mitigations.

---

### Support / On-call Owner

#### Role Summary
Represents operational and customer-support concerns during design and after release.

#### Responsibilities
- Define runbook and operational requirements
- Verify observability, alerts, and playbooks are in place
- Handle escalations from customer support and on-call rotations
- Own incident handoffs and post-incident follow-ups

#### Goals
- Ensure operability and fast incident response
- Reduce customer impact through clear support processes

#### Typical Communication
- On-call handovers, incident reports, and post-incident reviews

#### Interaction Guidance
Works with Delivery Lead and Engineering Lead to ensure runbooks, dashboards, and alerts are ready; coordinates with PM for customer communications when incidents affect users.

---

### Release Manager (optional for larger orgs)

#### Role Summary
Owns the release process and coordination for production deployments.

#### Responsibilities
- Schedule and coordinate deployments
- Ensure rollback and mitigation plans are documented
- Confirm smoke tests and post-deploy verifications
- Publish release notes and stakeholder communications

#### Goals
- Reduce release-related incidents and rollbacks
- Improve transparency and predictability of deployments

#### Typical Communication
- Release schedules, deployment notes, and verification checklists

#### Interaction Guidance
Coordinates with Delivery Lead, Engineering Leads, and Support Owner during releases; notifies stakeholders and triggers rollback/incident procedures when needed.

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
