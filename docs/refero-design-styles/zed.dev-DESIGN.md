# Zed — a ruled workbench

## Overview

An editorial, technical style that feels like a working instrument rather than a glossy software advertisement. Pale paper, cobalt blue, fine construction lines and lightly textured surfaces surround modest serif headings and typewriter-like body text. Product interfaces provide the visual weight, while compact controls and a saturated closing field give long pages a firm rhythm. It suits tools and infrastructure products with real workflows to explain.

### Essentials

- Headlines behave like editorial titles, not billboards: regular plexSerif at 32px/1.2 for the opening and 25.6px/1.25 for sections, with normal tracking and cobalt reserved for the main promise.
- The opening is a shallow technical stage: a 57px navigation bar above a 350px centered hero, a 550px support line, paired 36px actions and faint scattered numeric marks; the first product chapter is already visible in the first 900px.
- The page is drawn like an engineering sheet: a 1120px visible content frame at desktop, 1px #dadde2 rules, dashed extensions and tiny outlined diamond nodes at intersections. Carry this construction-line device through every new landing page.
- Controls feel pressed rather than inflated: 4px corners, 14px/20px type, 6px icon gaps and a 2px inset lower edge on the blue primary button; secondary actions are translucent white.
- Color is concentrated, not spread evenly: nearly all reading sections remain pale #f4f4f2 with dark ink, blue links and faint cool washes; the closing footer becomes a full-width cobalt field, 632px tall, with fine white rules and diagonal hatching.
- Real work is the main illustration: dark interface panels sit within near-square-cornered light frames, fine grids and muted cool or greenish edge light. Use a credible task-oriented interface illustration when no finished product interface exists.
- Proof is formatted as working material: ruled quote matrices, a 6px hard-offset pale-blue highlight, compact uppercase mono labels at 11px with 0.05em tracking, and small inline statistics rather than giant vanity numerals.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Instrument blue | `#1348dc` | `--color-blue` | action, link, text, background | Primary actions, opening and closing titles, fine accents and the full closing field. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool paper wash | `#edf2f8` | `--color-blue-wash` | surface | Soft blue tint fading into paper around the opening; a low-opacity cool gradient, not a solid colored hero. |
| Control highlight | `#e6effe` | `--color-control-light` | border | Small outer light edge of the primary action. |
| Control lower edge | `#053794` | `--color-control-dark` | border | Inset lower edge of the primary action. |
| Pressed blue | `#0640ac` | `--color-hover-blue` | action | Primary action hover background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Primary action text, footer headings and translucent control fills. |
| Raised paper | `#fbfbfa` | `--color-panel-white` | surface | Visible translucent white proof panel; built with white at 60% over pale paper. |
| Paper | `#f4f4f2` | `--color-canvas` | background, surface | Default light paper appearance and navigation background. |
| Footer silver | `#e1e3e7` | `--color-footer-text` | text | Links on the blue closing field. |
| Construction rule | `#dadde2` | `--color-rule` | border | Section outlines, column dividers and fine technical grids. |
| Control edge | `#bdc1c9` | `--color-edge` | border | Secondary controls at 50% opacity and outlined product objects. |
| Secondary ink | `#5c636f` | `--color-muted` | text | Supporting pricing units and small utility information. |
| Body ink | `#393d45` | `--color-ink` | text | Main paragraphs and interface-like labels. |
| Heading black | `#000000` | `--color-heading` | text | Interior section titles and secondary action labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| compact multi-product directories | Rose paper | `#eee7e7` | `--color-portal-paper` | background | Warm pink-gray alternative to the core paper canvas. |
| compact multi-product directories | Second-product red | `#bf3c27` | `--color-portal-red` | action, accent | A second product identity alongside blue, confined to its emblem and action. |

## Typography

