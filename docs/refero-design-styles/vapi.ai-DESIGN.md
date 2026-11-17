# Vapi — forest speed, machine markings

## Overview

A predominantly light technical style with a fast, atmospheric forest-green opening and crisp black interludes. Tightly fitted geometric sans headlines sit beside small squared technical labels, while cinematic photography and tinted interface scenes give the engineering a physical presence. It suits developer products and infrastructure businesses that want to feel capable, direct, and human without becoming visually dense.

### Essentials

- Headlines feel compressed but not heavy: avantt at 80px/1.02, weight 600 and -0.05em tracking opens the page; section heads settle to 40px/1 at weight 500.
- The opening is a landscape, not a dashboard billboard: a 620px full-width motion-blurred green field carries a left-aligned two-line promise, a 508px support line and compact paired actions, leaving the right half atmospheric.
- Actions are small rounded rectangles rather than universal pills: default height 40px, radius 12px, 16px horizontal padding, white primary and black secondary. Larger product-page actions use 50px height.
- Color lives in bounded events: most reading sections are #fefefe or #fbfbfb with black text; forest imagery, black technical bands and a 90px #62f6b5 action strip punctuate the neutral majority. Include the bright action-strip device and an atmospheric field on a new landing page.
- Technical markings temper the organic imagery: foundryGridnik uppercase section labels at 14px/1 with 1.1px tracking, fine sage-gray rules, and square 72px logo cells in a horizontally moving black band. Use a labeled ecosystem or workflow rail when there are no partner marks.
- Proof is staged at two scales: large tinted interface scenes around 662×443px support short feature copy, while the closing proof rail uses 40px numbers, 16px captions and vertical 1px separators. A new page needs both a tangible product scene and a compact numerical proof treatment; use a simplified real workflow and verified operational measures when equivalent media is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal mint | `#62f6b5` | `--color-mint` | background, accent | The narrow high-contrast action strip, not ordinary reading sections. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Technical green | `#00cd8f` | `--color-green` | text, accent, action | Footer category markings, checks, active pricing controls and calculator conversion action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action | Text on imagery, primary actions on dark fields, and white cards. |
| Near-white canvas | `#fefefe` | `--color-canvas` | background, surface | Default long-form marketing sections. |
| Proof white | `#fbfbfb` | `--color-proof-canvas` | background | Subtle secondary canvas for quotations and editorial proof. |
| Soft white | `#fafafa` | `--color-button-text` | text | Text on black secondary buttons. |
| Sage edge on white | `#bbc7c5` | `--color-rule-light` | border | Visible result of rgba(120,144,140,0.5) over near-white in stat dividers and list rules. |
| Sage edge on black | `#3c4846` | `--color-rule-dark` | border | Visible result of rgba(120,144,140,0.5) over black in ecosystem cells. |
| Photo charcoal | `#2a2a2a` | `--color-photo-backing` | surface | Backing beneath photographic proof banners. |
| Soft black | `#111013` | `--color-soft-ink` | text, background | Quotation text and the dark plan-comparison band. |
| Black | `#000000` | `--color-ink` | text, background, action | Primary text, technical bands, footer and dark actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| culture pages and detailed product tours | Warm paper | `#f2f0ed` | `--color-warm-canvas` | background | Warm extended reading canvas with white cards. |
| story collections | Story slate | `#3f3f46` | `--color-story-backing` | surface | Backing underneath editorial photography. |
| pricing pages | Selected plan wash | `#e9f4ee` | `--color-selected-plan` | surface | Pale green selected calculator option. |
| developer demonstrations | Code night | `#0e0e13` | `--color-code-canvas` | background | Code demonstration interior. |
| developer demonstrations | Code edge | `#27272a` | `--color-code-edge` | border | Nested code frame edges. |
| detailed product tours | Warm reversed text | `#fffaea` | `--color-cream` | text | Text on the warm product-hero artwork. |
| process diagrams | Process sage | `#9acdbf` | `--color-process-sage` | surface | First bar of the staggered process diagram. |
| process diagrams | Process rust | `#b15828` | `--color-process-rust` | surface | Second bar of the staggered process diagram. |
| process diagrams | Process ochre | `#be9d45` | `--color-process-gold` | surface | Later bar of the staggered process diagram. |

## Typography

