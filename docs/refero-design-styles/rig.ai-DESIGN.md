# rig.ai — blue signal infrastructure

## Overview

A technical, slightly retro-futurist style with a bright blue opening and a long, dark green-black body. Warm off-white grotesk headlines sit beside monospaced equipment labels, fine ruled grids, and restrained circuit diagrams. Scanline texture, oversized ghosted geometry, and a luminous wireframe landscape give infrastructure products a tangible machine-room character without relying on photography. The composition is spacious at section scale and compact inside explanatory panels.

### Essentials

- A blue broadcast panel opens an otherwise dark document: #2981e0 fills the 649px opening, while #151e1d carries most of the page; later blue is reserved for labels, active paths and the final action.
- Headlines feel like broad signage rather than terminal output: Chalet 700 at 112px/0.88 in the opening, 56–72px for section leads, generally -0.03em tracking outside the hero; warm #e0dcd1 replaces pure white.
- The opening is typographic, not a floating product mockup: a two-line left-aligned headline spans about two thirds of the width over a ghosted 792×777px geometric mark at 0.08 opacity; a narrow support paragraph and dark action sit underneath. Recreate a large geometric watermark when no brand illustration exists.
- Actions are cut metal tabs: opposite 14px chamfers, no rounding, Chivo Mono bold text, 16px 32px padding for regular buttons; the final blue action expands to 500×89px.
- Information lives inside a continuous instrument grid: 1200px outer rails, 48px inner side padding, 1px warm-white rules at 0.18 opacity, square panels and numbered annotations rather than detached rounded cards.
- A persistent display patina ties the artwork together: 2px transparent/2px dark scanlines at 0.08 alpha, a 42px uppercase pixel-font ticker, and thin blue diagrams with small muted labels. Use product-relevant process signals in the ticker.
- The conversion moment becomes a terrain scene: a centered 112px/0.9 closing headline and broad blue tab float over a full-width undulating blue wireframe; construct the mesh with SVG curves when bespoke art is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal blue | `#2981e0` | `--color-signal` | background, accent, action, link, border | Opening field, section labels, active connectors, selected rules and final action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer black | `#0a0a0a` | `--color-black` | background, surface | Footer ground and the base hue of translucent section-label plates. |
| Smoked label plate | `#0b0c0c` | `--color-badge` | surface | Visible result of black at 88% over the main canvas. |
| Green-black canvas | `#151e1d` | `--color-canvas` | background, surface, text | Main document, dark opening actions, and dark lettering on blue closing actions. |
| Instrument hairline | `#3a403d` | `--color-rule` | border | Visible result of warm phosphor at 18% over the main canvas; use the alpha recipe for rules across different surfaces. |
| Recessed index | `#414745` | `--color-index` | text | Small peripheral card indices; source hue #f0ede6 at 20% over the main canvas. |
| Dormant annotation | `#4c524f` | `--color-faint-label` | text | Inactive step numbers; source hue #f0ede6 at 25% over the main canvas. |
| Inactive heading | `#626663` | `--color-inactive` | text | Inactive step headings; source hue #f0ede6 at 35% over the main canvas. |
| Low emphasis label | `#6d716d` | `--color-muted-label` | text | Diagram labels on the main canvas; source hue #f0ede6 at 40%. Footer uses the same alpha against black. |
| Secondary link | `#838682` | `--color-quiet-link` | link, text | Secondary navigation ink; source hue #f0ede6 at 50%. Against footer black it reads darker. |
| Secondary reading ink | `#adada4` | `--color-body-muted` | text | Visible result of warm phosphor at 75% over the main canvas; explanatory paragraphs. |
| Warm phosphor | `#e0dcd1` | `--color-ink` | text | Headlines and primary reading text. |

## Typography

