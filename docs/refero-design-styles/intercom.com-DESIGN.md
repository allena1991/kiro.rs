# Intercom — humanist systems and ephemera

## Overview

A light, editorial technology style that makes complex software feel approachable and culturally alive. Regular-weight grotesk headlines sit beside delicate serif explanations and small monospaced labels, with white and warm stone canvases interrupted by electric blue and orange markings. Oversized interface scenes, tactile abstract backdrops, candid image fragments and black ink drawings give spacious product storytelling a distinctly human counterweight.

### Essentials

- Headlines distinguish the proposition from its framing through tone rather than weight: regular Saans at 80px/1 with -0.03em tracking, mixing #111111 with a pale gray equivalent to 40% ink; section headlines use 54px/1 and -1.6px.
- The opening is an editorial clearing, not a dashboard wall: a centered three-line promise, a 640px serif support paragraph and paired 40px actions sit between small edge-clipped photographs; the first warm band begins around the bottom of the first 900px.
- Actions are small rectangles against monumental type: 4px corners, 40px height, 14px horizontal padding, black fill beside a 1px black outline, separated by 8px.
- Color behaves like a system of annotations: white and #faf9f6 dominate the page; #0007cb and #ff5600 appear as 8px square markers, thin selection lines and short quote highlights. Richer color belongs inside staged imagery rather than entire marketing bands.
- Software is presented as a tangible object: broad rectangular scenes about 1171px wide or 700px square place crisp white interface windows over warm photographic textures, with small square registration marks at their edges.
- The human counterweight is essential: isolated black ink vignettes and unframed photo fragments surround spacious text, culminating in an 80px closing statement on a blue micro-square lattice. Use original everyday-life images and rough ink silhouettes when bespoke artwork is unavailable.
- Proof looks like an annotated document: uppercase 12px mono tabs, a hairline rectangular quote stage, 28px tightly tracked quotation text and a short electric-blue reverse-text highlight; attribution and a small portrait stay subordinate.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0007cb` | `--color-blue` | accent, action, surface | Primary category markers, selection indicators, highlighted quotation phrases and primary-button hover. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5600` | `--color-orange` | accent, surface | Secondary category markers and alternate quotation highlighting; a small annotation, not a whole-page theme. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, interface staging and reversed button or highlighted quote text. |
| Warm white | `#faf9f6` | `--color-warm-canvas` | background | Alternating editorial bands, not a tint applied to every card. |
| Selector wash | `#f7f7f7` | `--color-selector-wash` | surface | Visible result of 3% black over white; selected feature explanation. |
| Chalk | `#f1eee9` | `--color-chalk` | surface | Product tiles and compact price stages. |
| Subtle gray edge | `#e7e7e7` | `--color-subtle-edge` | border | Visible result of 10% off black over white; testimonial frame and tab edges. |
| Linen edge | `#dedbd6` | `--color-linen-edge` | border | Fine perimeter around product demonstration scenes. |
| Clay | `#d3cec6` | `--color-clay` | border, accent | Card rules, FAQ separators and neutral registration squares. |
| Pale headline ink | `#a0a0a0` | `--color-pale-type` | text | Visible result of 40% off black over white; framing words in display headlines and inactive directory entries. |
| Attribution gray | `#888888` | `--color-attribution` | text | Visible result of 50% off black over white; small attribution roles. |
| Muted ink | `#707070` | `--color-muted` | text | Visible result of 60% off black over white; review lines and quieter headline clauses. |
| Secondary ink | `#585858` | `--color-secondary` | text | Visible result of 70% off black over white; feature descriptions. |
| Strong secondary ink | `#414141` | `--color-strong-secondary` | text | Visible result of 80% off black over white; supporting text with slightly stronger contrast. |
| Off black | `#111111` | `--color-ink` | text, action, border | Main type, filled actions and strong edges. |
| Pure black | `#000000` | `--color-black` | text | Footer link lettering and black ink artwork. |

## Typography

