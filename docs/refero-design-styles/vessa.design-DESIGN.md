# Vessa — dithered working canvas

## Overview

A cool, lightly technical marketing style that feels like a designer's working document brought to life. Pale blue-grey paper, near-black grotesk type and electric blue halftone fields give practical product explanations an unusually tactile frame. Spacious editorial passages alternate with tightly constructed interface fragments and real examples; long-form identity documents have their own photographic or painterly worlds.

### Essentials

- The promise reads like a compact statement, not a billboard: centered Switzer 56px/1.02, weight 500, -0.045em tracking in a 704px headline area, with a 672px support line and 20px gaps.
- The first screen hands the argument to the product: a short centered opening sits above a 1376px-wide dithered blue stage, with a 45px tab strip and an inset live-looking demonstration continuing below the fold.
- The page wears its construction lines: 1px grey dashed rails sit 32px from the desktop edges, using 9px marks and 6px spaces; section and column divisions echo them, with small blue square registration points at important intersections.
- Blue is concentrated into demonstrations and the final invitation, not spread across every card: #eef0f3 dominates the reading surface, #101216 carries headings, and #1f2de6 forms dense stippled surrounds with pale cutouts.
- Actions are compact rounded rectangles, not oversized pills: the main action is 40px high with an approximately 8px corner and 14px medium text; the closing blue stage reverses it to a light button.
- Product fragments are treated as small working artifacts: pale panels, 1px edges, 8–12px corners, visible token chips, connectors and tabs, with very little shadow. When a finished interface is unavailable, construct one truthful input-to-output diagram instead.
- The closing invitation is a graphic event: a 424px-high blue dither field surrounds a clear central blue island with 44px/1.05 white type and one light action, followed immediately by a ruled, multi-column footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#1f2de6` | `--color-accent` | accent, action, link, background | Main actions, graphic stages, selected details and occasional concluding sentences. |
| Blue proof wash | `#d9ddf2` | `--color-proof-wash` | surface | Visible blue wash for a tiny numeric proof capsule; blue at 0.1 alpha over cool paper. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ink | `#101216` | `--color-ink` | text, surface | Headlines, strong labels and dark graphic elements. |
| Graphite | `#3f434b` | `--color-body` | text | Paragraphs and ordinary links. |
| Muted slate | `#626873` | `--color-muted` | text | Secondary captions, closed questions and inactive controls. |
| Construction grey | `#a2a3a5` | `--color-guide` | border | Dashed rails and more visible media outlines. |
| Input edge | `#b2b8c2` | `--color-input-edge` | border | Email field outline. |
| Fine edge | `#d3d7de` | `--color-edge` | border | Fine panel and gallery cell borders. |
| Control bed | `#e5e8ec` | `--color-control` | surface | Tab tracks and small neutral control backgrounds. |
| Cool paper | `#eef0f3` | `--color-canvas` | background | Default marketing canvas and pale cutouts in the blue art. |
| Panel paper | `#f5f6f8` | `--color-panel` | surface | Inset demonstration and media frames. |
| Input paper | `#fcfdfe` | `--color-input` | surface | Input fields and selected tab faces. |
| White | `#ffffff` | `--color-white` | text, surface | Text over blue or dark media and reversed actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| literary identity documents | Terracotta | `#a03d2a` | `--color-terracotta` | accent, surface | The single assertive accent of the literary identity system. |
| the colored navigation state | Translucent periwinkle | `#acc2f5` | `--color-header-tint` | surface | Colored translucent navigation state, using the blue-tinted fill near 0.98 alpha. |
| literary identity documents | Warm ink | `#1e1a16` | `--color-warm-ink` | text, surface | Display text and dark swatches in the literary document. |
| photographic identity documents | Document graphite | `#505255` | `--color-document-body` | text | Paragraphs in the photographic identity system. |
| literary identity documents | Warm grey | `#5a5755` | `--color-warm-body` | text | Literary document paragraphs. |
| literary identity documents | Literary document paper | `#f4f5f8` | `--color-document-warm` | background | Canvas for the mono-and-serif identity-document variant. |
| photographic identity documents | Cool document paper | `#f4f6f8` | `--color-document-cool` | background | Canvas for the photographic identity-document variant. |

## Typography

