# OctoAcme Project Management Processes

This repository centralizes OctoAcme’s proven project management workflows, making them accessible and repeatable for every team member. Below is an overview of our approach, based on practice and living documentation.

---

## Key Principles

- **Customer-first:** Projects prioritize customer value and usability.
- **Iterative delivery:** Work is completed in small, testable increments.
- **Clear ownership:** A Project Manager (PM) and Product Manager (PdM) are assigned for every initiative.
- **Data-informed decisions:** Success is measured and actions are adjusted based on real evidence.
- **Psychological safety:** Feedback and learning are encouraged throughout.

---

## Core Roles

- **Project Manager (PM):** Coordinates delivery logistics, risk, and communications.
- **Product Manager (PdM):** Defines measurable outcomes, prioritizes the backlog, and validates success.
- **Developers:** Build features, participate in design and code review, and support testing.
- **QA/Test:** Ensures acceptance criteria and quality benchmarks are met.
- **Stakeholders:** Contribute requirements and approve key decisions.

---

## Workflows and Communication

- **Artifacts:** Each project maintains a charter/one-pager, a roadmap, backlog, risk register, release notes, and retrospective actions.
- **Tools:** GitHub Project boards organize work from Backlog → Ready → In Progress → In Review → QA → Done.
- **Meetings:** Daily standups, weekly PM/PdM and team syncs, and monthly stakeholder briefings foster alignment.
- **Reporting:** Velocity, burndown, and key success metrics are tracked in dashboards.
- **Documentation:** All process docs live in the `docs/` folder for discoverability; status and decisions are logged for reference.

---

## Quality Assurance Practices

- **Testing:** Unit tests for new logic, integration tests where needed, and smoke tests for critical release flows.
- **Automation:** CI pipelines enforce linting, security scans, and test coverage.
- **Release Checklist:** Before deploying, acceptance criteria and all PRs must be completed, tests must pass, release notes drafted, and a rollback plan prepared.
- **Retrospectives:** Each milestone or incident prompts a retrospective to capture lessons learned and action items, driving continuous improvement.

---

This process-focused culture accelerates onboarding, raises transparency, and supports reliable delivery across all OctoAcme projects.