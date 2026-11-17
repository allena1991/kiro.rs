# Hume — human signals, scientific instruments

## Overview

A research-led technology style that pairs humane geometric sans typography with the markings of scientific instruments. Mostly white and cool pale gray, it switches to deep black for immersive demonstrations and luminous, multicolored data art. Fine rules, square panels and sparse diagrams keep the content orderly, while soft particle fields and a glowing halftone finale add emotional warmth. It suits complex infrastructure, developer products and research stories with substantial explanatory content.

### Essentials

- Human-scale headlines sit inside machine-like framing: Fellix at 72px/1, weight 400 and -0.05em tracking for the main promise; section titles use 48px/1.25 and -0.025em, never heavy display weights.
- The opening is an immersive black stage, not a floating app card: a 768px-tall field holds a left-aligned 576px headline column and a colorful particle object sweeping through the right half, with a black veil protecting the copy. Use a custom SVG point cloud when no equivalent product media exists.
- Actions look like rectangular instrument controls: 44px height, 20px side padding, 14px/20px medium sans, square corners; white primary and transparent white-outline secondary on black, near-black primary on light.
- Color is a signal, not the page paint: most reading sections are #ffffff or #f7f8fa; mint → blue → violet → peach is concentrated in data marks, thin accents and atmospheric dark stages rather than saturated card fills.
- Explanations are staged as annotated specimens: 1px borders, uppercase 12px/16px mono labels with 0.1em tracking, schematic waveforms or point fields above restrained text, and 24px gutters between square cards.
- A luminous halftone field and monumental centered closing line are signature devices: 72px/1 white type over a black-to-spectrum lower glow with dots massed at the edges. Recreate with SVG dots and a blurred gradient, then continue into a black, ruled directory footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Spectrum blue | `#3452aa` | `--color-spectrum-blue` | accent | Second spectrum stop, between mint and violet. |
| Spectrum mint | `#4ebc9c` | `--color-spectrum-mint` | accent | First stop of the continuous spectrum used in signal graphics and atmospheric light. |
| Spectrum violet | `#6e50aa` | `--color-spectrum-violet` | accent | Third spectrum stop; never a general-purpose panel fill. |
| Spectrum peach | `#d29c7c` | `--color-spectrum-peach` | accent | Warm end of spectrum marks and light fields. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface, text, action | Reading canvas, diagram fields and reversed primary actions; full-strength headings on black. |
| Stage black | `#000000` | `--color-black` | background, text | Immersive stages, closing field and footer; text on white actions. |
| Near-black ink | `#0a0a0a` | `--color-ink` | text, action, border | Primary text and strong panel outlines on light; filled primary controls in light sections. |
| Dark-stage hairline | `#242424` | `--color-reverse-edge` | border | Visible white at 14% on black for footer separators; table lines use 10%, panel edges 15–20% and outlined controls 40%. |
| Slate text | `#5b6470` | `--color-muted` | text | Body copy and technical labels on light. |
| Reversed label gray | `#999999` | `--color-reverse-label` | text | Visible white at 60% on black for mono labels. |
| Reversed body gray | `#b3b3b3` | `--color-reverse-body` | text | Visible white at 70% on black for paragraphs and directory links; hero support uses white at 75%. |
| Secondary rule | `#dadde2` | `--color-rule-strong` | border | Stat rules, small tags and underlined links. |
| Fine panel edge | `#e6e8eb` | `--color-rule` | border, surface | Faint card outlines and row separators. |
| Cool pale gray | `#f7f8fa` | `--color-band` | background, surface | Alternating explanatory bands and card text decks. |

## Typography

