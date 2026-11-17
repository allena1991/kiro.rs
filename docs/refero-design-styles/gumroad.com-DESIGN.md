# Gumroad — paper money playground

## Overview

An upbeat, approachable style that treats starting something new as play rather than corporate ceremony. Warm off-white space and black grotesk typography hold together bubblegum pink, golden yellow, acid yellow and periwinkle illustration. Flat outlined cartoons, sticker-like objects and simplified interfaces bring personality to an otherwise spacious, plainly spoken marketing system.

### Essentials

- A small promise gets a very big voice: regular 96px/1 grotesk headlines, -0.4px tracking and centered 24px/32px support make an ordinary sentence feel monumental.
- The opening is a clear center surrounded by playful debris: a 768px text column on off-white, with outlined pink objects roughly 176–256px wide around the edges and a glimpse of the next cards within the first 900px.
- Actions are little rectangles, not capsules: the primary face is black with white 20px/28px text, 64px height, 4px corners and concealed acid-yellow and red backing layers.
- Color behaves like printed paper: the default landing canvas stays predominantly #f4f4f0 with white cards; saturated pink, gold and acid yellow live in illustrations, stickers and selected bands rather than a wash over every section.
- The image language is flat but physical: black-contoured vector objects, hard offset edges, circular cartoon scenes and browser-window illustrations; every new page needs an original outlined object motif, with simple SVG tokens as the minimum fallback.
- Proof and discovery become visual events: use an oversized 192px/0.9 metric and a rail of 50px outlined pills interleaved with colorful stickers, adapting the metric and categories to real product content.
- The ending changes register: a generous 72px closing invitation leads toward a black footer with a 48px/1.25 subscription statement, slim email form and pink arrow action; the default landing treatment also includes a full-width illustrated world near the close.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden paper | `#ffc900` | `--color-gold` | background, accent, text | Cartoon backings and outlined loop diagrams; headings on black in gold-themed capability chapters. Pricing openings use a full gold field. |
| Bubblegum | `#ff90e8` | `--color-pink` | accent, background, action, link | Hero objects, footer arrow and link hover; large closing bands on detailed product pages. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#f1f333` | `--color-acid` | accent, background | Button backing layer and graphic accents; the capability overview opening uses a full acid field. |
| Backing red | `#dc341e` | `--color-red` | accent | Deepest outlined button backing layer and small illustrative accents. |
| Teal green | `#23a094` | `--color-green` | background, accent | Second fee panel on pricing pages and accents within flat artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, border, action | Text, outlines, primary actions, dark benefit panels and footer. |
| Graphite | `#242423` | `--color-graphite` | border | Search field and search icon edges. |
| Footer edge | `#4d4d4d` | `--color-dark-edge` | border | Visible white at 30% over black on the email input. |
| Soft graphite edge | `#8c8c8a` | `--color-soft-edge` | border, text | 50% #242423 used on paper for muted utility text; the same alpha ink outlines white cards, where it appears slightly lighter. |
| Pill edge | `#d1d5dc` | `--color-chip-edge` | border | Fine outline of discovery pills. |
| Warm paper | `#f4f4f0` | `--color-canvas` | background, surface | Default landing canvas and hero search field. |
| White paper | `#ffffff` | `--color-white` | surface, text, background | Cards and navigation; text against black. White is also the base canvas for detailed pricing and capability pages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| capability chapters and pricing comparisons | Periwinkle | `#90a8ed` | `--color-blue` | background, text | Media backings and matching headings on black. |

## Typography

