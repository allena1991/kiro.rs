# OpenSea — collectibles under glass

## Overview

A dark, object-led marketplace aesthetic that makes colorful inventory feel valuable and immediately browsable. White medium-weight grotesk headlines, subdued gray explanations and small monospaced labels sit on charcoal surfaces with fine edges. Cinematic product collages provide the spectacle; dense galleries and compact controls keep the experience practical. It suits products with tangible assets, visual output or a rich catalog, with a more explanatory landing-page treatment alongside the browsing layouts.

### Essentials

- The promise reads like a confident catalog verdict: a centered 60px grotesk headline at weight 500, line height 1.05 and -0.025em tracking, supported by a restrained 16px/24px description.
- The opening is an object theater inside an application shell: a 52px icon rail and 64px top bar frame a 480px-high, 24px-radius stage, with enlarged objects entering from the perimeter and a clear central text zone.
- Actions are small capsules, not heavy rectangles: the primary and secondary hero actions are 48px high with 24px horizontal padding; category filters compress the same silhouette to 32px high.
- Color belongs to inventory, not the whole interface: #101011 canvas, #141415 controls and #17181a explanatory bands dominate, while #0786ff marks the main action. A thin prismatic rim and blurred halo distinguish that action without turning the page into a gradient field.
- Images are merchandise, not background decoration: use black-backed layered objects, 8px-rounded media tiles and bottom fades into the canvas. Without photography, render original product outputs or interface panels as overlapping physical plates.
- Explanations become rounded islands within the catalog: 24px-radius bands with 80px vertical and 48px horizontal padding, centered 32px/40px headings and 12px uppercase mono labels contrast with tighter left-aligned browse sections.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#0786ff` | `--color-blue` | action, accent, link | Primary action, verification marks and keyboard focus outlines. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black canvas | `#101011` | `--color-canvas` | background | Default page canvas and the destination of image fades. |
| Control charcoal | `#141415` | `--color-control` | surface, background | Navigation, benefit cards, support cards and outlined utility actions. |
| Glass fill | `#151516` | `--color-glass` | surface | Visible result of white at 2% over the canvas; used on category filters, search and compact metric cards. |
| Explanatory charcoal | `#17181a` | `--color-band` | surface | Large rounded explanatory and closing question bands. |
| Secondary action fill | `#1a1a1b` | `--color-secondary-fill` | surface | Visible result of white at 4% over the canvas for the secondary hero action. |
| Glass hairline | `#232324` | `--color-glass-edge` | border | Visible result of white at 8% over the canvas; transparent outlines around glass controls. |
| Solid edge | `#26272d` | `--color-rule` | border, surface | Solid card borders, row separators and dark caption plates. |
| Secondary gray | `#acadae` | `--color-muted` | text | Body copy, small labels and inactive filters. |
| White | `#ffffff` | `--color-ink` | text | Headlines, primary labels and action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| data-rich catalog views | Negative red | `#e24756` | `--color-negative` | text | Negative percentage changes. |
| data-rich catalog views | Positive green | `#47bb64` | `--color-positive` | text, accent | Positive percentage changes, live status and sparklines. |

## Typography

- **gtAmerica** — All headings, paragraphs and controls. A matter-of-fact grotesk with broad, highly legible forms and medium rather than bold emphasis. If unavailable, use **Inter**. Use 400 and 500; retain tight tracking only on the hero. Font stack: "gtAmerica", "Inter", ui-sans-serif, system-ui, sans-serif.
- **gtAmericaMono** — Uppercase section labels and numerical market information. Compact utilitarian monospace that gives labels and statistics a trading-terminal character. If unavailable, use **IBM Plex Mono**. Use 400 for labels and metrics, 500 for emphasized prices. Font stack: "gtAmericaMono", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | gtAmerica | 500 | 60px | 1.05 | -0.025em | Centered opening promise on a new marketing or product landing page. |
| heading | gtAmerica | 500 | 32px | 1.25 | normal | Section leads, both left-aligned browse headings and centered explanatory headings. |
| card-heading | gtAmerica | 500 | 18px | 1.25 | normal | Benefit and process-step titles. |
| body | gtAmerica | 400 | 16px | 1.5 | normal | Hero support and section explanations. |
| action | gtAmerica | 500 | 16px | 1.5 | normal | Hero buttons, question rows and support-card titles. |
| caption | gtAmerica | 400 | 14px | 1.5 | normal | Small explanations and inactive filter text. |
| label | gtAmerica | 500 | 14px | 1.5 | normal | Small card titles and compact navigation actions. |
| eyebrow | gtAmericaMono | 400 | 12px | 1.25 | normal, uppercase | Section labels and compact introductory badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| catalog and editorial discovery views | shelf-heading | gtAmerica | 500 | 20px | 1.25 | normal | Compact section leads above repeated gallery shelves. |
| data-rich catalog views | metric | gtAmericaMono | 400 | 14px | 1.5 | normal | Prices, totals and percentage changes in compact rows. |

