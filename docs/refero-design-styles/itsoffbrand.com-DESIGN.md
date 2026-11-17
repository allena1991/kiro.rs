# OFF+BRAND — orbital colour, oversized words

## Overview

A light, gallery-like style with enormous regular-weight grotesk lettering, warm grey space and soft iridescent objects. Pastel pink, yellow and blue light moves behind almost-black words, while saturated photography, 3D work and interface films live inside neatly rounded frames. The feeling is experimental but approachable, suited to creative technology and ambitious digital products; text is sparse at the top and more editorial in the proof sections.

### Essentials

- Headlines behave like independently placed objects: regular 400-weight uppercase grotesk at 102.9px/1, normal tracking, with three short phrases staggered across a 900px opening rather than a centred text stack.
- A luminous object carries the emotional pitch: a soft pink–yellow–blue orb occupies roughly 560px of the opening, backed by two oversized 1px dashed orbital circles. Keep this device even without product media, using a layered gradient sphere.
- The page is predominantly warm grey, not a succession of coloured bands: #e5e4e0 canvas, near-black readable type and #f1f0ec panels; colour is concentrated in the orb, media and a bounded gradient statement panel.
- Actions are pale capsules, not high-contrast slabs: a 305px × 75px closing action uses 24.4px uppercase text and a right arrow; smaller proof actions are 171px × 42px with 15.2px labels and a faint 1px edge.
- Proof is staged as artwork rather than dashboard UI: square image tiles have 9.5px corners, 30.5px inset captions and a 30px plus sign; offset two-column placement leaves a broad editorial rail to the left.
- Small information reads like gallery notation: 15.2px uppercase labels, 0.05em eyebrow tracking, 11.4px row indices and superscript counts, with hairline rules instead of heavy boxes.
- The ending remains a major composition: a four-line 102.9px invitation sits beside three narrow navigation columns, with a capsule embedded in the headline, a large identity at the lower right and orbital lines continuing behind it.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Luminous yellow | `#facb0e` | `--color-yellow` | accent, background | Warm light within the iridescent object and bounded gradient art, softened by broad white diffusion; not a solid button colour. |
| Pearlescent pink | `#f06ba8` | `--color-pink` | accent, background | Pink light on the left of the sphere and one end of the gradient art. |
| Pearlescent blue | `#78bae6` | `--color-blue` | accent, background | Cool rim light and the blue side of gradient art; not the default link colour. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light bloom | `#ffffff` | `--color-white` | accent, text | Diffused highlights in colour artwork and light captions against dark imagery. |
| Ivory panel | `#f1f0ec` | `--color-panel` | surface | Light media mats, capability panels and testimonial cards. |
| Warm grey canvas | `#e5e4e0` | `--color-canvas` | background, text, surface, action | Default page ground and capsule fill; also the light source colour for difference-blended lettering. |
| Soft grey rule | `#cdcdc9` | `--color-rule` | border | Visible result of rgba(111,111,111,0.2) over the warm grey canvas; use that alpha recipe for separators and faint edges so they adjust with the backing. |
| Orbital grey | `#bfbebe` | `--color-orbit` | border | Fine dashed circular outlines behind page content. |
| Charcoal ink | `#1d1d1d` | `--color-ink` | text, border, accent, link | Readable lettering, outlined labels and small symbols. Difference blending makes some large lettering appear black on the light ground. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruitment listings | Listing white | `#f4f4f4` | `--color-listing` | surface | Brighter background for repeated opportunity rows. |

## Typography

