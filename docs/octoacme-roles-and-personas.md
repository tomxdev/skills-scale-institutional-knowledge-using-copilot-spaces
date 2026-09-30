# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign only the roles needed for a project, but make accountability and decision rights explicit. A person may hold more than one role on a small team.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Project Sponsor / Executive Sponsor

### Role Summary
The Project Sponsor provides strategic sponsorship, confirms priority and funding, and makes or escalates decisions that exceed the delivery team's authority.

### Responsibilities
- Confirm the business case, priority, scope boundaries, and success expectations
- Approve significant scope, budget, timeline, or risk trade-offs
- Remove organizational obstacles and secure cross-team support
- Participate in initiation and decision gates
- Sponsor escalations when business impact requires executive action

### Interactions with Existing Roles
- Receives status, risk, and decision updates from the Project Manager
- Aligns with the Product Manager on outcomes, priority, and major trade-offs
- Supports Developers and technical leads by resolving organizational constraints
- Provides direction to stakeholders when priorities or approvals are unclear

---

## Business Analysts

### Role Summary
Business Analysts translate business needs into detailed requirements, workflows, acceptance criteria, and traceability that the delivery team can implement and validate.

### Responsibilities
- Elicit and document business rules, user needs, and process flows
- Refine backlog items and identify gaps or ambiguity
- Define measurable acceptance criteria with product and delivery teams
- Maintain requirements traceability through delivery and change control
- Help assess the impact of proposed scope changes

### Interactions with Existing Roles
- Partners with the Product Manager and stakeholders to clarify needs and priorities
- Supports the Project Manager with scope, dependency, and change information
- Works with Developers and technical leads to explain expected behavior
- Collaborates with QA/Testing to ensure requirements are testable and covered

---

## UX/UI or Service Designers

### Role Summary
UX/UI and Service Designers represent user needs and service usability through research, journeys, prototypes, interaction designs, and design validation.

### Responsibilities
- Research user needs, workflows, accessibility considerations, and pain points
- Create journeys, prototypes, and interface or service designs
- Validate concepts with users and incorporate feedback
- Document usability and accessibility requirements
- Partner with the team to maintain design consistency through implementation

### Interactions with Existing Roles
- Collaborates with the Product Manager and Business Analyst to connect user needs to outcomes and requirements
- Works with Developers and technical leads to assess feasibility and support implementation
- Partners with QA/Testing to define usability and accessibility checks
- Uses Customer Success / Support feedback and stakeholder input to validate designs

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide technical direction, design decisions, non-functional requirements, and technical risk management for the project.

### Responsibilities
- Define and communicate the technical approach and key design decisions
- Identify architecture, integration, scalability, reliability, and maintainability risks
- Establish non-functional requirements and technical acceptance expectations
- Support estimates, sequencing, dependency analysis, and technical trade-offs
- Ensure technical decisions are documented and understood by the delivery team

### Interactions with Existing Roles
- Works with Developers on implementation, reviews, and technical problem solving
- Advises the Project Manager on dependencies, estimates, risks, and sequencing
- Partners with the Product Manager on scope and outcome trade-offs
- Coordinates with Security/Privacy and Release/DevOps roles on controls and operability

---

## Delivery or Engineering Leads

### Role Summary
Delivery or Engineering Leads coordinate engineering execution, capacity, technical sequencing, and delivery health while preserving clear ownership within the team.

### Responsibilities
- Coordinate implementation flow, capacity, and engineering commitments
- Surface delivery impediments and resource constraints early
- Help sequence work and manage technical dependencies
- Support consistent engineering practices, reviews, and Definition of Done expectations
- Provide delivery health information for planning and status reporting

### Interactions with Existing Roles
- Works with the Project Manager on commitments, risks, dependencies, and reporting
- Partners with the Product Manager on scope trade-offs and backlog readiness
- Coordinates Developers and QA/Testing toward completed, releasable increments
- Collaborates with the Technical Lead on architecture and with Release/DevOps on delivery readiness

---

## Release / DevOps / Site Reliability Engineers