**Notes:**

- Keep the headline medium-weight rather than bold. Only the 60px display tightens its tracking; section headings and small text remain at normal tracking.
- The default landing-page hierarchy is 60px → 32px → 18px → 16px → 14px, with 12px mono labels. Catalog views use a separate compact 20px section-heading tier.
- Use gray for explanations and white for the item or action being named; do not create hierarchy by continually increasing weight.

## Layout

**Density:** Dense browsing controls and image shelves alternate with comfortable explanatory islands; even the cinematic opening leaves room for the next section in the first viewport.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Small icon-to-label gaps and compact shelf heading pairs. |
| 8px | Filter-to-filter spacing and card title-to-description gaps. |
| 12px | Eyebrow-to-heading and heading-to-support gaps; tight gallery gutters and support-card padding. |
| 16px | Standard image-gallery gutters and benefit-card internal gaps. |
| 20px | Hero text-stack gaps and vertical question-row padding. |
| 24px | Desktop side padding, section separation around raised bands and button horizontal padding. |
| 32px | Benefit-card padding and explanatory heading-to-content gap. |
| 40px | Browse-section vertical padding. |
| 48px | Explanatory band horizontal padding and separation between major content groups. |
| 80px | Explanatory band vertical padding. |

### Containers and grids

- **page container**: max width 1968px · side padding 24px. Centered content region to the right of a 52px desktop icon rail. At 1440px the inner content width is 1340px.
- **heading measure**: max width 672px. Section introduction measure; centered in explanatory bands and left-aligned in browsing sections.
- **hero support**: max width 576px. Balanced two-line support beneath the centered headline; the complete hero stack has a 768px maximum width.
- **benefit grid**: 4 columns · gap 16px. Four equal 299px-wide cards within the padded explanatory band at desktop.
- **process grid**: 3 columns · gap 24px. Equal-width centered process steps linked by a fine horizontal rule.
- **object gallery**: 6 columns · gap 12px. Two rows of portrait-led object tiles, about 213px wide at desktop.
- **question measure**: max width 768px. Centered single-column closing question list.
- **catalog sidebar** (only for data-rich catalog views): max width 367px. Right-hand live metric list beside a narrower 949px primary column.

## Corner radius

| Element | Radius |
| --- | --- |
| actions and filters | 9999px (pill) |
| media tiles and support cards | 8px |
| explanatory cards | 16px |
| hero and bands | 24px |
| search | 6px |
| small media edges | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| subtle card edge | `0px 1px 2px 0px rgba(0, 0, 0, 0.03)` | Compact cards; elevation is conveyed primarily by fine edges, not shadow depth. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous page background.

**CSS:** `background: #101011; color: #ffffff`

#### Navigation charcoal · level 1

**Use:** Persistent top bar and icon rail.

**CSS:** `background: #141415; border-bottom: 1px solid #26272d`

#### Explanatory island · level 1

**Use:** Feature reassurance, process and closing questions.

**CSS:** `background: #17181a; border-radius: 24px; padding: 80px 48px`

**Observed:** Broad inset bands interrupt the otherwise unboxed catalog; their content is centered and arranged in clear horizontal groups.

**Transfer:** Use for explanation that needs a slower reading pace, not for every section.

#### Glass control · level 2

**Use:** Search, filters and small metric tiles.

**CSS:** `background: rgba(255, 255, 255, 0.02); border: 1px solid rgba(255, 255, 255, 0.08); backdrop-filter: blur(40px)`

**Observed:** The effect is restrained and nearly opaque against the dark canvas; search uses a 16px rather than 40px blur.

**Transfer:** Preserve the fine edge and low fill opacity; do not simulate bright frosted glass.

