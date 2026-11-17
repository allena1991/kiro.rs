# Mailchimp — editorial with a wink

## Overview

An approachable, commercially confident style that pairs expressive editorial serifs with practical grotesk text. White and pale gray pages are punctuated by warm brown-black bands, electric yellow actions, and a generous ochre footer. Real people at work, vivid customer photography, and neatly staged interface collages balance human warmth with product utility; broad sections feel spacious while cards and pricing remain information-rich.

### Essentials

- An editorial promise with a bright aside: regular Means Web at 64px/1.2 with -1.2px tracking, followed by an italic yellow phrase at the same scale; section leads settle to 40px/1 with -0.5px tracking.
- A human scene carries the first impression: a full-width workplace photograph under a 25% black veil, centered headline, 20px/32px support, a 343px-wide yellow action, and a compact review cluster below.
- Buttons behave like small physical objects: 44px-high yellow or outlined capsules, 26px radius, 12px 24px padding, and a 1px ink ring; hover lifts the capsule above an ink-colored base.
- Color arrives in decisive blocks, not confetti: white and #f5f5f5 carry most of the narrative, #231e15 anchors proof and closing calls, #ffe01b marks actions and short emphasis, and #e7b75f owns the expansive footer.
- Proof is made editorial: include a large photographic story card with a serif quote over its lower edge and a narrow white results rail using 48px/48px numerals. Without customer photography, stage a real product or work artifact with the same quote-and-results structure.
- Utility gets a playful yellow punctuation mark: text actions end in a 32px yellow circle with an ink arrow; carry this device through capability and proof links.
- The ending has its own color and scale: a centered 40px serif closing statement in a dark band, then supporting disclosures and an ochre footer with five link columns, thin rules, and a compact bottom utility area.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric yellow | `#ffe01b` | `--color-yellow` | action, accent, background | Primary actions, arrow discs, italic hero emphasis and highlighted results. Full yellow bands belong to the content-led campaign variant. |
| Ochre | `#e7b75f` | `--color-footer` | background, link | Marketing footer canvas; warm links in the technical theme. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Peppercorn ink | `#231e15` | `--color-ink` | text, background, border | Default warm text, dark narrative bands, button rings and icons. |
| Secondary ink | `#706d67` | `--color-muted` | text | Visible 65% peppercorn over white for attribution and secondary price information. |
| Card edge | `#bcbab6` | `--color-edge` | border | Results rails, offer choices and card dividers. |
| Soft ink rule | `#bdbcb9` | `--color-rule` | border | Visible 30% peppercorn over white; use rgba(35,30,21,0.3) for accordion and control outlines. |
| Pale gray | `#f5f5f5` | `--color-band` | background | Capability and trial-offer section backgrounds. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, cards, inverse text and the visible white results rail; the rail uses white at 0.93 alpha. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| developer portals | Signal green | `#00c14e` | `--color-green` | accent, text | Oversized technical metrics and dark-theme mono labels. |
| developer portals | Technical teal | `#007c89` | `--color-teal` | action, text | Technical buttons and light-theme mono labels. |
| developer portals | Deep technical navy | `#001d28` | `--color-navy` | background, text | Technical product bands and light-theme headings. |
| developer portals | Technical slate | `#0c2832` | `--color-navy-soft` | background | Technical proof, testimonial and footer bands. |
| developer portals | Slate text | `#3d535b` | `--color-slate-text` | text, border | Technical body copy on paper and footer rules. |
| pricing comparisons | Comparison edge | `#bcbab8` | `--color-table-edge` | border | Pricing-table column outlines. |
| pricing comparisons | Feature separator | `#dbd9d2` | `--color-table-rule` | border | Pricing feature row separators. |
| developer portals | Technical paper | `#efeeea` | `--color-technical-paper` | background, text | Technical opening and illustration panels; inverse technical copy. |
| embedded pricing comparisons | Pricing paper | `#f6f6f4` | `--color-pricing-paper` | background | Warm pale background behind the extended plan-card comparison. |

## Typography

