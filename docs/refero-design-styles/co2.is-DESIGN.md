# co2.is — civic ink and terrain

## Overview

An editorial, public-minded style that pairs literary serif headlines with clear, regular-weight sans-serif information. Mostly white and airy, it gains energy from icy blue, mint, saturated blue and occasional charcoal chapters. Grainy duotone landscapes and architectural collages make complex information feel tangible, while open lists, understated data bars and oversized navigation keep it approachable. It suits information-rich products and programs that need both a persuasive overview and serious detail pages.

### Essentials

- Literary headlines, administrative detail: use Gt Alpina Standard at 64px/1.08, weight 300 for landing headlines and Abacaxilatinweb at 26px/1.5 for prominent labels; keep both at normal tracking.
- The opening is a statement above a printed landscape, not a sales dashboard: a 670px-wide, left-aligned headline starts after 256px of breathing room, followed by a 64px gap and edge-to-edge duotone artwork.
- Navigation is a set of floating capsules rather than a solid toolbar: a 60px fixed header holds 41px-high dropdown pills with 24px backdrop blur and a 40px segmented switch with a white inset thumb.
- Information behaves like a lightly annotated atlas: two-column chapters use a 0.75fr/1fr split and 64px gutter; labels have raised 18px counts, with 75px-high pale bars and 1px separators instead of heavy chart furniture.
- Color arrives in chapters, not in every sentence: white dominates the reading sections; icy blue and green fill data bars and the closing surface, while a saturated blue art interlude and a charcoal proof chapter interrupt the long light canvas.
- A grainy image field and a spacious index-like ending are signature devices: include a full-width thresholded terrain or material illustration, then preserve the spirit of 44px/1.32 closing links above a small ownership note separated by 224px. Without photography, use noise-masked contour fields rather than polished 3D art.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Field blue | `#4098ff` | `--color-blue` | background, accent, link | Full-width graphic interludes, printed-image ink and small text-link hover color. |
| Icy blue | `#dff9ff` | `--color-ice` | background, surface | Default pale brand field: data bars, duotone image backing and closing navigation band. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Progress green | `#dbffe7` | `--color-green-wash` | surface | Progress-distribution bars; retains the same construction as the icy-blue bars. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Civic ink | `#181b22` | `--color-ink` | text, background, action | Primary text, charcoal chapters, selected navigation and inverted interactive fills. |
| Section divider | `#d9d9d9` | `--color-rule` | border | Thin separators between open data rows and article chapters. |
| Visible capsule grey | `#f4f4f4` | `--color-glass` | surface | Visible navigation wash on white, made with rgba(186,186,186,0.16); retains the underlying chapter color over imagery. |
| Light grey | `#f5f5f5` | `--color-soft` | surface, background | Low-contrast list tiles, anchor controls and card-grid backing; also the editorial-page footer variant. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Default reading canvas, white cards and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| alternate program landing pages | Mint field | `#d3f7f4` | `--color-mint` | background, surface | Alternate program's opening support band and closing field. |
| alternate program landing pages | Program teal | `#00c2b2` | `--color-teal` | background, link, accent | Alternate program's graphic interlude and contextual links, replacing blue rather than adding another general accent. |
| articles and data detail pages | Caption grey | `#636568` | `--color-caption` | text | Explanatory chart captions and secondary editorial labels. |
| data detail pages | Inactive grey | `#8b8d90` | `--color-muted` | text | De-emphasized comparison rows and current-item navigation text. |
| data detail pages | Table hairline | `#c5c6c7` | `--color-table-edge` | border | Half-pixel rules in quantitative comparison tables. |

## Typography