- **Chalet** — Hero, section headings, card headings and FAQ questions. Broad, rounded grotesk with open counters and a friendly engineered silhouette; the bold face remains visually light at monumental sizes. If unavailable, use **DM Sans**. Use 700; check line breaks and broad counters before tightening tracking. Font stack: "Chalet", "DM Sans", Inter, sans-serif.
- **Instrument Sans** — Support paragraphs, descriptions and secondary links. Contemporary sans with open shapes, compact body proportions and clear small-size reading. Font stack: "Instrument Sans", system-ui, sans-serif.
- **Chivo Mono** — Action labels, section badges, numbering and technical annotations. Monospaced equipment lettering; regular uppercase labels contrast with bold sentence-case actions. Font stack: "Chivo Mono", monospace.
- **Geist Pixel Square** — Broadcast ticker text. Square pixel-built monospace used as a narrow atmospheric strip rather than as body text. Font stack: "Geist Pixel Square", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Chalet | 700 | 112px | 0.88 | normal | size clamp(3.5rem, 8vw, 7rem) | Opening headline; broad two-line promise. |
| closing-display | Chalet | 700 | 112px | 0.9 | -0.03em | size clamp(4rem, 8vw, 7rem) | Monumental short closing promise, stacked within a 600px measure. |
| heading-lg | Chalet | 700 | 72px | 0.96 | -0.03em | size clamp(3rem, 5vw, 4.5rem) | Centered introduction to the product demonstration. |
| heading-grid | Chalet | 700 | 72px | 0.92 | -0.03em | size clamp(3rem, 5vw, 4.5rem) | Left-aligned lead above a ruled problem matrix. |
| heading-setup | Chalet | 700 | 64px | 0.98 | -0.03em | size clamp(2.5rem, 5vw, 4rem) | Centered adoption or onboarding section. |
| heading-comparison | Chalet | 700 | 57.6px | 1.06 | -0.03em | size clamp(2.2rem, 4.5vw, 3.6rem) | Paired contrasting statements stacked into a single centered heading. |
| heading | Chalet | 700 | 56px | 0.92 | -0.03em | size clamp(2.5rem, 4vw, 3.5rem) | Default section lead for processes and questions. |
| card-heading | Chalet | 700 | 32px | 1.05 | -0.02em | size clamp(1.5rem, 2.5vw, 2rem) | Interactive process steps; inactive steps change color, not type. |
| step-heading | Chalet | 700 | 26.4px | 1.1 | -0.02em | size clamp(1.3rem, 2vw, 1.65rem) | Titles in ordered setup columns. |
| hero-support | Instrument Sans | 600 | 24px | 1.6 | normal | fixed | Opening support paragraph; max-width 580px, warm text at 0.85 opacity. |
| closing-button | Chivo Mono | 700 | 20.8px | 1.2 | normal | fixed | Large closing action label. |
| question | Chalet | 400 | 19.2px | 1.2 | -0.02em | fixed | FAQ summary questions. |
| body | Instrument Sans | 400 | 16px | 1.7 | normal | fixed | General section descriptions in secondary reading ink. |
| body-small | Instrument Sans | 400 | 14.4px | 1.7 | normal | fixed | Explanatory card paragraphs and expanded answers. |
| button | Chivo Mono | 700 | 13.6px | 1.25 | normal | fixed | Default opening action label. |
| footer-link | Instrument Sans | 400 | 13.6px | 1.25 | normal | fixed | Muted footer links. |
| ticker | Geist Pixel Square | 400 | 12.8px | 17px | 0.1em, uppercase | fixed | Full-width broadcast strip. |
| eyebrow | Chivo Mono | 400 | 12px | 1.25 | 0.12em, uppercase | fixed | Blue section-label text inside a smoked rectangular plate. |
| nav-button | Chivo Mono | 700 | 12px | 1.25 | 0.05em | fixed | Compact navigation action. |
| footer-label | Chivo Mono | 700 | 12px | 1.25 | 0.15em, uppercase | fixed | Footer column names. |
| micro-step | Chivo Mono | 400 | 9.6px | 1.25 | 0.2em, uppercase | fixed | Small process-step annotations. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep broad grotesk headings separate from monospaced annotations; do not make technical subject matter an excuse for monospaced headlines.
- The opening headline retains normal tracking, while almost all large section leads tighten to -0.03em. The closing headline uses tighter tracking than the equally sized opening.
- Large headline line heights stay below 1 except for the two-statement comparison. Body copy is much looser at 1.7.
- Color carries selection in the process stepper: primary ink and blue for the active step, gray-green for dormant steps.

## Layout

**Density:** Airy section spacing with compact ruled internals; the continuous rails keep the long document cohesive.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Stacked micro-label and step-heading gap. |
| 9.6px | Icon-to-label gaps and secondary footer link spacing. |
| 16px | Paragraph separation inside cards; action vertical padding. |
| 24px | Section title to support line, FAQ vertical padding and setup-card top padding. |
| 28px | Comparison panel interior padding. |
| 32px | Problem panel padding and three-column grid gaps. |
| 48px | Container inner side padding, comparison separation and closing headline to action. |
| 64px | Major header-to-demonstration gap and footer top padding. |
| 112px | Vertical padding for comparison and adoption sections. |
| 128px | Major explanatory section top padding. |
| 192px | Closing scene top padding. |
| 256px | Closing scene bottom padding. |

### Containers and grids

- **outer-rails**: max width 1200px · side padding 0px. Centered continuous document rails; at desktop these leave 120px outer margins.
- **reading-container**: max width 1200px · side padding 48px. Inset reading area within the rails, yielding 1104px of usable content.
- **opening-container**: max width 1296px · side padding 48px. Navigation and opening content align on a 1200px reading span.
- **heading-measure**: max width 720px. Centered large heading blocks; support lines usually narrow to 600–700px.
- **three-column**: 3 columns · gap 32px. Equal setup or explanatory columns within the inset container.
- **process-split**: 2 columns · gap 0px. 2fr/3fr split: a 480px text stepper beside a 720px diagram panel.
- **comparison**: 2 columns · gap 0px. Two equal 552px panels sharing a central seam.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing-panels | 0px |
|  | actions | 0px |
| product demonstrations | product-window | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| closing-action-glow | `0px 0px 40px 0px rgba(41,129,224,0.15)` | Soft signal halo around the large closing action. |

### Surfaces

#### Instrument canvas · level 0

**Use:** Default dark document ground.

**CSS:** `background: #151e1d; color: #e0dcd1`

**Observed:** Fine vertical container rails and horizontal section rules continue through the page.

**Transfer:** Keep the canvas uninterrupted through explanatory chapters.

#### Broadcast blue · level 0

**Use:** Full-width opening field.

**CSS:** `background: #2981e0; color: #e0dcd1; overflow: hidden`

**Observed:** Ghosted geometry stays behind the headline; the ticker forms the bottom edge.

**Transfer:** Use a single concentrated blue opening rather than repeating blue feature bands.

#### Display scanlines · level 2

**Use:** Subtle display texture over the visual system.

**CSS:** `background-image: repeating-linear-gradient(0deg, rgba(0,0,0,0), rgba(0,0,0,0) 2px, rgba(0,0,0,0.08) 2px, rgba(0,0,0,0.08) 4px); pointer-events: none`

**Observed:** Horizontal dark scanlines sit over blue and dark sections. A very faint red/blue 3px fringe texture adds analog grain.

**Transfer:** Keep texture low contrast enough to preserve thin labels and diagrams.

#### Ruled panel · level 1

**Use:** Comparison panels, explanatory grids and numbered content.

**CSS:** `background: transparent; border: 1px solid rgba(224,220,209,0.18); border-radius: 0px`

**Observed:** Many panels use only the shared edge or top rule rather than a full outline; the active comparison panel adds a blue top inset line and a faint diagonal light wash.

**Transfer:** Share seams within grids; do not double up adjacent borders.

#### Smoked plate · level 1

**Use:** Compact section badges.

**CSS:** `background: rgba(10,10,10,0.88); border: 1px solid rgba(224,220,209,0.18); backdrop-filter: blur(8px); border-radius: 0px`

**Observed:** Small dark plates carry blue labels and one tiny icon.

**Transfer:** Use for chapter markers, not for every individual heading.

#### Footer ground · level 0

**Use:** Final utility area.

**CSS:** `background: #0a0a0a; border-top: 1px solid rgba(224,220,209,0.18); padding: 64px 0px 160px`

**Observed:** The footer steps darker than the body, with restrained ink and generous empty space below the utility row.

**Transfer:** End with a low-emphasis utility zone after the dramatic conversion scene.

## Components

### Navigation

**Use:** Minimal opening navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; max-width: 1296px; padding: 24px 48px; gap: 16px`

**Text style:** `nav-button` — Chivo Mono 700 · 12px/1.25 · tracking 0.05em

**Observed:** A compact dark wordmark sits at left and a single Dark chamfer button at right; there is no crowded menu.

**Transfer:** Use a compact product mark and one high-intent action.

### Dark chamfer button

**Use:** Default primary action on the blue opening.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 16px 32px; background: #151e1d; color: #e0dcd1; border-radius: 0px; clip-path: polygon(14px 0px, 100% 0px, 100% calc(100% - 14px), calc(100% - 14px) 100%, 0px 100%, 0px 14px)`

**Text style:** `button` — Chivo Mono 700 · 13.6px/1.25

**Observed:** The top-left and bottom-right corners are cut; the body action is about 146×49px, with a smaller 142×47px navigation version using nav-button type.

**States:** Declared: hover box-shadow 4px 4px 0 #2981e0; focus-visible outline 2px solid #2981e0 with 2px offset.

**Transfer:** Keep the short sentence-case mono label and the opposing corner cuts.

### Closing action

**Use:** Dominant action inside the wireframe scene.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 12px; max-width: 500px; padding: 32px 48px; background: #2981e0; color: #151e1d; box-shadow: 0px 0px 40px 0px rgba(41,129,224,0.15); clip-path: polygon(14px 0px, 100% 0px, 100% calc(100% - 14px), calc(100% - 14px) 100%, 0px 100%, 0px 14px)`

**Text style:** `closing-button` — Chivo Mono 700 · 20.8px/1.2

**Observed:** A broad centered 500×89px tab with an 18px return-arrow icon after the label.

**States:** Declared: hover adds a 4px 4px solid warm-gold offset shadow; focus-visible outline 2px solid #2981e0 with 2px offset.

**Transfer:** Let the final action be materially larger than the first action.

### Section badge

**Use:** Recurring chapter marker above section leads.

**CSS:** `display: flex; gap: 9.6px; padding: 8px 16px; margin-bottom: 32px; background: rgba(10,10,10,0.88); border: 1px solid rgba(224,220,209,0.18); backdrop-filter: blur(8px); color: #2981e0`

**Text style:** `eyebrow` — Chivo Mono 400 · 12px/1.25 · tracking 0.12em · uppercase

**Observed:** A tiny blue icon precedes uppercase lettering; plates are centered for most sections, left aligned beside split illustrations.

**Transfer:** Choose brief functional chapter labels.

### Ordered setup card

**Use:** Three equal instructions beneath an adoption heading.

**CSS:** `border-top: 1px solid rgba(224,220,209,0.18); padding-top: 24px; border-radius: 0px`

**Text style:** `step-heading` — Chalet 700 · 26.4px/1.1 · tracking -0.02em

**Observed:** A blue two-digit index and verb label precede the heading; body text follows with a 16px gap. The cards remain open to the canvas rather than having a separate fill.

**Transfer:** Use concrete steps that make adoption feel finite.

### Process step

**Use:** Selectable process explanation beside a technical diagram.

**CSS:** `padding: 24px 32px 24px 20px; border-top: 1px solid rgba(224,220,209,0.18); background: transparent; text-align: left`

**Text style:** `card-heading` — Chalet 700 · 32px/1.05 · tracking -0.02em

**Observed:** A micro-step label sits above the title. The selected step has blue numbering, warm heading text, a thin blue left progress mark and a visible description; inactive titles are muted and collapsed.

**Transfer:** Tie each selected explanation to one highlighted route in the diagram.

### FAQ row

**Use:** Compact objection handling.

**CSS:** `display: flex; align-items: center; gap: 20px; padding: 24px 0px`

**Text style:** `question` — Chalet 400 · 19.2px/1.2 · tracking -0.02em

**Observed:** Inside a top-ruled wrapper with 24px horizontal insets, a blue two-digit index comes first, the question fills the middle and a muted 20px chevron sits at the far right. Closed rows are 73px tall including the rule; answers use body-small.

