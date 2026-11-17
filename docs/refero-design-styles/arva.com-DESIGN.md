# Arva — fieldwork meets editorial

## Overview

An open, pastoral marketing style that pairs delicate editorial serifs with plain, light sans-serif explanations. Forest green, cream and sky blue create a grounded atmosphere, punctuated by tiny flashes of electric lime. Wide documentary imagery, people at work and restrained diagrams make technical offerings feel tangible and human; the pacing is expansive rather than dashboard-dense.

### Essentials

- The promise belongs inside a real-world scene: a near-viewport photographic stage sits in a 10px white frame with 18px corners, carrying a centered 65px serif headline at 1.06 line height.
- Headlines feel cultivated, not corporate-bold: light Reckless serif at 55px/1 for section leads and 45px/1 inside benefit panels, paired with Inter 17px/1.24 at weight 300.
- Color works in fields rather than confetti: white and cream carry the long reading passages, forest green anchors benefit panels and the entire footer, and sky blue gives a 523px closing band its own horizon. Electric lime is concentrated in the 26px announcement strip, small tags and selected actions, never a full-page wash.
- Actions are soft capsules with a mechanical endpoint: 49px high, 110px radius, 15px sans text, with a 35px white circular arrow docked at the right on conversion buttons; paired audience choices use sky blue and forest green.
- Proof is spatial and human: include large, thin numerals and a map or relationship graphic, plus pastel testimonial cards with a near-half-width documentary photograph. With no geographic story, use a fine-line network diagram and equally concrete original proof.
- End with an inhabited brand world: a forest-green footer combines a 424px newsletter column, a large fine-line map with lime location markers, and a three-line serif belief statement at clamp(24px, 3vw, 48px). Replace geography with an original network drawing when needed, but retain the drawing and belief device.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest | `#07503f` | `--color-forest` | background, surface, action, text, link | Core dark brand field, buttons, diagram lines and emphasized quote text. |
| Oat cream | `#f1efdf` | `--color-cream` | background | Broad editorial and capability bands. |
| Sky blue | `#b2cee7` | `--color-sky` | background, surface, action | Closing invitation band, secondary actions and selected capability panels. |
| Sage | `#c3cda7` | `--color-sage` | text, surface, accent | Footer contact text, map accents and subdued highlights. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric seed | `#e8fe85` | `--color-lime` | background, accent, action | Announcement strip, compact impact labels, selected CTAs and key location dots. |
| Testimonial blue | `#d7e6f5` | `--color-quote-blue` | surface | First testimonial panel backing. |
| Testimonial green | `#e4ebcf` | `--color-quote-green` | surface | Companion testimonial backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, surface, border | Main canvas, reversed type, button arrow discs and footer outlines. |
| Proof white | `#fdfdfd` | `--color-soft-white` | background | Light quantified-proof and reach field. |
| Mist | `#f8f8f8` | `--color-mist` | background, surface | Process bands, culture and partner-story fields. |
| Pale seed cream | `#f1f2e2` | `--color-benefit-cream` | surface | Light benefit panel and understated location label. |
| Metadata gray | `#6d6d6d` | `--color-muted` | text | Dates beneath editorial images. |
| Charcoal | `#353535` | `--color-ink` | text, border | Default headings and body on light fields. |
| Deep reading ink | `#212529` | `--color-deep-ink` | text | Small impact labels; technical and culture headings. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical solution pages | Proof card cream | `#fbfaf1` | `--color-stat-cream` | surface | Metric cards over photography. |
| technical solution pages | Technical white | `#fbfbfb` | `--color-technical-card` | surface | Overlapping explanatory cards. |
| technical solution pages | Technical edge | `#d5d5d5` | `--color-technical-rule` | border | Fine outlines on overlapping explanatory cards. |
| enterprise comparison and people sections | Space black | `#000000` | `--color-black` | background, text | High-contrast comparison chapter and portrait names. |
| enterprise comparison sections | Comparison rule | `#7c7c7c` | `--color-comparison-rule` | border | Horizontal dividers between comparison metrics. |

## Typography

