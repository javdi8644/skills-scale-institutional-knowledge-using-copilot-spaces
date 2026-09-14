# OctoAcme Project Management Documentation

## Overview
The OctoAcme project management framework provides standardized processes and guidance for delivering projects successfully across our organization. This documentation covers the complete project lifecycle — from ideation through retrospective — and emphasizes iterative delivery, clear ownership, data-informed decisions, and psychological safety. Teams validate ideas with a one‑pager, plan with prioritized backlogs and acceptance criteria, execute using a project board and small pull requests, and iterate through retrospectives and action items.

Core workflows include a stage-gated lifecycle (Initiation → Planning → Execution → Release → Retrospective), a project board with columns Backlog → Ready → In Progress → In Review → QA → Done, and a PR workflow that requires issue links, acceptance criteria, CI checks, and at least one approval before merging. Quality is enforced through unit and integration tests, smoke tests for critical flows, security scanning in CI, and manual QA as needed. Releases follow a staging→production pipeline with rollback plans and post‑deploy verifications.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement features and tests, and QA validates acceptance and quality. The docs include role-specific guidance and templates so each persona knows where to start and what artifacts to produce or review.

Communication is structured: daily standups for immediate progress and blockers, weekly delivery syncs for progress and risks, regular PM↔PdM alignment, and demos at the end of sprints or milestones. Stakeholder updates follow a weekly status template (progress, next steps, risks, asks) and escalation paths are defined (team → PM → Product Lead → Sponsor). Continuous improvement is driven by retrospectives with prioritized action items tracked back into the backlog.

## Quick Navigation

### Project Lifecycle
- **Initiation** — docs/octoacme-project-initiation.md — Validate business need, align stakeholders, create a one‑pager
- **Planning** — docs/octoacme-project-planning.md — Prioritize backlog, estimate scope, define Definition of Done
- **Execution** — docs/octoacme-execution-and-tracking.md — Manage day-to-day execution, PR and board conventions, escalation
- **Release** — docs/octoacme-release-and-deployment.md — Release types, pre-release checks, deployment checklist, rollback playbook
- **Retrospective** — docs/octoacme-retrospective-and-continuous-improvement.md — Run retros, track action items, close the loop

### Reference Guides
- docs/octoacme-project-management-overview.md — High-level approach, principles, key artifacts
- docs/octoacme-risks-and-communication.md — Risk register format, communication templates, escalation paths
- docs/octoacme-roles-and-personas.md — Role definitions and responsibilities

## Key Artifacts & Templates
- Project One‑pager / Charter
- Roadmap and Release Plan
- Sprint / Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## For Different Roles
- Project Manager: Start with docs/octoacme-project-management-overview.md → docs/octoacme-project-initiation.md → docs/octoacme-execution-and-tracking.md
- Product Manager: Begin with docs/octoacme-project-initiation.md → docs/octoacme-project-planning.md
- Developer / QA: See docs/octoacme-execution-and-tracking.md and docs/octoacme-release-and-deployment.md for workflow, tests, and deployment steps

## How to Contribute
If you identify gaps or improvements, submit an issue using the Add Content to Project Management Process Docs template:
../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
