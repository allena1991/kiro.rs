# Pangram Pangram — specimen meets spectacle

## Overview

An orderly typographic shopfront with the energy of an independent design magazine. Light neutral pages and compact grotesk text frame outsized lettering, tactile mockups, vivid photography and occasional theatrical product objects. Black panels, electric blue, tomato red and playful badges punctuate an otherwise restrained, information-rich layout. It suits creative tools and collections that can alternate expressive visual proof with unusually concrete buying information.

### Essentials

- A small voice introduces a big visual punch: the default landing opening pairs a 17.7px product label with a centered 60px/1, weight-600 grotesk headline, a compact 14px support line and an oversized physical-looking product object.
- The product becomes a word sculpture: stage monumental lettering as a material object against a blue-to-white backdrop, filling the lower half of the opening; when no product render exists, construct layered outlined initials inside a translucent display case.
- Soft rectangles organize hard typography: cards, media frames, buttons and the footer share a 20px radius; actions stay compact at 34px or 39px high rather than becoming oversized pills.
- Color lives in exhibits, not everywhere: white is the default canvas, #ededed holds repeated information, and blue dominates the opening before yielding to mostly neutral sections. #0067f7 marks the preferred offer; pale blue proof cards and one yellow support band provide discrete interruptions.
- Editorial abundance uses a disciplined frame: 1260px of content at a 1440px viewport, 90px side margins and 25.7px grid gaps; dense 14px details sit below short centered 36px headings.
- Buying information has personality: italic 63.6px serif prices, emoji-led plan names and a tilted recommendation sticker coexist with a precise comparison matrix. Preserve an expressive numeric or proof treatment even when the product has no subscription.
- The ending is a destination, not a thin legal strip: a large #ededed rounded directory carries a calligraphic identity line, several columns of 14px links, a white newsletter field and a separated bottom utility row.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage blue | `#015baf` | `--color-stage-blue` | background | Middle stop of the opening gradient, fading out toward white. |
| Midnight blue | `#002642` | `--color-deep-blue` | background | Top of the theatrical opening gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Offer blue | `#0067f7` | `--color-blue` | action, text, border, link | Recommended offer title, price, outline and action; inline campaign links. |
| Golden yellow | `#ffb700` | `--color-yellow` | surface, accent | Support callout and playful announcement stickers. |
| Tomato | `#ff2f00` | `--color-red` | action, surface, link, accent | Global active links, compact badges and catalog conversion actions; not the default campaign button. |
| Blue rule | `#9bc7fa` | `--color-blue-rule` | border | Separators within the sky-blue comparison column. |
| Sky blue | `#bfe0ff` | `--color-proof` | surface | Floating review cards and recommended comparison column. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, border | Primary text, solid buttons and inverted editorial panels. |
| Secondary gray | `#666666` | `--color-muted` | text, surface, border | Secondary descriptions, directory links and inactive commerce controls. |
| Mid gray | `#ababab` | `--color-divider` | border, text | Thin plan dividers and inactive commerce labels. |
| Table rule | `#d9d9d9` | `--color-rule` | border | Two-pixel comparison separators. |
| Gallery gray | `#ededed` | `--color-card` | surface, border | Repeated cards, comparison frame and footer. |
| Frosted gray | `#f2f2f2` | `--color-glass` | surface | Visible result of #ededed at 60% opacity over an off-white canvas in sticky navigation. |
| White | `#ffffff` | `--color-canvas` | background, text, border | Default landing canvas and reversed text or borders over blue. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| configurable product checkout panels | Commerce mint | `#5cffa8` | `--color-mint` | action, text, surface, border | Selected controls, monumental total and purchase action against black. |
| catalog and editorial pages | Off white | `#fafafa` | `--color-soft-canvas` | background, text | Catalog and editorial canvas; softer reversed text. |

## Typography

