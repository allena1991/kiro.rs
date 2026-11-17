# Baseten — neon infrastructure atlas

## Overview

An airy technical style that makes invisible systems feel tangible through luminous isometric diagrams and an exposed drafting grid. White and pale sage dominate, with electric green and small pink accents, then a deep black directory at the end. Tight semibold grotesk headlines meet utilitarian mono labels; sparse diagrams alternate with denser capability matrices and practical commercial detail. It suits developer platforms, infrastructure products and complex services with a strong performance story.

### Essentials

- Headlines feel like compressed declarations: grotesk at 88px/80px, weight 600 and -0.02em tracking in the main opening; 64px/70px with -0.03em tracking for major statements.
- The opening is a system diagram beside a bold promise, not a dashboard billboard: a 500px-tall split stage within a 1296px container, approximately equal text and art halves, 32px text-stack gaps and 48px actions.
- The page exposes its construction grid: 1px dashed rules using #d9d9d9 in an 8px repeat cross section edges, column boundaries and text baselines. Keep these visible as a signature device.
- Actions resemble equipment controls: square black or white rectangles, 48px tall for conversion and 36px for supporting links, with uppercase Chivo Mono at 16px or 14px and a small right chevron.
- Color behaves like an energized signal inside a mostly white and #f5f8f4 environment: #19e76e powers diagram faces, selected headline strips and a 40px announcement bar; pink is a smaller counterpoint, while full black is reserved for the closing directory.
- Illustrations are schematic objects with depth: pale translucent cylinders, cubes and connector paths float directly on the canvas with tiny rectangular telemetry labels. Every new page needs an equivalent diagram; a simple SVG node-and-stack composition is the fallback.
- Pixel-like signal bands punctuate the grid and frame the final invitation: shallow rows of hard-edged green, pink and pale-sage blocks lead to a centered 64px closing line, then a tall black footer with dark dashed rules and a green status control.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric signal | `#19e76e` | `--color-green` | accent, background, action, text | Announcement bar, headline highlights, diagram accents, interaction outlines and status lettering. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal pink | `#ffa9fd` | `--color-pink` | accent, surface | Small counterpoint in schematic art and pixel bands; commercial callout strips on pricing pages. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Headlines, body, primary actions and the closing directory. |
| Dark drafting rule | `#4d4d4d` | `--color-dark-rule` | border | Dashed construction grid within the black directory. |
| Sage gray text | `#676e64` | `--color-muted` | text | Section labels and subdued commercial notes. |
| Sage label edge | `#909a8b` | `--color-tag-edge` | border | Fine rectangular section-label borders. |
| Directory gray | `#b3b3b3` | `--color-footer-muted` | text | Directory group labels and copyright on black. |
| Control edge | `#cccccc` | `--color-edge` | border, surface | Navigation bottom border, commercial controls and inactive carousel dots. |
| Drafting rule | `#d9d9d9` | `--color-rule` | border | Repeated dashed construction lines on light canvases. |
| Soft panel edge | `#e6e6e6` | `--color-subtle-edge` | border | Secondary-action outline and commercial-card borders. |
| Faint quote edge | `#f2f2f2` | `--color-faint-edge` | border | Visible result of black at 5% over white on quote cards. |
| Pale sage | `#f5f8f4` | `--color-sage` | background, surface | Capability bands, diagram stages and label backing. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page, cards, secondary actions and text on black. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dark status green | `#084621` | `--color-status-wash` | surface | Visible dark green of rgba(15,139,66,0.5) over the black footer; outlined in electric green. |

## Typography

