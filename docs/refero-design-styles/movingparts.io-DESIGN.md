# Moving Parts — oversized playful engineering

## Overview

A graphic, technically literate style with bold grotesk headlines and exuberant product demonstrations. White, black, pale lavender and electric blue form broad, sharply separated stages, while oversized interface objects bring tactile detail and flashes of brighter color. It suits design tools, developer products and configurable software: spacious at the page level, richly detailed inside the demonstrations, and confident without sounding corporate.

### Essentials

- Headlines feel compressed into confident word blocks: Unica77 700, 110px/0.95 with -0.04em tracking in the opening, then 100px/0.93 with -0.04em for major chapters.
- A restrained promise sits above an unruly product world: a centered 1000px headline and 840px support line on white, one blue rectangular action, then oversized black-edged interfaces entering from below and extending beyond both sides.
- Conversion controls are square-cut labels, not soft app buttons: 28px/0.95 semibold white text, 25px 30px padding, electric-blue fill and a 22px right arrow.
- Color arrives in architectural blocks: white frames the opening and closing, black carries deep demonstrations, pale lavender carries annotated anatomy, and a saturated #2525ff field carries social proof. These colored chapters occupy much of the long page; bright yellow and pink stay inside illustrated product themes.
- The signature demonstration is an exploded or restyled interface stage: thin 48.3px graph-paper cells, oversized rounded black device edges and blue mono callouts with elbow connectors. Every new landing page needs an equivalent constructed product scene; use a simplified real workflow if polished media is unavailable.
- Proof and the closing retain graphic personality: 32px/1.37 quotes on a full blue field, uppercase 21px mono credits, and a 100px closing question beside a vertically fading inventory diagram. End with an enlarged white geometric brand mark on black rather than a dense corporate sitemap.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0000ff` | `--color-action` | action, accent, background | Default conversion buttons, diagram connectors and component annotations. |
| Proof blue | `#2525ff` | `--color-proof` | background | Extended testimonial and supporter stage, distinct from the action blue. |
| Lavender stage | `#dadbf1` | `--color-lavender` | background | Full-width annotated product chapter; a cool, very pale lavender. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, action | Primary headlines, dark chapters, alternate buttons and footer. |
| Soft black | `#121212` | `--color-text-dark` | text, surface | Hero support text and dark demonstration shells. |
| Muted inverse copy | `#707070` | `--color-muted-dark` | text | White at 0.44 opacity over black, used for secondary paragraphs in dark chapters. |
| Secondary gray | `#999999` | `--color-muted` | text | Newsletter reassurance and low-emphasis editorial copy; also the visible result of black at 0.4 opacity over white. |
| Newsletter gray | `#efefef` | `--color-band` | background | Broad light-neutral signup band. |
| Grid lavender | `#f0f0ff` | `--color-grid` | border | Pale graph-paper lines behind the opening demonstration. |
| Input white | `#fcfcfc` | `--color-field` | surface | Email-entry surface, subtly separate from the gray band. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Opening and editorial canvas; inverse type and white interface panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| installation instructions | Step violet | `#6040fc` | `--color-step` | surface | Numbered installation markers. |
| standalone open-source product pages | Release violet | `#5b41f2` | `--color-violet` | surface, action, link | Contribution action, release links and testimonial speech bubbles. |
| installation instructions | Step edge | `#4125cc` | `--color-step-edge` | border | Thin edge around installation markers. |
| product demonstrations | Warm texture ground | `#c4c0bd` | `--color-texture` | surface | Warm gray ground under black-and-white marbled artwork inside a customization example. |

## Typography

