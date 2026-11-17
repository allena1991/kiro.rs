# Privy — luminous product machinery

## Overview

An airy, predominantly white technology style that makes complex infrastructure feel tangible and approachable. Regular-weight grotesk headlines and restrained interface text sit beside luminous violet product scenes, pastel technical illustrations and sharply colored customer stories. It suits developer platforms and sophisticated business products, balancing spacious compositions with compact controls and unusually detailed proof.

### Essentials

- Headlines turn a promise into a two-tone sentence: regular-weight grotesk at 58px/64px with -0.03em tracking, near-black main clause and #70707d concluding phrase; section headings repeat the device at 42px/48px.
- The opening is a product stage, not a centered slogan: a 677px-tall pale band divides roughly equally between left-aligned copy and a violet-backed interface scene that reaches the right edge; a 72px white navigation bar sits above it.
- Conversion controls stay surprisingly small beside the art: 36px-high pills, 100px radius, Inter 14px/14px at 500, dark primary and white outlined secondary separated by 10px.
- Color belongs to demonstrations and proof rather than chrome: white and #f8f9fc carry the ordinary page, violet occupies roughly half the opening, and vivid lime, lavender, mint and pink are confined to story panels. Include a bright proof panel with a real outcome, not a page-wide accent wash.
- Technical ideas become luminous physical objects: stage crisp white interfaces or floating layered planes on lavender/violet fields with fine grain, soft colored light and restrained isometric grids. Every new landing page needs this material demonstration; use a simplified purpose-built interface and three floating planes when no polished product media exists.
- Proof and endings have their own visual cadence: use unboxed 52px/60px statistics, a row of 286px × 420px color-and-image stories, faint patterned band edges, and a centered two-line 58px/64px closing promise before a spacious five-column footer. These are signature devices, not a fixed section sequence.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Luminous violet | `#6042f5` | `--color-violet` | accent, background | The saturated center of product-media lighting; vary softly across the image rather than using it for marketing buttons. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale lavender stage | `#eeebff` | `--color-lavender` | background, surface | Technical illustration backdrops and the light portions of violet scenes. |
| Electric yellow lime | `#e3ff38` | `--color-story-lime` | surface | One bright customer-outcome panel in a colorful proof row. |
| Story lilac | `#bea7f0` | `--color-story-lilac` | surface | A second story header, paired with natural photography. |
| Story mint | `#99fbe1` | `--color-story-mint` | surface | A contrasting story header, paired with darker interface photography. |
| Story pink | `#f4a6cf` | `--color-story-pink` | surface | A contrasting story header; also a family of light colors in conceptual artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main page canvas, interface cards, secondary controls and inverse text. |
| Cool porcelain | `#f8f9fc` | `--color-band` | background, surface | Opening copy field, proof and closing bands, small benefit cards. |
| Pale gray rule | `#f0f0f0` | `--color-rule` | border | Visible result of black at 6% on white; use rgba(0,0,0,0.06) for separators. |
| Neutral gray | `#737373` | `--color-caption` | text | Supporting captions and case-study explanation. |
| Slate gray | `#70707d` | `--color-muted` | text | Muted headline clauses, labels and footer links. |
| Graphite copy | `#2e2e3d` | `--color-body` | text | Small descriptive paragraphs. |
| Navigation ink | `#111827` | `--color-nav` | text | Navigation labels. |
| Charcoal | `#111117` | `--color-charcoal` | text, background, action | Default primary button and card titles; also the canvas of the dark technical variant. |
| Almost-black ink | `#010110` | `--color-ink` | text, action | Primary headings and dark controls outside the default charcoal button. |
| Pure black | `#000000` | `--color-black` | text | Opening support line and monochrome pictograms. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Lavender edge | `#e2e3f0` | `--color-panel-edge` | border | Hairline outlines on plan and included-feature panels. |
| technical infrastructure pages | Raised charcoal | `#22222a` | `--color-dark-card` | surface | Stat tiles within dark technical chapters. |
| technical infrastructure pages | Periwinkle blue | `#c4d4f6` | `--color-closing-blue` | background | Full-width concluding statement after a dark technical chapter. |
| pricing pages | Blue-black | `#020713` | `--color-pricing-night` | background | Comparison matrix canvas. |
| pricing pages | Blue slate | `#1a2230` | `--color-matrix-group` | surface | Matrix category bars. |
| pricing pages | Muted violet gray | `#64668b` | `--color-pricing-copy` | text | Plan support copy. |
| culture and recruitment pages | Indigo ink | `#110f2a` | `--color-culture-ink` | text | Culture subheadings and role labels. |
| culture and recruitment pages | Blue graphite | `#3e3e5d` | `--color-culture-copy` | text | Culture explanations and eyebrow labels. |
| recruitment and pricing pages | Pale slate label | `#9498b8` | `--color-secondary-label` | text | Role locations and muted comparison labels. |