- **plexSerif** — Titles, small card headings, prices and footer headings. Literary serif with restrained contrast and slightly sturdy shapes, mostly regular rather than bold. If unavailable, use **IBM Plex Serif**. Use regular cuts around 400; retain the modest title scale. Font stack: "plexSerif", "IBM Plex Serif", Georgia, serif.
- **writer** — Paragraphs, navigation, controls, quotations and supporting labels. Typewriter-like text face with open spacing, mechanical texture and a practical editorial tone. If unavailable, use **iA Writer Quattro**. Use regular and italic; preserve the compact sizes and slightly tightened lead copy. Font stack: "writer", "iA Writer Quattro", ui-monospace, monospace.
- **zedMono** — Technical section labels. Compact technical monospace with spaced uppercase labels. If unavailable, use **IBM Plex Mono**. Font stack: "zedMono", "IBM Plex Mono", ui-monospace, monospace.
- **ui-monospace** — Plan names and utility key hints. Small conventional system monospace. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | plexSerif | 390 | 32px | 1.2 | normal | size clamp(1.7rem, 1.5rem + 1.85vw, 2rem) | Centered main promise; also the primary title of editorial company pages. |
| heading | plexSerif | 390 | 25.6px | 1.25 | normal | size clamp(1.4rem, 1.5rem + 1.55vw, 1.6rem) | Section headings and the closing conversion title. |
| body | writer | 400 | 16px | 1.5 | -0.025em | fixed | Opening support and feature section introductions. |
| footer-heading | plexSerif | 400 | 15.2px | 1.1 | normal | size clamp(0.875rem, 0.8rem + 0.35vw, 0.95rem) | Column titles and company identification on the closing field. |
| card-title | plexSerif | 400 | 15px | 1.5 | normal | fixed | Small capability and resource cell headings. |
| control | writer | 400 | 14px | 20px | -0.025em | fixed | Buttons, navigation and compact quotations. |
| link | writer | 400 | 14px | 20px | normal | fixed | Text links, resource lines and collapsed capability labels. |
| inline-stat | writer | 400 | 14px | 20px | normal, uppercase | fixed | Small numbers paired with activity labels in ruled cells. |
| small-body | writer | 400 | 13px | 1.5 | normal | fixed | Capability cell explanations and resource summaries. |
| eyebrow | zedMono | 400 | 11px | 1.5 | 0.05em, uppercase | fixed | Technical category labels above section titles. |
| caption | writer | 400 | 11px | 1.5 | normal | fixed | Quote author credentials and small metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | plexSerif | 400 | 30px | 1.2 | -0.025em | fixed | Plan price, blue and aligned with a much smaller billing unit. |
| pricing pages | pricing-display | plexSerif | 390 | 28px | 1.2 | normal | size clamp(1.5rem, 1.5rem + 1.65vw, 1.75rem) | Short centered pricing introduction. |
| pricing pages | question | plexSerif | 380 | 21.6px | 1.3 | 0.005em | fixed | Question headings and a compact business conversion banner. |
| compact multi-product directories | directory-title | plexSerif | 410 | 18.4px | 1.2 | normal | size clamp(1.125rem, 0.9rem + 0.75vw, 1.15rem) | Product names next to square product emblems. |
| editorial and pricing pages | reading-body | writer | 400 | 16px | 26px | normal | fixed | Long-form explanatory paragraphs and answers. |
| pricing pages | plan-label | ui-monospace | 400 | 13px | 1.5 | 0.025em, uppercase | fixed | Plan names and trial indicator. |
| compact multi-product directories | directory-summary | writer | 400 italic | 13px | 1.5 | normal | fixed | Short product descriptions beneath directory titles. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the serif/small mechanical-text contrast: do not turn the title system into bold sans-serif display type.
- The default title is only twice the body size. Headings use normal tracking; tighter tracking belongs to lead copy, controls and prices.
- Small statistics remain 14px and sit alongside uppercase labels. Their contrast comes from ruled layout rather than numerical scale.

## Layout

**Density:** Comfortable section framing around compact working content; the typography and controls stay small even when the media panels are broad.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-label gap in controls and hard-offset proof shadows. |
| 8px | Heading-to-support gap and distance between paired actions. |
| 12px | Footer link list gaps and spacing below FAQ headings. |
| 16px | Small cell padding and stacked content gaps. |
| 24px | Plan card padding and footer vertical padding. |
| 28px | Opening copy group to action group. |
| 32px | Quote matrix separation from its heading and spacing between questions. |
| 40px | Capability cell vertical padding. |
| 48px | Default desktop section and chapter header inset. |
| 72px | Opening stage vertical padding. |

### Containers and grids