- **Means Web** — Display headlines, section leads, quotes and large results. Soft, expressive editorial serif with a lively italic, distinctive terminals and compact headline setting. If unavailable, use **Lora**. Use regular and italic at 400; use 400 as the nearest practical light technical cut. Font stack: "Means Web", "Lora", Georgia, Times, 'Times New Roman', serif.
- **Graphik Web** — Supporting prose, capability titles, navigation, buttons and forms. Even, pragmatic geometric grotesk; regular text and restrained medium-weight controls. If unavailable, use **Inter**. Use 400–600 and preserve the relatively open body leading. Font stack: "Graphik Web", "Inter", 'Helvetica Neue', Helvetica, Arial, Verdana, sans-serif.
- **Input Mono** (only for developer portals) — Uppercase technical category labels. Mechanical mono with generously tracked capitals. If unavailable, use **IBM Plex Mono**. Font stack: "Input Mono", "IBM Plex Mono", Courier, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Means Web | 400 | 64px | 1.2 | -0.0187em | fixed | Default photographic opening headline. |
| display-aside | Means Web | 400 italic | 64px | 1.2 | -0.0187em | fixed | Yellow second phrase of the opening headline. |
| heading-lg | Means Web | 400 | 48px | 1 | -0.0208em | size max(28px, min(5.5vw, 48px)) | Trial-offer headline and large results. Results use the fluid scale given here. |
| heading | Means Web | 400 | 40px | 1 | -0.0125em | fixed | Primary section leads and closing statements. |
| quote | Means Web | 400 | 32px | 1.25 | normal | fixed | Customer quote laid over photography. |
| card-heading | Graphik Web | 400 | 23px | 30px | normal | fixed | Compact capability-card headings. |
| hero-support | Graphik Web | 400 | 20px | 1.6 | normal | fixed | Support beneath the photographic opening headline. |
| body | Graphik Web | 400 | 16px | 1.75 | normal | fixed | General explanatory prose and proof captions. |
| arrow-link | Graphik Web | 400 | 16px | 2 | normal | fixed | Text actions paired with yellow arrow discs. |
| footer-heading | Graphik Web | 400 | 16px | 1.5 | normal | fixed | Footer column labels. |
| hero-action | Graphik Web | 600 | 15px | 1.6 | normal | fixed | Wide primary action in the photographic opening. |
| card-body | Graphik Web | 400 | 14px | 1.5 | normal | fixed | Capability-card descriptions. |
| action | Graphik Web | 500 | 13px | 1.5 | normal | fixed | Standard capsule actions. |
| navigation | Graphik Web | 500 | 13px | 1.1 | normal | fixed | Dense main navigation links. |
| footer-link | Graphik Web | 400 | 13px | 1.35 | normal | fixed | Underlined directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| developer portals | technical-stat | Means Web | 300 | 74px | 1.1 | normal | fixed | Green results above short reliability captions. |
| developer portal openings | technical-display | Means Web | 300 | 54px | 1 | -0.03em | fixed | Light serif technical opening headline. |
| developer portals | technical-heading | Means Web | 300 | 54px | 1.02 | -0.02em | fixed | Editorial program and community section headings. |
| developer portals | technical-product | Means Web | 300 | 54px | 1 | -0.02em | fixed | Large linked product titles in the two-column documentation gateway. |
| solution and pricing support sections | split-heading | Means Web | 400 | 40px | 1.2 | -0.0125em | fixed | Multiline editorial headings beside half-width imagery. |
| solution capability chapters | feature-heading | Graphik Web | 400 | 32px | 1.25 | normal | fixed | Practical product-feature headings beneath or beside demonstration media. |
| developer portals | technical-quote | Means Web | 300 | 28px | 1.4 | -0.01em | fixed | Centered testimonial before the footer. |
| solution landing pages and FAQs | solution-lead | Graphik Web | 400 | 24px | 32px | -0.0133em | fixed | Large supporting lines and accordion questions. |
| solution capability chapters | feature-body | Graphik Web | 400 | 20px | 1.5 | normal | fixed | Longer explanations of mechanisms and benefits. |
| developer portal openings | technical-body | Graphik Web | 400 | 19px | 1.5 | normal | fixed | Slate supporting prose. |
| developer portals | technical-label | Input Mono | 400 | 14px | 1.5 | 0.08em, uppercase | fixed | Technical product and program eyebrows. |
| solution landing pages | eyebrow | Graphik Web | 500 | 13px | 1.25 | normal, uppercase | fixed | Category marker above the main promise or a capability chapter. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Serif headlines are expressive but not heavy. Keep marketing headings at 400; the technical theme uses 300.
- Do not carry the italic hero treatment into every heading. Short highlighted price words use a yellow underline instead.
- Sans headings take over when explaining a specific product mechanism; serif headings organize the broader narrative.
- Keep the 40px/40px section lead distinct from the roomier 40px/48px split-feature variant.

## Layout

**Density:** Airy at section level, compact inside controls and comparison tables; the change in density keeps long commercial pages readable.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Result-to-caption and tight list gaps. |
| 12px | Card text stacks and button vertical padding. |
| 16px | Card-grid gutters, media-tile padding and heading-to-support gaps. |
| 24px | Section-heading support gaps, standard button horizontal padding and three-column gutters. |
| 32px | Proof cluster spacing and compact offer-band padding. |
| 40px | Heading-to-closing-action separation and results-rail padding. |
| 48px | Capability-card content padding. |
| 64px | Heading-to-story-card separation and horizontal logo-band padding rhythm. |
| 80px | Default major section vertical padding and desktop content margin. |
| 120px | Deep resource-download band padding. |

