# Browserbase — pixel terrain and gridlines

## Overview

A light, engineering-minded style with a playful, early-computing edge. White space, pale blue drafting lines and black grotesk typography are interrupted by orange-red highlights, pastel proof strips and intensely dithered landscapes. It suits developer platforms and technical products that need to feel both dependable and unusually alive; diagrams and simplified interfaces carry the detail while pixel-treated imagery supplies the spectacle.

### Essentials

- Headlines behave like highlighted statements, not oversized posters: gtPlanar 45px/1.15, weight 500, -0.02em in the opening; recurring headings use 36px/1.05 and -0.01em. White lettering sits on orange-red, line-shaped rectangles in the main opening.
- The opening is a landscape stage: a 1312px-wide, 710px-tall scene carries a centered 555px text lockup above a low, jagged, dithered panorama. Keep the headline, support and paired actions fully visible before the first proof strip.
- Actions are small capsules against rectilinear architecture: 99px corner radius, plain 16px/1 at weight 500, 14px 18px padding and an 8px pair gap. The primary is black, not orange; declared hover makes its corners square.
- Color has assigned territories: white dominates the reading sections, orange-red marks short phrases and the full-width 571px footer, and pastel blocks carry numbers. Neon color belongs in pixel art and tiny grid markers rather than broad reading surfaces.
- Technical imagery reads like a pale blueprint: square-edged browser schematics, fine blue-gray rules, faded interface blocks and a few orange pointers. Pair this with a coarse, limited-color landscape or physical-object image; if no product artwork exists, dither a relevant landscape or object and draw a simple workflow in SVG.
- Grid interruptions and monumental proof are signature devices: use a 102px ruled strip with 13 cells and small colored bars, plus a prominent proof scene with a 104px-class number on a blue-gray text-width backing. A four-cell pastel strip uses 36px numerals and 14px uppercase mono captions.
- The ending is a graphic brand field, not a dark utility tail: an orange-red full-width surface holds an oversized white identity mark on the left and four black link columns on the right, with small social and legal links below.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orange-red | `#ff4500` | `--color-accent` | accent, background, text, border | Line-shaped headline highlights, selected heading words, diagram pointers, code edges and the footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal cyan | `#00b0ff` | `--color-grid-cyan` | accent | Short solid bar inside the ruled interruption strips. |
| Signal blue | `#0000cd` | `--color-grid-blue` | accent | Small square or bar inside the ruled interruption strips. |
| Proof pink | `#ffc0cb` | `--color-stat-pink` | surface | One cell of pastel proof strips and occasional small grid marks. |
| Proof blue | `#c4edff` | `--color-stat-blue` | surface | Pale cyan proof cell and technical text markers. |
| Proof yellow | `#fffde6` | `--color-stat-yellow` | surface | Pale yellow proof cell and small inline markers. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, border | Headings, body copy, primary capsules and occasional strong outlines. |
| Drafting blue-gray | `#c5d3e8` | `--color-rule` | border, surface | Page rails, dividers, secondary sales capsules and the backing behind monumental proof numbers. |
| Feature rail | `#d3deed` | `--color-feature-rule` | border | Slightly lighter 2px rule above short demonstration explanations; secondary button hover fill. |
| Warm gray text | `#686562` | `--color-muted` | text | Paragraphs under cards, longer supporting copy and secondary text. |
| Warm divider | `#e5e4e2` | `--color-soft-edge` | border | Accordion and comparison-row separators. |
| Setup capsule | `#e1e9f2` | `--color-setup-fill` | action | Utility action paired with the main opening CTA. |
| Proof gray | `#e2e9f3` | `--color-stat-gray` | surface | Cool neutral proof cell. |
| Warm logo paper | `#f8f7f4` | `--color-logo-paper` | surface | Subtle rectangular logo cells. |
| Diagram paper | `#f8fafc` | `--color-diagram-paper` | surface | Almost-white backing beneath large system maps. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default reading canvas; inverse text on black actions and orange-red title highlights. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| testimonial-led industry pages | Quote lime | `#e1eb80` | `--color-quote-lime` | surface | Alternative line-by-line quote highlight. |
| testimonial-led industry and pricing pages | Quote magenta | `#ffbaff` | `--color-quote-magenta` | surface | Rectangular line-by-line highlight behind a centered customer statement. |
| pricing pages and technical diagrams | Cool gray canvas | `#f0f4f8` | `--color-cool-canvas` | background | Extended pricing-page canvas and pale interface backing. |
| developer integration sections | Code blush | `#fff8f6` | `--color-code-paper` | surface | Very pale warm code-panel backing. |

