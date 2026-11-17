# RevenueCat — pastel tools afloat

## Overview

A light, approachable technical style that makes complex software feel tangible and easy to adopt. Tight geometric sans headlines sit above lighter grotesk explanations, with inky purple text, periwinkle actions and tiny coral and mint signals. Floating interface compositions, softly tinted cards and abundant white space give product-heavy pages a friendly, polished rhythm without becoming decorative spectacle.

### Essentials

- Headlines feel compact and rounded rather than massive: Object Sans 500, 60px/1.125 with -0.04em tracking for the main promise; 56px/1.125 for centered chapter leads and 40px/1.125 for split chapters.
- The opening is a working product still life: a 64px navigation strip above roughly equal text and illustration columns, with a 600px square layered interface scene, a 480px email capsule and three compact proof numbers beneath the copy.
- Actions are capsules, not rounded rectangles: 48px primary buttons with 28px horizontal padding, nested inside a 64px input in the opening; navigation uses 36px capsules.
- Color is contained like light inside objects: white and #f9f9fb dominate whole bands, while periwinkle, coral and mint appear in small icons, data, blurred card corners and thin gradient edges rather than saturated section fills.
- Product imagery floats in shallow layers: white interface windows, fine pale rules, soft blue-purple shadows and occasional dotted orbits. Every new landing page needs this dimensional product stage; a few purpose-built interface fragments are the minimum substitute for elaborate artwork.
- Proof has two deliberately different scales: compact 210px logo plinths beside 30px outcome sentences, and broad testimonial cards with a 280px metric rail and light 48px numerals. Ratings expand to light 80px numerals rather than bold dashboard counters.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Periwinkle | `#576ddb` | `--color-action` | action, accent, text | Filled primary actions and blue proof numerals. |
| Deep periwinkle | `#3d52b8` | `--color-link` | link, text | Unfilled text actions with a small chevron. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral signal | `#f2545c` | `--color-coral` | accent, text | Inline outcomes, selected metric numerals and small pictograms, not full bands. |
| Lavender edge | `#d6dbf5` | `--color-gradient-edge` | border, accent | Thin proof-card frames and pricing card outlines. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Purple ink | `#1f1f47` | `--color-ink` | text | Headlines, navigation and strongest labels. |
| Slate purple | `#3d3d5c` | `--color-body` | text | Body copy and supporting explanations; alpha variants soften secondary labels. |
| Button outline | `#abb3ba` | `--color-outline` | border | Compact outlined navigation action. |
| Gray hairline | `#e3e6e8` | `--color-rule` | border | Chart cards, footer divider and separators between opening statistics. |
| Blue hairline | `#eaedf6` | `--color-soft-edge` | border, surface | Illustrated tile borders, input outline and thin carousel progress tracks. |
| Mist edge | `#ebedf5` | `--color-gradient-end` | border, accent | Low-contrast terminal color of proof frame gradients. |
| Panel seam | `#ebeef4` | `--color-panel-edge` | border | Technical comparison panel and row seams. |
| Blue porcelain | `#f8f9fb` | `--color-illustration-card` | surface | Illustrated benefit tiles and the opaque end of their caption fade. |
| Cool porcelain | `#f9f9fb` | `--color-band` | background, surface | Opening, alternating chapter bands, audience cards, proof rails and footer. |
| White | `#ffffff` | `--color-white` | background, surface, text | Default canvas, floating windows and reversed button labels. |

## Typography