**States:** Declared: hover is unspecified; focus-visible outline 2px solid #2981e0 with 2px offset.

**Transfer:** Keep every row full width and text led.

### Broadcast ticker

**Use:** A slim stream of contextual proof or current signals at the opening edge.

**CSS:** `padding: 12px 0px; overflow: hidden; border-top: 1px solid rgba(10,10,10,0.15); color: #151e1d`

**Text style:** `ticker` — Geist Pixel Square 400 · 12.8px/17px · tracking 0.1em · uppercase

**Observed:** A 42px strip contains repeated single-line uppercase links separated by small dots, with 64px spacing in the running group and 0.7 group opacity.

**States:** Declared: hover opacity 1 and underline with 0.25em offset; focus-visible opacity 1 and the same underline.

**Transfer:** Use genuine short signals relevant to the new product; keep the strip narrow and peripheral.

### Footer link

**Use:** Secondary social and legal navigation.

**CSS:** `color: rgba(240,237,230,0.5); transition: color 0.2s`

**Text style:** `footer-link` — Instrument Sans 400 · 13.6px/1.25

**Observed:** Short vertical lists under tracked mono column labels, not button-shaped links.

**States:** Declared: hover color #2981e0; focus-visible unspecified.

**Transfer:** Keep utility links deliberately quieter than the conversion scene.

## Imagery and graphics

### Ghosted geometric watermark

**Use:** Large atmospheric object behind the opening typography.

**Observed:** An oversized rounded, nested right-angle brand geometry occupies the right half and bleeds above and below the blue field. At 792×777px and 0.08 opacity it is much quieter than the warm headline.

**Transfer:** Use a new product's abstract geometry. The minimum version is a set of broad nested elbow paths rather than a photo or stock illustration.

**Build:** Create an SVG with three nested rounded 90-degree elbow paths, thick uniform strokes and no fine detail. Scale to roughly 792×777px at desktop, anchor to the right half, let it exceed the section boundary, color it with warm ink at 0.08 opacity and clip it inside Broadcast blue.

### Instrument diagrams

**Use:** Problem, process and benefit explanations throughout the dark body.

**Observed:** Sparse vector schematics show small terminal/code boxes, branching connector lines, funnels, gate-like bars and a database cylinder. Thin electric-blue paths stand out from gray-green inactive routes; occasional tiny warning marks use red. Corner brackets, dotted guide lines and small mono captions make each drawing feel like a measured instrument. Drawings occupy roughly 400–480px square beside text.

**Transfer:** Translate the product into a small input→transformation→output system. A few nodes with one highlighted route are sufficient; preserve sparse line work and low contrast rather than making a dense architecture map.

**Build:** Use SVG with 1px strokes, no solid backing, square 28–48px nodes and orthogonal connectors. Draw inactive paths in warm ink at 0.18–0.35 opacity and the active route in #2981e0. Add short mono labels above groups, four faint L-shaped framing brackets, and a few dashed alignment guides.

### Product demonstration window

**Use:** Large centered proof stage after the introductory heading.

**Observed:** A 1104×507px near-black application window shows an editor and conversation side by side. A thin frame, small corner radius, restrained syntax colors and tiny interface text make it look operational, not like a glossy tilted mockup.

**Transfer:** Use a real or carefully simplified product workflow at readable scale. Preserve straight-on framing, a subdued near-black UI and one clear event being demonstrated; avoid recreating every internal control.

### Wireframe terrain

**Use:** Signature conversion scene behind the final promise and action.

**Observed:** A blue rectilinear mesh bends into broad waves across the whole viewport and bleeds beyond both sides. The dark canvas shows through it, with restrained bloom and tiny occasional light points. A soft central dark veil protects the headline and button.

**Transfer:** Retain the undulating wireframe regardless of product category. The minimum version is a static SVG field of intersecting curved blue lines, not a generic gradient blob.

