# ClickUp — spectrum-powered work playground

## Overview

A bright, confident software style that pairs tightly packed geometric headlines with expansive product stages. White and charcoal canvases alternate with electric violet, pink, orange and blue light; interfaces, soft sculptural objects and human portraits give the technology a playful physical presence. It suits ambitious productivity platforms and capability-rich products, with spacious storytelling around densely detailed demonstrations. A separate editorial treatment pairs elegant serif titles with paper objects and retro office ephemera.

### Essentials

- The promise reads as one continuous, tightly fitted thought: Plus Jakarta Sans 60px/1.1, weight 700, -0.035em tracking; recurring section headings use 48px/1.25 at 650.
- The opening is a left-aligned promise above a full-width working product, not a split hero: a 1080px content stage, 52px paired actions, then a 1080×680px interface frame with a 16px radius.
- Actions are compact rounded rectangles, not capsules: the opening pair uses 15px corners and 14px 20px padding; subsequent calls generally use 12px corners and navigation uses 8px.
- Color behaves like energy behind useful objects: white dominates the default page, one black capability chapter supplies contrast, and saturated spectrum color concentrates in glows, sculptural accents and a 32px-radius conversion stage rather than every section.
- Every page needs a tangible product emblem and a light-backed demonstration: soft inflated forms or layered interface fragments sit above violet-pink-blue light. If no finished artwork exists, use a custom rounded geometric object with a colored rim and a real miniature interface instead.
- Proof is engineered into the layout: thin #e8e8e8 rules on white, #2a2a2a rules on black, mono uppercase labels at 14px/18px, and closely joined cards; keep large areas of whitespace inside proof tiles rather than enlarging every number.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Spectrum blue | `#0b88fd` | `--color-blue` | background, accent | Cool lower edge of spectrum artwork. |
| Spectrum orange | `#fc6d2d` | `--color-orange` | background, accent | Hot upper-right region of the closing spectrum field. |
| Spectrum pink | `#f73699` | `--color-pink` | background, accent | Central energetic region of spectrum artwork. |
| Violet label | `#6647f0` | `--color-violet` | accent, text, border | Mono proof labels, selected pricing controls and spectrum transitions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#202020` | `--color-ink` | text, action | Primary headlines and dark actions on the light canvas. |
| Black chapter | `#000000` | `--color-black` | background | Immersive capability chapters and dark product pages. |
| Footer charcoal | `#111111` | `--color-dark-panel` | surface, background | Dark footer and layered black materials. |
| Charcoal seam | `#2a2a2a` | `--color-dark-rule` | border, surface | Shared seams in black capability grids. |
| Body gray | `#646464` | `--color-body` | text | Readable supporting paragraphs and navigation. |
| Dim continuation | `#7b7b7b` | `--color-dim` | text | Secondary phrase on dark sections and superseded values. |
| Secondary gray | `#838383` | `--color-muted` | text | Short support lines, captions and low-priority labels. |
| Dark-theme body | `#b4b4b4` | `--color-inverse-body` | text | Support copy on black. |
| Light hairline | `#e8e8e8` | `--color-rule` | border | Fine card outlines and shared grid seams. |
| Soft white type | `#eeeeee` | `--color-inverse` | text | Headings and labels over dark sections. |
| Secondary action gray | `#f0f0f0` | `--color-secondary-action` | action, surface | Secondary buttons against white. |
| Cool white stage | `#f8f9fa` | `--color-soft` | surface, background | Interface frames, solution panels and subtle announcement bands. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default marketing canvas, light cards and reversed actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Conversion violet | `#7a3fe6` | `--color-pricing-violet` | background | Compact pricing conversion stage beneath its colored artwork. |
| dark product pages | Lavender signal | `#b38cff` | `--color-lavender` | text, accent, border | Eyebrows, checks, quote rules and focus indicators on dark product pages. |
| editorial feature campaigns | Rose paper | `#ff9ed2` | `--color-paper-pink` | surface | Second physical sticky note. |
| editorial feature campaigns | Lemon paper | `#ffffa5` | `--color-paper-yellow` | surface | First physical sticky note. |
| editorial feature campaigns | Mint paper | `#a5ffd6` | `--color-paper-mint` | surface | Third physical sticky note. |
| editorial feature campaigns | Editorial black | `#080808` | `--color-editorial-ink` | text | Serif editorial headings and long mono explanations. |
| dark showcase pages | Graphite shadow | `#0a0a0a` | `--color-card-bottom` | surface | Lower stop of dark gallery cards. |
| dark showcase pages | Graphite highlight | `#141414` | `--color-card-top` | surface | Upper stop of dark gallery cards. |
| dark showcase pages | Dark table edge | `#2f2f2f` | `--color-table-rule` | border | Comparison tables and bordered question lists. |

## Typography

