# DELEGATION.md

> *Defines the authority chain from human principal to AI agent*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/delegation.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

> **Canonical Source:** This spec is maintained in the main
> [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs) repository.
> This repo is an auto-synced mirror for easy discovery and download.
> To report issues or submit changes, please open a PR or issue on the
> [main repository](https://github.com/totalmarkdown/agent-md-specs).

## What is DELEGATION.md?

DELEGATION.md answers NIST's most-asked question: who authorized this agent and with what constraints? It defines the complete authority chain — scope, time bounds, budget caps, geographic restrictions, sub-delegation policies, and revocation mechanisms.

Maps directly to OAuth 2.0 On-Behalf-Of (OBO) token exchange flows. Addresses the "confused deputy" problem by requiring explicit scope allow-lists rather than deny-lists.

Create a DELEGATION.md for any agent operating on behalf of a human or organization, especially in multi-agent systems where authority chains must be auditable.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/delegation.md/main/DELEGATION.md
```

Add to your project root and customize for your agent.

---

## When to use DELEGATION.md

- Enterprise agents operating on behalf of executives or departments
- Multi-agent systems where agents delegate sub-tasks to other agents
- Any scenario requiring auditable proof of who authorized what

---

## Where it fits

Works alongside LEASTPRIVILEGE.md (dynamic runtime privileges), PERMISSIONS.md (static access control), CONSENT.md (user consent is separate from organizational authority), SESSION.md (sessions inherit delegation scope), and ENFORCEMENT.md (how delegation policies are verified).

---

## The Full Spec

→ [DELEGATION.md](./DELEGATION.md)

---

## Part of agent-md-specs

One of 178 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
