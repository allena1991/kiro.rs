# Sourcegraph — grids and coral signals

## Overview

A technical, high-contrast style with a black architectural canvas, pale grotesk typography and small coral signals. Fine perspective grids and pixel fields make the space feel engineered, while pale geometric artwork and real interfaces provide tangible focal points. It suits complex infrastructure and enterprise products: spacious at the level of the page, compact and information-rich within demonstrations and comparison tables.

### Essentials

- Headlines act as confident, tightly packed statements rather than billboard slogans: Poly Sans 500 at 64px/1.1 with -0.031em tracking, usually broken into two centered lines.
- The opening is a wireframe room with a tangible pale object: a full-width black perspective grid behind a 900px text container and a 576×324px rounded media panel, with the whole composition visible in the first 900px.
- Actions are deliberately smaller than the claims: the opening uses a 34px-high charcoal mono button with 6px corners; recurring conversion buttons use 14px medium sans, 8px corners and 8px 12px padding.
- Color behaves like an instrument signal: most of the page remains black, white and gray; #f34e3f marks the header action, small icons and proof links, with #410604 confined to the 40px announcement strip.
- Technical texture carries the brand between content: use fine low-contrast grid lines and crisp monochrome pixel fields, including a 130px pixel-dissolve transition around a pale content band. Recreate these with SVG lines and square cells when bespoke art is unavailable.
- Proof gets architectural framing rather than decorative badges: 64px compact numerals sit in a three-column ruled strip; a 52px numeral also anchors a charcoal pixel-textured card beside a larger interface.
- A bright reversal interrupts the black canvas: an #ededed capability stage uses stacked 64px/1 headlines, numbered tabs and a 2:1 media/proof pairing; a white conversion band returns to a black, four-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Oxblood announcement | `#410604` | `--color-announcement` | background | Slim announcement strip above navigation. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral signal | `#f34e3f` | `--color-coral` | accent, action, link | Header action, small feature icons, report links and scoped benchmark numerals. |
| Peach announcement text | `#ffcdc3` | `--color-announcement-text` | text | Readable warm text within the oxblood strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale foreground | `#ededed` | `--color-foreground` | text, surface, action | Default display text, pale capability band and primary button fill. |
| Near black canvas | `#020202` | `--color-canvas` | background, text | Default marketing canvas and ink on pale buttons. |
| Raised black | `#0e0e0e` | `--color-panel` | surface | Dark closing panels, quote panels and pricing aside. |
| Ink on pale bands | `#111111` | `--color-light-ink` | text | Capability headlines and tab copy. |
| Dark hairline | `#202020` | `--color-rule` | border, surface | Section rules, active numbered tabs, charcoal proof cards and secondary actions. |
| Opening charcoal | `#222222` | `--color-hero-button` | action | Opening mono action fill. |
| Panel edge | `#343434` | `--color-edge` | border | Stronger outline around product media and dashed tags. |
| Opening action edge | `#3a3a3a` | `--color-hero-edge` | border, text | Opening mono action border and support text on white. |
| Body on pale bands | `#444444` | `--color-light-body` | text | Capability explanations on the light band. |
| Recessed gray | `#606060` | `--color-caption` | text | Trust captions and low-emphasis metadata; not primary paragraphs. |
| Inline explanation gray | `#8a8a8a` | `--color-inline-muted` | text | Continuation of a 28px inline benefit statement on pale surfaces. |
| Opening support gray | `#909090` | `--color-muted` | text | Opening support line and restrained secondary marks. |
| Secondary text | `#a9a9a9` | `--color-body` | text | Body paragraphs and technical labels on black. |
| Light edge | `#d4d4d4` | `--color-light-rule` | border | Pale media and tab borders. |
| Opening action label | `#dedede` | `--color-hero-label` | text | Mono action label on charcoal. |
| Pale media backing | `#f7f7f7` | `--color-light-media` | surface | Backing behind bright interface demonstrations. |
| White | `#ffffff` | `--color-white` | background, surface, text | Bright closing band, inactive capability tabs and reversed button labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| resource cards | Resource black wash | `#0a0a0a` | `--color-resource-surface` | surface | Visible 3% white wash over near black; use rgba(255,255,255,0.03). |
| resource cards | Resource outline | `#161616` | `--color-resource-edge` | border | Visible 8% white outline over near black; use rgba(255,255,255,0.08). |
| product, solution and pricing pages | Warm pale foreground | `#efecec` | `--color-warm-foreground` | text | Headings on product, solution and pricing pages. |

## Typography

