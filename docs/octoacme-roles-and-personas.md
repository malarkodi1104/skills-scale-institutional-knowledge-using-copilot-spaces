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
QA and Testing Leads define quality standards, create test plans, and validate that features meet acceptance criteria before release. They collaborate with developers, product managers, and operations to ensure quality gates are met throughout the delivery lifecycle.

### Responsibilities
- Develop comprehensive test plans and test cases aligned with acceptance criteria
- Execute manual QA and coordinate automated test coverage across features
- Identify, document, and track defects through resolution
- Validate features against acceptance criteria before release to production
- Define quality gates, entry/exit criteria, and testing standards for each project phase
- Participate in sprint planning to assess testability and quality risks

### Goals
- Ensure high-quality deliverables with minimal production defects
- Accelerate release cycles through efficient and effective testing
- Provide early feedback to development teams on quality issues
- Establish measurable quality metrics and track improvements

### Typical Communication
- QA planning and test strategy discussions during sprint planning and backlog refinement
- Defect reports with reproducible steps and severity assessments
- Test status updates and quality readiness reviews before release
- Collaboration with developers on test automation and coverage

### Interactions with Other Roles
- **Works closely with Developers** on test coverage, automation, and defect resolution
- **Partners with Product Managers** to clarify acceptance criteria and define quality expectations
- **Coordinates with Technical Leads** on testing strategy for complex features
- **Aligns with Operations Engineers** on production smoke testing and deployment validation

---

## Technical Lead / Architect

### Role Summary
Technical Leads make high-level architectural and design decisions, guide implementation approach, and ensure technical quality and alignment with system constraints. They partner with developers, product managers, and operations to balance technical feasibility with feature delivery.

### Responsibilities
- Define technical approach and architecture for major features and initiatives
- Review design proposals and code for technical alignment with system standards
- Identify technical risks, dependencies, and propose solutions or mitigations
- Mentor developers on technical standards, best practices, and code quality
- Participate in sprint planning to assess technical feasibility and complexity
- Guide decisions on technology choices, frameworks, and infrastructure patterns

### Goals
- Deliver scalable, maintainable, and performant solutions
- Reduce technical debt and minimize refactoring cycles
- Ensure system reliability, security, and scalability
- Build team capability and technical knowledge sharing

### Typical Communication
- Design reviews and architecture discussions for major features
- Technical risk assessments and mitigation plans during planning
- Code review guidance and technical mentoring
- Technical specifications and design documentation

### Interactions with Other Roles
- **Guides Developers** on technical approach and code quality standards
- **Advises Product Managers** on technical feasibility and trade-offs
- **Collaborates with Security Officers** on security architecture and threat modeling
- **Works with Operations Engineers** on infrastructure and deployment patterns

---

## Operations / Infrastructure Engineer

### Role Summary
Operations and Infrastructure Engineers manage deployment pipelines, production environments, and system reliability. They work with developers and QA to ensure smooth releases and operational excellence.

### Responsibilities
- Build, maintain, and improve CI/CD pipelines and automation
- Manage staging and production environments, including configuration and scaling
- Execute deployments, manage rollbacks, and coordinate deployment windows
- Monitor production health, set up alerting, and triage operational issues
- Support incident response and post-incident reviews to prevent recurrence
- Document deployment procedures, runbooks, and operational best practices
- Plan and execute infrastructure changes and capacity planning

### Goals
- Achieve high deployment frequency with low error rates and mean time to recovery
- Minimize unplanned downtime and production incidents
- Enable teams with self-service deployment and monitoring capabilities
- Maintain secure, reliable, and scalable infrastructure

### Typical Communication
- Deployment planning, readiness reviews, and release coordination
- Production monitoring alerts and incident notifications
- Post-deployment verifications and incident retrospectives
- Infrastructure and deployment process improvement discussions

### Interactions with Other Roles
- **Coordinates with Developers** on deployment readiness and CI/CD integration
- **Works with QA/Testing Leads** on smoke testing and production validation
- **Advises Technical Leads** on infrastructure patterns and scalability
- **Partners with Project Managers** on release scheduling and risk mitigation

---

## Security Officer

### Role Summary
Security Officers define security requirements, review features for vulnerabilities, and ensure compliance with organizational policies. They collaborate with developers, architects, and operations to embed security throughout the delivery lifecycle.

### Responsibilities
- Define security requirements and threat models for features and systems
- Review designs and code for security vulnerabilities and compliance issues
- Coordinate security testing and scanning in CI/CD pipelines
- Manage compliance and regulatory requirements (e.g., data privacy, encryption)
- Support incident response for security-related issues and breaches
- Provide security guidance and training to the team
- Monitor and track security improvements and vulnerability remediation

### Goals
- Prevent security breaches and data loss
- Ensure timely detection and remediation of vulnerabilities
- Build security awareness and accountability across the team
- Maintain compliance with organizational and regulatory standards

### Typical Communication
- Security reviews during design and code review phases
- Vulnerability reports with severity assessments and remediation timelines
- Security training and awareness sessions
- Compliance audits and security policy updates

### Interactions with Other Roles
- **Reviews with Developers** on secure coding practices and vulnerability fixes
- **Partners with Technical Leads** on security architecture and threat modeling
- **Advises Operations Engineers** on infrastructure security and access controls
- **Collaborates with Project Managers** on security risks and compliance milestones

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand how personas interact across the delivery lifecycle (planning, execution, testing, release, and operations).
