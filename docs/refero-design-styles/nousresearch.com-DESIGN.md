# Nous Research — electric humanist engravings

## Overview

An electric-blue and chalk-white identity that feels like a research manifesto printed on a futuristic broadsheet. Extremely tall compressed grotesks sit beside tiny utilitarian labels and compact, matter-of-fact paragraphs. Grainy duotone engravings, classical figures, geometric diagrams and interface demonstrations give technical products a mythic, humanist character. The composition is spacious at the chapter level and dense within individual text and navigation groups.

### Essentials

- Headlines behave like architectural lettering: compressed uppercase grotesks at 304px/1 and weight 400 span a 1080px text stage, while body copy remains only 13–15px.
- The opening is a typographic poster, not a dashboard: a centered emblem and split navigation lead to a 720px command strip, a huge single-line name, centered support and two compact actions on chalk paper.
- Actions resemble printed equipment labels: 15px condensed capitals, weight 500, 0.02em tracking, 3px corners and 47px height; the filled electric-blue action sits beside an almost unpainted secondary action.
- Color is a two-ink system rather than a decorative accent: #f2f2f2 carries the light opening and explanatory chapters; #0000f2 takes over entire illustrated bands and the closing scene. Keep all principal art blue-and-paper, with no competing marketing accent.
- Illustrations are grainy printed artifacts at cinematic scale: classical or human imagery is thresholded into blue and pale highlights, with scanlines, halftone and diagram overlays. Include this print-art device; when bespoke illustration is unavailable, use a licensed subject photograph with the same duotone and geometric treatment.
- The page has a designed perimeter and a theatrical ending: a 5px blue-violet frame surrounds the desktop viewport, and an oversized translucent compressed word sculpture emerges from a duotone image above a blue multi-column footer. Preserve both devices with the new product's lettering.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0000f2` | `--color-electric` | background, text, action, link, border | Primary printing ink, full-band backgrounds, light-page display text and filled actions. |
| Blue underlay | `#0000c2` | `--color-underlay` | background | Outer page backing beneath the primary blue layer. |
| Deep blue ink | `#000091` | `--color-ink` | text, surface | Body text and smaller headings on paper; terminal panel backing. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue-violet edge | `#3333f5` | `--color-frame` | border | Continuous desktop perimeter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft secondary wash | `#ededed` | `--color-secondary` | surface | Visible result of 2% black over chalk paper for secondary actions; use rgba(0,0,0,0.02). |
| Chalk paper | `#f2f2f2` | `--color-paper` | background, text, surface | Default light canvas and reversed text on electric blue. |
| Pale command edge | `#f2f2fa` | `--color-command-edge` | border | Subtle outline separating the white command strip from paper. |
| Pure white | `#ffffff` | `--color-white` | surface, text | Command strip and selected high-contrast reverse lettering. |

## Typography

