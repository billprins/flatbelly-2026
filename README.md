# The 2026 Flatbelly — Event Site

Single-page event site for Hillwood Country Club's 2026 Flatbelly tournament, modeled on the Summer Hummer 2026 site (same brochure design system: Playfair Display / Cormorant Garamond, black & gold, sticky anchor nav, zero-JS CSS interactivity).

Everything lives in `index.html` — no build step. Deploy by dropping the folder on Netlify or connecting the repo.

## Confirmed content (from the club's Golf Genius itinerary & guest letter)

- Dates July 23–25, 2026 · registration window Mar 1–15 · 60-team lottery
- Format: team best ball, five 9-hole matches, 1 pt/hole + 1 pt match win (ties split), 80% handicaps, team index = each player's lowest of last 6 months, 11 flights (66 teams, six per flight); 11 flight winners + 1 wildcard → shootout, last team standing wins
- Entry $1,500/team, $500 deposit billed to host member at lottery draw
- Pink Jacket branding (jacket image hotlinked from the club's Golf Genius CDN)
- Contacts: Hayden Hartz (hayden.hartz@hillwoodcc.org), Golf Shop 615-352-5600, 6201 Hickory Valley Rd
- Guest Info section from the Accompanied Guest Letter
- Golf Genius portal: https://www.golfgenius.com/pages/12326936842300562696

## Still TBD (search `TBD` in index.html)

- Thursday schedule, daily tee times, shootout holes
- Food & beverage / menus ("announced soon" per itinerary)
- Awards party details (band, dress, time)
- Flight prizes, wildcard criteria, pools/Calcutta
- History stats & defending champions
- **Draft banner** — remove the `.draft-banner` div when content is final

The course section (hole flyover videos, pars, yardages) is real Hillwood data reused from the Summer Hummer site; 7,059 yds & championships-hosted list from the guest letter.
