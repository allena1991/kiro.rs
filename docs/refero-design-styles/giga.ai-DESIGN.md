# Giga — spectral instruments at work

## Overview

A technical, cinematic style that makes software feel like a physical instrument. Scan-lined monospace headlines and tiny equipment labels sit against black, with orange keys, spectral light and convincingly weighted interface objects. Human photography softens the engineering atmosphere; the overall density is sparse outside the demonstrations. It suits ambitious enterprise products, with a warmer silver-and-paper variant for people-focused stories.

### Essentials

- Headlines look electronically drawn rather than typeset in a conventional grotesk: Geist Pixel Line, weight 400, 72px/64px in the opening and 52.6px/58px for major chapters.
- The first screen is a lit instrument stage: an 1100×470px two-part object sits below a left headline and right 19px support paragraph, over full-bleed spectral color and vertical light seams.
- Actions feel like little physical keys: orange diagonal gradients, 8px corners, 44px height, 11px uppercase mono labels, bright inset edges and stacked downward shadows.
- Color behaves like illumination, not a page-wide theme: reserve the strongest spectrum for the opening and localized halos; the long-form marketing canvas and expansive ending stay black.
- Product media has material weight: 12px framed demonstrations, fine pale edges, recessed black glass, warm silver plates and realistic directional shadows. Use a purpose-built interactive panel when no product media exists.
- Small industrial markings and human proof coexist: 11px/14px mono eyebrows with an 8px orange square, vignetted real-world photography, and compact 15px proof numerals beside the speaker rather than giant statistic billboards.
- End with an isolated conversion instrument and a wide black utility footer: a 540×52px recessed email well with a faint spectral halo, followed by four link columns, circular trust marks and a tiny green status lamp.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Key top | `#f7732b` | `--color-orange-light` | action | Upper-left stop of the orange key. |
| Key bottom | `#dd520c` | `--color-orange-dark` | action | Lower-right stop of the orange key. |
| Orange signal | `#ef5a00` | `--color-signal` | accent | Eyebrow squares, small indicators and focus accents. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White light | `#ffffff` | `--color-white` | text, accent | Opening type and specular highlights. |
| Warm keycap | `#f2f1ec` | `--color-warm-white` | surface | Pale Continue key in the instrument demonstration. |
| Cool white | `#e8edef` | `--color-heading` | text | Major section headings and footer link source color. |
| Soft silver text | `#acafb1` | `--color-body` | text | Support copy: rgba(232,237,239,0.74) over black. |
| Detail gray | `#a3a3a3` | `--color-detail` | text | Dense explanatory text: white at 0.64 over black. |
| Dim gray text | `#858585` | `--color-muted` | text | Quote base and captions: white at 0.52 over black. |
| Graphite key top | `#3b3b3e` | `--color-key-top` | action | Secondary-key gradient start. |
| Graphite sheen | `#2e2e30` | `--color-panel-top` | surface | Selector panel upper gradient. |
| Graphite key bottom | `#2a2a2d` | `--color-key-bottom` | action | Secondary-key gradient end. |
| Graphite panel | `#272729` | `--color-panel` | surface | Material base of the horizontal selector panels. |
| Graphite shade | `#1f1f21` | `--color-panel-bottom` | surface | Selector panel lower gradient. |
| Dark hairline | `#1f1f1f` | `--color-edge` | border | White at 0.12 over black, used for separators and key outlines. |
| Keycap ink | `#1f1d1b` | `--color-warm-ink` | text | Text on the pale instrument key. |
| Glass upper | `#141517` | `--color-well-top` | surface | Email well upper stop. |
| Faint panel edge | `#141414` | `--color-faint-edge` | border | White at 0.08 over black for panel boundaries. |
| Glass lower | `#030405` | `--color-well-bottom` | surface | Email well lower stop. |
| Black stage | `#000000` | `--color-canvas` | background | Default long-form canvas and universal footer. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Status green | `#46c97d` | `--color-status` | accent | Tiny operational lamp, not a broad success fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| builder-style product pages | Warm night | `#0f0d0d` | `--color-night` | background | Warmer background for paired capability-card narratives. |
| culture and recruiting pages | Silver wall | `#e8e6e4` | `--color-silver` | background | Warm silver base under vertically folded lighting. |
| culture and research galleries | Research paper | `#f7f5f0` | `--color-paper` | surface | Cream research-document sheets. |
| builder-style capability cards | Periwinkle illumination | `#6e8cff` | `--color-blue-glow` | accent | Radial light source at 0.78, 0.28 and 0.06 alpha under feature media. |
| deployment timelines | Timeline violet | `#9d8bff` | `--color-violet` | accent | Start of the deployment progress spectrum. |
| deployment timelines | Timeline rose | `#f899f2` | `--color-pink` | accent | Inner timeline gradient stop. |
| builder-style product pages | Timeline pink | `#ff9af1` | `--color-pink-light` | accent | Late timeline gradient stop and product-name light. |
| deployment timelines | Timeline peach | `#ff9c5e` | `--color-peach` | accent | End of the progress spectrum. |

