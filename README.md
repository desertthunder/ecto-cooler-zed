# Ecto Cooler for Zed

Zed theme extension for Ecto Cooler, an experimental color palette that blends Gruvbox
with Catppuccin:

- **Ecto Cooler Dark**: Gruvbox dark + Catppuccin **Mocha**
- **Ecto Cooler Light**: Gruvbox light + Catppuccin **Latte**

The theme keeps Gruvbox's warm, earthy readability while using Catppuccin **sapphire**
as the primary UI accent. The rest of the Catppuccin pastels are used for syntax contrast,
diagnostics, terminal colors, and editor chrome.

## Usage

In Zed, install this directory as a development extension:

1. Open the command palette.
2. Run **zed: install dev extension**.
3. Select this directory.
4. Choose either **Ecto Cooler Dark** or **Ecto Cooler Light** from the theme picker.

## Palette source

This palette blends the color palettes of the Catppuccin & Gruvbox vim themes.

### Generated Ecto Cooler palettes

#### Dark: Gruvbox dark + Mocha

| Token          | Hex       |
| -------------- | --------- |
| `bg`           | `#24242b` |
| `bg_alt`       | `#26252a` |
| `bg_float`     | `#36353e` |
| `bg_sidebar`   | `#181a1f` |
| `bg_visual`    | `#58656a` |
| `bg_search`    | `#f9d686` |
| `bg_incsearch` | `#fba66a` |
| `bg_selection` | `#696f6f` |
| `fg`           | `#e0d9cb` |
| `fg_alt`       | `#c9c3bd` |
| `fg_muted`     | `#928e91` |
| `fg_subtle`    | `#7c787e` |
| `red`          | `#f57e91` |
| `maroon`       | `#ef8d92` |
| `orange`       | `#fba76d` |
| `yellow`       | `#f9d88b` |
| `green`        | `#aada86` |
| `aqua`         | `#93dbc1` |
| `sky`          | `#8ad7d7` |
| `sapphire`     | `#76c2e0` |
| `blue`         | `#88b1e6` |
| `purple`       | `#cca0e6` |
| `pink`         | `#eeb6d8` |
| `rosewater`    | `#edd9ce` |
| `flamingo`     | `#ebcbc2` |
| `lavender`     | `#aab9ea` |

#### Light: Gruvbox light + Latte

| Token          | Hex       |
| -------------- | --------- |
| `bg`           | `#f5f1dc` |
| `bg_alt`       | `#ede7d1` |
| `bg_float`     | `#e9e2d1` |
| `bg_sidebar`   | `#ededde` |
| `bg_visual`    | `#c7c2b9` |
| `bg_search`    | `#ce8419` |
| `bg_incsearch` | `#e35608` |
| `bg_selection` | `#b4afab` |
| `fg`           | `#414047` |
| `fg_alt`       | `#555259` |
| `fg_muted`     | `#847e81` |
| `fg_subtle`    | `#979293` |
| `red`          | `#c50b2d` |
| `maroon`       | `#d3333f` |
| `orange`       | `#e85809` |
| `yellow`       | `#d0851a` |
| `green`        | `#509423` |
| `aqua`         | `#228c88` |
| `sky`          | `#109dc9` |
| `sapphire`     | `#1c96ab` |
| `blue`         | `#1966da` |
| `purple`       | `#8a3ad3` |
| `pink`         | `#d66ab7` |
| `rosewater`    | `#b5786a` |
| `flamingo`     | `#b66b6a` |
| `lavender`     | `#5a80e0` |

## Project

```text
.
├─ extension.toml
└─ themes/
   └── ecto-cooler.json
```
