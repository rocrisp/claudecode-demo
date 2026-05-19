---
layout: center
class: text-center
---

# Commands vs Skills: When to use each

| Feature | Commands | Skills |
|---------|----------|--------|
| **Scope** | Single project | Global or project |
| **Location** | `.claude/commands/` | `~/.claude/skills/`<br>`.claude/skills/` |
| **Config** | Simple markdown | Frontmatter + instructions |
| **Use case** | Quick shortcuts | Reusable workflows |

**Decision:** Start with commands, upgrade to skills when you need multi-project reuse

<!--
PRESENTER NOTES:
Opening: "Quick comparison to help you choose between commands and skills."

Key differences:
- Scope: Commands are always project-local, skills can be global
- Location: Commands in .claude/commands/, skills can be in ~/.claude/skills/ for global access
- Configuration: Commands are just markdown instructions, skills need frontmatter
- Use case: Commands for one-off project tasks, skills for workflows you'll reuse

Decision guide:
- Need it in one project only? → Command
- Will use across multiple projects? → Global skill
- Project-specific but complex? → Project skill

Real example:
- Command: "Review the API docs in /docs/api.md" (this project only)
- Global skill: "Analyze any code file for quality" (works everywhere)
- Project skill: "Deploy to our staging environment" (complex, but project-specific)

Transition: "Local extensions are useful, but real power comes from connecting to external tools like Jira."

Timing: 75 seconds
Word count: 15 words (excluding title and table) ✓
Element count: 1 table + 1 decision line = 2 total ✓
-->