- **Fellix** — All headings, prose, actions and navigation. Rounded geometric sans with single-storey forms and open circular counters; regular display weight feels human rather than institutional. If unavailable, use **Outfit**. Use 400–500 and retain tight tracking; compare line wraps before adjusting width. Font stack: "Fellix", "Outfit", system-ui, sans-serif.
- **PP Fraktion Mono** — Eyebrows, metric values, numbered annotations and figure captions. Compact utilitarian monospace that provides a technical counterpoint to the rounded sans. OpenType features: "calt" 0, "liga" 0. If unavailable, use **IBM Plex Mono**. Use 400–500; keep uppercase tracking and disabled ligatures. Font stack: "PP Fraktion Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Fellix | 400 | 72px | 1 | -0.05em | Main marketing promise and monumental centered closing calls. |
| heading | Fellix | 400 | 48px | 1.25 | -0.025em | Section leads on light and dark; allow balanced two-line statements. |
| stat | PP Fraktion Mono | 400 | 36px | 1 | -0.05em | Prominent compact quantitative proof. |
| lead | Fellix | 400 | 18px | 1.625 | normal | Hero support and introductory paragraphs under major headings. |
| card-heading | Fellix | 500 | 18px | 28px | -0.025em | Capability and resource card headings. |
| body | Fellix | 400 | 16px | 1.625 | normal | Explanatory paragraphs in panels and editorial columns. |
| body-compact | Fellix | 400 | 16px | 1.5 | normal | Short explanatory support, stat descriptions and compact text. |
| action | Fellix | 500 | 14px | 20px | normal | Filled and outlined buttons and editorial text actions. |
| navigation | Fellix | 400 | 14px | 20px | normal | Navigation and footer directory links. |
| eyebrow | PP Fraktion Mono | 500 | 12px | 16px | 0.1em, uppercase | Section labels, footer group names and numbered chapter markers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| research and company introductions | editorial-title | Fellix | 400 | 60px | 1.25 | -0.025em | Longer editorial opening statements. |
| historical storytelling | chapter-heading | Fellix | 400 | 30px | 1.25 | -0.025em | Milestone statements beside a timeline. |
| company narratives | vision-statement | Fellix | 400 | 30px | 1.375 | -0.025em | Extended statement beside smaller explanatory prose. |
| research-to-product narratives | feature-row-heading | Fellix | 400 | 24px | 32px | -0.025em | Compact title alongside a diagram in a ruled chapter row. |
| rankings and comparison pages | table-score | PP Fraktion Mono | 400 | 15px | 1.5 | normal | Right-aligned numeric table scores. |
| historical storytelling | timeline-label | PP Fraktion Mono | 400 | 14px | 20px | 0.1em, uppercase | Dates paired with short attribution labels. |

**Notes:**

- Keep headings regular and tighten the largest display more than section titles: -0.05em versus -0.025em.
- Body copy keeps normal tracking; medium card headings retain the tighter sans treatment.
- Mono is a second voice for structure, not a replacement for prose. Disable contextual alternates and standard ligatures.
- Use the display recipe for the closing call even when the page opens with the smaller editorial-title variant.

## Layout

**Density:** Airy section-level pacing with compact instrument-like details inside panels.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and newsletter input-to-action gap. |
| 12px | Hero action pair gap and short title-to-description spacing. |
| 16px | Body and label spacing inside cards. |
| 20px | Section heading-to-lead gap. |
| 24px | Card gutters and standard paired-action groups. |
| 28px | Hero headline-to-support gap. |
| 32px | Standard diagram and workflow inner padding. |
| 36px | Paired capability panel inner padding. |
| 40px | Intro-to-card-grid spacing, stat column gutters and footer column gutters. |
| 48px | Ruled editorial row padding and footer top inset. |
| 64px | Editorial split-column gaps. |
| 80px | Asymmetric illustration-to-text gap. |
| 112px | Hero vertical content padding. |
| 144px | Main desktop section top and bottom padding. |

### Containers and grids

- **container**: max width 1280px · side padding 32px. Centered border-box wrapper; at 1440px this leaves 1216px of usable content between 112px side margins.
- **copy column**: max width 672px. Section intros; hero headline is narrower at 576px and its support at 512px.
- **three-card grid**: 3 columns · gap 24px. Equal 389px-wide cards across the main content field.
- **paired capabilities**: 2 columns · gap 24px. Equal 596px panels; each combines prose and a diagram.
- **editorial split**: 2 columns · gap 64px. Balanced prose columns or asymmetric 0.85fr/1fr media-to-text composition.
- **stat directory**: 4 columns · gap 40px. Four 274px columns used by quantitative proof and footer directories.

