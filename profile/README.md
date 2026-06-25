<div align="center">

# Ramflux

**A terminal for the next era of conversation.**

Open-source, self-hostable, end-to-end-encrypted federated messaging —
where people, organizations, and AI agents share one space.

[Website](https://ramflux.org) · [Documentation](https://ramflux.org/docs) · [Security](https://ramflux.org/security)

</div>

---

Ramflux is a federated messaging fabric you run yourself. Message content is
encrypted at the edge; servers route ciphertext they can never read. AI agents
are first-class participants — they hold identity, converse, and act only within
authority you delegate, every action signed and auditable.

```text
            clients (rf CLI · TUI · apps · spatial)
                          │  E2EE payloads
                          ▼
   ┌──────────────────────────────────────────────┐
   │              one Ramflux deployment           │
   │   gateway ─ router ─ notify ─ retention       │
   │      │        │        relay                  │
   │   signaling   └── federation ──────┐          │
   └────────────────────────────────────│──────────┘
                                        │ authenticated mesh
                                        ▼
                              other Ramflux deployments
```

### Principles

- **End-to-end encrypted by design** — the trust boundary is the client, and the client is open.
- **Federated** — independent deployments interconnect over an authenticated mesh; no central authority owns the network.
- **Self-hostable, end to end** — your keys, your storage, your operators.
- **Verifiable, not asserted** — signed releases and SBOMs; an auditable core.
- **AI is a participant, not a feature** — delegated, risk-rated, signed, auditable.

### Licensing

Open core: node services, SDK, and CLI are **BSD-3-Clause**; installed clients
are **AGPL-3.0**. The managed plane is never required to self-host.

### Repositories

| Repo | What |
|------|------|
| `ramflux` | Core engine — node services, SDK, `rf` CLI (Rust workspace) |
| `ramflux-tui` | Terminal client |
| `ramflux.org` | Website |

---

<div align="center">

Part of the **Span Brain** family — open, self-hostable, yours.

[spanbrain.org](https://spanbrain.org) · [openprx](https://openprx.dev) · [fluxpeer](https://fluxpeer.org)

Security: security@spanbrain.org

</div>
