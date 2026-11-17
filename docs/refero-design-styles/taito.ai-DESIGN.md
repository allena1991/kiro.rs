# Taito.ai — everyday life, automated

## Overview

A warm off-white software style that pairs matter-of-fact grotesk typography with soft, sunlit scenes of people and city life. Near-black actions and fine warm-gray rules give the pages an orderly, practical feel, while pale interface panels float over blurred photography. It suits useful, workflow-oriented products that need to feel capable without feeling technical or cold; the overall density is airy, with compact pockets of detail.

### Essentials

- A product promise reads like plain speech rather than a poster: regular-weight Suisse Intl at 60px/1.2 with -0.025em tracking, usually broken into two or three left-aligned lines.
- The opening pairs a narrow argument with an oversized working object: a 5/7 split on a 12-column grid, 38.8px gutters, a 721px-tall photographic interface stage, and one dark action beneath the copy.
- Color belongs to life and recognizable tools, not the page chrome: #fafaf9 and #f2f1f0 dominate, #0f0e0d supplies text and actions, and subdued green, tan and blue appear inside photography. Keep the long reading canvas neutral and reserve a full-width dark field for the closing call.
- Buttons are compact rounded rectangles, not capsules: 49px height and 8px corners for the principal action; 40px height and 6px corners for navigation and secondary actions.
- Make software feel suspended in daylight: readable pale UI panels with 8px corners, a translucent 8px outer rim and a white hairline sit over defocused street or park photography. Every new landing page needs this photographic product-stage device; use a small constructed task/result panel when no finished interface exists.
- Proof uses editorial furniture rather than badges everywhere: edge-to-edge ruled rows carry 60px right-aligned numbers; testimonial text sits at 30.8px beside a tall real-world photograph.
- The ending is a complete dark room, not a detached CTA card: #0f0e0d contains a 38.5px closing line, a pale inverse action, four link columns and restrained #33312c dividing rules.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm near-black | `#0f0e0d` | `--color-ink` | text, background, action | Primary text, main actions and the closing field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Photographic dark backing | `#1f1d1a` | `--color-photo-base` | surface | Backing beneath full-bleed photographic audience cards. |
| Dark edge and hover | `#33312c` | `--color-dark-rule` | border, action | Dark-field rules and hover fill for near-black actions. |
| Warm gray text | `#524f49` | `--color-secondary` | text | Supporting paragraphs and sentence-case section labels. |
| Muted text | `#6e6a65` | `--color-muted` | text | Trial reassurance, small metadata and secondary control labels. |
| Subtle label gray | `#8f8b85` | `--color-subtle` | text | Footer category headings and low-priority footer metadata. |
| Pale dark-field text | `#cccac6` | `--color-dark-support` | text | Supporting copy over dark fields and photographic cards. |
| Light edge | `#e5e5e3` | `--color-rule` | border, surface | One-pixel grid edges, section rules and inverse-action hover fill. |
| Warm pale gray | `#f2f1f0` | `--color-wash` | surface, background | Media backing, icon squares, quote panels and small hover fills. |
| Off-white | `#fafaf9` | `--color-canvas` | background, surface, text | Default canvas, interface panels and inverse text/actions on dark fields. |
| Tile white | `#ffffff` | `--color-white` | surface, border | Small floating icon tiles and the light edge of the glass rim, not the default page background. |

## Typography

