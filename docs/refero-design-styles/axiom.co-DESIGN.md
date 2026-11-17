# Axiom — ember-lit machine room

## Overview

A near-black technical marketing style with the feeling of an instrument panel emerging from darkness. White grotesk headlines, muted gray explanations and small monospace markings keep the language sober, while burnt-orange actions and fine diagonal light trails give it warmth. Detailed interface scenes and schematic illustrations carry the proof; spacious chapters surround dense, credible product detail. It suits developer tools, infrastructure and complex software that benefits from showing its workings.

### Essentials

- The promise is left-aligned, not poster-centered: a 64px/1 Geist headline at weight 500 and -0.015em tracking occupies a 768px column, followed by a 576px support line and compact paired actions.
- Darkness acts as a material, not just a theme: #090909 canvas, #0c0c0c interface wells and #0f0f0f cards remain close together; orange is confined to small actions, annotations and light filaments rather than section-sized fills.
- Actions look like console controls: 36px height, 6.1px corners, 13px/1.5 medium labels and an arrow on the burnt-orange primary; the secondary is a faintly graded dark outlined rectangle.
- Product proof emerges and disappears into the canvas: a 16px outer frame with 6px inset surrounds a 10px inner frame; right and bottom gradient masks let oversized interfaces dissolve rather than end abruptly. When no finished interface exists, construct a truthful miniature workflow with controls, structured rows and one result.
- Fine diagonal amber light is a signature device: several hairline trails rise toward the upper right, with one warm-white glint and a very restrained glow. Carry this device into the opening and closing atmosphere without competing with text.
- Proof can occupy the whole stage: a centered 36px/1.35 quotation in a 768px measure uses orange quotation marks and a 12px uppercase mono attribution separated by 32px; progressive word emphasis gives it a deliberate reading pause.
- The ending is expansive rather than boxed: a 48px/56px centered closing promise sits in 192px vertical padding, followed by the light-trail atmosphere, a small utility row and a hairline-separated multi-column directory.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt orange | `#da5c2b` | `--color-accent` | action, link, accent | Primary actions, text links, quote punctuation on interior pages and selected technical details. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Amber punctuation | `#f97316` | `--color-spark` | accent, text | Opening quote punctuation and small capability labels; never a large background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Machine black | `#090909` | `--color-canvas` | background | Continuous page canvas and dark masks. |
| Interface well | `#0c0c0c` | `--color-well` | surface | Inset interface scenes and recommended-plan interior. |
| Raised charcoal | `#0f0f0f` | `--color-card` | surface | Comparison cards and subdued logo tiles. |
| Control charcoal | `#111111` | `--color-control` | surface, border | Toolbar fills, outer illustration edges and secondary-action gradient endpoint. |
| Section edge | `#1f1f1f` | `--color-rule` | border, surface | Thin button outlines and shared-grid dividers. |
| Panel edge | `#222222` | `--color-panel-edge` | border | Inner interface outlines; also used at 50% alpha on raised cards, visibly about #181818 over the card. |
| Raised edge | `#2a2a2a` | `--color-edge-hover` | border | Hover outline on comparison cards. |
| Directory gray | `#757575` | `--color-footer-text` | text, link | Footer links; white at 44.1% over the canvas. |
| Technical gray | `#7b7b7b` | `--color-muted` | text | Captions, subordinate card copy, small technical labels. |
| Support gray | `#a4a4a4` | `--color-secondary` | text | Supporting paragraphs; white at 63% over the canvas. |
| Off-white | `#fafafa` | `--color-text` | text | Primary marketing headings and labels. |
| Action white | `#ffffff` | `--color-white` | text, action | Primary-button labels and the enterprise closing-action inversion. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#30a46c` | `--color-status` | accent | Small operational-status dot only. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing comparisons | Warm comparison well | `#22150d` | `--color-pricing-wash` | surface | Right edge of the paid-plan comparison cells. |
| product, solution and pricing openings | Soft headline white | `#c2c2c2` | `--color-display-secondary` | text | White at 75% over the canvas for the second thought in an interior hero. |

## Typography

