# Design Style 3 — Editorial (Adults, Young Adults, Clinicians)

**Audience:** adults and young adults (self-help workbooks) and clinicians (cheat sheets, field guides).
**Mood words:** editorial, magazine, clinical-but-warm, structured, diagrammatic, printable, serious without being cold.
**Palette:** own palette (section 6). Does **not** use the kids palette.

Reference products (Wix store slugs in [sources.md](sources.md)): Therapy Modality Cheat Sheets
Bundle (Editorial Edition), ADHD In The Workplace Full Workbook, Move At Your Own Pace (young adults),
Alexithymia Workbook For Adults. Two sub-registers exist and both are covered here:

- **Workbook register** (ADHD, Own Pace, Alexithymia): white page, navy serif headlines, blue/sage/tan tinted panels, numbered steps, tables with a dark header row.
- **Field-guide register** (Modality cheat sheets): warm cream paper, black serif headlines, olive and terracotta accents, small engraved-style icons, dense three-column reference layout.

---

## 1. The look in one paragraph

A page reads like a well-set magazine feature or a clinical handbook: a large serif headline, an
italic serif stand-first, then body copy in a clean sans. Information is organised into **numbered
steps, two-column comparison tables, and tinted callout panels** with a coloured left rule. Every
page carries a small uppercase section chip at the top and a precise footer with the page count.
Diagrams are simple and schematic (timelines, loops, tiers, network dots), drawn in thin lines in
the palette colours, never clip-art. Whitespace is disciplined: consistent 10 mm module, nothing
tilted, nothing decorative that does not carry information.

## 2. Page anatomy (A4 portrait)

```
┌──────────────────────────────────────────────┐
│ 15 mm margin                                 │
│ [ TIER 1 — MAPPING ]            ◦ small icon │  Section chip (pill) top-left; line icon top-right
│                                              │
│ Headline in Serif Bold 30–36 pt              │
│ Stand-first in Serif Italic 14 pt (one line) │
│ Intro paragraph, Sans 10.5 pt, max 4 lines   │
│                                              │
│ ┌ panel ─ left rule 3 pt ────────────────┐   │  Callout panel: tint fill + 3 pt coloured
│ │ Panel heading (Serif Bold 13)          │   │  left rule, 2 mm radius
│ │ body                                   │   │
│ └────────────────────────────────────────┘   │
│                                              │
│ ┌──────────────┬───────────────┐             │  Comparison table: dark header cells,
│ │ HEADER (navy)│ HEADER (sage) │             │  white text, 0.5 pt rules, zebra tint
│ ├──────────────┼───────────────┤             │
│ │ • item       │ • item        │             │
│ └──────────────┴───────────────┘             │
│                                              │
│ ──────── diagram zone (timeline / loop) ──── │  One diagram max per page
│                                              │
│ ┌ REFLECT: prompt ───────────────────────┐   │  Reflection panel at the bottom with
│ │ .......................................│   │  dotted lines
│ └────────────────────────────────────────┘   │
│ Provided By Gentle Observations © 2026 · Tier 1 — Mapping · Page 2 of 82 │
└──────────────────────────────────────────────┘
```

- **Margins:** 15 mm outer, 12 mm inner; content 180 × 267 mm. Letter: keep 12 mm minimum.
- **Grid:** 12 columns, 5 mm gutter; panels span 6/12 or 12/12; three-up layouts use 4/12.
- **Vertical rhythm:** 10 mm module; headline block occupies 40–50 mm.

## 3. Typography

| Role | Font | Size (A4) | Treatment |
|------|------|-----------|-----------|
| Headline | **Playfair Display Bold** (the ADHD / Own Pace titles). Field-guide register: **Libre Baskerville Bold** | 30–36 pt (cover 60–72 pt) | `ink.navy` on workbooks; `ink.black` on cream field guides; tracking −1 % |
| Stand-first / pull quote | Playfair Display Italic | 14–16 pt | `ink.navy` or `accent.sage`; one line, sentence case |
| Panel heading | Playfair Display Bold | 12–13 pt | `ink.navy` |
| Section chip | **Inter Medium** (or Open Sans) | 8 pt | ALL CAPS, tracking +10 %, white on `blue.mid` pill |
| Body | **Inter Regular** / Open Sans Regular | 10–10.5 pt | `ink.body`, line-height 1.4, left aligned, 70–80 characters per line |
| Table header | Inter Semibold | 8.5 pt | ALL CAPS, white on navy or sage |
| Table body / list | Inter Regular | 9–9.5 pt | `ink.body` |
| Numbered step label | Inter Bold | 9 pt | "STEP 1" white on a coloured square |
| Footer | Inter Regular | 7.5 pt | `ink.muted`, centred: `Provided By Gentle Observations © <year> · <Section> · Page X of Y` |

