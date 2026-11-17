# Hightouch — campaigns in the atmosphere

## Overview

A bright, commercially confident style for software that turns complex work into tangible output. Warm yellow, misty teal and occasional peach atmospheres sit behind crisp interfaces and rich photographic examples, while most reading happens on white. A rounded geometric grotesk and tiny monospaced labels give the spacious compositions a practical, product-led feel; the ending switches to a deep dark field.

### Essentials

- The promise sits above a gallery of finished work: a split opening pairs a 64px/74px regular headline with a 22.8px/32px explanation, then gives most of the first screen to floating output cards.
- Type changes personality between promise and explanation: the opening uses weight 400 and -0.03em tracking; working section headings use 32.9px/40px at 700, with -0.015em tracking.
- Color is an atmosphere, not a button system: use a full-width yellow-to-teal opening, then mostly white reading sections with localized misty media stages; reserve solid dark fields for the closing conversion and footer.
- Actions are small rounded rectangles rather than capsules: 44px height, 16px radius, charcoal fill, 13.2px/20px semibold labels and a 20px right chevron.
- Product imagery feels like material laid out on a desk: large 1200×534px stages, softly blurred colored backing, rounded corners and white interface panels; include a layered output scene even when it must be redrawn as simplified UI.
- Proof has its own visual grammar: oversized 68.1px/72px bold numbers sit beside 11px uppercase mono descriptors, above a fine rule and a customer mark; use verified outcomes or equally concrete process measures.
- The ending is a deliberate change of light: a centered 56.8px/64px bold invitation on near-black leads into five compact link columns, with 96px structural gaps and an 8px mint status dot.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint wash | `#e3fcee` | `--color-mint` | background, surface | Positive comparison cells and pale proof-art backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#302d2e` | `--color-secondary` | text, action, border | Paragraphs and primary action fill and edge. |
| Primary ink | `#141213` | `--color-ink` | text, background | Headlines and primary text; default closing field. |
| Action hover | `#696365` | `--color-hover` | action, border | Primary button hover and focused background. |
| Action active edge | `#8f8a8b` | `--color-active-edge` | border | Focused and active primary action edge. |
| Warm gray rule | `#c7c2c3` | `--color-rule` | border, surface | Separators, inactive progress tracks and outlined action edges. |
| Light edge | `#ebebeb` | `--color-edge` | border, text | Fine media edges and inverse supporting text. |
| Soft gray | `#f5f5f5` | `--color-soft` | surface, text, background | Feature cards and light bands; inverse action and heading text. |
| White | `#ffffff` | `--color-canvas` | background, surface | Main reading canvas and raised interface panels. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mint | `#40de9e` | `--color-focus` | accent, border | Focus ring and small system-status dot; not a broad conversion fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| warm audience-solution pages | Peach | `#fee6ca` | `--color-peach` | background, surface | Hero and luminous testimonial enclosure. |
| specialized product pages | Ice blue | `#ebf9fc` | `--color-ice` | background | Announcement strip. |
| warm audience-solution pages | Warm dark | `#240802` | `--color-warm-dark` | background | Closing conversion and footer. |
| specialized product pages | Blue black | `#02131b` | `--color-blue-dark` | background | Closing conversion and footer in the cool product theme. |
| product demonstrations | Interface canvas | `#fafafa` | `--color-ui-canvas` | surface | Inset application shell, not the marketing page canvas. |

## Typography

