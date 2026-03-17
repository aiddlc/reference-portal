# AIDDLC Reference Portal

The official reference implementation of the AIDDLC Standard.

**Status: In Development**
The portal is currently being built. This repository will contain the
complete source once it reaches public beta.

---

## What the portal will be

A working, self-hostable web application that guides teams through
the complete AIDDLC lifecycle:

- **Phase navigator** — step-by-step guidance through all 7 Engineering
  Track phases and 4 Product Track phases
- **Artifact templates** — pre-built templates for every required artifact
  (Intelligence Brief, Compliance Matrix, ADRs, Decision Log, etc.)
- **Gate checklists** — interactive gate review checklists with sign-off
  tracking per role
- **Context Layer** — persistent, append-only project knowledge base
  that accumulates across all phases
- **AI Supervisor interface** — context loading, session management,
  and drift detection tooling
- **Compliance Evidence Package** — one-click export of all artifacts
  formatted for regulatory submission
- **Decision Log** — auto-generated audit trail of all material decisions

## Reference implementation

The portal is being built and validated on
[Club Health OS](https://10qbit.ai) — a regulated healthcare SaaS
platform operating across 21+ clinics in the UK. Everything in the
portal has been tested in a live regulated-industry environment.

## Hosted version

A managed hosted version will be available at `aiddlc.ai/portal`
once the portal reaches public beta.

To be notified when the portal is available:
→ [standard@aiddlc.ai](mailto:standard@aiddlc.ai)
→ Watch this repository

## Self-hosting

Self-hosting documentation will be published alongside the first
public release. The portal will be deployable on any Node.js host,
including DigitalOcean, Railway, Render, and Vercel.

## Licence

Business Source Licence 1.1 (BSL 1.1).
Converts to Apache 2.0 on 1 January 2030.

The hosted version at `aiddlc.ai/portal` is operated by
10QBIT Technologies.

---

Maintained by [10QBIT Technologies](https://10qbit.ai) · [aiddlc.ai](https://aiddlc.ai)
