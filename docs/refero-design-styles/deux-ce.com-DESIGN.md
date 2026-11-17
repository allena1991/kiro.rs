# Deux-Cé — tactile image narratives

## Overview

An image-led editorial style with the feeling of a carefully sequenced design monograph. White pages, black grotesk labels and literary serif paragraphs frame warm, tactile photography, with a sudden saturated color field at the close. It suits visually expressive products and services whose materials, environments and finished work can carry the argument; the imagery is dense while the surrounding language is spare.

### Essentials

- The opening makes a sentence stretch across two photographs: an 800px-tall, equal-width diptych beneath a 60px white header, with three separated fragments of 20px/1.2, weight 600 uppercase Helvetica across its middle.
- Small capitals do the work of headlines: section labels and project names use Helvetica 17px/1.2, weight 400, 0.04em tracking, while explanatory passages switch to minion-3 at 24px/1.2.
- Actions look like editorial annotations, not controls in containers: the main inline action is 17px uppercase, weight 600, with no filled shape, radius or enclosing border; filters are 24px regular sans with small serif counts.
- Pictures are the dominant proof: alternate 684×912px pairs and 448×597px triplets inside 24px page margins and gutters, with compact captions 12px below and 48px between rows. Without finished campaign media, pair a material detail with a naturally lit use-context photograph.
- Color belongs to pictures and the final field, not the text system: white and black govern the long reading surface; a single 800px green closing panel supplies the default flat brand-color interruption.
- A monumental wordmark signs the page: a black, condensed uppercase graphic occupies an 850×193px area at the lower right of the colored ending, aligned with the serif statement and contact links above. Recreate this device with the new product's own short name.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Closing green | `#259558` | `--color-closing-green` | background | Default full-width closing panel, carrying black text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, link | All ordinary text, hairline rules, menu strokes and wordmark artwork. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Main page and header; reversed lettering over opening photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company narrative pages and expanded navigation | Pale sage | `#d8ddc6` | `--color-sage` | background | Alternate closing field for company narrative pages; also the declared menu field. |
| case studies | Closing cyan | `#009de2` | `--color-closing-blue` | background | Alternate closing field for detailed project stories. |
| work archives | Closing ochre | `#a37434` | `--color-closing-ochre` | background | Alternate closing field for extensive archives. |

## Typography

- **Helvetica** — Labels, image-overlay statement, filters, actions and large editorial declarations. Neutral neo-grotesk with open, positive tracking rather than compressed headline spacing. If unavailable, use **Arimo**. Use regular and semibold cuts; preserve positive tracking. Font stack: "Helvetica", "Arimo", Helvetica, "Helvetica Neue", Arial, sans-serif.
- **minion-3** — Explanatory paragraphs, project disciplines, dates and parenthetical category labels. Literary old-style serif, moderate contrast and compact paragraph rhythm. If unavailable, use **Source Serif 4**. Use weight 400 and check paragraph wrapping against the intended column width. Font stack: "minion-3", "Source Serif 4", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial-lead | minion-3 | 400 | 24px | 1.2 | normal | fixed | Main explanatory passages and closing statement. |
| filter-label | Helvetica | 400 | 24px | 1.2 | 0.02em | fixed | Wrapping taxonomy links and capability titles. |
| hero-statement | Helvetica | 600 | 20px | 1.2 | 0.04em, uppercase | fixed | Three fragments of a single positioning sentence laid over the image diptych. |
| section-label | Helvetica | 400 | 17px | 1.2 | 0.04em, uppercase | fixed | Section headings, project names, contact details and compact text links. |
| metadata | minion-3 | 400 | 17px | 1.2 | normal | fixed | Project dates, disciplines, superscript counts and supporting captions. |
| inline-action | Helvetica | 600 | 17px | 1.2 | 0.04em, uppercase | fixed | Short editorial calls to continue reading or explore the collection. |
| category-caption | minion-3 | 400 | 16px | 1.2 | normal, uppercase | fixed | Parenthesized category headings beside compact proof lists. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| case studies and company manifestos | editorial-display | Helvetica | 400 | 42.8px | 1.04 | 0.04em, uppercase | size 2.9703vw | Case-study titles and full-width attributed declarations. |
| case studies | story-body | minion-3 | 400 | 20px | 1.2 | normal | fixed | Compact contextual paragraph in the left half of a project introduction. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default opening is not a giant typographic headline: the small white sentence lets the images provide scale.
- Maintain the sans/serif division within captions: uppercase sans title at left, serif date at right, serif discipline beneath.
- Tracking stays positive in the grotesk, at 0.04em for uppercase labels and display, and 0.02em for mixed-case filters. Serif text uses normal tracking.
- The closing wordmark is graphic lettering rather than a paragraph or display-font recipe; scale it by its image area.

