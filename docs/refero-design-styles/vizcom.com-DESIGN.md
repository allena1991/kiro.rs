# Vizcom — sketch into substance

## Overview

A design-studio sensibility that moves between warm drawing paper and charcoal workspaces. Rounded grotesk typography, occasional brush lettering, fine construction grids and tactile product renders make technical software feel like a creative medium. The atmosphere is spacious and demonstrative rather than dashboard-dense, with restrained blue controls and a saturated blue finale.

### Essentials

- The promise becomes a word sculpture: an almost full-width black headline on warm paper, with one brush-drawn word and a sketched object crossing in front; use an artwork area roughly 1280px wide rather than a conventional text-and-image split.
- The studio changes lighting as the story develops: warm paper for the theatrical opening, #191919 for most explanatory content, #242425 for tools and frames, and #1145a0 for the full-width ending. Blue is concentrated in small actions until that final band.
- Headings feel rounded rather than heavy: Matter at 500, 56.3px/1.1 and -0.01em tracking; supporting statements use 19.9px/1.3 at 400. Brush lettering interrupts selected promises, not everyday paragraphs.
- Controls look like small pieces of equipment: blue rectangular actions with 8px corners, a neighboring outlined action, and a compact dark floating navigation bar with 16px corners; no pill-button system.
- A working canvas is part of the identity: low-contrast rectangular grids and dot patterns sit behind staggered media frames, floating tool fragments and the central object. When there is no physical product, use a sketched diagram becoming a finished interface or output.
- The ending is a second poster: a blue link-and-newsletter field above an oversized cream slogan, clipped along its lower edge, followed by a 50px charcoal legal strip. Preserve the monumental type device with new words.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Poster blue | `#1145a0` | `--color-footer` | background | The large closing navigation field; not a general feature-card fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control blue | `#4586da` | `--color-blue` | action, accent | Compact conversion controls and small utility accents. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal canvas | `#191919` | `--color-canvas` | background, text | Default explanatory canvas and inverse text on light sections. |
| Tool charcoal | `#242425` | `--color-panel` | surface, border | Navigation, feature frames, plan cards and forms; also low-contrast separators on the dark canvas. |
| Soft dark edge | `#424140` | `--color-edge` | border | Visible approximation of paper at 20% opacity over charcoal; use rgba(232,227,221,0.2) for form outlines. |
| Warm gray | `#8d8a88` | `--color-muted` | text | Secondary descriptions, eyebrows and understated metadata. |
| Drawing paper | `#e8e3dd` | `--color-paper` | background, surface, border | Warm opening paper, newsletter input, pricing inset and pale comparison rules. The opening paper should feel softly lit rather than flat gray. |
| Warm white | `#f8f4f1` | `--color-text` | text | Main text, icons and monumental ending lettering on dark or blue backgrounds. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product capability directories | Directory edge | `#4d4c4a` | `--color-row-edge` | border | Paper at 25% opacity over charcoal for broad directory rows. |
| pricing pages | Comparison white | `#ffffff` | `--color-white` | background | Long comparison tables and their question section. |
| lead forms | Required red | `#e04f4f` | `--color-error` | text | Required field asterisks. |
| product demonstrations | Editor violet | `#4c4cef` | `--color-tool-purple` | action | Generative actions inside demonstrations only. |

## Typography

