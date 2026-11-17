# Mother Design — objects before explanations

## Overview

An image-led editorial style with the confidence of a design exhibition and the informality of a working studio. A white, black and grey grotesk framework gives saturated product photography, sculptural objects and oversized word artwork the room to dominate. It suits design-conscious products and creative services, combining very sparse compositions with compact, matter-of-fact captions.

### Essentials

- The product arrives before the pitch: a 1440×900 full-bleed opening scene carries a central sculptural object, with the 60px/1 regular-weight title and grey proposition below the first screen.
- Navigation feels like a small desktop instrument panel: fixed 20px from the edges, 45px outer height, square cells, 1px black dividers and translucent white with 4px backdrop blur; actions are text or rectangular cells, never pills.
- Explanations behave like exhibition labels: 16px/1.2 body at -0.02em, small 600-weight section titles, a 12-column grid with 20px gutters, and prose offset from the left quarter of the page.
- Color belongs to the exhibited work, not the explanatory furniture: white prose sections and black rules alternate with near-full-width chromatic images; the default product world is emerald and deep green, occupying entire media panels rather than tiny interface accents.
- A monumental word artwork must interrupt the imagery: an original product name or short promise fills nearly the full 1400px panel width. If custom lettering is unavailable, tightly fitted live grotesk type on a flat colored field is the minimum equivalent.
- Image scale changes like a magazine spread: 1400px-wide images alternate with 453px, 572px and 808px asymmetric placements, with 12px caption gaps and 60px breathing room rather than framed cards.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Emerald stage | `#048464` | `--color-stage-green` | background, surface | Base of the default green product scene; lighting introduces dark and bright regions within the imagery. |
| Deep green matte | `#0c544c` | `--color-deep-green` | background, surface | Solid word-art and identity demonstration fields within the default product world. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | All editorial sections and reversed media labels. Header white is used at 85% opacity over imagery, not as a separate grey fill. |
| Editorial grey | `#808080` | `--color-secondary` | text, link | Propositions, questions, descriptions, emails and inactive text controls. |
| Black ink | `#000000` | `--color-ink` | text, border, background | Primary text, 1px structural rules, selected navigation cells and dark media overlays. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| sensorial product stories | Burgundy matte | `#4c042c` | `--color-burgundy` | background, surface | Deep wine backing for a sensorial product identity, paired with pale natural materials and pastel details in the imagery. |
| collection filters | Faint control underline | `#d9d9d9` | `--color-filter-rule` | border | Visible 15% black underline over white, constructed with rgba(0,0,0,0.15). |

## Typography

- **Basis** — All editorial text, navigation, captions and live display type. Direct contemporary grotesk with round counters and tightly set display proportions; regular text is contrasted with restrained semibold labels. If unavailable, use **DM Sans**. Use 400 and 600; preserve the compact line heights and negative tracking. Font stack: "Basis", "DM Sans", Arial, sans-serif.
- **Basis Mono** — Gallery fractions and location clocks. Plain technical monospace used as a tiny functional counterpoint, not an overall technology aesthetic. If unavailable, use **IBM Plex Mono**. Font stack: "Basis Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| statement | Basis | 400 | 60px | 1 | -0.04em | size clamp(40*1px,60*1vw/1440*100,calc(60 * 1)*1px) | Main live headline, project name, proposition, editorial introduction and large testimonial. |
| body | Basis | 400 | 16px | 1.2 | -0.02em | fixed | Prose, navigation labels, descriptive captions and text controls. |
| section-label | Basis | 600 | 16px | 1.2 | -0.02em | fixed | Small section titles, card names and metadata headings; these remain small beside much larger imagery. |
| gallery-counter | Basis Mono | 400 | 16px | 1 | -0.02em | fixed | Current image and total count beneath a horizontal image sequence. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| institutional and collection footers | footer-display | Basis | 600 | 226.4px | 1.2 | -0.04em | fixed | Edge-to-edge closing brand name. |
| institutional principle grids | word-cell | Basis | 600 | 110px | 1 | -0.04em | size clamp(70*1px,110*1vw/1440*100,calc(110 * 1)*1px) | Centered one-word principles in ruled panels. |
| service overview sections | capability-list | Basis | 400 | 48px | 1.1 | -0.04em | fixed | Large stacked capability names opposite a small section label and explanation. |
| institutional and collection footers | footer-text | Basis | 400 | 14px | 1.2 | -0.01em | fixed | Addresses, email links, social links and newsletter actions. |
| institutional and collection footers | footer-label | Basis | 600 | 14px | 1.2 | -0.01em | fixed | Location names and signup title. |
| institutional and collection footers | clock | Basis Mono | 400 | 14px | 1.2 | 0.06em, uppercase | fixed | Live local times and parenthesized timezone labels beside location names. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display tracking is -0.04em while body tracking relaxes to -0.02em. Do not replace this with uniformly loose editorial typography.
- The hierarchy is deliberately discontinuous: 16px section labels sit beside 60px statements or enormous visual artwork, rather than a ladder of medium-sized headings.
- Lettering embedded in product identity artwork is an image treatment, not an additional website font. Keep the website grotesk stable while the work changes.
- Use live type fitted to the available width for new monumental word artwork; retain the separate measured footer-display recipe for institutional closings.

