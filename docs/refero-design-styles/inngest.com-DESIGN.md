# Inngest — grain and signal

## Overview

A dark, technically fluent style with the tactile roughness of printed matter and the energy of a live system. Regular grotesk headlines, outlined emphasis and equipment-like mono labels sit over smoky charcoal, interrupted by coral and electric blue. Real interfaces, monochrome portraits and fine particle sculptures give developer tools and complex platforms a concrete, human presence. Spacious chapters alternate with dense, practical comparisons and proof.

### Essentials

- The promise has a hollow punchline: 72px regular uppercase grotesk at 0.95 line height and -0.02em tracking, with the final emphasis drawn as a 1px white outline rather than a colored word.
- The opening pairs a manifesto with a working artifact: a 576px text column inside a 1280px composition, a comparably sized technical scene to its right, 42px actions underneath, and a monochrome proof ticker along the bottom of the first 900px.
- Darkness is textured, not flat: #1c1c1c canvas, near-black directional panels, fine grain and a soft charcoal light patch. Most of the page remains dark; electric blue gets a broad editorial interruption while coral concentrates in the 32px announcement band, labels and conversion actions.
- Actions look like instrument keys: 6px corners, 42px height, 20px horizontal padding and 12px semibold uppercase mono with 0.8px tracking. Pair a coral or white key with a transparent key outlined by a 2px inset white stroke.
- Evidence is staged as an object, not a stock illustration: wide black interface panels have 10px corners and a faint 1px gradient edge; human proof uses grainy monochrome portraits. Without a polished interface, use a compact truthful process diagram in the same black frame.
- Fine points turn engineering into atmosphere: include a white particle ribbon or twisted dot field near a closing action, continuing more faintly through the footer. Use 1px SVG dots along curved paths as the minimum version, not a generic starfield.
- Feature chapters have a connected reading rail: a hairline vertical rule and 11px round nodes sit left of 480px text columns, beside wider 751px media, with 48px column gaps and 120px chapter spacing.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal coral | `#f65c4f` | `--color-coral` | action, accent, link | Default opening conversion button, technical eyebrows, active markers and link hover. |
| Electric blue | `#013cf6` | `--color-blue` | background, accent | Broad editorial band and the simplified side of a before/after comparison; concentrated rather than ubiquitous. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm coral field | `#f76246` | `--color-warm-fill` | background | Announcement strip and textured highlighted proof surfaces; large fills belong to highlighted commercial content rather than every feature. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Frost | `#ffffff` | `--color-white` | text, action, border | Headlines, interface outlines and white conversion buttons. |
| Soft white | `#f6f6f6` | `--color-basis` | text | General inherited text and secondary feature headings. |
| Reading gray | `#b3b3b3` | `--color-body` | text | Supporting paragraphs, small descriptions and footer links. |
| Graphite edge | `#7c7c7c` | `--color-edge` | border, text | Proof-card borders and subdued markers; also used at 0.35–0.55 alpha in directional edge gradients. |
| Raised charcoal | `#212121` | `--color-elevated` | surface | Status badge, diagrams and raised panel tone. |
| Charcoal canvas | `#1c1c1c` | `--color-canvas` | background | Main painted page base beneath grain and atmospheric lighting. |
| Panel black | `#020202` | `--color-panel` | surface | Deep end of directional black panel gradients. |
| Absolute black | `#000000` | `--color-black` | text, background | White-button lettering and the scrolled navigation backing. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#0bdd48` | `--color-green` | accent | Small square operational indicator; reserve for state rather than marketing emphasis. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Comparison edge | `#cdcdcd` | `--color-contrast-edge` | border | Brighter outlines around tier cards and pricing tools. |
| resource closing sections | Resource indigo | `#2f33cb` | `--color-resource-blue` | background | Color-blend overlay on one half of a grainy resource banner. |

## Typography

