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

## Delivery Lead

### Role Summary
The Delivery Lead keeps the team on schedule, aligns planning and execution, and helps remove cross-team blockers so work can move forward predictably.

### Responsibilities
- Own sprint or milestone cadence and delivery sequencing
- Monitor project plan, dependencies, and execution risks
- Coordinate with PM and Product Lead on trade-offs and resourcing
- Support weekly planning, burn-down tracking, and readiness reviews
- Escalate blockers that require stakeholder or cross-functional intervention

### Goals
- Maintain predictable delivery flow
- Reduce delays caused by unclear ownership or dependencies
- Keep engineering and product aligned on delivery commitments

### Typical Communication
- Delivery planning meetings
- Weekly status reviews with PM and Product Lead
- Blocker escalation updates during standups and cross-team syncs

### Interaction with Existing Roles
- Works closely with Project Managers on schedules, risks, and communication
- Coordinates with Product Managers on priority and release alignment
- Partners with Technical Leads to confirm readiness and risk mitigation

---

## Technical Lead

### Role Summary
The Technical Lead guides architecture, technical decision-making, and engineering quality across the initiative.

### Responsibilities
- Define and validate technical direction and design trade-offs
- Review architecture and implementation choices
- Mentor developers and support technical problem-solving
- Ensure work is testable, maintainable, and aligned with engineering standards
- Partner with QA and release roles to assess confidence before launch

### Goals
- Deliver technically sound, maintainable solutions
- Reduce engineering rework and avoid architectural drift
- Improve quality and confidence in delivery

### Typical Communication
- Design reviews and architecture discussions
- Engineering planning and implementation reviews
- Incident triage and technical risk discussions

### Interaction with Existing Roles
- Collaborates with Developers on technical design and implementation quality
- Partners with QA/Testing to define testability and quality gates
- Aligns with Release/Build Engineer on deployment readiness and rollback considerations
- Supports PM and Product Lead on feasibility, sequencing, and risks

---

## Release / Build Engineer

### Role Summary
The Release / Build Engineer owns the software delivery pipeline, reliability of deployment processes, and release readiness checks.

### Responsibilities
- Maintain CI/CD workflows and build quality gates
- Manage release automation, deployment scripts, and environment readiness
- Validate rollback plans and deployment health
- Coordinate release windows and communication of deployment milestones
- Support issue detection and recovery during releases

### Goals
- Reduce deployment risk and downtime
- Improve release consistency and rollback confidence
- Enable faster, safer delivery of changes

### Typical Communication
- Release readiness reviews
- Deployment checklists and post-deploy verification
- Incident and rollback coordination with engineering and support

### Interaction with Existing Roles
- Works with Technical Lead and Developers to verify release readiness
- Coordinates with QA on validation and smoke-test execution
- Interfaces with Support Liaison and Product Ops to announce release timing and impacts
- Provides status and escalation inputs to Project Managers during high-risk releases

---

## Product Operations

### Role Summary
Product Operations helps operationalize product changes by coordinating launches, communications, and enablement activities across stakeholders.

### Responsibilities
- Plan rollout timing and stakeholder communication
- Coordinate feature flags, launch activities, and support readiness
- Maintain release enablement materials and process documentation
- Track operational readiness for customer-facing changes
- Support adoption and feedback collection after launch

### Goals
- Improve launch readiness and stakeholder confidence
- Reduce friction between product strategy and operational execution
- Ensure new capabilities are supported and communicated effectively

### Typical Communication
- Release and launch planning
- Stakeholder updates and readiness check-ins
- Post-release feedback and adoption review

### Interaction with Existing Roles
- Works with Product Managers on launch goals and messaging
- Coordinates with Project Managers on timeline and dependencies
- Supports Release / Build Engineer and Support Liaison during go-live preparation
- Collects feedback from support and customer-facing teams to inform follow-up improvements

---

## Support Liaison

### Role Summary
The Support Liaison serves as the bridge between project teams and customer support functions, ensuring issues, knowledge, and operational impacts are communicated clearly.

### Responsibilities
- Create or maintain runbooks, troubleshooting guidance, and escalation paths
- Triage post-release issues and correlate them with product changes
- Share customer-impacting feedback with engineering and product teams
- Help prepare support teams for new releases or changes
- Track recurring issues and support trends

### Goals
- Reduce customer friction and support burden
- Improve issue visibility and resolution speed
- Ensure operational readiness for new product changes

### Typical Communication
- Incident summaries and escalation updates
- Support handoff documentation and release readiness notes
- Feedback loops with Product and Engineering teams

### Interaction with Existing Roles
- Works with Product Managers on user-impact signals and support readiness
- Coordinates with Technical Lead and Developers on root cause analysis
- Shares release information with Product Ops and Project Managers
- Escalates cross-team issues when customer impact requires broader intervention

---

## Data Analyst / Insights Partner

### Role Summary
The Data Analyst or Insights Partner measures product impact, defines telemetry expectations, and helps teams use evidence to validate outcomes.

### Responsibilities
- Define metrics and instrumentation requirements for success tracking
- Analyze product usage, quality, and customer impact data
- Validate whether a change achieved intended business or user outcomes
- Support experiments, feature measurement, and reporting
- Provide evidence to inform iteration decisions

### Goals
- Improve decision quality using measurable evidence
- Connect product outcomes to operational and business goals
- Make performance and quality visible across stakeholders

### Typical Communication
- Metric definitions and dashboard reviews
- Outcome reporting for PM and leadership
- Feedback to technical and product teams after launch

### Interaction with Existing Roles
- Partners with Product Managers to define success metrics
- Works with Developers and Technical Lead to ensure telemetry is instrumented appropriately
- Supports Release / Build Engineer during validation and monitoring
- Helps Support Liaison and Product Ops interpret customer and impact data

---

## Security Liaison

### Role Summary
The Security Liaison helps ensure that project work meets security requirements and that vulnerabilities or risks are addressed consistently.

### Responsibilities
- Coordinate security reviews and risk assessments
- Ensure compliance and secure design considerations are captured early
- Support vulnerability identification, triage, and remediation planning
- Validate that release and deployment activities account for security controls
- Escalate critical findings to the appropriate stakeholders

### Goals
- Reduce security risk across delivery and release activities
- Improve awareness of security expectations and controls
- Protect the organization and customers from avoidable exposure

### Typical Communication
- Security review checkpoints
- Risk and remediation updates
- Escalation communication for high-risk or compliance-related issues

### Interaction with Existing Roles
- Partners with Technical Lead and Developers on design review and mitigation
- Coordinates with Release / Build Engineer for secure deployment controls
- Shares risk information with Project Managers and Product Leads
- Supports Support Liaison during incident communication and related documentation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles improve accountability, clarify handoffs, and support more resilient project execution across planning, delivery, release, support, and continuous improvement.
