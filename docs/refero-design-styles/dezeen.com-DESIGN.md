# Dezeen — stories in unequal lanes

## Overview

An image-led editorial style with the pace of a specialist magazine and the utility of a directory. White pages, black keylines and compact grotesk headlines give way to serif reading text, with navy, dusty pink and brick red reserved for distinct service modules. Large documentary photographs sit beside smaller stories and practical controls, producing a dense but strongly ordered experience suited to collections, product discovery and evidence-led marketing.

### Essentials

- The lead is a photograph, not a slogan: a 624px square image anchors an unequal 624px + 300px editorial pair, with a separate 300px service rail and 24px gutters.
- Headlines behave like news: Standard CT bold at 32px/1.25 for lead stories and 20px/1.25 for smaller cards, normal tracking and sentence case rather than monumental display lettering.
- Taxonomy attaches directly to the picture: 28px-high rectangular badges use 14px bold text, 7px padding and adjacent light-gray and black fills; headlines follow about 12px below.
- Controls are small square tools: 32px icon buttons and dropdowns, 0px corners, flat fills and 3px gray focus outlines rather than rounded conversion pills.
- The page stays predominantly white and black; color is concentrated inside imagery and isolated service modules, such as a 300px navy audio card or dusty-pink listing card, not spread across all sections.
- Black keylines are the recurring organizing device: 3px rules crown compact section labels and footer groups; use them with the unequal image hierarchy even when the new product needs original diagrams in place of photography.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, text, surface | Main canvas, email fields and reverse text. |
| Utility gray | `#eeeeee` | `--color-utility` | surface, background, border, action | Category badges, dropdowns, newsletter panels and the footer. |
| Muted gray | `#757575` | `--color-muted` | text, border | Footer group headings and 3px focus outlines. |
| Black ink | `#000000` | `--color-ink` | text, surface, action, border | Primary headlines, keylines, active controls and inverse editorial cards. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audio features | Audio navy | `#10376b` | `--color-audio` | surface | Solid backing for a compact audio-player module. |
| dated listings and event discovery | Listing pink | `#e09c9e` | `--color-listing` | surface | Isolated image-led listing cards with black text. |
| product catalog pages | Catalog brick | `#ab2d17` | `--color-catalog` | surface, action, link, border | Catalog category labels, promotional actions and subscription panel; white type on the solid fill. |

## Typography

- **Standard CT** — Headlines, taxonomy, controls and footer navigation. Matter-of-fact grotesk with a compact bold news voice and restrained regular utility text. If unavailable, use **Libre Franklin**. Use 400 and 700; preserve the compact line lengths and normal tracking. Font stack: "Standard CT", "Libre Franklin", Arial, sans-serif.
- **Chronicle Text G1** — Reading paragraphs, inline links, contributor names and copyright. Text serif with sturdy contrast and a recognizably editorial texture. If unavailable, use **Libre Baskerville**. Use 400; check wraps against the narrow reading columns. Font stack: "Chronicle Text G1", "Libre Baskerville", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| lead-headline | Standard CT | 700 | 32px | 1.25 | normal | fixed | Lead story or evidence headline below a large photograph. |
| signup-heading | Standard CT | 700 | 32px | 1.2 | normal | fixed | The closing subscription invitation, distinct from the lead-story line height. |
| card-headline | Standard CT | 700 | 20px | 1.25 | normal | fixed | Secondary story titles, product titles, quotations and feature links. |
| section-heading | Standard CT | 700 | 20px | 1.2 | normal | fixed | Compact keyline labels and footer group titles. |
| footer-link | Standard CT | 400 | 20px | 1.2 | normal | fixed | Footer links; keep their compact line spacing and strong visual presence. |
| body | Chronicle Text G1 | 400 | 18px | 1.35 | normal | size clamp(16px, 13.4px + 0.446vw, 18px) | Feature summaries and newsletter explanation, with underlined inline links. |
| badge | Standard CT | 700 | 14px | 1 | normal | fixed | Short category labels and pagination numbers. |
| utility-label | Standard CT | 700 | 14px | 1.25 | normal | fixed | Navigation selectors, filter controls and compact action text. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use normal tracking throughout; hierarchy comes from size, weight, image scale and lane width, not letterspacing or all capitals.
- Serif paragraphs provide a deliberate change of texture below bold sans-serif titles. Do not turn every card into a paragraph-heavy panel.
- The footer link recipe is regular; retain a visually sturdy grotesk rather than artificially increasing all footer text to heading weight.

## Layout

**Density:** Compact editorial density: short local gaps and long independent image lanes, with 24px module spacing rather than oversized landing-page interludes.

### Spacing

| Value | Use |
| --- | --- |
| 3px | Tight separation between compact navigation controls and thickness of keylines. |
| 6px | Internal icon-and-label gaps. |
| 7px | Badge padding on every side. |
| 8px | Email-field control gap and inset. |
| 12px | Taxonomy-to-title separation and heading-to-support spacing. |
| 24px | Column gutters, card-row gaps and newsletter/footer padding. |
| 32px | Vertical spacing around feature bands and before the closing signup. |

### Containers and grids

- **outer-container**: max width 1320px · side padding 24px. Centered outer frame. Its inner content is 1272px wide at a 1440px viewport, leaving 84px from viewport edge to editorial content.
- **editorial-lanes**: max width 1272px · 3 columns · gap 24px. 624px lead lane, 300px secondary lane and 300px service rail; the first two form a 948px main area. Later bands can swap the wide and narrow story lanes.
- **feature-pair**: max width 1272px · 2 columns · gap 24px. Two 624px-wide feature cards with landscape media and short serif summaries.
- **catalog-grid** (only for product catalog pages): max width 948px · 3 columns · gap 24px. 300px product cards in the main region, with selected 624px-wide cards spanning two columns; a separate rail occupies the remaining width.
- **category-strip** (only for product catalog pages): max width 1272px · 8 columns · gap 24px. Eight 138px-square category thumbnails, each with a short bold label below.

## Corner radius

| Element | Radius |
| --- | --- |
| cards-and-controls | 0px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default page and unboxed editorial cards.

**CSS:** `background: #ffffff; color: #000000; border-radius: 0px; box-shadow: none`

**Observed:** Images and text sit directly on the page without card outlines or elevation.

**Transfer:** Let gutters, image edges and keylines establish grouping.

#### Utility panel · level 0

**Use:** Newsletter panel and full-width footer band.

**CSS:** `background: #eeeeee; color: #000000; padding: 24px; border-radius: 0px; box-shadow: none`

**Observed:** A solid neutral plane, not a translucent or raised surface.

**Transfer:** Use it to distinguish practical actions from the surrounding editorial material.

#### Inverse editorial panel · level 0

**Use:** A narrow interview or quotation feature.

**CSS:** `background: #000000; color: #ffffff; padding: 16px; border-radius: 0px`

**Observed:** Inset portrait or contextual photograph above a white title, with a serif contributor line near the bottom.

**Transfer:** Use one such panel to give a substantive testimonial the status of an editorial story.

#### Audio panel · level 0

**Only for:** audio features

**Use:** Self-contained player backing.

**CSS:** `background: #10376b; color: #ffffff; border-radius: 0px`

**Observed:** Square cover art, title, date, progress line and controls occupy a narrow solid-color card.

**Transfer:** Retain the rectangular silhouette and white-on-navy utility treatment.

#### Dated listing panel · level 0

**Only for:** dated listings and event discovery

**Use:** Compact listing with artwork, title and dates.

**CSS:** `background: #e09c9e; color: #000000; padding: 24px; border-radius: 0px`

**Observed:** A 300px-wide card contains a 252px square image; the text continues below on the same pink plane.

**Transfer:** Use for a relevant time-bound offer rather than tinting the entire page.

#### Catalog subscription panel · level 0

**Only for:** product catalog pages

**Use:** Catalog signup and related category accents.

**CSS:** `background: #ab2d17; color: #ffffff; padding: 24px; border-radius: 0px`

**Observed:** The closing signup uses the same brick hue as product category badges; the email field remains white.

**Transfer:** Keep this a coherent catalog theme rather than replacing the default neutral newsletter everywhere.

## Components

### Masthead navigation

**Use:** Brand identification and compact route selection.

**CSS:** `background: #ffffff; max-width: 1320px; padding: 24px 24px 12px; column-gap: 24px`

**Text style:** `utility-label` — Standard CT 700 · 14px/1.25

**Observed:** An asymmetric black wordmark sits left in a tall white masthead; search aligns right. A full-width black keyline tops the short navigation row below. The active service selector is black; gray topic selectors and a square menu control cluster at the right.