- **Whyte** — Primary headings and testimonial prose; the primary heading cut is declared WhyteV1. Direct, wide-open grotesk with regular strokes and tightly spaced large text. If unavailable, use **Inter**. 400; preserve the tight tracking and line breaks. Font stack: "Whyte", Inter, -apple-system, system-ui, Segoe UI, Roboto, sans-serif.
- **WhyteMono** — Uppercase technical labels, navigation and action text; declared WhyteMonoV1. Utilitarian monospaced lettering, visibly tracked at small sizes. If unavailable, use **IBM Plex Mono**. 400 for labels, 600 for actions. Font stack: "WhyteMono", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, monospace.
- **CircularXX** — Paragraphs and practical detail. Soft geometric sans with round forms that temper the harder mono labels. If unavailable, use **DM Sans**. 400 with -0.01em tracking. Font stack: "CircularXX", "DM Sans", Inter, -apple-system, system-ui, Segoe UI, Roboto, sans-serif.
- **Whyte Inktrap** (only for product-detail, use-case, pricing and company pages) — Uppercase editorial section headings and split colored openings. Regular grotesk display with subtle ink traps and less compressed tracking than the default headings. If unavailable, use **Space Grotesk**. 400; retain the measured widths through line breaks. Font stack: "Whyte Inktrap", "Space Grotesk", Inter, system-ui, sans-serif.
- **CircularXXMono** (only for technical actions and product demonstrations) — Literal commands and code artifacts, not marketing paragraphs. Compact code lettering with conventional terminal proportions. If unavailable, use **IBM Plex Mono**. Font stack: "CircularXXMono", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Whyte | 400 | 72px | 0.95 | -0.02em, uppercase | size clamp(2.75rem, 6.5vw, 4.5rem) | Opening promise; final phrase receives transparent fill and a 1px white text stroke. |
| heading-lg | Whyte | 400 | 64px | 1.1 | -0.035em | size clamp(2rem, 4.6vw, 4rem) | Default major section heading, sentence case. |
| heading-lg-loose | Whyte | 400 | 64px | 1.25 | -0.035em | size clamp(2rem, 4.6vw, 4rem) | Multiline broad statements, editorial band and getting-started heading. |
| chapter-heading | Whyte | 400 | 43.2px | 1.1 | -0.02em | size clamp(2rem, 3vw, 2.75rem) | Feature chapter heading adjacent to product media. |
| heading-sm | Whyte | 400 | 26px | 1.2 | -0.01em | fixed | Capability tiles, proof-card quotes and footer column headings. |
| quote | Whyte | 400 | 26px | 1.4 | normal | size clamp(20px, 1.9vw, 26px) | Long customer testimonial beside a monochrome portrait. |
| lead | CircularXX | 400 | 20px | 1.5 | -0.01em | size clamp(1rem, 2.6vw, 1.25rem) | Opening support copy. |
| body | CircularXX | 400 | 18px | 1.5 | -0.01em | size clamp(1rem, 2.4vw, 1.125rem) | Section support and feature explanations. |
| eyebrow | WhyteMono | 400 | 16px | 1 | 0.05em, uppercase | fixed | Technical chapter labels and arrow links. |
| body-sm | CircularXX | 400 | 16px | 1.5 | -0.01em | fixed | Tile paragraphs, comparison details and footer links. |
| action | WhyteMono | 600 | 12px | 1.5 | 0.067em, uppercase | fixed | Filled and outlined button labels. |
| navigation | WhyteMono | 600 | 12px | 1 | 0.067em, uppercase | fixed | Compact navigation links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company pages | company-display | Whyte Inktrap | 400 | 80px | 1.25 | -0.01em, uppercase | size clamp(2.75rem, 7.5vw, 5rem) | Two-line company introduction. |
| product-detail, use-case, pricing and company pages | editorial-heading | Whyte Inktrap | 400 | 64px | 1.25 | -0.01em, uppercase | size clamp(2rem, 4.6vw, 4rem) | Section leads for detailed product, use-case, commercial and company narratives. |
| resource closing sections | resource-display | Whyte | 400 | 64px | 1 | normal, uppercase | fixed | Two short words aligned with halves of a resource banner. |
| product-detail and use-case openings | split-display | Whyte Inktrap | 400 | 63.4px | 1 | -0.01em, uppercase | fixed | Staggered promise split across two colored columns. |
| pricing pages | pricing-display | Whyte Inktrap | 400 | 58px | 70px | -0.01em, uppercase | fixed | Centered compact commercial opening. |
| pricing pages | price | Whyte | 400 | 44px | 1 | -0.02em | fixed | Tier price or custom-pricing word. |
| quantified commercial proof | stat | Whyte | 400 | 38px | 1 | -0.01em, uppercase | fixed | Short outcome numerals and units beneath mono captions. |
| use-case capability grids | primitive-heading | Whyte | 400 | 36px | 1.1 | -0.01em | fixed | Larger heading inside illustrated capability cards. |
| company team grids | portrait-name | CircularXX | 600 | 15px | 1.3 | -0.01em | fixed | Name beneath each team portrait. |
| company team grids | portrait-caption | CircularXX | 400 | 13px | 1.3 | normal | fixed | Subdued job title under a name. |
| technical actions | command-action | CircularXXMono | 600 | 12px | 1.5 | 0.067em | fixed | Copyable command inside an outlined action. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular weight, not boldness, carries headline scale. The default sentence-case 64px headings use tighter -0.035em tracking than the uppercase editorial variant's -0.01em.
- Mono text distinguishes navigation, labels and actions from prose. Literal commands retain their case.
- Keep the outlined final promise at the same size and rhythm as the solid headline; the outline is an emphasis treatment, not a separate logo.

## Layout

**Density:** Airy at the chapter level, compact inside technical artifacts and commercial comparisons.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight caption and name stacks. |
| 10px | Status indicator gap and compact repeated rows. |
| 12px | Tile title-to-description gap. |
| 16px | Paired action gap and compact media grids. |
| 20px | Tile padding and paragraph stacks. |
| 24px | Heading-to-support gap in centered introductions and feature-grid column gap. |
| 32px | Desktop page gutters and heading-to-action stacks. |
| 40px | Team-grid gaps and inset reading rail. |
| 48px | Default section stack and chapter column gap. |
| 64px | Introduction-to-main-media gap and panel top padding. |
| 80px | Footer top padding and smaller-screen section rhythm. |
| 96px | Intermediate section rhythm. |
| 120px | Space between connected feature chapters. |
| 160px | Major desktop section top and bottom padding. |

### Containers and grids

