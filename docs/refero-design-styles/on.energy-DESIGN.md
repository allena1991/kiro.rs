# ON.energy — industrial voltage cinema

## Overview

A cinematic industrial style that makes complex infrastructure feel tangible and consequential. Black and charcoal stages, pale grotesk typography and sudden electric-yellow fields balance technical seriousness with unmistakable energy. Monumental monochrome product renders dominate the spacious marketing experience, while compact editorial and engineering chapters provide denser proof.

### Essentials

- The product is the architecture of the opening: a full-bleed 900px monochrome stage, a close-up object extending beyond the frame, a left-aligned 64px/72px light headline and small support copy at the bottom.
- Typography feels machined but exceptionally light: Univers Next Pro at weight 300, with -0.04em tracking on 64px, 48px, 36px and 24px headings; equipment-like mono labels use 12px/20px with -0.04em tracking.
- Yellow arrives as an interruption, not a decorative wash: #fff313 fills a near-screen-height statement and the closing panel, while black and #202020 dominate the longer product narrative and #eeeeee isolates editorial proof.
- Actions are tiny rectangular controls against monumental scenes: navigation is 28px tall with 6px corners, primary black contact buttons are 40px tall with 4px corners, and labels are 12px mono rather than oversized pill text.
- Proof is staged as a spacious object: 676×451px charcoal cards with 56px corners and 48px padding, 120px weight-250 numbers high on the right, and explanatory text low on the left.
- A technical dot language and an oversized closing identity anchor the experience: small dotted symbols, a dotted proof graphic, and a black identity mark about 404×191px inside a yellow panel over a 96px circle-and-square grid. Use a new product's own abstract mark and a dotted capability diagram when equivalent imagery is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric yellow | `#fff313` | `--color-yellow` | accent, surface, action, text | Statement fields, closing panel, small calls to action and selected technical values. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-canvas` | background, text, action | Default page canvas, text on yellow and pale surfaces, and black controls. |
| Charcoal | `#202020` | `--color-panel` | surface, background, text | Stat cards, capability bands and dark text in light testimonial sections. |
| Technical grid gray | `#323232` | `--color-grid` | border, text | Closing backdrop circle and square lines; active navigation text. |
| Dark gray | `#4b4b4b` | `--color-rule` | text, border | Editorial row separators and subdued large statement continuations on black. |
| Graphite text | `#7d7d7d` | `--color-muted` | text | Supporting feature descriptions, roles and secondary metadata. |
| Navigation silver | `#a8a8a8` | `--color-nav-text` | text | Default translucent navigation labels over the cinematic scene. |
| Silver | `#afafaf` | `--color-secondary` | text | Large proof numerals, mono section labels and secondary text on charcoal. |
| Pressed gray | `#cdcdcd` | `--color-hover` | surface, text | Active navigation fill and editorial row hover fill. |
| Pale white | `#eeeeee` | `--color-text` | text, background | Primary light text and full-width editorial proof bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical proof charts | Measurement cyan | `#00ddff` | `--color-cyan` | accent | Contrasting measured series in technical proof charts only. |
| technical explainers and problem statements | Muted yellow | `#c0b400` | `--color-olive` | text, accent | Section labels on pale technical bands and muted yellow statement continuations. |
| technical proof charts | Instrument navy | `#0a1a2a` | `--color-chart` | surface | Live-data chart backing within the marketing document, not the general page canvas. |
| technical explainers | Technical near black | `#080808` | `--color-technical-canvas` | background, text | Engineering document dark bands and text on its light bands. |
| technical explainers | Technical gray | `#585858` | `--color-technical-muted` | text, border | Small engineering card descriptions and dashed reference lines. |
| technical explainers | Technical silver | `#b8b8b8` | `--color-technical-body` | text | Engineering prose on dark backgrounds. |
| technical explainers | Card white | `#ffffff` | `--color-white-card` | surface | Compact technical cards on the pale document bands. |

## Typography

- **Univers Next Pro** — All large headlines, prose, numbers and navigation labels. Light, neutral neo-grotesk with narrow, open forms and tightly packed large lettering. If unavailable, use **Roboto**. Use weights 300 and 400; tune line breaks to retain the light, compact silhouette. Font stack: "Univers Next Pro", "Roboto", Arial, sans-serif.
- **ABC Monument Grotesk Mono** — Section labels and contact controls. Small utilitarian monospace, contrasting with the flowing light grotesk. If unavailable, use **IBM Plex Mono**. Use 400 for labels and 600 for compact navigation actions. Font stack: "ABC Monument Grotesk Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat | Univers Next Pro | 250 | 120px | 1 | -0.08em | size 8.33333vw | Heroic numerals in large proof cards. |
| display | Univers Next Pro | 300 | 64px | 1.125 | -0.04em | fixed | Default cinematic headline and text-led service or company opening. |
| statement | Univers Next Pro | 300 | 48px | 1.167 | -0.04em | fixed | Wide statement paragraphs and major editorial section labels. |
| heading | Univers Next Pro | 300 | 36px | 1.167 | -0.04em | size clamp(3rem, 2.5vw, 2.5vw) | Secondary section headings and oversized footer navigation. |
| stat-unit | Univers Next Pro | 300 | 36px | 1 | -0.04em | size 2.5vw | Small units aligned near the top of large numerals. |
| lead | Univers Next Pro | 300 | 24px | 1.167 | -0.04em | size clamp(2rem, 1.66667vw, 1.66667vw) | Feature titles, testimonials, featured article titles and closing invitation. |
| body-large | Univers Next Pro | 300 | 20px | 1.2 | -0.02em | size clamp(1.6rem, 1.38889vw, 1.38889vw) | Short feature descriptions and proof-card labels. |
| body | Univers Next Pro | 300 | 16px | 1.375 | -0.02em | fixed | Proof-card paragraphs, news rows and people metadata. |
| eyebrow | ABC Monument Grotesk Mono | 400 | 12px | 1.67 | -0.04em, uppercase | fixed | Small section labels, generally with a tiny dot before the words. |
| navigation | Univers Next Pro | 400 | 12px | 1 | normal | fixed | Top bar category labels. |
| button | ABC Monument Grotesk Mono | 400 | 12px | 1.67 | -0.04em | fixed | Black contact and contextual buttons. |
| button-compact | ABC Monument Grotesk Mono | 600 | 12px | 1 | normal | fixed | Yellow navigation conversion button. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| technical explainers | technical-display | Univers Next Pro | 300 | 96px | 0.95 | -0.04em | size clamp(48px, 7vw, 96px) | Three-line document title with a yellow trademark accent. |
| technical explainers | technical-heading | Univers Next Pro | 300 | 51.2px | 1.1 | -0.04em | size clamp(32px, 4vw, 51.2px) | Numbered engineering chapter headings. |
| technical explainers | technical-stat | Univers Next Pro | 300 | 44.8px | 1 | -0.03em | size clamp(32px, 3.5vw, 44.8px) | Yellow values in compact left-ruled proof cards. |
| technical explainers | technical-subheading | Univers Next Pro | 300 | 28.8px | 1.1 | -0.04em | size clamp(20.8px, 2.5vw, 28.8px) | Proof-chart introductions and explanatory subheads. |
| technical explainers | technical-card-title | Univers Next Pro | 600 | 17.6px | 1.1 | -0.04em | fixed | Compact challenge-card headings. |
| technical explainers | technical-body | Univers Next Pro | 400 | 15.2px | 1.6 | -0.013em | fixed | Long-form engineering prose. |
| technical explainers | technical-small | Univers Next Pro | 400 | 13.6px | 1.6 | -0.015em | fixed | Technical card descriptions and comparison rows. |
| technical explainers | technical-eyebrow | Univers Next Pro | 400 | 12px | 1.6 | 0.15em | fixed | Number, em dash and uppercase chapter name. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The dominant contrast is between exceptionally light large grotesk text and compact mono labels, not between bold and regular headings.
- Large prose shares the headline's tight -0.04em tracking; ordinary paragraphs relax to -0.02em. Stat numerals tighten further to -0.08em.
- Keep heading and supporting continuation visually connected: pale lead phrases can flow directly into darker gray continuation text on black.
- Fluid rem minima use a 10px root basis. Preserve the authored formulas rather than treating the desktop size as a universal fixed size.

## Layout

**Density:** Airy cinematic marketing with long visual pauses; compact technical documents keep prose and comparison data more tightly grouped.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Dominant vertical rhythm for repeated padding and gaps; exceptions such as 60px feature row gaps remain intentional.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Tight control and label gaps. | fixed |
| 16px | Primary grid gutter and card-to-card gap. | 1.11111vw |
| 24px | Feature title-to-copy separation and technical grid gutters. | fixed |
| 32px | Section-label stacks, control separation and compact technical card padding. | fixed |
| 36px | Desktop marketing side inset. | fixed |
| 48px | Large proof-card padding and statement heading separation. | 3.33333vw |
| 60px | Feature and people-grid row gaps. | fixed |
| 96px | Vertical padding of technical chapter bands. | fixed |
| 120px | Vertical padding of editorial and capability bands. | fixed |
| 200px | Separation between service chapters and large closing breathing space. | fixed |
| 277px | Vertical space around the wide yellow manifesto. | fixed |

### Containers and grids

- **marketing grid**: 24 columns · gap 16px · side padding 36px. Fluid 1368px content width at a 1440px viewport. Divide into equal halves for major proof and editorial content; right-half-only blocks deliberately leave the left half open.
- **proof grid**: 2 columns · gap 16px. Two 676px proof cards per row at desktop. A service opening uses one card on the upper right and two below.
- **feature grid**: 2 columns · gap 16px. A 676px right-half container subdivided into 330px feature cells, with 60px vertical gaps.
- **document container** (only for technical explainers): max width 1136px · side padding 32px. Centered engineering content within full-width alternating bands.
- **document card grid** (only for technical explainers): 3 columns · gap 24px. Compact technical challenges; four-column rows serve shorter metric or economic summaries.
- **people grid** (only for company and culture pages): 4 columns · gap 16px · side padding 36px. Four 330px portraits per row, 60px between rows.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | navigation | 6px |
|  | black buttons | 4px |
|  | proof cards | 56px |
|  | closing panel | 24px |
|  | editorial media | 32px |
| company and culture pages | portrait | 16px |
| technical explainers | technical panels | 12px |
| recruiting sections | recruiting action | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default canvas behind cinematic media and sparse capability sections.

**CSS:** `background: #000000; color: #eeeeee`

**Observed:** The scene can fade seamlessly into this canvas; no raised-card shadow system is used.

**Transfer:** Let the object and lighting create depth instead of adding UI elevation.

#### Charcoal band · level 0

**Use:** Capability chapters and supporting dark proof.

**CSS:** `background: #202020; color: #eeeeee`

#### Pale editorial band · level 0

**Use:** Testimonials and news.

**CSS:** `background: #eeeeee; color: #000000`

**Observed:** Entire sections invert together rather than placing a white card on every item.

#### Yellow statement · level 1

**Use:** A high-impact manifesto or problem statement.

**CSS:** `background: #fff313; color: #000000`

**Observed:** A nearly full-screen field with broad multiline type. The panel develops visibly rounded corners as it moves through the page.

**Transfer:** Use one consequential paragraph, not a collection of small promotional cards.

#### Closing yellow panel · level 1

**Use:** Shared closing invitation and navigation.

**CSS:** `background: #fff313; color: #000000; border-radius: 24px; padding: 40px 20px 20px`

**Observed:** Inset 16px from the page edges; the patterned black surround remains visible.

#### Engineering light card · level 1

**Only for:** technical explainers

**Use:** Small explanatory cards on a pale document band.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.08); border-radius: 12px; padding: 32px`

#### Instrument panel · level 1

**Only for:** technical proof charts

**Use:** Wide live-data plots.

**CSS:** `background: #0a1a2a; border-radius: 12px; overflow: hidden`

**Observed:** Fine dark grid, cyan and yellow traces, small axis labels and legends sit below the plot.

#### Technical closing call · level 1

**Only for:** technical explainers

**Use:** Focused engineering inquiry before the shared footer.

**CSS:** `background: #202020; border: 1px solid rgba(255, 243, 19, 0.15); border-radius: 12px; padding: 48px`

**Observed:** A thin yellow-to-transparent line follows the top edge; heading, paragraph and yellow action align left.

## Components

### Glass navigation item

**Use:** Persistent top category navigation.

**CSS:** `background: rgba(167, 167, 167, 0.2); color: #a8a8a8; border-radius: 6px; backdrop-filter: blur(20px); padding: 0px 14px; height: 28px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — Univers Next Pro 400 · 12px/1

**Observed:** A small identity tile leads a row of five equal flexible category cells and a compact contact control. Tiny chevrons sit on the right. The bar is fixed 16px from the top with 15px side insets and 4px gaps; on lighter sections the labels and backing adjust for contrast.

**States:** Declared: hover background-color #eee and color #000; focus-visible outline 1px dashed #fff313 with 3px offset; active background-color #cdcdcd and color #323232.

### Compact yellow action

**Use:** Conversion control at the end of the top bar.

**CSS:** `background: #fff313; color: #000000; border-radius: 6px; padding: 0px 17px; height: 28px`

**Text style:** `button-compact` — ABC Monument Grotesk Mono 600 · 12px/1

**Observed:** The action is deliberately no taller than the adjacent navigation cells.

**States:** Declared: hover background-color #000 and color #fff313; focus-visible outline 1px dashed #fff313 with 3px offset.

### Black contact button

**Use:** Contact action on the yellow closing field and contextual editorial actions.

