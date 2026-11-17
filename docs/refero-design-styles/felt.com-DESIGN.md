# Felt — field notes meet software

## Overview

An editorial software style that makes technical infrastructure feel tangible and human. Warm ivory, charcoal and restrained burnt orange surround expressive serif headlines, practical grotesk text and tiny monospaced annotations. Watercolor environments, pencil diagrams and crisp floating interfaces share an airy light canvas, with occasional dark technical panels adding weight. It suits complex collaborative products that need both approachability and credible working detail.

### Essentials

- Editorial authority without corporate heaviness: GT Alpina at weight 400, a 69.1px opening headline with 1.02 line height and -0.02em tracking, then 46px section headings rather than bold sans display text.
- The opening is a working landscape, not a screenshot billboard: a roughly 560px text column faces an edge-bleeding painted scene across the right half, with white information cards floating over it inside an approximately 900px stage.
- Instrument markings frame the warmth: a 29px charcoal telemetry rail above a 61px ivory navigation bar, plus 11px uppercase mono section labels with 0.1em tracking. Carry this annotated-instrument device to meaningful product context rather than decorative gibberish.
- Actions are small rectangular tools: 46px tall, 4px radius, 13px 23px padding, charcoal primary beside a fine outlined secondary; 34px versions belong in compact navigation and plan cards.
- Color belongs chiefly to the work: ivory dominates the page, charcoal provides isolated inset chapters and the footer, burnt orange marks labels and hover states. Rich greens, blues and pinks are concentrated in artwork and product demonstrations, not alternating saturated marketing bands.
- Handmade explanation is a signature, not an embellishment: use transparent-edged watercolor and pencil art beside sharply rendered interfaces. If there is no equivalent physical landscape, depict the product's workflow as painted sheets, objects and human tasks on ivory.
- Close with an annotated data landscape: a 475px pale dotted-art stage carries a centered 62px serif call and paired actions before a charcoal multi-column footer. Recreate the data-art device using an abstract field of plotted dots when geographic imagery is irrelevant.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt orange | `#a7531b` | `--color-rust` | accent, link, action | Mono labels, active indicators, recommended-plan markers and action hover states. |
| Lit orange | `#dc8c46` | `--color-apricot` | text, accent, link | Labels and links on dark panels, and oversized quotation marks in problem cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Interface white | `#ffffff` | `--color-white` | surface, text | Product windows, plan cards and primary-button text. |
| Ivory paper | `#f4f2ea` | `--color-canvas` | background, text | Default canvas and inverse headings; also used at 0.9 alpha for navigation and 0.86 alpha to veil closing artwork. |
| Gray ivory | `#ecebe3` | `--color-stone` | surface, background | Quote cards, logo bands and browser strips. |
| Paper hairline | `#d6d4cd` | `--color-rule` | border | Visible result of charcoal at 0.14 alpha over ivory; separates sections and lightly outlines cards. |
| Soft inverse text | `#c4c4c3` | `--color-inverse-muted` | text | Footer links: rgba(238,238,238,0.8) over charcoal. |
| Firm paper edge | `#c0beb8` | `--color-edge` | border | Visible result of charcoal at 0.24 alpha over ivory; outlined actions and media frames. |
| Faint inverse markings | `#858581` | `--color-inverse-faint` | text | Telemetry labels: rgba(238,238,238,0.5) over charcoal. |
| Pencil gray | `#69685f` | `--color-muted` | text | Supporting captions and compact feature descriptions. |
| Warm graphite | `#3a382f` | `--color-body` | text | Sans body text and navigation. |
| Charcoal ink | `#1c1b18` | `--color-ink` | text, background, action | Headlines, primary actions, technical panels and footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Recommended parchment | `#f3e8d8` | `--color-plan-tint` | surface | Recommended plan fill. |
| pricing pages | Comparison parchment | `#f9f4eb` | `--color-matrix-tint` | surface | Subtle continuous highlight through the recommended comparison column. |
| pricing pages | Comparison header | `#f5f5f1` | `--color-matrix-head` | surface | Sticky neutral table headings. |
| pricing pages | Table grid | `#dfdfdf` | `--color-matrix-rule` | border | Dense comparison-cell dividers. |
| product demonstrations | Demo black | `#101010` | `--color-video-dark` | surface | Dark application-video backing. |

## Typography

