# AutoSend — pastoral software ledger

## Overview

A light, personable software style that pairs a soft old-style serif with matter-of-fact grotesk text and technical monospace labels. Warm white and stone gray dominate, with violet actions and small rose and lime markings. Pixel-art landscapes and scenic photographs give the interface demonstrations an unexpectedly outdoorsy setting, while fine ruled grids keep long product stories orderly. It suits developer tools and practical SaaS products that want to feel approachable without losing technical credibility.

### Essentials

- A literary promise over a technical ledger: use regular cooperLtBT at 80px/1.1 with selective italic words, then switch to regular Geist at 40px/1.2 for section headings and uppercase Geist Mono for navigation and labels.
- The opening is text-first, with scenery arriving at the fold: a 56px header, 120px hero padding, a centered two-line headline about 718px wide, 16px to support copy and 40px to compact paired actions; the 1104px-wide landscape starts beneath it.
- Actions are small rounded rectangles, not oversized pills: 32px height, 12px corners, 6px 16px padding and uppercase 14px/20px semibold monospace; violet is reserved for the primary action and links.
- Most of the page remains pale stone or white; saturated color is concentrated in scenic media, violet controls, 14px chapter labels and a tiny lime status indicator, rather than whole colored section bands.
- Product proof lives inside scenery: include a landscape-backed demonstration with a pale browser window inset 24px, 8px window corners and a soft two-layer shadow. Include a pixel-art scenic stage as an expressive counterpoint; a simplified original low-resolution landscape plus one useful interface panel is the minimum equivalent.
- Sections behave like ruled ledger sheets: 1px stone dividers, square outer corners, shared edges, 24px inner padding, equal half-width demonstrations and compact four-cell statistical proof.
- The ending offers help instead of shouting another sales pitch: a 40px question beside a two-by-two resource matrix and a full-width human-help row, followed by a five-column ruled footer and a small operational-status line.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#615fff` | `--color-violet` | action, accent | Primary button fill and narrow progress accents. |
| Link violet | `#4f39f6` | `--color-violet-deep` | link, border, action | Primary button edges and hover fill; section-wide text links. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Rose chapter marking | `#ff2056` | `--color-rose` | text, accent | Short chapter labels; not a band background. |
| Lime chapter marking | `#5ea500` | `--color-lime` | text, border | Short chapter labels and operational-status dot border. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#292524` | `--color-ink` | text | Primary text, dark announcement tab and outline icons. |
| Stone text | `#78716c` | `--color-muted` | text | Support copy, descriptions and captions. |
| Faint stone text | `#a6a09b` | `--color-subtle` | text | Low-emphasis metadata and footer copyright. |
| Stone hairline | `#e7e5e4` | `--color-rule` | border | Outer frames, shared grid edges, internal separators and window dots. |
| Recessed stone | `#f5f5f4` | `--color-recess` | surface | Window chrome and interactive hover grounds. |
| Pale stone canvas | `#fafaf9` | `--color-canvas` | background, text | Default page ground and light text on the violet action. |
| White paper | `#ffffff` | `--color-white` | surface, background | Raised interface windows, testimonial bodies, secondary actions and footer category cells. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime status | `#9ae600` | `--color-status` | accent, surface | Tiny operational-status dot; also the recommendation tag on plan cards. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and comparison pages | Savings highlighter | `#d8f999` | `--color-saving` | surface | Small annual-savings chips in cost comparisons. |

## Typography