- **Rules Gothic Compressed** — Monumental lettering, section headings and narrow card titles. Extremely tall, thin-stemmed compressed grotesk; its width is essential to the poster effect. If unavailable, use **Barlow Condensed**. Use 300–500; fit short uppercase names across the stage while retaining tall proportions. Font stack: "Rules Gothic Compressed", "Barlow Condensed", sans-serif.
- **Rules Condensed** — Navigation, actions, metadata and uppercase labels. Compact utilitarian sans with a technical, almost monospaced rhythm. If unavailable, use **Roboto Condensed**. Use 400–500 and keep role-specific tracking. Font stack: "Rules Condensed", "Roboto Condensed", sans-serif.
- **Rules Variable** — Paragraphs and explanatory copy. Plain proportional grotesk, modest x-height and regular weight. If unavailable, use **Inter**. Use 400; keep compact paragraph widths. Font stack: "Rules Variable", "Inter", sans-serif.
- **Rules Gothic Condensed** — Footer titles and sentence-case product headlines. Tall narrow grotesk, more open than the compressed display family. If unavailable, use **Barlow Condensed**. Use 200–400 for the light sentence-case roles. Font stack: "Rules Gothic Condensed", "Barlow Condensed", sans-serif.
- **Aeonik Fono Pro TRIAL** — Command strip label and installation code. Technical, mono-like lettering for small functional text. If unavailable, use **IBM Plex Mono**. Font stack: "Aeonik Fono Pro TRIAL", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Rules Gothic Compressed | 400 | 304px | 1 | normal, uppercase | Fit a short name across the main light-page stage; maintain the tall unbroken silhouette. |
| section-heading | Rules Gothic Compressed | 500 | 90px | 1 | normal, uppercase | Major editorial section labels on paper. |
| chapter-heading | Rules Gothic Compressed | 400 | 48px | 1.1 | normal | Multi-line headings beside illustrated chapters. |
| card-heading | Rules Gothic Compressed | 500 | 36px | 1.2 | normal | Names above product entry cards. |
| footer-title | Rules Gothic Condensed | 400 | 32px | 1.4 | normal | Sentence-case directory column titles. |
| hero-support | Rules Variable | 400 | 15px | 1.4 | normal | Centered introductory explanation. |
| action | Rules Condensed | 500 | 15px | 1.4 | 0.02em, uppercase | Primary and secondary button labels. |
| news-body | Rules Variable | 400 | 14.6px | 1.3 | normal | Editorial update excerpts. |
| navigation | Rules Condensed | 500 | 14px | 1 | 0.1em, uppercase | Top-level navigation markings. |
| date | Rules Condensed | 400 | 13.5px | 1 | 0.04em, uppercase | Datelines below update excerpts. |
| body | Rules Variable | 400 | 13px | 1.5 | normal | Compact chapter descriptions and recruitment explanations. |
| eyebrow | Rules Condensed | 400 | 13px | 1.2 | normal, uppercase | Short category labels above chapter headings. |
| command-label | Aeonik Fono Pro TRIAL | 400 | 13px | 1.5 | normal | Text inside the introductory command strip. |
| footer-label | Rules Condensed | 400 | 13px | 1 | normal, uppercase | Footer categories and directory links. |
| metadata | Rules Condensed | 400 | 12.4px | 1 | 0.04em, uppercase | Product categories and update handles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| installation-focused product landings | product-display | Rules Gothic Condensed | 200 | 108px | 1 | -0.02em | Three-line sentence-case promise in a blue split hero. |
| installation-focused product landings | product-section | Rules Gothic Condensed | 400 | 80px | 1 | -0.02em | Sentence-case feature, download and question headings. |
| installation-focused product landings | feature-heading | Rules Gothic Compressed | 500 | 48px | 1.1 | normal | Capability titles and plan prices; prices use uppercase styling. |
| question sections | question | Rules Gothic Compressed | 400 | 32px | 1.4 | normal | Underlined accordion questions. |
| recruitment pages | catalogue-title | Rules Gothic Condensed | 400 | 20px | 1.4 | normal | Linked opportunity titles in table-like rows. |
| installation-focused product landings | product-body | Rules Variable | 400 | 16px | 1.6 | normal | Capability explanations and plan introductions. |
| installation-focused product landings | install-code | Aeonik Fono Pro TRIAL | 400 | 11px | 1.5 | normal | Installation command and platform tabs. |

**Notes:**

- The contrast is primarily width and scale, not boldness: keep compressed lettering tall and delicate beside small proportional body text.
- Use normal tracking for the most compressed lettering. The less-compressed sentence-case product display tightens to -0.02em; navigation expands to 0.1em.
- Fit large names to their available width rather than applying the same size to arbitrary copy. The secondary monumental title reaches 338.5px/1 within the same 1080px stage.
- The root text scale follows clamp(14px, 7px + 0.5vw, 18px) on the light corporate and recruitment treatments. Retain that relationship for rem-based details; fit-text headlines size independently.

## Layout

**Density:** Airy chapters surrounding tightly grouped technical labels and compact paragraphs; art receives considerably more area than prose.

### Spacing

