# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This repository contains standardized processes and best practices for managing cross-functional projects at OctoAcme.

## About OctoAcme Project Management

OctoAcme employs a structured, lifecycle-based approach to project delivery that spans five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The methodology is built on five core principles: customer-first prioritization, iterative delivery of small testable increments, clear ownership with defined roles, data-informed decision-making, and psychological safety. This lightweight yet disciplined approach ensures that projects validate business needs early, break work into shippable increments, and consistently measure impact against success metrics.

OctoAcme runs projects using a lightweight, iterative approach that emphasizes:
- **Customer-first** prioritization and usability
- **Iterative delivery** of small, testable increments
- **Clear ownership** with defined roles and responsibilities
- **Data-informed decisions** based on measurable outcomes
- **Psychological safety** and continuous learning

## Key Workflows & Execution Practices

During execution, teams use GitHub Projects or similar tools with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintain a prioritized backlog with clear acceptance criteria. Quality is embedded throughout via small pull requests (≤400 lines), automated CI/CD with testing and linting, unit and integration tests, security scanning, and code review requirements (minimum one approval before merge). A Risk Register tracks identified issues with impact, likelihood, owner, and mitigation status, reviewed weekly during syncs. Teams also conduct regular demos at sprint or milestone ends, track velocity and burndown, and escalate blockers through defined escalation ladders.

Release decisions follow a pre-release checklist ensuring all acceptance criteria are met, CI passes, security scans complete, and rollback plans are documented. Releases are classified as Patch (hotfixes), Minor (incremental features), or Major (significant changes), with smoke tests and staging verification prior to production deployment. After each sprint, release, or milestone, teams conduct retrospectives to capture what went well, identify improvements, and assign action items with owners and due dates. This continuous improvement culture, combined with post-incident blameless retrospectives, ensures the organization learns from each cycle and evolves its processes iteratively.

## Core Roles & Responsibilities

The organization defines three core roles that drive project success:
- **Project Managers** coordinate schedules, risks, and stakeholder communications to ensure on-time delivery
- **Product Managers** define outcomes, prioritize the backlog, and measure impact
- **Developers** implement features with quality, collaborate on design and acceptance criteria, and help identify technical risks

Communication occurs through a regular cadence including daily standups (15 minutes), weekly PM-to-PdM alignment, and monthly stakeholder updates, with formal escalation paths (team → PM → Product Lead → Sponsor) for blockers and risks.

For detailed role definitions and personas, see [Roles and Personas](octoacme-roles-and-personas.md).

## Process Documentation

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate the business need, align stakeholders, and decide go/no-go

### Planning & Execution
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments and create actionable backlogs
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, standups, and progress tracking

### Quality & Risk Management
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies

Quality and risk management are embedded throughout execution. Teams practice small PRs (≤400 lines), require automated testing and linting in CI, conduct code reviews, and employ unit and integration tests. A Risk Register tracks identified issues with impact, likelihood, owner, and mitigation status, reviewed weekly in sync meetings.

### Release & Continuous Improvement
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to reduce risk and improve observability
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive process improvements

### Reference
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed definitions of key PM roles (Project Manager, Product Manager, Developers, etc.)

## Quick Reference

| Phase | Key Artifacts | Owner |
|-------|---------------|-------|
| Initiation | One-pager, Stakeholder list | Product Lead + PM |
| Planning | Backlog, Release plan, Risk register | PM + Product Manager |
| Execution | Sprint board, Daily standups, Status reports | PM + Delivery Team |
| Release | Release notes, Deployment plan | PM + Engineering |
| Retrospective | Action items, Improvements log | PM + Full Team |

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
3. **Planning a project?** See [Project Planning](octoacme-project-planning.md)
4. **Managing day-to-day execution?** Refer to [Execution & Tracking](octoacme-execution-and-tracking.md)
5. **Need to manage risks?** Check [Risk Management & Communication](octoacme-risks-and-communication.md)
6. **Preparing for release?** See [Release & Deployment Guide](octoacme-release-and-deployment.md)
7. **Want to improve processes?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Contributing

To request updates or additions to these process docs, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

**Last updated:** September 4, 2026
