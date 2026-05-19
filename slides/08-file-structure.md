---
layout: default
---

# Create custom commands, skills, and agents

```
.claude/
  agents/        # Specialized AI assistants
  commands/      # Manual execution
  skills/        # Automatic execution
```

**Next:** Fill these folders with custom functionality

<!-- TODO: Visual opportunity - MEDIUM PRIORITY
Type: Directory tree (code block or mermaid)
Suggestion: Expanded tree showing example files in each directory
Why: Shows concrete examples of what goes where
Element count: 1 code block (~3) + 1 text line = 4 total ✓
-->

<!--
PRESENTER NOTES:
Opening: "Claude CLI uses a simple three-folder structure for all customization."

Key points:
- .claude/agents/ - Define custom AI agents with specific tools
- .claude/commands/ - Simple project-specific shortcuts (like bash aliases)
- .claude/skills/ - More powerful workflows that work across projects

Example file locations:
- .claude/agents/reviewer.md
- .claude/commands/doc-review.md
- .claude/skills/code-analyzer/SKILL.md

Note: We simplified from outline (removed settings.json mention, saving for hooks slide)

Transition: "Let's start filling these folders, beginning with the simplest: commands."

Timing: 60 seconds
Word count: 19 words (excluding title and code) ✓
-->
