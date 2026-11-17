# Shopify — ambition in motion

## Overview

An expansive, human-centered technology style that makes sophisticated infrastructure feel like personal possibility. Thin grotesk headlines and compact pill actions sit against near-black green, with deep blue and violet chapters and sharp mint markings. Candid people, tactile product photography, luminous network graphics and floating interface fragments alternate between cinematic spectacle and clear explanation. It suits broad platforms and ambitious product launches; focused product and pricing variants bring brighter canvases and denser practical detail.

### Essentials

- Possibility is written in unusually light, tightly packed type: the opening uses 96px/1.08 at weight 300 with -0.02em tracking; ordinary chapter headlines use 56px/1.08 at weight 330 with -0.03em tracking.
- The opening is a lived moment, not a software billboard: full-bleed human footage backs a left-aligned two-line promise, 24px support and a 56px white pill; the dark next chapter rolls over the lower edge with 48px top corners. Use an authentic working photograph when footage is unavailable.
- Actions are solid little islands in expansive scenes: white-on-dark primary pills and transparent 2px outline secondary pills, 9999px radius, 12px 24px padding and 18px/28px weight 550 labels; navigation uses the compact 44px version.
- Color lives in near-black chapters rather than rainbow cards: #02090a is the default canvas, #041e18 backs proof, and #000a1e backs technical scenes. Bright mint #36f4a4 marks numbers, rules and small labels; a bounded violet chapter provides the saturated interruption.
- Demonstrations float above atmospheric fields: light interface fragments, offset product cards and photos occupy much more space than their captions inside 12px–16px dark stages. Include a luminous network or orbit device with small mono factoids; a dotted SVG network with curved light trails is the minimum equivalent.
- The closing invitation becomes a practical scene: a centered 64px heading introduces offset portrait images beside 44px ruled action steps, mint 24px two-digit markers and one white pill. This substantial closing device can move within the story, but must remain more than a generic centered button.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep navy | `#000a1e` | `--color-navy` | background | Technical and ecosystem chapters. |
| Deep pine | `#041e18` | `--color-pine` | background | Extended quantified-proof chapters. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal mint | `#36f4a4` | `--color-mint` | text, accent, border | Proof labels, numbered steps and thin vertical rules, not primary button fills. |
| Iridescent purple | `#865cff` | `--color-gradient-purple` | accent | Second end of interactive statement text gradients. |
| Chapter violet | `#2c007f` | `--color-violet` | background | One bounded high-energy capability chapter, fading into midnight. |
| Iridescent mint | `#5fd5b6` | `--color-gradient-mint` | accent | First end of interactive statement text gradients. |
| Forest glow | `#0d3a2d` | `--color-panel-glow` | accent | Restrained green end of demonstration-stage gradients. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, action, background | Dark-theme primary type and filled actions; light product canvases. |
| Raised pine edge | `#133b32` | `--color-quote-edge` | border | Thin outlines around raised pine quotes. |
| Network green edge | `#11352d` | `--color-factoid-edge` | border | Network factoid outlines and 0.5px stat rules. |
| Raised pine | `#072720` | `--color-quote` | surface | Overlapping testimonial cards. |
| Gradient midnight | `#000a1d` | `--color-midnight` | background | Lower end of the violet chapter. |
| Pine gray | `#99b3ad` | `--color-body-pine` | text, link | Supporting copy and linked explanations in green proof chapters. |
| Black | `#000000` | `--color-black` | text, background, action | Footer and cinematic backing; inverse text and light-theme primary actions. |
| Coal green | `#02090a` | `--color-canvas` | background | Default dark marketing canvas. |
| Dark teal stage | `#061a1c` | `--color-panel` | surface | Inset demonstration stages. |
| Footer edge | `#121c1e` | `--color-footer-edge` | border | Footer utility-row separator. |
| Inactive statement gray | `#71717a` | `--color-inactive` | text | Unselected phrases in the large interactive statement. |
| Cool body gray | `#9797a2` | `--color-body-muted` | text | Default secondary paragraphs and image captions on dark. |
| Footer gray | `#a1a1aa` | `--color-footer-muted` | text | Footer links and active gray button fills. |
| Teal gray | `#9dabad` | `--color-body-teal` | text, link | Supporting copy inside dark teal stages. |
| Lavender gray | `#bdbdca` | `--color-body-bright` | text | Larger supporting paragraphs in navy chapters. |
| Light-theme rule | `#d4d4d8` | `--color-light-rule` | border, action | Feature top rules; also the shared white-button hover fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan green | `#95bf47` | `--color-plan-accent` | text, accent | Plan audience captions, toggle and comparison checks. |
| physical-product pages | Lime wash | `#eefab3` | `--color-lime` | background, surface | Promotional band and small photo-hotspot labels. |
| physical-product pages | Warm closing brown | `#35231b` | `--color-brown` | background | Warm final conversion band. |
| physical-product pages | Resource charcoal | `#18181b` | `--color-charcoal` | background | Resource-card and question chapters. |
| pricing pages | Cool charcoal green | `#141a1a` | `--color-pricing-card` | surface, background | Plan cards and supporting benefits bands. |
| light product pages | Light-theme secondary ink | `#52525b` | `--color-light-text` | text | Secondary links and text on white. |
| focused software product pages | Warm pale gray | `#f2f2f0` | `--color-pale-panel` | surface | Large light interface demonstrations. |
| physical-product pages | Warm paper | `#f3f3ec` | `--color-paper` | background | Light feature-summary and demonstration bands. |
| pricing pages | Soft gray stage | `#f5f5f5` | `--color-light-stage` | surface | Interface-art backing in benefits cards. |