### Containers and grids

- **Marketing container**: max width 1280px · side padding 80px. Centered desktop narrative area at 1440px; full-bleed surfaces continue outside it.
- **Centered statement**: max width 853px. Centered editorial promises, solution openings and closing calls.
- **Capability grid**: 2 columns · gap 16px. Two broad cards per row, each combining text on the left and a narrow product scene on the right.
- **Editorial thirds**: 3 columns · gap 24px. Three capability or learning cards, approximately 411px each at desktop.
- **Split chapter**: 2 columns · gap 53px. Alternating roughly 613px-wide text/media columns; media can instead meet text at the midpoint with a 640px half-width.
- **Footer directory**: max width 1200px · 5 columns. Five uneven-width, widely separated link columns above a centered utility area.
- **FAQ layout** (only for solution and pricing FAQs): max width 1280px · 2 columns · gap 40px. Small left title rail beside a 960px question list.
- **Comparison table** (only for pricing comparisons): max width 1240px · 4 columns · gap 0px. Four equal 310px columns with shared edges and aligned feature rows.
- **Technical container** (only for developer portals): max width 1188px · side padding 24px. 1140px content area inside a centered outer container.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Standard actions | 26px |
|  | Hero action | 40px |
|  | Story and capability cards | 24px |
|  | Utility tiles | 16px |
|  | Inputs | 4px |
|  | Arrow discs | 50% |
| pricing offers | Offer choices | 10px |
| developer portals | Technical buttons | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Story card | `rgba(35, 30, 21, 0.06) 0px 8px 64px 0px, rgba(35, 30, 21, 0.04) 0px 4px 8px 0px` | Broad soft lift around a photographic proof card. |
| Capability card | `rgba(0, 0, 0, 0.06) 0px 4px 16px 0px` | Very soft lift against a pale gray capability band. |
| Utility tile | `rgba(0, 0, 0, 0.086) 0px 15.5px 44px 0px` | Floating integration tiles. |
| Offer card | `rgba(35, 30, 21, 0.15) 0px 0px 20px 3px` | Recommended single-plan conversion card. |

### Surfaces

#### White canvas · level 0

**Use:** Main page and editorial chapters.

**CSS:** `background: #ffffff; color: #231e15`

#### Pale gray band · level 0

**Use:** Capability collections and trial offers.

**CSS:** `background: #f5f5f5`

#### Peppercorn band · level 0

**Use:** Proof statements, media features and closing calls.

**CSS:** `background: #231e15; color: #ffffff`

**Observed:** Broad, flat warm-black planes with minimal decoration.

**Transfer:** Let the type and photography carry these sections; keep the dark ground warm rather than blue.

#### Ochre footer · level 0

**Use:** Expansive final directory and utility area.

**CSS:** `background: #e7b75f; color: #231e15; padding: 60px 0px`

#### Photo veil · level 1

**Use:** Legibility over opening photography.

**CSS:** `background: rgba(0, 0, 0, 0.25)`

#### Quote fade · level 1

**Use:** Lower portion of customer photography behind the quotation.

**CSS:** `background: linear-gradient(rgba(35, 30, 21, 0) 0%, rgba(35, 30, 21, 0.55) 45%, rgba(35, 30, 21, 0.82) 100%)`

#### Yellow campaign band · level 0

**Only for:** content-led solution campaigns

**Use:** A proof chapter or concise closing call.

**CSS:** `background: #ffe01b; color: #231e15; padding: 80px 0px`

**Transfer:** Use as an intentional full-width change of pace, not as a fill for every card.

#### Pricing paper · level 0

**Only for:** embedded pricing comparisons

**Use:** Backdrop for a raised recommended column.

**CSS:** `background: #f6f6f4`

#### Technical dark bands · level 0

**Only for:** developer portals

**Use:** Documentation gateway and community messaging.

**CSS:** `background: #001d28; color: #efeeea`

**Observed:** Proof, quote and footer bands shift to #0c2832; the opening and illustrated program feature use #efeeea.

**Transfer:** Keep this theme internally consistent rather than mixing navy with marketing peppercorn on the same page.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #ffe01b; color: #231e15; border-radius: 26px; padding: 12px 24px; height: 44px; box-shadow: #231e15 0px 0px 0px 1px`

**Text style:** `action` — Graphik Web 500 · 13px/1.5