#### Object fade · level 1

**Use:** Lower portion of image-led browse tiles.

**CSS:** `background: linear-gradient(in oklab, rgba(0, 0, 0, 0) 0%, #101011 100%); border-radius: 8px`

**Observed:** The image recedes into the page behind its bottom-aligned label.

**Transfer:** Layer this above product imagery and below readable text.

#### Hero vignette · level 1

**Use:** Darken the center of the opening object scene.

**CSS:** `background: radial-gradient(70% 70% at 50% 45%, rgba(0, 0, 0, 0.78) 0%, rgba(0, 0, 0, 0.55) 45%, rgba(0, 0, 0, 0.25) 100%)`

**Observed:** Darkest behind the centered copy, leaving more of the peripheral imagery visible.

**Transfer:** Keep the text area clear while retaining rich edge detail.

#### Blurred collection spotlight · level 1

**Only for:** catalog and editorial discovery views

**Use:** A highlighted inventory source beside three item cards.

**CSS:** `background: rgba(0, 0, 0, 0.5); backdrop-filter: blur(10px); border-radius: 8px; padding: 24px`

**Observed:** An enlarged image backs the entire panel under a dark blurred layer. The left portion carries identity and monospaced proof; the right holds three sharp item cards. The underlying artwork can make the result blue or gray.

**Transfer:** Borrow the featured inventory's own palette rather than adding an unrelated gradient.

## Components

### Application navigation

**Use:** Persistent orientation around the content.

**CSS:** `height: 64px; background: #141415; border-bottom: 1px solid #26272d; padding: 12px 24px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `label` — gtAmerica 500 · 14px/1.5

**Observed:** A narrow fixed icon rail contains the brand mark and stacked navigation icons. The top bar starts to its right, with search on the left and account actions on the far right.

**Transfer:** Use a compact symbol and a small set of meaningful navigation icons rather than a conventional centered menu.

### Search field

**Use:** Quick catalog search in the top bar.

**CSS:** `max-width: 360px; height: 40px; padding: 0px 8px 0px 12px; border-radius: 6px; background: rgba(255, 255, 255, 0.02); border: 1px solid rgba(255, 255, 255, 0.08); backdrop-filter: blur(16px); display: inline-flex; align-items: center; gap: 6px`

**Observed:** Leading magnifier, short search prompt and a small slash-key hint on the trailing edge.

### Category chip

**Use:** Horizontal primary categories and sticky subcategory filters.

**CSS:** `height: 32px; padding: 0px 12px; border-radius: 9999px; background: rgba(255, 255, 255, 0.02); border: 1px solid rgba(255, 255, 255, 0.08); backdrop-filter: blur(40px); color: #acadae; display: inline-flex; align-items: center; gap: 4px`

**Text style:** `caption` — gtAmerica 400 · 14px/1.5

**Observed:** Small leading pictogram followed by a short label. The selected chip uses white medium text, white at 8% fill and a white-at-12% edge.

**States:** Declared: hover background rgba(255, 255, 255, 0.08) and border rgba(255, 255, 255, 0.12); focus-visible solid 2px #0786ff outline with 2px offset; active scale 1 1 with the hover colors.

### Primary button

**Use:** Main opening conversion action.

**CSS:** `height: 48px; padding: 0px 24px; border-radius: 9999px; background: #0786ff; color: #ffffff; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — gtAmerica 500 · 16px/1.5

**Observed:** The hero action sits inside a thin prismatic rim with a blurred matching halo. Smaller form actions retain the blue capsule but use a 32px height and 14px label.

**States:** Declared: hover background rgb(32 146 255); focus-visible outline-style none; active scale 0.97 and background rgb(32 146 255).

**Transfer:** Keep the halo on the principal action only; use the plain blue version elsewhere.

### Secondary button

**Use:** Explanatory action beside the primary conversion.

**CSS:** `height: 48px; padding: 0px 24px; border-radius: 9999px; background: rgba(255, 255, 255, 0.04); border: 1px solid rgba(255, 255, 255, 0.08); backdrop-filter: blur(8px); color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — gtAmerica 500 · 16px/1.5

**Observed:** Paired with the primary action with a 12px gap; its quieter surface keeps the blue action dominant.

