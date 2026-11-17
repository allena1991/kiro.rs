# me.sh — luminous human orbits

## Overview

A cinematic software style that makes digital organization feel human and almost celestial. Near-black stages alternate with glowing cream atmospheres, peach light and occasional prismatic edges; condensed humanist sans headlines sit above restrained serif introductions. Floating interfaces, luminous orbital diagrams and small portraits carry the imagery, with spacious storytelling surrounding much denser product views.

### Essentials

- Compact, emphatic headlines rather than giant grotesk walls: VerlagCondensed at 64px/1, weight 700 for the opening and 48px/1, weight 900 for capability statements, with positive 0.01375em tracking.
- A centered promise floats above a rising interface: dark opening, a small live-proof label, 740px-wide serif support, one luminous action and a 1232px-wide product window entering near the bottom of the first 900px.
- Actions resemble illuminated physical keys: the hero uses a 204×54px ivory inner key with 14px corners inside a 236×74px softly lit surround; navigation actions shrink to 123×32px with 8px corners.
- Color behaves like light, not flat decoration: most of the page remains black or cream, while broad diffuse gold, peach and violet atmospheres sit behind media and white edges. Solid orange is reserved for the pricing variant.
- Orbital light is a signature device: include thin elliptical paths, brilliant white nodes, blurred halos and subtle grain around a product object. Without complex artwork, use SVG ellipses and a few glowing nodes behind a real interface.
- Human proof is spatial, not a wall of boxes: circular portraits at 48–72px drift around a centered 48px heading, while connected portraits elsewhere turn proof into a constellation.
- The ending feels like closing credits: a centered proof-led call, compact 12px uppercase directory rows with dotted leaders, a hairline legal bar and a separate 298px charcoal production seal band.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pressed peach | `#ed9d5d` | `--color-active-peach` | link, action | Declared active link color. |
| Prismatic gold | `#f7b500` | `--color-glow-gold` | accent | Warm end of the prismatic action glow. |
| Prismatic cyan | `#32c5ff` | `--color-glow-cyan` | accent | Blurred button-edge light, not a solid page fill. |
| Prismatic violet | `#b620e0` | `--color-glow-violet` | accent | Middle stop of the prismatic action glow. |
| Hover peach | `#efab74` | `--color-hover-peach` | link, action | Declared hover text for conversion and footer links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-black` | background, text | Deep art fields and text on bright actions. |
| Near-black stage | `#0f0f10` | `--color-canvas-dark` | background | Default marketing canvas. |
| Dark chapter ink | `#1d1d1f` | `--color-ink` | text | Headings and feed labels over cream atmospheres. |
| Credit charcoal | `#1e1e1d` | `--color-credit-charcoal` | background | Visible production band, built with rgba(31,31,30,0.97) over black. |
| Dark hairline | `#2a2a2b` | `--color-edge-dark` | border | Visible legal separator from gray at 20% over the dark canvas. |
| Dim white | `#6f6f70` | `--color-muted-dark` | text | Visible footer text made with white at 40% over the near-black stage. |
| Warm gray copy | `#86868b` | `--color-body-gray` | text | Hero support and light-chapter body copy. |
| Cool gray copy | `#868f97` | `--color-cool-gray` | text | Supporting paragraphs on dark chapters. |
| Cream paper | `#f9f8f6` | `--color-paper` | background | Light utility-page canvas and the visual target for luminous light chapters. |
| Ivory key | `#fdfcfa` | `--color-button-ivory` | action, surface | Main hero button face. |
| Warm headline white | `#fefef7` | `--color-ivory` | text | Headlines on the dark stage. |
| White light | `#ffffff` | `--color-white` | text, surface, accent | Bright nodes, action surfaces and highlights. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Pricing orange | `#fb7232` | `--color-orange` | action, border, text, accent | Recommended plan outline, badges and conversion actions. |
| pricing and download pages | Utility ink | `#1f1f1f` | `--color-utility-ink` | text | Text on pricing and download pages. |
| pricing and download pages | Muted paper ink | `#7f7e7e` | `--color-muted-light` | text | Ink at 56% over cream for utility support copy. |
| dark product launch pages | Soft white copy | `#b3b3b3` | `--color-body-on-black` | text | White at 70% over black for launch-page body copy. |
| pricing pages | Paper edge | `#eceae8` | `--color-edge-light` | border | Thin outlines on light plan cards. |

## Typography

