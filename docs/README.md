# OctoAcme Project Management Documentation

## Overview

OctoAcme employs a comprehensive, phase-based project management approach that guides projects from initiation through retrospective and continuous improvement. Our methodology emphasizes clear roles, effective communication, risk management, and data-driven execution.

### Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to validate and improve continuously
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and open communication

### Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, context, and approvals

### Project Lifecycle

OctoAcme projects follow a structured lifecycle with five key phases:

1. **Initiation** - Validate business need, align stakeholders, create lightweight plan
2. **Planning** - Break work into shippable increments, identify dependencies and risks
3. **Execution** - Build, test, review, and iterate on deliverables
4. **Release** - Deploy to production, verify success, communicate outcomes
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

---

## Project Management Phases & Documentation

### 1. [Project Management Overview](./octoacme-project-management-overview.md)
Foundation document outlining OctoAcme's core principles, roles, key artifacts, and high-level project lifecycle. Start here to understand our overall approach.

**Key topics:**
- Principles and core roles
- Key artifacts and lifecycle overview
- Communication cadence

### 2. [Project Initiation](./octoacme-project-initiation.md)
Guide for validating and authorizing new work, aligning stakeholders, and creating a lightweight initial plan.

**Key topics:**
- Goals for initiation phase
- Project One-pager template
- Initiation checklist
- Decision gate for moving to planning

### 3. [Project Planning](./octoacme-project-planning.md)
Turn approved initiatives into actionable plans and prioritized backlogs for delivery.

**Key topics:**
- Activities: kickoff, backlog creation, estimation, dependencies
- Backlog item template
- Sprint/iteration planning
- Risk & dependency management
- Planning checklist

### 4. [Execution and Tracking](./octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution and tracking progress toward project milestones.

**Key topics:**
- Team rhythm (standups, delivery syncs, demos)
- Project board workflows
- Pull request conventions
- Quality & testing standards
- Reporting & metrics
- Blocker escalation
- Execution checklist

### 5. [Risks and Communication](./octoacme-risks-and-communication.md)
Explain how to identify, manage, and communicate risks and dependencies throughout the project lifecycle.

**Key topics:**
- Risk register structure and lifecycle
- Stakeholder communication strategies
- Communication templates (weekly status, incidents)
- Escalation paths

### 6. [Release and Deployment](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

**Key topics:**
- Release types (patch, minor, major)
- Pre-release requirements
- Deployment checklist
- Rollback & incident playbook
- Release notes template

### 7. [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements for the team and processes.

**Key topics:**
- When and how to run retrospectives
- Retrospective structure and timing
- Tracking and measuring improvements
- Action item template
- Building a continuous improvement culture

### 8. [Roles and Personas](./octoacme-roles-and-personas.md)
Define typical roles and responsibilities used in OctoAcme projects, including detailed persona descriptions.

**Key topics:**
- Developer responsibilities and goals
- Product Manager responsibilities and goals
- Project Manager responsibilities and goals
- How personas are used in exercises and scenarios

---

## Using This Documentation

**For new team members:**
- Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our framework
- Review [Roles and Personas](./octoacme-roles-and-personas.md) to understand team structure
- Dive deeper into phases relevant to your current project

**For project initiation:**
- Follow the [Project Initiation](./octoacme-project-initiation.md) guide and use the Project One-pager template

**For ongoing execution:**
- Reference the [Execution and Tracking](./octoacme-execution-and-tracking.md) guide for daily workflows
- Use the [Risks and Communication](./octoacme-risks-and-communication.md) guide for escalations and stakeholder updates

**Before release:**
- Follow the [Release and Deployment](./octoacme-release-and-deployment.md) guide and deployment checklist

**After completion:**
- Run a retrospective using [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- Capture action items and track improvements

---

## Quick Links

| Document | Purpose | Audience |
|----------|---------|----------|
| [Overview](./octoacme-project-management-overview.md) | Framework foundation | Everyone |
| [Initiation](./octoacme-project-initiation.md) | Project kickoff | PM, PdM, Leadership |
| [Planning](./octoacme-project-planning.md) | Detailed planning | PM, Developers, QA |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day work | Developers, QA, PM |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk management | PM, PdM, Leadership |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Go-to-production | Developers, DevOps, PM |
| [Retrospective & Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Learning & optimization | Everyone |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Role clarity | Everyone |

---

## Key Artifacts & Templates

Throughout the project lifecycle, use these key templates and artifacts:

- **Project One-pager** - Define problem, goal, success metrics, stakeholders, timeline, risks, and team (see [Initiation](./octoacme-project-initiation.md))
- **Backlog Item Template** - Structure work with title, description, acceptance criteria, priority, estimate, owner (see [Planning](./octoacme-project-planning.md))
- **Definition of Done** - Ensure consistent quality standards across delivery
- **Risk Register** - Track risks with ID, description, impact, likelihood, owner, mitigation (see [Risks & Communication](./octoacme-risks-and-communication.md))
- **Release Notes Template** - Communicate changes clearly to stakeholders (see [Release & Deployment](./octoacme-release-and-deployment.md))
- **Action Item Template** - Capture improvements with owner and due dates (see [Retrospective & Improvement](./octoacme-retrospective-and-continuous-improvement.md))

---

## Communication Cadence

- **Daily**: Team standups (15 min) - progress, blockers, dependencies
- **Weekly**: PM + PdM sync - alignment and prioritization
- **Twice-weekly**: Delivery team standups (or as agreed)
- **Monthly**: Stakeholder updates
- **Sprint/Milestone-based**: Demos and reviews
- **Ongoing**: Ad-hoc escalations and decision requests

---

## Getting Help

If you have questions about:
- **Which phase you're in**: See [Project Management Overview](./octoacme-project-management-overview.md)
- **How to structure your project**: See [Project Initiation](./octoacme-project-initiation.md)
- **How to plan and estimate work**: See [Project Planning](./octoacme-project-planning.md)
- **How to execute and report status**: See [Execution and Tracking](./octoacme-execution-and-tracking.md)
- **How to escalate risks or communicate**: See [Risks and Communication](./octoacme-risks-and-communication.md)
- **How to release safely**: See [Release and Deployment](./octoacme-release-and-deployment.md)
- **How to run retrospectives**: See [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Team roles and responsibilities**: See [Roles and Personas](./octoacme-roles-and-personas.md)

For updates or suggestions to this documentation, please open an issue using the [Process Doc Update template](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

---

*Last updated: 2026-09-29*