- **objectSans** — Headings, actions, navigation and prominent proof copy. Geometric sans with round counters, a substantial x-height and tightly joined headline rhythm. If unavailable, use **DM Sans**. Use weights 300–700 and retain tight display tracking. Font stack: "objectSans", "DM Sans", ui-sans-serif, system-ui, sans-serif.
- **helveticaNeue** — Paragraphs, illustrated-tile captions and detailed feature descriptions. Neutral neo-grotesk; light body weights contrast with medium geometric headings. If unavailable, use **Roboto**. Use 300 for explanatory text and 400 for opening support. Font stack: "helveticaNeue", "Roboto", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| rating | objectSans | 300 | 80px | 1.375 | -0.04em | Review rating numerals in trust tiles. |
| display | objectSans | 500 | 60px | 1.125 | -0.04em | Default main landing-page promise. |
| heading-lg | objectSans | 500 | 56px | 1.125 | -0.04em | Centered chapter leads, closing calls and feature-page opening headlines. |
| metric | objectSans | 300 | 48px | 1 | -0.04em | Testimonial metric rail and compact rating denominators. |
| heading | objectSans | 500 | 40px | 1.125 | -0.04em | Alternating split-section headings. |
| banner-heading | objectSans | 500 | 32px | 1.125 | -0.02em | Wide onboarding banners. |
| proof-sentence | objectSans | 400 | 30px | 1.5 | -0.04em | Compact outcome statements beside logo plinths. |
| audience-heading | objectSans | 400 | 28px | 1 | -0.04em | Short titles in pastel audience cards. |
| opening-stat | objectSans | 500 | 24px | 1.375 | -0.02em | Small proof numbers under the opening form. |
| quote | helveticaNeue | 300 | 22px | 1.5 | normal | Long quotations inside wide testimonial cards. |
| hero-support | helveticaNeue | 400 | 20px | 1.375 | normal | Opening explanation. |
| section-support | helveticaNeue | 300 | 20px | 1.375 | normal | Centered support under chapter headlines. |
| split-support | helveticaNeue | 300 | 20px | 1.375 | -0.02em | Explanations in split feature chapters. |
| tile-heading | helveticaNeue | 500 | 18px | 28px | normal | Headings at the bottom of illustrated benefit tiles. |
| tile-copy | helveticaNeue | 300 | 18px | 1.375 | normal | Descriptions beneath illustrated tile headings. |
| body | helveticaNeue | 300 | 16px | 1.5 | normal | Audience cards and small feature descriptions. |
| action | objectSans | 500 | 16px | 1.5 | normal | Default filled buttons and chevron text links. |
| input-action | objectSans | 500 | 16px | 1 | -0.02em | Button nested within the opening email capsule. |
| footer-heading | objectSans | 500 | 16px | 1 | normal | Footer directory group labels. |
| nav | objectSans | 400 | 14px | 20px | normal | Navigation and footer links. |
| compact-action | objectSans | 500 | 14px | 1 | normal | Compact navigation capsules. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | objectSans | 500 | 64px | 1.125 | -0.025em | Centered pricing promise. |
| pricing pages | pricing-heading | objectSans | 500 | 32px | 1.125 | -0.04em | Plan names or entry-point promises. |
| technical feature catalogs | detail-heading | objectSans | 500 | 24px | 1.375 | -0.04em | Headings in technical demonstration cards. |
| technical feature catalogs | detail-copy | helveticaNeue | 300 | 16px | 1.375 | normal | Detailed copy above chart or interface examples. |
| feature landing pages | feature-label | helveticaNeue | 400 | 14px | 20px | normal | Small raised category pill above a feature headline. |

**Notes:**

- The default hierarchy changes size more than weight: most large headings remain at 500 and -0.04em tracking.
- Keep explanatory text visibly lighter than headings; reserve 700 for customer identity in testimonial headers, not ordinary chapter titles.
- Body text uses neutral tracking except the slightly tightened split-section support. Rating and outcome numerals are conspicuously light.

## Layout

**Density:** Airy at chapter scale, comfortable inside cards; broad pauses separate compact groups of product detail.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Technical card heading-to-copy gap. |
| 14px | Audience title-to-copy gap and footer group spacing. |
| 16px | Default headline-to-support gap. |
| 24px | Illustrated-card caption padding and text-link offset after split copy. |
| 28px | Technical card text-to-media gap and primary button horizontal padding. |
| 32px | Main side padding, card-grid gaps and closing action separation. |
| 40px | Logo-plinth-to-quote gap and pricing card padding. |
| 48px | Testimonial inner padding and wide banner inner padding. |
| 64px | Chapter heading-to-audience-carousel interval. |
| 120px | Testimonial band top and bottom padding. |
| 160px | Major chapter pauses and closing-call vertical padding. |

### Containers and grids

- **container**: max width 1280px · side padding 32px. Centered outer box giving 1216px of usable width at desktop.
- **heading measure**: max width 896px. Centered chapter headlines; support is narrower at 672px.
- **support measure**: max width 672px. Centered explanatory paragraphs and longer closing support.
- **benefit grid**: 3 columns · gap 32px. Three 384px illustrated tiles across the content width; support chapters also use two 592px tiles.
- **compact proof**: max width 840px · gap 40px. Centered horizontal logo plinth and outcome sentence.
- **testimonial**: max width 1060px. Broad floating quote card with a 280px right-hand metric rail.
- **footer directory**: 4 columns · gap 80px. Four equal directory columns; legal occupies a second group in the last column.
- **pricing container** (only for pricing pages): max width 1024px · side padding 32px. 960px usable plan cards and FAQ rows.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and input | 9999px (pill) |
|  | cards | 16px |
|  | logo plinth | 32px |
| technical feature catalogs | chart media | 12px |
| visual builder galleries | phone gallery | 40px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating proof | `5px 5px 20px rgba(71,92,133,0.1), 0px 30px 60px rgba(144,138,208,0.1)` | Large testimonial frame. |
| email capsule | `0px 6px 16px rgba(61,75,143,0.15)` | Opening email input. |
| logo plinth | `0px 3px 16px rgba(73,46,107,0.14)` | Compact customer logo plinth. |