**CSS:** `background: #000000; color: #fff313; border-radius: 4px; height: 40px; padding: 0px 24px; backdrop-filter: blur(32px); display: flex; align-items: center; justify-content: center`

**Text style:** `button` — ABC Monument Grotesk Mono 400 · 12px/1.67 · tracking -0.04em

**Observed:** A separate backing and energy-stream layer sit behind the label. The contextual editorial variant uses pale text.

**States:** Declared: hover box-shadow rgba(255, 243, 19, 0.3) 0px 0px 20px and color #000; focus-visible outline 1px dashed #000 with 3px offset.

### Proof card

**Use:** Major quantified proof.

**CSS:** `background: #202020; border-radius: 56px; padding: 48px; display: flex; flex-direction: column; position: relative; overflow: hidden`

**Text style:** `stat` — Univers Next Pro 250 · 120px/1 · tracking -0.08em

**Observed:** A 676×451px desktop card puts the numeral at the upper right, its unit aligned high. Body-large label and body paragraph occupy the lower left; prose is limited to about 300px. Some cards replace the numeral with dotted iconography or a dotted geographic diagram.

**Transfer:** Use only substantiated numbers; keep the same visual weight when replacing geography with a relevant dotted network.

### Footer navigation row

**Use:** Large index links in the closing panel.

**CSS:** `border-bottom: 1px solid rgba(0, 0, 0, 0.4); padding: 5px 0px; color: #000000; display: flex; align-items: center; justify-content: space-between`

**Text style:** `heading` — Univers Next Pro 300 · 36px/1.167 · tracking -0.04em

**Observed:** Seven 676px-wide desktop rows sit in the right half of the closing panel, followed by small social marks.

**States:** Declared: hover opacity 1 while ancestor-hover dims sibling rows to 0.5; focus-visible outline 1px dashed #000 with 3px offset.

### Editorial news row

**Use:** Compact updates beneath featured stories.

**CSS:** `border-bottom: 1px solid #4b4b4b; padding: 24px 0px; display: flex; align-items: center; gap: 16px; color: #000000`

**Text style:** `body` — Univers Next Pro 300 · 16px/1.375 · tracking -0.02em

**Observed:** Title occupies the left half; date starts at the midpoint and the Read more label with a tiny diagonal arrow is right aligned. Row height grows with wrapping rather than clipping.

**States:** Declared: hover background-color #cdcdcd; focus-visible outline 1px dashed #fff313 with 3px offset.

### Featured story

**Use:** Image-led editorial proof on a pale band.

**CSS:** `display: flex; flex-direction: column; gap: 33px`

**Text style:** `lead` — Univers Next Pro 300 · 24px/1.167 · tracking -0.04em

**Observed:** Two equal columns pair 676×450px images with 32px corners. Beneath each image, a narrow uppercase metadata column sits beside the title and short body excerpt.

**Transfer:** Keep the image dominant and the text factual rather than turning this into a heavy boxed card.

### People portrait

**Only for:** company and culture pages

**Use:** Leadership or expert directory.

**CSS:** `border-radius: 16px; overflow: hidden; position: relative`

**Observed:** 330×414px grayscale portraits use a light studio background, cropped near the waist. A 28px yellow dotted plus sits at the lower right. Name and subdued role appear below the image with a 16px gap.

**States:** Declared: focus-visible outline 1px dashed #fff313 with 3px offset; image filter transition 0.2s.

**Transfer:** Use consistent portrait framing and lighting, with meaningful biography controls rather than ornamental plus signs.

### Technical challenge card

**Only for:** technical explainers

**Use:** Dense explanatory requirement grids.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.08); border-radius: 12px; padding: 32px`

**Text style:** `technical-card-title` — Univers Next Pro 600 · 17.6px/1.1 · tracking -0.04em

**Observed:** A small outline symbol in a 40px tinted circle precedes the title; technical-small copy follows with 12px separation. Dark process-card variants use charcoal backing and pale titles.

### Technical metric tile

**Only for:** technical explainers

**Use:** Short proof rows after comparisons or validation.

**CSS:** `background: #202020; border-left: 2px solid #fff313; border-radius: 0px 8px 8px 0px; padding: 24px`

**Text style:** `technical-stat` — Univers Next Pro 300 · 44.8px/1 · tracking -0.03em

**Observed:** Four equally sized tiles sit across the document width, with a yellow value above a small uppercase description. A validation variant rounds all corners to 12px.

## Imagery and graphics

### Monochrome industrial cinema

**Use:** Opening scene and immersive product demonstration.

**Observed:** Low-angle close-up hardware fills the viewport, cropped beyond the top and right edges. Brushed silver faces, black vents, sharp edge highlights and deep shadows make the object nearly architectural. Later views pull back to a centered object and repeated rows on a dark floor lit by a broad white pool; supporting copy stays small and low.

