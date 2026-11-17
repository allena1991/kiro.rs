# re grocery — refillable editorial play

## Overview

A sun-warmed, tactile retail style that pairs narrow bookish serifs with matter-of-fact grotesk text. Cream and vermilion give the interface a printed-shop character, while still-life photography, hands at work and playful cutout objects add warmth. It suits physical products and approachable service brands, balancing sparse editorial chapters with information-rich shopping grids.

### Essentials

- Identity becomes the opening headline: a full-bleed 1440×900px photographic stage carries an oversized cream wordmark across the lower half, with only a 74px navigation and compact action above it.
- Bookish display meets utilitarian detail: regular narrow Garamond headings at 80px/0.8 and 100px/0.8 sit beside regular Suisse Int'l body text at 20px/1.25 with -0.4px tracking.
- Vermilion behaves like printing ink: #f74c25 supplies text, 1px outlines and actions across a predominantly #f7f6f2 canvas; the closing panel reverses to a full vermilion field with cream text.
- Geometry is oversized and hairline-light: 62px outlined pill actions accompany editorial copy, while a pair of 480px square and circular action targets turns conversion into a graphic composition.
- Pictures alternate between intimacy and inventory: tall 600px-wide pill-masked documentary photos balance centered text, while isolated objects sit small on flat #efede7 rectangular fields.
- Language becomes decoration: include an edge-clipped 180px/0.8 word ribbon and a centered 100px/0.8 serif link sculpture threaded with photographic cutouts; use product details or material fragments when whole objects are unavailable.
- The ending is a destination, not a thin legal strip: a 900px vermilion panel pairs a 266×130px identity mark with a 30px mission paragraph, a 40px serif invitation and three compact link columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion ink | `#f74c25` | `--color-ink` | text, background, border, action, link | Default lettering, outlines and action color; full-field closing panel. Continuous full-page use belongs to the institutional variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm stone | `#efede7` | `--color-product-field` | surface | Flat backing behind isolated product photography; slightly darker than the cream page, without an outline. |
| Warm cream | `#f7f6f2` | `--color-canvas` | background, text, surface, border | Primary canvas and reversed lettering on vermilion. Also the solid compact action fill over photography. |

## Typography

- **Suisse Int'l** — Navigation, body copy, product information, actions and monumental sans lettering. Neutral neo-grotesk with open everyday readability, generally regular rather than bold. If unavailable, use **Inter**. Use 400 for most text and 700 only for help questions; preserve negative tracking. Font stack: "Suisse Int'l", "Inter", -apple-system, system-ui, "Helvetica Neue", Helvetica, sans-serif.
- **ITC Garamond W01 Book Narrow** — Editorial headings, category sculpture and closing invitation. Narrow oldstyle serif with high contrast, long ascenders and a warm book face rather than a fashion Didone. If unavailable, use **EB Garamond**. Use 400; tune width and line breaks to retain the narrow silhouette. Font stack: "ITC Garamond W01 Book Narrow", "EB Garamond", Garamond, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| word-ribbon | Suisse Int'l | 400 | 180px | 0.8 | -0.03305em | Single-line edge-clipped verbal ribbon. |
| category-display | ITC Garamond W01 Book Narrow | 400 | 100px | 0.8 | -0.02175em | Stacked link sculpture; each short label forms a separate centered line. |
| feature-heading | ITC Garamond W01 Book Narrow | 400 | 80px | 0.8 | -0.02175em | Centered editorial feature titles and collection selector labels. |
| closing-invitation | ITC Garamond W01 Book Narrow | 400 | 40px | 1.1 | -0.01em | Newsletter invitation within the closing panel. |
| lead | Suisse Int'l | 400 | 30px | 1.25 | -0.0133em | Mission paragraph, social heading and large geometric action labels. |
| action-large | Suisse Int'l | 400 | 30px | 20px | -0.0133em | Large outlined editorial pill actions; vertically center within the button. |
| body | Suisse Int'l | 400 | 20px | 1.25 | -0.02em | Support copy, navigation links, product names and prices. |
| action-small | Suisse Int'l | 400 | 20px | 1 | -0.02em | Compact filled or outlined pills. |
| attribute | Suisse Int'l | 400 | 15px | 20px | -0.027em | Product attribute pills. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| institutional pages | institutional-title | Suisse Int'l | 400 | 140px | 145px | -0.03305em | Large cream category or identity descriptor beside a separate wordmark. |
| catalog feature tiles | featured-product-title | ITC Garamond W01 Book Narrow | 400 | 120px | 0.8 | -0.0033em | Centered oversized title overlay on a two-column product tile. |
| catalog pages | catalog-title | Suisse Int'l | 400 | 100px | 1.05 | -0.03305em | Slash-prefixed collection title. |
| help sections | help-title | Suisse Int'l | 400 | 60px | 65px | -0.016525em | Large left-column help heading. |
| help sections | help-category | Suisse Int'l | 400 | 30px | 35px | -0.0133em | Right-column topic headings and introduction. |
| institutional pages | editorial-body | Suisse Int'l | 400 | 24px | 1.25 | -0.0167em | Multi-column explanatory prose. |
| help sections | help-question | Suisse Int'l | 700 | 20px | 1.25 | -0.02em | Arrow-prefixed questions above regular-weight answers. |

**Notes:**

- Regular weight is the default even at monumental sizes; bold is reserved for question prompts.
- The serif uses unusually tight 0.8 line height at display scale. Keep heading blocks short and separate them from support text by 20px.
- The opening identity is artwork rather than an ordinary text headline. Give the new identity the same visual prominence without forcing it into a body-font recipe.

## Layout

**Density:** Airy editorial chapters surround compact, useful shopping information; large gaps do not enlarge small labels.

### Spacing

**Spacing system:**

- **vertical rhythm** 20px, vertical — Major non-fluid vertical layout rhythm; 40px, 80px and 120px are recurring multiples.

| Value | Use |
| --- | --- |
| 5px | Attribute wrapping gaps and footer link spacing. |
| 10px | Image-to-product-detail gap and compact internal clusters. |
| 20px | Page side gutters, column gutters and heading-to-support separation. |
| 30px | Support-to-editorial-action spacing and navigation clusters. |
| 40px | Catalog row gaps and section subgroups. |
| 80px | Opening-to-content breathing room, footer grid rhythm and spacing between geometric action targets. |
| 120px | Editorial chapter gaps and closing-panel top inset. |

### Containers and grids

- **page-grid**: gap 20px · side padding 20px. Full-width desktop grid: 1400px of usable width within a 1440px viewport; do not center the entire site inside a narrow box.
- **editorial-pair**: 2 columns · gap 20px · side padding 20px. Balanced halves, with text and media each capped at 600px; support copy is capped at 400px.
- **merchandise-row**: 4 columns · gap 20px · side padding 20px. Four 335px product fields across desktop; social squares reuse this arrangement.
- **closing-grid**: 2 columns · gap 20px · side padding 20px. Two equal halves; identity and newsletter on the left, mission and three-column link navigation on the right.
- **catalog-grid** (only for catalog pages): 3 columns · gap 20px. Three approximately 332px columns occupy the right 1035px beside a left navigation rail; row gap is 40px.

## Corner radius

| Element | Radius |
| --- | --- |
| action-pills | 9999px (pill) |
| product-fields | 0px |
| editorial-photo | 9999px (pill) |
| round-action-target | 50% |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default page foundation.

**CSS:** `background: #f7f6f2; color: #f74c25`

**Observed:** Untextured, matte and uninterrupted between chapters.

**Transfer:** Let whitespace, type and photography carry the hierarchy rather than adding panels.

#### Product field · level 0

**Use:** Backing for isolated goods.

**CSS:** `background: #efede7; border-radius: 0px; box-shadow: none`

**Observed:** A pale rectangular field; the details sit beneath it on the cream canvas.

**Transfer:** Use one consistent studio background across the assortment.

#### Vermilion reversal · level 0

**Use:** Full-width closing destination.

**CSS:** `background: #f74c25; color: #f7f6f2`

**Observed:** A flat saturated field, not a gradient. Institutional content extends this treatment across the page.

**Transfer:** Keep the default page mostly cream and give the closing statement the saturated field.

#### Institutional field · level 0

**Only for:** institutional and help pages

**Use:** Long-form identity, location and help content.

**CSS:** `background: #f74c25; color: #f7f6f2`

**Observed:** Cream headings, prose and rules remain on the same continuous vermilion ground.

**Transfer:** Use this inversion for a distinct informational destination, not every ordinary marketing chapter.

## Components

### Sticky navigation

**Use:** Persistent orientation and a compact primary action.

**CSS:** `display: grid; grid-template-columns: 1fr auto 1fr; height: 74px; padding: 0px 20px; gap: 30px; align-items: center; position: sticky; top: 0px; z-index: 3`

**Text style:** `body` — Suisse Int'l 400 · 20px/1.25 · tracking -0.02em

**Observed:** Menu anchors the left edge; search and a compact filled pill sit right. The small centered identity appears over content, while the first photographic stage lets the giant identity lead. Cream controls reverse to vermilion on cream; the action also becomes vermilion-filled over cream.

**Transfer:** Keep the middle visually reserved for the identity rather than a long menu list.

### Editorial outline pill

**Use:** Primary action within a feature chapter.

**CSS:** `color: #f74c25; border: 1px solid #f74c25; border-radius: 9999px; padding: 10px 30px; height: 62px; display: flex; align-items: center; gap: 10px`

**Text style:** `action-large` — Suisse Int'l 400 · 30px/20px · tracking -0.0133em

**Observed:** Centered beneath a short support paragraph; text-only labels carry the action without a filled rectangular slab.

### Compact filled pill

**Use:** Navigation conversion or contact action.

**CSS:** `background: #f7f6f2; color: #f74c25; border: 1px solid #f7f6f2; border-radius: 9999px; padding: 5px 20px; height: 42px; display: flex; align-items: center; gap: 10px`

**Text style:** `action-small` — Suisse Int'l 400 · 20px/1 · tracking -0.02em

**Observed:** Cream-filled over photography or vermilion. The inverse vermilion fill with cream type serves the same compact role on cream.

### Product attribute pill

**Use:** Brief factual qualifiers below product prices.

**CSS:** `color: #f74c25; border: 1px solid #f74c25; border-radius: 9999px; padding: 5px 15px; height: 32px; display: flex; align-items: center`

**Text style:** `attribute` — Suisse Int'l 400 · 15px/20px · tracking -0.027em

**Observed:** Outlined tags wrap into tight rows with 5px separation; they are metadata rather than filled badges.

### Product card

**Use:** Repeated merchandise or offering preview.

**CSS:** `display: grid; position: relative; row-gap: 10px`

**Text style:** `body` — Suisse Int'l 400 · 20px/1.25 · tracking -0.02em

**Observed:** A portrait Product field comes first, then a flush-left linked name, price or price range, then Product attribute pills. A sale price can sit beside a struck-through old price. No enclosing border, rounded shell or elevation.

**Transfer:** Keep the image stage distinct from the text block and preserve the compact name-price relationship.

### Geometric action target

**Use:** Pair of visually equal conversion routes.

**CSS:** `display: grid; justify-content: center; width: 480px; height: 480px; background: #f7f6f2; color: #f74c25; border: 1px solid #f74c25`

**Text style:** `lead` — Suisse Int'l 400 · 30px/1.25 · tracking -0.0133em

**Observed:** One target is square and the other circular; both hold only a centered short label. They sit side by side with an 80px gap.

**Transfer:** Use two genuinely distinct routes or modes, not a row of feature cards.

### Footer link columns