## Corner radius

| Element | Radius |
| --- | --- |
| panels and actions | 0px |
| eyebrow capsule | 9999px (pill) |
| data points | 50% |

## Surfaces and depth

### Surfaces

#### Reading canvas · level 0

**Use:** Default explanatory page surface.

**CSS:** `background: #ffffff; color: #0a0a0a`

#### Cool band · level 0

**Use:** Alternating full-width chapters.

**CSS:** `background: #f7f8fa`

**Observed:** Flat, cool-neutral backing with no texture or elevation.

**Transfer:** Use to distinguish chapters without adding extra accent colors.

#### Black stage · level 0

**Use:** Opening, immersive proof and closing chapters.

**CSS:** `background: #000000; color: #ffffff; overflow: hidden; position: relative`

**Observed:** Art and low-intensity glow sit behind reversed text.

**Transfer:** Keep large areas genuinely black rather than navy.

#### Specimen panel · level 1

**Use:** Bounded explanation and diagram groups.

**CSS:** `background: #ffffff; border: 1px solid #0a0a0a; border-radius: 0px; box-shadow: none`

**Observed:** Strong outlines frame interactive workflows and paired capability panels; lighter resource cards use the fine panel edge.

**Transfer:** Use border hierarchy rather than elevation.

#### Spectrum atmosphere

**Use:** Announcement and dark illustrative backgrounds.

**CSS:** `background: linear-gradient(90deg, #4ebc9c, #3452aa, #6e50aa, #d29c7c); filter: blur(40px); opacity: 0.8`

**Observed:** The announcement confines this light to a 49px strip. Research hero variants use blur(64px), opacity 0.3; the centered narrative variant uses opacity 0.25.

**Transfer:** Clip the glow to its stage and preserve readable black around the main message.

## Components

### Sticky navigation

**Use:** Persistent orientation and conversion action.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 73px; background: rgba(0,0,0,0.92); border-bottom: 1px solid rgba(255,255,255,0.12); backdrop-filter: blur(8px)`

**Text style:** `navigation` — Fellix 400 · 14px/20px

**Observed:** Logo at left, compact menu centered, white contact action at right. Menu controls are 36px high with 12px side padding and tiny chevrons. A separate 49px spectrum announcement sits above it and scrolls away.

### Primary button

**Use:** Main conversion on a black stage.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 0px 20px; background: #ffffff; color: #000000; border-radius: 0px`

**Text style:** `action` — Fellix 500 · 14px/20px

**Observed:** Text-only or followed by a small right arrow. Navigation uses the same construction at 36px height with 16px side padding.

**States:** Declared: hover background becomes white at 90%; focus-visible unknown; active background becomes white at 80%.

### Outline button

**Use:** Secondary action alongside the main white button.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 0px 20px; background: transparent; color: #ffffff; border: 1px solid rgba(255,255,255,0.4); border-radius: 0px`

**Text style:** `action` — Fellix 500 · 14px/20px

**Observed:** Shares baseline and height with Primary button; secondary role is carried by the fine outline rather than muted text.

**States:** Declared: hover background white at 5% and border white at 70%; focus-visible unknown; active background white at 10%.

### Dark button

**Use:** Main conversion in white and pale-gray chapters.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 0px 20px; background: #0a0a0a; color: #ffffff; border-radius: 0px`

**Text style:** `action` — Fellix 500 · 14px/20px

**Observed:** Usually placed beneath a panel or card group, aligned to the content left edge.

**States:** Declared: hover background rgb(52, 58, 66); focus-visible unknown; active background #000000.

### Underlined text action

**Use:** Study links and lower-priority editorial destinations.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding-bottom: 2px; border-bottom: 1px solid #dadde2; color: #0a0a0a`

**Text style:** `action` — Fellix 500 · 14px/20px

