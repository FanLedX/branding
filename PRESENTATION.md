# Presentations: PowerPoint

Part of the Fan Led X brand set. See [BRAND.md](BRAND.md).

This file covers how a Fan Led deck implements the brand. Brand-wide rules (voice, colour,
type, logo, imagery) live in the topic files. This file holds only what is specific to
slides, and it is written for the person building the deck, not the designer.

**Template:** `fanledx-template.pptx`. Sixteen example slides, one of every kind, on
eight branded layouts. Duplicate the slides you need, delete the rest.
**Reference:** `export.pdf` is a Claude artifact (the Football Drome check-in flow)
styled to the brand. It is the look to aim for on a light ground: blue eyebrows, two-tone
headlines, pills, numbered circles, hairline tables.

---

## The deck in one page

- **Sandwich.** Dark cover, light content, dark statement and close. Dark grounds carry
  the big moments. Ice grounds carry the reading.
- **One message per slide.** The headline is the message, in sentence case, with a full
  stop. Everything under it is proof. If a slide needs two headlines, it is two slides.
- **Two-tone headlines.** On dark: white, then lime. On light: navy, then electric blue.
  Split at a sentence break, never mid-sentence.
- **Lime is a signal.** Lime text on dark grounds, lime eyebrows, lime second lines.
  Never lime text on a light ground, and never a lime fill the size of a card.
- **The X in the corner.** Every content slide carries the X mark bottom right. It is on
  the layout. Do not add logos to slides.
- **Inter, three weights.** Black for headlines, ExtraBold for labels, Regular for body.
- **Left-aligned, always.** Nothing is centred except a number inside a circle.
- **Real people in real venues.** Low-key photography with a black scrim on dark slides,
  rounded-corner cards on light slides. Never an empty stadium.

---

## Canvas

| | Value |
|---|---|
| Size | 16:9 widescreen, 13.333 × 7.5 in (the PowerPoint default) |
| Margins | 0.7 in left and right. Titles start 0.5 in from the top |
| Content area | Starts 2.35 in from the top on light slides, ends at 6.5 in |
| Columns | Two columns are 5.67 in with a 0.6 in gutter. Three cards are 3.71 in with 0.4 in gutters |
| Gaps | 0.4 in between blocks. Keep to it; do not mix 0.3 and 0.5 |
| Corners | Cards and image slots 10 px (0.14 in radius). Chips fully round. Panels and bands square |
| Footer | Slide number and the X mark, bottom right, on the layout. Nothing else |

Export at the native size. Do not change the slide size: the layouts are positioned for it.

## Colour

The template's theme carries the palette, so the first row of PowerPoint's colour picker
is the brand. Pick from there and the deck stays in step if the theme changes.

| PowerPoint slot | Brand colour | Hex | Use on slides |
|---|---|---|---|
| Text 1 | Black | `#050505` | Dark grounds. Body text on light grounds |
| Background 1 | White | `#FFFFFF` | Text on dark grounds. Cards and table rows |
| Text 2 | Ink navy | `#25345D` | Headlines on light grounds. Chip outlines |
| Background 2 | Ice | `#F2F5F7` | The light-slide ground |
| Accent 1 | Electric blue | `#1930FF` | Eyebrows and key phrases on light. Icons, numbers, chart bars, stat callouts |
| Accent 2 | Signal lime | `#C7FF13` | Eyebrows and second lines on dark. Never on light |
| Accent 3 | Deep navy | `#1F294F` | Captions, sources, slide numbers on light |
| Accent 4 | Mist | `#EAECF1` | Alternate light panel |
| Accent 5 | Muted grey | `#9BA0A8` | Table column headers, legal line, slide numbers on dark |
| Accent 6 | Rule grey | `#C9CACB` | Card outlines, table hairlines |

Placeholder grey `#D9D9D9` is for empty image slots only, and is not in the theme.

**Pairings on slides**

| Situation | Treatment |
|---|---|
| Headline on dark | First sentence white, second sentence lime |
| Headline on light | Navy, with the key phrase in electric blue |
| Eyebrow | ExtraBold uppercase, blue on light, lime on dark |
| Big number | Inter Black, electric blue, on ice |
| Chart bars | Electric blue. Highlight one bar in navy, not lime |
| Chip | White fill, 1 pt navy outline, black text |
| Card | White fill, 1 pt rule-grey outline, no shadow |
| Table | White rows, rule-grey hairlines, no vertical lines, no fills |
| Text on photography | White and lime over a black-to-transparent scrim |

No gradients except the X mark, the vertical bars and the photo scrim. No shadows, no
glows, no 3D.

## Type

