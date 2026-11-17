# Paper — the tactile drafting canvas

## Overview

A light, softly textured workshop aesthetic for creative tools and technically fluent products. Warm ivory and pale stone carry delicate drafting lines, restrained blue accents and airy geometric grotesk typography. Large working-interface scenes contrast with small, conversational copy; occasional paper constructions and an almost invisible monumental wordmark make the otherwise orderly layout feel handmade.

### Essentials

- Headlines behave like editable canvas text, not advertising posters: Matter at 48px/1, weight 360, -0.02em tracking; an ink promise continues into equally sized gray explanatory lines.
- The opening pairs a left-aligned three-line promise with a broad working window below: a 1080px content rail, 600px support measure, 40px primary action and a plain adjacent text action.
- The whole page feels like a drafting surface: cream outside off-white square-edged cells, 1px rules, 12px selection handles and faint rulers, grids and geometric masks. Carry these devices into every new landing page.
- Color is a small object inside a mostly neutral room: ink buttons have 4px corners; blue belongs to the brand mark, controls and occasional special action, while richer hues stay inside demonstration artwork rather than full-page bands.
- Demonstrations are large working objects with overlapping windows, not floating feature icons: light interface chrome, 12px window corners, fine edges and layered soft shadows; use a credible task scene when no original product media exists.
- The ending is a sheet lifting away from a textured footer: a 728px footer with 120px vertical inset, small uppercase column headings, readable 18px links and a giant near-invisible outlined wordmark cropped by the lower edge. Recreate that oversized typographic imprint with the new identity.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft working blue | `#82aae2` | `--color-blue` | accent | Small brand and collaborative markers; not a large marketing background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light paper | `#fcfcf9` | `--color-paper` | surface, background, text | Content cells, navigation, footer and reversed action labels. |
| Cream drafting ground | `#efefe4` | `--color-canvas` | background | Warm outer canvas behind the continuous content grid. |
| Pencil edge | `#d7d7d6` | `--color-rule` | border | Continuous cell boundaries and tiny selection-handle edges. |
| Headline gray | `#909090` | `--color-gray` | text | Secondary display lines and subdued captions. |
| Column label gray | `#8a8a89` | `--color-faint-text` | text | Visible result of 50% ink over paper for footer labels. |
| Dark gray | `#666666` | `--color-muted` | text | Supporting prose on light panels. |
| Translucent ink on paper | `#464645` | `--color-secondary` | text | Visible result of 80% ink on light paper; use rgba(24,24,24,0.8) for the live text treatment. |
| Off black | `#181818` | `--color-ink` | text, action | Primary text and default conversion-button fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| public planning pages | Collaborator amber | `#e99d15` | `--color-amber` | accent | Collaborator dots and names. |
| public planning pages | Collaborator violet | `#a293e1` | `--color-violet` | accent | Collaborator dots and forthcoming-state markers. |
| public planning pages | Completed lime | `#b4d759` | `--color-done` | accent | Tiny completed-status dot. |
| public planning pages | Warm annotation paper | `#f9f8f1` | `--color-bubble` | surface | Floating annotation cards, slightly warmer than the main cells. |

## Typography

