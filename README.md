# CIAM Program Blueprint

A practical, vendor-agnostic blueprint for **Consumer Identity & Access Management (CIAM)** programs.
Use it to frame strategy, make platform decisions, and ship secure, low-friction auth at scale.

## Who this is for

- Product & growth teams (conversion/retention)
- Security/IAM engineers (risk, fraud, MFA, bot mitigation)
- Data privacy/compliance leaders (consent, DSRs, retention)

## What’s inside

- **Reference architectures:** SPA→API (Auth Code + PKCE), native mobile, B2B Orgs with SSO
- **User journeys:** sign up, progressive profiling, passwordless, account recovery, deactivation
- **Risk & fraud:** adaptive MFA, device signals, bot protection, velocity/rate limits
- **Data & consent:** data model, PII minimization, consent capture, retention, DSR playbooks
- **Migration:** bulk + just-in-time (JIT), hashing strategies, staged rollouts & A/B
- **Tenancy:** organizations, roles, custom claims, per-org config
- **Governance:** SLAs/SLOs, auditability, incident runbooks

## Quick start

1. Read `docs/01-vision-and-principles.md` and align on north star.
2. Pick a target ref-arch under `reference-architectures/`.
3. Use `decision-matrix/ciam-platform-comparison.md` to select a platform.
4. Draft your rollout using `docs/07-migration-playbook.md`.

## Decision matrix (example axes)

- **Capabilities:** Orgs/M2M, Actions/hooks/extensibility, social IdPs, passkeys
- **Risk/Fraud:** adaptive MFA, bot mitigation, anomaly detection
- **Ops:** regionality, air-gapped/on-prem paths, HA/DR, support, roadmap fit
- **Cost:** MAU pricing, spikes, non-prod environments
- **Compliance:** data residency, consent tooling, audit logs, export

## Status

This blueprint is a living doc. Use Issues/PRs to propose updates.

## License

MIT
