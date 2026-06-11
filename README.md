# Hawkins

A cinema-grade Stranger Things theme for [Obsidian](https://obsidian.md).

Dark mode is the primary art-directed grade — lifted blacks, warm
off-white text, and a restrained red neon glow on headings. Light mode
is a minimal, accessibility-correct fallback (not a second art
direction).

## Palette

- Display red `#ef4135` — borders, fills, focus rings, glows
  (non-text; fails AA as text on dark backgrounds)
- Text red `#f4756c` — links, `--text-accent`, heading accents
  (AA-safe on `#0d0d12`)
- Cyan `#03aeef` — tags, inline code, graph "tag" nodes
- Background `#0d0d12` (lifted black), depth wells `#010102`
- Body text `#e8e4df` (warm off-white)

### Graph view — official ST palette

The graph view uses a separate accent set lifted from the official
Stranger Things title palette: iconic red `#ff1515` on a warm
near-black void `#1e0707`, with sparse blue `#3a5fe5` / indigo
`#1e193c` / green `#073e1e` "portal" specks in the starfield. Node
halos use a canvas `drop-shadow` filter (desktop only).

## Install

### As a full theme

1. Copy this folder into `<vault>/.obsidian/themes/Hawkins/`
   (must contain `manifest.json` and `theme.css`)
2. In Obsidian: **Settings → Appearance → Themes → Hawkins**
3. Leave **Accent color** on its default — the theme wires both
   `--accent-h/s/l` and explicit derived variables, but a custom
   accent picker value can still override part of the system

### As a CSS snippet

1. Copy `theme.css` into `<vault>/.obsidian/snippets/hawkins.css`
2. **Settings → Appearance → CSS snippets** → enable `hawkins`

Use one or the other, not both, to avoid double-applying the rules.

## Optional grain overlay

`.hawkins-grain` is an opt-in scanline + vignette texture, off by
default. Add the class `hawkins-grain` to `<body>` (e.g. via the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings)
plugin or a small snippet) to enable it. Automatically disabled on
mobile and in print/export.

## iPad / iCloud note

If syncing the vault via iCloud, keep it pinned/Downloaded — iCloud
can evict `theme.css` under storage optimization, which silently
reverts the theme until it's re-downloaded.
