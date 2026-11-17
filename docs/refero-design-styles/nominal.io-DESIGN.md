# Nominal — instrumented momentum

## Overview

An engineering-led style that moves between bright drafting-table compositions and black, atmospheric technical stages. Regular grotesk headlines and compact monospaced markings give complex products an assured, operational character. Monochrome object illustrations, real working environments and large interface views carry the narrative, with sparse green signals and dense information held inside expansive ruled layouts.

### Essentials

- Headlines behave like plainspoken engineering promises: muoto at 72px/1.1, weight 400 and -0.01em tracking in the opening; section titles at 52px/1.1 and -0.03em, never bold display lettering.
- The opening is an instrumented white stage beneath a 65px black navigation bar: a left-aligned headline occupying roughly two thirds of the width, a diagonal black object illustration, fine telemetry frames and a faint 48px drafting grid.
- Controls look like equipment labels: square corners, 1px outlines, 41px button height, 12px 16px padding and 11px/1.35 bold uppercase mono text; invert the outline and text for black sections.
- Color belongs to operational signals and real media, not decorative marketing fills: black and white dominate whole sections, with #357f46 reserved for status or selected technical paths. Photographs and interface charts supply most other hue.
- Technical imagery breaks out of its text column: large square-edged interface views and monochrome illustrated objects sit against grayscale gradients, while 1px rules connect text, media and captions into a common frame.
- Atmosphere and moving markings are signature devices: include grainy monochrome diagonal light fading to black, and a clipped horizontal ribbon mixing 64px sans statements with 32px uppercase mono phrases and a square pause control. Without specialist artwork, use layered SVG light bands, a schematic product object and honest product data.
- Proof is presented as an operating record: a wide dark photographic stage, a raised outline tab, divided copy and quote columns, and 104px weight-200 numbers with smaller plus signs. The ending returns to a 64px closing promise, stacked outline actions, a ruled directory and a 66px identity ribbon.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#357f46` | `--color-green` | accent, surface, border | Online indicators, selected category frames and technical connectors; keep the occupied area small. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Drafting white | `#ffffff` | `--color-white` | background, text, border, action | Light stages, dark-stage text and fine white frames. |
| Stage black | `#000000` | `--color-black` | background, text, border | Dark canvas, text on white and light-theme outlines. |
| Control ink | `#121212` | `--color-near-black` | text | Text on the solid white application action. |
| Translucent charcoal | `#1a1a1a` | `--color-panel` | surface | Visible white at 10% over black, used for dark media panels and hover washes. |
| Metal dark | `#2e2e2e` | `--color-metal-dark` | surface | Upper end of grayscale interface backing gradients. |
| Light-stage secondary text | `#595959` | `--color-muted-light` | text, border | Supporting paragraphs and quiet labels on white. |
| Half-white edge | `#808080` | `--color-rule` | border | Visible 50% white over black for thin panel dividers; also 50% black over white in light tables. |
| Dark-stage secondary text | `#848484` | `--color-muted-dark` | text, border | Subdued body text and directory separators on black. |
| Metal light | `#e5e5e5` | `--color-metal-light` | surface | Lower end of grayscale interface backing gradients. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product case-study result grids | Metric frame gray | `#737885` | `--color-metric-edge` | border | Thicker edges around customer result cells. |
| industry-specific landing pages | Warm application canvas | `#edebe4` | `--color-warm-paper` | background | Warm end of the white-to-paper opening gradient and problem chapter. |

## Typography

