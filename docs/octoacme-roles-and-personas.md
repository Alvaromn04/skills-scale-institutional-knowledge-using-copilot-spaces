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

## UX Designers

### Role Summary
UX Designers shape the user experience strategy so solutions are intuitive, accessible, and aligned with user needs. They translate product goals into usable flows and design deliverables.

### Responsibilities
- Conduct and synthesize user research and usability insights
- Create user flows, wireframes, and prototypes
- Advocate for accessibility and inclusive design decisions
- Partner with product and engineering during design reviews

### Goals
- Improve usability and adoption of shipped features
- Reduce friction in critical user journeys
- Ensure design decisions reflect user and business outcomes

### Typical Communication
- Discovery sessions with Product Managers
- Design walkthroughs with Developers
- Handoff documentation and annotated prototypes

---

## QA Leads

### Role Summary
QA Leads define and coordinate quality practices across manual and automated testing to ensure releases meet acceptance and reliability expectations.

### Responsibilities
- Define test strategy, scope, and quality gates
- Coordinate test execution across manual and automated coverage
- Track defects, triage severity, and verify fixes
- Provide release quality sign-off recommendations

### Goals
- Prevent high-impact defects from reaching production
- Increase confidence in release readiness
- Improve regression coverage for critical workflows

### Typical Communication
- Test planning with Developers and Project Managers
- Defect triage and status updates with delivery teams
- Release readiness reporting before deployment

---

## DevOps Engineers

### Role Summary
DevOps Engineers enable reliable delivery by automating build, test, and deployment workflows and maintaining healthy runtime infrastructure.

### Responsibilities
- Build and maintain CI/CD automation
- Implement monitoring, alerting, and operational dashboards
- Manage infrastructure-as-code and environment consistency
- Define rollback and recovery mechanisms for deployments

### Goals
- Increase deployment reliability and frequency
- Reduce time to detect and resolve operational issues
- Standardize repeatable, low-risk release processes

### Typical Communication
- Pipeline and environment coordination with Developers
- Release and quality alignment with QA and Project Managers
- Incident and post-release updates with stakeholders

---

## Business Analysts

### Role Summary
Business Analysts bridge product direction with business constraints by refining requirements, validating solutions, and clarifying expected value.

### Responsibilities
- Elicit and document business requirements and constraints
- Refine acceptance criteria and process dependencies
- Validate proposed solutions against business needs
- Assess expected ROI, trade-offs, and delivery impacts

### Goals
- Keep scope aligned with measurable business outcomes
- Reduce ambiguity in requirements and handoffs
- Improve decision quality through structured analysis

### Typical Communication
- Requirement refinement with Product and Project Managers
- Stakeholder interviews and clarification sessions
- Change-impact and dependency communication across teams

---

## Cross-functional Collaboration Model

These roles complement the core Developer, Product Manager, and Project Manager personas across the lifecycle:

- **Initiation (`octoacme-project-initiation.md`)**: Product and Business Analysis clarify problem framing and resource needs, including UX, QA, and DevOps participation.
- **Planning (`octoacme-project-planning.md`)**: UX scope, QA approach, dependencies, and delivery constraints are incorporated into backlog and milestone planning.
- **Execution (`octoacme-execution-and-tracking.md`)**: Developers, QA, and DevOps coordinate quality gates, CI workflows, and blocker escalation.
- **Release (`octoacme-release-and-deployment.md`)**: QA validates release readiness while DevOps drives deployment reliability, rollback readiness, and post-deploy checks.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
