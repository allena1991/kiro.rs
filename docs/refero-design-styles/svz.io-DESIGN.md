# SVZ — grotesk meets tactile theater

## Overview

A dark, theatrical digital style with tightly packed grotesk capitals, delicate editorial serif interruptions and small utilitarian navigation. Black and charcoal dominate, interrupted by warm white galleries and concentrated flashes of hot red. Abstract geometric animation, glossy sculptures, cinematic editorial art and an unexpectedly furry closing object lend a playful physicality to otherwise restrained layouts. It suits ambitious creative technology, premium services and product launches with room for immersive storytelling.

### Essentials

- Headlines behave like compressed word sculptures: regular grotesk capitals at 64px/1 with -0.075em tracking, with occasional single-letter calligraphic substitutions rather than whole script phrases.
- The opening is a black stage, not a conventional split hero: an 800px centered two-line promise sits near mid-height in a 900px screen, small 20px serif connector words flank it, and oversized charcoal geometry with bright circular accents rises from the lower half.
- Actions are fine rectangular instruments: the default button is 240px by 45px, a 1px translucent white outline, 2px corners, 14px text and a small northeast arrow at the right.
- Color arrives as punctuation and deliberate interruptions: most of the page stays black or charcoal; warm-white gallery bands and isolated #fe1e34 feature tiles punctuate it, while #ff242e highlights selected words and compact labels. Do not distribute red evenly through every block.
- Media is staged at both intimate and monumental scales: dense interface montages sit in 540px-tall tiles, while a small portrait video interrupts a 160px uppercase text ribbon. Include a scale collision of this kind; a recorded product explanation can replace the portrait.
- The ending returns to the theatrical promise: repeat the centered 64px two-line headline and serif side words over a tactile sculptural object, then set tiny navigation in five columns below. Use an original textured initial or simple fabric-like abstract form when no sculptural asset exists.
- Section titles mix industrial spacing with a flourish: bracketed 12px red labels, 16px label-to-heading gaps, 64px or 80px uppercase headings, and a single ornamental glyph create an editorial identity without ornamental panels.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal red | `#fe1e34` | `--color-red` | accent, surface, link | Bracket labels, rare full-color feature panels and link hover. |
| Headline red | `#ff242e` | `--color-text-red` | text, accent | Highlighted words in large statements and category captions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Tile ink | `#0d0d0d` | `--color-tile` | surface, text | Dark feature tiles and text on light or red panels. |
| Stage black | `#000000` | `--color-stage` | background, surface | Immersive opening, proof and closing stages; darker than the main canvas. |
| Near black | `#080808` | `--color-canvas` | background | Default page canvas. |
| Footer charcoal | `#131313` | `--color-footer-base` | background | Underlying closing surface, mostly covered by the black stage. |
| Objection charcoal | `#171617` | `--color-objection-band` | background | Question-and-answer band. |
| Dark hairline | `#212121` | `--color-hairline` | border | Visible 10% white rule over the near-black canvas; implemented with rgba(255,255,255,0.1). |
| Quote charcoal | `#262525` | `--color-testimonial` | surface | Testimonial cards; surrounding cards are visually dimmed. |
| Raised charcoal | `#373535` | `--color-raised` | surface | Question cards and geometric illustration backplates. |
| Action edge | `#525252` | `--color-action-edge` | border | Visible 30% white action outline over the near-black canvas; implemented with rgba(255,255,255,0.3). |
| Warm gray | `#777373` | `--color-muted` | text | Low-emphasis descriptions and breadcrumb context. |
| Soft gray | `#b5b2b2` | `--color-legal` | text | Legal and footer utility copy; the legal row is further subdued. |
| Silver text | `#d4d2d2` | `--color-secondary` | text | Question titles and secondary links. |
| Warm paper | `#f3efef` | `--color-warm-white` | text, background | Warm gallery canvas and large section headings. |
| Soft white | `#fcfcfc` | `--color-text` | text, background | Primary dark-theme text and bright editorial bands. |
| Pure white | `#ffffff` | `--color-white` | text, surface | Arrow squares, selected text and light customer-story panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detailed service or offer pages | Service panel | `#131212` | `--color-service-panel` | surface | Inset panel holding features, project images, quote and questions. |
| detailed service or offer pages | Subtle panel wash | `#141414` | `--color-subtle-fill` | surface, border | Visible 5% white wash over near black, implemented with rgba(255,255,255,0.05). |

## Typography