## Typography

- **Shopify-Inter** — All marketing headlines, body, navigation and actions. Neutral grotesk with a tall x-height and notably light display cuts. If unavailable, use **Inter**. Use variable weights 300, 330, 360, 420, 450 and 550; preserve tight display tracking. Font stack: "Shopify-Inter", "Inter", Helvetica, Arial, sans-serif.
- **ui-monospace** — Network factoids and numerical-proof micro-labels. Small uppercase system monospace, utilitarian against the theatrical scenes. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Shopify-Inter | 300 | 96px | 1.08 | -0.02em | Two-line cinematic opening promise. |
| statistic | Shopify-Inter | 300 | 96px | 0.96 | normal | Large proof numerals aligned beside smaller suffixes. |
| heading-major | Shopify-Inter | 330 | 64px | 1.08 | -0.02em | Major transitions and centered closing headings; focused-product hero headlines. |
| statistic-suffix | Shopify-Inter | 330 | 64px | 1 | normal | Top-aligned percent or plus suffix next to statistic numerals. |
| heading | Shopify-Inter | 330 | 56px | 1.08 | -0.03em | Default capability chapter headline. |
| statement | Shopify-Inter | 330 | 56px | 1 | -0.02em | Interactive phrase-based statement immediately after the cinematic introduction. |
| heading-small | Shopify-Inter | 330 | 44px | 1.1 | -0.01em | Proof headings and large ruled closing steps. |
| quote | Shopify-Inter | 330 | 34px | 1.14 | -0.02em | Raised testimonial quote overlapping a human photograph. |
| hero-support | Shopify-Inter | 400 | 24px | 1.3 | -0.02em | Compact opening support, about two lines. |
| number-marker | Shopify-Inter | 400 | 24px | 1.3 | -0.01em | Two-digit step markers; pricing category headings. |
| body-large | Shopify-Inter | 400 | 20px | 1.4 | normal | Support for wide navy scenes and focused product openings. |
| card-title | Shopify-Inter | 450 | 20px | 1.3 | normal | Short image-caption headings. |
| body | Shopify-Inter | 400 | 18px | 1.4 | normal | Default marketing paragraphs and proof-card descriptions. |
| button | Shopify-Inter | 550 | 18px | 28px | normal | 56px primary and secondary pills. |
| utility | Shopify-Inter | 400 | 16px | 1.5 | normal | Footer links and compact supporting copy. |
| navigation | Shopify-Inter | 420 | 16px | 1.5 | normal | Desktop navigation items. |
| factoid | ui-monospace | 400 | 12px | 1.5 | 0.02em, uppercase | Floating network factoid titles in white and descriptions in mint. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-statistic | Shopify-Inter | 300 | 96px | 1.08 | -0.025em | Large totals or durations in paired black proof cards. |
| focused product and pricing pages | product-heading | Shopify-Inter | 330 | 56px | 1.08 | -0.01em | Product explanation and compact final conversion headings. |
| focused product pages | product-card-title | Shopify-Inter | 360 | 28px | 1.2 | -0.01em | Feature cards, demonstration selectors and large question labels. |
| focused product pages | eyebrow | Shopify-Inter | 550 | 16px | 1 | -0.01em, uppercase | Product-category labels above headline groups. |
| pricing pages | comparison-value | Shopify-Inter | 450 | 16px | 1.4 | normal | Values in the detailed comparison table. |

**Notes:**

- Use light weight, size and tight spacing—not boldness—to establish the headline hierarchy. Display tracking is -0.02em; the default 56px chapter tightens to -0.03em.
- Product explanations relax the same 56px size to -0.01em tracking; keep this as a scoped recipe rather than averaging it into the default.
- Navigation actions use a compact 16px/24px weight 550 label in 44px pills. Body paragraphs remain normal tracking; inline links retain the paragraph recipe.
- Keep statistic suffixes top-aligned and visibly smaller than the 96px numeral. White factoid headings and mint descriptions share one mono recipe.

## Layout

**Density:** Airy cinematic chapters with compact controls and tightly grouped captions; practical tables are deliberately denser.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card heading-to-description gap. |
| 16px | Paired actions, inset text stacks and compact card gutters. |
| 24px | Default grid gutter, standard card padding and headline-to-support gap in wider scenes. |
| 32px | Opening copy-to-action gap and photograph-to-caption separation. |
| 40px | Heading-group bottom space, inset feature padding and question-row separation. |
| 64px | Standard chapter vertical padding and heading-to-media separation. |
| 80px | Footer padding and selected major transition top padding. |
| 128px | Proof chapter breathing room, product chapter padding and substantial chapter endings. |

### Containers and grids

- **desktop content**: max width 1260px · side padding 90px. Centered content at a 1440px viewport. Full-width backgrounds and cinematic media escape this alignment; type and cards return to it.
- **chapter grid**: 12 columns · gap 24px. Two roughly equal six-column regions for copy and demonstration; align nested compositions to the same outer edges.
- **story cards**: 3 columns · gap 16px. Three approximately 409px image-led customer stories with no enclosing card fill.
- **reading width**: max width 768px. Contained heading or explanation groups; the cinematic opening support is much narrower at 420px.
- **product feature grid** (only for focused product pages): 3 columns · gap 24px. Three 404px columns, sometimes two rows, with rules instead of boxes.
- **software benefit grid** (only for focused software product pages): 2 columns · gap 24px. Four 618px-wide media demonstrations in a two-by-two explanation grid.
- **plan grid** (only for pricing pages): 4 columns · gap 16px. Equal 316px minimum-width plan cards in a horizontally scrollable track.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 9999px (pill) |
|  | chapter top corners | 48px |
|  | feature stages | 16px |
|  | media cards | 12px |
|  | quote and factoid cards | 8px |
| pricing and focused software product pages | plan and light demo cards | 24px |
| physical-product pages | promotion band top corners | 32px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| demo lift | `0px 8px 8px rgba(0,0,0,0.1), 0px 4px 4px rgba(0,0,0,0.1), 0px 2px 2px rgba(0,0,0,0.1)` | Subtle lift for dark demonstration stages; not a general elevation system. |

### Surfaces

#### Coal canvas · level 0

**Use:** Default marketing page background.

**CSS:** `background: #02090a; color: #ffffff`

#### Pine chapter · level 0

**Use:** Quantified proof and reassurance chapter.

**CSS:** `background: #041e18; border-radius: 48px 48px 0px 0px`

**Observed:** A broad rounded top bridges out of the navy chapter; subsequent proof blocks continue on green without repeated rounded corners.

**Transfer:** Make one continuous proof environment rather than independent green cards.

#### Inset teal stage · level 1

**Use:** Large split text and media capability panels.

**CSS:** `background: linear-gradient(290.7deg, #061a1c 58.79%, #0d3a2d 100%); border-radius: 16px; overflow: hidden`

**Observed:** Text is grounded low in one half while a floating demonstration fills the other; cool gray supporting text softens the contrast.

**Transfer:** Give the main workflow a single expansive stage with a very low-contrast directional glow.

#### Violet chapter · level 0

**Use:** A major high-energy capability interruption.

**CSS:** `background: linear-gradient(in oklab, #2c007f 42.49%, #000a1d 100%); border-radius: 48px 48px 0px 0px; padding: 100px 0px`

**Observed:** Dark demonstration cards sit against saturated violet that resolves into navy below.

**Transfer:** Reserve this treatment for one strong product leap, not every benefit.

#### Navy atmosphere · level 0

**Use:** Technical and ecosystem scenes.

**CSS:** `background: #000a1e`

**Observed:** Broad blue radial glows support overlapping dark browser and terminal silhouettes.

**Transfer:** Keep blue in the light field rather than coloring the body text.

#### Closing charcoal mist · level 0

**Use:** Atmospheric backing for the practical closing scene.

**CSS:** `background: radial-gradient(at 65% 36%, rgba(63,63,75,0.5) 0px, rgba(0,0,0,0) 50%), radial-gradient(at 38% 61%, rgba(63,63,75,0.5) 0px, rgba(0,0,0,0) 50%), linear-gradient(rgba(9,9,10,1), rgba(9,9,10,1)); border-radius: 48px 48px 0px 0px; padding: 80px 0px 128px`

**Observed:** Soft charcoal light pools sit behind the photos and steps, with darkened edges.

**Transfer:** Match the soft glow; exact stops are not essential.

#### Light product chapter · level 0

**Only for:** focused software product pages

**Use:** Clear product explanation after a dark opening.

**CSS:** `background: #ffffff; color: #000000; border-radius: 48px 48px 0px 0px; padding: 128px 0px`

#### Pale demo panel · level 1

**Only for:** focused software product pages

**Use:** Large annotated interface stage.

**CSS:** `background: #f2f2f0; border-radius: 24px; overflow: hidden`

**Observed:** A text selector occupies the left; an enlarged application window is clipped by the bottom and right edges.

**Transfer:** Enlarge the useful workflow instead of shrinking a full application to fit.

#### Warm feature band · level 0

**Only for:** physical-product pages

**Use:** Text-led feature summaries.

**CSS:** `background: #f3f3ec; color: #000000; padding: 64px 0px`

#### Lime promotion · level 0

**Only for:** physical-product pages

**Use:** A discrete switch or purchase offer.

**CSS:** `background: #eefab3; color: #000000; border-radius: 32px 32px 0px 0px; padding: 64px 0px`

#### Warm final call · level 0

**Only for:** physical-product pages

**Use:** Final conversion band after dark questions.

**CSS:** `background: #35231b; color: #ffffff; padding: 128px 0px`

## Components

### Sticky navigation

**Use:** Persistent global orientation and compact conversion.

**CSS:** `position: sticky; top: 0px; height: 72px; padding: 0px 90px; display: flex; align-items: center; gap: 32px; z-index: 50`

**Text style:** `navigation` — Shopify-Inter 420 · 16px/1.5

**Observed:** Brand mark at left, short menu cluster with 16px chevrons, login and compact white action pushed right. It overlays the opening film and becomes a solid dark strip over later content. Light product pages invert it and add a local product navigation row.

**Transfer:** Keep navigation shallow and let the opening media extend behind it.