- **GT Alpina** — Headlines, editorial leads, quotations and question labels. Expressive contemporary serif with soft, slightly idiosyncratic forms; regular weight does the display work. If unavailable, use **Lora**. Use 400; retain tight display tracking and test line breaks. Font stack: "GT Alpina", "Lora", Georgia, 'Times New Roman', serif.
- **Atlas Grotesk** — Navigation, actions, working body text, feature labels and prices. Unshowy grotesk with compact, legible forms; mostly regular, with selective medium and bold emphasis. If unavailable, use **Inter**. Use 400, 500 and 700; preserve the contrast with serif editorial text. Font stack: "Atlas Grotesk", Inter, system-ui, -apple-system, sans-serif.
- **SF Mono** — Instrument rail, section eyebrows, numbering, technical captions and comparison values. Small utilitarian monospace; letterspacing distinguishes technical annotations from prose. If unavailable, use **Roboto Mono**. Font stack: "SF Mono", "Roboto Mono", ui-monospace, Menlo, monospace.
- **Publico Text** — Long-form answers and compact explanatory prose. Text-oriented serif, quieter and more readable in long passages than the display serif. If unavailable, use **Source Serif 4**. Use 400 with the specified open line heights. Font stack: "Publico Text", "Source Serif 4", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | GT Alpina | 400 | 69.1px | 1.02 | -0.02em | fixed | Default landing-page opening, broken into a few substantial lines. |
| closing-display | GT Alpina | 400 | 62px | 1.03 | -0.02em | size clamp(30px, 4.6vw, 62px) | Centered closing proposition. |
| heading | GT Alpina | 400 | 46px | 1.06 | -0.015em | size clamp(26px, 3.4vw, 46px) | Major section headings, including inverse chapters. |
| quote | GT Alpina | 400 | 27px | 1.26 | normal | fixed | Customer quotation cards. |
| editorial-lead | GT Alpina | 400 | 26px | 1.3 | -0.01em | fixed | Generous explanatory leads beneath section headings or beside media. |
| question | GT Alpina | 400 | 21px | 1.2 | normal | fixed | FAQ question column. |
| hero-support | Atlas Grotesk | 400 | 18px | 1.55 | normal | size clamp(15px, 1.35vw, 18px) | Opening support, subordinate to the serif promise. |
| body | Atlas Grotesk | 400 | 17.5px | 1.6 | normal | size clamp(15px, 1.3vw, 17.5px) | Capability explanations, especially technical prose. |
| feature-title | Atlas Grotesk | 700 | 17px | 1.294 | normal | fixed | Compact ruled-list titles. |
| closing-support | Atlas Grotesk | 400 | 17px | 1.294 | normal | fixed | One centered reassurance under the closing headline. |
| answer | Publico Text | 400 | 16.5px | 1.6 | normal | fixed | FAQ answers and inline contextual links. |
| text-link | Atlas Grotesk | 400 | 16px | 1.313 | normal | fixed | Underlined contextual navigation ending in a right arrow. |
| action | Atlas Grotesk | 500 | 15px | 1.2 | normal | fixed | Primary conversion buttons. |
| secondary-action | Atlas Grotesk | 400 | 15px | 1.2 | normal | fixed | Outlined secondary buttons. |
| caption | Atlas Grotesk | 400 | 14px | 1.55 | normal | fixed | Small feature descriptions and supporting details. |
| navigation | Atlas Grotesk | 400 | 14px | 1.286 | normal | fixed | Main navigation links. |
| footer-link | Atlas Grotesk | 400 | 13.5px | 1.26 | normal | fixed | Footer directories. |
| eyebrow | SF Mono | 400 | 11px | 1.545 | 0.1em, uppercase | fixed | Section and category labels. |
| telemetry | SF Mono | 400 | 11px | 1.545 | 0.06em | fixed | Instrument-rail labels and values. |
| question-number | SF Mono | 400 | 10.5px | 1.2 | 0.14em | fixed | Small sequential numbers alongside questions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| solution and industry pages | solution-display | GT Alpina | 400 | 86.4px | 0.98 | -0.025em | size clamp(40px, 6vw, 88px) | Larger multi-line promise opposite a rectangular live-product view. |
| AI product landing pages | ai-display | GT Alpina | 400 | 50.4px | 0.98 | -0.025em | fixed | Compact two-line promise over a broad painted product environment. |
| pricing pages | pricing-display | GT Alpina | 400 | 36px | 1.05 | -0.02em | size clamp(28px, 2.6vw, 36px) | Compact promise above immediately visible plans. |
| solution and industry pages | workflow-heading | GT Alpina | 400 | 32px | 1.12 | -0.015em | size clamp(24px, 2.3vw, 32px) | Individual workflow-stage headings. |
| pricing pages | price | Atlas Grotesk | 400 | 27px | 1 | -0.02em | fixed | Plan prices, deliberately restrained rather than oversized statistics. |
| pricing pages | plan-name | GT Alpina | 400 | 25px | 1.1 | -0.015em | fixed | Tier names. |
| pricing pages | matrix-value | SF Mono | 400 | 11.5px | 1.5 | 0.04em | fixed | Centered numeric limits and availability values. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep serif display at regular weight. Negative tracking grows from -0.01em in leads to -0.025em in the largest solution promises.
- The default explanatory lead is serif; longer technical explanations use the sans body recipe, and FAQ answers switch to the reading serif. Do not flatten these roles into one body style.
- Mono is annotation, not the main text voice. Uppercase eyebrows contrast with sentence-case headings and ordinary mixed-case prose.
- Keep headline widths intentional: approximately 560px for the default opening, 760px for section heads and leads, and 570px for the centered closing line.

## Layout

