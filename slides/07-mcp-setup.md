---
layout: default
---

# MCP connects Claude to GitHub

**Setup GitHub:**
```bash
claude mcp add-json github \
  '{"type":"http","url":"https://api.githubcopilot.com/mcp",
    "headers":{"Authorization":"Bearer YOUR_PAT"}}' \
  --scope user
```

**Key:** `--scope user` makes it global (all projects)

<!-- TODO: Visual opportunity - HIGH PRIORITY
Type: mermaid architecture diagram
Suggestion: Claude CLI ↔ MCP ↔ [Jira, GitHub]
Why: Shows connection architecture
Element count: 2 setup sections + 2 code blocks (~4) + 1 key = 6 total ✓
-->

<!--
PRESENTER NOTES:
Opening: "MCP - Model Context Protocol - connects Claude to external services."

Key points:
- Jira: One command via atlassian plugin (easiest)
- GitHub: Requires PAT token from github.com/settings/tokens
- --scope user: Configures globally in ~/.claude.json, works in all projects
- These are one-time setups

Example workflows enabled:
- "Create a Jira ticket for this bug" - Claude talks to Jira via MCP
- "Show me open PRs" - Claude queries GitHub via MCP
- "Link this commit to PROJ-123" - Cross-service integration

Benefit: No context switching, no manual ticket creation, seamless workflow

Transition: "Let's see this in action with a real workflow."

Timing: 90 seconds
Word count: 21 words (excluding title and code) ✓
-->