- **Switzer** — All default marketing type and photographic-document headlines. Contemporary neo-grotesk with open lowercase forms; medium headlines feel compact rather than heavy. If unavailable, use **Inter**. Use weights 400–600 and retain tight display tracking. Font stack: "Switzer", "Inter", ui-sans-serif, system-ui, sans-serif.
- **Space Mono** (only for literary identity documents) — Headlines, navigation brand names and specimen displays. Wide, characterful monospace that contrasts with literary body text. Font stack: "Space Mono", ui-monospace, monospace.
- **EB Garamond** (only for literary identity documents) — Paragraphs, captions, navigation and download links. Fine old-style serif; turns a technical system into an editorial document. Font stack: "EB Garamond", Georgia, serif.
- **General Sans** (only for photographic identity documents) — Body, navigation and captions. Neutral sans with a softer reading texture than the tightly set display face. If unavailable, use **Inter**. Font stack: "General Sans", "Inter", ui-sans-serif, system-ui, sans-serif.
- **Sentient** (only for photographic identity type specimens) — A secondary accent serif shown within the type system, not a marketing headline face. Sturdy editorial serif used in a contained specimen role. If unavailable, use **Lora**. Font stack: "Sentient", "Lora", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Switzer | 500 | 56px | 1.02 | -0.045em | size clamp(32px, 5vw, 56px) | Default centered opening promise. |
| heading | Switzer | 500 | 48px | 1.02 | -0.03em | size clamp(30.4px, 4.2vw, 48px) | Primary capability section heading. |
| commercial-heading | Switzer | 500 | 46px | 1.05 | -0.035em | size clamp(30px, 3.4vw, 46px) | Pricing and objection-handling headings. |
| closing-heading | Switzer | 500 | 44px | 1.05 | -0.035em | size clamp(28px, 3.5vw, 44px) | Closing invitation and broad capability statement. |
| proof-heading | Switzer | 500 | 40px | 1.05 | -0.035em | size clamp(25.6px, 3.2vw, 40px) | Centered demonstration and example introductions. |
| editorial-passage | Switzer | 400 | 32px | 1.45 | -0.022em | fixed | Centered long-form argument in a narrow column. |
| question | Switzer | 500 | 28px | 1.15 | -0.025em | size clamp(19px, 2vw, 28px) | Accordion questions. |
| feature-title | Switzer | 500 | 19px | 1.35 | -0.015em | size clamp(17px, 1.4vw, 19px) | Short captions leading feature explanations. |
| lead | Switzer | 400 | 18px | 1.55 | normal | size clamp(16px, 1.5vw, 18px) | Opening support paragraph. |
| body | Switzer | 400 | 15px | 1.6 | normal | fixed | Reading text in answers and compact explanations. |
| small | Switzer | 400 | 14px | 1.5 | normal | fixed | Footer text and compact descriptive labels. |
| control-label | Switzer | 500 | 14px | 1.5 | normal | fixed | Navigation and tabs. |
| action | Switzer | 500 | 14px | 1.4 | normal | fixed | Primary conversion action. |
| text-link | Switzer | 400 | 14px | 1.6 | normal | fixed | Underlined explanatory links. |
| proof-number | Switzer | 500 | 13px | 1.5 | normal | fixed | Small proof capsule. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| photographic identity documents | document-heading | Switzer | 500 | 80px | 0.98 | -0.045em | size clamp(38.4px, 7 * 1vw, 80px) | Major chapter title. |
| literary identity documents | literary-heading | Space Mono | 500 | 80px | 0.98 | -0.045em | size clamp(38.4px, 7 * 1vw, 80px) | Major chapter title. |
| photographic identity documents | document-cover | Switzer | 500 | 78.4px | 0.92 | -0.05em | fixed | White cover title at the lower left of an image. |
| literary identity documents | literary-cover | Space Mono | 500 | 78.4px | 0.92 | -0.05em | fixed | White cover title over painting. |
| example collections | collection-display | Switzer | 500 | 64px | 1.02 | -0.03em | size clamp(36px, 5.5vw, 64px) | Left-aligned opening title. |
| pricing sections | price | Switzer | 500 | 56px | 1 | -0.04em | size clamp(40px, 4.5vw, 56px) | Price displayed as the dominant element of an otherwise unboxed column. |
| example collections | collection-title | Switzer | 500 | 26px | 1.1 | -0.02em | fixed | Linked title beneath a preview. |
| photographic identity documents | document-body | General Sans | 400 | 16px | 1.6 | normal | fixed | Readable document paragraphs. |
| literary identity documents | literary-body | EB Garamond | 400 | 16px | 1.6 | normal | fixed | Document reading copy. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headlines are medium, not bold. Negative tracking ranges from -0.03em to -0.045em for marketing headings while small reading copy stays at normal tracking.
- Use the centered 56px opening as the default. The 64px collection title and 78.4px image-cover titles belong to their own page types rather than forming a larger universal hero scale.
- Keep body text looser than headlines: 1.55–1.6 line height for explanations against 1.02–1.05 for large marketing type.
- The literary document pairs mono display with serif text; the photographic document pairs grotesk display with neutral sans text. Do not blend these into the default marketing family.