- **Ataero Retina OB Edition** — All marketing lettering, paragraphs, labels and actions. Plain, open grotesk with a broad capital footprint, almost always at regular weight; scale and placement create the drama rather than boldness. If unavailable, use **Inter**. Use 400; tune line breaks to preserve the wide capital compositions. Font stack: "Ataero Retina OB Edition", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Ataero Retina OB Edition | 400 | 102.9px | 1 | normal, uppercase | fixed | Default opening phrases and monumental closing invitation. |
| manifesto | Ataero Retina OB Edition | 400 | 76.2px | 1 | normal, uppercase | fixed | Large multi-line statements inset into the page grid. |
| scroll-statement | Ataero Retina OB Edition | 400 | 45.7px | 1 | normal, uppercase | fixed | Short declaration inside a bounded immersive statement panel. |
| identity | Ataero Retina OB Edition | 400 | 30.5px | 1.4 | normal | fixed | Small text identity in the fixed navigation. |
| action-large | Ataero Retina OB Edition | 400 | 24.4px | 1 | normal, uppercase | fixed | Capsule action embedded in the closing composition. |
| eyebrow | Ataero Retina OB Edition | 400 | 15.2px | 1 | 0.05em, uppercase | fixed | Section rail labels, proof headings and outlined micro-labels. |
| label | Ataero Retina OB Edition | 400 | 15.2px | 1 | normal, uppercase | fixed | Navigation, small action labels and short names. |
| body | Ataero Retina OB Edition | 400 | 15.2px | 1.4 | normal | size 1.0582vw | Default compact text in editorial columns. |
| body-tracked | Ataero Retina OB Edition | 400 | 15.2px | 1.4 | 0.013em | fixed | Short supporting paragraphs under large statements. |
| caption | Ataero Retina OB Edition | 400 | 15.2px | 1.4 | normal, uppercase | fixed | Names over project artwork and short media captions. |
| micro | Ataero Retina OB Edition | 400 | 11.4px | 1 | 0.017em, uppercase | fixed | Two-digit indices, annotations and superscript proof counts. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| recruitment pages | listing-display | Ataero Retina OB Edition | 400 | 266.7px | 0.8 | normal, uppercase | fixed | Oversized split-word opening that the first listing overlaps. |
| culture pages | culture-display | Ataero Retina OB Edition | 400 | 190.5px | 0.8 | normal, uppercase | fixed | Two-line identity declaration with the second line spanning nearly the full inner width. |
| dedicated service landing pages | service-display | Ataero Retina OB Edition | 400 | 158.1px | 0.8 | normal, uppercase | fixed | Four-row headline with inline rectangular films and graphic inserts. |
| dedicated service-page footers | closing-identity | Ataero Retina OB Edition | 400 | 70.1px | 0.8 | normal | fixed | Large identity at the foot of the service-page ending. |
| case studies, culture narratives and detailed service pages | heading | Ataero Retina OB Edition | 400 | 38.1px | 1.2 | normal, uppercase | fixed | Editorial objectives, method panels and compact section statements. |
| recruitment listings | listing-title | Ataero Retina OB Edition | 400 | 34.3px | 1 | normal, uppercase | fixed | Opportunity title beneath a small outlined location label. |
| detailed service pages | capability-title | Ataero Retina OB Edition | 400 | 34.3px | 1.3 | normal, uppercase | fixed | Title in the overlapping numbered capability stack. |
| FAQ sections | question | Ataero Retina OB Edition | 400 | 30.5px | 1.2 | normal | fixed | Sentence-case accordion questions. |
| testimonial cards | quote-title | Ataero Retina OB Edition | 400 | 22.9px | 1 | normal | fixed | Organisation name beside a circular portrait. |
| case studies, testimonials and recruitment pages | body-large | Ataero Retina OB Edition | 400 | 18.3px | 1.5 | 0.011em | fixed | Case-study prose, longer quotations and supporting recruitment text. |
| FAQ sections | answer | Ataero Retina OB Edition | 400 | 16px | 1.4 | 0.0125em | fixed | FAQ answers set narrower than the question row. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Normal tracking and weight 400 are the baseline even for the largest words. Do not turn the display into a heavy condensed face.
- Default display lines use line-height 1; the much larger culture, recruitment and service headline variants compress to 0.8 and rely on deliberate line-by-line framing.
- Difference-blended #e5e4e0 lettering reads near-black over the canvas and can take on complementary colour over media. Use normal ink for small text; use blending only in controlled large compositions.
- Only the body size has a documented viewport formula. Preserve headline proportions by fitting short phrases and intentional breaks rather than treating every size as one universal fluid scale.

## Layout

**Density:** Airy overall, with huge pauses between artwork-led chapters and compact annotation clusters inside each chapter.

### Spacing

| Value | Use |
| --- | --- |
| 7.6px | Fine text and icon separation. |
| 8px | Eyebrow-to-outline-label and small listing title gaps. |
| 15.2px | Paragraph-to-action separation, compact vertical stacks and overlapping capability offset. |
| 19px | Default page gutter and grid gap. |
| 22.9px | Listing card padding. |
| 30.5px | Project caption inset, panel padding and larger internal separation. |
| 45.7px | Extra inset for the closing text block and quotation header separation. |
| 76px | Closing-section top breathing room and large heading-to-list separation. |
| 152px | Long chapter pauses and major section breathing room. |

### Containers and grids

- **page grid**: 12 columns · gap 19px · side padding 19px. Full desktop composition: a 1402px-wide grid in a 1440px viewport. Narrow rails and staggered objects share this grid rather than independent centred containers.
- **inner editorial span**: max width 1165px · side padding 0px. Ten-column inner span for large text, team grids, opportunities and FAQs; roughly 137px from either edge at desktop.
- **work gallery**: max width 928px · 2 columns · gap 19px. Right-hand eight-column span of square media, leaving the left third available for sticky section labels. Vertically stagger the two streams.
- **footer navigation**: max width 573px · 3 columns · gap 19px · side padding 45.7px. Compact navigation groups occupy the right side of the monumental closing invitation.
- **portrait grid** (only for culture pages): max width 1165px · 3 columns · gap 19px. Near-square portraits aligned in three equal columns.
- **case-study prose** (only for case studies): max width 810px. Main explanation column beside a narrow left label rail; media may expand beyond this prose width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media and panels | 9.5px |
|  | outlined labels | 6.5px |
|  | capsule actions | 95.2px |
|  | closing action | 9999px (pill) |
|  | immersive statement panel | 30.5px |
|  | orbits and avatars | 50% |
| testimonials and service-page media inserts | testimonial cards | 21px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| immersive panel edge | `0px 0px 0px 0.4px rgba(111,111,111,0.2)` | A barely perceptible edge around the large bounded statement scene, not an elevation shadow. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default marketing page background.

