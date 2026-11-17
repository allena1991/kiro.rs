# INK — cinematic gallery restraint

## Overview

An airy, image-led style that pairs a white editorial canvas with warm charcoal grotesk typography and muted stone labels. Cinematic photography and highly finished three-dimensional product scenes supply almost all the color, ranging from dark studio lighting to saturated campaign backdrops. The feeling is cultured, technically assured and reductive, well suited to design-led products, creative technology and portfolios with strong visual proof.

### Essentials

- The opening reads as an oversized editorial paragraph, not a slogan poster: regular 60px Good Sans with 1.135 line height and normal tracking, a stone-colored promise followed immediately by charcoal explanation.
- A deliberately empty upper field gives the statement authority: 32px side margins, text beginning after 320px of top space, then 128px before a full-width moving-image stage.
- Visual proof behaves like an art catalogue: square-edged image pairs alternate 776px and 536px widths at a 1440px viewport, separated by 64px; captions sit 32px below and rows breathe with 160px separation. Include this unequal image pairing even for software, using a composed interface view beside a detail.
- Color belongs to the pictures, not the interface: white canvas, #2e2a2b text, #afab9f labels and #e4e1d7 hairlines surround rich photography. Keep controls unfilled; the category-return variant is a 1px outline pill with 100px radius and 2px 12px padding.
- Navigation is reduced to a small line-built identity at the upper left and a muted olive circular menu cue at the upper right; its invisible interaction area is 160px by 64px rather than a conventional filled menu button.
- The close is a contact directory rather than a sales banner: an isolated thin upward arrow, a 1px rule, then two spacious columns of 22.1px labels and contact details with 64px top padding. Preserve this understated closing device on new pages.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive menu cue | `#596152` | `--color-menu` | accent, action | Small circular navigation cue, not a section fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text | Default page canvas and reversed text. |
| Warm hairline | `#e4e1d7` | `--color-rule` | border | Footer separator and editorial row dividers. |
| Stone label | `#afab9f` | `--color-muted` | text | Introductory promise, inline category names, directory labels and slide counts. |
| Warm charcoal | `#2e2a2b` | `--color-ink` | text, border, action, link | Primary text, arrows, outline controls and hover fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company credibility sections | Dark proof field | `#1d1d20` | `--color-proof` | background | Full-width reversed logo field. |

## Typography

- **Good Sans** — All editorial text, headings, captions, directory labels and controls. Open, rounded contemporary grotesk with restrained geometric construction; the visual hierarchy relies on size rather than bold weights. If unavailable, use **DM Sans**. Use weight 400 and normal tracking; tune line wrapping to keep the broad editorial measure. Font stack: "Good Sans", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Good Sans | 400 | 60px | 1.135 | normal | Opening promise and large explanatory paragraph; the two lines share one type recipe and differ only in color. |
| caption | Good Sans | 400 | 22.1px | 1.6 | normal | Image titles, directory labels and medium editorial support copy. |
| contact-link | Good Sans | 400 | 22.1px | 24px | normal | Directory actions, with underline decoration controlled separately from the text recipe. |
| body | Good Sans | 400 | 18px | 1.75 | normal | Small section labels, contextual navigation, person roles and outlined return controls. |
| browse-link | Good Sans | 400 | 18px | 1 | normal | Compact text-and-arrow browsing action above the directory. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company principles sections | principle-title | Good Sans | 400 | 92px | 1.086 | normal | Single-word editorial chapter titles, paired with much smaller support text. |
| category, people and company pages | editorial-intro | Good Sans | 400 | 40px | 1.2 | normal | Multiline introductory statement spanning about two thirds of the content width. |

**Notes:**

- Keep every main text role at weight 400 and normal tracking; contrast comes from size, width and stone-versus-charcoal color rather than weight.
- The opening explanation is display-sized rather than a small body paragraph. On informational page types the whole opening drops to the editorial-intro recipe.
- Testimonials use the same broad, regular-weight visual register as the main display, with a much smaller attribution. Keep the quote on a wide measure rather than styling it as italic body copy.

## Layout