## Layout

**Density:** Airy at the page level, compact inside text and controls; image spreads and large unoccupied grid regions carry the pacing.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small question-to-support and inline icon spacing. |
| 12px | Image-to-caption gap and gallery metadata offset. |
| 16px | Navigation cell horizontal padding and paragraph separation. |
| 20px | Page side margins, main grid gutters and standard section top spacing. |
| 24px | Separation between metadata groups. |
| 60px | Editorial bottom padding, collection row gaps and media breathing room. |
| 64px | Bottom padding in footer contact and signup blocks. |
| 200px | Long pauses after collections and service lists. |
| 245px | Top inset before the first content in text-led institutional and collection openings. |

### Containers and grids

- **editorial-grid**: 12 columns · gap 20px · side padding 20px. Full-width default grid; at 1440px the inner width is 1400px. Metadata occupies the left three columns, primary prose starts in column four and spans five or six.
- **prose**: max width 736px. Rich-text maximum; actual case-study prose commonly occupies 572px, with two narrow 276px columns for short paired arguments.
- **media-spread**: 2 columns · gap 20px · side padding 20px. Equal 690px images or deliberately unequal 453px and 808px images. Use the 12-column grid to leave white space between unequal images.
- **collection-grid** (only for collections and catalogues): 4 columns · gap 20px · side padding 20px. Mixed-width archive: featured images span two columns, smaller images one, with 60px row gaps.
- **contact-grid** (only for institutional and collection footers): 3 columns · gap 20px. Three 276px contact columns in an 868px left block, alongside a 513px signup block divided by a black rule.

## Corner radius

| Element | Radius |
| --- | --- |
| editorial elements | 0px |

## Surfaces and depth

### Surfaces

#### Editorial canvas · level 0

**Use:** Default background for prose, captions and navigation surroundings.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Untextured white with structure supplied by rules, alignment and scale rather than raised panels.

**Transfer:** Let the imagery carry material richness; keep the explanatory layer plain.

#### Translucent toolbar · level 2

**Use:** Floating segmented navigation and utility controls.

**CSS:** `background: rgba(255,255,255,0.85); border: 1px solid #000000; backdrop-filter: blur(4px); border-radius: 0px`

**Observed:** A thin outlined strip floats over both white space and large pictures. Its cells remain visually flat.

**Transfer:** Use translucency only for the compact persistent toolbar, not for content cards.

#### Green media matte · level 0

**Use:** Backing for product demonstrations and monumental identity artwork.

**CSS:** `background: #0c544c`

**Observed:** A solid deep green panel fills the image area; the opening product scene uses emerald with photographic light variation.

**Transfer:** Keep the default product world green and allow its light and material to change from scene to scene.

#### Ruled editorial band · level 0

**Use:** Boundaries between explanatory chapters.

**CSS:** `border-top: 1px solid #000000; padding: 20px 20px 60px`

**Observed:** The rule spans the page, while text occupies only a few grid columns.

**Transfer:** Use a single rule to announce a change of argument without introducing a card.

#### Dimmed continuation image

**Use:** Closing full-image navigation to another product or story.

**CSS:** `background: rgba(0,0,0,0.5)`

**Observed:** An overlay darkens the image while small white labels remain near its upper edge.

**Transfer:** Use on the image layer only; leave labels undimmed.

#### Sensorial wine matte

**Only for:** sensorial product stories

**Use:** Alternative product-art backing.

**CSS:** `background: #4c042c`

**Observed:** Burgundy lettering panels sit among warm glass, stone, fabric and rippled nature imagery.

