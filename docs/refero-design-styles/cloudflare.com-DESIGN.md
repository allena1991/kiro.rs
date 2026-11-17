# Cloudflare — infrastructure in sunlight

## Overview

A bright, engineering-minded style that makes complex platforms feel approachable and ready to use. White technical grids and restrained grotesk typography are punctuated by hot orange stages, dotted light fields and a warm horizon glow. The imagery favors explanatory diagrams, abstract data forms and small interface vignettes rather than photography, with spacious storytelling around compact capability lists.

### Essentials

- Broad promises sit inside a luminous orange stage: a near-full-width panel with 8px outer gutters, 16px corners and centered white 56px/0.99 medium headlines tracked at -0.025em.
- Technical scaffolding stays visible but faint: 1200px grids use 1px #f0f0f0 dividers and small 14px square junction markers with 3px corners, rather than separate floating cards.
- Headings feel conversational rather than monumental: 48px/1 and 56px/1 at weight 500, paired with 19.2px/1.2 support text; small card descriptions tighten to 16px/1.2.
- Actions are capsules, not slabs: the main white-on-orange-stage button is 50px tall with 12px 24px padding; white-page utility actions use 38px outlined pills.
- Color arrives as a concentrated burst, not a continuous theme: most of the body is white, with #ff5e1f reserved for the opening, selected controls, a highlighted proof tile and the closing stage; secondary marketing colors belong inside explanatory diagrams.
- A fine dot field and a pale warm glow rising from the bottom anchor the orange stages. Recreate this light-and-data material even without product artwork; the closing version adds tilted dashed icon tiles and a 56px proof ticker.
- Proof is presented as a working browser-like instrument: a 1200px wide softly outlined testimonial panel with a 76px logo tab rail, 2px orange active underline, a roomy quote and a separate customer-logo strip.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5e1f` | `--color-orange` | background, accent, action, border, link | Large luminous stages, selected tabs, highlighted tiles and small emphasis. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Secondary orange | `#ff7038` | `--color-orange-soft` | surface, action, text | Secondary capsule on orange and command-line accents. |
| Orange haze | `#ffcfbc` | `--color-orange-haze` | background | Visible 30% orange wash over white; atmospheric blur rather than solid card color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text, action | Main page, grid cells and primary buttons; inverse text on orange stages. |
| Button ink | `#1f1f1f` | `--color-button-ink` | text | Text on the white primary capsule. |
| Primary ink | `#262626` | `--color-ink` | text | Headlines, labels, body text and outline icons. |
| Secondary text | `#676767` | `--color-secondary` | text | Visible result of primary ink at 70% opacity over white; supporting descriptions. |
| Tertiary gray | `#727272` | `--color-tertiary` | text | Small category labels, captions and subdued supporting detail. |
| Structural rule | `#f0f0f0` | `--color-rule` | border | Grid edges, panel outlines, junction markers and dividers. |
| Warm near-white | `#fdfdfc` | `--color-panel` | surface | Testimonial and nested technical panels; only subtly warmer than the page. |

## Typography

