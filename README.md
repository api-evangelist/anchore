# Anchore

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

Anchore is a container and software supply chain security company providing open source and enterprise tools for vulnerability scanning, SBOM generation, policy enforcement, and continuous compliance. Core open source products include Syft (SBOM generator for container images and filesystems), Grype (vulnerability scanner), and Grant (license scanner). The Anchore Enterprise platform adds policy engines, CI/CD integrations, registry connectors, Kubernetes admission control, and reporting. Anchore supports CycloneDX and SPDX SBOM formats and integrates with Docker, Kubernetes, GitHub Actions, Jenkins, and major cloud registries.

**Areas:** Container Security · Containers · SBOM · Software Supply Chain · Vulnerability Scanning

## Anchore on APIs.io

Everything profiled for Anchore is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/anchore/](https://apis.io/providers/anchore/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Anchore Images API](https://apis.io/apis/anchore/anchore-images-api/) — The Images API from Anchore — 2 operation(s) for images.
- [Anchore Policies API](https://apis.io/apis/anchore/anchore-policies-api/) — The Policies API from Anchore — 2 operation(s) for policies.
- [Anchore Registries API](https://apis.io/apis/anchore/anchore-registries-api/) — The Registries API from Anchore — 1 operation(s) for registries.
- [Anchore SBOM API](https://apis.io/apis/anchore/anchore-sbom-api/) — The SBOM API from Anchore — 1 operation(s) for sbom.
- [Anchore Subscriptions API](https://apis.io/apis/anchore/anchore-subscriptions-api/) — The Subscriptions API from Anchore — 1 operation(s) for subscriptions.
- [Anchore Vulnerabilities API](https://apis.io/apis/anchore/anchore-vulnerabilities-api/) — The Vulnerabilities API from Anchore — 1 operation(s) for vulnerabilities.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (6)

Multi-step workflows that chain operations into a business task.

- [Anchore Analyze Image End to End](https://apis.io/arazzos/anchore/anchore-analyze-image-workflow/)
- [Anchore Create Policy and Evaluate Image](https://apis.io/arazzos/anchore/anchore-create-policy-and-evaluate-workflow/)
- [Anchore Image SBOM and Vulnerability Pull](https://apis.io/arazzos/anchore/anchore-image-sbom-and-vulns-workflow/)
- [Anchore Registry Image Onboarding](https://apis.io/arazzos/anchore/anchore-registry-scan-workflow/)
- [Anchore Rescan Active Image and Gate](https://apis.io/arazzos/anchore/anchore-rescan-active-images-workflow/)
- [Anchore Subscribe on Policy Failure](https://apis.io/arazzos/anchore/anchore-subscribe-on-policy-fail-workflow/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [MCP Server](https://apis.io/servers/anchore/mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Anchore Agentic Access](https://apis.io/agentic-access/anchore/anchore-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Anchore Image](https://apis.io/schemas/anchore/anchore-image/)
- [Anchore SBOM](https://apis.io/schemas/anchore/anchore-sbom/)
- [Anchore Vulnerability](https://apis.io/schemas/anchore/anchore-vulnerability/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Anchore Image Structure](https://apis.io/json-structure/anchore/anchore-image-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Anchore Enterprise Api Context](https://apis.io/jsonld/anchore/anchore-enterprise-api-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Anchore Vocabulary](https://apis.io/vocabularies/anchore/anchore-vocabulary/)

#### Collections (7)

Postman and Open Collection request collections.

- [Anchore Enterprise Images API](https://apis.io/collections/anchore/open-anchore-images-api/)
- [Anchore Enterprise Images Policies API](https://apis.io/collections/anchore/open-anchore-policies-api/)
- [Anchore Enterprise Images Registries API](https://apis.io/collections/anchore/open-anchore-registries-api/)
- [Anchore Enterprise Images SBOM API](https://apis.io/collections/anchore/open-anchore-sbom-api/)
- [Anchore Enterprise Images Subscriptions API](https://apis.io/collections/anchore/open-anchore-subscriptions-api/)
- [Anchore Enterprise Images Vulnerabilities API](https://apis.io/collections/anchore/open-anchore-vulnerabilities-api/)
- [Anchore Enterprise API](https://apis.io/collections/anchore/postman-anchore-enterprise-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Anchore — jsonschema rules](https://apis.io/rules/anchore/anchore-jsonschema-spectral-rules/)
- [Anchore API Rules](https://apis.io/rules/anchore/anchore-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Anchore Authentication](https://apis.io/security/anchore/anchore-authentication/)
- [Anchore Domain Security](https://apis.io/security/anchore/anchore-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Anchore Plans Pricing](https://apis.io/plans/anchore/anchore-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Anchore Rate Limits](https://apis.io/rate-limits/anchore/anchore-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Anchore Finops](https://apis.io/finops/anchore/anchore-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.anchore.com/)
- [Documentation](https://docs.anchore.com/)
- [Getting started](https://docs.anchore.com/current/docs/quickstart/)
- [Pricing](https://anchore.com/pricing/)
- [Support](https://anchore.com/support/)
- [Blog](https://anchore.com/blog/)
- [Terms of service](https://anchore.com/terms-of-service/)
- [Privacy policy](https://anchore.com/privacy-policy/)
- [GitHub](https://github.com/anchore)
- [Status](https://status.anchore.com/)

## API Evangelist rating

**Kin Score 37.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 57.5 |
| Contract governance | 27.3 |
| Operational transparency | 18.4 |
| Developer ergonomics | 34.5 |
| Access clarity | 18.4 |

**Agent readiness 21.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
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

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/anchore/](https://apis.io/providers/anchore/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Anchore: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/anchore/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