- **Matter** — All marketing headings, paragraphs, actions and navigation. Open geometric grotesk with a rounded, informal lowercase and unusually light large headings. OpenType features: "calt". If unavailable, use **DM Sans**. Use variable weights 360, 400, 480 and 550; preserve tight display spacing. Font stack: "Matter", "DM Sans", system-ui, sans-serif.
- **Paper Mono** (only for planning status labels and technical release notes) — Status tags, keyboard shortcuts and inline code. Compact practical monospace that gives technical details a tool-like finish. If unavailable, use **IBM Plex Mono**. Font stack: "Paper Mono", "IBM Plex Mono", SFMono-Regular, Menlo, ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display-card | Matter | 360 | 64px | 1 | -0.02em, features "ss01" | Large two-line title inside the inset destination card; also a planning-page title. |
| display | Matter | 360 | 48px | 1 | -0.02em, features "ss01" | Opening statement, its gray continuation and major capability headings. |
| body | Matter | 400 | 18px | 28px | 0.01em, features "calt" | Support paragraphs, navigation and sentence-case section eyebrows. |
| item-heading | Matter | 550 | 18px | 28px | 0.01em | Compact card headings and release-note category headings. |
| button | Matter | 480 | 18px | 28px | 0.01em, features "calt" | Filled action labels. |
| footer-link | Matter | 400 | 18px | 28px | -0.01em, features "calt" | Footer destination and contact links. |
| column-label | Matter | 500 | 14px | 28px | 0.05em, uppercase, features "calt" | Footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| release archives | date | Matter | 480 | 24px | 32px | 0.005em, features "calt" | Linked month or release date beneath a large artwork. |
| comparison pages | article-heading | Matter | 480 | 24px | 28px | 0.005em, features "calt" | Editorial comparison section headings. |
| comparison pages | table-body | Matter | 400 | 16px | 1.5 | 0.015em, features "calt" | Detailed comparison cells. |
| comparison pages | table-key | Matter | 480 | 16px | 1.5 | 0.015em, features "calt" | Comparison row names. |
| comparison pages | table-label | Matter | 700 | 14px | 20px | 0.06em, uppercase, features "calt" | Small table column headers. |
| technical release notes | keycap | Paper Mono | 400 | 13.5px | 1.7 | 0.013em | Inline keyboard shortcut labels. |
| public planning pages | status | Paper Mono | 400 | 13px | 28px | 0.014em, features "calt" | Compact progress-state labels. |

**Notes:**

- Keep the display light even when it describes an ambitious product. Dark and gray headline runs share the same metrics; gray is not a smaller subtitle.
- The standard eyebrow is ordinary 18px body text, not a miniature uppercase mono label. Uppercase is reserved for organizational furniture.
- Body copy uses positive tracking, while large type and footer links tighten. Do not normalize all roles to one tracking value.

## Layout

**Density:** Airy framed chapters around dense working demonstrations; reading columns remain comfortable even in long technical lists.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small list-item and compact content gaps. |
| 18px | Opening headline-to-support gap. |
| 24px | Eyebrow, headline and support separation in capability cells. |
| 30px | Support-to-actions separation and inset-card content gap. |
| 40px | Main panel inner padding. |
| 60px | Planning cell inset and space above archive dates. |
| 120px | Footer vertical inset and larger geometric construction intervals. |
| 240px | Breathing room between the end of the main grid and the footer on the landing and comparison treatments. |

### Containers and grids

- **main rail**: max width 1080px · side padding 0px. Centered desktop content rail; at 1440px it leaves 180px outer margins. The navigation, opening and continuous chapter grid align to it.
- **connected cells**: 2 columns · gap 0px. Equal-width cells share 1px rules rather than gutters. Full-width media and heading cells span both columns.
- **support measure**: max width 600px. Opening support prose and broad section descriptions.
- **article measure** (only for comparison pages): max width 750px. Text remains narrower than the surrounding table and social proof.
- **archive rail** (only for release archives): max width 842px · side padding 40px. Bordered archive column; media bleeds to the inner 840px width and prose has a 760px measure.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing panels | 0px |
|  | primary actions | 4px |
|  | working windows | 12px |
| public planning pages | status tags | 6px |
| public planning pages | annotation cards | 12px |
| technical release notes | shortcut keys | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| lifted main sheet | `rgba(0,0,0,0.12) 0px 16px 32px -16px, rgba(0,0,0,0.08) 0px 8px 16px -8px, rgba(0,0,0,0.04) 0px 4px 8px -4px, rgba(0,0,0,0.02) 0px 2px 4px 0px, rgba(0,0,0,0.08) 0px 0px 0px 1px` | The main page plane above the footer. |
| working window | `rgba(128,128,128,0.15) 0px 0px 0px 1px, rgba(0,0,0,0.01) 0px 59px 24px 0px, rgba(0,0,0,0.05) 0px 33px 20px 0px, rgba(0,0,0,0.09) 0px 15px 15px 0px, rgba(0,0,0,0.1) 0px 4px 8px 0px` | Large hero application window, not every content tile. |

