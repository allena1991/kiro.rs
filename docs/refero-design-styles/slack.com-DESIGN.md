# Slack — conversation at full scale

## Overview

A bright, confident software-marketing style that makes complex work feel approachable and human. Geometric display sans meets practical body sans, with black-on-white clarity punctuated by deep aubergine chapters and pale lavender staging. Large interface demonstrations carry the story, supported by cinematic customer photography, compact editorial cards and unusually emphatic numerical proof. The overall density is airy in the narrative and deliberately compact in comparison and directory views.

### Essentials

- Big promises sound conversational, not institutional: centered geometric headlines at 64px/68px, weight 700 and -0.012em tracking; major capability leads use 50px/56px at weight 600.
- The opening is a promise above a working product, not a decorative abstract scene: a 923px headline block, paired 57px actions, a subdued trust strip and an 800px-wide interface extending below the first screen.
- Actions are crisp rectangles rather than pills: 4px corners, 14px bold uppercase labels with 0.057em tracking, purple fill beside a 1px inset purple outline.
- White owns most of the narrative; aubergine is concentrated into immersive demonstration, proof and closing bands. Keep saturated purple for actions and active text, and pale lavender behind media rather than washing every section.
- Interfaces are monumental and legible: a centered 800×548px opening demonstration and 876×600px capability scenes that can extend beyond the container. If no finished interface exists, construct one coherent task scene with real labels and a visible outcome.
- Pair an active vertical-rail story with emphatic proof: 24px/32px purple accordion leads, a 4px lavender rail with purple progress, and either gradient 64px numerals or white 80px numerals on aubergine. End the argument with an expansive 50px conversion line and paired reversed actions. These devices belong in the design even when their position and frequency change.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Aubergine | `#481a54` | `--color-purple-deep` | background, text, action | Immersive bands, closing calls and primary-action hover. |
| Action purple | `#730394` | `--color-purple-action` | action, accent, text | Primary buttons, outline buttons, badges and active progress. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link blue | `#0b5cab` | `--color-link` | link | Underlined text actions and editorial card actions. |
| Lavender wash | `#f9f0ff` | `--color-lavender` | surface, background | Media backing, badges, broad curved staging and gradient endpoints. |
| Active violet | `#9602c7` | `--color-purple-bright` | text, accent | Active capability titles and gradient statistics. |
| Gradient lilac | `#d17dfe` | `--color-purple-light` | accent | Light endpoint of purple numerical gradients. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, card surfaces and reversed text. |
| Card hairline | `#f3f3f3` | `--color-card-edge` | border | Subtle outline on rounded release cards. |
| Footer edge | `#edeaed` | `--color-footer-rule` | border | Fine boundaries above and below the footer directory. |
| Divider gray | `#c9c9c9` | `--color-rule` | border | Accordion rules, carousel control edges and column dividers. |
| Secondary gray | `#5c5c5c` | `--color-muted` | text | Footer links, trust captions and quieter labels. |
| Caption gray | `#444444` | `--color-caption` | text | Editorial format labels and support copy. |
| Navigation ink | `#1d1d1d` | `--color-nav-ink` | text, border | Navigation labels, footer categories and input outlines. |
| Soft black | `#181818` | `--color-text` | text | Capability headings and product-marketing descriptions. |
| Headline black | `#000000` | `--color-ink` | text | Opening headline, editorial headings and main prose. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and sales pages | Plan divider | `#e5e5e5` | `--color-plan-rule` | border | Plan-card boundaries and table rules. |
| pricing and sales pages | Recommended orchid | `#a350af` | `--color-plan-highlight` | border, background | Recommended-plan border and raised banner. |
| pricing pages | Comparison gray | `#f5f4f5` | `--color-comparison` | surface | Comparison columns and security information panels. |
| feature directories | Ice blue | `#eaf5fe` | `--color-ice` | background | Long, almost-white blue gradient beneath capability tiles. |
| enterprise storytelling | Blue mist | `#eef4ff` | `--color-blue-mist` | background | Cool end of lavender media-panel gradients. |

## Typography