- **page-container**: max width 1440px · side padding 32px. Centered desktop sections with 1376px usable width.
- **opening-composition**: max width 1280px · gap 64px. Balanced promise and technical artifact; text column max-width 576px and support max-width 560px.
- **chapter-pair**: 2 columns · gap 48px. Text/media proportions 5:7; text max-width 480px, 40px inset for the reading rail.
- **capability-grid**: 3 columns · gap 24px. Three columns with 32px row gaps; tiles are about 443px wide.
- **proof-grid**: 3 columns · gap 32px. Three equal quote cards, about 437px wide.
- **footer-grid**: 3 columns · gap 160px. Five navigation groups across two rows, with 48px row gaps; the remaining position holds assurance material.
- **commercial-grid** (only for pricing pages): 4 columns · gap 20px. Four equally aligned plan columns, each about 329px wide.
- **team-container** (only for company pages): max width 1440px · side padding 70px. 1300px usable width with four portrait columns and 40px gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-small-panels | 6px |
|  | wide-product-media | 10px |
|  | quote-cards | 8px |
|  | tags-and-carousel-controls | 9999px (pill) |
| pricing pages | featured-commercial-surface | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| outline-key | `0px 0px 0px 2px #ffffff inset` | Button outline rather than a drop shadow. |

### Surfaces

#### Grained canvas · level 0

**Use:** Default page atmosphere.

**CSS:** `background-color: #1c1c1c; color: #f6f6f6`

**Observed:** Fine irregular grain crosses the whole canvas. A diffuse diagonal charcoal illumination lifts the right side while the left remains almost black.

**Transfer:** Layer a low-opacity monochrome noise texture and a broad, soft white light patch over the base; keep text crisp above both.

#### Directional black panel · level 1

**Use:** Large proof grouping and framed media.

**CSS:** `background-image: linear-gradient(297deg, rgba(33, 33, 33, 0) -2.25%, #020202 46.83%); border-radius: 10px; overflow: hidden`

**Observed:** Near-black on one side and transparent charcoal on the other, with a separately drawn 1px gradient perimeter. Smaller detailed-page panels use 6px corners.

**Transfer:** Use a wrapper edge layer and an inset content layer rather than a heavy uniform border.

#### Gradient perimeter · level 2

**Use:** Faint directional edge on dark panels.

**CSS:** `background-image: linear-gradient(135deg, rgba(124, 124, 124, 0.35) 0%, rgba(124, 124, 124, 0.55) 32%, rgba(124, 124, 124, 0.02) 72%, rgba(124, 124, 124, 0.5) 100%); padding: 1px; border-radius: 10px`

**Observed:** Only the perimeter shows; the center is masked or covered by the content layer.

**Transfer:** Nest the Directional black panel inside this wrapper, keeping the edge thin.

#### Electric editorial field · level 0

**Use:** A forceful interruption within the predominantly dark narrative.

**CSS:** `background-color: #013cf6; color: #ffffff`

**Observed:** Full-width blue backing with grain and a rough black pixel dissolution at one edge. Product media can bridge its lower boundary.

**Transfer:** Give a single big claim room on the field; retain dark chapters around it.

#### Coral proof field · level 1

**Only for:** commercial proof and pricing pages

**Use:** Highlighted plan or outcome card.

**CSS:** `background-color: #f76246; border-radius: 4px`

**Observed:** Fine soft-light grain and a warm radial highlight make the fill tactile rather than flat; the selected surface projects slightly beyond its neighbors.

**Transfer:** Layer a radial rgba(255,210,195,0.32) highlight fading by 65% and fine noise over the fill; emphasize one item.

## Components

### Navigation

**Use:** Persistent orientation and a compact conversion entry.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; z-index: 50`

**Text style:** `navigation` — WhyteMono 600 · 12px/1 · tracking 0.067em · uppercase

**Observed:** An 88px opening header includes a 32px coral announcement strip above a single compact navigation row. Brand at left, links across the center, utility links and a 32px white action at right. After scrolling, a black inset bar with small corners carries a simplified brand mark.

**Transfer:** Keep utilities subordinate and preserve the low, instrument-like profile.

### Coral button

**Use:** Default opening conversion action.

**CSS:** `background-color: #f65c4f; color: #ffffff; border-radius: 6px; height: 42px; padding: 0px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — WhyteMono 600 · 12px/1.5 · tracking 0.067em · uppercase

**Observed:** Content-sized key paired with a transparent command or documentation action.

**States:** Declared: hover background-color rgb(217 74 43 / 1).

### White button

**Use:** Main actions on dark proof sections and the highlighted plan.

**CSS:** `background-color: #ffffff; color: #000000; border-radius: 6px; height: 42px; padding: 0px 20px; box-shadow: 0px 0px 0px 2px #ffffff inset`

**Text style:** `action` — WhyteMono 600 · 12px/1.5 · tracking 0.067em · uppercase

**Observed:** A bright rectangular key; the navigation variant is 32px high. Commercial outcome cards stretch it across the available width.

**States:** Declared: hover background-color rgb(246 92 79 / 1), color rgb(255 255 255 / 1), box-shadow none.

### Outline button

**Use:** Companion documentation or secondary action.