## Layout

**Density:** Airy editorial framing around dense image sequences, with tightly stacked metadata and proof lists.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Image-to-caption gap, action margin and wrapped filter row gap. |
| 18px | Secondary grid row spacing. |
| 24px | Page side padding, column gutters and closing panel padding. |
| 40px | Space before the final colored panel. |
| 48px | Portfolio row separation and major rule-to-content intervals. |
| 70px | Capability section top padding and wider editorial separations. |
| 110px | Separation between the introductory explanation and taxonomy. |
| 180px | Breathing room around related-story content in a detailed narrative. |

### Containers and grids

- **page-frame**: side padding 24px. Fluid edge-to-edge canvas with consistent inset content; at 1440px, usable width is 1392px.
- **portfolio-grid**: 12 columns · gap 24px. Pairs span six columns each, triplets four each; desktop image widths are 684px and 448px respectively.
- **editorial-column**: max width 850px. Right-aligned narrative, proof-list and footer column; leaves a substantial label rail on the left.
- **intro-column**: max width 784px. Right-hand introductory serif explanation on the default landing layout.
- **story-column** (only for case studies): max width 528px. Left-side contextual text opposite the first case-study image.
- **archive-grid** (only for work archives): 3 columns · gap 24px. Staggered columns of 448px images with occasional 920px images spanning two columns.
- **story-diptych** (only for case studies): 2 columns · gap 0px. Full-bleed 720px halves, independent of the inset portfolio grid.

## Corner radius

| Element | Radius |
| --- | --- |
| image-and-panel-corners | 0px |

## Surfaces and depth

### Surfaces

#### White reading field · level 0

**Use:** Continuous main surface.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No raised cards, corner rounding or decorative shadows.

**Transfer:** Let editorial spacing and image boundaries group content.

#### Colored closing field · level 0

**Use:** Full-width contact and signature ending.

**CSS:** `background: #259558; color: #000000; padding: 24px; min-height: 800px`

**Observed:** A flat field without gradient or texture. Detailed stories use cyan, archives ochre, and company narratives pale sage.

**Transfer:** Keep the default green for ordinary landing pages and preserve the black typography and oversized signature.

#### Photographic veil · level 1

**Use:** Opening media treatment supporting white overlay text.

**CSS:** `background: rgba(0, 0, 0, 0.1)`

**Observed:** A subtle black layer over each photograph, not a neutral-colored tile.

**Transfer:** Keep photography legible and materially rich; darken only enough for the central sentence.

#### Hairline editorial divider

**Use:** Metadata and related-story boundaries.

**CSS:** `border-top: 1px solid #000000`

**Observed:** Rules are structural, spanning the inset content width rather than boxing content.

**Transfer:** Use only where a new editorial chapter or specification band begins.

## Components

### Sticky masthead

**Use:** Persistent brand and menu access.

**CSS:** `position: sticky; top: 0px; height: 60px; padding: 0px 24px; background: #ffffff; display: flex; justify-content: space-between; align-items: center; z-index: 1000`

**Observed:** A compact black condensed wordmark sits left in a 150×34px area; a 32×20px three-line menu mark sits right. No navigation labels occupy the central space.

**Transfer:** Use the product's own condensed wordmark or custom text mark.

### Inline action

**Use:** Main invitation to read or browse.

