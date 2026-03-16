# AIDDLC Reference Portal

[![Standard](https://img.shields.io/badge/Standard-v1.0-0D6E6E?style=flat-square)](https://github.com/aiddlc/standard)
[![Licence](https://img.shields.io/badge/Licence-BSL%201.1-333333?style=flat-square)](LICENCE)
[![Production](https://img.shields.io/badge/Production-Club%20Health%20OS-0D6E6E?style=flat-square)](https://github.com/aiddlc/reference-portal)

The official interactive implementation of the AIDDLC Standard. Provides a navigable, searchable interface to the complete specification, phase-by-phase guidance, artifact templates, and checklist tools.

Hosted at **[aiddlc.ai/portal](https://aiddlc.ai/portal)** — maintained and operated by 10QBIT Technologies.

---

## What it is

The Reference Portal is not documentation. It is an interactive tool that teams use actively during development — loading the relevant phase, working through gate criteria, generating artifact templates, and tracking conformance status.

It implements the AIDDLC Standard v1.0 in full, covering:
- All seven Engineering Track phases with interactive gate checklists
- All four Product Track phases with community development area guidance
- Artifact template library (Intelligence Brief, Compliance Matrix, ADR, and all other required artifacts)
- Context Package assembly and export
- Compliance mapping by regulation (GDPR, MHRA, CQC, GPhC, FCA, HIPAA, ISO 27001, EU AI Act)
- Self-assessment checklist linked to certification criteria

---

## Production use

The Reference Portal runs in production at **Club Health OS** — a regulated physiotherapy clinical management system operating under CQC registration and subject to GPhC oversight for its pharmacy-adjacent functions.

This is not a demo environment. Production use means:
- The portal is used by the engineering team on live development cycles
- Gate criteria and artifact requirements are validated against real regulatory scrutiny
- Compliance mapping has been reviewed against actual CQC inspection requirements
- Issues found in production are fixed in the portal, not papered over

When you use the Reference Portal, you are using tooling that has been exercised in a regulated production context.

---

## Hosted version

The hosted portal at [aiddlc.ai/portal](https://aiddlc.ai/portal) is always current with the latest published version of the AIDDLC Standard. It requires no installation, no account, and no cost for individual use.

---

## Self-hosting

### Prerequisites

- Node.js 18 or later
- npm 9 or later
- A static file server or hosting platform (Vercel, Netlify, Cloudflare Pages, Nginx)

### Installation

```bash
git clone https://github.com/aiddlc/reference-portal.git
cd reference-portal
npm install
```

### Development

```bash
npm run dev
```

The portal will be available at `http://localhost:3000`.

### Production build

```bash
npm run build
```

Output is in `/dist`. Serve as a static site — no server-side runtime is required.

### Environment variables

| Variable | Required | Description |
|---|---|---|
| `AIDDLC_VERSION` | No | Standard version to display (defaults to latest) |
| `AIDDLC_ORG_NAME` | No | Your organisation name for portal personalisation |
| `AIDDLC_BASE_URL` | No | Base URL for self-hosted deployment |

---

## Licence

The Reference Portal is licensed under the **Business Source Licence 1.1 (BSL 1.1)**.

**What this means in practice**:

- **Non-production use**: Free. Use it for evaluation, learning, development, and testing without restriction.
- **Production use**: Requires a licence from 10QBIT Technologies. Contact [licensing@aiddlc.ai](mailto:licensing@aiddlc.ai).
- **Automatic open source**: On **1 January 2030**, the licence automatically converts to the Apache License 2.0. From that date, production use is free for everyone.

**Why BSL 1.1?**

The AIDDLC Standard itself (the specification) is CC BY 4.0 — fully open. The Reference Portal is the commercial implementation that funds the ongoing development and maintenance of the standard. BSL 1.1 allows the open-source community to inspect, learn from, and contribute to the portal code while protecting the investment that makes the standard sustainable.

See [LICENCE](LICENCE) for the full licence text.

---

## Contributing

Contributions to the portal are welcome for:
- Bug fixes
- Accessibility improvements
- Additional artifact templates (open an issue first to align with the standard)
- Compliance mapping corrections

Design changes and new features require an issue discussion before a PR. The portal must accurately implement the standard — changes that diverge from the specification will not be accepted.

See [github.com/aiddlc/.github/CONTRIBUTING.md](https://github.com/aiddlc/.github/blob/main/CONTRIBUTING.md) for the contribution process.

---

*Reference Portal · AIDDLC Standard v1.0 · 10QBIT Technologies · [aiddlc.ai](https://aiddlc.ai)*
