# Amplemarket — human doodles, liquid light

## Overview

An optimistic software style that pairs tightly set grotesk headlines with pencil-like human drawings and pools of luminous color. Warm off-white expanses alternate with near-black product and customer chapters; lemon, pink, mint and lavender bring warmth to proof. Large interface demonstrations carry the substance, while compact controls and dense testimonial walls keep the spacious composition commercially grounded.

### Essentials

- Regular headlines feel almost hand-composed: 56px/1 at weight 400 with -0.05em tracking for the opening, 44px/1.1 with -0.04em for chapters, and occasional slanted letterforms rather than an entirely italic headline.
- The opening is a centered promise above an oversized working product: a 472px headline block, 400px support line, 448px inline email form and roughly 993px-wide demo entering the lower third of the first screen. A black line drawing sits off to one side, riding a blurred orange–cream–lavender light trail; use a simple original human/tool sketch if no product illustration exists.
- Controls stay small and squared-soft, not pill-shaped: 40px buttons with 8px corners, 12px 16px padding and 14px medium text; email fields use 48px height and 12px corners.
- Color is staged rather than spread everywhere: long #f6f5f3 and #111111 chapters dominate, with orange and lavender in soft media glows, cyan behind capability scenes, and pastel proof cards. Keep ordinary text and actions neutral; let colored artwork occupy the lower hero, not obscure the promise.
- Interfaces are physical paper-like layers: white 12px-cornered product panels, fine 4% ink edges, lifted multilevel shadows and a few overlapping notification cards. A working UI composition is the fallback when polished demo media is unavailable.
- Human marks interrupt the software polish: black pencil-like characters, loose arrows, small hearts and emphasis rays sit beside headings or interactions. Pair these with a structured 880px-wide proof mosaic of 205px × 210px pastel metrics and double-width quotes.
- The closing changes voice visually: a two-line 56px, weight-900 uppercase statement with 0.8 line height, one orange–cream–lavender glowing word, then the compact email form and a deep black directory footer. Preserve this bold glowing ending even on otherwise light pages.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Liquid orange | `#e8400d` | `--color-orange` | accent | Warm ends of the hero light field and glowing closing word, not everyday button fill. |
| Light lavender | `#d0b2ff` | `--color-glow-lavender` | accent | Central glow color and small iridescent badges. |
| Light cream | `#ffeed8` | `--color-glow-cream` | accent | Warm transition between lavender and orange light. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mist | `#99fff9` | `--color-cyan` | accent, background | Cool capability-stage light field and alternate glow treatment. |
| Lemon proof | `#fff7a8` | `--color-lemon` | surface | Flat metric cards. |
| Mint proof | `#b7efb2` | `--color-mint` | surface | Flat metric cards. |
| Pink proof | `#ffd7f0` | `--color-pink` | surface | Flat metric cards. |
| Violet proof | `#e2ddfd` | `--color-violet` | surface | Flat metric cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#111111` | `--color-ink` | text, background, action | Primary text, dark chapters and primary conversion buttons. |
| Warm charcoal | `#272625` | `--color-charcoal` | surface, background | Dark quote cards and fields; pricing uses this hue at 40% and 80% over near-black. |
| Charcoal hairline | `#302f2e` | `--color-dark-edge` | border | Visible 4% white edge on charcoal cards; use rgba(255,255,255,0.04). |
| Secondary ink | `#6d6c6b` | `--color-muted-ink` | text | Visible equivalent of 60% #111111 on the warm canvas; supporting copy. |
| Secondary inverse | `#a0a0a0` | `--color-muted-light` | text | Visible equivalent of 60% white on near-black; inverse directory links and attribution. |
| Control stone | `#eae8e5` | `--color-stone` | action, surface | Light button fill and compact award panels. |
| Paper hairline | `#edecea` | `--color-light-edge` | border | Visible 4% ink edge on warm canvas; panels and separators use rgba(17,17,17,0.04). |
| Warm canvas | `#f6f5f3` | `--color-canvas` | background, surface, text | Default light page canvas; also pale text in the oversized inset call. |
| Porcelain | `#fbfaf9` | `--color-light-band` | background, surface | Proof and editorial bands; small feature cards. |
| Paper white | `#ffffff` | `--color-white` | text, surface, action | Product panels, light fields and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| mid-page conversion interludes | Midnight indigo | `#10054d` | `--color-indigo` | background | Inset oversized conversion panel. |

