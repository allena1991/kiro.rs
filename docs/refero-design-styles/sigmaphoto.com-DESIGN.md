# Sigma — instruments meet image-making

## Overview

An image-led editorial style that treats engineered objects with the seriousness of art. White and near-white pages, charcoal lettering and restrained serif typography make room for monumental product details, atmospheric landscapes and occasional intensely colored photographic artwork. Small grotesk utilities and spare commerce grids balance the cinematic scale; it suits crafted tools, specialist equipment and design-led products.

### Essentials

- The object speaks before the headline: a full-width, 900px-high photographic stage sits behind a 48px announcement and 48px navigation; the editorial headline arrives below the first screen. Use a tightly framed material study when a finished product photograph is unavailable.
- Headlines behave like printed exhibition titles: regular-weight Sigma Serif head at 88px/83.8px with -3px tracking and uppercase, centered above a 500px-wide explanation; recurring section labels deliberately shrink to 16px/17.6px.
- Actions remain typographic, not ornamental: 13px/16.3px uppercase sans links carry discovery; the filled form action is a square charcoal rectangle, 400px wide and 40px high.
- Color belongs to the image, not the interface: nearly all structural space is white or #fefefd with #333333 text. A saturated editorial photograph can fill an entire 1440×810px band without turning its colors into UI accents.
- Images alternate between overwhelming proximity and specimen-like isolation: edge-cut macro photography contrasts with small, centered cutout objects on expansive white fields, arranged in three columns with 16px gutters.
- A seal-like closing mark gives the page a final visual punctuation: center an 80×80px emblem above four understated utility columns, separated by 120px of breathing room. Use the new identity's own simple emblem or a thin outlined monogram.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#333333` | `--color-ink` | text, background, action | Main text, announcement background and filled form action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft charcoal | `#707070` | `--color-muted` | text, border | Muted utility headings and form outlines; 70% charcoal over the near-white canvas. |
| Near-white canvas | `#fefefd` | `--color-canvas` | background, surface | Root page and navigation backing; the default canvas outside white editorial bands. |
| White | `#ffffff` | `--color-white` | background, text, surface | Main editorial sections, footer, input fill and reversed text on photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product listing grids | Faint charcoal rule | `#eaeae9` | `--color-rule` | border | Visible result of 10% charcoal over the near-white canvas in the catalog matrix. |
| illustrated newsletter closings | Drawing paper | `#faf7ef` | `--color-cream` | surface | Warm illustrated newsletter panel, not a general card fill. |

## Typography

- **Sigma Serif head** — Monumental editorial titles. High-contrast, sharp serif capitals with a sculptural, tightly fitted silhouette. If unavailable, use **Bodoni Moda**. 400; tune line breaks to preserve broad title silhouettes. Font stack: "Sigma Serif head", "Bodoni Moda", "Noto Sans JP", sans-serif.
- **Sigma Serif** — Body copy, prices, product names and section labels. Regular editorial serif; used small and compact rather than in a bold heading ladder. If unavailable, use **Libre Caslon Text**. 400; preserve narrow text columns. Font stack: "Sigma Serif", "Libre Caslon Text", "Noto Sans JP", sans-serif.
- **Sigma Sans** — Navigation, utilities, links and forms. Plain regular grotesk, compact and utilitarian beside the serif voice. If unavailable, use **Arimo**. 400; retain compact utility sizing and near-neutral tracking. Font stack: "Sigma Sans", "Arimo", "Noto Sans JP", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Sigma Serif head | 400 | 88px | 83.8px | -0.0341em, uppercase | Primary centered editorial statement, including the statement following the photographic opening. |
| image-display | Sigma Serif head | 400 | 88px | 1.1 | 0.0009em, uppercase | Centered white title across a full-width editorial photograph. |
| film-title | Sigma Serif | 400 | 24px | 1.25 | 0.0033em, uppercase | Short centered titles over paired moving-image panels. |
| tile-title | Sigma Serif | 400 | 21px | 1.1 | 0.004em | Centered product title over dark photographic tiles. |
| body | Sigma Serif | 400 | 16px | 1.25 | 0.005em | Paragraphs, descriptions, product names and prices. |
| section-label | Sigma Serif | 400 | 16px | 1.1 | 0.005em, uppercase | Small centered section leads and left-aligned story captions. |
| action | Sigma Sans | 400 | 13px | 1.25 | 0.006em, uppercase | Discovery links, footer links and small merchandise flags. |
| utility | Sigma Sans | 400 | 13px | 1.25 | 0.006em | Navigation and form labels. |
| footer-heading | Sigma Sans | 400 | 13px | 1.1 | 0.006em, uppercase | Muted column titles above utility links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| people directories | directory-title | Sigma Serif head | 400 | 48px | 0.95 | -0.0275em, uppercase | Centered title above a portrait directory. |
| people directories | portrait-caption | Sigma Serif | 400 | 16px | 1.25 | 0em, uppercase | Names beneath portrait images. |
| product listing pages | catalog-title | Sigma Sans | 400 | 13px | 0.95 | normal, uppercase | Tiny left-hand heading sharing a toolbar with filtering and comparison. |

