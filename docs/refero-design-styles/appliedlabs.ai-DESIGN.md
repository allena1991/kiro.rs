# Applied Labs — streetlight and systems

## Overview

A human, street-level expression of technical software: cinematic everyday photography sits beside warm paper surfaces and compact, matter-of-fact product demonstrations. The palette moves between cream, white and brown-charcoal, with periwinkle and sapphire reserved for signals and proof. Tight grotesk headlines, tiny monospaced markings and spacious modular layouts suit operational products that need to feel both capable and approachable.

### Essentials

- Real life is the main product stage: use full-bleed, warm architectural photography with a still human focal point and softly blurred movement; the default opening occupies 900px including its black proof strip. If bespoke media is unavailable, use a licensed everyday-work photograph with the same depth and negative space, not an abstract software orb.
- Headlines sound like short declarations and look tightly fitted: Archivo 64px/70px, weight 600, -0.03em for the opening; section leads are 54px/60px, weight 500, -0.02em. White opening copy occupies a narrow 480px column against a scene that fills the width.
- Technical markings punctuate a human canvas: use IBM Plex Mono labels at 11px/14px with 0.16em tracking and 12px/16px with 0.16em tracking for feature chapters, plus small sapphire checks and arrows.
- Buttons change silhouette with their job: primary photographic actions are white 8px-radius rectangles, 50px high with 16px 30px padding; compact navigation actions and capability tags are pills. Closing actions grow to 56px with 18px 36px padding.
- Color behaves as evidence rather than wallpaper: most reading surfaces are white, parchment #fdf8f2 or pale stone #f3f0ee; a brown-charcoal #3d3838 chapter band holds pale demonstrations. Include a periwinkle proof accent, using #e3e9ff for a feature tile or #6b8eff for a quote, rather than tinting every section.
- Capability chapters feel like a deck of physical panels: 24px-radius pale panels pair a 44px/50px heading and blue checklist with a white, 14px-radius product demonstration. Include this tangible product stage and a narrow black assurance strip on a new landing page, adapting the proof to the product.
- The final conversion returns to the outside world: a full-width warm photographic scene carries a centered white 68px/74px declaration, a short support line and paired solid/outlined actions; the next surface is an off-white directory footer, not another sales card.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sapphire signal | `#3061ff` | `--color-sapphire` | text, link, accent | Mono labels, checkmarks and directional arrows; not the default button fill. |
| Cornflower proof | `#6b8eff` | `--color-cornflower` | surface, accent | Highlighted quote cards, thin data curves and small outline icons. |
| Light sapphire | `#9fb6ff` | `--color-inverted-accent` | text, accent | Small checks, captions and links against black. |
| Periwinkle card | `#e3e9ff` | `--color-periwinkle` | surface | One contrasting feature tile within an otherwise neutral grid. |
| Blue-gray proof wash | `#e9eef7` | `--color-proof-wash` | background, surface | Quantified proof band; also one tier in commercial comparisons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, surface, action | Reading canvas, product demonstration cards, photographic text and solid actions. |
| Near black | `#020202` | `--color-ink` | text, background, action | Default headings, dark buttons, proof strips and inverted feature cards. |
| Photographic underlay | `#1c1a18` | `--color-espresso` | background | Dark backing beneath full-bleed photographic sections. |
| Warm ink | `#26251e` | `--color-warm-ink` | text, action | Proof headings and commercial text; also the assistant variant's primary ink. |
| Brown charcoal | `#3d3838` | `--color-graphite` | background, surface | Long product chapter stage and premium commercial panels. |
| Warm gray text | `#57534e` | `--color-body` | text | Paragraphs and secondary explanations on light surfaces. |
| Stone caption | `#8a857e` | `--color-muted` | text | Small secondary captions and numbered markings. |
| Inverted secondary text | `#b9b6b0` | `--color-dark-body` | text | Explanations within black cards and security bands. |
| Dark-surface text | `#c6c0bc` | `--color-dark-muted` | text | Supporting text and mono summaries on charcoal. |
| Outline action edge | `#c9c4bc` | `--color-outline-edge` | border | Outlined secondary actions over photography. |
| Tag edge | `#d6d2ca` | `--color-tag-edge` | border | Outlined capability pills. |
| Card edge | `#e4e0da` | `--color-card-edge` | border | Product framing, inset commercial card edges and the 2px bottom edge on white feature tiles. |
| Quote edge | `#ece8e2` | `--color-quote-edge` | border | Faint outline of white testimonial cards. |
| Section hairline | `#ece9e4` | `--color-section-rule` | border | Dividers between editorial bands and list rows. |
| Chapter stone | `#f3f0ee` | `--color-stone` | surface | Large product chapter panels against charcoal. |
| Warm parchment | `#fdf8f2` | `--color-parchment` | background, surface | Editorial bands and capability cards; also the white-button hover fill. |
| Off-white shell | `#fbfbfa` | `--color-shell` | background, surface | Footer and utility shell; the glass header uses this hue at about 28% opacity over media. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Active olive | `#405a00` | `--color-active` | text, accent | Small system-status link in the footer; not a general brand accent. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| assistant-style product demonstrations | Shader teal | `#5f9e9a` | `--color-assistant-teal` | background | Soft teal field in the grainy atmospheric media. |
| pricing pages | Lavender tier | `#dce4ff` | `--color-tier-wash` | surface | A higher-volume commercial tier. |
| assistant-style product demonstrations | Shader mist | `#a9c9c7` | `--color-assistant-mist` | background | Diffuse teal middle tones in atmospheric media backdrops. |
| assistant-style product demonstrations | Shader navy | `#162235` | `--color-assistant-navy` | background | Deep lower edge of assistant media backdrops. |
| pricing pages | Alternative plan olive | `#6f7b63` | `--color-olive` | surface | Separate integration-first commercial option, visually detached from the main tiers. |
| company and people pages | Portrait stone | `#e8e4df` | `--color-portrait` | surface | Neutral portrait backings. |
| assistant-style product pages and comparison-table category bands | Assistant paper | `#f2f1ed` | `--color-assistant-card` | surface | Outer frames for alternating demonstration chapters. |
| assistant-style product demonstrations | Shader light | `#f7f7f4` | `--color-assistant-light` | background | Light end of the assistant atmospheric backdrops. |