### Surfaces

#### Drafting ground · level 0

**Use:** Warm background surrounding the page's working sheets.

**CSS:** `background: #efefe4`

**Observed:** Fine paper grain, pale construction geometry and ruler ticks sit behind the content; no high-contrast decorative wallpaper.

**Transfer:** Use the Drafting geometry build to carry a neutral workshop atmosphere.

#### Connected paper cell · level 1

**Use:** Feature chapters, cards and destination panels.

**CSS:** `background: #fcfcf9; border-right: 1px solid #d7d7d6; border-bottom: 1px solid #d7d7d6; border-radius: 0px; box-shadow: none`

**Observed:** An enclosing grid supplies the top and left edges. Cells meet directly; tiny selection squares punctuate important corners.

**Transfer:** Treat panels as one composed document, not a collection of floating rounded cards.

#### Footer paper · level 0

**Use:** Shared closing plane.

**CSS:** `background: #fcfcf9; overflow: hidden`

**Observed:** A paper texture uses multiply at 0.5 opacity; a 10px grid uses overlay at 0.3. An extremely faint outline wordmark extends beneath links and off the page.

**Transfer:** Keep the texture and imprint below the contrast of all readable content.

## Components

### Navigation

**Use:** Persistent orientation across page types.

**CSS:** `position: fixed; top: 0px; height: 61px; z-index: 50; background: #fcfcf9; box-shadow: 0px 1px 0px rgba(0,0,0,0.08)`

**Text style:** `body` — Matter 400 · 18px/28px · tracking 0.01em

**Observed:** Brand at the left edge of the main rail, short destination links across the middle and a plain sign-up link on the right. No large filled navigation CTA.

**Transfer:** Use a small identity and a compact set of relevant destinations.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 6px 14px; gap: 6px; background: #181818; color: #fcfcf9; border-radius: 4px`

**Text style:** `button` — Matter 480 · 18px/28px · tracking 0.01em

**Observed:** Short rectangular action paired with a text alternative; platform symbols may precede the label. A special desktop-promotion variant uses a soft blue vertical gradient, 42px height and 7px 18px padding.

**States:** Declared: hover background becomes black; focus-visible 2px blue outline with 2px offset and 2px corner radius; active scale 0.97.

### Text destination

**Use:** Secondary actions and footer navigation.

**CSS:** `color: #181818; opacity: 0.8; transition: opacity 0.15s ease`

**Text style:** `footer-link` — Matter 400 · 18px/28px · tracking -0.01em

**Observed:** No container; editorial onward links and the opening alternative can end with a right arrow. Footer destinations are stacked with a 10px gap.

**States:** Declared: hover opacity 1; focus-visible 2px blue outline with 2px offset.

### Feature cell

**Use:** Compact benefit or capability explanation.

**CSS:** `background: #fcfcf9; border-right: 1px solid #d7d7d6; border-bottom: 1px solid #d7d7d6; border-radius: 0px`

**Text style:** `body` — Matter 400 · 18px/28px · tracking 0.01em

**Observed:** A compact heavier title precedes ordinary prose. The landing treatment uses 40px inner padding and two equal cells; planning cells use a 60px inset and a status at the bottom.

**Transfer:** Keep each cell about one useful capability, not a dense inventory.

### Inset destination card

**Use:** A larger onward invitation within the drafting grid.

**CSS:** `background: #fcfcf9; padding: 40px; display: flex; flex-direction: column; align-items: flex-start; gap: 30px`

**Text style:** `display-card` — Matter 360 · 64px/1 · tracking -0.02em

