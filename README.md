# taugr — AI plugins

A personal collection of plugins and integrations I build for AI tools.

Today it ships a **Claude Code** plugin marketplace. Support for other tools
(OpenAI Codex, Cursor) is planned and will be MCP-based — see [Other tools](#other-tools).

## Claude Code

The flagship: a Claude Code plugin marketplace.

### Add the marketplace

```
/plugin marketplace add taugr/taugr-marketplace
```

### Install a plugin

```
/plugin install climatenet@taugr
```

### Plugins

| Plugin | Description | Source |
| ------ | ----------- | ------ |
| `climatenet` | Query ClimateNet environmental monitoring data from Armenia — devices, sensors, readings, and comparisons. | [taugr/climatenet-mcp](https://github.com/taugr/climatenet-mcp/tree/main/plugin) |

### Updating

After I push changes here, refresh your local copy:

```
/plugin marketplace update taugr
```

## Other tools

Codex and Cursor don't use a plugin marketplace — they connect to MCP servers
directly. Setup for those is planned and will point at the same hosted MCP
endpoints (e.g. the ClimateNet server at `https://climatenet-mcp.tomauger.am/mcp`).
Coming soon.
