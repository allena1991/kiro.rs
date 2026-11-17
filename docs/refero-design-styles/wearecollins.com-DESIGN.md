# COLLINS — editorial theatre of transformation

## Overview

An editorial identity with a spare, almost ceremonial entrance and vivid work presented like objects on a gallery shelf. Warm near-black and off-white grounds alternate beneath fine, tightly set serif statements and plain grotesk labels. Photography, expressive graphic design and short films supply the color; the surrounding interface stays restrained. It suits ambitious creative products and services that can demonstrate their value visually, with low text density and expansive pauses.

### Essentials

- A small sentence carries a huge entrance: a centered 72px regular serif headline, line height 1 and -0.02em tracking sits in an 810px-tall off-white opening with a tiny proof cluster near its foot.
- Editorial rather than oversized-tech hierarchy: 36px/1.05 serif statements occupy a 500px measure, paired with 16px/1.3 grotesk section labels; both stay at weight 400.
- Actions are small lozenges, not banners: 45px high, 96px radius, 24px horizontal padding and 14px regular grotesk text, with polarity reversed against light or dark ground.
- Color belongs to the work: most of the page remains off-white or warm near-black; saturated photography and graphic artwork fill rounded 16px media windows. A self-contained story scene can carry an image-related muted color across one viewport, rather than tinting every section.
- Work has the presence of a shelf: portrait media of unequal heights, a shared lower edge, 16px gaps and a partially visible next item. Include a vivid visual proof shelf on a new page; when original media is unavailable, use composed product artifacts or type-led benefit posters rather than generic feature icons.
- The ending is an oversized table of contents: centered 72px serif destination links with 16px gaps occupy a 900px dark closing stage, followed by a small contact pill, utility links, newsletter and socials. Preserve this monumental navigation device even when the destination names change.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft off-white | `#f8f8f7` | `--color-paper` | background, text, action | Default entrance canvas and editorial background; primary text and solid actions on dark sections. |
| Warm near-black | `#140700` | `--color-ink` | background, text | Dark narrative canvas and footer; primary lettering on the light opening. |
| Receding charcoal | `#4c4c4c` | `--color-inactive` | text | Inactive monumental footer destinations on focused interior-page navigation. |
| Dark field edge | `#514c49` | `--color-edge` | border | One-pixel outline around the newsletter input. |
| Warm gray | `#5e5855` | `--color-muted` | text | Supporting copy and labels on light ground. |
| Warm light gray | `#d0d0c8` | `--color-secondary` | text | Labels, supporting copy and social links on dark ground. |
| Pure white | `#ffffff` | `--color-white` | text, surface, action | Footer links, contact pill and dedicated white catalog band. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| rose-toned immersive story scenes | Story rose | `#9c3f62` | `--color-story-rose` | background | Rose-toned ground for a self-contained visual story, not a global interface accent; keep the final appearance subdued and related to its image. |
| service catalogs and light editorial reading sections | Catalog black | `#000000` | `--color-black` | text | Primary text in the white service catalog. |
| editorial scroll-reading introductions | Unfilled reading gray | `#cccccc` | `--color-reveal-gray` | text | Unfilled portion of the scroll-reading paragraph, paired with black letter fill. |

## Typography

