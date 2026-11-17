# Arrakis — fieldwork meets cosmic machinery

## Overview

An editorial, technically charged style for ambitious products that operate beyond the screen. Warm paper and near-black alternate with dusty photographic scenes, ember light and deep blue atmospheric diagrams. Light serif headlines, understated sans-serif explanations and tiny equipment-like labels keep even expansive pages restrained. The density is low, but the imagery and fine instrumentation make the empty space feel purposeful.

### Essentials

- Field footage becomes an instrument panel: the opening is an edge-to-edge photographic scene, 835px tall at desktop, with white 56px/0.98 weight-300 serif copy anchored low on the left and fine dots, measurements and leader lines layered over the subject.
- Editorial type stays delicate rather than monumental: display headings use -0.03em tracking at 56px, section statements use 48px/1.05, and the long reading statement opens to 48px/1.48.
- Actions look like small equipment controls, not consumer-app pills: cream fill, dark text, 15px/18px sans, 9px 14px padding, 38px height and 2px corners.
- Color belongs to worlds, not decoration: warm #fcf9f4 and near-black #1a1714 cover most of the page; orange is concentrated in grainy luminous callout bands and blue in technical diagram stages, never a rainbow of feature cards.
- The atmospheric light band is a signature device: an inset 8px-radius panel has a broad ember cloud, dark vignette and visible fine grain behind a serif statement and a small cream action. Recreate the cloud procedurally when no cinematic artwork is available.
- Fine registration marks tie everything together: 1px dotted rules repeat on a 5px pitch with 3px corner returns, logo reticles use 1.5px strokes, and 12px/12px uppercase labels carry 0.05em tracking. Carry these marks into proof, diagrams and the closing footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm flare | `#e08a3c` | `--color-flare` | accent, background | The brighter core of the atmospheric orange light. |
| Ember cloud | `#c46a2a` | `--color-ember` | accent, background | Orange-brown atmospheric light inside vignetted statement bands, not buttons or body text. |
| Blue horizon | `#7993e2` | `--color-dawn` | accent, background | Blue illumination at the base of technical stages, softened and darkened by the scene layers. |
| Twilight blue | `#15203d` | `--color-twilight` | background, accent | Base blue of the technical stage, confined to diagram-rich regions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control cream | `#fbf6ec` | `--color-cream` | surface, action, text, border | Filled conversion controls and warm light text. |
| Deep space | `#030813` | `--color-space` | background | Technical scenes and diagram backdrops; also a 45% darkening overlay within those scenes. |
| Photographic night | `#1b1613` | `--color-night` | background, surface | Under photographs and luminous callout bands; slightly warmer than the main dark canvas. |
| Warm black | `#1a1714` | `--color-ink` | text, background, border | Primary dark text on paper and full dark sections. |
| Blue-black glass | `#1a1e28` | `--color-glass` | surface | Visible white 9% veil over deep space; actual appearance varies with the blue light beneath. |
| Glass edge | `#42464e` | `--color-glass-edge` | border | Visible white 25% dashed outline over deep space. |
| Dark-field rule | `#54504e` | `--color-rule-dark` | border | Dotted bracket rules on dark sections and footer. |
| Muted dark-field text | `#a3a2a1` | `--color-muted-light` | text | Visible white 60% over warm black for footer metadata; use alpha over variable backgrounds. |
| Proof rule | `#b1aca6` | `--color-rule-mid` | border | Muted dotted framing around statistic cells. |
| Paper rule | `#dfd8d3` | `--color-rule-light` | border | Faint rules around integration details on paper. |
| Warm paper | `#fcf9f4` | `--color-canvas` | background | Default marketing canvas; the long reading and proof areas remain warm rather than pure white. |
| Pale demonstration panel | `#fdfaf6` | `--color-panel` | surface | Subtle differentiation for the wide integration demonstration. |
| Light on dark | `#ffffff` | `--color-white` | text, border | Headlines, navigation and diagram marks on dark imagery. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product detail pages | Chapter ink | `#1b1815` | `--color-chapter-ink` | text | Headings and explanation text on the product chapter paper. |
| product detail pages | Chapter paper | `#fbf8f3` | `--color-chapter-paper` | background | Slightly warmer capability chapter background. |

## Typography

