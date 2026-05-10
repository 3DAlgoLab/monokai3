# Monokai3 — A Slightly Brighter Monokai Pro

A VS Code color theme based on the Monokai Pro palette, with a subtle brightness lift for comfortable coding in slightly brighter environments.

## Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Background | <span style="background-color:#252425;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#252425` |
| Red | <span style="background-color:#ff6e92;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#ff6e92` |
| Orange | <span style="background-color:#fca073;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#fca073` |
| Yellow | <span style="background-color:#ffdb72;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#ffdb72` |
| Green | <span style="background-color:#b0df81;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#b0df81` |
| Cyan | <span style="background-color:#83dfea;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#83dfea` |
| Purple | <span style="background-color:#b2a5f3;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#b2a5f3` |
| White | <span style="background-color:#fcfcfa;display:inline-block;width:1.2em;height:1.2em;border:1px solid #ccc;border-radius:2px;"> </span> | `#fcfcfa` |

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
