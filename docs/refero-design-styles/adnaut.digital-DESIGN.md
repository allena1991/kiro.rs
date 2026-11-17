# Adnaut — luminous orbital machinery

## Overview

A charcoal digital world lit by acid yellow, with fine technical grids and glowing objects suspended above abstract architecture. Light grotesk headlines meet plain sans-serif paragraphs and uppercase monospace controls, giving the exuberant imagery an engineered frame. The mood is exploratory and optimistic rather than austere, suited to technical products and consultative services with a substantial story to tell. Content is spacious at section level and tightly organised inside outlined panels.

### Essentials

- Headlines feel weightless while punctuation lights up: Archivo 300 at 64px/1 for the opening and 56px/1 for major chapters, normal tracking, grey letters and a yellow terminal dot.
- The opening is a wide cinematic stage, not a centred slogan: 24px side gutters, a 640px headline on the left, a 304px support column on the right, and a 1392px-wide framed scene below.
- Actions look like interlocking machine parts: yellow 40px-high stepped label strips with a detached 40px arrow tile, uppercase Geistmono 600 at 16px/1; the closing action enlarges to 134px high with 56px/1.5 text.
- Colour behaves like emitted light: most of the page remains #282828 and #222222; #ffe900 is concentrated in actions, punctuation, bright proof cards and one immersive portal rather than spread across every section.
- Imagery lives on dark isometric stages: hairline diagonal grids, grainy charcoal pillars, translucent objects, white-hot centres and tapered yellow beams; every new page needs this luminous spatial language, using simple SVG prisms and a glowing sphere when bespoke 3D is unavailable.
- Rounded frames and pixel gestures coexist: 16px panel corners and 0.5px #707070 edges surround scenes, while stepped arrows and notched quote cards supply the deliberately digital silhouette.
- The ending is an inhabited dashboard: a two-column 16px-gap footer pairs modular navigation and a monumental yellow contact action with a tall grid-backed luminous object panel; retain a live-feeling visual counterweight rather than ending in links alone.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal yellow | `#ffe900` | `--color-signal` | accent, action, surface, text, link | Primary actions, terminal punctuation, portal layers, selected links and compact bright proof panels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive shadow | `#1f1d01` | `--color-portal-base` | background | Deep backing for the yellow concentric portal. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep charcoal | `#1d1d1d` | `--color-deep` | surface | Media badge backing and darker closing bands. |
| Recessed charcoal | `#222222` | `--color-panel` | surface, text | Default panel fill and ink on bright controls. |
| Charcoal canvas | `#282828` | `--color-canvas` | background, text | Main page field and dark text on yellow proof cards. |
| Panel edge | `#707070` | `--color-edge` | border | Fine panel and navigation outlines. |
| Muted grey | `#8d8d8d` | `--color-muted` | text | Secondary footer links. |
| Callout edge | `#c0c0c0` | `--color-strong-edge` | border | Brighter outlines around full-width link bands and closing calls. |
| Soft silver | `#d7d7d7` | `--color-text` | text, border | Default headings, body copy, navigation and selected outlines. |
| Bright silver | `#f2f2f2` | `--color-bright-text` | text | Brighter section leads and primary footer links. |
| White light | `#ffffff` | `--color-white` | text, accent | Small bold copy emphasis and white-hot illumination centres. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| responsibility messaging | Electric green | `#00ff1a` | `--color-green` | text, accent, action | A single responsibility-themed word and the corresponding action or illuminated pillar. |
| technical product mastheads | Ember light | `#ff5634` | `--color-ember` | accent | Broad warm glow mixed with yellow and white behind a monumental product word. |
| service selectors and technical product chapters | Electric cyan | `#3af6ff` | `--color-cyan` | surface, accent, action | Selected service tabs, feature cards, chapter markers and data illumination. |

## Typography

