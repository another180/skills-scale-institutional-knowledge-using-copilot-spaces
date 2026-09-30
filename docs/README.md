# OctoAcme Project Management Process Docs

Welcome to the OctoAcme project management documentation. These guides standardize how we run projects across the organization, support clear ownership and alignment, and reinforce our customer-first and data-informed principles.

## Table of Contents

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