**Observed:** A small rightward or diagonal arrow completes the label. On dark, text is white and the underline is white at 40%.

**States:** Declared: hover border-color #0a0a0a; focus-visible unknown. Dark variant hover border-color white.

### Illustrated resource card

**Use:** Capability summaries and research destinations.

**CSS:** `display: flex; flex-direction: column; background: #f7f8fa; border: 1px solid #e6e8eb; border-radius: 0px`

**Text style:** `card-heading` — Fellix 500 · 18px/28px · tracking -0.025em

**Observed:** A white schematic field occupies the upper part; a pale text deck follows with a mono category, title and compact paragraph or underlined action. Cards are 389px wide; resource variants are 305px tall and capability variants 376px tall.

**Transfer:** Illustrate one process or distinction per card instead of inserting a full dashboard.

### Workflow panel

**Use:** Explain a multi-step product loop.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 42%) minmax(0px, 58%); background: #ffffff; border: 1px solid #0a0a0a; margin-top: 24px`

**Observed:** A 512px-tall panel pairs a left narrative cell with a pale schematic on the right. Above it, 46px-high text tabs sit on a rule, 32px apart; active tab has a 2px near-black underline. The right cell uses a dashed divider and stacked annotated signal rows.

**Transfer:** Use the tabs to reveal stages of one coherent workflow rather than unrelated features.

### Ruled statistic

**Use:** Compact quantitative credibility.

**CSS:** `border-top: 2px solid #0a0a0a; padding-top: 18px; display: flex; flex-direction: column-reverse`

**Text style:** `stat` — PP Fraktion Mono 400 · 36px/1 · tracking -0.05em

**Observed:** Numeral above a smaller plain-language descriptor, four columns with 40px gutters. The lead statistic gets the stronger rule; the other three use 1px #dadde2 rules.

### Eyebrow capsule

**Use:** A compact named problem or chapter marker.

**CSS:** `display: inline-block; border: 1px solid #dadde2; border-radius: 9999px; padding: 6px 14px; color: #5b6470`

**Text style:** `eyebrow` — PP Fraktion Mono 500 · 12px/16px · tracking 0.1em · uppercase

**Observed:** One of very few rounded forms. Most eyebrows remain unboxed; use the capsule for the framing idea, not every label.

### Newsletter input

**Use:** Subscription row at the top of the footer.

**CSS:** `height: 44px; padding: 0px 16px; background: transparent; border: 1px solid rgba(255,255,255,0.4); border-radius: 0px; color: #ffffff`

**Text style:** `navigation` — Fellix 400 · 14px/20px

**Observed:** Input and square Subscribe action form a 448px-wide row with an 8px gap; prompt sits on the left. Empty-form Subscribe appears at 0.4 opacity.

### Directory link

**Use:** Footer destinations under mono category headings.

**CSS:** `color: rgba(255,255,255,0.7)`

**Text style:** `navigation` — Fellix 400 · 14px/20px

**Observed:** Simple unboxed links in four columns; rows follow a compact 32px rhythm. The bottom strip pairs a small logo and social icons with legal links.

**States:** Declared: hover color white; focus-visible unknown.

### Ranking row

**Only for:** rankings and comparison pages

**Use:** Dense quantitative comparison on black.

**CSS:** `display: grid; grid-template-columns: 30px 26px minmax(0px, 1fr) minmax(120px, 208px) 72px; align-items: center; gap: 16px; padding: 13px 0px; border-bottom: 1px solid rgba(255,255,255,0.1)`

**Text style:** `table-score` — PP Fraktion Mono 400 · 15px/1.5

**Observed:** Rank, small identity mark, model name, thin spectrum score bar and right-aligned mono number. Rows are about 50px tall; a 232px category rail is separated from the table by a faint vertical line.

**Transfer:** Preserve aligned scores and thin marks; populate with real, relevant comparison criteria.

## Imagery and graphics

### Immersive particle specimen

**Use:** Signature opening object on the black stage.

