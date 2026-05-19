---
layout: default
---

# Plugins extend Claude with pre-built domain expertise

**Popular plugins:**
- `frontend-design` - UI/UX assistance
- `code-review` - Automated review
- `playwright` - Browser automation
- `atlassian` - Jira integration

**Setup Jira:**
```bash
claude plugin install atlassian@claude-plugins-official
```

<!-- TODO: Visual opportunity - MEDIUM PRIORITY
Type: Grid layout showing plugin icons/names
Suggestion: 2x2 grid with plugin names and use cases
Why: Visual organization of options
Element count: 4 plugin bullets + 1 install line + 1 diagram = 6 total ✓
-->

<!--
PRESENTER NOTES:
Opening: "Plugins are how Claude connects to external tools - they're the bridge to services like Jira, GitHub, and more."

Key points:
- Integration focus: Plugins connect Claude to external services
- Atlassian: The key plugin for this training - bundles Jira and Confluence
- Other plugins: frontend-design, code-review, playwright for other use cases
- Installation: One command to get full integration

Installation:
- claude plugin install atlassian@claude-plugins-official
- This bundles the MCP servers for Jira and Confluence

Why plugins matter: They package up the integration layer (MCP servers) in an easy-to-install format

Transition: "The atlassian plugin includes MCP servers. Let's see how MCP actually works."

Timing: 90 seconds
Word count: 31 words (excluding title) ✓
-->