- **COLLINS Portrait Text Web** — Promise headlines, editorial statements and monumental destination links. A literary, sharp serif with lively stroke contrast and a compact, slightly old-fashioned voice; always regular rather than bold. OpenType features: "kern", "liga". If unavailable, use **Bodoni Moda**. Use 400; preserve the compact measure and negative tracking. Font stack: "COLLINS Portrait Text Web", "Bodoni Moda", Georgia, serif.
- **COLLINS Graphik Web** — Labels, body copy, capability names and controls. An unembellished grotesk with even color and restrained regular weight. OpenType features: "kern", "liga". If unavailable, use **Inter**. Use 400 and keep body tracking at -0.01em. Font stack: "COLLINS Graphik Web", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | COLLINS Portrait Text Web | 400 | 72px | 1 | -0.02em | Centered opening promise and large closing navigation. |
| story-heading | COLLINS Portrait Text Web | 400 | 40px | 1.05 | -0.02em | Short statement beside an immersive story image. |
| statement | COLLINS Portrait Text Web | 400 | 36px | 1.05 | -0.02em | Section statements, interior-page titles, editorial paragraphs and light-gallery headings. |
| row-title | COLLINS Graphik Web | 400 | 28px | 1.05 | normal | Primary label of a linked capability row. |
| body | COLLINS Graphik Web | 400 | 16px | 1.3 | -0.01em | Body copy, section labels, row support and utility links. |
| button | COLLINS Graphik Web | 400 | 14px | 1 | -0.0114em | Solid actions and short inline exploration links. |
| media-action | COLLINS Graphik Web | 400 | 14px | 1.2 | -0.0114em | Link labels inside translucent media pills. |
| proof | COLLINS Graphik Web | 400 | 12px | 1 | -0.053em | Compact recognition labels beneath the opening statement. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial galleries | gallery-caption | COLLINS Graphik Web | 400 | 16px | 1.25 | -0.01em | Linked titles beneath editorial images. |

**Notes:**

- Serif hierarchy is built with scale and whitespace, not increased weight. Keep -0.02em tracking at 36px, 40px and 72px.
- Section labels are sentence-case grotesk, not tracked uppercase eyebrows. Preserve the distinction between the 28px row title and its 16px support line.
- The introductory light canvas uses ink lettering; the same type recipes reverse to off-white over the dark narrative ground.

## Layout

**Density:** Airy at the section scale, compact within controls and captions; small type sits inside very large fields of unoccupied space.

### Spacing

**Spacing system:**

- **gutter** 16px — Declared gutter for media grids and structural columns; combine with the 24px minimum page inset and 48px section token.

| Value | Use |
| --- | --- |
| 8px | Caption-to-description gap and compact utility spacing. |
| 16px | Grid gutter, image-to-caption gap and closing destination gap. |
| 24px | Minimum page inset, button horizontal padding and media overlay inset. |
| 28.8px | Heading-group layout gap before optical negative type margins. |
| 32px | Capability-row vertical padding, story outer inset and action-group spacing. |
| 48px | Declared section padding token and editorial gallery row gap. |
| 64px | Section-head-to-content spacing and shelf separation. |
| 96px | Main content section vertical padding. |
| 128px | Footer and white catalog vertical padding. |
| 160px | Large chapter spacing and footer lower-row separation. |

### Containers and grids

- **main-container**: max width 1440px · side padding 98px. Desktop content spans 1244px within a centered page width. Keep text aligned to this inset even when media continues off the right edge.
- **reading-container**: max width 992px · side padding 0px. Centered inset reading area, 224px from each side at desktop; used for footer content and editorial grids.
- **statement-measure**: max width 500px. Cap ordinary serif statements and supporting text; do not stretch these across the entire container.
- **capability-grid**: 3 columns · gap 16px. Unequal columns in a 3fr 3fr 2fr ratio: title, support, then a right-aligned arrow.
- **story-split**: 2 columns · gap 32px · side padding 32px. 42:58 copy-to-media split; the large image occupies most of the right side and almost all the section height.
- **editorial-grid** (only for editorial galleries): 3 columns · gap 16px. Three 320px portrait images in the inset reading area; use 48px between rows.

## Corner radius

| Element | Radius |
| --- | --- |
| media | 16px |
| action-pills | 96px |
| newsletter | 160px |
| story-progress | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| soft-underlay | `0px 21px 13px 0px rgba(0,0,0,.06),0px 9px 9px 0px rgba(0,0,0,.1),0px 2px 5px 0px rgba(0,0,0,.11)` | Pseudo-element underlay for solid pills and editorial media; a soft contact shadow rather than a floating dashboard-card effect. |

### Surfaces

#### Light canvas · level 0

**Use:** Default opening and editorial reading ground.

**CSS:** `background: #f8f8f7; color: #140700`

**Observed:** A broad untextured paper-like field with no decorative gradient.

**Transfer:** Let the type and work provide the visual interest.

#### Dark canvas · level 0

**Use:** Main narrative chapters, work shelves and the closing navigation.

**CSS:** `background: #140700; color: #f8f8f7`