## Layout

**Density:** Airy at section scale, compact at control scale; long pale intervals surround modest type and tightly grouped artifacts.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Inline control gaps and proof-label spacing. | fixed |
| 12px | Footer item rhythm and tight groups. | fixed |
| 20px | Opening headline, support and action separation. | fixed |
| 24px | Collection media-to-copy gap. | clamp(16px, 1.8vw, 24px) |
| 31.7px | Collection-cell inset. | clamp(20px, 2.2vw, 32px) |
| 40px | Main stage inset and paired-preview gutter. | fixed |
| 44.8px | Paragraph separation in the centered editorial passage. | fixed |
| 57.6px | Text inset inside the outer construction rails. | fixed |
| 72px | Opening top padding; document side inset. | fixed |
| 136px | Default breathing room before major marketing sections. | clamp(80px, 11vw, 136px) |
| 144px | Capability demonstration vertical padding. | fixed |
| 160px | Editorial argument vertical padding. | fixed |

### Containers and grids

- **outer rails**: max width 1376px · side padding 32px. Full desktop working canvas bounded by dashed vertical guides.
- **text and examples**: max width 1261px · side padding 57.6px. Content inset within the outer rails; use for paired previews, pricing and footer content.
- **hero copy**: max width 736px · side padding 16px. Centered opening stack; headline occupies 704px, paragraph 672px.
- **editorial column**: max width 832px. Centered argument with large paragraph text.
- **capability grid**: 2 columns · gap 0px. Open, ruled feature cells; a wide first cell can span both columns.
- **preview pair**: 2 columns · gap 40px. Equal media cards under a centered proof heading.
- **pricing columns** (only for pricing sections): 3 columns · gap 0px. Equal unboxed columns divided by dashed guides.
- **collection grid** (only for example collections): 2 columns · gap 0px. Equal cells joined by fine rules rather than floating cards.
- **document shell** (only for identity documents): 2 columns · gap 0px. 320px sticky contents rail beside a 1120px reading region at desktop; reading region has 72px side padding and 976px usable width.
- **application grid** (only for identity documents): 3 columns · gap 29px. Three columns of approximately 306px media tiles with captions beneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action and navigation | 8px |
|  | media frames | 10px |
|  | tab track and major preview | 12px |
|  | proof capsule | 9999px (pill) |
| identity documents | document application tiles | 14px |
| identity documents | document moodboard | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| input edge lift | `0px 1px 2px 0px rgba(0, 0, 0, 0.05)` | Only a slight lift on the email input; other marketing panels rely on outlines. |

### Surfaces

#### Working canvas · level 0

**Use:** Default marketing surface.

**CSS:** `background: #eef0f3; color: #101216`

**Observed:** The same paper continues through editorial sections, feature cells and footer.

**Transfer:** Keep the reading ground continuous; separate material by guides, not by alternating generic white cards.

#### Dither stage · level 0

**Use:** Graphic surround for the main product demonstration and final invitation.

**CSS:** `background-color: #1f2de6; position: relative; overflow: hidden`

**Observed:** Pale ordered dots and cross-like clusters form broad irregular cloudy regions over solid electric blue. The central subject remains clean.

**Transfer:** Use the Dither field imagery recipe and reserve an unpatterned area behind text.

#### Artifact panel · level 1

**Use:** Product fragments and paired media frames.

**CSS:** `background: #f5f6f8; border: 1px solid #a2a3a5; border-radius: 10px; overflow: hidden; box-shadow: none`

**Observed:** Panels are shallow and flat, not floating glass; some fragments soften toward an edge to suggest continuation.

**Transfer:** Show a small functional fragment with a clear input or value, not a fully populated dashboard.

#### Construction rails

**Use:** Page edges and structural divisions.

**CSS:** `background-image: repeating-linear-gradient(#a2a3a5 0px, #a2a3a5 9px, rgba(0, 0, 0, 0) 9px, rgba(0, 0, 0, 0) 15px); width: 1px`

**Observed:** Vertical rails fade near the page ends; horizontal rules use the same pattern rotated to the right.

**Transfer:** Overlay noninteractive guides on the common grid. Put 4px blue square registration points only at selected joins.

#### Colored navigation glass · level 2

**Only for:** the colored navigation state

**Use:** A tint state of the compact fixed header.

**CSS:** `background: rgba(171, 193, 245, 0.982); backdrop-filter: blur(10px); border-radius: 8px`

**Observed:** The opening navigation visually blends with the canvas; the colored state adds periwinkle rather than a black glass bar.

**Transfer:** Keep the initial header visually light and let the colored state remain subordinate to product art.

#### Photographic document canvas · level 0

