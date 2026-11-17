# Allier Ho — sculpture meets italic

## Overview

An art-directed editorial style that pairs organic black sculpture with delicate, mixed-italic serif headlines and tiny uppercase sans-serif annotations. Pale gray and near-white space dominate, interrupted by dusty purple and soft sage, while photography and dimensional artwork carry the stronger colors. It suits design-led products, creative tools and visually rich services whose work can speak through large, unboxed images rather than dense feature cards.

### Essentials

- A sculptural opening rather than a centered sales stack: a full-bleed 900px stage carries a tall black perforated object, with a 604×480px dusty-purple statement panel anchored at the lower right and 40px outer margins. Use an original dimensional silhouette or a shaded SVG mesh when no product object exists.
- Headlines sound like a sentence with an italic turn: Crimson Pro 300 at 50px/0.95 with -1.5px tracking in the opening, then 44px/1.15 with -1.5px tracking for section leads. Italicize a meaningful phrase within the same line, not a separate decorative subtitle.
- Actions stay smaller than the artwork: 34px-high capsules, 200px radius and 10px 18px padding, with Manrope 600 at 12px/1.2 and 0.8px uppercase tracking. The pale gray filled capsule is the default; the purple stage uses a fine light outline.
- Color is concentrated in one statement plane and the media: the purple opening panel occupies about 22% of the first screen, with sage text; most of the remaining page uses #fcfcfc, dark text and borderless rectangular images.
- The gallery has a deliberate imbalance: 40px side margins, 20px paired-image gutters, tiny uppercase captions 20px below images, and generous 120–200px chapter breathing room. Unequal widths and alternating alignments replace a uniform card dashboard.
- The ending becomes an artwork: a fine rule and three editorial columns lead into an expansive void, then a 1360×178px soft, grainy, dimensional word sculpture at the bottom. Create an original product-name sculpture or mask cloudy light through chunky custom lettering; this closing device remains part of the style. 

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty purple | `#6c5f7d` | `--color-purple` | surface, text | Opening statement plane and closing invitation text. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale sage | `#cee6cc` | `--color-sage` | text | Serif statement over the purple plane. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black action ink | `#000000` | `--color-action-ink` | text, action, link | Capsule labels, navigation on light backgrounds and direct contact links. |
| Deep heading ink | `#1c1c1c` | `--color-heading-ink` | text | Default editorial section headings on near-white. |
| Charcoal ink | `#262626` | `--color-ink` | text, background | Primary compact text. Also the full dark canvas for biographical storytelling. |
| Metadata gray | `#a8a8a8` | `--color-muted` | text, border | Categories, small labels and fine recognition-list rules. |
| Inactive navigation gray | `#b2b2b2` | `--color-inactive-nav` | text, link | Secondary navigation text over the sculptural opening; white lettering is used for the identity. |
| Neutral glass wash | `#d9d9d9` | `--color-glass` | surface | Neutral header glass, using rgba(186,186,186,0.545) over light material; its appearance follows the image behind it. |
| Pale control gray | `#e6e6e6` | `--color-control-wash` | surface, action | Visible black at 10% over white for filled capsules; the same translucent recipe takes on the surrounding canvas. |
| Near-white canvas | `#fcfcfc` | `--color-canvas` | background | Default gallery and closing canvas. |
| White | `#ffffff` | `--color-white` | background, text | Text over the opening image and purple stage; also the case-study canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| biographical contact artwork | Electric citron | `#e6ff00` | `--color-electric` | text, accent | Oversized playful greeting over a stone photograph, not a general CTA color. |
| long-form case studies and biographical stories | Narrative gray | `#919191` | `--color-body-muted` | text | Longer sans-serif narratives and the dark biographical chapters. |
| project archives | Soft archive rule | `#dbdbdb` | `--color-archive-rule` | border | Visible #aaaaaa at 40% over the near-white canvas for archive separators. |

## Typography