- **Matter** — All live marketing headings, paragraphs, navigation and controls. Rounded contemporary grotesk with a broad, open lowercase and gentle geometric construction. If unavailable, use **DM Sans**. Use 400 and 500; retain compact negative tracking on headings. Font stack: "Matter", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading | Matter | 500 | 56.3px | 1.1 | -0.01em | fixed | Main chapter titles, centered secondary-page promises, large testimonials and price numerals. |
| heading-small | Matter | 500 | 39.8px | 1.2 | -0.01em | fixed | Utility section titles and comparison introductions. |
| question | Matter | 500 | 23.8px | 1.3 | -0.01em | fixed | Question rows and medium repeated-item titles. |
| body-large | Matter | 400 | 19.9px | 1.3 | normal | fixed | Short support statements beneath or beside headings. |
| body | Matter | 400 | 16px | 1.3 | normal | fixed | Explanations, footer links, comparison cells and expanded answers. |
| action | Matter | 500 | 16px | 1 | normal | fixed | Standard conversion labels. |
| label | Matter | 500 | 14px | 1.3 | -0.02em | fixed | Navigation labels, feature-frame titles and form labels. |
| caption | Matter | 400 | 14px | 1.3 | -0.02em | fixed | Media descriptions, portrait credits and small supporting metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| product capability directories | directory-display | Matter | 500 | 88px | 1.1 | -0.01em | fixed | Oversized linked categories, subdued to 0.5 opacity at rest. |
| culture pages | values-title | Matter | 500 | 27.7px | 1.3 | -0.01em | size clamp(1.5rem, 1.3142rem + 0.4661vw, 2rem) | Left-hand principles in wide editorial rows. |
| forms | form-action | Matter | 500 | 16px | 1.3 | normal | fixed | Newsletter and lead-form submit controls. |
| proof and recruiting sections | eyebrow | Matter | 400 | 14px | 1.3 | 0.1em, uppercase | fixed | Restrained context above testimonials and recruiting promises. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the main hierarchy at weight 500; visual scale and spacing do the work instead of boldness.
- Headings use -0.01em tracking, small labels and captions -0.02em, while full-size body copy remains normally tracked.
- Treat brush emphasis and the oversized opening slogan as custom lettering artwork. Use a forward-leaning, dry-edged brush word beside clean grotesk words; do not change the whole text system to a script font.
- The opening poster lettering has roughly 230px-tall visible letterforms at 1440px width. Fit the artwork to the available width; ordinary section titles remain at the heading recipe.

## Layout

**Density:** Airy at the chapter level, compact inside controls and media captions; large dark pauses give the images room to read.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight label stacks, button pairs and footer link spacing. |
| 12px | Media-frame padding, navigation item padding and small control padding. |
| 16px | Grid gutters, form row gaps and question-row padding. |
| 23.9px | Heading-to-support gaps, card content spacing and portrait caption inset. |
| 31.9px | Support-to-action separation and larger text stacks. |
| 47.9px | Large internal gaps and bottom clearance beneath the opening actions. |
| 63.8px | Media separation and large panel padding. |
| 79.8px | Desktop page side padding. |
| 159.5px | Major explanatory chapter padding above and below. |

### Containers and grids

- **page-container**: max width 2560px · side padding 79.8px. Full-width chapters with an inner 1281px content area at a 1440px viewport.
- **demo-container**: max width 1440px · side padding 79.8px. Centered interactive demonstrations; do not stretch their internal tools indefinitely.
- **centered-copy**: max width 615px. Centered title and short support groups.
- **split-chapter**: 2 columns · gap 16px. Title and explanation on the left, questions or form on the right; each half is about 632px wide.
- **media-triad**: 3 columns · gap 16px. Outcome studies or tall story portraits, with overflow allowed for a slider.
- **plan-grid** (only for pricing pages): 4 columns · gap 16px. Equal-width plan summaries around 308px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 8px |
|  | navigation | 16px |
|  | form-fields | 4px |
| pricing pages | plan-cards | 6px |

## Surfaces and depth

### Surfaces

#### Dark workspace · level 0

**Use:** Main explanatory canvas.

**CSS:** `background: #191919; color: #f8f4f1`

**Observed:** Nearly black without a blue cast; panels are separated by a small luminance shift rather than shadows.

**Transfer:** Keep most of the long-form narrative on this canvas.

#### Warm drawing stage · level 0

**Use:** Theatrical opening.

**CSS:** `background: #e8e3dd; color: #191919`

**Observed:** Softly lit warm paper with very faint texture, black lettering and linework.

**Transfer:** Use a subtle paper texture or low-opacity grain, with no aged-paper stains.

#### Tool frame · level 1

**Use:** Feature media and grouped controls.

**CSS:** `background: #242425; box-shadow: none`

**Observed:** Low-contrast charcoal backing; media cards use square edges while the navigation and compact tools have their own radii.

**Transfer:** Use background contrast and narrow matte framing rather than elevation.

#### Construction field · level 0

**Use:** Working-canvas chapters.

