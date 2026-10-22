# Mytets plugin

Ukrainian theatrical absurd communication style plugin for Claude Code and Codex, inspired by Les Podervyansky's dramatic works. Both use the same skill in `skills/mytets-mode/`.

## Installation

### Claude Code: local testing

```bash
claude --plugin-dir ~/Workspace/projects/r.rader/mytets
```

### Claude Code: install from GitHub marketplace

1. Add the marketplace:
```bash
/plugin marketplace add rrader/mytets
```

2. Install the plugin:
```bash
/plugin install mytets
```

3. Restart Claude Code to load the plugin

### Codex: install from GitHub marketplace

```bash
codex plugin marketplace add rrader/mytets
codex plugin add mytets@mytets-marketplace
```

If you already added the marketplace, refresh it before installing:

```bash
codex plugin marketplace upgrade mytets-marketplace
codex plugin add mytets@mytets-marketplace
```

Restart Codex after installation. In the desktop plugin directory, select the Mytets marketplace and install Mytets.

### Codex: local testing

From this repository's root:

```bash
codex plugin marketplace add .
codex plugin add mytets@mytets-marketplace
```

Check discovery with `codex plugin list --marketplace mytets-marketplace`.

## Usage

### Activate MYTETS mode

In Claude Code:

```
/mytets:mytets-mode
```

In Codex:

```text
$mytets-mode
```

You can also ask to activate MYTETS mode in natural language. If you include a question or task, the agent answers it in the same response.

## Inspiration

Based on the theatrical works of Les Podervyansky, particularly "Pavlik Morozov".