**Density:** Airy: large empty fields separate concise text from carefully framed media, while captions remain closely attached to their images.

### Spacing

**Spacing system:**

- **grid** 16px — Dominant layout rhythm; use its multiples for gutters, image-caption space and section separation.

| Value | Use |
| --- | --- |
| 16px | Inline icon spacing. |
| 32px | Page side inset and image-to-title spacing. |
| 40px | Directory group bottom spacing; a local exception to the main grid. |
| 64px | Gallery gutter, directory top padding and principle-row separation. |
| 128px | Opening-to-media separation and informational section bottom padding. |
| 160px | Gallery row breathing room. |
| 256px | Informational opening top space and transition from showcase to gallery. |
| 320px | Default landing introduction top space. |

### Containers and grids

- **page-container**: max width 1920px · side padding 32px. Wide desktop canvas; content nearly fills the viewport rather than sitting in a narrow central column.
- **unequal-gallery**: 2 columns · gap 64px. At 1440px, pair 776px and 536px media widths inside a 1376px content field. Alternate the wide side from row to row; align the pair at the top and let image aspect ratios create different caption baselines.
- **directory-columns**: 2 columns · gap 64px. Two 656px content columns at 1440px, with newsletter/social/legal on the left and practical contact groups on the right.
- **portrait-grid** (only for people directories): 3 columns · gap 64px · side padding 32px. Three equal 416px square portrait areas at 1440px, with 128px between person items vertically.
- **intro-measure** (only for category, people and company pages): max width 917px. Informational statements use about two thirds of the desktop content field, aligned to its left edge.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media | 0px |
|  | menu-cue | 50% |
| category browsing | return-pill | 100px |

## Surfaces and depth

### Surfaces

#### Editorial canvas · level 0

**Use:** Default page ground, including image galleries and contact directory.

**CSS:** `background: #ffffff; color: #2e2a2b`

**Observed:** Flat and untextured, with no raised cards, shadows or decorative panel fills.

**Transfer:** Let the pictures carry the material richness; leave editorial content on the shared canvas.

#### Ruled directory · level 0

**Use:** Final practical contact area.

**CSS:** `background: #ffffff; border-top: 1px solid #e4e1d7; padding: 64px 0 32px`

**Observed:** A full-width fine line separates the directory from an airy action strip.

**Transfer:** Use the line as the page's final structural boundary, not a colored CTA panel.

#### Reversed proof field · level 0

**Only for:** company credibility sections

**Use:** A contrasting field for customer or partner marks.

**CSS:** `background: #1d1d20; color: #ffffff; padding: 0 32px`

**Observed:** The entire section reverses, with a small upper-left label and an evenly distributed four-column logo arrangement; generous dark space remains around the marks.

**Transfer:** Use monochrome white marks with balanced optical sizing rather than individual logo cards.

## Components

### Menu trigger

**Use:** Persistent minimal navigation access.

**CSS:** `position: fixed; z-index: 100; width: 160px; height: 64px`

**Observed:** The visible affordance is a small olive dot near the right edge; the clickable area is much larger. Informational pages add a small current-section label to its left. The identity sits separately at the upper left.

**Transfer:** Use an accessible button with a circular pseudo-element and a restrained text identity; preserve the small visible mark and roomy hit area.

### Gallery tile

**Use:** Visual proof or feature entry in the unequal gallery.

**CSS:** `padding-left: 64px; margin-bottom: 160px`

**Text style:** `caption` — Good Sans 400 · 22.1px/1.6

**Observed:** One linked image followed by a plain title; no outer card background or frame. The media wrapper clips enlarged artwork, while title and image share a left edge. Wide and narrow items trade sides in successive pairs.

**Transfer:** Keep a concise noun-phrase caption below each product view. Use an overflow-hidden media wrapper and preserve the varied image ratios.

### Browse link

**Use:** Low-pressure exploration at the end of the visual story.

**CSS:** `display: inline-flex; align-items: center; color: #2e2a2b; margin-top: 22.4px`

**Text style:** `browse-link` — Good Sans 400 · 18px/1

**Observed:** Plain text followed by a fine right arrow, with a separate upward control at the opposite edge of the action strip.

