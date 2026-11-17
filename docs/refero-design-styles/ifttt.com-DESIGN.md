# IFTTT — chunky connected color

## Overview

An upbeat, rounded software style that makes complex capabilities feel immediately usable. Heavy rounded sans-serif headlines and oversized pill actions sit on a mostly white canvas, punctuated by black chapters and unapologetic cyan, orange, green and pink blocks. Product-interface illustrations, colorful symbol collections and bold customer quotes provide the visual energy; the overall rhythm is spacious even when the catalog grids are dense.

### Essentials

- Soft letters, hard confidence: one rounded sans family, weight 900 headlines at 79.3px/1 for the opening and 50px/1 for capability chapters, with normal tracking rather than fashionable negative spacing.
- A clear center surrounded by activity: the opening keeps its two-line promise, 660px-wide support and prompt, and 348×101px black action centered while cyan, orange and black symbol collages enter from both clipped edges.
- Buttons are emphatic lozenges: 64px corner radii, 28px/1.1 weight 900 section actions at 79px high; the opening grows to 34px/1.1 and navigation shrinks to 20px/1.1 at 54px high.
- Color lives in objects and chapters, not everywhere: white carries most explanatory content; full-width #111111 chapters alternate with it, while #01b6ff and #ff5e19 frame demonstrations and conversion moments. Green and pink appear as concentrated proof-card fills.
- Show the mechanism as a friendly diagram: include a rounded product stage, typically 1344×480px with 32px corners, containing oversized white interface panels and simple colored tokens. If no interface exists, diagram the input-to-result relationship instead.
- Proof has a loud, human face: pair 660px-wide green and pink quote cards with 34px/1.1 white heavy text, oversized quote marks, white 14px uppercase outcome badges and small circular portraits; use verified outcomes or a concrete customer benefit.
- End with a useful billboard, not only link columns: a 1344×143px rounded white-and-cyan upsell banner sits inside the black footer, followed by four navigation columns and centered circular social controls. Preserve the split-color banner device with the new product’s next step.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric cyan | `#01b6ff` | `--color-cyan` | background, surface, link, accent | Hero collage blocks, proof-band frame, links and footer billboard. |
| Hot orange | `#ff5e19` | `--color-orange` | background, surface, accent | Demonstration backings, collage panels and closing conversion band. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Clover | `#0dd14e` | `--color-green` | surface, accent, text | Outcome quote card, outcome badge text and selected capability cards. |
| Fuchsia | `#ff3cec` | `--color-pink` | surface, accent, text | Companion quote card and selected capability cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#111111` | `--color-ink` | text, background, action | Main lettering, black buttons and dark chapters. |
| Demo charcoal | `#171717` | `--color-demo-dark` | surface | Dark rounded mechanism illustration stage. |
| Raised charcoal | `#292929` | `--color-dark-card` | surface | Visible white 10% fill over the near-black chapter, for upgrade cards and social discs. |
| Secondary gray | `#585858` | `--color-secondary` | text | Visible near-black 70% paragraph text over white. |
| Charcoal edge | `#585858` | `--color-dark-edge` | border | Visible white 30% border over the near-black chapter; distinct from secondary text. |
| Muted gray | `#707070` | `--color-muted` | text | Visible near-black 60% feature descriptions over white. |
| Inverse secondary | `#a0a0a0` | `--color-inverse-muted` | text | Visible white 60% footer headings over near-black. |
| Faint edge | `#e7e7e7` | `--color-edge` | border | Visible near-black 10% outline over white; also the solid comparison-table rule. |
| Mist | `#eeeeee` | `--color-mist` | surface, border | Prompt border, light testimonial backing and bottom of neutral proof gradients. |
| Soft gray | `#f3f3f3` | `--color-soft` | surface | Visible near-black 5% wash over white, used behind symbol pairs and small media. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas, light panels and reversed lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and educational explainers | Pale mint | `#e4f9e7` | `--color-mint` | surface | Soft backing to a symbol-library explainer. |

## Typography