- **Salesforce-Avant-Garde** — Headlines, capability titles and emphatic statistics. Geometric, broad and rounded with single-storey forms; friendly without losing the force of bold display type. If unavailable, use **Poppins**. Use 600–700 for headings; preserve tight tracking and check line breaks. Font stack: "Salesforce-Avant-Garde", "Poppins", system-ui, sans-serif.
- **Salesforce-Sans** — Body copy, navigation, actions and captions. Practical humanist sans, more restrained than the geometric headlines, with light italic testimonial cuts. If unavailable, use **Open Sans**. Use regular and bold; light italic for testimonial passages. Font stack: "Salesforce-Sans", "Open Sans", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat-band | Salesforce-Avant-Garde | 700 | 80px | 1.05 | -0.012em | fixed | White numerical proof on aubergine. |
| display | Salesforce-Avant-Garde | 700 | 64px | 68px | -0.012em | fixed | Default centered opening promise. |
| stat | Salesforce-Avant-Garde | 700 | 64px | 1 | -0.012em | size clamp(3rem, 2.35897rem + 2.5641vw, 4rem) | Black numerical proof in stacked rows. |
| stat-gradient | Salesforce-Avant-Garde | 400 | 64px | 1 | -0.012em | fixed | Gradient numerical callouts beneath an active capability. |
| chapter | Salesforce-Avant-Garde | 600 | 50px | 1.12 | -0.012em | fixed | Major capability chapter and immersive demonstration headings. |
| conversion-heading | Salesforce-Avant-Garde | 700 | 50px | 1.12 | -0.012em | size clamp(2rem, 1.27885rem + 2.88462vw, 3.125rem) | Closing conversion line; also the opening headline for narrower-purpose pages. |
| heading | Salesforce-Avant-Garde | 700 | 32px | 1.25 | -0.008em | size clamp(1.75rem, 1.58974rem + 0.641026vw, 2rem) | Editorial, resource, FAQ and compact section headings. |
| heading-tight | Salesforce-Avant-Garde | 700 | 32px | 1.25 | -0.012em | size clamp(1.75rem, 1.58974rem + 0.641026vw, 2rem) | Release-module and proof-section heading variant. |
| card-heading | Salesforce-Avant-Garde | 700 | 24px | 1.25 | -0.004em | size clamp(1.4rem, 1.3359rem + 0.25641vw, 1.5rem) | Editorial and release card titles. |
| accordion-heading | Salesforce-Avant-Garde | 600 | 24px | 1.333 | -0.012em | fixed | Capability accordion leads, purple when active. |
| stat-caption | Salesforce-Avant-Garde | 400 | 24px | 1.333 | -0.012em | fixed | Gradient proof descriptions attached closely to the numeral. |
| lead | Salesforce-Sans | 400 | 20px | 1.5 | -0.0012em | size clamp(1.125rem, 1.04487rem + 0.320513vw, 1.25rem) | Supporting copy on focused product, sales and culture openings. |
| body | Salesforce-Sans | 400 | 18px | 1.555 | -0.0012em | fixed | Default support lines and prose. |
| faq-question | Salesforce-Sans | 700 | 18px | 1.555 | -0.0012em | fixed | Accordion questions. |
| text-link | Salesforce-Sans | 700 | 16px | 1.5 | normal | fixed | Underlined supporting links with a right arrow. |
| action | Salesforce-Sans | 700 | 14px | 1.286 | 0.057em, uppercase | fixed | Button labels, small campaign eyebrows and resource actions. |
| caption | Salesforce-Sans | 400 | 14px | 1.3 | 0.007em | fixed | Editorial format labels. |
| footer-link | Salesforce-Sans | 400 | 14px | 1.555 | -0.0015em | fixed | Dense footer directory links. |
| footer-label | Salesforce-Sans | 700 | 14px | 1.555 | 0.057em, uppercase | fixed | Footer directory categories. |
| badge | Salesforce-Sans | 700 | 12px | 1.333 | normal | fixed | Small new-feature badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| enterprise storytelling | enterprise-heading | Salesforce-Avant-Garde | 700 | 40px | 1.25 | -0.008em | fixed | Centered enterprise chapter headings. |
| feature-directory proof sections | testimonial | Salesforce-Sans | 200 italic | 28px | 1.5 | -0.009em | size clamp(1.375rem, 1.13462rem + 0.961539vw, 1.75rem) | Centered, spacious customer quotation. |
| feature directories | tile-heading | Salesforce-Sans | 700 | 18px | 1.444 | normal | fixed | Compact capability tile headings. |
| feature directories | tile-body | Salesforce-Sans | 400 | 18px | 1.444 | normal | fixed | Capability tile descriptions. |
| pricing and sales pages | plan-name | Salesforce-Avant-Garde | 700 | 18px | 1.556 | -0.004em | fixed | Plan names above price and action. |
| careers directories | job-row | Salesforce-Sans | 400 | 14px | 1.555 | -0.0012em | fixed | Role title and metadata in opportunity directories. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use the geometric family for promises and the practical sans for explanation. Large headings tighten to -0.012em; small card titles relax to -0.004em.
- Keep the 64px default opening distinct from the 50px focused-page opening. Do not average their weights with the 600-weight capability chapters.
- Statistics have three voices: monumental reversed bold, compact black bold and purple-gradient regular. Their captions remain adjacent, not detached into a distant footnote.

## Layout

**Density:** Airy narrative sections with tightly grouped headings and actions; dense comparison and directory regions provide a deliberate change of pace.

### Spacing

**Spacing system:**

- **layout rhythm** 8px — Dominant reusable layout rhythm for gaps and section padding; retain exceptions such as 30px card gutters and 11.2px comparison-cell padding.

| Value | Use |
| --- | --- |
| 8px | Close title-to-description and link spacing; paired actions. |
| 16px | Headline support spacing, tile padding and small grid gaps. |
| 24px | Release-card copy insets and grouped control spacing. |
| 30px | Four-column editorial and three-column contact-card gutters. |
| 32px | Closing heading-to-action spacing and FAQ button vertical padding. |
| 48px | Heading-to-media separation and release-carousel gutters. |
| 64px | Proof-column horizontal padding and larger internal separation. |
| 72px | Immersive demonstration band padding and proof-column gaps. |
| 80px | Editorial sections and closing-band vertical padding. |
| 96px | Major capability-chapter vertical padding. |
| 104px | Opening content start, just beneath the 80px header. |

