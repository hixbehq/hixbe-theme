<p align="center">
  <img alt="Hixbe Logo" src="https://raw.githubusercontent.com/hixbehq/hixbe-theme/main/images/logo.png" width="100" />
</p>
<h1 align="center">
  Hixbe Theme for VS Code
</h1>
<p align="center">
  A minimal, dark blue theme for <a href="https://theme.hixbe.com/">VS Code, Sublime Text, Atom, and more</a>.
</p>
<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=hixbehq.hixbe-theme">
    <img alt="Version" src="https://img.shields.io/visual-studio-marketplace/v/hixbehq.hixbe-theme?color=brightgreen" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=hixbehq.hixbe-theme">
    <img alt="Downloads" src="https://img.shields.io/visual-studio-marketplace/d/hixbehq.hixbe-theme" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=hixbehq.hixbe-theme">
    <img alt="Installs" src="https://img.shields.io/visual-studio-marketplace/i/hixbehq.hixbe-theme" />
  </a>
</p>

![demo](https://raw.githubusercontent.com/hixbehq/hixbe-theme/master/images/demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Hixbe`
3. Click **Install** to install it
4. Click **Reload** to reload the editor
5. Code > Preferences > Color Theme > **Hixbe**

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://github.com/hixbehq/hixbe-theme/blob/master/vsc-extension-quickstart.md)

## Icon Theme

The file icon theme seen in the screenshot above is [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) with these settings:

```json
  "material-icon-theme.folders.color": "#8695b7",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
```

## Color Reference

### Syntax Colors

|                               Color                                | Usage                                           |
| :----------------------------------------------------------------: | ----------------------------------------------- |
| ![#c3a6ff](https://placehold.co/10x10/c3a6ff/FFF) `#c3a6ff` | Keywords, constants, template literals          |
| ![#ffd580](https://placehold.co/10x10/ffd580/FFF) `#ffd580` | Functions, classes, object literal keys         |
| ![#ffae57](https://placehold.co/10x10/ffae57/FFF) `#ffae57` | Constants, operators                            |
| ![#bae67e](https://placehold.co/10x10/bae67e/FFF) `#bae67e` | Strings, markdown headings                      |
| ![#5ccfe6](https://placehold.co/10x10/5ccfe6/FFF) `#5ccfe6` | Special keywords, classes, markdown code blocks |
| ![#a2aabc](https://placehold.co/10x10/a2aabc/FFF) `#a2aabc` | Variables, property names, tags                 |

### UI Colors

|                               Color                                | Usage                                      |
| :----------------------------------------------------------------: | ------------------------------------------ |
| ![#171c28](https://placehold.co/10x10/171c28/FFF) `#171c28` | Workbench background                       |
| ![#1d2433](https://placehold.co/10x10/1d2433/FFF) `#1d2433` | Editor background                          |
| ![#2f3b54](https://placehold.co/10x10/2f3b54/FFF) `#2f3b54` | Highlight, widgets, panels                 |
| ![#6679a4](https://placehold.co/10x10/6679a4/FFF) `#6679a4` | Dividers, subtle UI elements               |
| ![#8695b7](https://placehold.co/10x10/8695b7/FFF) `#8695b7` | Status bar text, buttons, etc              |
| ![#d7dce2](https://placehold.co/10x10/d7dce2/FFF) `#d7dce2` | Active text, anything that should be white |
| ![#ffcc66](https://placehold.co/10x10/ffcc66/FFF) `#ffcc66` | Accent, list tree titles, badges, etc      |
| ![#bae67e](https://placehold.co/10x10/bae67e/FFF) `#bae67e` | Addition highlights                        |
| ![#ef6b73](https://placehold.co/10x10/ef6b73/FFF) `#ef6b73` | Deletion highlights, errors, warnings      |
| ![#5ccfe6](https://placehold.co/10x10/5ccfe6/FFF) `#5ccfe6` | Modified highlights                        |

## Theming Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

Syntax & Workbench colors based on [Ayu Mirage Theme](https://github.com/teabyii/vscode-ayu)

```bash
vsce publish patch/minor/major
```

## Shameless Plug

Hixbe is also available for [Sublime Text, Atom](https://theme.hixbe.com/).
