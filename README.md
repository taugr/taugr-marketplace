# taugr — AI plugins

A personal collection of plugins and integrations I build for AI tools.

Today it ships a **Claude Code** plugin marketplace. Support for other tools
(OpenAI Codex, Cursor) is planned.

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
