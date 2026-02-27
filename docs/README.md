# OctoAcme Project Management Docs — README

This README is the central entry point for OctoAcme's project management process documentation. It summarizes our approach and links to detailed process guides kept in the docs/ folder. Use this page to quickly find templates, checklists, and role guidance for initiating, planning, executing, releasing, and improving work.

## Project Management Process Summary
OctoAcme follows an iterative, customer-first approach to deliver reliable outcomes:

- Initiation: Define the problem, success metrics, stakeholders, and decision gates (see Project Initiation Guide).
- Planning: Break work into shippable increments, create a prioritized backlog, estimate effort, and map milestones (see Project Planning).
- Execution: Run team rhythms (standups, delivery syncs), use the project board and PR workflow, run CI and testing, and track progress against milestones (see Execution & Tracking).
- Risks & Communication: Maintain a risk register, assess and mitigate risks, and communicate status and escalations to stakeholders (see Risk Management & Communication).
- Release & Deployment: Follow pre-release checks, automated deployments where possible, smoke tests, rollback plans, and release notes (see Release & Deployment Guide).
- Retrospective & Continuous Improvement: Capture learnings after milestones and incidents, convert into action items, and measure improvements (see Retrospective & Continuous Improvement).
- Roles & Personas: Clear responsibilities for PMs, PdMs, Developers, QA Lead, UX/UI Designer, Business Analyst, Operations Lead, Customer Success Manager, and Stakeholders (see Roles & Personas).

## Process Documents (docs/)
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risk Management & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment Guide — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md
- Cross-Functional Onboarding Checklist — docs/octoacme-cross-functional-onboarding-checklist.md

## How to use these docs
- Start here when onboarding to a project: read the Overview and the relevant process guide for the project stage you are owning.
- Keep your project One-pager and Project README in the project repo up to date with links to these process docs.
- Add process-specific playbooks or artifacts into `.copilot/` if you want Copilot Spaces to use them as context for automated assistance.
- When updating process docs, use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` issue template to propose changes so reviewers can evaluate alignment and acceptance criteria.

## Navigation tips for contributors
- If you are adding or updating a process doc, open an issue using "Add Content to Project Management Process Docs" issue template (see .github/ISSUE_TEMPLATE/).
- Propose changes as small, reviewable PRs and link them to the originating issue.
- Keep language concise and include checklists or templates whenever helpful.

## Maintenance
- Owners: Project Managers and Product Leads should keep this README and the linked docs accurate for active projects.
- Review cadence: Review process docs at least once per quarter or after any major process change.