### Primary button

**Use:** Main conversion in a dark scene.

**CSS:** `background: #ffffff; color: #000000; border: 2px solid transparent; border-radius: 9999px; padding: 12px 24px; height: 56px; box-sizing: border-box; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — Shopify-Inter 550 · 18px/28px

**Observed:** Text-only pill with no permanent arrow; a 44px compact version serves the header. Light product pages use black fill and white text.

**States:** Declared: hover background #d4d4d8, color #000000 and transparent border; focus-visible 2px solid #751be9 outline with 2px offset; active background #a1a1aa and black text.

### Secondary button

**Use:** Sales conversations, exploration or a second route beside conversion.

**CSS:** `background: transparent; color: #ffffff; border: 2px solid #ffffff; border-radius: 9999px; padding: 12px 24px; height: 56px; box-sizing: border-box; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — Shopify-Inter 550 · 18px/28px

**Observed:** Matches the primary pill's shape and visual height. On white, text and border invert to black. Pricing plan actions use a 44px compact outline version.

**States:** Declared: hover border #d4d4d8 with transparent fill and white text; focus-visible 2px solid #751be9 outline with 2px offset; active border #a1a1aa.

### Inset feature panel

**Use:** One workflow dramatized at chapter scale.

**CSS:** `background: linear-gradient(290.7deg, #061a1c 58.79%, #0d3a2d 100%); border-radius: 16px; display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); overflow: hidden`

**Text style:** `heading` — Shopify-Inter 330 · 56px/1.08 · tracking -0.03em

**Observed:** Small partner badges can cluster above the left-hand copy; the title and short support are pinned toward the lower left with 40px inset. A floating live-product scene occupies the right without a heavy device frame.

**Transfer:** Choose one legible interaction rather than a collage of unrelated feature icons.

### Overlapping quote card

**Use:** Human proof alongside reassurance or business support.

**CSS:** `background: #072720; border: 1px solid #133b32; border-radius: 8px; padding: 36px`

**Text style:** `quote` — Shopify-Inter 330 · 34px/1.14 · tracking -0.02em

**Observed:** A generous quote card overlaps the bottom-right of a taller portrait. Hanging opening quotation mark, quote text, then separated author and organization lines.

**Transfer:** Pair one credible first-person outcome with a real person at work.

### Network factoid

**Use:** Small readable facts anchored to a luminous infrastructure scene.

**CSS:** `background: rgba(16,16,16,0.7); border: 1px solid #11352d; border-radius: 8px; padding: 16px 12px; display: grid; grid-template-columns: 20px 1fr; gap: 13px`

**Text style:** `factoid` — ui-monospace 400 · 12px/1.5 · tracking 0.02em · uppercase

**Observed:** A small outline symbol sits beside uppercase white title and mint explanatory text. Cards float near the network rather than forming a dashboard.

**Transfer:** Use short factual measures relevant to the new product; keep labels secondary to the light trails.

### Footer columns

**Use:** Substantial site ending after the final conversion scene.

**CSS:** `background: #000000; padding: 80px 90px; display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); column-gap: 24px; row-gap: 56px`

**Text style:** `utility` — Shopify-Inter 400 · 16px/1.5

**Observed:** First column holds a standalone brand symbol and back-to-top link; four remaining columns carry 20px medium headings and muted links with 16px list gaps. A full-width utility row has a 1px #121c1e top edge and 40px top padding, locale and legal links on the left, social circles on the right. The light product variant uses white, black headings, gray links and a pale rule.

**States:** Declared: hover footer links become white.

### Mint rule proof

**Use:** Short explanatory evidence below metrics or alongside reassurance.

**CSS:** `border-left: 2px solid #36f4a4; padding-left: 18px; color: #99b3ad`

**Text style:** `body` — Shopify-Inter 400 · 18px/1.4

**Observed:** An understated vertical mint line carries the proof accent. Inline product references stay underlined and use the surrounding muted color.

**Transfer:** Reserve the line for a result or reason, not every paragraph.

### Inline text link

**Use:** Specific next steps embedded within explanatory copy.

**CSS:** `color: #9dabad; text-decoration-line: underline`

**Text style:** `body` — Shopify-Inter 400 · 18px/1.4

**Observed:** The link inherits its paragraph size rather than becoming a separate callout; colors follow the teal, pine or navy text context.

**States:** Declared: hover underline is removed and color becomes #d4d4d8; active color #a1a1aa.

### Plan card

**Only for:** pricing pages

**Use:** Comparable plans with equal action prominence.

**CSS:** `background: #141a1a; border-radius: 24px; padding: 24px 24px 32px; min-width: 316px; display: flex; flex-direction: column`

**Text style:** `card-title` — Shopify-Inter 450 · 20px/1.3

**Observed:** Plan name at upper left, compact monthly price at upper right, green audience line beneath. A full-width compact outline action precedes the feature list. Fine translucent separators divide features; the default dark set does not crown a single plan with a large badge.

**Transfer:** Keep plan differences in the content, not competing colors.

### Question row

**Only for:** product and pricing pages

**Use:** Full-width objection handling near the end.

**CSS:** `border-bottom: 1px solid rgba(255,255,255,0.2); padding-bottom: 40px; display: grid`

**Text style:** `number-marker` — Shopify-Inter 400 · 24px/1.3 · tracking -0.01em

**Observed:** Native disclosure with a left-aligned question and 44px white circular plus control at right. Rows are separated by 40px gaps. Physical-product questions enlarge to the 28px product-card-title recipe and use 30% white rules.

**Transfer:** Use concise questions; expanded answers retain 18px body type.

### Email conversion pill

**Only for:** pricing pages

**Use:** Low-friction signup at the end of a long decision page.

**CSS:** `border-radius: 9999px; box-shadow: inset 0px 0px 0px 2px #ffffff; width: 512px; height: 56px; display: flex; justify-content: space-between`

**Text style:** `utility` — Shopify-Inter 400 · 16px/1.5

**Observed:** Single email field and inset white submit pill share one outline. A short consent line sits beneath, while a compact sequence of trial benefits appears above.

**Transfer:** Keep the entry point to one field; separate commercial detail from the control.

## Imagery and graphics

### Human opening film

**Use:** The default first impression.

**Observed:** Edge-to-edge candid footage of people working, selling or celebrating, framed as a lived moment rather than a pristine studio ad. Warm interiors and natural motion carry the color; a dark overlay keeps white copy readable. The scene occupies almost the entire first screen.

**Transfer:** Film a person experiencing the product's benefit in a real setting. Minimum equivalent: one full-bleed editorial photograph with a useful darkened copy area, not a stock handshake.

### Floating product choreography

**Use:** Capability demonstrations inside dark stages.

**Observed:** Light product cards and application fragments hover at differing depths. A central bright card overlaps faded duplicates; small transaction pills, flags or selected states explain the motion. Dark teal backs the scene with localized green illumination; captions remain outside the main interaction or grounded at its bottom.

**Transfer:** Reduce a workflow to two or three readable artifacts: an input, a transformed result and a compact confirmation. Keep the light cards visually distinct from the dark marketing controls.

**Build:** Use a relative 1260px stage with 12px–16px corners. Place one white 8px-radius card forward and two offset duplicates behind at reduced opacity; back them with a 540px radial teal field fading to transparent at 65%, opacity 0.2–0.25. Add one small white confirmation pill and a dim dotted vector map or relevant system silhouette behind.

### Luminous network sculpture

**Use:** Signature infrastructure or reach proof device.

**Observed:** A huge partially offstage globe in deep blue-green carries fine gold-white nodes, bright curved connection trails and a mint atmospheric rim. Tiny star points extend into the surrounding pine field; compact factoids sit over the art while a short proof heading occupies the other side.

**Transfer:** Translate reach into a network, orbital system or connected field relevant to the product. Retain the luminous arcs, large offstage mass and small factoid contrast even when a globe is not appropriate.

**Build:** Use an SVG circle with navy fill and a teal radial rim; clip a sparse dotted mesh inside it. Draw quadratic or cubic arcs between selected nodes with thin white strokes, duplicate them under a soft Gaussian blur for bloom, and add tiny warm-white node circles. Place the sculpture partly beyond the left and top edges of a pine stage, mask its lower edge into the canvas, scatter small blurred white points outside, and overlay Network factoid cards. A flat SVG hemisphere and a handful of glowing arcs is the minimum acceptable version.

### Navy developer theater

**Use:** Technical capability chapters.

**Observed:** Overlapping black browser and terminal windows emerge from electric blue haze. Broad dark bezels, tiny window controls and clipped lower edges create depth; subdued labels float above the windows. The light field is brighter near the center and fades into the navy perimeter.

**Transfer:** Stage real technical artifacts from the new product, keeping internals secondary to the recognizable silhouettes and one readable result.

**Build:** Back a 16px-radius navy panel with two large elliptical radial gradients using rgba(18,96,255,0.35) fading to transparent at 50%, each at 0.8 opacity. Layer three differently sized dark rounded windows, a larger center window forward, and use a navy transparent-to-opaque lower mask to dissolve their bases.

### Ecosystem icon current

**Use:** Breadth-of-ecosystem proof.

**Observed:** Rows of colorful square app icons sweep horizontally across a navy field; the nearest row is crisp while distant or peripheral rows disappear into darkness. The headline and short support sit above and partly alongside the stream.

**Transfer:** Use actual integration or capability symbols, or a restrained set of product-relevant pictograms when no integration library exists. Preserve the flowing band instead of making a static white logo wall.

**Build:** Build repeated horizontal flex rows of rounded icon tiles. Duplicate row contents for looping; offset adjacent rows. Apply navy linear-gradient masks at the top, bottom and left copy area so the dense grid emerges from darkness. Keep bright colors inside tile artwork.

### Candid proof photography

**Use:** Customer stories, reassurance and the practical closing scene.

**Observed:** Warm, tactile photographs of founders, shops, products and hands using tools. Story images are wide and evenly cropped; closing photos become two 288px by 384px portrait crops, staggered vertically rather than perfectly aligned. Corners stay modest at 12px or less.

**Transfer:** Use authentic customers and working environments. Match warm daylight, meaningful objects and human scale; combine a detail of work with a person experiencing the result.

### Physical product still life

**Only for:** physical-product pages

**Use:** Light-theme opening and hardware demonstrations.

**Observed:** Devices stand on pale green counters against cream vertical tile, with foliage and soft green directional light. Later images use wood grain, textiles, hands and shop interiors. Hardware feels grounded on real surfaces rather than floating in neon space.