- **Technical frame**: max width 1120px · side padding 48px. Visible desktop content span, centered with 160px outer margins at a 1440px window. Thin vertical rails align all major sections; the CSS container uses a 1080px max-width token with box-model context.
- **Opening copy**: max width 550px · side padding 32px. Centered support copy, usually two lines beneath a single-line title.
- **Capability grid**: 3 columns · gap 0px. Contiguous cells separated by rules, not floating cards.
- **Quote matrix**: max width 1024px · 3 columns · gap 0px. Two rows of compact quotations within the inset content frame.
- **Plan grid** (only for pricing pages): max width 1100px · 3 columns · gap 32px. Three equal-width plan panels; 320px wide at desktop.
- **Reading column** (only for pricing pages): max width 768px · side padding 48px. 672px readable text area centered inside the technical frame.
- **Editorial split** (only for editorial company pages): max width 1120px · 2 columns · gap 0px. 224px left navigation rail with a right reading area containing a 720px text column.
- **Directory frame** (only for compact multi-product directories): max width 1024px · side padding 16px. Compact ruled page without the full marketing navigation.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Controls and proof panels | 4px |
|  | Media frames | 2px |
|  | Product emblem face | 32px |
|  | Product emblem rim | 40px |
| compact multi-product directories | Directory interface | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Primary lower edge | `inset 0px -2px 0px 0px #053794, 0px 1px 3px 0px #e6effe` | Blue conversion controls. |
| Secondary lower edge | `inset 0px -2px 0px 0px rgba(111,123,144,0.1)` | Pale secondary controls. |
| Proof offset | `6px 6px 0px 0px rgba(7,77,207,0.04)` | Metrics panel; emphasized quotations reverse the offset to -6px -6px with alpha 0.06. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f4f4f2`

**Observed:** Subtle neutral grain covers the paper rather than a perfectly flat digital white.

**Transfer:** Add a seamless neutral noise overlay at opacity 0.03, repeating at 180px, below all content.

#### Cool opening wash · level 0

**Use:** A gentle atmosphere within the opening frame.

**CSS:** `background: linear-gradient(to bottom, rgba(219,234,254,0.3) 0%, rgba(0,0,0,0) 100%)`

**Observed:** The pale cool tint dissolves into the paper, leaving the centered copy crisp.

**Transfer:** Use a faint cool wash rather than a vivid gradient background.

#### Ruled cell · level 0

**Use:** Chapter headers, features, resource rows and proof matrices.

**CSS:** `border-bottom: 1px solid #dadde2`

**Observed:** Adjacent cells share borders; some columns add a right rule. No raised-card silhouette is needed.

**Transfer:** Treat sections as subdivisions of one continuous document.

#### Proof paper · level 1

**Use:** A quantitative proof panel.

**CSS:** `background: rgba(255,255,255,0.6); border: 1px solid #dadde2; border-radius: 4px; box-shadow: 6px 6px 0px 0px rgba(7,77,207,0.04)`

**Observed:** A lightly raised white sheet with a hard, almost printed offset edge.

**Transfer:** Use for one important chart or similarly concrete proof artifact.

#### Cobalt closing field · level 0

**Use:** The full-width ending of the default marketing page.

**CSS:** `background: #1348dc; color: #e1e3e7`

**Observed:** Column rules become white at 10% opacity; lower hatching and grain retain the drafting-sheet character.

**Transfer:** Concentrate the strongest color here rather than tinting every preceding section.

#### Directory paper · level 0

**Only for:** compact multi-product directories

**Use:** Alternative condensed directory treatment.

**CSS:** `background: #eee7e7`

**Observed:** Rose-gray paper, a continuous thin frame and tightly stacked product strips.

**Transfer:** Use for a small product family or organization index, not the default full landing page.

## Components

### Sticky navigation

**Use:** Compact global orientation and conversion.

**CSS:** `height: 57px; position: sticky; top: 0px; background: #f4f4f2; border-bottom: 1px solid #dadde2; z-index: 100`

**Text style:** `control` — writer 400 · 14px/20px · tracking -0.025em

**Observed:** Small wordmark at left, text destinations and two dropdown labels, then utility search, sign-up and a blue action at right. Key hints are tiny bordered squares; navigation actions are 32px tall.

**States:** Declared: hover pale neutral fill on navigation actions; focus-visible 3px rgba(9,78,206,0.5) outline with 2px offset; active scale 0.99.

**Transfer:** Keep the navigation compact enough to preserve the shallow opening stage.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; height: 36px; padding: 0px 6px 0px 10px; border: 1px solid transparent; border-radius: 4px; background: #1348dc; color: #ffffff; box-shadow: inset 0px -2px 0px 0px #053794, 0px 1px 3px 0px #e6effe`