- **Nuckle** — All marketing headings, prose, navigation and actions. Geometric grotesk with rounded bowls, open counters and a light, wide regular cut contrasted with dense bold headings. OpenType features: "kern". If unavailable, use **DM Sans**. Use 400, 600 and 700; preserve tight large-type tracking and slightly open small text. Font stack: "Nuckle", "DM Sans", sans-serif.
- **DM Mono** — Uppercase product labels, chapter markers and statistical descriptors. Compact utilitarian monospace that contrasts with the rounded main face. Font stack: "DM Mono", monospace.
- **Inter** (only for product demonstrations) — Application controls and editor details inside interface artwork. Neutral, compact interface sans; it is not the marketing headline voice. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | Nuckle | 700 | 68.1px | 72px | -0.03em | Large numerical outcome. |
| display | Nuckle | 400 | 64px | 74px | -0.03em | Default split-stage opening headline, normally two lines. |
| closing-display | Nuckle | 700 | 56.8px | 64px | -0.03em | Centered closing invitation; also the bold opening treatment for specialist studio and warm solution variants. |
| heading | Nuckle | 700 | 32.9px | 40px | -0.015em | Default major section heading, left aligned over a demonstration or centered over proof. |
| heading-sm | Nuckle | 700 | 27.4px | 32px | -0.0125em | Wide product cards, compact proof statements and trust headings. |
| lead | Nuckle | 400 | 22.8px | 32px | -0.005em | Opening explanation and closing supporting paragraph. |
| item-heading | Nuckle | 700 | 19px | 24px | -0.01em | Feature titles and logo-wall introduction. |
| body | Nuckle | 400 | 17.4px | 24px | 0.005em | Default explanatory paragraphs, generally constrained to 500px. |
| card-caption | Nuckle | 600 | 17.4px | 24px | 0.005em | Centered recognition-card captions. |
| small-body | Nuckle | 400 | 13.2px | 20px | 0.0275em | Navigation and detailed feature descriptions. |
| action | Nuckle | 600 | 13.2px | 20px | 0.0275em | Buttons, short text links and announcements. |
| eyebrow | DM Mono | 500 | 11px | 16px | 0.035em, uppercase | Compact category labels in product-card compositions. |
| stat-label | DM Mono | 500 | 11px | 16px | 0.025em, uppercase | Short descriptor positioned beside the lower portion of a large number. |
| footer-link | Nuckle | 600 | 11px | 16px | 0.035em | Compact footer directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| specialized product and audience-solution pages | heading-lg | Nuckle | 700 | 47.3px | 56px | -0.02em | Centered major section statements and compact platform openings. |
| specialized product and audience-solution pages | section-lead | Nuckle | 400 | 19px | 28px | normal | Support for large centered section headings. |
| audience-solution FAQs | question | Nuckle | 700 | 17.4px | 24px | -0.011em | Accordion questions. |
| chaptered product pages | chapter-label | DM Mono | 500 | 13.2px | 20px | 0.0275em, uppercase | Workflow chapter markers above left-aligned headings. |
| specialized product and audience-solution openings | hero-label | DM Mono | 500 | 13.2px | 1 | 0.025em, uppercase | Product name or audience above the hero promise. |

**Notes:**

- The regular opening is exceptional: most section headings are bold, not lightweight.
- Negative tracking tightens with size, reaching -0.03em on display and statistics; small prose and actions open to 0.0275em.
- Use mono only for short labels. Photographic examples and application artwork can contain their own editorial fonts without changing the page typography.
- Line breaks group a clear benefit into two or three compact lines; do not stretch centered copy across the full container.

## Layout

**Density:** Airy at section scale, compact within interfaces and controls; wide quiet intervals separate dense demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon gaps and tight inset framing. |
| 12px | Adjacent actions and footer link rhythm. |
| 16px | Opening support-to-action gap and small card insets. |
| 24px | Grid gaps and card padding. |
| 32px | Heading-to-support gap, stacked product-card gap and many section-heading pairs. |
| 40px | Closing call content gaps and rows of integration marks. |
| 64px | Opening top padding, proof media separation and closing call vertical inset. |
| 96px | Large text-to-scene separation, major band padding and footer structural gaps. |
| 160px | Separation between major narrative chapters. |

### Containers and grids

- **main-container**: max width 1200px · side padding 0px. Centered desktop content gives 120px margins at 1440px. Full-bleed atmospheres and carousels escape this container.
- **opening-split**: max width 1200px · 2 columns · gap 96px. 500px headline on the left and a support/action group up to 580px on the right; align by visual center.
- **centered-copy**: max width 680px. Centered section statements and closing support. Wider 840px statements belong to specialist product chapters.
- **feature-grid**: max width 1200px · 4 columns · gap 24px. Four 282px feature tabs or small capability columns beneath a large scene.
- **proof-grid**: max width 1200px · 3 columns · gap 24px. Three 384px metric blocks or feature cards.
- **media-pair**: max width 1200px · 2 columns · gap 24px. Two 588px feature panels; testimonial splits pair concise copy with roughly 596×335px media.
- **footer-grid**: max width 1200px · 5 columns · gap 24px. Compact directories with independent link stacks.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 16px |
|  | feature-panels | 24px |
|  | media | 16px |
|  | icon-discs | 50% |
| product demonstrations | small-ui-tiles | 8px |
| warm audience-solution testimonials | testimonial-inner | 64px |
| warm audience-solution testimonials | testimonial-outer | 96px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | recognition-card | `rgba(0, 0, 0, 0.05) 0px -1px 6px 0px, rgba(0, 0, 0, 0.04) 0px 12px 12px 0px, rgba(0, 0, 0, 0.02) 0px 27px 16px 0px, rgba(0, 0, 0, 0.01) 0px 47px 19px 0px` | Floating white recognition cards. |
| product demonstrations | interface-shell | `rgba(0, 0, 0, 0.04) 0px 4px 8px 0px, rgba(0, 0, 0, 0.06) 0px 0px 2px 0px, rgba(0, 0, 0, 0.12) 0px 0px 1px 0px` | Subtle application-shell lift, with a fine outline rather than a heavy drop shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading background.

**CSS:** `background: #ffffff; color: #141213`

