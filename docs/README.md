# OctoAcme Project Management Documentation

Welcome! This directory contains the complete OctoAcme project management playbook. Whether you're new to the team or managing a complex initiative, you'll find guidance here for every phase of project delivery.

## About OctoAcme Project Management

OctoAcme follows a structured, iterative approach to project delivery grounded in five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

Our projects follow a structured lifecycle: **Initiation** → **Planning** → **Execution** → **Release** → **Close & Retrospective**.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Key Project Management Processes

### Initiation Phase
Projects begin with a **Project One-pager** that confirms business need, identifies stakeholders and champions, and defines success criteria. A decision gate ensures stakeholder alignment before moving to planning.

### Planning Phase
Teams break work into shippable increments, estimate scope (T-shirt sizing or story points), define acceptance criteria, and identify dependencies and risks. A prioritized backlog and release plan guide execution.

### Execution & Quality Assurance
Teams use GitHub Projects with standardized workflow columns and follow small PR practices (≤400 lines) with automated CI testing and linting. Quality is enforced through:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance

Daily standups (15 min) focus on progress and blockers, while weekly delivery syncs review progress and flagged risks.

### Risk Management & Communication
Risks are captured in a Risk Register (ID, Description, Impact, Probability, Owner, Mitigation, Status) and reviewed at weekly syncs. A multi-level escalation path (team → PM → Product Lead → Sponsor) manages blockers. Regular stakeholder communication uses weekly status templates and incident communications to maintain transparency.

### Release & Deployment
Pre-release requirements include passing CI scans, drafted release notes, and documented rollback plans. Deployments follow a structured checklist: staging verification, smoke tests, production deployment, post-deploy verification, and stakeholder announcement. If issues occur, a blameless incident response and rollback process is triggered.

### Retrospectives & Continuous Improvement
After each sprint, release, or milestone, teams conduct retrospectives to capture what went well, identify improvements, and assign action items to owners with clear timelines. These improvements feed back into the project backlog.

## Documentation by Phase

### Starting a Project
- [**Project Initiation Guide**](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and make a go/no-go decision
- [**Roles and Personas**](./octoacme-roles-and-personas.md) — Understand key roles and responsibilities

### Planning and Design
- [**Project Planning**](./octoacme-project-planning.md) — Break work into shippable increments and create actionable backlogs

### Day-to-Day Execution
- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Manage standups, sprints, quality, and progress tracking
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies

### Release and Beyond
- [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardize releases and manage incidents
- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Overview and Reference
- [**Project Management Overview**](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme processes, roles, and artifacts

## Quick Reference

- **How do I start a new project?** → See [Project Initiation Guide](./octoacme-project-initiation.md)
- **How do I set up a delivery team?** → See [Roles and Personas](./octoacme-roles-and-personas.md) and [Project Planning](./octoacme-project-planning.md)
- **How do I track progress?** → See [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **How do I handle risks and blockers?** → See [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **How do I release?** → See [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **How do I improve after a project?** → See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Getting Help

If you have questions about a process or need clarification, reach out to your Project Manager or Product Lead.