## Typography

- **Labil Grotesk Variable** — All marketing typography, including labels, headlines, metrics and controls. Compact contemporary grotesk with open round forms and playful slanted alternates. Regular text carries most of the hierarchy; very heavy cuts are reserved for conversion statements. If unavailable, use **Inter**. Use 400, 500 and 900; retain tight tracking and introduce only isolated italic accents. Font stack: "Labil Grotesk Variable", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Labil Grotesk Variable | 400 | 56px | 1 | -0.05em | Primary opening promise; balanced into two or three short lines. |
| closing-display | Labil Grotesk Variable | 900 | 56px | 0.8 | -0.03em, uppercase | Bold two-line closing conversion statement. |
| heading | Labil Grotesk Variable | 400 | 44px | 1.1 | -0.04em | Chapter headings and editorial heading pairs. |
| heading-small | Labil Grotesk Variable | 400 | 36px | 1.1 | -0.03em | Capability titles, proof-section headings and metric values. |
| quote | Labil Grotesk Variable | 400 | 36px | 1.2 | -0.03em | Standalone testimonial in a narrow centered column. |
| card-heading | Labil Grotesk Variable | 400 | 24px | 1.1 | -0.02em | Small capability cards and FAQ questions. |
| lead | Labil Grotesk Variable | 400 | 20px | 1.3 | -0.02em | Hero support and testimonial-wall quote text. |
| body | Labil Grotesk Variable | 400 | 16px | 1.3 | -0.01em | Standard support paragraphs, article titles and metric labels. |
| caption | Labil Grotesk Variable | 400 | 14px | 1.3 | normal | Logo-grid migration captions and quote attribution. |
| directory | Labil Grotesk Variable | 400 | 14px | 1.4 | normal | Footer links and article metadata. |
| button | Labil Grotesk Variable | 500 | 14px | 1 | normal | Navigation and button labels. |
| eyebrow | Labil Grotesk Variable | 500 | 12px | 1.2 | 0.012em, uppercase | Directory category headings; compact uppercase labels. |
| announcement | Labil Grotesk Variable | 400 | 12px | 1 | normal | One-line announcement link and small trust text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| mid-page conversion interludes | interlude-display | Labil Grotesk Variable | 900 | 84px | 0.8 | -0.03em, uppercase | Oversized inset call with cool gradient emphasis. |
| pricing pages | price | Labil Grotesk Variable | 400 | 44px | 1 | -0.04em | Plan amount or custom-price descriptor. |
| focused feature pages | feature-eyebrow | Labil Grotesk Variable | 400 | 12px | 1.2 | 0.012em, uppercase | Product-category and FAQ lead-in labels. |

**Notes:**

- The large regular scale tightens from -0.03em at 36px to -0.05em at 56px. Do not make chapter headings semibold to manufacture hierarchy.
- Use isolated italic-looking or alternate letter groups as a human inflection; the full headline remains readable as one phrase.
- The heavy uppercase closing is a deliberate contrast to regular sentence-case chapters, not the default headline style.

## Layout

**Density:** Airy chapter spacing with compact controls and denser proof clusters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon gaps and close metadata relationships. |
| 12px | Plan and small-card gutters. |
| 20px | Quote-card padding and editorial/proof grid gutters. |
| 24px | Paragraph separation and plan-card inner spacing. |
| 28px | Heading-to-action spacing and hero content grouping. |
| 56px | Desktop side gutters and section-heading-to-main-object gap. |
| 84px | Feature-page section padding. |
| 100px | Primary chapter top padding and closing call padding. |
| 144px | Large testimonial and editorial section padding. |
| 168px | Centered opening content top space. |

### Containers and grids