- **cooperLtBT** — Hero headlines and italic testimonials. Soft, rounded old-style serif with a friendly italic rather than a formal fashion serif. If unavailable, use **Libre Caslon Text**. Use regular and italic 400; tune line breaks to preserve the broad two-line silhouette. Font stack: "cooperLtBT", "Libre Caslon Text", Georgia, serif.
- **Geist** — Section headings, body copy, questions and interface demonstrations. Clean contemporary grotesk; regular weight does most of the work. Font stack: "Geist", Arial, sans-serif.
- **Geist Mono** — Navigation, actions, technical labels, bylines and footer cells. Straightforward monospace that gives pale editorial layouts the feel of a developer console. Font stack: "Geist Mono", ui-monospace, monospace.
- **dataType** — Standalone statistical numerals outside product interfaces. Narrow, machine-like numerals with an instrument-panel feeling. If unavailable, use **Share Tech Mono**. Use 400 and keep the numerals compact. Font stack: "dataType", "Share Tech Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | cooperLtBT | 400 | 80px | 1.1 | normal | Default centered marketing promise and short pricing title. |
| display-emphasis | cooperLtBT | 400 italic | 80px | 1.1 | normal | One or two meaningful words within the main promise. |
| heading | Geist | 400 | 40px | 1.2 | normal | Section leads, closing questions and capability headings. |
| split-heading | Geist | 400 | 40px | 1.2 | -0.02em | Bottom-anchored heading inside scenic split panels. |
| stat | dataType | 400 | 24px | 32px | normal | Compact statistical proof values. |
| hero-support | Geist | 400 | 20px | 1.5 | normal | Centered hero explanation and closing support line. |
| lead | Geist | 400 | 20px | 1.4 | normal | Split-panel descriptions and longer explanatory leads. |
| quote | cooperLtBT | 400 italic | 18px | 24px | normal | Customer quotations inside white grid cells. |
| body | Geist | 400 | 16px | 1.5 | normal | Capability descriptions. |
| feature-label | Geist Mono | 500 | 16px | 1 | normal, uppercase | Capability row titles beside outline icons. |
| byline | Geist Mono | 500 | 16px | 1.5 | normal, uppercase | Attribution names beneath quotations. |
| eyebrow | Geist Mono | 500 | 14px | 16px | normal, uppercase | Colored section and numbered chapter labels. |
| action | Geist Mono | 600 | 14px | 20px | normal, uppercase | Navigation, compact conversion buttons and full-width detail links. |
| tile-label | Geist Mono | 500 | 14px | 20px | normal, uppercase | Resource matrix cells, integration names and proof-strip introductions. |
| footer-label | Geist Mono | 500 | 12px | 16px | 0.1em, uppercase | Footer category headers and small product-page kickers. |
| footer-link | Geist Mono | 500 | 12px | 16px | normal, uppercase | Compact footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| feature and comparison pages | detail-display | cooperLtBT | 400 | 80px | 1.1 | -0.02em | Longer centered feature or comparison promises. |
| FAQ and plan-comparison sections | faq-heading | Geist | 400 | 40px | 1 | normal | Compact heading over question rows. |
| FAQ sections | question | Geist | 500 | 16px | 1.25 | normal | Accordion question text. |
| comparison pages | comparison-number | Geist Mono | 500 | 14px | 18px | normal | Cost cells and annual savings. |

**Notes:**

- Reserve the soft serif for the first promise and human testimony; the working body of the page is grotesk and mono.
- Headings remain weight 400. Most text uses normal tracking; the split-panel heading and detailed-page display tighten to -0.02em.
- Uppercase is concentrated in mono utility text, not applied to body sentences or large headings.
- Default marketing headlines retain normal tracking; longer feature and comparison headlines use the separately scoped tighter recipe.

## Layout

**Density:** Airy between sections, compact inside ruled cells; the long page alternates generous breathing room with dense technical proof.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and feature title-to-description gaps. |
| 16px | Heading-to-support gap, eyebrow-to-heading gap and icon-to-content separation. |
| 24px | Default cell padding and interface-window inset. |
| 40px | Hero group separation and compact vertical section spacing. |
| 80px | Default major section margins and gaps between related capability chapters. |
| 120px | Main hero vertical padding. |
| 160px | Separation between major long-form feature, pricing and comparison modules. |

### Containers and grids

- **page-container**: max width 1152px · side padding 24px. Centered desktop wrapper; the inner framed content spans 1104px at a 1440px viewport.
- **hero-copy**: max width 768px. Centered default promise and support copy; the headline's two-line block is about 718px wide.
- **split-panel**: 2 columns · gap 1px. Equal text and scenic demonstration halves within a shared frame; each half is about 551px wide.
- **proof-grid**: 4 columns · gap 0px. Four equal statistics or logo cells with shared hairlines.
- **testimonial-grid**: 3 columns · gap 0px. Three equal quotation cells without card gutters.
- **footer-grid**: 5 columns · gap 0px. Five equal link columns, each about 220px wide, aligned as rows in a ledger.
- **detail-hero-copy** (only for feature and comparison pages): max width 896px. Wider centered title block for feature and comparison pages.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | section-frames | 0px |
|  | compact-actions | 12px |
|  | announcement-and-browser | 8px |
|  | status-dot | 50% |
| product demonstrations | interface-flow-nodes | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| demonstration-window | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Browser-like interface windows over landscape media, not outer marketing frames. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous pale page ground.

