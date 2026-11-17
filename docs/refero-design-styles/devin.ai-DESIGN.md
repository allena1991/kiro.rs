# Devin — translucent working worlds

## Overview

A pale, utilitarian marketing style with an unexpectedly tactile product world. Regular grotesk typography and black capsule actions sit on almost-white ruled canvases, while layered interfaces float over misty blue-green, softly textured imagery. It suits complex software products whose workflows can be demonstrated visually, balancing sparse editorial copy with dense but contained demonstrations.

### Essentials

- The opening sells through a working scene, not giant type: a left-aligned 40px/1.04 regular headline in a 568px column sits above a broad layered interface composition, with 140px top padding.
- Headings sound like two voices in one sentence: 40px regular grotesk with -0.03em tracking pairs muted setup text with near-black payoff text; the centered closing statement grows to 64px/1.
- Actions are black capsules rather than colored badges: 42px high, 20px side padding, white 16px text, paired with a transparent capsule edged in 8% black.
- The page stays almost entirely achromatic outside the media: #f8f8f8 canvas, #191919 text, 6% black rules; #317cff is reserved for short links, markers and proof highlights rather than section fills.
- Product demonstrations have physical depth: white translucent windows with 12–16px corners, 4–8px backdrop blur and soft descending shadows float over muted cloudy imagery. Include this atmospheric working-world device even when the product has no interface: use a legible task/result panel over a textured backdrop.
- The close is a typographic release: two centered 64px lines, muted then dark, separated by 12px, followed by capsule actions after 32px; the footer returns to small gray utility columns.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link blue | `#317cff` | `--color-blue` | link, accent | Short exploration links, tiny square markers and selected benchmark bars. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action black | `#000000` | `--color-black` | action, background | Primary actions and scoped inverse information panels. |
| Primary ink | `#191919` | `--color-ink` | text | Headings and primary marketing copy. |
| Secondary gray | `#7e7e7e` | `--color-secondary` | text | Support copy uses rgba(25,25,25,0.56), appearing approximately this gray on white and slightly darker on the default canvas. |
| Receding gray | `#a3a3a3` | `--color-tertiary` | text | Setup phrases, dates and footer links use rgba(25,25,25,0.4); visible gray shown on white. |
| Card edge | `#ebebeb` | `--color-edge` | border | 8% black card and outlined-action edges on white. |
| Structural hairline | `#f0f0f0` | `--color-rule` | border | 6% black rules on light surfaces; render with alpha to retain the underlying canvas. |
| Workbench canvas | `#f8f8f8` | `--color-canvas` | background | Default landing-page canvas and navigation. |
| Raised white | `#ffffff` | `--color-white` | surface, text | Raised cards and text on black actions; white at 90–94% opacity creates translucent scene panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer proof collections | Electric proof blue | `#2200ff` | `--color-proof-blue` | text | One emphatic line above the outcome-card field. |
| customer story collections | Story caption gray | `#818f9a` | `--color-caption-gray` | text | Company labels beneath story artwork. |
| inverse FAQ panels | Inverse supporting gray | `#8f8f8f` | `--color-inverse-dim` | text | White at 56% alpha over black for answer copy; opacity can further recede answers. |
| inverse FAQ panels | Inverse heading | `#e7e7e7` | `--color-inverse-text` | text | Headings and questions on black panels. |
| customer proof collections | Stat stone | `#efefef` | `--color-stat-card` | surface | Staggered outcome cards. |
| informational pages and product scenes | Bright paper | `#fcfcfc` | `--color-paper` | background, surface | Brighter canvas for informational and proof-led pages; also inner interface surfaces. |

## Typography

