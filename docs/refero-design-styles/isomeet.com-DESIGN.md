# ISO Meet — letters with human texture

## Overview

An airy, predominantly white style that makes a digital product feel personal and creative. Regular grotesk typography is interrupted by delicate italic serif letters, while close-up editorial photography and floating interface fragments lend a tactile human presence. Pale lavender and mint appear in contained product stages, with black pill actions providing the strongest contrast. It suits community platforms, creative tools and approachable product launches with a modest amount of text.

### Essentials

- Headlines have an editorial stutter of serif letters inside sans words: Instrument Sans 400 at 60px/1.12 with -0.02em tracking in the opening, and 48px/1.2 with -0.01em tracking elsewhere; selected letters switch to Instrument Serif italic without changing size.
- The opening is a balanced text-and-portrait stage, not a centered slogan: a roughly 639px text column faces a large rounded photograph occupying nearly half the 1328px content width, with a small white identity card crossing its left edge.
- Conversion feels like one short conversation: a 304px-wide, 48px-high gray email pill sits 12px from a black 48px-high button with an 80px radius; a tiny overlapping-avatar proof line follows 36px below.
- Color belongs to contained objects rather than the canvas: white remains dominant, with #f2f2f2 product panels and two pastel lavender/mint stages; a soft multicolor 16px rim makes a substantial conversion panel feel special.
- The human motif repeats at different scales: an intimate full-color hero photograph, small tilted photo tiles alongside moving category labels, and isolated 80–124px photo tiles floating around a centered closing action. If portraits do not fit, use close-up photographs of people’s work or tactile product details with the same framing.
- Interface proof is dimensional but light: phone mockups and white message or review fragments overlap within 24px-radius panels, while the text remains clear above them; the closing action gains a 76px silver app-emblem tile rather than a dark closing band.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint depth | `#b3e2cf` | `--color-mint` | surface | Stronger end of the mint product-stage gradient. |
| Lavender depth | `#e5d7ff` | `--color-lavender` | surface | Bottom of the lavender product-stage gradient. |
| Mint light | `#ecf7f1` | `--color-mint-light` | surface | Light end of the mint product-stage gradient. |
| Lavender light | `#f7f3ff` | `--color-lavender-light` | surface | Top of the lavender product-stage gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, accent | Headings, emphasized labels, icons and primary action fills. |
| Question ink | `#222222` | `--color-question-ink` | text | Accordion questions, slightly softer than heading black. |
| Choice gray | `#808080` | `--color-choice-text` | text | Radio-option labels; black at 50% opacity over white. |
| Secondary gray | `#999999` | `--color-muted` | text | Supporting paragraphs and navigation; black at 40% opacity over white. |
| Accordion rule | `#cccccc` | `--color-question-rule` | border | Question-row separators; black at 20% opacity over white. |
| Silver edge | `#dcdcdc` | `--color-silver` | surface | Outer shade of the closing emblem’s radial silver surface. |
| Faint edge | `#e6e6e6` | `--color-edge` | border | Card outlines, navigation dividers and footer rules; black at 10% opacity over white. |
| Soft gray | `#f2f2f2` | `--color-panel` | surface | Inputs, radio rows, announcement badge, tab track and neutral product stages. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | The dominant page canvas, floating cards, form interior and reversed button text. The fixed header uses white at 85% opacity. |

## Typography

