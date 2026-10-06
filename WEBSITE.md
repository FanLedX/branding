# Website: fanledx.com

Part of the Fan Led X brand set. See [BRAND.md](BRAND.md).

This file covers how the website implements the brand. Brand-wide rules (voice, colour,
type, logo, imagery) live in the topic files. This file holds only what is specific to
the site.

**Code:** `Cohoda/Clients/FLX/Projects/Fan Led X/Fan Led X Website/fanledx.com/`, an Astro 5
static site with Tailwind 3, GSAP and Lenis. Its own `CLAUDE.md` covers the build, deploys
and workflow.

**Design:** the Figma file `j1RBsNAQswR07Im62kAk9K`. The current pages are `Homenewest`,
`ServicesRevised`, `ExperiencesRevised`, `Rod Laver Arena (Experience)`,
`Sustainability` and `Contact`, plus `Menu Mobile & Ipad`. Each has Desktop 1440, iPad
810/834 and Mobile 390 frames.

---

## Colour tokens

These are defined in `src/styles/tokens.css` and exposed in Tailwind as `fl-*`.

| Token | Value | Brand colour |
|---|---|---|
| `--fl-black` | `#050506` | Black (dark grounds) |
| `--fl-near-black` | `#050505` | Black (text on light) |
| `--fl-ink` | `#0A0B0E` | Raised dark surface |
| `--fl-volt` | `#CCFF33` | Signal lime. **Should be `#C7FF13`** (see drift) |
| `--fl-blue` | `#1930FF` | Electric blue |
| `--fl-navy` | `#0B1C6B` | Not used in current Figma |
| `--fl-ink-navy` | `#25345D` | Ink navy |
| `--fl-deep-navy` | `#161F36` | Close to deep navy `#1F294F` (see drift) |
| `--fl-ice` | `#EDF1F5` | Ice (see drift) |
| `--fl-grey` | `#E6E6E6` | Placeholder grey |
| `--fl-mute` | `#9BA0A8` | Muted text on dark |
| `--fl-line` / `--fl-line-ice` | white 12% / navy 14% | Hairlines on dark / light |

Heading colours vary by section in Figma, so there is no single heading colour. Pillars
is navy. Strategy, Infrastructure, Experience and "Our Fans" are blue. Approach, Work and
Founder are near-black.

## Type in code

- Inter Variable via `@fontsource-variable/inter`. `global.css` still imports
  `@fontsource-variable/montserrat`, a v2 leftover that could be removed.
- `h1–h4` default to weight 900, tracking -0.01em, leading 1.05. Case is set per element.
- Fluid sizes in Tailwind: `text-mega` `clamp(2.75rem, 8.5vw, 8.5rem)`, `text-big`
  `clamp(2rem, 5.5vw, 4.75rem)`, `text-mid` `clamp(1.5rem, 3vw, 2.5rem)`.
- `.eyebrow`: 800 weight, uppercase, 0.08em tracking, 0.8rem, blue (`.eyebrow-volt`,
  `.eyebrow-white` variants).

## Components that carry the brand

| Brand element | Implementation |
|---|---|
| Buttons | `.btn` pill: 800 weight, uppercase, 0.82rem, 1.5px border, 999px radius. Variants: `--volt-blue`, `--volt-navy`, `--blue`, `--outline`, `--white-outline`, `--ghost` |
| Button hover | A 2px lift, a soft glow tinted to the variant, and the arrow nudges 5px. No colour invert and no scale |
| Gradient text | `.x-grad`, lime → blue clipped to text |
| Vertical bars | `VerticalBars.astro` + `.vbars` (36 bars, lime → blue), with an `.is-thin` variant |
| Light sections | `.sec-light`: ice ground, near-black headings, blue selection |
| Logo | `public/images/home/brand/fanledx-logo.png` in `Header.astro` |
| X mark | `public/images/home/brand/brand-x*.png`, `footer-x.png` |
| Cursor | `src/scripts/cursor.ts` swaps the pointer for the brand X on fine-pointer devices; `[data-magnetic]` pulls buttons toward the cursor |
| Selection | Lime on dark, blue on light |
| Focus | 2px blue outline, 3px offset |

## Layout

| | Value |
|---|---|
| Container | 1280px (`--container`), padding `clamp(1.25rem, 5vw, 4.6rem)` |
| Breakpoints | `tab` 768px, `dt` 1024px, matching the 390 / 810 / 1280+ Figma frames |
| Section padding | `clamp(4.5rem, 9vw, 8rem)` vertical |
| Rhythm | Dark hero → ice and white sections alternating → dark statement band → dark footer |
| Image radius | 10px on cards; larger cards 18–27px |

## Motion

Motion expresses "movement and flow".

- **Lenis** smooth scroll drives GSAP's ticker.
- **Reveals:** `.reveal` fades and rises 28px. `.reveal-line` stagger-unmasks headline lines.
  There is also `[data-parallax]`.
- **Pinned horizontal scroll** for the three pillars on desktop.
- Easing `cubic-bezier(.2,.7,0,1)` (`ease-flx`).
- `prefers-reduced-motion` is respected everywhere: content is static and visible.

## Photography notes

- The hero image is genuinely very dark (mean about 7.6/255). Figma shows it brighter, so
  the `<img>` gets `brightness(2.3) contrast(0.95)`. Keep that.
- Photos are optimised JPGs. Logos and icons are transparent PNGs displayed with
  `object-contain`.

## Site copy conventions

- Running copy uses "Fan Led". The `<title>` and meta use "Fan Led X".
- Footer: tagline in uppercase (white / lime), "Fan Led is the sports & events arm of CLX
  Professionals.", "© 2026 Fan Led Experience. All rights reserved.", contact
  `info@fanledx.com`, LinkedIn.
- `public/llms.txt` holds the site summary for AI crawlers. Keep it in line with VOICE.md.

## Figma vs code drift (2026-10-06)

| | Newest Figma | Code |
|---|---|---|
| Lime | **`#C7FF13`** (decided brand value) | `#CCFF33`. **Needs updating** |
| Blue fill | `#1A33FF` on some shapes | `#1930FF` |
| Light ground | `#F2F5F7`, `#EAECF1` | `#EDF1F5` |
| Small navy text | `#1F294F` | not tokenised |

The lime is decided: change `--fl-volt` to `#C7FF13`, and change the `rgb` glow value
`204, 255, 51` in `global.css` to `199, 255, 19`. The other rows are still open (see
COLOUR.md).