**CSS:** `background: #e5e4e0; color: #1d1d1d`

**Observed:** The same ground continues behind the majority of sections and the footer; content floats above it.

**Transfer:** Keep the uninterrupted grey field as the connective material.

#### Ivory panel · level 1

**Use:** Media mats and grouped explanatory content.

**CSS:** `background: #f1f0ec; border: 1px solid rgba(111,111,111,0.2); border-radius: 9.5px`

**Observed:** Low contrast against the page, with almost no elevation; some media mats omit the edge.

**Transfer:** Let images and type provide hierarchy instead of deeper shadows.

#### Immersive statement panel · level 1

**Use:** A contained colour-led declaration that interrupts the otherwise open canvas.

**CSS:** `border-radius: 30.5px; box-shadow: 0px 0px 0px 0.4px rgba(111,111,111,0.2); overflow: clip; mix-blend-mode: darken`

**Observed:** A broad rounded scene carries a short declaration; blue, pale light and warm yellow colour extend to its edge.

**Transfer:** Give the product's central promise a bounded gradient field and concise type rather than an additional feature grid.

#### Iridescent method panel · level 1

**Only for:** culture and method narratives

**Use:** A bounded, colourful statement with pale photographic motion behind its heading.

**CSS:** `background-image: linear-gradient(255deg, #facb0e, #f06ba8 30%, #78bae6 65%, #ffffff); border-radius: 9.5px; padding: 30.5px; overflow: hidden`

**Observed:** A wide panel about 1165px × 610px pairs uppercase copy at the top with translucent white flower imagery. A second full-inset gradient layer swaps the pink and yellow ordering.

**Transfer:** Use a single oversized pale organic or material study under the words, rather than many decorative thumbnails.

## Components

### Fixed navigation

**Use:** Persistent identity and a few high-level destinations without a full-width header bar.

**CSS:** `padding: 19px; position: fixed; z-index: 1000`

**Text style:** `label` — Ataero Retina OB Edition 400 · 15.2px/1 · uppercase

**Observed:** Identity sits top left, two slim underlined destinations and a contact capsule sit top right. A tiny solid dot anchors the lower left, while Menu control anchors the lower right. The open page remains visible through the centre.

**Transfer:** Keep only the most important destinations in this heads-up frame.

### Menu control

**Use:** Persistent lower-right navigation affordance.

**CSS:** `width: 46px; height: 46px; background: #e5e4e0; border: 1px solid rgba(111,111,111,0.2); border-radius: 9.5px`

**Observed:** Three fine horizontal strokes are centred in the compact rounded square; it is separate from the top navigation.

### Closing capsule

**Use:** Primary conversational conversion action in the closing headline.

**CSS:** `display: flex; position: relative; align-items: center; justify-content: center; width: 305px; height: 75px; border: 1px solid rgba(111,111,111,0.2); border-radius: 9999px; color: #1d1d1d; background: #e5e4e0`

**Text style:** `action-large` — Ataero Retina OB Edition 400 · 24.4px/1 · uppercase

**Observed:** A short label and right arrow sit together inside a pale outlined capsule, embedded beside a short line of the invitation rather than centred beneath the entire block.

**Transfer:** Change the verb to the new product's next step while preserving the calm, wide capsule.

### Small capsule

**Use:** Secondary actions inside proof and content panels.

**CSS:** `height: 42px; width: 171px; background: #e5e4e0; color: #1d1d1d; border: 1px solid rgba(111,111,111,0.2); border-radius: 95.2px; overflow: hidden`

**Text style:** `label` — Ataero Retina OB Edition 400 · 15.2px/1 · uppercase

**Observed:** One-line uppercase label followed by a right arrow; not a saturated accent fill.

**States:** Declared: hover outline 0px; focus-visible outline 2px solid Highlight with outline-offset 2px; active outline 0px.

### Arrow text link

**Use:** Navigation and secondary editorial destinations.

**CSS:** `display: flex; justify-content: space-between; column-gap: 8px; padding-bottom: 4.6px; position: relative`

**Text style:** `label` — Ataero Retina OB Edition 400 · 15.2px/1 · uppercase

**Observed:** Short uppercase label followed by a small arrow. A faint track runs underneath the text width; external destinations use an up-right arrow. Footer columns stack these with 15.2px gaps.

**States:** Declared: hover outline 0px; focus-visible outline 2px solid Highlight with outline-offset 2px; active outline 0px.

### Project tile

**Use:** Image-first proof, featured examples and related work.

**CSS:** `display: flex; position: relative; flex-direction: column; justify-content: flex-end; padding: 30.5px; border-radius: 9.5px; overflow: hidden`

**Text style:** `caption` — Ataero Retina OB Edition 400 · 15.2px/1.4 · uppercase