- **Archivo** — All display and section headings. Open, lightly drawn grotesk; headings rely on size rather than boldness. Font stack: "Archivo", Arial, sans-serif.
- **Geist** — Paragraphs, supporting copy and footer navigation. Neutral contemporary sans-serif, compact in lead paragraphs and relaxed in reading copy. Font stack: "Geist", Arial, sans-serif.
- **Geistmono** — Action labels, dock navigation, technical labels and attribution. Monospaced equipment-like lettering, usually uppercase. If unavailable, use **Geist Mono**. Use weights 400 and 600 with normal tracking. Font stack: "Geistmono", "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Archivo | 300 | 64px | 1 | normal | fixed | Default opening headline and the strongest statement cards. |
| heading-lg | Archivo | 300 | 56px | 1 | normal | fixed | Major chapter leads and large navigational cards. |
| closing-action | Geistmono | 600 | 56px | 1.5 | normal, uppercase | fixed | Monumental contact strip in the footer. |
| heading | Archivo | 300 | 48px | 1 | normal | size clamp(1.5rem, 0.75rem + 2.5vw, 3rem) | Centred process titles and secondary section leads. |
| card-heading | Archivo | 300 | 24px | 1 | normal | size clamp(1.125rem, 1rem + 0.5556vw, 1.5rem) | Compact proof-card headings. |
| band-label | Geistmono | 400 | 24px | 1.5 | normal | fixed | Uppercase lead-in above a link-band title. |
| lead | Geist | 400 | 20px | 1.1 | normal | fixed | Opening support and large compact statements inside bright cards. |
| footer-link | Geist | 400 | 20px | 1.5 | normal | fixed | Primary footer destinations. |
| body | Geist | 400 | 16px | 1.5 | normal | fixed | Reading copy and explanatory paragraphs. |
| action | Geistmono | 600 | 16px | 1 | normal, uppercase | size clamp(0.875rem, 0.8125rem + 0.3125vw, 1rem) | Stepped button labels. |
| technical-label | Geistmono | 400 | 16px | 1.5 | normal, uppercase | fixed | Attributions, step tags and service navigation. |
| dock-label | Geistmono | 400 | 14px | 1.5 | normal, uppercase | fixed | Bottom navigation and media badges. |
| small | Geist | 400 | 14px | 1.5 | normal | fixed | Secondary footer destinations and compact metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| technical chapters, company story and careers content | feature-heading | Archivo | 300 | 32px | 1 | normal | size clamp(1.25rem, 1rem + 1.1111vw, 2rem) | Technical benefit cards, role listings and prominent secondary links. |
| technical product chapters | chapter-label | Geistmono | 400 | 16px | 1.1 | normal | fixed | Short uppercase chapter labels on a vertical progress rail. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep normal tracking throughout: the light Archivo cuts and close line height already give headlines their character.
- Use sentence case for narrative headings. Yellow punctuation is a separate inline accent, not a separate floating decoration.
- Body text has more breathing room than the headline: 16px/1.5 is the reading default; 20px/1.1 is a compact lead, not the paragraph default.
- A responsibility-themed statement can colour one whole word green. Do not generalise this exception to ordinary headings.
- The technical masthead uses a near-edge-to-edge word sculpture with a visible letter field about 355px high; treat it as artwork rather than substituting the ordinary display recipe.

## Layout

**Density:** Airy between chapters, compact and modular inside panels; most major sections have 80px breathing space while repeated surfaces meet across 16px gaps.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Explains the recurring 16px, 24px, 32px, 48px and 64px horizontal gaps and padding; vertical spacing also uses exceptions.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Small footer link separation and badge padding. | fixed |
| 16px | Default grid gutter and repeated panel gap. | fixed |
| 24px | Outer page gutters, dock gaps and footer group separation. | fixed |
| 32px | Panel side padding, accordion padding and content gaps. | fixed |
| 40px | Heading-to-process-art gap. | fixed |
| 48px | Statement-card padding and media separation. | fixed |
| 64px | Footer column gap and technical chapter column separation. | fixed |
| 80px | Default major section top and bottom spacing. | clamp(2.5rem, 1.6667rem + 3.7037vw, 5rem) |
| 120px | Opening content begins below the top brand row. | fixed |
| 160px | Footer bottom breathing room. | fixed |

### Containers and grids

- **page frame**: max width 1392px · side padding 24px. At 1440px desktop width, content fills the viewport minus the side gutters; this is a broad stage, not a narrow reading column.
- **paired panels**: 2 columns · gap 16px. Equal 688px panels for editorial splits and footer; one side can contain stacked modules.
- **opening title**: max width 640px. Two-line promise on the left of the opening row.
- **opening support**: max width 304px. Compact support aligned to the lower edge of the headline at the far right.
- **reading measure**: max width 512px. Body copy in split editorial panels; narrow side essays use 368px.
- **benefit trio**: 3 columns · gap 16px. Equal dark feature cards; large icon above a bottom-aligned title.
- **technical benefits** (only for technical product chapters): 2 columns · gap 20px. Staggered cyan cards to the right of a narrow chapter title and progress rail.

## Corner radius

| Element | Radius |
| --- | --- |
| panels | 16px |
| dock and tags | 8px |
| immersive media | 24px |
| slider controls | 4px |
| portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| active quote glow | `-4px 1px 6px rgba(252,240,192,0.6)` | Warm perimeter light on the active notched testimonial card; apply as a drop-shadow to the clipped wrapper. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous page field.

**CSS:** `background: #282828; color: #d7d7d7`