### Containers and grids

- **marketing container**: max width 1230px. Centered desktop narrative container; at 1440px the side margins are 105px.
- **opening headline**: max width 923px. Centered two-line opening headline, broader than the 800px demonstration.
- **section introduction**: max width 800px. Centered chapter explanation with short support copy.
- **faq column**: max width 864px. Centered question list narrower than the narrative container.
- **editorial grid**: 4 columns · gap 30px. Four 285px resource cards across the main container.
- **demonstration split**: 2 columns · gap 61.5px. 40% text and 55% demonstration composition, with the remaining 5% separating them.
- **capability split**: 2 columns · gap 61.5px. 455px text rail alongside an 876px-wide interface that may extend beyond the container.
- **contact grid** (only for enterprise sales endings): 3 columns · gap 30px. Three 390px conversion cards.
- **feature grid** (only for feature directories): 4 columns · gap 16px. Compact capability directory; tall descriptive tiles can sit beside stacked short tiles.
- **plan comparison** (only for pricing pages): 4 columns · gap 0px. Touching plan columns; the recommended column lifts above its neighbors.
- **opportunity directory** (only for careers directories): max width 1040px. Centered listings with role title, location metadata and right-aligned action.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons and inputs | 4px |
|  | media and release cards | 16px |
|  | video frame | 12px |
|  | switcher rows | 32px |
|  | badges | 9999px (pill) |
| pricing and sales pages | plan cards | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | resource card | `rgba(0, 0, 0, 0.1) 0px 0px 16px 0px` | Diffuse lift without a visible hard base. |
| feature directories | feature tile | `rgba(0, 0, 0, 0.1) 0px 0px 32px 0px` | White tile lift over a pale blue field. |
| enterprise storytelling | enterprise bento | `rgba(0, 0, 0, 0.1) 0px 4px 23.4px 0px` | Rounded media and resource panels. |

### Surfaces

#### White canvas · level 0

**Use:** Default narrative field.

**CSS:** `background: #ffffff`

**Observed:** The dominant page material is clean white, with imagery and type doing most of the work.

**Transfer:** Keep broad light intervals between colored chapters.

#### Aubergine band · level 0

**Use:** Immersive demonstration, numerical proof and final conversion.

**CSS:** `background: #481a54; color: #ffffff`

**Observed:** Full-bleed color rather than a floating dark card; faint decorative sparkles stay subordinate to the white type and product scene.

**Transfer:** Concentrate the strongest color into a few narrative anchors.

#### Lavender horizon · level 0

**Use:** Curved backing rising behind the opening demonstration.

**CSS:** `background: linear-gradient(#f9f0ff 5%, #ffffff 10%); border-radius: 50%`

**Observed:** An oversized 2880px circle extends beyond both sides of the viewport. Only its shallow upper arc is prominent.

**Transfer:** Use an oversized circular field to ground the product without creating a boxed hero.

#### Gradient statistic

**Use:** Numerical callout and its short description.

**CSS:** `background-image: linear-gradient(#481a54 0%, #730394 35.2%, #9602c7 80%, #d17dfe 100%); background-clip: text; color: rgba(0, 0, 0, 0)`

**Observed:** The gradient affects the glyphs, not a panel behind them.

**Transfer:** Use on short credible proof, keeping the figure and explanation visually joined.

#### Blue directory field · level 0

**Only for:** feature directories

**Use:** Continuous backing across grouped capability tiles.

**CSS:** `background: linear-gradient(#ffffff, #eaf5fe 70%)`

**Observed:** A long pale-blue field is interrupted by white cards and finishes in a broad white arc.

**Transfer:** Treat the directory as one coherent landscape, not alternating unrelated colored sections.

#### Lavender bento panel · level 1

**Only for:** enterprise storytelling

**Use:** Wide accordion and product demonstration.

**CSS:** `background: linear-gradient(110deg, #ffffff 36.55%, #f9f0ff 95.84%); border-radius: 16px; overflow: hidden`

**Observed:** A pale blue-to-lavender rounded corner shape sits behind the right-hand product scene; the outer panel carries the enterprise bento shadow.

**Transfer:** Separate explanatory text from layered media without drawing a hard central divider.

#### Curved conversion band · level 0

**Only for:** pricing, feature-directory and culture endings

**Use:** Reversed closing line immediately before the footer.

**CSS:** `background: #481a54; color: #ffffff; padding: 80px 0px; clip-path: ellipse(75% 100% at 50% 0%)`

**Observed:** The bottom edge bows downward across the page rather than ending in a straight horizontal cut.

**Transfer:** Use a broad shallow elliptical exit, preserving enough colored area for actions.

#### Comparison surface · level 0

**Only for:** pricing pages

**Use:** Comparison columns and security information panels.

**CSS:** `background: #f5f4f5`

**Observed:** Column shading is restrained; security panels use 12px corners and 48px 64px padding.

**Transfer:** Keep dense decision content readable without making every cell a card.

## Components

### Primary navigation

**Use:** Persistent site-level wayfinding.

**CSS:** `height: 80px; position: fixed; background-color: rgba(255, 255, 255, 0.298); box-shadow: rgba(0, 0, 0, 0.024) 0px 1.2px 12px 0px; z-index: 1000`

**Observed:** Centered inner row; small logo at left, category links with tiny chevrons, search and sign-in toward the right, then outline and filled 42px actions. The surface reads white rather than dark glass.

**States:** Declared: hover behavior varies by link; focus-visible on category triggers uses a 2px dotted purple outline with 5px offset.

### Primary button

**Use:** Main conversion on a light field.

**CSS:** `background: #730394; color: #ffffff; border-radius: 4px; padding: 19px 40px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Salesforce-Sans 700 · 14px/1.286 · tracking 0.057em · uppercase

**Observed:** Default action is approximately 57px high. The compact navigation version is 42px high with 12px 16px padding. On aubergine, the main action reverses to white with purple text.

**States:** Declared: hover background #481a54 and white text; active background #481a54 and white text.

### Secondary button

**Use:** Adjacent lower-priority conversion.

**CSS:** `background: #ffffff; color: #730394; border-radius: 4px; padding: 19px 40px 20px; box-shadow: #730394 0px 0px 0px 1px inset`

**Text style:** `action` — Salesforce-Sans 700 · 14px/1.286 · tracking 0.057em · uppercase

**Observed:** Placed 8px after the filled action; a small right arrow can follow the label. Reversed variant uses white text and a white inset edge on aubergine.

**States:** Declared: hover thickens the purple inset edge to 2px while retaining white fill; active fills purple with white text.

### Arrow text link

**Use:** Supporting exploration without competing with conversion buttons.

**CSS:** `color: #0b5cab; text-decoration: underline; display: inline-flex; align-items: center; border: 2px solid transparent`

**Text style:** `text-link` — Salesforce-Sans 700 · 16px/1.5

**Observed:** Underlined words followed by a separate fine right arrow. The arrow has breathing room instead of being attached to the last letter.

**States:** Declared: hover color rgb(1, 68, 134) with no underline; focus-visible border 2px solid #481a54 and 4px radius; active matches hover.

### Resource card

**Use:** Editorial reports, guides and product education.

**CSS:** `background: #ffffff; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 16px 0px; display: flex; flex-direction: column; max-width: 285px`

**Text style:** `card-heading` — Salesforce-Avant-Garde 700 · 24px/1.25 · tracking -0.004em

**Observed:** Square-edged default: image first, format caption, short geometric title, uppercase blue action pinned near the bottom with a right arrow. Typical desktop card is 285×420px with a 285×208px image. Release variant grows to 400×440px, uses 16px corners and a faint card-edge outline, with a lavender new-feature badge.

**States:** Declared: hover transform scale(1.05) and shadow rgba(0, 0, 0, 0.2) 0px 0px 32px; active shadow rgba(24, 24, 24, 0.1) 0px 4px 8px -3px.

### Demonstration switcher

**Use:** Short capability choices beside a large demonstration on aubergine.

**CSS:** `border-radius: 32px; padding: 12px 16px; box-shadow: rgba(255, 255, 255, 0.25) 0px 0px 0px 1px inset; max-width: 492px; color: #ffffff`

**Text style:** `faq-question` — Salesforce-Sans 700 · 18px/1.555 · tracking -0.0012em

**Observed:** Five slim, evenly spaced choice rows face a larger video. Labels are sentence case; a tiny pale badge can sit at the far end. The media retains its own pause control.

### FAQ row

**Use:** Objection handling in a narrow centered list.

**CSS:** `border-top: 1px solid #c9c9c9; padding: 0px 24px`

**Text style:** `faq-question` — Salesforce-Sans 700 · 18px/1.555 · tracking -0.0012em

**Observed:** Question button inside has 32px vertical padding and reserves 48px at the right for a chevron. Rows are roughly 93px high, growing for wrapped questions. Last row closes the list with a bottom rule.

**Transfer:** Use direct buyer questions; expansion should reveal prose in place, not navigate to a new page.

### Footer directory

**Use:** Full site ending after the conversion section.

**CSS:** `border-top: 1px solid #edeaed; border-bottom: 1px solid #edeaed; padding: 48px 0px 40px; display: flex; justify-content: space-between`

**Text style:** `footer-link` — Salesforce-Sans 400 · 14px/1.555 · tracking -0.0015em

**Observed:** Region selector and social icons precede the directory. A small brand symbol occupies the left; five 176px link columns use 28px horizontal and 32px vertical gaps, with uppercase category labels. Download and privacy links finish at lower left, copyright at lower right.

**Transfer:** Scale the number of links to the new product, retaining the low-contrast directory and visibly distinct conversion ending.

### Capability tile

**Only for:** feature directories

**Use:** Compact browseable capability catalog.

**CSS:** `background: #ffffff; padding: 16px; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 32px 0px; display: flex; flex-direction: column`

**Text style:** `tile-heading` — Salesforce-Sans 700 · 18px/1.444

**Observed:** 48px icon, bold practical-sans title, optional regular description, and an arrow at the bottom right. Four columns mix full-height tiles with stacked short tiles; edges remain square.