## Typography

- **gtPlanar** — Headings and proof numbers. Compact contemporary grotesk with firm, rounded forms; medium rather than heavy display weight. If unavailable, use **DM Sans**. Use weights 400–500 and preserve the tight heading tracking. Font stack: "gtPlanar", "DM Sans", system-ui, Arial, sans-serif.
- **plain** — Body, card titles, navigation and capsule actions. Direct, readable grotesk with slightly open tracking and an unornamented technical tone. If unavailable, use **Inter**. Use weights 400–500; keep body tracking slightly positive. Font stack: "plain", "Inter", system-ui, Arial, sans-serif.
- **gtStandardMono** — Uppercase captions, compact action links, technical lists and code. Small utilitarian monospace that gives labels the feeling of machine annotations. If unavailable, use **IBM Plex Mono**. Font stack: "gtStandardMono", "IBM Plex Mono", ui-monospace, Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental-stat | gtPlanar | 500 | 104px | 1.1 | normal, features "ss05" | A single prominent proof value and its short unit on a text-width blue-gray backing. |
| display | gtPlanar | 500 | 45px | 1.15 | -0.02em | Centered main opening headline, white on line-shaped orange-red highlights. |
| heading | gtPlanar | 500 | 36px | 1.05 | -0.01em | Recurring section leads and closing statements; selected words may be orange-red. |
| stat | gtPlanar | 400 | 36px | 1.05 | -0.05em | Numerals in the pastel proof strip. |
| lead | plain | 500 | 20px | 1.2 | 0.02em | One-sentence section support and prominent listing titles. |
| hero-support | plain | 500 | 20px | 1.16 | 0.02em | Centered opening support line. |
| body | plain | 400 | 16px | 1.41 | 0.01em | Longer paragraphs and accordion answers. |
| body-tight | plain | 400 | 16px | 1.2 | 0.01em | Compact feature-card descriptions. |
| card-title | plain | 500 | 16px | 1.2 | 0.015em | Feature-card and accordion titles. |
| action | plain | 500 | 16px | 1 | 0.01em | Capsule buttons, navigation and footer links. |
| eyebrow | gtStandardMono | 400 | 14px | 1.2 | 0.06em, uppercase | Proof captions, footer group labels and small technical headings. |
| compact-link | gtStandardMono | 500 | 14px | 1.2 | 0.06em, uppercase | Unboxed conversion links below feature descriptions. |
| technical-list | gtStandardMono | 500 | 14px | 1.2 | 0.03em | Short capability lists and technical metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| focused product, industry and culture pages | secondary-display | gtPlanar | 500 | 45px | 1 | -0.02em | Black headline beside a square image; also centered culture-page opening. |
| testimonial-led industry and pricing pages | quote-display | gtPlanar | 500 | 36px | 1.2 | -0.01em | Centered customer quotation with pastel line highlights. |
| pricing and detailed product pages | heading-small | gtPlanar | 500 | 24px | 1.05 | -0.01em | Plan names, prices and subordinate capability chapters. |
| pricing pages | quote-body | plain | 400 | 20px | 1.2 | 0.02em | Compact four-column customer quotation strip. |
| developer integration sections | code | gtStandardMono | 400 | 14px | 1.41 | 0.06em | Readable integration sample inside the warm code panel. |

**Notes:**

- The default display is only 45px: visual drama comes from the landscape, block highlighting and the occasional monumental number, not a huge headline on every section.
- Headings tighten from -0.01em at 36px to -0.02em at 45px. Body remains positively tracked; proof-strip numerals alone use the stronger -0.05em tracking.
- Use inline, cloned line backgrounds for highlighted headings rather than one rectangular card around the entire lockup. Keep the title and support as separate layers.

## Layout

**Density:** Airy at section scale and compact within technical content; large image fields alternate with tight captions and lists.

### Spacing

**Spacing system:**

- **grid** 8px — Primary layout rhythm; 12px and 4px are smaller declared exceptions, not a replacement grid.

| Value | Use |
| --- | --- |
| 8px | Paired actions and inline groups. |
| 16px | Card text gaps, proof-cell padding and inner section gutters. |
| 20px | Image-to-card-title gap and feature rail inset. |
| 24px | Grid gutters and plan or listing-card padding. |
| 32px | Opening actions after supporting copy. |
| 40px | Opening headline-to-support gap and spotlight groups. |
| 48px | Compact banner padding and spotlight text insets. |
| 56px | Closing banner support-to-action separation. |
| 64px | Section heading-to-card-grid separation. |
| 80px | Default major-section vertical padding. |
| 96px | Split-feature, accordion and footer vertical padding. |

