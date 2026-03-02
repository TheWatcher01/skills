# AGENTS.md — TheWatcher01/skills

Agent Skills collection. Install: `npx skills add TheWatcher01/skills`

## Available Skills (24)

| Skill | Category | Description |
|-------|----------|-------------|
| [smart-commit](skills/smart-commit/SKILL.md) | Dev | Security-aware Git commits with Conventional Commits |
| [frontend-design](skills/frontend-design/SKILL.md) | Dev | Production-grade frontend interfaces |
| [webapp-testing](skills/webapp-testing/SKILL.md) | Dev | Web app testing with Playwright |
| [web-artifacts-builder](skills/web-artifacts-builder/SKILL.md) | Dev | React+Tailwind+shadcn/ui web app scaffolding |
| [mcp-builder](skills/mcp-builder/SKILL.md) | Dev | MCP server development guide |
| [skill-creator](skills/skill-creator/SKILL.md) | Dev | Meta-skill for creating new skills |
| [mastra-workflows](skills/mastra-workflows/SKILL.md) | Dev | DAG workflows with Mastra 1.x |
| [agentic-workspace](skills/agentic-workspace/SKILL.md) | Agent | VS Code agentic architecture setup |
| [workflows-creator](skills/workflows-creator/SKILL.md) | Agent | Chainskills workflow creation |
| [deep-research](skills/deep-research/SKILL.md) | Research | Systematic deep research methodology |
| [data-freshness-check](skills/data-freshness-check/SKILL.md) | Research | Data accuracy and freshness verification |
| [pwa-user-simulation](skills/pwa-user-simulation/SKILL.md) | Research | PWA user journey simulation via MCPs |
| [ui-neuro-ergo](skills/ui-neuro-ergo/SKILL.md) | Research | Neuro-ergonomic + a11y UI audit |
| [algorithmic-art](skills/algorithmic-art/SKILL.md) | Creative | p5.js generative art |
| [canvas-design](skills/canvas-design/SKILL.md) | Creative | Visual design with canvas/SVG |
| [brand-guidelines](skills/brand-guidelines/SKILL.md) | Creative | Brand identity system |
| [theme-factory](skills/theme-factory/SKILL.md) | Creative | 10 professional themes |
| [slack-gif-creator](skills/slack-gif-creator/SKILL.md) | Creative | Animated GIFs for Slack |
| [docx](skills/docx/SKILL.md) | Document | Word documents (.docx) |
| [pdf](skills/pdf/SKILL.md) | Document | PDF creation and editing |
| [pptx](skills/pptx/SKILL.md) | Document | PowerPoint presentations |
| [xlsx](skills/xlsx/SKILL.md) | Document | Excel spreadsheets |
| [doc-coauthoring](skills/doc-coauthoring/SKILL.md) | Document | Structured doc co-authoring workflow |
| [internal-comms](skills/internal-comms/SKILL.md) | Comms | Internal communications templates |

## Structure

Each skill follows the [Agent Skills specification](https://agentskills.io/specification):

```
skills/<skill-name>/
├── SKILL.md           # Required — agent instructions
├── references/        # Optional — detailed docs (loaded on demand)
├── scripts/           # Optional — executable helpers
└── assets/            # Optional — templates, static resources
```