**Transfer:** Use one short browsing label rather than a filled conversion button.

### Directory link

**Use:** Email, telephone, location and practical navigation.

**CSS:** `color: #2e2a2b; text-decoration-line: underline; transition: text-decoration-color 0.2s ease-in-out`

**Text style:** `contact-link` — Good Sans 400 · 22.1px/24px

**Observed:** Text sits immediately below a stone label; underline visibility is subdued at rest and reinforced on interaction.

**States:** Declared: hover text-decoration-color #2e2a2b; focus-visible unknown.

**Transfer:** Keep the link as readable contact text rather than placing it inside a button.

### Newsletter starter

**Use:** Newsletter entry point in the left directory column.

**CSS:** `color: #2e2a2b; margin-bottom: 3.2px; transition: opacity 0.6s ease-in-out 0.2s`

**Text style:** `caption` — Good Sans 400 · 22.1px/1.6

**Observed:** A text button beginning with an em dash sits below the newsletter label; the resting view is not a boxed email input.

**Transfer:** Retain the dash-led invitation and reveal the actual form through the interaction rather than drawing a permanent large input.

### Back to top

**Use:** Isolated upward navigation before the directory.

**CSS:** `display: inline-flex; align-items: center; column-gap: 16px; color: #2e2a2b; transition: transform 0.4s cubic-bezier(0.39, 0.71, 0.48, 0.98)`

**Observed:** A fine vertical arrow is the visible cue, with an accessible text label. It sits at the far right alongside the browse link on the landing layout, and at the left when it is the only action.

**States:** Declared: hover transform translateY(0.4rem); focus-visible unknown.

**Transfer:** Keep the arrow visually isolated and preserve the accessible label.

### Return pill

**Only for:** category browsing

**Use:** Return from a filtered collection to the full collection.

**CSS:** `display: flex; align-items: center; padding: 2px 12px; border: 1px solid #2e2a2b; border-radius: 100px; color: #2e2a2b; transition: color 0.5s cubic-bezier(0.39, 0.71, 0.48, 0.98), background 0.5s cubic-bezier(0.39, 0.71, 0.48, 0.98)`

**Text style:** `body` — Good Sans 400 · 18px/1.75

**Observed:** Compact 99px by 38px for the original short label; aligned to the far right under the introductory statement.

**States:** Declared: hover background #2e2a2b and color #ffffff; focus-visible unknown.

### Person entry

**Only for:** people directories

**Use:** Consistent portrait-and-role listing.

**CSS:** `padding-left: 64px; margin-bottom: 128px`

**Text style:** `caption` — Good Sans 400 · 22.1px/1.6

**Observed:** Square portrait above the person's name, then an 18px role on the next line. Images share a neutral studio background and the same scale.

**Transfer:** Keep identity captions outside the image and do not overlay biographies or social badges.

### Principle row

**Only for:** company principles sections

**Use:** Large editorial concept with a short explanatory paragraph.

**CSS:** `border-bottom: 1px solid #e4e1d7; margin-bottom: 64px`

**Text style:** `principle-title` — Good Sans 400 · 92px/1.086

**Observed:** A single oversized title above a half-width support paragraph. The title-to-support gap is 32px and the rule spans the full content width.

**Transfer:** Use a real product principle, method or differentiator with a concise explanation rather than an icon-feature card.

## Imagery and graphics

### Cinematic product showcase

**Use:** Full-bleed moving-image stage and major gallery views.

**Observed:** Highly finished product renders and photographic scenes use real-looking metal, glass, leather and fabric. A dusk aircraft scene combines grey-violet concrete, a pale sky and dark glossy surfaces. Other scenes alternate black studio fields, bright architectural whites and vivid campaign colors. Pictures dominate; text is kept outside them.

**Transfer:** Create a full-width film still or short loop with a convincing product object, directional light and a deliberate environment. For an abstract or software product, stage a clean interface plane or meaningful physical metaphor with the same material lighting; a well-lit still is the minimum acceptable substitute.

### Unequal editorial image pair

**Use:** Signature repeated visual proof throughout marketing and collection pages.

