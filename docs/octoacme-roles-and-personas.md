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

## QA Lead

### Role Summary
The QA Lead owns the quality assurance strategy across the project lifecycle. They work closely with Developers, Product Managers, and the Operations Lead to define acceptance criteria, design test plans, and gate releases.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, end-to-end, performance)
- Review acceptance criteria for testability before sprint planning
- Lead manual and exploratory testing for new features
- Own the QA sign-off step in the release process
- Coordinate with the Operations Lead on observability and rollback criteria
- Track and report defect trends and quality metrics

### Goals
- Prevent regressions and catch defects early in the development cycle
- Improve automated test coverage sprint over sprint
- Ensure every release meets the Definition of Done quality bar

### Typical Communication
- QA status updates in sprint reviews and release readiness meetings
- Bug triage sessions with Developers
- Pre-release sign-off reports shared with Project Manager and Product Manager

### Interactions with Existing Roles
- **Developers**: Reviews PR acceptance criteria; pairs on test automation gaps
- **Product Manager**: Clarifies edge cases and validates acceptance criteria
- **Project Manager**: Reports QA blockers and escalates if quality bar is not met before a release
- **Operations Lead**: Aligns on production observability, smoke test coverage, and rollback triggers

---

## UX/UI Designer

### Role Summary
The UX/UI Designer is responsible for user research, interaction design, and visual design. They partner with Product Managers and Developers to ensure features are usable, accessible, and aligned with the product vision.

### Responsibilities
- Conduct or synthesize user research to inform design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define and maintain a component/design system
- Lead design reviews before engineering implementation begins
- Ensure accessibility standards (WCAG) are met
- Collaborate with the Customer Success Manager on user feedback

### Goals
- Deliver intuitive, consistent user experiences
- Reduce rework by validating designs before build
- Promote accessibility and inclusive design practices

### Typical Communication
- Design reviews ahead of sprint planning
- Async feedback via design tools (Figma, etc.)
- Usability testing readouts shared with Product Manager and Customer Success Manager

### Interactions with Existing Roles
- **Product Manager**: Translates requirements into validated designs; aligns on user journeys
- **Developers**: Provides design specifications and answers implementation questions during build
- **QA Lead**: Reviews feature acceptance criteria to include design/accessibility checks
- **Customer Success Manager**: Incorporates customer feedback and usability findings into design iterations

---

## Business Analyst

### Role Summary
The Business Analyst bridges business needs and technical delivery. They document requirements, model workflows, and ensure that solutions align with organizational objectives and regulatory constraints.

### Responsibilities
- Elicit and document business requirements and process flows
- Translate business needs into user stories and acceptance criteria
- Facilitate requirements workshops with stakeholders
- Identify gaps, conflicts, and dependencies between business processes
- Support UAT (User Acceptance Testing) planning and execution

### Goals
- Ensure delivered solutions solve the right business problem
- Reduce ambiguity in requirements before development begins
- Improve traceability from business goals to delivered features

### Typical Communication
- Requirements workshops and stakeholder interviews
- Business Requirements Documents (BRDs) or refined user stories in the backlog
- UAT sign-off reports shared with Product Manager and Project Manager

### Interactions with Existing Roles
- **Product Manager**: Refines high-level product goals into detailed requirements
- **Project Manager**: Surfaces requirement-driven scope changes and timeline impacts
- **Developers**: Clarifies ambiguous requirements and validates implementation against business rules
- **QA Lead**: Collaborates on UAT test plans and acceptance criteria

---

## Operations Lead

### Role Summary
The Operations Lead ensures that new features and releases are operationally ready. They own deployment procedures, monitoring, incident response, and infrastructure readiness for production changes.

### Responsibilities
- Define and validate operational readiness criteria for each release
- Own runbooks, deployment procedures, and rollback plans
- Monitor production systems and respond to incidents
- Coordinate with the QA Lead on smoke tests and post-deploy verification
- Manage infrastructure provisioning and capacity planning
- Ensure security and compliance controls are in place before go-live

### Goals
- Enable zero-downtime or low-risk deployments
- Reduce mean time to recovery (MTTR) for production incidents
- Maintain system reliability, scalability, and security in production

### Typical Communication
- Ops readiness reviews before each release
- On-call handoff notes and incident post-mortems
- Infrastructure status updates in weekly delivery sync

### Interactions with Existing Roles
- **Developers**: Reviews infrastructure requirements and deployment scripts; owns production environment
- **QA Lead**: Aligns on smoke tests and rollback criteria for each release
- **Project Manager**: Communicates deployment windows, risks, and production constraints
- **Customer Success Manager**: Provides incident and outage updates that may affect customer-facing communications

---

## Customer Success Manager

### Role Summary
The Customer Success Manager (CSM) acts as the voice of the customer within the project team. They collect and relay customer feedback, manage customer communications around releases, and ensure adoption and satisfaction post-launch.

### Responsibilities
- Gather and synthesize customer feedback from support tickets, interviews, and usage data
- Communicate upcoming changes or releases to customers proactively
- Track feature adoption and customer satisfaction (NPS, CSAT)
- Escalate customer-impacting issues to the Product Manager and Project Manager
- Collaborate with the UX/UI Designer on usability findings
- Support the creation of release notes, FAQs, and training materials

### Goals
- Maximize customer adoption and satisfaction with each release
- Ensure customers are informed and prepared for changes
- Close the feedback loop between customers and the product team

### Typical Communication
- Customer feedback summaries shared with Product Manager and UX/UI Designer
- Release announcements and change notifications to customers
- Post-release adoption reports to the full delivery team

### Interactions with Existing Roles
- **Product Manager**: Channels customer insights to inform roadmap and prioritization
- **UX/UI Designer**: Shares usability findings and feature requests from customers
- **Project Manager**: Coordinates timing of customer communications with release schedule
- **Operations Lead**: Receives incident and outage information for customer-facing communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