**Observed:** Centered label, no trailing icon. A dark-filled inverse version appears alongside outlined actions in proof sections. The photographic opening expands to 343px by 48px with 40px radius and the hero-action recipe.

**States:** Declared: hover lifts by 0.375em with an ink base shadow of 0.375em; focus-visible outline none; active reduces the base to 3.3px and translates upward by half that amount.

**Transfer:** Use one visually dominant conversion action per local group.

### Secondary button

**Use:** Lower-emphasis action beside a primary action or at the end of explanatory copy.

**CSS:** `color: #231e15; background: transparent; border-radius: 26px; padding: 12px 24px; height: 44px; box-shadow: #231e15 0px 0px 0px 1px`

**Text style:** `action` — Graphik Web 500 · 13px/1.5

**Observed:** Same capsule geometry as the primary, with the section surface showing through.

**States:** Declared: hover retains transparent fill and lifts by 0.375em above an ink base; focus-visible outline none; active uses a 3.3px base.

### Arrow link

**Use:** Capability, proof and directory-level forward actions.

**CSS:** `color: #231e15; padding: 0px 40px 0px 0px; height: 32px; position: relative`

**Text style:** `arrow-link` — Graphik Web 400 · 16px/2

**Observed:** An ink right arrow sits in a yellow circular disc at the trailing edge. Compact card variants use 15px medium labels and smaller discs.

**States:** Declared: hover translates 4px to the right with no underline; focus-visible outline none.

**Transfer:** Repeat the disc as the small recognizable action marker instead of replacing it with a generic chevron.

### Main navigation

**Use:** Persistent desktop navigation above the product story.

**CSS:** `background: rgba(255, 255, 255, 0.592); padding: 12px 16px; height: 68px; z-index: 500`

**Text style:** `navigation` — Graphik Web 500 · 13px/1.1

**Observed:** Sticky white-looking bar: logo left, compact category links with down chevrons, utility/search/language controls, then outlined login and yellow conversion. A slim corporate strip and dark offer strip sit above it initially.

**States:** Declared: navigation items use a 5% ink hover wash; focus-visible uses a 2px turquoise outline with 2px offset.

**Transfer:** Use the product's own compact identity and categories; keep utilities subordinate to conversion.

### Capability card

**Use:** Broad capability summaries in a pale gray collection.

**CSS:** `background: #ffffff; border-radius: 24px; display: flex; overflow: hidden`

**Text style:** `card-heading` — Graphik Web 400 · 23px/30px

**Observed:** A small outline icon leads the left text column, then heading, 14px description, checkmarked benefits and a bottom arrow action. The right side holds a portrait-format product or photographic tile, approximately 212px by 266px. Content has 48px breathing room.

**Transfer:** Pair one outcome and a short benefit list with one tangible artifact; keep image and text distinct.

### Story results rail

**Use:** Quantified customer proof beside a large photograph.

**CSS:** `background: rgba(255, 255, 255, 0.93); border: 1px solid #bcbab6; border-radius: 0px 24px 24px 0px; padding: 40px; display: flex; flex-direction: column`

**Text style:** `heading-lg` — Means Web 400 · 48px/1 · tracking -0.0208em

**Observed:** A roughly 283px rail joins the photograph without a gutter. Two large serif results sit at the top with captions and a thin divider; attribution and an arrow action sit near the bottom. The whole card is 650px tall, softly lifted, with a partial next slide visible.

**Transfer:** Use a small number of verified results, not a dense dashboard.

### Integration tile

**Use:** Floating utility or compatibility cards in horizontal tracks.

**CSS:** `border-radius: 16px; padding: 16px; display: flex; align-items: center; gap: 16px; box-shadow: rgba(0, 0, 0, 0.086) 0px 15.5px 44px 0px`

**Text style:** `footer-heading` — Graphik Web 400 · 16px/1.5

**Observed:** White-looking 446px by 112px tiles combine an 80px pale icon well with a medium name and short 14px descriptor. Staggered rows extend beyond both viewport edges.

**Transfer:** If there is no integration ecosystem, use real workflow tools or supported formats in the same short, useful tile structure.

### Single plan card

**Use:** Compact conversion panel next to a broader offer explanation.

**CSS:** `background: #ffffff; padding: 24px 16px; width: 370px; box-shadow: rgba(35, 30, 21, 0.15) 0px 0px 20px 3px`

**Text style:** `heading` — Means Web 400 · 40px/1 · tracking -0.0125em

**Observed:** Square outer panel with serif plan title, send allowance, contact selector, rounded selectable offer boxes, a wide primary action and small terms. The left narrative has a two-column checked-benefits list; a segmented pill above switches offer modes.

**Transfer:** Keep the panel a focused decision aid rather than a miniature full comparison table.