- **muoto** — Headlines, paragraphs, quotes and result numerals. Contemporary grotesk with open counters, a generous x-height and restrained regular-weight display forms. If unavailable, use **Inter**. Use weights 200–400 and preserve the measured tracking. Font stack: "muoto", "Inter", Arial, sans-serif.
- **fraktionMono** — Navigation, controls, technical annotations, metadata and ribbons. Compact engineered monospace with utilitarian capitals and clear numerals. If unavailable, use **IBM Plex Mono**. Use 400 and 700; avoid adding wide tracking. Font stack: "fraktionMono", "IBM Plex Mono", ui-monospace, monospace.
- **Inter** — Large sans phrases in horizontal statement ribbons. Neutral sans that contrasts with compressed mono statements. Font stack: "Inter", ui-sans-serif, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat | muoto | 200 | 104px | 1 | normal | fixed | Large proof numerals, with a separate smaller plus sign. |
| display | muoto | 400 | 72px | 1.1 | -0.01em | size clamp(48px, 5vw, 72px) | Default white-stage opening promise. |
| closing | muoto | 400 | 64px | 1 | -0.03em | fixed | Monumental closing promise; also the photographic company opening. |
| ribbon-sans | Inter | 400 | 64px | 1.5 | normal, uppercase | fixed | Oversized sans words interspersed with mono phrases in statement ribbons. |
| heading-lg | muoto | 400 | 52px | 1.1 | -0.03em | fixed | Major section titles and split product-stage headings. |
| heading | muoto | 400 | 36px | 1.1 | -0.02em | fixed | Chapter leads and architecture row headings. |
| ribbon-mono | fraktionMono | 400 | 32px | 0.93 | -0.013em, uppercase | fixed | Compact two-line phrases in statement ribbons. |
| card-title | muoto | 400 | 24px | 1.2 | -0.02em | fixed | Feature and editorial card titles. |
| lead | muoto | 300 | 21px | 1.3 | normal | fixed | Opening supporting paragraph. |
| body-lg | muoto | 400 | 19px | 1.3 | normal | fixed | Product chapter explanations and wide supporting copy. |
| body | muoto | 400 | 16px | 1.3 | normal | fixed | Feature descriptions and directory support. |
| eyebrow | fraktionMono | 400 | 14px | 1.35 | normal, uppercase | fixed | Section categories and technical labels. |
| nav | fraktionMono | 700 | 14px | 1.35 | normal, uppercase | fixed | Navigation and prominent short technical headings. |
| action | fraktionMono | 700 | 11px | 1.35 | normal, uppercase | fixed | Buttons, fine annotations and file tabs. |
| caption | fraktionMono | 400 | 11px | 1.35 | normal, uppercase | fixed | Attributions, directory categories and fine metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| industry-specific landing pages | industry-display | muoto | 400 | 72px | 1 | -0.03em | fixed | Short industry-plus-product opening title. |
| product case-study result grids | result | muoto | 300 | 40px | 1.1 | -0.03em | fixed | Short results within a framed metric matrix. |
| company credibility sections | quote | muoto | 400 | 24px | 32px | -0.02em | fixed | White-stage customer quotations. |
| recruitment listings | listing-title | muoto | 400 | 24px | 1.2 | -0.05em | fixed | Recruitment listing names. |
| company and recruitment pages | company-lead | muoto | 300 | 18px | 1.3 | normal | fixed | Support over photography and recruitment opening copy. |
| recruitment listings | listing-meta | fraktionMono | 400 | 14px | 1.35 | -0.05em, uppercase | fixed | Locations and work arrangement metadata. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Large headlines stay regular-weight; the strongest contrast comes from scale, not boldness.
- The default opening has looser tracking than the 52px section titles. Keep the distinction rather than imposing one tracking token across the scale.
- Mono text is uppercase but normally untracked. The tightly tracked recruitment metadata is a scoped exception.
- Do not turn interface text into the marketing type scale; treat embedded product views as a separate visual system.

## Layout

**Density:** Airy at chapter scale, compact within the technical content: large stage transitions surround tightly stacked labels, rules and descriptions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small heading-support and metadata gaps. |
| 12px | Card title-to-copy gaps and button vertical padding. |
| 16px | Button side padding and small card content gaps. |
| 20px | Editorial grid gutters and directory column separation. |
| 24px | Result cell padding and secondary grid gutters. |
| 32px | Default page side gutters, framed chapter padding and feature image-to-title spacing. |
| 36px | Product title, paragraph and action separation. |
| 48px | Opening support-to-action rhythm. |
| 64px | Opening headline inset and feature grid separation. |
| 72px | Closing area top padding and substantial media-panel inset. |
| 80px | Large chapter breathing space. |
| 112px | Statement ribbon vertical padding. |
| 144px | Editorial section lead-in. |
| 192px | Atmospheric architecture-stage lead-in. |
| 200px | Separation beneath company team and leadership chapters. |

### Containers and grids

