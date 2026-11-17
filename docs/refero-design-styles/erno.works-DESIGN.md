# Erno Works — indented visual index

## Overview

A light, editorial portfolio language with a cool off-white canvas, charcoal grotesk typography and almost no interface decoration. Large conversational statements sit above an asymmetric index of richly staged work, from dark device views to softly lit physical objects. It suits design-led products and services with strong visual proof, balancing dense captions with broad empty margins.

### Essentials

- The opening reads like an indented paragraph rather than a slogan: regular 57.6px grotesk, line height 1, -0.05em tracking, with the first line beginning at the main content rail and subsequent lines returning to the page margin.
- An empty left rail acts as the organizing device: a nine-column desktop grid with 18px gutters reserves its first two columns for section labels, leaving 1088px of media at a 1440px viewport.
- Interface color stays neutral while the work carries color: #fafbfc canvas and #202020 text across the page, with muted labels at 50% ink opacity; color and deep dark fields are confined to rectangular media.
- Proof is exhibited, not boxed: one 1088×725px landscape stage or paired 535px-wide stages, square corners, no shadows on the containers, and captions 8px beneath the images. Include a composed product or interface exhibit even when photography is unavailable.
- Conversion is a typographic gesture rather than a filled button: a 43.2px invitation followed immediately by a same-scale underlined action with a 1px low-contrast bottom rule.
- The ending keeps the index geometry alive: an indented closing invitation above an 80px ruled footer, with copyright at the left and compact 21px stacked contact and legal links on the content rail.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#202020` | `--color-ink` | text, link, action | Brand-defining monochrome ink for all primary typography and actions; the interface has no chromatic accent. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool paper | `#fafbfc` | `--color-canvas` | background, surface | Continuous page canvas and opaque fixed navigation. |
| Section hairline | `#dddedf` | `--color-rule` | border | Visible section rules; constructed with rgba(27,27,27,0.13) over the canvas. |
| Action underline | `#cdcecf` | `--color-action-rule` | border | Visible closing-action underline; constructed with rgba(27,27,27,0.2) over the canvas. |
| Secondary gray | `#8d8e8e` | `--color-muted` | text | Visible result of #202020 at 50% opacity over the canvas; discipline captions and directional labels. |

## Typography

- **Nb akademie pro book webfont** — All marketing text, headings, captions, metrics and links. Neutral neo-grotesk with a book-weight texture; tight, matter-of-fact and unembellished. OpenType features: "tnum". If unavailable, use **Inter**. Use 400 throughout and retain the tight display tracking. Font stack: "Nb akademie pro book webfont", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Nb akademie pro book webfont | 400 | 57.6px | 1 | -0.05em | Long sentence-style opening statements. |
| section-heading | Nb akademie pro book webfont | 400 | 43.2px | 1.3333333333 | -0.05em | Left-rail section names and date-range headings. |
| closing-heading | Nb akademie pro book webfont | 400 | 43.2px | 1 | -0.0266666667em | Closing invitation and related-content heading. |
| closing-action | Nb akademie pro book webfont | 400 | 43.2px | 0.933 | -0.0266666667em | Large underlined contact action. |
| body | Nb akademie pro book webfont | 400 | 21px | 1.095 | -0.015em | Navigation, project names, discipline captions and prose. |
| compact-link | Nb akademie pro book webfont | 400 | 21px | 1 | normal | Stacked footer links and related-content navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case-study results | metric | Nb akademie pro book webfont | 400 | 41px | 0.56 | -0.0273em | Short single-line signed percentages; keep separate from prose. |
| case-study results | metric-label | Nb akademie pro book webfont | 400 | 17.3px | 1.33 | -0.0185em | Small sentence-case label above each result. |

**Notes:**

- Use one regular weight for the hierarchy; size, placement and opacity do the separating.
- Opening and section headings share -0.05em tracking; closing typography relaxes to about -0.027em.
- Body captions remain the same 21px size as navigation. Secondary information becomes lighter, not smaller.
- The metric line box is deliberately shorter than its glyph height. Keep values on one line with surrounding space.

