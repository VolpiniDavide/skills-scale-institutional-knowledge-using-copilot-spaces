# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- **QA Engineer signs off** on each release via a quality gate checklist (see `octoacme-cross-functional-handoff-checklist.md`)
- **UX/UI Designer reviews** implementation against design specs before QA sign-off

## Design Handoff
- UX/UI Designer provides final design specs (e.g., Figma links) in the relevant backlog items before development starts
- Developers flag any implementation deviations to the UX/UI Designer during PR review
- A design review checkpoint is held before the feature enters the QA column

## Documentation & Knowledge Handoff
- Technical Writer attends sprint demos to capture feature context
- Draft documentation is reviewed by Developers and Product Manager during sprint close
- Docs must be merged/published before the release is announced

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] UX/UI Designer completing design reviews before features enter QA
- [ ] QA Engineer tracking defects and quality gate status
- [ ] Technical Writer keeping documentation drafts up to date with sprint progress
- [ ] Support Lead receiving sprint demo summaries or release preview notes