- **NeueAlteGrotesk** — Headlines, paragraph copy, card titles and directory links. Compact contemporary grotesk with open counters, firm semibold headings and economical regular text. If unavailable, use **Inter**. Use 400 and 600; preserve the tight tracking and deliberate headline wrapping. Font stack: "NeueAlteGrotesk", "Inter", Arial, sans-serif.
- **chivoMono** — Actions, section labels, attribution lines and operational markings. Mechanical monospace, usually uppercase, without decorative code styling. OpenType features: "clig" 0, "liga" 0. If unavailable, use **Chivo Mono**. Font stack: "chivoMono", "Chivo Mono", monospace.
- **ui-sans-serif** — Navigation and some small utility or testimonial text. Neutral system sans subordinate to the main grotesk. Font stack: "ui-sans-serif", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | NeueAlteGrotesk | 600 | 88px | 80px | -0.02em | Default flagship opening headline, generally two compact lines. |
| heading-lg | NeueAlteGrotesk | 600 | 64px | 70px | -0.03em | Major section statements and closing invitation; also product and pricing opening headlines. |
| heading | NeueAlteGrotesk | 600 | 48px | 1.25 | -0.03em | Secondary section leads, highlighted feature statement and resource-band headings. |
| tile-heading | NeueAlteGrotesk | 600 | 24px | 1.25 | -0.02em | Illustrated feature-cell headings in the default marketing grid. |
| card-heading | NeueAlteGrotesk | 600 | 24px | 32px | -0.02em | Capability-card headings and accordion questions. |
| hero-support | NeueAlteGrotesk | 400 | 24px | 32px | -0.02em | Default opening description, two to three lines. |
| lead | NeueAlteGrotesk | 400 | 22px | 30px | normal | Centered section support and product-opening support. |
| body | NeueAlteGrotesk | 400 | 16px | 1.5 | normal | Main paragraphs, feature descriptions, tables and directory links. |
| eyebrow | chivoMono | 400 | 16px | 1 | normal, uppercase, features "clig" 0, "liga" 0 | Outlined equipment-like section labels. |
| action | chivoMono | 400 | 16px | 1.5 | -0.02em, uppercase, features "clig" 0, "liga" 0 | Large conversion-button labels. |
| directory-label | NeueAlteGrotesk | 400 | 16px | 1.5 | -0.02em, features "clig" 0, "liga" 0 | Muted grouping labels in the directory. |
| action-small | chivoMono | 400 | 14px | 18px | -0.02em, uppercase, features "clig" 0, "liga" 0 | Supporting actions, navigation actions, status and attribution. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-page testimonial bands | quote | NeueAlteGrotesk | 400 | 32px | 44px | -0.04em | Wide standalone customer quotations. |
| pricing pages | commercial-heading | NeueAlteGrotesk | 600 | 32px | 44px | -0.04em | Plan titles and rate-table section titles. |

**Notes:**

- Keep the display line height tighter than its font size; smaller section headings loosen to 70px and 60px to retain readable multi-line statements.
- Use weight 600 rather than an extra-bold substitute. Tighten section titles to -0.03em, while body copy returns to normal tracking.
- Reserve monospace for short operational strings, not paragraphs. Uppercase actions retain negative tracking rather than wide letterspacing.
- Use a flat green strip behind a selected phrase in a feature heading, with black text; do not turn the full headline into colored lettering.

## Layout

**Density:** Airy overall, with tightly organized cells: wide chapter breaks contrast with 12px–16px internal copy gaps.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps, compact utility groups and announcement vertical padding. |
| 12px | Default illustrated tile title-to-body spacing and large button icon gaps. |
| 16px | Container side padding, regular card content gaps and paired actions. |
| 24px | Grid gutters, small-card padding and label-to-section-heading gap. |
| 32px | Opening text-stack rhythm, final headline-to-action gap and pricing-card padding. |
| 40px | Large illustrated-cell inner padding and standalone quote padding. |
| 48px | Space before a wide demonstration and multi-column directory separation. |
| 56px | Resource-band top padding and centered-introduction bottom padding. |
| 64px | Common chapter top padding and separation below heading blocks. |
| 80px | Resource-band bottom padding and larger internal chapter separations. |
| 120px | Bottom breathing room for technical capability chapters. |
| 128px | Closing invitation top offset. |

### Containers and grids

- **container**: max width 1296px · 12 columns · gap 24px · side padding 16px. Centered desktop framework; at 1440px the outer container begins at 72px and content at 88px, giving 1264px of working width.
- **split-stage**: 2 columns · gap 24px. Opening text and diagram in roughly equal halves; also two-by-two illustrated capability cells.
- **capability-grid**: 3 columns · gap 24px. Three equal cells of approximately 405px at desktop. Exposed rules continue through the gutters.
- **heading-column**: max width 856px. Centered section heading with a narrower supporting paragraph.
- **faq-split**: 2 columns · gap 24px. Section title on the left and approximately 620px question stack on the right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Buttons and panels | 0px |
| pricing pages | Commercial toggles | 2px |
| product-page carousels | Carousel dots | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| product-page carousels | Selected carousel dot | `0px 0px 0px 2px #ffffff, 0px 0px 0px 3px #19e76e` | Concentric selection ring, not elevation. |