## Typography

- **Archivo** — All default marketing headlines, paragraphs, actions and shell navigation. Compact grotesk with open counters; firm semibold display and restrained regular body text. Font stack: "Archivo", Arial, sans-serif.
- **IBM Plex Mono** — Technical eyebrows, numbered markers, check glyphs, chart annotations and testimonial role captions. Small, widely tracked equipment-like markings rather than long code blocks. Font stack: "IBM Plex Mono", ui-monospace, monospace.
- **Geist** (only for assistant-style product pages) — Product narrative, demonstration labels and contact section. Lighter, more interface-oriented grotesk; smaller headlines and a softer hierarchy than the default marketing voice. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | Archivo | 600 | 68px | 74px | -0.03em | Monumental photographic closing declaration. |
| display | Archivo | 600 | 64px | 70px | -0.03em | Default opening headline and shorter photographic closing headlines. |
| proof-heading | Archivo | 500 | 58px | 62px | -0.02em | Quantified assurance and large social-proof headings. |
| heading | Archivo | 500 | 54px | 60px | -0.02em | Default section lead; often a short two-line statement. |
| chapter-heading | Archivo | 500 | 44px | 50px | -0.02em | Large product chapter titles inside pale panels. |
| tile-heading | Archivo | 500 | 34px | 40px | -0.02em | Headings in the asymmetric numbered tile grid. |
| card-heading | Archivo | 500 | 26px | 32px | -0.02em | Narrow capability cards and numbered overview cards. |
| closing-support | Archivo | 400 | 18px | 28px | normal | Single centered support line over closing photography. |
| quote | Archivo | 500 | 18px | 26px | -0.01em | Customer quotation, not an oversized editorial pull quote. |
| body | Archivo | 400 | 17px | 27px | normal | Main supporting paragraphs, including the opening. |
| body-small | Archivo | 400 | 16px | 1.5 | normal | Checklists and secondary product explanations. |
| action | Archivo | 600 | 16px | 1.25 | normal | Larger conversion buttons in proof and closing sections. |
| card-body | Archivo | 400 | 15px | 1.6 | normal | Capability card copy and company editorial descriptions. |
| hero-action | Archivo | 500 | 14.5px | 18px | normal | Opening primary and underlined secondary actions. |
| footer-link | Archivo | 400 | 14px | 1.55 | normal | Footer directory links and status. |
| tag | Archivo | 500 | 13px | 16px | normal | Capability pills within feature tiles. |
| navigation | Archivo | 400 | 13px | 20px | normal | Compact top navigation and utility actions. |
| footer-label | Archivo | 400 | 13px | 1.35 | normal | Muted directory category names. |
| chapter-label | IBM Plex Mono | 600 | 12px | 16px | 0.16em | Uppercase product chapter labels in sapphire. |
| eyebrow | IBM Plex Mono | 400 | 11px | 14px | 0.16em | Uppercase capability labels and two-digit tile numbers. |
| attribution | IBM Plex Mono | 400 | 11px | 14px | normal | Role and company below testimonial names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | commercial-section | Archivo | 300 | 54px | 1 | normal | Lightweight add-on section title. |
| pricing pages | commercial-display | Archivo | 300 | 50px | 1 | normal | Large titles inside setup-comparison cards. |
| assistant-style product pages | assistant-contact | Geist | 300 | 36px | 42px | normal | Contact-form section heading. |
| pricing pages | plan-number | Archivo | 400 | 30.4px | 1.285714 | normal | Plan quantities and prices, with tabular lining numerals. |
| assistant-style product pages | assistant-display | Geist | 400 | 28px | 1.2 | -0.02em | Intentionally small, narrow opening headline. |
| pricing pages | plan-title | Archivo | 400 | 24px | 1.08 | normal | Plan and add-on titles. |
| assistant-style product pages | assistant-statement | Geist | 400 | 24px | 1.25 | normal | Feature statement below a small sentence-case section label. |
| pricing pages | faq-question | Archivo | 400 | 15px | 1.5 | 0.005em | Questions in the commercial accordion. |
| assistant-style product pages | assistant-body | Geist | 400 | 15px | 1.5 | 0.005em | Small sentence-case section labels and supporting bullets. |

**Notes:**

- Archivo is the default, including body text; the utility shell does not require a separate type family.
- Display tracking is -0.03em at weight 600; section and card titles use -0.02em at weight 500. Body text is untracked.
- Headlines remain sentence case. Uppercase belongs to small mono labels, not paragraph text.
- The assistant variant reverses the usual hierarchy: a 15px sentence-case label introduces a 24px statement. Do not mix this scale into the default cinematic opening.
- Use tabular lining numerals for commercial quantities, without turning all marketing text into a numeric or mono style.

## Layout

