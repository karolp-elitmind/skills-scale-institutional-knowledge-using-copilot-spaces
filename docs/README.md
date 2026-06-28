# OctoAcme Project Management

This README centralizes OctoAcme's project management process documents and provides a summary and direct links to each document in the docs/ folder.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: **customer-first delivery, iterative increments, clear ownership, data-informed decisions, and psychological safety**. The process flows through five distinct phases—Initiation, Planning, Execution, Release, and Retrospective—each with specific deliverables and decision gates.

### Key Workflows & Practices

**Initiation & Planning:** During Initiation, teams validate business need and stakeholder alignment using a lightweight Project One-pager that captures the problem statement, SMART objectives, success metrics, and initial risk assessment. Once stakeholders approve, the project moves to Planning, where the backlog is prioritized, work is estimated, dependencies are mapped, and a Definition of Done is established. This emphasis on upfront clarity ensures teams enter execution with aligned expectations and measurable outcomes.

**Execution & Team Rhythm:** Execution in OctoAcme centers on a disciplined team rhythm and pull-based workflow. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs review sprint progress and flagged risks. Teams use project boards (e.g., GitHub Projects) with standardized columns and enforce small pull requests (≤400 lines) with mandatory automated testing, linting, and at least one peer approval before merging. A three-level escalation framework—Team → PM → Product Lead → Sponsor—ensures blockers are triaged quickly and business-impacting issues reach decision-makers.

**Quality & Release:** Quality and observability are embedded throughout OctoAcme's processes. Teams implement unit tests, integration tests, and end-to-end smoke tests for critical flows, supported by security scanning and manual QA gates when needed. Before any release—whether a patch, minor update, or major feature—teams verify all acceptance criteria are met, CI passes, release notes are drafted, and a rollback plan exists. Post-deployment verification and stakeholder communication complete the handoff.

**Roles & Continuous Improvement:** The organizational structure divides responsibility between three core roles: **Project Managers** coordinate timelines, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; and **Developers** implement features while participating in design and planning. Finally, Retrospectives held after each sprint, release, or incident capture learnings and convert them into prioritized action items, reinforcing a culture of continuous improvement and psychological safety.

---

## Process Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, roles, key artifacts, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, quality, and blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how to release features to production with reduced risk
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Define typical roles (PMs, Project Managers, Developers) and responsibilities

---

## How to Use These Docs

- **For onboarding:** Start with the [Project Management Overview](octoacme-project-management-overview.md), then explore specific phases and roles as needed.
- **For project work:** Reference the relevant process doc for your current phase (e.g., use [Project Initiation](octoacme-project-initiation.md) when kicking off a new project).
- **For continuous improvement:** Add new process docs to the `docs/` folder and update this README with a short summary and link.
- **For Copilot Spaces context:** Include `.copilot/` artifacts that link to or embed these docs to ground Copilot in your team's project management practices.

---

## Key Contacts & Feedback

To propose updates to these docs, [open an issue](https://github.com/karolp-elitmind/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) using the **Add Content to Project Management Process Docs** template.
