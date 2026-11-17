# Frame.io — cinematic glass currents

## Overview

A dark, cinematic language for sophisticated creative tools and collaborative platforms. Soft violet and blue light drifts behind tightly set grotesk headlines, translucent interface windows and jewel-like glass sculptures. Spacious product demonstrations alternate with compact explanations, while real photography brings warmth and credibility to the near-black world.

### Essentials

- The promise sits beside an oversize working window, not above a generic illustration: 80px/1.04 weight 600 headline with -0.045em tracking in a 504px text column; a 986×555px interface extends beyond the right edge.
- Headlines resolve from muted setup to luminous payoff: 48px/1.02 weight 600, -0.04em tracking, with rgba(234,234,255,0.5) leading into #fcfcfc, upright throughout.
- Small actions feel like polished controls beneath monumental content: 40px-high pills, 24px horizontal padding and 14px weight 600 labels; pale solid primary beside translucent secondary.
- Color behaves like stage lighting rather than paint: black and near-black dominate the long page, violet and blue glows pool behind media, and the only broad saturated flat strip is the 36px announcement band.
- Product proof is staged in glass: 10px outer radius, 6px inset, 1px rgba(157,157,255,0.05) edge and 16px backdrop blur; full working views alternate with isolated floating controls.
- Luminous curved glass is a signature device: oversized overlapping translucent blue-violet arcs accompany proof and reappear as a crest beneath the closing action. Recreate the arcs with layered SVG ellipses when no rendered artwork is available.
- Technical labels punctuate the cinema: NeueMachinaInktrap at 12px/0.9, uppercase with 0.06em tracking in soft blue; 24px grid gutters and 124px chapter openings keep small labels distinct from the big scenes.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement violet | `#5b53ff` | `--color-violet` | background, accent, text | Announcement strip; violet eyebrow variant for review features and customer editorial sections. |
| Closing blue glow | `#4e55a8` | `--color-footer-blue` | background, accent | Center of the closing radial glow. |
| Plum atmosphere | `#482a69` | `--color-purple-light` | background, accent | Broad transparent radial light behind curved glass. |
| Deep blue stage | `#0c1d32` | `--color-hero-blue` | background | Opening gradient lower stop. |
| Deep plum stage | `#0a001e` | `--color-hero-plum` | background | Opening gradient upper stop. |
| Violet black | `#02000a` | `--color-hero-black` | background | Opening gradient middle stop. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Instrument blue | `#6199f6` | `--color-blue` | text, accent | Default eyebrow, checkmarks and selected-plan inner light. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Porcelain action | `#f5f5f8` | `--color-action-fill` | action, surface | Primary button fill. |
| Slate lavender | `#81859f` | `--color-faq-text` | text | Expanded answers and secondary editorial support. |
| Black stage | `#000000` | `--color-canvas` | background, text | Default canvas and dark text on pale actions. |
| Faint lavender glass | `#08080d` | `--color-glass-edge` | surface, border | Visible rgba(157,157,255,0.05) over black; glass wrappers and subtle feature-card edges. |
| Graphite shadow | `#09090d` | `--color-card-dark` | surface | Dark end of the feature-card diagonal gradient. |
| Footer veil | `#0a0a13` | `--color-footer-fill` | surface | Visible rgba(13,13,24,0.8) over black; deep footer glass. |
| Navigation tile edge | `#131318` | `--color-tile-edge` | border | Visible rgba(189,189,244,0.1) over black; linked tiles and FAQ dividers. |
| Graphite sheen | `#1b1b26` | `--color-card-light` | surface | Light end of the feature-card diagonal gradient. |
| Muted lavender gray | `#757580` | `--color-muted` | text | Visible rgba(234,234,255,0.5) over black; secondary prose and the setup half of section headings. |
| Porcelain edge | `#c1c2d9` | `--color-action-edge` | border | Solid primary button edge. |
| Pale lavender body | `#dedfee` | `--color-body` | text | Opening support copy. |
| Luminous white | `#fcfcfc` | `--color-text` | text | Headlines, navigation and emphasis. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| plan summaries | Plan glass | `#08080c` | `--color-plan-fill` | surface | Visible rgba(16,16,23,0.5) over black. |
| plan summaries | Plan edge | `#10101a` | `--color-plan-edge` | border | Visible rgba(157,157,255,0.1) over black; standard plan outlines. |
| pricing pages | Comparison rule | `#2e2f40` | `--color-table-rule` | border | Comparison-table horizontal rules. |
| plan summaries | Plan detail gray | `#a3a3b3` | `--color-subtle` | text | Visible rgba(233,233,255,0.7) over black for plan details. |