- **Reckless** — Display, section headings, benefit titles, quotations and closing belief. High-contrast editorial serif with fine hairlines and an organic, literary voice; light cuts dominate. If unavailable, use **Newsreader**. Use light 300 and medium 500; preserve open tracking and compact headline leading. Font stack: "Reckless", "Newsreader", Georgia, serif.
- **Inter** — Body, navigation, actions and quantified proof. Clear neutral sans with light paragraphs and compact regular action labels. Font stack: "Inter", Arial, sans-serif.
- **FKGrotesk** — Impact tags and editorial metadata. Plain utilitarian grotesk, kept small beside expressive serif titles. If unavailable, use **Inter**. Use 300 for metadata and tags. Font stack: "FKGrotesk", "Inter", Arial, sans-serif.
- **Helvetica** — Newsletter text and submission controls. Neutral system sans used in the footer form. Font stack: "Helvetica", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Reckless | 100 | 65px | 1.06 | normal | fixed | Default scenic opening headline; use the light cut. |
| display-emphasis | Reckless | 300 | 65px | 1.06 | normal | fixed | A subtly stronger phrase inside the opening, not a bold slogan. |
| heading-lg | Reckless | 300 | 55px | 1 | normal | fixed | Main centered editorial section leads. |
| closing-heading | Reckless | 300 | 53px | 1 | normal | fixed | Single-line closing invitation. |
| benefit-heading | Reckless | 300 | 45px | 1 | normal | fixed | Benefit panel heading, often split into a lead and audience name. |
| belief | Reckless | 300 | 43.2px | 1 | -0.0116em | size clamp(24px, 3vw, 48px) | Three-line footer belief statement. |
| belief-emphasis | Reckless | 500 | 43.2px | 1 | -0.0116em | size clamp(24px, 3vw, 48px) | Middle line of the footer belief statement. |
| reach-heading | Reckless | 300 | 40px | 1.22 | normal | fixed | Multi-line narrative statement beside a reach graphic. |
| article-title | Reckless | 300 | 25px | 1.22 | normal | fixed | Editorial card titles beneath images. |
| body | Inter | 300 | 17px | 1.24 | normal | fixed | Support lines and descriptive paragraphs. |
| form-label | Helvetica | 300 | 17px | 1.24 | normal | fixed | Newsletter label and introduction. |
| metadata | FKGrotesk | 300 | 16px | 1.24 | normal | fixed | Editorial dates. |
| body-small | Inter | 300 | 15px | 1.24 | normal | fixed | Compact benefit explanations. |
| action | Inter | 400 | 15px | 1 | normal | fixed | Capsule labels; uppercase for principal marketing actions. |
| tag | FKGrotesk | 300 | 15px | 1 | normal, uppercase | fixed | Compact impact and geographic category labels. |
| announcement | Reckless | 500 | 14px | 1.3 | normal | fixed | Short serif announcement in the lime strip; medium cut. |
| testimonial | Inter | 400 | 14px | 1.47 | normal | fixed | Compact quotation paragraphs; emphasize a meaningful clause in forest green bold. |
| navigation | Inter | 400 | 13.6px | 1.1 | normal | fixed | Compact desktop navigation links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| technical solution pages | metric | Inter | 400 | 52px | 1 | -0.0385em | fixed | Primary values in cream proof cards. |
| technical solution pages | metric-unit | Inter | 200 | 52px | 1 | -0.0385em | fixed | Currency and magnitude suffixes beside metric values. |
| people, culture and enterprise process sections | culture-heading | Reckless | 300 | 50px | 1.22 | normal | fixed | Extended people statements, scenic quotations and process row headings. |
| technical solution pages | solution-heading | Reckless | 300 | 42px | 1 | normal | fixed | Compact technical hero and section leads. |
| enterprise comparison sections | comparison-value | Inter | 500 | 40px | 1 | normal | fixed | Before-and-after values. |
| enterprise comparison sections | comparison-unit | Inter | 100 | 40px | 1 | normal | fixed | Extremely thin units beside comparison values. |
| people directories | person-name | Reckless | 400 | 24px | 1.235 | normal | fixed | Names beside documentary portraits. |
| audience-specific scenic openings | audience-support | Inter | 300 | 22px | 1.24 | normal | fixed | Three-line support beneath a left-aligned promise. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The display voice is serif throughout; sans-serif is reserved for explanations, navigation and numeric proof. Strong tags inside large headings remain visually light rather than becoming weight 700.
- Most headline tracking stays normal. The footer belief alone tightens to -0.5px; metric cards tighten sans numerals to -2px.
- Use the light and medium cuts of the serif as one family. Keep the first-screen 65px treatment as the default; the 42px opening is a compact technical-page variant.

## Layout

**Density:** Airy across chapters, compact within explanations: broad media fields and long section pauses surround short, lightly set text.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Outer white frame around scenic media. |
| 18px | Gap between alternating benefit panels and photographs. |
| 20px | Action groups and compact flex groups. |
| 30px | Editorial grids, benefit bullet rows and heading separation. |
| 48px | Vertical footer subgroups. |
| 60px | Heading-to-action separation and carousel introduction space. |
| 64px | Footer side inset and separation between its major zones. |
| 80px | Footer top inset and selected card left inset. |
| 140px | Major content chapter vertical padding. |
| 180px | Closing invitation top and bottom padding. |
| 190px | Cream editorial band vertical padding. |

### Containers and grids

