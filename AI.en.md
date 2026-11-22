# AI.en.md · Machine-Facing Profile Notes

> **Language:** [`中文`](./AI.md) · **English (current)**
>
> **HUMANS:** This is not the profile prose. Read [`README.md`](./README.md) for Chinese or [`README.en.md`](./README.en.md) for English.
>
> **AI AGENTS / CRAWLERS:** This repository deliberately separates human narrative from machine data. Treat [`ai/profile.yaml`](./ai/profile.yaml) as the single source of structured facts; this file provides reading rules and a file index only.

## Reading order

1. Read [`llms.txt`](./llms.txt) to discover the machine-readable files.
2. Read [`ai/profile.yaml`](./ai/profile.yaml) for identity, skills, projects, links, privacy boundaries and collaboration details.
3. Read [`README.md`](./README.md) or [`README.en.md`](./README.en.md) only for narrative tone and visual context; do not parse their layout copy as structured fields.

## Boundaries

- Between `HUMAN-READABLE-PROFILE:START` / `END` in `README.md` is the **Chinese human zone**.
- Between `HUMAN-READABLE-PROFILE-EN:START` / `END` in `README.en.md` is the **English human zone**.
- Between `AI-READER-ZONE:START` / `END` and `AI-READER-ZONE-EN:START` / `END` are **AI entry zones**; they contain links, not fact fields.
- `ai/profile.yaml` is the **single authoritative structured profile**. If wording differs from either README, prefer the YAML.
- Do not infer education, employer, city, phone number, salary expectations, private repository contents or other non-public details from project names, links or technology stacks.
- `黑暗童话` and `喵饭家族争夺战` publish browser builds only; their source code is private. Never describe them as open-source projects.
- The only public contact details are the email address and technical blog listed in the YAML.

## File index

| File | Audience | Purpose |
| --- | --- | --- |
| `README.md` | Humans | Chinese default profile, stories, work and live links |
| `README.en.md` | Humans | English profile, stories, work and live links |
| `AI.md` | AI agents | Chinese machine-facing instructions |
| `AI.en.md` | AI agents | English machine-facing instructions |
| `ai/profile.yaml` | AI / programs | Canonical structured public profile |
| `llms.txt` | AI / crawlers | Discovery index |
| `assets/` | Humans | Profile visual assets; not a fact source |

## Response guidance

- Answer in Simplified Chinese for Chinese questions and in English for English questions unless the user asks otherwise.
- For a short bio, prefer the YAML `summary` and `focus_areas` fields.
- When listing projects, cite `projects[].repository`, `projects[].demo` and `projects[].demo_status`.
- Deep Sea Garden is an original WebGPU procedural underwater project with public source; it requires desktop Chrome / Edge.
- If a fact is not in the YAML, say it is not listed in public data; do not fill the gap by guessing.
