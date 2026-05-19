---
layout: default
---

# Hooks trigger automated actions on events

**Add to** `.claude/settings.json`

```json
{
  "hooks": {
    "Stop": [{
      "type": "command",
      "command": "codex exec 'Review changes'"
    }]
  }
}
```

**Result:** When Claude stops, auto-review runs

<!-- TODO: Visual opportunity - MEDIUM PRIORITY
Type: Event → Trigger → Action flow diagram
Suggestion: Simple sequence: Stop Event → Hook Fires → Review Executes
Why: Shows the automatic trigger concept
Element count: 1 add-to + 1 code block (~3) + 1 result = 5 total ✓
-->

<!--
PRESENTER NOTES:
Opening: "Hooks automate actions based on events - like git hooks but for Claude workflows."

Key points:
- Events: Stop (most common), Start, Error
- Configuration: Add to .claude/settings.json
- Command: What to execute when event fires
- Use case: Ralph loop pattern for iterative development

Example workflow:
1. You work with Claude on code
2. You say "stop" or exit
3. Hook fires automatically
4. Runs codex review of all changes
5. Writes feedback to hook.md
6. Next session, you see the review

Real use: Continuous improvement - every session ends with automated review

When to use:
- Stop hooks: Code review, changelog updates, test runs
- Start hooks: Load project context, check dependencies
- Error hooks: Log issues, notify team

Transition: "You now have all the building blocks - let's recap the journey."

Timing: 90 seconds
Word count: 29 words (excluding title and code) ✓
-->