- **Suisse Intl-99e21c928808656c** — All marketing headings, body text, labels and controls. A regular-weight neo-grotesk with straightforward proportions and open, unfussy forms. If unavailable, use **Inter**. Use 400 and 500; preserve the negative display tracking and deliberate line breaks. Font stack: "Suisse Intl-99e21c928808656c", "Inter", Arial, -apple-system, system-ui, sans-serif.
- **ui-monospace** (only for technical setup sections) — Copyable endpoint or code text. Functional fixed-width text, never a marketing display face. Font stack: "ui-monospace", "Roboto Mono", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Suisse Intl-99e21c928808656c | 400 | 60px | 1.2 | -0.025em | Default hero promise and pricing-page headline. |
| statistic | Suisse Intl-99e21c928808656c | 400 | 60px | 1 | -0.025em | Large numbers at the right of ruled proof rows. |
| heading | Suisse Intl-99e21c928808656c | 400 | 38.5px | 1.2 | -0.015em | Section leads and the closing call. |
| quote | Suisse Intl-99e21c928808656c | 400 | 30.8px | 1.25 | normal | Long customer quotations, with natural wrapping and no negative tracking. |
| card-heading | Suisse Intl-99e21c928808656c | 400 | 24.7px | 1.2 | normal | Titles beneath media-led benefit cards and names in people grids. |
| faq-question | Suisse Intl-99e21c928808656c | 400 | 24.7px | 1.5 | normal | Accordion question text. |
| body | Suisse Intl-99e21c928808656c | 400 | 19.8px | 1.5 | normal | Hero support, section introductions, expanded FAQ answers and sentence-case eyebrows. |
| feature-heading | Suisse Intl-99e21c928808656c | 400 | 19.8px | 1.25 | normal | Compact capability titles and statistic descriptions. |
| action | Suisse Intl-99e21c928808656c | 500 | 19.8px | 1.5 | normal | Main and inverse CTA labels; emphasized inline links. |
| photo-title | Suisse Intl-99e21c928808656c | 500 | 19.8px | 1.2 | normal | Short white title within full-bleed photo cards. |
| small-body | Suisse Intl-99e21c928808656c | 400 | 15.9px | 1.5 | normal | Card descriptions, attribution roles and footer links. |
| small-action | Suisse Intl-99e21c928808656c | 500 | 15.9px | 1.5 | normal | Navigation links, compact CTA labels and text links. |
| label | Suisse Intl-99e21c928808656c | 500 | 15.9px | 1.2 | normal | Footer category headings and compact panel headings. |
| caption | Suisse Intl-99e21c928808656c | 400 | 12.7px | 1.5 | normal | Trial reassurance and editorial date/category metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience-specific landing pages with a full-width photograph | wide-display | Suisse Intl-99e21c928808656c | 400 | 74.8px | 1.2 | -0.025em | Larger two-line promise above a broad photographic scene. |
| pricing pages | price | Suisse Intl-99e21c928808656c | 500 | 38.5px | 1.2 | -0.015em | Plan price and billing unit on one line. |
| technical setup sections | code | ui-monospace | 400 | 15.9px | 1.625 | normal | Copyable connection endpoint. |

**Notes:**

- Regular 400 weight carries almost the entire hierarchy. Reserve 500 for actions, small labels, photographic-card titles and prices; do not substitute bold display type.
- Tracking tightens only on the two display sizes, section headings and large statistics. Body, quotes and card titles retain normal tracking.
- Eyebrows are ordinary sentence-case body text rather than tiny uppercase annotations. Match their color to supporting copy.

## Layout

**Density:** Airy across sections, compact within controls and product panels; long passages are broken by fine rules rather than frequent boxed cards.

### Spacing

| Value | Use |
| --- | --- |
| 9.9px | Small icon/text gaps and feature-title-to-description separation. |
| 14.8px | Media-card title-to-copy gaps and compact horizontal action padding. |
| 19.8px | Eyebrow-to-heading and heading-to-support gaps; FAQ vertical padding and principal action horizontal padding. |
| 29.7px | Grouped panel content and closing-row gaps. |
| 38.8px | Container side padding, principal grid gutter and capability-cell padding. |
| 39.2px | Stat-row vertical padding and section-content internal separation. |
| 39.6px | Media-to-card-caption separation. |
| 58.6px | Testimonial panel padding and footer navigation vertical padding. |
| 59.4px | Section header-to-grid separation. |
| 117.2px | Major section and footer vertical padding. |

### Containers and grids

- **container**: max width 1500px · side padding 38.8px. Centered outer container; at 1440px it yields about 1362px of usable content.
- **editorial grid**: 12 columns · gap 38.8px. Underlying grid. Default split sections allocate five columns to text and seven to media, reversing sides between chapters.
- **media card grid**: 3 columns · gap 38.8px. Three 428px media cards across the desktop content area.
- **capability matrix**: 3 columns · gap 0px. Contiguous bordered cells; no gaps, with rules sharing edges.
- **reading measure**: max width 608px. Limit extended supporting prose, especially FAQ answers.
- **footer columns**: 4 columns · gap 39.2px. Equal-width link categories beneath the closing row.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media and grid outline | 4px |
|  | compact controls | 6px |
|  | principal buttons and UI panels | 8px |
|  | tags | 9999px (pill) |
| people and attribution portraits | portrait | 50% |
| technical setup sections | endpoint panel | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating panel | `0px 1px 2px 0px rgba(0, 0, 0, 0.05)` | Pale product panels and floating icon tiles, used together with a glass rim rather than a pronounced drop shadow. |
| technical setup sections | endpoint inset | `0px 10px 15px -3px rgba(0, 0, 0, 0.1), 0px 4px 6px -4px rgba(0, 0, 0, 0.1)` | Copyable endpoint field nested inside a pale outer shell. |

