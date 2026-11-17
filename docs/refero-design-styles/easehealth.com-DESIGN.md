# Ease Health — botanical systems in flow

## Overview

An airy, light software-marketing style with the warmth of an editorial interior magazine. Forest-green serif headlines sit beside restrained grotesk text, pale leaf-green blocks and dusty blue stages. Simplified interface illustrations, fine flowing line art and sunlit interiors make complex operations feel humane rather than technical. It suits workflow products that need both operational credibility and a sense of relief.

### Essentials

- Relief is expressed as a typographic contrast: light serif promises at 73.9px/1.05 with -0.03em tracking, supported by regular 17.6px/1.5 grotesk text.
- The opening is a pastel control board, not a floating headline: a 1:1.5 split with 21.1px gaps puts a green promise card and separate dark action bar beside a dusty-blue product stage.
- Actions can become architecture: ordinary buttons have 14.1px corners and 14.1px 21.1px padding, while major calls occupy 122px-tall dark-green bars with a 42px outlined arrow.
- Color lives in large bounded fields: #fffefc remains the connective canvas, #0f3e17 carries text and actions, and #e1f4df, #b1dbb8, #cfe7d3 and #b6ced5 fill cards. Dark fields are concentrated in conversion elements rather than making the whole page dark.
- Product stories are staged as cream interface cards on flat pastel backing, not device mockups. Pair the stage with slim capability pills; when no interface exists, construct a legible three-step workflow with connecting lines.
- Fine-line geometry supplies the signature movement: nested forest-green curves and open rectangular contours extend beyond their panels. Include a flowing-line panel in the closing mosaic, built in SVG when original art is unavailable.
- The ending is another hero: a 1.5:1 mosaic combines a 73.9px serif invitation, a separate dark action bar, blue line-art panel and green three-column navigation panel, all with 14.1px corners.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest ink | `#0f3e17` | `--color-ink` | text, background, action, border | Default text, line art and dark conversion fields. |
| Leaf green | `#b1dbb8` | `--color-leaf` | surface, background | Opening promise, testimonial and footer navigation panels. |
| Pale leaf | `#e1f4df` | `--color-pale-leaf` | surface, background | Benefit cards, statistic panels, question cards and closing invitation. |
| Soft mint | `#cfe7d3` | `--color-mint` | surface | Intermediate green card fill in benefit and capability groups. |
| Deep forest | `#0c2f10` | `--color-hover-ink` | action | Declared hover fill for primary buttons and large action bars. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty blue | `#b6ced5` | `--color-blue-stage` | surface, background, accent | Product-art stages, section labels, line-art backing and small capability dots. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Compact button text and resource cards. |
| Warm cream | `#fffefc` | `--color-canvas` | background, surface, text | Continuous page canvas, interface illustration cards and reverse text on dark fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| career listings and detailed product chapters | Warm hairline | `#efeeeb` | `--color-rule` | border | Listing-card outlines and category separators. |
| detailed product chapters | Oat panel | `#f8f6f0` | `--color-oat` | surface | Warm neutral break within a sequence of colored capability cards. |
| resource landing pages | Cool paper | `#f8faf8` | `--color-resource-wash` | background, surface | Contents rows and FAQ band. |
| resource landing pages | Paper edge | `#e5e5e5` | `--color-resource-edge` | border | Document cover and related-resource card outlines. |
| resource landing pages | Editorial gray | `#444444` | `--color-resource-body` | text | Long resource introduction. |
| resource landing pages | Contents gray | `#333333` | `--color-resource-text` | text | Compact contents text and download support. |
| resource landing pages | Muted gray | `#666666` | `--color-resource-muted` | text | Related-resource descriptions. |
| resource landing pages | Download hover | `#173e1e` | `--color-resource-hover` | action | Declared download-button hover fill. |

## Typography

