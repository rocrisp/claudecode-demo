---
layout: default
---

# Define agents globally or per-project

**Two levels:**
- **Global:** `~/.claude/agents/` (all projects)
- **Project:** `.claude/agents/` (this project only)

**Examples:**
- Global: code-analyzer, security-scanner
- Project: deploy-to-staging, custom-reviewer

<!--
PRESENTER NOTES:
Opening: "Just like commands and skills, agents can be global or project-specific."

Key points:
- Two levels: Global (~/.claude/agents/) available everywhere, project (.claude/agents/) local only
- Global agents: Generic specialists (code analysis, security scanning) - reuse across all projects
- Project agents: Codebase-specific (deployment scripts, custom review workflows)

When to use which level:
- Global: Generic tasks that apply to any codebase (linting, formatting, security checks)
- Project: Tasks tied to this repo's structure, tools, or workflows

Example: Put security-scanner in ~/.claude/agents/ to scan Python, JavaScript, Go - any language in any project. But deploy-to-staging knows your specific deployment pipeline, so it stays in .claude/agents/.

Transition: "Now let's see how multiple agents work together."

Timing: 75 seconds
Word count: 31 words (excluding title) ✓
Element count: 2 two-levels + 4 examples = 6 total ✓
-->