**Observed:** A square bordered card sits inset from the containing panel. Large two-line title, narrower muted description and Primary button occupy the left; a small tactile geometric object sits outside it on the right.

**Transfer:** Use this as a destination invitation, launch announcement or next-step explanation.

### Footer column

**Use:** Shared closing navigation.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 10px`

**Text style:** `column-label` — Matter 500 · 14px/28px · tracking 0.05em · uppercase

**Observed:** Uppercase muted group title above Text destination links. A brand-icon column precedes five destination groups; a secondary group can nest below resources. Copyright and contact sit near the bottom.

**Transfer:** Preserve uneven real-world column lengths and open lower space rather than filling every column.

### Status tag

**Only for:** public planning pages

**Use:** Show state without making the entire card colorful.

**CSS:** `display: flex; align-items: center; height: 24px; gap: 8px; padding: 0px 8px; border: 1px solid #d7d7d6; border-radius: 6px`

**Text style:** `status` — Paper Mono 400 · 13px/28px · tracking 0.014em

**Observed:** An 8px colored circle leads a lowercase mono label. Completed is lime, progress blue, upcoming violet and planned neutral.

**Transfer:** Keep the label explicit so the color is never the only state indicator.

### Archive date

**Only for:** release archives

**Use:** Anchor a new chronological entry.

**CSS:** `color: #181818; text-decoration: none`

**Text style:** `date` — Matter 480 · 24px/32px · tracking 0.005em

**Observed:** Linked date sits 60px below full-width entry artwork, then 24px before the introductory prose.

**States:** Declared: hover text becomes 70% ink; focus-visible 2px blue outline with 2px offset.

### Comparison cell

**Only for:** comparison pages

**Use:** Dense factual differentiation.

**CSS:** `padding: 12px 16px; border-bottom: 1px solid rgba(24,24,24,0.06); color: rgba(24,24,24,0.8); vertical-align: top`

**Text style:** `table-body` — Matter 400 · 16px/1.5 · tracking 0.015em

**Observed:** Three-column comparison with a narrower feature key and two wider descriptions. Keys use Table key, column headers use Table label. Outer columns have 60px edge insets and header rules use 12% ink.

**Transfer:** Compare concrete capabilities with similarly specific language on both sides.

### Shortcut key

**Only for:** technical release notes

**Use:** Inline shortcut hints within prose and nested lists.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #fcfcf9; border-radius: 4px; padding: 0.1px 6.8px 0px; box-shadow: inset 0px -0.7px 0px rgba(0,0,0,0.15), 0px 0px 0px 0.7px rgba(0,0,0,0.12), 0px 1.1px 2.3px rgba(0,0,0,0.2)`

**Text style:** `keycap` — Paper Mono 400 · 13.5px/1.7 · tracking 0.013em

**Observed:** Small raised keyboard-key form with light inset highlights and a slightly darker bottom lip, aligned within the text line.

## Imagery and graphics

### Drafting geometry

**Use:** Signature structure throughout the outer ground and chapter framing.

**Observed:** Very pale solid and dashed construction lines, fine graph-paper triangles, giant circles, diagonal cuts and marginal ruler ticks. Small square handles make page cells resemble selected artboards. Geometry stays behind the text and is often masked by the light paper plane.

**Transfer:** Carry these marks into every new landing page even when the product has no design canvas; they communicate a working document rather than a diagram of the original tool.

**Build:** Layer an SVG with 1px low-opacity ink rules on the cream ground: broad 120px construction intervals, dashed vertical guides, a 10px graph pattern clipped to a 45-degree triangle, and a large outlined circle spanning the 1080px rail. Add repeating short edge ticks, with longer ticks at broad intervals. Put 12px off-white squares with 1px pencil edges at selected grid intersections. Overlay low-contrast monochrome SVG turbulence as paper grain; keep the fine grid near 0.1 opacity and textures soft.

### Working interface scenes

**Use:** Hero object and full-width capability demonstrations.

