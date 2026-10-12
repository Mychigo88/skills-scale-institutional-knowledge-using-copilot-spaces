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

## QA / Testing Lead

### Role Summary
QA / Testing Leads define the quality strategy for the project and ensure that work meets the agreed acceptance criteria before release. They work closely with developers, PMs, and stakeholders to validate outcomes and surface risks early.

### Responsibilities
- Own test strategy, test planning, and release readiness checks
- Define quality gates and validate acceptance criteria
- Work with developers to improve testability and coverage
- Identify defects, regressions, and risk signals early
- Communicate quality status, blockers, and escalation needs to PMs and Product leads

### Goals
- Deliver high-confidence releases with minimal avoidable defects
- Strengthen quality practices across the delivery lifecycle
- Ensure customer-facing quality remains aligned with business expectations

### Typical Communication
- Daily or sprint-level quality updates with engineering
- QA signoff and release readiness reviews
- Risk reports and blocker escalation with PM / PdM and stakeholders

### Interaction with existing roles
- Works with Developers to validate behavior, catch regressions, and refine testability
- Collaborates with Product Managers on acceptance criteria and release confidence
- Supports Project Managers by surfacing risks and readiness issues that may affect schedule or scope

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches help the team operate effectively, remove impediments, and improve delivery flow. They focus on team health, agile practices, and sustainable execution.

### Responsibilities
- Facilitate sprint ceremonies and team planning activities
- Remove blockers that slow team progress
- Coach the team on process adherence and continuous improvement
- Monitor delivery health and highlight anti-patterns or impediments
- Support retrospectives and action tracking for process improvement

### Goals
- Improve team productivity and predictability
- Keep delivery focused on value and flow
- Foster a healthy, collaborative, and learning-oriented team culture

### Typical Communication
- Daily standups, sprint reviews, and retrospectives
- Coaching conversations with engineers and leads
- Process and escalation issues with Project Managers and stakeholders

### Interaction with existing roles
- Supports Developers by helping resolve process friction and prioritization bottlenecks
- Works with Project Managers to keep planning and execution aligned with sprint capacity
- Partners with Product Managers to ensure backlog refinement supports smooth delivery
- Helps leadership understand where process changes can reduce risk or improve throughput

---

## Technical Lead / Architect

### Role Summary
Technical Leads or Architects guide technical direction, design quality, and architectural consistency across the project. They ensure the solution remains maintainable, scalable, and aligned with long-term technical goals.

### Responsibilities
- Define architecture, design principles, and technical standards
- Review technical feasibility and major design trade-offs
- Guide implementation choices and reduce technical debt
- Mentor developers on best practices, code quality, and system design
- Identify cross-team technical dependencies and risk areas

### Goals
- Keep architecture coherent, scalable, and maintainable
- Reduce avoidable technical risk
- Enable delivery teams to make sound technical decisions with confidence

### Typical Communication
- Architecture reviews and design discussions
- Technical dependency and risk updates with leadership and PMs
- Code quality and engineering standards guidance for delivery teams

### Interaction with existing roles
- Works with Developers to review design choices and technical constraints
- Advises Product Managers on feasibility, trade-offs, and timeline impacts
- Coordinates with Project Managers on technical dependencies and delivery planning
- Collaborates with Security and DevOps roles to ensure operational and security constraints are respected

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, funding support, and prioritization authority. They ensure the initiative remains aligned with strategic goals and organizational needs.

### Responsibilities
- Provide business context and clarify expected outcomes
- Approve major decisions, trade-offs, and prioritization changes
- Sponsor the initiative and support cross-functional alignment
- Escalate business-impacting risks or strategic changes
- Review milestones and communicate outcomes to broader teams

### Goals
- Ensure the project delivers meaningful business value
- Maintain alignment between technical execution and strategic priorities
- Support decision-making with clear business context and accountability

### Typical Communication
- Steering meetings, stakeholder updates, and milestone reviews
- Decision logs and approvals for scope or priority changes
- Escalation of business risks and strategic concerns

### Interaction with existing roles
- Works with Product Managers to confirm business priorities and success criteria
- Collaborates with Project Managers on milestone alignment and executive communication
- Receives updates from QA and operational roles on release readiness and risk
- Escalates to leadership when risks or dependencies could affect business outcomes

---

## DevOps / Operations Engineer

### Role Summary
DevOps or Operations Engineers support reliable delivery, deployment, and service health. They help ensure systems are production-ready, observable, and operationally sustainable.

### Responsibilities
- Manage CI/CD pipelines, deployment automation, and environment configuration
- Support release execution, rollback, and operational readiness
- Monitor system health, reliability, and performance
- Help define uptime, observability, and incident response requirements
- Coordinate infrastructure and environment constraints with engineering teams

### Goals
- Reduce deployment risk and improve operational consistency
- Keep environments stable, secure, and observable
- Enable fast, reliable delivery into production

### Typical Communication
- Release planning, deployment coordination, and post-deploy verification
- Operational alerts, incident updates, and support handoffs
- Capacity and infrastructure constraints with PMs and engineering leads

### Interaction with existing roles
- Works with Developers to ensure deployment readiness and operational constraints are considered
- Supports Project Managers with release planning and rollout timing
- Coordinates with Security Engineers on secure deployment patterns and incident handling
- Works with QA leads to validate environment readiness and smoke-test execution

---

## Security Engineer

### Role Summary
Security Engineers protect the organization's systems and data by identifying vulnerabilities, guiding secure design, and helping the team respond to security risks and incidents.

### Responsibilities
- Review code, architecture, and workflows for security risks
- Advise on secure design patterns, threat mitigation, and compliance requirements
- Conduct security testing and review security-sensitive changes
- Support incident triage and response for security issues
- Help define risk treatment and remediation priorities

### Goals
- Reduce vulnerability exposure and improve security posture
- Enable teams to ship with confidence while respecting security controls
- Support secure, resilient, and compliant delivery

### Typical Communication
- Security review findings and design recommendations
- Incident updates and escalations for critical vulnerabilities
- Security guidance with engineering, PM, and stakeholder groups

### Interaction with existing roles
- Works with Developers to review code and recommend secure implementations
- Advises Product Managers and Stakeholders on risk trade-offs and compliance impacts
- Supports Project Managers in escalation paths for critical security concerns
- Collaborates with DevOps and Technical Leads to ensure secure deployment and operational practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