**CSS:** `background-color: transparent; color: #ffffff; border-radius: 6px; height: 42px; padding: 0px 20px; box-shadow: 0px 0px 0px 2px #ffffff inset`

**Text style:** `action` — WhyteMono 600 · 12px/1.5 · tracking 0.067em · uppercase

**Observed:** Pairs with a filled key at a 16px gap. A technical variant uses command-action type, a small copy icon at left, and a literal command instead of uppercase prose.

**States:** Declared: hover background-color rgb(246 92 79 / 1), color rgb(255 255 255 / 1), box-shadow none.

### Technical link

**Use:** Lightweight chapter navigation.

**CSS:** `display: inline-flex; align-items: center; color: #ffffff; text-transform: uppercase`

**Text style:** `eyebrow` — WhyteMono 400 · 16px/1 · tracking 0.05em · uppercase

**Observed:** A short label followed by a right arrow separated by 8px; no enclosing surface.

**States:** Declared: hover color rgb(246 92 79 / 1); focus-visible color rgb(246 92 79 / 1). The arrow translates 6px on hover.

### Capability tile

**Use:** Scannable overview of practical applications.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; gap: 32px; padding: 20px; border: 1px solid transparent; border-radius: 6px`

**Text style:** `heading-sm` — Whyte 400 · 26px/1.2 · tracking -0.01em

**Observed:** Small wire illustration, heading, short body-sm description, then an uppercase learn-more link. The resting tile nearly disappears into the canvas.

**States:** Declared: hover border-color rgb(255 255 255 / .18); focus-visible box-shadow 0 0 #0000, 0 0 #0000, 0 0 #0000.

### Status badge

**Use:** Operational reassurance above footer navigation.

**CSS:** `display: flex; align-items: center; gap: 10px; padding: 16px 20px; background-color: #212121; border-radius: 6px`

**Text style:** `body-sm` — CircularXX 400 · 16px/1.5 · tracking -0.01em

**Observed:** An 8px square green indicator precedes the muted label. It is a compact utility, not a pill-shaped marketing badge.

### Footer columns

**Use:** Deep navigation at the end of every page type.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); column-gap: 160px; row-gap: 48px`

**Text style:** `heading-sm` — Whyte 400 · 26px/1.2 · tracking -0.01em

**Observed:** Five groups arranged across two rows. Headings precede body-sm links by 32px; links have 16px gaps. A small assurance seal occupies the remaining area, followed by a low legal row. Sparse white and blue particles sit behind, never over the text.

**Transfer:** Keep only relevant navigation groups; preserve the spacious multirow composition and a factual assurance slot.

### Pricing plan

**Only for:** pricing pages

**Use:** Commercial comparison with one highlighted tier.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 32px 32px 16px; border: 1px solid #cdcdcd; border-radius: 6px`

**Text style:** `heading-sm` — Whyte 400 · 26px/1.2 · tracking -0.01em

**Observed:** Title, brief audience description, price, full-width action, then grouped check lists. The recommended tier uses Coral proof field, a dark floating popular pill and a White button; other tiers keep Outline button. Align the price and action rows across columns.

**Transfer:** Use real tier differences and a single visually emphasized recommendation.

### Quote card

**Only for:** product-detail and use-case proof grids

**Use:** A collection of attributable short endorsements.

**CSS:** `background-image: linear-gradient(297deg, rgba(33, 33, 33, 0) -2.25%, #020202 46.83%); border: 1px solid #7c7c7c; border-radius: 8px; padding: 16px 24px 32px 32px; display: flex; flex-direction: column; gap: 10px`

**Text style:** `heading-sm` — Whyte 400 · 26px/1.2 · tracking -0.01em

**Observed:** Avatar and attribution at top, small dark topic/source pills, prominent regular-weight quote, then an uppercase link pinned toward the bottom. Equal-height cards preserve uneven quote lengths.

### FAQ disclosure

**Only for:** pricing and use-case objection handling

**Use:** Plainspoken answers without a wall of boxes.

**CSS:** `position: relative; padding: 20px 16px; overflow: hidden`

**Text style:** `body-sm` — CircularXX 400 · 16px/1.5 · tracking -0.01em

**Observed:** A 24px marker slot contains an 8px square: coral for the open answer and gray for closed questions. Question text is about 20.2px with 1.45 line height; the answer uses body-sm and begins 16px below. One answer is open beside a separate large FAQ heading.

**Transfer:** Use literal customer questions; keep the square state cue instead of a large plus icon.

### Primitive card

**Only for:** use-case capability grids

**Use:** Illustrated technical mechanisms with documentation entry points.

**CSS:** `background-color: #212121; border: 1px solid rgba(255,255,255,0.6); border-radius: 4px; padding: 24px 24px 32px`

**Text style:** `primitive-heading` — Whyte 400 · 36px/1.1 · tracking -0.01em

**Observed:** Outlined pill docs action near the top, centered white striped abstract glyph, then heading and explanatory body. Three columns with tight 10px gaps; cards are approximately 452px wide and 467px tall.

**Transfer:** Choose one meaningful mechanism per card and a consistent family of line-built glyphs.

## Imagery and graphics

### Grain and smoky illumination

**Use:** Continuous atmospheric foundation across the page.

