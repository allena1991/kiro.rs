# General Intelligence Company — pastoral pixel futurism

## Overview

A sunny, game-world vision of technology pairs pixel-edged serif lettering with compact, matter-of-fact sans-serif copy. Expansive illustrated parks, blue skies and luminous greenery alternate with almost-white editorial space and delicate diagrams. The feeling is optimistic and humane rather than industrial, suited to ambitious tools, research organizations and products promising more freedom in everyday life.

### Essentials

- The future looks like a place to live, not a dashboard: a full-bleed illustrated landscape fills the opening, with a small centered 27px pixel-serif identity and a 500px-wide glass promise panel at the lower left.
- Headlines have the texture of an early digital storybook: ppmondwest at 48px/1.1, weight 500 and -0.02em tracking is the default section voice; the illustrated product invitation grows to 54px/1.1 at weight 400.
- Actions feel like tiny pieces of desktop hardware: 36px-high buttons use 8px corners, a dark graphite fill, and a miniature 12×16px capsule containing a right chevron rather than a big arrow.
- Color belongs to worlds, not to the prose: most of the long-form area is #fefffc with #2c2c2c headings; saturated blue, gold, orange and green live in the landscape scenes, including a broad #0081c0-backed product invitation.
- Pastoral pixels and schematic hairlines coexist: include an isolated pixel-art object beside editorial copy and a restrained line diagram inside a 24px-radius outer frame with a 12px-radius raised inner sheet. A simple original pixel plant and SVG node diagram are sufficient equivalents.
- Sections end with a horizon, not just a link list: include stacked 6px color stripes separated by 2px white gaps, a compact utility footer, and a 500px-deep luminous illustrated landscape revealed beneath it. The final artwork moves from dark teal edges toward a sunlit center.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Product sky | `#0081c0` | `--color-sky` | background, accent | Backing color of the illustrated product invitation; not a general text-link color. |
| Sky glass edge | `#41a1cf` | `--color-sky-edge` | border | Outline of the light glass action over the blue product scene. |
| Mint horizon | `#a0d7d1` | `--color-mint` | accent | Final closing stripe immediately above the landscape. |
| Soft mint stripe | `#d0ebe8` | `--color-mint-soft` | accent | Visible middle closing stripe: rgba(160,215,209,0.5) over white. |
| Pale mint stripe | `#e7f5f3` | `--color-mint-wash` | accent | Visible first closing stripe: rgba(207,235,231,0.5) over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Graphite action | `#1f1f29` | `--color-button` | action, surface | Main compact conversion button. |
| Graphite edge | `#282834` | `--color-button-edge` | border | Fine border on the dark conversion action. |
| Editorial ink | `#2c2c2c` | `--color-ink` | text | Default section headings and emphasized inline text. |
| Dusk stripe | `#334444` | `--color-stripe-dark` | accent | First stripe in the dark-to-light landscape transition. |
| Warm charcoal | `#444141` | `--color-body` | text, link | Utility links and stronger body copy. |
| Medium gray | `#646464` | `--color-muted` | text | Default supporting prose. |
| Slate stripe | `#576a6a` | `--color-stripe-mid` | accent | Second transition stripe. |
| Mist stripe | `#728383` | `--color-stripe-soft` | accent | Middle transition stripe. |
| Fog stripe | `#a5afaf` | `--color-stripe-pale` | accent | Fourth transition stripe. |
| Sage gray | `#b4b8b4` | `--color-subtle` | text, border | Figure labels, subordinate metadata and underlined secondary phrases. |
| Silver stripe | `#cfd3cf` | `--color-stripe-light` | accent | Final dark-to-light transition stripe. |
| Frame edge | `#dee2de` | `--color-rule` | border | Outer demonstration frame and social-button outlines. |
| Input edge | `#e5e5e5` | `--color-field-edge` | border | Newsletter field outline. |
| Frame wash | `#f9faf7` | `--color-frame-wash` | surface | Newsletter field; also the visible near-white wash of rgba(222,226,222,0.16) over the ivory canvas. |
| Ivory daylight | `#fefffc` | `--color-canvas` | background, surface | Main editorial canvas and inner demonstration sheets. |
| White | `#ffffff` | `--color-white` | text, background | Text on landscapes, white footer band and gaps between transition stripes; also the source of translucent glass highlights. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and recruiting pages | Deep ink | `#171717` | `--color-deep-ink` | text | Dark text for company and recruiting introductions. |
| company story pages | Letter edge | `#eef1ed` | `--color-paper-edge` | border | Subtle border around the signed letter. |