- **avantt** — All marketing headlines, paragraphs and actions. Geometric sans with circular bowls, a high x-height and unusually tight display fitting. If unavailable, use **Inter**. Use weights 400–600 and retain the negative tracking; check line breaks carefully. Font stack: "avantt", "Inter", Arial, sans-serif.
- **foundryGridnik** — Section markings, category tags, footer headings and pricing figures. Squared, machine-like technical lettering with distinctive engineered corners. If unavailable, use **Chakra Petch**. Use 400–500; keep labels short and widely tracked. Font stack: "foundryGridnik", "Chakra Petch", ui-monospace, monospace.
- **Geist Mono** (only for developer demonstrations) — Readable code samples. Even-width contemporary coding face. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | avantt | 600 | 80px | 1.02 | -0.05em | Default landing-page promise, usually broken into two short lines. |
| strip-action | avantt | 500 | 48px | 1 | -0.04em | Oversized underlined destination on the action strip. |
| section-heading | avantt | 500 | 40px | 1 | -0.058em | Major section headings, centered or left aligned according to composition. |
| feature-heading | avantt | 500 | 40px | 1 | -0.04em | Alternating feature titles and large proof numbers. |
| strip-title | avantt | 500 | 26px | 1 | -0.02em | Short invitation on the bright action strip. |
| quote | avantt | 400 | 20px | 1.3 | normal | Prominent customer quotation; emphasize only selected phrases at weight 600. |
| hero-support | avantt | 400 | 18px | 1.4 | normal | Short support beneath the main promise. |
| body | avantt | 400 | 16px | 1.3 | normal | Section introduction paragraphs. |
| stat-caption | avantt | 400 | 16px | 1.2 | normal | Metric captions and compact editorial support. |
| action | avantt | 500 | 15px | 1.429 | normal | Navigation labels and default conversion buttons. |
| feature-body | avantt | 400 | 14px | 1.3 | normal | Compact explanation beside a large product scene. |
| eyebrow | foundryGridnik | 500 | 14px | 1 | 0.0786em, uppercase | Section category directly above the headline. |
| rail-heading | foundryGridnik | 500 | 12px | 1 | 0.1em, uppercase | Footer categories and small technical rail labels. |
| footer-link | avantt | 400 | 12px | 1.2 | normal | Compact footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| story collections | collection-display | avantt | 500 | 80px | 0.9 | -0.05em | Centered editorial title above logos and filters. |
| culture-page endings | culture-closing | avantt | 500 | 80px | 1 | -0.05em | Monumental centered question over the green field without buttons. |
| detailed product-tour endings | product-closing | avantt | 600 | 80px | 1 | -0.05em | Centered short conversion imperative over the green field. |
| culture, pricing and detailed product openings | secondary-display | avantt | 500 | 58px | 0.9 | -0.05em | More restrained introductory headline than the default landing display. |
| pricing and story-collection closing calls | closing-heading | avantt | 500 | 58px | 1 | -0.05em | Left-aligned promise over the green atmospheric field. |
| story collections | story-heading | avantt | 500 | 40px | 1 | -0.05em | White headline placed over photography. |
| pricing pages | plan-price | foundryGridnik | 500 | 40px | 0.77 | -0.04em | Plan price or custom-pricing word. |
| culture pages | culture-card-heading | avantt | 500 | 36px | 1 | -0.04em | Bottom-weighted card titles. |
| pricing pages | question | avantt | 600 | 20px | 1.2 | normal | Accordion question title. |
| developer demonstrations | code | Geist Mono | 400 | 14px | 1.57 | normal | Code block text and line numbers. |
| story collections | story-tag | foundryGridnik | 400 | 10px | 1 | 0.1em, uppercase | Tiny category pills and read-more labels. |

**Notes:**

- Display tracking is -0.05em; ordinary feature headlines and stat values relax to -0.04em. The 40px major section-heading recipe is tighter still at -2.3px.
- Use the sans for large operational statistics, but the squared technical family for monetary prices. Do not merge these numeral treatments.
- A section label is small and widely spaced, never a second bold headline. Headline weight is usually 500; reserve 600 for the main landing promise and strong product closing imperative.

## Layout

**Density:** Airy section composition with compact controls and compact explanatory paragraphs; much of the breathing room belongs around media rather than inside text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small icon, label and stacked-detail gaps. |
| 10px | Metric-to-caption gap and calculator option spacing. |
| 12px | Gap between paired hero actions. |
| 16px | Eyebrow-to-heading and heading-to-support gaps; default control side padding. |
| 24px | Hero group spacing, collection gutters and compact card padding. |
| 32px | Editorial card insets and internal plan spacing. |
| 40px | Stat-cell padding, culture-card insets and secondary group gaps. |
| 48px | Feature-grid gutters and separation before larger action groups. |
| 72px | Desktop outer shell inset and large proof-card padding. |
| 80px | Footer vertical padding and editorial section spacing. |
| 96px | Major marketing-section vertical padding. |
| 112px | Atmospheric closing-band vertical padding. |

