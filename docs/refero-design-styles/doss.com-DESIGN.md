# DOSS — software with physical roots

## Overview

A light, matter-of-fact software identity grounded in the tangible world of products, people and work. Black grotesk headlines, cool white panels and small electric-blue actions sit alongside warm photography and sandy halftone textures. Interface demonstrations and fine technical diagrams provide substance without making the marketing page feel like a dashboard. Dark photographic interludes lend weight to an otherwise spacious, approachable presentation.

### Essentials

- Headlines sound conversational but look like display type: Switzer at 52px/58px, weight 400, with -1.3px tracking; section leads use 44px/48px at the same weight and tracking.
- The default opening puts the physical world between the promise and the explanation: a centered two-line headline above a graduated ribbon of portrait photographs, then an 18px support line and paired 53px pill actions.
- Electric blue acts like a control signal rather than a page theme: #0118df fills primary pills and appears in fine diagram details; white and #f6f8f9 occupy most of the page, with #efece3 proof bands and near-black photographic calls.
- Soft geometry separates controls from content: actions have 9999px radii, ordinary tiles 8px, and white proof cards 16px; most marketing cards have no outline or shadow.
- Proof gets its own physical material: white cards with 44px numbers sit on a full-width sandy photographic halftone band. Carry this textured proof device into every new landing page, using a dot-screened work image or an abstract tonal field if no suitable photograph exists.
- The page returns to real work before it ends: a dark, low-contrast, motion-blurred photographic call with white 44px type and a blue pill precedes the final information blocks or footer. Use relevant workplace imagery, or a blurred close-up of tools or materials, rather than a generic gradient.
- Technical ideas are drawn as small diagrams, not decorative mascots: pale panels, fine black or blue strokes, dotted connectors and white inset interface windows; use a simple original process diagram when a live interface is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0118df` | `--color-signal` | action, link, accent | Primary actions, secondary action text, diagram strokes and the narrow announcement strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Working black | `#161616` | `--color-ink` | text, background | Headlines, body text, dark bands and footer. |
| Warm gray text | `#625e55` | `--color-warm-muted` | text | Secondary copy, FAQ answers, editorial labels and muted navigation. |
| Fine gray edge | `#d6d6d6` | `--color-edge` | border | FAQ separators, circular navigation controls and inset demo-window outlines. |
| Warm light | `#e2ddd1` | `--color-warm-light` | text, surface | Footer links and tagline; backing beneath editorial thumbnail artwork. |
| Halftone sand | `#efece3` | `--color-sand` | background | Warm backing for textured proof bands and demonstration art. |
| Cool panel | `#f6f8f9` | `--color-cool-panel` | background, surface | Alternating feature bands, capability tiles and diagram backing. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, white proof cards and text on dark backgrounds. |

## Typography

- **Switzer** — All marketing headings, paragraphs, actions and labels. Contemporary compact grotesk; regular display weights and medium small text, with open but tightly fitted forms. If unavailable, use **Inter**. Use 400 and 500; retain tight tracking and check headline wrapping. Font stack: "Switzer", "Inter", PPNeueMontreal, sans-serif.
- **IBM Plex Mono** (only for company principles and institutional proof labels) — Numbered principle indexes and the spaced uppercase backer label. Small, technical monospace; semibold rather than a code-editor texture. Font stack: "IBM Plex Mono", MDIO-Medium, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Switzer | 400 | 52px | 58px | -0.0254em | Main promise in both white photographic and dark textured openings. |
| heading | Switzer | 400 | 44px | 1.091 | -0.03em | Section leads and large proof values; numbers remain in the same grotesk as headings. |
| quote-question | Switzer | 400 | 32px | 1.125 | -0.018em | Customer quotation, FAQ questions and smaller editorial section leads. |
| card-heading | Switzer | 500 | 21.6px | 1.167 | -0.0167em | Capability card titles, link-list labels and proof captions. |
| body | Switzer | 500 | 18px | 1.3 | -0.014em | Explanatory paragraphs beside demonstrations and extended hero support. |
| body-compact | Switzer | 500 | 18px | 1.222 | -0.014em | Short centered introductions, FAQ answers and compact supporting descriptions. |
| action-body | Switzer | 500 | 16px | 1.25 | -0.0156em | Large button text, inline links, capability descriptions and footer tagline. |
| label | Switzer | 500 | 14px | 1.43 | normal | Navigation, compact header actions, diagram-tile captions and footer column titles. |
| footer-link | Switzer | 400 | 14px | 1.43 | normal | Footer navigation links. |
| caption | Switzer | 500 | 12px | 1.333 | normal | Editorial categories and small supporting labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company principles | principle-index | IBM Plex Mono | 600 | 14px | 1.43 | 0.04em, uppercase | Blue two-digit index above each principle. |
| institutional backing sections | institutional-eyebrow | IBM Plex Mono | 600 | 14px | 1.43 | 0.286em, uppercase | Widely spaced centered label over a monochrome partner strip. |

