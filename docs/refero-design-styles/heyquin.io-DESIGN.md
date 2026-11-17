# Quin — paper, pinstripes and sunshine

## Overview

A warm, architectural style for products that make complicated work feel human and manageable. Cream paper, buttery yellow, pale cyan and deep brown alternate with near-black chapters; tightly set grotesk headlines sit above small technical monospace labels. Sunlit desk photography, real people and lightly staged interface fragments keep the spacious, ruled layouts tangible rather than futuristic.

### Essentials

- Big promises sit on paper, not in floating cards: centered 96px/1.1, weight 500 grotesk headlines with -3.2px tracking occupy a 650px text measure above a full-width media stage.
- The page behaves like a ruled working document: a centered 1280px frame, 1px edges, 24px internal insets and flush 1px-gutter grids continue through changes of background.
- Actions are rectangular blocks attached to the architecture: 64px height, 24px padding and uppercase 14px/1 monospace labels with 1.2px tracking; primary yellow sits beside a stone secondary action at the right of a striped rail.
- Color arrives by chapter rather than confetti: cream is the default opening and capability canvas, cyan carries big proof, yellow carries transformation and the closing call, brown and near-black form substantial contrasting chapters. Keep each chapter mostly one flat color, not a collection of tinted cards.
- Product proof lives in the physical world: wood-grain desks and daylight people photography occupy full-width stages or one half of a 1280px split, with sparse interface fragments layered over them. Where photography is unavailable, stage a real interface in a simple device on a warm wood backing.
- Pinstripe rails and registration-like square clusters are signature punctuation: repeat thin vertical rules across 64px or 160px bands, and use 48px square color blocks at media corners; carry both devices into a new page.
- End with a sunny architectural statement: a 600px-high product photograph meets an 80px/1.1 closing line in a 900px yellow panel flanked by pinstripes, then two equal 112px-high brown and cyan action blocks and a near-black directory footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sun yellow | `#f7cf49` | `--color-yellow` | background, accent, action, text | Primary actions, label tabs, benefit chapter and monumental close; inverse pricing accents. |
| Deep wood | `#492812` | `--color-wood` | background, action | Warm dark demonstration chapters and the left closing action. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky cyan | `#a9e1ff` | `--color-cyan` | background, surface, action | Large proof chapters, alternate actions and small registration blocks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#141414` | `--color-ink` | text, background, action | Default headlines and text; dark chapters and the footer. |
| Charcoal | `#222222` | `--color-text-secondary` | text | Navigation and FAQ text. |
| Graphite | `#545454` | `--color-graphite` | text, background | Muted tile labels and the compact comparison band. |
| Olive-gray rule | `#68655b` | `--color-dark-rule` | border | Edges and pinstripes on dark chapters. |
| Soft ink on paper | `#72716d` | `--color-muted-paper-text` | text | Visible result of ink at 60% opacity over cream, used for explanatory paragraphs. |
| Sand edge | `#a19c8c` | `--color-sand-edge` | border, background | Rules and 1px gutters in sand testimonial chapters. |
| Warm sand | `#d5d0c1` | `--color-sand` | surface, border | Testimonial chapters and secondary-button hover. |
| Soft ink edge | `#dcd9d1` | `--color-soft-ink-edge` | border | Visible ink at 15% over cream; use the alpha recipe for edges on colored chapters. |
| Light stone | `#f0ecdf` | `--color-stone` | surface, border | Secondary actions, pale demonstration backings and cream-section hairlines. |
| Cream paper | `#fffcf2` | `--color-canvas` | background, surface, text | Default canvas, grid cells and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| resource and subscription forms | Input white | `#ffffff` | `--color-white` | surface | Newsletter and resource-search inputs. |

## Typography

