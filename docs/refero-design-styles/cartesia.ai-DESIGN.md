# Cartesia — clouded instruments on paper

## Overview

An airy, light technical style that feels like a research instrument with an editorial voice. Warm white and stone surfaces, charcoal serif headlines and restrained green controls frame cloud-like interactive objects, fine line illustrations and explanatory diagrams. It suits developer platforms and complex products that need both an approachable invitation and substantial operational detail.

### Essentials

- Editorial claims arrive in two tones rather than oversized shouting: PP Kyoto 40px/1.15 at weight 500, -0.01em tracking, with a muted first thought and dark conclusion; section leads reduce to 26px/1.3.
- The opening is a small instrument on an expansive sheet: a centered two-line headline, 520px support measure, paired 36px actions and a row of clouded circular objects with one dominant 245px stage.
- The page is held inside a ruled chassis: 1280px maximum width, 1px warm stone side rails, 48px inner gutters and adjoining cells separated by 1px rules. Narrow 14px tick-mark bands punctuate chapter changes.
- Green is functional and atmospheric, not a page theme: #309d4b marks primary actions and status; almost all structural area stays #fefefe, #f9f9f8 or #f3f2ef. Clouded objects and pale green illustration details supply the larger color moments.
- Controls are compact rounded rectangles, not generic pills: primary and secondary actions are 36px high with 8px corners, 16px horizontal padding and 14px/20px medium sans text. Reserve the pill silhouette for the floating conversation instrument.
- Technical ideas become tangible through fine outlined scenes and node diagrams on stone backing, balanced by a clouded circular instrument. Carry both devices to new content; if no live interaction exists, use a static clouded disc with a relevant symbol and an original explanatory diagram.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Living green | `#309d4b` | `--color-primary` | action, accent | Primary actions, operational dots, checks and green atmospheric media. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#1e1c1a` | `--color-ink` | text, border | Primary headlines, labels and body emphasis. |
| Graphite | `#525150` | `--color-muted` | text, link | Supporting paragraphs, secondary labels and icons. |
| Soft headline ink | `#61605e` | `--color-soft-ink` | text | Visible result of charcoal at 70% over paper; the first clause of paired headings. |
| Stone edge | `#e4e3db` | `--color-rule` | border, surface | Side rails, cell edges, table divisions and low-contrast ticks. |
| Warm stone | `#f3f2ef` | `--color-media` | surface, background | Diagram and animation backing; secondary-action hover fill. |
| Chalk | `#f9f9f8` | `--color-card` | surface, text | Subtle chapter bands and floating instrument; reversed button text. |
| Paper white | `#fefefe` | `--color-canvas` | background, surface | Default page and cell background. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and product demonstrations | Faded graphite | `#a7a6a2` | `--color-faint` | text | Subordinate tier names and technical secondary labels. |

## Typography

