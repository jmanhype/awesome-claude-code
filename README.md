# Awesome Claude Code

A list of Claude Code plugins, MCP servers, editor integrations, and learning resources.

## Status

| Metric | Value |
|--------|------|
| Plugins listed | 5 |
| MCP servers | 5 |
| Editor integrations | 6 |
| Learning resources | 5 |
| Last updated | 2026-Q2 |

## Installation

```bash
# Add a marketplace
/plugin marketplace add <owner>/<repo>

# Install a specific plugin
/plugin install <owner>/<repo>
```

## Plugins & Extensions

| Name | Maintainer | Description |
|------|------------|-------------|
| [Claude Code Commands Marketplace](https://github.com/ananddtyagi/claude-code-marketplace) | ananddtyagi | Community marketplace for commands and plugins |
| [Claude Code Plugins](https://github.com/jeremylongshore/claude-code-plugins) | jeremylongshore | Instruction-template plugins and MCP plugin packs |
| [Multi-Agent Intelligence Marketplace](https://github.com/jmanhype/claude-code-plugins) | jmanhype | 19 plugins for trading, swarm intelligence, GitHub automation |
| [Docker Claude Plugins](https://github.com/docker/claude-plugins) | Docker | Exposes containerized MCP servers via Docker Desktop |
| [Perseus](https://github.com/tcconnally/perseus) | tcconnally | Live context engine — resolves @query/@services/@waypoint directives into CLAUDE.md before session start. Hook installer for `.claude/settings.json`. |

## MCP Servers

| Name | Auth | Coverage |
|------|------|----------|
| [Atlassian Remote MCP](https://developer.atlassian.com/platform/model-context-protocol/) | OAuth | Jira, Confluence |
| [GitHub MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/github) | Token | Repos, issues, PRs, workflows |
| [Google Workspace MCP](https://github.com/aekanun2020/Google-MCP-Servers) | OAuth | Sheets, Drive, Gmail, Calendar, Docs, Slides, Tasks |
| [Notion MCP](https://www.notion.so/help/add-and-manage-connections-with-the-api#mcp) | OAuth | Notion workspaces |
| [Supabase MCP](https://supabase.com/blog/supabase-mcp) | OAuth / HTTP | Supabase projects |

## Editor Integrations

| Editor | Name | Source | Notes |
|--------|------|--------|-------|
| VS Code | [Claude Code](https://marketplace.visualstudio.com/items?itemName=Anthropic.claude-code) | Anthropic (official) | Inline diffs, real-time edits |
| VS Code | [Claude Code Chat](https://marketplace.visualstudio.com/items?itemName=nishant.claude-code-chat) | Community | GUI chat front-end |
| JetBrains | [Claude Code](https://plugins.jetbrains.com/plugin/26099-claude-code) | Anthropic (official, beta) | Interactive diffs, selection context |
| Neovim | [claude-chat.nvim](https://github.com/ribru17/claude-chat.nvim) | Community | CLI wrapper, shares file/selection context |
| Neovim | [claude-code.nvim](https://github.com/greggh/claude-code.nvim) | Community | Full integration inside Neovim |
| Neovim | [claudecode.nvim](https://github.com/coder/claudecode.nvim) | Coder | Pure Lua IDE integration |

## Learning Resources

| Title | Type |
|-------|------|
| [Customize Claude Code with plugins](https://www.anthropic.com/news/customize-claude-code-with-plugins) | Official announcement (commands, agents, MCPs, hooks) |
| [Plugin marketplaces](https://docs.claude.com/en/docs/claude-code/plugins#plugin-marketplaces) | Guide: create/distribute marketplaces, team install via `.claude/settings.json` |
| [Connect Claude Code to tools via MCP](https://docs.claude.com/en/docs/claude-code/mcp) | Official MCP integration guide |
| [VS Code integration](https://docs.claude.com/en/docs/claude-code/vs-code) | Official VS Code extension docs |
| [JetBrains integration](https://docs.claude.com/en/docs/claude-code/jetbrains) | Official JetBrains plugin docs |

## Limitations

- This list tracks the Claude Code ecosystem, which is still early-stage. Many plugins are experimental.
- Plugin compatibility can break across Claude Code versions.
- Not all MCP servers have been tested against the latest release.
- Community editor integrations vary in maturity and maintenance cadence.

## Contributing

See [contributing.md](contributing.md).

## License

MIT