# dotconnect — engineered irreverence

## Overview

An airy, off-white technology identity with near-black green ink and sudden bursts of vermilion. Rounded grotesk typography, tiny arrow capsules and numbered chapter markings bring an engineering sensibility, while glassy objects, diagrammatic illustrations and neon artwork keep it playful. It suits ambitious technical products and expert-led services that want to sound capable without sounding corporate; a darker editorial mode gives longer arguments a more confrontational character.

### Essentials

- A complete sentence becomes the opening monument: centered AeonikPro at 72px/1, weight 500, -0.025em tracking across roughly 936px, with 21px/1.5 support and one compact action below.
- Actions look like a dot pulling a capsule: 44px-high vermilion pills with 44px corners, a near-black circular arrow at the left, and 18px labels with 0.025em tracking.
- Chapters are marked, not decorated: full-width 1px rules, 24px outer padding, a lowercase arrow-link at the left and a brace-wrapped two-digit number at the right.
- Color arrives in concentrated doses: off-white and pale gray dominate the main narrative, orange lives in actions, object details and a full-width contact scene; near-black takes over the closing scene rather than tinting every section.
- Ideas become objects: a large translucent hero sculpture on a pale circular stage, square 20px-radius graphic panels, and simple dots that turn into labeled capsules. Every new landing page needs an equivalent object and a dot-based explanatory graphic; a translucent SVG object and a small network diagram are the minimum alternatives.
- The last impression is artwork, not a utility sitemap: follow a centered 72px closing statement with a large luminous line-art emblem on a near-black circular stage. Recast a product-specific symbol as white tubing, faint mounting hardware and tiny orange light points.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#fd5321` | `--color-accent` | action, accent, background, text | Primary actions, graphic details and large contact scenes. Short highlighted phrases use it in the dark editorial variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Green black | `#001011` | `--color-ink` | text, background, action | Headlines, circular arrow disks and the dark closing canvas. |
| Soft green ink | `#0f1e1f` | `--color-body` | text, surface | Paragraphs and the lighter end of the closing dark field; also raised panels in the dark editorial variant. |
| Light rule | `#c1c4c2` | `--color-rule` | border, text | Thin section separators and capability-grid rules. |
| Warm gray | `#ededea` | `--color-card` | surface, text | Illustration panels, audience cards, stat tiles and reverse editorial body text. |
| Pale stage | `#f0f0ee` | `--color-stage` | surface | Pale circular hero backing and the translucent-object demonstration stage. |
| Soft reverse | `#f6f6f4` | `--color-reverse-soft` | text | Long supporting copy in the dark closing invitation. |
| Warm white | `#fcfbf8` | `--color-canvas` | background, text | Default page canvas and reverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark editorial pages | Dark rule | `#3b4747` | `--color-dark-rule` | border | Dividers and reading-column edges on dark editorial surfaces. |

## Typography

