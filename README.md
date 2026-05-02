# Ratify

Ratify is a CNCF Sandbox open-source verification framework for container images and other supply chain artifacts in Kubernetes environments. It enables policy-driven artifact ratification by coordinating any number of pluggable verifiers — signatures, SBOMs, scan results, and attestations — against a given policy, integrating with Kubernetes admission webhooks via the Gatekeeper policy engine.

Ratify is developed by the [ratify-project](https://github.com/ratify-project) GitHub organization (originally a Microsoft open-source project), written in Go, and distributed as a CLI tool, Go library, and Kubernetes admission webhook server. It supports OCI-compliant artifact stores including Azure Container Registry, Amazon ECR, and Docker Hub.

**No public-facing REST API or OpenAPI specification is published.** Ratify exposes an internal HTTP verification API (v2alpha1) consumed by its webhook server.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/ratify/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Artifact Verification, CNCF, Cloud Native, Container Security, Kubernetes, Open Source, Policy Enforcement, Security, Supply Chain

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

No public APIs have been documented at this time. Ratify is consumed via Kubernetes admission webhooks, a CLI, and Go libraries.

## Key Features

- **Pluggable Verifiers** — Signatures (Notation, Cosign), SBOMs, vulnerability scan results, custom attestations
- **Kubernetes-Native** — Admission webhook integration with OPA Gatekeeper
- **OCI Support** — Works with any OCI-compliant registry
- **Policy Engine** — Policy-driven verification decisions
- **CLI Tool** — Standalone verification via the `ratify-cli`
- **CNCF Sandbox** — Vendor-neutral governance under the CNCF

## GitHub Repositories

| Repo | Description |
|---|---|
| [ratify](https://github.com/ratify-project/ratify) | Core verification framework (Go) |
| [ratify-cli](https://github.com/ratify-project/ratify-cli) | Standalone CLI for artifact verification |
| [docker-ratify](https://github.com/ratify-project/docker-ratify) | Docker integration |
| [ratify-verifier-plugin](https://github.com/ratify-project/ratify-verifier-plugin) | Plugin framework for custom verifiers |

## Common Properties

- [Website](https://ratify.dev)
- [Documentation](https://ratify.dev/docs/what-is-ratify)
- [SourceCode](https://github.com/ratify-project/ratify)
- [GitHubOrg](https://github.com/ratify-project)
- [PackageManager](https://artifacthub.io/packages/helm/ratify/ratify)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