**States:** Declared: hover background rgba(255, 255, 255, 0.08); focus-visible outline-style none; active scale 0.97 and background rgba(255, 255, 255, 0.08).

### Image tile

**Use:** Browse categories, product types and individual visual objects.

**CSS:** `border-radius: 8px; overflow: hidden; position: relative`

**Text style:** `action` — gtAmerica 500 · 16px/1.5

**Observed:** Artwork fills the tile with an Object fade above it and the title anchored near the bottom left. Wide tiles group overlapping objects on black; portrait tiles isolate one central object. Collection-gallery variants use the smaller label recipe.

**Transfer:** Use landscape groups for categories and portrait singles for items; keep title treatment consistent within each row.

### Benefit card

**Use:** Short reassurance or capability statements inside an Explanatory island.

**CSS:** `background: #141415; border: 1px solid #26272d; border-radius: 16px; padding: 32px; display: flex; flex-direction: column; align-items: center; gap: 16px; text-align: center`

**Text style:** `card-heading` — gtAmerica 500 · 18px/1.25

**Observed:** A 44px framed icon holder precedes a medium title and short gray caption. Four equal cards make a single desktop row.

**Transfer:** Name a concrete benefit, then state its mechanism in one short sentence.

### Question row

**Use:** Objection handling at the end of the landing page.

**CSS:** `padding: 20px 0px; text-align: left; width: 100%`

**Text style:** `action` — gtAmerica 500 · 16px/1.5

**Observed:** A left-aligned question and small trailing chevron sit in a 768px-wide centered column. Fine separators produce rows about 65px high. The default view shows collapsed questions.

**Transfer:** Use direct operational questions, not marketing slogans.

### Support card

**Only for:** editorial discovery endings

**Use:** Newsletter, help and contact paths after educational content.

**CSS:** `background: #141415; border: 1px solid #26272d; border-radius: 8px; padding: 12px; display: flex; flex-direction: column; justify-content: space-between; gap: 16px`

**Text style:** `action` — gtAmerica 500 · 16px/1.5

**Observed:** Three equal cards carry a small icon-title row, muted explanation and bottom action. The first has an email field and compact blue button; the other two have full-width outlined capsules.

**Transfer:** End a resource-heavy page with useful next steps instead of a monumental sales pitch.

### Metric tile

**Only for:** data-rich catalog views

**Use:** Compact real-time proof within horizontal shelves.

**CSS:** `background: rgba(255, 255, 255, 0.02); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 8px; padding: 0px 16px 0px 0px; height: 82px; display: flex; gap: 12px; overflow: hidden`

**Text style:** `metric` — gtAmericaMono 400 · 14px/1.5

**Observed:** An asset thumbnail or circular identity leads, a small white name sits above muted monospaced value and colored change, and a compact green sparkline may finish the row.

**Transfer:** Use genuine product metrics; retain small-scale terminal-like typography instead of giant KPI numerals.

## Imagery and graphics

### Peripheral object theater

**Use:** Signature opening scene for a new marketing or product landing page.

**Observed:** Oversized graded-card cases float at varied angles around the edges. Blue-violet rim light catches transparent shells; objects overlap and extend beyond the frame while the middle stays dark for text. The scene occupies the full 480px hero rather than a separate illustration column.

**Transfer:** Stage the new product's objects or outputs as collectible artifacts. A minimum version uses original interface plates or rendered output panels in translucent dark frames, arranged around the same clear center.

**Build:** Create a black-backed 24px-rounded overflow-hidden stage. Place 6–8 portrait plates with translucent rims around its perimeter, rotating left objects about -15deg and right objects about 15deg, with varied scale and partial offscreen clipping. Add narrow blue and violet edge highlights with rgba(56,189,248,0.18) and rgba(168,85,247,0.15), then place the Hero vignette over the scene and the text stack above it. Keep the center free of sharp objects.

### Prismatic action halo

**Use:** Signature accent around the main hero action.

**Observed:** A 166px by 50px capsule surrounds the 164px by 48px blue action; a matching blurred layer adds a restrained multicolor glow.

**Transfer:** Fit the rim to the new label's natural width and keep the effect local to the conversion control.

**Build:** Wrap the button in a 1px-padded capsule. Use a conic-gradient starting at 242.2deg through rgb(45,212,191), rgb(34,211,238), rgb(56,189,248), rgb(99,102,241), rgb(168,85,247), rgb(236,72,153), then back through the same cool stops. Duplicate that gradient behind the wrapper, blur it by 16px and set opacity to 0.7.

