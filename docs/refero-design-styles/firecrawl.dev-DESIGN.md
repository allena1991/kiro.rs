# Firecrawl — embers on graph paper

## Overview

A light developer-facing style that feels like a technical workbench warmed by fire-orange accents. Neutral grotesk headlines, tiny monospaced markings and almost invisible ruled panels balance friendly directness with engineering detail. White interface objects float above pale gray stages, while character-based data sculptures supply atmosphere rather than conventional photography. Spacious chapter introductions alternate with denser demonstrations, proof and practical information.

### Essentials

- Headlines split promise from payoff with color, not font changes: Suisse 60px/64px at 500 and -0.005em for the opening, 52px/56px at 500 and -0.01em for major chapters; one phrase turns orange.
- The opening is a working instrument on graph paper: a centered two-line promise, paired 36px actions and a 552px-wide floating input panel sit inside a faint 102px-cell technical frame.
- Orange behaves like heat inside a nearly monochrome machine: #fa5d19 marks headline fragments, links, tiny registration details and primary actions; most page area remains #f9f9f9, with one concentrated orange character-art statement providing contrast.
- Actions are compact tactile rectangles, not oversized pills: 10px corners, 14px/20px medium labels, 8px 12px padding and a warm inset bottom shadow on the orange primary.
- The grid is visible architecture: 1112px content rails, #ededed 1px dividing lines, square-edged chapter cells and 12px/16px monospaced numbered labels keep unrelated sections feeling connected.
- Data becomes atmosphere: faint gray ASCII topographies sit behind chapter headings and orange character plumes flank the closing invitation. Recreate these as glyph-density fields when no equivalent product media exists; retain the device rather than replacing it with generic gradients.
- The page ends as a technical directory, not a dead-end logo: a graphic-backed brand statement and assurance cells precede four ruled link columns, legal cells and a small blue system-status signal.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Heat orange | `#fa5d19` | `--color-heat` | accent, text, background, action, link | Headline emphasis, primary actions, character art and occasional concentrated statement bands. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#262626` | `--color-ink` | text | Headlines, active labels and primary prose. |
| Support ink | `#616161` | `--color-support` | text | Primary ink at 0.721569 alpha over the canvas for section support, footer links and secondary prose. |
| Secondary ink | `#727272` | `--color-muted` | text | Visible result of primary ink at 0.639216 alpha on the canvas; explanatory feature copy. |
| Faint annotation | `#b5b5b5` | `--color-annotation` | text | Primary ink at 0.321569 alpha over the canvas for uppercase chapter markings. |
| Selected control | `#eaeaea` | `--color-selected` | surface | Visible black 0.058824 wash over the canvas for selected code tabs. |
| Faint rule | `#ededed` | `--color-rule` | border | 1px page rails, cell dividers and panel edges. |
| Neutral control | `#efefef` | `--color-control` | surface, action | Visible black 0.039216 wash over the canvas for secondary buttons. |
| Workbench canvas | `#f9f9f9` | `--color-canvas` | background, surface | Continuous light page canvas and flat technical panels. |
| Raised white | `#ffffff` | `--color-white` | surface, text | Floating interface objects and reversed text on orange. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| System blue | `#2a6dfb` | `--color-status` | text, accent | System-status label and its 6px dot at the very end of the footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing comparisons | Recommended plan wash | `#f9f3f0` | `--color-plan-wash` | background | Visible orange 0.039216 wash over the canvas, reserving saturated orange for the plan action. |

## Typography