**Text style:** `control` — writer 400 · 14px/20px · tracking -0.025em

**Observed:** A small leading action icon and a trailing boxed single-letter hint bracket the label. Header variant is 32px high; plan actions stretch to the inner card width.

**States:** Declared: hover background #0640ac and box-shadow none; focus-visible 3px rgba(9,78,206,0.5) outline with 2px offset; active scale 0.99 and box-shadow none.

### Secondary button

**Use:** Alternate conversion or deeper capability action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; height: 36px; padding: 0px 6px 0px 10px; border: 1px solid rgba(189,193,201,0.5); border-radius: 4px; background: rgba(255,255,255,0.5); color: #000000; box-shadow: inset 0px -2px 0px 0px rgba(111,123,144,0.1)`

**Text style:** `control` — writer 400 · 14px/20px · tracking -0.025em

**Observed:** Pairs horizontally with the Primary button at an 8px gap. Alternate chapter links use a trailing chevron instead of a boxed shortcut.

**States:** Declared: hover pale neutral fill and box-shadow none; focus-visible 3px rgba(9,78,206,0.5) outline with 2px offset; active scale 0.99.

### Editorial text link

**Use:** Read-more links and light inline calls to action.

**CSS:** `color: #1348dc; text-decoration-line: underline; text-decoration-color: rgba(19,72,220,0.2)`

**Text style:** `link` — writer 400 · 14px/20px

**Observed:** Usually a short action phrase ending in a text arrow, with no filled surface.

**States:** Declared: hover underline color at 80% blue; focus-visible 3px rgba(9,78,206,0.5) outline with 2px offset.

### Capability selector row

**Use:** Switch between related product demonstrations.

**CSS:** `display: flex; flex-direction: column; padding: 12px 48px; gap: 12px; border-bottom: 1px solid #dadde2; text-align: left`

**Text style:** `link` — writer 400 · 14px/20px

**Observed:** Collapsed rows are about 45px tall with a small plus. The expanded row replaces the compact label with a serif title, a paragraph and an Editorial text link, opposite a large demonstration.

**Transfer:** Keep the active explanation visible and substantial; inactive choices remain slim ruled rows.

### Highlighted quotation

**Use:** Make one authentic proof statement stand out within a matrix.

**CSS:** `display: flex; flex-direction: column; padding: 16px; gap: 32px; border: 1px solid rgba(190,219,255,0.8); border-radius: 2px 2px 0px 2px; background: linear-gradient(to bottom, rgba(190,219,255,0.05), rgba(239,246,255,0.1)); box-shadow: -6px -6px 0px 0px rgba(7,77,207,0.06)`

**Text style:** `control` — writer 400 · 14px/20px · tracking -0.025em

**Observed:** A compact quote above a bottom-aligned 32px portrait, serif author name and small credential. Other quotes are plain cells sharing hairline separators; selected phrases can have a pale blue text highlight.

**Transfer:** Use the offset treatment on one cell rather than converting the entire matrix into elevated cards.

### Metrics sheet

**Use:** Quantitative product proof.

**CSS:** `padding: 10px 10px 0px; margin: 48px; background: rgba(255,255,255,0.6); border: 1px solid #dadde2; border-radius: 4px; box-shadow: 6px 6px 0px 0px rgba(7,77,207,0.04)`

**Observed:** A broad 1024px sheet contains small range selectors at the upper right, fine chart gridlines, restrained colored lines and a tiny centered legend. It is a working chart, not an infographic poster.

**Transfer:** Substitute meaningful evidence with clearly labelled axes and similarly restrained visual weight.

### Footer column

**Use:** Dense yet orderly destination lists on the closing field.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 24px 16px; border-right: 1px solid rgba(255,255,255,0.1)`

**Text style:** `footer-heading` — plexSerif 400 · 15.2px/1.1

**Observed:** Four destination columns follow a company/legal area spanning two grid tracks. Lists use 14px links with 12px gaps, silver text and faint underlines. The full grid has six tracks and 24px gutters.

**States:** Declared: hover link underline becomes white; focus-visible 3px rgba(255,255,255,0.5) outline with 2px offset.

### Plan card

**Only for:** pricing pages

**Use:** Comparable purchase options.

**CSS:** `display: flex; flex-direction: column; padding: 24px; border: 1px solid #dadde2; border-radius: 4px`