### Catalog object collage

**Use:** Category tiles, type selectors and portrait object galleries.

**Observed:** Objects retain their native saturated artwork against black. Landscape tiles layer several upright objects at differing sizes; portrait tiles isolate a single vertical object with a subdued supporting collage behind it. The bottom fades to dark under small white titles.

**Transfer:** Use crisp cutouts or original rendered product outputs; organize them by size and overlap rather than placing them on pastel cards.

### Editorial feature mosaic

**Only for:** catalog and editorial discovery views

**Use:** Promotional carousel and collection shelves.

**Observed:** Large edge-to-edge artwork, including character renders, pixel art and graphic mosaics, appears with 8px corners. Hero labels are white near the lower left; small preview thumbnails line the lower right. The browsing opening can show one large feature or two adjacent features.

**Transfer:** Show actual output breadth and variation; preserve native aspect ratios where needed and use a dark lower scrim for overlaid metadata.

### Bright learning thumbnails

**Only for:** educational shelves

**Use:** Compact how-to resource cards near the page ending.

**Observed:** Landscape 300px by 169px illustrations use cyan, yellow and green backings, floating interface cards, small symbols and soft three-dimensional lighting. A short white title sits below on the dark canvas.

**Transfer:** Commission simple original instructional scenes; the minimum is a clear UI card with two or three softly lit geometric props on one bright backing. Keep these colors inside the image rectangle.

**Build:** Use a saturated single-hue rectangular backing with an 8px radius, a slightly tilted pale interface card, two small spheres or rounded symbols, and soft contact shadows. Arrange the card centrally and leave breathing room around the props.

### Icons

**Observed:** Mostly filled SVG pictograms at 16px and 20px, white or muted gray. Verification marks use blue at 14px; explanatory cards use white 28px symbols within 44px framed holders. Chevrons are small and unobtrusive.

**Transfer:** Choose compact filled symbols with consistent optical weight. Use 16px icons in chips, 20px icons in the rail and larger framed symbols only for explanatory groups.

## Section recipes

How recurring sections are built.

### First screen: Object theater opening

**Observed:** A 52px icon rail and 64px top navigation frame the page. A 68px category strip precedes the 1340px-wide, 480px-high rounded hero. From back to front: peripheral object imagery, Hero vignette, a centered pair of small mono badges, the display headline, a balanced two-line support paragraph and paired Primary button and Secondary button. The headline spans roughly half the available width; the support is limited to 576px. The stack uses 20px gaps and the actions sit 12px apart. Within the first 900px the full hero, a secondary category row, the next section's eyebrow, 32px heading, support and tops of its product cards are visible. Full inventory and explanatory bands continue below.

**Transfer:** Use this as the default landing-page opening: put the new product's strongest promise in a terse centered line and surround it with original outputs or translucent product plates. Catalog pages instead open with one or two image-led editorial slides, lower-left metadata and short progress bars, followed immediately by compact shelves.

**Avoid:** Do not substitute a conventional left-copy/right-mockup hero or an enormous text-only masthead; the clear central promise inside an edge-filled object stage is the defining composition.

**Text style:** `display` — gtAmerica 500 · 60px/1.05 · tracking -0.025em

### Browse introduction

**Observed:** Left-aligned eyebrow, heading and body use 12px vertical gaps with a 672px maximum measure. Browse sections use 40px vertical padding. A gallery begins 24px to 32px beneath the text, with small circular previous/next controls opposite the heading where needed.

**Transfer:** Use short category language and a single practical explanation before showing examples.

**Text style:** `heading` — gtAmerica 500 · 32px/1.25

### Explanatory card island

**Observed:** The Explanatory island holds a centered eyebrow, heading and gray paragraph, then a Benefit card grid after 32px. Four cards use 16px gutters, with framed icons, titles and compact descriptions.

**Transfer:** Explain the mechanisms behind the promise using parallel benefits or assurances rather than long feature essays.

**Text style:** `heading` — gtAmerica 500 · 32px/1.25

### Connected process island

**Observed:** The Explanatory island contains a centered introduction followed by three process columns with 24px gaps. Each column has a framed icon over a short uppercase mono step label, an 18px title and gray 14px explanation. A fine horizontal rule links the icon centers.