**Notes:**

- Keep all primary text at weight 400; scale, type family, reversal and whitespace do the hierarchy work.
- The large dark title is tightly tracked; the large reversed photographic title returns to nearly neutral tracking. Do not apply one tracking rule indiscriminately.
- The opening image has no overlaid promotional headline. The display recipe belongs to the next editorial statement.
- Use uppercase for labels and actions, but retain technical mixed-case specifications within product names.

## Layout

**Density:** Airy image-led chapters with compact text internals: large pauses separate small labels, narrow copy and substantial media.

### Spacing

**Spacing system:**

- **horizontal step** 16px, horizontal — Page edges, gutters and catalog item insets.

| Value | Use |
| --- | --- |
| 16px | Paragraph separation, image-to-caption gap and column gutter. |
| 20px | Footer heading-to-links separation and some action offsets. |
| 24px | Headline-to-body gap and form group spacing. |
| 32px | Editorial subheading-to-body gap and footer bottom inset. |
| 72px | Announcement sentence-to-action gap. |
| 80px | Chapter top and bottom padding; small section lead-to-grid pause; portrait grid row gap. |
| 120px | Footer columns separated from emblem and copyright. |
| 160px | Editorial page title top offset and major title-to-content pauses. |

### Containers and grids

- **edge container**: side padding 16px. Full-window content with narrow side margins; 1408px of usable width at a 1440px viewport.
- **intro column**: max width 500px. Centered, often center-aligned explanatory text below the large product statement.
- **editorial column**: max width 560px. Centered narrow article blocks with left-aligned paragraphs and centered small headings.
- **paired media**: 2 columns · gap 16px. Equal 696px-wide photographic panels at desktop, each 810px tall.
- **story grid**: 3 columns · gap 16px. Equal image-first stories or product categories, 459px wide at desktop.
- **footer grid**: 4 columns · gap 16px. Equal utility columns across the edge container.
- **directory grid** (only for people directories): 4 columns · gap 16px. 340px-wide portrait cards with an 80px row gap.
- **catalog matrix** (only for product listing pages): 3 columns · gap 0px. Full-bleed bordered 480px-wide cells, including an incomplete final row.

## Corner radius

| Element | Radius |
| --- | --- |
| media and actions | 0px |
| email input | 1px |

## Surfaces and depth

### Surfaces

#### Near-white canvas · level 0

**Use:** Root and navigation background.

**CSS:** `background: #fefefd; color: #333333`

#### White editorial sheet · level 0

**Use:** Main marketing chapters and footer.

**CSS:** `background: #ffffff; box-shadow: none`

**Observed:** Flat sections meet without elevated card boundaries; the white content sheet follows the opening photographic stage.

**Transfer:** Separate chapters through space and image scale rather than changes of panel chrome.

#### Charcoal strip · level 1

**Use:** Thin announcement strip.

**CSS:** `background: #333333; color: #ffffff`

#### Drawing paper panel · level 0

**Only for:** illustrated newsletter closings

**Use:** Illustrated newsletter backing.

**CSS:** `background: #faf7ef`

**Observed:** A flat warm rectangle occupies about two thirds of the closing row.

#### Ruled catalog cell · level 0

**Only for:** product listing pages

**Use:** Adjacent product listing cells.

**CSS:** `background: #fefefd; border-top: 1px solid rgba(51, 51, 51, 0.1); border-bottom: 1px solid rgba(51, 51, 51, 0.1); border-left: 1px solid rgba(51, 51, 51, 0.1); border-radius: 0px`