#### Soft feature panel · level 1

**Use:** Grouped capability explanations with images.

**CSS:** `background: #f5f5f5; border-radius: 24px; overflow: hidden`

**Observed:** Large low-contrast panels carry text above a product scene; images can reach the lower and side edges.

**Transfer:** Use for a concrete capability, not as a container around every paragraph.

#### Fading reading band · level 0

**Use:** Long demonstration chapters.

**CSS:** `background: linear-gradient(#ffffff, #f5f5f5)`

**Observed:** The page drifts from white toward soft gray without a hard band boundary.

**Transfer:** Keep the upper text area almost white and the strongest tone behind media.

#### Dark closing field · level 0

**Use:** Conversion invitation and directory footer.

**CSS:** `background: #141213; color: #f5f5f5; padding-top: 96px`

**Observed:** A continuous dark region connects the call to action and dense footer. The cool product variant uses blue black; warm solution pages use brown black.

**Transfer:** Use the default near-black unless the whole page belongs to a scoped color theme.

#### Application shell · level 1

**Only for:** product demonstrations

**Use:** Large interactive or illustrated editor.

**CSS:** `background: #fafafa; border: 0.5px solid #ebebeb; border-radius: 16px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.04) 0px 4px 8px 0px, rgba(0, 0, 0, 0.06) 0px 0px 2px 0px, rgba(0, 0, 0, 0.12) 0px 0px 1px 0px`

**Observed:** White sidebars, delicate gray dividers, a slim tool rail and a large central work area give the software credible structure.

**Transfer:** Show only enough interface detail to make the workflow understandable.

#### Frosted subscription panel · level 1

**Only for:** cool chaptered product pages

**Use:** Secondary subscription invitation before the final conversion.

**CSS:** `background: rgba(255, 255, 255, 0.3); border: 1px solid rgba(255, 255, 255, 0.5); border-radius: 16px; backdrop-filter: blur(16px); padding: 96px 24px`

**Observed:** A broad translucent rectangle sits over a pale blue gridded atmosphere with centered copy.

**Transfer:** Keep the backdrop visible through the panel; do not make this the default feature-card material.

#### Luminous peach testimonial · level 1

**Only for:** warm audience-solution pages

**Use:** A single high-emphasis customer quotation.

**CSS:** `background: #fee6ca; border-radius: 64px; padding: 96px; box-shadow: #ffffff 0px 0px 52px 16px`

**Observed:** An outer peach enclosure has 96px corners, 40px padding and white plus peach glows, making nested rounded rings rather than a flat colored card.

**Transfer:** Keep logo, substantial quote and small attribution centered; preserve the glowing nested silhouette.

## Components

### Primary button

**Use:** Main conversion and important editorial actions.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; box-sizing: border-box; background: #302d2e; color: #f5f5f5; border: 1px solid #302d2e; border-radius: 16px; padding: 12px 12px 12px 16px`

**Text style:** `action` — Nuckle 600 · 13.2px/20px · tracking 0.0275em

**Observed:** The label precedes a compact right chevron, making a directional action rather than a centered pill. Use the same construction in light and dark sections.

**States:** Declared: hover background and border #696365; focus-visible background #696365, border #8f8a8b and 0px 0px 0px 2px #40de9e ring; active border #8f8a8b and outline none.

### Outlined button

**Use:** Utility actions and carousel arrows.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; box-sizing: border-box; background: #ffffff; color: #141213; border: 1px solid #c7c2c3; border-radius: 16px; padding: 12px 16px`

**Text style:** `action` — Nuckle 600 · 13.2px/20px · tracking 0.0275em

**Observed:** Utility label only; carousel controls use square versions with a single directional glyph.

**States:** Declared: hover border changes to secondary text color and ink label; focus-visible 0px 0px 0px 2px #40de9e ring and transparent border; active ink border and outline none.

### Navigation bar

**Use:** Persistent orientation above the page.

**CSS:** `position: sticky; top: 0px; height: 72px; background: #ffffff; color: #302d2e; z-index: 1100`

**Text style:** `small-body` — Nuckle 400 · 13.2px/20px · tracking 0.0275em

**Observed:** A 1200px centered row holds a compact black wordmark left, six understated links in the middle and outlined plus primary actions right, 12px apart. A 44px announcement strip precedes it. In dark closing regions the navigation can invert.

**States:** Declared: hover links have no text decoration; focus-visible 0px 0px 0px 2px #40de9e ring; active outline none.

**Transfer:** Use similarly short category names and keep the header subordinate to the hero.

### Wide product card

**Use:** Present a small set of related products or major capabilities.

**CSS:** `display: flex; align-items: center; gap: 40px; background: #f5f5f5; border-radius: 24px; overflow: hidden`

**Text style:** `heading-sm` — Nuckle 700 · 27.4px/32px · tracking -0.0125em