- **STK Bureau Sans** — All marketing headings, descriptions, navigation and labels. A direct, open grotesk with an approachable large x-height; medium headings and regular text share one construction. If unavailable, use **Inter**. Use weights 400 and 500 with the specified tight display tracking. Font stack: "STK Bureau Sans", "Inter", Arial, sans-serif.
- **Apercu Mono Pro** (only for technical demonstrations) — Commands, code and architecture annotations. Compact, functional monospace that contrasts gently with the marketing grotesk. If unavailable, use **IBM Plex Mono**. Font stack: "Apercu Mono Pro", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | STK Bureau Sans | 500 | 56px | 0.99 | -0.025em | Opening promise and inverse closing call. |
| heading-lg | STK Bureau Sans | 500 | 56px | 1 | -0.025em | Short major chapter statements and commercial promises. |
| heading | STK Bureau Sans | 500 | 48px | 1 | -0.025em | Default section heading and centered proof statement. |
| price-or-quote | STK Bureau Sans | 500 | 32px | 1 | -0.025em | Price numerals; also freestanding customer quotes and larger quotation variants. |
| quote | STK Bureau Sans | 500 | 29.4px | 0.96 | -0.025em | Default large testimonial quotation. |
| lead | STK Bureau Sans | 400 | 19.2px | 1.2 | -0.025em | Centered supporting sentences and opening support. |
| card-heading | STK Bureau Sans | 500 | 18px | 1.2 | -0.025em | Benefit tiles and prominent capability labels. |
| body | STK Bureau Sans | 400 | 16px | 1.2 | -0.0025em | Compact descriptions in cards and diagrams. |
| label | STK Bureau Sans | 500 | 16px | 1.2 | -0.0025em | Capability titles and testimonial attribution names. |
| action | STK Bureau Sans | 500 | 16px | 1.5 | normal | Navigation and capsule actions. |
| tab | STK Bureau Sans | 500 | 16px | 1.5 | -0.01em | Segmented category controls. |
| footer-link | STK Bureau Sans | 400 | 16px | 1 | normal | Footer links and proof ticker text. |
| caption | STK Bureau Sans | 400 | 14px | 1.15 | -0.01em | Small descriptive text and secondary list lines. |
| category | STK Bureau Sans | 500 | 13px | 1 | normal | Subdued footer and grouped-directory category names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical demonstrations | command | Apercu Mono Pro | 400 | 14px | 1.5 | normal | Single-line install command in a small terminal panel. |
| product catalogs | catalog-eyebrow | STK Bureau Sans | 500 | 13px | 1.176 | 0.025em, uppercase | Small category captions above each catalog matrix. |

**Notes:**

- Keep the headline weight at 500, not bold. The 48px and 56px recipes share -0.025em tracking and nearly solid line spacing.
- Support text is not a generic 20px body style: it uses 19.2px with 1.2 line height and the same tight tracking as headings.
- Use sentence case throughout ordinary marketing text. Uppercase category captions are a catalog-specific variant, not the default section eyebrow.
- Long descriptions remain compact at 16px/1.2; keep them in short blocks rather than widening line spacing across every card.

## Layout

**Density:** Airy between narrative blocks, compact within technical grids and lists.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Outer stage gutters and small icon/text gaps. |
| 12px | Compact action horizontal padding and nested panel spacing. |
| 16px | Section heading-to-support gap. |
| 24px | Internal content groups and tighter card variants. |
| 32px | Default section side padding and grid-cell padding. |
| 40px | Hero content stack gaps, generous pricing-cell padding and heading-block grouping. |
| 48px | Catalog category separation and comparison-panel padding. |
| 64px | Hero inner vertical padding. |
| 80px | Primary separation between narrative sections. |
| 96px | Large commercial section top padding. |
| 128px | Closing stage top padding. |

### Containers and grids

- **Content grid**: max width 1200px · side padding 32px. Centered shared width for capability grids, testimonial panels and demonstrations.
- **Heading measure**: max width 1080px · side padding 32px. Centered heading-and-support groups; let the text balance naturally.
- **Stage shell**: max width 1480px · side padding 8px. Near-edge-to-edge orange opening and closing stages.
- **Capability columns**: 3 columns · gap 0px. Touching cells separated by hairlines; use an enclosing frame, not gutters.
- **Footer columns**: 4 columns · gap 32px. Four link columns to the right of a compact brand mark; secondary groups stack below primary groups.
- **Catalog columns** (only for product catalogs): max width 1200px · 4 columns · gap 0px. Equal-width product entries with small icons above title and description.

## Corner radius

| Element | Radius |
| --- | --- |
| Capsule actions | 9999px (pill) |
| Orange stages | 16px |
| Testimonial panel | 12px |
| Nested technical panel | 8px |
| Floating icon tile | 6px |
| Grid junction marker | 3px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Soft stacked edge | `inset 1px 6px 6px 0px rgba(255,255,255,0.2), 0px 4px 12px 0px rgba(0,0,0,0.02), 0px 2px 12px 0px rgba(0,0,0,0.03)` | Orange stages and the main testimonial instrument; a subtle lit top edge, not a dark elevation shadow. |

### Surfaces

#### White technical canvas · level 0

**Use:** Default page background.

**CSS:** `background: #ffffff; color: #262626`

**Observed:** The body remains bright; faint vertical rails and dotted texture provide structure without a dark theme.