- **Crimson Pro** — Statements, section leads, editorial summaries and closing invitation. Light, literary serif with expressive true italics and tightly fitted large text. Font stack: "Crimson Pro", Georgia, serif.
- **Manrope** — Navigation, small uppercase labels, compact descriptive copy and case-study titles. Clean geometric sans; small text uses a firm semibold weight rather than a light gray hairline. Font stack: "Manrope", Arial, sans-serif.
- **Azeret Mono** — Live local-time numerals beside the location in the closing section. Crisp compact monospaced numerals. Font stack: "Azeret Mono", ui-monospace, monospace.
- **Vampiro One** (only for biographical contact artwork) — Two-line informal greeting layered on photography. Bold slanted brush-like display lettering with a friendly retro quality. Font stack: "Vampiro One", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| hero | Crimson Pro | 300 | 50px | 0.95 | -0.03em | Primary statement within the purple opening plane. |
| hero-italic | Crimson Pro | 300 italic | 50px | 0.95 | -0.03em | Opening phrase embedded in the primary statement. |
| heading | Crimson Pro | 300 | 44px | 1.15 | -0.034em | Default section lead and closing invitation. |
| heading-italic | Crimson Pro | 300 italic | 44px | 1.15 | -0.034em | Emphasized phrase inside a section lead or the second closing line. |
| navigation | Manrope | 600 | 14px | 1 | 0.086em, uppercase | Identity and three short navigation links. |
| label | Manrope | 600 | 12px | 1.2 | 0.067em, uppercase | Eyebrows, image captions, categories, compact action labels and contact links. |
| body | Manrope | 600 | 12px | 1.8 | 0.03em | Compact descriptive copy and footer introduction. |
| clock | Azeret Mono | 400 | 12px | 1.2 | normal | Location-adjacent time. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| biographical contact artwork | greeting | Vampiro One | 400 | 100px | 1.2 | normal | Playful two-line contact artwork. |
| case studies | case-title | Manrope | 500 | 70px | 1 | -0.0214em, uppercase | Left-aligned project name beneath a category label. |
| project collections | collection-title | Crimson Pro | 300 | 70px | 1 | -0.0429em | Centered collection title. |
| project collections | collection-title-italic | Crimson Pro | 300 italic | 70px | 1 | -0.0429em | Opening adjective inside a centered collection title. |
| case-study endings | next-title | Crimson Pro | 300 | 30px | 1.2 | -0.0333em | Centered next-project description above its preview. |
| case studies and project archives | editorial-summary | Crimson Pro | 300 | 22px | 1.25 | -0.0227em | Case-study summary, outcome paragraphs and archive titles. |
| case studies | editorial-summary-italic | Crimson Pro | 300 italic | 22px | 1.25 | -0.0227em | Short outcome label above serif narrative. |
| biographical stories and case studies | narrative | Manrope | 500 | 14px | 1.5 | 0.01em | Longer personal paragraphs and centered campaign support copy. |

**Notes:**

- Use true italics within a single semantic headline. Keep regular and italic portions the same size, weight and baseline.
- The large serif is light and tightly tracked; compact Manrope copy is semibold and positively tracked. Do not make the tiny labels mono just because the clock is mono.
- The closing word sculpture is image-like custom lettering, not another live heading recipe. Its width and material matter more than matching a text font.

## Layout

**Density:** Airy, with compact type attached to very large imagery and long intervals of near-white space.

### Spacing

**Spacing system:**

- **rhythm** 20px — Dominant layout rhythm: 40px margins, 60px offsets, 120px section starts and 200px chapter endings; 10px is the common half-step.

| Value | Use |
| --- | --- |
| 6px | Caption title to category gap. |
| 10px | Tight label stacks and small component gaps. |
| 20px | Paired-media gutters, image-to-caption gap and heading-to-action gap. |
| 40px | Page side padding and statement-plane inset. |
| 60px | Closing section top padding and compact narrative separation. |
| 80px | Vertical padding around a narrow case-study text interlude. |
| 100px | Centered section header to featured work. |
| 120px | Major light-section opening padding. |
| 180px | Intervals between asymmetric gallery rows. |
| 200px | Deep section endings and archive-to-closing separation. |