| Value | Use |
| --- | --- |
| 5.3px | Tight repeated flex gaps. |
| 7.1px | Small inline gaps and micro spacing. |
| 12px | Button side padding. |
| 17.8px | Footer grid gaps and accordion vertical padding. |
| 20px | Chapter copy stack gaps. |
| 22.5px | Entry-card stack and update-card gaps. |
| 30px | Product split-hero and capability internal spacing. |
| 40px | Editorial rail and capability column gaps. |
| 45px | Inset of blue bands and product entry column gaps. |
| 60px | Illustrated chapter and compact section vertical padding. |
| 80px | Container side padding and major section padding. |
| 135px | Generous opening bottom space and monumental title lead-in. |

### Containers and grids

- **main-container**: max width 1240px · side padding 80px. Centered outer container yielding a 1080px working stage at desktop.
- **reading-stage**: max width 1080px. Shared alignment for section headings, wide media, catalogue and questions.
- **hero-copy**: max width 640px. Centered short paragraphs beneath the monumental headline; actual text occupies about 608px.
- **product-entry-grid**: 3 columns · gap 45px. Three 330px product previews with labels and actions outside the media.
- **editorial-rail**: 3 columns · gap 40px. 325px update cards with an additional card partially visible beyond the right edge.
- **feature-grid** (only for installation-focused product landings): 3 columns · gap 40px. Capability columns, with 80px between rows and 333px-wide entries.
- **plans** (only for pricing sections): 4 columns · gap 8.9px. Compact 263px plan columns under one shared wide illustration.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 3px |
|  | navigation-and-command | 1.8px |
|  | illustrated-band-top | 5.3px |
|  | preview-top | 6px |
| recruitment pages | culture-panel-top | 10px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #f2f2f2; color: #000091`

**Observed:** A nearly white plane rather than cream paper; little conventional card elevation.

**Transfer:** Let whitespace, print imagery and changes of ink establish hierarchy.

#### Electric band · level 0

**Use:** Illustrated chapters and the final directory.

**CSS:** `background: #0000f2; color: #f2f2f2; border-radius: 5.3px 5.3px 0px 0px`

**Observed:** The long chapter band is inset from paper; the closing blue field runs to the perimeter.

**Transfer:** Reserve full blue for decisive changes in narrative scale, not scattered pastel cards.

#### Viewport frame · level 3

**Use:** Persistent desktop perimeter.

**CSS:** `position: fixed; inset: 0px; border: 5px solid #3333f5; pointer-events: none; z-index: 100`

**Observed:** Faint moving light sits along the blue-violet edge, with a subtle fine-grain veil.

**Transfer:** Keep the border crisp and the edge light subordinate to the content.

#### Preview backing · level 1

**Use:** Clipped product demonstrations.

**CSS:** `background: #0000f2; border-radius: 6px 6px 0px 0px; overflow: hidden`

**Observed:** Blue printed texture surrounds pale interface views; no drop shadow.

**Transfer:** Use the same backing across heterogeneous product views.

#### Installation panel · level 1

**Only for:** installation-focused product landings

**Use:** Platform tabs and a single command.

**CSS:** `background: #000091; border-radius: 6px; padding: 4px`

**Observed:** A darker nested panel on the already blue hero. The active tab is electric blue, inactive tabs are translucent white.

**Transfer:** Keep this compact and functional, rather than expanding it into a full fake terminal.

## Components

### Split navigation

**Use:** Primary directory at the top of the page.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 1fr) auto minmax(0px, 1fr); max-width: 1240px; padding: 35.5px 80px 17.8px; column-gap: 21.3px; align-items: center`

**Text style:** `navigation` — Rules Condensed 500 · 14px/1 · tracking 0.1em · uppercase

**Observed:** Two links on either side of a small tall central emblem; labels distribute across the full stage. Initial header is 143px tall and becomes a shallow paper bar through the body.

**Transfer:** Use a compact original emblem, not a large horizontal logo.

### Primary button

**Use:** Filled action beside a lighter editorial action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #0000f2; color: #f2f2f2; border-radius: 3px; padding: 13px 12px; height: 47px; gap: 6px; border: 0px`

**Text style:** `action` — Rules Condensed 500 · 15px/1.4 · tracking 0.02em · uppercase

