# CIAM Platform Comparison

| Capability        | Okta CIC/Auth0 | AWS Cognito | Entra External ID | Keycloak (self-host) |
| ----------------- | -------------- | ----------- | ----------------- | -------------------- |
| Orgs / B2B        | ✔️ (strong)    | ➖          | ✔️                | ✔️ (custom)          |
| Actions/hooks     | ✔️             | ➖          | ➖                | ✔️ (SPIs)            |
| Social IdPs       | ✔️             | ✔️          | ✔️                | ✔️                   |
| Passkeys          | ✔️             | ✔️          | ✔️                | ✔️ (config)          |
| Risk/Adaptive MFA | ✔️             | ➖          | ➖                | 🔧 via extensions    |
| Data residency    | ✔️             | ✔️          | ✔️                | Self-managed         |
| Air-gapped        | Limited        | Limited     | Limited           | ✔️ (possible)        |
| Pricing model     | MAU            | MAU         | MAU               | Infra + ops          |
