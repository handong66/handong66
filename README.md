<h1 align="center">Hi, I'm Dong</h1>

<p align="center">
  Researcher-builder working across evidence-first AI, agent workflows, local-first research apps, and production web work.
  <br />
  连接证据优先 AI、agent 协作工作流、本地优先研究应用与生产级 Web 工作的研究型开发者。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Evidence--first%20AI-111827?style=for-the-badge&logo=openai&logoColor=white" alt="Evidence-first AI" />
  <img src="https://img.shields.io/badge/Agent%20Workflows-2563eb?style=for-the-badge&logoColor=white" alt="Agent Workflows" />
  <img src="https://img.shields.io/badge/Documentation%20Drift-0f766e?style=for-the-badge&logo=googledocs&logoColor=white" alt="Documentation Drift" />
  <img src="https://img.shields.io/badge/Local--first%20Apps-7c3aed?style=for-the-badge&logo=sqlite&logoColor=white" alt="Local-first Apps" />
  <img src="https://img.shields.io/badge/Academic%20Tools-92400e?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Academic Tools" />
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

## About Me

- I build AI-assisted products where source evidence, guardrails, and user workflows matter.
- My research background is Cantonese speech, tone, and emotional prosody; it keeps my engineering work grounded in human judgment and evidence.
- I ship local-first desktop apps, developer tools, production web work, portfolio agents, and language-learning tools from design through release.

## Current Focus

- Shipping Evidoc, a repo-local evidence gate for stale documentation and coding-agent instructions, now on npm as `@evidoc/evidoc`.
- Extending Claude Code with plugins that delegate reviews, rescues, and session handoffs to the opencode, Grok, and Antigravity (agy) CLIs.
- Tightening Claude Code, Codex, opencode, Grok, Antigravity, MCP, and personal skill workflows around review gates and release discipline.
- Developing local-first academic and viva-prep tools with evidence traces and opt-in external calls.
- Evolving [han-dong.link](https://han-dong.link) with source-grounded Q&A, Role Fit briefs, and spatial portfolio UI.

## Featured Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [Evidoc](https://github.com/handong66/Evidoc) | A repo-local evidence gate that checks README, AGENTS, docs, examples, and agent instructions against the code they describe | TypeScript / CLI / MCP / GitHub Actions |
| [opencode-plugin-cc](https://github.com/handong66/opencode-plugin-cc) | A Claude Code port of OpenAI's codex-plugin-cc surface, driving opencode for structured reviews, task delegation, and session transfer | JavaScript / Claude Code Plugin / opencode CLI |
| [grok-plugin-cc](https://github.com/handong66/grok-plugin-cc) | The same port driving the Grok CLI's headless mode for reviews, adversarial analysis, and rescue, with session handoff by transcript import | JavaScript / Claude Code Plugin / Grok CLI |
| [agy-plugin-cc](https://github.com/handong66/agy-plugin-cc) | A port of that port onto Google's Antigravity CLI (agy). Reviews run against a disposable copy because agy has no read-only mode; rescue deliberately gets the real tree | JavaScript / Claude Code Plugin / Antigravity CLI |
| [opencode-plugin-codex](https://github.com/handong66/opencode-plugin-codex) | Codex plugin that runs opencode as a bounded reviewer, rescue agent, and handoff target | TypeScript / MCP / opencode CLI |
| [grok-plugin-codex](https://github.com/handong66/grok-plugin-codex) | Codex plugin that delegates bounded review, rescue, and adversarial analysis to the local Grok CLI through MCP | TypeScript / MCP / Grok CLI |
| [agy-plugin-codex](https://github.com/handong66/agy-plugin-codex) | Codex plugin for the Antigravity CLI with a measured runtime contract, typed refusals, and filesystem-isolated read-only reviews | TypeScript / MCP / Antigravity CLI |
| [Dong-skills](https://github.com/handong66/Dong-skills) | Personal agent workflow skills for Claude, Codex, opencode, Grok, and Antigravity collaboration | Skills / Agent Workflows / Docs |
| [D-academic-agent](https://github.com/handong66/D-academic-agent) | Local-first academic evidence workspace for claim and citation auditing | TypeScript / Electron / MCP / SQLite |
| [D-viva-assistant-agent](https://github.com/handong66/D-viva-assistant-agent) | Thesis viva preparation app with evidence-linked practice, scoring, and revision tasks | Next.js / Electron / AI SDK / SQLite |
| [relaybar-open](https://github.com/handong66/relaybar-open) | macOS menu-bar monitor for AI coding account pools, remaining quota, and throttled states | Swift / macOS |
| [Cantonese-Mandarin-Cross-Ref](https://github.com/handong66/Cantonese-Mandarin-Cross-Ref) | Learner-facing lookup tool for Cantonese and Mandarin readings with Jyutping and audio | JavaScript / Language Education |

The three Claude Code plugins are ports: `opencode-plugin-cc` adapts the command surface of OpenAI's [codex-plugin-cc](https://github.com/openai/codex-plugin-cc) (Apache-2.0) to a different CLI, `grok-plugin-cc` applies the same adaptation to Grok, and `agy-plugin-cc` is a port of `opencode-plugin-cc` in turn. The three Codex plugins are built on the MCP surface rather than ported. None of the six is affiliated with or endorsed by OpenAI, xAI, or Google.

## Core Stack

**Agent & evidence tools:** `TypeScript` `Node.js` `MCP` `Codex Plugins` `opencode` `Grok CLI` `Antigravity CLI` `AI SDK`

**Local-first apps:** `Electron` `SQLite` `better-sqlite3`

**Production web:** `Next.js` `React` `Tailwind CSS` `Supabase` `Cloudflare` `Resend` `Sentry` `Umami` `i18n`

**Native / product surfaces:** `Swift` `macOS` `JavaScript` `Astro`

**Quality gates:** `GitHub Actions` `Vitest` `Playwright`

## Build Style

> Evidence first. Keep the boundary visible. Ship the useful path first.

## Notes

- Personal site and source-grounded portfolio: [han-dong.link](https://han-dong.link)
- Research thread: Cantonese speech, tones, emotional prosody, and learner-facing language tools.
- Engineering thread: agent workflows, bounded multi-agent review, documentation drift control, local-first AI products, production web work, and practical developer tools.

<p align="center">
  Thanks for stopping by.
</p>