- **Plus Jakarta Sans** — Marketing headlines, proof numbers and major product-page text. Geometric sans with broad circular counters, a friendly shape and very tight display fitting. Font stack: "Plus Jakarta Sans", Arial, sans-serif.
- **Inter** — Supporting paragraphs, actions, navigation and footer links. Neutral compact sans that keeps information clear beneath expressive headings. Font stack: "Inter", Arial, sans-serif.
- **Sometype Mono** — Uppercase section markers, proof labels and platform captions. Open, slightly mechanical monospace used as a technical counterpoint to the geometric display face. Font stack: "Sometype Mono", ui-monospace, monospace.
- **EB Garamond** (only for editorial feature campaigns) — Oversized single-word titles, editorial section headings and paper-card titles. High-contrast old-style serif, thin and elegant at display scale, with expressive italics. Font stack: "EB Garamond", Georgia, serif.
- **IBM Plex Mono** (only for editorial feature campaigns) — Large centered explanatory statement and widely tracked micro-labels. Typewriter-like technical voice that complements the serif and office-paper imagery. Font stack: "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| inverse-display | Plus Jakarta Sans | 700 | 80px | 1.2 | -0.04em | fixed | Centered statement introducing the black capability chapter. |
| inverse-emphasis | Plus Jakarta Sans | 700 italic | 80px | 1.2 | -0.04em | fixed | One emphasized possessive or human-centered word inside the black chapter statement. |
| chapter-display | Plus Jakarta Sans | 700 | 76px | 1.05 | -0.04em | fixed | A major sculptural feature introduction, with a restrained dark-to-gray text gradient. |
| display | Plus Jakarta Sans | 700 | 60px | 1.1 | -0.035em, features "calt" 0 | fixed | Default opening promise and large closing statement. |
| heading | Plus Jakarta Sans | 650 | 48px | 1.25 | -0.035em | fixed | Default section heading; centered for broad promises and left-aligned for proof. |
| stat | Plus Jakarta Sans | 650 | 34px | 1.2 | -0.04em | fixed | Numbers in joined return-on-investment proof cards. |
| hero-support | Inter | 400 | 22px | 28px | -0.0227em, features "calt" 0 | fixed | Opening support sentence; usually breaks into two short lines. |
| support | Inter | 500 | 18px | 1.333333 | -0.02em | fixed | Short muted support lines under section headings. |
| button | Inter | 650 | 18px | 1.333333 | -0.02em, features "calt" 0 | fixed | Opening primary and secondary actions. |
| portrait-quote | Inter | 600 | 18px | 24px | -0.014em | fixed | Short white quotation over a full-height customer portrait. |
| body | Inter | 500 | 16px | 22px | -0.02em | fixed | Capability descriptions and workflow rows. |
| eyebrow | Sometype Mono | 500 | 16px | 1.25 | normal, uppercase | fixed | Section markers and short proof statements. |
| small | Inter | 500 | 14px | 20px | -0.011em | fixed | Navigation and compact feature-card descriptions. |
| caption | Sometype Mono | 500 | 14px | 18px | normal, uppercase | fixed | Stat labels and platform captions. |
| footer-link | Inter | 500 | 14px | 1 | normal | fixed | Dense footer navigation. |
| footer-heading | Inter | 600 | 14px | 1.5 | normal | fixed | Footer column headings. |
| tab-label | Inter | 600 | 14px | 20px | normal | fixed | Compact solution-selection tabs. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| editorial feature campaigns | editorial-title | EB Garamond | 400 | 240px | 0.72 | normal | fixed | A single short feature name above physical package artwork. |
| before-and-after proof on dark showcase pages | comparison-after | Plus Jakarta Sans | 750 | 144px | 1 | -0.8px | size clamp(5rem, 10vw, 9rem) | The improved value, twice the type size of the superseded value. |
| dark flagship product pages | dark-hero | Plus Jakarta Sans | 700 | 76px | 1.05 | -0.04em | size clamp(48px, 20px + 4.6667vw, 76px) | Centered two-line promise above the convergence diagram. |
| before-and-after proof on dark showcase pages | comparison-before | Plus Jakarta Sans | 600 | 72px | 1 | -0.0111em | size clamp(3rem, 5vw, 4.5rem) | Muted struck-through original value. |
| dark showcase pages | showcase-hero | Plus Jakarta Sans | 700 | 68px | 1.04 | -0.04em | size clamp(2.5rem, 5vw, 4.25rem) | Centered product-output promise above demo tabs. |
| dark showcase pages | showcase-heading | Plus Jakarta Sans | 700 | 60px | 1.04 | -0.04em | size clamp(2.5rem, 4.2vw, 3.75rem) | Gallery, process and closing headlines. |
| editorial feature campaigns | editorial-close | EB Garamond | 400 | 52px | 1.15 | -0.02em | size clamp(32px, 4.2vw, 52px) | Narrow two-line closing invitation. |
| dark product pages | dark-heading | Plus Jakarta Sans | 700 | 48px | 1.15 | -0.035em, features "calt" 0 | fixed | Left-aligned chapter titles above ruled capability grids. |
| pricing pages | price | Plus Jakarta Sans | 700 | 40px | 1.1 | -0.03em, features "tnum" | fixed | Plan prices with tabular figures and baseline-aligned smaller old prices. |
| editorial feature campaigns | editorial-explainer | IBM Plex Mono | 400 | 36.7px | 1.3 | -0.02em | fixed | Long centered explanation within a 920px-wide stage. |
| before-and-after proof on dark showcase pages | proof-quote | Plus Jakarta Sans | 500 | 26px | 1.45 | -0.015em | size clamp(1.25rem, 1.9vw, 1.625rem) | Quote next to the giant numeric comparison. |
| editorial feature campaigns | paper-title | EB Garamond | 500 | 20px | 1.2 | normal | fixed | Small benefit headline on a paper note. |
| dark showcase pages | gallery-title | Plus Jakarta Sans | 600 | 18px | 1.3 | -0.015em | fixed | Short title below a finished-output thumbnail. |
| dark showcase pages | question | Plus Jakarta Sans | 600 | 17px | 1.4 | -0.01em | fixed | Accordion question row. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the headline family separate from the body family: the warmer geometric display is not interchangeable with the compact interface sans.
- Display tracking tightens to -0.035em or -0.04em; do not apply that fitting to body text or mono labels.
- Use gradients as neutral tonal shading on headlines, not rainbow lettering across every word. Italic emphasis stays in the same family and usually affects just one word.
- In the editorial variant the enormous serif title is a short name, not a long sentence. Its unusually tight 0.72 line height belongs only to that single-line treatment.