**Observed:** Shared fine rules make a continuous matrix rather than separate floating cards.

## Components

### Navigation bar

**Use:** Persistent identity and site navigation.

**CSS:** `background: #fefefd; height: 48px; color: #333333`

**Text style:** `utility` — Sigma Sans 400 · 13px/1.25 · tracking 0.006em

**Observed:** A small centered wordmark is flanked by the primary menu on the left and login, search and cart on the right. Links use 16px vertical padding and 16px gaps. The announcement scrolls away while navigation remains at the top.

**States:** Declared: hover link color rgba(51, 51, 51, 0.8), text-decoration none; focus-visible unknown; active link color #333333.

### Announcement bar

**Use:** Short timely message above navigation.

**CSS:** `background: #333333; color: #ffffff; display: flex; justify-content: center; align-items: center; gap: 72px; padding: 14px 16px; height: 48px; box-sizing: border-box`

**Text style:** `body` — Sigma Serif 400 · 16px/1.25 · tracking 0.005em

**Observed:** One uppercase serif sentence and a smaller sans action share the centered strip.

### Discovery link

**Use:** Default marketing action without a filled button.

**CSS:** `color: #333333; background: none; font-size: 13px; text-transform: uppercase`

**Text style:** `action` — Sigma Sans 400 · 13px/1.25 · tracking 0.006em · uppercase

**Observed:** Text-only actions follow captions or compact support copy. White variants sit directly on dark photographs; the announcement action is underlined.

**States:** Declared: hover color rgba(51, 51, 51, 0.8), text-decoration none; focus-visible unknown; active color #333333. White photographic variant: hover opacity 0.7 with white text.

### Photographic tile

**Use:** Paired product introductions.

**CSS:** `height: 810px; background-size: cover; background-position: 50% 50%; border-radius: 0px; overflow: hidden`

**Text style:** `tile-title` — Sigma Serif 400 · 21px/1.1 · tracking 0.004em

**Observed:** Two tall panels place a compact title and Discovery link over the center of a dim, tightly framed product photograph. Text overlay has 30px inner padding.

**Transfer:** Let the product fill most of each panel; choose exposure and framing that keep the central type legible.

### Story card

**Use:** Image-led editorial proof and category introductions.

**CSS:** `display: flex; flex-direction: column; color: #333333; border-radius: 0px`

**Text style:** `section-label` — Sigma Serif 400 · 16px/1.1 · tracking 0.005em · uppercase

**Observed:** Image first, caption 16px below. Editorial images are 459×573px; category images are square, followed by a short body paragraph and Discovery link. No surrounding box or shadow.

### Email input

**Use:** Newsletter address entry.

**CSS:** `background: #ffffff; border: 1px solid rgba(51, 51, 51, 0.7); border-radius: 1px; width: 400px; height: 40px; padding: 7px 11px; box-sizing: border-box`

**Text style:** `utility` — Sigma Sans 400 · 13px/1.25 · tracking 0.006em

**Observed:** Visible label sits above the outline; a separate consent checkbox follows below.

### Subscribe button

**Use:** Newsletter form submission.

**CSS:** `background: #333333; color: #ffffff; width: 400px; height: 40px; padding: 11px 15px; border-radius: 0px; letter-spacing: 0.3px; text-transform: uppercase`

**Text style:** `utility` — Sigma Sans 400 · 13px/1.25 · tracking 0.006em

**Observed:** A full-form-width rectangle follows consent. Its label has wider tracking than navigation.

**States:** Declared: hover background rgba(51, 51, 51, 0.9), border 0px, color #ffffff; focus-visible unknown; active matches hover.

### Footer columns

**Use:** Final navigation after the emblem.

**CSS:** `display: flex; column-gap: 16px; row-gap: 24px; color: #333333`

**Text style:** `action` — Sigma Sans 400 · 13px/1.25 · tracking 0.006em · uppercase

**Observed:** Four equal columns use muted Footer-heading labels, 20px before tightly stacked uppercase links. Social destinations remain words rather than icon buttons. Copyright sits separately at lower left.

### Catalog product cell

**Only for:** product listing pages

**Use:** Repeated product and price presentation.