## Typography

- **FFF Acid Grotesk** — Default marketing headlines, statistics and closing statements. A regular grotesk with rounded bowls and a slightly idiosyncratic, friendly construction; tightly fitted without becoming heavy. If unavailable, use **DM Sans**. Use 400; preserve negative tracking and test line wraps. Font stack: "FFF Acid Grotesk", "DM Sans", Arial, sans-serif.
- **Inter** — Body text, navigation, buttons, captions and most card titles. Neutral, compact interface sans; light paragraphs contrast with medium controls. Font stack: "Inter", Arial, sans-serif.
- **ABC Favorit** (only for technical infrastructure and pricing pages, plus FAQ display headings) — Larger technical promises, dark section titles, pricing headings and technical metrics. Direct neo-grotesk with a denser, tighter display silhouette than the default marketing face. If unavailable, use **Inter**. Use 400; retain the unusually tight -0.06em hero tracking. Font stack: "ABC Favorit", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | FFF Acid Grotesk | 400 | 58px | 64px | -0.03em | Default opening and two-line closing promise. |
| stat | FFF Acid Grotesk | 400 | 52px | 60px | -0.03em | Unboxed headline metrics in a horizontal proof band. |
| heading | FFF Acid Grotesk | 400 | 42px | 48px | -0.03em | Section leads; may split near-black and gray clauses. |
| feature-label | FFF Acid Grotesk | 400 | 26px | 32px | -0.01em | Vertical trust-selector titles. |
| card-title | Inter | 400 | 22px | 28px | -0.03em | Capability tile heading. |
| lead | Inter | 400 | 20px | 1.5 | normal | Default hero and closing support sentences. |
| benefit-title | Inter | 500 | 20px | 28px | -0.02em | Benefit or compact capability card titles. |
| story-title | Inter | 400 | 18px | 24px | -0.03em | Customer-outcome titles within colored story cards. |
| faq-question | Inter | 600 | 18px | 28px | normal | FAQ questions. |
| faq-answer | Inter | 400 | 16px | 1.75 | normal | Detailed FAQ explanations. |
| card-copy | Inter | 300 | 14px | 20px | normal | Compact explanatory text in capability and benefit cards. |
| button | Inter | 500 | 14px | 1 | normal | Pill actions and arrow text links. |
| navigation | Inter | 500 | 14px | 20px | normal | Top navigation labels. |
| footer-link | Inter | 400 | 14px | 20px | normal | Secondary navigation and footer links. |
| footer-heading | Inter | 500 | 14px | 1.5 | normal | Footer group titles. |
| eyebrow | Inter | 600 | 12px | 1.2 | 0.1em, uppercase | Short capability and culture chapter labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical infrastructure and pricing pages | technical-display | ABC Favorit | 400 | 78px | 1 | -0.06em | Technical opening promise or centered pricing headline. |
| technical infrastructure and pricing pages, plus FAQ introductions | technical-heading | ABC Favorit | 400 | 56px | 58px | -0.001em | Technical feature headings, plan titles and FAQ display leads. |
| technical infrastructure metric cards | technical-stat | ABC Favorit | 400 | 52px | 36px | -0.03em | Large numbers sharing a baseline with smaller units; reserve enough visual height to avoid clipping. |
| technical infrastructure closing bands | technical-close | ABC Favorit | 400 | 52px | 60px | -0.03em | Centered reassurance on a periwinkle field. |
| pricing pages | plan-copy | Inter | 400 | 18px | 30px | normal | Plan descriptions. |

**Notes:**

- Keep display weights at 400; scale and tight spacing, not boldness, create the hierarchy. The default headline and section lead both track at -0.03em.
- Use gray as part of a sentence, not a separate eyebrow. A muted clause may precede or follow the black clause according to the reading order.
- Technical display type is a scoped alternate system: its 78px hero is much tighter than its nearly neutral 56px heading. Do not average the two tracking values.
- Small product-interface lettering remains subordinate to the marketing hierarchy; do not promote demo text into the page type scale.

## Layout

**Density:** Airy compositions with compact controls: broad media and section intervals surround short blocks of relatively small text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer link gaps and title-to-small-caption spacing. |
| 10px | Paired action gap and capability title-to-copy gap. |
| 12px | Compact benefit card content gaps and footer heading-to-list gap. |
| 20px | Headline-to-support gap and compact card padding. |
| 24px | Feature-card gutters, FAQ vertical padding and included-feature card padding. |
| 32px | Capability grid gutters, major action spacing and tile side padding. |
| 40px | Section heading-to-content separation and pricing-panel side padding. |
| 60px | Common section top and bottom padding. |
| 80px | Footer vertical padding and broad media-to-next-block breathing room. |
| 100px | Dark technical chapter separation and trust illustration-to-text gap. |
| 120px | Deep bottom padding for technical closing bands. |

### Containers and grids

