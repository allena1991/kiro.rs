# MotherDuck — an outlined technical playground

## Overview

A light, exuberant technical style that turns infrastructure into a friendly illustrated world. Warm paper, sky blue, sunny yellow, coral and mint carry regular uppercase mono headings, a utilitarian sans-serif reading face, and flat cartoon diagrams. Broad color chapters and generous staging alternate with dense, practical cards and tables; it suits developer platforms that want to be approachable without losing technical substance.

### Essentials

- Technical headlines sound like plainspoken signs, not luxury display type: regular 400 weight, uppercase, 44px/1.2 Aeonik Fono for the opening and 40px/1.2 Aeonik Mono for section leads.
- The opening is a two-sided invitation: a 560px text column beside a 600×338px demo stage, separated by 80px, on warm #f4efea paper; a hard -12px 12px ink offset makes the demo tangible.
- Controls behave like movable printed pieces: blue #97d4ff faces, 2px #383838 outlines, 2px corners, and a 7px right/up hover displacement over an ink backing.
- Color belongs to whole chapters, not scattered decorations: blue, mint, coral and yellow fill broad edge-to-edge bands with 2px ink boundaries; the opening and reading/card chapters remain paper. Colored storytelling occupies roughly half the main product narrative, while the footer is solid charcoal.
- A repeated yellow typographic ribbon and outlined cloud cutouts are signature devices: the ribbon uses 32px/1.4 uppercase mono, 16px vertical padding and 60px side margins per repeat; cloud silhouettes overlap chapter boundaries.
- Illustrated systems replace abstract enterprise stock art: thin charcoal contours, white cloud shapes, yellow/coral/mint/blue flat fills, connecting wires and friendly geometric objects. Include this illustrated layer even without a character library—use a simple outlined workflow with clouds, diamonds and cylinders.
- Proof and explanation live in physical-looking panels: square white cards with 2px ink edges, 32px inner padding, 32px grid gaps, and occasional hard -16px 16px ink offsets for a flagship diagram.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky chapter | `#6fc2ff` | `--color-sky` | background, accent, action | Full-width explanatory and proof chapters; pressed primary actions and active links. |
| Light action blue | `#97d4ff` | `--color-action-blue` | action, background | Primary button faces; also the lighter blue variant for architecture and customer-proof chapters. |
| Signal yellow | `#ffde00` | `--color-yellow` | background, accent | Repeated ribbons, diagram stages and short highlighted plaques. |
| Mint chapter | `#50c7b7` | `--color-mint` | background, accent | Positive explanations and one half of audience splits. |
| Deep mint | `#16aa98` | `--color-teal` | background, accent | Darker illustration half of positive comparison chapters. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral chapter | `#ff7169` | `--color-coral` | background, accent | Audience panels, illustrated partnership bands and tilted labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Panel white | `#ffffff` | `--color-white` | surface, text | Cards, clouds and diagram boards; footer text and reverse title plaques. |
| Warm paper | `#f4efea` | `--color-canvas` | background, surface | Opening and long reading areas; resting background between colored chapters. |
| Old-world stone | `#e4ded7` | `--color-stone` | background | Muted illustration field in problem-versus-solution stories. |
| Secondary copy | `#818181` | `--color-secondary` | text | Metadata, plan explanations and small supplementary copy. |
| Muted copy | `#666666` | `--color-muted` | text | Field labels and subordinate descriptions. |
| Charcoal ink | `#383838` | `--color-ink` | text, border, background | Default text, outlines, hard offsets, title plaques and footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Warm table rule | `#ece5dd` | `--color-table-rule` | border, surface | Low-contrast pricing comparison separators and annual-plan strip. |
| resource collections and detailed feature campaigns | Lemon field | `#f9ee3e` | `--color-acid-yellow` | background, accent | Resource carousel backgrounds and feature-detail chapters; also audience-link hover text. |
| launch announcements | Announcement orange | `#ff5a1f` | `--color-announcement` | background | Thin announcement strip only, not a general chapter fill. |
| launch announcements | Announcement ink | `#111110` | `--color-announcement-ink` | text | Small text in the orange announcement strip. |
| lead forms | Field wash | `#f7f5f3` | `--color-field` | surface | Visible field fill from 70% #f8f8f7 over warm paper. |

## Typography