## Typography

- **Geist Pixel Line** — Opening, section and closing headlines. Monospaced skeletal letters assembled from horizontal pixel lines; regular weight. Font stack: "Geist Pixel Line", "Geist Mono", monospace.
- **Geist** — Opening support, quotes, navigation and human-centered copy. Clean modern grotesk, restrained regular weight. Font stack: "Geist", system-ui, sans-serif.
- **Inter** — Secondary support, panel titles, footer links and dense explanatory text. Neutral interface grotesk; slightly tightened at title sizes. Font stack: "Inter", system-ui, sans-serif.
- **Geist Mono** — Equipment-like labels, actions, indices and captions. Compact, unembellished technical monospace. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Geist Pixel Line | 400 | 72px | 64px | normal | Default short opening promise; break into two deliberately compact lines. |
| heading | Geist Pixel Line | 400 | 52.6px | 58px | normal | Major story chapters and closing conversion headline. |
| panel-title | Inter | 400 | 34px | 1.16 | -0.02em | Large conversational title inside selector panels. |
| hero-support | Geist | 400 | 19px | 1.45 | normal | Opening support paragraph. |
| support | Inter | 400 | 18px | 1.5 | normal | Section introductions and centered closing support. |
| question | Inter | 400 | 18px | 26px | normal | FAQ summary rows. |
| quote | Geist | 400 | 16px | 1.625 | normal | Customer quote with brighter phrases rather than bold emphasis. |
| proof-number | Geist | 400 | 15px | 18px | normal | Small proof value beside the attribution. |
| detail | Inter | 400 | 15px | 24px | normal | Dense capability explanations and FAQ answers. |
| navigation | Geist | 400 | 14px | 24px | normal | Header categories. |
| link | Inter | 400 | 14px | 20px | normal | Footer navigation links and sign-in. |
| caption | Geist | 400 | 14px | 18px | normal | Attribution role and metric definition. |
| eyebrow | Geist Mono | 500 | 11px | 14px | normal, uppercase | Category labels and footer column headings. |
| key-label | Geist Mono | 400 | 11px | 14px | normal, uppercase | Primary and secondary actions, small numeric chapter labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| builder-style product pages | builder-display | Geist Pixel Line | 400 | 64px | 1.1 | -0.03em | Centered long product promise. |
| outcome-led product pages | landscape-display | Geist Pixel Line | 400 | 64px | 1.08 | normal | Left-aligned promise over landscape photography. |
| culture and recruiting pages | culture-heading | Geist Pixel Line | 400 | 64px | 1.3 | normal | Major headings on the silver wall. |
| builder-style product pages | builder-heading | Geist Pixel Line | 400 | 44px | 1.1 | -0.02em | Capability chapter lead. |
| culture and recruiting pages | culture-row | Geist Pixel Line | 400 | 44px | 1.18 | -0.02em | Numbered principle rows and film-gallery heading. |
| builder-style capability cards | feature-title | Inter | 400 | 30px | 1.15 | -0.02em | Centered title above a detailed interface illustration. |
| interactive instrument demonstrations | instrument-action | Geist | 400 | 14px | 20px | normal | Pale Continue key. |

**Notes:**

- Keep the electronic headline texture distinct from the smooth sans paragraphs. Do not simulate it with bold sans or ordinary code text.
- Default headlines retain normal tracking; the builder variant tightens display tracking to -0.03em and its chapter titles to -0.02em.
- Small uppercase labels are not widely spaced. Weight 500 distinguishes category markings from weight 400 key labels.
- The silver-wall opening shares the 72px/64px display scale, while its chapter headings are larger and more relaxed than the dark default.

## Layout

**Density:** Airy around chapters and carefully packed inside demonstrations; long black intervals separate the major statements.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small icon-to-label relationships. |
| 12px | Eyebrow-to-title relationships and compact card copy groups. |
| 16px | Support paragraph separation and small form insets. |
| 20px | Narrative copy stacks and paired-card gutters. |
| 24px | Selector copy groups and culture-row columns. |
| 32px | Closing copy-to-action gap and footer gutters. |
| 48px | Three-column proof gutters and band contents. |
| 60px | Builder heading-to-card separation. |
| 80px | Top and bottom padding of outcome-led chapters; footer top padding. |
| 100px | Between builder capability chapters. |
| 136px | Culture chapter top padding. |
| 160px | Broad interchapter separation and recruiting lead-in. |