**CSS:** `background-color: #191919; background-image: linear-gradient(rgba(232,227,221,0.035) 1px, transparent 1px), linear-gradient(90deg, rgba(232,227,221,0.035) 1px, transparent 1px); background-size: 49px 20px`

**Observed:** Fine rectangular linework behind staggered media, distinct from the subtler dot field behind demonstrations.

**Transfer:** Match the subdued line density; the grid must remain behind the content, not compete with it.

#### Blue poster field · level 0

**Use:** Closing footer.

**CSS:** `background: #1145a0; color: #f8f4f1`

**Observed:** Faint architectural column lines organize a saturated blue rectangle above a dark legal strip.

**Transfer:** Use the blue as a single confident ending rather than scattering equally saturated bands throughout.

#### Light comparison canvas · level 0

**Only for:** pricing pages

**Use:** Long feature tables and related objections.

**CSS:** `background: #ffffff; color: #191919`

**Observed:** The dark plan overview gives way to white comparison content and a warm-paper explanatory inset.

**Transfer:** Keep the pricing contrast change local to the decision-making material.

## Components

### Floating navigation

**Use:** Persistent orientation above the page stage.

**CSS:** `display: flex; background: #242425; border-radius: 16px; padding: 6px 8px 6px 23.9px; width: 856px`

**Text style:** `label` — Matter 500 · 14px/1.3 · tracking -0.02em

**Observed:** A centered compact bar with the wordmark at left, six text destinations in the middle, and login plus a blue action at right. It floats close to the top edge instead of filling the viewport width.

**Transfer:** Shorten the destination set before expanding the bar.

### Primary button

**Use:** Main conversion, paired with an outlined alternative.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #4586da; color: #f8f4f1; border-radius: 8px; padding: 12px 17.9px; gap: 6px`

**Text style:** `action` — Matter 500 · 16px/1

**Observed:** Compact blue rectangle; ordinary conversion rows are about 43px tall, with a smaller 38px navigation variant. Labels use clipped duplicate text layers for motion.

**Transfer:** Give the blue control the next practical step, not a vague slogan.

### Secondary button

**Use:** Alternative conversion beside the blue control.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: transparent; color: #f8f4f1; border: 1px solid #f8f4f1; border-radius: 8px; padding: 12px 17.9px`

**Text style:** `action` — Matter 500 · 16px/1

**Observed:** Outline rather than a second colored fill; switches to charcoal lettering and outline on the warm opening. Action pairs are separated by about 8px or 12px.

**Transfer:** Keep both actions similar in size, with color providing priority.

### Media frame

**Use:** Image-led capability explanation.

**CSS:** `display: flex; flex-direction: column; background: #242425; padding: 12px; gap: 23.9px`

**Text style:** `label` — Matter 500 · 14px/1.3 · tracking -0.02em

**Observed:** Large image or video above a compact title and small description, with a small utility icon at the lower right. Mixed landscape and portrait proportions produce a staggered canvas rather than identical tiles.

**Transfer:** Show a concrete output first; keep the text as a caption, not a sales card.

### Question row

**Use:** Objection handling in a split section.

**CSS:** `display: inline-flex; justify-content: space-between; align-items: center; padding: 16px 0px; width: 100%`

**Text style:** `question` — Matter 500 · 23.8px/1.3 · tracking -0.01em

**Observed:** Question at left, fine 16px plus at right, and an irregular hand-drawn horizontal rule below. Typical row pitch is 79px; answers expand in body text with a small action. The pricing variant uses dark text on white.

**States:** Declared: hover unknown; focus-visible outline 0.1em solid var(--color--focus), outline-offset 0.1em.

**Transfer:** Rebuild the rule as a subtle SVG path, not a thick decorative zigzag.

### Footer link column

**Use:** Compact navigation within the blue ending.

**CSS:** `display: flex; flex-direction: column; gap: 8px; color: #f8f4f1`

**Text style:** `body` — Matter 400 · 16px/1.3

**Observed:** A larger medium-weight category label sits above the link stack; four navigation groups are flanked by a brand area and a social/newsletter area.

**Transfer:** Keep link labels short enough to preserve the narrow columns.