- **Poly Sans** — Display, headings, body, navigation and most actions. Compact contemporary grotesk with firm geometric shapes and an approachable, open lowercase. If unavailable, use **Inter**. Use 300–700 weights and preserve the tight display tracking. Font stack: "Poly Sans", "Inter", Arial, sans-serif.
- **Poly Sans Mono** — Technical eyebrows, trust captions, numbered markers and the opening action. Plain technical monospacing used as annotation rather than the dominant voice. If unavailable, use **IBM Plex Mono**. Use light and regular for labels; semibold for the opening action. Font stack: "Poly Sans Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Poly Sans | 500 | 64px | 1.1 | -0.031em | fixed | Default two-line opening promise. |
| display-stack | Poly Sans | 500 | 64px | 1 | -0.031em | size clamp(3rem, 6vw, 4rem) | Stacked capability statements and large proof numerals. |
| heading-lg | Poly Sans | 500 | 56px | 1.15 | -0.031em | size clamp(2.25rem, 5.5vw, 3.5rem) | Major architectural proof heading. |
| proof-number | Poly Sans | 500 | 52px | 1 | -0.031em | size clamp(2.5rem, 5vw, 3.25rem) | Single compact outcome in a pixel-textured proof card. |
| closing-heading | Poly Sans | 500 | 48px | 1.1 | -0.031em | size clamp(2rem, 5vw, 3rem) | Centered headline in a white conversion band. |
| problem-heading | Poly Sans | 500 | 41.6px | 1.28 | -0.01em | size clamp(1.85rem, 4vw, 2.6rem) | Centered problem statement. |
| inline-benefit | Poly Sans | 500 | 28px | 1.18 | -0.018em | fixed | Strong first clause above capability demonstrations. |
| inline-explanation | Poly Sans | 400 | 28px | 1.18 | -0.018em | fixed | Gray continuation on the same line as the inline benefit. |
| hero-support | Poly Sans | 400 | 22px | 1.32 | -0.031em | size clamp(1rem, 2.25vw, 1.375rem) | Centered opening explanation. |
| body | Poly Sans | 400 | 16px | 1.5 | 0.016em | fixed | Default paragraphs, feature descriptions and table content. |
| item-label | Poly Sans | 500 | 16px | 1.5 | normal | fixed | Capability tab headings and FAQ questions. |
| eyebrow | Poly Sans Mono | 400 | 14px | 1.5 | 0.04em, uppercase | fixed | Architectural section labels. |
| trust-caption | Poly Sans Mono | 300 | 14px | 1.5 | 0.018em | fixed | Trust strip captions and quiet technical annotations. |
| action | Poly Sans | 500 | 14px | 1 | 0.018em | fixed | Conversion buttons. |
| navigation | Poly Sans | 400 | 14px | 1.5 | normal | fixed | Navigation dropdown labels. |
| small | Poly Sans | 400 | 14px | 1.5 | 0.018em | fixed | Footer links, announcement copy and compact feature descriptions. |
| hero-action | Poly Sans Mono | 600 | 13px | 1.5 | 0.02em | fixed | Opening charcoal button. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| search product pages | product-display-centered | Poly Sans | 500 | 64px | 1.05 | normal | fixed | Centered opening above a large video. |
| investigative product pages | product-display-left | Poly Sans | 500 | 56px | 1.2 | normal | fixed | Left-aligned text block centered within the content width. |
| solution pages | solution-display | Poly Sans | 500 | 56px | 1.1 | normal | fixed | Three short outcome sentences beside editorial art. |
| pricing pages | pricing-display | Poly Sans | 700 | 56px | 1.2 | normal | fixed | Short centered page title. |
| product and solution pages | heading | Poly Sans | 500 | 40px | 1.2 | normal | fixed | Recurring product and solution section headings. |
| pricing and investigative product pages | pricing-heading | Poly Sans | 700 | 40px | 1.2 | normal | fixed | Plan titles; also used for emphatic FAQ and audience headings. |
| pricing pages | price | Poly Sans | 700 | 40px | 1 | 0.0064em | fixed | Starting price in a plan aside. |
| search product testimonials | testimonial | Poly Sans | 400 | 40px | 1.14 | 0.0064em | fixed | Large multi-line customer quote. |
| pricing pages | pricing-subheading | Poly Sans | 700 | 32px | 1.2 | 0.008em | fixed | Feature table and FAQ headings. |
| benchmark proof sections | benchmark-number | Poly Sans | 500 | 32px | 1 | 0.008em | fixed | Coral before-and-after values with a right arrow. |
| product and solution pages | card-heading | Poly Sans | 500 | 20px | 1.2 | 0.013em | fixed | Outlined capability cards. |
| product and solution pages | lead | Poly Sans | 400 | 20px | 1.5 | 0.013em | fixed | Longer product opening descriptions. |
| product, solution and pricing pages | support | Poly Sans | 400 | 18px | 1.5 | 0.014em | fixed | Section summaries and closing support on black. |
| resource cards | resource-title | Poly Sans | 500 | 18px | 1.2 | 0.014em | fixed | Resource card titles. |
| solution proof chapters | marker | Poly Sans Mono | 400 | 14px | 1.18 | 0.018em | fixed | Small capsule labels attached to long horizontal rules. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default display uses negative tracking equal to 3.1% of the font size; smaller body text retains a slight positive 0.3px tracking. Product and solution templates instead use normal tracking on their major headings.
- Use weight 500 for the default headline system, not bold. Weight 700 belongs to pricing titles and selected utilitarian headings.
- A light capability paragraph can use weight 300 at 16px/1.5; keep its dark gray ink and clear contrast. The 28px inline heading combines a medium black clause and regular gray continuation without changing size.

## Layout