- **Abacaxilatinweb** — Body copy, data, controls, labels and closing links. Open, rounded contemporary sans with a relaxed regular weight and readable figures. If unavailable, use **DM Sans**. Use 400 and 600; retain normal tracking and check line breaks. Font stack: "Abacaxilatinweb", "DM Sans", Arial, sans-serif.
- **Gt Alpina Standard** — Landing headlines, major editorial section titles and selected list titles. Light, literary serif with expressive curves and a substantial lowercase presence, not a high-contrast fashion Didone. If unavailable, use **Source Serif 4**. Use 300; tune width through line breaks rather than condensing. Font stack: "Gt Alpina Standard", "Source Serif 4", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Gt Alpina Standard | 300 | 64px | 1.08 | normal | Default landing headline and major split-column section titles. |
| closing-link | Abacaxilatinweb | 400 | 44px | 1.32 | normal | Large plain links forming the closing index. |
| lead | Abacaxilatinweb | 400 | 26px | 1.5 | normal | Prominent labels, introductory paragraphs and data-bar names. |
| body | Abacaxilatinweb | 400 | 20px | 1.5 | normal | Sustained explanatory paragraphs. |
| support | Abacaxilatinweb | 400 | 20px | 1.35 | normal | Short support lines, anchor labels and comparison values. |
| small | Abacaxilatinweb | 400 | 18px | 1.5 | normal | Raised counts beside large labels and secondary text. |
| control | Abacaxilatinweb | 400 | 16px | 1.32 | normal | Dropdown labels, small chevron links and list identifiers. |
| segment | Abacaxilatinweb | 400 | 16px | 27px | normal | Segmented navigation switch labels. |
| caption | Abacaxilatinweb | 400 | 14px | 1.32 | normal | Small ownership paragraphs and units. |
| caption-strong | Abacaxilatinweb | 600 | 14px | 1.32 | normal | Ownership heading above the closing paragraph. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| articles and data detail pages | article-title | Gt Alpina Standard | 300 | 80px | 1.09 | normal | Single-line detail and editorial page titles. |
| data detail pages | total | Abacaxilatinweb | 400 | 80px | 1.08 | normal | Right-aligned total below a quantitative table. |
| data detail pages | related-heading | Gt Alpina Standard | 300 | 56px | 1.08 | -0.0268em | The related-content heading above a tile list. |
| long-form editorial pages | article-heading | Abacaxilatinweb | 400 | 38px | 1.32 | normal | Editorial article chapter headings. |
| data detail pages | data-heading | Abacaxilatinweb | 400 | 36px | 1.08 | normal | Quantitative section headings. |
| alternate program landing pages | risk-list | Gt Alpina Standard | 300 | 30px | 1.32 | normal | Ruled editorial list titles beside a large section heading. |
| data detail pages | tile-title | Abacaxilatinweb | 400 | 20px | 1.08 | normal | Titles within broad navigation tiles. |

**Notes:**

- Weight stays light or regular even at the top of the hierarchy. Reserve 600 for small emphasis and ownership labels rather than making all headings bold.
- Normal letter spacing is the default at every size; the related-content serif heading is the specific tightened variant.
- Counts rise beside a name like annotations, separated by 4px, rather than becoming a second bold line. Keep figures in the same sans-serif character as the surrounding text.

## Layout

**Density:** Airy: expansive chapter intervals surround relatively compact navigation and information rows.

### Spacing

**Spacing system:**

- **desktop margin** 64px, horizontal — Declared desktop side margin for wide landing sections.
- **tablet margin** 32px, horizontal — Declared intermediate side-margin token.
- **mobile margin** 16px, horizontal — Declared narrow-screen side-margin token.

| Value | Use |
| --- | --- |
| 8px | Closing-link stack and small label-to-chevron gaps. |
| 12px | Navigation-tile stack and footer heading-to-paragraph gap. |
| 16px | Dropdown spacing, small content gaps and data-bar vertical padding. |
| 24px | Data-bar horizontal padding and accordion item spacing. |
| 32px | Heading-to-body gap and list-tile horizontal padding. |
| 64px | Wide content inset, split-column gutter and opening headline-to-art gap. |
| 128px | Detail-page chapter intervals and separation before related content. |
| 192px | Landing information-chapter top padding and detail-page left inset. |
| 224px | Editorial title top space and separation between closing index and ownership. |
| 256px | Landing headline top space. |

### Containers and grids

