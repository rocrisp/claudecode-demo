---
layout: default
---

# CLAUDE.md sets consistent behavior across all projects

**Two levels:**
- **Global:** `~/.claude/CLAUDE.md` (foundation for everything)
- **Project:** `[project]/CLAUDE.md` (optional overrides)

**Hierarchy:** Global → Project (project wins)

<!-- TODO: Visual opportunity - HIGH PRIORITY
Type: Hierarchy diagram
Suggestion: Show ~/.claude/CLAUDE.md → [project]/CLAUDE.md with override arrow
Why: Visual hierarchy shows inheritance and override pattern
Element count: 1 two-levels + 3 bullets + 1 hierarchy + 1 diagram = 6 total ✓
-->

<!--
PRESENTER NOTES:
Opening: "CLAUDE.md works like gitconfig - global defaults that any project can override."

Key points:
- Two levels: Global (home directory) and Project (repo root)
- Hierarchy: Global settings apply everywhere, project overrides when needed
- Example global: "Use uv for Python", "Never use emojis in code", "Prefer small functions"
- Example override: Global says "4 spaces", one project needs tabs → project CLAUDE.md wins

Real example:
- Global ~/.claude/CLAUDE.md: "Always use TypeScript strict mode"
- Applied to all projects automatically
- Special legacy project: Add CLAUDE.md with "Use TypeScript loose mode" → overrides

This is the foundation. Set it up once, customize per-project only when needed.

Transition: "Now let's see the complete file structure."

Timing: 90 seconds
Word count: 28 words (excluding title) ✓
-->