## Typography

- **ppmondwest** — Identity, promises and section headlines. Pixel-edged proportional serif with old digital-game warmth, thin strokes and lively letter shapes. If unavailable, use **Jacquard 12**. Use the least ornate letterforms available; preserve close spacing and test short mixed-case lines. Font stack: "ppmondwest", "Jacquard 12", Georgia, serif.
- **af** — Supporting copy, navigation, captions and actions. Compact neutral grotesk, medium weight, with a high readable x-height and restrained negative tracking. If unavailable, use **Inter**. Use weight 500 and preserve the compact 15px body scale. Font stack: "af", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| product-display | ppmondwest | 400 | 54px | 1.1 | -0.02em | Expansive product invitation on the illustrated sky panel. |
| heading | ppmondwest | 500 | 48px | 1.1 | -0.02em | Default editorial section headline, narrative statement and closing invitation. |
| hero-promise | ppmondwest | 500 | 40px | 1.1 | -0.02em | White promise inside the landscape glass panel. |
| identity | ppmondwest | 400 | 27px | 1.5 | -0.04em, features "liga" 0 | Small centered two-line identity floating near the top of the landscape. |
| card-heading | af | 500 | 18px | 1.3 | -0.01em | Centered editorial-card titles. |
| body | af | 500 | 15px | 1.4 | -0.01em | Default prose, text actions and navigation. |
| caption | af | 500 | 13px | 1.3 | -0.01em | Figure labels, compact informational cards and secondary row metadata. |
| utility | af | 500 | 13px | 1.4 | -0.01em | Footer navigation and editorial-card source lines. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and recruiting pages | company-display | ppmondwest | 400 | 54px | 1.1 | -0.02em, features "liga" 0 | Centered introductory identity on company-oriented pages. |
| company story pages | manifesto-heading | ppmondwest | 400 | 48px | 1.1 | -0.02em, features "liga" 0 | Centered thesis above the personal letter. |
| recruiting pages | culture-heading | ppmondwest | 500 | 40px | 1.1 | -0.024em | Editorial statement beside documentary workplace photographs. |
| company story pages | letter-body | af | 500 | 17px | 1.3 | -0.016em | Longer personal letter paragraphs. |

**Notes:**

- The default hierarchy is a modest identity above a larger promise, not a giant typographic hero. Pixel-serif headlines carry the emotional register while small grotesk copy carries specifics.
- Use sentence case and natural mixed-case names. The negative tracking is strongest on the small identity; ordinary section headlines stay at -0.02em.
- Keep supporting paragraphs narrow, commonly 360px, even when their neighboring headline uses a wider column.

## Layout

**Density:** Airy at the section scale, compact within individual controls and informational cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Label-to-icon gaps and tight card grids. |
| 16px | Glass-panel content gap and padding around inner diagram sheets. |
| 24px | Editorial grid gap, article caption padding and heading-to-link separation. |
| 32px | Glass-panel padding and product headline-to-support spacing. |
| 40px | Letter padding and image-to-prose separation. |
| 48px | Section-heading group to article grid; desktop outer section gutters. |
| 64px | Two-column vision gap and paragraph-to-headline separation. |
| 80px | Closing-call top padding and illustrated product panel side padding. |
| 128px | Illustrated product invitation top padding. |
| 200px | Default spacious editorial section top and bottom padding. |

### Containers and grids

- **wide-content**: max width 1280px · side padding 20px. Centered editorial cards and footer utility row; let the landscape continue full bleed behind or beyond it.
- **editorial-pair**: max width 1080px · 2 columns · gap 64px · side padding 48px. Pixel-art object in the left column; a narrow paragraph and wider headline in the right.
- **article-grid**: 3 columns · gap 24px. Three equal 400px-wide illustrated stories across a 1248px content area.
- **hero-panel**: max width 500px. Lower-left readable island within a full-width landscape.
- **letter-column** (only for company story pages): max width 540px · side padding 40px. Centered personal letter, distinct from the wider statement above it.
- **culture-grid** (only for recruiting pages): 3 columns · gap 8px. 240px-wide translucent principle cards over a wide office illustration.

## Corner radius

