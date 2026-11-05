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

## Additional Cross-Functional Roles

The following roles make ownership clearer for work that spans product, engineering, operations, and customer readiness. Assign them based on project needs; on smaller projects, one person may cover multiple roles. These roles provide functional expertise and own their defined outputs, while the Product Manager remains accountable for product outcomes and priorities and the Project Manager coordinates the overall plan, dependencies, and communications.

### Engineering / Technical Lead

#### Role Summary
The Engineering / Technical Lead guides the technical approach and coordinates engineering decisions across the delivery team.

#### Responsibilities
- Lead technical design and identify architectural constraints
- Coordinate engineering sequencing, estimates, and cross-component dependencies
- Surface technical risks and recommend mitigations
- Support Developers through implementation decisions and technical reviews

#### Collaboration and Accountability
- Works with the Product Manager to assess feasibility, options, and technical trade-offs without taking ownership of product priority.
- Works with the Project Manager to communicate engineering estimates, dependencies, and delivery risks.
- Aligns Developers on technical direction while leaving implementation ownership with the assigned Developers.
- Coordinates with QA/Testing on testability and technical acceptance needs.

### Design / UX Research Lead

#### Role Summary
The Design / UX Research Lead brings user research and experience design into product decisions and delivery.

#### Responsibilities
- Plan or coordinate user research and synthesize findings
- Create and validate user flows, interaction designs, and usability requirements
- Identify accessibility and usability risks and propose improvements
- Provide design artifacts and guidance for implementation and review

#### Collaboration and Accountability
- Works with the Product Manager to connect user needs to product goals, scope, and acceptance criteria; the Product Manager retains prioritization decisions.
- Partners with Developers and the Engineering / Technical Lead to resolve design feasibility questions.
- Works with QA/Testing to include usability and accessibility expectations in validation.
- Shares research and design decisions with the Project Manager so dependencies and reviews are reflected in the plan.

### Data / Analytics Lead

#### Role Summary
The Data / Analytics Lead ensures that product outcomes can be measured with trustworthy data.

#### Responsibilities
- Translate success metrics into instrumentation and reporting requirements
- Define event or data specifications and validate data quality
- Establish how outcome measures will be analyzed and reported
- Identify gaps or limitations in measurement and communicate their impact

#### Collaboration and Accountability
- Works with the Product Manager to define measurable outcomes and interpret results; the Product Manager owns product goals and decisions based on them.
- Partners with Developers and the Engineering / Technical Lead to implement instrumentation.
- Coordinates with QA/Testing to verify tracking and data quality.
- Provides the Project Manager with measurement dependencies and progress for planning and status reporting.

### Security / Privacy Partner

#### Role Summary
The Security / Privacy Partner advises the team on security, privacy, and applicable compliance requirements throughout delivery.

#### Responsibilities
- Identify relevant security and privacy requirements, risks, and review points
- Recommend safeguards and risk mitigations
- Review designs or changes when the project's risk or policy requires it
- Communicate unresolved risks and evidence needed for release readiness

#### Collaboration and Accountability
- Advises Developers and the Engineering / Technical Lead on secure design and implementation; implementation remains with the delivery team.
- Works with QA/Testing to identify appropriate security and privacy verification.
- Advises the Product Manager on user and product implications and the Project Manager on risk tracking, escalation, and review dependencies.
- Escalates material concerns through the established security and risk processes; does not replace the designated security decision-makers or incident responders.

### Release / Operations Lead

#### Role Summary
The Release / Operations Lead coordinates operational readiness and the transition of a change into supported service.

#### Responsibilities
- Define deployment, monitoring, and operational handoff needs
- Coordinate release readiness checks, rollback or mitigation plans, and post-deployment verification
- Identify service, reliability, and supportability risks
- Ensure operational documentation and ownership are ready for launch

#### Collaboration and Accountability
- Works with the Project Manager to align release timing, readiness dependencies, and risks.
- Partners with Developers and the Engineering / Technical Lead on deployment approach, monitoring, and rollback plans.
- Coordinates with QA/Testing on smoke tests and post-deployment verification.
- Informs the Product Manager and affected stakeholders of operational impact and readiness; product scope and release decisions remain with their designated owners.

### Customer Support / Enablement Lead

#### Role Summary
The Customer Support / Enablement Lead prepares customer-facing and internal support teams to adopt and support a change.

#### Responsibilities
- Identify support, training, and customer communication needs
- Prepare support materials, FAQs, and escalation guidance
- Brief support or enablement teams on expected behavior and known issues
- Gather customer feedback and recurring issues after launch

#### Collaboration and Accountability
- Works with the Product Manager to align customer messaging with product behavior, benefits, and known limitations.
- Coordinates with the Project Manager on readiness milestones, audiences, and launch timing.
- Partners with Developers and QA/Testing to understand verified behavior, known issues, and technical escalation routes.
- Shares feedback and support trends with the Product Manager and delivery team to inform follow-up work; does not independently change product scope or release commitments.

Together, these roles make design quality, measurable outcomes, risk review, operational readiness, and customer preparation explicit parts of delivery. Naming an owner and handoffs early helps teams find gaps sooner, route decisions to the right people, and reduce late rework. The roles can be scaled or combined to fit the project's size and risk.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