**Density:** Airy at chapter scale, with compact working details inside each chapter; long product views receive breathing room without becoming isolated tiles.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Paired-action gap and compact inline groups. |
| 16px | Eyebrow-to-section-heading separation and top padding of ruled feature items. |
| 20px | Quote and gallery grid gaps; closing headline-to-support gap. |
| 24px | Quote-card padding. |
| 26px | FAQ row vertical padding and navigation link gaps. |
| 34px | Declared inner container gutter. |
| 40px | Default content grid gap and section-head-to-content interval. |
| 44px | Inset technical-panel padding and workflow-stage vertical intervals. |
| 56px | Wide media/text split gaps and space before compact feature grids. |
| 72px | Default major-section vertical padding. |
| 96px | Closing-stage vertical padding. |

### Containers and grids

- **content-container**: max width 1320px · side padding 34px. Centered desktop content; visible content edges are 60px from the viewport edges at 1440px. The inner gutter is part of an outer padded wrapper, not an extra 34px added to those visible edges.
- **editorial-column**: max width 760px. Section headline and lead column; leaves the remaining width open until media or a grid begins.
- **opening-copy**: max width 560px. Left-aligned opening copy, vertically centered beneath the navigation.
- **feature-grid**: 4 columns · gap 40px. Ruled compact capabilities, four roughly 300px columns.
- **proof-grid**: 3 columns · gap 20px. Three equal quote cards or media-led resource cards.
- **wide-split**: 2 columns · gap 56px. Unequal 5:7 text/media split; artwork receives the larger side.
- **closing-container**: max width 900px · side padding 48px. Centered content over a full-width data-art field.
- **workflow-spine** (only for multi-stage solution pages): 2 columns · gap 48px. 220px left index beside a flexible 1052px illustration column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | cards-and-media | 6px |
| mobile product demonstrations | phone-shell | 31.7px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| media-lift | `rgba(28, 27, 24, 0.4) 0px 24px 60px -30px` | Large product windows; a broad low shadow, never a hard elevation stack. |
| dark-panel-lift | `rgba(28, 27, 24, 0.5) 0px 24px 60px -30px` | Inset charcoal technical and trust chapters. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page material.

**CSS:** `background: #f4f2ea; color: #1c1b18`

**Observed:** A warm, flat field separated by fine horizontal rules; no overall paper-noise overlay.

**Transfer:** Keep this continuous base behind prose, art and lists.

#### Ivory glass navigation · level 3

**Use:** Fixed main navigation beneath the instrument rail.

**CSS:** `background: rgba(244, 242, 234, 0.9); border-bottom: 1px solid rgba(28, 27, 24, 0.14); backdrop-filter: blur(10px)`

**Observed:** Translucency is confined to the header rather than applied to all cards.

**Transfer:** Let scrolling artwork faintly register beneath the navigation.

#### Stone proof card · level 1

**Use:** Quotation surfaces and restrained proof groupings.

**CSS:** `background: #ecebe3; border: 1px solid rgba(28, 27, 24, 0.14); border-radius: 6px`

**Observed:** Only slightly darker than paper, with no default drop shadow.

**Transfer:** Reserve the fill for bounded testimony, not every paragraph.

#### Product window · level 2

**Use:** Framed working interfaces and video.

**CSS:** `background: #ffffff; border: 1px solid rgba(28, 27, 24, 0.24); border-radius: 6px; box-shadow: rgba(28, 27, 24, 0.4) 0px 24px 60px -30px; overflow: hidden`

**Observed:** Can span the whole content width or sit opposite a lead; dark product video uses a demo-black backing.

**Transfer:** Present a coherent task and result rather than a collection of cropped dashboard widgets.

#### Charcoal inset · level 1

**Use:** Technical or trust emphasis within an ivory page.

**CSS:** `background: #1c1b18; color: #f4f2ea; border-radius: 6px; padding: 44px 44px 40px; box-shadow: rgba(28, 27, 24, 0.5) 0px 24px 60px -30px`

**Observed:** Inset from the outer page edges; orange annotations and muted ivory prose sit inside.

**Transfer:** Use for a distinct credibility argument or explanation, not as an arbitrary alternating background.

#### Closing veil · level 1

**Use:** Pale overlay above dense dotted data art.

**CSS:** `background: rgba(244, 242, 234, 0.86)`

**Observed:** Suppresses the illustration until it is almost a watermark.

**Transfer:** Maintain enough tonal separation for the foreground proposition to read cleanly.

#### Drafting field · level 0

**Only for:** solution and industry openings

**Use:** Faint technical texture behind the hero split.

**CSS:** `background-color: #f4f2ea; background-image: radial-gradient(circle, rgba(28, 27, 24, 0.2) 0.8px, transparent 1.3px); background-size: 24px 24px; background-position: 50% 0%`

**Observed:** Tiny low-contrast dots provide measurement-paper character without competing with the image.

**Transfer:** Keep dots faint and behind all copy.

#### Recommended tier · level 1

**Only for:** pricing pages

**Use:** One selected tier within the joined comparison cards.