**Text style:** `plan-label` — ui-monospace 400 · 13px/1.5 · tracking 0.025em · uppercase

**Observed:** Plan label, serif blue price and small baseline-aligned billing unit, brief summary, checkmarked benefits, then a bottom-aligned full-width action. Three 320px by 465px cards sit 32px apart. The recommended middle panel receives a pale blue gradient, blue-tinted edge and a 6px lower-right offset; its action is solid blue, the entry plan uses Secondary button and the business plan a pale blue action.

**Transfer:** Use genuine comparable features and anchor all actions on one horizontal line.

### Editorial sidebar item

**Only for:** editorial company pages

**Use:** Persistent local orientation next to long-form content.

**CSS:** `padding: 4px 16px; border-left: 1px solid rgba(19,72,220,0.5); background: rgba(19,72,220,0.05); color: #1348dc`

**Text style:** `link` — writer 400 · 14px/20px

**Observed:** Selected item is a shallow 28px strip in a 224px rail under a tiny uppercase organization label. Other items lose the blue wash and left rule.

**States:** Declared: focus-visible 3px rgba(9,78,206,0.5) outline with -4px offset.

## Imagery and graphics

### Drafting-sheet framework

**Use:** Signature structure across the whole landing page.

**Observed:** Thin solid and dashed vertical rails continue through section boundaries. Small outlined white diamonds mark their intersections. Fine square grids appear around key conversion areas; neutral grain softens every plane.

**Transfer:** Preserve the rails, nodes and textured paper even when the product has no visual assets.

**Build:** Draw a 1px #dadde2 border around the centered content span. Extend rails into the margins with 1px lines; use repeating-linear-gradient(#dadde2 0px 4px, transparent 4px 8px) for dashed portions. Place 6px white squares with 1px #cbcfd4 borders, rotated 45deg, over intersections. Add a separate low-opacity neutral SVG turbulence layer at 0.03 opacity, tiled at 180px. For graph paper, overlay two perpendicular repeating 1px pale-blue lines at roughly 10px intervals and fade them toward the text.

### Numeric opening atmosphere

**Use:** Signature background detail behind the centered promise.

**Observed:** Tiny low-contrast blue-gray numerals are scattered in loose vertical runs, concentrated below and around the copy; some are softly blurred. They never compete with the serif title.

**Transfer:** Use sparse numeric or short data-like markings related to the new product, remaining decorative rather than conveying essential information.

**Build:** Place a noninteractive SVG behind the text with small 8px–11px mono numerals. Distribute them in irregular columns, sparse at the top and denser near the lower edge. Vary blue opacity around 0.03–0.12 and apply a light blur to some groups. Keep the central text area largely clear over the Cool opening wash.

### Interface demonstrations

**Use:** Primary visual proof inside capability chapters.

**Observed:** Dark code/editor interfaces with muted syntax color occupy more area than the adjacent explanation. A large split demonstration is about 618px by 348px inside a 652px-wide stage; the broad demonstration is 1070px by 602px. Cool translucent blocks, faint dotted material and occasional greenish top-edge light frame the interfaces. Corners remain 2px rather than pill-like.

**Transfer:** Show a real task, selected state and enough detail to communicate work. If no interface exists, make a coherent static workflow illustration with a dark slate working area and restrained colored annotations; do not substitute unrelated abstract 3D art.

### Product emblem object

**Use:** A tactile anchor in the closing conversion stage.

**Observed:** A 144px dark rounded-square face sits in a 160px white rim, with 32px inner and 40px outer corners, faint grain, a fine edge and soft downward shadow. A white line emblem sits centrally.

**Transfer:** Use the new product's simple symbol, or create an original geometric monogram. This object supplies the conversion stage's visual anchor even without product photography.

**Build:** Make a 160px square with an 8px translucent-white border, 40px outer radius and a soft low-opacity gray shadow below. Inset a dark face with 32px radius and a thin gray edge. Add subtle noise and a tiny cool radial sheen toward the lower-right edge; center a white outlined geometric symbol.

### Hatched closing foundation

**Use:** Signature lower region of the blue closing field.

**Observed:** A broad rectangular diagonal hatch texture lies under the navigation columns, stretching across the central frame. The construction rails continue through the blue.

**Transfer:** Finish the closing field with texture and structure rather than adding another oversized marketing headline.

