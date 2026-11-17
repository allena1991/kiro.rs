# Greptile — halftone engineering paper

## Overview

A technical marketing style that feels like a lively engineering drawing rather than a polished software dashboard. Pale gray paper and deep violet-gray chapters carry dense, tightly set sans-serif headlines, utilitarian monospace markings, electric green actions and pastel diagrams. Halftone subjects, wireframe fields and sharply clipped controls give spacious product stories an experimental, slightly industrial character.

### Essentials

- Headlines behave like heavy printed labels: Anybody at 96px/1, weight 700, -0.025em tracking for the main opening; 48px/1, weight 600, -0.04em for section titles.
- The opening is an asymmetric specimen plate: a 765px-tall pale stage, 64px side gutters, a two-line headline high on the left, support and joined actions low on the left, and an oversized black-and-white halftone subject rising from the right edge.
- Actions interlock like directional connectors, not pills: 41px height, 10px 26px padding and 10px polygon tips; paired left controls have an inward right notch and the right control overlaps by 6px.
- Color belongs to signals and whole technical chapters: pale gray dominates the default page, #3d3b4f supports substantial dark chapters, #28e99f marks the announcement and conversion controls, while mint, pink and pale lime illuminate diagrams and dark-ground text rather than rainbow card fills.
- The layout exposes its construction: 32px gutters double as ruler rails, 1px dashed boundaries and registration points mark edges, and 10px fine hatch frames surround illustrations. Keep this drafting language even when the new product has only a simple process diagram.
- Product imagery mixes flat interface fragments with fine wireframe geometry: 3:2 image stages sit above numbered captions, with pastel mesh lines, tiny square nodes and no soft card shadows. A minimal equivalent is a readable interface fragment connected to a few annotated nodes.
- The ending is a designed artifact: a dark two-column action stage uses a 48px pale-lime statement and 55px interlocking actions; the pale dotted footer combines a large constructed brand emblem with mono columns and a full-width pile of repeated low-contrast geometric symbols. Rebuild the emblem and symbol field for the new identity.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric green | `#28e99f` | `--color-signal` | action, accent, background | Main conversion controls, announcement strip, link hover fills and identity artwork. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fresh mint | `#c5ffd6` | `--color-mint` | text, action, accent | Dark product chapters, diagram lines and pale secondary controls. |
| Technical pink | `#ffcffe` | `--color-pink` | text, action, accent | Diagram accents and dark feature headings; the pink treatment also defines the specialist security opening. |
| Pale lime | `#ecffa3` | `--color-lime` | text, action, accent | Closing statement and actions, small square markers and enterprise proof numerals. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light paper | `#eeeeee` | `--color-paper` | background, surface, text | Light content canvas, navigation, quote panels and light text on dark controls. |
| Translucent paper | `#ececec` | `--color-wash` | surface | Visible half-opacity light paper over gray paper; actual fill is rgba(238,238,238,0.5). |
| Gray paper | `#e9e9e9` | `--color-canvas` | background | Opening stage and alternating light bands. |
| Silver rule | `#d6d6d6` | `--color-silver` | border, surface | Logo-grid rules, section separators and subdued backing. |
| Faint drafting edge | `#d3d2d6` | `--color-fine-edge` | border | Visible 15% violet-gray grid over gray paper; use rgba(85,83,104,0.15) for finer construction lines. |
| Drafting edge | `#bdbcc2` | `--color-edge` | border | Visible 30% violet-gray edge over gray paper; use rgba(85,83,104,0.3) for the actual border. |
| Violet graphite | `#3d3b4f` | `--color-ink` | text, background, action | Primary marketing text, dark chapter backgrounds and dark buttons. |
| Printed black | `#2a2a2a` | `--color-onyx` | text | Footer text and long-form customer narratives. |
| Signal black | `#000000` | `--color-black` | text | Text inside bright green controls and hover states. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| enterprise pages | Sage mint | `#c8ead0` | `--color-sage` | text, action | Primary light-on-dark enterprise text and muted mint controls. |
| editorial and related-content modules | Muted gray | `#6a6a6a` | `--color-tertiary` | text | Related-story descriptions and breadcrumb text. |

## Typography