- **Instrument Sans Variable** — All marketing headlines, paragraphs, numbers and card titles. Open, slightly humanist grotesk with compact headline spacing and distinctive alternate letterforms. OpenType features: "kern", "ss01", "ss03", "ss05", "ss07", "ss08", "ss12". Font stack: "Instrument Sans Variable", Arial, sans-serif.
- **Geist Mono** — Navigation, chapter tags, action labels and footer directory. Light technical monospace, widely tracked capitals against the expressive large sans. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Instrument Sans Variable | 500 | 96px | 1.1 | -0.0333em | Default centered marketing promise. |
| closing-heading | Instrument Sans Variable | 500 | 80px | 1.1 | -0.016em | Monumental closing statement. |
| section-heading | Instrument Sans Variable | 500 | 56px | 1.1 | -0.0229em | Major chapter headings and full-size proof quotations. |
| heading | Instrument Sans Variable | 500 | 44px | 1.25 | -0.0182em | Split-feature headings, integration lead and enterprise offer. |
| quote-card | Instrument Sans Variable | 500 | 32px | 1.25 | -0.0025em | Short quotations in three-column proof cards. |
| subheading | Instrument Sans Variable | 500 | 28px | 1.25 | -0.003em | Capability and scenario titles and calculator prompt. |
| hero-support | Instrument Sans Variable | 400 | 20px | 1.35 | normal | Two-line support below the main centered promise. |
| tile-label | Instrument Sans Variable | 400 | 20px | 1.25 | normal | Capability navigation tiles. |
| body | Instrument Sans Variable | 400 | 16px | 1.5 | normal | Chapter support, feature descriptions and attributions. |
| closing-action | Geist Mono | 400 | 16px | 1 | 0.075em, uppercase | Equal-width closing actions and final app strip. |
| button | Geist Mono | 400 | 14px | 1 | 0.086em, uppercase | Standard rail actions. |
| eyebrow | Geist Mono | 400 | 12px | 1 | 0.1em, uppercase | Colored chapter tags and compact navigation action. |
| navigation | Geist Mono | 400 | 12px | 1 | 0.107em, uppercase | Desktop navigation links. |
| footer-link | Geist Mono | 300 | 12px | 1.1 | 0.2em, uppercase | Directory links in the dark footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing offers | price-number | Instrument Sans Variable | 400 | 96px | 1 | -0.0133em | Large price numeral with smaller currency mark and mono period label. |
| audience, use-case and resource pages | secondary-hero | Instrument Sans Variable | 500 | 64px | 1.1 | -0.025em | Split audience or capability opening, and centered resource heading. |
| pricing, audience, use-case and resource pages | secondary-support | Instrument Sans Variable | 400 | 20px | 1.5 | normal | Longer opening support on secondary pages. |
| pricing FAQs | faq-title | Instrument Sans Variable | 500 | 20px | 1.35 | normal | Question text on compact stone chips. |
| audience pages | feature-body | Instrument Sans Variable | 400 | 18px | 1.5 | normal | Explanations in alternating feature and scenario rows. |
| resource libraries | story-title | Instrument Sans Variable | 500 | 18px | 1.25 | normal | Compact resource-card headlines. |
| resource libraries and enterprise offers | story-description | Instrument Sans Variable | 400 | 14px | 1.5 | normal | Resource-card summaries and small enterprise support. |

**Notes:**

- Headlines use weight 500, never heavy bold; prices use 400. The 96px opening has tighter tracking than the 56px chapter scale.
- Sans support is commonly ink at 0.6 opacity; maintain full-strength headline ink. Use opacity on text only, not its whole parent.
- Mono labels stay uppercase and airy. Navigation, tags and footer links have distinct tracking and weights rather than one universal small-text recipe.
- Use fixed desktop recipes as the baseline; no viewport sizing formula is prescribed.

## Layout

**Density:** Airy chapter headers contrast with flush, tightly ruled grids; empty space is structural rather than card padding inflation.

### Spacing

| Value | Use |
| --- | --- |
| 1px | Grid gutters and chapter edges. |
| 8px | Icon-to-action and small text-stack gaps. |
| 16px | Card title support gaps and resource-grid gutters. |
| 24px | Standard inner inset and main button padding. |
| 28px | Chapter header stack gap. |
| 32px | Outer section side padding and footer directory row spacing. |
| 48px | Compact chapter padding and closing-action vertical padding. |
| 64px | Action rails, feature separators and calculator section padding. |
| 80px | Centered hero vertical padding. |
| 96px | Major chapter vertical padding and footer internal rhythm. |
| 160px | Deep pinstripe punctuation between chapters. |

### Containers and grids

- **page-frame**: max width 1280px · side padding 32px. Centered ruled frame on a full-width canvas; at 1440px the frame leaves 80px each side. Internal content usually has another 24px inset.
- **hero-measure**: max width 650px. Centered main headline and supporting copy.
- **chapter-measure**: max width 800px. Centered supporting content and FAQ region; narrower chapter headings often use 560px.
- **split-stage**: 2 columns · gap 1px. Equal halves of the 1280px frame, around 639px each; one photograph or demonstration and one text panel.
- **capability-grid**: 4 columns · gap 1px. Flush capability navigation, with 319px-wide cells and icon above bottom-aligned label.
- **proof-grid**: 3 columns · gap 1px. Three equal quotation panels, approximately 426px wide.
- **resource-grid** (only for resource libraries): 3 columns · gap 16px. A 978px resource pane next to an approximately 302px navigation sidebar; 299px cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing panels and actions | 0px |
| centered customer quotation | portrait avatar | 50% |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing canvas and capability tiles.