- **Kmr Waldenburg** — Headlines, body, actions and labels. Compact contemporary grotesk with clean circular forms and emphatically tight display spacing. If unavailable, use **Inter**. Use 400 and 700; retain tight headline tracking and tune line breaks to the same width. Font stack: "Kmr Waldenburg", "Inter", Arial, sans-serif.
- **Editorialnew** — Serif connector words, editorial card titles and expressive numbers. Light, high-contrast editorial serif with narrow proportions and sharp details. If unavailable, use **Instrument Serif**. Use regular as the light visual equivalent; preserve narrow line lengths. Font stack: "Editorialnew", "Instrument Serif", Georgia, serif.
- **Dirtyline 36 Daysoftype 2022** — One ornamental letter within otherwise grotesk display words. Swashing, sculptural calligraphic capitals with dramatic thick-thin contrast. If unavailable, use **Bodoni Moda**. Use an italic capital as a fallback and tune its width individually. Font stack: "Dirtyline 36 Daysoftype 2022", "Bodoni Moda", Times New Roman, serif.
- **system-ui** (only for testimonial cards) — Quote paragraphs and attribution. Plain system sans, visually more utilitarian than the branded headings. Font stack: "system-ui", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| ribbon | Kmr Waldenburg | 700 | 160px | 1.05 | -0.08em, uppercase | Oversized text running behind a small portrait video. |
| heading-large | Kmr Waldenburg | 400 | 80px | 1.05 | -0.0375em, uppercase | Major gallery heading and cinematic service-page opening. |
| wall-heading | Kmr Waldenburg | 400 | 80px | 0.9 | -0.05em, uppercase | Testimonial wall heading. |
| ornamental-letter-large | Dirtyline 36 Daysoftype 2022 | 400 | 80px | 0.9 | -0.03em, uppercase | Single expressive glyph in the testimonial wall title. |
| display | Kmr Waldenburg | 400 | 64px | 1 | -0.075em, uppercase | Default opening and closing promise, set as two tightly joined centered lines. |
| heading | Kmr Waldenburg | 400 | 64px | 0.9 | -0.0469em, uppercase | Editorial gallery and split feature section titles. |
| ornamental-letter | Dirtyline 36 Daysoftype 2022 | 400 | 64px | 0.9 | -0.0375em, uppercase | Single expressive glyph embedded in a 64px section title. |
| editorial-title | Editorialnew | 300 | 32px | 1.1 | -0.05em | Centered article card title over dark art. |
| connector | Editorialnew | 300 | 20px | 1.5 | normal | Short lowercase connecting words flanking opening and closing headlines. |
| question-title | Editorialnew | 300 | 20px | 1.1 | -0.02em, uppercase | Question card title. |
| body | Kmr Waldenburg | 400 | 14px | 1.5 | normal | General supporting copy; compact in scale even alongside monumental artwork. |
| category | Kmr Waldenburg | 400 | 14px | 1.5 | normal, uppercase | Card category captions and feature labels. |
| action | Kmr Waldenburg | 400 | 14px | 1 | normal | Outline and filled action labels; uppercase wording. |
| proof-caption | Editorialnew | 300 | 14px | 1 | normal | Tiny numeric corner labels and bottom captions on floating proof cards. |
| eyebrow | Kmr Waldenburg | 400 | 12px | 1.5 | normal, uppercase | Bracketed red section labels. |
| micro-signature | Kmr Waldenburg | 400 | 10px | 1.5 | 0.08em | Tiny centered identity line above a staged promise. |
| navigation | Kmr Waldenburg | 400 | 10px | 1.5 | normal | Grouped navigation and footer links; uppercase wording. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | case-display | Kmr Waldenburg | 700 | 128px | 1.05 | -0.10625em, uppercase | Broad left-aligned case title. |
| case studies | case-stat | Editorialnew | 300 | 80px | 1.3 | normal | Outcome figures inside outlined cards. |
| enterprise-style detailed benefit pages | serif-panel-title | Editorialnew | 300 | 72px | 1.05 | -0.0417em | Expressive title in red or white half-screen panels. |
| enterprise-style customer stories | compact-stat | Editorialnew | 300 | 48px | 1.3 | normal | Row of customer-story outcome numbers. |
| company history narratives | timeline-label | Editorialnew | 300 | 48px | 1 | normal | Bracketed word repeated at left and right of the card stack. |
| case-study conversion panels | conversion-serif | Editorialnew | 300 | 42px | 1 | -0.038em | Short persuasive sentence beside typographic media. |
| detailed service or offer pages | service-heading | Kmr Waldenburg | 400 | 32px | 1 | -0.0125em, uppercase | Offer or engagement-model title. |
| detailed service or offer pages | capability-heading | Kmr Waldenburg | 400 | 32px | 1.2 | -0.0156em, uppercase | Numbered capability row title. |
| case studies | case-label | Kmr Waldenburg | 400 | 16px | 1.2 | -0.0156em | Red bracketed chapter titles in the left column. |
| case studies | case-body | Kmr Waldenburg | 400 | 15px | 1.5 | normal | Case narrative paragraphs. |
| testimonial cards | quote-body | system-ui | 400 | 14px | 1.5 | normal | Plain-spoken testimonial paragraphs. |
| quantified customer stories | stat-label | Kmr Waldenburg | 400 | 14px | 1.1 | normal, uppercase | Brief outcome description beneath serif figures. |
| detailed service or offer pages | accordion-label | Kmr Waldenburg | 400 | 14px | 1.5 | -0.0286em, uppercase | Compact question inside the inset panel. |
| testimonial cards | quote-attribution | system-ui | 300 | 12px | 1.5 | normal, uppercase | Role and organization alongside a small portrait. |

**Notes:**

- Keep regular weight as the default for the largest promises. Bold is reserved for the enormous moving ribbon and case-study title, not every heading.
- Use the ornamental family for one letter, with 4px right padding where needed; preserve the word's legibility and baseline. Do not convert the whole heading into a script face.
- Large sans tracking is substantially tighter than body tracking. Serif inserts should feel slender and conversational beside the clean capitals.
- Use the 80px/1.05 heading with an 80px ornamental glyph at 84px line height when the title is not the tighter testimonial-wall variant.

## Layout