- **wide container**: max width 1728px · side padding 64px. Wide landing content is centered within this maximum; at 1440px it leaves a 1312px inner field. Artwork bands escape the content inset.
- **split chapter**: 2 columns · gap 64px. Use 0.75fr 1fr tracks, with a large serif heading left and a longer list or proof group right. Rows align at their top.
- **hero text**: max width 670px · side padding 0px. Landing headline occupies about half the desktop content width, leaving the right side intentionally open.
- **card grids**: 3 columns · gap 32px. White editorial cards in a pale-grey field; an alternate program uses two columns. Keep long headings high and linked subitems anchored low.
- **reading column** (only for articles and data detail pages): max width 960px · side padding 0px. Detail and editorial text is left-offset rather than centered on the viewport. At 1440px, outer layout insets are 192px left and 360px right, giving 888px actual reading width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | navigation pills | 9999px (pill) |
|  | data bars and anchors | 8px |
| data detail pages | navigation tiles | 16px |

## Surfaces and depth

### Surfaces

#### White reading canvas · level 0

**Use:** Default background for opening and information chapters.

**CSS:** `background: #ffffff; color: #181b22`

#### Soft grouping field · level 0

**Use:** Back broad card collections without outlines or elevation.

**CSS:** `background: #f5f5f5; box-shadow: none`

**Observed:** White editorial cards are differentiated by fill rather than shadow.

**Transfer:** Group related features on the grey field and keep the cards white.

#### Icy closing field · level 0

**Use:** Default full-width closing navigation surface.

**CSS:** `background: #dff9ff; color: #181b22`

**Observed:** Square outer edges, no border or shadow. The editorial variant uses light grey instead.

**Transfer:** Let the entire ending share a single pale fill.

#### Charcoal proof chapter · level 0

**Use:** A concentrated chapter of explanatory statements and quantitative proof.

**CSS:** `background: #181b22; color: #ffffff`

**Observed:** An uninterrupted dark band, rather than isolated black cards scattered across the page.

**Transfer:** Place a short chapter label over a substantial regular-weight statement; follow it with a rule and proof cards.

#### Capsule glass · level 1

**Use:** Floating navigation shells.

**CSS:** `background: rgba(186, 186, 186, 0.16); backdrop-filter: blur(24px); border-radius: 9999px`

**Observed:** The translucency allows the current background to show through; the header itself has no opaque full-width backing.

**Transfer:** Keep glass confined to controls, not whole content panels.

#### Blue art field · level 0

**Use:** Full-width graphic pause.

**CSS:** `background: #4098ff`

**Observed:** A 657px-high graphic band with dark fine-line terrain marks.

**Transfer:** Use as the backing of the signature field artwork, not an empty decorative rectangle.

#### Alternate mint field · level 0

**Only for:** alternate program landing pages

**Use:** Introductory and closing bands for a second program.

**CSS:** `background: #d3f7f4; color: #181b22`

#### Alternate teal art field · level 0

**Only for:** alternate program landing pages

**Use:** Backing for the architectural collage interlude.

**CSS:** `background: #00c2b2`

**Transfer:** Replace the blue art field with this coherent alternate color system.

## Components

### Floating navigation

**Use:** Persistent access to the main site areas.

**CSS:** `position: fixed; height: 60px; z-index: 99; width: 100%`

**Observed:** A small outline identity and segmented switch sit left; dropdown capsules align right. The internal row has 16px side insets, a 32px gap beside the identity and 16px gaps between dropdowns. No solid toolbar spans behind them.

**Transfer:** Use a compact identity and two top-level modes when the product genuinely has them.

### Dropdown capsule

**Use:** Category navigation.

**CSS:** `display: flex; align-items: center; height: 41px; padding: 10px 16px; background: rgba(186, 186, 186, 0.16); backdrop-filter: blur(24px); border-radius: 9999px; color: #181b22`

**Text style:** `control` — Abacaxilatinweb 400 · 16px/1.32

**Observed:** A small downward chevron precedes the text. The current category on detail pages is ink-filled with white type.

**States:** Declared: hover background-color #181b22 and color white; focus-visible not specified.

