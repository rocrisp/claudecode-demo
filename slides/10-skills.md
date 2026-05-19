---
layout: default
---

# Skills enable reusable workflows across projects

**Two levels:**
- **Global:** `~/.claude/skills/` (all projects)
- **Project:** `.claude/skills/` (this project only)

**Example:** `.claude/skills/code-analyzer/SKILL.md`

```markdown
---
name: code-analyzer
description: Analyze code quality
---

Analyze $ARGUMENTS for:
- Quality issues
- Performance concerns
- Security vulnerabilities
```

<!--
PRESENTER NOTES:
Opening: "Skills work like CLAUDE.md - they can be global or project-specific."

Key points:
- Two levels: Global (~/.claude/skills/) available everywhere, project (.claude/skills/) local only
- Structure: Create subdirectory with SKILL.md + frontmatter
- Frontmatter: name, description define the skill
- $ARGUMENTS: Works same as commands

When to use which level:
- Global skills: Generic tools (code analyzer, test generator) - reuse across all projects
- Project skills: Project-specific workflows (this repo's deploy script)

Example: Put code-analyzer in ~/.claude/skills/ to analyze Python, JavaScript, Go - any language in any project

Transition: "Now let's compare commands and skills to know when to use each."

Timing: 75 seconds
Word count: 41 words (excluding title and code) ✓
Element count: 2 two-levels + 1 example + 1 code block (~4) = 6 total ✓
-->
