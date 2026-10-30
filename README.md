# Lattice

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

Lattice is a people management platform used by over 5,000 companies to run performance reviews, track OKRs and goals, collect employee engagement survey data, manage compensation, and handle core HR (HRIS) workflows. The platform exposes two public REST APIs: the Lattice Talent API (v1) for performance, goals, feedback, and review data, and the Lattice HRIS API (v2) for employee records and organizational data. Both APIs use API-key authentication and are documented on the Lattice Developer Hub at developers.lattice.com. Lattice integrates with Slack, Gmail, Microsoft Teams, Salesforce, BambooHR, Okta, and other enterprise tools, and supports SCIM provisioning for identity management.

**Areas:** Human Resources · People Management · Performance Management · OKRs · Goals · Employee Engagement · HRIS · Compensation · Feedback · Surveys

## Lattice on APIs.io

Everything profiled for Lattice is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lattice/](https://apis.io/providers/lattice/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Lattice Competencies API](https://apis.io/apis/lattice/lattice-competencies-api/) — Retrieve competencies
- [Lattice Departments API](https://apis.io/apis/lattice/lattice-departments-api/) — Manage and retrieve department records
- [Lattice Feedbacks API](https://apis.io/apis/lattice/lattice-feedbacks-api/) — Retrieve continuous feedback
- [Lattice Goal Updates API](https://apis.io/apis/lattice/lattice-goal-updates-api/) — Create and retrieve goal progress updates
- [Lattice Goals API](https://apis.io/apis/lattice/lattice-goals-api/) — Create, read, and update goals and OKRs
- [Lattice Me API](https://apis.io/apis/lattice/lattice-me-api/) — Retrieve information about the authenticated user
- [Lattice Review Cycles API](https://apis.io/apis/lattice/lattice-review-cycles-api/) — Manage performance review cycles
- [Lattice Reviewees API](https://apis.io/apis/lattice/lattice-reviewees-api/) — Manage reviewees within a review cycle
- [Lattice Reviews API](https://apis.io/apis/lattice/lattice-reviews-api/) — Create, update, and submit performance reviews (v2)
- [Lattice Tags API](https://apis.io/apis/lattice/lattice-tags-api/) — Retrieve tags used across goals and feedback
- [Lattice Users API](https://apis.io/apis/lattice/lattice-users-api/) — Manage and retrieve user records

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/lattice/](https://apis.io/graphqls/lattice/lattice-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lattice Agentic Access](https://apis.io/agentic-access/lattice/lattice-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Goal](https://apis.io/schemas/lattice/lattice-goal/)
- [ReviewCycle](https://apis.io/schemas/lattice/lattice-review-cycle/)
- [User](https://apis.io/schemas/lattice/lattice-user/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lattice Context](https://apis.io/jsonld/lattice/lattice-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Lattice API Vocabulary](https://apis.io/vocabularies/lattice/lattice-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Lattice Create Draft Review Example](https://apis.io/examples/lattice/lattice-create-draft-review-example/)
- [Lattice Create Goal Example](https://apis.io/examples/lattice/lattice-create-goal-example/)
- [Lattice List Goals Example](https://apis.io/examples/lattice/lattice-list-goals-example/)

#### Collections (8)

Postman and Open Collection request collections.

- [Lattice HRIS Competencies API](https://apis.io/collections/lattice/open-lattice-competencies-api/)
- [Lattice HRIS Competencies Departments API](https://apis.io/collections/lattice/open-lattice-departments-api/)
- [Lattice HRIS Competencies Feedbacks API](https://apis.io/collections/lattice/open-lattice-feedbacks-api/)
- [Lattice HRIS Competencies Goal Updates API](https://apis.io/collections/lattice/open-lattice-goal-updates-api/)
- [Lattice HRIS Competencies Goals API](https://apis.io/collections/lattice/open-lattice-goals-api/)
- [Lattice HRIS Competencies Me API](https://apis.io/collections/lattice/open-lattice-me-api/)
- [Lattice HRIS Competencies Tags API](https://apis.io/collections/lattice/open-lattice-tags-api/)
- [Lattice HRIS Competencies Users API](https://apis.io/collections/lattice/open-lattice-users-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Lattice — jsonschema rules](https://apis.io/rules/lattice/lattice-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Lattice Authentication](https://apis.io/security/lattice/lattice-authentication/)
- [Lattice Domain Security](https://apis.io/security/lattice/lattice-domain-security/)
- [Lattice Trust Center](https://apis.io/security/lattice/lattice-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lattice Plans Pricing](https://apis.io/plans/lattice/lattice-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lattice Rate Limits](https://apis.io/rate-limits/lattice/lattice-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lattice Finops](https://apis.io/finops/lattice/lattice-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://lattice.com)
- [Documentation](https://developers.lattice.com)
- [Pricing](https://lattice.com/pricing)
- [Blog](https://lattice.com/blog)
- [Status](https://status.latticehq.com)

## API Evangelist rating

**Kin Score 35.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 62.2 |
| Contract governance | 23.5 |
| Operational transparency | 15.8 |
| Developer ergonomics | 19.0 |
| Access clarity | 26.3 |

**Agent readiness 19.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.6** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lattice/](https://apis.io/providers/lattice/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lattice: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lattice/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
