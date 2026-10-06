# Colour

Part of the Fan Led X brand set. See [BRAND.md](BRAND.md).

The deck's brief: *"Navy, black, electric blue and signal lime."*

The system is high contrast. **Dark grounds** carry the big moments: covers, heroes,
statement bands and footers. **Cool light grounds** carry the reading. **Lime is a
signal**: it marks the accent, the action and the second line of a headline. It is never
a large background.

---

## Palette

| Name | Hex | RGB | Role |
|---|---|---|---|
| **Signal lime** | `#C7FF13` | 199 255 19 | Accent text on dark, CTA pills, rule lines, highlights |
| **Electric blue** | `#1930FF` | 25 48 255 | Accent words in headings on light grounds, eyebrows, primary buttons, icons, focus states |
| **Black** | `#050505` | 5 5 5 | Dark grounds; default text on light grounds |
| **Ink navy** | `#25345D` | 37 52 93 | Headings on light grounds, button outlines |
| **Deep navy** | `#1F294F` | 31 41 79 | Small labels and captions on light grounds |
| **White** | `#FFFFFF` | 255 255 255 | Text on dark grounds, card surfaces |
| **Ice** | `#F2F5F7` | 242 245 247 | Light-section ground |
| **Mist** | `#EAECF1` | 234 236 241 | Alternate light ground, panels |
| **Placeholder grey** | `#D9D9D9` | 217 217 217 | Empty image slots only |
| **Rule grey** | `#4B4B4B` / `#C9CACB` | | Hairlines and inactive outlines on dark / light grounds |

Pure `#000000` isn't used. Black is always the slightly lifted `#050505`.

## Pairings

| Situation | Treatment |
|---|---|
| Headline on dark | First line **white**, second line **lime**. *"Operations built around people. / Experiences that turn guests into fans."* |
| Headline on light | **Navy or black**, with the key phrase in **electric blue**. *"Our **Offices.**"* |
| Uppercase statement on dark | White line, then lime line |
| Primary action | Lime pill, black or navy text, a thin dark outline and an arrow |
| Navigation action | Blue pill, white uppercase text and an arrow |
| Action on photography | A white outline circle or pill, with a white arrow |
| Eyebrow / kicker | Electric blue on light, lime on dark |
| Accent rule | Short lime line under a headline, or a lime bar beside it |

## Gradient

**Lime to blue**, used on the X mark, the vertical-bar motif and the brand-band graphics.
The X is drawn as white to lime to blue. Its reversed version (for light grounds) runs
black to blue to lime. For flat applications in code or print use `#C7FF13` → `#1930FF`,
top to bottom.

No other gradients, apart from black-to-transparent scrims for text over photography.

## Contrast

- White on black: about 20:1. Lime on black: about 17:1. Both are safe at any size.
- Blue `#1930FF` on white: about 7:1, so safe for body text and headings.
- **Lime on white or ice fails.** Never set lime text on light grounds. Lime fills on
  light grounds need dark text and a dark outline.
- White on blue is about 7:1, so the nav pill is fine.

## Decisions and open questions

The Figma file has no colour variables, so near-duplicates have crept in. **Rule: the
value Figma uses most on its current pages is the brand value.**

**Lime: decided, `#C7FF13`** (2026-10-06). It is the dominant lime on every current page
(about 265 uses, against about 22 for `#CCFF33`). Treat these as strays and replace them
with `#C7FF13` wherever you find them: `#CCFF33` (the website's original token, labelled
"Neon Green" in Figma), `#CBFF34` and `#B8FF00` (both on the older Rod Laver Arena page).

**Still open:**

| | Value used more | Value used less | What this folder uses |
|---|---|---|---|
| Blue | `#1930FF` (text) | `#1A33FF` (some fills) | `#1930FF` |
| Light ground | `#F2F5F7`, `#EAECF1` | `#EDF1F5` (the website) | `#F2F5F7` |

**Action:** set up the palette as Figma colour variables so the drift stops.