- **Museo Sans Rounded** — All marketing headings, paragraphs, labels and actions. Friendly rounded sans with broad, blunt heavy forms; even small text is substantial rather than wispy. If unavailable, use **Nunito**. Use 700 and 900; retain normal tracking and check headline wrapping. Font stack: "Museo Sans Rounded", "Nunito", "Museo Sans Rounded Fallback", "Avenir Next", helvetica, arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Museo Sans Rounded | 900 | 79.3px | 1 | normal | size clamp(64px, -5.4px + (0.11173 * max(708px, -682px + 100vw)), 88px) | Centered main landing promise, usually two lines. |
| heading-xl | Museo Sans Rounded | 900 | 64px | 1 | normal | fixed | Major proof headings and pricing-page promise. |
| heading | Museo Sans Rounded | 900 | 50px | 1 | normal | fixed | Capability chapter headings and price numerals. |
| heading-small | Museo Sans Rounded | 900 | 34px | 1.1 | normal | fixed | Catalog leads, quote text, billboard line and opening action. |
| action-large | Museo Sans Rounded | 900 | 28px | 1.1 | normal | fixed | Section actions, editorial card titles and FAQ questions. |
| lead | Museo Sans Rounded | 700 | 24px | 1.3 | normal | fixed | Hero support and chapter introduction. |
| action | Museo Sans Rounded | 900 | 20px | 1.1 | normal | fixed | Navigation, standalone links and feature card headings. |
| body | Museo Sans Rounded | 700 | 18px | 1.3 | normal | fixed | Proof support, attributions and comparison entries. |
| body-small | Museo Sans Rounded | 700 | 16px | 1.3 | normal | fixed | Mechanism explanations and compact feature descriptions. |
| label | Museo Sans Rounded | 900 | 16px | 1.3 | normal | fixed | Compact value-proposition headings and footer links. |
| outcome | Museo Sans Rounded | 700 | 14px | 1.3 | normal, uppercase | fixed | White outcome badges inside quote cards. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling pages | closing-display | Museo Sans Rounded | 900 | 88px | 1 | normal | fixed | Monumental left-aligned closing statement. |
| focused solution pages | solution-body | Museo Sans Rounded | 600 | 24px | 32px | normal | fixed | Longer use-case explanation paragraphs. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Normal tracking is consistent across the scale. Rounded forms and weight, rather than letter-spacing effects, create the identity.
- Most large headings use a line height of 1; 34px and 28px heavy text opens to 1.1, and supporting text to 1.3.
- The default lead is weight 700. The lighter weight 600 with 32px lines belongs to focused solution explanations, not the ordinary landing-page lead.

## Layout

**Density:** Airy chapters with compact internal groups: broad white margins separate emphatic visual blocks, while symbol rows and catalogs are tightly packed.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-link gaps and small heading-to-description groups. |
| 12px | Chapter heading to lead and badge to attribution. |
| 16px | Symbol-pair grid gaps, catalog row gaps and small explanation stacks. |
| 24px | Main grid gutters, lead-to-heading gaps, prompt-to-action gap and card internals. |
| 32px | Upgrade card and billboard padding. |
| 40px | Feature-card padding in benefit mosaics and proof-row separation. |
| 48px | Desktop page gutters, action separation and footer/banner spacing. |
| 64px | Chapter header to demonstration and quote-card horizontal padding. |
| 80px | Default top padding for capability and proof chapters. |
| 96px | Closing-band padding and quote-card top inset. |
| 128px | Bottom breathing room of neutral brand-proof bands. |

### Containers and grids

- **page container**: max width 1440px · side padding 48px. Full desktop composition with a 1344px usable inner width; backgrounds extend edge to edge.
- **inner content**: max width 1344px. Wide stages, proof cards and footer billboard share the same edges.
- **hero content**: max width 1116px · side padding 16px. Centered opening text layer; the support and prompt narrow to 660px.
- **reading column**: max width 660px. Centered proof headlines and compact support copy.
- **feature grid**: 3 columns · gap 24px. 432px-wide explanatory cards across the desktop inner container.
- **catalog grid**: 4 columns · gap 24px. 318px-wide example cards; row gap is 16px.
- **proof pair**: 2 columns · gap 24px. Two 660px-wide outcome cards.
- **symbol wall**: 7 columns · gap 24px. Compact service tiles on a dark chapter.
- **solution container** (only for focused solution pages): max width 936px. Narrower two-column illustration and prose layout.
- **plan grid** (only for pricing pages): 4 columns · gap 16px. Centered 310px-wide plan cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 64px |
|  | cards and prompt | 24px |
|  | stages and billboard | 32px |
|  | outcome badge | 16px |
|  | symbol square | 12px |
|  | social disc | 50% |
|  | category tab | 8px |
| pricing pages | plan card | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| catalog lift | `rgba(0, 0, 0, 0.24) 0px 1.5px 6px 0px` | Example cards only; ordinary feature panels are outlined, not elevated. |

### Surfaces

#### White canvas · level 0

**Use:** Default explanatory field.

**CSS:** `background: #ffffff; color: #111111`

#### Black chapter · level 0

**Use:** Catalog, upgrade and editorial contrast bands.

**CSS:** `background: #111111; color: #ffffff`

**Observed:** Edge-to-edge dark sections keep the same content gutters as the white sections.