- **Unica77** — All marketing headings, paragraphs, actions and footer links. Compact neo-grotesk with a tall x-height; forceful at bold weights and direct at regular weight. If unavailable, use **Inter**. Use 400, 600 and 700; preserve tight headline tracking and line breaks. Font stack: "Unica77", "Inter", system-ui, sans-serif.
- **Whyte Semi-Mono** — Attribution, editorial metadata, diagram labels and technical headings. Semi-monospaced, utilitarian lettering that gives human copy an engineering register. If unavailable, use **IBM Plex Mono**. Use 400–500; allow extra width for the fully monospaced substitute. Font stack: "Whyte Semi-Mono", "IBM Plex Mono", ui-monospace, Menlo, Monaco, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Unica77 | 700 | 110px | 0.95 | -0.04em | Centered opening promise, generally two lines. |
| heading-lg | Unica77 | 700 | 100px | 0.93 | -0.04em | Major chapter headings and closing questions. |
| heading-editorial | Unica77 | 700 | 70px | 0.96 | -0.04em | Editorial-index section heading. |
| hero-support | Unica77 | 400 | 40px | 1.27 | -0.005em | Centered explanation directly beneath the opening headline. |
| section-support | Unica77 | 400 | 32px | 1.32 | normal | Chapter introduction paragraphs. |
| quote | Unica77 | 400 | 32px | 1.37 | normal | Long-form testimonial copy. |
| button | Unica77 | 600 | 28px | 0.95 | normal | Default square conversion controls. |
| navigation | Unica77 | 600 | 28px | 1 | normal | Plain top-navigation links. |
| heading-small | Unica77 | 700 | 26px | 1.19 | normal | Feature columns and article titles. |
| body | Unica77 | 400 | 23px | 1.37 | normal | Feature descriptions and article summaries. |
| metadata | Whyte Semi-Mono | 400 | 21px | 1.36 | normal, uppercase | Attribution and editorial author/date labels. |
| footer-link | Unica77 | 700 | 17.5px | 1.22 | 0.03em, uppercase | Stacked social links in the black footer. |
| footer-label | Whyte Semi-Mono | 500 | 16.7px | 1.15 | 0.04em, uppercase | Compact footer column label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| standalone open-source product pages | release-display | Unica77 | 700 | 100px | 0.97 | -0.05em | Centered standalone-product headline. |
| installation instructions | instruction-heading | Unica77 | 400 | 48px | 1.23 | -0.005em | Practical closing installation heading. |
| standalone open-source product pages | speech-quote | Unica77 | 500 | 32px | 1.37 | normal | Short conversational testimonials in violet speech bubbles. |
| installation instructions | step-number | Whyte Semi-Mono | 400 | 30px | 1.833 | normal | Centered numeral inside circular instruction marker. |
| standalone open-source product pages | technical-heading | Whyte Semi-Mono | 400 | 27px | 1.19 | normal, uppercase | Release announcement and benefit-column titles. |
| standalone open-source product pages | instruction-body | Unica77 | 400 | 24px | 1.37 | normal | Numbered setup prose and release benefit descriptions. |

**Notes:**

- Tight tracking belongs to the bold display tier; body and mono labels retain normal tracking. Keep 100px headlines visibly more compressed than 32px supporting paragraphs.
- Marketing typography remains consistent even when the illustrated interfaces demonstrate radically different serif, condensed or decorative styles. Do not turn those demonstration fonts into the page's headline family.
- Dark chapter support copy uses a muted inverse treatment; testimonial quotations remain fully white. Metadata is uppercase without excessive added tracking.

## Layout

**Density:** Airy between major chapters and dense within product artwork; the scale contrast makes interfaces feel substantial rather than decorative.

### Spacing

| Value | Use |
| --- | --- |
| 13.3px | Feature heading to body gap. |
| 19.2px | Opening headline to support-line gap. |
| 25px | Vertical padding of square actions and signup controls. |
| 30px | Horizontal action and input padding. |
| 32px | Top-navigation item gap and signup row top separation. |
| 40px | Chapter headline to support gap. |
| 80px | Three-column feature and editorial gutters. |
| 96.7px | Large content-stack gaps between chapter introduction, demo and feature columns. |
| 120px | Main desktop chapter side inset. |
| 148px | Main chapter top and bottom padding. |

### Containers and grids