**Observed:** One broad view is paired with a narrower portrait or landscape detail. Dark studio hero objects sit beside bright material close-ups or contextual photography. Images are rectangular, borderless and sharp-cornered; saturated color is contained entirely inside the picture area.

**Transfer:** Pair a complete product or interface view with a tightly framed interaction, material or outcome. Vary the aspect ratios rather than fitting everything into identical landscape thumbnails.

### Neutral studio portrait

**Only for:** people directories

**Use:** Human identity grid.

**Observed:** Waist-up, front-facing or slightly turned portraits against a pale grey seamless background. Natural skin color, soft diffuse lighting and mostly neutral clothing keep the wall coherent without removing personality.

**Transfer:** Use consistent camera distance and background across all people. Retain square framing and avoid circular avatars or environmental backgrounds.

### Monochrome partner marks

**Only for:** company credibility sections

**Use:** Dark social-proof field.

**Observed:** Large white logos occupy four columns with equal optical importance and no containers, badges or colored versions.

**Transfer:** Use authorized partner marks in a single reversed color; tune by visual mass rather than forcing identical logo dimensions.

### Icons

**Observed:** Sparse thin arrows for rightward exploration and upward return, plus compact social-platform marks around 18px with 16px inline separation. The circular menu cue is a solid olive mark rather than a hamburger.

**Transfer:** Use simple single-weight line arrows and authentic platform silhouettes. Avoid adding a general-purpose icon set to every heading.

## Section recipes

How recurring sections are built.

### First screen: Editorial statement opening

**Observed:** A white field carries a small line-built identity near the upper-left corner and the Menu trigger at the upper right. The main text begins after 320px of empty top space, inset 32px. A short stone promise occupies one line, followed immediately by a charcoal explanation across roughly nine tenths of the width, wrapping to two lines at 60px. Both use display type. The statement finishes around 524px; 128px of white space leads to a full-bleed cinematic stage beginning at 652px. Within the first 900px, the full statement and only the top of the large product scene are visible. The scene continues below the fold; its caption, counter and gallery are below. There is no large hero conversion button or text over the image.

**Transfer:** For a new landing page, write a short product promise and one explanatory sentence, then provide a materially convincing film still, loop or staged interface below. Keep the typography and object on separate layers. Category pages open earlier at 256px with editorial-intro text, a stone inline category prefix and Return pill; people pages use a single paragraph before portraits; company pages use several similarly sized paragraphs with 48px separation.

**Avoid:** Do not center the headline over a background image, compress the upper whitespace into a conventional navbar hero, or replace the explanatory display paragraph with tiny support copy.

**Text style:** `display` — Good Sans 400 · 60px/1.135

### Showcase to catalogue

**Observed:** The edge-to-edge cinematic stage is 820px high at desktop, with a small title below on the left and a fraction counter on the right. A 256px transition leads into the unequal-gallery layout. Gallery tile titles sit outside their media and the wide side alternates from row to row.

**Transfer:** Use a broad demonstration to establish atmosphere, then let paired views prove individual benefits or details. The number of entries can suit the new story; preserve unequal pair rhythm.

### Contact-directory ending

**Observed:** An airy action strip places Browse link and Back to top on opposite ends, or leaves only the upward arrow on informational pages. The Ruled directory follows. Two equal columns contain stone labels and charcoal text: newsletter/social/practical links on the left; business, conversation, opportunities and address groups on the right. Directory links and Newsletter starter are text-led, and groups are separated with 40px bottom spacing.

**Transfer:** Close with a practical set of ways to continue, appropriate to the product. Preserve the two-column typographic directory and isolated arrow rather than adding a promotional closing panel.

### Informational introduction

**Only for:** category, people and company pages

**Observed:** An editorial-intro paragraph starts after 256px of top space and uses about a 917px measure. The category variant colors its leading category word stone and adds the right-aligned Return pill. The company variant separates paragraphs by 48px and leaves 128px below.

**Transfer:** Use this quieter opening for reference, team or explanatory content rather than applying the larger landing treatment everywhere.