**CSS:** `background: #fafaf9; color: #292524`

#### Ledger frame · level 1

**Use:** Capability chapters, proof strips, resource matrices and footer.

**CSS:** `border: 1px solid #e7e5e4; border-radius: 0px; box-shadow: none`

**Observed:** Background generally continues the page ground; adjoining cells share a single edge.

**Transfer:** Group related content in a single ruled assembly rather than separate floating cards.

#### White inset · level 1

**Use:** Testimonial copy cells and secondary action surfaces.

**CSS:** `background: #ffffff`

**Observed:** The white-to-stone difference is intentionally slight.

**Transfer:** Use white only when a subtle layer separation is useful.

#### Demonstration window · level 2

**Use:** Interface proof on a scenic backing.

**CSS:** `background: #ffffff; border-radius: 8px; overflow: hidden; box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Observed:** Pale chrome and three neutral dots sit above an interface; windows are inset from their media panel.

**Transfer:** Show one relevant, legible operation rather than an entire dashboard at illegible scale.

#### Window chrome · level 2

**Use:** Top edge of demonstration windows.

**CSS:** `background: #f5f5f4; border-bottom: 1px solid #e7e5e4; padding: 10px 12px`

#### Savings chip · level 1

**Only for:** pricing and comparison pages

**Use:** Short annual savings annotations.

**CSS:** `background: #d8f999; border-radius: 4px; padding: 4px 6px`

**Observed:** Small marker-like rectangular patches sit inside ordinary table cells.

**Transfer:** Highlight the result of a calculation, not the whole pricing column.

## Components

### Sticky navigation

**Use:** Persistent site-level orientation.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 56px; backdrop-filter: blur(16px)`

**Text style:** `action` — Geist Mono 600 · 14px/20px · uppercase

**Observed:** Centered wrapper places a modest wordmark left, text navigation in the middle and paired account actions right. Navigation items have 4px 12px padding and 8px corners; external destinations use a small diagonal arrow.

**States:** Declared: hover navigation uses a pale lavender background and deeper violet text; focus-visible styling is unknown.

### Primary button

**Use:** Main conversion action beside a secondary option.

**CSS:** `background: #615fff; color: #fafaf9; border: 1px solid #4f39f6; border-radius: 12px; padding: 6px 16px; height: 32px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Geist Mono 600 · 14px/20px · uppercase

**Observed:** Intrinsic text width; repeated unchanged in the header and hero.

**States:** Declared: hover background becomes #4f39f6; focus-visible styling is unknown.

### Secondary button

**Use:** Documentation, demo or login action.

**CSS:** `background: #ffffff; color: #292524; border: 1px solid #e7e5e4; border-radius: 12px; padding: 6px 16px; height: 32px`

**Text style:** `action` — Geist Mono 600 · 14px/20px · uppercase

**Observed:** Sits before the violet action in the hero; a small outline icon can precede documentation labels.

**States:** Declared: hover uses the recessed stone ground and a darker stone border; focus-visible styling is unknown.

### Announcement strip

**Use:** A short timely hook above the main promise.

**CSS:** `background: #ffffff; border-radius: 8px; height: 32px; display: flex`

**Text style:** `footer-link` — Geist Mono 500 · 12px/16px · uppercase

**Observed:** A charcoal left tab says New; the adjoining message has a thin charcoal outline with rounded right corners. The message itself uses sentence-case sans text rather than uppercase mono.

**States:** Declared: hover background becomes #f5f5f4; focus-visible styling is unknown.

**Transfer:** Use one concrete release or improvement; keep it shorter than the headline.

### Capability row

**Use:** Selectable explanation beside a live product example.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 24px; border-bottom: 1px solid #e7e5e4`

