# Belka — industrial light halos

## Overview

A dark, spacious industrial-tech style that pairs understated geometric sans typography with real working environments and oversized numerical proof. Charcoal and white dominate, with dusty periwinkle labels, coral line symbols and blurred violet-pink light circulating around the edges. It suits complex B2B products that need both engineering credibility and a more atmospheric, sculptural presence.

### Essentials

- An editorial headline crosses into a working-world image: regular Manrope at 85px/94px with -1px tracking, broken into three lines over a right-half video stage beneath a 60px navigation bar.
- Proof becomes architecture rather than cards: 220px/279px regular numerals sit in an open two-by-two grid with 1px charcoal rules; small 26px qualifiers and units orbit the figures.
- Color lives at the perimeter: a #181818 canvas occupies almost the whole page, #8d97cc marks section labels, and #eb5b5d marks tiny icons, arrows and hover feedback. Violet-pink blurred arcs intrude from beyond the viewport rather than filling every section.
- Actions are fine outlined capsules, not solid conversion blocks: 30px radius, a 0.8px white edge, 14px regular labels and 50px height in the opening; longer editorial actions use 55px height.
- Section titles behave like a left-hand index: 20px periwinkle labels face 26px/34px white statements in the right half, with four small coral-icon columns below.
- A luminous open ring carries the visual identity through the page and into the ending: use broad blurred arcs behind content and a 379px-deep closing glow behind compact contact columns. Rebuild this light sculpture with SVG when no custom artwork exists.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral signal | `#eb5b5d` | `--color-signal` | accent, action, link | Line icons, directional marks, small status text and hover feedback. |
| Dusty periwinkle | `#8d97cc` | `--color-section-label` | text, accent | Section index labels; related violet light belongs in atmospheric artwork rather than flat panels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal canvas | `#181818` | `--color-canvas` | background, text | Default page field and dark text on the exceptional light quotation panel. |
| Near-charcoal media bed | `#191919` | `--color-media-bed` | background, surface | Backing for atmospheric image fields, visually continuous with the canvas. |
| Dark rule | `#2f2f2f` | `--color-rule` | border | Subtle separators in statistics and recognition lists. |
| Credit gray | `#85889e` | `--color-credit` | text | Tiny bottom-of-page credit prefixes. |
| Supporting gray | `#a1a1a1` | `--color-muted` | text | Paragraphs, metric qualifiers, secondary descriptions and contact labels. |
| Soft white | `#e9e9e9` | `--color-soft` | text, border, surface | Lightweight lead copy, language-control outline and bright closing divider; also the base of the scoped quotation panel. |
| White | `#ffffff` | `--color-primary` | text, border | Headlines, numbers, logo treatments, action text and fine button outlines. |

## Typography

- **Manrope** — All main marketing text, numerals, navigation and actions. Open geometric sans with round counters; predominantly regular with light supporting text. Font stack: "Manrope", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | Manrope | 400 | 220px | 279px | normal | Single-digit proof figures. |
| stat-pair | Manrope | 400 | 220px | 279px | -20px | Tightly joined two-digit proof figures. |
| display | Manrope | 400 | 85px | 94px | -1px | Default marketing opening, split into editorial lines. |
| display-middle | Manrope | 400 | 85px | 140px | -1px | Independently positioned middle line of the opening headline; align its visible baseline with the other lines rather than making a uniform 140px paragraph. |
| heading | Manrope | 400 | 26px | 34px | normal | Main section statements and closing invitation. |
| lead-light | Manrope | 300 | 26px | 34px | normal | Long explanatory lead alongside a section index. |
| stat-qualifier | Manrope | 400 | 26px | 33px | normal | Gray prefixes next to the base of a metric. |
| contact-link | Manrope | 400 | 26px | 41px | normal | Direct email action in the closing section. |
| section-label | Manrope | 400 | 20px | 29px | normal | Periwinkle left-column section indexes. |
| stat-label | Manrope | 400 | 16px | 19px | normal | Concise outcome label above a metric. |
| body | Manrope | 300 | 14px | 22px | normal | Default supporting copy in gray; white when emphasis requires it. |
| item-title | Manrope | 400 | 14px | 20px | normal | Short capability labels. |
| button | Manrope | 400 | 14px | 1.55 | normal | Outlined action capsules. |
| navigation | Manrope | 400 | 12px | 19px | normal | Small navigation text. |
| caption | Manrope | 300 | 11px | 17px | normal | Subordinate recognition metadata. |
| contact-detail | Manrope | 300 | 11px | 18px | normal | Compact office and contact details. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and dedicated product introductions | page-title | Manrope | 400 | 116.7px | 118px | normal | Centered, short page title with a small label above and a right-half description below. |
| company storytelling | film-statement | Manrope | 400 | 50px | 58px | normal | Broad statement over a full-width working-environment film. |
| company principles lists | list-number | Manrope | 400 | 40px | 58px | normal | Large left-column sequence numbers. |
| product testimonial panels | quote | Manrope | 400 | 26px | 36px | normal | Long dark quotation on a pale field. |
| technical product explanations | technical-number | Manrope | 600 | 12px | 1.5 | normal | Coral sequence markers on a glass band. |
| technical product explanations | technical-caption | Manrope | 300 | 11px | 16px | normal | Small technical support below feature titles. |

