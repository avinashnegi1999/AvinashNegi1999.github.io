# avinashnegi1999.github.io

My personal site.

| Page | Live |
|---|---|
| Portfolio | **[avinashnegi.com](https://avinashnegi.com/)** |
| Blog | **[avinashnegi.com/blog](https://avinashnegi.com/blog/)** |

Python developer in Kotdwara, India. No job yet — so the site lists four things I actually
shipped, and nothing I didn't.

---

## What's here

| File | What it is |
|---|---|
| [`index.html`](index.html) | The entire site — markup, styles and scripts in one file |
| [`avinashnegi_resume.pdf`](avinashnegi_resume.pdf) | Résumé, linked from the nav, hero, contact block and footer |
| [`blog/`](blog/) | Blog index — links to my Hashnode publications and Medium posts, with local cover images in `blog/img/` |

No build step, no framework, no package.json. Open `index.html` in a browser and that's the site.

## Rules the page follows

1. **Only the four repositories pinned on my GitHub** appear as projects —
   [yojana-sathi](https://github.com/avinashnegi1999/yojana-sathi),
   [tufglow](https://github.com/avinashnegi1999/tufglow),
   [nimcet](https://github.com/avinashnegi1999/nimcet),
   [100 Days of Python](https://github.com/avinashnegi1999/100-Days-of-Python-Pro-Bootcamp).
   Nothing padded out to make the list look longer.
2. **No invented numbers.** No client counts, no test-coverage figures, no uptime percentages,
   no traffic stats. If it was never measured, it isn't on the page.
3. **Skills are tiered** — *Solid* / *In progress* / *Not yet* — and every entry names the
   repository that evidences it.
4. The hero says *no job yet* outright, because it's true and a recruiter finds out anyway.

## Design

**Portfolio** — built to an interpretation of Apple's design language: white → `#f5f5f7` → black band rhythm,
a 980px reading column, one Action Blue (`#0066cc`) carrying every link, and a single signature
shadow reserved for the "product shot". Since the product here is code, that shot is a terminal
that types out the same facts the page states.

Motion is one idea, used sparingly: content fades up as it comes into view. Everything respects
`prefers-reduced-motion`.

**Blog** — Notion's design language instead: warm `#f6f5f4` paper canvas, Inter, a single indigo
hero band, one blue (`#0075de`) for links, hairline dividers. Posts are listed Medium-style — one
row each, copy left, cover right. Tokens live in `blog/DESIGN.md`.

## Tech

Plain HTML, CSS custom properties, and [GSAP](https://gsap.com/) + ScrollTrigger from a CDN,
pinned with SRI hashes. Fonts fall back to the system stack.

## Deployment

GitHub Pages, deployed from `main` at the repository root. Any push to `main` publishes —
`index.html` becomes `/`, `blog/` becomes `/blog/`. Custom domain `avinashnegi.com` via `CNAME`.

## Elsewhere

[GitHub](https://github.com/avinashnegi1999) ·
[LinkedIn](https://linkedin.com/in/avinashnegi1999) ·
[Medium](https://medium.com/@avinashnegi1999) ·
[Hashnode](https://hashnode.com/@avinashnegi1999) ·
[LeetCode](https://leetcode.com/u/Avinashnegi1999/)

Open to remote Python internships and entry-level backend roles, India-based —
[avinashnegi1999work@gmail.com](mailto:avinashnegi1999work@gmail.com)