## Typography

- **FrameGothic** — Marketing headings, prose, navigation and actions. A broad, clean grotesk with open counters; soft geometry and tightly packed display lines. If unavailable, use **Inter**. Use 400–600 and preserve the tight display tracking. Font stack: "FrameGothic", "Inter", Arial, sans-serif.
- **NeueMachinaInktrap** — Eyebrows and small technical category labels. Mechanical, monospaced-looking construction with inktrap details and widely tracked capitals. If unavailable, use **Space Mono**. Use regular weight; keep labels short to accommodate wider letters. Font stack: "NeueMachinaInktrap", "Space Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | FrameGothic | 600 | 80px | 1.04 | -0.045em | Opening promise across page types. |
| heading | FrameGothic | 600 | 48px | 1.02 | -0.04em | Chapter headings, large proof statements and two-tone heading pairs. |
| closing | FrameGothic | 600 | 38px | 1.16 | -0.035em | Closing conversion heading; also FAQ and directory headings. |
| lead | FrameGothic | 400 | 18px | 1.45 | normal | Hero support and section introductions. |
| footer-link | FrameGothic | 400 | 16px | 1.25 | normal | Footer directory links and compact figure explanations. |
| body | FrameGothic | 400 | 15px | 1.45 | normal | Feature descriptions, answers and supporting copy. |
| feature-label | FrameGothic | 500 | 15px | 1.3 | normal | Short benefit headings and FAQ questions. |
| action | FrameGothic | 600 | 14px | 0.96 | 0.01em | Navigation and pill-button labels. |
| eyebrow | NeueMachinaInktrap | 400 | 12px | 0.9 | 0.06em, uppercase | Small chapter identifiers above headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| customer results cards | stat | FrameGothic | 500 | 80px | 0.72 | normal | Oversized bare percentage or multiplier beneath a small customer mark. |
| plan summaries | plan-title | FrameGothic | 600 | 30px | 1.02 | -0.03em | Plan names and prices, the latter using muted text. |
| customer stories and testimonial panels | story-title | FrameGothic | 600 | 25px | 1.12 | -0.03em | Narrow story headings and landscape-panel quotations. |
| customer story grids | editorial-title | FrameGothic | 600 | 20px | 1.23 | -0.025em | Story title below photography. |
| feature directory tiles | tile-title | FrameGothic | 600 | 18px | 1.2 | normal | Bottom-aligned linked capability name. |

**Notes:**

- Tracking tightens progressively from normal in prose to -0.03em in small display titles, -0.04em in chapter headings and -0.045em in the opening promise.
- Two-tone headings are one continuous upright thought, not an italic quotation or two unrelated heading sizes.
- The technical face is a punctuation layer, not a body font. Interface demonstrations may use their own UI typography without extending it into marketing copy.

## Layout

**Density:** Airy at chapter scale, compact within demonstrations and supporting feature lists.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Glass media inset. |
| 8px | Compact heading-support and answer gaps. |
| 12px | Eyebrow-to-heading and headline-to-lead separation. |
| 16px | Paired action gap and footer link bottom padding. |
| 24px | Grid gutter, card padding and support-to-action gap. |
| 32px | FAQ row padding and stacked benefit spacing. |
| 48px | Feature introduction to benefit stack. |
| 62px | Half-chapter vertical breathing room. |
| 80px | Closing block top padding. |
| 96px | Footer top padding. |
| 124px | Major chapter top padding. |
| 160px | Closing block space beneath the action. |
| 240px | Default opening stage top padding. |

### Containers and grids