### Containers and grids

- **Main stage**: max width 1102px. Centered marketing content, approximately 169px desktop side margins at 1440px. Hero instrument is 1100px wide.
- **Support measure**: max width 560px. Centered conversion paragraphs; split headings use roughly half the main stage.
- **Footer frame**: max width 1440px · side padding 56px. Footer deliberately wider than body content.
- **Paired capabilities**: 2 columns · gap 20px. Equal 541px-wide builder cards.
- **Proof trio**: 3 columns · gap 48px. Short benefit statements above a large media stage.
- **Footer links**: 4 columns · gap 32px. Four equal 223px link columns to the right of a broader brand-and-trust area.
- **Research shelf** (only for culture and research galleries): 3 columns · gap 64px. Three upright document objects, each 325px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Keys | 8px |
|  | Demonstration frames | 12px |
|  | Selector panels | 4px |
|  | Trust marks | 50% |
| culture and research galleries | Paper sheets | 1px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Orange key | `8px 12px 18px rgba(0,0,0,0.35), 4px 6px 8px rgba(0,0,0,0.45), 2px 4px 6px rgba(0,0,0,0.5), inset 1px 1px 0 rgba(255,255,255,0.25)` | Raised conversion actions. |
| Instrument weight | `24px 36px 70px rgba(7,9,11,0.28), 10px 16px 30px rgba(7,9,11,0.42), 2px 3px 4px rgba(7,9,11,0.45)` | Hero object casts a substantial shadow onto the lit stage. |

### Surfaces

#### Black stage · level 0

**Use:** Default page canvas.

**CSS:** `background: #000000; color: #e8edef`

#### Docked glass · level 3

**Use:** Fixed navigation over both light and dark media.

**CSS:** `background: rgba(8,7,7,0.62); backdrop-filter: blur(24px) saturate(1.6); box-shadow: inset 0 -1px 0 rgba(255,255,255,0.07)`

**Observed:** Thin dark glass retains the atmosphere behind it; light pages use translucent warm white with dark lettering.

**Transfer:** Keep the glass restrained rather than turning the header into a floating pill.

#### Graphite selector · level 1

**Use:** Tactile horizontal choice panels.

**CSS:** `background: linear-gradient(146.27deg, #2e2e30 4.55%, #1f1f21 95.45%); border: 1px solid rgba(0,0,0,0.5); border-radius: 4px; box-shadow: inset 0 1px 0 rgba(255,255,255,0.13), inset 1px 0 0 rgba(255,255,255,0.06), inset -1px -1px 0 rgba(0,0,0,0.4)`

**Observed:** Fine repeated grain at 60px tile size adds a dry manufactured finish.

**Transfer:** Apply a very low-contrast monochrome noise overlay; preserve directional rim lighting.

#### Blue-lit capability · level 1

**Only for:** builder-style capability cards

**Use:** Deep cards that stage a workflow fragment.

**CSS:** `background: radial-gradient(140% 95% at 50% 100%, rgba(110,140,255,0.78) 0%, rgba(110,140,255,0.28) 42%, rgba(110,140,255,0.06) 70%, rgba(110,140,255,0) 88%), linear-gradient(rgba(255,255,255,0.035), rgba(255,255,255,0.016)); border: 1px solid rgba(255,255,255,0.08); border-radius: 12px; box-shadow: inset 0 1px 0 rgba(255,255,255,0.06)`

**Observed:** Text occupies the upper half; the media rises from the blue lower edge and fades into it.

#### Silver wall · level 0

**Only for:** culture and recruiting pages

**Use:** Warm light variant with dimensional vertical folds.

**CSS:** `background: #e8e6e4; color: #000000`

**Observed:** Soft gray-to-silver illumination, narrow vertical highlights, and darker troughs continue behind text and prints.

**Transfer:** Use soft repeating vertical light bands over a warm-gray base, with modest unevenness rather than a flat grid.

#### Paper document · level 1

**Only for:** culture and research galleries

**Use:** Upright scholarly document objects.

**CSS:** `background: #f7f5f0; border-radius: 1px; box-shadow: 0 0 0 0.5px rgba(60,52,40,0.2), 0 -1px 3px rgba(60,52,40,0.1), 0 -10px 26px -12px rgba(60,52,40,0.36); transform: perspective(1400px) rotateX(9deg)`

**Observed:** Cream sheets have tiny serif editorial content, subtle fibers and a shaded lower edge.

**Transfer:** Treat real reports as physical artifacts; keep their miniature typography inside the artwork.

## Components

### Navigation bar

**Use:** Persistent global orientation.

**CSS:** `height: 54px; position: fixed; top: 0px; width: 100%; z-index: 50`