- **Suisseintl** — Body text, navigation, actions, capability titles and statistics. Neutral, even-width grotesk; regular text and unusually light large numerals. If unavailable, use **Inter**. Use 300 for statistics and 400 for normal text; keep tracking neutral below display scale. Font stack: "Suisseintl", "Inter", Arial, sans-serif.
- **Faire Octave** — Promises, section headings, short callouts and quotations. Light editorial serif with sharp contrast, delicate joins and compact spacing. If unavailable, use **Lora**. Use 400 as the lightest available substitute and tune width before changing line breaks. Font stack: "Faire Octave", "Lora", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Faire Octave | 300 | 73.9px | 1.05 | -0.03em | size clamp(3.25rem, 5.25vw, 5.25rem) | Opening promise and monumental closing invitation. |
| heading | Faire Octave | 300 | 56.3px | 1.2 | -0.03em | fixed | Main marketing section headings and dark product-opening headline. |
| stat | Suisseintl | 300 | 56.3px | 1 | -0.03em | size clamp(3.25rem, 4vw, 4rem) | Outcome numbers and short time quantities. |
| callout | Faire Octave | 300 | 40.5px | 1.35 | -0.01em | fixed | Short statements beside oversized line art and explanatory statements. |
| capability-title | Suisseintl | 400 | 28.2px | 1.3 | normal | fixed | Benefit-card and capability-panel titles. |
| quote | Faire Octave | 300 | 24.6px | 1.35 | -0.01em | fixed | Customer quotations in green proof cards. |
| action-large | Suisseintl | 400 | 22.9px | 1.5 | normal | fixed | Wide action bars and large product FAQ questions. |
| body | Suisseintl | 400 | 17.6px | 1.5 | normal | fixed | Hero support, feature explanations and stat descriptions. |
| eyebrow | Suisseintl | 400 | 17.6px | 1 | normal | fixed | Sentence-case text inside dusty-blue section labels. |
| small-body | Suisseintl | 400 | 14.1px | 1.5 | normal | fixed | Benefit descriptions, navigation and compact supporting text. |
| compact-label | Suisseintl | 400 | 14.1px | 1 | normal | fixed | Compact buttons, footer links and capability pills. |
| caption | Suisseintl | 400 | 12.3px | 1.5 | normal | fixed | Small secondary descriptions and utility text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| career landing pages and recruiting closing bands | recruiting-display | Faire Octave | 300 | 64px | 1.25 | -0.03em | fixed | Centered recruiting promise and reversed invitation. |
| career listings and role detail pages | listing-heading | Faire Octave | 300 | 46px | 1.35 | -0.01em | fixed | Openings title and role-detail title. |
| resource landing pages | resource-title | Faire Octave | 400 | 42.2px | 1.15 | -0.03em | size clamp(2rem, 4vw, 3rem) | Document or guide title. |
| career listings | listing-category | Faire Octave | 300 | 31.7px | 1.111 | -0.01em | fixed | Department headings above ruled groups. |
| career listings | listing-title | Faire Octave | 400 | 26.4px | 1.2 | normal | fixed | Clickable role names. |
| resource landing pages | resource-heading | Faire Octave | 400 | 24.6px | 1.2 | -0.03em | fixed | Contents, FAQ and related-material headings. |
| role detail pages | article-body | Suisseintl | 400 | 15.8px | 1.5 | normal | fixed | Long-form description and bullet lists. |
| resource landing pages | resource-intro | Suisseintl | 400 | 15.8px | 1.7 | normal | fixed | Gray explanatory paragraph under a resource title. |
| resource landing pages | resource-card-title | Suisseintl | 600 | 15px | 1.3 | normal | fixed | Related-resource card names. |
| resource landing pages | download-label | Suisseintl | 600 | 14.1px | 1.5 | normal | fixed | Download and print actions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The serif carries promises and human testimony; the sans carries operational explanations. Keep serif display weight light rather than making headings bold.
- Large headings and statistics share -0.03em tracking; smaller serif callouts and quotes relax to -0.01em. Body text has normal tracking.
- Career typography uses the FAIRE Octave Trial declaration; resource and listing typography uses Octave. Treat these as editorial cuts of the same visual family, preserving each scoped recipe.

## Layout

**Density:** Airy between chapters, comfortably packed inside pastel panels; large pauses alternate with deliberately structured card groups.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 7px | Icon-to-label and tight inline gaps. | fixed |
| 14.1px | Capability-pill stacks and FAQ-card gaps. | fixed |
| 17.6px | Footer-link rhythm and resource contents padding. | fixed |
| 21.1px | Default grid gutter and panel-to-action gap. | fixed |
| 28.2px | Label-to-heading separation and recruiting-card padding. | fixed |
| 35.2px | Page side padding and icon-to-benefit-title separation. | fixed |
| 42.2px | Default card padding and larger internal grid gaps. | fixed |
| 56.3px | Heading-block-to-grid gap and resource section padding. | fixed |
| 70.4px | Medium section padding and wide product-panel inset. | fixed |
| 72px | Detailed capability-panel padding. | 5vw |
| 98.6px | Main marketing-section vertical padding. | fixed |
| 140.8px | Exceptional pause before a major benefits chapter. | fixed |

