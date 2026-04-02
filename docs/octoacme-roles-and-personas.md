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

## QA / Testing

### Role Summary
QA/Testing validates the product against acceptance criteria and helps ensure releases meet quality standards.

### Responsibilities
- Design and run manual and automated test cases
- Triage and track defects
- Verify fixes and perform release sanity checks
- Contribute acceptance criteria for backlog items

### Typical Communication
- QA reports in weekly syncs
- Test results attached to release notes or PRs
- Collaborate with Developers and PMs on defect priorities

---

## New / Expanded Personas

The following personas were added to improve clarity for cross-functional work and handoffs.

---

### UX Designer

- Role Summary: Responsible for user experience research, interaction design, and usability testing.
- Responsibilities:
  - Conduct user research and facilitate design workshops
  - Provide wireframes, prototypes, and design rationale for new features
  - Validate concepts through usability tests and synthesize findings
  - Define UX acceptance criteria where relevant
  - Work with Product Managers and Developers to ensure design intent is met
- Typical Interaction:
  - Collaborates with Product Managers to define user problems and success criteria
  - Works with Developers during planning to clarify UI/UX requirements and during implementation to review fidelity
  - Participates in sprint reviews and acceptance testing for UX-related items
- Key handoffs:
  - Delivers prototypes before dev work begins
  - Confirms final UI in staging prior to release

---

### Data Analyst

- Role Summary: Delivers insights through data collection and analysis to inform decision-making and measure outcomes.
- Responsibilities:
  - Define, instrument, and validate key metrics and dashboards
  - Create reports that surface trends, regressions, and experiment results
  - Assist with experiment design and statistical analysis
  - Provide recommendations based on quantitative evidence
  - Collaborate with Product Managers to align metrics with business goals
- Typical Interaction:
  - Works with Product Managers to define success metrics and acceptance criteria tied to measurable signals
  - Partners with Developers to ensure tracking is implemented and data quality is maintained
  - Shares findings at weekly syncs and post-release reviews
- Key handoffs:
  - Provides metric spec before development starts
  - Delivers post-release measurement and recommendations

---

### Release Manager

- Role Summary: Oversees coordination and quality of software releases and deployments.
- Responsibilities:
  - Coordinate deployment scheduling and stakeholder communications
  - Draft and maintain release notes and change documentation
  - Facilitate go/no-go reviews and post-release retrospectives
  - Ensure rollback and mitigation plans are in place
  - Monitor post-release stability and coordinate hotfixes if needed
- Typical Interaction:
  - Partners with Project Managers, QA, and Engineering to manage release readiness
  - Communicates with Support and Stakeholders about release impact
  - Drives post-release review and metrics monitoring
- Key handoffs:
  - Confirms environment readiness and validates smoke tests
  - Coordinates announcement and support coverage

---

### Customer Support Lead

- Role Summary: Advocates for customers and translates support needs into actionable feedback for the product and engineering teams.
- Responsibilities:
  - Escalate customer issues and coordinate feedback into the backlog
  - Triage incidents and maintain clear communication with affected stakeholders
  - Verify fixes and validate resolution with customers when appropriate
  - Contribute to post-incident reviews and improvements
- Typical Interaction:
  - Works closely with Product Managers and Developers to prioritize customer-impacting issues
  - Provides ongoing context and reproducible reports for incidents
  - Participates in release readiness conversations for customer-impacting changes
- Key handoffs:
  - Supplies customer impact details during incident triage
  - Confirms resolution and customer communication post-fix

---

## Interaction & Accountability Mapping (summary)

- Product Managers: define outcomes and prioritize; rely on UX for research and on Data Analysts for metrics.
- Project Managers: coordinate delivery and scheduling; coordinate with Release Manager for deployment windows.
- Developers: implement features and rely on UX for UI details and Data Analysts for instrumentation requirements.
- QA: validate release readiness and collaborate with Release Manager on release gating.
- Customer Support Lead: brings customer signals to PdM and PM and participates in incident resolution and post-release feedback loops.

Use these expanded personas in the Project One-pager "Proposed team / roles" field and in role-specific checklists to make responsibilities explicit during planning and releases.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and provide consistent, repeatable expectations.