**Inter only.** Install it from rsms.me/inter or Google Fonts on every machine that will
open the deck. PowerPoint does not substitute weights well: without Inter, headlines fall
back to a regular-weight sans and the deck loses its voice. If a recipient cannot install
fonts, send a PDF.

In the font menu the weights appear as separate names:

| Pick | Weight | Use |
|---|---|---|
| **Inter Black** | 900 | Headlines, card titles, stat numbers. The theme heading font |
| **Inter ExtraBold** | 800 | Eyebrows, chip labels, table headers, statement bands, emphasis lines |
| **Inter Bold** | 700 | Agenda items, table first column, numbers in circles |
| **Inter Medium** | 500 | Lead sentences, captions on dark, chips |
| **Inter** | 400 | Body. The theme body font |

Do not use the bold button on Inter Black or ExtraBold. Pick the weight by name.

**Scale**

| Role | Face / size / leading | Case | Where |
|---|---|---|---|
| Cover title | Black 36 / 105% | Sentence, full stop | Cover |
| Section title | Black 40 / 105% | Sentence, full stop | Dividers |
| Slide title | Black 30 / 105% | Sentence, full stop | Every content slide, same position |
| Statement band | ExtraBold 36 / 120%, tracking -0.5 | **UPPER** | Statement slide |
| Stat number | Black 52, tracking -1 | | Stat callouts, three at most |
| Card title | Black 20 to 22 | Sentence or title | Cards, steps |
| Lead | Medium 18 / 130% | Sentence | First line under a title |
| Body | Regular 14 to 16 / 135% | Sentence | Everything else. 14 is the floor |
| Eyebrow | ExtraBold 11, tracking +1.5 | **UPPER** | Above every title |
| Table header | ExtraBold 10, tracking +1.2, muted grey | **UPPER** | Tables |
| Caption, source | Regular 10 to 12, deep navy | Sentence | Under photos and numbers |

Slide titles sit at the same position on every content slide. Two lines is normal, three
is the limit. If a title needs four, cut words.

**Case.** Headlines are sentence case and end with a full stop. That is the brand rule and
it overrides the general deck habit of dropping the full stop. Uppercase is reserved for
eyebrows, chip-sized labels, table headers, the statement band and venue names over
photography.

## Layouts

Eight layouts, in **Home > Layout** or the slide master. The text boxes on them are
placeholders: click and type, and the size, colour and alignment are already right.

| Layout | Ground | Placeholders | Use for |
|---|---|---|---|
| **Cover (dark)** | Black, logo top left, X mark bleeding off the right | Eyebrow, title, subtitle, meta line | Slide 1 only |
| **Section divider (dark)** | Black, vertical bars along the bottom | Eyebrow ("01 · NAME"), title | Between sections of a deck longer than ten slides |
| **Title only (light)** | Ice, X mark and slide number | Eyebrow, title | The workhorse. Cards, numbers, tables, charts, steps all go on this |
| **Title and body (light)** | Ice | Eyebrow, title, lead, body | A plain argument slide |
| **Two columns (light)** | Ice | Eyebrow, title, left, right | Text beside text, or text beside an image |
| **Title only (dark)** | Black | Eyebrow, title | Full-bleed photography, dark data slides |
| **Statement (dark)** | Black | Statement | One belief in uppercase, white then lime |
| **Photo split (dark)** | Black left, photo placeholder right | Eyebrow, title, body | A case study or venue with one strong photograph |
| **Closing (dark)** | Black, logo, vertical bars | Tagline, contact, legal | Last slide only |

Logos, the X mark, the bars and slide numbers are on the layouts. Never add them to a
slide by hand.

## The sixteen example slides

Each example slide carries speaker notes that say how to use it. In order:

| # | Slide | Shows |
|---|---|---|
| 1 | Cover | Two-tone tagline, meta line |
| 2 | Contents | Numbered circles beside items, a card with an icon |
| 3 | Section divider | Numbered eyebrow, two-tone title, bars |
| 4 | Headline, lead, body, chips | A blue key phrase in the title, the "Built around" chips |
| 5 | Three pillars | Cards with blue icon tiles, mantra line in blue |
| 6 | Two columns with photo | Bold run-in labels, rounded image slot, uppercase caption |
| 7 | Section divider | |
| 8 | Stat callouts | Three big blue numbers with labels and sources |
| 9 | Chart | Native bar chart, blue bars, values on the ends, commentary beside it |
| 10 | Table | Hairline table with muted uppercase headers |
| 11 | Process | Five numbered steps, left to right, arrows between |
| 12 | Statement band | "OPERATIONAL SYSTEMS / ARE HUMAN SYSTEMS." |
| 13 | Full-bleed photo | Photo slot, scrim, white and lime headline bottom left |
| 14 | Photo split | Dark left, photo right |
| 15 | Open questions | Blue 01, 02 labels, one question per line |
| 16 | Closing | Tagline, contact, parent line, legal line |

The text on them is illustrative, not client copy. Replace it.

## Components

Everything below is drawn shapes on the **Title only (light)** layout. Copy one from the
example slide rather than drawing from scratch.

**Eyebrow.** The small uppercase line above every title. Number them through the deck:
`01 · HOW WE WORK`, `02 · THE OFFER`. The separator is a middle dot with spaces. On the
cover it names the deck; on a divider it names the section.

**Numbered circle.** 0.42 in circle, white fill, 1.5 pt electric-blue outline, the number
in Inter Bold 13 blue, centred. Beside agenda items and steps. The larger 0.5 in version
is for the process row.

**Chips.** The "Built around" list: Movement, Trust, Safety, Service, Resilience,
Commercial performance, Return intent. Fully rounded rectangles, 0.42 in tall, white fill,
1 pt navy outline, Inter Medium 12. Chips wrap into rows with 0.16 in between.

**Cards.** White, 1 pt rule-grey outline, 10 px corners, 0.35 in internal padding. An
icon tile (0.7 in blue rounded square with a white outline icon) top left, a Black 22
title, an optional ExtraBold 13 line in blue, then 14 pt body. Three across at most.

**Icons.** Outline icons, 1.75 px stroke, in electric blue on light grounds or white on
a blue tile. `assets/graphics/icon-*.png` holds the set used in the template (strategy,
experience, delivery, arrow). Use the same style (Feather or similar) for new ones. No
filled, duotone or illustrated icons.

**Stat callout.** Inter Black 52 in electric blue, a Medium 16 label beneath, the source
in brackets beneath that in 12 pt deep navy. Three per slide at most. Every number has a
source: the ones in use are in VOICE.md section 6.

**Process row.** Numbered circles left to right with a blue arrow between them, a Black
20 title and a 14 pt line under each. Five steps across the slide at most. Motion is
implied by direction, so never stack a process vertically or run it right to left.

**Arrows.** The → character in Inter Medium, electric blue. In "next" cues and between
steps. No block arrows, no chevrons.

**Open questions.** Blue ExtraBold `01`, `02` labels in the left 0.65 in, the question
in 16 pt beside it, 0.95 in per row. Never present an open question as agreed. The brains
distinguish these on purpose, and so does the slide.

**Photo slots.** Placeholder grey `#D9D9D9` rounded rectangles labelled with the shot
you want. They are a brief for the photographer, not a finished slide. A deck leaves the
building with no grey slots in it.

## Tables

Build with **Insert > Table**, then strip it back:

- Table style: clear it (Table Design, Clear Table). White cells on the ice ground.
- Borders: 0.75 pt rule grey, top and bottom of each row only. No vertical lines.
- Header row: ExtraBold 10, uppercase, muted grey, tracking +1.2. No fill, not bold.
- First column: Inter Bold 14. Other cells: Regular 14, black. Top-aligned.
- Cell padding: 0.12 in top and bottom, 0.15 in left and right.
- Five body rows on a slide at most. Past that, split the table or cut the content.
- Muted grey text for a "Never" or "Not needed" cell, as the artifact does.

## Charts

Charts stay native (Insert > Chart) so the numbers can be edited. The template's chart on
slide 9 is the reference style:

- One series, bars in electric blue. If one bar is the point, make it navy and leave the
  others blue. Do not use lime bars on a light ground.
- No chart title (the slide title does that job), no legend for one series, no gridlines,
  no axis lines, value axis hidden.
- Data labels on the end of each bar, Inter 12, deep navy. Format with the unit (`0"%"`).
- Category labels Inter 12, black. Bar gap 60%.
- Commentary beside the chart in a 3.6 in column: a bold "What it means." line, two
  sentences, and the source in 12 pt deep navy.
- One point per chart. If a chart needs two sentences to explain, it is two charts.

Keep every chart in a deck looking the same: same label colour, size and font. Vary only
where a chart needs it.

## Photography

Rules are in IMAGERY.md. On slides:

- **Full bleed (slide 13).** Photo fills the slide, the scrim image sits above it, text
  above that. Replace the photo with right-click, Change Picture, which keeps the stacking.
  If you insert a new picture instead, send it to the back.
- **Photo split (slide 14).** Click the picture icon in the right half. It fills and
  crops automatically. Reposition the crop so the people, not the architecture, are in
  frame.
- **Card image (slide 6).** Insert the picture, then Picture Format, Crop, Crop to Shape,
  rounded rectangle, and match the 10 px corner of the slot.
- No colour filters, duotones or brand-colour overlays. The only treatment is the scrim.
- Caption in uppercase ExtraBold 10 blue under a card image: `ROD LAVER ARENA · MELBOURNE`.

Client and partner logos (Camborne RFC, Victoria Government) go in their own row on a
light slide, as supplied, in full colour or white. Never locked up with the Fan Led mark.

## Writing for slides

VOICE.md governs. On slides specifically:

- **The headline is the message.** Not "Market overview" but "Fans are cooling. The
  market is not." A reader who sees only the headlines should get the whole argument.
- **Six lines of body at most**, 16 pt. If it needs more, it is a pre-read, not a slide.
- **Verbatim lines stay verbatim.** The tagline, the proposition, the belief, the pillar
  mantra. Do not paraphrase them in headline positions.
- **One set of pillar names per deck.** Strategy, Experience, Delivery for brand-level
  decks; the Services set when listing services. Strategy is always first.
- **"Move, feel and behave"** once per section, never twice on a slide.
- **Numbers carry their source in brackets.** (Gemba, 2024). (PwC). Every time.
- **British English. No em dashes. No banned words** (synergy, leverage, holistic,
  best-in-class, world-class, solutions-driven, unlock).
- **Speaker notes carry the narration**, never a text box at the bottom of the slide.
- **Naming.** "Fan Led X" on the cover and in the file name. "Fan Led" in running copy.
  "FLX" only in file names.

File names: `FLX <Project> <Topic> <YYYY-MM-DD>.pptx`, for example
`FLX Camborne Connect proposal 2026-11-20.pptx`.

## Do and don't

| Do | Don't |
|---|---|
| Pick colours from the theme row | Type hex values into shapes |
| Pick Inter Black by name for headlines | Press bold on Inter |
| End headlines with a full stop | Use title case in headlines |
| Leave the lower third empty if the message is done | Fill the slide to the edges |
| Use the layouts' placeholders | Draw a new text box for a title |
| Put the lime line second | Put lime on a light ground |
| One chart, one point, blue bars | Rainbow series, 3D, gridlines |
| Replace every grey photo slot before sending | Send a deck with grey boxes in it |

Nothing is centred. No accent lines under titles, no coloured header bars, no sidebars,
no drop shadows, no clip art, no bullet points where a numbered circle or a chip would do.
Bullets are allowed in body text when the items are genuinely a list; let the layout
supply the bullet and never type a • character.

## Sending and exporting

- **PDF for anything that leaves the team.** File > Export > PDF. Fonts embed, layouts
  freeze, nothing shifts on a machine without Inter.
- **PPTX only to people who will edit it**, and tell them to install Inter first.
- **Google Slides** imports the file but loses Inter weights until you reselect them
  (Inter is on Google Fonts, all weights). Charts survive. Check every slide after import.
- **Keynote** opens the file and keeps the type and layouts. It drops the native charts,
  so export from PowerPoint when a deck has one.
- **Notion and Teams previews** render the PDF, not the PPTX. Share the PDF.

## QA before it goes

1. Every title in the same place, same size, sentence case, full stop.
2. No lime on a light ground. No black text on a dark one.
3. No text overflowing its box, no word broken across lines, no orphaned last word.
4. No grey photo slots left. No "Illustrative" notes left on slides that are now real.
5. Every number has a source. Every open question is on the open questions slide.
6. One set of pillar names, start to finish.
7. The file name follows the pattern, and the cover meta line carries the date and status.
8. Export the PDF and page through it once at full screen.

## Maintaining the template

`fanledx-template.pptx` is the master. Edit it in PowerPoint, not in a copy of a deck.
Theme colours and fonts live in the Slide Master (View, Slide Master); the eight layouts
and the X mark, slide number and vertical bars sit on the layouts, so a change there
reaches every slide. The graphics it uses are in `assets/graphics/`.

The template was first generated with pptxgenjs and the generator was retired on
2026-11-20. If a wholesale rebuild is ever needed, the rules in this file are the
specification. Validate any new build with the pptx skill's `scripts/office/validate.py`
and open it in PowerPoint before replacing the file.

## Open questions

- **Light-ground lockup.** There is no positive logo, so light slides carry only the X
  mark. When a positive lockup arrives, add it to the light layouts.
- **Lime on light.** The artifact darkens lime to an olive for a headline on white.
  COLOUR.md says lime never goes on light grounds, so the template uses blue there. If
  the client wants a darkened lime for light grounds, it needs a named value in COLOUR.md
  first.
- **Founder's name.** The closing slide says "Tony · Founder". Surname and title to come.
- **Chart rendering.** The native chart validates and reads correctly from the file, but
  this build was visually checked through Keynote, which does not render it. Open slide 9
  in PowerPoint before relying on it as the reference.
