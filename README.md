# Origen AE — Claude Code Plugins

A marketplace of Claude Code plugins maintained by [Origen AE](https://github.com/origen-ae).

## Add this marketplace

In Claude Code VSCode extension → Manage Plugins → Marketplaces → paste:
```
origen-ae/claude-plugins
```

Or via CLI:
```
/plugin marketplace add origen-ae/claude-plugins
```

## Available plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [claude-agent-team](https://github.com/origen-ae/claude-agent-team) | Scaffolds a 7-agent dev team with 8-stage workflow, approval gates, and STATUS dashboard | `/plugin install claude-agent-team` |

## Update

Plugins are pinned to a specific commit SHA. To pick up new versions of a plugin, update the `sha` in `.claude-plugin/marketplace.json` and push.
