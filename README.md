# Remitian

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Remitian is a fintech platform providing embedded tax payment infrastructure for tax software providers and accounting firms. Often described as the "Stripe for tax," Remitian offers a developer-friendly API that acts as a unified gateway to multiple tax authorities, enabling automated, jurisdiction-aware payment processing. The platform raised $7M in seed funding in 2026 and enables partners to embed payment initiation, validation, and confirmation directly within their existing platforms, replacing manual government portal logins with automated payment infrastructure.

**Areas:** Tax · Payments · Fintech · Accounting · Webhook · Embedded Payments

## Remitian on APIs.io

Everything profiled for Remitian is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/remitian/](https://apis.io/providers/remitian/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Remitian Accounts API](https://apis.io/apis/remitian/remitian-accounts-api/) — Manage client accounts and their linked bank connections for tax payment processing.
- [Remitian Audit Logs API](https://apis.io/apis/remitian/remitian-audit-logs-api/) — Access bank-grade audit logs that track every payment from initiation to completion for compliance and reconciliation.
- [Remitian Jurisdictions API](https://apis.io/apis/remitian/remitian-jurisdictions-api/) — Retrieve and manage supported tax jurisdictions and their associated payment requirements and routing rules.
- [Remitian Payments API](https://apis.io/apis/remitian/remitian-payments-api/) — Initiate, validate, and confirm tax payments across multiple jurisdictions through a single unified gateway.
- [Remitian Webhooks API](https://apis.io/apis/remitian/remitian-webhooks-api/) — Manage webhook subscriptions for real-time payment status updates and event notifications.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Remitian Tax Payment Events](https://apis.io/asyncapis/remitian/remitian-tax-payment-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/webhook](https://apis.io/channels/remitian/webhook/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Remitian Agentic Access](https://apis.io/agentic-access/remitian/remitian-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Remitian Tax Payment](https://apis.io/schemas/remitian/remitian-payment/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Remitian Payment Structure](https://apis.io/json-structure/remitian/remitian-payment-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Remitian Context](https://apis.io/jsonld/remitian/remitian-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Remitian Vocabulary](https://apis.io/vocabularies/remitian/remitian-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Remitian Initiate Payment Example](https://apis.io/examples/remitian/remitian-initiate-payment-example/)
- [Remitian List Jurisdictions Example](https://apis.io/examples/remitian/remitian-list-jurisdictions-example/)
- [Remitian Validate Payment Example](https://apis.io/examples/remitian/remitian-validate-payment-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Remitian Tax Payment Accounts API](https://apis.io/collections/remitian/open-remitian-accounts-api/)
- [Remitian Tax Payment Accounts Audit Logs API](https://apis.io/collections/remitian/open-remitian-audit-logs-api/)
- [Remitian Tax Payment Accounts Jurisdictions API](https://apis.io/collections/remitian/open-remitian-jurisdictions-api/)
- [Remitian Tax Payment Accounts Payments API](https://apis.io/collections/remitian/open-remitian-payments-api/)
- [Remitian Tax Payment API](https://apis.io/collections/remitian/open-remitian-tax-payment/)
- [Remitian Tax Payment Accounts Webhooks API](https://apis.io/collections/remitian/open-remitian-webhooks-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Remitian — asyncapi rules](https://apis.io/rules/remitian/remitian-asyncapi-spectral-rules/)
- [Remitian — jsonschema rules](https://apis.io/rules/remitian/remitian-jsonschema-spectral-rules/)
- [Remitian API Rules](https://apis.io/rules/remitian/remitian-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Remitian Authentication](https://apis.io/security/remitian/remitian-authentication/)
- [Remitian Domain Security](https://apis.io/security/remitian/remitian-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Remitian Plans Pricing](https://apis.io/plans/remitian/remitian-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Remitian Rate Limits](https://apis.io/rate-limits/remitian/remitian-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Remitian Finops](https://apis.io/finops/remitian/remitian-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://remitian.com)
- [Documentation](https://remitian.com/integrations/integrate-remitian)
- [Blog](https://remitian.com/blog/)

## API Evangelist rating

**Kin Score 29.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 74.1 |
| Contract quality | 62.9 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 19.0 |
| Access clarity | 7.9 |

**Agent readiness 26.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/remitian/](https://apis.io/providers/remitian/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Remitian: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/remitian/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