**CSS:** `background: #f3e8d8; border-left: 1px solid rgba(28, 27, 24, 0.14); box-shadow: inset 0px 3px 0px 0px #a7531b`

**Observed:** Uses a thin rust top accent, not a glowing outline.

**Transfer:** Highlight only one tier, and carry a lighter parchment tint down its table column.

## Components

### Instrument rail

**Use:** Persistent technical signature above navigation.

**CSS:** `height: 29px; background: #1c1b18; color: rgba(238, 238, 238, 0.5)`

**Text style:** `telemetry` — SF Mono 400 · 11px/1.545 · tracking 0.06em

**Observed:** Left clusters of coordinates, bearing and zoom; a coordinate-system label and miniature scale bar balance the right. Values change with the page's visual narrative.

**Transfer:** Use concise, relevant measurements, system context or document coordinates for another product.

### Navigation

**Use:** Primary site orientation and compact conversion.

**CSS:** `height: 61px; background: rgba(244, 242, 234, 0.9); border-bottom: 1px solid rgba(28, 27, 24, 0.14); backdrop-filter: blur(10px)`

**Text style:** `navigation` — Atlas Grotesk 400 · 14px/1.286

**Observed:** Brand mark left; links and small downward chevrons right, followed by outlined login and solid signup. The rail and navigation form a fixed 90px assembly. Compact buttons are 34px tall with 8px 15px padding and 13.5px text.

**States:** Declared: hover link color #a7531b.

**Transfer:** Keep categories few and leave the brand side open.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; box-sizing: border-box; height: 46px; padding: 13px 23px; background: #1c1b18; color: #ffffff; border: 1px solid transparent; border-radius: 4px`

**Text style:** `action` — Atlas Grotesk 500 · 15px/1.2

**Observed:** Text-only rectangular action; sits beside the outlined secondary rather than spanning the page.

**States:** Declared: hover background #a7531b.

**Transfer:** Use a concrete low-friction action with a similarly short label.

### Secondary button

**Use:** Sales or guided-product alternative.

**CSS:** `display: flex; align-items: center; justify-content: center; box-sizing: border-box; height: 46px; padding: 13px 23px; color: #1c1b18; background: transparent; border: 1px solid rgba(28, 27, 24, 0.24); border-radius: 4px`

**Text style:** `secondary-action` — Atlas Grotesk 400 · 15px/1.2

**Observed:** Same height as the primary; a right arrow is part of the label. Compact outlined variants serve login and non-featured plans.

**States:** Declared: hover border-color #a7531b; color #a7531b.

### Text link

**Use:** Contextual exploration beneath section prose.

**CSS:** `color: #1c1b18; text-decoration: underline`

**Text style:** `text-link` — Atlas Grotesk 400 · 16px/1.313

**Observed:** Ordinary underlined text with a trailing arrow; inverse variants turn ivory with orange hover.

**States:** Declared: hover color #a7531b; opacity 1.

**Transfer:** Link to the next relevant detail without making every exploration a button.

### Quote card

**Use:** Compact customer proof in a row or beside a product view.

**CSS:** `display: flex; flex-direction: column; background: #ecebe3; border: 1px solid rgba(28, 27, 24, 0.14); border-radius: 6px; padding: 24px`

**Text style:** `quote` — GT Alpina 400 · 27px/1.26

**Observed:** Monochrome logo first, roomy serif quote next, then a ruled lower attribution zone with mono organization name, sans person and muted story title. Equal-height cards align their lower metadata.

**Transfer:** Use approved testimony with enough space for a human sentence, not an oversized metric.

### Ruled feature

**Use:** Dense capability or audience directories.

**CSS:** `border-top: 1px solid rgba(28, 27, 24, 0.24); padding-top: 16px`

**Text style:** `feature-title` — Atlas Grotesk 700 · 17px/1.294

**Observed:** Small orange mono number above a bold sans title, then muted caption; directories replace numbering with linked titles and arrows. Transparent backing maintains the paper field.

**Transfer:** Use concise task names and one or two lines of practical explanation.

### FAQ row

**Use:** Visible objection handling.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 1fr) minmax(0px, 1fr); gap: 40px; padding: 26px 0px; border-bottom: 1px solid rgba(28, 27, 24, 0.14)`

**Text style:** `question` — GT Alpina 400 · 21px/1.2

**Observed:** Tiny sequential mono number precedes the serif question in the left half; reading-serif answer occupies the right half. Answers are shown together, not hidden behind disclosure controls. Longer sets have mono category headings.

**Transfer:** Answer the real operational objection directly before adding qualifications.

### Footer directory

**Use:** Final navigation after the pale closing stage.

**CSS:** `background: #1c1b18; padding: 60px 34px 36px; color: rgba(238, 238, 238, 0.8)`

**Text style:** `footer-link` — Atlas Grotesk 400 · 13.5px/1.26

**Observed:** A brand block and brief tagline occupy the left; four compact directories occupy the right with 52px gaps. Mono category labels and a coordinate annotation accompany the brand. A faint top-ruled bottom row holds copyright and coordinate-system markings.