**Build:** Create an oversized SVG plane about 1944px wide, centered and clipped to the viewport. Draw roughly 24 longitudinal and 14 crosswise paths as smooth cubic curves: lift the sides and sag the center so the grid forms a broad valley, then add a second rolling crest toward the right. Stroke #2981e0 at low-to-medium opacity with no fill. Duplicate beneath with a small blur for restrained bloom. Put a broad radial canvas-colored veil over the center at 0.6 opacity with 8px blur; place the text and Closing action above all paths.

### Icons

**Observed:** Section badges use 16px blue icons; FAQ chevrons are 20px outline marks with 2px rounded strokes. Integration marks are compact 24px silhouettes. The final action uses an 18px dark return arrow with a 2.5px rounded stroke.

**Transfer:** Use simple terminal, branch, link and directional symbols with consistent optical size. Keep brand integration logos muted and secondary; avoid multicolor decorative icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Broadcast opening

**Observed:** A 649px full-width Broadcast blue field begins with Navigation: compact dark wordmark on the left and a small Dark chamfer button on the right. Below, the display headline occupies about two thirds of the width on two tight lines, aligned to the same left rail. The hero-support paragraph is only 580px wide and breaks into three lines; a second Dark chamfer button follows after 40px. Layers run blue ground → oversized right-half Ghosted geometric watermark → warm text and dark actions → Display scanlines. The Broadcast ticker closes the field at 42px tall. Within the first 900px, the entire hero, both actions and ticker are visible, followed by a 64px dark breathing strip and the badge and heading of the next chapter. Detailed panels and the product demonstration fall below the fold.

**Transfer:** Lead with a short operational promise, a narrow explanation and one repeated high-intent action. Without bespoke media, use a huge low-opacity nested geometric mark behind the typography. For narrower-purpose marketing pages retain the same blue typographic opening but shorten the support and move straight into relevant proof.

**Avoid:** Do not replace the left-aligned typographic field with a centered headline over a floating browser card; do not turn the ghosted geometry into a high-contrast competing object.

**Text style:** `display` — Chalet 700 · 112px/0.88

### Ruled problem matrix

**Observed:** A Section badge sits above a broad heading-grid lead. Beneath it, a 1200px-wide shared-line grid reserves one 400×420px column for an Instrument diagram and uses the remaining area for four 400×210px text panels. Panels carry a blue micro-label, a recessed three-digit index, a short heading and a compact paragraph with 32px internal padding.

**Transfer:** Frame the reader's friction in several distinct dimensions while keeping the picture one third of the grid. Replace the diagram with a simple bottleneck or before-state relevant to the product.

**Text style:** `heading-grid` — Chalet 700 · 72px/0.92 · tracking -0.03em

### Centered product proof

**Observed:** A Section badge, heading-lg and narrow centered paragraph introduce a straight-on Product demonstration window after a 64px gap. The section uses 128px vertical padding. Beneath the window, an explanatory caption pair and four numbered, top-ruled progress tabs explain the workflow; square arrows and a pause control sit nearby.

**Transfer:** Show one complete product event, then explain its stages. Keep the control strip visually subordinate to the product scene.

**Text style:** `heading-lg` — Chalet 700 · 72px/0.96 · tracking -0.03em

### Paired evidence comparison

**Observed:** A Section badge precedes a two-line heading-comparison and a 700px-wide support paragraph. Two equal Ruled panels form a 1104×300px comparison with 28px internal padding; the right panel has a blue top edge and a faint diagonal wash. A three-column explanation row follows after 48px, with blue indices and short descriptive claims.

**Transfer:** Compare an old inference with a new observable result, using diagrams rather than a large table. Preserve equal panel sizes and emphasize the improved state with only a signal edge.

**Text style:** `heading-comparison` — Chalet 700 · 57.6px/1.06 · tracking -0.03em

### Selectable process map

**Observed:** A centered Section badge, heading and short paragraph lead into the process-split grid. Process step items stack on the left; the right is a 720×680px dark panel with a thin shared border and a centered Instrument diagram. Only one step's description and route are emphasized at a time.

**Transfer:** Use this when the product has several meaningful stages. Each stage must change the visible route or state, not merely swap a heading.

**Text style:** `heading` — Chalet 700 · 56px/0.92 · tracking -0.03em

### Illustrated benefit split

