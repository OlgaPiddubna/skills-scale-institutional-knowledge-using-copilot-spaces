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

### Interactions with Other Roles
- Collaborate with **QA/Testing Lead** on acceptance criteria validation and test strategy
- Work with **Technical Architect** on design decisions for complex features
- Coordinate with **Operations/DevOps Engineer** on deployment requirements and observability
- Support **Project Managers** with estimation and risk identification
- Implement features defined by **Product Managers**

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

### Interactions with Other Roles
- Partner with **Project Managers** on delivery timelines and scope
- Align with **Stakeholders/Sponsors** on priorities and business goals
- Collaborate with **Technical Architect** on feasibility of large initiatives
- Work with **QA/Testing Lead** on quality standards and acceptance criteria
- Engage **Developers** during backlog refinement and planning

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

### Interactions with Other Roles
- Partner with **Product Managers** on priorities and roadmap execution
- Coordinate with **Operations/DevOps Engineer** on deployment windows and release planning
- Support **Scrum Master/Agile Coach** with project-level tracking and escalations
- Engage **Stakeholders/Sponsors** on progress, risks, and decisions
- Track **Developers** and **QA/Testing Lead** capacity and dependencies
- Consult **Technical Architect** on complex technical dependencies and risks

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define quality standards, build and execute test strategies, and validate that features meet acceptance criteria before release. They champion quality culture and ensure customer value through comprehensive testing.

### Responsibilities
- Define test strategy aligned with project scope and risk profile
- Create and maintain test plans, cases, and automation frameworks
- Coordinate manual and automated testing efforts
- Validate acceptance criteria before marking work as done
- Track and report defect trends and quality metrics
- Participate in retrospectives to improve testing processes
- Partner with developers on testing best practices and coverage goals

### Goals
- Ensure features meet quality and usability standards
- Catch issues before production
- Enable faster iteration through efficient test automation
- Reduce post-release defects and customer impact

### Typical Communication
- QA standups and sprint ceremonies
- Defect reports and quality dashboards
- Test plan reviews and acceptance criteria walkthroughs
- Pre-release quality sign-offs

### Interactions with Other Roles
- Collaborate with **Developers** on test automation and coverage
- Work with **Product Managers** on acceptance criteria and user scenario validation
- Support **Project Managers** with quality metrics and release readiness reports
- Coordinate with **Operations/DevOps Engineer** on smoke tests and production verification
- Align with **Technical Architect** on test strategy for complex systems
- Provide feedback to **Scrum Master** on process improvements for testing efficiency

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors are business leaders or decision-makers who provide strategic direction, resources, and approval for projects. They represent business needs, organizational priorities, and expected outcomes.

### Responsibilities
- Approve project initiation, planning, and major scope changes
- Provide business context and strategic priorities
- Allocate resources and budget for projects
- Escalate blockers and risks that require executive attention
- Validate that delivered outcomes align with business goals
- Communicate project status to wider organization

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Minimize business risk and disruption
- Maximize return on investment

### Typical Communication
- Monthly stakeholder updates and status reports
- Governance and approval gates
- Escalation channels for business-impacting decisions
- Post-project reviews and business impact assessments

### Interactions with Other Roles
- Partner with **Project Managers** on scope, timeline, and resource decisions
- Align with **Product Managers** on business priorities and success metrics
- Receive risk escalations from **Developers** and **Project Managers**
- Approve major decisions involving **Technical Architect** recommendations
- Participate in **Scrum Master**-facilitated governance meetings when needed

---

## Technical Architect

### Role Summary
Technical Architects design system solutions for complex projects, ensuring scalability, reliability, and alignment with organizational technical standards. They provide technical leadership and guidance on design trade-offs.

### Responsibilities
- Design system architecture and integration approaches
- Evaluate technology choices and trade-offs
- Identify technical risks and propose mitigation strategies
- Ensure alignment with organizational technical standards and patterns
- Review and guide complex technical decisions
- Support capacity planning for large or cross-system initiatives
- Collaborate on performance, security, and scalability requirements

### Goals
- Enable sustainable, scalable system design
- Reduce technical debt and maintenance burden
- Accelerate delivery through proven patterns and approaches
- Ensure systems meet non-functional requirements (performance, security, reliability)

### Typical Communication
- Technical design reviews and architecture documentation
- Working sessions with developers on complex problems
- Risk assessments and mitigation planning
- Technology evaluation and proof-of-concept discussions

### Interactions with Other Roles
- Guide **Developers** on design patterns and technical decisions
- Collaborate with **Product Managers** on feasibility of major features
- Partner with **Project Managers** on technical risk assessment and timeline impact
- Support **QA/Testing Lead** with test strategy for complex systems
- Advise **Operations/DevOps Engineer** on infrastructure and deployment architecture
- Influence **Stakeholders/Sponsors** on technical investment decisions

---

## Operations/DevOps Engineer

### Role Summary
Operations/DevOps Engineers manage infrastructure, deployment pipelines, monitoring, and incident response. They enable reliable, observable delivery and rapid incident resolution, bridging development and production.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment infrastructure
- Configure monitoring, logging, and alerting for production systems
- Manage deployment windows and coordinate releases
- Lead incident response and post-incident reviews
- Provide guidance on scalability, performance, and security
- Automate manual operational tasks
- Ensure compliance with organizational operational standards

### Goals
- Minimize deployment risk and human error
- Achieve fast, reliable releases
- Reduce incident time-to-resolution
- Enable observability and rapid issue detection

### Typical Communication
- Deployment coordination meetings
- Incident response channels and post-mortems
- Infrastructure and observability design reviews
- Weekly reliability and performance reports

### Interactions with Other Roles
- Collaborate with **Developers** on deployment requirements and observability instrumentation
- Coordinate with **Project Managers** on release planning and deployment windows
- Partner with **QA/Testing Lead** on smoke test execution and production verification
- Support **Technical Architect** with infrastructure design and scalability planning
- Advise **Product Managers** on performance and reliability trade-offs
- Lead incident coordination with **Stakeholders/Sponsors** during critical issues

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team ceremonies, remove impediments, and foster a culture of continuous improvement and psychological safety. They enable the team to work effectively within their chosen agile framework.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and help resolve team impediments and blockers
- Coach team members on agile practices and principles
- Promote psychological safety and encourage feedback
- Track team velocity and process metrics
- Facilitate continuous improvement and process refinement
- Shield team from external distractions and scope creep

### Goals
- Enable consistent, predictable delivery cadence
- Build high-performing, self-organizing teams
- Foster culture of continuous improvement
- Remove obstacles to team productivity

### Typical Communication
- Sprint ceremonies and retrospectives
- One-on-one coaching conversations
- Process improvement discussions
- Team health and velocity tracking

### Interactions with Other Roles
- Support **Developers** in breaking down work and managing technical impediments
- Collaborate with **Project Managers** on schedule and dependency management
- Work with **Product Managers** on backlog prioritization and story clarity
- Encourage **QA/Testing Lead** participation in ceremonies and continuous improvement
- Facilitate **Stakeholders/Sponsors** communication and expectation management
- Coordinate with **Technical Architect** on technical blockers and design review scheduling

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When running exercises, assign personas to participants to explore cross-functional collaboration and communication patterns.
- Reference these personas in project charters and team compositions to ensure clear accountability and role clarity.