| Element | Radius |
| --- | --- |
| actions-and-fields | 8px |
| floating-navigation-and-captions | 12px |
| glass-and-media | 16px |
| outer-frames-and-product-scene | 24px |
| chevron-capsule | 50.5px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| glass | `0px 2px 6px 0px rgba(0,0,0,0.15)` | Glass panels and floating navigation. |
| inner-sheet | `0px 1px 1px 0px rgba(0,0,0,0.08), 0px 4px 5px 0px rgba(0,0,0,0.08)` | Inner diagram sheet and opportunity list. |
| media-rim | `0px 2px 2px 0px rgba(0,0,0,0.06), 0px 0px 0px 5px rgba(0,0,0,0.04)` | Broad illustrated product scene and city invitation. |

### Surfaces

#### Daylight canvas · level 0

**Use:** Long-form editorial areas.

**CSS:** `background: #fefffc`

**Observed:** Nearly white with a faint green warmth; prose sections remain untextured.

**Transfer:** Let the artwork, not the canvas, supply rich texture.

#### Landscape glass · level 1

**Use:** Readable promise or invitation on a complex scene.

**CSS:** `background: linear-gradient(to right, rgba(0,0,0,0.12) 0px, rgba(0,0,0,0.07) 50%, rgba(0,0,0,0.07) 100%); border: 1px solid rgba(255,255,255,0.2); border-radius: 16px; backdrop-filter: blur(15px); box-shadow: 0px 2px 6px 0px rgba(0,0,0,0.15)`

**Observed:** The scene's orange, green or blue remains visible as broad blurred color behind white type.

**Transfer:** Place over an area with enough tonal variation to make the blur legible without obscuring the scene's focal point.

#### Double demonstration frame · level 1

**Use:** Backing for fine schematic art.

**CSS:** `background: rgba(222,226,222,0.16); border: 1px solid #dee2de; border-radius: 24px; padding: 16px`

**Observed:** A pale outer tray encloses a slightly raised ivory inner sheet.

**Transfer:** Use one coherent framed diagram rather than a collection of unrelated UI tiles.

#### Inner sheet · level 2

**Use:** Diagram drawing plane.

**CSS:** `background: #fefffc; border-radius: 12px; box-shadow: 0px 1px 1px 0px rgba(0,0,0,0.08), 0px 4px 5px 0px rgba(0,0,0,0.08)`

**Observed:** The diagram has considerable empty space around its faint lines.

**Transfer:** Keep diagram marks far lighter than headline ink.

#### Blue illustrated invitation · level 1

**Use:** Broad product conversion scene.

**CSS:** `background-color: #0081c0; border-radius: 24px; overflow: hidden; box-shadow: 0px 2px 2px 0px rgba(0,0,0,0.06), 0px 0px 0px 5px rgba(0,0,0,0.04)`

**Observed:** Sky artwork covers a 1392×800px panel, inset 24px from the viewport edges.

**Transfer:** Use original art with a clear upper-left sky area and dense nature toward the bottom and right.

#### Closing white band · level 0

**Use:** Final statement and utility footer.

**CSS:** `background: #ffffff`

**Observed:** The clean band separates editorial content from the deep landscape beneath.

**Transfer:** Keep this band visually lighter and calmer than both adjacent scenes.

#### Landscape bottom veil · level 1

**Use:** Legible small credits at the base of the closing art.

**CSS:** `background: linear-gradient(rgba(255,255,255,0) 75%, rgba(0,0,0,0.82))`

**Observed:** The image remains bright through most of its height and darkens strongly only near the base.

**Transfer:** Keep the light at the horizon; do not darken the entire artwork.

## Components

### Floating navigation

**Use:** Persistent compact site navigation.

**CSS:** `position: fixed; top: 16px; height: 54px; border-radius: 12px; background: linear-gradient(to right in oklab, rgba(249,250,247,0.12) 0px, rgba(249,250,247,0.18) 100%); border: 1px solid rgba(255,255,255,0.2); backdrop-filter: blur(9px); box-shadow: 0px 2px 6px 0px rgba(0,0,0,0.15)`

**Text style:** `body` — af 500 · 15px/1.4 · tracking -0.01em

**Observed:** A centered floating island, about 441px wide, containing a small symbol, three short links and Primary button. Links read light over the opening art and dark over the editorial canvas.

**Transfer:** Keep the navigation content-fit rather than stretching it into a conventional full-width header.

### Primary button

**Use:** Main conversion action, especially inside navigation.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; height: 36px; padding: 8px 12px 8px 16px; background-color: #1f1f29; background-image: linear-gradient(90deg, rgba(255,255,255,0) 0%, rgba(255,255,255,0.12) 100%); color: #ffffff; border: 1px solid #282834; border-radius: 8px`

**Text style:** `body` — af 500 · 15px/1.4 · tracking -0.01em

