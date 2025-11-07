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

## QA Engineer

### Role Summary
Plans and executes test strategies, triages bugs, and signs off releases for software quality.

### Responsibilities
- Design and execute manual/automated tests
- Collaborate on acceptance criteria
- Run regression/release tests
- Triage bugs and perform release validation

### Interactions
- Works with Developers to resolve defects
- Coordinates with PM on test planning and release scope

---

## UX/UI Designer

### Role Summary
Designs user interfaces, prototypes, and tests usability and accessibility.

### Responsibilities
- Create wireframes, visual designs, and prototypes
- Perform usability and accessibility testing
- Collaborate on requirements and feature specs

### Interactions
- Works with Product Manager for requirements/goals
- Collaborates directly with Developers for implementation
- Engages Stakeholders for design feedback

---

## Security Lead

### Role Summary
Ensures application and infrastructure security throughout the project lifecycle.

### Responsibilities
- Conduct risk/threat assessments
- Review code and dependencies for vulnerabilities
- Lead incident response
- Advise teams on secure patterns and compliance

### Interactions
- Supports Developers for security implementation
- Collaborates with PM on risk mitigation tracking

---

## Business Analyst

### Role Summary
Translates business needs into technical requirements and analyzes data for improvement.

### Responsibilities
- Gather requirements and map processes
- Recommend improvements and document changes
- Track metrics to drive better delivery

### Interactions
- Works closely with Product Managers on needs and data
- Supports Developers for solution feasibility
- Engages Stakeholders for input and approval

---

## Stakeholder/Sponsor

### Role Summary
Provides strategic input, allocates resources, and removes blockers.

### Responsibilities
- Approve milestones and project direction
- Allocate resources and drive decisions
- Remove organizational barriers

### Interactions
- Receives updates from PM and Product Manager
- Engages teams during decision gates and escalations

---

## DevOps Engineer

### Role Summary
Manages CI/CD pipelines, infrastructure, deployment, and reliability.

### Responsibilities
- Set up, monitor, and maintain CI/CD systems
- Automate deployments and monitoring
- Respond to outages and production issues

### Interactions
- Collaborates with Developers and QA on release cycles
- Coordinates with PM for deployment planning

---

## Cross-Persona Interactions

| Persona           | Collaborates With                    | Main Touchpoints                  |
|-------------------|-------------------------------------|-----------------------------------|
| QA Engineer       | Dev, PM, PdM                        | UAT, release testing              |
| UX Designer       | PdM, Dev, Stakeholder               | Design reviews, specs, prototypes |
| Security Lead     | Dev, PM, Stakeholder                | Risk register, incident response  |
| Business Analyst  | PdM, Dev, Stakeholder               | Requirements, process docs        |
| Sponsor           | PM, PdM, Stakeholder                | Decision gates, escalations       |
| DevOps Engineer   | Dev, QA, PM                         | Deployments, CI/CD, post-release  |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.