- **AeonikPro** — All ordinary text, headlines, labels and numbers. Rounded contemporary grotesk with open counters and medium-weight headlines, not a heavy geometric display face. OpenType features: "dlig", "ss02", "ss08". If unavailable, use **DM Sans**. Use 400 and 500; preserve tight display tracking and check line breaks. Font stack: "AeonikPro", "DM Sans", Arial, sans-serif.
- **DotConnect** — Expressive braces, ampersands, plus signs and punctuation embedded within ordinary text. Custom diagram-like symbols; parentheses render with the character of curly braces. If unavailable, use **Space Grotesk**. Use 500 for punctuation; draw brace-like symbols in SVG where necessary. Font stack: "DotConnect", "Space Grotesk", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat | AeonikPro | 500 | 100.8px | 0.8 | normal | size 7vw | Oversized numbers pinned to the top of proof tiles. |
| display | AeonikPro | 500 | 72px | 1 | -0.025em | fixed | Centered opening statement and closing invitation. |
| heading | AeonikPro | 500 | 36px | 1.1 | -0.0125em | fixed | Main section headings, audience-card titles and contact invitations. |
| stat-caption | AeonikPro | 500 | 32px | 0.9 | -0.02em | fixed | Bottom-aligned noun beneath a large proof number. |
| chapter-label | AeonikPro | 500 | 24px | 1 | 0.01em | fixed | Section links, chapter numbers and small card headings. |
| symbols | DotConnect | 500 | 24px | 1 | 0.01em | fixed | Braces around chapter labels; align to adjacent text rather than using ordinary parentheses. |
| story-title | AeonikPro | 500 | 24px | 1 | normal | fixed | Short lowercase project titles in the carousel. |
| body | AeonikPro | 400 | 21px | 1.5 | normal | fixed | Introductory support lines and section paragraphs. |
| action | AeonikPro | 500 | 18px | 1 | 0.025em | fixed | Primary capsule action labels. |
| story-body | AeonikPro | 400 | 16px | 1.4 | normal | fixed | Compact project summaries inside story cards. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| dark editorial pages | chapter-display | AeonikPro | 500 | 230.4px | 0.8 | -0.025em | size 16vw | One-word chapter interludes with small chapter captions. |
| detail pages | page-title | AeonikPro | 500 | 160px | 1 | -0.04em | fixed | Single-word detail-page mastheads and monumental next-page links. |
| detail pages | editorial-heading | AeonikPro | 500 | 72px | 1 | -0.03em | fixed | Left-aligned sentence statements, sometimes interrupted by an inline action. |
| dark editorial pages | code-closing | AeonikPro | 500 | 64.1px | 1 | normal | size 4.45vw | Three-line closing statement with oversized code-like punctuation. |
| capability demonstrations | tab-label | AeonikPro | 500 | 32px | 1.1 | normal | fixed | Dark pill labels at the top of demonstration rows. |
| capability directories | capability-heading | AeonikPro | 500 | 28px | 1.2 | -0.01em | fixed | Capability directory headings. |
| dark editorial pages | editorial-lead | AeonikPro | 400 | 28px | 1.4 | normal | fixed | Centered long-form introductions with orange phrase emphasis. |
| service and capability detail pages | card-body | AeonikPro | 400 | 18px | 1.4 | normal | fixed | Benefit-card and capability-directory descriptions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Medium weight 500 does the hierarchy work; large text gets tighter tracking rather than heavier strokes.
- Main support paragraphs remain 21px even beside large artwork. Smaller 16px copy belongs inside story cards, not to the opening pitch.
- Use lowercase chapter nouns, sentence-case assertions and expressive brace punctuation. The symbol font is not a second body family.

## Layout

**Density:** Airy: broad open columns and long graphic stages contrast with tightly packed proof mosaics.

### Spacing

**Spacing system:**

- **rhythm** 8px, vertical — Main vertical rhythm; 16px, 24px, 32px, 48px and 64px are frequent multiples.

| Value | Use |
| --- | --- |
| 8px | Proof mosaic gutters and icon-to-link gaps. |
| 16px | Card heading-to-copy gaps and compact content stacks. |
| 24px | Outer page insets, chapter rails and standard card padding. |
| 32px | Audience-card padding and feature heading-to-paragraph-to-action gaps. |
| 48px | Detail statement-to-support separation and paired audience-card gutters. |
| 64px | Large artwork stages and carousel vertical breathing room. |
| 164px | Deep trailing space after detail-page editorial blocks. |

### Containers and grids

- **page-shell**: max width 2200px · side padding 24px. Wide full-bleed sections with inset content and edge-to-edge separating rules.
- **split-feature**: 2 columns · gap 0px. Equal-width columns each with 24px inner padding; at desktop the right graphic panel is 672px square and copy stays top-aligned.
- **hero-copy**: max width 936px. Centered three-line opening statement; supporting paragraph narrows to 640px.
- **audience-pair**: max width 1600px · 2 columns · gap 48px · side padding 48px. Two equally weighted square cards centered in a broad section.
- **proof-mosaic**: 5 columns · gap 8px · side padding 24px. Square portraits and statistic tiles; the lead proof tile spans two columns.
- **capability-directory** (only for capability directories): 3 columns · gap 0px. Continuous ruled grid with 480px-wide desktop columns, not separated floating cards.
- **editorial-reading** (only for dark editorial pages): max width 688px · side padding 24px. Narrow centered column with two vertical edge rules; centered introductory copy can widen to 800px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action capsule | 44px |
|  | large media cards | 20px |
|  | proof tiles | 12px |
|  | contact outer frame | 44px |
| service detail pages | benefit cards | 24px |
| capability demonstrations | demonstration labels | 52px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #fcfbf8; color: #001011`