**Text style:** `navigation` — Geist 400 · 14px/24px

**Observed:** Docked glass spans the viewport. Brand left, four subdued menu categories centered, sign-in and orange key right. Categories have 40px hit areas and tiny downward chevrons.

**States:** Declared: hover opacity 1; focus-visible outline 2px solid #ef5a00 with 2px offset; active background rgba(255,255,255,0.06).

### Primary button

**Use:** Main conversion key.

**CSS:** `background: linear-gradient(155.7deg, #f7732b 13.97%, #dd520c 87.5%); border: 1px solid rgba(255,210,184,0.7); border-radius: 8px; height: 44px; padding: 0px 20px; color: rgba(255,255,255,0.95); box-shadow: 8px 12px 18px rgba(0,0,0,0.35), 4px 6px 8px rgba(0,0,0,0.45), 2px 4px 6px rgba(0,0,0,0.5), inset 1px 1px 0 rgba(255,255,255,0.25)`

**Text style:** `key-label` — Geist Mono 400 · 11px/14px · uppercase

**Observed:** A rectangular manufactured key with a light upper-left rim. Header version is 119×42px with a less extended shadow.

**States:** Declared: hover brightness(1.12); focus-visible outline 1.5px solid rgba(232,237,239,0.6), offset 4px; active translate(1px, 2px) and compressed shadows.

### Secondary button

**Use:** Proof links and carousel controls.

**CSS:** `background: linear-gradient(123.37deg, #3b3b3e 13.97%, #2a2a2d 87.5%); border: 1px solid rgba(255,255,255,0.12); border-radius: 8px; height: 44px; padding: 0px 20px; color: rgba(232,237,239,0.88); box-shadow: 4px 6px 5px rgba(0,0,0,0.5), 2px 4px 2.5px rgba(0,0,0,0.6), inset 1px 1px 0 rgba(255,255,255,0.08)`

**Text style:** `key-label` — Geist Mono 400 · 11px/14px · uppercase

**Observed:** Same physical family as the orange action, in graphite. Icon-only carousel versions are 44px square.

**States:** Declared: hover brightness(1.12); focus-visible outline 1.5px solid rgba(232,237,239,0.6), offset 2px; active translate(1px, 2px).

### Conversion well

**Use:** Inline work-email conversion at the close.

**CSS:** `background: linear-gradient(162.07deg, #141517 4.55%, #030405 95.45%); border: 1px solid rgba(255,255,255,0.08); border-radius: 12px; width: 540px; height: 52px; padding: 0px 3px 0px 15px; display: flex; align-items: center; box-shadow: -1px -1px 0 rgba(0,0,0,0.55), 1px 1px 0 rgba(255,255,255,0.07), inset 2px 3px 6px rgba(0,0,0,0.85)`

**Observed:** Input occupies the flexible left side; an orange Primary button fits inside the right edge. A subdued spectral halo and thin white traveling rim surround the well.

**Transfer:** Use one clear input and short action, not a full form in this closing object.

### Selector panel

**Use:** Choice-driven exploration of different applications.

**CSS:** `width: 602px; height: 432px; border-radius: 4px; overflow: hidden; background: #272729`

**Text style:** `panel-title` — Inter 400 · 34px/1.16 · tracking -0.02em

**Observed:** Graphite selector finish; a leading question panel with an email action fronts a horizontal stack of media panels inside a recessed 1110×440px rail. Previous and next keys sit above at the right.

**Transfer:** Organize alternative use cases as physical sliding panels, not isolated pill tabs.

### FAQ row

**Use:** Plain-language objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 20px 0px; gap: 16px; color: rgba(255,255,255,0.96)`

**Text style:** `question` — Inter 400 · 18px/26px

**Observed:** 66px closed rows are separated by faint 1px rules; a small chevron sits at the far right. The first item is open, with dim explanatory text below.

**States:** Declared: focus-visible outline 1.5px solid rgba(232,237,239,0.6), offset 4px; other closed rows declare hover opacity 0.72.

### Footer link

**Use:** Dense but legible directory navigation.

**CSS:** `display: block; padding: 5px 0px; border-radius: 4px; color: #e8edef; opacity: 0.72`

**Text style:** `link` — Inter 400 · 14px/20px

**Observed:** Four columns use tiny uppercase mono category labels. A short fading hairline divides product groups within a column.

**States:** Declared: hover opacity 1; focus-visible opacity 1 and outline 1.5px solid rgba(232,237,239,0.6), offset 3px.

### Compact proof attribution

**Use:** Connect a claim to a person and one measured outcome.

**CSS:** `display: flex; align-items: center; gap: 14px; margin-top: 4px`

**Text style:** `proof-number` — Geist 400 · 15px/18px