**Density:** Airy at section scale, compact within content: entire black stages surround tiny labels and relatively small body text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight inline groups, tag-grid gaps and stacked statistic-card gaps. |
| 16px | Eyebrow-to-heading and heading-to-description gaps; question card internal rhythm. |
| 24px | Global side inset, editorial grid gutters and testimonial content gaps. |
| 32px | Standard feature-tile and inset-panel padding. |
| 48px | Medium section padding, testimonial card padding and broad gallery inset. |
| 64px | Large internal content breaks and two-column row gaps. |
| 80px | Wide editorial column gutters and closing headline-to-action gap. |
| 112px | Major narrative chapter top and bottom padding. |

### Containers and grids

- **global-container**: max width 1440px · side padding 24px. Full-width desktop composition with a small consistent edge inset; 1392px available at the standard desktop width.
- **stage-copy**: max width 800px. Centered opening and closing headline group; no conventional left/right hero split.
- **gallery-container**: max width 1440px · side padding 48px. Warm gallery containing edge-to-edge media tiles.
- **editorial-grid**: 2 columns · gap 24px. Equal article cards, each 684px wide at desktop.
- **hub-grid**: 2 columns · gap 2px. Asymmetric 1.5fr/1fr media hub; first portfolio tile spans both columns, later pairs combine a wider statement tile with a narrower media tile.
- **question-grid**: max width 1024px · 3 columns · gap 16px. Centered set of three compact question cards.
- **footer-grid**: 5 columns · gap 0px · side padding 24px. Evenly distributed link groups under the closing object.
- **narrative-columns** (only for case studies): 2 columns · gap 80px. Case label at left, 656px narrative or results stack at right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-tags | 2px |
|  | testimonial-card | 4px |
|  | feature-tiles-and-section-bands | 8px |
|  | floating-proof-card | 14.4px |
| case-study conversion panels | conversion-panel | 16px |
| detailed service or offer pages | geometric-backplates | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | proof-card-inner-light | `rgba(255, 255, 255, 0.2) 0px 2px 5px 0px inset` | Subtle reflected edge on floating black cards. |
| case studies | stat-inner-light | `rgba(255, 255, 255, 0.2) 0px 1px 10px -6px inset` | Barely lit outlined result cards. |

### Surfaces

#### Canvas · level 0

**Use:** Default dark content field.

**CSS:** `background: #080808; color: #fcfcfc`

#### Black stage · level 0

**Use:** Opening, immersive proof and closing object scenes.

**CSS:** `background: #000000; overflow: hidden`

**Observed:** Artwork has room to reach the viewport edges while text sits above it.

**Transfer:** Give one focal object space rather than framing every scene as a card.

#### Warm gallery · level 1

**Use:** A bright break in the dark narrative.

**CSS:** `background: #f3efef; color: #0d0d0d; border-radius: 8px`

**Observed:** A complete band contains dark media tiles and a centered heading.

**Transfer:** Use for a collection of product proof or related work, not an all-light page theme.

#### Editorial white · level 1

**Use:** Article and related-story collections.

**CSS:** `background: #fcfcfc; color: #080808; border-radius: 8px; padding-top: 32px`

#### Question band · level 0

**Use:** Objection-handling chapter.

**CSS:** `background: #171617`

#### Signal panel · level 1

**Use:** Concentrated red statement tile within a media hub.

**CSS:** `background: #fe1e34; color: #0d0d0d; border-radius: 8px`

#### Image darkening

**Use:** Legible editorial type over cinematic art.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), linear-gradient(0deg, rgba(0, 0, 0, 0.88), rgba(0, 0, 0, 0))`

**Observed:** A separate media wrapper adds a uniform 50% black layer and saturate(2).

**Transfer:** Preserve deep blacks and isolate the bright red detail rather than washing the whole image gray.

#### Inset offer panel · level 1

**Only for:** detailed service or offer pages

**Use:** Grouped proof and details beside sticky explanatory copy.

**CSS:** `background: #131212; border-radius: 8px; padding: 0px 32px; backdrop-filter: blur(72px)`

**Observed:** Dark opaque-looking panel holds compact tags, a four-image montage, a quote and questions.

**Transfer:** Retain the dense, dossier-like grouping rather than creating separate bright cards for every item.

#### Conversion red · level 1

**Only for:** case-study conversion panels

**Use:** Large two-column invitation after results and credits.

**CSS:** `background: #fe1e34; border-radius: 16px; padding: 80px 32px`

## Components

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; padding: 28.8px 24px 0px; mix-blend-mode: difference; z-index: 999`

**Text style:** `navigation` — Kmr Waldenburg 400 · 10px/1.5

**Observed:** Compact mark at left, four small categorized link groups near the center, and Outline action at right. It begins as a broad menu and the scrolled treatment pares back to a compact mark and action.

**Transfer:** Use a short set of product, work, company and resources groups; keep their visual weight tiny relative to the scene.

### Outline action

**Use:** Default conversion and collection navigation.

**CSS:** `display: flex; align-items: center; width: 240px; height: 45px; padding: 0px 12px; border: 1px solid rgba(255, 255, 255, 0.3); border-radius: 2px; color: rgba(255, 255, 255, 0.8); mix-blend-mode: difference; overflow: hidden`

**Text style:** `action` — Kmr Waldenburg 400 · 14px/1

**Observed:** Left-aligned wording with a northeast arrow aligned to the far right. Two stacked label layers support the text movement; only one label is legible at rest. Some actions are 256px wide.

**States:** Declared: hover outline 0px; active outline 0px. Focus-visible treatment is unspecified.

**Transfer:** Keep one short uppercase action; retain a visible keyboard focus indication in implementation.

### Editorial card

**Use:** Article or educational resource link.

**CSS:** `display: flex; flex-direction: column; justify-content: center; align-items: center; height: 448px; padding: 24px; border-radius: 8px; overflow: hidden`

**Text style:** `editorial-title` — Editorialnew 300 · 32px/1.1 · tracking -0.05em

**Observed:** Dark full-bleed art, tiny widely tracked bracketed category, centered serif title limited to 400px, and a white 48px square arrow in the upper-right corner.

**Transfer:** Write a useful editorial title and use abstract architecture to suggest the topic.

### Question card

**Use:** Compact overview of an objection or frequently asked question.

**CSS:** `display: flex; flex-direction: column; justify-content: center; align-items: center; gap: 16px; background: #373535; border: 2px solid rgba(255, 255, 255, 0.08); border-radius: 8px; padding: 56px 32px`

