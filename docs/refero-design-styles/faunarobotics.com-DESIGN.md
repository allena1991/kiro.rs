# Fauna Robotics — engineered block play

## Overview

A warm, approachable technology style that makes capable products feel at home around people. Cream backgrounds and near-black grotesk type carry a sparse layout, interrupted by chalky jewel-colored geometry and large, naturally lit product films. It suits tangible products and developer platforms that need both technical credibility and a sense of delight.

### Essentials

- Friendly declarations, not technical billboards: centered Matter 64px/1.03, weight 500, -2px tracking headlines form compact two- or three-line promises.
- The opening gives the product room to live: a 640px headline measure above an almost full-width film, with 32px side gutters, 64px corners and an 80px heading-to-media interval.
- Conversion controls look like joined toy parts: the coral primary action is 60px tall with 32px 8px 8px 32px corners, paired with a navigation capsule rounded in the opposite direction.
- Cream remains the dominant canvas; color arrives in concentrated islands rather than a full-page wash: blue #63a4bc, coral #f16b46, mustard #dbb154, green #3dac91, brick #a7625a and pink #e0a5cf form flat graphic blocks.
- Geometry is a required brand-language device: circles, arches, rings and quarter-rounded squares appear as feature emblems and a monumental stacked closing sculpture. Rebuild these in SVG when bespoke artwork is unavailable.
- Product proof alternates cinematic wide scenes with 32px-radius bento cards on #ece4d7; real spaces, people and close-up material details outweigh interface mockups.
- The ending feels like a playroom opening into an index: a 99.2px/0.93 conversion headline above colorful block figures, followed by a 64px-top-corner footer fading softly back into cream.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Chalk blue | `#63a4bc` | `--color-blue` | surface, action, accent | Secondary actions, video play buttons and geometric blocks. |
| Tomato coral | `#f16b46` | `--color-coral` | action, link, accent, surface | Primary actions, link hover color, technical line drawings and flat graphic modules. |
| Mustard | `#dbb154` | `--color-gold` | surface, accent | Circular blocks, arches and selected capability controls. |
| Sea green | `#3dac91` | `--color-green` | surface, accent | Rounded geometric blocks and capability markers. |
| Clay red | `#a7625a` | `--color-brick` | surface, accent | Flat bowls, blocks and geometric ornaments. |
| Soft orchid | `#e0a5cf` | `--color-pink` | surface, accent | Crosses, discs and sculpture modules; expanded into broad statement panels only for organization storytelling. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cream | `#f8f0e3` | `--color-canvas` | background, text | Dominant page canvas and light lettering on colored controls and panels. |
| Translucent oat | `#ede4d8` | `--color-soft` | surface, border | Navigation fill and visible 5% warm-black washes over cream; subtle edges use the source ink at 5% alpha. |
| Oat | `#ece4d7` | `--color-card` | surface | Bento cards and technical gallery backing. |
| Taupe | `#aca396` | `--color-secondary` | text, action | Low-priority footer text and chapter-control hover fills. |
| Warm gray text | `#9e9089` | `--color-muted` | text | Supporting paragraphs; visible result of rgba(24, 1, 2, 0.4) over cream. |
| Warm black | `#180102` | `--color-ink` | text, border, action | All primary type, active technical tabs and dark hover fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detailed product pages | Sand | `#ded2c0` | `--color-rule` | border, surface | Technical dividers and inactive chapter controls. |
| detailed product pages | Inactive text | `#938a7d` | `--color-inactive` | text | Inactive product chapter labels. |
| organization storytelling | Drawing paper | `#efe6d8` | `--color-illustration` | surface | Backing behind large technical line art. |

## Typography