- **Instrument Sans** — All ordinary text, headings, controls and navigation. Open, clean contemporary grotesk; predominantly regular weight, with medium weight reserved for short functional labels. Font stack: "Instrument Sans", Arial, sans-serif.
- **Instrument Serif** — Individual italic letters embedded within major headings. Narrow, high-contrast editorial italic that creates fleeting handwritten-looking accents inside otherwise plain words. Font stack: "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Instrument Sans | 400 | 60px | 1.12 | -0.02em | Two-line opening promise. |
| display-inset | Instrument Serif | 400 italic | 60px | 1.12 | -0.02em | Selected letters inside the opening promise. |
| heading | Instrument Sans | 400 | 48px | 1.2 | -0.01em | Major section headings, either left aligned or centered. |
| heading-inset | Instrument Serif | 400 italic | 48px | 1.2 | -0.01em | Selected letters within major section headings. |
| feature-title | Instrument Sans | 500 | 28px | 1.5 | -0.013em | Product-stage titles. |
| form-title | Instrument Sans | 500 | 28px | 1.5 | normal | Centered conversion-panel offer heading. |
| benefit-title | Instrument Sans | 500 | 20px | 1.5 | -0.016em | Short benefit-card titles. |
| category | Instrument Sans | 500 | 20px | 1.5 | -0.02em | Moving audience or use-case labels. |
| question | Instrument Sans | 400 | 20px | 1.5 | -0.02em | Accordion questions. |
| lead | Instrument Sans | 400 | 18px | 1.5 | -0.02em | Section support lines and product-stage descriptions. |
| body | Instrument Sans | 400 | 16px | 1.5 | -0.02em | Benefit descriptions, inactive tab text and supporting proof text. |
| navigation | Instrument Sans | 400 | 16px | 1.5 | normal | Header and footer text links, and radio labels. |
| label | Instrument Sans | 500 | 16px | 1.5 | -0.02em | Form labels and emphasized proof counts. |
| button | Instrument Sans | 400 | 16px | 1 | normal | Primary action labels. |
| announcement | Instrument Sans | 500 | 16px | 1.2 | normal | Small sentence-case announcement badge. |
| nav-action | Instrument Sans | 500 | 16px | 1.2 | -0.01em | Outlined header action. |

**Notes:**

- Keep mixed-family letters inline within complete words. The serif is an accent at the same nominal size and weight, not a second headline or a whole italic paragraph.
- Headings remain weight 400. Use weight 500 for short card titles and labels rather than adding a bold display tier.
- Support copy is subdued and narrow: the opening paragraph is limited to 368px; centered section headings commonly occupy 568px. Do not justify text.
- The page’s root size follows calc(0.599109rem + 0.445434vw); rem-based dimensions inherit that fluid relationship. The recipes specify their 1440px desktop sizes.

## Layout

**Density:** Airy; large white intervals isolate the narrative, while form controls and title-description pairs remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Benefit title to description and badge icon to text. |
| 12px | Email field to action; form label to field; adjacent short inputs. |
| 16px | Card icon to text group and centered heading to support line. |
| 20px | Card-grid gutters and opening headline-to-support gap. |
| 32px | Benefit-card padding. |
| 36px | Announcement to headline and form-to-proof spacing. |
| 40px | Product-stage vertical inner padding. |
| 48px | Major content-group gaps, product-stage side padding and conversion-panel padding. |
| 56px | Desktop page side padding. |
| 72px | Standard section top and bottom padding. |
| 120px | Opening top padding and closing section top padding. |
| 132px | Extra breathing room before the first benefit chapter. |
| 220px | Closing section bottom padding before the footer. |

### Containers and grids

- **main-container**: max width 1328px · side padding 56px. Centered marketing content at desktop; header, benefits, product stages, conversion and footer share its edges.
- **benefit-grid**: 3 columns · gap 20px. Three equal 429px-wide benefit cards in one desktop row.
- **product-grid**: 12 columns · gap 20px. Alternating wide and narrow panels: 7/5 column spans on the first row, then 5/7; panel widths are 766px and 542px, each 480px tall.
- **centered-heading**: max width 568px. Centered headings and closing-call copy remain short enough for two lines.
- **conversion-grid**: 2 columns · gap 20px. Left-side headline and bottom-aligned questions face a substantial framed form on the right.
- **form-content**: max width 480px. Input content inside the larger conversion panel, with a centered 400px-wide title above.