- **Neue Montreal** — All navigation, headlines, supporting text and controls. Direct neo-grotesk with a compact, high-x-height editorial presence. If unavailable, use **Inter**. 400–600 for text and headings; preserve normal tracking rather than tightening mechanically. Font stack: "Neue Montreal", "Inter", Arial, sans-serif.
- **PPLettra** — Expressive price numerals. High-contrast, sharply drawn italic serif, in deliberate contrast to the plain grotesk. If unavailable, use **Bodoni Moda**. 600 italic; match the width of short currency amounts. Font stack: "PPLettra", "Bodoni Moda", Georgia, serif.
- **neue-gstaad** (only for type-product demonstrations) — The product's own title and demonstrations, not the surrounding interface. Swiss grotesk displayed across compressed through expanded cuts. If unavailable, use **Roboto Flex**. 700 with width-axis variation for demonstrations. Font stack: "neue-gstaad", "Roboto Flex", Arial, sans-serif.
- **Pangaia** (only for company-story closing statements) — A solitary expressive closing sentence. Swashy italic serif; ornamental but still readable. If unavailable, use **Cormorant Garamond**. 600 italic; retain the contrast with surrounding sans-serif. Font stack: "Pangaia", "Cormorant Garamond", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| price | PPLettra | 600 italic | 63.6px | 1.3 | normal | Plan price; keep the billing interval much smaller and in the sans-serif. |
| display | Neue Montreal | 600 | 60px | 1 | normal | Centered opening promise; also major editorial chapter headings. |
| section-heading | Neue Montreal | 600 | 36px | 1.3 | normal | Default campaign section headings above compact support paragraphs. |
| quote-heading | Neue Montreal | 600 | 36px | 1 | normal | Review quotations and short support-band headings. |
| plan-heading | Neue Montreal | 600 | 22.4px | 1.3 | normal | Emoji-led plan titles. |
| product-label | Neue Montreal | 500 | 17.7px | 1.3 | normal | Small centered product name above the opening headline. |
| card-heading | Neue Montreal | 600 | 17.7px | 1.3 | normal | Card titles and emphatic plan summaries. |
| body | Neue Montreal | 400 | 14px | 1.3 | normal | Default supporting copy, lists, metadata and directory links. |
| section-label | Neue Montreal | 600 | 14px | 1.3 | normal | Small utilitarian section headings and footer group labels. |
| navigation | Neue Montreal | 530 | 14px | 1.3 | normal | Header navigation links. |
| badge | Neue Montreal | 400 | 12.4px | 1.167 | normal | Small status pills. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| configurable product checkout panels | checkout-total | Neue Montreal | 500 | 114.2px | 1.3 | normal | Right-aligned mint total, with a tiny subdued currency note beneath. |
| type-product detail openings | specimen-title | neue-gstaad | 700 | 80px | 1 | normal | Left-aligned product title before immersive specimen media. |
| company-story closing statements | closing-line | Pangaia | 600 italic | 36px | 1.3 | normal, features "swsh" | A single line surrounded by an exceptional amount of empty space. |
| company-story openings | editorial-lead | Neue Montreal | 400 | 22.4px | 1.2 | normal | Centered introduction below a two-line 60px headline. |

**Notes:**

- Normal tracking is the rule at every scale. Density comes from size, line height and weight rather than all-caps labels or exaggerated letterspacing.
- The everyday body is only 14px; do not inflate it to compete with the exhibit. The 60px promise is compact at line-height 1, while 36px section headings have line-height 1.3.
- Product lettering is content: demonstrations may use different widths, serifs or decorative faces while the interface remains Neue Montreal. Those display faces do not replace the text system.
- Use the stated desktop sizes as anchors; no continuous viewport scaling is prescribed for these text roles.

## Layout

**Density:** Airy between chapters, compact inside exhibits: dense lists and cards are separated by long neutral pauses.

### Spacing

| Value | Use |
| --- | --- |
| 7.7px | Heading-to-support spacing and compact control gaps. |
| 15.3px | Support-to-action spacing and paired control gaps. |
| 23px | Inline navigation spacing, quote vertical padding and price separation. |
| 25.7px | Grid gaps and standard card inset. |
| 30.6px | Opening text intervals and section-header top offsets. |
| 45.9px | Plan bottom inset and grid outside spacing. |
| 61.2px | Header-to-content separation, plan side insets and support-band padding. |
| 102.9px | Catalog chapter separation. |
| 122.4px | Default campaign chapter separation and footer lead-in. |
| 153px | Top inset of the blue opening. |

### Containers and grids