**Text style:** `feature-label` — Geist Mono 500 · 16px/1 · uppercase

**Observed:** A small outline icon leads a mono title and a muted body paragraph 8px below. Three or four rows fill the demonstration's height. Active rows have a very narrow violet progress streak at their left edge.

**Transfer:** Pair each row with a distinct view of the same product task.

### Browser demonstration

**Use:** Main interface proof within scenic media.

**CSS:** `background: #ffffff; border-radius: 8px; overflow: hidden; display: flex; flex-direction: column; box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Observed:** Default split-panel window is 503px wide inside a 551px media half. A short chrome bar with three dots caps the interface; the whole example is clipped to the scenic panel.

**Transfer:** Keep interface styling subordinate to the demonstrated operation.

### Statistic cell

**Use:** Small quantified proof in a four-cell strip.

**CSS:** `display: flex; flex-direction: column; justify-content: center; gap: 8px; padding: 24px; border-right: 1px solid #e7e5e4; text-align: center`

**Text style:** `stat` — dataType 400 · 24px/32px

**Observed:** Numerals are restrained rather than monumental; a 14px sans caption explains each. The row can be followed by an uppercase introduction and a separate logo grid.

### Testimonial cell

**Use:** Human validation between product modules.

**CSS:** `background: #ffffff; display: flex; flex-direction: column; gap: 16px; padding: 24px`

**Text style:** `quote` — cooperLtBT 400 italic · 18px/24px

**Observed:** Quotation body sits above a separately ruled attribution strip with a small portrait, uppercase mono name, small company line and logo toward the opposite edge. Three cells share borders.

**Transfer:** Keep each quotation concise enough to occupy a few lines without resizing the type.

### Resource tile

**Use:** Integration directories and the closing help matrix.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 24px; border-right: 1px solid #e7e5e4; border-bottom: 1px solid #e7e5e4`

**Text style:** `tile-label` — Geist Mono 500 · 14px/20px · uppercase

**Observed:** A small service symbol and mono label sit left; an understated diagonal arrow is pushed to the right edge. Four compact cells form the closing matrix; larger directory cells place the icon above the label.

**States:** Declared: hover background becomes #f5f5f4; focus-visible styling is unknown.

### Footer link cell

**Use:** Dense site directory after the closing help section.

**CSS:** `background: #fafaf9; padding: 8px 24px; border-right: 1px solid #e7e5e4; border-bottom: 1px solid #e7e5e4; display: flex; justify-content: space-between; align-items: center`

**Text style:** `footer-link` — Geist Mono 500 · 12px/16px · uppercase

**Observed:** Five columns share row edges. Category cells are white with muted tracked labels. The lower footer adds wordmark and copyright left, operational status centered and social icons right.

**States:** Declared: hover background becomes #ffffff; focus-visible styling is unknown.

### FAQ row

**Only for:** FAQ sections

**Use:** Address objections in a full-width accordion.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 16px 24px`

**Text style:** `question` — Geist 500 · 16px/1.25

**Observed:** Question aligns left with a small violet chevron far right. A single bottom hairline belongs to the row wrapper. Closed row height is 56px plus its divider; the section ends in a white full-width call link.

**States:** Declared: hover background becomes #f5f5f4; focus-visible styling is unknown.

### Plan panel

**Only for:** pricing pages

**Use:** Two parallel plan choices beneath a volume slider.

**CSS:** `display: flex; flex-direction: column; gap: 40px; padding: 24px; border-right: 1px solid #e7e5e4`

**Text style:** `tile-label` — Geist Mono 500 · 14px/20px · uppercase

**Observed:** A mono plan-category label leads a large sans price, tier name and billing annotation; violet checkmarks organize feature lists. The recommended panel is white and carries a small electric-lime recommendation tag. Bottom actions span the whole panel, use square corners, 44px height and 12px 24px padding: violet for the combined offer, dark stone for the narrower offer.

**Transfer:** Retain equal widths and align prices and actions; use the slider only when a meaningful usage variable changes pricing.

## Imagery and graphics

### Pixel landscape stage

**Use:** Signature wide scenic demonstration beneath the opening promise.

