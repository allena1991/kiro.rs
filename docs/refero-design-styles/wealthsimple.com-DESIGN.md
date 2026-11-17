# Wealthsimple — money as sculpture

## Overview

An editorial financial style with the confidence of a luxury object campaign and the friendliness of a useful everyday tool. Cream and near-white reading spaces alternate with immersive, softly lit product worlds in smoky blue, taupe, lavender and peach. A rounded geometric sans carries direct promises while a refined serif delivers expansive statements, with dimensional objects, warm lifestyle photography and unusually spacious compositions.

### Essentials

- A promise is staged beside a single monumental object: a 900px full-bleed opening, roughly equal text and object halves, a 580px text column and 64px/1.16 medium sans headline.
- Editorial authority interrupts the product theatre: regular serif statements reach 128px with -0.01em tracking, against #f5f3ef rather than a pure-white dashboard canvas.
- Controls look like small physical capsules: 64px conversion pills with 20px 32px padding, 44px navigation pills and 1.5px outlined alternatives; no bright action color.
- Color belongs to the stage, not the interface: neutral reading bands occupy roughly half the long-form canvas, while blue, purple, brown, green and peach occupy whole 900px media chapters rather than scattered accents.
- Light makes the product tangible: one oversized metal, glass, stone or sculptural object with soft directional illumination and a diffuse contact shadow must anchor the page; use a simple shaded geometric object when no product model exists.
- The ending has monumental scale too: a 128px serif proof statement and a sculptural emblem lead into a six-column footer with a near-container-width wordmark artwork, 1184px by 195px at desktop.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue night | `#080f16` | `--color-night` | background | Atmospheric opening backing beneath illuminated artwork. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Smoky purple | `#5f5974` | `--color-smoke-purple` | background | Dimensional product-stage backing with light text. |
| Smoky brown | `#564c47` | `--color-smoke-brown` | background | Metal-object stage backing with light text. |
| Deep forest | `#0c330d` | `--color-forest` | background | Abstract dimensional-tool stage backing. |
| Butter yellow | `#eee3b1` | `--color-butter` | surface | Large editorial invitation panel, not a button color. |
| Dusk gray | `#9894a3` | `--color-dusk` | background | Top of the atmospheric dusk gradient. |
| Dusk lilac | `#b3abbc` | `--color-dusk-lilac` | background | Upper transition of the dusk gradient. |
| Mist lilac | `#d6c9dc` | `--color-mist-lilac` | background | Soft middle transition of the dusk gradient. |
| Pink mist | `#f0dcef` | `--color-pink-mist` | background | Dusk gradient transition into warm light. |
| Rose mist | `#f4dce4` | `--color-rose-mist` | background | Middle of the dusk gradient. |
| Peach mist | `#fbdcd1` | `--color-peach-mist` | background | Lower dusk gradient transition. |
| Peach light | `#ffdcc4` | `--color-peach` | background | Warm base of the dusk gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Card white | `#ffffff` | `--color-white` | surface | Bordered editorial cards on the near-white canvas. |
| Near white | `#fcfcfc` | `--color-canvas` | background, text, action | Light product-page canvas and text or filled actions on dark stages. Navigation uses this at 95% opacity; outlined controls use 20% opacity. |
| Warm paper | `#f5f3ef` | `--color-paper` | background | Default editorial bands and footer canvas. |
| Pale edge | `#e4e2e1` | `--color-edge` | border | Light card outlines and comparison-table dividers. |
| Input edge | `#94908d` | `--color-input-edge` | border | Subtle email input outline on an atmospheric stage. |
| Warm gray | `#686664` | `--color-muted` | text, border | Secondary detail text and dark-theme table rules. |
| Raised charcoal | `#32302f` | `--color-charcoal` | surface, border | FAQ rules and circular actions; dark navigation uses this at 95% opacity. |
| Near-black ink | `#1c1b1b` | `--color-ink` | text, action, background | Default text and filled actions; also the canvas for the dark premium-product variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light comparison tables | Highlighted column | `#f1f0f0` | `--color-column` | surface | A restrained emphasized comparison column. |
| borrowing-style product stories | Architectural sand | `#d8cdc1` | `--color-sand` | surface, background | Sculptural architectural imagery and closing stage. |
| company and culture pages | Editorial stone | `#eeece7` | `--color-stone` | background, surface | Alternating organizational reading bands and feature tiles. |
| company and culture pages | Soft olive | `#9faa75` | `--color-olive` | surface | Editorial feature tile. |
| company and culture pages | Pale sage | `#e4e9d3` | `--color-sage` | surface | Companion editorial feature tile. |
| investment option comparisons | Portfolio navy | `#313b58` | `--color-navy` | surface | Dark option card and allocation segment. |
| investment option comparisons | Portfolio lavender | `#b4acbb` | `--color-lavender` | surface | Middle option card and allocation segment. |
| investment option comparisons | Portfolio blush | `#f6e7f8` | `--color-blush` | surface | Light option card. |

## Typography