**Text style:** `question-title` — Editorialnew 300 · 20px/1.1 · tracking -0.02em · uppercase

**Observed:** Small red category above a centered serif question; a Read more text link and northeast arrow follow. Tiny red plus marks sit at the four corners.

**States:** Declared: hover on the Read more link changes color to #fe1e34 and adds underline; active outline 0px.

**Transfer:** Keep each card to one genuine question; use the serif title as the focal element.

### Testimonial card

**Use:** Layered social-proof wall.

**CSS:** `display: flex; flex-direction: column; justify-content: center; gap: 24px; background: #262525; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 4px; padding: 48px`

**Text style:** `quote-body` — system-ui 400 · 14px/1.5

**Observed:** A three-line quote excerpt precedes a small portrait and uppercase attribution. Desktop cards are 486px by 233px inside a larger draggable wall; peripheral cards fade behind the centered heading.

**Transfer:** Use real attributable quotations and readable central cards; the wall should imply depth and abundance, not an ordinary carousel row.

### Floating proof card

**Use:** Tactile proof scene on black.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; width: 259px; height: 346px; padding: 11.5px; background: rgba(0, 0, 0, 0.2); border: 1px solid rgba(255, 255, 255, 0.12); border-radius: 14.4px; box-shadow: rgba(255, 255, 255, 0.2) 0px 2px 5px 0px inset; backdrop-filter: blur(6px)`

**Text style:** `proof-caption` — Editorialnew 300 · 14px/1

**Observed:** A tiny figure is aligned at the top-right, a partner mark occupies the center and a small serif caption sits at the bottom. Cards overlap and tilt slightly in a centered fan.

**Transfer:** Use verified integrations, teams, outcomes or compatibility marks with a small relevant numeric caption.

### Media hub tile

**Use:** Large visual navigation to product or company chapters.

**CSS:** `position: relative; display: flex; height: 540px; background: #0d0d0d; border-radius: 8px; overflow: hidden`

**Text style:** `category` — Kmr Waldenburg 400 · 14px/1.5 · uppercase

**Observed:** Artwork fills the tile; a lower-left uppercase title with one ornamental letter and a northeast arrow sits over a black bottom fade. A red statement variant uses black text.

**Transfer:** Show a montage, a simple object or a short typographic film; each tile should have a distinct visual idea.

### Footer link group

**Use:** Quiet wayfinding below the monumental final invitation.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `navigation` — Kmr Waldenburg 400 · 10px/1.5

**Observed:** Five evenly spaced groups: small category heading, then a short stack of links. Links rest at opacity 0.75 and become fully opaque on hover. A low-contrast legal row is separated below.

**States:** Declared: hover opacity 1 and outline 0px on links; active outline 0px.

### Filled action

**Only for:** case-study conversion panels

**Use:** Conversion against the red invitation surface.

**CSS:** `display: flex; align-items: center; width: 256px; height: 45px; padding: 0px 12px; background: #0d0d0d; color: #ffffff; border-radius: 4px`

**Text style:** `action` — Kmr Waldenburg 400 · 14px/1

**Observed:** Same arrow and layered label construction as Outline action, with a solid dark backing.

### Capability tag

**Only for:** detailed service or offer pages

**Use:** Compact list of included features within the inset panel.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 8px 12px; background: rgba(255, 255, 255, 0.05); border: 1px solid rgba(255, 255, 255, 0.05); border-radius: 2px; mix-blend-mode: difference`

**Text style:** `category` — Kmr Waldenburg 400 · 14px/1.5 · uppercase

**Observed:** Rectangular labels form a three-column grid with 8px gaps, not a flowing cluster of pills.

### Inset question

**Only for:** detailed service or offer pages

**Use:** Detailed offer-specific questions.

**CSS:** `background: rgba(255, 255, 255, 0.05); border: 1px solid rgba(255, 255, 255, 0.05); border-radius: 2px`

**Text style:** `accordion-label` — Kmr Waldenburg 400 · 14px/1.5 · tracking -0.0286em · uppercase

**Observed:** Question row uses 16px vertical and 24px horizontal padding, a plus at right and a separate answer area below. Most rows are 58px tall at desktop.

**Transfer:** Keep questions near the relevant offer rather than moving every objection into a distant generic FAQ.

### Outcome card

**Only for:** case studies

**Use:** Post-project quantified results.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 32px; border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 8px; box-shadow: rgba(255, 255, 255, 0.2) 0px 1px 10px -6px inset; overflow: hidden`

**Text style:** `case-stat` — Editorialnew 300 · 80px/1.3

**Observed:** A large light serif figure above a small uppercase metric description; cards stack with 8px gaps in the narrative's right column.

## Imagery and graphics

### Geometric opening alphabet

**Use:** Primary opening artwork and smaller chapter motifs.

