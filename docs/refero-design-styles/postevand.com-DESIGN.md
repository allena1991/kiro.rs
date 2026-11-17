# Postevand — ruled object theatre

## Overview

A stark, light editorial style that gives ordinary physical products the presence of exhibition objects. Black rules and small utilitarian grotesk labels organize expansive white and pale grey fields, while enormous regular-weight statements interrupt the fine print. Grainy outdoor photography and luminous studio product studies bring the emotion and color; the surrounding interface stays almost entirely monochrome. It suits material-led products and evidence-led brands with a restrained, candid voice.

### Essentials

- The opening behaves like a photographic poster, not a sales panel: full-bleed imagery fills a 900px desktop screen beneath a 40px fixed navigation strip, with a white wordmark artwork about 1238px wide and 195px high anchored near the bottom.
- A hairline framework replaces floating cards: 1px black dividers connect edge-to-edge halves and thirds, with 20px text insets, square corners and no interface shadows.
- Headlines feel like plainspoken declarations enlarged beyond their usual role: Nimbus Sans D OT at 80px/1, weight 400, -0.01em tracking; compact titles instead use 12px/1.2, weight 700, uppercase and 0.01em tracking.
- Actions are part of the architecture: 140px-wide, 39px-high rectangular navigation cells with a 1px left rule, or tiny underlined text links; there are no rounded conversion pills.
- Color lives in the pictures: white and #f0f1ef occupy essentially all interface surfaces, with black text and rules. Photographic sky, skin, grass and material colors can occupy a whole screen but never become decorative UI accents.
- The object is both specimen and proof: a white studio stage presents a central product with 80px statistics on its flanks and small explanatory copy above. Use a clean photograph or cutaway diagram on the same stage when a rendered object is unavailable.
- The ending is a principled refrain, not a giant button: a compact 150px ruled utility footer gives way to an 80px-high, edge-clipped repeating line in 56px/1.2 regular type. Carry a truthful, reader-serving principle into this device on every new page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink and rule | `#000000` | `--color-ink` | text, border, action | All primary text, dividers and the exposed backing of 1px grid gaps. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale mineral stage | `#f0f1ef` | `--color-stage` | background, surface | Product photography backings and neutral media stages. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Primary canvas and text panels; reversed wordmark over opening photography. |

## Typography

- **Nimbus Sans D OT** — All headings, paragraphs, labels and navigation. A neutral neo-grotesk with open, unembellished regular-weight statements and compact bold labelling. If unavailable, use **Libre Franklin**. Use 400 and 700; preserve wide regular headlines and tight display tracking. Font stack: "Nimbus Sans D OT", "Libre Franklin", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Nimbus Sans D OT | 400 | 80px | 1 | -0.01em | size 5.55556vw | Major marketing statements and large, centered product proof statistics. |
| explanation | Nimbus Sans D OT | 400 | 56px | 1.2 | -0.01em | size 3.88889vw | Extended claims in half-width panels. |
| refrain | Nimbus Sans D OT | 400 | 56px | 1.2 | normal | fixed | Single-line repeating principle at the bottom of every page. |
| invitation | Nimbus Sans D OT | 400 | 32px | 1.2 | -0.01em | fixed | Conversion-section statements beside a stack of action rows. |
| body-feature | Nimbus Sans D OT | 400 | 16px | 1.4 | normal | fixed | Short centered introductions above a product demonstration. |
| body | Nimbus Sans D OT | 400 | 12px | 1.4 | normal | fixed | Editorial paragraphs, media-card support and inline links. |
| label | Nimbus Sans D OT | 700 | 12px | 1.2 | 0.01em, uppercase | fixed | Product names, action-row titles and compact editorial section headings. |
| navigation | Nimbus Sans D OT | 400 | 12px | 1.4 | normal, uppercase | fixed | Unboxed navigation links; current destinations become bold. |
| navigation-cell | Nimbus Sans D OT | 400 | 12px | 1 | normal, uppercase | fixed | Centered text in the ruled navigation action cells. |
| caption | Nimbus Sans D OT | 400 | 10px | 1.4 | normal | fixed | Report citations, footer links and the short footer description. |
| utility-label | Nimbus Sans D OT | 700 | 10px | 1.2 | 0.01em, uppercase | fixed | Footer navigation group headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| trade and partnership landing pages | partner-display | Nimbus Sans D OT | 400 | 96px | 1 | -0.01em | fixed | Centered multi-line proposition in a white, viewport-height opening. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The photographic opening's huge lettering is wordmark artwork, not an 80px heading. Keep its near-full-width silhouette distinct from the text scale.
- Regular weight carries almost every large statement; bold is reserved for small uppercase labels and current navigation.
- Do not turn every paragraph into a 16px reading block: the contrast between 12px editorial detail and 80px statements is central.
- Keep long prose left aligned even when its 640px column is centered on the page.