**Transfer:** Give the new identity a strong left-aligned mark with a similarly compact utility row, not a row of large navigation pills.

### Category badge

**Use:** Attach classification directly beneath media.

**CSS:** `display: inline-flex; background: #eeeeee; color: #000000; padding: 7px; height: 28px; box-sizing: border-box; border-radius: 0px`

**Text style:** `badge` — Standard CT 700 · 14px/1

**Observed:** Labels abut the bottom edge of the image and sit adjacent to each other. A black badge with white text distinguishes editorial format; catalog category badges use brick red while maker labels remain gray.

**States:** Declared: hover underlines text and changes to white on black; focus-visible uses a 3px solid #757575 outline with 0px offset and white on black.

### Square utility button

**Use:** Search and menu tools.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 32px; height: 32px; background: #eeeeee; color: #000000; border: 1px solid #eeeeee; border-radius: 0px`

**Observed:** A 20px filled icon is centered inside the square; the accessible text label is hidden visually.

**States:** Declared: hover and active use white on black with a black border; focus-visible adds a 3px solid #757575 outline at 0px offset.

### Filter selector

**Use:** Compact topic, section or catalog filtering.

**CSS:** `display: inline-flex; justify-content: space-between; align-items: center; background: #eeeeee; color: #000000; height: 32px; width: 134px; padding: 6px 6px 6px 10px; gap: 6px; box-sizing: border-box; border-radius: 0px`

**Text style:** `utility-label` — Standard CT 700 · 14px/1.25

**Observed:** Left-aligned text and a downward chevron; several controls group into a single short toolbar.

**States:** Declared: focus-visible uses a 3px solid #757575 outline at 0px offset.

### Editorial card

**Use:** Image-led proof, news or capability story.

**CSS:** `background: #ffffff; color: #000000; width: 300px; border-radius: 0px`

**Text style:** `card-headline` — Standard CT 700 · 20px/1.25

**Observed:** Square image, Category badge row, then bold linked headline. The lead version doubles to 624px and uses lead-headline; most cards have no paragraph. The media is clipped and object-fit cover.

**States:** Declared: hover on the title underlines it and uses black text on #eeeeee; focus-visible adds a 3px solid #757575 outline at 0px offset with the same highlight.

**Transfer:** Replace news with genuine product outcomes while keeping the image-first hierarchy.

### Keyline section header

**Use:** Name recurring groups and expose carousel navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; column-gap: 24px; row-gap: 4px; margin-bottom: 24px; border-top: 3px solid #000000`

**Text style:** `section-heading` — Standard CT 700 · 20px/1.2

**Observed:** A small bold label sits just below the rule at left; paired 32px black arrow controls finish the line at right. The rule supplies structure without enlarging the heading.

### Email signup

**Use:** Low-friction closing conversion.

**CSS:** `background: #eeeeee; color: #000000; max-width: 948px; padding: 24px; display: flex; flex-direction: column; gap: 12px; border-radius: 0px`

**Text style:** `signup-heading` — Standard CT 700 · 32px/1.2

**Observed:** Heading spans the panel; body text and form occupy a much narrower 384px column at left, leaving substantial unused width on the right. The form begins 24px after the body. A catalog variant reverses the text onto brick red.

**Transfer:** Promise a specific useful update, then request only an email address.

### Email field and next control

**Use:** Single-field signup submission.

**CSS:** `display: flex; align-items: center; column-gap: 8px; background: #ffffff; width: 384px; height: 48px; border-radius: 0px`

**Text style:** `body` — Chronicle Text G1 400 · 18px/1.35

**Observed:** White rectangular field with serif placeholder, visible label supplied accessibly, and a 32px black square containing a white right chevron inset 8px from the right. The field has a 1px outline whose color should remain visually unobtrusive.

**States:** Declared: the next control changes to black on #eeeeee on hover and active; focus-visible adds a 3px solid #757575 outline with 0px offset.

### Keep reading pagination

**Use:** Continue a long collection without an oversized CTA.

**CSS:** `display: flex; justify-content: space-between; height: 32px; border-top: 3px solid #000000; color: #000000`

**Text style:** `badge` — Standard CT 700 · 14px/1

**Observed:** The left label uses section-heading; 32px page tiles group at the far right. Current page is black with white type; other page tiles are gray. Previous and next arrows bracket the sequence.