- **Matter** — All marketing headings, paragraphs, navigation and controls. Rounded, closely fitted contemporary grotesk with approachable geometric forms; medium weight throughout. If unavailable, use **DM Sans**. Use weight 500 and retain the tight headline tracking. Font stack: "Matter", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| monumental | Matter | 500 | 99.2px | 0.93 | -0.0101em | size clamp(6.2rem, 5vw, 7.625rem) | Closing invitation and oversized emotional statements. |
| headline | Matter | 500 | 64px | 1.03 | -0.03125em | fixed | Default opening and major section headings, centered and deliberately line-broken. |
| section | Matter | 500 | 42px | 1.14 | -0.0238em | fixed | Capability leads and the largest bento-card title. |
| statement | Matter | 500 | 32px | 1.18 | -0.0156em | fixed | Footer brand statement and labels on large colored shapes. |
| card-heading | Matter | 500 | 24px | 1.25 | -0.021em | fixed | Feature-card headings and audience headings. |
| control | Matter | 500 | 16px | 1 | normal | fixed | Navigation, primary actions, pills, technical rows and compact captions. |
| body | Matter | 500 | 16px | 1.5 | normal | fixed | Supporting paragraphs, footer supporting text and video-button labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| cinematic product introductions | product-name | Matter | 500 | 52px | 0.76 | -0.0192em | fixed | Short product name over a full-screen film. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use one medium grotesk throughout rather than adding a contrasting serif or mono for technical authority.
- Compact headings sit over much smaller supporting copy; preserve the jump from 64px to 16px.
- Paragraphs use 24px leading while controls use 16px; do not treat these as interchangeable.
- Large text usually centers; statement cards and the footer are left-aligned. Do not introduce a routine uppercase eyebrow system.

## Layout

**Density:** Airy at section scale, tightly packed inside graphic and media groups; long cream intervals separate large visual chapters.

### Spacing

**Spacing system:**

- **horizontal grid** 8px, horizontal — Underlying horizontal spacing with 16px, 24px, 32px, 48px and 64px tokens.

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing. |
| 16px | Default page gutter and bento grid gap. |
| 24px | Compact internal padding and paragraph-to-card-heading spacing. |
| 28px | Audience heading-to-paragraph interval. |
| 32px | Hero side gutters, card side padding and internal stacks. |
| 48px | Top inset for bento cards and statement-card horizontal padding. |
| 56px | Statement-card vertical padding. |
| 64px | Footer padding, chapter section padding and closing heading-to-action separation. |
| 80px | Opening heading-to-film interval. |
| 96px | Section heading-to-bento interval. |
| 124px | Oversized gallery heading-to-media separation. |
| 144px | Footer main-content-to-legal-row gap. |
| 296px | Major overview chapter separation. |

### Containers and grids

- **wide canvas**: max width 1920px · side padding 16px. Default centered content shell for bento, films and product chapters.
- **opening shell**: max width 1920px · side padding 32px. Slightly more inset opening film and navigation.
- **headline measure**: max width 640px. Centered short promise, usually split across two lines.
- **bento**: 3 columns · gap 16px. Three equal-width columns with unequal card heights and stacked media.
- **audience row**: max width 1085px · 3 columns · gap 78.1px. Three centered audience summaries below a film.
- **story container** (only for organization storytelling): max width 1280px · gap 16px · side padding 16px. More inset narrative cards; asymmetric 3:2 split.
- **technical pair** (only for detailed product pages): 2 columns · gap 16px. Half-width technical index beside a product gallery.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature cards | 32px |
|  | large films and statements | 64px |
|  | compact video button | 8px |
|  | pills | 40px |
|  | circles | 50% |
| detailed product pages | chapter panel | 20px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Continuous background through most of the page.

**CSS:** `background: #f8f0e3; color: #180102`

#### Oat card · level 1

**Use:** Feature groupings and product gallery.

**CSS:** `background: #ece4d7; border-radius: 32px; overflow: hidden; box-shadow: none`

**Observed:** Tonal separation replaces outlines and elevation.

**Transfer:** Use a flat warm backing for content that needs a boundary.

#### Soft glass · level 1

**Use:** Navigation and understated information pills.

**CSS:** `background: #ede4d8; backdrop-filter: blur(44px)`

**Observed:** The navigation has a solid oat appearance; other floating controls use warm-black alpha washes.

**Transfer:** Keep glass warm and low contrast rather than glossy or cool blue.

#### Footer fade · level 0

**Use:** Wide closing index.

**CSS:** `background: linear-gradient(0deg, rgba(216, 205, 194, 0) 7.18%, rgba(216, 205, 194, 0.5) 59.75%); border-radius: 64px 64px 0px 0px`

**Observed:** A sand-gray upper region disappears into the page canvas with no lower boundary.

**Transfer:** Preserve the fade instead of enclosing the footer in a fully painted card.

#### Color statement · level 1

**Only for:** organization storytelling

**Use:** Mission and narrative statements.

**CSS:** `background: #e0a5cf; color: #f8f0e3; border-radius: 64px; padding: 56px 48px`

**Observed:** Pink, mustard, brick, green and coral panels vary in size; text stays light.