**Observed:** A 1200×350px linked panel holds a 480px text region with 64px left inset and 24px internal gaps; a large interface scene enters from the right. Atmospheric art spans both halves. A mono label precedes the title, description and small arrow link.

**States:** Declared: focus-visible 0px 0px 0px 2px #40de9e ring and outline none.

**Transfer:** Create a meaningful pair of capabilities with different imagery, not a wall of identical cards.

### Feature progress tab

**Use:** Explain multiple views of a large product demonstration.

**CSS:** `display: flex; flex-direction: column; justify-content: center; gap: 8px; border-radius: 16px; background: transparent; color: #141213`

**Text style:** `item-heading` — Nuckle 700 · 19px/24px · tracking -0.01em

**Observed:** Four equal columns sit below the scene. Each has a 2px warm-gray track with a thin green active segment, then a heading and small-body description 24px apart. The visual emphasis comes from the track, not a filled tab background.

**States:** Declared: focus-visible 0px 0px 0px 2px #40de9e ring.

**Transfer:** Tie every tab to a distinct product state.

### Recognition card

**Use:** Third-party endorsements and awards.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 32px; background: #ffffff; color: #141213; border-radius: 24px; padding: 24px 24px 40px; box-shadow: rgba(0, 0, 0, 0.05) 0px -1px 6px 0px, rgba(0, 0, 0, 0.04) 0px 12px 12px 0px, rgba(0, 0, 0, 0.02) 0px 27px 16px 0px, rgba(0, 0, 0, 0.01) 0px 47px 19px 0px`

**Text style:** `card-caption` — Nuckle 600 · 17.4px/24px · tracking 0.005em

**Observed:** A 312×408px white card contains a 264×240px colored mark panel over a centered caption. Cards extend beyond both viewport edges and have centered arrow controls beneath.

**States:** Declared: hover no text decoration and ancestor-hover translateY(-8px); focus-visible uses a link-card outline; active outline none.

**Transfer:** Keep an airy outer frame even when the endorsement artwork has strong colors.

### Metric block

**Use:** Quantified proof.

**CSS:** `display: flex; flex-direction: column; color: #141213; max-width: 384px`

**Text style:** `stat` — Nuckle 700 · 68.1px/72px · tracking -0.03em

**Observed:** The large value and tiny mono descriptor share a row aligned near the baseline with 16px between them. A warm-gray rule spans the block below; a small linked customer mark sits underneath. Three blocks use a 24px grid gap.

**Transfer:** Use a short metric and an unambiguous descriptor; retain a source or attribution mark.

### Integration mark link

**Use:** Breadth-of-compatibility strip.

**CSS:** `display: flex; align-items: center; width: 144px; height: 48px; border-radius: 4px`

**Observed:** A 48px contained logo is flanked by 48px space on both sides. Three full-width rows are separated by 40px and clipped softly at viewport edges.

**States:** Declared: hover transform scale(0.92); focus-visible 0px 0px 0px 2px #40de9e ring and transparent border; active outline none.

**Transfer:** Use relevant ecosystem marks or labeled tool symbols rather than feature-card boxes.

### Footer link column

**Use:** Dense directory beneath the closing call.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 16px 0px; color: #f5f5f5`

**Text style:** `footer-link` — Nuckle 600 · 11px/16px · tracking 0.035em

**Observed:** Five columns organize product, audience, learning, company and legal destinations. Small bold category labels divide subgroups. The final utility row includes status at left and copyright at right, with ample separation from legal copy.

**States:** Declared: hover no text decoration; focus-visible 0px 0px 0px 2px #40de9e ring and transparent border; active outline none.

**Transfer:** Keep the directory compact, even when the closing invitation is expansive.

### FAQ row

**Only for:** audience-solution pages

**Use:** Answer implementation and adoption objections.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 24px; padding: 24px 0px; border-radius: 16px; background: transparent; color: #141213`

**Text style:** `question` — Nuckle 700 · 17.4px/24px · tracking -0.011em

**Observed:** A centered 700px stack uses thin warm-gray dividing rules and a small down chevron in a pale circular backing at the right.

**States:** Declared: hover background transparent; focus-visible 0px 0px 0px 2px #40de9e ring.

**Transfer:** Keep questions concrete and answer the likely buying barriers.

## Imagery and graphics

### Atmospheric output stage

**Use:** Signature opening and recurring product-media backing.

**Observed:** Soft gold light wraps a cloudy teal center. Photographic finished-work cards float in front, with a larger central card, smaller lateral cards and partial cards beyond the viewport. Realistic product and lifestyle imagery stays sharply legible against the defocused background.

**Transfer:** Show the new product's finished output or a credible result. If photography is unavailable, use three carefully composed interface/output panels with one dominant panel and partially visible neighbors; retain the atmosphere and depth.

