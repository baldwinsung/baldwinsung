# Baldwin Sung

Small, single-purpose tools, mostly built with [Claude Code](https://claude.com/claude-code).

## macOS menu bar apps

| App | What it does |
|---|---|
| [claude-menubar](https://github.com/baldwinsung/claude-menubar) | Current Claude Code session usage and when it resets. `brew install --cask baldwinsung/tap/simpleclaudemenubar` |
| [dns-menubar](https://github.com/baldwinsung/dns-menubar) | Switches DNS servers based on the Wi-Fi network |
| [proxy-menubar](https://github.com/baldwinsung/proxy-menubar) | Your current proxy IP address at a glance |
| [toner-menubar](https://github.com/baldwinsung/toner-menubar) | Discovers network printers; toner, trays and page counts via SNMP |
| [whois-menubar](https://github.com/baldwinsung/whois-menubar) | Bulk WHOIS / geo lookups for IP addresses |

Installable apps are published through [homebrew-tap](https://github.com/baldwinsung/homebrew-tap).

## Terminal tools

| Tool | What it does |
|---|---|
| [cisco-tui](https://github.com/baldwinsung/cisco-tui) | Terminal UI to apply/remove interface ACLs and save config on Cisco IOS |
| [online-presence](https://github.com/baldwinsung/online-presence) | `onlinepresence example.com`: registration, hosting provider and TLS certificate for a domain |

## MCP servers

| Server | Tools |
|---|---|
| [online-presence](https://github.com/baldwinsung/online-presence) | Domain registration, hosting provider, TLS certificate |
| [mcp-servers](https://github.com/baldwinsung/mcp-servers) | Weather, cloud-app outage status, internet-exchange status |

Hosted at `https://mcp.baldwinsung.com`, for example:

```bash
claude mcp add --transport http onlinepresence https://mcp.baldwinsung.com/onlinepresence
```

## Other

| Repo | What it does |
|---|---|
| [chatgpt-cleaner](https://github.com/baldwinsung/chatgpt-cleaner) | Browser console script to bulk-delete chatgpt.com history |
| [nyc-pied-tax](https://github.com/baldwinsung/nyc-pied-tax) | Search index over NYC's public supplemental market value roll |
