# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. These personas describe responsibilities, not necessarily separate positions: one person may hold multiple roles, especially on smaller projects. Teams should still make decision ownership and handoffs explicit.

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

## Project Sponsors / Business Owners

### Role Summary
Project Sponsors or Business Owners provide organizational backing for a project and are accountable for its business case and major business decisions.

### Responsibilities
- Confirm the business need, expected outcomes, and continued value of the investment
- Secure sponsorship, funding, and access to required business resources
- Resolve escalated scope, priority, or resource conflicts
- Make or obtain decisions that exceed the project team's authority

### Goals
- Ensure the project delivers meaningful business outcomes
- Keep investment and organizational priorities aligned
- Resolve escalations promptly

### Typical Communication
- Governance reviews and milestone decision meetings
- Escalation summaries and business outcome updates
- Approval or decision records

### Interactions with Existing Roles
- Align with the Product Manager on desired outcomes, product priorities, and business trade-offs
- Partner with the Project Manager on governance, escalations, resources, and decision timelines
- Provide Developers with business context through the Product Manager rather than directing implementation details

---

## Business Analysts

### Role Summary
Business Analysts translate stakeholder needs and business workflows into clear, traceable requirements that the team can deliver and validate.

### Responsibilities
- Elicit and document stakeholder needs, business rules, and process flows
- Refine requirements and acceptance criteria with the appropriate decision-makers
- Identify requirement gaps, assumptions, and dependencies
- Maintain traceability between needs, delivered work, and validation

### Goals
- Reduce ambiguity and avoid late discovery of requirements
- Keep delivered solutions aligned with stakeholder needs
- Make requirements understandable and verifiable

### Typical Communication
- Requirements, workflow diagrams, and decision records
- Refinement sessions and stakeholder interviews
- Acceptance-criteria reviews with delivery and test teams

### Interactions with Existing Roles
- Work with the Product Manager to clarify user and business needs and refine backlog items; the Product Manager retains prioritization decisions
- Coordinate with the Project Manager to surface analysis dependencies, open decisions, and schedule risks
- Clarify requirements for Developers and collaborate on acceptance criteria without taking over technical design decisions

---

## Technical Leads / Solution Architects

### Role Summary
Technical Leads or Solution Architects guide the technical approach and help the team deliver a secure, maintainable solution that fits the project's constraints.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Identify technical dependencies, constraints, and risks
- Support estimates and explain technical trade-offs
- Facilitate technical decisions and communicate their delivery impact

### Goals
- Deliver a reliable, maintainable solution that meets technical standards
- Make technical decisions early enough to protect delivery
- Balance near-term delivery needs with longer-term system health

### Typical Communication
- Architecture and design reviews
- Technical decision records and dependency reviews
- Engineering planning and risk discussions

### Interactions with Existing Roles
- Coordinate implementation and technical reviews with Developers, who remain responsible for the code they deliver
- Explain feasibility and technical trade-offs to the Product Manager so product decisions reflect engineering constraints
- Keep the Project Manager informed of technical dependencies, risks, and estimate changes that affect the plan

---

## QA / Test Leads

### Role Summary
QA or Test Leads coordinate quality practices and provide evidence about whether the solution meets agreed requirements and release criteria.

### Responsibilities
- Define test approach, coverage, and quality checkpoints with the team
- Coordinate functional, integration, regression, and other relevant testing
- Track defects, risks, and unresolved quality concerns
- Report test results and readiness evidence before release decisions

### Goals
- Find important issues early and reduce escaped defects
- Provide transparent, repeatable evidence of product quality
- Ensure release decisions account for known quality risks

### Typical Communication
- Test plans, test results, and defect reports
- Acceptance-criteria reviews and quality checkpoints
- Release-readiness summaries

### Interactions with Existing Roles
- Work with the Product Manager to confirm acceptance criteria and expected behavior
- Partner with Developers to reproduce, prioritize, and resolve defects and to improve testability
- Share quality risks and test status with the Project Manager so plans and stakeholder updates reflect actual readiness

---

## UX / Product Designers and Researchers

### Role Summary
UX or Product Designers and Researchers investigate user needs and shape usable, accessible experiences that support the product's intended outcomes.

### Responsibilities
- Plan and conduct user research appropriate to the project's needs
- Create and validate user flows, prototypes, and interaction designs
- Identify usability and accessibility risks
- Share research findings and design decisions with the delivery team

### Goals
- Ensure the solution addresses real user needs
- Reduce usability issues through early validation
- Keep the experience coherent and accessible

### Typical Communication
- Research findings and user journey artifacts
- Design reviews and prototype feedback sessions
- Usability and accessibility findings

### Interactions with Existing Roles
- Collaborate with the Product Manager to frame user problems and validate intended outcomes
- Coordinate research and design activities with the Project Manager so they are reflected in the plan and dependencies
- Work with Developers to assess implementation options and with them and QA to validate that the delivered experience matches approved designs

---

## DevOps / Release Managers

### Role Summary
DevOps or Release Managers coordinate deployment and operational readiness so changes can be released and supported reliably.

### Responsibilities
- Coordinate release plans, deployment windows, and environment readiness
- Confirm monitoring, operational support, rollback, and release-control plans
- Identify deployment and operational risks and dependencies
- Assemble release-readiness inputs and communicate deployment status

### Goals
- Make releases predictable, observable, and recoverable
- Reduce deployment-related risk and disruption
- Ensure operational ownership is clear after launch

### Typical Communication
- Release plans, deployment checklists, and go/no-go inputs
- Operational readiness and rollback reviews
- Deployment status and incident/escalation channels

### Interactions with Existing Roles
- Coordinate deployment pipelines and operational requirements with Developers and the Technical Lead
- Align release timing and customer or business impact with the Product Manager
- Keep the Project Manager informed of readiness, dependencies, release risks, and schedule changes
- Provide release evidence and operational risks to the designated decision-maker; the Release Manager coordinates readiness but does not automatically own business go/no-go authority

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