- **page-frame**: max width 1440px · side padding 90px. Centered desktop wrapper; yields 1260px usable width at a 1440px viewport.
- **promise-column**: max width 714px. Centered opening headline with a deliberate two-line break.
- **section-introduction**: max width 620px. Centered section heading and short body copy.
- **plans**: 3 columns · gap 25.7px. Equal-width pricing cards, approximately 403px each.
- **paired-editorial**: 2 columns · gap 25.7px. Equal 617px portrait media panels, or alternating text and media chapters.
- **directory**: 7 columns · gap 20px. Footer navigation: product directory occupies three columns; remaining columns group support, editorial, related properties and account links.
- **catalog** (only for catalog and related-product sections): 4 columns · gap 25.7px. 296px-wide specimen cards; incomplete final rows stay left-aligned.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards-and-actions | 20px |
|  | status-pills | 9999px (pill) |
| team sections | portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-review | `0px 0px 20px 0px rgba(0, 0, 0, 0.15)` | Pale blue review cards only; ordinary cards are flat. |
| recommendation-sticker | `0px 2px 8px 0px rgba(0, 0, 0, 0.15)` | Small tilted recommendation badge on a preferred offer. |

### Surfaces

#### Canvas · level 0

**Use:** Default landing background.

**CSS:** `background: #ffffff; color: #000000`

#### Blue stage · level 0

**Use:** Theatrical opening behind the product object.

**CSS:** `background-image: linear-gradient(#002642 0%, #015baf 41%, rgba(0, 0, 0, 0) 88%, rgba(0, 0, 0, 0) 100%); padding-top: 153px`

**Observed:** The gradient extends behind the object and resolves into the white page rather than ending in a hard horizontal seam.

**Transfer:** Keep the deep upper field, saturated middle and pale floor; match the object's lighting to the stage.

#### Gray exhibit · level 1

**Use:** Cards, comparison frames, related-product blocks and directory.

**CSS:** `background: #ededed; border-radius: 20px; box-shadow: none`

**Observed:** Flat tonal separation, not a collection of raised white panels.

**Transfer:** Use the same surface for both small items and whole information chapters.

#### Black chapter · level 1

**Use:** Concentrated editorial statement or a buying configurator.

**CSS:** `background: #000000; color: #fafafa; border-radius: 20px`

**Observed:** Inset to the content frame rather than full-bleed. Text is the visual focus.

**Transfer:** Use a contained high-contrast chapter to change pace.

#### Yellow support band · level 1

**Use:** Short customer-support or upgrade callout.

**CSS:** `background: #ffb700; color: #000000; border-radius: 20px; padding: 61.2px`

**Observed:** Centered headline, one sentence and a black action.

**Transfer:** Use for a genuine secondary route rather than a warning.

#### Frosted navigation · level 2

**Use:** Sticky navigation on scroll.

**CSS:** `background: rgba(237, 237, 237, 0.6); backdrop-filter: blur(20px); padding: 7.7px 0px`

**Observed:** Content remains faintly visible through the thin strip. Product pages replace global navigation with compact product-specific controls.

**Transfer:** Reserve translucency for navigation, not every card.

## Components

### Navigation strip

**Use:** Persistent wayfinding.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 23px`

**Text style:** `navigation` — Neue Montreal 530 · 14px/1.3

**Observed:** Identity at left, five short navigation links in the middle, search, bag and menu outlines at right. The opening uses white links over blue; the scrolled Frosted navigation uses black. Product context replaces the middle links with anchors and compact buying controls.

**States:** Declared: hover links turn tomato red; focus-visible uses a dark outline and a contrasting halo.

### Stage button

**Use:** Opening conversion link.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 7.7px 23px; border: 1px solid #ffffff; border-radius: 20px; color: #ffffff; height: 34px; background: transparent; line-height: normal`

**Text style:** `body` — Neue Montreal 400 · 14px/1.3

**Observed:** One centered outline action below support copy; the object beneath remains the dominant visual.

**States:** Declared: hover is not specified; focus-visible uses a contrasting halo and dark outline; active translates down 1px.

### Outline option button

**Use:** Conversion on nonpreferred offers.

**CSS:** `display: flex; justify-content: center; align-items: center; padding: 7.7px 30.6px; border: 1px solid #000000; border-radius: 20px; color: #000000; background: transparent; height: 39px; line-height: normal; font-weight: 530`

