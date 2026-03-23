# OctoAcme — Cross-Functional Handoff Checklist

## Purpose
Provide a reusable, lightweight checklist for the key handoff points between cross-functional roles in an OctoAcme project. Use this alongside the phase-specific checklists in the planning, execution, and release docs.

---

## Design → Development Handoff

- [ ] Final design specs linked in the backlog item (e.g., Figma link)
- [ ] Responsive/accessibility requirements documented in design notes
- [ ] Component inventory and reusable assets identified
- [ ] UX/UI Designer available for implementation questions during the sprint
- [ ] Edge-case states covered (empty, error, loading)

---

## Development → QA Handoff

- [ ] PR merged and deployed to staging environment
- [ ] Acceptance criteria reviewed and self-tested by Developer
- [ ] Known limitations or out-of-scope items documented in the PR or ticket
- [ ] Test data / environment setup notes provided to QA Engineer
- [ ] Automated tests passing in CI

---

## QA → Release Handoff (Quality Gate)

- [ ] All test cases executed; results recorded
- [ ] No open critical or high-severity defects (or exceptions documented and accepted by PM)
- [ ] Regression suite passed
- [ ] QA sign-off recorded in the project board or release tracking doc
- [ ] Release notes reviewed by QA for accuracy on known issues

---

## Development/QA → Technical Writer Handoff

- [ ] Feature demo or walkthrough provided to Technical Writer
- [ ] API changes or config changes documented in code (e.g., inline docs, CHANGELOG)
- [ ] Draft release notes reviewed for technical accuracy
- [ ] User guide or help content reviewed by Developer and/or Product Manager
- [ ] Documentation published or scheduled to publish with the release

---

## Release → Support Lead Handoff

- [ ] Support Lead has attended or received a summary of the pre-release demo
- [ ] Known issues and workarounds communicated to Support Lead before go-live
- [ ] Support runbook or FAQ updated with new feature information
- [ ] Escalation path for new-feature incidents confirmed with the development team
- [ ] Support Lead confirms readiness to handle user queries post-launch

---

## Post-Release → Retrospective Input

- [ ] QA Engineer: defect summary and test coverage notes prepared
- [ ] UX/UI Designer: usability feedback or design issues observed
- [ ] Technical Writer: documentation gaps or feedback received
- [ ] Support Lead: post-launch issue patterns and user feedback summary ready

---

> **Tip**: Add this checklist to a GitHub issue or PR comment block at the start of each sprint or release cycle. Assign each section to the relevant role owner.