- **Saans** — Display, headings, actions, feature text and footer links. Open, softly humanist grotesk with a high x-height, used at regular weight rather than heavy display weights. If unavailable, use **Inter**. Use 400 and retain tight display tracking; letter shapes are not identical. Font stack: "Saans", "Inter", system-ui, sans-serif.
- **Serrif** — Introductory support paragraphs and editorial feature explanations. Light, fine-stroked literary serif that softens the functional sans. If unavailable, use **Source Serif 4**. Use 300; preserve the compact 16px setting. Font stack: "Serrif", "Source Serif 4", Georgia, serif.
- **SaansMono** — Eyebrows, customer tabs, sequence numbers and footer group labels. Small, workmanlike monospace; uppercase labels look like printed annotations. If unavailable, use **IBM Plex Mono**. Use 400 for labels and 500 for footer groups. Font stack: "SaansMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Saans | 400 | 80px | 1 | -0.03em | Default opening and monumental closing statements. |
| heading | Saans | 400 | 54px | 1 | -0.0296em | Major section leads, centered price figures and compact commercial opening. |
| quote | Saans | 400 | 28px | 1 | -0.0343em | Large testimonial passages, including their highlighted spans. |
| card-heading | Saans | 400 | 24px | 1 | -0.02em | Image-led card titles, short product pairing statements and plan names. |
| feature-heading | Saans | 400 | 20px | 1.2 | -0.01em | Feature selectors, small benefit headings and FAQ questions. |
| editorial-body | Serrif | 300 | 16px | 1.4 | -0.01em | Support below major headlines and prose beneath image-led cards. |
| body | Saans | 400 | 16px | 1.5 | normal | Feature explanations, FAQ answers and default action labels. |
| caption | Saans | 400 | 14px | 1.4 | normal | Reviews, attribution and compact feature descriptions. |
| eyebrow | SaansMono | 400 | 12px | 1 | 0.05em, uppercase | Section labels, numbered annotations and customer tabs. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| flagship product landing pages | product-display | Saans | 400 | 100px | 0.9 | -0.04em | Two-line flagship product promise above a large material-backed interface. |
| pricing and product value summaries | commercial-heading | Saans | 400 | 40px | 1 | -0.03em | Estimator and add-on section leads; numbered value-card titles. |
| release announcements | announcement-heading | Serrif | 300 | 40px | 1 | -0.03em | An editorial release title inside a shallow media announcement strip. |
| footer navigation | footer-link | Saans | 400 | 14px | 1.25 | normal | Dense footer navigation. |
| footer navigation | footer-label | SaansMono | 500 | 12px | 1.3 | 0.1em, uppercase | Group titles within the footer. |

**Notes:**

- Use regular display weight throughout; emphasis comes from dark-versus-muted clauses, line breaks and short rectangular highlights rather than bold text.
- Headline tracking tightens from -0.01em at 20px to -0.03em at 80px and -0.04em at 100px. Keep the 54px recipe's specific -1.6px tracking.
- Serif support text is the default beneath major marketing headlines; switch to sans for functional explanations, FAQs and most pricing details.
- Uppercase is reserved for mono annotations. Display headlines remain sentence case, with tight line spacing and deliberate semantic wraps.

## Layout

**Density:** Airy editorial sections contain relatively compact controls and explanatory text; white space surrounds the argument rather than padding every element equally.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Paired-action gap, title-to-description gap in cards and label-to-square gap. |
| 12px | Short text stacks and footer label separation. |
| 16px | Outer desktop section padding, grid gutters and simple bordered-card padding. |
| 24px | Eyebrow-to-heading, heading-to-support and support-to-action spacing; selector interior padding. |
| 32px | Testimonial stage padding and larger feature-column gaps. |
| 40px | Compact card content separation and heading-to-media on product chapters. |
| 48px | Secondary vertical group gaps and narrower-page media separation. |
| 64px | Small proof-band padding and inner commercial stage spacing. |
| 80px | Default major-band vertical padding and heading-to-grid spacing. |
| 112px | Expanded editorial section padding and feature-opening separation. |

### Containers and grids

- **page-grid**: max width 1920px · 12 columns · gap 16px · side padding 16px. Centered outer grid. Most editorial content occupies the middle ten columns, about 1171px wide at a 1440px viewport.
- **intro-copy**: max width 640px. Centered serif supporting copy beneath the opening promise.
- **chapter-copy**: max width 696px. Left-aligned heading cluster occupying six outer-grid columns; paragraphs are often narrower than the headline.
- **feature-grid**: 3 columns · gap 16px. Three equal image or benefit columns, about 380px each at desktop.
- **split-demonstration**: 2 columns · gap 0px. A 700px-square image beside a 468px selector stack, approximately a 60:40 split, with no space between stage and explanation.
- **footer-grid**: max width 1600px · 5 columns · gap 24px · side padding 24px. Footer expands beyond the editorial measure; groups stack inside five equal columns.
- **commercial-container** (only for pricing pages): max width 1040px · 2 columns · gap 80px. Compact estimator composition with 480px controls and a 520px estimate panel.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | navigation-items | 6px |
|  | editorial-panels | 0px |
| pricing pages | commercial-cards | 2px |
| feature-detail opening demonstrations | feature-opening-stage | 12px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default page plane.

**CSS:** `background: #ffffff; color: #111111`

**Observed:** Flat and borderless; room is created by layout, not elevation.

**Transfer:** Keep navigation, proof and closing areas on this open white plane.