### Containers and grids

- **content**: max width 1280px · side padding 80px. Centered desktop reading width. At a 1440px viewport the content is 1280px wide; the surrounding stage extends 16px beyond each side to visible rails.
- **stage**: max width 1312px · side padding 64px. Wide hero, proof art and divider envelope with thin vertical side rails.
- **master-grid**: 12 columns · gap 24px. Section alignment grid; split features divide it into equal halves or a narrow text third and wide media area.
- **feature-grid**: 4 columns · gap 24px. Default capabilities: 302px-wide cards at desktop. Three-column variants use 411px-wide cards for larger illustrations or process steps.
- **proof-strip**: 4 columns · gap 4px. Four adjacent pastel proof cells, each 317px wide at desktop.
- **opening-lockup**: max width 555px. Centered main headline; support narrows to 450px beneath it.
- **quote-measure** (only for testimonial-led industry and pricing pages): max width 800px. Centered highlighted quotation.

## Corner radius

| Element | Radius |
| --- | --- |
| capsules | 99px |
| panels-and-cards | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation-rule | `inset 0px -1px 0px 0px #c5d3e8` | Crisp bottom edge of the navigation, not a floating elevation effect. |

### Surfaces

#### Ruled canvas · level 0

**Use:** Default light marketing canvas.

**CSS:** `background: #ffffff; border-left: 1px solid #c5d3e8; border-right: 1px solid #c5d3e8`

**Observed:** Long, faint vertical rails define the stage. Most cards sit directly on this canvas without a filled container.

**Transfer:** Keep the structural rails visible through changes in section content.

#### Blueprint field · level 0

**Use:** Large system diagrams and technical illustrations.

**CSS:** `background: #f8fafc; border-top: 1px solid #c5d3e8; border-radius: 0px`

**Observed:** Pale, low-contrast drafting surface makes thin connectors, wireframes and occasional orange pointers legible.

**Transfer:** Use as a drawing plane, not as a tinted card around prose.

#### Proof cell · level 1

**Use:** A compact factual metric.

**CSS:** `background: #ffc0cb; padding: 16px; border-radius: 0px; box-shadow: none`

**Observed:** Sibling cells alternate proof gray, yellow and blue. They share a baseline and appear nearly joined across 4px gaps.

**Transfer:** Give each metric one short unit label; use the pastel palette as categorical variety, not status semantics.

#### Orange identity field · level 0

**Use:** Shared closing footer.

**CSS:** `background: #ff4500; color: #000000; padding: 96px 16px`

**Observed:** The strongest uninterrupted color field on the page; white identity artwork contrasts with black navigation.

**Transfer:** Let the new identity mark become the footer's graphic anchor.

#### Cool commercial canvas · level 0

**Only for:** pricing pages

**Use:** Extended plan-selection and comparison background.

**CSS:** `background: #f0f4f8`

**Observed:** White plan cards and comparison tables sit on the cool background; the same cool tone continues through quotes and FAQs.

**Transfer:** Preserve the continuous canvas rather than separating every pricing block into a new theme.

#### Code paper · level 1

**Only for:** developer integration sections

**Use:** Wide integration sample.

**CSS:** `background: #fff8f6; border: 1px solid #ff4500; border-radius: 0px`

**Observed:** A slim language-tab bar sits above code; the selected tab has a stronger orange underline. Copy control occupies the upper right.

**Transfer:** Use an honest, concise integration example with ample line spacing.

## Components

### Navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: sticky; top: 0px; background: #ffffff; padding: 0px 48px; box-shadow: inset 0px -1px 0px 0px #c5d3e8`

**Text style:** `action` — plain 500 · 16px/1 · tracking 0.01em

**Observed:** A 52px-high band: compact identity at left, short category links centered, account links and black demo capsule at right. Pricing uses the cool commercial canvas instead of white.

**States:** Declared: hover navigation links use an orange-red text and pale peach backing; focus-visible uses a 3px outline.

### Primary button

**Use:** Main conversion.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #000000; color: #ffffff; border-radius: 99px; padding: 14px 18px`

**Text style:** `action` — plain 500 · 16px/1 · tracking 0.01em

**Observed:** A compact capsule, visually about 39px high, with a right chevron. Its white text is not uppercase. Listing actions have a 44px-high variant.

**States:** Declared: hover background-color #333132, border-color transparent, border-radius 0 and color #fff; focus-visible outline 3px solid #333132 with outline-offset .3ch.

### Secondary button

**Use:** Sales-led alternative beside the primary.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #c5d3e8; color: #000000; border-radius: 99px; padding: 14px 18px`