**Transfer:** Keep large areas unfilled so dense diagrams and small type have breathing room.

#### Orange stage · level 1

**Use:** Opening, closing and concentrated highlighted proof.

**CSS:** `background: #ff5e1f; border-radius: 16px; overflow: hidden; box-shadow: inset 1px 6px 6px 0px rgba(255,255,255,0.2), 0px 4px 12px 0px rgba(0,0,0,0.02), 0px 2px 12px 0px rgba(0,0,0,0.03)`

**Observed:** Fine light dots and a bottom-centered pale glow sit behind white content. A softly lit edge makes the panel feel layered.

**Transfer:** Use the luminous data-field treatment rather than an undifferentiated flat orange rectangle.

#### Technical frame · level 1

**Use:** Capability matrices, split demonstrations and proof modules.

**CSS:** `background: #ffffff; border: 1px solid #f0f0f0`

**Observed:** Square touching cells share dividers; tiny white outlined junction squares interrupt the outer frame.

**Transfer:** Treat the whole grid as one instrument with internal subdivisions.

#### Warm instrument · level 1

**Use:** Testimonial panel and nested technical material.

**CSS:** `background: #fdfdfc; border: 1px solid #f0f0f0; border-radius: 12px`

**Observed:** The tint differs only slightly from the white page. Dashed inner outlines give selected panels a second frame.

**Transfer:** Use near-white nesting to show structure without gray slabs.

#### Translucent icon tile · level 2

**Use:** Floating motifs around the closing call.

**CSS:** `background: rgba(255,255,255,0.05); border: 1px dashed rgba(255,255,255,0.7); border-radius: 6px; backdrop-filter: blur(2px)`

**Observed:** Small outlined product symbols sit in individually rotated square tiles around, not over, the main copy.

**Transfer:** Use symbols relevant to the new product, retaining the light transparent material.

## Components

### Navigation link

**Use:** Desktop central navigation.

**CSS:** `padding: 6px 12px; border-radius: 6px; color: #262626`

**Text style:** `action` — STK Bureau Sans 500 · 16px/1.5

**Observed:** Text links sit between a left wordmark and right utility capsules in a 72px fixed header. Dropdown links have tiny paired chevrons. The scrolled header simplifies to a compact mark and an orange action at opposite edges.

**States:** Declared: hover opacity 0.8.

**Transfer:** Keep navigation visually smaller than the stage, with a white header rather than an orange bar.

### Primary button

**Use:** Main conversion on orange stages.

**CSS:** `background: #ffffff; color: #1f1f1f; border: 1px solid #ffffff; border-radius: 9999px; padding: 12px 24px; height: 50px; backdrop-filter: blur(12px)`

**Text style:** `action` — STK Bureau Sans 500 · 16px/1.5

**Observed:** The opening uses one centered action; the closing pairs it with Secondary stage button. Width follows the label.

**States:** Declared: hover background transparent, color #fffbf5, opacity 0.95; focus-visible border-color #d4d4d4; active scale 0.98.

### Outline button

**Use:** White-page utilities, pricing actions and smaller conversion prompts.

**CSS:** `color: #262626; border: 1px solid #f0f0f0; border-radius: 9999px; padding: 6px 12px; height: 38px; backdrop-filter: blur(12px)`

**Text style:** `action` — STK Bureau Sans 500 · 16px/1.5

**Observed:** The compact default appears in navigation and pricing. A larger white-page variant uses 8px 16px padding and 42px height for longer labels.