### Form input

**Use:** Email signup or resource-download forms.

**CSS:** `background: #ffffff; border: 1px solid #231e15; border-radius: 4px; padding: 20px; height: 60px`

**Observed:** Visible label above the field, restrained rectangular geometry; download forms pair equal-width email and select fields. The compact opening signup variant is 43px high.

**Transfer:** Keep fields visibly different from capsule buttons and place consent copy below the field group.

### Footer link

**Use:** Compact underlined directory navigation.

**CSS:** `color: #231e15; text-decoration: underline`

**Text style:** `footer-link` — Graphik Web 400 · 13px/1.35

**Observed:** Links form loose vertical lists beneath 16px regular headings, not bold navigation tiles.

**States:** Declared: hover adds a 65% yellow highlight and a 3.3px highlight spread; focus-visible uses a 2px turquoise outline with 6.5px offset.

### FAQ row

**Only for:** solution and pricing FAQs

**Use:** Objection handling in a right-hand question list.

**CSS:** `border-top: 1px solid rgba(35, 30, 21, 0.3); min-height: 81px`

**Text style:** `solution-lead` — Graphik Web 400 · 24px/32px · tracking -0.0133em

**Observed:** Each full-width question button has 24px vertical padding and a yellow 32px plus disc aligned at the far right. The section's serif title sits separately in a narrow left rail.

**Transfer:** Use plain questions and the same ruled structure; allow long questions to wrap without shrinking them.

## Imagery and graphics

### Workplace photography

**Use:** Opening scene and human support chapters.

**Observed:** Warm, believable small-business workplaces: a person using a desktop, a shop studio, a bright table with a laptop. The wide opening scene fills the full width behind text; support images occupy about half the content width. Natural light, real materials and slightly busy environments replace pristine studio abstraction.

**Transfer:** Photograph a person accomplishing the new product's core task. Leave calm negative space for headline contrast; when people are unavailable, photograph a real workspace and its tools rather than an isolated stock laptop.

### Customer story photography

**Use:** Large proof cards.

**Observed:** Close portrait, vivid packaged goods or active real-world business scenes fill about three quarters of a joined card. Images are full-bleed and clipped by 24px outer corners, with a dark lower fade supporting white serif testimony.

**Transfer:** Use a real customer, meaningful product arrangement or work setting. Preserve strong subject scale and truthful color; do not turn the image into a tiny avatar.

### Product artifact collage

**Use:** Capability cards and solution chapters.

**Observed:** Layered email designs, phones, charts, workflow branches and editing panels on pale gray, cream or muted warm-colored backings. Interfaces are enlarged and selectively cropped, often with a cursor or floating white tool panel. Rectangular media occupy roughly half a split section or the top of a three-column card.

**Transfer:** Make a legible demonstration of one mechanism: one main product artifact with one or two supporting panels. Minimum version is a clean static mockup with meaningful data, not an entire application squeezed into a frame.

**Build:** Use a pale gray rounded 24px stage. Place a main rectangular artifact inset about 40px and a white secondary panel overlapping its right edge; apply only a subtle neutral shadow. Add a simple ink pointer or one connecting line where it explains the task. Keep bright chart and interface colors inside the demonstration rather than spreading them across the page.

### Highlighted result

**Use:** A quantitative proof statement inside a dark editorial band.

**Observed:** An inline serif revenue figure sits on a flat yellow marker with 3px corners. It reads as part of the sentence rather than a detached badge.

**Transfer:** Include a short highlighted, verified result or a concrete product outcome in an editorial statement.

**Build:** Wrap only the key phrase in an inline element with background #ffe01b, color #231e15, border-radius 3px and padding 2.4px 7.2px. Keep the surrounding text white and the figure at the sentence's serif scale.

### Technical cut-paper illustration

**Only for:** developer portals

**Use:** Light technical openings and program features.

**Observed:** Dark navy hand-like and geometric machine forms with chalky, scratched textures, cream negative space and sparse bright green circles. The opening illustration is a compact 300px square; a later feature uses a 380px square. It is flat editorial art, not glossy 3D.

**Transfer:** Create an original abstract assemblage suggesting the new tool's mechanisms. Minimum version uses a few strong navy shapes and green signal dots with hand-drawn line detail.

**Build:** Compose an SVG square from navy rectangles, semicircles, tapered organic silhouettes and cream cutouts. Add thin cream arcs, hatching, grids and starbursts; overlay very light monochrome grain. Limit #00c14e to a few small discs or triangles and retain abundant #efeeea negative space.

### Icons

**Observed:** Marketing actions use filled ink arrows or plus signs in yellow circles, usually 32px. Capability markers are small, thin outline pictograms rather than colored app icons. Product logos retain their own colors only within utility or demonstration areas.