**Transfer:** Use as a deliberate chapter change, not as the whole page theme.

#### Outlined card · level 1

**Use:** Feature summaries and paired-symbol trays.

**CSS:** `background: #ffffff; border: 2px solid rgba(17, 17, 17, 0.1); border-radius: 24px`

#### Soft tray · level 1

**Use:** Backing for small symbol pairs and feature art.

**CSS:** `background: rgba(17, 17, 17, 0.05); border-radius: 24px`

#### Dark translucent card · level 1

**Use:** Upgrade benefits within a Black chapter.

**CSS:** `background: rgba(255, 255, 255, 0.1); border: 2px solid rgba(255, 255, 255, 0.3); border-radius: 24px; padding: 32px`

**Observed:** Three equal cards center their illustration above a heavy heading and short reversed paragraph.

**Transfer:** Reserve this translucent treatment for dark bands; it is not frosted glass.

#### Neutral proof gradient · level 0

**Use:** Brand trust chapters.

**CSS:** `background: linear-gradient(#ffffff 0%, #eeeeee 100%); padding: 80px 0px 128px`

**Observed:** Subtle vertical change backs a centered headline and a monochrome logo ribbon.

**Transfer:** Keep the gradient neutral and nearly imperceptible.

#### Cyan proof frame · level 0

**Use:** A quantitative proof island.

**CSS:** `background: #01b6ff; padding: 48px`

**Observed:** A white 32px-radius inset panel carries the actual text and numbers.

**Transfer:** Frame a calm, readable proof panel with a loud outer color.

#### Orange close · level 0

**Use:** Conversion statement near the end of a marketing narrative.

**CSS:** `background: #ff5e19; color: #ffffff; padding: 96px 48px; overflow: hidden`

#### Mint explainer · level 1

**Only for:** company and educational explainers

**Use:** Friendly definition panel with an icon field.

**CSS:** `background: #e4f9e7; border-radius: 24px; overflow: hidden`

## Components

### Navigation

**Use:** Simple global wayfinding above the opening.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 22.5px 48px; max-width: 1440px; background: #ffffff`

**Text style:** `action` — Museo Sans Rounded 900 · 20px/1.1

**Observed:** Small wordmark at left, a 400×48px rounded search field beside it when useful, then two text destinations, an outlined login action and filled entry action at right. The whole header is 99px tall. A cyan company-story header reverses the lettering and button treatments.

**Transfer:** Keep a short menu and distinguish account access from the main entry action.

### Primary button

**Use:** Default section conversion action.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #111111; color: #ffffff; border-radius: 64px; height: 79px; padding: 0px 40px`

**Text style:** `action-large` — Museo Sans Rounded 900 · 28px/1.1

**Observed:** The opening uses a taller 101px version with 64px side padding and heading-small type. Navigation uses a 54px version with 28px side padding and action type. On colored or black fields the button reverses to white with black text.

**States:** Declared: hover filter opacity(0.9), background rgba(17, 17, 17, 0.7); focus-visible background rgba(17, 17, 17, 0.6); active filter opacity(0.8), background rgba(17, 17, 17, 0.6).

### Outlined button

**Use:** Login, secondary conversion and nonfeatured plan actions.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 54px; padding: 0px 28px; border-radius: 64px; box-shadow: #111111 0px 0px 0px 2px inset; color: #111111`

**Text style:** `action` — Museo Sans Rounded 900 · 20px/1.1

**Observed:** Same lozenge silhouette as the filled action but outlined on the light canvas. The cyan-header variant uses a white inset outline.

**States:** Declared: hover filter opacity(0.9), background rgba(17, 17, 17, 0.05); focus-visible background rgba(17, 17, 17, 0.6); active filter opacity(0.8), background rgba(17, 17, 17, 0.05).

### Prompt field

**Use:** A direct try-the-product entry inside the opening.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 2px solid #eeeeee; border-radius: 24px; padding: 14px; max-width: 660px; height: 110px; box-sizing: border-box`

**Observed:** A generous multiline input has its hint at the upper left; the primary action is centered beneath it rather than embedded in the right edge.

**Transfer:** Ask for the visitor’s desired result. For products without a prompt workflow, use a comparably simple result-oriented input rather than a fake chat.

### Feature card

**Use:** Short capability explanation with visual proof.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 18px; background: #ffffff; border: 2px solid rgba(17, 17, 17, 0.1); border-radius: 24px`

**Text style:** `action` — Museo Sans Rounded 900 · 20px/1.1

**Observed:** The top art well is 392×200px with a soft-gray backing and 16px corners. Beneath it are a heading, a compact body-small paragraph and a cyan arrow link; three cards fit across the page.

