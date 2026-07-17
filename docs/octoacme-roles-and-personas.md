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
QA/Testing Leads define and execute quality standards, design test strategies, and ensure features meet acceptance criteria before release. They collaborate with developers and product managers to validate that solutions work as intended and are ready for production.

### Responsibilities
- Design and execute comprehensive test plans (unit, integration, end-to-end)
- Define acceptance criteria validation approach
- Manage QA workflows and testing environments
- Conduct security and performance testing
- Track and triage defects, working with developers on resolution
- Provide release readiness sign-off
- Coordinate with developers and product managers on quality standards

### Goals
- Ensure high quality and reliability of shipped features
- Reduce post-release defects and incidents
- Enable fast, confident deployments
- Maintain quality consistency across releases

### Typical Communication
- Acceptance criteria workshops with Product and Development
- Test case reviews and QA plan sign-off
- Defect triage meetings and regression testing coordination
- Release readiness reports and quality assessments

### Interaction with Other Roles
- **Developers**: Collaborate on test design, defect resolution, and quality standards
- **Product Managers**: Define acceptance criteria and validate feature requirements
- **Project Managers**: Report on quality status and release readiness
- **Release Manager**: Provide sign-off on deployment readiness

---

## Tech Lead / Architect

### Role Summary
Tech Leads provide technical direction, conduct design reviews, and identify technical risks and architectural considerations. They mentor developers and ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Conduct technical design reviews and architecture discussions
- Identify technical risks and scalability concerns
- Mentor developers and guide implementation decisions
- Ensure code quality and adherence to standards
- Collaborate on technical estimates and dependency identification
- Provide guidance on technology selections and trade-offs

### Goals
- Deliver technically sound, scalable solutions
- Build institutional technical knowledge
- Reduce technical debt and rework
- Align technical decisions with organizational strategy

### Typical Communication
- Design review meetings and technical spec discussions
- Code review guidance and architecture decisions
- Risk identification in planning and execution
- Technical debt discussions in retrospectives
- Mentoring sessions with developers

### Interaction with Other Roles
- **Developers**: Guide implementation and conduct code/design reviews
- **Project Managers**: Identify and escalate technical risks and dependencies
- **Security Lead**: Collaborate on secure architecture and threat modeling
- **QA/Testing Lead**: Define testability requirements and quality standards

---

## Stakeholder / Business Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, define priorities, and ensure projects deliver value aligned with organizational goals. They serve as decision-makers and approvers for significant scope or priority changes.

### Responsibilities
- Define business objectives and success criteria
- Prioritize initiatives and make trade-off decisions
- Approve project scope, timeline, and budget
- Provide stakeholder feedback and direction
- Attend key milestones (kickoff, reviews, release)
- Communicate organizational constraints and strategic direction

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Enable informed decision-making on priorities
- Reduce scope creep and maintain focus

### Typical Communication
- Project kickoff and monthly stakeholder updates
- Milestone reviews and release announcements
- Ad-hoc escalations for priority or scope changes
- Executive status reporting and decision gates

### Interaction with Other Roles
- **Product Managers**: Define success metrics and business priorities
- **Project Managers**: Approve scope, timeline, and budget; escalate blockers
- **Release Manager**: Communicate release announcements and business impact

---

## Security Lead

### Role Summary
Security Leads ensure projects meet security requirements, conduct threat assessments, and manage security incidents. They integrate security into the design and deployment process and ensure compliance with organizational policies.

### Responsibilities
- Define security requirements and acceptance criteria
- Conduct threat modeling and security design reviews
- Integrate security scanning into CI/CD pipeline
- Manage security incidents and escalation procedures
- Ensure compliance with security policies and regulations
- Advise on secure coding practices and vulnerability remediation
- Review and approve security-related changes and deployments

### Goals
- Embed security into the development lifecycle
- Prevent security incidents and data breaches
- Maintain compliance and trust
- Build security awareness across the team

### Typical Communication
- Security requirement definition in planning
- Design and code review participation
- Security incident response and root cause analysis
- Risk register updates and escalations
- Security training and awareness sessions

### Interaction with Other Roles
- **Tech Lead/Architect**: Collaborate on secure architecture and threat modeling
- **Developers**: Review security code practices and advise on remediation
- **Project Managers**: Escalate security risks and manage security-related dependencies
- **Release Manager**: Approve releases from a security perspective

---

## Release Manager

### Role Summary
Release Managers coordinate the end-to-end release process, manage deployment windows, own rollback procedures, and communicate release status to stakeholders. They ensure releases are predictable, safe, and well-communicated.

### Responsibilities
- Plan and coordinate release timelines and deployment windows
- Verify pre-release requirements are met (testing, documentation, approvals)
- Execute or coordinate deployment processes
- Manage rollback procedures if issues occur
- Communicate release status and known issues
- Coordinate with support and operations teams
- Maintain release documentation and post-release verification

### Goals
- Execute safe, efficient, low-risk releases
- Minimize deployment downtime and incidents
- Ensure clear communication and stakeholder confidence
- Build a repeatable, reliable release process

### Typical Communication
- Release planning and pre-release checklists
- Deployment day coordination and status updates
- Post-release verification and incident communication
- Release notes and stakeholder announcements
- Retrospective participation on deployment issues

### Interaction with Other Roles
- **Project Managers**: Coordinate release scheduling and stakeholder communication
- **QA/Testing Lead**: Verify release readiness and sign-off
- **Developers**: Coordinate code freeze and deployment support
- **Security Lead**: Obtain security approval before deployment
- **Tech Lead/Architect**: Escalate technical deployment issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific persona responsibilities when assigning work or identifying communication needs.
- Use interaction descriptions to clarify cross-functional dependencies and handoff points.