**Observed:** Oversized charcoal semicircles, slanted bars, triangles and a cross-like figure fill the lower half of a black screen. Hot pink circles punctuate the dark forms. Shapes extend off the sides and bottom; the white headline remains in front.

**Transfer:** Construct an original symbolic alphabet for the new product. A simple SVG assemblage is sufficient; retain the scale, cropping and two or three bright circular accents.

**Build:** Use a 1440px by 450px SVG viewBox anchored to the bottom of a 900px stage. Draw thick semicircular paths, a rotated rectangular bar, a solid triangle and intersecting rectangles with circular cutouts in dark charcoal. Place two contrasting pink or signal-red circles, one partly below the left edge and one above the triangle. Layer headline text above the SVG.

### Tactile closing sculpture

**Use:** Signature final invitation behind the centered headline.

**Observed:** A large folded initial-like object floats against black, covered in yellow-gold fur with dark spots. Soft strands and directional highlights make it feel physical; the object occupies roughly half the screen width and most of the upper closing scene, behind white text.

**Transfer:** Create a new initial or folded geometric emblem with an unexpected tactile material. Minimum version: a textured SVG silhouette with dense fine hair-like strokes and soft directional shading, not a flat logo pasted behind the heading.

**Build:** Draw a folded ribbon or inflated initial as three joined curved SVG lobes. Clip a gold-and-dark irregular spot pattern to it, shade the underside with translucent black gradients, then add hundreds of short curved strokes clipped near the contour to simulate fibers. Keep the background black and a dark radial veil behind the copy for contrast. The particular spot pattern is not essential; physical texture and a clean silhouette are.

### Editorial architecture

**Use:** Dark illustration inside article cards.

**Observed:** Charcoal interlocking frames, stacked slabs and monumental interiors with a single saturated red structural element; some scenes include tiny human figures. Images fill the cards with cover framing, cinematic low light and heavy bottom darkening.

**Transfer:** Translate each topic into a restrained physical metaphor: connected frames for trust, stacked layers for infrastructure, a lit aperture for discovery. Minimum acceptable artwork is a clean isometric SVG with one red element and subtle directional shading.

**Build:** Draw three offset isometric quadrilaterals or hollow frames with near-black top and charcoal side faces. Color one connecting edge or slab signal red, then apply a black-to-transparent bottom overlay and a uniform translucent black veil. Keep the center open enough for the serif title.

### Interface and identity montages

**Use:** Product proof in galleries, case narratives and offer panels.

**Observed:** Full-color website frames and brand applications are grouped into tightly cropped collages. A broad gallery montage fades to black along its bottom; case images use warm off-white boards, framed interface fragments, apparel photography and a deep colored logo board. The inner product palettes can differ strongly from the surrounding red-and-black identity.

**Transfer:** Use the new product's real interface and branded artifacts on presentation boards. Preserve their own palette inside the artwork; do not promote those inner colors into page-wide design tokens.

### Dark material hero

**Only for:** cinematic service and enterprise pages

**Use:** Alternative opening stage.

**Observed:** A near-black glossy perforated membrane backs the service heading; the enterprise variant has a broad beveled dark emblem crossed by a jagged white light seam. Both occupy most of a full-screen scene with centered text and tiny corner utilities.

**Transfer:** Choose one abstract material tied to the product: a folded sheet, perforated shell or beveled emblem. Minimum version is a shaded SVG surface with sparse edge highlights, not an empty black stage.

**Build:** For the light-seam variant, place a beveled charcoal silhouette behind the title. Draw an irregular horizontal white SVG path across the screen; duplicate it with low-opacity strokes and 8px then 24px blur to create a narrow electric core with soft spill. Fade both ends into black; keep most of the object almost unlit.

### Orbiting proof sculpture

**Only for:** immersive quantified-proof chapters

**Use:** Dramatic proof scene on service and enterprise-style pages.

**Observed:** A glossy red toy-like animal occupies the center while black beveled coins, cubes and pyramids float around the perimeter. A large curved white text band sweeps across the scene, followed by compact justified copy with red-highlighted facts.

**Transfer:** Use an original product metaphor such as a red abstract module, surrounded by a few dark primitive solids. Keep the scale contrast and sparse black field; no animal motif is required.

**Build:** Build a central red rounded SVG or 3D form with directional specular highlights. Place six to eight charcoal primitives around the edges, with thin gray edge lighting and varied rotation. Use an SVG textPath on a shallow upward arc for the white proof statement, extending past both viewport edges.

### History card stack

**Only for:** company history narratives

**Use:** A tangible sequence of milestones.

**Observed:** A centered stack of tilted cards on black moves from dark red through bright red and pink to pale paper. Each card has a prominent serif year, serif milestone title and small paragraph; repeated bracketed serif labels sit at the outer edges.

**Transfer:** Use original dates and milestones or a product evolution story. Minimum version is layered HTML cards with subtle rotations and color progression.

**Build:** Center several rounded portrait cards and offset successive layers downward with progressively smaller scale. Use dark-red, signal-red, pink and warm-paper faces, light serif titles on dark faces and black on pale faces. Keep lower layers narrowly visible like a physical deck.

### Portrait tickets

**Only for:** company and team pages

**Use:** Leadership or expert roster.

**Observed:** Black-and-white portraits sit in wide ticket-like cards in two horizontally overflowing rows. Alternating pale and dark ochre boards include a small serif name, a compact role and a tall barcode, with tiny notches at the edges.