- **ABC Favorit** — All marketing headings, paragraphs, navigation and labels. Direct contemporary grotesk, open and unpretentious, with regular and medium cuts doing most of the work. OpenType features: "ss04", "ss11". If unavailable, use **DM Sans**. Use 400 and 500; preserve broad headline widths and restrained tracking. Font stack: "ABC Favorit", "DM Sans", Arial, sans-serif.
- **Arial** (only for newsletter arrow controls) — Arrow glyph on the newsletter submit control. Plain system sans used for a single functional glyph. Font stack: "Arial", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| metric | ABC Favorit | 500 | 192px | 0.9 | -0.0021em | One isolated, enormous proof number. |
| display | ABC Favorit | 400 | 96px | 1 | -0.0042em | Default centered opening promise. |
| heading-lg | ABC Favorit | 400 | 72px | 1 | -0.0056em | Major discovery headline. |
| closing | ABC Favorit | 500 | 72px | 1 | -0.0056em | Closing invitation and FAQ section title. |
| heading | ABC Favorit | 500 | 48px | 1 | -0.0083em | Comparison statements and benefit headings. |
| statement | ABC Favorit | 400 | 48px | 1.25 | -0.0083em | Conversational manifesto statements and newsletter invitation. |
| card-heading | ABC Favorit | 400 | 36px | 40px | -0.011em | Feature card titles. |
| metric-caption | ABC Favorit | 400 | 30px | 1.2 | -0.0133em | Centered explanation beneath the proof number. |
| body | ABC Favorit | 400 | 24px | 32px | -0.0167em | Hero support, longer benefit copy and diagram labels. |
| pill-label | ABC Favorit | 500 | 24px | 32px | -0.0167em | Discovery rail category labels. |
| action | ABC Favorit | 400 | 20px | 1.4 | -0.02em | Primary conversion buttons and short supporting paragraphs. |
| caption-label | ABC Favorit | 500 | 20px | 1.4 | -0.02em | Floating illustration captions and chapter labels. |
| quote | ABC Favorit | 500 | 20px | 1.625 | -0.02em | Speech-card customer quotes. |
| body-small | ABC Favorit | 400 | 18px | 28px | -0.022em | Compact card explanations and navigation. |
| footer-link | ABC Favorit | 400 | 16px | 1.625 | -0.025em | Footer navigation and small ownership line. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and capability overview pages | page-display | ABC Favorit | 500 | 96px | 0.9 | -0.0042em | Multiline centered headline on a saturated opening field. |
| detailed capability and pricing pages | chapter-heading | ABC Favorit | 500 | 96px | 1 | -0.0042em | Centered introductory heading between capability chapters. |
| pricing pages | fee | ABC Favorit | 500 | 60px | 1 | -0.0067em | Fee figures in paired color panels. |
| pricing FAQs | question | ABC Favorit | 500 | 36px | 40px | -0.011em | Accordion question titles. |
| detailed capability and pricing pages | chapter-support | ABC Favorit | 400 | 30px | 40px | -0.0133em | Centered chapter explanation under the large title. |
| newsletter arrow controls | arrow | Arial | 400 | 16px | 1.5 | normal | Newsletter submit arrow. |

**Notes:**

- Keep the same -0.4px tracking across the grotesk scale rather than aggressively tightening large type.
- The default opening is regular weight; more structured detail-page openings use medium weight and 0.9 line height.
- Sentence case carries nearly all hierarchy. Even chapter labels are readable text, not miniature spaced capitals.

## Layout

**Density:** Airy: generous quiet paper surrounds large text, while the interior of illustrated cards is deliberately busy.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 12px | Footer link spacing and compact sticker-to-pill gaps. | fixed |
| 16px | Action row gap and card-grid side inset. | fixed |
| 24px | Hero text stack rhythm and quote-to-attribution separation. | fixed |
| 28px | Chapter label, title and supporting text stack. | fixed |
| 32px | Card padding, paired-card gutters and newsletter heading-to-form gap. | fixed |
| 40px | Detailed opening text gaps and button horizontal padding. | fixed |
| 64px | Closing heading-to-action gap, metric-to-caption separation and footer column separation. | fixed |
| 96px | Closing band and footer vertical padding. | fixed |
| 128px | Major section breathing room and detailed split-panel inner padding. | fixed |
| 172.8px | Desktop FAQ icon-to-question gap. | 12vw |
| 220.8px | FAQ answer indentation relative to its row. | calc(3rem + 12vw) |
| 256px | Vertical breathing room around the discovery rail. | fixed |

### Containers and grids

- **landing container**: max width 1152px · side padding 16px. Centered illustrated cards and quote grid; white cards occupy a narrower island within full-bleed paper.
- **opening text**: max width 768px. Centered headline and support column; let short headlines span the column without forcing multiple lines.
- **statement container**: max width 896px. Centered conversational statements.
- **closing container**: max width 1024px. Broad centered two-line closing invitation.
- **card pairs**: 2 columns · gap 32px. Mix a two-thirds illustrated feature with a one-third card, then reverse emphasis; use equal halves for quotes and before/after scenes.
- **chapter split** (only for detailed capability and pricing pages): 2 columns · gap 0px · side padding 128px. Full-bleed 720px halves at desktop: saturated media on one side, black benefits on the other.