## Corner radius

| Element | Radius |
| --- | --- |
| primary controls | 80px |
| header action and tabs | 160px |
| announcement badge | 48px |
| content cards | 24px |
| conversion exterior | 40px |
| conversion interior | 32px |
| floating photo tiles | 12px |
| emblem tile | 16px |
| benefit icon backing | 14px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating portraits | `4px 12px 12px 0px rgba(0, 0, 0, 0.09), 1px 3px 7px 0px rgba(0, 0, 0, 0.1)` | Small detached photo tiles around the closing action. |
| selected tab | `0px 1px 1px 0px rgba(0, 0, 0, 0.08), 0px 2px 4px 0px rgba(0, 0, 0, 0.12), 0px 0px 0px 0.5px rgba(0, 0, 0, 0.04)` | White active segment inside the soft gray tab track. |
| emblem relief | `0px 1px 4px 0px rgba(0, 0, 0, 0.07), 0px 1px 2px 0px rgba(0, 0, 0, 0.13)` | Silver app-emblem tile above the final call. |

### Surfaces

#### White canvas · level 0

**Use:** Continuous light page foundation.

**CSS:** `background: #ffffff; color: #000000`

#### Glass header · level 2

**Use:** Fixed navigation over scrolling content.

**CSS:** `background: rgba(255, 255, 255, 0.85); border-bottom: 1px solid rgba(0, 0, 0, 0.1); backdrop-filter: blur(56px)`

**Observed:** The header is only 72px tall and stays visually white, with a fine lower rule.

**Transfer:** Use translucency solely for navigation, not as a general card material.

#### Outline benefit · level 1

**Use:** Light grouping without a filled tile.

**CSS:** `border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 24px`

**Observed:** White interiors merge with the canvas; no strong shadow.

**Transfer:** Use for compact reasons or outcomes.

#### Neutral stage · level 1

**Use:** Large product demonstration panels.

**CSS:** `background: #f2f2f2; border-radius: 24px; overflow: clip`

**Observed:** Light gray fills support phone imagery and detached white UI cards.

**Transfer:** Keep the background lower contrast than the illustrated product.

#### Lavender stage · level 1

**Use:** One contrasting product demonstration panel.

**CSS:** `background: linear-gradient(#f7f3ff, #e5d7ff); border-radius: 24px; overflow: clip`

#### Mint stage · level 1

**Use:** A second pastel product demonstration panel.

**CSS:** `background: linear-gradient(170deg, #ecf7f1, #b3e2cf); border-radius: 24px; overflow: clip`

#### Conversion interior · level 1

**Use:** White interior inside the multicolor conversion rim.

**CSS:** `background: #ffffff; border-radius: 32px; padding: 48px`

**Observed:** A 16px frame surrounds a 622px-wide white panel; the interior stays uncolored.

**Transfer:** Apply the rim to one important commitment module, not every card.

#### Silver emblem · level 1

**Use:** Small app-like emblem above the closing headline.

**CSS:** `background: radial-gradient(circle at 50% 20%, #ffffff 30%, #dcdcdc); border-radius: 16px; box-shadow: 0px 1px 4px 0px rgba(0, 0, 0, 0.07), 0px 1px 2px 0px rgba(0, 0, 0, 0.13)`

**Observed:** A centered monochrome symbol sits inside a 76px square.

**Transfer:** Use the new product’s simple symbol as a tactile stamp.

## Components

### Fixed navigation

**Use:** Persistent orientation and a secondary conversion link.

**CSS:** `height: 72px; padding: 0px 56px; background: rgba(255, 255, 255, 0.85); border-bottom: 1px solid rgba(0, 0, 0, 0.1); backdrop-filter: blur(56px); z-index: 1000`

**Text style:** `navigation` — Instrument Sans 400 · 16px/1.5

**Observed:** Brand mark at the far left, a short vertical divider, then four text links; a small outline action is aligned to the far right. The navigation wrapper is fixed.

