# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Personas

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions
- Receives design specs and acceptance criteria from **UX Researcher/Designer** and **Product Managers**
- Partners with **Tech Lead** on architectural decisions and code quality
- Collaborates with **QA** on test coverage and acceptance
- Works with **Release Engineer** during deployment phases
- Escalates observability and production issues to **SRE/Platform Engineer**

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions
- Partners with **UX Researcher/Designer** on problem validation and user feedback
- Aligns with **Project Manager** on schedule and resource constraints
- Reviews metrics and dashboards from **Data Analyst**
- Escalates customer impact and feedback from **Customer Success/Support Liaison**
- Coordinates with **Compliance/Security Representative** on regulatory requirements

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions
- Works with **Delivery Lead** on day-to-day execution and dependency resolution
- Coordinates with **Engineering Manager** on team capacity and resourcing
- Partners with **Product Manager** on prioritization and scope
- Monitors progress with **Tech Lead** on technical risks
- Escalates incidents and blockers to stakeholders and **Project Sponsor**

---

## Operational & Cross-Functional Personas

### Delivery Lead

#### Role Summary
Delivery Leads coordinate day-to-day delivery activities across development teams, manage schedules, unblock dependencies, and maintain the release calendar. They work closely with Project Managers and serve as the operational hub for delivery execution.

#### Responsibilities
- Coordinate daily standup cadence and manage blockers
- Unblock cross-team dependencies and escalate conflicts
- Maintain the release calendar and deployment schedule
- Track and communicate status to Project Manager and stakeholders
- Facilitate handoffs between development, QA, and release phases

#### Goals
- Ensure predictable, on-time delivery
- Reduce cycle time and remove friction from the delivery pipeline
- Maintain team velocity and capacity visibility

#### Typical Communication
- Daily standups and delivery huddles
- Dependency tracking and escalation logs
- Release readiness and deployment communications
- Weekly delivery metrics and progress reports

#### Interactions
- Works closely with **Project Manager** on schedule and resource alignment
- Coordinates with **Developers** and **Tech Lead** on task status and blockers
- Partners with **QA** on testing phase readiness
- Aligns with **Release Engineer** on deployment windows and readiness
- Escalates risks to **Engineering Manager** when capacity or capability gaps emerge

---

### Tech Lead

#### Role Summary
Tech Leads own technical design decisions, conduct architecture reviews, and mentor developers on code quality and maintainability. They serve as the technical authority for a feature area or squad.

#### Responsibilities
- Lead technical design discussions and architecture reviews
- Provide guidance on design patterns and code quality standards
- Mentor developers on implementation best practices
- Identify and mitigate technical risks
- Sign off on large changes and complex implementations

#### Goals
- Ensure scalable, maintainable architecture
- Build team technical capability and consistency
- Reduce technical debt and rework

#### Typical Communication
- Design review sessions and technical discussions
- Code review feedback and mentoring
- Technical risk assessments and mitigation plans
- Architecture documentation

#### Interactions
- Collaborates with **Developers** on design and code quality
- Partners with **Engineering Manager** on skill gaps and hiring needs
- Works with **UX Researcher/Designer** on technical feasibility of designs
- Coordinates with **SRE/Platform Engineer** on observability and operability
- Escalates architectural decisions to **Compliance/Security Representative** when needed

---

### Engineering Manager

#### Role Summary
Engineering Managers are responsible for people management, team capacity planning, performance feedback, and hiring. They ensure the team has the right skills and support to deliver effectively.

#### Responsibilities
- Manage performance feedback and career development for engineers
- Plan team capacity and coordinate resourcing across projects
- Hire and onboard new team members
- Remove organizational obstacles and support team well-being
- Advocate for team in resource and hiring decisions

#### Goals
- Build a high-performing, stable team
- Align team skills with project needs
- Reduce team turnover and improve satisfaction

#### Typical Communication
- One-on-ones and performance reviews
- Capacity planning and resource allocation meetings
- Hiring pipeline and candidate reviews
- Team health and engagement surveys

