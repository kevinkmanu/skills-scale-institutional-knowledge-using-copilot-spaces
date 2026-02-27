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
The QA Lead coordinates all testing activities across the project. They define the test strategy, manage test execution, and act as the quality gate before releases.

### Responsibilities
- Define and maintain the overall test strategy and test plans
- Coordinate unit, integration, end-to-end, and regression testing
- Collaborate with Developers to design testable features and acceptance criteria
- Report test status, defect trends, and quality risks to the PM and Product Manager
- Drive automation efforts and maintain the CI test pipeline

### Goals
- Ensure releases meet defined quality and acceptance standards
- Reduce escaped defects in production
- Increase test automation coverage over time

### Typical Communication
- Daily standup participation and blocker reporting
- QA status reports to PM before each release
- Defect and test-result summaries in project tracking tools

---

## UX/UI Designer

### Role Summary
The UX/UI Designer is responsible for user experience flows and interface design. They ensure that features are intuitive, accessible, and aligned with user needs.

### Responsibilities
- Translate product requirements into wireframes, prototypes, and high-fidelity designs
- Conduct or facilitate user research and usability testing
- Maintain a design system and ensure visual consistency
- Partner with Developers for design handoff and implementation reviews
- Collaborate with the Product Manager on feature definition and trade-offs

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce rework by aligning design and engineering early
- Validate design decisions with real user feedback

### Typical Communication
- Design reviews with Product Manager and Developers
- Handoff documentation (Figma specs, design tokens, etc.)
- Usability test findings shared with the full team

---

## Business Analyst

### Role Summary
The Business Analyst gathers, documents, and clarifies requirements. They act as a bridge between business stakeholders and the technical team, ensuring deliverables meet business goals.

### Responsibilities
- Elicit requirements through interviews, workshops, and documentation review
- Write clear user stories, acceptance criteria, and process flows
- Validate that implemented features meet stated business requirements
- Identify and escalate scope changes or conflicting requirements
- Support UAT (User Acceptance Testing) coordination with stakeholders

### Goals
- Ensure requirements are complete, clear, and agreed upon before development begins
- Reduce ambiguity and mid-sprint re-work
- Facilitate shared understanding between business and technical teams

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story write-ups and refinement sessions with the team
- UAT feedback reports to PM and Product Manager

---

## Operations Lead

### Role Summary
The Operations Lead oversees deployment, monitoring, and incident response. They ensure the team follows reliability and scalability practices and that production systems remain healthy.

### Responsibilities
- Manage deployment pipelines and release processes
- Define and maintain monitoring, alerting, and on-call practices
- Lead incident response and post-incident review processes
- Communicate operational risks, capacity concerns, and system status to the PM
- Ensure compliance with security, backup, and disaster recovery requirements

### Goals
- Maintain high availability and reliability of production systems
- Minimize mean time to detect (MTTD) and resolve (MTTR) incidents
- Improve deployment frequency and reduce deployment risk

### Typical Communication
- Operational readiness reviews before major releases
- Incident reports and post-mortems shared with the team
- Monitoring dashboards and alerting runbooks

---

## Customer Success Manager

### Role Summary
The Customer Success Manager represents the voice of the customer during project execution. They gather feedback during pilots and releases and ensure users are set up for success.

### Responsibilities
- Gather and relay customer feedback to the Product Manager and team
- Coordinate customer pilots, beta programs, and early access rollouts
- Ensure training, onboarding documentation, and release notes meet user needs
- Track customer health metrics and escalate adoption risks
- Serve as the primary point of contact for key customer relationships during a release

### Goals
- Drive high customer adoption and satisfaction for each release
- Ensure customers are prepared and supported before, during, and after launches
- Surface real-world usage insights that inform future prioritization

### Typical Communication
- Feedback summaries shared with Product Manager after pilots and releases
- Collaboration with PM and Developers on documentation and training materials
- Regular customer touchpoints and health check updates

---

## Role Interaction Matrix

This matrix summarizes key collaboration points and handoffs between roles.

| | PM | PdM | Developer | QA Lead | UX/UI Designer | Business Analyst | Operations Lead | Customer Success |
|---|---|---|---|---|---|---|---|---|
| **PM** | — | Weekly sync | Sprint planning, blockers | Release readiness | Design milestones | Requirement sign-off | Ops risk review | Launch coordination |
| **PdM** | Weekly sync | — | Acceptance criteria, demos | Quality metrics | Feature definition | Requirements review | Capacity input | Adoption goals |
| **Developer** | Status updates | Feature specs | — | Testability, defect triage | Design handoff | Story clarifications | Deployment support | Release notes |
| **QA Lead** | Test status reports | Defect trends | Test planning, defect triage | — | Usability test support | UAT coordination | Pre-release sign-off | Customer defect feedback |
| **UX/UI Designer** | Design milestones | Feature definition | Design handoff | Usability test support | — | Requirements flows | — | User feedback loops |
| **Business Analyst** | Requirement sign-off | Requirements review | Story clarifications | UAT coordination | Requirements flows | — | Operational constraints | Customer requirements |
| **Operations Lead** | Ops risk review | Capacity input | Deployment support | Pre-release sign-off | — | Operational constraints | — | Support escalations |
| **Customer Success** | Launch coordination | Adoption goals | Release notes | Customer defect feedback | User feedback loops | Customer requirements | Support escalations | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