- **Anybody** — Display headlines, section titles and major numerals. Broad, sturdy sans-serif with compressed spacing and emphatic lowercase shapes. Font stack: "Anybody", sans-serif.
- **DM Sans** — Support lines, paragraphs, feature titles, quotations and actions. Direct contemporary sans-serif; regular prose contrasts with semibold compact headings. Font stack: "DM Sans", sans-serif.
- **Space Mono** — Navigation, bracketed chapter labels, sequence numbers, figure captions and footer. Mechanical monospaced markings with generous tracking at small sizes. Font stack: "Space Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Anybody | 700 | 96px | 1 | -0.025em | Default landing-page headline, typically broken into two forceful lines. |
| heading | Anybody | 600 | 48px | 1 | -0.04em | Section titles, closing statements and large proof figures. |
| quote | DM Sans | 600 | 36px | 40px | -0.04em | Centered testimonial; also used for plan names. |
| quote-emphasis | DM Sans | 600 italic | 36px | 40px | -0.04em | One emphasized phrase inside a testimonial. |
| benefit-title | DM Sans | 700 | 30px | 1.2 | -0.04em | Text-led benefit columns. |
| hero-support | DM Sans | 400 | 24px | 32px | -0.01em | Opening support line; keep a compact measure of roughly 512px in the default opening. |
| feature-title | DM Sans | 600 | 24px | 32px | -0.02em | Titles beneath paired image stages. |
| lead | DM Sans | 400 | 20px | 1.4 | -0.01em | One-sentence section introductions. |
| body | DM Sans | 400 | 18px | 28px | -0.01em | Feature explanations beneath images. |
| eyebrow | Space Mono | 400 | 18px | 28px | 0.1em, uppercase | Bracketed chapter marker above the heading. |
| button-lg | DM Sans | 400 | 18px | 1.5 | -0.01em | Paired closing actions. |
| body-sm | DM Sans | 400 | 16px | 1.5 | -0.01em | FAQ answers and compact descriptive copy. |
| faq-question | DM Sans | 600 | 16px | 1.5 | normal | Compact accordion question labels. |
| figure-label | Space Mono | 400 | 14px | 20px | 0.025em | Small bracketed image labels, sequence numbers and figure notes. |
| button | DM Sans | 400 | 14px | 1.5 | -0.01em | Standard clipped actions. |
| announcement | DM Sans | 600 | 14px | 20px | -0.01em | Short news line in the green top strip. |
| rail-caption | Space Mono | 400 | 12px | 16px | 0.1em, uppercase | Centered micro-caption pinned to a horizontal boundary. |
| navigation | Space Mono | 400 | 12px | 16px | 0.05em, uppercase | Desktop navigation links. |
| footer-link | Space Mono | 400 | 11px | 1.5 | 0.025em, uppercase | Footer navigation. |
| footer-heading | Space Mono | 700 | 10px | 1.5 | 0.15em, uppercase | Footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | Anybody | 600 | 96px | 1 | -0.04em | Single centered title over the plan comparison. |
| specialist product and enterprise pages | secondary-display | Anybody | 600 | 72px | 1 | -0.04em | Two-line headline on a dark, compact product opening. |
| customer stories | story-display | Anybody | 700 | 72px | 1 | -0.04em | Long editorial outcome headline. |
| customer stories | story-stat | Anybody | 700 | 72px | 1 | normal | Paired outcome numerals under the story headline. |
| customer stories | interview-question | DM Sans | 400 | 30px | 1.2 | -0.04em | Large interview accordion questions. |
| related-content modules | related-title | DM Sans | 600 | 24px | 32px | -0.03em | Related-story and related-feature cards. |
| customer stories | story-body | DM Sans | 400 | 16px | 26px | -0.01em | Interview answers and editorial narrative. |
| enterprise proof modules | stat-caption | Space Mono | 400 | 16px | 1.5 | 0.05em, uppercase | Centered units below enterprise proof numbers. |
| pricing pages | recommended-label | Space Mono | 400 | 10px | 1.5 | 0.1em, uppercase | Thin full-width plan recommendation strip. |

**Notes:**

- Display and section headings use a single line-height ratio; preserve their compact silhouette rather than adding airy leading.
- The 96px default display has less negative tracking than the 48px section scale. Smaller body text keeps -0.01em; mono labels open out instead.
- Headlines are sentence case except deliberate short technical labels. Mono typography signals structure, not ordinary paragraphs.

## Layout

**Density:** Airy structural bands with compact internal groups: the diagram and headline have room to breathe, while captions and copy remain closely attached.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading to support line and close text groups. |
| 12px | Image-caption groups and footer link stacks. |
| 16px | Opening text/action stack and inner caption inset. |
| 24px | Related-card padding and quote groups. |
| 32px | Grid gutters, ruler rails, standard dark-card padding and heading-to-action separation. |
| 48px | Quote-stage padding and spacious proof-card interiors. |
| 64px | Main desktop side padding and closing-stage vertical padding. |
| 80px | Standard section heading band vertical padding. |
| 96px | Default opening top and bottom inset. |
| 120px | Full-width hatch separator interior height. |

