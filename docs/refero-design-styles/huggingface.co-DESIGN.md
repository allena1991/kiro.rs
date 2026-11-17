# Hugging Face — community meets workbench

## Overview

An approachable technical style that combines a bright, busy community directory with carefully staged product marketing. White and cool gray dominate, punctuated by near-black product stages, colorful miniature applications and cheerful illustration. Humanist sans-serif typography, monospaced resource names, real interface imagery and small public activity counts make it feel useful rather than luxurious. Spacious chapter introductions alternate with dense, practical grids and tables.

### Essentials

- A human headline beside a working product: the default opening pairs a 48px/1 bold humanist headline with a dark interface scene inside a 1248px-wide, 620px-tall stage with 25px corners and 80px inner padding.
- The site feels inhabited, not merely advertised: include compact resource or member cards with names, activity metadata and small counts; use 62px resource rows, 8px corners and 15px monospaced identifiers rather than giant testimonial quotations.
- Darkness is a stage, not the whole site: keep the ordinary canvas white, reserve #0b0f19 for the opening and a featured capability panel, and concentrate saturated color in small application cards, icons and artwork. Most reading sections remain neutral.
- Actions are modest tools: the opening uses a 42px outlined pill beside an underlined browse link; navigation uses a 30px dark pill, while ordinary in-card actions use 34px height and 8px corners.
- Product proof is softly integrated: interface images fill the bottom of 12px-corner cards with 32px text padding, light 1px edges and only a 0px 1px 2px shadow. Include a floating geometric capability scene with translucent 8px-corner labels as the counterpart to literal UI.
- A friendly illustrated flourish balances the technical density: include a clustered sticker-like illustration device, with white outlines and overlapping rotated shapes; it can form a 1248px-wide, 249px-tall closing mound above a restrained five-column footer. Use product-relevant symbols when there is no mascot.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page background, card faces and reversed stage text. |
| Soft gray backing | `#f9fafb` | `--color-wash` | surface | Pale interface-image backing and the start of small organization-card fades. |
| Faint edge and header wash | `#f3f4f6` | `--color-faint` | border, surface | Resource card edges, footer divider and compact data table headers. |
| Card edge | `#e5e7eb` | `--color-rule` | border, surface, text | Card outlines, dashed comparisons, light secondary action fills and dark-panel headings. |
| Light gray | `#d1d5dc` | `--color-disabled` | text, surface | Low-emphasis data and subdued reversed support text; the opening uses this hue at 80% opacity. |
| Metadata gray | `#99a1af` | `--color-metadata` | text | Activity metadata, prices beside actions and dark-panel support copy. |
| Muted gray | `#6a7282` | `--color-muted` | text | Feature descriptions, secondary links and support lines. |
| Secondary slate | `#4a5565` | `--color-secondary` | text, border | Support copy, footer links and the outlined opening action edge. |
| Cool headline ink | `#101828` | `--color-ink` | text, action | Dark action fills and headline ink in structured commercial sections. |
| Midnight stage | `#0b0f19` | `--color-stage` | background | Opening product stage and the lower end of the featured dark panel. |
| Plain black | `#000000` | `--color-black` | text, action | Core chapter titles, resource names and ordinary black action fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and comparison pages | Information blue | `#155dfc` | `--color-blue` | text, link, accent | Technical category labels and comparative value markers, not the default CTA fill. |
| comparison tables | Performance green | `#009966` | `--color-green` | accent, text | Positive performance markers paired with pale green status backgrounds. |
| pricing pages | Hardware violet | `#7f22fe` | `--color-violet` | text, accent | Hardware category label; paired with a 10% violet wash. |

## Typography