**Transfer:** Use short section anchors rather than a dense menu.

### Primary button

**Use:** Submit a lightweight signup or continue a commitment flow.

**CSS:** `background: #000000; color: #ffffff; border-radius: 80px; padding: 16px 20px; height: 48px; display: flex; align-items: center`

**Text style:** `button` — Instrument Sans 400 · 16px/1

**Observed:** Text-only black pill, placed beside the email input or centered at the bottom of a larger form. Its width follows its label.

### Outline action

**Use:** Compact navigation-level conversion.

**CSS:** `border-radius: 160px; padding: 10px 16px; outline: 1px solid rgba(0, 0, 0, 0.1); outline-offset: -1px; color: #000000; display: flex; align-items: center; justify-content: center`

**Text style:** `nav-action` — Instrument Sans 500 · 16px/1.2 · tracking -0.01em

**Observed:** A thin inset outline surrounds a short label; the page remains visible through the interior.

### Email pill

**Use:** Low-friction email collection in the opening and closing call.

**CSS:** `background: #f2f2f2; border-radius: 80px; padding: 8px 16px 8px 18px; height: 48px; width: 304px`

**Observed:** No visible dark border. Placeholder text is muted. The same shape extends to longer form inputs and radio rows.

**Transfer:** Pair with Primary button using a 12px horizontal gap; do not enclose the pair in a second filled capsule.

### Announcement badge

**Use:** A short launch-status or availability note above the promise.

**CSS:** `background: #f2f2f2; border-radius: 48px; padding: 10px 16px; display: grid; gap: 8px; align-items: center`

**Text style:** `announcement` — Instrument Sans 500 · 16px/1.2

**Observed:** Small black platform symbol before one sentence-case line; visually subordinate to the headline.

### Benefit card

**Use:** Explain a concise reason to choose the product.

**CSS:** `border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 24px; padding: 32px; display: grid; gap: 16px`

**Text style:** `benefit-title` — Instrument Sans 500 · 20px/1.5 · tracking -0.016em

**Observed:** A small monochrome icon in a 48px gray square comes first, then a medium title and muted body copy separated by 8px. Three cards share a row.

**Transfer:** Keep the description to two or three short lines.

### Product stage card

**Use:** Show one tangible capability through composed interface imagery.

**CSS:** `background: #f2f2f2; border-radius: 24px; padding: 40px 48px; height: 480px; position: relative; overflow: clip`

**Text style:** `feature-title` — Instrument Sans 500 · 28px/1.5 · tracking -0.013em

**Observed:** Title and support line are placed near a corner, above oversized phone and floating UI layers. Wide neutral and narrower pastel variants alternate across the grid; the final wide card places its text low on the left.

**Transfer:** Use one legible product operation per stage rather than a full dashboard.

### Segmented switch

**Use:** Switch between two user perspectives on the capability story.

**CSS:** `background: #f2f2f2; border-radius: 160px; padding: 4px; display: flex; width: 192px; height: 44px; justify-content: center; align-items: center`

**Text style:** `body` — Instrument Sans 400 · 16px/1.5 · tracking -0.02em

**Observed:** Two equal segments. The selected segment is white with a soft shadow, black text, 6px 24px padding and a 160px radius; the inactive segment is unfilled with muted text.

**States:** Seen: selected segment has white fill and black text; inactive segment has no fill and 40%-black text.

**Transfer:** Use only when the product genuinely has two complementary perspectives.

### Question row

**Use:** Handle practical objections alongside conversion.

**CSS:** `border-bottom: 1px solid rgba(0, 0, 0, 0.2); padding: 24px 0px; color: #222222`

**Text style:** `question` — Instrument Sans 400 · 20px/1.5 · tracking -0.02em

**Observed:** Question on the left, small black plus sign on the far right. Rows are about 79px tall when closed; there is no card fill.