**Notes:**

- Regular weight carries the hierarchy; scale and placement supply emphasis instead of bold headings.
- The default opening is 85px, while centered company and dedicated-product titles are 116.7px. Do not average these into one universal display size.
- Keep body text notably smaller than 26px statements. Tracking stays normal except for the opening and tightly joined two-digit statistics.

## Layout

**Density:** Airy: long pauses separate compact, finely set information groups, with the largest breathing room around numerical proof.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Small horizontal gap within compact controls. |
| 30px | Minor section offset or local spacing. |
| 120px | Top inset of the closing invitation. |
| 144px | Opening inset of the expertise chapter. |
| 148px | Bottom breathing room in company introduction and people sections. |
| 195px | Long trailing pause after a sparse capabilities chapter. |

### Containers and grids

- **editorial-container**: max width 1150px · side padding 145px. Desktop content spans the middle 1150px of a 1440px viewport. This is a reconstruction rule for the aligned content, not a padded inner box.
- **heading-pair**: 2 columns. Left index begins at the content edge; the main statement begins near the viewport midpoint and occupies roughly 558px.
- **capability-row**: 4 columns. Four unboxed columns across the content width; each icon sits well above its short label.
- **proof-grid**: 2 columns · gap 0px. Two-by-two figures divided by a cross of hairlines; no outer card border.
- **contact-row**: 3 columns. Three compact contact groups spread across the lower closing glow.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-capsules | 30px |
|  | embedded-media | 10px |
| company people sections | portrait | 50% |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page background.

**CSS:** `background-color: #181818; color: #ffffff`

#### Media fade · level 1

**Use:** Merge opening film into the dark page.

**CSS:** `background: linear-gradient(0deg, #181818 0%, rgba(24,24,24,0.1) 100%)`

**Observed:** A lower dark fade overlays the right-hand image without hiding its recognizable subject.

**Transfer:** Keep important image detail near the top and middle; dissolve the lower edge into the canvas.

#### Open ruled field · level 1

**Use:** Statistics, capabilities and recognition without raised cards.

**CSS:** `background-color: transparent; border-bottom: 1px solid #2f2f2f`

**Observed:** Content rests directly on the canvas. Rules carry the grouping, with no shadows.

**Transfer:** Use separators only where they clarify repeated items.

#### Pale quotation · level 1

**Only for:** product testimonial panels

**Use:** A rare bright proof interruption.

**CSS:** `background-color: #e9e9e9; color: #181818; border-radius: 0px`

**Observed:** A broad rectangular field contains a nearly white pastel wash, an oversized quotation glyph and a long paragraph. It extends farther right than the standard content area.

**Transfer:** Use one restrained ivory-lilac atmospheric field, not a collection of white cards.

#### Technical glass band · level 1

**Only for:** technical product explanations

**Use:** Three numbered explanations over a dark sculptural object.

**CSS:** `background-color: rgba(24,24,24,0.5); backdrop-filter: blur(40px); border-radius: 0px`

**Observed:** The translucent rectangular band softens a charcoal object behind it; its width is 1321px and height 422px on desktop.

**Transfer:** Keep the sculpture legible above and below the glass rather than turning the band into an isolated floating card.

## Components

### Fixed navigation

**Use:** Persistent orientation with a small identity mark and compact links.

**CSS:** `position: fixed; height: 60px; z-index: 990; color: #ffffff`

**Text style:** `navigation` — Manrope 400 · 12px/19px

**Observed:** Identity at the left content edge, four small links distributed across the right half, then a fine outlined language capsule. The bar visually stays dark while scrolling.

