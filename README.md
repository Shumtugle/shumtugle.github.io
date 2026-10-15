# shumtugle.github.io

Personal page. Content lives in `page.txt`, nothing else needs touching.

## How to add a project

Open `page.txt`, scroll to the bottom, add:

```
===
TITLE: Name
META: android · kind · v1.2.3
URL: https://…
FIBER: 13
UPDATED: 2026-10-15
---
One or two sentences. A blank line starts a new paragraph.
```

1. `===` on its own line separates blocks.
2. The first block is the About section — same grammar, no `TITLE:`.
3. `---` on its own line separates the header from the text.
4. Everything except `TITLE:` can be left out.
5. `LINK: Label | https://…` in the first block adds a link next to GitHub.

Optional fields:

- `META:` — words joined by `·`. A part that looks like a version (`v2.9.9`, `1.04`) becomes the version badge; the rest is the kind line.
- `URL:` — the project page. A GitHub address is labelled *Source*.
- `SOURCE:` — a second link to the code, when `URL:` is a page.
- `FIBER:` — the card's fibre number, given once and kept. It sets the colour by the fibre code: 1–12 plain, 13–24 the same colours with a black tracer. Without it the number follows the block's position.
- `UPDATED:` — `YYYY-MM-DD` of the last release. Shows "updated N days ago"; within two weeks the card carries a live dot. The newest date goes to the top line of the page.
- `KIND: tool` or `KIND: toy` — which tab the card sits under. Without it, a `game` or `music` in `META:` makes it a toy.
- `FEATURED: yes` — the card goes first and wide. Only the first such card counts.
- `STATUS: retired` — the card leaves the list and waits under *Earlier*.

Block order is the order on the page. Reordering no longer recolours anything: a card that has `FIBER:` keeps its colour wherever it stands.

A minute after the commit the page is updated. If it still looks old, that is the CDN cache, not a failed upload.

## Files

- `index.html` — layout, styles and the game at the bottom. Rarely changes.
- `page.txt` — everything you actually edit.