**States:** Declared: hover scale(1.05), blue text and shadow rgba(0, 0, 0, 0.2) 0px 0px 32px; active outline 0px.

### Recommended plan

**Only for:** pricing and sales pages

**Use:** Highlight one offer without darkening the whole card.

**CSS:** `border: 2px solid #a350af; border-radius: 12px; box-shadow: rgba(24, 24, 24, 0.1) 0px 4px 16px 0px; padding: 10px 0px; display: flex; flex-direction: column; align-items: center`

**Text style:** `plan-name` — Salesforce-Avant-Garde 700 · 18px/1.556 · tracking -0.004em

**Observed:** Raised above adjoining columns, with an orchid banner labeled Best value. Order is name, short benefit, promotional badge when relevant, price, billing qualifier, action, feature list. Only the recommended plan gets the filled button in the opening pricing grid; pale lavender rows group advanced capabilities.

**Transfer:** Use a single evidence-based recommendation; align price and action baselines across neighboring offers.

### Sales input

**Only for:** enterprise lead forms

**Use:** Compact fields in a two-column form beside a persuasive introduction.

**CSS:** `background: #ffffff; border: 1px solid #1d1d1d; border-radius: 4px; padding: 10.4px; height: 40px`

**Observed:** Visible labels sit above fields, not solely in placeholders. Required markers and privacy copy sit with the form; the submit action is purple.

### Opportunity category

**Only for:** careers directories

**Use:** Break a long role listing into readable groups.

**CSS:** `background: #730394; color: #ffffff; border-radius: 100px; padding: 8px 16px; margin-top: -20px`

**Observed:** A centered category pill interrupts a thin full-width rule. Beneath it, 48–64px rows align role, location metadata and blue Apply arrow. A white filter bar with underlined selectors stays above the directory.

**Transfer:** Keep listings tabular and light; use category pills as landmarks rather than boxing each role.

## Imagery and graphics

### Working product scene

**Use:** Primary visual language in the opening and capability chapters.

**Observed:** Large, bright interface windows use a purple shell around white working areas. Real conversations, avatars, task steps and a visible response make the product feel inhabited. Chapter scenes often extend off the right edge, while the opening scene is centered and partially below the fold.

**Transfer:** Show one clear job being completed in the new product. Minimum acceptable version is a crisp HTML or vector interface with coherent navigation, meaningful content and one emphasized result, rather than a collage of tiny unreadable windows.

**Build:** Use a white application panel with a 12–16px outer radius, a narrow brand-colored top bar and optional left rail. Add restrained window controls and a small number of content blocks; keep most detail inside the panel neutral. Stage the opening panel over Lavender horizon.

### Curved lavender staging

**Use:** Signature transition beneath the opening product and at major exits.

**Observed:** Very broad shallow arcs turn white into lavender or deep purple without diagonal cuts. They are architectural background shapes, not small decorative blobs.

**Transfer:** Include a broad curved field as a recognizable framing device even if the product has no illustration.

**Build:** For the opening, center a 2880×2880px circle behind the scene at a 1440px layout, with a lavender-to-white vertical gradient and its upper edge near the lower first screen. For a focused-page closing band, clip aubergine with ellipse(75% 100% at 50% 0%). Keep shapes behind readable content.

### Customer film cards

**Use:** Social proof after capability explanation.

**Observed:** One wide 580×328px photographic card sits beside three narrow 183×328px cards, separated by 24px. Natural workplace, portrait and industrial footage is darkened; white customer marks and a title stay readable, and the active card has a white circular play control.

**Transfer:** Use real people or real operating environments. Minimum acceptable version is a small set of high-quality still photographs with one selected card expanded.

**Build:** Use object-fit cover and 16px corners. Add a dark bottom gradient rising from rgba(24,24,24,0.55) to transparent, with roughly 24px content inset; narrow inactive cards can use a uniform rgba(0,0,0,0.5) veil.

### Editorial thumbnails

**Use:** Resource-card image areas.

**Observed:** Pale lavender fields support interface fragments, floating product objects and occasional event photography. Some artwork is saturated purple, but the surrounding card remains white and the title stays outside the image.

**Transfer:** Create simple benefit-specific diagrams or interface compositions within consistent thumbnail proportions. Avoid making every card a different illustration style.

### Enterprise media sculpture

**Only for:** enterprise storytelling

**Use:** Hero object and a partial repeat at the contact-card ending.

**Observed:** A large multicolor dimensional brand symbol has rounded extruded pieces, glossy translucent edges and soft lighting. The ending repeats it partially outside the left viewport; elsewhere pale rounded geometric backplates sit behind interface fragments.

**Transfer:** Replace the symbol with a dimensional form from the new product's own visual language. A small group of rounded colored slabs is an acceptable minimum; do not substitute generic floating cubes throughout the page.

**Build:** As a simpler equivalent, arrange rounded extruded lozenges as an SVG or CSS layered object, with pale highlights along upper edges, darker side faces and soft shadows. Keep the object confined to the hero or closing edge. For panel backplates, use a 661px shape with three 900px rounded corners, a 178deg blue-mist-to-lavender gradient and a 90deg rotation.

### Inclusive editorial illustration

**Only for:** culture and recruiting pages

**Use:** Culture opening and alternating editorial splits.

**Observed:** Flat, warm illustrations show people collaborating in person and through video windows. Diverse skin tones, varied bodies and bright clothing sit over cream, pink or turquoise rectangular backings, with black grounding shapes and simple furniture. Secondary illustrations show hands, everyday desk objects and plants.

**Transfer:** Commission human-centered scenes related to the new organization's work. Minimum acceptable version is a composed flat vector scene with a limited warm palette and credible human activity, not a row of stock avatars.

### Icons

**Observed:** Marketing icons read as simple black or purple outline-like pictograms, often 48px in directory tiles; the SVGs may be built from filled paths. Small 12px chevrons, 16–20px checks and fine right arrows support navigation. Play controls are white circles with purple triangles.

**Transfer:** Use a consistent simple pictogram set with rounded geometry. Keep standalone feature icons larger than utility marks; do not import detailed product-toolbar iconography into marketing headings.

## Section recipes

How recurring sections are built.

### First screen: Promise above the product

**Observed:** White canvas and fixed 80px Primary navigation lead into a centered 923px-wide, two-line display headline beginning at 104px. The support line sits 20px below, then the Primary button and Secondary button after 16px. A subdued horizontal trust strip separates the actions from an 800×548px working interface beginning around 469px. Back-to-front layers are White canvas, the oversized Lavender horizon rising near the bottom, then the product window, with headline and actions above. Within the first 900px, the headline, one-sentence support, both actions, trust marks and most of the large interface are visible; the interface bottom, playback control and lower choice chips fall below.

**Transfer:** Make a similarly short, wide promise above one convincing product task. Without finished media, build the Working product scene rather than leaving the stage empty. Focused product pages instead use a 40/55 split with a 50px headline and product scene; pricing opens with centered 50px type above plans; recruiting uses a short left-aligned invitation beside a flat editorial scene.

**Avoid:** Do not place a small decorative image beside the default opening headline, add a dark hero background, or shrink the product enough to fit the whole opening inside one screen.

**Text style:** `display` — Salesforce-Avant-Garde 700 · 64px/68px · tracking -0.012em

### Immersive demonstration chapter

**Observed:** Aubergine band with 72px vertical padding, centered chapter heading and 18px white support separated by 8px. Beneath, a Demonstration switcher occupies the left 40% and a 677×463px video the right 55%, with its own playback control.

**Transfer:** Use a small set of tangible outcomes as switcher labels and show the selected outcome in a coherent working scene.

**Text style:** `chapter` — Salesforce-Avant-Garde 600 · 50px/1.12 · tracking -0.012em

### Capability chapter with active rail

**Observed:** A centered chapter heading and short support line introduce a white section with 96px vertical padding. Below, a 455px text rail faces an oversized 876×600px interface. Active content has purple 24px type, explanation and Arrow text link spaced by 8px; inactive titles are separated by 48px. A pale 4px rail fills purple for the active item. A gradient statistic or compact attributed quote anchors the lower text area. A translucent sticky chapter strip uses four evenly spread labels and a thin purple active underline.

**Transfer:** Group capabilities by user outcomes, not menu inventory. Keep one item expanded and tie its progress rail to the visual. Use proof relevant to the active story.

**Text style:** `accordion-heading` — Salesforce-Avant-Garde 600 · 24px/1.333 · tracking -0.012em

### Proof with contrasting scales

**Observed:** Aubergine proof uses three centered columns of 80px white numbers with short 24px captions; a compact 32px heading introduces the band. White proof instead stacks 64px black figures with small adjacent descriptions on one side of a fine divider, with review badges and supporting copy on the other.

**Transfer:** Use genuine quantified outcomes or meaningful counts; preserve the scale contrast and compact captions. When external awards do not exist, replace badges with verifiable customer endorsements rather than invented seals.

**Text style:** `stat-band` — Salesforce-Avant-Garde 700 · 80px/1.05 · tracking -0.012em

### Release and resource shelves

**Observed:** Release shelf is left-headed with supporting Arrow text link and circular previous/next controls, followed by three rounded release cards. Resource shelf uses a centered heading, four square Resource cards with 30px gutters, and 80px section padding. Captions sit 8px above 24px titles; actions anchor the bottom.

**Transfer:** Separate news from deeper learning through card width and surface treatment; use the same image-title-action hierarchy.

**Text style:** `heading` — Salesforce-Avant-Garde 700 · 32px/1.25 · tracking -0.008em

### Feature directory landscape

**Observed:** A Blue directory field carries left-aligned 32px category headings and support copy above four-column Capability tile groups. Mixed-height groups include two descriptive tiles beside pairs of short tiles. The field ends in a broad white curve, followed by a centered light italic testimonial.

**Transfer:** Use this denser variant for browsing a product's capability range, preserving consistent icons and tile actions rather than reproducing the narrative landing layout.

**Text style:** `heading` — Salesforce-Avant-Garde 700 · 32px/1.25 · tracking -0.008em

### Decision and reassurance

