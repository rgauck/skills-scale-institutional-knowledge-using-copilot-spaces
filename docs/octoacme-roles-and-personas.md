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

## Business Analysts

### Role Summary
Business Analysts turn stakeholder needs into clear requirements and actionable work. They help ensure the team understands the problem and how proposed solutions will be accepted.

### Responsibilities
- Elicit and document business and user requirements
- Clarify scope, assumptions, and dependencies
- Define and refine acceptance criteria with stakeholders
- Validate that delivered work addresses the agreed needs

### Key Interactions
- Partner with Product Managers to refine priorities, outcomes, and backlog items
- Work with Developers to clarify requirements, constraints, and acceptance criteria
- Keep Project Managers informed of scope changes, dependencies, and decisions

### Typical Communication
- Requirements and acceptance criteria in backlog items
- Stakeholder interviews and refinement sessions
- Scope and decision updates with the delivery team

---

## UX/UI Designers

### Role Summary
UX/UI Designers shape usable, accessible experiences and interfaces that meet user needs and product goals.

### Responsibilities
- Research user needs and map key journeys
- Create and validate user flows, wireframes, and interface designs
- Apply accessibility and design-system guidance
- Incorporate user feedback and usability findings into design iterations

### Key Interactions
- Collaborate with Product Managers to align user needs with product outcomes and priorities
- Work with Business Analysts to connect research and user journeys to requirements
- Partner with Developers to assess feasibility and support implementation
- Share design decisions and changes with Project Managers to coordinate delivery

### Typical Communication
- Design files, prototypes, and usability findings
- Design reviews and handoffs with Developers
- User feedback and design decisions shared with the product team

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness, sequencing, and communication so changes can be deployed safely and predictably.

### Responsibilities
- Maintain the release schedule and coordinate deployment dependencies
- Confirm readiness against acceptance criteria, CI and security checks, release notes, and rollback plans
- Coordinate deployment and post-deployment verification
- Communicate release status, changes, and risks to stakeholders

### Key Interactions
- Coordinate milestones and release communications with Project Managers
- Confirm merged work and deployment requirements with Developers
- Work with Operations / Support Leads on operational readiness and post-release monitoring
- Consult Security Reviewers on unresolved security risks before release
- Align release scope and customer-facing changes with Product Managers

### Typical Communication
- Release plans, readiness checklists, and deployment status
- Release notes and stakeholder announcements
- Escalations for readiness gaps or schedule changes

---

## Operations / Support Leads

### Role Summary
Operations / Support Leads provide production-readiness and support-impact input, and coordinate operational follow-up after releases or incidents.

### Responsibilities
- Identify monitoring, reliability, and support needs before release
- Prepare support teams with known issues and troubleshooting guidance
- Monitor production impact and coordinate operational response
- Capture incident learnings and follow-up actions

### Key Interactions
- Work with Developers on observability, operational risks, and incident remediation
- Coordinate readiness, deployment windows, and post-release monitoring with Release Managers
- Share support impact, incidents, and dependencies with Project Managers
- Provide Product Managers with customer-impact trends and recurring feedback

### Typical Communication
- Operational readiness checks and support handoff notes
- Monitoring updates, incident communications, and escalation summaries
- Post-incident findings and tracked follow-up actions

---

## Security Reviewers

### Role Summary
Security Reviewers assess security risks and advise the team on appropriate controls throughout planning, delivery, and release.

### Responsibilities
- Identify security and privacy risks in proposed changes
- Review designs and implementation against applicable security requirements
- Recommend mitigations and track unresolved security findings
- Advise on security readiness and escalation for significant risks

### Key Interactions
- Advise Developers on secure design, implementation, and remediation
- Work with Product Managers and Business Analysts to clarify security requirements and trade-offs
- Share risks, owners, and mitigations with Project Managers for tracking and escalation
- Coordinate with Release Managers on security findings that affect release readiness
- Engage Operations / Support Leads on incident response and operational security concerns

### Typical Communication
- Security review findings and recommended mitigations
- Risk-register updates and security decisions
- Release-readiness advice and incident follow-up

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Business Analysts and UX/UI Designers contribute during discovery and planning; Release Managers and Operations / Support Leads coordinate release and production handoffs; Security Reviewers advise across planning, execution, and release.
