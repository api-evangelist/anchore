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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Anchore is a container and software supply chain security company providing open source and enterprise tools for vulnerability scanning, SBOM generation, policy enforcement, and continuous compliance. Core open source products include Syft (SBOM generator), Grype (vulnerability scanner), and Grant (license scanner).

**URL:** https://raw.githubusercontent.com/api-evangelist/anchore/refs/heads/main/apis.yml

## Tags

Container Security, Containers, SBOM, Software Supply Chain, Vulnerability Scanning

## APIs

| Name | Description |
|------|-------------|
| Anchore Enterprise API | REST API for image analysis, vulnerability scanning, policy evaluation, and SBOM generation |

## Features

- Container image vulnerability scanning (OS and language packages)
- SBOM generation in CycloneDX and SPDX formats (Syft)
- Policy-based compliance enforcement
- Kubernetes admission controller integration
- CI/CD pipeline integration (GitHub Actions, Jenkins, GitLab)
- Registry connectors (Docker Hub, ECR, GCR, ACR, Harbor)
- License scanning and compliance (Grant)
- Grype vulnerability database
- REST API for image analysis, subscriptions, and notifications

## Use Cases

| Use Case |
|----------|
| Shift-left container security scanning in CI/CD pipelines |
| Generate SBOMs for software supply chain transparency |
| Enforce image policies at Kubernetes admission control |
| Track vulnerabilities across container registries |
| License compliance scanning for open source components |
| Continuous compliance monitoring for regulated industries |

## Artifacts

| Type | File |
|------|------|
| OpenAPI | [anchore-enterprise-api.yaml](openapi/anchore-enterprise-api.yaml) |
| JSON Schema | [anchore-image-schema.json](json-schema/anchore-image-schema.json) |
| JSON Schema | [anchore-vulnerability-schema.json](json-schema/anchore-vulnerability-schema.json) |
| JSON Schema | [anchore-sbom-schema.json](json-schema/anchore-sbom-schema.json) |
| JSON Structure | [anchore-image-structure.json](json-structure/anchore-image-structure.json) |
| JSON-LD | [anchore-enterprise-api-context.jsonld](json-ld/anchore-enterprise-api-context.jsonld) |
| Spectral Rules | [anchore-spectral-rules.yml](rules/anchore-spectral-rules.yml) |
| Vocabulary | [anchore-vocabulary.yaml](vocabulary/anchore-vocabulary.yaml) |

## Capabilities

| Capability | Workflows |
|------------|-----------|
| [anchore-container-security](capabilities/anchore-container-security.yaml) | scan-and-report, generate-sbom |

## GitHub Organization

https://github.com/anchore

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