- **wide-container**: max width 1328px · side padding 56px. Main desktop stage inside the 1440px viewport; centered with wide media and editorial grids.
- **content-container**: max width 1104px · side padding 56px. Narrower product, comparison and dark proof sections.
- **proof-mosaic**: max width 880px · 4 columns · gap 20px. Single-width metric tiles interleaved with double-width quote tiles.
- **quote-column**: max width 656px. Large standalone testimonial, left aligned within a centered column.
- **editorial-grid**: 4 columns · gap 20px. Four horizontal article previews; three portraits plus an award column on company pages.
- **feature-split**: max width 1104px · 2 columns · gap 28px. Focused feature opening with left promise/form and right floating interface illustration.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 8px |
|  | cards-and-fields | 12px |
|  | small-feature-panels | 16px |
| pricing pages | plan-panels | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| interface-lift | `rgba(17, 17, 17, 0.12) 0px 26px 60px -6px, rgba(17, 17, 17, 0.02) 0px 28px 28px -14px, rgba(17, 17, 17, 0.04) 0px 6px 6px -3px, rgba(17, 17, 17, 0.04) 0px 1px 1px -0.5px` | Floating product images, not ordinary proof tiles. |
| stack-edge | `rgba(17, 17, 17, 0.02) 0px -6px 6px 0px, rgba(17, 17, 17, 0.01) 0px -23px 9px 0px` | White layered capability decks. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default marketing-page field.

**CSS:** `background: #f6f5f3; color: #111111`

#### Porcelain band · level 0

**Use:** Proof, editorial and focused feature sections.

**CSS:** `background: #fbfaf9; color: #111111`

#### Dark chapter · level 0

**Use:** Product theater, testimonial wall and footer.

**CSS:** `background: #111111; color: #ffffff`

**Observed:** Full-width near-black bands create long coherent chapters rather than separate black tiles.

**Transfer:** Invert typography and controls together.

#### Paper deck · level 1

**Use:** Layered capability panels.

**CSS:** `background: #ffffff; border: 1px solid rgba(17,17,17,0.04); border-radius: 12px; box-shadow: rgba(17,17,17,0.02) 0px -6px 6px 0px, rgba(17,17,17,0.01) 0px -23px 9px 0px; backdrop-filter: blur(20px)`

**Observed:** Several full panels recede behind the active one, exposing header strips and narrower widths.

**Transfer:** Use an actual layered deck, not four equal-height cards.

#### Dark quote surface · level 1

**Use:** Customer quote wall.

**CSS:** `background: #272625; border: 1px solid rgba(255,255,255,0.04); border-radius: 12px`

#### Form trust backing · level 1

**Use:** Backing below the white hero field and trust row.

**CSS:** `background: rgba(17,17,17,0.03); border-radius: 12px; backdrop-filter: blur(10px)`

**Observed:** The dark ending switches to 5% white backing; field and button invert as a unit.

#### Inset indigo · level 0

**Only for:** mid-page conversion interludes

**Use:** Distinct oversized mid-page conversion pause.

**CSS:** `background: #10054d; border-radius: 12px; padding: 100px 112px 84px`

**Observed:** A pale heavy heading with a cyan/lavender glowing phrase sits above a compact conversion form.

#### Plan glass · level 1

**Only for:** pricing pages

**Use:** Plan-selection panels on the dark opening.

**CSS:** `background: rgba(39,38,37,0.4); border: 1px solid rgba(255,255,255,0.04); border-radius: 20px; backdrop-filter: blur(50px)`

**Observed:** Recommended middle plan uses 80% charcoal, not a saturated brand-color slab.

## Components

### Primary button

**Use:** Main conversion action on light surfaces.

**CSS:** `background: #111111; color: #ffffff; border: 1px solid transparent; border-radius: 8px; padding: 12px 16px; height: 40px; display: flex; align-items: center; gap: 8px`

**Text style:** `button` — Labil Grotesk Variable 500 · 14px/1

**Observed:** In the email form the button is inset into the field on the right; the dark closing uses the light version.

**Transfer:** Keep labels short enough for the compact control.

### Light button

**Use:** Primary or discovery action against dark content.

**CSS:** `background: #eae8e5; color: #111111; border: 1px solid transparent; border-radius: 8px; padding: 12px 16px; height: 40px`

**Text style:** `button` — Labil Grotesk Variable 500 · 14px/1

**Observed:** Used beneath the centered product introduction and within the dark resource promo.

**States:** Declared: hover background-color #ffffff; active uses inset shadows; focus-visible not specified.

### Outline button

**Use:** Secondary exploration action.

**CSS:** `background: transparent; color: #111111; border: 1px solid rgba(17,17,17,0.3); border-radius: 8px; padding: 12px 16px; height: 40px`

**Text style:** `button` — Labil Grotesk Variable 500 · 14px/1

**Observed:** Usually aligned with a section heading or below a left-aligned feature title. Dark company-section version uses white text and an 8% white edge.