- **main container**: max width 1350px · side padding 15px. Centered desktop frame; at 1440px, content text begins about 60px from the viewport edges.
- **proof container**: max width 1160px. Narrower frame for impact metrics and paired map narrative.
- **support column**: max width 470px. Benefit-panel introduction width, leaving room for two columns of supporting details.
- **editorial grid**: max width 1310px · 3 columns · gap 30px. Three equal image-led articles, without individual card fills.
- **benefit grid**: 2 columns · gap 18px · side padding 10px. Alternating documentary image and colored text panel; swap sides on the next row.
- **testimonial pair**: 2 columns · gap 32px. Two pastel quote-and-photo panels across the main container.
- **people grid** (only for people directories): max width 1394px · 2 columns · gap 34px. Wide horizontal portrait-and-biography cards, rather than a wall of isolated headshots.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 110px |
|  | scenic stage | 18px |
|  | benefit panels | 30px |
|  | testimonial panels | 15px |
|  | editorial images | 26px |
|  | closing band top corners | 45px |
|  | email field | 33px |
| technical solution pages | proof cards | 16px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Primary reading surface.

**CSS:** `background: #ffffff; color: #353535`

**Observed:** Large unboxed white regions separate the scenic and colored chapters.

**Transfer:** Let composition and photography provide richness rather than adding texture to every surface.

#### Forest field · level 0

**Use:** Footer and major dark benefit panels.

**CSS:** `background: #07503f; color: #ffffff`

**Observed:** Flat saturated green with pale sage supporting details; no grain or luminous effects.

**Transfer:** Use as a stable anchor, not as a dark-mode treatment for the whole page.

#### Cream editorial field · level 0

**Use:** Long editorial and capability bands.

**CSS:** `background: #f1efdf; color: #353535`

**Observed:** A warm, uninterrupted backing for images and light serif text.

**Transfer:** Reserve for a change in narrative pace.

#### Sky invitation · level 0

**Use:** Broad closing invitation.

**CSS:** `background: #b2cee7; border-radius: 45px 45px 0px 0px; padding: 180px 0px; color: #353535`

**Observed:** A low-density band meets the forest footer directly.

**Transfer:** Use one strong proposition and one action.

#### Pastel testimonial · level 1

**Use:** Quote cards beside documentary media.

**CSS:** `background: #d7e6f5; border-radius: 15px; overflow: hidden; box-shadow: none`

**Observed:** The companion panel uses pale green; colored backing extends under both text and photograph.

**Transfer:** Alternate blue and green rather than introducing a new hue for each quote.

#### Mist chapter · level 0

**Use:** Process and culture chapters.

**CSS:** `background: #f8f8f8`

**Observed:** A cool near-white broad surface, not a visibly gray dashboard.

**Transfer:** Differentiate an extended explanatory chapter without adding heavy borders.

#### Technical card · level 1

**Only for:** technical solution pages

**Use:** Overlapping explanatory cards.

**CSS:** `background: #fbfbfb; border: 1px solid #d5d5d5; border-radius: 14.3px; padding: 32px 32px 0px 32px; overflow: hidden`

**Observed:** Tall 379px by 520px cards overlap horizontally, with short titles at top and diagrams toward the bottom.

**Transfer:** Use for a small family of linked technical capabilities, not for all feature lists.

#### Sky fade · level 0

**Only for:** technical solution pages

**Use:** A quantitative argument between white chapters.

**CSS:** `background: linear-gradient(#b2cee7 50.12%, #ffffff 100%); border-radius: 38px; padding: 168px 20px`

**Observed:** A blue upper field dissolves to white rather than forming a multicolor mesh.

**Transfer:** Pair with a concise split-layout argument.

#### Black comparison field · level 0

**Only for:** enterprise comparison sections

**Use:** High-contrast growth and scale chapter.

**CSS:** `background: #000000; color: #ffffff; padding: 140px 0px 200px 0px; overflow: hidden`

**Observed:** An isolated dramatic chapter with a partial planet at the lower left and ruled comparison rows at right.

**Transfer:** Use once for consequential before-and-after proof.

## Components

### Announcement strip

**Use:** Persistent short announcement above navigation.

**CSS:** `background: #e8fe85; color: #07503f; padding: 4px 16px; position: fixed; top: 0px; width: 100%; z-index: 1000; display: flex; justify-content: center; align-items: center`

**Text style:** `announcement` — Reckless 500 · 14px/1.3

**Observed:** A 26px high single line with a slightly stronger message and an underlined trailing link.

**Transfer:** Keep the announcement short enough to preserve the thin-strip proportion.

### Navigation

**Use:** Global navigation layered over the opening.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 8.5px 0px; color: #ffffff`

**Text style:** `navigation` — Inter 400 · 13.6px/1.1