- **chapter-container**: max width 1200px · side padding 120px. Centered chapter contents inside full-bleed backgrounds at a 1440px viewport.
- **hero-text**: max width 1000px. Centered two-line promise, with support constrained separately to 840px.
- **intro-column**: max width 697px. Left-aligned chapter introduction occupying a little over half the content width; the remaining space stays open above the demo.
- **feature-grid**: 3 columns · gap 80px. Three equal columns, about 347px wide, without enclosing cards.
- **testimonial-grid**: 2 columns · gap 172px. Two approximately 514px text columns; quotes retain their natural unequal heights.
- **release-container** (only for standalone open-source product pages): max width 1212px · side padding 114px. Narrower standalone release body with large gaps between independent proof, demonstration and setup blocks.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing controls | 0px |
|  | testimonial portrait | 14px |
| product demonstrations | code comparison shell | 50px |
| oversized product illustrations | device screen | 106.3px |
| standalone open-source product demonstrations | release demo shell | 70px |
| standalone open-source product pages | speech bubble | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| product demonstrations | device elevation | `15px 20px 30px 0px rgba(0,0,0,0.3)` | A selected floating device on the pale annotated stage, not ordinary marketing text blocks. |
| product demonstrations | floating icon tile | `7.5px 14.2px 21.7px 0px rgba(0,0,0,0.1)` | Small floating rounded tiles inside the opening product collage. |

### Surfaces

#### White canvas · level 0

**Use:** Opening, editorial and conversion areas.

**CSS:** `background: #ffffff; color: #000000`

#### Black chapter · level 0

**Use:** Engineering demonstrations, customization stages and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Full-bleed flat fill with no gradient or rounded outer section corners.

**Transfer:** Use as a dramatic chapter change, not as a small card.

#### Lavender chapter · level 0

**Use:** Product anatomy and explanatory staging.

**CSS:** `background: #dadbf1; color: #000000`

**Observed:** Pale lavender extends behind headline, annotated device and feature columns.

**Transfer:** Keep the stage continuous across its content.

#### Blue proof field · level 0

**Use:** Long-form testimonials and supporter marks.

**CSS:** `background: #2525ff; color: #ffffff`

**Observed:** A sustained full-width blue section with no individual quote cards.

**Transfer:** Place real proof directly on the color rather than adding white tiles.

#### Signup band · level 0

**Use:** Secondary low-commitment conversion.

**CSS:** `background: #efefef; color: #000000`

#### Light graph paper · level 1

**Use:** Backing layer for oversized interface collage.

**CSS:** `background-color: #ffffff; background-image: linear-gradient(#f0f0ff 2px, rgba(0,0,0,0) 2px), linear-gradient(90deg, #f0f0ff 2px, rgba(0,0,0,0) 2px); background-size: 48.3px 48.3px`

**Observed:** A fine, even square grid extends beneath and between the objects.

**Transfer:** Use a full-stage grid with strong objects on top; do not put it behind paragraph reading areas.

#### Dark graph paper · level 1

**Use:** Customization demonstration backing.

**CSS:** `background-color: #000000; background-image: linear-gradient(rgba(255,255,255,0.06) 2px, rgba(0,0,0,0) 2px), linear-gradient(90deg, rgba(255,255,255,0.06) 2px, rgba(0,0,0,0) 2px); background-size: 48.3px 48.3px`

#### Release demonstration shell · level 1

**Only for:** standalone open-source product demonstrations

**Use:** Wide code-and-device showcase.

**CSS:** `background: #121212; border-radius: 70px; overflow: hidden`

**Observed:** A horizontal selector sits above a split editor and phone stage.

**Transfer:** Show one real interaction and its implementation side by side.

## Components

### Navigation

**Use:** Sparse site-level orientation.

**CSS:** `display: flex; align-items: center; padding: 54px 64px; gap: 32px; color: #000000`

**Text style:** `navigation` — Unica77 600 · 28px/1

**Observed:** A small outlined geometric mark, 158px by 59px, precedes two plain text links. The release variant adds a right-aligned installation link.

**Transfer:** Use the new brand's simple mark and only the most important destinations.

### Primary button