**Transfer:** Use consistent grayscale portraits and original role labels. Preserve the ticket construction rather than a conventional circle-avatar grid.

**Build:** Use a 360px by 170px horizontal card with 8px corners, a portrait occupying its left third, a serif name at upper center, role at lower center and closely spaced unequal horizontal rules in the rightmost strip. Cut small semicircular notches into the upper and lower edge near the barcode. Alternate pale paper and a muted dark board.

### Icons

**Observed:** Utility icons are sparse: northeast arrows typically 13px, plus marks and small geometric signs at 16px or 18px. Cinematic corner controls use 32px crosshair-like strokes at 0.5px with round caps. Arrow squares on article cards are 48px.

**Transfer:** Prefer simple arrows and geometric marks over a general-purpose feature icon set. Keep action icons small and aligned at the far right; use delicate crosshairs only in immersive scenes.

## Section recipes

How recurring sections are built.

### First screen: Geometric stage opening

**Observed:** The first 900px is a black full-screen stage. Navigation sits across the top with 24px side insets, leaving a broad empty upper field. The two-line Display promise is centered in an 800px text group around the middle of the screen, spanning about half the screen width; a tiny identity line sits above, with 20px serif connector words beside the first line. Behind it, Geometric opening alphabet fills the bottom half, extends beyond the frame and rises toward the text. A small entry prompt and downward arrow sit near the bottom center; the only outlined conversion action is in the header at upper right. A slim leading edge of the next layered panel appears at the fold; narrative explanation and gallery proof sit below.

**Transfer:** Use a short outcome promise in two balanced uppercase lines with serif connectors and an original geometric alphabet. Without rich media, build the SVG primitives described in Geometric opening alphabet. Case studies instead open with a left-aligned 128px bold title, introduction and site action, with broad media entering below; cinematic service pages use an 80px centered heading over Dark material hero. Culture narratives can open with a right-aligned stack of giant serif words.

**Avoid:** Do not replace the stage with a left-copy/right-dashboard hero, a full paragraph and two large filled buttons. Do not fill the empty upper field with badges or a grid of feature chips.

**Text style:** `display` — Kmr Waldenburg 400 · 64px/1 · tracking -0.075em · uppercase

### Editorial heading pair

**Observed:** A bracketed red Eyebrow precedes a centered uppercase Heading by 16px. The copy group is often 768px wide; one ornamental letter interrupts an otherwise regular grotesk title. Major narrative sections use 112px top and bottom padding.

**Transfer:** Use a short category label and a compact descriptive title; repeat the single-letter flourish sparingly, not on every word.

**Text style:** `heading` — Kmr Waldenburg 400 · 64px/0.9 · tracking -0.0469em · uppercase

### Manifesto reveal

**Observed:** A narrow block of uppercase prose sits on a large black field. Select meaningful nouns and phrases turn red while related project imagery appears at the sides. The prose condenses into a centered vertical list of red keywords.

**Transfer:** Turn the product's differentiators into a concise point of view and a handful of terms; pair with actual proof images. Keep the final static reading complete and coherent.

### Bright media hub

**Observed:** Warm gallery contains Heading large, a small monochrome partner-logo strip and a Media hub tile grid. Tiles use 540px height, 2px seams and asymmetric widths. Full-color interface montage, dark motion graphics and one Signal panel create distinct tile personalities.

**Transfer:** Collect relevant demonstrations, case material or product chapters under a single light band. Include one red interruption rather than tinting all tiles.

### Floating proof stage

**Observed:** A centered Display heading and serif side words sit over black. Four Floating proof cards fan and overlap across the middle, with a restrained action below.

**Transfer:** Make proof feel collected and tangible; verified customer outcomes or integration marks can replace investor-related examples.

### Portrait and ribbon

**Observed:** A narrow vertical testimonial video occupies the center of a full-screen Black stage while the 160px bold Ribbon extends beyond both sides behind it. A case-study action follows lower in the scene.

**Transfer:** Use a human explanation or a compact product video as the intimate layer and one repeated topic word as the oversized backdrop. Preserve the unusual collision of scales.

**Text style:** `ribbon` — Kmr Waldenburg 700 · 160px/1.05 · tracking -0.08em · uppercase

### Editorial gallery

**Observed:** Editorial white holds a centered Heading followed by two-column Editorial cards with 24px gutters. A centered Outline action closes the collection.

**Transfer:** Use useful resources as supporting expertise; keep card art dark even though the containing band is light.

### Question overview

**Observed:** Question band uses a centered two-line white/red heading and red Eyebrow, followed by three Question cards inside a 1024px container. Outline action is centered below.

**Transfer:** Introduce the customer's likely concerns with a balanced pair of short phrases, then answer through focused linked questions.

### Testimonial wall

**Observed:** An 80px Wall heading sits over a viewport-tall dark, draggable field of Testimonial cards. Cards fill beyond the frame in multiple rows; a dark top gradient keeps the heading distinct and outer cards recede.

**Transfer:** Use a central readable cluster with a surrounding sense of abundance. Do not require dozens of quotes if only a few verified stories exist.

**Text style:** `wall-heading` — Kmr Waldenburg 400 · 80px/0.9 · tracking -0.05em · uppercase

### Sculptural close

**Observed:** A Black stage of 1080px contains Tactile closing sculpture behind a centered two-line Display promise, serif side words and micro identity line. Outline action sits 80px beneath the heading. Footer link group forms five columns toward the bottom, followed by a subdued legal row with privacy link at the far right.