#### Dark frame · level 1

**Use:** Default content panel and media perimeter.

**CSS:** `background: #222222; border: 0.5px solid #707070; border-radius: 16px; overflow: hidden`

**Observed:** The subtle fill contrast and hairline edge separate modules without ordinary elevation shadows.

**Transfer:** Frame both text and imagery with the same material.

#### Signal card · level 1

**Use:** High-energy proof or statement insert.

**CSS:** `background: #ffe900; color: #282828; border: 0.5px solid #707070; border-radius: 16px`

**Observed:** Appears as a compact stacked pair beside a larger dark statement, and as a brand block in the footer.

**Transfer:** Use short factual text or a simple growth motif; keep the surrounding canvas dark.

#### Portal chamber · level 1

**Use:** Immersive yellow spatial interlude.

**CSS:** `background: #1f1d01; border-radius: 24px; overflow: hidden`

**Observed:** Nested translucent rounded squares radiate around a dark central block; perspective grid lines converge into the depth.

**Transfer:** Use the portal to stage a short product promise rather than a conventional gradient section.

#### Cyan feature field · level 1

**Only for:** service selectors and technical product chapters

**Use:** Selected explanatory content and technical benefits.

**CSS:** `background: #3af6ff; color: #222222; border-radius: 16px`

**Observed:** Flat saturated cyan is contained by panel boundaries; it is not a wash over the whole page.

**Transfer:** Reserve for the active capability or a clearly scoped technical chapter.

#### Textured closing band · level 1

**Only for:** careers and technical product closing calls

**Use:** Compact pre-footer conversion call.

**CSS:** `background: #1d1d1d; border: 0.5px solid #c0c0c0; border-radius: 16px; padding: 50px 54px; overflow: hidden`

**Observed:** Fine noise overlays the dark field behind a left headline and right stepped action.

**Transfer:** Add a low-contrast monochrome grain overlay, not a photographic backdrop.

## Components

### Stepped primary button

**Use:** Primary conversion and chapter exploration.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 16px; height: 40px; color: #222222`

**Text style:** `action` — Geistmono 600 · 16px/1 · uppercase

**Observed:** Build the anchor as a yellow label strip plus a detached yellow arrow tile. The label has offset upper-left and lower-right steps with softly rounded joins; its middle uses 8px side padding, with 40px end shapes. The arrow tile repeats the step silhouette. Header spacing tightens to 8px. Use SVG paths or masks rather than a pill.

**Transfer:** Keep the split construction for every primary action; let label length determine strip width. Scale the same silhouette for the footer.

### Bottom navigation dock

**Use:** Persistent global destinations.

**CSS:** `display: flex; align-items: center; background: #282828; border: 0.5px solid #707070; border-radius: 8px; height: 62px; padding: 0px 24px`

**Text style:** `dock-label` — Geistmono 400 · 14px/1.5 · uppercase

**Observed:** A 785px-wide desktop dock is centred 32px above the viewport bottom. Links have 24px gaps; grouped destinations include small downward chevrons. Current destination is yellow. The top row contains only the brand mark and the primary action.

**States:** Declared: hover link color #ffe900; active outline 0px.

**Transfer:** Use a concise global destination set and preserve the floating dock placement.

### Media badge

**Use:** Entry to the opening film or visual story.

**CSS:** `background: #1d1d1d; color: #ffe900; border: 0.5px solid #ffe900; border-radius: 8px; padding: 8px; position: relative`

**Text style:** `dock-label` — Geistmono 400 · 14px/1.5 · uppercase

**Observed:** Small outlined label overlaps the centre of the media frame's top edge; the media itself is the larger interactive area.

### Capability link card

**Use:** Large chapter destinations around the portal scene.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 32px; padding: 48px 32px; background: #222222; color: #d7d7d7; border: 0.5px solid #707070; border-radius: 16px`

**Text style:** `heading-lg` — Archivo 300 · 56px/1

**Observed:** Large title on the left and a yellow stepped pixel arrow on the right. Cards are staggered between two columns and overlap the lower portion of the portal.

**States:** Declared: hover background #ffe900 and color #282828; active outline 0px.

**Transfer:** Use two or three short destinations rather than paragraphs.

### Full-width chapter link

**Use:** A substantial invitation between narrative chapters.

**CSS:** `display: flex; align-items: center; padding: 50px 54px; gap: 32px; background: #282828; color: #d7d7d7; border: 0.5px solid #c0c0c0; border-radius: 16px`

**Text style:** `heading-lg` — Archivo 300 · 56px/1

**Observed:** A band-label lead-in sits directly above the title with no vertical gap. A large pixel arrow occupies the far right. The entire 1392px-wide, 196px-high band is linked.