### Surfaces

#### Canvas · level 0

**Use:** Default page and open illustrated cells.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat and shadow-free; line work provides structure rather than depth.

**Transfer:** Let the illustration carry the luminosity while the page remains white.

#### Sage band · level 0

**Use:** Capability chapters, resource collections and product-diagram stages.

**CSS:** `background: #f5f8f4`

**Observed:** A very light green-neutral field spanning either the full page or the framed content width.

**Transfer:** Use for a chapter change without introducing a new color theme.

#### Drafting grid · level 1

**Use:** Horizontal dividers and exposed alignment guides.

**CSS:** `height: 1px; background-image: repeating-linear-gradient(to right, #d9d9d9 0px, #d9d9d9 50%, rgba(0,0,0,0) 0px, rgba(0,0,0,0)); background-size: 8px 1px`

**Observed:** Vertical counterparts use a 1px-wide strip and the same repeat along the vertical axis. Rules run beyond the immediate text cell and mark container edges.

**Transfer:** Align decorative rules to real section and column boundaries; keep them behind text.

#### Quote card · level 1

**Use:** Modular customer proof.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.05); padding: 24px; border-radius: 0px; box-shadow: none`

**Observed:** The card is barely distinct from the white canvas, embedded in the larger dashed grid.

**Transfer:** Use typography, logos and attribution rather than an elevated card treatment.

#### Black directory · level 0

**Use:** Full-width closing directory.

**CSS:** `background: #000000; color: #ffffff; padding-top: 52px`

**Observed:** A tall dark field with #4d4d4d dashed rules, muted group titles and large remaining breathing room below the link columns.

**Transfer:** Retain the substantial directory silhouette even when link inventories differ.

#### Commercial panel · level 1

**Only for:** pricing pages

**Use:** Plan comparison cards.

**CSS:** `background: #ffffff; border: 1px solid #e6e6e6; padding: 32px; border-radius: 0px; box-shadow: none`

**Observed:** White rectangular cards stand on a sage field, all with equal visual emphasis.

**Transfer:** Do not invent a floating or brightly filled recommended tier.

## Components

### Navigation

**Use:** Persistent global orientation.

**CSS:** `position: sticky; top: 0px; background: #ffffff; height: 87px; border-bottom: 1px dashed #cccccc; z-index: 9999`

**Text style:** `body` — NeueAlteGrotesk 400 · 16px/1.5

**Observed:** A compact mark anchors the left; small system-sans menu labels follow. Utility links and a white login plus black compact action sit on the right within the main container. Menu items use 7px 12px padding.

**Transfer:** Keep the broad white shell but the actual navigation row compact.

### Announcement bar

**Use:** One timely notice above navigation.

**CSS:** `background: #19e76e; color: #000000; padding: 8px 16px; min-height: 40px`

**Text style:** `body` — NeueAlteGrotesk 400 · 16px/1.5

**Observed:** Centered sentence with a short underlined uppercase mono link and a tiny chevron; visually separate from navigation.

**Transfer:** Use one relevant announcement rather than a stack of promotional messages.

### Primary button

**Use:** Opening and closing conversion.

**CSS:** `background: #000000; color: #ffffff; outline: 1px solid #000000; height: 48px; padding: 12px 16px; border-radius: 0px; display: inline-flex; align-items: center; justify-content: center; gap: 12px`

**Text style:** `action` — chivoMono 400 · 16px/1.5 · tracking -0.02em · uppercase

**Observed:** Content-width rectangle with a small right chevron. Black remains the default action fill, even on very pale green sections.

**States:** Declared: hover color rgb(0 0 0/1), outline-color #19e76e; focus-visible outline #000000 solid 2px, outline-offset 1px.

**Transfer:** Use one primary action per conversion group.

### Secondary button

**Use:** Human-assisted conversion or alternative route.

**CSS:** `background: #ffffff; color: #000000; outline: 1px solid #e6e6e6; height: 48px; padding: 12px 16px; border-radius: 0px; display: inline-flex; align-items: center; justify-content: center; gap: 12px`

**Text style:** `action` — chivoMono 400 · 16px/1.5 · tracking -0.02em · uppercase

**Observed:** Pairs with Primary button at a 16px gap. Product openings also use two white outlined actions instead of the black-and-white pair.

**States:** Declared: hover outline-color #000000; focus-visible outline #000000 solid 2px, outline-offset 1px.

