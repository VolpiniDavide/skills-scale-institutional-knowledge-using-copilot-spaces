# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- **QA Engineer sign-off** — quality gate checklist completed
- **UX/UI Designer sign-off** — visual and interaction acceptance confirmed
- **Technical Writer sign-off** — release notes drafted and documentation published/ready
- **Support Lead readiness review** — support team briefed on changes, known issues, and workarounds
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] QA Engineer sign-off received
- [ ] UX/UI Designer sign-off received (for user-facing changes)
- [ ] Release notes reviewed and approved by Technical Writer
- [ ] Support Lead briefed; support runbook/FAQ updated if needed
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Documentation links: *(add links to updated user guides, API docs, or release notes)*
- Support contact / escalation path:
