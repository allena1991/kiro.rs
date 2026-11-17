# Slash — serif in the shadows

## Overview

A cinematic, predominantly black style that pairs an expressive editorial serif with compact, practical grotesk text. Silver objects, smoked glass, charcoal interfaces and restrained champagne light give business software a physical, premium presence. Spacious narrative chapters alternate with dense but orderly product proof, making the style well suited to sophisticated tools and service platforms.

### Essentials

- Editorial promises interrupt the darkness: white IvyPresto at weight 400, 64px/1.05 in the opening and up to 88px/1 in chapter headings, with +0.01em tracking and a meaningful phrase in true italic.
- The opening is a product still life, not a dashboard billboard: a 900px-tall black stage carries left-aligned copy, a compact email action and an oblique, dramatically lit object filling the right and lower field; proof logos sit along the bottom.
- Conversion controls are nested bright inserts: the opening uses a 400×48px rounded-10px email shell and a white 40px-high, 6px-radius button; centered product and closing forms use a 520×60px pill with a 48px-high white pill inside.
- Color behaves like reflected light rather than branding paint: nearly the whole page remains black, charcoal, white and gray; gold is reserved for short numerical proof, small material highlights and warm closing atmosphere. Saturated colors stay within product illustrations.
- Capabilities live inside nocturnal display cases: 10px corners, 12px or 24px grid gaps, dark diagonal gradients and faint masked rim lighting; artwork fills the upper field and short captions settle at the bottom.
- Every new landing page carries both a low-key object scene and a textured warm-horizon conversion moment: use a simple tilted interface plane with a silver rim if physical media is unavailable, and a black-to-#2e2a26 grainy band with a 64px serif call to action. Place these devices wherever the narrative needs them, without fixing the section order.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brushed gold | `#ae9357` | `--color-gold` | accent, text | Metallic numerical proof gradient, not broad interface fills. |
| Champagne highlight | `#fff0cc` | `--color-gold-light` | accent, text | Narrow bright stop in metallic numerical proof. |
| Amber reflection | `#cd8939` | `--color-amber` | accent | Blurred light beneath metric numerals. |
| Copper annotation | `#cc9166` | `--color-copper` | link, accent | Editorial categories and keyboard focus outlines, not primary button fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White light | `#ffffff` | `--color-white` | text, action, accent | Headlines, important labels and solid conversion controls; also the source of translucent edge lighting. |
| Pale silver | `#e2e3e9` | `--color-label` | text, action | Light announcement links and small luminous action surfaces. |
| Feature silver | `#c7c9d1` | `--color-list` | text | Plan feature lists. |
| Cool silver text | `#acafb9` | `--color-body` | text | Main supporting paragraphs. |
| Slate text | `#9194a1` | `--color-muted` | text, border | Secondary copy, footer navigation and outlined plan buttons. |
| Distant gray | `#777a88` | `--color-subtle` | text | Metadata, dates and quieter captions. |
| Recessed gray | `#5e616e` | `--color-faint` | text | Low-priority disclosures and reading-time captions. |
| Control outline | `#464853` | `--color-control-edge` | border | Small outlined navigation action. |
| Graphite edge | `#2e3038` | `--color-edge` | border, surface | Navigation lower rule, opening form outline and announcement base. |
| Warm charcoal | `#2e2a26` | `--color-horizon` | background | Bottom of warm atmospheric conversion bands. |
| Fine division | `#1c1d22` | `--color-rule` | border, surface, text | FAQ separators, comparison structure and dark lettering inside white pills. |
| Charcoal face | `#121317` | `--color-panel` | surface | Light end of display-case gradients and raised dark cards. |
| Carbon underside | `#0b0c0e` | `--color-panel-deep` | surface | Dark end of display-case gradients; 50% over the canvas gives the footer its approximately #08080a appearance. |
| Almost black | `#040406` | `--color-canvas` | background | Default page canvas and the opaque base under atmospheric media. |
| Absolute black | `#000000` | `--color-black` | background, text | Metric-band backing, vignette shadows and opening button lettering. |

## Typography

