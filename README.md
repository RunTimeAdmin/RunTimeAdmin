# David Cooper (`DC`)

**CCIE #14019** · USAF veteran · building security tooling for networks, software supply chains, and autonomous agents.

I publish open work under [RunTimeAdmin](https://github.com/RunTimeAdmin). Longer background and essays: [protocol14019.com](https://protocol14019.com). Tooling hub: [runtimeadmin.com](https://runtimeadmin.com). On X: [@defiauditccie](https://x.com/defiauditccie).

> This GitHub account is relatively new as a *public publishing* surface. The career behind the CCIE / ops work is not. If you are reviewing a release, start with the active products below — not every archived experiment.

## What to look at first

| Project | What it is |
| --- | --- |
| **[Sigvara](https://github.com/RunTimeAdmin/Sigvara)** | Computed reputation + slashable bonds for AI agents on top of [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004). Live on Arc testnet. Primary protocol focus right now. |
| **[counterscarp](https://github.com/RunTimeAdmin/counterscarp)** | Smart-contract security analysis platform (EVM + Solana). |
| **[sbomix](https://github.com/RunTimeAdmin/sbomix)** | Lockfile-first SBOM / AI-BOM + CVE exposure search. |
| **[mcpshield-action](https://github.com/RunTimeAdmin/mcpshield-action)** | CI scanner for risky MCP server configs. |
| **[Countersig-Public](https://github.com/RunTimeAdmin/Countersig-Public)** | Public docs/SDK surface for the hosted NHI / agent identity platform (separate from the Sigvara protocol). |
| **[runtime-fence-ai](https://github.com/RunTimeAdmin/runtime-fence-ai)** | Kill-switch / runtime safety layer for autonomous agents. |

## How the suite fits together

- **Sigvara** — decentralized, on-chain *standing* trust (score + bond) above ERC-8004.
- **Countersig** (hosted platform) — centralized NHI / verification product. Same builder, different trust model; it does not write Sigvara state.
- **Counterscarp / ScamHound / ScarpShield** — audit and monitoring tools that feed the same security practice.
- **sbomix / MCPShield** — shift-left supply-chain and agent-tooling hygiene.

Site for Sigvara: [sigvara.xyz](https://sigvara.xyz).