**Transfer:** Show one mechanism or result per card, not an abstract decorative icon alone.

### Integration tray

**Use:** Compact ecosystem proof beside a capability heading.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 24px; background: #ffffff; border: 2px solid rgba(17, 17, 17, 0.1); border-radius: 24px`

**Text style:** `action` — Museo Sans Rounded 900 · 20px/1.1

**Observed:** A heading sits over four pairs of 48px rounded-square symbols. Each pair occupies a 160×80px Soft tray; a tiny connector points from one symbol to the other.

**Transfer:** Pair relevant inputs and outputs. For a product without integrations, pair artifact types or workflow stages.

### Arrow link

**Use:** Secondary exploration after cards or proof.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #01b6ff`

**Text style:** `action` — Museo Sans Rounded 900 · 20px/1.1

**Observed:** A short bold phrase ends with a matching cyan right arrow, 20px square with a 2.5px rounded stroke.

**States:** Declared: hover filter opacity(0.9), color #0089da; focus-visible unknown; active filter opacity(0.8).

### Outcome quote card

**Use:** Strong customer proof in a two-card pair.

**CSS:** `display: flex; flex-direction: column; justify-content: flex-end; gap: 48px; padding: 96px 64px 64px; background: #0dd14e; color: #ffffff; border-radius: 24px`

**Text style:** `heading-small` — Museo Sans Rounded 900 · 34px/1.1

**Observed:** An oversized opening quote sits above the bold statement. An Outcome badge and portrait/name block sit below; a separate Arrow link is outside the card. The companion card is pink. Portraits are small circular cuts, not full photographic backgrounds.

**Transfer:** Keep the quote concrete and preserve the contrasting paired fills.

### Outcome badge

**Use:** Compact quantified outcome within a quote card.

**CSS:** `background: #ffffff; color: #0dd14e; border-radius: 16px; padding: 8px 16px; text-transform: uppercase`

**Text style:** `outcome` — Museo Sans Rounded 700 · 14px/1.3 · uppercase

**Observed:** The text color follows its parent card’s accent; the badge precedes the small portrait attribution.

### Footer billboard

**Use:** An actionable next step before the dense footer navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 48px; padding: 32px; background: #01b6ff; border-radius: 32px; max-width: 1344px; overflow: hidden; margin-bottom: 48px`

**Text style:** `heading-small` — Museo Sans Rounded 900 · 34px/1.1

**Observed:** A white left block, about two fifths of the banner, holds a small product mark and a heavy benefit line. The cyan remainder holds a white action aligned right. The enclosing footer is black with 48px top/side and 64px bottom padding. Four white-link columns sit between a small mark and store badges; muted headings use action type, links use label type. Seven 48px translucent circular social controls finish the footer.

**States:** Declared: hover filter opacity(0.9); focus-visible unknown; active filter opacity(0.8).

**Transfer:** Retain the white/cyan split and benefit/action pairing, using a relevant next step rather than adding an unrelated promotion.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side plan comparison at the top of a pricing narrative.

**CSS:** `display: flex; flex-direction: column; gap: 32px; padding: 26px 22px 22px; background: #ffffff; border: 2px solid rgba(17, 17, 17, 0.1); border-radius: 16px`

**Text style:** `heading` — Museo Sans Rounded 900 · 50px/1

**Observed:** Plan name, large price with smaller cadence, outlined allowance chip, checked feature list, then bottom-aligned action. Four cards are 310px wide and 434px tall. The recommended card rises 22px above its peers with a 24px black top border containing its recommendation label, black remaining edges and a filled action; other paid actions are outlined.

**Transfer:** Keep the decision hierarchy legible before introducing the full comparison table.

### FAQ row

**Only for:** pricing and objection-handling sections

**Use:** Compact answers without a wall of text.

**CSS:** `border-bottom: 4px solid rgba(17, 17, 17, 0.1)`

**Text style:** `action-large` — Museo Sans Rounded 900 · 28px/1.1

**Observed:** A heavy question sits at left and a plus/minus at right. Closed rows are about 77px high; an open answer uses body type below. The first question is open, while the remaining questions are collapsed. A large section title occupies the left column and the 774px-wide question list the right.

**Transfer:** Use actual purchase or adoption objections, with one concise answer visible initially.

## Imagery and graphics

### Orbit collage

**Use:** Signature edge framing around the main opening; repeat its orbital language in a conversion background.

**Observed:** Large cyan and orange rounded panels overlap black inner panels at both sides, partly outside the page. Dotted elliptical paths and small circular service symbols suggest a connected universe without obscuring the central promise.

**Transfer:** Use the new product’s tools, inputs or outcomes as symbols; a set of simple pictograms on white discs is the minimum acceptable replacement.