### Segmented mode switch

**Use:** Switch between two parallel programs or product modes.

**CSS:** `display: flex; padding: 4px; height: 40px; background: rgba(186, 186, 186, 0.16); backdrop-filter: blur(24px); border-radius: 9999px; overflow: hidden`

**Text style:** `segment` — Abacaxilatinweb 400 · 16px/27px

**Observed:** Two text segments sit over a separately positioned white thumb at 0.8 opacity. Each segment is 32px high with 16px horizontal padding; the thumb follows the active segment.

### Annotated data bar

**Use:** Readable distribution summaries and progress status.

**CSS:** `display: flex; align-items: center; height: 75px; padding: 16px 24px; background: #dff9ff; border-radius: 8px; color: #181b22`

**Text style:** `lead` — Abacaxilatinweb 400 · 26px/1.5

**Observed:** The colored bar length encodes the count while the label remains readable even where it extends beyond a short bar. A raised count follows the label. Bars sit in a ruled right-hand column; the progress variant uses the pale green fill.

**States:** Declared: hover background-color #181b22 and color white; focus-visible not specified.

**Transfer:** Use real proportions and keep text outside the clipping of the fill.

### Open accordion row

**Use:** High-level category summaries.

**CSS:** `display: flex; align-items: center; gap: 16px; padding-right: 3px`

**Text style:** `lead` — Abacaxilatinweb 400 · 26px/1.5

**Observed:** Name and raised count occupy the left; a thin 24px plus sits at the far right. Rows have 24px separation. A small support line and a thin rule introduce the group.

**Transfer:** Use for a small set of meaningful categories; preserve the airy open-list treatment rather than boxing each item.

### Chevron text link

**Use:** Quiet onward navigation below an information group.

**CSS:** `display: flex; align-items: center; gap: 8px; height: 32px; color: #181b22; text-decoration: none`

**Text style:** `control` — Abacaxilatinweb 400 · 16px/1.32

**Observed:** Plain text followed by a narrow right chevron, without a filled button shell.

**States:** Declared: hover color #4098ff and text-decoration none; focus-visible not specified.

### Closing index link

**Use:** The principal links at the page ending.

**CSS:** `color: #181b22; text-decoration: none`

**Text style:** `closing-link` — Abacaxilatinweb 400 · 44px/1.32

**Observed:** Three or four large links stack left with 8px gaps, not a multi-column sitemap. Small ownership copy and monochrome partner identities occupy the lower row.

**States:** Declared: hover text-decoration underline; focus-visible not specified.

### Chapter anchor

**Only for:** long-form editorial pages

**Use:** Jump links below the article title.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 0px 24px; background: #f5f5f5; border-radius: 8px; color: #181b22`

**Text style:** `support` — Abacaxilatinweb 400 · 20px/1.35

**Observed:** A small down-arrow lead-in introduces a wrapping group with 12px horizontal and vertical spacing.

**States:** Declared: hover background-color #181b22 and color white; focus-visible not specified.

### Navigation tile

**Only for:** data detail pages

**Use:** Subcategories and related pages.

**CSS:** `display: flex; gap: 32px; padding: 0px 32px; height: 76px; background: #f5f5f5; border-radius: 16px`

**Text style:** `tile-title` — Abacaxilatinweb 400 · 20px/1.08

**Observed:** A small identifier comes first, then a vertically centered title. Tiles stack with 12px gaps. The current item is de-emphasized rather than turned into a bright selected card.

**Transfer:** Use short stable identifiers only if the new product has a real taxonomy.

### Comparison table row

**Only for:** data detail pages

**Use:** Quantified breakdowns.

**CSS:** `display: flex; align-items: flex-start; gap: 16px; padding: 8px 0px 32px; border-top: 0.5px solid #c5c6c7`

**Text style:** `support` — Abacaxilatinweb 400 · 20px/1.35

**Observed:** Percentage at left, name in the flexible middle, numeric amount right with smaller units. The focused row uses the icy-blue field and ink; other rows can be muted. A plain total label sits opposite an 80px total below the table.