- **container**: max width 1728px · side padding 32px. Centered full-width marketing wrapper; 1376px of working width at a 1440px viewport.
- **opening container**: max width 1728px · side padding 64px. Inset headline and supporting-copy frames in the default opening.
- **feature grid**: 3 columns · gap 12px. Three detailed feature cards under a large product chapter.
- **editorial grid**: 3 columns · gap 20px. Equal-width editorial and capability cards; approximately 445px each at desktop.
- **split stage**: 2 columns · gap 0px. Text and technical media joined by a central hairline rather than a floating card gutter.
- **directory**: 2 columns · gap 20px. Half-width link groups below three full-width product summary columns.

## Corner radius

| Element | Radius |
| --- | --- |
| controls and frames | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| interface lift | `rgba(0, 0, 0, 0) 0px 114.2px 32.2px 0px, rgba(0, 0, 0, 0.01) 0px 72.8px 28.8px 0px, rgba(0, 0, 0, 0.05) 0px 40.6px 24.5px 0px, rgba(0, 0, 0, 0.09) 0px 18.6px 18.6px 0px, rgba(0, 0, 0, 0.1) 0px 4.2px 10.2px 0px` | Restrained downward lift inside large product-interface frames, not on every content card. |

### Surfaces

#### Black stage · level 0

**Use:** Atmospheric technical chapters and the shared ending.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** True black, not a blue-black application shell.

**Transfer:** Use black as a full chapter canvas.

#### White drafting stage · level 0

**Use:** Opening and detailed product chapters.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Large clean white planes with straight rules and open margins.

**Transfer:** Switch whole bands to white rather than placing white cards over a dark page.

#### Drafting grid · level 1

**Use:** Faint geometry behind the opening object.

**CSS:** `background-image: linear-gradient(90deg, rgba(128, 128, 128, 0.145) 1.5px, rgba(0, 0, 0, 0) 0px), linear-gradient(rgba(128, 128, 128, 0.145) 1.5px, rgba(0, 0, 0, 0) 0px); background-size: 48px 48px; transform: skew(30deg)`

**Observed:** The grid recedes and fades around the object; the title remains on a solid white plane.

**Transfer:** Mask an oversized grid toward the stage edges, keeping paragraph contrast clear.

#### Interface backing · level 1

**Use:** Large screen presentations on light chapters.

**CSS:** `background: linear-gradient(#2e2e2e 0%, #e5e5e5 100%); border: 1px solid #ffffff; border-radius: 0px`

**Observed:** A narrow metallic grayscale frame supports a square interface view.

**Transfer:** Use behind genuine product views, not as a general card fill.

#### Dark translucent panel · level 1

**Use:** Dark media groupings.

**CSS:** `background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.5); border-radius: 0px`

**Observed:** Thin light edges keep the panel attached to its black technical stage.

**Transfer:** Use sparingly where several media items need a common backing.

#### Warm industry stage · level 0

**Only for:** industry-specific landing pages

**Use:** Opening and problem framing.

**CSS:** `background: linear-gradient(#ffffff 0%, #edebe4 100%); color: #000000`

**Observed:** The gradient settles into a warm paper band below the opening.

**Transfer:** Keep the warm alternative restricted to a focused application narrative.

## Components

### Fixed navigation

**Use:** Persistent global wayfinding.

**CSS:** `position: fixed; z-index: 50; height: 65px; background: #000000; color: #ffffff`

**Text style:** `nav` — fraktionMono 700 · 14px/1.35 · uppercase

**Observed:** White symbol and wordmark at left, centered product/company menus with small down triangles, compact documentation links and two right-aligned actions. The app action is solid white; the demo action is outlined.

### Light outline button

**Use:** Default action on white stages.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #000000; border-radius: 0px; padding: 12px 16px; height: 41px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — fraktionMono 700 · 11px/1.35 · uppercase

**Observed:** Short centered uppercase label; ordinary chapter actions fit their text while the opening action sits in a 204px-wide wrapper.

**States:** Declared: hover background-color #0000001a; focus-visible not specified; active background-color #1212121a.

### Dark outline button

**Use:** Actions on black chapters and in navigation.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid #ffffff; border-radius: 0px; padding: 12px 16px; height: 41px`