**Observed:** A square image fills the tile edge to edge; the short caption is bottom left and a plus is bottom right. The inner media is slightly oversized at scale 1.05. Default gallery tiles are 455px square; a related-work row uses three smaller equal tiles.

**States:** Declared: hover outline 0px; focus-visible outline 2px solid Highlight with outline-offset 2px; active outline 0px.

**Transfer:** Use an actual product result, physical object or composed interface scene rather than a generic feature icon.

### Outline label

**Use:** Second line of a small section heading or terse metadata tag.

**CSS:** `border: 1px solid #1d1d1d; border-radius: 6.5px; padding: 3px 6.1px`

**Text style:** `eyebrow` — Ataero Retina OB Edition 400 · 15.2px/1 · tracking 0.05em · uppercase

**Observed:** A compact rectangle with lightly rounded corners, not a full capsule; it sits just below another rail label or above a listing title.

### Proof ledger row

**Use:** Compact recognitions, certifications or quantified proof without giant statistic tiles.

**CSS:** `position: relative; padding-bottom: 30.5px`

**Text style:** `micro` — Ataero Retina OB Edition 400 · 11.4px/1 · tracking 0.017em · uppercase

**Observed:** The left rail names the proof collection and carries a small raised total. Within the wide row: a two-digit index at left, a larger institution name in the middle and right-aligned proof categories with superscript counts. Faint full-width rules divide the rows; orbital lines remain behind them.

**Transfer:** Use verified milestones, benchmarks or credentials; preserve the index/name/detail hierarchy rather than making the count the headline.

### Opportunity row

**Only for:** recruitment listings

**Use:** Repeatable role listings over the open canvas and orb.

**CSS:** `display: flex; flex-direction: column; gap: 15.2px; background: #f4f4f4; border: 1px solid rgba(111,111,111,0.2); border-radius: 9.5px; padding: 22.9px`

**Text style:** `listing-title` — Ataero Retina OB Edition 400 · 34.3px/1 · uppercase

**Observed:** Outlined location label and role title align left; application action aligns right. A hairline separates this from a bottom row of contract and compensation metadata. The stack uses 16px gaps and rows about 168px high.

### Capability stack card

**Only for:** detailed service pages

**Use:** A compact numbered stack explaining the offer.

**CSS:** `position: relative; background: #f1f0ec; border: 1px solid rgba(111,111,111,0.2); border-radius: 9.5px 9.5px 0px 0px; padding: 15.2px 15.2px 30.5px; margin-bottom: -15.2px; transition: background-color 0.2s ease`

**Text style:** `capability-title` — Ataero Retina OB Edition 400 · 34.3px/1.3 · uppercase

**Observed:** A tiny two-digit number precedes a large uppercase title. Successive panels overlap so the stack looks like offset sheets; an expanded item can expose supporting prose.

### Testimonial card

**Only for:** testimonial sections

**Use:** Long-form social proof in a horizontal sequence.

**CSS:** `display: flex; background: #f1f0ec; border: 1px solid rgba(111,111,111,0.2); border-radius: 21px; overflow: hidden; width: 373px; min-height: 638px`

**Text style:** `body-large` — Ataero Retina OB Edition 400 · 18.3px/1.5 · tracking 0.011em

**Observed:** An inner wrapper adds 30.5px padding. A 61px circular portrait sits beside the organisation name and small uppercase attribution; the quote and Small capsule sit lower in the card. Three cards are visible with a fourth continuing beyond the right edge; 50px circular previous/next controls and a thin progress track sit underneath.

**Transfer:** Use named, permissioned feedback with a short role line; retain the tall editorial shape.

### FAQ row

**Only for:** FAQ sections

**Use:** Objection handling after the large proof chapters.

**CSS:** `display: flex; justify-content: space-between; align-items: center; border-top: 1px solid rgba(111,111,111,0.2); padding: 30.5px 0px 15.2px`

**Text style:** `question` — Ataero Retina OB Edition 400 · 30.5px/1.2

**Observed:** Question on the left, a plain plus on the right. The open row replaces the plus with a cross and exposes Answer text at up to 70% of the row width. Rows are not individual rounded cards.

## Imagery and graphics

### Pearlescent orb and orbital lines

**Use:** Signature emotional object in the opening and a recurring, sometimes edge-cropped background throughout the page.

**Observed:** A softly irregular sphere has a milky centre, pink left edge, yellow upper-right light and a blue lower rim. Its rounded silhouette is tangible but not metallic; soft highlights suggest translucent resin or soap-film material. Two huge, very fine dashed circles pass behind it and behind the text. Its apparent size and off-centre placement change across the narrative.

**Transfer:** Always include this soft material contrast to the blunt typography. Without 3D assets, use a gently distorted gradient sphere; a flat multicolour disk is not enough.