**Use:** Repeated high-intent conversion.

**CSS:** `display: flex; align-items: center; padding: 25px 30px; background: #0000ff; color: #ffffff; border-radius: 0px`

**Text style:** `button` — Unica77 600 · 28px/0.95

**Observed:** Text is followed by a thin white right arrow, 22px square. Black fill is the alternate editorial action; the release variant uses black for installation and violet for contribution.

**Transfer:** Repeat one clear conversion label through the page; keep the arrow separate from the text.

### Feature column

**Use:** Plain-language capability explanation beneath a demonstration.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 13.3px`

**Text style:** `body` — Unica77 400 · 23px/1.37

**Observed:** A heading-small title sits above a paragraph. Three columns share a common top edge and no card background; dark-stage descriptions are muted, lavender-stage descriptions black.

### Testimonial

**Use:** Substantial peer endorsement.

**CSS:** `display: flex; flex-direction: column; color: #ffffff`

**Text style:** `quote` — Unica77 400 · 32px/1.37

**Observed:** Long quotations appear directly on the Blue proof field. A 64px square portrait with 14px corners accompanies the attribution, separated from the quote by 45px.

**Transfer:** Use varied quote lengths rather than forcing equal-height cards.

### Attribution link

**Use:** Organization or source of testimonial.

**CSS:** `color: rgba(255,255,255,0.5); text-transform: uppercase`

**Text style:** `metadata` — Whyte Semi-Mono 400 · 21px/1.36 · uppercase

**Observed:** The person's name is white; role and organization are dimmer on the second line.

**States:** Declared: hover color white; focus-visible not specified.

### Anatomy label

**Use:** Identify functional parts of a demonstrated interface.

**CSS:** `background: #0000ff; color: #ffffff; padding: 5px 18.3px 6.7px; font-family: "Whyte Semi-Mono", ui-monospace, monospace; font-size: 26.7px; font-weight: 400; line-height: normal`

**Observed:** Square blue text labels sit outside the device. Matching orthogonal connector lines terminate in solid blue dots at the relevant interface detail.

**Transfer:** Name meaningful features and connect each to a visibly relevant part, not to arbitrary decoration.

### Article teaser

**Use:** Light editorial credibility without a thumbnail grid.

**CSS:** `display: flex; flex-direction: column; color: #000000`

**Text style:** `body` — Unica77 400 · 23px/1.37

**Observed:** Uppercase metadata, then a heading-small title after 12px, then a short summary after 20px. Three text-only teasers sit in the Feature grid.

### Email field

**Use:** Newsletter entry joined flush to a black submission control.

**CSS:** `background: #fcfcfc; padding: 25px 30px; width: 352px; height: 83px; box-sizing: border-box; border-radius: 0px`

**Observed:** The adjacent black control is 166px wide and the same height. The row begins 32px below the large heading. Reassurance beneath uses Unica77 26.7px, weight 400, normal line height and tracking in secondary gray; use a compatible scale for entry text.

**Transfer:** Keep field and action as a single hard-edged horizontal unit.

### Footer social stack

**Use:** Minimal final navigation.

**CSS:** `display: flex; flex-direction: column; color: #ffffff`

**Text style:** `footer-link` — Unica77 700 · 17.5px/1.22 · tracking 0.03em · uppercase

**Observed:** A footer-label heading precedes three links separated by 12.5px. The stack sits beside an enlarged solid white brand mark on black, with a 106.7px horizontal gap.

### Speech bubble

**Only for:** standalone open-source product pages

**Use:** Short enthusiastic peer reactions.

**CSS:** `background: #5b41f2; color: #ffffff; border-radius: 20px; padding: 20px`

**Text style:** `speech-quote` — Unica77 500 · 32px/1.37

**Observed:** Violet bubbles of varied widths have small triangular tails and black author names with tiny round avatars beneath; two loose rows alternate the visual balance.

**Transfer:** Use concise, authentic reactions rather than shortening long formal case studies into chat.

### Instruction marker

**Only for:** installation instructions

