# Logo and marks

Part of the Fan Led X brand set. See [BRAND.md](BRAND.md).

---

## The lockup

"Fan" stacked over "Led" in a heavy white italic, with the striped X to the right. It is
a **reversed lockup, for dark grounds only.** Its Figma layer is named "RGB
Logos_FanLedX_Main Logo - Inverse", so a positive version may exist somewhere.

### Files (`assets/logo/`)

| File | What | Use for |
|---|---|---|
| `fanledx-logo.png` | **The master.** 3805 × 1665, transparent, untrimmed. Byte-identical to the image in Figma | Source for everything else |
| `fanledx-logo-trimmed.png` | The master cropped to the artwork + 40px padding (3466 × 1144) | Large raster uses |
| `fanledx-logo-{2000,1000,500,250}.png` | Trimmed, resized, transparent | Web, documents, email signatures |
| `fanledx-logo-{2000,1000}.webp` | As above, in WebP | Web |
| `fanledx-logo-on-black-{2000,1000}.png/.jpg` | On `#050505` with generous padding | Places that can't take transparency: social, video, slide templates |
| `fanledx-logo-traced.svg` | **Vector, traced from the master** (see below) | Scalable web use, signage, large format |
| `fanledx-logo-traced.pdf` | The same vector as PDF | Print, InDesign, Illustrator |

### About the traced vector

**No vector master exists.** In Figma the logo is just a PNG fill, so a Figma "SVG"
export only wraps the raster. The traced files were made on 2026-10-06:

- The wordmark and the 21 strands were traced individually with potrace.
- The gradients (white → lime `#CCFF33` → blue `#0033CC`) and the lime inner outline were
  rebuilt as SVG fills.

At normal sizes it matches the master closely. Under close inspection the gradient
positions and curve detail differ slightly. **Treat it as a stand-in.** If the original
AI/EPS/SVG turns up, replace both traced files with it.

- **Clear space and minimum size** haven't been specified by the designer. Working
  defaults until they are: clear space equal to the cap height of the "F" on every side,
  and at least 96px wide on screen or 25mm in print.
- Don't recolour, stretch, outline, add effects to, or retype the wordmark.
- **There is no light-ground version yet.** On a light ground, put the lockup on a black
  panel or ask for a positive version. Don't make one yourself.

Figma source: node `402:725` on HomeRevised (also `12:576`) in file `j1RBsNAQswR07Im62kAk9K`.

## The X mark

The X is the brand's graphic signature. It is built from slanted parallel strands that
step in size, like people streaming through a space. Each strand carries the gradient.

| File | Look | Use on |
|---|---|---|
| `assets/logo/brand-x.png` | White → lime → blue strands, lime outline | **Dark grounds** |
| `assets/logo/brand-x-stripes.png` | Black → blue → lime strands, navy outline | **Light grounds** |
| `assets/logo/footer-x.png` | A smaller, tighter crop of the dark-ground X | Small placements, footers, sign-offs |

Uses:
- As a large graphic element, cropped or bleeding off the edge, in heroes, cover slides and
  footers next to the tagline.
- As an avatar or favicon.
- As the cursor on the website.

Don't use the X as a letter inside words, and don't rotate it or re-space the strands.

Figma source: node `12:484`.

## Exporting from Figma

The lockup is node `402:725` (also `12:576`). Export the **raw image** (with the Figma
MCP, `download_assets` → `rawImages`). It is the same file as `fanledx-logo.png`. An SVG or
PDF export from Figma only wraps the raster.

## Co-branding

- Parent line: "Fan Led is the sports & events arm of CLX Professionals." Set it as text,
  not a CLX logo lockup, unless CLX supplies one.
- Partner and client logos (e.g. Camborne RFC crest, Victoria Government) go in a separate
  row. They are never locked up with the Fan Led mark. Use them as supplied, in full
  colour or white.