### Surfaces

#### White canvas · level 0

**Use:** Default page canvas and clear chapters.

**CSS:** `background: #ffffff`

#### Porcelain band · level 0

**Use:** Opening, alternating chapters, testimonial backing and footer.

**CSS:** `background: #f9f9fb`

**Observed:** Full-width flat cool off-white rather than a boxed panel.

**Transfer:** Switch the canvas at narrative boundaries, keeping large areas nearly neutral.

#### Illustrated tile · level 1

**Use:** Contained product benefit illustrations.

**CSS:** `background: #f8f9fb; border: 1px solid #eaedf6; border-radius: 16px; overflow: hidden`

**Observed:** The illustration fills the card above a bottom caption. A porcelain-to-transparent fade protects text without a hard division.

**Transfer:** Use the same soft backing behind simplified product fragments.

#### Pastel edge card · level 1

**Use:** Audience and capability cards.

**CSS:** `background: linear-gradient(#f9f9fb, #f9f9fb) padding-box, linear-gradient(135deg, rgba(184,194,224,1), rgba(234,237,246,0)) border-box, linear-gradient(#eaedf6, #eaedf6) border-box; border: 1px solid transparent; border-radius: 16px`

**Observed:** A blurred upper-left wash and a raised white icon puck add color inside an otherwise pale card; coral and mint are sister variants.

**Transfer:** Assign one restrained tint per category rather than making rainbow-filled cards.

#### Proof frame · level 1

**Use:** Large quote-card perimeter.

**CSS:** `background: linear-gradient(134deg, #d6dbf5 0%, #ebedf5 100%); padding: 1px; border-radius: 16px; box-shadow: 5px 5px 20px rgba(71,92,133,0.1), 0px 30px 60px rgba(144,138,208,0.1)`

**Observed:** White content is inset inside the gradient frame; the metric rail is porcelain.

**Transfer:** Keep the gradient at the edge rather than washing over the quotation.

#### Logo plinth · level 2

**Use:** Small customer proof object.

**CSS:** `background: linear-gradient(#ffffff, #ffffff) padding-box, linear-gradient(135deg, rgba(193,201,246,0.87), rgba(224,228,248,1) 30%, rgba(224,228,248,1) 60%, #ffffff) border-box; border: 1px solid transparent; border-radius: 32px; padding: 24px; box-shadow: 0px 3px 16px rgba(73,46,107,0.14); backdrop-filter: blur(12px)`

**Observed:** A luminous white square with a fine lilac perimeter, not visibly transparent glass.

**Transfer:** Center one customer mark or a simple neutral pictogram on the plinth.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 28px; background: #576ddb; color: #ffffff; border-radius: 9999px`

**Text style:** `action` — objectSans 500 · 16px/1.5

**Observed:** Usually paired with a chevron text action rather than a second filled button. Navigation uses a shorter 36px version with 18px side padding.

**States:** Declared: hover background-color hsl(230 50% 48%); focus-visible outline-style none and zero box-shadow.

### Outlined navigation action

**Use:** Sales contact alongside the compact filled signup action.

**CSS:** `display: inline-flex; height: 36px; padding: 0px 18px; border: 1px solid #abb3ba; border-radius: 9999px; color: #3d3d5c; align-items: center`

**Text style:** `compact-action` — objectSans 500 · 14px/1

**Observed:** Unfilled; visually subordinate to the adjacent periwinkle capsule.

**States:** Declared: hover border-color hsl(240 20% 30%) and color hsl(240 39% 20%); focus-visible outline-style none and zero box-shadow.

### Chevron link

**Use:** Documentation, secondary conversion and case-study actions.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; color: #3d52b8; border-radius: 4px`

**Text style:** `action` — objectSans 500 · 16px/1.5

**Observed:** Text followed by a narrow right-pointing chevron, no underline or enclosing border.