- **nbInternationalPro** — All marketing headings, prose, actions and utility navigation. Compact neo-grotesk with plain, open shapes; regular weight does most of the work. If unavailable, use **Inter**. Use 400 for core roles and 500 only in the proof-collection variant; retain tight display tracking. Font stack: "nbInternationalPro", "Inter", system-ui, sans-serif.
- **geistMono** — Technical eyebrows, plan qualifiers and small category markings. Even-width technical lettering, typically uppercase with restrained positive tracking. If unavailable, use **Geist Mono**. Font stack: "geistMono", "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | nbInternationalPro | 400 | 64px | 1 | -0.03em | fixed | Closing statement and large plan prices; also dedicated solution-page opening and inverse FAQ titles. |
| heading | nbInternationalPro | 400 | 40px | 1.04 | -0.03em | fixed | Default hero and major section headings; color can split setup from payoff. |
| chapter | nbInternationalPro | 400 | 32px | 1.2 | -0.02em | fixed | Numbered workflow chapters and plan names. |
| card-heading | nbInternationalPro | 400 | 20px | 1.2 | -0.01em | fixed | Feature captions and update-list titles. |
| question | nbInternationalPro | 400 | 20px | 1.2 | normal | fixed | Accordion question labels. |
| body | nbInternationalPro | 400 | 16px | 1.4 | normal | fixed | Default supporting prose and exploration links. |
| action | nbInternationalPro | 400 | 16px | 1.5 | normal | fixed | Capsule action labels and longer utility copy. |
| utility | nbInternationalPro | 400 | 14px | 1.4 | normal | fixed | Navigation labels and footer columns. |
| eyebrow | geistMono | 400 | 12px | 1.4 | 0.03em, uppercase | fixed | Technical category markers, product labels and plan qualifiers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| benchmark sections | benchmark-stat | nbInternationalPro | 400 | 80px | 1 | -0.04em | fixed | A pair of high-impact result numbers beneath benchmark comparisons. |
| customer proof collections | proof-display | nbInternationalPro | 500 | 64px | 74.4px | -0.04em | fixed | Centered proof headline and large card numerals. |
| customer story collections | story-display | nbInternationalPro | 500 | 61px | 1 | -0.03em | size clamp(36px, 4.233vw, 64px) | Headline beside a featured customer interview. |
| customer proof collections | proof-description | nbInternationalPro | 500 | 24.2px | 1.266 | -0.04em | fixed | Outcome descriptions under proof numerals. |
| testimonial sections | quote | nbInternationalPro | 400 | 20px | 1.25 | -0.01em | fixed | Plainspoken testimonial text in tall outlined cards. |
| solution pages | solution-body | nbInternationalPro | 400 | 18px | 1.4 | normal | fixed | More expansive supporting copy for a specialized solution. |
| customer story collections | story-caption | nbInternationalPro | 400 | 14.8px | 1.5 | normal | fixed | Customer name and short case-study title under portrait-format artwork. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Core marketing type stays at weight 400, including headlines and prices. The proof-collection variant uses 500, not a generalized bold hierarchy.
- Tracking tightens from normal body spacing to -0.01em at 20px, -0.02em at 32px and -0.03em at 40–64px.
- Use muted setup and dark conclusion as a color relationship within the same heading, not as a smaller subtitle. Technical labels are a separate mono register.

## Layout

**Density:** Airy outside demonstrations, compact inside them: large chapter intervals and short copy surround visually dense working scenes.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Feature title to support copy; compact internal groups. |
| 10px | Gap between paired hero actions. |
| 12px | Closing headline line gap and chapter link separation. |
| 16px | Hero heading to support copy, grid gutters and inner rail inset. |
| 24px | Card padding and image-to-caption separation. |
| 32px | Two-column chapter gutter and closing heading-to-actions gap. |
| 36px | Integration icon-to-caption gap and plan-card group spacing. |
| 40px | FAQ row vertical padding and testimonial content separation. |
| 60px | Main container side padding and standard section inset. |
| 64px | Footer vertical inset and large feature-grid row gaps. |
| 100px | Hero actions to main product scene. |
| 120px | Closing-section top inset and separation between workflow chapters. |
| 140px | Default hero top inset. |
| 200px | Major inter-section gaps on solution pages. |

### Containers and grids