**Build:** Create two absolutely positioned edge groups behind the text, each with overlapping 24px-radius cyan/orange rectangles and a smaller black rectangle. Clip groups at the viewport edges and keep the central 660px corridor clear. Overlay several large SVG ellipses with 1px white strokes at 20% opacity and a short dotted dash pattern; place 28–54px circular symbol discs around their paths, with some faded to 30% opacity. Avoid blur or photographic texture.

### Mechanism stage

**Use:** The main demonstration device within capability chapters.

**Observed:** Wide 32px-rounded stages back oversized browser panels, stacked trigger/action blocks, large cursor pointers and occasional device silhouettes. Backings alternate flat cyan, orange and a vivid yellow-green; the white interface is the focal object, sometimes cut off by the stage’s bottom edge. A dark compact variant introduces the underlying mechanism.

**Transfer:** Rebuild a legible simplified workflow using a handful of large labels rather than shrinking a complete application. When no UI is available, use a white process panel with two colored steps and a connector.

**Build:** Use a wide 1344×480px clipped panel with 32px corners. Center a white browser-like card with a thin black edge, gray toolbar and three small status dots. Place two rounded colored operation rows inside, connected by a plus or arrow; let the panel extend below the stage when this helps scale. Use cyan or orange for the default backing; choose only one bright backing per stage.

### Catalog symbols and example cards

**Use:** Dense proof of breadth within white example grids and dark symbol walls.

**Observed:** Example cards use flat service-colored fills, white paired symbols at top, heavy multiline task title, tiny service credit and bottom-left usage count. They are 318×368px with 24px corners and a small lift shadow. Symbol-wall tiles are about 171×159px, with a large centered white logo and small heavy label.

**Transfer:** Use distinct category colors tied to actual integrations or artifact types. Keep title-heavy cards separate from the simpler symbol tiles.

### Monochrome trust ribbon

**Use:** Social proof across neutral or black bands.

**Observed:** Recognizable wordmarks appear in a low-contrast gray horizontal ribbon about 36px high, extending beyond the page edges. The neutral version has a centered 64px headline, support paragraph and action; the black pricing version uses a compact 28px lead.

**Transfer:** Use only authorized, real partner or customer marks, equalized by optical weight and muted to a single neutral treatment.

### Editorial image cards

**Use:** Resource discovery within a dark chapter.

**Observed:** Three 432×331px cards combine topical imagery with dark gray, pink or blue lower gradient fields. A small category and heavy white title are pinned near the bottom; the image remains visible at the top.

**Transfer:** Tint relevant product or lifestyle images to a compact color family and preserve a reliable text-reading zone.

**Build:** Fill a 24px-radius card with an image, then overlay a vertical gradient from a transparent version of its dominant hue at the top to an opaque version by halfway down. Place the label and title above that layer at the bottom with 24px internal spacing.

### Hand-drawn explainer

**Only for:** focused solution pages

**Use:** Illustration beside a benefit-focused opening and longer capability explanation.

**Observed:** Loose black line drawings of people using devices sit on irregular pale-gray blobs, with a few bright app symbols, dashed arrows and handwritten annotations. Illustration occupies roughly half the narrow two-column composition.

**Transfer:** Use a simple line drawing of a user and an input-to-result relationship. Keep color limited to a few small functional symbols rather than coloring the whole person.

**Build:** Draw a black 2px rounded-line SVG person and device over a soft irregular light-gray SVG blob; add two colored rounded-square tokens, a dashed curved arrow and two short annotation strokes.

### Split outcome panel

**Only for:** focused solution pages

**Use:** A single testimonial with a large outcome statistic.

**Observed:** A blue doodle-backed left half carries a white outline watch and a heavy two-line saved-time statement. A small blue triangular pointer leads into the light-gray right half, which carries centered black quote text, gray quotation marks and attribution.

**Transfer:** Pair one verified outcome with one readable quote instead of duplicating the main landing page’s two neon cards.

**Build:** Split an edge-to-edge band into two equal panels, blue and mist gray. Add oversized low-opacity white line drawings of a clock, light bulb and result-related symbols on the blue half, then a white outline outcome icon. Place a small right-pointing triangle at the seam.

### Device silhouette close

**Only for:** company storytelling pages

**Use:** Graphic companion to the monumental orange closing line.

**Observed:** Simple white phone, tablet and laptop silhouettes step upward from small to large beside the left-aligned closing text. The shapes are flat, with an orange inset outline separating the white screen and outer contour.

**Transfer:** Use a family of three outcome-related silhouettes of increasing scale; keep them flat rather than rendering glossy hardware.

