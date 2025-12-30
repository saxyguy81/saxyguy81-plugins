# saxyguy81 Claude Code Plugin Marketplace

A collection of Claude Code plugins by saxyguy81.

## Available Plugins

| Plugin | Description | Version |
|--------|-------------|---------|
| [realitycheck](https://github.com/saxyguy81/realitycheck) | Quality gate plugin that ensures Claude Code completes tasks fully before stopping | 0.1.0 |

## Installation

### Add This Marketplace

```bash
# Interactive
claude /plugin install

# Then select "Add marketplace" and enter:
# https://github.com/saxyguy81/saxyguy81-plugins
```

Or add to your `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": [
    "https://github.com/saxyguy81/saxyguy81-plugins"
  ]
}
```

### Install Plugins

```bash
# Install realitycheck
claude plugin install realitycheck@saxyguy81-plugins --scope user
```

## Plugin Development

To add a new plugin to this marketplace:

1. Create your plugin with a `.claude-plugin/plugin.json` manifest
2. Push to a GitHub repository
3. Add an entry to `plugins.json` in this repo
4. Submit a PR

## License

MIT