**Transfer:** Use a few broad flat colors to make an editorial collage rather than applying them to every section.

## Components

### Navigation capsule

**Use:** Persistent top navigation beside a separate primary action.

**CSS:** `display: flex; align-items: center; gap: 32px; padding: 24px 28px 24px 24px; background: #ede4d8; backdrop-filter: blur(44px); border-radius: 8px 32px 32px 8px`

**Text style:** `control` — Matter 500 · 16px/1

**Observed:** Logo sits alone at left; the link capsule joins visually to the action at right. The header is fixed, 124px tall, with 32px top and side inset. During deeper scrolling the action remains the visual anchor.

### Primary button

**Use:** Main conversion, in the header and closing invitation.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 60px; padding: 0px 24px 0px 28px; background: #f16b46; color: #f8f0e3; border: 1px solid #f16b46; border-radius: 32px 8px 8px 32px`

**Text style:** `control` — Matter 500 · 16px/1

**Observed:** Text-only coral control; the asymmetry makes the left edge soft and the right edge clipped.

**States:** Declared: hover background-color #180102, color #f8f0e3, border 1px solid #180102; active outline 0px. No focus-visible treatment is specified.

### Secondary button

**Use:** Broad supporting navigation and document actions.

**CSS:** `background: #63a4bc; color: #f8f0e3; border: 1px solid #63a4bc; border-radius: 32px; padding: 19px 24px 19px 28px; display: flex; align-items: center; justify-content: center; gap: 8px; height: 60px`

**Text style:** `control` — Matter 500 · 16px/1

**Observed:** Fills the width of a narrow story column. Technical document variants are 72px tall; an outlined report companion uses a 2px warm-black 20% border.

**States:** Declared: hover background-color #180102, color #f8f0e3, border 1px solid #180102; active outline 0px. No focus-visible treatment is specified.

### Video play

**Use:** Centered invitation over a cinematic poster.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 16px; background: #63a4bc; color: #f8f0e3; border: 1px solid #63a4bc; border-radius: 8px`

**Text style:** `body` — Matter 500 · 16px/1.5

**Observed:** A small solid play triangle precedes the label; sits in the center of a very large film rather than a separate toolbar.

**States:** Declared: hover background-color #180102, color #f8f0e3, border 1px solid #180102; the same treatment is declared on ancestor hover.

### Feature card

**Use:** Capability explanation within a bento.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: space-between; background: #ece4d7; border-radius: 32px; padding: 48px 32px 44px 32px; overflow: hidden`

**Text style:** `card-heading` — Matter 500 · 24px/1.25 · tracking -0.021em

**Observed:** A small geometric emblem sits above a centered heading; the lower area holds a diagram, close-up product image or film. Neighboring cards can instead be full-bleed media or use the larger section title.

**Transfer:** Vary card heights and visual content while retaining three equal-width columns.

### Information pill

**Use:** Short inclusion statement paired with the closing action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 60px; padding: 0px 24px; background: rgba(24, 1, 2, 0.05); border-radius: 40px; color: #180102`

**Text style:** `control` — Matter 500 · 16px/1

**Observed:** A subdued, non-action capsule touches the primary action with a 4px gap.

### Geometric category block

**Use:** Broad audience or application labels in a graphic strip.

**CSS:** `background: #63a4bc; color: #f8f0e3; width: 477px; height: 477px; position: relative`

**Text style:** `statement` — Matter 500 · 32px/1.18 · tracking -0.0156em

**Observed:** The square is one of four overlapping shapes: a mustard circle, brick bowl and green quarter-rounded square accompany it. Text alternates top-left and centered positions; small glyphs project beyond the edges.

**Transfer:** Use broad new categories, not a standard row of outlined cards.

### Footer index

**Use:** Final navigation and brand statement on every page type.

**CSS:** `display: flex; flex-direction: column; gap: 144px; padding: 64px; background: linear-gradient(0deg, rgba(216, 205, 194, 0) 7.18%, rgba(216, 205, 194, 0.5) 59.75%); border-radius: 64px 64px 0px 0px`

**Text style:** `control` — Matter 500 · 16px/1

**Observed:** Left column holds a 32px statement and muted origin line. Three smaller columns hold exploration, organization and social links. A contact link sits beneath the first link group; copyright and legal links occupy a distant bottom row. Overall region is 656px tall, with a 16px outer inset.

### Chapter control

