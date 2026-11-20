# Fan Led X: Branding

The brand reference for everything that carries the Fan Led name. Read this file, then
the file for your task. Do not read the whole folder for a small job.

## What to read for which job

| You are making | Read, in order | Use |
|---|---|---|
| Anything at all | `BRAND.md` | The one-page summary. Always start here |
| Copy, a headline, a name, an email, a bio | `VOICE.md` | Positioning, messaging hierarchy, tone, banned words, writing rules |
| A PowerPoint or Keynote deck | `PRESENTATION.md`, then `COLOUR.md`, `TYPOGRAPHY.md` | Canvas, theme slots, layouts, components, writing for slides, QA list |
| A document, PDF or one-pager on a light ground | `export.pdf` for the look, `COLOUR.md`, `TYPOGRAPHY.md`, `VOICE.md` | Blue eyebrows, two-tone navy and blue headlines, pills, numbered circles, hairline tables |
| A web page or component | `WEBSITE.md`, then `COLOUR.md`, `TYPOGRAPHY.md` | Tokens, components, motion, the Figma file |
| Anything with the logo or the X mark | `LOGO.md` | Clear space, which asset for which ground, what not to do |
| Anything with photos, icons or the bars motif | `IMAGERY.md` | Photography direction and the graphic system |
| A new medium (email, print, signage, app) | `WEBSITE.md` as the model | Write a new `<MEDIUM>.md` in the same style and link it from `BRAND.md` |

## Files

| Path | What it is | When to use it |
|---|---|---|
| `fanledx-template.pptx` | The PowerPoint template, sixteen example slides on eight layouts, speaker notes on each | Start every Fan Led deck from a copy of this. Duplicate the slides you need, delete the rest. Never edit the master file for a one-off deck |
| `export.pdf` | A Claude artifact (Football Drome online check-in) styled to the brand | The reference for the light-ground document look. Not a template; copy the treatment, not the content |
| `assets/logo/` | Logo lockup and X mark in PNG, plus a traced SVG and PDF | `fanledx-logo-*.png` on dark grounds. `brand-x.png` on dark, `brand-x-stripes.png` on light. See `LOGO.md` before choosing |
| `assets/graphics/` | Vertical bars, photo scrim, outline icons in blue and white | Decks and documents. Blue icons on light grounds, white on dark |

## Rules that override defaults

- **No em dashes.** Anywhere, in any file or output. Use a comma, a full stop, parentheses or " - ".
- **British English.** Colour, organise, programme, centre.
- **Headlines in sentence case, ending in a full stop.** Uppercase only for eyebrows, buttons, nav and statement bands.
- **Inter only.** Black for headlines, ExtraBold for labels, Regular for body. Never substitute without saying so.
- **Lime `#C7FF13` is a signal.** On dark grounds only, never on white or ice, never as a large fill.
- **Two-tone headlines split at a sentence break.** White then lime on dark. Navy then blue on light.
- **Real people in real venues.** No empty stadiums, no stock-photo smiles, no renders passed off as photos.
- **The pillar names vary between sources.** Pick one set per piece and keep it. See `VOICE.md`.

## Working here

- This folder is a git repo (private, `github.com/FanLedX/branding`). Commit when asked.
- When a rule is missing or two sources disagree, do the work under a stated assumption and
  record it in the relevant file's "Open questions" section. Do not settle it silently.
- Brand-wide rules go in the topic files (`VOICE`, `COLOUR`, `TYPOGRAPHY`, `LOGO`,
  `IMAGERY`). Medium-specific rules go in the medium file (`WEBSITE`, `PRESENTATION`).
- The parent client file is `../../CLAUDE.md`. Deliverables for a project go in that
  project's folder under `Projects/`, not here. This folder holds the brand, not the work.
