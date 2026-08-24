# Logitropic Plugins Directory

**Repository:** [logitropic/conductor](https://github.com/logitropic/conductor)

A curated directory of plugins for Claude Code.

> **Important:** Make sure to trust a plugin before installing, updating, or using it. Review the plugin source code and understand what permissions it requires.

## Structure

- **`.claude-plugin/`** - Plugin marketplace manifest
  - `marketplace.json` - Plugin registry defining available plugins and their sources

## Available Plugins

### Conductor

**Category:** Coding

Conductor is a set of modular AI agent skills for Claude Code that enables Spec-Driven Development to specify, plan, and implement software features.

- **Source:** [gemini-cli-extensions/conductor](https://github.com/gemini-cli-extensions/conductor) (external repository, plugin at repo root)
- **Homepage:** [https://github.com/gemini-cli-extensions/conductor](https://github.com/gemini-cli-extensions/conductor)

## Installation

First, add this marketplace to Claude Code:

```
claude plugin marketplace add https://github.com/logitropic/claude-plugins.git
```

Plugins can then be installed directly from this marketplace via Claude Code's plugin system.

To install, run:
```
/plugin install conductor@logitropic-plugins
```

Or browse for the plugin in `/plugin > Discover`

## License

Please see each linked plugin repository for the relevant LICENSE file.

## Documentation

For more information on developing Claude Code plugins, see the [official documentation](https://code.claude.com/docs/en/plugins).