**Build:** Below the columns, add a 1px rgba(255,255,255,0.1) top border and a repeating-linear-gradient at 135deg with 1px rgba(255,255,255,0.1) strokes alternating with 3px transparent gaps. Fade the hatch slightly toward the bottom; continue vertical rails in white at 0.14 opacity.

### Directory product medallions

**Only for:** compact multi-product directories

**Use:** Distinguish a small family of products.

**Observed:** 144px square blue and red tiles show pale dimensional line emblems on fine gridded or diagonally hatched backgrounds. They sit flush beside ruled text-and-action strips above one broad light product interface.

**Transfer:** Give each product one restrained accent identity and a related geometric emblem, retaining the small square tile and tight alignment.

### Icons

**Observed:** Most marketing action icons are 14px outline SVGs with 2px rounded strokes; small chevrons and utility icons are 10px–12px. Icons sit before action labels, while chevrons, plus signs and boxed key hints sit after them.

**Transfer:** Choose simple technical outline icons that inherit the text color. Avoid oversized decorative icon badges; retain the 6px action gap.

## Section recipes

How recurring sections are built.

### First screen: Shallow promise stage

**Observed:** The first screen starts with Sticky navigation, then a 350px-high framed opening. Paper grain, Cool opening wash and Numeric opening atmosphere sit behind the centered display title; the title is a single modest blue line, not a giant word sculpture. A two-line support paragraph stays within 550px, followed after 28px by Primary button and Secondary button at an 8px gap, with a text link 20px below. Opening vertical padding is 72px. Within the first 900px, the entire opening and the next chapter's 48px-inset heading pair are visible, followed by the active Capability selector row and much of a dark product demonstration. The demonstration's lower edge and later proof chapters continue below the fold.

**Transfer:** Give a different product a specific short promise, one supporting sentence and two genuinely different actions. Use Numeric opening atmosphere and a convincing static Interface demonstration if no finished media exists. Pricing opens with a shorter 198px title band and proceeds into plan comparison; editorial pages open with a left rail and a 32px title over prose; compact directories use the warm paper variant and a short organization masthead.

**Avoid:** Do not make a viewport-height hero, a 72px sans-serif slogan, or a giant floating product mockup above the first chapter.

**Text style:** `display` — plexSerif 390 · 32px/1.2

### Chapter heading pair

**Observed:** A Ruled cell header uses 48px padding, a 25.6px serif heading and an 8px gap to 16px lead copy, generally constrained to 512px. An optional 11px uppercase mono eyebrow precedes it; a Secondary button aligns on the right. Centered variants introduce broad demonstrations.

**Transfer:** Organize capability chapters by user outcome, with a short explanation and a single route deeper.

**Text style:** `heading` — plexSerif 390 · 25.6px/1.25

### Split demonstration chapter

**Observed:** Below Chapter heading pair, a twelve-track layout gives five tracks to the Capability selector row stack and seven to Interface demonstrations. The expanded description has a serif subhead and text link; the large dark working scene supplies the contrast.

**Transfer:** Group related workflows in one chapter; align the active explanation with the matching work scene.

### Ruled proof matrix

**Observed:** A centered serif heading introduces a 1024px-wide three-column, two-row quotation matrix. Shared hairlines replace gutters; one Highlighted quotation has a cool offset border and selective blue text marking. Portrait and author details sit low in each cell.

**Transfer:** Use fewer cells when fewer authentic quotations are available, retaining a contiguous ruled layout and one emphasized voice.

### Measured proof chapter

**Observed:** Chapter heading pair sits above Metrics sheet with 48px external insets. The chart's range controls occupy its upper right; fine axes and modest labels keep the graphic utilitarian.

**Transfer:** Show a verifiable performance, usage or outcome measure rather than decorative rising curves.

### Capability ledger

**Observed:** Three flush columns of Ruled cells use serif card-title labels and 13px explanatory text. The first row includes small dark interface details in dashed outer frames; a second row is text and blue links. Borders tie the whole grid together.

**Transfer:** Mix illustrated capabilities with concise supporting principles without giving every cell its own raised card.

### Working activity and resources

**Observed:** A section introduction is paired with four small inline-stat cells in a two-by-two block. Below it, compact 53px ruled activity rows show a small avatar, update title, author and date metadata. Resource chapters combine three summary cells with full-width 49px title-description-link rows.

**Transfer:** Use a real release history, customer outcomes or a comparable living proof stream. Keep counts at 14px instead of turning them into display typography.