**Observed:** Pricing uses touching plan columns with aligned actions and one Recommended plan; below, a label column and four plan columns create a comparison matrix. Rows are roughly 45px high, with 11.2px vertical cell padding and fine rules; category headings create pauses. Soft-gray security panels pair isometric illustrations with 32px headings, then an 864px FAQ column answers objections.

**Transfer:** Match table length to meaningful decisions. Preserve the single highlighted recommendation and readable category breaks rather than forcing all information into opening cards.

### Enterprise bento chapter

**Observed:** Centered 40px heading, explanatory paragraph and blue link precede a Lavender bento panel. Its left accordion uses a progress rail, while layered product fragments occupy the right. Below, three-column combinations mix white quote cards, pale resource cards and photographic story cards. White and lavender chapter fields alternate.

**Transfer:** Use this scoped variant for longer enterprise arguments requiring security, trust and implementation detail. Let card sizes follow information weight, not a uniform mosaic.

**Text style:** `enterprise-heading` — Salesforce-Avant-Garde 700 · 40px/1.25 · tracking -0.008em

### Culture editorial and opportunity directory

**Observed:** Short left-aligned 50px opening and warm illustration lead into centered 32px editorial headings, simple three-column principle statements, alternating image/text splits, and a narrow two-column text grid divided by bottom rules. The opportunity section switches to a raised white filter bar and long tabular groups marked by Opportunity category pills.

**Transfer:** For culture-oriented content, use human activity and clear programs or principles, then move into a practical browseable directory. Retain the contrast between narrative breathing room and compact entries.

**Text style:** `conversion-heading` — Salesforce-Avant-Garde 700 · 50px/1.12 · tracking -0.012em

### Conversion and full directory ending

**Observed:** Default ending is a straight-edged Aubergine band, about 384px high, with a centered 50px white conversion line and reversed actions 32px below. Focused product, pricing and culture variants use Curved conversion band at about 370px high. Enterprise instead ends with three white 390×288px contact cards over a pale lavender gradient, a partial dimensional sculpture at left and a shallow curved exit. All variants continue into Footer directory: region and socials first, brand symbol and link columns next, then download, privacy and copyright.

**Transfer:** Keep the close expansive and decisive, with one clear next step and one lower-commitment alternative. Use contact-card choices only for a genuine assisted-sales journey; the footer remains a separate low-contrast navigation layer.

**Text style:** `conversion-heading` — Salesforce-Avant-Garde 700 · 50px/1.12 · tracking -0.012em

## Page flow

**Storyline:** Promise → product in use → capability stories → customer and numerical proof → deeper learning or decision support → closing conversion → navigable footer.

### Broad product marketing and category introduction

1. **Promise** — Centered headline, paired actions, trust strip and oversized working interface.
2. **Product demonstration** — Immersive purple chapter with choice rows beside video.
3. **Capability chapters** — Release shelf and white active-rail stories with large interfaces.
4. **Social and quantified proof** — Customer film cards, reversed numerical band and white count-and-review layout.
5. **Education** — Four editorial resources with source notes beneath claims.
6. **Closing call** — Straight purple conversion band, then full footer.

**Transfer:** Use the broad landing treatment as the default, adapting the number and order of stories to the new argument.

### Help a buyer choose and justify a plan

1. **Promise** — Centered 50px title, short reassurance and subdued trust marks.
2. **Pricing** — Four connected plan cards, one elevated recommendation.
3. **Comparison** — Long categorized matrix with plan actions retained above the rows.
4. **Reassurance** — Soft-gray illustrated information panels and ruled FAQ.
5. **Closing call** — Curved purple conversion band followed by the shared footer.

**Transfer:** Retain aligned plan anatomy and compact matrix rhythm; shorten comparison content to the new product's real differences.

### Make the capability range easy to browse

1. **Promise** — Split opening with eyebrow, 50px title, inline category anchors and product demonstration.
2. **Social proof** — Customer marks precede the category catalog.
3. **Capability catalog** — Pale-blue landscape with white mixed-height capability tiles.
4. **Proof and education** — Centered italic quote after a white arc, followed by four resource cards.
5. **Objection handling** — Narrow ruled FAQ.
6. **Closing call** — Curved purple closing band and shared footer.

**Transfer:** Use when breadth and findability matter more than a long sequential product story.

### Persuade a larger organization through depth, trust and assisted conversion

1. **Promise** — Split opening on lavender, dimensional object and four glowing chapter entry cards.
2. **Capability chapters** — Sticky pill chapter navigation, centered 40px introductions and layered bento panels.
3. **Decision support** — Two plan options and an adjacent-copy lead form on a soft gradient.
4. **Proof** — Customer quotations, award grid and three numerical outcomes.
5. **Ecosystem and comparison** — Wide pale integration panel and image/text alternative comparison.
6. **Closing call** — Three contact-choice cards over lavender with a partial dimensional object, shallow arc and shared footer.

**Transfer:** Use the lighter lavender bento variant for long sales narratives, preserving self-directed and assisted next steps.

### Connect a human organizational story to practical opportunities

1. **Invitation** — Short 50px left headline, action and warm collaborative illustration.
2. **Culture narrative** — Principle statements, illustrated alternating splits and restrained two-column program text.
3. **Opportunity discovery** — Centered introduction, filter bar, category pills and compact listing rows.
4. **Closing call** — Curved purple conversion band and shared footer.

