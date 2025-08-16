# Reference Architecture (CIAM)

## Core flow: SPA → API (Auth Code + PKCE)

- SPA obtains code + PKCE with Authorization Server (custom domain).
- Backend API validates JWT access tokens; uses m2m client creds for privileged calls.
- Adaptive MFA based on risk signals (IP reputation, device, velocity).

## Alternatives

- Native mobile (ASWebAuthenticationSession / AppAuth)
- B2B Orgs with enterprise SSO (SAML/OIDC), per-org roles, custom claims.

## Operational concerns

- Regional tenancy vs global: latency vs data residency
- HA/DR: multi-region auth, token cache, rate limit strategies
- Secrets & keys: rotation, JWKS, mTLS between services