**Text style:** `card-heading` — Neue Montreal 600 · 17.7px/1.3

**Observed:** Spans the inner width at the bottom of a plan. The same construction is used for trial actions beside a red buying action on product-detail pages.

**States:** Declared: hover on the plan ancestor fills the action #0067f7 with white text; focus-visible adds a contrasting halo and dark outline; active translates down 1px.

### Preferred option button

**Use:** Conversion on the highlighted offer.

**CSS:** `display: flex; justify-content: center; align-items: center; padding: 7.7px 30.6px; border: 1px solid #0067f7; border-radius: 20px; background: #0067f7; color: #ffffff; height: 39px; line-height: normal; font-weight: 530`

**Text style:** `card-heading` — Neue Montreal 600 · 17.7px/1.3

**Observed:** Aligned to neighboring Outline option buttons; communicates preference through color, not additional size.

### Black editorial button

**Use:** Support and secondary editorial routes.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; padding: 7.7px 23px; border: 1px solid #000000; border-radius: 20px; background: #000000; color: #ffffff; height: 34px; line-height: normal`

**Text style:** `body` — Neue Montreal 400 · 14px/1.3

**Observed:** Sits under a short supporting sentence or inside an image-led promotional tile.

### Plan card

**Use:** Present a distinct offer with clear limits.

**CSS:** `display: flex; flex-direction: column; background: #ededed; border: 2px solid #ededed; border-radius: 20px; padding: 25.7px 61.2px 45.9px`

**Text style:** `plan-heading` — Neue Montreal 600 · 22.4px/1.3

**Observed:** Emoji and plan title, italic Price, small billing interval, bold usage summary, thin divider, bullet list, then Outline option button. Preferred plan changes its outline, title and price to offer blue and uses Preferred option button. A pale-blue tilted sticker sits near its edge. The shorter repeat removes the feature list and centers the title.

**Transfer:** Keep the plan differences concrete; express the preferred option without enlarging its card.

### Floating review card

**Use:** Expressive social proof.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; background: #bfe0ff; border-radius: 20px; padding: 23px 61.2px; box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.15)`

**Text style:** `quote-heading` — Neue Montreal 600 · 36px/1

**Observed:** Emoji reaction above a bold centered quotation, then a small bold author and regular role. Variable widths and staggered horizontal placement create a loose stack with mild overlap.

**Transfer:** Use authentic short reviews; preserve the buoyant arrangement instead of turning them into an equal-height grid.

### Comparison cell

**Use:** Make offer differences auditable.

**CSS:** `display: flex; flex-direction: column; justify-content: center; border-top: 2px solid #d9d9d9; padding: 30.6px 23px`

**Text style:** `card-heading` — Neue Montreal 600 · 17.7px/1.3

**Observed:** A wider left label column accompanies three equal offer columns. Labels align left and values center. The preferred offer is sky blue for its full height, with blue rules instead of neutral ones.

**Transfer:** Use a semantic table or equivalent accessible structure; preserve alignment of like-for-like limits.

### Status badge

**Use:** Brief release or content-state annotation.

**CSS:** `background: #ff2f00; color: #000000; border-radius: 9999px; padding: 4px 11.7px`

**Text style:** `badge` — Neue Montreal 400 · 12.4px/1.167

**Observed:** Tiny black text on tomato; pale blue denotes early access and yellow denotes an update. It sits above media or overlaps a card corner rather than becoming a section heading.

### Newsletter field

**Use:** Email signup within the directory.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 24px 45.9px 24px 24px; height: 63px`

**Text style:** `body` — Neue Montreal 400 · 14px/1.3

**Observed:** A wide white field under a bold micro-heading and one sentence; a plain right arrow is embedded at the far right, not a separate colored button.

### Directory footer

**Use:** A substantial navigational ending.

**CSS:** `background: #ededed; border-radius: 20px; padding: 25.7px; overflow: hidden`

**Text style:** `body` — Neue Montreal 400 · 14px/1.3

**Observed:** An ornate black identity line spans about half the content width above the Directory grid. Black bold group labels contrast with gray link lists. Newsletter field occupies the lower right; payment marks and copyright sit at the panel's bottom. Outside the panel, back-to-top, a centered identity line and creator credit form a final row.