**Build:** Recommended reconstruction: layer oversized radial gradients of translucent golden yellow at the top and right, muted teal at lower center and cream between them. Blur the color layer by 50–80px, extend beyond the section and clip its edges. Place rounded output cards above it, center card about 370px square and lateral cards about 280px square; use scale and opacity rather than heavy shadows to imply depth. Match the soft glow; exact stops are not essential.

### Cloud-backed interface stage

**Use:** Capability demonstrations and proof artwork.

**Observed:** A broad rounded stage, commonly 1200×534px, carries misty blue-green clouds and occasional olive or pale rose light. A crisp white application panel sits inset or enters from below; dialogs can float over it. Corners are soft, but perspective is restrained.

**Transfer:** Rebuild the actual workflow using a slim tool rail, a useful main canvas and one clear control panel. Keep complexity inside the demonstration instead of spreading UI across the marketing layout.

**Build:** Recommended reconstruction: put two or three blurred radial color fields behind a white interface sheet; add a very low-opacity cloud texture with SVG turbulence, then a white veil. Use 24px stage corners, a fine gray interface edge and the Application shell shadow. Keep the main interface nearly front-on and allow its bottom edge to be clipped.

### Overlapping context deck

**Use:** Signature capability summary.

**Observed:** Four white 329×409px cards overlap across the container and descend in a shallow staircase. Each has an almost-square illustrated UI scene in muted teal and a short bold caption below; the cards have 24px corners and understated layered shadows.

**Transfer:** Use four stages or ingredients of the new product's process. Recreate them as simple meaningful interface fragments, not abstract stock icons.

**Build:** Recommended reconstruction: lay out four 329px cards with about 39px overlap and increasing stacking order; offset each successive card downward by a small equal step. Give each an 8px white frame, a colored UI tile and a caption inset by 16px. Draw small rounded panels, charts, asset thumbnails and connecting nodes as SVG; keep all scenes in one teal-gray palette.

### Customer video proof

**Use:** Human testimony between software-heavy chapters.

**Observed:** Wide documentary scenes show people in workplaces, retail spaces or real public settings. Videos use rounded rectangles, a translucent circular play control and restrained white identification overlays. Large carousels show an 800×450px active frame plus clipped neighbors; split proof rows use roughly 596×335px media.

**Transfer:** Use honest interviews or footage of the real context in which the product delivers value; let the environment provide color.

### Recognition atmosphere

**Use:** Backing for the recognition carousel.

**Observed:** White at the top changes into a softly mottled rose and lavender floor behind floating white cards. The colored floor is blurred and does not compete with the endorsement panels.

**Transfer:** Maintain this luminous floor beneath proof cards even when the panel artwork changes.

**Build:** Recommended reconstruction: place broad translucent rose and lavender radial fields low in the section and blur them; layer a white-to-transparent gradient over the upper half. Keep the cards and controls on top.

### Cool grid atmosphere

**Only for:** chaptered studio product pages

**Use:** Opening and secondary closing bands.

**Observed:** Pale blue cloudy light sits beneath a fine white square grid; the scene fades toward white at its boundary. The hero floats an example output and a translucent insight card between headline and explanation.

**Transfer:** Use one realistic output and a small explanatory insight, preserving legibility over the pale grid.

**Build:** Recommended reconstruction: combine pale blue-gray radial gradients, subtle noise and two repeating linear gradients of rgba(255,255,255,0.25) with 1px lines at roughly 40px intervals. Add a white linear fade at the lower edge. Float the main output above the grid and use the Frosted subscription panel material for the small insight card.

### Orbiting creative gallery

**Only for:** creative-tool openings

**Use:** Center a strong product promise among examples.

**Observed:** Rounded photographic creative tiles form a loose ring around an untouched white center. Tiles vary in scale and tilt, some exiting the edges; a broad white radial veil protects headline and action.

**Transfer:** Arrange finished examples around the promise, with the most colorful work away from text.

**Build:** Recommended reconstruction: position eight to twelve rounded image planes around an elliptical perimeter; vary width and rotate each slightly in 2D or restrained perspective. Overlay a radial white gradient, strongest in the center and transparent at the outside. Keep the headline and action in the clear center.

### Particle intelligence field

**Only for:** platform-overview pages

**Use:** An abstract opening motif and explanatory capability scenes.

**Observed:** An airy cyan-to-mint point field forms a loose twisting silhouette behind centered text. Later scenes pair a central tile with floating blue labels, pale cyan backing and delicate connectors; an overview diagram organizes three horizontal tiers inside a white panel.

**Transfer:** Use the point field to suggest orchestration rather than a humanoid robot. Translate the product into a few labeled input, capability and outcome groups.

