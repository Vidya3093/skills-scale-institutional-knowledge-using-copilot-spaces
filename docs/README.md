# OctoAcme Project Management Docs

## Overview

OctoAcme's project management approach is built on five core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles (PM, Product Lead, Developers)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Lifecycle

OctoAcme projects follow a structured lifecycle:

1. **Initiation** - Define the problem, goals, and stakeholders
2. **Planning** - Break work into actionable tasks with clear acceptance criteria
3. **Execution** - Build, test, and iterate with regular team rhythm
4. **Release** - Deploy to production with quality gates and observability
5. **Retrospective** - Capture learnings and drive continuous improvement

## How OctoAcme Runs Projects

OctoAcme follows a structured, customer-first project lifecycle divided into five key phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. During initiation, teams validate business needs and align stakeholders by creating a lightweight Project One-pager that defines the problem, success metrics, and initial timeline. The planning phase transforms approved initiatives into actionable backlogs through a kickoff meeting, scope estimation, and dependency mapping. Execution relies on iterative delivery with small pull requests, automated CI/CD testing, and a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done). Release activities emphasize pre-deployment verification, smoke testing, and documented rollback procedures to minimize production risk.

OctoAcme defines clear ownership through three core delivery roles: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; and **Developers** implement features with high quality standards including unit tests, integration tests, and security scanning. Communication follows a consistent cadence with daily standups (15 min), weekly delivery syncs between PM and product leadership, and monthly stakeholder updates. Risk management is integral to every phase—teams maintain a risk register throughout the project, escalate blockers through a three-level hierarchy (team → PM → sponsor), and use weekly syncs to monitor and update status.

Quality and testing are embedded throughout execution rather than treated as a final gate. Teams practice small PRs (≤400 lines), require peer review and passing CI before merging, and execute unit tests, integration tests, and end-to-end smoke tests before release. The project board and metrics dashboards provide real-time visibility into progress, velocity, and key signals. After each sprint or milestone, OctoAcme conducts timeboxed retrospectives (45–75 minutes) to capture learnings and convert them into prioritized action items, reinforcing a culture of psychological safety and continuous improvement. This systematic approach ensures consistent, repeatable delivery while distributing knowledge and reducing single-person dependency risk across teams.

## Documentation

### Getting Started

- [Project Management Overview](octoacme-project-management-overview.md) - Start here for a concise introduction to OctoAcme's approach, roles, and key artifacts
- [Roles and Personas](octoacme-roles-and-personas.md) - Understand team roles and responsibilities

### By Project Phase

#### Initiation Phase

- [Project Initiation Guide](octoacme-project-initiation.md) - Validate business need, align stakeholders, and create a lightweight project plan

#### Planning Phase

- [Project Planning](octoacme-project-planning.md) - Turn an approved initiative into an actionable plan and backlog

#### Execution Phase

- [Execution & Tracking](octoacme-execution-and-tracking.md) - Manage day-to-day execution and track progress toward milestones
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies

#### Release Phase

- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Standardize how OctoAcme releases features to production

#### Retrospective Phase

- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive actionable improvements

## How to Use These Docs

- Keep your Project Charter updated in your project repo
- Add process-specific customizations to `.copilot/` if using Copilot Spaces
- Use the checklists and templates as starting points for your project workflow