- **__ivyPresto_6eafe2** — Promises, chapter headings, selected italic words and editorial quotations. High-contrast display serif with tapered strokes, sharp details and an expansive, calligraphic italic. If unavailable, use **Bodoni Moda**. Use weight 400 with +0.01em tracking; preserve the italic word changes and adjust wrapping to keep similar line lengths. Font stack: "__ivyPresto_6eafe2", "Bodoni Moda", Georgia, serif.
- **__Inter_d8ebd1** — Navigation, supporting copy, controls, captions and numerical proof. Neutral contemporary grotesk; compact tracking and light-to-medium weights keep detailed information subordinate to the serif. Font stack: "__Inter_d8ebd1", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| chapter | __ivyPresto_6eafe2 | 400 | 88px | 1 | 0.01em | Most monumental chapter promise, usually balanced across two lines. |
| chapter-italic | __ivyPresto_6eafe2 | 400 italic | 88px | 1 | 0.01em | One emphasis word inside the monumental chapter promise. |
| chapter-relaxed | __ivyPresto_6eafe2 | 400 | 88px | 1.125 | 0.01em | Longer monumental chapter heading needing extra separation. |
| display | __ivyPresto_6eafe2 | 400 | 64px | 1.05 | 0.01em | Default cinematic opening headline. |
| heading | __ivyPresto_6eafe2 | 400 | 64px | 1 | 0.01em | Standard capability and FAQ section heading. |
| heading-italic | __ivyPresto_6eafe2 | 400 italic | 64px | 1 | 0.01em | Emphasis phrase in a standard capability heading. |
| closing-heading | __ivyPresto_6eafe2 | 400 | 64px | 1.125 | 0.01em | Centered conversion promise and spacious section leads. |
| heading-small | __ivyPresto_6eafe2 | 400 | 52px | 1.125 | 0.01em | Customer proof, security and inline plan introductions. |
| quote | __ivyPresto_6eafe2 | 400 | 44px | 1.375 | 0.01em | Standalone centered editorial quotation; an italic clause can use the identical recipe in italic. |
| metric | __Inter_d8ebd1 | 500 | 44px | 1.125 | -0.02em | Metallic proof-band numerals. |
| question | __Inter_d8ebd1 | 500 | 24px | 1.375 | -0.04em | FAQ question rows. |
| lead | __Inter_d8ebd1 | 400 | 20px | 1.5 | -0.02em | Section support line, normally constrained to two or three lines. |
| body | __Inter_d8ebd1 | 400 | 18px | 1.375 | -0.02em | Opening support and alternating feature paragraphs. |
| card-title | __Inter_d8ebd1 | 500 | 18px | 1.375 | -0.02em | Short capability label, frequently inline with its explanation. |
| card-copy | __Inter_d8ebd1 | 300 | 18px | 1.375 | -0.02em | Lightweight explanation within compact capability cases. |
| small | __Inter_d8ebd1 | 400 | 16px | 1.375 | -0.02em | Compact card paragraphs and footer links. |
| pill-button | __Inter_d8ebd1 | 600 | 16px | 1.5 | normal | White action within centered email pills. |
| button | __Inter_d8ebd1 | 600 | 15px | 1 | -0.02em | Opening conversion action and wide plan actions. |
| nav | __Inter_d8ebd1 | 400 | 14px | 1 | normal | Compact top-level navigation labels. |
| nav-action | __Inter_d8ebd1 | 500 | 14px | 1.5 | normal | Outlined navigation conversion action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| centered product and pricing openings | product-display | __ivyPresto_6eafe2 | 400 | 72px | 1.125 | 0.01em | Centered two-line product promise, with a selected phrase in true italic. |
| plan comparisons | price | __Inter_d8ebd1 | 500 | 48px | 1 | -0.0067em | Plan prices. |
| alternating product explanations | feature-heading | __ivyPresto_6eafe2 | 400 | 40px | 1.125 | 0.01em | Heading beside a single illustration. |
| product walkthroughs | sidebar-heading | __ivyPresto_6eafe2 | 400 | 32px | 1.125 | 0.01em | Compact heading beside a large product interface. |
| company narratives | timeline-year | __Inter_d8ebd1 | 500 | 28px | 1 | -0.04em | Year marker beside historical photographs. |
| plan comparisons | feature-list | __Inter_d8ebd1 | 400 | 15px | 1.375 | -0.02em | Plan checklist details. |
| editorial recommendations | category | __Inter_d8ebd1 | 600 | 13px | 1 | -0.02em | Copper editorial category. |

**Notes:**

- Serif tracking is positive at +0.01em even when the letters appear closely fitted; do not substitute negative display tracking.
- Use real serif italic for semantic emphasis, not a different color, bold weight or a cursive script. Match its size and line height to the surrounding serif.
- Sans text generally uses -0.02em; prominent question rows tighten further to -0.04em. Keep navigation and centered pill actions at normal tracking.
- The hierarchy changes scale more than weight: the largest serif remains 400 while practical labels use 500 or 600.

## Layout

**Density:** Airy chapters with compact details: major promises have long black breathing spaces, while card captions and comparison rows remain tightly packed.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Short card heading-to-copy separation and icon-to-label gaps. |
| 12px | Tight display-case grids. |
| 14px | Footer link row gaps and plan checklist spacing. |
| 16px | Editorial image-to-metadata gap and ordinary text grouping. |
| 20px | Opening copy-stack gap. |
| 24px | Three-column grid gaps and capability-card internal padding. |
| 32px | Container side padding and gap before centered conversion forms. |
| 48px | Gap from section support to capability grids; footer column gaps. |
| 64px | Large split-layout gap and spacing before proof media. |
| 112px | Standalone quotation vertical padding and compact product chapter entry. |
| 144px | First proof-section entry and timeline item separation. |
| 160px | Warm conversion band bottom padding. |
| 224px | Default large chapter entry space. |

### Containers and grids

- **main-container**: max width 1216px · side padding 32px. Centered desktop shell; the inner content width is 1152px at a 1440px viewport.
- **narrative-container**: max width 1024px · side padding 32px. Centered 960px inner field for plan comparisons, founder photography and explanatory video.
- **chapter-heading**: max width 832px. Balanced central two-line monumental serif title.
- **support-column**: max width 576px. Centered support paragraphs beneath capability headings.
- **capability-grid**: 3 columns · gap 24px. Three 368px-wide display cases across the main inner container.
- **foundation-grid**: 2 columns · gap 12px. Two equal feature cases followed by a full-width case; for larger feature stories.
- **faq-split**: gap 64px. Left title and contact line beside a 640px question list; align both at the top.
- **footer-grid**: 5 columns · gap 48px. Five compact navigation groups to the right of a small wordmark.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | display cases | 10px |
|  | opening button | 6px |
|  | conversion pills | 9999px (pill) |
|  | story panels | 12px |
| editorial recommendations | editorial thumbnails | 8px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page field.

**CSS:** `background: #040406; color: #ffffff`

**Observed:** Sections usually share the same canvas instead of being divided into alternating colored stripes.

**Transfer:** Use space, type scale and media to separate chapters.

#### Display case · level 1

**Use:** Feature artwork and product proof.

**CSS:** `background: linear-gradient(201deg, #121317 13.96%, #0b0c0e); border-radius: 10px; overflow: hidden`

**Observed:** The case is nearly as dark as the canvas. A separate rim layer gives it a faint top-lit edge; the artwork itself supplies most of the depth.

**Transfer:** Frame a purposeful miniature product scene rather than inserting a white interface rectangle.

#### Masked rim · level 2

**Use:** Thin reflective edge over display cases.

**CSS:** `border: 1px solid rgba(255,255,255,0.6); border-radius: 10px; mix-blend-mode: overlay; mask-image: linear-gradient(#ffffff, rgba(0,0,0,0)); pointer-events: none`

**Observed:** The edge fades toward the bottom and reads as reflected light rather than a bright white outline.

**Transfer:** Apply on an inset absolute overlay, not to the caption text.

#### Navigation glass · level 3

**Use:** Fixed navigation backing.

**CSS:** `background: rgba(4,4,6,0.7); backdrop-filter: blur(40px); border-bottom: 1px solid #2e3038`

**Observed:** A slim translucent bar remains above the dark scenes.

**Transfer:** Keep the backing dark enough for tiny white navigation text.

#### Warm horizon · level 0

**Use:** Atmospheric conversion and occasional quantified proof band.

**CSS:** `background: linear-gradient(rgba(0,0,0,0), #2e2a26)`

**Observed:** The band warms subtly toward its base, with fine grain emerging downward rather than a sharply bounded colored panel.

**Transfer:** Use the warm-horizon build recipe; preserve a black top so it joins the page seamlessly.

#### Footer carbon · level 0

**Use:** Site navigation and disclosure ending.

**CSS:** `background: rgba(11,12,14,0.5); padding-top: 40px; padding-bottom: 32px`

**Observed:** A near-black continuation with navigation first, then a utility strip and a long ruled disclosure field.

**Transfer:** Use the same tonal restraint even when the destination product has fewer legal requirements.

## Components

### Navigation

**Use:** Persistent global wayfinding.

**CSS:** `height: 64px; display: flex; align-items: center; justify-content: space-between; padding: 0px 32px; max-width: 1216px`

**Text style:** `nav` — __Inter_d8ebd1 400 · 14px/1

**Observed:** A small white wordmark anchors the left, short category links sit centrally, and sign-in plus the Navigation action sit at the right. Small chevrons mark menus. A separate 36px announcement strip sits above.

**Transfer:** Keep the horizontal links concise and let the hero remain visually dominant.

### Navigation action

**Use:** Small always-available conversion.

**CSS:** `height: 32px; padding: 0px 14px; border: 1px solid #464853; border-radius: 9999px; color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `nav-action` — __Inter_d8ebd1 500 · 14px/1.5

**Observed:** Outlined and visually weaker than the white conversion controls in the page.

**States:** Declared: hover border-color hsl(229 8% 60%/1); focus-visible outline 2px with 2px offset in #cc9166.

### Primary button

**Use:** Default cinematic opening form action.

**CSS:** `height: 40px; padding: 0px 32px; background: #ffffff; color: #000000; border-radius: 6px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — __Inter_d8ebd1 600 · 15px/1 · tracking -0.02em

**Observed:** A bright inset control sits flush inside the dark email shell rather than floating as a detached oversized CTA.

**States:** Declared: hover background-color hsl(228 10% 80%/1); focus-visible outline 2px with 2px offset in #cc9166.

### Opening email shell

**Use:** Compact inline email conversion beneath opening support.

**CSS:** `height: 48px; max-width: 400px; border-radius: 10px; border: 1px solid #2e3038; background: rgba(28,29,34,0.6); display: flex; align-items: center; gap: 12px`