- **chapter container**: max width 1080px · 12 columns · gap 24px · side padding 74px. Centered desktop chapter grid: twelve 68px tracks at 1440px yield 180px outer margins; 74px is the minimum wrapper margin.
- **opening stage**: max width 1440px · gap 68px · side padding 48px. Left 504px copy block beside an approximately 1000px-wide media wrapper; the media is deliberately clipped by the right viewport edge.
- **feature cards**: 3 columns · gap 24px. Three 344px cards; asymmetric bento variants combine a 712px card with a 344px stack.
- **centered lockup**: max width 712px. Centered section or closing heading; supporting lead may narrow to 528px.
- **plan cards** (only for plan summaries): 4 columns · gap 24px. Four 252px cards aligned within the chapter container.
- **editorial grid** (only for customer story grids): 2 columns · gap 24px. Two 528px picture-led columns with 124px between rows.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | glass and feature cards | 10px |
|  | media interior and directory tiles | 5px |
|  | chapter edges | 20px |
|  | carousel controls | 50% |
| customer montage sections | portrait mosaic tiles | 24px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default long-page canvas.

**CSS:** `background: #000000; color: #fcfcfc`

#### Opening atmosphere · level 0

**Use:** Full-width opening stage.

**CSS:** `background: linear-gradient(195deg, #0a001e 0%, #02000a 80%, #0c1d32 100%)`

**Observed:** A luminous smoky violet field floats above the darker base, making the interface feel suspended rather than boxed.

**Transfer:** Overlay the Atmospheric light graphic and retain a darker zone immediately behind text.

#### Glass media frame · level 1

**Use:** Large working views and isolated UI panels.

**CSS:** `background: rgba(157,157,255,0.05); border: 1px solid rgba(157,157,255,0.05); border-radius: 10px; padding: 6px; backdrop-filter: blur(16px)`

**Observed:** The inner view has a tighter corner than the wrapper; the edge is visible only as a faint glint.

**Transfer:** Use around real product imagery, not around every text block.

#### Graphite card · level 1

**Use:** Benefit and integration cards, including result cards.

**CSS:** `background: linear-gradient(140deg, #1b1b26 -41.97%, #09090d 77.06%); border: 1px solid rgba(157,157,255,0.05); border-radius: 10px`

**Observed:** Dark diagonal sheen separates cards from black without a bright opaque fill.

**Transfer:** Make imagery the dominant content and tuck brief text below it.

#### Navigation glass · level 2

**Use:** Top navigation backing.

**CSS:** `background: rgba(13,13,24,0.3); backdrop-filter: saturate(1.5) blur(125px)`

#### Footer veil · level 1

**Use:** Deep closing directory over the atmospheric light.

**CSS:** `background: rgba(13,13,24,0.8); backdrop-filter: saturate(1.5) blur(100px); border-radius: 20px 20px 0px 0px`

#### Announcement band · level 2

**Use:** Slim full-width update link above navigation.

**CSS:** `background-color: #5b53ff; background-image: linear-gradient(355deg, rgba(255,255,255,0.15) 4.03%, rgba(255,255,255,0) 95.81%); height: 36px; padding: 12px 24px`

**Observed:** Centered underlined update with a dismiss control at the far right; much brighter than all lower sections.

#### Closing glow · level 0

**Use:** Light behind the final action and curved-glass crest.

**CSS:** `background: radial-gradient(47.08% 45.75%, #4e55a8 0%, rgba(69,82,158,0.91) 33.36%, rgba(72,42,105,0) 100%); mix-blend-mode: screen`

**Observed:** A 1872×1500px light field extends beyond the viewport and softly illuminates the footer edge.

**Transfer:** Keep the light broad and feathered; exact stops are not essential to the soft falloff.

## Components

### Primary button

**Use:** Main trial, sign-up or meeting conversion.

**CSS:** `background: #f5f5f8; color: #000000; border: 1px solid #c1c2d9; border-radius: 9999px; height: 40px; padding: 0px 24px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — FrameGothic 600 · 14px/0.96 · tracking 0.01em

**Observed:** Pale solid treatment anchors the opening and plan cards; the closing call instead uses the glass treatment.

**States:** Declared: hover appearance unspecified; focus-visible outline 1px dotted #fcfcfc; active text #fcfcfc.

### Glass button

**Use:** Secondary tour and chapter actions; default closing action.

**CSS:** `background: rgba(209,209,251,0.2); color: #fcfcfc; border-radius: 9999px; height: 40px; padding: 0px 24px; backdrop-filter: blur(15px); display: inline-flex; align-items: center; gap: 6px`