**Observed:** Short label followed by Chevron capsule. Over the blue invitation the action becomes translucent light glass with a sky-colored edge and equal 16px side padding.

**States:** Declared: hover opacity 0.9; focus-visible zero-shadow stack.

### Chevron capsule

**Use:** Tiny directional marker beside text actions.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 12px; height: 16px; padding-left: 2.5px; padding-right: 1.5px; border-radius: 50.5px; border: 1px solid rgba(255,255,255,0.24); background: linear-gradient(0deg, rgba(255,255,255,0.16) 0%, rgba(255,255,255,0.08) 100%); box-shadow: 0px 1px 1px 0px rgba(0,0,0,0.04)`

**Observed:** A filled right chevron sits inside the narrow upright capsule; dark-on-light actions use a darker translucent outline.

**Transfer:** Keep this marker small enough to feel like a keycap, not a separate button.

### Glass promise panel

**Use:** Headline, support and editorial action over landscape art.

**CSS:** `max-width: 500px; padding: 32px 24px 32px 32px; border-radius: 16px; border: 1px solid rgba(255,255,255,0.2); background: linear-gradient(to right, rgba(0,0,0,0.12) 0px, rgba(0,0,0,0.07) 50%, rgba(0,0,0,0.07) 100%); backdrop-filter: blur(15px); box-shadow: 0px 2px 6px 0px rgba(0,0,0,0.15); color: #ffffff`

**Text style:** `hero-promise` — ppmondwest 500 · 40px/1.1 · tracking -0.02em

**Observed:** A left-aligned headline is followed by a compact paragraph and a text link with Chevron capsule. It remains an island within the landscape rather than becoming a full-width overlay.

### Editorial text action

**Use:** Secondary conversion, reading and recruiting links.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; height: 36px; color: #ffffff`

**Text style:** `body` — af 500 · 15px/1.4 · tracking -0.01em

**Observed:** Only the words receive a thin underline; the Chevron capsule sits outside the underline. On the ivory canvas the text is warm charcoal or editorial ink.

**States:** Declared: hover color #ffffff for the landscape variant; focus-visible color #2c2c2c with a zero-shadow stack.

### Article caption

**Use:** Readable title block within illustrated editorial cards.

**CSS:** `position: absolute; bottom: 24px; left: 40px; right: 40px; padding: 24px; border-radius: 12px; background: rgba(255,255,255,0.85); backdrop-filter: blur(10px); text-align: center`

**Text style:** `card-heading` — af 500 · 18px/1.3 · tracking -0.01em

**Observed:** A two-line title sits above a smaller source line in utility type. The inset translucent block overlaps the lower portion of a rounded 400×350px image.

### Newsletter field

**Use:** Compact subscription action beside social links in the footer.

**CSS:** `display: flex; align-items: center; justify-content: space-between; max-width: 222px; height: 38px; padding-left: 12px; background: #f9faf7; border: 1px solid #e5e5e5; border-radius: 8px`

**Text style:** `utility` — af 500 · 13px/1.4 · tracking -0.01em

**Observed:** One quiet inline field with a small trailing directional submit control; no large form panel.

### Footer link

**Use:** Small horizontal utility navigation.

**CSS:** `display: inline-flex; align-items: center; height: 36px; border-radius: 4px; color: #444141`

**Text style:** `utility` — af 500 · 13px/1.4 · tracking -0.01em

**Observed:** Links form a compact left-aligned row with 12px gaps, balanced by Newsletter field and two square social controls on the right.

**States:** Declared: hover color #2c2c2c and opacity 0.7; focus-visible color #2c2c2c with a zero-shadow stack.

### Signed letter

**Only for:** company story pages

**Use:** Personal explanation of the mission.

**CSS:** `max-width: 540px; padding: 40px; background: #fefffc; border: 1px solid #eef1ed; border-radius: 16px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Text style:** `letter-body` — af 500 · 17px/1.3 · tracking -0.016em

**Observed:** Three compact paragraphs lead to a generous pause, a warm sign-off, pale names and handwritten signatures. A tilted illustrated postage stamp overlaps the lower-right edge.

**Transfer:** Use authentic author names and a custom stamp illustration tied to the new organization.

### Opportunity list

**Only for:** recruiting pages

**Use:** A concise set of open roles.

**CSS:** `max-width: 725px; background: #fefffc; border-radius: 16px; overflow: hidden; box-shadow: 0px 1px 1px 0px rgba(0,0,0,0.08), 0px 4px 5px 0px rgba(0,0,0,0.08)`