**Transfer:** Use only when there is an actual collection to continue.

### Footer directory

**Use:** Service navigation, contact and subscription access at the page ending.

**CSS:** `background: #eeeeee; color: #000000; padding: 24px 0px; border-radius: 0px`

**Text style:** `footer-link` — Standard CT 400 · 20px/1.2

**Observed:** A 192px-wide brand mark occupies the left half; three 192px navigation columns share the right half with 24px gutters. Each group begins with a black keyline and muted gray heading. A second row holds subscription and social links; serif copyright rests low on the left.

**States:** Declared: link hover underlines black text; focus-visible uses a 3px solid #757575 outline at 0px offset and underlining.

## Imagery and graphics

### Documentary lead photography

**Use:** Dominant visual proof in lead and secondary story lanes.

**Observed:** Architecture, interiors and objects are shown with their physical surroundings intact: aerial geometry, front elevations, people at room scale and close material detail. Natural daylight, warm interiors and occasional strong color coexist without a global tint. Square edge-to-edge photographs occupy much more area than their captions; 624px and 300px squares share the same visual grammar.

**Transfer:** Commission real product-in-use images or carefully lit physical evidence of an outcome. For digital products, use a clean square composition of the working interface with one meaningful task visible, not a decorative device pile.

### Landscape feature imagery

**Use:** Wider editorial explanations and curated comparisons.

**Observed:** Two 624px × 351px images sit side by side, with 20px bold titles and serif summaries underneath. Wide aerial or environmental scenes retain context rather than isolating a tiny subject on a blank canvas.

**Transfer:** Use landscape demonstrations showing the product's operating environment or consequences. Preserve context, natural color and hard rectangular framing.

### Product catalog photography

**Only for:** product catalog pages

**Use:** Category strip and product listing grid.

**Observed:** Furniture and materials alternate between softly lit studio scenes, domestic interiors and close texture details. Neutral stone, concrete and wood backings allow occasional saturated red, blue or green products to stand out. Category images are 138px squares; product media is 300px square or 624px × 300px for a spanning story.

**Transfer:** Combine neutral studio images with believable use environments; keep scale and material detail legible rather than forcing every object onto identical cutout backgrounds.

### Serial cover collage

**Only for:** recurring audio or video series

**Use:** A recognizable repeated cover system for episodes.

**Observed:** Square covers combine several topical photographs in angular triangular windows. Broad crossing diagonal bands in cool blue and lilac connect them; a white rotated date rides one diagonal and a compact series title sits low on the artwork. The collage repeats at both image scales.

**Transfer:** Use original topic imagery and a new series identity while retaining the geometric montage and consistent dating system. A minimum version uses two photos and one broad diagonal date band.

**Build:** Use a square SVG with three or four polygon clipPaths at the top and side edges. Place photographs inside those masks over a cool blue-to-lilac backing. Overlay two broad diagonal polygons crossing around the center, each roughly one quarter of the square width. Set a short white date along the rising band at about -35deg and place the new series title in a solid dark color at lower left. Keep all art within the square; no external shadow.

### Icons

**Observed:** Filled black utility SVGs at 20px sit in 32px square tools; social marks occupy 32px boxes. Chevron arrows and a simple triangular play mark favor solid, compact shapes over thin decorative strokes.

**Transfer:** Choose a single solid utility set for search, menu, arrows and play. Keep social symbols recognizable and separate from editorial imagery.

## Section recipes

How recurring sections are built.

### First screen: Unequal editorial opening

**Observed:** The first screen layers a wide promotional creative above a white masthead, then a short keylined navigation row and immediately the unequal Editorial card lanes. At desktop the masthead occupies about 195px, with the logo left and small Search control right; the navigation is 32px high. Content begins around 523px down the 900px screen. The 624px square lead image fills roughly half the content width, a 300px square secondary story sits beside it and a separate 300px service rail sits right. Only the upper portion of the lead photograph is visible before the fold; its badges and 32px bold headline are below it. There is no separate centered slogan, support paragraph or large hero button. Secondary-story text can already be visible within the first screen.

**Transfer:** For a marketing page, make the main photograph an immediate demonstration of the product's value, and the adjacent card a complementary use case. Keep headline text beneath media rather than overlaying it. A populated promotional creative can sit above the masthead when relevant, but it is not a reserved empty band. A catalog opens instead with a small-image category strip and filter row; a series archive adds a compact 20px collection heading before the lanes.