#### Warm band · level 0

**Use:** Long editorial chapters and contrast between story blocks.

**CSS:** `background: #faf9f6`

**Observed:** Full-width warm-white bands with 80px or 112px vertical padding.

**Transfer:** Alternate with Canvas according to narrative changes, not every individual component.

#### Chalk stage · level 1

**Use:** Image-backed product tiles and centered price-summary panels.

**CSS:** `background: #f1eee9; border-radius: 0px; box-shadow: none`

**Observed:** A warm rectangular backing, frequently punctuated by small corner squares.

**Transfer:** Use behind original UI fragments or a concise commercial proposition.

#### Media perimeter · level 1

**Use:** Wide and square product demonstrations.

**CSS:** `border: 1px solid #dedbd6; overflow: hidden`

**Observed:** The perimeter is fine and nearly disappears against warm backing; product windows inside it may have their own realistic depth.

**Transfer:** Keep the outer scene flat even when the interface inside is dimensional.

#### Proof sheet · level 1

**Use:** Quotation stage below customer tabs.

**CSS:** `background: #ffffff; border: 1px solid rgba(17,17,17,0.1); padding: 32px; border-radius: 0px`

**Observed:** A wide document-like stage on a warm band. A warm chalk variant accompanies orange quote highlighting.

**Transfer:** Keep the marketing frame square and the selected quote phrase sharp-edged.

#### Selected explanation · level 1

**Use:** Active feature selector.

**CSS:** `background: rgba(0,0,0,0.03); border-radius: 0px`

**Observed:** The faint wash distinguishes the active text block; a thin colored rule reinforces selection.

**Transfer:** Show only one active explanation at a time.

#### Commercial panel · level 1

**Only for:** pricing pages

**Use:** Estimate results and add-on cards.

**CSS:** `background: #ffffff; border: 1px solid #d3cec6; border-radius: 2px; padding: 24px; box-shadow: none`

**Observed:** Small functional radius and visible warm-gray perimeter.

**Transfer:** Use for editable or comparable commercial information, not as a universal feature-card skin.

## Components

### Primary button

**Use:** Main conversion or selected next step.

**CSS:** `background: #111111; color: #ffffff; border-radius: 4px; height: 40px; padding: 0px 14px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `body` — Saans 400 · 16px/1.5

**Observed:** A compact dark rectangle paired with Secondary button. Navigation uses smaller 14px labels and 12px horizontal padding; pricing controls also use 14px labels.

**States:** Declared: hover background-color #0007cb, color #fff, border-color color-mix(in oklab, #000 80%, transparent); focus-visible solid 2px outline with 2px offset; active background-color color-mix(in oklab, #0007cb 85%, transparent), color #fff.

### Secondary button

**Use:** Demo or sales alternative beside the main action.

**CSS:** `background: transparent; color: #111111; border: 1px solid #111111; border-radius: 4px; height: 40px; padding: 0px 14px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `body` — Saans 400 · 16px/1.5

**Observed:** Matches the primary action's height and baseline; label determines width.