**Use:** Connect numbered prose to a setup image.

**CSS:** `background: #6040fc; color: #ffffff; border: 2px solid #4125cc; border-radius: 30px; width: 60px; height: 60px; text-align: center; box-sizing: border-box`

**Text style:** `step-number` — Whyte Semi-Mono 400 · 30px/1.833

**Observed:** Circular markers overlap the upper corners of setup images; the numbered prose below uses matching ordering.

## Imagery and graphics

### Oversized interface collage

**Use:** Signature product proof entering below the opening and filling a substantial scroll region.

**Observed:** Large black-edged phone forms and loose UI fragments overflow the page edges over Light graph paper. One central white garment is photographed front-on against electric blue, with thumbnail details below; adjacent elements include selectors, avatar discs, color controls and a travel-image card. Light, realistic isolated objects contrast with flat graphic color and thick black frames.

**Transfer:** Show the new product's actual output or a simplified credible task. Keep one dominant readable interface, partial neighbors and floating functional fragments; isolated product objects or clean generated diagrams can replace premium photography.

**Build:** Construct three tall interface panels in a horizontal flex stage with 96.7px gaps and clip the stage at viewport edges. Give the dominant white panel a thick black rounded frame, approximately 106.3px inner corners at this scale. Add a saturated blue media area, a small thumbnail strip and a white detail area. Put graph paper underneath; place a few softly shadowed rounded icon tiles and circular portraits above the margins. Keep marketing text outside these panels.

### Annotated product anatomy

**Use:** Signature explanation of modular capabilities.

**Observed:** A single tall phone, roughly 583px wide, is centered on lavender; pale rounded ghost forms sit behind it. Blue mono labels stand to either side with right-angle connectors and blue dots. The demonstrated UI combines dark bicycle photography with a white detail panel.

**Transfer:** Annotate one representative workflow using meaningful feature names. If no interface is available, draw a compact workflow panel with three or four real outputs and label those.

**Build:** Use a centered rounded black frame over a pale lavender full-width layer. Add low-contrast enlarged rounded rectangles behind its left and right edges. Position square electric-blue labels outside the frame and draw blue SVG polylines with 90-degree bends to circular endpoints on the product. Scale connectors with the scene rather than letting labels drift over copy.

### Theme comparison sculpture

**Use:** Visually prove customization through strong contrasts.

**Observed:** Overlapping tall panels extend off both edges of a black graph-paper stage. The same reflective silver pouch appears across acid-yellow, warm-gray marbled, pink and white treatments. Typography ranges from extreme condensed lettering to decorative serif and neutral sans, confined to these examples.

**Transfer:** Repeat one new product object or output across contrasting design systems. Keep the common object unmistakable so the variation reads as flexibility rather than unrelated portfolio work.

**Build:** Arrange three or four tall rounded panels at staggered heights with deliberate horizontal overlap. Use black, white, acid-yellow and pink as theme surfaces inside the artwork. Repeat the same isolated neutral object with soft metallic or matte highlights. For the marbled variant, draw broad black SVG paths on a warm-gray ground and distort them with feTurbulence plus feDisplacementMap; keep this texture clipped to one panel, not the marketing canvas.

### Fading inventory diagram

**Use:** Signature closing proof of depth beside a large conversion question.

**Observed:** A right-hand hierarchy of folders and component names rises next to the left-aligned headline. Small orange file marks and gray folder icons support indented black text; the bottom fades smoothly to white.

**Transfer:** Use the new product's real capability tree, deliverable inventory or workflow steps. This diagram is required as a depth cue, but its contents and position can change.

**Build:** Create an indented tree in a narrow column with gray folder glyphs, restrained accent file marks and about 28px text. Apply a vertical mask from opaque at the upper half to transparent at the bottom. Pair it with an open left column containing the 100px question and Primary button.

### Release edge illustrations

**Only for:** standalone open-source product pages

**Use:** Frame a centered release promise without obscuring it.

**Observed:** Playful outlined interface fragments enter from the far sides: a timing grid, a like counter and an emoji selector. Black contour lines, white fill and violet highlights make them feel like animated interface cartoons.