**Observed:** Content-sized rectangle; buttons sit as a close pair rather than separated across a row. Compact product variants use 7px vertical padding and 36px height.

**States:** Declared: hover clears shadow; focus-visible outline-style none and cleared shadow; active scale 0.98.

### Secondary button

**Use:** Lower-emphasis action in a paired row.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(0,0,0,0.02); color: #0000f2; border-radius: 3px; padding: 13px 12px; height: 47px; border: 0px`

**Text style:** `action` — Rules Condensed 500 · 15px/1.4 · tracking 0.02em · uppercase

**Observed:** Almost blends into the paper; lettering carries most of the emphasis.

**States:** Declared: hover background-color #f2f2f2; focus-visible outline-style none and cleared shadow; active scale 0.98 and background-color #f2f2f2.

### Command strip

**Use:** Interactive introduction above the main title.

**CSS:** `display: flex; align-items: center; gap: 16px; max-width: 720px; height: 54px; padding: 12px 12px 12px 16px; background: #ffffff; color: #000091; border: 2px solid #f2f2fa; border-radius: 1.8px`

**Text style:** `command-label` — Aeonik Fono Pro TRIAL 400 · 13px/1.5

**Observed:** Small pictorial glyph at left, a muted contextual label, and a toggle with two tiny keyboard keycaps at right.

**Transfer:** Provide a real search, question or command entry point with a restrained label.

### Product entry

**Use:** Three routes into the product ecosystem.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 22.5px; width: 330px`

**Text style:** `card-heading` — Rules Gothic Compressed 500 · 36px/1.2

**Observed:** Category and title align left above Preview backing, with a 330px by 352px media window; the action aligns below rather than overlaying the image.

**Transfer:** Give each route one recognizable interface fragment.

### Update card

**Use:** Horizontal editorial news rail.

**CSS:** `display: grid; justify-items: start; gap: 22.5px; width: 325px; color: #000091`

**Text style:** `news-body` — Rules Variable 400 · 14.6px/1.3

**Observed:** Duotone thumbnail, uppercase handle, short excerpt and detached uppercase dateline. Images can be landscape or square; there is no surrounding filled card.

**States:** Declared: hover unknown; focus-visible outline solid 1px with outline-offset -1px.

### Footer directory

**Use:** Final navigation over the blue closing field.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 320px) repeat(4, minmax(0px, 1fr)); max-width: 1240px; gap: 17.8px; padding: 0px 80px 35.5px; color: #f2f2f2`

**Text style:** `footer-label` — Rules Condensed 400 · 13px/1 · uppercase

**Observed:** Brand emblem and short tagline occupy the wide left column. Four narrow columns have dim uppercase categories, 32px sentence-case titles, and stacked small links; social icons and legal lines form a detached bottom row.

**Transfer:** Keep the directory legible over the ghost lettering, without enclosing columns in cards.

### Question row

**Only for:** question sections

**Use:** Compact objection handling.

**CSS:** `border-top: 1px dotted #0000f2; padding: 17.8px 0px; color: #0000f2`

**Text style:** `question` — Rules Gothic Compressed 400 · 32px/1.4

**Observed:** Full-width underlined question at left, tiny plus at the far right; the last row also closes with a dotted rule.

**Transfer:** Keep questions direct; expand answers in the same column rather than a side panel.

### Catalogue link

**Only for:** recruitment pages

**Use:** Title within an opportunity row.

**CSS:** `color: #0000f2; padding-bottom: 2px; background-image: linear-gradient(#0000f2, #0000f2); background-size: 0% 1px; background-position: 0px 100%; background-repeat: no-repeat`

**Text style:** `catalogue-title` — Rules Gothic Condensed 400 · 20px/1.4

**Observed:** A five-column row aligns employment type, title, short description, location and a tiny apply link; baseline alignment, 20px column gaps and 32px vertical padding.

**States:** Declared: hover text-decoration-color currentcolor; focus-visible outline solid 2px and outline-offset 4px.

### Plan action

**Only for:** pricing sections