- **suisse** — Marketing headlines, paragraphs, navigation and controls. Neutral neo-grotesk with compact proportions, an open readable lowercase and medium rather than bold display weight. If unavailable, use **Inter**. Use 400, 450 and 500; preserve the restrained negative tracking. Font stack: "suisse", "Inter", system-ui, -apple-system, "Segoe UI", Arial, sans-serif.
- **GeistMono** — Chapter numbering, technical annotations and code. Small, evenly spaced technical lettering contrasting with the proportional grotesk. If unavailable, use **Geist Mono**. Font stack: "GeistMono", "Geist Mono", ui-monospace, SFMono-Regular, Menlo, monospace.
- **Roboto Mono** (only for character-based graphic artwork) — Glyph fields and architectural character sculptures, never ordinary prose. Fixed-width texture whose density supplies form and tone. Font stack: "Roboto Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | suisse | 500 | 60px | 64px | -0.005em | Two-line marketing opening; the emphasized phrase keeps the same recipe. |
| heading-lg | suisse | 500 | 52px | 56px | -0.01em | Centered major chapter headlines and orange proof numerals. |
| heading | suisse | 500 | 40px | 44px | -0.01em | Compact split chapter headings, closing invitation and plan price numerals. |
| subheading | suisse | 500 | 24px | 32px | -0.01em | FAQ category labels and compact pricing subsection headings. |
| feature-copy | suisse | 400 | 20px | 1.4 | -0.005em | Feature text with a dark opening benefit clause followed by muted explanation. |
| body | suisse | 400 | 16px | 1.5 | normal | Opening support, section descriptions, testimonial quotations and expanded answers. |
| label-lg | suisse | 450 | 16px | 1.5 | normal | FAQ questions, feature labels and orange documentation links. |
| label | suisse | 450 | 14px | 20px | normal | Buttons, navigation and short card labels. |
| body-sm | suisse | 400 | 14px | 20px | 0.01em | Compact explanatory text, plan descriptions and directory links. |
| code | GeistMono | 400 | 14px | 22px | normal | Readable code in installation and integration panels. |
| caption | suisse | 450 | 13px | 20px | normal | Icon-led feature eyebrows and code tabs. |
| chapter | GeistMono | 400 | 12px | 16px | normal, uppercase | Uppercase chapter descriptions beside numbered progress markings. |
| chapter-number | GeistMono | 400 | 12px | 16px | normal | Orange chapter index, brackets and progress count. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company-story pages | statement | suisse | 500 | 32px | 36px | -0.01em | White mission sentence in a concentrated orange card. |
| company-story pages | statement-caption | GeistMono | 450 | 12px | 20px | 0.025em | Bracketed uppercase caption above a mission sentence. |

**Notes:**

- Keep display and section headings at 500; contrast comes from orange phrases and line breaks rather than a heavy bold cut.
- Tracking is -0.005em at 60px and 20px, tightening to -0.01em for 52px, 40px, 32px and 24px headings. Small body text has a slight positive 0.01em spacing.
- A chapter marking and a feature eyebrow are different roles: the former is uppercase mono, the latter sentence-case sans with a small outline icon.
- Centered major headings coexist with compact two-part heading bands: an eyebrow sits in the left portion and a left-aligned 40px headline sits to its right.

## Layout

**Density:** Airy chapter framing with compact controls and information-dense technical demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and compact control padding. |
| 12px | Paired-action gaps and progress-label spacing. |
| 16px | Headline-to-support gap, common flex gaps and feature eyebrow separation. |
| 24px | Floating input separation from actions and modest panel padding. |
| 28px | Directory horizontal insets and pricing-card text insets. |
| 32px | Integration column insets and headline-to-action spacing. |
| 40px | FAQ category vertical padding and mission-card padding. |
| 56px | Integration-column vertical padding. |
| 64px | Feature and FAQ horizontal insets; story-section vertical rhythm. |
| 88px | Compact split-heading band vertical padding. |
| 143px | Desktop major chapter-heading vertical padding. |

### Containers and grids

- **page rails**: max width 1112px · side padding 16px. Centered common frame for nearly all marketing content. At 1440px the rails sit 164px from either side; rules continue through neighboring blocks.
- **technical pair**: 2 columns · gap 0px. Two equal 556px cells with shared dividing rules; installation examples use 32px inner insets, feature introductions can use 64px.
- **proof strip**: 4 columns · gap 0px. Four contiguous 278px statistic cells with vertical separators and 32px 28px inner padding.
- **opening instrument**: max width 552px. Centered compact interaction panel beneath the opening actions.
- **narrow copy**: max width 520px. Readable feature explanation measure; ordinary section support can narrow to 369px.
- **story column** (only for company-story pages): max width 768px. Long-form left-aligned explanation inside the larger page rails.
- **plan grid** (only for pricing pages): 4 columns · gap 0px. Contiguous plans above a three-column scale-plan row; each column shares border rails rather than floating as a detached card.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary and secondary actions | 10px |
|  | navigation controls | 8px |
|  | small code tabs | 6px |
|  | browser demonstration panels | 12px |
|  | floating instrument | 20px |
| company-story pages | mission card | 16px |
| catalog browsing | filter chips | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| warm action | `inset 0px -6px 12px 0px rgba(250,29,25,0.2), 0px 2px 4px 0px rgba(250,93,25,0.12), 0px 1px 1px 0px rgba(250,93,25,0.12), 0px 0.5px 0.5px 0px rgba(250,93,25,0.16), 0px 0.3px 0.3px 0px rgba(250,93,25,0.2)` | Primary orange controls; a thin white-to-transparent overlay at 0.06 opacity adds a slight top sheen. |
| floating white | `0px 0px 44px 0px rgba(0,0,0,0.02), 0px 88px 56px -20px rgba(0,0,0,0.03), 0px 56px 56px -20px rgba(0,0,0,0.02), 0px 32px 32px -20px rgba(0,0,0,0.03), 0px 16px 24px -12px rgba(0,0,0,0.03), 0px 0px 0px 1px rgba(0,0,0,0.05)` | Hero instrument and high-emphasis white form panels; broad low-opacity layers rather than a dark drop shadow. |