- **Verlag** — Paragraphs, controls, navigation and small uppercase markings. Humanist geometric sans with friendly open forms rather than a severe neo-grotesk. If unavailable, use **Lato**. Use 400, 600 and 700; preserve the open spacing of small capitals. Font stack: "Verlag", "Lato", system-ui, sans-serif.
- **VerlagCondensed** — Main promise and chapter headlines. Narrow humanist sans with emphatic rounded strokes and compact word shapes. If unavailable, use **Barlow Condensed**. Use 700 and 900; do not replace with an ordinary-width sans. Font stack: "VerlagCondensed", "Barlow Condensed", sans-serif.
- **ChronicleTextG1Roman** — Editorial opening support. Bookish text serif, bringing warmth to an otherwise technological scene. If unavailable, use **IBM Plex Serif**. Font stack: "ChronicleTextG1Roman", "IBM Plex Serif", serif.
- **ChronicleCondensed** (only for pricing and data-story pages) — Plan prices and large data numerals. Narrow high-contrast serif with elegant, tall figures. If unavailable, use **Bodoni Moda**. Use the condensed width axis where available; regular 400 for figures. Font stack: "ChronicleCondensed", "Bodoni Moda", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | VerlagCondensed | 700 | 64px | 1 | 0.01375em | Centered opening promise with a subtle white bloom. |
| heading | VerlagCondensed | 900 | 48px | 1 | 0.01375em | Capability chapters, proof headings and the closing claim. |
| intro-serif | ChronicleTextG1Roman | 400 | 22px | 34px | normal | Two-line opening explanation. |
| body | Verlag | 400 | 20px | 1.4 | normal | Capability paragraphs and dark closing support. |
| hero-action | Verlag | 600 | 18px | 1 | 0.0556em, uppercase | Main illuminated hero key. |
| action | Verlag | 600 | 16px | 1 | 0.0625em, uppercase | Closing conversion key. |
| small-label | Verlag | 600 | 12px | 1 | 0.083em, uppercase | Header action labels and footer directory headings. |
| nav | Verlag | 700 | 12px | 27px | 0.083em, uppercase | Navigation links. |
| footer-link | Verlag | 700 | 12px | 1 | 0.083em, uppercase | Dim directory and legal links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| immersive data-story pages | data-year | ChronicleCondensed | 700 | 88px | 1 | normal | Year marker centered over the data field. |
| immersive data-story pages | data-number | ChronicleCondensed | 400 | 81px | 1 | normal | Large report totals and coordinates. |
| pricing pages | price | ChronicleCondensed | 400 | 56px | 1 | normal | Plan price or short price substitute. |
| pricing pages | stat | ChronicleCondensed | 400 | 56px | 0.75 | normal | Large figures aligned to compact explanatory text in a horizontal strip. |
| pricing and download pages | utility-title | VerlagCondensed | 700 | 48px | 56px | 0.0138em | Centered utility-page introduction. |
| pricing and download pages | utility-heading | VerlagCondensed | 700 | 40px | 42px | 0.0165em | Utility chapters and FAQ title. |
| dark product launch pages | launch-card-heading | Verlag | 700 | 28px | 36px | 0.0143em | Benefit titles inside dark illustrated cards. |
| pricing and download pages | utility-body | Verlag | 400 | 20px | 1.3 | normal | Support paragraphs on the light utility canvas. |
| download pages | download-label | Verlag | 600 | 18px | 1 | 0.008em | Platform name on download tiles. |
| dark product launch pages | launch-body | Verlag | 400 | 18px | 1.5 | normal | Longer launch-page explanations. |
| pricing and download pages | compact-body | Verlag | 400 | 16px | 1 | normal | FAQ questions and compatibility lines. |
| immersive data-story pages | data-label | Verlag | 700 | 15px | 1 | 0.133em, uppercase | Ruled metric headers. |

**Notes:**

- Large condensed headings keep positive tracking; do not apply the negative tracking common to oversized grotesk landing pages.
- Use the serif for the opening explanation, not every paragraph. Ordinary chapter support returns to the humanist sans.
- Keep uppercase typography for navigation, controls and markings; headlines remain sentence case. Condensed serif numerals are a scoped utility and reporting contrast, not the default hero face.

## Layout

**Density:** Airy, with long atmospheric transitions and relatively compact controls and product interiors.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 6px | Platform label to compatibility line. | fixed |
| 9.6px | Inline footer links and slash separators. | fixed |
| 12px | Card content gaps and small labels. | fixed |
| 16px | Compact grid gaps and control side padding. | fixed |
| 24px | Heading-to-body gap, navigation gaps and plan-card side padding. | fixed |
| 32px | Pricing columns and paired download tiles. | fixed |
| 56px | Body-to-secondary-action breathing room. | fixed |
| 64px | Hero support to main action and closing support to action. | fixed |
| 104px | Desktop marketing-stage side inset. | max(5vw, -616px + 50vw) |
| 150px | Footer directory lead-in. | fixed |

