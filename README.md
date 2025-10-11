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
- **Claude Code Commands Marketplace** — community marketplace for Claude Code commands and plugins; add with `/plugin marketplace add ananddtyagi/claude-code-marketplace`. (ananddtyagi/claude-code-marketplace)
- **Claude Code Plugins (jeremylongshore)** — a marketplace-style repo bundling instruction-template plugins and MCP plugin packs, with install docs. (jeremylongshore/claude-code-plugins)
- **Docker Claude Plugins** — integrates Docker Desktop's **MCP Toolkit** as a Claude Code plugin to expose containerized MCP servers through Claude. (docker/claude-plugins)

## MCP Servers
- **Atlassian Remote MCP Server** — OAuth-secured remote MCP for Jira/Confluence (Claude setup + cloud endpoints).  
- **GitHub MCP Server (official)** — first-party server to read repos, manage issues/PRs, and automate workflows.  
- **Google Workspace MCP (community)** — Sheets/Drive/Gmail/Calendar/Docs/Slides/Tasks coverage with remote OAuth and 1-click Claude install.  
- **Notion MCP (official)** — hosted server with OAuth; designed for Claude/Cursor/etc.  
- **Supabase MCP Server (official)** — connect Claude to Supabase projects; HTTP/SSE transports and OAuth supported.

## Editor Plugins
- **Claude Code for JetBrains (Beta)** — official plugin for IntelliJ family (interactive diffs, selection context).  
- **Claude Code for VS Code (official)** — marketplace extension; inline diffs, real-time edits.  
- **claude-chat.nvim** — Neovim wrapper around the Claude Code CLI (shares file/selection context).  
- **claude-code.nvim** — Neovim integration built using Claude Code inside Neovim (community).  
- **claudecode.nvim** — Neovim IDE integration for Claude Code (pure Lua).  
- **Claude Code Chat (VS Code, community)** — GUI chat/front-end for Claude Code inside VS Code.

## Documentation & Learning Resources
- **Customize Claude Code with plugins (announcement)** — official intro to plugins (commands, agents, MCPs, hooks).  
- **Plugin marketplaces (guide)** — how to create/distribute marketplaces and team-install via `.claude/settings.json`.  
- **Connect Claude Code to tools via MCP** — official MCP integration guide for Claude Code.  
- **VS Code integration docs** — official docs for the VS Code extension.  
- **JetBrains integration docs** — official docs for JetBrains plugin.