### Compact action

**Use:** Card links, navigation actions and resource links.

**CSS:** `background: #ffffff; color: #000000; outline: 1px solid #e6e6e6; height: 36px; padding: 8px 16px; border-radius: 0px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action-small` — chivoMono 400 · 14px/18px · tracking -0.02em · uppercase

**Observed:** Same mechanical rectangle as the larger actions. A black-filled version is used for direct deployment and rate-table actions; white is the default explanatory link.

**States:** Declared: hover outline-color #000000 on white actions; focus-visible outline #000000 solid 2px, outline-offset 1px.

### Section tag

**Use:** Short chapter or resource classification.

**CSS:** `background: #f5f8f4; color: #676e64; border: 1px solid #909a8b; padding: 4px 8px; border-radius: 0px; display: inline-flex`

**Text style:** `eyebrow` — chivoMono 400 · 16px/1 · uppercase

**Observed:** A shallow outlined label centered above a section heading or pinned to the upper left of a feature or resource cell.

**Transfer:** Use terse category words, not promotional badges.

### Feature tile

**Use:** Explain a capability in a ruled modular grid.

**CSS:** `background: #ffffff; padding: 24px; display: flex; flex-direction: column; gap: 16px; border-radius: 0px`

**Text style:** `card-heading` — NeueAlteGrotesk 600 · 24px/32px · tracking -0.02em

**Observed:** Small line icon, heading and regular body copy; surrounding dashed rules, rather than a continuous solid card border, define the cell. Illustrated two-column variants place the copy at top, Compact action at upper right and a large schematic beneath.

**Transfer:** Use text-only cells for dense details and illustrated cells for a small set of broad differentiators.

### Testimonial card

**Use:** Evidence integrated into the page grid.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.05); padding: 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `body` — NeueAlteGrotesk 400 · 16px/1.5

**Observed:** Customer logo first, quote second, then a small circular portrait beside uppercase mono name and role. A large heading can occupy two cells of an otherwise three-column proof mosaic.

**Transfer:** Keep quote length short enough to preserve the modular grid.

### System status

**Use:** Operational reassurance at the base of the directory.

**CSS:** `background: rgba(15,139,66,0.5); color: #19e76e; outline: 1px solid #19e76e; padding: 4px 8px; display: inline-flex; align-items: center; gap: 8px; border-radius: 0px`

**Text style:** `action-small` — chivoMono 400 · 14px/18px · tracking -0.02em · uppercase

**Observed:** A small green status dot precedes the text. The control sits at lower left, opposite copyright and compliance marks.

**States:** Declared: hover background-color #19e76e and text changes to #000000; focus-visible outline #000000 solid 2px, outline-offset 1px.

**Transfer:** Only display live operational status when the product has a truthful equivalent.

### Plan card

**Only for:** pricing pages

**Use:** Compare service levels.

**CSS:** `background: #ffffff; border: 1px solid #e6e6e6; padding: 32px; border-radius: 0px`

**Text style:** `commercial-heading` — NeueAlteGrotesk 600 · 32px/44px · tracking -0.04em

**Observed:** Three equal-height columns: plan name, brief positioning, checked inclusions, then bottom-aligned deployment tags, muted price note and black Compact action. Small green and pink outlined deployment tags are commercial variants, not global labels.

**Transfer:** Align bottom conversion controls across tiers, allowing whitespace after unequal feature lists.

### Rate table

**Only for:** pricing pages

**Use:** Transparent usage-based detail.

**CSS:** `background: #f5f8f4; color: #000000; border-radius: 0px`

**Text style:** `body` — NeueAlteGrotesk 400 · 16px/1.5

**Observed:** A title-and-description header sits above approximately 68px rows, separated by dashed guides; labels align left, numeric columns remain restrained, black Compact actions sit at right. Minute/hour controls have 2px corners and 1px gray borders. A short pink strip marks volume availability.

**Transfer:** Choose columns from the new billing model and keep units explicit.

### FAQ row

**Only for:** pricing and product pages

**Use:** Handle specific adoption objections.

**CSS:** `min-height: 80px; display: flex; align-items: center; justify-content: space-between; border-bottom: 1px dashed #d9d9d9`

**Text style:** `card-heading` — NeueAlteGrotesk 600 · 24px/32px · tracking -0.02em