**Build:** Compose three SVG rounded rectangles of increasing size with a white outer fill, orange inset stroke and white center. Add a thin white rounded base under the widest rectangle. Align all three to one baseline on the right half of the orange band.

### Icons

**Observed:** Service symbols are colorful or reversed white, usually in 48px rounded squares or 54px circles. Utility arrows use 20px boxes with 2.5px rounded strokes; compact benefit icons are black at about 18px. Pricing checks are solid circular 32px icons, green for availability and gray for absence.

**Transfer:** Use recognizable filled integration marks for ecosystem content and sparse rounded-stroke utilities for navigation. Keep utilities smaller and visually quieter than service symbols.

## Section recipes

How recurring sections are built.

### First screen: Centered promise with orbit framing

**Observed:** White canvas beneath the 99px Navigation. The centered display begins after 80px of top space and occupies two broad lines; the lead follows by 24px within a 660px measure. After 48px comes the 660×110px Prompt field, then a 24px gap to the 348×101px Primary button using heading-small. Behind this clear center, Orbit collage panels enter from the far left and right with black inner rectangles and tiny orbiting symbols. The hero itself is 688px tall; within the first 900px the header, entire promise, support, field, action and side artwork are visible, while the explanation chapter remains below the fold.

**Transfer:** Make one plain-language promise and one direct entry interaction the center of the scene. Use pictograms of inputs/results if no integration artwork is available, retaining the edge activity and clear middle. Focused solution pages instead open with a 50px left-aligned promise, longer solution-body copy, black pill and hand-drawn illustration in a 936px two-column container. Pricing opens with a centered 64px promise and plan cards; company storytelling opens on cyan with white 64px text and a white action.

**Avoid:** Do not put a giant dashboard across the center, stack several competing calls to action, or turn the edge collage into a full-bleed multicolor background.

**Text style:** `display` — Museo Sans Rounded 900 · 79.3px/1

### Mechanism introduction

**Observed:** A left text column uses heading, body-small copy and a 79px Primary button beside a 724×392px demo-dark illustration with 32px corners. The wide container has 48px side gutters, 160px top and 120px bottom breathing room.

**Transfer:** Explain the core idea before listing capabilities; use the compact Mechanism stage to make an unfamiliar product understandable.

### Capability chapter

**Observed:** At 80px top and 48px side padding, a left-aligned 50px heading and 24px lead sit beside an Integration tray. A 64px gap leads to the 1344×480px Mechanism stage. Four compact icon/label/body-small value propositions sit below on a 24px grid, followed by a centered Primary button.

**Transfer:** Group one capability around one demonstration and a small set of concrete outcomes; use only as many propositions as the content supports.

**Text style:** `heading` — Museo Sans Rounded 900 · 50px/1

### Example catalog and symbol wall

**Observed:** White example chapters use a centered 34px heading, 48px gap to 8px-radius category tabs, then a four-column grid of title-heavy example cards. Dark symbol chapters use Black chapter with a centered 34px lead, a seven-column symbol wall and a reversed action beneath.

**Transfer:** Use the richer cards for ready-to-use outcomes and the simpler wall for breadth; do not blend their information densities.

**Text style:** `heading-small` — Museo Sans Rounded 900 · 34px/1.1

### Quantified proof island

**Observed:** Cyan proof frame contains a 1344×588px white panel with 32px corners and 80px vertical inner padding. A centered 50px headline and 18px support lead into a horizontal proof row: an award symbol, rating and 34px heavy metrics with 16px captions. Paired distribution badges sit beneath.

**Transfer:** Use comparable verified measures, certifications or adoption outcomes. Keep the numbers compact and the panel white rather than making each metric a separate colored tile.

**Text style:** `heading` — Museo Sans Rounded 900 · 50px/1

### Trust ribbon chapter

**Observed:** Neutral proof gradient centers a 64px headline over a short paragraph, then a full-width monochrome ribbon and a black Primary button with a brief question above it. The pricing variant is a shorter Black chapter with a 28px lead and logo ribbon.

**Transfer:** Make trust legible through equalized marks and restrained contrast, reserving the colorful treatments for product and human outcomes.

**Text style:** `heading-xl` — Museo Sans Rounded 900 · 64px/1

### Outcome pair

**Observed:** A centered 64px proof heading leads into two Outcome quote cards on a 24px gutter, each with Outcome badge, small portrait and an external Arrow link. The section begins with 96px top padding and ends with 80px bottom padding.

**Transfer:** Use a pair of different but related results, retaining the bold white quotation text and green/pink contrast.

**Text style:** `heading-xl` — Museo Sans Rounded 900 · 64px/1

### Conversion close and useful footer