**Text style:** `action` — plain 500 · 16px/1 · tracking 0.01em

**Observed:** Same compact capsule and right chevron as the primary. Place after the primary with an 8px gap.

**States:** Declared: hover background-color #d3deed, border-color transparent, border-radius 0 and color #000; focus-visible outline 3px solid #000 with outline-offset .3ch.

### Setup button

**Use:** Utility action in the main opening.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 4px; background: #e1e9f2; color: #000000; border-radius: 99px; padding: 14px 18px`

**Text style:** `action` — plain 500 · 16px/1 · tracking 0.01em

**Observed:** A pale utility capsule uses a trailing copy-style icon rather than the sales chevron.

**States:** Declared: hover background-color #f0f4f8, border-color #000, border-radius 0 and color #000; focus-visible outline 3px solid #000 with outline-offset .3ch.

**Transfer:** Use for an actual utility action; use Secondary button for human-assisted conversion.

### Compact link

**Use:** Repeated card-level action.

**CSS:** `display: inline-flex; align-items: center; gap: 5px; color: #000000; background: transparent`

**Text style:** `compact-link` — gtStandardMono 500 · 14px/1.2 · tracking 0.06em · uppercase

**Observed:** Uppercase mono text followed by a small solid right-pointing triangle; no capsule and no underline.

**States:** Declared: hover background-color transparent and color #000; focus-visible outline 3px solid #000 with outline-offset .3ch.

### Feature card

**Use:** Capability or use-case grid.

**CSS:** `display: grid; position: relative; row-gap: 20px`

**Text style:** `card-title` — plain 500 · 16px/1.2 · tracking 0.015em

**Observed:** Unboxed article: large square or near-square illustration first, then title, body-tight description and Compact link. Text groups use 16px gaps. Four-column cards are 302px wide; larger three-column illustrations use 411px.

**Transfer:** Explain one concrete capability per card; the illustration should show the mechanism rather than a generic decorative icon.

### Stat tile

**Use:** Compact quantified proof.

**CSS:** `display: flex; flex-direction: column; justify-content: flex-start; row-gap: 16px; background: #ffc0cb; padding: 16px`

**Text style:** `stat` — gtPlanar 400 · 36px/1.05 · tracking -0.05em

**Observed:** Large number appears above an eyebrow caption. Four tiles form a near-continuous horizontal strip; captions remain black and left aligned.

**Transfer:** Use supported product or business metrics with similarly short labels.

### Footer

**Use:** Final identity and navigation.

**CSS:** `background: #ff4500; color: #000000; padding: 96px 16px; display: grid`

**Text style:** `action` — plain 500 · 16px/1 · tracking 0.01em

**Observed:** A 571px-tall full-width field, with a white identity artwork about 296px by 379px on the left, four 199px link columns separated by 24px on the right, uppercase mono category labels, and social/legal links low in the field.

**Transfer:** Use a bold white rendering of the new mark with enough visual mass to balance the navigation.

### Accordion row

**Only for:** FAQ and culture sections

**Use:** Objection handling or principles with expandable detail.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 8px; padding: 16px 0px`

**Text style:** `card-title` — plain 500 · 16px/1.2 · tracking 0.015em

**Observed:** Summary spans a roughly 698px-wide right column with a small chevron at the far edge; its parent has a 1px warm divider. Body copy unfolds directly below. A left column holds the section title and optional introduction.

**States:** Declared: hover color #686562; focus-visible outline 3px solid currentColor with outline-offset .3ch.

### Plan card

**Only for:** pricing pages

**Use:** Plan selection.

**CSS:** `display: grid; row-gap: 24px; background: #ffffff; padding: 24px`

**Text style:** `heading-small` — gtPlanar 500 · 24px/1.05 · tracking -0.01em

**Observed:** Name and muted price lead, followed by a short description, uppercase mono category labels, ruled feature rows with small pastel inline quantity highlights and a full-width black capsule at the bottom. Four equal columns; a black popularity tab sits above the emphasized plan.

**Transfer:** Align equivalent categories and actions across plans; keep quantity highlighting small.

### Listing card

**Only for:** careers and opportunity listings

**Use:** A structured opportunity with a direct action.

**CSS:** `display: grid; row-gap: 16px; background: #ffffff; border: 1px solid #000000; padding: 24px`

**Text style:** `lead` — plain 500 · 20px/1.2 · tracking 0.02em

**Observed:** Title above compact mono metadata and a black Apply capsule. Three columns; cards have strong black outlines unlike ordinary feature cards. Square filter tabs precede the grid, with the active filter filled black.

**Transfer:** Keep metadata as short tokens and let long titles wrap naturally.