Rules: exactly one serif and one sans per product; no condensed or display sans; never set body copy in the serif; no text smaller than 7.5 pt.

## 4. Component library

### 4.1 Section chip
Pill 6 mm high, `blue.mid` fill, white caps 8 pt: `TIER 1 — MAPPING`, `OUTCOME 2 — EXTERNALISING TIMELINE PRESSURE`, `HOW TO USE THIS WORKBOOK`. Always top-left.

### 4.2 Headline block
Headline + italic stand-first + 3–4 line intro. A thin 0.5 pt `rule` line may close the block.

### 4.3 Callout panel (tinted)
- Fill: `tint.blue`, `tint.sage`, `tint.rose` or `tint.sand`; 2 mm radius; 3 pt left rule in the matching mid colour (`blue.mid`, `accent.sage`, `accent.rose`, `accent.tan`).
- Heading in serif bold; body in sans. Stack 2–4 panels for "For Clinicians / For Clients / A Note on…" patterns.

### 4.4 Checklist grid
2 columns of pale panels (`tint.blue`/`tint.sage` alternating), each with a 5 mm square checkbox outlined in `blue.mid`, 9.5 pt text.

### 4.5 Comparison table
Header row cells filled `ink.navy` (left) and `accent.sage` (right) with white caps text; body rows white / `tint.sand` zebra; 0.5 pt `rule` borders; bullets inside cells.

### 4.6 Numbered step
Square or circle 9 mm, filled in rotating colours `blue.mid` → `accent.sage` → `accent.tan` → `ink.navy`, white numeral in serif bold 14 pt; step title serif bold 11 pt beside it; body sans.

### 4.7 Tier / category rows (cover and index pages)
Full-width rounded bars, 10 mm high, in `blue.mid`, `accent.sage`, `accent.tan`; white serif text; a 7 mm circular line icon at the left.

### 4.8 Diagram set
Use only these, drawn in 1 pt lines with palette colours:
- **Timeline**: horizontal axis with ticks every unit, labelled ages/years; an arched span in `tint.blue` with a label.
- **Loop / cycle**: 3–5 nodes joined by curved arrows (field guide "Aggressive challenge → Damaged rapport → Perceived invalidation").
- **Tier ladder**: stacked rounded bars (see 4.7).
- **Network dots**: cover motif only — 20–40 small circles in `blue.mid`, `accent.sage`, `accent.tan` connected by thin `rule` lines in the top-right corner.
- **Formula row**: boxes joined by "+" and "→" (ANCHOR + NEW HABIT → REWARD), each box in a different tint.
- **Three-column icon triptych** (field guide): icon above serif label above two-line sans description, separated by 0.5 pt vertical rules.
Icons are single-weight line icons (compass, map, tools, leaf, book, brain, ladder, magnifier), 7–12 mm, in `ink.navy` or `accent.tan`. Field-guide icons may be engraved/hatched style in olive and terracotta.

### 4.9 Reflection panel
Bottom of page, `tint.blue` fill, "Reflect:" in serif bold, prompt in sans, 2–4 dotted rules 8 mm apart.

### 4.10 Affirmation line
Closing italic serif line in `accent.sage`, centred above the footer ("You are not behind. You are differently wired.").

### 4.11 Cover
White (workbook) or `paper.cream` (field guide). Headline at 60–72 pt in two lines, subtitle sans 14 pt, three tier bars, italic serif tagline, network-dot motif top-right, `Provided By Gentle Observations © <year>` at the foot.

## 5. Illustration and imagery rules

