# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This README is the single entry point to our program management practices, key artifacts, and process guides. Use these docs to onboard new team members, maintain consistent delivery approaches across projects, and find templates and checklists for initiation, planning, execution, release, and continuous improvement.

Overview
OctoAcme runs projects with a customer-first, iterative approach that emphasizes small, testable increments and rapid feedback. Projects start with a lightweight initiation (one‑pager and stakeholder alignment), move into focused planning where scope is broken into prioritized backlog items with clear acceptance criteria, and proceed to execution using a project board workflow. Releases are staged with pre-release checks and smoke tests, and every project closes with a retrospective to capture learnings and action items.

Key workflows and roles
Work is managed on a columnar project board (Backlog → Ready → In Progress → In Review → QA → Done) and delivered through small, focused pull requests that include linked issues and acceptance criteria. Core personas are explicit: Project Manager (delivery coordination, risk, communication), Product Manager (outcomes, prioritization), Developers (implement and test), QA (validate acceptance), and Stakeholders (input/approvals). Regular team rhythms — daily standups, weekly delivery syncs, demos, and stakeholder updates — keep decisions visible and reduce surprises.

Communication and quality assurance
Communication is transparent and purpose-driven: weekly status templates, an escalation path (Team → PM → Product Lead → Sponsor), and a living risk register are used to keep stakeholders informed. Quality is built into the pipeline: unit/integration tests, CI security scans, end‑to‑end smoke tests for critical flows, and manual QA when needed. Pull requests should pass automated checks and require approval per repository policy. Releases follow a checklist (passing CI, release notes, rollback plan, staged verifications) and include an incident/rollback playbook.

Process Document Links
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

Acceptance Criteria
- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

How to contribute
To propose edits, open a branch and submit a pull request that updates this README or any of the linked process docs. For changes that affect multiple docs, include a short summary in the PR body explaining the cross-document update and call out any stakeholders to review.