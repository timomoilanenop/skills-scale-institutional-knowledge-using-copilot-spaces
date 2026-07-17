# OctoAcme Project Management Process Docs

Welcome to the OctoAcme project management documentation hub. This folder contains standardized processes, checklists, and guidance for running successful cross-functional projects.

## Quick Start

**New to OctoAcme projects?** Start here:
- [Project Management Overview](./octoacme-project-management-overview.md) — Learn our principles, roles, and key artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — Understand team roles and responsibilities

## Project Lifecycle

Follow these guides in order as your project progresses:

1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate the need, align stakeholders, and decide go/no-go
2. **[Project Planning](./octoacme-project-planning.md)** — Break work into actionable backlog items and release milestones
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day work, testing, and quality
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Prepare and ship features to production
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements

## Cross-Cutting Guides

Use these throughout your project:

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify risks, manage dependencies, and keep stakeholders informed

## OctoAcme Project Management Overview

OctoAcme follows a structured lifecycle approach that moves projects through five distinct phases: Initiation, Planning, Execution, Release, and Retrospective. The process is grounded in customer-first principles and emphasizes iterative delivery through small, testable increments. During **Initiation**, teams validate business need and create a lightweight Project One-pager defining the problem, objectives, success metrics, and stakeholders—serving as the decision gate to move forward. In the **Planning phase**, approved initiatives are broken down into prioritized backlogs with clear acceptance criteria, dependencies are mapped, and a release plan is established. **Execution** focuses on day-to-day delivery through daily standups, weekly syncs, and a structured pull request workflow that emphasizes small PRs, automated testing, and peer review before merge. Teams track progress using GitHub Projects with consistent columns (Backlog, Ready, In Progress, In Review, QA, Done) and measure velocity against identified success metrics.

The organizational structure centers on three core personas with complementary responsibilities: **Project Managers** coordinate schedules, risks, and communications while maintaining transparency across stakeholders; **Product Managers** own vision, prioritize work, and validate solutions through data-driven metrics; and **Developers** implement features, write tests, and collaborate on design decisions. This clear ownership model is reinforced through consistent communication rhythms—daily standups for the delivery team, weekly syncs between PM and Product Lead, and monthly stakeholder updates—ensuring alignment across all parties.

Quality and risk management are woven throughout the entire lifecycle. Teams maintain a **Risk Register** tracking impact, likelihood, ownership, and mitigation plans, with escalation paths flowing from team-level triage through PM to Product Lead and Sponsor as needed. Quality practices include unit tests, integration tests, end-to-end smoke tests before release, security scanning in CI, and manual QA when required. **Release and Deployment** are standardized through pre-release checklists, smoke test verification in staging, and defined rollback procedures. Finally, the process closes with **Retrospectives** that capture learnings, identify 2–3 actionable improvements, and track follow-up items to foster a culture of continuous improvement.

## Core Principles

All OctoAcme projects follow these principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Communication Cadence

- **Daily standups**: 15-minute team updates on progress, blockers, and dependencies
- **Weekly sync**: PM + Product Manager alignment
- **Weekly delivery sync**: Show progress, updates, and flagged risks
- **Monthly updates**: Stakeholder briefings
- **Ad-hoc escalations**: As needed for blockers

## Role-Based Navigation

### For Project Managers
- Start with [Project Management Overview](./octoacme-project-management-overview.md)
- Follow the [Project Lifecycle](#project-lifecycle) in order
- Reference [Risk Management & Communication](./octoacme-risks-and-communication.md) throughout

### For Product Managers
- Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand team structure
- Define success in [Project Initiation](./octoacme-project-initiation.md)
- Prioritize work in [Project Planning](./octoacme-project-planning.md)

### For Developers
- Understand the process in [Project Management Overview](./octoacme-project-management-overview.md)
- Get project context from your PM during [Project Initiation](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md)
- Execute work following [Execution & Tracking](./octoacme-execution-and-tracking.md)
- Prepare for release via [Release & Deployment](./octoacme-release-and-deployment.md)

## Questions?

If you have questions about OctoAcme processes, check the relevant guide or reach out to your Project Manager.