- **Source Sans Pro** — All marketing headings, descriptions, navigation and actions. Open humanist sans-serif with narrow, practical proportions and friendly double-storey lowercase. Font stack: "Source Sans Pro", -apple-system, system-ui, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif.
- **IBM Plex Mono** — Resource identifiers, technical names and quantitative tables. Distinctly engineered monospace that gives long identifiers and numerical comparisons a workbench character. Font stack: "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Source Sans Pro | 700 | 48px | 1 | normal | Default white opening headline, balanced into two lines. |
| heading | Source Sans Pro | 700 | 30px | 1.2 | normal | Centered chapter introductions. |
| panel-heading | Source Sans Pro | 600 | 24px | 32px | normal | Featured capability-panel titles. |
| feature-heading | Source Sans Pro | 600 | 20px | 1.4 | normal | Interface feature-card titles and utility-page title. |
| project-heading | Source Sans Pro | 700 | 20px | 1.25 | normal | Project tile headings beside a tiny colored dot. |
| lead | Source Sans Pro | 400 | 18px | 28px | normal | Opening support copy, chapter subtitles and small public counts. |
| group-heading | Source Sans Pro | 600 | 18px | 28px | normal | Directory column titles and footer column headings. |
| body | Source Sans Pro | 400 | 16px | 1.5 | normal | Paragraphs, navigation and ordinary links. |
| button | Source Sans Pro | 400 | 16px | 1 | normal | Opening and navigation pills. |
| resource-name | IBM Plex Mono | 400 | 15px | 24px | normal | Single-line resource identifiers in compact discovery cards. |
| caption | Source Sans Pro | 400 | 14px | 20px | normal | Small utility controls, plan annotations and card metadata. |
| chip | Source Sans Pro | 600 | 14px | 20px | normal | Translucent capability labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| enterprise landing pages | commercial-display | Source Sans Pro | 700 | 72px | 1 | -0.025em | Centered enterprise opening headline. |
| commercial pages | compact-display | Source Sans Pro | 700 | 48px | 1 | -0.025em | Centered pricing promise and a highlighted phrase in enterprise closing copy. |
| pricing pages | commercial-heading | Source Sans Pro | 700 | 36px | 40px | normal | Left-aligned category introductions. |
| pricing pages | plan-price | Source Sans Pro | 900 | 36px | 40px | normal | Plan prices, with a much smaller billing qualifier aligned to the baseline. |
| pricing pages | category-pill | Source Sans Pro | 600 | 15px | 1.5 | normal | Colored category badges above commercial headings. |
| comparison and hardware tables | table | IBM Plex Mono | 400 | 14px | 20px | normal | Technical identifiers and values. |
| comparison and hardware tables | table-heading | IBM Plex Mono | 600 | 14px | 20px | normal | Sortable comparison column names and emphasized rates. |
| enterprise comparison tables | table-category | Source Sans Pro | 500 | 12px | 16px | 0.05em, uppercase | Grouped comparison category labels. |

**Notes:**

- The default display keeps normal tracking; the centered commercial variant tightens to -0.025em. Do not apply that tightening to every heading.
- Sans-serif performs the narrative work; monospace is reserved for identifiers and comparable technical values, not all supporting copy.
- Most descriptions use regular weight, including numerical popularity counts. Heavy 900-weight numerals belong to plan pricing, not a general oversized-stat treatment.

## Layout

**Density:** Airy chapter transitions frame compact, useful content. Text-to-text gaps are small; section-to-section gaps and media stages are much more generous.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-subtitle separation, compact row padding and footer list spacing. |
| 12px | Small card-grid gaps and glass-list inner padding. |
| 16px | Container side padding and heading-to-paragraph gaps in commercial panels. |
| 20px | Project grid gaps and commercial feature-card padding. |
| 24px | Discovery column gaps and project-tile padding. |
| 32px | Feature-grid gaps, feature text padding and copy-to-action spacing. |
| 40px | Featured panel text padding and opening headline-to-support gap. |
| 44px | Opening support-to-action gap and hardware intro padding. |
| 56px | Opening offset below navigation and commercial category-panel padding. |
| 80px | Opening stage inner padding and discovery section top padding. |
| 96px | Chapter-introduction vertical padding. |
| 128px | Major chapter separation and footer bottom padding. |

### Containers and grids

