---
layout: default
---

# Real CLAUDE.md example: Debugging methodology

**Example:** `~/.claude/CLAUDE.md` (Part 2)

```markdown
## Important - debugging and fixing
* When troubleshooting, ALWAYS identify root
  cause BEFORE fixing.
* Reproduce consistently
* PROVE THE PROBLEM FIRST - don't guess.
* Try one test at a time. Be methodical.
* Don't jump to conclusions.
* Don't apply workarounds.
```

**Result:** Claude debugs methodically, not reactively

<!--
PRESENTER NOTES:
Opening: "Part 2 defines the debugging approach - this is critical for avoiding rushed fixes."

Key points:
- Methodology over speed: Prove the problem before fixing
- Systematic approach: One test at a time, reproducible
- Avoid shortcuts: No guessing, no workarounds
- This prevents the "fix one bug, create two more" pattern

Example impact:
- Bug reported → Claude reproduces first, then fixes
- "PROVE FIRST" → Claude asks for reproduction steps
- "One test at a time" → Claude doesn't batch untested changes

Real scenario:
- Bad: "Try changing this line" (guessing)
- Good: "Let's add logging to confirm X, then fix based on evidence"

Transition: "With global config established, let's see the complete file structure."

Timing: 75 seconds
Word count: 40 words (code block) ✓
Element count: 1 example header + 1 code block (~4) + 1 result = 6 total ✓
-->