**Density:** Airy at section scale, compact within product demonstrations; long breathing spaces contrast with small technical annotations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Wrapped tag gaps and tight label-to-statement spacing in the assistant variant. |
| 12px | Icon-to-copy gaps and small stacked details. |
| 16px | Internal numbered-tile rhythm and paired closing actions. |
| 20px | Default card-grid gutters. |
| 24px | Chapter copy stack, testimonial padding and three-column portrait gutters. |
| 26px | Opening headline-to-copy spacing and action-row gap. |
| 32px | Capability-card padding. |
| 40px | Numbered tile vertical padding. |
| 44px | Numbered tile horizontal padding. |
| 56px | Section heading-to-content rhythm and product panel vertical padding. |
| 64px | Desktop side inset and product-panel horizontal padding. |
| 88px | Gap between narrow proof copy and the wider chart. |
| 112px | Default major-band vertical padding. |
| 128px | Top and bottom padding for the tall photographic closing. |

### Containers and grids

- **main container**: max width 1312px · side padding 64px. Centered desktop content within full-width bands; photography remains edge-to-edge.
- **capability grid**: 4 columns · gap 20px. Equal 313px desktop cards with stable bottom-aligned links.
- **numbered mosaic**: 2 columns · gap 20px. First row uses 52:48 proportions; second row uses 45:55. Equal-height tiles within each row, not a uniform square bento.
- **chapter split**: 2 columns · gap 64px. Roughly 520px of copy paired with a roughly 620px white product stage inside a pale full-width panel.
- **proof split**: max width 1312px · 2 columns · gap 88px. 460px copy column alongside a wider 764px chart card.
- **footer container**: max width 1176px · side padding 40px. Narrower directory layout: identity rail up to 220px and a three-column, two-row link grid, separated by 144px.
- **people grid** (only for company and people pages): 3 columns · gap 24px. Three broad media panels, each about 421px wide, followed by titles and short captions.
- **plan grid** (only for pricing pages): max width 1312px · 5 columns · gap 0px. Touching equal commercial columns; the alternative setup is divided by a 6px light seam.
- **assistant panels** (only for assistant-style product pages): max width 1380px · 2 columns · gap 28px. Alternating 735px-high chapters; a 700px-high media field takes about two thirds and the text takes one third.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary actions | 8px |
|  | capability cards | 16px |
|  | numbered tiles | 20px |
|  | chapter panels | 24px |
|  | quotes and product frames | 14px |
|  | tags and utility actions | 9999px (pill) |
| assistant-style product pages | assistant outer frame | 4px |
| assistant-style product demonstrations | assistant glass | 10px |
| pricing pages | plan columns | 0px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | tile bottom edge | `0px 2px 0px 0px #e4e0da` | White numbered tiles have a restrained physical bottom edge, not an elevated drop shadow. |
| assistant-style product demonstrations | assistant glass depth | `inset 0px 0px 0px 1px rgba(255,255,255,0.55), inset 0px 1px 0px rgba(255,255,255,0.85), 0px 14px 36px rgba(22,34,53,0.12)` | Floating demonstration cards over grainy atmospheric backdrops. |

### Surfaces

#### Reading canvas · level 0

**Use:** Default light page foundation.

**CSS:** `background: #ffffff; color: #020202`

**Observed:** White reading bands alternate with warm parchment rather than a single tinted page.

**Transfer:** Use the neutral alternation to separate chapters without adding decorative gradients.

#### Warm editorial band · level 0

**Use:** Capability overviews, explanatory grids and objection handling.

**CSS:** `background: #fdf8f2; padding: 112px 64px`

**Observed:** Broad uninterrupted field with a centered content container.

**Transfer:** Keep the band full width and let the content density determine its height.

#### Charcoal stage · level 0

**Use:** Long capability demonstrations.

**CSS:** `background: #3d3838; padding: 112px 64px; overflow-x: clip`

**Observed:** White section introduction leads into large pale panels. The brown cast distinguishes the stage from black assurance strips.

**Transfer:** Use it for the deeper operational story, not for every dark section.

#### Photographic backing · level 0

**Use:** Opening and closing media.

**CSS:** `background: #1c1a18; position: relative; overflow: hidden`

**Observed:** Full-bleed photography with subdued exposure; local dark gradients keep white copy legible.

**Transfer:** Let the image supply texture and hue, leaving foreground typography unadorned.

#### Pale chapter panel · level 1

**Use:** Large product chapters.

**CSS:** `background: #f3f0ee; border: 1px solid rgba(0,0,0,0.06); border-radius: 24px; padding: 56px 64px`

**Observed:** A tangible pale slab inside the charcoal field, with two horizontally balanced content zones.

**Transfer:** Pair a compact benefit story with one legible working example.

#### Proof band · level 0

**Use:** Risk reduction and quantified assurance.

**CSS:** `background: #e9eef7; padding: 112px 64px`

**Observed:** Cool neutral field breaks the cream/charcoal rhythm around a white data card.

**Transfer:** Reserve the cool band for a distinct evidence or assurance moment.

#### Directory shell · level 0

**Use:** Footer.

**CSS:** `background: #fbfbfa; padding: 56px 40px 80px`

**Observed:** Flat, spacious directory with almost no framing.

**Transfer:** Finish on practical navigation rather than another decorated content panel.

#### Assistant glass · level 2

**Only for:** assistant-style product demonstrations

**Use:** Floating cards over textured teal, sage or navy media fields.

**CSS:** `background: rgba(252,252,249,0.7); border-radius: 10px; backdrop-filter: blur(16px) saturate(1.7); box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.55), inset 0px 1px 0px rgba(255,255,255,0.85), 0px 14px 36px rgba(22,34,53,0.12)`