**Only for:** photographic identity documents

**Use:** Long-form reading system.

**CSS:** `background: #f4f6f8; color: #101216`

#### Literary document canvas · level 0

**Only for:** literary identity documents

**Use:** Mono-and-serif reading system.

**CSS:** `background: #f4f5f8; color: #1e1a16`

## Components

### Primary button

**Use:** Single main conversion action.

**CSS:** `background: #1f2de6; color: #ffffff; height: 40px; border-radius: 8px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Switzer 500 · 14px/1.4

**Observed:** A short label sits centered in a modest rectangular action. The closing stage reverses to a light face with blue text.

**Transfer:** Choose a brief verb-led action; allow width to follow the label rather than forcing full width.

### Marketing navigation

**Use:** Compact fixed top navigation.

**CSS:** `height: 56px; display: grid; grid-template-columns: 1fr auto 1fr; gap: 16px; padding: 8px 8px 8px 16px; border-radius: 8px`

**Text style:** `control-label` — Switzer 500 · 14px/1.5

**Observed:** Small brand at left, four central links spaced 28px apart, sign-in and main action at right. The fixed header has 12px top inset and stays visually much narrower than the outer rails.

**States:** Declared: hover link color #101216; header transform transition .8s cubic-bezier(.3, .9, .1, 1).

### Demonstration tabs

**Use:** Switch sections or steps within a product demonstration.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 4px; background: #e5e8ec; border-radius: 12px`

**Text style:** `control-label` — Switzer 500 · 14px/1.5

**Observed:** Neutral track with a pale 8px-radius selection face; individual labels use 8px 14px padding and a 37px control height. A separate circular next-arrow control sits to the right.

**States:** Declared: hover inactive label color #3f434b; focus-visible outline 2px solid #1f2de6 with 2px offset.

**Transfer:** Use a short coherent sequence of real product steps, keeping the active state a sliding pale inset rather than a saturated pill.

### Numeric proof capsule

**Use:** Small supporting proof below the opening action.

**CSS:** `background: rgba(31, 45, 230, 0.1); color: #101216; padding: 3px 10px; border-radius: 9999px`

**Text style:** `proof-number` — Switzer 500 · 13px/1.5

**Observed:** The number is encapsulated; its descriptive phrase remains outside, separated by 8px.

**Transfer:** Use one verifiable count, not a row of oversized statistics.

### Preview frame

**Use:** Paired live-example previews.

**CSS:** `background: #f5f6f8; border: 1px solid #a2a3a5; border-radius: 10px; overflow: hidden`

**Observed:** A wide approximately 610px by 383px media frame is followed by a short title and one descriptive sentence, all on the page canvas.

**Transfer:** Give each preview its own visual identity while retaining identical frame proportions.

### Explanatory link

**Use:** Supporting detail links within answers.

**CSS:** `color: #1f2de6; border-bottom: 1px solid rgba(31, 45, 230, 0.3)`

**Text style:** `text-link` — Switzer 400 · 14px/1.6

**Observed:** The line sits under the words alone rather than spanning the paragraph.

**States:** Declared: hover border-bottom-color #1f2de6.

### Question row

**Use:** Objection-handling accordion.

**CSS:** `position: relative; padding: 21.6px 0px`

**Text style:** `question` — Switzer 500 · 28px/1.15 · tracking -0.025em

**Observed:** Question and small plus or close glyph share a baseline across a 772px-wide list. Dashed separators define rows. The open answer is a 424px-wide column with 36px bottom space; a separate contact prompt sits to the right. Closed titles are muted; the open one is ink.

**Transfer:** Keep answers plain and candid; use the body recipe and explanatory links, not nested cards.

### Email input

**Use:** Small update subscription form.

**CSS:** `background: #fcfdfe; border: 1px solid #b2b8c2; border-radius: 8px; height: 36px; padding: 4px 12px; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05)`

**Observed:** A 345px input and 127px action share a compact row with an 8px gap. Short proof and a restrained explanatory paragraph sit below.

**Transfer:** Keep the form secondary to the product narrative.

### Ruled footer

**Use:** Marketing page ending after the graphic invitation.

**CSS:** `display: grid; grid-template-columns: 1.4fr repeat(5, minmax(0px, 1fr)); gap: 0px; background: #eef0f3`

**Text style:** `small` — Switzer 400 · 14px/1.5

**Observed:** A wider brand-and-description cell precedes five narrow link columns, with vertical dashed rules. The upper grid is 314px tall, then a low legal strip; content starts with 44px top space.

**Transfer:** Group the new product's links by user purpose; keep the footer as an extension of the construction grid.

### Collection cell

**Only for:** example collections

