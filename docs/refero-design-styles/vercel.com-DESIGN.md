# Vercel — infrastructure as sculpture

## Overview

An almost-white technical landscape where tightly set grotesk headlines and small interface details surround isolated geometric objects. Black, white and soft gray dominate, with blue appearing as a small engineered reveal rather than a decorative wash. Product interfaces, fine-line diagrams and softly elevated browser windows supply the imagery. The feeling is expansive at the page level and densely useful inside demonstrations, suited to developer tools and complex digital products.

### Essentials

- Headlines behave like compact word sculptures: 64px/1, weight 400 and -0.06em tracking in the default opening; 56px/1, weight 450 and -0.06em for chapter leads. Use sentence case and deliberate two- or three-line wrapping.
- The opening is a three-part still life, not a centered slogan: a 444px text column at left, one black geometric object near the center and three short utility lines at right, within an 836px stage under a 64px navigation bar. Retain an isolated geometric product metaphor even without bespoke artwork.
- Conversion controls are small capsules against enormous breathing room: 40px-high primary and secondary actions with 12px side padding, 16px/24px medium text and 12px between them; navigation controls instead use 6px corners and 32px height.
- Color is revealed, not spread: keep the page overwhelmingly #fafafa, #ffffff and #171717. A blue 48px engineering grid appears beneath a 112px folded corner; saturated marketing color stays inside such discrete media devices, while status blue remains a tiny footer signal.
- Demonstrations dissolve into the page: broad 921px interface views sit beside 333px proof columns, with a 160px bottom fade to #fafafa. Include a tangible interface or fine-line working diagram, never substitute an unrelated decorative photograph.
- The ending releases all density: a centered 56px closing line and paired capsules sit inside 276px of breathing room above and below, then a small-type directory and blue monospace system-status signature ground the page. The final line should express the new product's outcome rather than add a new feature list.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blueprint blue | `#52aeff` | `--color-blueprint-light` | background, accent | Upper stop of the engineering-grid media reveal. |
| Blueprint deep blue | `#0072f5` | `--color-blueprint-deep` | background, accent | Lower stop of the engineering-grid media reveal. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Raised white | `#ffffff` | `--color-white` | surface, text | Browser windows, secondary actions and reversed action text. |
| Off-white canvas | `#fafafa` | `--color-canvas` | background, surface | Default page field and the color into which demonstrations fade. |
| Faint edge | `#ebebeb` | `--color-edge` | border, surface | Fine action outlines, window edges, pale diagram lines and chart tracks. |
| Panel boundary | `#e6e6e6` | `--color-panel-edge` | border, surface | Structural panel edges; black at 8% over the canvas produces a similar visible boundary. |
| Numbering gray | `#8f8f8f` | `--color-muted` | text | FAQ indices and low-priority numeric labels. |
| Graphite copy | `#4d4d4d` | `--color-secondary` | text | Supporting paragraphs, utility links and secondary halves of proof statements. |
| Primary ink | `#171717` | `--color-ink` | text, action | Headlines, primary text, solid primary actions and geometric objects. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational blue | `#0070f3` | `--color-status` | text, accent | Tiny operational-status dot and monospace footer link, not the default CTA fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Metadata gray | `#7d7d7d` | `--color-metadata` | text | Technical window labels. |
| product demonstrations and calculators | Inactive gray | `#a8a8a8` | `--color-inactive` | text, border | Inactive calculator markings and subdued demonstration edges. |
| calculators and product demonstrations | Comparison gray | `#c9c9c9` | `--color-comparison` | surface, border | Comparison bars and trace outlines. |
| pricing pages | Trial pink | `#e93d82` | `--color-trial` | action | Recommended paid-plan trial action, with white text. |
| security or trust chapters | Dark inset | `#0a0a0a` | `--color-dark` | background | Contained contrast chapter, surrounded by the normal light canvas. |
| security or trust chapters | Dark panel edge | `#2e2e2e` | `--color-dark-edge` | border | Outline around a dark inset. |
| security or trust chapters | Reverse heading | `#ededed` | `--color-reverse` | text | Headlines and the light action within a dark inset. |
| security or trust chapters | Reverse supporting text | `#a1a1a1` | `--color-reverse-secondary` | text | Supporting copy inside the dark inset. |
| product demonstrations | Syntax green | `#297a3a` | `--color-syntax-string` | text | Strings in code demonstrations. |
| product demonstrations | Syntax rose | `#bd2864` | `--color-syntax-keyword` | text | Keywords in code demonstrations. |

## Typography