**Transfer:** Replace organizational themes with the new organization's authentic story, keeping illustrations warm and listings functional.

## Writing

Confident and inviting, with the energy of a helpful teammate rather than an impersonal enterprise vendor. Large claims are followed quickly by concrete examples of what a person can do.

**Do not copy:** Do not reuse Slack or Salesforce names, logos, mascots, customer marks, quotes, rankings, product names, pricing, usage numbers or ROI claims. Source examples illustrate structure and tone only; new claims need their own substantiation.

- **Addressing the reader:** Use you and your for reader outcomes, we for organizational commitments, and the product name when clarifying what performs an action.
- **Rhythm:** Short, memorable headline clauses; often one sentence of support followed by a concrete action. Longer enterprise paragraphs explain mechanisms, while buttons stay brief and direct.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Bring people or work together in one plain-language outcome. | 6–11 words | “All your people and AI agents working together”<br>“One operating system for your entire workday.” |
| Support line | Connect the product's role to what the reader gains; use active verbs. | 1–2 short sentences | “[Brand] connects your team. Slackbot multiplies what they can do.” |
| Capability headline | A direct benefit or a conversational contrast instead of a feature taxonomy. | 3–8 words | “Give everyone instant context”<br>“When talking is easier than typing…” |
| Primary action | Verb-led invitation with minimal friction. | 2–3 words | “Get started”<br>“Find your plan”<br>“View Careers” |
| Reassurance | Ask the question a buyer would actually say aloud. | A complete, specific question | “Why should my company use [Brand]?” |
| Closing line | Expand the reader's sense of possibility, then offer the next step. | 5–12 words | “See all you can accomplish in [Brand]”<br>“Whatever work you do, you can do it in [Brand]” |

**Words and phrasing to use:** together; your team; get access; build; connect; work; simpler; learn more; from one place

**Avoid:** synergistic transformation; unparalleled excellence; revolutionary ecosystem; hype without a mechanism; anonymous corporate abstractions

**Rules:**

- Lead with what becomes easier for a person, then name the capability that makes it possible.
- Use conversational turns and restrained wordplay, but keep explanations literal.
- Keep title case for editorial titles and sentence case for narrative headlines; uppercase is visual treatment for actions and small labels.
- Attach attribution or methodology to numerical claims without letting it dominate the persuasive hierarchy.

## Do's and Don'ts

### Do

- Keep the default opening at 64px/68px and center it over a genuinely large product scene.
- Use 50px/56px weight 600 for major capability chapters, reserving weight 700 for focused openings and closing calls.
- Separate paired 57px actions by 8px and keep their corners at 4px.
- Maintain 1230px narrative width and a narrower 864px FAQ column.
- Give capability stories 96px vertical padding and keep their active rail visibly purple.
- Use 80px white numerals when proof sits on aubergine.
- Keep editorial resource cards square-edged even though release cards use 16px corners.
- Carry conversion into a substantial footer with quiet 14px link columns.

### Don't

- Do not turn every marketing surface into lavender; white remains the narrative default.
- Do not use rounded-pill conversion buttons merely because the switcher rows are rounded.
- Do not apply the directory's 18px practical-sans tile titles to the geometric editorial cards.
- Do not shrink all statistics into identical KPI widgets; reversed 80px figures and gradient 64px callouts have different jobs.
- Do not give every plan a filled action in the opening plan grid; highlight one recommendation.
- Do not apply the enterprise multicolor glow or dimensional sculpture to an ordinary narrative section.
- Do not put resource titles over thumbnails; keep the black title in the white card body.
- Do not make the footer a second dark conversion band; its directory is white, ruled and muted.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions animate box-shadow, color and background over 0.42s with cubic-bezier(0.165, 0.84, 0.44, 1).
- Declared resource-card hover scales to 1.05 over 0.42s with the same easing, increasing the shadow.
- Declared navigation background and shadow transition over 0.26s with cubic-bezier(0.22, 0.61, 0.36, 1).
- Product demonstrations expose pause/play controls; capability stories use active progress rails and sticky chapter navigation.

**Transfer:**

- Keep hover changes crisp but eased; reserve scaling for browseable cards, not body text.
- Tie active labels, progress and demonstration content together; provide a visible playback control for auto-running product stories.

**Unknown:**

- Full scroll choreography, switcher timing and video sequences are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 400px, 425px, 426px, 500px, 530px, 550px, 600px, 767px, 768px, 769px, 890px, 896px, 897px, 1023px, 1024px and 1280px.
- Focused-page headlines, compact headings, card headings, lead copy, proof numerals and testimonial type use the clamp formulas provided in their recipes.

**Transfer:**

- On narrow screens, retain promise → actions → working scene as the opening reading order, with the broad curve behind the media.
- Stack the active-rail copy and its corresponding demonstration rather than retaining a tiny two-column interface.
- Reduce directory and editorial column counts while preserving image-title-action anatomy; keep comparison headers associated with their plan values.

**Unknown:**

- Exact mobile navigation, card counts, stacking thresholds and horizontal table behavior are unspecified. These narrow-screen adaptations are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
