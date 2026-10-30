# npm

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

npm is the world's largest software registry, hosting over two million JavaScript packages for the Node.js ecosystem. Their developer platform provides APIs for searching and retrieving package metadata, managing access tokens, subscribing to registry event webhooks, and publishing packages with supply chain provenance verification.

**Areas:** Packages · JavaScript · Node.js · Package Management · Registry · Security · Developer Tools · npm

## npm on APIs.io

Everything profiled for npm is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/npm/](https://apis.io/providers/npm/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [npm Registry API](https://apis.io/apis/npm/registry/) — The npm Registry API provides programmatic access to the npm package registry, the largest software registry in the world hosting over two million…
- [npm Hooks API](https://apis.io/apis/npm/hooks/) — The npm Hooks API allows developers to subscribe to notifications about changes in the npm registry. Hooks send HTTP POST payloads to a configured URI…
- [npm CLI](https://apis.io/apis/npm/cli/) — The npm CLI is the official command-line interface for the npm package manager, providing developers with tools to install, publish, and manage JavaScript…
- [npm Provenance](https://apis.io/apis/npm/provenance/) — npm Provenance provides supply chain security for JavaScript packages by establishing a verifiable link between a published package and its source code…
- [npm Downloads API](https://apis.io/apis/npm/npm-downloads-api/) — Package tarball downloads.
- [npm OIDC API](https://apis.io/apis/npm/npm-oidc-api/) — OpenID Connect token exchange for trusted publishing. Exchange OIDC identity tokens from supported CI/CD providers for short-lived npm registry access tokens.
- [npm Packages API](https://apis.io/apis/npm/npm-packages-api/) — Package metadata retrieval, including full packuments and version-specific documents.
- [npm Search API](https://apis.io/apis/npm/npm-search-api/) — Full-text search across the npm registry with weighted scoring.
- [npm Tokens API](https://apis.io/apis/npm/npm-tokens-api/) — Manage npm access tokens for authentication. Create, list, and delete tokens with customizable permissions and restrictions.
- [npm Trusted Publishers API](https://apis.io/apis/npm/npm-trusted-publishers-api/) — Configure trusted publisher settings for packages to enable OIDC token exchange from CI/CD providers without long-lived npm tokens.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [npm Hooks Events](https://apis.io/asyncapis/npm/npm-hooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/webhook](https://apis.io/channels/npm/webhook/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Npm Agentic Access](https://apis.io/agentic-access/npm/npm-agentic-access/)

#### JSON Schema (19)

The data models the API reads and writes.

- [Distribution](https://apis.io/schemas/npm/npm-distribution/)
- [Error](https://apis.io/schemas/npm/npm-error/)
- [Hook](https://apis.io/schemas/npm/npm-hook/)
- [npm Hook Event Payload](https://apis.io/schemas/npm/npm-hook-event/)
- [HookCreateRequest](https://apis.io/schemas/npm/npm-hookcreaterequest/)
- [HookUpdateRequest](https://apis.io/schemas/npm/npm-hookupdaterequest/)
- [npm Package Document](https://apis.io/schemas/npm/npm-package/)
- [PackageDocument](https://apis.io/schemas/npm/npm-packagedocument/)
- [PackageVersion](https://apis.io/schemas/npm/npm-packageversion/)
- [Person](https://apis.io/schemas/npm/npm-person/)
- [RegistryMetadata](https://apis.io/schemas/npm/npm-registrymetadata/)
- [Repository](https://apis.io/schemas/npm/npm-repository/)
- [SearchResultItem](https://apis.io/schemas/npm/npm-searchresultitem/)
- [SearchResults](https://apis.io/schemas/npm/npm-searchresults/)
- [Token](https://apis.io/schemas/npm/npm-token/)
- [TokenCreateRequest](https://apis.io/schemas/npm/npm-tokencreaterequest/)
- [TokenWithValue](https://apis.io/schemas/npm/npm-tokenwithvalue/)
- [TrustedPublisher](https://apis.io/schemas/npm/npm-trustedpublisher/)
- [TrustedPublisherRequest](https://apis.io/schemas/npm/npm-trustedpublisherrequest/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Npm Structure](https://apis.io/json-structure/npm/npm-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Npm Context](https://apis.io/jsonld/npm/npm-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [npm Domain Vocabulary](https://apis.io/vocabularies/npm/npm-vocabulary/)

#### Collections (17)

Postman and Open Collection request collections.

- [npm Hooks Downloads API](https://apis.io/collections/npm/open-npm-downloads-api/)
- [npm Downloads Hooks API](https://apis.io/collections/npm/open-npm-hooks-api/)
- [npm Hooks Downloads OIDC API](https://apis.io/collections/npm/open-npm-oidc-api/)
- [npm Hooks Downloads Packages API](https://apis.io/collections/npm/open-npm-packages-api/)
- [npm Public API](https://apis.io/collections/npm/open-npm-public-api/)
- [npm Hooks Downloads Registry API](https://apis.io/collections/npm/open-npm-registry-api/)
- [npm Hooks Downloads Search API](https://apis.io/collections/npm/open-npm-search-api/)
- [npm Hooks Downloads Tokens API](https://apis.io/collections/npm/open-npm-tokens-api/)
- [npm Hooks Downloads Trusted Publishers API](https://apis.io/collections/npm/open-npm-trusted-publishers-api/)
- [npm Hooks Downloads API](https://apis.io/collections/npm/postman-npm-downloads-api/)
- [npm Downloads Hooks API](https://apis.io/collections/npm/postman-npm-hooks-api/)
- [npm Hooks Downloads OIDC API](https://apis.io/collections/npm/postman-npm-oidc-api/)
- [npm Hooks Downloads Packages API](https://apis.io/collections/npm/postman-npm-packages-api/)
- [npm Hooks Downloads Registry API](https://apis.io/collections/npm/postman-npm-registry-api/)
- [npm Hooks Downloads Search API](https://apis.io/collections/npm/postman-npm-search-api/)
- [npm Hooks Downloads Tokens API](https://apis.io/collections/npm/postman-npm-tokens-api/)
- [npm Hooks Downloads Trusted Publishers API](https://apis.io/collections/npm/postman-npm-trusted-publishers-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [npm — asyncapi rules](https://apis.io/rules/npm/npm-asyncapi-spectral-rules/)
- [npm — jsonschema rules](https://apis.io/rules/npm/npm-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Npm Authentication](https://apis.io/security/npm/npm-authentication/)
- [Npm Domain Security](https://apis.io/security/npm/npm-domain-security/)
- [Npm Vulnerability Disclosure](https://apis.io/security/npm/npm-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Npm Plans Pricing](https://apis.io/plans/npm/npm-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Npm Rate Limits](https://apis.io/rate-limits/npm/npm-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Npm Finops](https://apis.io/finops/npm/npm-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.npmjs.com/)
- [Documentation](https://docs.npmjs.com/)
- [Support](https://www.npmjs.com/support)
- [Blog](https://blog.npmjs.org/)
- [Terms of service](https://docs.npmjs.com/policies/terms)
- [Privacy policy](https://docs.npmjs.com/policies/privacy)
- [Status](https://status.npmjs.org/)

## API Evangelist rating

**Kin Score 48.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 68.8 |
| Contract governance | 13.6 |
| Operational transparency | 39.5 |
| Developer ergonomics | 39.3 |
| Access clarity | 42.1 |

**Agent readiness 27.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
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
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/npm/](https://apis.io/providers/npm/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for npm: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/npm/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
