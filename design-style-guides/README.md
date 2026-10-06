# Gentle Observations — Design Style Guides

Three reproducible visual systems for Gentle Observations worksheets, card decks and workbooks.
Each guide is written so that a designer **or** an AI design tool can be handed the file plus a
content brief and produce a page that looks like it belongs to the existing catalogue.

| # | Guide | Audience | Look | Palette |
|---|-------|----------|------|---------|
| 1 | [style-1-paper-cut-collage.md](style-1-paper-cut-collage.md) | Children 5–12 | Paper-cut / Matisse collage, torn paper, washi tape | [Kids palette](shared-palette-kids.md) |
| 2 | [style-2-scribble-hand-drawn.md](style-2-scribble-hand-drawn.md) | Children 5–12 | Scribble, crayon hatching, hand-drawn line art | [Kids palette](shared-palette-kids.md) |
| 3 | [style-3-editorial.md](style-3-editorial.md) | Adults, young adults, clinicians | Professional editorial, diagrams, structured tables | Own palette (in guide) |

Supporting files:

- [shared-palette-kids.md](shared-palette-kids.md) — the single colour system used by Styles 1 and 2, derived from the Inside Out 2 Board Game, the Inside Out 2 Emotion & Coping Skill Cards and the Coping Skills Toolbox for Kids.
- [tokens/](tokens/) — the same values as JSON (`style-1.json`, `style-2.json`, `style-3.json`, `palette-kids.json`) for design tooling.
- [sources.md](sources.md) — every product analysed, where its file lives (Wix store slug / Google Drive file), what was extracted from it, and which items could not be opened.

## How to use a guide with a generator

Paste the whole guide file into the prompt, then add a brief in this shape:

```
STYLE GUIDE: <paste style-N file>
PRODUCT: <worksheet / card deck / workbook page>
TITLE: <page title>
AGE / AUDIENCE: <e.g. children 6–9>
PAGE SIZE: A4 portrait (also export US Letter)
CONTENT: <the sections, prompts and copy to lay out>
```

The guide's "Page anatomy", "Component library" and "Rules" sections are written as
instructions, not descriptions, so they can be followed literally.

## Rules that apply to every style

1. **Two page sizes.** Every product ships as A4 (210 × 297 mm) and US Letter (8.5 × 11 in). Design on A4 with safe margins that survive Letter re-flow (see each guide).
2. **Footer.** Bottom-left: `Provided by **Gentle Observations**` (brand name in bold). Bottom-right: page number. Editorial products use `Provided By Gentle Observations © <year> · <Section> · Page X of Y`.
3. **Website.** Where a URL is shown it is `www.gentleobservations.com`.
4. **Print-safe.** No full-bleed solid blocks of saturated colour on body pages (ink cost); backgrounds are paper-white or a pale tint. Covers may be full-colour.
5. **Gender-neutral.** Characters, names and colour coding never imply gender. Avoid pink = girl / blue = boy pairings; the kids palette is used as a rainbow across all characters.
6. **Writing space is real.** Any field a child or client writes in is at least 9 mm tall per line and uses a dotted or thin solid rule, never a tinted box alone.
7. **Accessibility.** Body copy ≥ 10.5 pt (kids ≥ 11 pt), text on tinted panels must stay at or above 4.5:1 contrast — use the "ink" colour for text, not a darker shade of the panel colour.
