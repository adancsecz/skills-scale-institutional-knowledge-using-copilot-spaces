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

## Release Manager

### Role Summary
Release Managers own release readiness and coordinate release execution, approvals, dependencies, rollback decisions, and communication.

### Responsibilities
- Maintain the release plan and go/no-go readiness criteria
- Coordinate approvals, dependencies, and deployment windows
- Define rollback criteria and coordinate rollback decisions
- Communicate release status and impact to stakeholders

### Interactions
- Partners with Project Managers on schedules, risks, and cross-team dependencies.
- Coordinates with Developers on deployment readiness, fixes, and rollback procedures.
- Works with QA/Testing and Operations/SRE to confirm validation and operational readiness.
- Keeps stakeholders informed of release timing, changes, and customer impact.

### Lifecycle Touchpoints
Planning, execution, release and deployment, and post-release review.

---

## Security Lead

### Role Summary
Security Leads define security requirements and risk expectations, review threats and mitigations, and support incident response.

### Responsibilities
- Establish security requirements and risk-review practices
- Review threats, mitigations, vulnerabilities, and security exceptions
- Provide guidance for secure design and implementation
- Support security incident escalation and response

### Interactions
- Works with Product Managers to assess security trade-offs and prioritize mitigations.
- Advises Developers on secure implementation and reviews high-risk changes.
- Coordinates security validation with QA/Testing and Operations/SRE.
- Raises security schedule or scope impacts to Project Managers.

### Lifecycle Touchpoints
Initiation, planning, design, execution, release readiness, and retrospectives.

---

## Customer/Business Analyst

### Role Summary
Customer/Business Analysts gather, clarify, and prioritize stakeholder and customer needs, converting them into actionable requirements and acceptance criteria.

### Responsibilities
- Research stakeholder and customer needs
- Translate needs into requirements, process flows, and acceptance criteria
- Maintain traceability between needs, decisions, and delivered outcomes
- Coordinate validation and feedback

### Interactions
- Partners with Product Managers on scope, backlog priorities, and requirement trade-offs.
- Clarifies requirements with Developers and QA/Testing.
- Provides structured stakeholder and customer feedback to the delivery team.
- Supports Project Managers with scope and dependency clarification.

### Lifecycle Touchpoints
Initiation, discovery, planning, execution, validation, and outcome review.

---

## Support Lead

### Role Summary
Support Leads prepare support teams for launches and represent ongoing customer issues and operational impact.

### Responsibilities
- Prepare support content, routing, escalation paths, and launch readiness
- Aggregate and classify customer issues
- Identify systemic problems and recurring trends
- Communicate customer impact and resolutions to delivery teams and stakeholders

### Interactions
- Coordinates with Release Managers and Operations/SRE on launch readiness and operational handoff.
- Provides Product Managers and Developers with customer feedback and defect patterns.
- Shares project and launch impact updates with stakeholders.
- Participates in retrospectives to improve future readiness and issue handling.

### Lifecycle Touchpoints
Planning, release and deployment, stabilization, and retrospectives.

---

## Data/Analytics Lead

### Role Summary
Data/Analytics Leads define how project success will be measured, validate measurement plans, analyze outcomes, and highlight data-driven risks.

### Responsibilities
- Define success metrics and measurement hypotheses
- Build or validate instrumentation and reporting plans
- Analyze delivery and outcome data
- Escalate significant trends, quality concerns, or invalid assumptions

### Interactions
- Works with Product Managers to establish outcome metrics and interpret results.
- Coordinates with Developers on instrumentation, data quality, and observability.
- Provides Project Managers with evidence for status, decisions, and risk updates.
- Shares findings with stakeholders and the team during reviews and retrospectives.

### Lifecycle Touchpoints
Initiation, planning, execution, release validation, and outcome review.

---

## UX/Design Lead

### Role Summary
UX/Design Leads lead user research and interaction design, validate usability, and maintain accessibility and design-consistency standards.

### Responsibilities
- Plan and conduct or coordinate user research
- Design workflows and interactions that meet user and business needs
- Provide implementation specifications and design guidance
- Validate usability, consistency, and accessibility considerations

### Interactions
- Partners with Product Managers and Customer/Business Analysts on needs, priorities, and acceptance criteria.
- Works with Developers on feasibility and implementation quality.
- Coordinates experience validation with QA/Testing and Accessibility Leads.
- Incorporates stakeholder feedback into design decisions and communicates trade-offs.

### Lifecycle Touchpoints
Initiation, discovery, planning, design, execution, validation, and retrospectives.

---

## Accessibility Lead

### Role Summary
Accessibility Leads establish accessibility requirements and review practices, identify barriers, and advise delivery teams on remediation.

### Responsibilities
- Define applicable accessibility requirements and acceptance criteria
- Review designs and implementations for barriers
- Coordinate accessibility testing and remediation priorities
- Advise on exceptions, trade-offs, and escalation decisions

### Interactions
- Works with UX/Design Leads to incorporate inclusive design practices.
- Advises Developers on implementation and remediation.
- Coordinates conformance validation and defect triage with QA/Testing.
- Escalates scope or schedule impacts to Product and Project Managers.

### Lifecycle Touchpoints
Planning, design, execution, release readiness, and validation.

---

## Operations/SRE Lead

### Role Summary
Operations/SRE Leads own operational readiness, monitoring, reliability targets, capacity, incident response, and post-release stability.

### Responsibilities
- Define operational readiness, reliability, and capacity expectations
- Plan and review monitoring, alerting, and incident-response processes
- Coordinate operational testing and release stabilization
- Lead or support incident review and resilience improvements

### Interactions
- Coordinates with Release Managers on deployment readiness and rollback operations.
- Works with Developers on observability, resilience, fixes, and service ownership.
- Validates reliability practices with QA/Testing and Security Leads.
- Raises operational risks and readiness gaps to Project Managers and stakeholders.

### Lifecycle Touchpoints
Planning, execution, release and deployment, incident response, stabilization, and retrospectives.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