### Newsletter field

**Use:** Email collection within the closing blue band.

**CSS:** `background: #e8e3dd; border: 1px solid rgba(232,227,221,0.2); border-radius: 4px; padding: 4px 8px; height: 44px; width: 224px`

**Observed:** A small pale field below social icons and a short invitation; the submit action sits on its own line beneath it.

**Transfer:** Keep this an unobtrusive utility within the footer rather than a separate large signup card.

### Form submit

**Only for:** forms

**Use:** Newsletter subscription and lead submission.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #4586da; color: #f8f4f1; border-radius: 8px; padding: 12px 16px; gap: 6px`

**Text style:** `form-action` — Matter 500 · 16px/1.3

**Observed:** Left aligned below fields. Lead-form submit is similarly compact, while the newsletter control has a distinctive warm hover color.

**States:** Declared: hover newsletter background rgba(255,134,98,1), white text and translateY(-1px); focus-visible outline 0.1em solid var(--color--focus), outline-offset 0.1em; active background rgba(51,125,220,1), translateY(1px), box-shadow none.

### Lead field

**Only for:** lead forms

**Use:** Business inquiry fields.

**CSS:** `background: #242425; border: 1px solid rgba(232,227,221,0.2); border-radius: 4px; padding: 8px 8px 4px; color: #f8f4f1`

**Text style:** `label` — Matter 500 · 14px/1.3 · tracking -0.02em

**Observed:** Labels sit above fields, not inside them; short name fields share a row, longer fields span the form. Inputs are 44px tall, with a 96px textarea. Required markers are red.

**Transfer:** Keep field rows tightly spaced at 16px within the much more spacious page composition.

### Plan card

**Only for:** pricing pages

**Use:** Parallel plan summaries.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; background: #242425; border-radius: 6px; padding: 23.9px 16px; gap: 31.9px`

**Text style:** `body` — Matter 400 · 16px/1.3

**Observed:** Four equal-width tall cards with plan name, large price or sales prompt, small billing qualifier, description, checkmarked inclusions and bottom action. No bright recommended-plan ribbon dominates the set.

**Transfer:** Align equivalent information vertically; preserve breathing room rather than packing every difference into the cards.

### Directory row

**Only for:** product capability directories

**Use:** A typographic index of audiences or capabilities.

**CSS:** `position: relative; padding: 39.9px 0px; border-bottom: 1px solid rgba(232,227,221,0.25)`

**Text style:** `directory-display` — Matter 500 · 88px/1.1 · tracking -0.01em

**Observed:** Broad full-width rows; huge linked category labels rest at half opacity. A related portrait-format image and short description belong to the interactive presentation.

**Transfer:** Use a small set of meaningful categories rather than ordinary feature bullets.

## Imagery and graphics

### Sketch becoming substance

**Use:** Signature opening and product demonstrations.

**Observed:** Black construction sketches of designed objects cross an oversized headline on warm paper. The central three-quarter-view object occupies about 530px by 300px, with adjacent objects cut off at the sides. Later stages turn the sketch into a warm copper render and then place it in a realistic studio.

**Transfer:** Show the new product's input becoming a finished result. For software without physical objects, move from a hand-drawn workflow or wireframe to a polished real output. The minimum version is one credible line drawing and one finished image of the same composition.

**Build:** Draw the central subject with multiple uneven black SVG paths: a 1px structural outline, lighter offset construction strokes and sparse hatching. Place a faint rectangular grid behind the subject, not the whole paper. Layer the subject in front of a 1280px-wide slogan artwork; add cropped neighboring studies at the viewport edges. Crossfade to a lit finished version with the same silhouette.

### Brush-and-grotesk word sculpture

**Use:** Opening promise, selected emphasis and monumental ending.

**Observed:** A forward-slanted brush word contrasts with clean grotesk words on one line. The opening uses black lettering with roughly 230px visible letter height; the footer uses cream lettering in a 1281px by 234px SVG area and cuts the lower edge. Smaller chapter emphasis also uses brush lettering.

**Transfer:** Create a new short promise with one active word drawn in a brush style; preserve the collision of handmade and engineered lettering.