#### Interactions
- Partners with **Project Manager** on resourcing and capacity needs
- Works with **Tech Lead** on skill development and technical hiring
- Coordinates with **Delivery Lead** on workload and stress indicators
- Collaborates with **SRE/Platform Engineer** on on-call rotations and operational load
- Reports to **Project Sponsor** on team status and escalations

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers conduct user research, produce interaction designs, and provide usability guidance. They ensure solutions are user-centered and meet acceptance criteria.

#### Responsibilities
- Conduct user research and validate problem statements
- Produce wireframes, prototypes, and design specifications
- Define acceptance criteria related to usability and user experience
- Perform usability testing and gather feedback
- Hand off designs to developers with clear specifications

#### Goals
- Deliver user-centered, usable solutions
- Reduce rework due to design misunderstandings
- Maximize user satisfaction and adoption

#### Typical Communication
- User research findings and reports
- Design mockups and specifications
- Usability test results and recommendations
- Design review and feedback sessions

#### Interactions
- Partners with **Product Manager** on problem statement and success metrics
- Collaborates with **Developers** and **Tech Lead** on technical feasibility
- Works with **QA** to define usability acceptance criteria
- Provides design guidance to **Release Engineer** on release communication and UI changes
- Reports insights to **Customer Success/Support Liaison** on user feedback

---

### Release Engineer / Release Manager

#### Role Summary
Release Engineers maintain release pipelines, coordinate deployments, validate release readiness, and manage rollback procedures. They ensure safe, predictable production releases.

#### Responsibilities
- Maintain and improve release automation and CI/CD pipelines
- Coordinate deployment schedules and windows
- Validate pre-release checklist (tests, security scans, documentation)
- Execute deployments and verify post-deployment health
- Execute and document rollback procedures when needed

#### Goals
- Enable fast, safe releases with minimal manual effort
- Reduce deployment-related incidents and outages
- Maintain clear audit trails and release documentation

#### Typical Communication
- Release notes and deployment plans
- Pre-release readiness checklists
- Deployment window communications
- Incident and rollback documentation

#### Interactions
- Works with **Developers** on build and deployment artifacts
- Coordinates with **Delivery Lead** on deployment scheduling
- Partners with **SRE/Platform Engineer** on health checks and rollback procedures
- Aligns with **Compliance/Security Representative** on release approval requirements
- Communicates release status to **Project Manager** and stakeholders

---

### SRE / Platform Engineer

#### Role Summary
SREs and Platform Engineers operate production systems, define Service Level Objectives (SLOs), run incident response, and own observability and runbooks. They ensure systems are reliable, observable, and operationally excellent.

#### Responsibilities
- Define and monitor SLOs for critical services
- Build and maintain observability (logging, metrics, tracing)
- Respond to and manage production incidents
- Maintain incident runbooks and troubleshooting guides
- Advise developers on operability and observability best practices

#### Goals
- Maintain high system reliability and availability
- Enable fast incident detection and resolution
- Reduce toil through automation and tooling

#### Typical Communication
- On-call rotations and incident reports
- SLO dashboards and reliability metrics
- Post-incident retrospectives and action items
- Observability and operational guidance to developers

#### Interactions
- Supports **Developers** on observability instrumentation and runbook development
- Partners with **Tech Lead** on architecture decisions affecting reliability
- Works with **Release Engineer** on safe deployment procedures and health checks
- Coordinates with **Delivery Lead** on operational readiness and incident impact
- Collaborates with **Compliance/Security Representative** on security monitoring and audit logs
- Reports reliability metrics to **Data Analyst** and **Project Manager**

---

### Data Analyst

#### Role Summary
Data Analysts define metrics, instrument events, produce dashboards, and conduct analysis to measure project success and product impact. They enable data-driven decision-making.

#### Responsibilities
- Define success metrics aligned with project goals
- Design event instrumentation and data collection
- Build dashboards and automated reporting
- Conduct analysis to measure feature impact and user behavior
- Provide measurement support to Product and Project teams