**Observed:** Broad flat surfaces are articulated with hairlines rather than elevation.

**Transfer:** Let layout and artwork supply depth; keep the page itself flat.

#### Ruled band · level 0

**Use:** Chapter boundaries and large narrative sections.

**CSS:** `background: #fcfbf8; border-bottom: 1px solid #c1c4c2`

#### Gray graphic panel · level 1

**Use:** Square illustration backing and audience cards.

**CSS:** `background: #ededea; border-radius: 20px; overflow: hidden; box-shadow: none`

**Observed:** Soft corners contain sparse graphic objects, with no extra outline.

**Transfer:** Use a single coherent scene rather than a collage of interface windows.

#### Pale circular stage · level 0

**Use:** Hero sculpture backing.

**CSS:** `background: #f0f0ee; border-radius: 100%; overflow: hidden`

**Observed:** The visible stage is a centered disk that expands into a broad curved field as the page moves.

**Transfer:** Keep the curve much broader than the sculpture, clipped by the section.

#### Orange contact field · level 0

**Use:** High-contrast contact scene.

**CSS:** `background: #fd5321; color: #fcfbf8`

**Observed:** Full-width orange follows the light human invitation, centering a framed portrait and reverse text.

#### Dark closing field · level 0

**Use:** Closing invitation and luminous emblem.

**CSS:** `background: linear-gradient(#001011, #0f1e1f); color: #fcfbf8`

**Observed:** A subtle 32px tiled texture sits behind the copy. A near-black circular stage rises beneath the illustration.

**Transfer:** Use an extremely low-contrast dot or diamond SVG repeat; keep it subordinate to the emblem.

#### Dark reading field · level 0

**Only for:** dark editorial pages

**Use:** Long-form argument with narrow reading columns.

**CSS:** `background: #001011; color: #ededea; border-bottom: 1px solid #3b4747`

**Observed:** Full-width media interrupts vertical column rules; body copy is softer than white titles.

**Transfer:** Invert the light identity without changing the grotesk family or orange emphasis.

## Components

### Primary button

**Use:** Main action across opening, feature and contact blocks.

**CSS:** `background: #fd5321; color: #fcfbf8; border-radius: 44px; height: 44px; padding: 0px 24px 0px 60px; position: relative; overflow: hidden`

**Text style:** `action` — AeonikPro 500 · 18px/1 · tracking 0.025em

**Observed:** A dark circular disk overlaps the left end of the orange capsule and contains a light northeast arrow. The whole capsule is clickable. On dark editorial pages a white capsule with dark text reverses the treatment; the orange contact scene uses a contrasting ask action.

**States:** Declared: hover outline 0px; focus-visible color canvastext; active outline 0px.

**Transfer:** Keep a short verb or noun label. Provide a visible keyboard indicator rather than treating outline suppression as a design goal.

### Chapter rail

**Use:** Section identification and navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 24px; color: #0f1e1f`

**Text style:** `chapter-label` — AeonikPro 500 · 24px/1 · tracking 0.01em

**Observed:** Left side combines a small dark arrow disk and lowercase section link; right side uses two-digit numbering inside custom braces. Each side occupies half of the row.

**Transfer:** Name the function of each new chapter, not its marketing slogan.

### Audience card

**Use:** Two parallel entry points for different needs.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 32px; background: #ededea; border-radius: 20px; overflow: hidden`

**Text style:** `heading` — AeonikPro 500 · 36px/1.1 · tracking -0.0125em

**Observed:** Top-left arrow-linked title, short body paragraph, then a large centered orange object occupying the lower half of a square card.

**Transfer:** Use related object arrangements to express two different outcomes, such as scattered modules versus stacked modules.

### Story card

**Use:** Project or outcome proof in a horizontal carousel.

