# Kinfolk — collected objects, printed voices

## Overview

A light, magazine-like visual language where modest serif headlines and tiny sans-serif annotations give photography room to carry the emotion. White, black and a pale grey-green form the architecture; rich color belongs to portraits, still lifes and tactile product images. It suits design-led products, cultural services and curated collections with a spacious, image-heavy pace rather than a dense sales interface.

### Essentials

- The opening treats the product as a collected object, not an interface demo: a centered two-line 50px/52px regular serif heading, a small isolated portrait-format object and restrained Buy / Read links on a predominantly white first screen.
- Headlines speak in paired voices: uppercase titles followed immediately by sentence-case editorial descriptions, using the same regular serif at 60px/60px or 50px/52px, never bold emphasis.
- The page is a printed spread with working annotations: 32px/38px serif section names meet 2px black rules, while card titles use 15px/20px uppercase sans and category notes use 13px/17px sans.
- Color is carried by pictures rather than interface chrome: white dominates the canvas, #dbded5 backs a preview band, and black anchors the conversion ending. Include a full-bleed photographic statement; when no campaign photograph exists, use a carefully lit physical still life of the product or its materials.
- Actions are almost typographic punctuation: plain text links on white and 1px white outlined rectangles with 2px corners and 4px 8px padding on black, rather than oversized filled buttons.
- Image scale is deliberately unequal: combine 296px-wide portrait cards, 212px-wide portrait accents and full-width photography, with 20px gutters and 170px chapter breathing room.
- The closing device is an inverted editorial spread: a black offer panel with a centered 32px/38px headline pair, narrow portrait media, plan details to the left and small actions at the lower edges, followed by a 2px white-rule footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Grey-green stock | `#dbded5` | `--color-preview` | surface, background | Full-width preview band and media backing; keep actual imagery visible above the backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Print black | `#000000` | `--color-ink` | text, background, border, action | Default text and rules; inverted offer panel and footer background. |
| White paper | `#ffffff` | `--color-canvas` | background, text, border | Main canvas, reversed text and outlined actions on dark surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalog and archive filters | Selected category grey | `#a3a3a3` | `--color-selected` | text, action | Current category in an otherwise black comma-separated filter list. |

## Typography

- **Kinfolk-Serif-Deck** — Display headlines, section headings and product titles. Literary serif with pronounced stroke contrast, compact uppercase forms and an unforced regular weight. If unavailable, use **Libre Caslon Display**. Use regular weight; tune line breaks to the relatively compact headline measure. Font stack: "Kinfolk-Serif-Deck", "Libre Caslon Display", serif.
- **Kinfolk-Sans** — Annotations, editorial summaries, prices, navigation and small actions. Plain regular grotesk with open counters and lightly spaced small text. If unavailable, use **Arimo**. Use regular weight and preserve the positive tracking on small text. Font stack: "Kinfolk-Sans", "Arimo", Arial, sans-serif.
- **Kinfolk-Serif-Text** — Small reversed offer descriptions and plan names. Readable text serif with more durable small-size detail than the deck face. If unavailable, use **Libre Caslon Text**. Font stack: "Kinfolk-Serif-Text", "Libre Caslon Text", Georgia, serif.
- **Kinfolk-Serif-Display** (only for immersive editorial features) — Oversized type embedded in immersive photographic features. High-contrast, sharply drawn display serif. If unavailable, use **Bodoni Moda**. Font stack: "Kinfolk-Serif-Display", "Bodoni Moda", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial-display | Kinfolk-Serif-Deck | 400 | 60px | 1 | -0.005em | fixed | Large feature statements; pair an uppercase title with a sentence-case description at identical scale. |
| hero | Kinfolk-Serif-Deck | 400 | 50px | 52px | -0.01em, uppercase | fixed | Two-line product edition or campaign title in the opening; also uppercase half of split feature headlines. |
| section-heading | Kinfolk-Serif-Deck | 400 | 32px | 38px | -0.005em | fixed | Section names, newsletter invitation, category list and sentence-case half of centered headline pairs. |
| section-label | Kinfolk-Serif-Deck | 400 | 32px | 38px | -0.005em, uppercase | fixed | Uppercase first line of centered preview and conversion heading pairs. |
| product-title | Kinfolk-Serif-Deck | 400 | 25px | 29px | -0.005em, uppercase | fixed | Centered two-line titles beneath isolated products. |
| price | Kinfolk-Sans | 400 | 20px | 1.5 | 0.02em | fixed | Unembellished centered currency amounts. |
| body | Kinfolk-Sans | 400 | 15px | 20px | 0.01em | fixed | Short editorial descriptions, small actions and information text. |
| card-title | Kinfolk-Sans | 400 | 15px | 20px | 0.01em, uppercase | fixed | Small story titles and institutional row labels. |
| offer-copy | Kinfolk-Serif-Text | 400 | 15px | 20px | normal | fixed | White plan names and concise descriptions in the black conversion spread. |
| metadata | Kinfolk-Sans | 400 | 13px | 17px | 0.03em | size calc(11.6px + 0.06897vw) | Category and issue references immediately below editorial media. |
| product-label | Kinfolk-Sans | 400 | 13px | 17px | 0.06em, uppercase | size calc(11.6px + 0.06897vw) | Product category and small New marker. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| immersive editorial features | image-caption | Kinfolk-Serif-Deck | 400 | 25px | 29px | -0.005em | fixed | Short white introductory sentence over a large photograph. |
| information and support sections | accordion-label | Kinfolk-Sans | 400 | 15px | 20px | normal, uppercase | fixed | FAQ and careers accordion triggers. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular weight is the hierarchy's constant. Scale, case, placement and serif-versus-sans contrast do the work instead of heavier cuts.
- Headline tracking is slightly negative; small sans labels have positive tracking. Uppercase and sentence-case headline pairs have no change of weight.
- The immersive image feature uses a visually oversized white display line near the lower edge. Treat it as fitted editorial artwork rather than using the small caption size for that line.