**CSS:** `color: #000000; background: transparent; margin-top: 12px; text-decoration: none`

**Text style:** `inline-action` — Helvetica 600 · 17px/1.2 · tracking 0.04em · uppercase

**Observed:** A bare label immediately after the explanatory paragraph; no surrounding button silhouette.

**States:** Declared: hover rgba(0, 0, 0, 0.7), no text decoration; focus-visible unknown; active rgba(0, 0, 0, 0.7). Transition 0.1s ease-in-out.

### Taxonomy filter

**Use:** Compact browsing by capability or category.

**CSS:** `color: #000000; border-bottom: 1px solid transparent`

**Text style:** `filter-label` — Helvetica 400 · 24px/1.2 · tracking 0.02em

**Observed:** Mixed-case labels wrap in a flex list with 24px column gaps and 12px row gaps. Counts are parenthesized serif superscripts using metadata. An active archive choice receives a black underline.

**States:** Declared: hover rgba(0, 0, 0, 0.7), no text decoration; focus-visible unknown; active black, no text decoration. Transition 0.1s ease-in-out.

**Transfer:** Use a small, meaningful taxonomy with genuine counts rather than ornamental tags.

### Portfolio caption

**Use:** Identify each photographic proof item.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; margin-top: 12px; color: #000000`

**Text style:** `section-label` — Helvetica 400 · 17px/1.2 · tracking 0.04em · uppercase

**Observed:** Uppercase title on the first line with a right-aligned serif date; a serif discipline or short description follows under the title. It sits on the page, not on the photograph.

**Transfer:** Keep the description short enough to read as catalog metadata.

### Categorized proof list

**Use:** Dense, text-only social proof.

**CSS:** `display: flex; flex-wrap: wrap; column-gap: 48px; row-gap: 48px`

**Text style:** `section-label` — Helvetica 400 · 17px/1.2 · tracking 0.04em · uppercase

**Observed:** Two groups occupy the 850px right-hand column. Each group pairs a right-aligned 120px-wide parenthesized serif category with a narrow vertical stack of uppercase names; the section label remains far left.

**Transfer:** Use customer names, stockists, partners or integrations; preserve typographic listing instead of making a logo wall.

### Contact link row

**Use:** Direct conversion and social links within the colored ending.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; max-width: 850px; color: #000000`

**Text style:** `section-label` — Helvetica 400 · 17px/1.2 · tracking 0.04em · uppercase

**Observed:** Three widely separated links align to the same right-hand column as the opening paragraph and bottom wordmark. Small copyright text occupies the left rail.

**States:** Declared: hover rgba(0, 0, 0, 0.7), no text decoration; focus-visible unknown; active black, no text decoration.

### Story specifications

**Only for:** case studies

**Use:** Factual introduction under the story title.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); column-gap: 24px; row-gap: 18px; border-top: 1px solid #000000; padding-top: 22px; margin-top: 48px`

**Observed:** Three equal fields pair a semibold 17px sans label with a regular uppercase 17px value below; the tracking is 0.02em. Fields identify the subject, time and type of contribution.

### Related stories rail

**Only for:** case studies

**Use:** Continue browsing after a long visual narrative.

**CSS:** `border-top: 1px solid #000000; padding-top: 48px; display: flex; justify-content: space-between`

**Text style:** `section-label` — Helvetica 400 · 17px/1.2 · tracking 0.04em · uppercase

**Observed:** Header places the label left and Inline action right; below generous whitespace, small 14px arrows sit above a horizontal track of 295×393px images with 24px gaps and compact captions. A partial next item signals continuation.

**Transfer:** Show a small set of adjacent examples rather than introducing a new promotion.

## Imagery and graphics

### Atmospheric photographic diptych

**Use:** Primary opening device.

**Observed:** Two equally dominant full-height images meet with no gutter: one intimate material detail, one inhabited exterior. Mosaic tesserae, foliage, linen, terracotta and daylight create a warm, slightly grainy printed feel. The central white sentence crosses the seam.

**Transfer:** Photograph one close material or interaction detail and one wider scene where the product lives. For a digital product, use a naturally lit desk or device-in-use scene beside an intimate hands-and-interface detail rather than two floating screenshots.