- **container**: max width 1280px · side padding 16px. Centered outer container; at a 1440px viewport its usable width is 1248px.
- **feature-grid**: max width 1024px · 3 columns · gap 32px. Inset bento grid with alternating two-column and one-column cards; reverse the spans in the next row.
- **discovery-grid**: 3 columns · gap 24px. Equal resource columns across the main container.
- **project-grid**: max width 1152px · 4 columns · gap 20px. Slightly staggered project tiles; support text rests at the bottom.
- **footer-grid**: 5 columns · gap 32px. One theme-control column followed by four link columns.
- **commercial-frame** (only for commercial pages): max width 1280px · side padding 16px. Continuous side rails, horizontal separators and small circular junction marks; pricing divides into three plans and enterprise features into three columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | stage | 25px |
|  | feature-cards | 12px |
|  | resource-cards-and-labels | 8px |
|  | project-tiles | 25.6px |
|  | pills | 9999px (pill) |
| pricing pages | plan-action-frame | 14px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Subtle grounding beneath white feature and resource cards. |
| project-tile | `0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | Raised project tiles over a pastel atmospheric backing. |
| search-inset | `inset 0px 2px 4px 0px rgba(0,0,0,0.05)` | Navigation search field. |

### Surfaces

#### Canvas · level 0

**Use:** Default page background.

**CSS:** `background: #ffffff; color: #000000`

#### Dark stage · level 1

**Use:** Default opening product presentation.

**CSS:** `background: #0b0f19; border-radius: 25px; padding: 80px`

**Observed:** Near-black, cool and flat; interface detail and a faint localized glow create depth rather than a bright all-over gradient.

**Transfer:** Keep text on a stable dark field while the main object occupies the opposite half.

#### Feature card · level 1

**Use:** Bento capability proof.

**CSS:** `background: #ffffff; border: 1px solid #e5e7eb; border-radius: 12px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05); overflow: hidden`

**Observed:** Real UI imagery reaches card edges below the text block.

**Transfer:** Use a coherent piece of product UI rather than a decorative icon in every card.

#### Glass list · level 1

**Use:** Backing for grouped compact discovery cards.

**CSS:** `background: rgba(255,255,255,0.4); border-radius: 12px; padding: 12px; backdrop-filter: blur(16px)`

**Observed:** Nearly invisible on white; soft pastel light is visible through it.

**Transfer:** Place on an atmospheric backing, never a saturated glass dashboard.

#### Featured capability stage · level 1

**Use:** A commercial capability interrupt within a light page.

**CSS:** `background: linear-gradient(#101828, #0b0f19); border-radius: 12px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Observed:** A wide dark rectangle with small text at left and gray solids protruding beyond its edges.

**Transfer:** Retain the object overflow and small floating labels.

#### Ruled commercial panel · level 0

**Only for:** commercial pages

**Use:** Continuous commercial page structure.

**CSS:** `background: #ffffff; border-left: 1px solid rgba(229,231,235,0.7); border-right: 1px solid rgba(229,231,235,0.7)`

**Observed:** Dashed internal divisions contrast with solid outside rails; occasional 135-degree hairline hatch bands and tiny white circular intersections give a technical drawing quality.

**Transfer:** Keep the rules pale enough that the content leads; build hatch with transparent 4px bands and a 1px rgba(229,231,235,0.6) stripe.

## Components

### Navigation

**Use:** Compact shared orientation and utility bar.

**CSS:** `height: 65px; background: #ffffff`

**Text style:** `body` — Source Sans Pro 400 · 16px/1.5

**Observed:** A small illustrated mark and bold word label lead into a search field; compact icon-and-text category links follow, then login and the Navigation signup pill. Main content aligns to the same container.

### Hero action

**Use:** Default main opening action on the dark stage.

**CSS:** `height: 42px; padding: 0px 21.6px; border: 1px solid #4a5565; border-radius: 9999px; background: linear-gradient(to right, rgba(255,255,255,0), rgba(255,255,255,0.05), rgba(255,255,255,0)); color: #ffffff; display: inline-flex; align-items: center`

**Text style:** `button` — Source Sans Pro 400 · 16px/1

**Observed:** Paired with a low-emphasis conjunction and a separate underlined browse link; a small soft white glow sits behind the action.

**Transfer:** Use a destination verb, not an inflated conversion slogan.

### Navigation signup

**Use:** Small persistent conversion control.

**CSS:** `background: #101828; color: #ffffff; border: 1px solid transparent; border-radius: 9999px; padding: 4px 12px; height: 30px`

**Text style:** `button` — Source Sans Pro 400 · 16px/1

**Observed:** Much smaller than a commercial conversion button; sits at the end of navigation.

**States:** Declared: hover border-color #000000, background-color #ffffff and color #000000; focus-visible not specified.

### Search input

**Use:** Search-first navigation utility.