**Transfer:** Draw simplified functional fragments from the new product in the same outline treatment; keep the central promise and paired actions unobstructed.

**Build:** Use SVG rounded rectangles, black outline paths, small violet active states and a few gray inactive marks. Rotate the fragments slightly and place most of each outside the viewport. Reserve the center 840px for text.

### Setup image sequence

**Only for:** installation instructions

**Use:** Practical ending for a self-serve product.

**Observed:** Two desktop-interface details are shown side by side on white, softly fading at the lower edge. Violet circular numbers overlap their top corners; a numbered list below repeats the sequence.

**Transfer:** Use current setup imagery for the new product, reduce it to the controls needed to act, and pair each image with one concrete instruction.

### Icons

**Observed:** Marketing actions use simple white filled arrow SVGs around 22px. Product anatomy uses solid technical symbols and connector dots; release controls use roughly 29px outlined or image-based arrow/download symbols. Footer identity is a large solid geometric mark, not an icon set.

**Transfer:** Choose a small set of simple arrows and functional symbols. Keep expressive icons inside product illustrations and use the new brand's own mark in the footer.

## Section recipes

How recurring sections are built.

### First screen: Centered promise over product spill

**Observed:** White is the back layer. Navigation sits at the upper left with 64px side inset and 54px vertical padding. Beneath it, a bold centered two-line display spans about two thirds of the viewport in a 1000px text box; a 40px support line wraps in an 840px box after 19.2px. A single Primary button follows. The opening text and action finish around 608px; the product scene enters around 653–699px, with a color-wheel fragment at one edge, floating icon tiles at the other, and the tops of oversized black-edged interfaces rising over Light graph paper. Within the first 900px the whole promise, support and action are visible, but only the upper portion of the main interface; the detailed product proof falls below.

**Transfer:** Use a two-line outcome promise and one clear conversion above a dominant product collage. Without source-quality media, construct a simplified but believable product task with the same thick frame, saturated media block and loose controls. A standalone release opens with a technical announcement above a narrower centered headline, two adjacent actions and outlined fragments entering from the sides.

**Avoid:** Do not put a complete small laptop mockup beside a left-aligned hero or fill the whole opening with a generic gradient. Do not shrink the scene until it fits neatly inside the text container.

**Text style:** `display` — Unica77 700 · 110px/0.95 · tracking -0.04em

### Capability chapter

**Observed:** A Black chapter or Lavender chapter begins with a left-aligned heading-lg and section-support in an Intro column. The heading-to-support gap is 40px; the full chapter uses 148px vertical and 120px side padding. Primary button, a wide or tall demonstration and three Feature columns form separated content groups with 96.7px gaps.

**Transfer:** Organize a capability around a reader outcome, one deep visual proof and three concrete supporting attributes. Choose the stage color by content contrast rather than adding differently colored cards.

**Text style:** `heading-lg` — Unica77 700 · 100px/0.93 · tracking -0.04em

### Customization theater

**Observed:** A centered heading-lg and section-support sit on Dark graph paper, with a Primary button and Theme comparison sculpture spilling into the surrounding space. The heading uses a narrower line measure than left-aligned chapters.

**Transfer:** Use one repeated task or object to prove several configurations while keeping the page typography unchanged.

**Text style:** `heading-lg` — Unica77 700 · 100px/0.93 · tracking -0.04em

### Immersive proof field

**Observed:** The Blue proof field holds two-column Testimonial groups with 172px gutters, 32px quote copy and uppercase mono attribution. Below, a small centered uppercase support label introduces a horizontal row of white partner marks.

**Transfer:** Use real endorsements with unequal lengths, then consolidate institutional proof in a restrained mark row.

**Text style:** `quote` — Unica77 400 · 32px/1.37

### Closing question and inventory

**Observed:** On white, a heading-lg question and Primary button fill the left side of a 1200px container; the Fading inventory diagram occupies the right. The section has 148px vertical padding and unusually generous open space.