**Observed:** Brown-black rather than neutral black, with muted warm-gray support.

**Transfer:** Use as a full-width field, not as a small rounded card enclosing the whole page.

#### Story stage · level 0

**Use:** One image-led chapter with a related tonal ground.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 42fr) minmax(0px, 58fr); gap: 32px; padding: 32px; background: #140700`

**Observed:** The ground changes with the active story, including olive and muted mauve, around a large rounded image. Copy is held at left, with segmented progress near the lower edge.

**Transfer:** Use the dark canvas as a fallback; for authored scenes choose a subdued color belonging to the active image, not a site-wide accent.

#### Frosted media action · level 1

**Use:** Local navigation sitting directly on rich imagery.

**CSS:** `background: rgba(255,255,255,0.4); backdrop-filter: blur(20px); border-radius: 96px; color: #ffffff`

**Observed:** A restrained translucent lozenge rather than a large glass panel.

**Transfer:** Keep frosting local to the action; its visible color should come from the media underneath.

#### White catalog band · level 0

**Only for:** service catalogs

**Use:** A sustained readable inventory section.

**CSS:** `background: #ffffff; color: #000000; padding: 128px 98px`

**Observed:** An edge-to-edge polarity change, with the row list inset farther than the outer page container.

**Transfer:** Use the light band to distinguish structured selection from persuasive narrative.

## Components

### Minimal navigation

**Use:** Persistent access without competing with the opening promise.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); align-items: center; padding: 24px 98px 32px`

**Observed:** Small wordmark at left and two-line menu mark at right, with no desktop link parade. The fixed header occupies 74px and changes polarity with its ground.

**Transfer:** Use the product's compact wordmark and a similarly modest menu control.

### Solid action

**Use:** Explore a chapter or begin a conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #f8f8f7; color: #140700; border: 1px solid transparent; border-radius: 96px; padding: 0px 24px; height: 45px; gap: 12px`

**Text style:** `button` — COLLINS Graphik Web 400 · 14px/1 · tracking -0.0114em

**Observed:** Content-sized pill below the statement. On the light opening sections the polarity reverses to dark fill and light type.

**States:** Declared: hover transform scale(1.04); focus-visible transform scale(1.04); active transform scale(0.98).

### Capability row

**Use:** Present offerings as an editorial index rather than feature cards.

**CSS:** `display: grid; grid-template-columns: 3fr 3fr 2fr; align-items: center; gap: 16px; padding: 32px 0px; color: #f8f8f7`

**Text style:** `row-title` — COLLINS Graphik Web 400 · 28px/1.05

**Observed:** A large title sits beside a smaller one-line outcome; a small arrow closes the row. Subtle horizontal separators create a list about 93px per item. The white catalog reverses title color and uses warm-gray support.

**Transfer:** Name a capability in the first column and its useful consequence in the second.

### Work media card

**Use:** Visual proof in a horizontal shelf.

**CSS:** `border-radius: 16px; overflow: clip; background-size: cover; max-width: 500px`

**Observed:** Image-only portrait objects, commonly 362px wide with 453px, 483px or 543px height. Art runs to the rounded edge; adjacent items share a lower edge and the next item can extend beyond the viewport.

**Transfer:** Fill the surface with a product artifact, result or photographed use, not a heading-and-icon tile.

### Media link pill

**Use:** Identify and open the active visual story.

**CSS:** `display: flex; align-items: center; gap: 12px; background: rgba(255,255,255,0.4); backdrop-filter: blur(20px); border: 1px solid transparent; border-radius: 96px; height: 45px; padding: 0px 24px; color: #ffffff`

**Text style:** `media-action` — COLLINS Graphik Web 400 · 14px/1.2 · tracking -0.0114em

**Observed:** Short project label followed by a tiny expand-corners icon; placed 24px inside the image near its bottom edge.

**States:** Declared: hover transform scale(1.04); focus-visible transform scale(1.04); active transform scale(0.98).

### Closing destination

**Use:** Make site exploration the principal closing gesture.

**CSS:** `color: #ffffff; text-align: center; transition: .7s color cubic-bezier(.215,.61,.355,1)`