### Surfaces

#### Canvas · level 0

**Use:** Default reading field.

**CSS:** `background: #fafaf9; color: #0f0e0d`

**Observed:** Long off-white sections separated by light top rules.

**Transfer:** Let the page itself be the default card surface; box only meaningful groups.

#### Pale backing · level 1

**Use:** Media stages, icon squares and testimonial panels.

**CSS:** `background: #f2f1f0; border-radius: 4px`

**Observed:** Warm gray, barely darker than the page; frequently covered by photography.

**Transfer:** Use this backing to group related content without introducing a chromatic brand panel.

#### Ruled grouping · level 1

**Use:** Capability and use-case matrices.

**CSS:** `border: 1px solid #e5e5e3; border-radius: 4px; overflow: hidden`

**Observed:** Cells share the page background, with fine internal divisions and no cast shadow.

**Transfer:** Use contiguous cells rather than an array of independent floating cards.

#### Floating interface · level 2

**Use:** Product proof over photography.

**CSS:** `background: #fafaf9; border-radius: 8px; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); position: relative`

**Observed:** An outer translucent white rim and thin bright edge visually lift the panel. The hero interface extends beyond the right and bottom edges of its photographic stage.

**Transfer:** Add the glass rim as a separate layer so it does not reduce the panel's readable area.

#### Dark closing field · level 0

**Use:** Closing CTA and footer.

**CSS:** `background: #0f0e0d; color: #fafaf9`

**Observed:** One continuous full-width field with warm pale supporting text and dark-gray rules.

**Transfer:** Carry the inverse theme through the whole footer rather than ending the dark treatment after the CTA.

#### Photographic legibility veil · level 1

**Use:** Bottom text overlay on full-bleed photo cards.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(29, 29, 29, 0.9)); position: absolute; bottom: 0px; height: 75%; width: 100%`

**Observed:** The gradient darkens the bottom of the image without tinting the upper portrait.

**Transfer:** Keep photo detail visible above the text; do not dim the entire photograph uniformly.

## Components

### Navigation

**Use:** Shared top bar.

**CSS:** `background: #fafaf9; border-bottom: 1px solid #e5e5e3; height: 79px; position: relative`

**Text style:** `small-action` — Suisse Intl-99e21c928808656c 500 · 15.9px/1.5

**Observed:** Brand mark at left, centered menu and right-aligned login plus Compact button. The inner layout uses 1fr auto 1fr. Menu controls have 6px corners and 14.8px horizontal padding.

**States:** Declared: hover menu background #f2f1f0 and text #33312c; active transform scale(0.97).

**Transfer:** Keep the navigation quieter and smaller than the hero action.

### Primary button

**Use:** Default high-intent conversion action.

**CSS:** `display: inline-flex; align-items: center; background: #0f0e0d; color: #fafaf9; height: 49px; padding: 0px 19.8px; border-radius: 8px`

**Text style:** `action` — Suisse Intl-99e21c928808656c 500 · 19.8px/1.5

**Observed:** A short text label with no decorative trailing arrow. Width follows label length.

**States:** Declared: hover background-color #33312c; active transform scale(0.97).

### Compact button

**Use:** Header conversion action.

**CSS:** `display: inline-flex; align-items: center; background: #0f0e0d; color: #fafaf9; height: 40px; padding: 0px 14.8px; border-radius: 6px`

**Text style:** `small-action` — Suisse Intl-99e21c928808656c 500 · 15.9px/1.5

**Observed:** The same rectangular language as Primary button at the smaller navigation scale.

**States:** Declared: hover background-color #33312c; active transform scale(0.97).

### Inverse button

**Use:** Conversion action on the dark closing field.

**CSS:** `display: inline-flex; align-items: center; background: #fafaf9; color: #0f0e0d; height: 49px; padding: 0px 19.8px; border-radius: 8px`

**Text style:** `action` — Suisse Intl-99e21c928808656c 500 · 19.8px/1.5

**Observed:** Placed at the right of the closing copy, not centered underneath it on desktop.

**States:** Declared: hover background-color #e5e5e3; active transform scale(0.97).

### Secondary button

**Use:** Supporting trust or contact action.