#### Goals
- Enable data-driven prioritization and decisions
- Measure and communicate project impact
- Identify trends and opportunities for optimization

#### Typical Communication
- Metric definitions and measurement frameworks
- Dashboards and automated reports
- Analysis findings and recommendations
- Instrumentation guidance to developers

#### Interactions
- Partners with **Product Manager** on success metrics and KPI definitions
- Works with **Developers** on event instrumentation and data collection
- Provides dashboards and reports to **SRE/Platform Engineer** for reliability metrics
- Collaborates with **UX Researcher/Designer** on user behavior analysis
- Reports metrics to **Project Manager** and stakeholders on project progress

---

### Customer Success / Support Liaison

#### Role Summary
Customer Success and Support Liaisons represent customer impact and voice within project teams. They triage high-severity customer issues, surface product feedback, and coordinate customer communications.

#### Responsibilities
- Monitor and triage high-impact customer issues
- Surface customer feedback and pain points to Product team
- Advocate for customer-impacting improvements
- Coordinate customer communications during releases and incidents
- Gather usage and adoption insights

#### Goals
- Minimize customer impact and escalations
- Ensure product development is informed by real customer needs
- Accelerate customer adoption and satisfaction

#### Typical Communication
- Customer issue reports and escalations
- Feature request and feedback summaries
- Customer impact assessments for prioritization
- Release and incident communications

#### Interactions
- Reports customer feedback to **Product Manager** for prioritization
- Escalates high-severity issues to **Delivery Lead** and **Project Manager**
- Coordinates with **SRE/Platform Engineer** on production incident customer impact
- Provides customer context to **Release Engineer** on release communication needs
- Works with **UX Researcher/Designer** on user feedback validation
- Reports adoption and satisfaction metrics to **Data Analyst**

---

### Compliance / Security Representative

#### Role Summary
Compliance and Security Representatives advise on regulatory and security controls, conduct security reviews, and ensure releases meet compliance requirements. They mitigate security and regulatory risk.

#### Responsibilities
- Advise on applicable compliance and security controls
- Conduct security reviews of features and architecture
- Validate that releases meet compliance requirements
- Maintain compliance documentation and audit trails
- Escalate security and compliance risks

#### Goals
- Prevent security breaches and compliance violations
- Enable secure, compliant product delivery
- Maintain organizational risk posture

#### Typical Communication
- Security review findings and recommendations
- Compliance requirement assessments
- Security incident reports and escalations
- Compliance audit documentation

#### Interactions
- Partners with **Product Manager** on regulatory and compliance implications
- Works with **Tech Lead** and **Developers** on secure design and implementation
- Coordinates with **Release Engineer** on compliance approval for releases
- Collaborates with **SRE/Platform Engineer** on security monitoring and audit logs
- Advises **Project Manager** on compliance and regulatory risks

---

## Why These Personas Matter

**Clearer Ownership**: Explicit responsibility definitions reduce ambiguity and accelerate decision-making during critical phases like deployments and incidents.

**Effective Handoffs**: Named personas and interaction patterns reduce rework due to misaligned expectations across design, engineering, release, and operations.

**Better Measurement & Feedback Loops**: Data Analysts and UX Researchers provide continuous evidence to inform prioritization and validate impact.

**Faster Onboarding**: New team members can map their role to a persona and quickly understand responsibilities and key interactions.

**Improved Incident Response**: Clear escalation paths and operational roles (SRE, Release Engineer) reduce mean-time-to-resolution.

---

## How to Use These Personas

- **Staffing & Planning**: Use personas to identify capability gaps and plan hiring.
- **Process Definition**: Reference personas in playbooks, checklists, and runbooks to clarify who does what.
- **Communication**: Use persona names in status updates, escalations, and decision logs to improve clarity.
- **Onboarding**: Share this document with new team members to explain team structure and key interactions.
- **Iteration**: Refine these personas as your team evolves; they should reflect your actual structure and needs.

---

## How These Personas Are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Test handoff scenarios (e.g., Designer → Developer → QA → Release Engineer → SRE) to validate clarity and reduce rework.
