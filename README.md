# Cremisi

A gothic, arcane colour scheme for Sublime Text in two variants: **Cremisi Obsidian**, dark as
crypt stone, and **Cremisi Ivory**, pale as a page of vellum. Every colour is born from an object:
blood for keywords, lapis for functions, malachite for strings, amber for numbers, tallow for types.

![Cremisi Obsidian](https://raw.githubusercontent.com/vari-sh/Cremisi-Theme/main/assets/preview-obsidian.png)

![Cremisi Ivory](https://raw.githubusercontent.com/vari-sh/Cremisi-Theme/main/assets/preview-ivory.png)

The materials, the two tonal scales and the reasons behind each choice are on the page of the
theme: [vari-sh.github.io/cremisi](https://vari-sh.github.io/cremisi/).

## Install

With [Package Control](https://packagecontrol.io/): run **Package Control: Install Package**
from the command palette and pick *Cremisi*.

If you copied the `.sublime-color-scheme` files into `Packages/User` before, remove them:
Sublime Text merges schemes that share a name, and the old copies would override the package.

## Use

Run **UI: Select Color Scheme** from the command palette and pick *Cremisi Obsidian* or
*Cremisi Ivory*. To follow the system appearance, set both in your preferences:

```json
"color_scheme": "auto",
"light_color_scheme": "Cremisi Ivory.sublime-color-scheme",
"dark_color_scheme": "Cremisi Obsidian.sublime-color-scheme"
```

Every code token clears 4.5:1 against its own background; only comments, the smoke of incense,
may fall below. Requires Sublime Text build 3149 or later.

## Source

Both schemes are generated from the `palette.yaml` of
[vari-sh/Cremisi-Theme](https://github.com/vari-sh/Cremisi-Theme), together with the VS Code port
and the other ports: changes to the colours belong there, since these files are rebuilt from it.
MIT licence.
