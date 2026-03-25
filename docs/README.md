# OctoAcme Project Management Docs

This directory contains the official documentation for OctoAcme's project management processes. These documents define how OctoAcme teams plan, execute, communicate, and continuously improve across all projects. Whether you are a new team member or a seasoned contributor, this documentation provides the shared language and workflows that keep delivery predictable and customer-focused.

## Overview

OctoAcme follows an iterative, customer-first project lifecycle with clear ownership, defined artifacts, and decision gates at each phase. Projects begin with an **Initiation** phase where teams create a project one-pager capturing the problem statement, goals, and success metrics, alongside a stakeholder list, communication plan, high-level timeline, initial risk assessment, and resource needs. A formal decision gate ensures work only proceeds when success metrics, priority, and team availability are clearly established.

During the **Planning** phase, teams run a kickoff meeting and build a prioritized backlog with acceptance criteria, estimates, and a documented Definition of Done. Dependencies and integration points are identified early, and a release plan with milestone map, QA approach, and risk register are put in place. **Execution and tracking** are managed through a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Teams hold daily standups, weekly delivery syncs, and end-of-sprint demos to maintain visibility. Pull requests are kept small, linked to issues and acceptance criteria, and require passing CI checks plus at least one approval before merging.

OctoAcme's **communication and escalation** model centers on regular status updates (weekly or at milestones) and a single source of truth—either the project README or a release document—for current project status. The escalation path flows from the team to the Project Manager, then to the Product Lead, and finally to the project Sponsor when needed. Incident communications follow a defined protocol, and all incidents conclude with a blameless post-incident retrospective. Key roles include the **Project Manager** (delivery, schedule, risks, and communications), the **Product Manager** (outcomes and prioritization), **Developers** (build, test, review, and documentation), **QA/Testing** (acceptance criteria validation), and **Stakeholders** (input and approvals).

**Quality assurance and release** practices require unit and integration tests, smoke tests for critical flows, and security scanning in CI for every change. The release checklist covers acceptance criteria sign-off, passing CI and security scans, release notes, a rollback plan, staging deploy with smoke tests, production deploy, post-deploy verification, and stakeholder announcements. After each sprint, release, or incident, teams conduct **retrospectives** to capture action items with owners and due dates, which are reviewed during the weekly PM sync to drive continuous improvement.

## Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