**Text style:** `action` — FrameGothic 600 · 14px/0.96 · tracking 0.01em

**Observed:** Tour and chapter actions carry a short right arrow; on black the glass reads almost outlined, while over violet it is visibly filled.

**States:** Declared: hover appearance unspecified; focus-visible outline 1px dotted #fcfcfc; active text uses an unresolved custom color.

### Navigation

**Use:** Global top-level orientation.

**CSS:** `height: 80px; max-width: 1440px; display: flex; align-items: center; justify-content: space-between; background: rgba(13,13,24,0.3); backdrop-filter: saturate(1.5) blur(125px)`

**Text style:** `action` — FrameGothic 600 · 14px/0.96 · tracking 0.01em

**Observed:** Small white symbol at the left, compact dropdown links beside it, then contact, sign-in and a pale Primary button at the right. It sits beneath the Announcement band; side utility marks balance rather than dominate the bar.

### Feature card

**Use:** Concise capability demonstration.

**CSS:** `background: linear-gradient(140deg, #1b1b26 -41.97%, #09090d 77.06%); border: 1px solid rgba(157,157,255,0.05); border-radius: 10px; overflow: hidden; display: flex; flex-direction: column; align-items: center`

**Text style:** `feature-label` — FrameGothic 500 · 15px/1.3

**Observed:** Top artwork occupies most of the panel; centered benefit name and muted body form the lower caption. Equal three-up and asymmetric tall-plus-stack constructions coexist.

**Transfer:** Show one recognizable product operation per card, with a short result rather than a UI inventory.

### Footer link

**Use:** Directory navigation on the closing veil.

**CSS:** `color: #fcfcfc; padding: 0px 24px 16px 0px; display: block`

**Text style:** `footer-link` — FrameGothic 400 · 16px/1.25

**Observed:** Three link columns sit to the right of a small standalone symbol; technical group labels are muted. The legal/language/social row is separated by a faint rule and substantial vertical breathing room.

**States:** Declared: hover on the link group dims text to rgba(234,234,255,0.5); focus-visible outline 1px dotted #fcfcfc.

### Plan card

**Only for:** plan summaries

**Use:** Comparable offer with subtle recommended tier.

**CSS:** `background: rgba(16,16,23,0.5); border: 1px solid rgba(157,157,255,0.1); border-radius: 10px; padding: 24px; backdrop-filter: blur(75px); display: flex; flex-direction: column`

**Text style:** `plan-title` — FrameGothic 600 · 30px/1.02 · tracking -0.03em

**Observed:** Technical audience label precedes name and muted price; a separated description, action and dense inclusion list follow. The overview puts actions at the bottom; dedicated pricing places them earlier. Recommended tier changes the edge to rgba(157,157,255,0.5) and adds an inset blue glow, not a solid violet fill.

**Transfer:** Retain equal card heights and shared baselines. Use actual offer details.

### FAQ row

**Only for:** pricing and technical detail pages

**Use:** Objection handling without decorative containers.

**CSS:** `border-bottom: 1px solid rgba(189,189,244,0.1); padding: 32px 0px`

**Text style:** `feature-label` — FrameGothic 500 · 15px/1.3

**Observed:** Question spans the row, with a small downward chevron at the far edge. Expanded answer uses muted slate body text, separated by 8px and narrower than the full row. First row may omit upper padding.

### Feature directory tile

**Only for:** feature detail pages

**Use:** Cross-navigation after detailed demonstrations.

**CSS:** `background: #000000; border: 1px solid rgba(189,189,244,0.1); border-radius: 5px; width: 344px; height: 344px`

**Text style:** `tile-title` — FrameGothic 600 · 18px/1.2

**Observed:** Dark dimensional object centered above a bottom-aligned title; a small white circled arrow sits opposite the title. Inner content has 24px padding.

**Transfer:** Represent each destination with a simple polished translucent object rather than a colorful flat illustration.

### Comparison row

**Only for:** pricing pages

**Use:** Dense side-by-side feature evaluation.

**CSS:** `border-bottom: 1px solid #2e2f40; display: grid; column-gap: 24px`

**Text style:** `body` — FrameGothic 400 · 15px/1.45