**CSS:** `background: #fffcf2; color: #141414`

**Observed:** Thin stone frame lines continue through the opening and capability areas.

**Transfer:** Let the page frame, rather than raised cards, organize the content.

#### Stone panel · level 0

**Use:** Secondary actions, media backing and subscription chapter.

**CSS:** `background: #f0ecdf; border-radius: 0px; box-shadow: none`

**Observed:** A slight paper-tone change, not a raised layer.

**Transfer:** Use for quiet technical demonstrations and support areas.

#### Cyan proof band · level 0

**Use:** Large testimony and measured outcomes.

**CSS:** `background: #a9e1ff; color: #141414; border-top: 1px solid rgba(20,20,20,0.15)`

**Observed:** Either a full-width centered quotation or a split quotation-plus-device scene.

**Transfer:** Give one compelling proof statement a whole color field.

#### Sand proof field · level 0

**Use:** Three-column customer proof chapter.

**CSS:** `background: #d5d0c1; border-top: 1px solid #a19c8c; border-bottom: 1px solid #a19c8c`

**Transfer:** Carry the sand fill across header and cards, with slightly darker seams.

#### Yellow chapter · level 0

**Use:** Benefit transformation and closing conversion.

**CSS:** `background: #f7cf49; color: #141414`

**Observed:** Full-width color surrounds the continuing ruled container.

**Transfer:** Use yellow at chapter scale, balanced by cream and substantial dark fields.

#### Wood chapter · level 0

**Use:** Cross-channel demonstration and warm dark media staging.

**CSS:** `background: #492812; color: #fffcf2`

**Transfer:** Pair this solid brown with warm physical product photography.

#### Ink chapter · level 0

**Use:** Resource stories, pricing variant and footer.

**CSS:** `background: #141414; color: #fffcf2; border-color: #68655b`

**Transfer:** Invert text and rules together; keep the same square architecture.

#### Pinstripe rail

**Use:** Action rails, chapter punctuation and flanks of the closing statement.

**CSS:** `background-image: repeating-linear-gradient(90deg,rgba(20,20,20,0.15) 0px,rgba(20,20,20,0.15) 1px,transparent 1px,transparent 14px); overflow: hidden`

**Observed:** Thin parallel vertical lines, not crosshatching. Lines become olive gray on dark fields.

**Transfer:** Retain a repeated linear texture even where there is no media.

## Components

### Navigation

**Use:** Persistent site-level orientation.

**CSS:** `position: sticky; background: #fffcf2; border-bottom: 1px solid #f0ecdf; padding: 0px 32px; height: 89px; z-index: 9999`

**Text style:** `navigation` — Geist Mono 400 · 12px/1 · tracking 0.107em · uppercase

**Observed:** A left symbol and wordmark balance a right-aligned compact menu and 44px-high stone action. The inner 1280px frame has side rules and 24px insets. Navigation text begins at 0.7 opacity.

**States:** Declared: hover links reach opacity 1 and become underlined with 10px underline offset; active outline 0px.

**Transfer:** Keep the main navigation visually secondary to the large promise.

### Primary button

**Use:** Main conversion action on a standard rail.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 8px; background: #f7cf49; color: #141414; padding: 24px; height: 64px; border-radius: 0px`

**Text style:** `button` — Geist Mono 400 · 14px/1 · tracking 0.086em · uppercase

**Observed:** A small right arrow follows the label. Buttons meet edge-to-edge with the secondary action, aligned to the right end of a striped rail. Cyan is the alternate for secondary-page openings and security actions.

**States:** Declared: hover background #141414 and color #fffcf2; hover and active outline 0px; transition 0.2s.

**Transfer:** Keep width content-driven; preserve the rectilinear paired-action construction.

### Secondary button

**Use:** Demo or consultative action beside the primary action.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 8px; background: #f0ecdf; color: #141414; padding: 24px; height: 64px; border-radius: 0px`

**Text style:** `button` — Geist Mono 400 · 14px/1 · tracking 0.086em · uppercase

**Observed:** Same attached block construction as the primary action. The small navigation variant uses 16px 20px padding, 44px height and the eyebrow recipe.

**States:** Declared: hover background #d5d0c1 and color #141414; focus-visible outline rgb(77,101,255) solid 2px with 2px offset; transition 0.2s.