### Containers and grids

- **reading-container**: max width 1152px · side padding 0px. Centered primary text and proof width at desktop; at 1440px the reading edges sit 144px from either side.
- **wide-shell**: max width 1296px · side padding 72px. Wider media and diagram shell. Nested reading content may add another inset; keep the resulting 1152px readable width rather than blindly adding padding twice.
- **feature-split**: 2 columns · gap 48px. A roughly 400px copy column paired with a 662px media scene, alternating sides.
- **proof-grid** (only for story collections): 2 columns · gap 24px. Two visible 564px-wide story columns; tall stories share space with two stacked short stories.
- **culture-grid** (only for culture pages): 3 columns · gap 16px. White rectangular cards against warm paper.
- **plan-grid** (only for pricing pages): 4 columns · gap 20px. Four equal 273px comparison cards within the reading container.
- **calculator-split** (only for pricing pages): 2 columns · gap 24px. A 760px configuration column beside a 368px summary and contact column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | default-actions-and-media | 12px |
|  | small-header-action | 4px |
| pricing pages | calculator-fields | 6px |
| pricing pages | plan-cards | 8px |
| story tags, culture filters and process diagrams | tags-and-process-bars | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Reading canvas · level 0

**Use:** Default long reading stretches.

**CSS:** `background: #fefefe; color: #000000`

**Observed:** Flat and nearly white; no global card shadow.

**Transfer:** Let typography and media provide contrast instead of raising every block.

#### Proof canvas · level 0

**Use:** Editorial quotations and proof sections.

**CSS:** `background: #fbfbfb; color: #111013`

#### Black band · level 0

**Use:** Ecosystem rail and footer.

**CSS:** `background: #000000; color: #ffffff`

#### Bright action band · level 0

**Use:** A brief invitation interrupting the reading flow.

**CSS:** `background: #62f6b5; border-top: 1px solid rgba(0,0,0,0.1); border-bottom: 1px solid rgba(0,0,0,0.1)`

#### Media glass · level 1

**Use:** Controls over atmospheric imagery.

**CSS:** `background: rgba(0,0,0,0.3); border-radius: 12px; backdrop-filter: blur(40px)`

**Observed:** The selector side receives a separate 10% white fill; the action side stays darker.

#### Warm reading canvas · level 0

**Only for:** culture pages and detailed product tours

**Use:** Extended illustrated explanations or company stories.

**CSS:** `background: #f2f0ed; color: #000000`

**Observed:** Faint vertical guide rules can continue along the wide shell.

#### White culture card · level 1

**Only for:** culture pages

**Use:** Values and benefits.

**CSS:** `background: #ffffff; padding: 40px`

**Observed:** Square corners, small outline icon near the upper left, text weighted toward the bottom.

#### Selected calculator option · level 1

**Only for:** pricing pages

**Use:** Selected configuration package.

**CSS:** `background: #e9f4ee; border: 1px solid rgba(0,205,143,0.5); border-radius: 6px; padding: 14px`

#### Code frame · level 1

**Only for:** developer demonstrations

**Use:** Large tabbed code sample inside a black section.

**CSS:** `background: #0e0e13; border: 1px solid #27272a; padding: 8px`

**Observed:** Nested outlines frame tabs, scrollable code and resource links rather than a floating shadow.

## Components

### Primary button

**Use:** Default conversion on a dark or photographic field.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #000000; height: 40px; padding: 0px 16px; border-radius: 12px`

**Text style:** `action` — avantt 500 · 15px/1.429

**Observed:** Pairs with Secondary button. The header version has a 4px corner; detailed product-tour actions grow to 50px with 24px side padding.

**States:** Declared: active scale 1 1.

### Secondary button

**Use:** Sales or documentation beside the primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #000000; color: #fafafa; border: 1px solid rgba(255,255,255,0.15); height: 40px; padding: 0px 16px; border-radius: 12px`

**Text style:** `action` — avantt 500 · 15px/1.429

**Observed:** The dark fill remains dark even on the green atmospheric hero; it is not a transparent outline button.

**States:** Declared: active scale 1 1.

### Navigation

**Use:** Persistent top-level wayfinding.

**CSS:** `padding: 16px 72px; height: 72px; backdrop-filter: blur(40px); background: rgba(96,96,96,0.153)`