- **ABC Diatype-75f05108b2d5df75** — Body, navigation, controls and card headings. Matter-of-fact grotesk with open forms, compact medium labels and a softer regular text texture. If unavailable, use **Inter**. Use 400–500 and retain the compact measured sizes. Font stack: "ABC Diatype-75f05108b2d5df75", "Inter", Arial, ui-sans-serif, system-ui, sans-serif.
- **PP Kyoto-b14c6ebb315b725b** — Editorial headlines, section leads and prominent numerals. Moderately contrasted serif with broad readable forms; literary rather than ornamental. If unavailable, use **Libre Caslon Text**. Use regular or medium styling; preserve line breaks and tune measure rather than enlarging. Font stack: "PP Kyoto-b14c6ebb315b725b", "Libre Caslon Text", Georgia, "Times New Roman", serif.
- **IBM Plex Mono-1f31a4fbe8ce28fa** (only for pricing and product demonstrations) — Tier names, breadcrumbs and short configuration identifiers. Small technical monospace, used sparingly rather than as a global eyebrow system. Font stack: "IBM Plex Mono-1f31a4fbe8ce28fa", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | PP Kyoto-b14c6ebb315b725b | 500 | 40px | 1.15 | -0.01em | Default centered opening statement in two tonal clauses. |
| heading | PP Kyoto-b14c6ebb315b725b | 500 | 26px | 1.3 | normal | Section leads, split thought headings and closing invitation. |
| card-heading | ABC Diatype-75f05108b2d5df75 | 465 | 20px | 1.3 | normal | Feature titles and conversion-cell titles. |
| body-lead | ABC Diatype-75f05108b2d5df75 | 400 | 18px | 1.3 | normal | Closing action support and secondary opening descriptions. |
| footer-heading | ABC Diatype-75f05108b2d5df75 | 465 | 17px | 24px | normal | Directory group headings. |
| body | ABC Diatype-75f05108b2d5df75 | 400 | 16px | 1.5 | normal | Default support and opening paragraph. |
| caption | ABC Diatype-75f05108b2d5df75 | 400 | 15px | 24px | normal | Brand description and supporting footer text. |
| action | ABC Diatype-75f05108b2d5df75 | 500 | 14px | 20px | normal | Navigation and compact primary or secondary controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product, use-case and pricing pages | display-detail | PP Kyoto-b14c6ebb315b725b | 500 | 40px | 1.15 | normal | Detail-page openings, centered or split with an interactive object. |
| pricing pages | price | PP Kyoto-b14c6ebb315b725b | 500 | 36px | 1.3 | normal | Main tier prices. |
| instructional sections | step-number | PP Kyoto-b14c6ebb315b725b | 400 | 20px | 1.4 | normal | Two-digit process index beside a sans heading. |
| testimonial sections | quote | ABC Diatype-75f05108b2d5df75 | 400 | 18px | 1.375 | normal | Customer quotations in ruled cells. |
| product and use-case pages | body-detail | ABC Diatype-75f05108b2d5df75 | 400 | 16px | 26px | normal | Longer explanatory feature paragraphs. |
| FAQ sections | question | ABC Diatype-75f05108b2d5df75 | 500 | 14px | 1.625 | normal | Accordion questions. |
| FAQ and pricing sections | answer | ABC Diatype-75f05108b2d5df75 | 400 | 14px | 1.625 | normal | Accordion answers and dense explanations. |
| pricing pages | tier-label | IBM Plex Mono-1f31a4fbe8ce28fa | 500 | 12px | 1.375 | normal | Small understated tier names. |

**Notes:**

- Do not inflate the editorial hierarchy into a 72px hero: 40px is the opening scale, 26px the recurring section scale, 20px the sans cell title.
- Only the default opening tightens tracking to -0.01em; the other serif headings keep normal spacing.
- Use contrast within the same headline recipe: charcoal at 70% for setup and full charcoal for the conclusion. The tonal distinction is not a gradient.
- Medium card headings render at weight 465; control labels use 500.

## Layout

**Density:** Airy at chapter level, compact within controls and dense directories; the ruled framework keeps large white areas structured.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small icon groups and footer list gaps. |
| 12px | Heading-to-support separation and paired action gap. |
| 16px | Cell text stacks and label groups. |
| 24px | Media-to-caption spacing and small card gutters. |
| 32px | Opening support-to-action spacing and larger content groups. |
| 40px | Feature media column gap, card vertical padding and closing cell action separation. |
| 48px | Desktop inner gutter and conversion-cell padding. |
| 56px | Standard chapter top and bottom padding. |

### Containers and grids

- **Ruled chassis**: max width 1280px · side padding 48px. Centered outer frame with warm 1px vertical rails. At 1440px, the frame leaves 80px outside each side; inner content spans about 1182px.
- **Opening support**: max width 520px. Centered support text beneath the default opening statement.
- **Section introduction**: max width 576px. Left-aligned heading and explanatory paragraph, with a compact action at the far right.
- **Adjacent halves**: 2 columns · gap 1px. Process cells, comparisons and closing conversion choices; the gap reads as an edge, not empty space.
- **Capability cells**: 3 columns · gap 1px. Short resources, sample libraries and quotation grids.
- **Media pair**: 2 columns · gap 40px · side padding 48px. Two 571px media stages above labels and brief support.
- **Directory**: 5 columns · gap 1px. One wider identity column and four navigation columns. The first navigation column can stack two heading groups.
- **Tier row** (only for pricing pages): 5 columns · gap 1px. Equal width, full-height adjoining plan cells.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Primary and secondary controls | 8px |
|  | Navigation and utility controls | 4px |
|  | Structural cells | 0px |
|  | Floating conversation instrument | 9999px (pill) |
|  | Clouded objects | 50% |
| interactive product demonstrations | Demo enclosure | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Cell edge | `0 0 0 1px #e4e3db` | Structural cells; an outline rather than elevation. |
| Floating instrument | `0 0 0 1px #e4e3db, 0 10px 15px -3px rgba(0,0,0,0.1), 0 4px 6px -4px rgba(0,0,0,0.1)` | Conversation launcher, the principal raised element. |