**CSS:** `display: flex; flex-direction: column; max-width: 400px; background: #ededea; border-radius: 20px; overflow: hidden`

**Text style:** `story-title` — AeonikPro 500 · 24px/1

**Observed:** A landscape image sits above a compact text area with 24px padding, short title and 16px body text. The active center card is sharp; neighboring cards are softened with 8px blur, 0.39 opacity and 0.95 scale. Dark 48px circular arrows sit at the outer edges.

**Transfer:** Use blur only to express carousel focus, never as a general image treatment.

### Statistic tile

**Use:** Quantified proof among visual tiles.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 24px; background: #ededea; border-radius: 12px`

**Text style:** `stat` — AeonikPro 500 · 100.8px/0.8

**Observed:** The numeral sits high and the 32px noun sits low, leaving an intentionally empty middle. A hand-drawn-looking plus can sit raised beside the number. Tiles mix with portraits and may span two columns.

**Transfer:** Use real measurable outcomes; if people are not relevant, interleave original product or process images at the same scale.

### Framed contact portrait

**Use:** Portrait-centered orange contact invitation.

**CSS:** `border: 1px solid rgba(252, 251, 248, 0.25); border-radius: 44px; padding: 8px`

**Observed:** Three nested frames step inward from 476px to 458px to 440px around a 420px portrait. The radii decrease from 44px to 36px to 28px. The fine concentric edges evoke a powered interface without turning the portrait into an app mockup.

**Transfer:** Use a product guide, real specialist or representative object; keep the portrait image clean and softly lit.

### Capability cell

**Only for:** capability directories

**Use:** Ruled directory of concrete skills or features.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 24px; gap: 24px; border-right: 1px solid #c1c4c2; border-bottom: 1px solid #c1c4c2`

**Text style:** `capability-heading` — AeonikPro 500 · 28px/1.2 · tracking -0.01em

**Observed:** A 64px icon tile and title align across the top with a 12px gap; 18px supporting copy sits underneath in a spacious 369px-tall cell.

**Transfer:** Organize a coherent set of capabilities into a continuous table-like field rather than independent raised cards.

### Demonstration label

**Only for:** capability demonstrations

**Use:** Named modes beside a visual demonstration.

**CSS:** `background: #001011; color: #fcfbf8; border-radius: 52px; padding: 3.2px 16px 0px 16px; height: 44px; overflow: hidden`

**Text style:** `tab-label` — AeonikPro 500 · 32px/1.1

**Observed:** A dark pill crowns each ruled descriptive row; an orange progress segment moves through the pill while a large pale object stage occupies the right half.

**Transfer:** Use short method names that share a common demonstration object.

### Next chapter link

**Only for:** detail pages

**Use:** Detail-page ending that continues the narrative.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #fcfbf8; height: 420px`

**Text style:** `page-title` — AeonikPro 500 · 160px/1 · tracking -0.04em

**Observed:** Small brace-wrapped next label at the upper left; enormous lowercase destination near the bottom with a dark circular northeast arrow. Each content row has 24px insets. It replaces a conventional multi-column footer.

**Transfer:** Make the whole ending one navigable destination.

### Benefit card

**Only for:** service detail pages

**Use:** Compact explanations of operating advantages.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 24px; background: #ededea; border-radius: 24px`

**Text style:** `chapter-label` — AeonikPro 500 · 24px/1 · tracking 0.01em

**Observed:** A bold two-color diagram icon precedes a small heading and 18px explanation. Four 326px-wide cards form a two-by-two grid with 20px gutters in the right half of a section.

**Transfer:** Keep one operational advantage per card; let the left half carry a short question and an orange answer.

## Imagery and graphics

### Translucent idea sculpture

**Use:** Dominant opening object and capability demonstration media.

**Observed:** A clear, silver-white brain-like object has glassy folds, faint prismatic edges and soft frontal lighting. It is isolated on a pale disk in the opening and appears inside a transparent slab in the demonstration. It occupies a 900px-square media stage below the opening copy.

**Transfer:** Replace the anatomical subject with an ownable product metaphor: a lens, folded material, connected module or instrument. The minimum version is a carefully drawn translucent SVG object with overlapping highlights, not a flat stock icon.

