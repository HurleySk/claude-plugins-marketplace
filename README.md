# Claude Code Plugins Marketplace

A Claude Code marketplace for XrmToolBox, Dynamics 365 / Dataverse development, data migration analysis, terminal UI design, skill authoring, and productivity extensions.

## Available Plugins

| Plugin | Skills | Description |
|--------|--------|-------------|
| **xrmtoolbox** | `plugin-dev`, `testing`, `ui-review` | Build, deploy, pack, publish, scaffold tests, mock IOrganizationService, smoke tests, UI testing, and UI best practices review for XrmToolBox plugins. |
| **skill-authoring** | `skill-authoring`, `skill-review` | Create, write, and publish Claude Code skills to this marketplace. Scaffolding, best practices, CI/CD, marketplace registration, and comprehensive skill quality assessment. |
| **knbn** | `knbn`, `knbn-join`, `knbn-status` | Track work across multiple Claude Code CLI instances via a VS Enterprise kanban board. Register work items, smart-join existing cards, and post status updates. |
| **sherlock** | `migration-analyst`, `mapping-guide`, `lineage-tracer` | Domain analyst skills for ETL/data migration — mapping document generation, data lineage tracing with column-level precision. |
| **terminal-ui-design** | `terminal-ui-design` | Design polished terminal UIs — guided design workflows, CLI output auditing, refactoring with box drawing, color, typography, animation, and data visualization. |

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