**Build:** Recommended reconstruction: use SVG circles on a warped triangular or wave-shaped grid, decreasing opacity toward the edges; tint points cyan and mint and mask a clear center behind copy. For diagrams, draw thin blue connectors with small terminal dots and rounded white or blue label tiles. A static point field with layered opacity is the minimum acceptable version.

### Icons

**Observed:** Most marketing glyphs are simple filled SVGs at 16px or 20px, chiefly dark ink or inverse white. Right chevrons finish actions. Benefit illustrations can use 20px outline icons with 1.5px round strokes in 48px pale discs; trust marks use larger monochrome 120px circles.

**Transfer:** Choose one compact icon family, avoid oversized decorative line art, and keep expressive color inside small discs or product scenes.

## Section recipes

How recurring sections are built.

### First screen: Split promise and output gallery

**Observed:** A 44px announcement and 72px white Navigation bar sit above a full-width atmospheric hero. Within the 1200px container, 64px top padding leads to a 500px two-line regular headline at left; a 580px explanation and Primary button sit at right, with 16px between support and action. The headline occupies a little under half the content width, not the entire screen. Behind both is the Atmospheric output stage; below the text a larger central finished-work card is flanked by smaller cards, with more examples clipped at the edges. Within the first 900px the complete headline, explanation, action and most of the central output gallery are visible; the lower layered UI deck and the following customer proof fall below.

**Transfer:** Make the headline a broad outcome and the right explanation a concrete mechanism. Replace the examples with the new product's most convincing outputs, keeping one large center example and smaller neighbors. Specialized studio pages instead use bold display text with an output between copy columns or a centered promise inside an Orbiting creative gallery; platform overviews use a centered statement over a Particle intelligence field. Warm audience pages pair a bold left promise with a right-side data/action illustration.

**Avoid:** Do not replace the lower gallery with a small dashboard thumbnail, center all copy by default, or turn the background into a hard multicolor stripe.

**Text style:** `display` — Nuckle 400 · 64px/74px · tracking -0.03em

### Heading and demonstration chapter

**Observed:** A left-aligned 600px heading group uses Heading with Body 32px below, followed by a broad Cloud-backed interface stage after 40–96px. Feature progress tabs sit below the scene. Specialist versions enlarge the centered headline to Heading-lg and support to Section-lead.

**Transfer:** Use one chapter to explain one meaningful workflow, with tabs for distinct views rather than unrelated marketing benefits.

**Text style:** `heading` — Nuckle 700 · 32.9px/40px · tracking -0.015em

### Product family pair

**Observed:** A centered Heading introduces two stacked Wide product cards after 64px; cards are separated by 32px. Their artwork has a continuous atmosphere while the left text stays high contrast.

**Transfer:** Use for two related ways to solve the customer's problem; adapt the number of panels to the content.

### Layered capability summary

**Observed:** A left Heading and Body introduction lead into the Overlapping context deck. The staggered white frames make the capabilities feel connected rather than isolated grid tiles.

**Transfer:** Use the signature deck at an appropriate summary point, with captions that name distinct capabilities.

### Quantified customer proof

**Observed:** A centered Heading precedes a Customer video proof carousel, with concise outcome captions and Primary buttons. A separate three-column Metric block row uses Stat and Stat-label without card fills.

**Transfer:** Mix human stories and hard numbers; allow either proof mode to lead based on available verified material.

### Recognition and trust

**Observed:** Centered Heading-sm, a 32px support gap and 64px separation lead to five monochrome trust discs. Recognition cards sit in an edge-clipped carousel above the Recognition atmosphere, with outlined arrow controls below. The warm solution variant uses a plain soft-gray band instead of the colored floor.

**Transfer:** Use formal badges sparingly and give larger third-party endorsements their own stage.

### Compatibility field

**Observed:** A centered Heading, Body and Primary button are spaced 32px apart. Three rows of Integration mark links follow after 96px, each 48px high with 40px row gaps and full-bleed clipping.

**Transfer:** Show the ecosystem most relevant to the new product; the field conveys breadth without turning into a card grid.

### Closing invitation and directory

**Observed:** The Dark closing field begins with 96px top padding. A centered Closing-display, Lead paragraph and Primary button have 40px gaps and 64px upper/lower inset within the call. After a 96px structural gap, five Footer link columns fill the 1200px container. A separated utility row includes the mint status dot, locale where needed and copyright; legal text follows. Product variants use blue black, warm solution variants brown black. The creative-tool variant omits the support paragraph and gives the invitation a wider, taller stage.

**Transfer:** End with a specific low-friction next step and an expansive dark invitation, then compact navigation. Keep the final field continuous through the footer.

**Text style:** `closing-display` — Nuckle 700 · 56.8px/64px · tracking -0.03em

### Warm comparison and testimony

**Only for:** audience-solution pages

