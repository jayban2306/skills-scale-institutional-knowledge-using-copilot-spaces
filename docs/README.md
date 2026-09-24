# OctoAcme Project Management Docs

This directory contains the core project management guidance used by OctoAcme to plan, execute, track, and improve work across product and engineering teams. These documents are designed to create a shared operating model for delivery, stakeholder communication, quality assurance, and learning.

## Documentation index

- [Project Management Overview](octoacme-project-management-overview.md) — a high-level introduction to the project lifecycle, roles, artifacts, and communication rhythm.
- [Project Initiation Guide](octoacme-project-initiation.md) — how new ideas are validated, scoped, and approved before full planning begins.
- [Project Planning](octoacme-project-planning.md) — how backlog items, milestones, dependencies, and release plans are structured.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — daily rhythms, tracking practices, blockers, and delivery governance.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — how risks, dependencies, stakeholder updates, and incidents are managed.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — pre-release checks, deployment flow, rollback planning, and release communication.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — how the team captures learning and converts improvements into action.
- [Roles and Personas](octoacme-roles-and-personas.md) — role definitions and responsibilities used across the project process.

## Overview of OctoAcme project management processes

OctoAcme uses a structured delivery lifecycle that begins with project initiation and moves through planning, execution, release, and retrospective review. The initiation phase focuses on confirming the business problem, aligning stakeholders, defining measurable success criteria, and determining whether the work should proceed into planning. Once approved, the team creates a prioritized backlog, estimates effort, agrees on milestones, maps dependencies, and defines the release path. This keeps planning grounded in business value, stakeholder alignment, and a realistic delivery plan.

The operating model emphasizes clear ownership, iterative delivery, and visible progress. Product leaders define outcomes and prioritize work, project managers coordinate schedules, dependencies, and communications, and developers implement the work while maintaining quality and technical clarity. The role definitions in the repo make these responsibilities explicit so teams can work in a coordinated, cross-functional way. Communication is intentionally regular and structured through standups, sprint or milestone reviews, weekly PM/product syncs, and escalation paths that move issues upward when blockers or shared dependencies arise.

Quality assurance is built into the process rather than treated as a last-minute step. Teams define acceptance criteria and a Definition of Done for backlog items, require CI checks for tests and security validation, and use unit, integration, and smoke testing where appropriate. The execution guidance also promotes small PRs, required review before merge, and manual QA when needed for feature acceptance. Release and deployment practices add staging verification, rollback readiness, and post-deploy checks to reduce production risk and support consistent verification before and after launch.

Finally, OctoAcme treats retrospectives and continuous improvement as part of the operating rhythm. After each sprint, milestone, or incident, the team captures what went well, what needs improvement, and what action items should be tracked. Risk management, ongoing communication, and improvement actions are all tied together so the team can adapt quickly, learn from results, and keep making the process more effective over time.

## How to use these documents

Use this README as the starting point for the OctoAcme management process. Start with the overview and initiation guide for new work, then follow the planning, execution, and release documents as the project moves forward. The roles and personas document is especially useful for onboarding and clarifying responsibilities across the team.