**Only for:** detailed product pages

**Use:** Switch between film demonstrations within a capability chapter.

**CSS:** `background: #ded2c0; color: #938a7d; padding: 16px; height: 48px; border-radius: 40px`

**Text style:** `control` — Matter 500 · 16px/1

**Observed:** Three or four full-width pills stack with 4px gaps at the bottom of a narrow panel. One selected pill uses a chapter-specific blue, coral, mustard or green fill with light text.

**States:** Declared: hover background-color #aca396 and color #f8f0e3. No focus-visible treatment is specified.

### Specification row

**Only for:** detailed product pages

**Use:** Compact technical facts below category tabs.

**CSS:** `display: flex; justify-content: space-between; padding: 12px 0px; border-bottom: 2px solid #ded2c0`

**Text style:** `control` — Matter 500 · 16px/1

**Observed:** A one-third category label sits beside two-thirds detailed rows; values align right. The whole index sits in an Oat card with pill tabs above and document actions below.

**Transfer:** Present real decision-making facts in rows rather than converting them to oversized statistics.

## Imagery and graphics

### Everyday product films

**Use:** Opening, demonstration chapters and feature media.

**Observed:** Real product in warm studios, workshops and ordinary human rooms, with plants, timber flooring, light walls and visible people. Wide shots show use at human scale; close-ups isolate expressive or tactile details. Natural soft lighting and slightly subdued color contrast with the flat graphic accents. Main films nearly fill the content width and use 64px or 32px corners.

**Transfer:** Photograph the new product in an authentic place of use, include hands or people, and show one legible interaction. Minimum version is a high-quality still with the same framing and a play action only if video exists.

### Block sculpture

**Use:** Signature conversion artwork and recurring miniature feature emblems.

**Observed:** Flat rings, discs, crosses, arches, squares and one-corner curves stack into loosely anthropomorphic towers across the full width beneath the closing invitation. Cream holes cut through the colored pieces; there are no outlines, shading or 3D extrusion.

**Transfer:** Create new abstract assemblies in the same geometric vocabulary. The minimum version is a static SVG of several unequal-height towers, not generic clip-art robots.

**Build:** Use an SVG viewBox 0 0 1440 720. Assemble modules on an approximately 150px grid: solid squares, circles, half-round bowls and quarter-rounded paths. Cut ring centers and arch openings with masks revealing the cream background. Rotate one ring-bearing square 45 degrees; construct a rounded cross from two thick diagonal bars. Alternate coral, blue, gold, green, brick and pink. Stack towers at different heights with side arms and a broad central gap beneath the action. Keep all edges crisp and unshadowed.

### Human-scale gallery

**Use:** Emotional proof before the closing invitation.

**Observed:** A horizontal belt of tall rounded videos shows informal product interactions, play and practical experiments in real rooms. Edge tiles extend beyond the viewport; the heading is monumental and centered.

**Transfer:** Use short authentic clips or portrait stills showing distinct use moments. Keep the candid room context rather than turning each image into a polished advertisement.

### Partner belt

**Use:** Trust and institutional proof.

**Observed:** Muted monochrome logos sit centered inside warm tonal tiles with mixed round and arched silhouettes. The belt extends off both edges and fades into cream at its ends.

**Transfer:** Use only genuine partners or comparable proof marks; if there are no partner logos, retain the graphic tile language for credible short proof statements.

**Build:** Arrange low-contrast oat tiles in a horizontal overflow-hidden row; alternate 64px rounded rectangles and half-rounded silhouettes. Add 108px-wide cream-to-transparent overlays at both ends. Keep the marks visually subordinate to the product media.

### Technical product studies

**Only for:** detailed product pages

**Use:** Feature close-ups and the technical gallery.

**Observed:** Isolated full-body and component renders on oat with soft contact shadows, sage surfaces and bright physical accents. The gallery pairs one large render with a small thumbnail strip, outlined active thumbnail and compact finish swatches.

**Transfer:** Use neutral-backed renders or clean product photographs, matching camera angle and scale across the gallery. Product colors belong to the product rather than the marketing palette.

### Letterform play

**Only for:** detailed product pages

**Use:** A full-screen typographic interlude between introduction and capabilities.

**Observed:** A very large three-line statement occupies roughly two-thirds of the width. Selected rounded letters become colored discs, rings and arch shapes without losing readability.

**Transfer:** Use a short new promise with a handful of geometric letter substitutions; a static HTML/SVG composition is sufficient.