### Containers and grids

- **page frame**: side padding 40px. Full-width layout with 1360px of content at a 1440px viewport; retain broad side margins rather than a narrow centered marketing container.
- **paired gallery**: 2 columns · gap 20px. Two 670px-wide images on the desktop frame, with captions aligned to each image's left edge.
- **statement plane**: max width 604px · side padding 40px. Lower-right opening panel, 480px tall on desktop, with a 524px inner text measure.
- **closing columns**: 3 columns · gap 20px. Compact introduction and contact columns occupy the left two thirds; a roughly 450px serif invitation occupies the right third.
- **narrative interlude** (only for case studies): max width 450px. Centered short case-study text with 80px vertical padding.
- **biographical column** (only for biographical stories): max width 300px. A narrow image-and-copy column in the right half, balanced against a chapter heading on the left.

## Corner radius

| Element | Radius |
| --- | --- |
| capsules | 200px |
| media and statement planes | 0px |

## Surfaces and depth

### Surfaces

#### Near-white canvas · level 0

**Use:** Default light marketing ground.

**CSS:** `background: #fcfcfc`

**Observed:** Content is grouped through space and alignment, not raised white boxes.

**Transfer:** Keep long light stretches between the opening artwork and closing artwork.

#### Purple statement plane · level 1

**Use:** The principal colored content plane in the opening.

**CSS:** `background: #6c5f7d; color: #cee6cc; border-radius: 0px`

**Observed:** A flat opaque rectangle lies in front of the black sculpture; it is not tinted glass.

**Transfer:** Preserve the solid purple-to-sage pairing when changing the message.

#### Navigation glass · level 2

**Use:** Fixed navigation over sculptural imagery.

**CSS:** `background: rgba(186, 186, 186, 0.545); backdrop-filter: blur(38px)`

**Observed:** The translucent strip has no drop shadow. Light editorial views use near-white navigation instead, with a declared 70px backdrop blur.

**Transfer:** Keep glass restricted to the thin navigation and compact actions; do not spread it across content cards.

#### White case canvas · level 0

**Only for:** case studies

**Use:** Long image-led project narratives.

**CSS:** `background: #ffffff`

**Observed:** Flat white surrounds tightly stacked visual documentation.

**Transfer:** Let the project's own media supply saturated color.

#### Charcoal story canvas · level 0

**Only for:** biographical stories

**Use:** Immersive narrow-column chapter sequence.

**CSS:** `background: #262626; color: #ffffff`

**Observed:** White serif chapter labels, gray narrative copy and small isolated rectangular photographs sit on a continuous dark ground.

**Transfer:** Use this as a distinct story-page theme, not an alternating band on every landing page.

## Components

### Fixed navigation

**Use:** Persistent identity and access to three destinations.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 64px; padding: 20px 40px; display: flex; justify-content: space-between; align-items: center; z-index: 10; background: rgba(186, 186, 186, 0.545); backdrop-filter: blur(38px)`

**Text style:** `navigation` — Manrope 600 · 14px/1 · tracking 0.086em · uppercase

**Observed:** Identity is left-aligned; a compact group of links sits at the right. Over the opening, the identity is white and secondary links are pale gray; on light editorial content all lettering reads black.

**Transfer:** Use short destination names and keep navigation secondary to the artwork.

### Filled capsule

**Use:** Default secondary exploration and proof action.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 34px; padding: 10px 18px; border-radius: 200px; background: rgba(0, 0, 0, 0.1); backdrop-filter: blur(40px); color: #000000`

**Text style:** `label` — Manrope 600 · 12px/1.2 · tracking 0.067em · uppercase

**Observed:** The capsule hugs its label rather than filling a column. It normally sits centered beneath a serif section lead.

**Transfer:** Use brief verbs and a single clear destination.

### Outline capsule