**Observed:** 40px portrait with 10px corners, speaker name over dim role; a vertical hairline then a small regular-weight metric over its definition. Metric remains the scale of the name, not a display numeral.

**Transfer:** Use one supportable outcome with a short metric definition.

### Instrument continue key

**Only for:** interactive instrument demonstrations

**Use:** Submit the small form inside the black-glass half of the object.

**CSS:** `background: #f2f1ec; color: #1f1d1b; height: 38px; padding: 0px 16px; border-radius: 5px; box-shadow: 0 0 0 0.5px rgba(255,255,255,0.4), 0 0 14px rgba(242,241,236,0.12)`

**Text style:** `instrument-action` — Geist 400 · 14px/20px

**Observed:** Pale key sits within a 498×48px outlined dark input assembly, beside a long transparent field.

**States:** Declared: hover background #ffffff; focus-visible 2px warm-white glow; active background rgba(242,241,236,0.82).

### Capability card

**Only for:** builder-style capability cards

**Use:** Pair a benefit with a detailed workflow illustration.

**CSS:** `border-radius: 12px; padding: 90px 40px 0px; height: 550px; overflow: hidden; display: flex; flex-direction: column; gap: 32px`

**Text style:** `feature-title` — Inter 400 · 30px/1.15 · tracking -0.02em

**Observed:** Uses Blue-lit capability surface. Centered mono label, smooth sans title and short support occupy the top. A dark window rises into the bottom and is masked by the glow.

**Transfer:** Show one believable workflow fragment per card, not a collage of unrelated interfaces.

## Imagery and graphics

### Spectral folded light

**Use:** Signature full-bleed opening atmosphere.

**Observed:** Warm yellow and ember light at the top becomes wine, purple and cool blue toward the bottom. Tall uneven vertical seams make the light feel refracted through folded translucent material; it fills the viewport behind the instrument and text.

**Transfer:** Recreate the light field independently of the product. Match the soft glow and vertical folds; exact gradient stops are not essential.

**Build:** Layer broad vertical gradients from amber through burgundy to blue. Add repeating 180px-wide translucent vertical bands, each with a 2px pale edge blurred by 6px and a darker adjacent trough. Overlay blurred warm radial light near the upper edge and blue light near the bottom; finish with faint monochrome grain. Keep the central text and object silhouettes readable. Builder openings use the same folded construction in blue-violet rather than warm spectrum.

### Tactile instrument

**Use:** Signature main object and concrete product demonstration.

**Observed:** A wide two-part device: left black glass with sparse terminal greeting and a small form, right warm silver plate with screws, tiny perforations, cross seams and a large circular talk key. Fine bright bevels, grain and directional shadows make it feel fabricated.

**Transfer:** Create a useful instrument for the new product: command window plus control surface, inspector plus output, or input plus result. Minimum acceptable version is a working split panel with convincing edge lighting and one large purposeful control.

**Build:** Use an 1100×470px shell with 12px corners and Instrument weight shadow. Divide into equal halves. Left: near-black diagonal sheen and sparse warm-white text. Right: warm-gray gradient, 1px light/dark edge pairs and fine noise. Center a 196px circular cap inside a 216px recessed ring with concentric inset highlights and stepped down-right shadows. Add only a few screws and 1px seams.

### Human outcome photography

**Use:** Customer proof chapters.

**Observed:** A real doorway handoff, warmly lit and naturally colored, fills the right half. Black gradient masks feather left, bottom and outer edges into the page; faces and the central activity stay visible. Fine dotted annotation leaders label a tiny detail without becoming a diagram.

**Transfer:** Show a tangible moment of benefit in the new product's world. Use one candid action rather than posed stock teamwork.

**Build:** Place a large edge-to-edge photograph behind the right side of the chapter. Apply black-to-transparent masks at left and bottom and a soft dark vignette. For annotations, use two dotted SVG leaders and an 8px uppercase mono label, kept away from faces.

### Closing spectral halo

**Use:** Signature light around the conversion well.

**Observed:** A 700×140px blurred warm/cool halo sits behind the 540px well; a much finer white rim glints around its edge. Light is subtle against black.

**Transfer:** Keep this glow localized to the interaction, not behind the entire closing headline.

**Build:** Layer warm red-orange radial ellipses at the upper left, blue/cyan at the lower right and muted rose at the far right. Blur 36px, brighten 1.3 and reduce overall opacity to about 0.13. For the edge, mask a conic white highlight to a 1px rounded ring, blur 8px and keep it faint.

### Landscape product stage

**Only for:** outcome-led product pages

**Use:** Atmospheric promise and broad product proof.