**Observed:** A wide left feature label precedes four aligned value columns. Rows are about 55px high with 16px vertical cell padding. Blue filled checks and muted dashes make availability scannable; a sticky translucent header keeps plan names, prices and compact actions in view.

### Result card

**Only for:** customer results sections

**Use:** Quantified social proof.

**CSS:** `background: linear-gradient(140deg, #1b1b26 -41.97%, #09090d 77.06%); border-radius: 10px; padding: 24px; width: 344px; height: 220px`

**Text style:** `stat` — FrameGothic 500 · 80px/0.72

**Observed:** Small white customer mark above a bare oversized percentage or multiplier, with a single muted explanatory line directly beneath. Text remains left-aligned within the compact panel.

**Transfer:** Use verified results with a meaningful unit; the short 0.72 numeral line height is only for this treatment.

## Imagery and graphics

### Working interface cinema

**Use:** Opening and major capability demonstrations.

**Observed:** Dark product windows carry richly graded photographic assets: warm amber interiors, blue underwater scenes and high-contrast portraits. Large horizontal windows exceed the copy width, while isolated menus and tall phone views float in front. Frames are restrained dark glass, not laptop mockups.

**Transfer:** Use a real working view populated with coherent, attractive sample content. If the product is not visual, stage its meaningful output in a faithful dark interface with one enlarged control; do not fabricate dozens of unreadable UI fragments.

### Atmospheric light

**Use:** Opening stage and chapter transitions.

**Observed:** Smoky purple, indigo and blue patches fill the space around media, feathering into black. Light has soft irregular structure rather than a tidy corner-to-corner gradient.

**Transfer:** Keep the darkest areas behind prose and allow glow to spread behind the object; match the soft luminosity rather than exact stops.

**Build:** Use a black or Opening atmosphere base. Layer two oversized radial ellipses, one rgba(72,42,105,0.55) and one rgba(78,85,168,0.4), each fading to transparent by its edge. Make them 1000–1800px wide, blur by 100–160px, offset them in opposite directions, and add a low-opacity soft noise layer. Keep the result dimmer than the white headline.

### Curved glass sculpture

**Use:** Signature proof interludes and closing crest.

**Observed:** Huge translucent ribbons and elliptical shells overlap like folded lenses. Deep blue and violet interiors catch cyan rims and pale lilac highlights. In proof scenes the object fills the right half and extends beyond the frame; near the footer it becomes a low symmetrical crest beneath the call.

**Transfer:** Carry this luminous curved material into every new landing page. A small set of smooth layered arcs is sufficient when full rendered glass is unavailable.

**Build:** In SVG, overlap 3–5 wide elliptical rings with partial opacity, rotated and clipped so only sweeping upper arcs remain. Give each a deep violet-to-blue transparent fill and a thin cyan/lilac gradient stroke; duplicate strokes beneath with 8–16px blur for bloom. Use ring spans of 800–1400px, stagger centers and preserve dark transparent interiors. For the closing crest mirror the arcs around the center and place them beneath the text over Closing glow.

### Polished capability objects

**Only for:** feature directories and integration cards

**Use:** Small symbolic demonstrations.

**Observed:** Nearly black translucent folder, cloud, conversation and device forms catch soft white bevels. They float on black with tiny highlights and no bright cartoon color.

**Transfer:** Render a few overlapping rounded translucent rectangles and one simple white line glyph per capability; maintain subdued edges and a dominant dark silhouette.

**Build:** Layer two or three SVG rounded rectangles with graphite transparent gradients, 1px white edges at 10% opacity and a faint blurred light along the top. Offset planes by 8–16px and place a small monochrome glyph in the front plane.

### Cinematic photography

**Only for:** customer stories and immersive technical feature openings

**Use:** Human proof and scene-setting.

**Observed:** Real production environments, landscapes and people at work use dramatic natural light and subdued color. Story rows alternate a tall 528px-wide photo with narrow text; editorial cards use wide photographs. Full-width scenes receive black overlays for white copy, and testimonial landscapes sit in 1090×556px rounded slides with partial neighbors visible.

**Transfer:** Choose authentic use contexts with strong depth and directional light. Darken locally behind overlaid copy; leave story photography naturally legible rather than imposing violet duotone.

### Perimeter montage

**Only for:** customer overview openings and customer proof sections

**Use:** Surrounding a promise with a visible world of work.