**Observed:** A centered Heading-lg, Section-lead and action lead into a broad white rounded comparison board. Two equal columns pair soft-gray legacy conditions with mint improved conditions. Later, the Luminous peach testimonial gives a centered 32.9px/40px bold quote, customer mark and compact attribution an unusually expansive glowing enclosure.

**Transfer:** Compare a familiar frustrating workflow with a verifiable improvement. Use the luminous quote as a concentrated proof moment rather than adding peach to every section.

### Studio capability mosaic

**Only for:** chaptered studio product pages

**Observed:** Mono Chapter-label precedes a left Heading and Body by 32px. A large editor scene is followed by a two-column row of 588px panels and a three-column row of 384px panels, each with a short Item-heading and concrete interface illustration.

**Transfer:** Move from an end-to-end view into smaller supporting capabilities, letting panel width follow the amount of information.

## Page flow

**Storyline:** Outcome promise → tangible output → customer credibility → capability demonstrations → focused proof and risk reduction → ecosystem breadth → dark closing invitation and directory.

### Broad product-family landing page

1. **Promise** — Split regular-weight headline and mechanism over a colorful floating-output gallery.
2. **Product orientation** — Customer marks, then two broad linked product panels and a layered capability deck.
3. **Product demonstration** — Large interface scene with four progress tabs.
4. **Social and quantified proof** — Independent report feature, customer-video carousel and three oversized metrics.
5. **Risk reduction** — Monochrome security discs and a recognition-card carousel.
6. **Closing call** — Three-row integration field leads into a near-black invitation and five-column directory.

**Transfer:** Use this as the default vocabulary for a new marketing landing page, selecting the demonstrations and proof that support its promise.

### Audience-specific solution page

1. **Promise** — Warm peach two-column opening with mono audience label, bold headline and a practical data/action illustration.
2. **Quantified proof** — Customer marks and three metric blocks establish credibility early.
3. **Capability and differentiation** — Large tabbed demonstration, two-column comparison board and benefit columns.
4. **Social proof** — Glowing nested peach quotation enclosure.
5. **Objection handling** — Video explanation, use-case tabs and a narrow FAQ stack.
6. **Closing call** — Recognition cards, compatibility field and warm brown-black demo invitation plus directory.

**Transfer:** Use the warm scoped theme for audience buying concerns; keep comparisons factual and questions adoption-focused.

### Workflow-centered studio product page

1. **Promise** — Cool grid atmosphere with bold left headline, floating example output in the middle and support/action at right.
2. **Product demonstration** — Centered large statement over a full-width multi-column editor.
3. **Social proof** — Compact split customer interview and quantified outcome.
4. **Capability chapters** — Mono-labeled workflow chapters alternate large scenes, a feature mosaic, a compatibility field and a measurement demonstration.
5. **Secondary conversion** — Frosted subscription panel over the blue grid.
6. **Closing call** — Blue-black personalized demonstration invitation and directory.

**Transfer:** Organize a complex product by the user's actual stages of work; let the page alternate broad demonstration and smaller operational detail.

### Creative-tool product page

1. **Promise** — Centered bold promise inside an orbit of finished creative examples.
2. **Social proof** — Customer marks followed by a large rounded proof video.
3. **Capability chapters** — Three labeled workflow steps show discovery, editing and deployment; a large credible editor is the central demonstration.
4. **Applied proof** — Split real-world activation video.
5. **Supporting capabilities** — Two wide feature panels above three smaller panels, then governance badges and four compact assurance columns.
6. **Closing call** — Wide invitation without support paragraph on blue black, continuous into the directory.

**Transfer:** Give finished work top billing, then show enough editing detail and governance to make the creative promise credible.

### Platform overview and orchestration explanation

1. **Promise** — Centered bold headline over a mint-cyan particle silhouette, with output panels entering below.
2. **Problem framing** — Customer marks precede a grid of many small manual-work cards.
3. **Product orientation** — Two product cards on a cool atmosphere and a large three-tier architecture diagram.
4. **Capability chapters** — Concise text at left, large pale cyan animated explanatory scene at right.
5. **Breadth** — Two service-support columns and a rounded atmospheric workflow banner with icon discs.
6. **Closing call** — Blue-black personalized product invitation and five-column directory.

**Transfer:** Use a platform page to clarify relationships and inputs/outputs, not simply to multiply feature cards.

## Writing

Confident, practical and sympathetic to the effort behind a customer's work. Promises are direct and energetic, but grounded in workflows, visible outputs and measurable outcomes.

**Do not copy:** Do not reuse the Hightouch name, product names, customer marks, testimonials, proprietary artwork, award claims or performance numbers as claims for a different product. Source examples illustrate voice only.