**Observed:** Light translucent panels pick up the underlying atmospheric hue while preserving crisp text.

**Transfer:** Use a few simple records or workflow cards; do not turn the entire marketing shell into glass.

## Components

### Navigation

**Use:** Fixed top-level shell.

**CSS:** `position: fixed; top: 0px; height: 56px; width: 100%; padding: 0px 64px; background: rgba(251,251,250,0.27856); backdrop-filter: blur(8.4px); z-index: 50`

**Text style:** `navigation` — Archivo 400 · 13px/20px

**Observed:** Small symbol at the left, compact category links, then a right-aligned login and two 28px utility pills. Link color follows the underlying light or photographic context; the shell becomes more visibly frosted over content.

**Transfer:** Use the new brand's compact mark and a short navigation set. Keep the shell visually smaller than the hero.

### Primary button

**Use:** Default opening conversion action.

**CSS:** `display: flex; align-items: center; background: #ffffff; color: #020202; border-radius: 8px; padding: 16px 30px; height: 50px`

**Text style:** `hero-action` — Archivo 500 · 14.5px/18px

**Observed:** Sits beside a simple underlined secondary link. In proof sections its fill is black; the larger closing variant uses the action recipe and 18px 36px padding for 56px height.

**States:** Declared: hover background-color #fdf8f2.

### Outline button

**Use:** Secondary conversion action on dark photography.

**CSS:** `display: flex; align-items: center; color: #ffffff; background: transparent; border: 1px solid #c9c4bc; border-radius: 8px; padding: 18px 36px; height: 58px`

**Text style:** `action` — Archivo 600 · 16px/1.25

**Observed:** Paired with the solid closing action, rather than competing with it through a colored fill.

