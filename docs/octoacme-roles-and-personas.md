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

## QA/Testing Specialists

### Role Summary
QA/Testing Specialists validate solution quality and acceptance criteria. They design test strategies, execute manual and automated testing, and report issues to ensure features meet quality standards before release.

### Responsibilities
- Design and maintain test strategies and test plans
- Create and execute manual test cases for acceptance criteria
- Develop and maintain test automation
- Report and triage bugs with clear reproduction steps
- Participate in Definition of Done (DoD) discussions
- Conduct smoke tests and regression testing before releases

### Interactions
- Collaborate with developers on test planning and testability
- Work with Product Managers to clarify acceptance criteria
- Escalate blocking quality issues to PM and Project Manager
- Participate in sprint planning and retrospectives

### Goals
- Ensure all features meet acceptance criteria
- Reduce production defects and rework cycles
- Provide confidence in release readiness

### Typical Communication
- Sprint planning and retrospectives
- Bug reports and test execution summaries
- Release readiness assessments

---

## Product Lead / Technical Product Owner

### Role Summary
The Product Lead acts as the senior product strategist who ensures alignment between product vision and technical feasibility. They mentor Product Managers, resolve complex trade-offs, and guide major architectural decisions.

### Responsibilities
- Approve product roadmap and major feature proposals
- Guide Product Managers on technical feasibility and trade-offs
- Review and approve significant technical decisions
- Mentor Product Managers and provide escalation path
- Participate in stakeholder and sponsor communications
- Identify and resolve cross-team dependencies

### Interactions
- Partner weekly with PM and Project Manager
- Guide developers and architects on product strategy
- Escalate business-impacting decisions to sponsors
- Communicate product vision to all stakeholders
- Review technical proposals and architectural decisions

### Goals
- Balance customer value with technical sustainability
- Ensure scalable, forward-thinking product decisions
- Reduce rework due to misaligned trade-offs
- Build shared understanding of product direction

### Typical Communication
- Weekly sync with PM and Project Manager
- Architectural review sessions
- Stakeholder briefings and strategy sessions

---

## Release/DevOps Engineer

### Role Summary
Release/DevOps Engineers manage deployment pipelines, coordinate production releases, monitor system health, and execute rollback procedures when needed. They ensure repeatable, reliable deployment processes.

### Responsibilities
- Design and maintain CI/CD pipelines
- Coordinate and execute releases to production
- Monitor deployed systems and alert on issues
- Execute rollback procedures when necessary
- Document deployment runbooks and procedures
- Assist with incident response and troubleshooting

### Interactions
- Collaborate with developers on pipeline optimization and deployment testability
- Coordinate with Project Manager on release timing and scheduling
- Work with Security/Compliance on deployment security controls
- Participate in pre-release readiness reviews
- Support production incident response

### Goals
- Minimize deployment errors and production downtime
- Ensure deployments are fast, repeatable, and safe
- Provide observability and rapid incident response
- Reduce time-to-recovery during outages

### Typical Communication
- Release planning and coordination meetings
- Deployment runbooks and incident playbooks
- System health dashboards and alerts

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure solutions meet security and regulatory requirements. They conduct security reviews, manage vulnerability scanning, and guide teams on secure development practices.

### Responsibilities
- Review designs and pull requests for security vulnerabilities
- Configure and monitor security scanning in CI/CD pipelines
- Ensure compliance with regulatory and organizational standards
- Participate in threat modeling for critical features
- Manage and respond to security incidents
- Provide secure development guidance and training to teams

### Interactions
- Advise developers during design and code review phases
- Escalate security risks and compliance gaps to leadership
- Participate in risk registers and incident response
- Support release readiness verification
- Collaborate with Product Lead on security implications of decisions

### Goals
- Prevent security breaches and data loss
- Ensure compliance with regulations and organizational policies
- Build a culture of secure development practices
- Minimize security-related production incidents

### Typical Communication
- Security review meetings and code walkthroughs
- Vulnerability reports and remediation tracking
- Compliance audit documentation

---

## Technical Architect/Technical Lead

### Role Summary
Technical Architects and Leads design system-level solutions, guide implementation approaches, and ensure technical excellence. They mentor developers, identify technical risks, and advocate for system quality and maintainability.

### Responsibilities
- Design technical solutions for complex features
- Conduct architecture and design reviews
- Mentor developers on best practices and design patterns
- Identify and escalate technical risks and technical debt
- Participate in technology selection and evaluation
- Ensure code quality and maintainability standards

### Interactions
- Guide developers on implementation approaches and design decisions
- Collaborate with Product Lead on technical strategy alignment
- Escalate architectural concerns and trade-offs
- Participate in planning, design reviews, and retrospectives
- Work with QA/Testing on testability and quality approaches

### Goals
- Deliver scalable, maintainable, and performant systems
- Reduce technical debt and future rework
- Build team capability and technical excellence
- Ensure long-term system sustainability

### Typical Communication
- Design review sessions and architecture discussions
- Technical mentoring and code walkthroughs
- Technical decision logs and RFCs (Requests for Comments)

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests and provide approval for major project decisions. They set priorities, remove organizational blockers, and ensure projects align with business strategy.

### Responsibilities
- Provide business context and priority guidance
- Approve project charter and major scope changes
- Escalate and resolve organizational blockers
- Participate in go/no-go decision gates
- Receive and review status updates
- Support project teams with resources and advocacy

### Interactions
- Receive status updates from Project Manager
- Provide feedback and guidance to Product Manager
- Participate in milestone reviews and demos
- Escalate conflicts and resource constraints
- Make go/no-go decisions at key gates

### Goals
- Ensure project delivers business value
- Remove organizational obstacles to team success
- Maintain alignment with company strategy
- Maximize return on investment

### Typical Communication
- Monthly or milestone-based status updates
- Milestone reviews and demos
- Executive steering committee meetings
- Escalation and decision forums

---

## Role Interaction Matrix

| Phase | Key Interactions |
|-------|------------------|
| **Initiation** | Sponsor approves charter; Product Lead & Product Manager define goals; Project Manager schedules kickoff |
| **Planning** | Product Manager prioritizes backlog; Technical Architect reviews feasibility; Project Manager schedules work; QA designs test approach |
| **Execution** | Developers build; QA tests; Technical Lead guides; Product Manager clarifies requirements; Project Manager tracks progress |
| **Release** | Release/DevOps Engineer manages deployment; Security reviews; Product Manager validates; Project Manager coordinates timing |
| **Retrospective** | Project Manager facilitates; all roles contribute; action items tracked by PM for next iteration |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Role Interaction Matrix to understand how personas collaborate across project phases.