### Code panel

**Only for:** developer integration sections

**Use:** Executable technical proof.

**CSS:** `background: #fff8f6; border: 1px solid #ff4500; overflow: hidden`

**Text style:** `code` — gtStandardMono 400 · 14px/1.41 · tracking 0.06em

**Observed:** Wide warm panel with small uppercase language tabs, selected orange underline, upper-right copy icon and inset code. Code includes stronger keyword weight; syntax is restrained rather than rainbow-colored.

**Transfer:** Use the simplest complete example for the new API.

## Imagery and graphics

### Dithered terrain

**Use:** Opening panorama and major proof or closing art.

**Observed:** Jagged mountain silhouettes are rendered as coarse colored dots and pixels: black shadows, acid yellow, orange, green, pink and pale blue-gray. The opening has a pale textured sky above a low ridge; the proof scene isolates a bright green peak on white. The art is panoramic and materially rough, not softly photographic.

**Transfer:** Apply the same reduced-color raster treatment to a relevant landscape or physical metaphor. The minimum acceptable version is an original landscape silhouette with several tonal facets and a visibly coarse dither, not a smooth gradient mountain.

**Build:** Create a wide SVG or low-resolution canvas from a landscape silhouette. Divide it into hard tonal facets, quantize to black, orange-red, yellow, vivid green, pale pink and blue-gray, then apply a 2px–4px dot or square dither. Upscale with nearest-neighbor rendering. Keep the silhouette clean against the sky, with more black density in the lower crevices. Add a faint pale stipple texture over the sky without blurring the subject.

### Pixel object sculpture

**Use:** Focused product opening and illustrated spotlight.

**Observed:** A stacked tower, a chip close-up and an old desktop computer are treated like raster sculptures. Bright green and pink interrupt pale gray forms; cyan sky or white space backs them. The computer spills a streaked, pixelated trail across the bottom of its split section.

**Transfer:** Choose a tangible object that explains the new product metaphor and reduce it to the same coarse color planes. Minimum version: an isometric SVG object with hard light/shadow faces plus a pixelated texture mask.

**Build:** Construct an isometric object from rectangular SVG faces in white, blue-gray, black and green; add sparse pink highlight planes. Rasterize at a low resolution, dither the shaded edges, and enlarge without smoothing. For a trail, stretch several narrow horizontal pixel fragments from the object's base toward the neighboring column while keeping the headline readable.

### Blueprint interface illustration

**Use:** Capability grids, walkthroughs and system maps.

**Observed:** Simplified browser frames, input fields, documents, connecting lines and oversized pointers sit on pale blue-gray fields. Most marks are extremely light; blue outlines and small orange nodes, action pills or cursor tips provide the emphasis. Small feature images are square; a wide system map uses a central circular hub between input tiles and output windows.

**Transfer:** Draw only enough interface to explain the mechanism. Preserve thin linework, large clear zones and limited accent points; avoid a full dense dashboard.

**Build:** Use SVG rectangles with 1px blue-gray strokes, 3 small circles in browser title bars, pale horizontal content bars and elbow connectors ending in simple arrowheads. For the system map, arrange a pale ring around a central title, square integration nodes to the left and three outlined output windows to the right. Add one orange action indicator; keep most geometry low contrast.

### Mixed-media process tiles

**Use:** Three-column setup or onboarding explanation.

**Observed:** White interface cutouts sit over vivid dithered cyan-sky and green-terrain backdrops. The illustrations dominate each tile; short black titles and concise instructions sit below outside the artwork.

**Transfer:** Combine one workflow diagram per step with a shared raster landscape treatment so the sequence reads as one scene, not unrelated stock art.

**Build:** Reuse a single dithered panorama across three separate image windows. Overlay flat white interface or circular workflow shapes, blue-gray hairlines and one orange node per tile. Keep text inside the art sparse and put explanatory copy below.

### Ruled signal strip

**Use:** A visible pacing device between major chapters.

**Observed:** A 102px-high strip spans the stage, divided into 13 roughly square cells by fine blue-gray rules. One small 22px square and a longer 252px by 22px bar introduce isolated saturated color.

**Transfer:** Preserve the strip as a graphic punctuation device; change bar position and limited signal colors without adding explanatory prose.

**Build:** Use a 13-column grid with 1px rules at the stage edges and between cells. Place a 22px square at one cell edge and a 252px by 22px rectangle aligned to another strip edge. Use cyan and deep blue as the default pair. Do not fill the entire grid.

### Treated team photography

**Only for:** culture pages

**Use:** Human context beside culture copy.