### Chapter tag

**Use:** Short categorical label above major headings.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #f7cf49; padding: 6px 12px; gap: 8px; border-radius: 0px`

**Text style:** `eyebrow` — Geist Mono 400 · 12px/1 · tracking 0.1em · uppercase

**Observed:** The tag hugs the text; it is not a pill. Cyan tags appear on yellow chapters, and dark tags on cyan proof fields.

### Capability tile

**Use:** Scan-friendly entry to a product capability.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #fffcf2; padding: 24px; height: 213px; border-radius: 0px`

**Text style:** `tile-label` — Instrument Sans Variable 400 · 20px/1.25

**Observed:** Small monochrome icon at upper left, label near the bottom. Four columns sit on a stone backing visible only through 1px seams.

**Transfer:** Use a concise situation or work-area label, not a paragraph in every tile.

### Quotation card

**Use:** Compact human proof in a three-column band.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 64px; background: #d5d0c1; padding: 24px; height: 360px`

**Text style:** `quote-card` — Instrument Sans Variable 500 · 32px/1.25 · tracking -0.0025em

**Observed:** A small quote mark sits above the statement. A 48px portrait, name and role anchor the bottom. All three cards share the sand field and darker seams.

**Transfer:** Use actual short testimony; give attribution its own lower baseline.

### Closing action block

**Use:** Two equal actions below the monumental closing panel.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 8px; background: #492812; color: #fffcf2; padding: 48px 24px; height: 112px`

**Text style:** `closing-action` — Geist Mono 400 · 16px/1 · tracking 0.075em · uppercase

**Observed:** The left block is deep brown with cream type; the right is cyan with ink type. Together they fill the 1278px inner frame with no gap.

**States:** Declared: hover background #141414 and color #fffcf2; focus-visible outline rgb(77,101,255) solid 2px with 2px offset; transition 0.2s.

**Transfer:** Scale the action area to the architecture, rather than placing two small buttons beneath the close.

### Footer link

**Use:** Right-aligned directory rows on the ink field.

**CSS:** `color: #fffcf2; opacity: 0.6; text-transform: uppercase`

**Text style:** `footer-link` — Geist Mono 300 · 12px/1.1 · tracking 0.2em · uppercase

**Observed:** Category names sit at left; links wrap in an 800px right-side measure with slash separators, 16px row gaps and 10px column gaps. Directory rows are separated by 32px of space.

**States:** Declared: hover opacity 1; hover and active outline 0px; transition 0.2s.

### Final utility strip

**Use:** Full-width action at the bottom of the directory.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; background: #f7cf49; color: #141414; padding: 24px; height: 72px`

**Text style:** `closing-action` — Geist Mono 400 · 16px/1 · tracking 0.075em · uppercase

**Observed:** A small platform icon precedes the centered label. A 160px dark pinstripe band finishes the page beneath it.

**States:** Declared: hover background #a9e1ff and color #141414; hover and active outline 0px.

**Transfer:** Use an equivalent product-access or utility action when no app exists.

### FAQ chip

**Only for:** pricing FAQs

**Use:** Conversational objection handling.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #f0ecdf; padding: 12px 20px; border-radius: 0px`

**Text style:** `faq-title` — Instrument Sans Variable 500 · 20px/1.35

**Observed:** Questions occupy content-width stone chips, not full-width filled bars. A small outlined plus is detached to the left. The containing row is 83px high with a 16px gap.

**Transfer:** Let varied question lengths create a natural staggered right edge.

### Story card

**Only for:** resource libraries

**Use:** Customer video and editorial listing.

**CSS:** `display: flex; flex-direction: column; background: #fffcf2; border: 1px solid #f0ecdf; height: 400px; border-radius: 0px`

**Text style:** `story-title` — Instrument Sans Variable 500 · 18px/1.25

**Observed:** A 297px by 167px thumbnail sits above the text block. Titles, 14px descriptions and a small uppercase arrow link sit in an approximately 20px inset, with the action aligned toward the bottom.

**States:** Declared: hover border-color #d5d0c1 and background-color #f0ecdf; hover and active outline 0px; transition 0.2s.

### Subscription input

**Only for:** resource and subscription forms

**Use:** Simple name and email collection.

**CSS:** `background: #ffffff; border: 1px solid rgba(46,46,46,0.2); padding: 10px 12px 10px 16px; height: 62px; border-radius: 0px`

**Observed:** Two equal white inputs sit in a horizontal row with a dark submit block and 16px gaps, on a stone chapter.

