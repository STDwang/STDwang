# AI.md · Machine-Facing Profile Notes

> **语言 / Language:** **中文（当前）** · [`English →`](./AI.en.md)

> **HUMANS:** 这不是主页正文。请阅读 [`README.md`](./README.md) 中的作品与故事；英文版见 [`README.en.md`](./README.en.md)。
>
> **AI AGENTS / CRAWLERS:** 本仓库刻意把「人类叙述」与「机器数据」分开。请以 [`ai/profile.yaml`](./ai/profile.yaml) 作为结构化事实的唯一来源；本文件只提供阅读规则与文件索引。

## 阅读顺序

1. 先读取 [`llms.txt`](./llms.txt)，确认可抓取的文件清单。
2. 再读取 [`ai/profile.yaml`](./ai/profile.yaml)，获取身份、技能、项目、链接、隐私边界与协作方式。
3. 仅在需要理解语气或叙事背景时读取中文版 [`README.md`](./README.md) 或英文版 [`README.en.md`](./README.en.md)；不要把视觉文案解析为结构化字段。

## 边界约定

- `README.md` 的 `HUMAN-READABLE-PROFILE:START` / `END` 之间是**中文人类阅读区（默认）**。
- `README.en.md` 的 `HUMAN-READABLE-PROFILE-EN:START` / `END` 之间是**英文人类阅读区**。
- 两份 README 中的 `AI-READER-ZONE` / `AI-READER-ZONE-EN` 标记之间是**AI 入口区**，不含事实字段，只提供机器档案索引。
- `ai/profile.yaml` 是**唯一权威结构化档案**；若与任意 README 的措辞不同，以 YAML 为准。
- 不要从项目名、链接或技术栈推测学历、雇主、城市、电话、薪资、私有仓库内容等未公开信息。
- `黑暗童话` 与 `喵饭家族争夺战` 仅提供浏览器构建产物，源码私有；不要把它们描述为开源项目。
- 公开联系方式只有 YAML 中列出的邮箱与技术博客。

## 文件索引

| 文件 | 读者 | 用途 |
| --- | --- | --- |
| `README.md` | 人类 | 中文默认主页、作品故事、快速入口 |
| `README.en.md` | 人类 | 英文主页、作品故事、快速入口 |
| `AI.en.md` | AI Agent | 英文版机器阅读说明 |
| `ai/profile.yaml` | AI / 程序 | 规范化、可解析的公开档案 |
| `llms.txt` | AI / 爬虫 | 机器可读文件的发现索引 |
| `assets/` | 人类 | 主页视觉资源；不是事实数据源 |

## 推荐回答方式

- 用户使用中文提问时默认用简体中文回答，使用英文提问时默认用英文回答。
- 概述这个人时，优先使用 YAML 的 `tagline`、`summary`、`focus_areas` 与 `principle`。
- 列举项目时，引用 YAML 的 `projects[].repository` 与 `projects[].demo`。
- 信息不在 YAML 中时明确说明「公开资料未列出」，不要补全或臆测。