**Text style:** `action` — fraktionMono 700 · 11px/1.35 · uppercase

**Observed:** The same square construction is repeated as a narrow stacked pair in the closing call and as wide half-row actions at the directory bottom.

**States:** Declared: hover background-color #ffffff1a; focus-visible not specified; active background-color #fff3.

### Solid app button

**Use:** High-contrast application entry in the black header.

**CSS:** `background: #ffffff; color: #121212; border: 1px solid #ffffff; padding: 12px 16px; height: 41px; border-radius: 0px`

**Text style:** `action` — fraktionMono 700 · 11px/1.35 · uppercase

**Observed:** Pairs with the outlined conversion action rather than replacing every button.

**States:** Declared: hover border-color and background-color #eaeaea; focus-visible not specified; active border-color and background-color #fff.

### Feature card

**Use:** Detailed capability explanation below a product chapter.

**CSS:** `display: flex; flex-direction: column; gap: 32px; padding-bottom: 12px; background: #ffffff; border-radius: 0px`

**Text style:** `card-title` — muoto 400 · 24px/1.2 · tracking -0.02em

**Observed:** Landscape product image above a heading and paragraph; title-to-description gap is 12px. Three cards share the chapter width, without independent rounded outer shells.

**Transfer:** Show a different concrete task in each image; use body text for the explanation.

### Directory row

**Use:** Ruled navigation in the shared ending.

**CSS:** `display: flex; flex-direction: column; justify-content: center; height: 48px; padding-right: 40px; border-top: 1px solid #848484`

**Text style:** `nav` — fraktionMono 700 · 14px/1.35 · uppercase

**Observed:** Broad rows align with neighboring link columns; fine category captions distinguish groups from destinations.

**States:** Declared: hover background-color #ffffff1a; focus-visible not specified.

### Statement ribbon

**Use:** A signature typographic interruption between chapters.

**CSS:** `background: #000000; color: #ffffff; padding: 112px 0px; position: relative; overflow: hidden`

**Text style:** `ribbon-mono` — fraktionMono 400 · 32px/0.93 · tracking -0.013em · uppercase

**Observed:** Clipped edge-to-edge horizontal sequence combines large sans words, compact mono statements and technical symbols; a square pause button sits near the edge. A white variant belongs to recruitment and investor narratives.

**Transfer:** Write a short operating belief and repeat it with small schematic symbols rather than making a conventional logo carousel.

### Editorial card

**Use:** Related stories and proof links.

**CSS:** `display: flex; flex-direction: column; gap: 32px; border-radius: 0px`

**Text style:** `card-title` — muoto 400 · 24px/1.2 · tracking -0.02em

**Observed:** A fine half-white top rule, uppercase category, 445px by 287px landscape media, title and a short body line. Cards appear three across with 20px gutters.

**States:** Declared: hover background-color #ffffff1a; focus-visible not specified.

### File tab photo

**Only for:** recruitment culture galleries

**Use:** Candid culture imagery presented as a working archive.

**CSS:** `position: relative; background: #000000; border: 2px solid #ffffff; padding: 4px; border-radius: 0px`

**Text style:** `action` — fraktionMono 700 · 11px/1.35 · uppercase

**Observed:** A black filename tab projects 28px above the upper-left edge, outlined like the image frame. Two columns of natural-color photos sit in a translucent charcoal panel with 24px gutters.

**Transfer:** Use real working moments with brief filename-like captions, not polished testimonial cards.

### Listing row

**Only for:** recruitment listings

**Use:** Dense categorized role directory.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 32px 24px; border-bottom: 1px solid rgba(0, 0, 0, 0.5); background: #ffffff; border-radius: 0px`

**Text style:** `listing-title` — muoto 400 · 24px/1.2 · tracking -0.05em

**Observed:** A quarter-width category rail borders a three-quarter-width list. Each roughly 148px row holds a title and two uppercase metadata lines, with locations separated by slashes.

**Transfer:** Group listings by function and preserve the long shared category rail instead of repeating it in each card.

## Imagery and graphics

### Instrumented object illustration

**Use:** The opening's main visual anchor.

