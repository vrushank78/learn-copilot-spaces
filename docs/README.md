# OctoAcme Project Management Docs

This README provides a short summary of OctoAcme's project management processes and links to the full, detailed documents stored in the docs/ folder.

## Brief overview

OctoAcme’s project management approach follows a lightweight lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation uses a Project One-pager to capture the problem, objective, success metrics, stakeholders, and a high-level timeline; teams use a decision gate to confirm readiness for planning. Planning focuses on a prioritized backlog with clear acceptance criteria, estimates, and a documented Definition of Done, producing a release and milestone plan that guides execution.

Execution emphasizes predictable delivery through a shared team rhythm: short daily standups for progress and blockers, weekly delivery syncs for cross-team coordination and risk discussion, and demos at the end of sprints or milestones. Work is tracked on a project board with columns like Backlog, Ready, In Progress, In Review, QA, and Done. Pull request and CI practices enforce small PRs, automated tests and linting, and at least one approval before merging to keep quality high.

Quality, risk, and release practices are integrated into the flow. Developers write unit and integration tests, QA runs manual or automated smoke tests for critical flows, and CI includes security scanning. Releases follow a checklist—passing CI, release notes, rollback plans, and staged smoke tests—plus an incident playbook for triage and rollback when needed. Risks are captured in a Risk Register (impact, likelihood, owner, mitigation) and reviewed in weekly syncs. Retrospectives convert learnings into tracked action items to drive continuous improvement.

## Docs index
- Project management overview: docs/octoacme-project-management-overview.md
- Project initiation guide: docs/octoacme-project-initiation.md
- Project planning: docs/octoacme-project-planning.md
- Execution & tracking: docs/octoacme-execution-and-tracking.md
- Risk management & communication: docs/octoacme-risks-and-communication.md
- Release & deployment: docs/octoacme-release-and-deployment.md
- Retrospective & continuous improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & personas: docs/octoacme-roles-and-personas.md

## How to use
- Link to this README from new project templates and the repository root to make these docs discoverable.
- Keep the docs/ folder updated and use the "Add Content to Project Management Process Docs" issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes.

---

*This README was created to provide a single entry point for OctoAcme's process documentation and to help onboard new contributors quickly.*