**States:** Declared: hover background #ffe900 and color #1d1d1d; active outline 0px.

### Notched testimonial card

**Use:** Human proof in a horizontal slider.

**CSS:** `background: #222222; width: 456px; min-height: 541px; padding: 70px 50px 96px 50px; position: relative`

**Text style:** `body` — Geist 400 · 16px/1.5

**Observed:** Rounded card silhouette steps down at the upper right, removing roughly one fifth of its width and height. Yellow oversized opening quotation mark leads the body. Uppercase technical-label attribution sits near the bottom with an 80px circular portrait to the right. A faint grid fades under the text; the active card has the active quote glow. Adjacent cards remain partially visible with 24px gaps.

**Transfer:** Use authentic short quotes, retaining the notched silhouette and sparse attribution hierarchy.

### Footer navigation panel

**Use:** Grouped destinations in the left half of the closing dashboard.

**CSS:** `display: flex; justify-content: space-between; column-gap: 64px; row-gap: 24px; padding: 32px 64px; background: #222222; border: 0.5px solid #707070; border-radius: 16px`

**Text style:** `footer-link` — Geist 400 · 20px/1.5

**Observed:** Two columns combine major destinations and expandable groups. Secondary links use small typography in muted grey with 8px gaps; main groups are 24px apart.

**States:** Declared: hover grouped destination color #ffe900; focus-visible outline rgb(77, 101, 255) solid 0.125rem with 0.125rem offset.

**Transfer:** Keep grouped links inside a single substantial module rather than distributing tiny columns across the full page.

### Cyan service tab

**Only for:** service comparison sections

**Use:** Select a capability and its explanatory panel.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 16px 24px; height: 56px; background: #3af6ff; color: #222222; border-radius: 16px`

**Text style:** `technical-label` — Geistmono 400 · 16px/1.5 · uppercase

**Observed:** Selected item is filled cyan in a 336px-wide vertical list. Unselected items are unfilled with silver type. The list is separated by 24px gaps and sits beside a larger cyan description and a dark outcome panel.

**Transfer:** Adapt the list to a small set of distinct offerings; keep selection and explanatory panel colours coupled.

### Technical benefit card

**Only for:** technical product chapters

**Use:** Readable benefit statements rather than decorative statistics.

**CSS:** `background: #3af6ff; color: #222222; border-radius: 16px; padding: 48px 64px 48px 24px`

**Text style:** `feature-heading` — Archivo 300 · 32px/1

**Observed:** Text-only cards have a 320px reading measure and vary in height with copy. The right column begins lower, creating a staggered two-column rhythm.

### Technical step accordion

**Only for:** technical product chapters

**Use:** Explain a multi-stage workflow progressively.

**CSS:** `background: #222222; border: 0.5px solid #707070; border-radius: 16px; position: relative; overflow: hidden`

**Text style:** `feature-heading` — Archivo 300 · 32px/1

**Observed:** Each toggle has 32px padding, a cyan 8px-radius step tag above the title, and a pixel chevron at upper right. The expanded panel adds body text beneath the heading and diagonal cyan light strips across the right side. Closed rows remain substantial at about 169px tall, with 16px gaps.

**Transfer:** Retain short verb tags, plain explanatory titles and one visible expanded step.

## Imagery and graphics

### Luminous isometric stage

**Use:** Signature visual language for the opening and major explanatory scenes.

**Observed:** Dark grey isometric floor lines and grainy extruded columns surround a small translucent orb or prism with a brilliant white core. Yellow light spreads in tapered beams over surrounding geometry. Scenes occupy much more area than text, often a full 1392px-wide panel; the opening scene is about 524px high. Highlights are vivid but most of each scene stays near-black.

**Transfer:** Replace the character with a product-relevant abstract object. The minimum version is an SVG isometric prism with a translucent circular shell, white light centre, yellow beam and a few charcoal extrusions; no 3D renderer is necessary.

**Build:** Use an SVG viewBox 0 0 1392 630. Draw two families of fine diagonal lines at opposing 30-degree angles with rgba(215,215,215,0.08), spaced about 64px. Add three-face charcoal prisms with subtle face-value differences and a low-opacity SVG turbulence layer. Put a 70px translucent sphere above the floor, a 20px white core with 12px blur, and a broad polygon beam fading from rgba(255,233,0,0.4) to transparent. Add a blurred floor ellipse underneath. Clip the scene to the Dark frame.

### Concentric signal portal

**Use:** Signature high-colour visual interruption accompanying a short promise or capability grouping.

**Observed:** A dark central square is surrounded by many nested yellow rounded-square layers. They become more transparent toward the outer olive darkness. Perspective lines cross the entire chamber, giving a tunnel-like depth rather than a soft flat gradient.