**Observed:** A large black racing object in diagonal three-quarter perspective sits across the white stage. Fine white contour lines describe the body; framed speed, lap and route readouts surround it. The object occupies much of the lower and right half while leaving the top-left headline unobstructed.

**Transfer:** Use the new product's central physical object or a simplified system assembly. For a software-only product, make a schematic of its main object and connect it to two or three honest operational readouts.

**Build:** Draw an SVG silhouette from a three-quarter view using solid black shapes and thin white contour paths. Place it diagonally over the faded 48px grid. Add 1px gray rectangular data cells at upper right and a small route or process-path frame at lower right; keep all annotations monospaced and monochrome.

### Grainy monochrome light

**Use:** Signature atmosphere over black architecture and product stages.

**Observed:** Soft white light sweeps diagonally through a granular charcoal field, brightest near the upper edge and disappearing into true black below. It resembles illuminated brushed fabric rather than a colored glow.

**Transfer:** Preserve the diagonal direction, granular material and black fade; exact light stops are not essential.

**Build:** Layer three broad white-to-transparent SVG ribbons rotated about -30 degrees over black, vary their opacity between 0.1 and 0.5, and soften with 24px blur. Overlay low-opacity monochrome feTurbulence noise and a transparent-to-black vertical gradient. Keep the lower text region predominantly black.

### Technical system diagram

**Use:** System overview and integration chapters.

**Observed:** Orthogonal light-gray connectors join thin rectangular node frames on a faint 32px square grid. Green dashed paths and small green node marks identify the active system; lower label strips read like terminal captions.

**Transfer:** Reduce a new system to a few legible nodes and one emphasized route rather than placing a full architecture document on the page.

**Build:** Use an SVG with 1px neutral orthogonal paths, four to six square node frames, small mono footer strips and one green dashed connector. Back with two 1px rgba(128,128,128,0.19) gradients at 32px intervals, masked toward the edges.

### Product views

**Use:** Large demonstrations and smaller feature illustrations.

**Observed:** Desktop interfaces are square-edged, legible and oversized, sometimes extending beyond a chapter's text frame. Both dark analysis views and white control views appear. Small chart colors stay within the product, while grayscale backing and subtle downward shadows separate the view from the page.

**Transfer:** Use a real task-oriented interface or a faithful simplified view of the new product. Retain enough controls, plots or data to demonstrate a workflow rather than replacing it with an abstract empty window.

### Operational photography

**Use:** Proof, application and service chapters.

**Observed:** Real machines, vehicles, labs and people at work. Dark proof imagery uses deep black space and directional highlights; service imagery forms a full-width sequence of tall photographs with natural lighting and little decorative grading.

**Transfer:** Photograph the environment where the product delivers value. Keep machinery and working context visible, with wide dark breathing room when text overlays the image.

### Company portrait and archive

**Only for:** company and recruitment pages

**Use:** Human credibility and culture.

**Observed:** Founders use large color portraits on pale neutral backings; leadership uses compact grayscale headshots in a ruled matrix. Culture photos retain candid color and use the File tab photo construction.

**Transfer:** Separate formal role identification from informal working moments; keep the frames rectangular.

### Dotted operational globe

**Only for:** company location sections

**Use:** Global footprint alongside location records.

**Observed:** A large black globe with white dotted landmasses and brighter location points fills the left half. A subtle rim glow separates it from black; ruled location records occupy the right half with green online badges.

**Transfer:** Use only when geographic presence is meaningful; a network footprint can serve the same role for a distributed product.

**Build:** Clip a regular white dot pattern to simplified landmass paths inside a circular SVG, compress dots toward the sphere edge and add a faint white blurred rim. Place larger white points at real locations; keep all other geography black.

### Icons

**Observed:** Mostly small monochrome SVG symbols: 16px control icons with 2px round strokes, compact filled navigation triangles and square outlined pause controls. Technical diagrams use simple centered glyphs inside node frames.

**Transfer:** Choose utilitarian arrows, pause marks and system symbols. Use black on white or white on black, with green limited to active technical states.

## Section recipes

How recurring sections are built.

### First screen: Instrumented white opening