### Conversion object and blue ending

**Observed:** A 450px-high graph-paper stage centers Product emblem object above a blue 25.6px title, a short support line and paired actions. It meets Cobalt closing field directly. Footer column lists occupy the upper part of the 632px field, with Hatched closing foundation below. Editorial company pages enter the same blue ending directly after their final proof table.

**Transfer:** Preserve the tactile symbol, paired action and strong blue ending on a default product landing page. The object and hatch are the memorable punctuation; adapt their placement to the story rather than repeating a fixed section count.

### Plan comparison and open answers

**Only for:** pricing pages

**Observed:** A short centered introduction is followed by a muted partner-logo strip and three Plan cards. Answers remain expanded in a centered 672px reading column: 21.6px serif questions, 12px gap to 16px/26px paragraphs and 32px before the next question. A compact business banner precedes the standard conversion object and blue ending.

**Transfer:** Explain the purchasing model honestly and leave substantial answers readable without interaction.

**Text style:** `question` — plexSerif 380 · 21.6px/1.3 · tracking 0.005em

### Editorial rail and proof table

**Only for:** editorial company pages

**Observed:** A 224px local navigation rail stands to the left of a 720px reading column. A blue display title leads into 16px/26px prose, separated from a sequence of black serif principles by a rule. The ending includes a bordered partner table with tiny uppercase group bars and logo cells, then the blue footer without an extra conversion stage.

**Transfer:** Use for mission, philosophy or technical position essays. Close with an appropriately grouped evidence table rather than forcing a sales pitch.

### Condensed directory ending

**Only for:** compact multi-product directories

**Observed:** A 1024px rose-paper frame contains a 138px masthead, two product strips, a large light interface, a 77px three-cell related-tools strip and a 57px centered footer of tiny text links with dot separators.

**Transfer:** Use this smaller, denser variant for an organization or multi-product index; retain the three-cell cross-link strip and simple final text row rather than importing the large blue ending.

## Page flow

**Storyline:** specific promise → working demonstration → credible proof → capability detail → deeper resources → conversion punctuation and structured closing

### Flagship product landing page

1. **Promise** — Shallow centered title stage with paired actions and a faint technical atmosphere.
2. **Product demonstration** — A split active-capability explanation and dark working scene.
3. **Social and quantitative proof** — Ruled quotations followed by a chart sheet.
4. **Capability chapters** — A wide demonstration and a contiguous three-column capability ledger.
5. **Living proof and deeper resources** — Small activity counts, release rows, reading cells and resource links.
6. **Closing call** — Tactile product emblem, short promise, paired controls and the blue destination field.

**Transfer:** Let real product work lead the story, and use structured proof to earn the final conversion.

### Purchase decision page

1. **Promise** — Short centered introduction followed by understated partner marks.
2. **Pricing** — Three equal-height plan cards, with the middle one lightly offset and blue-accented.
3. **Objection handling** — Long expanded answers in a narrow reading column.
4. **Segment-specific conversion** — A compact ruled business banner.
5. **Closing call** — Standard emblem conversion stage and blue footer.

**Transfer:** Keep comparisons compact, but allow the explanation below to be as long as the purchasing model needs.

### Company philosophy or editorial page

1. **Position** — A local navigation rail beside a blue title and introductory prose.
2. **Principles** — Black serif statements followed by practical explanatory paragraphs.
3. **Credibility** — A grouped partner table with ruled logo cells.
4. **Closing orientation** — Direct transition into the blue footer.

**Transfer:** Use a reading-led structure and concrete beliefs; reserve the final section for relevant credibility.

### Compact organization and product directory

1. **Identity** — A modest serif organization masthead with an italic support sentence.
2. **Product choice** — Two compact emblem-and-description strips with paired actions.
3. **Product demonstration** — One broad detailed light interface.
4. **Related ecosystem** — Three flush ruled cross-link cells.
5. **Closing orientation** — Centered tiny company and utility links on the same warm paper.

**Transfer:** Offer quick orientation between a small number of products rather than stretching this pattern into a long campaign.

## Writing

Direct, literate and technically credible, with confidence grounded in how the product works. Warmth comes through practical benefits and candid explanations rather than inflated enthusiasm.

**Do not copy:** Do not reuse the brand name, logos, proprietary product names, customer names or quotations, partner marks, pricing, performance claims, dates or activity counts. The source phrases illustrate cadence only; write original claims supported by the new product.