**Observed:** Candid people working around computers, framed as a 628px by 471px image, receive the same coarse green, pink, black and pale-gray posterization as the product art. It sits on white beside restrained text.

**Transfer:** Use genuine candid work photography rather than posed portraits; preserve recognizable people while applying a limited-color dither treatment.

### Icons

**Observed:** Small, mostly solid SVG glyphs in black or white; 19px–24px action icons and compact chevrons. Technical drawings use thinner blue-gray linework, oversized pointers and small orange accents.

**Transfer:** Use filled chevrons for capsule actions, a solid triangle for compact mono links and simple utility glyphs. Reserve outlined technical symbols for diagrams rather than mixing them into every heading.

## Section recipes

How recurring sections are built.

### First screen: Landscape stage opening

**Observed:** A 52px navigation band sits above a centered, square-edged 1312px by 710px scene bounded by page rails. Back to front: pale blue-gray stippled sky; a jagged, intensely dithered ridge occupying the lower part; a centered text lockup in the upper half. The headline spans about 555px, breaks into two compact lines and uses display on orange-red line-shaped highlights. A 450px support measure sits 40px below, with subtle blue-gray backing, then paired Primary button and Setup button 32px later. The artwork extends across the full stage and remains below the actions. Within 900px, the complete headline, support, actions and main landscape are visible, plus the start of the proof/logo band; detailed capability content falls below.

**Transfer:** For a new marketing page, retain the pixel-treated environmental stage and compact highlighted statement. Without bespoke media, create a dithered landscape or meaningful object silhouette and a pale textured sky. Focused product and industry pages instead use a white split opening with secondary-display beside a 580px square treated object; culture pages use a centered black headline followed by wide editorial media; pricing opens directly with a heading and equal plan cards on Cool commercial canvas.

**Avoid:** Do not replace this with a huge black headline beside a floating dashboard, center the landscape behind the text, or turn the two-line highlight into a rounded orange card.

**Text style:** `display` — gtPlanar 500 · 45px/1.15 · tracking -0.02em

### Section heading pair

**Observed:** Left-aligned heading at 36px with a selected orange-red phrase, followed by a 20px support sentence after 16px. Major content begins after a 64px gap; the section usually has 80px vertical padding.

**Transfer:** Use a short statement plus one sentence of context. Highlight only the semantic hinge rather than alternating several colors.

**Text style:** `heading` — gtPlanar 500 · 36px/1.05 · tracking -0.01em

### Demonstration chapter

**Observed:** A narrow text column occupies about one third of the 1280px content grid while a pale interface demonstration fills about two thirds, typically 845px by 384px. A 2px Feature rail tops the text; title, short description and Compact link align beneath it.

**Transfer:** Present an actual mechanism or result rather than a decorative media tile. Repeat the same proportions when explaining related capabilities.

### Illustrated capability grid

**Observed:** Feature card components form four columns with 24px gutters and near-square imagery. Three-column variants enlarge the illustration to 411px square; large process artwork can be taller. Images precede all text and do not sit inside rounded cards.

**Transfer:** Choose three or four distinct mechanisms for the content; keep image treatment consistent while varying the internal drawing.

### Object spotlight

**Observed:** A split ruled panel uses a left text region with a 36px heading, short body and mono list, while the right side holds a large pixel object whose horizontal trail can cross the center rail. Text has 48px vertical inset; the object remains much larger than the copy block.

**Transfer:** Use a physical metaphor for an abstract capability and let it break the strict split slightly, without obscuring the copy.

### Monumental proof scene

**Observed:** A ruled, white stage about 1312px wide pairs a compact two-line 36px claim in the upper left with a large dithered peak growing from the right. A tiny mono caption with a colored square precedes a bottom-aligned monumental-stat across a text-width blue-gray bar. The image overlaps the region behind the number.

**Transfer:** Give one supported outcome this treatment, adapting the unit and line length rather than forcing the original wording. Keep the scenery and type in a bold but readable overlap.

**Text style:** `monumental-stat` — gtPlanar 500 · 104px/1.1

### Pastel proof strip

**Observed:** A short heading precedes four Stat tile components across 1280px with 4px gaps, about 103px high. Each cell combines stat numerals with an eyebrow caption; longer labels can make the row about 119px high.

**Transfer:** Use concise factual proof at a scale that fits in one row; retain pastel variation and mono labels.

**Text style:** `stat` — gtPlanar 400 · 36px/1.05 · tracking -0.05em

### Closing call and identity

**Observed:** Closing calls use a 36px statement, a muted support line and paired capsules. The compact centered variant has 48px vertical padding; the illustrated variant puts the line and actions across the top of a wide field with a low dithered ridge beneath. Orange identity field and Footer finish the page; a pastel proof strip can sit immediately before them.

