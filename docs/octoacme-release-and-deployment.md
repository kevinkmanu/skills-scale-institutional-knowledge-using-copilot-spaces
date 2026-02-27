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
- QA Lead sign-off on test results
- UX/UI Designer sign-off on design/accessibility acceptance criteria
- Operations Lead ops readiness review completed (runbook, rollback plan, monitoring)
- Release notes drafted and reviewed by Customer Success Manager
- Rollback / mitigation plan documented
- Smoke tests prepared and reviewed with QA Lead and Operations Lead

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Operations Lead confirms
- [ ] Backup or snapshot (if applicable) — Operations Lead owns
- [ ] Deploy to staging and run smoke tests — QA Lead + Operations Lead
- [ ] QA Lead final sign-off on staging results
- [ ] Deploy to production (automated pipeline preferred) — Operations Lead leads
- [ ] Run post-deploy verifications — QA Lead + Operations Lead
- [ ] Announce release to stakeholders and support — Project Manager + Customer Success Manager

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
