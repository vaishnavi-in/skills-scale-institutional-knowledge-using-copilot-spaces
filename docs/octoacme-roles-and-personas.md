# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme projects. Each persona has clear responsibilities, goals, and communication patterns to enable effective collaboration.

---

## Core Delivery Roles

### Developers

**Role Summary**
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

**Responsibilities**
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

**Goals**
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

**Interactions**
- **With QA/Testing:** Collaborate on test strategy; respond to test findings
- **With DevOps Engineer:** Work with deployment pipelines; provide deployment guides
- **With UX/UI Designer:** Implement design specs; raise feasibility concerns early
- **With Product Manager:** Clarify acceptance criteria; suggest technical trade-offs

**Typical Communication**
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

**Role Summary**
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

**Responsibilities**
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Create and refine acceptance criteria

**Goals**
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

**Interactions**
- **With Project Manager:** Align weekly on status, risks, and delivery timeline
- **With Developers:** Clarify requirements; discuss technical feasibility
- **With UX/UI Designer:** Define user needs; validate designs
- **With Business Analyst:** Refine requirements with stakeholder input
- **With Support Lead:** Gather post-release feedback for future iterations

**Typical Communication**
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

**Role Summary**
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

**Responsibilities**
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Escalate blockers and track resolution

**Goals**
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

**Interactions**
- **With Product Manager:** Weekly sync on priorities and delivery status
- **With Developers:** Daily standups; identify and resolve blockers
- **With QA/Testing:** Coordinate testing timelines; validate readiness for release
- **With Stakeholders:** Provide regular status updates and escalations

**Typical Communication**
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Specialized Roles

### UX/UI Designer

**Role Summary**
UX/UI Designers translate product requirements into intuitive, accessible, and visually appealing user interfaces. They ensure usability and consistency across the product.

**Responsibilities**
- Conduct user research and usability testing
- Produce wireframes, prototypes, and interaction flows
- Maintain design consistency and accessibility standards
- Collaborate on feature feasibility and technical constraints
- Provide design guidance during implementation and QA

**Goals**
- Deliver user-centered designs that solve customer problems
- Ensure accessibility and inclusive design practices
- Reduce support burden through intuitive interfaces

**Interactions**
- **With Product Manager:** Partner on feature scoping and user needs validation
- **With Developers:** Review implementation against designs; address technical constraints
- **With QA/Testing:** Provide acceptance criteria for user experience; review edge cases
- **With Support Lead:** Gather user feedback post-launch; inform design iterations

**Typical Communication**
- Design reviews and feedback sessions
- Prototype walkthroughs with stakeholders
- Design spec documentation and accessibility checklists

---

### Business Analyst

**Role Summary**
Business Analysts gather, clarify, and document requirements from stakeholders. They bridge communication between business needs and technical delivery.

**Responsibilities**
- Conduct stakeholder interviews and requirements gathering
- Document and prioritize business requirements
- Create business requirement specifications (BRS)
- Identify dependencies and integration points with other systems
- Validate solutions meet business objectives
- Support UAT and stakeholder sign-off

**Goals**
- Ensure clear alignment between business needs and delivery
- Reduce rework due to requirement misunderstandings
- Enable faster decision-making through thorough analysis

**Interactions**
- **With Product Manager:** Refine user stories; validate business value
- **With Project Manager:** Identify scope boundaries and change management needs
- **With Developers:** Clarify technical requirements; review proposed solutions
- **With Stakeholders:** Gather and confirm requirements; support testing and validation

**Typical Communication**
- Requirements documentation and walkthroughs
- UAT coordination and issue tracking
- Stakeholder alignment meetings

---

### QA/Testing Lead

**Role Summary**
QA/Testing Leads own the quality assurance strategy, coordinate testing activities, and ensure products meet acceptance criteria and quality standards.

**Responsibilities**
- Define testing strategy and test plans for projects
- Design and execute unit, integration, and end-to-end tests
- Validate acceptance criteria are met before release
- Identify and triage defects; track resolution
- Coordinate security and compliance testing
- Create and maintain test documentation and automation

**Goals**
- Deliver high-quality software that meets acceptance criteria
- Reduce production defects and customer-impacting issues
- Enable rapid, confident releases

**Interactions**
- **With Developers:** Review code for testability; collaborate on test strategy
- **With Product Manager:** Clarify acceptance criteria; validate feature completeness
- **With Project Manager:** Provide testing status; flag release readiness
- **With DevOps Engineer:** Coordinate smoke tests and post-deploy verification

**Typical Communication**
- Test plans and acceptance criteria reviews
- Daily testing standups during execution
- Defect reports and release readiness assessments

---

### DevOps Engineer

**Role Summary**
DevOps Engineers manage CI/CD pipelines, infrastructure, and deployment automation. They enable fast, reliable, and safe releases.

**Responsibilities**
- Design and maintain CI/CD pipelines
- Manage infrastructure and deployment environments
- Implement infrastructure as code (IaC)
- Automate testing and deployment processes
- Monitor system health and performance post-release
- Support incident response and rollbacks

**Goals**
- Enable rapid, safe, repeatable deployments
- Maintain high system reliability and uptime
- Reduce manual work and human error in releases

**Interactions**
- **With Developers:** Review deployment requirements; support local development tooling
- **With QA/Testing:** Coordinate test environments; facilitate smoke testing
- **With Project Manager:** Ensure deployment readiness; manage release windows
- **With Support Lead:** Monitor production; support incident response

**Typical Communication**
- Deployment guides and runbooks
- Infrastructure and pipeline documentation
- Release coordination and incident response

---

### Support Lead

**Role Summary**
Support Leads serve as the primary liaison between project teams and end-users post-release. They gather user feedback and ensure seamless product support.

**Responsibilities**
- Triage and escalate user-reported issues
- Gather and communicate customer feedback
- Create and maintain support documentation
- Conduct user training and onboarding
- Inform product roadmap based on support trends
- Support incident management and customer communication

**Goals**
- Ensure customers can successfully adopt and use the product
- Reduce support volume through great onboarding and documentation
- Inform product improvements through customer insights

**Interactions**
- **With Product Manager:** Share customer feedback; inform prioritization
- **With Developers:** Escalate bugs; provide context for customer issues
- **With Project Manager:** Coordinate launch communications; plan training
- **With UX/UI Designer:** Flag usability issues; validate design improvements

**Typical Communication**
- Support runbooks and customer documentation
- Feedback summaries and trend reports
- Customer training sessions and launch communications

---

## Role Interaction Matrix (RACI)

| Activity | PM | PdM | Dev | QA | Designer | BA | DevOps | Support |
|----------|----|----|-----|----|----------|----|---------| -------|
| Requirements gathering | C | R | I | I | I | R | — | C |
| Design & feedback | C | R | I | I | R | I | — | C |
| Implementation | C | C | R | I | C | — | — | — |
| Testing & QA | C | C | I | R | I | C | — | — |
| Pre-release checks | R | C | C | R | C | — | R | — |
| Deployment | R | C | — | C | — | — | R | — |
| Post-release monitoring | C | C | — | C | — | — | R | R |
| Customer feedback | C | R | I | — | C | — | — | R |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (final authority)
- **C** = Consulted (provides input)
- **I** = Informed (kept in the loop)
- **—** = Not involved

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in exercises
- Reference the RACI matrix during project planning to clarify decision authority
- Adapt roles based on team size (smaller teams may combine roles)
- Add project-specific personas or role names as needed in the project charter