**Observed:** A roughly 480×500px Instrument diagram sits opposite a left-aligned badge, compact two-line headline and narrow body paragraph. Beneath, three equal benefit cells share vertical rules; each pairs a short centered heading with one sentence.

**Transfer:** Connect the mechanism to practical outcomes, then summarize the outcomes in parallel language. Use the diagram to simplify the earlier problem rather than introducing unrelated art.

### Adoption and compatibility

**Observed:** The heading-setup is centered above three Ordered setup cards, each separated by 32px. A full-width thin-ruled terminal-note strip follows, then a centered compatibility heading and four compact logo categories with small mono group labels. The whole chapter uses 112px vertical padding.

**Transfer:** Describe a small number of concrete setup actions and show relevant ecosystem compatibility without turning the marks into large sponsor cards.

**Text style:** `heading-setup` — Chalet 700 · 64px/0.98 · tracking -0.03em

### Numbered objections

**Observed:** A centered badge and heading introduce six full-width FAQ rows after a 64px gap. Hairlines, blue indices and restrained chevrons organize the content; the body remains the same dark canvas.

**Transfer:** Use the questions most likely to block adoption; keep answers specific and bounded rather than promotional.

**Text style:** `heading` — Chalet 700 · 56px/0.92 · tracking -0.03em

### Terrain conversion and utility ending

**Observed:** A top rule begins an expansive closing scene with 192px top and 256px bottom padding. Wireframe terrain stretches beyond the viewport; the centered closing-display breaks into two lines inside 600px, followed by the Closing action after 48px. Footer ground then changes to near black. Its 1104px inner grid is 2fr/1fr/1fr with 32px gaps: brand descriptor, social links and legal links. After 64px, a top-ruled bottom row carries copyright at left and a small all-caps operational status at right, followed by 160px bottom padding.

**Transfer:** Close with a short, confident outcome and a broad single action. Keep the luminous mesh as the emotional peak, then lower the volume for utility information and a truthful operational status.

**Text style:** `closing-display` — Chalet 700 · 112px/0.9 · tracking -0.03em

## Page flow

**Storyline:** Operational promise → reader friction → working demonstration → differentiated proof → mechanism and outcomes → adoption reassurance → objections → monumental action → utility footer.

### A technical product landing page that explains an unfamiliar workflow and converts qualified interest

1. **Promise** — Blue typographic field with ghost geometry, repeated compact action and broadcast ticker.
2. **Problem framing** — Ruled matrix with one process illustration and four compact friction statements.
3. **Product demonstration** — Centered headline and large application window with a numbered explanatory control strip.
4. **Differentiated proof** — Equal before/after technical panels followed by three evidence-oriented explanations.
5. **Mechanism** — Selected text steps beside a route-highlighted schematic.
6. **Benefits** — Simplified process illustration beside an outcome headline, then three parallel benefit cells.
7. **Adoption reassurance** — Ordered setup columns, terminal note and categorized compatibility logos.
8. **Objection handling** — Numbered full-width disclosure rows.
9. **Closing call** — Monumental warm headline and broad blue chamfer action over wireframe terrain.
10. **Utility ending** — Near-black three-column footer and restrained status row.

**Transfer:** Adapt the sequence to the product's complexity. Preserve the broadcast opening, continuous instrument-grid language and wireframe conversion device while choosing only the explanatory blocks needed to earn the action.

## Writing

Direct, technical and operationally confident. Claims are explained through triggers, actions and observable results rather than abstract promises; occasional short imperatives give the page momentum.