**Text style:** `editorial-intro` — Good Sans 400 · 40px/1.2

### Principles as editorial rows

**Only for:** company principles sections

**Observed:** A small body-sized section label introduces a stack of Principle row components. Each combines a 92px single-word title with 22.1px support on a 688px measure, a full-width warm hairline and 64px separation.

**Transfer:** Explain a handful of genuine differentiators in text-led rows; let the concept word carry the visual emphasis.

**Text style:** `principle-title` — Good Sans 400 · 92px/1.086

### Reversed credibility field

**Only for:** company credibility sections

**Observed:** The Reversed proof field spans the width with a small white label, about 200px of space above it, then a four-column monochrome logo field. The dark band occupies roughly one desktop screen.

**Transfer:** Use a single strong visual reversal for institutional proof, without turning every section dark.

### Wide testimonial

**Only for:** company credibility sections

**Observed:** On white, a small upper-left label precedes one large, regular-weight multiline quotation, with small attribution below and a stone fraction counter at the lower right. The surrounding section has 256px top and 128px bottom padding.

**Transfer:** Use a concrete customer observation in a wide editorial measure. Keep attribution subordinate and pagination quiet; do not place the quote inside a speech bubble.

## Page flow

**Storyline:** Editorial promise → immersive visual demonstration → curated proof or explanatory chapters → practical ways to continue.

### Image-led marketing landing page

1. **Promise** — Two-tone, display-sized opening statement with generous upper space.
2. **Product demonstration** — Full-width cinematic showcase with discreet caption and fraction counter.
3. **Proof** — Unequal paired media entries alternate widths across a long visual catalogue.
4. **Closing action** — Browse link, isolated upward arrow and a ruled two-column contact directory.

**Transfer:** Use the product's strongest visual demonstration and a curated sequence of outcomes or details; retain the editorial hierarchy and gallery device without matching the catalogue length.

### Filtered visual capability collection

1. **Positioning** — Stone category prefix runs directly into a 40px statement; compact outlined return link aligns right.
2. **Proof** — Unequal media pairs form the majority of the page, with short captions outside images.
3. **Closing action** — Upward arrow followed by the shared contact directory.

**Transfer:** Use for a product family or use-case collection; let the filter-specific promise frame the same gallery language.

### Detailed technical visual collection

1. **Positioning** — A longer three-line category statement uses the smaller editorial introduction scale.
2. **Product proof** — A lengthy gallery mixes material close-ups, product scenes and composed interface presentations.
3. **Closing action** — A lone upward arrow and the same ruled directory finish the collection.

**Transfer:** Use for a more specialized capability or product category, varying narrative length rather than adding a different UI system.

### Human expertise directory

1. **Positioning** — A 40px multiline introduction gives context before the people.
2. **Human proof** — Three equal portrait columns pair names with smaller roles.
3. **Closing action** — The final partial row remains left aligned, followed by an upward arrow and directory.

**Transfer:** Use a consistent portrait system and plain role labels for a team or expert network.

### Company or philosophy narrative

1. **Positioning** — Several spacious 40px paragraphs introduce purpose and method.
2. **Differentiation** — Single-word 92px principle headings, short support paragraphs and hairline rules.
3. **Social proof** — A dark reversed logo field followed by a wide quotation on white.
4. **Closing action** — An isolated upward arrow transitions into the shared directory.

**Transfer:** Translate into principles, process and credible third-party validation relevant to the new product.

## Writing

Assured, reductive and craft-aware. Statements sound considered rather than promotional, pairing technical competence with a simple human or aesthetic outcome.

**Do not copy:** Do not reuse INK's name, identity artwork, client or staff names, contact details, campaign titles, mission claims or testimonial quotations as claims for another brand. Source examples illustrate voice only.

