# Shippo

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

Shippo provides a robust shipping API architecture that helps developers drive efficiency at scale. The Shippo API covers the complete shipping lifecycle from pre-purchase rate shopping across 80+ carriers to label generation, package tracking, and returns management. SDKs are available for Python, JavaScript, PHP, Java, Ruby, and Node.js.

**Areas:** E-Commerce · Labels · Logistics · Returns · Shipping · Tracking

## Shippo on APIs.io

Everything profiled for Shippo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/shippo/](https://apis.io/providers/shippo/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Shippo Addresses API](https://apis.io/apis/shippo/shippo-addresses-api/) — Validate and manage shipping addresses
- [Shippo Carrier Accounts API](https://apis.io/apis/shippo/shippo-carrier-accounts-api/) — Manage carrier account integrations
- [Shippo Parcels API](https://apis.io/apis/shippo/shippo-parcels-api/) — Define parcel dimensions and weight
- [Shippo Rates API](https://apis.io/apis/shippo/shippo-rates-api/) — Retrieve shipping rates from carriers
- [Shippo Refunds API](https://apis.io/apis/shippo/shippo-refunds-api/) — Request label refunds
- [Shippo Shipments API](https://apis.io/apis/shippo/shippo-shipments-api/) — Create and manage shipments
- [Shippo Tracking API](https://apis.io/apis/shippo/shippo-tracking-api/) — Track shipments across carriers
- [Shippo Transactions API](https://apis.io/apis/shippo/shippo-transactions-api/) — Purchase shipping labels
- [Shippo Webhooks API](https://apis.io/apis/shippo/shippo-webhooks-api/) — Manage webhook subscriptions

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Shippo Webhooks](https://apis.io/asyncapis/shippo/shippo-webhooks-asyncapi/)

#### Event channels (5)

Individual events and webhooks the provider emits.

- [batch_created](https://apis.io/channels/shippo/batch-created/)
- [batch_purchased](https://apis.io/channels/shippo/batch-purchased/)
- [track_updated](https://apis.io/channels/shippo/track-updated/)
- [transaction_created](https://apis.io/channels/shippo/transaction-created/)
- [transaction_updated](https://apis.io/channels/shippo/transaction-updated/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/shippo/](https://apis.io/graphqls/shippo/shippo-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [shippo](https://apis.io/servers/shippo/shippo/)

#### Agent skills (1)

Agent skills built on the API.

- [shippo-official](https://apis.io/agent-skills/shippo/shippo-official/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Shippo Agentic Access](https://apis.io/agentic-access/shippo/shippo-agentic-access/)

#### JSON Schema (24)

The data models the API reads and writes.

- [Address](https://apis.io/schemas/shippo/shippo-address/)
- [AddressCreateRequest](https://apis.io/schemas/shippo/shippo-addresscreaterequest/)
- [AddressPaginatedList](https://apis.io/schemas/shippo/shippo-addresspaginatedlist/)
- [CarrierAccount](https://apis.io/schemas/shippo/shippo-carrieraccount/)
- [CarrierAccountCreateRequest](https://apis.io/schemas/shippo/shippo-carrieraccountcreaterequest/)
- [CarrierAccountPaginatedList](https://apis.io/schemas/shippo/shippo-carrieraccountpaginatedlist/)
- [Parcel](https://apis.io/schemas/shippo/shippo-parcel/)
- [ParcelCreateRequest](https://apis.io/schemas/shippo/shippo-parcelcreaterequest/)
- [ParcelPaginatedList](https://apis.io/schemas/shippo/shippo-parcelpaginatedlist/)
- [Rate](https://apis.io/schemas/shippo/shippo-rate/)
- [RatePaginatedList](https://apis.io/schemas/shippo/shippo-ratepaginatedlist/)
- [Refund](https://apis.io/schemas/shippo/shippo-refund/)
- [RefundCreateRequest](https://apis.io/schemas/shippo/shippo-refundcreaterequest/)
- [RefundPaginatedList](https://apis.io/schemas/shippo/shippo-refundpaginatedlist/)
- [Shippo Shipment](https://apis.io/schemas/shippo/shippo-shipment/)
- [ShipmentCreateRequest](https://apis.io/schemas/shippo/shippo-shipmentcreaterequest/)
- [ShipmentPaginatedList](https://apis.io/schemas/shippo/shippo-shipmentpaginatedlist/)
- [TrackingStatus](https://apis.io/schemas/shippo/shippo-trackingstatus/)
- [TrackingWebhookRequest](https://apis.io/schemas/shippo/shippo-trackingwebhookrequest/)
- [Shippo Transaction](https://apis.io/schemas/shippo/shippo-transaction/)
- [TransactionCreateRequest](https://apis.io/schemas/shippo/shippo-transactioncreaterequest/)
- [TransactionPaginatedList](https://apis.io/schemas/shippo/shippo-transactionpaginatedlist/)
- [Webhook](https://apis.io/schemas/shippo/shippo-webhook/)
- [WebhookCreateRequest](https://apis.io/schemas/shippo/shippo-webhookcreaterequest/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Shippo Shipment Structure](https://apis.io/json-structure/shippo/shippo-shipment-structure/)
- [Shippo Structure](https://apis.io/json-structure/shippo/shippo-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Shippo Context](https://apis.io/jsonld/shippo/shippo-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Shippo API Vocabulary](https://apis.io/vocabularies/shippo/shippo-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Shippo Create Shipment Example](https://apis.io/examples/shippo/shippo-create-shipment-example/)
- [Shippo Purchase Label Example](https://apis.io/examples/shippo/shippo-purchase-label-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [Shippo API](https://apis.io/collections/shippo/open-shippo/)
- [Shippo Addresses API](https://apis.io/collections/shippo/open-shippo-addresses-api/)
- [Shippo Addresses Carrier Accounts API](https://apis.io/collections/shippo/open-shippo-carrier-accounts-api/)
- [Shippo Addresses Parcels API](https://apis.io/collections/shippo/open-shippo-parcels-api/)
- [Shippo Addresses Rates API](https://apis.io/collections/shippo/open-shippo-rates-api/)
- [Shippo Addresses Refunds API](https://apis.io/collections/shippo/open-shippo-refunds-api/)
- [Shippo Addresses Shipments API](https://apis.io/collections/shippo/open-shippo-shipments-api/)
- [Shippo Addresses Tracking API](https://apis.io/collections/shippo/open-shippo-tracking-api/)
- [Shippo Addresses Transactions API](https://apis.io/collections/shippo/open-shippo-transactions-api/)
- [Shippo Addresses Webhooks API](https://apis.io/collections/shippo/open-shippo-webhooks-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Shippo — asyncapi rules](https://apis.io/rules/shippo/shippo-asyncapi-spectral-rules/)
- [Shippo — jsonschema rules](https://apis.io/rules/shippo/shippo-jsonschema-spectral-rules/)
- [Shippo API Rules](https://apis.io/rules/shippo/shippo-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Shippo Authentication](https://apis.io/security/shippo/shippo-authentication/)
- [Shippo Domain Security](https://apis.io/security/shippo/shippo-domain-security/)
- [Shippo Trust Center](https://apis.io/security/shippo/shippo-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Shippo Plans Pricing](https://apis.io/plans/shippo/shippo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Shippo Rate Limits](https://apis.io/rate-limits/shippo/shippo-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Shippo Finops](https://apis.io/finops/shippo/shippo-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://goshippo.com)
- [Documentation](https://docs.goshippo.com/)
- [Getting started](https://support.goshippo.com/hc/en-us/articles/4404415886491-Shippo-API-Quick-Start-Guide)
- [API reference](https://docs.goshippo.com/shippoapi/public-api)
- [Pricing](https://goshippo.com/pricing/api)
- [GitHub](https://github.com/goshippo)

## API Evangelist rating

**Kin Score 48.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.7 |
| Contract quality | 71.5 |
| Contract governance | 27.3 |
| Operational transparency | 10.5 |
| Developer ergonomics | 73.1 |
| Access clarity | 23.7 |

**Agent readiness 34.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/shippo/](https://apis.io/providers/shippo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Shippo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/shippo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