**States:** Declared: hover color hsl(240 39% 20%); focus-visible outline-style none and zero box-shadow.

### Email conversion capsule

**Use:** Low-friction opening signup form.

**CSS:** `height: 64px; width: 480px; max-width: 100%; padding: 20px 176px 20px 28px; background: #ffffff; border: 1px solid #eaedf6; border-radius: 9999px; box-shadow: 0px 6px 16px rgba(61,75,143,0.15)`

**Observed:** A relative wrapper holds the input and an inset Primary button, 8px from the top, right and bottom; the nested label uses input-action.

**Transfer:** Keep one field only; use an appropriate contact identifier for the new offer.

### Navigation item

**Use:** Shared top navigation.

**CSS:** `display: inline-flex; align-items: center; height: 64px; padding: 0px 12px; gap: 4px; color: #1f1f47; border-radius: 4px`

**Text style:** `nav` — objectSans 400 · 14px/20px

**Observed:** Small dropdown triangles accompany category labels. Logo sits left, utility actions right.

**States:** Declared: hover color hsl(357 86% 64%); focus-visible outline-style none and zero box-shadow.

### Audience card

**Use:** Scan-friendly entry points by user role or capability.

**CSS:** `padding: 20px 24px; border: 1px solid transparent; border-radius: 16px; overflow: hidden; background: linear-gradient(#f9f9fb, #f9f9fb) padding-box, linear-gradient(135deg, rgba(184,194,224,1), rgba(234,237,246,0)) border-box, linear-gradient(#eaedf6, #eaedf6) border-box`

**Text style:** `audience-heading` — objectSans 400 · 28px/1 · tracking -0.04em

**Observed:** Uses Pastel edge card with an icon puck first, then title, short paragraph and bottom chevron link. The horizontal carousel reveals a partial next card.

**Transfer:** Use three or four distinct audience tasks, not a dense list of every feature.

### Illustrated benefit card

**Use:** Show one product benefit through a UI vignette.

**CSS:** `background: #f8f9fb; border: 1px solid #eaedf6; border-radius: 16px; overflow: hidden; position: relative`

**Text style:** `tile-heading` — helveticaNeue 500 · 18px/28px

**Observed:** Media owns most of the tile. Title and tile-copy sit together at the bottom with 24px inset and a soft fade behind them; no separate white caption slab.

### Testimonial card

**Use:** Long-form customer proof with quantified outcome.

**CSS:** `background: #ffffff; border-radius: 16px; overflow: hidden; display: flex`

**Text style:** `quote` — helveticaNeue 300 · 22px/1.5

**Observed:** Inside Proof frame: a white 778px quote area with 48px inset, identity header, quotation and author portrait low down; a 280px porcelain rail holds the metric high and Chevron link low. A customer-logo selector runs beneath with a thin active rule.

### Trust tile

**Use:** Ratings and certification reassurance.

**CSS:** `background: linear-gradient(90deg, #d6dbf5, #ebedf5); padding: 1px; border-radius: 16px; overflow: hidden`

**Text style:** `rating` — objectSans 300 · 80px/1.375 · tracking -0.04em

**Observed:** A porcelain inner panel centers a light colored rating with smaller denominator, or an 88px seal; a small label sits below. Default group is four tiles with 32px gaps. Pricing uses three taller explanatory tiles and a wide certification row.

### Footer directory

**Use:** Shared dense but calm ending after the closing call.

**CSS:** `background: #f9f9fb; padding: 96px 0px 64px`

**Text style:** `nav` — objectSans 400 · 14px/20px

**Observed:** Four columns use footer-heading labels and muted links. Below them, a small wordmark and social icons sit opposite distribution badges; a hairline separates copyright and language selection. No giant closing wordmark or dark inversion.

### Plan panel

**Only for:** pricing pages

**Use:** Explain an entry tier or custom contract without a tall tower of plans.

**CSS:** `display: flex; gap: 32px; padding: 40px; background: #ffffff; border: 1px solid #d6dbf5; border-radius: 16px; overflow: hidden; box-shadow: 0px 4px 20px rgba(87,108,219,0.06), 0px 30px 60px rgba(144,138,208,0.05), 5px 5px 30px rgba(71,92,133,0.03)`

**Text style:** `pricing-heading` — objectSans 500 · 32px/1.125 · tracking -0.04em

**Observed:** Wide horizontal stacked panels: promise and action on the left, included capabilities on the right. Custom pricing uses a thin coral-to-blue perimeter and outlined action instead.

