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

## Delivery / Engineering Lead

### Role Summary
The Delivery or Engineering Lead coordinates implementation sequencing, technical decisions, engineering capacity, and technical risk.

### Responsibilities
- Coordinate engineering capacity and implementation sequencing
- Facilitate technical decisions and design reviews
- Identify and mitigate technical dependencies and delivery risks
- Support Developers with design, code quality, and maintainability

### Goals
- Provide a realistic, achievable delivery plan
- Reduce technical risk and avoid implementation bottlenecks
- Maintain engineering quality and sustainable delivery

### Typical Communication
- Engineering planning and dependency reviews
- Technical design discussions and architecture decisions
- Delivery risk updates in project status reports

### Interactions with Existing Roles
- Works with the Project Manager on milestones, capacity, dependencies, and escalations.
- Works with the Product Manager on scope and technical trade-offs.
- Supports Developers with technical direction and resolution of delivery blockers.
- Coordinates with QA/Testing on testability, quality gates, and release readiness.
- Raises unresolved technical or cross-team risks to the appropriate stakeholders.

---

## Release / Deployment Owner

### Role Summary
The Release or Deployment Owner coordinates release readiness and execution, including deployment, verification, rollback planning, and stakeholder communication.

### Responsibilities
- Schedule deployment windows and coordinate release activities
- Confirm prerequisites, smoke tests, rollback plans, and required approvals
- Execute or oversee the deployment process
- Coordinate post-deployment verification and incident escalation
- Prepare release and support communications

### Goals
- Deliver releases safely and predictably
- Minimize deployment-related disruption
- Ensure stakeholders have timely, accurate release information

### Typical Communication
- Release readiness reviews and go/no-go decisions
- Deployment runbooks and rollback plans
- Release announcements and post-deployment summaries

### Interactions with Existing Roles
- Works with Engineering Leads and Developers to confirm implementation and rollback readiness.
- Works with QA/Testing to verify test evidence and smoke-test results.
- Coordinates timing and communications with the Project Manager.
- Confirms release scope and customer impact with the Product Manager.
- Communicates known risks, decisions, and support needs to stakeholders.

---

## Security / Compliance Representative

### Role Summary
The Security or Compliance Representative advises on security, privacy, regulatory, and policy requirements throughout delivery and release.

### Responsibilities
- Identify applicable security and compliance requirements
- Review risks, controls, mitigations, and exceptions
- Advise on security reviews and incident response
- Validate that evidence and approvals are complete when required

### Goals
- Prevent unacceptable security or compliance exposure
- Integrate security and compliance reviews into normal delivery
- Maintain clear records of decisions, risks, and exceptions

### Typical Communication
- Threat, privacy, and compliance reviews
- Risk register entries and exception requests
- Security incident and release-risk updates

### Interactions with Existing Roles
- Advises Developers and Engineering Leads on secure implementation and technical controls.
- Coordinates validation and evidence gathering with QA/Testing.
- Works with Project Managers to track deadlines, decisions, and unresolved risks.
- Works with Product Managers on trade-offs involving customer impact or required scope.
- Escalates high-risk findings or needed approvals to stakeholders and the appropriate security on-call process.

---

## Business / Requirements Analyst

### Role Summary
The Business or Requirements Analyst clarifies business needs, refines requirements, and maintains traceability between outcomes, requirements, and acceptance criteria.

### Responsibilities
- Gather and analyze stakeholder needs
- Document requirements and operational impacts
- Refine acceptance criteria and identify requirement dependencies
- Support prioritization and requirement validation

### Goals
- Ensure delivered work addresses the intended business need
- Reduce ambiguity and rework
- Maintain clear traceability from requirements to outcomes

### Typical Communication
- Requirements workshops and refinement sessions
- Process maps, business rules, and acceptance criteria
- Stakeholder reviews and decision logs

### Interactions with Existing Roles
- Partners with Product Managers on outcomes, prioritization, and backlog refinement.
- Consults stakeholders to clarify needs, constraints, approvals, and operational impacts.
- Works with Developers and Engineering Leads to assess feasibility and implementation details.
- Supports QA/Testing with acceptance expectations and test scenarios.
- Escalates conflicting requirements or unresolved decisions through the Project Manager and Product Manager.

---

## UX / Design Lead

### Role Summary
The UX or Design Lead owns experience strategy and design quality, and ensures that solutions are usable, accessible, and consistent with customer needs.

### Responsibilities
- Lead user research and experience strategy
- Create or govern interaction and visual design
- Define usability, accessibility, and content standards
- Incorporate customer feedback into design decisions

### Goals
- Improve usability and customer satisfaction
- Ensure a consistent, accessible experience
- Reduce rework through early design validation

### Typical Communication
- Design reviews and usability studies
- Interaction designs, prototypes, and content specifications
- Customer feedback summaries and acceptance recommendations

### Interactions with Existing Roles
- Works with Product Managers to align experience decisions with customer outcomes and scope.
- Partners with Developers and Engineering Leads on implementation feasibility and design quality.
- Works with QA/Testing to translate usability and accessibility requirements into acceptance checks.
- Presents significant experience decisions and trade-offs to stakeholders.
- Escalates unresolved customer or design risks to the Product Manager and Project Manager.

---

## Customer / Support Advocate

### Role Summary
The Customer or Support Advocate represents customer and operational perspectives, surfaces recurring issues, and prepares support teams for successful adoption and launch.

### Responsibilities
- Communicate customer feedback and recurring support themes
- Identify support and operational scenarios for planning and testing
- Prepare support documentation and launch readiness materials
- Monitor customer impact and feedback after release

### Goals
- Improve customer outcomes and supportability
- Reduce avoidable launch and operational issues
- Surface customer risk early in delivery

### Typical Communication
- Customer feedback summaries and support trend reviews
- Support readiness checklists and launch documentation
- Post-release feedback and incident updates

### Interactions with Existing Roles
- Shares customer needs and feedback with Product Managers for prioritization.
- Coordinates readiness, training, and communications with the Project Manager and stakeholders.
- Provides known issues and support scenarios to Developers and QA/Testing.
- Works with Release Owners to confirm support readiness and escalation paths.
- Escalates significant customer impact through the Product Manager and incident process.

---

## Change / Adoption Lead

### Role Summary
The Change or Adoption Lead plans enablement, communications, training, and measurement for the people and process impacts of a change.

### Responsibilities
- Identify affected audiences and adoption needs
- Plan training, documentation, communications, and support
- Coordinate rollout activities and adoption measures
- Gather feedback and recommend adoption improvements

### Goals
- Improve adoption and realization of business benefits
- Reduce disruption and resistance to change
- Ensure stakeholders and users are prepared for rollout

### Typical Communication
- Change impact assessments and adoption plans
- Training and communication schedules
- Adoption metrics and post-rollout feedback

### Interactions with Existing Roles
- Works with Product Managers to align adoption activities with customer and business outcomes.
- Coordinates rollout timing and dependencies with the Project Manager.
- Collaborates with stakeholders and Customer/Support Advocates on audiences and enablement.
- Works with Developers and Release Owners to understand new capabilities and deployment timing.
- Escalates low adoption, missing readiness, or unresolved change risks to the Project Manager and Product Manager.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign roles explicitly when needed; in smaller teams, one person may hold multiple roles as long as ownership and handoffs remain clear.
