# awesome-claude-code
🎨 Awesome list of Claude Code plugins, MCP servers, editor integrations, and resources

## How to use

Many resources can be installed directly via Claude Code commands:
```bash
# Add a marketplace
/plugin marketplace add ananddtyagi/claude-code-marketplace

# Install a specific plugin
/plugin install <owner>/<repo>
```

## Plugins & Extensions
- **[Claude Code Commands Marketplace](https://github.com/ananddtyagi/claude-code-marketplace)** — community marketplace for Claude Code commands and plugins; add with `/plugin marketplace add ananddtyagi/claude-code-marketplace`.
- **[Claude Code Plugins (jeremylongshore)](https://github.com/jeremylongshore/claude-code-plugins)** — a marketplace-style repo bundling instruction-template plugins and MCP plugin packs, with install docs.
- **[Docker Claude Plugins](https://github.com/docker/claude-plugins)** — integrates Docker Desktop's **MCP Toolkit** as a Claude Code plugin to expose containerized MCP servers through Claude.

## MCP Servers
- **[Atlassian Remote MCP Server](https://developer.atlassian.com/platform/model-context-protocol/)** — OAuth-secured remote MCP for Jira/Confluence (Claude setup + cloud endpoints).
- **[GitHub MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/github)** (official) — first-party server to read repos, manage issues/PRs, and automate workflows.
- **[Google Workspace MCP](https://github.com/aekanun2020/Google-MCP-Servers)** (community) — Sheets/Drive/Gmail/Calendar/Docs/Slides/Tasks coverage with remote OAuth and 1-click Claude install.
- **[Notion MCP](https://www.notion.so/help/add-and-manage-connections-with-the-api#mcp)** (official) — hosted server with OAuth; designed for Claude/Cursor/etc.
- **[Supabase MCP Server](https://supabase.com/blog/supabase-mcp)** (official) — connect Claude to Supabase projects; HTTP/SSE transports and OAuth supported.

## Editor Plugins
- **[Claude Code for JetBrains](https://plugins.jetbrains.com/plugin/26099-claude-code)** (Beta) — official plugin for IntelliJ family (interactive diffs, selection context).
- **[Claude Code for VS Code](https://marketplace.visualstudio.com/items?itemName=Anthropic.claude-code)** (official) — marketplace extension; inline diffs, real-time edits.
- **[claude-chat.nvim](https://github.com/ribru17/claude-chat.nvim)** — Neovim wrapper around the Claude Code CLI (shares file/selection context).
- **[claude-code.nvim](https://github.com/greggh/claude-code.nvim)** — Neovim integration built using Claude Code inside Neovim (community).
- **[claudecode.nvim](https://github.com/coder/claudecode.nvim)** — Neovim IDE integration for Claude Code (pure Lua).
- **[Claude Code Chat](https://marketplace.visualstudio.com/items?itemName=nishant.claude-code-chat)** (VS Code, community) — GUI chat/front-end for Claude Code inside VS Code.

## Documentation & Learning Resources
- **[Customize Claude Code with plugins](https://www.anthropic.com/news/customize-claude-code-with-plugins)** (announcement) — official intro to plugins (commands, agents, MCPs, hooks).
- **[Plugin marketplaces](https://docs.claude.com/en/docs/claude-code/plugins#plugin-marketplaces)** (guide) — how to create/distribute marketplaces and team-install via `.claude/settings.json`.
- **[Connect Claude Code to tools via MCP](https://docs.claude.com/en/docs/claude-code/mcp)** — official MCP integration guide for Claude Code.
- **[VS Code integration docs](https://docs.claude.com/en/docs/claude-code/vs-code)** — official docs for the VS Code extension.
- **[JetBrains integration docs](https://docs.claude.com/en/docs/claude-code/jetbrains)** — official docs for JetBrains plugin.