**Use:** Small outlined conversion action beneath a plan.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 7px 12px; height: 36px; gap: 6px; border-radius: 3px; color: #000091; box-shadow: 0px 0px 0px 1px rgba(0,0,145,0.2) inset`

**Text style:** `action` — Rules Condensed 500 · 15px/1.4 · tracking 0.02em · uppercase

**Observed:** The outline is an inset hairline, not a raised button. It sits below a tall compressed price, compact technical benefits and credit information.

## Imagery and graphics

### Duotone print collage

**Use:** Signature chapter imagery and wide closing scene.

**Observed:** Classical busts, human hands, engraved figures and impossible stairways are rendered in electric blue with pale, noisy highlights. Faces are tightly clipped in broad cinematic rectangles; scanlines, stipple and fragments of technical texture create a photocopied digital-print feel. The ending enlarges a hand holding a bright light, or a classical face surrounded by interface fragments.

**Transfer:** Use an original or licensed human, material or tool-related subject. Minimum version: high-contrast subject photography in the same two-color process, with one geometric overlay and no stock-photo color.

**Build:** Convert an image to grayscale, increase contrast, then map shadows to #0000f2 and highlights to #f2f2f2 with an SVG feComponentTransfer duotone filter. Overlay a fine 2px repeating scanline or SVG turbulence grain at low opacity. Clip to a broad rectangle. For the closing image, add a transparent-to-#0000f2 vertical gradient reaching full blue around 86%, leaving space beneath for navigation.

### Geometric emblem stage

**Use:** A large contemplative brand interlude on paper.

**Observed:** A centered circular engraved seal sits in a field of very faint concentric circles, diagonals and horizontal/vertical construction lines. The blue central artwork is much stronger than its technical drawing backdrop.

**Transfer:** Use an original symbol, abstract mark or product silhouette in the seal; keep the construction drawing and spacious scale even without a character illustration.

**Build:** Create an SVG viewBox matching the section, with centered concentric circles, a crosshair, two diagonals and several oversized intersecting arcs. Stroke these in rgba(0,0,242,0.08) at 1px, no fill. Put a roughly 400px circular two-ink emblem in the middle of a 1080px working stage; retain broad paper margins.

### Printed product stage

**Use:** Backing for interface previews and download cards.

**Observed:** Pale product windows are partially clipped within saturated blue rectangles. Mottled mineral or cloud-like textures sit behind the UI; the same texture appears enlarged across adjacent panels. A separate wide demonstration uses a dark terminal window over a muted painterly water-garden scene.

**Transfer:** Show authentic UI at recognizable scale; keep the surrounding texture tonal blue, and reserve the painterly full-color scene for a demonstration rather than the page palette.

**Build:** Layer a blue base, an enlarged grayscale cloud or noise texture with screen blending at 0.6 opacity, then the interface image. Crop the texture beyond the container edges so no obvious tile repeats are visible.

### Radial engraved sculpture

**Only for:** installation-focused product landings

**Use:** Main object beside the blue hero promise.

**Observed:** A pale engraved multi-armed figure occupies the entire right half and reaches above and below the copy block; dense straight rays and circular structures surround it on slightly differentiated blue.

**Transfer:** Replace the figure with a licensed sculptural object or a simple etched product silhouette; preserve a tall strong silhouette and dense diagrammatic rays.

**Build:** Place the duotone silhouette over the blue field. In SVG, draw several offset circles and 60–100 fine pale rays between an inner ring and a larger outer ring, then rotate and intersect a second fan. Clip all rays to a tall rectangular stage; keep them behind the object.

### Culture vortex

**Only for:** recruitment pages

**Use:** Square statement artwork before the opportunity catalogue.

**Observed:** A small falling figure is suspended in a warped checkerboard tunnel. The square blue artwork is 1080px across, with a thin white compressed statement near the top and another below.

**Transfer:** Choose a metaphor for the working culture rather than generic employee headshots; maintain the blue two-ink print treatment.

**Build:** Use an SVG checkerboard mesh whose cells contract toward an offset central point; warp rows into curved radial paths. Add pale grain and a small duotone human silhouette near the vanishing point. Put brief white compressed text above and below, not across the busiest center.