**Observed:** Orange close uses a centered white 50px conversion heading, a white 101px-high pill and subtle orbital line art. It flows into the black footer and Footer billboard rather than ending on the call alone. The company-story variant uses closing-display aligned left and Device silhouette close on the right.

**Transfer:** Close on a single outcome and action, then retain a separate useful next-step billboard and structured resource navigation. Choose the centered default unless a broader brand story merits the monumental variant.

**Text style:** `heading` — Museo Sans Rounded 900 · 50px/1

### Pricing decision and depth

**Only for:** pricing pages

**Observed:** Centered 64px headline and 24px support precede monthly/yearly controls and four Plan cards. A contact action follows. A 4px black-rule comparison heading opens a full-width table with a 442px label column, four 226px value columns, 64–72px rows and 2px gray rules. A colorful 24px-radius benefit mosaic alternates three-column, two-column and full-width cards, followed by a dark trust ribbon, FAQ row list and shared footer.

**Transfer:** Lead with the purchasing decision, then expose detailed comparison and objections without making the opening table-like.

**Text style:** `heading-xl` — Museo Sans Rounded 900 · 64px/1

### Educational alternating panels

**Only for:** company and educational explainers

**Observed:** A gray 24px-radius panel pairs definition copy on the left with overlapping product diagrams at right; a mint panel reverses the alignment with a clipped symbol field on the left. Panels use 48px outer gutters, 50px headings and 24px support, before returning to the neutral trust ribbon.

**Transfer:** Teach two important concepts with opposing compositions and simple diagrams rather than filling a company page with undifferentiated prose.

**Text style:** `heading` — Museo Sans Rounded 900 · 50px/1

## Page flow

**Storyline:** Plain benefit promise → explain the mechanism → show usable examples and capability chapters → substantiate outcomes and trust → make the next step unmistakable → resource-rich footer.

### Broad product landing narrative

1. **Promise and entry** — Centered headline and prompt between orbital symbol panels.
2. **Product explanation** — Short definition beside a compact dark animated mechanism.
3. **Breadth** — Example catalog followed by a dark wall of service symbols.
4. **Capability chapters** — Repeated heading/tray pairs, bright wide demonstrations and compact benefits.
5. **Quantified and commercial proof** — White proof island in cyan, dark upgrade benefits and neutral trust ribbon.
6. **Discovery and human proof** — Dark editorial cards and two loud outcome quotes.
7. **Closing call** — Orange action band, then split-color Footer billboard and black link footer.

**Transfer:** Adapt the length to the product, preserving the contrast between approachable explanation, colorful demonstrations and concrete proof.

### Focused use-case persuasion

1. **Specific promise** — Left headline and substantial paragraph beside a hand-drawn scene.
2. **Ecosystem proof** — Horizontal symbol strip.
3. **Capability explanation** — Illustration beside a stacked benefit list.
4. **Ready-to-use examples** — Narrow three-column example catalog and trial action.
5. **Customer proof** — Split blue outcome/gray quotation panel.
6. **Demonstration and closing call** — Embedded video, then a centered possibility statement and trial pill.
7. **Resource navigation** — Shared split-color billboard and black footer.

**Transfer:** Keep the page narrower and the language more use-case-specific, ending with a short reassurance and action rather than a large orange band.

### Explain the product’s basic concepts and wider relevance

1. **Mission promise** — Cyan orbital opening with white headline and action.
2. **Education** — Alternating gray and mint definition panels with diagrams and symbol field.
3. **Trust** — Neutral logo ribbon chapter.
4. **Closing call** — Monumental white line on orange paired with flat device silhouettes.
5. **Resource navigation** — Shared Footer billboard and black footer.

**Transfer:** Use clear definitions and a compact brand statement, not an unrelated corporate-history essay.

### Resolve the commercial decision

1. **Pricing promise** — Centered value statement, billing control and four equal plan cards.
2. **Detailed comparison** — Expandable comparison heading and long ruled feature table.
3. **Value reinforcement** — Bright, black and white feature mosaic with simplified product art.
4. **Trust** — Compact dark logo ribbon.
5. **Objection handling** — Large title beside an accordion list.
6. **Closing navigation** — Shared billboard and resource-rich black footer; no separate orange conversion band.

**Transfer:** Separate the quick purchase decision from exhaustive feature detail and end on genuine billing objections.

## Writing

Confident, practical and friendly. It presents useful outcomes in plain language, then makes the technical mechanism feel easy through direct examples rather than grandiose abstraction.

