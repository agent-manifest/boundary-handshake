# Positioning within the Agentic Web

**Boundary Handshake Agent — Agent Manifest Project — Draft v0.1**

---

## Thesis

The Agentic Web is building the mechanics of interoperability.

Boundary Handshake addresses the missing terms of interoperability.

---

## Current stack

The most visible efforts in agent interoperability are resolving how agents discover, connect, and communicate:

- **MCP** — standardized access to tools, data, and external workflows
- **A2A** — open protocol for agent-to-agent communication and interoperability
- **AGNTCY** — discovery, identity, messaging, and observability infrastructure for agent networks

What remains underspecified across these efforts is the explicit, negotiated declaration of limits before interaction begins.

Boundary Handshake enters the stack at that layer.

| Layer | Primary focus | What it defines |
|-------|--------------|-----------------|
| MCP | System access | Standardized access to tools, data, and external workflows |
| A2A | Agent transport | Open protocol for agent-to-agent communication and interoperability |
| AGNTCY | IoA infrastructure | Discovery, identity, messaging, and observability |
| **Boundary Handshake** | **Interaction governance** | **Declaration-first negotiation of the conditions under which interaction is acceptable** |

---

## Formulations

**Standard positioning:**

> Boundary Handshake is not another transport protocol, tool protocol, or agent runtime. It is a declaration-first governance layer for agent interaction.

**Comparative positioning:**

> Where MCP connects agents to systems, and A2A connects agents to agents, Boundary Handshake defines the declared conditions under which those interactions are acceptable.

**Protocol-agnostic positioning:**

> Boundary Handshake is protocol-agnostic. It can operate over A2A, alongside AGNTCY, and adjacent to MCP — because it does not redefine transport, tool access, or observability. It adds a declaration and boundary-negotiation layer before coordination begins.

---

## Relation to each layer

**MCP** — *complements*

MCP governs access to tools and systems. Boundary Handshake governs whether and under what limits that access should happen between agents.

**A2A** — *complements*

A2A provides the transport and interoperability protocol. Boundary Handshake provides the governance precondition — the declared terms before the transport is used.

**AGNTCY** — *extends naturally*

AGNTCY defines identity, discovery, messaging, and observability. Boundary Handshake adds explicit negotiated boundary declaration as a layer within or adjacent to that infrastructure.

**Agent Manifest** — *builds on*

Agent Manifest provides individual self-declaration. Boundary Handshake extends that into the relational layer — where declarations meet, negotiate, and produce shared interaction terms.

---

## Editorial note

The stack comparisons above are conceptual syntheses based on public descriptions of each project, not citations from official documentation. The Agentic Web is a conversation in consolidation, not a finalized standard. Positioning may evolve as these protocols develop.

---

*Hernán Alfredo Capucci — Agent Manifest Project — agent-manifest-spec.org — 2026*
