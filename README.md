# Hi, I'm Ashkan 👋

**Los Angeles.** I build open-source AI tools, and I make AIs argue with each other until one of them ships something.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)

## Start here

- **[Open Council](https://github.com/goshtasb/OpenCouncil)**: three AIs argue over your spec until they agree, then one ships it as a tested, gated PR. It never says done when it isn't. [Watch a real council →](https://github.com/goshtasb/OpenCouncil/tree/main/docs/replays)
- **[OmniGlass](https://github.com/goshtasb/OmniGlass)**: AI that acts on your screen, not just reads it. Snip anything, get buttons that execute. MCP plugins, sandboxed, local LLM.
- **[Anie](https://github.com/goshtasb/Anie)**: reads a news article and flags manipulation, bias and psyops. Live at [goanie.com](https://www.goanie.com/).

## What I'm building

### Agents that ship code
- **[OpenCouncil](https://github.com/goshtasb/OpenCouncil)**: Lead PM, Chief Engineer and Chief Architect seats deliberate a PRD to unanimous sign-off; you approve; it opens the PR. Claude Code plugin, CLI and agent skill.
- **[council-playground](https://github.com/goshtasb/council-playground)**: the small repo I point councils at to test solo mode end to end.

### Local-first AI
- **[OmniGlass](https://github.com/goshtasb/OmniGlass)**: Tauri and Rust desktop app. Screen pixels in, MCP tool calls out.
- **[NARS-JARVIS](https://github.com/goshtasb/NARS-JARVIS)**: a local cognitive assistant that pairs a NARS/ONA symbolic brain with a local LLM for language.

### Signal from noise
- **[Anie](https://github.com/goshtasb/Anie)**: forensic analysis of news articles. FastAPI backend, Chrome extension, mobile app.
- **[project-eagle-eye](https://github.com/goshtasb/project-eagle-eye)**: real-time WiFi CSI sensing that renders people as 3D skeletons on a floor plan.

## What I'm doing now

- Running Open Council on real repos and publishing every run, stalls included
- Making multi-agent coding boring enough to trust: gates, sign-offs, no false DONEs
- Writing about what breaks at [ashkan.us](https://ashkan.us)

## Connect

[![X](https://img.shields.io/badge/X-@Ashkon-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Ashkon)
[![Website](https://img.shields.io/badge/Web-ashkan.us-0A66C2?style=flat-square)](https://ashkan.us)

---

> Plausible isn't the same as approvable.

<details>
<summary>Things my councils taught me</summary>

- In ten runs in one day, every council pointed at my test repo caught that `npm test` had been running zero tests on Node 22. Nobody asked them to look.
- A PR can pass every check and still not build against main. Now the harness syncs with the base before it verifies.
- The most useful bug report is a council that went wrong.

</details>
