# Spec-Driven Development & Context Engineering for AI Coding Agents

Archcore is a git-native context layer for AI coding agents. Keep specs, architecture, decisions, rules, and plans in your repository and make the relevant project context available across Claude Code, Cursor, Codex, GitHub Copilot, Gemini CLI, and other MCP-compatible agents.

> Specs define intent. Context preserves understanding. Agents write the code.

## Repositories

| Repository | What it is |
| --- | --- |
| [cli](https://github.com/archcore-ai/cli) | Git-native project context and MCP infrastructure for AI coding agents. Owns `.archcore/`, the typed documents, the local MCP server, hooks, and agent integrations. |
| [plugin](https://github.com/archcore-ai/plugin) | Spec-driven development and context engineering inside your coding agent. Skills, slash commands, intent routing, gated tracks, review, and guardrails on Claude Code, Cursor, Codex CLI, and GitHub Copilot CLI. |

CLI = context infrastructure. Plugin = the command surface and guardrails. Archcore = one product system. Both read and write the same `.archcore/` directory; which one you use is decided by the agent you run, not by a recommendation.

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