**Text style:** `action` — avantt 500 · 15px/1.429

**Observed:** Wordmark at left, compact central links with small downward chevrons for menus, login and start action at right. The resting header reads white; over scrolled media it becomes visibly translucent. A separate 40px atmospheric announcement strip can sit above it.

**Transfer:** Preserve the horizontal compactness and restrained chevrons; adapt menu count to actual information architecture.

### Ecosystem cell

**Use:** Repeated compatibility or workflow marks in the black technical rail.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 72px; height: 72px; border: 1px solid rgba(120,144,140,0.5)`

**Observed:** Square cells hold centered 40px marks. Two rows move horizontally with 16px gaps and black fade masks at their edges.

**Transfer:** Use real integration marks or simple symbolic workflow icons, not empty squares.

### Stat cell

**Use:** Compact quantified proof rail.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 40px; gap: 10px; border-right: 1px solid rgba(120,144,140,0.5); text-align: center`

**Text style:** `feature-heading` — avantt 500 · 40px/1 · tracking -0.04em

**Observed:** Five equal cells occupy the wider shell; the last has no separator. Each pairs a sans number with stat-caption and no enclosing card.

**Transfer:** Choose a small set of verified measures; keep units attached to the number.

### Footer column

**Use:** Small navigation clusters in the black ending.

**CSS:** `display: flex; flex-direction: column; gap: 16px; color: #ffffff`

**Text style:** `footer-link` — avantt 400 · 12px/1.2

**Observed:** Green rail-heading above compact white links. Two columns sit at the right, balanced by a large white wordmark at left and a small community or event invitation near the center; legal text and social icons form a lower baseline.

### Proof banner card

**Use:** Paired photographic case-study teasers.

**CSS:** `position: relative; display: flex; flex-direction: column; gap: 24px; overflow: hidden; background: #2a2a2a; padding: 72px; height: 400px`

**Text style:** `stat-caption` — avantt 400 · 16px/1.2

**Observed:** Two 575px-wide photographic panels nearly touch with a 2px seam. White customer mark, concise operational result, glass action and small technical category label sit over a dark overlay.

**Transfer:** Keep one strong outcome per panel and preserve the photographic backdrop.

### Demo selector

**Only for:** interactive product trials

**Use:** Try a realistic scenario directly in the opening.

**CSS:** `display: flex; align-items: center; justify-content: space-between; background: rgba(255,255,255,0.1); color: #ffffff; height: 50px; padding: 16px`

**Text style:** `hero-support` — avantt 400 · 18px/1.4

**Observed:** A wide selector and narrower play action share Media glass, with a small permission note centered beneath. Selector width is 394px inside a 522px bar.