- **the-future** — Promises, body, navigation, buttons and card headings. Geometric sans with open circular forms, a friendly single-storey character and medium rather than heavy display weight. If unavailable, use **Outfit**. Use 400 and 500; preserve the slightly positive tracking. Font stack: "the-future", "Outfit", system-ui, "Helvetica Neue", sans-serif.
- **tiempos** — Editorial statements, section headings, figures and small sentence-case eyebrows. Refined text serif with sturdy bracketed serifs, moderate contrast and compact lowercase proportions. If unavailable, use **Libre Caslon Text**. Use regular 400 with -0.01em tracking; rebalance line breaks for its width. Font stack: "tiempos", "Libre Caslon Text", Lucida, Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| statement | tiempos | 400 | 128px | 1.16 | -0.01em | size clamp(32px, 3.8px + 9.02vw, 128px) | Large editorial interruption on paper. |
| closing-proof | tiempos | 400 | 128px | 1.08 | -0.01em | size clamp(56px, 34.9px + 6.77vw, 128px) | Centered monumental proof line before the footer. |
| hero | the-future | 500 | 64px | 1.16 | 0.005em | size clamp(40px, 33px + 2.26vw, 64px) | Default immersive opening promise. |
| invitation | the-future | 400 | 56px | 1.16 | 0.005em | size clamp(24px, 14.6px + 3.01vw, 56px) | Centered conversational editorial invitation. |
| heading | tiempos | 400 | 56px | 1.16 | -0.01em | size clamp(36px, 30.1px + 1.88vw, 56px) | Informational section headings and large ruled statistics. |
| chapter | the-future | 500 | 48px | 1.16 | 0.005em | size clamp(32px, 27.4px + 1.5vw, 48px) | Product-stage chapter headings. |
| editorial-lead | the-future | 400 | 32px | 1.4 | 0.005em | size clamp(20px, 16.5px + 1.13vw, 32px) | Wide introductory paragraph under an oversized serif statement. |
| card-heading | the-future | 500 | 30px | 1.16 | 0.005em | size clamp(20px, 17.1px + 0.94vw, 30px) | Bottom-aligned titles on reveal cards and portrait cards. |
| eyebrow | tiempos | 400 | 20px | 1.24 | -0.01em | fixed | Sentence-case labels above immersive promises. |
| body | the-future | 400 | 20px | 1.4 | 0.005em | size clamp(18px, 17.4px + 0.19vw, 20px) | Product explanations, quotes' attribution and feature paragraphs. |
| feature-label | the-future | 500 | 20px | 1.4 | 0.005em | size clamp(18px, 17.4px + 0.19vw, 20px) | Short feature titles and table labels. |
| footer-link | the-future | 400 | 18px | 1.4 | 0.005em | fixed | Footer link lists. |
| footer-heading | the-future | 500 | 18px | 1.16 | 0.005em | fixed | Footer column labels. |
| action | the-future | 500 | 16px | 1.4 | 0.005em | fixed | Conversion buttons and FAQ questions. |
| small | the-future | 400 | 16px | 1.4 | 0.005em | fixed | Card details, reading-time captions and secondary notes. |
| nav | the-future | 500 | 14px | 1.4 | 0.005em | fixed | Navigation links and compact header buttons. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company introductions | mission | tiempos | 400 | 84px | 1.16 | -0.01em | size clamp(40px, 27px + 4.14vw, 84px) | Centered multi-line mission statement. |
| editorial investment openings and centered product closing calls | product-serif-hero | tiempos | 400 | 64px | 1.16 | -0.01em | size clamp(40px, 33px + 2.26vw, 64px) | Refined alternative to the default sans opening. |
| educational resource cards | article-heading | the-future | 500 | 36px | 1.16 | 0.005em | fixed | Large title in an otherwise sparse white card. |
| dark premium-product openings | glass-value | the-future | 500 | 24px | 1.16 | 0.005em | size clamp(18px, 16.3px + 0.56vw, 24px) | Primary value in a glass benefit tile. |
| contained product and company openings | small-eyebrow | tiempos | 400 | 16px | 1.24 | -0.01em | size clamp(14px, 13.4px + 0.19vw, 16px) | Restrained label over a contained hero. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Sans tracking stays slightly positive at 0.005em even at display sizes; serif tracking stays negative at -0.01em. Do not apply a generic tightly tracked grotesk system.
- Use 1.16 for display and headings, 1.4 for reading text, and 1.24 for serif eyebrows. The monumental centered proof line alone compresses to 1.08.
- Eyebrows are small serif sentence case, not uppercase micro-labels. Most headings use regular serif or medium sans; bold weights are not the hierarchy mechanism.

## Layout

**Density:** Airy: full-screen object stages and 160px chapter breathing space are balanced by tightly organized 8px and 16px text groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Feature heading to body and compact stacked content. |
| 16px | Eyebrow to heading, heading to support, and action-group gaps. |
| 20px | Horizontal separation between lead form input and action. |
| 24px | Glass-tile padding and hero grid gaps. |
| 32px | Heading-to-action separation and standard card padding. |
| 40px | Default outer container's inner side padding. |
| 48px | Editorial grid gutters; visually about 48px. |
| 64px | Footer top padding and centered closing heading-to-action spacing. |
| 80px | Section heading to feature-card row. |
| 96px | Inset invitation-panel side padding and clear space beneath floating navigation. |
| 128px | Invitation-panel vertical padding. |
| 160px | Major chapter top and bottom breathing space. |