**Observed:** Broad pale desktop application windows contain real designed content, muted toolbars and side panels. A smaller terminal overlaps the lower left; an occasional compact application dock overlaps the bottom. Product artwork carries a little blue and black-and-white music imagery. The hero window is about 1084px wide and 591px tall; subsequent media fills the rail with small inner margins.

**Transfer:** Show a believable end-to-end task using the new product. If polished media is unavailable, build one carefully populated interface scene with meaningful sample content and an overlapping activity or output window. Retain the light chrome, modest corners and soft window depth, not the source application's controls.

### Tactile paper insert

**Use:** Small destination-panel artwork and editorial update images.

**Observed:** A tiny torn-paper geometric mark contrasts with the fine ruled background. Editorial artwork expands this language into a scalloped, wrinkled paper square, black divisions and muted blue and ochre blocks. Artwork is framed edge-to-edge above the associated text.

**Transfer:** Make an original folded, cut or perforated-paper construction that represents the new product's output. The minimum version is an irregular-edged layered SVG with subtle grain and a small contact shadow.

**Build:** Use two offset cut-paper polygons around a central square aperture; perturb the exposed edge with a short irregular path. Apply a low-opacity multiply noise texture and a 2px to 8px soft shadow. For editorial covers, divide a larger paper rectangle into unequal blocks with thin dark lines; restrict stronger color to the blocks, not the page ground.

### Ghost wordmark imprint

**Use:** Signature footer artwork behind the navigation and contact line.

**Observed:** An enormous outline-only wordmark is nearly the color of the paper, spans beyond both viewport edges and is clipped at the bottom. It behaves like a faint embossed sheet rather than a readable second headline.

**Transfer:** Use the new identity or a short product word as an oversized imprint; preserve the pale contour and monumental crop.

**Build:** Place an SVG text outline or outlined letter paths across a full-width footer, aligned toward the bottom. Use no fill, a 1px stroke in pencil-edge color at very low opacity, and width beyond the viewport. Aim for roughly 400px glyph height at a 1440px viewport; let long words crop horizontally. Keep links above it in normal readable ink.

### Collaborator annotations

**Only for:** public planning pages

**Use:** Humanize a long capability grid.

**Observed:** Small warm cards float across the grid edges beside 25px colored circular markers. Names use the marker color and heavier type; comments are short gray lines. Blue, amber and violet repeat across the page.

**Transfer:** Use authentic short comments on a planning or collaboration page; do not convert them into ordinary marketing-card headers.

**Build:** Place a 25px circle diagonally above-left of a warm 12px-radius card, padded 14px 20px, with a faint 0.5px edge and several low-opacity short shadows. Keep each comment to one or two lines and avoid blocking important reading content.

### Community portrait mosaic

**Only for:** community invitations on public planning pages

**Use:** The human closing invitation.

**Observed:** Text sits upper left while 120px square grayscale portraits and subdued community symbols form an irregular stepped mosaic across the lower right on cream. Images have print-like halftone texture; negative space remains dominant.

**Transfer:** Use original portraits of actual contributors and a few relevant community destinations, arranged as a staircase rather than uniform avatar circles.

### Archive artwork

**Only for:** release archives

**Use:** Entry-opening visual variety.

**Observed:** 840px by 599px covers alternate between interface details, paper compositions, floral imagery and vivid shader demonstrations. Some covers are dark or highly colored while the reading surface stays off-white.

**Transfer:** Let release artwork demonstrate the actual improvement or output. Keep all cover dimensions consistent and place dates and dense notes below rather than over the image.

### Icons

**Observed:** Marketing iconography is sparse: a small brand symbol, a 13px–14px platform glyph inside download actions and plain right arrows on text destinations. The many small editor tools belong within interface scenes, not the marketing navigation.

**Transfer:** Use a small original mark and only functional platform or directional glyphs; do not introduce a colorful icon at the start of every feature.

## Section recipes

How recurring sections are built.

### First screen: Working canvas opening