**Observed:** A sweeping, organic cloud of multicolored circular points fills the right two thirds, clipped at the right and lower edges. Sharp and defocused points create depth; green, violet, pink and blue clusters glow without lighting the black background. A left-to-right black veil keeps text unencumbered.

**Transfer:** Represent a product's complexity with an abstract point cloud, not a generic stock photograph. Minimum version: a deliberately shaped SVG field with varied focus and cluster density.

**Build:** In a 1440×768 SVG, distribute hundreds of circles along three curved, overlapping bands rising from lower center toward upper right. Vary radii roughly 2–12px and opacity 0.2–0.8; interpolate the four spectrum colors and add scattered brighter points. Layer a blurred copy beneath sharper points, then a horizontal black overlay fading from opaque at left to transparent at right. Keep the densest points beyond the text column.

### Annotated schematic miniatures

**Use:** Product explanation panels and resource card tops.

**Observed:** White-backed waveforms, thin vertical signal ticks, slider-like horizontal rules, small circular markers, compact bar charts and framed grids. Grays carry most marks; one spectrum trace emphasizes a signal. No browser chrome, perspective or floating shadows.

**Transfer:** Draw a simplified instrument for the new product's input, transformation and output. One visual idea should remain legible at 389px card width.

**Build:** Use SVG with 1px pale-gray guides, repeated 1px vertical bars of varying heights, and small solid or outlined circular handles. Apply the four-stop spectrum to a single trace or bar; add mono category captions and generous white backing.

### Luminous halftone finale

**Use:** Signature closing field behind a centered call to action.

**Observed:** Black across the top, with mint light rising from the lower left, blue and violet through the center and peach at lower right. Uneven halftone dots form taller banks at the outer edges, thinning toward the center so white text stays clear. The luminous layer is flat and atmospheric rather than a glossy object.

**Transfer:** Retain this patterned glow even when the product has no custom imagery; generate it procedurally.

**Build:** Place a broad four-stop linear gradient at the bottom of a black section, fading its opacity vertically to zero near the upper half. Overlay SVG circles on an approximately 16px lattice, varying radius and opacity with a low-frequency noise field; concentrate larger pale dots at the outer lower edges and darker dots across the violet middle. Fade the pattern behind the text; keep controls on the foreground.

### Annotated point map

**Only for:** research explanations and interactive data stories

**Use:** Research hero figure and expanded exploratory exhibit.

**Observed:** Small multicolored dots form irregular clusters on black. The compact 448px-square figure uses dashed circular callouts, leader lines and tiny uppercase mono captions; the expanded exhibit is a dark bordered map with compact tabs and scattered dark label chips.

**Transfer:** Plot a meaningful dataset or a clearly conceptual distribution; maintain cluster structure and sparse annotations.

**Build:** Use SVG circles with small radii in clustered coordinates, color by category, and a handful of dashed outline circles linked to mono labels. Back with a subdued spectrum glow rather than a filled chart grid.

### Historical and human editorial media

**Only for:** company and historical narratives

**Use:** Vision film and long-form milestone chapters.

**Observed:** A wide 1216×684 film uses warm ivory backing and loose black hand-drawn people in conversation. History pairs grayscale engraved portraits and documentary diagrams with black-backed timeline text; portraits are unrounded, often 384×480, without decorative frames.

**Transfer:** Use original line animation for human context and relevant monochrome documentary material for history. Keep these distinct from the default abstract product imagery.

### Icons

**Observed:** Small round-capped outline icons, usually 16×16px with 1.5px strokes, placed after action labels or beside menu text. Larger explanatory icons are 24–28px with 1.3px strokes. Social icons are simple 16px filled marks in muted white.

**Transfer:** Use a consistent thin outline set; reserve solid marks for social identities and data points.

## Section recipes

How recurring sections are built.

### First screen: Immersive product opening