## Corner radius

| Element | Radius |
| --- | --- |
| action face | 4px |
| feature cards | 24px |
| comparison and captions | 16px |
| discovery and navigation pills | 9999px (pill) |
| search icon button | 6px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default landing background.

**CSS:** `background: #f4f4f0; color: #000000`

**Transfer:** Keep the broad canvas neutral so outlined art reads as placed objects.

#### Outlined card · level 1

**Use:** Features, comparisons and quote containers.

**CSS:** `background: #ffffff; border: 1px solid rgba(36,36,35,0.5); border-radius: 24px; box-shadow: none`

**Observed:** Borders, not soft shadows, define the container. Comparison cards use 16px corners.

**Transfer:** Use clear silhouettes and allow illustrative objects to overhang selected cards.

#### Black panel · level 0

**Use:** Footer and detailed benefit panels.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Benefit headings take the hue of the adjacent media panel; footer headings remain white.

**Transfer:** Treat black as a substantial paper panel rather than a translucent overlay.

#### Pink invitation band · level 0

**Only for:** detailed capability and pricing pages

**Use:** Closing conversion invitation.

**CSS:** `background: #ff90e8; border-top: 1px solid #000000; padding: 96px 57.6px`

**Observed:** Full width with centered black heading and white action face.

**Transfer:** Use one decisive pink closing field rather than pinking every section.

#### Colored chapter stage · level 0

**Only for:** detailed capability and pricing pages

**Use:** Large outlined illustration backing.

**CSS:** `background: #90a8ed; border-right: 1px solid #000000; padding: 128px`

**Observed:** Gold and pink are alternate stage colors; each sits flush against a black text panel.

**Transfer:** Give a family of related capabilities one stage hue.

## Components

### Navigation bar

**Use:** Persistent orientation and immediate conversion.

**CSS:** `position: sticky; top: 0px; height: 80px; display: flex; justify-content: space-between; padding-left: 32px; background: #ffffff; border-bottom: 1px solid #000000; z-index: 50`

**Text style:** `body-small` — ABC Favorit 400 · 18px/28px · tracking -0.022em

**Observed:** Wordmark and compact repository-count badge sit left. The right side has pill links, then full-height login and black conversion cells separated by vertical rules.

**Transfer:** Use the new identity at a compact scale and retain the sharply ruled action end.

### Navigation pill

**Use:** Top-level destinations.

**CSS:** `border: 1px solid transparent; border-radius: 9999px; padding: 8px 16px; color: #000000; display: flex; align-items: center; justify-content: center`

**Text style:** `body-small` — ABC Favorit 400 · 18px/28px · tracking -0.022em

**Observed:** The selected destination is a black filled pill with white text; other destinations remain open on white.

**States:** Declared: hover border-color #000; focus-visible not specified.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 64px; padding: 0px 40px; border: 1px solid #000000; border-radius: 4px; background: #000000; color: #ffffff; position: relative; z-index: 3`

**Text style:** `action` — ABC Favorit 400 · 20px/1.4 · tracking -0.02em

**Observed:** Three coincident outlined rectangles form the object: red at the back, acid yellow in the middle, action face in front. The backing layers are hidden at rest. On pink detail-page closing bands the front is white with black text.

**States:** Declared: hover translate 00 on the action face; focus-visible not specified. Transition all 0.15s cubic-bezier(.4,0,.2,1).

**Transfer:** Retain the layered paper construction rather than substituting a blurred elevation shadow.

### Feature card

**Use:** Compact benefit and product demonstration.

**CSS:** `position: relative; display: flex; flex-direction: column; background: #ffffff; border: 1px solid rgba(36,36,35,0.5); border-radius: 24px; padding: 32px; height: 480px`

**Text style:** `card-heading` — ABC Favorit 400 · 36px/40px · tracking -0.011em