**Observed:** A mountain valley in low golden light supports white type. Later, the same warm-cool landscape frames a dark dashboard with a rising metric line. The image is richly colored but darkened behind copy.

**Transfer:** Choose a spacious landscape with one clear directional sweep, then inset one crisp product window. Minimum version uses a licensed landscape and a realistic dashboard illustration.

### Culture prints

**Only for:** culture and recruiting pages

**Use:** Human warmth around the silver-wall chapters.

**Observed:** Candid dinners, office moments and team scenes appear as small cream instant-photo prints, mildly desaturated, rotated in alternating directions and casting paper shadows. They float beside headings and numbered rows.

**Transfer:** Use genuine human moments rather than polished corporate portraits.

**Build:** Frame photography with 8px cream borders and 33.6px bottom margin, 2px corners, a 170-degree warm-paper gradient and layered 1px/2px/8px shadows. Rotate a few prints by roughly 6 degrees. Apply contrast(0.94) saturate(0.88) sepia(0.06) to the image.

### Icons

**Observed:** Marketing icons are small and functional: 14px rounded-stroke header chevrons with about 1.2px strokes; 16px accordion chevrons with 2px strokes; 20px arrows inside square carousel keys. Orange 8px squares act as chapter markers, not decorative pictograms.

**Transfer:** Use simple outline icons only where they clarify an action. Keep trust marks monochrome and compact rather than brightly colored logo tiles.

## Section recipes

How recurring sections are built.

### First screen: Lit instrument opening

**Observed:** A full-viewport Spectral folded light field sits behind Docked glass and the main stage. The uppercase eyebrow with an orange square leads into a compact two-line 72px/64px headline at the left; a 403px-wide 19px/1.45 paragraph sits high at the right. Below, the Tactile instrument spans 1100px, roughly three quarters of the page width and just over half the viewport height. Its top is around the upper-middle of the screen, with the complete object visible by 845px. Within the first 900px the user sees the headline, support, black terminal half, silver circular control, embedded email form and Continue key; no following content chapter is visible. The global orange action stays at the top right, while the local conversion is built into the object.

**Transfer:** Use an equally broad split instrument with one useful action and a live or illustrated output; do not need a literal voice device. Builder pages instead center a longer 64px headline above a row of small value statements and a large interface window that continues below the fold. Outcome-led product pages left-align 64px type over landscape media with a separate orange action and film stage. Culture pages center the 72px promise over silver folds with candid prints; direct inquiry pages open with a white two-column form-and-proof composition.

**Avoid:** Do not replace the stage with a centered SaaS headline, two floating pill buttons and a generic laptop mockup. Do not push the principal object entirely below the first screen.

**Text style:** `display` — Geist Pixel Line 400 · 72px/64px

### Marked chapter lead

**Observed:** An 11px uppercase mono eyebrow with orange square precedes the 52.6px headline by 12–18px. Support follows by about 17px or occupies a right-hand column aligned below the heading's top. Most outcome-led bands use 80px vertical padding.

**Transfer:** Introduce a single meaningful chapter; vary between stacked and split text while keeping the same marker and type hierarchy.

**Text style:** `heading` — Geist Pixel Line 400 · 52.6px/58px

### Sliding application rail

**Observed:** A chapter lead sits above Selector panel in a recessed horizontal rail; paired square Secondary buttons align at the right of the heading area. A large question and conversion panel leads into media-backed alternative choices.

**Transfer:** Use for industries, workflows or product configurations where comparing alternatives is useful.

### Paired illuminated capabilities

**Observed:** On Warm night, a 44px chapter headline leads into two Capability cards with 20px gutter and 60px separation from the heading. Each centers its smooth 30px title over one lower-edge interface fragment.

**Transfer:** Group benefits in pairs with matched visual complexity. Keep this more boxed and blue-lit variant confined to builder-oriented narratives.

**Text style:** `builder-heading` — Geist Pixel Line 400 · 44px/1.1 · tracking -0.02em

### Progress spectrum

**Observed:** A compact deployment chapter uses an 8px horizontal violet-to-pink-to-peach progress line spanning 1102px, duplicated behind at 50% opacity with 20px blur. Three explanatory columns sit below, separated by vertical hairlines and small day labels.

**Transfer:** Apply to onboarding or a short implementation path with real stages; the spectrum communicates progress rather than chart data.

### Human proof chapter

**Observed:** A 52.6px headline and 16px quote occupy the left, while Human outcome photography fills the right and dissolves into black. Selected phrases brighten rather than gaining weight. Compact proof attribution and a Secondary button follow the quote. The outcome number is only 15px.

**Transfer:** Let the photo carry emotional scale while the written proof stays precise and intimate.

**Text style:** `heading` — Geist Pixel Line 400 · 52.6px/58px

