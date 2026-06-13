---
title: "[Process Doc Update]: Adding more personas and roles to the project management processes"
labels: ["documentation", "process improvement"]
---

## Which process document do you want to update?

octoacme-roles-and-personas.md

## Summary of New Content

Expand the Roles & Personas document to add new personas and role descriptions to improve clarity and accountability across projects.

## Why is this update needed?

Current documentation covers core roles but could be clearer about handoffs, responsibilities for cross-team coordination, and specialized contributors. Adding additional personas will reduce ambiguity, speed onboarding, and improve coordination on cross-cutting concerns like releases, observability, security, and stakeholder communication.

## Suggested New Personas and Roles

### Technical Program Manager (TPM)
- **Responsibilities**: Coordinate cross-team dependencies, manage milestones and release cadence, facilitate technical risk mitigation, and maintain the cross-team roadmap.
- **Interactions**: Works with PMs for prioritization, with Developers and Delivery Leads for scheduling, and with Release Engineers for deployment planning.

### Delivery Lead
- **Responsibilities**: Day-to-day delivery coordination for a feature or program, ensure backlog readiness, drive standups and unblock the team.
- **Interactions**: Pairs with PM and PdM for scope decisions, with Developers and QA to ensure DoD is met.

### Release Engineer / CI Engineer
- **Responsibilities**: Maintain deployment pipelines, automate release verification, own rollback/playbooks, and improve release reliability.
- **Interactions**: Collaborates with Developers for pipeline changes, with QA for staging verification, and with On-call/Support for post-release monitoring.

### Observability/Monitoring Owner
- **Responsibilities**: Define metrics and alerts for new features, own dashboards and runbooks for on-call teams.
- **Interactions**: Works with Developers to instrument code, with SRE/ops for alerting, and with Product for success metrics.

### UX Researcher / Designer Liaison
- **Responsibilities**: Ensure user research feeds into planning, validate UX decisions, and provide prototypes and acceptance criteria.
- **Interactions**: Partners with PdM for defining success metrics and with Developers during implementation.

### Security & Compliance Owner
- **Responsibilities**: Review designs for security/compliance impact, maintain security checklists, and coordinate scans.
- **Interactions**: Engages with Developers, TPMs, and Release Engineers before production changes.

### Support Liaison / Product Support Owner
- **Responsibilities**: Surface customer pain points, own documentation and runbooks for support, and coordinate post-release support readiness.
- **Interactions**: Escalates issues to PMs, works with Developers for fixes, and informs Product about user impact.

## How This Will Improve Outcomes

- **Clarifies handoffs and ownership**: Reduces ambiguity during planning and execution.
- **Speeds onboarding**: Documents responsibilities for common cross-functional activities.
- **Improves release reliability**: Assigns clear owners for CI, observability, and security.
- **Enhances cross-team coordination**: Better communication and collaboration on releases, observability, and incident response.

## Proposed Location

Append these personas and role descriptions to `docs/octoacme-roles-and-personas.md` with examples of interactions and a RACI-style matrix for key activities.

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [x] Proposed content has been reviewed with stakeholders (if needed)