**Observed:** A short title is anchored toward the upper left, a compact explanation sits lower left, and a large illustrated product object occupies the remaining space or extends above the edge.

**Transfer:** Use a recognizably simplified working object, not a generic icon above a paragraph.

### Speech quote

**Use:** Human proof in a two-column grid.

**CSS:** `position: relative; background: #ffffff; border: 1px solid rgba(36,36,35,0.5); border-radius: 24px 24px 24px 4px; padding: 16px 32px; margin-bottom: 24px`

**Text style:** `quote` — ABC Favorit 500 · 20px/1.625 · tracking -0.02em

**Observed:** Opening quotation mark and medium-weight paragraph stay in the bubble. A 48px circular avatar and stacked name and descriptor sit outside below, aligned near the clipped bottom-left corner.

**Transfer:** Preserve the speech silhouette with genuine first-person quotes.

### Discovery pill

**Use:** Moving taxonomy or use-case rail.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #d1d5dc; border-radius: 9999px; padding: 8px 16px; height: 50px`

**Text style:** `pill-label` — ABC Favorit 500 · 24px/32px · tracking -0.0167em

**Observed:** Varying label widths are interleaved with colored outlined stickers in three rows that continue beyond both viewport edges.

**States:** Declared: hover translate 00 and transparent zero shadows; focus-visible not specified.

### Floating caption

**Use:** Short narrative label attached to an illustration.

**CSS:** `background: #ffffff; border: 1px solid #000000; border-radius: 16px; padding: 16px 32px; position: absolute`

**Text style:** `caption-label` — ABC Favorit 500 · 20px/1.4 · tracking -0.02em

**Observed:** A white caption straddles a circular scene or sits near its upper edge. A paired caption completes the thought in the adjacent scene.

**Transfer:** Use short contrast phrases that guide a before/after reading.

### Search field

**Use:** Secondary discovery action beside the hero conversion.

**CSS:** `background: #f4f4f0; border: 1px solid #242423; border-radius: 4px; height: 64px; width: 365px; padding: 0px 80px 0px 32px`

**Observed:** An inset white 42px square button with 6px corners contains a 24px outlined magnifier at the right.

**Transfer:** When search is not a useful product action, use a similarly proportioned secondary utility rather than fake search.

### Newsletter input

**Use:** Footer subscription form.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid rgba(255,255,255,0.3); border-radius: 4px; height: 48px; padding: 0px 16px; width: 560px`

**Observed:** A long transparent field occupies most of a 630px form row; the arrow control sits 4px away.

**Transfer:** Let the field flex to available width while retaining the narrow outlined treatment.

### Newsletter arrow

**Use:** Submit the footer form.

**CSS:** `background: #ff90e8; color: #000000; border: 1px solid #000000; border-radius: 4px; height: 48px; width: 66px; padding: 0px 24px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `arrow` — Arial 400 · 16px/1.5

**Observed:** Uses the same concealed colored backing-layer construction as the primary button, reduced to an arrow-only control.

**States:** Declared: hover translate 00; focus-visible not specified.

### Footer link

**Use:** Small navigation columns on black.

**CSS:** `color: #ffffff; text-decoration: none`

**Text style:** `footer-link` — ABC Favorit 400 · 16px/1.625 · tracking -0.025em

**Observed:** Two columns balance the subscription block; icons form a separate lower horizontal row.

**States:** Declared: hover color #ff90e8; focus-visible not specified.

### FAQ row

**Only for:** pricing FAQs

**Use:** Objection handling with expandable answers.

**CSS:** `border-top: 1px solid #000000; padding: 64px 0px; display: flex; align-items: center`

**Text style:** `question` — ABC Favorit 500 · 36px/40px · tracking -0.011em

**Observed:** A 48px plus icon leads, followed by a 172.8px desktop gap before the question. Closed rows are 177px tall. Answers use body text, aligned under the question rather than the plus.

**Transfer:** Keep the broad rule and strong left icon; use real questions rather than feature slogans.

## Imagery and graphics

### Outlined token orbit

**Use:** Signature object language in the first screen and throughout discovery.

**Observed:** Pink coin-like objects with black contours and bold face symbols drift around the clear center. Several are tilted ellipses with narrow extruded rims; some are clipped by the viewport. The objects are flat colored, not shaded metallic renders.

