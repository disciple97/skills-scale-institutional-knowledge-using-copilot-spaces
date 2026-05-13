# OctoAcme Process Documentation

This folder contains OctoAcme's project management process documents. The goal of these docs is to centralize project practices, make onboarding faster, and provide a consistent, versioned source of truth for how we plan, execute, release, and learn from work. These artifacts are intended to be the canonical reference for delivery teams and stakeholders.

Project management at OctoAcme follows a lightweight, lifecycle-driven approach. Initiation captures the problem, stakeholders, and success metrics in a Project One‑pager and confirms a go/no‑go decision. Planning turns approved initiatives into a prioritized backlog, defines a Definition of Done, sizes work, and produces a release plan. Execution uses iterative delivery with a project board (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests, CI gating, and clear acceptance criteria. Releases are classified as Patch, Minor, or Major; they require passing CI and security scans, smoke tests, release notes, and a rollback plan.

Roles and responsibilities are explicit so ownership is clear: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers own outcomes and prioritization; Developers implement and test features; QA validates acceptance criteria; and Stakeholders provide inputs and approvals. Communication cadence includes daily standups for the delivery team, weekly PM/PdM syncs, demos at the end of sprints or milestones, and monthly stakeholder updates. Risk escalation follows a team → PM → Product Lead → Sponsor path, with security incidents following the security runbook.

Quality assurance is enforced through automated unit/integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA when necessary. Pull requests should be small, link to their originating issue and acceptance criteria, and run CI before review and merge. Continuous improvement is implemented via regular retrospectives that produce prioritized action items tracked back into the backlog.

Quick links
- octoacme-project-management-overview.md — High-level principles, lifecycle, core roles, and artifacts.
- octoacme-project-initiation.md — One‑pager, initiation checklist, and decision gate.
- octoacme-project-planning.md — Backlog templates, planning cadence, and release planning.
- octoacme-execution-and-tracking.md — Project board workflow, PR guidance, CI, and metrics.
- octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook.
- octoacme-risks-and-communication.md — Risk register, stakeholder comms, and escalation paths.
- octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and action tracking.
- octoacme-roles-and-personas.md — Persona definitions and responsibilities.

How to use these docs
- Keep the Project One‑pager and project README updated in the project repo.
- Add process-specific files to `.copilot/` if you want Copilot Spaces to use them as context.
- Use the issue template ".github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml" to request edits or additions to process docs.
- When proposing changes, include the acceptance criteria and link to the originating issue so reviewers can validate alignment with program standards.