**Transfer:** Retain this portal device somewhere in a long landing page; a simple layered SVG is an acceptable substitute for animated spatial artwork.

**Build:** Inside a 1392px by 810px Portal chamber, centre a 475px dark square with 16px corners. Behind it stack roughly 16 rounded yellow squares from about 404px to 1606px, progressively reducing opacity from 0.8 to 0.02. Add SVG rays from the central square corners toward the outer frame and fine horizontal perspective lines. Keep the central message short and silver with one yellow keyword.

### Projected closing statement

**Use:** Signature large visual promise near a narrative transition or close.

**Observed:** A pale illuminated rectangular message plane is tilted in isometric perspective, backed by a cone of yellow light from a tiny luminous object. Grey block clusters collect at the right edge of a dark grid. The statement is part of the spatial scene rather than ordinary centred page copy.

**Transfer:** Use a concise outcome statement specific to the new product. Preserve the projected-plane device even when the statement can only be implemented as transformed live text.

**Build:** Within a wide Dark frame, draw a skewed pale yellow plane occupying the left half; back it with a larger translucent polygon beam directed from a small glowing sphere near the centre. Render a 3–4 line dark sans-serif statement on the plane with an affine SVG transform. Add low-contrast isometric blocks on the right and the same grid and grain as the Luminous isometric stage.

### Orbital footer console

**Use:** Tall visual counterweight to footer navigation.

**Observed:** A single glassy luminous object floats centrally above a small light reflection, backed by a fading diagonal grid. A compact uppercase mood caption sits above; six small coloured swatches sit below. The right panel is about 688px wide and 700px tall. Swatch selection changes the object's emitted light.

**Transfer:** Keep a central product symbol or abstract prism and a restrained row of colour controls; use the Luminous isometric stage recipe at a simpler scale rather than a static logo wall.

**Build:** Use a Dark frame with a diagonal grid fading toward the edges. Centre a 200px translucent sphere enclosing a three-face prism and white core; add a blurred floor ellipse. Place a short caption above and six compact rounded-square controls below. Pair each control with a coherent light hue and a visible selected outline.

### Technical word sculpture

**Only for:** technical product mastheads

**Use:** Alternative immersive opening for a named platform.

**Observed:** A huge lightweight dark product word spans beyond both side edges of a 1392px by 720px grainy panel. The visible letter field is about 355px high. A white centre blooms into yellow and warm ember light, while a small explanatory paragraph sits inside an open letter counter.

**Transfer:** Use the new product's short name as the oversized artwork. Preserve the contrast between enormous dark letters and a tiny central explanation; reflow the small copy separately if the name has no suitable counter.

**Build:** Layer a broad radial yellow glow and a 720px warm ember radial field blurred 300px behind the word; add a 372px white circle blurred 46px at the centre and a 419px yellow halo blurred 98px. Cover with low-opacity monochrome noise. Use thin SVG text sized to span beyond the clipped frame; tune glow stops by eye to retain a white centre and dark perimeter.

### Spatial process and culture graphics

**Only for:** process explanations and culture pages

**Use:** Explain stages or distributed participation without conventional stock photography.

**Observed:** Process stages appear as five narrow isometric towers with vertical labels, numbers on top and one illuminated accent stage. Culture uses a grey world map with small yellow vertical location lights, and a dark musical-orb scene. Responsibility messaging uses ascending grainy pillars with one green-lit column.

**Transfer:** Choose one spatial metaphor appropriate to the content: towers for stages, lit nodes for distribution, ascending columns for improvement. Keep the same dark grid, grain and sharply localised illumination.

**Build:** Build towers as SVG parallelogram tops and two shaded rectangle faces. Use narrow rotated labels for stages, with one brighter active face. For distribution, place small 4px-wide vertical yellow-to-transparent strokes over a grey map or abstract node field. For improvement, vary pillar heights and light only the final column.

### Icons

**Observed:** Pixel-stepped yellow arrows are the dominant navigational device, from compact 20px by 12px action arrows to 120px by 95px chapter arrows. Feature icons use yellow pixel-outline forms in generous square stages; chevrons are small silver stepped marks. Portraits are circular, not icon substitutes.

**Transfer:** Draw arrows and functional pictograms on a square pixel grid with consistent block increments. Keep full-colour pictograms out of the navigation; use yellow for destination arrows and silver for disclosure chevrons.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise opening