**Transfer:** Restate the reader's desired outcome while making the product's depth tangible through a readable hierarchy.

**Text style:** `heading-lg` — Unica77 700 · 100px/0.93 · tracking -0.04em

### Editorial bridge

**Observed:** A 70px heading-editorial leads into three Article teasers with 80px gutters. A centered black conversion button sits below the text-only grid.

**Transfer:** Use related guides or practical learning resources as a low-pressure bridge to the final signup.

**Text style:** `heading-editorial` — Unica77 700 · 70px/0.96 · tracking -0.04em

### Newsletter and geometric sign-off

**Observed:** The Signup band uses a 100px two-line heading, flush Email field and black submit control, then muted reassurance. The final Black chapter is 443px tall, with 148px vertical padding, a solid white mark enlarged to 390px by 147px on the left and a Footer social stack beside it. Most of the right half remains open.

**Transfer:** End an ordinary marketing page with a secondary signup and a visibly enlarged version of the new brand's simple identity, plus a short social or community stack rather than a dense sitemap.

**Text style:** `heading-lg` — Unica77 700 · 100px/0.93 · tracking -0.04em

### Self-serve setup ending

**Only for:** standalone open-source product pages

**Observed:** After the rounded code-and-device demonstration, a white closing block has a regular 48px instruction-heading, a pair of setup images with Instruction markers and numbered 24px prose. The page ends after these practical instructions with 112px bottom padding; it does not repeat the black marketing footer.

**Transfer:** When immediate adoption is the goal, make the ending a short, executable setup sequence rather than a sales question.

**Text style:** `instruction-heading` — Unica77 400 · 48px/1.23 · tracking -0.005em

## Page flow

**Storyline:** Outcome promise → expansive product proof → capability explanation → customization or interaction proof → peer confidence → next action, with editorial or setup support suited to the conversion.

### Broad product-library marketing with a demo-led conversion

1. **Promise** — Centered two-line outcome statement and a single blue action.
2. **Product demonstration** — An oversized multi-interface collage on pale graph paper.
3. **Capability chapters** — Black engineering stage and lavender anatomy stage, each paired with explanatory text and three-column details.
4. **Customization proof** — A black-grid theater with radically restyled versions of the same object.
5. **Social proof** — Full-blue testimonial field and supporter marks.
6. **Closing call** — Large outcome question paired with a fading product inventory.
7. **Ongoing relationship** — Text-only learning resources, a gray newsletter band and enlarged white identity on black.

**Transfer:** Keep the alternation of sparse narrative and rich visual proof; choose the number and order of chapters to fit the new offering.

### Standalone self-serve release with immediate installation as the goal

1. **Promise** — Technical announcement, centered headline, short support line and paired install/contribute controls framed by edge illustrations.
2. **Capability explanation** — Three unboxed benefit columns with uppercase mono headings.
3. **Social proof** — Short violet chat bubbles with author credits.
4. **Interactive proof** — Large rounded dark shell showing code alongside an interaction preview.
5. **Adoption** — Two numbered setup images followed by explicit installation instructions; this is the actual ending.

**Transfer:** Use this lighter, violet-accented variant for a focused release, keeping the close practical and executable.

## Writing

Confident maker-to-maker language: ambitious about the result, concrete about the mechanism and lightly playful about the experience. Technical details are used to reduce doubt, not to perform expertise.