- **GeistSans** — All marketing headlines, paragraphs, actions and directory text. Modern neutral grotesk with open counters and compact headline spacing; regular and intermediate variable weights rather than heavy bold. OpenType features: "calt" 0, "rlig", "ss11". If unavailable, use **Inter**. Use variable weights 400, 450 and 500; retain the tight display tracking. Font stack: "GeistSans", "Inter", Arial, sans-serif.
- **Geist Mono** — Code, calculator amounts and the operational-status signature. Crisp utilitarian monospace, used sparingly outside interfaces. Font stack: "Geist Mono", ui-monospace, SFMono-Regular, Menlo, monospace.
- **GeistPixelSquare** (only for quantified proof on technical product pages) — Oversized numerical proof and short unit suffixes. Square-pixel construction makes numbers feel like instrument readouts rather than financial typography. If unavailable, use **Silkscreen**. 400 weight; preserve pixel edges rather than smoothing into a conventional mono. Font stack: "GeistPixelSquare", "Silkscreen", "Geist Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GeistSans | 400 | 64px | 1 | -0.06em | Default landing-page opening, balanced into a short stacked phrase. |
| heading | GeistSans | 450 | 56px | 1 | -0.06em | Major chapter headings and default centered closing line. |
| proof-heading | GeistSans | 450 | 24px | 32px | -0.04em | Customer proof statements and feature subheads; switch from ink to secondary gray within a single statement. |
| tile-heading | GeistSans | 450 | 24px | 1.1 | -0.05em | Short lower-corner labels on release tiles. |
| lead | GeistSans | 400 | 18px | 28px | normal | Product-page support paragraphs and chapter introductions. |
| body | GeistSans | 400 | 16px | 1.5 | normal | Ordinary explanatory copy. |
| button | GeistSans | 500 | 16px | 24px | normal | Default hero and closing actions. |
| caption | GeistSans | 400 | 14px | 20px | normal | Feature lists, release descriptions, navigation links and directory links. |
| label | GeistSans | 500 | 14px | 20px | normal | Sentence-case eyebrows, card link labels and footer group headings. |
| button-compact | GeistSans | 500 | 14px | 1.5 | normal | Navigation actions and 32px or 36px product-page actions. |
| status | Geist Mono | 500 | 12px | 20px | normal, uppercase | Operational signature at the bottom of the footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| single numerical technical-product proof | stat-spotlight | GeistPixelSquare | 400 | 110px | 96px | -0.03em | One short numerical promise next to its explanation. |
| dedicated product pages with a monumental closing call | closing-wide | GeistSans | 450 | 96px | 1 | -0.05em | A short closing imperative aligned left with actions on the right. |
| quantified proof on technical product pages | stat | GeistPixelSquare | 400 | 72px | 1 | -0.02em | Three-column proof figures with attached unit suffixes. |
| dedicated product and pricing pages | product-display | GeistSans | 450 | 64px | 1 | -0.06em | Product promise and pricing headline; also the large dark-inset heading. |
| full-width technical product testimonials | quote-wide | GeistSans | 400 | 56px | 1 | -0.06em | Centered quotation with a small customer mark above and attribution below. |
| pricing pages and promotional headings | closing-compact | GeistSans | 450 | 48px | 56px | -0.06em | Compact closing question and promotional section lead. |
| pricing calculators | money | Geist Mono | 450 | 48px | 56px | -0.06em | Large estimated total aligned to the right edge of a breakdown. |
| paired product testimonials | quote-pair | GeistSans | 400 | 32px | 1.25 | -0.04em | Left-aligned long quotations in two equal columns. |
| technical onboarding and numerical spotlights | technical-support | GeistSans | 400 | 24px | 1.5 | normal | Step titles and short explanations beside oversized figures. |
| FAQ sections | faq-question | GeistSans | 400 | 20px | 1.6 | normal | Questions and their two-digit indices. |
| FAQ sections | faq-answer | GeistSans | 400 | 16px | 1.6 | normal | Expanded explanations and underlined inline links. |
| product demonstrations | code | Geist Mono | 400 | 10.6px | 20px | normal, features "liga" 0 | Compact code within white demonstration panels; not marketing body text. |

**Notes:**

- Headline tracking is markedly tighter than body tracking: -0.06em at both 64px and 56px. Body and labels retain normal tracking.
- Use weight 450 as the principal heading emphasis, not 600 or 700. The default opening is lighter at 400.
- Eyebrows are 14px mixed-case sans, often accompanied by a small monochrome icon and plan badge; they are not widely tracked uppercase mono.
- Keep proof captions subordinate to the product scene. A bold-color numeral inside a demonstration is not a new marketing headline role.

## Layout

**Density:** Airy outside the interfaces, compact within them: broad chapter separations coexist with 6px and 12px utility gaps.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Primary vertical rhythm, with half-step and smaller local exceptions.
- **horizontal module** 12px, horizontal — Declared half-gap; 24px page margins and column gutters derive from it. Release grids use a separate 20px gutter.

| Value | Use |
| --- | --- |
| 6px | Icon-to-label and release label-to-description gaps. |
| 8px | Subhead-to-body gaps in compact feature descriptions. |
| 12px | Paired action gaps, compact control padding and utility rows. |
| 16px | Code panel vertical inset and heading support gaps. |
| 20px | Release tile inset and default showcase column gutter. |
| 24px | Page side margin, standard grid gutters and headline-to-lead gap. |
| 32px | Hero content-to-action gap and plan-card padding. |
| 40px | Closing heading-to-action gap and footer vertical padding. |
| 44px | Default showcase heading-to-media separation. |
| 72px | Product chapter lead-to-demonstration gap. |
| 80px | Release heading-to-tile-grid gap. |
| 96px | Compact product chapter vertical padding and horizontal closing-call vertical padding. |
| 120px | Standard dedicated-product chapter vertical padding. |
| 144px | Numerical proof and testimonial chapter padding. |
| 208px | Default landing-page introduction and release-section separation. |
| 256px | Default landing-page showcase chapter separation. |
| 276px | Breathing room above and below the default centered closing call. |