- **terraneSerif** — Promises, editorial statements and capability headings. Light, compact contemporary serif with a large x-height, low visual weight and sharp but understated serifs. If unavailable, use **Instrument Serif**. Use its regular cut with tight tracking; preserve the compact line lengths rather than adding weight. Font stack: "terraneSerif", "Instrument Serif", Georgia, serif.
- **terraneSans** — Body copy, navigation, controls and supporting labels. Plainspoken contemporary sans with open counters, used mainly at light and regular weights. If unavailable, use **Inter**. Use 300 and 400; keep body copy light and uncompressed. Font stack: "terraneSans", "Inter", Arial, sans-serif.
- **pxGrotesk** — Small technical labels, indexes, categories and navigation arrows. Square, mechanical grotesk with the spacing and cadence of instrument notation; not a body-code font. If unavailable, use **Space Grotesk**. Use 400 with 0.05em tracking for labels. Font stack: "pxGrotesk", "Space Grotesk", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | terraneSerif | 300 | 56px | 0.98 | -0.03em | Opening promise in white; also the centered product-detail opening. |
| heading-lg | terraneSerif | 300 | 48px | 1.05 | -0.03em | Centered section promises and dark-stage headings. |
| reading-statement | terraneSerif | 300 | 48px | 1.48 | -0.03em | A long centered statement that reveals its argument phrase by phrase. |
| heading | terraneSerif | 300 | 40px | 1.1 | -0.03em | Left-aligned section titles beside proof or editorial content. |
| heading-sm | terraneSerif | 300 | 32px | 1.15 | -0.03em | Photo-card promises and capability chapter headings. |
| body | terraneSans | 300 | 18px | 1.5 | normal | Hero support and spacious explanatory paragraphs. |
| item-title | terraneSans | 400 | 18px | 1.5 | normal | Short feature and process titles above lighter paragraphs. |
| body-compact | terraneSans | 300 | 16px | 1.5 | 0.01em | Dense capability and process explanations. |
| action | terraneSans | 400 | 15px | 18px | normal | Navigation, footer links and filled conversion controls. |
| eyebrow | pxGrotesk | 400 | 12px | 1 | 0.05em, uppercase | Section labels, metadata, statistic captions and footer group titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product detail pages | product-manifesto | terraneSerif | 300 | 28px | 1.15 | -0.03em | Narrow prose bridge beneath the product illustration. |
| company and culture pages | value-title | terraneSerif | 300 | 24px | 1.2 | -0.03em | Principle titles beside abstract line drawings. |

**Notes:**

- Serif tracking is consistently -0.03em from 24px to 56px. Do not substitute bold geometric sans headlines.
- The main contrast is light serif against regular tiny technical labels; body copy moves between 300 and 400 rather than becoming bold.
- The reading statement is not an ordinary heading: its 1.48 line height and 1024px measure give it an almost spoken cadence.
- Use white lettering over dark photographs and warm-black lettering on paper. Supporting copy is commonly faded to 80%, technical captions to 60%. No viewport-size type formula is established.

## Layout

**Density:** Airy, with compact controls and local text groups separated by long editorial pauses and immersive scenes.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Tight item title-to-description gap. |
| 12px | Technical tile gaps and small internal offsets. |
| 16px | Hero action separation and compact content groups. |
| 24px | Technical tile padding and two-column feature gaps. |
| 32px | Headline-to-hero support gap and proof-cell side padding. |
| 48px | Desktop outer gutter, feature row spacing and common section internals. |
| 64px | Internal dark-stage side padding and larger column separation. |
| 120px | Capability chapter separation and callout-to-footer-links gap. |
| 144px | Large section exit space and technical-stage top padding. |
| 160px | Proof section top and bottom padding and deep chapter exits. |
| 200px | Long dark-page chapter breaks. |

### Containers and grids

- **desktop-container**: max width 1440px · side padding 48px. Centered outer container, yielding a 1344px content field at desktop.
- **hero-copy**: max width 896px. Lower-left headline occupies roughly two thirds of the scene width; support is narrower at 616px.
- **reading-measure**: max width 1024px. Centered prose statement with broad margins and open line height.
- **proof-grid**: max width 888px · 2 columns · gap 0px. Two columns of bracket-framed metrics on the right of a 342px section title; neighboring edges meet.
- **feature-grid**: 2 columns · gap 24px. Paired explanatory text items with 48px row gaps beneath a wide demonstration.
- **technical-grid**: max width 1024px · 3 columns · gap 12px. Two rows of technical glass tiles; one row expands the last column to 1.4 times its neighbors, the next reverses the emphasis.
- **product-chapters** (only for product detail pages): max width 1140px · gap 32px · side padding 24px. A 522px by 420px diagram sits left of a 516px text column, with a narrow sticky chapter index outside the frame.