**Avoid:** Do not replace the editorial opening with a full-viewport centered headline, a dark cinematic scene or a large floating signup button; do not preserve empty promotional space.

**Text style:** `lead-headline` — Standard CT 700 · 32px/1.25

### Keylined feature pair

**Observed:** Keyline section header spans the content frame, followed after 24px by two landscape feature cards. Each image is 624px × 351px; compact bold titles precede short serif descriptions. The enclosing band uses 32px vertical padding.

**Transfer:** Use for two complementary explanations, comparisons or customer outcomes. Keep the label modest and let the image pair carry the emphasis.

**Text style:** `card-headline` — Standard CT 700 · 20px/1.25

### Independent story lanes

**Observed:** Editorial cards descend in independent wide and narrow columns with 24px gaps. A later group reverses the wide and narrow lane positions; the service rail stays visually separate and can retain a module while stories continue.

**Transfer:** Adapt the number of stories to the available proof; use the unequal rhythm rather than manufacturing equal-height rows or a fixed number of sections.

### Opinion or interview insert

**Observed:** An Inverse editorial panel combines a contextual portrait, compact classification, a bold quotation and a serif contributor name. Wider opinion strips pair a 208px square image with text inside a 624px-wide slide.

**Transfer:** Present expert testimony as a small published story, with a specific attributed claim and a relevant portrait, rather than a centered quote floating between star ratings.

### Practical closing

**Observed:** Keep reading pagination ends the feed. Email signup follows after 32px, aligned to the 948px main region rather than spanning all columns. A populated promotional banner appears between the signup and Footer directory. The final footer is a 348px-tall gray band with the identity left, keylined navigation groups right and small social marks below.

**Transfer:** End with continuation when relevant, a useful single-field invitation and a real navigation directory. A promotional banner must contain meaningful original content; the footer should feel like a compact index rather than a second hero.

**Text style:** `signup-heading` — Standard CT 700 · 32px/1.2

### Catalog discovery grid

**Only for:** product catalog pages

**Observed:** A category strip precedes a keylined filter bar. Below it, a 948px three-column product grid mixes 300px-square media and selected two-column 624px × 300px media. Brick category badges and gray maker badges attach below each image; 20px bold product descriptions follow. A narrow rail carries promotion and a subscription card.

**Transfer:** Use for a browsable offering with actual categories and makers or product families. Keep the spanning cards as editorial emphasis, not arbitrary masonry.

**Text style:** `card-headline` — Standard CT 700 · 20px/1.25

## Page flow

**Storyline:** Image-led promise → related evidence in unequal lanes → curated explanatory breaks → continued discovery → practical subscription → service directory.

### Editorial discovery landing page

1. **Promise** — Large visual lead beside smaller related stories and a compact service rail.
2. **Depth** — Keylined two-card feature band introduces short serif explanations.
3. **Continued proof** — Further story groups change lane emphasis and introduce expert quotations or dated listings.
4. **Closing action** — Compact pagination, neutral subscription panel, populated promotional creative and a gray directory footer.

**Transfer:** Translate stories into use cases and customer outcomes; keep the visual hierarchy without inheriting the length of a news feed.

### Recurring series archive

1. **Orientation** — Compact collection title below the shared masthead.
2. **Discovery** — Large and small square serial covers run in separate lanes, alongside a navy player and interview module.
3. **Continuation** — Keep-reading controls follow the episode collection.
4. **Closing action** — Neutral email signup, promotional banner and the shared gray footer.

**Transfer:** Use for a recurring educational or demonstration series with real playable media and a consistent cover system.

### Product discovery catalog

1. **Orientation** — Eight thumbnail categories and a compact filter bar.
2. **Offering** — Three-column grid with selected double-width image stories and a service rail.
3. **Curation** — Wide special-feature pair adds editorial context before more products.
4. **Closing action** — Pagination and brick-red subscription panel precede promotional creative and the shared directory footer.

**Transfer:** Use for products that benefit from browsing by type; retain the editorial imagery rather than turning the grid into price-and-cart tiles.

## Writing

Specific, observant and editorial rather than sales-led. Concrete subjects and active verbs carry the confidence; questions and attributed quotations create curiosity without promising universal transformation.

**Do not copy:** Do not reuse the brand identity, artwork, publication names, named projects, quotations, dates, copyright, superlatives or institutional claims. Examples illustrate syntax only; supply original, substantiated product facts and permissions.