## Layout

**Density:** Airy narrative stages surround compact, highly detailed product and proof grids.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Label-to-stat or compact heading-to-copy separation. |
| 12px | Section-heading support gap, paired actions and stacked workflow rows. |
| 20px | Gallery gaps, common section markers and content gutter. |
| 24px | Dark feature-card inset and title-to-action gap. |
| 32px | Hero support-to-action gap and spacious inset details. |
| 40px | Outer desktop container gutters. |
| 48px | Chapter composition gap and closing-stage inset. |
| 64px | Opening text-to-product stage gap and major two-column proof gap. |
| 80px | Default vertical section padding. |
| 100px | Separation between pricing narrative sections. |
| 120px | Dark showcase chapter padding. |
| 140px | Editorial chapter padding. |
| 220px | Vertical space above and below the editorial mono explainer. |

### Containers and grids

- **content-stage**: max width 1120px · side padding 20px. Centered outer stage yielding 1080px of content at desktop; align navigation, hero and most chapter content to the same edges.
- **wide-stage**: max width 1440px · side padding 20px. Full-bleed-with-a-margin campaign art and closing conversion panels.
- **gallery-grid**: max width 1080px · 3 columns · gap 20px. Equal-width portrait proof or output cards, approximately 347px each.
- **dark-feature-grid**: max width 1080px · 3 columns · gap 1px. Black cards share charcoal seams rather than floating as separate rounded tiles.
- **footer-grid**: max width 1160px · 5 columns · side padding 40px. Five compact navigation columns; a second group can sit below the first within one column.
- **pricing-grid** (only for pricing pages): max width 1200px · 4 columns · gap 16px. Equal-width plan columns, followed by a full-width premium band.
- **editorial-stage** (only for editorial feature campaigns): max width 1080px · side padding 72px. Centered serif headings, video and three-column explanatory cards; full-width carousels can escape this frame.

## Corner radius

| Element | Radius |
| --- | --- |
| opening-actions | 15px |
| standard-actions | 12px |
| navigation-actions | 8px |
| product-frame | 16px |
| portrait-proof | 18px |
| gallery-and-plan-card | 20px |
| campaign-stage | 32px |
| small-tabs | 54px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | workflow-row | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px` | Subtle lift on white workflow rows inside cool white solution panels. |
| dark showcase pages | gallery-edge | `rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset` | Faint upper highlight on charcoal cards. |
| editorial feature campaigns | paper-lift | `rgba(0, 0, 0, 0.12) 2px 4px 12px 0px, rgba(0, 0, 0, 0.08) 1px 2px 4px 0px` | Soft physical lift under colored paper notes. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff`

#### Product frame · level 1

**Use:** Opening working interface.

**CSS:** `background: #f8f9fa; border: 1px solid #e8e8e8; border-radius: 16px; overflow: hidden`

**Observed:** A large straight-on application window, not a device floating in empty space.

**Transfer:** Show actual content, navigation and a useful workflow in a coherent miniature application.

#### Solution panel · level 1

**Use:** Tabbed workflow story.

**CSS:** `background: #f8f9fa; border-radius: 32px`

**Observed:** Two balanced columns: benefit statement and replacement list on the left, raised workflow rows on the right.

**Transfer:** Use the cool neutral fill to unite explanation and a concrete sequence of product actions.

#### Black chapter · level 0

**Use:** Immersive technical capability material.

**CSS:** `background: #000000; color: #eeeeee; border-radius: 32px`

**Observed:** On a light page this forms a long inset chapter with 20px outer margins; dark product pages extend black to the edges instead.

**Transfer:** Reserve the tonal inversion for a major product chapter, keeping readable headings and low-contrast seams.

#### Spectrum conversion stage · level 1

**Use:** The major conversion payoff.

**CSS:** `background: radial-gradient(132% 74% at 96% 1%, #fc6d2d 23%, #f73699 57%, #6647f0 95%, #0b88fd 115%); border-radius: 32px; overflow: hidden`

**Observed:** A luminous, lightly grainy field supports white type, a white action and layered desktop/mobile windows. The field is larger than its clipping frame and subtly tilted.

**Transfer:** Use the spectrum as a contained environment for the final promise rather than as a page-wide wash.

#### Navigation glass · level 2

**Use:** Sticky top navigation backdrop.

**CSS:** `background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(6px)`

**Observed:** White translucent navigation becomes charcoal translucent on dark product pages.

**Transfer:** Keep underlying content slightly visible without lowering link contrast.

#### Charcoal gallery · level 1

**Only for:** dark showcase pages

**Use:** Finished-output thumbnail cards.

**CSS:** `background: linear-gradient(#141414, #0a0a0a); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 20px; box-shadow: rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset; overflow: hidden`

**Observed:** The upper edge catches a faint white radial sheen; the thumbnail is brighter than the shell.

**Transfer:** Keep framing nearly black so output examples can carry their own varied palettes.

#### Paper note · level 1

**Only for:** editorial feature campaigns

**Use:** Tactile benefit cards.

**CSS:** `background: #ffffa5; box-shadow: rgba(0, 0, 0, 0.12) 2px 4px 12px 0px, rgba(0, 0, 0, 0.08) 1px 2px 4px 0px`

**Observed:** Lemon, pink and mint notes are slightly tilted, with imperfect top edges and folded lower corners.

**Transfer:** Use paper as an editorial object, not the default material for ordinary feature cards.

## Components

### Navigation

**Use:** Compact sticky global navigation.

**CSS:** `height: 60px; position: sticky; top: 0px; background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(6px)`