**Transfer:** Treat this as a complete art-direction variant, not an extra accent to sprinkle into the green theme.

## Components

### Segmented navigation

**Use:** Persistent primary wayfinding.

**CSS:** `display: flex; height: 45px; border: 1px solid #000000; border-radius: 0px`

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

**Observed:** A small symbol cell leads a run of textual destinations. The group is fixed in the top-left with 20px outer clearance; a separate utility group sits at the right. The active destination reverses to white on black.

**Transfer:** Replace destinations with the new product's short navigation labels; keep the grouped rectangular construction.

### Navigation cell

**Use:** Main navigation action and compact toolbar action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 43px; padding: 0px 16px 2px; border-left: 1px solid #000000; border-radius: 0px; color: #000000`

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

**Observed:** Cells touch with no inter-button gap and sit inside the Translucent toolbar. Label widths determine their width.

**States:** Declared: hover on the ancestor changes the cell background to white; focus-visible behavior is unspecified.

**Transfer:** Carry conversion links as short text cells rather than introducing a separate rounded button style.

### Gallery navigation

**Use:** Stepping through product-detail imagery.

**CSS:** `color: #808080; border-radius: 0px; background: transparent; border: 0px; padding: 0px`

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

**Observed:** Plain controls sit at the far right beneath the images, separated by a slash; the Gallery counter sits at the far left and an explanatory caption can occupy the middle.

**States:** Declared: hover changes text to #000; focus-visible behavior is unspecified.

### Gallery counter

**Use:** Small ordinal indicator for a horizontal gallery.

**CSS:** `display: flex; align-items: baseline; overflow: hidden`

**Text style:** `gallery-counter` — Basis Mono 400 · 16px/1 · tracking -0.02em

**Observed:** The current number is a vertically stacked number sequence masked to one line, followed by the total. The metadata row begins 12px beneath the images.

**Transfer:** Use a real current/total count without pagination dots.

### Chapter text band

**Use:** Explaining one decision between image spreads.

**CSS:** `display: grid; grid-template-columns: repeat(12,minmax(0px,1fr)); gap: 20px; border-top: 1px solid #000000; padding: 20px 20px 60px`

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

**Observed:** A small semibold chapter label occupies the left rail. The argument is offset to column four; some chapters use paired narrow paragraphs instead of one broad paragraph.

**Transfer:** Describe a problem, a deliberate decision and its effect rather than filling every column.

### Continuation panel

**Use:** The default product-story ending.

**CSS:** `position: relative; height: 815px; color: #ffffff; border-radius: 0px`

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

**Observed:** The entire photographic panel is a link. Above the Dimmed continuation image, one short navigation label sits in the left quarter and a title plus a 256px-wide description starts in column four.

**Transfer:** Link to a related product, demonstration or customer story with a large relevant picture rather than a conventional CTA card.

### Editorial text link

**Only for:** institutional and collection footers

**Use:** Secondary contact and cross-page actions.

**CSS:** `color: #808080; background-image: linear-gradient(#808080,#808080); background-size: 0px 1px; background-position: 100% 100%; background-repeat: no-repeat; transition: background-size .6s,color .3s`

**Text style:** `footer-text` — Basis 400 · 14px/1.2 · tracking -0.01em

**Observed:** The link is text-sized rather than boxed; black social-link variants share the underline construction.

**States:** Declared: hover changes grey text to #000; focus-visible behavior is unspecified.

### Project tile

**Only for:** collections and catalogues

**Use:** Browseable visual project or product entry.

**CSS:** `display: flex; flex-direction: column; text-align: left; position: relative`

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

**Observed:** A square-cornered image with a 1.3 width-to-height ratio sits above a 12px gap, a 600-weight name and a grey description. Featured tiles span two columns of a four-column grid; smaller tiles span one.

**Transfer:** Vary tile size while keeping image ratios and caption alignment consistent.

### View filter

**Only for:** collections and catalogues

**Use:** Switching presentation or narrowing a collection.

**CSS:** `padding-bottom: 4px; color: #000000; background-image: linear-gradient(#000000,#000000),linear-gradient(rgba(0,0,0,0.15),rgba(0,0,0,0.15)); background-size: 0px 1px,100% 1px; background-position: 100% 100%,0px 100%; background-repeat: no-repeat; transition: background-size .6s,color .3s`

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

**Observed:** Small text controls are arranged beside a plain 'View:' label, with category filtering further to the right. The inactive option is grey.