**Observed:** A fine dark noise layer, subtly mottled rather than smoothly shaded. Light blooms diagonally across the right half; contrast stays low enough that white type and product frames remain dominant.

**Transfer:** Use the same tactile treatment even without any photography.

**Build:** Place SVG feTurbulence fractalNoise with baseFrequency around 0.8 and 3 octaves over #1c1c1c, desaturate, then blend soft-light at roughly 0.12 opacity. Under it add an oversized radial ellipse of rgba(255,255,255,0.07) fading to transparent across the right half. Match the soft glow; exact stops are not essential.

### Working artifact

**Use:** Opening technical scene and large feature demonstrations.

**Observed:** The opening shows code directly on the atmosphere, with two or three horizontal checkpoint bands and state tags along the left. Later media uses crisp black dashboard or editor frames, restrained syntax color and faint edges; wide demonstrations dominate more space than accompanying text.

**Transfer:** Show an honest task in progress. For a non-code product, use a real workflow or stripped-back interface with two clearly annotated states; keep it dark and legible rather than building a decorative fake dashboard.

**Build:** For the opening fallback, typeset a short real process in compact mono in a roughly 492px-wide scene. Highlight one row with translucent coral, one with muted green, add 2px left inset strokes, 8px corners and small state tags. Later stages sit in Directional black panel with Gradient perimeter.

### Particle ribbon

**Use:** Signature closing art and faint footer continuation.

**Observed:** Thousands of tiny white points form a sweeping twisted ribbon, more concentrated near the upper or right edges. It dissolves into sparse points behind footer navigation; occasional blue points introduce depth.

**Transfer:** Use a ribbon or loop that reflects the new product's movement, with the minimum version made as a static vector point field.

**Build:** Generate SVG circles of 1px diameter along 50–80 offset sinusoidal paths, with irregular sampling and opacity between 0.12 and 0.65. Bend the paths into a broad diagonal loop across a 1440px-wide artboard, leaving the left text area mostly empty. Spread a much sparser layer below it, with occasional #013cf6 dots. Do not substitute evenly random stars.

### Monochrome human proof

**Use:** Portrait-led customer story and testimonial carousel.

**Observed:** A close-cropped grayscale portrait is visibly dithered or stippled, without a colored card behind it. A tall portrait occupies roughly one third of the proof composition; logos, regular-weight quote, attribution and actions occupy the rest.

**Transfer:** Use a genuine customer portrait with a coarse monochrome halftone; keep the identity and quote legible and the backdrop nearly black.

### Wire and striped glyphs

**Use:** Small capability illustrations and explanatory steps.

**Observed:** Thin white orbit loops, radial fans, coils and stacked contour lines; usually monochrome, with rare colored state points. The forms look plotted, not hand drawn or filled like app icons.

**Transfer:** Choose a repeatable geometric metaphor for each capability.

**Build:** Use SVG ellipses rotated around a shared origin for orbit shapes; vary radii to create fans and springs. For card glyphs, clip 1px parallel white lines spaced 4px apart inside a circle, polygon or curved wedge. Keep them around 160–192px across in explanatory stages, smaller in overview tiles.

### Colored split sculpture

**Only for:** product-detail and use-case openings

**Use:** Alternative opening for deeper product narratives.

**Observed:** Two thirds of the width is saturated blue or coral, divided into two vertical panels with slightly different illumination; the last third is charcoal with a huge twisted particle torus. Type is staggered between the colored columns rather than centered on the whole scene.

**Transfer:** Use the blue treatment for platform mechanics and coral for an application story; preserve the contrast between flat typography and complex point geometry.

**Build:** Use three equal columns across a 799px-high stage. Fill the first two with the accent and layer a soft white radial wash across the center. In the last column, draw a rotated torus from repeated dotted ellipses or projected parametric points, white at low alpha on #212121, clipped at the stage edges.

### Team portrait wall

**Only for:** company team grids

**Use:** Dense human directory.

**Observed:** Four columns of 295px-wide cards. Grayscale cutout portraits fill a 295px by 271px image area backed by a sparse curved white dot lattice on black. A dark 92px caption area carries name and role, separated by a faint directional rule.

**Transfer:** Normalize different portrait sources through grayscale, shoulder-level framing and a consistent dot backing, while retaining natural expressions.

**Build:** Place transparent cutout portraits over a black SVG containing a 16px-spaced dot lattice warped gently into a wave. Keep points small and pale; use a 6px card radius and a 1px gradient edge. Caption padding is 24px vertically and 32px horizontally.

### Grainy resource diptych

**Only for:** resource closing sections

**Use:** A distinctive editorial ending before the footer.

**Observed:** A 5:1 panoramic banner splits at its midpoint: smoky grayscale light on one half, intense indigo on the other. White curved light masses feel soft and photographic, with heavy fine grain; two short words align to the lower edges of the halves.

**Transfer:** Recreate a two-part luminous abstract field rather than introducing unrelated stock photography.

**Build:** Use two equal overflow-hidden panels. Position oversized blurred white ellipses crossing their upper and lower edges, add dense monochrome noise, and apply #2f33cb with color blend mode to the right half. Anchor 64px uppercase text at each half's bottom edge.

### Icons