**Transfer:** Turn a complex service into three clearly separated actions or responsibilities; align the icon row and keep prose lengths similar.

**Text style:** `card-heading` — gtAmerica 500 · 18px/1.25

### Portrait inventory grid

**Observed:** A Browse introduction leads into six portrait tiles per row, two rows deep, with 12px gutters. Objects are large relative to their short captions, and image fades keep the repeated grid integrated with the canvas.

**Transfer:** Show a breadth of outputs or use cases without inventing a different card style for every item.

### Closing questions island

**Observed:** The landing-page ending is an Explanatory island with centered mono eyebrow and 32px heading, then a 768px-wide stack of five Question rows after 32px. The page ends with restrained dark spacing rather than another sales hero or a multi-column link footer.

**Transfer:** Close with the practical uncertainties most likely to prevent action. Match the calm density and direct question phrasing.

**Text style:** `heading` — gtAmerica 500 · 32px/1.25

### Compact discovery shelf

**Only for:** catalog and editorial discovery views

**Observed:** A 20px heading sits 4px above a gray 14px support line. Content follows after 16px in 300px-wide landscape or square cards with 16px gutters, often continuing past the right edge. Repeated shelves are separated by 48px.

**Transfer:** Group inventory by useful editorial criteria; use the same heading pair and card proportions for each shelf.

**Text style:** `shelf-heading` — gtAmerica 500 · 20px/1.25

### Collection spotlight

**Only for:** catalog and editorial discovery views

**Observed:** A compact shelf heading introduces the Blurred collection spotlight. Identity, monospaced statistics and a short description occupy the left, while three sharp item cards occupy the right. Their lower caption plates use solid dark gray and small white prices.

**Transfer:** Highlight one maker, customer or product family with its own visual palette and concrete proof.

### Learning and utility ending

**Only for:** editorial discovery endings

**Observed:** A compact education heading pair precedes bright 16:9 illustrated resource cards. An editorial discovery view follows this with three Support cards at 12px gutters; a leaner catalog view ends after the learning shelf. Both finish with a small 32px dark tail rather than a large footer.

**Transfer:** Give readers a way to learn, subscribe or resolve questions without changing to a different visual system.

## Page flow

**Storyline:** visual promise → concrete examples → ways to browse → mechanism and reassurance → broader proof → practical next steps

### Product landing page combining a clear proposition with a usable inventory

1. **Promise** — Centered statement and paired actions inside an atmospheric object stage.
2. **Concrete proof** — A horizontally browsable row of recent high-value examples.
3. **Capability discovery** — Wide category collages and a three-way format selector.
4. **Reassurance** — Centered explanation in a rounded band with four benefit cards.
5. **Breadth** — Dense portrait object grid followed by a connected three-step explanation.
6. **Trust** — A horizontal shelf of active verified sources.
7. **Objection handling** — Rounded closing band of collapsed questions with no oversized final CTA.

**Transfer:** Use this as the default marketing structure, adapting the inventory blocks into concrete outputs, integrations or use cases as appropriate.

### High-density catalog overview with live performance context

1. **Orientation** — Category chips and a large editorial image feature beside a persistent market list.
2. **Momentum proof** — Compact value-and-change cards with miniature sparklines.
3. **Discovery** — Repeated landscape shelves alternate curated examples and market movement.
4. **Featured proof** — A collection spotlight combines identity, compact statistics and three items.
5. **Education** — Bright illustrated learning resources form the ending.

**Transfer:** Use for an inventory-heavy portal where the user wants to scan and compare rather than read a long proposition.

### Editorial category destination with visual breadth and helpful utility

1. **Visual invitation** — Two adjacent promotional artwork slides under category chips.
2. **Curation** — Repeated landscape and square artwork shelves organize different creative approaches.
3. **Featured proof** — One blurred collection spotlight with three sharp item cards.
4. **Education** — A horizontal learning shelf explains core concepts.
5. **Practical next steps** — Three small newsletter, help and support cards end the content.

**Transfer:** Use for a focused category or resource destination; preserve the compact shelf hierarchy instead of importing the large landing-page heading into every shelf.

## Writing

Confident, practical and collector-literate without sounding grandiose. The promise is compressed, while explanations clarify ownership, responsibility and what the reader can actually do.