**States:** Declared: hover expands the current-color underline to 100% width; the inactive list option also changes to black.

### Principle cell

**Only for:** institutional principle grids

**Use:** An emphatic set of short beliefs or differentiators.

**CSS:** `display: flex; align-items: center; justify-content: center; border-top: 1px solid #000000; border-right: 1px solid #000000; border-radius: 0px`

**Text style:** `word-cell` — Basis 600 · 110px/1 · tracking -0.04em

**Observed:** A 720×407 desktop cell is one quarter of a full-width two-by-two ruled grid; its centered word has no icon or supporting paragraph.

**Transfer:** Use short, contrasting words with enough conceptual weight to stand alone.

### Contact block

**Only for:** institutional and collection footers

**Use:** Local contact information with a human sense of place.

**CSS:** `display: grid; grid-template-columns: repeat(3,minmax(0px,1fr)); column-gap: 20px; row-gap: 60px; padding-top: 20px; padding-bottom: 64px; border-right: 1px solid #000000`

**Text style:** `footer-text` — Basis 400 · 14px/1.2 · tracking -0.01em

**Observed:** Each column begins with a semibold location, a tiny weather symbol, a mono local clock and timezone; address and grey email follow. A signup area occupies the separate right-hand block.

**Transfer:** Use genuine locations and times, or adapt the columns to equally concrete contact channels; retain the split ruled construction.

## Imagery and graphics

### Sculptural product stage

**Use:** Default first impression and recurring product close-ups.

**Observed:** A tube and carton form a suspended diagonal sculpture in an emerald environment, roughly centered and occupying about half the width and most of the height. Directional light creates a near-black upper-left field and brighter green lower-right space; edges, printing and material finish are sharply legible.

**Transfer:** Photograph or render the new product as one striking object arrangement rather than a collage of features. Without physical hardware, stage a dimensional representation of its central artifact or one sharply framed interface plane; maintain the green light field and sparse composition.

**Build:** For a minimum stage, use an emerald base and a broad radial light layer centered toward the lower right, fading from rgba(255,255,255,0.18) to transparent; add a black-to-transparent diagonal layer at the upper left. Place one isolated product image or dimensional SVG at the center, rotated diagonally, with directional shading baked into the object. Keep the scene full-width and 900px high at the desktop reference size; match the soft light rather than requiring exact gradient stops.

### Monumental word artwork

**Use:** A signature visual interruption within the product narrative.

**Observed:** White sculptural custom lettering fills nearly the full width of a deep green 1400px panel, leaving a substantial green field below. This is brand artwork, distinct from the regular website type.

**Transfer:** Use an original name or compact promise at wall scale. The minimum acceptable version is live semibold grotesk text fitted almost edge-to-edge on a deep green field, not a small logo centered in a card.

**Build:** Create an SVG with a 1400px-wide viewBox and a deep-green rectangle. Fit original white vector lettering across the top half with approximately 20px edge clearance, preserving counters and intentional letter shapes. Alternatively use live tightly tracked grotesk type in a single line, adjusting size to the new word length; leave the lower field unoccupied.

### Material and application spreads

**Use:** Repeated evidence throughout product stories.

**Observed:** Full-width close-ups, carton details, a glass shelf, opened corrugated packaging and real-world advertising alternate with unequal image pairs. Clinical directional lighting produces distinct cast shadows and clear paper, plastic and glass surfaces. Image rectangles are not surrounded by UI borders or shadows.

**Transfer:** Show the new product's actual texture, construction, packaging and use context at several scales. At minimum create one close-up, one structural view and one real-world application, with consistent light and color.

### Liquid sensorial art

**Only for:** sensorial product stories

**Use:** Alternative material language for an indulgent product.

**Observed:** A transparent ribbed glass bottle floats against warm ivory; adjacent scenes use reflective fabric, gemstones, burgundy identity panels and blurred nature seen through rippled glass. Distortion communicates touch and scent rather than functioning as a page background.

**Transfer:** Choose a physical material metaphor tied to the product and keep it inside substantial rectangular image spreads.

**Build:** Use a nature photograph beneath an SVG filter with low-frequency feTurbulence feeding feDisplacementMap. Favor elongated horizontal waves, with displacement around 20–40px as a starting build recommendation, and preserve recognizable green foliage and pale sky. Pair it with an undistorted product still life so the material effect does not obscure the object.

### Studio life and personal portraits