### Containers and grids

- **Immersive content**: max width 1264px · 2 columns · gap 24px · side padding 40px. Centered within full-bleed artwork. At desktop this yields an 1184px text-and-object content span; each half is about 580px.
- **Feature triptych**: 3 columns · gap 48px. Three approximately 373px cards or feature columns across a 1216px reading area.
- **Footer grid**: 6 columns · gap 32px. Six equal link columns across an 1184px area, followed by a full-width typographic signature.
- **FAQ split**: 2 columns · gap 24px. A 5:7 split: heading and hand-drawn illustration left; approximately 695px question stack right.
- **Editorial container** (only for informational product and company pages): max width 1280px · side padding 32px. Contained product and company sections; 1216px usable width at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Action capsules | 9999px (pill) |
|  | Cards and navigation | 12px |
|  | Invitation panel | 24px |
|  | Icon discs | 50% |
| dark premium-product openings | Glass benefit tiles | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Floating controls | `0px 1px 4px 0px rgba(16,24,40,0.1), 0px 1px 2px 0px rgba(16,24,40,0.06)` | Navigation and floating utility discs only; editorial cards remain flat. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default long-form reading background.

**CSS:** `background: #f5f3ef; color: #1c1b1b`

**Observed:** Warm, untextured and edge-to-edge, with artwork allowed to dissolve into it.

**Transfer:** Separate vivid media chapters with long paper reading intervals.

#### Night stage · level 0

**Use:** Immersive opening beneath dimensional artwork.

**CSS:** `background: #080f16; color: #fcfcfc`

**Observed:** The visible field is mottled smoky blue, not a flat navy rectangle.

**Transfer:** Add the directional haze treatment described in imagery rather than using a generic dark gradient alone.

#### Dusk stage · level 0

**Use:** Warm atmospheric product chapter.

**CSS:** `background: linear-gradient(#9894a3 0%, #b3abbc 9.48%, #d6c9dc 23.03%, #f0dcef 32.44%, #f4dce4 50%, #fbdcd1 76.78%, #ffdcc4 100%); color: #1c1b1b`

**Observed:** A vertical gray-lilac-to-peach sky backs oversized dimensional terrain.

**Transfer:** Keep the sky broad, smooth and low-frequency behind a single focal object.

#### Invitation panel · level 1

**Use:** A bright editorial break within a paper canvas.

**CSS:** `background: #eee3b1; border-radius: 24px; padding: 128px 96px; max-width: 1264px`

**Observed:** Large inset panel with centered publication identity, a small moving graphic, generous invitation text and outlined action.

**Transfer:** Use one concise editorial invitation, not a cluster of small promotional tiles.

#### Bordered card · level 1

**Use:** Resources and explanatory panels.

**CSS:** `background: #ffffff; border: 1px solid #e4e2e1; border-radius: 12px; padding: 32px; box-shadow: none`

#### Light product canvas · level 0

**Only for:** informational product and company pages

**Use:** Detailed explanatory sections.

**CSS:** `background: #fcfcfc; color: #1c1b1b`

#### Premium dark canvas · level 0

**Only for:** premium metal-product campaigns

**Use:** A continuous dark alternative, including footer.

**CSS:** `background: #1c1b1b; color: #fcfcfc`

**Observed:** Charcoal carries every chapter rather than alternating back to white; metal and photography provide the color.

#### Glass benefit tile · level 1

**Only for:** dark premium-product openings

**Use:** Compact proof strip beneath hero.

**CSS:** `background: rgba(255,255,255,0.05); border-radius: 16px; padding: 24px; backdrop-filter: blur(16px); box-shadow: inset 0px -2px 12px rgba(255,255,255,0.15), inset 0px 2px 8px rgba(0,0,0,0.15)`

**Observed:** A masked diagonal edge gradient brightens opposing corners: white at 40% alpha fades to zero at the middle and returns at the far corner.

**Transfer:** Keep glass confined to this short benefit strip; do not turn all content into translucent panels.

#### Architectural stage · level 0

**Only for:** borrowing-style product stories

**Use:** Object cards and wide closing imagery.

**CSS:** `background: #d8cdc1; color: #1c1b1b`

**Observed:** Pale sand backing for silver ladders, cream steps and blue-sky apertures.

## Components

### Floating navigation

**Use:** Persistent navigation above both imagery and reading sections.

**CSS:** `height: 60px; padding: 8px 16px; background: rgba(252,252,252,0.95); backdrop-filter: blur(16px); border-radius: 12px; display: grid; column-gap: 8px; grid-template-columns: 176px 1fr auto auto; box-shadow: 0px 1px 4px 0px rgba(16,24,40,0.1), 0px 1px 2px 0px rgba(16,24,40,0.06)`

**Text style:** `nav` — the-future 500 · 14px/1.4 · tracking 0.005em

**Observed:** Floats 16px inside viewport edges, with wordmark left, horizontal menu, search, outlined login and a filled conversion pill right. Header controls are 44px high. Dark campaigns use translucent charcoal with light lettering. An announcement bar is a separate narrow rounded strip above, not part of the default menu.