**States:** Declared: hover link color #dc8c46.

**Transfer:** Retain the contrast between spacious brand block and compact utility columns.

### Plan card

**Only for:** pricing pages

**Use:** Joined subscription tiers.

**CSS:** `background: #ffffff; padding: 26px 24px 28px; border-left: 1px solid rgba(28, 27, 24, 0.14)`

**Text style:** `plan-name` — GT Alpina 400 · 25px/1.1 · tracking -0.015em

**Observed:** Four joined 330px-wide cards share a single rounded outer enclosure. Tier name, serif one-line purpose, 27px sans price, full-width compact CTA, seat allowance and ruled feature list align vertically. Recommended tier uses Recommended tier and the solid CTA; the others use outlined actions. A full-width charcoal add-on strip sits below.

**Transfer:** Keep the price modest and make billing, included seats and feature differences explicit.

### Comparison cell

**Only for:** pricing pages

**Use:** Detailed plan comparison.

**CSS:** `padding: 10px 14px; border-bottom: 1px solid #dfdfdf; border-left: 1px solid #dfdfdf; text-align: center`

**Text style:** `matrix-value` — SF Mono 400 · 11.5px/1.5 · tracking 0.04em

**Observed:** A 422px label column leads four 224px value columns. Rows are generally 40px tall; category bands interrupt the grid. Sticky 74px headers keep names visible, and the recommended column keeps a pale parchment fill. Rust outline checks indicate availability; unavailable values use faint dashes.

**Transfer:** Group features by user task and keep values terse.

## Imagery and graphics

### Painted working landscape

**Use:** Signature opening scene and major explanatory illustrations.

**Observed:** Bird's-eye terrain, farms, roads, rivers and trees are rendered in translucent sage, straw, dusty blue and ochre washes with fine pencil contours. Irregular brush edges dissolve into the ivory canvas rather than ending in a rectangle. White task summaries, chat cards, pins and collaborator avatars hover sharply above the paint; the artwork is larger than the text and bleeds beyond the right edge.

**Transfer:** Illustrate the new product's real working environment or an arrangement of its inputs and outputs. Preserve paper, pigment, imperfect outlines and clean live annotations. Minimum acceptable version is a coherent hand-drawn workflow of layered sheets and objects with a small real interface card, not a generic stock landscape.

**Build:** Use an SVG scene extending across roughly the right 60% of the opening. Layer irregular low-opacity pigment polygons and thin, slightly varied graphite strokes; soften the outer perimeter with a mask made of overlapping uneven ellipses. Use muted olive and ochre washes, pale blue routes and unpainted paper gaps. Add a subtle SVG turbulence/displacement filter to the pigment layer only; keep text and floating UI outside that filter. Composite white 6px-radius task cards above the art with broad low-opacity shadows.

### Human workflow watercolor

**Use:** Large narrative explanation between technical chapters.

**Observed:** A wide connected triptych places a person outdoors, a person at a desktop and a group gathered around a table in one sunlit painted environment. The image expands across the content width below a narrow editorial lead; no hard photo frame separates the scenes.

**Transfer:** Show the same work passing between different people or contexts, using natural daylight, warm paper and lightly drawn details rather than corporate portrait photography.

**Build:** Arrange three overlapping SVG or illustrated vignettes along a shared ground line. Keep figures and work objects strongest near the bottom, with pale plant and architectural washes behind them. Mask each vignette with irregular paper-edge shapes so neighboring scenes merge; leave generous unpainted space at the top.

### Working product views

**Use:** Proof of capabilities, media-led galleries and live examples.

**Observed:** Wide application windows show actual layers, controls, side panels and selected results. They use Product window, sometimes with a stone browser strip. Smaller popups overlap the main view; phone demonstrations use two upright devices side by side. Saturated visualizations remain inside the interface.

**Transfer:** Show a plausible completed task with readable hierarchy; keep outer framing restrained and preserve the relationship between the main result and a small contextual popup.

### Painted object diagrams

**Use:** Explain tools, data types and audience roles.

**Observed:** Small stacks of map sheets, a database cylinder connected by a thread, a brush over colored hexagons, a field observer and aerial imagery appear as isolated watercolor-pencil objects directly on ivory. Industry data tiles add imperfect square pencil frames.

**Transfer:** Draw a few concrete objects that clarify the product's mechanism, with the same warm light and paper backing.

**Build:** Use thin irregular graphite SVG outlines with translucent muted color fills, offset duplicate contours by 1px in a few places, and add tiny ground shadows below objects. For sheet stacks, draw three offset quadrilaterals with gently curved edges and sparse marks. Leave objects isolated instead of enclosing them in glossy icon tiles.

### Exploded technical drawing

**Use:** Technical credibility beside inverse-panel prose.

**Observed:** A hand-drawn exploded app stack uses fine ivory outlines above a painted lower layer; the dark material makes the layers read like a workshop diagram. A fuller technical chapter links simple outline symbols, tool-call rows and a painted output sheet with thin arrows.

**Transfer:** Expose the new product's layers or operational sequence using diagrammatic lines and one tangible result, not neon abstract circuitry.