**Notes:**

- Display and section headings stay at weight 400; emphasis comes from scale, wrapping and contrast rather than bold words.
- The 52px and 44px recipes share -1.3px tracking. Smaller 32px text uses -0.018em, while 18px and 16px text retain -0.3px.
- Body text is weight 500 even though it reads lightly. Keep prose blocks comparatively narrow: 470px in the default opening and 500px beside wide media.
- Use the ordinary heading recipe for stats, including arrow comparisons and unit suffixes. Do not introduce a separate numeric display family.

## Layout

**Density:** Airy section rhythm with compact internal text groups; demonstrations and photographs carry more area than their explanations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title-to-description gap inside capability cards and icon-to-label gaps. |
| 16px | Paired actions, answer inset and small label padding. |
| 18px | Opening support and action offsets. |
| 21.6px | Link-list inner padding and gaps; preserve this distinct component measurement. |
| 24px | Container gutter, card padding, grid gutters and headline-to-body gaps. |
| 32px | Internal card separation and integration heading-to-action gap. |
| 40px | Proof-card grid gutter and testimonial text inset. |
| 48px | Heading-to-grid separation, split-section gutter and demonstration panel padding. |
| 72px | Vertical padding of tabbed product showcases; space reserved below testimonial slides for controls. |
| 96px | Default section top and bottom padding and footer top inset. |

### Containers and grids

- **content**: max width 1200px · side padding 24px. Centered desktop content. At 1440px, most content occupies the middle 1200px; full-bleed backgrounds extend beyond it.
- **navigation**: max width 1264px · 3 columns · gap 24px · side padding 24px. Logo left, centered navigation and right-aligned sign-in plus compact action.
- **opening**: max width 963px · side padding 24px. Centered promise and media ribbon; headline max-width 664px and support max-width 470px.
- **split-feature**: max width 1200px · 2 columns · gap 48px. A 500px copy area beside 652px media, vertically centered. Alternate media side across adjacent chapters.
- **capability-grid**: max width 1200px · 4 columns · gap 24px. Four equal 282px cells across, mixing text capabilities and full-bleed photographs.
- **proof-grid**: max width 1200px · 3 columns · gap 40px. Three equal white proof cards; company overview variant has four columns.
- **link-grid**: max width 1200px · 2 columns · gap 24px. Wide 588px destination rows with northeast arrows.
- **editorial-grid**: max width 1200px · 3 columns · gap 24px. Three editorial links, each with a 384px by 216px image and text below.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | tiles-and-media | 8px |
|  | proof-cards | 16px |
|  | small-ui-tiles | 4px |
|  | round-controls | 50% |
| inset product demonstrations | demo-window | 7px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| media-lift | `0px 4px 8px 0px rgba(0, 0, 0, 0.12)` | Video stills, editorial thumbnails and inset demonstration windows, not ordinary capability cards. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and split-section background.

**CSS:** `background: #ffffff; color: #161616`

#### Cool band · level 0

**Use:** Alternating feature, proof-story and editorial sections.

**CSS:** `background: #f6f8f9; padding: 96px 24px`

**Observed:** Full-width flat band with no framing border.

**Transfer:** Use to group a substantial content chapter, not every paragraph.

#### Flat tile · level 1

**Use:** Capabilities, related products and destination rows.

**CSS:** `background: #f6f8f9; border-radius: 8px; box-shadow: none`

**Observed:** Cards rely on tonal separation rather than outlines.

**Transfer:** Keep icons and type inside the pale field; let neighboring photography provide color.

#### Halftone proof band · level 0

**Use:** A tactile field behind white proof cards.

**CSS:** `background-color: #efece3; background-size: cover; background-position: 50% 50%; padding: 96px 24px`

**Observed:** Cream photographic dot texture with irregular white light areas; cards remain crisp over it.

**Transfer:** Apply the halftone material recipe to an original work image or abstract tonal field.

#### Dark photographic call · level 0

**Use:** High-contrast conversion interlude.

**CSS:** `background-color: #161616; color: #ffffff; position: relative; padding: 96px 24px; overflow: hidden`

**Observed:** A dim monochrome work photograph fills the band; all copy is centered above it.