**Text style:** `small` — Inter 500 · 14px/20px · tracking -0.011em

**Observed:** Logo at left, small dropdown links in the middle, a demo link and compact login/signup actions at right; inner stage is 1120px including 20px side padding. Dark product pages reverse the backdrop and link colors.

**Transfer:** Keep brand navigation visually quieter than the promise beneath it.

### Primary button

**Use:** Default first-screen conversion.

**CSS:** `background: #202020; color: #ffffff; border-radius: 15px; padding: 14px 20px; height: 52px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — Inter 650 · 18px/1.333333 · tracking -0.02em

**Observed:** The primary action leads a paired row, with a small reassurance line directly beneath it. Later sections use 12px corners; inverse actions on black or spectrum fields are white.

**States:** Declared: hover background rgba(32, 32, 32, 0.8).

**Transfer:** Use one direct verb-led action and a quieter alternative.

### Secondary button

**Use:** Demo or supporting conversion beside the primary.

**CSS:** `background: #f0f0f0; color: #202020; border-radius: 15px; padding: 14px 20px; height: 52px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — Inter 650 · 18px/1.333333 · tracking -0.02em

**Observed:** Aligned to the primary button with a 12px gap; uses a filled gray surface rather than an outline.

**States:** Declared: hover background rgb(222, 222, 222).

### Solution tab

**Use:** Switch between audience or workflow stories.

**CSS:** `border: 2px dashed transparent; border-radius: 54px; padding: 4px 12px; height: 32px; color: #646464`

**Text style:** `tab-label` — Inter 600 · 14px/20px

**Observed:** A fine dashed pseudo-outline surrounds inactive tabs. The selected variant uses a blue outline and pale blue backing, distinct from the violet used for proof labels.

**States:** Declared: hover background-color rgb(250, 250, 250).

**Transfer:** Keep a single row of short category labels above Solution panel.

### Workflow row

**Use:** Concrete product actions inside a solution panel.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 12px; display: flex; align-items: center; gap: 12px; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`

**Text style:** `body` — Inter 500 · 16px/22px · tracking -0.02em

**Observed:** Four short rows stack with small friendly avatar or object icons at the left; labels describe an action rather than a feature category.

**Transfer:** Show a plausible sequence of useful work for the new product.

### Stat tile

**Use:** Joined quantified proof.

**CSS:** `background: #ffffff; border-top: 1px solid #e8e8e8; padding: 20px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `stat` — Plus Jakarta Sans 650 · 34px/1.2 · tracking -0.04em

**Observed:** Four closely joined white tiles share light vertical seams and gently rounded top junctions. A violet mono caption sits above the number; a much smaller explanation anchors the bottom of a roughly 281px-tall card.

**Transfer:** Preserve the deliberately empty middle and use only substantiated metrics.

### Portrait testimonial

**Use:** Human customer proof.

**CSS:** `border: 1px solid rgba(0, 0, 0, 0.3); border-radius: 18px; position: relative; overflow: hidden`

**Text style:** `portrait-quote` — Inter 600 · 18px/24px · tracking -0.014em

**Observed:** Three tall 347×613px portrait videos sit side by side. A dark, progressively blurred bottom zone holds a short white quote, name, role and a customer mark.

**Transfer:** Use real people in real working environments; preserve the portrait ratio and bottom-caption hierarchy.

### Footer link

**Use:** Dense multi-column navigation ending.

**CSS:** `color: #646464; padding: 9px; border-radius: 9px`

**Text style:** `footer-link` — Inter 500 · 14px/1

**Observed:** Links occupy compact rows in five columns under small bold headings. The upper logo is followed by navigation; a broad lower breathing zone separates links from social icons, trust marks and the thin legal row. Dark pages use light gray links over charcoal.

**States:** Declared: hover background-color rgba(0,0,0,.04); color rgb(100,100,100).

### Feature cell

**Use:** Technical benefits in the black chapter.

**CSS:** `background: #000000; display: flex; flex-direction: column; justify-content: space-between; overflow: hidden`

**Text style:** `small` — Inter 500 · 14px/20px · tracking -0.011em

**Observed:** Three equal columns share 1px charcoal seams. A mono uppercase label and compact gray description sit at the top with 24px side insets; a small luminous interface sculpture fills the lower half.

**Transfer:** Make each lower illustration explain one mechanism; do not repeat the same abstract glow in every cell.

### Gallery card

**Only for:** dark showcase pages

**Use:** A browsable collection of finished outputs.

**CSS:** `background: linear-gradient(#141414, #0a0a0a); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 20px; overflow: hidden`

**Text style:** `gallery-title` — Plus Jakarta Sans 600 · 18px/1.3 · tracking -0.015em

**Observed:** A bright 329×205px thumbnail sits inside an approximately 347×330px shell with an 8px image inset. Beneath it, a short title and muted two-line description explain the output. Cards repeat in three columns with 20px gaps.

**Transfer:** Show varied, finished artifacts rather than identical generic app windows.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side subscription comparison.

**CSS:** `background: #ffffff; border: 1px solid #e8e8e8; border-radius: 20px; display: flex; flex-direction: column`

**Text style:** `price` — Plus Jakarta Sans 700 · 40px/1.1 · tracking -0.03em

**Observed:** A 24px-top, 22px-side header holds plan name, price, billing note and full-width action. Bordered feature bands follow. One recommended card is black with white type and a white action; the entry plan uses a dark action while other light plans use gray actions. A full-width premium spectrum band follows the four columns.

**Transfer:** Use inversion, not only a colored badge, to distinguish the recommended tier.

### Question row

**Only for:** dark showcase pages