### Containers and grids

- **wide-container**: max width 1450px · side padding 35.2px. Centered outer marketing container, leaving about 1370px of usable width at a 1440px viewport.
- **reading-container**: max width 1042px · side padding 35.2px. Inset section headings, benefit grids and trust sections.
- **opening-grid**: 2 columns · gap 21.1px. Two unequal columns, 1fr 1.5fr; promise and action on the narrower side, product stage on the wider side.
- **proof-grid**: 3 columns · gap 21.1px. Equal-width quote, atmospheric photograph and stacked outcome/action columns.
- **closing-grid**: 2 columns · gap 21.1px. Reverse the opening ratio to 1.5fr 1fr: invitation and action at left, art and navigation at right.
- **editorial-container** (only for career listings and role detail pages): max width 900px · side padding 84.5px. Centered listings or a two-column article with a 280px application rail and 42.2px gap.
- **feature-chapters** (only for detailed product pages): 2 columns · gap 42.2px. A 1fr 4fr navigation-to-content ratio; colored chapter panels occupy the broad right column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing-panels-and-buttons | 14.1px |
|  | section-labels | 7px |
|  | capability-pills | 9999px (pill) |
| detailed product pages | feature-chapter-panels | 21.1px |
| career pages | recruiting-panels | 16px |
| resource landing pages | resource-cards | 12px |
| resource landing pages | document-preview | 10px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| resource landing pages | document-preview | `0px 16px 36px 0px rgba(0, 0, 0, 0.1)` | Lift the document cover off the otherwise flat canvas. |

### Surfaces

#### Cream canvas · level 0

**Use:** Continuous light background.

**CSS:** `background: #fffefc; color: #0f3e17`

#### Pastel panel · level 1

**Use:** Default bounded content surface.

**CSS:** `background: #e1f4df; border-radius: 14.1px; box-shadow: none`

**Observed:** Leaf green and mint variants distinguish neighboring benefits without introducing a new visual language.

**Transfer:** Assign one pastel per panel, not per individual sentence or icon.

#### Blue stage · level 1

**Use:** Interface illustrations and flowing line art.

**CSS:** `background: #b6ced5; border-radius: 14.1px; overflow: hidden`

**Observed:** A flat, low-saturation field backs cream floating objects; no glow, glass or textured material.

**Transfer:** Keep product objects readable against a single quiet hue.

#### Forest field · level 1

**Use:** Large action bars and conversion panels.

**CSS:** `background: #0f3e17; color: #fffefc; border-radius: 14.1px`

**Observed:** Dark areas appear as strong bounded rectangles amid the pale page.

**Transfer:** Reserve the darkest fields for a decisive promise or action.

#### Chapter panel · level 1

**Only for:** detailed product pages

**Use:** Long capability demonstrations.

**CSS:** `background: #b1dbb8; border-radius: 21.1px; padding: 72px; overflow: hidden`

**Observed:** Alternates leaf, oat, dusty blue, mint and forest fields. Some chapters use a split composition, others a full-width interface above supporting text.

**Transfer:** Change composition to fit the workflow, retaining the shared frame.

#### Resource paper · level 1

**Only for:** resource landing pages

**Use:** Contents and question bands.

**CSS:** `background: #f8faf8`

#### Document cover · level 2

**Only for:** resource landing pages

**Use:** Portrait preview.

**CSS:** `border: 1px solid #e5e5e5; border-radius: 10px; box-shadow: 0px 16px 36px 0px rgba(0, 0, 0, 0.1)`

**Observed:** A real typeset document cover, not an abstract download icon.

**Transfer:** Use a readable miniature cover with a graphic header and contents texture.

## Components

### Navigation

**Use:** Persistent desktop wayfinding.

**CSS:** `position: fixed; height: 84px; padding: 0px 35.2px; background: #fffefc; display: flex; align-items: center; z-index: 1000`

**Text style:** `small-body` — Suisseintl 400 · 14.1px/1.5

**Observed:** Brand lockup at left, compact centered text links with small dropdown chevrons, and Primary button at right. The inner grid is 0.5fr 1fr 0.5fr.