### Tactile portfolio plates

**Use:** Repeated visual proof throughout the reading field.

**Observed:** Portrait photographs fill rectangular frames without borders. Close-ups reveal embossed paper, ribbons, glass, ceramics, timber and woven cloth; environmental images supply sea, planting, architecture and interiors. Some images contain their own designed typography; that lettering is not part of the site type system.

**Transfer:** Create visually complete plates of the new product, packaging, use environment or output. Alternate detail and wide context, soft daylight and controlled studio color, retaining authentic texture.

### Monumental signature graphic

**Use:** Required closing device on the colored field.

**Observed:** Black, very heavy condensed uppercase lettering with broad spacing fills an 850×193px area, anchored to the bottom-right content column. It acts as a visual sign-off rather than another headline.

**Transfer:** Use the new product's own short wordmark, preserving its rectangular presence and contrast. Minimum version: a carefully typeset condensed uppercase name with no extra symbol.

**Build:** Make an SVG with viewBox 0 0 850 193. Set the new name in a freely available heavy condensed sans such as Anton, convert to outlines, and fit within the area with deliberate letter spacing. Fill black, preserve the word's proportions and right-align the SVG at the base of the closing panel.

### Context and artifact pairs

**Only for:** case studies

**Use:** Long-form demonstrations of one design system.

**Observed:** Full-bleed paired portrait panels alternate warm interiors, gardens, people at work and landscape with printed guides, folded paper, maps and cards. Printed work is photographed on dark backing, linen or other photographs; soft shadows and off-angle arrangements belong inside the media.

**Transfer:** Pair a real usage environment with a tangible result or document. For software, show an interface in a photographed context and an exported artifact; keep the page outside the media white and unadorned.

### Lived-in workspace portrait

**Only for:** company narrative pages

**Use:** Image-led introduction and square manifesto image.

**Observed:** Warm daylight through ribbed glass partitions, large potted plants, pale timber and working desks. A full-width 1440×800px scene reappears as a 589px square beside an attributed declaration.

**Transfer:** Use a genuine work environment with visible materials and signs of use; photograph the place rather than arranging headshots.

### Icons

**Observed:** Sparse functional marks only: a black 32px-wide three-line menu with 2px strokes, and 14px carousel arrows; the previous arrow is reduced to 0.3 opacity at its boundary.

**Transfer:** Keep icons linear and utilitarian. Avoid feature-icon grids and decorative badges.

## Section recipes

How recurring sections are built.

### First screen: Split image sentence opening

**Observed:** Sticky masthead occupies the top 60px. Below it, two 720×800px photographs fill the width edge to edge, without gutter, ending at 860px. Back to front: paired cover images, Photographic veil, then a single horizontal text layer with 24px inset. Three white uppercase fragments sit left, around the seam and at the right edge across the vertical center; all use hero-statement rather than a giant display. The whole overlay is linked. No separate button or support paragraph competes with the scene. Within the first 900px the masthead, complete image stage and the start of the next section are visible; the introductory paragraph and taxonomy continue below.

**Transfer:** Retain the split scene and three-part positioning sentence for a new landing page. When there is no campaign photography, commission a material close-up and real use-context photograph. An archive opens instead with taxonomy above staggered media; a case study opens with an editorial-display title and Story specifications; a company narrative uses one full-width workspace image with small white chapter links.

**Avoid:** Do not replace the scene with a centered giant headline, rounded product mockup, stacked CTA buttons or a translucent card.

**Text style:** `hero-statement` — Helvetica 600 · 20px/1.2 · tracking 0.04em · uppercase

### Label and literary explanation

**Observed:** A small uppercase section label sits in the left rail, with an editorial-lead paragraph in a right-aligned column up to 784px wide. Inline action follows 12px below. Taxonomy filter begins after a 110px separation.

**Transfer:** State the product's point of view in a concise serif paragraph while keeping the label factual and small.

**Text style:** `editorial-lead` — minion-3 400 · 24px/1.2