**Observed:** An 88px brand row leaves the top-left mark and top-right Stepped primary button isolated. Main content begins at 120px inside 24px gutters. A two-line display headline occupies roughly the left half, bounded to 640px; the final dot is yellow. At the far right a 304px-wide lead paragraph aligns with the headline's lower edge, leaving a deliberately broad empty interval. About 40px below, the Dark frame holds a 1392px by 524px Luminous isometric stage with the Media badge centred across its upper edge. Back to front: charcoal canvas, fine bordered stage, diagonal grid and grainy architecture, small glowing object and beam, then badge and the floating Bottom navigation dock. Within the first 900px, the entire headline, support, top action and cinematic scene are visible; the dock overlaps the lower edge. The next editorial block begins below this screen.

**Transfer:** Use a concise two-line product promise and a support statement of comparable visual length. Without bespoke media, create the SVG Luminous isometric stage with a product-shaped prism. Company-story and careers openings use paired panels with text and a bottom-anchored action opposite bright facts or a distribution graphic; service pages use a left copy column and tall right scene; technical platform pages can use the Technical word sculpture.

**Avoid:** Do not centre the headline over a small mockup, fill the broad interval with badges, or replace the scene with a white interface card.

**Text style:** `display` — Archivo 300 · 64px/1

### Asymmetric conviction cards

**Observed:** A 895px-wide, 540px-high Dark frame stands beside a 481px-wide stack of two Signal cards across a 16px gutter. The left carries a small introduction above a three-line display statement; a luminous object projects across the background. The right cards use compact heading and lead recipes.

**Transfer:** Use a brand conviction or product transformation on the left, with short proof or practical outcomes on the right.

### Spatial process chapter

**Observed:** A centred heading at 48px/1 is constrained to 768px. After 40px, a large framed isometric process diagram uses numbered towers and an illuminated stage. The section has 80px top and bottom space.

**Transfer:** Turn a real workflow into spatially differentiated stages; retain readable labels alongside the graphic.

**Text style:** `heading` — Archivo 300 · 48px/1

### Partner signal strip

**Observed:** A 48px section title introduces a horizontal row of outlined dark logo cells. Marks are monochrome light grey or white, and both ends fade into the canvas.

**Transfer:** Use verified partners or integrations. Keep marks visually equal and subordinate to the main narrative.

### Portal with overlapping destinations

**Observed:** The Portal chamber fills nearly the content width and is about 810px high. A short central promise anchors its depth. Capability link cards overlap the lower edge in staggered two-column positions, continuing over the dark isometric background.

**Transfer:** Keep the luminous portal as an experiential statement, then attach a few product chapters as tangible destinations.

### Editorial split scene

**Observed:** Two equal panels meet across 16px. Text in a Dark frame has a heading-lg lead, body copy with a 512px measure, and a Stepped primary button anchored low; the opposite panel is a full-height luminous scene about 710px tall.

**Transfer:** Use for a human, operational or differentiating story; let the scene carry atmosphere and the copy explain the practical significance.

### Technical overview with wide scene

**Observed:** A 56px or 64px heading occupies the left of an open row, with 16px body paragraphs in a narrow right column. An exploration action or a secondary 32px heading can sit beneath the lead. Below, a full-width 630–653px-high media panel shows beams, paths and illuminated architecture.

**Transfer:** Describe a capability at a high level before the technical detail. Preserve the large scene even for intangible products by visualising connections as light paths.

### Proof spotlight slider

**Observed:** A heading-lg title and luminous beam scene occupy the left, while Notched testimonial cards extend horizontally on the right. The active card catches a warm perimeter glow; two 40px yellow square arrow controls sit below.

**Transfer:** Give social proof a spotlight-like stage rather than a uniform wall of quotes.

### Projected promise interlude

**Observed:** A wide Dark frame, about 630px high, contains the Projected closing statement. It has 80px separation above and below and no ordinary paragraph beneath the artwork.

**Transfer:** Make the line a memorable summary of value rather than adding another feature list.

### Dashboard ending

**Observed:** The footer uses paired 688px columns across a 16px gap and a roughly 700px-tall content area. On the left, a yellow brand block sits beside a small dark positioning block; below are the Footer navigation panel, a shallow contact row, then a 134px-high stepped contact action with closing-action type and a separate large arrow tile. On the right, the Orbital footer console fills the height. Copyright sits about 32px below the grid, with 160px bottom breathing room. The persistent dock remains over the page.

**Transfer:** Retain both the large contact invitation and the atmospheric object console. Careers and technical pages can precede this with the Textured closing band; the shared ending still carries the strongest action.

**Text style:** `closing-action` — Geistmono 600 · 56px/1.5 · uppercase

### Service selection theatre

**Only for:** service comparison sections

**Observed:** A smaller centred heading sits above three unequal columns: a 336px vertical selector, a 683px cyan description panel and a narrow dark results card, with 16px gaps. The description uses a 48px light heading and 20px explanatory text. Results are compact bullet claims, not oversized stat numerals.