**Observed:** The 61px Navigation floats above a light paper-textured drafting ground. Within the 1080px rail, a left-aligned 48px Display statement begins with a short dark promise and continues into two gray lines, taking a little over half the rail width. The right side is mostly open, crossed by a pale diagonal construction mask. An 18px support paragraph, no wider than 600px, follows after 18px; Primary button and a plain arrow destination follow after 30px with a 28px horizontal separation. A large Working interface scene starts beneath the copy and fills the rail width. Within the first 900px the full headline, two-line support, both actions and most of the interface window are visible; the window's lower edge continues below the fold. Background geometry sits behind the text, the working window sits above it and the small terminal overlaps the window.

**Transfer:** Replace the promise and task scene with the new product's most convincing workflow, preserving the dark-to-gray headline cadence and the object below rather than beside the text. Without ready-made media, construct one coherent populated interface and output overlay. Planning pages instead open with a two-cell title-and-introduction sheet under a taller geometric margin; comparison pages use a 360px title panel with title near the lower left; release archives open directly with artwork and date.

**Avoid:** Do not center the default hero, put a huge illustration beside a tiny paragraph, or turn the working scene into an empty browser frame.

**Text style:** `display` — Matter 360 · 48px/1 · tracking -0.02em

### Capability heading cell

**Observed:** A full-width Connected paper cell pairs an ordinary Body eyebrow with a two-line Display heading and Body support, separated by 24px gaps. The copy occupies roughly 600px with 40px inner inset. A fine graph-paper triangle decorates the upper-right corner, and a large working scene follows in an adjoining cell.

**Transfer:** Introduce one capability using a casual short label, a concrete benefit and one explanatory sentence.

**Text style:** `display` — Matter 360 · 48px/1 · tracking -0.02em

### Circular promise and closing call

**Observed:** A rail-wide 1080px circle supplies the pale paper field and thin boundary for a centered headline and narrow support. Its upper half introduces a workflow chapter; the lower half provides a closing promise and Primary button. The circle joins the rectangular grid at selection-handle intersections.

**Transfer:** Use the large circular cut as a recurring visual punctuation for a product's central promise or closing invitation; retain the same neutral treatment and working-document boundary.

**Text style:** `display` — Matter 360 · 48px/1 · tracking -0.02em

### Destination and editorial pair

**Observed:** Inset destination card sits within a wider drafting panel with ruler edge and small paper object. An adjoining two-column editorial row places equal-size artwork above compact item headings, muted descriptions and heavier arrow links. The continuous rules and selection handles connect them.

**Transfer:** Use an onward invitation and evidence of current activity relevant to the new product; these need not occupy the same order or count.

**Text style:** `display-card` — Matter 360 · 64px/1 · tracking -0.02em

### Imprinted footer

**Observed:** All page types end on Footer paper with a main sheet shadow above. A 1080px inner rail with 120px top and bottom padding holds a small app mark and Footer columns. The Ghost wordmark imprint fills the lower plane behind a copyright and contact line. The footer is 728px tall rather than a compact legal strip.

**Transfer:** Keep this tactile typographic ending even on short editorial pages; use fewer destinations when appropriate but maintain the imprint and open space.

**Text style:** `column-label` — Matter 500 · 14px/28px · tracking 0.05em · uppercase

### Planning grid

**Only for:** public planning pages

**Observed:** The opening sheet has two equal cells: a large two-line title with small dated caption low on the left and an introduction low on the right. Full-width 240px heading cells alternate with 300px capability cells, occasional tall interface illustrations and status tags. Collaborator annotations drift along grid edges. Near the end an interactive circular keepsake invitation and graphic playground precede the Community portrait mosaic and a warm sign-off.

**Transfer:** Separate capabilities by reader goal, intersperse genuine output demonstrations and finish by inviting feedback rather than applying a generic conversion banner.

**Text style:** `display` — Matter 360 · 48px/1 · tracking -0.02em

### Comparison article

**Only for:** comparison pages