**Build:** Use a roughly 560px circular SVG or CSS-masked object inside a 720px square stage. Layer broad pink light at 10% 35%, yellow at 80% 10%, blue at 65% 95%, then a white radial bloom at 45% 55% with 0.65 alpha. Blur colour layers by 40px inside the mask, not outside its silhouette. Add a small soft white highlight near the upper-right edge and a darker translucent lower rim. Place two 1px dashed #bfbebe circles, roughly 900px–1200px across, behind the sphere; offset their centres slightly. Match the soft glow; exact gradient stops are not essential.

### Image-first proof artwork

**Use:** Featured examples, related results and product demonstrations.

**Observed:** The gallery mixes dark studio-lit physical objects, vivid editorial collage and glossy interface scenes. Artwork occupies nearly all of each square; captions are subordinate overlays. A blue-lit laptop, fluorescent patterned helmet, cut-paper portrait collage and glassy device render illustrate the range. The colour intensity belongs inside the media frame, not to the surrounding page.

**Transfer:** Compose a small set of distinct hero-quality results in a consistent square frame. Minimum version: a crisp product still or real interface on a dark atmospheric backing, with a single purposeful light source.

### Floating capability constellation

**Use:** An immersive capabilities chapter that brings multiple kinds of work into one open scene.

**Observed:** Rounded thumbnail rectangles of markedly different sizes float across and beyond the canvas, some overlapping. One much larger central image is backed by the orb; peripheral images sit along the edges and a short category label occupies the open middle. Dashed orbits connect the composition visually without connectors.

**Transfer:** Use several real use-case stills at different scales, with one hero image and restrained labels. Keep the background shared rather than drawing a card behind every label.

**Build:** Arrange one 470px-wide rounded hero image near centre-left and 5–8 supporting rectangles about 150px–230px wide around the outer edges, all clipped at 9.5px. Put the large orb behind the hero image and two offset dashed circles behind everything. Clip the scene at the viewport edges to imply continuation; preserve a clear text zone.

### Framed desktop and mobile studies

**Only for:** case studies

**Use:** Evidence chapters between short explanations.

**Observed:** Wide films and collages sit on pale ivory mats with 9.5px corners. A large horizontal demonstration alternates with paired square films, then two tall mobile screens with one offset lower than the other. Device content keeps its original vivid colours and dark UI; the marketing canvas stays light.

**Transfer:** Show actual product behaviour in generous frames. Pair one system-level overview with focused details and narrow-screen applications; keep UI typography inside the artwork separate from the marketing type.

### Portrait wall

**Only for:** culture pages

**Use:** Human proof in a three-column near-square grid.

**Observed:** Consistent head-and-shoulders portraits against neutral light grey, mostly dark clothing, frontal framing and natural colour. Names and roles sit along the bottom over a subtle dark gradient; a small light plus sits at the top right. The sphere can remain partly visible behind the grid.

**Transfer:** Use consistently lit real portraits with the same crop and backing, not varied lifestyle stock images.

### Loose line drawing

**Only for:** culture narratives

**Use:** A playful counterpoint to the portrait wall and orderly grids.

**Observed:** One thin dark continuous line loops across almost the full page width, crossing over and around an inset uppercase statement. It feels hand-drawn, not like a diagram.

**Transfer:** Use a single abstract looping gesture instead of literal illustrations of each sentence.

**Build:** Draw one unfilled SVG path in a wide viewBox with a thin charcoal stroke. Use long cubic Bézier curves, three loose loops and one large sweep into the lower-right corner; leave the text centre relatively open. Avoid nodes, arrows or multiple coloured strokes.

### Translucent botanical gradient study

**Only for:** culture and method narratives

**Use:** Organic imagery inside the Iridescent method panel.

**Observed:** Oversized pale flower petals dissolve into a lateral blue–yellow–pink colour field. Text sits across the top and a small plus marks the lower right; the image is soft and nearly translucent rather than sharply cut out.

**Transfer:** Use an original pale material, petal, fabric or sculptural study with the same luminous translucency.

**Build:** Place a white-on-transparent organic study at the centre of the gradient panel, enlarge it until it exceeds the frame, and lower its contrast with a white alpha veil. Keep large uninterrupted colour regions visible on either side.

### Icons

**Observed:** Small right or up-right arrows accompany labels rather than circular icon badges. The repeated project mark is a 30px filled plus; portrait marks are about 24px. The lower-right menu uses three fine horizontal lines. FAQ toggles are plain plus/cross marks.

**Transfer:** Use simple geometric signs, not a feature-icon library. Keep project plus marks light over dark media and ink over light surfaces.

## Section recipes

How recurring sections are built.

### First screen: Orbital staggered opening

**Observed:** The first 900px form an open, full-height stage on Warm canvas. Fixed navigation sits at the corners. Back to front: two faint dashed orbital circles, a central pearlescent object about 560px across, then three independent uppercase Display phrases. The first phrase begins toward the upper left and spans about half the page; the second anchors to the right around the sphere's middle; the third returns left near the bottom. Each line is 102.9px at weight 400 and line-height 1. The main object occupies roughly the central two-fifths of the width. A small scroll cue sits low on the right; Menu control and a tiny dot occupy the bottom corners. No supporting paragraph or large central CTA crowds this screen: the top-right contact capsule is the action, while the fuller proposition falls below the first 900px.