## Layout

**Density:** Airy at the section scale and deliberately compact within labels, descriptions and the utility footer.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 1px | Grid seams and section rules. | fixed |
| 10px | Small navigation padding and footer list separation. | fixed |
| 20px | Standard panel insets, editorial heading separation and utility column gaps. | fixed |
| 24px | Product-card title vertical padding. | fixed |
| 40px | Action-row vertical padding and product-image inset. | fixed |
| 67.2px | Large half-panel headline side padding. | 4.66667vw |
| 80px | Top and bottom padding of narrow editorial text sections. | fixed |
| 180px | Separation between successive refrain copies. | fixed |

### Containers and grids

- **edge-to-edge framework**: max width 1440px · 12 columns · gap 1px · side padding 0px. Black-backed structural grid with white children; compose halves, thirds and one-third/two-thirds combinations rather than a centered card deck.
- **editorial column**: max width 640px · side padding 20px. Centered prose column inside full-width ruled bands.
- **product grid**: 3 columns · gap 1px · side padding 0px. Square product tiles, about 479px per side at desktop width.
- **partner proposition** (only for trade and partnership landing pages): max width 1160px · side padding 20px. Centered statement with a stack of square product images moving in front of it.

## Corner radius

| Element | Radius |
| --- | --- |
| panels and actions | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Page field and editorial panels.

**CSS:** `background: #ffffff; color: #000000`

#### Ruled framework · level 0

**Use:** Section grids whose seams define the visual structure.

**CSS:** `background: #000000; display: grid; gap: 1px; border-bottom: 1px solid #000000`

**Observed:** White or pale media children conceal the black backing except at the seams.

**Transfer:** Treat adjacent panels as one continuous structure, not separate raised objects.

#### Mineral product stage · level 0

**Use:** Backing for isolated product objects.

**CSS:** `background: #f0f1ef; border-radius: 0px; box-shadow: none`

**Observed:** A warm, very pale grey merges into the studio image backing; photographed shadows belong to the object, not the tile.

**Transfer:** Match the image background to the panel so the object feels placed in a continuous field.

## Components

### Fixed navigation

**Use:** Persistent site orientation above imagery and content.

**CSS:** `position: fixed; height: 40px; z-index: 1000; background: #ffffff; border-bottom: 1px solid #000000`

**Text style:** `navigation` — Nimbus Sans D OT 400 · 12px/1.4 · uppercase

**Observed:** The logo occupies the left third, a fine vertical rule starts the navigation area, and two action cells align at the far right. Current destination is bold.

**Transfer:** Keep the wordmark small in the strip so the opening poster can carry the monumental version.

### Navigation cell

**Use:** Persistent commercial and basket actions.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 140px; height: 39px; border-left: 1px solid #000000; color: #000000; border-radius: 0px`

**Text style:** `navigation-cell` — Nimbus Sans D OT 400 · 12px/1 · uppercase

**Observed:** The whole rectangle is the hit target; basket count appears in parentheses. The current trade destination uses bold text.

**States:** Declared: hover text-decoration none; focus-visible and active styling are unspecified.

### Text link

**Use:** Quiet contextual navigation within prose and media cards.

**CSS:** `color: #000000; text-decoration: underline`

**Text style:** `body` — Nimbus Sans D OT 400 · 12px/1.4

**Observed:** Short wording stays at body scale rather than growing into a button. Some card labels use a fine underline drawn beneath the text.

**States:** Declared: hover text-decoration none; focus-visible and active styling are unspecified.

### Action row

**Use:** A commercial destination inside a conversion stack.

**CSS:** `display: flex; align-items: center; padding: 40px 20px; border-bottom: 1px solid #000000`