**Density:** Airy architectural sections surround compact controls, tables and demonstrations. Large voids separate narrative chapters without inflating button sizes.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Button vertical padding and small label-to-value gaps. |
| 12px | Card heading-to-body spacing and capability tab gutters. |
| 16px | Eyebrow-to-heading gap and two-column capability card gutters. |
| 24px | Hero text/action rhythm, logo strip gap and closing stack rhythm. |
| 32px | Card padding and three-column feature gutters. |
| 48px | Desktop container side padding, plan aside padding and media separation. |
| 56px | Trust band vertical padding and footer column gutters. |
| 64px | White closing stack vertical padding. |
| 96px | Default product and solution section vertical padding; footer top padding. |
| 144px | Large capability bridge and architectural proof chapter breathing room. |

### Containers and grids

- **main container**: max width 1152px · side padding 48px. Centered outer frame at desktop. With border-box sizing, its inner content is 1056px wide; faint vertical rails align to its outer edges.
- **wide container**: max width 1280px · side padding 48px. Navigation and footer frame.
- **hero copy**: max width 900px · side padding 48px. Centered opening headline; explanatory text narrows to 640px.
- **medium container**: max width 1024px · side padding 48px. FAQ and centered closing panel; inner width 928px.
- **capability pairing**: 2 columns · gap 17.6px. Large interface and smaller proof card in a 2fr 1fr proportion.
- **feature columns**: 3 columns · gap 32px. Unboxed supporting capability explanations.
- **footer columns**: 4 columns · gap 56px. Four compact link columns to the right of the brand and social block.
- **outlined capabilities** (only for product pages): 2 columns · gap 16px. Outlined capability cards, with a final full-width item when needed.
- **pricing split** (only for pricing pages): 2 columns · gap 0px. 2fr 3fr split: a 461px shaded plan aside next to a 691px ruled detail column.
- **solution opening** (only for solution pages): 2 columns · gap 0px. 3fr 2fr split: a 691px text zone beside a 460px full-height illustration.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | conversion buttons and tabs | 8px |
|  | opening mono button | 6px |
|  | media and proof cards | 16px |
|  | opening media | 32px |
|  | annotation capsules | 9999px (pill) |
| resource sections | resource cards | 12px |
| search product testimonials | quote card | 20px |
| investigative product pages | closing panel | 32px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | guide card | `rgba(0, 0, 0, 0.04) 0px 1px 2px 0px` | Barely raised guide card in a white closing band. |
| product demonstrations | product media | `rgba(0, 0, 0, 0.45) 0px 24px 60px -32px` | Subtle depth beneath a large dark media frame. |

### Surfaces

#### Black canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #020202; color: #ededed`

**Observed:** Full-bleed near black, divided by fine dark rules and vertical content rails.

**Transfer:** Keep the page spatial and black rather than turning each chapter into a separate floating card.

#### Pale capability stage · level 0

**Use:** High-contrast capability and demonstration chapter.

**CSS:** `background: #ededed; color: #111111`

**Observed:** A full-width light band bounded by crisp pixel dissolves rather than rounded section containers.

**Transfer:** Use this reversal to make the product's practical value tangible.

#### White closing band · level 0

**Use:** Default late-page conversion reversal.

**CSS:** `background: #ffffff; border-top: 1px solid #202020; color: #020202`

**Observed:** Centered stack and a faint cool glow; a thin rule separates the main call from a smaller guide card.

**Transfer:** Keep it luminous and almost white; match the soft glow without making exact gradient stops important.

#### Media frame · level 1

**Use:** Large interface or product video.

**CSS:** `background: #020202; border: 1px solid #343434; border-radius: 16px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.45) 0px 24px 60px -32px`

**Observed:** A broad landscape window, up to 1056×550px, not a heavily elevated mockup.

**Transfer:** Preserve a readable workflow and real information structure.

#### Pale media frame · level 1

**Use:** Interface within the pale capability stage.

**CSS:** `background: #f7f7f7; border: 1px solid #d4d4d4; border-radius: 16px; overflow: hidden`

**Observed:** 692×360px visual next to a 346×360px proof card.

**Transfer:** Use a bright application view with quiet chrome rather than restyling the application as a black marketing graphic.

#### Dark panel · level 1

**Only for:** investigative product pages

**Use:** Rounded conversion panel within an otherwise black product page.

**CSS:** `background: #0e0e0e; border: 1px solid #202020; border-radius: 32px; padding: 56px 32px`

**Observed:** A 928px-wide panel with centered copy, support and action spaced by 24px.

**Transfer:** Use as the product-page alternative to a full-width white closing band.

## Components

### Navigation

**Use:** Persistent global orientation.

**CSS:** `background: #020202; border-bottom: 1px solid #202020; padding: 0px 48px; height: 63px`

**Text style:** `navigation` — Poly Sans 400 · 14px/1.5

**Observed:** Brand at left, centered compact navigation, coral action at right. The navigation sits below an announcement strip in a sticky 103px combined header; its inner grid has three equal columns.

**Transfer:** Use a short set of broad navigation categories; preserve the balanced center alignment.

### Announcement strip

**Use:** A single timely announcement above the main navigation.

**CSS:** `background: #410604; color: #ffcdc3; height: 40px; padding: 0px 16px; display: flex; align-items: center; justify-content: center`

**Text style:** `small` — Poly Sans 400 · 14px/1.5 · tracking 0.018em