**Build:** On charcoal, draw three perspective quadrilaterals separated vertically, connect aligned corners with faint dashed lines, and add sparse UI-line marks to the top sheet. Use ivory strokes at low alpha and one desaturated painted result layer. For a sequence, distribute outline symbols across a horizontal row with thin connecting arrows and short mono annotations.

### Dotted closing landscape

**Use:** Signature full-width conversion-stage backing.

**Observed:** An enlarged map-like data field made of pale circular dots is rotated diagonally and partly outside the stage. Warm gray and faint ochre patches are strongly veiled so centered black typography stays dominant.

**Transfer:** Always include this plotted-data closing device; for a non-spatial product, form dots into an abstract field or a meaningful output silhouette rather than copying a map.

**Build:** Create an SVG pattern of circles on a regular grid, clip it to several broad irregular polygons, and rotate the group approximately -25deg. Vary circle radius and gray/ochre opacity in zones, extend it beyond all stage edges, then overlay Closing veil. Keep the approximately 475px stage light enough that the pattern reads as a watermark.

### Icons

**Observed:** Navigation chevrons are tiny 9px by 6px outlines with 1.2px round strokes. Pricing checks are 11px by 9px rust outlines with 1.6px round strokes. Integration logos retain small native colors; painted explanatory objects are larger and more expressive than utility icons.

**Transfer:** Use restrained thin outline utility symbols at small scale. Keep pictorial explanation handmade rather than replacing it with a large uniform filled-icon library.

## Section recipes

How recurring sections are built.

### First screen: Painted product opening

**Observed:** The first 900px is a complete composition: Instrument rail and Navigation occupy the upper 90px, followed by a vertically centered left copy stack and a broad right-hand Painted working landscape. The copy spans about two fifths of the width, with an orange mono eyebrow, a three-line regular serif promise at 69.1px, an 18px sans support line and paired 46px Primary button and Secondary button. Back-to-front layers are ivory paper, watercolor environment fading toward the text, crisp floating working cards and pins, then copy and controls. The main object fills most of the right half and bleeds off the viewport; a small progress-dot row sits near the lower left. Headline, support, both actions and the main illustrated task are all visible before 900px; the logo-proof band starts below this stage.

**Transfer:** For a different product, paint its working context or a sheet-and-object workflow and overlay a small believable result card. Preserve the contrast between editorial promise and a tangible working scene. Solution and industry openings instead use Drafting field, a larger solution-display and a 5:7 split with a framed product view and overlapping popup. AI-focused openings keep the painted environment but use the more compact ai-display. Pricing opens with pricing-display and immediate joined tiers rather than this illustrated stage.

**Avoid:** Do not center a generic headline over a small dashboard, put a hard rectangular boundary around the painted environment, or let the image fade erase the product's actual working detail.

**Text style:** `display` — GT Alpina 400 · 69.1px/1.02 · tracking -0.02em

### Editorial chapter

**Observed:** Paper canvas sections use a top hairline and 72px vertical padding. An eyebrow precedes heading by 16px; the 760px-wide lead or media begins 40px below the heading group. A chapter can use a full-width Product window, a wide illustration, or a split with editorial prose.

**Transfer:** Give each chapter one user outcome, then show the mechanism in a clear working view.

**Text style:** `heading` — GT Alpina 400 · 46px/1.06 · tracking -0.015em

### Capability directory

**Observed:** Ruled feature items form four columns with 40px gaps; mono numbers, bold 17px names and muted 14px descriptions make the density feel like an annotated reference sheet rather than a bento board.

**Transfer:** Use this for the compact supporting layer beneath a larger demonstration.

### Proof row and paired proof

**Observed:** Three Quote cards form a 20px-gap row. In use-case chapters a larger Product window sits left of one taller Quote card, followed by a ruled three-column list of relevant inputs. Logos and lower attribution zones align across the cards.

**Transfer:** Pair an observable result with a human account of why it mattered.

### Technical inset

**Observed:** Charcoal inset sits within normal section margins and uses an orange eyebrow, inverse heading and either a 5:7 drawing split or three to four numbered proof points. The exploded drawing supplies visual explanation, while short sans text names the concrete interfaces or guarantees.

**Transfer:** Adapt to architecture, reliability or controls that matter to the new audience.

### Visible questions

**Observed:** A standard editorial chapter introduces FAQ rows; all answers remain visible in a two-column question/answer arrangement. Numbering is tiny and gray; rules and 26px row padding replace card fills.

**Transfer:** Use fewer well-answered questions on a general landing page, with mono category dividers for a longer commercial FAQ.

### Pale call and dark directory

**Observed:** A full-width 475px Dotted closing landscape and Closing veil hold a centered eyebrow, 62px two-line proposition within about 570px, a 17px reassurance and paired actions. Immediately below, Footer directory uses about 539px of charcoal with a left brand block, four right directories and a ruled utility baseline.

**Transfer:** End with a specific achievable result and low-friction invitation, then keep the utility footer visibly separate from the conversion stage.