**Observed:** A 65px fixed black Fixed navigation caps an 836px white stage. The display headline is left aligned in a solid white upper panel inset 64px, with a 672px text measure inside a frame spanning roughly two thirds of the working width. Below it, the lead paragraph sits in a ruled left panel, with a Light outline button below. Behind these panels, a faint drafting grid and the diagonal Instrumented object illustration spread across the lower center and right; telemetry sits at upper right and a route panel at lower right. Small square down and pause controls anchor the lower-left edge. Within the first 900px the complete headline, support, action, object and controls are visible; the next dark overview chapter starts below the fold.

**Transfer:** Keep the collision of a calm text plane and an active technical object. Replace the object and readouts with a simplified assembly, process map or product model using the new product's own data. A focused product opening instead splits white text and a huge interface stage about equally, using heading-lg and a low-anchored action; an industry opening gives roughly three fifths to the object and two fifths to text. Company storytelling opens with full-bleed work photography and closing-size white text; recruitment uses a white text panel beside a tall candid photograph.

**Avoid:** Do not center the headline above a small floating device, or use a stock colored dashboard as the entire hero background. The object must not cover the support copy or primary action.

**Text style:** `display` — muoto 400 · 72px/1.1 · tracking -0.01em

### Atmospheric architecture overview

**Observed:** Grainy monochrome light crosses a Black stage above two equal columns joined by a vertical rule. A heading-lg and body paragraph fill the left; the Technical system diagram fills the right, with a square pause control near the outer edge. The atmosphere has about 192px of lead-in before the framed content.

**Transfer:** Explain how a new product connects its parts, using a small number of clearly labeled system nodes.

### Alternating product chapter

**Observed:** A White drafting stage with 40px top and 64px bottom padding contains a product label, heading-lg, body-lg and Light outline button in one half; a large Product view with Interface backing crosses the other half. A three-column Feature card row follows after 64px. A neighboring chapter reverses the media/text direction.

**Transfer:** Use for major product capabilities; choose a single concrete workflow for the large view, then show supporting tasks below.

### Ruled architecture ledger

**Observed:** On a Black stage with Grainy monochrome light, an eyebrow and large title introduce wide horizontal rows. A narrow left column uses heading and muted body-lg text; wider right columns contain deployment, integration or data-flow graphics inside shared 1px frames.

**Transfer:** Use for trust, integration and operational objections. Make the diagrams explain real deployment choices rather than decorative badges.

### Tabbed proof stage

**Observed:** A heading-lg and Dark outline button sit above a large outlined photographic stage. The active logo tab rises from the frame, with other tabs subdued. A wide dark object photo anchors the center; divided lower columns carry result copy, a quote, attribution and stat numerals. White fine rules and overlaid black fades maintain legibility.

**Transfer:** Adapt to customer evidence with one real image, a verifiable result, an attributed quote and a small number of meaningful metrics. Preserve the tabbed frame even if the proof library is short.

### Monumental closing and directory

**Observed:** Every page ends on a Black stage. An eyebrow precedes an 800px-wide closing headline, with two small outline actions stacked 8px apart below and 56px square partner links to the right. A broad identity-art region precedes the small brand mark and directory. Three product summaries span the top of a two-column directory, followed by ruled 48px links and two wide outline actions. A 66px-high bottom ribbon mixes symbols, short mono beliefs and larger identity/copyright words, with a square pause control.

**Transfer:** Retain the large closing promise, broad identity gesture, structured directory and bottom ribbon. Use an original word or symbol composition for the new identity region; adapt the directory to the new information architecture.

**Text style:** `closing` — muoto 400 · 64px/1 · tracking -0.03em

### Framed result matrix

**Only for:** product case studies

**Observed:** A white split chapter places category, heading-lg, action and three ruled explanatory rows at left. A wide operational photograph sits at right above a two-by-two result grid. Each 408px by 139px cell uses 24px padding, a small label and a result-sized value with an icon; shared edges are 4px metric gray.

**Transfer:** Reserve for compact, verified case-study results.

**Text style:** `result` — muoto 300 · 40px/1.1 · tracking -0.03em

### Company credibility ledger

**Only for:** company pages

**Observed:** White sections pair a narrow eyebrow rail with a wider heading and copy column. Three quote columns use a left rule, a boxed quotation mark, quote text and small attribution. Team portraits follow in three columns; leadership entries become compact ruled headshot cells. Press entries are horizontal ruled title rows with an action aligned right.