**Build:** Use SVG text converted to paths or custom vector lettering. Give one word long tapered strokes and an energetic forward slant, leaving the other words upright and rounded. Fit the full phrase to about 89% of the viewport width; in the footer clip its bottom inside a 234px-high artwork region at desktop. A minimum version uses an original hand-lettered SVG word next to live grotesk text.

### Construction patterns

**Use:** Signature working-canvas backing.

**Observed:** Very faint rectangular grids behind feature assemblies, and low-opacity dot patterns behind interactive demonstrations; these add drafting-table texture without looking like a tech starfield.

**Transfer:** Use the grid to unify the page's media chapters and the small closing promise.

**Build:** For the line field, layer 1px horizontal and vertical rgba(232,227,221,0.035) gradients over charcoal, using roughly 49px by 20px cells and broader 98px pattern repeats. For the dot field, tile small clusters of 1px dots in a 26.6px SVG repeat on an overlay at 0.09 opacity. Fade peripheral pattern regions with a mask rather than increasing contrast.

### Material output studies

**Use:** Outcome galleries and capability media.

**Observed:** Furniture, headphones, vehicles and small objects are shown as studio renders, detail studies and occasional real-world scenes. Matte paper or neutral studio backgrounds contrast with rich material color; images are not all tinted blue. Galleries mix portrait and landscape cuts.

**Transfer:** Choose real outputs with believable texture, lighting and scale; pair a finished object with a detail or contextual use. For intangible products, use actual deliverables on neutral backings rather than decorative abstract blobs.

### Floating tool assembly

**Use:** Demonstration and iteration chapters.

**Observed:** Charcoal tool fragments sit around a central colored object on a dark dotted field: small input panels, material swatches and result thumbnails make the process legible without a full app-window border.

**Transfer:** Use only the few interface fragments that explain the transformation; retain a dominant result image.

### Human story portraits

**Use:** Customer or maker proof.

**Observed:** Tall environmental portraits in workshops or studios, with subdued natural light and a black 25% overlay. White title and small descriptive copy sit at the lower left; three cards form a horizontal strip.

**Transfer:** Photograph people doing the work, not generic business headshots. Keep environmental context and enough shadow for legible overlaid captions.

### Collaborative promise graphic

**Use:** A large closing conversion moment.

**Observed:** A centered brush-and-grotesk phrase sits over a small fading construction grid, surrounded by colored cursor arrows and tiny name tags. A single support line and two small actions sit beneath it.

**Transfer:** Keep the graphic device for a promise about coordinated work or the equivalent core outcome; use new words and participant labels.

**Build:** Center a roughly 650px-wide phrase above a 500px-wide grid. Add four small SVG pointer triangles with 12px rectangular name tags around the phrase in muted orange, blue, olive and violet. Keep these colors local to the graphic. Fade the grid outward and place the support line and action pair below.

### Instant-photo collage

**Only for:** culture pages

**Use:** Humanizing recruiting and company storytelling.

**Observed:** A wide edge-to-edge collage inside the content container: overlapping flash-lit instant photographs with white borders, varied rotations and a dark stone-like backing.

**Transfer:** Assemble candid team photographs with imperfect exposure and physical paper overlap rather than a polished headshot grid.

**Build:** Place 12–20 rectangular portraits in thick white instant-photo frames on a charcoal photographic backing. Rotate individual frames in alternating directions, overlap edges and let some frames leave the bounds of a 1281px-wide landscape strip. Keep a few flash highlights and warm paper variations.

### Icons

**Observed:** Small functional SVG marks, not a decorative icon system: 16px thin-stroke plus and arrow controls, tiny checkmarks in pricing, and 32px filled social marks. Icons inherit the local warm-white or charcoal text color.

**Transfer:** Choose simple 1px-stroke controls with square-ended lines for navigation and disclosure; keep social and brand marks filled. Let imagery carry the expression.

## Section recipes

How recurring sections are built.

### First screen: Drawing-stage opening