**Transfer:** Keep the compact floating-window silhouette and substitute a concise product taxonomy.

### Primary button

**Use:** Default conversion on dark immersive media.

**CSS:** `background: #fcfcfc; color: #1c1b1b; border-radius: 9999px; height: 64px; padding: 20px 32px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — the-future 500 · 16px/1.4 · tracking 0.005em

**Observed:** A solid light pill sits directly below the promise or beside an email input. The light-canvas variant reverses to ink fill and near-white text; header version shrinks to 44px with 12px 16px padding and nav type.

**States:** Declared: hover background color-mix(in srgb,#fcfcfc 80%,transparent), color #1c1b1b, outline unset; dark-filled variant hover background color-mix(in srgb,#1c1b1b 80%,transparent), color #fcfcfc; active outline 0px on the link variant.

### Outline button

**Use:** Secondary conversion on paper or lighter imagery.

**CSS:** `background: rgba(252,252,252,0.2); color: #1c1b1b; border-radius: 9999px; height: 64px; padding: 20px 32px; outline: 1.5px solid #1c1b1b; outline-offset: -1.5px; backdrop-filter: blur(3px)`

**Text style:** `action` — the-future 500 · 16px/1.4 · tracking 0.005em

**Observed:** Same capsule proportions as the solid action. On dark scenes the outline and text turn near-white with an ink wash.

**States:** Declared: hover outline 1.5px solid #1c1b1b, background color-mix(in srgb,#fcfcfc 20%,transparent), color #1c1b1b; active outline 0px.

### Menu link

**Use:** Short navigation destinations and dropdown triggers.

**CSS:** `color: #1c1b1b; padding: 6px 12px; border-radius: 12px`

**Text style:** `nav` — the-future 500 · 14px/1.4 · tracking 0.005em

**Observed:** Sentence-case text and a 10px downward chevron when expandable; links remain visually light beside capsule actions.