**Transfer:** Make a final concrete invitation, then close with an oversized white identity mark and useful black navigation. The graphic footer is the shared ending, while the preceding call adapts to the page's purpose.

### Highlighted customer statement

**Only for:** testimonial-led industry and pricing pages

**Observed:** An 800px centered quotation uses quote-display with pastel magenta or lime backgrounds cloned across text lines, inside a roomy section with about 99px above and 76px below. Attribution follows underneath.

**Transfer:** Use a short, attributable statement about a concrete benefit, with a single highlight color.

**Text style:** `quote-display` — gtPlanar 500 · 36px/1.2 · tracking -0.01em

### Split accordion

**Only for:** FAQ and culture sections

**Observed:** A 510px-class left introduction column faces a 698px-class stack of Accordion row components. The group has 96px vertical padding and fine separators, with no enclosing rounded panel.

**Transfer:** Use this for objection handling or detailed principles. Keep summaries short enough to scan without opening them.

## Page flow

**Storyline:** Promise → tangible mechanism → useful capabilities → evidence of scale or trust → low-friction action → graphic identity ending.

### Broad platform or product landing

1. **Promise** — Highlighted centered statement over dithered landscape, paired action and utility.
2. **Social proof** — Short trust line and six lightly backed logo cells.
3. **Product demonstration** — Narrow explanatory rails beside wide pale interface media.
4. **Capability chapters** — Pixel object spotlight, unboxed illustration grid and wide system map.
5. **Activation** — Three mixed-media steps and a centered conversion call.
6. **Quantified proof** — Monumental landscape statistic, ruled signal strip and pastel metrics.
7. **Identity ending** — Orange footer with oversized white mark and black link columns.

**Transfer:** Balance explanation and spectacle; adapt the number of capability chapters to the new product.

### Focused technical product explanation

1. **Promise** — White split opening with black 45px headline, paragraph, paired capsules and square raster sculpture.
2. **Capability chapters** — Four-image capability grid, pixel object spotlight and square blueprint illustrations paired with text.
3. **Technical proof** — Wide warm code panel with language tabs and copy control.
4. **Quantified proof** — Landscape scene with exceptionally large single number.
5. **Closing call** — Horizontal headline and actions above a low dithered ridge.
6. **Identity ending** — Shared orange footer.

**Transfer:** Use the split opening for a narrower offer and reserve integration detail for readers already convinced by capabilities.

### Culture and recruiting

1. **Invitation** — Centered black 45px headline with short support.
2. **Human context** — Wide editorial video area, followed by a treated candid photo and split culture copy.
3. **Principles** — Left introduction beside a compact accordion.
4. **Quantified proof** — Four pastel metrics, punctuated by ruled signal strips.
5. **Conversion** — Square category filters above three columns of outlined Listing cards.
6. **Identity ending** — Shared orange footer immediately after listings.

**Transfer:** Translate culture into concrete practices and a direct opportunity listing; do not add an unrelated sales closing banner.

### Industry-specific solution

1. **Promise** — Small category label, black split headline and treated square object.
2. **Social proof** — Five logo cells.
3. **Capability chapters** — Three-column infrastructure grid, highlighted quote and four-column applied-use grid.
4. **Quantified proof** — Compact pastel strip plus another highlighted customer statement.
5. **Objection handling** — Split FAQ accordion.
6. **Closing call** — Centered reliability-oriented statement and paired actions.
7. **Identity ending** — Shared orange footer.

**Transfer:** Adapt examples and objections to the audience while retaining the same product illustration language.

### Commercial comparison and plan selection

1. **Plan selection** — Cool gray canvas, short heading and four tall white plan cards.
2. **Reassurance** — Highlighted centered customer quotation.
3. **Comparison** — Wide white table with aligned plan columns, grouped category headings and fine row rules.
4. **Decision support** — Short explanatory paragraph and outlined contact capsule.
5. **Social proof** — Four compact logo-led customer quotes with bottom rules.
6. **Closing call** — Horizontal statement and actions above a dithered ridge.
7. **Objection handling** — Split FAQ continues the cool canvas.
8. **Identity ending** — Shared orange footer.

**Transfer:** Keep commercial detail scan-friendly and aligned; proof and imagery provide relief without interrupting the comparison logic.

## Writing

Confident, concrete and builder-facing, with flashes of playful ambition. Technical mechanisms earn the claims; warmth comes from plain language and short contrasts rather than hype.