**States:** Declared: hover text changes to #eb5b5d; focus-visible and active are unknown.

**Transfer:** Keep the navigation small relative to the editorial opening; avoid a large conversion button in the header.

### Outline action

**Use:** Default primary marketing action.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 50px; width: 192px; border: 0.8px solid #ffffff; border-radius: 30px; color: #ffffff; background-color: transparent`

**Text style:** `button` — Manrope 400 · 14px/1.55

**Observed:** Centered text with a directional-arrow pseudo-element. Longer chapter links grow to 289–322px wide and 55px high.

**States:** Declared: hover background-color #eb5b5d and border-color #eb5b5d; focus-visible and active are unknown.

**Transfer:** Let width follow label length while preserving the fine capsule outline.

### Section index

**Use:** Label a chapter without making it a large heading.

**CSS:** `color: #8d97cc`

**Text style:** `section-label` — Manrope 400 · 20px/29px

**Observed:** Sits alone in the left half, aligned with a larger white statement in the right half.

**Transfer:** Name the category plainly in two to four words.

### Metric cell

**Use:** Make quantified outcomes the dominant proof.

**CSS:** `color: #ffffff; background-color: transparent`

**Text style:** `stat` — Manrope 400 · 220px/279px

**Observed:** A small outcome caption and coral diagonal arrow precede a giant figure. Gray qualifiers sit near its baseline; small units sit by its upper right. Interior horizontal and vertical rules separate the cells.

**Transfer:** Use real outcome data, retain qualifiers, and use stat-pair for a two-digit value.

### Capability item

**Use:** A sparse row of expertise or capability explanations.

**CSS:** `color: #ffffff; background-color: transparent`

**Text style:** `item-title` — Manrope 400 · 14px/20px

**Observed:** A coral outline symbol at about 31px sits above the short title, with ample vertical separation. Technical variants add small gray support text; there is no bounding card.

**Transfer:** Choose four short capabilities with distinct line icons.

### Recognition row

**Use:** Compact third-party proof list.

**CSS:** `border-bottom: 1px solid #2f2f2f; background-color: transparent; color: #ffffff`

**Text style:** `item-title` — Manrope 400 · 14px/20px

**Observed:** Rows occupy the right half only: title above gray 11px metadata, with a small coral result aligned far right. A chapter action follows the list.

**Transfer:** Use awards, certifications or independently verified milestones with the same title–context–result hierarchy.

### Direct contact

**Use:** The closing conversion action.

**CSS:** `color: #ffffff; background-color: transparent`

**Text style:** `contact-link` — Manrope 400 · 26px/41px

**Observed:** A plain, prominent email link follows a modest invitation and a small gray support line. There is no form or solid button.

**States:** Declared: hover color #eb5b5d; focus-visible and active are unknown.

### Contact column

**Use:** Compact practical information in the ending.

**CSS:** `color: #ffffff; background-color: transparent`

**Text style:** `contact-detail` — Manrope 300 · 11px/18px

**Observed:** A muted 11px label precedes a multi-line address and optional phone number. Three columns sit in front of the broad lower glow, followed by tiny credits.

**Transfer:** Use real office, support or service contact information; retain the compact scale.

### Testimonial panel

**Only for:** product testimonial panels

**Use:** A high-contrast customer endorsement.

**CSS:** `background-color: #e9e9e9; color: #181818; width: 1292px; border-radius: 0px`

**Text style:** `quote` — Manrope 400 · 26px/36px

**Observed:** Pale quotation surface with a pink quotation glyph in a left gutter, a wide paragraph, then small author and role text below.

**Transfer:** Use a substantiated quotation with generous inset rather than a carousel of mini-cards.

### Numbered principle

**Only for:** company principles lists

**Use:** Values or working principles as broad editorial rows.

**CSS:** `color: #ffffff; background-color: transparent`

**Text style:** `list-number` — Manrope 400 · 40px/58px

**Observed:** Large white sequence numbers sit at the left content edge; right-half titles and gray descriptions align into rows with fading dark dividers. A luminous ring passes behind the number column.

**Transfer:** Use a small set of durable working principles rather than generic feature checklists.

## Imagery and graphics

### Perimeter light sculpture

**Use:** Signature atmospheric device across the page and in the ending.

