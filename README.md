# Claude CLI: Multi-Agent Workflows

A 17.5-minute training presentation on building multi-agent workflows with Claude Code.

## What's Covered

- **Foundation:** CLAUDE.md configuration
- **Connectivity:** Plugins and MCP
- **Customization:** Commands, Skills, Agents
- **Automation:** Hooks and integration

## Prerequisites

Install Slidev globally:

```bash
npm install -g @slidev/cli
```

Or use npx (no installation needed):

```bash
npx slidev --version
```

## Running the Presentation

Start the dev server:

```bash
slidev slides.md
```

Or with npx:

```bash
npx slidev slides.md
```

The presentation will open in your browser at `http://localhost:3030`

## Presenter Mode

Press `p` during the presentation to open presenter mode with:
- Speaker notes
- Next slide preview
- Timer

## Exporting

Export to PDF:

```bash
slidev export slides.md --output presentation.pdf
```

Export to PowerPoint:

```bash
slidev export slides.md --format pptx
```

## Presentation Structure

17 slides total (17.5 minutes @ ~1 min/slide):

1. Title
2. Why Multi-Agent Workflows
3. Global Configuration
4-5. CLAUDE.md Examples
6-7. Plugins & MCP Setup
8-11. Commands, Skills, and Comparison
12-13. Custom Agents
14. Hooks
15. Real-World Integration Example
16. Progressive Learning Path
17. Next Steps & Q&A

## Keyboard Shortcuts

- `Space` / `→` - Next slide
- `←` - Previous slide
- `p` - Presenter mode
- `o` - Slides overview
- `f` - Fullscreen
- `Esc` - Exit fullscreen/overview

## Built With

- [Slidev](https://sli.dev/) - Presentation framework
- Theme: Seriph
- Generated with Claude Code
