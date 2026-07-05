![Status](https://img.shields.io/badge/status-draft-1a1917?style=flat-square)
![Version](https://img.shields.io/badge/version-0.1-1a1917?style=flat-square)
![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey?style=flat-square)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18894794.svg)](https://doi.org/10.5281/zenodo.18894794)

# Boundary Handshake

**A Manifesto for Declaration-First Agent Interoperability**

*Agent Manifest Project — Draft v0.1 — 2026*

> **Status:** Draft v0.1 — conceptual framework, not runtime infrastructure.

-----

> Agents should not coordinate actions before declaring the boundaries under which they are willing to interact.

-----

## What this is

Boundary Handshake Agent is a conceptual framework introducing a **declaration-first governance layer** for agent interaction.

It proposes that before two agents coordinate, they should establish — through structured declaration — the identity, limits, autonomy, and termination conditions governing that interaction.

The output of this process is an **Interaction Manifest**: a structured declaration of the conditions under which two agents agree to interact.

-----

## Why it matters

The emerging agent ecosystem has made significant progress on *how* agents connect:

- **MCP** — standardized access to tools, data, and external systems
- **A2A** — open protocol for agent-to-agent communication and interoperability
- **AGNTCY** — discovery, identity, messaging, and observability infrastructure

What remains underspecified is *under what declared conditions* those interactions should begin.

Boundary Handshake addresses that gap.

-----

## Core concept

Three layers form the framework:

|Layer|Name                    |Function                                                                             |
|-----|------------------------|-------------------------------------------------------------------------------------|
|1    |Agent Manifest          |Self-declaration — what an agent declares about itself                               |
|2    |Interaction Manifest    |Relational declaration — what two agents accept about each other in order to interact|
|3    |Boundary Handshake Agent|Interaction establishment — the mechanism that attempts to bridge the two            |

-----

## Documents

- [`docs/manifesto.md`](docs/manifesto.md) — Full manifesto
- [`docs/conceptual-architecture.md`](docs/conceptual-architecture.md) — Framework architecture and layer definitions
- [`docs/key-citations.md`](docs/key-citations.md) — Five quotable formulations from the manifesto
- [`docs/positioning-agentic-web.md`](docs/positioning-agentic-web.md) — Relationship to MCP, A2A, AGNTCY, and the Agentic Web

## Relationship to Agent Manifest

This repository extends the [Agent Manifest specification](https://agent-manifest-spec.org) into the relational layer.

Agent Manifest defines what an individual agent declares about itself.  
Boundary Handshake defines what two agents must declare to each other before interacting.

-----

## Status

Draft v0.1 — conceptual framework and manifesto.  
Future work: Interaction Manifest schema, compatibility validator, interoperability registry.

-----

## License

[CC BY 4.0](LICENSE) — Hernán Alfredo Capucci, Agent Manifest Project, 2026

## Citation

See [`CITATION.cff`](CITATION.cff) for academic citation format.

---

**Part of the [Agent Manifest](https://agent-manifest-spec.org) ecosystem**

[Spec](https://github.com/agent-manifest/agent-manifest) ·
[Registry](https://github.com/agent-manifest/agent-manifest-registry) ·
[Dataset](https://github.com/agent-manifest/agent-manifest-dataset) ·
[Ambassador](https://github.com/agent-manifest/agent-manifest-ambassador) ·
[Diplomat](https://github.com/agent-manifest/agent-manifest-diplomat) ·
[Boundary Handshake](https://github.com/agent-manifest/boundary-handshake) ·
[∈ Principle](https://github.com/agent-manifest/e-principle)

CC BY 4.0 · Hernán Alfredo Capucci · Agent Manifest Project