**States:** Declared: hover background-color #272625, border-color #111111, box-shadow none; focus-visible not specified.

### Navigation link

**Use:** Compact links within the fixed navigation.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 12px 16px; border: 1px solid transparent; border-radius: 8px; height: 42px`

**Text style:** `button` — Labil Grotesk Variable 500 · 14px/1

**Observed:** A 12px down chevron follows dropdown labels. At the top, logo and controls span nearly the full width; scrolling condenses them into a centered rounded floating bar. Its light/dark theme follows the chapter.

**States:** Declared: hover background-color #ffffff and color #111111 on the light variant; focus-visible not specified.

### Email conversion form

**Use:** Hero and closing email conversion.

**CSS:** `background: #ffffff; border: 1px solid rgba(17,17,17,0.08); border-radius: 12px; height: 48px; width: 448px; padding: 0px 16px`

**Observed:** Single field with Primary button inset 4px at right. A narrow trust row below combines rating marks, a divider and analyst endorsement. The dark variant uses charcoal fill and an 8% white edge.

**Transfer:** Preserve the compact combined input/action rather than separating into a tall form.

### Announcement chip

**Use:** Small topical hook above an opening headline.

**CSS:** `background: #ffffff; border: 1px solid #ffffff; border-radius: 12px; padding: 6px 14px 6px 6px; display: flex; gap: 8px; align-items: center; height: 34px`

**Text style:** `announcement` — Labil Grotesk Variable 400 · 12px/1

**Observed:** A small black inset tag leads a short text link and right arrow.

**States:** Declared: hover transform scale(1.02), background-color #ffffff and color #111111; focus-visible not specified.

### Metric tile

**Use:** Colored quantitative proof within the mosaic.

**CSS:** `background: #fff7a8; border: 1px solid rgba(17,17,17,0.04); border-radius: 12px; padding: 16px 20px 20px; width: 205px; height: 210px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `heading-small` — Labil Grotesk Variable 400 · 36px/1.1 · tracking -0.03em

**Observed:** Metric and small muted descriptor sit at the top; black customer logo anchors the bottom. Lemon, pink, mint and violet alternate. Neutral quote tiles span two columns.

**Transfer:** Use a real metric with its unit, concise descriptor and permissioned proof identity.

### Testimonial card

**Use:** Dark customer wall.

**CSS:** `background: #272625; border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 20px; display: flex; flex-direction: column; gap: 28px`

**Text style:** `lead` — Labil Grotesk Variable 400 · 20px/1.3 · tracking -0.02em

**Observed:** Small avatar/name/role row precedes the quote. Variable card heights form three independent columns, with top and bottom fades into the black chapter.

**Transfer:** Keep natural quote lengths and attribution; do not force equal-height rows.

### Footer link

**Use:** Low-emphasis directory navigation.

**CSS:** `color: rgba(255,255,255,0.6); padding: 6px 12px; border-radius: 12px; display: flex; gap: 6px`

**Text style:** `directory` — Labil Grotesk Variable 400 · 14px/1.4

**Observed:** Grouped below uppercase category labels. The product group occupies roughly half the footer, split internally into two columns; three narrower directory groups sit beside it.

**States:** Declared: hover background-color #272625; focus-visible not specified.

### Plan card

**Only for:** pricing pages

**Use:** Tier selection above the comparison matrix.

**CSS:** `background: rgba(39,38,37,0.4); border: 1px solid rgba(255,255,255,0.04); border-radius: 20px; padding: 24px 24px 16px; width: 360px; display: flex; flex-direction: column; justify-content: space-between; gap: 24px; backdrop-filter: blur(50px)`

**Text style:** `body` — Labil Grotesk Variable 400 · 16px/1.3 · tracking -0.01em

**Observed:** Tier name and brief fit statement precede price, included users, grouped feature lists and a full-width action. A luminous compact popular badge marks the middle tier; its panel is darker/more opaque.

### Comparison row

**Only for:** pricing pages

**Use:** Detailed tier comparison.

**CSS:** `background: #ffffff; border-radius: 8px; display: grid; grid-template-columns: 2fr 1fr 1fr 1fr; padding: 0px 20px; height: 54px`

**Text style:** `body` — Labil Grotesk Variable 400 · 16px/1.3 · tracking -0.01em

**Observed:** Alternating white and porcelain rows; first column left aligned, three value columns centered. Colored diamond markers introduce feature groups; plan selectors remain in the comparison header.

