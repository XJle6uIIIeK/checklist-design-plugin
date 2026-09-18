# Checklist Design plugin for Codex

This repository packages the `checklist-design` Agent Skill as a Codex plugin and as an installable Codex marketplace source.

## Included

- `.agents/plugins/marketplace.json` — Codex marketplace manifest
- `.codex-plugin/plugin.json` — plugin manifest
- `skills/checklist-design/SKILL.md` — skill instructions
- `skills/checklist-design/references/` — bundled Checklist Design reference material
- `skills/checklist-design/agents/openai.yaml` — skill UI metadata

No MCP server, app connector, hook, or network dependency is required.

## Add as a marketplace in Codex

Use this repository as the marketplace source:

`https://github.com/XJle6uIIIeK/checklist-design-plugin`

Use Git ref `main`.

Leave **Selective paths** empty so Codex can read both `.agents/plugins/marketplace.json` and the plugin files at the repository root.

After the marketplace is added, install the `checklist-design` plugin from it.

## Clone manually

```bash
git clone https://github.com/XJle6uIIIeK/checklist-design-plugin.git
```