**CSS:** `background: #ffffff; border: 1px solid #e5e7eb; border-radius: 8px; height: 36px; padding: 8px 12px 8px 32px; box-shadow: inset 0px 2px 4px 0px rgba(0,0,0,0.05)`

**Observed:** Small muted search glyph occupies the left inset; field is 325px wide at desktop.

### Interface feature card

**Use:** Explain a capability through visible product proof.

**CSS:** `background: #ffffff; border: 1px solid #e5e7eb; border-radius: 12px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05); overflow: hidden; height: 420px`

**Text style:** `feature-heading` — Source Sans Pro 600 · 20px/1.4

**Observed:** Title and a short muted paragraph sit above a large interface image, with 32px padding around text. Wide and narrow spans alternate across a three-column grid.

**Transfer:** Choose one recognizable workflow per card and let the UI fade gently into the surrounding white.

### Resource row

**Use:** Make a community or catalog feel active.

**CSS:** `background: #ffffff; border: 1px solid #f3f4f6; border-radius: 8px; height: 62px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `resource-name` — IBM Plex Mono 400 · 15px/24px

**Observed:** A single-line identifier sits over muted recency and tiny download/like counters; long names truncate. App variants replace the white face with a vivid diagonal gradient and white sans-serif text.

**Transfer:** Use real catalog names and live-seeming, truthful metadata rather than placeholder slogans.

### Project tile

**Use:** Show a maintained ecosystem with modest quantitative proof.

**CSS:** `background: rgba(255,255,255,0.8); border: 1px solid #f3f4f6; border-radius: 25.6px; padding: 24px; height: 224px; display: flex; flex-direction: column; box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `project-heading` — Source Sans Pro 700 · 20px/1.25

**Observed:** An 8px color dot leads the title; an 18px regular count and tiny repository icon sit just below. A short description anchors the lower part; rows are slightly staggered.

**Transfer:** Use usage, contributions or integrations as the proof without turning the number into the headline.

### Floating capability label

**Use:** Connect abstract geometry to concrete functionality.

**CSS:** `background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.1); border-radius: 8px; padding: 8px 16px; backdrop-filter: blur(4px); color: #ffffff`

**Text style:** `chip` — Source Sans Pro 600 · 14px/20px

**Observed:** Labels are scattered among geometric solids rather than packed into a toolbar.

**States:** Declared: hover background-color rgba(255,255,255,0.15); focus-visible not specified.

### Theme control

**Use:** Small utility at the beginning of the footer.

**CSS:** `background: #ffffff; border: 1px solid #f3f4f6; border-radius: 9999px; padding: 4px 10px 4px 8px; color: #6a7282; height: 30px`

**Text style:** `caption` — Source Sans Pro 400 · 14px/20px

**Observed:** A small monitor-like glyph precedes the label. It is visually subordinate to the footer column headings.

### Footer columns