**States:** Declared: hover background-color color-mix(in srgb,#32302f 10%,transparent); focus-visible uses the same background, a 4px outline in color-mix(in srgb,#1c1b1b 50%,transparent), and 2px outline-offset.

### Reveal card

**Use:** Image-led benefit or application chapters.

**CSS:** `width: 373px; height: 502px; border: 1px solid transparent; border-radius: 12px; position: relative; overflow: hidden`

**Text style:** `card-heading` — the-future 500 · 30px/1.16 · tracking 0.005em

**Observed:** A tall image fills the face; title and 36px circular plus sit at the bottom inside 32px padding. Reveal replaces the face with a matched-color detail panel and close control. Photography uses a black scrim darkening to 60% alpha near the base. Architectural versions use sand and dark text. Investment option variants are navy, lavender and blush with titles at the foot.

**Transfer:** Use a meaningful image or colored product-specific illustration rather than an icon floating in a generic white box.

### FAQ row

**Use:** Objection handling in a split section.

**CSS:** `border-bottom: 1px solid #32302f; padding: 32px 0px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `action` — the-future 500 · 16px/1.4 · tracking 0.005em

**Observed:** A simple question with a small plus at far right; single-line rows are about 87px high. The dark version uses a white rule. Use details/summary construction with answer content below, not separate boxed questions.

### Footer link

**Use:** Six-column footer navigation.

**CSS:** `display: inline-flex; align-items: center; padding: 6px 12px; border-radius: 12px; color: #1c1b1b`

**Text style:** `footer-link` — the-future 400 · 18px/1.4 · tracking 0.005em

**Observed:** Links sit in short lists below medium sans labels. Dark campaign variant reverses text to near-white.

**States:** Declared: hover background-color color-mix(in srgb,#32302f 10%,transparent), outline 0px; focus-visible same background plus 4px outline in color-mix(in srgb,#1c1b1b 50%,transparent), offset 2px; active outline 0px.

### Resource card

**Only for:** educational resource sections

**Use:** Sparse links to supporting reading.

**CSS:** `background: #ffffff; border: 1px solid #e4e2e1; border-radius: 12px; padding: 32px; height: 312px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `article-heading` — the-future 500 · 36px/1.16 · tracking 0.005em

**Observed:** Large title and small reading-time line at the top; a dark arrow disc sits at bottom right. No thumbnail is needed.

**States:** Declared: border transition 0.25s cubic-bezier(0.29, 0, 0.09, 1).

### Comparison panel

**Only for:** detailed product comparisons

**Use:** Feature-by-feature decision support.

**CSS:** `background: #fcfcfc; border-radius: 12px; outline: 1px solid #e4e2e1; overflow: hidden`

**Text style:** `body` — the-future 400 · 20px/1.4 · tracking 0.005em

**Observed:** Four equal columns in the light variant; row labels left, values centered, one product column filled #f1f0f0. Cells have fine shared borders and 24px padding. Dark version has three columns, warm-gray rules, a smoky diagonal gradient and a slightly brighter central column.

**Transfer:** Keep comparison prose short enough to read as a useful table rather than marketing paragraphs.

### Email capsule

**Only for:** lead-generation openings

**Use:** Inline entry paired with the opening action.

**CSS:** `height: 64px; width: 342px; border: 1px solid #94908d; border-radius: 100px; padding: 20px 52px 1px 24px; background: transparent`

**Text style:** `footer-heading` — the-future 500 · 18px/1.16 · tracking 0.005em

**Observed:** Persistent label sits inside the pill, with a 20px gap to the solid action; the pair occupies a roughly 500px row.

**Transfer:** Use only for a real short entry flow, not as a decorative pseudo-button.

### Glass value card

**Only for:** dark premium-product openings

**Use:** Four-part proof strip at the foot of the hero.

**CSS:** `background: rgba(255,255,255,0.05); border-radius: 16px; padding: 24px; backdrop-filter: blur(16px); display: flex; flex-direction: column; gap: 8px`

**Text style:** `glass-value` — the-future 500 · 24px/1.16 · tracking 0.005em

**Observed:** Four 286px-wide tiles separated by 24px. Medium value line above an 18px supporting line, with luminous diagonal edges and soft inset highlights.

## Imagery and graphics

### Illuminated object theatre

**Use:** Required visual anchor for the opening and recurring product chapters.

**Observed:** One monumental coin, matte metal card, glass-like pie sculpture or tall phone occupies the right half of a full-bleed scene. Objects have real thickness, bevels, slightly oblique perspective and restrained reflections; soft lavender pools and directional shadows establish a floor. Text remains on a calmer left half.

**Transfer:** Use a relevant three-dimensional artifact or a simple extruded symbol in metal, frosted glass or stone. Minimum acceptable version is a bevelled SVG or layered CSS object with a specular edge and soft elliptical floor shadow, not a stock icon.

**Build:** Create a right-half stage with a perspective-transformed rounded rectangle or circular disc, add a narrow offset duplicate for extrusion, a light-to-dark metallic fill, a fine bright inset rim and a soft ellipse below at about 40% object width with 24px blur. Keep the object around 40% of viewport width and leave the left text field clear.

### Directional blue haze

**Use:** Atmosphere around the opening object.

**Observed:** Blue-black at upper left becomes smoky slate-blue toward lower right, with softly mottled texture rather than a sharply defined glow.

**Transfer:** Match the cloudy tonal depth and directional light; exact stops are not essential.

**Build:** Over #080f16, layer a broad radial ellipse centered near 85% 85% in rgba(150,184,210,0.45), fading to transparent across about 70% of the stage. Add a second low-opacity blue-gray ellipse at center right with 100px blur. Overlay an SVG fractal-noise texture at low opacity, keeping the text half darkest.

### Pastel landscape stage

**Use:** Aspirational chapters and visual closing calls.

**Observed:** A sharply textured mountain rises out of a lilac-to-peach sky, with gold light on the upper ridge and deep blue-violet shadow. In a closing scene the ridge is low across the bottom, leaving the centered copy in open sky.

**Transfer:** Use a large sculptural landscape or single product-relevant form with dawn lighting; minimum acceptable is a shaded low-poly ridge with a warm lit edge, not a scenic photo tiled behind text.

**Build:** Use the Dusk stage gradient as sky. Place an SVG irregular triangular ridge across the lower or right half; use a dark shadow face, muted lilac mid-face and a warm pale-gold narrow face toward the light. Add irregular fine contour strokes clipped within the silhouette for rock texture. Preserve broad open sky around type.

### Monumental typographic signature

**Use:** Required final footer device.

**Observed:** A single serif wordmark image spans 1184px by 195px after the link grid, followed by a thin horizontal rule and small legal and language controls. It is dark on paper and reversed on the premium dark canvas.

**Transfer:** Set the new identity as one confident near-container-width typographic artwork. Keep the footprint and visual weight even if the name is shorter.

**Build:** Render the new name in a heavy high-contrast serif as SVG text or outlined vectors. Use a single line in ink or near-white, fit it proportionally within a wide shallow viewBox, then place a 1px rule underneath.

### Hand-drawn help vignette

**Use:** Human counterpoint beside the FAQ stack.

**Observed:** A compact black-outline drawing of a hand reaching toward a bell-like object sits below the heading, about 248px by 259px; linework is irregular and friendly.

**Transfer:** Use one small, high-contrast hand-drawn gesture related to help or discovery, with no colored sticker background.

**Build:** Draw a simple hand and one object as SVG paths with rounded caps, uneven 3px to 5px contours, near-white fill and ink stroke; leave abundant negative space around it.

### Architectural metaphors

**Only for:** borrowing-style product stories

**Use:** Hero, use-case cards and closing call.

**Observed:** A silver ladder reaches toward an oval ceiling opening containing saturated blue sky and white clouds. Cream steps with wood tops and a small stepladder repeat the upward-access metaphor. Sand backing, long diffuse shadows, clean studio light and no people.

**Transfer:** Invent a coherent physical metaphor for the new product and reuse its materials across the opening, cards and ending.

**Build:** Construct a pale sand floor and wall, a tilted SVG ladder with parallel silver rails and repeated horizontal rungs, and a foreshortened sky-filled ellipse near the upper edge. Add a wide low-opacity shadow under the ladder; shade rails with narrow linear highlights.

### Lifestyle and portrait photography

**Only for:** human proof, premium benefits and company pages

**Use:** Photographic cards, quote pairs and organizational stories.

**Observed:** Warm candid scenes: hands holding a phone over marble, textured clothing and a metal card, rolling luggage, glasses clinking against blue sky. Portraits are waist-up against pale office brick, smiling and naturally lit. Images fill rounded rectangles; portrait names appear at the base under a dark gradient.

**Transfer:** Show tactile real-world use and human context, with close framing and material detail. Favor editorial warmth over glossy corporate team montages.

### Icons

**Observed:** Small monochrome SVGs: 10px menu chevrons, 16px plus and utility marks, 20px search and 24px chat controls. Arrow and plus controls sit in circular or short capsule frames; most marks are filled, with occasional 2px round strokes.

**Transfer:** Use simple ink or near-white symbols and keep icon controls smaller than text conversions. Large expressive illustration belongs outside the navigation icon system.

## Section recipes

How recurring sections are built.

### First screen: Immersive promise opening

**Observed:** A 900px-tall full-bleed Night stage fills the first screen. Back to front: directional blue haze, a gold bevelled disc on the right, a left-aligned text block, then Floating navigation and bottom-right utility discs. The text spans about two fifths of the viewport in a 580px column inside Immersive content. A 20px serif eyebrow is followed after 16px by a 64px/1.16 medium sans promise, balanced into three lines. The main object occupies most of the right half and roughly two thirds of the screen height. After 32px, a 64px Email capsule and Primary button form one horizontal row. The first 900px shows the complete promise, entry and action, main object and navigation; the next editorial chapter begins below the fold. There is no separate explanatory paragraph in this opening.

**Transfer:** Make one clear outcome the headline and give the new product one sculptural artifact with enough physical detail to hold half the screen. Without a model, use the bevelled-object fallback and haze treatment. Detailed investment-like pages can instead use a contained near-white split with a 64px serif headline, body copy and 672px by 744px framed media; company introductions use an 84px centered serif statement and a wide photograph below.

**Avoid:** Do not replace the object theatre with a centered text-only SaaS masthead, a busy dashboard collage or a small thumbnail inside a card. Do not flatten the smoky light into a uniform navy fill.

**Text style:** `hero` — the-future 500 · 64px/1.16 · tracking 0.005em

### Oversized editorial interruption

**Observed:** Paper canvas with 160px vertical padding, a small 180px graphic above the statement, 128px serif text across the reading width and a 32px supporting paragraph below with 24px separation.

**Transfer:** Interrupt capability chapters with one broad idea about the new product's purpose, using typographic scale rather than another card grid.

**Text style:** `statement` — tiempos 400 · 128px/1.16 · tracking -0.01em

### Full-screen capability stage

**Observed:** A 900px media band, 160px vertical padding, chapter label and 48px medium sans headline on the left, a 72px by 52px outlined arrow capsule 32px below, and one oversized object on the right. Purple, brown, green and Dusk stage backings create distinct chapters.

**Transfer:** Give each major capability its own physical world while retaining the same left-copy/right-object construction.

**Text style:** `chapter` — the-future 500 · 48px/1.16 · tracking 0.005em

### Heading and explanation pair

**Observed:** A 56px regular serif heading with a 20px paragraph 16px below; text often spans about two thirds of the section while a control or action aligns to the right. Feature triptych begins 80px later; each feature has a 20px medium title and 8px gap to body.

**Transfer:** Use this as the core explanatory grammar between immersive scenes.

**Text style:** `heading` — tiempos 400 · 56px/1.16 · tracking -0.01em

### Ruled quantitative proof

**Observed:** Three equal columns separated by 48px gutters, each with a thin ink top rule and a 56px serif number followed by a 20px descriptor. Some product comparisons add small softly colored serif pill labels above the number.

**Transfer:** Display a few genuinely meaningful quantities with editorial restraint, not a dashboard of colored badges.

**Text style:** `heading` — tiempos 400 · 56px/1.16 · tracking -0.01em

### Reveal triptych

**Observed:** Three Reveal cards across the editorial reading width, 80px after the heading pair. Photography, architectural models or colored option faces occupy the full 500px card interior; titles and plus controls remain anchored to the bottom.

**Transfer:** Group distinct benefits or applications, with the detail panel carrying explanatory bullets rather than adding dense copy to the front.

### Bright editorial invitation

**Observed:** Invitation panel inset on paper, with a publication-like identity and small animated visual above centered 56px regular sans text. One Outline button follows after 32px.

**Transfer:** Use an editorial resource, demonstration invitation or ongoing relationship offer; retain the single broad warm panel and conversational oversized sentence.

**Text style:** `invitation` — the-future 400 · 56px/1.16 · tracking 0.005em

### Monumental proof ending

**Observed:** A centered 128px serif proof statement spans most of the reading width, with an Outline button 32px below. Beneath it, a large pale-metal emblem emerges from the paper field before the footer.

**Transfer:** Give every page a memorable large-scale ending device. Use substantiated proof or a confident product promise, then an oversized sculptural emblem of the new identity.

**Text style:** `closing-proof` — tiempos 400 · 128px/1.08 · tracking -0.01em

### FAQ and signature footer

**Observed:** FAQ split puts the 56px serif title and Hand-drawn help vignette left, with unboxed FAQ rows right. The footer follows with 64px top padding, Footer grid, Monumental typographic signature, hairline and secondary details. The default is paper; informational pages use near-white, and premium dark campaigns retain charcoal to the bottom.

**Transfer:** Finish practical questions with a recognizable typographic signature rather than a generic compact copyright bar.

**Text style:** `heading` — tiempos 400 · 56px/1.16 · tracking -0.01em

### Sky-backed product close

**Only for:** detailed product landing pages

**Observed:** A full-width 900px scene has centered 64px serif closing promise high in open sky, one 20px support line and a dark Primary button. The mountain ridge or ladder enters from the bottom. Dark premium campaigns use a plain charcoal field and a more compact centered closing block with a 64px action gap.

**Transfer:** Echo the opening's material and metaphor at a different scale; follow it with resources or FAQ as needed rather than treating it as the literal last page element.

**Text style:** `product-serif-hero` — tiempos 400 · 64px/1.16 · tracking -0.01em

### Organizational editorial mosaic

**Only for:** company and culture pages

**Observed:** A 56px serif heading leads a two-column mosaic: one 584px-wide tall stone tile opposite two stacked olive and pale-sage tiles, with 64px top insets, large serif titles, short copy and arrow discs. Warm photography is inset within the tall tile. Portrait carousel follows; later two-column directory bands alternate stone and near-white.

**Transfer:** Use this variant for human and institutional context, not as the default product-feature grid.

**Text style:** `heading` — tiempos 400 · 56px/1.16 · tracking -0.01em

### Interactive outcome stage

**Only for:** products with a useful calculator

**Observed:** A 48px sans heading includes a muted parenthetical aside. Three pill-shaped controls form a compact row above an enormous black numeric result spanning nearly the full 1216px reading width; small explanatory text and comparison controls sit below.

**Transfer:** Make the computed outcome the artwork. Scale the numeric result around 360px at a 1440px viewport, with controls subordinate and uncluttered.

**Text style:** `chapter` — the-future 500 · 48px/1.16 · tracking 0.005em

## Page flow

**Storyline:** Immersive promise → tangible capability chapters → editorial explanation and proof → renewed invitation → practical questions → monumental identity ending.

### Broad marketing discovery

1. **Promise** — Atmospheric full-screen object with a short promise and direct action.
2. **Wayfinding** — Oversized stacked serif product-category links on paper.
3. **Capability chapters** — Alternating full-screen material worlds with left-aligned sans benefits and arrow capsules.
4. **Editorial rationale** — A giant serif statement and wide supporting paragraph interrupt the media rhythm.
5. **Relationship invitation** — Butter-yellow editorial panel.
6. **Quantified proof and ending** — Monumental serif proof line, sculptural emblem, six-column footer and giant typographic signature.

**Transfer:** Use for a multi-capability offering; adapt chapter order to the story rather than reproducing a fixed sequence.

### Company credibility

1. **Purpose** — Centered serif mission followed by a wide candid photograph.
2. **Principles** — Stone band with three explanatory text columns.
3. **Independent proof** — Large serif quotation paired with a square lifestyle image.
4. **Human context** — Asymmetric editorial mosaic and portrait carousel.
5. **Institutional proof** — Alternating split directory sections.
6. **Ending** — Near-white footer with giant serif signature; no forced conversion band.

**Transfer:** Use the calmer centered opening and human proof when the reader needs institutional trust, not a product sale.

### Premium physical-product conversion

1. **Promise** — Dark hero with a close-up metal object and four glass benefit tiles.
2. **Benefits** — Warm photographic reveal triptych.
3. **Decision support** — Dark comparison table with highlighted central column.
4. **Closing call** — Centered serif promise on charcoal and one solid light pill.
5. **Objection handling and ending** — Long split FAQ followed by the fully reversed signature footer.

**Transfer:** Maintain the dark theme across the entire story when material quality is the central selling point.

### Explain a sophisticated product simply

1. **Promise** — Near-white split hero, serif headline and dramatic mountain media.
2. **Quantified proof** — Two bordered statistics then three concise benefit columns.
3. **Product explanation** — Simple allocation graphic and segmented choices.
4. **Qualification and options** — Ruled statistics, tall colored reveal cards and matching numeric summaries.
5. **Demonstration** — Spacious line chart inside a white bordered panel.
6. **Renewed invitation** — Wide dawn landscape closing call.
7. **Education and ending** — White reading cards, FAQ with help illustration, then typographic signature footer.

**Transfer:** Move from a strong outcome to increasingly specific evidence, keeping controls and explanatory graphics visually subordinate to editorial headings.

### Make an unfamiliar utility feel accessible

1. **Promise** — Sand architectural hero with ladder and open-sky metaphor.
2. **Quantified proof** — Three large serif rates with pill labels and concise feature columns.
3. **Personal demonstration** — Pill controls and monumental computed number.
4. **Decision support** — Light comparison table with one tinted product column.
5. **Applications** — Architectural reveal triptych repeating the hero's materials.
6. **Closing call** — Centered promise over a cropped ladder scene.
7. **Objection handling and ending** — Split FAQ and near-white signature footer.

**Transfer:** Use a coherent physical metaphor and a useful interactive outcome to make a complex utility feel immediate.

## Writing

Confident, plainspoken and lightly irreverent. Benefits are concrete and often numerical, while short conversational asides puncture institutional stiffness.

**Do not copy:** Do not reuse Wealthsimple's name, wordmarks, proprietary artwork, product names, monetary amounts, rates, audience counts, promotional offers, comparative claims or attributed quotations. Source examples illustrate voice only; new claims need their own substantiation.

- **Addressing the reader:** Speak directly to you and your goals; use we for the people simplifying the service. Product descriptions stay human rather than impersonal.
- **Rhythm:** Headlines range from short 4-word declarations to 10–16-word specific promises. Support usually occupies one compact paragraph. Fragments, contractions, parenthetical remarks and short punchlines coexist with precise explanations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Lead with a tangible outcome and a specific mechanism or number. | 8–16 words | “Save on fees, retire up to 47% richer”<br>“Turn investments into credit instantly, with rates as low as 3.95%” |
| Section heading | An everyday metaphor makes an unfamiliar feature accessible. | 4–8 words | “Your portfolio’s secret ingredient”<br>“Unlock first-class card perks” |
| Supporting copy | Explain the practical consequence, then add a human aside. | 1–3 sentences | “Invest in a high-performing, high-potential portfolio. Future you says thanks.” |
| Action | Short verb plus concrete destination or next step. | 2–5 words | “Open an account”<br>“Read the latest newsletter” |
| Objection or aside | Voice the reader's skepticism with a short question or parenthetical. | 3–10 words | “No FX fees? Really?”<br>“(spoiler: it's less than you'd expect)” |
| Closing promise | A short, memorable challenge or future-facing benefit. | 5–10 words | “Give your long-term goals a leg up”<br>“Break up with your bank” |

**Words and phrasing to use:** your; instantly; simple; smarter; hands-off; on your own time; future you; Win-win; not anymore

**Avoid:** revolutionary ecosystem; unlock synergies; best-in-class solutions; leverage our platform; guaranteed success; corporate jargon without explanation

**Rules:**

- Pair an ambitious outcome with a clear explanation of how it works.
- Use humor as a short aside after useful information, not as the entire message.
- Prefer concrete verbs and ordinary objects to abstract financial language.
- Explain tradeoffs, eligibility and risks in direct prose near the claim.
- Keep sentence case across headings, navigation and actions.

## Do's and Don'ts

### Do

- Keep the first-screen object comparable in visual weight to the 580px promise column.
- Use 64px medium sans for the default opening and 128px regular serif for an editorial scale change.
- Keep conversion pills 64px high and header controls 44px high.
- Leave 160px breathing space around major reading chapters.
- Use 12px card radii and reserve 24px for the large invitation panel.
- Keep the 48px editorial gutters across triptychs and wide text columns.
- Return to the opening's material language in a closing visual.
- End with a near-full-width typographic identity above a fine rule.

### Don't

- Do not make bright blue or green the button system; actions are ink, near-white or outlined.
- Do not tighten the sans into negative tracking; its 0.005em spacing is part of the friendly geometry.
- Do not set regular serif statements in bold to manufacture hierarchy.
- Do not put drop shadows under every card; elevation belongs to floating navigation and utility discs.
- Do not use the 16px glass-tile treatment as the default surface for light explanatory sections.
- Do not reduce every image to a bordered thumbnail; full-width 900px stages carry the product story.
- Do not replace 32px card padding with dense dashboard-style spacing.
- Do not carry the culture mosaic's olive palette indiscriminately into ordinary product sections.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare border-color, background-color and background transitions of 0.35s cubic-bezier(0.241,0.969,0.635,0.997).
- Navigation text declares color 0.1s ease-in; navigation backing declares background 0.2s ease-in-out.
- Reveal cards declare transform 0.6s; bordered cards declare border 0.25s cubic-bezier(0.29, 0, 0.09, 1).
- Floating controls include a pause-motion action; dimensional media and some small editorial graphics are moving content.

**Transfer:**

- Keep material scenes as coherent moving compositions, with one page-level pause control rather than independent decorative spinners.
- Use the declared card-flip and button transitions without introducing bouncy motion.

**Unknown:**

- Scene choreography, playback duration and scroll-scrub timing are unspecified.

### Responsive

**Observed:**

- Typography uses clamped viewport-relative formulas with smaller display endpoints between 24px and 56px depending on role.
- Declared width thresholds include 480px, 640px, 768px, 960px, 1024px, 1280px and 1440px.

**Transfer:**

- On narrow screens, preserve one large object and a readable promise rather than shrinking the entire desktop stage into a tiny poster.
- Stack the split hero and explanatory columns; retain the material stage and signature typography, using each recipe's clamped size.
- Let tall card sequences become horizontal browsing rows where appropriate, preserving their portrait proportions.

**Unknown:**

- Exact mobile navigation construction, breakpoint-specific stacking order and mobile stage heights are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
