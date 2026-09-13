# OpenPencil Skills — moved

The OpenPencil agent skill is now maintained alongside the editor, CLI, and MCP implementation in [open-pencil/open-pencil](https://github.com/open-pencil/open-pencil/tree/master/skills/open-pencil).

This repository is archived. Its skill files remain available for historical installations but no longer receive updates.

## Migrate

Install from the new canonical repository:

```bash
npx skills add open-pencil/open-pencil
```

The skill name remains **`open-pencil`**. Install into the same scope and agents as your existing installation; add `-g` if you previously installed globally. Confirm replacement if prompted, then use `npx skills list` (or `npx skills list -g`) to check the installation.

Existing installations do not automatically switch repositories. Reinstall from the new source before relying on future `npx skills update` runs.

## Contribute

Submit skill changes and issues to [open-pencil/open-pencil](https://github.com/open-pencil/open-pencil). The canonical source is `skills/open-pencil/`; agent-facing implementation, documentation, prompts, and skill examples are maintained together.

[OpenPencil documentation](https://openpencil.dev) · [CLI](https://www.npmjs.com/package/@open-pencil/cli) · [MCP server](https://www.npmjs.com/package/@open-pencil/mcp)
