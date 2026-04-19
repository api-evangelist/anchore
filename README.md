# Anchore

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