- **Addressing the reader:** Use you and your for the reader's work, we for a team explaining its choices, and the product name for factual capability statements.
- **Rhythm:** Headlines are usually short sentence-case phrases. Support is one concrete sentence, often split into two balanced lines. Longer answers use plain paragraphs and occasional candid qualifications rather than bullet-heavy sales copy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the activity and a distinctive quality of the experience. | 4–7 words | “AI coding at native speed”<br>“Build better with [Brand]” |
| Capability title | Use active verbs or an outcome followed by a concrete mechanism. | 4–8 words | “Delegate, review, and extend your flow”<br>“Code faster with edit predictions” |
| Support | Explain what happens in the user's workflow, with concrete actions. | 15–28 words | “Hand off tasks to your favorite agent, follow it along in real-time, and easily review its changes.” |
| Action | A literal verb and destination; use arrows for reading links. | 2–5 words | “Download now”<br>“View Full Metrics”<br>“Read Post →” |
| Principle | State a clear belief and explain the daily consequences. | 4–8 words for the title | “Your editor should disappear”<br>“Conversations should happen close to code” |
| Answer heading | Ask the actual buyer's question, without disguising the trade-off. | 7–12 words | “Is there a minimum seat count for Business?” |

**Words and phrasing to use:** native speed; real-time; full control; your flow; bring your own; open; review; connect; learn; built in public

**Avoid:** revolutionary; game-changing; unlock limitless potential; magic; superlatives without a mechanism

**Rules:**

- Pair each benefit with an observable operation or implementation detail.
- Prefer a simple imperative in actions over a clever branded verb.
- State restrictions and alternatives plainly in purchase explanations.
- Keep headings in sentence case; uppercase belongs to tiny category and plan labels.

## Do's and Don'ts

### Do

- Keep the default opening title at 32px/1.2 and interior titles at 25.6px/1.25.
- Carry 1px construction rules and intersection nodes across section boundaries.
- Use 48px desktop chapter insets around compact text, not oversized typography.
- Pair 36px blue and translucent controls with 4px corners and an 8px gap.
- Frame real working interfaces with 2px edges and low-intensity cool light.
- Use 6px hard-offset proof shadows instead of a blurred elevation stack.
- Maintain the pale reading canvas and concentrate full saturation in the closing field.
- Set technical eyebrows at 11px/1.5 with 0.05em tracking.

### Don't

- Do not turn 4px control corners into 24px pills; the controls should feel like instrument keys.
- Do not replace the serif title face with bold geometric sans-serif.
- Do not style every feature as a separate floating white tile with a deep shadow.
- Do not enlarge 14px activity counts into 80px statistic posters.
- Do not use the red directory accent as a second full-page marketing theme.
- Do not apply the directory's italic summaries to ordinary landing-page lead copy.
- Do not make the blue footer a flat unstructured rectangle; retain column rules and the hatch foundation.
- Do not introduce large lifestyle portraits where the working interface should carry the visual proof.

## Motion and responsive

### Motion

**Observed:**

- Declared control interactions include scale 0.99 on active and removal of inset shadows on hover or active for raised actions.
- Declared transitions include all 70ms ease and transform-related changes over 0.1s or 0.15s with cubic-bezier(.4,0,.2,1). No active animation was matched to the marketing elements.

**Transfer:**

- Keep pressed-control feedback small and immediate; maintain the instrument-like edge removal rather than introducing springy button motion.
- Keep decorative numeric atmosphere behind content and independent of reading order.

**Unknown:**

- The numeric canvas animation behavior and timing are not established.
- Scroll reveal timing and runtime use of the available keyframes are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 639px, 640px, 768px, 820px, 1024px, 1280px and 1536px.
- Layout classes declare stacked actions before the large breakpoint, one-column quote and plan grids before their desktop expansion, and 16px padding before 48px desktop insets.
- Footer declares one column, then four columns at the medium breakpoint, then six tracks at the large breakpoint.

**Transfer:**

- On narrow screens preserve the shallow title hierarchy, compact controls and ruled-document logic while stacking text and demonstrations.
- Move the editorial local navigation above the prose; keep its selected strip rather than shrinking the reading column beside a fixed rail.
- Let the emblem remain the closing stage's anchor while the paired actions stack.

**Unknown:**

- Exact rendered narrow-screen navigation behavior, rail visibility and media cropping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
