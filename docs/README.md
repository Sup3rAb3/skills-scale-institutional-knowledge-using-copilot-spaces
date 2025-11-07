# OctoAcme Project Management Docs

## What this folder is
This docs/ folder is the canonical hub for OctoAcme's project management processes, templates, role definitions, and runbooks. It centralizes initiation, planning, execution, release, risk, retrospective, and role guidance so teams can onboard quickly, run predictable projects, and continuously improve.

## Project management overview
OctoAcme runs projects through a lightweight, evidence-driven lifecycle: Initiation → Planning → Execution → Release → Close & Retrospective. Initiation captures the problem, SMART goals, stakeholders, and initial risks in a short Project One‑pager; this artifact aligns sponsors and forms the decision gate for planning. Planning turns approved initiatives into an actionable backlog and release plan through a kickoff, prioritized backlog items with acceptance criteria, estimates (T‑shirt sizing or story points), a Definition of Done, and an explicit Risk Register that lists owners and mitigations.

Day-to-day delivery follows a structured execution workflow supported by project boards and a disciplined PR/CI process: teams use board columns (Backlog → Ready → In Progress → In Review → QA → Done), keep PRs small and linked to issues and acceptance criteria, and require automated testing and at least one review before merging. Quality assurance is layered — unit and integration tests, end-to-end smoke checks for critical flows, security scanning in CI, and manual QA where required. Releases are classified (patch/minor/major) and follow pre-release and post-deploy checklists (staging smoke tests, rollback plan, release notes) plus an incident/rollback playbook when necessary.

Roles and communications are explicit and documented: Project Managers coordinate delivery, schedules, risks and stakeholder communication; Product Managers own outcomes and backlog prioritization; Developers implement and author tests; QA validates acceptance criteria; and Stakeholders provide approvals and remove organizational blockers. Teams keep a regular cadence (daily standups, weekly delivery syncs, PM/PdM alignment, and monthly stakeholder updates). Blockers escalate through defined paths (team triage → PM → Product Lead / dependent teams → Sponsor). Retrospectives after sprints, releases, or incidents produce prioritized action items tracked as issues; progress on those actions is reviewed in weekly PM syncs to drive continuous improvement.

## Key workflows & practices
- Initiation: Project One‑pager → stakeholder alignment → decision gate to planning.
- Planning: Kickoff → prioritized backlog with acceptance criteria → estimates → release plan → risk register.
- Execution: Project board + small PRs + CI + defined DoD; blocker escalation and weekly risk review.
- Release: Pre-release checks, staging smoke tests, automated pipeline deploy, post‑deploy verification, and rollback playbook.
- Continuous improvement: Timeboxed retrospectives, action items tracked as issues, regular review of outstanding actions.

## Files in this folder
- [octoacme-project-management-overview.md](octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](octoacme-project-initiation.md)
- [octoacme-project-planning.md](octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)

## How to contribute
Use the "Add Content to Project Management Process Docs" issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose additions or edits. For small changes, open a branch, update the relevant file, and open a PR requesting review from the PM/docs maintainers.

---

(Related issue: https://github.com/Sup3rAb3/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)