### Surfaces

#### Workbench · level 0

**Use:** Continuous page foundation.

**CSS:** `background: #f9f9f9; color: #262626`

**Observed:** Light neutral canvas carries thin horizontal and vertical technical rails; it does not alternate between unrelated background colors.

**Transfer:** Keep sections within one ruled environment.

#### Ruled cell · level 0

**Use:** Feature, logo, proof and footer architecture.

**CSS:** `background: #f9f9f9; border: 1px solid #ededed`

**Observed:** Adjacent cells share lines; corners are largely square. Tiny cross or curved registration details punctuate intersections.

**Transfer:** Use contiguous cells instead of a field of separately rounded cards.

#### Floating white · level 2

**Use:** Interactive hero instrument and selected form panels.

**CSS:** `background: #ffffff; border-radius: 20px; box-shadow: 0px 0px 44px 0px rgba(0,0,0,0.02), 0px 88px 56px -20px rgba(0,0,0,0.03), 0px 56px 56px -20px rgba(0,0,0,0.02), 0px 32px 32px -20px rgba(0,0,0,0.03), 0px 16px 24px -12px rgba(0,0,0,0.03), 0px 0px 0px 1px rgba(0,0,0,0.05)`

**Observed:** The strongest raised object is still white on near-white. A matching canvas-colored outer halo separates it from the stage.

**Transfer:** Reserve real elevation for the instrument the visitor can use.

#### Technical panel · level 1

**Use:** Installation and integration examples.

**CSS:** `background: #f9f9f9; border: 1px solid #ededed`

**Observed:** Square frame, divided toolbar, monospaced body and an orange text link underneath.

**Transfer:** Show a short useful instruction rather than an entire application.

#### Heat statement · level 0

**Use:** A concentrated change of intensity within the light layout.

**CSS:** `background: #fa5d19; color: #ffffff; overflow: clip; padding: 96px 20px`

**Observed:** An orange 1112px-wide, 560px-tall band holds a centered white headline and character-built architecture around its perimeter. White primary and translucent outlined secondary actions invert the ordinary controls.

**Transfer:** Dedicate the band to one meaningful expansion of the promise, leaving the text center clear.

#### Plan highlight · level 0

**Only for:** pricing comparisons

**Use:** One recommended plan in a contiguous grid.

**CSS:** `background: rgba(250,93,25,0.039216); border-left: 1px solid #ededed; border-right: 1px solid #ededed`

**Observed:** The selected column has a very pale warm wash rather than a saturated fill.

**Transfer:** Keep all prices legible in dark ink and use the orange action as the focal point.

## Components

### Primary button

**Use:** Main conversion or exploration action.

**CSS:** `background: #fa5d19; color: #ffffff; border-radius: 10px; padding: 8px 12px; height: 36px; display: inline-flex; align-items: center; justify-content: center; gap: 6px; box-shadow: inset 0px -6px 12px 0px rgba(250,29,25,0.2), 0px 2px 4px 0px rgba(250,93,25,0.12), 0px 1px 1px 0px rgba(250,93,25,0.12), 0px 0.5px 0.5px 0px rgba(250,93,25,0.16), 0px 0.3px 0.3px 0px rgba(250,93,25,0.2)`

**Text style:** `label` — suisse 450 · 14px/20px

**Observed:** A subtle top sheen and darker warm lower edge make it tactile. A small arrow can follow the label. Hero controls use 8px padding plus label insets; the standard button is the default elsewhere.

**States:** Declared: hover background uses orange at 0.9 alpha and a stronger shadow; focus-visible outline is transparent, 2px with 2px offset; active scale is 0.995.

**Transfer:** Pair with a quieter secondary action rather than another equally bright control.

### Secondary button

**Use:** Pricing, documentation or alternate conversion beside the primary.

**CSS:** `background: rgba(0,0,0,0.039216); color: #262626; border-radius: 10px; padding: 8px 12px; height: 36px; display: inline-flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `label` — suisse 450 · 14px/20px

**Observed:** Neutral translucent fill on the page canvas; no heavy outline or action shadow.

**States:** Declared: hover background rgba(0,0,0,0.058824); focus-visible transparent 2px outline with 2px offset; active background rgba(0,0,0,0.070588) and scale 0.99.

### Navigation item

**Use:** Compact sticky-header menu.

**CSS:** `height: 32px; padding: 6px; border-radius: 8px; display: flex; align-items: center; color: #262626`

**Text style:** `label` — suisse 450 · 14px/20px

**Observed:** Logo left, centered menu and utility actions right in a 92px sticky header. Small downward chevrons mark expandable groups; the header uses the same canvas as the page.

**Transfer:** Keep the navigation narrow and functional; the catalog campaign reverses its header over orange.