**CSS:** `display: inline-flex; align-items: center; color: #0f0e0d; border: 1px solid #e5e5e3; height: 40px; padding: 0px 14.8px; border-radius: 6px`

**Text style:** `small-action` — Suisse Intl-99e21c928808656c 500 · 15.9px/1.5

**Observed:** Outline treatment against the page canvas; sometimes includes a small arrow on contact actions. Pricing uses an outlined 49px variant for the nonpreferred billing choice.

**States:** Declared: hover background-color #f2f1f0; active transform scale(0.97).

### Capability matrix

**Use:** Compact overview of functions or use cases.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); border: 1px solid #e5e5e3; border-radius: 4px; overflow: hidden`

**Text style:** `feature-heading` — Suisse Intl-99e21c928808656c 400 · 19.8px/1.25

**Observed:** Cells have 38.8px padding, a pale icon square, a generous gap before the title and small-body description. Internal hairlines make a single shared table-like object. Use-case cells add small category pills above the title and tool tags with a corner arrow below.

**Transfer:** Choose a small set of comparable capabilities and keep the cell content hierarchy consistent.

### Photo card

**Use:** Audience or outcome routes with a human context.

**CSS:** `background: #1f1d1a; border-radius: 4px; overflow: hidden; position: relative; aspect-ratio: 2 / 3`

**Text style:** `photo-title` — Suisse Intl-99e21c928808656c 500 · 19.8px/1.2

**Observed:** Full-bleed human photography, Photographic legibility veil, bottom-left eyebrow/title/description and a near-black circular plus at top right. Desktop cards are 428px by 642px with 38.8px text insets.

**Transfer:** Photograph the people or situations served by the new product, not generic abstract avatars.

### Testimonial panel

**Use:** Substantial customer proof.

**CSS:** `display: flex; flex-direction: column; gap: 39.2px; padding: 58.6px; border-radius: 4px; background: #f2f1f0`

**Text style:** `quote` — Suisse Intl-99e21c928808656c 400 · 30.8px/1.25

**Observed:** A tall contextual photograph occupies one third of the composition; the remaining two thirds hold a logo, substantial quotation, story link and bottom attribution with a small square headshot. Carousel controls are 40px pale circles at lower right.

**Transfer:** Keep the quote readable as a paragraph rather than a giant decorative pull quote.

### FAQ row

**Use:** Objection handling.

**CSS:** `display: flex; align-items: flex-start; justify-content: space-between; gap: 19.8px; padding: 19.8px 0px`

**Text style:** `faq-question` — Suisse Intl-99e21c928808656c 400 · 24.7px/1.5

**Observed:** Native details/summary construction. Closed rows are about 78px high, with a right-edge plus and light horizontal separators. Answers use body typography and a constrained reading measure.

**Transfer:** Start closed; reveal useful prose, not another card stack.

### Statistic row

**Use:** Quantified proof.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 39.6px; padding: 39.2px 0px; border-top: 1px solid #e5e5e3`

**Text style:** `statistic` — Suisse Intl-99e21c928808656c 400 · 60px/1 · tracking -0.025em

**Observed:** A short feature-heading description and small source-information icon sit on the left; the large number is flush right, with units kept on the same line. Rows are about 139px high.

**Transfer:** Use a sourced, meaningful metric with enough room for a readable unit; let alignment supply the drama.

### Closing footer

**Use:** Final conversion and navigational ending.

**CSS:** `background: #0f0e0d; color: #fafaf9; padding: 117.2px 38.8px`

**Text style:** `small-body` — Suisse Intl-99e21c928808656c 400 · 15.9px/1.5

**Observed:** The top row uses heading and body typography with Inverse button at right. A dark rule separates it from four link columns; category labels are subtle gray and links pale. Another rule frames copyright at left and two small social marks at right. The desktop ending occupies about 885px.

**Transfer:** Keep the call, links and final metadata in the same dark field.

### Endpoint field

**Only for:** technical setup sections

**Use:** Copyable configuration value.

**CSS:** `background: #fafaf9; border: 1px solid #e5e5e3; border-radius: 12px; overflow: clip; box-shadow: 0px 10px 15px -3px rgba(0, 0, 0, 0.1), 0px 4px 6px -4px rgba(0, 0, 0, 0.1)`

**Text style:** `code` — ui-monospace 400 · 15.9px/1.625

**Observed:** A pale shell with 12px top corners and 20px bottom corners contains a small label and Copy action above the inset field. Code has 19.8px padding. Three numbered prose steps follow below.