**Observed:** An email field fills the left side, with the Primary button inset by 4px on the right. The label is visually hidden and the short prompt is visible inside the field.

**Transfer:** Keep this rectangular shell for cinematic left-aligned openings; use the Email pill for centered compositions.

### Email pill

**Use:** Centered conversion in product openings and warm closing bands.

**CSS:** `height: 60px; max-width: 520px; border-radius: 9999px; background: linear-gradient(135deg, rgba(255,255,255,0.08), rgba(255,255,255,0.02)); border: 1px solid rgba(255,255,255,0.1); display: flex; align-items: center`

**Observed:** The email field flexes on the left with 24px left padding. A Pill action is nested on the right, inset by 8px. A thin white-alpha highlight fades across the top.

**Transfer:** Use a real labeled email input and keep prompt and action on the same visual track.

### Pill action

**Use:** White control inside Email pill.

**CSS:** `height: 48px; padding: 0px 24px; background: #ffffff; color: #1c1d22; border-radius: 9999px; margin-right: 8px`

**Text style:** `pill-button` — __Inter_d8ebd1 600 · 16px/1.5

**Observed:** The bright insert is sized to its label, leaving most of the shell for the input.

**States:** Declared: hover background-color hsl(230 12% 90%/1); focus-visible outline 2px with 2px offset in #cc9166; active transform returns to scale 1.

### Capability case

**Use:** A short capability paired with a product illustration.

**CSS:** `position: relative; background: linear-gradient(201deg, #121317 13.96%, #0b0c0e); overflow: hidden; border-radius: 10px`

**Text style:** `card-title` — __Inter_d8ebd1 500 · 18px/1.375 · tracking -0.02em

**Observed:** Artwork dominates the upper field; bottom-aligned caption combines a white medium-weight label and a gray lightweight explanation, often as one paragraph. Three-column cases are 368×418px with 24px caption insets. The clickable wrapper can have 2px corners while its visible rim retains 10px corners.

**Transfer:** Use one concept per scene, retaining a readable caption zone instead of filling every corner with UI.

### Question row

**Use:** FAQ accordion item.

**CSS:** `border-bottom: 1px solid #1c1d22; padding: 22px 0px; display: flex; justify-content: space-between; text-align: left; color: #ffffff`

**Text style:** `question` — __Inter_d8ebd1 500 · 24px/1.375 · tracking -0.04em

**Observed:** A restrained downward chevron aligns at the far right. The label can wrap naturally within a 544px text width. The final item drops the lower rule.

**Transfer:** Keep question wording direct; let the left section introduction remain outside the accordion.

### Footer link

**Use:** Grouped navigation at the end of the page.

**CSS:** `color: #9194a1; display: flex; align-items: center; gap: 6px; border-radius: 2px`

**Text style:** `small` — __Inter_d8ebd1 400 · 16px/1.375 · tracking -0.02em

**Observed:** Links stack at 14px gaps under a white 16px medium group label. They do not sit in individual cards.

**States:** Declared: hover color white; focus-visible outline 2px with 2px offset in #cc9166.

### Editorial card

**Only for:** editorial recommendations

**Use:** Scrollable resource recommendations.

**CSS:** `width: 340px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `category` — __Inter_d8ebd1 600 · 13px/1 · tracking -0.02em

**Observed:** A 340×192px image with 8px corners precedes copper category and uppercase gray date, then a white title and subdued reading time. Cards extend beyond the right edge; circular 36px arrows sit by the section introduction.

**Transfer:** Use coherent dark still-life thumbnails with one warm highlight, rather than unrelated bright stock photography.

### Plan action

**Only for:** plan comparisons

**Use:** Contrasting conversion controls in a two-plan comparison.

**CSS:** `height: 44px; padding: 0px 40px; border: 1px solid #9194a1; border-radius: 9999px; color: #ffffff`

**Text style:** `button` — __Inter_d8ebd1 600 · 15px/1 · tracking -0.02em

**Observed:** The entry plan uses the outlined action; the higher plan uses a white fill with dark text. Both span their 384px text column.

**States:** Declared: hover border-color hsl(228 10% 80%/1), light background and dark text; focus-visible outline 2px with 2px offset in #cc9166.

## Imagery and graphics

### Cinematic object stage

**Use:** Signature opening visual.

**Observed:** A nearly monochrome phone and silver payment card rest diagonally on a rough concrete plinth. The object occupies the right and lower majority, lit with soft diagonal beams and small specular reflections; edges disappear into black. The image is full-bleed behind the copy, not inside a visible browser frame.

**Transfer:** Stage a relevant physical tool, a device displaying the new interface or a simple tilted interface plane on a dark textured slab. The minimum version still needs one convincing oblique object, a soft silver edge and deep black negative space behind copy.

**Build:** Use a full-bleed black stage with the object grouped to the lower right. Layer two broad diagonal white-alpha light wedges behind it, blur their edges, and put a black radial vignette over the perimeter. Fade the bottom into #040406 with a vertical gradient. On a CSS-built substitute, rotate a dark rectangular plane in perspective, add a 1px translucent white rim, a soft charcoal slab underneath and a low-opacity white reflection across one edge.