### Containers and grids

- **stage**: max width 1440px · side padding 104px. Full cinematic stage; art can extend past its edge while text stays inset.
- **content**: max width 1160px · side padding 0px. Centered navigation alignment, directory, legal bar and utility content.
- **hero-copy**: max width 740px. Centered serif support beneath the main promise.
- **chapter-copy**: max width 480px. Short left- or right-aligned capability explanation beside oversized art.
- **pricing-grid** (only for pricing pages): max width 1248px · 4 columns · gap 32px. Four equal plan columns; feature lists extend below the short raised price heads.
- **download-grid** (only for download pages): max width 744px · 2 columns · gap 32px · side padding 12px. Phone demonstration alongside a 360px action column.
- **launch-grid** (only for dark product launch pages): max width 1138px · 2 columns · gap 35px. Two tall illustrated benefits with reversed image/text order.
- **data-grid** (only for immersive data-story pages): 3 columns · gap 36px · side padding 36px. Three 432px desktop columns for totals, growth sculpture and activity map.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | hero key | 14px |
|  | hero key surround | 24px |
|  | navigation action | 8px |
|  | cards and navigation tray | 16px |
|  | portraits | 50% |
| product demonstrations | phone corners | 36px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | key bloom | `0px 0px 4px 1px rgba(255,255,255,0.98)` | Fine luminous rim around the main ivory key. |
| pricing pages | recommended plan | `0px 0px 0px 3px rgba(251,114,50,0.24)` | Soft emphasis outside the orange plan border. |

### Surfaces

#### Dark stage · level 0

**Use:** Default marketing background.

**CSS:** `background: #0f0f10`

**Observed:** Near-black rather than flat charcoal; grain, pollen-like lights and glows live on separate layers.

**Transfer:** Keep a large dark surround around the promise and art.

#### Luminous paper · level 0

**Use:** Bright capability chapters and utility pages.

**CSS:** `background: #f9f8f6; color: #1d1d1f`

**Observed:** Cream rather than pure white, with fine paper-like noise. Marketing chapters admit broad warm edge illumination.

**Transfer:** Let atmospheric color fade into the canvas, not end at a card boundary.

#### Glass tray · level 2

**Use:** Floating central navigation.

**CSS:** `background: linear-gradient(rgba(255,255,255,0.12) 10%, rgba(255,255,255,0) 86%) rgba(255,255,255,0.03); border-radius: 16px; backdrop-filter: blur(16px) saturate(1.5)`

**Observed:** Soft top reflection over translucent dark material; on cream it reads as a milky translucent tray.

**Transfer:** Reserve glass for floating controls, not every content block.

#### Production band · level 0

**Use:** Distinct final credit panel after the footer.

**CSS:** `background: rgba(31,31,30,0.97); height: 298px; display: flex; align-items: center; justify-content: center`

**Observed:** A grainy charcoal panel holds a small centered studio-style seal, with short uppercase words above and below a wireframe emblem.

**Transfer:** Make an original maker or product seal using simple linework and restrained lettering.

#### Illustrated glass card · level 1

**Only for:** dark product launch pages

**Use:** Tall benefit cards backed by colored illustration.

**CSS:** `background: rgba(43,43,43,0.2); border: 1px solid rgba(151,151,151,0.16); border-radius: 16px; backdrop-filter: blur(20px) brightness(1.2)`

**Observed:** Art occupies about half the tall card; subdued violet and amber light unifies the pair.

**Transfer:** Use a substantial visual metaphor with benefit text, not an icon-only feature tile.

#### Pearl card · level 1

**Only for:** pricing and download pages

**Use:** Raised light action and price surfaces.

**CSS:** `background: linear-gradient(#ffffff, rgba(255,255,255,0.5)) rgba(149,149,149,0.06); border: 1px solid #eceae8; border-radius: 16px; box-shadow: 0px 4px 8px -2px rgba(165,160,152,0.16), 0px -10px 6px inset rgba(255,255,255,0.5), 0px -16px 24px inset rgba(255,255,255,0.24)`

**Observed:** White top face, translucent lower edge and inset reflections create a porcelain-glass material.

**Transfer:** Keep the lower edge luminous and the exterior shadow soft.

## Components

### Floating navigation

**Use:** Persistent orientation over changing scenes.

**CSS:** `position: fixed; top: 24px; height: 48px; padding: 0px 24px; border-radius: 16px; display: flex; align-items: center; gap: 24px; z-index: 10`

**Text style:** `nav` — Verlag 700 · 12px/27px · tracking 0.083em · uppercase

**Observed:** A centered Glass tray separates itself from the left wordmark and right authentication/conversion controls. Links rest at 64% opacity.

