<div align="center">

<img src="https://raw.githubusercontent.com/YusenZhang0601/context-canopy/main/docs/assets/tony-system-builder-banner.png" alt="Tony Rainforest — personal brand banner" width="100%" />

# Tony Rainforest

### Coastal Engineering · Scientific Computing · AI Systems

**M.S. Candidate @ Tianjin University** · Wave–Structure Interaction · Research Software · Reliable AI Tooling

<p>
  <img src="https://img.shields.io/badge/Coastal_Engineering-Research-C7A25B?style=flat-square&labelColor=111111" alt="Coastal Engineering" />
  <img src="https://img.shields.io/badge/Scientific_Computing-GPU%2FHPC-C7A25B?style=flat-square&labelColor=111111" alt="Scientific Computing" />
  <img src="https://img.shields.io/badge/LBM-Numerical_Methods-C7A25B?style=flat-square&labelColor=111111" alt="LBM" />
  <img src="https://img.shields.io/badge/AI_Systems-Agents%20%2F%20MCP-C7A25B?style=flat-square&labelColor=111111" alt="AI Systems" />
  <img src="https://img.shields.io/badge/Open_Source-Upstream_Contributor-C7A25B?style=flat-square&labelColor=111111" alt="Open Source" />
</p>

[Research](#-research-focus) · [Systems](#-selected-systems) · [Open Source](#-open-source-engineering) · [Signals](#-github-signals) · [Contact](#-connect)

</div>

> I study **computational coastal engineering** and build scientific software and reliable AI systems. My bias is toward explicit assumptions, reproducible evidence, and systems that remain correct when things go wrong.

---

<table>
<tr>
<td align="center" width="25%"><strong>🎓 Tianjin University</strong><br />M.S. Candidate</td>
<td align="center" width="25%"><strong>🌊 Research</strong><br />Wave–Structure Interaction</td>
<td align="center" width="25%"><strong>⚙️ Compute</strong><br />LBM · GPU/HPC</td>
<td align="center" width="25%"><strong>🤖 Systems</strong><br />Agents · MCP · Automation</td>
</tr>
</table>

## 🌊 Research Focus

My research centers on **waves interacting with coastal and porous structures**, with an emphasis on physically defensible numerical results rather than tool loyalty.

| Scientific questions | Computational methods |
|---|---|
| Wave–structure interaction · free-surface flow · multiphase flow · porous-media interaction | Lattice Boltzmann methods · GPU/HPC workflows · numerical diagnostics · verification & validation |

**Current principle:** the scientific question owns the route; solvers, frameworks, and agents are replaceable means for reaching a result that can be checked and reproduced.

> Public research artifacts will be linked here when they are documented, reproducible, and cleared for release.

## 🧩 Selected Systems

### 🌿 [ContextCanopy](https://github.com/YusenZhang0601/context-canopy)

**Switch agents. Keep your context.** A local-first, user-owned context layer that lets independent AI agents share durable context without collapsing into one role.

<p>
  <a href="https://github.com/YusenZhang0601/context-canopy/releases/latest"><img src="https://img.shields.io/github/v/release/YusenZhang0601/context-canopy?style=flat-square&label=release&labelColor=111111&color=C7A25B" alt="ContextCanopy release" /></a>
  <a href="https://github.com/YusenZhang0601/context-canopy/actions"><img src="https://img.shields.io/github/actions/workflow/status/YusenZhang0601/context-canopy/ci.yml?branch=main&style=flat-square&label=CI&labelColor=111111&color=C7A25B" alt="ContextCanopy CI" /></a>
  <img src="https://img.shields.io/badge/MCP-compatible-C7A25B?style=flat-square&labelColor=111111" alt="MCP compatible" />
  <img src="https://img.shields.io/badge/authority-local--first-C7A25B?style=flat-square&labelColor=111111" alt="Local first" />
</p>

**What it demonstrates:** cross-agent continuity, MCP integration, transactional writes and rollback, deterministic validation, explicit authority boundaries, and an isolated Claude → Codex handoff proof.

**Explore:** [Project](https://github.com/YusenZhang0601/context-canopy) · [Proof](https://github.com/YusenZhang0601/context-canopy#proof-not-promise) · [CI](https://github.com/YusenZhang0601/context-canopy/actions)

### 🎓 [Tutor](https://github.com/YusenZhang0601/tutor)

A file-based AI tutoring template built around persistent learner state, retrieval-oriented sessions, review scheduling, and reusable agent instructions.

**Engineering focus:** stateful workflows, inspectable file-based state, configurable learning gates, and multi-agent project structure. Educational-effect claims are kept separate from software behavior.

## 🔧 Open-source Engineering

I prefer contribution work that starts from a reproducible failure and ends with a narrow fix, regression coverage, and a clear upstream decision.

| Upstream project | Contribution | Status |
|---|---|---|
| **[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)** | Prevented destructive context compression after degraded empty provider responses; substantive fix from [#94531](https://github.com/NousResearch/hermes-agent/pull/94531) was incorporated through [#94606](https://github.com/NousResearch/hermes-agent/pull/94606) with authorship preserved. | ✅ Incorporated upstream |
| **[Draculabo/AntigravityManager](https://github.com/Draculabo/AntigravityManager)** | Fixed 401 token recovery, concurrent poll coordination, and transient availability-state cleanup with regression coverage in [#305](https://github.com/Draculabo/AntigravityManager/pull/305). | ✅ Merged upstream |

<details>
<summary><strong>Ongoing upstream contributions</strong></summary>

- **[OpenClaw #138750](https://github.com/openclaw/openclaw/pull/138750)** — preserving the dotenv assignment backing a newly configured environment SecretRef. **Open / not merged** as last checked 2026-09-05.
- **[CC Switch #6791](https://github.com/farion1231/cc-switch/pull/6791)** — routing takeover for declared long-context model markers. **Open / not merged** as last checked 2026-09-05.

</details>

<div align="center">

**reproduce → isolate → fix → test → review → upstream**

</div>

## 📊 GitHub Signals

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=YusenZhang0601&show_icons=true&hide_border=true&bg_color=00000000&title_color=D4AF37&text_color=E6EDF3&icon_color=D4AF37&ring_color=D4AF37&rank_icon=github" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=YusenZhang0601&show_icons=true&hide_border=true&bg_color=00000000&title_color=9A7300&text_color=24292F&icon_color=9A7300&ring_color=9A7300&rank_icon=github" />
  <img alt="Tony Rainforest's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=YusenZhang0601&show_icons=true&hide_border=true&rank_icon=github" width="520" />
</picture>

</div>

## 🐍 Build · Research · Contribute · Evolve

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YusenZhang0601/YusenZhang0601/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YusenZhang0601/YusenZhang0601/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/YusenZhang0601/YusenZhang0601/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

</div>

## 🤝 Connect

**Working principle:** reproduce the failure, make assumptions explicit, test the fix, preserve the evidence.

I use AI throughout development and research workflows; problem definition, validation, and technical judgment remain my responsibility.

Additional experience: **WorldQuant BRAIN Consultant**.

I welcome conversations about **research collaboration, scientific computing, research software, and reliable AI systems**.

<div align="center">

📫 **[zhangyswx@163.com](mailto:zhangyswx@163.com)** · <a href="https://orcid.org/0009-0004-4856-7214"><img src="https://img.shields.io/badge/ORCID-0009--0004--4856--7214-A6CE39?style=flat-square&labelColor=111111" alt="ORCID 0009-0004-4856-7214" /></a>

<img src="https://komarev.com/ghpvc/?username=YusenZhang0601&style=flat-square&label=PROFILE%20VIEWS&color=C7A25B&labelColor=111111" alt="Profile views" />

### Connect complexity. Create order. Keep evolving.

</div>
