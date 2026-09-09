# IMXP — Fundraise Deck

A hand-coded, cinematic web deck for IMXP's raise. Built from the strategist's
storyboard (Google Sheet, IMXP Content Editor), it carries the full investor
narrative: hook → proof → reach → market → problem → solution → business →
team → horizon.

- **15 slides**, 16:9, self-contained (one CDN dependency: Google Fonts).
- **Design:** IMXP's source design language — Archivo headlines, Inter body,
  the Canva pill palette (teal / green / yellow / lavender / orange), eyebrow
  labels, imxp logo top-right, cinematic full-bleed photo slides mixed with
  clean data slides.
- **Photos:** real Iceland Eclipse 2026 press photos (`media/photos/`), no
  generated imagery. Team headshots in `media/people/`.
- **Video:** the Festival-in-a-Box demo plays inline as a native slide.
- **Facts:** figures and citations verbatim from the storyboard's researched
  sources (WHO, Amadeus, Skift, NASA, Live Nation FY2024, PwC, KKR/Superstruct).
- **No ask on the page**, per Mitch — the close is contact only.

## View

```
https://<account>.github.io/<repo>/
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

## Editing

Content lives directly in `index.html` (the `.slide` sections). Hand-coded, so
text edits are immediate and reflow cleanly — no image regeneration required.

## Open items (blanks from the storyboard, to fill from IMXP's own numbers)

These were flagged in the source as "blanks you must fill" and are **not**
invented in the deck:

- Engineering headcount today (Team slide).
- IMXP's own presale curve, repeat-purchase rate, blended acquisition cost
  (Business slide).
- The before-picture: production hours / headcount for Texas Eclipse (Problem
  slide).