### Icons

**Observed:** Mostly solid monochrome silhouettes and compact line glyphs. Social marks are 18–21px; small inline action glyphs are about 12–22px. The central emblem is tall, about 43px by 60px; tiny section glyphs sit immediately after a heading.

**Transfer:** Use one-color SVGs matching the surrounding ink. Keep expressive pictorial marks rare and avoid colored app-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Typographic poster opening

**Observed:** Paper canvas fills the first 900px inside Viewport frame. Split navigation occupies the upper 143px, with a tall centered emblem and four widely distributed labels. Command strip sits centered below it. A tiny uppercase overline precedes a single-line blue name across the 1080px working stage; the display uses 304px/1 lettering with a visible cap-height around 238px. The name dominates the middle of the screen, not a product mockup. Under it, two centered short paragraphs sit in about 608px, followed by Secondary button and Primary button as a touching pair. The opening leaves 135px of lower breathing room. At the bottom edge, the next inset blue art band begins; its main artwork is below the fold. Layers are paper, command strip and display/copy, small actions, then the perimeter above all.

**Transfer:** Use a short product or proposition name that can become a monumental one-line word shape. The typography is the main object, so no bespoke hero image is needed. Recruitment openings retain the monumental title but replace the command strip with a tiny count and use two paragraph columns. Installation-focused landings instead open with the scoped blue split composition.

**Avoid:** Do not shrink the title to a conventional 64px headline, place a huge dashboard above it, or replace the small paired actions with pill buttons.

**Text style:** `display` — Rules Gothic Compressed 400 · 304px/1 · uppercase

### Alternating illustrated chapters

**Observed:** Electric band is inset 45px from the paper edge. A wide art introduction and a monumental reversed slogan establish the band, followed by 400px-tall rows with 60px vertical padding. A narrow 280px text column sits against broad panoramic art; alternate sides. Eyebrow, chapter-heading and body form a 20px-spaced stack.

**Transfer:** Use each row for one distinct belief or capability. Preserve the unequal text-to-art ratio and swap sides to maintain rhythm.

**Text style:** `chapter-heading` — Rules Gothic Compressed 400 · 48px/1.1

### Monumental product chapter

**Observed:** A huge blue compressed title on paper begins a separate product story. A tiny overline sits above; below, two short support fragments align left and right across the stage. Paired actions center beneath, then a 1350px-wide demonstration follows.

**Transfer:** Use a second monumental word shape to mark a substantial new narrative, not every subsection.

**Text style:** `display` — Rules Gothic Compressed 400 · 304px/1 · uppercase

### Entry grid and update rail

**Observed:** Product entry components form a three-column grid, followed by a strong uppercase section-heading with a tiny social glyph. Update card components extend into a horizontal rail with 40px gaps and a partial next item.

**Transfer:** Distinguish practical entry routes from editorial proof: contained media windows for routes, unboxed excerpts for updates.

**Text style:** `section-heading` — Rules Gothic Compressed 500 · 90px/1 · uppercase

### Theatrical directory ending

**Observed:** A paper interlude closes with a geometric emblem stage and compact legal markings; the product variant uses a very faint monumental name in its paper strip. A full-width Duotone print collage then fills roughly a screen, fading down to electric blue. A gigantic low-contrast compressed word sculpture stretches behind the Footer directory. The final screen retains blue, white links, emblem, social marks, column headings and widely separated legal lines; it does not return to paper.

**Transfer:** End with an atmospheric two-ink image and the new product's oversized translucent lettering. Use an abstract duotone object if human art is unavailable; keep the image-to-blue fade and readable directory. The visual finale can carry a sense of invitation without adding an unrelated conversion card.

**Text style:** `footer-title` — Rules Gothic Condensed 400 · 32px/1.4

### Blue split installation opening

**Only for:** installation-focused product landings

**Observed:** Blue fills the hero and header. The 108px thin sentence-case promise forms three tightly stacked lines on the left, while Radial engraved sculpture occupies the right half. Two 36px actions sit 30px below the promise; the dark installation panel comes below after a larger gap. Within 900px the complete promise, actions, platform tabs, command and most of the tall artwork are visible; the demonstration starts below.