- **Aeonik Fono** — Opening headline and selected editorial/resource headings. A regular, open utilitarian sans with engineered, almost monospaced rhythm. If unavailable, use **IBM Plex Sans**. Use 400; preserve uppercase line breaks and column width. Font stack: "Aeonik Fono", "IBM Plex Sans", "Segoe UI", sans-serif.
- **Aeonik Mono** — Section titles, ribbons, chapter plaques, feature titles and technical labels. Regular-width monospaced lettering with an informal technical voice. If unavailable, use **IBM Plex Mono**. Use 400 for most titles and 300 only where explicitly specified. Font stack: "Aeonik Mono", "IBM Plex Mono", monospace.
- **Inter** — Paragraphs, actions, navigation and metadata. Light reading text contrasts with the mono labels; action labels stay regular. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | Aeonik Fono | 400 | 56px | 1.2 | 0.02em, uppercase | One prominent before-to-after result inside a proof card. |
| feature-display | Aeonik Mono | 400 | 56px | 1.2 | normal, uppercase | Large centered ecosystem lead; also a specialized illustrated campaign headline. |
| heading-lg | Aeonik Mono | 400 | 52px | 1.4 | normal, uppercase | Centered question introducing a major narrative change. |
| display | Aeonik Fono | 400 | 44px | 1.2 | normal, uppercase | Default split-opening headline. |
| heading | Aeonik Mono | 400 | 40px | 1.2 | normal, uppercase | Feature and FAQ section leads. |
| chapter-plaque | Aeonik Mono | 400 | 36px | 1.4 | normal, uppercase | Reverse title on an ink rectangle bridging two chapters. |
| heading-sm | Aeonik Mono | 400 | 32px | 1.4 | normal, uppercase | Compact section leads, ribbons and audience plaques. |
| card-heading | Aeonik Mono | 400 | 24px | 1.4 | normal, uppercase | Feature titles and repeated narrative benefit statements. |
| question | Aeonik Mono | 400 | 23px | 1.4 | normal, uppercase | Full-width accordion questions. |
| lead | Inter | 300 | 20px | 1.6 | normal | Explanatory paragraphs in split narrative chapters. |
| intro | Inter | 300 | 18px | 1.6 | normal | Support below the opening headline; linked audience phrases stay inline. |
| answer | Inter | 300 | 18px | 1.6 | 0.02em | Expanded FAQ answers. |
| body | Inter | 300 | 16px | 1.6 | 0.02em | Feature cards and ordinary explanatory text. |
| action | Inter | 400 | 16px | 1.2 | normal, uppercase | Main conversion buttons. |
| text-link | Inter | 400 | 16px | 1.2 | 0.02em | Uppercase underlined secondary actions with a separate arrow. |
| footer-link | Inter | 300 | 16px | 1.3 | normal | Sentence-case footer directory links. |
| caption | Inter | 400 | 16px | 1.4 | 0.02em | Short explanation attached to a proof number. |
| action-small | Inter | 400 | 14px | 1.2 | normal, uppercase | Header and compact conversion actions. |
| navigation | Inter | 400 | 14px | 1.37 | 0.023em | Uppercase desktop navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and culture pages | company-display | Aeonik Mono | 400 | 80px | 1.2 | 0.02em, uppercase | Oversized two-line institutional opening. |
| pricing pages | price | Aeonik Mono | 400 | 64px | 1.2 | normal, uppercase | Plan amount or Custom label. |
| pricing pages | pricing-display | Aeonik Mono | 400 | 44px | 1.2 | normal, uppercase | Centered pricing promise. |
| detailed feature campaigns | campaign-heading | Aeonik Mono | 400 | 32px | 1.2 | normal, uppercase | Short centered headings in a detailed feature campaign. |
| lead forms | field-label | Inter | 300 | 16px | 1.4 | 0.02em | Input labels. |
| launch announcements | announcement | Aeonik Fono | 400 | 12.5px | 1.2 | normal, uppercase | Compact launch strip text. |
| detailed feature campaigns | eyebrow | Aeonik Mono | 400 | 12px | 1.4 | normal, uppercase | Small paper-backed feature tag. |

**Notes:**

- Keep headline weights at 400 rather than substituting bold. The scale comes from uppercase width and framing, not extreme size or negative tracking.
- Body copy is mostly Inter 300 with a relaxed 1.6 line height. Small card copy uses 0.02em tracking; the opening support and long comparison paragraphs use normal tracking.
- A title plaque can cross a section boundary while its white or yellow subtitle remains in a separate outlined rectangle.

## Layout

**Density:** Airy at chapter scale, compact within controls and cards. Wide narrative pauses give the illustrations room; tables and footer directories become deliberately dense.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and tight title/support relationships. |
| 12px | Small title-to-support and feature-tag spacing. |
| 16px | Card content stack gap and ribbon vertical padding. |
| 24px | Navigation gaps, paired form fields and supporting content gaps. |
| 32px | Card padding and repeated-card grid gaps. |
| 40px | Opening action gap, form row spacing and audience-panel content gaps. |
| 52px | Feature section lead to card grid. |
| 64px | Feature chapter top inset and footer directory-to-bottom spacing. |
| 80px | Opening column gap and repeated chapter insets. |
| 120px | Illustrated closing and service-story chapter insets. |
| 140px | Deep lower inset below feature grids and diagram chapters. |
| 380px | Narrative pauses between benefit statements beside a staged illustration. |

### Containers and grids