- **Addressing the reader:** The organization speaks as we and our. The reader is rarely directly addressed except in practical invitations such as the newsletter starter.
- **Rhythm:** A short promise followed by a longer explanatory sentence. Editorial concept titles are often single words; image captions are concise names, and actions are brief plain-language phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A technical subject paired with a simple aesthetic outcome. | 3–6 words | “Technology made Beautiful.”<br>“Making the future beautiful.” |
| Opening explanation | Identify the organization and connect a capability to an understandable outcome. | 12–24 words | “A future-focused digital studio passionate about bringing clarity to the complex.”<br>“We tell stories and craft experiences to move people.” |
| Principle explanation | Lead with a concise thought or imperative, then explain how it changes the work. | 15–30 words | “Explore, experiment and learn. Curiosity is an instinctive part of how we think and work.” |
| Browsing action | Simple verb plus destination; no hype or urgency. | 2–4 words | “View all work”<br>“All work”<br>“View all openings” |
| Contact label | Short conversational labels distinguish different reasons to get in touch. | 2–5 words | “Talk to Us”<br>“Sign up for our newsletter” |

**Words and phrasing to use:** craft; clarity; beautiful; future-focused; experiences; explore; collaboration

**Avoid:** game-changing; 10x; dominate; hurry; unlock your potential; revolutionary

**Rules:**

- Describe an actual capability and its outcome rather than stacking superlatives.
- Keep gallery captions as names or concise noun phrases, without explanatory marketing paragraphs.
- Use sentence case and ordinary punctuation; an em dash can join a category label directly to its statement.
- Prefer specific practical destinations for actions over generic conversion slogans.

## Do's and Don'ts

### Do

- Keep display text regular at 60px/1.135 with normal tracking.
- Use 32px desktop side insets and a 1920px container ceiling.
- Alternate 776px and 536px image widths with a 64px gutter at 1440px.
- Place image captions 32px beneath the media rather than over it.
- Give gallery rows 160px breathing room and keep imagery square-edged.
- Keep the circular menu cue visually small within a 160px by 64px target.
- Use #afab9f for directory labels and #2e2a2b for the information beneath.
- Finish with a 1px #e4e1d7 separator and 64px directory top padding.

### Don't

- Do not use bold 700-weight headings to create hierarchy; size and tone carry it.
- Do not spread campaign colors into navigation, links or page backgrounds.
- Do not turn image pairs into equal-sized rounded cards with shadows.
- Do not force portrait, square and landscape artwork into one uniform thumbnail ratio.
- Do not use 92px principle titles as the default landing hero scale.
- Do not give the newsletter starter a permanent filled input or oversized subscription button.
- Do not use tiny uppercase tracked labels throughout; the small section-label recipe is 18px with normal tracking.
- Do not make the closing directory a dense multi-column sitemap with tiny text.

## Motion and responsive

### Motion

**Observed:**

- Text reveal declarations combine transform 1s cubic-bezier(0.075, 0.82, 0.165, 1) with opacity 0.9s ease-in.
- Gallery item reveals declare the same transform curve with a 0.2s delay; image transforms use 0.7s cubic-bezier(0.39, 0.71, 0.48, 0.98).
- Menu transforms declare 0.8s cubic-bezier(0.77, 0, 0.43, 0.99). Return-pill color and background transitions use 0.5s cubic-bezier(0.39, 0.71, 0.48, 0.98).

**Transfer:**

- Use gentle text and image reveal behavior to support the catalogue pacing rather than decorative continual motion.
- Keep captions stable and readable while image wrappers clip their larger artwork.

**Unknown:**

- Exact reveal trigger positions, autoplay cadence and slide interaction behavior are unspecified.
- Focus-visible styling and reduced-motion behavior are unspecified.

### Responsive

**Observed:**

- Desktop composition uses a 1920px maximum container, 32px side padding and 64px gutters.
- Styles declare width breakpoints including 449px, 649px, 767px, 979px, 1024px, 1279px, 1449px, 1600px and 1920px; individual layout transformations are unspecified.

**Transfer:**

- On narrow screens, preserve the editorial paragraph and separate media stage; reduce type to maintain readable line lengths instead of letting the desktop measure overflow.
- Stack unequal image pairs while retaining different aspect ratios, caption spacing and row breathing room. Collapse portrait and directory columns without adding card surfaces.

**Unknown:**

- Mobile font sizes, menu-open composition, exact column-switch thresholds and viewport scaling formulas are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