**Observed:** Soft, broad open rings and curved light streaks in violet, pink and blue sit on charcoal. Much of each ring lies outside the viewport; the center remains dark and content stays dominant. The ending uses a low, wide arc with a blue left side and pale pink right side at 0.6 opacity.

**Transfer:** Recreate an incomplete luminous ring even without custom media. Keep its dark center and off-canvas scale; match the soft glow rather than exact color stops.

**Build:** Create an SVG ellipse about 1100px wide and 900px tall with no fill and a 70px stroke. Apply a blue-to-violet-to-pink linear gradient using rgba(100,115,230,0.6), rgba(180,140,220,0.7), rgba(235,190,225,0.8); blur it by 35px and add a second 120px-wide stroke blurred by 65px at 0.25 opacity. Place most of the ellipse beyond a side or upper edge, beneath text. For the ending, clip a flattened ellipse into a 379px-high field and lower the whole layer to 0.6 opacity.

### Working-world film

**Use:** Default opening media and contextual product demonstrations.

**Observed:** The opening shows a tightly framed industrial vehicle and excavation, with muted natural yellow and gray colors. It occupies roughly the right half, begins immediately below the header, has a softened upper-left corner and fades dark at the bottom. A smaller rounded film shows a person operating dual displays.

**Transfer:** Use a real working environment appropriate to the new product, with a single recognizable subject and subdued color. Without film, use a still photograph with the same framing and dark fade.

### Monochrome partner field

**Use:** Credibility near the lower half of a marketing page.

**Observed:** Eight white partner marks appear in two rows of four on charcoal, without individual tiles. Their optical sizes are balanced despite different silhouettes.

**Transfer:** Use approved logos in a single white treatment, or typeset verified partner names when marks are unavailable.

### Charcoal liquid object

**Only for:** dedicated product storytelling

**Use:** A sculptural product-opening object and background to the technical glass band.

**Observed:** A large irregular, inflated charcoal form has broad soft reflections, subtly olive-gray undertones and no bright metallic edges. It is clipped dramatically at the left of the opening and reappears on the right behind explanatory content.

**Transfer:** Use an abstract dark material study rather than a literal mascot. A softly shaded SVG blob is the minimum acceptable equivalent.

**Build:** Draw an asymmetric SVG path with five broad lobes inside a 1000px square. Fill with a dark gray radial gradient; overlay two blurred white ellipses at 0.08–0.18 opacity for broad studio reflections. Add a dark lower gradient for volume. Scale beyond the content edge and clip it rather than centering a small icon.

### People and workplace

**Only for:** company storytelling

**Use:** Introduce people and demonstrate practical work.

**Observed:** Two circular monochrome headshots sit in open columns with coral experience highlights. A full-width workplace film is heavily darkened behind a broad white statement and smaller quotation.

**Transfer:** Use neutral monochrome portraits and authentic workplace scenes; keep text separate from portrait backgrounds and preserve the dark film treatment.

### Icons

**Observed:** Small coral outline symbols, usually 31px, use rounded geometric enclosures and uncomplicated internal marks. Metric arrows are about 19px and point diagonally up or down. No filled multicolor icon tiles.

**Transfer:** Choose a consistent thin, rounded outline set; keep symbols coral and separate them from text with generous vertical air.

## Section recipes

How recurring sections are built.

### First screen: Film and editorial opening

**Observed:** A 60px fixed navigation caps a 742px opening. Behind everything is Canvas, with a dim Perimeter light sculpture leaking in from the left. Working-world film starts below the header in the right half and fills that side to the edge, under Media fade. A three-line white display headline begins at the left content margin, occupies about two thirds of the width and crosses the image boundary. Its lines read as a single regular-weight statement, with the middle word positioned independently. A small one-line support statement and Outline action sit below it in the left half. Within the first 900px the full headline, support, action and image are visible; only the next chapter's first line begins at the bottom, while numerical proof remains below the fold.

**Transfer:** Use a three-line outcome promise and a tightly framed workplace still or film for a different product. Preserve the overlap, dark lower fade and left glow even without video. Company and dedicated-product introductions instead use page-title centered high on the canvas, a small category label above, a right-half heading below, and a large cropped ring or charcoal object.

**Avoid:** Do not turn this into a centered headline with two filled buttons above a floating dashboard; do not put the headline wholly inside a small opaque text card.

**Text style:** `display` — Manrope 400 · 85px/94px · tracking -1px

### Indexed statement and capabilities

**Observed:** Section index anchors the left half while heading sits in the right half. After a long open pause, four Capability items span the full editorial-container; the expertise chapter has about 144px of top inset and 195px of trailing air.