### Containers and grids

- **content shell**: max width 1600px · side padding 64px. Centered outer shell for headings and content; at 1440px the normal content width is 1312px.
- **drafting grid**: max width 1600px · 12 columns · gap 32px. Two half-width, three third-width or four quarter-width modules share the same visible construction rails.
- **quote measure**: max width 768px · side padding 48px. Centered testimonial text inside the full-width framed stage.
- **faq measure**: max width 672px. Centered accordion list, visually flanked by decorative vertical rails.
- **editorial shell** (only for customer stories): max width 1280px · side padding 64px. Story material; interview layout pairs a 200px left label with the main question column and an 80px gap.
- **secondary opening** (only for specialist product and enterprise pages): max width 1600px · 12 columns · gap 32px · side padding 32px. Eight columns of text beside four columns of figure; a 540px-tall dark opening.

## Corner radius

| Element | Radius |
| --- | --- |
| controls and panels | 0px |

## Surfaces and depth

### Surfaces

#### Gray paper · level 0

**Use:** Default opening and alternating light chapters.

**CSS:** `background: #e9e9e9`

**Observed:** Flat matte gray with faint drafting boundaries; no depth effect.

**Transfer:** Let typography, rules and illustration carry hierarchy.

#### Light paper · level 0

**Use:** Content areas, quote stages and navigation.

**CSS:** `background: #eeeeee`

#### Graphite chapter · level 0

**Use:** Major technical chapters and closing stage.

**CSS:** `background: #3d3b4f; color: #c5ffd6`

**Observed:** Large uninterrupted dark grounds carry pastel type and restrained linework.

**Transfer:** Use as a substantial chapter rather than isolated dark cards on every row.

#### Hatched pause

**Use:** Wide visual breath between chapters.

**CSS:** `height: 120px; background: repeating-linear-gradient(-55deg, rgba(0,0,0,0) 0px, rgba(0,0,0,0) 7px, rgba(61,59,79,0.15) 7px, rgba(61,59,79,0.15) 8px)`

**Observed:** A 1px silver border above and below encloses the hatch. Dark enterprise variants use translucent pink lines.

**Transfer:** Use a true texture band, not an empty spacer.

#### Dotted footer paper · level 0

**Use:** Shared closing identity and navigation field.

**CSS:** `background-color: #eeeeee; background-image: radial-gradient(circle, rgba(0,0,0,0.15) 1px, rgba(0,0,0,0) 1px); background-size: 24px 24px`

**Observed:** Fine evenly spaced dots remain visible behind the emblem, columns and low-contrast symbol pile.

**Transfer:** Preserve the drawing-sheet feeling across the entire footer.

#### Drafting card · level 1

**Only for:** related-content and example modules

**Use:** Related-content and compact example cards.

**CSS:** `background: rgba(238,238,238,0.5); border: 1px solid rgba(85,83,104,0.3); border-radius: 0px; box-shadow: none`

**Observed:** Square, thinly outlined panels sit within larger dashed construction bays.

## Components

### Announcement strip

**Use:** Compact persistent news signal above navigation.

**CSS:** `background: #28e99f; height: 45px; border-bottom: 1px solid rgba(61,59,79,0.2); position: fixed; top: 0px`

**Text style:** `announcement` — DM Sans 600 · 14px/20px · tracking -0.01em

**Observed:** Centered short news sentence followed by an underlined mono link and tiny right arrow; wraps as one group.

### Navigation frame

**Use:** Persistent desktop wayfinding.

**CSS:** `background: #eeeeee; border: 0.5px dashed rgba(61,59,79,0.2); border-bottom-width: 1px; height: 66px`

**Text style:** `navigation` — Space Mono 400 · 12px/16px · tracking 0.05em · uppercase

**Observed:** Inset rectangular rail with a small geometric emblem on the left, centered links separated by 40px and a joined action pair at right. Registration crosses anchor the corners; the interior is 64px high.

**Transfer:** Keep the icon compact and the frame light even on dark pages.

### Navigation link

**Use:** Small technical navigation label.

**CSS:** `padding: 4px 8px; color: #3d3b4f; display: flex; gap: 6px`

**Text style:** `navigation` — Space Mono 400 · 12px/16px · tracking 0.05em · uppercase

**Observed:** A tiny chevron distinguishes links with menus.