**Transfer:** Retain the open baseline structure and unit labels, not a dense spreadsheet grid.

## Imagery and graphics

### Printed terrain field

**Use:** Signature opening artwork and a full-width graphic pause within landing pages.

**Observed:** Blue and icy-blue grain forms a high-contrast aerial or geological field, with branching masses, erosion-like voids and dense speckling. The opening image spans the entire viewport width below the white headline zone, with no frame, rounding, caption or UI mockup. The later blue band converts the motif into fine dark squiggles over flat blue.

**Transfer:** Use a close-up material, aerial image or process texture related to the new product. If no suitable photography exists, generate an abstract contour field with irregular clustered lines; keep it tactile, flat and two-tone.

**Build:** Create an SVG with a 1440px-wide viewBox. Use 4–6 overlapping irregular contour masses, broad empty channels and a fine fractal-noise mask to break their edges. Map the two tones to #4098ff and #dff9ff using a duotone transfer. For the interlude, use #4098ff as the solid base and thousands of short 1px ink paths at about 0.4 opacity, clustered along the same contours. Extend the field beyond both viewport edges; avoid blur and glossy lighting.

### Category picture tiles

**Use:** Visual routes into broad themes after explanatory content.

**Observed:** Two wide rounded tiles sit side by side, with a short title and small outlined pill action above a large printed picture. A bright yellow field contrasts with a grey landscape tile. The alternate-program grid uses pink, lavender, mint-green and yellow tints across four categories.

**Transfer:** Choose a concise category palette for the grid and reuse the grainy duotone treatment. These colors belong to the category system, not to ordinary body text or every button.

**Build:** Place title and action in a solid-tint header above a photo carrying the same tint through a two-color map. Clip both into a shared rounded rectangle. Use a grain mask to interrupt the photographic midtones; keep header text crisp and untextured.

### Architectural grain collage

**Only for:** alternate program landing pages

**Use:** Alternate hero, tall visual interlude and category imagery.

**Observed:** Buildings, structural lines and window grids are cut into displaced rectangular strips and granular patches. Pale mint and teal flatten the photography into a printed collage; the field fills the available width and extends below the opening fold.

**Transfer:** Use product-related environments or workspaces, not generic smiling portraits. The minimum equivalent is one strong structural photograph rearranged into staggered blocks and duotoned.

**Build:** Layer a grayscale photograph under an SVG rectangular mask made of staggered strips 80–240px wide. Offset duplicate strips horizontally, overlay a thresholded fine-noise mask, and map dark and light to teal and mint. Preserve some recognizable structural diagonals without restoring natural photographic color.

### Explanatory charts

**Only for:** data detail pages

**Use:** Historical series and projected outcomes within the reading column.

**Observed:** Charts sit directly on white, roughly 888px wide and 463–480px high. Fine pale gridlines, slender bars, restrained colored series and small grey units allow the data to remain primary. A grey caption sits 32px beneath the graphic.

**Transfer:** Use real data with explicit time periods, baselines and units. Match the lightweight plotting style and avoid decorative dashboard framing.

### Icons

**Observed:** Simple square-ended outline marks: 24px plus icons with 1.7px strokes, narrow right chevrons with 2px strokes, and small downward navigation chevrons. Ink is the default, with white in inverted states and grey in editorial helpers.

**Transfer:** Use SVG line icons with square caps and minimal geometry. Align them to label baselines or far row edges; do not substitute filled multicolor icon badges.

## Section recipes

How recurring sections are built.

### First screen: Statement over printed field

**Observed:** A white 900px opening sits beneath Floating navigation. The fixed header occupies 60px but has no solid full-width background. A 64px serif headline begins after 256px of top space, inset 64px, spans at most 670px and wraps into three lines with a deliberately empty right half. A 64px gap separates it from the edge-to-edge Printed terrain field, which begins around 527px and fills the remaining 374px of the first screen. Layers are white canvas, the image band, headline, then floating controls. No support paragraph or conversion button appears in this opening; navigation is the only action layer. Explanatory prose and cards begin below the first 900px.