**Use:** Objection handling in a ruled list.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 24px; padding: 22px 24px; color: #eeeeee`

**Text style:** `question` — Plus Jakarta Sans 600 · 17px/1.4 · tracking -0.01em

**Observed:** Questions are enclosed by a thin dark table frame with horizontal rules and a plus at the far right. The light pricing variant uses a narrower 851px list, smaller sans text, bottom rules and chevrons.

**States:** Declared: focus-visible outline 2px solid #b38cff; outline-offset -2px.

## Imagery and graphics

### Working interface stage

**Use:** Opening product proof and closing application windows.

**Observed:** Straight-on task, document and conversation views show actual populated work, subtle browser chrome, white panels and small colored status details. The opening frame spans the full content width; closing windows overlap a bright field in translucent shells.

**Transfer:** Create a credible miniature workflow using the new product's real information architecture. Keep the surrounding marketing styling separate from the internal app UI.

### Soft spectrum sculpture

**Use:** Tangible emblem in a major feature introduction.

**Observed:** A compact, inflated mask-like object blends orange, hot pink, violet and blue, with rounded cutouts, soft specular highlights and a low soft shadow. It is isolated under a monumental heading before appearing on a human portrait.

**Transfer:** Choose an object metaphor appropriate to the new product; the minimum version is a custom rounded shape with two or three cutouts and believable depth, not a stock icon.

**Build:** Draw a rounded SVG silhouette with a violet-to-pink-to-orange-to-blue fill, add a soft white highlight near the upper edge, a darker lower rim and a blurred black shadow below. Keep the object around 436×222px on desktop and surround it with white space.

### Prismatic horizon

**Use:** Light behind the black chapter statement and final dark conversion call.

**Observed:** A broad low blue-violet-pink-orange glow rises from the bottom of black space. Fine grain and faint horizontal data-like traces keep it from reading as a smooth generic gradient.

**Transfer:** Use the horizon as the required luminous backing for one clear product statement or working demonstration; preserve black at the top for legibility.

**Build:** Place overlapping wide elliptical radial gradients beneath the content: blue at left, violet and pink at center, warm orange at right, each at roughly 0.3–0.6 alpha, blurred 40–80px. Clip them into the lower third of the stage, add a very faint SVG noise layer and sparse horizontal paths fading toward the sides.

### Capability micro-sculptures

**Use:** Lower regions of Feature cell.

**Observed:** Small dark interface fragments become physical objects: stacked conversation windows, rotating model pills, code-like preference panels, a memory card, connected application nodes and a progress strip. Colored edge light is thin, localized and set against deep black.

**Transfer:** Turn one product mechanism into a small diagram or layered interface object per card; preserve empty black space around it.

**Build:** Stack two or three charcoal rounded rectangles with 8–18px corners and 1px low-alpha white outlines. Place a blurred conic spectrum layer 20–45px behind the front object, mask the light to one rim and fade rear objects with opacity. Connect nodes with thin gray SVG curves where useful.

### Pastel product atlas

**Use:** Broad capability overview on a light canvas.

**Observed:** An edge-faded matrix of small white icon tiles surrounds four larger product windows. Hairline seams, pale cream, blue, lavender and pink backdrops make the central windows readable without turning the whole section colorful.

**Transfer:** Use a dense peripheral vocabulary of tools around a few larger core capabilities; keep peripheral icons monochrome and central examples useful.

**Build:** Build a 1px-seam tile grid with simple gray line icons. Merge central cells into four double-size tiles, each with a low-opacity pastel radial wash and a compact UI fragment. Apply an outer white fade mask so the grid dissolves into the canvas.

### Convergence diagram

**Only for:** dark flagship product pages

**Use:** Technical opening scene.

**Observed:** A green-lit central orb, concentric radar rings and dotted paths connect incoming conversation chips to organized capability lists. Mono labels orbit the center while black dominates the background.

**Transfer:** Map many inputs into one coherent outcome for the new product; keep the green mechanism language separate from the default spectrum chapter.

**Build:** Use a 370px circular radial gradient in rgba(20,224,138,0.15), thin concentric rings, one translucent conic sweep and a brighter center. Add dashed SVG paths, small green nodes and muted mono label blocks on either side; the complete diagram spreads below a centered promise.

### Output gallery and pastel process stage

**Only for:** dark showcase pages

**Use:** Gallery thumbnails and split process demonstration.

**Observed:** Output thumbnails deliberately vary in visual language: bright decks, restrained dashboards, editorial websites and practical calculators. The process stage displays layered windows on a tall blue-lavender or peach-pink card, against a near-black dot field.

**Transfer:** Let the new product's outputs have their own palettes while keeping the marketing frame consistent.

**Build:** Make a 455×683px rounded scene with overlapping radial washes over a 160deg linear gradient. Place two interface windows at different depths, with small soft shadows and a dark translucent pill caption near the bottom. Behind the card use a 1px white dot at about 0.1 alpha on a sparse repeating grid.

### Editorial office ephemera

**Only for:** editorial feature campaigns

**Use:** Feature-name opening, benefit cards and human closing collage.

**Observed:** A serif title sits above a physical software-package-like box with colorful soft graphics. Later white cards carry toy-like brains, charts and flow diagrams with yellow circular callouts. Paper notes have torn tops and folded corners. The closing collage shows a friendly office worker, a vintage computer, circular portrait backing, a blue seal and a black label.

**Transfer:** Invent a physical package, a small set of relevant toy-like diagrams and a human office collage for the new product; keep the retro tone distinct from ordinary landing pages.