**Observed:** Functional icons are simple SVG outlines, commonly 16px or 24px with 1.5–1.8px strokes and round caps. White dominates; checks and state symbols use green. Arrows and copy symbols sit close to text; conceptual capability art is a separate, finer wire system.

**Transfer:** Use one consistent thin-outline icon set for controls. Keep the geometric illustrations distinct from utility icons and avoid multicolor filled badges.

## Section recipes

How recurring sections are built.

### First screen: Manifesto and working artifact

**Observed:** The first 900px is a complete composition: Navigation above a grained dark stage; a 1280px-wide inner composition balances left promise and right live-looking artifact. The left 576px column begins with a coral eyebrow, then a 72px uppercase display spread over three lines. Solid white words end in an equally large hollow final line. A 560px support paragraph follows, with a copy-command Outline button and Coral button below at a 16px gap. The technical scene occupies approximately the right half, with understated code, highlighted state bands and small badges rather than a large browser bezel. Behind both is the smoky grain, not a colored hero slab. A thin divider introduces a monochrome logo ticker at the bottom of the first screen. The next centered introduction and its large interface demo fall below the fold.

**Transfer:** Write a short promise whose final word deserves outlined emphasis. Replace the technical scene with a truthful working artifact or a minimal process of three states in the same visual weight. Deeper product pages can use Colored split sculpture; pricing opens with a compact centered heading and early tiers; company introductions use two text columns and an 80px uppercase title.

**Avoid:** Do not center everything above a generic floating browser mockup, fill the opening with blue by default, or turn the hollow word into a bold gradient headline.

**Text style:** `display` — Whyte 400 · 72px/0.95 · tracking -0.02em · uppercase

### Centered demonstration

**Observed:** A centered heading-lg, body support at a 24px gap, paired actions at 32px, then a large 1376px-wide product stage after 64px. The section uses 160px vertical padding and the Directional black panel.

**Transfer:** Demonstrate the core task before expanding into secondary capabilities.

### Editorial interruption and connected chapters

**Observed:** Electric editorial field carries a broad sentence-case heading-lg-loose. Below it, connected chapters use the left hairline reading rail, 11px nodes, coral eyebrow, chapter-heading, body paragraph and Technical link. Text is capped at 480px and the media is wider, with a 48px gap. Chapters use 120px spacing; media can overlap the colored boundary.

**Transfer:** Use the bright field to summarize a contrast, then unpack that contrast through linked feature chapters rather than independent card islands.

### Portrait-led proof

**Observed:** A tall monochrome portrait at left; section heading, short support, subdued customer-logo selector, quote, attribution and paired actions at right. Slim segmented progress lines and round arrow controls close the composition.

**Transfer:** Use one substantial customer story to interrupt a run of technical sections. Place broader anonymous or short endorsements in Quote cards only when attribution is available.

### Open capability grid

**Observed:** A broad left-aligned statement and short support lead into six Capability tiles in three columns. These are visually open at rest, not six raised blocks.

**Transfer:** Group distinct applications or jobs; keep descriptions short enough to scan.

### Before and after instrument

**Observed:** Short stacked heading at left beside a 912px by 456px comparison frame with 2px white edge. The left side is a gray line diagram; the right is blue with a dramatically simpler artifact. A vertical white divider and small round handle communicate the comparison.

**Transfer:** Use a real reduction in complexity: many steps versus fewer steps, or scattered tools versus a unified task. Keep the contrast understandable without dragging the handle.

### Technical proof enclosure

**Observed:** A wide Directional black panel contains a large heading, three tab-like feature summaries, a substantial dark data visualization and a plain six-item assurance grid. Small square markers, thin progress rules and mono links replace decorative badges.

**Transfer:** Combine operational proof with factual assurance where the buyer needs it; the chart must reflect real product behavior rather than arbitrary curves.

### Builder closing and particle handoff

**Observed:** The default closing uses a large sentence-case heading, a short invitation, White button and Outline button, then three open quickstart tiles with mono language labels and 32px framework titles. Particle ribbon sweeps through the lower space and hands off to Footer columns with Status badge and faint dot art.

**Transfer:** Offer concrete starting paths suited to the new product, then use the particle sculpture to make the transition into navigation feel intentional. A direct commercial or product-detail closing can instead use a 602px-tall stage with an uppercase promise, support and two actions over the ribbon.

### Commercial comparison and calculator

**Only for:** pricing pages

**Observed:** A centered pricing-display and muted support lead to a logo ticker and four Pricing plans. One tier uses Coral proof field. Later sections pair an editorial-heading with a two-column calculator: dark tracks with coral fills on the left, a black bordered recommendation summary on the right. A full comparison table uses hairline row separators and expandable category headings.

**Transfer:** Separate choosing a plan from exhaustive comparison; keep the first decision legible and defer detailed metering explanations.

### Outcome triptych

**Only for:** quantified commercial proof

**Observed:** Three touching outcome cards use large customer marks, 16px mono captions, 38px uppercase stat values and full-width White buttons. The first coral card projects slightly beyond the adjoining outlined dark pair.

**Transfer:** Use three verifiable outcomes, keeping the unit attached to the number and the brightest surface on the strongest result.

### Numbered mechanism narrative