**Observed:** A single-line or wrapped question with a small chevron at the far right. Rows stack in the right half beside a left-aligned section heading; no separate rounded cards.

**Transfer:** Keep the split composition and use real product objections; do not imply an unverified expansion animation.

## Imagery and graphics

### Luminous system schematics

**Use:** Required signature diagram in the opening and selected broad capability cells.

**Observed:** Isometric cubes, cylindrical stacks and rounded plates float against white or sage without a bounding image card. Green faces and pale translucent layers dominate, with occasional pink plates, mint hairline outlines, dashed connectors and tiny rectangular mono labels. The opening illustration occupies roughly half the content width; feature illustrations occupy most of the area beneath their copy.

**Transfer:** Turn the new product's inputs, processing layers and outputs into a small connected model. Minimum acceptable version is a clean SVG with three dimensional nodes, restrained colored faces and explanatory connectors rather than a generic application window.

**Build:** Use SVG polygon cubes with white top faces and electric-green side faces at different opacities; stack three elliptical discs with pale green fills and thin green strokes. Arrange them on isometric diagonals, connect centers with 1px green dashed paths, and add small pale rectangular labels with black mono text. Place a few small diamond particles in green and pink around the assembly. Duplicate selected outlines at low opacity to suggest translucent layers; avoid heavy cast shadows.

### Signal-block ribbons

**Use:** Required graphic punctuation around chapter changes or the final invitation.

**Observed:** Shallow full-width bands of horizontal grid rows contain scattered hard-edged rectangular cells in green, pink, white and pale sage. Some ribbons are sparse; others form clustered runs. They remain secondary to the surrounding text.

**Transfer:** Generate a fresh arrangement from the same small palette; use the device at meaningful pauses without requiring a fixed section sequence.

**Build:** Create an SVG strip with several 16px–32px-high horizontal lanes. Draw 1px dashed gray boundaries and sparse rectangular runs aligned to lane edges, varying widths from narrow slivers to broad spans. Use #19e76e for energized blocks, #ffa9fd as a smaller counterpoint and #f5f8f4 for quiet fills. Keep most of the strip white; extend beyond the content container and clip at viewport edges.

### Network hemisphere

**Use:** Large-scale reach or distributed-system explanation.

**Observed:** A pale hemisphere of tiny typographic marks sits inside a large dashed circular outline. Small green cubes hover over it, linked by fine right-angled green paths and compact location labels. White space around the sphere keeps the drawing light.

**Transfer:** Use the same diagram logic for a distributed product, or replace geography with a connected process topology when reach is not relevant.

**Build:** Clip low-opacity mono glyphs to a circular or hemispherical SVG mask; add a 1px dashed circumference. Distribute four simple isometric cube nodes, join them with thin rounded orthogonal paths, and attach tiny white bordered labels. Keep the background almost white and nodes saturated.

### Monochrome proof marks

**Use:** Opening social proof and quote attribution.

**Observed:** Black customer wordmarks occupy evenly sized grid cells; the default proof wall is five columns by three rows. Product variants use a short horizontal logo strip on sage, continuing beyond viewport edges.

**Transfer:** Use authorized relevant proof marks at consistent optical size, preserving their own proportions.

### Abstract research thumbnails

**Only for:** editorial resource carousels

**Use:** Three-up article collections.

**Observed:** Wide 405px by 212px rectangular images show soft liquid swirls, translucent pink folds or green light streaks. They are much more chromatic than the main canvas, with no rounded corners and no text overlaid.

**Transfer:** Use abstract material thumbnails rather than unrelated stock photos. Maintain pale luminous backgrounds with concentrated green or pink detail.

**Build:** Make a roughly 1.9:1 SVG or raster field with broad pale-sage and white areas. Layer curving green or pink ribbons at several opacities, blur the broad underlayer, and retain one or two sharper flowing edges. Vary direction across cards while keeping the palette related.

### Icons

**Observed:** Small outline chevrons in actions are 14px–16px with 2px round strokes. Capability icons are approximately 20px with 1.5px–2px black strokes. Social marks are 24px solid icons; the status dot is 8px green.

**Transfer:** Choose simple geometric line icons that read as technical markings. Avoid colorful icon tiles and oversized illustrative pictograms.

## Section recipes

How recurring sections are built.

### First screen: Split schematic opening