**Observed:** Offset columns of rounded photographic tiles run beyond the viewport, leaving a clear black center for the headline. A separate proof montage combines tall portrait columns with a phone interface in the foreground.

**Transfer:** Use varied real scenes cropped consistently; keep the central reading zone empty and intentional. If photography is limited, repeat coherent product outputs rather than unrelated stock portraits.

### Icons

**Observed:** Compact mostly filled SVGs: arrows and social marks around 16px, dropdown chevrons around 10px, comparison checks 18px in soft blue. Carousel controls are 44px circles; a few utility outlines use 1.5px round strokes.

**Transfer:** Use simple monochrome utility symbols, tiny arrows and restrained blue checks. Keep object illustrations separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** The first 900px contains a 36px bright Announcement band, 80px Navigation, and an atmospheric split stage. The 504px left text block begins around one third down the screen, using display across roughly three lines; a lead paragraph follows after 12px and paired Primary button and Glass button after 24px. The working interface begins above the headline, occupies more than half the viewport, and is clipped at the right edge rather than scaled to fit. Behind it are deep plum/blue base and smoky light; in front is Glass media frame around a 986×555px window. Headline, support, both actions and the main working view are visible before 900px; the centered logo proof strip falls below.

**Transfer:** Use one decisive promise beside the strongest faithful view of a new product. Without existing media, construct one credible working panel and enlarge its primary output. Dedicated feature pages may open with centered display and actions above an expansive window, or an immersive photo with narrow left-aligned text. Pricing opens left-aligned above plan cards; customer overviews center the promise inside Perimeter montage.

**Avoid:** Do not replace the right-clipped interface with a small centered dashboard, make a full-width centered headline the default, or turn the atmospheric stage into a flat violet rectangle.

**Text style:** `display` — FrameGothic 600 · 80px/1.04 · tracking -0.045em

### Two-tone chapter lockup

**Observed:** Within the chapter container, a blue eyebrow sits 12px above heading. Muted setup resolves into luminous payoff with no size or weight change. Lead or Glass button follows with 12px or 24px separation. Chapter padding commonly begins at 124px; text can span 528–896px.

**Transfer:** Write one two-part thought: the problem or setup in muted text and the positive result in white. Keep the emphasis legible even without animation.

**Text style:** `heading` — FrameGothic 600 · 48px/1.02 · tracking -0.04em

### Large demonstration and caption rail

**Observed:** A broad Glass media frame sits 24px below its introduction. Three supporting columns beneath use feature-label, a 4px gap, then body copy. A different variant places narrow copy beside a very large interface that bleeds offscreen, with floating controls layered over it.

**Transfer:** Let a single operation own the large view, then explain three distinct consequences below; alternate media orientation only when it supports the story.

### Bento benefit chapter

**Observed:** Graphite card panels form three equal columns or one large panel with two smaller stacked panels. Artwork takes the upper area; short centered captions sit low. Some wide cards combine edge-to-edge cinematic footage with a local dark text scrim.

**Transfer:** Vary geometry according to demonstration importance, not merely to fill a fashionable mosaic.

### Sculptural proof interlude

**Observed:** An open black stage places a 48px white quantified statement in a narrow left column and Curved glass sculpture across the right half. A small source line or Glass button may follow; broad plum or blue light bridges into the next rounded chapter.

**Transfer:** Give one substantiated outcome a moment of visual scale. Use the glass material as a nonliteral signal of flow, not as a chart.

### Closing light and directory

**Observed:** A centered closing heading is smaller than chapter headlines at 38px, with a Glass button 24px beneath and 160px breathing room below. A broad blue glow and a crest of curved translucent lenses rise underneath. Footer veil overlaps the art, then gives a small symbol its own left column and three grouped link columns at right. Footer padding is 96px above and 48px below, with a separated tiny legal/language/social rail.

**Transfer:** End with one short outcome-focused invitation, luminous sculptural artwork and an unusually spacious directory. Keep the glow even on technical pages where the crest gives way to a simpler illuminated edge.

**Text style:** `closing` — FrameGothic 600 · 38px/1.16 · tracking -0.035em

### Offer and objections

**Only for:** pricing pages and offer sections