## Corner radius

| Element | Radius |
| --- | --- |
| controls-and-pale-panels | 2px |
| photo-and-atmosphere-panels | 8px |
| technical-glass-tiles | 12px |
| registration-corners | 3px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default body sections and reading space.

**CSS:** `background: #fcf9f4; color: #1a1714`

**Observed:** A warm uninterrupted field rather than a grid of raised cards.

**Transfer:** Let typography and bracket marks organize the content without adding container fills everywhere.

#### Dark canvas · level 0

**Use:** Closing footer and selected immersive chapters.

**CSS:** `background: #1a1714; color: #ffffff`

**Observed:** Warm almost-black, flat and shadowless.

**Transfer:** Use as a full-width tonal change, not a dark card behind every paragraph.

#### Atmospheric band · level 1

**Use:** Signature promise and conversion statements.

**CSS:** `background: #1b1613; border-radius: 8px; overflow: hidden; position: relative`

**Observed:** An orange, grainy cloud blooms through the center and falls almost to black at the edges. One variant centers its copy in a 440px-tall panel; the footer variant is 272px tall with lower-left text.

**Transfer:** Combine this surface with Ember cloud artwork and a Primary button; match the soft glow rather than relying on exact gradient stops.

#### Technical night stage · level 1

**Use:** Grouped system explanations and diagram scenes.

**CSS:** `background: #030813; color: #ffffff; border-radius: 8px; overflow: hidden; padding: 144px 64px 160px`

**Observed:** Deep navy carries a blue lower horizon, faint grain and a soft warm light leak in the upper-left. The centered heading sits far above the tile grid.

**Transfer:** Keep the scene dark enough for pale line diagrams to feel luminous, not neon.

#### Technical glass · level 2

**Use:** Diagram tiles within the night stage.

**CSS:** `background: rgba(255,255,255,0.09); border: 1px dashed rgba(255,255,255,0.25); border-radius: 12px`

**Observed:** A modest translucent veil, not glossy frosted glass; the horizon passes through all cards as one continuous scene.

**Transfer:** Keep borders fine and dashed; avoid separate heavy glows or shadows on individual tiles.

#### Pale demonstration · level 1

**Use:** Wide integration illustration backed by a subtly different paper tone.

**CSS:** `background: #fdfaf6; border-radius: 2px; overflow: hidden`

**Observed:** A shallow tonal shift supports a broad diagram without suggesting elevation.

**Transfer:** Use for a single detailed product explanation rather than a whole page of pale cards.

## Components

### Navigation

**Use:** Persistent orientation over imagery and editorial sections.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 86px`

**Text style:** `action` — terraneSans 400 · 15px/18px

**Observed:** Brand mark at left, a short horizontal link cluster, conversion control at right. Over the opening it is transparent and wide; after scrolling it contracts into a centered bracket-ended rail, changing text and button polarity with the section.

**Transfer:** Keep the link cluster short and preserve the bracket-ended rail rather than replacing it with a rounded floating capsule.

### Primary button

**Use:** Demo, exploration and recruiting conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #fbf6ec; color: #1a1714; border: 1px solid #fbf6ec; border-radius: 2px; padding: 9px 14px; height: 38px`

**Text style:** `action` — terraneSans 400 · 15px/18px

**Observed:** A small text-only rectangle; no large leading icon or arrow. The light-page navigation uses the inverse dark control.

**Transfer:** Let the text determine width; retain the compact height even beside a large statement.

### Text link

**Use:** Navigation and footer lists.

**CSS:** `display: block; color: #ffffff; font-size: 15px; line-height: 18px`

**Text style:** `action` — terraneSans 400 · 15px/18px

**Observed:** Plain text links in grouped columns, with 20px vertical gaps in the footer. Header links have a subtle active underline.

**Transfer:** Use succinct category labels, not repeated button outlines.

### Field photo card

**Use:** A horizontally scrolling application or story gallery.

**CSS:** `position: relative; display: flex; flex-direction: column; background: #1b1613; border-radius: 8px; overflow: hidden; height: 534px`

**Text style:** `heading-sm` — terraneSerif 300 · 32px/1.15 · tracking -0.03em