**Use:** Preview-led editorial listing.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 31.7px; border-right: 1px solid #d3d7de; border-bottom: 1px solid #d3d7de`

**Text style:** `collection-title` — Switzer 500 · 26px/1.1 · tracking -0.02em

**Observed:** Wide 3:2 preview, linked title, two short explanatory paragraphs, then tiny palette chips and a type-system caption. Cells share rules, not rounded outer boxes.

**States:** Declared: hover title color #1f2de6.

**Transfer:** Describe what makes each example work, rather than giving every item the same promotional blurb.

## Imagery and graphics

### Dither field

**Use:** Signature graphic framing throughout marketing pages, including the main demonstration and closing invitation.

**Observed:** Electric blue with paper-colored dots, tiny crosshatches and irregular density waves. Dense pale patches open into solid blue pools; the image feels digitally screened, not grainy photographic noise.

**Transfer:** Retain this graphic device even for a text-led product. A simple deterministic halftone surround around a truthful diagram is the minimum equivalent.

**Build:** Create a canvas or SVG layer over #1f2de6. Sample a slow multi-wave or blurred-cloud density map on a 4px lattice; draw paper-colored 1–2px squares at ordered Bayer thresholds so dense areas form crosshatched clusters and sparse areas isolated dots. Vary density in broad diagonal swells across the width. Mask out the central content island and clip within the stage. Add a smaller, fading echo of the same field behind the top navigation.

### Working interface fragments

**Use:** Capability cells and explanatory diagrams.

**Observed:** Tiny pale windows show color swatches, type chips, password gates, token rows, rounded grey blocks and dotted connector lines. They are framed on the shared canvas, with selective blue emphasis and a lot of empty space around each useful detail.

**Transfer:** Represent the product's actual input, transformation and output. Keep a limited number of legible controls rather than drawing decorative faux analytics.

**Build:** Use 1px outlined panels with 10–12px corners. Arrange one input card and one output card on a pale backing; join them with thin dashed SVG curves. Use small neutral bars for secondary detail and one blue element to mark the meaningful result.

### Live-example media

**Use:** Paired proof cards and collection previews.

**Observed:** Wide views of finished identity websites keep their own colors, imagery and typography. A sports photograph and a classical painted landscape can coexist because the outer frames and captions are consistent.

**Transfer:** Show real outputs or faithful prototypes at a consistent ratio. Let their diversity prove the product's flexibility; do not recolor every example blue.

### Photographic cover and cloud

**Only for:** photographic identity documents

**Use:** Full-height opening cover and spatial moodboard.

**Observed:** The cover is dark, cinematic sports photography with a solitary athlete, directional light and extensive negative space. White branding sits above a lower-left title and small metadata columns. Later, fabric macros, tracks, portraits and action photographs float in a pale rounded cloud canvas; warm red-orange and cool blue photography stays inside the media.

**Transfer:** Choose a subject genuinely related to the new identity. Match the strong light direction, dark negative space and varied close-up-to-wide rhythm rather than borrowing the sport.

**Build:** Fill a 1120px by 900px cover using object-fit: cover. Overlay a top black-to-transparent gradient ending at 26% and a bottom transparent-to-black gradient starting at 58%; use alpha 0.34 at the top and 0.5 at the bottom. For the cloud, distribute mixed-aspect image rectangles with 10px corners across a 16px-radius pale canvas, allowing edge clipping and generous space between groups.

### Painted cover and cloud

**Only for:** literary identity documents

**Use:** Full-height cover and image-reference field.

**Observed:** Classical landscape painting depicts distant mountains, sea, ruins and human figures in subdued olive, stone, ochre and russet. The cover uses a wide panoramic composition; later reference paintings float at different sizes on pale grey with softly rounded corners.

**Transfer:** Select a coherent historic or illustrative world connected to the new identity. Preserve muted pigment, scenic depth and editorial framing, not the original subject matter.

**Build:** Use a landscape artwork as a full-cover image with the same top and bottom readability gradients as the photographic cover. Place varied landscape and portrait references in a spacious clipped cloud with 10px image corners and 16px outer corners.

### Application mockups

**Only for:** identity documents

**Use:** Demonstrate an identity across physical and digital contexts.

**Observed:** Three-column tiles combine signs on timber, concrete and brick; cards on fabric or stone; phones, browser details and social or presentation layouts. Directional daylight and realistic material shadows make the flat identity tangible. Each rounded tile has a small muted caption outside it.

**Transfer:** Choose relevant touchpoints for the new product. Use convincing material photography or simple frontal mockups with consistent light; retain the caption-under-image structure rather than placing text over every image.

### Icons

**Observed:** Utility icons are mostly 14–16px outlined SVGs with round caps and 1–1.5px strokes in ink or muted slate. Next-step arrows can sit in a 40px circular control; blue is used for the prominent arrow or play affordance.