### Proof line

**Use:** Provide compact reassurance directly below an email form.

**CSS:** `display: grid; gap: 8px; align-items: center`

**Text style:** `label` — Instrument Sans 500 · 16px/1.5 · tracking -0.02em

**Observed:** A tiny overlapping avatar stack precedes a black medium-weight count and a regular muted continuation on the same line. It appears 36px below the control row.

**Transfer:** Use a verified metric or a similarly brief trust statement, not an oversized statistic.

### Footer links

**Use:** Provide a restrained utility ending.

**CSS:** `display: grid; gap: 4px`

**Text style:** `navigation` — Instrument Sans 400 · 16px/1.5

**Observed:** The white footer has a mark and a two-line maker statement on the left, with Sitemap and Email columns on the right. Muted links have 4px vertical padding. Thin rules separate the main footer and the bottom copyright/social row.

**Transfer:** Preserve the compact, human maker note and spare right-side utilities instead of adding a large sitemap.

## Imagery and graphics

### Editorial portrait stage

**Use:** Primary opening image and human point of entry.

**Observed:** An extreme close-up face with visible skin texture and a pale pink flower in the foreground, against a muted sage background. The photograph is warm and natural rather than glossy stock imagery. It fills a large near-square rounded rectangle on the right, with a broad soft shadow below and a small white identity/rating card overlapping the left edge. Small carousel dots sit below.

**Transfer:** Use a tightly framed person, their craft or a tactile product detail; retain nuanced skin/material texture, subdued natural background color and a foreground detail. The minimum version is one strong photograph plus a simple white identity or contextual caption card.

**Build:** Set a cover-fit photograph in a near-square rounded wrapper roughly half the desktop content width. Place a soft black shadow with low alpha beneath it, and overlap a white rounded caption containing a small avatar, a short name and one context line. Use five neutral dot controls below, with the active dot larger and darker.

### Floating product compositions

**Use:** Product-stage cards.

**Observed:** Black-rimmed upright phone mockups occupy much of each card and extend beyond its lower boundary. White message, hiring, metadata and review cards float across them; some are tilted. Cropped human photographs within the UI link the product back to the opening portrait. Lavender and mint stages alternate with light gray.

**Transfer:** Show the new product’s real interface with one oversized device or primary panel and one or two detached functional fragments. For a non-app product, compose a close-up object and a white specification or result card. Preserve clear space for the title.

**Build:** Use a clipped 24px-radius stage. Anchor one device image toward the bottom or side and layer one white rounded interface fragment in front, with a light shadow. On narrower pastel panels, rotate a backing plate and foreground content slightly in opposing directions; do not rotate the section copy.

### Category photo ticker

**Use:** Full-width audience or use-case interlude.

**Observed:** Two horizontal lanes pair short black category labels with small, rounded photographic tiles tilted by a few degrees. The lanes run beyond the viewport and fade softly at the edges, under a centered heading.

**Transfer:** Translate categories into relevant user types, workflows or application contexts; use genuine photographs of their work or tools when portraits are unavailable.

**Build:** Create two overflow-hidden horizontal lanes containing duplicated inline groups. Each group pairs a roughly 60px photo tile with a 20px medium label. Alternate slight rotations on the photos. Apply a horizontal mask that fades both ends to transparent; animate the lanes in opposite directions with 30s linear infinite movement.

### Multicolor conversion rim

**Use:** Emphasize a substantial conversion panel without coloring its contents.

**Observed:** A soft, blurred-color border runs around the tall form: pink and mauve along the upper-left edge, peach at the upper right and olive green near the lower right. Only a 16px rim remains visible around the white interior.

**Transfer:** Retain a softly blended chromatic rim around one high-value action module. The interior, inputs and typography remain neutral; exact color stops are not essential.

