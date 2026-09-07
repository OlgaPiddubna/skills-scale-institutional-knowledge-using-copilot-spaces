# OctoAcme Project Management Docs

## Welcome

This directory contains the complete OctoAcme project management framework, designed to provide clear, consistent guidance for running successful projects across the organization.

## Quick Start

New to OctoAcme projects? Start here:
1. Read the [Project Management Overview](./octoacme-project-management-overview.md) for high-level principles and roles
2. Follow the lifecycle phases below based on your project stage

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework consists of five primary phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (day-to-day delivery with continuous tracking), **Release** (standardized deployment with risk mitigation), and **Close & Retrospective** (capturing learnings for improvement). Each phase is supported by lightweight, well-defined artifacts—such as a Project One-pager, prioritized backlog, risk register, and release notes—that serve as single sources of truth for the project.

The organization operates with clearly defined roles that enable efficient collaboration: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** own the vision, prioritize the backlog, and measure outcomes; **Developers** implement features while contributing to design and risk identification; and **QA/Testing** ensures quality and acceptance criteria compliance. OctoAcme's communication strategy is built on structured cadences and transparency, with daily standups (15 minutes) focused on progress and blockers, weekly delivery syncs to review progress and flagged risks, and monthly stakeholder updates. A clear escalation path—team-level → PM → Product Lead → Sponsor—ensures that risks and decisions move appropriately through the organization.

Quality and delivery excellence are embedded throughout OctoAcme's execution model. The team uses GitHub Projects for workflow management, enforces small pull requests (≤400 lines), requires automated testing and linting in CI before review, and demands at least one approval before merge. Quality assurance includes unit tests, integration tests, smoke tests for critical flows, and security scanning in CI. Post-release, the team captures retrospective learnings and converts them into prioritized action items, creating a continuous improvement cycle.

## Project Lifecycle

### 1. [Initiation](./octoacme-project-initiation.md)
Validate business need, align stakeholders, and create initial project one-pager. Define success criteria and confirm go/no-go for planning.

**Key Deliverables:**
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and key milestones
- Initial risk list

### 2. [Planning](./octoacme-project-planning.md)
Turn approved initiatives into actionable plans and prioritized backlogs. Break work into shippable increments with clear acceptance criteria.

**Key Activities:**
- Project kickoff meeting
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and integration points
- Create release plan and milestone map

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
Manage day-to-day delivery, track progress toward milestones, and escalate blockers. Maintain team rhythm with standups, syncs, and demos.

**Key Practices:**
- Daily standups (15 min) and weekly delivery syncs
- GitHub Projects workflow (Backlog → Ready → In Progress → In Review → QA → Done)
- Small PRs (≤400 lines) with automated tests and linting
- Regular demos and risk register updates

### 4. [Release & Deployment](./octoacme-release-and-deployment.md)
Standardize releases to production with proper verification, rollback planning, and risk mitigation.

**Key Steps:**
- Pre-release verification (acceptance criteria met, CI passing, security scans complete)
- Deploy to staging with smoke tests
- Deploy to production via automated pipeline
- Run post-deploy verifications and announce to stakeholders

### 5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements. Run retrospectives after sprints, releases, or important milestones.

**Key Outcomes:**
- What went well / what could be improved
- Prioritized action items with owners and due dates
- Follow-up on previous action items

## Cross-Cutting Concerns

- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies. Maintain risk registers, stakeholder communication, and escalation paths.
- [**Roles & Personas**](./octoacme-roles-and-personas.md) — Understand key roles and responsibilities across Project Managers, Product Managers, Developers, and QA/Testing.

## How to Use These Docs

- **Keep the Project Charter updated** in your project repo
- **Reference relevant sections** as your project progresses through lifecycle phases
- **Add project-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Use templates** provided in each phase document for checklists, one-pagers, and status reports
- **Link back to this README** when onboarding new team members

---

**Questions?** Refer to the specific lifecycle phase document or the Project Management Overview for detailed guidance.