**Do not copy:** Do not reuse the IFTTT or IFTTT.ai names, logo, Applet naming system, service artwork, customer quotations, customer identities, partner marks, adoption figures, saved-time claims or source prices as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader with you and your. The product is named when defining how it works; first-person we is mainly used for support, billing and commitments.
- **Rhythm:** Short imperative or benefit headlines, usually 4–9 words, followed by one or two plain sentences. Action labels are short and literal. Longer solution explanations use bold introductory phrases followed by practical detail.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Make a broad benefit feel simple or make the purchasing logic explicit. | 5–10 words | “The easiest way to automate anything”<br>“Pay only for what you use” |
| Supporting line | State what works better, then give a concrete scale or ease cue. | 12–22 words | “Your apps and devices work better together. Connect 1,000+ services in minutes.” |
| Capability heading | Lead with a verb and the reader’s result. | 4–8 words | “Save time and boost productivity”<br>“Set your home on autopilot” |
| Primary action | Literal verb plus a clear entry or exploration step. | 2–5 words | “Start building”<br>“Get started for free”<br>“Start free trial” |
| Outcome label | A specific result and its time basis, set as a compact uppercase badge. | 4–7 words | “5 hours saved every week” |
| Objection question | Ask the actual practical question a buyer would ask. | 4–9 words | “Which payment methods can I use?”<br>“Can I switch plans?” |

**Words and phrasing to use:** connect; build; save time; work better together; your way; get started; make more happen; in minutes

**Avoid:** revolutionary paradigm; synergistic ecosystem; disrupt everything; unprecedented transformation; unexplained technical acronyms

**Rules:**

- Describe an action and its outcome together.
- Follow broad ease claims with a concrete mechanism, example or verified measure.
- Use questions for genuine education and objections, not as coy teaser headlines.
- Keep the action label aligned to what happens next; distinguish exploration, free entry and trial.
- Use concrete task language in example cards, even when it needs several bold lines.

## Do's and Don'ts

### Do

- Use weight 900 rounded headings with normal tracking; keep the large headline line height at 1.
- Align wide stages and footer billboard to the same 1344px inner width and 48px desktop gutters.
- Keep 24px card corners distinct from 32px stage corners and 64px action radii.
- Use white and black for the structural rhythm, and reserve cyan/orange/green/pink for purposeful chapters and objects.
- Keep chapter header-to-stage spacing at 64px and default chapter top padding at 80px.
- Make example cards title-heavy, with white paired symbols and small metadata at the bottom.
- Preserve the 14px uppercase white outcome badge against the bold quote-card fill.
- Use a muted monochrome logo ribbon to keep trust proof calmer than the product demonstrations.

### Don't

- Do not introduce a thin geometric display or serif contrast; the one rounded family carries both authority and friendliness.
- Do not tighten headlines with negative tracking or spread small headings into widely tracked capitals.
- Do not give ordinary white feature cards heavy floating shadows; their default edge is a 2px translucent outline.
- Do not replace the black/white primary pills with small rectangular cyan buttons.
- Do not distribute every accent hue evenly across every section; color is concentrated into specific objects and bands.
- Do not make trust marks full-color competitors to the saturated product art.
- Do not turn the dark upgrade-card treatment into blurred glass; it is simply a translucent fill and outline.
- Do not shrink a complete application into the wide demo stage; use a few oversized readable operation blocks.

## Motion and responsive

### Motion

**Observed:**

- Declared orbital symbol animation runs for 240s, linear, infinitely.
- Declared brand-ribbon animation runs for 30s, linear, infinitely.
- Declared action transitions include opacity 0.2s; some surfaces declare background-color 0.2s. The billing control declares background-color and transform 0.12s ease-in-out.

**Transfer:**

- Keep orbital motion slow enough that the centered prompt and headline remain the primary objects.
- Use a steady linear ribbon for breadth proof; keep important text independent of moving artwork.

**Unknown:**

- The full sequencing and timing of product demonstrations, scroll-triggered behavior and reduced-motion alternatives are not established.

### Responsive

**Observed:**

- The main display uses a clamped viewport-relative formula between 64px and 88px.
- Width breakpoints declared for the broad landing layout include 483px, 723px, 963px, 964px, 1024px, 1025px, 1115px, 1150px, 1170px, 1443px and 1920px.

**Transfer:**

- On narrow layouts, preserve the centered text/prompt corridor and move orbital art farther beyond the edges rather than letting symbols collide with the copy.
- Stack the two-column explanations and outcome pair; reduce catalog columns while retaining the contrast between title-heavy cards and simple symbol tiles.
- Keep the white/cyan distinction in the footer billboard when its action stacks below its benefit.
- Allow detailed pricing comparisons to scroll horizontally instead of compressing four value columns into unreadable labels.

**Unknown:**

- Exact mobile gutters, navigation collapse behavior, card-column breakpoints and reordered mobile artwork are not established; the stacking rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