**Transfer:** Use a consistent simple outline family for capabilities, and build the recurring arrow/plus discs with plain SVG geometry. Keep pictograms subordinate to headings.

## Section recipes

How recurring sections are built.

### First screen: Photographic promise opening

**Observed:** Two slim utility/offer strips precede a 68px sticky navigation bar. Below it, a 632px-tall full-width workplace scene is layered with Photo veil and centered text. The 64px serif headline spans roughly two thirds of the viewport; its second phrase is yellow italic. The support line sits 24px below the headline, followed by the wide Primary button with hero-action typography and 40px separation. A centered stars-and-review cluster with small review-service marks occupies the lower part of the photograph. Within the first 900px, navigation, both headline phrases, support, action, social proof and the next pale gray section title are visible; capability cards begin below the fold.

**Transfer:** For a different product, retain the human scene, editorial two-part promise, wide capsule and compact proof cluster. If a photograph is unavailable, stage a real product artifact at large scale on a warm dark backing with equally clear text contrast. Solution pages can instead use a white, centered 853px text opening with a 48px serif promise and email signup, or a half-text/half-photo opening; pricing starts with offer-mode tabs and the Single plan card. Technical portals use the light illustrated variant.

**Avoid:** Do not replace this with a generic left-aligned SaaS headline and tiny dashboard, or make the whole first screen a yellow field. Do not let background activity compete with the italic phrase.

**Text style:** `display` — Means Web 400 · 64px/1.2 · tracking -0.0187em

### Capability collection

**Observed:** Pale gray band with 80px top and bottom padding, a 40px serif title aligned left and a small outlined customization action right. A 64px separation leads to the two-column Capability grid. Cards share the same height and image/text structure; a centered price action follows.

**Transfer:** Group a handful of distinct outcomes with concrete artifacts. Keep the editorial header outside the cards.

### Editorial result band

**Observed:** Peppercorn band with a small yellow context label, a white serif statement, Highlighted result inline, qualification beneath and an Arrow link. A vertical progress rail distinguishes the rotating proof treatment.

**Transfer:** Use one result that deserves a sentence, with its denominator or timeframe nearby; retain the inline marker device even when the result is not financial.

### Photographic proof carousel

**Observed:** White section with 80px padding, serif headline and Arrow link, then a large joined image/Story results rail card after 64px. The photo carries a lower-left category and quote using Quote fade. A sliver of the next card appears at the right edge; short horizontal slide indicators and paired conversion actions follow.

**Transfer:** Tell one specific customer outcome at a time. Preserve the split between lived experience and measurable result.

### Alternating capability chapters

**Observed:** White sections alternate half-width Product artifact collage or photography with text. Broad editorial headings use split-heading; detailed mechanisms use feature-heading and feature-body. Heading-support gaps are 16px or 24px, action gaps are 24px or 40px, and major chapters use 80px vertical padding.

**Transfer:** Switch image/text sides to create cadence without inventing a new card shell for every feature.

### Floating compatibility field

**Observed:** Centered serif heading, support and Arrow link above three staggered horizontal tracks of Integration tile components. Tracks bleed off both viewport sides; 24px tile gaps and soft shadows create a light floating field.

**Transfer:** Use compatibility, workflow or supported-format content relevant to the new product; retain the clipped, staggered field rather than a rigid logo matrix.

### Offer explanation and decision panel

**Observed:** Pale gray band pairs a broad left narrative with a 370px Single plan card on the right. A 48px serif headline gives one price word a yellow underline. Checked benefits form two columns; the panel contains selectable offer boxes and a full-width action.

**Transfer:** Separate the persuasive reason to choose from the controls needed to decide.

### Closing call and ochre directory

**Observed:** Peppercorn band with 80px padding frames a centered 40px serif statement within 853px, then a yellow Primary button after 40px. A content-led campaign variant uses a yellow band with an outlined action. Supporting disclosures precede the Ochre footer: related links, full-width rules, five directory columns, then a lower utility zone with affiliated identities, app/social marks, language selector and legal text.

**Transfer:** End the persuasive story before the directory begins. Make the final statement short and affirmative, and keep the ochre footer substantial rather than a narrow strip.

### Pricing comparison

**Only for:** pricing pages and embedded comparisons

**Observed:** Four adjoining plan columns with fine gray borders, compact text, offer choice boxes and aligned actions. The recommended middle paid tier gains a pale blue best-value ribbon; the embedded version is taller and raised. The full pricing page continues into a ruled feature matrix with alternating pale rows, checks and crosses, then awards, onboarding support, alternative buying routes and FAQs.