**Text style:** `body` — af 500 · 15px/1.4 · tracking -0.01em

**Observed:** The list sits inside Double demonstration frame. Each approximately 91px row has 24px vertical and 32px horizontal padding, title above pale 13px metadata, faint separators and a right chevron in a tall rounded control.

## Imagery and graphics

### Pastoral digital worlds

**Use:** Opening and closing visual anchors, with a related scene behind the product invitation.

**Observed:** Detailed pixel-painted urban parks use real architectural silhouettes, leafy framing, tiny people and animals, reflective water and broad clear skies. The opening is autumnal gold and red against vivid blue; the closing is deep teal and green with a bright central avenue. Images dominate their sections while text occupies only a small glass island.

**Transfer:** Commission an original optimistic environment relevant to the product's benefit. Keep recognizable everyday life, rich nature, small human scale and a carefully reserved text area. The minimum version is an original low-resolution landscape with layered trees, sky and a lit path, enlarged with crisp pixel edges; not a generic gradient.

**Build:** Create a low-resolution raster or rect-based SVG scene on a roughly 480px-wide artboard and enlarge 3× with crisp edges. Layer sky, distant block-shaped buildings or hills, middle-distance foliage and dark foreground branches. Use clustered rectangular leaf marks rather than smooth vector blobs. Reserve open sky near the top center and a broad low-contrast patch behind the lower-left text. For the closing scene, arrange darker tree masses at both edges and a bright narrow vanishing point in the center.

### Pixel specimen

**Use:** A standalone illustrated object beside an editorial vision statement.

**Observed:** One yellow flower on a green stem occupies a 300×450px drawing area, floating directly on the ivory canvas without a frame. Its stepped edges and limited colors contrast with the delicate text.

**Transfer:** Include a single original pixel object that symbolizes growth or the product's benefit. Retain its small-scale game-sprite character rather than replacing it with a glossy 3D render.

**Build:** Draw a compact sprite on a roughly 60×90-cell SVG or raster grid. Cluster yellow and cream squares into the lit object head, darker ochre beneath, and green stepped leaves and stem below. Enlarge with nearest-neighbor scaling; leave the surrounding drawing area transparent.

### Schematic progression

**Use:** A capability explanation inside Double demonstration frame.

**Observed:** Fine gray squares, dotted circles, orbital connectors and later neat rows of circles evolve across a long scroll chapter. A narrow prose column and tiny bar-like progress marks sit to the left; small figure captions align below the drawing.

**Transfer:** Explain a real progression in the new product with a sparse diagram. Start from disconnected parts, show relationships, then show organized output; do not imitate a detailed product interface.

**Build:** Use an SVG with 1px sage-gray strokes, no filled node bodies, and ample blank space. Begin with varied 12–32px squares around a dotted center, introduce thin elliptical connectors, then replace with equal circles in a grid. Keep labels outside the drawing plane and use caption type for figure numbers.

### Blue-sky editorial covers

**Use:** Article cards and the broad product invitation.

**Observed:** Pixel clouds, foliage at corners and occasional central marks make the cards feel like windows into the same world. The product invitation uses oversized sunflowers growing upward from the lower and right edges under a large blue sky.

**Transfer:** Carry one coherent illustrated ecosystem into editorial thumbnails. Keep the subject or mark centered and give it clear sky rather than filling every cover with dense detail.

**Build:** For covers, use a blue sky plane, blocky white cloud clusters, and layered green leaves in two corners. For the broad invitation, place 3–5 pixel flowers at varied scales along the lower edge, largest at the right, leaving the upper-left half open for white text.

### Documentary workplace pairing

**Only for:** recruiting pages

**Use:** Ground the illustrated ambition in real working life.

**Observed:** Two differently proportioned photographs share a 1080px two-column grid with a 16px gap: a tall outdoor portrait and a shorter naturally lit office image with plants and informal details. Text sits below each at different heights.

**Transfer:** Use candid daylight photographs, not stock team poses. Preserve the uneven image heights and asymmetrical text placement.

### Personal postage

**Only for:** company story pages

**Use:** A warm handcrafted counterpoint at the letter's lower edge.

**Observed:** Handwritten signatures and an oversized illustrated postage stamp with scalloped edges overlap the paper; the stamp contains a blue-sky city scene.

**Transfer:** Use an original small place illustration tied to the authors, retaining the stamp silhouette and slight rotation.

**Build:** Clip a small landscape to a rectangle with evenly spaced circular edge cutouts using an SVG mask. Add a pale paper rim, rotate slightly, and overlap the lower-right letter corner without covering the final paragraph.

