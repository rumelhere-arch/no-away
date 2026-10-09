# Bangladesh in My Lifetime — আমার বাংলাদেশ, আমার সময়

A single-file, responsive Bengali website built with HTML, CSS, and JavaScript. It includes an optional Three.js 3D globe, a curated timeline of notable Bangladesh events from 1996 to 2026, category filters, search, sort, saved events (current-session only), source links, copy/share tools, and a PNG share-card generator.

## Run it

1. Download `index.html`.
2. Double-click it, or open it in Chrome/Edge/Firefox.
3. The timeline and PNG generator work locally. The 3D globe uses Three.js from a CDN; if the CDN is blocked or there is no internet, the page shows a CSS fallback visual.

## Publish it online

Upload `index.html` to GitHub Pages, Netlify, or another static host. No backend or API key is required. The shared page URL can then preserve the birth year through `?born=2008` (replace the year as needed).

## Scope and editorial notes

- The built-in database is a curated selection, not every major or minor event in Bangladesh over 30 years.
- Every event links to a source or relevant source repository. Some historical entries use broad reference pages; before public launch, review each citation and replace broad links with exact primary reports where available.
- The page does not make live AI calls or auto-update itself. Its descriptions are pre-written and source-linked to avoid fabricated events. New events need to be researched and added to the `EVENTS` array in `index.html`.
- A birth year alone cannot determine whether an event occurred before or after a person's birthday that year. The display labels age as approximate.
- The November 24, 2026 LDC-graduation date is marked as upcoming as of the site's data date, October 9, 2026.