### Containers and grids

- **page container**: max width 1448px · side padding 24px. Centered outer wrapper; at 1440px the usable content field is 1392px wide.
- **structural grid**: 12 columns · gap 24px. Dedicated product chapters divide into halves, thirds or an eight-column lead with four-column support.
- **showcase grid**: 12 columns · gap 20px. Broad two-thirds media against a narrow proof rail; reverse the composition across adjacent chapters.
- **hero text**: max width 444px. Default opening headline column, separate from the central object and right utility rail.
- **release grid**: 2 columns · gap 20px. A 580px-tall large tile beside two 280px-tall stacked tiles.
- **directory grid**: 6 columns · gap 24px. Six groups across, repeated in a second row; groups are about 212px wide at desktop.
- **plan grid** (only for pricing pages): 3 columns · gap 0px. Three equal plan columns in one outlined frame, with shared dividers rather than floating cards.
- **comparison grid** (only for pricing pages): 4 columns · gap 0px. One feature-label column and three aligned plan columns; persistent column headings help navigate a long matrix.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing capsules | 9999px (pill) |
|  | navigation actions and release tiles | 6px |
|  | structural panels | 2px |
| product demonstrations | code panels | 8px |
| product demonstrations | browser windows | 12px |
| conversation demonstrations | conversation bubbles | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | hairline action | `0px 0px 0px 1px #ebebeb` | Secondary capsules and white navigation actions. |
| product demonstrations | floating window | `0px 0px 0px 1px rgba(0,0,0,0.08), 0px 2px 2px 0px rgba(0,0,0,0.04), 0px 8px 16px -4px rgba(0,0,0,0.04), 0px 0px 0px 1px #fafafa` | Softly elevated white browser windows. |

### Surfaces

#### Canvas · level 0

**Use:** Default light page field.

**CSS:** `background: #fafafa; color: #171717`

#### Structural panel · level 1

**Use:** Feature diagrams and capability cards.

**CSS:** `border: 1px solid #e6e6e6; border-radius: 2px; background: #fafafa`

**Observed:** Nearly square outer frames hold internally softer UI surfaces. They remain visually attached to the page rather than floating above it.

**Transfer:** Use a faint frame to define the demonstration region, not a saturated card fill.

#### Dissolving media

**Use:** Lower edge of showcase imagery and dense diagrams.

**CSS:** `background: linear-gradient(to top, #fafafa 0%, rgba(0,0,0,0) 100%); height: 160px`

**Observed:** The interface loses contrast toward its bottom edge and merges with the canvas.

**Transfer:** Overlay this on imagery only; preserve headline and caption contrast.

#### Blueprint reveal

**Use:** Engineering texture beneath a folded release-tile corner.

**CSS:** `background-image: linear-gradient(to right, rgba(255,255,255,0.16) 1px, rgba(0,0,0,0) 1px), linear-gradient(rgba(255,255,255,0.16) 1px, rgba(0,0,0,0) 1px), linear-gradient(#52aeff, #0072f5 160%); background-size: 48px 48px, 48px 48px, 100% 100%; box-shadow: inset 0px 1px 2px rgba(0,0,0,0.18), inset 0px 0px 24px rgba(0,0,0,0.14)`

**Observed:** A blue engineered layer is mostly concealed by the pale front surface, visible at the folded corner.

**Transfer:** Retain the restrained reveal as a tactile change-of-layer device, not a full-page blue theme.

#### Floating window · level 2

**Only for:** product demonstrations

**Use:** Browser and application windows layered within a hero or explanatory scene.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 2px 2px 0px rgba(0,0,0,0.04), 0px 8px 16px -4px rgba(0,0,0,0.04), 0px 0px 0px 1px #fafafa`

**Observed:** A white window can overlap another smaller window; fine title bars and restrained shadows supply depth.

**Transfer:** Show one legible operation, with lightweight chrome instead of a full browser screenshot.

#### Dark inset · level 1

**Only for:** security or trust chapters

**Use:** A contained contrast chapter.

**CSS:** `background: #0a0a0a; border: 1px solid #2e2e2e; border-radius: 2px; padding: 112px 0px; color: #ededed`

**Observed:** The panel stays inside the light page margins. A large left heading and pale capsule balance three stacked right-hand explanations in muted gray.

**Transfer:** Use when the narrative changes to assurance; do not invert every subsequent section.

## Components

### Global navigation

**Use:** Persistent site orientation and account conversion.

**CSS:** `position: sticky; top: 0px; height: 64px; z-index: 75`

**Text style:** `caption` — GeistSans 400 · 14px/20px

**Observed:** Small geometric identity at left, compact menu links beside it, and a right-aligned set of white demo/login controls plus a dark sign-up control. The light bar acquires a fine lower rule on scroll.

