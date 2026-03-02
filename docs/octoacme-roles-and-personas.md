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
The Release Manager owns the end-to-end release process. They coordinate pre-release checks, deployment activities, rollback procedures, and stakeholder communications, ensuring every release meets the defined release checklist before going live.

### Responsibilities
- Schedule and lead release planning and go/no-go meetings
- Perform pre-deployment checks and coordinate readiness with Developers and QA
- Communicate release status and timelines to stakeholders
- Manage rollback procedures and coordinate incident response if a release fails
- Maintain release notes and deployment documentation

### Goals
- Ship releases safely, on schedule, and with full stakeholder awareness
- Minimize production incidents caused by avoidable deployment errors
- Keep release documentation accurate and accessible

### Typical Communication
- Release planning sessions with Project Managers and Developers
- Go/no-go decisions shared with Product Managers and stakeholders
- Post-release status updates and incident reports

---

## Risk & Compliance Advisor

### Role Summary
The Risk & Compliance Advisor identifies, assesses, and helps mitigate project risks, and ensures the project remains compliant with relevant regulatory and organizational standards. They maintain the risk register and escalate high-severity or cross-team risks.

### Responsibilities
- Facilitate risk identification and assessment sessions
- Advise on mitigation strategies and compliance requirements
- Review and update the risk register throughout the project lifecycle
- Support audit readiness and post-incident reviews and postmortems
- Escalate risks that exceed defined thresholds to Project Managers and Sponsors

### Goals
- Maintain an up-to-date, actionable risk register
- Reduce the likelihood and impact of high-severity incidents
- Ensure the project meets all applicable compliance obligations

### Typical Communication
- Regular risk review meetings with Project Managers
- Compliance status updates to Sponsors and Stakeholders
- Postmortem and audit documentation

---

## Customer Success Lead

### Role Summary
The Customer Success Lead represents the customer's perspective throughout delivery. They ensure new features and releases align with customer needs, manage beta and pilot programs, and maintain feedback loops between customers and internal teams.

### Responsibilities
- Collect user feedback and relay actionable insights to Product and Project Managers
- Prepare customer-facing communications and documentation for new releases
- Coordinate beta and pilot programs with willing customer groups
- Monitor post-release customer satisfaction metrics and surface emerging issues
- Advocate for the customer voice during planning and prioritization

### Goals
- Ensure delivered features meet real customer needs and expectations
- Reduce post-release churn and support escalations
- Build strong feedback loops between customers and the product team

### Typical Communication
- Alignment with Product Managers during backlog and roadmap planning
- Coordination with the Release Manager on launch communications
- Post-release satisfaction reports shared with Product and Project Managers

---

## Role Interactions Across the Project Lifecycle

The new roles integrate with existing roles (Developers, Product Managers, Project Managers) at specific points across the project lifecycle:

| Lifecycle Phase | Role Interactions |
|---|---|
| **Planning** | Risk & Compliance Advisor facilitates risk identification with the Project Manager. Customer Success Lead shares customer insights with the Product Manager to shape priorities. Release Manager aligns on target release windows with Project and Product Managers. |
| **Execution** | Risk & Compliance Advisor updates the risk register as development progresses. Customer Success Lead coordinates beta programs. Release Manager confirms deployment readiness with Developers and QA. |
| **Release** | Release Manager leads go/no-go decisions, communicates status to stakeholders, and triggers rollback if needed. Customer Success Lead prepares and distributes release communications. Risk & Compliance Advisor validates compliance sign-off. |
| **Incident** | Release Manager coordinates incident response and rollback. Risk & Compliance Advisor supports the post-incident review. Customer Success Lead manages customer communications during and after the incident. |
| **Retrospective** | All three roles contribute to retrospectives: Release Manager reviews release process gaps, Risk & Compliance Advisor reviews risk register accuracy, and Customer Success Lead shares post-release customer feedback. |

---

## Why These Roles Improve Project Outcomes

Adding these roles addresses accountability gaps that are not fully covered by the existing Developer, Product Manager, and Project Manager roles:

- **Clear ownership:** The Release Manager provides a single accountable owner for deployment activities, eliminating hand-off confusion between engineering and project management.
- **Reduced release risk:** Having a dedicated Release Manager enforcing a release checklist and owning rollback decisions reduces production incidents caused by missed steps or unclear responsibility.
- **Better risk governance:** The Risk & Compliance Advisor ensures the risk register is maintained continuously—not just at the start—and that compliance obligations are tracked throughout the lifecycle.
- **Improved customer alignment and feedback loops:** The Customer Success Lead creates a structured channel for customer feedback to reach Product and Project Managers, reducing the risk of shipping features that miss real user needs and improving post-release satisfaction.

Together, these roles strengthen ownership across the full project lifecycle and support the OctoAcme principle of clear, data-informed, customer-first delivery.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