**Transfer:** Write a short promise that can be separated into three balanced phrases and compose them around the gradient sphere. The sphere is the minimum viable hero art when no original product film is available. Culture pages use a two-line 190.5px identity declaration; recruitment uses a 266.7px split word with the first listing overlapping its base. Case studies open with a right-heavy film and overlapping title; dedicated service pages use the inline-media headline variant.

**Avoid:** Do not reduce this to a centred heading, paragraph and pair of buttons above a small illustration. Do not put the whole headline in one rigid left-aligned column or hide the sphere behind a rectangular hero card.

**Text style:** `display` — Ataero Retina OB Edition 400 · 102.9px/1 · uppercase

### Inset statement and twin support columns

**Observed:** A Manifesto statement spans the broad central-right region with 152px breathing room. Below it, a narrow uppercase summary sits at the left inner grid line, with a separate short mixed-case paragraph farther right. The orb can enlarge and drift beyond the right edge while the words stay readable.

**Transfer:** Follow the visual promise with one explicit positioning statement and two unequal explanatory fragments, not several equal feature cards.

**Text style:** `manifesto` — Ataero Retina OB Edition 400 · 76.2px/1 · uppercase

### Label rail and proof field

**Observed:** Small Eyebrow text stays in the left rail while a broad field of logos or Proof ledger rows occupies the remaining columns. The outlined second label is separated by 8px. Ledger details use right alignment and raised counts rather than giant metric numerals.

**Transfer:** Use real customer signals, benchmarks or independent credentials and let the amount of proof determine the number of rows.

**Text style:** `eyebrow` — Ataero Retina OB Edition 400 · 15.2px/1 · tracking 0.05em · uppercase

### Staggered work gallery

**Observed:** A broad left rail holds the section label and a small action. Project tiles occupy the right eight columns in two square streams separated by 19px; their vertical starts are staggered. The enlarged orb remains visible through the generous open left side.

**Transfer:** Display outcomes or use cases as distinct visual stories, allowing one column to begin higher than the other.

### Capability constellation scene

**Observed:** Floating capability constellation imagery spreads across a 1364px-tall chapter with an oversized statement and category labels. The orb and rings bind the otherwise scattered media into one shared space.

**Transfer:** Use this required spatial collage device to show the breadth of a product through real outputs; vary where it appears without making its exact chapter length a template.

### Bounded colour declaration

**Observed:** Immersive statement panel occupies nearly the full width with 30.5px corners. A short uppercase declaration has the Scroll-statement recipe and the field carries luminous cool-to-warm colour.

**Transfer:** Give one concise differentiating promise a colour scene of its own. Reuse the sphere's lighting language rather than inventing a new decorative palette.

**Text style:** `scroll-statement` — Ataero Retina OB Edition 400 · 45.7px/1 · uppercase

### Monumental closing invitation

**Observed:** The ending is about 666px tall with 76px top breathing room. Display copy forms four lines on the left seven-column span, while three compact navigation columns occupy the right. Closing capsule sits beside a short third line. The final line contains a plus-like typographic interruption. Small utility links and a compact row of summary-service icons sit low left; a much larger identity anchors the lower right. Orbital lines remain visible behind it all.

**Transfer:** End with an original conversational invitation, a capsule embedded into the line structure, concise destination groups and a large new identity. Keep the low-left summary shortcut as a compact utility device when equivalent destinations exist. A dedicated service footer can instead restate its benefit in four terse stacked lines, include a small circular partner symbol and move legal links onto the bottom baseline.

**Text style:** `display` — Ataero Retina OB Edition 400 · 102.9px/1 · uppercase

### Numbered culture chapters

**Only for:** culture pages

**Observed:** A compact four-item side index accompanies an identity opening, Portrait wall, a Loose line drawing statement, an Iridescent method panel and a brief final belief over an oversized orb. Chapter statements use small parenthesised fractions beside 38.1px uppercase text.

**Transfer:** Use a small numbered chapter index for a human story, one hand-drawn interruption and one luminous method panel; use new chapter subjects rather than copying the original organisation's story.

**Text style:** `heading` — Ataero Retina OB Edition 400 · 38.1px/1.2 · uppercase

### Opportunity listing page

**Only for:** recruitment pages

**Observed:** The huge two-line Listing-display opening meets the first Opportunity row around the middle of the first screen. Repeated pale rows overlap the orb visually. A small prose-led invitation follows after a 152px pause, then the shared Monumental closing invitation.

**Transfer:** Make the practical opportunities easy to scan without losing the oversized opening typography.

**Text style:** `listing-display` — Ataero Retina OB Edition 400 · 266.7px/0.8 · uppercase

### Case-study evidence chapters

**Only for:** case studies

**Observed:** A large right-hand film fills most of the first screen, with a 102.9px title crossing its left edge and tiny client/service annotations below on the left rail. Next, a rounded question strip leads into an objective heading and prose. Wide films, paired square details and two staggered tall mobile studies alternate with concise labelled explanations. A three-tile related-results row follows a two-line offset display heading, then the shared ending.

