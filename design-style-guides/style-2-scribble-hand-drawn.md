# Design Style 2 — Scribble / Hand-Drawn (Children)

**Audience:** children aged roughly 5–12.
**Mood words:** crayon, scribble, hatching, marker line art, sketchbook, playful, gentle, gender-neutral.
**Palette:** [shared-palette-kids.md](shared-palette-kids.md) — identical to Style 1. No other colours.

Reference products: Divorce Worksheets for Kids (`A4 Portrait-Divorce Workbook for Kids.pdf`, 32 pp)
and Somatic Therapy Coping Skill Cards for Kids (`A4 - Somatic Therapy Coping Skill Cards.pdf`, 8 pp).
Both PDFs were opened and fonts/colours measured directly (Wix store slugs `divorce-worksheets-for-kids-therapy`, `somatic-therapy-coping-skill-cards-for-kids`).

---

## 1. The look in one paragraph

Everything looks **drawn by hand with a crayon or a fine marker**. Big shapes (a house, a flower,
a heart, a winding path) are filled with visible diagonal **scribble hatching** rather than flat
colour, so the fill never reaches the outline cleanly. Small icons are single-weight black line
drawings. Backgrounds are either white or one bold page colour from the palette; text sits on
rounded, outlined boxes with a dashed inner border like a cut-out card. Type pairs a wide,
letter-spaced hand-lettered display with a clean geometric sans.

## 2. Page anatomy (A4 portrait)

```
┌──────────────────────────────────────────────┐
│ 12 mm margin                                 │
│   U n d e r s t a n d i n g                  │  Kicker: display font, tracked +40 %
│   S e p a r a t i o n                        │  Title: same font, 2× size, tracked +30 %
│                                              │
│   intro sentence(s), Open Sans Light 11 pt   │
│                                              │
│   ┌ outlined box, 4 mm radius ───────────┐   │  Content box: 1.5 pt ink outline,
│   │ ┌ dashed inner border ─────────────┐ │   │  inner dashed border 1 pt, 3 mm inset
│   │ │ prompt / list                    │ │   │
│   │ └──────────────────────────────────┘ │   │
│   └──────────────────────────────────────┘   │
│                                              │
│       ╭──╮      large scribble-filled        │  Hero drawing: 1 per page, scribble fill
│      ╱    ╲     hero shape (house, flower,   │  in 1–3 tool colours, black outline
│     ╱______╲    cloud, path with steps)      │
│                                              │
│ Provided by Gentle Observations              │
└──────────────────────────────────────────────┘
```

- **Margins:** 12 mm. **Grid:** 4 columns, 8 mm gutter.
- Either **one hero drawing** that occupies 40–60 % of the page with prompts written around/into it, or **a grid of 2 × 2 cards** (card products). Not both.

## 3. Typography (measured from the PDFs)

| Role | Font (embedded in source) | Size | Treatment |
|------|---------------------------|------|-----------|
| Title / kicker | **Mintmolly** (hand-lettered sans caps, Divorce workbook) | kicker 14–16 pt, title 36–44 pt | Letter-spacing +30–40 % (the signature "K i d s" look), colour `cream` or white on coloured pages, `ink` on white pages |
| Card title | **Kollektif Bold** (Somatic cards) | 12–13 pt | ALL CAPS, `ink`, centred in the card's top band |
| Body | **Open Sans Light** | 10.5–11.5 pt | `ink` (or white on dark blue pages), centred inside cards, left-aligned on worksheets |
| Emphasis / labels | **Open Sans Bold** | same as body | Used for "Exercise:" lead-ins and list words |
| Secondary sans | **Glacial Indifference** Regular/Bold | 10–12 pt | Section sub-labels, numbered steps |
| Footer | Open Sans | 9 pt | `Provided by **Gentle Observations**` |

If Mintmolly is unavailable use *Delius Swash Caps* or *Gaegu Bold* with the same tracking; if Kollektif is unavailable use *Glacial Indifference Bold*.

## 4. Component library