**States:** Declared: hover background-color color-mix(in oklab, #fff 10%, transparent).

### Text link

**Use:** Low-weight secondary action on photographic openings and card bottoms.

**CSS:** `color: #ffffff; text-decoration: underline; text-underline-offset: 4px`

**Text style:** `hero-action` — Archivo 500 · 14.5px/18px

**Observed:** No enclosing shape. Light-background variants use dark text and a small sapphire arrow; the arrow is separate from the label.

**States:** Declared: hover opacity 0.8 for the opening trial link.

### Capability card

**Use:** A small set of adjacent outcome promises.

**CSS:** `display: flex; flex-direction: column; position: relative; background: #fdf8f2; border-radius: 16px; padding: 32px; min-height: 420px`

**Text style:** `card-heading` — Archivo 500 · 26px/32px · tracking -0.02em

**Observed:** Tiny mono eyebrow at top left, 26px outline icon at top right, benefit headline, compact explanatory paragraph and a bottom-anchored action. Product-detail variants shorten the card to 360px.

**Transfer:** Use one distinct user outcome per card, with comparable copy length across the row.

### Numbered tile

**Use:** Explain a small framework with varied emphasis.

**CSS:** `display: flex; flex-direction: column; gap: 16px; background: #ffffff; color: #020202; border-radius: 20px; padding: 40px 44px; box-shadow: 0px 2px 0px 0px #e4e0da`

**Text style:** `tile-heading` — Archivo 500 · 34px/40px · tracking -0.02em

**Observed:** Two-digit mono marker precedes title and paragraph; outlined capability pills finish the tile. Variants invert to black with light text or use a flat periwinkle fill.

**Transfer:** Balance two neutral tiles against one inverted tile and one tinted tile; keep the asymmetry in widths rather than adding irregular shapes.

### Chapter panel

**Use:** Large demonstration unit on the Charcoal stage.

**CSS:** `display: flex; align-items: center; gap: 64px; background: #f3f0ee; border: 1px solid rgba(0,0,0,0.06); border-radius: 24px; padding: 56px 64px`

**Text style:** `chapter-heading` — Archivo 500 · 44px/50px · tracking -0.02em

**Observed:** A sapphire mono label, short benefit heading, paragraph and blue-check list share one side; a white product example occupies the other. The panels behave like an overlapping deck on desktop; the CRM variant uses parchment fill.

**Transfer:** Show a single useful operation in each example, not an unreadable complete application window.

### Capability tag

**Use:** Compact catalogue of related functions inside numbered tiles.

**CSS:** `border: 1px solid #d6d2ca; border-radius: 9999px; padding: 6px 14px; color: #020202`

**Text style:** `tag` — Archivo 500 · 13px/16px

**Observed:** Pills wrap across rows with 8px gaps. Dark tiles use a translucent white outline, without filled badge colors.

### Testimonial card

**Use:** Human proof in an edge-to-edge horizontal quote wall.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 20px; background: #ffffff; border: 1px solid #ece8e2; border-radius: 14px; padding: 24px; width: 360px; flex-shrink: 0`

**Text style:** `quote` — Archivo 500 · 18px/26px · tracking -0.01em

**Observed:** Compact quote above an avatar and two-line attribution. White, cream, cornflower and black variants create an irregular visual cadence across two offset rows.

**Transfer:** Use genuine concise quotes; mix emphasis through surface color, not through a different headline scale.

### Footer link

**Use:** Practical directory navigation.

**CSS:** `display: inline-flex; align-items: center; color: #020202; text-decoration: none`

**Text style:** `footer-link` — Archivo 400 · 14px/1.55

**Observed:** Small links under muted category labels; identity sits in its own left rail, with olive status and copyright near the bottom.

**States:** Declared: hover color color-mix(in oklab, #000 55%, transparent); focus-visible color #020202, 2px solid outline with 4px offset and color-mix(in oklab, #000 20%, transparent).

### Plan column

**Only for:** pricing pages

**Use:** Aligned commercial tiers with feature lists below.

**CSS:** `background: #fdf8f2; border-radius: 0px; height: 624px; box-shadow: inset 0px 0px 0px 1px #e4e0da; overflow: hidden; position: relative`

**Text style:** `plan-title` — Archivo 400 · 24px/1.08

**Observed:** 20px inner padding belongs to the content layer. Plan name and brief description occupy the top; ruled price/usage groups sit lower; black actions align across columns. Headers progress through cream, blue-gray, lavender, charcoal and olive, while lower feature lists return to white.

**Transfer:** Keep pricing labels, units and comparison rows aligned even when the tier count changes.

### FAQ row

**Only for:** pricing pages

**Use:** Commercial objection handling.

**CSS:** `border-top: 1px solid rgba(0,0,0,0.1); padding: 20px 0px; display: flex; justify-content: space-between; gap: 24px`

**Text style:** `faq-question` — Archivo 400 · 15px/1.5 · tracking 0.005em

**Observed:** Question and a 20px thin chevron form a roughly 68px closed row. A matching bottom rule closes the group; expanded content appears beneath its question, not in a floating panel.

**Transfer:** Keep the section title and introduction in a separate narrower column.

## Imagery and graphics

### Cinematic everyday life

**Use:** Signature full-width opening and closing media for the default marketing style.

**Observed:** Warm brick storefronts, dark green awnings, brownstone facades, plants and people in ordinary moments. Frontal architectural compositions hold a still focal person or doorway while pedestrians blur across the foreground. Natural dappled light and subdued saturation make white type readable without a conspicuous colored overlay.

**Transfer:** Use environments where the new product's value is felt by real people. Commission or license an eye-level scene with a stable focal point and negative space for copy. Minimum acceptable treatment is a carefully art-directed still photograph with subtle foreground motion blur; retain the human scene even when no original film is available.

**Build:** Use an edge-to-edge object-fit:cover image over the Photographic backing. Keep architecture sharp and apply directional blur only to separate foreground figures. Add a local black-to-transparent left scrim where needed, around 45% black at the left fading through 15% near center; keep the closing centered and dark enough for white text.

### Working product vignettes

**Use:** Legible media within Chapter panels and evidence bands.

**Observed:** White, softly framed interface fragments: a reply exchange, an executable flow, a small test checklist, a customer timeline or an orderly integration-logo grid. Content is isolated from heavy application chrome and occupies roughly half the panel. Thin rules, tiny labels and blue checks carry detail.

**Transfer:** Rebuild one representative operation as HTML or SVG. Use real, short example content and visible outcomes; leave ample white margins instead of shrinking a complete dashboard. If a full interface is unavailable, create a clearly labeled workflow schematic with the same pale frame and blue signals.

### Measured trajectory graphic

**Use:** Quantified assurance in the Proof band.

**Observed:** A 690px by 300px plot sits in a 764px-wide white 20px-radius card with 36px padding. Thin cornflower and olive curves use small outlined point markers; a low rust dotted line indicates the undesirable metric. Very light gridlines, endpoint values and tiny mono labels keep the proof understated.

**Transfer:** Use the new product's validated measures, showing a few meaningful milestones rather than a dense analytics dashboard.

**Build:** Draw an SVG with three horizontal guide lines, two thin polylines or smooth paths, outlined circular markers at three milestones, and one low dotted benchmark path. Add a faint blue area under the improving curve. Keep legend dots small and labels mono; use a single endpoint annotation for each series.

### Grainy atmospheric glass stage

**Only for:** assistant-style product pages

**Use:** Media half of the opening and alternating feature panels.

**Observed:** Large diffused teal, sage and navy shapes swell diagonally through a fine noisy field. Near-white upper areas flow toward deep lower corners; translucent pale UI cards float centrally over the grain. The imagery takes about half the opening and two thirds of later panels.

**Transfer:** Give a focused utility product its own lighter, more restrained treatment without changing the main brand's default. Minimum acceptable version is a grainy layered gradient behind a few crisp glass records.

**Build:** Layer a 145deg gradient from off-white through pale gray-green, mist teal and deeper teal into navy. Add a radial white glow at 16% 18% fading by 34% and a teal glow at 82% 72% fading by 44%. Blur large curved masks, then overlay SVG feTurbulence monochrome noise at low opacity to create fine visible grain. Place Assistant glass cards above it; vary sage versus blue fields by chapter, keeping exact glow stops subordinate to the soft light.

### Blue halftone editorial panels

**Only for:** company values and culture storytelling

**Use:** Three-column illustrated editorial cards.

**Observed:** Conceptual photographic silhouettes, including a climber, a standing figure and a craftsperson, become high-contrast electric-blue halftones over pale blue-white. The rectangular images have 16px corners, with plain dark titles and gray descriptions outside the image.

**Transfer:** Choose metaphoric imagery appropriate to the new organization, then apply a consistent duotone halftone process instead of unrelated stock illustrations.

**Build:** Convert a high-contrast monochrome source to a blue/near-white duotone; use an SVG dot screen or a fine repeating dot mask whose dot density follows luminance. Preserve large silhouette shapes and light backgrounds so the subject reads at card scale.

### Neutral portrait triptych

**Only for:** company and people pages

**Use:** Backers, partners or team proof.

**Observed:** Black-and-white waist-up portraits on flat warm stone backings, with 16px rounded corners, matched image height and small unboxed captions below. A restrained monochrome logo row precedes the portraits.

**Transfer:** Use consistent portrait framing and grayscale conversion; align eyes and subject scale rather than mixing casual profile thumbnails with studio portraits.

### Icons

**Observed:** Outline icons are compact and round-capped: 26px blue capability icons, mostly 16px and 20px utility icons at 1.8px stroke, and 20px accordion chevrons at 1.6px stroke. Mono check glyphs and separate slim arrows supplement SVG icons.

**Transfer:** Choose a coherent thin outline family, use cornflower or sapphire for signals and dark neutral for controls. Avoid filled multicolor feature illustrations; third-party integration marks may retain their original colors inside product demonstrations.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A 900px first screen combines an 826px full-bleed photographic field and a 74px black proof strip. The fixed Navigation overlays the top. From back to front: espresso backing, warm street scene, subtle local contrast scrim, left-aligned white text and actions. The display headline wraps into two lines within 480px, about one third of the viewport width; support is limited to 400px. The text group is vertically centered with a slight downward bias and uses 26px gaps. The Primary button and underlined Text link sit side by side below the paragraph. The full main scene, headline, support, actions and proof strip are visible within 900px; the first explanatory card grid begins below the fold. The strip carries small checks and short assurance statements across the width, with a secondary linked assurance label beneath.

**Transfer:** For a new marketing product, stage a real use context with a human or architectural focal point on the right and dark negative space on the left. Without custom film, use the Cinematic everyday life still-image treatment. Product-detail pages retain this composition with a more literal benefit headline. Pricing pages instead open on white with 128px top padding, the display recipe and one short support line. The assistant-style variant uses a small 28px headline on the left and a grainy demonstration field on the right.

**Avoid:** Do not replace the scene with a centered dashboard floating on a gradient, a giant logo, or an all-white hero with oversized type. Do not place the proof strip below a second screen of empty space.

**Text style:** `display` — Archivo 600 · 64px/70px · tracking -0.03em

### Section heading pair

**Observed:** A left-aligned heading sits within the main container, followed by a 17px/27px supporting paragraph with about 20px separation. Main bands use 112px vertical padding; heading-to-grid spacing commonly opens to 56px. Selected broad proof headings are centered.

**Transfer:** State the benefit in the heading, then explain how it works in one compact paragraph. Use the existing section scale rather than introducing a unique type size for every chapter.

**Text style:** `heading` — Archivo 500 · 54px/60px · tracking -0.02em

### Capability row

**Observed:** Four Capability cards span the main container with 20px gutters. All labels, top-right icons and bottom links align; short paragraphs do not pull the links upward. A compact row of small channel pills and a centered dark action can sit below.

**Transfer:** Use a manageable set of distinct outcomes. If the product has fewer capabilities, preserve the card construction rather than adding filler categories.

**Text style:** `card-heading` — Archivo 500 · 26px/32px · tracking -0.02em

### Asymmetric numbered framework

**Observed:** Numbered tiles form two paired rows with 20px gaps, first slightly wider on the left and then wider on the right. White tiles share space with a black tile and a pale periwinkle tile; 16px internal stacks lead from number to title, description and wrapped tags.

**Transfer:** Map the product's operating principles or stages to a coherent small framework. The tinted and inverted tiles should highlight meaningful contrasts.

**Text style:** `tile-heading` — Archivo 500 · 34px/40px · tracking -0.02em

### Product chapter deck

**Observed:** A white heading introduces the Charcoal stage. Large Chapter panels repeat as a sticky desktop deck, showing text on the left and a white working vignette on the right. At rest the main panel reads straight; incoming panels can tilt slightly as they overlap. A small mono summary and a white exploration action close the dark band.

**Transfer:** Give each panel one operational benefit and one visual example. Keep the deck device even if fewer chapters are needed; a static series of pale panels is the narrow-screen treatment.

**Text style:** `chapter-heading` — Archivo 500 · 44px/50px · tracking -0.02em

### Quantified assurance

**Observed:** The Proof band pairs a narrow proof-heading, body paragraph, blue-check assurance list and black action on the left with the Measured trajectory graphic on the right. A separate compact black security strip uses small white text, pale-blue links and circular certification marks.

**Transfer:** Address adoption risk with real commitments and verifiable measures. When there is no longitudinal metric, use a compact measured comparison in the same white plot card rather than inventing a trend.

**Text style:** `proof-heading` — Archivo 500 · 58px/62px · tracking -0.02em

### Quote wall

**Observed:** A centered proof-heading introduces two horizontally overflowing, offset rows of Testimonial cards. Cards mix white, cream, cornflower and black, and vary height with the quotation. Attribution uses a small avatar, a compact name and an 11px mono role/company caption.

**Transfer:** Make proof feel populated and human, while keeping each quote short enough to scan. The wall can be placed wherever trust is needed; it need not follow a fixed sequence.

**Text style:** `quote` — Archivo 500 · 18px/26px · tracking -0.01em

### Photographic closing

**Observed:** A full-width architectural scene returns after the main story. The taller default is 840px, with centered text beginning 128px into the section; shorter product, company and commercial variants are 640px with 64px display type. A maximum 860px title and 560px support line lead to paired solid and outlined actions with a 16px gap. The Directory shell follows immediately.

**Transfer:** Restate the reader's desired change, not a final feature list. Keep the physical environment and visible human movement; the closing is a memorable scene rather than a generic CTA box.

**Text style:** `closing-display` — Archivo 600 · 68px/74px · tracking -0.03em

### Directory ending

**Observed:** A small brand mark anchors the left rail while six link groups occupy a three-column, two-row grid on the right. The 1176px container is narrower than the main content; muted 13px labels contrast with 14px links, and the olive system-status line sits low in the identity rail.

**Transfer:** Group the new site's real destinations into a clear directory. Preserve the airy identity rail and practical small-text ending.

**Text style:** `footer-link` — Archivo 400 · 14px/1.55

### Commercial comparison system

**Only for:** pricing pages

**Observed:** White title-led opening gives way to touching Plan columns with colored upper surfaces and white feature lists. A black assurance strip separates the plans from a warm deployment band. Two large setup-comparison cards contrast cream and charcoal using lightweight 50px titles. Cost modeling uses ruled tables, small numeric annotations and restrained inputs. Add-ons sit in a 20px-radius cream panel with internal vertical rules. The long comparison table has 48px rows, faint column dividers and pale category bands; FAQs split an introduction from a 738px question list.

**Transfer:** Keep the commercial page more tabular and information-dense than the narrative landing page. Use surface progression to distinguish options without a bright recommended-plan badge.

**Text style:** `commercial-display` — Archivo 300 · 50px/1

### Assistant alternating chapters

**Only for:** assistant-style product pages

**Observed:** The split opening is followed by alternating text/media panels on a pale paper frame. Each 735px chapter combines a small sentence-case heading, 24px statement and compact bullets with a 700px-high Grainy atmospheric glass stage. A black rounded marketplace call precedes a two-column contact section: 626px-wide underlined fields on the left and a 626px by 640px warm human video on the right. This page closes with that form and the Directory shell, not the default full-width architectural closing.

**Transfer:** Use this variant for a focused hands-on assistant or utility. Retain the human photographic finish through the form-side media while keeping the feature story more interface-led.

**Text style:** `assistant-statement` — Geist 400 · 24px/1.25

### Company editorial proof

**Only for:** company and recruiting pages

**Observed:** A cinematic human-group opening uses the default display scale. Warm three-column Blue halftone editorial panels introduce principles; a white benefits list uses 640px ruled rows and leaves abundant space beside it. A logo row and Neutral portrait triptych establish credibility; simple ruled role links lead into the shorter Photographic closing.

**Transfer:** Use the same warmth and strong typography for a company story, but let metaphoric images, people and plain lists replace product demonstrations.

**Text style:** `heading` — Archivo 500 · 54px/60px · tracking -0.02em

## Page flow

**Storyline:** Promise → concrete outcomes → operating model → working demonstrations → risk reduction and proof → decisive invitation → practical directory; emphasis and order adapt to the page's job.

### Broad product and platform landing page

1. **Promise** — Cinematic opening with a narrow benefit headline and black assurance strip.
2. **Outcome map** — Capability row followed by an asymmetric numbered framework and a before/after trajectory.
3. **Product demonstration** — Long charcoal chapter deck explains operations through isolated working vignettes.
4. **Risk reduction** — Cool proof band with a measured chart, then a narrow security strip.
5. **Social proof** — Offset mixed-color quote wall.
6. **Closing call** — Tall centered photographic invitation followed by the airy directory.

**Transfer:** Move from an ambitious promise to tangible operations, then remove risk. Keep the signature scenes, panel deck and proof devices without reproducing the same section count.

### Specific capability detail page

1. **Promise** — Full-width human photograph with a concrete benefit title and a concise assurance strip.
2. **Conceptual model** — Four numbered white overview cards on parchment.
3. **Capability chapters** — Charcoal band containing pale split panels with memory, analysis or action examples.
4. **Business proof** — Plain two-column readout of outcomes and controls.
5. **Ecosystem fit** — A shared capability-card pattern relates the detail to the broader system.
6. **Closing call** — Shorter photographic invitation and common directory.

**Transfer:** Narrow the story to one capability; use working examples and an explicit business readout instead of repeating every platform feature.

### Focused assistant product page

1. **Promise** — Small left-aligned headline beside a full-height grainy interactive demonstration.
2. **Capability demonstration** — Alternating broad media/text chapters show connected tools, recurring work, learning and governance.
3. **Expansion path** — Black rounded marketplace call.
4. **Conversion form** — Underlined form fields beside warm human video.
5. **Directory** — Common off-white footer, with the variant's Geist typography.

**Transfer:** Use the smaller, more hands-on variant as a coherent page system, including its form-led ending.

### Company credibility and recruiting

1. **Mission promise** — Human-group street scene with the default large white headline.
2. **Principles** — Three blue halftone editorial illustrations with plain captions.
3. **Practical offer** — A short unboxed ruled list on white.
4. **Credibility** — Monochrome partner marks and neutral grayscale portraits.
5. **Actionable opportunities** — Simple role rows with small blue arrows.
6. **Closing call** — Short centered architectural scene and common directory.

**Transfer:** Alternate values and practical facts; preserve warmth without making the people story look like a product dashboard.

### Commercial evaluation and purchase confidence

1. **Commercial promise** — White headline-led opening with one pricing principle.
2. **Plan selection** — Touching tinted plan columns, aligned actions and white feature lists.
3. **Risk reduction** — Black assurances and a cream deployment-support band.
4. **Setup choice** — Paired cream and charcoal comparison cards.
5. **Quantified value** — Ruled cost-model table and understated numeric results.
6. **Detail and expansion** — Cream add-on panel and long categorized comparison matrix.
7. **Objection handling** — Split heading and FAQ list on parchment.
8. **Closing call** — Short photographic invitation and common directory.

**Transfer:** Make costs and conditions easy to compare; use the same cinematic finish to reconnect dense commercial detail to the human promise.

## Writing

Confident, operational and human. Benefits are expressed as completed work and measurable change, while technical detail makes the promise credible rather than futuristic.

**Do not copy:** Do not reuse Applied Labs names, logos, customer names, portraits, quotations, proprietary artwork, plan economics or outcome claims. In particular, automation, CSAT, error-rate, launch-time and savings figures require the new product's own substantiation. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use 'your' for the reader's team, tools, customers and desired results. Product descriptions usually name the product or use an active imperative; 'we' is reserved for company beliefs and direct commitments.
- **Rhythm:** Short sentence-case headlines, usually four to ten words, followed by one or two concrete sentences. Contrast constructions, periods and occasional em dashes replace exclamation marks and rhetorical flourish.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A compact reframing of familiar work, stated as a complete thought. | 4–9 words | “Think outside the inbox.”<br>“Unified Customer Memory” |
| Section lead | Tie an operational capability to a business consequence; use contrast when useful. | 6–12 words | “Most AI stops at the inbox. Applied starts there.”<br>“Complete customer state before the reply.” |
| Feature headline | Lead with a concrete action, not a noun pile. | 4–10 words | “Turn SOPs into precise AI actions.”<br>“Recall the customer before the reply is written.” |
| Supporting line | Name what connects, what acts and how the result is verified. | 15–35 words | “Give AI agents and human teams a unified profile, memory, and timeline for every customer.”<br>“Pay for outcomes, not seats. Every plan includes unlimited teammates.” |
| Proof language | Define what is counted and refuse an easier but misleading measure. | 1–2 sentences | “A resolution counts only when the AI resolves it end to end.” |
| Primary action | Plain verb plus an explicit next step. | 2–5 words | “Book a demo”<br>“See open roles” |
| Closing line | Return to the desired change with a short positive declaration. | 4–9 words | “Grow revenue and delight customers.”<br>“Come build with us.” |

**Words and phrasing to use:** real outcomes; source-backed; end to end; before the reply; without losing context; verified; map; resolve; protect; launch; write back; controls

**Avoid:** revolutionary; magic as a product claim; supercharge everything; infinite possibilities; effortless transformation; vague autonomous promises

**Rules:**

- Pair every broad benefit with a named mechanism or an observable result.
- Describe work that finishes, not just work the system touches.
- Use technical nouns only when they clarify an operation; define consequences in ordinary language.
- Commercial copy states units, conditions and included access plainly.
- Keep labels terse and factual; do not add conversational jokes to the mono markings.

## Do's and Don'ts

### Do

- Keep the opening display at 64px/70px and -0.03em, with copy limited to a narrow column against full-width media.
- Use 112px vertical breathing room around major narrative bands and 64px desktop side insets.
- Give pale chapter panels 24px corners and a restrained 1px translucent dark edge.
- Preserve small blue mono labels and checkmarks as recurring technical signals.
- Include a black assurance strip with concise, supportable proof rather than a row of oversized statistics.
- Keep the numbered-grid contrast to white, black and one periwinkle accent, with 20px gutters.
- Stage product examples on white with enough internal margin to remain readable at half-panel width.
- Finish the main marketing narrative with centered white type over warm real-world photography, then a small-text directory.

### Don't

- Do not make sapphire the default large-area background or primary button color; it functions as a signal.
- Do not replace the warm #3d3838 product stage with pure black; reserve near-black for sharper assurance and emphasis.
- Do not give every card the same 24px radius: small capability cards use 16px and quotes use 14px.
- Do not set all headings in semibold; section and feature titles use weight 500, while commercial comparison titles can use 300.
- Do not use pills for every conversion action; the principal photographic buttons have 8px corners.
- Do not turn 11px mono markings into large uppercase marketing headlines.
- Do not treat product-demo micro-labels as a second global marketing type system.
- Do not expand the footer into a giant slogan or oversized wordmark; its identity mark and directory text remain compact.

## Motion and responsive

### Motion

**Observed:**

- The desktop feature panels use sticky positioning and overlapping translated/rotated card layers; settled frames read as nearly straight panels.
- Primary white actions declare color transitions over 0.2s with cubic-bezier(.4, 0, .2, 1); outline closing actions use .15s with the same curve.
- The fixed header declares background, backdrop-filter and color transitions over 0.3s with cubic-bezier(0, 0, .2, 1).
- Quote rows are horizontally translated and expose a grab cursor. Accordion chevrons declare a 180deg rotation in the open state.

**Transfer:**

- Keep the panel-deck transition subordinate to the readable settled layout; use the same pale cards and charcoal stage in the static version.
- Use subtle fill and color feedback rather than colored glow or large button movement.

**Unknown:**

- Panel entrance timing, scroll interpolation, quote autoplay timing and media playback behavior are not established.

### Responsive

**Observed:**

- The default opening headline has declared 44px, 56px and 64px sizes; the desktop line height is 70px.
- The capability grid declares one column, then two, then four; major content insets declare 20px, 32px and 64px variants.
- The numbered mosaic declares a single-column base before the desktop asymmetric two-column layout.
- Chapter panels declare stacked content before desktop horizontal composition; the fixed desktop navigation is hidden below its medium layout.
- Assistant chapters declare a two-column composition from a 900px breakpoint; the commercial grid declares one, two and five columns.

**Transfer:**

- On narrow screens, keep the human focal point in the photographic field, stack actions when necessary and preserve the black assurance device as a compact wrapping band.
- Stack the chapter panels in reading order, keeping the demonstration below its explanatory copy rather than reducing it to illegible thumbnail size.
- Preserve the distinction between the cinematic default and the compact assistant variant while reducing columns.

**Unknown:**

- Actual mobile navigation behavior, image focal-point changes, comparison-table overflow behavior and reduced-motion behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