**Observed:** A 360px title panel leads into narrower prose, Article heading sections and a three-column comparison table. Two side-by-side third-party social cards retain their recognizable white backgrounds, 12px corners, fine gray borders and embedded video. Related comparisons appear after the proof, then the shared footer.

**Transfer:** Use plain explanations before a small concrete comparison matrix; keep embedded proof visually distinct rather than making it look like native feature cells.

**Text style:** `article-heading` — Matter 480 · 24px/28px · tracking 0.005em

### Chronological notes

**Only for:** release archives

**Observed:** The Archive rail begins with a full-width cover followed by Archive date and introductory prose. Compact Item heading categories sit 32px above their next block with 16px below the heading. Bullet lists use 36px indentation, 8px between items, nested hollow bullets and occasional Shortcut keys or italic feature names. Subsequent entries repeat cover and date; the oldest entry ends in two short launch paragraphs before the shared footer.

**Transfer:** Let factual details remain dense and readable; use one substantial image per entry rather than tiny cards for every change.

**Text style:** `date` — Matter 480 · 24px/32px · tracking 0.005em

## Page flow

**Storyline:** promise → credible working object → capability explanation and proof → onward invitation or closing action → imprinted navigation footer

### Product landing page with a workflow story

1. **promise** — Dark-to-gray statement, support, action pair and large working scene.
2. **social proof** — Small customer attribution and a centered desktop announcement with compact application object.
3. **capability chapters** — Circular workflow introduction, alternating heading cells, large demonstrations and paired detail cells.
4. **closing call** — Circular summary and download action, then inset onward invitation.
5. **current activity** — Two editorial artwork cards before the full shared footer.

**Transfer:** Choose the demonstrations that substantiate the promise; use the connected-cell grammar without reproducing the original topics or section count.

### Public product planning and community invitation

1. **intent** — Split title-and-introduction sheet on a visible drafting ground.
2. **capability chapters** — Thematic headings, status-bearing cells and tall illustrations with floating human comments.
3. **participation** — Interactive keepsake, graphic demonstration and a warm feedback invitation with portrait mosaic.
4. **orientation** — Shared imprinted footer.

**Transfer:** Organize a live plan by user outcomes and end with a personal invitation to contribute.

### Factual alternative evaluation

1. **framing** — Low-left title in a tall paper panel followed by concise explanatory paragraphs.
2. **differentiation** — Compact section heading and detailed table.
3. **social proof** — Two tall embedded posts with video.
4. **onward navigation** — Related comparison link, open breathing space and shared footer.

**Transfer:** State mechanisms and tradeoffs directly, then provide genuine outside proof and a useful next destination.

### Long chronological product record

1. **current release** — Large editorial cover, linked date and brief introduction.
2. **detailed proof** — New features, technical categories and nested improvements lists.
3. **history** — Repeated artwork-and-date entries continue backward to the original launch note.
4. **orientation** — Short closing launch prose, then shared footer without an added sales CTA.

**Transfer:** Prioritize changelog scanning and consistent media dimensions; preserve factual density and a calm ending.

## Writing

Friendly, design-literate and technically specific. The confidence comes from describing how work gets done, tempered by informal lowercase labels and an evident human team.

**Do not copy:** Do not reuse the Paper name, logo, proprietary artwork, customer roster, funding numbers, original product claims, feature promises or third-party quotations. Examples below demonstrate voice only; replace them with truthful material about the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Use we for the people making the product, especially in invitations and updates; refer to the product by name when explaining its mechanism.
- **Rhythm:** Very short promises, conversational section labels and one- or two-sentence explanations. Marketing headlines and actions often start lowercase; editorial category headings use sentence case. Technical notes are compact verb-led bullets.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Short imperative or benefit followed by a quieter explanatory continuation. | 2–6 words for the dark promise | “design incredible” |
| Section eyebrow | A colloquial friction or a playful shorthand, not a formal category code. | 1–4 words | “good bye lorem ipsum”<br>“anti-slop” |
| Capability headline | A tangible change to working life, using ordinary verbs. | 7–12 words | “hand off boilerplate work, focus on the human touch” |
| Action | Name the action and destination or platform plainly. | 1–4 words | “download for macOS”<br>“view the roadmap” |
| Invitation | Warm direct request, with real openness to feedback. | Short heading plus personal paragraph | “come join the chat”<br>“Take a peek at what's coming and join us in designing the future. We're genuinely excited to hear your ideas.” |
| Release note | Verb first, concrete changed behavior second. | One concise sentence per bullet | “Reduced memory usage to nearly half of previous usage”<br>“Added a color token from any color property panel” |

