# Claude Template

A starter template for projects using [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

Everything Claude needs to know about your project lives right here.

## Anatomy of the `.claude/` Folder

```
your-project/
├── CLAUDE.md                 # Team instructions, committed
├── CLAUDE.local.md           # Personal overrides, gitignored
│
├── .claude/
│   ├── settings.json         # Permissions + config, committed
│   ├── settings.local.json   # Personal permissions, gitignored
│   │
│   ├── commands/             # Custom slash commands
│   │   ├── review.md         #   /project:review
│   │   ├── fix-issue.md      #   /project:fix-issue
│   │   └── deploy.md         #   /project:deploy
│   │
│   ├── rules/                # Modular instruction files
│   │   ├── code-style.md
│   │   ├── testing.md
│   │   └── api-conventions.md
│   │
│   ├── skills/               # Auto-invoked workflows
│   │   ├── security-review/
│   │   │   └── SKILL.md
│   │   └── deploy/
│   │       └── SKILL.md
│   │
│   └── agents/               # Subagent personas
│       ├── code-reviewer.md
│       └── security-auditor.md
│
└── docs/superpowers/         # Superpowers plugin
    ├── plans/                #   Implementation plans
    └── specs/                #   Design specs
```