## Layout

**Density:** Airy in composition, compact within captions and utility text; large blank rails coexist with tightly stacked labels.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Image-to-caption gap. |
| 16px | Repeated-grid row gaps, footer top inset and closing-rule top inset. |
| 18px | Main side margins, media gutters and section-rule inset. |
| 19.2px | Paragraph bottom margin in detailed narratives. |
| 42px | Space after project-grid content. |
| 48.8px | Separation before the closing section. |
| 65px | Bottom breathing space within the closing invitation block. |
| 108px | Opening heading top margin below the viewport top. |
| 106.6px | Opening heading bottom margin before the first proof section. |

### Containers and grids

- **desktop framework**: 9 columns · gap 18px · side padding 18px. Full-width framework without a fixed maximum width. At 1440px the inner width is 1404px; first two columns form a 298px label rail, then the main rail begins at 334px.
- **proof grid**: 2 columns · gap 18px. Main rail is 1088px wide at desktop. A full-span stage is 1088px wide; equal paired stages are 535px wide.
- **footer framework**: 9 columns · gap 16px · side padding 16px. Footer rule spans nearly the page width. Copyright occupies the left rail, followed by contact and legal columns; the right side stays open.
- **narrative grid** (only for case-study results and credits): 3 columns · gap 16px. Three 352px columns occupy the main rail; left outer rail carries a date or contextual label.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and actions | 0px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Entire page and navigation backdrop.

**CSS:** `background: #fafbfc; color: #202020`

**Observed:** One continuous cool-white field, without alternating section bands.

**Transfer:** Let the media establish tonal changes rather than changing the page background.

#### Ruled section · level 0

**Use:** Section divisions, footer and indented contact area.

**CSS:** `border-top: 1px solid rgba(27, 27, 27, 0.13); padding-top: 18px`

**Observed:** Rules replace filled panels. Most span the full inner page; the closing rule spans only the main content rail.

**Transfer:** Use a single top rule to organize a new chapter; keep sides and bottom open.

## Components

### Fixed index navigation

**Use:** Persistent page identity, context and two destination links.

**CSS:** `display: grid; position: fixed; top: 0px; width: 100%; height: 52px; grid-template-columns: repeat(9, 1fr); column-gap: 18px; row-gap: 16px; padding: 12.8px 18px 0px; background: #fafbfc; z-index: 2000`

**Text style:** `body` — Nb akademie pro book webfont 400 · 21px/1.095 · tracking -0.015em

**Observed:** Identity sits on the outer left rail, contextual descriptor begins at the main content rail, and two text links align to the far right. Current destination is muted.

**Transfer:** Use a product name, a short category descriptor and two essential destinations.

### Project exhibit

**Use:** Clickable visual proof item.

**CSS:** `position: relative; max-width: 100%; border-radius: 0px`

**Text style:** `body` — Nb akademie pro book webfont 400 · 21px/1.095 · tracking -0.015em

**Observed:** A borderless rectangular image or video leads; a two-line caption follows. The lead exhibit spans both media columns; smaller exhibits appear in pairs. Landscape media is approximately 3:2.

**Transfer:** Make the entire exhibit the link, not a detached button beneath it.

### Two-line caption

**Use:** Identify an exhibit and its discipline or format.

**CSS:** `margin-top: 8px; color: #202020`

**Text style:** `body` — Nb akademie pro book webfont 400 · 21px/1.095 · tracking -0.015em

**Observed:** Title on the first line, category on the next line with 0.5 opacity; both lines align with the media edge.

**Transfer:** Use a concise object name followed by a factual medium or capability.

### Underlined contact action

**Use:** Primary conversion at the close.

**CSS:** `color: #202020; border-bottom: 1px solid rgba(27, 27, 27, 0.2); font-size: 43.2px; line-height: 40.3px; letter-spacing: -1.2px`

**Text style:** `closing-action` — Nb akademie pro book webfont 400 · 43.2px/0.933 · tracking -0.0266666667em

**Observed:** Plain large text directly below the invitation. The underline follows the label width rather than spanning a panel.