**Transfer:** Use restrained line icons for navigation and interaction. Keep partner marks and product symbols confined to relevant diagrams rather than making a decorative icon library.

## Section recipes

How recurring sections are built.

### First screen: Promise above a working stage

**Observed:** On cool paper, a compact fixed navigation sits above a centered promise. The headline occupies roughly half the desktop width and wraps into two lines using display; 20px below it is lead text with a short stronger clause. A single 40px Primary button, a small reassurance line and Numeric proof capsule complete the stack. The headline begins after 72px of opening top space. The product stage begins around the middle of the first 900px view: first the blue Dither stage surround, then centered Demonstration tabs, then the top of a large inset example. Back to front: continuous paper, faint upper dither echo and construction rails, text/navigation, blue stage pattern, pale tab controls and media. The first 900px shows the full promise, support, action, proof and upper product media; the rest of the demonstration continues below.

**Transfer:** Give a different product one concrete outcome-led promise and a truthful example of the result. Without finished product media, create Working interface fragments that make input and output obvious. Example collections open with a left-aligned collection-display and preview grid; identity documents open with a full-height media cover beside their contents rail.

**Avoid:** Do not replace this with a full-screen photographic marketing hero, an enormous all-caps wordmark, or two competing hero buttons. Do not push all product evidence below the first screen.

**Text style:** `display` — Switzer 500 · 56px/1.02 · tracking -0.045em

### Editorial argument

**Observed:** An 832px centered text column uses editorial-passage with 44.8px paragraph breaks and 160px vertical padding. Several graphite paragraphs establish a concrete frustration; the concluding sentence changes to electric blue.

**Transfer:** Explain the human cost of the old workflow, then turn with one plain alternative. Keep this as a reading pause rather than a list of card-sized benefits.

**Text style:** `editorial-passage` — Switzer 400 · 32px/1.45 · tracking -0.022em

### Heading pair and step demonstration

**Observed:** A two-column heading row pairs a 48px heading with a smaller explanatory paragraph. About 44px below, a 627px-wide Dither stage diagram sits left while Demonstration tabs, a short subheading and support copy sit right. The section has 144px vertical padding.

**Transfer:** Use for one capability with a clear progression. Let the diagram carry the mechanism while the heading states the benefit.

**Text style:** `heading` — Switzer 500 · 48px/1.02 · tracking -0.03em

### Ruled capability field

**Observed:** A broad heading leads an open two-column grid on Working canvas. A full-width first cell can contain a connector diagram; following cells combine Working interface fragments above feature-title and short copy. Cells are approximately 688px wide and 491px tall, separated by dashed construction lines rather than card shells.

**Transfer:** Group related capabilities into a handful of meaningful cells. Keep one large diagram and vary the smaller fragments to avoid repetitive icon cards.

**Text style:** `feature-title` — Switzer 500 · 19px/1.35 · tracking -0.015em

### Demonstration and paired proof

**Observed:** A centered proof-heading introduces a large video panel backed by Dither stage, with a restrained dark overlay and circular play action. A related proof section uses Preview frame in two columns with 40px gutter, titles and one-line captions beneath.

**Transfer:** Show process and result as complementary forms of proof. The video can become an interactive walkthrough; paired outputs should remain directly comparable in size.

**Text style:** `proof-heading` — Switzer 500 · 40px/1.05 · tracking -0.035em

### Unboxed pricing

**Observed:** A left-aligned commercial-heading and support introduce three equal columns with no floating plan cards. Each has a small plan label, 56px price, 13px qualification line, short audience description and compact checked features. Dashed vertical rules do the grouping; a small blue dot singles out one option. A shared action sits beneath the columns.

**Transfer:** Make distinctions understandable through audience and inclusions, not large badges or oversized buttons on every tier.

**Text style:** `commercial-heading` — Switzer 500 · 46px/1.05 · tracking -0.035em

### Updates and objections

**Observed:** A modest centered subscription block uses Email input with a short heading and small proof text. A later left-aligned commercial-heading introduces Question row in a broad left column, with a narrow human contact prompt to its right.

**Transfer:** Use this as a low-pressure opportunity to stay connected followed by candid answers to practical doubts. The two blocks need not be adjacent.

**Text style:** `commercial-heading` — Switzer 500 · 46px/1.05 · tracking -0.035em

### Graphic closing invitation

**Observed:** A 1376px-wide, 424px-high Dither stage surrounds a solid blue central rectangular island. A centered white closing-heading wraps into two short lines, with a reversed Primary button underneath. Ruled footer begins immediately afterward, continuing the outer rails.