**Transfer:** Keep the product promise below the navigation, not inside a large masthead.

### Primary button

**Use:** Primary conversion in the opening and closing call.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 12px; border-radius: 9999px; background: #171717; color: #ffffff`

**Text style:** `button` — GeistSans 500 · 16px/24px

**Observed:** A short label sits within a compact capsule. Dedicated-product secondary chapters use a 36px version with compact action type; some deployments include a small leading geometric icon.

### Secondary button

**Use:** Documentation, sales or examples beside a primary conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 12px; border-radius: 9999px; background: #ffffff; color: #171717; box-shadow: 0px 0px 0px 1px #ebebeb`

**Text style:** `button` — GeistSans 500 · 16px/24px

**Observed:** A white capsule is visibly quieter than the primary; pairs are aligned on the same baseline rather than stretched across a column.

### Navigation action

**Use:** Account or demo controls within the global bar.

**CSS:** `height: 32px; padding: 0px 6px; border-radius: 6px; background: #ffffff; color: #171717; box-shadow: 0px 0px 0px 1px #ebebeb`

**Text style:** `button-compact` — GeistSans 500 · 14px/1.5

**Observed:** The sign-up sibling reverses to ink with white text; this squared-off navigation family is distinct from marketing capsules.

### Release tile

**Use:** Recently released capabilities in an asymmetric grid.

**CSS:** `position: relative; display: flex; flex-direction: column; align-items: flex-end; overflow: hidden; padding: 20px; border-radius: 6px; background: #fafafa; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08)`

**Text style:** `tile-heading` — GeistSans 450 · 24px/1.1 · tracking -0.05em

**Observed:** Artwork occupies most of the tile. Title and short caption are pinned at lower left, kept out of the illustration's main activity. One tall tile pairs with two short tiles.

**States:** Declared: focus-visible outline-style solid; outline-width 2px.

**Transfer:** Use a real workflow fragment or the pale window-field graphic as content; retain an engineered folded-corner reveal on a tile.

### Directory link

**Use:** Footer navigation and low-emphasis utility links.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 2px; color: #4d4d4d`

**Text style:** `caption` — GeistSans 400 · 14px/20px

**Observed:** Links sit in unboxed lists under ink group labels, with small neutral badges on new items.

**States:** Declared: hover color hsla(0, 0%, 9%, 1); focus-visible outline-style solid and outline-width 2px.

### Directory footer

**Use:** Shared ending after the final conversion or objection-handling block.

**CSS:** `max-width: 1448px; padding: 40px 24px`

**Text style:** `caption` — GeistSans 400 · 14px/20px

**Observed:** Twelve groups form two rows of six columns. Ink group labels sit above gray links; beneath the directory a small identity mark sits left, followed by a separate bottom row with blue status left and a tiny theme selector and utility icon right.

**Transfer:** Use only meaningful destinations; preserve the small operational sign-off and light field rather than ending on a dark corporate footer.

### Resource card link

**Only for:** technical product pages

**Use:** Documentation and compatibility pathways.

**CSS:** `display: flex; flex-direction: column; gap: 32px; padding: 24px; border: 1px solid #e6e6e6; border-radius: 2px`

**Text style:** `label` — GeistSans 500 · 14px/20px

**Observed:** A horizontal icon-label-chevron row sits inside the frame; short versions are 70px tall. Related rows stack with 12px gaps.

**States:** Declared: hover border-color hsla(0, 0%, 79%, 1); focus-visible outline-style none, outline-width 2px and box-shadow 0 0 #0000, 0 0 #0000, 0 0 #0000, 0 0 #0000, 0 0 #0000.

### Code panel

**Only for:** technical product demonstrations and onboarding

**Use:** Concrete executable proof beside an explanation.

**CSS:** `background: #ffffff; padding: 16px 0px; border-radius: 0px 0px 8px 8px`

**Text style:** `code` — Geist Mono 400 · 10.6px/20px

**Observed:** A 40px pale title bar has a file or terminal label at left and copy control at right. The outer wrapper supplies faint side and bottom borders; individual lines have 16px horizontal insets. Syntax colors are muted green and rose, with comments gray.

**Transfer:** Use concise valid code demonstrating the new product. Keep the surrounding page text at marketing sizes.

### FAQ row

**Only for:** FAQ sections

**Use:** Resolve detailed adoption and pricing objections.

**CSS:** `display: grid; align-items: start; gap: 24px; padding: 18px 12px; border-radius: 6px`

**Text style:** `faq-question` — GeistSans 400 · 20px/1.6

**Observed:** A muted two-digit index, ink question and tiny far-right chevron form the summary. A single-line row is 68px tall. Expanded answers align beneath question text, not beneath the index; the first item is open while subsequent rows are closed.

**Transfer:** Use semantic details and summary; keep the section title in its own left column.

### Plan column

**Only for:** pricing pages

**Use:** Entry, recommended and enterprise-level choices.

**CSS:** `display: flex; flex-direction: column; padding: 32px; border-right: 1px solid rgba(0,0,0,0.08)`

**Text style:** `body` — GeistSans 400 · 16px/1.5