**Observed:** A bright pixel-art alpine valley fills a 1104px by 620px rectangular stage: blue sky, cream cloud clusters, distant snow peaks, layered pine trees and green banks. A small white prompt interface sits over the center of the scene farther down the page. The landscape, not a device mockup, supplies the large visual mass.

**Transfer:** Create an original outdoors-inspired pixel landscape around the new product's central operation. Keep the same welcoming daylight and low-resolution texture; the minimum is a deliberately pixelated layered valley with one legible original workflow panel.

**Build:** Draw on a small raster canvas around 368px by 207px and enlarge with image-rendering: pixelated. Layer stepped cloud polygons across a pale blue upper half, two jagged blue-gray mountain silhouettes with cream snowcaps near the center, then dark green triangular conifers along both sides and brighter olive banks at the bottom. Use hard stepped edges and small square dither patches, not blur. Center a white operation panel around 60% of the stage width.

### Scenic interface backing

**Use:** Recurring visual system for capability demonstrations.

**Observed:** Natural photographs show misty wooded hills, snowy mountain faces, teal valleys and an aerial green coastline. These are daylight, softly colored scenes. A pale browser panel occupies most of each image, leaving a narrow scenic perimeter; equal-half sections devote about half the content width to this media. Some larger demonstrations span the full framed width.

**Transfer:** Use real landscape photography with restrained contrast behind a clear original interface. Preserve visible geography at the edges rather than blurring it into an anonymous gradient.

**Build:** Use a cover-fitted scenic image in a clipped rectangular wrapper, overlay the Demonstration window with 24px inset, and keep white or pale-stone chrome with three 12px neutral dots. For a broad demonstration increase the inset while preserving the image as a perimeter, not a text background.

### Progress streak

**Use:** Active state on capability lists.

**Observed:** A thin vertical violet line runs along the active row's left boundary and fades into white near its top.

**Transfer:** Use the same small signal for whichever capability drives the adjacent demonstration.

**Build:** Place a 4px-wide absolute strip on the left edge of the active item. Use a vertical gradient from white through white at 40% to action violet at the lower end; clip it within the row.

### Process pictograms

**Only for:** migration and setup explanations

**Use:** Three-cell setup or migration proof.

**Observed:** Simple dark outline symbols sit on small softly raised white rounded tiles, surrounded by faint violet trajectories. Captions sit near the lower edge of each large cell in muted uppercase mono.

**Transfer:** Choose three concrete operations and give each a clear symbolic object rather than a detailed scene.

**Build:** Center an approximately 80px square white rounded tile in each 367px-wide cell; add a fine stone outline and minimal shadow. Draw thin violet SVG paths entering from above or left at low opacity, with small outline tokens traveling toward the central symbol. Keep most of each cell pale and empty.

### Icons

**Observed:** Interface-independent icons are mainly 16px or 20px dark outline SVGs with rounded stroke caps; common 16px icons use 2.3px strokes and 20px icons use 1.8px strokes. Diagonal external-link arrows are small and secondary. Resource services retain compact colored symbols, while capability icons stay monochrome.

**Transfer:** Use a consistent rounded outline set for capabilities and actions; preserve small service marks only when they identify a real destination.

## Section recipes

How recurring sections are built.

### First screen: Literary promise and scenic reveal

**Observed:** A 56px Sticky navigation sits on the continuous Canvas. After 120px of breathing room, the Announcement strip centers above the promise with a 40px gap. The regular 80px serif headline occupies about two thirds of the inner width and two lines; selected nouns are italic, not separately colored. A centered 20px/30px support statement follows after 16px, then paired Secondary button and Primary button after 40px. The text hero ends around 693px down the page. The Pixel landscape stage begins immediately beneath it, so within the first 900px the full promise, support and actions are visible, along with roughly the upper third of the scenic object; the prompt operation lies below the fold.

**Transfer:** Use a two-line promise naming a user and a useful outcome, with one or two italic emphasis words. Recreate the scenic stage with original low-resolution art and a relevant operation panel when no suitable product media exists. Feature pages replace the announcement with a small tracked category label, use the wider tighter detail headline and introduce a product demonstration or logo strip beneath; comparison pages add a compact two-symbol illustration, while pricing opens with a short title and volume selector.