**Transfer:** End with one confident invitation over an original tactile object, then let practical navigation stay small. Preserve the sculptural close even when the rest of the page is more informational.

**Text style:** `display` — Kmr Waldenburg 400 · 64px/1 · tracking -0.075em · uppercase

### Case narrative and results

**Only for:** case studies

**Observed:** Red bracketed chapter labels sit in the left half, with 15px/1.5 narrative text in the right half and an 80px gutter. Wide media and two-column boards alternate with the prose. Outcome cards stack in the right column; credits follow before Conversion red and related stories.

**Transfer:** Tell a problem, decisions, implementation and outcomes story. Let the product imagery keep its own internal palette.

**Text style:** `case-body` — Kmr Waldenburg 400 · 15px/1.5

### Red invitation panel

**Only for:** case-study conversion panels

**Observed:** Conversion red uses two columns: oversized red-on-black typographic media at left, a 42px light serif persuasion sentence, three compact benefit lines and Filled action at right. The panel sits within 24px page insets.

**Transfer:** Use an original short typographic film or a static oversized typographic composition, alongside a truthful next-step invitation.

**Text style:** `conversion-serif` — Editorialnew 300 · 42px/1 · tracking -0.038em

### Split benefit dossier

**Only for:** enterprise-style detailed benefit pages

**Observed:** A black left half holds a sticky 64px heading while the right half cycles between red and white 720px by 900px panels. Each panel carries a 72px serif title, one simple symbol and compact ruled facts. The later light chapters use numbered 32px bold headings on the left and fine tabular details on the right.

**Transfer:** Use for substantive comparison, risk, compliance or adoption concerns. Alternate dramatic benefit statements with evidence-rich rows.

**Text style:** `serif-panel-title` — Editorialnew 300 · 72px/1.05 · tracking -0.0417em

### Capability and offer chapters

**Only for:** detailed service or offer pages

**Observed:** Numbered rows combine a 32px uppercase title, compact list and a 320px square charcoal backplate with red/black geometric art. Rows stack in a sticky sequence. Later offers use a sticky explanation at left and Inset offer panel at right containing Capability tags, project montages, quote and Inset questions.

**Transfer:** Organize actual product capabilities into named chapters; compare ways to adopt the product using contextual proof rather than a generic pricing-card grid.

**Text style:** `capability-heading` — Kmr Waldenburg 400 · 32px/1.2 · tracking -0.0156em · uppercase

### Culture narrative

**Only for:** company and team pages

**Observed:** A red serif word stack opens on black, followed by a centered manifesto, History card stack, a warm-paper team-distribution band and two rows of Portrait tickets. Testimonial wall and Sculptural close finish the narrative.

**Transfer:** Use this variant for a human or organizational story; keep the theatrical identity while showing real people and concrete history.

## Page flow

**Storyline:** staged promise → point of view → visual demonstration → credible proof → deeper explanation or objections → sculptural invitation and practical navigation

### Broad marketing landing page

1. **promise** — Centered type over oversized geometric artwork.
2. **point of view** — Uppercase manifesto with red keywords and moving proof images.
3. **product demonstration** — Warm gallery containing an asymmetric media hub.
4. **social proof** — Floating proof cards and an intimate portrait over an oversized ribbon.
5. **education and objections** — White editorial gallery, then dark question overview.
6. **closing call** — Testimonial wall, tactile object, centered invitation and five footer groups.

**Transfer:** Use the visual stage as the default, selecting proof and explanation blocks that fit the new product rather than reproducing every chapter.

### Project or customer story

1. **context** — Broad bold title, short introduction, external action and full-width demonstration.
2. **problem and decisions** — Red left-column labels against right-column narrative, interleaved with identity and interface boards.
3. **outcomes** — Stacked serif result cards and compact project credits.
4. **conversion** — Red invitation panel followed by related stories.
5. **closing call** — Testimonial wall and shared sculptural footer.

**Transfer:** Ground this storyline in a specific problem, product decisions and verified outcomes; keep the gallery imagery larger than the explanatory text.

### Company and culture narrative

1. **identity** — Giant serif word stack on black.
2. **point of view** — Compact uppercase manifesto with red phrase emphasis.
3. **history** — Layered physical milestone deck.
4. **people proof** — Light distribution band and grayscale portrait tickets.
5. **closing call** — Testimonial wall and shared sculptural footer.

**Transfer:** Translate history and people into tangible artifacts, not a generic values-card grid.

### High-consideration enterprise offer

1. **promise** — Centered heading over a beveled dark emblem and luminous seam.
2. **credibility** — Manifesto, sculptural quantified-proof scene and light customer outcome panel.
3. **benefit chapters** — Sticky split layout with red/white serif panels.
4. **objection handling** — Light, numbered evidence rows with compact facts.
5. **related proof** — Testimonial wall, project gallery and editorial gallery.
6. **closing call** — Shared tactile object and centered invitation.

**Transfer:** Pair cinematic confidence with detailed adoption, reliability and scale evidence; the long light dossier is specific to this high-consideration variant.

### Capabilities and engagement-model explanation

1. **promise** — Centered headline over a dark perforated material scene.
2. **capability chapters** — Numbered sticky rows with compact text and geometric backplates.
3. **quantified proof** — Red central sculpture, orbiting black primitives and curved fact band.
4. **adoption options** — Sticky left offer descriptions paired with dense right-hand proof panels and contextual questions.
5. **closing call** — Testimonial wall and shared tactile footer.