**Build:** For notes, use three rectangular sheets in lemon, pink and mint, rotate each by roughly 1–3 degrees, add paper-lift shadows, a subtly jagged top SVG edge and a 29px folded-corner triangle. For the closing collage, combine one circular portrait, one device cutout and two small label shapes, keeping the person larger than the decorative seals.

### Icons

**Observed:** Marketing utility icons are small rounded line SVGs: navigation chevrons are 14px with 1.5px strokes; card icons are commonly 16px with 1.6px round strokes. Larger atlas icons remain monochrome gray while product and customer marks retain color.

**Transfer:** Choose one rounded line-icon family for controls, use muted gray by default and reserve colorful illustrated objects for product mechanisms.

## Section recipes

How recurring sections are built.

### First screen: Promise above working product

**Observed:** A 40px announcement strip sits above a 60px sticky Navigation. The 1080px-wide opening content starts after 80px of breathing space, aligned to the left edge of the navigation content. A small rounded announcement chip leads the single-line 60px headline, followed almost immediately by two lines of 22px support. The paired Primary button and Secondary button sit 32px beneath the support, with reassurance below the first. After a 64px gap, Product frame starts at about 528px down the page and occupies the full content width. Within the first 900px the visitor sees the complete text and actions plus the upper half of a populated working interface; the bottom of the interface and customer logo strip continue below the fold. Layers run from white canvas to fine gray frame to detailed application content; the promise, not decorative art, owns the top half.

**Transfer:** Use a concise broad promise and a believable working interface for the new product. If no real interface is available, design a coherent demonstration with populated content rather than substituting an empty rectangle. Pricing opens with a centered 60px promise and plan controls; dark product pages use centered 68–76px promises above technical scenes; editorial campaigns use the giant single-word serif title and a physical package.

**Avoid:** Do not turn this into a centered generic hero, a text-left/image-right split, or a screen filled by an abstract illustration before visitors see useful product detail.

**Text style:** `display` — Plus Jakarta Sans 700 · 60px/1.1 · tracking -0.035em

### Heading and support pair

**Observed:** A 48px heading and 18px muted support line sit 12px apart within the shared content stage. Centered treatments introduce broad problems or capabilities; left-aligned versions lead proof and customer stories. Light headings often grade from black to medium gray.

**Transfer:** Change alignment according to narrative function without changing the default scale.

**Text style:** `heading` — Plus Jakarta Sans 650 · 48px/1.25 · tracking -0.035em

### Sculptural chapter introduction

**Observed:** A centered 76px headline spans about 760px above two actions. A compact Soft spectrum sculpture sits well below it; a following inset 1400×800px portrait scene expands the object into a human metaphor with fine mono callouts and a warm grainy backdrop.

**Transfer:** Give the new product one tangible emblem and show it in a human context; the chapter can be placed wherever an emotional change of pace is useful.

**Text style:** `chapter-display` — Plus Jakarta Sans 700 · 76px/1.05 · tracking -0.04em

### Black mechanism chapter

**Observed:** Black chapter begins with an 80px neutral-gradient statement and a single italic emphasis, followed by muted support and compact uppercase platform captions. Prismatic horizon backs the lead; Feature cell repeats in three columns with 1px shared seams and luminous lower illustrations.

**Transfer:** Use a tonal inversion to explain the product's deeper mechanism, keeping each card focused on one useful distinction.

**Text style:** `inverse-display` — Plus Jakarta Sans 700 · 80px/1.2 · tracking -0.04em

### Tabbed solution story

**Observed:** Heading and support sit above a row of Solution tab. Solution panel then combines a large benefit statement, short replacement line and checks at left with four Workflow row items at right.

**Transfer:** Replace audience categories with the new product's most meaningful use cases; show actions rather than a list of feature names.

### Joined numerical proof

**Observed:** A left-aligned heading and short support sit above four Stat tile items. Numbers remain 34px while captions are violet mono; the large whitespace within each tile gives small substantiated claims an authoritative rhythm.

**Transfer:** Use a few comparable outcomes and their explanatory context; do not inflate all figures into hero-sized type.

**Text style:** `stat` — Plus Jakarta Sans 650 · 34px/1.2 · tracking -0.04em

### Portrait and institutional proof

**Observed:** A broad heading is paired with compact award marks, then three Portrait testimonial items. Subsequent proof uses an awards wall opposite text and a matrix of 500 small dots, 425 of them violet, opposite a second claim. A compact security strip uses grayscale certification symbols and mono captions.

**Transfer:** Separate lived customer experience, quantified adoption and institutional reassurance into visually different proof devices. If a percentage is visualized as dots, make the colored share accurate.

**Text style:** `heading` — Plus Jakarta Sans 650 · 48px/1.25 · tracking -0.035em

### Spectrum closing and complete footer

**Observed:** Spectrum conversion stage is inset 20px from the viewport, 1400×860px on desktop, with a 32px radius. A raised square emblem precedes a centered white 60px two-line statement and white action. A wide desktop application window rises from the lower edge with a smaller mobile window alongside, both in translucent shells. A small note separates this from a white five-column footer with logo, navigation, social links, trust marks and legal row.

**Transfer:** End the broad marketing story with a vivid product-backed promise and a quiet, fully resolved navigation ending. Use the new product's own emblem and working content.

**Text style:** `display` — Plus Jakarta Sans 700 · 60px/1.1 · tracking -0.035em

### Pricing comparison and reassurance

**Only for:** pricing pages

**Observed:** A centered 60px promise leads billing-period controls and a guarantee. Four Plan card columns use 16px gutters and one inverted recommendation; a full-width premium spectrum band follows. Three add-on cards have warm-spectrum headers and small glass UI fragments. A cool white savings calculator pairs selectable app tiles and a people slider with a raised cost summary. Policy explanation, narrow FAQ and a compact 1080×397px violet conversion stage precede the light footer.