## Layout

**Density:** Airy at chapter scale, compact within annotations: expansive image-to-section intervals contrast with tightly stacked title and description lines.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Gap from small card title to description. |
| 5px | Gap from editorial media to metadata. |
| 15px | Metadata-to-title gap. |
| 20px | Column gutters and heading-rule padding. |
| 25px | Product label-to-title and title-to-price spacing. |
| 60px | Information opening paragraph separation and product card bottom padding. |
| 75px | Archive grid row gaps. |
| 80px | Rule-to-carousel media gap. |
| 110px | Preview heading-to-grid gap and category-list lower padding. |
| 120px | Preview band lower padding. |
| 170px | Default major chapter separation. |
| 315px | Top whitespace above centered catalog and archive filters. |

### Containers and grids

- **editorial-container**: max width 1372px · side padding 34px. Desktop content spans nearly the whole 1440px window; full-bleed media escapes this margin.
- **underlying-grid**: 24 columns · gap 20px. Shared alignment scaffold for asymmetrical features, section bars, editorial lists and footer.
- **story-grid**: 4 columns · gap 20px. Archive stories use four 328px-wide image-led columns with 75px row gaps.
- **preview-grid**: max width 1024px · 3 columns · gap 20px. Centered three-card selection inside the grey-green band.
- **offer-description**: max width 500px. Keep the left offer description short and separate from the narrow centered image.
- **catalog-grid** (only for product catalogs): 3 columns · gap 20px. Three 444px-wide cells at desktop. Product artwork is centered within each cell rather than stretched to its edges.

## Corner radius

| Element | Radius |
| --- | --- |
| outlined-actions | 2px |
| media-and-panels | 0px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default page field and unboxed story cards.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No ornamental texture, raised panels or shadows.

**Transfer:** Let photography and rules articulate the white field.

#### Preview stock · level 0

**Use:** A bounded editorial preview chapter.

**CSS:** `background: #dbded5; padding-top: 110px; padding-bottom: 120px`

**Observed:** Flat grey-green behind a centered headline pair and three editorial cards.

**Transfer:** Use for a curated taste of the product, not every repeated content block.

#### Inverted spread · level 0

**Use:** Closing offer and utility footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Full-width black with fine white text and no card containers around individual plans.

**Transfer:** Reserve this strongest inversion for a decisive offer or membership close.

## Components

### Minimal navigation

**Use:** A lightweight persistent header.

**CSS:** `position: fixed; height: 54px; display: grid; column-gap: 20px; z-index: 40`

**Observed:** A spaced serif wordmark sits at the upper left and a two-line menu mark at the upper right; the menu remains visible while the wordmark can withdraw on scroll. The surrounding field stays visually unobtrusive.

**Transfer:** Use the new product's wordmark and the same two-line menu vocabulary; do not introduce a full desktop link bar.

### Outline action

**Use:** Small conversion and account actions on the black spread.

