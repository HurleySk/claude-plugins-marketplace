# Claude Code Plugins Marketplace

A Claude Code marketplace for XrmToolBox and Dynamics 365 / Dataverse development tools.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **xrmtoolbox-plugin-dev** | Skill for building XrmToolBox plugins. Scaffolding, architecture guidance, packaging, deployment, and publishing to the XrmToolBox Tool Store. |
| **xrmtoolbox-testing** | Skill for testing XrmToolBox plugins. Test scaffolding, mock IOrganizationService, smoke tests, and UI testing via [Test Harness](https://github.com/HurleySk/xrmtoolbox-testing-toolkit) + FlaUI-MCP. |

## Installation

### 1. Add this marketplace

```bash
claude plugin marketplace add HurleySk/claude-plugins-marketplace
```

### 2. Install a plugin

```bash
claude plugin install xrmtoolbox-plugin-dev
```

## Related

- [XrmToolBox Plugin Template](https://github.com/HurleySk/XrmToolBox-Plugin-Template) - GitHub template for scaffolding new plugins
- [claude-xrmtoolbox-skill](https://github.com/HurleySk/claude-xrmtoolbox-skill) - The plugin source repo