**Do not copy:** Do not reuse Browserbase names, marks, customer logos, proprietary artwork, quotes, numerical claims or product-specific assertions. Replace them with the new product's own identity, validated facts and original assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; name the product when describing its role. Use we for culture and shared working principles.
- **Rhythm:** Short declarative headlines, often two clauses or a compact contrast. Support lines explain what happens in one sentence; feature paragraphs add specific mechanisms. Actions are two to four words and rarely use punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the infrastructure or outcome and the action it enables. | 7–12 words | “Infrastructure for your agents to act on the web.” |
| Section headline | Contrast a barrier with an immediate result; highlight the hinge phrase. | 4–12 words | “Zero setup. Real results.”<br>“Automate what’s tedious. Accelerate what’s ambitious.” |
| Support | A direct mechanism, followed by the benefit or reliability condition. | 12–25 words | “One API to search, fetch, and browse, with a verified identity that sites won’t block” |
| Card title | Use an active verb plus a concrete capability. | 4–9 words | “Catch broken flows before your users do” |
| Action | Start, try, build or talk; state the next step without flourish. | 2–4 words | “Start building”<br>“Talk to sales” |
| Proof caption | Name exactly what the number counts, in terse noun phrases. | 2–6 words | “Weekly SDK Downloads” |
| Culture invitation | An open invitation tied to meaningful work. | 4–10 words | “Come build with us.” |

**Words and phrasing to use:** build; ship; scale; real; works; production-ready; one; full control; in minutes; without

**Avoid:** revolutionary; unparalleled; magical; synergy; unlock limitless potential; excessive exclamation marks

**Rules:**

- Make abstract benefits tangible through actions such as configure, inspect, connect or execute.
- Use short contrasts to create memorable headings, then resolve them with technical detail.
- Keep feature descriptions specific enough to be illustrated as a mechanism.
- Tie reliability claims to an explanation or validated proof, not a stack of adjectives.
- Write proof captions as precise units rather than miniature sales pitches.

## Do's and Don'ts

### Do

- Keep the default opening headline at 45px and recurring section headings at 36px, both weight 500.
- Use 24px grid gutters and 80px major-section padding to give dense technical details room.
- Keep unboxed capability imagery large: 302px-class four-column or 411px-class three-column fields.
- Use black primary capsules with 99px radius and 8px between paired actions.
- Retain 14px uppercase mono captions on proof and footer groups.
- Include ruled signal punctuation and a materially dithered image rather than relying entirely on conventional UI mockups.
- Give a supported proof value a text-width blue-gray backing and a much larger typographic scale than body copy.
- End with the saturated orange-red field, oversized white identity and black navigation.

### Don't

- Do not turn ordinary feature cards into softly rounded, shadowed containers; their default is unboxed.
- Do not use orange-red as the default CTA fill; primary actions are black.
- Do not replace the coarse raster treatment with glossy 3D, smooth gradients or soft-focus stock photography.
- Do not set all copy in monospace; body and actions use the plain grotesk.
- Do not apply the -0.05em proof-number tracking to body copy or navigation.
- Do not spread pastel fills over full prose sections; keep them concentrated in metrics, quote highlights and small annotations.
- Do not make the footer black or reduce the identity mark to a tiny logo in a utility row.
- Do not use the pricing cool-gray canvas as the default for every marketing page.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary actions declare background-color, border-color, border-radius and color transitions of .2s cubic-bezier(.3, 0, .15, 1). Hover changes capsules to square corners.
- Compact and setup actions declare border-radius .3s cubic-bezier(.3, 0, .15, 1). Accordion title color declares .3s ease-in-out.
- The main opening uses layered picture, video and canvas media; demonstration chapters also contain video. Sticky content and scroll-reveal structures occur in the long-form layout.

**Transfer:**

- Preserve the distinctive capsule-to-square interaction rather than adding scale or bounce to CTAs.
- Use motion to reveal a technical mechanism or evolve the pixel scene while keeping text and actions readable.

**Unknown:**

- Exact playback, scroll choreography, canvas interaction and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width boundaries include 600px, 960px, 1120px and 1280px, with additional near-boundary rules.
- Logo cells use auto-fit with a 180px minimum constrained by available width; action rows allow wrapping.

**Transfer:**

- On narrow screens, preserve the compact highlighted title above a low dithered silhouette and keep actions in a wrapping group.
- Stack split copy and illustration, reduce capability columns, and reflow footer columns without losing the oversized white identity.
- Keep proof numerals on their own line when units are long; avoid shrinking mono captions until they become illegible.

**Unknown:**

- Mobile type sizes, exact grid reductions, navigation collapse and narrow-screen art direction are not established; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