**CSS:** `color: #ffffff; border: 1px solid #ffffff; border-radius: 2px; padding: 4px 8px; transition: opacity 0.5s cubic-bezier(0.25, 1, 0.5, 1)`

**Text style:** `body` — Kinfolk-Sans 400 · 15px/20px · tracking 0.01em

**Observed:** Content-sized rectangle, paired with plain helper text for account access; never the visual center of the section.

**States:** Declared: hover opacity 0.4; focus-visible unknown; active unknown.

### Ruled section bar

**Use:** Introduce editorial carousels and product selections.

**CSS:** `display: flex; justify-content: space-between; align-items: center; border-bottom: 2px solid #000000; padding-bottom: 20px; margin-bottom: 80px`

**Text style:** `section-heading` — Kinfolk-Serif-Deck 400 · 32px/38px · tracking -0.005em

**Observed:** Serif heading at left; a small sans View All link rests at the far right near the rule.

**Transfer:** Name the selection rather than making a promotional claim.

### Story card

**Use:** Repeated editorial items in grids and horizontal selections.

**CSS:** `display: flex; position: relative; flex-direction: column`

**Text style:** `card-title` — Kinfolk-Sans 400 · 15px/20px · tracking 0.01em · uppercase

**Observed:** Portrait photograph first, metadata after 5px, uppercase title after 15px and a sentence-case summary after 2px. No card border or internal padding. Carousel images are about 296 × 397px; archive images are 328 × 441px.

**Transfer:** Make the image do the persuasive work, with a useful category and one concrete descriptive sentence.

### Product card

**Use:** Product selection within a landing page or catalog.

**CSS:** `display: flex; position: relative; flex-direction: column; padding-bottom: 60px`

**Text style:** `product-title` — Kinfolk-Serif-Deck 400 · 25px/29px · tracking -0.005em · uppercase

**Observed:** An isolated cover or object sits above a centered category, two-line serif title and sans price. The media includes ample white breathing room; the visible cover is smaller than its media box. A New marker may be underlined next to the category.

**Transfer:** For software, show one designed artifact or tangible output as the collectible object rather than a busy dashboard.

### Comma category list

**Use:** A typographic browsing index.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: center; align-items: center; border-bottom: 2px solid #000000; padding-bottom: 110px`

**Text style:** `section-heading` — Kinfolk-Serif-Deck 400 · 32px/38px · tracking -0.005em

**Observed:** Categories run as a centered comma-separated sentence rather than chips. The current filter is grey in catalog and archive contexts; the default links are black.

**Transfer:** Use a short vocabulary that can wrap naturally.

### Newsletter rule

**Use:** A low-pressure subscription invitation between editorial chapters.

**CSS:** `display: grid; column-gap: 20px; justify-content: space-between; padding-bottom: 20px`

**Text style:** `section-heading` — Kinfolk-Serif-Deck 400 · 32px/38px · tracking -0.005em

**Observed:** Invitation occupies roughly two thirds of the line, with a fine bottom rule; the remaining third contains an email field and a small Submit action on their own baseline rule.

**Transfer:** Keep it as one horizontal editorial line, not a boxed signup form.

### Offer spread

**Use:** The signature closing conversion block.

**CSS:** `background: #000000; position: relative; color: #ffffff`

**Text style:** `section-heading` — Kinfolk-Serif-Deck 400 · 32px/38px · tracking -0.005em

**Observed:** Centered uppercase label and sentence-case heading above narrow portrait media. Plan names, prices and a short serif description occupy the left; a small outline action is anchored low left, with account helper text and Login low right. The desktop block is 625px high; catalog and archive versions add 60px above for 685px total.

**Transfer:** Retain the black field, centered physical-use image and lateral small print even when the offer is a single product rather than a subscription.

### Utility footer

**Use:** Final navigation and credits beneath the offer.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; border-top: 2px solid #ffffff; padding-top: 15px; padding-bottom: 35px`

**Text style:** `card-title` — Kinfolk-Sans 400 · 15px/20px · tracking 0.01em · uppercase

**Observed:** Copyright at left, two small horizontal groups of commerce and social links in the middle, credit at right. The line stays inside the shared content margin; the black surface continues from the offer.

**Transfer:** Keep this a narrow 72px utility strip rather than a multi-column sitemap.

### Accordion row

**Only for:** information and support sections