**States:** Declared: hover transparent background with border and text color color-mix(in oklab, #111 75%, transparent); focus-visible solid 2px outline with 2px offset; active background-color color-mix(in oklab, #111 2%, transparent), color #000.

### Navigation shell

**Use:** Persistent orientation and conversion access.

**CSS:** `background: #ffffff; min-height: 66px; padding: 0px 12px; display: flex; flex-direction: column; justify-content: center`

**Observed:** Full-width fixed header with logo left, product and resource menus beside it, and utility links plus compact conversion actions right. Menu labels use 14px/15.4px regular sans; chevrons are 18px. A separate shallow announcement ribbon can sit above it.

**Transfer:** Keep the core bar lean; use one bordered product-switch control only when the information architecture needs it.

### Feature selector

**Use:** Explain several capabilities alongside a changing product demonstration.

**CSS:** `background: rgba(0,0,0,0.03); display: flex; flex-direction: column; position: relative; overflow: hidden; border-radius: 0px`

**Text style:** `feature-heading` — Saans 400 · 20px/1.2 · tracking -0.01em

**Observed:** A square category marker precedes heading, body and an underlined small link inside 24px padding. Selected text is dark, inactive explanations lighter. A fine blue or orange progress line sits along the top; selectors stack beside a square stage or form three adjacent blocks below a wide stage.

**States:** Declared: hover opacity 0.8; focus-visible solid 2px outline with 2px offset.

**Transfer:** Tie each concise explanation to one concrete view of the new product.

### Customer tab

**Use:** Switch between testimonial stories.

**CSS:** `padding: 16px; border-top: 1px solid rgba(17,17,17,0.1); border-right: 1px solid rgba(17,17,17,0.1); border-left: 1px solid rgba(17,17,17,0.1); margin-left: -1px; position: relative`

**Text style:** `eyebrow` — SaansMono 400 · 12px/1 · tracking 0.05em · uppercase

**Observed:** Three equal-width tabs share edges above a Proof sheet. A thin colored line marks the active tab; the active background merges with the quote stage.

**States:** Declared: hover color color-mix(currentcolor 75%, transparent 25%); focus-visible solid 2px outline with 2px offset.

### Testimonial stage

**Use:** Substantial third-party proof with a highlighted outcome.

**CSS:** `background: #ffffff; border: 1px solid rgba(17,17,17,0.1); padding: 32px; display: grid; grid-template-columns: repeat(10, minmax(0px, 1fr)); column-gap: 16px`

**Text style:** `quote` — Saans 400 · 28px/1 · tracking -0.0343em

**Observed:** Customer logo sits at upper left; quotation occupies the middle columns, attribution sits below and a small natural-color portrait anchors the lower right. Blue rectangles with white text highlight the important phrase, including across line wraps. Blue corner squares register the panel. A chalk variant uses orange highlighting and can omit the portrait.

**Transfer:** Highlight one verified result or striking observation, not the entire quotation.

### Benefit card

**Use:** Short, equal-weight value propositions.

**CSS:** `border: 1px solid #d3cec6; padding: 16px; display: flex; flex-direction: column; border-radius: 0px`

**Text style:** `card-heading` — Saans 400 · 24px/1 · tracking -0.02em

**Observed:** Three equal rectangular outlines, with deliberately spacious interiors. A product-summary variant uses a 12px mono sequence number and 40px blue title; a feature-detail variant uses a 24px black title over serif explanation.

**Transfer:** Give all cards similar copy length and keep their interiors unillustrated when the argument is purely textual.

### FAQ row

**Use:** Resolve detailed objections without turning the page into prose.

**CSS:** `display: flex; justify-content: space-between; align-items: baseline; padding: 20px 0px; color: #111111; text-align: left`

**Text style:** `feature-heading` — Saans 400 · 20px/1.2 · tracking -0.01em

**Observed:** Each question spans a 696px right-hand column and sits inside a 1px clay top rule. A small disclosure triangle sits at the far edge. Open answers use 16px sans text; the first answer is expanded. The section label sits alone in the left column.

**States:** Declared: focus-visible solid 2px outline; most question rows declare hover opacity 0.6.

### Footer navigation

**Use:** Broad discovery after the closing call.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); gap: 24px; padding: 0px 24px; max-width: 1600px; margin: 0px auto`

**Text style:** `footer-link` — Saans 400 · 14px/1.25

**Observed:** Five columns of links, grouped with Footer-label titles and 12px label-to-list gaps. Links occupy a 24px row rhythm with 4px list gaps. Legal links sit in a separate bottom-left row. No dark footer block, giant logo or raised cards.

**States:** Declared: link hover opacity 1 from 0.9; underline background-size transition 0.2s ease-out.

### Commercial card

**Only for:** pricing pages

**Use:** Add-ons or an estimate summary.

**CSS:** `background: #ffffff; border: 1px solid #d3cec6; border-radius: 2px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between; gap: 40px`

**Text style:** `card-heading` — Saans 400 · 24px/1 · tracking -0.02em

**Observed:** Title and concise 14px description sit above a price and underlined link. Add-ons form three equal columns; an estimate result uses the same fine-edged panel language with line items and a warm action strip.

## Imagery and graphics

### Editorial fragments

**Use:** Human-scale edge imagery in openings and the closing composition.

**Observed:** Unframed rectangular photo fragments show sunlight, shadows, sky, bubbles and everyday life, mixed with isolated black ink drawings. The opening crops pictures against the left and right viewport edges while leaving the central text untouched. Small drawings of animals, birds and leisure scenes accompany chapter headings.

**Transfer:** Use original tactile everyday imagery with light, air and imperfect human presence; mix photography with rough monochrome vignettes rather than generic software mascots.

**Build:** Place two offset image stacks behind the opening content at opposite edges. Use rectangles roughly 150–290px wide and 190–245px tall, object-fit: cover, no frame or rounding. Pair a square-ish photo with an isolated SVG ink vignette made of irregular filled black shapes and dry-brush gaps. Keep all fragments out of the center text measure.

### Photographic product stages

**Use:** Default wide product demonstrations and square capability scenes.

**Observed:** Crisp white application windows overlap secondary message panes over golden paper-like texture, softly lit gray photographic material and partial plant leaves. The image fills a broad landscape stage; white UI is the dominant foreground object. Small three-column scenes use chalk backings and enlarged UI fragments rather than entire browser windows.