- **container**: max width 1302px · side padding 30px. Centered desktop shell; usable content is 1242px at a 1440px viewport, leaving 99px to the first text edge.
- **opening split**: 2 columns · gap 80px. 560px headline column and 600px demo stage, vertically centered.
- **feature grid**: 3 columns · gap 32px. Equal cards across the usable width; cards are about 393px wide.
- **audience split**: max width 1440px · 2 columns · gap 0px · side padding 30px. Two edge-to-edge 720px fields separated by an ink rule; centered illustration, plaque, paragraph and link in each.
- **contact column**: max width 702px · gap 40px. Centered form with two equal name fields at a 24px gap, followed by full-width fields.
- **footer directory**: 4 columns · gap 32px. Four 200px link columns to the right of a separate brand/social block.
- **code panel** (only for code-led feature pages): max width 1028px. Centered technical demonstration under a concise heading and support line.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 2px |
|  | marketing cards | 0px |
|  | play control | 50% |
| code-led feature pages | code panel | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | demo stage | `-12px 12px 0px 0px #383838` | Hard ink offset behind the opening media. |
|  | diagram board | `-16px 16px 0px 0px #383838` | Flagship white diagram on yellow. |
| interactive architecture explainers | expanded feature | `-4px 4px 0px 0px #383838` | Small active architecture accordion panel. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default opening and reading background.

**CSS:** `background: #f4efea; color: #383838`

#### Color chapter · level 0

**Use:** Broad narrative change or proof stage.

**CSS:** `background: #6fc2ff; border-top: 2px solid #383838`

**Observed:** Mint, coral and yellow are separate chapter variants; paired positive-comparison panels use mint at left and deep mint at right.

**Transfer:** Assign each chapter a single semantic color rather than mixing all colors inside each block.

#### Outlined white panel · level 1

**Use:** Feature cards and proof containers.

**CSS:** `background: #ffffff; border: 2px solid #383838; border-radius: 0px`

**Observed:** Square, opaque faces sit on warm paper or a saturated chapter background.

#### Diagram board · level 1

**Use:** Dominant explanatory diagram.

**CSS:** `background: #ffffff; border: 2px solid #383838; box-shadow: -16px 16px 0px 0px #383838`

**Observed:** An overlapping two-part label marks the board's upper edge.

#### Graph paper · level 0

**Use:** System maps and illustrated closing panels.

**CSS:** `background-color: #f4efea; background-image: linear-gradient(rgba(56,56,56,0.08) 1px, transparent 1px), linear-gradient(90deg, rgba(56,56,56,0.08) 1px, transparent 1px); background-size: 56px 56px`

**Observed:** A faint square grid runs behind the system, interrupted by paper-backed headings.

**Transfer:** Keep the grid faint enough that connectors and text dominate.

#### Dark directory · level 0

**Use:** Shared page ending.

**CSS:** `background: #383838; color: #ffffff; padding: 90px 0px 72px`

#### Code demonstration · level 1

**Only for:** code-led feature pages

**Use:** Readable short code examples.

**CSS:** `background: #383838; border: 2px solid rgba(255,255,255,0.2); border-radius: 20px`

**Observed:** A header row with language label and copy control is separated by a faint white rule; syntax colors remain inside the demonstration.

## Components

### Site navigation

**Use:** Persistent desktop wayfinding.

**CSS:** `position: fixed; z-index: 99; background: #f4efea; border-bottom: 2px solid rgba(56,56,56,0.77); height: 122px`

**Text style:** `navigation` — Inter 400 · 14px/1.37 · tracking 0.023em

**Observed:** A brand mark sits left, grouped section links and small downward chevrons occupy the middle, login and a compact blue action sit right. The 122px assembly includes a 40px announcement above an 80px navigation row; without an announcement, retain the navigation row.

**Transfer:** Keep navigation short enough that the logo and conversion action retain their own space.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; background: #97d4ff; color: #383838; border: 2px solid #383838; border-radius: 2px; padding: 16.5px 22px; height: 56px`

**Text style:** `action` — Inter 400 · 16px/1.2 · uppercase

**Observed:** The clickable face is nested over an equally sized charcoal backing. Compact navigation and some trial variants use a 44px face with 11.5px 18px padding and the action-small recipe.

**States:** Declared: hover on ancestor translates the face translate(7px, -7px); focus-visible not specified; active returns transform to none and changes the face to #6fc2ff.

### Text action

**Use:** Secondary exploration beside a filled button or at a card's end.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #383838; border-bottom: 1px solid #383838; padding: 1px 0px`

**Text style:** `text-link` — Inter 400 · 16px/1.2 · tracking 0.02em

**Observed:** Underline belongs to the text span, not the trailing arrow; the opening uses a down arrow while onward links use a right arrow.

**States:** Declared: hover not specified; focus-visible not specified; active link color changes to #6fc2ff.

### Feature card