**Transfer:** Use the blurred-work imagery treatment and keep enough dark area for white text.

#### Footer ground · level 0

**Use:** Final site navigation area.

**CSS:** `background: #161616; color: #e2ddd1`

**Observed:** A flat dark region without the photographic material of the preceding call.

**Transfer:** Maintain a distinct quiet base after the more atmospheric conversion band.

#### Inset demo window · level 2

**Only for:** product demonstrations

**Use:** UI video or still over a warm textured panel.

**CSS:** `background: #ffffff; border: 1px solid #d6d6d6; border-radius: 7px; box-shadow: 0px 4px 8px 0px rgba(0, 0, 0, 0.12); object-fit: contain`

**Observed:** A 556px by 418px interface window sits inside a 652px by 514px panel with 48px padding and 8px outside corners.

**Transfer:** Show a coherent real task at a readable overall scale; use the marketing frame without importing tiny interface typography.

## Components

### Primary button

**Use:** Main conversion action in openings and calls.

**CSS:** `background: #0118df; color: #ffffff; border-radius: 9999px; height: 53px; padding: 0px 32px; display: inline-flex; align-items: center; position: relative; overflow: hidden`

**Text style:** `action-body` — Switzer 500 · 16px/1.25 · tracking -0.0156em

**Observed:** Text-only pill, sized to its label. Header and footer use a compact 44px version with 12px 24px padding and the label recipe. A dark overlay layer belongs beneath the text, not across the whole section.

**Transfer:** Choose a single direct action and repeat its label consistently.

### Secondary button

**Use:** Exploration beside the primary action or after a capability paragraph.

**CSS:** `background: transparent; color: #0118df; border: 1px solid #0118df; border-radius: 9999px; height: 53px; padding: 0px 32px; display: inline-flex; align-items: center`

**Text style:** `action-body` — Switzer 500 · 16px/1.25 · tracking -0.0156em

**Observed:** Visually outlined pill alongside the solid action; dark openings use white text and a light outline. Some inline exploration actions omit the enclosing outline.

### Navigation item

**Use:** Compact category navigation in the fixed header.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 12px; border-radius: 4px; color: #161616`

**Text style:** `label` — Switzer 500 · 14px/1.43

**Observed:** Short label followed by a tiny down chevron for menus; logo and conversion controls sit outside the central link cluster. A 28px blue announcement strip can sit above the 84px white bar for a launch.

**States:** Declared: hover background #f6f8f9 and color #161616; focus-visible not specified.

### Capability card

**Use:** Outcome-led capability in a mixed photo-and-text grid.

**CSS:** `background: #f6f8f9; border-radius: 8px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px; position: relative`

**Text style:** `card-heading` — Switzer 500 · 21.6px/1.167 · tracking -0.0167em

**Observed:** Small outline icon at upper left and northeast arrow at upper right; the title and action-body description are grouped near the bottom with an 8px gap. Text cards share their proportions with photographic cells.

**States:** Declared: hover background #eceff1; focus-visible not specified.

### Proof card

**Use:** Quantified results on the Halftone proof band.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 20px 24px 24px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px`

**Text style:** `heading` — Switzer 400 · 44px/1.091 · tracking -0.03em

**Observed:** Large numeric line, compact card-heading caption directly below with 4px separation, then a small customer mark when the number is attributed. Operational-scale variants use just a number and unit caption.

**Transfer:** Use a verified before-and-after or scale value with its unit; retain the card's plain hierarchy.

### Destination row

**Use:** Route readers by need, audience or adjacent product.

**CSS:** `background: #f6f8f9; border-radius: 8px; padding: 21.6px; display: flex; align-items: center; gap: 21.6px; color: #161616`

**Text style:** `card-heading` — Switzer 500 · 21.6px/1.167 · tracking -0.0167em

**Observed:** A long label occupies the left; a 24px northeast arrow is pushed to the far right. Rows form a two-column grid.

**States:** Declared: hover background #eceff1; focus-visible not specified.

### Diagram tile

**Use:** Compact related-product navigation.

**CSS:** `background: #f6f8f9; border-radius: 8px; display: flex; flex-direction: column; padding-top: 16px`

**Text style:** `label` — Switzer 500 · 14px/1.43

**Observed:** Fine line illustration occupies the upper compartment; its bottom edge is a 1px rule in black at 50% opacity. The centered label occupies a 52px lower row. Six 180px tiles fit across the main container; five wider tiles are a related-platform variant.

**States:** Declared: hover background #eceff1; focus-visible not specified.

**Transfer:** Draw each concept with the same fine-line vocabulary and keep labels short.