**Transfer:** Use the new identity in a calligraphic or expressive typographic treatment and organize the real information architecture; retain the newsletter and separated final utility row.

### Specimen card

**Only for:** catalog and related-product sections

**Use:** Browse variants or complementary products.

**CSS:** `display: flex; flex-direction: column; background: #ededed; border-radius: 20px; padding: 25.7px; overflow: hidden`

**Text style:** `card-heading` — Neue Montreal 600 · 17.7px/1.3

**Observed:** Compact title and gray metadata at the upper left, tiny format glyph at upper right, then an enormous black specimen anchored in the lower portion. A status badge may overlap the upper edge. At desktop the card is 296px by 407px.

**States:** Declared: hover background becomes black and text white; focus-visible adds a contrasting halo and dark outline.

**Transfer:** Replace letter specimens with an equally bold silhouette, glyph or single visual demonstration of the new product.

## Imagery and graphics

### Luminous product sculpture

**Use:** Signature object in the default opening.

**Observed:** A large front-facing rectangular metallic case contains transparent cyan-lit letterforms, with visible fasteners, layered edge highlights and a cool floor reflection. It fills most of the lower first screen, continues below the fold and contrasts with the clean white headline. Small yellow stickers add an irreverent human layer.

**Transfer:** Turn the new product's initials, emblem or recognizable form into a single luminous object. Minimum acceptable version is crisp layered vector linework in a dimensional case, not a small logo floating in empty space.

**Build:** Create a wide rounded case with dark-blue fill, nested metallic-looking edge strokes and small corner screw circles. Set original initials as large transparent SVG outlines; repeat the outlines with small insets and offsets to suggest internal channels. Layer white thin highlights above cyan strokes and a blurred cyan duplicate behind. Add a broad low-opacity cyan ellipse under the case as reflected light. Center the object across roughly three quarters of the viewport; clip its lower portion naturally at the first fold. Add one tilted yellow rounded sticker near an upper corner. Match the cool glow; exact light stops are not essential.

### Tactile applications

**Use:** Visual proof galleries and supporting product chapters.

**Observed:** Physical books, paper, signage, packaging, screens and posters show the product in use. Scenes mix natural light, colored printed surfaces, subtle grain and realistic shadows. Portrait pairs occupy most of a screen with very little explanatory copy; a denser mockup gallery uses eight small columns.

**Transfer:** Show credible applications of the new product in different contexts. Pair a photographic mockup with an art-directed flat graphic so the gallery does not become one uniform set of screenshots.

### Immersive photographic specimen

**Only for:** catalog hero banners and individual creative-product stories

**Use:** Large product-as-editorial-image stage.

**Observed:** Saturated alpine greens and snowy peaks, or close-up orange slices in drinks, fill wide rounded banners. A dark scrim allows huge white product lettering, a short centered descriptor and paired actions. Detail pages also let the landscape bleed across the full width before returning to inset panels.

**Transfer:** Choose a real environment or material metaphor tied to the product's character. Preserve rich photographic texture and overlaid lettering; use original still-life photography when landscape is irrelevant.

### Letterform poster system

**Only for:** creative-product demonstration galleries

**Use:** Distinctive graphic specimen mixed with real-world mockups.

**Observed:** Giant words change width and weight within the same line; fine rules divide informational rows, small captions sit underneath, and solid colored paper backgrounds carry visible print-like texture.

**Transfer:** Make original typographic posters using the product's own vocabulary and properties.

**Build:** Use SVG text spans with contrasting widths and weights, arranged in four horizontal bands. Place hairline rules between bands and two small caption columns below each large word. Back with a strong flat paper color and a subtle low-opacity monochrome noise texture. Keep the type close to the edges while retaining a consistent inner margin.

### Editorial culture graphics

**Only for:** company-story pages

**Use:** Explain craft and introduce people.

**Observed:** An opening Venn diagram uses two thin black overlapping circles labelled at the outer sides and intersection. Alternating chapters show outline-letter construction, specimen cards and type drawings on white. Team portraits are monochrome circles, 189px across, in a six-column grid with centered 14px names and roles.

**Transfer:** Use simple line diagrams to express the new company's core tension, then show actual craft and people rather than abstract stock illustrations.