**Transfer:** Invent tokens related to the new product: tickets, tools, folded notes or abstract badges. Minimum acceptable execution is a set of carefully outlined SVG discs with an original simple symbol.

**Build:** Draw an elliptical front and offset rear ellipse joined at the edges, with a 1–2px black contour. Fill both pink, add a black geometric face symbol, then rotate whole groups at varied angles. Use roughly 176–256px objects around the perimeter, keeping the central 768px clear. No blur or gradient.

### Illustrated interface objects

**Use:** Feature cards and substantial capability stages.

**Observed:** White browser windows with black outlines, small colored window dots and heavy hard black lower-right edges show simplified product tasks. Bright cartoon characters or sticker objects overlap the interface. Media is often as large as, or larger than, the accompanying text.

**Transfer:** Reduce a real workflow to one or two legible interface objects, retaining the outlines and cheerful backing. Avoid tiny detailed dashboard replicas.

**Build:** Construct rounded white SVG window rectangles with a black stroke, top divider and three small colored dots. Add an offset solid black duplicate behind the window as a drawn extrusion. Inside, use a few large text lines, blocks and one salient control; place a gold, teal or pink outlined sticker across one corner.

### Circular narrative scenes

**Use:** Paired illustrated comparisons and human-scale benefits.

**Observed:** Simple pink-headed characters inhabit everyday working or outdoor scenes. Gold circles or periwinkle sky discs crop the scene; flat teal ground, acid clothing and black detail lines provide contrast. Floating caption components sit above the artwork.

**Transfer:** Show the new product's everyday change in two original moments. Minimum version: a circular flat vector vignette with one person, one relevant object and a caption.

**Build:** Clip SVG art to a roughly 412px circle. Divide into two or three flat color regions, add a simple silhouette with black outlines and a few purposeful props, and let one caption overlap the circle boundary.

### Discovery stickers

**Use:** Small visual interruptions among category pills and larger media objects.

**Observed:** Colored books, tools, hands and abstract objects are rendered as cutout stickers with black interior lines. They alternate with white text pills instead of living inside uniform icon containers.

**Transfer:** Create a compact family of original task-related symbols; retain mixed silhouettes and multiple bright fills.

**Build:** Draw simple SVG silhouettes with a broad colored outer contour and thin black interior contours. Use gold, pink, teal, acid yellow and periwinkle across the set. Rotate individual objects slightly and vary their silhouettes rather than applying one bounding-box shape.

### Loop diagram

**Use:** A visual explanation of a repeatable method.

**Observed:** Broad gold outlined racetrack loops carry 24px labels on the landing treatment. The capability opening uses pink loops on acid yellow, with labels connected by arrows and outlined creative-tool objects inside.

**Transfer:** Map a real short cycle in the new product to an elongated loop. A clean SVG track with three or four labels is the minimum version.

**Build:** Use a wide 1152px pill-shaped SVG path, black 1px outer and inner outlines, gold fill and a second inset track line. Place labels along the top and bottom with matching fill patches behind text. Add small black directional arrows. Use pink fill only for the capability-overview variant.

### Illustrated closing world

**Use:** Signature full-width landing-page closing scene.

**Observed:** A 504px-high illustrated strip places stylized people and everyday activity around a gold path across teal ground, all edged with black drawing. It transitions from the invitation into the black footer without a card frame.

**Transfer:** Create an original panoramic scene of people using or benefiting from the product. Minimum acceptable version is a full-bleed flat landscape with a continuous colored path, a few original figures and recognizable product props.

**Build:** Compose a 1440px-wide SVG scene with teal ground, a broad horizontal gold path and sparse black seam lines. Distribute three or more simple outlined figures and props at different points across the panorama. Keep the color flat and the horizon uncomplicated; use object-fit cover with a 300px minimum height.

### Portrait collage

**Only for:** capability-page customer spotlight

**Use:** Large testimonial carousel between capability chapters.

**Observed:** A natural photographic cutout portrait fills the left half of a pink band, clipped into an irregular ink-outlined organic shape with a darker colored backing. A large black quote and bold attribution occupy the right. Tiny circular slide indicators sit below; thin arrows sit at the side edges.