**Transfer:** Use the same composition for benefits, methods or differentiators; let the heading explain the category rather than repeating it.

**Text style:** `heading` — Manrope 400 · 26px/34px

### Monumental proof field

**Observed:** Section index and a right-hand lead introduce the proof-grid. Metric cells have very large white numerals, subdued gray qualifiers, fine dark rules and small coral arrows. Perimeter light sculpture enters at both outer edges; a right-half paragraph and Outline action close the chapter.

**Transfer:** Give a few well-supported outcomes room to become the graphic focal point. Keep the architecture open even if the values are not percentages.

**Text style:** `stat` — Manrope 400 · 220px/279px

### Recognition and partner proof

**Observed:** A left Section index faces a narrow right-side stack of Recognition rows and an Outline action. A following statement pair introduces the Monochrome partner field. A bright 1px divider marks the transition to contact.

**Transfer:** Adapt this proof chapter to credible third-party validation and approved partner marks; preserve the difference between dense right-hand rows and the broad unboxed logo field.

### Luminous contact ending

**Observed:** All page types end in the same 831px dark section. A bright 1px line spans the editorial-container. After a 120px inset, Section index sits left and a two-line heading, gray support and Direct contact sit right. The lower 379px contains a wide blurred ring behind three Contact columns; tiny credits align along the bottom left.

**Transfer:** Close with an invitation to discuss the reader's work, one direct contact route and practical contact details. Preserve the luminous lower arc and compact typography rather than replacing this with a conventional sitemap footer.

**Text style:** `heading` — Manrope 400 · 26px/34px

### Bright endorsement interruption

**Only for:** product testimonial panels

**Observed:** Testimonial panel interrupts the dark flow with a broad, square-edged pastel near-white rectangle. A large pink quote mark occupies the left gutter; the quote and author sit farther right with generous vertical separation.

**Transfer:** Use an endorsement at a moment when reassurance matters. Keep this a special proof treatment, not the default surface for capabilities.

**Text style:** `quote` — Manrope 400 · 26px/36px

### Workplace statement

**Only for:** company storytelling

**Observed:** A full-width 817px workplace film backs a periwinkle index, a broad 50px/58px white statement and a small quotation with attribution. The film is dark enough that the statement remains the primary visual.

**Transfer:** Explain the organization's practical commitment through a real working scene, not a stock celebration photograph.

**Text style:** `film-statement` — Manrope 400 · 50px/58px

### Glass explanation chapter

**Only for:** technical product explanations

**Observed:** A right-half heading sits above a large charcoal liquid object. Technical glass band stretches across its middle, holding three small coral sequence markers, white titles and gray technical support.

**Transfer:** Use this to explain constraints, operating conditions or complex mechanisms while keeping the object atmospheric rather than diagrammatic.

**Text style:** `heading` — Manrope 400 · 26px/34px

## Page flow

**Storyline:** Outcome promise → explanation → visible proof → capability or trust chapters → direct conversation.

### Broad marketing introduction

1. **Promise** — Overlapping editorial headline and contextual film.
2. **Product explanation** — Indexed definition and large right-hand lead.
3. **Quantified proof** — Four monumental figures on an open ruled field.
4. **Capability chapters** — Four coral-icon items under an indexed statement.
5. **Social proof** — Recognition rows and monochrome partner marks.
6. **Closing call** — Luminous contact ending.

**Transfer:** Use this as the default landing-page grammar; reorder proof and capabilities according to the product's strongest argument.

### Company and people credibility

1. **Introduction** — Centered short title with a cropped upper ring and right-side supporting statement.
2. **Approach** — Three coral-icon items.
3. **People proof** — Two monochrome portrait columns with experience highlights.
4. **Commitment** — Darkened workplace film and expansive white statement.
5. **Principles** — Numbered editorial rows over a left-side light arc.
6. **Closing call** — Luminous contact ending.

**Transfer:** Borrow the people-led emphasis for a company or service page while retaining the common index alignment and ending.

### Dedicated complex-product explanation

1. **Product introduction** — Centered name and right-half definition beside a clipped charcoal sculpture.
2. **Benefits** — Two icon-led explanations beside a rounded workplace demonstration.
3. **Customer validation** — Broad pale testimonial interruption.
4. **Capabilities** — Indexed heading and four technical feature columns.
5. **Objection handling** — Three numbered explanations on a glass band over the sculpture.
6. **Quantified proof** — Monumental ruled metrics.
7. **Closing call** — Luminous contact ending.