- **Main container**: max width 1200px · side padding 40px. Centered default content; at 1440px the content edges are 120px from the window. Full-width opening and closing bands escape this container.
- **Capability mosaic**: max width 1200px · 3 columns · gap 32px. Wide 784px tile beside narrow 384px tile, with the proportions reversed in a later row; media tile height is 450px.
- **Story row**: max width 1200px · 4 columns · gap 18px. Four equally sized 286px-wide, 420px-tall story cards.
- **FAQ column**: max width 800px. Centered narrow question-and-answer list within a broader page.
- **Footer grid**: max width 1200px · 5 columns · gap 42px. Four directory columns followed by a right-aligned identity column; identity and social links are vertically separated.
- **Product detail chapters** (only for detailed product pages): max width 1040px · gap 64px · side padding 200px. Alternate a roughly 476px text area and 500px square visual inside 60px vertical section padding.
- **Plan grid** (only for pricing pages): max width 1130px · 2 columns · gap 24px · side padding 155px. Equal 553px plan panels; comparison and included-feature sections align to the same content width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Pill controls | 100px |
|  | Media tiles | 8px |
|  | Benefit cards | 12px |
| pricing pages | Plan panels | 32px |
| detailed product pages | Small metric tiles | 4.5px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Primary page background.

**CSS:** `background: #ffffff`

**Observed:** Most sections are flat and borderless; depth belongs to the artwork rather than surrounding containers.

**Transfer:** Separate narrative blocks with space and occasional pale bands.

#### Porcelain band · level 0

**Use:** Opening copy area, proof section and default closing call.

**CSS:** `background: #f8f9fc`

**Observed:** Full-bleed pale cool neutral; faint patterned transitions can soften its top and bottom edges.

**Transfer:** Keep text dark and let colored media provide the stronger contrast.

#### Lavender media stage · level 1

**Use:** Technical illustrations and capability imagery.

**CSS:** `background: #eeebff; border-radius: 8px; overflow: hidden`

**Observed:** Light lavender fields support colored objects, interface panels and subtle line grids.

**Transfer:** Keep the backing low contrast so the object remains legible.

#### Benefit surface · level 1

**Use:** Compact icon-led explanations.

**CSS:** `background: #f8f9fc; border-radius: 12px; padding: 20px; box-shadow: none`

**Observed:** No visible lift or thick outline.

**Transfer:** Use small text and icon hierarchy rather than heavy borders.

#### Dark technical field · level 0

**Only for:** technical infrastructure pages

**Use:** Extended run of alternating capability chapters and performance proof.

**CSS:** `background: #111117; color: #ffffff; padding: 100px 0 120px`

**Observed:** Edge-only cross patterns leave an uninterrupted dark center; bright image windows punctuate the field.

**Transfer:** Use a contiguous chapter environment rather than alternating black and white every row.

#### Dark metric surface · level 1

**Only for:** technical infrastructure pages

**Use:** Performance tiles.

**CSS:** `background: #22222a; border-radius: 8px; padding: 36px`

**Observed:** A small tonal step above the dark canvas; not a floating shadow card.

**Transfer:** Keep numbers white and supporting labels at white 70%.

#### Periwinkle conclusion · level 0

**Only for:** technical infrastructure pages

**Use:** Reassurance after the dark chapters.

**CSS:** `background: #c4d4f6; padding: 80px 0 120px`

**Observed:** A centered statement with one dark pill and small decorative media above.

**Transfer:** Use it as a calm release from a dense technical story.

#### Included-feature glass · level 1

**Only for:** pricing pages

**Use:** Included-feature cards over a pale technical pattern.

**CSS:** `background: rgba(255,255,255,0.75); border: 1px solid #e2e3f0; border-radius: 12px; backdrop-filter: blur(2px); padding: 24px`

**Observed:** The translucency is subtle and nearly white, not high-contrast frosted glass.

**Transfer:** Retain the hairline edge and let only faint pattern detail show through.

#### Comparison field · level 0

**Only for:** pricing pages

**Use:** Dense comparison matrix.

**CSS:** `background: #020713; padding: 80px 155px`

**Observed:** A low-opacity dark inner panel and thin row separators carry a long matrix; blue-slate category bars group rows.

**Transfer:** Place a broad label column beside two narrower plan columns.

## Components

### Navigation

**Use:** Shared top-level wayfinding.

**CSS:** `height: 72px; padding: 16px 24px; background: #ffffff; display: flex; align-items: center; justify-content: space-between; border-bottom: 1px solid rgba(0,0,0,0.06)`

**Text style:** `navigation` — Inter 500 · 14px/20px

**Observed:** Identity at left, compact menu labels and small chevrons in the center, documentation and outlined login at right. Individual menu actions use 8px 12px padding.

**Transfer:** Use a short product taxonomy rather than a long promotional menu.

### Primary button

**Use:** Main conversion.

