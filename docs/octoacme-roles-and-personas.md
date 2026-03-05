# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. The goal is to make responsibilities explicit, reduce handoff ambiguity, and improve cross-functional collaboration.

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

### Interactions with other personas
- Works with Product Managers to clarify requirements and acceptance criteria.
- Coordinates with QA Engineers on testability and acceptance tests.
- Collaborates with Technical Writers for necessary docs and release notes.

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

### Interactions with other personas
- Partners with Project Managers for timelines and resource coordination.
- Works closely with UX Designers to shape customer experiences.
- Provides Business Analysts and Developers with clarified requirements.

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

### Interactions with other personas
- Works with Product Managers to align on scope and priorities.
- Escalates cross-team dependencies to Product Leads and Sponsors.
- Coordinates with Support/Customer Success for post-release readiness.

---

## QA Engineer (Suggested new persona)

### Role Summary
QA Engineers design and execute testing strategies to ensure product quality and that acceptance criteria are met.

### Responsibilities
- Develop test plans, test cases, and automation strategies
- Execute integration, regression, and acceptance tests
- Report and triage defects; verify fixes
- Collaborate on testability during design and planning
- Maintain test environments and CI test suites

### Goals
- Reduce escaped defects and rework
- Increase confidence in releases via consistent validation
- Improve test automation coverage for critical flows

### Typical Communication
- QA updates in standups and weekly syncs
- Defect reports and test result summaries
- Test plans for major releases

### Interactions with other personas
- Partners with Developers to clarify acceptance criteria and test cases.
- Works with Product Managers to ensure acceptance criteria reflect user needs.
- Coordinates with Support for post-release verification and production issues.

---

## UX Designer (Suggested new persona)

### Role Summary
UX Designers focus on the user experience, designing flows, interactions, and prototypes that meet user needs and product goals.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and accessibility considerations
- Provide design assets and specifications for development
- Validate design decisions with metrics and user feedback

### Goals
- Improve usability and user satisfaction
- Reduce rework due to usability gaps
- Ensure consistent design patterns across the product

### Typical Communication
- Design critiques, handoffs, and demonstrations
- Design documentation and annotated prototypes
- User research summaries and recommendations

### Interactions with other personas
- Works with Product Managers to translate requirements into user-centered designs.
- Partners with Developers to ensure designs are feasible and testable.
- Collaborates with QA to define usability-related test cases.
- Provides Technical Writers with UX context for documentation.

---

## Technical Writer (Suggested new persona)

### Role Summary
Technical Writers create and maintain user-facing and internal documentation, release notes, and process documents to ensure information is accessible and accurate.

### Responsibilities
- Draft release notes, end-user documentation, and runbooks
- Maintain process docs and templates in docs/
- Ensure documentation stays in sync with releases and APIs
- Improve clarity and findability of information (searchable docs)
- Support onboarding materials and internal playbooks

### Goals
- Reduce support load via clear documentation
- Speed up onboarding and knowledge transfer
- Keep living documentation accurate and discoverable

### Typical Communication
- Documentation reviews and approvals
- Requests for information from Product, Dev, and Support
- Publishing and versioning notes for releases

### Interactions with other personas
- Works cross-functionally to gather details from Developers, Product Managers, and Support.
- Partners with Project Managers to schedule documentation deliverables for releases.

---

## Business Analyst (Suggested new persona)

### Role Summary
Business Analysts bridge product goals and implementation by capturing and refining requirements, data needs, and acceptance criteria.

### Responsibilities
- Elicit and document business requirements and workflows
- Translate stakeholder needs into clear user stories and acceptance criteria
- Perform analysis on data, dependencies, and impacts
- Support prioritization with cost/benefit and impact analysis

### Goals
- Reduce ambiguity in requirements
- Ensure traceability from business need to implementation
- Improve cross-team alignment on scope and outcomes

### Typical Communication
- Requirements documents, process flows, data models
- Stakeholder interviews and synthesis reports
- Support for planning and estimation

### Interactions with other personas
- Works with Product Managers and Stakeholders to clarify goals.
- Provides Developers and QA with detailed acceptance criteria and data contracts.

---

## Support / Customer Success (Suggested new persona)

### Role Summary
Support and Customer Success teams own post-release user interactions, feedback collection, and operational readiness.

### Responsibilities
- Triage and escalate customer-reported issues
- Maintain knowledge base and support resources
- Communicate customer impact and feature adoption
- Provide input into prioritization from a customer perspective
- Participate in release readiness and post-release verification

### Goals
- Reduce time-to-resolution for customer issues
- Improve customer satisfaction and adoption metrics
- Feed clear operational feedback into product improvements

### Typical Communication
- Incident tickets, customer feedback digests, and prioritization requests
- Status updates during incidents and major releases
- Post-release reports for Product and Project leads

### Interactions with other personas
- Escalates production issues to Developers and PMs, provides symptom and reproduction details.
- Works with Technical Writers to keep help content current.
- Participates in retrospectives to close the loop on customer-impacting issues.

---

## How these personas are used in exercises & processes
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning or documenting a work item, add the Owner field mapping to one of these personas for clarity.

---
