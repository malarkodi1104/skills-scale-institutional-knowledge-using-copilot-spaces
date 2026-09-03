# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This repository contains standardized processes and best practices for managing cross-functional projects at OctoAcme.

## About OctoAcme Project Management

OctoAcme follows a structured, lifecycle-based approach to project delivery centered on clear ownership, iterative execution, and data-driven decision-making. The methodology spans five phases: **Initiation** (validate business needs and success metrics), **Planning** (break work into shippable increments), **Execution** (deliver incrementally with regular reviews), **Release** (deploy to production with comprehensive checks), and **Close & Retrospective** (capture learnings and drive improvements).

OctoAcme runs projects using a lightweight, iterative approach that emphasizes:
- **Customer-first** prioritization and usability
- **Iterative delivery** of small, testable increments
- **Clear ownership** with defined roles and responsibilities
- **Data-informed decisions** based on measurable outcomes
- **Psychological safety** and continuous learning

## Core Roles & Responsibilities

The organization defines three core roles that drive project success:
- **Project Managers** coordinate schedules, risks, and communications to ensure on-time delivery
- **Product Managers** define outcomes, prioritize the backlog, and measure impact
- **Developers** implement features with quality, collaborate on design and acceptance criteria, and help identify technical risks

Communication occurs through a regular cadence including daily standups, weekly PM-to-PdM alignment, and monthly stakeholder updates, with formal escalation paths (team → PM → Product Lead → Sponsor) for blockers and risks.

## Process Documentation

### Getting Started
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate the business need, align stakeholders, and decide go/no-go
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, and lifecycle

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
3. **Need to manage risks?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md)
4. **Preparing for release?** See [Release & Deployment Guide](octoacme-release-and-deployment.md)
5. **Want to improve processes?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Contributing

To request updates or additions to these process docs, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

**Last updated:** September 3, 2026