**CSS:** `background: #111117; color: #ffffff; border-radius: 100px; height: 36px; padding: 16px 20px; display: flex; align-items: center; justify-content: center; flex-shrink: 0`

**Text style:** `button` — Inter 500 · 14px/1

**Observed:** Compact text-only pill. The technical, culture and detailed-product variants use almost-black ink instead of charcoal. Pricing-panel actions stretch to 473px wide and 48px high.

**Transfer:** Preserve the compact visual height and prevent flex padding from enlarging it.

### Secondary button

**Use:** Sales, documentation and alternate conversion.

**CSS:** `background: #ffffff; color: #010110; border: 1px solid #010110; border-radius: 100px; height: 36px; padding: 16px 20px; display: flex; align-items: center; justify-content: center; flex-shrink: 0`

**Text style:** `button` — Inter 500 · 14px/1

**Observed:** A white pill with a thin dark outline; paired 10px from the primary. Some documentation links use a white fill with no prominent outline.

**Transfer:** Maintain the visual outline even when the surrounding band is almost white.

### Arrow text link

**Use:** Secondary exploration beside section headings or below feature lists.

**CSS:** `color: #010110; padding: 16px 28px 16px 0; height: 36px; display: flex; align-items: center; gap: 8px`

**Text style:** `button` — Inter 500 · 14px/1

**Observed:** Unfilled label with a 16px right arrow, often aligned to the far side of a heading row. In dark chapters it becomes white and uses 16px label text.

**Transfer:** Keep the arrow subordinate to the label, not in a colored circle.

### Capability tile

**Use:** Asymmetric product benefit mosaic.

**CSS:** `border-radius: 8px; padding: 24px 32px 32px; height: 450px; overflow: hidden; display: flex; flex-direction: column; gap: 10px`

**Text style:** `card-title` — Inter 400 · 22px/28px · tracking -0.03em

**Observed:** Title and short card-copy sit over a full-card illustration, occupying its upper left. Wide and narrow tiles share a height, but their artwork scales and framing differ.

**Transfer:** Reserve a calm text zone in each image and let the main graphic grow beneath it.

### Color story card

**Use:** Customer proof with an outcome and recognizable context.

**CSS:** `width: 286px; height: 420px; border-radius: 8px; padding: 82px 20px 32px; overflow: hidden; border: 1px solid rgba(47,43,67,0.1)`

**Text style:** `story-title` — Inter 400 · 18px/24px · tracking -0.03em

**Observed:** A dark customer mark occupies the top, an outcome paragraph follows, and photography or interface context fills the lower half. Lime, lilac, mint and pink headers differ across the row; a tiny raster-like seam bridges color and photograph.

**Transfer:** Keep proof content short enough to leave the image substantial.

### Benefit card

**Use:** Compact four-up explanation of capabilities or benefits.

**CSS:** `background: #f8f9fc; border-radius: 12px; padding: 20px; display: flex; flex-direction: column; gap: 12px`

**Text style:** `benefit-title` — Inter 500 · 20px/28px · tracking -0.02em

**Observed:** A 24px monochrome icon, a short medium title and light card-copy. Culture cards are 292px × 226px; detailed-product cards are 242px × 224px.

**Transfer:** Use one concrete benefit per card, not a miniature section.

### Metric group

**Use:** Quantified proof before or beside stories.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 6px; padding: 24px`

**Text style:** `stat` — FFF Acid Grotesk 400 · 52px/60px · tracking -0.03em

**Observed:** Default metrics are centered, unboxed and arranged four across, with a small gray explanatory label. Dark technical variants use Dark metric surface, left alignment and technical-stat; smaller detailed-product variants use pale 253px × 129px tiles.

**Transfer:** Pair every number with its unit and meaning; use only substantiated metrics.

### Trust selector

**Use:** Security and developer-benefit explanation beside a conceptual illustration.

**CSS:** `display: flex; flex-direction: column; gap: 42px; color: #70707d`

**Text style:** `feature-label` — FFF Acid Grotesk 400 · 26px/32px · tracking -0.01em

**Observed:** Four stacked feature labels beside a 550px × 601px illustration. The active title is charcoal and reveals one short gray support line; inactive labels remain muted. The heading above combines gray and ink clauses.

**Transfer:** Use a clear active state without giving every label an enclosing panel.

### FAQ item

**Use:** Detailed objection handling in an 800px column.

**CSS:** `background: #ffffff; padding: 24px 0; display: flex; flex-direction: column; gap: 16px; border-bottom: 1px solid rgba(0,0,0,0.06)`

**Text style:** `faq-question` — Inter 600 · 18px/28px

**Observed:** Question and a small minus sign share the top row; the visible answer uses faq-answer beneath. Multiple answers are open at the same time.

**Transfer:** Allow substantive answers and independent expanded states instead of forcing a single-open accordion.

### Directory footer

**Use:** Shared ending on all page types.

