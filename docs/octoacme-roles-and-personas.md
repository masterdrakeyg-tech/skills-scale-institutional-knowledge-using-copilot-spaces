# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assignments may vary by project size; one person may cover multiple roles, but ownership and decision-making responsibilities should remain explicit.

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

## QA/Testing Leads

### Role Summary
QA/Testing Leads guide the team's approach to verifying product quality and confirming that delivery meets acceptance criteria. Depending on team structure, this responsibility may be held by a dedicated tester or shared among team members.

### Responsibilities
- Define and communicate a risk-based test strategy and test coverage
- Coordinate test planning and validation across unit, integration, end-to-end, and manual testing as appropriate
- Surface quality gaps, defects, and release risks, and track them through resolution or an explicit decision
- Ensure test results and known limitations are visible to the team

### Goals
- Provide timely, useful evidence about quality and release readiness
- Reduce escaped defects and prevent avoidable regressions
- Make quality expectations and unresolved risks clear

### Typical Communication and Interactions
- Work with Product Managers to clarify acceptance criteria and edge cases
- Partner with Developers on testability, automated tests, and defect investigation
- Coordinate with Project Managers on quality risks, milestones, and dependencies
- Share test outcomes and release concerns with Release Managers and Support/Operations Leads

---

## UX/Design Leads

### Role Summary
UX/Design Leads represent user needs in the delivery process and guide the design of accessible, coherent experiences. The role may be combined with product responsibilities on smaller teams.

### Responsibilities
- Research user needs and translate findings into workflows, prototypes, or design specifications
- Define and communicate interaction, usability, and accessibility considerations
- Validate designs with users or stakeholders and incorporate feedback
- Support implementation by clarifying intended behavior and reviewing delivered experiences

### Goals
- Make solutions useful, understandable, and accessible to intended users
- Reduce rework by resolving design questions early
- Connect product outcomes to evidence about user needs

### Typical Communication and Interactions
- Partner with Product Managers to shape problems, priorities, and success measures
- Collaborate with Developers to assess feasibility and preserve design intent during implementation
- Coordinate with QA/Testing Leads on usability and accessibility validation
- Share research findings and design decisions with Project Managers and stakeholders

---

## Security Leads

### Role Summary
Security Leads help teams identify and address security requirements and risks throughout planning, implementation, and release. They coordinate with the organization's security function and incident processes where applicable.

### Responsibilities
- Identify applicable security requirements, threat considerations, and review needs
- Advise on secure design and implementation and coordinate security reviews or testing
- Track findings, mitigations, and accepted residual risks with clear ownership
- Escalate security concerns through the established security incident or risk process

### Goals
- Address security risks early and transparently
- Ensure security findings receive appropriate ownership and follow-up
- Support releases with a clear view of outstanding security concerns

### Typical Communication and Interactions
- Work with Developers on secure implementation and remediation
- Coordinate with Project Managers to record and track risks, dependencies, and mitigations
- Advise Product Managers on security-related trade-offs and requirements
- Partner with QA/Testing Leads and Release Managers on security checks and readiness; follow the security incident runbook and notify Security on-call for security incidents

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness and execution across delivery and operational roles. A dedicated Release Manager may not be needed for every project; when the role is shared, the owner should be identified.

### Responsibilities
- Coordinate the release plan, schedule, readiness review, and go/no-go inputs
- Confirm that required acceptance criteria, CI, security checks, release notes, smoke tests, and rollback or mitigation plans are accounted for
- Coordinate deployment communications and post-deployment verification
- Ensure issues and follow-up actions from a release are recorded and assigned

### Goals
- Make releases predictable, observable, and appropriately prepared
- Reduce deployment risk and improve coordination across teams
- Ensure stakeholders know release status and any required actions

### Typical Communication and Interactions
- Coordinate schedules and dependencies with Project Managers
- Confirm scope and customer impact with Product Managers
- Work with Developers and QA/Testing Leads on readiness evidence and known issues
- Partner with Support/Operations Leads on deployment, monitoring, rollback, and incident response
- Communicate release updates to stakeholders with the Project Manager

---

## Support/Operations Leads

### Role Summary
Support/Operations Leads represent the teams responsible for operating the service and supporting users after delivery. They help ensure that changes can be monitored, supported, and recovered safely.

### Responsibilities
- Define operational and support readiness needs, including monitoring, alerting, runbooks, and support documentation
- Review service impact, capacity, and recovery considerations for planned changes
- Coordinate on-call readiness and operational handoffs
- Contribute to incident response, customer-impact assessment, and post-incident follow-up

### Goals
- Maintain service reliability and effective user support
- Make operational ownership and escalation paths clear
- Enable timely detection, response, and recovery when issues occur

### Typical Communication and Interactions
- Work with Developers on observability, runbooks, and operational changes
- Coordinate with Release Managers on rollout, post-deploy verification, and rollback plans
- Partner with QA/Testing Leads on operational and critical-flow validation
- Share support themes and customer impact with Product Managers and Project Managers

---

## Stakeholder/Customer Representatives

### Role Summary
Stakeholder/Customer Representatives provide domain expertise, user or customer feedback, and input on business impact. They inform decisions but do not replace the Product Manager's responsibility for product prioritization or the Sponsor's decision authority.

### Responsibilities
- Explain stakeholder needs, constraints, and expected outcomes
- Provide timely feedback on proposals, acceptance, and milestone demonstrations
- Identify changes in business context or customer impact
- Help communicate relevant changes to represented groups, in coordination with the project team

### Goals
- Ensure plans and outcomes reflect relevant stakeholder and customer needs
- Make decisions and trade-offs better informed
- Support adoption by keeping affected groups appropriately engaged

### Typical Communication and Interactions
- Work with Product Managers to provide input on needs, priorities, and outcome measures
- Coordinate with Project Managers on stakeholder mapping, updates, decisions, and feedback timing
- Review designs and demonstrations with UX/Design Leads and delivery teams
- Raise operational or support concerns through the Project Manager and Support/Operations Lead

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Projects should name an owner for each responsibility that is needed; roles may be combined when appropriate, while decision rights and handoffs remain clear.