**States:** Declared: hover background #28e99f and text #000000.

### Primary button

**Use:** Main conversion action and right-hand member of a joined pair.

**CSS:** `background: #28e99f; color: #000000; padding: 10px 26px; height: 41px; border-radius: 0px; clip-path: polygon(10px 0px, calc(100% - 10px) 0px, 100% 50%, calc(100% - 10px) 100%, 10px 100%, 0px 50%); display: flex; align-items: center; justify-content: center`

**Text style:** `button` — DM Sans 400 · 14px/1.5 · tracking -0.01em

**Observed:** When paired, the right member overlaps the notched left member by 6px. Mint and pink replace the green inside matching dark chapters.

**States:** Declared: hover on the pair translates the right member 4px horizontally; focus-visible outline-offset 2px with a transparent 2px outline and zero ring shadows.

### Notched companion button

**Use:** Sales or information action to the left of the main action.

**CSS:** `background: #3d3b4f; color: #eeeeee; padding: 10px 26px; height: 41px; clip-path: polygon(10px 0px, 100% 0px, calc(100% - 10px) 50%, 100% 100%, 10px 100%, 0px 50%)`

**Text style:** `button` — DM Sans 400 · 14px/1.5 · tracking -0.01em

**Observed:** The concave right edge receives the pointed primary control; an inset pseudo-layer produces outlined versions on dark backgrounds.

**States:** Declared: hover on the pair translates the left member -4px horizontally; focus-visible outline-offset 2px with a transparent 2px outline and zero ring shadows.

### Standalone hex button

**Use:** Local feature and proof links.

**CSS:** `background: #3d3b4f; color: #eeeeee; padding: 10px 26px; height: 41px; clip-path: polygon(10px 0px, calc(100% - 10px) 0px, 100% 50%, calc(100% - 10px) 100%, 10px 100%, 0px 50%)`

**Text style:** `button` — DM Sans 400 · 14px/1.5 · tracking -0.01em

**Observed:** Both ends point outward; no notch when there is no neighboring action.

### Closing action pair

**Use:** Prominent final action on a graphite stage.

**CSS:** `background: #ecffa3; color: #3d3b4f; padding: 14px 34px; height: 55px; clip-path: polygon(14px 0px, calc(100% - 14px) 0px, 100% 50%, calc(100% - 14px) 100%, 14px 100%, 0px 50%)`

**Text style:** `button-lg` — DM Sans 400 · 18px/1.5 · tracking -0.01em

**Observed:** The CSS describes the filled right member. Its left companion has a 14px inward notch, pale-lime outline and graphite inner layer inset by 1px; overlap increases to 10px.

**States:** Declared: hover on the pair translates the right member 4px and the left member -4px.

### Logo cell

**Use:** Compact proof matrix under an opening.

**CSS:** `background: rgba(238,238,238,0.5); height: 80px; padding: 0px 12px; border-right: 1px dashed #d6d6d6; border-bottom: 1px dashed #d6d6d6; display: flex; align-items: center; justify-content: center`

**Observed:** Eight columns and two rows make a full-width strip; marks are monochrome and optically balanced. A small rail caption sits above.

**Transfer:** Use authentic partner or customer marks, maintaining equal cells rather than identical logo widths.

### Quote stage

**Use:** A large credibility pause.

**CSS:** `max-width: 768px; text-align: center`

**Text style:** `quote` — DM Sans 600 · 36px/40px · tracking -0.04em

**Observed:** Centered quote with a single italic emphasis, customer emblem above, compact square portrait and mono name below, then a standalone hex button. The outer stage has 48px padding and 24px group gaps.

### FAQ row

**Use:** Short objection handling in a centered list.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 16px 0px; min-height: 56px; width: 100%`

**Text style:** `faq-question` — DM Sans 600 · 16px/1.5

**Observed:** A 16px chevron sits at the far right; dashed horizontal rules divide rows. Answers use body-sm and appear below the question, not in floating cards.

**States:** Declared: hover text #2a2a2a.

### Footer link

**Use:** Dense technical directory navigation.

**CSS:** `color: #2a2a2a; padding: 0px 4px; width: fit-content`

**Text style:** `footer-link` — Space Mono 400 · 11px/1.5 · tracking 0.025em · uppercase

**Observed:** Four directory columns sit beside a much wider identity panel. Headings use footer-heading, link stacks use 12px gaps, and a green status dot appears in the status group.

**States:** Declared: hover background #28e99f and text #000000.

### Related card

**Only for:** related-content and example modules

**Use:** Links to adjacent stories or features.