**Transfer:** Use a desaturated render or photograph of the new product with hard edge lighting and a black vignette. For software or services, construct a tangible abstract system of layered slabs or modules, not a floating colorful dashboard.

**Build:** Stage a monochrome object on a black plane; light its upper-left edges and place a broad low white light beneath it. Add a black bottom gradient behind the caption. Minimum version: one high-resolution grayscale cutout, large enough to bleed offscreen, with a soft elliptical floor light and dark vignette.

### Dotted technical symbols

**Use:** Feature symbols, proof graphics and small directional marks.

**Observed:** Small pale dot matrices form technical pictograms; a larger geographic outline is made of evenly spaced dots with a few brighter location points. Dotted plus signs accompany thin oversized numerals.

**Transfer:** Use the same dot construction for the new product's distribution, process or capability diagram.

**Build:** Create an SVG pattern of evenly spaced small circles in silver, clipped to a custom silhouette. Place several larger pale points within it; for small symbols arrange dots into simple arrows, plus signs or component outlines. Keep them unshaded and monochrome against charcoal.

### Closing identity and engineering grid

**Use:** Signature closing artwork.

**Observed:** An oversized black identity symbol occupies the lower left of the yellow panel. Behind the panel, thin gray circles fit inside a square grid, fading into charcoal toward the bottom.

**Transfer:** Use the new product's own compact mark or a typographic monogram at comparable scale; preserve the patterned surround.

**Build:** Tile 96×96px SVG cells with a 1px square outline and a centered circle of 47px radius, both in #323232 over black. Overlay a bottom fade using rgba(32,32,32,0.8). Place an approximately 404×191px black mark in the panel's lower-left zone.

### Field and editorial photography

**Use:** Deployment proof and featured news.

**Observed:** Natural-color equipment and construction photography contrasts with the monochrome product stage. Broad landscape frames show the working context, sky and surrounding ground rather than isolated sales cutouts; featured images use 32px corners.

**Transfer:** Show the actual product in operation with restrained natural color and documentary lighting.

### People photography

**Only for:** company and culture pages

**Use:** Company opening, directory and recruiting context.

**Observed:** Full-width warm office photographs show people collaborating or sitting informally; these alternate with consistent grayscale studio portraits and a smaller grayscale field-work image.

**Transfer:** Pair authentic workplace color photography with rigorously consistent monochrome directory portraits.

### Isometric system explainer

**Only for:** immersive educational pages

**Use:** Long-form challenge-to-solution demonstration.

**Observed:** A white technical landscape carries gray isometric buildings, black outlines and long solid black shadows. Fine hatch and dot textures mark the ground. Black challenge panels turn yellow for solutions; highlighted routes connect the system while small black tags identify parts.

**Transfer:** Illustrate the new product's ecosystem as simple connected isometric blocks. Keep the visual world monochrome and reserve yellow for the successful state.

**Build:** Build SVG parallelogram ground tiles and extruded cuboids with three gray face tones, thin black edges and offset solid black shadow polygons. Add sparse line hatching and dot patterns. Route pale-to-bright yellow bands between nodes and float compact black annotation panels above the scene. A static before/after pair is the minimum acceptable version.

### Instrument data plots

**Only for:** technical proof charts

**Use:** Measured comparisons and engineering validation.

**Observed:** Wide navy panels contain fine grid lines, cyan and yellow traces, restrained filled areas, tiny axes and legends. Multiple charts stack vertically with controls below; these read as instruments, not decorative sparklines.

**Transfer:** Use authentic new measurements, retaining a stable contrasting reference trace and explicit axes.

**Build:** Draw a rectangular grid at low white opacity over navy; plot thin cyan and yellow SVG polylines inside padded axes. Clip translucent fills below selected series and position labels outside the plotting region.

### Icons

**Observed:** Dot-matrix symbols dominate features and plus controls. Small filled social icons are black in the yellow footer; technical cards use simple 22px outline pictograms in tinted circular backings.

**Transfer:** Use a coherent dotted symbol set for marketing; restrict conventional outline icons to compact technical cards. Avoid oversized colorful icon badges.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product opening

**Observed:** A 900px-tall black stage carries edge-to-edge grayscale hardware, then the small fixed Glass navigation item row above it. The object fills most of the view and bleeds out of frame, leaving the two-line display headline on the left at roughly mid-height. A short body caption sits near the lower-left corner. A compact yellow product teaser with a thumbnail occupies the lower right. All these elements are visible in the first 900px; the yellow statement begins below the fold. There is no large centered headline or central button stack.