**Do not copy:** Do not reuse OpenSea names, logos, partner identities, artwork, collection titles, proprietary claims, market prices, sales totals or verification claims as the new product's content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for practical benefits and instructions. Refer to the product by name when explaining its role; reserve impersonal wording for inventory and market summaries.
- **Rhythm:** Short noun-led headings, usually two to six words, alternate with one-sentence explanations. Hero support may be two short sentences. Action labels are direct and unpunctuated; avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category, then resolve it with a compact verdict separated by periods. | 3–6 words | “Trading cards. Collected.” |
| Section heading | Simple browsing instruction or concrete category of proof. | 2–6 words | “Shop by type”<br>“Top sales this past week” |
| Supporting line | Explain what is included and where responsibility sits. | 12–30 words | “Partner platforms handle the physical card. You trade the digital version. Here's how it fits together.” |
| Primary action | Start with a familiar verb and name the immediate activity. | 2–4 words | “Start collecting”<br>“See how it works” |
| Catalog support | State a time window or curation criterion plainly. | 4–12 words | “Collections with momentum today”<br>“This week's curated generative art collections” |
| Closing question | Ask the operational question in the user's own language. | 5–9 words | “Who authenticates and stores the cards?” |

**Words and phrasing to use:** browse; explore; start; your; how it works; trusted; popular; curated; today

**Avoid:** revolutionary; world-changing; unleash; limitless; magic-powered; join the revolution

**Rules:**

- Prefer a specific mechanism to a vague benefit: who handles what, and what the user receives.
- Make each shelf subtitle state why these examples belong together.
- Use short uppercase eyebrows to classify sections, not to add another slogan.
- Keep helper and support language straightforward and service-oriented.

## Do's and Don'ts

### Do

- Keep the main display at 60px/1.05, weight 500, with -0.025em tracking.
- Use 12px uppercase mono section labels with normal tracking.
- Pair 48px-high capsule actions with a 12px gap in the hero.
- Keep desktop content inset by 24px to the right of the 52px rail.
- Use 24px-rounded explanatory islands with 80px vertical padding.
- Keep imagery crisp and saturated while the surrounding surfaces stay near-black.
- Use 16px gutters for wide inventory shelves and 12px for dense portrait grids.
- Close a landing page with practical question rows inside the same rounded-band system.

### Don't

- Do not make all headings bold at 700; the visual hierarchy depends on medium 500.
- Do not turn explanatory bands into white cards; their tonal separation is #17181a against #101011.
- Do not use the prismatic effect as a full-page rainbow background; its strongest UI role is a 1px action rim.
- Do not apply 24px corners to every small tile; ordinary media uses 8px.
- Do not center the copy above browsing shelves; left-aligned headings distinguish scanning from explanatory sections.
- Do not replace monospaced prices with giant decorative statistics in compact catalog layouts.
- Do not add deep floating-card shadows; fine 1px borders carry the separation.
- Do not append a towering multi-column footer to the lean dark endings.

## Motion and responsive

### Motion

**Observed:**

- Hero actions and category controls declare scale/color transitions of 0.2s ease-out; primary and secondary hero actions scale to 0.97 when active.
- Navigation backdrop opacity declares 0.2s cubic-bezier(0.22, 1, 0.36, 1). Search background and shadow declare 0.15s ease-out.
- Live status dots in catalog views declare a 1s infinite ping animation with cubic-bezier(0, 0, .2, 1).

**Transfer:**

- Keep interaction movement at control scale: subtle pressed capsules, color changes and low-key opacity changes.
- Use the live-status ping only for genuinely live activity.

**Unknown:**

- Carousel autoplay cadence, object-scene movement and scroll-trigger timing are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints including 640px, 768px, 1024px and 1280px.
- Benefit-card markup specifies one column, two at the small tier and four at the large tier. Utility cards specify one column then three at the medium tier.
- Desktop side padding is 24px; container classes also declare a 16px narrower-screen padding tier.

**Transfer:**

- On narrow screens, retain the centered promise and peripheral object staging but reduce the number of visible objects rather than squeezing all of them in.
- Stack paired actions when necessary and let category chips scroll horizontally.
- Preserve the contrast between compact browse shelves and padded explanatory bands as grids collapse.

**Unknown:**

- Exact rendered mobile headline sizes, navigation behavior and object positions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