**Observed:** Audience links at left, centered wordmark, organizational links and white contact capsule at right. It reads as a transparent layer over the initial scenic stage and as a solid forest band while scrolling; link padding is 20px 10px.

**States:** Declared: hover link color changes to electric lime; text-decoration none.

**Transfer:** Preserve the centered brand axis and separate audience navigation from utility links.

### Primary button

**Use:** Default conversion action on light fields.

**CSS:** `background: #07503f; color: #ffffff; border-radius: 110px; height: 49px; padding: 6px 6px 6px 30px; display: flex; justify-content: space-between; align-items: center; transition: 0.4s`

**Text style:** `action` — Inter 400 · 15px/1

**Observed:** Label at left, then a 35px white circular disc containing a simple right arrow. A compact green capsule without the arrow is used for audience choices; lime and sage are scoped alternatives in solution and partner invitations.

**States:** Declared: hover background-color #ffffff; text color changes to dark ink; text-decoration none.

### Secondary button

**Use:** Companion audience choice inside the scenic opening.

**CSS:** `background: #b2cee7; color: #353535; border-radius: 110px; height: 49px; padding: 6px 30px; display: flex; align-items: center; transition: 0.4s`

**Text style:** `action` — Inter 400 · 15px/1

**Observed:** A text-only capsule paired with the forest action at a 20px gap. Audience labels are uppercase.

**States:** Declared: hover background-color #ffffff; color #787878; text-decoration none.

### Benefit panel

**Use:** Audience-oriented value explanation beside photography.

**CSS:** `background: #07503f; color: #ffffff; border-radius: 30px; padding: 60px 40px 30px 80px`

**Text style:** `benefit-heading` — Reckless 300 · 45px/1

**Observed:** A serif lead and audience phrase, short introduction, then a two-by-two group of illustrated benefits. Each small icon sits above its explanation. The light alternative uses pale seed cream and dark text, beside the next photo.

**Transfer:** Use concrete outcomes instead of generic feature labels; keep short paragraphs within the panel.

### Impact tag

**Use:** Small category marker before numerical or geographic proof.

**CSS:** `background: #e8fe85; color: #212529; border-radius: 18.5px; padding: 7px 20px`

**Text style:** `tag` — FKGrotesk 300 · 15px/1 · uppercase

**Observed:** A narrow capsule above a much larger proof area; the geographic companion uses pale seed cream.

### Testimonial card

**Use:** Human and commercial proof.

**CSS:** `display: grid; grid-template-columns: 1fr 299px; background: #d7e6f5; border-radius: 15px; overflow: hidden`

**Text style:** `testimonial` — Inter 400 · 14px/1.47

**Observed:** At desktop the panel is 650px by 527px. Left: small customer mark and serif attribution, then a compact quote with a forest-green bold clause. Right: a 282px by 493px inset portrait or landscape image. The companion card is pale green; two 45px forest circular arrows sit centered below.

**Transfer:** Keep real attribution and image together rather than replacing the image with oversized quotation marks.

### Editorial card

**Use:** Three-up news and resource stories.

**CSS:** `position: relative; max-width: 407px; margin-bottom: 50px`

**Text style:** `article-title` — Reckless 300 · 25px/1.22

**Observed:** A 407px by 305px photograph with 26px corners, small white category pill over the upper-left corner, then muted date, serif title and brief sans excerpt. Text sits directly on the cream band, not inside a separate raised card.

**Transfer:** Use meaningful editorial images and shorten long titles with an ellipsis.

### Newsletter input

**Use:** Email entry on the forest footer.

**CSS:** `background: #07503f; border: 1px solid #ffffff; border-radius: 33px; height: 49px; width: 424px; padding: 12px 10px`

**Observed:** A single rounded outline field follows a small newsletter introduction; consent and explanatory copy sit below with a separate white rectangular submit control.

**Transfer:** Keep the form visually subordinate to the adjacent large line drawing.

### Metric card

**Only for:** technical solution pages

**Use:** Quantified outcomes over a scenic proof band.

**CSS:** `background: #fbfaf1; border-radius: 16px; padding: 20px 20px 24px 20px; display: flex; flex-direction: column; justify-content: space-between; height: 260px`

**Text style:** `metric` — Inter 400 · 52px/1 · tracking -0.0385em

**Observed:** Four 318px wide cards in a row with 16px gaps; small label at top left, thumbnail at top right and large value at bottom. Units use the much lighter metric-unit recipe.

**Transfer:** Use only substantiated metrics, keeping units visually lighter than the values.

### Comparison row

**Only for:** enterprise comparison sections

**Use:** Before-and-after numerical proof on black.