### FAQ row

**Use:** Direct objection handling near the end of product pages.

**CSS:** `border-top: 1px solid #d6d6d6; padding: 24px 0px; color: #161616`

**Text style:** `quote-question` — Switzer 400 · 32px/1.125 · tracking -0.018em

**Observed:** Full-width question button with plus or minus at the right. The first answer is expanded, set in body-compact warm gray, inset 16px from the question and limited to 900px. Closed rows are about 85px tall.

### Video play control

**Use:** Centered over a photographic product video still.

**CSS:** `background: rgba(22, 22, 22, 0.8); color: #ffffff; width: 64px; height: 64px; border-radius: 50%; display: flex; align-items: center; justify-content: center; position: absolute; transform: translate(-50%, -50%)`

**Observed:** White 24px triangular play icon on a dark translucent circle.

**States:** Declared: hover background #161616 and transform translate(-50%, -50%) scale(1.05); focus-visible outline 2px solid #0118df with 3px offset.

### Editorial thumbnail

**Use:** Resource and news links on Cool band.

**CSS:** `background: #e2ddd1; border-radius: 8px; box-shadow: 0px 4px 8px 0px rgba(0, 0, 0, 0.12); overflow: hidden; display: flex; align-items: center; justify-content: center; aspect-ratio: 16 / 9`

**Text style:** `body-compact` — Switzer 500 · 18px/1.222 · tracking -0.014em

**Observed:** Image first, small caption category underneath, then a sentence-case title. The text is outside the raised image, not inside a larger raised card.

### Footer link

**Use:** Final navigation grouped in four columns.

**CSS:** `color: #e2ddd1; text-decoration: none; transition: color .18s cubic-bezier(.22, 1, .36, 1)`

**Text style:** `footer-link` — Switzer 400 · 14px/1.43

**Observed:** White label heading over a vertical list of warm-light links; list gap 10px and heading-to-list gap 16px.

**States:** Declared: hover color #ffffff; focus-visible not specified.

## Imagery and graphics

### Graduated photo ribbon

**Use:** Signature visual in the default opening.

**Observed:** A horizontal run of portrait lifestyle and work photographs grows toward the center and shrinks toward the edges. Natural light, tactile packaging, hands and people at work provide varied warm color; outer images fade gently. Images remain upright with small 4px corners, no tilted collage or heavy shadow. The largest portraits are roughly 266px by 333px and the smaller ones about 132px by 165px.

**Transfer:** Photograph the new product in use, the people it serves and its tangible context. If the product is entirely digital, use people, desks, tools and material details rather than six repeated UI windows.

**Build:** Use a centered flex strip of six portrait images with object-fit: cover and about 12px gaps. Grade heights from roughly 132px at the edges through 200px to about 300px at the center; keep a 4:5 ratio, align vertical centers and soften the edge images with opacity or an edge mask. Use a pale cool backing beneath each image.

### Sandy halftone material

**Use:** Proof bands and framed product-demonstration backing.

**Observed:** A warm cream field is textured with fine regular dots. A low-contrast workplace image is legible only as large pale structural shapes and white openings; demonstration panels also use sweeping light diagonal bands. It supports the content rather than competing with it.

**Transfer:** Preserve the sandy paper tone and screened physical texture regardless of the new subject. A low-contrast abstract light field is the minimum equivalent.

**Build:** Begin with #efece3. Place a desaturated workplace photo or broad diagonal white light shapes at low opacity. Overlay an SVG dot-screen pattern with a roughly 4px pitch and small white circles whose opacity follows a softened luminance mask. Vary the mask across the field so some zones resolve almost to white. Use this texture behind, never on top of, the crisp white proof cards.

### Blurred work call

**Use:** Signature dark conversion band.

**Observed:** Monochrome shelving, stock and workspaces stretch across the full width; lateral or radial motion blur is strongest near the edges. A very dark overlay leaves the photograph barely luminous behind centered white text. The band is typically 317px to 455px tall.

**Transfer:** Use an original image tied to the product's working world. If no scene exists, use an authentic close-up of relevant materials or tools and create the same dark blurred depth.

**Build:** Use a full-bleed cover photograph, grayscale it, then blend it over #161616 at about 0.2 opacity. Build edge motion by layering a softly blurred enlarged duplicate beneath a sharper central image with a feathered mask; keep the text on a separate sharp layer. Match the soft directional blur rather than a colorful glow.

### Fine-line system diagrams

**Use:** Technical explanation beside feature copy and inside Diagram tile.