**Transfer:** Explain what the product does and how customers can adopt it; use comparison chapters and contextual proof when pricing is not a simple tier table.

## Writing

Confident and art-directed, with an ambitious creative vocabulary balanced by practical explanations. Large statements are declarative and compact; longer paragraphs explain decisions, outcomes and how collaboration works.

**Do not copy:** Do not reuse SVZ names, logos, artwork, client identities, testimonial quotations, funding figures, awards, dates, scarcity claims or project results. Replace every claim with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you or your for the customer. Aspirational headlines focus on the result; explanations shift into direct, useful language.
- **Rhythm:** Two-line headline fragments and short category labels contrast with compact paragraphs. Actions use brief uppercase verb phrases. Serif side words act as grammatical connectors rather than additional slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Two complementary noun phrases joined by small conversational words. | 5–9 main words | “digital worlds”<br>“brands of tomorrow” |
| Section headline | A short, memorable editorial label, often with a paired response. | 2–6 words | “THE HUB”<br>“YOU ASKED. WE ANSWER.” |
| Supporting explanation | State who the offer fits and the practical benefit without decorative language. | 1–3 compact sentences | “A simple, upfront pricing model where the project scope and cost are agreed upon from the beginning. Ideal for clients with well-defined requirements who want predictability.” |
| Primary action | A specific next step or a verb-led collection link. | 2–4 words | “DISCOVERY CALL”<br>“READ CASE STUDY”<br>“DISCOVER OUR PROCESS” |
| Chapter marker | Bracketed uppercase topic, compact and functional. | 1–5 words | “[THE CHALLENGE]”<br>“[RESULTS AND OUTPUT]” |
| Closing promise | Bridge two complementary ideas in a confident final statement. | 6–10 main words | “Bridging The Gap”<br>“Technology and Artistry” |

**Words and phrasing to use:** craft; vision; purpose; evolve; connect; scale; artistry; groundwork; built to scale

**Avoid:** frictionless synergy; revolutionary everything; cute diminutives; breathless exclamation marks; vague luxury superlatives

**Rules:**

- Let the opening communicate the ambition, then substantiate it through specific examples and results.
- Use uppercase as visual treatment, not as an excuse for clipped or incomprehensible prose.
- Highlight only the meaningful terms in a manifesto, leaving complete sentences readable without color.
- Make article titles genuinely informative and questions recognizable to the intended customer.

## Do's and Don'ts

### Do

- Keep default display promises at 64px/1, weight 400 and -0.075em tracking.
- Use 20px light serif connector words beside the major promise.
- Anchor large geometric art to the lower half of the opening and retain black space above it.
- Use 240px by 45px outlined actions with 2px corners and a small right-hand arrow.
- Set standard outer gutters to 24px and broad gallery insets to 48px.
- Preserve the 112px chapter padding and compact 14px body scale.
- Give large media tiles 8px corners and let warm-paper bands frame dark artwork.
- Carry the tactile closing object and small five-column navigation into new landing pages.

### Don't

- Do not turn the primary action into a red pill; red belongs mainly to selected text and isolated statement surfaces.
- Do not use bold 64px display copy by default; weight 700 belongs to the 160px ribbon and 128px case title.
- Do not replace every serif interruption with italic sans; the contrast of constructions is essential.
- Do not make all dark surfaces the same black: distinguish #080808 canvas, #0d0d0d tiles and #373535 question cards.
- Do not apply bright product-art palettes to the marketing canvas; keep those colors within their media boards.
- Do not give the fine outlined buttons the 14.4px radius reserved for floating proof cards.
- Do not make the white editorial band contain pale article cards; its cards remain cinematic and dark.
- Do not turn the detailed offer comparison into a row of generic rounded pricing cards with giant prices.

## Motion and responsive

### Motion

**Observed:**

- Sticky full-screen stages, overlapping card decks, changing headline phases and oversized horizontal text bands define the theatrical pacing.
- The question cards declare a 0.2s transition. Other actions and surfaces declare background-color and color transitions at 0.3s, with some background-color transitions at 0.1s ease-in.
- Navigation links declare hover opacity 1. The question Read more link declares red text and underline on hover.

**Transfer:**

- Preserve a settled, readable promise at every staged stop; use movement to reveal material or rearrange proof, not to make the message decipherable only in motion.
- Let a single scale-changing or horizontally sweeping scene carry the theatrical effect rather than animating all small labels.
- For a reduced-motion implementation, present the final complete text, a composed fan of proof cards and one static sculptural closing object.

**Unknown:**

- Exact scroll durations, triggers, label-roll timings and scene-specific easing are unspecified.

### Responsive

**Observed:**

- Desktop compositions use a 1440px-wide field. CSS includes width breakpoints at 479px, 767px, 768px, 991px, 992px, 1440px and 1920px; additional landing-specific rules include 1024px.
- Root font sizing is fluid; rem-based dimensions track the viewport. Floating proof-card padding follows 0.8vw, radius follows 1vw and overlap follows -6vw.

**Transfer:**

- On narrow screens, preserve the central stage and lower-edge geometric artwork; shorten or rebreak the headline rather than forcing desktop line widths.
- Stack the two-column narrative and offer layouts with explanations before their proof panels. Keep the tags rectangular and allow a smaller column count.
- Keep the closing sculpture behind the promise, reduce its visual footprint and wrap footer groups into a compact grid. These are adaptation rules, not a separate mobile theme.

**Unknown:**

- Actual narrow-screen compositions, navigation interaction and mobile type sizes are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