**Transfer:** Use a short human action and let its width determine the underline.

### Compact footer links

**Use:** Contact channels and legal destinations.

**CSS:** `color: #202020; font-size: 21px; line-height: 21px; letter-spacing: normal`

**Text style:** `compact-link` — Nb akademie pro book webfont 400 · 21px/1

**Observed:** Three contact links stack tightly in one column; two legal links occupy the next. No icons or button shells.

### Ruled footer

**Use:** Final compact information band.

**CSS:** `display: grid; grid-template-columns: repeat(9, 1fr); gap: 16px; border-top: 1px solid rgba(27, 27, 27, 0.13); margin: 0px 16px 16px`

**Text style:** `compact-link` — Nb akademie pro book webfont 400 · 21px/1

**Observed:** An 80px-deep band uses the outer left rail for copyright and the indented rail for Compact footer links. Text begins 16px below the rule.

**Transfer:** Preserve the asymmetry and short height instead of adding a broad multi-column sitemap.

### Results triplet

**Only for:** case-study results

**Use:** Present measured outcomes above the project narrative.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px`

**Text style:** `metric` — Nb akademie pro book webfont 400 · 41px/0.56 · tracking -0.0273em

**Observed:** Each column starts with a smaller label, then a signed percentage 19px below it; prose continues beneath. All values use the same ink as ordinary text, without charts.

**Transfer:** Use three genuinely supported outcomes; labels use metric-label and values use metric.

### Related project navigation

**Only for:** case-study endings

**Use:** Continue discovery before the shared contact close.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px`

**Text style:** `compact-link` — Nb akademie pro book webfont 400 · 21px/1

**Observed:** A large left-rail heading introduces two compact directional links in the main rail. A 50%-opacity direction label sits above a full-ink project title; a third main-rail column remains empty.

## Imagery and graphics

### Staged digital exhibits

**Use:** Signature proof imagery in the opening and repeated visual index.

**Observed:** Large interface views appear inside black or dark olive-gray fields, sometimes on tilted black screens with cropped device edges. Other pieces use straight-on browser compositions on tan, gray or black backing. Media dominates the main rail while captions remain outside it; color is restrained but not removed.

**Transfer:** Create an equivalent product demonstration in a square-edged landscape stage. If no photography exists, use a real interface view on a dark neutral field or a carefully typeset product artifact, never an empty frame.

**Build:** Use a 3:2 rectangular stage; place a product view at roughly 75% of its width, centered or slightly low. For the physical-screen variant, wrap it in a thin dark device bezel, apply modest perspective rotation, and let an edge approach or pass the frame boundary. Keep the backing flat and low-saturation; any object shadow belongs inside the artwork, not on the page container.

### Material touchpoint studies

**Only for:** physical-product and identity case studies

**Use:** Extended proof galleries showing the system across formats.

**Observed:** Black cards, bags and stacked boxes are photographed or rendered against warm ivory. Paired portrait frames alternate with wide views of books, storefronts and interface systems. Paper grain, fabric folds, soft contact shadows and diffuse light make minimal objects tactile.

**Transfer:** Show the new product's packaging, documents, hardware or tangible outputs with the same soft ivory backing and low-color light. Use actual contextual photography for architectural or in-use views.

### Portrait and product pairs

**Only for:** fashion or people-led case studies

**Use:** Demonstrate image direction alongside product and identity work.

**Observed:** Full or three-quarter figures in dark clothing sit against warm pale backgrounds, with natural skin color and soft directional light. Portrait frames are 535×713px and pair evenly across the main rail.

**Transfer:** Use people or real objects relevant to the product, retaining restrained lighting, uncluttered backing and equal frame proportions rather than treating portraits as decorative avatars.

## Section recipes

How recurring sections are built.

### First screen: Indented statement opening

**Observed:** Paper canvas sits behind Fixed index navigation; the first text begins 108px from the viewport top. The display is a long sentence in regular 57.6px type, line height 1 and -0.05em tracking, occupying roughly four lines. Its first line begins at the main content rail while following lines return to the outer 18px margin. A broad pause leads to a full-width hairline around 445px down. Below it, a 43.2px left-rail heading sits beside a 1088px-wide Project exhibit beginning around 464px. Within the first 900px, navigation, the entire statement, section label and the upper portion of the dark device exhibit are visible; its caption and the rest of the gallery fall below. There is no hero button or supporting microcopy layer.

