# shumtugle.github.io

Personal page. Content lives in `page.txt`, nothing else needs touching.

## How to add a project

Open `page.txt`, scroll to the bottom, add:

```
===
TITLE: Name
META: kind · year
URL: https://…
---
One or two sentences. A blank line starts a new paragraph.
```

1. `===` on its own line separates blocks.
2. The first block is the About section — same grammar, no `TITLE:`.
3. `---` on its own line separates the header from the text.
4. `META:` and `URL:` can be left out.
5. `LINK: Label | https://…` in the first block adds a link next to GitHub.

Project colours come from the fibre code — first block blue, second orange, third green — so reordering blocks recolours the cards.

A minute after the commit the page is updated. If it still looks old, that is the CDN cache, not a failed upload.

## Files

- `index.html` — layout, styles and the header game. Rarely changes.
- `page.txt` — everything you actually edit.