**Text style:** `label` — Nimbus Sans D OT 700 · 12px/1.2 · tracking 0.01em · uppercase

**Observed:** A bold uppercase destination sits above a regular underlined support link with 4px title separation. An inner 20px wrapper makes the effective left inset 40px. Desktop rows are about 140px tall.

**Transfer:** Offer a small set of meaningful paths as stacked architectural rows, beside an invitation statement.

### Product tile

**Use:** A product choice in an edge-to-edge catalogue or landing-page assortment.

**CSS:** `position: relative; overflow: hidden; background: #ffffff; border-radius: 0px`

**Text style:** `label` — Nimbus Sans D OT 700 · 12px/1.2 · tracking 0.01em · uppercase

**Observed:** Square media on Mineral product stage fills the tile. A title row uses 24px vertical and 20px horizontal padding, name at left with a short dash indicator and size at right. The product image is inset 40px; the visible object is substantially smaller than its image frame.

**States:** Declared: hover text-decoration none; focus-visible and active styling are unspecified.

**Transfer:** Use consistent specimen photography and compact metadata, not a floating price badge or separate purchase button.

### Utility footer

**Use:** Compact common ending before the large refrain.

**CSS:** `padding: 20px; background: #ffffff`

**Text style:** `caption` — Nimbus Sans D OT 400 · 10px/1.4

**Observed:** A 150px ruled three-column band: small logo, description and a monochrome trust mark on the left; a spacious middle cell; four small navigation groups on the right. Group titles use utility-label, 20px column gaps and 10px link separation.

**Transfer:** Preserve the asymmetry and density; allocate the middle field deliberately without inventing a filler graphic.

### Principle refrain

**Use:** Signature closing strip across all page types.

**CSS:** `overflow: hidden; height: 80px; color: #000000; background: #ffffff`

**Text style:** `refrain` — Nimbus Sans D OT 400 · 56px/1.2

**Observed:** A flex row repeats one complete sentence without wrapping; each copy has 20px left padding and 180px right padding. The row has 8px top and 5px bottom padding, and clips at both viewport edges.

**Transfer:** Write a candid principle that benefits the reader even when it does not maximize the sale.

### Editorial media card

**Only for:** topic indexes and related-story calls

**Use:** A whole-row link to a deeper topic.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; padding: 20px; background: #ffffff; position: relative; transition: transform ease .4s`

**Text style:** `body` — Nimbus Sans D OT 400 · 12px/1.4

**Observed:** This is the text panel: one third of the desktop width beside a two-thirds image. A label with dash indicator and support line sit at its top, while an underlined link sits at the bottom. A complete row is about 521px high including its bottom rule.

**Transfer:** Use it for a substantive feature or story, not a compact feature checklist.

## Imagery and graphics

### Grainy photographic poster

**Use:** Default marketing opening and occasional full-width photographic pauses.

**Observed:** A close, low-angle view of a hand holding a white product against blue sky and cloud. Visible grain, slightly imperfect skin detail and casual gesture contrast with the engineered grid. Cover framing fills the screen; the object sits in the upper-right half and the arm runs upward from the lower middle.

**Transfer:** Photograph the new product in a human gesture under natural light with strong open negative space. If no physical object exists, use a real-world scene of its use rather than a generic dashboard collage.

### Monumental wordmark

**Use:** Signature bottom layer over opening photography.

**Observed:** White vector lettering spans about 1238px with a 195px artwork height at desktop, leaving room for a small trust mark at lower right; it sits 28px above the image bottom. The lettering is neutral, regular and nearly touches the left edge.

**Transfer:** Set the new product name as a similarly broad, simple word-shape. If a bespoke mark is unavailable, use clean regular grotesk lettering fitted to the same width rather than shrinking it into a conventional hero heading.

**Build:** Use an SVG viewBox containing an original wordmark or live text converted to paths. Fill white, preserve its aspect ratio, place 22px from the left and 28px from the bottom, and reserve 180px on the right for a small legitimate proof mark or clear negative space.

### Studio specimen and cutaway

**Use:** Signature product demonstration, statistical proof and assortment photography.

**Observed:** White cartons, silver can and pale bottle stand in luminous white or mineral-grey environments with subtle contact shadows. The extended demonstration unfolds a package into floating pale planes with a detached cap, then turns and pours the object; thin black leader lines connect it to tiny labels.