**Build:** Center a 997px-wide text-and-SVG group in a 900px-tall cream section. Use approximately 108px medium grotesk type with tight tracking and about 104px line spacing; replace a few o-shaped glyphs with pink discs or green and gold rings, and an n-shaped glyph with a brick or green arch. Keep most letters warm black and preserve word silhouettes.

### Engineering line portrait

**Only for:** organization storytelling

**Use:** Large visual counterweight to colored narrative panels.

**Observed:** Dense coral-red transparent technical contours reveal internal assemblies of a product, enlarged until parts run beyond a 739px by 839px paper-backed card with 64px corners.

**Transfer:** Use a wireframe or line illustration of the new product or its construction. Minimum version is an authentic simplified contour drawing with a few interior structural details, not an invented engineering diagram.

**Build:** Place coral SVG contours over the drawing-paper surface. Layer exterior paths at stronger opacity over internal paths at approximately 0.2–0.4 opacity; omit fills except very faint coral washes. Enlarge to fill the card and clip at its edges.

### Icons

**Observed:** Utility arrows use 20px SVGs with 2px rounded strokes in warm black; play triangles are solid light shapes. Feature emblems are 24px or larger flat geometric glyphs, not detailed pictograms.

**Transfer:** Use restrained arrows and play controls for utility; construct feature symbols from the block-art vocabulary rather than mixing a large line-icon set.

## Section recipes

How recurring sections are built.

### First screen: Promise over living product

**Observed:** A cream first screen places the logo at upper left and Navigation capsule plus Primary button at upper right. The centered headline uses the headline recipe at a 640px maximum measure, starting with a 172px top inset. Its two-line promise occupies a compact central island, not the full width. After an 80px interval, a 1376px-wide, 64px-corner film begins within 32px side gutters. Layers are cream, headline and header, then the real-room film with the product embedded in its environment. Within the first 900px the complete headline, persistent action and upper majority of the product scene are visible; the rest of the film and trust belt continue below. There is no separate supporting paragraph or CTA row under the headline.

**Transfer:** Use an equally compact promise above a convincing real-world product scene; without film, use a full-width still with people or context. Organization introductions use the same headline-over-film logic in a more inset 1248px field. Cinematic product introductions instead make the film almost the entire first screen, place a 52px product-name overlay low in the center, and add a small frosted video preview at lower right.

**Avoid:** Do not turn this into a left-copy/right-render SaaS hero or cover the scene with a paragraph, badge stack and several competing actions.

**Text style:** `headline` — Matter 500 · 64px/1.03 · tracking -0.03125em

### Demonstration and audience summaries

**Observed:** A centered headline precedes a huge 64px-corner film with Video play at its center. Three centered audience summaries sit beneath, using card-heading and body recipes, 28px internal intervals and a 1085px total measure.

**Transfer:** Pair an impressive demonstration with three distinct reasons different users should care.

**Text style:** `headline` — Matter 500 · 64px/1.03 · tracking -0.03125em

### Capability bento

**Observed:** A centered headline leads into a three-column 16px-gap grid after 96px. Feature card cells alternate abstract diagrams, isolated detail renders, concise explanations and full-bleed real-world videos; heights stagger across columns.

**Transfer:** Mix explanatory and experiential proof; retain equal columns but vary the vertical rhythm.

**Text style:** `headline` — Matter 500 · 64px/1.03 · tracking -0.03125em

### Color-block categories

**Observed:** Geometric category block modules overlap across a 1376px strip about 524px tall. Four large silhouettes carry cream statement-sized labels; small colored glyphs protrude above and below.

**Transfer:** Use this device to group audiences, outcomes or modes into a memorable graphic landscape.

**Text style:** `statement` — Matter 500 · 32px/1.18 · tracking -0.0156em

### Origin and context pair

**Observed:** A large centered headline sits over a narrow tall pill-shaped Oat card beside a much wider real-location photograph. The narrow card centers a geometric emblem and 24px statement, with Secondary button below.

**Transfer:** Pair an origin, craft or process claim with a place or material image that makes it credible.

**Text style:** `headline` — Matter 500 · 64px/1.03 · tracking -0.03125em

### Playful invitation and index

**Observed:** A monumental centered invitation stands above an Information pill joined to Primary button. Block sculpture fills a 1440px by 720px artwork field beneath it. Footer index follows in a 16px-inset, softly fading field, with the brand statement left, three link groups right and muted legal information at the bottom. Organization storytelling ends after Partner belt directly in the same Footer index.

