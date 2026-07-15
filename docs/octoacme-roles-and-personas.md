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

### Interactions
- **With QA/Testing Lead**: Discuss testability requirements, address defects, validate fixes
- **With Technical Architect**: Seek design guidance, participate in architecture reviews
- **With Security Champion**: Implement security recommendations, participate in threat modeling
- **With Scrum Master**: Collaborate on sprint planning, escalate blockers

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Align with business objectives and measure impact

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Backlog refinement and prioritization sessions

### Interactions
- **With Project Manager**: Align on scope, timeline, and resource needs
- **With QA/Testing Lead**: Define acceptance criteria and testability requirements
- **With Technical Architect**: Discuss feasibility and technical trade-offs
- **With Security Champion**: Incorporate security requirements into features
- **With Stakeholder/Business Owner**: Align priorities and measure business impact
- **With Scrum Master**: Support backlog refinement and prioritization ceremonies

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
- Track progress against milestones and escalate issues

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Executive briefs and steering committee updates

### Interactions
- **With Product Manager**: Align on scope, priorities, and delivery timeline
- **With QA/Testing Lead**: Track testing progress and confirm release readiness
- **With Technical Architect**: Understand technical complexity and risks
- **With Security Champion**: Manage security risks and compliance requirements
- **With Scrum Master**: Coordinate ceremonies and remove process blockers
- **With Stakeholder/Business Owner**: Report progress and seek prioritization decisions

---

## QA / Testing Lead

### Role Summary
QA/Testing Leads design and execute comprehensive testing strategies to ensure features meet quality standards and acceptance criteria. They collaborate with developers and product managers to define testability requirements and validate solutions before release.

### Responsibilities
- Develop and maintain comprehensive test plans and test cases
- Coordinate manual and automated testing efforts
- Define acceptance criteria testability requirements and edge cases
- Identify, log, and track defects with clear reproduction steps
- Validate fixes and perform regression testing
- Report quality metrics and test coverage
- Participate in release readiness assessments
- Mentor developers on testable design patterns

### Goals
- Ensure all features meet acceptance criteria and Definition of Done
- Minimize bugs reaching production
- Maintain high test coverage and build team confidence in releases
- Provide early feedback to catch quality issues before QA stage

### Typical Communication
- Sprint planning and backlog refinement (testability input)
- Daily standups and QA sync calls
- Defect reports and testing status dashboards
- Release readiness sign-offs and quality sign-offs
- Testing strategy and test plan reviews

### Interactions
- **With Developers**: Clarify testable requirements, report defects, validate fixes, discuss edge cases
- **With Product Managers**: Refine acceptance criteria, align on testing scope
- **With Project Managers**: Track testing progress, escalate blockers, confirm release readiness
- **With Technical Architect**: Understand system design to optimize test strategy
- **With Security Champion**: Include security testing in acceptance criteria and test plans

---

## Technical Architect

### Role Summary
Technical Architects provide design leadership and guidance on technology choices, system design, and technical strategy. They ensure solutions are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Lead technical design reviews and architecture discussions
- Define technology standards, patterns, and best practices
- Assess technical risks and propose mitigation strategies
- Mentor developers on design patterns and code quality
- Evaluate build-vs-buy decisions and tool selections
- Ensure consistency across systems and components
- Review major technical decisions for alignment with strategy
- Provide guidance on performance, scalability, and maintainability

### Goals
- Build scalable, maintainable systems
- Reduce technical debt and complexity
- Enable fast, confident delivery through clear design patterns
- Maintain technical consistency across the organization

### Typical Communication
- Technical design reviews and architecture sessions
- Code reviews and design feedback
- Technology evaluation and selection meetings
- Risk escalation and mitigation planning
- Architecture documentation and decision logs