- **Geist** — All marketing headlines, explanations, navigation and action labels. Compact contemporary grotesk; open forms, medium-weight display and low-contrast body. Font stack: "Geist", system-ui, sans-serif.
- **berkeleyMono** — Equipment-like labels, quote attribution and technical quantities. Crisp utilitarian monospace, primarily regular with small medium-weight capitals. If unavailable, use **IBM Plex Mono**. Use weights 400–500 and preserve the role-specific tracking. Font stack: "berkeleyMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Geist | 500 | 64px | 1 | -0.015em | Default landing-page promise. |
| closing | Geist | 500 | 48px | 56px | -0.025em | Centered final promise. |
| heading | Geist | 500 | 40px | 1.1 | -0.025em | Main chapter headings, usually one or two lines. |
| quote | Geist | 500 | 36px | 1.35 | -0.025em | Large centered testimonial. |
| card-heading | Geist | 500 | 16px | 1.5 | -0.025em | Feature-card titles. |
| hero-support | Geist | 400 | 15px | 1.5 | normal | Compact opening explanation. |
| body | Geist | 400 | 15px | 1.6 | normal | Chapter explanations, often two paragraphs. |
| card-body | Geist | 400 | 14px | 22px | normal | Feature-card explanations. |
| small-body | Geist | 400 | 14px | 24px | normal | Closing reassurance and expanded FAQ answers. |
| text-link | Geist | 500 | 14px | 20px | normal | Arrow-bearing chapter links. |
| button | Geist | 500 | 13px | 1.5 | normal | Primary and secondary conversion controls. |
| navigation | Geist | 450 | 13px | 1.5 | normal | Header navigation and compact header actions. |
| caption | Geist | 400 | 13px | 18px | normal | Footer links and utility descriptions. |
| proof-copy | Geist | 400 | 13px | 1.5 | normal | Comparison-card descriptions. |
| quote-attribution | berkeleyMono | 400 | 12px | 16px | 0.05em, uppercase | Single-line attribution below a quotation. |
| proof-label | berkeleyMono | 500 | 11px | 1.5 | 0.1em, uppercase | Small label above a logo wall. |
| directory-heading | berkeleyMono | 500 | 11px | 1.5 | -0.025em, uppercase | Footer directory column names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product, solution and pricing openings | interior-display | Geist | 500 | 60px | 1 | -0.025em | Two-tone hero promise. |
| pricing pages | price | Geist | 600 | 48px | 1 | -0.035em | Plan cost, with a much smaller baseline-aligned period. |
| pricing calculators | estimate-total | berkeleyMono | 400 | 36px | 40px | -0.025em | Calculator total aligned to the lower-right corner. |
| pricing pages | plan-heading | Geist | 600 | 19px | 24px | -0.025em | Plan names. |
| enterprise adoption narratives | step-heading | Geist | 600 | 17px | 1.5 | -0.025em | Numbered adoption steps. |
| evaluation sections | question | Geist | 450 | 15px | 24px | normal | Expandable evaluation questions. |
| evaluation and pricing sections | category-label | berkeleyMono | 400 | 12px | 16px | 0.1em, uppercase | Grouped FAQ categories and comparison-table categories. |

**Notes:**

- The default hero is slightly looser than the chapter scale: -0.015em versus -0.025em. Do not increase display weight to compensate for the dark background.
- Small sans copy keeps normal tracking; mono capitals alternate deliberately between wide equipment markings and tight directory labels.
- The interior hero's muted phrase is part of the same sentence, not a separate subtitle. Keep its size and weight identical to the bright phrase.

## Layout

**Density:** Airy chapters around compact instruments: marketing sections have long breathing intervals while controls, data rows and labels stay close together.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Logo-grid gutters and illustration-frame inset. |
| 8px | Card title-to-copy gaps and fine control clusters. |
| 12px | Action-pair gaps, section heading-to-description gaps. |
| 16px | Hero headline-to-support gap and horizontal container inset. |
| 20px | Raised-card padding. |
| 24px | Card-grid gutters, plan-card padding and support-to-action separation. |
| 32px | Quote-to-attribution separation and footer utility-row bottom space. |
| 40px | Chapter heading block to main content and directory top padding. |
| 48px | Opening text-to-product-stage gap and large card internal separation. |
| 80px | Horizontal text-to-demo gutter and proof-band vertical padding. |
| 96px | Standard section top and bottom padding. |
| 128px | Opening top padding and footer top padding. |
| 192px | Closing-call top and bottom padding. |

### Containers and grids