**CSS:** `display: flex; flex-direction: column; background: rgba(238,238,238,0.5); border: 1px solid rgba(85,83,104,0.3); overflow: hidden`

**Text style:** `related-title` — DM Sans 600 · 24px/32px · tracking -0.03em

**Observed:** A 24px-padded inner column holds title, muted body-sm description and a small learn-more arrow. Feature variants add a wide image above; example variants use a full-width shaded bottom action strip.

## Imagery and graphics

### Halftone specimen

**Use:** Dominant right-hand object in the default opening.

**Observed:** A large monochrome reptile head rises from the lower-right boundary, angled upward and cut off by the viewport edge. Dense black-and-white print dots retain photographic form; a very soft mint rim separates it from gray paper. Its roughly square 792px stage is nearly as tall as the hero, while text remains dominant on the left.

**Transfer:** Choose a product-relevant physical subject or a distinctive abstract object with a readable silhouette; turn it into a monochrome halftone and let it escape the frame.

**Build:** Use a transparent masked grayscale subject. Convert luminance into a regular black dot screen with an SVG halftone filter or preprocessed dot texture; preserve white highlight masses. Place it in a 792px square overflowing the right and bottom edges, with a subtle rgba(197,255,214,0.3) blurred silhouette behind. Minimum version: a single bold geometric specimen rendered in the same black dot treatment.

### Wireframe product plates

**Use:** Technical feature illustrations, repeated in paired or numbered columns.

**Observed:** Flat interface fragments float over thin blue, mint or pink wireframe tori, globes and sandbox boxes. Small bright squares mark nodes. Light stages are pale gray; dark stages preserve the graphite ground and use pastel lines. A 10px diagonal hatch frame surrounds 3:2 illustrations; text is outside below, never baked into a large photorealistic device.

**Transfer:** Reduce the new product to one legible interaction, data transformation or result, then place it over a restrained geometric network.

**Build:** In SVG, draw 10–18 intersecting elliptical paths or a perspective cuboid with 1px pastel strokes at 20–40% opacity. Layer 6–10 small square nodes in mint and pink, then a flat rectangular interface fragment in the foreground. Add 10px edge strips of repeating -55deg 1px lines on a 4px interval at 30% opacity. Minimum version: a clear input/output diagram with the same linework and square nodes.

### Closing network illustration

**Use:** Right half of the final graphite action stage.

**Observed:** A flat white review/result card sits at the center of dashed polygon connections, surrounded by six small stacks of pink and green bars. The full image stage is 640px by 427px and occupies the same width as the closing text column.

**Transfer:** Show one central outcome with surrounding contributing inputs, using a real interaction from the new product.

**Build:** Create an SVG hexagonal orbit of dashed 1px connections in translucent paper gray. Place six miniature stacks of 3–4 mint/pink rectangles around it and a centered white or light-paper result card. Keep shadows absent and preserve large areas of graphite between nodes.

### Constructed footer identity

**Use:** Shared footer identity panel and monumental lower artwork.

**Observed:** A bright green geometric emblem and wordmark sit on fine construction lines in the upper-left panel. Beneath the directory, dozens of pale gray faceted cube-like emblems accumulate into a dense uneven pile with several detached rotating-looking symbols above. The symbol field spans 1440px and its artwork stage is 567px high.

**Transfer:** Turn the new identity's simplest shape into a repeatable faceted symbol. Even a word-only identity needs a geometric monogram or modular abstract equivalent for this ending.

**Build:** Draw one original isometric modular SVG glyph using three flat faces separated by paper-colored seams. Reuse it at varied rotations and 64–100px scale; densely interlock 3–4 uneven rows at the bottom, then place 8–12 detached copies above. Use low-contrast silver against dotted paper, with a saturated green version in the upper identity panel. Add 1px construction diagonals and crosshairs behind the upper emblem.

### Runtime contour field

**Only for:** runtime or simulation feature promotions

**Use:** Dedicated experimental demonstration chapter.

**Observed:** A broad low landscape made from many thin blue contour lines sits below centered copy. Pink/lime rectangular stacks and isolated square nodes punctuate the field; tiny repeated mono words line the top and bottom of the stage.

**Transfer:** Use only when the product has a live process or simulation to explain; recast contours as a measured field relevant to that process.

**Build:** Draw 40–60 parallel SVG paths with gently varying vertical offsets and a central rise, at 1px blue strokes with low opacity. Place 4–6 flat pastel stacks on the surface and repeat a short process label across boundary rails.

### Icons