**Build:** Use a 40px-radius outer wrapper with 16px padding. Build its background from broad, blurred pink, peach and olive fields using layered radial gradients, for example rgba(210,75,130,0.65) near the upper left, rgba(205,155,120,0.65) near the upper right and rgba(108,145,57,0.75) near the lower right over a pale neutral ground. Insert a white 32px-radius inner panel so only the rim shows.

### Closing portrait constellation

**Use:** Human surround for the final conversion invitation.

**Observed:** Small detached photographic tiles are scattered well outside the centered text/form column, with some partly cut off by the viewport. They range from 80px to 124px, have 12px rounded corners and soft offset shadows; some are reduced to 60% opacity. The center remains clear. A silver emblem tile precedes the headline.

**Transfer:** Repeat details from the visual world established in the opening: people, work or product materials. Keep at least several detached tiles, even if the new product has no portrait library; close-up detail photos are sufficient.

**Build:** Position four to six rounded photo tiles around a central 568px text column, leaving the control row unobstructed. Use 80px and 124px sizes with the Floating portraits shadow; reduce secondary tiles to 0.6 opacity and let one tile on each side intersect the outer section edge. Center the Silver emblem above the headline.

### Icons

**Observed:** Small black monochrome symbols; benefit icons appear visually as fine outline motifs within 48px pale-gray rounded squares, with 24px SVG bounds. The announcement uses a 16px solid platform symbol. Accordion controls use simple black plus signs.

**Transfer:** Use simple single-color functional symbols and keep them smaller than the text groups they introduce. Reserve the largest monochrome symbol for the silver closing emblem.

## Section recipes

How recurring sections are built.

### First screen: Portrait-and-promise opening

**Observed:** A white first screen beneath Fixed navigation balances a left copy column with a large right portrait. The content container has 56px side padding and 1328px maximum width. The text is vertically centered against the image: Announcement badge, a two-line display heading, a 368px-wide muted support paragraph, then Email pill and Primary button with Proof line underneath. Display type is regular sans with selected italic serif letters. Back-to-front layers are white canvas, a broad soft image shadow, rounded photograph, overlapping white identity card and the fixed translucent navigation. Within the first 900px, the complete badge, headline, support, controls, proof, portrait, identity card and carousel dots are visible; the opening’s lower divider and the next section are below the fold. The overall opening is 935px tall.

**Transfer:** Create an equally strong photo-led split opening with one textured human or product-detail photograph if a portrait is not appropriate. Keep the mixed-letter headline, immediate action and contextual overlap card. Other page types can open with a shorter heading pair, but retain the editorial letter treatment and a concrete visual object.

**Avoid:** Do not replace this with a centered full-width headline, a full-bleed background photograph, or an enormous device mockup that pushes signup below the first screen.

**Text style:** `display` — Instrument Sans 400 · 60px/1.12 · tracking -0.02em

### Reason-and-benefit chapter

**Observed:** A two-column heading pair aligns a 48px left headline with a short muted support paragraph at the bottom of the right column. A 48px gap leads into three Benefit cards. This chapter has 132px top padding and 72px bottom padding.

**Transfer:** Present the reader’s friction in the heading and give three concrete outcomes in the cards, with minimal prose.

**Text style:** `heading` — Instrument Sans 400 · 48px/1.2 · tracking -0.01em

### Audience interlude

**Observed:** A centered mixed-letter heading precedes the Category photo ticker by 48px. The section is full width rather than constrained to the main container, with 72px vertical padding and clipped outer edges.

**Transfer:** Use the moving photo-and-label device to show breadth without creating a dense directory.

**Text style:** `heading` — Instrument Sans 400 · 48px/1.2 · tracking -0.01em

### Alternating capability stages

**Observed:** A centered heading and support line lead into Segmented switch, then a 12-column grid of Product stage cards. The grid uses 20px gutters, alternating 766px and 542px widths and 480px panel heights. Neutral stage, Lavender stage and Mint stage hold the Floating product compositions.