**Transfer:** Align comparable information across columns. Use recommendation elevation on only one tier, keeping choice controls and feature descriptions compact.

### Resource download band

**Only for:** lead-generation solution pages

**Observed:** Peppercorn band with 120px vertical padding, centered 40px serif title, 24px support and two labeled white Form inputs in a row. Small consent text spans beneath, with one centered yellow action.

**Transfer:** Offer a specific useful resource rather than a vague newsletter promise; preserve the broad dark field and restrained form geometry.

### Technical gateway and ending

**Only for:** developer portals

**Observed:** A compact paper-colored illustrated opening leads directly into two navy documentation columns, with tracked mono category labels, 54px light serif linked titles, stacked warm links and explanatory text. A slate band uses three 74px green results separated by top rules. Paper illustration features and navy community messaging lead to a centered 28px serif testimonial; the slate footer has two navigation groups and a join-account column, followed by affiliated identities, small uppercase utility links and a final rule.

**Transfer:** Prioritize routes to documentation and trust in infrastructure. Keep the terminal testimonial and footer in the same dark slate family, without importing the marketing ochre ending.

## Page flow

**Storyline:** Promise → tangible capabilities → credible results → decision support → ecosystem and learning → objection handling → confident closing call → substantial utility ending.

### Broad product or platform landing page

1. **Promise** — Photographic editorial opening with a yellow italic aside and review proof.
2. **Capability selection** — Pale gray collection of broad, image-backed capability cards.
3. **Quantified proof** — Logo reassurance, dark highlighted result band and photographic story carousel.
4. **Decision support** — Focused trial narrative paired with a single plan panel.
5. **Ecosystem** — Floating utility tiles across staggered tracks.
6. **Closing call** — Dark centered statement, disclosures and a substantial ochre directory.

**Transfer:** Use a broad range of benefits but give each chapter a different form of proof; keep the product story ahead of pricing mechanics.

### Plan selection and commercial comparison

1. **Decision framing** — Offer-mode tabs and a focused recommended-plan offer.
2. **Comparison** — Contact selector, recommendation strip, four plan columns and feature matrix.
3. **Reassurance** — Dark award band and human onboarding photography.
4. **Alternative routes** — Two editorial text columns and a centered pale band for smaller needs.
5. **Objection handling** — Ruled FAQ list.
6. **Utility ending** — Detailed terms and the shared ochre directory; no separate final conversion band.

**Transfer:** Lead with a clear recommended route, then let comparison and reassurance answer increasing levels of scrutiny.

### Focused capability education with self-service conversion

1. **Promise** — Centered white text opening with category label and compact email signup.
2. **Quantified proof** — Yellow band with an editorial lead and four proof points.
3. **Capability chapters** — Alternating demonstrations followed by paired image-led explanations.
4. **Pricing** — Embedded four-column plan comparison with a raised recommendation.
5. **Education and objections** — Dark video feature, learning links and FAQs.
6. **Human reassurance** — Support photograph with a conversational editorial heading.
7. **Closing call** — Yellow centered call, warm disclosure bands and ochre directory.

**Transfer:** For a focused feature page, explain how the tool works before asking the reader to choose a plan.

### Audience-specific acquisition and sales-led conversion

1. **Promise** — Split white opening with a real workplace photograph and paired actions.
2. **Quantified proof** — Four large serif metrics on peppercorn.
3. **Product demonstration** — Three illustrated capability columns and a joined photographic story carousel.
4. **Capability chapters** — Logo reassurance, alternating demonstration rows and an inserted trial panel.
5. **Lead generation** — Dark resource-download form followed by compatibility logos and learning cards.
6. **Objection handling** — Ruled FAQs.
7. **Closing call** — Dark ROI-led statement, sales action, warm disclosures and ochre directory.

**Transfer:** Balance audience relevance, concrete mechanisms and a human proof story; offer a sales route where buying requires discussion.

### Technical product gateway and integration ecosystem

1. **Orientation** — Paper opening with light serif title and compact abstract illustration.
2. **Product routes** — Two dark documentation columns with mono labels and stacked links.
3. **Reliability proof** — Slate band with three oversized green metrics.
4. **Community support** — Paper illustrated program feature and dark community investment statement.
5. **Social proof** — Centered light serif testimonial on slate.
6. **Utility ending** — Slate technical footer with documentation groups, account action and small utility links.

**Transfer:** Retain the editorial serif personality while replacing marketing conversion density with clear documentation entry points.

## Writing

Confident, practical and encouraging, with a conversational wink rather than a comedic performance. Benefits are concrete and commercially legible; strong claims are paired with qualifiers and supporting detail.