**Observed:** A wide selected card is 640px across; narrow neighbors are 288px. Full-bleed documentary imagery sits behind a dark bottom gradient, with category caption, serif outcome and right arrow low in the frame. The selected card adds corner reticles and measurement marks; text inset is 36px.

**Transfer:** Make selection change the emphasis of one photographic story, keeping the rail partly outside the viewport.

### Technical tile

**Use:** Capabilities within the technical night stage.

**CSS:** `position: relative; display: flex; flex-direction: column; padding: 24px; border-radius: 12px; overflow: hidden; min-height: 302px; background: rgba(255,255,255,0.09); border: 1px dashed rgba(255,255,255,0.25)`

**Text style:** `item-title` — terraneSans 400 · 18px/1.5

**Observed:** Tiny numbered technical caption at top, a restrained line illustration through the middle, and a short sans promise low in the tile. Cards vary in width while their height stays aligned.

**Transfer:** Describe one capability per tile; use geometric diagrams rather than mini dashboards.

### Bracket rule

**Use:** Top and bottom boundaries of feature rows, metrics and footer metadata.

**CSS:** `background-image: linear-gradient(90deg, #b1aca6 0px, #b1aca6 1.5px, rgba(0,0,0,0) 1.5px); background-size: 5px 1px; background-repeat: repeat-x; padding: 0px 3px; position: relative`

**Observed:** The dotted horizontal line terminates in short 1px vertical returns with 3px corner radii. Top and bottom pieces are separate; dark scenes use the darker rule tone and pale detail rows the lighter tone.

**Transfer:** Use pseudo-elements for the returns. Leave the rest of the cell edge open rather than drawing a complete box.

### Metric cell

**Use:** Large numerical proof paired with small technical captions.

**CSS:** `padding: 24px 32px; min-height: 144px`

**Text style:** `eyebrow` — pxGrotesk 400 · 12px/1 · tracking 0.05em · uppercase

**Observed:** An unfilled cell between Bracket rules: approximately 56px light serif numerals with smaller suffixes, followed by a 12px uppercase technical caption separated by 10px. Six cells form two columns and three rows beside the left-hand heading.

**Transfer:** Use real substantiated metrics and let numerical values dominate. Preserve smaller units and suffixes rather than enlarging every character.

### Logo reticle

**Use:** Customer or publication proof strips.

**CSS:** `width: 176px; height: 56px; border: 1.5px solid #1a1714; border-radius: 3px; opacity: 0.3; position: absolute`

**Observed:** Only the four short corner fragments remain visible around a centered monochrome logo; each logo sits in an 80px-high allocation.

**Transfer:** Mask the continuous border down to its corners and keep marks subordinate to the logos.

### Footer columns

