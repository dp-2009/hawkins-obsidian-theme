---
title: Hawkins Theme Demo
category: demo
tags: [demo, upside-down, hawkins]
status: active
rating: 5
created: 2026-08-14
aliases: [Hawkins Theme Demo]
---

# Hawkins — The Upside Down

*This note exercises every element Hawkins styles. Open it with the theme active — dark mode is the primary art-directed grade, light mode is the accessibility-correct fallback. Toggle between them to compare.*

## Headings scale down in weight and glow

### h3 stays legible without the red glow
#### h4 switches to the interface font
##### h5 is body-weight, for dense notes
###### h6 is the quietest label style

---

## Text formatting

Regular paragraph text runs in the theme's serif stack. Use **bold for emphasis**, *italic for a softer emphasis*, and ==highlighted text== for something you want to jump out during review. You can also drop in `inline code` — it picks up the cyan accent — versus a fenced block below.

```js
// Fenced code blocks keep the deep-well background,
// Obsidian's own syntax colors render on top.
function openGate(location) {
  return location === "Hawkins Lab" ? "portal" : "closed";
}
```

> Blockquotes get the display-red left border and a faint red wash behind the text — good for pulling a quote or a warning aside.

---

## Links

- External link: [Obsidian](https://obsidian.md) — renders cyan
- Internal link to an existing note: [[Hawkins Theme Demo]] — renders text-red
- Unresolved internal link: [[Upside Down Lab Notes]] — renders desaturated/muted red, since the note doesn't exist yet

---

## Tags

#demo #upside-down #hawkins #stranger-things

Tags render as cyan pills — distinct from links so you can tell navigation from taxonomy at a glance.

---

## Callouts

> [!note] Note
> Default cyan callout — general info.

> [!tip] Tip
> Also cyan — a shortcut or suggestion.

> [!success] Success
> Green — something worked.

> [!question] Question
> Amber — open question or thing to verify.

> [!warning] Warning
> Amber — proceed carefully.

> [!danger] Danger
> Red — high-severity, pay attention.

> [!bug] Bug
> Red — known issue.

> [!example] Example
> Purple — a worked example or sample.

> [!quote] Quote
> Muted gray — a citation, distinct from a blockquote.

> [!abstract] Summary
> Cyan — TL;DR block at the top of a long note.

---

## Task list

- [x] Read the Hawkins README
- [x] Install as a theme or CSS snippet
- [ ] Enable the optional grain overlay
- [ ] Open the graph view and check the starfield

---

## Table

| Element | Dark mode | Light mode |
|---|---|---|
| Accent | `#ef4135` display red | `#c5281d` |
| Tag pill | cyan, 12px radius | cyan, desaturated |
| Blockquote | red wash, italic | red wash, italic |
| Code block | deep-well background | light gray background |

---

## Footnotes

Session cookies for a real Instagram integration expire every 60–90 days[^1], which is unrelated to this theme but demonstrates footnote styling.

[^1]: Footnotes render smaller and muted, tucked below the fold.

---

## Horizontal rule

---

*End of demo. Toggle Settings → Appearance → Base color scheme to compare dark vs. light, and open the graph view to see the Upside-Down starfield backdrop (desktop only — the node glow is disabled on mobile).*