### Icons

**Observed:** Very small solid chevrons are usually 6×10px; functional outline symbols are approximately 13–15px with thin strokes. The navigation begins with a small rising-sun-like mark. Social marks sit in 36px square, 8px-radius outlined buttons.

**Transfer:** Choose simple monochrome glyphs, sized to the small typography. Use the upright chevron capsule consistently instead of mixing arrow families.

## Section recipes

How recurring sections are built.

### First screen: Landscape promise opening

**Observed:** A 1440px-wide, 1344px-tall illustrated landscape opens the page. Back to front: full-bleed art, a small two-line centered identity near the upper sky in identity type, a tiny upper-right time/location detail, Floating navigation above it, then Glass promise panel at the lower left. The first 900px show the sky and skyline framed by autumn branches, the identity, navigation, a 40px two-line promise, supporting paragraph and Editorial text action. The glass island is about one third of the width, inset 16px from the left and roughly 272px tall. The lower park, pond, small people, secondary scene caption and transition stripes continue below the fold.

**Transfer:** For a new product, let an original landscape express the life it enables, with a short identity in the sky and a clear benefit in the lower-left panel. Without elaborate artwork, use the layered pixel landscape recipe, not a blank colored background. Recruiting pages instead open on ivory with a centered 54px identity, a small context label and photographs beginning around 558px down; company story pages retain the landscape but use a larger centered identity and a mission panel.

**Avoid:** Do not replace this composition with a centered giant slogan, a dashboard mockup and two oversized pill buttons; it would remove the small human-scale promise inside a large world.

**Text style:** `hero-promise` — ppmondwest 500 · 40px/1.1 · tracking -0.02em

### Specimen and vision

**Observed:** Daylight canvas with 200px top and bottom space; editorial-pair layout places Pixel specimen left and a 360px paragraph above a 48px multi-line statement right, separated vertically by 64px.

**Transfer:** Pair a tangible metaphor with a concise account of the future the product makes possible; the art and text should balance without a surrounding card.

**Text style:** `heading` — ppmondwest 500 · 48px/1.1 · tracking -0.02em

### Pinned schematic chapter

**Observed:** A left-aligned 48px thesis spans about 700px within a 1080px container. One secondary phrase is pale and underlined; a short follow-up sentence sits 32px below. Beneath, a small explanatory column faces a 640×359px Double demonstration frame. A sticky drawing and narrative update across a long scroll chapter, with small right-aligned figure labels.

**Transfer:** Use a few meaningful states to explain a system or process; preserve the broad quiet canvas and the contrast between expressive serif thesis and tiny schematic detail.

**Text style:** `heading` — ppmondwest 500 · 48px/1.1 · tracking -0.02em

### Illustrated product invitation

**Observed:** Blue illustrated invitation spans nearly the viewport width with 24px outer gutters. Its 800px height contains a 54px white headline at the upper left, up to about 842px wide, then support and a compact glass action. Padding is 128px top and 80px at the sides; huge pixel flowers grow from the bottom and right. A small lower-left aside and occasional floating notification add scale.

**Transfer:** Turn a benefit into a single bright world, keeping most illustration below or beside the copy. A notification can demonstrate actual product output, but the sky scene must carry the section even without it.

**Text style:** `product-display` — ppmondwest 400 · 54px/1.1 · tracking -0.02em

### Editorial windows

**Observed:** A 48px left-aligned heading and a secondary reading action lead to a three-column article-grid 48px below. Each card combines rounded illustrated media and Article caption. The section retains 200px breathing room around its content.

**Transfer:** Show relevant stories or proof in related illustrated windows rather than conventional white text cards.

**Text style:** `heading` — ppmondwest 500 · 48px/1.1 · tracking -0.02em

### Invitation and horizon ending

**Observed:** A white closing band has 80px top space, a small emblem and centered 48px two-line invitation, followed 32px later by a soft supporting sentence ending in an underlined text action. Utility links align left and Newsletter field plus social controls align right well below the invitation. Three 6px mint stripes with white gaps separate this band from a 500px-deep pastoral avenue scene. The image is a fixed lower layer revealed by the ending content; Landscape bottom veil supports small white corner credits. Recruiting pages omit the repeated invitation and close with the opportunity list followed by the same utility row and landscape.

**Transfer:** Close with a humane next step, compact practical links and a memorable illustrated horizon. Keep the landscape as a real closing destination rather than treating the link row as the end of the page.