### Alternating portfolio rows

**Observed:** Portfolio caption accompanies portrait plates arranged as pairs and triplets in Portfolio-grid. Equal image ratios near 3:4 produce a repeating cadence; 48px separates completed rows.

**Transfer:** Vary the number and scale of proof images, not the card decoration. Adapt the row sequence to the volume of meaningful work.

### Categorized textual proof

**Observed:** A section label at far left introduces Categorized proof list in the right 850px column. Long narrow lists of uppercase names balance small parenthesized serif categories; no enclosing cards or decorative marks.

**Transfer:** Use a meaningful body of names or compatible tools, with category grouping only where it helps scanning.

### Colored signature ending

**Observed:** Colored closing field is 800px tall with 24px inset. Address information occupies the top-left rail; an editorial-lead statement fills the top-right 850px column. Contact link row crosses the middle while copyright remains left. Monumental signature graphic anchors the bottom-right, leaving most of the left half open. The same composition closes every page type with a scoped color change.

**Transfer:** Retain this ending's scale, three-level organization and wordmark signature. Replace the address and channels with genuinely useful conversion details, keeping the direct text-link approach.

**Text style:** `editorial-lead` — minion-3 400 · 24px/1.2

### Staggered archive

**Only for:** work archives

**Observed:** Taxonomy filter precedes a three-column image archive. Independent image heights and occasional two-column hero plates break the cadence; captions stay directly beneath each item.

**Transfer:** Let an extensive library retain its varied image formats while enforcing the 24px gutters and shared captions.

### Story title and visual chapters

**Only for:** case studies

**Observed:** An editorial-display title begins 48px below the masthead, followed by Story specifications and a 48px separation before a split introduction. A 528px serif paragraph sits low on the left, while the first image fills the right half. Subsequent full-bleed diptychs use 720px halves and approximately 62px white chapter gaps; Related stories rail follows the visual narrative.

**Transfer:** Lead with facts and one contextual paragraph, then let paired usage and artifact images explain the result.

**Text style:** `editorial-display` — Helvetica 400 · 42.8px/1.04 · tracking 0.04em · uppercase

### Attributed manifesto

**Only for:** company narrative pages

**Observed:** Section-label introduces a full-width editorial-display statement. Below, a 589px square workspace image sits left, a large attribution starts beside its upper edge, and a small metadata paragraph anchors the lower right. Substantial white space separates the elements.

**Transfer:** Use one concise product belief and attribute it honestly; pair with a genuine environment or making-process image.

**Text style:** `editorial-display` — Helvetica 400 · 42.8px/1.04 · tracking 0.04em · uppercase

## Page flow

**Storyline:** Atmosphere or category entry → concise point of view → visual demonstration → organized proof → direct contact and monumental signature.

### Image-led marketing landing page

1. **Positioning** — Split image sentence opening.
2. **Explanation** — Label and literary explanation with a short continuation link.
3. **Product demonstration** — Taxonomy and alternating paired or triplet photographic proof.
4. **Social proof** — Categorized textual proof.
5. **Closing call** — Green colored signature ending.

**Transfer:** Use atmosphere to establish desire, then explain briefly and prove through varied media rather than many headline blocks.

### Detailed product or project story

1. **Context** — Regular uppercase title, three factual fields and one compact serif explanation opposite an image.
2. **Product demonstration** — Repeated full-bleed context and artifact diptychs.
3. **Continuation** — Ruled related-story rail with small arrows and a partial next card.
4. **Closing call** — Cyan colored signature ending.

**Transfer:** Explain one result through a sustained visual narrative instead of reusing the landing-page grid.

### Large browsable archive

1. **Wayfinding** — Wrapping category links and superscript counts replace a promotional heading.
2. **Product demonstration** — Staggered image library with occasional oversized plates and consistent caption syntax.
3. **Closing call** — Ochre colored signature ending.

**Transfer:** Prioritize navigation and visible examples; avoid introductory marketing paragraphs when readers already want the catalog.

### Company or product philosophy narrative

