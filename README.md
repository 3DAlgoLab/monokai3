# Monokai3 — A Slightly Brighter Monokai Pro

A VS Code color theme based on the Monokai Pro palette, with a subtle brightness lift for comfortable coding in slightly brighter environments.

## Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Background | █ | `#252425` |
| Red | █ | `#ff6e92` |
| Orange | █ | `#fca073` |
| Yellow | █ | `#ffdb72` |
| Green | █ | `#b0df81` |
| Cyan | █ | `#83dfea` |
| Purple | █ | `#b2a5f3` |
| White | █ | `#fcfcfa` |

## Install

### From VSIX

1. Download the latest `.vsix` file from the [Releases](../../releases) page (or build one with `npx vsce package`)
2. Open VS Code → **Extensions** (`Ctrl+Shift+X`)
3. Click **⋯ (menu)** → **Install from VSIX…**
4. Select the `monokai3-0.1.0.vsix` file

Or via terminal:

```bash
code --install-extension monokai3-0.1.0.vsix
```

### From Source

1. Clone this repo and open it in VS Code
2. Press `F5` (launch Extension Development Host)
3. Open **Color Theme** picker: `Ctrl+K Ctrl+T` (or `Cmd+K Cmd+T`)
4. Select **Monokai3**

After installing, open the **Color Theme** picker (`Ctrl+K Ctrl+T`) and select **Monokai3**.

## Features

- Full workbench color support (editor, sidebar, tabs, status bar, panels)
- TextMate syntax highlighting for TypeScript, JavaScript, Python, CSS, JSON, YAML, Markdown, and more
- Terminal ANSI color support
- Git diff highlighting
- Semantic token support

## License

MIT