**Use:** Repeated capability summary.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 32px 32px 40px; background: #ffffff; border: 2px solid #383838`

**Text style:** `card-heading` — Aeonik Mono 400 · 24px/1.4 · uppercase

**Observed:** A small flat illustration occupies the top zone, followed by mono title, body paragraph and underlined details action. Equal-height cards rest over a charcoal backing.

**States:** Declared: hover on ancestor translates the card face translate(14px, -14px); focus-visible and active not specified.

**Transfer:** Use one understandable visual metaphor per card, not miniature full application windows.

### Repeating ribbon

**Use:** Signature chapter divider.

**CSS:** `display: flex; justify-content: center; overflow: hidden; background: #ffde00; border-top: 2px solid #383838`

**Text style:** `heading-sm` — Aeonik Mono 400 · 32px/1.4 · uppercase

**Observed:** The same short label repeats across and beyond both edges; each repeat has 16px top/bottom padding and 60px side margins.

**Transfer:** Repeat the new section's short category label; keep the edge-to-edge band.

### Audience plaque

**Use:** Large linked title centered in an illustrated audience panel.

**CSS:** `background: #383838; color: #ffffff; padding: 8px 30px`

**Text style:** `heading-sm` — Aeonik Mono 400 · 32px/1.4 · uppercase

**Observed:** The plaque is just wide enough for its label, placed beneath the illustration and above the centered paragraph.

**States:** Declared: hover text changes to #f9ee3e; focus-visible text changes to #f9ee3e; active not specified.

### FAQ row

**Use:** Objection handling near the end of a product or pricing story.

**CSS:** `display: flex; flex-direction: column; padding: 26px 0px; border-top: 2px solid #383838`

**Text style:** `question` — Aeonik Mono 400 · 23px/1.4 · uppercase

**Observed:** Full-bleed separators frame a constrained question and small down-chevron. The collapsed single-line row is 86px tall. Answers use the answer recipe and inline underlined documentation links; the final rows share space with an outlined character.

### Footer directory

**Use:** Shared substantial ending.

**CSS:** `display: grid; grid-template-columns: repeat(4, 1fr); gap: 32px; color: #ffffff`

**Text style:** `footer-link` — Inter 300 · 16px/1.3

**Observed:** Four narrow directories sit beside a brand/social column on Dark directory. Bold category labels punctuate light link lists; recent resources can wrap to several lines. A lower line holds attribution and underlined legal links at left, with two restrained certification seals at right.

**States:** Declared: hover not specified; focus-visible not specified; active link color changes to #6fc2ff.

### Form field

**Only for:** lead forms

**Use:** Contact or guide-download input.

**CSS:** `background: rgba(248,248,247,0.7); border: 2px solid #383838; border-radius: 2px; padding: 16px 40px 16px 24px; height: 58px`

**Text style:** `field-label` — Inter 300 · 16px/1.4 · tracking 0.02em

**Observed:** Warm translucent fields are arranged in a narrow centered column. A longer message uses a 114px textarea; name fields share a row.

### Plan card

**Only for:** pricing pages

**Use:** Compare purchase paths before the detailed table.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 2px solid #383838; padding: 32px`

**Text style:** `price` — Aeonik Mono 400 · 64px/1.2 · uppercase

**Observed:** Plan name comes first, then oversized price with compact billing qualifier, short audience description, full-width action, divider and checkmarked inclusions. The recommended middle card is raised above its neighbors and uses a blue action; the outer cards use white actions. Small illustrated characters perch over the top edge.

### Launch strip

**Only for:** launch announcements

**Use:** Small announcement above navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; background: #ff5a1f; border-top: 2px solid #383838; border-bottom: 2px solid #383838; color: #111110`

**Text style:** `announcement` — Aeonik Fono 400 · 12.5px/1.2 · uppercase

**Observed:** One centered sentence and a short underlined onward link with arrow; much smaller type than any section label.

## Imagery and graphics

### Outlined illustrated world

**Use:** Signature supporting art in openings, chapter transitions and explanations.

**Observed:** White cartoon characters and cloud silhouettes have thin charcoal contours, simple facial details, orange/yellow accents and flat coral, mint or blue props. Small tilted cylinders, outlined diamonds and loops occupy the margins. Illustrations range from a small card emblem to a half-section system scene; they overlap panel edges rather than sitting in glossy image containers.

**Transfer:** Develop a small set of friendly objects related to the new product, with flat fills and restrained outlines. The minimum version is a diagram made from labeled cylinders, folders and connecting lines, with a cloud cluster and a speech bubble.

**Build:** Use SVG paths with 1.5–2px charcoal strokes and rounded joins. Join 4–6 overlapping white ellipses into one continuous cloud silhouette. Add 12–24px outlined diamonds, a tilted 60px cylinder in coral, and one yellow ellipse clipped by a page edge. Use no diffuse shadows; a short charcoal offset can give a sticker depth.

### System diagram