**Observed:** Utility arrows and chevrons are compact solid SVG forms at 12–16px; footer social marks are 14px. Larger diagram symbols live inside the image plates. Fine crosshairs and small square markers belong to the framing system.

**Transfer:** Choose simple monochrome arrows, chevrons and social silhouettes; keep marketing icons subordinate to labels and preserve square node markers instead of rounded badges.

## Section recipes

How recurring sections are built.

### First screen: Specimen plate opening

**Observed:** The first screen layers a fixed 45px green news strip and a light framed navigation bar above a 765px gray-paper stage. Fine vertical dashed rails and corner registration points sit behind the content. The heavy 96px display breaks into two lines high on the left, filling about half the width, with 96px top inset and 64px side gutters. A square halftone subject grows from the bottom-right, occupying roughly the right half and cropped by the outer stage. The 24px support line is anchored low on the left in a 512px measure, followed at 16px spacing by the notched companion and green primary actions, then a small underlined mono auxiliary link. Within the first 900px the headline, support, complete actions and specimen are visible; only the caption of the logo matrix peeks in at the bottom, with logos below the fold.

**Transfer:** Keep the high headline/low support tension and the oversized halftone silhouette for a new product. If no physical subject exists, render a single distinctive geometric artifact in halftone. Specialist openings instead use a 540px graphite split stage with a 72px pastel title across two thirds, a one-third figure with mono caption, and paired pastel actions below. Pricing opens with a centered 96px medium-weight title; customer stories open with a long 72px bold outcome headline and paired metrics.

**Avoid:** Do not replace the specimen with a centered dashboard card, center the whole text stack, or fill the intentional vertical interval with extra badges.

**Text style:** `display` — Anybody 700 · 96px/1 · tracking -0.025em

### Chapter heading band

**Observed:** An 80px-padded heading band stacks eyebrow, heading and lead with 8px gaps inside the content shell. A standalone hex button can align to the far right. The dark variant uses mint or pink for all three roles; light chapters use graphite.

**Transfer:** Use a short bracketed category and a declarative title, then describe the mechanism in one sentence.

**Text style:** `heading` — Anybody 600 · 48px/1 · tracking -0.04em

### Numbered technical plates

**Observed:** Three or four equal bays share a 32px gutter and visible ruler rails. Each holds a hatch-framed illustration, then a 14px mono sequence number, a compact title and 18px explanation. Larger paired plates use feature-title and a local standalone hex action below.

**Transfer:** Split one capability into distinct stages or parallel methods rather than unrelated generic benefits.

### Quote and proof mosaic

**Observed:** The Quote stage forms a full-width pause between chapters. Later, six light quote cards populate a three-column drafting grid with the section title and action occupying a central bay; card names are small uppercase mono, portraits remain small and square.

**Transfer:** Use one strong editorial quote early and a more compact proof mosaic later when there is enough authentic material.

### Text benefit row

**Observed:** Three equal columns place a small mono index above a 30px bold benefit title and an 18px explanation. Construction rails stay visible between columns; the enterprise variant uses dotted graphite cards with 32px padding.

**Transfer:** Use this for concrete operational assurances, not long feature inventories.

### Decorated FAQ

**Observed:** A centered heading leads a 672px FAQ measure with 32px separation. FAQ rows are 56px minimum with dashed separators; a contact sentence sits 48px below. The wide outer margins contain vertical dashed lines spaced 32px apart, each carrying scattered 8px lime squares. The dark variant switches markers to mint.

**Transfer:** Keep decorative activity at the edges so the center stays calm and legible.

### Closing action stage

**Observed:** A 555px graphite band with 64px vertical and horizontal padding places a pale-lime 48px statement in the left 640px column, joined closing actions 32px below and the Closing network illustration in the matching right column. Faint vertical construction lines continue through the background.

**Transfer:** End with an outcome promise and two clear next steps; use the network to summarize how the product produces that outcome.

**Text style:** `heading` — Anybody 600 · 48px/1 · tracking -0.04em

### Identity directory ending

**Observed:** Dotted footer paper contains a large green constructed identity at left and four compact mono directory columns at right, separated by rails. The upper directory occupies about 413px; the low-contrast symbol pile then takes over the full width, with tiny right-aligned copyright at the bottom. Total footer height is 907px. This ending is shared across every page type; pricing goes directly from FAQ to this footer rather than adding the closing action stage.

**Transfer:** Treat the repeated symbol artwork as the final visual memory, not as a background behind a tiny conventional footer.

### Enterprise quantified proof

**Only for:** enterprise pages