**Observed:** A 40px green Announcement bar and 87px white Navigation precede a 500px white stage. The 1296px container splits into approximately equal text and diagram halves. Behind everything, Drafting grid rules mark the content edges and text-stack divisions. The left headline uses display, filling most of its half in two tightly stacked lines; the support paragraph follows after 32px and paired Primary button and Secondary button after another 32px. The diagram floats in the right half, similar in overall height to the text stack, without an image frame. Within the first 900px, the headline, support, both actions, full system object and most of the ruled logo wall are visible; the next major chapter falls below the fold.

**Transfer:** For a different product, articulate one broad promise and diagram a meaningful input-process-output relationship. Without polished artwork, use the SVG schematic recipe. Product-detail openings reduce the headline to heading-lg, add a left-aligned Section tag and use a more focused diagram; commercial pages use a centered heading-lg, support and actions above a shallow logo strip rather than the split art stage.

**Avoid:** Do not use a full-bleed dark hero, a centered dashboard mockup, a giant mono text block or a gradient-filled headline in place of the split schematic composition.

**Text style:** `display` — NeueAlteGrotesk 600 · 88px/80px · tracking -0.02em

### Centered chapter introduction

**Observed:** Section tag sits 24px above a centered heading, usually constrained to 856px. Main statements use heading-lg; denser product chapters use heading. Support uses lead beneath it, with 64px chapter top padding and 56px–64px separation before the next content grid.

**Transfer:** State a fresh outcome or chapter argument rather than repeating the opening promise.

**Text style:** `heading-lg` — NeueAlteGrotesk 600 · 64px/70px · tracking -0.03em

### Highlighted product stage

**Observed:** A Sage band inside the container pairs a 48px heading and short description on the left with Luminous system schematics on the right. One phrase is backed by a solid green strip. Primary and explanatory compact actions sit below copy, followed by a three-column row of related offerings.

**Transfer:** Use the highlighted phrase to spotlight a differentiating benefit, and let the following modules explain alternative ways into the product.

**Text style:** `heading` — NeueAlteGrotesk 600 · 48px/1.25 · tracking -0.03em

### Illustrated capability matrix

**Observed:** Two columns of large white ruled cells place 24px tile-heading copy at the upper left, Compact action at upper right, and substantial schematics below. Other chapters use three columns of smaller Feature tiles with 16px body copy and 24px gutters.

**Transfer:** Use the large illustrated matrix for a few conceptual benefits, then the smaller text matrix for detailed capabilities.

**Text style:** `tile-heading` — NeueAlteGrotesk 600 · 24px/1.25 · tracking -0.02em

### Wide topology demonstration

**Observed:** A left-aligned heading-lg and short support paragraph lead a broad Network hemisphere. A Compact action aligns at the upper right. Below the illustration, two side-by-side explanations compare delivery choices, one backed in sage.

**Transfer:** Explain scale, collaboration or multiple operating modes using one spatial diagram followed by a clear comparison.

### Modular customer proof

**Observed:** A three-column grid mixes Testimonial cards with a two-cell headline and a small See all action. Logos head the quotes; portraits and mono attributions close them. Product variants use a single wide quote with quote typography, 40px internal padding and generous vertical space; training-oriented variants add carousel arrows and centered dots.

**Transfer:** Choose either a proof mosaic for breadth or a standalone quote for depth, using the same flat ruled geometry.

**Text style:** `quote` — NeueAlteGrotesk 400 · 32px/44px · tracking -0.04em

### Resource band

**Observed:** Sage band with a left-aligned 48px title and right-aligned Compact action, followed by three ruled resource cells. Each has a tag, short title, body and small action. Editorial carousel variants add Abstract research thumbnails, edge-aligned arrow controls and centered 10px dots with a green selection ring.

**Transfer:** Offer useful next steps rather than a decorative content carousel. Apply the thumbnail variant only to editorial resources.

**Text style:** `heading` — NeueAlteGrotesk 600 · 48px/1.25 · tracking -0.03em

### Signal-framed closing invitation

**Observed:** Signal-block ribbons frame a white centered invitation approximately 443px tall. The heading-lg statement begins after 128px of top space; actions sit 32px below. The usual pair offers direct entry and an engineering conversation; early-access variants use a single black action. This gives way to Black directory, not another promotional panel.

**Transfer:** Close with a direct next step appropriate to product maturity, while preserving the bright grid punctuation and black directory contrast.

**Text style:** `heading-lg` — NeueAlteGrotesk 600 · 64px/70px · tracking -0.03em

### Deep closing directory