**Only for:** institutional and team pages

**Use:** Human context, culture interludes and people grids.

**Observed:** Warm, lived-in offices contain pinned typography, books, fabric and wooden floors; moving people leave photographic blur. Individual portraits resemble personal family-album pictures in varied color and monochrome, aligned into small repeated rectangles with name and grey role underneath.

**Transfer:** Use real working environments and candid personal images instead of uniform corporate headshots. Keep varied image character but consistent rectangular framing.

### Monochrome partner marks

**Only for:** institutional proof sections

**Use:** A quiet band of external credibility.

**Observed:** Six black marks occupy a widely spaced single row; each has an approximately 217px square allocation rather than a visible logo card.

**Transfer:** Normalize visual weight, not literal logo dimensions, and leave the band on white.

### Icons

**Observed:** Small solid black silhouettes: a heart-like home symbol, pointer, musical note, moon and weather signs. Utility icons are 16–20px and footer weather symbols 14px; each toolbar icon has its own ruled rectangular cell.

**Transfer:** Use a few filled, immediately recognizable symbols. Match their compact scale and cell construction; avoid introducing a large decorative outline-icon vocabulary.

## Section recipes

How recurring sections are built.

### First screen: Sculptural scene opening

**Observed:** The first 900px is an uninterrupted full-bleed product image. Back to front: emerald light field, a suspended diagonal arrangement of product and carton centered in the scene, then the compact Segmented navigation at the top-left and icon controls at the top-right, all inset 20px. The object reaches through most of the vertical space but occupies roughly half the scene width, leaving strong colored negative space. There is no overlaid marketing headline, support paragraph or hero CTA. The live title and grey proposition use statement typography and begin 20px below the image, in a left-half column on white; they fall below the first 900px.

**Transfer:** Open a new marketing landing page with an equally decisive, single-object product tableau. If no product photography exists, make one dimensional SVG or clean interface artifact over the lit green stage, not a generic screenshot collage. Keep the name and proposition below the scene. Text-led institutional pages instead begin with a broad 60px introduction at a 245px top inset; collection pages begin at that inset with small view controls and imagery.

**Avoid:** Do not superimpose a giant sales headline and two pill CTAs over the central object, or split the opening into a conventional text-left/image-right hero.

**Text style:** `statement` — Basis 400 · 60px/1 · tracking -0.04em

### Name and proposition

**Observed:** A white editorial band follows the full-height scene. The black product name sits directly above a grey, balanced proposition at the same 60px size and line height; the group spans six of twelve columns with 20px side inset and 60px bottom padding.

**Transfer:** Give the product a direct name and one memorable conceptual tension or benefit. Keep the grey line as visually important as the black one.

**Text style:** `statement` — Basis 400 · 60px/1 · tracking -0.04em

### Challenge and decision band

**Observed:** The Chapter text band uses the left rail for small scope or metadata labels, a grey question starting in column four, and black prose below in a 572px measure. Later chapters often use two 276px text columns separated by 20px.

**Transfer:** State what convention or obstacle the product challenges, then explain a concrete design or product decision. Allow unused columns to remain white.

**Text style:** `body` — Basis 400 · 16px/1.2 · tracking -0.02em

### Image essay

**Observed:** A sequence alternates 1400px-wide image panels with asymmetric small-and-large pairs and horizontal galleries. Full media typically leaves 20px side margins and 60px below; small captions sit 12px beneath their image. Gallery navigation and Gallery counter belong to the same baseline beneath the sequence.

**Transfer:** Let the viewer understand material, mechanism and application through scale changes. Introduce the Monumental word artwork within this essay without imposing a fixed section count.

### Related story ending

**Observed:** The product essay ends on the Continuation panel rather than a contact footer: a full-width 815px image, dimmed by 50% black, with a small white navigation label at the left and a title plus short description aligned to column four.

**Transfer:** Close a product narrative by inviting the next relevant discovery. For a single-product site, use a demonstration or customer application as the destination.

### Large spoken proof

**Only for:** testimonial-led product stories

**Observed:** A long left-aligned quotation uses the 60px statement recipe, black on white, across approximately 1163px. Attribution is compact 16px text beneath it, with the role in grey; the quote is not boxed.

**Transfer:** Use a genuine detailed quote when it contributes evidence. Keep its spoken quality and let line wrapping provide the drama.

**Text style:** `statement` — Basis 400 · 60px/1 · tracking -0.04em

### Principles and capabilities