**Transfer:** Keep forms planar and simple; avoid floating-label ornament.

## Imagery and graphics

### Warm physical product stage

**Use:** Main opening object, large demonstration splits and the closing photograph.

**Observed:** Real tablets, laptops and phones rest on golden wood desks. Close angled views crop device edges confidently; daylight sweeps across wood grain. Cyan interface light contrasts with warm brown surroundings. Images are flush to the frame without rounded marketing-card masks.

**Transfer:** Photograph the new interface on a real device in warm natural light. The minimum version is a clean device mockup on a well-lit wood photograph; retain convincing perspective and a legible primary screen.

### Human scene with interface overlay

**Use:** Transformation chapter and audience-focused split stage.

**Observed:** People converse across a bright table, framed tightly at human eye level with daylight windows and soft foreground occlusion. One or two translucent white interface fragments float across the photo, sometimes fading at the bottom. A fine noise overlay softens the composite.

**Transfer:** Choose a real activity relevant to the new product, not a posed handshake. Overlay one useful output with restrained translucency so faces and the task remain visible.

**Build:** Place the photograph with object-fit: cover in one 639px-wide half. Overlay a white interface panel across roughly 70% of that half, centered below mid-height, with a soft bottom opacity mask. Add a repeating 60px noise tile at opacity 0.4 and mix-blend-mode: overlay; create the tile with SVG feTurbulence. Keep the noise subtle, not visibly distressed.

### Registration square cluster

**Use:** Corners of media stages and selected transitions.

**Observed:** A compact two-by-two cluster of 48px squares mixes yellow, cyan, ink and sand; some cells visually merge into the backing. It looks like print registration rather than an illustrative icon.

**Transfer:** Repeat this small geometric punctuation with the new imagery.

**Build:** Use a 96px square CSS grid with two 48px columns and rows, gap 0px. Fill two or three cells with yellow, cyan or ink, letting the remaining cell match the background. Anchor to a media corner and clip flush to its boundary.

### Isolated workflow illustration

**Only for:** audience and use-case detail pages

**Use:** Feature rows and a focused secondary-page opening.

**Observed:** Sparse white interface fragments and occasional tactile objects such as paper notes sit in a 639px square stone panel. Small connected logos, message cards, checkmarks and a cyan focal item explain one operation at a time. The illustration occupies most of its panel but keeps substantial empty backing.

**Transfer:** Show a single input-to-output relationship from the new product, not its entire dashboard.

**Build:** Center two to four simplified interface fragments in a stone square. Use white rectangles, faint stone outlines, short gray lines, restrained cyan emphasis and thin orthogonal connectors. For integration diagrams, distribute small square logo tiles around a cyan central disc; do not spread these graphics into the marketing text area.

### Portrait video thumbnail

**Only for:** resource libraries

**Use:** Customer-story card media.

**Observed:** Landscape black thumbnails combine a cutout portrait on the left and a white short outcome line on the right. Cyan caption strips and small corner blocks repeat the graphic system; photographs retain natural skin tones.

**Transfer:** Use genuine contributors, a brief outcome and the same simple black/cyan editorial framing.

**Build:** Make a 16:9 dark rectangle. Place the portrait across the left third, a short light sans heading at right and a shallow cyan name strip along the lower edge; add tiny registration squares at one corner. Keep the thumbnail readable at about 297px wide.

### Icons

**Observed:** Small functional monochrome symbols accompany capabilities and actions. Standard icons are 24px, arrows 16px and dropdown chevrons 12px; larger channel symbols can be 40px. Thin outline-like forms dominate the visual appearance, with filled SVG arrows and marks.

**Transfer:** Use simple consistent functional symbols in ink or cream; keep arrows small and inline. Reserve colored logos for product demonstrations and integration rows.

## Section recipes

How recurring sections are built.

### First screen: Paper promise and product stage

**Observed:** The first 900px contains a 48px yellow announcement strip, the 89px cream Navigation, and a centered promise block with 80px vertical breathing room. The two-line headline fills a 650px measure in display typography; a two-line hero-support paragraph follows after 24px. The text block finishes above a 64px Pinstripe rail whose right end contains Secondary button and Primary button, edge-to-edge. A broad wood-backed product scene begins directly below the rail, around 650px down the first viewport, so its upper connected-tool objects are visible before the fold while most of the device remains below it. Back-to-front layers are cream canvas, continuous stone frame, restrained striped rail, attached actions, then the warm photographic stage and sparse interface objects.

