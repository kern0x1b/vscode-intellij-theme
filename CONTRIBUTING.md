# Contributing

Thanks for considering a contribution — bug reports, theme tweaks, and new
color variants are all welcome.

## Setup

```
git clone https://github.com/kern0x1b/vscode-intellij-theme.git
cd vscode-intellij-theme
code .
```

Press `F5` in VS Code to launch an Extension Development Host with the theme
loaded, so you can preview color changes live.

## Making theme changes

Theme definitions live under `themes/*.json`. After editing, reload the
Extension Development Host window (`Cmd+R` / `Ctrl+R`) to see changes without
restarting.

## Pull requests

- One theme/fix per PR, with a short description of what changed and why.
- Include a before/after screenshot for visual changes.
- Update `CHANGELOG.md` under `[Unreleased]`.

## Reporting bugs

Open a [GitHub issue](https://github.com/kern0x1b/vscode-intellij-theme/issues)
with the language/file type affected, a screenshot, and which theme variant
(Islands Dark/Light, Classic Dark).