**Transfer:** Present the challenge, system and outcomes through large real media; adapt the small metadata rail to the product's relevant technical details.

**Text style:** `display` — Ataero Retina OB Edition 400 · 102.9px/1 · uppercase

### Inline-media service promise

**Only for:** dedicated service landing pages

**Observed:** Four rows of 158.1px uppercase text share an inner 1165px span with rounded graphic and film inserts. The 0.8 line-height creates tightly packed capital rows; inserts have 21px corners and occupy the empty ends of lines. A supporting paragraph and two pale capsules sit immediately below. Later, a horizontal project deck leads to Capability stack cards, a Manifesto introduction, Testimonial cards, FAQ rows and a framed showreel before the benefit-led footer.

**Transfer:** Use a short benefit sentence with media-sized gaps. Replace each inline insert with a product behaviour, abstract material study or original product symbol, not arbitrary decorative images.

**Text style:** `service-display` — Ataero Retina OB Edition 400 · 158.1px/0.8 · uppercase

## Page flow

**Storyline:** visual promise → explicit positioning → tangible proof → capability or method depth → credibility and objections → conversational closing invitation

### Broad marketing introduction that sells a point of view through the quality of the work

1. **Visual promise** — Staggered uppercase phrases orbit a luminous object.
2. **Positioning** — Large inset statement followed by two unequal support columns.
3. **Social proof** — Small label rail beside a restrained logo field.
4. **Outcome proof** — Staggered image-first project gallery.
5. **Capability breadth** — Floating media constellation with category labels.
6. **Credibility** — Indexed recognition ledger with superscript totals.
7. **Differentiation** — Bounded immersive colour declaration.
8. **Closing call** — Monumental invitation, embedded capsule, compact navigation and bottom identity.

**Transfer:** Keep the contrast between emotional spectacle and practical proof; change the amount and placement of proof to fit the product.

### Human and method narrative that makes an organisation feel distinctive and approachable

1. **Identity** — Oversized two-line declaration with an orb.
2. **Human proof** — Three-column portrait wall with bottom annotations.
3. **Belief** — Numbered statement crossed by a continuous line drawing.
4. **Method** — Luminous organic panel and contrasting method/tool tiles.
5. **Purpose** — Short final belief beside a greatly enlarged orb.
6. **Closing call** — Shared monumental invitation and complete navigation footer.

**Transfer:** Use people, working methods and an original belief rather than treating this as a second feature page.

### Recruitment page that brings practical listings into the visual identity

1. **Invitation** — A giant split-word opening in front of the orb.
2. **Opportunities** — Single stack of pale metadata-rich listing rows.
3. **Alternative contact** — Short heading and paragraph with an underlined email action.
4. **Closing call** — Shared large invitation and complete footer.

**Transfer:** Use the type-led opening to attract attention, then move quickly into useful listing information.

### Evidence-led case study connecting a challenge to a scalable system and its visible outputs

1. **Outcome preview** — Overlapping title, client/service rail and dominant product film.
2. **Challenge and objective** — Small section labels, rounded question and uppercase objective over prose.
3. **Demonstration** — Large framed overview film.
4. **Approach** — Short labelled explanation and paired square detail films.
5. **System proof** — Concise engineering explanation and wide composed product study.
6. **Device breadth** — Two tall staggered mobile screens with a short caption.
7. **Related outcomes** — Offset display heading above three image tiles.
8. **Closing call** — Shared invitation footer.

**Transfer:** Prioritise actual product evidence, explain why decisions matter, and end with adjacent outcomes rather than an abrupt legal strip.

### Detailed service or solution landing page that makes a complex offer feel simple

1. **Benefit promise** — Packed four-line display with inline media, support copy and two capsule actions.
2. **Social proof** — Overlapping horizontal project deck.
3. **Capability depth** — Numbered stack with large uppercase titles.
4. **Customer endorsement** — Large introduction followed by tall quote cards and slider controls.
5. **Objection handling** — Ruled FAQ with a first expanded answer and plus toggles.
6. **Emotional reminder** — A bounded cinematic showreel.
7. **Closing call** — Four-line benefit restatement with embedded action, partner symbol, navigation columns and large identity.

**Transfer:** Use this denser variant when the offer needs explanations and reassurance, while retaining the light ground and oversized words.

## Writing

Confident and playful, with creative ambition expressed in ordinary conversational language. The large statements are bold in intent rather than formal or technical; practical supporting copy becomes more specific about process and outcomes.

**Do not copy:** Do not reuse the brand name, wordmark, distinctive source slogans, client names, award counts, recruitment facts, product claims or customer quotations. Examples are references for structure and tone only; use original copy and substantiated proof for the new product.