**Observed:** One centered line with a small warm arrow; visually separate from the primary navigation.

### Header action

**Use:** Persistent conversion action.

**CSS:** `background: #f34e3f; color: #ffffff; border-radius: 8px; padding: 8px 12px; display: inline-flex; align-items: center`

**Text style:** `action` — Poly Sans 500 · 14px/1 · tracking 0.018em

**Observed:** Compact filled action at the far right, without a trailing icon.

**States:** Declared: hover background-color #e0443a; focus-visible not specified.

### Primary button

**Use:** Conversion actions in content sections.

**CSS:** `background: #ededed; color: #020202; border: 1px solid #ededed; border-radius: 8px; padding: 8px 12px; display: flex; justify-content: center; align-items: center`

**Text style:** `action` — Poly Sans 500 · 14px/1 · tracking 0.018em

**Observed:** A small pale rectangle. A dark secondary button can sit beside it using the dark hairline color as its fill; the opening has its own mono treatment.

**States:** Declared: hover opacity 0.9; focus-visible not specified.

### Opening mono action

**Use:** Primary action within the perspective-room opening.

**CSS:** `background: #222222; color: #dedede; border: 1px solid #3a3a3a; border-radius: 6px; padding: 6.4px 14.4px; margin-top: 16px`

**Text style:** `hero-action` — Poly Sans Mono 600 · 13px/1.5 · tracking 0.02em

**Observed:** Centered beneath support copy, with a literal right arrow as part of the label.

**States:** Declared: hover background #2e2e2e; focus-visible not specified.

### Numbered capability tab

**Use:** Selecting a benefit and its demonstration within the pale stage.

**CSS:** `background: #ffffff; color: #111111; border: 1px solid #d4d4d4; border-radius: 8px; padding: 10.4px 16px; display: flex; align-items: flex-start; gap: 10.4px`

**Text style:** `item-label` — Poly Sans 500 · 16px/1.5

**Observed:** Outlined circular number at left; title and one-line explanation stacked at right. Three tabs share a row with 12px gutters. Active tab reverses to charcoal with white copy and a thin progress line at its lower edge.

**States:** Declared: hover border-color #b0b0b0; focus-visible not specified.

**Transfer:** Name each tab for a distinct customer outcome, not a product SKU.

### Pixel proof card

**Use:** A compact numeric outcome beside a larger demonstration.

**CSS:** `background: #202020; border-radius: 16px; padding: 32px; display: flex; flex-direction: column; justify-content: flex-end; position: relative; overflow: hidden`

**Text style:** `proof-number` — Poly Sans 500 · 52px/1 · tracking -0.031em

**Observed:** Muted mono attribution above the number and a short result label below. Pixel-wave artwork fills the background, with a dark lower-left gradient protecting the text.

**Transfer:** Use one substantiated number and keep all text anchored near the bottom.

### Guide card

**Use:** Secondary reading invitation below the main closing call.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 16px; padding: 24px 32px; max-width: 640px; display: flex; align-items: center; gap: 24px; box-shadow: rgba(0, 0, 0, 0.04) 0px 1px 2px 0px`

**Text style:** `body` — Poly Sans 400 · 16px/1.5 · tracking 0.016em

**Observed:** A small fanned stack of publication covers precedes one paragraph; the whole card is a link.

**States:** Declared: hover border-color rgba(0, 0, 0, 0.25); focus-visible not specified.

### Footer link

**Use:** Quiet navigation in the shared ending.

**CSS:** `color: #ededed; padding: 4px 0px; opacity: 0.9`

**Text style:** `small` — Poly Sans 400 · 14px/1.5 · tracking 0.018em

**Observed:** Links form four plain columns under small mono category labels; brand, a two-line mono descriptor and social symbols sit to the left. A sparse low-contrast legal row sits near the bottom.

**States:** Declared: hover opacity 1; focus-visible not specified.

### Capability card

**Only for:** product and solution pages

**Use:** Concrete use cases in a product chapter.

**CSS:** `border: 1px solid #202020; border-radius: 16px; padding: 32px; display: flex; flex-direction: column; gap: 12px`

**Text style:** `card-heading` — Poly Sans 500 · 20px/1.2 · tracking 0.013em

**Observed:** Small coral outline icon, medium heading, then one gray paragraph. Two columns sit on black; a wider final card can span both.

### FAQ row

**Only for:** pricing and investigative product pages

**Use:** Objection handling before conversion or the footer.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 24px; padding: 20px 0px; color: #ededed`

**Text style:** `item-label` — Poly Sans 500 · 16px/1.5

**Observed:** Full-width text button with a small down-chevron at the far right. A 1px dark rule on the enclosing row creates a 65px repeated rhythm.

**States:** Declared: hover opacity 0.8; focus-visible not specified.

### Resource card

**Only for:** resource sections

**Use:** Related reading and supporting research.

