# AGENTS.md — TheWatcher01/skills

Agent Skills collection. Install: `npx skills add TheWatcher01/skills`

## Available Skills

| Skill | Description |
|-------|-------------|
| [smart-commit](skills/smart-commit/SKILL.md) | Security-aware intelligent Git commits with Conventional Commits |

## Structure

Each skill follows the [Agent Skills specification](https://agentskills.io/specification):

```
skills/<skill-name>/
├── SKILL.md           # Required — agent instructions
├── references/        # Optional — detailed docs (loaded on demand)
├── scripts/           # Optional — executable helpers
└── assets/            # Optional — templates, static resources
```