**Observed:** Four Plan cards share a 24px gutter. The dedicated pricing opening includes monthly/annual controls and a small blue savings badge. A long Comparison row table groups capabilities under collapsible category headings with persistent plan actions; cinematic customer proof then gives way to a simple FAQ list.

**Transfer:** Separate fast offer selection from detailed comparison. Keep answers truthful and dense data visually quiet.

### Customer proof system

**Only for:** customer stories

**Observed:** Result cards follow a two-tone lockup. Alternating story rows place 25px headings in narrow copy columns opposite tall rounded photography; a later two-column story grid uses 20px headings beneath images. Large photographic testimonial slides expose neighboring panels and circular controls.

**Transfer:** Move between concise measurable outcomes, deeper human stories and a voice-led image panel; do not make every proof item a tiny logo.

## Page flow

**Storyline:** Promise → product in action → capability explanations → outcome proof → choice or related exploration → final invitation and luminous directory.

### Broad product landing page that introduces an integrated offer

1. **Promise** — Split opening with clipped working interface and paired actions.
2. **Orientation** — Logo proof and two-tone platform introduction with four compact benefits.
3. **Capability chapters** — Large working windows, caption rails and bento cards alternate with sculptural outcome statements.
4. **Social proof** — Photographic montage with a foreground device view.
5. **Choice** — Four restrained plan cards beneath a centered introduction.
6. **Closing call** — Short centered invitation, glass crest, glow and directory.

**Transfer:** Use the split stage and luminous materials as the default, adapting the number and order of capability chapters to the product.

### Offer selection followed by detailed evaluation

1. **Choice** — Large left-aligned promise, billing selector and four plan cards.
2. **Comparison** — Long ruled matrix with grouped categories and sticky plan actions.
3. **Social proof** — Full-width scenic customer quotation treatment.
4. **Objection handling** — Simple question rows under a 38px heading.
5. **Closing call** — Meeting invitation, luminous crest and full directory.

**Transfer:** Keep pricing deliberately more utilitarian than the default stage; move decorative spectacle to proof and closing.

### Explain a focused workflow with concrete product behavior

1. **Promise** — Centered opening display, support and paired actions over cool atmosphere, then a large cinematic working view.
2. **Capability chapters** — Two-tone introductions, annotation-led bento and centered demonstration.
3. **Workflow depth** — Side-by-side control overlays and asymmetric integration cards.
4. **Related exploration** — Six dark object-led navigation tiles.
5. **Closing call** — Centered trial invitation, glass crest and directory.

**Transfer:** Choose a focused workflow and show precise interactions, not a broad repeated feature inventory.

### Make a technical connection feel tangible and usable

1. **Promise** — Full-bleed production scene with stacked display and floating asset cards.
2. **Product demonstration** — Immersive media and large progressive explanatory text.
3. **Capability chapters** — Setup bento and speed-focused three-card row.
4. **Audience breadth** — Large stacked category words with a warm-to-cool text gradient.
5. **Compatibility** — Wide scene, caption rail and compact four-column partner tiles.
6. **Objection handling** — Technical FAQ followed by related feature tiles.
7. **Closing call** — Two glass actions over a simpler blue glow, then the same directory.

**Transfer:** Reserve this immersive photographic opening for products whose physical use can be shown convincingly; use a labeled compatibility directory and direct setup answers.

### Show range, outcomes and lived experience

1. **Promise** — Centered headline surrounded by an edge-clipped photographic montage.
2. **Quantified proof** — Three dark result cards with oversized bare numerals.
3. **Case studies** — Alternating narrow text and tall imagery, followed by two-column editorial stories.
4. **Social proof** — Wide landscape testimonial carousel with partial neighboring slides.
5. **Closing call** — Team-focused meeting invitation, glass crest and directory.

**Transfer:** Use real results and authentic contexts; balance compact numbers against visually generous narratives.

## Writing

Confident and practical, with an occasional cinematic turn of phrase. Benefits are framed as faster, clearer work and then made credible through specific functions, customer contexts and attributed outcomes.