**Observed:** Black directory spans 1180px in the desktop composition, with its grid inset beneath 52px top padding. A brand/social block sits left of dense grouped link columns, with white 16px links, muted directory-label headings and 40px column gaps. At the bottom, System status sits left and copyright plus compliance marks right, followed by substantial dark breathing space.

**Transfer:** Group the new site's destinations by reader task and retain the dark, diagrammed end-state. Compliance or status content must reflect the new product's real capabilities.

**Text style:** `directory-label` — NeueAlteGrotesk 400 · 16px/1.5 · tracking -0.02em

### Commercial comparison

**Only for:** pricing pages

**Observed:** Centered opening and logo strip lead into three Plan cards on Sage band. A separate centered introduction precedes long Rate tables; narrow units and minute/hour controls remain near the section headers. Pink callout strips occupy only the width of their short text.

**Transfer:** Keep plan comparison and unit rates as distinct reading tasks; let the table extend naturally rather than hiding costs behind oversized cards.

**Text style:** `commercial-heading` — NeueAlteGrotesk 600 · 32px/44px · tracking -0.04em

### Objection split

**Only for:** pricing and product pages

**Observed:** A 48px left heading with optional Compact action faces a right stack of FAQ rows. Dashed rules define the split and row boundaries, and substantial empty space beneath the left title balances the question stack.

**Transfer:** Use concise practical objections; preserve the asymmetric reading rhythm rather than centering everything.

**Text style:** `heading` — NeueAlteGrotesk 600 · 48px/1.25 · tracking -0.03em

## Page flow

**Storyline:** Broad promise → tangible system explanation → proof → capability chapters → practical decision support → direct invitation → operational directory.

### Broad platform or flagship landing page

1. **Promise** — Split schematic opening and ruled proof-mark wall.
2. **Product orientation** — Centered chapter lead and highlighted product stage with related offering modules.
3. **Capability chapters** — Illustrated two-column matrix, wide topology diagram and compact three-column use-case grid.
4. **Social proof** — Customer quote mosaic with a heading embedded in the grid.
5. **Closing call** — Signal-framed paired actions and deep black directory.

**Transfer:** Start with an expansive outcome, then progressively translate it into tangible mechanisms and credible adoption proof.

### Commercial evaluation page

1. **Promise** — Centered value-led headline, short support and paired actions.
2. **Pricing** — Logo strip, equal-weight plan cards and separate usage-rate tables.
3. **Objection handling** — Split FAQ with practical purchasing questions.
4. **Closing call** — Shared signal-framed invitation and black directory.

**Transfer:** Lead with affordability or growth logic, then provide explicit comparison and rates without replacing the brand's sparse grid.

### Technical capability landing page

1. **Promise** — Tagged split opening with focused schematic.
2. **Social proof** — Shallow logo strip and a wide customer quotation.
3. **Capability chapters** — Three broad benefit cells followed by a denser three-column technical matrix.
4. **Decision support** — Resource band and another standalone quote.
5. **Closing call** — Shared invitation and deep directory.

**Transfer:** Move from user-visible benefit to implementation depth, with proof bracketing the technical detail.

### Product introduction or early-access page

1. **Promise** — Tagged split opening with system art and signup/documentation routes.
2. **Product orientation** — Two-column comparison of product paths.
3. **Capability chapters** — Three illustrated problem-to-solution cells.
4. **Social proof** — Wide quote carousel with named attribution.
5. **Decision support** — Support band, editorial research carousel and split FAQ.
6. **Closing call** — Single early-access action framed by signal blocks, then shared directory.

**Transfer:** Explain fit and differentiation before inviting commitment; use research and practical FAQs to support an emerging product.

## Writing

Direct engineering confidence with enough warmth to promise a better developer experience. Strong outcome claims are followed by concrete mechanisms, controls or deployment details rather than vague aspiration.

**Do not copy:** Do not reuse the brand name, logos, customer names, quotations, proprietary product names, performance numbers, savings, uptime commitments or compliance claims as assets or claims for another product. Source examples below illustrate phrasing only.

