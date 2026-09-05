# TonyRainforest

**Computational Coastal Engineering · Scientific Computing · Research Software**

Master’s student at **Tianjin University**, working on wave–structure interaction and computational coastal engineering. I also build tools for reliable, reproducible AI-assisted work.

[Research](#research-in-progress) · [Software](#selected-software) · [Contributions](#open-source-contributions) · [Contact](mailto:zhangyswx@163.com)

**Start here:** [ContextCanopy](https://github.com/YusenZhang0601/context-canopy) — portable context for independent AI agents.

**Upstream work:** [Hermes Agent](https://github.com/NousResearch/hermes-agent/pull/94606) — context-preservation fix incorporated upstream with authorship preserved.

## Research in Progress

My research interests center on **waves interacting with coastal and porous structures**, including free-surface and multiphase flow. My working areas include lattice Boltzmann methods, GPU/HPC workflows, numerical diagnostics, and verification and validation.

The priority is a defensible physical result: clear assumptions, appropriate benchmarks, and reproducible analysis. Research artifacts will be linked here when documented and cleared for public release.

## Selected Software

### [ContextCanopy](https://github.com/YusenZhang0601/context-canopy)

A local-first, user-owned context layer for independent AI agents. Shared context stays portable without merging every agent into the same role.

**Engineering focus:** MCP integration, transactional writes and rollback, deterministic validation, and a documented isolated cross-agent handoff test.

[Overview and verification procedure](https://github.com/YusenZhang0601/context-canopy#proof-not-promise) · [CI](https://github.com/YusenZhang0601/context-canopy/actions)

### [Tutor](https://github.com/YusenZhang0601/tutor)

A file-based AI tutoring template that organizes diagnosis, retrieval practice, review scheduling, and learner state.

**Engineering focus:** persistent workflow state and reusable agent instructions. The template’s educational effectiveness is not established by its software features alone.

## Open-source Contributions

**Merged / incorporated upstream**

- **Hermes Agent:** contributed the substantive fix preventing destructive context compression after empty provider responses. [Original #94531](https://github.com/NousResearch/hermes-agent/pull/94531) → [merged salvage #94606](https://github.com/NousResearch/hermes-agent/pull/94606), with authorship preserved.
- **AntigravityManager:** fixed token recovery, concurrent polling coordination, and transient availability-state cleanup, with regression coverage. [Merged #305](https://github.com/Draculabo/AntigravityManager/pull/305).

<details>
<summary>Ongoing contributions — status checked 2026-09-05</summary>

- **OpenClaw #138750:** proposed a fix to preserve the dotenv assignment backing a newly configured environment SecretRef. [Open; not merged](https://github.com/openclaw/openclaw/pull/138750).
- **CC Switch #6791:** proposed a routing change for declared long-context model markers. [Open; not merged](https://github.com/farion1231/cc-switch/pull/6791).

</details>

## Working Style & Background

**Reproduce the failure. Make assumptions explicit. Test the fix. Preserve the evidence.**

I use AI throughout development and research workflows; problem definition, validation, and technical judgment remain my responsibility.

Additional experience: **WorldQuant BRAIN Consultant**.

I welcome conversations about research collaboration and research-software or AI-tooling opportunities.

**Contact:** [zhangyswx@163.com](mailto:zhangyswx@163.com)
