# The 2026 Flatbelly — Event Site

Single-page event site for Hillwood Country Club's 2026 Flatbelly tournament, modeled on the Summer Hummer 2026 site (same brochure design system: Playfair Display / Cormorant Garamond, black & gold, sticky anchor nav, zero-JS CSS interactivity).

Everything lives in `index.html` — no build step. Deploy by dropping the folder on Netlify or connecting the repo.

## Placeholders to replace before launch

Search `index.html` for these:

- **Dates/times** — currently August 21–22, 2026; every schedule row
- **`TBD`** — entry fees, pool amounts, flight prizes, band name, history stats, defending champions, handicap differential, wild card paths
- **Menus** — all dining blocks say "Menu to be announced"
- **Golf Genius link** — the green banner near the top is a non-link `<div>`; turn it back into an `<a href="...">` when the portal URL exists (see the Summer Hummer site for the markup)
- **Draft banner** — remove the `.draft-banner` div at the top of `<body>` when content is final

The course section (hole flyover videos, pars, yardages) is real Hillwood data reused from the Summer Hummer site.