**CSS:** `border-top: 1px solid #7c7c7c; padding: 40px 0px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `comparison-value` — Inter 500 · 40px/1

**Observed:** A short semibold label at left, then two numeric columns joined by a fine arrow. Year pills above identify blue earlier and lime later states; suffixes use comparison-unit.

**Transfer:** Keep the same column alignment across every metric.

## Imagery and graphics

### Documentary landscape stage

**Use:** Opening and major photographic narrative bands.

**Observed:** Wide aerial views of working fields, crop lines and machinery under a real blue or overcast sky. Natural green, brown and straw remain visible rather than being fully tinted. A restrained dark overlay supports white type. The image fills almost the whole opening rather than sitting beside the headline in a small card.

**Transfer:** Show the new product's actual working environment at landscape scale: infrastructure, workshop, studio or field operations. If no video is available, use a strong still with depth, directional lines and visible human-scale activity.

**Build:** Place a cover-fitted photo or video in an overflow-hidden 18px-radius frame with 10px white surround. Add an absolute black alpha overlay, strengthening toward the bottom using rgba(0,0,0,0) and rgba(0,0,0,0.6); tune it so the scene remains legible and white copy is clear.

### People doing real work

**Use:** Alternating benefits, testimonials and culture stories.

**Observed:** Candid producers in fields, people beside machinery, collaborative groups and outdoor portraits. Warm daylight, ordinary work clothing, real textures and minimally processed color; photographs fill rounded rectangles rather than floating against cutout backgrounds.

**Transfer:** Photograph practitioners using the new product in context, keeping the surroundings and materials visible. Mix one close human view with one expansive environment view.

### Impact numerals and reach drawing

**Use:** Quantified proof chapter.

**Observed:** A row of oversized, very thin charcoal numerals is separated by faint vertical rules; a later two-column region pairs a serif statement and small location capsules with a gray world silhouette whose active regions are sage. The proof chapter is visually spacious, not a dense infographic.

**Transfer:** Include an original numerical proof composition and a map or relationship diagram. If reach is not geographic, replace country shapes with an equally restrained network or workflow drawing.

**Build:** Use four equal statistic columns in a 1160px frame, hairline separators and thin sans numerals around 80px as a working display target. Below, create a simplified SVG silhouette or node network: inactive shapes in light gray, active shapes in sage, white hairline boundaries. Give the graphic about half the row.

### Footer line map

**Use:** Persistent closing brand-world graphic.

**Observed:** A broad US outline with fine internal boundaries on forest green, several small pale points and one lime headquarters marker with concentric rings. A tiny outlined capsule labels the main point. The map occupies substantially more width than the newsletter form.

**Transfer:** Create a region map appropriate to the new business, or a line-based relationship drawing if geography is irrelevant. Retain pale boundaries, sparse points, a lime focal node and a small caption capsule.

**Build:** Draw SVG paths with no fill and a thin rgba(255,255,255,0.5) stroke. Place 9px white point cores within 22px outlined rings; make the focal core lime inside a 27px lime ring with rgba(232,254,133,0.1) fill. Set the composition on forest green and size it near 800px by 471px at desktop.

### Pastoral culture illustration

**Only for:** culture and community invitations

**Use:** Illustrated transition into the forest footer.

**Observed:** A low watercolor-like panorama of pale golden fields, converging crop rows, soft green hedges and muted plum shrubs. Above it, two loose green contour lines wander across a near-white field, with small rounded candid photos around the central invitation.

**Transfer:** Use a hand-textured landscape or material world relevant to the new product; retain low horizon bands, organic silhouettes and a paperlike softness.

**Build:** Layer SVG or hand-painted raster bands across the lower 218px: pale tan sky/soil, converging straw lines, irregular sage and forest shrub silhouettes, and sparse muted plum shapes. Add a low-opacity paper-grain mask; draw two loose 2px green Bezier contours across a separate 146px upper band. Keep the headline clear above.

### Shared-value lens

**Only for:** collaborative technical solution diagrams

**Use:** Explain two interdependent sides of an offering.

**Observed:** Two 280px circular photographs overlap inside a sky-blue capsule. The left image shows a dark-green crop texture, the right a translucent green leaf close-up; the shared lens is lime. Fine dotted horizontal guides connect small outline icons and serif labels on either side.

**Transfer:** Use two product-relevant material photographs for contribution and outcome, then name the shared benefit in their overlap.

**Build:** Create a roughly 539px by 317px blue capsule. Inset two 280px circles filled with green-toned cover images, overlapping at the center. Construct the intersection as an SVG lens filled with lime; overlay small white serif labels in each circle. Extend thin dotted guides to two short stacks of outline icons.

### Planet comparison art

**Only for:** enterprise scale proof

**Use:** Lower-left counterweight to a numerical comparison table.

**Observed:** A large partial Earth emerges from the left edge against black, with blue atmospheric rim and a shadowed lower hemisphere. It stays below a white serif statement while the right half holds the table.

**Transfer:** Use a single contextual, photoreal object that expresses scale. A well-masked photographic hemisphere or relevant material macro is preferable to an ornate low-quality 3D render.

**Build:** Place a circular planetary image partly outside the left edge, about 425px wide. Mask the lower portion into black with an alpha gradient; keep the highlight along the upper-left rim and leave the numerical table unobstructed.

### Icons

**Observed:** Main CTAs use a plain 16px right arrow on a 35px white disc; navigation chevrons are small white strokes with rounded caps. Benefit icons are small pale botanical or financial illustrations, while technical diagrams use fine green outlines with sage fills. Footer social marks are 25px filled sage icons.

**Transfer:** Use thin, simple, domain-relevant pictograms in green and sage; reserve filled marks for social destinations and simple arrows for actions.

## Section recipes

How recurring sections are built.

### First screen: Scenic promise opening

**Observed:** A 26px lime Announcement strip sits above a near-full-screen landscape stage inset 10px from white edges, with 18px corners. Navigation overlays its upper region around a centered wordmark. Behind the type, a cover-fitted aerial scene retains its sky, horizon, field rows and machinery, with darker tones below. The white 65px headline is centered across roughly two thirds of the width, split across two lines, with one phrase subtly stronger. A paired blue and forest action group follows about 51px below the headline; a small scroll cue anchors the bottom. Within the first 900px the complete headline, both actions, landscape and scroll cue are visible; there is no separate support paragraph in this default opening. The next benefit chapter falls below the fold.

**Transfer:** Create the same immersive first screen with an authentic wide still when video is unavailable. Let the new headline determine its line breaks while keeping its compact centered block. Audience-specific pages use a shorter 740px scenic stage and left-aligned headline with 22px three-line support; technical pages use a 582px full-width stage with a 42px centered heading. Culture pages open on forest green with a centered 65px statement and a horizontal candid-photo ribbon.

**Avoid:** Do not turn the first screen into a white split-layout SaaS hero with a small floating UI card, or let a paragraph crowd the default centered promise.

**Text style:** `display` — Reckless 100 · 65px/1.06

### Alternating benefits

**Observed:** Benefit grid places a rounded documentary image beside Benefit panel, then reverses the pair on the next row. Forest and pale seed cream alternate the text panels. A 45px serif title and a 470px introduction lead into four small illustrated benefits with 15px explanations.

**Transfer:** Separate two audiences, use cases or outcome families while retaining image/text alternation.

**Text style:** `benefit-heading` — Reckless 300 · 45px/1

### Proof and reach

**Observed:** Proof white field with 140px vertical padding, a small Impact tag, thin oversized numeric proof and a later two-column narrative/map composition inside the proof container. Location capsules wrap beneath the serif statement.

**Transfer:** Show credible scale and explain where or how the product operates using Impact numerals and reach drawing.

**Text style:** `reach-heading` — Reckless 300 · 40px/1.22

### Heading and support pair

**Observed:** Centered 55px serif section lead, followed by a light 17px support line about 25px below; the content grid begins after a substantially larger pause, commonly 60px.

**Transfer:** Use a short noun phrase for the heading and one explanatory line rather than duplicating the headline.

**Text style:** `heading-lg` — Reckless 300 · 55px/1

### Human proof carousel

**Observed:** Heading and support pair leads into Testimonial card pair. Blue and pale green cards contain attribution, quote and tall inset photograph, followed by centered forest circular previous/next controls.

**Transfer:** Use the same visual weight for human testimony as for quantitative proof.

**Text style:** `testimonial` — Inter 400 · 14px/1.47

### Editorial field

**Observed:** Cream editorial field with 190px vertical padding, Heading and support pair, three Editorial cards at 30px gaps and a centered white view-more capsule.

**Transfer:** Use for resources, research or recent work; keep text exposed on the band.

**Text style:** `article-title` — Reckless 300 · 25px/1.22

### Closing invitation and inhabited footer

**Observed:** Sky invitation contains a centered 53px line and a Primary button about 60px beneath. It joins the full forest footer. The upper footer pairs a narrow newsletter form with Footer line map. Below, a three-line belief occupies the largest text column, then compact address, contact and social columns and a small brand symbol; fine-print links form the bottom edge.

**Transfer:** End with one invitation, then a useful place to subscribe or make contact. Keep the line drawing and belief statement as design devices even for businesses without offices.

**Text style:** `closing-heading` — Reckless 300 · 53px/1

### Numbered process chapters

**Only for:** partner and enterprise explanation pages

**Observed:** Partner explanations alternate text and small green/sage diagrams across a mist chapter; small numbered discs lead 45px serif titles. Enterprise explanations use three horizontal rows over one darkened landscape, each with number, 50px serif title, short paragraph and white top hairline.

**Transfer:** Choose alternating illustrated steps for a relationship-led story, or full-width ruled rows for a concise enterprise process.

### Technical proof landscape

**Only for:** technical solution pages

**Observed:** A 42px centered serif heading and short support sit over a broad aerial photograph; a compact resource action precedes four Metric cards near the lower edge. Adjacent chapters use Technical card stacks and the Shared-value lens rather than decorative stock illustrations.

**Transfer:** Link the technical argument to verified outcomes and a clear next step.

**Text style:** `solution-heading` — Reckless 300 · 42px/1

### People and culture chapters

**Only for:** people and culture pages

**Observed:** A centered 50px statement introduces a two-column People grid. Each horizontal card combines a tall candid portrait, serif name, compact biography, small role tags and a social icon. Later, a full-width aerial quote band gives way to a split careers photo/text block and Pastoral culture illustration invitation.

**Transfer:** Use original people, roles and a real point of view; let the culture closing be softer and more illustrative than the default sky invitation.

**Text style:** `culture-heading` — Reckless 300 · 50px/1.22

### Comparison at scale

**Only for:** enterprise comparison sections

**Observed:** Black comparison field pairs a large multi-line serif statement at left with aligned Comparison rows at right. Blue and lime date pills distinguish two states; Planet comparison art enters below the text.

**Transfer:** Use a limited set of matched metrics with a defensible comparison period.

**Text style:** `comparison-value` — Inter 500 · 40px/1

## Page flow

**Storyline:** Immersive promise → audience outcomes → tangible method → quantified and human proof → invitation → inhabited footer.

### Broad marketing entry for multiple audiences

1. **Promise** — Centered scenic headline and two audience capsules.
2. **Audience outcomes** — Alternating documentary images and forest/cream benefit panels.
3. **Quantified proof** — Thin numeric impact row followed by reach map.
4. **Human proof** — Pastel testimonial pair.
5. **Editorial credibility** — Cream three-up news band.
6. **Closing call** — Sky invitation, then forest newsletter/map/belief footer.

**Transfer:** Use as the default narrative vocabulary, adapting the order and number of proof chapters to the new offering.

### Explain the organization and the people behind it

1. **Purpose** — Centered forest statement with candid horizontal image ribbon.
2. **Mission** — Cream split narrative.
3. **Human credibility** — Centered collective statement and horizontal portrait cards.
4. **Point of view** — Scenic full-width quote.
5. **Participation** — Careers split and illustrated community invitation.
6. **Closing contact** — Shared forest newsletter, map and belief footer.

**Transfer:** Use people and practice to make the purpose credible, not a feature inventory.

### Recruit an ecosystem or distribution partner

1. **Audience promise** — Left-aligned scenic hero with two different actions.
2. **Value** — Benefit carousel with photograph.
3. **Method** — Large centered promise followed by alternating numbered explanations.
4. **Social proof** — Wide rows of partner marks with a testimonial action.
5. **Partner gains** — Three compact illustrated outcomes.
6. **Closing call** — Dark crop-photo invitation and shared forest footer.

**Transfer:** Present the commercial benefit, then make participation concrete and easy to understand.

### Explain a specialized technical solution

1. **Focused promise** — Compact 42px scenic opening.
2. **Context and challenge** — Sage-to-white explainer and paired numbered challenge cards.
3. **Argument** — Sky fade fact band and cream statement with small floating photographs.
4. **Method** — Short technical explanation beside overlapping cards.
5. **Measured proof** — Landscape-backed row of cream metric cards.
6. **Collaboration** — Centered milestones explanation and shared-value lens.
7. **Closing call** — Scenic transformation invitation and shared forest footer.

**Transfer:** Keep terminology precise but introduce it through outcomes, images and short, clearly separated arguments.

### Sell an enterprise outcome with operational and scale proof

1. **Promise** — Left-aligned scenic headline and single action.
2. **Opportunity** — Editorial split statement and explanation.
3. **Capabilities** — Cream two-by-two mixed photo and colored panel grid.
4. **Method** — Numbered ruled rows over a photograph.
5. **Scale proof** — Black chapter with planet and before-and-after rows.
6. **Solutions and credibility** — Unequal photo cards, partner marks and leader-story media.
7. **Closing call** — Sky invitation and shared forest footer.

**Transfer:** Combine strategic outcomes with operational specifics and a small number of measurable comparisons.

## Writing

Optimistic, grounded and collaborative. The language connects a broad better-future promise to practical, measurable value for the people doing the work, with technical specificity where the audience needs it.

**Do not copy:** Do not reuse Arva's name, marks, product names, photographs, customer logos, testimonials, proprietary program terminology or claimed metrics. Replace all claims, dates and evidence of performance with the new product's substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for audience benefits, we for shared purpose and operational responsibility, and the product name for specific capabilities. Partnership language is more common than commands.
- **Rhythm:** Short editorial headings of roughly 2–9 words alternate with occasional longer mission statements. Most support blocks are one or two direct sentences; technical sections may use selective bold clauses rather than extra paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A concrete system or audience linked to an aspirational shared outcome. | 6–12 words | “Regenerative supply chains for a better world”<br>“Empower your farmers for a resilient tomorrow” |
| Section heading | Plain descriptive noun phrase or a brief outcome statement. | 2–7 words | “Valued partners”<br>“Careers for good” |
| Support | Explain what the reader gains through participation; connect practical outcomes to the larger purpose. | One or two sentences | “Insights from other leaders regenerating their operations”<br>“Empower farmers in their sustainable journey while unlocking new revenue streams for your business” |
| Technical promise | Use precise terms in a clipped, parallel sequence. | 3 short clauses | “Science-Based. Data-Driven. FLAG-Aligned.” |
| Action | Direct verb plus relationship or next step; audience selectors can use first person. | 2–4 words | “PARTNER WITH ARVA”<br>“I’M A FARMER”<br>“SEE OPPORTUNITIES” |
| Closing belief | A short collective conviction with a tactile metaphor. | 8–12 words | “We believe in change from the ground up.” |

**Words and phrasing to use:** together; connect; measurable; resilient; shared value; trusted; real-world; built for; your business; outcomes

**Avoid:** disrupt everything; 10x magic; crush the competition; frictionless revolution; vague planet-saving promises

**Rules:**

- Lead with an audience outcome; follow with the operational mechanism that makes it believable.
- Use technical vocabulary only when it helps the intended audience evaluate the offering.
- Attach numbers to units and a meaningful timeframe; distinguish measured results from ambitions.
- Let the emotional headline and practical paragraph do different jobs.
- Keep CTAs calm and literal, with relationship verbs rather than urgency or scarcity.

## Do's and Don'ts

### Do

- Keep the scenic stage inside a 10px white surround and 18px rounded frame.
- Set the principal scenic headline at 65px/1.06 and leave the photographic world visible around it.
- Use 55px/1 light serif section leads with 17px/1.24 support.
- Pair 49px capsules with 35px circular arrow endpoints for conversion actions.
- Use 30px benefit-panel corners and 18px gaps between media and text panels.
- Keep cream editorial stories in a three-column grid with 30px gaps and no raised outer card.
- Use pale blue and pale green testimonial backings with 15px corners.
- Give the forest footer its 64px side insets and a distinct three-line serif belief.

### Don't

- Do not replace the light serif hierarchy with bold geometric sans headings.
- Do not turn electric lime into the main page canvas; its strongest broad use is the thin 26px announcement strip.
- Do not add shadows to every panel; the main cards are flat color fields.
- Do not use one radius everywhere: buttons are 110px capsules, benefit panels 30px and testimonial panels 15px.
- Do not recolor every photograph forest green; retain natural skies, soil and skin tones.
- Do not render all metrics in uniformly bold type; units are deliberately lighter than values.
- Do not replace the large footer drawing with a generic dense sitemap.
- Do not default every page to the black comparison look; it belongs to a scoped scale-proof chapter.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare 0.4s transitions; the newsletter input declares box-shadow 0.2s.
- Scrolling logo rows declare 65s linear infinite motion.
- Location-marker rings declare a 3s infinite marker-ping animation with cubic-bezier(0,0,0.2,1).
- Headings use line-wise and upward reveal constructions; scenic openings contain video.

**Transfer:**

- Keep slow-moving logo rows and sparse pulsing map points as quiet proof devices, subordinate to the landscape and copy.
- Use real-world video for atmosphere rather than an animated software dashboard.

**Unknown:**

- Exact scroll choreography, video playback parameters and headline reveal timing are not established. Focus-visible treatments are not established.

### Responsive

**Observed:**

- Desktop layout uses a 1350px centered main container and two- or three-column content groups.
- The footer belief has the explicit fluid rule clamp(24px, 3vw, 48px).
- Declared width breakpoints include 576px, 768px, 992px and 1200px, among many element-specific thresholds.

**Transfer:**

- On narrow layouts, preserve the scenic photo as the opening backdrop and keep the headline compact; do not reduce it to an inline thumbnail.
- Stack alternating benefit pairs and testimonial cards in reading order. Keep photographs attached to their corresponding text.
- Place the large footer line drawing below the form, then stack contact groups while retaining the three-line belief.

**Unknown:**

- Mobile menu behavior, exact mobile type sizes, image crops and stacking breakpoints are not established; narrow-screen directions are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