**Transfer:** Make the invitation concise and retain the large geometric artwork as a recognizable closing gesture; adapt the navigation groups to the new offering.

**Text style:** `monumental` — Matter 500 · 99.2px/0.93 · tracking -0.0101em

### Capability cinema

**Only for:** detailed product pages

**Observed:** A 1408px-wide 32px-corner film stage contains a 442px-wide inset control panel with 20px corners. The panel centers a geometric emblem and section-sized title, with Chapter control pills anchored at the bottom. Alternating chapters place it on opposite sides. A split variant separates the media and uses a panel with a deep rounded lower end. Sections use 64px top and bottom padding.

**Transfer:** Give each capability one dominant demonstration and a short selectable set of outcomes.

**Text style:** `section` — Matter 500 · 42px/1.14 · tracking -0.0238em

### Tactile proof triptych

**Only for:** detailed product pages

**Observed:** A centered emblem and section title sit over three differently proportioned media panels: narrow portrait, broad center, narrow detail. One portrait has an arched top. Small translucent dark caption pills float near the lower edges.

**Transfer:** Show overall use, human scale and a material close-up rather than three near-identical renders.

**Text style:** `section` — Matter 500 · 42px/1.14 · tracking -0.0238em

### Technical decision area

**Only for:** detailed product pages

**Observed:** Two Oat card columns pair a tabbed technical index with a large render gallery. Specification row groups use 2px sand rules, 16px text and right-aligned values. The image side includes finish dots and seven small rounded thumbnail buttons, active outline in ink. Document controls span the bottom of the index.

**Transfer:** Use only genuinely useful specifications; allow the gallery to substantiate physical details.

**Text style:** `section` — Matter 500 · 42px/1.14 · tracking -0.0238em

### Editorial color collage

**Only for:** organization storytelling

**Observed:** A 1248px-wide collage uses 16px gaps, 64px corners and 56px 48px padded Color statement panels. Small 24px and 42px statements contrast with one 99.2px mission panel; a 3:2 image-and-copy split accompanies the Engineering line portrait.

**Transfer:** Use unequal blocks for a narrative point of view, a broad ambition and a tangible explanation of the work.

**Text style:** `monumental` — Matter 500 · 99.2px/0.93 · tracking -0.0101em

## Page flow

**Storyline:** Promise → lived demonstration → audience relevance → capability proof → context and credibility → invitation → useful index; emphasize or compress beats to fit the page purpose.

### Broad marketing overview

1. **Promise** — Compact two-line declaration over a large real-world film and a muted trust belt.
2. **Product demonstration** — Wide cinematic poster and three audience summaries.
3. **Capability proof** — Staggered bento of diagrams, product details and films.
4. **Audience relevance** — Overlapping colored geometric category strip.
5. **Credibility** — Origin statement paired with place photography.
6. **Emotional proof** — Monumental short headline and candid portrait-media belt.
7. **Closing call** — Invitation, inclusion pill, primary action and stacked geometric artwork.
8. **Index** — Fading rounded footer with statement, links and legal row.

**Transfer:** Move between credible product experience and playful abstraction without requiring the same number of chapters.

### Organization narrative

1. **Purpose** — Centered statement over an origin-story film.
2. **Point of view** — Asymmetric colored statement cards with rows of geometric glyphs.
3. **Ambition** — Oversized light text on a broad pink panel.
4. **Tangible proof** — Technical line portrait beside coral and green narrative cards.
5. **Social proof** — Centered credibility headline and monochrome partner belt.
6. **Index** — Shared fading footer, without the separate illustrated conversion scene.

**Transfer:** Use the brighter editorial collage only when explaining the organization or its philosophy.

### Detailed flagship product presentation

1. **Introduction** — Near-full-screen film, low centered product name and small preview.
2. **Positioning** — Full-screen statement with geometric letter substitutions.
3. **Capability overview** — Three-column explanatory bento.
4. **Capability chapters** — Large films with alternating inset panels and selectable outcome pills.
5. **Objection handling** — Tactile media triptych and concise caption pills.
6. **Technical decision support** — Specification index beside render gallery, finishes and thumbnails.
7. **Closing call** — Shared monumental invitation and geometric sculpture.
8. **Index** — Shared fading footer.

