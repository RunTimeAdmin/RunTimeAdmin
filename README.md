# David C (`DC`)

**CCIE #14019** · building trust and security tooling for autonomous agents, software supply chains and networks.

Tooling hub: [runtimeadmin.com](https://runtimeadmin.com) · Background and essays: [protocol14019.com](https://protocol14019.com) · On X: [@defiauditccie](https://x.com/defiauditccie)

## What I'm building

Tools for deciding whether to trust an AI agent before you pay it or rely on it.

| Project | What it is |
| --- | --- |
| **[Sigvara](https://github.com/RunTimeAdmin/Sigvara)** | Computed reputation and slashable bonds for agents on [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004). Live on Arc testnet. [sigvara.xyz](https://sigvara.xyz) |
| **[The Agent Bureau](https://github.com/RunTimeAdmin/the-agent-bureau)** | Dated, evidence-backed files on agent operators, built from signed outcomes that other businesses report. On test data while the outcome service is reviewed; its interrogation game for people and AI agents is live. [theagentbureau.xyz](https://theagentbureau.xyz) |
| **[agent-bureau-furnish](https://github.com/RunTimeAdmin/agent-bureau-furnish)** | The open-source tool for businesses to sign the outcomes they report: Ed25519 over RFC 8785 canonical JSON, with CSV import. |
| **[Nooscape](https://github.com/RunTimeAdmin/nooscape-public)** | An evidence-first public atlas of AI agents, with retained observations and verifiable provenance. Ask it from your own agent with [nooscape-mcp](https://github.com/RunTimeAdmin/nooscape-mcp). [nooscape.si](https://nooscape.si) |
| **CounterAudit** | Hosted audit trail for agent actions: sealed, hash-chained and RFC 3161 timestamped, with public proofs. The Agent Bureau's system of record. [counteraudit.io](https://counteraudit.io) |
| **[Countersig](https://github.com/RunTimeAdmin/Countersig-Public)** | Hosted identity and egress policy for agents (NHI). [countersig.com](https://countersig.com) |

## How they fit together

- **Nooscape** shows what the public record says about an agent.
- **Sigvara** gives it on-chain standing: a score and a bond, above ERC-8004.
- **The Agent Bureau** adds what other businesses report about the operator behind it, each report signed by the business and sealed in **CounterAudit**.
- **Countersig** is a separate, hosted identity product with its own trust model. It does not write Sigvara state.

## Security tooling

| Project | What it is |
| --- | --- |
| **[sbomix](https://github.com/RunTimeAdmin/sbomix)** | Lockfile-first SBOM and AI BOM generator with CVE exposure search. CLI, GitHub Action and hosted API. [sbomix.com](https://sbomix.com) |
| **[mcpshield-action](https://github.com/RunTimeAdmin/mcpshield-action)** | Scans committed MCP config files for risky MCP servers before merge. |
| **[runtime-fence-ai](https://github.com/RunTimeAdmin/runtime-fence-ai)** | Kill switch and runtime safety layer for autonomous agents. |
| **[counterscarp](https://github.com/RunTimeAdmin/counterscarp)** | Smart contract security analysis for EVM and Solana, with [ScarpShield](https://github.com/RunTimeAdmin/ScarpShield) for contract monitoring and [ScamHound](https://github.com/RunTimeAdmin/ScamHound) for rug-risk signals. [counterscarp.io](https://counterscarp.io) |

Contact: `david@runtimeadmin.com`
