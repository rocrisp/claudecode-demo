---
layout: default
---

# Custom commands provide project-specific shortcuts

**Create:** `commands/doc-review.md`

```markdown
Review the documentation file called $ARGUMENTS 
and add feedback to a new section
```

**Usage:** `/doc-review myfile.md`

**When to use:** Simple, single-project tasks

<!-- TODO: Visual opportunity - LOW PRIORITY
Type: Code snippet with syntax highlighting
Note: Already using code block above
Element count: 1 create line + 1 code block (~3) + 1 usage + 1 when = 6 total ✓
-->

<!--
PRESENTER NOTES:
Opening: "Commands are the simplest customization - think of them as bash aliases for Claude."

Key points:
- Create: Just put a markdown file in commands/ directory
- $ARGUMENTS: Gets replaced with what you type after the command
- Usage: Type /doc-review myfile.md and Claude follows the instructions
- When: Use for simple, repetitive tasks specific to this project

Example use cases:
- /code-review - Review all changed files
- /test-plan - Generate test plan from spec
- /changelog - Update CHANGELOG.md with recent commits

Limitation: Commands are project-specific. For reusable workflows, use skills next.

Transition: "Commands work for one project, but skills work everywhere."

Timing: 90 seconds
Word count: 28 words (excluding title and code) ✓
-->