### Technical showcase card

**Only for:** technical feature catalogs

**Use:** Explain an individual data view or technical capability.

**CSS:** `background: #f9f9fb; border: 1px solid #e3e6e8; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; gap: 28px`

**Text style:** `detail-heading` — objectSans 500 · 24px/1.375 · tracking -0.04em

**Observed:** Heading, detail-copy and an inset interface image. The inner image has a 12px radius, pale outline and a small cool shadow. Cards sit on a horizontal track rather than shrinking all examples to fit.

## Imagery and graphics

### Layered product still life

**Use:** Opening and split capability chapters.

**Observed:** White editor panels, code, charts and phone previews overlap frontally, with small depth offsets and cool diffuse shadows. Real-world photography appears inside the phone preview rather than as a full-bleed backdrop. The main opening scene is about as wide as the text column.

**Transfer:** Stage two or three authentic workflow fragments: a source or setup view behind, a working screen in front and a small result card off to the side. Minimum version is a clean static SVG or HTML composition, not a generic laptop mockup.

**Build:** Use a roughly 600px square stage with three white panels. Put a taller setup panel behind at upper left, a larger editor panel in front toward the right and a compact result card at lower left. Give panels 12–24px corners, 1px pale blue-gray edges and low-opacity cool shadows. Confine stronger colors to tiny status dots, charts and one image within the front panel.

### Pastel corner light and icon pucks

**Use:** Audience cards and capability summaries.

**Observed:** A nearly imperceptible lilac, pink or mint corner glow sits behind a white circular icon puck. There is no glossy bevel or saturated card fill.

**Transfer:** Use simple task pictograms and preserve the hierarchy of white puck, tinted light and neutral card.

**Build:** Clip a 200px circle near the card's upper-left corner, offset 30px to the left; use rgba(193,201,246,0.5), rgba(247,212,212,0.5) or rgba(193,246,224,0.5), filter blur(120px). Add a 60px white circle above it with a 28px colored pictogram and a faint matching shadow.

### Dotted workflow orbits

**Use:** Product diagrams and floating feature scenes.

**Observed:** Fine dotted loops or right-angle connectors link white icon nodes; tiny periwinkle, coral and mint points mark junctions. Lines stay much lighter than the UI objects.

**Transfer:** Turn the new workflow into a few legible inputs and outputs. Keep connections secondary to the actual product surface.

**Build:** In SVG, draw one or two ellipses behind the central interface with a 1px rgba(61,61,92,0.12) stroke and a short dash pattern. Add a few 3–5px colored circles. For infrastructure diagrams use orthogonal dotted connectors between white circular nodes and a centered white rectangular or hexagonal hub.

### Captioned interface vignettes

**Use:** Three-column and two-column benefit grids.

**Observed:** Small UI windows, notification stacks, charts and abstract platform connections sit on cool faintly tinted backing. Illustrations fade into the same porcelain as their captions, creating one continuous object.

**Transfer:** Reduce the interface to the controls needed to demonstrate the benefit; keep enough real labels to be credible. Maintain a clear lower zone for the caption.

### Phone inspiration gallery

**Only for:** visual builder galleries

**Use:** Show the breadth of customer-facing outputs.

**Observed:** A horizontal row of tall finished mobile layouts with vivid photography or illustration contained inside thick white rounded shells. Five examples extend beyond the content area; edge items fade toward white and circular arrow controls float at the sides.

**Transfer:** Use genuinely varied outputs from the new product, retaining the white shells so the page itself remains neutral.

**Build:** Make each shell 280px by 512px with a 10px white border, 40px corners and a soft 0px 8px 32px rgba(12,29,110,0.1) shadow. Place finished layouts inside, clip overflow and mask the track's outer edges with a white fade.

### Icons

**Observed:** Small functional chevrons are narrow filled shapes, 6–8px wide in a 16px-high slot. Feature pictograms are usually filled 28px symbols on white 60px pucks; checklist marks use 16px outlines with approximately 1.3px round strokes. Footer social symbols are 24px and dark purple.

**Transfer:** Use simple recognizable solid task symbols for feature pucks and thin outline checks for details. Avoid a single oversized outline-icon style everywhere.

## Section recipes

How recurring sections are built.

### First screen: Floating workflow opening