- **page-container**: max width 1400px · side padding 60px. Centered outer container. At a 1440px viewport its 20px outer margin plus padding yields 80px content margins.
- **ruled-content**: max width 1280px · side padding 16px. Hairline vertical rails bound the default landing-page body; content is inset inside the rails.
- **hero-copy**: max width 568px. Left-aligned opening column; support text is narrower, about 455px.
- **workflow-pair**: 2 columns · gap 32px. Equal-width image and copy columns. Copy rests toward the bottom of each image and alternates sides across chapters.
- **feature-pair**: 2 columns · gap 8px. Near-adjoining image-led feature tiles, with captions directly below.
- **integration-grid**: 4 columns · gap 0px. Four columns with left-hand separators; desktop-product variant expands to five columns.
- **plan-grid** (only for pricing sections): 3 columns · gap 16px. Three individual plan cards; organization plans use two wide columns.
- **story-grid** (only for customer story collections): 4 columns · gap 14.4px. Portrait-format artwork and short captions, repeated as an editorial gallery.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | scene-windows | 16px |
|  | secondary-scene-panels | 12px |
| pricing and inverse FAQ panels | information-panels | 4px |
| customer proof collections | proof-cards | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-window | `0px 25px 50px -12px rgba(0,0,0,0.25)` | Foreground scene panel, not ordinary marketing cards. |
| back-window | `0px 8.9px 13.4px -2.7px rgba(0,0,0,0.06)` | Lighter depth under the main translucent product window. |

### Surfaces

#### Workbench canvas · level 0

**Use:** Default new marketing and landing-page background.

**CSS:** `background: #f8f8f8; color: #191919`

#### Ruled band · level 0

**Use:** Structural sections and workflow chapters.

**CSS:** `border-left: 1px solid rgba(0,0,0,0.06); border-right: 1px solid rgba(0,0,0,0.06); padding: 60px 16px`

**Observed:** Long shared rails connect adjacent sections; horizontal rules mark selected transitions.

**Transfer:** Use rails to organize the page rather than outlining every content item.

#### Floating glass window · level 2

**Use:** Main product scene and foreground result panel.

**CSS:** `background: rgba(255,255,255,0.9); border-radius: 16px; backdrop-filter: blur(8px); box-shadow: 0px 25px 50px -12px rgba(0,0,0,0.25); overflow: hidden`

**Observed:** A pale translucent main application sits behind a smaller, more legible result panel. Some secondary scenes use 12px corners and 4px blur.

**Transfer:** Reserve depth and translucency for staged demonstrations; use clear text and structured rows inside the front panel.

#### Bright informational canvas · level 0

**Only for:** informational pages

**Use:** Specialized solution, pricing and story pages.

**CSS:** `background: #fcfcfc; color: #191919`

#### Inverse FAQ panel · level 1

**Only for:** pricing and solution pages

**Use:** High-contrast objection handling near the end of informational pages.

**CSS:** `background: #000000; color: #e7e7e7; border: 1px solid rgba(0,0,0,0.08); border-radius: 4px; padding: 36px`

**Observed:** A contained dark rectangle, not a dark page theme.

**Transfer:** Keep it within the same content width as the light sections.

#### Proof stone · level 1

**Only for:** customer proof collections

**Use:** Outcome cards in a staggered field.

**CSS:** `background: #efefef; border-radius: 12px; overflow: hidden`

**Observed:** Flat gray cards have no visible elevation; their staggered positions supply the drama.

**Transfer:** Use one strong number, one compact explanation and a faint organization category.

## Components

### Primary button

**Use:** Main conversion and paid-plan selection.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #000000; color: #ffffff; height: 42px; padding: 0px 20px; border-radius: 9999px`

**Text style:** `action` — nbInternationalPro 400 · 16px/1.5

**Observed:** Pairs with Secondary button; header version is 28px high with 12px side padding and 14px/21px labels. Paid plans use full-width black actions; the entry plan uses the outline version.

**States:** Declared: hover opacity 0.8; focus-visible solid 2px outline with 4px offset. Header focus offset is 2px.

### Secondary button

**Use:** Demo booking and secondary exploration.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: transparent; color: #191919; border: 1px solid rgba(0,0,0,0.08); height: 42px; padding: 0px 20px; border-radius: 9999px`

**Text style:** `action` — nbInternationalPro 400 · 16px/1.5

**Observed:** Same silhouette as Primary button but visually recedes into the canvas.

**States:** Declared: hover background-color rgb(0 0 0 / .06); focus-visible solid 2px outline with 4px offset.

### Navigation item

**Use:** Compact fixed-header browsing.

**CSS:** `display: flex; align-items: center; gap: 4px; height: 28px; padding: 1px 8px 0px 12px; border-radius: 200px; color: #000000; background: transparent`

**Text style:** `utility` — nbInternationalPro 400 · 14px/1.4

