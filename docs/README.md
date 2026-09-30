# OctoAcme Project Management Process Docs

Welcome to the OctoAcme project management documentation. These guides standardize how we run projects across the organization, support clear ownership and alignment, and reinforce our customer-first and data-informed principles.

## Overview of OctoAcme Project Management Processes

OctoAcme's project management approach is structured around a clear lifecycle that moves work from initiation to planning, execution, release, and continuous improvement. The process begins with an initiation phase in which the team defines the problem, success metrics, stakeholders, and high-level milestones to decide whether the project should move forward. Once approved, planning turns the initiative into a prioritized backlog, estimates, dependencies, and a release plan, with explicit activities like kickoff meetings, definition of done, and risk identification. Execution is managed through sprint or milestone-based delivery, with work tracked in a project board and progress monitored through daily standups, demos, and weekly delivery reviews. At the end of the cycle, the team conducts retrospectives to capture lessons learned and convert them into concrete action items for the next planning cycle.

The operating model is grounded in defined personas and role clarity. Product managers own the problem definition, outcomes, and prioritization, while project managers coordinate schedules, risks, dependencies, and documentation so execution stays aligned with stakeholder expectations. Developers build and test the work, QA teams validate quality and acceptance criteria, and stakeholders provide input, approvals, and business context. The documentation emphasizes customer value, iterative delivery, clear ownership, and psychological safety, creating a team culture where decision-making is evidence-based and accountability is visible.

Communication is a core part of OctoAcme's process and is intentionally regular and structured. The team follows a cadence that includes daily standups, weekly syncs between PM and product lead, periodic demos, and monthly stakeholder updates, while also using ad hoc escalations when blockers arise. Risk and dependency management is handled through a risk register and explicit escalation paths, so impacts are assessed early and communicated upward when issues become business critical or cross-team. Status updates are expected to use a single source of truth, and communication templates help keep information consistent across engineering, stakeholders, and support teams.

Quality assurance is built into the delivery workflow rather than treated as a last-minute step. The process asks teams to use small PRs, include issue links and acceptance criteria in pull requests, and require CI checks such as automated tests, linting, and security scanning before review. New logic should be covered by unit and integration tests, and critical user flows should receive smoke tests before release. Release and deployment follow defined checklists, rollback plans, and post-deploy verification, while retrospectives ensure that process improvements are tracked and incorporated over time.

## Table of Contents

- [Overview of OctoAcme Project Management Processes](#overview-of-octoacme-project-management-processes)
- [Quick Start](#quick-start)
- [Documentation by Lifecycle Phase](#documentation-by-lifecycle-phase)
  - [Overview](#overview)
  - [Initiation](#initiation)
  - [Planning](#planning)
  - [Execution](#execution)
  - [Release](#release)
  - [Close and Learn](#close-and-learn)
- [Role-Based Guides](#role-based-guides)
- [Core Principles](#core-principles)
- [How to Use These Documents](#how-to-use-these-documents)
- [Suggesting Improvements](#suggesting-improvements)

## Quick Start

New to OctoAcme projects? Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, lifecycle, roles, and key artifacts. Then review [OctoAcme Personas](./octoacme-roles-and-personas.md) to understand the responsibilities and communication patterns associated with common project roles.

For a specific project, follow the lifecycle from initiation through planning, execution, release, and retrospective. Use the relevant guide as a starting point, while keeping the project charter, backlog, risk register, status updates, and release information current in the project repository.

## Documentation by Lifecycle Phase

### Overview

- [Project Management Overview](./octoacme-project-management-overview.md) — Understand the overall lifecycle, operating principles, core roles, key artifacts, and communication cadence.

### Initiation

- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate the business need, define success metrics, identify stakeholders, create the initial project one-pager, and decide whether to proceed to planning.

### Planning

- [Project Planning](./octoacme-project-planning.md) — Turn an approved initiative into an actionable backlog, estimate scope, define the Definition of Done, identify dependencies, and create a release plan.

### Execution

- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day delivery through project boards, standups, delivery syncs, demos, pull requests, testing, reporting, and blocker escalation.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, assess, mitigate, monitor, and communicate risks and dependencies using a risk register, status updates, and defined escalation paths.

### Release

- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Prepare and deploy releases safely with acceptance checks, CI and security validation, smoke tests, release notes, rollback planning, and post-deployment verification.

### Close and Learn

- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture what went well, identify improvements, assign follow-up actions, and measure the impact of changes after sprints, releases, milestones, or incidents.

## Role-Based Guides

- **Product Managers:** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then use the [Project Initiation Guide](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) to define outcomes, prioritize work, and align stakeholders.
- **Project Managers:** Focus on [Execution & Tracking](./octoacme-execution-and-tracking.md), [Risk Management & Communication](./octoacme-risks-and-communication.md), and [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to coordinate delivery, manage risks, communicate status, and drive learning.
- **Developers and Delivery Teams:** Review [Project Planning](./octoacme-project-planning.md), [Execution & Tracking](./octoacme-execution-and-tracking.md), and [OctoAcme Personas](./octoacme-roles-and-personas.md) for backlog expectations, quality practices, collaboration, and technical responsibilities.
- **QA and Testing:** Use [Execution & Tracking](./octoacme-execution-and-tracking.md) and the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for test coverage expectations, smoke tests, acceptance validation, security scanning, and deployment verification.
- **Stakeholders and Leaders:** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then review [Risk Management & Communication](./octoacme-risks-and-communication.md) and the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for status, escalation, risk, and release information.
- **All Team Members:** Review [OctoAcme Personas](./octoacme-roles-and-personas.md) to understand how responsibilities and communication practices fit together.

## Core Principles

OctoAcme projects are guided by the following principles:

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments and use feedback to improve.
- **Clear ownership:** Every project has a named Project Manager and Product Lead.
- **Data-informed decisions:** Measure impact and use evidence to guide priorities and iteration.
- **Psychological safety:** Encourage feedback, learning, and constructive collaboration.

## How to Use These Documents

- Keep the project charter or one-pager current in the project repository.
- Maintain the backlog, milestones, dependencies, and Definition of Done as planning evolves.
- Keep the risk register and status information up to date during execution.
- Add process-specific supporting material to `.copilot/` when you want Copilot Spaces to use it as context.
- Use the checklists and templates in each guide to make project practices consistent and repeatable.

## Suggesting Improvements

These documents are living process references. If you identify a gap, clarification, or useful practice, open an issue using the process-document update template in `.github/ISSUE_TEMPLATE/`. Include the affected document, a summary of the proposed change, the rationale, and suggested content when available.