**Use:** Shared ending after the luminous closing call.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); column-gap: 24px; row-gap: 56px; max-width: 888px`

**Text style:** `action` — terraneSans 400 · 15px/18px

**Observed:** Three left-aligned groups occupy only part of the dark width. Technical uppercase titles sit 40px above plain link lists. A large empty interval precedes the bracket-framed metadata strip, with copyright left, a small symbol centered and a social link right; the privacy sentence sits below.

**Transfer:** Preserve the spacious asymmetric footer rather than adding a giant wordmark or a dense sitemap.

## Imagery and graphics

### Instrumented field photography

**Use:** The default opening and photographic story rail.

**Observed:** Documentary scenes of active equipment, people working and large physical systems. The opening is warm, dusty and low contrast, with the main machine right of center and open darker ground for copy at lower-left. Faint data strings, dashed leaders, tiny target dots and measurement annotations make the image feel sensed rather than merely photographed.

**Transfer:** Choose a real working scene relevant to the new product. For a nonphysical product, photograph people using it in a real environment or use a convincing material still life; retain directional light, warm shadows and one dominant object instead of replacing the scene with a generic dashboard.

**Build:** Use object-fit: cover for the scene, with a warm-black overlay at about 42% and very subtle grain. Add an SVG overlay with short 1px pale dashed leaders, small 2px target dots and sparse technical strings following actual subject edges. Keep most marks low opacity and away from headline letterforms; one or two clusters are enough.

### Ember cloud artwork

**Use:** Signature inset atmospheric statements, including the shared closing call.

**Observed:** A broad, softly turbulent orange-brown light cloud glows against near-black, with a fine stippled texture and dark edges. It fills the whole band behind the text, not a small decorative orb. Its apparent warmth contrasts with the technical blue scenes.

**Transfer:** Recreate this material even without bespoke art: soft layered light and grain are the minimum acceptable version, not a flat orange gradient.

**Build:** On a #1b1613 backing, layer two large elliptical radial gradients centered around 50% 55% and 65% 35%, using #c46a2a and #e08a3c with translucent falloff. Stretch the ellipses horizontally, blur a separate light layer by roughly 60px, then add a dark radial vignette approaching rgba(10,8,6,0.8) at the edges. Overlay fine SVG feTurbulence grain at low opacity. Keep the center cloud broad and irregular; exact stops are not essential.

### Blue horizon diagrams

**Use:** System overview and product capability scenes.

**Observed:** Thin pale isometric planes, stacked layers, connector nodes and simplified document shapes float above a navy-to-periwinkle horizon. Rectangular diagrams often occupy 522px by 420px; the product opening uses a much wider centered exploded stack. This is explanatory line art with depth, not photorealistic 3D.

**Transfer:** Diagram the new product's actual relationships using three to five planes, connectors or modules. The minimum version is clean SVG geometry on a dark blue light field, not a screenshot with tiny unreadable UI.

**Build:** Create a navy rectangular stage with a diffuse #7993e2 radial glow rising from the lower edge. Draw parallelogram planes in SVG with thin white strokes at low alpha, offset vertically to create an exploded stack; use sparse dots and simple card silhouettes on selected planes. Add a soft warm blurred patch near the upper-left and a 7% grain veil.

### Particle bridge

**Use:** A centered problem-to-promise interlude on paper.

**Observed:** Sparse dark particles gather into a broad elevated arch or wave above a centered serif statement, thinning into the warm canvas. Edge ticks suggest the same instrument system as the photographic scenes.

**Transfer:** Use a restrained particle field to visualize a meaningful connection or transition; keep the text area clear.

**Build:** Distribute tiny warm-black SVG circles along a wide arch using a density mask: strongest around the arch crown, sparse toward both edges, and nearly absent behind text. Vary alpha rather than using saturated colors. Add short horizontal edge ticks at widely separated intervals.

### Geometric principle drawings

**Only for:** company and culture pages

**Use:** Values or working principles beside editorial descriptions.

**Observed:** Each 205px by 180px drawing uses faint light lines and corner registration marks: a wave with endpoint dots, nested perspective squares, concentric elliptical rings and overlapping orbital circles. Four drawings repeat down the page beside short serif titles.

**Transfer:** Develop a small coherent set of abstract diagrams for the new organization's principles, keeping the same line density and generous empty interiors.

**Build:** Use SVG with a thin low-alpha white stroke, 3px endpoint dots and four short corner brackets. Construct one motif from a sine path, another from nested rectangles connected at corners, and another from concentric ellipses with one vertical axis. Keep all marks inside a consistent 205px by 180px field.

### Orbital invitation

**Only for:** company and recruiting pages

**Use:** A dedicated centered invitation before the shared footer.

**Observed:** A wide fine ellipse surrounds the headline and button, with dotted arcs above and below and short lateral hairlines terminating in dots. The central artwork is 816px wide; it is airy and almost monochrome.

**Transfer:** Frame a human invitation with a thin orbital construction instead of introducing an unrelated photo or colorful recruiting card.

**Build:** Draw a horizontal SVG ellipse about 816px wide, a second taller dashed ellipse partially hidden behind it, and two horizontal side leaders ending in small dots. Use low-alpha white strokes on the Dark canvas; place the heading and button in HTML over the center.

### Icons

**Observed:** Sparse outline symbols, typically 16px by 16px with 1.5px round strokes for controls. Dark-page feature symbols can be 40px line drawings; shields, arrows and small corner targets reinforce the technical vocabulary.

**Transfer:** Choose a consistent thin outline set; favor diagrams, arrows and registration marks over filled pictograms. Keep icons secondary to the light serif headlines.

## Section recipes

How recurring sections are built.

### First screen: Instrumented scene opening

**Observed:** An edge-to-edge 835px-high working scene fills almost the first 900px; a narrow strip of warm paper appears beneath it. The transparent 86px Navigation floats above. Back-to-front layers are the full-bleed photograph, warm darkening and fine grain, sparse pale instrumentation, then the lower-left text group. The main object occupies the center-right half while the headline spans roughly two thirds of the width, breaking across two compact 56px lines. Its left edge sits slightly inside the 48px container gutter; support is 616px wide with 32px separation, followed 16px later by the small Primary button. Headline, support, action and main object are all visible before the fold; proof and other narrative content begin below.

**Transfer:** Use a single believable scene with a dominant subject and a lower-left quiet zone. Without film-quality media, use carefully lit still photography and the Instrumented field photography overlay. A product-detail page can instead center the same display recipe above a blue exploded diagram; a company page opens with a centered 48px statement on warm black.

**Avoid:** Do not center the default hero over a blue gradient, put copy into a floating white card, enlarge the action into a pill, or cover the image with dense fake telemetry.

**Text style:** `display` — terraneSerif 300 · 56px/0.98 · tracking -0.03em

### Atmospheric statement band

**Observed:** Atmospheric band inset by the desktop 48px gutters; the central version is 440px tall with a centered serif promise, a short support line and Primary button. The same material returns in a shorter lower-left-aligned closing variant.

**Transfer:** Include the grainy luminous band as a signature moment wherever the new narrative needs concentration; use one short promise and one action rather than embedding several feature lists.

**Text style:** `heading-lg` — terraneSerif 300 · 48px/1.05 · tracking -0.03em

### Reading pause

**Observed:** A centered 1024px-wide Reading statement on Paper canvas sits within an extended scroll scene. Its lines gradually move from muted gray to warm black; small vertical progress marks live well outside the text at left.

**Transfer:** Give one important argument room to be read at 48px/1.48. Keep the block static when scroll-linked reveal is unavailable, preserving its typography and measure.

**Text style:** `reading-statement` — terraneSerif 300 · 48px/1.48 · tracking -0.03em

### Photographic story rail

**Observed:** A tiny section label and category-icon controls sit above the Field photo card rail; previous and next arrows sit at the far right. One wide selected photograph and narrower neighbors fill a 534px-high horizontal track with 44px gaps.

**Transfer:** Use applications, outcomes or stories that benefit from documentary imagery. Let the rail imply more content beyond the edge without forcing all cards into equal columns.

**Text style:** `heading-sm` — terraneSerif 300 · 32px/1.15 · tracking -0.03em

### Problem bridge

**Observed:** An uppercase technical eyebrow, centered light serif claim and narrow supporting paragraph sit on Paper canvas. Particle bridge artwork and sparse edge ticks emerge above and around the copy within an expansive reading interval.

**Transfer:** Use this for a tension the product resolves. Treat long scrolling space as an editorial pause, not as an empty content section.

**Text style:** `heading-lg` — terraneSerif 300 · 48px/1.05 · tracking -0.03em

### Technical capability stage

**Observed:** Technical night stage is inset inside the paper canvas. A centered icon, eyebrow and 48px heading occupy the top; a generous 120px gap leads to six Technical tiles in two variable-width rows. The blue horizon unifies all diagrams.

**Transfer:** Explain a small system with relationships rather than presenting a generic feature checklist. Keep diagrams subordinate to short bottom-aligned promises.

**Text style:** `heading-lg` — terraneSerif 300 · 48px/1.05 · tracking -0.03em

### Quantified proof

**Observed:** A 40px heading in a 342px left column faces the 888px two-column metric grid. Metric cells use open bracket boundaries rather than filled cards; section top and bottom padding are 160px.

**Transfer:** Use a few significant metrics with compact technical captions. If numerical proof is unavailable, use similarly framed concrete evidence statements, without invented numbers.

**Text style:** `heading` — terraneSerif 300 · 40px/1.1 · tracking -0.03em

### Demonstration and feature pair

**Observed:** A broad Pale demonstration with 32px serif explanation is followed by a bracket-framed detail area: a large proof value at left and four text features at right, arranged in two columns with 24px column and 48px row gaps. Item titles sit only 4px above 18px light descriptions.

**Transfer:** Pair one meaningful diagram with a few operational details, not a screenshot wall.

**Text style:** `heading-sm` — terraneSerif 300 · 32px/1.15 · tracking -0.03em

### Luminous close and footer

**Observed:** A full-width Dark canvas begins with 48px top padding and the inset 272px Atmospheric band. Its statement and Primary button align lower-left. After 120px, Footer columns group short links under muted technical labels. Below a broad quiet interval, Bracket rules enclose a sparse metadata strip; a small centered privacy sentence is the final element. This closing structure is shared across all three page types.

**Transfer:** Close with an explicit invitation inside the warm light band and then a genuinely useful sparse footer. Preserve the final metadata strip and modest last sentence rather than terminating immediately after the CTA.

### Product chapter rows

**Only for:** product detail pages

**Observed:** A narrow sticky technical chapter index precedes four bracket-framed 1140px rows, separated by 120px. Each row pairs a 522px by 420px blue diagram with a 32px title at the top of a text column and compact support near its base. The chapter system transitions from dark to paper as the narrative progresses.

**Transfer:** Give each product capability a distinct diagram and a concrete explanation. End the chapters with a centered 48px assurance heading, a small shield and a compact horizontally divided proof strip before the shared footer.

**Text style:** `heading-sm` — terraneSerif 300 · 32px/1.15 · tracking -0.03em

### Dark editorial company chapters

**Only for:** company and culture pages

**Observed:** Dark canvas runs continuously from the centered 48px opening through a bracketed scrolling problem list, a four-column icon-and-text argument, numbered process rows beside a blue deployment diagram, and a principles list with Geometric principle drawings. Section breaks commonly use 160px or 200px.

**Transfer:** Organize a company narrative around problems, methods and principles; keep its darker, more diagrammatic look scoped to editorial company content.

**Text style:** `heading` — terraneSerif 300 · 40px/1.1 · tracking -0.03em

### Orbital invitation

**Only for:** company and recruiting pages

**Observed:** Orbital invitation artwork frames a centered 48px headline, tiny bracketed category label and Primary button. A narrow low-contrast advisory line sits 56px below the central group, followed by a deep exit into the shared footer.

**Transfer:** Use for a purposeful invitation with a practical note beneath it; keep this ceremonial ellipse distinct from ordinary conversion bands.

**Text style:** `heading-lg` — terraneSerif 300 · 48px/1.05 · tracking -0.03em

## Page flow

**Storyline:** Immersive promise → editorial argument → concrete applications or system explanation → operational proof → reassurance → luminous invitation and sparse footer.

### Broad marketing landing page that connects an ambitious promise to real working contexts

1. **Promise** — Instrumented photographic opening with one small conversion action.
2. **Positioning** — Reticle-framed proof strip, luminous statement band and spacious reading argument.
3. **Application proof** — Expanding photographic story rail.
4. **Problem and mechanism** — Particle-backed editorial tension followed by a blue technical capability stage.
5. **Quantified and operational proof** — Bracketed metric grid, wide integration diagram and compact feature details.
6. **Social proof and closing call** — Publication strip followed by the shared luminous close, footer columns and metadata.

**Transfer:** Use the same alternation of physical credibility, editorial breathing room and technical explanation without preserving the exact number or order of sections.

### Product detail page explaining a system through a few clear capability chapters

1. **Product promise** — Centered display headline over a broad exploded blue diagram.
2. **Positioning** — Narrow 28px serif paragraphs between faint edge ticks.
3. **Capability chapters** — Sticky chapter index beside large diagram-and-copy rows transitioning from dark to light.
4. **Reassurance** — Centered assurance headline above a divided certification and information strip.
5. **Closing call** — Shared ember band and dark footer.

**Transfer:** Let the diagram and chapter navigation carry the argument; replace certification examples with the new product's genuine trust evidence.

### Company narrative and invitation built around a worldview and working method

1. **Tension** — Centered dark opening followed by a bracketed problem scroller.
2. **Approach** — Two-tone editorial heading over four technical icon columns.
3. **Method** — Numbered process rows paired with a blue diagram.
4. **Principles** — Left statement and repeated geometric principle drawings with text.
5. **Invitation** — Centered orbital call with a concise practical note.
6. **Closing call** — Shared luminous conversion band and sparse dark footer.

**Transfer:** Adapt the rhythm to the organization's real beliefs and methods; preserve the dark editorial variant and abstract diagram language.

## Writing

Assured, operational and ambitious without conversational cheerleading. Large claims are grounded by concrete systems, constraints, actions and outcomes rather than lifestyle language.

**Do not copy:** Do not reuse Arrakis names, logos, proprietary artwork, customer and publication marks, numerical claims, certification claims or source sentences as the new product's own assets or promises. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the team doing the work and your for the reader's people, systems and outcomes. Product statements may be impersonal; avoid an overly familiar second-person monologue.
- **Rhythm:** Headlines are compact assertions or purposeful contrasts, usually 4–10 words. Body lines are one or two concrete sentences; fragments in threes give selected statements cadence. No exclamation marks are needed.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A new category or transformed world, stated directly. | 5–14 words | “This is the industrial world, reengineered for the frontier”<br>“The AI OS for real-world operations” |
| Section contrast | State what the product is for, then reject the weaker alternative. | 4–10 words | “Designed for execution, not experimentation”<br>“Built to expand your people, not replace them.” |
| Capability title | Verb plus the concrete system or work being improved. | 3–8 words | “Consolidate your existing systems”<br>“Build a living knowledge graph” |
| Supporting line | Name the work, the inputs and the practical implication. | 15–35 words | “Integrate ERPs, CRMs, data warehouses, and operational tools into one unified layer.”<br>“Model-agnostic. Deployable anywhere. Built backwards from your outcomes.” |
| Primary action | Short direct invitation naming the next step. | 3–4 words | “Request a demo”<br>“Join our team” |

**Words and phrasing to use:** built for; real-world; workflows; control; outcomes; your teams; connect; execute; deploy; end-to-end

**Avoid:** magical; game-changing; supercharge everything; effortless revolution; friendly robot banter; vague intelligence claims

**Rules:**

- Make the contrast between aspiration and operational reality explicit.
- Use concrete inputs, work and consequences in support copy.
- Put one promise in each heading and one mechanism in its paragraph.
- Use compact technical nouns for labels, not whole sentences.
- Qualify trust, performance and speed statements with genuine support.

## Do's and Don'ts

### Do

- Keep display type at weight 300 and -0.03em tracking, with 56px/0.98 for the default opening.
- Pair the 18px/1.5 light body recipe with 12px/1 uppercase technical labels.
- Keep desktop content within 1440px with 48px side gutters.
- Use 38px-high cream controls with 2px corners and 9px 14px padding.
- Carry dotted 5px-pitch bracket rules into proof and closing metadata.
- Use 8px corners for photographic and luminous panels, reserving 12px for technical glass tiles.
- Give major proof sections 160px top and bottom space and capability chapters 120px separation.
- Keep blue illumination inside dark technical scenes and orange glow inside atmospheric statement bands.

### Don't

- Do not make serif headings bold or increase tracking toward zero; the delicate compact cut is essential.
- Do not apply the 1.48 reading-statement line height to the compact two-line hero.
- Do not turn the 2px conversion rectangles into rounded pills or oversized app-store buttons.
- Do not replace the warm #fcf9f4 body with stark white or cool gray.
- Do not make each technical tile a different saturated color; the blue horizon is one shared environment.
- Do not give the metric grid solid full-box borders, tinted fills or drop shadows.
- Do not draw continuous heavy boxes around logos; only low-opacity corner reticles should remain.
- Do not fill the footer's unused right-hand space with extra cards, a newsletter form or a huge brand wordmark.

## Motion and responsive

### Motion

**Observed:**

- Declared: the navigation rail changes margin, padding, height, max-width and border-radius over 0.5s with cubic-bezier(0.22,1,0.36,1).
- Declared: photo-card width transitions over 0.7s with cubic-bezier(0.22,1,0.36,1).
- Declared: technical-tile veils transition opacity over 0.5s with cubic-bezier(.4,0,.2,1).
- Declared: reticle-lock runs for 1.1s with cubic-bezier(0.22,1,0.36,1); atmospheric layers use 50s and 70s ease-in-out alternate cycles, with a 26s star-twinkle cycle.
- Seen: reading statements progressively darken and metrics settle to their final values as the page advances.

**Transfer:**

- Keep the long atmospheric drift subordinate to legibility and the measured card expansion separate from fine icon movement.
- Use scroll emphasis on a small number of editorial passages; show the completed statement and final proof values when motion is disabled.

**Unknown:**

- Exact scroll trigger thresholds, intermediate keyframe transforms and reduced-motion implementation are not established.

### Responsive

**Observed:**

- Desktop composition is established at 1440px by 900px. Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1440px among others.
- Layout declarations switch chapter rows from column to row, detail features to two columns, and the technical grid toward a stacked arrangement at narrower widths.

**Transfer:**

- On narrow screens preserve the photographic subject and readable dark copy area; reduce the headline measure rather than overlaying it on the subject.
- Stack technical chapters with diagram before explanation, retain the 12px technical-label cadence, and keep field stories in a horizontal rail.
- Collapse the metric and footer grids without losing their open bracket framing; keep controls rectangular.

**Unknown:**

- Exact mobile type sizes, gutter values, header menu behavior and mobile art direction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
