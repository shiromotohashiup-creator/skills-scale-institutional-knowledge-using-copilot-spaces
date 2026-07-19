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

## Technical Lead

### Role Summary
Technical Leads guide technical direction for a project, ensure architectural coherence, and mentor engineers to maintain code quality and scalability.

### Responsibilities
- Make or guide architecture and design decisions
- Define technical roadmap and major milestones
- Review complex PRs and technical proposals
- Identify and mitigate technical risks and debt
- Coach and mentor developers on best practices

### Goals
- Maintain a clear, scalable architecture
- Reduce technical debt and rework
- Improve developer productivity and code quality

### Typical Communication
- Architecture/tech design sessions
- PR reviews and technical decision records
- Weekly syncs with engineering leads

### Interactions with existing roles
- With Developers: provide guidance, review designs, unblock implementation
- With PM / Product Manager: translate product requirements into technical scope and effort
- With Project Manager: surface technical risks and inform timelines

---

## Delivery Lead

### Role Summary
Delivery Leads focus on execution: planning sprints/releases, tracking commitments, and coordinating cross-team dependencies to meet delivery targets.

### Responsibilities
- Lead sprint/iteration planning and commitment tracking
- Coordinate dependencies across teams and external partners
- Monitor delivery health (velocity, scope creep, blockers)
- Maintain release readiness checklists and runbooks

### Goals
- Improve predictability of delivery
- Reduce unplanned work and last-minute scope changes
- Ensure releases meet readiness criteria

### Typical Communication
- Sprint planning, daily delivery syncs, release checklists
- Status updates to PM and stakeholders

### Interactions with existing roles
- With Project Manager: align on timelines and risk mitigations
- With Product Manager: ensure prioritized backlog is delivery-ready
- With Developers/QA: confirm acceptance criteria and readiness for release

---

## UX Researcher

### Role Summary
UX Researchers bring user insight into product decisions through research, usability testing, and validation, ensuring features meet real user needs.

### Responsibilities
- Plan and run user research and usability studies
- Synthesize findings into actionable recommendations
- Support product decisions with evidence and hypotheses
- Validate proposed UX flows against acceptance criteria

### Goals
- Reduce product risk by validating assumptions early
- Improve usability and user satisfaction
- Provide measurable input to success metrics

### Typical Communication
- Research briefs and findings reports
- Design reviews and acceptance criteria sessions

### Interactions with existing roles
- With Product Manager: define research questions, success metrics, and inform prioritization
- With Developers/Designers: provide guidance on user expectations and usability fixes
- With QA: help define user-focused acceptance criteria

---

## Support Lead / Site Reliability (Ops) Lead

### Role Summary
Support/ Ops Leads own production reliability, incident response, runbooks, and post-release monitoring to ensure operational stability.

### Responsibilities
- Maintain runbooks and incident response procedures
- Own on-call escalation path and handoffs
- Define monitoring, alerting, and post-deploy verification steps
- Coordinate post-incident root cause analysis and follow-ups

### Goals
- Minimize customer-impacting incidents and recovery time
- Improve observability and operational runbooks
- Ensure smooth handoffs between development and operations

### Typical Communication
- Incident reports and postmortems
- Runbook updates and on-call rotation notices
- Post-deploy verifications with delivery teams

### Interactions with existing roles
- With Developers: coordinate incident remediation and bug fixes
- With Project Manager / Product Manager: communicate production impact and customer-facing updates
- With QA: validate production smoke tests and rollback procedures

---

## Security Reviewer

### Role Summary
Security Reviewers ensure security and compliance are considered across planning, design, and delivery through threat modeling, reviews, and guidance.

### Responsibilities
- Conduct security reviews and threat modeling for features
- Define security acceptance criteria and checklists
- Coordinate security scans and remediate findings
- Ensure compliance requirements are considered and documented

### Goals
- Reduce security risk introduced by changes
- Ensure compliance with relevant standards and policies
- Integrate security checks early in the lifecycle

### Typical Communication
- Security review findings and remediation plans
- Threat modeling workshops and documentation

### Interactions with existing roles
- With Product Manager: advise on security implications of feature choices
- With Developers: provide actionable fixes, review PRs for security issues
- With Project Manager: escalate high-risk findings and influence timelines if mitigation is required

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