### Luminous product miniatures

**Use:** Inside Display case and Capability case.

**Observed:** Floating transaction chips, stacked metal cards, small charts and glass shields are rendered in smoky charcoal with sparse gold, blue, violet or green interface accents. Soft bloom and grain make them feel like photographed objects. Text is small and subordinate; the scene fills roughly the upper two thirds of its case.

**Transfer:** Select only the interface fragment that proves the capability. Render it as a small floating surface with controlled rim light, not a full dense app screen on every card.

**Build:** Stack two or three dark planes with a small offset; use a faint white top border and black soft shadow, then place one radial white or champagne-alpha glow behind the focal feature. Blur the glow by 30–64px and keep the caption zone dark. Add fine low-opacity monochrome noise over the artwork.

### Metallic numerical proof

**Use:** Short horizontal metric band and a single dominant metric beside a quote.

**Observed:** Sans numerals carry a brushed-gold horizontal gradient, with a blurred amber glow underneath and modest gray labels. The standard band uses 44px numerals; the single-metric quote variant rises to 68px.

**Transfer:** Use verified figures belonging to the new product and keep surrounding labels short. Include metallic numerical proof as a concentrated highlight, not gold across every heading.

**Build:** Clip a 103deg gradient to the numeral: #ae9357, #fff0cc at 40%, #ae9357 at 70%, then rgba(189,157,79,0). Put a roughly 167×44px vertical amber gradient behind its lower half, transparent until 23.5%, ending at #cd8939, with blur(64px) and plus-lighter blending.

### Warm grain horizon

**Use:** Signature atmospheric conversion device.

**Observed:** A broad black-to-warm-charcoal field carries a central white serif promise, a short silver sentence and one bright action. Fine grain is most visible toward the bottom; there is no literal landscape or colorful sunset.

**Transfer:** Always retain this atmospheric device somewhere in a new landing page. It can hold a conversion, a major proof statement or a short invitation.

**Build:** Make a full-width field around 600px high. Blend transparent black downward into #2e2a26; add a tiled monochrome noise layer at 100px tile scale and opacity 0.3, masked from invisible at the top to visible at the bottom. Keep content on an independent foreground layer with 224px top and 160px bottom space.

### Human business proof

**Use:** Customer story cards and explanatory video.

**Observed:** Real people and workplaces retain restrained natural color: warehouse aisles, desks, workshop activity and founder interviews. Story cards darken strongly toward the bottom for names and quotations; large video is framed at 960×540px with softly rounded edges.

**Transfer:** Photograph customers in their own working environment. Let ambient warm browns and cool grays remain, and use dark overlays only where text needs contrast.

### Company documentary

**Only for:** company narratives

**Use:** Opening photograph, alternating timeline and leadership portraits.

**Observed:** A 960×540px candid office photograph opens the story. Historical images alternate across a thin central timeline, with 384px-wide photos opposite year-and-copy blocks; square 222px portraits form a four-column team row.

**Transfer:** Use authentic working moments and consistently framed headshots. Keep the photographs warmer and more human than the product scenes.

### Material family tiles

**Only for:** related-product cross-sells

**Use:** Three compact neighboring offering tiles.

**Observed:** A silver frosted panel, a gold glowing panel and a deep charcoal panel sit side by side. Each carries a small outlined icon in a glass circle at top left and a bottom-aligned white title with short support.

**Transfer:** Use these as a deliberately limited material family rather than assigning a new saturated color to every offering.

**Build:** Use 320×299px rounded-10px tiles. Layer a broad desaturated silver or champagne radial glow toward the upper center over charcoal, add fine monochrome grain, and darken the bottom for the caption. Place a 44px white-alpha glass circle with a 1px rim at top left.

### Network globe

**Only for:** international or network product openings

**Use:** Right-hand symbolic object opposite left-aligned product copy.

**Observed:** A gold-gray dotted globe floats on black with thin elliptical orbit paths, tiny luminous nodes, flag badges and dark rail labels. It is restrained and dimensional, not a flat colorful map.

**Transfer:** For another networked product, render its topology as a sparse dotted sphere or orbital cluster while preserving dark space around the copy.

**Build:** Use an SVG dotted sphere with density reduced near its edges, three thin elliptical orbits at different rotations and a soft gold-alpha radial glow behind it. Place a few circular nodes on the paths; keep labels in small dark pills and avoid an all-over star field.

### Icons

**Observed:** Small utility chevrons and arrows are generally 14–16px, fine round-capped outlines around 1–2px in white or muted gray. Capability symbols can be 24–30px and sit inside glass circles; social marks are compact solid white silhouettes.