**Observed:** A warm paper field fills the first 900px. The compact Floating navigation is centered at the top. Behind the main object, an almost full-width black word sculpture uses one brush word and upright grotesk words, with visible letters about 230px tall. The three-quarter-view sketch overlaps the lower half of the slogan, with cropped neighboring objects at both edges and small circular arrow controls beside the center study. Layers run paper, huge lettering, fine local grid, black sketch, then controls. A centered 19.9px support line and blue-plus-outline action pair sit near the bottom, with 47.9px bottom clearance. All of those elements are visible in the first screen; the finished render, workspace scene and customer logos arrive below it. The ordinary text hierarchy uses heading and body-large; the slogan itself is artwork.

**Transfer:** Use the same handmade-to-finished contrast for a different product, with a central sketched diagram or output if there is no 3D model. Keep the giant word sculpture, overlapping subject and bottom action group even in a static version. Product, solution, pricing and recruiting pages instead open with a compact centered 56.3px title, short support and the same action pair on charcoal, followed by relevant media or decision content.

**Avoid:** Do not replace this composition with a small centered slogan above a boxed dashboard, or put a long paragraph over the sketch.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Centered toolkit chapter

**Observed:** Heading and body-large are centered within the centered-copy layout, with a 23.9px text gap and actions about 31.9px below. Four short process tabs sit above a broad demonstration on the Construction field; the main result is flanked by compact tools.

**Transfer:** Describe a short transformation process, then demonstrate the actual outcome rather than illustrating each tab with an unrelated icon.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Split heading and media stories

**Observed:** A large two-line heading anchors the left; a short body-large explanation and Primary button sit on the right. Below, three tall Human story portraits or three output studies use 16px gutters. Portrait captions are inset 23.9px at the bottom.

**Transfer:** Pair a broad claim with either people proving it or varied concrete results; use one kind of proof per strip.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Staggered capability canvas

**Observed:** An upper-left heading and Secondary button introduce a Construction field. Media frame components occupy unequal columns and heights, with some starting well below their neighbors; image areas dominate compact label-and-caption footers.

**Transfer:** Arrange a small set of complementary capabilities as an editorial pinboard. Keep enough shared grid alignment that the offsets feel composed.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Outcome gallery

**Observed:** A centered heading uses brush emphasis on a short phrase, followed by short support and paired actions. A loosely aligned horizontal strip of material photographs rises from below, with image tops at different heights and side images leaving the viewport.

**Transfer:** Use the finished results of the new product, with a mix of detail and full views; preserve the uneven skyline instead of turning it into a uniform card grid.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Split questions

**Observed:** The split-chapter layout puts heading, support and actions in the left half; Question row components fill the right half. Major vertical padding is 159.5px, the title block is limited to about 475px, and the right side is about 632px wide.

**Transfer:** Use direct purchase or adoption questions; switch the same construction to dark text on white only in the pricing context.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Collaborative closing call

**Observed:** A deep dark pause surrounds the Collaborative promise graphic. Its large mixed-lettering line, faint central grid and cursor tags settle into one centered composition; a body-large support sentence and compact action pair sit underneath.

**Transfer:** Use an outcome promise appropriate to the product, retaining the word sculpture and working-canvas motif without copying the subject matter.

**Text style:** `body-large` — Matter 400 · 19.9px/1.3

### Blue poster ending

**Observed:** Blue poster field spans the viewport, about 875px tall at desktop. Brand, four Footer link column groups and a social/newsletter group occupy the upper region, divided by very faint vertical lines. A huge cream slogan fills a 1281px by 234px artwork region below and is clipped at its bottom; a 50px Dark workspace strip holds small muted legal text.

**Transfer:** End with the new identity's short promise rendered at architectural scale. Preserve the contrast between the useful small navigation and the oversized expressive lettering.

**Text style:** `body` — Matter 400 · 16px/1.3

### Split inquiry

**Only for:** lead-generation pages

**Observed:** A large heading and three-line support statement occupy the left, with a few white customer marks low in that column. A 576px-wide form occupies the right, mixing paired short fields and full-width rows, terms checkbox and Form submit.

**Transfer:** Use the split only when a considered business inquiry is the desired action; do not add the full form to every landing page.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Decision sequence

**Only for:** pricing pages

**Observed:** Dark centered promise and four Plan card summaries lead into Light comparison canvas. A wide warm-paper inset explains usage; a five-column matrix uses 237px columns, 38px typical rows, pale 1px rules and simple checkmarks. Split questions remain on white before the blue ending.