**Avoid:** Do not push a giant dashboard into the title area, put the headline over scenery, or expand the small conversion controls into hero-sized buttons.

**Text style:** `display` — cooperLtBT 400 · 80px/1.1

### Ruled heading pair

**Observed:** Ledger frame contains a 24px-padded heading area. An uppercase colored eyebrow precedes a 40px regular sans heading by 16px. The title commonly occupies the left half while the right half remains open or carries a 20px explanatory paragraph.

**Transfer:** Use the eyebrow as a short chapter marker and make the heading an outcome. Let short sections omit supporting copy without filling the space with decoration.

**Text style:** `heading` — Geist 400 · 40px/1.2

### Capability chapter

**Observed:** Ruled heading pair above an equal-half body about 520px tall. One half stacks Capability rows and the other holds Scenic interface backing with Browser demonstration. A narrow Progress streak marks the active explanation. A white full-width detail-link strip closes the assembly, with violet uppercase mono text and arrow. Related chapters have 80px gaps.

**Transfer:** Use this for a product with several demonstrable capabilities; synchronize each row's promise with the adjacent state rather than showing unrelated interface fragments.

### Bottom-anchored split story

**Observed:** A framed two-column panel is about 522px tall. The eyebrow pins to the top left, while the Split-heading and a 20px paragraph anchor near the bottom left with 24px between them. Scenic interface backing fills the right half. The large empty area separates labeling from the payoff.

**Transfer:** Give a single operational advantage its own breathing room; keep the title and support near the bottom rather than vertically centering everything.

**Text style:** `split-heading` — Geist 400 · 40px/1.2 · tracking -0.02em

### Compact proof ledger

**Observed:** Four Statistic cells share a 1104px-wide strip. A centered uppercase mono introduction and four logo cells can sit beneath, still within the same square frame.

**Transfer:** Choose a few understandable metrics and pair them with plain-language captions. Preserve the modest 24px numeral scale.

### Human proof triptych

**Observed:** Three Testimonial cells sit edge-to-edge in a thin frame. Soft 18px italic serif quotes contrast with 16px uppercase mono bylines and small sans organization details beneath a divider.

**Transfer:** Use the editorial serif to change pace after technical demonstrations, with equal-height quote bodies.

### Helpful close and directory

**Observed:** A 216px-tall framed close splits equally: a 40px question and 20px support line on the left, four Resource tiles in a two-by-two matrix on the right, then a full-width human-contact row within that right half. After a 48px spacer, the Footer link cells form a five-column ruled directory. A lower framed band holds small branding, centered lime-dot system status and compact social icons. The technical product variant replaces the conversational close with a documentation heading and four technical resource tiles, without the human row.

**Transfer:** Always end with a helpful resource matrix and a concrete next route, adapted to the buyer's uncertainty. Technical offerings can close on documentation instead of third-party advice. Carry the ledger construction through to the last line rather than adding a separate dark footer.

**Text style:** `heading` — Geist 400 · 40px/1.2

### Tabbed use-case panel

**Only for:** feature pages

**Observed:** Ruled heading pair leads into six narrow equal-width tabs around 184px by 72px. The selected tab is white with a thin violet underline. Beneath, copy anchors low in the left half while an original flow demonstration occupies the right half.

**Transfer:** Use tabs for alternate practical applications of one core capability, not six unrelated product categories.

### Cost and feature comparison

**Only for:** pricing and comparison pages

**Observed:** Pricing starts with an 80px serif title, support copy and a labeled volume slider with violet progress. Two Plan panels share a frame; later a full-width ruled feature table uses compact rows about 45px tall, white label cells and pale neutral value cells. Comparison storytelling pairs a 40px heading with explanatory copy above larger approximately 81px rows and small Savings chips.

**Transfer:** Separate the simple buying choice from the detailed audit table. Keep savings accents small and use real, comparable assumptions.

### Objection ledger

**Only for:** FAQ sections

**Observed:** A 24px heading band uses a 40px/40px heading, sometimes preceded by a colored eyebrow. FAQ rows fill the width; a white closing text-link row invites further questions.

**Transfer:** Write real buying or setup objections as conversational questions, then offer a human route after the accordion.

**Text style:** `faq-heading` — Geist 400 · 40px/1

