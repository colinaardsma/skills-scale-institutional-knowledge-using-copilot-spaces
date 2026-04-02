# OctoAcme Project Management Docs — Overview & Directory

Welcome — this README is the entry point for OctoAcme’s project management processes. It summarizes the core workflows, personas, communication practices, and quality controls used to plan, deliver, and improve projects. Use this page to quickly find the detailed process documents stored in this folder.

OctoAcme organizes project work around a lightweight, repeatable lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. Initiation captures the problem, target outcome, success metrics, and key stakeholders in a Project One-pager. Planning breaks approved work into shippable backlog items with clear acceptance criteria, estimates, and owners; it produces a release plan and a Definition of Done. Execution runs against a project board with visible states (Backlog → Ready → In Progress → In Review → QA → Done), uses small PRs linked to issues, and follows CI/test gating and peer review before merges. Releases follow a checklist approach (staging smoke tests, rollback plan, post-deploy verification) and incidents follow the incident playbook.

Roles and responsibilities are explicit so ownership and escalations are clear: Product Managers define outcomes and success metrics, Project Managers coordinate schedules, risks, and stakeholder communications, Developers implement and test features, QA validates acceptance criteria, and Stakeholders provide input and approvals. Core artifacts (Project One-pager, roadmap/release plan, sprint backlog, acceptance criteria, risk register, and retrospective action items) anchor decision-making and transparency.

Communication is structured to reduce ambiguity: daily standups, a regular weekly delivery sync for progress and risk, demos or reviews at the end of each sprint/milestone, and stakeholder updates (weekly or monthly as appropriate). Reporting emphasizes measurable signals (velocity/burndown, success metrics) and dashboards for operational health (errors, latency, usage). Continuous improvement is enforced via retrospectives that produce 2–3 action items tracked back into the backlog so improvements are owned and measured.

## Docs directory (click to open)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs
- Keep the Project One-pager and release notes updated in each project’s repo.
- Add process-specific project details into `.copilot/` if you want Copilot Spaces to use them for context.
- Treat these documents as living artifacts — propose improvements via the “Add Content to Project Management Process Docs” issue template.

## Acceptance criteria for this README
- Content aligns with existing process docs in this folder.
- Improves clarity or closes a documented gap.
- Reviewed by the appropriate stakeholders (PM / Product Lead).

> These documents are living—improvements and additions are always welcome. To propose a change, open the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.