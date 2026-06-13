# OctoAcme Project Management Docs

This README provides a single-entry index to the OctoAcme project management process documents and a brief summary of the processes used across projects. Use these docs to onboard new teammates, run projects consistently, and keep process guidance up to date.

## Brief Summary of Project Management Processes

OctoAcme follows an iterative, customer-focused delivery process organized into six key phases:

### 1. **Initiation**
Validate the business need and authorize work. Confirm problem statements, identify stakeholders and champions, define success criteria, and create a lightweight project one-pager. The decision gate ensures measurable outcomes are clear and stakeholder alignment is established before moving to planning.

### 2. **Planning**
Transform an approved initiative into an actionable plan and backlog for delivery. Break work into shippable increments, estimate scope, identify dependencies and risks, define acceptance criteria and the Definition of Done, and create a release plan with milestone mapping.

### 3. **Execution & Tracking**
Manage day-to-day execution and track progress toward project milestones. Run daily standups, enforce pull request and CI practices, use project boards to visualize workflow, and maintain quality through unit and integration tests. Escalate blockers through a three-level escalation path (team → PM → sponsor).

### 4. **Risks & Communication**
Identify, manage, and communicate risks and dependencies throughout the project. Maintain a risk register, assess impact and likelihood, implement mitigations, and provide regular stakeholder updates. Follow clear escalation paths and incident communication protocols when needed.

### 5. **Release & Deployment**
Standardize how features reach production to reduce risk and improve observability. Follow pre-release checklists, deploy to staging with smoke tests, verify in production, and maintain rollback and incident playbooks. Release notes document changes and migration steps.

### 6. **Retrospective & Continuous Improvement**
Capture learnings and convert them into actionable improvements. Run retrospectives after sprints or milestones, prioritize 2–3 top action items, track improvements in the project backlog, and measure impact of changes to build a continuous improvement culture.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Links to Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate work and create a project one-pager
- [Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, PR workflows, quality standards, and escalation
- [Risks & Communication](./octoacme-risks-and-communication.md) — Risk management, stakeholder communication, and escalation paths
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release process, checklists, and incident playbooks
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive continuous improvement
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities

## How to Use These Docs

1. **For onboarding**: New team members should start with the Project Management Overview, then dive into the specific phases relevant to their role.
2. **For project execution**: Reference the appropriate phase document (Initiation → Planning → Execution → Release → Retrospective) as your project progresses.
3. **For updates**: Add new or updated process documents to the `docs/` folder. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes.
4. **For consistency**: Keep the Project Charter updated in your project repo. Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context.

## Communication Cadence

- **Weekly sync** between PM + Product Manager
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates** for visibility and alignment
- **Ad-hoc escalations** as needed for blockers or risks