**Transfer:** Make the main object visually overwhelming while keeping text calm and left aligned. Without product photography, use the layered monochrome module scene described in Monochrome industrial cinema. Text-led service and company variants begin with the same 64px headline after about 337px of black space, followed by staggered proof cards or full-width people photography. Technical documents instead use the scoped technical-display title beside a smaller dark product rendering and a compact metric strip.

**Avoid:** Do not replace the scene with a centered SaaS hero, bright gradient illustration, or a white card containing a miniature product image.

**Text style:** `display` — Univers Next Pro 300 · 64px/1.125 · tracking -0.04em

### Yellow manifesto

**Observed:** A nearly viewport-height Yellow statement contains a wide 48px paragraph with 36px side insets and about 277px of breathing room above and below. The problem-led variant adds a small uppercase label 48px above the text and distinguishes the leading phrase from its muted continuation.

**Transfer:** State one consequential proposition in connected prose. Keep the color interruption and typographic scale, but vary its position to suit the story.

**Text style:** `statement` — Univers Next Pro 300 · 48px/1.167 · tracking -0.04em

### Right-half capability chapter

**Observed:** A large left-hand void balances content in the right 676px half. A 2×2 feature grid uses small dotted symbols, lead titles, body-large descriptions and 60px row gaps. Related heading-pair chapters put a mono label over a pale heading and a subdued continuation.

**Transfer:** Use the empty half to slow the narrative or hold a product detail, without filling it with unrelated cards.

**Text style:** `heading` — Univers Next Pro 300 · 36px/1.167 · tracking -0.04em

### Immersive demonstration

**Observed:** A full-screen dark product scene changes from close-up to whole unit to repeated deployment. Educational variants use the Isometric system explainer with a persistent annotation panel and successive challenge and solution states.

**Transfer:** Explain one mechanism through a few comprehensible changes of scale or state. A static sequence can preserve the same visual logic without an elaborate scene engine.

### Editorial testimonial

**Observed:** Pale editorial band with 120px vertical padding. A 48px section label sits in the left half; a 24px quote fills the right half above the customer mark, small attribution, Black contact button variant and compact stacked carousel controls.

**Transfer:** Keep the quote as proof, not as a decorative oversized quotation mark. A dark specialist variant uses two smaller logo-and-quote columns inside the right half.

**Text style:** `lead` — Univers Next Pro 300 · 24px/1.167 · tracking -0.04em

### Quantified proof field

**Observed:** Proof cards form a two-column grid with 16px gaps. Large upper-right numerals balance lower-left labels; dotted diagrams can replace a numeral. A text-led service variant staggers the first card to the right before filling both columns.

**Transfer:** Choose a small set of consequential metrics and one nonnumeric capability illustration. Preserve spacious card internals.

**Text style:** `stat` — Univers Next Pro 250 · 120px/1 · tracking -0.08em

### Editorial news field

**Observed:** A pale band carries a 48px title and short introductory line, then two Featured story components and an Editorial news row list. The whole section has 120px top space and 240px closing space.

**Transfer:** Offer two image-led proof stories followed by a quieter list of updates; adjust quantity to actual content.

**Text style:** `statement` — Univers Next Pro 300 · 48px/1.167 · tracking -0.04em

### Yellow closing index

**Observed:** Closing yellow panel sits within the patterned black surround, with a 24px invitation and Black contact button in the upper left, Footer navigation rows in the right half, an oversized identity mark in the lower left, and legal details along the lower right. Panel height is 694px at desktop, leaving 160px of patterned tail below. This same ending follows every page type. Technical documents add their own Technical closing call before it.

**Transfer:** Retain the bright closing field, practical contact language, oversized own-brand mark and index hierarchy even on a short page.

**Text style:** `lead` — Univers Next Pro 300 · 24px/1.167 · tracking -0.04em

### Partner wall

**Only for:** institutional service pages

**Observed:** A 36px heading aligns to the right half above a grid of charcoal square tiles with generous rounded corners. White monochrome logos are centered; incomplete rows remain left aligned and distinct partner categories are separated by 200px.

**Transfer:** Group equivalent proof institutions or integrations by role and normalize logo scale without forcing every row to be full.

**Text style:** `heading` — Univers Next Pro 300 · 36px/1.167 · tracking -0.04em

### People and culture chapter

**Only for:** company and culture pages

**Observed:** Text-led opening gives way to full-width workplace photography, a 48px mixed-tone statement, then a 36px directory heading and four-column People portrait grid. A later full-width color image separates directory from recruiting content; a small field portrait balances right-half principles and a yellow pill recruiting action.

**Transfer:** Use this variant for human credibility rather than transferring the directory to every product page.