**Transfer:** Help readers compare, personalize cost, resolve billing objections and then act; do not force the long broad-marketing sequence onto a pricing page.

### Process rail and finished outputs

**Only for:** dark showcase pages

**Observed:** A centered showcase promise and tabbed demo lead to three-column Gallery card collections. A split process section uses a 60px headline and thin ruled step labels at left; the active step expands supporting copy while a pastel interface composition occupies the right. Comparison rows and a large live-product window supply concrete proof.

**Transfer:** Show finished results before teaching the process, then pair each process step with a visible change to a real output.

**Text style:** `showcase-heading` — Plus Jakarta Sans 700 · 60px/1.04 · tracking -0.04em

### Before-and-after quote

**Only for:** before-and-after proof on dark showcase pages

**Observed:** Two equal columns with a 64px gap sit within 1080px. A muted 72px struck-through original value, arrow and bright 144px improved value share a baseline; the unit stays small. At right, a 26px quote is inset 32px from a 2px lavender rule, with name and role below.

**Transfer:** Use this rare oversized number treatment only for a strongly supported transformation, keeping the comparison and attribution adjacent.

**Text style:** `comparison-after` — Plus Jakarta Sans 750 · 144px/1 · tracking -0.8px

### Dark product ending

**Only for:** dark product pages

**Observed:** Ruled Question row lists are followed by a compact conversion area over Prismatic horizon. One variant centers a short finished-outcome promise and white action; another uses overlapping luminous source icons, a one-click migration promise and a warm outlined import action. Small explanatory terms then lead to the charcoal five-column footer.

**Transfer:** Choose the final conversion that removes the largest remaining barrier: starting a result or bringing existing work across. Keep the dark ending complete rather than stopping after FAQs.

### Editorial package story

**Only for:** editorial feature campaigns

**Observed:** A 240px serif feature name and compact black action lead physical package artwork. An isolated 36.7px mono explanation receives 220px vertical padding. Serif headings introduce a wide video, three numbered instruction cards, a perspective carousel of white feature cards and three tilted paper notes. The final centered human office collage is followed by a narrow 52px two-line serif invitation, support and paired actions; this version ends on the invitation rather than adding the dense global footer.

**Transfer:** Use this as a deliberately different campaign language for a teachable new capability. Preserve the package-to-explanation-to-human-payoff logic without importing its exact subject.

**Text style:** `editorial-title` — EB Garamond 400 · 240px/0.72

## Page flow

**Storyline:** promise → working product or tangible metaphor → capability explanation → concrete outcomes → customer and quantified proof → reassurance → conversion payoff

### Broad platform marketing

1. **promise** — Left-aligned promise above a large working interface and a quiet customer-logo line.
2. **problem framing** — Centered statement above a physical tangle diagram.
3. **capability overview** — Faded product atlas and a sculptural human-centered chapter.
4. **product mechanism** — An inset black chapter with spectrum light and joined feature cells.
5. **use cases** — Tabbed audience stories paired with concrete workflow rows.
6. **proof** — Joined metric tiles, portrait testimonials, awards, a dot matrix and security strip.
7. **closing call** — Large spectrum stage with application windows, followed by a complete light footer.

**Transfer:** Choose the most relevant mechanisms and proof forms for the new product; the light-stage, dark-depth and vivid-payoff contrast is more important than repeating every section.

### Pricing and purchase confidence

1. **promise** — Centered value headline, billing toggle and guarantee.
2. **pricing** — Four aligned plans, one inverted recommendation and a full-width premium band.
3. **expansion options** — Three add-on cards with gradient-backed examples.
4. **personalized proof** — Interactive replacement-cost calculator.
5. **objection handling** — Policy explanation and narrow FAQ list.
6. **closing call** — Compact violet conversion panel and full light footer.

**Transfer:** Prioritize comparable information and billing clarity, using spectrum color mainly for expansion and premium value.

### Flagship technical product landing

1. **promise** — Centered bold promise above a green convergence scene.
2. **quantified proof** — A four-cell benchmark strip.
3. **demonstration** — Role selector alongside a working conversation scene.
4. **capability chapters** — Ruled dark cells and alternating text with output artwork.
5. **social proof** — Large isolated customer quotation revealed across a spacious black stage.
6. **reassurance** — Device story, security mechanisms and FAQs.
7. **closing call** — Migration prompt over luminous art, explanatory terms and a charcoal footer.

**Transfer:** Use the dark variant for deep product education and technical confidence, not as a blanket replacement for the light default.

### Output-led capability showcase

1. **promise** — Centered product-output promise, demo tabs and a glowing prompt panel.
2. **finished-result proof** — Several categorized three-column output galleries.
3. **process explanation** — Split step rail with changing pastel-backed interface scenes.
4. **comparison** — A ruled capability table with lavender checks.
5. **live demonstration** — Three short benefits over a large working dashboard.
6. **quantified proof** — Oversized before-and-after value next to a ruled quotation.
7. **objection handling** — Bordered FAQ list.
8. **closing call** — Short finished-outcome promise, white action and dark footer.

**Transfer:** Let finished examples do the selling before explaining mechanics, with consistent shells around varied output aesthetics.

### Editorial feature campaign

1. **promise** — Giant serif feature name, physical product package and simple trial action.
2. **definition** — Large centered typewriter-style explanation.
3. **demonstration** — Wide explanatory video.
4. **process explanation** — Three numbered instruction cards.
5. **use cases** — Perspective carousel of illustrated white cards.
6. **benefits** — Three tilted, colored paper notes.
7. **closing call** — Retro human office collage, narrow serif invitation and paired actions with no dense footer.