**Transfer:** Stage a real workflow from the new product over softly lit physical texture; if no finished product imagery exists, create a high-fidelity static interface with a few readable interactions and layer two coherent windows.

**Build:** Use a rectangular texture image as the back layer, then one dominant white interface panel and a narrower offset companion. Keep windows mostly front-facing, with subtle contact shadows inside the art only. For a minimal version, use a chalk backing with a softly lit photographic paper surface and an original flat interface foreground.

### Registration lattice

**Use:** Signature closing artwork and tiny framing marks on chapters and proof.

**Observed:** Blue micro-squares form a widely spaced regular lattice behind the closing statement; small photos and black ink vignettes interrupt it. Larger 8px squares mark chapter or panel corners. The closing composition is 592–672px high and preserves a broad clear central corridor for text and paired actions.

**Transfer:** Include this open lattice with original image fragments as the signature end punctuation, even for products with no visual assets.

**Build:** Use an SVG grid of 4px square blue marks on roughly 180px horizontal and vertical intervals across the full width. Mask the central text corridor where necessary. Position five or six unframed 100–150px image fragments around the outer cells; allow side images to clip. Keep the main 80px statement and paired actions above the lattice layer.

### Halftone price atmosphere

**Use:** Compact commercial summary within a marketing page.

**Observed:** A soft black halftone silhouette rises behind a centered chalk price panel and a shallower explanatory strip. It is densest around the lower and outer edges, nearly disappearing toward the top. Small dark corner marks make the panels look registered to the print field.

**Transfer:** Turn an abstract product-related form into a faint halftone field behind a clear price or proof proposition, without sacrificing legibility.

**Build:** Create an SVG pattern of tiny black circles on a regular roughly 8px pitch. Mask it with a large soft organic silhouette and an upward fading alpha gradient. Keep the field low contrast, behind a solid chalk rectangle about 696px wide, and add 4px ink corner squares.

### Blue fiber sculpture

**Only for:** flagship product landing pages

**Use:** Material-backed interface hero and chapter imagery.

**Observed:** Saturated cobalt ribbons have hundreds of fine parallel ridges, folding into large looping waves behind white interface windows. Their scale extends beyond the viewport in the opening; later scenes contain them within rectangular stages.

**Transfer:** Use one consistent sculptural material family across a flagship product story, not an unrelated effect per section.

**Build:** Minimum equivalent: draw broad looping SVG paths behind the interface on chalk. Layer many thin parallel blue strokes with alternating translucent light and dark edges to suggest ribbed fiber, using a large loop entering from the left and another arch behind the right. Add gentle directional shading; preserve the white UI as the foreground.

### Iridescent membrane

**Only for:** feature-detail product demonstrations

**Use:** Colorful abstract backing for channel and workflow demonstrations.

**Observed:** Soft translucent membranes blend lime, pale blue, pink and orange. Large curved edges are partially visible around white UI, with subtle grain; the colors belong to the media, not the surrounding page.

**Transfer:** Use a consistent translucent material to unite related demonstrations while preserving the neutral outer layout.

**Build:** Layer oversized blurred elliptical shapes on a pale cool backing: lime at upper left, pink at right and warm orange near lower edges. Mask with broad curved cutouts to create membrane boundaries, add a faint fine-grain overlay and place crisp white interface windows above. Match the soft glow; exact stops are not essential.

### Icons

**Observed:** Navigation chevrons use 18px outline SVGs with 1px strokes and butt caps, often at reduced opacity. FAQ disclosure marks are small filled dark triangles; 20px filled icons appear in functional controls. Tiny blue or orange squares often replace conventional feature icons.

**Transfer:** Prefer square category marks for marketing labels and restrained monochrome utility icons for controls. Keep icon language separate from the expressive ink artwork.

## Section recipes

How recurring sections are built.

### First screen: Editorial clearing opening

**Observed:** A fixed white 66px Navigation shell sits above a white composition; a shallow announcement ribbon can increase its total height. A small review line precedes a centered three-line Display headline occupying roughly half the viewport width. Pale framing clauses surround a dark middle proposition. Behind and beside this text, asymmetric photo fragments enter from the viewport edges; 8px blue registration marks anchor the composition's corners. A centered Editorial-body paragraph about 640px wide sits 24px below the headline; Primary button and Secondary button sit 24px below it with an 8px gap, followed by a small trial reassurance. Within the first 900px, all headline, support, actions and fragments are visible; the next Warm band and its short introductory line appear near the bottom, while the main interface demonstration falls below.