**Transfer:** For a new landing page, make a specific outcome statement of comparable visual length and pair it with a full-width tactile material field. Without source photography, build the contour-field equivalent. Editorial pages instead open with an 80px serif title in the offset reading column and Chapter anchors; data pages open with an 80px serif title low within a 448px pale image banner, followed by a 26px introduction.

**Avoid:** Do not center the headline, add a right-hand app screenshot or install a pair of oversized conversion buttons over the artwork.

**Text style:** `display` — Gt Alpina Standard 300 · 64px/1.08

### Split-column information chapter

**Observed:** The wide container uses a 0.75fr/1fr split with 64px gutter and 192px top padding. A display-size serif heading anchors the left; support, Open accordion row or Annotated data bar groups sit right. Hairlines and raised counts carry the visual organization.

**Transfer:** Pair a concise chapter title with a category breakdown, usage distribution or operational summary. Let the right column determine the chapter height.

**Text style:** `display` — Gt Alpina Standard 300 · 64px/1.08

### Editorial feature cards

**Observed:** A pale-grey grouping field holds tall white cards in three columns, with serif titles, concise sans-serif descriptions and small category pills above them. Linked subitems sit near the card bottoms behind fine rules, each ending in a chevron. The alternate program uses a two-column grid of shorter cards with a small identifier and category tag.

**Transfer:** Group product capabilities into meaningful editorial stories rather than evenly sized icon-and-title feature boxes. Keep bottom links aligned even when descriptions differ.

### Graphic pause

**Observed:** Blue art field spans the full width for 657px with Printed terrain field fine-line artwork and no text. The alternate program uses a taller teal architectural collage.

**Transfer:** Include a tactile art interval between dense information chapters, scaled to the pace of the new page.

### Dark proof chapter

**Observed:** Charcoal proof chapter contrasts with the long white sections. A small chapter label leads a substantial white sans-serif statement; a long thin rule introduces a three-card proof group below. Alternate-program cards emphasize large counts with descriptions above them.

**Transfer:** Use the dark chapter to concentrate an important explanation and the strongest supporting numbers. Keep it typographic rather than turning it into another illustrated hero.

### Offset article chapters

**Observed:** An 888px reading field sits 192px from the left at desktop. The editorial opening uses an 80px serif title at 224px top space, then Chapter anchors. Content uses 38px sans-serif headings, 26px introductions, 20px/1.5 body copy and 32px internal gaps. Thin rules and 128px chapter spacing create separation.

**Transfer:** Use for a detailed methodology, policy or technical explanation. Preserve the distinction between an introductory lead and sustained body text.

**Text style:** `article-heading` — Abacaxilatinweb 400 · 38px/1.32

### Data detail and related routes

**Observed:** A 448px full-width pale terrain banner puts a serif title low in the field with a smaller taxonomy code at its left. The offset reading column then introduces the topic, lists Navigation tiles, presents Comparison table row groups and a large total, and shows an explanatory chart. A related-content area uses the tightened 56px serif heading and another tile stack before the closing field.

**Transfer:** Use for a product category or deep capability page: definition, drill-down routes, measurable comparison, trend and adjacent routes. A system-level page places the route list before its data and chart.

**Text style:** `article-title` — Gt Alpina Standard 300 · 80px/1.09

### Pale closing index

**Observed:** Icy closing field spans the width for 694px, with 64px insets. Closing index links stack at top left. After 224px of separation, a 14px semibold ownership label and a 14px paragraph occupy a narrow lower-left area; small monochrome identities align lower right. Editorial pages use grey; the alternate program uses mint and three links within a 628px band.

**Transfer:** End with a concise navigational index and a real ownership or trust note, keeping the scale contrast between large links and tiny attribution.

### Scope note and word strip

**Only for:** alternate program landing pages

**Observed:** A mint chapter uses a small label and several readable sans-serif paragraphs about the program's wider effects. Below, oversized serif words sit in dark desaturated rounded blocks on one horizontal strip that runs beyond the viewport.