- **Addressing the reader:** Use we for the maker and you for the reader; closing language invites collaboration rather than issuing a sales command.
- **Rhythm:** Short capitalised phrase groups carry the visual headlines. Statements can run longer across several deliberate lines; support paragraphs are compact and mixed-case. Plus signs interrupt selected words or pair ideas, not every sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Three simple phrase fragments that together communicate a different point of view. | 4–8 words | “A different Creative approach”<br>“We make Enterprise look nice AND Easy.” |
| Manifesto | An active sentence pairing emotional and practical strengths with a plus sign. | 10–20 words | “With EMOTION + INNOVATION, We push THE BOUNDARIES OF DIGITAL CREATIVITY.” |
| Support | Explain how the approach works in plain language, moving from a reader situation to a concrete working method. | 2–4 short sentences | “Every brand has a story, from startups finding their voice to titans refining their legacy.” |
| Evidence heading | Name an outcome or engineering objective without marketing punctuation. | 3–12 words | “Deliver a cohesive DESIGN SYSTEM and an incredible web experience”<br>“Engineered for scale” |
| Action | Simple verb phrase; directional arrow supplies the energy. | 2–3 words | “Get in touch”<br>“go big” |
| Closing invitation | A casual question broken into monumental lines, ending on a shared action or togetherness idea. | 9–16 words | “How about we do a thing or two, To+Gether” |
| Question | Ask the reader's actual practical concern in sentence case. | 4–14 words | “Should I be concerned about vendor lock-in?” |

**Words and phrasing to use:** different; make; together; possibilities; emotion + innovation; scale; shape; build; look nice; go big

**Avoid:** revolutionary ecosystem; unparalleled synergies; unlock limitless potential; enterprise jargon without an example; aggressive urgency or countdown language

**Rules:**

- Let the large headline sound simpler than the technology it introduces.
- Use one meaningful plus-sign pairing or word interruption in a major composition, not as a substitute for all conjunctions.
- Keep technical specificity in evidence chapters and FAQs, not in the emotional opening.
- Lead proof with what was made or changed, then explain the underlying system.
- Make the final action feel like the beginning of a conversation.

## Do's and Don'ts

### Do

- Use regular 400-weight uppercase Display at 102.9px/1 for the core large-word compositions.
- Keep the 19px outer gutter and twelve-column alignment visible even when objects appear to float.
- Stage a roughly 560px pearlescent object with two faint dashed rings in the opening.
- Use the 9.5px radius for ordinary media and reserve the 21px variant for testimonial and service inserts.
- Keep small labels near 15.2px; use 11.4px type for indices and raised proof annotations.
- Place captions and plus marks inside the image frame with about 30.5px inset.
- Keep long explanatory prose narrower than the media, with 18.3px/1.5 for case-study paragraphs.
- Give the closing invitation 102.9px lettering and let the 305px × 75px capsule join its line structure.

### Don't

- Do not replace the warm #e5e4e0 ground with a bright-white SaaS canvas or dark page theme.
- Do not use the pink, yellow or blue as default solid action fills; their job is luminous art.
- Do not add broad drop shadows to each card; use the 1px low-alpha edge instead.
- Do not force 21px corners onto the square project gallery; its default is 9.5px.
- Do not turn recognition counts into giant dashboard statistics; preserve tiny raised counts and ledger rows.
- Do not make body paragraphs uppercase merely because display text is uppercase; explanations and quotations are mixed-case.
- Do not place feature icons in coloured circles above every paragraph; the recurring marks are arrows, pluses and a three-line menu.
- Do not make the ending a dark utility band with a small heading; it is a second oversized text composition.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains fixed while the content moves; the orb and orbital outlines recur at changing scales and positions across the narrative.
- Declared transitions include transform 0.6s, transform 0.6s cubic-bezier(0.165,0.84,0.44,1), transform 0.4s cubic-bezier(0.68,-0.55,0.265,1.55), opacity 600ms ease and background-color 0.2s ease.
- Actions use clipped label wrappers and a repeated text layer offset by one line, supporting a rolling-label treatment.
- FAQ presentation includes a plus for closed questions and a cross for the open question; testimonial controls include a progress track.

**Transfer:**

- Keep motion concentrated in the orb, media placement and clipped label movement; leave the underlying grid legible.
- Maintain the slow spatial feeling of the shared object instead of adding unrelated animations to every text block.

**Unknown:**

- Exact scroll-to-orb mappings, label trigger timing and the full immersive panel sequence are not specified.
- Declared easing does not establish a duration for every scene or interaction.

### Responsive

**Observed:**

- Styles declare width breakpoints at 479px, 497px, 767px, 768px, 991px and 992px.
- The default body size uses 1.0582vw at the desktop width.

**Transfer:**

- On narrow screens, preserve the three-phrase opening and orb as one composition, reducing their scale together while protecting readable labels.
- Stack the two project streams and prose rails rather than squeezing metadata into narrow columns; preserve the tile's square framing and inset caption relationship.
- Reflow the four-line closing invitation above the navigation groups; keep the action adjacent to a short phrase when space permits.

**Unknown:**

- Exact mobile typography, gutter sizes, menu expansion and breakpoint-specific column changes are not established. Narrow-screen reflow rules above are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