**Text style:** `closing-display` — GT Alpina 400 · 62px/1.03 · tracking -0.02em

### Indexed workflow

**Only for:** multi-stage solution pages

**Observed:** A 220px left index stays beside a broad sequence of painted explanations, separated by 48px. Each index row pairs a mono number with a serif action name; the active row has a 2px rust left rule. Each stage places a roughly 1052px-wide illustration above a 32px serif heading and concise supporting prose, divided by hairlines and 44px vertical intervals.

**Transfer:** Use for a real multi-step workflow where the user needs to understand progression, not for unrelated features.

### Industry capability split

**Only for:** industry landing pages

**Observed:** Numbered 32px serif headings and compact sans descriptions occupy the left; a roughly 638px by 425px result view occupies the right, with a smaller floating legend overlapping its upper-left edge. A small mono caption below names the demonstrated material. Subsequent chapters introduce four painted role objects and a three-column grid of square illustrated inputs.

**Transfer:** Translate the product into the audience's everyday work and evidence before discussing the broad platform.

### Pricing and comparison

**Only for:** pricing pages

**Observed:** A compact serif promise and reassurance appear above four joined Plan cards; the billing toggle aligns to the right. One highlighted plan uses parchment, a rust top line and small Recommended badge. A charcoal add-on strip spans below. After a logo band, the Comparison cell grid uses sticky headers, task-based category bands and a continuous tinted recommended column.

**Transfer:** Make both the initial choice and the detailed comparison easy to audit; retain the source's modest price scale.

## Page flow

**Storyline:** Outcome promise → tangible working demonstration → capability explanation and human proof → trust and objections → result-oriented invitation → utility directory.

### Broad platform introduction

1. **Promise** — Painted product opening makes the complex tool approachable.
2. **Social proof** — Shallow gray-ivory band of monochrome customer marks.
3. **Product demonstration** — Editorial lead and wide application video establish one shared working view.
4. **Capability chapters** — Alternate painted scenes, working views, integration lists, mobile devices and ruled directories.
5. **Credibility** — Quotes, inset technical chapters, trust points and a media gallery add different kinds of proof.
6. **Objection handling** — Visible questions answer adoption concerns.
7. **Closing call** — Pale dotted-art invitation followed by the charcoal directory.

**Transfer:** Use an expansive platform story without turning every capability into the same card.

### Help buyers understand cost and select a tier

1. **Commercial promise** — Compact heading, billing reassurance, four joined tiers and a dark add-on strip.
2. **Social proof** — Monochrome logo band interrupts commercial detail.
3. **Comparison** — Long categorized grid with sticky headers and one tinted column.
4. **Objection handling** — Numbered visible questions grouped by billing, access, usage and support.
5. **Closing call** — Trial reassurance in the pale dotted stage, then the common dark directory.

**Transfer:** Bring the offer above the fold and use precise language instead of persuasive ornament.

### Explain a concrete decision-making workflow

1. **Promise** — Large serif statement opposite a live-view frame and popup on a drafting field.
2. **Problem recognition** — Three stone cards open with oversized orange quotation marks and familiar objections.
3. **Workflow** — Indexed stages explain assembly, evaluation and collaboration with large handmade scenes.
4. **Applied proof** — Repeated use-case chapters combine a real product view, quote and ruled input list.
5. **Adoption** — Four top-ruled columns explain how existing material enters the system.
6. **Closing call** — Outcome-specific dotted-art invitation and common footer.

**Transfer:** Use audience language and a concrete workflow before expanding into adjacent applications.

### Introduce an intelligent feature and explain its mechanism

1. **Promise** — Compact serif statement over a painted result environment with floating conversation and summary cards.
2. **Demonstration** — Large working video shows a request turning into a result.
3. **Capability explanation** — A second demonstration pairs with four painted tool-object cards.
4. **Human proof** — A large editorial quote and story face a result view.
5. **Technical mechanism** — Full-width charcoal chapter diagrams a hosted process with thin lines, tool-call annotations and a painted output.
6. **Credibility and objections** — Result-building cards, inset trust points and categorized visible questions.
7. **Closing call** — Shared dotted-art invitation and dark directory.

**Transfer:** Show what the feature produces, then reveal enough of the mechanism to make it credible.

### Translate a broad product for a specific professional audience

1. **Audience promise** — Large serif industry statement opposite an immediately relevant working view.
2. **Social proof** — Audience-specific monochrome logo band.
3. **Capability chapters** — Numbered text/result splits with overlapping legends and small technical captions.
4. **Audience and inputs** — Painted role objects and square framed illustrations explain who works and what material they use.
5. **Proof and enablement** — Quote row, charcoal operational chapter and media-led learning resources.
6. **Objection handling** — Five visible practical questions.
7. **Closing call** — Audience-specific outcome in the pale dotted stage, followed by the common footer.

**Transfer:** Keep the shared design language but rewrite tasks, imagery and objections around the audience's actual day.

## Writing

Plainspoken, warm and technically literate. Confidence comes from naming the work, its friction and the tangible result rather than making sweeping promises.