### Interactions
- **With Developers**: Guide design, review code, provide technical mentorship
- **With Product Managers**: Assess technical feasibility, discuss trade-offs and constraints
- **With Project Managers**: Identify technical risks, estimate technical complexity and impact on timeline
- **With QA/Testing Lead**: Discuss testability and performance testing requirements
- **With Security Champion**: Incorporate security architecture and threat modeling

---

## Scrum Master / Delivery Coach

### Role Summary
Scrum Masters facilitate agile processes, remove blockers, and coach teams on continuous improvement. They ensure the team follows agreed-upon ceremonies and practices, and help resolve process impediments.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove process blockers and impediments
- Coach team on agile principles, practices, and mindset
- Track and monitor sprint health, velocity, and burndown
- Escalate risks, dependencies, and organizational impediments
- Drive continuous process improvement through retrospectives
- Foster psychological safety and team cohesion
- Protect team from scope creep and external distractions

### Goals
- Enable consistent, predictable delivery
- Create psychological safety and high-performing team culture
- Minimize process waste and maximize team flow
- Improve team velocity and effectiveness over time

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action tracking
- 1-on-1 coaching conversations
- Metrics and velocity tracking
- Process improvement proposals

### Interactions
- **With All Team Members**: Facilitate ceremonies, remove blockers, provide coaching
- **With Project Managers**: Coordinate on scheduling, escalation, and status tracking
- **With Product Managers**: Support backlog refinement and prioritization sessions
- **With Developers**: Coach on agile practices and team collaboration

---

## Security Champion

### Role Summary
Security Champions embed security best practices into project execution, ensuring compliance with security policies and identifying security risks early. They serve as security advocates and escalation points for the team.

### Responsibilities
- Review requirements and design for security implications
- Conduct security assessments and threat modeling
- Ensure security testing is included in QA plans
- Advise on secure coding practices and dependencies
- Track security compliance and audit requirements
- Escalate security risks to security team and leadership
- Participate in code reviews from a security perspective
- Stay current on security threats and best practices

### Goals
- Reduce security vulnerabilities and compliance risk
- Build security awareness across the team
- Enable secure-by-design delivery practices
- Ensure compliance with regulatory and organizational requirements

### Typical Communication
- Security design reviews and threat modeling sessions
- Code reviews (security focus) and dependency scans
- Compliance and audit coordination
- Risk escalation and incident response
- Security training and awareness updates

### Interactions
- **With Developers**: Advise on secure coding, review for vulnerabilities, share threat models
- **With QA/Testing Lead**: Include security testing in acceptance criteria and test plans
- **With Project Managers**: Escalate security risks, track compliance items, manage security timeline impact
- **With Product Managers**: Identify security requirements and dependencies from business perspective
- **With Technical Architect**: Incorporate security architecture and design principles

---

## Stakeholder / Business Owner

### Role Summary
Stakeholders and Business Owners represent the business and customer perspective, ensuring projects align with strategic goals and deliver measurable business value. They provide prioritization, resource decisions, and business context.

### Responsibilities
- Define business objectives and success metrics
- Prioritize features and trade-offs from business perspective
- Approve budgets, timelines, and resource allocation
- Communicate project status to executive leadership
- Provide business context and decision-making authority
- Validate business outcomes and ROI post-release
- Escalate blockers and constraints that impact business outcomes

### Goals
- Maximize ROI and business impact
- Align technology investments with strategy
- Ensure accountability for business results
- Reduce time-to-value for business initiatives

### Typical Communication
- Monthly status updates and executive briefings
- Steering committee meetings and decision gates
- Business requirements and priority-setting sessions
- Post-release outcome reviews and retrospectives
- Strategic alignment and roadmap sessions

### Interactions
- **With Product Managers**: Set business context, validate priorities, measure impact, align on ROI
- **With Project Managers**: Approve scope, timeline, and resource decisions; resolve trade-offs
- **With All Team Members**: Provide business context and strategic alignment

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when creating issue templates, checklists, and communication guidelines.