**Transfer:** Adapt panel count and placement to the product story; keep alternating scale, contained pastels and oversized cropped objects. Use the switch only for meaningful alternative perspectives.

**Text style:** `heading` — Instrument Sans 400 · 48px/1.2 · tracking -0.01em

### Commitment with objections

**Observed:** A left-aligned 48px heading sits above a long white interval and a stack of Question rows. Opposite it, a tall framed conversion panel combines Multicolor conversion rim, Conversion interior, a centered 28px offer heading, a 480px-wide form and a centered black action. Short name fields share a row; longer inputs and choices stack below.

**Transfer:** Pair the most important action with the practical questions that could block it. Match the framing and form hierarchy without inheriting any particular offer or price.

**Text style:** `heading` — Instrument Sans 400 · 48px/1.2 · tracking -0.01em

### Human closing invitation

**Observed:** A centered Silver emblem sits above a two-line mixed-letter headline and one muted support sentence. Email pill, Primary button and Proof line repeat the opening action. Closing portrait constellation leaves a large white center and wide bottom breathing room: 120px top padding and 220px bottom padding.

**Transfer:** Repeat the same primary conversion as the opening while returning to the human or tactile image motif; keep the surrounding photo fragments rather than replacing the ending with a generic colored band.

**Text style:** `heading` — Instrument Sans 400 · 48px/1.2 · tracking -0.01em

### Maker-and-utility footer

**Observed:** The white 341px footer starts and divides with faint rules. Its 261px main area has a simple mark and two-line maker note left, with two small link columns right. The final 80px row places a short copyright/location line left and a social prompt with a 32px circular icon right.

**Transfer:** Close with concise provenance about the new product’s makers, basic navigation and a direct contact route. Keep the footer lower in contrast and density than the conversion section.

## Page flow

**Storyline:** promise and immediate action → reasons to believe → breadth of relevance → tangible capability proof → commitment with objections → human invitation → spare utilities

### Introduce a new product, make it feel populated and trustworthy, and convert interest into an early commitment

1. **Promise** — Split photo-led opening with editorial mixed-letter headline, email signup and compact social reassurance.
2. **Reasons to believe** — Left/right heading pair followed by three light outline benefit cards.
3. **Breadth of relevance** — Centered headline over moving photographic category lanes.
4. **Capability proof** — A two-perspective switch and alternating neutral/pastel product stages with dimensional interface layers.
5. **Commitment and objection handling** — Tall multicolor-rimmed conversion form faces a headline and practical question accordion.
6. **Closing call** — Centered emblem, invitation, repeated email signup and proof, surrounded by floating photo tiles.
7. **Utilities** — White ruled footer with maker note, short sitemap, email and a slim social/copyright row.

**Transfer:** Use the narrative as a flexible progression from personal promise to concrete proof and commitment. The signature letter mixing, photographic ticker, contained pastel demonstrations, special conversion rim and human closing surround can be positioned to suit a shorter or longer story rather than copied as a fixed section sequence.

## Writing

Warm, practical and casually confident. The product speaks like people who know the reader’s frustrations, with conversational assurances rather than grand technical claims.

**Do not copy:** Do not reuse ISO Meet names, logos, people’s identities, customer imagery, user counts, prices, launch promises, testimonials or maker affiliations. Source examples illustrate tone only; all new claims and proof must belong to the new product.