**Text style:** `heading` — ppmondwest 500 · 48px/1.1 · tracking -0.02em

### Signed manifesto

**Only for:** company story pages

**Observed:** A narrow centered introductory paragraph leads to a centered manifesto-heading spanning 816px. Signed letter sits beneath with about 100px separation; its handwritten details and Personal postage soften the surrounding typography.

**Transfer:** Use a genuine authorial explanation or founding thesis rather than adding a letter to ordinary feature pages.

**Text style:** `manifesto-heading` — ppmondwest 400 · 48px/1.1 · tracking -0.02em

### Culture in place

**Only for:** recruiting pages

**Observed:** An asymmetrical Documentary workplace pairing leads into a full-width 636px office illustration. A white 48px headline sits above eight small Landscape glass cards in three columns, with one unfilled position in the final row. Cards use 20px padding and compact caption type.

**Transfer:** Describe real working principles over a warm lived-in environment. Keep the list concise and the illustration subordinate to readable text.

**Text style:** `heading` — ppmondwest 500 · 48px/1.1 · tracking -0.02em

### Place-based invitation

**Only for:** company story pages

**Observed:** A 1016×611px rounded city-and-lake illustration holds a 400px glass panel at its upper left, with a 40px invitation, short paragraph and underlined action. Below, small two-column contact and press details remain on the ivory canvas.

**Transfer:** Use a meaningful place or community scene and a specific invitation, followed by restrained practical contact information.

**Text style:** `hero-promise` — ppmondwest 500 · 40px/1.1 · tracking -0.02em

## Page flow

**Storyline:** An inhabited future → a human ambition → an explanation of how it works → a concrete invitation or proof → a personal next step → a luminous horizon.

### Product or organization marketing landing page

1. **Promise** — Immersive landscape with a small identity and glass benefit panel.
2. **Vision** — Isolated pixel specimen beside editorial prose and a larger future-facing statement.
3. **Capability explanation** — Pinned thesis and framed diagrams progress from separate parts to coordinated output.
4. **Conversion** — Broad blue illustrated invitation with a direct product action.
5. **Proof** — Three illustrated story windows.
6. **Closing call** — Centered invitation, compact utilities, mint transition and illustrated horizon.

**Transfer:** Preserve the alternation between rich worlds and sparse explanation; adapt the order and number of proof or capability blocks to the product.

### Recruiting and culture page

1. **Identity** — Centered serif introduction on ivory with a small working-context label.
2. **Human proof** — Uneven documentary photo pair and short statements about the work.
3. **Working principles** — Small glass cards over an illustrated office.
4. **Available next steps** — Centered headline above a double-framed opportunity list and a secondary browse action.
5. **Ending** — Utility footer followed by the same mint stripes and luminous avenue illustration.

**Transfer:** Use the real people, place and opportunities of the organization; reserve the compact principle grid for culture content.

### Company story and mission page

1. **Mission** — Green park scene with a centered identity and left-side glass mission panel.
2. **Thesis** — Centered introductory prose and serif statement.
3. **Personal explanation** — Signed letter with a place-themed stamp.
4. **Invitation** — Framed city landscape with a glass recruiting call and practical contact details.
5. **Closing call** — Centered invitation, utilities, mint stripes and the shared illustrated horizon.

**Transfer:** Use a personal story and a meaningful place to make an abstract mission tangible; keep these authorial devices scoped to story pages.

## Writing

Optimistic, direct and unusually earnest about a better future. The copy makes ambitious statements in ordinary language, then becomes compact and practical when explaining how things work.

**Do not copy:** Do not reuse the company name, Cofounder product name, founder signatures, customer and investor names, New York identity, proprietary illustrations, numerical business claims or the source's assertions about autonomous companies. Source examples illustrate tone only.

- **Addressing the reader:** Use we for the builders and you for the person enabled by the product. Product names appear when a concrete invitation replaces the broader vision.
- **Rhythm:** Short declarative sentences alternate with longer future-facing headlines. Supporting paragraphs stay compact, often two or three sentences; actions are brief verbs and plain nouns rather than slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Promise | Name a concrete capability in plain language, without an adjective stack. | 5–10 words | “AI that runs businesses autonomously” |
| Vision | Describe an everyday possibility becoming easier, often using a familiar comparison. | 12–24 words | “Where starting up a real world company is as easy as playing a video game.” |
| Supporting line | State who is building what and why, without marketing superlatives. | 15–35 words | “The [Brand] is an applied AI lab working towards automating businesses full-stack with AI.” |
| Explanatory turn | Follow a problem statement with a short, definitive sentence. | 3–8 words | “They need a coordinator.” |
| Primary action | Use a direct verb plus the destination or product. | 2–5 words | “Get Cofounder”<br>“Get to know us” |
| Culture statement | Use brisk imperatives with a human ambition behind them. | 3–10 words per sentence | “Make beautiful things.”<br>“Scope small. Ship fast. Iterate in tight loops to stay close to real feedback.” |
| Closing invitation | Lead gently into a specific personal next step. | 6–16 words | “If that sounds interesting to you,”<br>“come work with us” |