**Transfer:** Use the editorial rail and ruled records to organize trust material without turning it into a wall of identical cards.

### Recruitment archive and directory

**Only for:** recruitment pages

**Observed:** A dark atmospheric chapter places a short team statement over a right-heavy Dark translucent panel containing File tab photos in two columns. The page then switches to white for a heading, talent-network link, 32px filter controls and categorized Listing rows. Selected filters invert to black.

**Transfer:** Use candid culture material to create interest, then make the listing portion deliberately functional and dense.

## Page flow

**Storyline:** Promise → visible system or product → task-level capabilities → operational credibility → customer or editorial proof → monumental closing and functional directory.

### Broad platform marketing

1. **Promise** — White instrumented object stage with a concise outcome promise.
2. **System explanation** — Dark atmospheric overview with a connected-node diagram.
3. **Capability chapters** — Alternating white product demonstrations with three supporting feature cards each.
4. **Operational credibility** — A moving workflow ribbon, application-media selector and ruled deployment ledger.
5. **Social proof** — Tabbed photographic customer record with large numerals and attributed quote.
6. **Human support** — Full-width field-work photo sequence with mono service statements.
7. **Closing call** — Large promise, stacked actions, broad identity region, directory and bottom ribbon.

**Transfer:** Borrow the transitions between tangible object, usable software and real-world proof without requiring the same chapter count.

### Focused product landing

1. **Product promise** — White text panel beside an oversized interface on a dark atmospheric backing.
2. **Value reinforcement** — Mixed-type technical ribbon.
3. **Product demonstration** — Dark feature selector and large task view with ruled explanation rows.
4. **Quantified proof** — White customer case study and framed metric matrix.
5. **Ecosystem connection** — Atmospheric split product cross-link.
6. **Further proof** — Three related-story cards.
7. **Closing call** — Shared closing, directory and identity ribbon.

**Transfer:** Lead with one clear product view and explain the task before customer results.

### Industry application landing

1. **Application promise** — Warm-paper stage with oversized monochrome object and a short paired title.
2. **Problem framing** — Warm split editorial composition followed by a two-column pain-point grid.
3. **Capability explanation** — Black introduction and three-column illustrated capability records.
4. **Outcome reinforcement** — White illustrated split section with a compact action and supporting claims.
5. **Related proof** — Editorial cards and two product cross-links.
6. **Closing call** — Shared closing, directory and identity ribbon.

**Transfer:** Translate the use environment into the main object and problem language, keeping the warmer visual variant confined to the application story.

### Company credibility

1. **Mission** — Full-bleed working-environment photography behind large white text.
2. **Customer credibility** — White three-column quotation ledger.
3. **Team credibility** — Large portraits followed by compact leadership cells.
4. **Operating footprint** — Dotted globe and live-style location records.
5. **Institutional credibility** — White partner ribbons and ruled press records.
6. **Further reading** — Editorial cards and product cross-links.
7. **Closing call** — Shared closing, directory and identity ribbon.

**Transfer:** Choose the credibility records appropriate to the new organization rather than reproducing its exact institutional story.

### Recruitment

1. **Invitation** — White statement beside tall candid work photography.
2. **Culture** — Mono statement ribbon and dark file-tab photo archive.
3. **Actionable directory** — White role index with filter row, category rail and long metadata-rich listings.
4. **Closing call** — The same commercial closing, directory and identity ribbon used elsewhere.

**Transfer:** Keep recruitment imagery and archive devices scoped to hiring while preserving the shared brand ending.

## Writing

Direct, technically literate and ambitious without playful salesmanship. Claims attach speed and confidence to specific tasks, real workflows and operational outcomes.

**Do not copy:** Do not reuse Nominal's name, wordmark, partner identities, product names, proprietary illustrations, customer quotations, funding claims or performance figures. Source examples illustrate sentence construction only; create truthful names, proof and claims for the new product.