## Page flow

**Storyline:** Promise → working demonstration → compact proof → capability or value chapters → reassurance → helpful resource close → ruled directory.

### Broad product introduction

1. **promise** — Two-line serif promise, announcement and paired small actions, followed by a pixel landscape operation stage.
2. **product demonstration** — Three technical-resource cells connect the scenic operation to practical entry points.
3. **quantified proof** — Four restrained statistics and a customer-logo strip.
4. **capability chapters** — Numbered ruled modules pair selectable lists with scenic interface demonstrations, then a focused split story and integration directory.
5. **social proof** — Three italic customer quotations.
6. **closing call** — Conversational help matrix, human-contact row and ruled five-column footer.

**Transfer:** Use this as the default broad marketing narrative; vary the number and arrangement of capability chapters to match the new product.

### Alternative evaluation and switching confidence

1. **promise** — Centered serif comparison title with a small paired-symbol illustration and comparison destinations.
2. **differentiation** — Three concise benefit cells introduce the material differences.
3. **pricing proof** — Growth-stage comparison table uses mono cost values and small annual-savings highlights.
4. **capability chapters** — Compact statistics and several scenic demonstrations explain operational advantages.
5. **transition reassurance** — Split introduction and three process pictograms explain migration.
6. **objection handling** — Testimonials and a full-width FAQ.
7. **closing call** — Helpful matrix and standard ruled footer.

**Transfer:** Lead with comparable criteria, then demonstrate why the differences matter and how a user changes over.

### Explain a visual workflow capability

1. **promise** — Centered serif title with selective italic outcome words, category kicker and compact actions.
2. **product demonstration** — Wide scenic workflow demonstration followed by a customer-logo ledger.
3. **onboarding** — Three equal steps explain the mental model.
4. **use cases** — Tabbed applications pair low-anchored copy with a flow demonstration.
5. **measurement** — Scenic split story shows per-step performance.
6. **objection handling** — Question ledger.
7. **closing call** — Conversational resource matrix and standard footer.

**Transfer:** Show the working system early, then reduce it to setup steps and useful applications before answering edge cases.

### Earn technical implementation confidence

1. **promise** — Centered serif capability statement, concise technical support copy and documentation/signup actions.
2. **social proof** — Production-customer logo strip.
3. **product demonstration** — Scenic API example and paired implementation-method panels.
4. **operational proof** — Full-width analytics interface on a scenic backing.
5. **integration reassurance** — Compact ecosystem directory, command example and coding-tool matrix.
6. **closing call** — Documentation resource matrix replaces the conversational close; the same ruled footer follows.

**Transfer:** Favor implementation paths, observability and working examples over broad promotional claims.

### Make a usage-based buying decision understandable

1. **promise** — Short centered serif title and a plain explanation of the billing principle.
2. **pricing** — Usage slider and two aligned plan panels with full-width bottom actions.
3. **value explanation** — Bottom-anchored copy beside a scenic comparison chart and links to alternatives.
4. **detailed evaluation** — A long ruled feature table with aligned plan columns and compact inclusion markers.
5. **reassurance** — Italic testimonial triptych and detailed pricing FAQ.
6. **closing call** — Helpful matrix and standard footer.

**Transfer:** Keep the first decision simple and put detailed plan auditing later; visualize only a pricing variable users can understand.

## Writing

Direct, practical and lightly warm. Technical vocabulary is used without ceremony, and confidence comes from describing operations, costs and outcomes rather than grand positioning.

**Do not copy:** Do not reuse AutoSend or competitor branding, logos, customer portraits, landscape artwork, quotes, prices, volumes, performance metrics or claims. Source quotations below illustrate voice only; replace them with original verified content.