**Transfer:** Use a restrained wordmark and a small set of destinations; keep the center visually light.

### Primary button

**Use:** Compact main action in the header and content.

**CSS:** `background: #0f3e17; color: #ffffff; border: 1px solid #0f3e17; border-radius: 14.1px; padding: 14.1px 21.1px`

**Text style:** `compact-label` — Suisseintl 400 · 14.1px/1

**Observed:** Text-only in the header; content versions add a small right arrow. The dark product-opening variant reverses to cream fill and forest text.

**States:** Declared: hover background-color and border-color #0c2f10; focus-visible outline 2px solid #0f3e17 with 2px offset; active outline 0px.

### Action bar

**Use:** Architectural conversion block under the opening or closing promise and proof statistics.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 21.1px; padding: 42.2px; background: #0f3e17; color: #fffefc; border-radius: 14.1px`

**Text style:** `action-large` — Suisseintl 400 · 22.9px/1.5

**Observed:** One left-aligned label and a large unboxed outlined arrow at the far right; approximately 122px tall.

**States:** Declared: hover background-color #0c2f10; focus-visible outline 2px solid #0f3e17 with 2px offset; active outline 0px.

**Transfer:** Keep the entire bar clickable and the label short.

### Section tag

**Use:** Small contextual marker above a serif heading.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 7px; padding: 10.6px; background: #b6ced5; border-radius: 7px`

**Text style:** `eyebrow` — Suisseintl 400 · 17.6px/1

**Observed:** Sentence-case label sized to its text, not a full-width banner. Pale cream is used on a green full-width statement.

### Capability pill

**Use:** Short supporting capabilities inside product panels.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 7px; padding: 8.8px 14.1px; background: #fffefc; border-radius: 9999px`

**Text style:** `compact-label` — Suisseintl 400 · 14.1px/1

**Observed:** A 5px dusty-blue dot precedes text. Pills stack vertically and remain content-width; mint replaces cream on dark chapters.

### Benefit card

**Use:** Scannable benefit triads.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; gap: 28.2px; padding: 42.2px; background: #e1f4df; border-radius: 14.1px`

**Text style:** `capability-title` — Suisseintl 400 · 28.2px/1.3

**Observed:** Thin geometric icon above a sans title, with small-body explanation below; neighboring cards use mint and leaf fills.

**Transfer:** Use one operational benefit per card rather than a list of unrelated features.

### Statistic card

**Use:** Quantified outcome alongside a quotation and photograph.

**CSS:** `padding: 42.2px; background: #e1f4df; border-radius: 14.1px`

**Text style:** `stat` — Suisseintl 300 · 56.3px/1 · tracking -0.03em

**Observed:** A light sans quantity is followed by a regular body-size explanation separated by 14.1px. Two cards stack above an Action bar.

**Transfer:** Keep units attached to the number and put qualifications in the explanation.

### Footer menu

**Use:** Navigation inside the closing mosaic.

**CSS:** `padding: 42.2px; background: #b1dbb8; border-radius: 14.1px`

**Text style:** `compact-label` — Suisseintl 400 · 14.1px/1

**Observed:** Three link columns with 21.1px gutters and 17.6px vertical rhythm. Group labels are subdued; a compact brand symbol sits beneath the columns. Utility links and copyright sit outside the mosaic on cream.

**Transfer:** Retain the panel structure even with fewer links; do not turn it into a conventional full-width dark footer.

### Question card

**Only for:** product landing pages

**Use:** Large objection-handling accordion.

**CSS:** `background: #e1f4df; border-radius: 14.1px; overflow: hidden`

**Text style:** `action-large` — Suisseintl 400 · 22.9px/1.5

**Observed:** Question row has 35.2px vertical and 42.2px horizontal padding, with a cream circular plus control aligned right. Cards form a 600px-wide column beside the section heading.

**Transfer:** Keep the question readable over two or three lines; reveal the answer within the same panel.

### Role card

**Only for:** career listings

**Use:** Whole-row link to a role description.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 14.1px; background: #e1f4df; border: 1px solid #efeeeb; border-radius: 16px; padding: 28.2px`

**Text style:** `listing-title` — Faire Octave 400 · 26.4px/1.2

**Observed:** Serif role name above small location and employment metadata, with a compact View role arrow at right. Department headings sit on fine rules above each group.