**Observed:** Plan label, 56px price or custom-price word, small billing suffix, support paragraph, feature list and bottom-aligned action. The middle column is white; the others share the canvas. All columns share a single 2px-radius outside frame.

**Transfer:** Keep prices and inclusion descriptions aligned; use actual commercial facts.

### Trial button

**Only for:** pricing pages

**Use:** The recommended paid-plan trial conversion.

**CSS:** `height: 36px; padding: 0px 12px; border-radius: 9999px; background: #e93d82; color: #ffffff`

**Text style:** `button-compact` — GeistSans 500 · 14px/1.5

**Observed:** The pink capsule differentiates one plan without tinting its entire card.

## Imagery and graphics

### Isolated geometric object

**Use:** Signature default opening media.

**Observed:** A matte black triangular solid floats against the off-white field, approximately 192px wide and 166px tall at desktop. A diffuse charcoal shadow beneath it and a broad almost-white halo make it tactile without a visible pedestal. The rendering stage is much larger than the object.

**Transfer:** Make an equally simple object tied to the new product: a slab, aperture, stack or abstract instrument. Minimum acceptable treatment is a crisp SVG silhouette with soft grounding shadow; retain the scale contrast and central isolation.

**Build:** Place a roughly 192px geometric SVG silhouette near the center of a 1080px by 720px transparent stage. Add an elliptical black shadow at roughly 18% alpha, 24px blur, just beneath its base, and a broad white radial halo behind it. Keep edges crisp, the object dark and the field #fafafa; match the soft light rather than emphasizing glossy reflections.

### Dissolving interface proof

**Use:** Primary capability showcases and customer evidence.

**Observed:** Large pale application views, documentation windows and customer-site interfaces fill about two thirds of a chapter. They have thin edges and white interiors, with content fading into the canvas along the bottom. A narrow adjacent column holds a short mixed-ink proof sentence and a small feature list.

**Transfer:** Use a recognizable workflow view for the new product, simplifying chrome while retaining real hierarchy and a demonstrable result. Keep color subordinate to readability; place endorsement facts outside the interface.

### Folded engineering layer

**Use:** Signature tactile detail within a release tile.

**Observed:** A pale front plane curls up at its lower-right corner, revealing a small bright blue grid. The paper fold has narrow white and gray highlights, a diagonal crease and a soft shadow.

**Transfer:** Recreate the change of material even when no rich product art is available; it makes a simple tile feel built rather than empty.

**Build:** Back the tile with Blueprint reveal. Cover it with a #fafafa front plane clipped to cut off a 112px lower-right triangle. Add a matching triangular flap with a -45deg gradient alternating #ffffff and #ebebeb over stops at 23.2px, 61.2px, 76.2px and 79.2px. Give the flap a soft rgba(0,0,0,0.16) shadow offset 4px 6px with 10px blur. Keep the reveal small relative to the full tile.

### Receding window field

**Only for:** execution, scale or parallel-work demonstrations

**Use:** Pale technical illustration beside a scale or efficiency claim, and within release art.

**Observed:** Repeated small white browser windows recede in diagonal rows. Most edges nearly disappear into the canvas; one central tile is outlined more clearly and carries a tiny chip-like symbol. The field occupies roughly half a split section, not the text column.

**Transfer:** Represent repeated units of work with the same browser-card vocabulary. A static SVG field is sufficient; focus attention on one unit instead of making every tile equally dark.

**Build:** Repeat 120px by 84px white rectangles with 12px corners and 1px #ebebeb outlines on a staggered diagonal lattice. Put three tiny neutral dots near each top-left corner. Use top and bottom gradients into #fafafa to fade the array; give one center rectangle a #a8a8a8 edge and a 24px monochrome symbol. Keep shadows shallow.

### Fine-line working diagrams

**Only for:** technical product demonstrations

**Use:** Explain routing, measurement, isolation or system relationships.

**Observed:** Thin gray curves, small nodes, white pills and lightly elevated browser fragments sit in wide pale frames. Active routes use ink; inactive or alternate routes are faint or dotted. Charts use very soft color fills and small precise labels.

**Transfer:** Describe one meaningful operation or relationship rather than filling the diagram with generic connected icons.

**Build:** Use SVG paths with 1px neutral strokes inside Structural panel; use solid #171717 for the active branch and dashed #c9c9c9 for alternatives. Add white rounded node cards and compact labels. Where useful, back the scene with radial-gradient(#ebebeb 1px, transparent 1px) on a sparse dot grid; fade edges into #fafafa.

### Icons

**Observed:** Predominantly monochrome filled SVGs at 16px; action chevrons commonly 14px and compact technical symbols 12px. Larger demonstration symbols use 24px. Icons sit adjacent to labels rather than in brightly colored medallions.

**Transfer:** Choose compact geometric silhouettes or visually light technical icons, consistent in optical weight. Keep them ink or graphite; reserve colored dots for meaningful status inside interfaces.

## Section recipes

How recurring sections are built.

### First screen: Sculptural three-part opening