**Observed:** A 49px glowing announcement precedes the 73px Sticky navigation. Below, a 768px Black stage occupies nearly the rest of the first 900px. Background to foreground: black canvas, Immersive particle specimen sweeping into the right two thirds, left black veil, then a vertically centered left copy block. The display headline fits a 576px column and wraps to two lines; support is 512px wide with a 28px gap. A Primary button and Outline button follow after 40px with a 12px gap. Headline, support, both actions and the main object all appear before 900px; only the edge of the next light band appears at the bottom.

**Transfer:** Replace the promise with a short product outcome and the artwork with a custom point-cloud specimen derived from its domain. Keep the art large and cropped beyond the stage, not inside a card. Research introductions instead use editorial-title on the left and a compact annotated figure on the right; company narratives can open on white with an eyebrow and a wide editorial statement. Comparison stories can center the display above a thin waveform.

**Avoid:** Do not turn the opening into a centered gradient headline above a browser mockup, or shrink the particle field into a decorative thumbnail.

**Text style:** `display` — Fellix 400 · 72px/1 · tracking -0.05em

### Problem and annotated specimen

**Observed:** Cool band with 144px top and bottom padding; asymmetric media/text split with 80px gap. A circular grayscale human portrait is surrounded by a pale radar-like polygon and small measurement labels. Beside it, Eyebrow capsule, heading, support and two short questions sit above a 2px left rule.

**Transfer:** Frame the hidden complexity of the new product with an annotated specimen; if photography is not relevant, use a central product input and labels that describe its observable dimensions.

**Text style:** `heading` — Fellix 400 · 48px/1.25 · tracking -0.025em

### Quantitative proof strip

**Observed:** White strip with 56px top and 72px bottom padding; a mono label introduces four Ruled statistic columns. Numerals are 36px mono rather than giant sans.

**Transfer:** Use a few substantiated facts with short descriptions; let the stronger first rule establish emphasis.

### Tabbed process chapter

**Observed:** Cool band, heading and lead, 40px to tabs, then Workflow panel. One dark action sits below the panel, aligned left.

**Transfer:** Explain one mechanism through sequential stages. Keep each state to a concise narrative plus a schematic.

### Reversed comparison exhibit

**Observed:** Black stage with a 48px heading, 18px lead and large outlined comparison surface. Selectable rows occupy the left half; the right uses thin horizontal bars and mono scores. White action and underlined methodology link follow beneath.

**Transfer:** Show tradeoffs or inspectable proof rather than decorative metrics. Ranking-heavy pages expand this into Ranking row tables with a category rail.

### Capability and resource grid

**Observed:** Reading canvas or Cool band; a heading and max-672px lead precede Illustrated resource cards by 40px. Three equal columns use 24px gutters. Paired capability variants use two strong-bordered Specimen panels, 36px inner padding and schematic grids.

**Transfer:** Group by distinct customer tasks or outcomes; put the illustration above the text and keep actions consistent within the group.

### Monumental closing and directory

**Observed:** A full-width Black stage combines Luminous halftone finale with a centered display headline, compact support and Primary button plus Outline button. Closing heights vary from 419px for a short mission call to 621px for a longer research invitation; the main product version is 563px. A 567px black footer continues directly beneath: newsletter row first, 40px-padded separator, four directory columns, then a ruled logo/social/legal strip with 24px vertical padding.

**Transfer:** Resolve the page's core promise into one action-led closing statement; keep the patterned light and complete directory treatment while tailoring the invitation to the page purpose.

**Text style:** `display` — Fellix 400 · 72px/1 · tracking -0.05em

### Ruled research chapters

**Only for:** research-to-product narratives

**Observed:** A white introduction leads into repeated split rows with 1px pale top rules, 48px vertical padding and 64px column gaps. Each row pairs feature-row-heading, body and a text action with a flat annotated diagram.

**Transfer:** Translate abstract principles into concrete product mechanisms using one row per conceptual transformation.

**Text style:** `feature-row-heading` — Fellix 400 · 24px/32px · tracking -0.025em

### Editorial history

**Only for:** company and historical narratives