**Observed:** Thin charcoal and electric-blue strokes depict linked records, stacked panels, grids and simple object symbols. Pale gray-white surfaces, lightly raised inset cards and sparse dotted connectors make the diagram feel like an intelligible machine.

**Transfer:** Create a compact diagram of the new product's actual system. At minimum show one primary panel, two or three simple internal content regions and a connected foundation strip.

**Build:** Draw SVG rectangles, circles and connectors at 1px to 1.5px stroke. Use #161616 with reduced opacity for structure and #0118df for a few active details. Set the main panel on #f6f8f9; place white inset regions above it and a narrow foundation panel below, joined by a short blue dotted line. Use restrained 0px 4px 8px rgba(0,0,0,0.12) elevation.

### Integration fan

**Use:** Broad ecosystem proof beside a short heading and one action.

**Observed:** A 752px by 608px illustration fans fine dashed blue paths from one point toward scattered white 112px by 64px partner tiles. It sits on the Cool band and occupies more space than the left text column.

**Transfer:** Map real connections or compatible tools. For a product without an ecosystem, use the same fan geometry to connect an input to distinct outputs rather than inventing partnerships.

**Build:** In an SVG viewBox of 752 by 608, place the convergence point near the left-middle and draw 10 to 13 thin blue paths to tiles distributed above, below and to the right. Use dashed or dotted strokes, some gently curved paths, 4px tile corners and ample blank space between endpoints.

### Customer proof photography

**Use:** Large quotation card and occasional standalone endorsement.

**Observed:** Warm outdoor or product-in-hand photographs occupy the left 40% of a white testimonial frame; the right side holds the quote and author. Product packs and hands are prominent, with natural scenery rather than a corporate portrait backdrop.

**Transfer:** Choose a customer-use image with genuine context and enough crop flexibility for a near-square left panel. Keep its natural color distinct from the monochrome conversion band.

### Team and founder photography

**Only for:** company and people pages

**Use:** Team opening, origin story and founder biographies.

**Observed:** Large documentary group photographs remain naturally colored, with 8px corners, while individual founders use small square headshots beside long biographical copy. The company opening places the group image to the right of white text on a dark brushed background.

**Transfer:** Use actual team moments, not stock office imagery; keep headshots consistent in crop and let the group image supply the larger human presence.

### Brushed dark material

**Only for:** platform-overview and company openings and deep technical showcases

**Use:** Dark alternative to the light photographic-ribbon opening.

**Observed:** Near-black charcoal texture resembles broad brushed or dragged material, with diagonal fine grain and a soft gray sweep near a lower corner. It fills the whole opening behind white text.

**Transfer:** Carry this variant only into a deep-platform or company narrative, not every ordinary landing page.

**Build:** Start with #161616. Overlay a monochrome brushed-material texture at low opacity, scale it to cover and place a broad translucent white diagonal sweep near the lower edge. A fallback can use many fine curved SVG strokes in white at 0.02 to 0.08 opacity over a blurred diagonal light mask; avoid a metallic high-gloss finish.

### Icons

**Observed:** Small outline glyphs are 20px with 1px rounded strokes for card concepts; navigation arrows are 24px with 1.5px rounded strokes. Main colors are #161616, white on dark and occasional #0118df in technical diagrams.

**Transfer:** Use a consistent fine-line icon family. Place a small concept symbol at the upper left of cards and a northeast arrow at upper right; reserve filled shapes for play and social marks.

## Section recipes

How recurring sections are built.

### First screen: Physical-world opening

**Observed:** The white canvas begins behind a fixed white navigation bar and a 28px blue announcement strip. A centered 52px display promise starts below the navigation with 148px section top padding, spans about two thirds of the visual center and wraps into two balanced lines within 664px. Below it, the Graduated photo ribbon forms the main object, occupying roughly a third of the first screen's height and most of its central width. A centered 470px-wide support line follows, then Primary button and Secondary button with a 16px gap. Layers are white ground, portrait-image ribbon, sharp black text and blue actions; there is no atmospheric background behind this default opening. Within 900px, the entire headline, image ribbon, support and actions are visible, plus the beginning of the muted customer-logo strip. The first explanatory chapter is below the fold.

**Transfer:** State the new product category and audience in plain language, then give its working world a rich photographic presence. Use the ribbon fallback of people, tools and material details when no product photography exists. Deep-platform pages instead open with centered white display type on Brushed dark material; specialized-product pages add a breadcrumb and an overlapping wide video below the actions. Industry pages use a left-aligned promise over a work photograph with a dark left fade. Company pages pair left copy with a large team image on the dark material.