**Transfer:** Use tactile office objects and plainspoken instruction to humanize a new capability, while keeping the serif/mono campaign scope explicit.

## Writing

Confident, energetic and conversational. Broad claims are delivered in short memorable phrases, then grounded in recognizable work, finished outputs or attributed proof.

**Do not copy:** Do not reuse the brand name, product names, logos, proprietary illustrations, customer identities, testimonials, benchmark results, awards, savings figures, guarantees or pricing claims. Source examples demonstrate voice and structure only; replace them with verified facts and original assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team. The product is an active coworker that finds, builds, learns or completes things; company voice uses we for commitments and policies.
- **Rhythm:** Headlines usually contain one direct thought in 5–12 words; rhythmic three-part statements and sentence fragments are common. Support is one or two short sentences, while UI labels and calls stay compact.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a unified outcome in plain, confident language. | 6–12 words | “One Workspace built to think and work” |
| Capability headline | Contrast the old way with a finished useful result. | 6–12 words | “Personalized software your team will want to use”<br>“The only AI that actually knows your work” |
| Rhythmic value statement | Use repeated short clauses with concrete verbs. | Three short clauses | “Save time. Save money. Kill busy work.” |
| Supporting line | Describe the mechanism in terms of familiar work and what happens next. | One or two sentences | “Already plugged into your team, your tools, and your tasks.”<br>“Each one started as a single request in [Brand]. Open one to try it, then make your own copy.” |
| Primary action | Direct verb plus an immediate low-friction next step. | 2–5 words | “Get Started. It's FREE”<br>“Try Skills free” |
| Closing invitation | Make the old friction feel unnecessary, without adding a new technical claim. | 7–12 words | “You’ve done this the hard way long enough.”<br>“What used to take hours now takes a sentence” |

**Words and phrasing to use:** your team; work; build; ready to use; just ask; every time; one; free to start; actually; finished

**Avoid:** synergistic; paradigm-shifting; leverage our cutting-edge ecosystem; disruptive innovation; vague superlatives without proof

**Rules:**

- Lead with the result, then explain the mechanism in concrete work language.
- Use strong verbs for finished work instead of long feature inventories in prose.
- Balance confident assertions with visible examples and attribution where claims depend on research.
- Keep technical naming in labels and diagrams; keep the main sentence understandable without those labels.
- Use a brief reassurance line beneath an action when there is a real friction-reducing fact to state.

## Do's and Don'ts

### Do

- Keep the default hero left-aligned in a 1080px content area above the working product.
- Pair the 60px/1.1 headline with 22px/28px support rather than using the same sans recipe for both.
- Use 80px vertical padding for ordinary chapters and preserve larger 120px dark-showcase intervals where appropriate.
- Make white cards and panels legible through #e8e8e8 edges and faint shadows, not heavy outlines.
- Keep black feature grids joined by 1px #2a2a2a seams.
- Include tangible product artwork and a prismatic light-backed demonstration even when creating those assets from simple SVG shapes.
- Use 15px corners on the opening actions and 12px on ordinary section calls.
- Give the closing conversion a complete product-backed stage and resolve the page ending deliberately.

### Don't

- Do not make every button a full pill; 15px, 12px and 8px rounded rectangles carry the action hierarchy.
- Do not replace Plus Jakarta Sans headlines with the body sans or use broad positive headline tracking.
- Do not spread saturated gradient fills over ordinary body sections; white space and black space carry most of the story.
- Do not round every black capability cell into a detached floating card; preserve shared seams.
- Do not scale every metric to 144px; the ordinary joined proof scale is 34px and the giant comparison belongs to its scoped treatment.
- Do not use the editorial serif and paper-note palette on an ordinary platform page.
- Do not turn supporting copy on black into near-invisible charcoal; use #b4b4b4 for readable descriptions.
- Do not repeat one abstract decorative blob in all feature cells; each miniature scene needs a distinct mechanism.

## Motion and responsive

### Motion

**Observed:**

- Declared opening-action background-color transition: 0.2s.
- Declared output-gallery shell transform transition: 0.16s cubic-bezier(0.23, 1, 0.32, 1).
- Declared paper-note transitions: transform 0.3s and box-shadow 0.3s.
- Declared diagram tickers include 30s linear infinite motion; voice bars use 1.3s ease-in-out. Process demonstrations change active steps and corresponding output scenes.

**Transfer:**

- Keep spectrum light behind stable legible text while changing small interface fragments or process steps.
- Use a visible active step and corresponding demonstration rather than animating unrelated objects throughout the page.

**Unknown:**

- Complete entrance choreography, reduced-motion behavior and timing of canvas scenes are not specified.

### Responsive

**Observed:**

- Desktop containers use 20px inner gutters, with declared desktop gutter tokens of 40px and mobile gutter tokens of 20px.
- Dark flagship titles use clamp(48px, 20px + 4.6667vw, 76px); showcase titles use clamp(2.5rem, 5vw, 4.25rem).
- Styles include breakpoints around 640px, 768px, 820–821px, 900px, 1000px and 1120px; exact component behavior differs.

**Transfer:**

- On narrow screens, preserve the promise-above-product hierarchy and the 20px edge gutter; let headline copy wrap before shrinking interface detail into illegibility.
- Adapt the prismatic horizon to the bottom of a stacked composition, retaining black space behind text.
- Stack joined proof and feature cells with their seam language intact; retain the editorial carousel as a focused card presentation rather than squeezing every card into one row.

**Unknown:**

- Mobile layouts, precise column-collapse thresholds and touch interaction behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