**Observed:** Small wordmark at left, compact links beside it, conversion controls pushed right. Dropdown categories have a tiny downward chevron; direct links use symmetrical 12px side padding. Navigation sits on a 52px canvas-colored fixed bar.

**States:** Declared: hover background-color rgb(0 0 0 / .06); focus-visible solid 2px outline, -2px offset, currentcolor.

### Exploration link

**Use:** Connect feature descriptions to deeper product detail.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; color: #317cff; text-decoration: none`

**Text style:** `body` — nbInternationalPro 400 · 16px/1.4

**Observed:** Text followed by a 20px chevron; sits below a short support paragraph rather than inside a filled control.

### Integration tile

**Use:** Show compatibility through familiar tools and a specific action.

**CSS:** `display: flex; flex-direction: column; gap: 36px; padding: 0px 16px; border-left: 1px solid rgba(0,0,0,0.06)`

**Text style:** `body` — nbInternationalPro 400 · 16px/1.4

**Observed:** Monochrome icon at top and muted short caption below; first tile in a row can omit the left separator. Product-specific variant adds tool names and uses five columns.

**States:** Declared: hover not specified; focus-visible solid 2px blue outline with 4px offset.

### Update row

**Use:** A compact release or news ledger.

**CSS:** `display: grid; grid-template-columns: 75px minmax(0px, 1fr) 106px max-content; column-gap: 36px; row-gap: 8px; align-items: center; padding: 15px 0px 16px; border-top: 1px solid rgba(0,0,0,0.06)`

**Text style:** `card-heading` — nbInternationalPro 400 · 20px/1.2 · tracking -0.01em

**Observed:** Muted date, dark single-line title, smaller muted category, then right chevron. First row has no top rule. A narrow left introduction column includes a small artwork thumbnail.

**States:** Declared: hover color rgb(49 124 255); focus-visible same blue, solid 2px outline with 4px offset.

### FAQ row

**Use:** Reveal practical answers without a dense wall of prose.

**CSS:** `border-top: 1px solid rgba(0,0,0,0.08); padding: 40px 0px`

**Text style:** `question` — nbInternationalPro 400 · 20px/1.2

**Observed:** Question on left, thin plus at right; an open item swaps plus for minus and adds 16px/24px answer copy. Default product-page variant remains on the light canvas beside a left heading column; inverse variant uses white 12% rules and light question text inside Inverse FAQ panel.

**States:** Declared: hover not specified; focus-visible not specified. Answer opacity transition is 0.2s cubic-bezier(0, 0, .2, 1).

### Footer link

**Use:** Low-emphasis utility navigation.

**CSS:** `color: rgba(25,25,25,0.4); text-decoration: none`

**Text style:** `utility` — nbInternationalPro 400 · 14px/1.4

**Observed:** Three columns of small links under darker labels. Links have 4px vertical gaps, labels are separated by 8px; a gray wordmark and compact maker-credit graphic occupy the wider left area.

**States:** Declared: hover color rgb(51 125 244); focus-visible same color, solid 2px outline with 4px offset.

### Plan card

**Only for:** pricing sections

**Use:** Present a tier with clear price and incremental benefits.

**CSS:** `display: flex; flex-direction: column; gap: 36px; background: #ffffff; border: 1px solid rgba(0,0,0,0.08); border-radius: 4px; padding: 24px`

**Text style:** `chapter` — nbInternationalPro 400 · 32px/1.2 · tracking -0.02em

**Observed:** Muted tier name, optional tiny mono status badge, 64px price with small mono billing qualifier, full-width action, then ruled benefit rows with blue checks. Individual plans use three equal columns; organization plans use two. Compact product-page cards omit benefit lists.

**Transfer:** Make price hierarchy and comparison easy without a large colored featured-plan fill.

### Testimonial card

**Only for:** testimonial sections

