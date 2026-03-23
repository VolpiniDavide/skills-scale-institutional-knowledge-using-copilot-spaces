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

## UX/UI Designer

### Role Summary
UX/UI Designers are responsible for crafting intuitive, user-centred experiences and ensuring design intent is reflected throughout the product. They bridge user research and implementation.

### Responsibilities
- Collaborate with the Product Manager to gather and refine user requirements
- Create wireframes, prototypes, and high-fidelity visual designs
- Conduct or support usability testing and incorporate feedback
- Work with Developers to verify design intent is preserved during implementation
- Maintain a design system and shared asset library

### Goals
- Deliver clear, consistent, and accessible user experiences
- Reduce rework by aligning design and development early
- Keep the product vision and end-user needs in sync

### Typical Communication
- Design reviews and prototype walkthroughs with Product and Dev team
- Handoff notes in design tooling (e.g., Figma annotations)
- Participation in sprint planning and backlog refinement to size design work

### Interactions with Other Roles
| Role | How they interact |
|---|---|
| Product Manager | Translate product vision into user flows and mockups |
| Developers | Provide design specs; review implementation for fidelity |
| QA Engineer | Share acceptance criteria related to visual and interaction quality |
| Technical Writer | Align on terminology, labelling, and in-product microcopy |

---

## QA Engineer

### Role Summary
QA Engineers own the definition and execution of testing strategies to ensure product quality across the full release cycle.

### Responsibilities
- Develop and maintain test plans, test cases (manual and automated), and regression suites
- Report and track defects; verify bug fixes before sign-off
- Define and enforce quality gates for release readiness
- Provide early feedback on requirements and acceptance criteria during planning
- Contribute to CI pipeline health (test automation, coverage reporting)

### Goals
- Prevent defects from reaching production
- Ensure consistent quality standards across all releases
- Reduce manual testing effort through automation over time

### Typical Communication
- QA status updates in sprint reviews and weekly syncs
- Defect reports linked to project board items
- Release sign-off document or checklist sign-off before each deployment

### Interactions with Other Roles
| Role | How they interact |
|---|---|
| Developers | Joint triage of defects; review PRs for testability |
| Product Manager | Clarify acceptance criteria; confirm scope of testing |
| Project Manager | Report quality risks; flag blockers to release |
| UX/UI Designer | Validate that UI implementation matches design specs |
| Support Lead | Receive known-issue lists; share regression notes post-release |

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation that helps teams and end-users understand, adopt, and support project deliverables.

### Responsibilities
- Author and maintain API docs, user guides, onboarding materials, and release notes
- Collaborate with Developers and Product Managers to gather accurate technical information
- Ensure documentation is reviewed, versioned, and published before each release
- Maintain consistency in terminology and style across all docs
- Flag documentation debt and gaps as backlog items

### Goals
- Ensure every release is accompanied by accurate, audience-appropriate documentation
- Reduce support load by providing clear self-service materials
- Maintain a single source of truth for product and process knowledge

### Typical Communication
- Review cycles with Developers and Product Manager during sprint close
- Coordination with Support Lead on FAQs and known issues post-launch
- Attendance at sprint demos to capture feature context firsthand

### Interactions with Other Roles
| Role | How they interact |
|---|---|
| Developers | Review code, APIs, and configs for documentation accuracy |
| Product Manager | Align on messaging and feature scope for user-facing docs |
| QA Engineer | Incorporate known issues and workarounds into release notes |
| Support Lead | Translate escalated questions into documentation improvements |
| UX/UI Designer | Align microcopy and terminology with UI labels |

---

## Support Lead

### Role Summary
The Support Lead acts as the bridge between technical teams and end-users, managing escalations, synthesising user feedback, and feeding real-world learnings back into the improvement cycle.

### Responsibilities
- Monitor support channels for incoming issues, feature requests, and feedback
- Triage and coordinate incident resolution with Developers and QA
- Maintain a knowledge base of known issues and workarounds
- Provide input to retrospectives based on patterns in user feedback
- Validate that release communications and documentation are sufficient for support readiness

### Goals
- Minimise user impact from production issues
- Reduce repeat escalations through documentation and product improvements
- Close the feedback loop between users and the product team

### Typical Communication
- Support readiness review before each release
- Regular feedback summaries shared with Product Manager and Project Manager
- Retrospective participation to surface systemic issues

### Interactions with Other Roles
| Role | How they interact |
|---|---|
| Developers | Escalate production incidents for triage and fix |
| Product Manager | Surface user pain points and feature feedback for backlog |
| QA Engineer | Share recurring defects and edge cases for test coverage |
| Technical Writer | Identify documentation gaps causing support tickets |
| Project Manager | Report support SLA risks and escalation patterns |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See `octoacme-cross-functional-handoff-checklist.md` for a practical checklist that operationalises handoffs between these roles.