- **Addressing the reader:** Address the reader as you and your. Name the product when explaining what it does; use we mainly in attributed testimony rather than in self-congratulation.
- **Rhythm:** Headlines usually use one compact benefit phrase over two lines. Supporting lines are one or two clear sentences; detailed feature paragraphs stay short and action-led. Commas and contrasts provide cadence without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar outcome made faster or qualitatively different; often a compact contrast. | 4–10 words | “Marketing looks different here”<br>“From idea to personalized campaigns, in minutes”<br>“Scroll-stopping ads, on demand” |
| Supporting line | Explain mechanism and context behind the benefit rather than restating the headline. | 15–30 words | “Connect AI that’s grounded in all your brand context and data to every customer-facing channel.”<br>“Build, edit, and launch on-brand ads at the volume performance marketing requires.” |
| Capability heading | Verb-led, concrete working action with a useful qualifier. | 3–10 words | “Launch across every channel, in the tools you already use”<br>“Sign off before anything ships” |
| Proof statement | Name an organization, a changed workflow and a verified result. | 10–20 words | “Thumbtack cut campaign cycles from six weeks to days with [Brand] Lifecycle Studio.” |
| Primary action | Short verb plus concrete object; demo language for conversion and story/report language for proof. | 2–5 words | “Get a demo”<br>“Talk to an expert”<br>“Read story” |
| Closing invitation | Invite the reader to see the product in action or try a relevant use case. | 4–12 words | “Get a personalized demo”<br>“See what you can create with Ad Studio today” |

**Words and phrasing to use:** your; on-brand; ready to ship; in minutes; without the handoffs; complete context; launch; connect; build; review; real-time; the tools you already use

**Avoid:** revolutionary synergy; unlock infinite possibilities; magic with no explanation; world-class as an unsupported boast; jokey developer slang; fear-heavy warnings

**Rules:**

- Lead with the changed experience; explain the technical mechanism immediately beneath it.
- Pair speed claims with an actual workflow, artifact or verified measure.
- Use reassurance through operational specifics: review, compliance, existing systems and control.
- Give each feature title an action and each paragraph one distinct job.
- Keep mono labels categorical and brief, not full sentences.

## Do's and Don'ts

### Do

- Keep the default opening headline at 64px/74px and weight 400; reserve bold 56.8px display for the closing or scoped product openings.
- Constrain most desktop content to 1200px and let only atmospheres, galleries and logo fields escape it.
- Keep actions at 44px high with 16px corners and compact 13.2px labels.
- Separate heading and body with 32px, and major chapters with 160px where the narrative needs a full reset.
- Stage interface demonstrations at roughly 1200×534px with a crisp white panel over softly colored light.
- Pair large metrics with 11px uppercase mono descriptors and a fine dividing rule.
- Use 24px gaps for ordinary three- and four-column grids.
- Carry the dark closing surface through the footer, using 40px call-content gaps and a 96px structural rhythm.

### Don't

- Do not make mint the primary button fill; its saturated role is a 2px focus ring or 8px status dot.
- Do not give every card a heavy shadow; ordinary feature panels are flat soft gray.
- Do not put body paragraphs in DM Mono or use the demonstration's editorial fonts for marketing headings.
- Do not replace the 16px action radius with fully pill-shaped buttons.
- Do not spread 13.2px feature descriptions across the full 1200px width; they belong in short columns.
- Do not carry peach, blue-grid glass and the orbit gallery into every page; they belong to different scoped themes.
- Do not frame every integration logo in a tile; the compatibility field is three open rows of marks.
- Do not use a pure-black full-page dark theme; most reading remains white and the dark field is a concluding contrast.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions cover background-color, border-color, color, fill, stroke, opacity, box-shadow and transform, commonly 150ms; navigation links declare cubic-bezier(0, 0, 0.2, 1).
- Declared integration-mark hover scales to 0.92 with a 0.1s ease-in-out transform transition.
- Declared recognition-card hover translates upward by 8px with a 0.15s ease-out transform transition.
- The compatibility field uses horizontal marquee rows; demonstrations and the opening gallery include changing media and carousel controls.

**Transfer:**

- Keep hover motion local: marks contract, recognition cards lift and buttons change neutral tone.
- When using a moving gallery, retain its explicit pause control and preserve the visual hierarchy of one dominant output.

**Unknown:**

- Autoplay durations, scroll-trigger timing and the exact point-field or 3D gallery animation paths are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 768px, 896px, 992px and 1280px; the platform-overview theme also declares 1536px.

**Transfer:**

- Recommended adaptation: stack split copy before the output scene on narrow screens, preserving the dominant central example and clipped neighboring examples.
- Recommended adaptation: make the overlapping deck a horizontally browsable sequence instead of shrinking captions; keep the progression visible.
- Recommended adaptation: reduce feature-grid columns and retain a separate, full-width logo field rather than squeezing all marks into the text container.

**Unknown:**

- Exact mobile typography, gutters, navigation collapse behavior and breakpoint-specific scene arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