**Transfer:** Show the product whole, then reveal construction or function. Minimum acceptable substitute is one sharply lit product photograph plus a clean annotated exploded SVG; for intangible products, use a legible system diagram with the same central-object scale.

**Build:** For an explanatory diagram, arrange original product layers as pale SVG polygons in a central vertical stack, separated clearly in depth. Add black 1px horizontal leader lines to outside labels, using label and body recipes. Back with White canvas; use soft rgba(0,0,0,0.12) blurred ellipses only as object contact shadows, not panel shadows.

### Atmospheric editorial photography

**Only for:** editorial stories, topic indexes and partnership pages

**Use:** Full-bleed pauses and two-thirds-width story images.

**Observed:** Close-up water bubbles, sunlit packaging on wood, dark meadow plants, cloudy sky, sunset grasses and a person sitting in grass. Color is earthy and photographic, often grainy or softly focused. A trade image uses dark fabric and sunglasses behind the pale product.

**Transfer:** Choose textures and places relevant to the new product's real context. Keep warm light, tactile materials, imperfect framing and uninterrupted rectangular edges rather than applying a uniform brand-color wash.

### Icons

**Observed:** Very little decorative iconography. A black filled trust-mark SVG is 40px by 67px in the footer; opening photography uses a larger white reversed mark. Small dashes indicate linked product and topic titles.

**Transfer:** Use simple monochrome indicators and only relevant legitimate trust marks; do not introduce a colorful icon set.

## Section recipes

How recurring sections are built.

### First screen: Photographic poster opening

**Observed:** The first 900px are almost entirely a cover photograph under Fixed navigation. Back to front: photographic sky and cloud, a raised hand and product in the upper-right half, the huge white Monumental wordmark along the lower edge, a small reversed proof mark at lower right, and the white 40px fixed navigation strip. The wordmark spans roughly six sevenths of the width and supplies the opening headline silhouette; ordinary display text is reserved for the next chapter. There is no support paragraph or standalone hero button in this screen: the navigation cells provide actions. The next ruled product-proof chapter starts below the fold.

**Transfer:** Keep the image-led poster as the default marketing first impression and use an original wordmark-shaped name overlay. Without custom photography, stage a real product against bright natural surroundings and retain the strong bottom lettering. Catalogue and editorial pages instead open with a centered 640px text column, 80px vertical padding and a small label heading; partnership pages use partner-display on white.

**Avoid:** Do not replace this with centered headline, paragraph, two pill buttons and a small product thumbnail; do not superimpose an additional sales headline over the wordmark.

**Text style:** `display` — Nimbus Sans D OT 400 · 80px/1 · tracking -0.01em

### Split proposition and specimen

**Observed:** A viewport-scale White canvas is bisected with a 1px vertical rule. An 80px display statement sits in the left half with 67.2px side padding; the right half stages a tall white product, broadly centered with plentiful surrounding white.

**Transfer:** Pair one substantial assertion with one object or diagram. Preserve equal halves and let the statement break into several short lines.

**Text style:** `display` — Nimbus Sans D OT 400 · 80px/1 · tracking -0.01em

### Flanking quantified proof

**Observed:** The studio object moves to the center of a full-width white stage. A 300px-wide body-feature introduction sits above it; 80px centered multiline facts occupy left and right fields. A small bracketed reference attaches to the claim and a 10px report citation sits near the lower edge.

**Transfer:** Use a pair of verifiable product facts around a central specimen. Keep the citation adjacent to its claim instead of hiding it in unrelated legal text.

**Text style:** `display` — Nimbus Sans D OT 400 · 80px/1 · tracking -0.01em

### Extended claim beside demonstration

**Observed:** A 1px seam joins a media half and a white explanatory half. The latter uses explanation with 67.2px horizontal padding and a small report citation below, while the media receives the full opposite half.

**Transfer:** Use this for one longer comparative statement and its visual demonstration, retaining a compact source note where a claim requires one.

**Text style:** `explanation` — Nimbus Sans D OT 400 · 56px/1.2 · tracking -0.01em

### Invitation and destination stack

**Observed:** A ruled half-and-half band pairs invitation text with three Action rows; the statement is vertically centered. The trading variant uses two contact rows containing method labels and smaller response-time or hours text.

**Transfer:** Present alternate ways to proceed without creating a conventional CTA banner.