### Surfaces

#### Paper chassis · level 0

**Use:** Default page framework.

**CSS:** `background: #fefefe; border-left: 1px solid #e4e3db; border-right: 1px solid #e4e3db; max-width: 1280px; margin: 0 auto`

**Observed:** Continuous side rails connect sections, navigation and footer.

**Transfer:** Make the page feel like one ruled document rather than isolated floating sections.

#### Ruled cell · level 1

**Use:** Adjacent features, conversion choices and directories.

**CSS:** `background: #fefefe; box-shadow: 0 0 0 1px #e4e3db; border-radius: 0px`

**Observed:** Cells meet along shared edges, usually on a 1px-gap grid.

**Transfer:** Use hierarchy through padding and typography, not raised cards.

#### Chalk band · level 0

**Use:** Research notes and quieter chapter emphasis.

**CSS:** `background: #f9f9f8`

**Observed:** A light neutral shift within the same ruled frame.

**Transfer:** Reserve for a compact conceptual or editorial interlude.

#### Stone media stage · level 0

**Use:** Explanatory diagrams and model animations.

**CSS:** `background: #f3f2ef; border-radius: 0px`

**Observed:** Wide, low rectangles with pale green and charcoal technical drawings.

**Transfer:** Keep the backing almost monochrome so small green connections remain legible.

#### Tick divider

**Use:** Chapter boundaries.

**CSS:** `height: 14px; opacity: 0.3; background-image: repeating-linear-gradient(to right, #e4e3db 0px, #e4e3db 1px, transparent 1px, transparent 8px); border-top: 1px solid #e4e3db; border-bottom: 1px solid #e4e3db`

**Observed:** Fine short vertical hatch marks sit between very faint horizontal rules.

**Transfer:** Use the instrument-like marking between selected chapters, not a bold striped banner.

#### Demo enclosure · level 1

**Only for:** interactive product demonstrations

**Use:** Contain a real input/result interaction.

**CSS:** `background: #f9f9f8; border: 1px solid #e4e3db; border-radius: 8px; padding: 24px`

**Observed:** A 1056px-wide shell contains two white subpanels; controls and consent detail sit in the input half, a clouded object marks the result.

**Transfer:** Use the product's simplest reversible input/result action.

## Components

### Sticky navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; height: 64px; z-index: 40; background: #fefefe; border-bottom: 1px solid #e4e3db`

**Text style:** `action` — ABC Diatype-75f05108b2d5df75 500 · 14px/20px

**Observed:** Brand at left, a compact link row with small dropdown chevrons, account link and paired sales/primary actions on the right. Navigation triggers have 4px corners and 6px 8px padding.

**States:** Declared: hover navigation triggers use #f3f2ef; focus-visible border-color lab(66.128% -.0000298023 .0000119209).

### Primary button

**Use:** One visually dominant conversion action in each action group.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 16px; gap: 6px; background: #309d4b; color: #f9f9f8; border: 1px solid transparent; border-radius: 8px`

**Text style:** `action` — ABC Diatype-75f05108b2d5df75 500 · 14px/20px

**Observed:** A compact text-only rectangle, paired with a paper secondary control. Pricing reserves the green treatment for one tier.