**Do not copy:** Do not reuse Moving Parts or Pow names, identity artwork, product inventories, customer names, testimonials, claims of platform support, performance promises or source-specific adoption facts. Write original claims and use verified proof for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for outcomes, we and our for responsibility. Name the product when identifying what it is, then switch to direct reader benefits.
- **Rhythm:** Headlines are compact, usually three to seven words, arranged into firm two- or three-line blocks. Supporting copy alternates one-sentence summaries with fuller explanatory paragraphs; calls to action stay short and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | An active verb plus the reader's team or desired outcome. | 4–7 words | “Supercharge your mobile team” |
| Chapter headline | A short imperative that makes an abstract capability feel usable. | 3–4 words | “Import engineering excellence”<br>“Make it your own” |
| Supporting line | Identify the category and connect it directly to a practical result. | 8–20 words | “SwiftUI transitions that make your app shine” |
| Primary action | Literal verb and object, without promotional decoration. | 2–3 words | “Book a demo”<br>“Install Package” |
| Capability title | Plain technical assurance or a concise benefit. | 2–5 words | “Localized & Accessible”<br>“Built-in escape hatches” |
| Closing call | A direct readiness question that returns to the opening outcome. | 7–10 words | “Ready to level up your mobile team?” |
| Reassurance | A human promise that acknowledges the reader's reluctance. | One or two short sentences | “We promise we’ll only send you emails that are actually worthwhile.” |

**Words and phrasing to use:** build; ship; style; configure; native; delight; out of the box; make it your own; maintain less

**Avoid:** synergize; disruptive ecosystem; unparalleled innovation; revolutionary solution; effortless magic

**Rules:**

- Lead with what changes for the reader, then explain which product decisions make that possible.
- Be specific about constraints, compatibility and customization when relevant.
- Allow warmth in newsletter reassurance and short peer reactions; keep instructional prose literal.
- Use ampersands sparingly in compact capability labels, not as a substitute for normal sentence structure.

## Do's and Don'ts

### Do

- Keep the default opening at 110px/0.95, weight 700 and -0.04em tracking.
- Let a real interface scene cross the viewport edges while keeping the 1000px promise readable.
- Use square blue actions with 25px 30px padding and a separate 22px arrow.
- Keep the 148px chapter padding and 120px side insets at the desktop reference width.
- Use three unboxed feature columns with 80px gutters and 26px bold titles.
- Make proof a full #2525ff field with 32px white quotes, not a row of generic cards.
- Use blue elbow connectors to connect anatomy labels to actual product details.
- Carry the enlarged identity and short social stack into the ordinary marketing ending.

### Don't

- Do not apply 100px type to every heading: use 70px for the editorial index and 26px for local titles.
- Do not use pill corners on marketing actions; large radii belong to illustrated devices and the scoped speech bubbles.
- Do not spread violet across the default marketing palette; it belongs to the standalone release variant.
- Do not add drop shadows to feature columns, editorial teasers or testimonial text.
- Do not turn decorative demonstration fonts into site-wide typography.
- Do not replace the 48.3px square grid with diagonal hatching or a dense dot texture.
- Do not mute the full testimonial quotation to the 0.44-opacity chapter-copy treatment.
- Do not add a dense multi-column sitemap to the sparse 443px black sign-off.

## Motion and responsive

### Motion

**Observed:**

- Declared transitions include opacity/filter at 400ms ease-in-out and background-color at 400ms ease-in-out; isolated controls also declare 300ms background or transform changes and a 200ms opacity change.
- The product color wheel declares a 40000ms linear infinite rotation; an entry-field progress indicator declares an 1800ms linear infinite rotation.
- Attribution links declare a change from half-opacity white to white on hover.

**Transfer:**

- Keep animation concentrated in the demonstrated controls and objects so the marketing typography remains the stable frame.
- Use the long linear rotation for a wheel-like demonstration object, not for page-wide decorative movement.

**Unknown:**

- Scroll choreography and exact interaction playback are not established.
- No verified focus-visible styling or reduced-motion behavior.

### Responsive

**Observed:**

- Declared default-site width breakpoints include 620px, 800px, 1000px, 1200px and 1728px; release styles also use boundaries around 840px and 1200px.
- The main feature and demonstration groups declare mobile stacking variants.

**Transfer:**

- On narrower screens, stack feature and quote columns while keeping the full-bleed chapter colors.
- Retain one dominant product panel and clip partial neighbors rather than scaling the entire collage to illegibility.
- Move anatomy labels into short captions or a stacked legend if the two-sided connector layout no longer fits; keep each label associated with its product detail.

**Unknown:**

- Exact mobile type sizes, padding values and breakpoint-specific visibility rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
