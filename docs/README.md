# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This repository contains standardized processes and best practices for managing cross-functional projects at OctoAcme.

## About OctoAcme Project Management

OctoAcme runs projects using a lightweight, iterative approach that emphasizes:
- **Customer-first** prioritization and usability
- **Iterative delivery** of small, testable increments
- **Clear ownership** with defined roles and responsibilities
- **Data-informed decisions** based on measurable outcomes
- **Psychological safety** and continuous learning

## OctoAcme Project Management Processes Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that captures the problem statement, objectives, success metrics, and resource requirements. Once approved by the Product Lead and stakeholders, work moves into planning, where the backlog is prioritized, acceptance criteria are defined, dependencies are identified, and a Definition of Done is established. This deliberate gate-keeping approach ensures that only well-scoped, clearly understood work enters execution.

Execution at OctoAcme is coordinated through a structured team rhythm: daily 15-minute standups focused on progress and blockers, weekly delivery syncs with stakeholders, and regular demos at sprint or milestone boundaries. Work flows through a GitHub Projects board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval before merging. Quality assurance is embedded throughout delivery via unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in the CI pipeline. Risk management is continuous: teams triage blockers at the standup level, escalate to the PM and Product Lead when needed, and track all risks in a centralized register with clear ownership and mitigation plans.

OctoAcme's organizational model clarifies roles across three primary personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build, prioritize the backlog, and measure success; and **Developers** implement features, write tests, and collaborate on design. A weekly sync between PM and Product Manager, twice-weekly standups for the delivery team, and monthly stakeholder updates create consistent touch points across all levels. Communication templates standardize status reporting (progress, next steps, risks, decisions needed) and incident response, while escalation paths channel issues from team level → PM → Product Lead → Sponsor, with security incidents following a dedicated runbook.

Finally, OctoAcme closes every project or major milestone with a structured retrospective (45–75 minutes) that captures what went well, what could improve, and actionable next steps. Action items are tracked with clear owners and due dates, reviewed at weekly PM syncs, and prioritized to avoid overload. This continuous improvement culture ensures learnings feed back into the process documentation itself, making OctoAcme's practices increasingly refined and team-wide adoption increasingly seamless.

## Process Documentation

### Getting Started
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate the business need, align stakeholders, and decide go/no-go
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, and lifecycle

### Planning & Execution
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments and create actionable backlogs
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, standups, and progress tracking

### Risk & Communication
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies

### Release & Continuous Improvement
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to reduce risk and improve observability
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive process improvements

### Reference
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of key PM roles (Project Manager, Product Manager, Developers, etc.)

## Quick Reference

| Phase | Key Artifacts | Owner |
|-------|---|---|
| Initiation | One-pager, Stakeholder list | Product Lead + PM |
| Planning | Backlog, Release plan, Risk register | PM + Product Manager |
| Execution | Sprint board, Daily standups, Status reports | PM + Delivery Team |
| Release | Release notes, Deployment plan | PM + Engineering |
| Retrospective | Action items, Improvements log | PM + Full Team |

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
3. **Need to manage risks?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md)
4. **Preparing for release?** See [Release & Deployment Guide](octoacme-release-and-deployment.md)
5. **Running a retrospective?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Contributing

To request updates or additions to these process docs, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
