# Baldwin Sung

Small, single-purpose tools, mostly built with [Claude Code](https://claude.com/claude-code).

## MCP servers

| Server | Tools |
|---|---|
| [online-presence](https://github.com/baldwinsung/online-presence) | Domain registration, hosting provider, TLS certificate, IP holder + abuse contacts (`ip_info`) |
| [mcp-servers](https://github.com/baldwinsung/mcp-servers) | Weather, cloud-app outage status, internet-exchange status |

Hosted at `https://mcp.baldwinsung.com`, for example:

```bash
claude mcp add --transport http onlinepresence https://mcp.baldwinsung.com/onlinepresence
```

## Terminal tools

| Tool | What it does |
|---|---|
| [cisco-tui](https://github.com/baldwinsung/cisco-tui) | Terminal UI to apply/remove interface ACLs and save config on Cisco IOS |
| [claude-statusline](https://github.com/baldwinsung/claude-statusline) | Two-line Claude Code status line: git repo and branch, context window, 5-hour and weekly usage with reset countdowns and pace |
| [online-presence](https://github.com/baldwinsung/online-presence) | `onlinepresence example.com`: registration, hosting and TLS certificate for a domain; `onlinepresence 8.8.8.8`: IP holder and abuse contacts |

## macOS menu bar apps

| App | What it does |
|---|---|
| [proxy-menubar](https://github.com/baldwinsung/proxy-menubar) | Current proxy and egress IP, plus diagnostics: PAC fetch and evaluation, proxy reachability, egress check |
| [toner-menubar](https://github.com/baldwinsung/toner-menubar) | Discovers network printers; toner, trays and page counts via SNMP |

Install both: `curl -fsSL https://raw.githubusercontent.com/baldwinsung/homebrew-tap/main/install-menubar-apps.sh | bash`

Install and uninstall scripts live in [homebrew-tap](https://github.com/baldwinsung/homebrew-tap).

## Other

| Repo | What it does |
|---|---|
| [chatgpt-cleaner](https://github.com/baldwinsung/chatgpt-cleaner) | Browser console script to bulk-delete chatgpt.com history |
| [nyc-pied-tax](https://github.com/baldwinsung/nyc-pied-tax) | Search index over NYC's public supplemental market value roll |
