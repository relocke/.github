<div align="center">

# ReLocke

### Infrastructure for open systems.

Build, deploy, discover, and verify code, contracts, services, and autonomous software—from first commit to production.

[Website](https://relocke.io) · [Platform](https://relocke.io) · [Agentic ABI](https://github.com/relocke/agentic-abi) · [Get involved](https://github.com/relocke/.github/blob/main/CONTRIBUTING.md)

</div>

---

ReLocke is building a shared control plane for software that spans repositories, cloud services, decentralized networks, smart contracts, agents, and machine-readable interfaces.

The goal is larger than deployment automation. We want software to be operable by people and machines, portable across infrastructure, understandable at its boundaries, and verifiable from source to runtime.

## What belongs in the platform

| Capability | What it means |
| --- | --- |
| **Build & deploy** | Reproducible builds, preview environments, immutable releases, rollbacks, domains, logs, and runtime health. |
| **Discover & compose** | A universal registry for services, contracts, packages, agents, APIs, networks, and the capabilities they expose. |
| **Verify & trust** | Source provenance, signed artifacts, deployment attestations, ownership, interface compatibility, and security signals. |
| **Connect ecosystems** | Native support for web applications, conventional APIs, Antelope contracts, decentralized infrastructure, and autonomous software. |
| **Operate together** | Shared projects, environments, policy, secrets, identities, events, observability, and automation. |

## Machine-readable software

ReLocke extends familiar interfaces with the context needed for reliable discovery and operation. For Antelope and EOSIO ecosystems, this includes richer ABI semantics such as:

- contract and token identity;
- icons and human-readable asset metadata;
- capability and interface types;
- action and table semantics;
- source repositories and immutable revision links;
- deployment and network provenance; and
- context that agents can interpret with explicit trust boundaries.

These ideas are not limited to blockchains. The same registry model can describe APIs, services, packages, agents, workflows, and deployment artifacts.

## Principles

- **Open by interface.** Prefer portable schemas and transparent boundaries.
- **Verifiable by default.** Connect what is running to where it came from.
- **Human and machine legible.** Design metadata for both audiences.
- **Composable without capture.** Enable ecosystems without requiring centralized ownership.
- **Secure at every boundary.** Treat repositories, metadata, builds, networks, and external content as untrusted input.
- **Progressive adoption.** Existing applications and Antelope contracts should become richer without breaking compatibility.

## Current work

- [`relocke/agentic-abi`](https://github.com/relocke/agentic-abi) — one versioned specification and LLM skill for creating rich, ReLocke-supported contract ABIs.
- **ReLocke Platform** — the control plane for importing projects, building and deploying software, browsing source, managing environments, and publishing verified interfaces. The initial public foundation is being prepared.
- **Universal Registry** — schemas and services for resolving capabilities, provenance, deployments, and human-facing metadata across ecosystems.

## Build with us

ReLocke is early, and the architecture should be shaped in the open. Read the [contribution guide](https://github.com/relocke/.github/blob/main/CONTRIBUTING.md), propose an interface, document an integration, or help turn a platform primitive into working infrastructure.

If you find a security issue, please follow our [security policy](https://github.com/relocke/.github/blob/main/SECURITY.md) rather than opening a public issue.

---

<div align="center">
<sub>Software should know what it is, where it came from, and how it can work with the world.</sub>
</div>