**Words and phrasing to use:** connect; real; built on; from … to … and back; work; canvas; human touch; join; coming soon; improvements and fixes

**Avoid:** revolutionary; supercharge everything; unleash limitless potential; enterprise-grade excellence; synergy; vague AI magic

**Rules:**

- Tie each benefit to a mechanism or recognizable task.
- Allow a playful label, then ground it in straightforward explanatory prose.
- Retain technical terms when they explain interoperability or capability; do not pile them into the opening promise.
- Use explicit platform or destination names on actions.
- Keep invitations personal and release notes factual.

## Do's and Don'ts

### Do

- Keep major headings at 48px/1 and weight 360 rather than heavy display weights.
- Use 1080px as the alignment rail for navigation, opening and chapter grid.
- Let 1px rules connect square-edged cells with no inter-card gutter.
- Keep support copy at 18px/28px and about 600px wide in the opening.
- Reserve layered shadows for working windows and the lifted sheet edge.
- Use 4px corners and a 40px height for default filled actions.
- Preserve the tiny 12px selection handles and low-contrast drafting marks.
- Give the closing imprint a full-width, cropped scale below readable footer content.

### Don't

- Do not replace warm paper with stark white across the entire canvas; the cream-to-paper distinction is structural.
- Do not apply 12px rounding to marketing panels; that radius belongs to working windows and special embedded or annotation objects.
- Do not convert every 18px eyebrow into uppercase mono text.
- Do not color entire capability cells blue, amber or violet; keep color in small markers and artwork.
- Do not shrink the footer to a single legal row; its large pale wordmark is part of the identity.
- Do not put strong drop shadows beneath every feature cell; shared pencil rules establish the depth there.
- Do not use bright gradients for ordinary headlines; the secondary headline treatment is plain gray.
- Do not promote the colors and typography inside demonstration interfaces into the site's marketing system.

## Motion and responsive

### Motion

**Observed:**

- Default filled actions declare a 0.15s ease transition for colors and transform, with active scale 0.97.
- Text destinations declare opacity transitions of 0.15s ease; navigation background and shadow transition over 0.1s ease.
- Shortcut keys declare translate and box-shadow transitions of 60ms.
- The footer is a fixed underlying plane revealed beneath the clipped main sheet.

**Transfer:**

- Retain the light tactile press on filled actions and the subtle sheet-over-footer depth relationship; keep ordinary content cells visually stationary.

**Unknown:**

- Timing and paths of demonstration scenes, collaborator movement and artwork animations are not established.

### Responsive

**Observed:**

- Desktop composition uses the 1080px rail; declared width thresholds include 480px, 600px, 640px, 700px, 800px, 880px, 900px, 1080px, 1140px and 1600px.
- Markup declares stacked action alignment on narrow layouts, and the archive declares a 362px narrow rail versus 842px desktop. Some large geometry is desktop-only.

**Transfer:**

- As an adaptation, stack paired cells while retaining shared rules, keep the headline's dark-to-gray cadence and scale the main task scene as one coherent object.
- Move intricate ruler geometry away from narrow reading columns; retain a few selection handles and the footer imprint rather than squeezing every desktop detail.

**Unknown:**

- Exact mobile type sizes, navigation behavior and the complete breakpoint-to-layout mapping are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