**Text style:** `heading` — Univers Next Pro 300 · 36px/1.167 · tracking -0.04em

### Technical chapter

**Only for:** technical explainers

**Observed:** Centered 1136px document container inside alternating near-black, charcoal and pale bands, each padded 96px vertically. A tracked numbered technical-eyebrow precedes technical-heading, followed by restrained 15.2px prose, comparison tables, three-column Technical challenge cards or four-column Technical metric tiles. Light and dark tables use faint 1px row rules and 16px 20px cell padding.

**Transfer:** Use numbered chapters when readers need to evaluate mechanism, requirements, validation and economics. Keep the dense document variant distinct from the cinematic marketing default.

**Text style:** `technical-heading` — Univers Next Pro 300 · 51.2px/1.1 · tracking -0.04em

### Technical validation

**Only for:** technical explainers

**Observed:** A wide field photograph is followed by short prose, compact yellow metrics and a Why This Matters subhead. Instrument panels show stacked real-data traces with legends, explanatory captions and small reset or zoom controls.

**Transfer:** Pair each technical claim with its measurement context and an interpretation, not a graph alone.

**Text style:** `technical-subheading` — Univers Next Pro 300 · 28.8px/1.1 · tracking -0.04em

## Page flow

**Storyline:** Tangible promise → consequential context → mechanism or capability → validated proof → human or editorial credibility → direct contact and a bright closing index.

### Flagship marketing landing page

1. **Promise** — Full-viewport grayscale product close-up and left headline.
2. **Context** — Yellow manifesto at oversized paragraph scale.
3. **Product demonstration** — Immersive hardware sequence moves from detail to system scale.
4. **Capabilities** — Right-half dotted feature grid and dark heading pairs.
5. **Social proof** — Light testimonial interlude.
6. **Quantified proof** — Oversized charcoal proof cards.
7. **Editorial credibility** — Pale news field with featured media and compact rows.
8. **Closing call** — Yellow closing index over the technical grid.

**Transfer:** Use cinematic media as the through-line, with a yellow statement and bright closing identity as punctuation rather than making every section visually loud.

### Service and institutional credibility page

1. **Promise** — Text-led 64px headline on black with staggered large metric cards.
2. **Capabilities** — Wide mixed-tone statement and right-half dotted capability grid.
3. **Institutional proof** — Grouped monochrome partner tiles with large gaps.
4. **Closing call** — Shared yellow closing index.

**Transfer:** Replace the main visual spectacle with consequential metrics and institutional proof while keeping the black-space asymmetry.

### Company and recruiting page

1. **Introduction** — Sparse title followed by full-width collaborative workplace photography.
2. **Positioning** — Large mixed-tone statement.
3. **Human credibility** — Four-column grayscale portrait directory.
4. **Culture** — Full-width informal workplace image and right-half principles.
5. **Conversion** — Small field image beside a recruiting action.
6. **Closing call** — Shared yellow closing index.

**Transfer:** Show real people with disciplined portrait consistency, then use warmer documentary photography for culture.

### Educational product narrative

1. **Problem promise** — Dark isometric product scene with left headline and low caption.
2. **Context** — Yellow problem statement.
3. **Mechanism** — Long isometric challenge-to-solution world with black-to-yellow annotations.
4. **Quantified proof** — Right-half deployment heading followed by large proof cards.
5. **Social proof** — Right-half customer quotes.
6. **Validation** — Two large field-photo deployment cards with oversized labels.
7. **Closing call** — Shared yellow closing index.

**Transfer:** Explain the new product's ecosystem through consistent visual states; do not reproduce the original subject matter or scroll duration.

### Engineering evaluation and technical sales document

1. **Promise** — 96px three-line title on near-black, product render and metric strip.
2. **Executive summary** — Numbered heading and concise problem-to-solution prose.
3. **Requirements** — Pale band with compact challenge cards.
4. **Mechanism** — Comparison tables and yellow metric tiles.
5. **Validation** — Field test context and measured data charts.
6. **Architecture and economics** — System diagram, structured specification rows and economic cards.
7. **Objection handling** — Standards listed in three categories.
8. **Conversion** — Compact proof tiles and a bordered technical inquiry panel.
9. **Closing call** — Shared yellow closing index.

**Transfer:** Scope the denser type, numbered chapters, navy plots and smaller corners to serious evaluation content, not ordinary marketing pages.

## Writing

Confident, technically literate and materially grounded. Claims are stated directly and supported by operating context, measured performance or named validation; the contact language becomes warmer and simpler.

