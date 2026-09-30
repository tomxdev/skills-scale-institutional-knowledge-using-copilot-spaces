# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation collection. This repository contains comprehensive guidance, checklists, templates, and best practices for running projects at every stage of the lifecycle—from initiation through retrospective and continuous improvement.

## Overview of OctoAcme Project Management Processes

OctoAcme is a customer-first, iterative project management approach designed for cross-functional teams delivering product features, services, and integrations. The methodology is built on five core principles that guide all project work: prioritizing customer value and usability, delivering small testable increments, establishing clear ownership with named accountable roles, making data-informed decisions based on evidence, and fostering psychological safety to encourage feedback and learning.

The OctoAcme approach centers on well-defined roles and responsibilities. Project Managers coordinate delivery activities, manage schedules, risks, and communications to enable teams to deliver on commitments efficiently. Product Managers define what should be built to deliver customer and business value, owning the product vision, backlog prioritization, and outcome measurement. Developers implement features and fixes to meet acceptance criteria and quality standards while collaborating on design and testability. This clear role structure ensures accountability and streamlined decision-making across all projects.

Communication and quality assurance are fundamental to successful OctoAcme execution. Teams maintain a regular cadence including daily standups (15 minutes), weekly delivery syncs, and end-of-sprint demos, supplemented by monthly stakeholder updates and ad-hoc escalations as needed. Quality is embedded throughout the project lifecycle via unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Projects are tracked using GitHub Projects with columns (Backlog, Ready, In Progress, In Review, QA, Done), and pull requests follow a structured workflow with small PR sizes (≤400 lines when possible), required approvals, and automated testing before merge.

Risk management and continuous improvement round out the OctoAcme framework. A Risk Register captures risks by ID, description, impact, likelihood, owner, and mitigation plan, reviewed weekly during syncs. Retrospectives are held after each sprint, release, or milestone to capture learnings and drive actionable improvements. This culture of transparency, shared learning, and iterative refinement enables teams to execute reliably while continuously raising their delivery capabilities.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles with clear accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation** — Validate business need, identify stakeholders, define success criteria, and decide go/no-go for planning
2. **Planning** — Break work into shippable increments, identify dependencies, and create actionable backlog with acceptance criteria
3. **Execution** — Build, test, review, and iterate using daily standups and project board tracking
4. **Release** — Deploy to production with pre-release verification, smoke tests, and rollback plans
5. **Close & Retrospective** — Capture learnings, celebrate successes, and drive continuous improvement

## Documentation

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for a concise introduction to how OctoAcme runs projects, key roles, and artifacts
- **[Personas & Roles](octoacme-roles-and-personas.md)** — Understand the responsibilities and goals of Developers, Product Managers, and Project Managers

### Lifecycle Guides

- **[Project Initiation](octoacme-project-initiation.md)** — Validate ideas, align stakeholders, authorize work, and create a Project One-pager
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, define Definition of Done, and identify dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, run daily standups, use project boards, and escalate blockers
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize releases and deployments, prepare release notes, and execute rollback plans if needed
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, drive action items, and measure impact of improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, mitigate, and monitor risks; communicate status to stakeholders; escalate issues

## How to Use These Docs

- **Keep your Project Charter updated** in your project repo — use the One-pager template from the Initiation guide
- **Reference checklists and templates** during project execution — each guide includes actionable checklists to ensure completeness
- **Add process-specific docs to `.copilot/`** if you want Copilot Spaces to use them as context for your project
- **Share relevant docs with team members and stakeholders** — tailor your communication based on role and context
- **Review and iterate on processes** — treat these docs as living artifacts; capture feedback and continuous improvements through the process doc update issue template

## Process Documentation Template

To propose updates or additions to these process documents, use the **[Process Doc Update issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** in `.github/ISSUE_TEMPLATE/`. This ensures new content is reviewed for alignment with existing processes and organizational needs.

---

**Questions?** Refer to the specific lifecycle guide that matches your current project phase, or reach out to your Project Manager or Product Manager for guidance.