**Use:** A principal product explanation, with smaller variants in feature cards.

**Observed:** Flat rectangular and cylindrical modules are connected by clean wires or dashed arrows. White boards sit on yellow; a faint graph-paper field backs ecosystem maps. Large diagrams occupy most of the usable page width, while mono labels preserve a technical reading order.

**Transfer:** Diagram a real product relationship instead of drawing decorative random nodes. Keep three or fewer top-level groups in a flagship board; a central hub with category boxes works for an integration map.

**Build:** Draw a white SVG board with a 2px charcoal outline and hard lower-left offset. Arrange mint and coral group headers over paler child rows; connect groups with 1–2px dashed arrows and right-angle routes. For an ecosystem version, place a white rounded hub centrally and route lightly tinted 6px pipes behind rectangular category boxes on a faint square grid.

### Demo stage

**Use:** Opening's main product object.

**Observed:** A 16:9 editorial demo thumbnail is enclosed by an ink edge with a lower-left hard offset. A 100px white circular play control sits over the image. A speech bubble and outlined character overlap the lower-right corner.

**Transfer:** Show one legible product task in the thumbnail, with short explanatory text. Without video, use a static diagram or interface composition in the same framed stage, with a short annotation bubble rather than a nonfunctional play control.

### Cloud transition

**Use:** Signature scene change between broad colored chapters.

**Observed:** Oversized white scalloped clouds with ink outlines cross both the horizontal boundary and the center seam of split chapters; some extend beyond the viewport.

**Transfer:** Retain a visible cloud-cutout transition within the new narrative; its location can change.

**Build:** Layer 3–5 SVG cloud silhouettes across the full width, varying widths from 250px to 600px and overlapping by 40–100px. Keep white fill, 2px charcoal stroke and no blur. Let the next chapter's blue show through the gaps.

### Proof portrait and result cards

**Use:** Human and numerical credibility.

**Observed:** One blue quote band pairs a large natural-color portrait on the right with text on the left, plus a small paper nameplate overlapping its lower edge. Another proof composition uses white outlined cards on a light-blue sky with white cloud cutouts, mixing one quotation and one large before-to-after result above smaller customer summaries.

**Transfer:** Use real people or a real measured result. Preserve mixed card sizes and strong plain numerals rather than turning all proof into identical logo tiles.

### Resource thumbnail

**Only for:** resource collections

**Use:** Article and video carousels.

**Observed:** Bright flat editorial thumbnails combine mono headlines, small illustrations or a presenter portrait; yellow strips act as a printed label. White outlined card bodies carry type/date metadata, uppercase titles and optional summaries. The row extends beyond the right edge.

**Transfer:** Create a consistent editorial thumbnail system and allow a partial next card to signal horizontal continuation.

### Campaign landscape

**Only for:** detailed feature campaigns

**Use:** Immersive opening and matching final invitation.

**Observed:** Yellow sky, white outlined clouds, mint mountains and blue water form a cartoon landscape with a small fishing scene. The centered headline pairs plain mono with puffy white illustrated lettering outlined in charcoal. The closing repeats the same landscape inside the right side of a white outlined panel using an irregular curved cutout.

**Transfer:** Use a product-relevant calm activity and keep the same scene motif in the opening and closing. The minimum version is simple SVG hills, water arcs, cloud silhouettes and an outlined object rather than a complex character.

**Build:** Stack a yellow full-width field behind a blue water path with a gently sloping horizon. Add two mint mountain paths on the right, white cloud silhouettes and sparse 1px pale water arcs. Clip the closing illustration with an asymmetric S-curved vertical edge inside the panel.

### Culture photography and stickers

**Only for:** company and culture pages

**Use:** Institutional story, people and recruiting.

**Observed:** A wide natural-color outdoor group portrait sits in a simple ink border. Nearby value labels are separate tilted paper, mint, coral, blue and yellow rectangles with mono text, loose orbit lines and small outlined diamonds. A diagonal repeating yellow ribbon runs behind the opening illustration.

**Transfer:** Use real team or user-community photography without a color filter; arrange a small set of culture or principle labels as physical stickers.

**Build:** Rotate outlined rectangular labels between -15deg and 15deg and stagger them vertically beside the text column. Add a thin elliptical orbit behind the labels. For the diagonal ribbon, rotate a full-width yellow outlined strip slightly upward, repeat a short category label, and layer one foreground object over it.

### Icons

**Observed:** Navigation chevrons are small and plain; ordinary directional arrows sit outside underlined labels. Feature art is illustrative rather than a generic line-icon set. Pricing checks and utility marks use 24px SVGs with 1.6–2px rounded strokes in charcoal or teal; footer social marks are white 32px silhouettes.

**Transfer:** Use simple 16–24px arrows and chevrons for controls, with 2px rounded strokes for utility icons. Reserve colored pictograms for explanatory art, not every text link.

## Section recipes

How recurring sections are built.

