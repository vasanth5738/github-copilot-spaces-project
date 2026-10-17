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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed additions)

To reduce handoff gaps and improve accountability for cross-functional activities, the following supporting personas are proposed for inclusion. Each entry includes a concise Role Summary, Responsibilities, Primary Goals, and Typical Interactions with existing roles.

### Release Engineer

- Role Summary:
  Owns release pipelines, deployment safety, and rollback procedures across environments.

- Responsibilities:
  - Maintain and improve CI/CD pipelines and deployment automation
  - Create and run release checklists and pre-deploy verifications
  - Coordinate deployment windows and rollback plans
  - Monitor post-deploy health and automated alerts
  - Document release runbooks and mitigation steps

- Primary Goals:
  - Reduce deployment risk and mean time to recover (MTTR)
  - Ensure repeatable, auditable release processes

- Typical Interactions:
  - Works with Developers and QA to ensure release artifacts meet quality gates
  - Coordinates with PM/PdM for release timing and stakeholder communication
  - Engages Support/On-call for incident handoffs and post-release monitoring
  - Consults Security Engineer for releases that include sensitive dependencies or configuration changes

### UX Researcher

- Role Summary:
  Drives user research and helps translate user insights into acceptance criteria and design decisions.

- Responsibilities:
  - Plan and conduct user interviews, usability tests, and surveys
  - Synthesize research findings and produce actionable recommendations
  - Validate design hypotheses with target users and iterate on prototypes
  - Provide artifacts (personas, journey maps, usability reports) that inform acceptance criteria

- Primary Goals:
  - Increase product usability and alignment with user needs
  - Reduce rework by surfacing UX risks early

- Typical Interactions:
  - Partners with PdM to shape requirements and prioritize features based on user impact
  - Works with Designers to align design and research outcomes
  - Shares validation outcomes with Developers and QA to ensure the shipped experience matches expectations

### Data Analyst

- Role Summary:
  Defines measurement plans and validates success metrics for features and experiments.

- Responsibilities:
  - Define instrumentation and measurement requirements for features
  - Build dashboards and run analyses to evaluate feature impact
  - Ensure data quality and collaborate on telemetry implementation
  - Provide post-release analysis and recommendations

- Primary Goals:
  - Ensure features have measurable outcomes and that data supports decision-making
  - Reduce ambiguity in success criteria through clear metrics

- Typical Interactions:
  - Collaborates with PdM to define success metrics and experiment design
  - Works with Developers to implement events and with Release Engineer to ensure telemetry deploys correctly
  - Shares findings with PM and stakeholders to inform next steps

### Security Engineer

- Role Summary:
  Ensures security best practices are integrated into design and delivery and that vulnerabilities are managed.

- Responsibilities:
  - Conduct threat modeling and security reviews for significant changes
  - Run or coordinate dependency and static analysis scans
  - Triage and prioritize security findings and recommend mitigations
  - Support incident response and coordinate with Security on-call when needed

- Primary Goals:
  - Minimize security risks and ensure compliance with policies
  - Integrate security checks into the normal delivery workflow

- Typical Interactions:
  - Engages early with Developers and PdM during planning for high-risk features
  - Coordinates with Release Engineer before production deploys on mitigations and compensating controls
  - Works with Project Managers for scheduling remediation effort and with Support for any customer-impacting vulnerabilities

### Support Lead (Customer/Support)

- Role Summary:
  Represents customer-facing concerns, captures common issues, and feeds prioritization back to the team.

- Responsibilities:
  - Triage user reports and maintain reproducible steps for engineering
  - Maintain incident communication templates and coordinate outward-facing messaging
  - Identify patterns from support tickets and escalate recurring issues
  - Help prioritize bug fixes and customer-impacting work

- Primary Goals:
  - Improve customer satisfaction and reduce time to resolution
  - Provide clear, actionable feedback to the delivery team

- Typical Interactions:
  - Works with PM and Developers during incident triage
  - Coordinates with QA to validate fixes for customer-reported issues
  - Feeds recurring issues into the backlog and informs PdM on customer impact

### Technical Program Manager (TPM)

- Role Summary:
  Drives cross-team coordination and program-level planning for larger initiatives with complex dependencies.

- Responsibilities:
  - Manage program-level timelines, milestones, and dependency matrices
  - Facilitate cross-team planning, risk identification, and mitigation
  - Track progress across multiple teams and surface escalations early
  - Ensure alignment between engineering, product, and stakeholder roadmaps

- Primary Goals:
  - Keep multi-team initiatives on schedule and reduce cross-team blockers
  - Ensure end-to-end visibility for complex deliveries

- Typical Interactions:
  - Coordinates with Project Managers and PMs across teams
  - Works closely with Engineering Leads and Release Engineer for integration and cutover planning
  - Reports status and risks to stakeholders and senior leadership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and to make expectations explicit for onboarding.