**Build:** Draw two equal unfilled SVG circles with a 1px black stroke and a broad central overlap. Add one short label at each outer side and a bold label in the intersection. Scale the diagram as a single centered artwork below the introduction.

### Icons

**Observed:** Utility icons are thin black or white outlines: search about 19px square with a 1px stroke, bag and menu around 31px with round line ends. Arrow characters are plain text. Emoji supply personality in offers and reviews rather than a large custom icon family.

**Transfer:** Use sparse outline search, bag, menu and downward arrows matching the local text color. Use emoji only where an offer or reaction benefits from the informal tone.

## Section recipes

How recurring sections are built.

### First screen: Blue object opening

**Observed:** A full-width Blue stage starts behind a slim white-text Navigation strip. Below the navigation, the content is centered: Product label begins after 153px of top inset, then a two-line Display promise confined to about 714px, compact Body support with a bold starting-price line, and one Stage button. The main object begins below that text cluster and spans roughly three quarters of the viewport; its cyan-lit interior and yellow sticker are already visible in the first 900px, but its base and explanatory inventory continue below. Layers run from the blue gradient through floor glow and large case to luminous lettering and sticker, while the text stays clean and separate above.

**Transfer:** Stage an original emblem or initials as Luminous product sculpture when there is no renderable product. Keep the object substantial enough to compete with the headline. Catalog openings instead use an Immersive photographic specimen with a giant overlaid product name; detail openings use a left-aligned 80px product title and actions above the image. Company-story openings use a centered 60px heading, editorial lead and line diagram.

**Avoid:** Do not shrink the object into a small illustration beside the headline, add a row of feature cards above the fold, or replace the luminous material scene with a generic blue blob.

**Text style:** `display` — Neue Montreal 600 · 60px/1

### Centered chapter introduction

**Observed:** A 620px centered text column contains Section heading and a Body paragraph separated by 7.7px. The content below is usually separated by 61.2px; major campaign chapters have about 122.4px of outer separation.

**Transfer:** Introduce one visual or buying question at a time. Keep supporting copy short enough that the exhibit remains dominant.

**Text style:** `section-heading` — Neue Montreal 600 · 36px/1.3

### Offer ladder and matrix

**Observed:** Three Plan cards share equal width and vertical alignment. Preferred offer has blue accents and a tilted recommendation sticker. A later Gray exhibit matrix uses a 1.5fr label column plus three 1fr offer columns, 2px rules, and a sky-blue preferred column. A closing offer repeat uses shorter centered Plan cards.

**Transfer:** Use for genuine tiers or selectable bundles. Repeat the decision once the product has been demonstrated, reducing detail on the repeat.

### Editorial gallery chapter

**Observed:** Paired editorial media uses two 617px-wide portrait frames with 25.7px between them. An asymmetric variant places a wide central poster between smaller portrait panels. Dense proof libraries use eight narrow columns instead. Text steps back and lets physical applications carry the chapter.

**Transfer:** Alternate overview, close-up, poster and physical application; use the density appropriate to the number of real examples.

### Loose review constellation

**Observed:** Centered chapter introduction leads into staggered Floating review cards, variable in width and occasionally overlapping. The heading is orderly while the reactions below are exuberant.

**Transfer:** Keep the grid loose but quotations readable; use verifiable reviews and original reaction choices.

### Support route and quiet terms

**Observed:** Yellow support band presents a short 36px/1 heading, one Body line and Black editorial button. Below, a narrow centered terms block receives unusually generous vertical padding before Directory footer.

**Transfer:** Give existing customers or edge cases a distinct secondary route. Keep legal qualifications visually subordinate but legible.

### Directory ending

**Observed:** Directory footer begins about 122.4px after the preceding chapter. The rounded gray panel is approximately 1260px wide and 988px tall, with a script-like identity at the top, dense navigational columns and Newsletter field below. Payment marks and copyright close the panel; a separate utility row closes the page.

**Transfer:** Scale the link inventory to real content while retaining the expressive identity, useful signup and clearly separated last row.

### Inverted information and purchase

**Only for:** individual product detail pages

**Observed:** A Black chapter first pairs a 60px short statement on the left with several 17.7px paragraphs on the right. Four metadata cards follow, one tomato and three gray, with tiny labels and 36px key information. The buying chapter uses another Black chapter: centered 60px heading, two-column form, selected mint controls at left, a 114.2px mint total at right and a 75px-high purchase action. Two gray assistance cards sit below it.