**Transfer:** Use an authentic consenting customer portrait against an original organic cut-paper silhouette, not corporate headshots in identical circles.

### Icons

**Observed:** Functional symbols are black outlined or solid SVGs: 24px magnifier with 2px rounded stroke, 48px plus controls, and small directional arrows. Footer social symbols are white and compact.

**Transfer:** Keep functional icons plain and monochrome; reserve the multicolor cutout treatment for illustrative stickers.

## Section recipes

How recurring sections are built.

### First screen: Paper promise opening

**Observed:** An 80px sticky Navigation bar caps an off-white hero. The central 768px column is surrounded by Outlined token orbit artwork with the biggest shapes clipped at side edges. The single-line 96px regular headline spans about half the viewport width, above a centered two-line support paragraph. A black Primary button and Search field share a row 32px below the support, separated by 16px; a muted utility link follows 24px lower. Layers run paper, perimeter tokens, centered text and actions, then overlapping white feature cards. Within the first 900px the entire promise, support and action row are visible, with the upper part of the next cards and their overhanging interface art. The hero is 776px tall beneath the navigation; the card collection overlaps its bottom by 80px.

**Transfer:** Make a short, concrete change feel attainable; surround it with original product-related outlined tokens rather than copying the face symbol. Use a meaningful secondary utility only when needed. Pricing pages instead open on gold with a 24px label, medium 96px/0.9 multiline headline and support at 40px gaps. Capability overview pages use acid yellow, receipt-like edge objects and a pink Loop diagram beginning below the support and continuing below the fold.

**Avoid:** Do not turn this into a left-aligned SaaS hero with a huge screenshot on the right, or put decorative objects behind the headline where they reduce clarity.

**Text style:** `display` — ABC Favorit 400 · 96px/1 · tracking -0.0042em

### Asymmetric illustrated card island

**Observed:** Feature card pairs sit in the landing container with 32px gaps. A wide card carries overhanging browser-window art while a narrow neighbor carries a smaller scene; subsequent pairs vary emphasis. Card-heading and body-small keep the text subordinate to the image.

**Transfer:** Group related capabilities into a small number of distinct scenes, allowing proportions and art overlap to differ.

### Conversational method

**Observed:** Centered 48px/60px statements bracket a gold Loop diagram with body-size labels. A 20px supporting paragraph and Primary button follow; the whole band has 128px vertical padding.

**Transfer:** Explain a short repeatable method as a visual cycle, framed by encouraging human language rather than numbered feature bullets.

**Text style:** `statement` — ABC Favorit 400 · 48px/1.25 · tracking -0.0083em

### Monumental proof

**Observed:** A single 192px medium number sits directly on paper, with 160px top space and a 64px gap before a centered 30px/36px caption constrained to 672px. No card, badge or chart competes with it.

**Transfer:** Use one verified outcome or scale indicator; make its explanatory sentence tell readers exactly what was measured.

**Text style:** `metric` — ABC Favorit 500 · 192px/0.9 · tracking -0.0021em

### Human proof grid

**Observed:** Speech quote components form two columns with 32px gutters and 48px row gaps, with avatar attributions outside the bubbles.

**Transfer:** Use quotes with concrete personal changes, keeping attribution visually separate from the spoken paragraph.

### Discovery field

**Observed:** A centered 72px regular heading and 24px support sit above three edge-clipped rails of Discovery pills and stickers. The section uses 256px top and bottom padding and a 96px gap between the heading stack and rails.

**Transfer:** Use categories, outcomes or user tasks to create an abundant vocabulary; preserve the sticker interruptions and full-width overflow.

### Small contrast diptych

**Observed:** Two equal columns alternate short 48px headings with circular narrative scenes, on white 16px-radius cards separated by 32px gaps. Floating captions complete a contrasting sentence across the pair.

**Transfer:** Compare an intimidating old approach with a smaller achievable next step; let scenes do more than decorative work.

### Invitation and black sign-off

**Observed:** A centered Closing heading in a 1024px container has a 64px gap to the Primary button and 96px vertical padding. The default paper invitation is followed by the Illustrated closing world and then a Black panel footer. The footer uses 96px vertical padding and 57.6px side padding, a left 48px/60px subscription statement with form 32px below, two link columns on the right, and an ownership line and white social icons lower down. Detail pages use Pink invitation band and a white button, proceeding directly into the same footer.