**Transfer:** Use the sculptural and glass variants for a deep product page, not as a replacement for the default film-led marketing opening.

## Writing

Measured, practical and engineering-oriented, with confidence grounded in implementation and useful outcomes. The tone becomes warmer in the contact invitation without becoming playful or breathless.

**Do not copy:** Do not reuse Belka's name, identity artwork, customer logos, offices, personal names, quotations, awards, proprietary claims or numerical outcomes. Source phrases illustrate syntax and tone only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use 'we' for the organization and 'your' for the reader's business. Product explanations can name the product and describe its behavior directly.
- **Rhythm:** A short opening promise contrasts with longer single-sentence explanations. Section indexes are brief noun phrases; actions are plain verbs. Supporting paragraphs are compact and declarative.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An active first-person promise tied to a concrete improvement. | 8–12 words | “We take minerals processing to the next level” |
| Section index | A short category name with no punctuation or all-caps styling. | 2–4 words | “Results of implementation”<br>“Our expertise” |
| Capability explanation | State what the product does, how it acts and when. | 15–25 words | “[Brand] manages the technological process in automatic mode, making complex decisions for the operator in real-time.” |
| Action | A low-pressure verb phrase inviting investigation. | 3–6 words | “Find out how”<br>“Learn more about the platform” |
| Closing invitation | Offer a practical conversation rather than urgency. | 10–16 words | “We are readily available to discuss your project in more detail” |

**Words and phrasing to use:** practical results; implementation; expertise; real-time; responsible collaboration; your business; discuss your project

**Avoid:** magic; insane; crush it; revolutionary; limited-time; effortless everything

**Rules:**

- Describe an operational behavior before promising an outcome.
- Keep qualifiers such as 'up to' attached to numerical claims.
- Use technical terminology when it clarifies the mechanism, not as decorative jargon.
- Keep warmth in direct invitations and restraint in proof statements.

## Do's and Don'ts

### Do

- Use 400-weight Manrope for the 85px opening rather than a heavy display face.
- Maintain the 20px left-index versus 26px right-statement hierarchy.
- Keep numerical proof at 220px and allow its qualifiers to remain only 26px.
- Use 30px-radius outline actions and coral hover feedback.
- Preserve 1px dark dividers instead of raised proof cards.
- Carry the blurred light arc into the 379px-deep lower contact field.
- Stage four coral outline icons in an unboxed capability row.
- Keep the standard content aligned to a 1150px desktop span.

### Don't

- Do not make coral a full-page background; it belongs to signals and interaction.
- Do not turn periwinkle section indexes into uppercase, widely tracked micro-labels.
- Do not add drop shadows to the open ruled content.
- Do not use the 116.7px centered title as the default marketing display.
- Do not give every panel the pale testimonial treatment.
- Do not normalize the tightly joined two-digit statistics to ordinary tracking.
- Do not use colorful logo tiles where a monochrome partner field belongs.
- Do not expand the closing invitation into an oversized promotional headline; it stays at 26px.

## Motion and responsive

### Motion

**Observed:**

- Outlined actions declare 0.2s ease-in-out background, color and border transitions; text navigation and email links declare 0.3s transitions.
- Opening headline lines declare a 1s reveal with cubic-bezier(0.22,0.61,0.36,1) and a 0.5s delay.
- Atmospheric artwork has declared linear loops of 10s and 40s; exact paths are not specified here.

**Transfer:**

- Keep atmospheric movement slow and peripheral; preserve the headline's independent line staging.
- Use the declared coral feedback on actions rather than adding scale or shadow effects.

**Unknown:**

- Exact artwork trajectories, video playback behavior and reduced-motion variants are unknown.

### Responsive

**Observed:**

- Declared width boundaries include 479px/480px, 639px/640px, 959px/960px and 1199px/1200px.

**Transfer:**

- On narrow screens, preserve headline-to-image overlap but reduce line length before reducing the image to a thumbnail.
- Stack the index above its statement, then reduce four capability columns and two proof columns to readable vertical groups.
- Keep the ring clipped outside the canvas and behind the closing contact groups rather than allowing it to create horizontal scrolling.

**Unknown:**

- Mobile geometry, text sizes, navigation transformation and exact breakpoint-specific rules are unknown; the stacking rules are transfer guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