**CSS:** `padding: 16px; border-top: 1px solid rgba(51, 51, 51, 0.1); border-bottom: 1px solid rgba(51, 51, 51, 0.1); border-left: 1px solid rgba(51, 51, 51, 0.1); margin-top: -1px; position: relative`

**Text style:** `body` — Sigma Serif 400 · 16px/1.25 · tracking 0.005em

**Observed:** Square image region above a two-line product name and price. The isolated object is much smaller than its 447px image field; a small NEW flag can sit at the upper edge. Cells meet without gutters.

### Portrait card

**Only for:** people directories

**Use:** Human proof in a repeated directory.

**CSS:** `display: block; color: #333333`

**Text style:** `portrait-caption` — Sigma Serif 400 · 16px/1.25 · tracking 0em · uppercase

**Observed:** 340×425px vertical image, followed by an uppercase name 16px below; no biography, action button or ornamental frame.

## Imagery and graphics

### Monumental product detail

**Use:** Primary marketing opening.

**Observed:** An almost monochrome close-up of black equipment against a pale cool-gray field fills the viewport. Knurling, optical reflections and engraved controls remain tactile; the object extends beyond the image edges. The composition has no decorative frame or headline overlay.

**Transfer:** Photograph the new product's most recognizable material junction at extreme scale with directional soft light and deep blacks. Without a full product shoot, use a genuine macro material photograph or a simple physically lit model; avoid substituting a generic UI collage.

### Isolated specimen

**Use:** Merchandise and category grids.

**Observed:** Dark objects are centered at modest scale on a white field with generous space on every side. The imagery itself supplies delicate shading; there is no added card shadow.

**Transfer:** Use clean cutouts or neutral studio renders at consistent visual scale and angle. Keep the canvas larger than the object, even for compact products.

### Editorial color interruption

**Use:** Full-width art-led feature between white chapters.

**Observed:** An intensely blue leaf lies across a deep crimson photographic field. White display lettering, a narrow paragraph and a small action occupy its center. The image fills a 1440×810px band; its colors do not recur as interface accents.

**Transfer:** Create one similarly bold photographic still life around a material or outcome relevant to the new product. Use a single subject, a saturated contrasting ground and generous unoccupied area for type, rather than a multicolor UI gradient.

### Process and place

**Use:** Film panels and editorial chapters.

**Observed:** Machining, polished glass and handwork are paired with dawn fields and misty mountains. Cool blue-green workshop light contrasts with natural amber or blue landscape light. Media alternates full-width, paired and a centered 704px-wide image.

**Transfer:** Pair tactile process details with an honest environmental view. Let atmosphere and real light supply color instead of applying a uniform brand tint.

### Closing emblem

**Use:** Visual punctuation before final navigation.

**Observed:** An 80px circular outlined mark is centered alone in a spacious white area.

**Transfer:** Use the new identity's own emblem, keeping the same isolated scale and placement.

**Build:** Set an 80×80px SVG with a thin #333333 circular outline and a simple centered monogram or geometric symbol. Use no badge background, glow or shadow.

### Portrait directory

**Only for:** people directories

**Use:** Repeated human proof.

**Observed:** Vertical 4:5 head-and-shoulders photographs combine natural and studio light, varied backgrounds and restrained natural color; consistent framing holds the grid together.

**Transfer:** Normalize face scale and aspect ratio while preserving each person's setting.

### Playful ink drawing

**Only for:** illustrated newsletter closings

**Use:** Warm counterpoint to technical photography.

**Observed:** Loose black line art on cream depicts playful envelope-like figures with a few wind strokes and tiny floating details. The drawing occupies a broad panel beside a narrow form.

**Transfer:** Commission or draw an original small narrative about communication or the new product, keeping the ink sparse and hand-made.

**Build:** Use an SVG on #faf7ef with #333333 unfilled paths, approximately 2–4px irregular strokes, round caps and two unequal simple figures. Limit solid fills to small facial details, leave most of the panel empty, and add a handful of gently diagonal open paths for movement.

### Abstract material loops

**Only for:** company-story openings

**Use:** Large symbolic image beneath a company title.

**Observed:** Fine dark elliptical ribbons overlap on white, some edges fading into pale gray. The artwork is wide and airy, not a dense diagram or a literal product render.

**Transfer:** Use a sparse abstract arrangement derived from the new product's material or geometry.