### 4.1 Scribble fill
- Fill any large shape with parallel diagonal strokes at 45°, stroke 1.5–2.5 pt, spacing 2–3 pt, in a tool colour at 100 %. Strokes overshoot the outline by 1–2 mm in places and leave small white gaps; a second colour may be layered at 60 % for depth.
- Shapes in the references: house (`tool.mustard` walls, `tool.apricot` roof, `tool.steel` door), flower (`ink` petals, scribbled), heart (`cream` on mustard), cloud clusters (`tool.olive`, `tool.steel`, `tool.mustard`), winding path (segments in coral, mustard, steel, mint, blush).

### 4.2 Line icon
- Single-weight black line, 2 pt, rounded caps, no fill, 18–28 mm. Inside cards the icon sits on a soft **blob** of the card's emotion tint (see 4.4).
- Icon subjects: body outlines, hands, feet, bells, waves, stick figures, faces with three-line expressions.

### 4.3 Content box
- Outer: 1.5 pt `ink` outline, 4 mm corner radius, white fill (or the page tint).
- Inner: 1 pt dashed border, 3 mm inset, same colour.
- Headings inside the box sit in a **band** across the top: filled with a tool colour, text in `ink` caps (Kollektif Bold).

### 4.4 Card (coping-skill cards)
- 2 × 2 per A4 page, each 90 × 130 mm, 6 mm gap, trim marks optional.
- Structure top to bottom: title band (tool colour, 14 mm) → white body → icon on tint blob → instruction text → "why it helps" note in a second outlined box at the bottom.
- Each page of a deck uses **one** warm or cool colour family (the Somatic deck is blush `#DDA6A7` / terracotta `#C36757` and sand/apricot); vary families across pages.

### 4.5 Step path
- A thick S-curve path made of coloured segments (scribble-filled), with square check boxes drawn in black line rotated ±10°, and a short prompt beside each box.

### 4.6 Word cloud blobs
- Overlapping cloud shapes scribble-filled in olive / steel / mustard with white bullet text inside (used for "words grown-ups use" lists).

### 4.7 Coloured page
- A full-page solid in `tool.mustard`, `tint.sadness` (deepened to `#98BDD3`), `#96D599` mint or `#F8A281` peach is permitted for **introduction / story pages only**; text on these pages is white or `cream` and the body text is centred.

## 5. Illustration rules

1. Black line only for outlines (`ink`, 1.5–2.5 pt). Colour appears only as scribble fill or as a tint blob.
2. Imperfection is the point: lines wobble, fills overshoot, corners don't meet.
3. People are simplified stick/round figures; hair and clothing give no gender cues; skin is left white or line-hatched, never pink/peach fill.
4. One hero drawing per worksheet page; cards get one icon each.

## 6. Colour usage on a typical page

| Element | Colour |
|---------|--------|
| Page background | white, or one solid colour on story pages |
| Title | `ink` on white; `cream` (#EDE3CF) or white on colour |
| Scribble fills | 1–3 tool colours, never an emotion tint (tints are too pale to read as crayon) |
| Icon blobs | emotion tints |
| Card title band | tool colour |
| Text | `ink` |

## 7. Do / Don't

**Do**
- Let the scribble show white between strokes.
- Mix one cool and one warm fill colour per drawing.
- Keep type crisp and geometric so the hand-drawn art reads as deliberate.

**Don't**
- Use flat vector fills with torn edges (that is Style 1).
- Add gradients, photo textures, or coloured outlines.
- Use more than two tracking-heavy headline lines per page.
- Use rounded "emoji" faces with yellow fill.

## 8. Prompt snippet for generators

```
Style: hand-drawn scribble worksheet for children. Black marker outlines (2 pt), large shapes
filled with visible diagonal crayon hatching, single-line icons, outlined content boxes with a
dashed inner border, letter-spaced hand-lettered titles (Mintmolly-like), Open Sans Light body.
Palette strictly: mustard #E2BE42, apricot #F8BB5D, coral #F27D8A, terracotta #C36757,
blush #DDA6A7, lilac #BD8FC0, steel #779EB7, aqua #9BC6C2, olive #AEB271, mint #B4D19C,
sand #D9BCA3, mist #ADBEB2; icon blobs from tints #EEB5BE #F3CFC3 #F3E1BE #D9E0C9 #CDE4DF
#BDD1E6 #B9BDD1 #D7C9DF #F4D1D7; text ink #222222. One hero drawing per page, gender-neutral
stick figures, no gradients. Footer: "Provided by Gentle Observations".
```