- **container**: max width 1240px · side padding 16px. Centered desktop container; at 1440px its inner content spans 1208px, giving a consistent left edge to navigation, headlines and grids.
- **opening-copy**: max width 768px. Landing headline measure; support copy is limited to 576px.
- **centered-proof**: max width 768px. Quotation stage centered within the main container.
- **closing-copy**: max width 896px. Centered final headline and support.
- **feature-grid**: 3 columns · gap 24px. Equal-width illustrated problem or benefit cards.
- **comparison-grid**: 4 columns · gap 24px. Compact comparison cards.
- **split-chapter**: 2 columns · gap 80px. Narrow text chapter on the left with an oversized product scene on the right, allowed to extend beyond the container.
- **directory**: 7 columns · gap 24px. Footer navigation columns under the utility row.
- **shared-feature-grid** (only for product detail pages): 2 columns · gap 1px. Product capability cells share borders rather than float as independent cards.
- **plan-grid** (only for pricing pages): 2 columns · gap 24px. Two plans with one subtly emphasized paid tier.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 6.1px |
|  | raised-cards | 10.6px |
|  | outer-illustration | 16px |
|  | inner-illustration | 10px |
|  | status-dot | 50% |
| evaluation sections | faq-trigger | 7.6px |
| enterprise and pricing trust sections | trust-strip-outer | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| raised-card | `0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)` | Very low-contrast grounding for comparison cards. |
| illustration-halo | `0px 0px 40px 20px rgba(0,0,0,0.05)` | Soft outer edge around large interface frames; outlines do most of the separation. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous marketing background.

**CSS:** `background: #090909; color: #fafafa`

**Observed:** No alternating light sections; depth comes from tiny differences in charcoal.

**Transfer:** Let the same black connect copy, graphics and footer.

#### Raised card · level 1

**Use:** Proof and comparison tiles.

**CSS:** `background: #0f0f0f; border: 1px solid rgba(34,34,34,0.5); border-radius: 10.6px; box-shadow: 0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)`

**Observed:** Edges barely separate the card from the page.

**Transfer:** Use for bounded proof, not every paragraph.

#### Illustration shell · level 1

**Use:** Large product demonstrations.

**CSS:** `background: #090909; border: 1px solid #111111; border-radius: 16px; padding: 6px; box-shadow: 0px 0px 40px 20px rgba(0,0,0,0.05)`

**Observed:** A second nested frame gives the illustration a machined rim.

**Transfer:** Keep the double edge even when replacing the interior with a different workflow.

#### Illustration well · level 2

**Use:** Interior of the product shell.

**CSS:** `background: #0c0c0c; border: 1px solid #222222; border-radius: 10px; overflow: hidden`

**Observed:** Toolbars and structured rows remain visible near the leading edge; trailing detail dissolves into black.

**Transfer:** Show enough working detail to establish real functionality.

#### Scene dissolve

**Use:** Bottom of large product illustrations.

**CSS:** `background: linear-gradient(to top, #090909 0%, rgba(0,0,0,0) 100%); pointer-events: none`

**Observed:** A matching right-edge mask fades horizontally; these overlays belong to the scene, never the marketing copy.

**Transfer:** Fade peripheral detail while retaining a clear focal interaction.

#### Shared border matrix

**Only for:** product and evaluation detail sections

**Use:** Capability grids.

**CSS:** `background: #1f1f1f; border: 1px solid #1f1f1f; border-radius: 8px; gap: 1px; overflow: hidden`

**Observed:** Canvas-colored cells expose a single thin divider between them.

**Transfer:** Group related capabilities in a single framed matrix rather than many bright cards.

#### Warm comparison cell

**Only for:** pricing comparisons

**Use:** Paid-plan column emphasis.

**CSS:** `background: linear-gradient(to right, #0f0f0f 0%, #22150d 100%); padding: 12px 20px`

**Observed:** The paid column is warmed subtly; adjacent cells remain charcoal. A fine warm edge encloses each category group.

**Transfer:** Use the warm tint only on the plan being compared or recommended.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; z-index: 50; background: #090909; border-bottom: 1px solid rgba(31,31,31,0.5); height: 65px`

**Text style:** `navigation` — Geist 450 · 13px/1.5

**Observed:** Small white symbol and wordmark at left, centered topic links, sign-in and compact orange action at right. Header actions are 28px high with 8px side padding; topic controls use 4px 10px padding.

**States:** Declared: hover topic background #222222 and white text; focus-visible topic background #222222.

**Transfer:** Retain the small scale and three-part alignment.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; background: #da5c2b; color: #ffffff; border: 1px solid transparent; border-radius: 6.1px; height: 36px; padding: 0px 12px`