**Transfer:** Give a different product one short dark central promise within a lighter contextual phrase. Replace edge photos with original images of human activity, materials or natural light; no finished product media is needed for this first screen. Flagship product pages instead use Product-display above a large material-backed UI entering the lower fold. Feature-detail pages use a bracketed mono category, an 80px centered promise and a wide colorful UI stage. Pricing pages open more compactly with a 54px centered proposition and comparison panels.

**Avoid:** Do not turn the default opening into a left-copy/right-dashboard split, a full-bleed photograph or a giant rounded gradient card. Do not place a busy screenshot behind the central headline.

**Text style:** `display` — Saans 400 · 80px/1 · tracking -0.03em

### Annotated chapter lead

**Observed:** Eyebrow with an 8px category square, then 24px to Heading, 24px to Editorial-body support and 24px to paired actions. A small black ink vignette balances the heading cluster at the right. Chapters sit on Canvas or Warm band with 80px or 112px vertical padding. Some headings split into muted setup and dark conclusion.

**Transfer:** Name a capability category briefly, state its benefit in a two- or three-line heading, then explain its mechanism. Match the vignette's emotional tone rather than illustrating the feature literally.

**Text style:** `heading` — Saans 400 · 54px/1 · tracking -0.0296em

### Tabbed broad product proof

**Observed:** A short 24px two-tone heading precedes a broad Photographic product stage, about 1171px wide. Two equal-width tabs sit flush on its top edge, separated by fine borders, with a short blue selection line. White software windows overlap within the warm tactile backing.

**Transfer:** Use two coherent product modes or workflows, not arbitrary visual variations. Let the product scene do more work than surrounding copy.

**Text style:** `card-heading` — Saans 400 · 24px/1 · tracking -0.02em

### Capability demonstration

**Observed:** Annotated chapter lead above a Media perimeter scene, with 48–80px separation. A wide scene can have three adjacent Feature selectors below it; a square scene uses a flush 60:40 image-to-selector split. Each selector links a compact heading and explanation to a distinct product state.

**Transfer:** Use this chapter construction for processes that benefit from specific visual proof; vary broad and square formats rather than repeating identical media stacks.

### Three image stories

**Observed:** Three columns with 16px gutters; each starts with a 380px-square chalk-backed UI fragment, then 24px to a Card-heading and 8px to Editorial-body. Small clay squares register the image corners.

**Transfer:** Focus each image on one outcome and show only the interface fragments necessary to understand it.

**Text style:** `card-heading` — Saans 400 · 24px/1 · tracking -0.02em

### Value summary cards

**Observed:** A left-aligned Heading precedes three Benefit cards with 16px gutters and generous interior height. Numbered product summaries use blue 40px titles; detail summaries use black 24px titles. The perimeter, not a colored fill or shadow, groups the copy.

**Transfer:** Use a few distinct benefits before deeper demonstrations; keep numbered summaries scoped to product-overview storytelling.

### Annotated customer proof

**Observed:** Three Customer tabs attach to a Testimonial stage. A tightly set Quote includes a blue reverse-text phrase; small attribution and a natural portrait sit below or alongside. The warm variant uses a chalk interior and orange highlight. Some chapters use an unboxed quotation with the same highlight language.

**Transfer:** Provide a genuine third-party statement and make its one consequential phrase visually prominent.

**Text style:** `quote` — Saans 400 · 28px/1 · tracking -0.0343em

### Compact price proposition

**Observed:** Centered Heading over a Chalk stage with 64px inner breathing room. Short product description, two large 54px price figures separated by a plus sign, 12px mono billing labels and paired actions sit above a shallow explanatory strip. Halftone price atmosphere frames the panels.

**Transfer:** Use for a concise commercial model or quantified summary; replace the two-part price structure when the offer differs.

**Text style:** `heading` — Saans 400 · 54px/1 · tracking -0.0296em

### Two-column questions

**Observed:** Heading stands alone at left while a 696px stack of FAQ rows occupies the right. Top and bottom clay rules organize the list; one answer is open and its body remains compact.

**Transfer:** Use specific buying or adoption questions, with direct answers and contextual text links.

**Text style:** `heading` — Saans 400 · 54px/1 · tracking -0.0296em

### Lattice closing and open footer

**Observed:** Registration lattice and Editorial fragments surround a centered 80px statement with paired actions in a white 592–672px closing composition. Images remain small against the monumental text. After about 80px separation, Footer navigation spreads to five columns on the same white canvas, followed by a small legal row; all page types preserve this light ending.

**Transfer:** End with a short outcome-oriented invitation and keep the lattice, human fragments and generous central clearing. Adapt the closing line and link groups to the new product; retain the open white finish.

**Text style:** `display` — Saans 400 · 80px/1 · tracking -0.03em

### Functional pricing comparison

**Only for:** pricing pages

