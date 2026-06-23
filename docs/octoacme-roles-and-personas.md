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

## Additional Personas (Proposed Additions)

To improve clarity, handoffs, and accountability across projects, consider adding the following supporting and cross-cutting personas. Each entry includes a short responsibility summary, expected deliverables, and how they typically interact with existing roles.

### Technical Lead / Architect
- Responsibilities: Own high-level technical design and architectural decisions; ensure solutions align with system and platform principles.
- Deliverables: Architecture diagrams, design decision records (DDR), code review guidance, risk assessments.
- Interactions: Collaborates with Developers on implementation details, advises PM/PdM on technical trade-offs, participates in design reviews with QA and Security.

### Release Manager
- Responsibilities: Coordinate release schedules, run deployment checklists, verify rollback plans and communications during releases.
- Deliverables: Release runbook, deployment checklists, post-release verification notes.
- Interactions: Works with DevOps/Platform, PM, QA, Support, and Product to schedule and validate releases; updates stakeholders and the issue/PR that triggers the release.

### DevOps / Platform Engineer
- Responsibilities: Maintain CI/CD pipelines, environments, infrastructure as code, and operational runbooks; ensure observability and resilience.
- Deliverables: Pipeline configurations, environment provisioning scripts, runbooks, incident playbooks.
- Interactions: Partners with Developers for automation, Release Manager for deployments, and PM for capacity/effort planning.

### Security Engineer / AppSec Liaison
- Responsibilities: Review designs for security risks, run security scans, own remediation tracking and security acceptance criteria.
- Deliverables: Threat models, security review notes, scan results, compliance checklists.
- Interactions: Engages with Developers and Architects during design and implementation, informs PM of security impacts on scope/timeline.

### QA Lead / Test Engineer
- Responsibilities: Define test strategy across unit, integration, and E2E; own test plans and acceptance validation for releases.
- Deliverables: Test plans, QA checklists, automation coverage reports, test run results.
- Interactions: Works closely with Developers to make acceptance criteria testable, with PM to prioritize testing, and with Release Manager to sign off releases.

### UX Researcher / Designer Liaison
- Responsibilities: Provide user research insights, validate designs, and ensure UX considerations are captured in acceptance criteria.
- Deliverables: Research findings, usability test scripts and results, design assets and specifications.
- Interactions: Partners with PdM on user outcomes, hands off designs to Developers, and validates end-to-end UX with QA.

### Data Analyst / Insights Owner
- Responsibilities: Define instrumentation needs, track success metrics, and validate the impact of releases against target metrics.
- Deliverables: Metrics definitions, dashboards, analysis reports, event/telemetry plans.
- Interactions: Works with PdM on success metrics, with Developers to ensure instrumentation, and with PM for release monitoring.

### Customer Success / Support Liaison
- Responsibilities: Represent customer feedback and operational issues, prioritize customer-impacting bugs and feature requests.
- Deliverables: Customer impact summaries, support runbooks, prioritized feedback lists.
- Interactions: Coordinates with PM and PdM for prioritization, with Developers and QA for reproducing and fixing issues, and with Release Manager for hotfix coordination.

### Compliance / Privacy Officer (when applicable)
- Responsibilities: Assess regulatory or privacy impacts and required controls; ensure documentation and audits are in place.
- Deliverables: Compliance checklists, privacy impact assessments, required documentation for audits.
- Interactions: Coordinates with Security, PM, and Product on requirements and mitigation plans.

---

## Suggested implementation guidance
- For each new persona added, include: role summary, responsibilities, deliverables, and interaction notes.
- Add a short "when to involve" note (e.g., "Engage Security Engineer during design for any feature exposing PII").
- Add a matrix mapping personas to common artifacts (PRs, release notes, risk register, runbooks) to clarify ownership.
- Include a lightweight checklist template teams can copy into project READMEs to record who currently occupies each persona for a project.