### First screen: Split demo opening

**Observed:** Paper canvas starts below the fixed navigation assembly. The opening has 92px top and 156px bottom padding; the main row centers a 560px text column beside a 600×338px Demo stage across an 80px gap. A regular uppercase 44px/1.2 headline takes about three lines, followed by an 18px/1.6 support line with linked audience phrases; 32px separates the headline/support/action zones. Primary button and Text action sit left with a 40px gap. Behind the content are clipped yellow/coral shapes and small white clouds; in front, the stage's play circle, annotation bubble and friendly outlined object cross the lower-right edge. Within the first 900px, the complete headline, support, both actions, main media and illustration are visible, followed by the yellow Repeating ribbon and only the top of the next colored chapter. The next chapter's full content falls below the fold.

**Transfer:** Use a short product promise, one audience sentence and a single framed demonstration of the new product. Without source-quality illustration, combine a clear static workflow in the stage with a simple outlined geometric character and cloud shapes. Pricing pages instead open centered over three plans; company pages use the company-display recipe with a diagonal ribbon; a focused feature campaign can open as a centered illustrated landscape.

**Avoid:** Do not replace this balanced invitation with an enormous centered wordmark, a full-screen dark interface, or a tiny demo buried below the opening.

**Text style:** `display` — Aeonik Fono 400 · 44px/1.2 · uppercase

### Audience color split

**Observed:** Repeating ribbon introduces two equal color fields, coral left and mint right. Each panel centers an illustration about 440×340px, an Audience plaque, a compact paragraph and Text action, with 40px gaps. An ink vertical seam divides the fields.

**Transfer:** Compare two audiences, work modes or outcomes using parallel content length; use illustrations to distinguish them instead of adding extra UI controls.

### Problem and better-world chapters

**Observed:** A centered heading-lg question on sky leads into two-column stories. The left half carries three short card-heading statements with 20px/1.6 paragraphs and diamond markers; the right half stages a corresponding system illustration. A 2px seam has small pointed notches. The problem uses paper and stone, while the better alternative uses mint and teal. Chapter-plaque labels overlap the upper boundary. Long 380px pauses let each point read beside the illustration.

**Transfer:** Use a contrast that genuinely explains the product; reduce the number of points when the content is shorter while retaining the two material worlds and one staged illustration per idea.

### Flagship diagram chapter

**Observed:** A yellow Color chapter with 144px top and 140px bottom padding carries Diagram board at nearly full container width. A dark heading-sm plaque and white explanatory tab overlap the board's top edge. The diagram is the dominant object, not a small image below paragraphs.

**Transfer:** Show the new product's architecture, process or operating model using a handful of labeled groups.

**Text style:** `heading-sm` — Aeonik Mono 400 · 32px/1.4 · uppercase

### Card-grid capabilities

**Observed:** A heading lead has 52px breathing room above three columns of Feature card, with 32px gutters. Cards hold small illustration, card-heading, body and a details action; two rows can present six capabilities.

**Transfer:** Use enough cards to cover genuinely different capabilities and keep descriptions similar in length.

**Text style:** `heading` — Aeonik Mono 400 · 40px/1.2 · uppercase

### System map

**Observed:** Graph paper holds a centered feature-display heading with a smaller mono subtitle. A central white hub sends softly colored pipes to category boxes arranged around it; category labels and partner marks are directly on the tinted panels.

**Transfer:** Show a product's ecosystem, inputs/outputs or workflow neighbors. Use named categories rather than an unstructured logo cloud.

**Text style:** `feature-display` — Aeonik Mono 400 · 56px/1.2 · uppercase

### Proof band and numerical card

**Observed:** A blue quote band pairs a wide left quote with a portrait filling the right side and an overlapping paper attribution. The alternate white-card arrangement uses varied card widths, a 56px result, its 16px caption and a short onward action, on a cloud-backed sky.

**Transfer:** Choose either portrait-led testimony or a mixed quotation/result grid based on available proof; retain the playful physical panel framing.

### FAQ and contact ending

**Observed:** A heading lead precedes full-bleed FAQ row separators on paper. A small outlined figure overlaps the last rows. The default closing is a 702px contact column: 32px uppercase heading, 20px support, paired name fields then full-width email/company/message fields, 40px row gaps and Primary button. Marginal clouds, diamonds and loose loops frame the form without competing with inputs.

**Transfer:** End a sales-oriented story with a short invitation and only the fields needed to respond. A self-serve pricing story can instead use a centered short call, support line and blue button with 120px vertical breathing room.

### Directory ending

**Observed:** Dark directory is a substantial 1040px-tall desktop ending, not a narrow legal bar. Brand/social block sits beside Footer directory; the bottom adds attribution/legal links and certification marks, separated from the upper lists by 64px.

**Transfer:** Keep the ending useful and information-rich, adapting directory length to the new product's actual resources.

### Detailed feature deck

**Only for:** detailed feature campaigns