**Use:** Compact navigation within the closing destination.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); column-gap: 20px; row-gap: 40px; max-width: 800px`

**Text style:** `body` — Suisse Int'l 400 · 20px/1.25 · tracking -0.02em

**Observed:** Three left-aligned columns occupy the right half; each column is a vertical stack with 5px gaps. The newsletter invitation occupies the opposite half.

### Ruled help topic

**Only for:** help sections

**Use:** Divide long, fully expanded question-and-answer content.

**CSS:** `border-top: 1px solid #f7f6f2; padding-top: 10px; margin-top: 40px; color: #f7f6f2`

**Text style:** `help-category` — Suisse Int'l 400 · 30px/35px · tracking -0.0133em

**Observed:** Topic labels precede arrow-prefixed bold questions and regular body answers. These are expanded text blocks, not closed accordion cards.

**Transfer:** Keep content in the right half, with a large heading introducing the left half.

## Imagery and graphics

### Warm still-life stage

**Use:** Full-bleed first impression.

**Observed:** Everyday objects form a carefully balanced studio tableau: ceramic pump, metal tool, crumpled paper, glass bottle and sponge with delicate flower stems. Ochre, honey and dusty pink light warms the seamless backing; real texture and soft directional shadows remain visible. It fills the entire first viewport, with an oversized cream identity over its lower half.

**Transfer:** Photograph the new product with a few material or usage props at varied heights. If no physical object exists, stage printed output or tangible tools of the service in the same warm light; the minimum is a compelling single-object photograph, not a UI mockup floating in a gradient.

**Build:** Use a full-bleed cover image in a 900px-tall desktop stage. Place a cream vector or live serif identity over the lower half, about half the viewport wide and roughly 350px tall including its distinctive letterforms. Keep the top half open enough for sparse navigation.

### Pill documentary photography

**Use:** Alternating editorial feature chapters.

**Observed:** Hands scoop bright goods into a paper bag or jar; warm timber counters and daily working details provide context. Tall source images are 600×900px or similar and masked into elongated pills. They occupy one half of the layout while the other half stays cream and typographic.

**Transfer:** Show a real task, material interaction or human-scale working environment in warm natural light. Retain the tall pill silhouette even when the content changes.

**Build:** Place a portrait photograph in a 600px-wide wrapper, use border-radius:9999px and overflow:hidden, and preserve its tall aspect ratio. Center the companion copy within the other grid half.

### Inventory still lifes

**Use:** Merchandise grids and featured products.

**Observed:** Top-down transparent dishes of goods and front-facing jars or tools are isolated on warm stone. Objects occupy a restrained fraction of the field, with consistent soft light and substantial clear space around them; colors come from the materials rather than decorative UI.

**Transfer:** Use a consistent viewpoint per object class and normalize object scale across a row. For non-retail offerings, show tangible outputs or materials rather than screenshots inside device frames.

### Cutout link sculpture

**Use:** A signature category or capability index.

**Observed:** Large centered serif labels form a compact vertical sculpture. An almond, a bowl, a green textured object and an egg overlap or flank different lines, with a small outlined circular stamp as punctuation. The pictures have transparent edges and no enclosing tiles.

**Transfer:** Use isolated details from the new product or its materials. For intangible products, photograph small relevant tools or printed artifacts; retain several unequal cutouts around the type, not generic vector feature icons.

**Build:** Set centered 100px serif links with 80px line height and 15px spacing in a roughly 770px-wide relative wrapper. Absolutely position four transparent cutouts at alternating left and right edges, roughly 80–235px in size, allowing occasional overlap with letters. Add a small rotated 1px vermilion circular stamp containing a short contextual mark.

### Social square strip

**Use:** Visual community proof near the closing panel.

**Observed:** Four edge-to-edge square photographs show packaging, storefronts, daily-use products and arranged jars. Their varied imagery shares warm directional light and tactile materials.

**Transfer:** Use four real scenes of the product in the world, keeping equal square frames and avoiding screenshot-heavy testimonial cards.