- **Addressing the reader:** Speak directly to the reader with you and your; use we when describing a team decision or a belief. Product descriptions use clear active verbs and restrained first-person ownership.
- **Rhythm:** Headlines are short declarations or outcome phrases, often broken across two lines. Support usually runs one or two sentences; technical cells may use longer explanatory paragraphs. Action labels stay at two to four words, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A broad declarative promise, or a technical advantage tied to production use. | 3–7 words | “Inference is everything”<br>“Pricing built for growth”<br>“Frontier performance research in production” |
| Supporting line | Name the tangible mechanisms that make the promise believable. | One or two sentences | “The fastest model runtimes, cross-cloud high availability, and seamless developer workflows. Powered by the [Brand] Inference Stack.” |
| Capability title | A terse user outcome or an explicit technical capability. | 3–6 words | “DevEx built for rapid iteration”<br>“Control SLAs and economics”<br>“Don't compromise quality” |
| Primary action | Verb plus concrete task, or a direct route to expert help. | 2–4 words | “Start deploying”<br>“Talk to an engineer”<br>“Read the docs” |
| Practical reassurance | Use plain operational language with an explicit unit or constraint. | One short sentence | “Only pay for the compute you use, down to the minute.”<br>“Write training logic, not infra code.” |

**Words and phrasing to use:** production; performance; scale; configure; deploy; rapid iteration; your workflows; fully configurable; out of the box; latency; throughput

**Avoid:** magical; revolutionary; unleash your potential; game-changing; effortless everything; limitless possibilities

**Rules:**

- Tie technical detail to a reader-visible benefit, cost tradeoff or control.
- Use domain vocabulary naturally, but explain the consequence instead of merely listing acronyms.
- When contrasting alternatives, make the operational difference explicit.
- Keep sentence case in headings; reserve uppercase presentation for labels and action controls.
- Use quantified proof only when a real measurement can support it.

## Do's and Don'ts

### Do

- Keep the default opening headline at 88px/80px and weight 600 with -0.02em tracking.
- Use the 1296px outer container and 16px inner side padding to align text, art and rules.
- Carry 1px dashed grid lines through meaningful section and column edges.
- Keep conversion actions 48px tall and explanatory actions 36px tall with square corners.
- Let white and pale sage occupy most page area; concentrate green in art, strips and brief controls.
- Give smaller capability cells 24px padding and a 16px content gap.
- Preserve tiny uppercase mono telemetry and attribution as a counterpoint to broad grotesk headings.
- End with a white signal-framed invitation and a substantial black grouped directory.

### Don't

- Do not apply 12px–24px rounded corners to the brand's rectangular cards and controls.
- Do not turn all primary buttons neon green; the resting conversion control is black.
- Do not replace the exposed dashed grid with a continuous heavy table border.
- Do not use elevation shadows to separate ordinary white cells; their separation comes from rules and padding.
- Do not spread pink across full sections; it is a subordinate signal color outside editorial thumbnails.
- Do not set long explanatory paragraphs in monospace or uppercase.
- Do not use glows and gradients as the main page background; luminous effects belong inside diagrams and editorial art.
- Do not collapse the commercial rate detail into oversized price numerals; its character is a restrained 16px tabular presentation.

## Motion and responsive

### Motion

**Observed:**

- Actions declare all 236ms cubic-bezier(0.5, 0.2, 0.4, 1). Several cards and carousel indicators declare 75ms transitions.
- The opening headline declares a 0.8s ease reveal. Status dots declare a 2s infinite pulse with cubic-bezier(0.4, 0, 0.6, 1).
- Logo strips declare linear marquee motion; decorative line-reveal animations are also present.

**Transfer:**

- Use the declared action transition for the square controls and retain small status-dot motion rather than animating whole panels.
- Keep signal ribbons as shallow graphic transitions and preserve settled readability of the main diagram.

**Unknown:**

- Marquee duration, diagram animation sequencing and scroll-trigger behavior are not established.

### Responsive

**Observed:**

- Declared CSS includes 640px, 768px, 992px, 1024px, 1150px and 1280px breakpoints among others.
- Layout classes switch three-column capability grids to one column below the medium breakpoint; some decorative opening rules are hidden below the large breakpoint. Opening action groups use a vertical arrangement below their larger layout. The main desktop stage uses 500px height and switches to automatic height on smaller layouts.

**Transfer:**

- Stack opening copy before the schematic on narrow layouts; keep the object legible rather than retaining equal desktop halves.
- Reduce multi-column matrices to one column and align surviving grid rules with the resulting cell boundaries.
- Retain square controls and short mono labels while allowing the final directory groups to stack.

**Unknown:**

- Exact small-screen type sizes and the complete mobile navigation interaction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