**Transfer:** Pair each selectable offering with a clear outcome, a short explanation and independently supportable proof.

### Technical chapter rail

**Only for:** technical product chapters

**Observed:** A thin vertical line with small cyan square markers sits left of the content. Uppercase chapter-label text introduces a 48px or 56px heading. Two sticky product-mode controls accompany the chapter; selected mode is cyan, inactive mode is outlined. Staggered Technical benefit cards lead into Technical step accordion rows.

**Transfer:** Use this long-form chapter structure only when there are genuinely distinct product modes and enough detail to justify progressive disclosure.

### Careers listing and answers

**Only for:** careers and recruitment pages

**Observed:** A 56px section title introduces job rows with 32px role names on the left, level and department metadata toward the right, and an uppercase apply action with arrow. A department filter is outlined with 16px corners. Later, full-width Dark frame FAQ rows have 32px toggle padding, 24px light questions and 16px body answers; one is expanded.

**Transfer:** Keep roles scannable as wide rows and answer practical objections in a separate accordion rather than shrinking them into cards.

## Page flow

**Storyline:** promise → visual explanation → conviction and proof → capability exploration → deeper differentiator → memorable outcome → contact dashboard

### Broad marketing landing page

1. **Promise** — Asymmetric headline and support above a cinematic spatial stage.
2. **Positioning** — Dark conviction statement beside compact bright proof cards.
3. **Method and credibility** — Spatial process followed by a monochrome partner strip.
4. **Capability exploration** — Yellow portal with overlapping destination cards and a full-width chapter link.
5. **Differentiation** — Paired editorial scene and a second full-width link band.
6. **Social proof** — Spotlight testimonial slider with notched cards.
7. **Outcome and closing call** — Projected statement followed by the dashboard ending.

**Transfer:** Use the luminous scene, bright proof insert and closing dashboard as identity anchors while changing the narrative order to suit the new product.

### Company story and principles

1. **Conviction** — A luminous statement panel opposite two yellow principle cards and a substantial secondary link.
2. **Enabling capability** — Heading and side essay above a wide light-path scene.
3. **Responsibility** — Editorial split with green-lit spatial artwork and a green action.
4. **Closing call** — Shared dashboard ending with navigation, monumental contact and object console.

**Transfer:** Replace internal principles with the new company's real beliefs; keep the green variant confined to responsibility messaging.

### Recruitment and culture

1. **Invitation** — Tall text panel with bottom action opposite a distribution map and a bright location statement.
2. **Opportunity discovery** — Filterable role rows with metadata and apply actions.
3. **Culture demonstration** — Wide atmospheric scene with introductory copy and an exploration action.
4. **Objection handling** — Large FAQ heading and outlined accordion rows.
5. **Closing call** — Textured recruitment band then shared dashboard ending.

**Transfer:** Balance a warm invitation with practical scannable opportunity information; keep global and location claims factual.

### Focused service landing page

1. **Outcome promise** — Breadcrumb, small gradient category tag and a 64px left headline opposite a tall isometric scene.
2. **Offering explanation** — Vertical service tabs, active cyan description and dark outcome proof.
3. **Benefits** — Three tall dark cards with yellow pixel icons and bottom-aligned 32px titles.
4. **Enabling capability** — Open heading row and a wide luminous technical scene.
5. **Outcome and closing call** — Projected statement then shared dashboard ending.

**Transfer:** Keep cyan inside the active offering theatre, not as the page-wide brand colour.

### Technical product narrative

1. **Product identity** — Oversized word sculpture over a grainy white-yellow-ember glow.
2. **Differentiation** — Framed overview with plain body copy and illuminated pillars.
3. **Capability explanation** — Mode selector, progress rail, split headline and explanation, then wide data scene.
4. **Benefits** — Staggered cyan text cards aligned to chapter markers.
5. **Workflow** — Verb-tagged technical step accordions with one expanded light-strip panel.
6. **Closing call** — Textured conversion band followed by shared dashboard ending.

**Transfer:** Use the monumental word opening and chapter rail for a flagship platform, not as the default for every short campaign.

## Writing

Confident technical optimism with a playful expedition metaphor. Headlines are buoyant and memorable; explanations become direct about processes, efficiency and outcomes.

**Do not copy:** Do not reuse Adnaut or Nebula names, logos, character artwork, partner marks, quotations, named individuals, performance percentages, proprietary claims or company-specific facts. Source examples illustrate voice only.