**Transfer:** Make the new promise equally compact and centered, then reveal the top of a real product scene below the action rail. With no finished photography, use a device mockup and warm wood backing rather than replacing the stage with a generic floating dashboard. Secondary audience and use-case pages open in equal text/media halves with secondary-hero typography; pricing keeps the centered display promise but moves straight into the calculator; resource libraries use a sidebar and centered 64px introduction.

**Avoid:** Do not center loose pill buttons directly beneath the paragraph, fill the opening with yellow, or shrink the product stage to a small card beside the default hero.

**Text style:** `display` — Instrument Sans Variable 500 · 96px/1.1 · tracking -0.0333em

### Chapter heading stack

**Observed:** Chapter tag, section-heading and body support form a 28px-gap stack inside 96px vertical padding and 24px internal side insets. Centered variants use a 560px to 800px measure; left-aligned variants open wider capability chapters. Background and frame continue uninterrupted into the material below.

**Transfer:** Use a short category, one benefit statement and one compact explanation. Alignment follows whether the next content is a centered proof field or a practical grid.

**Text style:** `section-heading` — Instrument Sans Variable 500 · 56px/1.1 · tracking -0.0229em

### Ruled capability matrix

**Observed:** Four-column Capability tiles share stone 1px gutters and a cream fill. A larger two-column continuation pairs an image with a stone summary and attached action.

**Transfer:** Organize the offering by recognizable situations; keep tile labels brief so the spacious icon-to-label construction survives.

### Cyan quote and stats split

**Observed:** Cyan proof band splits into equal halves: a section-heading-scale quotation and attribution at left, a tall angled device photograph at right. Two 56px figures sit below the quote in ruled columns; labels explain the units in body typography. An attached action rail closes the band.

**Transfer:** Use a verified quote and two clearly labeled outcomes; preserve the outsized quote rather than turning the proof into many badges.

### Yellow benefits with live panel

**Observed:** Yellow chapter holds a full-height human photograph in the left half and a heading stack plus benefit accordion in the right. The right panel uses 24px inner inset and 96px vertical rhythm. Active text is dark with a small minus, 50px ruled option rows follow, and the explanatory paragraph sits beneath the active title.

**Transfer:** Use a small set of benefits mapped to matching imagery or outputs; the active explanation should show a concrete change in the user's day.

### Dark editorial and channel chapters

**Observed:** Ink chapter presents a centered heading stack above a nearly full-frame people photograph, then thin-bordered horizontal resource rows. Wood chapter uses a similar header above five equal channel tabs, one yellow active cell and a full-width phone photograph.

**Transfer:** Use the dark fields for deeper material or cross-channel reach. Keep the same frame and rail grammar rather than introducing elevated dark cards.

### Sand testimony triptych

**Observed:** Sand proof field starts with the Chapter heading stack and continues into three Quotation cards separated by 1px sand-edge seams. Small portraits and attributions align across the bottom.

**Transfer:** Three independent short voices create a broad proof chapter; reduce the number for less material without changing the card construction.

### Sunny closing architecture

**Observed:** A full-width Yellow chapter within the continuing frame begins with a 1278px by 600px photograph of a tablet on wood, accented by Registration square cluster. Below it, a centered 900px yellow panel uses 96px top and bottom padding around a two-line closing-heading. Vertical pinstripes flank the panel and thin ink-alpha rules frame it. Two Closing action blocks fill the next row, brown left and cyan right. A 50px yellow ruled spacer separates this from the footer.

**Transfer:** Give the new product a confident, short final promise and a tangible product view; if there is no physical object, put its main interface into a device scene. Keep the striped flanks and wide actions even when the wording changes.

**Text style:** `closing-heading` — Instrument Sans Variable 500 · 80px/1.1 · tracking -0.016em

### Directory footer and final stripe

**Observed:** The Ink chapter footer is bounded by olive-gray frame rules. A 96px inset rhythm separates five directory rows from a bottom identity/social row. Category labels align left while slash-separated links align right. Final utility strip spans the inner frame, followed by a dark 160px Pinstripe rail at the absolute ending.

**Transfer:** Map categories to the new information architecture while preserving the unusually wide rows, small mono type and bright final strip.

### Illustrated feature and scenario rows

**Only for:** audience detail pages

**Observed:** Feature rows alternate text and 639px square stone illustrations in equal columns, using heading and feature-body typography. Later scenario rows use a 400px square media cell and a wider explanation. Cyan portrait-and-quote ribbons about 184px tall sit directly under individual scenarios. Pinstripe separators punctuate the sequence.