### Documentation link

**Use:** Continuation beneath a technical panel or quantified benefit.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; color: #fa5d19`

**Text style:** `label-lg` — suisse 450 · 16px/1.5

**Observed:** A small right chevron follows the text; there is no enclosing button surface.

**States:** Declared: hover opacity 0.8.

### Chapter marker

**Use:** Technical chapter identification within the page rails.

**CSS:** `display: flex; align-items: center; gap: 12px`

**Text style:** `chapter` — GeistMono 400 · 12px/16px · uppercase

**Observed:** An orange number sits among faint brackets and total count, followed by a tiny divider and uppercase mono description. A short orange tick marks the left rail. The label has substantial breathing space above it.

**Transfer:** Use the new page's own chapter labels and total; preserve the equipment-marking appearance.

### Code panel

**Use:** A useful install instruction or integration example.

**CSS:** `background: #f9f9f9; border: 1px solid #ededed; position: relative`

**Text style:** `code` — GeistMono 400 · 14px/22px

**Observed:** Divided toolbar with compact selected tabs and a copy icon; code body has 16px to 20px insets. Two panels sit side by side under short introductory copy, with Documentation link below.

**Transfer:** Keep examples short enough to understand as real instructions, with only sparse orange syntax emphasis.

### Selected code tab

**Use:** Active mode in an installation panel.

**CSS:** `background: rgba(0,0,0,0.058824); color: #262626; border-radius: 6px; padding: 4px 10px; height: 28px`

**Text style:** `caption` — suisse 450 · 13px/20px

**Observed:** Inactive siblings are plain muted text; a separate copy icon is pushed to the far edge of the toolbar.

### Question row

**Use:** FAQ objection handling.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 20px 64px; min-height: 64px; width: 100%; color: #262626`

**Text style:** `label-lg` — suisse 450 · 16px/1.5

**Observed:** A right-edge chevron follows a flexible question label. Each row occupies a ruled right-hand cell, opposite a category label in the left half. Answers use muted Body text.

**Transfer:** Keep the category column spacious rather than filling it with explanatory copy.

### Directory link

**Use:** Social links and the final multi-column resource directory.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 16px 28px; color: rgba(38,38,38,0.721569)`

**Text style:** `body-sm` — suisse 400 · 14px/20px · tracking 0.01em

**Observed:** Each link occupies an individual ruled cell. Social links include small monochrome icons; the larger directory uses four equal columns with medium labels at the top.

**States:** Declared: hover color changes to orange.

### System status

**Use:** Final operational signal below the legal directory.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 6px; padding: 8px 12px; height: 36px; border-radius: 10px; color: #2a6dfb`

**Text style:** `label` — suisse 450 · 14px/20px

**Observed:** A 6px blue dot sits inside a 20px icon area. The status control is left-aligned within an 84px-tall ruled bottom band.

**States:** Declared: hover background rgba(0,0,0,0.039216); focus-visible transparent 2px outline at 2px offset; active scale 0.99.

### Plan column

**Only for:** pricing pages

**Use:** Comparable self-serve subscription plans.

**CSS:** `border-left: 1px solid #ededed; border-right: 1px solid #ededed; position: relative`

**Text style:** `body-sm` — suisse 400 · 14px/20px · tracking 0.01em

**Observed:** Plan name and a short fit sentence lead into allowance, 40px price, a compact annual toggle, full-width action and ruled benefit rows. One recommended column uses Plan highlight and an orange action; others use neutral actions. High-volume options form a second three-cell row.

**Transfer:** Keep equivalent facts on aligned horizontal baselines; use a single recommended choice.

### Form input

**Only for:** multi-step lead forms