**CSS:** `background: #ffffff; padding: 80px 0; display: grid; grid-template-columns: repeat(5, minmax(1px, 1fr)); gap: 42px; max-width: 1200px`

**Text style:** `footer-link` — Inter 400 · 14px/20px

**Observed:** Four link directories with footer-heading labels and 8px link gaps, plus a right-aligned identity column. A strong wordmark sits above a compact two-line principle; social icons and a small copyright sit near the bottom. The footer is 581px tall at desktop.

**Transfer:** Preserve the asymmetry between dense directories and a spacious identity block.

### Plan panel

**Only for:** pricing pages

**Use:** Two-tier commercial choice.

**CSS:** `border: 1px solid #e2e3f0; border-radius: 32px; padding: 40px 40px 14px; width: 553px; display: flex; flex-direction: column; gap: 34px`

**Text style:** `technical-heading` — ABC Favorit 400 · 56px/58px · tracking -0.001em

**Observed:** Title, muted description, usage tiers or a short check list, then a full-width action anchored near the bottom. The self-serve plan uses a dark button and the enterprise plan an outlined one; no oversized price dominates.

**Transfer:** Keep two options visually balanced, using utility rather than a bright recommended badge to differentiate them.

## Imagery and graphics

### Luminous interface stage

**Use:** Main product demonstration and large capability media.

**Observed:** White browser and mobile surfaces float over a saturated violet-to-lavender luminous field with very fine grain. The opening scene is 745px × 677px, with the browser extending beyond the right boundary and a phone overlapping it in front. Interface details stay crisp while the backdrop is softly uneven.

**Transfer:** Use the new product's core workflow in a clean white interface. Minimum version: one desktop panel and one narrow foreground panel showing a real task, on a carefully lit violet background.

**Build:** Layer a lavender base with broad violet radial gradients at the upper left and lower center, plus translucent white ellipses blurred about 60px. Add a very low-opacity SVG turbulence layer. Place a large white UI panel partly outside the right edge and a narrower foreground panel over its left side; give the objects pale translucent rim frames rather than heavy drop shadows.

### Floating technical planes

**Use:** Trust and architecture illustrations, plus conceptual capability tiles.

**Observed:** A sparse isometric line grid supports stacked square planes: matte white below, glowing pink and violet above. Objects float with visible space between layers, soft shadows inside the artwork, and cool lavender surroundings; another capability image uses a fine point-cloud globe with pink-violet arcs.

**Transfer:** Represent the new product's architecture as a small number of layered objects, not generic glossy spheres. The minimum acceptable image is three separated planes over a subtle grid.

**Build:** Create three SVG quadrilaterals using a consistent isometric projection, each about 230px wide within a 550px illustration. Separate them vertically by about 36px; fill the lowest white, the middle with a pink-to-violet gradient, and the top with lavender and violet light. Draw a 1px diagonal lattice beneath at low opacity, then add a soft elliptical shadow under the stack and fine grain over colored planes. For a network equivalent, distribute small points on an elliptical globe and connect only a few long arcs.

### Patterned band edges

**Use:** Signature transitions around pale proof and closing bands.

**Observed:** Very faint repetitive line and cross-like marks fade in along horizontal boundaries. The pale band remains visually flat; pattern is detail at the edge, not a dense wallpaper.

**Transfer:** Include the patterned seam around a proof or closing region; it supplies technical character without competing with the content.

**Build:** Tile an SVG of four short diagonal 1px strokes around a small empty center on a roughly 20px square. Render with ink at very low alpha and apply a vertical mask over a strip about 78px tall so the pattern dissolves into the adjacent field.

### Bright proof collages

**Use:** The color-and-image portion of customer story cards.

**Observed:** The upper half uses a vivid flat fill and dark identity mark; the lower half varies between a natural-light worker portrait, a close-up interface, a laptop with a dark trading screen and urban brand photography. Images are tightly framed within the same rounded card, not detached thumbnails.

**Transfer:** Mix human and product context across the proof row. Use real, relevant subject matter with equally strong framing rather than repeating the same dashboard four times.

**Build:** Divide a clipped 286px × 420px card into an approximately 190px colored header and a lower cover image. Add a narrow 10px halftone seam with repeated translucent vertical and horizontal marks at their boundary; align text in a 20px inset.

### Dark cross-field

**Only for:** technical infrastructure and comparison sections

**Use:** Ambient technical detail at the edges of dark chapters.

**Observed:** Tiny gray cross patterns accumulate in corner and edge patches, with occasional bright circular nodes and short rays. The central reading area stays almost solid dark.

**Transfer:** Use the field to connect multiple technical chapters without adding new boxes around their text.

**Build:** Reuse the four-stroke SVG tile at roughly 24px intervals in two edge strips, with white at low alpha. Mask it into irregular fading corner patches. Add a few 6px white or violet nodes with short radial dashes; keep them outside the text columns.

### Culture photography

**Only for:** culture and recruitment pages

