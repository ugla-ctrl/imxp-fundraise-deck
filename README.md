# IMXP — Info Deck

A hand-coded, editorial web deck for IMXP's raise. Built verbatim from the
storyboard tab of the IMXP Content Editor (Google Sheet): the full investor
narrative — hook → proof → reach → market → problem → solution → business →
team → horizon.

## Design — its own identity

Deliberately distinct from IMXP's other decks (which run Archivo + a pastel
"Canva pill" palette on dark cinematic photo slides). This one is an
**editorial / archival-cosmic** system:

- **Type:** Fraunces (high-contrast display serif, italic accents) + Space
  Grotesk (labels & body). Big figures set in the serif.
- **Palette:** warm bone paper, near-black ink, and a single solar-gold accent
  (with muted sky-blue / rust / sage for data), photography carrying the rest.
- **Layout:** magazine masthead + running foot, hairline rules, a giant index
  numeral, big serif numbers, and a **photographer credit** on every photo
  slide. A warm duotone grade unifies many different images into one deck.
- **15 slides**, 16:9, self-contained (one CDN dependency: Google Fonts).

## Photography

Fresh curation from the **IE26 Media Finder** library (7,752-file Iceland
Eclipse 2026 archive) — no images recycled from the other decks. Credited to
the original photographers (Whitney Petters, The Bailey Perspective, Andrianna
Kaimis, Monica Cazes, Daniel, and more). Team headshots in `media/people/`.

## View

```
https://ugla-ctrl.github.io/imxp-fundraise-deck/
```

## Navigation

- **← / →**, **Space / Page Down**, **Home / End**
- Swipe on touch, scroll / trackpad, or the dot rail
- Deep-link to any slide with `#<n>`

## Slide order

1. Cover — Immersive Experiences at Global Scale
2. The Eclipse — the emotional beat
3. The Proof — Iceland Eclipse, delivered
4. The Reach — press & audience
5. The Demand — why this is a category
6. What's Next — Egypt, the longest totality
7. Upcoming Events — the full slate
8. The Business — presale float, comps
9. The Problem — production eats the margin
10. The Solution — Festival in a Box
11. FIAB — technology demo (video)
12. Where it Stands — live / in build / proving ground
13. The Team — the people who have already done this
14. The Horizon — a total solar eclipse from the Moon
15. Close — thank you

No funding ask on the page, per Mitch — the close is contact only.

## Editing

Content lives directly in `index.html` (the `.slide` sections). To swap a
photo, drop a new file into `media/photos/` and update the slide's `background-image`
and its footer credit.

## Open items (blanks from the storyboard, to fill from IMXP's own numbers)

Flagged in the source as "blanks you must fill" — **not** invented here:

- Engineering headcount today (Team).
- IMXP's own presale curve, repeat-purchase rate, blended acquisition cost
  (Business).
- The before-picture: production hours / headcount for Texas Eclipse (Problem).