- **Addressing the reader:** Address the reader as you and your; use we when explaining the team’s motivation or the work already done for the reader.
- **Rhythm:** Short declarative fragments can build a headline before a plain-language payoff. Support lines usually stay to one sentence; benefit descriptions use one or two short sentences. Questions are literal and practical.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Three clipped action verbs followed by a reassuring simplification. | About 10 words across two lines | “Meet. Collaborate. Hire. Finally, all in one place.” |
| Section headline | Name a familiar frustration or tell the reader the difficult work is already handled. | 6–14 words | “Because creative work shouldn’t be this complicated”<br>“We’ve done the hard part, now it’s your turn to create” |
| Support line | Explain the benefit directly, with a natural dash or a simple connective rather than jargon. | 12–20 words | “We’ve lived the creative chaos ourselves — so we built a simpler way to connect and collaborate.” |
| Benefit title | A short result-oriented noun phrase with a friendly qualifier. | 3–6 words | “Fair, Friction-Free Booking”<br>“A Community You Can Trust” |
| Primary action | Use a personal commitment or clearly name the next step. | 3–4 words | “Reserve My Spot”<br>“Continue to checkout” |
| Practical question | Ask the reader’s real question in first person. | 5–12 words | “Is the payment refundable?”<br>“What happens after I reserve my username?” |

**Words and phrasing to use:** all in one place; your turn; simpler; clear; trust; no more; built by people; connect

**Avoid:** synergize; enterprise-grade transformation; revolutionary ecosystem; disruptive paradigm; unparalleled excellence

**Rules:**

- Let the main promise name things people can do, then explain why doing them becomes easier.
- Describe a specific friction before promising relief; use ordinary nouns and verbs.
- Keep benefit titles brief enough for one line at 20px; supporting details belong below.
- Write form labels as direct questions when that feels more personal than a field name.
- Keep the closing invitation and primary action consistent with the opening conversion goal.

## Do's and Don'ts

### Do

- Keep opening headlines at 60px and regular weight, with matching-size italic serif letters inside words.
- Use 48px section headings and restrained 18px gray support copy.
- Align primary content to a 1328px container with 56px desktop side padding.
- Maintain 20px gutters in card grids and 24px card corners.
- Pair a 48px gray input with a 48px black pill rather than separating the signup into multiple steps.
- Confine lavender and mint to product stages, leaving the majority of the page white.
- Give the final invitation a clear 568px center, a silver emblem and detached photographic tiles.
- Use 1px low-alpha rules to separate the footer and compact question rows.

### Don't

- Do not make the headline sans bold or turn the serif accents into whole decorative words.
- Do not paint primary buttons lavender or mint; the strongest action contrast is black against white.
- Do not assign 24px card corners to every control; inputs and actions use much fuller 80px pills.
- Do not add heavy shadows to outline benefit cards; their grouping comes from a faint edge.
- Do not turn the conversion rim into a saturated full-panel gradient; its white interior must remain dominant.
- Do not enlarge the small reassurance count into a monumental statistics band.
- Do not cram a dashboard wall into each product stage; one primary object and a few detached details provide depth.
- Do not reverse the footer to black or inflate it into many dense navigation columns.

## Motion and responsive

### Motion

**Observed:**

- Category lanes declare 30s linear infinite scroll animations, including forward and reverse directions.
- The opening contains five carousel indicators, with a larger darker active indicator.
- No hover/focus transitions were identified for actions or surfaces.

**Transfer:**

- Use opposing, continuous linear motion for the photo-and-label lanes rather than bounce or stepped transitions.
- Keep carousel indicators small and neutral so photography stays primary.

**Unknown:**

- Carousel timing, opening-scene transitions, scroll-reveal timing and hover/focus appearance are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 375px, 479px, 767px, 991px and 1440px.
- The root font size uses calc(0.599109rem + 0.445434vw), allowing rem-based dimensions to vary with the viewport.

**Transfer:**

- On narrow layouts, stack opening copy and portrait without losing the overlapping context card or the mixed-family headline.
- Collapse the asymmetric product grid into single panels while keeping neutral/pastel variation and clipped oversized imagery.
- Stack the conversion form and questions; keep its 16px multicolor rim.
- Keep the closing call centered and move surrounding tiles outward rather than letting them collide with controls; allow the ticker to remain horizontally clipped.

**Unknown:**

- Exact mobile typography, side padding, navigation collapse and image placement are not established; the narrow-layout treatments above are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