**Observed:** A compact centered 54px opening leads to a three-column plan group plus a separate fourth product panel. Shared top bands, 1px clay dividers and 4px outer corners create a table-like structure; descriptions and feature lists use 14px sans. Below, a 40px estimator heading introduces input controls left and a Commercial panel right. Add-ons appear as three Commercial cards.

**Transfer:** Make comparison, estimate and inclusions separate decisions, preserving the quieter functional density of this page type.

**Text style:** `heading` — Saans 400 · 54px/1 · tracking -0.0296em

### Large feature directory

**Only for:** broad product overview pages

**Observed:** A square product preview and small caption sit left; a right column of 54px feature links has clay bottom rules and northeast arrows. Inactive entries are pale; the active item turns dark and changes the preview.

**Transfer:** Use as an exploratory index when a product has many equally important capabilities.

**Text style:** `heading` — Saans 400 · 54px/1 · tracking -0.0296em

### Release media strip

**Only for:** release announcements

**Observed:** A shallow white media announcement uses an oversized atmospheric image behind a small play treatment, a 40px light-serif release title, short sans support and one dark action.

**Transfer:** Use as a compact editorial interruption for a genuine release rather than as a repeating capability card.

**Text style:** `announcement-heading` — Serrif 300 · 40px/1 · tracking -0.03em

## Page flow

**Storyline:** Promise → tangible product proof → credibility → capability chapters → customer outcomes → buying clarity or objections → expressive closing call → open navigation footer.

### Introduce an integrated product proposition and make a complex offer feel coherent

1. **Promise** — Centered two-tone display with human photo fragments and compact paired actions.
2. **Product demonstration** — Two-mode product stage and a restrained logo field.
3. **Capability chapters** — Alternating warm and white chapters mix ink vignettes, broad interface scenes, square selectors and image-led cards; a release strip interrupts the rhythm.
4. **Social proof** — Tabbed highlighted quotation with portrait.
5. **Compatibility** — Short text beside an orderly integration-logo grid.
6. **Buying clarity** — Halftone-backed compact price summary.
7. **Closing call** — Monumental statement in the image-and-square lattice, then the five-column white footer.

**Transfer:** Introduce the relationship between the new product's parts before enumerating individual capabilities.

### Establish a flagship product and demonstrate how its major advantages work

1. **Promise** — 100px two-tone headline over oversized blue sculptural material and white application UI.
2. **Value summary** — Three numbered, outlined benefit cards with blue titles.
3. **Capability chapters** — Productivity-style wide demo, collaboration-style square split and integration-style broad scene, each led by a muted-and-dark heading.
4. **Social proof** — Unboxed customer quotation with a blue highlighted result between chapters.
5. **Exploration** — Large ruled feature directory with synchronized square preview.
6. **Closing call** — White lattice composition with ink vignettes and blue material fragments; same open five-column footer.

**Transfer:** Group advantages into a few memorable themes, then offer a broad directory for deeper exploration.

### Explain one product capability through concrete use cases and resolve practical questions

1. **Promise** — Bracketed mono category, centered 80px promise and colorful material-backed application stage.
2. **Social proof** — Monochrome customer-logo field.
3. **Value summary** — Three airy outlined benefit cards.
4. **Capability chapters** — Alternating white and warm chapters combine square split demonstrations and a broad full-context workflow scene.
5. **Customer outcome** — Tabbed chalk quotation with orange highlighted phrase.
6. **Objection handling** — Two-column FAQ with the first answer expanded.
7. **Closing call** — Outcome invitation on the human-fragment lattice, then the white navigation footer.

**Transfer:** Organize the middle around distinct contexts in which the capability matters, rather than listing every technical feature.

### Make offer comparison and cost expectations understandable

1. **Pricing** — Compact centered promise, short trial assurances and table-like comparison columns.
2. **Cost clarity** — Interactive-looking setup controls beside an itemized estimate panel.
3. **Value explanation** — Outcome definition and spending reassurance beside an abstract material-backed product scene.
4. **Offer extensions** — Three bordered add-on cards on a warm band.
5. **Social proof** — Large centered heading and tabbed quote panel with blue highlighted metric.
6. **Objection handling** — Long two-column FAQ stack.
7. **Closing call** — Same monumental lattice invitation and light five-column footer.

**Transfer:** Separate plan selection, cost calculation and definitions so commercial complexity never overwhelms the opening.

## Writing

Confident, explanatory and human, with a clear belief that sophisticated technology should make ordinary work easier. Claims are direct, but the supporting prose explains mechanisms and consequences rather than relying on slogans alone.