**Use:** Exploration action inside the opening statement plane.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 34px; padding: 10px 18px; border-radius: 200px; background: transparent; backdrop-filter: blur(40px); color: #ffffff; border: 1px solid rgba(255, 255, 255, 0.3)`

**Text style:** `label` — Manrope 600 · 12px/1.2 · tracking 0.067em · uppercase

**Observed:** A faint light outline contains the white label; the action is aligned with the left edge of the statement text and sits near the panel's bottom.

**Transfer:** Keep this low-contrast treatment on the colored plane, rather than making a large contrasting conversion button.

### Project tile

**Use:** Large linked visual proof with restrained captions.

**CSS:** `display: flex; flex-direction: column; gap: 20px; overflow: hidden; border-radius: 0px`

**Text style:** `label` — Manrope 600 · 12px/1.2 · tracking 0.067em · uppercase

**Observed:** Media comes first, followed by an uppercase descriptive title and a gray category with a 6px internal gap. There is no enclosing border, shadow or colored card body. Images commonly use a roughly 1.42:1 landscape proportion.

**Transfer:** Present a real result, product scene or crafted visualization; keep all explanatory copy outside the image.

### Contact underline

**Use:** Direct email and social links in the closing columns.

**CSS:** `display: flex; flex-direction: column; align-items: center; padding: 6px 0px 3px; color: #000000`

**Text style:** `label` — Manrope 600 · 12px/1.2 · tracking 0.067em · uppercase

**Observed:** A separate 1px dark rule underlines the compact label. Links stack with 10px gaps rather than becoming a large button row. White links are used on the dark story theme.

**Transfer:** Use real communication destinations and keep link length short enough to read as a compact marking.

### Closing colophon

**Use:** Main marketing and collection-page ending.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; padding: 60px 40px 20px; background: #fcfcfc; min-height: 810px`

**Text style:** `body` — Manrope 600 · 12px/1.8 · tracking 0.03em

**Observed:** A fine horizontal rule leads into three columns: a short introduction with location and live time below, stacked contact links, and a two-line purple invitation with an italic response. The bottom holds the word sculpture across nearly the full width.

**Transfer:** Use a concise product or company description and a human invitation; retain the large separation between the information and the closing artwork.

### Recognition row

**Only for:** biographical proof lists

**Use:** Compact credentials or public recognition.

**CSS:** `display: flex; flex-direction: column; height: 42px; color: #262626`

**Text style:** `body` — Manrope 600 · 12px/1.8 · tracking 0.03em

**Observed:** A long sentence-like title sits left, year near the right, and a small right arrow at the far edge. A 1px gray separator spans the row. Lists are grouped under tiny uppercase labels.

**Transfer:** Use verifiable credentials, publications or milestones; avoid turning the list into decorative badges.

### Archive row

**Only for:** project archives

**Use:** Secondary work that does not need a large image.

**CSS:** `display: flex; flex-wrap: wrap; align-items: center; height: 49px; color: #262626`

**Text style:** `editorial-summary` — Crimson Pro 300 · 22px/1.25 · tracking -0.0227em

**Observed:** Serif project title at left, uppercase category and year in the middle, and a concise destination at right. A faint full-width separator keeps the list editorial.

**Transfer:** Use the same compact row construction for a supporting resource archive.

### Next project

**Only for:** case-study endings