**Transfer:** Write a specific multi-line promise and preserve the paragraph-like indent. Introduce a strong staged product view on the right rail beneath it; use a clean interface composition if physical media is unavailable. Detail pages use the same display recipe but a flush-left project description of about three lines, followed by labeled media rather than an index heading.

**Avoid:** Do not center a short slogan above two pill buttons, add a badge row, or shrink the exhibit to a floating thumbnail.

**Text style:** `display` — Nb akademie pro book webfont 400 · 57.6px/1 · tracking -0.05em

### Labeled proof index

**Observed:** Ruled section contains a left-rail section-heading and a right-rail proof grid. A full-width Project exhibit can precede pairs; other chapters use an equal two-column grid with 18px horizontal gutters and 16px row gaps. Two-line caption follows each image.

**Transfer:** Group visual evidence by capability, release, period or customer problem. Vary exhibit emphasis without changing the underlying rail alignment.

**Text style:** `section-heading` — Nb akademie pro book webfont 400 · 43.2px/1.3333333333 · tracking -0.05em

### Open invitation close

**Observed:** The main rail alone receives a top rule; its left rail remains empty. Closing-heading and Underlined contact action stack as two lines with no supporting paragraph. The section occupies 245px, followed by Ruled footer. On detail pages, Related project navigation appears before this shared close.

**Transfer:** End with a conversational invitation and one direct action. Retain the open space beneath and the compact footer rather than turning the close into a colored promotion.

**Text style:** `closing-heading` — Nb akademie pro book webfont 400 · 43.2px/1 · tracking -0.0266666667em

### Extended exhibit gallery

**Only for:** case studies

**Observed:** A narrow left rail names the current medium while the main rail alternates 1088×725px landscapes, paired 535×713px portraits and occasional shallow demonstrations. Gaps are usually 18px; captions and explanatory prose do not interrupt every image.

**Transfer:** Show a system across several real contexts, using landscape and portrait evidence appropriate to the subject rather than repeating a single mockup.

### Results and editorial account

**Only for:** case studies

**Observed:** A full-width top rule introduces a date in the left rail and Results triplet in the main rail. Beneath it, three 352px prose columns use body typography with 19.2px paragraph margins. A subsequent rule separates compact service and collaborator credits.

**Transfer:** Connect measured outcomes to the challenge, work and rationale in compact independent columns; include factual credits where collaboration matters.

**Text style:** `body` — Nb akademie pro book webfont 400 · 21px/1.095 · tracking -0.015em

## Page flow

**Storyline:** Personal promise → exhibited proof → deeper context where useful → human invitation → compact contact index.

### Introduce a design-led offer through a curated visual index

1. **Promise** — Long indented statement describes what is made and how the practice works.
2. **Visual proof** — A large lead exhibit followed by paired examples gives immediate range.
3. **Breadth** — A second ruled chapter organizes more work with the same caption system.
4. **Closing call** — Indented invitation and underlined contact action lead to a short ruled footer.

**Transfer:** Use the visual index to organize product applications or capability proof, not only portfolio projects.

### Demonstrate the depth and consistency of one engagement

1. **Context** — A flush-left large statement names the deliverable, audience and defining qualities.
2. **Demonstration** — A long sequence of wide and paired media shows digital, physical and in-use touchpoints with left-rail labels.
3. **Quantified proof** — Three restrained percentage results introduce a multi-column account of challenge, decisions and outcomes.
4. **Attribution** — Services and contributor credits form compact ruled lists.
5. **Continued discovery** — Previous and next project links sit under a large related-work label.
6. **Closing call** — The shared invitation and compact footer finish the page.

**Transfer:** Use this variant for product stories or customer outcomes, scaling gallery length to the strength of available evidence.

## Writing

