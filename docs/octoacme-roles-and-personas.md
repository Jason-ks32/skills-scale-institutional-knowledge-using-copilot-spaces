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
QA/Testing Leads define and execute quality strategies for projects. They collaborate with product and engineering teams to establish acceptance criteria, coordinate testing activities, and report quality metrics. They ensure features meet quality standards before release and reduce post-release defect escapes.

### Responsibilities
- Define test strategy and acceptance criteria validation approach
- Coordinate manual and automated testing activities
- Identify, triage, and track defects with severity assessment
- Report quality metrics and blockers to PM and delivery team
- Collaborate on Definition of Done and test coverage targets
- Validate features meet acceptance criteria before release
- Participate in release planning to establish quality gates

### Goals
- Ensure features meet quality standards before release
- Reduce post-release defect escapes and improve customer satisfaction
- Enable confident, low-risk deployments
- Establish and maintain quality benchmarks

### Typical Communication
- Sprint planning and acceptance criteria review meetings
- Daily standups and test status reports
- Pre-release smoke test coordination
- Quality metrics dashboards and reports
- Design reviews to identify testability issues early

### Interaction with Existing Roles
- **With Developers**: Collaborates on test strategy, acceptance criteria clarity, and defect resolution
- **With Product Managers**: Validates that features meet acceptance criteria and business requirements
- **With Project Managers**: Reports quality risks and blockers for escalation
- **With Technical Lead**: Discusses test coverage strategy and automation approach

---

## Test Engineer

### Role Summary
Test Engineers execute manual and automated testing activities. They identify defects, validate acceptance criteria, and maintain test automation frameworks to support continuous quality assurance throughout the project lifecycle.

### Responsibilities
- Execute manual test cases and document results
- Develop and maintain automated test scripts and frameworks
- Identify, document, and track defects with clear reproduction steps
- Validate fixes and perform regression testing
- Collaborate with developers on testability improvements
- Maintain test data and test environment setup
- Report test coverage metrics and trends

### Goals
- Ensure comprehensive test coverage of features
- Detect defects early to reduce production issues
- Maintain efficient, reusable test automation
- Support rapid iteration with reliable test feedback

### Typical Communication
- Daily standups with QA/Testing Lead and development team
- Defect reports and status updates
- Test automation documentation and knowledge sharing
- Retrospectives focused on quality improvements

### Interaction with Existing Roles
- **With Developers**: Works closely to resolve defects and improve testability
- **With QA/Testing Lead**: Reports test results and receives test strategy direction
- **With Project Managers**: Escalates quality blockers affecting release timelines

---

## Security Champion / Security Lead

### Role Summary
Security Champions review security requirements, conduct threat assessments, and ensure compliance in deployments. They manage security incident escalation, coordinate security reviews throughout the project lifecycle, and ensure that security considerations are integrated into planning, design, and release processes.

### Responsibilities
- Define security requirements and acceptance criteria
- Conduct threat assessments and risk analysis for features
- Review design and architecture for security vulnerabilities
- Coordinate security scanning in CI/CD pipelines
- Ensure secure code practices and compliance standards are met
- Manage security incident response and escalation
- Provide security guidance and training to development teams
- Validate security fixes and approve security-related releases

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with regulatory and organizational standards
- Build a security-aware development culture
- Reduce security-related incidents and response time

### Typical Communication
- Design review participation for security assessment
- Weekly security status updates to Project Manager
- Security incident alerts and escalation procedures
- Security documentation and compliance reports
- Collaboration on release notes regarding security changes

### Interaction with Existing Roles
- **With Developers**: Provides security guidance, reviews code for vulnerabilities, and supports incident response
- **With Product Managers**: Aligns on security requirements and trade-offs
- **With Project Managers**: Escalates security risks and manages incident response timeline
- **With QA/Testing Lead**: Coordinates security testing and validation activities
- **With Technical Lead**: Reviews architecture decisions for security implications

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical guidance and vision for projects. They review design decisions, identify technical risks and dependencies, mentor developers, and ensure the team follows technical best practices and maintains code quality standards.

### Responsibilities
- Design technical architecture and solution approach
- Review and approve design documents and major code changes
- Identify technical risks, dependencies, and integration points
- Mentor developers and guide technical problem-solving
- Establish and enforce coding standards and best practices
- Coordinate with other technical leads on cross-team dependencies
- Validate solutions meet performance and scalability requirements
- Guide technology selection and tool decisions

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and complexity
- Accelerate team velocity through clear technical direction
- Identify and mitigate technical risks early