**Observed:** A 64px sticky navigation precedes an 836px off-white stage. The left text group is 444px wide and vertically balanced with the central object: a 64px/1 regular headline wraps into two short lines, then a 32px gap leads to Primary button and Secondary button separated by 12px. The central Isolated geometric object remains small within a 1080px by 720px rendering field, with a near-white halo behind and soft grounding shadow beneath. Three short 16px utility statements occupy the right rail instead of a conventional subtitle under the heading. A monochrome customer-mark strip spans the foot of the stage. Within the first 900px, navigation, full headline, actions, object, utility rail and mark strip are visible; the first capability showcase starts below the fold.

**Transfer:** Keep the light field, left compact promise, isolated geometric metaphor, narrow utility rail and low monochrome proof strip. An SVG product-shaped silhouette supplies the same visual force without custom rendering. Dedicated-product openings use a 64px weight-450 promise with an 18px support paragraph and paired capsules at left, balanced by a browser demonstration or a full-width thin-line chart. Pricing opens with the same promise scale over the plan grid rather than a central object.

**Avoid:** Do not enlarge the object to fill the viewport, turn the first screen into a centered text stack, or wrap the entire composition in a floating card. Do not add a gradient headline or multicolor decorative cloud.

**Text style:** `display` — GeistSans 400 · 64px/1 · tracking -0.06em

### Alternating demonstration and proof

**Observed:** A 56px Heading sits above a broad interface view with 44px separation. The showcase grid pairs about 921px of media with a 333px proof rail, vertically centered beside it. The rail combines a 24px/32px mixed-ink proof statement, 40px gap and a compact feature list. Adjacent chapters reverse the media and text alignment; 256px separates chapter groups.

**Transfer:** Pair an outcome with an interface that visibly earns it, followed by a short corroborating fact. Alternate the composition to create rhythm without changing the visual language.

**Text style:** `heading` — GeistSans 450 · 56px/1 · tracking -0.06em

### Product chapter heading pair

**Observed:** A small Label eyebrow with icon sits 12px to 18px above a 56px Heading. The lead occupies the left half or two thirds, while an 18px/28px support paragraph aligns to its right. Demonstrations begin about 72px lower. Dedicated-product chapters typically use 120px top and bottom padding; denser technical chapters use 96px.

**Transfer:** Separate the benefit from the mechanism: the heading names the outcome, the right paragraph explains what happens, and the lower diagram proves it.

**Text style:** `heading` — GeistSans 450 · 56px/1 · tracking -0.06em

### Asymmetric release gallery

**Observed:** A 56px Heading leads by 80px into Release tiles: one 685px by 580px tile beside two 685px by 280px tiles with 20px gutters. Short Tile headings and 14px captions anchor the lower left. Fine-line product art, conversation fragments and a Folded engineering layer carry the visual activity.

**Transfer:** Group unequal capability stories by visual weight rather than making every card identical. Carry the folded-layer device onto an appropriate tile.

**Text style:** `tile-heading` — GeistSans 450 · 24px/1.1 · tracking -0.05em

### Closing release and directory

**Observed:** The default closing is a centered 56px Heading with actions 40px below, surrounded by 276px above and below. A product-page variant sets a 96px short imperative at left with compact actions right inside 96px vertical padding; pricing uses a 48px question in that same horizontal arrangement. Directory footer follows. Technical pages with extensive onboarding and FAQs finish directly from the questions into the directory rather than adding another oversized sales panel.

**Transfer:** Conclude the narrative with an outcome or immediate next step. Preserve the tiny operational-status signature in the directory regardless of which closing variant suits the story.

**Text style:** `heading` — GeistSans 450 · 56px/1 · tracking -0.06em

### Quantified proof spotlight

**Only for:** technical product proof

**Observed:** A single 110px pixel figure can stand beside a compact explanatory block with a 24px/36px line, framed by 144px vertical padding. Another variant places a centered 56px regular quotation above three equal 72px pixel figures with short 16px captions. Paired quotes instead use 32px/40px text and 48px column gutters.

**Transfer:** Use a defensible single number or a small set of measured outcomes; preserve the instrument-like pixel figures and generous isolation. Use the paired-quote variant when prose matters more than the metric.

**Text style:** `stat` — GeistPixelSquare 400 · 72px/1 · tracking -0.02em

### Contained dark assurance

**Only for:** security or trust chapters

**Observed:** Dark inset sits within normal side margins. A two-line 64px promise and pale action occupy the left, while three spaced explanations occupy the right; their headings are pale and paragraphs use reverse secondary gray. Internal padding is 112px vertically.

**Transfer:** Make a deliberate contrast chapter for assurance or governance, then return to the light field.

**Text style:** `product-display` — GeistSans 450 · 64px/1 · tracking -0.06em

### Pricing and comparison

**Only for:** pricing pages

**Observed:** A 64px left-aligned promise is followed by the shared Plan column frame. Prices use the 56px heading treatment and small billing suffixes. Explanatory illustrated cards bridge into a long four-column comparison matrix. Category leads use 24px/32px subheads, rows use 14px/20px text and faint horizontal separators; search and plan headings remain accessible above the matrix. A pink Trial button highlights the recommended choice.