**States:** Declared: hover opacity 1 and white text; focus-visible unknown.

**Transfer:** Use short destination labels and keep the center tray visually independent.

### Primary key

**Use:** Dominant opening action.

**CSS:** `background: #fdfcfa; color: #000000; height: 54px; padding: 0px 27px; border-radius: 14px; box-shadow: 0px 0px 4px 1px rgba(255,255,255,0.98); display: inline-flex; align-items: center`

**Text style:** `hero-action` — Verlag 600 · 18px/1 · tracking 0.0556em · uppercase

**Observed:** The ivory face is nested in a wider transparent illuminated surround. Prismatic edge light remains softer than the white face.

**States:** Declared: hover color #efab74; focus-visible unknown; active color #ed9d5d.

**Transfer:** Let label length set width; preserve the face and surround proportions.

### Compact header key

**Use:** Persistent conversion action.

**CSS:** `height: 32px; width: 123px; border-radius: 8px; background: rgba(255,255,255,0.655); display: inline-flex; align-items: center; justify-content: center`

**Text style:** `small-label` — Verlag 600 · 12px/1 · tracking 0.083em · uppercase

**Observed:** Paired with a less prominent sign-in control; its face adapts between bright and dark as the chapter changes.

**Transfer:** Use the same illuminated-key family without enlarging the header.

### Closing key

**Use:** Final marketing conversion.

**CSS:** `background: #ffffff; color: #000000; border-radius: 16px; padding: 18px 24px; height: 52px; display: inline-flex; align-items: center`

**Text style:** `action` — Verlag 600 · 16px/1 · tracking 0.0625em · uppercase

**Observed:** A simpler white illuminated key beneath the closing support. The pricing variant uses orange and a trailing arrow.

### Directory footer

**Use:** Compact destination index and legal closure.

**CSS:** `max-width: 1160px; margin: 0px auto; padding: 23px 0px 56px; border-top: 1px solid rgba(151,151,151,0.2); display: grid; grid-template-columns: 1fr auto 1fr; gap: 16px`

**Text style:** `footer-link` — Verlag 700 · 12px/1 · tracking 0.083em · uppercase

**Observed:** Above the legal bar, three horizontal directory rows put bright category labels left and dim slash-separated links right, joined by dotted leaders. Copyright sits left, legal links center and tiny social tiles right.

**States:** Declared: hover link color #efab74; focus-visible unknown; active color #ed9d5d.

**Transfer:** Keep a directory-like rhythm rather than tall conventional footer columns.

### Plan head

**Only for:** pricing pages

**Use:** Price and action at the top of each plan column.

**CSS:** `background: linear-gradient(#ffffff, rgba(255,255,255,0.5)) rgba(149,149,149,0.06); border: 1px solid #eceae8; border-radius: 16px; padding: 22px 24px 24px; display: flex; flex-direction: column; justify-content: space-between; gap: 12px`

**Text style:** `price` — ChronicleCondensed 400 · 56px/1

**Observed:** Small uppercase plan label, large condensed serif price with small billing suffix, then a 44px outlined action. Checkmarked feature lists sit outside the raised head. The recommended plan adds an orange border, a soft 3px orange ring, a top badge and orange action.