**States:** Declared: hover border-color color-mix(in oklab,#ff5e1f 40%,transparent), opacity 0.95; focus-visible border-color #d4d4d4; active scale 0.98.

### Secondary stage button

**Use:** Documentation or alternate action beside the primary stage action.

**CSS:** `background: #ff7038; color: #ffffff; border: 1px solid rgba(255,255,255,0.1); border-radius: 9999px; padding: 12px 24px; height: 50px; backdrop-filter: blur(12px)`

**Text style:** `action` — STK Bureau Sans 500 · 16px/1.5

**Observed:** Tonally merges with the orange surface while the white primary capsule remains dominant.

**States:** Declared: hover border-color #fffbf5, background-color color-mix(in oklab,#2a2927 5%,transparent), opacity 0.95; focus-visible border-color #d4d4d4; active scale 0.98.

### Benefit cell

**Use:** Compact benefit rows and capability matrices.

**CSS:** `background: #ffffff; border-left: 1px solid #f0f0f0; padding: 32px`

**Text style:** `card-heading` — STK Bureau Sans 500 · 18px/1.2 · tracking -0.025em

**Observed:** Icon first, then short heading and one compact body paragraph. Three touching cells form a single framed row. Denser solution matrices use the label recipe for titles.

**Transfer:** Give each cell one benefit, not a mini landing page.

### Category selector

**Use:** Switch between commercial or catalog categories.

**CSS:** `height: 40px; padding: 10px 14px; border-radius: 9999px; color: #262626; gap: 8px`

**Text style:** `tab` — STK Bureau Sans 500 · 16px/1.5 · tracking -0.01em

**Observed:** Controls sit in a white pill tray with 4px padding and a 1px structural outline. A solid orange capsule slides behind the selected label, which reads white; unselected labels stay dark. Commercial categories include small icons.

**Transfer:** Use this for alternative views of the same material, not every ordinary navigation list.

### Customer story panel

**Use:** Prominent qualitative proof.

**CSS:** `background: #fdfdfc; border: 1px solid #f0f0f0; border-radius: 12px; max-width: 1200px; overflow: hidden`

**Text style:** `quote` — STK Bureau Sans 500 · 29.4px/0.96 · tracking -0.025em

**Observed:** Logo tabs across the top, a pause control, large left quote and small attribution, with a customer mark and small circular portrait on the right. The inner quote stage uses a faint dashed frame. A separate logo row sits below.

**Transfer:** Use authentic, attributable outcomes; a simple customer symbol can replace elaborate brand art.

### Customer story tab

**Use:** Select among customer stories.

**CSS:** `padding: 16px 12px; height: 76px; border-bottom: 2px solid #ff5e1f`

**Text style:** `category` — STK Bureau Sans 500 · 13px/1

**Observed:** Each tab contains a small customer logo and label. The selected logo is additionally held in a white outlined 6px-corner chip; unselected tabs have transparent underlines. The rail fades at its clipped sides.

### Footer link

**Use:** Link lists in the shared white footer.

**CSS:** `color: #262626; padding: 8px 0px`

**Text style:** `footer-link` — STK Bureau Sans 400 · 16px/1

**Observed:** 13px muted category headings precede each list. Four columns begin to the right of the small wordmark; a second row of groups fills the first three columns. The 900px desktop footer leaves a long white breathing area before a bottom copyright and privacy row.

**Transfer:** Keep the ending light and spacious, not a dense dark sitemap.

### Grid junction

**Use:** Technical framing detail at grid intersections.

**CSS:** `width: 14px; height: 14px; background: #ffffff; border: 1px solid #f0f0f0; border-radius: 3px`

**Observed:** Tiny empty outlined squares sit centered across frame intersections and selected panel corners, like handles in a design or diagram tool.

**Transfer:** Repeat sparingly at structural junctions; they are decoration rather than controls.

### Comparison panel

**Only for:** pricing pages

**Use:** Detailed plan comparison and objection handling.

**CSS:** `background: #ffffff; border: 1px solid #f0f0f0; border-radius: 8px; overflow: hidden`

**Text style:** `body` — STK Bureau Sans 400 · 16px/1.2 · tracking -0.0025em

**Observed:** Four compact plan summaries precede a five-column comparison: feature label plus four tiers. Category accordion headers are 48px tall; detail rows use checkmarks, dashes and short values, with very faint alternating near-white washes. Plan buttons are outlined rather than one oversized dark recommended card.

**Transfer:** Maintain equal tier widths and align feature values consistently.

## Imagery and graphics

### Luminous data field

**Use:** Signature material on the opening and closing orange stages.

**Observed:** Dense columns of tiny pale marks ripple like a fabric of data over saturated orange. A cream-yellow light blooms from just below the bottom center and fades upward; the sides stay strongly orange. The background fills the whole stage, with text remaining crisp above it.

**Transfer:** Keep this atmosphere even when no product render exists. A static vector dot mesh with an elliptical glow is the minimum acceptable equivalent; exact light stops are not essential.

**Build:** Use an orange base, then a clipped SVG pattern of 1px pale circles or short vertical strokes spaced about 5px apart. Modulate their opacity with a broad wave-shaped mask, strongest around the lower central area and softer at the upper edges. Behind the dots place a wide bottom-centered cream radial glow, blurred about 64px and extending below the panel. Keep the glow away from headline letterforms and add a subtle translucent white inset along the top edge.

### Dotted global object

**Use:** Large explanatory proof object on a white background.

**Observed:** A pale globe made of orange points sits centrally in a roughly 500px-tall media area. Circular user and database markers connect with thin dashed arcs. White translucent stat callouts have orange dashed outlines and sit to either side; a three-cell benefit strip anchors the illustration.

**Transfer:** Translate the spatial globe into a relevant system, workflow or network of the new product. Keep the point-cloud lightness and small labeled annotations rather than using a dense glossy render.

**Build:** Draw a spherical or domain-specific outline as many tiny orange SVG dots with decreasing opacity toward the edges. Add sparse curved dashed paths, 48px circular icon markers and two white translucent 240px callout boxes with 1px dashed orange borders. Keep the explanatory silhouette visible without animation.

### Interface vignettes

**Use:** Demonstrate workflows in capability mosaics and split technical panels.

**Observed:** Small, light interface fragments show deployment rows, command bars, code or agent activity. They float inside much larger white frames and often fade at one edge. Adjacent text cells explain the outcome; these are not full-screen dashboard screenshots.

**Transfer:** Create a few legible, product-specific rows or a concise command, framed as a real action. Keep its internal palette subordinate to the surrounding marketing grid.

### Before-and-after signal

**Use:** Contrast operational friction with a simplified outcome.

**Observed:** A 1200px split panel contrasts a pale left half with scattered messages and a noisy dotted waveform against a saturated orange right half with one calm translucent success notification. Both halves use 48px headings.

**Transfer:** Choose a real contrast in the new product's workflow; show complexity versus one clear outcome, not generic decorative charts.

**Build:** Divide one technical frame into equal halves. On white, place several small near-white message cards around a sparse orange-gray point waveform. On orange, continue a single faint horizontal dotted signal through a centered translucent status capsule. Keep the orange half visually calmer.

### Closing orbit tiles

**Use:** Surround the signature closing call.

**Observed:** Six transparent dashed tiles, roughly 70–88px square, carry pale outline symbols and rotate at different shallow angles on the left and right of the centered text.

**Transfer:** Use product-relevant abstract symbols in the same material, leaving a clear central reading corridor.

**Build:** Place three Translucent icon tile elements on each side of the call, with approximately -12deg to 30deg rotations, centered 35–38px line icons and varying vertical offsets. Keep their opacity below the white headline and clip them within the Orange stage.

### Editable architecture diagram

**Only for:** technical solution explanations

**Use:** A large diagram proving how components work together.

**Observed:** A near-white framed canvas holds pastel blue, teal, orange and magenta groups, each with thin colored outlines, small square corner handles, dashed inner tiles and monospace captions. Fine gray dashed connectors lead left to right through a roomy arrangement. Small explanatory copy and customer attribution float above the diagram.

**Transfer:** Use color to distinguish functional groups only inside the diagram; preserve whitespace and make the connections readable.

**Build:** Create SVG rounded rectangles with 1px colored outlines and matching 10% fills. Add 8px white square handles on corners, 50px dashed icon tiles, 14px mono labels and light gray dashed Bezier connectors. Use a near-white backing with faint dot texture and keep most nodes below the explanatory caption.

### Icons

**Observed:** Marketing icons are small, mostly monochrome SVG symbols at 16px, 20px and 24px. Outlined examples use 2px round strokes; product-category glyphs mix simple solid and outline construction. Larger closing symbols are pale and approximately 38px.

**Transfer:** Choose simple functional symbols with little detail. Put a small icon before a benefit title or above a catalog label; reserve color-coded icon boxes for architecture diagrams.

## Section recipes

How recurring sections are built.

### First screen: Luminous promise opening

**Observed:** A 72px white Navigation link header sits above an Orange stage with 8px side gutters and 16px corners. At desktop the stage is 760px tall and occupies almost the full first screen. Layers run orange base, Luminous data field, bottom light bloom, then centered copy and actions. A slender outlined announcement capsule sits above the headline. The white display headline spans about three quarters of the available width, constrained to 1080px, and balances into two lines. A two-line lead follows, then one Primary button; the vertical stack uses 40px gaps with extra separation before the action. The entire headline, support, action and luminous field are visible within the first 900px; the next white proof chapter starts below that view.

**Transfer:** For a different product, make the first screen's main object the luminous data field itself, with a concise promise and one conversion action. Use a product-relevant announcement if there is one. Technical solution pages use a scoped white opening instead: a small orange dashed category badge, 48px centered headline, 16px supporting paragraph and a three-cell benefit strip. Pricing and catalog openings use a white 56px heading with support and Category selector.

**Avoid:** Do not replace the luminous background with a huge dashboard screenshot, left-right stock-photo hero or black gradient. Do not expand the headline to billboard scale or turn the opening into several disconnected cards.

**Text style:** `display` — STK Bureau Sans 500 · 56px/0.99 · tracking -0.025em

### Centered chapter pair

**Observed:** Within Heading measure, a centered heading is followed after 16px by a muted lead. Most section titles use heading; major commercial statements use heading-lg. About 80px separates the heading block from the next large framed module.

**Transfer:** Keep each chapter to one claim and one support sentence; allow long technical headings to balance over two lines.

**Text style:** `heading` — STK Bureau Sans 500 · 48px/1 · tracking -0.025em

### Annotated system proof

**Observed:** Centered chapter pair sits above Dotted global object. Two compact stat callouts overlap the illustration, and a three-column Benefit cell row forms its base.

**Transfer:** Use one intelligible visual system with a few truthful performance annotations, not a dashboard of unrelated numbers.

### Tabbed customer instrument

**Observed:** A centered quantified proof heading and short lead introduce Customer story panel. Customer story tab controls lead the panel, then a generous left-aligned quotation shares the inner stage with a customer mark. Additional logos continue below the panel.

**Transfer:** Quantified proof should set context, with a human quote explaining what that scale enables. Keep tab controls and pause affordance if the content rotates.

**Text style:** `quote` — STK Bureau Sans 500 · 29.4px/0.96 · tracking -0.025em

### Capability matrix

**Observed:** Technical frame contains three touching columns of icon, label and short body copy. Denser matrices sit inside a dashed near-white 12px-corner wrapper with an 8px-corner white inner frame. One bottom cell can hold Outline button actions rather than another capability.

**Transfer:** Adapt the row count to the product's substance, keeping all cells concise and aligned.

### Split demonstration

**Observed:** A Technical frame allocates roughly two thirds to an Interface vignette on a very pale patterned backing and one third to stacked text cells. Some demonstrations reverse the sides. Installation panels are centered and about 500px wide within the larger visual area.

**Transfer:** Show one meaningful task, command or API interaction, then explain three or four reasons it matters; preserve the imbalance between a large visual field and compact text.

### Capability mosaic

**Observed:** A 1200px framed mosaic mixes a wide workflow vignette with a narrower orange highlighted benefit. The next row reverses the weight. White cards use small 18px headings and compact body descriptions, with imagery held above or beside them.

**Transfer:** Use the orange tile for a unifying benefit and the white tiles for concrete tasks; keep the grid architectural, not a set of equally raised cards.

### Commercial comparison

**Observed:** Category selector precedes a compact introductory benefit or diagram, then touching price columns with 32px numerals and Outline button actions. Dedicated pricing pages use four smaller plan summaries and Comparison panel, followed by a three-column add-on matrix.

**Transfer:** Separate the pricing model explanation from detailed feature comparison; keep numbers plain rather than oversized.

**Text style:** `price-or-quote` — STK Bureau Sans 500 · 32px/1 · tracking -0.025em

### Product directory

**Observed:** Grouped capabilities use either three category columns of compact icon-plus-two-line links or a four-column catalog matrix. Catalog category captions are uppercase 13px with 0.025em tracking and sit 16px above the grid; categories are separated by 48px.

**Transfer:** Use the three-column directory for supporting breadth, and the four-column matrix only for an actual catalog.

### Luminous closing and white footer

**Observed:** Orange stage returns at 528px tall inside an 8px wrapper. The upper 472px contains Closing orbit tiles, a centered 56px display call, a white lead and Primary button plus Secondary stage button. The base carries a 56px-high horizontal proof ticker with small icons, white 16px text and a faint top rule. Footer link columns begin immediately below on white, followed by generous empty breathing space and a low copyright/privacy row.

**Transfer:** End with the same light-field material as the opening, a fresh action-oriented line and brief reassurance. Keep the ticker as a repeating product-proof device and preserve the light footer rather than ending in a dark contact band.

**Text style:** `display` — STK Bureau Sans 500 · 56px/0.99 · tracking -0.025em

## Page flow

**Storyline:** Promise → concrete system or workflow proof → capability chapters → customer validation → commercial or product breadth → luminous closing action → spacious white sitemap.

### Broad platform marketing landing page

1. **Promise** — Immersive orange light-field stage with one centered conversion.
2. **System proof** — Annotated dotted object and three-cell benefit strip.
3. **Social proof** — Quantified heading, customer story instrument and logo row.
4. **Differentiation** — Before-and-after signal contrast.
5. **Commercial model** — Segmented selector, model explanation and touching price columns.
6. **Capability chapters** — Asymmetric workflow mosaic with one orange unifying tile.
7. **Closing call** — Luminous stage, proof ticker and white footer.

**Transfer:** Use this as the default balance of broad promise, technical clarity and commercial reassurance.

### Technical solution landing page for a development workflow

1. **Promise** — White centered badge, 48px headline, compact support and three benefits.
2. **Product demonstration** — Pastel architecture diagram with editable-node styling.
3. **Capability chapters** — Three-column matrix, then split install-command demonstration.
4. **Social proof** — Freestanding 32px customer quote, followed by the tabbed proof instrument.
5. **Product breadth** — Three-column grouped directory.
6. **Closing call** — Shared orange light-field stage, proof ticker and white footer.

**Transfer:** Let the architecture diagram explain the workflow and use compact implementation material to reduce perceived effort.

### Technical solution landing page for a multi-step application system

1. **Promise** — White category badge, centered headline and three-cell benefit strip.
2. **Social proof** — Early freestanding customer quote.
3. **Capability chapters** — Centered proof headings and three-column capability matrix.
4. **Product demonstration** — Code vignette with side explanations, followed by a second installation-led chapter.
5. **Social proof** — Tabbed customer instrument.
6. **Product breadth** — Grouped category directory.
7. **Closing call** — Shared orange light-field stage, proof ticker and white footer.

**Transfer:** Use separate demonstration chapters for different user jobs instead of forcing every feature into one grand diagram.

### Pricing and plan decision page

1. **Commercial promise** — White 56px centered heading, short support and Category selector.
2. **Pricing** — Four equally weighted plan summaries above an accordion comparison.
3. **Expansion options** — Three-column add-on matrix with short prices and inline activation links.
4. **Social proof** — Shared customer instrument.
5. **Product breadth** — Grouped directory under a centered reliability statement.
6. **Closing call** — Shared orange light-field stage, proof ticker and white footer.

**Transfer:** Make tier differences scannable before adding proof and ecosystem breadth; avoid a promotional hero that delays the actual plans.

### Product discovery catalog

1. **Orientation** — White heading, concise description and long capsule category selector.
2. **Product breadth** — Uppercase category captions above four-column icon/title/description matrices.
3. **Closing call** — Shared orange light-field stage, proof ticker and white footer.

**Transfer:** Keep catalog entries short and consistently framed; do not append the full marketing narrative to every category.

## Writing

Confident and practical, with developer fluency but little ceremony. Large claims are followed by concrete operational benefits, recognizable tools or quantified proof.

**Do not copy:** Do not reuse Cloudflare's name, marks, product names, customer logos, quotations, market-share claims, network coverage numbers, prices or event announcements as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we or our when explaining the platform's own working experience. Actions start with verbs.
- **Rhythm:** Short sentence-case headings alternate with one- or two-sentence support. Technical descriptions can be longer but remain literal; em dashes and plus signs compress relationships without turning everything into slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A capability or earned advantage offered directly to the reader. | 2–16 words | “Everything we learned from powering 20% of the Internet—yours by default”<br>“Scale predictably” |
| Chapter heading | Short outcome or plain description of a system advantage. | 3–9 words | “Tailored to your team”<br>“Powerful primitives, seamlessly integrated” |
| Supporting line | Name the tools or scope, then remove an operational burden. | 12–30 words | “One platform for your apps, agents, and workforce. Build, secure, and scale without managing infrastructure.” |
| Capability description | Concrete action plus immediate result. | 10–25 words | “Create a pull request, get a preview URL to view and share before deploying to production.” |
| Primary action | Verb, task and low-risk qualifier. | 2–5 words | “Start building for free”<br>“View docs” |
| Closing call | A short expansive imperative, followed by practical reassurance. | 3–6 words | “Build without boundaries” |

**Words and phrasing to use:** build; deploy; scale; by default; one platform; without managing; built-in; global; primitives; workflows

**Avoid:** revolutionary; magical; game-changing; unleash your potential; vague superlatives; forced jokes

**Rules:**

- Lead with the reader's job, then explain the infrastructure that makes it easier.
- Pair a broad promise with a concrete mechanism or supported proof in the next block.
- Use actual tool names only when they clarify compatibility, not as decorative keyword lists.
- Keep CTA labels literal and concise; put reassurance in the adjacent support rather than crowding the button.

## Do's and Don'ts

### Do

- Keep the core display at 56px, weight 500 and -0.025em tracking.
- Use 1200px technical grids with zero gutters and 1px #f0f0f0 dividers.
- Leave 80px between narrative blocks while keeping card copy at 16px/1.2.
- Repeat the orange dotted light-field material at the closing call, including the 56px proof ticker.
- Use 50px white conversion pills on orange and compact 38px outlined pills on white.
- Put 14px junction squares on selected frame corners and grid intersections.
- Use one concentrated orange tile to unify an otherwise white capability mosaic.
- Preserve the white four-column footer with 32px column gaps and substantial lower breathing space.

### Don't

- Do not use heavy 700-weight headlines; their tone is broader and harsher than the 500-weight grotesk.
- Do not turn every grid cell into a 16px-rounded elevated card; touching technical cells remain square.
- Do not spread blue, teal and magenta across ordinary page sections; they belong to explanatory architecture graphics.
- Do not replace the near-white panel tint with a visibly dark gray slab.
- Do not give support paragraphs the same 48px scale as section headings.
- Do not make every CTA orange: the primary action on an orange stage is white.
- Do not substitute a big price numeral for the plan's actual description; the commercial scale is restrained at 32px or smaller.
- Do not use a black footer or let the last luminous panel become the final content edge.

## Motion and responsive

### Motion

**Observed:**

- Navigation transitions use 0.2s cubic-bezier(0.19, 1, 0.22, 1); primary capsule scale/translate transitions use 0.16s cubic-bezier(0.25, 0.46, 0.45, 0.94).
- Primary and outline capsule actions declare active scale 0.98.
- Story tabs declare border-color and color transitions at 0.2s cubic-bezier(0.19, 1, 0.22, 1). Customer stories include a pause control.
- Background-pulse is declared at 2s ease-in-out infinite; a footer wordmark slide is declared with auto duration and linear timing.

**Transfer:**

- Keep interaction changes small: color, border and a slight capsule press rather than large movement.
- Preserve pause control when rotating stories and logos; the light-field scene must also work as a static composition.

**Unknown:**

- Playback timing of the main background scene and the ticker's travel speed are not established.
- The full footer wordmark animation is not visually established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1536px.
- The opening headline uses left alignment on narrow layouts and centered alignment from the medium layout; the three-column benefit grid declares a single-column base.
- The closing actions declare a vertical base stack and a horizontal row from the small layout. Footer lists declare a two-column base within groups and four main columns at the large layout.

**Transfer:**

- On narrow screens, retain the orange stage's dot texture and bottom glow while placing headline, support and action in one left-aligned stack.
- Stack touching capability cells with horizontal dividers; keep diagram nodes readable by simplifying the scene rather than shrinking all annotations.
- Let long category selectors scroll horizontally rather than compressing their pill labels.

**Unknown:**

- Exact mobile type sizes, stage heights and observed breakpoint behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