**Transfer:** Use accurate tier distinctions and explicitly stated usage units. Keep dense comparison information tabular, not a second series of oversized marketing cards.

**Text style:** `product-display` — GeistSans 450 · 64px/1 · tracking -0.06em

### Calculator and actionable onboarding

**Only for:** technical product pages

**Observed:** A 56px heading and 18px explanation introduce a wide workload slider with small mono tick labels. A two-column comparison follows: 8px-high neutral bars at left, a quantity-and-cost breakdown and 48px mono total at right. Onboarding pairs numbered left-hand instructions with white Code panels on the right; explicit copy actions convert explanation into action.

**Transfer:** Replace abstract savings with an honest manipulable workload model, then offer the shortest executable path to trial. Keep calculator and setup modules scoped to products that can support them.

**Text style:** `money` — Geist Mono 450 · 48px/56px · tracking -0.06em

### Numbered objection handling

**Only for:** FAQ sections

**Observed:** The 56px section title occupies the left side while an 802px-wide right column holds FAQ rows. Questions have pale two-digit indices and right chevrons, with the first answer open. Answers use 16px/1.6 text and underlined inline links. There are no heavy accordion boxes or colorful dividers.

**Transfer:** Answer actual adoption concerns in plain language, preserving the asymmetry and quiet numbered rhythm.

**Text style:** `faq-question` — GeistSans 400 · 20px/1.6

## Page flow

**Storyline:** Promise → tangible working proof → capability chapters and corroboration → practical adoption or commercial clarity → objections or closing invitation → operational directory.

### Broad platform landing page

1. **promise** — Three-part sculptural stage and low monochrome customer-mark rail.
2. **capability proof** — Alternating broad application scenes and narrow proof rails.
3. **momentum** — Asymmetric release gallery with a tactile engineering-layer reveal.
4. **closing invitation** — Centered outcome line and two compact capsules in a deep field of space.
5. **orientation** — Six-column directory, small identity and operational status.

**Transfer:** Choose a few strong outcomes and show them working; use the default composition and keep the narrative visually spare.

### Commercial decision and feature comparison

1. **promise** — Large left-aligned headline above three shared-frame plans.
2. **commercial clarity** — Short illustrated explanations before a searchable four-column comparison.
3. **detailed comparison** — Category headings, compact feature rows, checkmarks, usage units and aligned plan values.
4. **objection handling** — Numbered FAQ with the first answer visible.
5. **closing invitation** — Compact horizontal question and paired actions, then shared directory.

**Transfer:** Give buyers a fast plan choice before exhaustive detail; do not impose the long matrix on a normal product landing page.

### Show the value of a measurable application capability

1. **promise** — Left promise and actions over a fine full-width graph with tiny data callout.
2. **working proof** — Eyebrow-led chapters with wide dashboards, logs, charts and captions.
3. **assurance** — One contained dark panel interrupts the light technical chapters.
4. **adjacent capabilities** — Several compact framed demonstrations under split heading pairs.
5. **closing invitation** — Monumental 96px left-aligned imperative and actions, then directory.

**Transfer:** Use the product's own visible instrumentation as persuasion; keep the contrast chapter contained.

### Explain a technical execution product and make trial practical

1. **promise** — Split hero with stacked white browser windows and customer marks.
2. **use-case proof** — Several explanatory left columns paired with real code panels.
3. **capability chapters** — Pale windows, security diagrams, small feature rows and code illustrate the mechanism.
4. **economic proof** — Receding window field, paired testimonials and a workload cost calculator.
5. **adoption** — Copyable CLI and agent-prompt pathways.
6. **objection handling** — Numbered FAQ flows directly into the shared directory.

**Transfer:** Keep the mechanism concrete and make the last practical action executable; use the calculator only when valid comparisons are available.

### Explain a broad integration layer with many adoption pathways

1. **promise** — Secondary product navigation, left promise with an inline outlined word badge, and right code playground.
2. **economic proof** — Pixel numerical spotlight and scoped promotional offers.
3. **working proof** — Wide fine-line route diagram and compact capability panels.
4. **corroboration** — Three release cards, a broad centered quotation and pixel statistics.
5. **capability breadth** — Security and controls chapters followed by repeated split demonstrations.
6. **adoption** — Compatibility cards and a numbered multi-step quickstart with code.
7. **objection handling** — FAQ followed directly by shared directory; product subnavigation remains available.

**Transfer:** For complex products, use secondary navigation and a sequence of concrete demonstrations; group breadth by operation, not by a wall of feature names.

## Writing

Confident, literal and developer-fluent. It makes ambitious outcomes feel credible through concrete operations, constraints and immediately usable actions rather than exuberance.

**Do not copy:** Do not reuse Vercel names, the triangle identity, customer logos, product names, proprietary artwork, customer quotations, promotional offers, performance statistics, pricing facts or unsupported claims. Examples below illustrate language only; replace them with the new product's verified content.

