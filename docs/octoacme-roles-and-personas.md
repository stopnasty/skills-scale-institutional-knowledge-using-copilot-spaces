# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or shared depending on project size, but each responsibility should have a clear owner.

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

### Collaboration
- Work with the Product Manager to clarify requirements and acceptance criteria.
- Work with the Technical Lead on design, implementation, and technical risks.
- Coordinate with the QA/Test Lead on testability, defects, and validation.
- Partner with Security/Privacy and Data/Analytics leads to implement required controls and instrumentation.

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

### Collaboration
- Partner with the UX/UI Designer or User Researcher to understand user needs and validate solutions.
- Agree on technical trade-offs with Developers and the Technical Lead.
- Define acceptance expectations with the QA/Test Lead and success measures with the Data/Analytics Lead.
- Coordinate launch priorities and customer impact with the Project Manager and Customer Support/Operations representative.

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

### Collaboration
- Coordinate role ownership, dependencies, milestones, and escalations across the project team.
- Work with the Product Manager to align delivery plans with priorities and outcomes.
- Use status, risks, and readiness inputs from the Technical Lead, QA/Test Lead, Security/Privacy Lead, and Customer Support/Operations representative to support planning and release decisions.

---

## UX/UI Designer or User Researcher

### Role Summary
The UX/UI Designer or User Researcher investigates user needs and helps shape accessible, understandable, and usable experiences.

### Responsibilities
- Plan and conduct appropriate user research and synthesize findings
- Create user flows, prototypes, interaction designs, and interface guidance
- Consider accessibility and usability throughout design
- Validate designs with users and incorporate feedback
- Communicate design assumptions, constraints, and open questions

### Goals
- Ensure solutions address user needs and are usable and accessible
- Reduce avoidable rework by validating assumptions early

### Typical Communication
- Research readouts, design reviews, prototypes, and usability findings
- Collaboration during discovery, backlog refinement, and acceptance planning

### Collaboration
- Partner with the Product Manager to connect user needs to product goals and priorities.
- Work with Developers and the Technical Lead to assess feasibility and implement designs faithfully.
- Coordinate with the QA/Test Lead on usability and accessibility validation, and share relevant findings with the Project Manager for planning.

---

## Technical Lead or Architect

### Role Summary
The Technical Lead or Architect guides technical design and engineering alignment for the project while enabling Developers to deliver maintainable solutions.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Identify integration points, technical dependencies, and implementation risks
- Facilitate technical decisions and document significant trade-offs
- Support estimation and help resolve complex technical issues
- Promote reliability, security, maintainability, and observability

### Goals
- Deliver a coherent, maintainable technical solution
- Surface technical risks and dependencies early

### Typical Communication
- Design proposals, architecture decisions, code reviews, and technical risk updates
- Planning discussions with Developers, Product Manager, and Project Manager

### Collaboration
- Provide Developers with technical direction while incorporating their implementation expertise.
- Advise the Product Manager on feasibility and technical trade-offs without owning product priority decisions.
- Work with the Project Manager to communicate technical dependencies and schedule risks.
- Coordinate with Security/Privacy, Data/Analytics, and QA/Test leads on design requirements and validation.

---

## QA/Test Lead

### Role Summary
The QA/Test Lead coordinates the project’s quality strategy and helps ensure that delivered work meets acceptance criteria and release expectations.

### Responsibilities
- Define and communicate a proportionate test approach
- Coordinate test coverage across unit, integration, end-to-end, and manual testing as appropriate
- Validate acceptance criteria and track defects through resolution
- Report quality risks and readiness evidence

### Goals
- Find important issues early and provide clear evidence of product quality
- Make quality expectations and unresolved risks visible before release

### Typical Communication
- Test plans, defect reports, test results, and release-readiness updates
- Collaboration in refinement, implementation, and pre-release reviews

### Collaboration
- Work with the Product Manager to clarify acceptance criteria and with Developers to build testability and resolve defects.
- Coordinate with the Technical Lead on integration and technical risks.
- Share validation status and unresolved risks with the Project Manager and relevant Security/Privacy or Operations representatives.

---

## Data/Analytics Lead

### Role Summary
The Data/Analytics Lead helps define how project outcomes will be measured and ensures that relevant data is collected and interpreted responsibly.

### Responsibilities
- Translate success metrics into measurable events and indicators
- Advise on instrumentation, data quality, dashboards, and analysis
- Monitor outcome signals after launch and communicate findings
- Identify limitations or risks in data interpretation

### Goals
- Provide trustworthy evidence about adoption, performance, and outcomes
- Help teams use measurement to inform decisions and iteration

### Typical Communication
- Metric definitions, instrumentation guidance, dashboards, and outcome reviews

### Collaboration
- Work with the Product Manager to define success measures and interpret results against product goals.
- Partner with Developers and the Technical Lead on instrumentation and data quality.
- Coordinate with Security/Privacy on appropriate data handling and share relevant progress with the Project Manager.

---

## Security/Privacy Lead

### Role Summary
The Security/Privacy Lead advises the team on security and privacy requirements, reviews risks, and helps ensure that appropriate controls are addressed throughout delivery.

### Responsibilities
- Identify applicable security and privacy requirements and risks
- Advise on secure design, privacy considerations, and appropriate controls
- Coordinate or conduct reviews and communicate findings and remediation needs
- Escalate significant risks or incidents through the established response paths

### Goals
- Address security and privacy risks early and transparently
- Support delivery that protects users, systems, and sensitive information

### Typical Communication
- Risk assessments, review findings, remediation tracking, and incident communications

### Collaboration
- Work with Developers and the Technical Lead to incorporate controls into design and implementation.
- Coordinate validation with the QA/Test Lead and consult the Product Manager on user or product implications.
- Keep the Project Manager informed of material risks, dependencies, and required escalations.

---

## Customer Support or Operations Representative

### Role Summary
The Customer Support or Operations representative brings customer-facing and service-operational needs into planning, release readiness, and post-launch follow-up.

### Responsibilities
- Share customer feedback, support trends, and operational constraints
- Identify support, documentation, monitoring, and service-readiness needs
- Prepare or coordinate support materials and operational handoffs
- Report emerging customer or service issues after release

### Goals
- Ensure teams and customers are prepared for changes
- Improve service readiness and feed real-world feedback into future work

### Typical Communication
- Support readiness reviews, operational checklists, release communications, and feedback summaries

### Collaboration
- Work with the Product Manager to relay customer needs and prioritize follow-up.
- Coordinate with the Project Manager on launch readiness, communications, and operational dependencies.
- Partner with Developers, the Technical Lead, and QA/Test Lead on runbooks, monitoring, and known issues; escalate service risks through agreed channels.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign roles according to project needs; one person may cover multiple roles, but ownership and handoffs should remain explicit.