**Do not copy:** Do not reuse the Frame.io or Adobe names, logotypes, customer marks, product imagery, customer quotations, reported multipliers, savings or performance claims. Replace every example with truthful content and assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Directly address the reader as you and your; name the product when stating a capability or measured outcome. Imperative verbs lead benefit explanations and actions.
- **Rhythm:** Headlines often form two compact clauses. Support is usually one sentence; feature captions use a short title followed by one or two plain sentences. Actions are brief verb phrases; punctuation supports cadence rather than hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A broad outcome in an economical declarative sentence, or a three-beat memorable phrase. | 3–12 words | “One platform for all your creative work.”<br>“Lights. Camera. Cloud.” |
| Chapter headline | Muted setup followed by a brighter practical payoff. | 7–14 words | “Remove blockers to streamline your workflow.”<br>“Fast, reliable, and secure from the start.” |
| Benefit caption | Short active verb phrase, followed by a concrete explanation. | 2–5 words for the label | “Organize everything”<br>“More peace of mind” |
| Supporting line | Name practical operations and their benefit in a single direct sentence. | 15–30 words | “Reduce review cycles across all asset types with the powerful, centralized [Brand] feedback and review experience.” |
| Action | A direct action or desirable outcome, title case. | 2–4 words | “Start Free Trial”<br>“Unlock Faster Workflows” |
| Question | Answer the real procurement or setup concern in the reader's language. | 6–14 words | “How does the free trial work?” |

**Words and phrasing to use:** clarity; control; faster; precise; secure; streamline; connect; share; organize; your workflow

**Avoid:** revolutionary magic; disrupt everything; frictionless synergy; unsubstantiated best-ever claims; overly playful technical jargon

**Rules:**

- Pair an abstract promise with a concrete operation nearby.
- Use numerical proof only when attributable and meaningful.
- Write parallel benefit labels and keep captions short enough for three-column rails.
- Keep technical answers literal; reserve wordplay for an occasional headline.

## Do's and Don'ts

### Do

- Keep the default opening headline at 80px/1.04 and weight 600 with -0.045em tracking.
- Use 48px headings with a muted-to-white phrase transition, not a size transition.
- Keep major demonstration windows much wider than adjacent copy and let selected media bleed right.
- Use 24px grid gutters and a centered 1080px chapter width on desktop.
- Keep primary and glass actions 40px high with compact 14px labels.
- Include luminous curved-glass artwork with dark transparent interiors and broad feathered light.
- Give chapter openings 124px of breathing room and keep dense feature text at 15px/1.45.
- Place the final invitation above a blue-lit art crest and a spacious dark directory.

### Don't

- Do not turn the long canvas into alternating white and saturated purple bands.
- Do not use 700–900 weight display typography; tight 600 grotesk carries the scale.
- Do not expand the technical label face into paragraphs or use generic code styling as the main personality.
- Do not give every card a 24px corner; standard feature glass uses 10px and directory tiles 5px.
- Do not make primary actions oversized 56px rectangular blocks.
- Do not make every comparison cell colorful; blue checks, muted values and fine rules are enough.
- Do not replace the dark translucent sculpture with opaque candy-colored blobs.
- Do not squeeze the closing directory directly beneath the button; retain the art and long light-filled pause.

## Motion and responsive

### Motion

**Observed:**

- Declared action color transition: 0.3s cubic-bezier(0,0.44,0.6,1). Footer links use color 0.3s cubic-bezier(0.28,0.44,0.49,1).
- Declared card borders transition over 0.5s cubic-bezier(0.28,0.44,0.49,1); some media transforms use 0.5s cubic-bezier(0.42,0,0.28,0.99).
- Scrolling stages reveal large media, floating control layers and progressively lit text; media includes video demonstrations.

**Transfer:**

- Use motion to reveal an operation or move light through glass, while keeping the settled layout complete and readable.
- Retain the declared short color and border transitions for control feedback; keep large cinematic scenes distinct from button feedback.

**Unknown:**

- Exact scroll timelines, playback behavior and reduced-motion variants are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 767px/768px, 1023px/1024px and 1240px/1280px; no continuous viewport type formula is established.

**Transfer:**

- On narrow layouts, preserve the promise before the working view and retain an intentional close-up rather than shrinking the entire desktop interface to illegibility.
- Reduce multi-column rails and plan grids to readable stacks; keep the 40px action height and let text wrap.
- Keep curved-glass material visible as an edge or low crest without letting it displace the main promise.

**Unknown:**

- Actual narrow-screen type sizes, navigation behavior and stacking breakpoints remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