- **Addressing the reader:** Address the reader as you or your, usually through direct imperatives. Refer to the product by name when explaining a mechanism; reserve we for clear operational commitments.
- **Rhythm:** Short sentence-case headline fragments, often 4–10 words, followed by one or two explanatory sentences. Three-part lists and contrasted clauses supply rhythm; technical sections can be longer when specificity earns the space.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category plainly or express an outcome with a strong verb and an explicit constraint. | 2–10 words | “Agentic Infrastructure”<br>“The safest way to run code you didn’t write” |
| Chapter heading | Pair a familiar operation with the result it enables; parallel verbs can replace a sentence. | 3–11 words | “Ship apps that scale from zero to millions instantly”<br>“View, search, inspect” |
| Supporting explanation | Explain what happens and why the user benefits, with a concrete mechanism rather than adjectives. | 1–2 sentences | “See traffic spikes and usage anomalies to pinpoint and resolve issues before they impact users.”<br>“Only pay for actual execution time, not idle resources.” |
| Proof statement | Customer or measured result first, followed by a plain description of the workload. | one compact statement | “Notion powers millions of agent conversations daily on [Brand].” |
| Action | A short verb plus an immediate destination or result. | 2–5 words | “Deploy now”<br>“Read the docs”<br>“Copy CLI code” |
| Closing line | A compact invitation or outcome, not a fresh argument. | 3–7 words | “Built by you, or your agents”<br>“Inspect your app”<br>“Can't decide?” |

**Words and phrasing to use:** build; ship; run; inspect; deploy; your; one; same; real-time; isolated; no markup; get started; read the docs

**Avoid:** revolutionary; game-changing; magical; supercharge everything; unlock limitless possibilities; unexplained enterprise jargon; exclamation-heavy hype

**Rules:**

- Make a headline about what a user can do, then let the supporting line name the implementation.
- Use explicit limits, unit prices and configuration details when they matter to adoption.
- Contrast unnecessary work with the simpler path: same calls, fewer steps, no rewrites.
- Keep action labels tied to their actual destination; prefer documentation and examples to vague discovery.
- Use real questions in FAQs and answer directly before adding caveats.

## Do's and Don'ts

### Do

- Keep the default opening at 64px/1 and weight 400; use 450 for chapter headings.
- Use 24px page margins and align media, chapter leads and directory to the same outer field.
- Give primary and secondary hero actions matching 40px heights with 12px between them.
- Preserve the contrast between large open page areas and compact 14px/20px detail lists.
- Make interface media visually merge into #fafafa with a restrained bottom fade.
- Keep structural panel corners at 2px while internal demonstration windows soften to 12px.
- Retain a small tactile blue-grid reveal and a tiny blue monospace status sign-off.
- End the default page with a 56px closing thought in substantial space, before the light directory.

### Don't

- Do not turn the 64px headline into a heavy 700-weight display; the character relies on regular and intermediate weights.
- Do not replace the 6px navigation-action corners with the marketing capsule shape everywhere.
- Do not use blue as the default primary-button fill; core conversion is #171717 on #ffffff.
- Do not convert pale structural panels into dark elevated cards with large soft shadows.
- Do not set chapter eyebrows in 12px tracked uppercase mono; their default is 14px sentence-case sans.
- Do not use the 10.6px code-demonstration scale for readable marketing paragraphs.
- Do not spread the pricing trial pink into ordinary headings, media backdrops or page bands.
- Do not make every proof card equal in height; the release gallery has a tall tile and two stacked tiles.
- Do not add a full dark footer; the directory continues the #fafafa page field.

## Motion and responsive

### Motion

**Observed:**

- Declared action timing includes 0.15s cubic-bezier(.4, 0, .2, 1); directory link color transitions use 0.1s with the same curve.
- Declared transforms include 0.3s cubic-bezier(0, 0, .2, 1). Calculator comparison bars use 0.5s cubic-bezier(0.25, 1, 0.5, 1).
- Declared slide-in animation uses 1.25s cubic-bezier(.4, .04, .04, 1) forwards. A border-trail declaration uses a 5s linear loop.

**Transfer:**

- Keep operational interaction in small details: border, ink and short transform changes rather than moving entire chapter layouts.
- Use the comparison-bar transform timing for calculator updates; preserve the settled, diagram-like composition after updates.

**Unknown:**

- Exact hero-object animation, scroll choreography and animation triggers are not specified.
- No additional timing or reduced-motion behavior is established.

### Responsive

**Observed:**

- The styles declare width breakpoints including 640px, 768px, 960px, 1024px, 1200px and 1400px, alongside component-specific thresholds.
- Heading classes include smaller 32px and 48px variants before the desktop 56px chapter treatment, and 40px before the 64px dedicated-product display. The footer has fewer grid columns at narrower widths.

**Transfer:**

- On narrow layouts, retain the isolated central-object idea but stack promise, object and short utility statements rather than shrinking a three-rail composition into illegibility.
- Collapse paired proof rails and code chapters into reading order: outcome, mechanism, demonstration, corroboration. Keep the small action shapes rather than scaling them with the artwork.
- Treat comparison matrices as a separate navigable information surface; do not squeeze four columns into unreadable miniatures.

**Unknown:**

- Exact mobile compositions, responsive canvas behavior and breakpoint-to-layout mapping are not established. The transfer rules describe adaptation, not additional measured layouts.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