**Transfer:** Reserve this stronger shadow and rounding for a small technical utility, not every content card.

## Imagery and graphics

### Daylight product stage

**Use:** Signature hero and large capability demonstrations.

**Observed:** Softly defocused pedestrian streets, crossings and tree-lined paths form large rectangular backdrops. Colors are washed sage, cream, gray-blue and muted tan, with daylight highlights. Sharp pale software panels float centrally over the blur; the hero shows an oversized application window clipped at the right and bottom while later scenes isolate one task or result.

**Transfer:** Use a similarly sunlit environment relevant to the user's daily life. If no product UI is available, construct one credible task panel with a title, three or four result rows and a small prompt bar; it must remain readable over the photographic ground.

**Build:** Use a cover-fitted street or park photo inside a 4px-radius overflow-hidden stage. Soften the photo with blur(4px) and a light rgba(250,250,249,0.15) wash as design guidance. Layer an off-white 8px-radius panel above it. Add a pseudo-element inset -8px with an 8px rgba(255,255,255,0.25) border and 16px outer radius, then a second 1px white edge masked from opaque at left to transparent at right. Use only a 0px 1px 2px rgba(0,0,0,0.05) shadow; preserve crisp dark panel text.

### Working-life photography

**Use:** Photo cards, testimonials and editorial thumbnails.

**Observed:** Natural-light offices, workshops and informal conversations; people look at each other or at their work, not directly into a glossy stock-photo lens. Tall 2:3 framing supports audience and quote sections; editorial thumbnails use landscape framing. The palette remains muted and believable rather than monochrome.

**Transfer:** Choose candid, context-rich scenes with soft window light and subdued clothing. Use a dark lower veil only when text overlays the photograph.

### Floating tool constellation

**Only for:** integration and ecosystem pages

**Use:** Alternative split-hero object.

**Observed:** A near-black 128px central tile is surrounded by three rows of white 96px logo tiles on a pale gray field; 32px spaces separate the tiles. The middle row is wider and edge tiles fade softly into the backing. Recognizable tool marks provide the localized bright color.

**Transfer:** Use actual compatible tool identities or meaningful capability symbols. Keep the host product dominant and the surrounding marks visually lighter.

**Build:** Construct three centered flex rows with 32px gaps. Put a 128px dark rounded tile in the middle row; neighboring tiles are 96px white squares with 8px corners, a translucent white rim and subtle panel shadow. Apply a pale lateral mask to the whole constellation, keeping the center fully opaque. Add a small pill at the bottom edge of the central tile.

### Civic life scene

**Only for:** company and mission pages

**Use:** Non-product hero photography.

**Observed:** A tall overhead photograph of a busy pedestrian crossing in warm low-angle sunlight fills the right seven columns. Long shadows and crosswalk stripes create order without a UI overlay.

**Transfer:** Use a human-scale public scene that suggests coordinated activity; retain warm light, real people and architectural geometry.

### People portraits

**Only for:** company and attribution sections

**Use:** Team grid and customer attribution.

**Observed:** Team portraits are small circular cutouts against pale gray, not large rectangular biography photographs. Three-column team entries have generous space and faint vertical divisions; each pairs a name, role and compact biography. Customer attribution uses a much smaller square portrait.

**Transfer:** Keep people recognizable, evenly scaled and consistently lit; let names and experience carry the profile rather than oversized portrait cards.

### Icons

**Observed:** Simple rounded-stroke SVG line icons, normally 16px, 20px or 24px with 2px strokes and round caps. Capability icons sit in pale squares; trust rows include larger seal-like line drawings. Tool logos retain their own fills and colors.

**Transfer:** Choose a consistent Lucide-like outline family for navigation and capabilities. Use authentic integration marks only inside tool tags or product scenes; avoid using multicolored pictograms as marketing decoration.

## Section recipes

How recurring sections are built.

### First screen: Photographic product opening

**Observed:** A 79px light Navigation bar sits above a split hero. Inside the 1500px container the left five columns hold a small story link, a two-line display promise about 485px wide, a warm-gray support paragraph, Primary button and a caption reassurance. The right seven columns are a roughly 779px by 721px Daylight product stage, starting immediately beneath the navigation. Its layers are pale backing, blurred street photograph, then a sharp oversized application window with a translucent rim; the window overflows into the right and bottom boundaries. The copy sits lower than the media's top, leaving breathing room above the promise. Within the first 900px the whole headline, support, action, reassurance, main interface and a low customer-logo strip are visible; the first explanatory chapter begins below.