**Use:** Opening banner and three editorial culture stories.

**Observed:** A broad office photograph shows a colorful working environment with posters, plants and people; smaller stories show candid work in sunlit communal spaces. Photos retain natural greens, warm architecture and real everyday clutter, without a violet duotone.

**Transfer:** Use documentary photography of people actually working; retain the setting and environment instead of isolating posed headshots.

### Grainy culture conclusion

**Only for:** culture and recruitment pages

**Use:** Full-width recruiting close.

**Observed:** A 380px-tall field of pale pink, blue and lavender grain carries a centered short heading and a pair of small pills. A diagonal blue haze runs upward through the otherwise very light field.

**Transfer:** Use a warm, inviting atmospheric close after structured recruitment information.

**Build:** Start from white, layer broad pale-pink and periwinkle radial gradients and a blurred diagonal blue ellipse rising from lower left to upper right. Overlay fine monochrome SVG turbulence at low opacity; keep the center light enough for indigo text.

### Icons

**Observed:** Small monochrome functional glyphs, visually mostly outline even where the SVG is a filled path. Benefit icons are 24px; arrow links use 16px arrows; some technical standalone icons are 22px with 2px round strokes. Bullets and check marks are small and restrained.

**Transfer:** Choose simple recognizable line-like icons with consistent visual weight; keep multicolor marks inside product interfaces or customer imagery, not the marketing controls.

## Section recipes

How recurring sections are built.

### First screen: Split product stage opening

**Observed:** A 72px white Navigation sits above a 677px Porcelain band. Left copy occupies a little under half the width with 60px side inset; the three-line display promise uses ink for the first two lines and muted gray for its last phrase. A 20px gap leads to a two-line lead, then 34px to Primary button and Secondary button. The right half is Luminous interface stage, a 745px-wide object field reaching the right edge with a foreground phone and partially cut-off browser. Layers run from pale canvas to violet light to browser to phone; text never overlaps the scene. Within the first 900px the entire headline, support, actions and main scene are visible, followed by a short monochrome customer-logo strip; the next heading starts below the fold.

**Transfer:** Use an equally specific task scene for a different product, with a plain UI mockup and luminous backing if richer art is unavailable. Detailed product pages can instead begin with a centered 1040px × 394px media banner above the same display treatment; technical pages use technical-display beside a code or control panel; pricing and culture openings center their promise.

**Avoid:** Do not turn the default into a centered all-text hero, place the headline over violet art, or shrink the right-hand object into a small thumbnail.

**Text style:** `display` — FFF Acid Grotesk 400 · 58px/64px · tracking -0.03em

### Two-tone heading and mosaic

**Observed:** A left-aligned heading spans about 960px within Main container; its final phrase is gray. After 40px, Capability mosaic alternates wide and narrow Capability tiles with 32px gutters. The art fills each tile while its title and explanation sit near the top.

**Transfer:** Use different tile proportions to reflect different capabilities rather than giving every feature the same small icon card.

**Text style:** `heading` — FFF Acid Grotesk 400 · 42px/48px · tracking -0.03em

### Metrics and color proof

**Observed:** Porcelain band combines four unboxed Metric groups, a two-tone heading with Arrow text link aligned opposite, and Story row beneath. Four Color story cards share one consistent frame while their color and subject change. Patterned band edges provide a faint transition.

**Transfer:** Use the strongest measurable outcomes and distinct customer contexts; the proof row can stand apart from the numeric band.

**Text style:** `stat` — FFF Acid Grotesk 400 · 52px/60px · tracking -0.03em

### Conceptual trust split

**Observed:** A 550px-wide technical illustration sits beside Trust selector with a 100px column gap. The text column starts with a two-tone 42px heading, then a 72px interval before stacked labels; only one label displays its support sentence.

**Transfer:** Use the conceptual object to explain the active trust principle, keeping the illustration and state visually linked.

**Text style:** `heading` — FFF Acid Grotesk 400 · 42px/48px · tracking -0.03em

### Default closing promise

**Observed:** A 568px Porcelain band centers a two-line display promise: ink first line and gray second. A short lead follows after 20px, paired pills after 32px; Patterned band edges frame the transition into Directory footer.

**Transfer:** End on a concrete time-to-value or ease-of-adoption promise with a self-serve and a conversational path, without requiring the same wording or section order.

**Text style:** `display` — FFF Acid Grotesk 400 · 58px/64px · tracking -0.03em

### Alternating product chapters

**Only for:** detailed product pages

**Observed:** Each chapter uses 60px top and bottom padding, a 500px square luminous illustration and about 476px of text, alternating sides. Eyebrow, heading, short paragraph, compact bullet list and Arrow text link follow a consistent hierarchy; sections stay white until a combined pale integration-and-proof band.

**Transfer:** Describe a workflow in distinct chapters, alternating artwork to avoid a monotonous list.