**States:** Declared: hover background-color color-mix(in oklab, #fff 16%, transparent).

**Transfer:** Use a scenario selector only when the product has a genuine trial; otherwise provide a compact working-example control in the same visual space.

### Story card

**Only for:** story collections

**Use:** Large clickable editorial proof.

**CSS:** `position: relative; display: flex; flex-direction: column; overflow: hidden; background: #3f3f46; border-radius: 12px; padding: 32px`

**Text style:** `story-heading` — avantt 500 · 40px/1 · tracking -0.05em

**Observed:** Edge-to-edge photograph, dark overlay, white logo at top, outcome headline and support near the bottom. Tall and short cards mix; category tags and a glass read-more pill share the final line.

**Transfer:** Use contextual customer photography with a clear outcome, not an abstract stock-tech graphic.

### Story tag

**Only for:** story collections

**Use:** Small categorical metadata on photography.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #111013; border-radius: 9999px; padding: 6px 12px`

**Text style:** `story-tag` — foundryGridnik 400 · 10px/1 · tracking 0.1em · uppercase

**Observed:** White category pills contrast with the neighboring translucent black read-more pill.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side package comparison in a dark band.

**CSS:** `display: flex; flex-direction: column; gap: 32px; padding: 24px 16px; border: 1px solid rgba(255,255,255,0.25); border-radius: 8px`

**Text style:** `feature-heading` — avantt 500 · 40px/1 · tracking -0.04em

**Observed:** Title, short qualification, squared price, supporting billing line, full-width action and checkmarked feature list. Cards share a baseline; the action uses a flatter 4px radius and 50px height.

### Question row

**Only for:** pricing pages

**Use:** Objection handling beneath comparison and logos.

**CSS:** `padding: 14px; border-bottom: 1px solid rgba(17,16,19,0.2)`

**Text style:** `question` — avantt 600 · 20px/1.2

**Observed:** Full-width question with a thin plus at the right. Rows are separated by 20px; expanded content belongs below the question, not in a popover.

## Imagery and graphics

### Forest speed field

**Use:** Signature full-bleed opening atmosphere and smaller atmospheric closing bands.

**Observed:** Dark emerald foliage streaks diagonally across the whole width, with soft yellow-green highlights and almost-black pockets. It reads as a fast pan through a forest, not a green gradient or isolated 3D object. White copy sits over the darkest left region.

**Transfer:** Create a motion-blurred organic photograph or an abstract directional field with the same dark-to-luminous depth. Keep the atmosphere even when the product has no natural imagery; do not replace it with a generic dashboard hero.

**Build:** Start with a nearly black green backing. Layer several oversized SVG paths or elongated ellipses at roughly 10–20 degrees downward to the right, in rgba(17,95,57,0.7), rgba(72,130,62,0.5) and rgba(154,185,87,0.35). Apply directional blur using an SVG filter or repeated horizontally offset paths, then a soft 12px Gaussian blur. Vary streak width and leave large dark gaps. Finish with a black overlay at 0.3 and a vertical black gradient from 0.15 to 0.45; keep the text region darker than the right half. A blurred foliage photograph is the minimum acceptable substitute.

### Tinted product scenes

**Use:** Large alternating feature illustrations on the light canvas.

**Observed:** Real interface panels are embedded in rounded landscape frames around 662×443px. One has warm red-orange translucent lighting, the other muted green-gray glass and dark teal panels; charts and cards remain recognizable while soft material layers and partial edge occlusion add depth.

**Transfer:** Show a genuine product task in a simple panel with a restrained tinted photographic or glass backing. If no interface exists, draw a truthful workflow diagram and place it in the same landscape frame.

**Build:** Clip a product image to a 12px rounded landscape frame. Put a dark backing beneath it, a low-opacity warm-red or sage translucent sheet above it, and one oversized blurred highlight near an outer edge. Retain readable panel hierarchy; avoid piling decorative fake widgets over the task.

### Contextual proof photography

**Use:** Editorial stories, paired proof banners and testimonial video.

**Observed:** Doorway hardware, urban driving, people using phones, offices and working environments are tightly framed. Photography fills the card, darkened enough for white logos and headlines; testimonial video keeps a more natural green-gray grade.

**Transfer:** Choose believable people and environments tied to the outcome. Put subjects off the text region and use a dark overlay rather than text shadows.

### Team documentary strip

**Only for:** culture pages

**Use:** Human context around values and openings.

**Observed:** A wide 1296×600px team photograph opens the human story. Later, a full-bleed horizontal strip mixes landscape and portrait frames at 400px height, including talks and outdoor gatherings. Images are natural-color, rectangular and largely unadorned.

**Transfer:** Use real team activity, not cutout headshots or a uniform avatar grid.

### Warm refracted horizon

**Only for:** detailed product-tour openings

**Use:** Centered alternative to the green landing opening.

**Observed:** Broad horizontal red, orange, ochre and wine bands fill a 710px hero. A 1296×566px inset translucent slab subtly bends the bands at its upper corners; thin vertical guides define the shell. Cream centered copy floats over the warmer field.

**Transfer:** Use soft horizontal color bands behind a single inset refractive sheet, with the center quiet enough for two-line text.

**Build:** Stack broad blurred SVG rectangles in warm red, ochre and dark wine across a full-width field. Add an inset translucent rectangle 72px from the desktop edges, a 5% black fill, and an inset 80px shadow at 10% black. Use a mild displacement filter on the background only, concentrated near the upper corners. Keep exact gradient stops secondary to the soft horizontal refraction.

### Staggered process bars

**Only for:** process explanations

**Use:** A compact transition from explanation to implementation.

**Observed:** Four pill bars descend through a fine orthogonal guide grid. Sage, rust, ochre and black bars carry one action each, with short plain text below. Bars are 56px high and around 324–350px wide; the final two align on the lower row.

**Transfer:** Map an actual process into short action phrases. Preserve the stagger and the contrast between organic pills and rigid rules.

**Build:** Draw a four-column SVG or CSS grid with 1px rgba(0,0,0,0.1) horizontal and vertical guides. Place 56px-high fully rounded bars in #9acdbf, #b15828, #be9d45 and #000000, progressing downward in roughly 56px increments; set 16px side insets and attach a short caption 8px beneath each. On narrow layouts turn the same bars into a vertical sequence.

### Icons

**Observed:** Small monochrome outline symbols, usually 16–24px, with roughly 1.5px strokes; tiny chevrons use a finer 1.3px stroke. Feature icons sit above or beside text; pricing uses 16px rounded checkmarks in green. Play and social marks are solid.

**Transfer:** Choose restrained outline symbols with consistent stroke weight. Reserve filled shapes for playback, partner marks and social identities.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric landing opening

**Observed:** A 40px announcement strip and 72px white-reading Navigation precede a 620px full-width Forest speed field. The copy occupies the left portion of a 1296px shell, inset to about the reading edge, with a two-line display at 80px/1.02 and a compact 508px-wide support line. The right half remains imagery. From back to front: forest image, black tonal overlays, left text stack, Primary button and Secondary button with a 12px gap, then the compact trial bar. The first 900px includes the whole opening and the beginning of a light quotation-and-logo proof section; large product illustrations begin below it.

**Transfer:** Use a short product-and-audience promise with the same left-weighted composition and directional field. A real trial can occupy the compact control line; otherwise show a small actionable working example. Culture openings use a centered 58px headline on warm paper followed by a wide team image; story collections use an 80px centered title, support and monochrome logo rail; pricing opens left aligned with a 58px title above its calculator; detailed product tours center 58px cream text over Warm refracted horizon.

**Avoid:** Do not center the default opening, fill the right half with feature cards, or turn the atmospheric field into a bright flat mint fill. Do not stretch the compact actions into giant pills.

**Text style:** `display` — avantt 600 · 80px/1.02 · tracking -0.05em

### Centered heading group

**Observed:** Eyebrow, section-heading and body are stacked with 16px gaps in a roughly 508px-wide centered group, normally with 96px section breathing room.

**Transfer:** Use one category, one concise claim and one explanatory sentence; switch to left alignment when introducing an adjacent grid.

**Text style:** `section-heading` — avantt 500 · 40px/1 · tracking -0.058em

### Alternating product chapter

**Observed:** A small outline icon sits over feature-heading and feature-body in a roughly 400px copy column. Tinted product scenes occupy the wider side; the next chapter reverses sides. Each image is around 662×443px with large white intervals.

**Transfer:** Alternate real tasks and their benefits without repeating an identical card grid.

**Text style:** `feature-heading` — avantt 500 · 40px/1 · tracking -0.04em

### Bright direct-action strip

**Observed:** Bright action band is 90px high on desktop, with strip-title on the left and a much larger underlined strip-action on the right, vertically centered in the reading width.

**Transfer:** Make a short direct invitation and a prominent destination: a live example, calculator, trial or contact route. Preserve the oversized underlined action rather than adding a conventional card.

**Text style:** `strip-action` — avantt 500 · 48px/1 · tracking -0.04em

### Technical ecosystem band

**Observed:** Black band holds a left-aligned technical label, 40px heading and compact outlined text link. To the right, two rows of Ecosystem cell move behind dark edge masks; the band is about 320px high with 80px vertical space.

**Transfer:** Show compatibility, inputs or workflow steps with authentic marks or simple symbols.

### Capability matrix

**Observed:** A left introductory heading group faces two columns of small icon-led capabilities with 48px horizontal gaps. Item names are 16px semibold; explanations are 15px with about 21.4px line height. The light band has 96px vertical padding.

**Transfer:** Use concise technical assurances or capabilities, with the most explanatory text in the smaller right-hand columns.

### Editorial proof block

**Observed:** Proof canvas pairs a customer quotation and small attribution on the left with a 677×437px rounded video on the right. Nearby Proof banner card pairs provide shorter outcome-led routes to deeper stories.

**Transfer:** Combine first-person proof with contextual moving or still imagery; do not let the quotation become a giant decorative pull quote.

### Closing metrics and footer

**Observed:** A centered 40px line precedes a five-cell Stat cell rail on Reading canvas with 96px vertical padding and a 72px group gap. It ends directly in a black 372px footer with 80px vertical padding, left wordmark, central community invitation, right Footer column groups and a low legal/social baseline.

**Transfer:** Use this as the default proof-led ending; keep a substantive compact footer rather than adding an oversized logo sculpture.

### Atmospheric closing call

**Only for:** culture, pricing, story collections and detailed product tours

**Observed:** The Forest speed field returns as a 346–402px closing band before the same black footer. Pricing and story collections use a left-aligned 58px line with 40px actions and 24px gap below. The product-tour variant centers an 80px semibold imperative with larger actions and a 48px gap. Culture uses an 80px medium two-line centered question, without buttons.

**Transfer:** Choose the closing treatment according to the page's purpose; preserve the green landscape and clear contrast with the following black footer.

### Warm tour with active index

**Only for:** detailed product tours

**Observed:** Warm reading canvas supports a left capability index and a much wider right scene. The active index row is black while inactive rows are muted. Each right chapter places a 24px explanation above a large roughly 770×580px interface illustration and a small uppercase underlined guide link aligned to the far edge.

**Transfer:** Use a persistent chapter index for a genuinely deep product tour, not for an ordinary short landing page.

### Culture and opportunity section

**Only for:** culture pages

**Observed:** Warm reading canvas alternates square White culture card grids and documentary photography. Values use 36px titles, benefits use smaller 24px titles; job listings become plain 90px rule-separated rows with location over title, small metadata and a pill application action. Filters are compact 32px rounded controls and the view-more action spans the list.

**Transfer:** Keep people and opportunities editorial and concrete, with real photography and scannable role metadata.

### Calculator and comparison

**Only for:** pricing pages

**Observed:** A 760px configuration column faces a 368px estimate column. Small amount presets, a green slider and three provider cards lead into selectable packages, fees, add-ons and included capabilities. The right column summarizes line items, total and a green action, with a separate dark contact panel below. Later a Soft black band carries four Plan cards; logos and Question row follow on white.

**Transfer:** Separate interactive estimation from the broad package comparison and explain cost components in plain language.

## Page flow

**Storyline:** Promise → tangible product or human context → capabilities and proof → decision support → quantified proof or closing invitation → compact black footer.

### Broad product landing page

1. **Promise** — Left-weighted atmospheric opening with short support, paired actions and a working trial.
2. **Social proof** — Light quotation alongside enterprise logo marks.
3. **Product demonstration** — Centered overview followed by alternating tinted interface scenes.
4. **Engagement** — Bright direct-action strip and black ecosystem rail.
5. **Trust** — Capability matrix, contextual testimonial video and paired proof banners.
6. **Quantified proof** — Five-column metric rail leading directly into the black footer.

**Transfer:** Balance immersive atmosphere with tangible tasks and verified outcomes; the proof-led ending is the default.

### Company and recruiting narrative

1. **Promise** — Centered compact introduction on warm paper and a direct application route.
2. **Human context** — Wide team portrait, principle cards and an overflowing documentary photo strip.
3. **Decision support** — Filterable opportunity list and practical benefit cards.
4. **Closing invitation** — Large centered question over the green landscape, then the black footer.

**Transfer:** Translate the warm-paper variant into a culture or people page with real activity and concrete opportunities.

### Customer-story discovery

1. **Framing** — Centered large title, short support and monochrome logo rail.
2. **Discovery** — Compact filters and search above varied photographic story cards.
3. **Closing call** — Left-aligned promise and paired actions over the green field, then the black footer.

**Transfer:** Organize proof by actual audience needs and outcomes, with varied editorial card heights.

### Commercial decision support

1. **Framing** — Left-aligned compact title above a calculator.
2. **Configuration** — Usage presets, provider choices and package options beside an itemized estimate.
3. **Comparison** — Dark four-card package band with squared prices.
4. **Objection handling** — Monochrome customer logos and thin-rule FAQ rows.
5. **Closing call** — Green atmospheric promise band and black footer.

**Transfer:** Explain variable and fixed charges separately, making the decision feel controllable rather than promotional.

### Deep technical product explanation

1. **Promise** — Centered cream headline over refracted warm bands.
2. **Capability chapters** — Warm-paper tour with a left active index and large right-hand illustrations.
3. **Process explanation** — Staggered colored process bars on a thin guide grid.
4. **Breadth** — Light feature matrix.
5. **Implementation proof** — Large black code section with language tabs and resource links.
6. **Control** — Light customization matrix.
7. **Closing call** — Centered monumental imperative over green atmosphere and the shared footer.

**Transfer:** Reserve the long indexed narrative and code proof for products whose buyer needs implementation confidence.

## Writing

Direct, builder-oriented and assured. The language makes sophisticated infrastructure feel controllable, then backs the promise with concrete tasks, operational detail and customer outcomes.

**Do not copy:** Do not reuse Vapi's name, logos, event identity, customer names, quotations, numerical claims, proprietary interface artwork or exact product-specific assertions. Source examples illustrate cadence only; replace them with truthful material for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Use we sparingly for commitments and collective values; product explanations favor active verbs over corporate self-description.
- **Rhythm:** Short three-to-eight-word headlines, often split into two clauses. Supporting copy is usually one or two compact sentences; occasional clipped fragments give speed without sounding breathless.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product category and the person it empowers, or use a direct build-oriented imperative. | 4–7 words | “Voice agents for builders”<br>“Build voice agents that scale” |
| Supporting line | Pair reader ownership with practical control and speed. | 10–22 words | “Your agents, your rules. Build, deploy, and improve voice agents as fast as you ship.”<br>“All the control of code. None of the infrastructure overhead.” |
| Section heading | Use a concrete outcome, sometimes followed by a short reinforcing fragment. | 5–10 words | “Build, test, and deploy in minutes.”<br>“Ship better agents. Faster. Every time.” |
| Technical explanation | Lead with a measurable behavior or a clear verb; explain the mechanism without a metaphor. | 10–25 words | “Responses in under 500ms for seamless, real-time conversation.” |
| Primary action | Plain verb plus immediate task, with sentence case. | 1–3 words | “Get started”<br>“Start building”<br>“Contact sales” |
| Culture statement | A direct, memorable commitment rather than an abstract noun. | 3–7 words | “Commit and follow through.”<br>“Be direct and kind.” |

**Words and phrasing to use:** build; ship; configure; deploy; control; your; ready; in minutes; no lock-in; production

**Avoid:** revolutionary solution; unlock limitless possibilities; seamless synergy; magic; game-changing; effortlessly transform everything

**Rules:**

- Make speed credible with a task, mechanism or verified measure.
- Use ownership language to emphasize configurable behavior rather than vague autonomy.
- Keep technical labels noun-like and short; let the larger heading communicate the benefit.
- Prefer specific operational proof over superlatives.

## Do's and Don'ts

### Do

- Keep the opening display at 80px/1.02 with -0.05em tracking and weight 600 on desktop.
- Use 40px medium section heads with short 16px or 14px support beneath.
- Preserve a mostly near-white reading field and confine strong fills to distinct bands.
- Pair white and black 40px actions with a 12px gap and 12px corner radius.
- Give media scenes around 662×443px of presence beside a roughly 400px text column.
- Use 14px squared uppercase section labels with 1.1px tracking.
- Let quantitative proof sit in plain cells with 1px vertical rules, not floating cards.
- Keep the black footer compact at about 372px, with 80px vertical padding and 12px navigation.

### Don't

- Do not use weight 700–900 for ordinary section headings; the fitted medium face supplies the force.
- Do not use the squared technical family for body paragraphs or the large default hero.
- Do not make all buttons pill-shaped; pills belong to tags, filters and process bars.
- Do not tint every reading section green; the #62f6b5 fill is a narrow interruption.
- Do not add drop shadows to every card; outlines, flat fills and image contrast define the layers.
- Do not put colorful category badges throughout ordinary marketing copy; tiny technical labels carry the hierarchy.
- Do not enlarge the footer into an enormous wordmark mural; its identity mark shares space with practical links.
- Do not expose a dense unframed interface as the entire visual system; stage product views with material light and breathing room.

## Motion and responsive

### Motion

**Observed:**

- Declared ecosystem scrolling is 40s linear infinite.
- Default conversion actions declare all-property transitions at 0.3s cubic-bezier(.4,0,.2,1).
- The trial selector declares a background-color transition at .15s cubic-bezier(0,0,.2,1).
- Story read-more arrows declare a small horizontal translation on hover; card spotlight parallax is tied to scrolling.

**Transfer:**

- Use the slow moving ecosystem rail behind edge masks, keeping text beside it stationary.
- Confine trial feedback to tint changes inside the glass bar rather than moving the entire hero.

**Unknown:**

- The precise temporal behavior of atmospheric imagery and the complete scroll-reveal choreography are not established.

### Responsive

**Observed:**

- CSS declares common width thresholds including 640px, 768px, 1024px and 1280px.
- Heading classes reduce major 40px section heads to 28px and left alignment at narrower widths; the primary hero support reduces from 18px to 16px.
- Culture grids declare one column before three columns; plan grids declare one, then two, then four columns.
- The wide staggered process composition is hidden below the widest layout threshold.

**Transfer:**

- Stack feature copy and media while retaining the landscape frame and recognizable tinted material.
- Keep the atmospheric field full bleed, reduce headline scale and give the trial controls their own full-width line.
- Replace staggered process placement with a vertical sequence of the same colored bars and captions.
- Wrap the proof rail into readable rows rather than squeezing five stat values into a phone width.

**Unknown:**

- Exact mobile navigation behavior, all reduced type sizes and small-screen atmospheric focal points are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