**Observed:** Four 48px pale-lime figures occupy two stacked cards on each side of a central result-feed column. A three-column 32px grid holds the composition; 8px fine striped edges frame the metrics and 16px mono captions label units.

**Transfer:** Use four independently meaningful measures and a central concrete activity example; preserve the balance of numbers and evidence.

### Editorial outcome opening and interview

**Only for:** customer stories

**Observed:** A breadcrumb precedes a 600px story stage. A customer emblem sits above a left-aligned 72px bold headline, with two 72px untracked metrics and mono captions below. The background is a faint square grid with a warm translucent tint. A small graphite conversion inset has registration brackets. The interview places its section label in a 200px left column, questions at 30px in the right column, and 16px/26px answers; one answer is expanded.

**Transfer:** Lead with the customer's specific operating problem and measurable result, then use an interview to explain the change.

### Pricing comparison

**Only for:** pricing pages

**Observed:** A centered 96px title sits in a 257px drafting frame. Three aligned plan columns follow with 36px semibold names, short centered suitability lines and clipped actions. The middle plan has a 23px green recommendation strip; detail lists align below dashed internal dividers. A two-column eligibility band and hatch pause lead to the FAQ and shared footer.

**Transfer:** Make plan logic legible through alignment and the thin recommendation signal, not by inflating one plan into a rounded floating card.

## Page flow

**Storyline:** Promise → concrete demonstration → credible proof → capability or operational chapters → objection handling → decisive action and constructed identity ending.

### General product landing page

1. **Promise** — Specimen plate opening with compact promise and joined actions.
2. **Social proof** — Logo matrix and large centered testimonial.
3. **Mechanism** — Dark chapter with three illustrated process plates and concrete examples.
4. **Capabilities** — Light paired plates, numbered integration grid and dedicated experimental scene.
5. **Trust** — Text benefit row and quote mosaic.
6. **Objection handling** — Decorated centered FAQ.
7. **Closing call** — Graphite action stage followed by the constructed identity directory.

**Transfer:** Alternate atmospheric hero art with increasingly concrete explanations; borrow the narrative functions without requiring the same number of sections.

### Customer outcome story

1. **Quantified promise** — Customer emblem, long outcome headline and two oversized metrics.
2. **Credibility** — Centered customer quotation.
3. **Explanation** — Interview accordion followed by a two-column contextual narrative.
4. **Continued reading** — Four compact related-story cards.
5. **Closing call** — Graphite action stage and shared identity footer.

**Transfer:** Use authentic customer language, a specific starting condition and verified outcomes.

### Commercial comparison

1. **Orientation** — Large centered page title.
2. **Decision** — Three aligned plan columns with a thin green recommendation strip.
3. **Eligibility** — Two parallel discount or access panels.
4. **Objection handling** — Short decorated FAQ after a hatched separator.
5. **Ending** — Shared identity directory directly after the FAQ.

**Transfer:** Prioritize price logic and access conditions; avoid adding an unrelated late sales pitch.

### Focused specialist capability

1. **Promise** — Compact dark split opening with pastel headline and annotated product figure.
2. **Mechanism** — Pixel-wave boundary leads into a light three-stage process.
3. **Concrete proof** — Compact finding cards with full-width bottom links.
4. **Adjacent capabilities** — Related-feature image cards.
5. **Closing call** — Shared dark action stage and identity directory.

**Transfer:** Explain the specialist mechanism first, then illustrate actual outputs.

### Enterprise evaluation

1. **Promise** — Dark split opening and monochrome logo matrix.
2. **Coverage** — Two large pastel technical plates.
3. **Operational trust** — Three assurance cards and a hatched pause.
4. **Adaptability** — Large illustrated explanation plus four numbered plates.
5. **Credibility** — Centered quote on the dark field.
6. **Ecosystem fit** — Four text-led capability cards.
7. **Quantified proof** — Four striped metric panels flanking an activity feed.
8. **Closing call** — Graphite action stage.
9. **Objection handling and ending** — Dark FAQ followed by the same light identity footer.

**Transfer:** Keep graphite as the page-wide enterprise theme, and move from coverage to deployment concerns to scale proof.

## Writing

Direct technical confidence with occasional human wit. Concrete mechanisms and outputs do most of the persuading; a short conversational title can soften an otherwise serious explanation.