- **Addressing the reader:** Address the reader as you and your, often with an imperative verb. Product descriptions name the product plainly; we and our appear when explaining a specific implementation advantage.
- **Rhythm:** Headlines are usually short outcome statements, sometimes expanded into two balanced lines. Support copy is one or two plain sentences. Punchy fragments contrast with longer technical explanations; occasional exclamation marks appear but are not the default.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the capability and the user-visible result; italicize the useful contrast or outcome words. | 6–12 words | “Automate all emails from conversion to retention.”<br>“Transactional emails that reach inboxes faster!” |
| Supporting line | Explain what the user can do, then state the practical constraint removed. | 15–30 words | “Transactional, marketing & automations in one platform. Priced by volume, not contacts.” |
| Section heading | Concrete operation or payoff, not an abstract category name. | 4–12 words | “Multiple Projects, One Bill.”<br>“Debug email issues before your users report them.” |
| Primary action | Short familiar verb phrase without persuasive decoration. | 2–4 words | “Sign up”<br>“Book a demo” |
| Comparison explanation | Use a short repeated construction to underline a practical difference. | Three brief fragments | “Same list. Same sends. Different bill.” |
| Closing help | A conversational question followed by an invitation to investigate or ask someone. | 2–3 word heading; one support sentence | “Still wondering?”<br>“Talk to a Human” |

**Words and phrasing to use:** clean and simple; drop-in; in minutes; your users; what matters; real-time; automatically; pay for what you use

**Avoid:** revolutionary; unparalleled; synergize; unlock limitless potential; next-generation everything

**Rules:**

- Tie each capability to an actual user task and a visible demonstration.
- State pricing principles in ordinary language before explaining tiers.
- Use compact technical labels for scanability and sentence-case descriptions for understanding.
- Give uncertainty a useful destination: documentation, an independent resource or a human conversation.

## Do's and Don'ts

### Do

- Keep the main serif promise at 80px/1.1 and regular weight on desktop.
- Use 40px/1.2 regular grotesk for most section headings.
- Align ruled sections to the same 1104px inner width.
- Use 24px padding inside shared-border cells and around scenic interface windows.
- Keep conversion buttons at 32px height with 12px corners.
- Make proof numerals compact at 24px rather than competing with the promise.
- Use 80px chapter gaps and 160px separation for major long-form modules.
- Carry the pale ruled system through the closing matrix and footer.

### Don't

- Do not turn every panel into an 8px-rounded floating card; outer section frames are square.
- Do not use the serif for ordinary feature descriptions or navigation.
- Do not make the page predominantly violet; reserve broad color for scenic imagery.
- Do not use pill radii for the primary and secondary actions; their corners are 12px.
- Do not apply the demonstration-window shadow to testimonial cells or footer links.
- Do not enlarge section captions into heavy bold subheadings; mono labels stay compact.
- Do not make feature-table rows spacious promotional cards; the pricing table uses approximately 45px rows.
- Do not make the final helpful close a dark full-bleed sales banner.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare all-property transitions of 75ms with cubic-bezier(.4,0,1,1).
- Resource tiles declare color-related transitions of 0.1s with cubic-bezier(.4,0,.2,1); opacity transitions use the same short timing for icon links.
- A 1s infinite ping is declared for operational-status indicators. Logo entrances declare .5s ease with staggered delays.
- Capability demonstrations use a narrow active progress streak and changing interface states.

**Transfer:**

- Keep control feedback quick and local to the small control or ruled cell.
- Use the active streak to connect a selected capability with the adjacent demonstration; keep the scenery steady enough to read the interface.

**Unknown:**

- Demonstration-cycle durations, full entrance choreography and reduced-motion behavior are unspecified.
- No reliable focus-visible treatment or active scaling behavior is established.

### Responsive

**Observed:**

- Declared width breakpoints include 375px, 600px, 640px, 768px, 1024px, 1280px and 1536px.
- Hero classes specify 40px type below the 1024px desktop display size; section headings commonly specify 32px below 768px.
- The outer wrapper declares 16px side padding before 768px and 24px thereafter. Proof grids declare two columns before 768px and four thereafter.
- Desktop navigation is hidden below 1024px; the five-column footer grid is hidden below 640px.

**Transfer:**

- On narrow screens, retain the serif/mono contrast and scenic stage rather than reducing the design to plain cards.
- Stack text and demonstrations, preserving the frame and logical heading-first reading order. Treat this as an adaptation rule, not a specific mobile composition.
- Reduce major whitespace to the declared 40px and 80px alternatives while keeping useful scene area around the interface.

**Unknown:**

- Mobile menu construction, footer replacement layout and exact demonstration aspect ratios on phones are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