**Text style:** `display` — COLLINS Portrait Text Web 400 · 72px/1 · tracking -0.02em

**Observed:** Three stacked serif destinations, not boxed navigation cards. Interior-page variants dim other destinations to charcoal while keeping the current one white.

**States:** Declared: hover color #fff; focus-visible color #fff.

### Contact pill

**Use:** Compact contact action below the monumental links.

**CSS:** `display: grid; align-items: center; justify-content: center; background: #ffffff; color: #140700; border-radius: 96px; height: 45px; width: 132px`

**Text style:** `button` — COLLINS Graphik Web 400 · 14px/1 · tracking -0.0114em

**Observed:** Aligned with a short row of secondary company links. It exposes contact-address and copied-confirmation content rather than a large lead form.

**States:** Declared: hover transform scale(1.04); focus-visible transform scale(1.04); active transform scale(0.98).

### Newsletter field

**Use:** Low-emphasis subscription in the lower-left of the closing stage.

**CSS:** `display: flex; align-items: center; gap: 12px; height: 44px; width: 248px; padding: 0px 16px; border: 1px solid #514c49; border-radius: 160px; background: #140700`

**Text style:** `body` — COLLINS Graphik Web 400 · 16px/1.3 · tracking -0.01em

**Observed:** Small invitation above an outlined email field with an envelope at left; social links sit across the lower-right of the same footer row.

### Editorial story card

**Only for:** editorial galleries

**Use:** Captioned work, places and reading material.

**CSS:** `display: grid; gap: 16px`

**Text style:** `gallery-caption` — COLLINS Graphik Web 400 · 16px/1.25 · tracking -0.01em

**Observed:** A 16px-radius image above a plain linked title; the caption inset is 8px, followed by an optional muted description after 8px. Three-column grids use 320×400px images; lateral story strips mix 362×452px portraits and 669×452px landscapes.

**Transfer:** Mix concrete artifacts and candid human context. Keep copy outside the image rather than overlaying every card.

## Imagery and graphics

### Vivid work shelf

**Use:** Signature visual proof within the marketing narrative.

**Observed:** Photographic workers and physical environments sit beside intensely colored packaging, performance imagery and graphic illustration. Portrait frames are rounded without decorative borders; the supporting ground is dark and the shelf dominates more area than its introductory text.

**Transfer:** Show the new product's output in use, its tangible artifacts and one vivid abstract or typographic interpretation. Keep differences in art direction while maintaining the common frame and lower alignment.

**Build:** Create a flex or grid shelf with 16px gaps and align-items:end. At desktop use 362px-wide media windows with 16px radius and varied heights of 453px to 543px. Continue the track beyond the right edge. Without photography, compose original benefit words and product artifacts inside equally saturated portrait posters; do not substitute empty frames.

### Wide opening film

**Use:** The first visual demonstration below the restrained opening.

**Observed:** A broad rounded moving-image window introduces vivid material, including a golden circular object and a bold yellow hand graphic against a pale ground. It enters at the bottom of the first viewport and becomes the next major object.

**Transfer:** Use a short, strongly art-directed product film or a single decisive still at a wide cinematic ratio. Keep the first screen's typography independent of the media.

### Immersive story image

**Use:** The dominant right-hand object in the Story stage.

**Observed:** Nearly full-height media mixes wooded architecture, graphic publications and abstract painterly forms. The surrounding field relates to the image, from earthy olive to mauve; overlays are limited to a small frosted link.

**Transfer:** Commission one coherent image per story, mixing actual product context with an expressive visual. A carefully framed original photograph is sufficient; do not imitate painterly work with a generic blurred gradient.

### Floating evidence constellation

**Only for:** offering overview openings

**Use:** Surround a modest title with multiple examples at different apparent depths.

**Observed:** Off-white ground holds portrait images of different sizes around the text. A sharp 311×389px colorful portrait dominates the right-middle; 249×311px and 187×233px cards orbit it, with smaller distant images visibly blurred. Several objects extend beyond the viewport.

**Transfer:** Use a handful of product outputs rather than duplicating one mockup. Preserve a clear text island at left.

