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

## Release Managers

### Role Summary
Release Managers coordinate release readiness, deployment windows, communication, and rollback planning so that changes reach production reliably and with clear ownership.

### Responsibilities
- Define release scope, schedules, and approval gates
- Coordinate release readiness reviews with engineering, QA, and stakeholders
- Manage deployment checklists, cutover timing, and rollback planning
- Communicate release status, known risks, and customer impact
- Support post-release validation and issue triage

### Goals
- Reduce release risk and operational surprises
- Improve predictability across environments and milestones
- Ensure stakeholders understand launch timing and readiness

### Typical Communication
- Release readiness meetings and approval checkpoints
- Deployment updates and incident notifications
- Status reporting to PMs, Product leads, and stakeholders

### Interaction with existing roles
- Works closely with Project Managers to align release timing with milestone plans
- Partners with Product Managers on launch readiness and stakeholder expectations
- Coordinates with Developers and QA/Testing Lead on validation, deployment readiness, and rollback readiness
- Escalates blockers to the PM or sponsor when release risk impacts business commitments

---

## QA / Testing Leads

### Role Summary
QA / Testing Leads define quality expectations, validate acceptance criteria, and ensure defects are addressed before release with a clear and measurable testing strategy.

### Responsibilities
- Define test strategy, coverage goals, and quality gates
- Validate features against acceptance criteria and business requirements
- Prioritize defects, coordinate triage, and verify fixes
- Partner with development teams on testability and regression prevention
- Support release sign-off and risk-based manual QA when needed

### Goals
- Deliver a predictable, high-quality product experience
- Catch issues early and reduce production defects
- Align testing with risk, user value, and release goals

### Typical Communication
- Test planning and QA reviews
- Defect triage sessions and release sign-off discussions
- Feedback loops with Product and Engineering teams

### Interaction with existing roles
- Works with Developers to clarify acceptance criteria and testable requirements
- Provides quality signals to Project Managers for milestone progress and risk awareness
- Aligns with Product Managers on customer-facing validation and release confidence
- Reports release blockers to the PM or escalation path when quality issues affect commitments

---

## Security / Compliance Partners

### Role Summary
Security / Compliance Partners help teams identify and reduce security, privacy, and regulatory risks while ensuring delivery remains aligned to enterprise standards and policies.

### Responsibilities
- Review architecture, workflows, and release changes for security and compliance impacts
- Define or validate secure-by-default patterns and control requirements
- Support risk analysis and mitigation planning for sensitive work
- Coordinate with stakeholders on compliance evidence or review needs
- Participate in incident response and post-incident corrective actions when relevant

### Goals
- Reduce exposure to security and compliance risks
- Enable safe delivery without introducing unnecessary process friction
- Ensure teams meet policy and risk expectations before release

### Typical Communication
- Design reviews, security check-ins, and policy guidance
- Risk assessments and compliance-related escalation updates
- Incident and remediation coordination with PMs and engineering leads

### Interaction with existing roles
- Advises Product Managers on risk trade-offs and policy constraints
- Reviews technical decisions with Developers and Platform/DevOps teams before production release
- Supports Project Managers in tracking risks, mitigation plans, and escalations
- Coordinates with stakeholders when compliance or security decisions affect scope or timing

---

## Platform / DevOps Engineers

### Role Summary
Platform / DevOps Engineers ensure the delivery environment is reliable, observable, and ready for frequent, safe releases across development, testing, and production.

### Responsibilities
- Maintain CI/CD pipelines, build automation, and environment consistency
- Support infrastructure, deployment tooling, and observability platforms
- Improve reliability through monitoring, alerting, and automation
- Help teams with environment readiness, configuration, and deployment troubleshooting
- Support operational readiness for production releases

### Goals
- Improve delivery speed without sacrificing reliability
- Reduce environment drift and operational friction
- Enable safe, repeatable deployments and service health monitoring

### Typical Communication
- CI/CD reviews and infrastructure status updates
- Deployment troubleshooting and incident coordination
- Collaboration with engineering and release teams during milestones and launches

### Interaction with existing roles
- Works with Developers to improve delivery tooling and environment stability
- Supports Project Managers in assessing execution risk tied to tooling or deployment readiness
- Coordinates with Release Managers on deployment windows, automation, and rollback readiness
- Provides technical risk input to Product Managers when dependency or platform issues may affect roadmap commitments

---

## Customer Success / Stakeholder Liaisons

### Role Summary
Customer Success / Stakeholder Liaisons translate customer feedback, stakeholder needs, and adoption signals into actionable delivery priorities and communication plans.

### Responsibilities
- Gather customer and stakeholder feedback from support, usage, and relationship channels
- Provide context on customer impact, urgency, and priority trade-offs
- Support communication plans for launches, updates, and milestones
- Help align engineering output with customer commitments and business goals
- Surface recurring issues or opportunities for product improvement

### Goals
- Improve customer satisfaction and adoption outcomes
- Ensure stakeholder expectations stay aligned with delivery reality
- Strengthen the feedback loop between teams and customer-facing stakeholders

### Typical Communication
- Stakeholder briefings and customer update meetings
- Feedback summaries and prioritization discussions
- Cross-functional alignment on customer risk and opportunity

### Interaction with existing roles
- Feeds customer needs and support trends to Product Managers to inform prioritization
- Shares launch and risk information with Project Managers and Release Managers
- Provides context to Developers and QA teams on real-world customer pain points and critical workflows
- Helps stakeholders understand delivery decisions, trade-offs, and readiness conditions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles clarify accountability across planning, execution, release, quality, and stakeholder alignment.


