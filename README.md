# Brand

Logos, wordmarks and colours of OpenMarksman and its projects, with the script that generates the logos.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="openmarksman/openmarksman-dark.svg">
  <img src="openmarksman/openmarksman-light.svg" width="400" alt="OpenMarksman">
</picture>

[![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/hUCSjDYNaa)

## Colours

`colours/tokens.css` is the palette every project site uses. Copy it into the site and keep its version comment; a site that loads it from another origin breaks when it changes.

| Role | Light | Dark | Use |
|---|---|---|---|
| page | `#ffffff` | `#10121b` | page background |
| surface, surface-alt | `#f6f8fc`, `#eef0f6` | `#161923`, `#1e212c` | cards, panels, code |
| ink | `#1d2130` | `#e9ebf1` | text, headings |
| muted | `#555a6d` | `#acb0c0` | secondary text |
| accent | `#1971c2` | `#4dabf7` | primary buttons, active tab, links |
| line | `#dcdfe9` | `#2f323f` | separators only |
| control-line | `#7b7f91` | `#6f7485` | edges of inputs and outlined buttons |
| warn | amber | amber | safety panels only |

Neutrals: [Mantine colour generator, seed #63687C](https://mantine.dev/colors-generator/?color=63687C). Accent: Mantine's built-in `blue` (shade 8 light, shade 4 dark), the `primaryColor` of the Ballistics app. To change a colour, edit `colours/tokens.css`, raise its version, check every pair against the contrast ratios in its header, then update each site.