**Transfer:** Use as an editorial scope statement with a few key nouns from the new product's ecosystem. Keep the word strip a graphic device rather than a second navigation menu.

## Page flow

**Storyline:** Statement → context and priorities → structured breakdown → graphic pause → concentrated proof → thematic routes → implications → spacious closing index.

### Broad marketing overview with multiple ways into detailed information

1. **Promise** — Left-aligned serif statement above the printed terrain band.
2. **Context and priorities** — Large explanatory paragraphs and a grey-backed editorial card collection.
3. **Structured proof** — Split-column category list followed by annotated distribution bars.
4. **Visual reset** — Full-width blue fine-line art band.
5. **Quantified rationale** — Dark explanatory chapter with proof cards.
6. **Capability routes** — White explanatory chapter and two large image tiles.
7. **Implications and onward navigation** — A pale supporting statement leads toward the large closing-link index and ownership row.

**Transfer:** Use the overview to connect a broad promise to an organized body of real detail, without making the exact sequence or number of chapters fixed.

### Long-form strategy or methodology explanation

1. **Orientation** — Large serif title and a wrapping group of chapter anchors.
2. **Definition** — Sans-serif chapter heading, prominent lead and explanatory body.
3. **Commitments** — Ruled chapters with specific objectives, timeframes and occasional bullets.
4. **Long-term context** — Final substantial explanation in the same reading column.
5. **Onward navigation** — Grey closing index and small ownership row.

**Transfer:** Let anchors and typographic hierarchy carry a long explanation instead of introducing unrelated promotional graphics.

### Single-category quantitative detail

1. **Identification** — Pale illustrated banner with taxonomy code and large serif title.
2. **Definition and drill-down** — Large introductory paragraph and two navigation tiles.
3. **Comparison** — Ruled quantitative rows, one pale highlighted row and an oversized right-aligned total.
4. **Outcome explanation** — Chart, grey caption and a concise interpretation.
5. **Adjacent routes** — Serif related-content heading and stacked tiles.
6. **Onward navigation** — Icy closing index with ownership.

**Transfer:** Use for a focused capability, pairing a clear definition with real comparative evidence and related routes.

### System-level overview connecting subcategories to aggregate data

1. **Identification** — Illustrated banner and serif title.
2. **Context** — Update label, introduction and a supporting explanatory paragraph.
3. **Drill-down navigation** — Sans-serif heading and a broad stacked tile list.
4. **Aggregate proof** — Comparison rows and a large total.
5. **Trend** — Historical and projected chart with explanatory introduction.
6. **Onward navigation** — Icy closing index with ownership.

**Transfer:** Prefer a directory-first structure when users need to choose a subcategory before inspecting aggregate evidence.

### Parallel program landing page with a distinct visual family

1. **Promise** — Serif headline above mint architectural grain collage.
2. **Context** — Mint introductory band and white vision statement.
3. **Problem framing** — Large serif title and support beside a ruled serif list.
4. **Priorities** — Grey-backed two-column editorial card grid and broad onward link.
5. **Visual reset** — Tall full-width teal collage.
6. **Progress proof** — Dark chapter with three large count cards.
7. **Capability routes** — Four tinted image tiles in two columns.
8. **Scope and onward navigation** — Mint explanatory text, oversized word strip and mint closing index.

**Transfer:** Use a parallel tint family only for a genuinely separate product mode; keep the typography, information rhythm and closing construction continuous.

## Writing

Measured, factual and institutionally confident, with a strong explanatory impulse. Urgency comes from concrete consequences and quantified plans rather than sales enthusiasm.

**Do not copy:** Do not reuse co2.is identities, government insignia, program names, climate claims, targets, figures, dates or source quotations as claims for a different product. Examples below illustrate language structure only.