1. No photographs inside products (photos are for listing images only).
2. No cartoon characters, no emoji, no clip-art colour fills.
3. Icons: line only, consistent 1 pt weight, one colour per icon.
4. Field-guide register may use engraved/woodcut-style spot illustrations (maze, ladder, magnifier) in `ink.black` with a single olive or terracotta accent.
5. Charts (if any) follow the same palette: navy, blue, sage, tan in that order.

## 6. Palette

### Workbook register (ADHD · Own Pace · Alexithymia)

| Token | Hex | Use |
|-------|-----|-----|
| `ink.navy` | `#1C2C4D` | Headlines, table headers, step squares |
| `ink.body` | `#2B2B2B` | Body text |
| `ink.muted` | `#6B6F76` | Footer, captions |
| `blue.mid` | `#7D9BCE` | Section chips, primary tier bar, checkbox outlines |
| `blue.deep` | `#697B9A` | Secondary blue, chart series 2 |
| `accent.sage` | `#86886A` | Tier 2 bar, table header right, affirmation text |
| `accent.tan` | `#B4A392` | Tier 3 bar, warm step squares |
| `accent.rose` | `#C9A5A0` | Rare warm accent for "caution / cost" panels |
| `tint.blue` | `#DCE1EF` | Panel and checklist fill |
| `tint.sage` | `#E9EBE4` | Panel fill, zebra rows |
| `tint.rose` | `#F2E2E0` | "For clients" panel fill |
| `tint.sand` | `#EFE9E1` | Neutral panel fill |
| `paper` | `#FFFFFF` | Page |
| `rule` | `#C9CDD3` | Table rules, dotted lines |

### Field-guide register (Modality cheat sheets)

| Token | Hex | Use |
|-------|-----|-----|
| `paper.cream` | `#F4F1E9` | Page background |
| `ink.black` | `#1C1C1B` | Headlines and body |
| `accent.olive` | `#6B6B47` | Bullet dots, icon accents, dividers |
| `accent.terracotta` | `#B5523A` | Single warm accent (maze path, warning icon) |
| `accent.tan` | `#B4A392` | Secondary accent |
| `panel.grey` | `#E9E5DE` | Left "Core message / Primary targets" sidebar |
| `rule` | `#B1ADA8` | Column dividers |

### Pairing rules
1. Headline colour is always `ink.navy` (workbook) or `ink.black` (field guide); never a tint.
2. A page uses at most three tints and two accents.
3. Tier/step colour order is fixed: blue → sage → tan → navy.
4. Warm accents (`accent.rose`, `accent.terracotta`) appear on at most one element per page.
5. Text on `blue.mid`, `accent.sage`, `accent.tan`, `ink.navy` is white; on tints it is `ink.body`.

## 7. Do / Don't

**Do**
- Keep every element on the grid; alignment is the style.
- Use real tables for comparisons and real numbered steps for processes.
- Give each page one diagram at most, and make it carry information.
- Keep the footer format exact.

**Don't**
- Use rounded "bubbly" shapes, hand-drawn lines, torn edges or washi tape (those are Styles 1–2).
- Use more than one serif.
- Use saturated or pastel-rainbow colours from the kids palette.
- Centre body copy (only the affirmation line and footer are centred).
- Add stock photos, gradients or drop shadows.

## 8. Prompt snippet for generators

```
Style: editorial clinical workbook page, A4. White page, 15 mm margins, 12-column grid. Section
chip pill top-left (white caps on #7D9BCE). Headline Playfair Display Bold 32 pt in navy #1C2C4D,
italic serif stand-first, Inter 10.5 pt body #2B2B2B. Components: tinted callout panels (#DCE1EF,
#E9EBE4, #F2E2E0, #EFE9E1) with a 3 pt coloured left rule; comparison table with navy and sage
(#86886A) header cells and white caps text; numbered step squares in blue → sage → tan (#B4A392)
→ navy; one schematic diagram (timeline, loop, tier bars or formula row) in 1 pt lines; reflection
panel with dotted rules at the bottom; italic sage affirmation line; footer "Provided By Gentle
Observations © 2026 · <Section> · Page X of Y". Line icons only, no photos, no gradients.
Field-guide variant: cream paper #F4F1E9, black serif headlines, olive #6B6B47 and terracotta
#B5523A accents, three-column reference layout with engraved-style spot icons.
```