**Avoid:** Do not replace this opening with a generic left-text/right-dashboard SaaS split, enlarge the headline into a billboard, or move the supporting copy above the image ribbon.

**Text style:** `display` — Switzer 400 · 52px/58px · tracking -0.0254em

### Centered chapter lead

**Observed:** A regular 44px heading is centered over a grid or proof area, followed by a concise 18px support line when needed. The support starts 24px below the heading; cards usually start 48px after the heading group. Sections use 96px vertical padding.

**Transfer:** Introduce one reader problem or capability group, not a label for every individual card.

**Text style:** `heading` — Switzer 400 · 44px/1.091 · tracking -0.03em

### Split demonstration chapter

**Observed:** A 1200px centered row pairs 500px copy with 652px media and a 48px gap. Heading and body are 24px apart and vertically centered against the object. Alternate White canvas and Cool band and reverse media side between successive chapters. Video stills use the media-lift shadow; detailed product demonstrations use Inset demo window on sandy patterned backing.

**Transfer:** Build each chapter around a specific task and its evidence. Use a simple Fine-line system diagram if real UI cannot yet communicate the task clearly.

**Text style:** `heading` — Switzer 400 · 44px/1.091 · tracking -0.03em

### Mixed capability matrix

**Observed:** A centered chapter lead sits over four columns of 282px by 256px cells with 24px gutters. Capability card and photographic cells share equal proportions. Six text cards are interspersed with two warm work photographs rather than forming an uninterrupted wall of text.

**Transfer:** Mix concise task-oriented capabilities with genuine context images, preserving equal cell geometry.

### Textured quantified proof

**Observed:** Halftone proof band supports a centered heading and three Proof cards with 40px gutters. Values use 44px type; captions use card-heading. A company-scale variant fits four cards and omits customer attribution marks.

**Transfer:** Translate real outcomes into short values with explicit units. Preserve the sand/white contrast even when the proof is qualitative.

**Text style:** `heading` — Switzer 400 · 44px/1.091 · tracking -0.03em

### Related concept shelf

**Observed:** A centered 44px heading sits 48px above a row of Diagram tile components. Six compact tiles fit within 1200px; the upper art is about 151px tall, with a lower caption separated by a hairline.

**Transfer:** Use as a compact map to related capabilities; avoid turning it into a larger marketing-card grid.

### Customer story frame

**Observed:** A white 1200px by 514px rounded frame sits on Cool band below a centered heading. A 480px photograph fills the left; the right uses a 32px quotation, author identity, a compact case-study action and two bottom metric compartments separated by hairlines. Two 48px circular arrows sit centered below the frame.

**Transfer:** Use an attributable quotation and a contextual customer image; metric compartments should support the story rather than introduce unrelated statistics.

**Text style:** `quote-question` — Switzer 400 · 32px/1.125 · tracking -0.018em

### Atmospheric closing call

**Observed:** Dark photographic call spans the viewport, generally 317px to 455px tall. Center a 44px white heading, optional short 18px support and Primary button. The heading stays concise enough for one or two lines. Product pages can continue into resources and FAQ after the call; a company page moves directly into the footer.

**Transfer:** Make the last invitation concrete and suitable to the audience. Preserve the monochrome physical-work field rather than replacing it with a plain blue box.

**Text style:** `heading` — Switzer 400 · 44px/1.091 · tracking -0.03em

### Editorial continuation and objections

**Observed:** Cool band carries a centered heading over three Editorial thumbnail links with 24px gutters and 48px heading-to-grid separation. A following white FAQ section uses full-width FAQ row components. Only the first answer is visible initially; other questions remain compact.

**Transfer:** Offer useful next reading and answer realistic buying questions without competing with the principal action.

### Structured footer

**Observed:** Footer ground contains a 1200px container with 96px top inset and 32px bottom inset. A wider brand column holds a small white mark, short 16px positioning statement and compact blue action; four link columns follow with 48px gutters. A 1px white-at-16% separator introduces the final legal row and right-aligned social controls. All page types share this restrained ending.

**Transfer:** Keep the ending useful and compact: brand promise and action on the left, grouped destinations on the right, utility information below.

### Tabbed suite showcase

**Only for:** platform-overview pages

**Observed:** A 44px left-aligned section heading leads a 280px tab rail beside an 872px by 491px demonstration. Selected tabs have a pale fill; a paired dark chapter uses a translucent white selection panel on Brushed dark material. The description is above the demonstration, with an exploration link below; section padding is 72px vertically.

**Transfer:** Contrast the daily product layer and its enabling system with adjacent light and dark chapters, keeping the same tab geometry.