**States:** Declared: hover border-color #0f3e17; focus-visible outline 2px solid #0f3e17 with 2px offset; active outline 0px.

### Download button

**Only for:** resource landing pages

**Use:** Document acquisition.

**CSS:** `display: inline-flex; align-items: center; gap: 7px; background: #0f3e17; color: #ffffff; border-radius: 9999px; padding: 12.3px 28.2px`

**Text style:** `download-label` — Suisseintl 600 · 14.1px/1.5

**Observed:** Small download icon before semibold text. An adjacent white outlined pill provides the print alternative and a small page-count note.

**States:** Declared: hover background #173e1e; focus-visible outline 2px solid #0f3e17 with 2px offset.

### Related resource card

**Only for:** resource landing pages

**Use:** Compact onward reading.

**CSS:** `background: #ffffff; border: 1px solid #e5e5e5; border-radius: 12px; padding: 21.1px`

**Text style:** `resource-card-title` — Suisseintl 600 · 15px/1.3

**Observed:** Small uppercase category, semibold title and two-line gray description. Three equal cards sit in a 21.1px-gap grid.

**States:** Declared: hover border-color #0f3e17 and box-shadow 0px 2px 8px rgba(0, 0, 0, 0.06); focus-visible outline 2px solid #0f3e17 with 2px offset.

## Imagery and graphics

### Workflow miniatures

**Use:** Opening product stage and feature demonstrations.

**Observed:** Cream cards contain edited interface fragments: a profile, form, chart, table or note dialog. The opening uses three upright miniatures linked with fine dotted paths on dusty blue; later panels enlarge and overlap a few windows without device chrome.

**Transfer:** Show three meaningful moments of the new workflow, using realistic concise content. A minimum version is three cream SVG cards with a clear status, input and result, linked by dotted curves.

### Flowing contours

**Use:** Signature punctuation between chapters and in the closing blue panel.

**Observed:** Thin forest-green parallel curves sweep upward and out of the frame. Elsewhere, nested open rectangular contours and concentric curves extend past the edge of the page, with a short serif statement in the remaining space.

**Transfer:** Include a line-art panel in the closing mosaic and use open contour art to punctuate a long landing page; preserve the sense of flow without reproducing a logo.

**Build:** Use an SVG with a 540 by 270 viewBox over #b6ced5. Draw 8–10 unfilled cubic Bezier paths in #0f3e17 at roughly 1.5px stroke: begin beyond the left edge at staggered lower positions, sweep diagonally toward the upper right, and finish beyond the top or right edge. Offset paths by 20–30px, clip to the 14.1px rounded panel. For chapter punctuation, draw 5–7 nested open right-angle rectangles or quarter-circle arcs in the same thin stroke, oversized so the panel edge cuts them off.

### Sunlit interior proof

**Use:** Middle column of customer outcome compositions.

**Observed:** Portrait crops of warm, unoccupied rooms: soft chairs, wood cabinetry, woven art, plants and books. Sideways sunlight makes long shadows; beige, olive and caramel dominate. Photography is flush to its rounded frame and occupies as much width as the quote panel.

**Transfer:** Choose an environment associated with the benefit, not a generic team high-five. Use warm natural light, tactile furnishings and an uncrowded composition; an equivalent real workspace is preferable to decorative people portraits.

### Logo proof strips

**Use:** Immediately below the opening and before the closing mosaic.

**Observed:** Small organization or investor marks arranged across a cream band beneath a centered support label. Customer marks keep muted native colors; investor marks use subdued green-gray.

**Transfer:** Use available real marks at restrained visual heights, with substantial space around each.

### Document preview

**Only for:** resource landing pages

**Use:** Right side of a resource introduction.

**Observed:** A 440px-wide portrait page with a green flowing-line header, serif title, miniature contents and restrained footer. It is square-on, lightly rounded and softly shadowed.

**Transfer:** Typeset a genuine preview of the new material, with the same visual hierarchy and a simple line-art header.

### Icons

**Observed:** Simple unfilled diagrams use thin forest strokes; compact arrows use 16–18px boxes and 1.5–2px round strokes. Large action bars use a 42 by 38px arrow. Section illustrations use nested squares, checklists and contours rather than filled multicolor icon badges.

**Transfer:** Choose outline arrows and structural geometric diagrams. Keep icons subordinate to text except for the large directional arrow on conversion bars.

## Section recipes