**Observed:** A black section begins with eyebrow, heading and lead. A media column sits opposite a vertical timeline; milestone text has a 32px left inset, small circular nodes, 14px uppercase mono date labels and 30px chapter headings. Desktop milestone rows extend to 630px, allowing grayscale media to breathe.

**Transfer:** Use this slow documentary pacing only when a genuine evolution or origin story supports it; shorter research histories use a horizontal four-column line on white.

**Text style:** `chapter-heading` — Fellix 400 · 30px/1.25 · tracking -0.025em

## Page flow

**Storyline:** Promise → expose the hidden problem → demonstrate a mechanism → establish inspectable proof → explain capabilities and methods → offer deeper reading → focused closing invitation and directory.

### Product and infrastructure landing narrative

1. **Promise** — Immersive black opening with a left promise and large particle specimen.
2. **Problem framing** — Light annotated specimen and paired questions reveal what a superficial measure misses.
3. **Credibility** — Compact four-column mono statistic strip.
4. **Product demonstration** — Tabbed workflow followed by reversed comparison exhibit.
5. **Capability chapters** — Paired audience panels and three-column illustrated infrastructure cards.
6. **Deeper reading** — Research resource cards.
7. **Closing call** — Monumental glowing invitation followed by newsletter and directory.

**Transfer:** Adapt the emphasis and number of chapters to the product; preserve the contrast between immersive promise, explanatory instruments and luminous resolution.

### Benchmark or evidence-led conversion narrative

1. **Hook** — Centered black display, thin waveform and atmospheric light introduce a tension.
2. **Problem demonstration** — Scroll-led conversation and signal illustration make the gap tangible.
3. **Quantified proof** — Introductory metrics lead into a category-filtered dark ranking table.
4. **Conversion bridge** — A ruled full-results invitation closes the public exhibit.
5. **Applied value** — White and gray chapters explain private application, methods and diagnostic detail.
6. **Deeper reading** — Strong-bordered research grid.
7. **Closing call** — Large centered challenge over halftone light, then shared newsletter and directory.

**Transfer:** Use for independently checkable product proof, retaining methodology access and a bridge from general results to the reader's own problem.

### Research foundation translated into product usefulness

1. **Authority** — Black editorial opening with annotated point-map figure.
2. **Context** — White split introduction and horizontal timeline.
3. **Supporting studies** — Three pale-band study cards with thin spectrum top accents.
4. **Explorable proof** — Dark map exhibit with tabs and annotated clusters.
5. **Practical translation** — White ruled chapters pair prose with taxonomy and process diagrams.
6. **Closing call** — Research invitation over the halftone light field, followed by newsletter and directory.

**Transfer:** Move from conceptual foundation to practical mechanisms without turning the whole page into an academic paper.

### Company positioning and intellectual origin story

1. **Positioning** — White editorial statement under a mono eyebrow.
2. **Vision** — Large statement beside smaller prose, followed by a wide hand-drawn film.
3. **Scope** — Two pale-band cards distinguish research and practical work.
4. **Origin story** — Long black documentary timeline with grayscale media and milestone text.
5. **Closing call** — Short mission invitation over the same halftone light, then newsletter and directory.

**Transfer:** Use a quieter white opening for institutional positioning, then reserve extended dark storytelling for meaningful history.

## Writing

Scientifically grounded and direct, with an underlying concern for human experience. Confidence comes from explaining mechanisms, conditions and limitations rather than superlatives.

**Do not copy:** Do not reuse Hume names, product names, logos, proprietary artwork, research claims, customer assertions, statistics or distinctive mission language. Source examples illustrate voice only; replace them with substantiated content for the new product.

