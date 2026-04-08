# Claude Code Plugins Marketplace

A Claude Code marketplace for XrmToolBox, Dynamics 365 / Dataverse development tools, and skill authoring.

## Available Plugins

| Plugin | Skills | Description |
|--------|--------|-------------|
| **xrmtoolbox** | `plugin-dev`, `testing` | Build, deploy, pack, publish, scaffold tests, mock IOrganizationService, smoke tests, and UI testing for XrmToolBox plugins. |
| **skill-authoring** | `skill-authoring` | Create, write, and publish Claude Code skills to this marketplace. Scaffolding, best practices, CI/CD, and marketplace registration. |

## Installation

### 1. Add this marketplace

```bash
claude plugin marketplace add HurleySk/claude-plugins-marketplace
```

### 2. Install a plugin

```bash
claude plugin install xrmtoolbox
```

## Related

- [XrmToolBox Plugin Template](https://github.com/HurleySk/XrmToolBox-Plugin-Template) - GitHub template for scaffolding new plugins
- [XrmToolBox Testing Toolkit](https://github.com/HurleySk/xrmtoolbox-testing-toolkit) - Standalone test harness for plugin UI testing
- [claude-xrmtoolbox-skill](https://github.com/HurleySk/claude-xrmtoolbox-skill) - The plugin source repo