**Only for:** use-case and product-detail pages

**Observed:** Uppercase editorial statements pair with numbered concise benefits. A later four-step navigation strip sits above an asymmetric text-and-demo stage; numbered mono labels and thin progress lines explain implementation rather than adding more selling slogans.

**Transfer:** Use a few real steps from first use to production readiness, with an artifact that changes to explain each step.

### Company editorial directory

**Only for:** company pages

**Observed:** An 80px uppercase title and short mission at left balance two candid paragraphs at right, inside 70px side gutters. The Team portrait wall follows in four columns. Later a narrow text column with a coral recruitment action sits beside practical values and benefits; a dark investor panel mixes large monochrome logos and smaller named supporters.

**Transfer:** Make the people and working principles concrete, retaining the same technical atmosphere rather than changing to bright lifestyle branding.

### Sparse objections

**Only for:** pricing and use-case objection handling

**Observed:** A large heading sits in the first third; FAQ disclosures occupy the other two thirds. Square markers and whitespace do most of the organization, with the first answer open.

**Transfer:** Answer the question directly before linking to deeper documentation.

### Resource diptych ending

**Only for:** use-case resource endings

**Observed:** Grainy resource diptych precedes four open resource tiles in a single row, each with a 32px title and compact White button. It goes directly into Footer columns rather than another large conversion block.

**Transfer:** Use this ending for a learning-heavy narrative when deeper reading is the logical next action.

### Company related-reading ending

**Only for:** company pages

**Observed:** A sentence-case related-content heading precedes two touching article panels inside a 1300px-wide frame, with 32px titles and low uppercase article links. One panel carries faint particle art. Footer columns follow without a separate sales call.

**Transfer:** End company narratives with useful editorial context, preserving the common atmospheric footer.

## Page flow

**Storyline:** Promise → working proof → capability explanation → human or quantified proof → practical evaluation → a concrete next step → atmospheric deep navigation.

### Broad product landing narrative

1. **Promise** — Outlined-emphasis headline beside a working artifact and a monochrome proof ticker.
2. **Product demonstration** — Centered introduction with a broad interface stage.
3. **Capability chapters** — Blue editorial interruption followed by connected text-and-media chapters.
4. **Social proof** — Portrait-led customer story.
5. **Breadth and simplification** — Open application grid and before/after instrument.
6. **Operational confidence** — Dark proof enclosure and factual assurance grid.
7. **Closing action** — Concrete starter paths, particle ribbon and multirow footer.

**Transfer:** Use this as the default landing-page vocabulary, adapting the order and number of chapters to the decision being made.

### Commercial evaluation and purchase confidence

1. **Promise** — Compact centered commercial headline, muted support and logo ticker.
2. **Pricing** — Four long aligned tier cards with one warm highlighted recommendation.
3. **Reassurance** — Customer quotation and concise metering explanation.
4. **Decision support** — Interactive calculator followed by a detailed category comparison.
5. **Quantified proof** — Outcome triptych with one bright coral card.
6. **Education and objections** — Illustrated implementation steps and sparse FAQ.
7. **Closing action** — Short time-to-value call over particle art, two actions and common footer.

**Transfer:** Keep recommendations, raw feature comparison and billing explanations as distinct layers.

### Explain a complex platform mechanism

1. **Promise** — Blue two-column text stage beside a charcoal particle sculpture.
2. **Problem and comparison** — Large uppercase challenge, small line diagrams and a technical comparison table.
3. **Mechanism** — Framed primitive demonstration and flow-control explanation.
4. **Product depth** — Dark observability enclosure, runtime examples and setup demonstrations.
5. **Applied proof** — Use-case carousel and attributable quote-card grid.
6. **Closing action** — Large uppercase invitation over a particle ribbon and shared footer.

**Transfer:** Move from failure mode to mechanism to implementation; let technical artifacts carry the explanation.

### Show how a platform serves a particular application

1. **Promise** — Coral staggered opening with particle sculpture.
2. **Human proof** — Large portrait-led endorsement before detailed explanation.
3. **Benefits** — Oversized statement balanced by a narrow numbered benefit column.
4. **Implementation** — Four-stage strip and wide product demo.
5. **Applications and proof** — Code-and-flow stage, quote cards and illustrated primitive grid.
6. **Objections** — Sparse questions and one open answer.
7. **Further learning** — Grainy two-tone resource banner, four documentation paths and common footer.

**Transfer:** Narrow the vocabulary to the application, but retain the underlying technical visual system.

### Humanize the organization and establish credibility

1. **Identity** — Two-column introduction with a large uppercase title and candid editorial prose.
2. **People** — Extended four-column monochrome portrait wall.
3. **Working principles** — Narrow introduction and recruitment key beside practical lists.
4. **Institutional proof** — Dark panel of investor logos and named supporters.
5. **Related reading** — Two editorial article panels.
6. **Ending** — Shared status, deep navigation and particle atmosphere without an added sales stage.

**Transfer:** Use the same materials for human stories; vary density and prose rather than inventing a separate company-page brand.

## Writing

Engineer-to-engineer confidence with a little impatience for needless complexity. Benefits are blunt, practical and conversational, then supported by mechanisms rather than inflated adjectives.