**Text style:** `heading` — Switzer 400 · 44px/1.091 · tracking -0.03em

### Numbered principles

**Only for:** company and philosophy pages

**Observed:** A two-column grid of pale rectangular cards uses 48px padding. Blue mono two-digit indexes sit above medium-weight card titles and 18px explanations. This is a plainer, squarer construction than the rounded capability tiles.

**Transfer:** Present distinct operating beliefs with one practical implication each; retain the spare indexes rather than adding pictograms.

## Page flow

**Storyline:** Category promise → tangible context → demonstrated capabilities → quantified and customer proof → routes to a relevant next step → atmospheric invitation → useful reading or objections → structured footer.

### Broad product marketing landing page

1. **Promise** — Centered category statement, graduated portrait ribbon, support and paired actions.
2. **Social proof** — Muted customer-mark strip.
3. **Product demonstration** — Video-led introduction followed by a focused feature spotlight.
4. **Capability chapters** — Mixed text/photo matrix, textured proof band, related concept shelf and a system diagram.
5. **Ecosystem and customer proof** — Integration fan and large photographic quotation frame.
6. **Audience routing** — Two-column destination rows.
7. **Closing call** — Dark work-photo invitation.
8. **Objection handling and ending** — White FAQ, then dark structured footer.

**Transfer:** Use the light physical-world opening as the default; select the proof and capability devices that explain the new product rather than reproducing the full sequence.

### Explain a platform's product layer and technical foundation

1. **Promise** — Centered white promise over brushed dark material, followed by customer marks.
2. **Product demonstration** — Light tabbed suite showcase paired with a dark technical showcase.
3. **Quantified proof** — Sandy stat band.
4. **Adoption reassurance** — Photographic call explains a staged starting point.
5. **Capability and ecosystem proof** — Split system diagram and integration fan.
6. **Audience routing** — Destination rows.
7. **Closing call** — Dark photographic invitation.
8. **Further reading and ending** — Resources, FAQ and the shared footer.

**Transfer:** Use a scoped dark opening when explaining a foundational system; keep the product and foundation showcases visibly related.

### Introduce a specialized product or agent

1. **Promise** — Breadcrumb, centered white headline and actions on dark material; wide video overlaps into the white section below.
2. **Scale proof** — Logo strip and textured numeric band.
3. **Capability chapters** — Three alternating split chapters demonstrate distinct tasks with framed UI.
4. **System context** — Technical diagram and related concept shelf.
5. **Closing call** — Short dark photographic invitation.
6. **Objection handling and ending** — Resources, product-specific FAQ and shared footer.

**Transfer:** Show what the specialized product does before expanding into architecture; use task-specific demonstration chapters rather than a general feature inventory.

### Make a broad platform relevant to one industry or audience

1. **Audience promise** — Left-aligned white headline over a contextual work photograph with dark fade.
2. **Early proof** — Textured outcome cards and a compact attributed quotation.
3. **Capability chapters** — Four alternating task-led split demonstrations.
4. **Customer proof** — Large photographic story frame.
5. **Starting-point routing** — Need-based destination rows, related concept shelf and technical foundation.
6. **Closing call** — Short dark photographic invitation.
7. **Further reading and ending** — Audience-specific resources, FAQ and shared footer.

**Transfer:** Use the audience's actual situations in copy and photography; reuse the system's typography and components instead of inventing an industry color theme.

### Explain the people, beliefs and credibility behind a company

1. **Mission promise** — Left white headline and recruiting action beside a large team photograph on dark brushed material.
2. **Origin story** — Split narrative and documentary team photograph.
3. **Principles** — Two-column numbered pale cards.
4. **Institutional proof** — Four-card textured stat band and muted backer strip.
5. **People** — Small square founder portraits beside extended biographies.
6. **External proof** — Three-column news links.
7. **Closing call and ending** — Recruiting invitation on a dark work image followed directly by the shared footer; no FAQ.

**Transfer:** Use the scoped people and mono treatments for company storytelling while retaining the main palette, display hierarchy and footer.

## Writing

Confident, practical and close to the reader's daily work. Claims are explained through specific tasks, constraints and outcomes rather than a visionary technology monologue.