**Transfer:** Use a consistent fine-stroke icon set. Reserve glass circular holders for offering tiles and symbolic product nodes rather than every text label.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A full-width 900px black stage contains the Navigation glass below a 36px announcement strip. Copy is left aligned inside the main container, beginning in the upper quarter beneath the header: a small translucent review badge, a single-line 64px serif promise, an 18px support paragraph occupying about 400px and the Opening email shell. The phone-and-card still life dominates the right and lower field, while a diagonal pool of light leaves copy in deep shadow. Layers run from black backing to object imagery, vignette and bottom fade, then copy and controls. At the bottom of the first 900px a 14px proof sentence and subdued monochrome logo strip are visible. The next customer chapter starts below the fold.

**Transfer:** Preserve the asymmetry and editorial confidence for an unrelated product: make a single product object feel tangible and large, leaving the upper-left copy field uncluttered. Without physical media, build the tilted-interface alternative in Cinematic object stage. Centered product openings instead use a 72px two-line promise above Email pill and a broad sculptural object below; network-product openings split a 64px title and an orbital illustration. Company narratives use a left title above candid photography; pricing introductions place two plans under a centered promise.

**Avoid:** Do not replace the scene with a centered white dashboard screenshot, make the headline fill the whole viewport, or push proof and all product imagery below the first screen.

**Text style:** `display` — __ivyPresto_6eafe2 400 · 64px/1.05 · tracking 0.01em

### Editorial chapter lead

**Observed:** A 224px chapter entry introduces a centered serif title at 64px or a monumental 88px. A meaningful phrase switches to italic while staying white. Supporting Lead copy occupies a 576px column and sits about 24–28px below the heading; a 42–48px gap leads into cases.

**Transfer:** Write a short conceptual promise and italicize the word that changes its meaning. Use the monumental version for a broad chapter and the standard version for a focused capability.

**Text style:** `chapter` — __ivyPresto_6eafe2 400 · 88px/1 · tracking 0.01em

### Display-case mosaic

**Observed:** Display case, Masked rim and Capability case form a hierarchy of two broad cases with a full-width follow-up, three equal cases, or a mixed-width tools mosaic. The 1152px field uses 12px gaps for the tight mosaic and 24px for the three-up row; captions sit at the bottom over dark artwork.

**Transfer:** Choose a grid based on the relative importance of the new capabilities. Keep the visual scene and its label together rather than separating icons into a generic feature list.

### Customer proof gallery

**Observed:** A left-aligned 52px serif introduction precedes photographic story cards by 64px. One 578×350px card expands beside two 263×350px cards. Dark lower overlays hold a small avatar and attribution; short outcome figures and a story link can sit beneath the wide card. The cinematic carousel variant centers a 928×522px image with neighboring panels peeking in, an overlaid 32px quotation and a small white story action.

**Transfer:** Use real working environments and let one story receive clear visual priority. Keep both attribution and an action legible without whitening the photograph.

### Quotation and metallic proof

**Observed:** An 832px-wide centered 44px serif quotation gets 112px vertical padding, with an italic clause, restrained attribution and dot controls. A separate black strip concentrates gold-gradient numerals and short labels. A product-specific alternative places one 68px gold metric beside a 32px sans quote on Warm horizon.

**Transfer:** Use a short authentic quote plus numerical proof; scale the single-stat variant only when the figure merits a whole composition.

### Objection split

**Observed:** A 64px serif title and 20px contact sentence sit on the left of a 640px column of Question rows with a 64px gap. The heading wraps into a compact two-line block. Product variants use 224px above and below the section; a closing conversion may precede the FAQ rather than follow it.

**Transfer:** Group the practical objections on the right and keep a human contact escape route on the left.

**Text style:** `heading` — __ivyPresto_6eafe2 400 · 64px/1 · tracking 0.01em

### Warm conversion

**Observed:** Warm horizon and Warm grain horizon carry a centered 64px/1.125 serif promise, a 20px support sentence after 24px, and Email pill after 32px. The section gives 224px of entry space and 160px of exit space. Company and dedicated pricing variants replace the email shell with a small luminous pill action and subtle glow.

**Transfer:** Use an actionable promise tied to a credible low-friction next step, not a vague inspirational slogan.

**Text style:** `closing-heading` — __ivyPresto_6eafe2 400 · 64px/1.125 · tracking 0.01em

### Carbon ending

**Observed:** After the conversion or FAQ, Footer carbon begins with a small wordmark and five columns of grouped navigation. Links use 16px type and 14px vertical gaps. A utility row places copyright and preferences opposite social icons and an app badge. A 1px divider precedes dense muted 14px/21px disclosures, arranged in paragraphs with 24px gaps. All page types keep this layered ending rather than stopping at the marketing CTA.

**Transfer:** Retain navigation, utility and disclosure as distinct bands. Adjust disclosure length to the new business while keeping its hierarchy visibly quieter than the marketing content.

### Split explanation

**Only for:** product walkthroughs

**Observed:** A large interface illustration sits beside a compact 32px serif title and ruled feature list. Later alternating rows use 40px serif headings, 18px support, a 64px gap and roughly equal text/media columns. A 960×540px explanatory video can follow a centered heading with 48px separation.

**Transfer:** Explain one workflow at a time. Alternate the image side and use brief text, rather than turning every row into another three-card grid.

### Plan comparison