Direct, reflective and craft-conscious. Confidence comes from concrete work and clear intent rather than energetic sales language; the close is warm and personal.

**Do not copy:** Do not reuse the designer's name, client names, identity marks, project artwork, performance percentages, collaborator credits or specific business claims. Source examples illustrate syntax only.

- **Addressing the reader:** First-person singular for the practice; collaborative we/us when discussing delivery. The closing invitation speaks inclusively to the reader rather than issuing a command.
- **Rhythm:** The hero is a full multi-clause statement, not a three-word punchline. Index labels are one or two factual words; detailed prose uses compact paragraphs and sentence case. Actions are short and conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | State the deliverable, then name the qualities pursued and the way the work happens. | Two sentences, roughly 25–35 words. | “I create scalable digital experiences and brand identities, striving for logic, clarity and craft. I work with multidisciplinary teams, carefully curated to fit the needs of the project.” |
| Chapter label | Use a plain organizational noun or date range, without a marketing claim. | One word or a short range. | “Featured”<br>“2018—2020” |
| Exhibit caption | Specific name followed by a factual discipline. | One to four words per line. | “Brand and website” |
| Case narrative | Explain the initial need and the intended change in concrete language. | Short paragraphs of two to four sentences. | “The project began when the founders of Nomen Nescio, Timo and Niina Leskelä, asked us to develop their brand further to reflect the quality of their products.” |
| Closing invitation | Human invitation followed by a direct contact verb. | One short sentence plus a two-word action. | “Let’s get to know each other.”<br>“Reach out” |

**Words and phrasing to use:** logic; clarity; craft; develop; reflect; quality; touchpoints; foundation

**Avoid:** game-changing; revolutionary; unleash; crush it; next-level; limited-time offer

**Rules:**

- Let an exact deliverable or working principle carry the headline rather than a superlative.
- Keep titles and labels in sentence case; reserve numbers for dates and substantiated results.
- Use process explanations to connect visual decisions to a real need.
- Keep conversion language friendly and brief, without urgency or exclamation marks.

## Do's and Don'ts

### Do

- Keep all text at weight 400, including display headings and metrics.
- Align the main proof rail with the navigation descriptor on the nine-column grid.
- Maintain 18px page margins and media gutters at the desktop reference width.
- Place captions 8px beneath media and use 0.5 opacity only on their secondary line.
- Use the 1px low-alpha top rule to introduce new chapters.
- Show at least one composed landscape product exhibit with a roughly 3:2 proportion.
- Keep the closing invitation at 43.2px and place the action directly beneath it.
- Stack footer links at 21px line height rather than spreading them into spacious buttons.

### Don't

- Do not introduce bold or black weights to manufacture hierarchy.
- Do not give media containers rounded corners or interface drop shadows.
- Do not use a saturated page-wide accent band; keep color within the exhibited work.
- Do not compress captions to tiny 12px metadata; the normal label size is 21px.
- Do not center all content in a narrow maximum-width column; retain the empty label rail.
- Do not turn the results triplet into colorful dashboards, gauges or progress bars.
- Do not add icon badges to text-only navigation and footer links.
- Do not expand the footer into a tall sitemap or repeat the full sales pitch there.

## Motion and responsive

### Motion

**Observed:**

- Media is presented in video as well as still-image formats. No action transitions, keyframes or easing declarations are established.

**Transfer:**

- Use moving demonstrations within the same rectangular exhibit frames, keeping the surrounding typography and canvas stable.

**Unknown:**

- Playback controls, autoplay behavior, hover/focus changes and animation timings are not specified.

### Responsive

**Observed:**

- Desktop uses a nine-column outer framework, two-column exhibits and three-column narrative blocks.
- Detail-page CSS includes width breakpoints at 480px, 767px, 768px, 991px and 992px.

**Transfer:**

- For narrower layouts, prioritize preserving caption-to-image attachment and readable long statements. Collapse paired exhibits and narrative columns when their content no longer fits; reduce or remove the empty label rail before making text tiny.

**Unknown:**

- Exact narrow-screen typography, navigation behavior, breakpoint-specific grid assignments and heading visibility are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