**Text style:** `heading` — FFF Acid Grotesk 400 · 42px/48px · tracking -0.03em

### Dark infrastructure narrative

**Only for:** technical infrastructure pages

**Observed:** After a white split opening, Dark technical field contains alternating image-and-copy rows separated by 100px. Bright interface windows about 500px wide sit against the black field; technical-heading, larger support text, small icon lists and white arrow links occupy the other side. Performance tiles and a dark customer-story carousel continue the environment. Periwinkle conclusion then resets the tone before Directory footer.

**Transfer:** Use the variant for lower-level or security-heavy products; emphasize real controls and reliability rather than making the whole brand dark.

**Text style:** `technical-heading` — ABC Favorit 400 · 56px/58px · tracking -0.001em

### Commercial choice and comparison

**Only for:** pricing pages

**Observed:** A centered technical-display promise and support precede two Plan panels. Monochrome customer marks separate the plans from six Included-feature glass cards in a three-column grid. Comparison field carries grouped rows and small circular checks; a narrow FAQ column returns to white, followed by a centered 56px closing line, paired pills and Directory footer.

**Transfer:** Use the same sequence of decision, reassurance and detail while adapting the number of plans and comparison rows to the offer.

**Text style:** `technical-display` — ABC Favorit 400 · 78px/1 · tracking -0.06em

### Editorial culture and listings

**Only for:** culture and recruitment pages

**Observed:** A centered eyebrow, display promise, restrained paragraph and paired actions sit above a full-width office image. Three large unboxed statistics lead into three photographic culture stories, followed by split-column principle rows separated by faint rules. Four Benefit cards precede a flat listing of 63px-high role links with 24px top padding, names at left, muted locations and small diagonal arrows at right. Grainy culture conclusion and Directory footer finish the page.

**Transfer:** Replace the principles and listings with the new organization's actual working culture and opportunities; preserve the documentary tone and full-width atmospheric close.

**Text style:** `display` — FFF Acid Grotesk 400 · 58px/64px · tracking -0.03em

### Expanded questions as ending

**Only for:** detailed product pages

**Observed:** A centered 56px FAQ introduction offers paired sales and documentation pills before an 800px-wide column of FAQ items. Several answers remain visible. The last answer leads directly into Directory footer without an additional conversion band.

**Transfer:** Let a thorough FAQ carry the final reassurance when a second closing call would be redundant.

**Text style:** `technical-heading` — ABC Favorit 400 · 56px/58px · tracking -0.001em

## Page flow

**Storyline:** Promise → tangible product demonstration → capability explanation → quantified and human proof → reassurance → an appropriate final action or answered objection → directory.

### Broad platform introduction with multiple product possibilities

1. **Promise and demonstration** — Split stage with a two-tone promise, paired pills and a large luminous interface scene.
2. **Social proof** — A compact monochrome logo strip.
3. **Capability range** — Two-tone section lead and alternating wide/narrow illustrated mosaic.
4. **Quantified and customer proof** — Large unboxed numbers and vividly colored outcome cards on a pale band.
5. **Trust** — Layered conceptual artwork beside an active-label selector.
6. **Closing call** — Centered two-line time-to-value promise, paired actions and patterned pale boundaries.
7. **Directory** — Four link columns and a separate identity-and-principle column.

**Transfer:** Start with one strong product task, broaden into possibilities, then earn the close through proof and trust.

### Recruitment and culture storytelling

1. **Invitation** — Centered promise, short introduction and paired actions above documentary office photography.
2. **Mission and scale** — Compact company explanation, customer examples and three large statistics.
3. **Working principles** — Three photographic stories followed by split-column principle rows.
4. **Practical benefits** — Four compact icon-led cards.
5. **Opportunity** — A flat list of roles, locations and outbound arrows.
6. **Closing call** — Centered invitation on a grainy pastel atmosphere.
7. **Directory** — Shared white footer.

**Transfer:** Move from the feeling of working together to specific expectations and finally an actionable opportunity.

### Explain lower-level infrastructure and reliability

1. **Technical promise** — Tight 78px headline beside a code/control demonstration on a bright backing.
2. **Capability chapters** — Extended dark field with alternating image-and-copy blocks.
3. **Performance proof** — Four dark metric tiles under a centered technical statement.
4. **Applied proof** — Dark split customer-story carousel with dots and a next control.
5. **Closing reassurance** — Periwinkle field with a centered statement and single dark pill.
6. **Directory** — Return to the white shared footer.

**Transfer:** Use the dark variant to create a cohesive technical middle act, then resolve it with a light reassurance band.

### Support a commercial decision without losing product character

1. **Value promise** — Centered tight 78px heading and a short explanatory line.
2. **Plan choice** — Two generously rounded outlined panels with aligned full-width actions.
3. **Reassurance** — Logo strip and a three-column included-feature card grid.
4. **Comparison** — Long blue-black matrix with grouped category bars and circular checks.
5. **Objection handling** — White narrow FAQ list with visible answers.
6. **Closing call** — Short centered 56px statement and two small pills.
7. **Directory** — Shared white footer.