**Observed:** Porcelain band starts with Navigation item in a 64px header. Inside the 1280px container, two roughly equal columns balance a left-aligned two-line promise with a 600px square product still life on the right. The text is vertically centered against the scene, not pinned to its top. The display headline spans most of the text column, then hero-support follows at 16px. Email conversion capsule follows after 32px, with three opening-stat values beneath, separated by 56px vertical hairlines. The back-to-front stack is neutral canvas, soft illustration light, rear code/setup panel, foreground editor/phone, small chart card. Within the first 900px the navigation, headline, full support, form, stats, complete product scene and muted customer logo strip are visible; the next major chapter falls below.

**Transfer:** For a new landing page, retain the balanced working-product still life and compact proof under the form. Construct the scene with simplified authentic workflow fragments if finished media is unavailable. Feature pages use a feature-label pill, heading-lg headline and a button-plus-link pair instead of the email form and stats. Pricing opens centered with pricing-display over stacked Plan panels.

**Avoid:** Do not replace the right half with an abstract gradient blob, enormous mascot, full-bleed photo or raw full-dashboard image. Do not enlarge the promise into edge-to-edge poster type.

**Text style:** `display` — objectSans 500 · 60px/1.125 · tracking -0.04em

### Centered chapter heading

**Observed:** heading-lg centered within 896px, section-support within 672px, 16–20px below. Illustrated grids begin about 40px later; audience carousels allow 64px. White and Porcelain band establish chapter boundaries.

**Transfer:** Use a brief benefit headline to introduce a family of related capabilities, not one heading per tiny feature.

**Text style:** `heading-lg` — objectSans 500 · 56px/1.125 · tracking -0.04em

### Alternating workflow split

**Observed:** Text and product art share the 1216px usable width. A heading at 40px precedes split-support by 16px and a Chevron link by 24px. Text is vertically centered; illustration sides alternate across consecutive chapters. Broad neutral space keeps the pair separate from its neighbors.

**Transfer:** Explain one task and one result per pair. Let the illustration demonstrate the mechanism instead of repeating the paragraph.

**Text style:** `heading` — objectSans 500 · 40px/1.125 · tracking -0.04em

### Illustrated benefit grid

**Observed:** Illustrated benefit cards form three columns with 32px gaps, or two columns for broader workflows. Each tile uses Illustrated tile, a large interface vignette and bottom caption. Caption titles are 18px medium with light 18px explanations.

**Transfer:** Choose a few concrete benefits whose mechanism can each be shown in one visual.

**Text style:** `tile-heading` — helveticaNeue 500 · 18px/28px

### Compact proof interruption

**Observed:** An 840px-wide group pairs Logo plinth at 210px square with a proof-sentence across a 40px gap. A short measured outcome may be coral within otherwise inky copy. Chevron link follows below the statement. This interrupts long feature chapters without becoming another grid.

**Transfer:** Use one verified customer result or quote. For non-customer proof, put a neutral institution or category mark on the plinth and explain the real validation.

**Text style:** `proof-sentence` — objectSans 400 · 30px/1.5 · tracking -0.04em

### Long quote with metric rail

**Observed:** A Porcelain band with 120px vertical padding holds a centered heading and Testimonial card in Proof frame. The quote is the dominant content, with light metric numerals isolated in the side rail. Customer logos below act as selectors, with one thin dark segment on a faint track.

**Transfer:** Keep narrative proof and numerical proof in separate zones so neither becomes a decorative statistic dashboard.

**Text style:** `quote` — helveticaNeue 300 · 22px/1.5

### Technical catalog track

**Observed:** A left-aligned heading and short support introduce a horizontal row of Technical showcase cards. Two complete 576px cards and part of the next can be visible; each image is inset and softly raised. Chapters alternate white and porcelain.

**Transfer:** Use for a deep feature catalog; preserve readable UI size through horizontal overflow rather than compressing three interfaces.

**Text style:** `heading` — objectSans 500 · 40px/1.125 · tracking -0.04em

### Pricing reassurance and objections

**Observed:** Centered pricing-display leads to two wide Plan panels, then capability explanations and a three-column set of taller Trust tiles. FAQ uses a 960px measure, 20px question labels, 20px vertical row padding, thin separators and a small plus at the left. A translucent rounded in-page navigation strip tracks the long page.

**Transfer:** Lead with the charging principle; explain inclusions and practical objections before the final action. Keep the plan comparison horizontal rather than multiplying tiers.

### Technical work comparison

**Observed:** A centered chapter lead introduces a 1216px white rounded panel with soft cool halo. Three columns contrast the user's goal, implementation burden and managed capability. Approximately 88px rows use pale horizontal seams, with checks in the first column.

