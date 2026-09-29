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
QA/Testing Leads define quality standards, develop test strategies, and ensure features meet acceptance criteria and quality gates before release. They are responsible for validating feature readiness and maintaining confidence in product quality.

### Responsibilities
- Develop test plans and acceptance criteria for each backlog item
- Design and execute unit, integration, and end-to-end tests
- Manage test automation and CI/testing infrastructure
- Track defects and quality metrics throughout the project lifecycle
- Collaborate with Product Managers on success criteria and acceptance standards
- Approve features for release based on established quality gates
- Identify quality risks and recommend mitigation strategies

### Goals
- Ensure high-quality releases with minimal defects
- Reduce time spent on rework and bug fixes
- Provide confidence in feature readiness before production deployment
- Establish and maintain quality standards across all deliverables

### Typical Communication
- Quality metrics in weekly status updates
- Test plan reviews during sprint planning
- Defect triage meetings and code review participation
- Release readiness sign-off and pre-deployment verification
- Collaboration with Developers on test coverage and acceptance criteria clarity

### Interaction with Other Roles
- **With Developers**: Review acceptance criteria clarity, provide test feedback, collaborate on test coverage strategies
- **With Product Managers**: Validate success metrics, confirm acceptance criteria completeness, communicate quality risks
- **With Project Managers**: Report quality status, flag quality-related blockers, participate in risk assessments
- **With Technical Architects**: Validate technical design testability, collaborate on test automation architecture

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects and Tech Leads shape technical strategy, review design decisions, mentor developers, and manage technical risk. They ensure architectural coherence, scalability, and long-term maintainability of the system.

### Responsibilities
- Define architectural patterns and technology choices for the project
- Review technical designs and code for quality, alignment, and adherence to standards
- Identify and mitigate technical risks and dependencies early in the planning phase
- Mentor developers and support skill development through design reviews and feedback
- Provide input on scalability, performance, and maintainability considerations
- Participate in technical spikes and design reviews to evaluate new approaches
- Document architectural decisions and rationale (ADRs)

### Goals
- Maintain architectural coherence and code quality across the project
- Reduce technical debt and long-term risk to product sustainability
- Enable team learning and growth through mentorship and guidance
- Ensure decisions are traceable and understood by the team

### Typical Communication
- Design review sessions and technical decision records (ADRs)
- Code review comments with architectural perspective and mentoring
- Risk identification in planning and retrospectives
- Technical spike findings and recommendations
- Collaboration on system design documentation

### Interaction with Other Roles
- **With Developers**: Mentor through code reviews, guide design decisions, support problem-solving
- **With Project Managers**: Flag technical risks early, provide effort estimates for architectural changes
- **With QA/Testing Leads**: Ensure designs are testable, collaborate on test automation architecture
- **With Product Managers**: Advise on technical feasibility and trade-offs, influence roadmap decisions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors are business owners and decision-makers who provide strategic direction, secure resources, and ensure alignment with organizational goals. They serve as the executive voice and ultimate authority on project prioritization and go/no-go decisions.

### Responsibilities
- Provide business context and strategic direction for the project
- Secure and allocate necessary resources (budget, personnel, tools)
- Make go/no-go decisions at key milestones and gates
- Approve scope changes and major trade-offs
- Escalate blockers that require executive intervention
- Communicate project progress and outcomes to broader organizational leadership
- Validate that the project delivers on business objectives

### Goals
- Ensure project alignment with organizational strategy
- Maximize return on investment and business value delivery
- Remove organizational blockers to project success
- Maintain stakeholder confidence and support

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Decision gate reviews and approval meetings
- Escalation and blocker resolution discussions
- Go/no-go decision points at major milestones
- Business outcome validation and ROI confirmation

### Interaction with Other Roles
- **With Project Managers**: Receive regular status updates, approve scope changes, resolve escalations
- **With Product Managers**: Align on strategic priorities and business outcomes
- **With Developers/Tech Teams**: Provide context for business decisions, understand feasibility constraints
- **With Retrospective Leads**: Participate in post-project reviews to assess business impact

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate Agile ceremonies, remove team impediments, and foster a culture of continuous improvement. They serve as process guardians and enablers, helping the team work more effectively within their chosen Agile framework.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove team impediments and blockers that hinder progress
- Coach the team on Agile practices and principles
- Maintain sprint artifacts (backlog, board, burndown charts)
- Foster psychological safety and encourage team collaboration
- Shield the team from external distractions during sprints
- Track and improve team velocity and process health metrics
- Escalate impediments that require management intervention

### Goals
- Enable the team to deliver at a consistent, sustainable pace
- Improve team collaboration, communication, and morale
- Reduce waste and cycle time through process improvements
- Build an adaptive, high-performing team culture

### Typical Communication
- Daily standup facilitation and blocker identification
- Sprint planning and capacity planning discussions
- Retrospective facilitation and action item tracking
- Metrics reporting (velocity, burndown, cycle time)
- Coaching conversations with individual team members

### Interaction with Other Roles
- **With All Team Members**: Remove impediments, coach on Agile practices, foster psychological safety
- **With Project Managers**: Align on sprint schedules, escalate process blockers, report team health
- **With Developers/QA/Tech Teams**: Support self-organization, facilitate collaboration, remove distractions
- **With Product Managers**: Help manage backlog refinement cadence, clarify acceptance criteria

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment infrastructure, release pipelines, and operational readiness to enable safe, frequent releases. They bridge development and operations, ensuring reliable, automated, and observable deployments.

### Responsibilities
- Design and maintain CI/CD pipelines for automated testing and deployment
- Manage deployment environments (staging, production) and infrastructure as code
- Automate release processes and create rollback procedures for rapid incident response
- Monitor system health and performance post-release
- Coordinate with Developers and QA on deployment requirements and testing needs
- Document and execute release runbooks and deployment procedures
- Implement security scanning and compliance checks in the deployment pipeline
- Support incident response and post-incident analysis

### Goals
- Enable fast, safe, and repeatable releases with minimal manual intervention
- Minimize deployment risk and production incidents
- Provide operational visibility and observability across environments
- Reduce time-to-recovery and support operational excellence

### Typical Communication
- Release planning and pre-deployment checklists
- Deployment status updates and incident response coordination
- Infrastructure and tooling improvements during retrospectives
- Post-release verification and monitoring alerts
- Collaboration with Developers on deployment requirements

### Interaction with Other Roles
- **With Developers**: Support deployment needs, provide feedback on pipeline improvements, collaborate on monitoring
- **With QA/Testing Leads**: Coordinate on staging environment readiness, align on test automation in CI/CD
- **With Project Managers**: Provide deployment timeline estimates, flag deployment risks
- **With Technical Architects**: Implement architectural decisions in infrastructure, design for scalability and resilience

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interaction with Other Roles" section to understand how personas collaborate across functional boundaries.