**Transfer:** Use a three-part benefit statement, two practical routes and a real installation command. Keep this a deliberate product-specific variant rather than mixing its headline styling into the poster default.

**Text style:** `product-display` — Rules Gothic Condensed 200 · 108px/1 · tracking -0.02em

### Capability and question chapters

**Only for:** installation-focused product landings

**Observed:** A centered blue download chapter pairs an 80px heading with three printed download panels. Paper then introduces a left-aligned 80px section heading with a small trailing glyph. Capability entries use numbered tiny uppercase labels, 48px headings, 16px descriptions and square duotone art in three columns. Question row components span the shared 1080px stage below.

**Transfer:** Explain the product in discrete operational verbs and concrete outcomes, then resolve setup and usage questions.

**Text style:** `product-section` — Rules Gothic Condensed 400 · 80px/1 · tracking -0.02em

### Shared illustration pricing

**Only for:** pricing sections

**Observed:** A heading and short explanation precede one wide blue engraving shared by all plans. Four compact unboxed columns sit beneath with compressed 48px prices, uppercase labels, tiny technical benefit lists and Plan action components. A small most-popular marker singles out one tier without enlarging its card.

**Transfer:** Let the shared illustration unify the offer; distinguish plans through allowance and access, not differently colored boxes.

**Text style:** `feature-heading` — Rules Gothic Compressed 500 · 48px/1.1

### Opportunity catalogue and contact

**Only for:** recruitment pages

**Observed:** An uppercase compressed section heading introduces five-column catalogue rows. Type, linked role, description, location and apply action align on baselines. A separate 80px-padded application block uses a large heading, a small action, email and a concise checklist. A shallow paper legal strip precedes the blue ending.

**Transfer:** Use this structure for any list of opportunities requiring comparison and a direct human contact route.

**Text style:** `section-heading` — Rules Gothic Compressed 500 · 90px/1 · uppercase

## Page flow

**Storyline:** identity and purpose → expressive demonstration → practical routes and capabilities → current proof or objections → atmospheric brand finale and directory

### Institutional marketing with a connected product story

1. **Identity and promise** — Monumental name, command entry, short mission copy and paired actions.
2. **Belief and differentiation** — Inset blue illustrated band with broad introductory art, a giant slogan and alternating text/art chapters.
3. **Product demonstration** — Second monumental title leads to a wide demonstration and three practical entry routes.
4. **Current proof** — Horizontal rail of dated illustrated updates.
5. **Brand finale** — Geometric seal interlude, legal strip, full-width duotone reveal and blue directory.

**Transfer:** Use the institutional story to establish a worldview, then show how a product makes it tangible.

### Recruitment and opportunity discovery

1. **Purpose** — Monumental title, tiny opening count and two concise explanatory columns.
2. **Culture** — Square blue vortex artwork carrying short compressed statements.
3. **Opportunity comparison** — Compact baseline-aligned catalogue rows.
4. **Next step** — Direct contact action and concise application checklist.
5. **Brand finale** — Paper legal strip gives way to the shared duotone image and blue directory.

**Transfer:** Keep the worldview expressive but make the actionable catalogue easy to scan.

### Installation-led product conversion

1. **Promise and action** — Blue split hero with thin three-line headline, engraved object, download actions and installation command.
2. **Product demonstration** — Wide interface film and platform-specific download panels.
3. **Capabilities** — Numbered three-column chapters with square blue print art.
4. **Objection handling** — Full-width question rows and a documentation route.
5. **Offer comparison** — Shared engraving above compact plan columns and account actions.
6. **Brand finale** — Faint name and legal marks on paper, then classical duotone scene, ghost word sculpture and directory.

**Transfer:** Lead with something the reader can do immediately, then make the same visual language carry capabilities and purchasing decisions.

## Writing

Earnest, humanist and technically direct. Big statements sound like a manifesto; supporting copy names concrete mechanisms rather than decorating the claim with hype.