**Build:** Use a centered object inside a 900px-square stage. Layer several irregular closed SVG paths with pale gray fills at 0.15–0.35 alpha, thin near-white highlights and slightly offset darker contour lines. Use a small blurred duplicate behind highlights for a glass edge; set it over a pale circular backing rather than a colored gradient cloud.

### Dot and capsule diagrams

**Use:** Signature explanatory panels throughout the main narrative.

**Observed:** Near-black dots float in a pale gray square. Some extend into soft gray or off-white labeled capsules, others carry small symbols or rotate into diagonal labels. The graphic shares roughly half the section with text.

**Transfer:** Use dots for the new product's entities and labeled capsules for their functions or transformations. Keep the composition sparse.

**Build:** In a square SVG with rounded clipping, arrange 6–9 solid ink circles at varied positions. Make a subset expand horizontally into rounded rectangles about four to six circle diameters long; retain the leading dot and add one short black label. Use warm-white or gray capsule fills and reserve orange for one active node.

### Luminous mounted emblem

**Use:** Signature final artwork after the closing invitation.

**Observed:** A white neon brain outline sits on dark green rails and brackets with loose cables hanging below. White tubing carries soft halos; tiny orange terminals punctuate the lines. The media canvas is 900px square and the near-black circular backing is wider than the viewport.

**Transfer:** Turn a symbol associated with the new product into a physical neon sign. A simple original outline built from 3–6 curved paths is sufficient if detailed illustration is unavailable.

**Build:** Draw rounded open SVG paths in warm white at about 5–7px stroke on a 900px viewBox. Duplicate below with 12px and 24px Gaussian blur at low alpha. Add orange endpoint circles, dim green mounting bars and two thin looping cables behind the main paths. Place the assembly within a very large near-black circle over a subtly textured dark field.

### Orange modular objects

**Use:** Audience-card artwork and service metaphors.

**Observed:** Orange coin-like disks form a loose lattice or small towers on a pale gray backing. Other scenes use a white technical bottle with orange fittings and thin diagram callouts. Lighting is soft and shadows belong to objects, not their cards.

**Transfer:** Use a family of simple repeated modules that can rearrange into different benefits; preserve orange material, gray backing and explanatory clarity.

**Build:** For a simple SVG alternative, make orange ellipses with darker lower rims and pale upper arcs; stack repeated ellipses into columns or spread them on an isometric grid. Use alpha ink for small contact shadows and leave the upper card area free for text.

### Portrait mosaic

**Only for:** people and organization stories

**Use:** Human proof tiles and full-width portrait triptychs.

**Observed:** Waist-up people in predominantly dark clothing stand against consistent charcoal studio backgrounds. Expressions and gestures vary; square tiles use close gutters, while the detail opening uses three adjoining large portraits.

**Transfer:** Commission consistent soft-lit portraits and vary pose, not background color or filter. Use short silent loops only when available.

### Technical editorial scenes

**Only for:** service and dark editorial pages

**Use:** Full-width narrative interruptions and illustrated arguments.

**Observed:** Isometric stages, machinery, circuitry and exploded diagrams use dark green monochrome with orange fasteners or signals. Long-form passages also use cinematic photography, pop-culture-like visual jokes and a deliberately more colorful illustration interlude.

**Transfer:** Use original conceptual scenes about the new product's work, not generic office stock. Minimum acceptable illustration: a coherent isometric assembly with thin outlines, dark green planes and a few orange joints.

**Build:** Construct isometric boxes and rails using SVG polygons on a near-black field, with 30-degree diagonals, thin low-contrast edges and orange circles at connectors. Put one focal assembly in the center and subordinate surrounding machinery.

### Icons

**Observed:** Northeast arrows repeat in dark circular disks, from 17px small rail graphics to 68px large continuation arrows. Capability icons are chunky, rounded, technical silhouettes in 64px pale tiles; benefit icons combine ink and orange.

**Transfer:** Use one consistent rounded arrow drawing and a small set of bold diagrammatic icons. Avoid delicate generic outline icons beside the thick, compact typography.

