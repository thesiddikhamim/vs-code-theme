# OLED VSCode Theme

Pure **OLED black** (`#000000`) UI with the exact **VS Code Dark+** syntax colour palette.

## Colour Reference

| Token | Colour | Use |
|---|---|---|
| Keywords | `#569cd6` | `if` `for` `class` `return` |
| Control flow | `#c586c0` | `import` `export` `async` `await` |
| Types / Classes | `#4ec9b0` | Class names, interfaces |
| Functions | `#dcdcaa` | Function definitions & calls |
| Variables | `#9cdcfe` | Variables, parameters, properties |
| Constants | `#4fc1ff` | `true` `false` `null` enum members |
| Strings | `#ce9178` | All string literals |
| Numbers | `#b5cea8` | Numeric literals |
| Comments | `#6a9955` | Line & block comments |
| Operators | `#d4d4d4` | `+ - * / = < >` |
| Regex | `#d16969` | Regular expressions |

## Install from folder (dev / personal use)

```bash
# 1. Copy the folder to your extensions directory
cp -r oled-vscode-theme ~/.vscode/extensions/

# 2. Restart VS Code, then:
#    Command Palette → "Color Theme" → "OLED VSCode"
```

## Build a VSIX with vsce

```bash
npm install -g @vscode/vsce
cd oled-vscode-theme
vsce package
# → oled-vscode-theme-1.0.0.vsix

# Install the VSIX
code --install-extension oled-vscode-theme-1.0.0.vsix
```