**Transfer:** Convert complicated choices into a deliberate contrast chapter. Preserve the oversized total and show selected states clearly rather than making all controls equally bright.

### Company-story closing pause

**Only for:** company-story pages

**Observed:** A single swashy italic 36px line sits in a very tall off-white field, with 630px of space before and after the line's container. Two short supporting paragraphs and a tomato action follow before the shared directory.

**Transfer:** Use an original short credo as a typographic artwork. Preserve the exceptional pause only in a narrative brand story, not between routine product features.

**Text style:** `closing-line` — Pangaia 600 italic · 36px/1.3

## Page flow

**Storyline:** Expressive promise → tangible product proof → understandable choices → deeper visual evidence → human validation → renewed decision → practical help → navigational ending.

### Collection-led discovery

1. **Promise** — Stacked full-width inset photographic product banners with monumental names and paired actions.
2. **Product discovery** — Four-column specimen grid with metadata and small status badges.
3. **Applied proof** — Wide image carousel with adjacent previews and tiny pagination dots.
4. **Positioning and trust** — Black statement panel followed by a horizontal logo strip.
5. **Adjacent discovery** — Immersive promotional banner, paired image promotions and editorial carousel.
6. **Navigational ending** — Full directory with expressive identity, newsletter and utility row.

**Transfer:** Use when the reader is choosing among several products; let visual families establish personality before detailed comparison.

### Flagship campaign and offer conversion

1. **Promise** — Blue object opening pairs a witty two-line promise with a luminous physical-looking product sculpture.
2. **Choices** — Three offers identify audience and usage limits.
3. **Detailed comparison** — Large matrix makes inclusions and differences explicit.
4. **Product demonstration** — Dense visual library and real-world application gallery demonstrate breadth and context.
5. **Human validation** — Loose constellation of pale-blue review cards.
6. **Renewed decision** — Shorter offer cards restate the choice.
7. **Objection handling** — Yellow support route followed by narrow terms.
8. **Navigational ending** — Shared directory and final utility row.

**Transfer:** Default for a new marketing landing page: combine an unforgettable object with unusually clear commercial information.

### Individual product exploration and configurable buying

1. **Identification** — Width-variant navigation, left-aligned product name, trial and buying actions.
2. **Immersive demonstration** — Full-width photographic specimen, variant cards and paired application posters.
3. **Interactive proof** — Black variable-type demonstration with three light control pills.
4. **Depth and specifications** — More applied imagery, black editorial description and four metadata cards.
5. **Purchase decision** — Black configurator with mint controls, giant total and large purchase action.
6. **Cross-discovery** — Related-product cards and an applied-work carousel.
7. **Navigational ending** — Shared directory and final utility row.

**Transfer:** Use for a product whose properties need hands-on exploration; keep the product's own visual language distinct from the shared interface.

### Company story and credibility

1. **Introduction** — Centered welcome, substantial lead paragraph and large line diagram.
2. **Capability chapters** — Alternating text-and-media rows illustrate craft, range and bespoke capability.
3. **Human credibility** — Monochrome circular portrait grid.
4. **External validation** — Five-column logo matrix and short centered action.
5. **Broader discovery** — Paired image-led promotions introduce adjacent offerings.
6. **Closing statement** — Isolated italic credo in an exceptionally tall neutral field, followed by supporting copy and action.
7. **Navigational ending** — Shared directory and final utility row.

**Transfer:** Use for a narrative page: alternate factual craft evidence with people, then end with a memorable typographic pause.

## Writing

Design-literate and confident, with practical specificity and an occasional wink. Product character can be poetic; offers are frank about formats, quantities and limits.

