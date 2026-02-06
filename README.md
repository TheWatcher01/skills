# Agent Skills

A collection of production-ready skills for AI coding agents. Skills are reusable capabilities that extend agent expertise with procedural knowledge.

Skills follow the [Agent Skills](https://agentskills.io/) specification.

## Installation

```bash
npx skills add TheWatcher01/skills
```

## Available Skills (17)

### Development & Technical

| Skill | Description |
|-------|-------------|
| [frontend-design](skills/frontend-design/SKILL.md) | Create distinctive, production-grade frontend interfaces with high design quality |
| [webapp-testing](skills/webapp-testing/SKILL.md) | Test local web applications using Playwright — verify UI, capture screenshots, debug |
| [web-artifacts-builder](skills/web-artifacts-builder/SKILL.md) | Build multi-component web apps with React + Tailwind + shadcn/ui, bundled to single HTML |
| [mcp-builder](skills/mcp-builder/SKILL.md) | Guide for creating high-quality MCP servers (Python FastMCP or Node/TypeScript) |
| [smart-commit](skills/smart-commit/SKILL.md) | Security-aware Git commits with Conventional Commits format |
| [skill-creator](skills/skill-creator/SKILL.md) | Meta-skill for creating effective new skills |

### Creative & Design

| Skill | Description |
|-------|-------------|
| [algorithmic-art](skills/algorithmic-art/SKILL.md) | Create algorithmic art using p5.js with seeded randomness and interactive exploration |
| [canvas-design](skills/canvas-design/SKILL.md) | Create visual designs, posters, and artwork using canvas/SVG techniques |
| [brand-guidelines](skills/brand-guidelines/SKILL.md) | Apply consistent brand colors, typography, and visual identity to any output |
| [theme-factory](skills/theme-factory/SKILL.md) | Toolkit for styling outputs with 10 pre-set professional themes |
| [slack-gif-creator](skills/slack-gif-creator/SKILL.md) | Create animated GIFs optimized for Slack using PIL/Pillow |

### Document Skills

| Skill | Description |
|-------|-------------|
| [docx](skills/docx/SKILL.md) | Create and edit Word documents (.docx) with python-docx |
| [pdf](skills/pdf/SKILL.md) | Create, edit, and extract data from PDF documents |
| [pptx](skills/pptx/SKILL.md) | Create and edit PowerPoint presentations with python-pptx |
| [xlsx](skills/xlsx/SKILL.md) | Create and edit Excel spreadsheets with openpyxl |
| [doc-coauthoring](skills/doc-coauthoring/SKILL.md) | Structured workflow for co-authoring documentation, specs, and proposals |

### Communication

| Skill | Description |
|-------|-------------|
| [internal-comms](skills/internal-comms/SKILL.md) | Write internal communications: 3P updates, newsletters, FAQs, reports |

## Skill Structure

Each skill contains:

- `SKILL.md` — Instructions for the agent (required)
- `references/` — Supporting documentation loaded on demand (optional)
- `scripts/` — Executable helper scripts (optional)
- `assets/` — Templates, static resources (optional)
- `themes/` — Theme definitions (optional, theme-factory only)

## Sources

Skills in this collection are adapted from multiple sources:

- **[anthropics/skills](https://github.com/anthropics/skills)** — Adapted for cross-agent compatibility (Claude-specific references removed)
- **Custom skills** — Original skills by TheWatcher01

## License

MIT
