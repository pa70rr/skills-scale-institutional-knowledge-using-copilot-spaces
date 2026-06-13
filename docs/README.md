# OctoAcme Project Management Docs

This collection contains OctoAcme's project management process documents — guidance, templates, and checklists to run projects consistently.

## Overview

OctoAcme follows a structured, people-centered approach to project management grounded in five core principles: customer-first delivery, iterative value, clear ownership, data-informed decisions, and psychological safety. These documents provide the framework, roles, and workflows that enable teams to deliver reliably while maintaining transparency and continuous improvement.

## Project Management Processes (Summary)

### Initiation
Validate business needs and authorize work. During initiation, the team creates a lightweight **Project One-pager** that captures the problem statement, success metrics, stakeholders, timeline, and resource needs. A formal decision gate ensures stakeholders align before moving into planning.

### Planning
Turn an approved initiative into an actionable plan. The team builds a prioritized backlog with acceptance criteria, estimates scope using T-shirt sizing or story points, defines the **Definition of Done**, identifies dependencies, and creates a release timeline. Planning concludes with a project kickoff that aligns the entire delivery team.

### Execution & Tracking
Manage day-to-day delivery and track progress toward milestones. The team follows a consistent rhythm: daily standups (15 min), weekly delivery syncs, and demos at sprint or milestone boundaries. Work flows through a project board (Backlog → Ready → In Progress → In Review → QA → Done), and pull requests follow conventions (small PRs ≤400 lines, automated CI, at least one approval). Blockers are escalated through three levels: team triage → PM escalation → sponsor escalation.

### Risks & Communication
Identify, assess, and manage risks while keeping stakeholders informed. The team maintains a **Risk Register** (ID, description, impact, likelihood, owner, mitigation plan) reviewed weekly. Communication follows a predictable cadence: weekly PM/PdM syncs, twice-weekly standups, monthly stakeholder updates, and ad-hoc escalations. Regular status updates use a standard template covering progress, next steps, risks, and asks.

### Release & Deployment
Standardize the path to production and reduce risk. Pre-release requirements include all acceptance criteria met, passing CI and security scans, release notes drafted, and a rollback plan documented. The deployment checklist ensures staging verification, production deployment (preferably automated), and post-deploy verification. Incidents trigger a blameless retrospective.

### Retrospective & Continuous Improvement
Capture learnings and convert them into actionable improvements. After each sprint, release, or milestone, the team runs a 45–75 minute retrospective to discuss what went well, what could improve, and prioritize 2–3 action items with clear owners and due dates. Action items are tracked in the project backlog and reviewed weekly to measure impact.

### Roles & Personas
Clear ownership and responsibilities across four core personas:
- **Developers**: Implement features, maintain tests and documentation, participate in design reviews, help identify technical risks.
- **Product Managers**: Define problems and success metrics, prioritize the backlog, make data-driven trade-off decisions, validate solutions.
- **Project Managers**: Coordinate delivery, manage schedules and risks, facilitate meetings, ensure transparent status reporting.
- **Stakeholders**: Provide inputs, approve decisions, and receive regular updates.

## Quality Assurance & Testing

Quality is embedded throughout the delivery lifecycle:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Automated linting and tests required before PR review

## Key Artifacts

- **Project Charter / One-pager**: Problem, goal, success metrics, stakeholders, timeline, risks, resources
- **Roadmap and Release Plan**: Milestones, delivery dates, feature priorities
- **Sprint/Iteration Backlog**: Prioritized work with acceptance criteria and estimates
- **Risk Register**: Tracked risks with impact, likelihood, owner, and mitigation plans
- **Decision Log**: Significant decisions and rationale
- **Retrospective Notes & Action Items**: Learnings and improvements tracked for the next cycle

## Links to Process Documents

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to roles, principles, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate, authorize, and initiate new projects
- [Project Planning](./octoacme-project-planning.md) — Creating backlog, estimates, release timeline, and Definition of Done
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery, team rhythm, quality standards, and blocker escalation
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk register, stakeholder communication, escalation paths
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback playbook
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and tracking action items
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a quick orientation.
- **Starting a new project?** Follow the sequence: Initiation → Planning → Execution → Release → Retrospective.
- **Need a template?** Each process doc includes templates for One-pagers, backlog items, risk registers, and communication.
- **Looking for best practices?** Each doc includes checklists and workflows to ensure consistency.
- **Copilot Spaces context?** Add relevant process docs to `.copilot/` or your project's context to ground Copilot's guidance in OctoAcme practices.

---

*Last updated: 2026-06-13*
*Maintained by: OctoAcme Project Management Office*