**Transfer:** Photograph the product in a restrained, tactile workspace with cream, wood and pale green surroundings; keep functional controls visible.

### Light software diagrams

**Only for:** focused software product and pricing pages

**Use:** Benefit grids and focused interface demonstrations.

**Observed:** Soft off-white backdrops hold white interface cards, product thumbnails and cropped phone or application windows. Depth comes from soft shadows and overlapping fragments, not colorful enclosing frames. Detailed UI can extend beyond the stage edges.

**Transfer:** Create simplified but credible workflow fragments on a warm gray field; maintain one clear product result per image.

### Icons

**Observed:** Small monochrome SVGs dominate controls: 16px chevrons, 20px small symbols and 32px solid social marks. Outline arrows and utility glyphs use thin 1px round strokes. Factoid symbols are small mint outlines; interface and integration logos retain their own colors only within demonstrations.

**Transfer:** Choose simple outline utility icons with round caps, and reserve filled silhouettes for social or brand symbols. Keep button labels text-led.

## Section recipes

How recurring sections are built.

### First screen: Cinematic possibility opening

**Observed:** A 72px Sticky navigation overlays a full-width human film. The media stage is about 847px tall at desktop, with the next coal chapter visually rolling upward over its lower edge through 48px top corners. Layers run film, dark readability veil, then white copy and pills. The left-aligned promise is a light 96px two-line construction occupying roughly half the width, with a repeated introductory phrase and a changing aspirational completion. A 420px-wide, 24px support paragraph sits beneath; Primary button follows with 32px separation. A distinct outlined alternate route sits near the right edge at the action baseline. Within the first 900px the navigation, human scene, full promise, support and both routes are visible, followed by the beginning of a large phrase-based next chapter; detailed product proof is below the fold.

**Transfer:** Open with the user's desired identity or outcome over a genuine working moment. Without film, use the Human opening film photograph fallback with equal visual weight. Focused software pages instead open in a black two-column stage: 64px headline and compact uppercase category on the left, one floating workflow on the right, with a partner row below. Physical-product pages use a centered 64px promise above a tactile device still life; pricing pages use a centered promise and immediately visible comparable plans.

**Avoid:** Do not replace this with a centered bold SaaS headline over a small laptop mockup; do not let the alternate route compete with the main promise or turn the media into a boxed card.

**Text style:** `display` — Shopify-Inter 300 · 96px/1.08 · tracking -0.02em

### Interactive statement bridge

**Observed:** A large 56px/1 phrase composition spans the dark content width. One phrase is white while the others recede to #71717a; the hidden mint-to-purple text gradient becomes visible through interactive transparent text. The bridge introduces the range before detailed media stages.

**Transfer:** Use a few parallel phrases describing how or where the new product works; maintain an active-versus-inactive reading order instead of four equal slogans.

**Text style:** `statement` — Shopify-Inter 330 · 56px/1 · tracking -0.02em

### Capability chapter

**Observed:** A 56px Heading sits at the shared content edge, then 40px or 64px separation introduces an Inset feature panel or a wide demonstration. Standard chapter padding is 64px. Two or three succinct caption groups beneath the media use Card-title and Body recipes; broad navy scenes use Body-large support.

**Transfer:** Give each capability one dominant image and a short benefit-led explanation rather than equal-weight text and graphic fragments.

**Text style:** `heading` — Shopify-Inter 330 · 56px/1.08 · tracking -0.03em

### Customer range grid

**Observed:** A wide lightweight heading introduces three unboxed Candid proof photography cards. The 409px images sit in a 16px-gutter row, with 32px separation before 20px caption titles and 8px before muted 18px descriptions. One centered Secondary button closes the group.

**Transfer:** Show different customer scales or use situations with genuine differences in the photographs and outcomes.

### Quantified proof scene

**Observed:** Pine chapter contains a split composition: 44px heading, a pair of 96px statistics with 64px top-aligned suffixes, mono mint labels and 0.5px green top rules, followed by Mint rule proof. A bright product interface with scattered image tiles fills the opposite side. Luminous network sculpture extends into the next reassurance block.

**Transfer:** Use substantiated measures and one interface result; retain the contrast between monumental numbers and tiny technical labels.

**Text style:** `statistic` — Shopify-Inter 300 · 96px/0.96

### Human reassurance overlap

**Observed:** On pine, a working portrait and Overlapping quote card fill one half; a 44px benefit heading, muted green paragraph and short mint-rule facts fill the other. The quote is substantial but does not replace the human image.

**Transfer:** Use a specific operational or emotional result, and keep the supporting facts concise.

**Text style:** `quote` — Shopify-Inter 330 · 34px/1.14 · tracking -0.02em

### Practical closing scene

**Observed:** Closing charcoal mist wraps a centered 64px headline, two staggered portrait photographs at left and three large ruled steps at right. Mint 24px markers occupy a separate narrow column; 44px step text follows, with thin white separators under the first steps. Primary button sits beneath the steps. The black Footer columns follows as a distinct, substantial ending.

**Transfer:** Turn the final promise into a small set of achievable actions for the new product. Retain the off-axis photos and oversized step typography even if the scene appears earlier in the story.