**Transfer:** Use the white region to make dense comparison readable, with billing mechanics explained before feature detail.

**Text style:** `heading` — Matter 500 · 56.3px/1.1 · tracking -0.01em

### Culture editorial rows

**Only for:** culture pages

**Observed:** A centered recruiting promise precedes the Instant-photo collage and a large charcoal role-list panel. Later principles use a wide title-left, explanation-right row with dark 1px rules; benefits use a left heading and stacked right-hand entries. A centered quote carousel and short charcoal callout close before the blue ending.

**Transfer:** Use human material and readable editorial lists for organizational stories; keep the rough collage local to this page type.

**Text style:** `values-title` — Matter 500 · 27.7px/1.3 · tracking -0.01em

## Page flow

**Storyline:** expressive promise → transformation demonstration → evidence of useful outcomes → capability exploration → confidence and objections → next step → monumental identity ending

### Flagship marketing narrative

1. **Promise** — Paper-stage word sculpture and overlapping sketch.
2. **Product demonstration** — The same object becomes rendered, then appears in a realistic workspace; logos bridge into the dark explanatory canvas.
3. **Capability chapters** — Process tabs, floating tools and a staggered output canvas.
4. **Social proof** — Environmental story portraits and finished-result galleries.
5. **Objection handling** — Split question list with hand-drawn rules.
6. **Closing call** — Mixed-lettering promise with cursor tags, paired actions and blue poster footer.

**Transfer:** Borrow the transformation story rather than the long scroll duration; show what changes for the user before listing features.

### Audience-specific solution narrative

1. **Promise** — Centered benefit title and paired actions above a wide product study and logos.
2. **Problem and resolution** — Three-column comparison of friction and the improved process.
3. **Outcome proof** — Split chapter header above three material output studies.
4. **Objection handling** — Split questions.
5. **Closing call** — Collaborative promise graphic, then a split inquiry form and the blue poster ending.

**Transfer:** Adapt the friction comparison and outcomes to one audience without changing the core visual vocabulary.

### Detailed product exploration

1. **Promise** — Centered title with a prominent evolving object and floating editor fragments.
2. **Capability chapters** — Construction-field media assembly and oversized category directory.
3. **Breadth of outcomes** — Tabbed result strip with varied material treatments.
4. **Social proof** — Large centered quote with small portrait and credit.
5. **Real-world proof** — Finished-result gallery.
6. **Closing call** — Split inquiry form followed by the blue poster ending.

**Transfer:** Demonstrate one memorable transformation, then broaden the use cases and finish with a suitable next step.

### Plan selection and purchase confidence

1. **Promise** — Centered team-scale promise.
2. **Pricing** — Billing selector and four equal dark plan summaries.
3. **Explanation** — Warm inset explaining usage on a white field.
4. **Comparison** — Fine-ruled five-column feature matrix.
5. **Objection handling** — Light-theme questions.
6. **Ending** — Blue poster footer without an additional large conversion scene.

**Transfer:** Keep summary choices simple and move dense distinctions into the white comparison field.

### Recruiting and organizational confidence

1. **Invitation** — Centered title and actions followed by instant-photo collage.
2. **Actionable inventory** — Open-role list with three compact filters in a charcoal panel.
3. **Principles** — Wide editorial rows and a four-column team-character strip.
4. **Practical value** — Benefits list with compact descriptions.
5. **Social proof** — Centered employee quote carousel.
6. **Closing call** — Short contained charcoal recruiting callout, then blue poster footer.

**Transfer:** Make the opportunities easy to find before elaborating the culture story.

## Writing

Optimistic, tactile and matter-of-fact. Creativity is framed as practical progress: the language talks about form, iteration and real outcomes rather than mysterious technology.

**Do not copy:** Do not reuse Vizcom's name, wordmark, signature slogan, product artwork, customer logos, testimonials, employee names, prices, benefit promises or performance claims. Source examples illustrate voice only.