- **Addressing the reader:** Use you and your for the reader's system or task. Use we for research and product work, and the product name when describing a concrete mechanism.
- **Rhythm:** Short declarative headlines, often 5–11 words, lead into one or two explanatory sentences. Follow longer technical paragraphs with terse verb-led actions; rhetorical contrasts are more common than exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the infrastructure or outcome in a plain declarative phrase. | 5–10 words | “Infrastructure to improve voice AI.” |
| Problem headline | Contrast the obvious surface with the more meaningful underlying reality. | 6–12 words | “There is more to voice than words.”<br>“Your aggregate score is hiding something. Find out what.” |
| Supporting line | Concrete verbs explain what the system does and how that helps the reader. | 20–45 words | “Generate targeted tests, stress-test your voice AI, diagnose failures, and validate improvements, all in one evaluation platform.” |
| Primary action | Verb plus a specific object or destination. | 2–7 words | “Evaluate your system”<br>“Request a private evaluation” |
| Technical eyebrow | Short noun phrase that classifies the chapter rather than advertises it. | 2–5 words | “The measurement gap”<br>“How we measure” |

**Words and phrasing to use:** measure; evaluate; real-world; conditions; human judgment; diagnose; define; validate; what to improve; research; tradeoffs

**Avoid:** magic; revolutionary; game-changing; unleash; effortless perfection; best-in-class without qualification

**Rules:**

- Attach claims to a mechanism, a condition or a measurable result.
- Use parallel verbs when describing an improvement loop.
- Separate what is demonstrated conceptually from actual measured results.
- Prefer precise task language in actions over generic Learn more when a specific destination is known.
- Human concern should appear in the problem framing, not as sentimental decoration.

## Do's and Don'ts

### Do

- Keep main display text at weight 400 with -0.05em tracking and a 1 line height.
- Use 144px desktop chapter padding to separate dense instrument panels.
- Align cards, actions and footer columns to the 1216px usable content field.
- Use 24px gutters for equal resource cards and 40px gutters for four-column statistics.
- Keep explanatory graphics flat on white, with 1px rules and sparse spectrum traces.
- Preserve the 44px square action silhouette across light and dark sections.
- Carry the multicolored halftone field into a centered closing invitation.
- Use 12px uppercase mono labels with 0.1em tracking to classify content, not to carry long paragraphs.

### Don't

- Do not round the main cards or CTA buttons into pills; rounded capsules belong to small framing labels.
- Do not replace #000000 stages with a uniform blue-black dashboard theme.
- Do not fill every card with a different spectrum color; keep #ffffff and #f7f8fa dominant in reading chapters.
- Do not add floating drop shadows to the specimen panels; use 1px edges instead.
- Do not enlarge supporting body copy to compete with the 48px section heading.
- Do not use mono for long explanations or navigation; retain the rounded sans reading voice.
- Do not turn the compact 36px mono statistic strip into oversized colorful KPI tiles.
- Do not replace schematic miniatures with dense browser screenshots full of unreadable controls.

## Motion and responsive

### Motion

**Observed:**

- Actions declare color-related transitions of 0.15s cubic-bezier(.4,0,.2,1).
- Signal graphics declare width 0.5s and height 1s cubic-bezier(0,0,.2,1).
- Timeline content declares opacity 0.5s cubic-bezier(.4,0,.2,1), with reduced-motion transition removal.
- Announcement status declares pulse 2s cubic-bezier(.4,0,.6,1) infinite; some signal strips declare a 60s linear marquee.

**Transfer:**

- Use short color changes for instrument controls and reserve slower changes for signals or the active milestone.
- Keep particle and glow treatments subordinate to reading; reduced-motion versions should retain a composed static specimen.

**Unknown:**

- Exact particle animation paths and timing, scroll choreography and interaction focus styling are not fully specified.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Main section classes specify 80px, 112px and 144px vertical padding tiers; side padding changes from 24px to 32px.
- Opening display classes specify 48px, 60px and 72px tiers; desktop navigation is hidden below 1024px.
- Card grids become three columns at 1024px; footer starts with two columns and becomes four at 1024px.

**Transfer:**

- On narrow screens, put the headline and actions ahead of the particle specimen; keep the black veil and avoid squeezing text beside the art.
- Stack paired explanations and diagrams while preserving square outlines. Keep table scores aligned and permit the category controls to precede the table rather than compressing a desktop rail.

**Unknown:**

- Mobile menu construction, exact narrow-screen particle composition and full table overflow behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