**CSS:** `background: rgba(255, 255, 255, 0.03); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 12px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `resource-title` — Poly Sans 500 · 18px/1.2 · tracking 0.014em

**Observed:** Landscape art occupies the top half; below it a coral uppercase mono content type, compact title and a low-positioned Read now link with chevron. Three cards use 16px gutters.

**States:** Declared: hover border-color rgba(255, 255, 255, 0.15); focus-visible not specified.

## Imagery and graphics

### Perspective room

**Use:** Signature architectural setting for the main opening.

**Observed:** A black box-like space with fine gray lines converging toward a central rear plane, faint dots at intervals and a flat gridded back wall. The image extends edge to edge behind centered copy and a pale media panel.

**Transfer:** Retain this technical room even without custom media; place a simple product workflow plate in its center rather than substituting generic stock photography.

**Build:** Recommended SVG construction: draw a central rectangular back wall roughly 45% of viewport width and height; join its corners and subdivisions to the outer frame with 1px strokes in rgba(237,237,237,0.10). Add horizontal and vertical subdivisions on the rear plane, then sparse 2px dots in rgba(237,237,237,0.18). Clip to the hero and keep the headline region low contrast.

### Pixel dissolve and wave

**Use:** Signature section transitions, proof textures and architectural data bands.

**Observed:** Crisp square cells accumulate into pale fields at a black-to-light boundary. Long proof bands use sparse gray pixels at left, denser irregular clusters at right; the charcoal outcome card uses a diagonal, fabric-like pixel wave.

**Transfer:** Include a pixel-texture device on every new landing page. Use a square-cell dissolve or data band if bespoke wave art is unavailable.

**Build:** Recommended SVG construction: use a 6px square lattice with small gutters, filling cells in pale gray at variable opacity. For a 130px transition, increase occupancy toward the light-band edge until the field becomes solid. For a proof band, modulate occupancy with two overlapping sine waves and increase density toward the right; use no blur on cells. Fade the lower-left of a card with a charcoal-to-transparent gradient to protect copy.

### Product demonstrations

**Use:** Primary tangible proof after a promise and inside capability chapters.

**Observed:** Large landscape views show a real workflow: bright question-and-answer panels with source citations, or dark search/code views with colored syntax and sidebars. Broad views occupy much more area than accompanying prose; supporting close-ups isolate a search bar, hovercard or result counter.

**Transfer:** Use genuine interfaces from the new product or a faithful purposeful workflow mockup. Show enough data to communicate the operation; retain restrained application chrome and use the Media frame or Pale media frame.

### Geometric campaign plate

**Only for:** launch campaigns

**Use:** Pale launch video poster or large editorial tile.

**Observed:** Black outlined squares repeat along curling ribbon-like paths on a pale gray plate. Coral arrows and polygon bursts punctuate the paths; black sans copy and mono captions remain centered in open space. The plate has broad rounded corners.

**Transfer:** Use an original repeated-shape system that suggests the new product's operations, keeping the pale backing, thin black outlines and very limited coral accents.

**Build:** Recommended SVG construction: place 40–70 small pale rectangles with 1px black outlines along two or three bezier paths; rotate successive rectangles with each tangent to create a ribbon. Add two flat coral arrowheads or polygons at turns, leaving the central third open for copy. Clip the plate to a 32px radius.

### Monochrome maze with coral light

**Only for:** solution pages

**Use:** Tall opening illustration and related editorial artwork.

**Observed:** An isometric maze of pale walls with thin black outlines fills an edge-cropped vertical panel. Small black balls and rounded black capsules imply movement; local coral glows punctuate corners and paths.

**Transfer:** Create an original systems diagram or maze with the same hard geometry and localized warm illumination, not a generic glossy 3D object.

**Build:** Recommended SVG construction: extrude an orthogonal path network diagonally upward with pale polygon walls and 1px dark strokes. Scatter a few black circles and capsules; behind two or three objects add coral radial ellipses at 25–40% alpha with 20–40px blur. Crop the network at all four edges.

### Publication artwork

**Only for:** resource and guide sections

**Use:** Reading cards and the guide invitation.

**Observed:** Resource images mix printed report covers, black-and-pale grids, repeated rounded bars, and maze art. Coral is restricted to a few geometric marks or light patches. The guide card shows a small fanned cover stack with a soft shadow.

**Transfer:** Produce original editorial covers in the same geometric vocabulary, with readable short titles and a limited black/pale/coral palette.

**Build:** Recommended construction: use a pale rectangular cover with black grotesk title and a repeated geometric band; layer two offset copies behind it for the guide stack. For alternative thumbnails, alternate black and pale rounded bars with one coral bar and a few circular end caps.

### Icons

**Observed:** Most feature icons are 24×24px outline SVGs with 1.5px round strokes, in gray or coral. Compact controls use 16px marks. Social icons are solid 32×32px symbols; pricing checks are small outlined circles rather than oversized badges.

**Transfer:** Choose restrained line icons for functions and filled recognizable symbols for social destinations. Align feature icons to the start of the heading or place them directly above it.

## Section recipes

How recurring sections are built.

### First screen: Perspective product opening

**Observed:** The first 900px contains the combined 103px sticky header, a full-width Perspective room, centered two-line display promise, a two-line support paragraph, the Opening mono action and a complete 576×324px pale video panel. The text sits in the upper half of the room in a 900px container, its headline spanning roughly two thirds of that width; support narrows to 640px. Background grid and faint dots sit behind the copy, then the rounded media object sits beneath it as the tangible focal point. The headline is 64px/1.1, weight 500, with -0.031em tracking. The room continues as a pinned launch scene below the first screen; the trust strip is below this extended opening rather than competing with the initial composition.

**Transfer:** For a different product, preserve the dark room, emphatic centered promise and tangible pale object. Without launch video, make an original diagram plate or a framed product workflow with one clear interaction. Product pages can instead open with a centered 64px heading above a broad demo or a left-aligned 56px heading in a centered 672px block; solution pages split text and tall geometric art 3:2. Pricing uses a compact 56px bold title over faint pixel texture.

**Avoid:** Do not replace the room with a flat generic dark hero, let art obscure the copy, or enlarge the action into a pill that competes with the headline.

**Text style:** `display` — Poly Sans 500 · 64px/1.1 · tracking -0.031em

### Trust strip

**Observed:** A centered trust-caption sits above a horizontally arranged set of desaturated customer marks, with a 24px gap and generally 48–56px vertical breathing room. Marks remain modest and share optical height rather than identical widths.

**Transfer:** Use authentic partner or customer proof with quiet monochrome treatment; if those are unavailable, use a factual trust statement rather than invented logos.

### Problem statement

**Observed:** A narrow centered block uses an eyebrow, a 41.6px/1.28 problem-heading, a brief gray paragraph and compact outlined capsules. The section uses 96px top and 144px bottom padding before a pixel transition.

**Transfer:** Name a concrete tension in short parallel phrases; capsules summarize consequences rather than becoming another feature grid.

**Text style:** `problem-heading` — Poly Sans 500 · 41.6px/1.28 · tracking -0.01em

### Bright capability stage

**Observed:** The Pale capability stage begins with three centered stacked display-stack statements and a support line. Numbered capability tabs lead into a 28px inline benefit/explanation pair, then a 2:1 Pale media frame and Pixel proof card pairing. Three unboxed icon-and-copy columns sit below. Major top and bottom space reaches 144px.

**Transfer:** Translate product features into three outcome lenses; keep the light reversal and pixel boundary even when the number of benefits changes.

**Text style:** `display-stack` — Poly Sans 500 · 64px/1 · tracking -0.031em

### Architectural quantified proof

**Observed:** An eyebrow and heading-lg align left, while a short body summary aligns at right. Monochrome pixel bands bracket a three-column strip with 64px/1 numbers, 16px supporting labels and fine vertical dividers; trust details form an unboxed three-column grid below.

**Transfer:** Use real quantified outcomes with compact explanatory labels; if numerical proof is unavailable, use equally concise verified milestones without manufacturing statistics.

**Text style:** `heading-lg` — Poly Sans 500 · 56px/1.15 · tracking -0.031em

### Conversion and footer endings

**Observed:** The default ending uses the White closing band with a centered 48px heading, short support, Primary button and Guide card beneath a divider, then the black footer. Product variants stay black: a 928px Dark panel centers the call, or a small pixel emblem sits beside a bold call. Solution endings are left-aligned with paired actions. Every ending returns to the same 503px black footer with 96px top padding, brand/social block, four link columns and a low legal row.

**Transfer:** Choose the ending appropriate to the page's level of explanation, but retain a decisive final invitation and the structured footer. A pricing ledger can end directly at the footer after FAQs.

**Text style:** `closing-heading` — Poly Sans 500 · 48px/1.1 · tracking -0.031em

### Outlined use cases

**Only for:** product pages

**Observed:** A coral technical eyebrow and 40px heading introduce two columns of Capability cards separated by 16px. Each card contains a small outline icon, 20px heading and 16px paragraph. A final item can span the row.

**Transfer:** Choose concrete tasks and describe what changes for the user rather than listing abstract qualities.

**Text style:** `heading` — Poly Sans 500 · 40px/1.2

### Heading beside ruled capabilities

**Only for:** product and solution pages

**Observed:** A 40px heading and summary occupy the left half; the right half contains short icon-led explanations separated by hairlines. Platform cross-links use a similar left title/right rows construction, with a vertical dividing rule and 32px inset.

**Transfer:** Use this asymmetric chapter for mechanism, differentiation or an ecosystem of related capabilities.

**Text style:** `heading` — Poly Sans 500 · 40px/1.2

### Two-column quote proof

**Only for:** investigative product pages

**Observed:** Two quotes use 20px text with 29px leading, coral quotation marks and uppercase 14px attributions; each quote is defined by a left hairline rather than a filled card. The section uses 96px vertical padding.

**Transfer:** Pair two distinct verified perspectives, keeping attributions separate from the quote body.

### Large quote panel

**Only for:** search product pages

**Observed:** A 992px-wide Dark panel variant with 20px corners and 32px padding sits over a fine grid-and-stars background. A 40px regular testimonial dominates; a smaller muted attribution follows.

**Transfer:** Let one substantive customer observation carry the entire panel; keep the grid secondary.

**Text style:** `testimonial` — Poly Sans 400 · 40px/1.14 · tracking 0.0064em

### Task ticker

**Only for:** investigative product pages

**Observed:** Two edge-clipped rows of mono task tags run across a 140px black band with top and bottom rules. Tags have 8px corners, 1px dashed outlines and 8px 16px padding; edge fades soften the overflow.

**Transfer:** Use short examples of workflows, not generic brand adjectives, and retain the two-row technical-label feel.

### Sticky plan and detail ledger

**Only for:** pricing pages

**Observed:** A compact textured title and trust strip precede the Pricing split. A shaded plan aside keeps its 48px-padded summary, starting price, action and checklist visible while the larger detail ledger scrolls. The right column has category headers, 53px ruled feature rows and right-aligned circular checks or tiny optional tags. FAQs end the ledger, then the shared black footer begins directly; there is no separate conversion banner.

**Transfer:** Use this when one enterprise offer needs substantial explanation. Keep inclusions, commercial terms and questions in one coherent ledger rather than inventing a three-tier comparison.

**Text style:** `pricing-heading` — Poly Sans 700 · 40px/1.2

### Benchmark and comparison chapter

**Only for:** solution proof pages

**Observed:** Small mono capsule markers attach to long rules above 40px headings and 18px summaries. Three coral 32px before-and-after values share an outlined container. Subsequent horizontal charts use thin coral bars against gray alternatives and mono numeric labels. Paired dark demonstration windows show the same task under two conditions, with restrained red/green result summaries.

**Transfer:** Use fair, explicit comparisons and label baselines. Preserve equal window widths and equivalent prompts; keep detailed application styling inside the demonstration rather than spreading it across the marketing page.

**Text style:** `heading` — Poly Sans 500 · 40px/1.2

### Resource grid

**Only for:** resource sections

**Observed:** A 40px section heading leads into three Resource cards with 16px gutters, each approximately 341×368px. Art is landscape and aligned along one top edge; titles remain compact.

**Transfer:** Show a small curated group with varied geometric cover art and a consistent card frame.

**Text style:** `heading` — Poly Sans 500 · 40px/1.2

## Page flow

**Storyline:** Promise → tangible demonstration → trust → problem or mechanism → capabilities and substantiated proof → questions or further reading → decisive invitation → structured footer.

### Broad platform or marketing landing page

1. **promise** — Perspective room, centered two-line claim and pale media object, expanding into a launch scene.
2. **social proof** — Monochrome logo strip with a mono caption.
3. **problem framing** — Centered parallel problem statement and consequence capsules.
4. **capability chapters** — Pixel dissolve into a pale stage with stacked outcomes, numbered tabs, demonstration and a proof card.
5. **quantified proof** — Dark architectural statistics and trust details between pixel bands.
6. **closing call** — White conversion reversal with guide card, followed by the black footer.

**Transfer:** Use the broadest product promise first, then make complexity concrete through a demonstration and a few clear outcome lenses.

### Enterprise pricing and commercial explanation

1. **orientation** — Short centered bold title over faint pixels.
2. **social proof** — Compact monochrome logo band.
3. **pricing** — Sticky shaded plan aside beside a longer ruled capabilities ledger.
4. **objection handling** — FAQ rows in the ledger's content column.
5. **ending** — Direct transition to the shared black footer without another sales banner.

**Transfer:** Support a single considered purchase with transparent inclusion details and commercial questions.

### Established product capability landing page

1. **promise** — Centered 64px product promise and paired actions.
2. **product demonstration** — Large dark workflow video with coral play control.
3. **social proof** — Monochrome logos.
4. **capability chapters** — Ruled search feature grid, large quote panel, compact scale/compatibility pair and full-width interface.
5. **mechanism** — Navigation capabilities and a close-up interface detail.
6. **closing call** — Pixel emblem beside a bold call, then the shared black footer.

**Transfer:** Use this path for a product whose speed and exact workflow can be shown directly.

### New or explanatory product landing page

1. **promise** — Small product label, left-aligned 56px claim within a centered text block, support and action.
2. **product demonstration** — Broad bright workflow video within a dark outlined frame.
3. **capabilities** — Outlined use-case cards followed by two attributed quotes.
4. **differentiation** — Heading beside a ruled mechanism list, then two rows of dashed task tags.
5. **ecosystem and audience** — Related capability rows and a short centered audience statement.
6. **objection handling** — Wide FAQ list.
7. **closing call** — Centered rounded dark conversion panel, then shared footer.

**Transfer:** Explain what a novel product does, why its mechanism matters and who can benefit before asking for the demo.

### Evidence-led solution page

1. **promise** — Outcome-led text beside pale maze artwork.
2. **social proof** — Quiet monochrome customer marks.
3. **quantified proof** — Coral before-and-after statistics and relative time/cost charts.
4. **problem demonstration** — Equal-condition paired workflow windows and explicit result comparison.
5. **capability chapters** — Three unboxed task explanations and ruled platform links.
6. **further reading** — Three geometric resource cards.
7. **closing call** — Left-aligned heading, support and paired actions, then shared black footer.

**Transfer:** Lead with the outcome and then substantiate it through fair comparisons, not a longer generic feature list.

## Writing

Confident and technical, but direct rather than ceremonial. Claims are linked to mechanisms, concrete tasks or explicitly framed proof; urgency comes from the cost of missing understanding, not from hype.

**Do not copy:** Do not reuse Sourcegraph names, logos, artwork, customer marks, quotations, pricing, benchmark values, security claims or performance promises. Examples show structure and tone only; replace them with original content and substantiated facts.

- **Addressing the reader:** Speak to the reader as you and your, especially about their system and team. Use the product name to explain its mechanism; use we sparingly, chiefly for straightforward capability reassurance.
- **Rhythm:** Short parallel headline clauses alternate with one- or two-sentence explanations. Outcome statements often use periods to create a three-beat cadence. Actions are usually two to four words; supporting technical prose can be longer when it explains how something works.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the foundational role of the product in the reader's whole system. | 8–12 words | “The context layer for your entire codebase” |
| Outcome headline | Three comparative improvements, each stated as a short sentence. | 6–9 words | “Higher accuracy. Faster execution. Fewer tokens.” |
| Problem heading | Parallel increase/increase/consequence phrasing. | 6–9 words | “More code. More agents. Less understanding.” |
| Mechanism support | Explain the technical cause of a benefit, then the way it can be verified. | 12–25 words | “Agent reasoning over your indexed code graph, with sources you can verify at every step.” |
| Capability heading | Start with a task verb and a tangible object. | 3–7 words | “Understand legacy code”<br>“Find what was never written down” |
| Primary action | Plain invitation to a concrete next step. | 2–4 words | “Schedule a demo”<br>“Request a demo” |
| Proof caption | Explain what is measured and name its baseline or conditions. | 10–25 words | “Precision@5 with [Brand] MCP vs. a local grep/file baseline (CodeScaleBench, 370 tasks)” |

**Words and phrasing to use:** understand; across; at scale; exact; trace; grounded; verify; complete; confidence; faster

**Avoid:** revolutionary; magical; game-changing; limitless; supercharge everything; effortlessly transform

**Rules:**

- Make the opening about the customer's whole problem, then use feature copy to explain a precise operation.
- Prefer contrasts such as minutes versus hours or real answers versus guessing, but only when justified.
- Keep technical terms when they identify a mechanism; define unfamiliar terms in adjacent prose.
- Put conditions, baselines and attribution beside quantitative claims rather than hiding them in vague footnotes.
- Use concise sentence-case headings and plain action labels; reserve uppercase for technical labels and content types.

## Do's and Don'ts

### Do

- Keep the default opening at 64px/1.1, weight 500 and -0.031em tracking.
- Use the 1152px outer content frame with 48px internal side padding at desktop.
- Pair a broad interface with a smaller proof card in a 2:1 ratio and a 17.6px gap.
- Use 1px #202020 rules to express section and column structure on black.
- Keep conversion controls compact: 14px type, 8px 12px padding and 8px corners.
- Include a crisp pixel field or dissolve and a fine architectural grid as recognisable technical devices.
- Use 96px chapter padding and 144px around the broad capability bridge.
- End a broad landing page with a white conversion reversal before the black four-column footer.

### Don't

- Do not use a blue-purple gradient as the default canvas; the principal field is #020202.
- Do not make all buttons coral; coral belongs primarily to the persistent header action and selective signals.
- Do not apply 700 weight to the default display system; that emphasis belongs to scoped utilitarian headings.
- Do not round entire content sections into floating cards; use straight full-width bands and ruled subdivisions.
- Do not enlarge every interface to cover the entire viewport; preserve the 1056px inner frame and readable adjacent explanation.
- Do not blur the pixel-dissolve cells into soft noise; their crisp square construction is the point.
- Do not use the muted #606060 caption color for primary explanatory paragraphs; use #a9a9a9 on black.
- Do not turn the footer into a bright campaign graphic or giant wordmark; keep its compact link columns and 96px top inset.

## Motion and responsive

### Motion

**Observed:**

- Declared opening word animation: 0.6s cubic-bezier(0.16, 1, 0.3, 1), forwards. Support and action use 0.8s ease fade-ins with 0.55s and 0.7s delays.
- Declared marquee durations include 80s and 38s, linear and infinite.
- Declared interaction transitions are predominantly opacity 0.2s, background-color 0.2s and border-color 0.2s. The capability tab has a linear progress animation.
- The opening uses a pinned scene that changes from the broad promise to a launch announcement while the media panel grows. Some stacked headline lines transition through blur.

**Transfer:**

- Keep the opening promise readable before advancing to the launch scene.
- Use slow continuous motion for technical tickers and restrained short transitions for controls; never animate the pixel device into a distracting full-screen effect.

**Unknown:**

- The exact scroll interpolation, tab timing and full motion choreography are not specified.
- Focus-visible styling beyond the listed declared states is not established.

### Responsive

**Observed:**

- Declared width breakpoints are 376px, 768px and 1200px.
- Several broad landing-page type roles use the supplied clamp formulas rather than a fixed desktop size.

**Transfer:**

- Recommended narrow-screen adaptation: preserve the grid-room impression while reducing line density and stacking the media beneath the promise.
- Recommended narrow-screen adaptation: stack the 2:1 demonstration pairing, solution text/art split and pricing ledger; release the plan aside from sticky positioning.
- Keep headline, support and compact action ahead of artwork, and preserve pixel boundaries between light and dark chapters.

**Unknown:**

- Only desktop layouts are established; mobile navigation arrangement, exact padding changes and breakpoint-specific stacking behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