**Do not copy:** Do not reuse Felt's brand name, wordmark, customer logos, named customer stories, quotations, product-specific claims, prices, compliance assertions or performance numbers as facts for another product. Source examples below illustrate phrasing only.

- **Addressing the reader:** Speak to the reader as you and your team; name the product in straightforward third person when explaining what it does. Use real task roles rather than a vague collective we.
- **Rhythm:** Sentence-case headlines usually fit 4–10 words; supporting copy combines a short assertion with one concrete explanation. Fragments and compact lists add pace, while technical paragraphs and answers stay calmly complete.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the infrastructure or outcome in the reader's working life. | 6–10 words | “The spatial infrastructure your business runs on” |
| Capability heading | Start with a practical verb and a recognizable object or result. | 5–10 words | “See your whole operation on one map”<br>“Keep field boundaries current” |
| Technical reassurance | Explain the removal of a concrete burden in ordinary language. | One short heading and one explanatory paragraph | “Your data gets in without a fight” |
| Primary action | Direct verb with low-friction qualifier or immediate outcome. | 2–5 words | “Get started for free”<br>“Put a map in the field” |
| Commercial promise | State the billing principle plainly, not as an aspirational slogan. | 8–12 words | “Start free, pay for the people doing the work” |
| Closing proposition | Turn the product promise into a result the reader can begin now. | 6–10 words | “Bring your data, see it on the map” |

**Words and phrasing to use:** your team; live; share; connect; bring; ask; build; one place; without; in plain language

**Avoid:** revolutionary; next-generation; unlock limitless potential; seamless synergy; supercharge everything; AI magic

**Rules:**

- Describe a before-and-after task instead of listing adjectives.
- Use specific technical nouns where they clarify the mechanism; translate their practical benefit in the same paragraph.
- Answer yes-or-no questions directly before explaining conditions.
- Keep the closing support sentence focused on effort, access or the immediate result.
- Use arrows for onward exploration, not exclamation marks for urgency.

## Do's and Don'ts

### Do

- Set the default opening serif at 69.1px with regular weight and tight -0.02em tracking.
- Keep section headings at 46px and editorial leads at 26px so explanation retains a book-like hierarchy.
- Maintain 72px chapter padding and 40px main content gaps on desktop.
- Stage white product windows with 6px corners, fine edges and broad low shadows.
- Use 11px mono capitals with 0.1em tracking for section labels.
- Keep action pairs 12px apart, with 46px heights and 4px corners.
- Include painted explanation and a pale plotted-data closing field even when the new product is not geographic.
- Use 20px gaps for quote and gallery rows, and 40px gaps for ruled capability directories.

### Don't

- Do not replace the ivory canvas with pure white across the marketing page; white belongs to working windows and plan cards.
- Do not use rust as a full-page background or a default oversized primary CTA; it is an annotation and hover color.
- Do not turn the 4px action corners into pills or the 6px media edges into soft app-store cards.
- Do not apply the product interface's vivid pinks, purples and blues to ordinary marketing text and section backgrounds.
- Do not make every prose section a shadowed card; transparent ruled directories are a major part of the system.
- Do not render all body text in the same sans face; editorial leads and long FAQ answers have distinct serif roles.
- Do not inflate prices into giant billboard numerals; the pricing recipe uses 27px sans numbers.
- Do not use mono for long marketing paragraphs or large promises; it should remain instrument-scale.

## Motion and responsive

### Motion

**Observed:**

- Primary buttons declare background 0.18s; outlined buttons declare border-color 0.15s and color 0.15s. Footer links declare color 0.14s.
- The opening has multiple illustrated scenes, compact progress dots and accessible play/pause controls. Some product demonstrations expose a separate Play animation control.
- The instrument rail declares linear scroll-linked zoom and scale animations. Quote surfaces declare border-color and box-shadow transitions of 0.16s.
- A technical dot texture fades down the dark chapter; painted inputs also use short staggered rise or ink-fill animations.

**Transfer:**

- Link telemetry changes to the scene or meaningful scroll progress rather than running unrelated decorative counters.
- Preserve static, legible chapter compositions while using the scene controls to reveal additional working examples.
- Keep button and link transitions as short tonal changes, distinct from the richer illustration sequences.

**Unknown:**

- Complete scene timing, exact autoplay sequencing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Fluid section, solution, pricing and closing heading formulas are retained in their type recipes.
- Desktop composition uses a broad 1320px content area and fixed two-level header; no explicit width breakpoints are established.

**Transfer:**

- On narrow layouts, keep copy before the painted result and preserve one coherent scene instead of shrinking all floating UI into unreadable miniatures.
- Collapse proof and capability grids into fewer columns while retaining their rules and metadata alignment.
- Stack each question immediately above its answer when the two-column relationship becomes too narrow; keep its number attached to the question.
- Move a workflow's side index above its stages when the 220px spine cannot fit beside readable content.

**Unknown:**

- Mobile navigation treatment, actual breakpoint values, small-screen art masks and device-specific media scaling are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