**Do not copy:** Do not reuse DOSS names, logos, customer or investor marks, photographs, quotations, proprietary feature names, performance figures or adoption claims. Replace them with the new product's own assets and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you and your team. Use we for guided help and the product name when explaining a concrete mechanism.
- **Rhythm:** Headlines are sentence case and often a full proposition. Short support lines establish the benefit; longer feature paragraphs connect a real situation, what the system does and the resulting relief. No exclamation-driven sales language.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name the category and audience, or state the product's job in a conversational sentence. | 8–18 words for a broad promise; specialized explanations can be longer. | “The AI-Native Operations Platform for Consumer Goods”<br>“The platform that lets your operations reshape around your business” |
| Section heading | State a recognizable concern or a concrete outcome, often as a contrast. | 6–14 words. | “Growing shouldn’t mean a new system or another hire”<br>“Hand it the work, stay in control” |
| Support line | Explain the promise in practical nouns and tasks. | One short sentence for centered support; two or three connected sentences beside media. | “Build your single source of truth across inventory, cost, orders and procurement, for every channel.” |
| Conversion action | Direct verb plus the next useful thing. | 2–5 words. | “Book a demo”<br>“See all integrations”<br>“See open roles” |
| Closing invitation | Offer an action with the reader's own situation as the input. | A short headline and optional one-sentence invitation. | “Bring your SKUs, channels, and 3PLs. We’ll show you what one live record looks like.”<br>“Build with us” |
| FAQ answer | Answer directly, then explain the boundary or mechanism. | Two or three concise sentences. | “No. Most brands start with one or two and add the rest over time; every module runs on the same record, so each one you add builds on the last.” |

**Words and phrasing to use:** your team; one live record; start with; built into; in plain English; without rebuilding; stay in control; show you; add the next

**Avoid:** revolutionary; game-changing; unleash limitless potential; magic; effortless transformation; unqualified best-in-class claims

**Rules:**

- Make the feature paragraph show an input, an action and an outcome.
- Name familiar operational objects and constraints instead of abstract transformation.
- Use contrast to clarify a real difference: minutes versus months, one task versus a repeatable process.
- Keep button labels stable across the page; distinguish exploration from conversion.
- When discussing automation, explain what remains under the user's control.

## Do's and Don'ts

### Do

- Keep display headlines at 52px/58px and weight 400; use 44px/48px for chapter leads.
- Give split chapters 96px vertical padding and a 48px text-to-media gutter.
- Keep ordinary pale cards flat with 8px corners; reserve 16px corners for white proof cards.
- Use #0118df chiefly for 53px conversion pills and fine active details.
- Stage quantitative proof on the warm halftone field with 40px card gutters.
- Use real context photography in the opening ribbon and customer story frame.
- Pair dense demonstrations with narrow 18px explanations rather than additional marketing labels.
- End with the dark structured footer even when resources or FAQ follow the atmospheric call.

### Don't

- Do not set the main headings in bold or all caps; the display weight is 400.
- Do not turn the white-led page into a blue-gradient theme; blue is an action signal.
- Do not give every card a border and drop shadow; elevation belongs primarily to media.
- Do not apply pill geometry to content cards or use square primary actions.
- Do not use a monospace eyebrow on every section; mono belongs to scoped company proof and principle indexes.
- Do not render the customer story as a small floating quote over a photograph; keep the large adjacent white quote panel.
- Do not flatten all proof into a monochrome logo wall; preserve large numbers, texture and photographic stories.
- Do not make the footer a monumental decorative wordmark; it is a compact brand-and-navigation grid.

## Motion and responsive

### Motion

**Observed:**

- Color and background transitions commonly use .18s cubic-bezier(.22, 1, .36, 1). Capability-card backgrounds also use .3s with that curve.
- Play-control hover combines background and transform over .18s cubic-bezier(.22, 1, .36, 1), growing to scale(1.05).
- Editorial thumbnail transform transitions use 0.18s cubic-bezier(0.23, 1, 0.32, 1).
- Logo marquees declare marquee-scroll 42s linear infinite.
- The header declares background and box-shadow transitions over .5s cubic-bezier(.22, 1, .36, 1).

**Transfer:**

- Keep hover movement localized to media controls and thumbnail details; let pale tiles change tone instead of bouncing.
- Use slow linear logo movement for breadth of proof, preserving readable marks and soft edge fades.

**Unknown:**

- Exact opening-ribbon choreography, scroll reveal timing and video playback sequences are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 600px, 768px, 1024px and 1200px; the desktop compositions use a 24px container gutter.

**Transfer:**

- For narrow layouts, retain a centered light opening and the graduated photo-strip idea in a clipped horizontal region rather than squeezing all portraits equally.
- Stack split chapters in reading order and reduce multi-column proof and capability grids before shrinking the text.
- Keep the dark photographic call full-bleed and maintain a separate structured footer.

**Unknown:**

- Exact mobile font sizes, header menu behavior and breakpoint-specific grid arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
