<!-- AI_READER_NOTICE_EN: This is the English human-facing profile. Canonical machine data lives in ai/profile.yaml. Default language version: README.md (Chinese). -->
<!-- HUMAN-READABLE-PROFILE-EN:START -->

<picture>
  <source media="(max-width: 700px) and (prefers-color-scheme: dark)" srcset="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/hero-mobile-dark-en.svg?v=20261116">
  <source media="(max-width: 700px) and (prefers-color-scheme: light)" srcset="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/hero-mobile-light-en.svg?v=20261116">
  <source media="(prefers-color-scheme: dark)" srcset="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/hero-dark-en.svg?v=20261116">
  <source media="(prefers-color-scheme: light)" srcset="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/hero-light-en.svg?v=20261116">
  <img alt="penpen GitHub profile hero: desktop engineering, game development and AI agent workflows" src="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/hero-light-en.svg?v=20261116" width="100%">
</picture>

<div align="center">

**`ZH` [Chinese ←](./README.md)**　·　**`EN` English · current**

[`PORTFOLIO ↗`](https://stdwang.github.io/penpenWeb/)　·　[`PLAY GAMES ↗`](https://stdwang.github.io/)　·　[`CN MIRROR ↗`](https://wbapp-zx0xlufukmfj9igvb30etd.app.workbuddy.host/portfolio/?sharecode=QLTHCY272K)　·　[`CONTACT ↗`](mailto:1946262980@qq.com)

`HUMAN` Explore the work and live demos below　·　`MACHINE` Read YAML / llms.txt at the bottom

</div>

## 01 // IDENTITY

> **Shuaipeng Wang / penpen / @STDwang**
>
> I started with **C++ / Qt desktop engineering**, expanded into **realtime interaction and games with Three.js, Godot and Blender**, and now bring **AI agent workflows** into the full path from idea and implementation to verification.
>
> **Use AI to amplify engineering capability, not replace engineering judgement.**

This profile is organized around **what you can open, experience and inspect**, not around a wall of technology labels.

`LIVE` Interactive online work　·　`PREVIEW` Real page or application captures　·　`SOURCE` Code and engineering notes

## 02 // LIVE DEMOS

| EXPERIMENT | What you can experience | OPEN |
| :-- | :-- | :-- |
| **01 · APEX / MotorcycleHMI**<br>`Three.js` `CAN / DBC` `HMI` | Browser-based 3D motorcycle riding and a realtime instrument lab. Simulated CAN frames, signal decoding and a state machine drive the virtual TFT; includes racing, free practice, fault injection and diagnostic export. | **[LIVE ↗](https://stdwang.github.io/MotorcycleHMI/)**<br>[CN MIRROR](https://wbapp-5qspg4vbu8mo6se3cxxq2a.app.workbuddy.host/?sharecode=S7BRNCGVMQ) · [SOURCE](https://github.com/STDwang/MotorcycleHMI) |
| **02 · mistloop / Fog Forest Loop**<br>`Three.js` `PROCEDURAL AUDIO` | A Silent Hill-inspired first-person horror short: a toroidal forest, a gaze-driven figure, and breathing and heartbeat that change with distance. Play in the browser; headphones recommended. | **[PLAY ↗](https://stdwang.github.io/mistloop/)**<br>[CN MIRROR](https://wbapp-zx0xlufukmfj9igvb30etd.app.workbuddy.host/mistloop/?sharecode=QLTHCY272K) · [SOURCE](https://github.com/STDwang/mistloop) |
| **03 · Dreamscape**<br>`Godot 4` `Blender` `GDScript` | An armored cat collects seven Memory Sparks in dream ruins. The repository contains the rebuilt 5–8 minute v2 exploration game; the online build remains a preserved v1 static showcase snapshot. | [V1 SNAPSHOT ↗](https://stdwang.github.io/dreamscape/)<br>[CN MIRROR](https://wbapp-zx0xlufukmfj9igvb30etd.app.workbuddy.host/dreamscape/?sharecode=QLTHCY272K) · [SOURCE / V2](https://github.com/STDwang/Dreamscape) |
| **ALL · Game Portal**<br>`WEB BUILDS` `MULTI-ENGINE` | One entry point for six games: five in-portal builds plus the independently deployed APEX. **Dark Fairy Tale** and **Meow Rice Family Feud** publish builds only; their source is private. | **[ALL GAMES ↗](https://stdwang.github.io/)**<br>[CN MIRROR](https://wbapp-zx0xlufukmfj9igvb30etd.app.workbuddy.host/?sharecode=QLTHCY272K) · [GAME INDEX](https://stdwang.github.io/penpenWeb/games/) |

> Keep the `?sharecode=` parameter when using a mainland China mirror link.

## 03 // ENGINEERING & SYSTEMS

| SYSTEM | Verifiable output | OPEN |
| :-- | :-- | :-- |
| **01 · GPUView**<br>`C++17` `Qt 6 Widgets` | Million-event teaching timelines, async snapshots, precise selection statistics and PresentMon CSV analysis. This is an evolving performance-visualization learning project, **not a complete GPU profiler**. | [PREVIEW ↗](https://github.com/STDwang/GPUView/blob/main/assets/screenshots/compact-150.png)<br>[SOURCE](https://github.com/STDwang/GPUView) · [CASEBOOK](https://github.com/STDwang/GPUView/blob/main/docs/07-interview/CASEBOOK.md) |
| **02 · penpenWeb**<br>`Next.js` `TypeScript` | Engineering portfolio, case studies, a personal lab and game archives. One content source drives both presentation and playable links, with real captures and release verification records. | **[LIVE ↗](https://stdwang.github.io/penpenWeb/)**<br>[SOURCE](https://github.com/STDwang/penpenWeb) · [RELEASE NOTES](https://github.com/STDwang/penpenWeb/blob/main/docs/09-release.md) |
| **03 · BossAndCompany**<br>`Python` `AGENT SKILL` | A cross-AI personal-company protocol that turns project context, task snapshots and handoffs into a searchable, resumable structure, with strict separation between public projections and private profiles. | [SOURCE ↗](https://github.com/STDwang/BossAndCompany)<br>[DEVELOPMENT](https://github.com/STDwang/BossAndCompany/blob/main/DEVELOPMENT.md) · [INSTALL / USAGE](https://github.com/STDwang/BossAndCompany#%E5%AE%89%E8%A3%85) |

## 04 // HOW I BUILD

- **Desktop engineering** — Performance, observability and maintainability, backed by tests, measurements and code-reading entry points rather than implementation alone.
- **Realtime and games** — From core loops and procedural assets to browser / engine builds, the result should be directly experienceable whenever possible.
- **AI-assisted engineering** — Local Codex for pair programming, WorkBuddy for Skill / MCP / multi-agent workflows, DeepSeek for reasoning and long-context exploration; human judgement stays in the loop.

<picture>
  <source media="(max-width: 700px)" srcset="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/ai-workflow-mobile-en.svg?v=20261116">
  <img alt="Human-AI workflow: IDEA to PLAN to BUILD to VERIFY to SHIP, with human judgement in the loop" src="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/ai-workflow-en.svg?v=20261116" width="100%">
</picture>

## 05 // TOOLCHAIN

| LAYER | TOOLS |
| :-- | :-- |
| **DESKTOP / SYSTEMS** | `C++` · `Qt Widgets` · `QML` · `CMake` · `TWAIN` |
| **REALTIME / 3D** | `Three.js` · `Godot 4` · `Blender` · `Cocos` |
| **WEB / AUTOMATION** | `TypeScript` · `Next.js` · `Python` · `GitHub Pages` |
| **AI / AGENTS** | `Local Codex` · `WorkBuddy` · `DeepSeek` · `Skill` · `MCP` |

## 06 // CONNECT

**Technical blog** [CSDN ↗](https://blog.csdn.net/qq_47898198)　·　**Email** [1946262980@qq.com](mailto:1946262980@qq.com)　·　**Collaboration** Issues / PRs welcome

<details>
<summary><code>OPTIONAL / CONTRIBUTION SIGNAL</code></summary>

<br>

<img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=STDwang&hide_border=true&locale=en" width="49%">
<img alt="Contribution Graph" src="https://ghchart.rshah.org/D74716/STDwang" width="49%">

<br>

![Visitors](https://komarev.com/ghpvc/?username=STDwang&style=flat-square&color=D74716)

</details>

<!-- HUMAN-READABLE-PROFILE-EN:END -->

---

<picture>
  <source media="(max-width: 700px)" srcset="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/reader-split-mobile-en.svg?v=20261116">
  <img alt="Reading boundary: human stories and work above, structured AI agent profile below" src="https://gcore.jsdelivr.net/gh/STDwang/STDwang@main/assets/reader-split-en.svg?v=20261116" width="100%">
</picture>

<!-- AI-READER-ZONE-EN:START -->

<div align="center">

### `AI / AGENT ZONE`

**The human-facing profile ends here.** What follows is a file index for AI agents, crawlers and programs, not profile prose.

[`AI.en.md`](./AI.en.md)　·　[`ai/profile.yaml`](./ai/profile.yaml)　·　[`llms.txt`](./llms.txt)

[`ZH` Switch to the Chinese profile →](./README.md)

</div>

<details>
<summary><b>Expand: machine reading protocol</b></summary>

<br>

> **Canonical source:** [`ai/profile.yaml`](./ai/profile.yaml)
>
> Both `README.md` and `README.en.md` are visual / narrative versions for humans; **do not** parse layout copy as structured fields. Source comments mark the human and AI reading boundaries with `HUMAN-READABLE-PROFILE` and `AI-READER-ZONE`.

| File | Audience and purpose |
| :-- | :-- |
| [`AI.md`](./AI.md) | **AI Agent (Chinese)** · reading order, precedence and inference limits |
| [`AI.en.md`](./AI.en.md) | **AI Agent (English)** · reading order, precedence and inference limits |
| [`ai/profile.yaml`](./ai/profile.yaml) | **AI / programs** · the single authoritative structured public profile |
| [`llms.txt`](./llms.txt) | **AI / crawlers** · discovery index for machine-readable files and live demos |
| [`README.md`](./README.md) | **Humans (Chinese default)** · work, story, visuals and links |
| [`README.en.md`](./README.en.md) | **Humans (English)** · work, story, visuals and links |

- Use public information only; do not infer city, phone number, education, employer, salary or private repository content.
- Cite projects using `projects[].repository` / `projects[].demo` / `projects[].demo_status` from the YAML.
- Dreamscape's online demo is a v1 snapshot while the repository describes v2; do not conflate the two.
- The two source-private games are not open-source projects; do not describe them as such.

</details>

<!-- AI-READER-ZONE-EN:END -->