**Transfer:** Use one concrete promise and one large example of work completed. Without finished UI, use the constructed task/result panel described in Daylight product stage, large enough to compete with the text. Technical pages can replace the photo stage with Floating tool constellation; company pages use Civic life scene. Audience-specific pages open with a wider 74.8px headline beside support and CTA, followed by a full-width photograph. Pricing pages replace the media object with two restrained billing columns beneath a split headline/support row.

**Avoid:** Do not center the default hero, reduce the product to a small detached card, or use a glowing abstract orb instead of a daylight working scene.

**Text style:** `display` — Suisse Intl-99e21c928808656c 400 · 60px/1.2 · tracking -0.025em

### Section heading pair

**Observed:** A light top rule and 117.2px vertical padding establish each chapter. Sentence-case body-size eyebrow comes first, with 19.8px before a regular heading. Support either follows with another 19.8px gap in a roughly 608px measure or aligns to the right of the heading on the editorial grid. A 59.4px gap leads into the section's object.

**Transfer:** Use the eyebrow to locate the subject and the heading to state an outcome, not to repeat the same phrase.

**Text style:** `heading` — Suisse Intl-99e21c928808656c 400 · 38.5px/1.2 · tracking -0.015em

### Media-led benefit trio

**Observed:** Three columns with 38.8px gutters contain 4:3 photographic product scenes about 428px by 321px. Card-heading text follows 39.6px below the media, then small-body copy after 14.8px. The media has 4px corners; the text sits directly on Canvas.

**Transfer:** Give each benefit one small, concrete visual proof; do not wrap the image and text in another raised card.

### Alternating capability chapter

**Observed:** The editorial grid pairs a seven-column Daylight product stage with a five-column text stack. Eyebrow, heading and body introduce three or four compact feature rows with line icons and bottom rules. Adjacent chapters reverse the media and text sides. Stages are nearly square, around 779px wide, and the UI remains centered with clear photographic margins.

**Transfer:** Demonstrate one useful mechanism per chapter, then explain its sub-benefits in the nearby rows.

### Contiguous capability overview

**Observed:** A Section heading pair leads into Capability matrix. Three columns by two rows carry icons, titles and compact descriptions. Use-case libraries extend the same structure to more rows and add tags; a principles section uses four cells with small numbered labels instead of icons.

**Transfer:** Keep the grid a finite, comparable set rather than mixing testimonials, prices and capabilities in one bento layout.

### Human proof spread

**Observed:** A tall contextual photograph and Testimonial panel share equal height, about 642px. The image takes four grid columns and the quote takes eight. A customer mark precedes the quotation, and attribution stays near the bottom.

**Transfer:** Pair a specific customer experience with a relevant real-world image; shorten the quotation only enough to preserve its natural voice.

### Trust ledger

**Observed:** Five columns of intro copy and Secondary button face a seven-column stack of four trust rows. Each has a line emblem at left, body-size title and a subdued Details label at far right. A pricing variant instead places compact icon-and-label proofs below a narrow introduction.

**Transfer:** Turn verified assurances into a readable ledger; adapt the proof categories to the new product.

### Ruled numerical proof

**Observed:** A Section heading pair precedes a full-width stack of Statistic rows. The number is isolated at far right in statistic typography, while its explanation and source-information control stay at left.

**Transfer:** Use a handful of consequential metrics rather than a dense dashboard; retain units and provenance links for each claim.

### FAQ to dark close

**Observed:** FAQ row components sit under a heading with about 59.4px separation. Closed questions and plus controls are visible; long answers reveal within the same row structure. The light section gives way directly to Closing footer: heading and body at left, Inverse button at right, a rule, four navigation columns and a final ruled metadata row.

**Transfer:** Answer the final adoption objections, then finish with a short outcome-led invitation in the complete inverse footer.

### Open editorial links

**Only for:** audience-specific and resource-led pages

**Observed:** Three landscape editorial thumbnails are about 402px by 226px with 4px corners; wide gutters and faint vertical rules separate the columns. Titles use approximately 19.8px type, descriptions use small-body, and category/date lines use caption. Text is directly on the canvas.

**Transfer:** Close an audience story with useful related reading, not a second sales-card grid.

### Company story and people

**Only for:** company pages

