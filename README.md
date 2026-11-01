# Tackle.io

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

Tackle.io is the Cloud Marketplace and Co-Sell platform that helps software vendors list, sell, co-sell, and meter through the AWS, Microsoft Azure, and Google Cloud marketplaces. The Tackle developer surface spans nine services: a core Platform API (authentication, webhooks, metering/usage records, products, subscriptions, disbursements, invoices, registrations), a Prospect buyer-signal scoring API, Co-Sell APIs for AWS Partner Central, Microsoft Partner Center, and Google Cloud, Private Offer APIs for the AWS and Microsoft marketplaces, a public Contracts API, and a SCIM 2.0 user-provisioning API. Authentication is OAuth 2.0 client-credentials (machine-to-machine) issuing short-lived JWT bearer tokens gated by fine-grained RBAC permissions.

**Areas:** Company · Cloud · Cloud Marketplace · Co-Sell · AWS Marketplace · Azure Marketplace · Google Cloud Marketplace · Private Offers · Metering · SCIM · Webhook · B2B SaaS

## Tackle.io on APIs.io

Everything profiled for Tackle.io is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tackleio/](https://apis.io/providers/tackleio/)** — or go straight to one of the APIs or properties below.

### APIs (27)

- [Tackle.io Authentication API](https://apis.io/apis/tackleio/tackleio-authentication-api/) — Operations for API Authentication
- [Tackle.io Contracts API](https://apis.io/apis/tackleio/tackleio-contracts-api/) — The Contracts API from Tackle.io — 2 operation(s) for contracts.
- [Tackle.io Currencies API](https://apis.io/apis/tackleio/tackleio-currencies-api/) — Microsoft marketplace currency and conversion helpers.
- [Tackle.io Customers API](https://apis.io/apis/tackleio/tackleio-customers-api/) — Look up customer accounts in Microsoft Partner Center before creating a referral. Use these endpoints to determine `customerProfile.ids` and the…
- [Tackle.io Disbursements API](https://apis.io/apis/tackleio/tackleio-disbursements-api/) — The Disbursements API from Tackle.io — 1 operation(s) for disbursements.
- [Tackle.io Entitlements API](https://apis.io/apis/tackleio/tackleio-entitlements-api/) — Legacy entitlements endpoint - returns flat role objects
- [Tackle.io Groups API](https://apis.io/apis/tackleio/tackleio-groups-api/) — SCIM 2.0 Groups endpoint - returns full Group resources (RFC 7643 §4.2)
- [Tackle.io Invitations API](https://apis.io/apis/tackleio/tackleio-invitations-api/) — Create (test-environment-only), read, update, and list co-sell invitations — AWS-led requests to partner with you on a specific opportunity. Use the update…
- [Tackle.io Invoices API](https://apis.io/apis/tackleio/tackleio-invoices-api/) — The Invoices API from Tackle.io — 1 operation(s) for invoices.
- [Tackle.io Marketplace API](https://apis.io/apis/tackleio/tackleio-marketplace-api/) — AWS Marketplace context endpoints used to assemble offers and amendments.
- [Tackle.io Metering API](https://apis.io/apis/tackleio/tackleio-metering-api/) — The Metering API from Tackle.io — 2 operation(s) for metering.
- [Tackle.io Notifications API](https://apis.io/apis/tackleio/tackleio-notifications-api/) — Buyer instruction notification operations.
- [Tackle.io Opportunities API](https://apis.io/apis/tackleio/tackleio-opportunities-api/) — Create, read, update, and list co-sell opportunities — the partner- originated (Outbound / Partner Referral) and AWS-originated (Inbound / AWS Referral)…
- [Tackle.io Partners API](https://apis.io/apis/tackleio/tackleio-partners-api/) — Look up partner organizations in Microsoft Partner Center. Use the returned `organizationId` when adding a non-Microsoft partner via `inviteContexts`.
- [Tackle.io Private Offer Actions API](https://apis.io/apis/tackleio/tackleio-private-offer-actions-api/) — Private offer lifecycle actions such as archive, cancel, and sync.
- [Tackle.io Private Offers API](https://apis.io/apis/tackleio/tackleio-private-offers-api/) — AWS private-offer lifecycle (create, read, update, cancel, push to marketplace).
- [Tackle.io Products API](https://apis.io/apis/tackleio/tackleio-products-api/) — Microsoft product and plan detail lookup.
- [Tackle.io Referrals API](https://apis.io/apis/tackleio/tackleio-referrals-api/) — Create, read, update, and list events on Microsoft Partner Center co-sell referrals (both outbound and inbound).
- [Tackle.io Registrations API](https://apis.io/apis/tackleio/tackleio-registrations-api/) — Operations for Order Registrations
- [Tackle.io Scores API](https://apis.io/apis/tackleio/tackleio-scores-api/) — Score domains and search scored accounts.
- [Tackle.io Service Provider API](https://apis.io/apis/tackleio/tackleio-service-provider-api/) — Service provider configuration and capabilities
- [Tackle.io Settings API](https://apis.io/apis/tackleio/tackleio-settings-api/) — Vendor-level reference data, including the picklist endpoint that supplies the acceptable values for opportunity fields.
- [Tackle.io Solutions API](https://apis.io/apis/tackleio/tackleio-solutions-api/) — List the co-sell solutions registered with AWS Partner Central for your account. Solution identifiers are referenced by `solutions` on opportunities.
- [Tackle.io Subscriptions API](https://apis.io/apis/tackleio/tackleio-subscriptions-api/) — Operations for Subscriptions
- [Tackle.io Users API](https://apis.io/apis/tackleio/tackleio-users-api/) — User management operations
- [Tackle.io Version API](https://apis.io/apis/tackleio/tackleio-version-api/) — Operations for API Versions
- [Tackle.io Webhooks API](https://apis.io/apis/tackleio/tackleio-webhooks-api/) — Operations for Webhooks

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Tackleio Webhooks](https://apis.io/asyncapis/tackleio/tackleio-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Tackle API MCP Server](https://apis.io/servers/tackleio/tackle-api-mcp-server/)

#### Collections (28)

Postman and Open Collection request collections.

- [Tackle Public Contracts Authentication API](https://apis.io/collections/tackleio/open-tackleio-authentication-api/)
- [Tackle Public Authentication Contracts API](https://apis.io/collections/tackleio/open-tackleio-contracts-api/)
- [Tackle Public Contracts Authentication Currencies API](https://apis.io/collections/tackleio/open-tackleio-currencies-api/)
- [Tackle Public Contracts Authentication Customers API](https://apis.io/collections/tackleio/open-tackleio-customers-api/)
- [Tackle Public Contracts Authentication Disbursements API](https://apis.io/collections/tackleio/open-tackleio-disbursements-api/)
- [Tackle Public Contracts Authentication Entitlements API](https://apis.io/collections/tackleio/open-tackleio-entitlements-api/)
- [Tackle Public Contracts Authentication Groups API](https://apis.io/collections/tackleio/open-tackleio-groups-api/)
- [Tackle Public Contracts Authentication Invitations API](https://apis.io/collections/tackleio/open-tackleio-invitations-api/)
- [Tackle Public Contracts Authentication Invoices API](https://apis.io/collections/tackleio/open-tackleio-invoices-api/)
- [Tackle Public Contracts Authentication Marketplace API](https://apis.io/collections/tackleio/open-tackleio-marketplace-api/)
- [Tackle Public Contracts Authentication Metering API](https://apis.io/collections/tackleio/open-tackleio-metering-api/)
- [Tackle Public Contracts Authentication Notifications API](https://apis.io/collections/tackleio/open-tackleio-notifications-api/)
- [Tackle Public Contracts Authentication Opportunities API](https://apis.io/collections/tackleio/open-tackleio-opportunities-api/)
- [Tackle Public Contracts Authentication Partners API](https://apis.io/collections/tackleio/open-tackleio-partners-api/)
- [Tackle Public Contracts Authentication Private Offer Actions API](https://apis.io/collections/tackleio/open-tackleio-private-offer-actions-api/)
- [Tackle Public Contracts Authentication Private Offers API](https://apis.io/collections/tackleio/open-tackleio-private-offers-api/)
- [Tackle Public Contracts Authentication Products API](https://apis.io/collections/tackleio/open-tackleio-products-api/)
- [Tackle Contracts Authentication public API](https://apis.io/collections/tackleio/open-tackleio-public-api/)
- [Tackle Public Contracts Authentication Referrals API](https://apis.io/collections/tackleio/open-tackleio-referrals-api/)
- [Tackle Public Contracts Authentication Registrations API](https://apis.io/collections/tackleio/open-tackleio-registrations-api/)
- [Tackle Public Contracts Authentication Scores API](https://apis.io/collections/tackleio/open-tackleio-scores-api/)
- [Tackle Public Contracts Authentication Service Provider API](https://apis.io/collections/tackleio/open-tackleio-service-provider-api/)
- [Tackle Public Contracts Authentication Settings API](https://apis.io/collections/tackleio/open-tackleio-settings-api/)
- [Tackle Public Contracts Authentication Solutions API](https://apis.io/collections/tackleio/open-tackleio-solutions-api/)
- [Tackle Public Contracts Authentication Subscriptions API](https://apis.io/collections/tackleio/open-tackleio-subscriptions-api/)
- …and 3 more published on APIs.io

#### Overlays (9)

OpenAPI overlays, including conversational phrasing for each operation.

- [Tackleio Contracts Overlay](https://apis.io/overlays/tackleio/tackleio-contracts-overlay/)
- [Tackleio Cosell Aws Overlay](https://apis.io/overlays/tackleio/tackleio-cosell-aws-overlay/)
- [Tackleio Cosell Gcp Overlay](https://apis.io/overlays/tackleio/tackleio-cosell-gcp-overlay/)
- [Tackleio Cosell Msft Overlay](https://apis.io/overlays/tackleio/tackleio-cosell-msft-overlay/)
- [Tackleio Offers Aws Overlay](https://apis.io/overlays/tackleio/tackleio-offers-aws-overlay/)
- [Tackleio Offers Msft Overlay](https://apis.io/overlays/tackleio/tackleio-offers-msft-overlay/)
- [Tackleio Platform Overlay](https://apis.io/overlays/tackleio/tackleio-platform-overlay/)
- [Tackleio Prospect Overlay](https://apis.io/overlays/tackleio/tackleio-prospect-overlay/)
- [Tackleio Scim Overlay](https://apis.io/overlays/tackleio/tackleio-scim-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Tackleio Authentication](https://apis.io/security/tackleio/tackleio-authentication/)
- [Tackleio Domain Security](https://apis.io/security/tackleio/tackleio-domain-security/)
- [Tackleio Trust Center](https://apis.io/security/tackleio/tackleio-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Tackleio Scopes](https://apis.io/scopes/tackleio/tackleio-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://tackle.io)
- [Documentation](https://developers.tackle.io/docs/getting-started)
- [Getting started](https://developers.tackle.io/docs/getting-started)
- [API reference](https://developers.tackle.io/reference)
- [Support](https://help.tackle.io/)
- [Blog](https://tackle.io/resources-category/blogs/)
- [Terms of service](https://tackle.io/terms-conditions/)
- [Privacy policy](https://tackle.io/privacy-policy-tackle-platform/)
- [Status](https://status.tackle.io)

## API Evangelist rating

**Kin Score 57.1** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 64.8 |
| Contract governance | 4.5 |
| Operational transparency | 47.4 |
| Developer ergonomics | 50.6 |
| Access clarity | 36.8 |

**Agent readiness 46.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 39.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tackleio/](https://apis.io/providers/tackleio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Tackle.io: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tackleio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