**Build:** Create an SVG with 4–6 overlapping elliptical paths centered in a wide white viewBox. Vary rotation and ellipse proportions; use #333333 at several alpha levels with 1–3px strokes and a few tapered filled arcs. Keep the center largely white.

### Icons

**Observed:** The visual language is primarily typographic: utilities and social links are words, and the closing circular emblem is the main isolated symbol.

**Transfer:** Prefer short text utilities over a row of generic icons; reserve emblematic geometry for the closing signature.

## Section recipes

How recurring sections are built.

### First screen: Photographic stage opening

**Observed:** Back to front: a fixed full-window photographic stage, then the near-white Navigation bar and the Charcoal strip Announcement bar. At 1440px wide, the stage is 900px tall; the two 48px bars occupy the top 96px and the macro object fills everything beneath. The object is dramatically enlarged, cut off by the left, right and lower edges against a pale cool field. The entire image is a link. Within the first 900px there is no promotional headline, support paragraph or separate CTA cluster; only announcement copy, its action, navigation and the product scene. The White editorial sheet starts below the opening, with the 88px Display statement and body copy later in the scroll.

**Transfer:** Retain the media-first opening for a new marketing page: use a real detail photograph or restrained material render with a recognizable silhouette. Keep the large editorial statement below the image rather than forcing it over the subject. Company-story and initiative variants instead open with a centered Display title after 160px of space; people directories use Directory-title, and commerce uses a small Catalog-title toolbar.

**Avoid:** Do not turn this into a conventional split hero with a left headline, pill CTA and small object on the right, or invent a headline over the initial product image.

**Text style:** `display` — Sigma Serif head 400 · 88px/83.8px · tracking -0.0341em · uppercase

### Editorial statement

**Observed:** A centered Display title spans most of the content width, with 24px before a 500px Body column. Paragraphs are separated by 16px and a Discovery link follows. The section has 80px top and bottom padding.

**Transfer:** Distill the product promise into a few substantial words, then explain it with a compact, specific paragraph rather than adding a second medium heading.

**Text style:** `display` — Sigma Serif head 400 · 88px/83.8px · tracking -0.0341em · uppercase

### Labeled paired panels

**Observed:** Section-label is centered, followed by an 80px pause and two Photographic tiles in the Paired media layout. The section has 80px padding above and below. Film variants use Film-title over the center of each moving image.

**Transfer:** Pair two distinct capabilities or applications, maintaining equal photographic weight rather than a dominant card and a smaller secondary tile.

**Text style:** `section-label` — Sigma Serif 400 · 16px/1.1 · tracking 0.005em · uppercase

### Three-column proof gallery

**Observed:** A centered Section-label leads a Story grid by 80px. Story cards use portrait imagery and short uppercase captions; category variants use square isolated specimens, paragraphs and Discovery links.

**Transfer:** Show outcomes, applications or product families with consistent image ratios. Let differences in subject matter create variety without changing card construction.

**Text style:** `section-label` — Sigma Serif 400 · 16px/1.1 · tracking 0.005em · uppercase

### Full-width editorial feature

**Observed:** A 1440×810px image centers Image-display, a narrow Body paragraph and a small Discovery link. White space of 80px surrounds the band, separating its saturated photographic color from the neutral page.

**Transfer:** Give a notable collaboration, outcome or conceptual story a cinematic single-image chapter.

**Text style:** `image-display` — Sigma Serif head 400 · 88px/1.1 · tracking 0.0009em · uppercase

### Exploration and seal ending

**Observed:** The ending resolves to a White editorial sheet with the Closing emblem centered above Footer columns. The emblem is 80px wide; columns begin 120px below its bottom, with another 120px before the lower copyright area and 32px bottom padding. Story variants can introduce two right-aligned portrait media links with a small exploration label at left before this shared footer.

**Transfer:** Always provide the isolated emblem as final visual punctuation, then a low-density utility directory rather than an oversized closing sales slogan.

**Text style:** `footer-heading` — Sigma Sans 400 · 13px/1.1 · tracking 0.006em · uppercase

### Narrow long-form chapter

**Only for:** company and initiative stories

**Observed:** A 560px Editorial column alternates left-aligned Body paragraphs with small centered uppercase headings. Wide landscape or process imagery interrupts the narrow text. Major blocks use 80px padding, often producing 160px between chapters.

