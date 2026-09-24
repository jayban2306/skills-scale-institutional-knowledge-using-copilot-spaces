# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Executive Sponsors

### Role Summary
Executive Sponsors provide strategic sponsorship, organizational support, and escalation authority for projects. They ensure the initiative remains aligned with business priorities and has the resources needed to succeed.

### Responsibilities
- Confirm strategic alignment and sponsorship
- Secure organizational support and resolve resource constraints
- Make or facilitate escalated scope, priority, and trade-off decisions
- Remove organizational blockers beyond the delivery team's authority

### Interaction with Existing Roles
- Receive status, risk, and decision updates from the Project Manager
- Align with the Product Manager on desired outcomes and priority decisions
- Support Developers and other specialists by resolving organizational constraints rather than directing implementation

---

## Business Analysts

### Role Summary
Business Analysts translate stakeholder needs into clear requirements, workflows, impacts, and acceptance criteria. They help the team build a shared understanding of the problem before and during delivery.

### Responsibilities
- Elicit and document business and stakeholder requirements
- Map current and proposed workflows and identify impacts
- Clarify scope, assumptions, and acceptance criteria
- Identify gaps, dependencies, and process risks

### Interaction with Existing Roles
- Partner with the Product Manager on discovery, prioritization, and outcome definition
- Work with Developers to clarify expected behavior and edge cases
- Coordinate with the Project Manager to surface dependencies and maintain planning inputs
- Support QA/Testing by making requirements and acceptance criteria testable

---

## UX/UI Designers and User Researchers

### Role Summary
UX/UI Designers and User Researchers represent user needs through research, workflows, prototypes, visual designs, and usability validation. They help ensure that delivered solutions are useful, accessible, and understandable.

### Responsibilities
- Conduct or synthesize user research
- Create user journeys, wireframes, prototypes, and interface designs
- Validate usability and accessibility assumptions
- Document design decisions and user-centered acceptance considerations

### Interaction with Existing Roles
- Collaborate with the Product Manager to connect user evidence to product outcomes and priorities
- Work with Developers and Technical Leads to create feasible, maintainable designs
- Coordinate with QA/Testing on usability, accessibility, and experience-focused checks
- Provide the Project Manager with design dependencies and readiness updates

---

## Technical Leads and Architects

### Role Summary
Technical Leads and Architects guide technical direction, design decisions, integration approaches, and engineering quality for the project. They help the team manage technical complexity while preserving delivery focus.

### Responsibilities
- Define or review technical approaches and architecture
- Identify technical risks, dependencies, and integration points
- Support estimates, sequencing, and implementation decisions
- Establish appropriate engineering standards and review significant changes
- Help plan migration, observability, and maintainability needs

### Interaction with Existing Roles
- Guide Developers through design and implementation without replacing their delivery ownership
- Partner with the Project Manager on estimates, dependencies, risks, and sequencing
- Advise the Product Manager on technical trade-offs and scope implications
- Coordinate with Security, Privacy, or Compliance Leads and Release/DevOps Engineers on operational readiness

---

## Security, Privacy, and Compliance Leads

### Role Summary
Security, Privacy, and Compliance Leads identify applicable controls and risks and verify that the solution is ready to meet organizational, legal, and regulatory expectations.

### Responsibilities
- Identify security, privacy, and compliance requirements
- Review designs, data handling, access controls, and threat or impact assessments
- Define required controls, evidence, approvals, and release gates
- Coordinate remediation and escalate unresolved risks

### Interaction with Existing Roles
- Work with Technical Leads and Developers to design and implement appropriate controls
- Coordinate with QA/Testing on verification and evidence
- Advise the Project Manager on risk status, dependencies, and release readiness
- Help the Product Manager understand user, business, and regulatory trade-offs

---

## Release and DevOps Engineers

### Role Summary
Release and DevOps Engineers support reliable delivery through deployment automation, environment readiness, observability, and rollback capabilities.

### Responsibilities
- Maintain deployment pipelines and environment configuration
- Coordinate environment readiness and release automation
- Define or support monitoring, alerting, and operational verification
- Prepare rollback, recovery, and mitigation procedures
- Assist with post-deployment validation and incident response

### Interaction with Existing Roles
- Partner with Developers and Technical Leads on build, deployment, and operational concerns
- Coordinate with QA/Testing on staging validation and smoke tests
- Work with the Project Manager and Product Manager on release readiness, timing, and communication
- Provide evidence and support for security and compliance release gates

---

## Customer Support and Operations Representatives

### Role Summary
Customer Support and Operations Representatives prepare the organization to support, operate, and learn from the delivered solution after release. They provide practical feedback from customers and operational teams.

### Responsibilities
- Identify support, service, training, and operational readiness needs
- Prepare knowledge-base content, runbooks, training, and escalation paths
- Share customer and operational feedback with the delivery team
- Help monitor adoption, recurring issues, and post-release impact

### Interaction with Existing Roles
- Work with the Product Manager to connect customer feedback and adoption signals to product decisions
- Coordinate with the Project Manager on launch planning, communications, and readiness tracking
- Partner with Developers, Technical Leads, and Release/DevOps Engineers on triage and operational issues
- Collaborate with QA/Testing to ensure common support scenarios are covered

---

## Data and Analytics Owners

### Role Summary
Data and Analytics Owners define how project outcomes will be measured and ensure that instrumentation, reporting, and interpretation support informed decisions.

### Responsibilities
- Translate success metrics into measurement plans and data requirements
- Define instrumentation, dashboards, reporting, and data quality checks
- Establish baselines and support impact analysis after release
- Communicate findings, limitations, and recommendations

### Interaction with Existing Roles
- Partner with the Product Manager to define and evaluate success metrics
- Work with Developers and Technical Leads to implement reliable instrumentation
- Coordinate with the Project Manager on reporting milestones and decision logs
- Support retrospectives and release reviews with evidence about outcomes and usage

---

## Applying Personas Across Project Teams

- Engage each persona according to the project's scope, risks, customer impact, and lifecycle stage; not every project requires a dedicated person for every role.
- In small teams, one person may hold multiple personas, but decision ownership and accountability should still be documented.
- Project Managers coordinate cross-functional participation, while Product Managers retain ownership of product outcomes and Developers retain ownership of implementation quality.
- Use the relevant initiation, planning, execution, risk, release, and retrospective documents to record decisions, dependencies, readiness evidence, and follow-up actions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