**Text style:** `invitation` — Nimbus Sans D OT 400 · 32px/1.2 · tracking -0.01em

### Assortment and closing refrain

**Observed:** Product tile thirds provide a dense visual destination after the long product demonstration. Utility footer follows as a compact ruled band, and Principle refrain provides the final large-scale gesture. Editorial pages can lead into the same ending from a story row; catalogue pages use a large photographic pause before it.

**Transfer:** Adapt the material before the ending to the page purpose, while preserving the abrupt contrast between tiny utility type and the huge one-line refrain.

### Editorial text band

**Only for:** catalogue introductions and long-form editorial pages

**Observed:** Full-width ruled White canvas with 80px top and bottom padding. A centered 640px column stays left aligned: label heading, 20px gap, 12px/1.4 paragraphs. Long-form chapters repeat this calm construction between very large photographs.

**Transfer:** Use compact prose for context, policy or process. Let photography supply scale instead of enlarging every section heading.

**Text style:** `label` — Nimbus Sans D OT 700 · 12px/1.2 · tracking 0.01em · uppercase

### One-third story row

**Only for:** topic indexes and related-story calls

**Observed:** Editorial media card forms the left third and a 960px by 520px photograph fills the right two thirds. The small title and support stay top-left; the link is pinned toward the lower-left, making the whole text panel spacious despite its small type.

**Transfer:** Repeat for a small set of substantial topics or use a single row as a related-content close.

## Page flow

**Storyline:** poster or compact proposition → tangible demonstration or editorial context → substantiated detail → useful next destinations → compact utility → oversized principle

### Immersive product-led marketing

1. **Emotional promise** — Full-screen human product photograph with monumental wordmark.
2. **Quantified proof** — Split declaration transitions to a central product with flanking statistics and a citation.
3. **Product demonstration** — White-stage object studies reveal construction, materials and operation, interrupted by large half-width claims.
4. **Conversion** — Invitation with destination rows and a square assortment grid.
5. **Closing principle** — Ruled utility footer followed by the repeating sentence strip.

**Transfer:** Use an object or system as the narrative anchor; vary the number of proof chapters to suit the available facts.

### Catalogue and direct product selection

1. **Context** — Compact centered text introduction with a small uppercase title.
2. **Product selection** — Three-column square specimen grid.
3. **Emotional reinforcement** — A tall, full-bleed photograph of a hand holding the product.
4. **Closing principle** — Shared utility footer and large repeating refrain.

**Transfer:** Keep the selection grid immediate and leave the immersive storytelling to the imagery.

### Trade and partnership conversion

1. **Proposition** — Centered 96px regular statement on white; square product images pass in front of it.
2. **Invitation** — A centered 32px line in a ruled band.
3. **Emotional reinforcement** — Large tactile product photograph.
4. **Contact** — Half-width statement beside two contact-method rows.
5. **Closing principle** — Shared footer and repeating refrain.

**Transfer:** Use one clear partner proposition and direct contact methods rather than a lead-generation form by default.

### Topic index and credibility navigation

1. **Context** — Small heading and several compact paragraphs in the centered editorial column.
2. **Topic exploration** — Four one-third/two-thirds photographic story rows with bottom-aligned links.
3. **Closing principle** — Final story row meets the shared utility footer and refrain directly.

**Transfer:** Let topics vary while keeping equal-weight full-width rows rather than a rounded card mosaic.

### Long-form commitments and accountability

1. **Commitment** — Small uppercase declaration with compact paragraphs.
2. **Emotional context** — Full-width sunset grasses photograph.
3. **Substantiation** — Narrow prose chapters with small headings, detailed explanations and ruled boundaries.
4. **Concrete examples** — Project descriptions alternate with large documentary imagery and a small embedded illustration.
5. **Related destination** — One-third/two-thirds story row closes the editorial content.
6. **Closing principle** — Shared utility footer and repeating refrain.

**Transfer:** Use specific actions, named processes and supporting detail appropriate to the new organization; keep the long-form typography intentionally modest.

## Writing

Candid, matter-of-fact and quietly challenging. It mixes plain product language with serious substantiation, and is willing to recommend a simpler alternative to buying.

**Do not copy:** Do not reuse Postevand names, logo artwork, package designs, certification marks, report claims, environmental percentages, donation pledges, contacts or slogans as facts about a new brand. Source quotations below illustrate cadence only.