### Icons

**Observed:** Sparse utility symbols: 22px search, 1.5px outline arrows and a larger 51×25px carousel arrow with 2px stroke. Color follows the local cream/vermilion reversal; no multicolor icon set.

**Transfer:** Use simple line utilities only where needed; keep illustrations photographic rather than substituting feature icons.

## Section recipes

How recurring sections are built.

### First screen: Photographic identity opening

**Observed:** The first 900px is a single full-bleed still-life stage. Back to front: warm seamless photographic backing, carefully staggered tactile objects, a huge cream identity across the lower half, then sparse Sticky navigation at the top. The identity spans about half the width and approximately 350px in visible height; it acts as the headline rather than a sentence. The only action is the top-right Compact filled pill beside search, with Menu opposite. No supporting paragraph, headline stack or merchandise grid appears within this first viewport; the cream content begins below it, with 80px breathing room before the first selector. Subsequent editorial titles use feature-heading.

**Transfer:** Create an equally rich Warm still-life stage and a large original identity lockup for the new product. Catalog destinations instead open on cream with a separate left identity and a slash-prefixed 100px sans title; institutional destinations use the vermilion field, a 140px cream sans descriptor and a large square environmental image beside a short anchor list.

**Avoid:** Do not turn the opening into a conventional left headline/right product split, or add a large paragraph and multiple hero buttons over the photograph.

**Text style:** `feature-heading` — ITC Garamond W01 Book Narrow 400 · 80px/0.8 · tracking -0.02175em

### Merchandise selector and row

**Observed:** Centered 80px serif collection labels sit above a four-column Product card row. Active text is fully saturated; inactive labels use 0.25 opacity. Portrait images are 335×415px at desktop. An outline arrow at the right edge advances the row.

**Transfer:** Use a small set of meaningful groupings, followed by a disciplined row of offerings rather than descriptive feature panels.

**Text style:** `feature-heading` — ITC Garamond W01 Book Narrow 400 · 80px/0.8 · tracking -0.02175em

### Clipped verbal ribbon

**Observed:** A 144px-high single line uses word-ribbon in vermilion on cream. Repeated short verbs extend beyond both viewport edges; generous separation keeps each word readable.

**Transfer:** Choose a small set of action words that express the new product's behavior, keeping the oversized clipped-strip device independent of section order.

**Text style:** `word-ribbon` — Suisse Int'l 400 · 180px/0.8 · tracking -0.03305em

### Alternating editorial pair

**Observed:** A Pill documentary photography frame occupies one half while a centered 600px text block occupies the other. The 80px serif title is followed by support limited to 400px, 20px below; the Editorial outline pill follows the support after 30px. Successive chapters alternate image side and are separated by 120px.

**Transfer:** Use each chapter to explain one use, service or reason to care, with a different real-world scene.

**Text style:** `feature-heading` — ITC Garamond W01 Book Narrow 400 · 80px/0.8 · tracking -0.02175em

### Type and cutout index

**Observed:** The Cutout link sculpture centers a narrow stack of 100px serif links with 15px spaces, interleaved with floating object photographs. An Editorial outline pill sits 40px below the list.

**Transfer:** Make categories or capabilities navigable through typography, and use relevant object fragments to punctuate the list.

**Text style:** `category-display` — ITC Garamond W01 Book Narrow 400 · 100px/0.8 · tracking -0.02175em

### Conversion geometry and social strip

**Observed:** Two Geometric action targets, one square and one circle, create a 480px-high conversion section. A later social strip pairs a 30px heading with an Editorial outline pill, followed after 20px by four 335px square images.

**Transfer:** Use the geometric pair for alternative next steps and the image strip for lived-in proof rather than written endorsements.

**Text style:** `lead` — Suisse Int'l 400 · 30px/1.25 · tracking -0.0133em

### Vermilion closing destination