**Transfer:** Give a complex product more room for demonstrated capability and decision details, while preserving the same warmth and geometric punctuation.

## Writing

Confident but companionable. Technical capability is described plainly, then softened by language about people, everyday spaces and enjoyment rather than futurist spectacle.

**Do not copy:** Do not reuse the Fauna Robotics or Sprout names, logo, partner identities, origin claims, product specifications, included items or mission as claims for another brand. Source examples illustrate voice only.

- **Addressing the reader:** Use 'we' for purpose and craft, 'you' or 'your' for developer agency, and straightforward product descriptions for technical detail.
- **Rhythm:** Short sentence fragments and paired declarations for headings; one compact explanatory sentence per supporting block. Repeated three-part phrases add a friendly cadence without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Three plain qualities followed by an inclusive promise. | 6–10 words | “Capable, safe, fun. Robots for everyone.” |
| Demonstration lead | A possibility followed immediately by present-tense availability. | 5–9 words | “Create new experiences. Shipping today.” |
| Supporting paragraph | Start with a concrete action, then state what the user can do and what makes it accessible. | 12–30 words | “Build and test your own applications on easy-to-use hardware with full SDK access.” |
| Capability title | Plain technical noun phrase, qualified by a useful human-facing trait. | 2–5 words | “Compliant, capable locomotion”<br>“Safety-first design” |
| Closing invitation | Short direct ownership invitation. | 3–4 words | “Make it yours” |
| Primary action | Concrete verb and tangible object. | 2–3 words | “Request Robot” |

**Words and phrasing to use:** build; capable; safe; fun; useful; delightful; everyday; ready; modular; full-stack; move from idea to prototype

**Avoid:** revolutionary; disruptive; unprecedented; supercharge; magic; the future is here; effortless everything

**Rules:**

- Ground ambitious statements in a demonstrated capability or practical detail nearby.
- Use technical vocabulary when it clarifies a real function, not as a decorative badge.
- Let short warm headings coexist with precise supporting sentences.
- Keep conversion language direct and use one primary request consistently.

## Do's and Don'ts

### Do

- Keep default opening headlines at 64px, weight 500, with -2px tracking and compact line breaks.
- Use cream #f8f0e3 as the continuous field around the colored graphics.
- Preserve the 32px 8px 8px 32px primary-button silhouette.
- Keep bento gaps at 16px while allowing individual card heights to differ.
- Use 64px corners on the widest films and broad editorial panels.
- Include crisp geometric emblems and a substantial block-art moment, even when imagery is scarce.
- Keep body copy at 16px/24px and controls at 16px/16px.
- Finish with a softly fading footer rather than an abruptly boxed bottom band.

### Don't

- Do not replace the warm black #180102 with cool charcoal across the typography.
- Do not make the primary action a symmetric generic capsule; reserve symmetric pills for secondary controls and information.
- Do not add drop shadows to the flat oat bento system.
- Do not set the entire page in bright coral or green; concentrated graphic islands need cream around them.
- Do not add mono labels or uppercase tracked eyebrows to manufacture a technical tone.
- Do not put gradient fills, highlights or bevels inside the geometric block artwork.
- Do not inflate technical specifications into unrelated giant-number stat cards; retain the 16px ruled index treatment.
- Do not make every photograph an isolated studio render; everyday environments are a major part of the human tone.

## Motion and responsive

### Motion

**Observed:**

- Primary, secondary and play controls declare background-color 0.3s, color 0.3s, border 0.3s transitions.
- Chapter controls declare color and background-color 0.25s cubic-bezier(0.47, 0, 0.745, 0.715).
- Text-link color transitions include 0.2s cubic-bezier(0.25, 0.46, 0.45, 0.94).

**Transfer:**

- Use the declared color transitions to distinguish actions; keep the flat block geometry crisp through state changes.
- Let product films carry most of the visible activity rather than adding motion to every text block.

**Unknown:**

- Scroll choreography, media autoplay behavior and exact graphic animation timing are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 480px, 767px, 768px, 991px, 1024px and 1920px; the broad overview also includes 1279px and 1280px.

**Transfer:**

- On narrow layouts, preserve the promise-above-media hierarchy and the asymmetric conversion control.
- Stack bento and technical columns, keep caption pills attached to their media, and recompose geometric towers rather than shrinking every module into illegibility.

**Unknown:**

- Exact mobile type sizes, navigation behavior, gutter changes and stack order are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