**Transfer:** End with an encouraging invitation, then offer a smaller ongoing relationship through the subscription form. Keep the footer a substantial final composition rather than a thin legal strip.

**Text style:** `closing` — ABC Favorit 500 · 72px/1 · tracking -0.0056em

### Chapter heading pair

**Only for:** detailed capability and pricing pages

**Observed:** White interludes use 96px top and 128px bottom padding, a centered short label, a 96px medium heading and 30px/40px support in a 768px column; the stack gap is 28px.

**Transfer:** Use these pauses to organize long capability pages into readable themes.

**Text style:** `chapter-heading` — ABC Favorit 500 · 96px/1 · tracking -0.0042em

### Color and black split

**Only for:** detailed capability and pricing pages

**Observed:** Flush equal-width halves pair a Colored chapter stage with a Black panel. Text halves use 128px padding and stack two or three 48px colored headings above white 24px explanations. Alternate the art side between rows; use gold or periwinkle consistently through a capability family.

**Transfer:** Give each split a coherent capability theme and a large custom outlined product object.

**Text style:** `heading` — ABC Favorit 500 · 48px/1 · tracking -0.0083em

### Paired fee panels

**Only for:** pricing pages

**Observed:** Two equal full-width periwinkle and teal blocks use 128px padding, centered 60px fee figures and 24px explanatory text 32px below. Black rules divide and finish the band.

**Transfer:** Compare two real charge conditions directly, without dressing them as subscription cards when they are not plans.

**Text style:** `fee` — ABC Favorit 500 · 60px/1 · tracking -0.0067em

### Questions with room

**Only for:** pricing FAQs

**Observed:** A centered 72px title leads to FAQ row components within 112px side margins. The closed presentation shows only plus symbols and questions between rules; expanded answers use 24px text beneath the title alignment.

**Transfer:** Collect real purchase objections in this spacious ruled format rather than a dense card grid.

**Text style:** `question` — ABC Favorit 500 · 36px/40px · tracking -0.011em

## Page flow

**Storyline:** attainable promise → tangible capability scenes → method and proof → breadth or deeper explanation → reassuring invitation → ongoing relationship

### Broad product landing page that lowers the emotional barrier to trying

1. **promise** — Centered paper hero with perimeter token art and immediate actions.
2. **capability demonstration** — Asymmetric illustrated card pairs and captioned scenes.
3. **method** — Large conversational statements around an outlined loop.
4. **quantified and human proof** — One monumental number followed by speech quotes with avatars.
5. **breadth** — Moving category pills with small stickers.
6. **reassurance** — Contrasting small-step scenes.
7. **closing call** — Large invitation, panoramic illustrated world and black newsletter footer.

**Transfer:** Let simple actions and visible outcomes replace enterprise-style feature inventories.

### Pricing explanation with direct fees and reassurance

1. **promise** — Gold opening with a clear multiline headline and floating outlined tokens.
2. **pricing** — Two contrasting fee panels with plain explanations.
3. **obligation handling** — Large centered heading pair followed by illustration-and-black explanation split.
4. **objection handling** — Generously ruled FAQ rows.
5. **closing call** — Pink invitation band with white action, then black newsletter footer.

**Transfer:** State the charging model first and use the rest of the page to remove uncertainty.

### Long-form capability overview organized into approachable chapters

1. **promise and method** — Acid-yellow opening with receipts and a pink process loop.
2. **capability chapters** — White heading interludes alternate with saturated illustration and black-copy halves.
3. **social proof** — Pink portrait collage carousel interrupts the chapter rhythm.
4. **deeper capability demonstration** — Related groups share gold or periwinkle, with alternating art sides.
5. **closing call** — Pink invitation and common black newsletter footer.

**Transfer:** Organize a long toolset by user outcomes and give each family a coherent visual backing.

## Writing

Friendly, candid and encouraging, with the confidence of someone who has already made the first step. Benefits are explained in everyday language, with occasional puns and casual asides rather than institutional sales language.

**Do not copy:** Do not reuse Gumroad names, logos, character art, customer identities, quotations, revenue figures, fees, tax promises or other brand-specific claims. Examples illustrate voice, not reusable product facts.

