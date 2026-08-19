<div align="center">

# Helm Template Baseline

**Incubating Kubernetes delivery baseline for services created from the
`@teo-garcia` application templates**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Helm](https://img.shields.io/badge/Helm-incubating-0F1689?logo=helm&logoColor=white)](https://helm.sh)

Part of the [@teo-garcia/templates](https://github.com/teo-garcia/templates)
ecosystem

</div>

---

## Status

This repository is incubating. It records the intended ownership boundary but
does not yet contain a deployable chart. Planning and open design questions live
in the portfolio [roadmap](https://github.com/teo-garcia/templates/blob/main/ROADMAP.md#helm-baseline).

---

## Intended Scope

| Capability | Contract |
| --- | --- |
| Workload | Deployment using the existing container and shutdown contracts |
| Health | `/health/live` and `/health/ready` probes |
| Networking | Service and configurable Ingress with TLS termination |
| Configuration | ConfigMap and secret-provider wiring |
| Reliability | Resource requirements, autoscaling, and disruption budget |

---

## Non-Goals

- Application-specific business configuration
- Cluster-level operators and controllers
- Abstractions that hide the underlying Kubernetes primitives

---

## Activation Criteria

Scaffolding begins when a real application deployment can validate the chart
contract and its operational defaults.

---

## License

MIT

---

<div align="center">
  <sub>Built by <a href="https://github.com/teo-garcia">teo-garcia</a></sub>
</div>