**Transfer:** Explain rationale and process through short, distinct chapters. For a dated plan, end with an unboxed two-column sequence of dates and descriptions rather than a decorative progress chart.

**Text style:** `body` — Sigma Serif 400 · 16px/1.25 · tracking 0.005em

### Directory opening and grid

**Only for:** people directories

**Observed:** Directory-title appears centered with 160px spacing above and below. A tiny left-aligned member count precedes a four-column Directory grid; Portrait cards repeat with 80px between rows. The last incomplete row remains left-aligned.

**Transfer:** Use for expert, contributor or partner lists; keep the count subordinate and omit marketing card chrome.

**Text style:** `directory-title` — Sigma Serif head 400 · 48px/0.95 · tracking -0.0275em · uppercase

### Catalog opening and matrix

**Only for:** product listing pages

**Observed:** After 160px of top space, Catalog-title sits left with filter and compare utilities right. A Ruled catalog cell matrix follows, three columns without gutters; prices sit directly beneath names. The incomplete final row retains its normal cell widths.

**Transfer:** Use the small heading and repetitive specimen staging when comparison and selection matter more than narrative spectacle.

**Text style:** `catalog-title` — Sigma Sans 400 · 13px/0.95 · uppercase

### Illustrated newsletter closing

**Only for:** newsletter-enabled marketing pages

**Observed:** An 80px-padded row gives roughly one third of the width to a 400px form and two thirds to a 932×630px Drawing paper panel. The form combines a short serif invitation, label, Email input, consent, Subscribe button and brief legal support.

**Transfer:** Create a human, informal sign-off beside the functional conversion area, using an original Playful ink drawing instead of another product photograph.

**Text style:** `body` — Sigma Serif 400 · 16px/1.25 · tracking 0.005em

## Page flow

**Storyline:** Immersion or title → explanation → visual demonstration → focused proof or selection → understated exploration or signup → emblem and utility navigation.

### Broad marketing landing page

1. **Immersion** — Full-screen macro product stage with thin navigation.
2. **Promise** — Large centered editorial statement and narrow support column.
3. **Selection and proof** — Paired introductions, isolated merchandise and three-column editorial outcomes.
4. **Emotional depth** — Saturated full-width feature and paired process films.
5. **Closing conversion** — Category exploration, illustrated newsletter row, then emblem and four utility columns.

**Transfer:** Mix product and editorial scales to make a new tool feel both engineered and culturally meaningful; adapt the number and order of chapters.

### People or expert directory

1. **Orientation** — Smaller centered serif title and tiny item count.
2. **Human proof** — Four-column portrait grid with uppercase names and generous row gaps.
3. **Resolution** — Left-aligned final partial row followed directly by emblem and utility navigation.

**Transfer:** Use repeated framing and minimal captions to make the people themselves the proof.

### Purpose-led initiative story

1. **Statement** — Large title, substantial whitespace and a narrow introduction.
2. **Context** — Wide atmospheric landscape.
3. **Rationale** — Small centered headings with left-aligned explanations in a narrow column.
4. **Concrete plan** — A compact date-and-description roadmap, then the shared emblem footer.

**Transfer:** Move from an accessible explanation to grounded process and dated next steps without adding promotional cards.

### Comparison-focused product collection

1. **Orientation** — Tiny collection title with filter and compare controls.
2. **Selection** — Three-column ruled matrix of isolated product specimens, names and prices.
3. **Resolution** — The final partial row ends without a large CTA, followed by the shared emblem footer.

**Transfer:** Keep catalog typography small and repetitive so visual differences between products remain legible.

### Long-form company or craft story

1. **Identity** — Centered large title, short motto and airy abstract material image.
2. **Credibility** — Narrow factual paragraphs alternating with process and place imagery.
3. **Philosophy** — A smaller centered material image, compact declarative heading and explanatory text.
4. **Deeper exploration** — Broad factory film followed by two portrait media links on the right; shared emblem and utilities end the page.

**Transfer:** Balance factual narrative and atmospheric visual pauses, then offer deeper reading rather than an aggressive conversion panel.

## Writing

Measured, thoughtful and materially specific. Technical facts and human creativity sit together without hype; confidence comes from describing design intent, process and place.