**Do not copy:** Do not reuse the Rig name, logo geometry, proprietary product terminology, security claims, incident headlines, customer or integration endorsements, legal text, dates or operational status as facts for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use the product name as the subject of mechanism explanations, 'your' for the reader's workflow, and direct imperative verbs for setup. Reserve 'we' for fit, support or commitments.
- **Rhythm:** Short headline fragments alternate with one- or two-sentence explanations. Paired contrasts and three-part benefit phrases supply rhythm without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Imperative outcome tied to a concrete workflow. | 6–10 words | “Build Security Into The Agent Loop” |
| Supporting line | A sequence of practical verbs explaining when value arrives. | 18–30 words | “Find vulnerabilities as agents work, guide them through fixes, and verify the results, before findings turn into tickets.” |
| Contrast heading | Two brief statements distinguish an existing method from the new behavior. | 4–8 words per statement | “Static analysis reads the code.”<br>“Rig tests what it does.” |
| Benefit heading | Parallel verb-led fragments. | 2–3 words | “Catch More”<br>“Chase Less”<br>“Ship More” |
| Setup heading | Short imperative naming the actual action. | 3–6 words | “Install the CLI.”<br>“Connect the coding agent.” |
| Primary action | Plain verb plus concrete next step, not a slogan. | 3–4 words | “Get a Demo”<br>“Book a Demo” |
| Closing promise | A compact outcome with a confident adverb. | 2–4 words | “Ship Confidently” |

**Words and phrasing to use:** check; connect; run; verify; confirm; guide; results; workflow; context; evidence; before; when

**Avoid:** revolutionary; game-changing; unleash; magic; effortless perfection; guaranteed safety; best-in-class

**Rules:**

- Explain what starts an action and where the result goes.
- Distinguish a potential result from a confirmed result when accuracy matters.
- Write benefits in parallel grammatical forms.
- Use functional labels for chapter badges and concrete verbs for adoption steps.
- Answer objections directly, including limits; do not bury qualifications in hype.

## Do's and Don'ts

### Do

- Use #2981e0 as a broad opening field and a narrow active signal across the dark body.
- Keep large section headlines at 700 with -0.03em tracking; preserve normal tracking on the opening display.
- Align ruled grids to the 1200px rails and inset prose by 48px.
- Use shared 1px warm-ink rules at 0.18 alpha to organize dense information.
- Pair 14px opposite chamfers with bold mono button text.
- Give explanatory diagrams 400–480px of space and emphasize only one route in blue.
- Keep support paragraphs near 600–700px and use 1.7 line height for ordinary body text.
- Make the final action visibly larger at 500×89px and stage it over the wireframe mesh.

### Don't

- Do not use pure-white reading text on pure-black body sections; the main relationship is #e0dcd1 on #151e1d.
- Do not round marketing cards into 12px or 24px rectangles; square shared seams define the system.
- Do not turn every section into a blue fill; the blue opening is a concentrated contrast against the long dark document.
- Do not give normal content cards drop shadows; reserve glow for the closing action and signal artwork.
- Do not use 24px uppercase mono text for body copy; mono belongs to small equipment labels and actions.
- Do not replace sparse line diagrams with glossy 3D isometric servers or colorful sticker art.
- Do not make compatibility logos large saturated tiles; keep them near 24px and visually subdued.
- Do not compress the footer to a narrow strip; preserve 64px top and 160px bottom breathing room.

## Motion and responsive

### Motion

**Observed:**

- Chamfer actions declare a 0.2s cubic-bezier(0.25, 1, 0.5, 1) transition; footer links declare color 0.2s.
- The geometric watermark declares a 4s linear repeating glitch animation; the header glow declares a 3s ease-in-out pulse.
- The demonstration declares a 0.35s ease scene reveal and a 6s linear progress fill; arrows and a pause control accompany the sequence.
- A ticker animation is declared with a 0s duration; a nonzero running speed is not established.

**Transfer:**

- Keep the button's offset-shadow response crisp rather than elastic.
- Let process progression connect the selected text to the highlighted diagram, retaining explicit pause and step controls.
- Retain the broadcast-strip format even when presenting it statically.

**Unknown:**

- Exact glitch displacement, ticker speed, scroll activation thresholds and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The display and section heading recipes use the recorded clamp formulas.
- Declared width breakpoints include 700px, 768px, 769px, 900px, 901px, 1000px, 1024px and 1280px.

**Transfer:**

- As design guidance, stack diagram/text splits and setup columns when they no longer fit while retaining shared rules and ordered indices.
- Keep the ghost geometry clipped behind the opening; preserve the text-first hierarchy rather than moving it into a separate illustration block.
- Scale the wireframe across the available width and keep the closing action within the reading area.

**Unknown:**

- Only the desktop composition is established; exact mobile padding, navigation changes and stacking order are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