**Transfer:** Explain how work changes, then attach testimony at the point it supports. Use the square isolated workflow illustrations rather than repeated full-dashboard views.

### Calculator and enterprise offer

**Only for:** pricing offers

**Observed:** A centered 480px calculator asks a subheading-size question above a thin 448px slider with small ticks and a square handle. A 96px price numeral appears in a flat filled header, with currency and period around it. A short icon-led list and a filled inclusion strip finish the card. On an ink chapter the accents and card border are yellow; the dedicated pricing variant is cream with stone fills and cyan slider handle. A broad enterprise row uses heading typography, concise support, two benefits and an outlined action.

**Transfer:** Tie the price to a meaningful usage variable, retain the single focal card, and make enterprise a horizontal alternate path rather than another competing plan column.

### Resource library and subscription

**Only for:** resource libraries

**Observed:** A persistent narrow sidebar contains a white search input and uppercase category links; the selected link is a stone rectangle. In the wider pane, a centered secondary-hero introduction leads to a three-column 16px-gap Story card grid. After the library a full-frame stone subscription chapter has a centered heading, two Subscription inputs and dark submit action.

**Transfer:** Use this denser variant only for browsable content. Keep the marketing close outside the sidebar layout.

## Page flow

**Storyline:** promise → recognizable work → concrete demonstration → human and quantified proof → deeper capabilities or objections → monumental closing call → utility directory

### Broad product marketing landing page

1. **promise** — Centered oversized promise, right-attached action rail and warm physical product stage.
2. **capability overview** — Left-led chapter heading and flush four-column situation tiles.
3. **social and quantified proof** — Large cyan quote/device split with two figures, followed by an integration strip.
4. **transformation** — Yellow benefit accordion paired with a real human scene.
5. **depth and trust** — Dark editorial material, sand testimony, wood channel demonstration and cream security chapter.
6. **commercial decision** — Graphite comparison punctuation and ink pricing calculator with enterprise path.
7. **closing call** — Sunny closing architecture, directory footer, yellow utility strip and final dark pinstripes.

**Transfer:** Adapt the middle chapters to the product's strongest evidence; keep the paper opening, physical proof, ruled color chapters and expressive ending.

### Pricing and purchase confidence

1. **promise** — Centered 96px free-trial promise with support and attached paired actions.
2. **pricing** — Light calculator, one focal price and broad enterprise row.
3. **objection handling** — Centered FAQ chapter lead and content-width question chips.
4. **closing call** — Sunny product photograph and closing architecture, then the complete directory and striped ending.

**Transfer:** Use the light pricing variant for focused comparison and objections, not the full dark marketing chapter.

### Audience-specific product explanation

1. **relevance** — 64px split opening with human scene and an integration/action rail.
2. **problem recognition** — Centered context statement over five icon-led pain tiles.
3. **mechanism** — Alternating square illustrated feature rows.
4. **benefits and proof** — Ink outcome/device split followed by sand testimony.
5. **scenarios** — Wider concrete scenario rows with cyan testimonial ribbons.
6. **capability depth** — Two-column illustrated feature panels.
7. **closing call** — Shared yellow close, full directory, utility strip and pinstripe bottom.

**Transfer:** Make this variant specific through actual workflows and language, not a changed audience noun alone.

### One capability explained end to end

1. **promise** — 64px split headline with sparse stone-backed interface illustration.
2. **capabilities** — Centered chapter lead and two-by-two benefit cards with wide secondary actions.
3. **demonstration** — A centered product view on deep brown.
4. **onboarding** — Sand step accordion with square numerals and a large device photograph.
5. **social proof** — Full-width cyan quotation with centered portrait attribution.
6. **audience relevance** — Ink split chapter with human photograph and role accordion.
7. **closing call** — Yellow close uses a shorter 80px invitation plus support; complete directory and final stripe follow.

**Transfer:** Explain one task through benefits, setup and proof without reproducing the entire general landing page.

### Browsable proof and editorial library

1. **orientation** — Sidebar search and categories beside centered 64px introduction.
2. **proof collection** — Three-column customer video cards with portrait thumbnails and outcome summaries.
3. **retention** — Stone subscription chapter with simple white input row.
4. **closing call** — Full-width yellow close leaves the sidebar behind; dark directory, utility strip and bottom pinstripes finish.

**Transfer:** Keep denser browsing and forms within this scoped variant, while restoring the broad brand architecture at the end.

## Writing

Confident, conversational and practical. The product sounds like a capable colleague who knows the small chores that consume a working day; benefits are described as relief and follow-through rather than technological spectacle.

