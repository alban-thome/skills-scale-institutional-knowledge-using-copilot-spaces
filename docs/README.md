# OctoAcme Project Management Docs README

This directory contains OctoAcme's program and project management process documents. The README below provides a concise overview of our approach and direct links to each detailed document in /docs so contributors and stakeholders can find guidance quickly.

OctoAcme follows a lightweight, iterative project lifecycle: initiation, planning, execution, release, and continuous improvement. Initiation focuses on validating a business need and capturing measurable outcomes in a Project One-pager (problem, goal, success metrics) and aligning stakeholders before moving into planning. Planning breaks approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, and an identified set of risks and dependencies.

Execution emphasizes small, testable increments and a steady team rhythm: daily standups, weekly delivery syncs, and end-of-sprint demos. Work moves through a project board (Backlog → Ready → In Progress ��� In Review → QA → Done) and follows PR conventions that enforce CI, linked acceptance criteria, and required reviews. Release and deployment are guarded by pre-release checks (CI/security scans, smoke tests, rollback plans) and post-deploy verifications. Retrospectives capture learnings, create a small set of actionable improvements, and feed those improvements back into the backlog.

Roles are clear: Product Managers define outcomes and prioritize work; Project Managers coordinate delivery, risk, and stakeholder communication; Developers implement and test features; QA validates acceptance criteria and critical flows. A Risk Register, release checklist, and the issue template for updating process docs help keep processes versioned and discoverable.

## Links to process documents

- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-roles-and-personas.md

## How to use

- Propose changes using the "Add Content to Project Management Process Docs" issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
- Keep the README and docs/ updated as processes evolve and after stakeholder review.