**Do not copy:** Do not reuse Sigma names, logos, product designations, artist names, proprietary imagery, slogans, superlative claims, prices or dated promotional offers. Source examples illustrate tone only; create truthful equivalents for the new product.

- **Addressing the reader:** Use we and our for makers and their commitments; describe products directly in the third person. Address the reader sparingly through practical possibilities rather than repeated commands.
- **Rhythm:** Headlines are often short noun phrases or a compact sequence of qualities. Supporting paragraphs use complete, moderately long sentences; actions stay at one or two words. Capitalization supplies emphasis without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Editorial promise | Three concrete qualities, separated by commas. | 3–5 words | “SMALL, POWERFUL, ADAPTABLE” |
| Support | Explain how physical design affects the user's creative experience. | 2–4 sentences | “Even in the digital age, taking a photograph is a deeply physical process.” |
| Section lead | A factual noun phrase, not a benefit slogan. | 2–4 words | “NEW PRODUCTS”<br>“our community” |
| Action | Plain verb plus minimal destination cue. | 1–2 words | “EXPLORE MORE”<br>“READ MORE”<br>“Subscribe” |
| Editorial chapter | Link craft to a wider context through direct declarative phrasing. | 4–10 words | “CRAFTSMANSHIP ROOTED IN THE LOCAL COMMUNITY AND NATURE” |

**Words and phrasing to use:** designed; engineered; craftsmanship; creativity; process; vision; physical; community; quality

**Avoid:** game-changing; disruptive; unlock your potential; 10x; magic; ultimate solution

**Rules:**

- Support benefits with physical or operational detail.
- Use model and specification strings only where selection requires them; keep narrative headings conceptual.
- Qualify measurable superlatives and distinguish an intention from an achieved result.
- Let a small factual caption do the work beneath an expressive image.

## Do's and Don'ts

### Do

- Set the main editorial title at 88px, weight 400, with -3px tracking and centered alignment.
- Use 16px page edges and column gutters to let media dominate the width.
- Keep explanatory copy within 500px and longer editorial chapters within 560px.
- Preserve 80px chapter padding and the substantial pause between small section labels and image grids.
- Use charcoal text and white structure; let photographic subjects supply chromatic intensity.
- Make discovery actions small uppercase sans text rather than filled marketing buttons.
- Keep objects modestly scaled inside isolated commerce imagery, even when the image region is 447px square.
- End with an isolated 80px emblem and four compact utility columns.

### Don't

- Do not make the body sans-serif throughout; the 16px serif voice is central to the editorial character.
- Do not bold every heading; the hierarchy uses regular weight across both small and monumental roles.
- Do not round photographic tiles or catalog cards into soft app panels; media corners are square.
- Do not add drop shadows to separate cards; the site uses whitespace and faint 1px catalog rules.
- Do not derive recurring UI accent buttons from a saturated editorial photograph.
- Do not turn the 40px-high subscription action into a pill or apply that filled style to every discovery link.
- Do not center an incomplete catalog or portrait row; keep the grid aligned to its original columns.
- Do not enlarge the catalog collection title to 88px; the commerce variant deliberately uses a 13px toolbar heading.

## Motion and responsive

### Motion

**Observed:**

- The opening photographic stage is fixed while the white content sheet advances over it; navigation remains visible in later scroll positions.
- Declared transitions include 0.2s linear with 0.1s delay and transform 0.3s / opacity 0.3s on some elements.
- Photographic panels include video; exact playback sequencing is unspecified.

**Transfer:**

- Preserve the contrast between a stationary immersive opening and the advancing editorial sheet.
- Keep text-link responses subtle; use the documented color and opacity states rather than motion-heavy button transformations.

**Unknown:**

- Element-specific entrance choreography, video looping behavior and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop layouts use two-column feature panels, three-column story and catalog grids, and four-column directory and footer grids.
- Styles include breakpoints at 480px, 768px, 1024px and 1440px among many others; no single mobile composition is established.

**Transfer:**

- On narrower screens, preserve the media-first emphasis and narrow reading measure; reduce column counts before shrinking captions below their 13px utility or 16px body roles.
- Keep the product's defining detail visible when reframing the opening image; keep the emblem isolated even when footer columns stack.

**Unknown:**

- Exact narrow-screen font sizes, header replacement, image swaps and grid breakpoints are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