- **Addressing the reader:** Use we for the maker's actions and you for the reader's choices; speak directly without pretending intimacy.
- **Rhythm:** Short declarative sentence pairs for big headings, small functional labels for navigation, and longer explanatory paragraphs for substantiation. Few rhetorical flourishes and no exclamation-driven selling.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Major statement | A concrete benefit followed by a terse qualification or consequence. | 5–12 words | “Refreshing, local water. Minimum climate impact.” |
| Proof heading | Name the study category, then state its conclusion after a colon. | 5–9 words | “Lifecycle study results: Proven better” |
| Invitation | Two compact imperatives that link action to participation. | 6–10 words | “Start the future. Join our mission” |
| Navigation and action | Literal destination or simple action, without promotional adjectives. | 1–4 words | “Become a reseller”<br>“Read more” |
| Closing principle | A conditional opening followed by a direct recommendation. | 8–14 words | “If you have the option, always drink tap water.” |
| Practical reassurance | State what the organization will do and when. | 10–18 words | “We’ll do our best to get back to you within 24 hours” |

**Words and phrasing to use:** less; lower; local; materials; lifecycle; get in touch; we believe; concrete action; transparency

**Avoid:** revolutionary; game-changing; unlock your potential; planet-saving miracle; ultimate luxury; hurry now

**Rules:**

- Write claims with a clear comparison and a qualification when needed.
- Let the small label name a subject; do not force a sales headline into every editorial section.
- A final principle should sound useful even to someone who chooses not to buy.
- Keep commercial routes literal and easy to distinguish.

## Do's and Don'ts

### Do

- Keep display text at weight 400 and -0.01em tracking.
- Use 1px black seams to join adjacent panels into a continuous grid.
- Keep standard text insets at 20px and large half-panel headline insets at 67.2px on desktop.
- Stage products on #ffffff or #f0f1ef with photographic contact shadows.
- Reserve bold uppercase 12px labels for compact titles and metadata.
- Keep the 40px fixed navigation distinct from the photographic opening.
- Use 640px centered columns with left-aligned 12px prose for editorial content.
- End with the compact utility band and 56px single-line principle refrain.

### Don't

- Do not use colored buttons to compensate for the intentionally monochrome interface.
- Do not round square product tiles or add card-elevation shadows.
- Do not give every small section label an 80px headline treatment.
- Do not widen the 12px editorial paragraphs into full-viewport lines.
- Do not turn the 39px navigation cells into tall padded pills.
- Do not recolor natural photography into a uniform grey filter; its color is the emotional counterweight to the grid.
- Do not fill product stages with decorative patterns or floating geometric confetti.
- Do not convert the large closing sentence into a multi-line centered CTA block.

## Motion and responsive

### Motion

**Observed:**

- Product storytelling uses pinned, scroll-progressed scenes: central object views, exploded construction, enlarged pouring detail and reassembly into an assortment package.
- Trade imagery moves in front of a centered statement during scrolling.
- Editorial media panels declare transform ease .4s; a surface also declares opacity .4s ease.
- The closing sentence is repeated in a horizontally translated, clipped row.

**Transfer:**

- Tie a product's construction or operation to the scroll sequence rather than adding unrelated floating animation.
- Retain readable static product states and a fully visible sentence when motion is reduced.

**Unknown:**

- Exact scroll durations, progress mapping and refrain speed are not specified.
- No complete focus-visible or active treatment is established.

### Responsive

**Observed:**

- Declared width breakpoints include 374px, 375px, 575px, 767px, 768px, 1023px, 1024px, 1440px and 2048px.
- Product grid classes distinguish half-width narrow-screen tiles from third-width larger-screen tiles; some header actions have narrow-screen visibility changes.
- Display and explanation use viewport-relative type, and large half-panel padding uses 4.66667vw.

**Transfer:**

- Preserve square product images and fine seams when the assortment becomes two columns.
- Fit the monumental name to the available image width rather than keeping a desktop-sized wordmark.
- As a narrow-screen adaptation, stack explanatory media and text while retaining their shared boundary; keep the footer refrain single-line and clipped.

**Unknown:**

- Exact mobile navigation composition, small-screen font sizes and footer stacking have not been established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