**Observed:** A centered story chapter narrows the prose and follows it with a rule and two investor marks. A four-column ruled principles grid uses numbered labels. The people chapter returns to a horizontal heading pair and a three-column grid of circular portraits, names, roles and biographies, including a recruiting entry.

**Transfer:** Use this variant for institutional credibility, keeping people and narrative primary rather than inserting product demonstrations into every block.

### Plain pricing and comparison

**Only for:** pricing pages

**Observed:** The opening headline and support sit side by side above a light rule. Two billing columns share a vertical division; the preferred choice uses Primary button, the alternative an outlined action. Prices use price typography rather than display. Later, a three-column comparison table places category at left, muted status-quo text in the middle and darker product text at right; horizontal rules span all columns.

**Transfer:** Make commercial differences explicit in text; keep emphasis monochrome and do not invent a colored recommended-plan card.

## Page flow

**Storyline:** Promise → visible work or context → practical capabilities → human or quantified proof → trust and adoption detail → final invitation.

### Broad product marketing landing page

1. **promise and product demonstration** — Split photographic interface hero, one action and a compact customer-logo strip.
2. **value proposition** — Horizontal heading pair and three media-led benefits.
3. **capability chapters** — Contiguous overview followed by alternating text-and-product scenes.
4. **audience relevance** — Three tall photographic route cards.
5. **social proof** — Large customer quote spread.
6. **trust and ecosystem** — Trust ledger and three integration scenes.
7. **quantified proof** — Ruled right-aligned metrics.
8. **objection handling and closing call** — FAQ rows followed by the complete dark CTA/footer.

**Transfer:** Adapt the length and order to the product while retaining the photographic working object, editorial proof and dark ending.

### Integration or technical use-case landing page

1. **promise** — Split hero with tool constellation.
2. **capability discovery** — Nine contiguous use-case cells with category and tool tags.
3. **mechanism and trust** — Short explanatory intro and three aligned principles.
4. **adoption detail** — Copyable endpoint shell and three numbered steps.
5. **objection handling and closing call** — Compact FAQ followed by the shared dark ending.

**Transfer:** Replace protocols and tools with relevant technical concepts; retain the strong visual object and plain setup language.

### Audience-specific solution story

1. **audience promise** — Wide two-line headline beside support and action above a broad human photograph.
2. **product demonstration** — Activity panel over workplace photography beside ruled use-case rows.
3. **social proof** — Tall customer photo and substantial quote.
4. **capability overview** — Six-cell matrix with small supporting actions.
5. **trust** — Shared trust ledger.
6. **further exploration and closing call** — Three editorial links followed by the shared dark ending.

**Transfer:** Use the audience's actual work constraints and imagery without changing the neutral visual system.

### Company credibility and recruiting

1. **mission promise** — Split headline and overhead civic-life photograph.
2. **origin and external proof** — Centered narrative, rule and investor marks.
3. **principles** — Four ruled numbered cells.
4. **human credibility** — Heading pair and three-column people grid ending with a recruiting entry.
5. **closing call** — The shared dark CTA/footer, not a special corporate ending.

**Transfer:** Use an authentic origin, concrete principles and concise experience-led bios.

### Commercial explanation and decision support

1. **pricing promise** — Split headline/support row with two billing options below.
2. **inclusion proof** — Six-cell capability matrix and compact external marks.
3. **comparison** — Long ruled three-column table.
4. **trust** — Narrow security introduction with compact icon proofs.
5. **objection handling** — Extended FAQ covering commercial and adoption concerns.
6. **closing call** — Shared dark CTA/footer.

**Transfer:** Explain the actual billing model directly; show inclusion and tradeoffs rather than escalating plan-card decoration.

## Writing

Direct, useful and confidently understated. Technical ideas are explained through everyday work and concrete outcomes, with human warmth carried by the examples rather than jokes or exuberance.

**Do not copy:** Do not reuse Taito.ai names, customer or investor identities, logos, quotations, proprietary UI, claims, certifications, prices or statistics. Source examples illustrate voice only; all new product assertions need their own support.

