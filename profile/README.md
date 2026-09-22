# Spec-Driven Development & Context Engineering for AI Coding Agents

Archcore is a git-native context layer for AI coding agents. Keep specs, architecture, decisions, rules, and plans in your repository and make the relevant project context available across Claude Code, Cursor, Codex, GitHub Copilot, Gemini CLI, and other MCP-compatible agents.

> Specs define intent. Context preserves understanding. Agents write the code.

## Start

```bash
curl -fsSL https://archcore.ai/install.sh | bash    # macOS / Linux
cd your-project && archcore init
```

On Windows: `irm https://archcore.ai/install.ps1 | iex`

`archcore init` scaffolds `.archcore/`, detects your coding agents, and wires up hooks and MCP for them.

## Links

- [archcore.ai](https://archcore.ai) — website
- [docs.archcore.ai](https://docs.archcore.ai) — documentation
- [Learn](https://archcore.ai/learn/) — reference explainers on project context and context engineering