**Transfer:** Highlight one plan only; preserve open feature lists below the short pearl heads.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling beside a separate chapter heading.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 12px; padding: 19px 0px; margin-left: 28px`

**Text style:** `compact-body` — Verlag 400 · 16px/1

**Observed:** A single text line and an 18px plus icon occupy a 56px row; questions are stacked in a 682px column.

**Transfer:** Keep questions plain and compact; do not turn them into elevated cards.

### Download tile

**Only for:** download pages

**Use:** Platform-specific installation action.

**CSS:** `display: grid; grid-template-columns: 64px auto; align-items: center; gap: 18px; height: 100px; padding: 0px 20px; border-radius: 16px; background: linear-gradient(#ffffff 0%, rgba(255,255,255,0.24) 100%) rgba(149,149,149,0.12); box-shadow: 0px 0px 0px 0.5px rgba(0,0,0,0.06), 0px 1px 3px rgba(0,0,0,0.06), 0px 7px 16px rgba(0,0,0,0.03), 0px 39px 79px rgba(0,0,0,0.02), 0px -5px 6px inset rgba(255,255,255,0.5), 0px -8px 24px inset rgba(255,255,255,0.24)`

**Text style:** `download-label` — Verlag 600 · 18px/1 · tracking 0.008em

**Observed:** A glossy platform medallion precedes a two-line label/compatibility group. Paired desktop tiles become stacked mobile-store tiles. The final dark-device chapter uses a black translucent version.

**States:** Declared: hover translateY(-2px) and color #efab74; focus-visible unknown; active color #ed9d5d.

### Ruled data metric

**Only for:** immersive data-story pages

**Use:** Large technical totals on an atmospheric dashboard.

**CSS:** `border-bottom: 1px solid rgba(255,255,255,0.24); padding-bottom: 12px; margin-bottom: 6px; color: rgba(255,255,255,0.8)`

**Text style:** `data-label` — Verlag 700 · 15px/1 · tracking 0.133em · uppercase

**Observed:** The ruled uppercase heading sits above an 81px condensed serif total and a much smaller uppercase explanation. Three columns mix totals with a growth sculpture and map.

**Transfer:** Use actual measurable totals and generous vertical intervals, not a standard KPI-card grid.

## Imagery and graphics

### Orbital light and grain

**Use:** Signature atmospheric layer around the opening object and capability art.

**Observed:** Thin refractive ellipses sweep beyond the viewport, dotted with white points and blown-out stars. Light changes from black/teal to cream/gold and pink-violet at the edges; fine grain prevents a sterile gradient appearance.

**Transfer:** Stage a real product object within the light field. The minimum version is an SVG orbit system with a few white nodes and a grain overlay, not a generic gradient blob.

**Build:** Draw 3–5 oversized SVG ellipses with 1px strokes, tilted at different shallow angles, partly outside the stage. Duplicate paths beneath with 6–20px blur and low-opacity cyan, peach and gold strokes. Add 4–12px white nodes with 20–60px soft halos, one brighter 40–70px central node, broad blurred radial lights behind them and a low-opacity monochrome noise layer. Keep exact glow stops subordinate to the soft luminous effect.

### Floating product windows

**Use:** Hero and capability demonstrations.

**Observed:** Real, dense interfaces remain crisp inside rounded frames. A dark desktop window rises from the opening's lower edge; a tall cream phone-like feed floats beside short text. Light-platform demonstrations use a perspective desktop panel over a softly reflected blue-green atmosphere.

**Transfer:** Show a coherent real workflow at useful scale. With no finished interface, construct one believable task view rather than a blank display.

**Build:** Use a rounded interface panel with a faint edge and soft shadow; for the light desktop variant place a larger blue-toned backing plane behind it, apply a mild perspective tilt to both, and add a broad blurred reflection underneath.

### Connected human constellation

**Use:** Collective-value chapter and human proof.

**Observed:** Circular face cutouts with hot white rims and warm halos connect through thin luminous lines against black. Smaller glass name tags float nearby; faint background constellations make the main network feel deep.

**Transfer:** Use legitimate people, product objects or meaningful entities as nodes. Without portraits, use original circular object thumbnails; retain the connected luminous structure.

**Build:** Position circular nodes of varied sizes on an SVG graph. Layer 1px white connector paths over broad low-opacity blurred copies; apply warm and cool drop shadows to white-rimmed nodes. Add a sparse second network at low opacity and a few translucent 12px-radius caption tags.

### Orbiting proof portraits

**Use:** Centered social proof interlude.

**Observed:** A bright cream center supports a dark condensed headline. Small circular portraits and blue review-source medallions orbit at different radii while gold and charcoal haze darkens the perimeter.

**Transfer:** Surround a short trust statement with genuine reviewer faces or original proof symbols instead of boxing each testimonial.

**Build:** Place 8–10 circles at unequal angular positions around a central clear text area. Use 48–72px diameters, several orbit radii, a cream radial center and a soft darker outer vignette.

### Illustrated launch metaphors

**Only for:** dark product launch pages

**Use:** Benefit pair and video introduction.

**Observed:** Translucent green lily-pad-like logo discs cluster around an iridescent flower on one card; the other uses a glowing amber sunset reflected across a dark horizon. A wide rounded video poster uses deliberately defocused blue-gray city photography and a white play disc.

**Transfer:** Create two restrained metaphor illustrations related to the new benefit, keeping their glassy or luminous material and alternating image/text placement.

**Build:** For a minimum geometric treatment, layer translucent radial-gradient discs around a central faceted rosette; pair with an orange-to-gold circular light clipped by a horizontal horizon and blurred flattened reflection. Fade both into black.

### Particle data field

**Only for:** immersive data-story pages

**Use:** Full-screen history and final reporting dashboard.

**Observed:** Deep navy spatial dust and cyan dotted wave lines surround serif years. The ending combines blue-green irregular particle spheres at increasing scale with a fine dot-map and oversized coordinates.

**Transfer:** Represent genuine growth or cumulative activity with particle density and object size, retaining a technical observatory tone.

**Build:** Use an SVG or canvas field of low-opacity cyan points on a black-to-navy radial light. Distort dot rows with layered sine waves; for growth forms distribute points on displaced spheres, tint cyan and lime and scale each sphere by the chosen metric. A simpler acceptable form is a set of irregular dotted SVG discs beside ruled totals.

### Spatial device finale

**Only for:** download pages with a spatial-computing product

**Use:** Final platform chapter before the legal and production bands.

**Observed:** The cream catalog drops into black with a large glossy visor silhouette and cool blue halo, then centered white chapter text and a dark download tile.

**Transfer:** Use a polished silhouette of the relevant device rather than inserting unrelated headset imagery.

**Build:** Back a dark reflective device illustration with a large blue radial glow, blurred 50px. Mask reflections inside the device shape and fade the scene into black before the footer.

### Icons

**Observed:** Feature selectors use 24px dark outline/mixed icons with roughly 2px round strokes. Secondary chevrons use 20px strokes; FAQ plus signs are 18px with 1.5px round strokes. Footer social glyphs are 16px inside tiny rounded squares.

**Transfer:** Prefer simple rounded outline icons for actions and restrained solid glyphs for platform marks; use white over illuminated art and dark ink on paper.

## Section recipes

How recurring sections are built.

### First screen: Orbital product opening

**Observed:** A small wordmark sits left, Floating navigation centers above the scene, and compact actions sit right. Back to front: Dark stage, grain and diffuse lights, orbital arcs and stars, centered proof counter, headline and serif explanation, Primary key, then a large crisp desktop interface. The 64px condensed promise spans one centered line at desktop, with a changing final phrase and subtle white bloom. The serif support occupies 740px and two lines, separated from the heading by 36px; the action follows after 64px. Within the first 900px the whole promise, support, key and upper part of the 1232px-wide interface are visible; the interface begins around 727px and continues below the fold. Arcs occupy the lower third rather than competing with the headline.

**Transfer:** Use a short outcome statement, a small truthful proof marking and one main action. Build the orbit field around an original workflow panel if no cinematic media exists. Utility pages instead open on cream with a centered title and plans or a floating desktop demonstration; a dedicated launch can use a delicate serif product logotype above a dark demo, while a data story opens with a year and cumulative total in a particle field.

**Avoid:** Do not replace the centered narrow headline with a huge left-aligned grotesk, put the entire interface above the fold, or crowd the stage with multiple equally bright calls.

**Text style:** `display` — VerlagCondensed 700 · 64px/1 · tracking 0.01375em

### Luminous capability split

**Observed:** Luminous paper carries a 480px copy column and an oversized product view or orbital object. Heading and body are separated by 24px. A feed demonstration pairs a 360px-wide tall UI with a vertical list of nine 48px selector rows; the integration chapter reverses the balance, with a huge orbit entering from the left and a right-aligned copy block.

**Transfer:** Explain one outcome beside one substantial demonstration; use selectors only when they change or clarify the displayed task.

**Text style:** `heading` — VerlagCondensed 900 · 48px/1 · tracking 0.01375em

### Collective constellation

**Observed:** A two-line centered heading on Dark stage leads a centered paragraph, a warm secondary link and Connected human constellation art extending beyond the lower edges. The art is much larger than the text and shows both bright foreground clusters and faint distant connections.

**Transfer:** Translate individual value into shared value using real entities in a connected diagram, without requiring the original product's subject matter.

**Text style:** `heading` — VerlagCondensed 900 · 48px/1 · tracking 0.01375em

### Human proof halo

**Observed:** Orbiting proof portraits encircle a centered dark heading on a luminous cream center. A quiet uppercase customer-logo line precedes this broader proof region; monochrome press marks and three compact award treatments follow it.

**Transfer:** Use different proof forms at distinct scales: organization marks, individual voices and independent recognition. Only include genuine proof.

**Text style:** `heading` — VerlagCondensed 900 · 48px/1 · tracking 0.01375em

### Credit-style closing

**Observed:** A centered 48px condensed proof claim, 448px-wide support and Closing key finish the narrative on Dark stage. Directory footer adds dotted-leader rows and the legal bar; Production band sits below it as a visibly separate charcoal ending. Launch pages simplify this to a centered two-line invitation, early-access key and legal bar without the production band.

**Transfer:** Close with a defensible outcome or proof claim, then a single action and an original credit-seal treatment. Use the simplified ending for focused launches.

**Text style:** `heading` — VerlagCondensed 900 · 48px/1 · tracking 0.01375em

### Light comparison and objections

**Only for:** pricing pages

**Observed:** A centered utility title and compact support introduce a small billing switch and four Plan heads. Features remain in open columns below. A subdued horizontal strip pairs 56px serif figures with compact explanation; a left FAQ title faces the FAQ row stack at a 150px gap. The page ends with a centered free-start call, orange key, legal bar and Production band.

**Transfer:** Make comparison factual, emphasize one plan and answer transaction concerns before repeating the action.

**Text style:** `utility-title` — VerlagCondensed 700 · 48px/56px · tracking 0.0138em

### Platform catalog

**Only for:** download pages

**Observed:** A floating perspective desktop scene opens above a centered utility title, support and paired Download tiles. A phone scene sits left of mobile-store actions, followed by a compact browser-extension chapter, a centered web introduction and a 1264px-wide browser product frame. Spatial device finale changes to black before the final dark download action, legal bar and Production band.

**Transfer:** Group by how people use the product; use compatibility sublines and real platform-specific actions rather than repeating a generic CTA.

**Text style:** `utility-heading` — VerlagCondensed 700 · 40px/42px · tracking 0.0165em

### Illustrated launch explanation

**Only for:** dark product launch pages

**Observed:** A restrained introduction leads a 1138px-wide rounded video poster. Two Illustrated glass cards follow, each about 552px wide and 679px tall, separated by 35px. One puts art first and text below; the other reverses the order with 60px text insets.

**Transfer:** Use the video to establish the idea and the paired illustrated benefits to explain it; preserve the asymmetry inside equal outer cards.

**Text style:** `launch-card-heading` — Verlag 700 · 28px/36px · tracking 0.0143em

### Immersive history to dashboard

**Only for:** immersive data-story pages

**Observed:** A full-screen particle field frames a centered 88px serif year, uppercase descriptor and spaced cumulative count. Scroll-driven history resolves into three reporting columns with 81px serif totals, a growth sculpture, dot-map and large coordinates. Ruled metric labels and a small outlined methodology/anonymization panel replace sales actions; the ending is the shared legal bar over navy.

**Transfer:** Let a time-based story culminate in current measurable data and methodology, rather than inserting a standard conversion block.

**Text style:** `data-number` — ChronicleCondensed 400 · 81px/1

## Page flow

**Storyline:** Outcome promise → tangible product experience → capability or value chapters → credible proof → focused next step → credit-like closure.

### Broad product marketing landing page

1. **Promise** — Centered condensed outcome, serif support, proof counter and luminous key over an orbital product stage.
2. **Product demonstration** — Large dark interface becomes bright feed and integration scenes.
3. **Capability expansion** — Connected entities visualize collective value.
4. **Social proof** — Organization marks, orbiting portraits, press and compact awards.
5. **Closing call** — Proof-led headline and one white action.
6. **Closure** — Dotted directory, legal strip and separate maker-seal band.

**Transfer:** Alternate intimate product detail with large atmospheric diagrams; let genuine proof determine the content and number of chapters.

### Focused new-product launch

1. **Promise** — Serif product logotype, single-line explanation, early-access key and dark prompt demonstration.
2. **Explanation** — Short introduction and wide cinematic video.
3. **Benefits** — Two tall illustrated glass cards.
4. **Closing call** — Condensed invitation, small early-access key and minimal legal footer.

**Transfer:** Keep this variant entirely dark and more concentrated than a general brand landing page.

### Purchase comparison

1. **Framing** — Centered investment-oriented title and concise upgrade explanation.
2. **Pricing** — Billing switch, four raised plan heads and open checkmark lists.
3. **Quantified proof** — Three serif-number proof pairs in a soft strip.
4. **Objection handling** — Split heading and compact question rows.
5. **Closing call** — Free-start invitation, orange key, legal footer and production seal.

**Transfer:** Use the cream utility theme and assign orange only to commercial emphasis.

### Immersive impact report

1. **Historical hook** — A year and cumulative count inside a full-screen particle field.
2. **Progression** — Scroll-linked growth through time.
3. **Quantified proof** — Totals, increasing particle forms, activity map and coordinates.
4. **Methodology and closure** — Outlined methodology note and legal bar rather than sales CTA.

**Transfer:** Adapt time and measurement dimensions to real activity; retain the observatory visual language.

### Platform download hub

1. **Product demonstration** — Floating desktop display above installation explanation.
2. **Primary action** — Paired platform download tiles and a quieter web alternative.
3. **Availability** — Phone/store split, browser extensions and full-width web product view.
4. **Specialized platform** — Dark spatial-device showcase and matching dark download tile.
5. **Closure** — Legal bar and production seal.

**Transfer:** Organize by device context and make each action specific to its destination.

## Writing

Warmly confident, practical and human. Emotional outcomes are stated plainly, then grounded in concrete actions and familiar moments rather than technical spectacle.

**Do not copy:** Do not reuse Mesh or Nexus names, logotypes, Automattic production artwork, customer marks, people, quotations, awards, usage totals, savings claims or platform requirements. Substitute verified material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; name the product as the helpful actor. Use we sparingly and avoid an institutional narrator.
- **Rhythm:** Headlines are compact outcome statements, often four to eight words. Support alternates short fragments with two or three clear explanatory sentences; parallel clauses supply momentum.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the complete outcome in a short human phrase. | 4–8 words | “Every relationship, top of mind.” |
| Capability headline | A direct benefit, often with a reassuring finality. | 4–7 words | “Never miss what matters.”<br>“Your network, finally under control.” |
| Support | Concrete tasks first, then the emotional payoff; vary fragments and full sentences. | 2–4 short sentences | “Every email, every meeting, every connection. Mesh captures it all without you lifting a finger.” |
| Commercial framing | Make the spend about the outcome, not the billing mechanism. | 4–6 words | “Invest in better relationships” |
| Action | Simple imperative plus destination or access model. | 2–5 words | “Get Mesh Free”<br>“Get Early Access”<br>“View all integrations” |
| Utility description | Explain where and how the product is used in one straightforward sentence. | 12–24 words | “Use the Mesh web app on any computer in your preferred modern web browser.” |

**Words and phrasing to use:** every; your; finally; automatically; remember; moments; better; without lifting a finger; found in seconds

**Avoid:** synergize; disruptive ecosystem; 10x everything; crush it; unprecedented paradigm

**Rules:**

- Lead with the user's result before naming a mechanism.
- Follow abstract value with specific tasks or recognizable situations.
- Use parallel clauses for breadth and a short concluding sentence for reassurance.
- Make utility and compatibility copy factual, not poetic.
- Keep interface labels short enough for the small uppercase control system.

## Do's and Don'ts

### Do

- Keep the main promise at 64px/1 in a condensed face, with 0.01375em positive tracking.
- Use 22px/34px serif support only at the editorial opening.
- Let a large 1232px interface rise from the first screen rather than shrinking it into a decorative thumbnail.
- Use 24px between capability heading and 20px/28px body copy.
- Preserve 14px hero-key corners and 8px compact-header corners as different scales of the same object.
- Include luminous orbital linework and fine grain even when replacing complex art with SVG.
- Keep proof portraits circular and varied at 48–72px around a central claim.
- End a broad marketing story with a compact directory and a separate 298px maker-credit band.

### Don't

- Do not set every heading in an ordinary-width sans; the condensed 48px and 64px forms carry the brand character.
- Do not tighten headline tracking below zero; these headlines use positive spacing.
- Do not make all actions pills; the default key is a rounded rectangle, not a capsule.
- Do not use #fb7232 as the default marketing canvas; it belongs to commercial emphasis.
- Do not apply the glass tray to every paragraph or proof item; most content floats directly on the stage.
- Do not turn the footer into a tall four-column sitemap; retain horizontal directory rows and dotted leaders.
- Do not use condensed serif pricing figures as ordinary body text.
- Do not flatten all chapters into black cards; cream atmospheric intervals are part of the cinematic contrast.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares opacity 0.1s ease-in-out and color 0.24s; footer links declare color 0.15s ease-in-out.
- The hero key inner face declares transform 0.35s; the header key declares background-color 0.3s and box-shadow 0.3s.
- Download tiles declare border-color and transform 0.15s ease-in-out with a -2px hover lift.
- Proof portraits declare 28s linear infinite orbits and 0.55s scale-in with cubic-bezier(0.16,1,0.3,1).
- Floating particle layers declare long linear loops ranging from 60s to 150s; launch glows declare 4s and 5.2s ease-in-out loops.

**Transfer:**

- Let orbiting human proof and slowly drifting light provide ambient life while navigation and links react quickly.
- Keep the download hover lift subtle and preserve the key's luminous material during interaction.

**Unknown:**

- Exact scroll-scene choreography, typing-cycle duration and reduced-motion behavior are not established.
- Focus-visible styling is unknown.

### Responsive

**Observed:**

- Desktop composition uses a 1440px stage, 1160px content region and fluid side inset max(5vw, -616px + 50vw).
- Styles declare breakpoint families around 754–769px, 991–1024px, 1215–1216px and 1407–1408px.

**Transfer:**

- On narrow layouts, stack chapter copy and its demonstration while preserving the large central light object and readable text.
- Let orbital paths extend beyond the screen rather than squeezing all rings into view.
- Stack plan and platform columns; retain the contrast between short raised plan heads and open feature lists.

**Unknown:**

- Mobile typography sizes, exact navigation collapse and breakpoint-specific ordering are not established; stacking is recommended adaptation rather than a measured mobile layout.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