**Build:** Place 16px-radius portrait windows on separate absolute-positioned layers around a 500px text measure. Use a sharp primary window, smaller rear windows and selective CSS blur on distant cards. Keep the principal artwork unobscured; let peripheral objects cross top and bottom edges.

### Editorial context photography

**Only for:** editorial galleries

**Use:** Long-form galleries and horizontal story chapters.

**Observed:** Natural-light buildings, gatherings in book-lined rooms, mountain landscapes, wooded retreats and candid people alternate with graphic artifacts. Landscapes retain their spatial context; portrait works fill their frames. Captions remain separate on off-white.

**Transfer:** Photograph the new product's real working environment and people with natural light and rich environmental detail, then combine with its artifacts rather than stock business portraits.

### Icons

**Observed:** Small filled arrows around 16px, media marks around 18px and an 11px expand-corners icon with 2px strokes. Newsletter envelope is about 17×19px. Marks inherit ink or off-white; navigation uses a simple two-line menu.

**Transfer:** Use a minimal monochrome arrow, envelope and expand set. Keep icons subordinate to type, not as colorful feature badges.

## Section recipes

How recurring sections are built.

### First screen: Ceremonial promise opening

**Observed:** An off-white field places Minimal navigation above a single centered display sentence. The headline sits near the vertical middle of an 810px opening, occupying roughly two fifths of the width rather than running edge to edge. There is no supporting paragraph or primary action next to it. Far below it, a centered 500px-wide proof cluster uses 12px labels, a small summary and two rows of laurel-flanked acknowledgments. Within the first 900px the full headline, proof cluster and upper lip of the rounded Wide opening film are visible; the film's full composition and detailed explanation fall below. Layers are the flat canvas, header, headline, proof marks and then the next section's media edge.

**Transfer:** Write one short change-oriented promise. Replace awards with truthful compact credentials or concise proof labels, retaining the diminutive visual scale. Use an original product film or a composed artifact still beneath it. Offering overviews instead open with a left-aligned statement among the Floating evidence constellation; editorial libraries open with a small label, a 36px serif title and a wide image; work indexes begin with the heading pair above a dark shelf.

**Avoid:** Do not turn the first screen into a split SaaS hero with a paragraph, two oversized CTAs, a dashboard and decorative gradient. Its tension comes from a small amount of content in a very large field.

**Text style:** `display` — COLLINS Portrait Text Web 400 · 72px/1 · tracking -0.02em

### Editorial heading pair

**Observed:** A body-sized section label precedes a 36px serif statement capped at 500px. The layout gap is 28.8px before optical negative type margins; the resulting visible separation is about 19px. Solid action follows the group with a 32px layout gap; content begins about 64px later.

**Transfer:** Use the small label to identify the category and the serif line to state the consequence or invitation.

**Text style:** `statement` — COLLINS Portrait Text Web 400 · 36px/1.05 · tracking -0.02em

### Capability index

**Observed:** Capability row repeats across the main container on dark ground; a compact view-all link finishes the short preview. The catalog variant uses White catalog band, a narrower 982px list and a serif section heading above a longer inventory.

**Transfer:** Prefer a scannable offering-plus-outcome list when the user needs selection, rather than converting every offering into a separate card.

**Text style:** `row-title` — COLLINS Graphik Web 400 · 28px/1.05

### Visual proof shelf

**Observed:** Editorial heading pair sits over a horizontally continuing row of Work media card objects, 16px apart and aligned at their bottoms. The section uses 120px top and 80px bottom padding, with media allowed to continue past the normal content inset.

**Transfer:** Choose visually distinct examples and let their relative sizes make the rhythm, without requiring identical image ratios.

### Immersive split story

**Observed:** Story stage fills approximately one 900px viewport. Left copy is vertically centered while a 780×836px rounded image occupies the right. Four narrow progress segments sit toward the lower left; a Media link pill sits within the image. The next dark stage arrives as a hard field change.

**Transfer:** Give a single product story breathing room. Adapt the left statement and right image without treating it as another repeated feature grid.

**Text style:** `story-heading` — COLLINS Portrait Text Web 400 · 40px/1.05 · tracking -0.02em

### Monumental closing navigation

