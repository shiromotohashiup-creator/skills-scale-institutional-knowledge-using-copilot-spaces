# OctoAcme Project Management Docs

This README centralizes OctoAcme project management process documents. It provides a brief summary of the OctoAcme approach, direct links to each document in the docs/ folder, and guidance for how to use and maintain these artifacts.

Overview

OctoAcme’s project management approach is structured around clear initiation, planning, execution, and continuous improvement phases. Projects begin with a lightweight validation step—creating a Project One-pager that captures the problem, objective, success metrics, stakeholders, timeline, and risks—before moving into planning. Planning converts approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone plan. Key artifacts (one-pager, roadmap, backlog, risk register, release notes) are versioned in the repository so the project’s status and decisions are discoverable and auditable.

Workflows emphasize iterative delivery and disciplined task flow. Teams use a project board with columns like Backlog, Ready, In Progress, In Review, QA, and Done to visualize progress; sprint planning pulls DoD-ready items into an iteration using T-shirt sizing or story points. Pull request conventions require small PRs, links to the associated issue and acceptance criteria, and passing CI (tests and linters) before requesting review; at least one approval is required prior to merging. Release and deployment are governed by checklists and roll-back plans (staging smoke tests, production verification, release notes), and releases are categorized (patch/minor/major) with pre-release gates such as security scans and documented rollback procedures.

Roles and responsibilities are explicit and align to delivery needs: Product Managers define outcomes, prioritize the backlog, and measure success; Project Managers coordinate schedules, risks, and stakeholder communication; Developers implement and test features; QA validates acceptance criteria and runs manual or automated tests as appropriate; stakeholders provide approvals and domain inputs. Persona definitions are used to frame scenarios and ensure consistent handoffs—each project has named owners (PM and Product Lead) to ensure clear accountability across planning, execution, and release.

Communication is regular and intentional to surface progress and risks: daily standups for short progress and blocker triage, weekly delivery syncs to show progress and surface cross-team dependencies, dedicated PM–PdM syncs, and monthly or milestone-based stakeholder updates. Risk management uses a simple register (ID, impact/likelihood, owner, mitigation, status) and escalation paths that move from team-level triage up to sponsor-level for business-critical issues. Retrospectives after sprints or incidents capture action items, which are tracked into the backlog and reviewed in weekly PM syncs to close the loop on continuous improvement. Quality assurance combines automated unit/integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for acceptance as needed.

## Key workflows

- Initiation: create a One-pager (problem, goal, success metrics, stakeholders) and confirm go/no-go.
- Planning: prioritize and estimate backlog items, define DoD, and create a release/milestone plan.
- Execution: follow the project board, use small PRs with linked issues and acceptance criteria, require CI and at least one approval before merge.
- Release: follow release checklists (staging smoke tests, security scans, rollback plan) and categorize releases as patch/minor/major.
- Continuous improvement: run retrospectives and track action items into the project backlog.

## Process documents

- [Project Management Overview](./octoacme-project-management-overview.md) — concise intro to roles, principles, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — how to validate, authorize, and set up a new project
- [Project Planning](./octoacme-project-planning.md) — turning an initiative into an actionable plan and backlog
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — day-to-day execution, tracking, and reporting
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release types, checklists, and rollback playbook
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register and stakeholder communication templates
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — role definitions and responsibilities

## How to use

- Link this README from the repository root or include it in project READMEs to help team members find process docs quickly.
- Propose updates using the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.
- Keep each doc current; track stakeholder reviews where required.