- **Addressing the reader:** Address the reader as you or your team. Use we for the company perspective and the product name when explaining a mechanism; emphasize the reader's work rather than the vendor's ambition.
- **Rhythm:** Short, sentence-case headlines often contrast two states or use two clipped sentences. Supporting paragraphs explain a mechanism in one to three sentences; small feature copy is concise but specific. Periods, commas, em dashes and middle-dot metadata appear; exclamation marks do not drive the voice.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A plain imperative joining the work to a better operating state. | 5–9 words | “Run people ops on autopilot” |
| Section heading | Outcome contrast, or a pair of short declarative sentences. | 5–10 words | “Grow your team, not your people ops overhead”<br>“Set it up once. Run forever.”<br>“One tier. Everything inside.” |
| Supporting line | Name the task, explain how it is handled, then say what effort disappears. | 1–3 sentences | “Time-off requests, attendance, contracts, and pre-payroll run automatically. Your team never has to follow up on it.” |
| Primary action | Plain verb plus the concrete next step. | 2–4 words | “Start free trial” |
| Reassurance | Two practical adoption facts separated by a middle dot. | 6–10 words | “14-day free trial · No card required” |
| Closing line | Invite the reader to see the promised operating state. | 5–8 words | “See what autopilot looks like.” |

**Words and phrasing to use:** handled; from day one; built in; automatically; one place; live data; no manual steps; your team

**Avoid:** revolutionary; game-changing; supercharge; unlock limitless potential; magic; AI-powered everything

**Rules:**

- Lead with the work or result; put technology names in the explanation when needed.
- Make contrasts concrete: a manual step versus a completed result, not a vague before-and-after emotion.
- Explain limits and setup honestly in FAQ answers.
- Keep labels sentence case and feature names literal.
- Use numbers only when they make a substantiated decision easier.

## Do's and Don'ts

### Do

- Use 400-weight display type with -0.025em tracking and 1.2 line height.
- Keep the 38.8px desktop side padding and align rules, headings and grids to it.
- Preserve the pale canvas through long chapters, with 117.2px vertical padding at major boundaries.
- Give the interface readable off-white panels and an 8px translucent rim over daylight photography.
- Use 4px corners for media and matrix outlines, reserving 8px for primary actions and interface panels.
- Keep large proof numbers on the right with 1 line height and explanatory text on the left.
- Carry #0f0e0d through the complete footer with #33312c rules.
- Use natural full-color human scenes with subdued light rather than a completely monochrome image treatment.

### Don't

- Do not use a saturated brand color for a CTA, section fill or headline gradient; page chrome is neutral.
- Do not make every action a pill; main buttons have 8px corners and compact controls 6px.
- Do not turn section eyebrows into tracked uppercase microtype; they share the approximately 19.8px body scale.
- Do not give capability cells separate shadows or large gaps; the overview is a single ruled matrix.
- Do not make media corners 24px or 32px; the outer photographic framing stays at 4px.
- Do not enlarge customer quotes to the 60px hero scale; their 30.8px paragraph rhythm is intentional.
- Do not replace the integrated footer with a floating rounded conversion card.
- Do not apply the technical endpoint's deeper shadow to ordinary marketing content.
- Do not fill every chapter with tool logos; their localized color belongs to ecosystem scenes and tags.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color and background-color transitions at 0.2s cubic-bezier(0.23, 1, 0.32, 1) and transform at 0.16s with the same curve; active scale is 0.97.
- Quote navigation controls declare a 2px solid near-black focus-visible outline with 2px offset.
- A customer-logo marquee declares 60s linear infinite motion.
- Hero words use individual overflow-hidden wrappers and vertical transforms; supporting content uses opacity and vertical translation classes, including reduced-motion alternatives.
- A prompt caret declares a 1s steps(2) repeating blink.

**Transfer:**

- Use the measured short action transitions rather than springy overshoot.
- Keep a logo strip as a low-height supporting rhythm, not a competing hero.
- Preserve static readability when reduced motion is requested; the photograph and UI remain the main visual device.

**Unknown:**

- Hero reveal durations and sequencing, carousel autoplay and the actual interactive demo timing are not established.

### Responsive

**Observed:**

- The centered desktop navigation and right-side CTA declare visibility from a 1200px minimum width.
- Capability matrices declare one-, two- and three-column variants; footer navigation declares one-, two- and four-column variants.
- Split media chapters declare a text-first stacked order at narrow widths, and photographic route cards declare a landscape small-screen aspect ratio before the desktop 2:3 ratio.

**Transfer:**

- On narrow screens stack promise, action and product stage in that order. Keep the panel large and readable instead of shrinking a full desktop application window.
- Progressively reduce matrix and footer column counts while preserving the shared rules and neutral backing.
- Let photo-card text keep its inset and contrast when the framing changes to landscape.

**Unknown:**

- Exact mobile gutters, type sizes, container-query thresholds and mobile menu behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