**Observed:** Dark canvas occupies 900px with 128px vertical and 224px side padding. Three Closing destination links are centered with 16px gaps, starting roughly 174px below the top. A Contact pill and three small utility links sit beneath. A large pause separates that group from a lower row: newsletter at left, socials at right. No extra legal-content wall interrupts the finish.

**Transfer:** Use a few meaningful destinations as the closing statement, then keep contact and ongoing updates visibly secondary.

**Text style:** `display` — COLLINS Portrait Text Web 400 · 72px/1 · tracking -0.02em

### Focused outcome stack

**Only for:** offering detail pages

**Observed:** A small left-side label accompanies a right-side stack of six 36px serif outcome lines. Each line occupies about 74px including 18px vertical padding; inactive lines recede to 0.1 opacity and the active outcome remains legible.

**Transfer:** Use this to distinguish desired outcomes from the inventory of offerings; it should not become a low-contrast body-text section.

**Text style:** `statement` — COLLINS Portrait Text Web 400 · 36px/1.05 · tracking -0.02em

### Editorial library and strips

**Only for:** editorial libraries

**Observed:** A two-column introduction gives a small label to the left and a 36px serif paragraph to the right. A three-column Editorial story card grid follows a serif heading and muted support. Later chapters use 96px vertical padding, a 40px gap from support to imagery, and horizontally continuing strips of mixed portrait and landscape media.

**Transfer:** Use a dense visual library for breadth, then switch to larger lateral images for human context and deeper reading.

**Text style:** `statement` — COLLINS Portrait Text Web 400 · 36px/1.05 · tracking -0.02em

## Page flow

**Storyline:** A concise transformation promise → visual demonstration → ways to act → proof in the work → a broader human story → monumental destination navigation.

### Introduce a brand and route visitors into its offer and work

1. **Promise** — A centered serif sentence and compact credential cluster on light ground.
2. **Demonstration** — A wide rounded film introduces vivid work.
3. **Offer discovery** — Heading pair, small action and abbreviated capability index.
4. **Visual proof** — Unequal portrait objects form a horizontally continuing dark shelf.
5. **Human context** — A full-height split story changes the visual ground.
6. **Closing navigation** — Monumental destinations, contact, newsletter and social links.

**Transfer:** Keep the alternation of very spare claims and rich media; adapt the number and order of middle chapters.

### Let visitors browse a large body of results

1. **Framing promise** — A small category label and compact serif statement over dark ground.
2. **Visual archive** — An extensive shelf of portrait work with compact view controls and search.
3. **Closing navigation** — The shared dark closing stage highlights the active destination.

**Transfer:** Use a work-first index rather than adding a conventional long landing-page pitch.

### Explain an offering system and make selection easy

1. **Offer promise** — Left-aligned statement within a floating constellation of colorful examples.
2. **Desired outcomes** — A focused serif outcome stack beside a small label.
3. **Offer selection** — White band with an extended linked row catalog.
4. **Audience fit** — A dark two-column chapter with a serif heading and concise explanatory paragraphs.
5. **Closing navigation** — The shared footer emphasizes the active category.

**Transfer:** Separate outcomes, options and buyer fit rather than blending them into repeated cards.

### Show depth through an editorial body of work and human context

1. **Editorial invitation** — Small label, short serif statement and broad rounded story image on light ground.
2. **Point of view** — A small left label and large right serif reading paragraph.
3. **Breadth of proof** — Three-column portrait gallery with understated linked captions.
4. **Human context** — Larger lateral chapters mix places, people and gatherings.
5. **Further exploration** — A mixed-media reading strip leads directly into the shared dark closing stage.

**Transfer:** Use the light editorial variant for a substantial library; preserve the final shift to dark navigation.

## Writing

Assertive, literate and commercially ambitious, with a creative director's economy. Short declarative claims and surprising contrasts carry the argument; concrete outcomes prevent the language from becoming purely poetic.