**Use:** Continue exploration after outcome and credits.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 50px`

**Text style:** `next-title` — Crimson Pro 300 · 30px/1.2 · tracking -0.0333em

**Observed:** An uppercase next label sits above a centered serif description constrained to 680px. A wide 1360×520px visual follows. This ending replaces the contact colophon on case-study pages.

**Transfer:** Link to one related story with a strong image; avoid a dense grid of recommendations.

## Imagery and graphics

### Black cellular sculpture

**Use:** Signature full-bleed opening object.

**Observed:** A glossy, irregular black membrane with large organic apertures twists vertically through a cool pale-gray field. Its top and bottom are cut off by the viewport, making it feel larger than the page. Soft reflections and tiny surface imperfections give it physical weight; the purple plane occludes its lower-right portion.

**Transfer:** Make an original object from the product's geometry or an abstract network of rounded voids. Minimum acceptable artwork is a shaded vector silhouette with nonuniform holes and convincing edge highlights, not a flat icon.

**Build:** Use an SVG viewBox of 1440 900. Draw a broad twisting central ribbon extending beyond the top and bottom, roughly from the lower-left third to the upper-right third. Subtract 10–14 unequal elliptical and rounded triangular holes with an evenodd path. Fill with near-black, then overlay narrow curved white reflections at 8–25% opacity, blur 2–8px, clipped to the ribbon. Place a very low-contrast cool-gray and lilac cloudy field behind it; retain broad empty space at left.

### Dimensional word sculpture

**Use:** Signature monumental closing artwork.

**Observed:** A single very wide row of chunky, swollen letters fills 1360×178px near the bottom. White, gray, beige and sage reflections are interrupted by a small citron glow. Slightly warped edges, diffuse shading and fine grain make the lettering look like soft translucent material rather than an ordinary logo.

**Transfer:** Create new chunky lettering for the new identity. Minimum acceptable treatment is custom outlined letterforms with clipped cloudy gradients and subtle grain, preserving the broad low silhouette.

**Build:** Set an original short identity in an extra-heavy rounded display construction, convert it to SVG paths and adjust each letter's contour slightly. Scale the combined paths into a roughly 7.6:1 strip. Clip several blurred overlapping white, warm-gray and sage ellipses inside the paths; add one small yellow light pool near the middle. Overlay a low-opacity SVG turbulence texture inside the mask and gentle inner-edge shading. Use no external drop shadow.

### Contextual work imagery

**Use:** Large project tiles and full case-study visual sequences.

**Observed:** Campaigns are shown in real bus shelters, tiled transit environments, streets and architectural spaces; the work itself can be vividly colored while its setting remains photographic. Other projects combine dimensional interface concepts with shallow-focus gallery spaces. Framing is straight-edged and image-first, ranging from paired 670×896px posters to 1360×901px context images.

**Transfer:** Show the new product operating in a credible physical or digital setting. Use original UI or product details, with the environment serving as scale and atmosphere; keep image-internal type separate from the site's own typography.

### Experimental printed graphics

**Use:** Offset visual counterpoint to polished project imagery.

**Observed:** A tall 540×797px piece shows repeated oversized vertical lettering in red and muted yellow-green, with rubbed print texture. It sits off-center in abundant near-white space rather than inside a card frame.

**Transfer:** Make an original typography study, material test or graphic experiment using the new product's language. It should feel tactile and exploratory, with one strong color pairing.

**Build:** Create a tall SVG poster divided into two vertical columns and stacked horizontal cells. Set a short original word rotated 90 degrees, nearly filling each cell. Use a saturated warm-red backing and muted yellow-green letters with dark offset edges. Add a clipped low-opacity grain mask and sparse horizontal abrasion marks.

### Small biographical vignettes

**Only for:** biographical stories

**Use:** Narrow story chapters on the charcoal canvas.

**Observed:** 300×330px images alternate between a softly lit portrait, pencil-and-paper sketches, glossy pink and citrus hearts, and mottled stone. Each is backed directly by charcoal, with gray paragraph text just below. The stone image carries a tilted electric-citron greeting.

**Transfer:** Use personally revealing but carefully framed original photographs and process details. The images should stay intimate instead of becoming full-bleed team banners.

**Build:** For the greeting vignette, place a rough natural-stone photograph inside a 300×330px rectangle. Overlay two short lines in Vampiro One at 100px/1.2, rotate the text group -10deg and color it electric citron. Keep the texture visible through the surrounding negative space.

### Physical editorial objects

**Only for:** project collections featuring tangible products

**Use:** Paired supporting product images.

**Observed:** Books and printed matter are photographed frontally or at an oblique tabletop angle against pale neutral grounds, with soft natural shadows and visible paper, cloth, foil and binding details.

**Transfer:** Photograph tangible products in restrained light; let material quality rather than decorative frames create depth.

### Icons

**Observed:** Icons are sparse: a simple downward arrow marks the opening's lower-left edge; small filled black right arrows of about 20×14px finish recognition rows. Most actions contain text alone.

**Transfer:** Use only directional glyphs when they clarify movement. Avoid a decorative feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Sculpture and statement opening

**Observed:** The first 900px form one full-width stage. Back to front: pale cool atmospheric image field, an enormous twisting black sculpture clipped above and below, a 64px Fixed navigation strip, left-side uppercase service annotations, then the Purple statement plane in the lower-right quadrant. The plane is 604×480px with 40px inset, leaving 40px to the viewport's right and bottom. The 50px mixed-italic statement spans about three lines at its top; Outline capsule sits near its bottom-left. A small down arrow finishes the opposite lower corner. The whole object, statement, annotations and action appear within the first screen; the light gallery starts below 900px.

**Transfer:** Preserve the full-screen object-versus-plane composition with an original product-inspired sculpture, using the shaded vector construction if necessary. Choose one concise positioning statement and a short category list, not a stack of support paragraphs. Collection pages instead open with a centered mixed-italic 70px title in a 432px-tall light field; case studies open with a category and left-aligned uppercase 70px name after substantial top space; biographical pages open on charcoal with an intimate image column opposite a chapter heading.

**Avoid:** Do not replace this with a centered headline above a small product mockup, a full purple background, or multiple competing CTA buttons.

**Text style:** `hero` — Crimson Pro 300 · 50px/0.95 · tracking -0.03em

### Editorial heading and featured pair

**Observed:** Near-white canvas begins with 120px top padding. A centered 44px serif sentence mixes roman and italic text; a Filled capsule sits 20px below. After 100px, two Project tiles share the 1360px frame with a 20px gutter. Labels sit outside the media.

**Transfer:** Use this composition for flagship product proof, customer stories or two complementary capabilities; keep the headline conversational rather than a taxonomy label.

**Text style:** `heading` — Crimson Pro 300 · 44px/1.15 · tracking -0.034em

### Offset experimentation stage

**Observed:** A centered mixed-italic 44px lead and Filled capsule precede a tall tactile graphic offset to the left, with a smaller companion visual offset to the right. Broad gaps and 200px bottom padding make the composition feel like a studio wall rather than a card grid.

**Transfer:** Show original process, a material study or an alternative product concept as a visual pause. Preserve the asymmetric scale relationship and physical texture.

**Text style:** `heading` — Crimson Pro 300 · 44px/1.15 · tracking -0.034em

### Invitation and word-art ending

**Observed:** Closing colophon occupies 810px. A thin rule sits above the information row; introduction, contact links and purple two-line invitation share the top. Location and a 12px mono clock sit below the introduction. The page then opens into a large quiet interval before the Dimensional word sculpture spans almost the entire bottom width, with about 20px bottom padding. The same ending serves marketing, biographical and collection pages.

**Transfer:** Retain the invitation and expansive word-art payoff using the new identity. Choose truthful location or availability information; the final artwork should feel like a material sign-off, not a repeated navigation logo.

**Text style:** `heading` — Crimson Pro 300 · 44px/1.15 · tracking -0.034em

### Asymmetric collection gallery

**Only for:** project collections

**Observed:** The 40px page frame contains alternating unequal pairs, right-aligned single images, left-aligned smaller images and a centered feature. Examples include 816px right-aligned work, 544px left-aligned work and a 952px-wide feature. Rows are separated by 180px; every Project tile retains the same tiny caption hierarchy.

**Transfer:** Assign width by narrative emphasis rather than equalizing every item. Vary alignment while maintaining the shared outer frame.

**Text style:** `label` — Manrope 600 · 12px/1.2 · tracking 0.067em · uppercase

### Case narrative and visual chapters

**Only for:** case studies

**Observed:** A 70px uppercase sans title introduces a 22px light-serif summary with role metadata and a small Filled capsule at right. Large visual chapters follow at 1360px width with 20px bottom gaps; paired portrait media uses 670px columns. A centered 450px text interlude has 80px vertical padding. Outcome uses a 22px italic label, serif paragraphs, and compact credits in adjacent columns before Next project.

**Transfer:** Separate context, craft and outcomes. Let the visuals occupy most of the page; use compact factual metadata and restrained narrative rather than oversized performance counters.

**Text style:** `editorial-summary` — Crimson Pro 300 · 22px/1.25 · tracking -0.0227em

### Dark biographical chapters and light recognition

**Only for:** biographical stories

**Observed:** Charcoal story canvas holds a left chapter-label region and a right 300px image-and-copy column. Each chapter occupies about 900px vertically. A small uppercase label and white 44px serif title balance the intimate image. The last dark chapter adds the tilted greeting and contact links. A near-white recognition section follows with 120px top and 200px bottom padding, stacked 42px Recognition rows and 40px gaps between list groups.

**Transfer:** Use narrow chapters for origin, process, experience or people, then a factual proof list. Keep electric lettering confined to the personal contact vignette.

**Text style:** `heading` — Crimson Pro 300 · 44px/1.15 · tracking -0.034em

## Page flow

**Storyline:** Sculptural promise → selected visual proof → a glimpse of process or personality → human invitation and material sign-off; deeper stories expand proof into context, craft and outcomes.

### Marketing introduction with a strong visual identity

1. **Promise** — Full-screen sculpture, lower-right serif statement and one compact exploration action.
2. **Selected proof** — Centered editorial lead followed by a pair of large linked visuals.
3. **Creative range** — Asymmetric experimental media under a mixed-italic invitation to explore.
4. **Closing call** — Three-column contact colophon and monumental textured word artwork.

**Transfer:** Use a visual metaphor for the product and let selected proof do most of the persuasion; adapt the number and position of proof sections to the offer.

### An in-depth case study that makes craft and execution tangible

1. **Context** — Spacious category and uppercase title, serif brief, role metadata and compact external action.
2. **Demonstration** — Large contextual imagery and paired creative executions.
3. **Narrative pause** — Short centered text explains the creative idea.
4. **Execution proof** — Successive full-width real-world applications.
5. **Outcome** — Serif outcome copy alongside factual credits and year.
6. **Continuation** — Centered next-story title and a wide image preview.

**Transfer:** Tell one coherent transformation with original work; replace claims and credits with verifiable project details.

### A personal or company story with a distinct darker atmosphere

1. **Origin** — Intimate portrait with narrow gray copy and opposite white chapter title.
2. **Development** — Process imagery and experience chapters across a continuous charcoal field.
3. **Human invitation** — Tilted expressive greeting on stone with direct contact links.
4. **External proof** — Light lists of recognition, speaking and publications.
5. **Closing call** — Shared contact colophon and dimensional identity artwork.

**Transfer:** Apply the dark theme to a focused origin story, then return to the light system for factual proof and closure.

### A browsable collection whose hierarchy comes from image scale

1. **Orientation** — Small category above a centered mixed-italic serif title.
2. **Breadth of proof** — Unequal image pairs and alternating isolated features, separated by 180px.
3. **Supporting archive** — Compact serif-title rows with category, year and destination.
4. **Closing call** — Shared light invitation and dimensional word-art ending.

**Transfer:** Curate visual weight deliberately, using larger pieces for the strongest proof rather than flattening all items into equal tiles.

## Writing

Warm, visually literate and quietly assured. The copy pairs personal curiosity with clear descriptions of what the work changes, using invitations rather than hard-selling commands.

**Do not copy:** Do not reuse the identity, wordmark artwork, personal biography, email address, client names, campaign lines, project claims, awards, credits or dates. Source quotations below illustrate rhythm only; write original content and substantiate every new claim. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Editorial descriptions often speak in third person; personal stories use first person. Brief direct invitations address the reader naturally, with occasional contractions.
- **Rhythm:** Sentence-like serif headlines are short but not slogan fragments. Small captions can be longer descriptive clauses; actions stay at one to three words. Longer explanations use compact paragraphs rather than many subheads.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | An italic descriptive phrase turns into a roman statement of focus. | About 10–16 words | “A multidisciplinary creative centered on the intersection of brands & experiences.” |
| Section lead | A conversational invitation or statement with one expressive italic phrase. | About 4–8 words | “See the latest & greatest”<br>“Experimentation is always celebrated here.” |
| Project caption | Active gerund plus a concrete change or outcome. | About 7–15 words | “Bringing the Android rebrand to life through a fresh online experience”<br>“Transforming PST from a museum exhibit to a modern cultural icon” |
| Action | Short unforced exploration verb. | 1–3 words | “view all work”<br>“Explore playground”<br>“learn more” |
| Closing invitation | A short question followed by a contracted human response. | Two short lines | “Building something?”<br>“Let's chat.” |

**Words and phrasing to use:** explore; craft; experience; shapes; visual language; bringing to life; building; conversation

**Avoid:** revolutionary; game-changing; dominate; supercharge; unprecedented; buy now

**Rules:**

- Make captions describe the change shown in the image, not just name a feature.
- Keep uppercase a typographic treatment of labels and captions, not the tone of paragraph copy.
- Use a contraction or friendly question in the closing invitation.
- Let factual proof remain factual; do not invent numerical results to fill an otherwise image-led story.

## Do's and Don'ts

### Do

- Keep the main statement at 50px Crimson Pro 300 with 0.95 line height and a meaningful italic phrase.
- Use 44px/1.15 serif section leads and give their compact exploration action a 20px gap.
- Keep the 40px side frame consistent across imagery, rules and closing artwork.
- Use 20px paired-image gutters and 20px image-to-caption spacing.
- Keep rectangular media and purple statement surfaces at 0px radius.
- Use Manrope 600 at 12px for uppercase annotations, not a default 16px UI scale.
- Retain an original dimensional word artwork at the close, with a broad low silhouette.
- Scope the charcoal narrative theme and electric greeting to personal storytelling.

### Don't

- Do not turn the 34px capsules into oversized 56px filled conversion bars.
- Do not make the purple statement plane translucent; it must clearly occlude the sculpture.
- Do not introduce card shadows or rounded panel corners into the gallery.
- Do not distribute sage and purple fills across every section; neutral page space is the dominant ground.
- Do not set whole headlines in bold Manrope on the default marketing page; the 70px uppercase sans belongs to case-study titles.
- Do not place paragraph copy on top of project images; the normal caption sits outside the media.
- Do not make the entire site dark because the biographical story is charcoal.
- Do not add a colorful feature-icon grid; the icon language is almost entirely directional. 

## Motion and responsive

### Motion

**Observed:**

- No action transitions or content animations have established durations or easing recipes. Navigation remains fixed as the content moves behind it.
- The biographical chapter title changes as the narrow story column advances; the precise transition mechanism is not established.

**Transfer:**

- Keep the sculpture and statement readable as a complete static composition.
- Keep the navigation attached to the viewport and let editorial imagery provide the visual change during scrolling.

**Unknown:**

- Object animation, chapter-transition timing, hover and focus-visible styling are not established. No timing curve is prescribed.

### Responsive

**Observed:**

- Width breakpoints are declared at 809px, 810px, 1199px and 1200px.

**Transfer:**

- On narrower screens, preserve the hierarchy of sculpture behind statement rather than merely shrinking the desktop panel and 50px type.
- Stack paired media and closing columns when necessary, keeping captions attached to their images and the dimensional word artwork as a distinct ending.
- For narrow biographical stories, place the chapter label directly before its corresponding image and paragraph rather than retaining two remote columns.

**Unknown:**

- Exact mobile type sizes, side margins, navigation behavior, image substitutions and breakpoint-specific layouts are not established. The narrower-screen rules are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