How recurring sections are built.

### First screen: Pastel workflow opening

**Observed:** An 84px cream Navigation sits over a wide two-column composition with 35.2px outer gutters and 21.1px gaps. The left two-fifths contains a leaf-green promise panel, roughly 539px wide and 389px high, followed by a separate 122px Action bar. The display headline is left-aligned and broken into two short lines near the top; its support paragraph sits much lower in the panel. The right three-fifths is a 533px-tall Blue stage containing three cream workflow miniatures centered across it, each with a small label below. Layers are cream canvas, flat pastel panels, dotted connectors, then crisp cream interface objects. The headline, support, action, complete stage, proof label and customer marks all appear within the first 900px; the next explanatory chapter begins below that screen.

**Transfer:** For a new product, make a similarly short before/after promise and a three-step illustrated workflow rather than requiring a full interface. A detailed product page can instead open with a dark rounded field, light serif heading at the heading scale on the left and enlarged interface fragments at right. Career pages use a centered editorial title; role pages use a left-aligned title and application action; resources pair title and download actions with a portrait document.

**Avoid:** Do not replace the split panel composition with a centered headline floating above a generic browser window, or merge the promise panel and Action bar into one undifferentiated block.

**Text style:** `display` — Faire Octave 300 · 73.9px/1.05 · tracking -0.03em

### Editorial heading pair

**Observed:** Section tag above a light serif heading, separated by 28.2px. Headings have a 450.6–647.7px reading width; the content grid starts another 56.3px below. Main chapters use about 98.6px top and bottom padding.

**Transfer:** Use short contextual labels to introduce a benefit, proof or trust chapter; reserve the larger headline for the claim.

**Text style:** `heading` — Faire Octave 300 · 56.3px/1.2 · tracking -0.03em

### Capability spectrum and metrics

**Observed:** A pale-green vertical field holds centered serif category names, beside a 40.5px serif statement and two light 56.3px sans quantities. The composition uses two broad columns with a 70.4px gap.

**Transfer:** Replace the category names with the new product's breadth of use and ground it with two substantiated scale or outcome measures.

### Benefit triad

**Observed:** Three Benefit cards share a 1041.9px inset container and 21.1px gutters. Their fills progress through pale leaf, mint and leaf; icons, sans titles and compact explanations align consistently.

**Transfer:** Use a small number of contrasting benefits with equal visual status.

### Contour interlude

**Observed:** A short callout is offset beside very large open line art, with approximately 70.4px vertical padding. One statement aligns right opposite curves; another aligns left opposite nested rectangles.

**Transfer:** Use the required contour motif to create breathing room around one concise product conviction.

**Text style:** `callout` — Faire Octave 300 · 40.5px/1.35 · tracking -0.01em

### Product demonstration chapters

**Observed:** Wide green capability stages place text and pills at left and enlarged cream interface fragments at right. The broad overview uses 70.4px panel insets. Detailed product chapters use Chapter panel, a narrow side index, 21.1px gaps between panels and 72px insets; large scheduling or task scenes instead span the panel above their supporting text.

**Transfer:** Choose split or stacked composition based on interface shape. Use the same pastel palette to make a long explanation readable without turning it into a repetitive card catalog.

### Customer outcome triptych

**Observed:** A heading pair introduces a three-column Proof grid. A tall leaf quote card has attribution pinned low; a warm portrait interior occupies the middle; two Statistic cards and an Action bar stack at right. All columns end on one baseline.

**Transfer:** Combine a credible voice, an atmospheric environment and measured outcomes. Preserve the balance of human testimony and light sans quantities.

**Text style:** `quote` — Faire Octave 300 · 24.6px/1.35 · tracking -0.01em

### Trust checklist

**Observed:** An inset two-part section places a serif heading at left and six compact icon-plus-description items in a two-column grid at right. The surrounding cream is unboxed and generous.

**Transfer:** State meaningful standards or operational safeguards in small concrete sentences, not another row of colorful sales cards.

### Closing invitation mosaic

**Observed:** The final 813px composition reverses the opening's column proportions. A roughly 809px-wide pale invitation panel pairs a two-line display heading at top with support text pinned low; an Action bar sits below. At right, a 539 by 270px Blue stage holds Flowing contours above the Footer menu. The mosaic uses 21.1px gaps and 42.2px internal padding, with small utility text outside on cream.