**Transfer:** Present the simple choice first and defer dense specification detail until trust has been established.

### Explain a focused end-user product workflow

1. **Demonstration and promise** — Wide luminous interface collage above a centered two-line headline and paired actions.
2. **Capability summary** — Four small icon-led cards.
3. **Workflow chapters** — Alternating square imagery and eyebrow-heading-bullet blocks.
4. **Quantified proof** — Four compact pale metric tiles.
5. **Implementation choice** — Pale band with short integration choices and paired actions.
6. **Applied proof and resources** — A photographic case study followed by three compact editorial resource links.
7. **Objection handling** — Centered FAQ introduction and expanded answer list.
8. **Directory** — Footer follows the questions directly.

**Transfer:** Let the workflow organize the chapters, then answer implementation concerns and finish with useful detail instead of another generic sales band.

## Writing

Confident, practical and technically fluent without sounding armored or cold. Promises are expressed through concrete actions and supported by specific operational detail; culture copy allows more warmth and personality.

**Do not copy:** Do not reuse Privy or customer names, logos, proprietary artwork, quotes, account counts, commercial terms, performance claims, company relationships or the footer principle as assets or claims for another product. Source examples illustrate syntax and tone only.

- **Addressing the reader:** Speak directly to builders using imperative verbs and occasional 'you' or 'your'; use 'we' for the team's commitments and the product name for factual infrastructure claims.
- **Rhythm:** Headlines are short clauses, often joined as a two-part promise. Support is usually one sentence; cards use compact outcome statements. Technical chapters can include a denser explanatory sentence followed by a concise noun-phrase list.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Begin with a concrete building or enabling verb, then name the outcome. | 6–12 words | “Build products that hold, move, and grow digital assets”<br>“Make digital assets accessible to everyone” |
| Supporting sentence | List the useful operations, then connect first use to long-term scale. | 18–28 words | “Build wallets, move stablecoins, and automate money movement—from first transaction to global scale.” |
| Capability heading | Use an everyday action phrase for the benefit, reserving technical nouns for the explanation. | 3–7 words | “Meet users where they are”<br>“Create wallets behind the scenes” |
| Technical heading | A short factual noun phrase, often with a period. | 2–4 words | “Powerful policy engine.”<br>“Webhooks and indexing.” |
| Primary and secondary actions | Literal verb-led next steps; self-serve and human help appear side by side. | 1–3 words | “Get started”<br>“Contact sales”<br>“Read the docs” |
| Culture invitation | A friendly, slightly unexpected invitation supported by concrete expectations. | 5–9 words | “Join us for some type 2 fun”<br>“Come do your best work.” |
| Closing promise | Parallel short clauses make adoption feel attainable. | 4–6 words per line | “Get started in minutes”<br>“Go live in hours” |

**Words and phrasing to use:** build; hold, move, and grow; behind the scenes; without friction; by design; at scale; your product; from first use to scale

**Avoid:** revolutionary magic; limitless disruption; the ultimate solution; unexplained acronyms in the opening; inflated superlatives without proof

**Rules:**

- Lead with what the reader can accomplish, then explain the machinery.
- Use precise terms in feature lists, but keep the main promise understandable without specialist vocabulary.
- Make customer copy describe an actual outcome, not merely praise.
- Let numbers do evidentiary work; always state what is being counted.
- Keep action labels literal and avoid whimsical button copy.

## Do's and Don'ts

### Do

- Keep default display text at 58px/64px and 400 weight; repeat the gray-clause device in 42px/48px section leads.
- Use the 1200px main width and 32px capability gutters to support deliberately unequal tile widths.
- Keep primary actions 36px high even beside very large media.
- Place a monochrome customer mark, an outcome and a substantial image together in each colored story card.
- Keep artwork corners mostly at 8px and utility cards at 12px; reserve the 32px frame for commercial panels.
- Use a 24px monochrome icon above a compact benefit heading, with 12px internal gaps.
- Give detailed answers an 800px reading width and 16px/28px type.
- Retain the separate identity column and 80px vertical padding in the footer.

### Don't

- Do not make every heading bold; 400-weight type is the source of the spacious display character.
- Do not color primary marketing buttons violet; the violet belongs to media lighting.
- Do not apply decorative box shadows to the page's ordinary cards; the depth is inside illustrations.
- Do not give every capability an identical one-third-width card; use the 784px/384px mosaic relationship.
- Do not replace colorful proof headers with a uniform gray testimonial grid.
- Do not spread the dark technical canvas to ordinary marketing pages; keep it a deliberate page-type variant.
- Do not use the 32px pricing radius on every image and utility card.
- Do not reduce the footer to one centered legal line; its directory and identity asymmetry are substantial parts of the ending.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