**Observed:** A lemon Color chapter introduces centered campaign-heading and support. Large white outlined cards pair a diagram about half the width with an eyebrow, compact uppercase title, body copy and Text action. The repeated cards form a sticky stacked presentation.

**Transfer:** Break a technical feature into one visual mechanism per panel; keep each explanation short enough to read while its diagram remains visible.

### Pricing comparison

**Only for:** pricing pages

**Observed:** A centered 44px promise and small pill switch precede three Plan cards. A short illustrated annual-plan strip and quote lead into a comparison table: one 240px feature column plus three equal plan columns, with warm 2px separators, 20px cell padding and a persistent plan-header row. A blue illustrated chapter explains the tiers after the dense table.

**Transfer:** Keep purchase choices brief at the top, then provide exact inclusions and billing units in the table; use an illustrated chapter to make technical tiers memorable.

### Illustrated closing panel

**Only for:** detailed feature campaigns

**Observed:** Graph paper backs a white outlined panel; heading and support occupy the left, actions sit below, and a curved-edge landscape fills the right. The surrounding section uses 120px top and 160px bottom padding before Dark directory.

**Transfer:** Echo the opening's metaphor at the end, but give the text a calm opaque white area.

### Culture and community close

**Only for:** company and culture pages

**Observed:** A yellow band carries a tilted coral title plaque, short email and recruiting links, and a large outlined geometric character. A paper community invitation follows with a wide banner image, then Dark directory.

**Transfer:** Close an institutional story with real contact paths and a community invitation rather than a product trial form.

## Page flow

**Storyline:** Promise and demonstration → audience or mechanism explanation → colorful capability chapters → concrete proof → practical objections → contextual invitation → substantial directory.

### General platform introduction

1. **Promise** — Split headline and video with trial/demo actions and a compact customer-logo strip.
2. **Mechanism explanation** — Blue illustrated architecture with an accordion, followed by a stacked system diagram and three pastel product-tool cards.
3. **Social proof** — Wide customer quote, integration scene, then mixed-size quotation and result cards.
4. **Practical capabilities** — Terminal demonstration paired with tool cards.
5. **Continuing value** — Lemon resource carousel flows directly into the dark directory; no separate final sales form.

**Transfer:** Introduce the platform through one promise, explain the mechanism, then mix proof and practical entry points before the resource-led ending.

### Product evaluation and sales conversion

1. **Promise and demonstration** — Paper split opening with framed demo and yellow repeated ribbon.
2. **Audience fit** — Parallel coral and mint illustrated panels.
3. **Differentiation** — Blue question followed by neutral problem and mint solution chapters with staged diagrams; cloud transition into another capability banner.
4. **Product explanation** — Callout cards, large yellow diagram chapter, capability grid and graph-paper ecosystem map.
5. **Social proof** — Blue quote band with portrait and overlapping nameplate.
6. **Objection handling** — Full-width FAQ rows.
7. **Closing call** — Illustrated contact form followed by the shared dark directory.

**Transfer:** Use color chapters for the main argument, then shift to factual cards and FAQs before the contact invitation.

### Transparent purchase decision

1. **Purchase promise** — Centered headline, compact product switch and three plan cards, with the middle choice raised.
2. **Detailed comparison** — Quote and long plan matrix with persistent headers and subtle rules.
3. **Tier explanation** — Sky-blue field with illustrated instance cards and short workload descriptions.
4. **Trust** — Integration band followed by alternating illustrated partnership, support and security splits.
5. **Objection handling** — Dense FAQ list.
6. **Closing call** — Centered mark, short free-start invitation and blue action before the directory.

**Transfer:** Separate the quick commercial decision from the detailed feature matrix; use illustrations to explain tiers rather than hiding pricing mechanics.

### Focused technical feature campaign

1. **Promise** — Centered mixed plain/illustrated headline in a yellow-and-blue landscape, with two actions.
2. **Product demonstration** — Short code block and side-by-side architecture comparison.
3. **Educational offer** — Book image and compact email form.
4. **Capability chapters** — Lemon-backed stacked white diagram/text panels, then a paper code demonstration.
5. **Continuing value** — Outlined resource carousel with a blog action.
6. **Closing call** — Graph-paper framed invitation that reprises the landscape, then the directory.

**Transfer:** Let one coherent metaphor carry both ends of a specialized story while diagrams and code carry the substance.

### Company credibility and connection

1. **Introduction** — Oversized mono title, illustrated foreground object and diagonal yellow repeating ribbon.
2. **Origin and principles** — Long text beside tilted colored value labels.
3. **Human proof** — Large natural outdoor group photo, then a restrained investor-logo row.
4. **Closing call** — Yellow contact/recruiting band with coral plaque, followed by a paper community banner and the dark directory.

**Transfer:** Use the institutional type variant and real photography; keep the core outlined stickers and ribbons to connect the story to the product world.

## Writing