**Use:** Direct human proof in a horizontally advancing strip.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 40px; min-height: 420px; border: 1px solid rgba(0,0,0,0.06); padding: 24px 24px 18px`

**Text style:** `quote` — nbInternationalPro 400 · 20px/1.25 · tracking -0.01em

**Observed:** Monochrome organization mark above a hanging-quote paragraph; name and muted role are pinned near the bottom. Three full cards and part of another are visible; small arrows and dash indicators sit beside the section heading.

## Imagery and graphics

### Atmospheric working world

**Use:** Signature backdrop for the main product scene and repeated capability illustrations.

**Observed:** Soft blue-green, silver-gray and lavender clouds resemble defocused fabric or pearlescent film with fine grain. Crisp white application windows overlap this material, often extending beyond a rectangular image edge. Scene images usually occupy half a chapter; the opening expands to nearly the full content width.

**Transfer:** Create a truthful task/result composition for the new product. Without a mature interface, use a small set of legible document, activity and result panels; the atmospheric backing and layered depth remain.

**Build:** Make a 4:3 rectangular stage with a pale gray base. Layer oversized translucent teal and blue-gray radial ellipses at opposing corners, a low-opacity lavender ellipse through the center, and a broad white diagonal band; blur the color layers by 40–80px. Add a fine monochrome SVG noise layer at low opacity. Place two or three white translucent windows above it, with 12–16px corners and soft downward shadows. Keep color subdued and text panels readable; exact cloud contours are not essential.

### Opening collage

**Use:** Background fragments behind the broad first-screen application scene.

**Observed:** Small grayscale paper, technical diagrams, machinery and historical-computing photographs float at different scales behind the main windows. Some are softened or partly hidden; they read as context, not a card gallery.

**Transfer:** Use a few restrained technical artifacts relevant to the new field, keeping the working interface dominant.

**Build:** Position a handful of 195–352px image fragments behind the main window, mixing portrait and landscape proportions. Desaturate them, soften selected distant fragments and lower their contrast. Mask the lower scene into the page canvas rather than giving each fragment an outlined card.

### Reflective object vignette

**Only for:** specialized solution pages

**Use:** A compact physical metaphor opposite a product-specific promise.

**Observed:** A chrome padlock stands on a reflective pale ground with grayscale mist and faint square pixels. The object is centered within a 608px by 408px scene; illumination is soft and metallic, not saturated.

**Transfer:** Choose one physically meaningful object for the new capability. Minimum equivalent: a carefully shaded monochrome SVG silhouette with highlight contours and a blurred contact shadow.

**Build:** Use a pale rectangular stage; center a metallic SVG or rendered object with broad white edge highlights and gray interior gradients. Add an elliptical contact shadow, faint vertically stacked squares at varying opacities and a misty white fade near the ground.

### Customer story artwork

**Only for:** customer story collections

**Use:** Portrait-format covers in a four-column story gallery.

**Observed:** Colored atmospheric scenes, luminous abstract ribbons, textured gradients, landscapes and occasional photography carry centered white customer marks. Each cover is visually rich but the caption below is small and plain; the imagery is far more colorful than the surrounding page.

**Transfer:** Use licensed organization marks or neutral project identifiers on coherent portrait art, adapting the background palette to each story without coloring the page canvas.

**Build:** Create a 3:4 portrait composition using a deep muted color base, one broad translucent curved ribbon or horizon glow, fine grain and centered white project lettering. Vary the dominant hue between cards while keeping the same tonal depth and rounded clipping.

### Interview media

**Only for:** customer stories and solution introductions

**Use:** Featured human explanation beside a short product or outcome statement.

**Observed:** Natural office or studio conversation, medium framing, restrained daylight or warm interior lighting. Video is a wide rectangle; featured story media has softly rounded corners and a centered play control.

**Transfer:** Use real people explaining a concrete result, in a simple environment with believable light; avoid theatrical full-bleed lifestyle photography.

### Icons

**Observed:** Marketing controls use small filled SVG chevrons around 14–20px. Integration marks are monochrome and often 32–40px. Thin plus/minus marks signal accordions; blue checks mark plan benefits.

**Transfer:** Choose compact, low-detail filled symbols and consistent thin disclosure marks. Keep tool logos monochrome outside the richer story-cover variant.

## Section recipes

How recurring sections are built.

### First screen: Working-world opening

**Observed:** A 52px fixed navigation bar sits on the pale canvas. The opening begins at 140px with a left-aligned 40px/1.04 regular heading spanning about two-fifths of the content width, usually two lines, followed after 16px by a narrow muted 16px support paragraph. Primary button and Secondary button follow about 27px later. After 100px of breathing space, a broad application window spans roughly four-fifths of the content width, with a smaller result panel overlapping its right side. Back-to-front layers are the canvas, desaturated collage fragments, a translucent main workspace and a crisp front result panel. Within the first 900px, the complete promise, support, both actions and the upper half of the working scene are visible; the lower scene and logo strip continue below the fold.

**Transfer:** Use a similarly short promise and a broad task-to-result scene for a different product. Preserve the disproportion between modest headline and expansive object. Dedicated downloadable-product openings use one large app view and a single download action; specialized solutions use a 64px headline beside a compact object vignette; story collections use an interview and a result; pricing starts with a title and immediately useful plan cards.

**Avoid:** Do not replace the working scene with an enormous centered slogan, a dashboard thumbnail in a small card, or unrelated full-bleed stock imagery.

**Text style:** `heading` — nbInternationalPro 400 · 40px/1.04 · tracking -0.03em

### Two-tone heading pair

**Observed:** A muted setup line and dark payoff share the heading recipe. They may stack or continue inline, with no extra typographic ornament; the dark portion carries the concrete benefit.

**Transfer:** Write an ordinary setup and a specific outcome. Preserve the shared scale instead of turning the first phrase into an eyebrow.

**Text style:** `heading` — nbInternationalPro 400 · 40px/1.04 · tracking -0.03em

### Image-led feature grid

**Observed:** Feature-pair places two near-adjoining 4:3 scenes above 20px captions and 16px muted support copy. A lower row can use three smaller scenes; row separation is about 60–64px.

**Transfer:** Group related capabilities by user benefit, giving each its own small truthful demonstration.

**Text style:** `card-heading` — nbInternationalPro 400 · 20px/1.2 · tracking -0.01em

### Numbered workflow chapter

**Observed:** Workflow-pair alternates a 607px by 455px working-world image with bottom-aligned text. A muted 32px two-digit ordinal precedes a 32px chapter title, short body paragraph and Exploration link. Chapters are separated by 120px.

**Transfer:** Explain a process through a few clearly distinct stages; choose the number of stages to fit the new narrative.

**Text style:** `chapter` — nbInternationalPro 400 · 32px/1.2 · tracking -0.02em

### Compatibility band

**Observed:** A two-tone heading sits above Integration tile rows. Ruled band keeps the grid aligned; default layout uses four columns and two rows, while a product-specific variant is denser with five columns and tool names.

**Transfer:** Show what each integration enables, not only a wall of logos.

### Release ledger

**Observed:** A narrow left heading and small artwork thumbnail accompany Update row in a wider right column. The surrounding band uses 60px vertical insets and a continuous shared rail.

**Transfer:** Use for releases, research, company updates or another genuinely chronological body of proof.

### Centered closing statement

**Observed:** A top hairline introduces a centered two-line statement: muted setup then dark payoff at 64px/1, with a 12px interline gap. Actions sit 32px below. The band has 120px top and 80px bottom padding; no illustration competes with the words.

**Transfer:** Include this typographic release on new landing pages, using a product-relevant tension and resolution rather than a generic sales slogan.

**Text style:** `display` — nbInternationalPro 400 · 64px/1 · tracking -0.03em

### Utility ending

**Observed:** After 80px of separation, a top rule begins a 360px footer with 64px vertical padding. A gray wordmark and small maker-credit artwork occupy the left two-fifths; three columns of Footer link fill the right. Solution and pricing variants arrive here after a contained black FAQ; the downloadable-product variant instead uses a light two-column FAQ after compact plans and trust statistics.

**Transfer:** End with legible understated navigation and a small original maker credit. Retain the same light canvas even when the preceding information panel is black.

**Text style:** `utility` — nbInternationalPro 400 · 14px/1.4

### Quantified comparison

**Only for:** benchmark sections

**Observed:** Two-tone heading and compact explanation lead to full-width ruled rows. A blue highlighted bar identifies the featured product while alternatives recede to gray. A small methodology note sits below; two 80px result numbers follow in columns with left rules and 24px insets.

**Transfer:** Use verified comparison dimensions, restrained bars and compact methodology. Keep the numbers visually stronger than decorative chart furniture.

**Text style:** `benchmark-stat` — nbInternationalPro 400 · 80px/1 · tracking -0.04em

### Story collection and outcome field

**Only for:** customer proof collections

**Observed:** A featured interview and outcome lead into rounded filter capsules, then a four-column portrait cover gallery with small gray organization labels. The ending shifts to a centered 64px medium-weight statement, its first line electric blue, above five staggered columns of flat gray cards. Large numerals sit above compact descriptions, with faint organization categories near the bottom; the field expands beyond the normal text rails.

**Transfer:** Use an editorial gallery for individual stories and a staggered field for independently verified outcomes. This page type ends with proof and the utility footer, not an additional conversion banner.

**Text style:** `proof-display` — nbInternationalPro 500 · 64px/74.4px · tracking -0.04em

### Plan selection and comparison

**Only for:** pricing pages

**Observed:** A two-line 64px heading uses dark product name and muted page purpose; short support and a mono blue announcement sit opposite it. Plan card groups lead to a restrained provider-logo band and a six-column ruled comparison table: feature names at left, five plan columns, black checks and red outlined exclusions. Category separators remain plain text rather than colored bands.

**Transfer:** Keep the opening decision-ready and move detailed differentiation below it. Finish objection handling with Inverse FAQ panel and the utility footer.

**Text style:** `display` — nbInternationalPro 400 · 64px/1 · tracking -0.03em

## Page flow

**Storyline:** Promise → tangible working demonstration → capability explanation → credible proof and ecosystem fit → decision support → typographic release or objection handling → utility ending.

### Broad product landing page

1. **Promise and demonstration** — Modest left-aligned introduction over a broad layered working scene.
2. **Social proof** — Narrow monochrome moving logo strip.
3. **Capability explanation** — Image-led feature grid, then alternating numbered workflow chapters.
4. **Ecosystem fit** — Compatibility grid with action-oriented captions.
5. **Confidence** — Release ledger and ruled trust-control band.
6. **Closing call** — Centered muted-to-dark statement and paired actions, then utility footer.

**Transfer:** Lead with a concrete scene of work, then choose the chapters and proof that reduce uncertainty for the new product.

### Specialized solution marketing

1. **Focused promise** — Large heading and actions beside a reflective object vignette, followed by a slim announcement strip.
2. **Quantified proof** — Ruled benchmark bars, methodology note and oversized result pair.
3. **Mechanism explanation** — Human introduction video and alternating task/result panels.
4. **Offering detail** — Two complementary product cards and a broad pale service-program band.
5. **Conversion and objections** — Centered call, contained black FAQ and light utility footer.

**Transfer:** Substitute a capability-specific metaphor and genuinely substantiated result; preserve the factual explanation before the sales close.

### Plan selection

1. **Choice framing** — Two-tone title and a concise model announcement.
2. **Pricing** — Individual plan trio followed by organization-plan pair.
3. **Compatibility reassurance** — Small provider-logo band.
4. **Detailed comparison** — Long ruled feature matrix with compact category separators.
5. **Objection handling** — Black FAQ panel and utility footer, without a separate closing CTA.

**Transfer:** Make selecting and comparing plans the dominant work; do not force a general-purpose hero into this page type.

### Customer proof library

1. **Featured proof** — Large editorial heading, result teaser and interview video.
2. **Discovery** — Small filter capsules above a four-column cover gallery.
3. **Quantified proof** — Electric-blue closing line and staggered gray outcome-card field.
4. **Utility ending** — Light footer directly after the proof field.

**Transfer:** Let credible stories carry the colorful media treatment; use the ending for a synthesis of outcomes rather than another pitch.

### Downloadable-product landing page

1. **Product introduction** — Short heading, download action, small technical announcement and broad application window.
2. **Capability chapters** — Alternating demonstrations, paired features and a compact tool-logo band.
3. **Human proof and ecosystem fit** — Tall quote carousel and named integration grid.
4. **Closing call** — Centered two-line statement with download and demo actions.
5. **Decision support** — Compact five-plan row, large trust statistics and light two-column FAQ.
6. **Utility ending** — Shared light footer.

**Transfer:** Keep the installed product visually concrete; support download with compatibility, peer reassurance and migration answers.

## Writing

Matter-of-fact technical confidence with a conversational teammate metaphor. Benefits are explained through actions and visible outcomes, not abstract declarations of transformation.

**Do not copy:** Do not reuse Devin or Cognition names, logos, interface artwork, customer marks, quotations, proprietary feature names, benchmark claims, prices or performance figures as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader; refer to the product by name when describing what it does. Treat the product as an active participant without making the prose cute.
- **Rhythm:** Short sentence-case headings and compact one- or two-sentence support paragraphs. Workflow headings are often two to five words; CTA labels are two to four words. Periods are uncommon in short labels, but normal prose punctuation remains.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Introduce the product through a recognizable role in the reader's working life. | About 8–12 words | “Meet [Brand], your team's autonomous software engineer” |
| Supporting line | Describe concrete operating conditions and the completed result in one sentence. | About 20–30 words | “[Brand] runs in the cloud or on your machine, tests in its own browser, and won't stop until the PR is ready to merge” |
| Chapter heading | Pair verbs that describe a useful stage of work. | 2–4 words | “Understand and plan”<br>“Automate and maintain” |
| Primary action | Direct low-friction verb; name the destination or platform when useful. | 2–4 words | “Get started”<br>“Download for MacOS” |
| Proof headline | Name the actor and a specific measurable improvement. | One compact sentence | “How Citi cut 30% of tech vendor spend with [Brand]” |
| Closing statement | Acknowledge an unfinished ambition, then resolve it through the product. | Two short lines | “Stop deprioritizing”<br>“Do it all with [Brand]” |

**Words and phrasing to use:** build; test; review; ship; your team; one place; works with; find and fix; plan; run

**Avoid:** revolutionary; unleash; magic; game-changing; supercharge everything; limitless possibilities

**Rules:**

- Explain what actually happens after the user delegates or starts a task.
- Keep technical nouns when they make the workflow more credible; explain the outcome beside them.
- Pair a benefit with an operating detail rather than adding a second slogan.
- Use result numbers only with a clear unit, context and substantiation.

## Do's and Don'ts

### Do

- Keep core 40px headlines at weight 400 and -0.03em tracking.
- Let product scenes dominate image area while the hero copy stays within 568px.
- Use 1px alpha-black rules to align long sections across shared rails.
- Keep paired actions at 42px high with 10px between them.
- Use 60px standard section insets and 120px chapter separation to distinguish prose from demonstrations.
- Put translucency, 12–16px corners and soft shadows in the working scenes, not everywhere.
- Keep exploration links blue and unfilled, with a small trailing chevron.
- Close ordinary landing pages with the 64px two-tone typographic release and compact utility footer.

### Don't

- Do not turn the 40px default opening into a 96px bold startup slogan.
- Do not use the electric proof blue as the default button or page background.
- Do not round flat pricing panels to 24px; their corners are 4px.
- Do not give every feature an elevated white card; the layout relies on open canvas and shared rails.
- Do not apply the 500-weight story typography to ordinary landing-page prose.
- Do not make integration captions as dark and prominent as primary headings; they are supporting information.
- Do not brighten the atmospheric backgrounds into high-saturation mesh gradients behind body copy.
- Do not turn the footer into a giant wordmark billboard; its mark and links recede into gray.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary action duration is 0.2s; navigation items declare 0.15s.
- The logo strip declares a 30s linear infinite scroll. The opening collage declares a linear infinite pan, but its effective duration is not established.
- Small working indicators use shimmer and pulse; declared shimmer is 2.5s ease-in-out and pulse is 2s cubic-bezier(.4, 0, .6, 1).

**Transfer:**

- Keep movement concentrated in the working world and proof strip; conversion controls use the restrained opacity or background changes described in their states.
- For a static implementation, preserve the overlapping scene layers rather than replacing them with animated decorative blobs.

**Unknown:**

- Effective collage speed, scroll choreography and complete reduced-motion behavior.

### Responsive

**Observed:**

- CSS declares breakpoints including 640px, 768px, 940px and 1024px. Navigation is desktop-only at the large breakpoint; chapter grids declare a single-column base and two-column large-screen layout.
- Plan groups declare stacked base layouts and side-by-side cards from the medium breakpoint. Integration grids declare two base columns and four medium-screen columns.

**Transfer:**

- On narrow layouts, stack the working image with its explanatory copy and preserve readable panel content rather than shrinking an entire desktop composition.
- Retain pale canvas, black capsule actions and two-tone heading relationships as columns collapse.

**Unknown:**

- Exact mobile font scaling, mobile navigation behavior and the complete narrow-screen collage composition.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