**States:** Declared: hover background-color color-mix(in oklab, #309d4b 90%, transparent); focus-visible border-color lab(66.128% -.0000298023 .0000119209).

### Secondary button

**Use:** Sales, documentation and comparison actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 16px; gap: 6px; background: #fefefe; color: #1e1c1a; border: 1px solid #e4e3db; border-radius: 8px`

**Text style:** `action` — ABC Diatype-75f05108b2d5df75 500 · 14px/20px

**Observed:** Same dimensions and text hierarchy as the primary; understated outlined treatment.

**States:** Declared: hover background-color #f3f2ef and color #1e1c1a; focus-visible border-color lab(66.128% -.0000298023 .0000119209).

### Conversion cell

**Use:** Closing routes for assisted and self-service adoption.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 40px; padding: 48px; background: #fefefe; box-shadow: 0 0 0 1px #e4e3db`

**Text style:** `card-heading` — ABC Diatype-75f05108b2d5df75 465 · 20px/1.3

**Observed:** Title and support form a close stack; a separate button follows. Two equal cells place expert help beside immediate building.

**Transfer:** Preserve the two distinct reader intents, not two synonyms for the same action.

### Footer column

**Use:** Dense but orderly destination directory.

**CSS:** `display: flex; flex-direction: column; gap: 32px; padding: 40px 48px; background: #fefefe; box-shadow: 0 0 0 1px #e4e3db`

**Text style:** `footer-heading` — ABC Diatype-75f05108b2d5df75 465 · 17px/24px

**Observed:** Group heading above an 8px-gap list of 15px/20px muted links. Identity column includes a short mission, social icons, an 'Ask AI' icon group and language selector.

**Transfer:** Group actual product, capability, solution and resource destinations into the same ruled directory.

### Conversation launcher

**Use:** Persistent invitation to experience the product.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 4px; background: #f9f9f8; color: #1e1c1a; border-radius: 9999px; box-shadow: 0 0 0 1px #e4e3db, 0 10px 15px -3px rgba(0,0,0,0.1), 0 4px 6px -4px rgba(0,0,0,0.1)`

**Observed:** A roughly 203px by 60px floating pill at the bottom right, 16px from viewport edges; small green clouded disc precedes an 18px medium label.

**States:** Declared: hover button opacity 0.8.

**Transfer:** Use an honest product-experience or help action. Retain the circular material thumbnail as its identifying device.

### FAQ row

**Only for:** FAQ sections

**Use:** Answer practical objections without a wall of expanded copy.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 16px; padding: 24px 48px; color: #1e1c1a; border-bottom: 1px solid #e4e3db`

**Text style:** `question` — ABC Diatype-75f05108b2d5df75 500 · 14px/1.625

**Observed:** Question at left, small downward chevron at right; rows are about 72px tall when closed. Answers align to the same inner text edge.

**States:** Declared: focus-visible outline 2px solid lab(66.128% -.0000298023 .0000119209), offset -2px.

### Plan cell

**Only for:** pricing pages

**Use:** Side-by-side tier selection.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 40px 24px; background: #fefefe; box-shadow: 0 0 0 1px #e4e3db`

**Text style:** `price` — PP Kyoto-b14c6ebb315b725b 500 · 36px/1.3

**Observed:** Small muted mono tier label, serif price with smaller suffix, full-width action, allowance details and ruled benefit list with green checks. The cells are adjoining rather than individual rounded cards.

### Process cell

**Only for:** instructional sections

**Use:** Explain a finite setup workflow.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px; padding: 40px 48px; background: #fefefe; box-shadow: 0 0 0 1px #e4e3db`

**Text style:** `card-heading` — ABC Diatype-75f05108b2d5df75 465 · 20px/1.3

**Observed:** A centered 256px by 144px illustration stage sits above a two-digit serif index and sans title on one baseline, then a paragraph. Cells form a two-column ruled grid.

## Imagery and graphics

### Clouded circular instrument

**Use:** Signature opening object and smaller conversation-launcher thumbnail.

**Observed:** Translucent, softly mottled green discs float directly on white without a rectangular image boundary. The default opening uses five circles with a dominant central object, smaller neighbors and faded outer objects. A pale circular microphone control overlays the center; a short name and tiny mood caption sit below. A blue version accompanies a split use-case opening.

**Transfer:** Retain this material as an abstract product presence even without audio: a central disc with a meaningful simple symbol and an honest caption. Use green as the default, not a rainbow carousel.

**Build:** Clip a square to a circle. Layer #309d4b at 45–70% alpha with several irregular pale rgba(254,254,254,0.3) radial clouds, softly blurred by 12–24px; add low-contrast SVG turbulence masked to the disc. Keep the edge softly luminous rather than adding a dark sphere shadow. Stage a 245px dominant object with 135px neighbors and smaller faded edge discs; place a 48px translucent paper control in the center. Exact cloud stops are not essential.

### Fine line scenes

**Use:** Concept explanation and workflow chapters.

**Observed:** Charcoal hairline drawings depict objects and human-scale systems. A large architectural cutaway occupies the right side of a chalk panel; smaller instructional symbols sit centered above text. Pale green fills emphasize only a few parts. No photographic textures or heavy dimensional shadows.

**Transfer:** Draw the new product's working environment or process as clean outline geometry. Minimum version: one legible object-and-action diagram per concept, with white and pale green fills.

**Build:** Use SVG paths with approximately 1px charcoal strokes, simple rounded rectangles, open contours and sparse rgba(48,157,75,0.12) fills. Build detailed scenes from repeated room or object modules; keep the surrounding field empty. For process cells, fit the artwork inside 256px by 144px and avoid enlarging a utility icon to fill the whole cell.

### Signal and node diagrams

**Use:** Signature technical proof media.

**Observed:** Stone-backed wide diagrams connect pale rectangular nodes with thin straight or gently curved lines and tiny square ports. Green waveform-like strands enter from the sides; one central node receives a pale green emphasis. Labels combine serif node names with sans descriptors. Paired motion panels also show green text fragments bending along signal paths.

**Transfer:** Represent the new system as input, transformation and output, with a few secondary modules. The minimum is a static SVG diagram with the same thin edges, pale backing and one green focus.

**Build:** On #f3f2ef, place three 8px-radius paper nodes along the horizontal middle, connect them with 1px muted lines and 4px square terminals, then branch to smaller nodes beneath the center. Give the center a rgba(48,157,75,0.08) fill and green edge. Draw multiple thin green cubic Bézier strands fanning in at the far ends; mix solid and dashed strokes. Maintain a wide, low proportion near 1182px by 317px.

### Exploded technical tiles

**Use:** Explain infrastructure or layered architecture.

**Observed:** An isometric stack floats on white beside text and an accordion. The active top tile is pale green with a saturated simple symbol; lower circuit-like tiles are almost white with faint grey edges. Separation between layers supplies depth without dramatic lighting.

**Transfer:** Use three layers of the new product's architecture; identify the active layer through green rather than realism.

**Build:** Draw three rounded diamond planes in SVG, spaced vertically by about 50px. Use 1px stone outlines for inactive layers, pale green active fill, a green lower edge and one centered solid symbol. Add very faint line details to the inactive planes.

### Icons

**Observed:** Most control icons are 12–16px outlines at 2px stroke with round caps; content symbols are often 20–24px solids. Charcoal and muted grey dominate, with green checks or play accents. Icons accompany labels rather than replacing the hierarchy.

**Transfer:** Choose simple outline chevrons, arrows and media controls; use compact solid symbols for categories. Keep detailed illustrations separate from this utility icon vocabulary.

## Section recipes

How recurring sections are built.

### First screen: Cloud instrument opening

**Observed:** A 64px sticky navigation tops a paper field bounded by side rails. The centered opening chapter is 717px tall, with 56px top padding. A two-line 40px serif statement spans about two thirds of the viewport: muted setup above a dark conclusion. Beneath it, a 520px-wide two-line support paragraph is followed by Primary button and Secondary button, 12px apart and 32px below support. The lower half stages five clouded discs around a 245px central instrument, with left/right chevrons and a centered short label plus tiny mood caption. Layers run paper, clouded objects, translucent central control, text and actions. Within the first 900px the entire opening, its object and caption are visible, plus the heading and tabs of the next chapter; the detailed next-chapter illustration continues below.

**Transfer:** Use the same balanced sentence pair and one tangible abstract instrument for a different product. A static clouded object is sufficient if no real demo exists. Product detail openings can keep centered text and paired actions but replace the carousel with a two-panel input/result enclosure. Use-case openings can split left text and right 320px object; pricing opens with a left editorial title and right short support line.

**Avoid:** Do not replace the compact serif statement with a giant grotesk slogan or use a full-bleed gradient background; do not turn the object row into a large dashboard screenshot.

**Text style:** `display` — PP Kyoto-b14c6ebb315b725b 500 · 40px/1.15 · tracking -0.01em

### Heading and support rail

**Observed:** Section heading in 26px serif, often with muted setup and dark concluding phrase. A 12px gap leads to support, usually no wider than 576px; a small Secondary button can align at the right. Common wrapper padding is 56px vertically and 48px horizontally.

**Transfer:** Lead with one concrete capability or reader outcome, then explain it once. An all-dark heading is appropriate when the sentence does not need tonal splitting.

**Text style:** `heading` — PP Kyoto-b14c6ebb315b725b 500 · 26px/1.3

### Tabbed scene

**Observed:** Heading on the left and a compact three-option segmented control on the right. Below, a chalk-backed panel places a short title and paragraph in the left third and a large fine-line cutaway scene on the right. Selected tab uses paper fill with an 8px corner; unselected labels sit directly on a stone track.

**Transfer:** Show contexts or applications without multiplying prose-heavy cards; change a scene and its short explanation together.

### Rank and customer matrix

**Observed:** A narrow chalk proof cell pairs a 26px serif rank with a short source description; adjacent customer marks occupy a four-by-two matrix of white 1px-ruled cells. An understated line above invites the reader to join the teams already using the product.

**Transfer:** Use a sourced benchmark, measured result or compact credential beside a logo or outcome matrix. Keep marks visually subdued rather than introducing a colorful sponsor wall.

### Paired technical stages

**Observed:** Heading and support rail leads to two Stone media stages, each 571px by 300px at desktop with a 40px column gap. Below are compact product/category labels and short descriptions. A ruled boundary can lead into a full-width Signal and node diagram.

**Transfer:** Use one stage per complementary capability, then explain how they work together. Replace unavailable animation with a finished static diagram.

### Editorial interlude

**Observed:** A compact Chalk band uses a two-part 26px serif thought on the left and a short rationale, outlined action and small decorative illustration on the right; the entire band is about 304px tall.

**Transfer:** Explain the foundational approach or research principle in a brief editorial pause rather than inserting another feature grid.

### Layered architecture explanation

**Observed:** Exploded technical tiles fill the left half, while a two-line serif lead and short paragraph introduce a three-row accordion on the right. The active row shows an icon, label, explanation and upward chevron; inactive rows retain only icon, label and downward chevron.

**Transfer:** Use this to expose layers, environments or modes while maintaining one primary illustration.

### Instructional grid

**Observed:** A Heading and support rail can place guide actions at right. Below, Process cells form a two-by-two grid with centered pale-green line illustrations and numbered headings.

**Transfer:** Describe preparation, input, action and validation using the new product's actual workflow.

**Text style:** `card-heading` — ABC Diatype-75f05108b2d5df75 465 · 20px/1.3

### Practical detail and related tools

**Observed:** A restrained two-column policy explanation puts a serif title left and short factual paragraphs plus underlined links right. Related tools then use three ruled cells with a small icon, 20px sans title, paragraph and text arrow action.

**Transfer:** Keep constraints near the workflow that needs them, and offer adjacent capabilities without turning them into another hero.

### Enterprise proof

**Observed:** Six quotation cells form a three-by-two ruled grid. Quotes use 18px sans text, with subdued customer mark and smaller author details below. A separate security strip pairs a two-line serif thought with three evenly spaced pale certification symbols and captions.

**Transfer:** Use authentic quotations and applicable credentials. Keep the proof typography modest; do not enlarge every number into a stat poster.

**Text style:** `quote` — ABC Diatype-75f05108b2d5df75 400 · 18px/1.375

### Split FAQ

**Observed:** A serif title occupies the left third, separated by a vertical rule from a two-thirds-width stack of FAQ rows. The heading area begins 56px down; question rows are about 72px tall and answers align under the question text. The visual resting state is closed rows.

**Transfer:** Use task-specific objections. Match the row geometry regardless of the number of questions.

**Text style:** `question` — ABC Diatype-75f05108b2d5df75 500 · 14px/1.625

### Pricing decision system

**Observed:** Five Plan cells follow an editorial title/support split. A usage calculator pairs selection chips and a slider on the left with an inset stone recommendation card on the right; its serif plan name reaches 48px. A detailed comparison matrix follows with a translucent sticky tier header, 12px backdrop blur, faint alternate rows and stone category bands.

**Transfer:** Keep tier choice, individualized recommendation and exhaustive comparison as separate reading layers.

**Text style:** `price` — PP Kyoto-b14c6ebb315b725b 500 · 36px/1.3

### Dual-path closing

**Observed:** A 26px serif invitation sits above two Conversion cells: assisted contact and immediate self-service. The latter owns the green button. The default marketing variant adds a narrow chalk recruitment strip below; product and use-case variants proceed directly toward the directory.

**Transfer:** End with two genuinely different paths to adoption. A narrow editorial opportunity strip can be used when there is a real secondary audience.

**Text style:** `heading` — PP Kyoto-b14c6ebb315b725b 500 · 26px/1.3

### Ruled directory ending

**Observed:** Every ending uses the same tall directory: wider identity column with mission, socials, AI-provider shortcut icons and language control; four navigation columns divided by 1px rules, with products and company stacked in the first. Beneath, a top-ruled legal strip places copyright and an 8px green operational dot left, policy links right. The floating Conversation launcher remains at the lower right. Pricing proceeds from FAQ directly to this ending rather than adding conversion cells.

**Transfer:** Keep the identity block, useful grouped navigation and compact operational/legal strip; scale link counts to real content.

## Page flow

**Storyline:** Promise → tangible product experience → capability explanation → substantiated proof → operational detail → practical objections → appropriate adoption path and directory.

### Broad platform introduction

1. **Promise and experience** — Two-tone editorial headline and centered cloud instrument carousel.
2. **Application framing** — Tabbed illustrated environment followed by rank/customer matrix.
3. **Capability system** — Paired technical stages and a full-width integration diagram.
4. **Foundational rationale** — Short chalk editorial band.
5. **Operational confidence** — Layered architecture illustration and deployment accordion.
6. **Closing call** — Two conversion paths, narrow opportunity strip, ruled directory and legal status strip.

**Transfer:** Move from an inviting tangible presence to the system underneath it; avoid presenting the whole platform as undifferentiated features.

### Commercial evaluation and plan choice

1. **Commercial promise** — Left editorial title paired with a brief right-side payment explanation.
2. **Pricing** — Five adjacent tier cells with one green selection action.
3. **Personalized decision** — Feature chips and usage slider beside a recommendation panel.
4. **Detailed comparison** — Dense ruled matrix with persistent tier headings.
5. **Objection handling and ending** — Split FAQ leads directly into the common directory and operational/legal strip.

**Transfer:** Let scanning, estimation and exhaustive comparison serve different reader needs without changing the visual framework.

### Single capability adoption through a working tool

1. **Promise and demonstration** — Centered benefit headline, proof badge, paired actions and two-panel input/result tool.
2. **Method comparison** — Two adjacent cells with requirements, available tiers and next steps.
3. **Application breadth** — Three-column sample library with compact play controls.
4. **Instruction and constraints** — Four illustrated numbered steps followed by a factual permission note.
5. **Related capabilities** — Three resource cells.
6. **Objection handling** — Split FAQ.
7. **Closing call and ending** — Dual conversion cells followed by common ruled directory and operational/legal strip.

**Transfer:** Show a small usable interaction first, then methods, examples, preparation and limits.

### Translate a technical platform into a specific operational use case

1. **Outcome promise** — Left-aligned headline and support, paired actions, right-side clouded instrument.
2. **Context and workflows** — Introductory explanation and four illustrated workflow cells.
3. **Implementation demonstration** — Configuration panel beside an illustrative conversation.
4. **System integration** — Full-width signal/node diagram with compact resource links.
5. **Evaluation and proof** — Practical outcome checklist, quotation grid and certification strip.
6. **Objection handling** — Split FAQ followed by a compact related-use-case link grid.
7. **Closing call and ending** — Dual conversion cells and common directory with operational/legal strip.

**Transfer:** Connect the reader's existing work to implementation, evaluation and trust rather than only listing abstract benefits.

## Writing

Calm technical confidence with a direct invitation to try. Editorial claims are followed by concrete descriptions of what happens, what the user needs and where the limits lie.

**Do not copy:** Do not reuse Cartesia's name, product names, artwork, customer marks or quotations, rankings, benchmark claims, prices, latency numbers or capability assertions as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your in practical guidance; use we or our sparingly for the organization and name the product when describing implementation.
- **Rhythm:** Short declarative headings and compact support sentences. Long technical detail belongs in explanatory cells or FAQs, not in the hero; actions are brief verb phrases and punctuation stays restrained.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Concrete category or benefit, followed by a compact reason to believe; can split into two tonal thoughts. | 5–14 words per thought | “#1-ranked for realtime voice.”<br>“Models and agents built on frontier research.” |
| Section heading | Name the capability or issue directly; paired clauses can create a memorable contrast. | 4–10 words | “Deploy AI anywhere. Own it everywhere.”<br>“Make sure the voice is yours to use” |
| Supporting line | Describe the reader's next action or the operational mechanism, not generic transformation. | 1–3 compact sentences | “Start free, scale as you ship. Pay for the credits and agent minutes you use.”<br>“Start with an instant clone. Listen to the result before committing to a longer recording session.” |
| Primary action | Action verb plus product or immediate task. | 2–4 words | “Try [Brand]”<br>“Clone your voice” |
| Practical guidance | State a constraint plainly, then give a testable next step. | 1–3 sentences | “Keep music and other speakers out of the recording. Use a quiet room and speak naturally in the tone you want customers to hear.” |

**Words and phrasing to use:** build; connect; record; test; compare; your existing tools; in production; real requests; start; learn

**Avoid:** revolutionary; game-changing; magical; limitless; supercharge; effortlessly transform everything

**Rules:**

- Follow a broad claim with an operational explanation.
- Give readers explicit requirements and permission boundaries where relevant.
- Use measurable claims only when the new product can substantiate them.
- Separate an invitation to start from an invitation to speak to an expert.

## Do's and Don'ts

### Do

- Keep the default hero serif at 40px/1.15 and section leads at 26px/1.3.
- Maintain the 1280px ruled frame and 48px desktop inner gutters.
- Use 1px adjoining cell divisions instead of wide gaps between every card.
- Keep primary actions 36px tall with 8px corners and 14px/20px medium labels.
- Include both a clouded circular instrument and a fine-line explanatory graphic.
- Use 56px chapter padding and 12px heading/support gaps as recurring rhythms.
- Preserve two separate adoption paths in the marketing closing.
- Keep the directory vertically ruled and include the compact status/legal strip.

### Don't

- Do not use a black or saturated green page canvas; green is an action and media accent.
- Do not round the structural grids into 16px floating tiles.
- Do not apply the launcher's pill silhouette to ordinary buttons.
- Do not add large diffuse card shadows throughout; structural cells use a 1px edge.
- Do not turn the small technical mono into an all-caps eyebrow above every heading.
- Do not make the serif display bold, ultra-condensed or dramatically larger than 40px.
- Do not replace the fine outline media with glossy stock photography or dark neon 3D scenes.
- Do not fill the footer with oversized typography or a monumental wordmark; it is a practical directory.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.15s cubic-bezier(.4,0,.2,1) color/background/border or all-property transitions.
- The floating conversation button declares an opacity transition and hover opacity 0.8.
- Signal panels and clouded objects have dedicated animation implementations; declared names include bar pulses, transcription movement and speaking states.

**Transfer:**

- Keep control feedback quick and localized; the atmosphere belongs to the circular object and technical signal stages, not moving whole page sections.

**Unknown:**

- Exact object animation cycles, autoplay sequencing and scroll-reveal behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 360px, 640px, 768px, 1024px, 1280px, 1440px and 1536px.
- Container classes declare narrower 16px side allowance on small screens and 48px at wider widths; section padding classes progress through 16px, 32px and 48px.
- Grid declarations progress from one column to two, then three or five where appropriate; the full desktop navigation is declared only at the widest navigation breakpoint.

**Transfer:**

- At narrow widths retain the ruled document idea, stack adjoining cells and reduce inner gutters before shrinking body text.
- Keep the dominant clouded disc legible and let peripheral discs clip rather than making all five equally tiny.
- Stack split text/object and configuration/conversation layouts while retaining input-before-result reading order.

**Unknown:**

- Mobile navigation interaction, exact narrow-screen object sizing and pricing-table overflow behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