**Text style:** `button` — Geist 500 · 13px/1.5

**Observed:** Short label followed by a mono right arrow; paired with Secondary button rather than centered alone. The enterprise closing call uses a white fill with dark text.

**States:** Declared: hover opacity 0.9; focus-visible white border; active scale 1 1.

**Transfer:** Use a concise verb-based conversion label.

### Secondary button

**Use:** Human-assisted or exploratory alternative.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; background: linear-gradient(rgba(0,0,0,0) 0%, #111111 100%); color: #fafafa; border: 1px solid #1f1f1f; border-radius: 6.1px; height: 36px; padding: 0px 12px`

**Text style:** `button` — Geist 500 · 13px/1.5

**Observed:** Same compact proportions as the primary, with a much quieter surface.

**States:** Declared: hover text remains off-white; focus-visible neutral border at 70% opacity; active scale 1 1.

### Arrow link

**Use:** Chapter-level continuation.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; color: #da5c2b; background: transparent; border: 1px solid transparent; border-radius: 6.1px; height: 32px`

**Text style:** `text-link` — Geist 500 · 14px/20px

**Observed:** A bare orange label and right arrow sit below explanatory text. Documentation-oriented variants use white.

**States:** Declared: hover underline; focus-visible white border and 10% white background; active scale 1 1.

### Product frame

**Use:** Credible product demonstration.

**CSS:** `background: #090909; border: 1px solid #111111; border-radius: 16px; padding: 6px; height: 720px`

**Observed:** Illustration well sits inside; compact toolbar, controls, code or data and a visible result establish the working sequence. The scene may overflow the container to the right.

**Transfer:** Replace the internals with the new product's strongest real interaction, not arbitrary dashboard furniture.

### Comparison card

**Use:** Short proof or alternative positioning.

**CSS:** `display: flex; flex-direction: column; gap: 48px; background: #0f0f0f; border: 1px solid rgba(34,34,34,0.5); border-radius: 10.6px; padding: 20px`

**Text style:** `proof-copy` — Geist 400 · 13px/1.5

**Observed:** Monochrome logo at top; small title and muted explanation below. Four columns for alternatives, three for customer outcomes.

**States:** Declared: hover border #2a2a2a; focus-visible neutral border at 70% opacity.

**Transfer:** Use one proof point per card; keep logos subdued and descriptions short.

### Footer directory

**Use:** Closing site map.

**CSS:** `display: grid; grid-template-columns: repeat(7, minmax(0px, 1fr)); column-gap: 24px; row-gap: 40px; border-top: 1px solid rgba(31,31,31,0.5); padding-top: 40px; background: #090909`

**Text style:** `directory-heading` — berkeleyMono 500 · 11px/1.5 · tracking -0.025em · uppercase

**Observed:** Uppercase mono heading above a vertical link list with 16px top separation and 8px list gaps. Directory links use Caption, white at 44.1%. A small operational status and social links finish the bottom row.

**Transfer:** Choose categories appropriate to the new product while retaining the dense directory scale.

### Status indicator

**Use:** Footer operational reassurance.

**CSS:** `display: flex; background: #30a46c; border-radius: 50%; width: 8px; height: 8px`

**Observed:** A small green dot precedes a muted Caption label; a translucent larger ring pings behind it.

**Transfer:** Only use a live-status treatment for a meaningful service state.

### FAQ trigger

**Only for:** evaluation sections

**Use:** Grouped evaluation questions.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; padding: 10px 0px; border: 1px solid transparent; border-radius: 7.6px; color: #a4a4a4; background: transparent; min-height: 46px`

**Text style:** `question` — Geist 450 · 15px/24px

**Observed:** Question at left and a small downward chevron at right; categories precede groups. Answers use Small-body and are hidden until expanded.

**States:** Declared: hover text #fafafa; focus-visible orange border.

### Plan card

**Only for:** pricing pages

**Use:** Plan selection.

**CSS:** `display: flex; flex-direction: column; background: #0c0c0c; border-radius: 7px; padding: 24px`

**Text style:** `plan-heading` — Geist 600 · 19px/24px · tracking -0.025em

**Observed:** Plan name, short description, prominent Price, mono billing qualifier, arrow-led benefits and full-width action. The paid plan has nested dark rims and a hairline orange gradient that becomes stronger toward the bottom; the free tier remains near the canvas.

**Transfer:** Emphasize one plan through its border and action, not a large badge.

## Imagery and graphics

### Diagonal light filaments

**Use:** Required atmospheric punctuation in the opening and closing.

**Observed:** Several extremely fine parallel amber streaks run from lower left to upper right over black. A tiny warm-white highlight creates a soft localized bloom; most of the art is barely visible. It occupies the spare right side of the hero and the center above the footer directory.

**Transfer:** Use the same restrained geometry with the new brand's warm accent. This abstract light device works even without product artwork.

**Build:** Create a clipped 720px by 670px transparent layer. Place 4–6 parallel 1px SVG paths rising at roughly 45 degrees, separated by 40–80px. Stroke with a transparent-to-rgba(218,92,43,0.25)-to-transparent gradient. Add one short rgba(255,255,255,0.5) segment and duplicate it beneath with 12px blur and low opacity. Feather all edges into the canvas; exact glow stops are not essential.

### Emergent interface scenes

**Use:** Primary visual proof throughout the page.

**Observed:** Large dark software windows show actual queries, tables, timelines, fields and terminal output. Front-facing orthographic views, small mono detail and restrained orange or blue data marks make them feel operational, not cinematic. Wide scenes dominate their chapter while the copy stays narrow; right and bottom masks remove hard edges.

**Transfer:** Use truthful interface material from the new product. Minimum acceptable version is a simplified but readable editor, timeline or table with one meaningful result and a clear focal action.

**Build:** Nest Illustration well inside Illustration shell. Build a 40px toolbar, a compact control row and structured content with thin horizontal rules. Use mostly grayscale; reserve color for one active series or syntax. Overlay Scene dissolve at the bottom and its horizontal equivalent at the trailing edge.

### Monochrome proof marks

**Use:** Logo walls and compact proof cards.

**Observed:** White customer marks centered in dark rectangular tiles; the wall uses 192px by 84px tiles with 6px gaps in four columns and two rows. Logos are much smaller than their tile and share a comparable visual weight.

**Transfer:** Normalize legitimate proof marks to a common perceived size and monochrome treatment; use text names if artwork is unavailable.

### Technical schematics

**Only for:** product architecture chapters

**Use:** Explanatory feature diagrams.

**Observed:** Gray hairline pipelines, stacked storage blocks, dotted connectors, arrows and tiny orange mono labels are drawn directly on black. Feature-cell illustrations float with dark glows and faded edges rather than sit on colorful cards.

**Transfer:** Diagram the new product's process with a small vocabulary of blocks, connectors and stages.

**Build:** Use SVG with 1px neutral strokes, dashed secondary connectors and small rectangular nodes. Arrange one main horizontal flow, then 3–4 lower detail nodes. Use short uppercase mono labels in burnt orange, keep fills canvas-colored and taper secondary lines through opacity.

### Trust medallions

**Only for:** enterprise and pricing trust sections

**Use:** Security and procurement proof.

**Observed:** Dark circular seals with fine gray rings sit above titles and short muted descriptions inside a five-cell shared strip. Badges are 64px square, deliberately less bright than the headings.

**Transfer:** Use relevant verified certifications or comparable verified trust indicators, framed as understated medallions rather than colorful awards.

**Build:** Draw concentric thin neutral SVG rings around compact text or a simple symbol. Keep the medallion within 64px, with no metallic bevel or saturated fill.

### Icons

**Observed:** Utility outlines are predominantly 16px square with 2px round strokes; standalone feature outlines use 20px and 1.5px strokes. Small filled symbols and mono arrows coexist with them. Icons inherit neutral text color rather than gain independent colored backgrounds.

**Transfer:** Choose simple rounded line icons for controls and technical features, using mono right arrows for calls to action.

## Section recipes

How recurring sections are built.

### First screen: Instrument-stage opening

**Observed:** Navigation anchors the top in a 65px strip. After 128px of breathing room, a left-aligned Display promise spans about two thirds of the content width and wraps into two lines. Hero-support follows after 16px, then paired Primary button and Secondary button after 24px. The black canvas is the back layer, diagonal light occupies the spare right side, and an oversized Product frame comes forward below the copy with roughly 56px separation. Within the first 900px, the entire promise, explanation and actions are visible plus the upper product window: toolbar, editor and the beginning of structured results. The rest of the 720px scene and social proof fall below the fold. The product frame reaches beyond the right edge and dissolves there.

**Transfer:** Keep the left promise and substantial below-copy instrument stage for an ordinary landing page. Without finished media, create a truthful miniature workflow and result. Interior product pages use Interior-display with a dimmer second phrase above a wide scene; enterprise solutions use a left-copy/right-scene split, while pricing opens with two plan panels below its promise.

**Avoid:** Do not center the hero over a generic floating browser mockup, replace the fine light with a giant orange orb, or compress the complete product scene into the first viewport.

**Text style:** `display` — Geist 500 · 64px/1 · tracking -0.015em

### Chapter heading and proof

**Observed:** A Heading starts a chapter in 96px vertical padding; support follows after 12–24px in a 576–768px measure. A second paragraph is separated by 12px, then an Arrow link. The main proof appears below after a 40–48px structural gap.

**Transfer:** State one capability or friction removed, explain the mechanism, then show a result rather than adding a second slogan.

**Text style:** `heading` — Geist 500 · 40px/1.1 · tracking -0.025em

### Split capability chapter

**Observed:** Text occupies the narrow left column with an 80px gutter before the Product frame. The right scene is approximately 720px wide and can run past the container. The text block starts slightly below the top of the illustration, with 24px top inset.

**Transfer:** Pair one claim with one visual interaction; alternate the kind of interaction rather than changing the visual theme.

### Compact proof band

**Observed:** A short testimonial occupies the left side and a muted Proof-label precedes a four-by-two logo wall on the right. The band has 80px vertical padding; logos sit on barely raised dark tiles.

**Transfer:** Use a concise credible endorsement and a normalized set of relevant proof marks.

### Reading-stage quotation

**Observed:** Quote is centered in a 768px measure, with colored punctuation and Quote-attribution below after 32px. A full-height sticky figure sits in a 1980px desktop scroll stage. Words progressively brighten from dim gray to off-white, ending with the attribution.

**Transfer:** Use a meaningful external endorsement or a short verified statement that rewards the pause. Preserve the typographic stage even when the source product's exact testimonial format is unavailable.

**Text style:** `quote` — Geist 500 · 36px/1.35 · tracking -0.025em

### Expansive closing and directory

**Observed:** Closing is centered within 896px, followed by Small-body after 16px and paired actions after 24px. The call has 192px top and bottom padding. Diagonal light then bridges into a footer with a left symbol and short descriptor, right-aligned compact assistant-query icon controls, Footer directory, then operational status and social marks. Footer padding is 128px above and 56px below; the directory begins under a faint horizontal rule.

**Transfer:** Restate the product's practical promise and remove a final adoption barrier. Carry the atmosphere into a useful site directory; assistant-query links can become equivalent compact utility links when appropriate.

**Text style:** `closing` — Geist 500 · 48px/56px · tracking -0.025em

### Shared capability matrix

**Only for:** product detail pages

**Observed:** Shared border matrix holds two columns of large illustration-led cells. The graphic sits above Card-heading, Card-body and a white Arrow link. Cells share a 1px divider instead of separate gutters.

**Transfer:** Use a coherent set of capabilities, each with a distinct small diagram or product fragment.

### Numbered adoption path

**Only for:** enterprise adoption narratives

**Observed:** A narrow vertical narrative uses four 28px circular number markers joined by thin dark lines. Each marker pairs with Step-heading and a muted explanation; the heading block and each step are separated generously.

**Transfer:** Translate adoption, migration or setup into small independently credible steps; the count can follow the new story.

**Text style:** `step-heading` — Geist 600 · 17px/1.5 · tracking -0.025em

### Trust strip

**Only for:** enterprise and pricing trust sections

**Observed:** Five 240px cells share 1px dividers inside a 20px rounded strip, with a 24px outer rim and 4px inset. Each contains a Trust medallion, title and short description with 24px padding. A qualification note and right-aligned Arrow link sit below.

**Transfer:** Collect verified trust criteria into a low-noise strip rather than a wall of bright badges.

### Calculator and rate comparison

**Only for:** pricing pages

**Observed:** A full-width double-rimmed calculator splits controls on the left from a charcoal breakdown on the right; an Estimate-total anchors the lower right. Dense tick-mark rulers and small orange controls make it feel like an instrument. A later comparison table groups rows under Category-label, with a warm paid-plan column and compact repeated plan actions above.

**Transfer:** Expose assumptions and a computed outcome; build the table around comparable units and keep the recommendation treatment subtle.

### Grouped questions

**Only for:** evaluation sections

**Observed:** Heading occupies the left column, Category-label and FAQ trigger groups the right, separated by an 80px gutter. Questions stay unboxed on the canvas, with 40px category top space and small chevrons.

**Transfer:** Group objections by decision stage rather than flattening them into a card grid.

**Text style:** `heading` — Geist 500 · 40px/1.1 · tracking -0.025em

## Page flow

**Storyline:** promise → visible workings → credible proof → capability and adoption chapters → evaluation support → spacious closing promise → useful directory

### Broad product landing page

1. **promise** — Left-aligned headline, short explanation, paired actions and oversized instrument scene.
2. **social proof** — Concise endorsement beside a monochrome logo wall.
3. **problem framing** — Short chapter heading and three illustrated friction cards.
4. **capability chapters** — Full-width demonstrations and split text/product scenes, interrupted by a centered reading-stage quotation.
5. **evaluation support** — Hands-on product invitation and compact alternative-comparison cards.
6. **closing call** — Centered practical promise and paired actions, then atmospheric directory.

**Transfer:** Choose a few mechanisms worth demonstrating and vary the proof format without changing the dark material system.

### Audience-specific use-case evaluation

1. **promise** — Two-tone headline above a wide workflow demonstration.
2. **problem framing** — A narrow argument beside a compact taxonomy of existing approaches.
3. **capability chapters** — Shared-border benefit columns and a small case-study matrix.
4. **social proof** — Large centered quotation followed by audience-specific outcome cards.
5. **evaluation support** — Dense capability directory, alternative comparisons and grouped questions.
6. **closing call** — Audience-specific closing promise, paired actions and shared footer.

**Transfer:** Connect the audience's workflow seams to visible capabilities; distinguish scope honestly.

### Enterprise buying and adoption

1. **promise** — Split opening with a two-tone promise beside settings and purchasing controls.
2. **trust** — Customer proof, five-cell trust strip and two-by-two commercial-benefit cards.
3. **adoption path** — Linked capability rows followed by a numbered migration narrative.
4. **commercial proof** — Pricing explanation beside a terminal-style calculation scene.
5. **objection handling** — Grouped enterprise questions.
6. **closing call** — Centered promise with white primary action, then shared atmospheric footer.

**Transfer:** Treat rollout and verification as product features, with proof for each buying concern.

### Detailed product capability page

1. **promise** — Two-tone technical headline over a wide working interface.
2. **social proof** — Three concise outcome cards.
3. **mechanism** — Selectable explanatory text beside a pipeline schematic.
4. **capability chapters** — Two-column shared-border matrix of illustrated capabilities.
5. **social proof** — Centered reading-stage quotation.
6. **objection handling** — Grouped technical questions.
7. **closing call** — Large practical promise, paired actions and shared footer.

**Transfer:** Explain how the mechanism works before enumerating operators or features.

### Self-serve pricing evaluation

1. **pricing promise** — Two-tone hero and two plan cards, with restrained warm emphasis on the paid plan.
2. **cost modeling** — Instrument-like calculator with inputs and itemized result.
3. **trust** — Add-on matrix and verified trust strip.
4. **comparison** — Categorized detailed plan table with warm column emphasis, then alternative cards.
5. **machine-readable support** — Rate-card explanation beside a terminal calculation scene.
6. **objection handling** — Grouped billing questions.
7. **closing call** — Practical start-and-scale promise and shared atmospheric footer.

**Transfer:** Make the commercial model inspectable through plans, assumptions, rates and objections, without turning the page into a sales funnel.

## Writing

Direct, technically literate and commercially candid. Confidence comes from explaining the mechanism and naming practical constraints, with occasional dry friction-removal phrasing rather than exuberance.

**Do not copy:** Do not reuse Axiom names, logos, customer marks, proprietary product terminology, testimonials, competitor comparisons, prices, performance statistics or commercial promises as claims for another product. Source examples illustrate sentence construction only.

- **Addressing the reader:** Address the reader as you or your team; name the product when explaining concrete behavior. Imperatives invite an action rather than demand attention.
- **Rhythm:** Short, often parallel headline fragments alternate with information-dense explanatory paragraphs. Lists of concrete mechanisms carry the detail; short negative sentences remove perceived friction.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name a practical product category or promise, sometimes followed by a contrasting second thought. | 5–14 words | “The modern machine data platform.”<br>“Pricing that scales with you, not against you.” |
| Chapter heading | One confident outcome or two short parallel fragments. | 3–9 words | “Modern backend. Classic UX.”<br>“No rip-and-replace. No renegotiation.” |
| Supporting explanation | Explain concrete behavior, then the operational burden it removes. | 1–3 sentences | “Pay only for what you use. Automatic volume discounts in-console. Permanent free tier. Self-serve enterprise add-ons. Per-unit rates drop at higher tiers, so total cost grows sub-linearly with usage.” |
| Primary action | Short verb and low-friction object. | 2–4 words | “Start free”<br>“Open Playground” |
| Closing reassurance | Remove a specific barrier in plain language. | 2 short sentences | “Sign up in 30 seconds. No credit card.” |
| Evaluation question | Ask the practical compatibility or adoption question a technical buyer would ask. | 6–15 words | “What happens to our existing observability environment during the migration?” |

**Words and phrasing to use:** fully managed; queryable; on your timeline; no account required; same primitives; usage-based; self-serve; without; every; keep; predict

**Avoid:** revolutionary; magical; game-changing; unleash; supercharge; limitless; seamless as an unsupported claim

**Rules:**

- Lead with an outcome; use the support paragraph to explain the mechanism.
- Name boundaries and integration scope explicitly instead of implying replacement of every adjacent tool.
- Use parallel short negatives sparingly to remove real buying friction.
- Keep metrics tied to a unit, workload or verifiable context.
- CTA language should describe what happens next, not an abstract aspiration.

## Do's and Don'ts

### Do

- Keep the ordinary landing hero at 64px/1 and weight 500.
- Use the 1240px container with 16px inset as the common alignment anchor.
- Keep paragraph copy at 15px/24px and the opening explanation at 15px/22.5px.
- Give standard chapters 96px vertical padding and the closing call 192px.
- Use 36px conversion controls and the 28px compact header variant.
- Preserve the nested 16px and 10px illustration frames with 6px inset.
- Keep the quotation at 36px/1.35 within a 768px measure.
- Separate shared capability cells with 1px dividers rather than broad gutters.

### Don't

- Do not turn the #da5c2b action color into full-width orange section backgrounds.
- Do not replace 6.1px action corners with pills.
- Do not make marketing body text monospaced; reserve mono for labels, attribution and technical detail.
- Do not turn faint charcoal borders into bright white outlines.
- Do not apply gradient color to the main headline; the interior variant uses a solid muted second phrase.
- Do not use heavy 700-weight display typography or wide positive headline tracking.
- Do not lift every feature onto a glowing raised card; many cells remain flush with the canvas.
- Do not enlarge utility icons into decorative illustrations or give them saturated circular backplates.

## Motion and responsive

### Motion

**Observed:**

- Primary controls declare all-property transitions of 0.15s cubic-bezier(.4, 0, .2, 1); secondary controls and comparison-card color transitions use 0.2s with the same curve.
- Quotation words declare opacity transitions of 0.5s cubic-bezier(0, 0, .2, 1), brightening progressively through the sticky reading stage.
- The operational-status halo declares ping 1s cubic-bezier(0, 0, .2, 1) infinite.

**Transfer:**

- Keep action feedback compact and surface-based rather than adding button travel.
- Use progressive word emphasis for the typographic proof stage and let peripheral interface detail remain subdued.

**Unknown:**

- Exact scroll-to-word mapping and the light-filament animation timing are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 620px, 640px, 768px, 1024px, 1280px, 1440px and 1536px.
- Default landing headline classes specify 40px/40px below the medium breakpoint and 64px/64px above it; standard chapters use 56px vertical padding before the small-breakpoint 96px variant.
- The central desktop navigation is hidden below the large breakpoint. Logo walls declare two columns on narrow layouts and four above the small breakpoint; comparison cards move from one to two to four columns.
- Footer directory declares two columns at its narrowest layout. The opening light canvas is hidden below the large breakpoint.

**Transfer:**

- On narrow screens preserve the left-aligned promise and compact actions, then stack copy above the product scene. Keep a legible focal slice of the instrument instead of shrinking all its data to fit.
- Use the closing light atmosphere as a lightweight static graphic where the wide opening art is suppressed; keep the directory useful in two columns.

**Unknown:**

- Mobile menu behavior, exact narrow-screen scene masking and complete mobile compositions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