## Section recipes

How recurring sections are built.

### First screen: Sentence and sculpture opening

**Observed:** A slim light navigation bar puts the wordmark left, short section links across the center and a small orange contact capsule right, separated from the page by a hairline. On the paper canvas a centered 72px/1 sentence occupies roughly two thirds of the width in three close lines. A 640px support paragraph follows with 24px separation, then a Primary button. A pale circular stage starts below the action with 64px breathing room; its glassy sculpture rises through the bottom of the first screen. Within 900px the navigation, complete headline, support, action and upper portion of the object are visible; the full 900px object stage and next chapter remain below. Back-to-front layers are paper, pale disk, sculpture, then text and navigation above.

**Transfer:** Write a direct proposition that can hold three balanced lines and create a translucent original object using Translucent idea sculpture. Detail pages instead open with a left-aligned 160px lowercase noun, a small chapter number near the lower edge and a 448px-tall masthead before editorial content. Dark editorial pages open with oversized neon lettering, a centered subtitle and one reverse action.

**Avoid:** Do not substitute a two-column app-dashboard hero, several competing CTAs or a tiny illustration tucked beside a paragraph.

**Text style:** `display` — AeonikPro 500 · 72px/1 · tracking -0.025em

### Numbered split feature

**Observed:** Chapter rail crosses the section top; below it equal columns place a 36px heading, 21px paragraph and Primary button left, and Gray graphic panel right. Copy stacks use 32px gaps and each column has 24px padding. The panel is 672px square at desktop.

**Transfer:** Explain one capability or principle with one sparse dot-based visual; alternate the subject matter without making each section a new design system.

**Text style:** `heading` — AeonikPro 500 · 36px/1.1 · tracking -0.0125em

### Paired audience pathways

**Observed:** Two Audience cards sit across the wide container with 48px gutters. Each card pairs a top-left heading and support line with a related orange modular object below.

**Transfer:** Offer two meaningful routes into the product using visually related metaphors.

### Centered proof carousel

**Observed:** A centered heading, paragraph and Primary button precede Story cards. The central card is sharp while neighboring cards blur back; 48px dark circular arrows sit at the edges.

**Transfer:** Feature a small number of concrete outcomes with one clear active story.

### Proof mosaic

**Observed:** Statistic tiles and portrait media share a five-column grid with 8px gutters. The leading number tile spans two columns, and text labels sit at the bottom rather than directly under numerals.

**Transfer:** Pair quantitative proof with equally sized evidence imagery; preserve varied tile spans instead of turning it into a uniform row of counters.

### Contact scene exchange

**Observed:** A centered light invitation uses a 36px heading with expressive braces, 21px supporting copy, a Primary button and a 420px portrait. The following full-width Orange contact field reverses the text and uses Framed contact portrait above the invitation copy.

**Transfer:** Provide a human route and a contrasting self-serve route when both are real. Otherwise use the orange scene for the strongest conversion path without inventing an assistant.

### Dark emblem closing

**Observed:** Dark closing field carries a centered two-line 72px statement, a 640px-wide 21px paragraph and an orange Primary button. Beneath it the Luminous mounted emblem fills a 900px media stage on a broad near-black circular surface. The page ends with the artwork rather than footer columns.

**Transfer:** Use the final statement to express a sharper point of view, then leave the luminous product-specific emblem as the last impression.

**Text style:** `display` — AeonikPro 500 · 72px/1 · tracking -0.025em

### Editorial statement and continuation

**Only for:** detail pages

**Observed:** A left-aligned 72px sentence spans the upper portion of a section; support sits in the right half after 48px vertical separation. An inline Primary button can interrupt the sentence. End with Next chapter link, using a small brace label and 160px destination.

**Transfer:** Use for deeper explanations and adjacent product journeys; do not require the same chapter order.

**Text style:** `editorial-heading` — AeonikPro 500 · 72px/1 · tracking -0.03em

### Dark chapter essay

**Only for:** dark editorial pages