**Observed:** Vermilion reversal fills a 900px desktop ending with 120px top and 40px bottom insets. A 266×130px cream identity anchors the upper left; a 600px-wide 30px mission paragraph sits upper right and embeds proof in prose rather than stat cards. Below, the 40px serif invitation and a short body line face Footer link columns. A small credential mark sits low on the left, followed by fine print at the base. The institutional ending remains on the same saturated ground.

**Transfer:** Give the new identity and a concise purpose-plus-proof paragraph the upper row. Keep the serif invitation and practical navigation below; display a credential only when a legitimate one exists.

**Text style:** `closing-invitation` — ITC Garamond W01 Book Narrow 400 · 40px/1.1 · tracking -0.01em

### Catalog with editorial interruptions

**Only for:** catalog pages

**Observed:** A left taxonomy rail accompanies three columns of Product cards on cream. Occasional Product fields span two columns and overlay a 120px centered serif title plus a small outlined oval word stamp. The catalog ends with the Type and cutout index and Vermilion closing destination.

**Transfer:** Interrupt a large assortment with a few oversized featured items without abandoning the quiet inventory photography.

**Text style:** `featured-product-title` — ITC Garamond W01 Book Narrow 400 · 120px/0.8 · tracking -0.0033em

### Institutional explanation and help

**Only for:** institutional and help pages

**Observed:** Continuous vermilion ground carries cream text. Explanatory content pairs a 30px introductory sentence on the left with 24px multi-column prose on the right. A centered location/contact chapter uses a wide oval title and vertically stacked 30px address blocks. Help begins with a 60px left title and a right column of Ruled help topics, bold arrow-prefixed questions and 20px answers capped at 600px.

**Transfer:** Use the inverted layout for organizational context and practical questions. Keep location details relevant to the new service, or substitute equally useful contact routes.

**Text style:** `help-title` — Suisse Int'l 400 · 60px/65px · tracking -0.016525em

## Page flow

**Storyline:** Sensory identity → browsable offering → editorial uses → typographic discovery → practical next step → community imagery → purpose-led closing.

### Marketing landing page that makes a physical offering feel useful and desirable

1. **Sensory promise** — Full-viewport still life with monumental identity and minimal navigation.
2. **Offering preview** — Serif selectors above a four-item merchandise row.
3. **Brand behavior** — Oversized clipped verb ribbon.
4. **Use-case explanation** — Alternating pill-shaped photographs and compact centered editorial copy.
5. **Discovery** — Serif category sculpture with floating cutouts.
6. **Conversion and social proof** — Square/circle action pair followed by a four-image social strip.
7. **Purpose and utility** — Full saturated closing panel with mission prose, newsletter invitation and link columns.

**Transfer:** Adapt the number and placement of chapters to the new product while retaining the identity stage, verbal scale, tactile imagery and destination-like ending.

### Browse a large assortment without losing editorial character

1. **Orientation** — Separate identity mark and slash-prefixed sans title.
2. **Navigation and comparison** — Left taxonomy rail, compact view control and three-column inventory grid.
3. **Highlight** — Intermittent two-column product fields with giant serif overlays and oval stamps.
4. **Further discovery** — Centered serif index with photographic cutouts.
5. **Purpose and utility** — Shared vermilion closing destination.

**Transfer:** Scale the assortment freely; preserve the sidebar-to-grid proportion and a few editorial interruptions rather than reproducing the original list length.

### Explain the organization and answer practical questions

1. **Identity and orientation** — Cream descriptor on a vermilion field, short anchor list and square environmental photo.
2. **Rationale** — Left introduction and right multi-column explanatory prose.
3. **Access** — Centered contact/location blocks and compact cream action pills.
4. **Objection handling** — Large left title beside expanded, ruled question-and-answer topics.
5. **Purpose and utility** — Same mission-led footer continuing the saturated ground.

**Transfer:** Use the inverted informational variant for context, access and help rather than applying its all-red canvas to an ordinary launch page.

## Writing

Friendly, practical and lightly playful, with conviction expressed through concrete everyday behavior. Editorial headings invite participation; explanatory copy stays direct and useful rather than lofty.