**Text style:** `heading-major` — Shopify-Inter 330 · 64px/1.08 · tracking -0.02em

### Product explanation and selector

**Only for:** focused software product pages

**Observed:** A Light product chapter uses a 56px product-heading and a two-column benefit grid with 618px media stages, 24px gutters, 28px titles and 18px muted descriptions. A later Pale demo panel places stacked selectors and an enlarged clipped interface side by side; a dark active vertical rail contrasts with muted inactive rails.

**Transfer:** Use the grid to establish separate benefits, then let one enlarged workflow answer how it works.

**Text style:** `product-heading` — Shopify-Inter 330 · 56px/1.08 · tracking -0.01em

### Plan decision and comparison

**Only for:** pricing pages

**Observed:** A centered 64px promise opens directly onto four Plan cards, with a yearly toggle above left and comparison link above right. Further down, a rounded white comparison chapter changes density: one broad feature column takes about 35% of the width, followed by four equal plan columns, 57px common rows, subtle 10% black rules and a sticky plan header. Dark benefit media, human testimony and paired monumental black stat cards make the decision more than a table.

**Transfer:** Use consistent aligned plan actions and group the full comparison by decision category; put common benefits and credibility between selection and exhaustive detail.

**Text style:** `heading-major` — Shopify-Inter 330 · 64px/1.08 · tracking -0.02em

### Compact final conversion

**Only for:** focused product and pricing pages

**Observed:** Focused software pages end with a dark centered 56px readiness line, two pills and a short eligibility note. Physical-product pages use Warm final call after charcoal resource cards and Question rows, then a white footer. Pricing ends with a 56px line, a short progression of trial benefits separated by green arrows, Email conversion pill, consent line and legally necessary details before the black footer.

**Transfer:** Match the last action to the page's decision: self-serve signup, sales contact or email entry. Keep legal material below the conversion moment rather than inside its headline.

**Text style:** `product-heading` — Shopify-Inter 330 · 56px/1.08 · tracking -0.01em

## Page flow

**Storyline:** aspiration → product possibility → capability demonstrations → human and quantified proof → reduced effort or objections → concrete next action → substantial utility ending

### Broad platform marketing: make a large system feel personally achievable

1. **aspiration** — Full-bleed human film and a changing identity-led promise.
2. **capability range** — Interactive phrase bridge and dark split product stages.
3. **social proof** — Three image-led stories showing different scales of success.
4. **capability depth** — Violet assistant chapter, icon current and navy technical theater.
5. **quantified proof** — Pine statistics, glowing network sculpture and portrait-backed testimony.
6. **closing call** — Practical closing scene with staggered photos and numbered steps, then black Footer columns.

**Transfer:** Use the same alternation of lived experience, product theater and proof without reproducing the original subject sequence.

### Plan selection and detailed buying confidence

1. **pricing** — Centered friendly promise followed by four comparable dark plan cards.
2. **included value** — Large light-backed benefit media and optional add-on cards on dark.
3. **social and quantified proof** — Human quote beside photography, then two large black statistic cards.
4. **comparison** — White rounded chapter with sticky plan columns and exhaustive grouped feature rows.
5. **objection handling** — Dark full-width Question rows with circular plus controls.
6. **closing call** — Benefit progression and Email conversion pill, then necessary terms and black Footer columns.

**Transfer:** Balance immediate choice with deeper evidence; let the comparison be dense while surrounding chapters remain airy.

### Introduce a focused software capability and explain the workflow

1. **promise** — Black split opening with small category label, 64px headline, floating workflow and paired pills.
2. **ecosystem proof** — Monochrome partner marks in a restrained centered row.
3. **capability explanation** — White rounded chapter with four media-led benefits in two columns.
4. **product demonstration** — Large pale interface stage beside stacked vertical-rail selectors.
5. **social proof** — Dark rounded testimonial carousel with prominent quote, square product photography and circular controls.
6. **closing call** — Centered dark readiness statement and paired actions, short eligibility note, then black Footer columns.

**Transfer:** Lead with a single new possibility, explain it clearly on light surfaces, then return to dark for confidence and conversion.

### Sell a physical and software system through real-world use

1. **promise** — White global and local navigation above a centered headline and full-width tactile still life.
2. **social proof** — Logo row and three tall photographs representing different operating situations.
3. **system explanation** — Overlapping workplace photos with lime hotspot pills, then a warm-paper demo strip.
4. **capability chapters** — Dark software benefits, wide hardware photography, payment detail and ruled light feature grid.
5. **reduced effort** — Three setup steps followed by a lime promotional band.
6. **education and objections** — Charcoal image-led resource cards and full-width Question rows.
7. **closing call** — Warm brown conversion band with paired pills and a smaller existing-user route; white Footer columns.

**Transfer:** Ground the technology in materials, hands and use contexts, preserving dark chapters only where explanation or resources benefit from contrast.

## Writing

Confident, encouraging and conversational, with large ambitions expressed in everyday verbs. It moves easily from short, rhythmic promises to specific practical explanations and credible numerical proof.

**Do not copy:** Do not reuse Shopify names, marks, product names, customer identities, quotes, prices, trial offers, market-share claims, transaction totals or performance figures as claims for another product. Source examples illustrate voice only.