**Transfer:** Finish every page with this second-hero structure, adapting the invitation to the new outcome. Keep the line-art panel, navigation and major action as separate pieces.

**Text style:** `display` — Faire Octave 300 · 73.9px/1.05 · tracking -0.03em

### Product questions

**Only for:** product landing pages

**Observed:** A short serif heading sits at left, with a 600px question column at right. Question cards have 14.1px gaps and are followed by a compact outlined load-more action.

**Transfer:** Group late-stage buying objections into a few readable questions rather than introducing more capabilities.

### Editorial recruiting body

**Only for:** career pages

**Observed:** Listings use a 900px column, ruled department headers and Role cards. Role detail has a roughly 578px text column, large serif subheads, compact body paragraphs and lists, plus a 280px pale application rail. A separate forest invitation panel precedes the shared closing mosaic.

**Transfer:** Adapt this lower-media, reading-led variant to directory or detail content without imposing the full marketing hero.

### Resource utility sequence

**Only for:** resource landing pages

**Observed:** A serif document introduction and two pill actions sit beside a shadowed portrait cover. A two-column grid of numbered contents rows leads to a centered pale-green download band, then a cool-paper FAQ band and three Related resource cards. Section padding is 56.3px; FAQ rows are small, ruled and chevron-led rather than large pastel Question cards.

**Transfer:** Make the utility and contents explicit, repeat the acquisition action, then offer useful onward reading.

**Text style:** `resource-title` — Faire Octave 400 · 42.2px/1.15 · tracking -0.03em

## Page flow

**Storyline:** Outcome promise → breadth and scale → unified-product explanation → capabilities → human and quantified proof → reassurance → renewed invitation.

### Broad marketing introduction

1. **Promise** — Pastel workflow opening and logo proof strip.
2. **Breadth and scale** — Large category field opposite a statement and two metrics.
3. **Product explanation** — Problem-to-solution statement, contour geometry, benefit triad and wide product demonstrations.
4. **Proof** — Quote, atmospheric interior and measurable outcomes in a triptych.
5. **Reassurance** — Unboxed standards checklist, short company rationale and investor marks.
6. **Closing call** — Closing invitation mosaic.

**Transfer:** Use this as the default breadth-to-depth narrative; adjust the number of capability chapters to the new product.

### Recruiting directory

1. **Mission** — Centered serif promise with compact supporting paragraph.
2. **Opportunities** — Ruled categories, counts and pale full-row links.
3. **Alternate contact** — Small invitation to contact the team after the final listing.
4. **Closing call** — Inset dark invitation, then the shared closing mosaic.

**Transfer:** Adapt the editorial list treatment for opportunities and categorized directories.

### Single opportunity detail

1. **Orientation** — Back link, small category, role name, metadata and application button.
2. **Qualification** — Compact notices and long-form expectations with a pale application rail.
3. **Closing call** — Dark invitation band followed by the shared closing mosaic.

**Transfer:** Use this split reading-and-action structure for detailed offerings with one focused conversion.

### Downloadable resource

1. **Utility promise** — Category, document title, description and download/print pills beside a cover.
2. **Preview** — Numbered two-column contents.
3. **Conversion** — Centered pale download band.
4. **Objection handling** — Compact ruled questions on cool paper.
5. **Discovery** — Three small related-material cards.
6. **Closing call** — Shared closing mosaic.

**Transfer:** Keep informational pages visibly useful and more compact than the broad landing-page narrative.

### Detailed product explanation

1. **Promise** — Dark rounded hero with light text and interface fragments.
2. **Breadth** — Horizontal category carousel with large serif names.
3. **Capability chapters** — Narrow side index beside alternating-color demonstration panels.
4. **Proof** — Quote/interior/outcomes triptych.
5. **Reassurance** — Standards checklist, integration statement and logo movement.
6. **Objection handling** — Large pale question cards beside a short heading.
7. **Closing call** — Shared closing mosaic.

**Transfer:** Use the dark opening as a scoped product variant while retaining the same editorial hierarchy and pastel chapter system.

## Writing

Warmly operational and confident without swagger. Relief is described through specific work becoming easier, with human outcomes following practical improvements.

**Do not copy:** Do not reuse Ease Health's name, logo, customer or investor marks, proprietary interface artwork, quotations, numerical claims, certifications, funding claims or product-specific promises. Examples illustrate cadence only; replace them with truthful material for the new product.

