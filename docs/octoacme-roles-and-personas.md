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

## UX/Design Lead

### Role Summary
The UX/Design Lead owns the user experience and interface design across the project. They translate user needs and product requirements into design artifacts, ensuring the delivered product is usable, accessible, and aligned with customer expectations.

### Responsibilities
- Own UX design artifacts including wireframes, prototypes, and design specifications
- Collaborate with Product Managers to translate user needs into actionable designs
- Work with Developers to ensure accurate and faithful implementation of designs
- Participate in sprint planning to flag design dependencies and lead times early
- Conduct or coordinate user research and usability testing
- Review implemented features against design specs before release

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce rework caused by late-stage design feedback
- Ensure user research informs product decisions

### Typical Communication
- Design reviews and feedback sessions with Developers and Product Managers
- Sprint planning participation to surface design readiness blockers
- Usability test reports and design documentation shared with the delivery team

### Interaction with existing roles
- Works closely with Product Managers to align designs with product goals and success metrics
- Collaborates directly with Developers during implementation to clarify design intent
- Informs Project Managers of design dependencies that may affect timelines

---

## Engineering Lead / Tech Lead

### Role Summary
The Engineering Lead (or Tech Lead) provides technical direction and architecture guidance for the delivery team. They act as the bridge between Developers and Project/Product Managers on technical trade-offs, ensuring the technical approach is sound, scalable, and aligned with project goals.

### Responsibilities
- Provide technical direction and architecture guidance for the delivery team
- Review and approve significant technical decisions and design documents
- Act as the bridge between Developers and Project/Product Managers on technical trade-offs
- Identify and escalate technical risks and dependencies
- Contribute to estimation, sprint planning, and release readiness assessments
- Support Developers through mentorship and technical unblocking

### Goals
- Ensure technical quality, scalability, and maintainability of the codebase
- Reduce technical risk through early identification and mitigation
- Align engineering decisions with project and product outcomes

### Typical Communication
- Technical design reviews and architecture discussions with Developers
- Sprint planning and estimation sessions with Project and Product Managers
- Risk and dependency escalation to the Project Manager

### Interaction with existing roles
- Partners with Developers to guide implementation approach and resolve technical blockers
- Advises Product Managers on technical feasibility and trade-offs during backlog refinement
- Provides technical input to Project Managers for risk register updates and milestone planning

---

## Security / Compliance Reviewer

### Role Summary
The Security/Compliance Reviewer ensures that features, code, and infrastructure changes meet security and compliance requirements throughout the project lifecycle. They partner with the delivery team to embed secure practices from planning through release.

### Responsibilities
- Review features, code, and infrastructure changes for security and compliance requirements
- Participate in release readiness by signing off on security scans and vulnerability assessments
- Escalate security incidents and coordinate with the Security on-call team
- Provide guidance on data privacy and regulatory requirements (e.g., GDPR, SOC2)
- Partner with Developers and the Engineering Lead to embed security practices throughout the SDLC
- Contribute to the risk register with security-specific risks and mitigations

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure the project meets applicable compliance and regulatory requirements
- Build a culture of security-first development within the team

### Typical Communication
- Security review sign-offs included in release checklists
- Escalation notifications to PM and Security on-call for identified incidents
- Guidance shared with Developers during design and implementation phases

### Interaction with existing roles
- Works with Developers and the Engineering Lead to address security findings early in development
- Provides release approval to Project Managers as part of the deployment checklist
- Collaborates with Product Managers to ensure compliance requirements are captured in acceptance criteria

---

## Stakeholder / Executive Sponsor

### Role Summary
The Executive Sponsor champions the project at the leadership level, secures resourcing, and provides final approval at key decision gates. They align the project with organizational strategy and serve as the ultimate escalation point for business-impacting issues.

### Responsibilities
- Champion the project at the leadership level and secure funding and resourcing
- Provide final approval at key decision gates (go/no-go, scope changes, major escalations)
- Receive monthly or milestone-based status updates from the Project Manager
- Act as the escalation point for Level 3 (business-impacting) blockers
- Align project goals with organizational strategy and priorities

### Goals
- Ensure the project delivers expected business value and strategic impact
- Provide decisive leadership support when critical decisions are needed
- Maintain organizational alignment and remove executive-level blockers

### Typical Communication
- Monthly or milestone-based status updates from the Project Manager
- Decision gate approvals via documented go/no-go checkpoints
- Escalation notifications for business-impacting risks or blockers

### Interaction with existing roles
- Receives regular status reporting from Project Managers and Product Managers
- Acts as the final decision-maker when PM and Product Lead escalate unresolved risks or scope changes
- Aligned by Product Managers on product vision and strategic trade-offs

---

## Support / Customer Success Representative

### Role Summary
The Support/Customer Success Representative provides the voice of the customer during planning and release phases. They ensure that released features are communicated clearly to customers and that post-launch issues are surfaced back to the delivery team promptly.

### Responsibilities
- Provide the voice of the customer during planning and release phases
- Review release notes and communicate changes to end users or customers
- Flag post-launch issues surfaced through support channels back to the delivery team
- Participate in UAT (User Acceptance Testing) where applicable
- Coordinate knowledge base and documentation updates for released features

### Goals
- Ensure customers are informed and supported through product changes
- Reduce post-launch support burden through proactive communication and documentation
- Provide actionable customer feedback to the delivery team

### Typical Communication
- Release note reviews and sign-off with the Project Manager before deployment
- UAT participation and feedback reporting to Product Managers
- Post-launch issue reports surfaced to Project and Product Managers

### Interaction with existing roles
- Partners with Product Managers to incorporate customer feedback into backlog prioritization
- Coordinates with Project Managers on release communication timing and customer-facing announcements
- Works with Developers and QA/Testing to validate customer-impacting fixes and changes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