**Only for:** institutional and service overviews

**Observed:** The Principle cell grid makes four words into a ruled two-by-two typographic field. The capabilities section takes a different form: a small title in the left quarter, short support in the next quarter and a 48px stacked list across the right half, with a 200px closing pause.

**Transfer:** Separate beliefs from capabilities; give the former monumental words and the latter a plain, large inventory rather than interchangeable feature cards.

### Monumental contact ending

**Only for:** institutional and collection footers

**Observed:** A 900px white closing section puts a 226.4px semibold brand name almost edge-to-edge above a horizontal rule. Under it, the Contact block takes roughly five eighths of the width and signup takes the remainder, separated by a vertical rule. Email entry and Submit are unboxed text; social and legal links sit near the bottom, while a short personal aside anchors the lower left.

**Transfer:** Fit the new identity to the width rather than preserving the same word count. Keep the contrast between monumental naming and tiny useful contact details; use this ending for company and catalogue pages, not as an automatic appendage to a product essay.

**Text style:** `footer-display` — Basis 600 · 226.4px/1.2 · tracking -0.04em

## Page flow

**Storyline:** Object as promise → proposition → challenge and decisions → visual evidence at changing scales → proof or reflection → another discovery or human contact.

### Product identity and launch story

1. **Product demonstration** — Full-viewport green sculptural object scene, followed by a black name and equal-size grey proposition.
2. **Problem framing** — Ruled metadata and challenge band with compact offset prose.
3. **Capability chapters** — Material studies, monumental identity artwork, galleries, short two-column explanations, packaging and real-world applications.
4. **Closing discovery** — Dimmed full-image link to a related story; no institutional footer follows.

**Transfer:** Use the product's actual mechanism and design logic as the content of the visual essay.

### Sensorial product story with outcome proof

1. **Product demonstration** — Floating glass object on a warm pale field; name and proposition follow on white.
2. **Capability chapters** — Ruled explanation alternates with liquid, fragrance and packaging imagery and a numbered image gallery.
3. **Outcome proof** — A small grey results caption accompanies an image; a detailed 60px testimonial follows rather than an isolated giant statistic.
4. **Closing discovery** — A brief project recap and year lead to a dimmed photographic related-story link.

**Transfer:** Use this variant when touch, desire and responsible use are essential to the product; substantiate the emotional story with real outcomes.

### Creative-services marketing overview

1. **Visual introduction** — A selected-work media presentation leads into a broad 60px editorial declaration.
2. **Point of view** — A two-by-two field of oversized one-word principles.
3. **Capabilities** — Small side labels and support sit opposite a tall 48px service inventory.
4. **Credibility and human context** — A monochrome partner-mark row and a full-bleed warm tabletop photograph.
5. **Human contact** — Monumental brand-name footer with clocks, contact information and a restrained signup area.

**Transfer:** Introduce the offering through selected work and a clear point of view, then expose practical services without converting everything into cards.

### Company and people introduction

1. **Point of view** — A broad text-led introduction, with a full-bleed working-office photograph directly below.
2. **Capability and credibility** — Sparse ruled bands, partner names, service inventory and unequal office photographs.
3. **Human proof** — Large principle words and a dense grid of varied personal portraits with tiny captions.
4. **Human contact** — Large location/email pairs precede the same monumental contact footer.

**Transfer:** Make culture tangible through the workspace, people and language, not a generic list of abstract values.

### Visual collection and discovery

1. **Orientation** — Small Image/List and category controls after a deep top inset.
2. **Browseable proof** — Mixed-width image tiles on a four-column grid, with semibold names and grey one-sentence descriptions.
3. **Human contact** — A long white pause leads into the monumental contact footer.

**Transfer:** Use a visual collection to show range while preserving caption and grid discipline.

## Writing

Confident, curious and materially literate, with an understated human joke never far away. Ideas are expressed as tensions and deliberate choices, while longer passages explain how the design actually works.

**Do not copy:** Do not reuse Mother Design's name, heart symbol, custom client lettering, project names, client claims, sales figures, proprietary product terminology, testimonials or company-specific contact details. Examples illustrate voice only.