**Do not copy:** Do not reuse Quin's name, symbol, proprietary artwork, customer names or quotations, prices, savings figures, certifications, integration claims or performance promises. Source examples illustrate voice only; replace them with substantiated content for the new product.

- **Addressing the reader:** Speak directly to you and your team. Refer to the product by name as the active subject; explain what it handles and what remains in the user's control.
- **Rhythm:** Headlines usually use 4–10 plain words, sometimes a compact contrast. Support is one or two short sentences; mechanism copy can list three concrete verbs. Sentence fragments work for tags and benefits, while quotations may be more expressive.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A simple desirable state or a contrast between meaningful work and friction. | 5–9 words | “Your dream assistant is here”<br>“Run your firm, not the paperwork”<br>“Stop drafting emails from scratch” |
| Supporting line | Name what the product does, then where the recovered effort goes. | 20–40 words | “[Brand] runs the work behind your work. The hours that used to disappear into admin go back to growing your business.” |
| Chapter headline | Describe a daily change in ordinary language, often with a concrete place or moment. | 5–12 words | “The day you'd have if admin ran itself”<br>“Wherever you work, [Brand]'s already there” |
| Mechanism | Short active clauses explain output and human control. | 20–50 words | “[Brand] drafts and waits. You see what's been handled, what's queued for your review, and what's already gone out. The judgment calls stay yours.” |
| Primary action | A direct verb plus a clear next step; offer reassurance only when factual. | 2–4 words | “Try [Brand] Free”<br>“See for yourself” |
| Story title | Outcome framed as less overhead or more room for valuable work. | 5–9 words | “Full pipeline with zero admin backlog”<br>“Scaling your business without extra spend” |

**Words and phrasing to use:** handles; runs; drafts; review; follow-through; your day; already there; off your plate; the work behind your work

**Avoid:** revolutionary; cutting-edge; unprecedented; synergize; AI-powered everything; frictionless ecosystem

**Rules:**

- Write about recognizable moments and outputs before explaining technology.
- Make the user's retained judgment explicit when the product acts on their behalf.
- Use contractions and plain verbs; keep section labels functional rather than poetic.
- Put evidence next to the claim it supports, with units and attribution.
- Let large typography carry the drama; keep the prose grounded.

## Do's and Don'ts

### Do

- Keep default hero type at 96px/1.1 and weight 500, within a 650px centered measure.
- Continue the 1280px ruled frame across color changes.
- Use 1px seams for flush capability and proof grids, with 24px cell insets.
- Attach 64px rectangular actions to striped rails rather than floating them.
- Use 96px chapter padding and a 28px heading-stack rhythm.
- Stage product proof against warm wood or a real daylight working scene.
- Preserve yellow closing architecture, 900px headline panel and 112px action blocks.
- Make the final footer action a 72px bright strip above dark pinstripes.

### Don't

- Do not replace the cream canvas with pure white across the page; white belongs to inputs and depicted interfaces.
- Do not add rounded marketing panels or pill buttons; the standard radius is 0px.
- Do not add card drop shadows; separation comes from flat fills and 1px rules.
- Do not make every section a different pastel card grid; color belongs to entire chapters.
- Do not use weight 700 for the large headlines or price numeral.
- Do not set body paragraphs in the tracked uppercase monospace used for labels.
- Do not turn a three-panel sand proof band into detached white review cards.
- Do not enlarge tiny navigation text to compete with the 56px chapter hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Standard actions, cards and footer links declare 0.2s transitions.
- Word-level heading spans have blur and translation transforms resolving to blur(0px) and translate(0px, 0px).
- Benefit, channel and numbered-step sections present a single active panel with the other labels visually subdued.

**Transfer:**

- Keep color swaps and opacity changes on the square action blocks and links.
- For a progressive headline reveal, settle to fully crisp dark type; do not leave readable content permanently blurred.

**Unknown:**

- Specific headline reveal duration, easing and trigger sequence are not established.
- Automatic panel cycling and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 768px, 991px and 1440px; resource pages also declare 992px.

**Transfer:**

- On narrow screens, retain the frame-and-rail grammar with slimmer side gutters; stack equal text/media halves rather than shrinking their contents beyond legibility.
- Collapse capability and resource grids into fewer columns, keeping square corners and hairline seams.
- Keep the closing statement between stripe accents and let the two wide actions stack when needed.
- Turn the library sidebar into a compact category control before the card grid.

**Unknown:**

- Exact mobile typography, gutter values, navigation behavior and image reordering are not established; these transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