**Use:** Compact questions, service topics and opportunities.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding-bottom: 14px`

**Text style:** `accordion-label` — Kinfolk-Sans 400 · 15px/20px · uppercase

**Observed:** Uppercase trigger at left and a 16px plus at the right; repeated triggers have black baseline rules. The accordion occupies the right portion of a much wider ruled information row.

**Transfer:** Keep expanded copy in the same plain sans body treatment; preserve the large empty left-hand label area.

## Imagery and graphics

### Collected object

**Use:** The opening and product cards.

**Observed:** A flat front-facing magazine cover is centered on white without a visible shadow or container. In the opening its visible area is about 314 × 406px, much smaller than the surrounding canvas; the red cover and green clothing supply the color.

**Transfer:** Photograph a product, its packaging or a single representative output straight-on. If no physical equivalent exists, design one clean portrait-format artifact and give it the same white space.

### Editorial photography

**Use:** Card grids, small portraits and asymmetrical feature spreads.

**Observed:** People in lived-in interiors, tactile objects, architectural details and staged still lifes. Natural directional light, warm wood, stone, cloth and paper recur; occasional black-and-white portraits sit alongside strong but controlled color. Portrait framing is the norm, with square corners and no graphic frame.

**Transfer:** Commission scenes of the people, tools and environments around the product. Preserve material detail, shadow and human presence rather than resorting to generic business imagery.

### Immersive photographic statement

**Use:** A signature large-scale pause among the smaller editorial items.

**Observed:** A full-bleed image of painted cubes and spheres against textured blue fills a tall feature. A small white serif sentence sits near the top, while a very large uppercase white serif line spans almost the entire lower width. The objects show brush texture, scuffs and directional shadows rather than polished synthetic gloss.

**Transfer:** Stage an equivalent physical still life from the new product's materials or tools, or use a close photographic study of its making. Keep the oversized lower headline and small upper caption even with simpler media.

**Build:** Use a full-width photographic image layer with object-fit: cover. Overlay a white regular display-serif line across the lower edge inside 34px side margins; fit its length to the available width, aiming for roughly 90px visible capital height at a 1440px window. Place a 25px/29px white deck-serif caption near the upper left. Use real lit objects and a matte textured backdrop rather than CSS floating shapes.

### Photographic destination tiles

**Use:** A three-way navigation or action choice before the closing offer.

**Observed:** Three 444 × 571px images with 20px gaps: a cover on a red textured surface, a book in sunlight beside a moving person, and shelves of printed material. White 32px serif action names and small See More links are centered near the lower edge over darkened photographic tones.

**Transfer:** Show three distinct ways into the product through physical use, an object and an environment. Keep labels short; use tonal darkening only where needed for white text.

### Hands-on offer media

**Use:** Centered inside the black closing spread.

**Observed:** A narrow portrait video shows hands turning through printed material on a warm wooden table with domestic objects nearby; the vivid human-scale vignette contrasts with the empty black field.

**Transfer:** Show the product being handled or a person using its outcome. A single still of hands at work is the minimum equivalent if video is unavailable.

### Icons

**Observed:** Very little iconography: a two-line menu mark, 16px black plus signs in information accordions and a small 17 × 10px downward chevron with 2px butt-ended stroke for issue filtering.

**Transfer:** Use only functional line marks in black or reversed white. Keep them at annotation scale; do not add decorative feature icons.

## Section recipes

How recurring sections are built.

### First screen: Collected object opening

**Observed:** A white stage fills almost the first 900px. Minimal navigation occupies the upper edge. A centered two-line uppercase serif title at 50px/52px sits high on the page; the front-facing portrait product is centered well below it, separated by about 90px of white. The visible product is about 314 × 406px, leaving most of the width untouched. Small Buy and Read text actions, separated by a vertical stroke, sit below the object near the bottom of the white stage. By 850px the next full-bleed image begins to enter. There is no supporting sales paragraph or large button above the fold. Layers are white field, isolated product image and restrained black typography.

**Transfer:** For a new landing page, choose one hero object or portrait-format output and a concise two-line product designation. Give it a complete white stage before revealing a larger editorial scene. Catalogs instead open with centered category navigation over a rule; archives add an issue selector above it. Institutional pages open with two broad 32px serif paragraphs.

**Avoid:** Do not replace the centered object with a split-screen dashboard, a wall of badges or a left-aligned slogan with an oversized pill CTA.

**Text style:** `hero` — Kinfolk-Serif-Deck 400 · 50px/52px · tracking -0.01em · uppercase

### Ruled selection

**Observed:** Ruled section bar followed by an image-led horizontal row, with 20px gutters and a partially visible next card. Story cards maintain compact annotation spacing; major selections are separated by 170px.

**Transfer:** Use to reveal a curated range of uses, outputs or stories without making every item a feature panel.

### Headline and portrait feature

**Observed:** A 60px regular serif uppercase title and sentence-case sentence form a centered typographic event above a small 212px-wide portrait. An alternate asymmetrical version uses 50px/52px text across roughly half the content width and a 444px-wide portrait at the right. Small category annotations sit below the text or image.

**Transfer:** Elevate one person, craft process or product idea through an editorial headline instead of a conventional benefit icon row.

**Text style:** `editorial-display` — Kinfolk-Serif-Deck 400 · 60px/1 · tracking -0.005em

### Preview chapter

**Observed:** Preview stock holds a centered section-label and section-heading pair, then 110px before a three-column selection of Story cards. The content is about 1024px wide and the band has 110px top and 120px bottom padding.

**Transfer:** Offer a specific taste of the collection, service or output in this single colored-paper interlude.

### Interview index

**Observed:** A 32px serif heading above ruled rows: small 212 × 285px portrait at left, large 60px title and description in the middle, small metadata aligned at the far right. Three entries illustrate the pattern without card shells.

**Transfer:** Use for substantial proof, maker profiles or customer perspectives; preserve the imbalance between small portrait and large language.

**Text style:** `editorial-display` — Kinfolk-Serif-Deck 400 · 60px/1 · tracking -0.005em

### Inverted closing spread

**Observed:** Offer spread and Utility footer form a single black ending. The centered heading pair, left plan details, narrow hands-on media and low corner actions are the composition; the footer's white top rule resolves it.

**Transfer:** End with a concrete next relationship to the product: ownership, access or membership. Keep the editorial spread construction rather than turning it into a centered button banner.

### Institutional details

**Only for:** company and support pages

**Observed:** Two broad 32px/38px serif opening paragraphs lead into 2px top-ruled rows with 20px top and 100px bottom padding. Small uppercase labels occupy the left; compact columns or 618px-wide accordions begin well into the right half.

**Transfer:** Organize factual detail as an index with generous empty space rather than a dense prose column.

### Catalog and archive index

**Only for:** catalog and archive pages

**Observed:** A centered comma-separated category sentence sits after 315px of top whitespace, with 110px below it before the black baseline. Product lists use three spacious centered columns; story lists use four portrait columns and 75px row gaps. Archive filtering includes a small uppercase issue selector and a thin bottom status bar.

**Transfer:** Use the product version for things to buy and the archive version for things to read; do not average their distinct image scales.

## Page flow

**Storyline:** Isolated object or concise orientation → curated exploration → deeper editorial perspective → tangible offer → inverted relationship close.

### A flagship product and editorial landing experience

1. **Product introduction** — Centered edition title and isolated product, followed by a full-bleed editorial image.
2. **Curated exploration** — Ruled horizontal selections alternate with small portrait features.
3. **Product experience** — Grey-green preview chapter, newsletter line and immersive photographic statement.
4. **Depth and ownership** — Asymmetrical feature, product selection, paired image stories and a large-type interview index.
5. **Route choice** — Three photographic destination tiles and a comma-separated browsing index.
6. **Closing relationship** — Black offer spread followed by the narrow white-ruled utility footer.

**Transfer:** Borrow the alternation of collectible object, human story and product detail; adapt the number and order of chapters to the new narrative.

### A shoppable collection

1. **Orientation** — Centered category sentence with the selected category in grey.
2. **Comparison** — Repeated three-column product cards with isolated covers, uppercase serif titles and plain prices; the final row can be incomplete.
3. **Closing relationship** — Black offer spread and utility footer.

**Transfer:** Let products differ through their imagery, keeping the card construction fixed and unboxed.

### A browsable editorial archive

1. **Orientation** — Issue selector above comma-separated category links and a black rule.
2. **Exploration** — Long four-column portrait grid with category notes, uppercase titles and one-sentence summaries; a compact viewing-status bar supports browsing.
3. **Closing relationship** — Black offer spread and utility footer after the archive grid.

**Transfer:** Scale the grid to the available library; preserve the editorial hierarchy rather than the original archive length.

### Institutional introduction and practical information

1. **Positioning** — Two expansive serif paragraphs establish purpose and reach without a hero image.
2. **Operational trust** — Ruled rows organize people, locations and contact channels in small sans columns.
3. **Objection handling** — Right-aligned FAQ and opportunity accordions within the same ruled-row structure.
4. **Closing relationship** — Black offer spread and utility footer.

**Transfer:** Use the factual layout for any concise company or service information page, with only relevant detail categories.

## Writing

An observant editor rather than a salesperson: cultured, specific and sometimes playful. Intrigue comes from a well-chosen subject or a compact question, while practical offer language is direct.

**Do not copy:** Do not reuse the Kinfolk name, logo, issue numbers, article titles, named contributors, publication history, subscriber claims, original prices or quoted statements as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Editorial descriptions usually speak in the third person or use impersonal phrases. Direct you-language appears in useful subscription explanations, while actions use simple verbs.
- **Rhythm:** Short titles often run two to five words, followed by a one-sentence deck. Larger statements can carry an entire thought over several lines; exclamations and stacked sales superlatives are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product designation | A concise edition label followed by a theme, displayed as two uppercase serif lines. | 2–6 words | “Issue 61”<br>“THE PLAY ISSUE” |
| Editorial title | Compact noun phrase, gentle wordplay or a pointed question. | 2–7 words | “Mind Games”<br>“What Makes a Classic?” |
| Supporting line | One concrete premise or a description of the subject, not a list of benefits. | 6–20 words | “Why keeping score doesn’t work.”<br>“The British artist and designer behind some of the design world’s most playful pieces.” |
| Section name | A curatorial invitation or useful index term. | 1–5 words | “Worth Revisiting”<br>“In Conversation” |
| Action | Familiar verbs and navigation labels, without urgency. | 1–3 words | “Learn More”<br>“View All”<br>“Subscribe” |

**Words and phrasing to use:** Inside; In Conversation; At Work With; Discover; A conversation with; A short history of; On the…

**Avoid:** revolutionary; game-changing; unlock your potential; hurry; limited-time deal; best-in-class

**Rules:**

- Prefer one revealing detail over an abstract promise.
- Keep category notes factual and distinct from the title.
- Let a short title and a longer deck complete one another instead of repeating the same claim.
- Use transparent terms and eligibility details when describing an offer.

## Do's and Don'ts

### Do

- Keep display and section type at weight 400; contrast 60px features with 15px annotations.
- Use 20px column gutters across portrait grids and wider editorial spreads.
- Preserve the 5px, 15px and 2px metadata/title/description sequence on story cards.
- Leave 170px of chapter breathing room around major editorial shifts.
- Stage an isolated object on white as well as showing it in a tactile real-world scene.
- Use 2px rules as structural lines, not faint card borders.
- Retain small 2px-corner outlined actions on the black ending.
- Keep product prices at 20px sans while titles remain 25px serif.

### Don't

- Do not bold the 32px or 60px serif headings to manufacture hierarchy.
- Do not give editorial cards 12px corners, shadows or padded colored shells.
- Do not promote photographic reds or blues into recurring button and background tokens.
- Do not stretch product cover artwork to fill the whole 444px catalog cell.
- Do not turn the comma-separated 32px browsing list into rounded tabs.
- Do not center every text block: the institutional details and asymmetrical features rely on lateral alignment.
- Do not expand the 72px utility footer into a large sitemap.
- Do not use 20px body copy for compact story summaries; their working size is 15px.

## Motion and responsive

### Motion

**Observed:**

- Actions declare opacity changes to 0.4 on hover; outlined actions use opacity 0.5s cubic-bezier(0.25, 1, 0.5, 1).
- Editorial actions also declare opacity 0.4s, transform 0.4s, color 0.4s transitions.
- The opening is a pinned product stage and the large photographic feature uses a sticky text layer.

**Transfer:**

- Preserve the restrained fading-link behavior and the separation between a still product stage and a taller immersive image chapter.

**Unknown:**

- Exact scroll choreography, focus-visible appearance and active states are not established.

### Responsive

**Observed:**

- The desktop composition uses a 24-column scaffold, 20px gutters and a fixed 54px header.
- Styles declare width breakpoints including 740px, 835px, 1024px, 1200px, 1280px and 1440px.

**Transfer:**

- On narrower layouts, preserve the centered object stage and comma-list wrapping. Reduce the number of image columns before shrinking the annotation type excessively.
- Stack the lateral parts of the black offer while retaining its narrow hands-on media and small outlined actions; keep information labels attached to their ruled content rows.

**Unknown:**

- Specific mobile column counts, ordering, type sizes and pinned-scene behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