**Do not copy:** Do not reuse Nous or Hermes names, emblems, characters, slogans, artwork, mission claims, leadership claims, adoption claims, prices, plan allowances, hiring counts or quoted culture statements. Source examples illustrate form only.

- **Addressing the reader:** Use we for institutional purpose and you/your for product outcomes. Capability descriptions often use the product as the subject, with direct verbs and clear operational detail.
- **Rhythm:** Very short category labels and two-to-six-word headings alternate with compact one- or two-sentence explanations. A product promise can break into three short lines; actions are usually two to four words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A monumental proper name, or a short relationship-centered promise in the product variant. | 2–7 words | “[Brand]”<br>“The Agent That Grows With You” |
| Chapter headline | Active proposition linking a technical field to a larger human outcome. | 3–7 words | “Advancing Human Rights and Freedoms”<br>“Persistent Memory” |
| Supporting line | Name the operations, then explain the durable benefit. | 15–40 words | “It learns your projects, auto-generates skills, and never forgets how it solved a problem.” |
| Primary action | A direct verb with a specific destination or operation. | 2–4 words | “Read Mission”<br>“Download for macOS” |
| Question | Plain user concern phrased as a real question. | 4–10 words | “Does my agent keep its data between sessions?” |

**Words and phrasing to use:** build; learn; create; access; experience; projects; research; memory; tools; your

**Avoid:** magical; game-changing; revolutionary platform; supercharge everything; effortless excellence

**Rules:**

- Use expansive language only for the purpose; use concrete nouns and mechanisms for the product.
- Make technical descriptions understandable without stripping out operational detail.
- Keep action labels task-specific rather than repeating Get started everywhere.
- Use uppercase as a visual label treatment, not as the default voice of paragraphs.

## Do's and Don'ts

### Do

- Keep the default headline near 304px/1 on the 1080px desktop stage.
- Use 13px/1.5 body text for compact institutional chapters.
- Keep default actions rectangular with 3px corners and 47px height.
- Retain 45px paper gutters around a major blue chapter band.
- Use 20px copy-stack gaps and 60px chapter vertical padding.
- Put interface views on saturated blue textured backing with no conventional elevation.
- Let the footer remain a blue field with four narrow directory columns.
- Separate date captions at 13.5px/1 with 0.04em tracking from update prose.

### Don't

- Do not replace the narrow display family with a wide geometric bold grotesk.
- Do not introduce orange, mint or purple feature-card accents into the two-ink palette.
- Do not round action corners into 9999px pills or enlarge every action into a banner.
- Do not turn the editorial rail into uniformly boxed, shadowed cards.
- Do not increase every paragraph to 18px; the small copy is part of the scale contrast.
- Do not make the construction diagram as dark as the central emblem.
- Do not put thick colored borders around every plan; its emphasis is typographic.
- Do not apply translucency or blur to final footer links; keep those readable over the ghost lettering.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color, box-shadow, color and transform transitions at 0.15s cubic-bezier(0, 0, .2, 1), with active scale 0.98.
- Some media declare opacity/filter transitions of 1.27s ease; the desktop frame declares a 42s ease-in-out infinite bloom.
- The closing scene uses a sticky reveal beneath the foreground paper content.

**Transfer:**

- Keep button motion small and mechanical; let slow perimeter light and the closing reveal carry the atmospheric movement.

**Unknown:**

- The exact scroll triggers, full artwork animation sequences and final reveal timings are not established.

### Responsive

**Observed:**

- The desktop perimeter is hidden below the medium layout threshold.
- The institutional root scale uses clamp(14px, 7px + 0.5vw, 18px).
- The product-entry grid declares a two-column intermediate layout; plan markup declares two columns before the medium four-column layout.

**Transfer:**

- For narrow layouts, retain the monumental narrow-letter silhouette with fit-to-width sizing; stack art and copy instead of shrinking body text.
- Reduce paper gutters before compressing the internal text stacks. Preserve the full blue closing field while stacking directory groups.

**Unknown:**

- Exact mobile spacing, navigation interaction and art placements are not established; these narrow-screen adaptations are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