**Do not copy:** Do not reuse the brand names, logos, proprietary illustrations, customer identities, testimonials, awards, market-leadership claims, discounts or performance figures. Supply the new product's own verified facts and assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we sparingly for reassurance and our platform when explaining a mechanism.
- **Rhythm:** Short benefit-first headings alternate with one or two clear explanatory sentences. Longer hero promises are allowed when they remain readable across two or three lines; action labels stay short and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the useful category, then remove a familiar obstacle. | 6–14 words | “Email & SMS marketing minus the learning curve” |
| Support line | State the business result and identify the tools that produce it. | 12–28 words | “Drive revenue with intuitive marketing analytics, automations, and AI tools.” |
| Capability heading | Verb-led, plain-language benefit with no technical throat-clearing. | 3–10 words | “Design with ease”<br>“Know what works and scale what’s selling well” |
| Human reassurance | Acknowledge the reader's concern, then answer it warmly. | 7–14 words | “Need to hire a helping hand? We got you.” |
| Primary action | Literal verb plus the next step; trial and sales actions are explicit. | 2–4 words | “Start Free Trial”<br>“Schedule a demo” |
| Closing statement | An affirmative outcome or brief invitation, not a new feature list. | 4–14 words | “Transform content into revenue” |

**Words and phrasing to use:** grow; create; connect; get started; with confidence; helping hand; save time; what works; your team

**Avoid:** revolutionary paradigm; unleash limitless potential; synergize; frictionless everything; developer jargon in marketing headlines

**Rules:**

- Lead with the reader's outcome, then explain the mechanism.
- Use contractions and occasional ordinary idioms without becoming cute in every sentence.
- Keep quantitative claims qualified with timeframe, population or measurement context nearby.
- Make link labels specific to the destination instead of repeating a page full of identical learn-more labels.
- In technical variants, name the interface or protocol clearly while keeping the explanatory sentences approachable.

## Do's and Don'ts

### Do

- Keep large marketing serif text at weight 400 and preserve its tight -1.2px or -0.5px tracking.
- Use 80px vertical padding for major narrative bands and a 1280px desktop content area.
- Repeat yellow arrow discs across ordinary forward links so utility carries the same personality as conversion.
- Keep capability cards broad, with 48px content breathing room and a distinct image column.
- Give photographic proof a 24px rounded outer frame and a separate results rail rather than mixing every fact over the image.
- Use a white and pale gray majority with deliberate peppercorn pauses and a substantial ochre ending.
- Use rectangular 4px-radius fields so forms remain visually distinct from 26px-radius action capsules.
- Scope green numerals, tracked mono labels and navy fields to the technical theme.

### Don't

- Do not make every heading a bold sans-serif; that erases the editorial hierarchy.
- Do not distribute yellow across every card background; most cards remain white against pale gray.
- Do not turn the default 44px action into a square-cornered or gradient-filled control.
- Do not give all panels the same 24px radius: price panels are square outside, offer boxes use 10px and utility tiles use 16px.
- Do not replace human workplace media with glossy floating 3D devices.
- Do not use tiny gray metrics as the main proof treatment; results need the 48px serif scale and a readable caption.
- Do not collapse the ochre footer into a small black legal bar on ordinary marketing pages.
- Do not style pricing feature matrices as widely separated floating cards; shared edges and aligned rows make comparison possible.

## Motion and responsive

### Motion

**Observed:**

- Primary and outlined capsules declare transform and box-shadow transitions of 0.3s cubic-bezier(0.5, 2.5, 0.7, 0.7).
- Arrow links declare color 0.15s ease-in-out and transform 0.3s; many shift 4px right on hover.
- Utility tiles declare box-shadow 0.2s transitions. Marquee rows declare opposing linear loops of 45s, 50s and 55s; other scrolling strips declare 60s linear infinite.

**Transfer:**

- Preserve the playful physical capsule lift rather than substituting a generic color fade.
- Use long, steady horizontal tracks for ecosystem abundance; keep neighboring rows directionally offset.

**Unknown:**

- Actual animation playback, autoplay behavior and reduced-motion handling are not established.

### Responsive

**Observed:**

- Declared layouts include breakpoints at 600px, 768px, 1024px and 1280px, among many component-specific widths.
- The large result recipe declares max(28px, min(5.5vw, 48px)).

**Transfer:**

- On narrow screens, retain the headline's editorial/italic relationship and legible contrast over the photographic subject.
- Stack joined story media above its results while preserving the distinction between quote and metrics; adapt broad capability cards without shrinking product art into an unreadable thumbnail.
- Keep comparison content aligned and navigable rather than compressing four plans into tiny text.

**Unknown:**

- Exact mobile compositions, navigation collapse behavior and responsive image choices are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
