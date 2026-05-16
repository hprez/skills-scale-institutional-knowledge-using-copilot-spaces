# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process guidance and templates to help teams plan, deliver, and continuously improve work.

## Project Management Processes Overview
OctoAcme uses a lightweight, outcome-focused project management approach with these core phases:

- Project Initiation
  - Capture problem, goals, success metrics, and stakeholders.
  - Deliverable: Project One-pager and decision to proceed.

- Planning
  - Create prioritized backlog, estimate scope, define Definition of Done, and build a release/milestone plan.
  - Deliverables: Roadmap, backlog with acceptance criteria, release plan.

- Execution & Tracking
  - Work in small increments, use a project board to track status, and follow PR and CI conventions.
  - Activities: daily standups, weekly delivery sync, demos, CI test and security checks.

- Risk Management & Communication
  - Maintain a risk register, surface dependencies, and follow defined escalation paths.
  - Regular stakeholder updates (weekly or milestone-based) and incident communication templates.

- Release & Deployment
  - Pre-release checks, automated pipelines where possible, smoke tests, rollback plans, and release notes.

- Retrospective & Continuous Improvement
  - Capture what went well and action items after sprints, releases, or incidents and track improvements in the backlog.

- Roles & Personas
  - Clear role definitions (PM, PdM, Developers, QA, Stakeholders) to ensure ownership and efficient collaboration.

## Documentation Index
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

(Each link is relative to this docs/ folder. Click to open the detailed process document.)

## How to use these docs
- Read the Project Management Overview to understand roles and lifecycle.
- Use the Project Initiation and Planning guides to start new initiatives.
- Follow Execution & Tracking, Release, and Risk guides during delivery.
- Add action items from retros to the backlog and track them as issues.
- To make changes to process docs, use the issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Contribution & Review
- Proposed edits should be submitted as a pull request against this repository.
- Link PRs to the relevant process doc issue (if present) and include acceptance criteria.
- Small, focused PRs are preferred for easier review.

## Acceptance Criteria (for updates to these docs)
- Content aligns with existing process docs
- Update improves clarity or closes a documented gap
- Proposed content has been reviewed with stakeholders (if needed)

## Sample PR details (I will use these when creating the pull request)
- Branch: feature/add-octoacme-docs-readme-issue-2
- PR title: Add README for OctoAcme Project Management Docs
- PR body: Adds docs/README.md with links and an overview of OctoAcme project management processes. Linked to issue #2.
- Reviewers: hprez