**Only for:** plan comparisons

**Observed:** The embedded variant uses a left-aligned 52px serif heading and two unboxed 384px plan columns separated by 192px in a 960px field. Each plan presents name, 48px price, support, Plan action and check list. Dedicated pricing uses dark 438×566px Display cases with smoky grain and a restrained gold premium label, then a long feature matrix with 50px rows and compact plan-header actions.

**Transfer:** Keep entry and premium options structurally comparable. Use the open embedded version on ordinary landing pages and the boxed plus matrix version for a detailed pricing destination.

### Documentary timeline

**Only for:** company narratives

**Observed:** A centered serif chapter title precedes alternating two-column image and year-copy rows. A thin center line with small metallic 12px nodes holds the narrative together. Rows use a 128px column gap and approximately 144px separation; a later four-column portrait row gives names and roles a modest sans treatment.

**Transfer:** Use this for a true origin or evolution story, adapting the count to meaningful milestones rather than filling a preset timeline.

### Press material wall

**Only for:** company reputation sections

**Observed:** A 72px serif heading tops a three-column wall of 304×185px dark textured panels with 24px gaps and 10px corners. Each contains one centrally placed silvery media mark, not a bright multicolor collage.

**Transfer:** Unify legitimate third-party recognition through monochrome material treatment and equal optical scale.

## Page flow

**Storyline:** Promise and tangible product scene → human or numerical trust → capability chapters and workflow proof → commercial or comparative clarity → invitation and objection handling → navigational and disclosure ending.

### Broad platform marketing

1. **Promise** — Cinematic opening with a compact email action and bottom proof logos.
2. **Social proof** — Unequal photographic customer gallery.
3. **Capability chapters** — Large italic-accented promises alternate with display-case mosaics.
4. **Quantified proof** — Editorial quote followed by metallic numerical highlights.
5. **Risk reduction** — Security illustration and accordion, open two-plan comparison and partner marks.
6. **Objection handling** — Split FAQ followed by a dark editorial recommendation rail.
7. **Closing call** — Warm grain conversion band, then the carbon navigation, utility and disclosure ending.

**Transfer:** Borrow the alternation between cinematic emotion and practical proof; shorten chapters without dropping the signature object and warm-horizon devices.

### Company credibility and recruiting narrative

1. **Introduction** — Left-aligned serif title over candid office photography and three restrained sans metrics.
2. **Conviction** — A compact mission quotation mixing sans with an italic serif phrase.
3. **Credibility** — Monochrome backer marks.
4. **Origin story** — Alternating documentary timeline.
5. **Human proof** — Portrait row and customer quotations.
6. **External recognition** — Three-column press material wall.
7. **Closing call** — Warm-horizon recruiting invitation and small luminous action, then full carbon ending.

**Transfer:** Use human imagery and a genuine origin story rather than reproducing the sales-page case grid throughout.

### Commercial decision support

1. **Promise** — Centered serif opening with a small proof badge and email pill.
2. **Pricing** — Two dark plan cards, distinct outline and filled actions, then a muted logo strip.
3. **Detailed comparison** — Long categorized ruled feature matrix with compact plan headers.
4. **Closing call** — Warm-horizon invitation and small action, then full carbon ending.

**Transfer:** Keep the plans easy to compare and let the larger matrix do the detailed work below.

### Focused product acquisition

1. **Promise** — Centered two-line serif promise, email pill and broad curved arrangement of metal cards.
2. **Capability chapters** — Three illuminated feature cases.
3. **Social proof** — Wide photographic quote carousel with peeking neighbors.
4. **Product proof** — Two focused interface cases and a three-tile related-offering material family.
5. **Pricing** — Open two-column comparison.
6. **Closing call** — Warm email conversion band.
7. **Objection handling** — Split FAQ before full carbon ending.

**Transfer:** Lead with a distinctive sculptural product arrangement and give the most important controls visible demonstrations.

### Workflow and differentiation for a specialized audience

1. **Promise** — Left-aligned serif promise beside an orbital globe, small overlapping badges, email pill and proof logos.
2. **Product demonstration** — Large dashboard beside a compact ruled feature list, then alternating explanations.
3. **Explanation** — Centered wide founder video.
4. **Quantified proof** — Single gold-gradient figure beside a testimonial on warm atmosphere.
5. **Differentiation** — Dark luminous comparison panel with thin row rules.
6. **Closing call** — Warm email conversion band.
7. **Objection handling** — Expanded split FAQ and full carbon ending.

**Transfer:** Use the split workflow structure to make unfamiliar concepts understandable before asking readers to compare alternatives.

## Writing

Assured, contemporary and practical, with a small amount of editorial flourish in the headline. The promise is broad but the supporting language quickly becomes concrete about capabilities, effort saved and control gained.