**Use:** Default marketing-page ending.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); gap: 32px`

**Text style:** `body` — Source Sans Pro 400 · 16px/1.5

**Observed:** Theme control in the first column; four groups of plain slate links in the others, with 18px semibold headings, 8px list spacing, 48px top padding and 128px bottom padding. A faint top rule separates it from the page.

**Transfer:** Keep the footer functional and open; a compact single-row footer belongs to dense utility listings instead.

## Imagery and graphics

### Working product stage

**Use:** The dominant object in the default opening.

**Observed:** A dark product directory is tilted slightly in perspective on the right, rising above the top of the main rounded stage and filling roughly its right half. Dense lists, small colored provider marks and muted controls remain subordinate to the large white headline at left; the bottom fades into the stage.

**Transfer:** Use a real dark-mode workflow, or construct a credible static interface with a filter column and activity list. Preserve the angled slab, readable hierarchy and restrained color, not the original data.

**Build:** Place an interface panel about 730px wide and 650px tall on the right of the 1248px stage. Apply a mild perspective rotation and skew, rounded top corners and a bottom linear mask to transparency; use #0b0f19 and translucent white rules. Layer a very faint radial white glow behind it.

### Soft atmospheric backing

**Use:** Behind compact discovery lists and project grids.

**Observed:** Broad, low-opacity lavender, blush and cool-gray elliptical clouds barely tint the white page. White cards stay crisp above them; top and bottom fades dissolve the backing.

**Transfer:** Always include this soft-light device around one dense card collection; match the softness rather than making the page a rainbow.

**Build:** Use an absolutely positioned ellipse about 1180px wide and 470px tall with border-radius:50% and blur(40px). Layer rgba(180,170,220,0.18), rgba(245,190,210,0.14) and transparent white gradients; add white masks at the section edges.

### Geometric capability sculpture

**Use:** Featured capability scene and commercial opening decoration.

**Observed:** Faceted gray cubes and banded cylinders float at different sizes and angles. Large solids overlap the panel boundary; small blurred pieces recede behind translucent labels. Light commercial openings reuse the same neutral objects around centered text.

**Transfer:** Recreate a restrained set of product-relevant solids; use flat isometric SVG faces if full 3D is unavailable.

**Build:** Draw three-face cubes in SVG using #ffffff, #99a1af and #4a5565 polygons; cylinders use two elliptical ends and a gray side band with a white stripe. Rotate and distribute 30px–180px objects, with one larger foreground form, several small distant forms and selective 1px–3px blur. Keep saturation out of the solids.

### Interface proof images

**Use:** Feature bento cards and commercial capability grids.

**Observed:** Light interface views show activity feeds, code, profiles, configuration panels and charts. They are clipped to a card, often fade toward white and occupy more space than their title and one-sentence description. A storage illustration introduces colorful isometric blocks within the otherwise neutral commercial grid.

**Transfer:** Choose realistic UI views with legible structure, not enlarged invented microcopy. Keep screenshot internals at product-UI scale.

### Sticker mound

**Use:** A friendly illustrated counterweight to the technical content and the default marketing close.

**Observed:** A low, wide pile of cheerful yellow mascot stickers overlaps densely, with white cutout outlines, orange edging and varied rotations; its lower edge is clipped cleanly by the footer boundary.

**Transfer:** Use original product symbols or friendly illustrated tools. The minimum equivalent is a collection of custom flat SVG badges with white outlines, varied expressions or motifs, and overlapping rotations.

**Build:** Arrange 40px–110px SVG stickers in several overlapping rows inside a 1248px by 249px clipped region. Raise the center into a shallow mound, rotate pieces roughly -25 to 25 degrees, outline each in white, and use a warm yellow/orange art palette with dark details. Repeat a small family of motifs rather than one identical icon.

### Commercial decorative drafting

**Only for:** commercial pages

**Use:** Subtle texture around commercial openings, section separators and closing panels.

**Observed:** Very pale monospaced mathematical or geometric glyph fields fade behind text. Thin diagonal hatching and tiny circles mark the ruled layout; these remain decorative rather than actual product controls.

**Transfer:** Use a low-contrast symbol field or hatch to convey technical structure without adding dashboard clutter.

**Build:** Repeat small neutral glyphs on an 18px vertical pitch, mask them out behind primary text and fade toward white at the edges. For separators, repeat a transparent 4px stripe and 1px rgba(229,231,235,0.6) stripe at 135 degrees.

### Iridescent plan action

**Only for:** pricing pages

**Use:** Personal premium plan action and its closing upgrade panel.

**Observed:** A pastel pink-to-mint-to-yellow diagonal button, surrounded by a thin colored frame, a white inset line and one tiny sparkle at the upper left. Small round avatars form a softly edge-faded ribbon beneath the final offer.

**Transfer:** Reserve this exceptional color treatment for a distinct personal upgrade, not all primary actions.

**Build:** Use a 14px-radius outer frame with 2px padding and a diagonal pink/mint/yellow gradient. Put a 48px-high, 12px-radius action inside with a 2px white border, then overlap a 24px four-point sparkle at the upper-left corner.

### Icons

**Observed:** Small filled SVGs dominate, typically 12px–18px in muted gray, with 16px navigation glyphs and compact provider avatars. Pricing checkmarks use 16px outlines with 2px round strokes. Emoji-like accents add warmth to discovery and illustration.

**Transfer:** Use restrained filled utility icons for resource metadata, small original avatars for entities and occasional friendly pictorial symbols. Do not replace every section heading with a large outline icon.

## Section recipes

How recurring sections are built.

### First screen: Dark product-stage opening

**Observed:** A 65px white Navigation sits above a 56px gap. The centered 1248px-wide Dark stage is 620px tall, with a 512px text column inset 80px at left. A small friendly pictorial mark precedes the 48px bold, two-line white headline; an 18px muted support line follows after 40px, with Hero action and an underlined browse link another 44px below. Back to front: near-black rounded stage, faint glow, right-hand angled Working product stage, then left-hand copy and actions. The interface rises slightly above the panel and nearly fills the right half. Within 900px, the full stage, headline, support, actions and main interface are visible; the next discovery-section label just starts below, while its lists remain below the fold.

**Transfer:** Use a concise shared-purpose promise and an original friendly mark with a credible product workflow at right. If no product imagery exists, build a static filter-and-results view. Commercial pages instead use a light centered opening, larger tight-tracked type and neutral floating solids; utility listings open with a compact title toolbar immediately above data.

**Avoid:** Do not use a full-bleed black page, a centered giant headline that displaces the interface, or a tiny isolated screenshot floating in unused space.

**Text style:** `display` — Source Sans Pro 700 · 48px/1

### Chapter heading pair

**Observed:** A centered 30px bold heading and an 18px muted subtitle separated by 8px. Tiny neutral pictorial marks and fading hairlines act as chapter ornaments; 96px vertical padding and very pale elliptical gray transitions separate dense collections.

**Transfer:** Use a short conceptual chapter title followed by a single practical sentence, then move into proof cards.

**Text style:** `heading` — Source Sans Pro 700 · 30px/1.2

### Active directory collection

**Observed:** Three equal discovery columns with 24px gutters; each has an 18px semibold centered icon/title, a Glass list of five Resource rows, and a browse link below. One column carries saturated app gradients while the flanking identifiers stay white and monospaced.

**Transfer:** Group three useful object types, keeping one visibly expressive and the other two neutral. Counts and recency make the section feel maintained.

### Alternating interface bento

**Observed:** A 1024px-wide, three-column grid with 32px gaps; one 672px card beside one 320px card, reversing the proportions in the next row. Interface feature card text remains at top and product proof occupies the lower area.

**Transfer:** Alternate broad workflows and narrow supporting capabilities rather than making four identical icon cards.

### Capability stage with tangible geometry

**Observed:** A Featured capability stage spans the inset 1024px grid at 450px height. Its left third contains a 24px semibold title, support copy and a light action. Geometric capability sculpture fills the other two thirds, with Floating capability labels and several objects crossing the edges. Two light product cards follow; a compact four-column organization grid supplies proof.

**Transfer:** Contrast one serious commercial offer with friendly abstract geometry, then substantiate it with practical product cards.

### Ecosystem proof and illustrated close

**Observed:** Project tiles occupy four columns over Soft atmospheric backing, with understated counts and colored title dots. Lower rows dissolve toward white, then Sticker mound creates a warm illustrated ending directly above Footer columns.

**Transfer:** Use a collection of maintained resources or integrations and an original sticker family. The illustration is a character device, not another sales headline.

### Light commercial opening

**Only for:** commercial pages

**Observed:** Centered tight-tracked headline within a 1280px ruled frame, pale glyph texture and floating neutral solids around its perimeter. Enterprise uses 72px display, 24px support and paired 48px pill actions with a white outer ring; pricing uses a shorter 48px promise and 20px support above plan columns.

**Transfer:** Use the light variant for a focused commercial decision and retain the default darker stage for broad product storytelling.

**Text style:** `commercial-display` — Source Sans Pro 700 · 72px/1 · tracking -0.025em

### Commercial features and comparison

**Only for:** enterprise landing pages

**Observed:** A three-column capability grid uses pale dashed divisions, 20px padding, broad light UI images above 18px semibold titles and 14px descriptions. Comparison follows with grouped 12px uppercase labels, roughly 63px rows, pale dashed rules, green checks and left-aligned descriptions against centered plan values.

**Transfer:** Let features establish meaning before a dense comparison; use a larger two-column visual span for one especially tangible capability.

### Commercial final invitation

**Only for:** enterprise landing pages

**Observed:** A centered 48px closing line returns to the opening promise, with one phrase using a black-to-gray text gradient. A 24px support line and paired 48px actions sit over a faint dot field. Three horizontal rows of small organization cards with avatars, plan badges and metadata follow before Footer columns.

**Transfer:** Restate the buyer's desired identity without introducing new technical claims; follow with compact social proof rather than a wall of logos.

### Plan and usage pricing

**Only for:** pricing pages

**Observed:** Three flush 412px plan columns sit inside the ruled frame, with 20px names, 36px heavy prices and 48px full-width actions. A small blue popular badge marks a team plan while the personal plan gets the Iridescent plan action. Further categories pair colored pills, 36px headings, 18px support and pale tinted diagrams or small price cards; hardware rates become 14px mono tables with 37px or 45px rows. The ending returns to a compact upgrade offer at left, an avatar ribbon below and a fine-rule benefit matrix at right, then Footer columns.

**Transfer:** Separate subscription choice from usage-based detail; preserve explicit units and a distinct final upgrade panel.

### Data-first utility listing

**Only for:** utility comparison pages

**Observed:** A compact 20px semibold title and 20px support phrase share a toolbar with pale pill links; a 34px filter field precedes gray table headers. Roughly 29px–30px rows use 14px mono text, solid 1px rules and tiny blue/green status markers. The table header remains visible during scrolling. After the last row and a generous white gap, a 56px single-row footer carries theme, legal links, a small center mark and product links.

**Transfer:** For comparison utilities, lead with filtering and data rather than a promotional stage. Keep the marketing footer and illustrated close out of this specialized page type.

**Text style:** `table` — IBM Plex Mono 400 · 14px/20px

## Page flow

**Storyline:** Shared-purpose promise → active product proof → capability chapters → commercial path → ecosystem or buyer proof → characterful or decision-focused close → practical navigation.

### Broad product and community discovery

1. **Promise** — Dark split stage with human headline and an angled working interface.
2. **Activity proof** — Three compact resource lists with real recency and public counts.
3. **Capability chapters** — Centered chapter introductions and alternating wide/narrow interface cards.
4. **Commercial path** — Dark geometry-led offer, paired light product cards and compact organization proof.
5. **Ecosystem proof** — Staggered project tiles with modest popularity counts.
6. **Closing character** — Overlapping illustrated sticker mound above five-column footer.

**Transfer:** Balance tangible product usefulness with an inhabited community feeling; keep chapter order adaptable.

### Fast technical comparison

1. **Orientation** — Small title toolbar, utility links and filter.
2. **Product comparison** — Long sortable mono data table, sticky headers and small performance markers.
3. **Ending** — Last table rows lead into a compact one-line footer, not another promotion.

**Transfer:** Let the comparison itself be the product proof and keep decoration outside the data area.

### Organizational purchase confidence

1. **Promise** — Centered light commercial opening with floating gray solids and paired subscription/sales paths.
2. **Capability proof** — Dashed three-column UI-image grid with one wider illustrated feature.
3. **Pricing and objection handling** — Grouped feature-comparison matrix with short explanations and centered availability values.
4. **Closing call** — Return to a large centered invitation and the same two actions over a dot field.
5. **Social proof and ending** — Three organization-card ribbons, small decorative punctuation, then full footer.

**Transfer:** Explain controls visually, compare plainly, and repeat the two buyer paths without turning the entire page into a lead form.

### Subscription and usage-price selection

1. **Promise** — Short centered light headline above three flush plan columns.
2. **Pricing** — Large prices, explicit billing units, feature lists and full-width plan actions.
3. **Usage explanation** — Storage cost illustration and small volume cards, then a capability introduction with interface tiles.
4. **Detailed comparison** — Hardware category introductions followed by long monospaced rate tables.
5. **Closing offer** — Personal upgrade panel with pastel action, avatar strip and small benefit matrix.
6. **Ending** — Full five-column footer.

**Transfer:** Make plan choice quick, leave detailed metering lower down, then close with a focused offer rather than duplicating the entire plan grid.

## Writing

Friendly, practical and community-minded, with technical specificity treated as normal language. Confidence comes from visible functions, explicit quantities and useful verbs rather than ornate brand rhetoric.

**Do not copy:** Do not reuse the brand name, mascot, proprietary marks, customer identities, repository names, prices, popularity counts or numerical claims. Source quotations are voice examples only; replace them with truthful facts and original wording for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for benefits and actions; we for the product team's contributions. Short interface labels can be impersonal nouns.
- **Rhythm:** Most headlines are short sentence-case phrases; support is usually one complete sentence. Feature descriptions are concise and direct, while technical plan details use compact noun phrases and explicit units.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name a shared aspiration in a plain declarative sentence. | 6–10 words | “The AI community building the future.” |
| Chapter title | Short verb-led or place-like framing. | 3–7 words | “Accelerate your ML”<br>“The Home of Machine Learning” |
| Support line | A useful action sequence rather than a second grand claim. | 7–18 words | “Create, discover and collaborate on ML better.”<br>“Start for free. Upgrade for more control, capacity, and support.” |
| Feature description | Verb plus concrete capability and its practical outcome. | 8–20 words | “Connect securely to your identity provider with SSO integration.” |
| Action | Destination or next step, with a specific object. | 2–5 words | “Explore AI Apps”<br>“Contact sales for Enterprise” |
| Pricing chapter | Concrete service plus a starting price or a plain pricing principle. | 3–9 words | “Transparent, volume-based pricing”<br>“On-demand GPU hardware. Starting at $0.” |

**Words and phrasing to use:** build; explore; collaborate; community; host; deploy; your team; starting at; included; per user per month

**Avoid:** revolutionary magic; unparalleled synergy; luxury; exclusive elite; frictionless everything

**Rules:**

- Give every benefit a concrete product noun or observable action.
- Use exact billing units and distinguish included capacity from paid extensions.
- Allow technical vocabulary without translating every term into marketing euphemisms.
- Keep public counts adjacent to their objects; they are small proofs, not unsupported headline claims.

## Do's and Don'ts

### Do

- Keep the ordinary canvas white and confine deep #0b0f19 stages to focal product moments.
- Use 48px/1 weight-700 normal-tracked type for the default opening.
- Pair 30px chapter headings with 18px support at an 8px gap.
- Use 32px gaps and alternating one/two-column spans for the interface bento.
- Keep discovery cards compact at 62px height with 8px corners.
- Retain modest 18px regular-weight public counts beneath 20px project titles.
- Let gray geometric objects cross the edge of a 12px-corner capability panel.
- Finish broad marketing pages with an original clustered illustration and the open five-column footer.

### Don't

- Do not turn all CTAs into iridescent buttons; that exception belongs to personal-plan pricing.
- Do not apply 72px centered commercial typography to ordinary feature-card titles.
- Do not use pill corners on every card; resource rows use 8px and feature panels use 12px.
- Do not turn public activity counts into oversized bold display statistics.
- Do not replace dense technical comparison tables with spacious decorative cards when the task is comparing values.
- Do not flatten all content into the 1280px outer width; the 1024px feature inset is an important composition change.
- Do not darken all product-proof images to match the opening; most feature demonstrations are pale and integrated into white.
- Do not strengthen faint dividers into black grid lines or heavy drop shadows.

## Motion and responsive

### Motion

**Observed:**

- Declared card transform transitions use .15s cubic-bezier(.4, 0, .2, 1); floating labels use 0.2s on all properties.
- Declared floating-object bouncing cycles range from 7s to 13s with ease.
- Declared organization ribbons run 45s linear, alternating direction; the pricing avatar ribbon runs 90s linear.
- Compact signup actions invert from dark to white on hover; ordinary footer links underline.

**Transfer:**

- Use slow independent floating cycles only for the geometric scene, and long linear ribbon motion only for compact proof cards or avatars.
- Keep hover responses short and local; the interface and copy remain stable while decoration moves.

**Unknown:**

- Exact floating keyframe paths, animation start phases and unreported focus-visible treatments are unknown.

### Responsive

**Observed:**

- The opening becomes centered and overflow-clipped below its large-screen layout; feature grids declare single-column bases, and footer grids declare two-column then five-column variants.
- The comparison table has a horizontal overflow wrapper and truncates long identifiers; some explanatory comparison captions are hidden in narrow layouts.

**Transfer:**

- On narrow screens, stack copy before the main interface and retain a cropped dark stage rather than shrinking the entire desktop composition.
- Stack bento cards and commercial plans while keeping their internal title/media order; let dense quantitative tables scroll horizontally.
- Keep a reduced sticker mound above the footer and reduce the number of floating solids so they do not cover copy.

**Unknown:**

- Exact breakpoint widths, mobile typography and final mobile art positioning are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