**Observed:** Chapter interludes use centered 16vw headings with 0.8 line height, a small chapter caption and generous dark space. Centered 28px introductions lead into a 688px ruled reading column with 36px headings and 21px paragraphs; orange phrases interrupt the argument. Full-width cinematic or technical images break the narrow column. The final orange band uses three code-like lines at 4.45vw, with 128px top and 24px side/bottom padding.

**Transfer:** Use the darker mode for a long opinionated editorial narrative, not as the default landing-page skin.

**Text style:** `chapter-display` — AeonikPro 500 · 230.4px/0.8 · tracking -0.025em

## Page flow

**Storyline:** Direct promise → pathways into the offering → methods and tangible proof → people or operating principles → contact invitation → distinctive visual ending.

### Broad marketing landing page

1. **Promise** — Centered sentence with one action and a translucent object emerging below.
2. **Audience pathways** — Two square cards with related orange object arrangements.
3. **Capability and proof** — Numbered split diagrams, a centered story carousel and a tight quantitative mosaic.
4. **Trust** — People and operating principles appear as proof, not as a wall of generic logos.
5. **Conversion** — Human and contrasting self-serve contact scenes.
6. **Closing point of view** — Dark centered invitation followed by a luminous mounted emblem.

**Transfer:** Adapt the narrative to the product's strongest proof; preserve the object, chapter rails, dot diagrams and artwork ending without enforcing a fixed section count.

### People and expertise detail

1. **Identification** — Large lowercase masthead and three adjoining studio portraits.
2. **Credibility** — Large sentence statement and right-column explanation.
3. **Complementary strengths** — Ruled paired qualities, each linked by an expressive ampersand and supporting copy.
4. **Scale of delivery** — Network explanation and full-width supporting media.
5. **Conversion and continuation** — Inline action within a large sentence, then a monumental next-destination link.

**Transfer:** Explain the strengths and organization behind a product, ending with a useful continuation rather than conventional footer navigation.

### Service proposition detail

1. **Promise** — Lowercase masthead, large editorial sentence and offset support.
2. **Visualization** — Full-width dark isometric work scene.
3. **Differentiation** — Inline action statement and a square technical-object metaphor.
4. **Objection handling** — Left question with orange answer beside a two-by-two benefit-card grid.
5. **Audience fit** — Editorial introduction and paired audience cards.
6. **Continuation** — Monumental next-destination link.

**Transfer:** Move from outcome to operating advantages to fit, using technical metaphors rather than feature screenshots alone.

### Long-form brand argument

1. **Provocation** — Neon word artwork above centered subtitle and reverse action.
2. **Argument** — Narrow ruled essays with orange emphasized phrases, alternating with wide media.
3. **Chapter reset** — Giant centered chapter nouns separate major ideas.
4. **Explanation and proof** — Technical diagrams, dark raised panels and cinematic imagery expand the claims.
5. **Conversion** — Human invitation followed by orange framed contact scene.
6. **Closing credo** — Three lines of white code-like language on orange.

**Transfer:** Reserve for a strong sustained editorial voice; retain visual pauses and do not carry its extreme length into an ordinary landing page.

### Capability directory detail

1. **Identification** — Giant lowercase masthead with chapter number.
2. **Method demonstration** — Three ruled rows with dark progress-pill labels beside a glassy object stage.
3. **Rationale** — Large sentence and offset supporting explanation.
4. **Capability inventory** — Three-column hairline grid with pale icon tiles and concise descriptions.
5. **Objection handling** — Question and sparse dot diagram, followed by a specialist invitation.
6. **Continuation** — Monumental next-destination link.

**Transfer:** Make a broad product's scope legible with a compact directory while giving methods and specialist cases their own stages.

## Writing

Confident, conversational and technically literate, with blunt assertions and occasional mischievous metaphors. It rejects polished corporate vagueness in favor of practical outcomes, while the dark editorial voice is deliberately more provocative.