## Imagery and graphics

### Liquid light and human sketch

**Use:** Signature opening illustration and smaller decorative emphasis across a landing page.

**Observed:** A loose black pencil figure on a rocket appears to the right of the centered promise. Its soft trail expands leftward behind the lower demo: hot orange, cream and lavender with very blurred boundaries, leaving the upper text field warm white. Other areas use tiny hearts, freehand arrows and emphasis rays.

**Transfer:** Create an original human/tool metaphor tied to the new product. Minimum version: a clean irregular black SVG drawing of a person interacting with a tool, backed by a broad blurred colored trail rather than stock 3D art.

**Build:** Behind the demo place a wide SVG ribbon with a curved path rising toward the right-hand illustration. Layer a broad lavender stroke, narrower cream stroke and localized orange lobe on the far left; blur edges 30–60px and fade into the canvas. Draw the foreground figure with uneven 1–2px black paths, sparse pencil hatching and no filled face. Keep the headline region clear.

### Layered interface demonstration

**Use:** Main object in the opening and feature chapters.

**Observed:** A large crisp white software window occupies most of the content width; the opening has a black play control and translucent 12px-thick outer frame with 16px corners. Dark product theater adds a few slightly tilted small notification cards overlapping the lower sides of a 1062px-wide UI.

**Transfer:** Show one meaningful workflow at useful reading scale. If there is no filmed demo, compose a realistic static interface with a selected item, contextual details and one or two external signals; avoid a collage of tiny full dashboards.

### Cool capability atmosphere

**Use:** Soft backing behind the capability deck.

**Observed:** Lavender and cyan light gathers near the bottom sides of the layered white panels, while the heading remains on the warm canvas.

**Transfer:** Use cool atmospheric color to distinguish the capability scene without making it a flat turquoise section.

**Build:** Place two radial-gradient ellipses behind the deck, cyan centered low and lavender at the lower side edges. Use broad transparent falloff and 40–80px blur; mask the top half to transparent. Keep white panels opaque and crisp.

### Glowing closing word

**Use:** Signature emphasis within the heavy closing statement.

**Observed:** One word uses a radial orange–cream–lavender gradient clipped to heavy uppercase letters, with a softly blurred duplicate behind it. White words surround the glow on black.

**Transfer:** Choose one short benefit word in the closing statement, not the whole paragraph.

