# Design systems used on this site

Each `DESIGN.md` here comes from [`getdesign`](https://www.npmjs.com/package/getdesign)
(`npx getdesign@latest add <brand>`). Before changing any page, read the file that governs it and
stay inside its tokens. Do not mix systems on one page.

| Page(s) | Design | File | Notes |
|---|---|---|---|
| `/` (portfolio, `index.html`) | Apple | [`apple/DESIGN.md`](apple/DESIGN.md) | white → `#f5f5f7` → black bands, 980px column, one Action Blue `#0066cc`, terminal "product shot" |
| `/blog/` (index, `blog/index.html` + `blog/styles.css`) | Notion | [`notion/DESIGN.md`](notion/DESIGN.md) | warm `#f6f5f4` canvas, Inter, indigo `#213183` hero with four sticker squares, Medium-style rows. **The hero is a keeper — patch around it, never redesign it.** |
| `/blog/scheme-sathi/` (`blog/scheme-sathi/index.html` + `post-verge.css`) | The Verge, on a **white** canvas | [`theverge/DESIGN.md`](theverge/DESIGN.md) | Anton shout headline, Space Grotesk body, Space Mono uppercase kickers, ultraviolet `#5200ff` links, colour-block section tiles (mint / uv / yellow / pink / orange / white). Deliberate deviation from the file: canvas is `#ffffff`, not `#131313`, and mint is never used as text on white. |

## Adding a new post

1. Pick a system from this table, or add a new folder here with its `DESIGN.md` **in the same commit**.
2. Add the row above. If you deviate from the file (like the white canvas on The Verge), say so in the row.
3. Long-form posts are authored as Markdown outside this repo and built to HTML; the rendered
   `index.html` + its stylesheet are what gets committed under `blog/<slug>/`.

Tried and rejected: WIRED (paper-white broadsheet, serif display) — read as a newspaper, not kept.
