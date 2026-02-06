# Agent Skills

A collection of production-ready skills for AI coding agents. Skills are reusable capabilities that extend agent expertise with procedural knowledge.

Skills follow the [Agent Skills](https://agentskills.io/) specification.

## Installation

```bash
npx skills add TheWatcher01/skills
```

## Available Skills

### smart-commit

Automates intelligent Git commits with security-first approach. Analyzes unstaged/staged changes, groups files by logical development concern, and commits sequentially with Conventional Commit messages.

**Features:**
- Pre-commit security audit (credential leak detection, large file warnings)
- Adaptive framework detection (15+ stacks: Next.js, Vue, Django, Go, Rust...)
- Conventional Commits format with smart scoping
- Progressive disclosure with reference docs

**Use when:**
- "commit", "smart commit", "save changes"
- "push", "git commit", "commit all"

**Structure:**
```
skills/smart-commit/
├── SKILL.md                          # Core instructions (233 lines)
├── references/
│   ├── security-checklist.md         # Full pre-commit security audit
│   ├── grouping-patterns.md          # Framework-specific file grouping
│   └── conventional-commits.md       # Commit message reference
└── scripts/
    └── pre-commit-audit.sh           # Executable security audit script
```

## Skill Structure

Each skill contains:

- `SKILL.md` — Instructions for the agent (required)
- `references/` — Supporting documentation loaded on demand (optional)
- `scripts/` — Executable helper scripts (optional)

## License

MIT