**Do not copy:** Do not reuse COLLINS names, wordmarks, client artwork, project titles, award counts, branded program names, proprietary claims or the historical quotation. Source examples describe rhetoric, not approved copy for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use your in the promise, we in explanations and direct imperatives for actions. Speak to the reader as a capable decision-maker rather than a novice.
- **Rhythm:** Three- to eight-word headline sentences, brief outcome lines and occasional fuller explanatory paragraphs. Periods give short claims a finished, editorial cadence; paired clauses create contrast.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A short imperative links change to a meaningful outcome. | 3–6 words | “Rewrite your worth.” |
| Section statement | A concrete transformation framed as a memorable inevitability. | 8–14 words | “Design a future so irresistible, it becomes inevitable.” |
| Outcome line | Two clipped clauses sharpen an opposition or progression. | 5–10 words | “Don’t Become the Best. Become the Only.”<br>“Stay Relevant. Stay Valuable.” |
| Action | Plain exploration verb, optionally followed by the destination category. | 1–3 words | “Explore Programs”<br>“Work with us” |
| Editorial support | A compact explanation of the experience or perspective offered. | 6–12 words | “Immersive retreats that reshape how you see, decide and lead” |

**Words and phrasing to use:** future; worth; distinctive; desired; valuable; see differently; move; create; command; turning point

**Avoid:** game-changing platform; seamless solution; leverage synergies; unlock endless possibilities; revolutionary AI-powered ecosystem

**Rules:**

- Make the promise about an altered position or capability, not a list of tools.
- Pair poetic statements with concrete outcomes in the next explanatory layer.
- Keep actions literal and short; reserve rhetorical flourishes for statements.
- Use numerals in concise proof labels only when the fact is defensible.

## Do's and Don'ts

### Do

- Use regular 72px serif type for the opening promise and closing destinations.
- Keep ordinary statements at 36px/1.05 within a 500px measure.
- Pair 28px capability titles with 16px supporting outcomes in the same row.
- Use 16px rounded media and a 16px shelf gutter.
- Keep action pills 45px high with 96px corners and compact 14px labels.
- Retain a 900px dark closing stage with separate monumental and utility scales.
- Let artifact imagery carry high saturation while the interface remains warm-neutral.
- Use the 98px desktop inset for main text and the deeper 224px inset for reading galleries.

### Don't

- Do not replace the warm #140700 narrative ground with cool blue-black.
- Do not bold the serif statements; weight 400 is part of their literary character.
- Do not introduce a bright site-wide CTA color; solid actions use neutral polarity.
- Do not give every work item an identical height; the shelf depends on varied portrait proportions.
- Do not put all explanatory text inside rounded cards; capability rows live directly on the page.
- Do not enlarge proof labels beyond their 12px supporting role.
- Do not move editorial captions onto every image; the light gallery uses separate 16px labels.
- Do not make the footer a conventional many-column sitemap with tiny headings; the 72px destination stack is the main event.

## Motion and responsive

### Motion

**Observed:**

- Solid and translucent actions declare .8s transform cubic-bezier(.19,1,.22,1), with hover and focus-visible scale(1.04) and active scale(0.98).
- Closing links declare .7s color cubic-bezier(.215,.61,.355,1).
- The fixed header declares .45s transform cubic-bezier(.215,.61,.355,1).
- Story scenes use clipping and transforms; segmented progress marks accompany changing imagery. The outcome stack declares .75s opacity, transform, padding and margin with cubic-bezier(.165,.84,.44,1).

**Transfer:**

- Keep the small pill's elastic size feedback rather than changing its shape or fill into a conspicuous accent.
- Treat the story as one scene transition with coordinated media and ground; keep the settled text composition readable.

**Unknown:**

- Full playback sequencing, scroll thresholds and reduced-motion behavior are unspecified.

### Responsive

**Observed:**

- The numerical layout describes a 1440px-wide desktop composition. The declared minimum page inset is 24px; no width breakpoints are established.

**Transfer:**

- On narrow layouts, retain the centered promise and separate proof cluster; reduce headline size only enough to preserve a short readable phrase.
- Collapse the story split into copy then media; keep a lateral work track with part of the next card visible instead of shrinking every card to fit.
- Stack title and outcome within capability rows and preserve the closing destination hierarchy above the newsletter and socials.

**Unknown:**

- Exact mobile type sizes, media dimensions, breakpoint widths and header behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