**Words and phrasing to use:** build; world; ideas; tools; people; beautiful; future; make; enable

**Avoid:** revolutionary solution; unlock limitless potential; 10x everything; industry-leading platform; synergize; excessive jargon

**Rules:**

- Let the headline carry one idea and the support line supply the concrete mechanism.
- Frame technology around what people can do with it, not only the machinery itself.
- Use declarative confidence without exclamation marks or breathless urgency.
- Make culture copy more blunt and imperative than general marketing prose.
- Keep closing invitations warm and conditional rather than applying sales pressure.

## Do's and Don'ts

### Do

- Keep the default section serif at 48px/1.1 with -0.02em tracking.
- Make the opening landscape larger than the copy panel; use a 500px panel rather than a full-width text overlay.
- Use 15px/1.4 medium grotesk prose and constrain supporting paragraphs to about 360px.
- Retain the 36px action height and 8px button corners across navigation and illustrated invitations.
- Separate rich artwork from sparse prose with 200px editorial breathing room.
- Include the stepped horizontal stripe motif using 6px bands and 2px white gaps.
- Use the 24px outer tray and 12px inner drawing sheet to stage faint diagrams.
- Give the closing landscape 500px of visual depth beneath the white utility band.

### Don't

- Do not replace the pixel serif with a heavy modern sans-serif at 700 weight; it erases the storybook register.
- Do not make blue the default body text, border and button color; its strong fill belongs to the illustrated invitation.
- Do not enlarge the capsule chevrons into 24px arrow circles; their narrow 12×16px scale is intentional.
- Do not turn article captions into opaque full-height cards; retain the 85% white translucent inset.
- Do not put blur on the ivory editorial canvas; 9–15px backdrop blur belongs to glass over actual imagery.
- Do not add large diffuse colored shadows to the diagram tray; the inner sheet uses short neutral 1px and 4px shadows.
- Do not spread the utility footer into a multi-column sitemap; keep 13px links in a compact row.
- Do not put documentary team photography on every product section; it is a recruiting-specific counterpoint to the illustrated world.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares an all-property transition of 0.25s cubic-bezier(0.4,0,0.2,1).
- Primary button declares opacity .15s cubic-bezier(.4,0,.2,1), with hover opacity 0.9.
- Text actions declare color-related transitions of 0.2s cubic-bezier(.4,0,.2,1).
- The capability chapter uses sticky headline and diagram regions across changing diagram states; the closing landscape is fixed beneath the content.

**Transfer:**

- Keep the contrast between a stationary narrative frame and changing diagram state; the animation should explain progression rather than decorate every card.
- Preserve the reveal of the closing landscape beneath the white footer band.

**Unknown:**

- Exact scroll-state timing and interpolation for schematic transformations are unspecified.
- Reduced-motion behavior and the trigger logic for entry text effects are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 400px, 420px, 640px, 768px, 1024px, 1280px, 1536px and 1920px.
- Headline classes include 22px, 28px, 32px, 40px and 48px stepped sizes; the landscape promise uses 22px, 28px and 40px.
- Editorial story grids declare one column initially, two at 640px and three at 1280px. The specimen pair becomes two columns at 768px; the documentary pair at 640px.
- The floating navigation is content-fit and rounded on desktop; smaller-width declarations use a full-width navigation.
- Glass-panel padding changes from 20px to the desktop 32px treatment; the illustrated invitation changes from 20px side padding and 48px top padding to 80px sides and 128px top.

**Transfer:**

- On narrow screens retain the landscape as the main opening object and place a readable glass promise above its lower edge; keep the tiny identity separate from the promise.
- Stack specimen and explanation, and allow the schematic chapter to read as a normal sequence rather than forcing the desktop side-by-side composition.
- Preserve the stripe motif and closing illustrated horizon even when utility links wrap.

**Unknown:**

- Actual mobile compositions and touch interactions have not been visually established.
- Exact narrow-screen landscape focal points and sticky behavior remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
