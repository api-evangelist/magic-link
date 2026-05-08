# Magic (magic-link)

Magic is an embedded-wallet and authentication platform offering passwordless login (magic links, OAuth, WebAuthn, SMS) plus white-label Embedded Wallets and Server Wallets. Primary surface is the Magic SDK; an Admin REST API exists for user lookup, token validation, and metadata.

Magic exposes API reference docs at https://magic.link/docs but no stable public OpenAPI download URL. Honest skip: SDK-first surface; the Admin REST API is the limited HTTP surface.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/magic-link/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=magic-link-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Magic Admin API** - REST API for backend integrations: validate Magic-issued DID tokens, fetch user metadata, log out users, and manage white-label policies.
- **Magic Server Wallets API** - REST API to provision server-managed wallets and sign transactions in backend services.

## Tags
 - Web3, Wallets, Authentication, Embedded Wallets, MPC

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://magic.link/)
- [Plans](plans/magic-link-plans-pricing.yml)
- [RateLimits](rate-limits/magic-link-rate-limits.yml)
- [FinOps](finops/magic-link-finops.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
