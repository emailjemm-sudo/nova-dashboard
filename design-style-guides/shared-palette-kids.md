# Shared Kids Palette (Styles 1 and 2)

One colour system for all children's products. It is derived from three existing products:

| Source product | Where the values came from |
|----------------|----------------------------|
| Inside Out 2 Therapy Coping Skill Board Game | Wix store `inside-out-2-emotional-regulation-board-game-for-kids`; the game reuses the emotion card set below |
| Inside Out 2 — Emotions & Coping Skill Cards | `A4 - INSIDE OUT 2 FLASHCARDS.pdf` (9 pages, one emotion per page) — card tint sampled per page |
| Coping Skills Toolbox for Kids | `A4 - Coping Skills Toolbox .pdf` (7 pages) — tool-tag colours sampled per tag |

Two families come out of those files and they are used together:

- **Tool colours** (from the Toolbox) — mid-saturation, slightly dusty. These carry the design: headers, tabs, tags, paper-cut shapes, scribble fills.
- **Emotion tints** (from Inside Out 2) — pale pastel backgrounds, one per emotion. These are the only colours allowed as full-panel or card backgrounds behind text.

Never introduce a colour outside this list. If a product needs a colour "between" two, pick the nearer one.

## 1. Tool colours (primary)

| Token | Name | Hex | Use |
|-------|------|-----|-----|
| `tool.mustard` | Mustard | `#E2BE42` | Hero / toolbox yellow. Titles on covers, star accents |
| `tool.apricot` | Apricot | `#F8BB5D` | Warm highlight, "try this" callouts |
| `tool.coral` | Coral | `#F27D8A` | Energy, movement, anger-adjacent tools |
| `tool.terracotta` | Terracotta | `#C36757` | Deepest warm; headings on cream, stamps |
| `tool.blush` | Blush | `#DDA6A7` | Soft warm panels, comfort tools |
| `tool.lilac` | Lilac | `#BD8FC0` | Imagination, visualisation, calm-down |
| `tool.steel` | Steel blue | `#779EB7` | Thinking / breathing tools, primary cool |
| `tool.aqua` | Aqua | `#9BC6C2` | Grounding, senses, water |
| `tool.olive` | Olive | `#AEB271` | Nature, body, movement |
| `tool.lime` | Lime | `#D1D67B` | Playful accent, limited to small areas |
| `tool.mint` | Mint | `#B4D19C` | Growth, "I can" statements |
| `tool.sand` | Sand | `#D9BCA3` | Neutral warm panel, craft paper |
| `tool.mist` | Mist | `#ADBEB2` | Neutral cool panel, dividers |

## 2. Emotion tints (backgrounds only)

Each tint is the card background from the Inside Out 2 flashcards. Use them as page or card
backgrounds, never as text colour.

| Token | Emotion | Hex | Lighter wash (for large areas) |
|-------|---------|-----|-------------------------------|
| `tint.anger` | Anger | `#EEB5BE` | `#F5DBDF` |
| `tint.anxiety` | Anxiety | `#F3CFC3` | `#F5DFD7` |
| `tint.joy` | Joy | `#F3E1BE` | `#EDE3CF` |
| `tint.disgust` | Disgust | `#D9E0C9` | `#E8ECDB` |
| `tint.envy` | Envy | `#CDE4DF` | `#DCEDE9` |
| `tint.sadness` | Sadness | `#BDD1E6` | `#DFE8F0` |
| `tint.ennui` | Ennui / Boredom | `#B9BDD1` | `#E7E9F0` |
| `tint.fear` | Fear | `#D7C9DF` | `#E9DFEF` |
| `tint.embarrassment` | Embarrassment | `#F4D1D7` | `#F9E4E8` |

## 3. Deep accents (text on tints, icons, numbering)

| Token | Hex | Pairs with |
|-------|-----|-----------|
| `deep.wine` | `#9C4B5F` | anger / embarrassment tints, coral |
| `deep.ochre` | `#BAA275` | joy tint, mustard, sand |
| `deep.sage` | `#697D73` | disgust / envy tints, olive, mint |
| `deep.blue` | `#7797B7` | sadness tint, steel, aqua |
| `deep.slate` | `#39455F` | ennui tint, any cool panel; secondary text colour |
| `deep.plum` | `#554660` | fear tint, lilac |

## 4. Neutrals

| Token | Hex | Use |
|-------|-----|-----|
| `paper` | `#FFFFFF` | Body page background (worksheets) |
| `paper.warm` | `#F6F4F2` | Cover / card-back background |
| `cream` | `#EDE3CF` | Craft-paper panels |
| `ink` | `#222222` | All body text and hand-drawn line work |
| `charcoal` | `#464436` | Headings on light panels, outlines |
| `rule` | `#B5B5B5` | Writing lines, table rules |

## 5. Pairing rules

1. A page uses **one emotion tint** (or white) as background, **two or three tool colours** for structure, and **one deep accent** for icons/numbers. Covers may use up to five tool colours.
2. Tool colours sit next to each other in this fixed order when a row of tags/tabs is needed (it is the Toolbox order and reads as a calm rainbow): steel → olive → apricot → aqua → lilac → mint → mustard → blush → coral → terracotta → sand → mist.
3. Text on a tool colour is `ink`, except on terracotta and steel where it may be white.
4. Never place two warm tool colours (coral, terracotta, apricot, mustard) directly adjacent without a cool or neutral between them.
5. Emotion colour-coding is consistent across every product: joy = yellow, sadness = blue, anger = red-pink, disgust = green, fear = purple, anxiety = orange-peach, envy = teal, embarrassment = pink, ennui = slate-lavender.