**Use:** Short-answer field inside a raised form card.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.078431); border-radius: 8px; padding: 8px 12px; height: 36px; width: 100%`

**Text style:** `body-sm` — suisse 400 · 14px/20px · tracking 0.01em

**Observed:** A small step count and thin progress line precede a question and helper sentence. Continue action follows the field; small privacy copy closes the white card.

## Imagery and graphics

### Technical registration grid

**Use:** Opening stage and closing invitation; a signature frame repeated across the site.

**Observed:** Very pale square cells, tiny cross intersections, occasional filled square clusters, bracketed edge labels and a few orange four-point registration stars. The center remains clear enough for dark text; the stage extends wider than the main content rails.

**Transfer:** Use abstract technical markings appropriate to the new product, retaining the pale structured surround rather than copying interface labels.

**Build:** Draw a 102px square SVG pattern with 1px #ededed lines and 3px faint cross intersections. Fade the grid toward the clear central text region using a mask. Add a few 10px squares at low-opacity black and two 20px orange four-point stars near the upper side corners. Keep marks behind all content.

### ASCII topography

**Use:** Chapter-heading atmosphere, closing side plumes and footer graphic.

**Observed:** Tiny gray characters form soft rolling topographies behind headings; sparse orange characters form tall tapering columns at either side of the closing invitation and a low landscape under the footer brand statement. The texture is tonal and airy, not a legible text block.

**Transfer:** Rebuild the data sculpture using a glyph-density field. A simpler still SVG topography is the minimum equivalent; it must retain coherent volume and a clear text center.

**Build:** Place mono glyphs such as dots, colons, pluses and x characters on a 5px to 8px lattice in SVG. Vary glyph density along several offset sine-wave contours to form an irregular mound; render gray fields at rgba(38,38,38,0.06) to 0.16 and orange plumes at rgba(250,93,25,0.16) to 0.5. Fade edges into #f9f9f9. Use a clear center mask and confine the strongest orange to the lower side shapes.

### Floating product miniatures

**Use:** Hero demonstration and capability proof cells.

**Observed:** Small white browser windows, paper sheets, stacked cards and network-like icon orbits are built as clean vector/interface objects. Thin gray edges, short peach or gray content rules, tiny orange status chips and broad pale shadows make them feel almost embossed. The object sits below the explanatory copy, not as a full-bleed application image.

**Transfer:** Show the simplest recognizable input-to-output scene for the new product. If a real interface is unavailable, build one browser frame, meaningful rows and a clear result label; do not fill the cell with arbitrary dashboard furniture.

### Character architecture band

**Use:** A concentrated orange statement contrasting with the light technical chapters.

**Observed:** White ASCII characters form tall architectural side walls and a low perspective floor around an open orange center. Centered white typography stays dominant; the artwork behaves like a luminous hall rather than a flat patterned wallpaper.

**Transfer:** Use character-built walls, contours or a product-relevant monumental form. The minimum version is a pair of density-modulated side volumes and a perspective character floor with a clear center.

**Build:** On #fa5d19, use Roboto Mono glyph rows in rgba(255,255,255,0.86), roughly 8px lettering with 9px row spacing. Compress glyph spacing toward distant vanishing lines. Layer two architectural side masks and a lower floor field, then apply a radial center cutout with a transparent inner 30% and opaque edge. Keep text and actions above the art.

### Orbiting ecosystem globe

**Only for:** ecosystem or catalog pages

**Use:** Visual proof of broad connected coverage.

**Observed:** A monochrome globe made of tiny plus signs occupies a 1112px by 600px stage. Several thin tilted elliptical orbits carry small white square logo tiles; an understated mono count caption sits at the bottom.

**Transfer:** Replace provider logos with genuine integrations or abstract category symbols; preserve the light scientific-diagram treatment.

**Build:** Project a dotted sphere into SVG using small gray plus glyphs, vary their alpha by depth, and draw three tilted ellipses with 1px rgba(38,38,38,0.12) strokes. Place 32px to 40px white symbol tiles at different orbit points with faint edges and minimal shadows.

### Mission heat card

**Only for:** company-story pages

**Use:** One memorable sentence inside a longer editorial explanation.

**Observed:** A 768px by 180px orange rounded rectangle holds a bracketed mono caption and white 32px statement with 40px insets. A tight field of pale square dots supplies texture behind the sentence.

**Transfer:** Use one concrete organizing belief or purpose, not a long manifesto.

**Build:** Use a 16px radius orange rectangle, with 4px square marks on an 8px lattice in rgba(255,255,255,0.2). Modulate density in broad wavy bands and fade behind the text center.

### Human proof portraits

**Only for:** testimonials and company-story pages

**Use:** Small identity cues beside quotations or founder cards.

**Observed:** Small circular color photographs accompany names; the surrounding cards stay monochrome and understated. There is no large lifestyle photography system.

**Transfer:** Use authentic small portraits, keeping names and words more prominent than photography.

### Icons

**Observed:** Thin outline functional icons are usually 18px to 24px with 1.3px round strokes; small chevrons and arrows can use 16px shapes and heavier strokes. Icons are muted gray or ink, with orange reserved for emphasis. Tiny registration crosses belong to the frame, not to the content icon vocabulary.

**Transfer:** Choose one restrained outline set, using orange sparingly. Use simple small product symbols and keep third-party marks inside proof or integration contexts.

## Section recipes

How recurring sections are built.

### First screen: Instrument on graph paper

**Observed:** The first screen layers a thin orange announcement strip, a 92px sticky navigation, a wide Technical registration grid, a centered two-line 60px headline and a compact working instrument. The heading occupies roughly the central 600px width and distinguishes its payoff with orange. A small offer pill sits above it; a short 16px support paragraph and Primary button plus secondary connection action sit below. The 552px-wide white instrument follows with an input row above mode tabs and an orange arrow action. Within the first 900px, the headline, support, actions and whole instrument are visible; the upper edge of a larger code/output stage appears near the bottom. Customer proof falls below the fold. ASCII texture is behind the instrument, never over the text.

**Transfer:** Use a meaningful compact input or selector as the main object for a different product; a single realistic interactive result card is the fallback. Product-detail openings can show a 624px browser demonstration below the same centered promise; pricing openings shorten to a 52px title above a usage selector; company openings use the same grid with a short descriptive paragraph and no large instrument. Catalog campaign openings reverse to white text over orange character architecture.

**Avoid:** Do not replace the useful instrument with a giant decorative dashboard, make the heading fill the whole viewport, or place an orange gradient behind the entire default opening.

**Text style:** `display` — suisse 500 · 60px/64px · tracking -0.005em

### Numbered chapter and heading stage

**Observed:** A Chapter marker occupies a roomy ruled band before a clear heading stage. The major stage uses 143px vertical padding, 52px heading-lg with one orange phrase, an icon-led eyebrow and a narrow centered Body support line. ASCII topography sits behind the content at very low contrast.

**Transfer:** Introduce a real new narrative topic with a short technical label and a direct benefit headline. Reuse the graphic device without forcing the same number of chapters.

**Text style:** `heading-lg` — suisse 500 · 52px/56px · tracking -0.01em

### Compact heading pair

**Observed:** A 736px-wide composition puts a small icon-led eyebrow toward the left and a 40px Heading with support on the right. It sits within the full-width ruled stage, often with 88px vertical padding and faint character texture.

**Transfer:** Use for integration, testimonial or FAQ introductions when a full centered billboard would be repetitive.

**Text style:** `heading` — suisse 500 · 40px/44px · tracking -0.01em

### Capability workbench

**Observed:** Two contiguous ruled cells combine a small Caption eyebrow, a 20px benefit-first sentence and an interface miniature below. Introductory copy uses 60px top padding and generous side insets. Full-width centered benefit cells interrupt the pairs, while monochrome diagram controls remain secondary.

**Transfer:** Explain a capability with one useful visual operation: a transformation, a stack, a network or a measured result. Mix paired cells and full-width proof without introducing unrelated materials.

### Installation pair

**Observed:** Two equal cells place Feature-copy above Code panel, with Selected code tab, copy control and Documentation link. 32px horizontal and 56px vertical cell insets make the technical panels feel deliberately embedded.

**Transfer:** Offer two complementary ways to begin, or one instruction and one sample result, rather than duplicating decorative code.

### Proof as ruled numerals

**Observed:** A four-cell strip uses orange 40px numerals, 14px labels and quieter explanatory captions. Company-story proof uses a three-column, two-row arrangement with 52px orange numerals instead. Benchmark chapters use comparison bars and small ruled measurement tables under benefit copy.

**Transfer:** Choose honest, comprehensible measures and retain the unit beside the number. Use orange to distinguish the outcome, not a rainbow chart.

### Concentrated heat statement

**Observed:** Heat statement pairs white heading-lg typography, short support and inverted paired actions with Character architecture band. A four-cell proof strip can directly follow its lower edge.

**Transfer:** Use one focused statement about the broader value or ecosystem. Preserve the contrast with the mostly neutral rest of the page.

**Text style:** `heading-lg` — suisse 500 · 52px/56px · tracking -0.01em

### Categorized questions

**Observed:** A compact heading pair or centered heading stage leads into a two-column ruled FAQ. Subheading categories occupy the left half; Question rows occupy the right, beginning below the category's top band. Expanded prose uses muted Body text.

**Transfer:** Group questions by the visitor's decision rather than presenting a single undifferentiated accordion.

### Graphic closing invitation

**Observed:** A 416px-high ruled stage has a roughly 506px central message cell, a small icon-led prompt, 40px Heading, short Body support, two actions and a faint tertiary setup link. Technical registration grid surrounds the cell and orange ASCII topography forms two tall side plumes.

**Transfer:** Keep the invitation concrete and low-friction. Retain the side sculpture even for products without visual media; change its contours rather than removing it.

**Text style:** `heading` — suisse 500 · 40px/44px · tracking -0.01em

### Technical directory ending

**Observed:** The footer opens with a roomy chapter-like label band. A 346px brand/proof region places logo, 20px statement and orange character landscape on the left; backing and assurance cells plus two social-link columns occupy the right. Four equal directory columns follow, with individual 52px link cells. A legal row and System status finish the page; the light canvas and rails continue all the way down.

**Transfer:** Use appropriate assurance and resource categories for the new product, preserving the graphic-left / proof-right relationship and the final operational signal.

### Contiguous pricing comparison

**Only for:** pricing pages

**Observed:** A compact centered title leads into a large usage numeral, a long orange track with labeled ticks and a centered currency control. Four Plan columns align their fact rows; the recommended column has Plan highlight. A three-cell scale row follows, then compact credit and comparison tables with 32px 64px insets and repeated pale headers.

**Transfer:** Let visitors map a usage amount to a plan before reading detailed limits. Keep detail tables subordinate to the aligned plan choices.

### Editorial story and statement

**Only for:** company-story pages

**Observed:** A 768px left-aligned text column sits inside the shared rails. A 40px split-color heading leads to 16px paragraphs separated by 20px. Mission heat card punctuates the prose after 64px; later proof and small portrait cards expand to wider three-column compositions.

**Transfer:** Move from a concrete problem to a belief, then support it with product capabilities, scale and people rather than generic culture slogans.

## Page flow

**Storyline:** Promise → usable demonstration → credible proof → capability chapters → adoption or commercial detail → objection handling → renewed invitation → technical directory.

### Broad product marketing landing page

1. **Promise** — Grid-backed split-color headline with a compact usable instrument.
2. **Product demonstration** — Customer logo cells, capability summaries and a code/output stage establish practical use.
3. **Adoption** — Paired installation panels reduce setup uncertainty.
4. **Quantified proof** — Benchmark cells and comparison bars substantiate performance benefits.
5. **Capability chapters** — Alternating large heading stages, paired feature miniatures and a use-case workbench.
6. **Broader value** — Orange character-architecture statement with a ruled statistic strip.
7. **Social proof** — Ruled quotation cards with small identity portraits.
8. **Conversion and objections** — Graphic closing invitation followed by categorized questions.
9. **Wayfinding ending** — Brand/proof region, four directory columns, legal cells and blue system status.

**Transfer:** Adapt the balance of demonstration, proof and objections to the new product; retain the instrument, ruled architecture and character-art punctuation rather than the same chapter count.

### Focused product capability landing page

1. **Promise** — Centered split-color headline above a tabbed browser-style transformation demonstration.
2. **Capability proof** — Two-column miniature scenes and a full-width measured benefit.
3. **Adoption** — Integration heading and paired technical panels.
4. **Pricing** — Contiguous self-serve plans and larger-volume options.
5. **Objection handling** — Categorized questions.
6. **Closing and ending** — Graphic closing invitation and complete shared directory with final status.

**Transfer:** Narrow the opening to one clear input and outcome, then demonstrate edge cases before discussing price.

### Commercial comparison and selection page

1. **Plan selection** — Short centered title, prominent usage numeral, labeled slider and currency control.
2. **Pricing** — Four aligned plans with one pale orange recommendation and a separate scale row.
3. **Billing explanation** — Compact explanatory band and credit-consumption rows.
4. **Detailed comparison** — Repeated ruled tables grouped by decision category.
5. **Social proof** — Compact-heading quotation grid.
6. **Objection handling** — Billing questions, then the shared full directory and status ending.

**Transfer:** Let the pricing controls and aligned facts do the persuasion; a separate closing invitation is not necessary when purchase choices already dominate.

### Ecosystem catalog and partner acquisition page

1. **Promise and discovery** — Orange character-architecture opening with white headline, filter chips and eight compact provider cards.
2. **Value explanation** — Four contiguous miniature diagram cells.
3. **Coverage proof** — Large orbiting glyph globe followed by four orange numeric cells.
4. **Exploration** — Category chips and expandable provider browsing.
5. **Adoption** — Paired code/instruction panels.
6. **Partner acquisition** — Split heading and raised multi-step form.
7. **Closing and ending** — Product-specific invitation followed by shared graphic footer, directory, legal and status.

**Transfer:** Scope the saturated opening and browsing controls to pages with a genuine inventory or ecosystem; retain the neutral default elsewhere.

### Company story and credibility page

1. **Introduction** — Compact grid-backed heading and descriptive paragraph.
2. **Purpose** — Narrow explanatory text column punctuated by an orange mission card.
3. **Product context** — Short numbered capability summaries.
4. **Scale proof** — Three-column orange statistic grid.
5. **People and backing** — Small circular portraits and concise supporter cards.
6. **Closing and ending** — Graphic closing invitation, shared brand/proof footer and directory through blue status.

**Transfer:** Use a more editorial measure and longer prose while preserving technical chapter markings and the orange statement device.

## Writing

Confident, developer-literate and practical, with occasional warmth and playful fire-adjacent language. Benefits are stated plainly, then supported with concrete mechanisms, setup instructions or qualified measurements.

**Do not copy:** Do not reuse the brand name, flame mark, proprietary ASCII artwork, customer logos, founders, funding statements, benchmark results, prices, customer quotations or adoption counts. Replace all examples with truthful content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader and their project as you and your; use we for the team taking responsibility for difficult implementation work. Product descriptions can use the product name as the subject.
- **Rhythm:** Short benefit headlines, usually four to nine words, followed by one or two compact explanatory sentences. Feature text often starts with a short dark benefit clause and continues in muted explanatory prose; technical detail grows in pricing and FAQ sections.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the useful output or capability, then emphasize the scope or payoff in orange. | 4–12 words | “Give your AI agents web data and beyond”<br>“Clean markdown from any URL.” |
| Section headline | Use an active promise with one short emphasized phrase; occasional sentence pairs create a crisp contrast. | 4–10 words | “We handle the hard stuff”<br>“A world of data. One library.” |
| Supporting line | Explain the mechanism and practical outcome without an abstract slogan. | 12–30 words | “The infrastructure layer that helps AI find, read, and act on the live web.”<br>“Discover data and tools from providers, indexes and the web.” |
| Feature explanation | Lead with a terse benefit, then say what the system handles. | 15–40 words | “No navs, footers, or ads. Just clean markdown, with 93% fewer input tokens for your model.” |
| Primary action | Verb plus low-friction outcome; secondary actions name the destination. | 2–4 words | “Start for free”<br>“Read the docs”<br>“See our plans” |
| Closing invitation | A brief readiness question followed by a concrete path to starting. | 3–6 words for the heading | “Ready to build?” |

**Words and phrasing to use:** built for; clean; real-time; one call; connect; start; scale; handles; your project; the hard stuff

**Avoid:** revolutionary platform; unlock limitless possibilities; synergize; game-changing solution; effortlessly transform everything

**Rules:**

- Make technical nouns specific enough for a practitioner to recognize the operation.
- Pair strong performance language with a meaningful measurement, test context or implementation explanation.
- Keep free-start reassurance close to the conversion action when it is factually true.
- Use short practical labels for navigation, tabs and FAQs rather than clever metaphors.
- Allow occasional conversational phrases, but keep extended technical explanation direct and unembellished.

## Do's and Don'ts

### Do

- Use 60px/64px medium grotesk type for the default opening and emphasize one phrase in orange.
- Carry 1px #ededed rails through headings, feature cells and the footer within the 1112px frame.
- Make the main interaction panel about 552px wide with 20px corners and broad low-alpha white-surface shadows.
- Keep standard actions at 36px high with 10px corners and 14px/20px labels.
- Include coherent character-density art in heading atmosphere and the graphic closing frame.
- Use 12px/16px mono chapter markings with an orange index and faint uppercase descriptor.
- Align commercial facts across contiguous columns and give only the recommended choice a pale orange wash.
- Keep the final status signal blue and small, separated from orange conversion actions.

### Don't

- Do not turn medium-weight 500 headings into heavy 700 display blocks.
- Do not replace the neutral page architecture with dark panels or multicolor feature backgrounds.
- Do not round every architectural cell to match the 20px floating instrument; most shared-rule cells stay square.
- Do not use pill-shaped primary CTAs merely because small filters and diagram labels are pills.
- Do not apply broad floating shadows to every feature and footer cell; elevation distinguishes usable instruments.
- Do not expand tiny outline icons into a colorful illustration system; use 18px to 24px functional marks.
- Do not use orange for every numeric table value; reserve it for key outcomes and recommendations.
- Do not end immediately after a conversion button; preserve the graphic brand/proof region and technical directory.

## Motion and responsive

### Motion

**Observed:**

- Declared color and background transitions commonly use 0.2s ease; primary and secondary actions declare a 0.2s transition with scale and box-shadow at 0.1s.
- Primary actions declare an active scale of 0.995, secondary actions 0.99; navigation items have a 50ms all-property transition.
- Character architecture declares a 7s alternating illumination animation with cubic-bezier(0.455,0.03,0.515,0.955). Spinner rotations declare 1s linear infinite.

**Transfer:**

- Keep button motion subtle and tactile. Let the character hall gently change illumination rather than moving the text or central actions.
- Preserve the clarity of the white technical objects while limiting animation to meaningful progress and background texture.

**Unknown:**

- Full scroll-animation choreography, exact canvas animation behavior and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints including 575px/576px, 767px/768px, 995px/996px, 1199px/1200px and 1279px.
- The shared container is capped at 1112px with 16px side clearance. Integration layouts declare two columns at their wide layout; header navigation is hidden below its wide layout.

**Transfer:**

- On narrow screens, stack paired demonstration cells while preserving their shared rail language and technical labels.
- Keep the compact instrument within the viewport and move decorative grid and ASCII volume toward the side edges, preserving a clean text center.
- Allow pricing comparisons to remain scannable through stacked plans or a contained horizontal table; do not shrink 14px text to fit all columns.

**Unknown:**

- Exact mobile type recipes, menu interaction, pricing-table behavior and artwork recomposition are not established; the narrow-layout transfer rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