**Do not copy:** Do not reuse the brand name, logo, proprietary artwork, named assistant, team identities, portfolio names, statistics, years of experience or delivery claims. Source quotations are tone examples only, not copy for a new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the team or maker and you for the reader; speak directly about what the reader can accomplish.
- **Rhythm:** Mix short lowercase navigation nouns with complete sentence headlines. Support paragraphs usually explain one point in two to four sentences; actions are often a single lowercase word.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening proposition | A full sentence names what the maker does and delivers, without a slogan fragment. | 12–18 words | “We are an engineering-driven company that effectively delivers deep tech products.” |
| Editorial headline | A concrete metaphor divides the reader's role from the product's role. | 7–12 words | “The floor is yours, we'll handle the backstage.” |
| Operating promise | A plain assertion with repetition that makes accountability memorable. | 8–12 words | “When we say we’ll deliver something, we deliver it.” |
| Support | Explain the method with tangible verbs and one short outcome. | 12–30 words | “We strip a problem down to its core and then solve it with technology.” |
| Primary action | Short lowercase conversational verb; let surrounding text supply context. | 1–2 words | “more”<br>“talk”<br>“connect” |
| Editorial challenge | A punchy contrarian label introduces an argument rather than a feature list. | 3–7 words | “startup agnostic, delivery oriented” |

**Words and phrasing to use:** deliver; build; solve; real; behind the scenes; no fluff; get things done; concrete physical metaphors

**Avoid:** seamless synergy; revolutionary ecosystem; unsubstantiated superlatives; formal institutional address; generic future-of-everything slogans

**Rules:**

- Support confidence with a method, outcome or proof immediately nearby.
- Use playful technical punctuation sparingly at meaningful nouns, not around every sentence.
- Keep the everyday landing voice direct and friendly; reserve censored profanity and extended cultural jokes for explicitly editorial content.
- A metaphor should clarify how something works, not replace an explanation.

## Do's and Don'ts

### Do

- Keep the default opening at 72px/1 and weight 500, with a 640px support measure.
- Use 24px page insets and 1px rules to make chapter boundaries visible.
- Give orange actions a dark circular arrow head and 44px capsule height.
- Stage important graphics in 20px-radius pale gray squares rather than floating arbitrary assets.
- Set proof numbers at 7vw and anchor their 32px captions to the bottom of tiles.
- Use the 8px mosaic gap to make mixed portraits and stat spans read as one proof field.
- Give the ending enough room for a 900px artwork stage and its broad dark circular backing.
- Keep 160px lowercase mastheads and next-page links scoped to deeper detail journeys.

### Don't

- Do not make all headlines bold 700; the identity depends on medium 500 and tight spacing.
- Do not replace 21px main paragraphs with tiny 14px startup-template body copy.
- Do not make every card a white floating panel with shadows; depth belongs inside the artwork.
- Do not distribute orange evenly across every section; keep it concentrated in actions, objects and contact fields.
- Do not turn chapter numbers into oversized decorative watermarks; they are compact 24px markings.
- Do not use carousel blur on the active story or across ordinary photographs.
- Do not collapse stat captions immediately below the numerals; the open middle is part of the tile.
- Do not append a dense multi-column footer after the luminous closing artwork or monumental continuation link.

## Motion and responsive

### Motion

**Observed:**

- Actions and surfaces declare opacity transitions of 0.3s and some color transitions of 0.15s.
- Graphic objects and portraits use video or vector animation; the contact composition uses sticky overlapping scenes, and dark chapter headers are sticky.
- The story carousel distinguishes an active sharp card from blurred, reduced-opacity neighboring cards.

**Transfer:**

- Keep movement object-led: reveal the translucent sculpture, expand dots into labels and exchange contact scenes without making every paragraph a separate spectacle.
- Preserve a fully readable settled state for the headline and action.

**Unknown:**

- Complete scroll timelines and which easing applies to each scene are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 768px, 991px, 992px, 1280px and 1920px.
- Stat size uses 7vw, dark chapter headings 16vw and the code-like closing 4.45vw.

**Transfer:**

- On narrow screens, preserve promise → action → object reading order and stack split graphics below their explanatory text.
- Reduce mosaic columns while retaining at least one wider proof tile; keep chapter label and number on opposite sides of the same rail.
- Fit the monumental continuation word to the available width without losing the attached arrow.

**Unknown:**

- Exact mobile type values, navigation behavior and grid breakpoints are not established; narrow-screen arrangements above are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