**Do not copy:** Do not reuse Intercom or Fin names, logos, customer identities, quotations, product claims, prices, performance statistics or original artwork. Source examples demonstrate voice and structure only; replace them with truthful content and original assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to 'you', 'your team' and 'your customers'. Name the product plainly as the subject of explanations; use 'we' sparingly outside attributed quotations.
- **Rhythm:** Short sentence-case headings lead into one compact paragraph, often with a causal second sentence. Repeated capability entries use a short title, a practical explanation and an optional descriptive link; actions are usually two or three words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the integrated outcome in plain language, with contextual words and the essential proposition visually separated. | 6–12 words | “A complete system for AI and human customer service”<br>“Meet your customers wherever they are” |
| Chapter heading | Lead with a tangible benefit, often a verb and the thing the reader gains. | 5–10 words | “Works with the tools you already use”<br>“Support customers where they work” |
| Supporting explanation | Explain how the system works, then connect that mechanism to an everyday advantage. | 25–65 words | “Supporting more channels shouldn’t mean managing more tools. [Brand] brings every conversation together so your AI agents and team can deliver consistent support, wherever customers choose to reach you.” |
| Primary action | Direct verb plus a concrete, low-friction next step. | 2–3 words | “Start free trial”<br>“View demo” |
| FAQ question | Ask the practical question a buyer would actually say aloud. | 5–12 words | “Which channels does [Brand] support?”<br>“How does [Brand] pricing work?” |
| Closing invitation | Return to the desired outcome or invite direct experience of the product. | 4–10 words | “Perfect customer experiences”<br>“See the helpdesk in action” |

**Words and phrasing to use:** together; your team; one shared; full context; works with; every conversation; without switching; consistent; built for

**Avoid:** revolutionary; game-changing; supercharge; unlock limitless potential; magic; disrupt; !!!

**Rules:**

- Pair a broad benefit with an observable mechanism: shared information, fewer handoffs, a specific action or a concrete workflow.
- Use everyday verbs before technical terminology; explain specialized terms where they affect buying decisions.
- Keep headings sentence case and unpunctuated unless they are genuine questions.
- Use numerical claims only when verifiable and attach quotations to real attribution.
- Make secondary links contextual when helpful, while keeping primary conversion labels consistent.

## Do's and Don'ts

### Do

- Keep the default display at 80px/1, weight 400 and -0.03em tracking.
- Use 16px light serif support under major editorial headings, reserving 16px sans for functional explanation.
- Keep paired actions 40px high with 4px corners and an 8px gap.
- Align most chapters to the middle ten columns of the 12-column grid.
- Use 80px band padding and expand to 112px for major editorial chapters.
- Keep category squares at 8px and use them consistently in blue or orange.
- Preserve the full-width white closing lattice with its small human fragments and 80px statement.
- Use 1px warm-gray rules instead of elevation to group functional panels.

### Don't

- Do not use bold 700-weight display type; the tonal clause split carries emphasis.
- Do not replace the fine serif support paragraphs with oversized 24px sans lead text.
- Do not turn 4px action corners into capsules or inflate the default buttons to 56px.
- Do not paint whole text-led sections electric blue or orange; reserve saturated fields for the imagery itself.
- Do not round all product scene perimeters to 24px; most editorial stages remain square.
- Do not put drop shadows on ordinary benefit cards or testimonial frames.
- Do not extend pale display-gray text to functional body copy; explanations need stronger contrast.
- Do not switch to a dark mega-footer or add a giant footer wordmark.

## Motion and responsive

### Motion

**Observed:**

- Links declare background-size 0.2s ease-out for underline treatment. Many disclosure and selection controls declare opacity 0.3s cubic-bezier(.4, 0, .2, 1).
- Feature selectors include a horizontal progress-line animation; header chevron styling supports a rotated open state. Customer-story and product views use tabbed or carousel structures.
- Primary and secondary button hover, focus-visible and active treatments are defined in their component recipes.

**Transfer:**

- Use the thin progress line as the visible time cue for changing product scenes; keep content changes subordinate to the editorial reading experience.
- Animate link underlines and restrained control color changes rather than making every card float or scale.

**Unknown:**

- Scene-change timing, autoplay durations, scroll-trigger choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px, 1536px and 1920px among finer intermediate thresholds.
- Grid declarations include single-column feature layouts before multi-column variants; the footer has a separate narrower layout.

**Transfer:**

- On narrow layouts, retain the headline's dark-versus-muted relationship while reducing size to fit semantic line groups.
- Stack demonstration and explanation rather than shrinking a 60:40 scene into unreadable columns; keep the active visual adjacent to its text.
- Move edge fragments outward or reduce their count while preserving the central clearing and small square-mark motif.

**Unknown:**

- Exact mobile type sizes, mobile navigation construction and the small-screen closing-art arrangement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
