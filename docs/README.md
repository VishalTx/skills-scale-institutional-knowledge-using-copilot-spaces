# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured, iterative project management approach centered on customer value, clear ownership, and data-driven decisions. These docs provide guidance for all phases of project delivery—from initiation through retrospective.

### Project Management Processes Summary

OctoAcme's project lifecycle begins with project initiation, where new work is validated by confirming the business need, identifying stakeholders, defining success metrics, and creating a lightweight project one-pager with goals, timeline, risks, and resource needs. Once an initiative is approved, it moves into planning, where the team builds a prioritized backlog, clarifies acceptance criteria, estimates effort, identifies dependencies, and defines the Definition of Done. During the execution phase, the team works in iterative cycles with daily standups, sprint planning, milestone reviews, and demo checkpoints to keep delivery aligned and visible. The process then moves to release and deployment, where standardized gates ensure quality, testing, and stakeholder communication before going live. Finally, the project closes with retrospectives that capture lessons learned and convert them into tangible improvements for future iterations.

OctoAcme emphasizes distinct roles and responsibilities to keep work coordinated. Product leaders define outcomes, prioritize the roadmap, and measure customer and business impact. Project Managers manage schedules, dependencies, risks, and stakeholder communication. Developers focus on implementation, testing, and maintainability; QA functions validate behavior against acceptance criteria; and stakeholders contribute business context, approvals, and strategic input. Communication is intentionally regular and transparent, with daily standups for delivery coordination, weekly PM syncs for progress and risks, stakeholder updates at a set cadence, and milestone demos to confirm progress. Quality assurance is integrated throughout the project rather than added only at the end, with pull request reviews, CI checks, and testing at each stage. The process emphasizes customer-first thinking, iterative delivery, shared ownership, and psychological safety so that cross-functional teams can make decisions quickly and transparently.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **[Initiation](octoacme-project-initiation.md)** — Validate the problem, align stakeholders, define success metrics
2. **[Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify risks and dependencies
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, escalate blockers
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize releases, reduce risk, ensure observability
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, convert to action items

## Process Documents

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize new work |
| [Project Planning](octoacme-project-planning.md) | Process for creating actionable plans and backlogs |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Guidance for day-to-day execution and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk identification, management, and stakeholder communication |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized release process and deployment checklist |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Process for capturing learnings and driving improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definition of typical roles and responsibilities |

## Who Should Use These Docs?

- **Developers** → Start with [Execution & Tracking](octoacme-execution-and-tracking.md) and [Roles and Personas](octoacme-roles-and-personas.md)
- **Product Managers** → Start with [Project Management Overview](octoacme-project-management-overview.md) and [Project Initiation Guide](octoacme-project-initiation.md)
- **Project Managers** → Start with [Project Planning](octoacme-project-planning.md) and [Risk Management & Communication](octoacme-risks-and-communication.md)
- **New Team Members** → Start here with this README, then explore [Project Management Overview](octoacme-project-management-overview.md)

## Key Workflows and Practices

### Communication Cadence
- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery sync** — Show progress, updates, and flagged risks
- **Stakeholder updates** — At a set cadence (e.g., monthly or milestone-based)
- **Demo/Review** — At the end of each sprint or milestone

### Quality Assurance
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Pull Request workflow: small PRs (≤400 lines), issue links, acceptance criteria, CI passing, at least one approval before merge

### Risk and Dependency Management
- Maintain a Risk Register with: ID, Description, Impact, Likelihood, Owner, Mitigation plan, Status
- Mark cross-team dependencies in the project board
- Escalate blockers through defined levels: Team-level triage → PM escalation → Product Lead/Sponsor

## Issue Templates

Use the following template when contributing to process documentation:
- [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — Request updates or new content for process docs

## Next Steps

- **Just starting?** Read the [Project Management Overview](octoacme-project-management-overview.md)
- **Planning a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- **Executing a project?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Preparing a release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Closing a project?** Run a [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) session