**Do not copy:** Do not reuse brand names, logos, proprietary artwork, type specimen phrases, customer identities, testimonials, commercial claims, prices or numerical inventory. Create original equivalents supported by the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you or your for the reader. Speak directly to creative ambition without making the reader sound inexperienced.
- **Rhythm:** Short, punchy headlines and sentence fragments alternate with compact explanatory paragraphs. Triplets and emphatic full stops are common; emoji, ellipses and exclamation marks belong to playful campaign moments, not every sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar statement interrupted by a playful turn. | 6–12 words | “The perfect font starter pack doesn’t exi...” |
| Product character | Three concise qualities separated by full stops. | 3–6 words | “Calm. Efficient. Swiss.” |
| Supporting inventory | Concrete inclusions delivered as short fragments. | 8–20 words | “Commercial use. All key fonts. All formats. Pro Mockups.” |
| Chapter heading | A direct benefit with a physical or conversational metaphor. | 4–8 words | “A lot more to unpack!”<br>“Impress your clients with context” |
| Action | Plain verb plus a specific object or decision. | 2–5 words | “Choose your pack”<br>“Get this option”<br>“Try for Free” |
| Closing credo | One personal, expressive sentence about the work's value. | 5–9 words | “Typefaces that tell your Story.” |

**Words and phrasing to use:** crafted; free to try; explore; your next project; all formats; key styles; design game; tailored; context

**Avoid:** revolutionary ecosystem; synergy; unparalleled innovation; enterprise-grade transformation; limited-time urgency without cause

**Rules:**

- Connect expressive character to a practical use case in the next sentence.
- Make quantities and usage boundaries easy to compare instead of burying them in inspirational copy.
- Let a playful headline earn its space through concrete proof below.
- Use brief plain-language help prompts for unusual buying situations.

## Do's and Don'ts

### Do

- Keep the opening promise at 60px/1 and weight 600, with normal tracking.
- Frame most desktop chapters within 1260px of usable width.
- Reuse the 20px corner across information cards, image panels and compact actions.
- Retain a 14px/1.3 default body so the imagery and prices carry the scale contrast.
- Use 25.7px grid gaps and roughly 122.4px pauses between campaign chapters.
- Make the preferred offer blue in title, price, edge and button while preserving equal card dimensions.
- Give quotations the pale-blue surface and restrained 15% black shadow rather than elevating every card.
- Preserve the full newsletter-and-directory ending, including the final outside utility row.

### Don't

- Do not introduce uppercase, widely tracked eyebrows into this sentence-case grotesk hierarchy.
- Do not round the entire system to an 8px spacing grid; retain the characteristic fractional spacing values.
- Do not turn every action into a 56px-high capsule; standard actions are 34px or 39px high.
- Do not place white drop-shadow cards on the gray page as the default; repeated exhibits are flat #ededed.
- Do not spread offer blue, tomato and mint equally across a page; mint belongs to the checkout variant.
- Do not make all specimen cards image thumbnails with small captions; their demonstration should dominate the lower card area.
- Do not force an incomplete catalog row to stretch its final cards across the frame.
- Do not apply ornamental serif lettering to navigation or paragraphs; reserve it for prices, identity artwork and the scoped closing credo.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color .2s ease, color .2s ease, border-color .2s ease and transform .2s ease-out; active actions translateY(1px).
- Specimen cards declare background-color .5s cubic-bezier(.22, 1, .36, 1) and color with the same duration and easing.
- Sticky navigation declares transform and opacity .1s cubic-bezier(.32, 0, .67, 0).
- Floating reviews use view-linked animations with linear timing and auto duration; a sliding element declares 30s linear infinite.

**Transfer:**

- Keep specimen hover as a full black/white inversion, not a scale-up effect.
- Let the loose review arrangement move with the reading journey without turning it into an auto-advancing equal-card carousel.
- Preserve the compact product-context header when scrolling into buying sections.

**Unknown:**

- The complete paths of scroll-linked object and review animations, their reduced-motion behavior and the exact trigger thresholds are not specified.

### Responsive

**Observed:**

- Desktop compositions use a 1440px wrapper, centered narrow text columns and repeated grids. A 750px breakpoint is declared for company-story styling.

**Transfer:**

- On narrower screens, preserve the object below the opening text and reduce headline width before compromising its two-part visual hierarchy.
- Collapse portrait pairs and offer columns into a readable stack; keep preferred-offer color and the oversized serif price.
- Turn the comparison into a horizontally navigable table with its row labels retained, rather than shrinking all four columns to unreadable text.
- Reduce directory columns and keep newsletter signup distinct from the link inventory.

**Unknown:**

- Exact mobile type sizes, gutter values, grid breakpoints, menu behavior and comparison overflow behavior are unspecified; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