- **Addressing the reader:** Product descriptions usually name the product and its users; imperatives address the reader's task directly. Company and recruitment narratives use we and us more freely.
- **Rhythm:** Short outcome headlines alternate with dense explanatory paragraphs. Parallel verbs and paired time contrasts create momentum; compact action labels stay functional.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Repeat an active verb across two short outcome clauses. | 4–9 words | “Accelerate test. Accelerate progress.” |
| Section title | Name the capability or contrast slow setup with fast work. | 5–12 words | “Set up test stands in minutes, not months”<br>“Enterprise-grade security and scale” |
| Supporting copy | Explain what runs where, what it does and why the user benefits. | 2–4 concrete sentences | “Deploy test stands in minutes, not months. Connect runs at the edge, reading from and writing to instruments in real time.” |
| Action | Plain verb and destination, no conversational flourish. | 2–5 words | “Request Demo”<br>“Read case study” |
| Closing promise | Link progress toward a meaningful goal to speed. | 6–10 words | “Achieve your milestones and mission, faster.” |
| Recruitment invitation | State the shared belief, then invite collective action. | 8–13 words | “Progress depends on test. Let's accelerate together.” |

**Words and phrasing to use:** accelerate; execute; analyze; collect data; control; operate; real-time; reliable; resilient; collaborative; in minutes, not months; where the work happens

**Avoid:** magic; effortless revolution; game-changing; supercharge everything; delightful little; unlimited possibilities

**Rules:**

- Lead with the task and outcome; introduce technical mechanisms immediately after.
- Use specific nouns and operational verbs instead of abstract transformation language.
- Keep technical specificity appropriate to the new product; jargon must explain a real capability.
- Attach metrics to a clear baseline, time frame and credible attribution.
- Use the mono labels as terse categories, not miniature marketing paragraphs.

## Do's and Don'ts

### Do

- Keep display headlines at weight 400 and 72px/1.1, with the 52px section scale clearly subordinate.
- Use 32px standard page gutters and 64px headline insets for the default opening.
- Join technical content with 1px rules instead of separate floating containers.
- Include a monochrome atmospheric light treatment and a clipped typographic ribbon as brand devices.
- Use 41px square-corner actions with 11px uppercase mono labels.
- Keep technical card grids at 12px gutters and editorial grids at 20px.
- Give proof numerals the 104px weight-200 treatment when they carry the section.
- Finish with the large closing line, functional ruled directory and identity ribbon.

### Don't

- Do not replace true black with navy or violet to make the dark stages feel like generic software marketing.
- Do not turn operational green into a full-width brand background or a gradient headline.
- Do not add pill corners to the 41px controls or round interface frames.
- Do not make every paragraph monospaced; prose belongs in the grotesk family.
- Do not shrink the main product view to a small decorative thumbnail beside a huge empty text column.
- Do not apply heavy elevated-card shadows to feature and editorial grids; reserve lift for framed interface media.
- Do not use 104px numerals inside the compact case-study matrix; its scoped result recipe is 40px.
- Do not replace the ruled footer directory with a minimal logo-and-legal strip.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare all 0.3s cubic-bezier(.4,0,.2,1) transitions; directory and editorial hover transitions declare 0.3s ease-in-out.
- Pause controls are provided for the opening object, diagram, rotating media, globe and horizontal ribbons.
- Comparison tabs declare focus-visible outline-color white and outline-offset -2px.

**Transfer:**

- Keep moving technical scenes paired with square pause controls.
- Animate diagram connectors and ribbons without changing the strong still composition or obscuring copy.

**Unknown:**

- Exact object, light, globe and ribbon animation timing and autoplay behavior are unspecified.

### Responsive

**Observed:**

- The opening display declares a desktop clamp of 48px to 72px at 5vw; its narrow rule is clamp(20px, 8vw, 48px).
- Layouts declare breakpoints including 640px, 768px, 960px, 1024px, 1280px, 1536px and 1728px.
- Desktop navigation is shown at the 1280px tier. Feature cards declare horizontal snapping in narrower layouts; the large footer identity-art region is hidden below the medium tier.

**Transfer:**

- On narrow layouts, keep the title on an opaque text plane and move the main object beneath rather than allowing telemetry to overlap text.
- Collapse the quarter-width category rail above its listings; preserve the ruled record structure.
- Preserve horizontal clipping and a usable pause control on ribbons rather than wrapping them into a paragraph.

**Unknown:**

- Exact mobile navigation appearance and settled mobile compositions are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