- **Addressing the reader:** Speak directly to you and your business. The platform supports your agency rather than becoming the hero; we and us appear occasionally as a friendly counterpart.
- **Rhythm:** Headlines commonly use 3–10 words, often split into two punchy clauses. Support tends to be one or two short sentences; captions start with a verb. Contractions and conversational fragments replace formal exposition.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Invite an ambitious future identity or state a timely opportunity followed by a direct action. | 4–10 words | “Be the next”<br>“AI shopping is here. Start selling.”<br>“The point of sale for every sale” |
| Chapter heading | Pair a broad benefit with a plain-language reversal or rhythmic contrast. | 4–10 words | “Show up everywhere. Without going anywhere.”<br>“Rock steady. Blazing fast.”<br>“All the features. All in one place.” |
| Support | Explain the user outcome in concrete operational terms; remove effort without sounding magical. | 1–3 short sentences | “Reach new buyers in AI chats and manage it all in one place with [Brand].”<br>“Whether you’re starting out or switching platforms, we're here to help.” |
| Plan introduction | Use a friendly shared-word turn, then state the offer plainly. | 5–9 words plus one explanatory line | “You've got plans. Us too.” |
| Action | Start with a short verb; conversion is clear, while closing actions can feel like an encouraging nudge. | 2–6 words | “Start for free”<br>“Take your shot”<br>“Pick a plan that fits” |
| Final invitation | Resolve ambition into forward movement or readiness. | 4–12 words | “Turn plans into progress”<br>“Ready to sell in AI? With [Brand], you’re set.” |

**Words and phrasing to use:** build; start; grow; sell; your; all in one place; ready; fast; everywhere; from first to full scale

**Avoid:** revolutionary synergy; best-in-class solutions; leverage our ecosystem; unlock unparalleled potential; passive corporate introductions

**Rules:**

- Lead with the reader's benefit, then name the mechanism in the support paragraph.
- Use paired clauses and light wordplay sparingly enough that practical details remain easy to find.
- Make specific numerical claims only where they can be substantiated; place the qualification beside or below the proof.
- Keep action labels short and literal at the top; a more expressive closing action can follow a concrete set of steps.
- Use customer language in quotations and operational language in comparison tables.

## Do's and Don'ts

### Do

- Keep the main display light at weight 300, not medium or bold.
- Use the 1260px desktop content span and 90px side alignment to unify otherwise different media scenes.
- Give standard chapters 64px vertical padding and proof chapters up to 128px breathing room.
- Keep primary pills white on dark, 56px tall, with 18px/28px weight 550 labels.
- Let major chapters turn through 48px top corners while ordinary stages use 12px–16px radii.
- Make proof numerals 96px and their suffixes 64px, with small mint mono labels.
- Use actual people and working details as the warm counterpoint to luminous digital scenes.
- End with a substantial conversion composition and 80px-padded footer rather than an abrupt utility strip.

### Don't

- Do not make mint the default button fill; its role is signal text and thin rules.
- Do not use heavy 700-weight headings to imitate impact; this hierarchy gets impact from size and lightness.
- Do not wrap every image caption in a bordered card; customer stories are unboxed.
- Do not apply the lime promotion color across an ordinary dark marketing page; it belongs to the physical-product variant.
- Do not convert every chapter into white; the default visual identity depends on continuous near-black green with bounded navy and violet fields.
- Do not give stats and descriptive body text the same scale or weight; preserve the 96px-to-18px contrast.
- Do not turn the luminous network into a dashboard of equal fact tiles; the sculpture remains dominant.
- Do not carry the 24px pricing-card radius onto pills or the 48px chapter radius onto small controls.

## Motion and responsive

### Motion

**Observed:**

- Declared: primary and secondary buttons transition all properties over 0.15s with cubic-bezier(.4,0,.2,1); footer color transitions use 0.2s with the same curve.
- The opening changes aspirational headline completions over human footage. Product demonstrations use floating, orbiting and flipping constructions; declared examples include 6s ease-in-out float, 36s linear orbit and 8s linear glow cycles.
- Declared: icon-stream movement includes 240s linear infinite horizontal scrolling; factoids use a 0.5s ease-in-out fade with 0.5s delay. Pricing cards have staggered 0.8s flip animations.

**Transfer:**

- Keep the opening footage human and the text completion short enough to remain legible between changes.
- Use slow looping icon currents and localized glow motion to imply platform activity, while conversion pills remain steady.
- Keep the network readable as a static composition with luminous trails and factoid contrast.

**Unknown:**

- Exact video cut rhythm, headline-change timing, full scroll choreography and animation triggers are unspecified.

### Responsive

**Observed:**

- Desktop uses 12-column chapter grids; declared layout classes also describe 4-column and 8-column grids.
- Plan tracks declare 85vw card minimums at narrow sizes and 316px minimums at wider sizes. Footer classes switch to a vertical arrangement; some image stories use scroll snapping.
- Reduced-motion classes are present in the opening construction.

**Transfer:**

- On narrow layouts, keep the person or main workflow large and stack copy above or over a single useful crop rather than shrinking the whole desktop stage.
- Let plan and story cards remain horizontally browsable where a stacked list would overwhelm the narrative.
- Reposition the luminous network so one offstage mass and one factoid remain visible, with the explanatory text outside its brightest trails.

**Unknown:**

- Exact breakpoint thresholds and mobile type sizes are not specified; narrow-screen arrangements here are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