**Transfer:** Use for technical buy-versus-build decisions where the hidden work is specific and verifiable, not for a generic competitor scoring matrix.

### Closing invitation and directory

**Observed:** The close is deliberately unboxed: a centered heading-lg, support at 20px below, and Primary button plus Chevron link 32px later, all with 160px vertical padding. Default is white; the infrastructure-oriented variant continues Porcelain band and uses a longer task-specific promise. Footer directory follows on porcelain with 96px top and 64px bottom padding.

**Transfer:** End with an accessible next step and one alternative conversation route, then a genuinely useful directory. Keep the calm scale even after a visually rich page.

**Text style:** `heading-lg` — objectSans 500 · 56px/1.125 · tracking -0.04em

## Page flow

**Storyline:** Promise and tangible product → adoption proof → capability chapters interrupted by customer outcomes → deeper validation or objections → simple closing invitation → directory.

### Broad product landing page that connects multiple audiences to one platform

1. **Promise** — Balanced workflow opening with signup capsule and compact scale statistics.
2. **Audience orientation** — Pastel cards translate the platform into role-specific value.
3. **Capability chapters** — Illustrated benefit grids and alternating workflow splits, punctuated by compact proof plinths.
4. **Customer validation** — Wide testimonial carousel followed by ratings and certification tiles.
5. **Closing call** — Unboxed centered invitation and four-column directory.

**Transfer:** Vary capability depth to suit the new product while retaining a tangible opening, proof interruptions and a calm close.

### Pricing page that explains the charging model before qualifying complex needs

1. **Pricing promise** — Centered headline over stacked horizontal entry and custom-contract panels.
2. **Inclusions** — Product explanation followed by pastel capability cards with checklists.
3. **Reassurance** — Quote-with-metric carousel, taller rating tiles and certification row.
4. **Objection handling** — Narrow FAQ accordion with left plus icons.
5. **Closing call** — Shared centered invitation before the directory.

**Transfer:** Use the charging principle as the main promise rather than displaying a wall of price numerals.

### Detailed analytical feature page

1. **Promise** — Category pill, feature headline, chart scene and two actions; trusted-customer strip below.
2. **Early proof** — Compact customer quote before the detailed explanation.
3. **Capability overview** — A workflow split and centered headline introduce a catalog.
4. **Product demonstration** — Repeated technical-card tracks show related data views on alternating neutral bands.
5. **Portability reassurance** — An export/integration diagram addresses the lock-in concern.
6. **Closing call** — Shared invitation and directory.

**Transfer:** For a data-heavy product, group views by decisions the user makes, preserving readable examples.

### Technical infrastructure feature page that makes invisible work concrete

1. **Promise** — Category pill and benefit promise beside a connected service diagram.
2. **Fast start** — Three compact benefits, a wide onboarding banner and an early customer quote.
3. **Capability chapters** — Grouped alternating diagrams explain operations, access and data movement; compact proof interrupts.
4. **System explanation** — One tall connection diagram sits beside stacked output capability cards.
5. **Work comparison** — Three-column table makes implementation burden explicit.
6. **Reassurance and closing call** — Security tiles precede a longer task-specific closing promise on porcelain, then directory.

**Transfer:** Show concrete responsibilities and workflow handoffs instead of using server imagery as decoration.

### Visual builder feature page that demonstrates speed and output variety

1. **Promise** — Category pill, benefit headline and actions beside a tall live-product scene.
2. **Demonstration** — Video introduction followed by a split chapter with a large rounded editor media panel.
3. **Output breadth** — Finished mobile layouts fill a horizontally overflowing white-shell gallery.
4. **Control and learning** — Detailed targeting chapter, customer proof, then two centered chapters pairing UI art with concise feature lists.
5. **Extensibility** — Toolkit split addresses advanced automation.
6. **Closing call** — Centered invitation with feature-specific support and the shared directory.

**Transfer:** Keep the colorful outputs inside neutral frames and explain the creation-to-improvement loop.

## Writing

Friendly technical confidence: clear operational benefits, plain verbs and concrete mechanisms. It lowers the perceived burden of complex work without turning every claim into hype.