1. **Atmosphere** — Full-width workplace image with white chapter links.
2. **Explanation** — Serif paragraphs opposite a small label, then a ruled capability grid.
3. **Point of view** — Attributed manifesto with square workspace portrait and low-right support text.
4. **Social proof** — Categorized textual proof.
5. **Closing call** — Pale-sage colored signature ending.

**Transfer:** Make the product's method and beliefs tangible through real environments and restrained textual proof.

## Writing

Cultured, matter-of-fact and collaborative. The language treats design as a combination of thinking and making, relying on specificity rather than sales pressure.

**Do not copy:** Do not reuse the agency's name, wordmark artwork, address, client names, project titles, counts, dates, claims or attributed quotations. Source examples demonstrate syntax only; all new claims and proof must belong to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First-person plural describes the practice; the reader appears occasionally as 'your'. Navigation and actions use direct, impersonal labels.
- **Rhythm:** Short factual labels frame longer serif sentences. Explanations develop one thought across roughly two to four lines; captions remain compressed and catalog-like. Avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening sentence | A three-part identity statement: who we are, what we do, where or how we operate. | Three short fragments | “a full-service creative agency,” |
| Section label | Plain noun or concise question identifying the subject. | 1–3 words | “What we do”<br>“Our difference” |
| Explanation | Define a principle, then explain its practical expression. | One developed sentence or short paragraph | “A brand is the combination of strategy, design, content, and words that tells a story.” |
| Action | Literal verb and destination, without urgency or reward language. | 2–3 words | “Read more”<br>“Send email”<br>“All projects” |
| Metadata | A simple discipline description under a named work item. | 2–5 words | “Visual identity and Design” |

**Words and phrasing to use:** story; identity; craft; alongside; methodology; side-by-side; visual; meaningful

**Avoid:** game-changing; unlock; revolutionary; 10x; limited time; supercharge

**Rules:**

- Let named outputs and real examples support the promise instead of stacking superlatives.
- Use category labels as navigation, not as miniature slogans.
- Keep actions literal and low-pressure.
- A poetic principle can sit beside exact factual metadata; do not make both abstract.

## Do's and Don'ts

### Do

- Keep the header at 60px with 24px side insets and a largely empty center.
- Use the 20px semibold uppercase sentence over the opening imagery.
- Keep section labels at 17px regular with 0.04em tracking.
- Use 24px serif paragraphs for the main explanation and closing statement.
- Keep image gutters at 24px and completed portfolio rows 48px apart.
- Put compact metadata 12px below the image.
- Preserve the 850px right-hand alignment across the closing statement, contact row and signature.
- Keep all page-level image and panel corners square.

### Don't

- Do not turn filter labels into padded pills; their 24px mixed-case text and superscript counts provide the structure.
- Do not use a bold grotesk for all body copy; the 24px serif voice is essential.
- Do not apply shadows to portfolio cards; physical shadows belong within photographed objects.
- Do not color ordinary navigation or captions with the closing accent.
- Do not make proof names into a dense badge wall; retain narrow typographic lists.
- Do not center the closing wordmark or shrink it into a conventional footer logo.
- Do not import lettering inside campaign images into the site's text scale.
- Do not force archive images into equal-height thumbnails; the staggered archive preserves varied proportions.

## Motion and responsive

### Motion

**Observed:**

- Links and the header declare 0.1s ease-in-out transitions.
- Opening media figures declare a 4s linear infinite hero animation.

**Transfer:**

- Keep feedback focused on subtle text-color changes; preserve the split scene's stable composition.

**Unknown:**

- Hero keyframe appearance, focus-visible states and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 600px, 767px, 768px, 991px, 1023px, 1024px, 1279px, 1280px, 1599px and 1600px.
- Editorial display follows 2.9703vw.

**Transfer:**

- Reflow the label rail above its serif paragraph on narrow screens.
- Reduce image-grid columns while preserving captions beneath square-cornered media.
- Keep the diptych and three-part sentence together as one composition; vertically paired imagery is preferable to colliding fragments.

**Unknown:**

- Exact mobile column counts, padding, hero height and expanded navigation layout are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