- **Addressing the reader:** Most headlines describe the subject in the third person. Direct address appears in practical signup instructions; first-person plural is reserved for a conversational recurring series or an editorial question.
- **Rhythm:** Lead headlines are often one descriptive clause across two or three lines. Short category labels punctuate the feed; explanations use one or two readable serif sentences. Questions are direct, not rhetorical hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Lead headline | Named subject + active verb + concrete distinguishing feature. | About 8–16 words | “Arup creates arrow-shaped viewpoint for Fehmarnbelt Tunnel project” |
| Series headline | A direct question that names a real subject and stakes. | About 6–14 words | “Is this year’s Stirling Prize winner a worthy victor?” |
| Section label | Plain noun phrase identifying the kind of material. | 1–3 words | “Special features”<br>“More stories” |
| Supporting line | State what the reader will receive and how to proceed. | 1–2 sentences | “Receive a quarterly editor's pick of newly-released furnishings launched in the previous season.” |
| Action | Compact literal instruction, not an aspirational promise. | 1–4 words | “See all episodes”<br>“Promote your products”<br>“Keep reading” |

**Words and phrasing to use:** creates; designs; extends; introduces; by; for; features; more; sign up; receive

**Avoid:** revolutionary; game-changing; unlock your potential; seamless solutions; world-class without proof; excessive exclamation marks

**Rules:**

- Lead with a concrete object, activity or result rather than a broad brand manifesto.
- Credit creators and attribute quotations when relevant; do not use anonymous quotation marks as decoration.
- Use questions for genuine topics of inquiry, not as a substitute for a clear product promise.
- Keep taxonomy short enough to work inside 28px-high badges.
- Reserve direct instructions for actions and forms; keep editorial summaries descriptive.

## Do's and Don'ts

### Do

- Keep lead headlines at 32px/1.25 bold with normal tracking.
- Pair 624px lead media with 300px secondary media across 24px gutters.
- Place 28px taxonomy badges directly against the lower image edge.
- Use 20px compact keyline labels rather than large chapter titles.
- Keep serif explanations at 18px/1.35 and narrow signup text to 384px.
- Use 0px corners and no elevation throughout the page furniture.
- Keep the closing signup at 948px maximum width with 24px padding.
- Preserve the left identity/right directory split in the gray footer.

### Don't

- Do not use letterspaced uppercase eyebrows in place of the bold 14px category badges.
- Do not round category labels into pills or increase square tools into oversized CTA blocks.
- Do not turn every image story into a bordered card with a shadow.
- Do not replace the serif reading texture with an all-sans interface.
- Do not apply navy or brick red as the default full-page background; they identify specific modules.
- Do not center the signup form across the full panel; its 384px column belongs at left.
- Do not normalize lead-story and signup headings to one line-height: they use 1.25 and 1.2 respectively.
- Do not add a uniform color wash over photography; preserve real material and lighting differences.

## Motion and responsive

### Motion

**Observed:**

- Image transforms declare 320ms cubic-bezier(0.135, 0.75, 0.355, 1); some smaller transform rules use 80ms with the same curve.
- Some backgrounds declare 0.2s ease-in transitions.
- Hover underlines and hard black/gray inversions provide the primary action feedback; carousel controls are compact arrows.

**Transfer:**

- Keep media clipped within hard rectangular edges when applying the declared transform transition.
- Use restrained state changes on badges and tools rather than animating whole editorial sections.

**Unknown:**

- The image hover transform endpoint and actual carousel movement behavior are not established.
- No entrance-animation sequence or mobile motion behavior is established.

### Responsive

**Observed:**

- Declared CSS boundaries include 576px, 768px, 1024px, 1124px, 1200px and 1440px; a further 1272px boundary exists for the editorial layout.
- The body-text recipe has a fluid 16px-to-18px size rule.

**Transfer:**

- On narrower screens, prioritize the lead story before secondary discovery and service content; retain square media and attached badge rows.
- Collapse the unequal lanes rather than proportionally shrinking a 300px rail into unreadable cards; treat this as an adaptation rule.
- Allow the category strip to remain navigable without compressing eight thumbnails into tiny squares, and make the email field fit its panel.

**Unknown:**

- Mobile column counts, masthead dimensions, category-strip behavior and exact breakpoint-to-layout mappings are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