- **Addressing the reader:** Speak directly to you and your; use we for the product team. Make the reader the person doing the interesting work.
- **Rhythm:** Short headline clauses, often two paired thoughts. Supporting paragraphs are conversational and concrete; fragments, contractions and occasional exclamation marks are welcome when they sound spoken.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An easy-to-understand change or fresh start, compressed into a short phrase. | 4–6 words | “Go from 0 to $1”<br>“Built for new beginnings” |
| Support | Reassure first, then explain a practical next step in ordinary language. | 1–3 short sentences | “Anyone can earn their first dollar online. Just start with what you know, see what sticks, and get paid. It's that easy.” |
| Capability heading | Direct benefit or light everyday metaphor; occasional wordplay. | 3–7 words | “Money, incoming”<br>“Don't sweat VAT”<br>“Your store, your way” |
| Primary action | Start plus a familiar verb, or a plain invitation to learn. | 2–4 words | “Start selling”<br>“Find out how” |
| Closing invitation | Imperative plus a warm reason someone should act. | Two short sentences | “Share your work. Someone out there needs it.” |

**Words and phrasing to use:** start; try; your way; simple; get going; No problem; you don't have to; small

**Avoid:** synergize; enterprise-grade transformation; unlock limitless potential; revolutionary ecosystem; seamless end-to-end excellence

**Rules:**

- Name the actual activity or outcome rather than replacing it with abstract productivity language.
- Use a playful turn of phrase only when the adjacent paragraph explains the practical benefit.
- Make reassurance specific: explain what is easy, handled or unnecessary.
- Use contrast to make starting feel smaller, not to shame the reader.

## Do's and Don'ts

### Do

- Keep the default hero at 96px/1 and weight 400, with -0.4px tracking.
- Keep the default landing background off-white and the cards white.
- Use black 1px outlines and 24px card corners instead of soft elevation.
- Give primary buttons 64px height, 4px corners and a clearly separate colored backing construction.
- Pair the 192px proof number with a plain explanatory 30px caption.
- Interleave 50px category pills with irregular colored stickers.
- Keep detailed chapter splits equal-width and flush, with black text panels and saturated media halves.
- Give the black footer real space: 96px vertical padding and a 48px subscription statement.

### Don't

- Do not make every headline bold; 400 and 500 carry the hierarchy.
- Do not round conversion buttons into the pill silhouette used by navigation and discovery.
- Do not add photographic gradients, glossy metallic lighting or ambient glows to the flat token art.
- Do not replace drawn black extrusions with diffuse box shadows.
- Do not scatter periwinkle full-bleed panels throughout an ordinary paper landing page; reserve that treatment for capability chapters.
- Do not make the footer pale to match the page; its black ground is a deliberate ending.
- Do not render discovery categories as a rigid grid of identical colored squares.
- Do not reduce all illustrations to small uniform line icons inside cards.

## Motion and responsive

### Motion

**Observed:**

- Declared navigation transition: all 0.2s cubic-bezier(.4,0,.2,1); button faces and backing layers use 0.15s with the same curve.
- Declared category marquee: 60s linear infinite; rail classes pause it on hover.
- Parallax-scroll and marquee-related keyframes are declared; their complete visual trajectories are not established.

**Transfer:**

- Retain the slow continuous rail for the discovery field and its hover pause.
- Keep outlined button layers separate so their short transitions can reveal the colored paper construction.

**Unknown:**

- Complete button-group hover offsets and focus-visible appearance are not established.
- Portrait-carousel timing and automatic advance behavior are not established.

### Responsive

**Observed:**

- Desktop composition uses 1440px width and an 80px navigation bar. Layout classes provide stacked alternatives to paired cards and capability halves, and smaller text alternatives to desktop display sizes.

**Transfer:**

- On narrow screens, stack card pairs and split chapters, keeping each illustration adjacent to its explanation.
- Reduce perimeter artwork before allowing it to overlap the promise; keep the headline and action legible.
- Let the discovery rails continue beyond the viewport, while making forms fit the available width.

**Unknown:**

- Exact breakpoint widths and mobile type sizes are not established.
- Mobile navigation interaction and small-screen illustration cropping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