**Do not copy:** Do not reuse Inngest names, marks, product identifiers, customer logos or quotations, proprietary diagrams, pricing, performance figures, certification claims or time-saving promises. Replace all with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the builder as you and your; use we for the team in company prose. Name the product when explaining what it does, then return to the reader's work.
- **Rhythm:** Short, punchy headings contrast with concrete explanatory paragraphs. Use clipped lists, deliberate repetition and occasional rhetorical questions; action labels stay extremely short.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A forceful verb or outcome followed by a memorable final emphasis. | 4–8 words | “make every backend unbreakable.” |
| Feature chapter | Repeat a simple verbal stem; change the practical outcome. | 3–5 words | “Know what happened”<br>“Know what works” |
| Support | Describe what the mechanism does and the work it removes. | 2–4 concise sentences | “However it’s written, wherever it runs, [Brand] makes it unbreakable. Start locally, scale instantly.” |
| Technical explanation | Name the concrete primitive, then the behavior it guarantees. | 1–3 sentences | “Wrap any work as a named checkpoint. Retried on failure, cached on success.” |
| Action | Verb plus immediate destination or low-friction outcome. | 2–4 words | “Start free”<br>“View case study”<br>“Read the docs” |
| Objection | Ask the actual billing or implementation question without softening it. | 5–12 words | “What counts as one "execution"?” |
| Assurance | Plain conversational lead-in followed by facts. | Short heading plus brief factual support | “Stuff your CISO needs to see” |

**Words and phrasing to use:** wrap; run; ship; by default; existing code; no more; without; in production; one command; start locally

**Avoid:** revolutionary; unleash limitless potential; seamless synergy; magical; best-in-class; enterprise-grade as an unsupported adjective

**Rules:**

- Name the burden removed, then explain exactly what replaces it.
- Pair big claims with a product view, a concrete mechanism or attributable proof.
- Use repeated grammatical structures to link chapters.
- Keep humor occasional and specific to real working frustrations.
- Keep literal commands and API names exact; do not uppercase them merely because neighboring labels are uppercase.

## Do's and Don'ts

### Do

- Keep the default opening display regular at 72px with a hollow 1px final emphasis.
- Use 64px sentence-case headings for the default broad narrative and scope uppercase ink-trap headings to deeper page types.
- Retain 160px desktop chapter padding and compact 20px tile interiors.
- Stage major interface media at 10px corners with a faint 1px directional edge.
- Keep coral conversion keys at 42px high with 6px corners.
- Give the blue field enough width to feel architectural, then return to charcoal.
- Include a purposeful particle ribbon in the closing region and sparse dots behind the footer.
- Use monochrome human proof with regular-weight quotes and clear attribution.

### Don't

- Do not make every card a #212121 raised tile; open capability tiles have transparent resting borders.
- Do not replace instrument-key actions with pill buttons; pills belong to tags, a few scoped docs actions and circular controls.
- Do not spread operational green through headlines or decorative section fills.
- Do not add drop-shadow elevation to all black panels; thin gradient edges define their boundaries.
- Do not use the commercial #cdcdcd outline on every default capability tile.
- Do not use 700-weight display text to simulate impact; scale and outline provide the contrast.
- Do not recolor customer portraits or wire illustrations into a full rainbow.
- Do not compress the multirow footer into a tiny legal strip; its 26px headings and 48px group rhythm are part of the ending.

## Motion and responsive

### Motion

**Observed:**

- White and outline buttons declare background-color and color transitions of 0.3s cubic-bezier(0.2, 0.8, 0.2, 1), with box-shadow at 0.2s on the same curve.
- The coral key declares a 0.2s cubic-bezier(0.4, 0, 0.2, 1) color/background transition.
- Label wipe links declare background-size 0.36s cubic-bezier(0.7, 0, 0.15, 1).
- The logo marquee declares 40s linear infinite animation. Feature-tile transforms and borders declare 0.5s cubic-bezier(0.22, 0.61, 0.27, 1).
- Technical-link arrows translate 6px on hover; carousel controls and segmented progress strips indicate current content.

**Transfer:**

- Use the long continuous ticker for social proof and compact state motion in the working artifact; keep body text visually stable.
- Animate button color and outline changes with their own declared timings rather than applying one global transition.

**Unknown:**

- Particle-sculpture motion paths and exact scroll choreography are not established.
- Reduced-motion behavior of every animated scene is not established.

### Responsive

**Observed:**

- Declared heading clamps preserve the display hierarchy below desktop sizes.
- Section classes declare 80px, 96px and 160px vertical rhythms; content gutters declare 24px, 36px and 32px variants.
- Capability grids declare one column, then two, then three. Team grids declare two columns before four; commercial tier grids declare one column before four.
- Desktop feature chapters use a 5:7 grid and the connected rail is hidden below the large-screen variant.

**Transfer:**

- On narrow screens, keep the outlined punchline and put the working artifact below the promise, not behind body text.
- Let split colored openings become one readable text narrative before the particle object. Keep the footer particle layer faint as navigation reflows.
- Preserve content order and factual readability in pricing comparisons; do not shrink the desktop table's type to fit.

**Unknown:**

- Exact mobile visual compositions and breakpoint-to-layout mapping are not fully established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
