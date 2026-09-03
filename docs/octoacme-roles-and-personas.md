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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality strategies, validate that features meet acceptance criteria, and ensure the product is fit for release. They collaborate closely with Developers and Product Managers to maintain quality gates throughout the development lifecycle.

### Responsibilities
- Define test plans and acceptance criteria validation approach
- Execute manual and automated testing throughout the sprint
- Triage and document defects with clear reproduction steps
- Collaborate with developers on root cause analysis and verification
- Provide sign-off on quality gates before release
- Maintain test automation frameworks and coverage metrics
- Communicate quality metrics and risk assessments to the team

### Goals
- Ensure customer-facing quality and usability
- Reduce defects reaching production
- Enable fast feedback cycles during development
- Build a culture of quality awareness

### Interactions with Other Roles
- **Developers**: Partner on test design, defect triage, and root cause analysis
- **Product Managers**: Validate that features meet acceptance criteria; communicate quality risks that impact release timelines
- **Project Managers**: Provide quality status updates and escalate blocking issues
- **Technical Leads**: Consult on test strategy and technical feasibility of automation

### Typical Communication
- Sprint planning and acceptance criteria review
- Daily standup defect updates
- QA sign-off gates in release checklist
- Pre-release quality reports

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural direction, mentor developers, and ensure technical decisions align with long-term system health and scalability. They work across the team to establish technical standards and guide implementation of complex features.

### Responsibilities
- Review technical designs and architecture decisions
- Identify technical risks and propose mitigations
- Guide implementation of complex features and refactoring efforts
- Mentor junior developers and conduct code reviews
- Advocate for reducing technical debt and maintaining code quality
- Participate in planning to validate feasibility and effort estimates
- Establish and maintain technical standards and best practices

### Goals
- Maintain code quality and system reliability
- Reduce technical debt and unplanned work
- Build scalable, maintainable solutions
- Foster a strong engineering culture

### Interactions with Other Roles
- **Developers**: Mentor and guide through code reviews and technical discussions
- **Project Managers**: Advise on technical feasibility during planning; escalate technical risks
- **QA/Testing Lead**: Collaborate on test automation strategy and technical validation
- **Product Managers**: Provide technical trade-off analysis to support prioritization decisions

### Typical Communication
- Design reviews and technical discussions
- Code review feedback and mentorship
- Planning sessions for high-complexity work
- Technical risk assessments

---

## Release / DevOps Engineer

### Role Summary
Release and DevOps Engineers automate, manage, and monitor the deployment pipeline from staging to production, ensuring reliable, auditable releases. They enable the team to deploy frequently and safely while maintaining system stability.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Automate build, test, and deployment processes
- Manage infrastructure and deployment environments (staging, production)
- Execute or orchestrate releases and rollbacks
- Monitor post-release health and coordinate incident response
- Document runbooks and deployment procedures
- Work with security and operations to ensure compliance and safety

### Goals
- Enable fast, safe, repeatable deployments
- Reduce manual effort and human error in releases
- Maintain high system availability and observability
- Minimize deployment-related incidents and rollbacks

### Interactions with Other Roles
- **Developers**: Partner on CI/CD improvements and troubleshooting deployment issues
- **Project Managers**: Coordinate release windows and deployment schedules
- **QA/Testing Lead**: Automate test execution and provide feedback on deployment status
- **Security Lead**: Ensure deployments meet security and compliance requirements

### Typical Communication
- Release planning and deployment window coordination
- Incident response and rollback coordination
- CI/CD pipeline updates and improvements
- Post-deployment monitoring and metrics

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, set priorities, approve scope, and ensure the project aligns with organizational strategy. They serve as the voice of the business and decision-makers for project direction.

### Responsibilities
- Approve project charter and scope decisions
- Provide business and user context for requirements
- Prioritize competing initiatives and trade-offs
- Allocate or approve resources and budget
- Review progress and provide feedback on outcomes
- Escalate blockers and risks that affect business outcomes
- Communicate project status and value to leadership

### Goals
- Ensure projects deliver measurable business value
- Align product roadmap with organizational strategy
- Support team success through timely decisions and resource allocation
- Minimize scope creep and maintain project focus

### Interactions with Other Roles
- **Product Managers**: Set strategic direction; provide business priorities
- **Project Managers**: Review progress; make scope and resource decisions
- **Developers/Technical Leads**: Understand technical constraints and trade-offs
- **QA/Testing Lead**: Understand quality expectations and release criteria

### Typical Communication
- Monthly stakeholder briefings and progress reviews
- Milestone reviews and go/no-go decisions
- Ad-hoc escalations and approvals
- Business metrics and outcome reporting

---

## Security Lead

### Role Summary
Security Leads integrate security requirements into the development lifecycle, conduct security reviews, and respond to security incidents. They ensure that security is built into products and processes from the start.

### Responsibilities
- Define security requirements and acceptance criteria for features
- Review designs and code for security vulnerabilities
- Conduct security testing and vulnerability assessments
- Manage security incidents and post-incident reviews (blameless)
- Educate team on secure coding practices and security awareness
- Maintain security compliance and audit trails
- Collaborate with infrastructure and operations on security hardening

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness and culture across the team
- Meet compliance and regulatory requirements
- Enable rapid, secure response to security incidents

### Interactions with Other Roles
- **Developers**: Partner on secure coding practices; review code for vulnerabilities
- **Technical Leads**: Advise on security architecture and design patterns
- **Product Managers**: Define security requirements and acceptance criteria
- **Release/DevOps Engineers**: Ensure deployments meet security standards
- **Project Managers**: Escalate security risks and coordinate incident response

### Typical Communication
- Security design reviews and threat modeling sessions
- Vulnerability triage and remediation tracking
- Incident response and post-incident blameless retrospectives
- Security training and awareness communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions highlight how roles depend on and support each other throughout the project lifecycle.