**Do not copy:** Do not reuse the re_ identity, proprietary artwork, product and service names, store addresses, discount offer, sustainability totals, founding date or other source-specific claims. Source examples illustrate tone only.

- **Addressing the reader:** Use we for the organization and you or your when describing the reader's task; short labels can remain plain nouns.
- **Rhythm:** Most headings are two to four words. One short support sentence usually leads into a one-to-three-word action; help answers expand into clear paragraphs and simple steps. Occasional exclamation marks add genuine warmth.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Editorial heading | Short benefit or conversational invitation with an everyday turn of phrase. | 2–4 words | “Stay in the Loop”<br>“We Pop Up!” |
| Supporting line | Connect a concrete action to an understandable benefit. | One sentence | “Achieve your corporate sustainability goals by switching to package-free office snacks!” |
| Primary action | Name the destination or immediate task rather than a generic conversion slogan. | 1–3 words | “Order”<br>“The Scoop” |
| Closing invitation | Warm ongoing relationship rather than high-pressure urgency. | 4–5 words | “Let's Keep in Touch” |
| Help introduction | Acknowledge unfamiliarity and immediately reassure. | Two short clauses | “New here? We're here to help.” |

**Words and phrasing to use:** we’re here; your; keep in touch; bring; shop; refill; everyday actions; specific materials

**Avoid:** revolutionary platform; unlock your potential; disruptive ecosystem; luxury exclusivity; artificial urgency

**Rules:**

- Prefer a specific useful action to an abstract brand promise.
- Let playful headings sit above literal, informative body text.
- Integrate credible proof into a short human paragraph rather than turning every number into a giant metric.
- Answer practical questions directly, then explain the process in everyday language.

## Do's and Don'ts

### Do

- Use #f74c25 as the default text and hairline color on #f7f6f2.
- Keep editorial serif headings at weight 400 and 0.8 line height.
- Pair 600px-wide portrait pill photographs with support copy no wider than 400px.
- Retain the 20px desktop page gutters and column gaps.
- Separate editorial chapters by 120px while keeping product details only 10px below images.
- Use 1px outlines for pills and the large square/circle action pair.
- End with a spacious saturated panel, 120px top inset and a 30px purpose paragraph.
- Keep product photography consistently scaled and surrounded by warm stone.

### Don't

- Do not replace vermilion body text with a generic black or charcoal neutral ramp.
- Do not round merchandise fields into soft UI cards; their corners remain 0px.
- Do not add drop shadows or glass blur to compensate for the flat surface system.
- Do not convert the serif link sculpture into an equal-size icon grid.
- Do not make every action a filled rectangle; editorial actions are outlined 62px pills.
- Do not use bold or uppercase display typography as the dominant hierarchy.
- Do not turn the closing purpose paragraph into a dashboard of giant numerical stats.
- Do not wash photography in monochrome vermilion; the material colors and warm light are integral.

## Motion and responsive

### Motion

**Observed:**

- The navigation and opening stage use sticky positioning.
- The word ribbon is horizontally translated and clipped at the viewport edges.
- No action or surface transition timing is established.

**Transfer:**

- Preserve the ribbon's overflow and the sticky navigation relationship; if animating the ribbon, keep its words readable and retain the same static composition.

**Unknown:**

- Ribbon speed and interaction timing, hover and focus appearance, and transition durations are unspecified.

### Responsive

**Observed:**

- Width breakpoints are declared at 600px, 700px and 1000px.

**Transfer:**

- At narrower widths, preserve the full-bleed identity stage, warm photograph and sparse navigation. Reflow editorial halves into a vertical pairing and scale the word sculpture and cutouts together so they do not obscure links.
- Allow merchandise and taxonomy layouts to simplify without converting them into rounded cards; retain the cream/vermilion reversal at the ending.

**Unknown:**

- Exact mobile font sizes, column counts, navigation behavior and image masking changes are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