**Transfer:** Restate the new product's tangible next step in a compact sentence. Preserve the dither-to-solid contrast and the calm light action, wherever the closing invitation belongs.

**Text style:** `closing-heading` — Switzer 500 · 44px/1.05 · tracking -0.035em

### Editorial collection

**Observed:** A left-aligned collection-display occupies a 544px title width with explanatory text below; Collection cell entries begin beneath a top hairline and form a continuous two-column grid. The page ends with Graphic closing invitation and Ruled footer.

**Transfer:** Curate examples through the preview plus a specific editorial reading of each, not a wall of unexplained thumbnails.

**Text style:** `collection-display` — Switzer 500 · 64px/1.02 · tracking -0.03em

### Identity chapter system

**Observed:** A 320px sticky numbered contents rail stays separate from a 1120px document region. Chapters begin with tiny running metadata over a 1px rule, then a large chapter heading and short support. The interior width is 976px with 72px side padding. Logo chapters compare light, dark and clear-space panels; palette chapters use contiguous clickable swatches; type chapters use oversized lowercase specimens and specimen rules. Motion chapters show geometric exercises, small interface examples and editable-looking curve diagrams.

**Transfer:** Use for a detailed system or documentation page, not as the default landing-page shell. Choose either the photographic sans system or the literary mono-and-serif system, and keep that choice consistent.

### Reference cloud and usable ending

**Observed:** Identity chapters progress to spacious reference-image clouds and three-column Application mockups. The ending is utilitarian: an asset heading and download-all link, followed by groups of logo, type, color and image rows with small previews, format metadata and right-aligned download links. A 64px colophon ends with a fine rule, document name, end-of-document note and publishing credit; there is no marketing callout at this ending.

**Transfer:** For a system page, finish by letting readers take usable materials away. Keep this distinct from the graphic closing invitation used on marketing and collection pages.

## Page flow

**Storyline:** Concrete promise → visible mechanism → human reason to care → capabilities and real outputs → terms and practical doubts → decisive invitation or usable handoff.

### Product marketing and conversion

1. **Promise** — Centered outcome statement and compact action above the first product stage.
2. **Product demonstration** — Tabbed live-looking example within blue dither art.
3. **Problem framing** — Centered editorial passage with a blue turning sentence.
4. **Capability chapters** — Step demonstration and ruled cells combine explanations with functional artifacts.
5. **Proof** — Walkthrough, paired finished examples and external-reference previews.
6. **Terms and objections** — Unboxed pricing, small update form and question list.
7. **Closing call** — Dither-framed invitation followed by a structured ruled footer.

**Transfer:** Borrow the alternation between text, mechanism and output; choose the sequence appropriate to the new buying decision.

### Editorial collection of real outputs

1. **Orientation** — Left-aligned title and a brief account of what to look for.
2. **Proof collection** — Two-column preview cells with explanatory prose and system metadata.
3. **Closing call** — Shared dither invitation and ruled marketing footer.

**Transfer:** Let variety live inside the previews while the outer editorial grid stays consistent.

### Literary identity-system document

1. **Identity promise** — Panoramic painting cover, white mono title and small metadata beside a numbered rail.
2. **System explanation** — Introductory statement, logo comparisons, contiguous palette and mono/serif specimens.
3. **Behavior specification** — Geometric motion demonstrations, curves and concise voice examples.
4. **World and application** — Painted reference cloud followed by physical and digital mockups.
5. **Usable handoff** — Grouped asset rows and a small end-of-document colophon.

**Transfer:** Use a coherent illustrative world and a deliberate display/text contrast for an editorial system, with a practical rather than promotional ending.

### Photographic identity-system document

1. **Identity promise** — Cinematic photograph with lower-left white headline and metadata.
2. **System explanation** — Large sans statement, logo placement panels, palette mosaic and type specimens.
3. **Behavior specification** — Motion exercises and short declarative voice examples with do/don't comparisons.
4. **World and application** — Mixed-scale photographic cloud and three-column application tiles.
5. **Usable handoff** — Downloadable files by category followed by restrained colophon.

**Transfer:** Create a strong photographic world while keeping the shell, chapter rules and asset handoff disciplined.

## Writing

Direct, maker-to-maker and mildly dissatisfied with unnecessary work. Claims are explained through what the product does, what changes for the reader and what the terms actually are; confidence comes from specificity rather than hype.

**Do not copy:** Do not reuse brand names, logos, artwork, customer names, proprietary claims, signup counts, prices, guarantees or product-specific wording. Quotations illustrate voice only; write original copy for the new product.