**Do not copy:** Do not reuse Greptile's name, emblem, reptile artwork, customer identities, quotations, funding announcements, usage numbers, security certifications, performance claims or pricing terms. Supply the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team. The product usually names itself in explanatory prose; customer quotations may use first-person language.
- **Rhythm:** Short headline, one-sentence support, then a concrete explanation. Most titles run 3–8 words; long outcome headlines and closing statements are allowed. Actions are short verb phrases; bracketed labels are terse nouns.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category plainly or state the concrete benefit. | 4–8 words | “The AI Code Reviewer”<br>“Security reviews for your PRs” |
| Support line | Explain the action and the mechanism in one sentence. | 12–25 words | “AI agents that review and test pull requests with full context of the codebase.” |
| Feature title | Mix exact technical terms with occasional conversational idiom. | 3–8 words | “Your house, your rules”<br>“Independent by design” |
| Technical description | Start with an active verb and name the actual object or operation. | 10–25 words | “Builds a graph of your repo - files, functions, and dependencies.” |
| Section marker | A bracketed category in capitals, not a sentence. | 1–3 words | “[ PERSONALIZATION ]”<br>“[ KEEP READING ]” |
| Action | Direct verb plus destination or object; no ornamental enthusiasm. | 2–5 words | “Start now”<br>“Set your rules”<br>“Apply for startup discount” |

**Words and phrasing to use:** your team; context; workflow; built for; review; validate; runs; learns; before they ship; plain English

**Avoid:** revolutionary; unleash; magical; synergy; game-changing; next-generation solution

**Rules:**

- Put the mechanism immediately after the promise; prefer an exact operation over a string of adjectives.
- Pair technical certainty with one human phrase per chapter at most.
- Keep evidence, qualifications and eligibility conditions explicit in commercial and trust copy.
- Use mono labels for orientation and sans-serif sentences for persuasion.

## Do's and Don'ts

### Do

- Keep the default 96px headline heavy and the 48px section headings at weight 600.
- Use 64px desktop side gutters and 32px grid gaps as the structural anchors.
- Retain 0px corner radii; draw action silhouettes with polygon tips and inward notches.
- Carry drafting rails, hatch edges and registration points through both light and dark chapters.
- Place feature copy below 3:2 illustration stages instead of overlaying long text on diagrams.
- Reserve the strongest green for compact signals and identity artwork, with pastel text on graphite chapters.
- Rebuild the footer as a large dotted identity artifact, including the low-contrast symbol pile.
- Keep technical labels in Space Mono and prose in DM Sans.

### Don't

- Do not substitute near-black for #3d3b4f; the violet cast is essential to the dark chapters.
- Do not make every section a white card on a white background; retain the #e9e9e9 and #eeeeee paper distinction.
- Do not use rounded SaaS pills or 12px-radius feature panels in place of the clipped controls and square bays.
- Do not add drop shadows to lift the marketing cards; separation comes from 1px rules, pattern and tone.
- Do not use monospace for long body paragraphs; it belongs to structural markings.
- Do not saturate every figure with electric green; pastel linework and sparse square nodes keep diagrams readable.
- Do not enlarge small portraits into lifestyle photography blocks; customer faces remain subordinate to quotes.
- Do not replace wide hatch bands with gradient glows; the material language is printed and diagrammatic.

## Motion and responsive

### Motion

**Observed:**

- Joined action members declare transform 0.2s, separating by 4px in opposite directions on hover.
- Navigation color transitions declare 0.15s cubic-bezier(0.4,0,0.2,1); logo cells use 0.2s with the same curve.
- The announcement strip declares all 0.7s cubic-bezier(0,0,0.2,1). A specimen glow declares 6s ease-in-out infinite; a sphere scene declares 40s linear infinite.

**Transfer:**

- Keep the button-pair separation as the characteristic interaction; do not replace it with scale or lift.
- Use slow internal movement only within the wireframe/specimen artwork so reading positions stay fixed.

**Unknown:**

- Scroll choreography and the exact canvas animation paths are unspecified.

### Responsive

**Observed:**

- Desktop navigation is displayed at 1024px and above; the desktop footer directory also uses this breakpoint.
- The opening headline declares smaller text classes below desktop; feature grids declare one column before their 768px multi-column arrangement.
- Outer content classes step through 24px, 48px and 64px padding. Decorative FAQ edge rails are hidden below 1280px.

**Transfer:**

- On narrow screens, keep the title above support and actions, then let the specimen extend below or beside the text without obscuring it.
- Collapse multi-column plates into a single readable sequence; retain hatch framing, mono numbering and clipped buttons.
- Remove peripheral FAQ rails before shrinking the 672px reading column. Preserve the identity artwork in a vertically reorganized footer.

**Unknown:**

- Exact narrow-screen typography, navigation menu behavior and footer rearrangement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