**Do not copy:** Do not reuse RevenueCat names, logos, interface artwork, customer names, quotes, adoption figures, rating values, certification claims or business results. Replace them with the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Product references explain what the service handles; we appears mainly when explaining responsibilities.
- **Rhythm:** Headlines usually run 4–10 words; compact paired clauses are common. Support is one or two sentences, followed by a short action. Feature paragraphs get more specific rather than more promotional.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Verb-led business benefit, or name a burdensome task the user can stop doing. | 6–10 words | “Build and grow your app business”<br>“Run subscription infrastructure without building it” |
| Chapter headline | Pair a practical improvement with its outcome; short sentence fragments can work together. | 4–10 words | “Smarter support. Stronger retention”<br>“Faster tests, better decisions” |
| Support | Explain the mechanism behind the benefit and the user's recovered time or control. | 15–40 words | “Track renewals, restores, refunds, upgrades, downgrades, billing retries, and expirations without building a complex state machine.” |
| Primary action | Short imperative with a low-friction destination. | 2–4 words | “Start for free”<br>“Talk to us” |
| Secondary action | Name the resource or the next investigation explicitly. | 3–7 words | “See the docs”<br>“Learn about no-code experimentation” |
| Pricing promise | Defuse a commercial objection with plain parallel clauses. | 7–12 words | “No plans, no gates. Pay for what you track.” |
| Closing invitation | A brief question with a direct action and reassuring support. | 3–6 words | “Ready to grow?” |

**Words and phrasing to use:** build; grow; launch; without building; source of truth; get started; full picture; in real time; tools; your team

**Avoid:** revolutionary; unleash limitless potential; world-changing magic; enterprise-grade synergy; guaranteed growth

**Rules:**

- Put the benefit in the heading and the actual workflow in the support.
- Use technical nouns where they help readers evaluate fit, not as decorative jargon.
- For proof, specify the metric and the outcome in a single readable statement.
- Make link text identify the next step rather than repeating Learn more everywhere.

## Do's and Don'ts

### Do

- Keep large headings at weight 500 with -0.04em tracking and 1.125 line height.
- Pair 20px explanatory text with 40px split headings; keep centered chapter support within 672px.
- Use 16px card corners and 1px pale borders for the main card families.
- Stage white UI panels in overlapping layers with diffuse cool shadows.
- Keep 32px grid gaps even when illustration content is intricate.
- Use the 210px logo plinth and short outcome sentence to punctuate long capability explanations.
- Use light 48px metrics and light 80px ratings as distinct proof roles.
- Give the closing invitation 160px of vertical breathing room and follow it with the useful directory.

### Don't

- Do not make the primary action coral; the filled conversion color is periwinkle.
- Do not turn pastel corner light into saturated full-card color blocks.
- Do not set body paragraphs in the geometric display face by default; use the lighter neutral grotesk.
- Do not use bold 80px counters for ratings; the light weight is part of the proof treatment.
- Do not add thick black outlines or hard black drop shadows to floating interfaces.
- Do not force three technical interfaces into equal narrow columns when they need a readable horizontal track.
- Do not turn every secondary action into an outlined pill; chevron links carry that role.
- Do not invert the footer to black or add a giant typographic brand wall after the closing call.

## Motion and responsive

### Motion

**Observed:**

- Color, border and background transitions are declared at 0.3s cubic-bezier(.4,0,.2,1) for most actions; the nested opening action uses 0.2s.
- Trusted-logo scrolling is declared as a 35s linear infinite animation.
- Some media and carousel layers declare opacity transitions at 0.5s cubic-bezier(0.22,1,0.36,1).

**Transfer:**

- Keep interface scenes readable at their resting state; movement should reveal a working workflow rather than carry the entire explanation.
- Use the slow continuous logo treatment for adoption proof and color-only feedback for ordinary links.

**Unknown:**

- Playback schedules for product scenes, carousel automation and scroll-entry choreography are not established.

### Responsive

**Observed:**

- CSS declares breakpoints including 640px, 768px, 992px, 1024px and 1280px.
- Opening layout declares a stacked direction below the xl breakpoint; desktop navigation hides there. Split chapters declare stacking below the md breakpoint.
- Container classes reduce side padding from 32px to 20px or 16px at narrower widths. Pricing headline classes step from 64px to 56px, 40px and 32px.
- Footer classes wrap columns at narrower widths, eventually making each directory group full width.

**Transfer:**

- Retain the workflow stage when stacking the opening; simplify the panel count before shrinking every label.
- Preserve horizontal tracks for technical cards and output galleries instead of making the interfaces illegible.
- Keep the capsule form within the available width and move its action into a separate row if the field no longer has usable writing space.

**Unknown:**

- Exact mobile visual compositions, final line wraps and touch interactions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