- **Addressing the reader:** Institutional copy speaks as 'we' and 'our'; case narratives describe the product and its audience directly. Questions use 'you' to invite the reader into a problem, not to pressure a purchase.
- **Rhythm:** Short project names and one-sentence propositions contrast with compact explanatory paragraphs. Headlines commonly hold two ideas in balance; small section labels are direct and ordinary. Human asides are brief, dry and warm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Proposition | A concise phrase that joins two seemingly opposed benefits or worlds. | 5–10 words | “Bridging the gap between art and science”<br>“Designing for planet and pleasure” |
| Challenge | An open question names the category convention to overcome. | 8–18 words | “How do you take on an established category?”<br>“How do you throw out tired category codes to create your own new lane?” |
| Section label | Plain language announces the function of the next block. | 3–5 words | “What we do”<br>“Why we do it” |
| Chapter heading | Link a material quality to an experience or strategic idea. | 5–10 words | “A rolling, liquid-like brand identity”<br>“A moment of pleasure that you can feel” |
| Action | Unadorned navigation or a simple invitation; no urgency. | 1–4 words | “See our work”<br>“Next Project”<br>“Submit” |
| Human aside | A short ordinary sentence softens the institutional scale. | 6–12 words | “[Brand] is a small branding studio with massive heart.”<br>“For the love of design, and the courage of our partners.” |

**Words and phrasing to use:** structure and fluidity; material; feel; courage; new worlds; clarity; pleasure; a question about conventions

**Avoid:** best-in-class; seamless ecosystem; unlock your potential; game-changing solution; hurry; overblown futurist language

**Rules:**

- Describe one deliberate decision and its effect in each explanatory chapter.
- Let emotional language sit beside specific materials, mechanisms or applications.
- Keep numbers embedded in evidence-bearing prose or captions rather than manufacturing a dashboard of statistics.
- Use a personal aside sparingly, where the composition already has breathing room.

## Do's and Don'ts

### Do

- Keep default editorial paragraphs at 16px/1.2 with -0.02em tracking.
- Use the 20px margin and gutter to align very different image sizes.
- Make the first scene fill the desktop 900px height before the textual proposition begins.
- Retain a monumental original word artwork in the visual narrative.
- Keep navigation at 45px outer height with 1px black dividers and square corners.
- Use 12px between imagery and captions, then 60px before the next substantial beat.
- Keep section titles small and semibold while image scale supplies the hierarchy.
- Use white for explanation and let green consume full media fields rather than tinting every section.

### Don't

- Do not turn 16px section labels into a conventional series of 32px bold headings.
- Do not wrap image spreads in rounded 16px cards with drop shadows; the editorial elements have 0px radius and no elevation.
- Do not make all text semibold: the 60px statement is weight 400.
- Do not scatter burgundy and emerald together as equal interface accents; they belong to separate product-art directions.
- Do not replace numbered gallery metadata with large carousel dots or floating chevron circles.
- Do not enlarge grey captions into centered promotional subheadings; keep them left-aligned and compact.
- Do not promote outcome numbers into giant metric cards when a plain caption or spoken testimonial carries the proof.
- Do not apply the 85% white translucency and 4px blur to ordinary content panels.

## Motion and responsive

### Motion

**Observed:**

- Text links declare background-size .6s and color .3s transitions.
- Navigation and gallery controls declare .3s transitions using cubic-bezier(0.4,0,0.2,1).
- A gallery counter is constructed as a vertical sequence masked to one line. Product images include motion-blurred and distorted visual treatments.

**Transfer:**

- Keep interaction emphasis in small changes of color, underline extent and toolbar fill; let large media remain the expressive layer.
- Preserve the counter's one-line mask when changing the current index.

**Unknown:**

- Exact media playback, scroll choreography, counter timing and transition sequences are not specified.
- Focus-visible and active interaction treatments are not established.

### Responsive

**Observed:**

- Declared stylesheet width breakpoints include 375px, 450px, 639px, 640px, 767px, 768px, 1024px, 1280px, 1440px, 1536px, 1900px and 2500px.
- The statement size clamps between 40px and 60px; principle words clamp between 70px and 110px.
- Layout declarations distinguish compact stacked content from desktop twelve-column compositions; full navigation and gallery Previous/Next controls have desktop visibility variants.

**Transfer:**

- On narrow layouts, stack the metadata before the argument while preserving the small-label/large-image contrast.
- Keep the hero object legible in a full-width scene by reframing the image rather than shrinking the entire desktop composition.
- Collapse the two-by-two principle field and multi-column contacts into readable stacked bands while retaining their black rules.

**Unknown:**

- Exact mobile compositions, menu behavior, image focal-point changes and footer display scaling are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