**Build:** Use background-clip:text with radial-gradient(80.17% 109.2% at 61.6% 33.8%, #d0b2ff 0%, #ffeed8 37.5%, #e8400d 95.5%). Duplicate the text in an absolutely positioned pseudo-element behind it with filter:blur(6px) and opacity:0.75; retain a crisp front layer.

### Editorial thumbnails

**Use:** Resource grids and dark inset article promo.

**Observed:** Four previews use roughly 2:1 images with 8px corners, small category/date metadata and compact article titles. Artwork ranges from bold typographic covers to UI fragments; the inset resource promo pairs a video still with text and an action.

**Transfer:** Keep a consistent frame while allowing cover-specific colors. Do not turn each preview into a padded shadow card.

### Human photography and directory

**Only for:** company and culture pages

**Use:** Leadership introduction and team breadth.

**Observed:** Three waist-up portraits in black shirts against soft gray walls use 317px × 401px rounded frames. Names and roles sit immediately below. The wider team appears as six columns of tiny rounded portraits with names rather than large staff cards; award links form a separate stacked column.

**Transfer:** Use consistent honest portraits and a compact people directory. Retain the restrained lighting and low-saturation environment.

### Icons

**Observed:** Navigation uses 12px chevrons, footer destinations use compact 16px monochrome glyphs, and benefit lists use black circular checks. Capability categories use small colored rounded diamonds. Hand-drawn decorative marks are looser than utility icons.

**Transfer:** Use simple filled or fine-outline monochrome utility icons at 12–20px, reserving colored diamonds for category coding. Keep doodles separate from controls.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** Warm canvas, full-width top navigation, then a small Announcement chip around 168px into the page. The 56px regular headline is centered in a 472px block and spans two lines, with selective slanted letters. A 400px-wide two-line support paragraph follows, then the 448px Email conversion form and its trust strip. The main white interface enters around the lower third of the 900px first screen and continues below the fold. Behind it, orange–cream–lavender light flows across the lower viewport; a black pencil character with a tool sits to the right of the promise. The first screen contains the entire promise, support, form and trust row, plus the upper portion of the demo and its play action; the demo bottom and proof grid follow below.

**Transfer:** Keep this centered light composition as the default for a marketing landing page. Substitute an original human/tool sketch and one clear working-product panel when no hero media exists. A focused feature page opens as a two-column promise/form and UI scene; a company page centers its promise amid floating pastel proof tiles; pricing uses a dark centered introduction over three Plan cards.

**Avoid:** Do not replace the opening with a full-bleed dark gradient, a giant all-caps headline or a generic equal-width text-and-photo split.

**Text style:** `display` — Labil Grotesk Variable 400 · 56px/1 · tracking -0.05em

### Chapter heading and product theater

**Observed:** A centered 44px heading, brief 16px support line and Light button lead into a large interface on Dark chapter. The heading cluster stays near 512px wide; 28px separates action grouping and 56px separates it from the main demonstration.

**Transfer:** Introduce a major product promise with one workflow object, not a feature inventory.

**Text style:** `heading` — Labil Grotesk Variable 400 · 44px/1.1 · tracking -0.04em

### Layered capability deck

**Observed:** Centered heading and support sit above Paper deck on Cool capability atmosphere. Several receding header strips expose small diamond markers. The active panel holds a narrow left title/body column and a much larger interface clipped at the right edge; a hand-drawn arrow points toward the clickable headers.

**Transfer:** Use a small set of related capability chapters; each panel should pair an outcome with a product view.

**Text style:** `heading` — Labil Grotesk Variable 400 · 44px/1.1 · tracking -0.04em

### Logo migration grid and solo quote

**Observed:** A centered trust line introduces four columns by two rows of monochrome logos with small migration captions. A generous gap leads to a left-aligned 36px quote in a 656px centered column, followed by a fine hand-like divider and avatar/role/logo attribution. The same composition inverts on dark pricing sections.

**Transfer:** Use permissioned identities and short context captions; connect the grid to one substantial user story.

**Text style:** `quote` — Labil Grotesk Variable 400 · 36px/1.2 · tracking -0.03em

### Audience selector

**Observed:** Five narrow illustrated tabs sit above a 16px-cornered light panel. The selected tab has dark text, black drawing and a small color glow; inactive tabs become pale. Below, a left title/action column sits beside two benefit descriptions divided by hairlines.

**Transfer:** Organize by relevant audience or use case; retain one active story rather than five simultaneous feature columns.

**Text style:** `heading-small` — Labil Grotesk Variable 400 · 36px/1.1 · tracking -0.03em

### Pastel proof mosaic

**Observed:** An 880px four-column grid with 20px gutters alternates Metric tiles and double-width neutral quotes over three staggered rows. A loose pencil arrow introduces the proof; logos anchor card bottoms.

**Transfer:** Mix quantitative and qualitative proof at equal visual importance. Change row arrangement to fit the available evidence.

**Text style:** `heading-small` — Labil Grotesk Variable 400 · 36px/1.1 · tracking -0.03em

### Dark customer wall

**Observed:** Dark chapter with a centered 44px heading and small pencil hearts. Three columns of Testimonial cards sit in a vertically clipped field with black fades at top and bottom; card lengths vary.

**Transfer:** Present a convincing volume of real customer voices without equalizing every quote.

**Text style:** `heading` — Labil Grotesk Variable 400 · 44px/1.1 · tracking -0.04em

### Feature explanation and FAQ

**Observed:** Focused feature pages alternate two-column benefit text and floating interface/email scenes, then a four-card capability row. FAQ uses a left 44px section title with a tiny uppercase lead-in and a right 540px stack of 24px questions, hairline dividers and small circular plus controls.

**Transfer:** Use alternating explanations for mechanisms and the split FAQ for objections; keep long answers subordinate to the question hierarchy.

**Text style:** `card-heading` — Labil Grotesk Variable 400 · 24px/1.1 · tracking -0.02em

### Glowing closing and directory

**Observed:** On Dark chapter, a centered two-line Closing-display statement fits within 608px. One word glows; the Email conversion form follows after 36px. Around 100px vertical padding isolates the call. Below, a full-width hairline separates the logo/assistant-link row from the directory: product links take the left half, three compact navigation groups the right. Another hairline precedes a quiet copyright and legal row. Pricing retains the same close but omits the extra analyst trust strip.

**Transfer:** Use one bold final benefit and one action, then a genuinely useful grouped directory. The glowing close is retained regardless of the preceding page type.

**Text style:** `closing-display` — Labil Grotesk Variable 900 · 56px/0.8 · tracking -0.03em · uppercase

### Company editorial chapters

**Only for:** company and culture pages

**Observed:** A centered opening promise floats among pastel metric tiles at different sizes and blur depths. Subsequent broad heading pairs combine a dark opening sentence with a muted continuation; portraits and compact people listings follow. A narrow 432px manifesto column uses 28px text, widely separated paragraphs and occasional hand-drawn underlines. The lower dark section has three values or onward-link columns.

**Transfer:** Use this human/editorial variant for origin, philosophy and people, not as the ordinary product opening.

**Text style:** `heading` — Labil Grotesk Variable 400 · 44px/1.1 · tracking -0.04em

### Pricing selection and matrix

**Only for:** pricing pages

**Observed:** Near-black opening with a centered 56px promise, small uppercase label and trial note. Three 360px Plan cards use 12px gutters. A dark logo grid and solo quote precede a porcelain comparison section with a sticky plan-selection header and alternating Comparison rows; proof mosaic and customer wall follow.

**Transfer:** Keep financial choice calm and neutral. Emphasize one recommended tier with opacity and a small glowing badge rather than a colored oversized card.

**Text style:** `display` — Labil Grotesk Variable 400 · 56px/1 · tracking -0.05em

## Page flow

**Storyline:** Promise → working product → credibility → capability or company story → concrete proof → objection handling or resources → glowing final action and directory.

### Broad platform marketing landing page

1. **Promise** — Centered light product-stage opening with inline conversion.
2. **Social proof** — Monochrome logo/migration grid and standalone quote.
3. **Product demonstration** — Dark theater, signal cards and a layered light capability deck.
4. **Audience relevance** — Illustrated audience selector and inset oversized conversion interlude.
5. **Quantified proof** — Pastel metric-and-quote mosaic.
6. **Education and reassurance** — Article row followed by the dark customer wall.
7. **Closing call** — Glowing uppercase benefit, inline email form and deep directory.

**Transfer:** Balance strong working-product scenes with human proof; the chapters can be rearranged without losing the light-to-dark cadence.

### Company story and culture page

1. **Purpose** — Centered promise amid floating pastel proof tiles.
2. **Human credibility** — Leadership portraits, award column and compact team directory.
3. **Point of view** — Narrow manifesto text, media scene and four-stat row.
4. **Differentiation** — Three-column dark principles section and standalone quote.
5. **Social proof** — Dark customer wall.
6. **Onward paths** — Three icon-led links to engagement opportunities.
7. **Closing call** — Shared glowing close and directory.

**Transfer:** Use real people and a clear point of view in place of product inventory.

### Focused feature acquisition page

1. **Promise** — Left category label, large benefit, checked outcomes and form; floating UI at right.
2. **Social proof** — Customer quote carousel.
3. **Mechanism** — Alternating explanation and interface scenes.
4. **Capability summary** — Four light cards with colored diamonds.
5. **Education** — Dark inset article promo and broad customer trust call.
6. **Objection handling** — Split FAQ and four resource previews.
7. **Closing call** — Shared glowing close and directory.

**Transfer:** Lead with a focused outcome, demonstrate how it works, and answer objections without adopting the full platform-page length.

### Plan selection and purchase evaluation

1. **Pricing** — Dark centered introduction and three translucent plan cards.
2. **Value reassurance** — Migration logos and cost-consolidation testimonial.
3. **Detailed comparison** — Light feature matrix with grouped rows and persistent tier actions.
4. **Quantified proof** — Pastel mosaic followed by dark customer wall.
5. **Closing call** — Glowing conversion statement and full directory.

**Transfer:** Separate fast tier selection from detailed comparison and reinforce value through customer proof.

## Writing

Warm, direct and commercially confident. The language makes software feel like a helpful teammate, mixing clear outcomes with a restrained streak of superhero-like optimism.

**Do not copy:** Do not reuse Amplemarket names, product names, logos, characters, analyst awards, customer identities, quotations, metrics or performance claims. Replace them with original language and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you or your team. Use we for company purpose and the product name for specific capabilities.
- **Rhythm:** Headlines are short benefit-led phrases, often balanced across two lines. Support usually takes one sentence; cards favor a compact title plus one paragraph. Small doses of playful language sit beside concrete operational details.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A confident future-facing promise or direct outcome for the reader. | 6–12 words | “Step into the future of sales: Human + AI”<br>“Follow your top prospects to new opportunities” |
| Supporting line | Link a small set of useful actions to a larger business outcome. | 12–24 words | “Empower reps, uncover opportunities, and grow revenue with an all-in-one AI platform.” |
| Capability title | Plain benefit, frequently a compact contrast or paired phrase. | 4–8 words | “Better data, more wins”<br>“Hit every inbox, every time” |
| Primary action | Verb plus a concrete next step; trial, exploration or reading. | 2–4 words | “Get free trial”<br>“Read blog post” |
| Proof heading | Human reassurance with conversational repetition. | 5–7 words | “Real results from real customers”<br>“Some love from our customers!” |
| Closing call | Imperative that upgrades the reader's ability, expressed as an energetic final benefit. | 5–8 words | “Unlock your AI sales superpowers” |

**Words and phrasing to use:** smarter and faster; all-in-one; your team; real results; save time; unlock; level up; opportunities

**Avoid:** synergistic ecosystem; revolutionary paradigm; enterprise-grade excellence; unmatched best-in-class; abstract transformation without an outcome

**Rules:**

- Name the task or outcome before explaining the technology.
- Use concrete mechanisms and verified quantities to support energetic benefits.
- Allow a playful metaphor in a headline, but keep supporting text practical.
- Use questions in FAQ labels and direct verbs in actions; avoid clever navigation labels.

## Do's and Don'ts

### Do

- Set ordinary opening headlines at 56px/1, weight 400, with -0.05em tracking.
- Keep large chapter headings at 44px/1.1 and let line breaks supply emphasis.
- Preserve 56px desktop gutters and centered 1104px or 1328px content stages.
- Use 40px controls with 8px corners and 48px fields with 12px corners.
- Reserve 20px gutters for the proof mosaic and article grid; use 12px between plan cards.
- Anchor pastel metric cards with a small descriptor above a bottom-aligned identity.
- Pair crisp white interface layers with blurred color, not blurred interfaces.
- End with the weight-900, 0.8-line-height glowing statement on near-black.

### Don't

- Do not make every headline heavy; weight 900 belongs to conversion statements.
- Do not use pill radii for the main actions or email field.
- Do not turn the brand orange into a site-wide button color.
- Do not replace #f6f5f3 and #fbfaf9 with cold blue-gray page backgrounds.
- Do not add drop shadows to every quote and metric tile; these use fine borders.
- Do not enlarge compact directory text to the 20px lead scale.
- Do not fill all proof tiles with a single accent; retain the lemon, pink, mint and violet mix.
- Do not center standalone quote text merely because its 656px column is centered.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions include 0.2s and all 0.5s cubic-bezier(0.23,1,0.32,1).
- Announcement chips declare a scale(1.02) hover with 0.25s cubic-bezier(0.215,0.61,0.355,1).
- Fields declare border-color 0.2s cubic-bezier(0.215,0.61,0.355,1). Testimonial cards declare 0.25s cubic-bezier(0.23,1,0.32,1).
- Navigation visibly changes from broad top alignment to a compact floating bar; the quote wall uses vertically offset columns and edge fades.

**Transfer:**

- Use restrained control feedback while reserving atmospheric movement for the light field and layered scenes.
- Keep text and form controls stable even when decorative artwork shifts.

**Unknown:**

- Exact timing of navigation contraction, light-field motion and testimonial-column loops is not established.

### Responsive

**Observed:**

- CSS includes breakpoint families around 479/480px, 767/768px, 991/992px and 1049/1050px.
- Some desktop atmospheric backdrops and testimonial columns are designated for hiding on narrower layouts.

**Transfer:**

- On narrow layouts, retain the promise, combined action and one main interface before secondary decorations; move the side sketch away from text.
- Stack feature splits and reduce proof-grid columns while preserving the metric-versus-quote width relationship where space allows.
- Keep the closing gradient word and tight uppercase rhythm readable rather than retaining desktop line breaks.

**Unknown:**

- Mobile type sizes, exact navigation behavior and complete small-screen compositions are not established. These are adaptation recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