- **Addressing the reader:** Address the reader as you and your; use we for the team in human stories. Product descriptions name the product and explain what it helps people do.
- **Rhythm:** Short verb-led headlines, usually 4–9 words, followed by one or two plain-language support sentences. Three-part verb sequences and concise contrasts keep the pace moving; actions are short and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Headline | Express an input-to-output change or a useful destination. | 4–10 words | “From sketch to 3D render in seconds”<br>“Accurate product visuals, simplified” |
| Chapter title | Lead with an active benefit, sometimes balancing digital process with tangible outcome. | 4–9 words | “Instantly iterate and explore”<br>“Bridging the gap from digital to physical” |
| Support | Name the user's process and the improvement without a long technical preamble. | One or two sentences | “From your vision, through variations, and into reality.”<br>“Speed up every step of your ideation, without sacrificing your creative spark” |
| Action | Use a recognizable next step rather than clever campaign language. | 2–4 words | “Get Started”<br>“Book a Demo”<br>“View open roles” |
| Question | Use first-person practical concerns, then answer directly. | One short question | “Can I use [Brand] for free?”<br>“Do I own the content I produce in [Brand]?” |

**Words and phrasing to use:** explore; refine; iterate; bring to life; from … to …; real world; workflow; together; form; materials

**Avoid:** revolutionary ecosystem; disruption; unparalleled synergy; magic with no explanation; hyperbolic superlatives

**Rules:**

- Prefer a concrete verb and visible result over an abstract capability noun.
- Mention speed only when a demonstration or substantiated claim supports it.
- Keep media captions specific to what the image demonstrates.
- Use audience-specific friction in solution copy and warm first-person language in people stories.

## Do's and Don'ts

### Do

- Keep main chapter titles at 56.3px, weight 500 and -0.01em tracking.
- Use the blue action and outlined alternative as a compact pair, with 8px corners.
- Keep desktop page gutters near 79.8px and major chapter padding near 159.5px.
- Let the central sketch overlap the opening word sculpture.
- Use 12px matte frames and 14px captions around large useful media.
- Preserve the faint construction grid or dot field in working-canvas chapters.
- Finish with a saturated blue poster field and monumental cream lettering.
- Use the pricing-only white canvas for dense feature comparison.

### Don't

- Do not turn all 8px action corners into fully rounded pills.
- Do not use pure black as the default explanatory canvas; use #191919.
- Do not spread footer blue across every feature card.
- Do not set all headings in bold 700; the rounded 500 weight is essential.
- Do not add drop shadows or glass blur to the matte charcoal panels.
- Do not force staggered media into identical rounded-square tiles.
- Do not use violet generative controls as the general marketing action color.
- Do not apply the instant-photo collage treatment to ordinary product proof.

## Motion and responsive

### Motion

**Observed:**

- Navigation and action surfaces declare 0.33s transitions with cubic-bezier(0.126,0.382,0.282,0.674); navigation radius changes declare 0.66s.
- The flagship stage progresses from sketch to render to a physical studio scene through scrolling.
- A repeating marquee is declared at 120s linear infinite; interactive hotspots declare a 3s repeating pulse.
- Newsletter controls declare transform 0.2s ease-out, background-color 0.2s linear and box-shadow 0.2s.

**Transfer:**

- Tie the main scene change to a single intelligible input-to-output transformation.
- Use the clipped text-layer treatment on short actions rather than large disruptive hover effects.
- Retain a static finished composition when motion is unavailable, including the oversized lettering and overlapping object.

**Unknown:**

- Exact scroll-linked animation timing and interpolation are not established.
- The focus color variable's resolved value is not established.

### Responsive

**Observed:**

- Width breakpoints include 479px, 767px, 768px, 991px and 992px, with additional narrow rules at 430px and 497px.
- The culture values title declares clamp(1.5rem, 1.3142rem + 0.4661vw, 2rem).

**Transfer:**

- On narrow layouts, preserve the opening's paper, mixed lettering and overlapping central subject while reducing or removing peripheral studies.
- Stack split chapters while keeping title before questions or fields; allow image strips to remain horizontally browsable.
- Keep the monumental ending lettering fitted to width rather than reducing it to an ordinary footer heading.

**Unknown:**

- Exact mobile navigation construction, mobile scene behavior and narrow-screen spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