**Do not copy:** Do not reuse the Slash name, wordmark, proprietary artwork, customer or investor marks, quotations, financial claims, plan prices, statistics, regulated claims or testimonials. All new claims and figures must belong to the new product and be independently supportable. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your in benefits and controls. The product is usually named in support copy; we is used naturally in company narrative and customer quotations.
- **Rhythm:** Short editorial headline fragments alternate with one-sentence explanations. Use parallel capability labels, brief imperative actions and straightforward questions; avoid exclamatory sales patter.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a desired reduction in friction or a capability built for a particular outcome; emphasize one decisive phrase in italic. | 3–10 words | “[Brand] the friction”<br>“Corporate cards built for complete control” |
| Chapter heading | Pair a plain structural phrase with a meaningful descriptive word. | 4–8 words | “A strong financial foundation”<br>“Coupled with intelligent tools” |
| Support | One sentence naming tangible functions and the practical advantage. | 12–25 words | “Complete any banking task in just a few clicks.”<br>“High cashback, detailed spend insights, and controls and automation to save hours of work.” |
| Capability caption | A short declarative label followed immediately by a plain explanation. | 2–5 word label; 10–25 word explanation | “Sophisticated spend controls.”<br>“Create distinct money "pools" for better tracking.” |
| Action | Clear verb and immediate next step; no theatrical metaphor. | 2–3 words | “Get Started”<br>“Start for Free”<br>“Read Story” |
| Closing promise | Make the next step feel short and achievable with a concrete commitment. | 6–10 words | “Apply in less than 10 minutes today” |
| Question | Use the customer's natural practical concern. | 5–14 words | “Can I set spend controls on corporate cards?” |

**Words and phrasing to use:** control; modern; built for; real-time; unified; granular; seamless; transparent; your business

**Avoid:** revolutionary magic; game-changing ecosystem; crush your goals; limitless possibilities; excessive exclamation marks

**Rules:**

- Let the headline carry the flourish and the next sentence carry the specifics.
- Use concrete verbs such as create, send, manage, automate and track.
- Pair broad claims with functional proof rather than more adjectives.
- Keep typography emphasis semantic: italicize the key modifier or outcome, not random decorative words.
- Write captions as small useful explanations, not miniature marketing speeches.

## Do's and Don'ts

### Do

- Keep the main canvas #040406 and headlines white; let material highlights supply warmth.
- Use serif weight 400 and +0.01em tracking for large promises.
- Give major chapters 224px entry space while keeping case caption padding around 24px.
- Use a 1216px shell with 32px side padding and a 1152px inner media field.
- Preserve the nested conversion structure: 400×48px rectangular shell in the cinematic opening, 520×60px pill in centered conversion moments.
- Make rim lighting a separate 1px masked overlay so the case fades into black at the bottom.
- Reserve metallic gold for short quantified proof and concentrated object reflections.
- Keep real people and workplaces visibly human through restrained natural color.

### Don't

- Do not turn the whole neutral ramp into just black and white; supporting copy needs #acafb9, #9194a1 and quieter metadata grays.
- Do not give every card a thick solid white outline; the 60% white rim blends in overlay and fades.
- Do not use gold as a primary button fill or turn the warm horizon into an orange banner.
- Do not make every headline bold sans; the 400-weight display serif is the visual anchor.
- Do not round all controls to the same shape: the cinematic opening action has 6px corners while centered actions are pills.
- Do not put every paragraph in white; white belongs to promises, labels and high-priority controls.
- Do not enlarge small UI accent colors into section backgrounds.
- Do not end immediately after the CTA; preserve the navigation, utility and muted disclosure hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Declared action color transitions commonly use 0.15s cubic-bezier(0.4,0,0.2,1); nested pill actions use all 0.2s and glass/form backing uses 0.3s.
- Declared logo marquees run 45s linear infinite.
- Declared hero entry uses 0.8s cubic-bezier(.25,.46,.45,.94), with 80ms stagger increments and a reduced-motion disabling class.
- Customer gallery declarations include flex, opacity, filter and aspect-ratio transitions at 0.7s cubic-bezier(0,0,0.2,1).

**Transfer:**

- Keep interactive color changes brief and material-focused rather than adding springy movement to all cards.
- If the proof-logo rail moves, keep it a slow continuous monochrome marquee.
- Preserve static readable copy and a convincing product still when motion is reduced.

**Unknown:**

- Exact product-scene video sequencing, scroll-trigger timing and full interactive carousel behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 400px, 500px, 536px, 640px, 768px, 1024px, 1280px and 1536px.
- The page has a declared 340px minimum width. Responsive classes reduce major chapter headings to 36px and centered product promises to 40px at the smallest tier.
- Responsive classes make the capability rail scroll-snap horizontally before the desktop three-column grid and hide the dashboard's side feature column below the wide layout.

**Transfer:**

- Recommended adaptation: preserve the object stage but move the object beneath or behind the shorter text block so the dark text-clear region survives.
- Recommended adaptation: stack FAQ introduction above questions and reduce documentary timeline to a readable single sequence.
- Keep the email shell and nested action coherent; reduce type and padding before letting the button consume the input area.

**Unknown:**

- Mobile compositions, menu expansion, exact fluid sizing between breakpoints and touch behavior were not visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