### Typical Communication
- Technical design reviews and architecture discussions
- Code review leadership and guidance
- Technical documentation and decision logs
- Cross-team dependency coordination
- Mentoring and technical guidance in standups and planning

### Interaction with Existing Roles
- **With Developers**: Provides technical direction, reviews code, and mentors on complex problems
- **With Project Managers**: Escalates technical risks and dependencies affecting timeline
- **With QA/Testing Lead**: Discusses test strategy, automation approach, and test coverage
- **With Security Champion**: Aligns on security architecture and technical security implementations

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide strategic alignment, budget approval, and escalation authority for projects. They ensure projects remain aligned with organizational strategy and remove organizational barriers to success.

### Responsibilities
- Provide budget approval and resource allocation
- Ensure project alignment with organizational strategy
- Serve as escalation point for business-impacting issues
- Communicate project status to executive leadership
- Remove organizational and cross-functional blockers
- Approve major scope or timeline changes
- Validate that project outcomes deliver expected business value

### Goals
- Ensure strategic alignment and business value delivery
- Minimize business impact from project delays or issues
- Maintain executive visibility and alignment
- Remove barriers to team success

### Typical Communication
- Monthly or quarterly stakeholder updates
- Executive escalations for business-impacting risks
- Approval gates for major scope/budget/timeline changes
- Post-project business impact assessment

### Interaction with Existing Roles
- **With Project Managers**: Receives escalations and approves major changes
- **With Product Managers**: Validates business value and strategic alignment
- **With Development Team (via PM)**: Provides resource and organizational support

---

## Business Analyst / Requirements Owner

### Role Summary
Business Analysts gather, clarify, and document business requirements. They validate that solutions meet business needs, serve as a bridge between stakeholders and delivery teams, and ensure clear acceptance criteria are defined before implementation begins.

### Responsibilities
- Conduct stakeholder interviews and gather requirements
- Document and clarify business needs and workflows
- Define detailed acceptance criteria with stakeholders
- Validate solutions meet business requirements
- Communicate requirements to development team
- Manage requirements changes and trade-offs
- Conduct user acceptance testing (UAT) coordination

### Goals
- Ensure solutions solve actual business problems
- Reduce rework due to misunderstood requirements
- Accelerate time-to-value by clarifying scope upfront
- Increase stakeholder satisfaction and adoption

### Typical Communication
- Requirement workshops and stakeholder interviews
- Detailed acceptance criteria documentation
- Project planning and backlog prioritization meetings
- UAT coordination and stakeholder feedback gathering
- Requirements clarification during execution

### Interaction with Existing Roles
- **With Product Managers**: Collaborates on requirements prioritization and acceptance criteria
- **With Project Managers**: Communicates requirement changes and clarifies scope
- **With Developers**: Answers questions on requirement intent and acceptance criteria
- **With QA/Testing Lead**: Defines test scenarios based on business requirements

---

## Operations / Support Lead

### Role Summary
Operations/Support Leads participate in release planning, manage post-deployment verification, and escalate production issues. They serve as the bridge between delivery teams and support operations, ensuring smooth deployments and rapid incident response.

### Responsibilities
- Participate in release planning and deployment scheduling
- Coordinate deployment procedures and runbooks
- Manage post-deployment verification and smoke testing
- Monitor production for deployment-related issues
- Escalate and coordinate response to production incidents
- Plan rollback procedures and mitigation strategies
- Communicate deployment status to support and end users
- Gather operational feedback for future improvements

### Goals
- Ensure smooth, low-risk deployments to production
- Minimize post-deployment issues and user impact
- Enable rapid incident detection and response
- Reduce mean time to recovery (MTTR) for production issues

### Typical Communication
- Release planning meetings and deployment coordination
- Deployment runbook and procedures documentation
- Post-deployment status updates and incident reports
- Production monitoring and alert escalations
- Retrospectives focused on deployment and operational improvements

### Interaction with Existing Roles
- **With Project Managers**: Coordinates release schedule and escalates production issues
- **With Technical Lead**: Reviews deployment procedures and architecture for operational concerns
- **With QA/Testing Lead**: Participates in pre-release smoke testing
- **With Developers**: Coordinates rapid fixes for production issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When setting up a project, identify which personas are needed based on project scope and complexity.
- Refer to interaction notes to understand communication patterns and handoff points between roles.