- **Addressing the reader:** Predominantly impersonal or third-person institutional voice. The organization and program are named as responsible actors; direct second-person persuasion is rare.
- **Rhythm:** Headlines name an outcome or a topic, from a short noun phrase to a multi-line statement. Supporting paragraphs can be substantial, but navigation labels stay short and literal. Sentence case throughout; no exclamation-driven pitch.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Name the action and intended outcome without a slogan or a superlative. | 6–12 words | “Aðgerðir til samdráttar í losun og aukinnar kolefnisbindingar”<br>“Áætlun vegna áhrifa loftslagsbreytinga” |
| Section heading | A short noun phrase describes what the following information organizes. | 2–5 words | “Skipting aðgerða”<br>“Staða aðgerða” |
| Support line | Explain the structure or interpretation in a direct declarative sentence. | One sentence | “Aðgerðirnar skiptast upp í fjögur kerfi”<br>“Áætluð þróun í málaflokknum til 2030.” |
| Navigation action | Literal destination or a brief verb-led invitation to see more. | 1–4 words | “Sjá allar aðgerðir”<br>“Sjá einnig”<br>“Markmið og stefna” |

**Words and phrasing to use:** plan; status; responsibility; implementation; estimated development; scope; objectives; see all

**Avoid:** game-changing; revolutionary; unlock your potential; effortless magic; limited-time urgency

**Rules:**

- Explain an acronym at first meaningful use, then use the short form consistently.
- Attach dates, baselines and units to quantitative claims.
- Distinguish planned outcomes from achieved results through explicit wording.
- Keep navigation descriptive enough to work without promotional supporting copy.

## Do's and Don'ts

### Do

- Keep landing headlines at 64px/1.08 and weight 300, with a 670px maximum text width.
- Preserve the 64px wide-content inset and gutter at desktop.
- Use 192px chapter top space to make structured information feel like editorial chapters.
- Attach 18px raised counts to 26px labels with a 4px separation.
- Use pale 75px bars with 8px corners for readable distribution proof.
- Retain 24px backdrop blur on translucent navigation capsules.
- Let 44px closing links and 14px ownership copy form a deliberate scale contrast.
- Stage the grainy full-width artwork independently from text so the printed texture stays legible.

### Don't

- Do not replace the literary serif hierarchy with bold geometric sans-serif headlines.
- Do not apply negative tracking globally; normal is the default even at 80px.
- Do not turn the whole page into a dark interface: charcoal belongs to a concentrated proof chapter.
- Do not use card shadows as the main separation mechanism; the surfaces are flat.
- Do not round the full-width image bands like floating media cards.
- Do not clip long labels to the lengths of short proportional bars.
- Do not turn 76px navigation tiles into compact spreadsheet rows.
- Do not spread bright category colors through paragraphs, standard navigation and every page background.

## Motion and responsive

### Motion

**Observed:**

- Dropdown capsules declare a 0.3s cubic-bezier(0.19, 1, 0.22, 1) transition; hover inverts their ink and fill.
- Annotated data bars declare width 200ms cubic-bezier(0.645, 0.045, 0.355, 1).
- The segmented thumb declares transform 0.2s cubic-bezier(0.455, 0.03, 0.515, 0.955).
- Closing links declare 0.2s ease-in-out; chapter anchors declare 0.4s cubic-bezier(0.19, 1, 0.22, 1).

**Transfer:**

- Keep motion attached to the capsule, thumb and proportional-bar mechanics. Preserve the flat printed character of artwork rather than adding 3D camera moves.

**Unknown:**

- Exact scroll-driven art behavior, opening animation timing and expanded-menu choreography are unspecified.

### Responsive

**Observed:**

- Side-margin tokens are 64px desktop, 32px tablet and 16px mobile.
- Styles declare width thresholds around 479/480px, 767/768px, 991/992px, 1075/1076px and 1196px; the main landing also declares 1280px.

**Transfer:**

- Recommended adaptation: reduce side insets through the declared margin tokens and stack the split chapters with title before proof on narrow screens.
- Keep the printed image band full bleed while allowing the text column to shrink. Preserve raised counts and readable labels even when proportional bars become short.
- Recommended adaptation: stack category tiles and simplify the capsule navigation without replacing the light header with a heavy solid bar.

**Unknown:**

- Exact narrow-screen typography, mobile menu construction and breakpoint-to-layout mapping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