### Workflow and FAQ split

**Observed:** A chapter heading and short support sit above a numbered workflow: narrow 436px step list at left, larger dark interface at right. The objection-handling variant uses a roughly 4:6 split with a 64px gutter, heading on the left and FAQ rows on the right.

**Transfer:** Use visible product states to explain a sequence; use plain accordion rows when the reader needs answers rather than another visual.

### Physical culture archive

**Observed:** Silver wall chapters use 64px headings, numbered 223px-tall principle rows with 1px dark rules, 44px row titles, compact copy and angled Culture prints. A wide film stage and three-column Paper document shelves extend the tangible-material language.

**Transfer:** For people-focused pages, make values visible through real artifacts and candid scenes rather than the default dark product cards.

**Text style:** `culture-heading` — Geist Pixel Line 400 · 64px/1.3

### Isolated closing instrument

**Observed:** The default close is centered on black, with broad empty space above and below, an 11px marked eyebrow, a two-line 52.6px headline, 560px support measure and Conversion well separated by 32px. Builder pages use a faintly filled 1102px outlined panel with a 60px headline and orange action; outcome-led pages use an unboxed centered promise. Culture pages close on silver with a large centered invitation, surrounding prints and one orange key.

**Transfer:** Restate a specific next outcome, then offer one concrete input or action. Preserve the localized light instrument and breathing room, without requiring a fixed section order.

**Text style:** `heading` — Geist Pixel Line 400 · 52.6px/58px

### Wide utility ending

**Observed:** Every page ends on the same 564px black footer, including light pages. The Footer frame uses 80px top and 44px bottom padding. Brand, green status lamp, five circular trust controls and social icons sit left; four link columns occupy the right. A faint horizontal rule separates the main directory from small legal links and copyright.

**Transfer:** Retain this broad, low-contrast directory ending with real trust information and a restrained operational signal; do not turn it into another hero.

## Page flow

**Storyline:** Promise → tangible product experience → application or capability chapters → human or operational proof → specific next step → broad utility ending.

### Broad marketing landing page

1. **Promise** — Spectral instrument stage with a short urgent headline and embedded conversion.
2. **Application exploration** — Sliding physical panels compare different applications.
3. **Human proof** — Vignetted real-world image, customer quote and compact outcome.
4. **Closing call** — Centered personalized-outcome invitation and glowing email well.
5. **Utility ending** — Black directory, trust marks and legal strip.

**Transfer:** Use the opening device and proof language to make an abstract product tangible; adapt the middle chapters to the new product.

### Builder-oriented product page

1. **Promise** — Centered long pixel headline over blue-violet folded light and a large detailed product window.
2. **Capability chapters** — Paired illuminated cards show setup, editing, customization and testing.
3. **Implementation** — Three-column deployment path under a glowing spectrum line.
4. **Closing call** — Centered invitation within a faintly filled outlined panel.
5. **Utility ending** — Shared black footer.

**Transfer:** Use this variant when the creation workflow itself is the differentiator.

### Direct sales inquiry

1. **Conversion** — White two-column composition: labeled form and progress indicator left, dark landscape-backed proof poster right.
2. **Reassurance** — Poster contains a serif promise with italic emphasis, three icon-led benefits, a pale testimonial card, customer marks and security badges.
3. **Utility ending** — White content transitions directly to the shared black footer.

**Transfer:** Keep the form practical and let the adjoining poster provide confidence. Use the rounded black Continue treatment only for this form, not as the marketing action default.

### Outcome-led product landing page

1. **Promise** — Left-aligned pixel headline over dark landscape with orange key and large film stage.
2. **Benefit proof** — Three concise benefit columns and a dashboard backed by the same landscape.
3. **Product mechanism** — Numbered step list beside changing interface states.
4. **Social proof** — Human customer scene, quote and small industry examples.
5. **Operational detail** — Three steps lead into a large dark collaboration-thread demonstration.
6. **Objection handling** — Split FAQ with the first answer open.
7. **Closing call** — Centered outcome-specific invitation, action and shared footer.

**Transfer:** Choose this storyline for products whose value is measured in operational outcomes; show how those outcomes are achieved.

### Culture and recruiting

1. **Mission** — Centered pixel promise on silver folds, candid prints and a signed internal hardware-like artifact.
2. **Opportunity** — Search and filter controls above full-width team rows.
3. **Principles** — Numbered ruled rows, large pixel statements and candid prints; compact benefits grid.
4. **Work proof** — Wide film gallery followed by upright research-paper objects.
5. **Closing call** — Centered invitation and orange key surrounded by photographs, then the shared black footer.

**Transfer:** Let real work artifacts and people supply the texture; retain the silver scope instead of applying it to ordinary product pages.