- **Addressing the reader:** Benefit headings often speak to you or describe what the system does. Company and recruiting text uses we; actions use direct imperative verbs.
- **Rhythm:** Short, balanced headlines alternate with one-sentence explanations. Benefit titles are usually four to eight words; support text names a few concrete improvements rather than stacking abstractions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Two short clauses contrast friction with the desired human outcome. | 4–8 words | “Fewer clicks. More care.” |
| Section heading | Plain-language capability framed as a useful outcome. | 5–10 words | “A super-powered system, working together.”<br>“Scheduling that stays in sync” |
| Support | Name the work, the mechanism and the payoff in one sentence. | 18–35 words | “Consolidate tools, reduce spend, and gain unified reporting without painful integrations.” |
| Action | Verb plus tangible next step, not an abstract motivational slogan. | 2–4 words | “Request a Demo”<br>“Download Free PDF” |
| Reassurance | Concrete operational safeguard rather than a broad trust adjective. | 8–16 words | “End-to-end encryption, role-based access, and secure data handling” |

**Words and phrasing to use:** built for; works for you; in one place; less time; real work; stays in sync; seamless; supports; automatically

**Avoid:** revolutionary; game-changing; crush it; 10x everything; magic; unprecedented disruption

**Rules:**

- Put the human benefit in the headline and explain the workflow mechanism below.
- Keep capability pills as short noun phrases; avoid complete sales sentences in them.
- Qualify estimated outcomes in the stat description instead of hiding the qualification.
- Use domain terminology only where it makes the work clearer.
- Recruiting details can be more direct and candid than the marketing promise.

## Do's and Don'ts

### Do

- Use light 73.9px serif type for both the opening promise and closing invitation.
- Keep the default gutter at 21.1px so stage, action and neighboring cards align.
- Use 42.2px panel padding for marketing cards and large action bars.
- Keep section labels sentence-case, 17.6px and backed by dusty blue.
- Use light 56.3px sans numerals for outcome quantities, not serif display numerals.
- Pair an atmospheric portrait image with quote and outcome panels in equal columns.
- Reserve the 21.1px-radius, 72px-inset frame for detailed capability chapters.
- Preserve the separate flowing-line panel and three-column menu in the closing mosaic.

### Don't

- Do not make every action a pill; the default marketing button has 14.1px corners.
- Do not replace forest text with pure black across the marketing canvas.
- Do not apply shadows to every green panel; the core card system is flat.
- Do not turn the dusty blue into saturated electric blue or use it as the main text color.
- Do not make 56.3px statistics bold; their light weight is part of the proof treatment.
- Do not substitute glossy 3D objects for the thin contour illustrations.
- Do not use the compact 24.6px resource heading scale as the main landing-page hierarchy.
- Do not force paragraph text into centered alignment outside the recruiting introduction or centered resource call.

## Motion and responsive

### Motion

**Observed:**

- Primary-button background and border transitions are declared at 0.3s with cubic-bezier(0.215, 0.61, 0.355, 1).
- Heading and section-label reveals declare opacity 1s and transform 1s cubic-bezier(0, 0, 0, 1).
- An integrations marquee declares a 25s linear infinite animation.
- Role cards declare all 0.15s cubic-bezier(0.4, 0, 0.2, 1); related-resource cards transition border-color and box-shadow over 0.15s.

**Transfer:**

- Keep action-color changes restrained rather than adding bounce or scaling.
- Use reveal motion to introduce whole editorial elements and panel groups; the final resting layout must remain crisp.
- Limit continuous horizontal motion to a repeated integration strip.

**Unknown:**

- Exact scroll-trigger thresholds, header hide/show timing and complete panel-scroll choreography are not established.

### Responsive

**Observed:**

- Declared widths include 479px, 767px, 768px, 991px and 992px among other utility breakpoints.
- Display and resource titles use clamp formulas; detailed chapter padding uses 5vw.

**Transfer:**

- On narrow screens, stack the opening promise and action before the workflow stage; retain the three miniature steps as a readable sequence.
- Stack the proof triptych without losing quote, environment, quantities or action.
- Collapse the chapter side index into a compact navigational row and let interface art use the available width.
- Keep the closing invitation, action, flowing-line art and footer links as distinct stacked panels.

**Unknown:**

- Exact mobile measurements and breakpoint-specific rearrangements are not established; stacking rules here are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