- **Addressing the reader:** Address the reader as you and your. The product is named when explaining a mechanism; we appears for personal help and operational commitments.
- **Rhythm:** Sentence-case headlines are usually one compact statement. Supporting copy uses plain sentences with contractions, often naming a concrete inconvenience before explaining the alternative. Actions are short verb phrases; longer paragraphs are reserved for the argument and practical answers.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the result and add a human-use test rather than an abstract quality. | 6–10 words | “Animated brand guidelines your clients actually use.” |
| Capability heading | A subject performs one concrete action. | 5–8 words | “The AI writes your first draft.”<br>“Everything lives on one link.” |
| Commercial reassurance | Say exactly when payment happens and remove the ongoing concern. | One short sentence followed by practical detail | “You pay once per brand and nothing ever renews.” |
| Action | Verb, activity and a clear qualifier when relevant. | 2–4 words | “Start building free”<br>“Keep me posted” |
| Closing line | A concrete alternative to the old habit, phrased as a short invitation. | 5–8 words | “Hand over a link this time.” |
| Collection description | Explain one notable design choice and why it fits, in an editorial rather than celebratory voice. | Two or three brief paragraphs | “Movement is used to show a figure settling into place, never to introduce a page.” |
| Identity voice example | A short, self-contained statement suited to the individual identity; not a universal marketing slogan. | 4–10 words | “Churn rises in March. Two cohorts drive it.”<br>“Dries between intervals. That's the whole pitch.” |

**Words and phrasing to use:** actually; one link; build; send; edit; publish; real; the whole thing; no subscription; this time

**Avoid:** revolutionary; unleash; ultimate potential; seamless ecosystem; game-changing; grab yours before they're gone

**Rules:**

- Lead with a concrete benefit and let the explanation name the mechanism.
- Use exact, supportable facts for proof; keep qualifications close to the claim.
- Answer practical questions directly, including limits, ownership and what happens next.
- Let a short conversational turn end an argument; avoid turning every sentence into a slogan.
- For editorial collections, discuss a distinctive choice instead of repeating generic praise.

## Do's and Don'ts

### Do

- Keep the default opening centered at 56px and weight 500 with -0.045em tracking.
- Carry the 32px outer rails and 57.6px inner text inset through demonstrations, pricing and footer.
- Include a dither surround with a clean interior island; use the same visual language at more than one scale.
- Use 136px section lead-ins to let compact diagrams and copy breathe.
- Keep featured media at 10–12px corners and separate captions from the image.
- Make small proof a 13px numeric capsule rather than a giant metric wall.
- Keep pricing columns on the continuous paper surface with 56px figures and dashed dividers.
- End identity documents with asset access and a 64px colophon rather than the marketing footer.

### Don't

- Do not use heavy 700-weight default headlines; the marketing voice is carried by medium 500.
- Do not tint every capability cell blue; blue belongs to actions, focused details and graphic surrounds.
- Do not use blurred rainbow gradients as a substitute for the ordered halftone field.
- Do not give every panel a drop shadow; 1px edges supply almost all depth.
- Do not turn the 40px rectangular main action into a tall full-width pill.
- Do not place explanatory captions over media when the design gives them their own space below.
- Do not apply the literary mono-and-serif pair to ordinary marketing sections.
- Do not make the long-form contents rail part of a standard product landing page.

## Motion and responsive

### Motion

**Observed:**

- Declared header transform transition: .8s cubic-bezier(.3, .9, .1, 1); header fill transition: 0.2s.
- Declared action transitions include color 0.2s with border-color 0.2s, and clip-path 0.22s cubic-bezier(0.3, 0.9, 0.1, 1).
- Tabbed demonstrations and geometric motion studies are part of the visual language. The literary document describes slow settlement without bounce; the photographic document describes hard acceleration, late braking and complete stillness between moves.

**Transfer:**

- Make the demonstration itself explain behavior: show a tab changing a meaningful result or a fragment moving between functional states.
- Keep the two identity motion personalities scoped to their own systems; do not average slow literary settlement and decisive athletic movement into one marketing animation style.

**Unknown:**

- Exact sequencing, runtime durations of canvas art and scroll-linked behavior are unspecified.

### Responsive

**Observed:**

- Type and several spacing values use clamped viewport formulas.
- The desktop document shell has a 320px rail; the marketing demonstration nearly spans the viewport inside 32px gutters.

**Transfer:**

- Preserve the centered promise and visible start of the product stage when narrowing the page; let the specified clamped type scales reduce first.
- For narrow layouts, stack preview pairs and capability cells while retaining their structural rules; reduce the rail system to a manageable outer frame.
- For identity documents, replace the wide contents rail with a compact chapter control rather than squeezing the 976px content composition.

**Unknown:**

- Exact mobile layouts, navigation behavior and width breakpoints are unspecified; stacking guidance is an adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