## Writing

Direct, technically fluent and outcome-first, with occasional conversational ease. Confidence comes from concrete workflows and named results rather than grandiose adjective stacks.

**Do not copy:** Do not reuse the brand name, product names, logos, proprietary device artwork, customer identities, quotes, mission statements, performance numbers or scale claims. Replace them with substantiated material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Refer to the product by name when describing what it does; use we mainly for the team or an invitation to demonstrate.
- **Rhythm:** Short declarative headline fragments alternate with longer explanatory sentences. Supporting lines usually carry one complete thought; compact labels sound like instrument markings. Headlines can be conversational without becoming jokey.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short pressure-releasing statement or a direct automation benefit. | 4–8 words | “No time to wait.”<br>“Automatically improve business-critical KPIs.” |
| Capability headline | Use a practical verb and a concrete user concern. | 6–12 words | “Control exactly how your agents show up”<br>“Get a new agent up and running in no time” |
| Support | Explain the mechanism and its value in one sentence. | 15–30 words | “Swap rigid workflows for agents that adapt to your industry and its unique needs.” |
| Action | Plain verb plus a specific object; render in uppercase mono. | 2–4 words | “See a demo”<br>“Build my page”<br>“Read the story” |
| Closing invitation | Bring the reader's context into a specific demonstration of value. | 8–14 words | “See what [Brand] would resolve at your company.”<br>“Bring your KPI. See how Scout moves it.” |

**Words and phrasing to use:** resolve; improve; build; define; approve; real conversations; in production; plain English; end to end

**Avoid:** revolutionary; game-changing; unlock limitless potential; magic; synergy; delightful journey

**Rules:**

- Pair automation claims with what the user defines, reviews or approves.
- Explain actual inputs, systems and outputs instead of listing abstract intelligence attributes.
- Use contrast sparingly: rigid versus flexible, telling it what to say versus telling it what to improve.
- Keep action labels literal and low-friction; avoid exclamation marks and inflated urgency.

## Do's and Don'ts

### Do

- Use weight 400 for the scan-lined display family, preserving its thin horizontal construction.
- Keep the main product stage near 1100px wide while footer content expands into a 1440px frame.
- Give orange keys 8px corners and a bright upper-left edge; use 44px height outside the header.
- Use 11px/14px uppercase mono for labels, with normal tracking.
- Place 1px dim rules between repeated rows rather than outlining every content group.
- Stage at least one convincing physical or interface instrument within the narrative.
- Keep the proof numeral at 15px beside a name when using the compact testimonial treatment.
- Leave 80px vertical padding around outcome-led chapters and broad black space around the closing action.

### Don't

- Do not make all body copy monospace; support uses smooth Geist or Inter at 18–19px.
- Do not use orange as a flat full-page background; it is a key and signal color outside the spectral art.
- Do not round marketing keys into capsules; their default radius is 8px.
- Do not turn the 15px customer outcome into a huge freestanding percentage.
- Do not use uniform ambient card shadows; the key and instrument shadows have directional down-right weight.
- Do not spread blue-lit card treatments across every ordinary marketing section; that boxed variant belongs to builder narratives.
- Do not use bright multicolored trust badges in the black footer; the controls are small and monochrome.
- Do not enlarge the serif text found in document or sales-poster artwork into the main marketing headline system.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary keys declare transform and shadow transitions of 0.15s cubic-bezier(0.16,0.84,0.32,1), plus filter 0.16s ease.
- Selector panels declare transform and filter 0.68s cubic-bezier(0.3,0,0.1,1).
- Footer links declare opacity and background-color 0.15s cubic-bezier(0.16,0.84,0.32,1). The status lamp declares a 2.4s ease-in-out infinite alternate animation.
- Paper sheets declare transform and shadow 0.42s cubic-bezier(0.2,0.7,0.2,1).

**Transfer:**

- Let raised keys brighten and depress by 1px horizontally and 2px vertically, with their shadow visibly compressing.
- Keep spectral movement subordinate to the legible instrument and the practical action.

**Unknown:**

- Exact scroll choreography, canvas animation timing and the full reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop stage is centered at 1102px. Declared width thresholds include 640px, 700px, 810px, 1024px and 1100px.
- Builder card groups declare a column arrangement before changing to a row on wider layouts.

**Transfer:**

- On narrow screens, stack the headline and support before the instrument. Preserve its black-versus-silver material contrast while making the local action usable.
- Collapse paired capabilities and proof trios into a reading sequence; retain the bottom-edge media illumination.
- Wrap footer groups without shrinking the 14px links into miniature text.

**Unknown:**

- Exact mobile type sizes, stage proportions, navigation behavior and footer column counts are not established. These narrow-screen adaptations are guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