- **Addressing the reader:** Speak to the reader as you and your. Use we for the team and name the product when describing a concrete mechanism.
- **Rhythm:** Headlines are typically 4–10 words with purposeful line breaks; short three-part declarations can form a statement card. Support copy is one compact paragraph, while deeper technical copy uses two plain explanatory paragraphs. Uppercase belongs to controls and labels, not narrative prose.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A navigational or motion metaphor tied to the reader's desired result. | 5–10 words | “Your navigator in the Ad-Tech universe”<br>“Drive media outcomes that matter” |
| Conviction statement | Three clipped adverbs, each able to stand alone. | 1 word per beat | “Boldly. Fearlessly.”<br>“Sustainably.” |
| Chapter title | An exploratory invitation or a concrete benefit with one imaginative verb. | 4–10 words | “Decode constellations for success”<br>“Unify KPIs and amplify returns using AI-driven insights” |
| Support | State who benefits, what is enabled and why it matters. | 20–40 words | “We hire brilliant minds across the globe. Offer fully-remote jobs that give them the flexibility and autonomy to carry out their life’s best work.” |
| Primary action | Short verb-led destination or conversational contact invitation. | 2–5 words | “explore our technology”<br>“Reach out”<br>“Let's Talk” |
| Workflow tag and title | Single technical verb followed by a benefit-oriented plain-language title. | 1-word tag; 3–6-word title | “INTEGRATE”<br>“Organise the disorganised” |

**Words and phrasing to use:** navigate; explore; fuel; chart; unify; amplify; insights; calculated; outcomes; efficiency; your

**Avoid:** disrupt everything; revolutionary magic; guaranteed returns; enterprise-grade synergy; unexplained acronym chains

**Rules:**

- Choose one coherent metaphor system and attach it to concrete benefits; do not turn every noun into a space pun.
- Support imaginative headings with plain operational detail.
- Write outcome claims only when supportable; compact proof panels do not require invented percentages.
- Keep action labels destination-specific and active.
- Use sentence case in prose and let the interface apply uppercase to controls.

## Do's and Don'ts

### Do

- Keep default display text at Archivo 300 with 1 line height and normal tracking.
- Hold desktop side gutters at 24px and default panel gaps at 16px.
- Use #d7d7d7 rather than pure white for most reading text.
- Let full-width media occupy about 524–653px of height at the desktop composition.
- Keep yellow primary actions 40px high with detached arrow tiles.
- Anchor actions low in tall paired editorial panels.
- Use 0.5px #707070 edges and 16px corners for default panels.
- Give the footer action the 134px-high monumental treatment rather than repeating the small header control.

### Don't

- Do not make the default headline bold or tightly tracked; that erases the lightly engineered tone.
- Do not use black #000000 as the main canvas in place of the layered charcoal values.
- Do not replace stepped controls with fully rounded pills.
- Do not colour every panel yellow; dark framing must dominate outside the portal and selected proof inserts.
- Do not use cyan or green as interchangeable global action colours; their contexts are scoped.
- Do not use glossy floating white cards or ordinary soft drop shadows to imply elevation.
- Do not replace pixel arrows with thin generic circular arrow buttons.
- Do not inflate compact result bullets into giant statistic numerals; proof here is integrated into scenes and panels.

## Motion and responsive

### Motion

**Observed:**

- Declared: stepped button end-shapes transition clip-path over 0.4s cubic-bezier(0.23, 1, 0.32, 1).
- Declared: large destination cards and full-width link bands transition over 0.3s ease-out; footer links use 0.2s ease-out.
- Declared: portal layers have transform 5s cubic-bezier(0.661, 0.088, 0.708, 0.439) and opacity 5s linear transitions.
- The visual language includes looping cinematic media and a footer light-colour selector.

**Transfer:**

- Keep interactive shape changes tied to the stepped geometry rather than generic button scaling.
- Use slow spatial light or portal movement as atmosphere while text remains independently readable.

**Unknown:**

- Exact scroll choreography, media loop durations and the full behaviour of each colour mode are not specified.

### Responsive

**Observed:**

- Desktop layout is composed at 1440px width. Declared CSS includes major boundaries at 479px, 767px, 991px and 1439px.
- Heading and action recipes include clamped size formulas; the 80px section spacing also has a clamped formula.
- The desktop dock and some desktop-specific action instances are hidden in tablet variants.

**Transfer:**

- On narrower layouts, stack the opening support beneath its headline and preserve a full-width dark luminous stage rather than shrinking it into a tiny thumbnail.
- Collapse paired frames in reading order, keeping a meaningful scene beside or below each editorial block. Retain stepped actions and the large closing invitation at a fitting scale.
- Treat the technical word sculpture as clipped artwork with a separate readable explanation when its letter counter can no longer hold text.

**Unknown:**

- Exact mobile navigation construction, responsive media swaps and all breakpoint-specific spacing are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