**Do not copy:** Do not reuse ON.energy identity artwork, product names or trademarks, partner logos, customer quotations, certification claims, financial totals, performance figures or deployment claims. Create original content and use only substantiated facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly product-led or first-person plural for capability and culture; address the reader directly in contact and recruiting invitations.
- **Rhythm:** Short noun-led headlines contrast with broad, connected explanatory sentences. Labels are terse; supporting prose commonly uses one or two factual sentences without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | State the capability and its consequential application with a compact line break. | 4–9 words | “Grid-Safe Power for AI Factories.”<br>“Financial Engineering & Structured Capital” |
| Supporting line | Define what the product does and the two sides of the problem it addresses. | One sentence, about 15–30 words | “Built with Tier-1 components backed by 20-year warranties.” |
| Section heading | Concrete capability, validation or outcome rather than a playful slogan. | 3–7 words | “Performance Proven at Scale”<br>“Modular Design at Any Scale” |
| Proof label | Number plus operational qualifier; make the basis of the number clear. | 4–9 words | “3 GW+ Operating & Under Construction” |
| Primary action | Plain invitation or specific next step. | 2–4 words | “Get in touch”<br>“Explore Open Roles” |
| Closing invitation | Acknowledge complexity, then make contacting the team feel uncomplicated. | Two or three short sentences | “Energy is complicated. Reaching us isn’t. Contact the ON team anytime.” |
| Culture | Concrete working expectations, with compact contrasts and verbs. | One short claim followed by explanatory prose | “We move fast, debate hard, and learn from each other.” |

**Words and phrasing to use:** built; validated; deployed; proven; operating; integrated; resilience; scale; designed system; real-world conditions

**Avoid:** magic; game-changing; effortless everything; revolutionary without proof; cute technical puns; vague superlatives

**Rules:**

- Pair strong adjectives with a mechanism, qualification or measurement.
- Name the practical benefit before explaining technical implementation.
- Use uppercase for compact labels, not long headlines.
- Use parallel noun phrases for feature titles and direct verbs for culture.
- Keep contact copy plain and human after technical sections.

## Do's and Don'ts

### Do

- Preserve the 64px light opening headline and allow the product object to dominate the 900px stage.
- Align major text to the 36px marketing inset and maintain 16px primary gutters.
- Use 56px corners and 48px padding for the large proof cards.
- Keep 120px numerals high on the right and short explanatory text low on the left.
- Let #fff313 occupy complete statement and closing fields rather than scattering unrelated yellow cards.
- Use 120px band padding and 200px chapter gaps to create deliberate pauses.
- Carry the dot-matrix symbol language into at least one original capability or proof graphic.
- Retain the 24px rounded closing panel and oversized own-brand identity artwork.

### Don't

- Do not make every heading bold; weights 250–300 carry the dominant scale.
- Do not replace the 28px segmented navigation with a tall opaque toolbar.
- Do not turn all actions into pills; the pill treatment belongs to recruiting.
- Do not add drop shadows to every charcoal card; depth belongs to the product lighting.
- Do not use navy, cyan or multicolor data traces as general marketing accents; they belong to technical plots.
- Do not give ordinary feature lists the technical document's three-column white-card treatment.
- Do not center every chapter; right-half-only content and substantial left voids are characteristic.
- Do not reduce proof cards to dense KPI widgets with the label crowded beside the number.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares background-color and color transitions of 0.2s; compact contact controls declare 0.3s.
- Black contact buttons declare box-shadow and color transitions of 0.6s; footer rows declare opacity and border-color transitions of 0.15s.
- Portrait images declare filter transitions of 0.2s. Technical cards declare border-color and transform transitions of 0.3s.
- Product sequences change camera scale and scene composition as the page progresses; the yellow statement changes its corner treatment during movement.

**Transfer:**

- Keep the scenic movement tied to explanation: product detail to whole object to repeated system, or challenge state to resolved state.
- Use the declared small-control transitions without making the entire page bounce like an interface demo.

**Unknown:**

- Exact scroll choreography, scene durations, reveal triggers and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Shared CSS has width breakpoints at 833px, 834px and 1024px; technical content also declares 600px, 700px, 900px, 1000px and 1100px.
- Several sizes and spaces are viewport-relative, including 8.33333vw stat numerals and 3.33333vw proof-card padding.

**Transfer:**

- On narrow layouts, stack proof cards and move right-half narrative content into the main reading column while preserving its order and dark breathing space.
- Keep the product stage as a dominant image, with headline and caption in readable zones rather than shrinking the entire desktop composition.
- Let the closing invitation, index and large identity mark stack; preserve the yellow panel and patterned tail.

**Unknown:**

- Actual mobile compositions, navigation expansion behavior and minimum scenic heights are unknown; the stacking rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