Plainspoken technical confidence with a warm, lightly mischievous edge. Specific mechanisms and practical outcomes do most of the persuasion; occasional playful phrasing keeps the infrastructure approachable.

**Do not copy:** Do not reuse MotherDuck or DuckDB names, duck mascots, logos, proprietary product names, customer quotations, performance numbers, compliance assertions or trial terms as the new product's assets or claims. All examples illustrate tone and structure only.

- **Addressing the reader:** Address the reader as you and your; use we for the team and product name for factual mechanisms. Invite action without sounding like a distant enterprise vendor.
- **Rhythm:** Short uppercase headlines followed by one or two explanatory sentences. Longer technical paragraphs are reserved for mechanisms and FAQs; occasional asides, contractions and an emphatic stretched word add conversational texture.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Product category plus clear advantage or foundation. | 5–10 words | “Serverless Data Warehouse Built on DuckDB” |
| Section lead | A direct question or concise category label. | 1–6 words | “What Makes [Brand] Unique?”<br>“Support with a heart” |
| Supporting line | Explain who it serves or what becomes simpler, using an actual mechanism. | 1–2 sentences | “Plans that fit customer-facing analytics and internal data warehousing use cases.” |
| Capability title | Short benefit anchored in a technical action. | 2–7 words | “Maintenance made simple”<br>“Share business context” |
| Primary action | Plain verb with a clear next step or substantiated entry offer. | 2–5 words | “Get Started”<br>“Try 7 Days Free” |
| Closing invitation | Friendly invitation tied to what the reader is building. | 1–2 sentences | “We’d love to learn more about what you’re building. A Product Expert will fly right back to you with resources to help you take flight.” |

**Words and phrasing to use:** simple; built for; your; managed; share; fast; no more waiting; just; get started; learn more

**Avoid:** revolutionary paradigm; synergistic ecosystem; unprecedented transformation; world-class solution suite; empty superlatives without a mechanism

**Rules:**

- Follow a benefit with its practical cause: isolation, a simpler operation, fewer steps or a readable output.
- Use playful wording as a small accent, not a pun in every heading.
- Let technical terms remain technical; explain them with plain verbs and concrete relationships.
- Keep buttons literal and short; let supporting copy explain conditions and scope.

## Do's and Don'ts

### Do

- Keep the main text color charcoal #383838, including outlines, so the whole page shares one drawn edge.
- Preserve the regular 400 uppercase title treatment and light 300 paragraph contrast.
- Use a yellow repeated ribbon and overlapping white cloud silhouettes somewhere in the narrative.
- Keep desktop cards in a 32px-gutter grid with square 2px outlined white faces.
- Give the main demo or diagram a crisp lower-left offset rather than ambient elevation.
- Use paper-backed title plaques that overlap colored chapter boundaries.
- Stage a simple colored system illustration beside a real explanation, using generous pauses.
- Finish with a substantial charcoal directory and clearly grouped links.

### Don't

- Do not turn every corner into a pill: core buttons are 2px and marketing cards are square.
- Do not set the main headline in bold or compress it with negative tracking; its regular open width is intentional.
- Do not use black as the default full-page canvas; reserve the charcoal field for the directory, plaques and technical demonstrations.
- Do not wash every section into pale gradients; solid blue, yellow, coral and mint fields carry the chapter structure.
- Do not replace the line-drawn objects with glossy 3D renders or corporate stock photos.
- Do not use blurred gray card shadows; offsets are solid charcoal with no blur.
- Do not make every customer proof item an identical small tile; vary quotation, result and summary scale.
- Do not color every utility icon; keep navigation arrows and chevrons simple charcoal.

## Motion and responsive

### Motion

**Observed:**

- Primary action faces declare transform 120ms ease-in-out and move 7px right/up on ancestor hover; active returns them to rest.
- Feature cards declare transform 120ms ease-in-out and move 14px right/up on ancestor hover.
- The header declares border-bottom and background-color transitions at 200ms ease-in-out.
- Detailed feature cards use a sticky stacked arrangement; repeated ribbons extend beyond the viewport.

**Transfer:**

- Keep a stationary ink backing while moving only the interactive face.
- Use sticky illustrated chapters only when each text beat has a corresponding explanatory scene.

**Unknown:**

- Exact scroll animation timing, ribbon playback and sticky scene choreography are not established.
- No general focus treatment is established for all controls.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 556px, 728px, 960px, 1302px and 1600px; some pages add 600px or 1440px.

**Transfer:**

- For narrow screens, stack text and demo while keeping the hard offset and one foreground illustrated accent.
- Stack split audience and comparison panels, carrying their distinct color fields and plaques into the single column.
- Keep the repeated ribbon edge-to-edge and clipped horizontally; simplify the system diagram into a readable vertical sequence instead of shrinking its labels.

**Unknown:**

- Exact small-screen typography, navigation collapse and stacking thresholds are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