### Role Summary
Release, DevOps, or Site Reliability Engineers provide deployment automation, environment management, observability, operational readiness, and rollback support.

### Responsibilities
- Maintain deployment pipelines, environments, and release controls
- Define operational readiness, monitoring, alerting, and rollback requirements
- Support staging validation, production deployment, and post-deployment verification
- Identify reliability, capacity, and operational risks
- Participate in incident response and post-incident improvement actions

### Interactions with Existing Roles
- Partners with Developers and Technical Leads on deployability, reliability, and observability
- Works with QA/Testing on environment readiness and smoke tests
- Coordinates with the Project Manager on release schedules, risks, and status
- Collaborates with Security/Privacy on pipeline and infrastructure controls

---

## Security / Privacy Representatives

### Role Summary
Security and Privacy Representatives advise on security, privacy, compliance, and risk acceptance throughout the project lifecycle.

### Responsibilities
- Identify security and privacy requirements and applicable obligations
- Support threat modeling, data classification, and risk assessments
- Advise on security testing, access controls, and secure design
- Review residual risk and document mitigation or acceptance decisions
- Coordinate security incident escalation according to the relevant runbook

### Interactions with Existing Roles
- Engages early with the Product Manager and Business Analyst to identify requirements
- Works with Technical Leads, Developers, and Release/DevOps on controls and implementation
- Partners with QA/Testing on security test coverage and evidence
- Escalates material residual risk to the Project Manager and Project Sponsor

---

## Data / Analytics Representatives

### Role Summary
Data and Analytics Representatives define instrumentation, measurement plans, data quality expectations, dashboards, and outcome reporting.

### Responsibilities
- Translate product success metrics into measurable events and data requirements
- Define instrumentation, data quality checks, and reporting ownership
- Build or coordinate dashboards for usage, performance, and business outcomes
- Validate that measurements support decision-making after release
- Identify data risks, privacy considerations, and interpretation limits

### Interactions with Existing Roles
- Works with the Product Manager to define success metrics and evaluate outcomes
- Partners with Developers and Technical Leads on telemetry and data implementation
- Collaborates with QA/Testing to validate event accuracy and reporting behavior
- Provides the Project Manager and Sponsor with evidence for status and investment decisions

---

## Customer Success / Support Representatives

### Role Summary
Customer Success or Support Representatives bring customer needs, support trends, readiness concerns, and feedback into planning, delivery, and release activities.

### Responsibilities
- Share customer feedback, support patterns, and recurring pain points
- Identify customer-facing risks and operational readiness needs
- Review release communications, support content, and escalation procedures
- Help validate that changes address customer needs and are supportable
- Report post-release feedback and adoption issues to the project team

### Interactions with Existing Roles
- Partners with the Product Manager and UX/UI or Service Designer on customer needs
- Works with the Project Manager on readiness, communications, and escalation
- Collaborates with QA/Testing on acceptance scenarios based on real customer workflows
- Coordinates with Release/DevOps and Change/Adoption roles on launch support and enablement

---

## Change / Adoption Managers

### Role Summary
Change and Adoption Managers plan training, enablement, stakeholder adoption, and organizational transition for changes that affect users or operating processes.

### Responsibilities
- Assess change impact, readiness, and adoption risks
- Define training, enablement, communication, and rollout plans
- Coordinate stakeholder readiness activities and feedback loops
- Establish adoption measures and track progress after release
- Identify resistance or capability gaps and propose mitigations

### Interactions with Existing Roles
- Works with the Project Manager on readiness plans, milestones, risks, and communications
- Partners with the Product Manager on expected user outcomes and adoption metrics
- Coordinates with Customer Success / Support on training and support materials
- Engages the Project Sponsor and stakeholders when adoption barriers require leadership action

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign only the roles needed for a project, and name a primary accountable owner when responsibilities overlap.
- For complex initiatives, use a lightweight RACI or lifecycle matrix to document who is responsible, accountable, consulted, and informed during initiation, planning, execution, release, and retrospective activities.

