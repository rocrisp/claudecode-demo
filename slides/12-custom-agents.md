---
layout: default
---

# Agents are AI assistants with specialized tools and constraints

**Create:** `.claude/agents/reviewer.md`

```markdown
---
name: reviewer
description: Code review specialist
tools: Read, Glob, Grep
---

Review planning/PLAN.md and write 
feedback to planning/REVIEW.md
```

**Usage:** "Use the reviewer agent to carry out a review"

<!-- TODO: Visual opportunity - MEDIUM PRIORITY
Type: Diagram showing agent anatomy (frontmatter + instructions)
Suggestion: Annotated code block highlighting name, tools, instructions
Why: Shows the structure beginners need to understand
Element count: 1 create + 1 code block (~4) + 1 usage = 6 total ✓
-->

<!--
PRESENTER NOTES:
Opening: "Agents are like hiring a specialist - you define what they can do and what they should do."

Key points:
- Frontmatter: name identifies it, description explains purpose
- tools: Limits what the agent can access (Read, Glob, Grep = read-only)
- Instructions: What to do when invoked
- Delegation: You say "use reviewer agent", Claude invokes it

Agent architecture benefits:
- Isolation: Reviewer can't write files, only read and report
- Reusability: Define once, use anywhere
- Specialization: Each agent focused on one task

Example agents:
- reviewer: Code review
- generator: Scaffold new components
- security: Scan for vulnerabilities

Transition: "One agent is useful. Multiple agents working together is powerful."

Timing: 90 seconds
Word count: 38 words (excluding title and code) ✓
-->
